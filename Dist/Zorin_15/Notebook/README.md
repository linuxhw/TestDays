Zorin 15 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 15.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ Kernel                   ](#kernel)
  - [ Kernel Family            ](#kernel-family)
  - [ Kernel Major Ver.        ](#kernel-major-ver)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linuxbsd)
  - [ Dual Boot (Win)          ](#dual-boot-win)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Secure Boot              ](#secure-boot)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Op-Modes             ](#cpu-op-modes)
  - [ CPU Microcode            ](#cpu-microcode)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 1423

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Compaq 6730s                | [5d805b2f5e](https://linux-hardware.org/?probe=5d805b2f5e) | Jul 31, 2022 |
| Dell          | Inspiron 1525               | [f1af5f5e45](https://linux-hardware.org/?probe=f1af5f5e45) | Jul 22, 2022 |
| Dell          | Inspiron 1525               | [6c43e1dfd6](https://linux-hardware.org/?probe=6c43e1dfd6) | Jul 22, 2022 |
| Dell          | MXG061                      | [9301162b93](https://linux-hardware.org/?probe=9301162b93) | Jul 18, 2022 |
| HP            | ENVY 17                     | [bc1e8b41a5](https://linux-hardware.org/?probe=bc1e8b41a5) | Jul 17, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| Fujitsu Si... | AMILO L Series              | [410cd1aeec](https://linux-hardware.org/?probe=410cd1aeec) | Jul 08, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | [f11f4826ba](https://linux-hardware.org/?probe=f11f4826ba) | Jul 08, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | [50e02d8554](https://linux-hardware.org/?probe=50e02d8554) | Jul 08, 2022 |
| ASUSTek       | K70IC                       | [baa2ddeb5a](https://linux-hardware.org/?probe=baa2ddeb5a) | Jul 08, 2022 |
| ASUSTek       | ZenBook UX392FN_UX392FN     | [b4699ba106](https://linux-hardware.org/?probe=b4699ba106) | Jun 30, 2022 |
| Dell          | Latitude E6400              | [df93b48c3c](https://linux-hardware.org/?probe=df93b48c3c) | Jun 28, 2022 |
| Acer          | Aspire A315-42              | [57d9c7c28a](https://linux-hardware.org/?probe=57d9c7c28a) | Jun 24, 2022 |
| Dell          | Latitude E6400              | [6198dd2784](https://linux-hardware.org/?probe=6198dd2784) | Jun 22, 2022 |
| HP            | Pavilion Notebook           | [551da1dbb6](https://linux-hardware.org/?probe=551da1dbb6) | Jun 20, 2022 |
| Acer          | TravelMate 5320             | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| HP            | Pavilion 17                 | [a3f1fe480c](https://linux-hardware.org/?probe=a3f1fe480c) | May 14, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| Lenovo        | ThinkPad L412 440332U       | [6616ce20ee](https://linux-hardware.org/?probe=6616ce20ee) | Apr 28, 2022 |
| Acer          | Aspire 9410                 | [f6c795c09a](https://linux-hardware.org/?probe=f6c795c09a) | Apr 20, 2022 |
| HP            | Notebook                    | [b746d96b41](https://linux-hardware.org/?probe=b746d96b41) | Apr 19, 2022 |
| Dell          | Latitude E6410              | [391866815a](https://linux-hardware.org/?probe=391866815a) | Apr 17, 2022 |
| Packard Be... | EasyNote TN36               | [23936e29bb](https://linux-hardware.org/?probe=23936e29bb) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | [ae514187f2](https://linux-hardware.org/?probe=ae514187f2) | Apr 15, 2022 |
| HP            | Laptop 14-cm0xxx            | [d6463e4014](https://linux-hardware.org/?probe=d6463e4014) | Apr 14, 2022 |
| HP            | Presario C500 (GF852EA#A... | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | [4864fcdfa0](https://linux-hardware.org/?probe=4864fcdfa0) | Apr 07, 2022 |
| Panasonic     | CF-31ACJAXPM                | [c90a918208](https://linux-hardware.org/?probe=c90a918208) | Mar 28, 2022 |
| ASUSTek       | K70IC                       | [25066676e9](https://linux-hardware.org/?probe=25066676e9) | Mar 28, 2022 |
| ASUSTek       | K70IC                       | [977e15d60c](https://linux-hardware.org/?probe=977e15d60c) | Mar 28, 2022 |
| Acer          | Aspire 3690                 | [76139c48e8](https://linux-hardware.org/?probe=76139c48e8) | Mar 25, 2022 |
| BGH e-Nova    | Unknown                     | [408be10e82](https://linux-hardware.org/?probe=408be10e82) | Mar 22, 2022 |
| Acer          | Unknown                     | [3c80f8700c](https://linux-hardware.org/?probe=3c80f8700c) | Mar 19, 2022 |
| Toshiba       | Satellite M505              | [924c539075](https://linux-hardware.org/?probe=924c539075) | Mar 12, 2022 |
| Dell          | Inspiron MM061              | [ad5413d163](https://linux-hardware.org/?probe=ad5413d163) | Mar 06, 2022 |
| HP            | ProBook 445 G7              | [b0b810cf14](https://linux-hardware.org/?probe=b0b810cf14) | Mar 04, 2022 |
| HP            | 255 G5                      | [050e7b02e7](https://linux-hardware.org/?probe=050e7b02e7) | Feb 28, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [d5c0be1b13](https://linux-hardware.org/?probe=d5c0be1b13) | Feb 27, 2022 |
| ASUSTek       | S500CA                      | [db6a143f17](https://linux-hardware.org/?probe=db6a143f17) | Feb 27, 2022 |
| Fujitsu       | FARQ0200GZ                  | [a309120953](https://linux-hardware.org/?probe=a309120953) | Feb 26, 2022 |
| ASUSTek       | S500CA                      | [d8941a4a85](https://linux-hardware.org/?probe=d8941a4a85) | Feb 25, 2022 |
| HP            | 2140                        | [ad18e8d0b3](https://linux-hardware.org/?probe=ad18e8d0b3) | Feb 22, 2022 |
| HP            | 2140                        | [e0757f087f](https://linux-hardware.org/?probe=e0757f087f) | Feb 22, 2022 |
| Sony          | VPCEH3L1E                   | [4fa6aebb55](https://linux-hardware.org/?probe=4fa6aebb55) | Feb 21, 2022 |
| HP            | Notebook                    | [aee3f5ce0b](https://linux-hardware.org/?probe=aee3f5ce0b) | Feb 18, 2022 |
| ATI           | BONEFISH                    | [caa7c41c75](https://linux-hardware.org/?probe=caa7c41c75) | Feb 17, 2022 |
| Lenovo        | ThinkPad T61 6458CTO        | [9081d7a51d](https://linux-hardware.org/?probe=9081d7a51d) | Feb 17, 2022 |
| Lenovo        | ThinkPad T61 6458CTO        | [4f0437053f](https://linux-hardware.org/?probe=4f0437053f) | Feb 17, 2022 |
| HP            | Compaq 6910p (GR670ET#UU... | [f21dcf572e](https://linux-hardware.org/?probe=f21dcf572e) | Feb 13, 2022 |
| HP            | Compaq 6910p (GR670ET#UU... | [7f07e2a9da](https://linux-hardware.org/?probe=7f07e2a9da) | Feb 13, 2022 |
| Dell          | Inspiron 1525               | [3db88da0ec](https://linux-hardware.org/?probe=3db88da0ec) | Feb 13, 2022 |
| Dell          | Inspiron 1545               | [feafacf00d](https://linux-hardware.org/?probe=feafacf00d) | Feb 13, 2022 |
| HP            | 255 G5                      | [a030b8f406](https://linux-hardware.org/?probe=a030b8f406) | Feb 13, 2022 |
| HP            | Compaq 6530b (NA755ES#AB... | [5bc4fdcfb0](https://linux-hardware.org/?probe=5bc4fdcfb0) | Feb 13, 2022 |
| Dell          | Inspiron 1545               | [00d31012f1](https://linux-hardware.org/?probe=00d31012f1) | Feb 12, 2022 |
| Acer          | Aspire 5600                 | [35dd7239e3](https://linux-hardware.org/?probe=35dd7239e3) | Feb 06, 2022 |
| Acer          | Aspire 5600                 | [4d2723a19e](https://linux-hardware.org/?probe=4d2723a19e) | Feb 06, 2022 |
| BenQ          | Joybook Lite U121           | [28f254dd8d](https://linux-hardware.org/?probe=28f254dd8d) | Feb 02, 2022 |
| Toshiba       | Satellite Pro C660          | [8be575e86a](https://linux-hardware.org/?probe=8be575e86a) | Feb 01, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7db720ba39](https://linux-hardware.org/?probe=7db720ba39) | Feb 01, 2022 |
| Dell          | Inspiron 5567               | [0e47f03d64](https://linux-hardware.org/?probe=0e47f03d64) | Jan 24, 2022 |
| Toshiba       | Satellite Pro C660          | [49c83041f3](https://linux-hardware.org/?probe=49c83041f3) | Jan 24, 2022 |
| Toshiba       | Satellite M505              | [9356dfa5a9](https://linux-hardware.org/?probe=9356dfa5a9) | Jan 20, 2022 |
| WinSome       | A14C .B005                  | [d685b78944](https://linux-hardware.org/?probe=d685b78944) | Jan 19, 2022 |
| TWC           | Unknown                     | [85a8fd2cf1](https://linux-hardware.org/?probe=85a8fd2cf1) | Jan 18, 2022 |
| Dell          | Inspiron 5567               | [4b51693e30](https://linux-hardware.org/?probe=4b51693e30) | Jan 17, 2022 |
| TWC           | Unknown                     | [d4cc69cea7](https://linux-hardware.org/?probe=d4cc69cea7) | Jan 16, 2022 |
| Dell          | Inspiron 1545               | [a6c2013bf1](https://linux-hardware.org/?probe=a6c2013bf1) | Jan 15, 2022 |
| eMachines     | G625                        | [1c60347748](https://linux-hardware.org/?probe=1c60347748) | Jan 07, 2022 |
| Packard Be... | EasyNote MZ35               | [63281c8766](https://linux-hardware.org/?probe=63281c8766) | Jan 06, 2022 |
| Packard Be... | EasyNote MZ35               | [205f3bc0b9](https://linux-hardware.org/?probe=205f3bc0b9) | Jan 06, 2022 |
| Toshiba       | Satellite Pro C660          | [4d080d5d7a](https://linux-hardware.org/?probe=4d080d5d7a) | Jan 03, 2022 |
| eMachines     | G625                        | [03810742ed](https://linux-hardware.org/?probe=03810742ed) | Jan 03, 2022 |
| Lenovo        | ThinkPad T540p 20BFS5630... | [e1e090d622](https://linux-hardware.org/?probe=e1e090d622) | Jan 02, 2022 |
| eMachines     | G625                        | [e3f96637bb](https://linux-hardware.org/?probe=e3f96637bb) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 1294BL5         | [2cd6f5fbb0](https://linux-hardware.org/?probe=2cd6f5fbb0) | Jan 01, 2022 |
| HP            | Unknown                     | [acd2b01673](https://linux-hardware.org/?probe=acd2b01673) | Dec 31, 2021 |
| HP            | Unknown                     | [8f2ecbe94d](https://linux-hardware.org/?probe=8f2ecbe94d) | Dec 31, 2021 |
| Dell          | Latitude D420               | [3caac63d5f](https://linux-hardware.org/?probe=3caac63d5f) | Dec 31, 2021 |
| HP            | ZBook 15u G3                | [e220b55c78](https://linux-hardware.org/?probe=e220b55c78) | Dec 30, 2021 |
| HP            | Pavilion dv6700             | [ce62bcd9b0](https://linux-hardware.org/?probe=ce62bcd9b0) | Dec 28, 2021 |
| HP            | 255 G5                      | [0bf7bc5435](https://linux-hardware.org/?probe=0bf7bc5435) | Dec 28, 2021 |
| HP            | Laptop 14-dk1xxx            | [31fbadcc88](https://linux-hardware.org/?probe=31fbadcc88) | Dec 28, 2021 |
| HP            | ZBook 15u G3                | [f770dacb13](https://linux-hardware.org/?probe=f770dacb13) | Dec 25, 2021 |
| Acer          | Aspire 5250                 | [bef8e4334a](https://linux-hardware.org/?probe=bef8e4334a) | Dec 23, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [8f7a53f316](https://linux-hardware.org/?probe=8f7a53f316) | Dec 20, 2021 |
| Quanta        | MW1/HW1                     | [06bcb3603d](https://linux-hardware.org/?probe=06bcb3603d) | Dec 17, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [b9908b0aa8](https://linux-hardware.org/?probe=b9908b0aa8) | Dec 12, 2021 |
| HP            | Notebook                    | [97e434f4aa](https://linux-hardware.org/?probe=97e434f4aa) | Dec 11, 2021 |
| Packard Be... | EasyNote MH35               | [c5dd11f2bd](https://linux-hardware.org/?probe=c5dd11f2bd) | Dec 08, 2021 |
| Packard Be... | EasyNote MH35               | [87a83af447](https://linux-hardware.org/?probe=87a83af447) | Dec 08, 2021 |
| Lenovo        | S10-3                       | [19cd43f2f7](https://linux-hardware.org/?probe=19cd43f2f7) | Nov 29, 2021 |
| Dell          | Inspiron 14-3452            | [b0fb64bf16](https://linux-hardware.org/?probe=b0fb64bf16) | Nov 27, 2021 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [c23b71e54e](https://linux-hardware.org/?probe=c23b71e54e) | Nov 27, 2021 |
| HP            | Pavilion g7                 | [e8dcea99ad](https://linux-hardware.org/?probe=e8dcea99ad) | Nov 26, 2021 |
| Toshiba       | Satellite L750              | [836cf1ca10](https://linux-hardware.org/?probe=836cf1ca10) | Nov 25, 2021 |
| Toshiba       | Satellite L750              | [827e07a075](https://linux-hardware.org/?probe=827e07a075) | Nov 24, 2021 |
| Fujitsu Si... | AMILO Li1705                | [397611b48d](https://linux-hardware.org/?probe=397611b48d) | Nov 20, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | [d543e2cd80](https://linux-hardware.org/?probe=d543e2cd80) | Nov 19, 2021 |
| HP            | Pavilion dv7                | [33202c35ad](https://linux-hardware.org/?probe=33202c35ad) | Nov 19, 2021 |
| HP            | Pavilion dv7                | [66ec298a1c](https://linux-hardware.org/?probe=66ec298a1c) | Nov 18, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [641218d2e6](https://linux-hardware.org/?probe=641218d2e6) | Nov 16, 2021 |
| HP            | Pavilion dv9500             | [bef50ae82a](https://linux-hardware.org/?probe=bef50ae82a) | Nov 15, 2021 |
| HP            | Compaq nx8220 (PG801ET#A... | [60c7204131](https://linux-hardware.org/?probe=60c7204131) | Nov 14, 2021 |
| Samsung       | 370E4K                      | [f076dae1f9](https://linux-hardware.org/?probe=f076dae1f9) | Nov 12, 2021 |
| Medion        | P8610                       | [122043c04d](https://linux-hardware.org/?probe=122043c04d) | Nov 08, 2021 |
| Medion        | P8610                       | [4d519680a1](https://linux-hardware.org/?probe=4d519680a1) | Nov 07, 2021 |
| ASUSTek       | K42F                        | [a0fc0b335f](https://linux-hardware.org/?probe=a0fc0b335f) | Nov 07, 2021 |
| MAXDATA       | ECO4000IW                   | [5a5fb011c7](https://linux-hardware.org/?probe=5a5fb011c7) | Nov 06, 2021 |
| Apple         | MacBookAir4,1               | [01eb7627e2](https://linux-hardware.org/?probe=01eb7627e2) | Nov 06, 2021 |
| Dell          | XPS M1330                   | [3fcb1bf591](https://linux-hardware.org/?probe=3fcb1bf591) | Nov 06, 2021 |
| Intel         | HURONRIVER                  | [5ded89b4a5](https://linux-hardware.org/?probe=5ded89b4a5) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | [e18dd8b896](https://linux-hardware.org/?probe=e18dd8b896) | Nov 01, 2021 |
| Toshiba       | Satellite U400              | [abcf2eee75](https://linux-hardware.org/?probe=abcf2eee75) | Oct 27, 2021 |
| Acer          | Acadia V1.42                | [01122f69f4](https://linux-hardware.org/?probe=01122f69f4) | Oct 23, 2021 |
| Acer          | Acadia V1.42                | [11b24034fc](https://linux-hardware.org/?probe=11b24034fc) | Oct 23, 2021 |
| HP            | 255 G5                      | [02e4b753ca](https://linux-hardware.org/?probe=02e4b753ca) | Oct 22, 2021 |
| HP            | EliteBook 8460p             | [24535d9a4b](https://linux-hardware.org/?probe=24535d9a4b) | Oct 20, 2021 |
| HP            | EliteBook 8460p             | [cf78694aa7](https://linux-hardware.org/?probe=cf78694aa7) | Oct 20, 2021 |
| Dell          | System XPS 15Z              | [751ffeefa0](https://linux-hardware.org/?probe=751ffeefa0) | Oct 20, 2021 |
| HP            | Presario CQ42               | [d82c04d026](https://linux-hardware.org/?probe=d82c04d026) | Oct 19, 2021 |
| Acer          | Aspire ES1-531              | [a7058244ce](https://linux-hardware.org/?probe=a7058244ce) | Oct 16, 2021 |
| Dell          | Inspiron N5010              | [eca5c4cbf7](https://linux-hardware.org/?probe=eca5c4cbf7) | Oct 15, 2021 |
| HP            | Laptop 15-da0xxx            | [3054954ea5](https://linux-hardware.org/?probe=3054954ea5) | Oct 14, 2021 |
| Dell          | Inspiron N5010              | [2495309045](https://linux-hardware.org/?probe=2495309045) | Oct 14, 2021 |
| HP            | Laptop 15-da0xxx            | [dd3b21ba26](https://linux-hardware.org/?probe=dd3b21ba26) | Oct 14, 2021 |
| Dell          | Inspiron N5050              | [1dd1c022a2](https://linux-hardware.org/?probe=1dd1c022a2) | Oct 13, 2021 |
| Dell          | Inspiron N5050              | [8866975539](https://linux-hardware.org/?probe=8866975539) | Oct 13, 2021 |
| American M... | 255/259 Series              | [e8761321aa](https://linux-hardware.org/?probe=e8761321aa) | Oct 13, 2021 |
| Acer          | Aspire E1-572               | [dc154fe7c0](https://linux-hardware.org/?probe=dc154fe7c0) | Oct 13, 2021 |
| ASUSTek       | N61Jv                       | [0e300bafe8](https://linux-hardware.org/?probe=0e300bafe8) | Oct 12, 2021 |
| Toshiba       | Satellite Pro C660          | [14a96b5cec](https://linux-hardware.org/?probe=14a96b5cec) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
| HP            | Laptop 15-db0xxx            | [a49c0e5d41](https://linux-hardware.org/?probe=a49c0e5d41) | Oct 08, 2021 |
| Sony          | VPCEA20FB                   | [de4d94232e](https://linux-hardware.org/?probe=de4d94232e) | Oct 07, 2021 |
| Sony          | VPCEA20FB                   | [52e6abba3c](https://linux-hardware.org/?probe=52e6abba3c) | Oct 07, 2021 |
| Matsushita... | CF-19CHB23BE                | [7024487bcd](https://linux-hardware.org/?probe=7024487bcd) | Oct 07, 2021 |
| Acer          | AOD255                      | [79fa37e2d3](https://linux-hardware.org/?probe=79fa37e2d3) | Sep 30, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [4cd46a616f](https://linux-hardware.org/?probe=4cd46a616f) | Sep 29, 2021 |
| Digibras      | NH4CU53                     | [f0615abf72](https://linux-hardware.org/?probe=f0615abf72) | Sep 27, 2021 |
| Toshiba       | Satellite C50-B             | [0914aeed54](https://linux-hardware.org/?probe=0914aeed54) | Sep 25, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1070... | [c77dd4d1b4](https://linux-hardware.org/?probe=c77dd4d1b4) | Sep 23, 2021 |
| Philco        | 14F                         | [093b9632e8](https://linux-hardware.org/?probe=093b9632e8) | Sep 23, 2021 |
| Dell          | Inspiron 6000               | [f48bad44cd](https://linux-hardware.org/?probe=f48bad44cd) | Sep 22, 2021 |
| ASUSTek       | UX430UAR                    | [57d695a843](https://linux-hardware.org/?probe=57d695a843) | Sep 21, 2021 |
| HP            | ProBook 4540s               | [ccac6a82ca](https://linux-hardware.org/?probe=ccac6a82ca) | Sep 20, 2021 |
| Fujitsu Si... | AMILO M7440D                | [e23f21b9b4](https://linux-hardware.org/?probe=e23f21b9b4) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | [bce3e66350](https://linux-hardware.org/?probe=bce3e66350) | Sep 19, 2021 |
| Positivo      | Mobile                      | [6f701d72fd](https://linux-hardware.org/?probe=6f701d72fd) | Sep 17, 2021 |
| ASUSTek       | F5SL                        | [e6e93168a6](https://linux-hardware.org/?probe=e6e93168a6) | Sep 15, 2021 |
| Toshiba       | Satellite Pro C850-1H8      | [ea23c035b2](https://linux-hardware.org/?probe=ea23c035b2) | Sep 15, 2021 |
| HP            | EliteBook 6930p             | [8f38de340d](https://linux-hardware.org/?probe=8f38de340d) | Sep 15, 2021 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [445f079c6d](https://linux-hardware.org/?probe=445f079c6d) | Sep 15, 2021 |
| Lenovo        | ThinkPad T61 765818U        | [7bae831cdf](https://linux-hardware.org/?probe=7bae831cdf) | Sep 12, 2021 |
| Acer          | Lugano M                    | [5c114a6e41](https://linux-hardware.org/?probe=5c114a6e41) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | [54ddef7aa7](https://linux-hardware.org/?probe=54ddef7aa7) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | [8c00427976](https://linux-hardware.org/?probe=8c00427976) | Sep 11, 2021 |
| Acer          | Aspire 3610                 | [fc6953a3f9](https://linux-hardware.org/?probe=fc6953a3f9) | Sep 10, 2021 |
| HP            | ProBook 6460b               | [b0f0eaf216](https://linux-hardware.org/?probe=b0f0eaf216) | Sep 09, 2021 |
| Pendo Indu... | PNDFWXUFD11BLK6             | [06d0750e6e](https://linux-hardware.org/?probe=06d0750e6e) | Sep 08, 2021 |
| Acer          | Aspire 3610                 | [3ab0387498](https://linux-hardware.org/?probe=3ab0387498) | Sep 08, 2021 |
| Dell          | Inspiron 1010               | [ee05ebef50](https://linux-hardware.org/?probe=ee05ebef50) | Sep 07, 2021 |
| Dell          | Inspiron 1010               | [8805be4e5c](https://linux-hardware.org/?probe=8805be4e5c) | Sep 07, 2021 |
| Lenovo        | ThinkPad T61 765818U        | [df384e1ab4](https://linux-hardware.org/?probe=df384e1ab4) | Sep 06, 2021 |
| GPD           | MicroPC                     | [d0ffed23be](https://linux-hardware.org/?probe=d0ffed23be) | Sep 05, 2021 |
| Unknown       | T3 MRD                      | [0687d6609d](https://linux-hardware.org/?probe=0687d6609d) | Sep 03, 2021 |
| Dell          | Latitude D630               | [6b4af154d5](https://linux-hardware.org/?probe=6b4af154d5) | Sep 03, 2021 |
| Acer          | Aspire 9410                 | [d6632fcd8b](https://linux-hardware.org/?probe=d6632fcd8b) | Sep 02, 2021 |
| HP            | 530                         | [cc7cc97ae3](https://linux-hardware.org/?probe=cc7cc97ae3) | Aug 31, 2021 |
| HP            | 530                         | [20bf2422fc](https://linux-hardware.org/?probe=20bf2422fc) | Aug 31, 2021 |
| ASUSTek       | X55U                        | [b37f7fdf24](https://linux-hardware.org/?probe=b37f7fdf24) | Aug 30, 2021 |
| Acer          | Aspire 8920                 | [8a006e9280](https://linux-hardware.org/?probe=8a006e9280) | Aug 28, 2021 |
| ASUSTek       | 1001PX                      | [1b8954cf9f](https://linux-hardware.org/?probe=1b8954cf9f) | Aug 27, 2021 |
| Lenovo        | ThinkPad R61e 7650ELU       | [7c29fad093](https://linux-hardware.org/?probe=7c29fad093) | Aug 26, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | [285a023dd8](https://linux-hardware.org/?probe=285a023dd8) | Aug 26, 2021 |
| ASUSTek       | UX430UAR                    | [88f301b39f](https://linux-hardware.org/?probe=88f301b39f) | Aug 26, 2021 |
| HP            | Mini 110-3100               | [2bca9a30ab](https://linux-hardware.org/?probe=2bca9a30ab) | Aug 25, 2021 |
| Dell          | Inspiron 6000               | [f4ae3e605a](https://linux-hardware.org/?probe=f4ae3e605a) | Aug 24, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [ab8a4f01d9](https://linux-hardware.org/?probe=ab8a4f01d9) | Aug 22, 2021 |
| Panasonic     | CF-31JEGAX1M                | [c5acecef3a](https://linux-hardware.org/?probe=c5acecef3a) | Aug 22, 2021 |
| HP            | Compaq Presario CQ61        | [c7c1d06954](https://linux-hardware.org/?probe=c7c1d06954) | Aug 21, 2021 |
| Positivo      | Mobile                      | [e4a47e39b6](https://linux-hardware.org/?probe=e4a47e39b6) | Aug 21, 2021 |
| Samsung       | RV419                       | [ba6f454b7d](https://linux-hardware.org/?probe=ba6f454b7d) | Aug 20, 2021 |
| Samsung       | N150                        | [86914b23ac](https://linux-hardware.org/?probe=86914b23ac) | Aug 19, 2021 |
| Positivo      | Q232A                       | [f76d2dc489](https://linux-hardware.org/?probe=f76d2dc489) | Aug 19, 2021 |
| HP            | ProBook 4430s               | [0235e3c344](https://linux-hardware.org/?probe=0235e3c344) | Aug 18, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [5ab0429d85](https://linux-hardware.org/?probe=5ab0429d85) | Aug 17, 2021 |
| HP            | ENVY 17                     | [7c9143912d](https://linux-hardware.org/?probe=7c9143912d) | Aug 17, 2021 |
| ASUSTek       | X441SA                      | [f23d4d50be](https://linux-hardware.org/?probe=f23d4d50be) | Aug 16, 2021 |
| Itautec       | Infoway                     | [f66edac6bd](https://linux-hardware.org/?probe=f66edac6bd) | Aug 16, 2021 |
| Itautec       | Infoway                     | [94c198d530](https://linux-hardware.org/?probe=94c198d530) | Aug 16, 2021 |
| HP            | Pavilion 17                 | [b628f70687](https://linux-hardware.org/?probe=b628f70687) | Aug 15, 2021 |
| SiS           | M672 Board SI94B-20+SI96... | [8268c73ee9](https://linux-hardware.org/?probe=8268c73ee9) | Aug 14, 2021 |
| HP            | Pavilion g7                 | [cf766b8d76](https://linux-hardware.org/?probe=cf766b8d76) | Aug 13, 2021 |
| Quanta        | QL5 TBD                     | [be465dec60](https://linux-hardware.org/?probe=be465dec60) | Aug 13, 2021 |
| Toshiba       | Satellite L505D             | [b7b43a605d](https://linux-hardware.org/?probe=b7b43a605d) | Aug 12, 2021 |
| Toshiba       | Satellite L505D             | [8560337601](https://linux-hardware.org/?probe=8560337601) | Aug 12, 2021 |
| Acer          | Aspire 8920                 | [9ac1d0a471](https://linux-hardware.org/?probe=9ac1d0a471) | Aug 12, 2021 |
| Lenovo        | Z50-70 20354                | [1eba114602](https://linux-hardware.org/?probe=1eba114602) | Aug 11, 2021 |
| Lenovo        | Z50-70 20354                | [a31c1f0fda](https://linux-hardware.org/?probe=a31c1f0fda) | Aug 11, 2021 |
| HP            | Pavilion dv6700             | [ebf6b956cb](https://linux-hardware.org/?probe=ebf6b956cb) | Aug 10, 2021 |
| Apple         | MacBookPro7,1               | [da4107ffc3](https://linux-hardware.org/?probe=da4107ffc3) | Aug 10, 2021 |
| Samsung       | RV419                       | [66823b7d4d](https://linux-hardware.org/?probe=66823b7d4d) | Aug 10, 2021 |
| ASUSTek       | X51R                        | [1d1aad3900](https://linux-hardware.org/?probe=1d1aad3900) | Aug 08, 2021 |
| Dell          | Inspiron 3521               | [d0814fcb72](https://linux-hardware.org/?probe=d0814fcb72) | Aug 08, 2021 |
| Acer          | Extensa 5220                | [c2e39c0d39](https://linux-hardware.org/?probe=c2e39c0d39) | Aug 07, 2021 |
| HP            | Compaq 2510p                | [ea3c7d2fe2](https://linux-hardware.org/?probe=ea3c7d2fe2) | Aug 07, 2021 |
| HP            | Compaq 2510p                | [31449a4b42](https://linux-hardware.org/?probe=31449a4b42) | Aug 07, 2021 |
| Dell          | Inspiron 3421               | [dc8767625f](https://linux-hardware.org/?probe=dc8767625f) | Aug 07, 2021 |
| Acer          | Extensa 5220                | [b0da636247](https://linux-hardware.org/?probe=b0da636247) | Aug 07, 2021 |
| Dell          | Inspiron 3421               | [52f396865d](https://linux-hardware.org/?probe=52f396865d) | Aug 07, 2021 |
| Positivo      | CHT14B                      | [c8d89d2cde](https://linux-hardware.org/?probe=c8d89d2cde) | Aug 06, 2021 |
| Acer          | Aspire E5-575               | [9d4f584337](https://linux-hardware.org/?probe=9d4f584337) | Aug 06, 2021 |
| Lenovo        | ThinkPad T61 6468AE2        | [58f1efa783](https://linux-hardware.org/?probe=58f1efa783) | Aug 06, 2021 |
| Dell          | Latitude E5500              | [0688139a45](https://linux-hardware.org/?probe=0688139a45) | Aug 04, 2021 |
| Lenovo        | ThinkPad T61 6465CTO        | [d93258840e](https://linux-hardware.org/?probe=d93258840e) | Aug 04, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [1b40831803](https://linux-hardware.org/?probe=1b40831803) | Aug 04, 2021 |
| Acer          | Extensa 5220                | [e8b82c756d](https://linux-hardware.org/?probe=e8b82c756d) | Jul 26, 2021 |
| Acer          | Extensa 5220                | [82ae089b21](https://linux-hardware.org/?probe=82ae089b21) | Jul 26, 2021 |
| Medion        | Unknown                     | [021ba4d5b5](https://linux-hardware.org/?probe=021ba4d5b5) | Jul 25, 2021 |
| Medion        | Unknown                     | [e9c5e99e0b](https://linux-hardware.org/?probe=e9c5e99e0b) | Jul 25, 2021 |
| HP            | Compaq CQ58                 | [96df68c59e](https://linux-hardware.org/?probe=96df68c59e) | Jul 25, 2021 |
| Dell          | Latitude 5480               | [1b32299688](https://linux-hardware.org/?probe=1b32299688) | Jul 24, 2021 |
| HP            | Notebook                    | [71959b30db](https://linux-hardware.org/?probe=71959b30db) | Jul 23, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [8d72c96d15](https://linux-hardware.org/?probe=8d72c96d15) | Jul 23, 2021 |
| Dell          | Inspiron N5010              | [4a76f84bf5](https://linux-hardware.org/?probe=4a76f84bf5) | Jul 22, 2021 |
| Lenovo        | Y70-70 Touch 80DU           | [36fb0f3df5](https://linux-hardware.org/?probe=36fb0f3df5) | Jul 16, 2021 |
| Sony          | SVE14A2V1EW                 | [2b1ce53eca](https://linux-hardware.org/?probe=2b1ce53eca) | Jul 16, 2021 |
| HP            | 250 G7 Notebook PC          | [846febb191](https://linux-hardware.org/?probe=846febb191) | Jul 14, 2021 |
| HP            | EliteBook 820 G2            | [8c035c3e82](https://linux-hardware.org/?probe=8c035c3e82) | Jul 14, 2021 |
| ASUSTek       | G50V                        | [ec1ddd4644](https://linux-hardware.org/?probe=ec1ddd4644) | Jul 11, 2021 |
| Samsung       | N145P/N250P/N260P           | [e60ff3401a](https://linux-hardware.org/?probe=e60ff3401a) | Jul 11, 2021 |
| Sony          | VPCEH16EA                   | [189be303f7](https://linux-hardware.org/?probe=189be303f7) | Jul 09, 2021 |
| Sony          | VPCEH16EA                   | [c93e5aee87](https://linux-hardware.org/?probe=c93e5aee87) | Jul 08, 2021 |
| HP            | 255 G7 Notebook PC          | [b543fedfd0](https://linux-hardware.org/?probe=b543fedfd0) | Jul 08, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [508ac5b4d5](https://linux-hardware.org/?probe=508ac5b4d5) | Jul 07, 2021 |
| Sony          | VPCSB25FB                   | [6de928a758](https://linux-hardware.org/?probe=6de928a758) | Jul 07, 2021 |
| Gateway       | MX8711                      | [185e86b37e](https://linux-hardware.org/?probe=185e86b37e) | Jul 06, 2021 |
| Acer          | Aspire A515-45              | [42249c6e47](https://linux-hardware.org/?probe=42249c6e47) | Jul 02, 2021 |
| HP            | Pavilion dv6700             | [93c6a703a7](https://linux-hardware.org/?probe=93c6a703a7) | Jun 27, 2021 |
| HP            | Pavilion dv6700             | [f7e407b14c](https://linux-hardware.org/?probe=f7e407b14c) | Jun 27, 2021 |
| ASUSTek       | K54HR                       | [8fcbeb49c1](https://linux-hardware.org/?probe=8fcbeb49c1) | Jun 26, 2021 |
| Sony          | VPCSB16FG                   | [ead356e548](https://linux-hardware.org/?probe=ead356e548) | Jun 24, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f3430744d8](https://linux-hardware.org/?probe=f3430744d8) | Jun 24, 2021 |
| HP            | Laptop 15-da0xxx            | [77fba11f44](https://linux-hardware.org/?probe=77fba11f44) | Jun 21, 2021 |
| Lenovo        | G40-30 80FY                 | [114ba38c36](https://linux-hardware.org/?probe=114ba38c36) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [0cb7e73af9](https://linux-hardware.org/?probe=0cb7e73af9) | Jun 19, 2021 |
| Dell          | Precision 7520              | [9b19302ca7](https://linux-hardware.org/?probe=9b19302ca7) | Jun 18, 2021 |
| Dell          | Inspiron N4010              | [d385bb7617](https://linux-hardware.org/?probe=d385bb7617) | Jun 15, 2021 |
| Dell          | Inspiron N4010              | [be79fbc95c](https://linux-hardware.org/?probe=be79fbc95c) | Jun 15, 2021 |
| Samsung       | N150/N210/N220              | [8e03d52f53](https://linux-hardware.org/?probe=8e03d52f53) | Jun 12, 2021 |
| Lenovo        | Unknown                     | [108d3cba46](https://linux-hardware.org/?probe=108d3cba46) | Jun 10, 2021 |
| HP            | Stream Notebook             | [806c24449c](https://linux-hardware.org/?probe=806c24449c) | Jun 09, 2021 |
| HCL Infosy... | HCL ME Laptop               | [0aaf1b69bc](https://linux-hardware.org/?probe=0aaf1b69bc) | Jun 08, 2021 |
| Dell          | Latitude E6520              | [04a7f10801](https://linux-hardware.org/?probe=04a7f10801) | Jun 08, 2021 |
| Lenovo        | G40-30 80FY                 | [b2fe748178](https://linux-hardware.org/?probe=b2fe748178) | Jun 08, 2021 |
| Sony          | VGN-BX51VN                  | [debf4b3290](https://linux-hardware.org/?probe=debf4b3290) | Jun 06, 2021 |
| ASUSTek       | Q524UQ                      | [442c1c8b06](https://linux-hardware.org/?probe=442c1c8b06) | Jun 05, 2021 |
| HP            | Pavilion dv5                | [94cfdbc88f](https://linux-hardware.org/?probe=94cfdbc88f) | Jun 03, 2021 |
| Unknown       | Unknown                     | [3ce5819b57](https://linux-hardware.org/?probe=3ce5819b57) | Jun 02, 2021 |
| Apple         | MacBookPro12,1              | [f7f5736b13](https://linux-hardware.org/?probe=f7f5736b13) | Jun 01, 2021 |
| Sony          | VGN-BX51VN                  | [055903703c](https://linux-hardware.org/?probe=055903703c) | Jun 01, 2021 |
| Toshiba       | Satellite M70               | [67580c50df](https://linux-hardware.org/?probe=67580c50df) | Jun 01, 2021 |
| Acer          | Aspire 3100                 | [d38f5b09d2](https://linux-hardware.org/?probe=d38f5b09d2) | Jun 01, 2021 |
| Acer          | Aspire 3100                 | [fbcd23ac31](https://linux-hardware.org/?probe=fbcd23ac31) | May 31, 2021 |
| Toshiba       | Satellite P300              | [feb13460e8](https://linux-hardware.org/?probe=feb13460e8) | May 30, 2021 |
| Toshiba       | Satellite P300              | [8b5034adc9](https://linux-hardware.org/?probe=8b5034adc9) | May 30, 2021 |
| Lenovo        | G40-30 80FY                 | [eb9aaa55ea](https://linux-hardware.org/?probe=eb9aaa55ea) | May 30, 2021 |
| Dell          | Inspiron 3521               | [9fc71241e6](https://linux-hardware.org/?probe=9fc71241e6) | May 26, 2021 |
| Lenovo        | G40-30 80FY                 | [0c3e0e8293](https://linux-hardware.org/?probe=0c3e0e8293) | May 26, 2021 |
| ARIMA         | W351UI                      | [6cbffa9177](https://linux-hardware.org/?probe=6cbffa9177) | May 25, 2021 |
| Dell          | Latitude D520               | [7a817a0426](https://linux-hardware.org/?probe=7a817a0426) | May 25, 2021 |
| HP            | Pavilion dv6700             | [b30d13bbba](https://linux-hardware.org/?probe=b30d13bbba) | May 25, 2021 |
| ASUSTek       | UX31A                       | [edeed3b99b](https://linux-hardware.org/?probe=edeed3b99b) | May 23, 2021 |
| ASUSTek       | UX31A                       | [7f750ead39](https://linux-hardware.org/?probe=7f750ead39) | May 23, 2021 |
| Google        | Candy                       | [f6b5b1fd81](https://linux-hardware.org/?probe=f6b5b1fd81) | May 23, 2021 |
| ASUSTek       | X540YA                      | [369ebd51b8](https://linux-hardware.org/?probe=369ebd51b8) | May 23, 2021 |
| ASUSTek       | F5N                         | [414786c3d5](https://linux-hardware.org/?probe=414786c3d5) | May 22, 2021 |
| Dell          | Inspiron 3521               | [ef65e1a0f7](https://linux-hardware.org/?probe=ef65e1a0f7) | May 21, 2021 |
| Dell          | Latitude E7240              | [9e790ba3f0](https://linux-hardware.org/?probe=9e790ba3f0) | May 21, 2021 |
| HP            | 255 G5                      | [cbd6a96f91](https://linux-hardware.org/?probe=cbd6a96f91) | May 20, 2021 |
| ASUSTek       | T100TA                      | [bca3c06314](https://linux-hardware.org/?probe=bca3c06314) | May 20, 2021 |
| ASUSTek       | T100TA                      | [f232d2395d](https://linux-hardware.org/?probe=f232d2395d) | May 19, 2021 |
| Dell          | G5 5587                     | [39be80ad79](https://linux-hardware.org/?probe=39be80ad79) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [d9592ead1e](https://linux-hardware.org/?probe=d9592ead1e) | May 18, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [bc6920fa56](https://linux-hardware.org/?probe=bc6920fa56) | May 16, 2021 |
| HP            | 435                         | [65bbde1e13](https://linux-hardware.org/?probe=65bbde1e13) | May 16, 2021 |
| HP            | 435                         | [fe5a82cf02](https://linux-hardware.org/?probe=fe5a82cf02) | May 16, 2021 |
| ASUSTek       | K54C                        | [af86f8b1ed](https://linux-hardware.org/?probe=af86f8b1ed) | May 14, 2021 |
| Dell          | Inspiron 14-3467            | [511f638394](https://linux-hardware.org/?probe=511f638394) | May 14, 2021 |
| Acer          | V5-131                      | [d78c3cc207](https://linux-hardware.org/?probe=d78c3cc207) | May 14, 2021 |
| Dell          | Inspiron 1525               | [22f4b67d9b](https://linux-hardware.org/?probe=22f4b67d9b) | May 12, 2021 |
| Dell          | Inspiron 7520               | [fdf52a6676](https://linux-hardware.org/?probe=fdf52a6676) | May 11, 2021 |
| Samsung       | RF712                       | [a3624b29fa](https://linux-hardware.org/?probe=a3624b29fa) | May 11, 2021 |
| Samsung       | RF712                       | [652fb28adb](https://linux-hardware.org/?probe=652fb28adb) | May 11, 2021 |
| HP            | ProBook 4510s               | [dbdd169cb4](https://linux-hardware.org/?probe=dbdd169cb4) | May 10, 2021 |
| Dell          | Inspiron 14-3467            | [2fd207a33d](https://linux-hardware.org/?probe=2fd207a33d) | May 10, 2021 |
| Fujitsu       | FMVNF40UK                   | [8648b42278](https://linux-hardware.org/?probe=8648b42278) | May 09, 2021 |
| Dell          | Inspiron 14-3467            | [173baf5fdb](https://linux-hardware.org/?probe=173baf5fdb) | May 09, 2021 |
| Toshiba       | Satellite P200              | [5fff6be5f0](https://linux-hardware.org/?probe=5fff6be5f0) | May 05, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [0c612ea2a3](https://linux-hardware.org/?probe=0c612ea2a3) | May 04, 2021 |
| Lenovo        | 406822U                     | [68080373ce](https://linux-hardware.org/?probe=68080373ce) | May 03, 2021 |
| Lenovo        | 406822U                     | [5d498a42cc](https://linux-hardware.org/?probe=5d498a42cc) | May 03, 2021 |
| ASUSTek       | X540SA                      | [0f79fb429b](https://linux-hardware.org/?probe=0f79fb429b) | May 02, 2021 |
| Acer          | Aspire 5538                 | [b01066567a](https://linux-hardware.org/?probe=b01066567a) | May 02, 2021 |
| Acer          | Aspire 5538                 | [39c929202c](https://linux-hardware.org/?probe=39c929202c) | May 02, 2021 |
| Acer          | AOD255E                     | [202573d3f1](https://linux-hardware.org/?probe=202573d3f1) | May 02, 2021 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [21666fb8b5](https://linux-hardware.org/?probe=21666fb8b5) | May 01, 2021 |
| TrekStor      | Notebook Slim S130          | [3ee0251799](https://linux-hardware.org/?probe=3ee0251799) | May 01, 2021 |
| HP            | ENVY Notebook               | [00123e7e27](https://linux-hardware.org/?probe=00123e7e27) | May 01, 2021 |
| Positivo      | S14CT01                     | [d6ad6f67a7](https://linux-hardware.org/?probe=d6ad6f67a7) | Apr 30, 2021 |
| Dell          | Latitude D630               | [ce166d946d](https://linux-hardware.org/?probe=ce166d946d) | Apr 30, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [dc22e810b4](https://linux-hardware.org/?probe=dc22e810b4) | Apr 29, 2021 |
| Itautec       | Infoway                     | [01e1f5151c](https://linux-hardware.org/?probe=01e1f5151c) | Apr 28, 2021 |
| Fujitsu       | LIFEBOOK U772               | [e2c74983d8](https://linux-hardware.org/?probe=e2c74983d8) | Apr 28, 2021 |
| Lenovo        | ThinkPad X131e 3372A14      | [3c79681783](https://linux-hardware.org/?probe=3c79681783) | Apr 26, 2021 |
| Acer          | Aspire E5-523               | [7acc074ffd](https://linux-hardware.org/?probe=7acc074ffd) | Apr 26, 2021 |
| Acer          | Aspire E5-523               | [349b8662d9](https://linux-hardware.org/?probe=349b8662d9) | Apr 26, 2021 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [4cffaa3991](https://linux-hardware.org/?probe=4cffaa3991) | Apr 23, 2021 |
| Acer          | Unknown                     | [cd6b0eabe2](https://linux-hardware.org/?probe=cd6b0eabe2) | Apr 23, 2021 |
| Acer          | Aspire 5333                 | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| Toshiba       | IS 1422                     | [f52456fce9](https://linux-hardware.org/?probe=f52456fce9) | Apr 22, 2021 |
| Toshiba       | IS 1422                     | [9443f68502](https://linux-hardware.org/?probe=9443f68502) | Apr 22, 2021 |
| Samsung       | 550XCJ/550XCR               | [2a2a56b6d4](https://linux-hardware.org/?probe=2a2a56b6d4) | Apr 22, 2021 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [d8340c053a](https://linux-hardware.org/?probe=d8340c053a) | Apr 22, 2021 |
| Packard Be... | EasyNote_BU45               | [7d3e06e670](https://linux-hardware.org/?probe=7d3e06e670) | Apr 21, 2021 |
| Packard Be... | EasyNote_BU45               | [c97faabab8](https://linux-hardware.org/?probe=c97faabab8) | Apr 21, 2021 |
| Dell          | Latitude D620               | [116568909e](https://linux-hardware.org/?probe=116568909e) | Apr 19, 2021 |
| Dell          | Latitude D520               | [4e8b58ab28](https://linux-hardware.org/?probe=4e8b58ab28) | Apr 16, 2021 |
| Acer          | Aspire 5333                 | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A             | [6670c58f24](https://linux-hardware.org/?probe=6670c58f24) | Apr 15, 2021 |
| Dell          | Inspiron 5759               | [7fcec2352e](https://linux-hardware.org/?probe=7fcec2352e) | Apr 15, 2021 |
| HP            | Pavilion dv5                | [901dd6f4bc](https://linux-hardware.org/?probe=901dd6f4bc) | Apr 14, 2021 |
| Toshiba       | Satellite C55-A             | [7862f9a6e6](https://linux-hardware.org/?probe=7862f9a6e6) | Apr 14, 2021 |
| Toshiba       | Satellite P200              | [f6b3c134f2](https://linux-hardware.org/?probe=f6b3c134f2) | Apr 11, 2021 |
| HP            | EliteBook 850 G5            | [8351e652e0](https://linux-hardware.org/?probe=8351e652e0) | Apr 11, 2021 |
| Dell          | Latitude D620               | [f0eb74cd27](https://linux-hardware.org/?probe=f0eb74cd27) | Apr 11, 2021 |
| Dell          | Latitude D620               | [599e543d6b](https://linux-hardware.org/?probe=599e543d6b) | Apr 11, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [24f7a90612](https://linux-hardware.org/?probe=24f7a90612) | Apr 10, 2021 |
| Lenovo        | ThinkPad W540 20BHS1MX00    | [762a1d15ab](https://linux-hardware.org/?probe=762a1d15ab) | Apr 09, 2021 |
| Toshiba       | dynabook R731/E             | [108510a130](https://linux-hardware.org/?probe=108510a130) | Apr 08, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [cdf6743f68](https://linux-hardware.org/?probe=cdf6743f68) | Apr 08, 2021 |
| Positivo      | Mobile                      | [340616710c](https://linux-hardware.org/?probe=340616710c) | Apr 07, 2021 |
| Toshiba       | QOSMIO X300                 | [7f3b22129c](https://linux-hardware.org/?probe=7f3b22129c) | Apr 07, 2021 |
| Toshiba       | QOSMIO X300                 | [c1e66d512d](https://linux-hardware.org/?probe=c1e66d512d) | Apr 07, 2021 |
| HP            | 15                          | [69d2aa2538](https://linux-hardware.org/?probe=69d2aa2538) | Apr 05, 2021 |
| HP            | EliteBook Folio 9480m       | [c878c10e7b](https://linux-hardware.org/?probe=c878c10e7b) | Apr 03, 2021 |
| Gigabyte      | AERO 15-SA                  | [b162082414](https://linux-hardware.org/?probe=b162082414) | Apr 03, 2021 |
| Compaq        | Presario CQ-17              | [d1ae1543d9](https://linux-hardware.org/?probe=d1ae1543d9) | Apr 02, 2021 |
| HP            | Stream Notebook PC 11       | [a2a25ee9ac](https://linux-hardware.org/?probe=a2a25ee9ac) | Apr 02, 2021 |
| HP            | Stream Notebook PC 11       | [bb9c9dc740](https://linux-hardware.org/?probe=bb9c9dc740) | Apr 01, 2021 |
| HP            | Laptop 15-dw1xxx            | [276153c011](https://linux-hardware.org/?probe=276153c011) | Mar 31, 2021 |
| HP            | Laptop 15-dw1xxx            | [7dc5cad98d](https://linux-hardware.org/?probe=7dc5cad98d) | Mar 31, 2021 |
| Gigabyte      | AERO 15-SA                  | [26957c118d](https://linux-hardware.org/?probe=26957c118d) | Mar 30, 2021 |
| Toshiba       | QOSMIO F50                  | [d9d565847f](https://linux-hardware.org/?probe=d9d565847f) | Mar 29, 2021 |
| HP            | ProBook 4540s               | [94b1064fc6](https://linux-hardware.org/?probe=94b1064fc6) | Mar 28, 2021 |
| HP            | ProBook 4540s               | [c6e6b05536](https://linux-hardware.org/?probe=c6e6b05536) | Mar 28, 2021 |
| ASUSTek       | X200CA                      | [fd66b80491](https://linux-hardware.org/?probe=fd66b80491) | Mar 28, 2021 |
| Gigabyte      | AERO 15-SA                  | [536dfb993f](https://linux-hardware.org/?probe=536dfb993f) | Mar 28, 2021 |
| Lenovo        | ThinkPad T430s 2356DH2      | [86d756fb89](https://linux-hardware.org/?probe=86d756fb89) | Mar 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8S... | [327b8352df](https://linux-hardware.org/?probe=327b8352df) | Mar 27, 2021 |
| HP            | Mini 110-1100               | [05039f09e2](https://linux-hardware.org/?probe=05039f09e2) | Mar 26, 2021 |
| HP            | Mini 110-1100               | [5192a10f03](https://linux-hardware.org/?probe=5192a10f03) | Mar 26, 2021 |
| ASUSTek       | 1011PX                      | [3d23090e46](https://linux-hardware.org/?probe=3d23090e46) | Mar 26, 2021 |
| HP            | Compaq Presario CQ61        | [58db0eef1f](https://linux-hardware.org/?probe=58db0eef1f) | Mar 25, 2021 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [125911ba8d](https://linux-hardware.org/?probe=125911ba8d) | Mar 21, 2021 |
| Apple         | MacBookPro5,4               | [e1ff6cd3c6](https://linux-hardware.org/?probe=e1ff6cd3c6) | Mar 20, 2021 |
| ASUSTek       | X555LD                      | [cf0c496200](https://linux-hardware.org/?probe=cf0c496200) | Mar 20, 2021 |
| HP            | ProBook 470 G1              | [7358a0ab88](https://linux-hardware.org/?probe=7358a0ab88) | Mar 20, 2021 |
| HP            | ProBook 470 G1              | [9a754ec32f](https://linux-hardware.org/?probe=9a754ec32f) | Mar 20, 2021 |
| Lenovo        | ThinkPad T420 41786UU       | [3965832137](https://linux-hardware.org/?probe=3965832137) | Mar 20, 2021 |
| Dell          | Latitude D610               | [faaf3b4f3d](https://linux-hardware.org/?probe=faaf3b4f3d) | Mar 18, 2021 |
| Panasonic     | CF-31JEGAX1M                | [4636e611d8](https://linux-hardware.org/?probe=4636e611d8) | Mar 14, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [9707772e02](https://linux-hardware.org/?probe=9707772e02) | Mar 13, 2021 |
| Acer          | Aspire 5610Z                | [ba43bff53e](https://linux-hardware.org/?probe=ba43bff53e) | Mar 13, 2021 |
| ASUSTek       | E402SA                      | [eec3171b5f](https://linux-hardware.org/?probe=eec3171b5f) | Mar 13, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [85703241b5](https://linux-hardware.org/?probe=85703241b5) | Mar 13, 2021 |
| MSI           | GX60 1AC                    | [774db4f685](https://linux-hardware.org/?probe=774db4f685) | Mar 12, 2021 |
| Hometech      | ELITE TAB 10                | [8bfad5d181](https://linux-hardware.org/?probe=8bfad5d181) | Mar 09, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [8a0395042b](https://linux-hardware.org/?probe=8a0395042b) | Mar 08, 2021 |
| Toshiba       | Satellite P300-17Q          | [72b5282501](https://linux-hardware.org/?probe=72b5282501) | Mar 08, 2021 |
| Gateway       | NV55C                       | [3f5377a2de](https://linux-hardware.org/?probe=3f5377a2de) | Mar 08, 2021 |
| Acer          | Aspire 5735                 | [cde827bd2e](https://linux-hardware.org/?probe=cde827bd2e) | Mar 07, 2021 |
| Acer          | Aspire 5735                 | [9730b9273d](https://linux-hardware.org/?probe=9730b9273d) | Mar 07, 2021 |
| HP            | 255 G7 Notebook PC          | [f5600011bb](https://linux-hardware.org/?probe=f5600011bb) | Mar 05, 2021 |
| HP            | 255 G7 Notebook PC          | [19e8d1a155](https://linux-hardware.org/?probe=19e8d1a155) | Mar 05, 2021 |
| Toshiba       | Satellite U920t             | [26b9e489aa](https://linux-hardware.org/?probe=26b9e489aa) | Mar 04, 2021 |
| Toshiba       | Satellite NB10t-A           | [c1c084e42c](https://linux-hardware.org/?probe=c1c084e42c) | Feb 28, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [dfc0744775](https://linux-hardware.org/?probe=dfc0744775) | Feb 28, 2021 |
| Multilaser    | PC024                       | [abaddb333b](https://linux-hardware.org/?probe=abaddb333b) | Feb 27, 2021 |
| Multilaser    | PC024                       | [54e46489ac](https://linux-hardware.org/?probe=54e46489ac) | Feb 27, 2021 |
| HP            | Compaq 6510b (GR690ET#AB... | [b9b8fa550a](https://linux-hardware.org/?probe=b9b8fa550a) | Feb 26, 2021 |
| HP            | Compaq 6510b (GR690ET#AB... | [4529dc90b2](https://linux-hardware.org/?probe=4529dc90b2) | Feb 26, 2021 |
| ASUSTek       | X555LD                      | [665cf4701a](https://linux-hardware.org/?probe=665cf4701a) | Feb 25, 2021 |
| Dell          | Inspiron 3543               | [cfc4c1a529](https://linux-hardware.org/?probe=cfc4c1a529) | Feb 24, 2021 |
| ASUSTek       | X751SJ                      | [81295695f3](https://linux-hardware.org/?probe=81295695f3) | Feb 24, 2021 |
| Dell          | Inspiron 3543               | [6b53f592ed](https://linux-hardware.org/?probe=6b53f592ed) | Feb 22, 2021 |
| HP            | ZBook 17 G2                 | [7213996a6e](https://linux-hardware.org/?probe=7213996a6e) | Feb 22, 2021 |
| Samsung       | 370E4K                      | [9d25cf824e](https://linux-hardware.org/?probe=9d25cf824e) | Feb 20, 2021 |
| Dell          | Inspiron 7737               | [ffaf611204](https://linux-hardware.org/?probe=ffaf611204) | Feb 20, 2021 |
| ASUSTek       | K52N                        | [0139461f57](https://linux-hardware.org/?probe=0139461f57) | Feb 19, 2021 |
| ASUSTek       | U36SD                       | [981c7e8da7](https://linux-hardware.org/?probe=981c7e8da7) | Feb 19, 2021 |
| ASUSTek       | X550ZA                      | [503250e6f1](https://linux-hardware.org/?probe=503250e6f1) | Feb 19, 2021 |
| HP            | 255 G5                      | [2ffdcec174](https://linux-hardware.org/?probe=2ffdcec174) | Feb 19, 2021 |
| Dell          | XPS 13 9333                 | [0166a2e7b9](https://linux-hardware.org/?probe=0166a2e7b9) | Feb 17, 2021 |
| Dell          | XPS 13 9333                 | [4e08aeb5c5](https://linux-hardware.org/?probe=4e08aeb5c5) | Feb 17, 2021 |
| HP            | Compaq Presario CQ61        | [e72ebb6663](https://linux-hardware.org/?probe=e72ebb6663) | Feb 14, 2021 |
| Toshiba       | Satellite L855              | [941b946e5e](https://linux-hardware.org/?probe=941b946e5e) | Feb 14, 2021 |
| Toshiba       | Satellite L855              | [4cfe29288e](https://linux-hardware.org/?probe=4cfe29288e) | Feb 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [622900874e](https://linux-hardware.org/?probe=622900874e) | Feb 14, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | [2b5732689b](https://linux-hardware.org/?probe=2b5732689b) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | [0005b66219](https://linux-hardware.org/?probe=0005b66219) | Feb 13, 2021 |
| HP            | ENVY 15                     | [ab6ef5e4cf](https://linux-hardware.org/?probe=ab6ef5e4cf) | Feb 12, 2021 |
| HP            | Compaq Presario CQ61        | [bcf179fa51](https://linux-hardware.org/?probe=bcf179fa51) | Feb 12, 2021 |
| ASUSTek       | X510UAR                     | [e194fe9742](https://linux-hardware.org/?probe=e194fe9742) | Feb 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [c7c4c6fe88](https://linux-hardware.org/?probe=c7c4c6fe88) | Feb 11, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1070... | [b14a3d0adb](https://linux-hardware.org/?probe=b14a3d0adb) | Feb 09, 2021 |
| NEC Comput... | PC-VY12FBHEW                | [c65bc992c6](https://linux-hardware.org/?probe=c65bc992c6) | Feb 08, 2021 |
| Dell          | Inspiron 1012               | [e5ec198a6d](https://linux-hardware.org/?probe=e5ec198a6d) | Feb 07, 2021 |
| HP            | Stream Laptop 11-y0XX       | [1a6227c6cf](https://linux-hardware.org/?probe=1a6227c6cf) | Feb 07, 2021 |
| Toshiba       | Satellite Pro L550          | [b6870f2fea](https://linux-hardware.org/?probe=b6870f2fea) | Feb 07, 2021 |
| Lenovo        | ThinkPad R61 8943DKG        | [fd7beeb674](https://linux-hardware.org/?probe=fd7beeb674) | Feb 06, 2021 |
| Lenovo        | ThinkPad R61 8943DKG        | [6a3c7e3263](https://linux-hardware.org/?probe=6a3c7e3263) | Feb 06, 2021 |
| Acer          | TravelMate 6592             | [9b2c049705](https://linux-hardware.org/?probe=9b2c049705) | Feb 06, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [067995d50f](https://linux-hardware.org/?probe=067995d50f) | Feb 05, 2021 |
| Unknown       | ARCELIK ANB 573 D SR        | [7ef8639d95](https://linux-hardware.org/?probe=7ef8639d95) | Feb 04, 2021 |
| Unknown       | ARCELIK ANB 573 D SR        | [70b60f77cc](https://linux-hardware.org/?probe=70b60f77cc) | Feb 04, 2021 |
| Lenovo        | G560 0679                   | [ebf2298ba0](https://linux-hardware.org/?probe=ebf2298ba0) | Feb 04, 2021 |
| Dell          | Latitude E6400              | [99e1f46388](https://linux-hardware.org/?probe=99e1f46388) | Feb 03, 2021 |
| HP            | EliteBook 2560p             | [f741035d0d](https://linux-hardware.org/?probe=f741035d0d) | Feb 02, 2021 |
| Dell          | Latitude D520               | [038841ada5](https://linux-hardware.org/?probe=038841ada5) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2dd10bb86f](https://linux-hardware.org/?probe=2dd10bb86f) | Feb 01, 2021 |
| HP            | G42                         | [532d273aec](https://linux-hardware.org/?probe=532d273aec) | Feb 01, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [18ceaaebaf](https://linux-hardware.org/?probe=18ceaaebaf) | Feb 01, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [90149b2d99](https://linux-hardware.org/?probe=90149b2d99) | Feb 01, 2021 |
| ASUSTek       | X555LD                      | [eb3be3f63f](https://linux-hardware.org/?probe=eb3be3f63f) | Jan 31, 2021 |
| Sony          | VGN-AR630E                  | [2e155fc628](https://linux-hardware.org/?probe=2e155fc628) | Jan 31, 2021 |
| Panasonic     | CF-30K3PAZN2                | [9a9c09f250](https://linux-hardware.org/?probe=9a9c09f250) | Jan 30, 2021 |
| Panasonic     | CF-30K3PAZN2                | [a1b4116c85](https://linux-hardware.org/?probe=a1b4116c85) | Jan 30, 2021 |
| ASUSTek       | U36SD                       | [5267c17fbb](https://linux-hardware.org/?probe=5267c17fbb) | Jan 30, 2021 |
| HP            | Pavilion zd8000 (PW934EA... | [640a4d1741](https://linux-hardware.org/?probe=640a4d1741) | Jan 29, 2021 |
| Olidata       | U40SI1                      | [60dd97276a](https://linux-hardware.org/?probe=60dd97276a) | Jan 28, 2021 |
| Olidata       | U40SI1                      | [cca9468e85](https://linux-hardware.org/?probe=cca9468e85) | Jan 28, 2021 |
| ASUSTek       | U36SD                       | [15288996d1](https://linux-hardware.org/?probe=15288996d1) | Jan 28, 2021 |
| Lenovo        | ThinkPad X240 20AM006KMN    | [7c40d08353](https://linux-hardware.org/?probe=7c40d08353) | Jan 28, 2021 |
| Acer          | Aspire E1-570G              | [19e6d6afd7](https://linux-hardware.org/?probe=19e6d6afd7) | Jan 28, 2021 |
| Toshiba       | Satellite L500              | [f9341665f3](https://linux-hardware.org/?probe=f9341665f3) | Jan 27, 2021 |
| Dell          | Latitude E5470              | [72db68119a](https://linux-hardware.org/?probe=72db68119a) | Jan 27, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [00f0257410](https://linux-hardware.org/?probe=00f0257410) | Jan 27, 2021 |
| HP            | ZBook 17 G6                 | [63c3d95bd5](https://linux-hardware.org/?probe=63c3d95bd5) | Jan 27, 2021 |
| Dell          | Latitude D630               | [efc4256a09](https://linux-hardware.org/?probe=efc4256a09) | Jan 26, 2021 |
| Dell          | Latitude E6400              | [91be1b1bd7](https://linux-hardware.org/?probe=91be1b1bd7) | Jan 26, 2021 |
| Acer          | Aspire E1-570G              | [f8f4880823](https://linux-hardware.org/?probe=f8f4880823) | Jan 26, 2021 |
| Toshiba       | Satellite L635              | [ca6d27fd9c](https://linux-hardware.org/?probe=ca6d27fd9c) | Jan 24, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [158b3578e3](https://linux-hardware.org/?probe=158b3578e3) | Jan 23, 2021 |
| Unknown       | Unknown                     | [0c6628ea31](https://linux-hardware.org/?probe=0c6628ea31) | Jan 23, 2021 |
| Dell          | Latitude E6400              | [fc052ebe8f](https://linux-hardware.org/?probe=fc052ebe8f) | Jan 23, 2021 |
| Apple         | MacBookPro11,1              | [b27a2d92e2](https://linux-hardware.org/?probe=b27a2d92e2) | Jan 22, 2021 |
| Sony          | SVE14A2V1EW                 | [baaf829145](https://linux-hardware.org/?probe=baaf829145) | Jan 20, 2021 |
| Dell          | Latitude E5430 non-vPro     | [db6d4d3deb](https://linux-hardware.org/?probe=db6d4d3deb) | Jan 20, 2021 |
| HP            | ProBook 6560b               | [4771c30f72](https://linux-hardware.org/?probe=4771c30f72) | Jan 18, 2021 |
| Lenovo        | ThinkPad X220 4290NC9       | [f90fbc6c88](https://linux-hardware.org/?probe=f90fbc6c88) | Jan 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | [1dfeaa1b83](https://linux-hardware.org/?probe=1dfeaa1b83) | Jan 17, 2021 |
| Toshiba       | Satellite L850-1HP          | [1e0aa7f353](https://linux-hardware.org/?probe=1e0aa7f353) | Jan 17, 2021 |
| Toshiba       | Satellite U920t             | [566f573caf](https://linux-hardware.org/?probe=566f573caf) | Jan 17, 2021 |
| Itautec       | Infoway a7420               | [d32d9bf816](https://linux-hardware.org/?probe=d32d9bf816) | Jan 16, 2021 |
| Quanta        | MW1/HW1                     | [ebab0a47f8](https://linux-hardware.org/?probe=ebab0a47f8) | Jan 16, 2021 |
| Unknown       | Unknown                     | [1fddcd5f95](https://linux-hardware.org/?probe=1fddcd5f95) | Jan 15, 2021 |
| Lenovo        | V145-15AST 81MT             | [ecaaa0fccb](https://linux-hardware.org/?probe=ecaaa0fccb) | Jan 14, 2021 |
| Lenovo        | ThinkPad Edge E530 3259A... | [e7ef3a9e86](https://linux-hardware.org/?probe=e7ef3a9e86) | Jan 14, 2021 |
| HP            | Presario V6000 (GF814EA#... | [1cb2345540](https://linux-hardware.org/?probe=1cb2345540) | Jan 12, 2021 |
| HP            | Compaq 6730s                | [71a2587c96](https://linux-hardware.org/?probe=71a2587c96) | Jan 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell          | Inspiron 3521               | [2e84869a9a](https://linux-hardware.org/?probe=2e84869a9a) | Jan 11, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [a8a6e06472](https://linux-hardware.org/?probe=a8a6e06472) | Jan 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9088e2aaad](https://linux-hardware.org/?probe=9088e2aaad) | Jan 09, 2021 |
| HP            | Pavilion (EH735UA#ABA)      | [f01f51c47c](https://linux-hardware.org/?probe=f01f51c47c) | Jan 09, 2021 |
| HP            | Pavilion (EH735UA#ABA)      | [d3c610e2b0](https://linux-hardware.org/?probe=d3c610e2b0) | Jan 08, 2021 |
| Acer          | Aspire V5-571               | [1d56503d52](https://linux-hardware.org/?probe=1d56503d52) | Jan 06, 2021 |
| Packard Be... | EasyNote TS11HR             | [ab603b2fe8](https://linux-hardware.org/?probe=ab603b2fe8) | Jan 06, 2021 |
| Dell          | Inspiron M5040              | [1cac82f558](https://linux-hardware.org/?probe=1cac82f558) | Jan 06, 2021 |
| Acer          | Aspire 5100                 | [a009c7e619](https://linux-hardware.org/?probe=a009c7e619) | Jan 05, 2021 |
| ASUSTek       | G74Sx                       | [17e1f90630](https://linux-hardware.org/?probe=17e1f90630) | Jan 04, 2021 |
| HP            | Compaq 6730s                | [00acad5ef5](https://linux-hardware.org/?probe=00acad5ef5) | Jan 03, 2021 |
| HP            | 250 G5 Notebook PC          | [a79116f681](https://linux-hardware.org/?probe=a79116f681) | Jan 03, 2021 |
| Dell          | XPS 13 9300                 | [0d6592676a](https://linux-hardware.org/?probe=0d6592676a) | Jan 02, 2021 |
| Packard Be... | EasyNote TS11HR             | [343249d2da](https://linux-hardware.org/?probe=343249d2da) | Jan 02, 2021 |
| HP            | 250 G5 Notebook PC          | [393c8ee706](https://linux-hardware.org/?probe=393c8ee706) | Jan 01, 2021 |
| Dell          | Inspiron 3541               | [e194f83f11](https://linux-hardware.org/?probe=e194f83f11) | Jan 01, 2021 |
| Dell          | Inspiron 3541               | [6d747c6598](https://linux-hardware.org/?probe=6d747c6598) | Jan 01, 2021 |
| Panasonic     | CF-31JEGAX1M                | [c0745f5a94](https://linux-hardware.org/?probe=c0745f5a94) | Dec 31, 2020 |
| HP            | ProBook 6560b               | [d6d7748e86](https://linux-hardware.org/?probe=d6d7748e86) | Dec 30, 2020 |
| Dell          | Inspiron 7737               | [494c51dbea](https://linux-hardware.org/?probe=494c51dbea) | Dec 30, 2020 |
| HP            | Compaq Presario CQ61        | [82c51cc214](https://linux-hardware.org/?probe=82c51cc214) | Dec 29, 2020 |
| HP            | Compaq Presario CQ61        | [a28099fd90](https://linux-hardware.org/?probe=a28099fd90) | Dec 29, 2020 |
| BGH           | C46G                        | [e61ae53564](https://linux-hardware.org/?probe=e61ae53564) | Dec 29, 2020 |
| HP            | Pavilion g7                 | [df2771c104](https://linux-hardware.org/?probe=df2771c104) | Dec 28, 2020 |
| Dell          | Inspiron 6000               | [7158c9692c](https://linux-hardware.org/?probe=7158c9692c) | Dec 27, 2020 |
| Insyde        | CherryTrail                 | [3d9eb0babd](https://linux-hardware.org/?probe=3d9eb0babd) | Dec 26, 2020 |
| BGH           | C46G                        | [515be17b75](https://linux-hardware.org/?probe=515be17b75) | Dec 26, 2020 |
| HP            | Mini 110-3100               | [f716ec84db](https://linux-hardware.org/?probe=f716ec84db) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | [25dadb6466](https://linux-hardware.org/?probe=25dadb6466) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | [72bfd374e3](https://linux-hardware.org/?probe=72bfd374e3) | Dec 26, 2020 |
| HP            | 255 G5                      | [0dc71b4d28](https://linux-hardware.org/?probe=0dc71b4d28) | Dec 24, 2020 |
| Acer          | Aspire 5715Z                | [8e6e0fd1c6](https://linux-hardware.org/?probe=8e6e0fd1c6) | Dec 24, 2020 |
| Ematic        | EWT127                      | [c48f491ddd](https://linux-hardware.org/?probe=c48f491ddd) | Dec 24, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [d3a90166ed](https://linux-hardware.org/?probe=d3a90166ed) | Dec 23, 2020 |
| Acer          | Aspire 5738                 | [27df1aad94](https://linux-hardware.org/?probe=27df1aad94) | Dec 22, 2020 |
| Lenovo        | G700 20251                  | [2bf9eaa028](https://linux-hardware.org/?probe=2bf9eaa028) | Dec 22, 2020 |
| HP            | Stream Notebook PC 14       | [515632d3df](https://linux-hardware.org/?probe=515632d3df) | Dec 22, 2020 |
| Dell          | Inspiron M5040              | [aa3db87a20](https://linux-hardware.org/?probe=aa3db87a20) | Dec 22, 2020 |
| Dell          | Latitude E6540              | [a210e1c5b0](https://linux-hardware.org/?probe=a210e1c5b0) | Dec 21, 2020 |
| Lenovo        | G700 20251                  | [33926859e5](https://linux-hardware.org/?probe=33926859e5) | Dec 20, 2020 |
| Dell          | Inspiron 6000               | [2cb0530e89](https://linux-hardware.org/?probe=2cb0530e89) | Dec 20, 2020 |
| Acer          | Aspire E1-570G              | [54c4be3905](https://linux-hardware.org/?probe=54c4be3905) | Dec 19, 2020 |
| Phoenix/Si... | M720SR                      | [019e901528](https://linux-hardware.org/?probe=019e901528) | Dec 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [7148c9a870](https://linux-hardware.org/?probe=7148c9a870) | Dec 19, 2020 |
| HP            | 550                         | [43d983a998](https://linux-hardware.org/?probe=43d983a998) | Dec 16, 2020 |
| Dell          | Precision 3520              | [688878db51](https://linux-hardware.org/?probe=688878db51) | Dec 16, 2020 |
| Toshiba       | Satellite L40               | [1ec0f32bdf](https://linux-hardware.org/?probe=1ec0f32bdf) | Dec 14, 2020 |
| HP            | Stream Laptop 11-y0XX       | [ed04aa76f7](https://linux-hardware.org/?probe=ed04aa76f7) | Dec 13, 2020 |
| HP            | Stream Laptop 11-y0XX       | [a45597a09a](https://linux-hardware.org/?probe=a45597a09a) | Dec 13, 2020 |
| ASUSTek       | G74Sx                       | [79afc26e90](https://linux-hardware.org/?probe=79afc26e90) | Dec 13, 2020 |
| Acer          | Aspire ES1-111              | [89f4d8b69a](https://linux-hardware.org/?probe=89f4d8b69a) | Dec 13, 2020 |
| Acer          | Aspire ES1-111              | [d0f8154669](https://linux-hardware.org/?probe=d0f8154669) | Dec 13, 2020 |
| Lenovo        | ThinkPad T440p 20AWS37D0... | [c35140641b](https://linux-hardware.org/?probe=c35140641b) | Dec 13, 2020 |
| NEC Comput... | PC-VY16AWZE4                | [c395763d53](https://linux-hardware.org/?probe=c395763d53) | Dec 12, 2020 |
| Dell          | Inspiron 3737               | [db241e053d](https://linux-hardware.org/?probe=db241e053d) | Dec 11, 2020 |
| HP            | ZBook 17 G5                 | [ca21d7e31d](https://linux-hardware.org/?probe=ca21d7e31d) | Dec 11, 2020 |
| NEC Comput... | PC-VY16AWZE4                | [eb1884e7bd](https://linux-hardware.org/?probe=eb1884e7bd) | Dec 10, 2020 |
| Insyde        | CAVION BASE 8 MS            | [b2a146e87c](https://linux-hardware.org/?probe=b2a146e87c) | Dec 09, 2020 |
| Insyde        | CAVION BASE 8 MS            | [9a210b4ebc](https://linux-hardware.org/?probe=9a210b4ebc) | Dec 09, 2020 |
| HP            | Laptop 15-bw0xx             | [577608cf6f](https://linux-hardware.org/?probe=577608cf6f) | Dec 08, 2020 |
| HP            | Laptop 15-bw0xx             | [f20b348140](https://linux-hardware.org/?probe=f20b348140) | Dec 08, 2020 |
| HP            | ProBook 450 G3              | [68d5e14ae0](https://linux-hardware.org/?probe=68d5e14ae0) | Dec 08, 2020 |
| HP            | Mini 110-1000               | [b0b1659e5a](https://linux-hardware.org/?probe=b0b1659e5a) | Dec 07, 2020 |
| Toshiba       | NB500                       | [fa6b10012f](https://linux-hardware.org/?probe=fa6b10012f) | Dec 06, 2020 |
| HP            | Pavilion dv9700             | [c2e755bbd2](https://linux-hardware.org/?probe=c2e755bbd2) | Dec 06, 2020 |
| HP            | ProBook 450 G3              | [a2e08c9405](https://linux-hardware.org/?probe=a2e08c9405) | Dec 06, 2020 |
| HP            | Laptop 15s-eq0xxx           | [31f7a22aab](https://linux-hardware.org/?probe=31f7a22aab) | Dec 04, 2020 |
| HP            | Laptop 15s-eq0xxx           | [411cb199ce](https://linux-hardware.org/?probe=411cb199ce) | Dec 04, 2020 |
| Acer          | V5-131                      | [bfdf441399](https://linux-hardware.org/?probe=bfdf441399) | Dec 03, 2020 |
| HP            | EliteBook 2560p             | [704777ce16](https://linux-hardware.org/?probe=704777ce16) | Dec 03, 2020 |
| Fujitsu       | CELSIUS H710                | [03fea3325c](https://linux-hardware.org/?probe=03fea3325c) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | [1214e804ff](https://linux-hardware.org/?probe=1214e804ff) | Dec 01, 2020 |
| Dell          | Latitude E6410              | [073ae61394](https://linux-hardware.org/?probe=073ae61394) | Nov 30, 2020 |
| HP            | G7000                       | [9596f449f8](https://linux-hardware.org/?probe=9596f449f8) | Nov 30, 2020 |
| HP            | G7000                       | [ae575e12ab](https://linux-hardware.org/?probe=ae575e12ab) | Nov 30, 2020 |
| Notebook      | RIM2020                     | [2b494bfd6c](https://linux-hardware.org/?probe=2b494bfd6c) | Nov 28, 2020 |
| Dell          | Inspiron 15-3552            | [762c5e70ba](https://linux-hardware.org/?probe=762c5e70ba) | Nov 28, 2020 |
| Dell          | Inspiron 15-3552            | [fc13827e05](https://linux-hardware.org/?probe=fc13827e05) | Nov 28, 2020 |
| Dell          | Latitude E6410              | [c17a248879](https://linux-hardware.org/?probe=c17a248879) | Nov 28, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [b6570c8388](https://linux-hardware.org/?probe=b6570c8388) | Nov 28, 2020 |
| HP            | 530                         | [8f3bc43ec5](https://linux-hardware.org/?probe=8f3bc43ec5) | Nov 27, 2020 |
| Notebook      | RIM2020                     | [a8a163c8b0](https://linux-hardware.org/?probe=a8a163c8b0) | Nov 27, 2020 |
| Dell          | Vostro A860                 | [beffd605b7](https://linux-hardware.org/?probe=beffd605b7) | Nov 27, 2020 |
| HP            | 530                         | [4d719de8d0](https://linux-hardware.org/?probe=4d719de8d0) | Nov 26, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4be164a8cb](https://linux-hardware.org/?probe=4be164a8cb) | Nov 26, 2020 |
| HP            | 2000                        | [031b9cf2af](https://linux-hardware.org/?probe=031b9cf2af) | Nov 25, 2020 |
| HP            | Pavilion dv6                | [678f6ed857](https://linux-hardware.org/?probe=678f6ed857) | Nov 24, 2020 |
| eMachines     | eM350                       | [2bafdd62aa](https://linux-hardware.org/?probe=2bafdd62aa) | Nov 23, 2020 |
| eMachines     | eM350                       | [03b9a0de29](https://linux-hardware.org/?probe=03b9a0de29) | Nov 23, 2020 |
| HP            | Presario V6500              | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Pavilion Notebook           | [a021bfc757](https://linux-hardware.org/?probe=a021bfc757) | Nov 23, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4accc1011e](https://linux-hardware.org/?probe=4accc1011e) | Nov 23, 2020 |
| HP            | 2000                        | [2090a455f6](https://linux-hardware.org/?probe=2090a455f6) | Nov 23, 2020 |
| HP            | 2000                        | [39c1685ce9](https://linux-hardware.org/?probe=39c1685ce9) | Nov 23, 2020 |
| HP            | Presario V6500              | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [7fe15caabf](https://linux-hardware.org/?probe=7fe15caabf) | Nov 23, 2020 |
| eMachines     | E525 V1.03                  | [a5c37bf711](https://linux-hardware.org/?probe=a5c37bf711) | Nov 22, 2020 |
| Dell          | Inspiron 3737               | [7dced8b5ca](https://linux-hardware.org/?probe=7dced8b5ca) | Nov 22, 2020 |
| Dell          | Vostro1710                  | [a359187c45](https://linux-hardware.org/?probe=a359187c45) | Nov 22, 2020 |
| Dell          | Vostro1710                  | [748c9cec43](https://linux-hardware.org/?probe=748c9cec43) | Nov 22, 2020 |
| ARIMA         | W622-DCX                    | [07cc1e0952](https://linux-hardware.org/?probe=07cc1e0952) | Nov 22, 2020 |
| ARIMA         | W622-DCX                    | [7388498d54](https://linux-hardware.org/?probe=7388498d54) | Nov 22, 2020 |
| Dell          | Latitude D430               | [77ef794b1d](https://linux-hardware.org/?probe=77ef794b1d) | Nov 21, 2020 |
| Dell          | Latitude D430               | [c028c146b6](https://linux-hardware.org/?probe=c028c146b6) | Nov 21, 2020 |
| Dell          | Inspiron 3737               | [80df1af89c](https://linux-hardware.org/?probe=80df1af89c) | Nov 20, 2020 |
| Dell          | Latitude E6410              | [4879940968](https://linux-hardware.org/?probe=4879940968) | Nov 19, 2020 |
| HP            | Pavilion x2 Detachable      | [742f34e12f](https://linux-hardware.org/?probe=742f34e12f) | Nov 19, 2020 |
| Acer          | Aspire 5253                 | [5700a5a6f1](https://linux-hardware.org/?probe=5700a5a6f1) | Nov 19, 2020 |
| Dell          | Latitude E5420              | [816b9060e4](https://linux-hardware.org/?probe=816b9060e4) | Nov 19, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [6e9cf39149](https://linux-hardware.org/?probe=6e9cf39149) | Nov 18, 2020 |
| HP            | Compaq Mini 110c-1100       | [36bc2c3cdf](https://linux-hardware.org/?probe=36bc2c3cdf) | Nov 18, 2020 |
| Acer          | Aspire one V1.03            | [455b9d5ac3](https://linux-hardware.org/?probe=455b9d5ac3) | Nov 17, 2020 |
| Acer          | Aspire E1-570G              | [3ac799a86e](https://linux-hardware.org/?probe=3ac799a86e) | Nov 17, 2020 |
| HP            | Pavilion x2 Detachable      | [14c5b0631b](https://linux-hardware.org/?probe=14c5b0631b) | Nov 17, 2020 |
| Toshiba       | Satellite Pro L550          | [0bd37ae304](https://linux-hardware.org/?probe=0bd37ae304) | Nov 16, 2020 |
| HP            | Pavilion dv6                | [b9e6c75b90](https://linux-hardware.org/?probe=b9e6c75b90) | Nov 15, 2020 |
| Dell          | Latitude E5440              | [b010db49f4](https://linux-hardware.org/?probe=b010db49f4) | Nov 15, 2020 |
| Acer          | Aspire 5630                 | [7479658951](https://linux-hardware.org/?probe=7479658951) | Nov 15, 2020 |
| Dell          | Latitude E6410              | [415cdc7c74](https://linux-hardware.org/?probe=415cdc7c74) | Nov 15, 2020 |
| HP            | EliteBook 840 G3            | [ec506b9770](https://linux-hardware.org/?probe=ec506b9770) | Nov 14, 2020 |
| Lenovo        | G550 20023                  | [9d67fb8d8b](https://linux-hardware.org/?probe=9d67fb8d8b) | Nov 13, 2020 |
| Fujitsu Si... | LIFEBOOK E8410              | [d79b3878a5](https://linux-hardware.org/?probe=d79b3878a5) | Nov 13, 2020 |
| Dell          | Latitude E6410              | [11be79ed72](https://linux-hardware.org/?probe=11be79ed72) | Nov 13, 2020 |
| Dell          | Inspiron 1545               | [3a0512d317](https://linux-hardware.org/?probe=3a0512d317) | Nov 13, 2020 |
| Dell          | Inspiron 1545               | [0c78c7bd9e](https://linux-hardware.org/?probe=0c78c7bd9e) | Nov 13, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [0470427c68](https://linux-hardware.org/?probe=0470427c68) | Nov 12, 2020 |
| HP            | Pavilion dv5000 (EP413UA... | [d8592798be](https://linux-hardware.org/?probe=d8592798be) | Nov 12, 2020 |
| ASUSTek       | M50Vm                       | [152f954015](https://linux-hardware.org/?probe=152f954015) | Nov 11, 2020 |
| ASUSTek       | M50Vm                       | [46b6e6863b](https://linux-hardware.org/?probe=46b6e6863b) | Nov 11, 2020 |
| HP            | Pavilion dv5                | [8be4ce3c5a](https://linux-hardware.org/?probe=8be4ce3c5a) | Nov 11, 2020 |
| Toshiba       | Satellite C660              | [a5ce6d0206](https://linux-hardware.org/?probe=a5ce6d0206) | Nov 11, 2020 |
| Notebook      | RIM2520                     | [771a897694](https://linux-hardware.org/?probe=771a897694) | Nov 11, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [2c5e88fe3a](https://linux-hardware.org/?probe=2c5e88fe3a) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | [cb23a45745](https://linux-hardware.org/?probe=cb23a45745) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | [ccdf1d9de6](https://linux-hardware.org/?probe=ccdf1d9de6) | Nov 10, 2020 |
| HP            | EliteBook 820 G2            | [d57310a957](https://linux-hardware.org/?probe=d57310a957) | Nov 10, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [4c0fec3ac5](https://linux-hardware.org/?probe=4c0fec3ac5) | Nov 09, 2020 |
| Lenovo        | S20-30 Touch 20434          | [bbac27d1f0](https://linux-hardware.org/?probe=bbac27d1f0) | Nov 08, 2020 |
| Lenovo        | ThinkPad T530 23595JU       | [2cce5c789a](https://linux-hardware.org/?probe=2cce5c789a) | Nov 08, 2020 |
| HP            | ENVY 15                     | [1fc6315caf](https://linux-hardware.org/?probe=1fc6315caf) | Nov 08, 2020 |
| HP            | ENVY 15                     | [996ca9b894](https://linux-hardware.org/?probe=996ca9b894) | Nov 08, 2020 |
| Dell          | Latitude D520               | [48ca9c477c](https://linux-hardware.org/?probe=48ca9c477c) | Nov 08, 2020 |
| Lenovo        | S20-30 Touch 20434          | [344bc8046a](https://linux-hardware.org/?probe=344bc8046a) | Nov 08, 2020 |
| HP            | Pavilion g6                 | [a1e12ac11a](https://linux-hardware.org/?probe=a1e12ac11a) | Nov 07, 2020 |
| HP            | 15                          | [a322932224](https://linux-hardware.org/?probe=a322932224) | Nov 07, 2020 |
| HP            | Pavilion g6                 | [c9fef7b025](https://linux-hardware.org/?probe=c9fef7b025) | Nov 07, 2020 |
| Toshiba       | Satellite C660              | [d5f99c156c](https://linux-hardware.org/?probe=d5f99c156c) | Nov 07, 2020 |
| Toshiba       | Satellite C660              | [45404bd97a](https://linux-hardware.org/?probe=45404bd97a) | Nov 07, 2020 |
| ASUSTek       | 1001PXD                     | [d50b2e1307](https://linux-hardware.org/?probe=d50b2e1307) | Nov 05, 2020 |
| Dell          | Inspiron 3421               | [e08c38affc](https://linux-hardware.org/?probe=e08c38affc) | Nov 04, 2020 |
| Dell          | System Inspiron N7110       | [df14fcf89e](https://linux-hardware.org/?probe=df14fcf89e) | Nov 04, 2020 |
| HP            | Compaq Presario CQ60        | [dd9a86b9e4](https://linux-hardware.org/?probe=dd9a86b9e4) | Nov 04, 2020 |
| HP            | Compaq Presario CQ60        | [04db08c84c](https://linux-hardware.org/?probe=04db08c84c) | Nov 04, 2020 |
| Acer          | Aspire 5742G                | [9bc7704a4f](https://linux-hardware.org/?probe=9bc7704a4f) | Nov 02, 2020 |
| Packard Be... | EasyNote TJ65               | [f4459e22c9](https://linux-hardware.org/?probe=f4459e22c9) | Nov 02, 2020 |
| Acer          | Aspire V5-531               | [8eb2cc2336](https://linux-hardware.org/?probe=8eb2cc2336) | Nov 01, 2020 |
| Acer          | Aspire 5742G                | [214289d932](https://linux-hardware.org/?probe=214289d932) | Oct 29, 2020 |
| HP            | 255 G5                      | [e0fe2872e1](https://linux-hardware.org/?probe=e0fe2872e1) | Oct 29, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [5e797005c4](https://linux-hardware.org/?probe=5e797005c4) | Oct 27, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3e49c517bb](https://linux-hardware.org/?probe=3e49c517bb) | Oct 25, 2020 |
| Acer          | Extensa 5635Z               | [c0b6900751](https://linux-hardware.org/?probe=c0b6900751) | Oct 24, 2020 |
| Toshiba       | Satellite P100              | [60e53b8e68](https://linux-hardware.org/?probe=60e53b8e68) | Oct 22, 2020 |
| Toshiba       | Satellite M70               | [b99abfd9d6](https://linux-hardware.org/?probe=b99abfd9d6) | Oct 21, 2020 |
| Sony          | SVE15115ENB                 | [fb5da6e89d](https://linux-hardware.org/?probe=fb5da6e89d) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6A... | [9565cc6937](https://linux-hardware.org/?probe=9565cc6937) | Oct 20, 2020 |
| HP            | Notebook                    | [8057d8104a](https://linux-hardware.org/?probe=8057d8104a) | Oct 19, 2020 |
| HP            | Compaq Presario CQ60        | [3b01f6d9e5](https://linux-hardware.org/?probe=3b01f6d9e5) | Oct 19, 2020 |
| HP            | Pavilion dv6                | [6fd2a79436](https://linux-hardware.org/?probe=6fd2a79436) | Oct 18, 2020 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [4408c079e4](https://linux-hardware.org/?probe=4408c079e4) | Oct 17, 2020 |
| ASUSTek       | K53BR                       | [11d1b669d5](https://linux-hardware.org/?probe=11d1b669d5) | Oct 17, 2020 |
| Unknown       | Unknown                     | [4b9298725d](https://linux-hardware.org/?probe=4b9298725d) | Oct 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [3a3de52609](https://linux-hardware.org/?probe=3a3de52609) | Oct 16, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [7e7adfbb13](https://linux-hardware.org/?probe=7e7adfbb13) | Oct 16, 2020 |
| Dell          | Vostro 3578                 | [aca3bf63fc](https://linux-hardware.org/?probe=aca3bf63fc) | Oct 16, 2020 |
| Lenovo        | ThinkPad T400 64752C3       | [1729f0708e](https://linux-hardware.org/?probe=1729f0708e) | Oct 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [b572236a74](https://linux-hardware.org/?probe=b572236a74) | Oct 14, 2020 |
| Dell          | Inspiron 15-3567            | [42a82239c5](https://linux-hardware.org/?probe=42a82239c5) | Oct 13, 2020 |
| HP            | Mini 5103                   | [d51f4ebf17](https://linux-hardware.org/?probe=d51f4ebf17) | Oct 13, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [6c015911fb](https://linux-hardware.org/?probe=6c015911fb) | Oct 12, 2020 |
| HP            | 2000                        | [36cb1ae33f](https://linux-hardware.org/?probe=36cb1ae33f) | Oct 12, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [7f2d533ddf](https://linux-hardware.org/?probe=7f2d533ddf) | Oct 12, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [00f264d5ce](https://linux-hardware.org/?probe=00f264d5ce) | Oct 12, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [78f452a46b](https://linux-hardware.org/?probe=78f452a46b) | Oct 12, 2020 |
| HP            | Pavilion dv6                | [5b878286a6](https://linux-hardware.org/?probe=5b878286a6) | Oct 10, 2020 |
| Lenovo        | Kona                        | [7490728355](https://linux-hardware.org/?probe=7490728355) | Oct 09, 2020 |
| HP            | Notebook                    | [60b847baba](https://linux-hardware.org/?probe=60b847baba) | Oct 08, 2020 |
| HP            | Pavilion Notebook           | [8e441f98e8](https://linux-hardware.org/?probe=8e441f98e8) | Oct 08, 2020 |
| ASUSTek       | G60VX                       | [737170838e](https://linux-hardware.org/?probe=737170838e) | Oct 07, 2020 |
| Panasonic     | CF-31JQH7MDM                | [bd9af285fe](https://linux-hardware.org/?probe=bd9af285fe) | Oct 07, 2020 |
| Dell          | Latitude E5470              | [a1ae53e261](https://linux-hardware.org/?probe=a1ae53e261) | Oct 06, 2020 |
| Dell          | Vostro 1510                 | [b2e8cb8306](https://linux-hardware.org/?probe=b2e8cb8306) | Oct 06, 2020 |
| Toshiba       | NB100                       | [0136048af7](https://linux-hardware.org/?probe=0136048af7) | Oct 06, 2020 |
| ASUSTek       | 1015PX                      | [4c53e6b790](https://linux-hardware.org/?probe=4c53e6b790) | Oct 05, 2020 |
| Acer          | AOD260                      | [df3f6056c4](https://linux-hardware.org/?probe=df3f6056c4) | Oct 05, 2020 |
| HP            | Presario C700 (GY219LA#A... | [4154ef951b](https://linux-hardware.org/?probe=4154ef951b) | Oct 03, 2020 |
| HP            | Presario C700 (GY219LA#A... | [322081e0c8](https://linux-hardware.org/?probe=322081e0c8) | Oct 03, 2020 |
| Fujitsu       | LIFEBOOK T730               | [79e7520c34](https://linux-hardware.org/?probe=79e7520c34) | Oct 02, 2020 |
| Fujitsu       | LIFEBOOK T730               | [df7fc1fcdd](https://linux-hardware.org/?probe=df7fc1fcdd) | Oct 02, 2020 |
| ASUSTek       | K54C                        | [b82b607833](https://linux-hardware.org/?probe=b82b607833) | Oct 02, 2020 |
| Toshiba       | Satellite A100              | [05371b4921](https://linux-hardware.org/?probe=05371b4921) | Oct 02, 2020 |
| HUAWEI        | HN-WX9X                     | [2b80873c58](https://linux-hardware.org/?probe=2b80873c58) | Oct 02, 2020 |
| Acer          | Makalu                      | [e68197eded](https://linux-hardware.org/?probe=e68197eded) | Sep 30, 2020 |
| Apple         | MacBook5,2                  | [47c45ae46f](https://linux-hardware.org/?probe=47c45ae46f) | Sep 30, 2020 |
| Acer          | AOD270                      | [4d7f40e97b](https://linux-hardware.org/?probe=4d7f40e97b) | Sep 30, 2020 |
| Apple         | MacBookPro8,1               | [7b095a0a58](https://linux-hardware.org/?probe=7b095a0a58) | Sep 30, 2020 |
| ASUSTek       | K54C                        | [a15a6332bf](https://linux-hardware.org/?probe=a15a6332bf) | Sep 30, 2020 |
| Lenovo        | 3000 N200 0769B6G           | [7e9967fb0e](https://linux-hardware.org/?probe=7e9967fb0e) | Sep 30, 2020 |
| HP            | 530                         | [c330f06c15](https://linux-hardware.org/?probe=c330f06c15) | Sep 30, 2020 |
| HP            | ZBook 17 G2                 | [0d0b182c79](https://linux-hardware.org/?probe=0d0b182c79) | Sep 27, 2020 |
| Dell          | Latitude D630               | [fa947637f9](https://linux-hardware.org/?probe=fa947637f9) | Sep 25, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | [fffe9391c2](https://linux-hardware.org/?probe=fffe9391c2) | Sep 25, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [31e0cd8ca1](https://linux-hardware.org/?probe=31e0cd8ca1) | Sep 24, 2020 |
| Acer          | Extensa 5620                | [2cd43c8065](https://linux-hardware.org/?probe=2cd43c8065) | Sep 24, 2020 |
| HP            | Laptop 15-bw0xx             | [9067f67190](https://linux-hardware.org/?probe=9067f67190) | Sep 24, 2020 |
| Acer          | Swift SF314-42              | [03a2ad0203](https://linux-hardware.org/?probe=03a2ad0203) | Sep 23, 2020 |
| Sony          | VGN-SZ4VWN_X                | [b5f136ce13](https://linux-hardware.org/?probe=b5f136ce13) | Sep 23, 2020 |
| Fujitsu Si... | AMILO Li3710                | [4e11c10492](https://linux-hardware.org/?probe=4e11c10492) | Sep 23, 2020 |
| Fujitsu Si... | AMILO Li3710                | [a5d32c72d2](https://linux-hardware.org/?probe=a5d32c72d2) | Sep 23, 2020 |
| Sony          | VGN-CR120E                  | [8569f91c17](https://linux-hardware.org/?probe=8569f91c17) | Sep 23, 2020 |
| HP            | EliteBook 840 G4            | [adec24022c](https://linux-hardware.org/?probe=adec24022c) | Sep 22, 2020 |
| ASUSTek       | W7J                         | [70078e77fa](https://linux-hardware.org/?probe=70078e77fa) | Sep 22, 2020 |
| Acer          | Swift SF314-42              | [a243f6284c](https://linux-hardware.org/?probe=a243f6284c) | Sep 21, 2020 |
| Dell          | Inspiron 1110               | [01517be2d7](https://linux-hardware.org/?probe=01517be2d7) | Sep 20, 2020 |
| ASUSTek       | G74Sx                       | [76f3c2d574](https://linux-hardware.org/?probe=76f3c2d574) | Sep 20, 2020 |
| AMI           | Cherry Trail CR             | [a1343de48d](https://linux-hardware.org/?probe=a1343de48d) | Sep 20, 2020 |
| Toshiba       | Satellite C660              | [ba30a12748](https://linux-hardware.org/?probe=ba30a12748) | Sep 19, 2020 |
| HP            | ENVY Notebook               | [fab3ee0d2e](https://linux-hardware.org/?probe=fab3ee0d2e) | Sep 19, 2020 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [fe11f72b06](https://linux-hardware.org/?probe=fe11f72b06) | Sep 19, 2020 |
| HP            | ProBook 4540s               | [9ca21222f5](https://linux-hardware.org/?probe=9ca21222f5) | Sep 19, 2020 |
| HP            | Compaq Presario C700        | [4e8ba77ee3](https://linux-hardware.org/?probe=4e8ba77ee3) | Sep 18, 2020 |
| HP            | Compaq Presario C700        | [b9b510693c](https://linux-hardware.org/?probe=b9b510693c) | Sep 18, 2020 |
| Acer          | AO722                       | [d4c9b21741](https://linux-hardware.org/?probe=d4c9b21741) | Sep 18, 2020 |
| Toshiba       | NA 1402                     | [e1d38cee7f](https://linux-hardware.org/?probe=e1d38cee7f) | Sep 17, 2020 |
| HP            | Mini 210-1100               | [3b76e02a8f](https://linux-hardware.org/?probe=3b76e02a8f) | Sep 17, 2020 |
| Packard Be... | EasyNote ENTF71BM           | [b6c8ba71e9](https://linux-hardware.org/?probe=b6c8ba71e9) | Sep 17, 2020 |
| Packard Be... | EasyNote ENTF71BM           | [e09802de6b](https://linux-hardware.org/?probe=e09802de6b) | Sep 17, 2020 |
| Dell          | Inspiron 5577               | [17862346f8](https://linux-hardware.org/?probe=17862346f8) | Sep 15, 2020 |
| Acer          | Aspire 7520                 | [d8ae16fc0b](https://linux-hardware.org/?probe=d8ae16fc0b) | Sep 14, 2020 |
| Unknown       | Unknown                     | [2c52151f77](https://linux-hardware.org/?probe=2c52151f77) | Sep 13, 2020 |
| Acer          | AO722                       | [39f920ae53](https://linux-hardware.org/?probe=39f920ae53) | Sep 13, 2020 |
| ASUSTek       | N750JK                      | [e140f6e3e4](https://linux-hardware.org/?probe=e140f6e3e4) | Sep 12, 2020 |
| Unknown       | Unknown                     | [922d1c2533](https://linux-hardware.org/?probe=922d1c2533) | Sep 11, 2020 |
| Unknown       | Unknown                     | [f56d6dcffd](https://linux-hardware.org/?probe=f56d6dcffd) | Sep 11, 2020 |
| HP            | 530                         | [e0ea19e1dc](https://linux-hardware.org/?probe=e0ea19e1dc) | Sep 10, 2020 |
| HP            | Pavilion dv5                | [f5a369d166](https://linux-hardware.org/?probe=f5a369d166) | Sep 10, 2020 |
| HP            | Pavilion dv5                | [f9f9a9ca5f](https://linux-hardware.org/?probe=f9f9a9ca5f) | Sep 09, 2020 |
| Acer          | Aspire A315-21              | [07fb4fed45](https://linux-hardware.org/?probe=07fb4fed45) | Sep 08, 2020 |
| HP            | 530                         | [8d751d7d91](https://linux-hardware.org/?probe=8d751d7d91) | Sep 07, 2020 |
| Lenovo        | ThinkPad T520 4239CTO       | [fa8846ee61](https://linux-hardware.org/?probe=fa8846ee61) | Sep 07, 2020 |
| Dell          | Inspiron 5577               | [da6490c410](https://linux-hardware.org/?probe=da6490c410) | Sep 06, 2020 |
| Toshiba       | Satellite L855D             | [a14d72d23c](https://linux-hardware.org/?probe=a14d72d23c) | Sep 06, 2020 |
| ASUSTek       | W7J                         | [c505a80ea5](https://linux-hardware.org/?probe=c505a80ea5) | Sep 06, 2020 |
| Dell          | Vostro 3700                 | [c9b764a48b](https://linux-hardware.org/?probe=c9b764a48b) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | [4ddf924081](https://linux-hardware.org/?probe=4ddf924081) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | [23a0e05047](https://linux-hardware.org/?probe=23a0e05047) | Sep 05, 2020 |
| HP            | EliteBook 840 G6            | [4a5bac87d8](https://linux-hardware.org/?probe=4a5bac87d8) | Sep 04, 2020 |
| Dell          | Inspiron N4010              | [59357480b7](https://linux-hardware.org/?probe=59357480b7) | Sep 04, 2020 |
| Toshiba       | Satellite C650D             | [c661cb7e35](https://linux-hardware.org/?probe=c661cb7e35) | Sep 03, 2020 |
| HP            | Laptop 15-bw0xx             | [02c0bf156d](https://linux-hardware.org/?probe=02c0bf156d) | Sep 03, 2020 |
| HP            | Presario CQ57               | [2dcab385bd](https://linux-hardware.org/?probe=2dcab385bd) | Sep 03, 2020 |
| Dell          | Inspiron 3542               | [9661146a6a](https://linux-hardware.org/?probe=9661146a6a) | Sep 02, 2020 |
| Acer          | Aspire one V1.13            | [37b4d70de4](https://linux-hardware.org/?probe=37b4d70de4) | Sep 01, 2020 |
| Toshiba       | Satellite C55-A-16D         | [ffb7e1e547](https://linux-hardware.org/?probe=ffb7e1e547) | Aug 31, 2020 |
| Dell          | Inspiron 15-3567            | [f9903ce5d2](https://linux-hardware.org/?probe=f9903ce5d2) | Aug 31, 2020 |
| Toshiba       | Satellite Pro L550          | [02e28c5706](https://linux-hardware.org/?probe=02e28c5706) | Aug 30, 2020 |
| Apple         | MacBookAir3,1               | [a3168c57ea](https://linux-hardware.org/?probe=a3168c57ea) | Aug 30, 2020 |
| Dell          | Inspiron 1520               | [6d520f3f75](https://linux-hardware.org/?probe=6d520f3f75) | Aug 29, 2020 |
| HP            | Laptop 14-dk1xxx            | [f72e36a4c1](https://linux-hardware.org/?probe=f72e36a4c1) | Aug 28, 2020 |
| Dell          | Inspiron N4010              | [f80559862a](https://linux-hardware.org/?probe=f80559862a) | Aug 27, 2020 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [a2b597141c](https://linux-hardware.org/?probe=a2b597141c) | Aug 27, 2020 |
| HP            | Pavilion g4                 | [55dec82070](https://linux-hardware.org/?probe=55dec82070) | Aug 26, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [de3f00fc50](https://linux-hardware.org/?probe=de3f00fc50) | Aug 26, 2020 |
| Lenovo        | G475 20080                  | [c97ad59308](https://linux-hardware.org/?probe=c97ad59308) | Aug 26, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [6b7781d4f0](https://linux-hardware.org/?probe=6b7781d4f0) | Aug 25, 2020 |
| Acer          | Aspire A515-52G             | [86a890eb18](https://linux-hardware.org/?probe=86a890eb18) | Aug 23, 2020 |
| Acer          | Aspire A515-52G             | [5034bf6bc3](https://linux-hardware.org/?probe=5034bf6bc3) | Aug 23, 2020 |
| Dell          | Inspiron MM061              | [a34d3a0236](https://linux-hardware.org/?probe=a34d3a0236) | Aug 22, 2020 |
| Unknown       | Unknown                     | [858431dd69](https://linux-hardware.org/?probe=858431dd69) | Aug 22, 2020 |
| HP            | EliteBook 725 G2            | [f9f5c68624](https://linux-hardware.org/?probe=f9f5c68624) | Aug 22, 2020 |
| Dell          | Inspiron 1545               | [0502d22a6e](https://linux-hardware.org/?probe=0502d22a6e) | Aug 22, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [955166808e](https://linux-hardware.org/?probe=955166808e) | Aug 22, 2020 |
| Lenovo        | 4068RZ7                     | [a019743ebe](https://linux-hardware.org/?probe=a019743ebe) | Aug 20, 2020 |
| Lenovo        | 4068RZ7                     | [8b55712014](https://linux-hardware.org/?probe=8b55712014) | Aug 20, 2020 |
| Dell          | Inspiron 1545               | [20a0eaa36a](https://linux-hardware.org/?probe=20a0eaa36a) | Aug 20, 2020 |
| Toshiba       | Satellite L670D             | [746e1de754](https://linux-hardware.org/?probe=746e1de754) | Aug 19, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [47f5ea43b8](https://linux-hardware.org/?probe=47f5ea43b8) | Aug 18, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [712e524505](https://linux-hardware.org/?probe=712e524505) | Aug 18, 2020 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [188c3f31c6](https://linux-hardware.org/?probe=188c3f31c6) | Aug 18, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [55d79e4d6a](https://linux-hardware.org/?probe=55d79e4d6a) | Aug 17, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [19b6cecfad](https://linux-hardware.org/?probe=19b6cecfad) | Aug 17, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [5faf279c4f](https://linux-hardware.org/?probe=5faf279c4f) | Aug 17, 2020 |
| HP            | Laptop 15-bs0xx             | [45004f5195](https://linux-hardware.org/?probe=45004f5195) | Aug 17, 2020 |
| Medion        | ERAZER X7853 MD60604        | [1216fcc86c](https://linux-hardware.org/?probe=1216fcc86c) | Aug 16, 2020 |
| Medion        | ERAZER X7853 MD60604        | [6be345d7bd](https://linux-hardware.org/?probe=6be345d7bd) | Aug 16, 2020 |
| Samsung       | 400B4B/400B5B/200B4B/200... | [299e17392c](https://linux-hardware.org/?probe=299e17392c) | Aug 15, 2020 |
| Acer          | Aspire one V1.13            | [c2802686dc](https://linux-hardware.org/?probe=c2802686dc) | Aug 15, 2020 |
| Dell          | G5 5505                     | [9d7d4c771b](https://linux-hardware.org/?probe=9d7d4c771b) | Aug 14, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [72b1361358](https://linux-hardware.org/?probe=72b1361358) | Aug 13, 2020 |
| Toshiba       | STI NA 1402                 | [d75672b88f](https://linux-hardware.org/?probe=d75672b88f) | Aug 13, 2020 |
| Alienware     | 15                          | [4b1d9f9153](https://linux-hardware.org/?probe=4b1d9f9153) | Aug 13, 2020 |
| Alienware     | 15                          | [dfde91faf2](https://linux-hardware.org/?probe=dfde91faf2) | Aug 13, 2020 |
| Toshiba       | Satellite C650              | [0b2880b414](https://linux-hardware.org/?probe=0b2880b414) | Aug 12, 2020 |
| Dell          | G5 5505                     | [c4a555abaa](https://linux-hardware.org/?probe=c4a555abaa) | Aug 12, 2020 |
| MSI           | GT72 2PC                    | [464657ada9](https://linux-hardware.org/?probe=464657ada9) | Aug 11, 2020 |
| Acer          | Aspire 5532                 | [6d1ed17c3a](https://linux-hardware.org/?probe=6d1ed17c3a) | Aug 10, 2020 |
| HP            | 255 G3                      | [4d659eb265](https://linux-hardware.org/?probe=4d659eb265) | Aug 10, 2020 |
| Bluechip C... | Crestline & ICH8M Chipse... | [9b8c4353cc](https://linux-hardware.org/?probe=9b8c4353cc) | Aug 09, 2020 |
| HP            | G62                         | [79f5cf8c86](https://linux-hardware.org/?probe=79f5cf8c86) | Aug 08, 2020 |
| HP            | 14                          | [b7289075c1](https://linux-hardware.org/?probe=b7289075c1) | Aug 08, 2020 |
| Dell          | Vostro 15-3568              | [3b1e04b2da](https://linux-hardware.org/?probe=3b1e04b2da) | Aug 07, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [df9004d133](https://linux-hardware.org/?probe=df9004d133) | Aug 07, 2020 |
| HP            | ProBook 650 G1              | [3790f3b233](https://linux-hardware.org/?probe=3790f3b233) | Aug 07, 2020 |
| Toshiba       | Satellite C55-A             | [8fb6762361](https://linux-hardware.org/?probe=8fb6762361) | Aug 06, 2020 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [b9fddd15e8](https://linux-hardware.org/?probe=b9fddd15e8) | Aug 05, 2020 |
| Toshiba       | Satellite L670D             | [d28122373c](https://linux-hardware.org/?probe=d28122373c) | Aug 05, 2020 |
| HP            | EliteBook 8460p             | [452088e655](https://linux-hardware.org/?probe=452088e655) | Aug 03, 2020 |
| Dell          | Inspiron MP061              | [7355e190ca](https://linux-hardware.org/?probe=7355e190ca) | Aug 03, 2020 |
| HP            | Pavilion g4                 | [4fc16d6e09](https://linux-hardware.org/?probe=4fc16d6e09) | Aug 02, 2020 |
| HP            | Pavilion g4                 | [0b9fc56cd1](https://linux-hardware.org/?probe=0b9fc56cd1) | Aug 02, 2020 |
| Unknown       | Unknown                     | [59c9ce7401](https://linux-hardware.org/?probe=59c9ce7401) | Aug 02, 2020 |
| Dell          | Latitude E5450              | [884ee42c35](https://linux-hardware.org/?probe=884ee42c35) | Aug 01, 2020 |
| ASUSTek       | GX501VIK                    | [de4780e6e4](https://linux-hardware.org/?probe=de4780e6e4) | Aug 01, 2020 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [18b9136e87](https://linux-hardware.org/?probe=18b9136e87) | Aug 01, 2020 |
| Dell          | Inspiron N5050              | [cb18c38bd3](https://linux-hardware.org/?probe=cb18c38bd3) | Jul 30, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [dc8ed0c837](https://linux-hardware.org/?probe=dc8ed0c837) | Jul 30, 2020 |
| HP            | EliteBook 2760p             | [ef84151f18](https://linux-hardware.org/?probe=ef84151f18) | Jul 29, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [3db826b463](https://linux-hardware.org/?probe=3db826b463) | Jul 29, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [3fd417f684](https://linux-hardware.org/?probe=3fd417f684) | Jul 29, 2020 |
| HP            | ProBook 6470b               | [fe3206ee5f](https://linux-hardware.org/?probe=fe3206ee5f) | Jul 28, 2020 |
| Toshiba       | Satellite L670D             | [91a4aad7d7](https://linux-hardware.org/?probe=91a4aad7d7) | Jul 28, 2020 |
| Toshiba       | Satellite L670D             | [10658a729f](https://linux-hardware.org/?probe=10658a729f) | Jul 28, 2020 |
| HP            | 1000                        | [d0cdc87248](https://linux-hardware.org/?probe=d0cdc87248) | Jul 27, 2020 |
| Lenovo        | G560 20042                  | [fb76f0edee](https://linux-hardware.org/?probe=fb76f0edee) | Jul 27, 2020 |
| Acer          | Aspire 5741                 | [6fa0f96d6b](https://linux-hardware.org/?probe=6fa0f96d6b) | Jul 27, 2020 |
| HP            | 1000                        | [36db752887](https://linux-hardware.org/?probe=36db752887) | Jul 26, 2020 |
| Sony          | VPCYB35AB                   | [6cc28f56ff](https://linux-hardware.org/?probe=6cc28f56ff) | Jul 26, 2020 |
| Sony          | VPCYB35AB                   | [4b5b2115c1](https://linux-hardware.org/?probe=4b5b2115c1) | Jul 26, 2020 |
| ASUSTek       | G750JM                      | [9b3a5ac253](https://linux-hardware.org/?probe=9b3a5ac253) | Jul 25, 2020 |
| Dell          | Inspiron 1545               | [57675258c0](https://linux-hardware.org/?probe=57675258c0) | Jul 25, 2020 |
| Compal        | HGL31I                      | [8f7aac30a8](https://linux-hardware.org/?probe=8f7aac30a8) | Jul 25, 2020 |
| Dell          | Latitude E6420              | [0de23594ba](https://linux-hardware.org/?probe=0de23594ba) | Jul 24, 2020 |
| Acer          | Aspire 5750                 | [fbb8795c20](https://linux-hardware.org/?probe=fbb8795c20) | Jul 24, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [8dd238e5a1](https://linux-hardware.org/?probe=8dd238e5a1) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15API 81V7     | [d65a2f5a5a](https://linux-hardware.org/?probe=d65a2f5a5a) | Jul 24, 2020 |
| HP            | 14                          | [143464e093](https://linux-hardware.org/?probe=143464e093) | Jul 24, 2020 |
| Dell          | Vostro 3460                 | [ecdbc21896](https://linux-hardware.org/?probe=ecdbc21896) | Jul 24, 2020 |
| Clevo         | M540SR VT6363A              | [b5b4e22b05](https://linux-hardware.org/?probe=b5b4e22b05) | Jul 21, 2020 |
| Dell          | Vostro 15-3568              | [7ef51b8ffe](https://linux-hardware.org/?probe=7ef51b8ffe) | Jul 20, 2020 |
| Dell          | Vostro 15-3568              | [7ba1b7b850](https://linux-hardware.org/?probe=7ba1b7b850) | Jul 19, 2020 |
| Digibras      | NH4CU03                     | [3bad8b713e](https://linux-hardware.org/?probe=3bad8b713e) | Jul 19, 2020 |
| HP            | ElitePad 1000 G2            | [a8871cdcff](https://linux-hardware.org/?probe=a8871cdcff) | Jul 19, 2020 |
| HP            | Notebook                    | [875e3886d1](https://linux-hardware.org/?probe=875e3886d1) | Jul 18, 2020 |
| Dell          | Studio 1737                 | [b08787e998](https://linux-hardware.org/?probe=b08787e998) | Jul 17, 2020 |
| Acer          | Aspire 5715Z                | [929559cae0](https://linux-hardware.org/?probe=929559cae0) | Jul 17, 2020 |
| HP            | Laptop 14-dq1xxx            | [1e49fe5909](https://linux-hardware.org/?probe=1e49fe5909) | Jul 16, 2020 |
| Google        | Chell                       | [fb663766c0](https://linux-hardware.org/?probe=fb663766c0) | Jul 16, 2020 |
| Google        | Chell                       | [af33f4bc7b](https://linux-hardware.org/?probe=af33f4bc7b) | Jul 15, 2020 |
| HP            | EliteBook 840 G2            | [a2a8e9d267](https://linux-hardware.org/?probe=a2a8e9d267) | Jul 13, 2020 |
| Sony          | VGN-P11Z_G                  | [7615c6d02b](https://linux-hardware.org/?probe=7615c6d02b) | Jul 11, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | [8164d6222a](https://linux-hardware.org/?probe=8164d6222a) | Jul 11, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | [478d2b6718](https://linux-hardware.org/?probe=478d2b6718) | Jul 11, 2020 |
| Lenovo        | BP PV CLASSMATE+            | [0e381612fb](https://linux-hardware.org/?probe=0e381612fb) | Jul 11, 2020 |
| Toshiba       | Satellite C660              | [b15da8cdfc](https://linux-hardware.org/?probe=b15da8cdfc) | Jul 11, 2020 |
| HP            | ElitePad 1000 G2            | [b2c793bfb4](https://linux-hardware.org/?probe=b2c793bfb4) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | [152f8e9ebd](https://linux-hardware.org/?probe=152f8e9ebd) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | [5054174795](https://linux-hardware.org/?probe=5054174795) | Jul 08, 2020 |
| ASUSTek       | GX501VIK                    | [0dc513d440](https://linux-hardware.org/?probe=0dc513d440) | Jul 07, 2020 |
| UMAX          | VisionBook 14Wg Pro         | [5d2b6ed775](https://linux-hardware.org/?probe=5d2b6ed775) | Jul 06, 2020 |
| Dell          | Latitude E6520              | [c11c08470c](https://linux-hardware.org/?probe=c11c08470c) | Jul 06, 2020 |
| ECS           | G410                        | [38bad5d8cb](https://linux-hardware.org/?probe=38bad5d8cb) | Jul 05, 2020 |
| Samsung       | N150                        | [76e856e9e9](https://linux-hardware.org/?probe=76e856e9e9) | Jul 04, 2020 |
| Samsung       | N150                        | [cf90fb442b](https://linux-hardware.org/?probe=cf90fb442b) | Jul 04, 2020 |
| Lenovo        | ThinkPad X140e 20BMS00E0... | [ee2280ecd4](https://linux-hardware.org/?probe=ee2280ecd4) | Jul 04, 2020 |
| Toshiba       | Satellite C40-A             | [672cca96fd](https://linux-hardware.org/?probe=672cca96fd) | Jul 04, 2020 |
| Acer          | Lugano M                    | [c3722a65f4](https://linux-hardware.org/?probe=c3722a65f4) | Jul 04, 2020 |
| WIPRO         | WIVNB7B1623-0002            | [4669989193](https://linux-hardware.org/?probe=4669989193) | Jul 03, 2020 |
| Acer          | Lugano M                    | [d91f2c3af1](https://linux-hardware.org/?probe=d91f2c3af1) | Jul 03, 2020 |
| Dell          | Latitude E6440              | [521818b099](https://linux-hardware.org/?probe=521818b099) | Jul 02, 2020 |
| HP            | ProBook 450 G3              | [cf66568c1a](https://linux-hardware.org/?probe=cf66568c1a) | Jul 01, 2020 |
| HP            | Notebook                    | [1b077e7d7e](https://linux-hardware.org/?probe=1b077e7d7e) | Jun 30, 2020 |
| HP            | G60                         | [2c11d20a74](https://linux-hardware.org/?probe=2c11d20a74) | Jun 29, 2020 |
| Toshiba       | Satellite C645              | [962d89d16d](https://linux-hardware.org/?probe=962d89d16d) | Jun 29, 2020 |
| Toshiba       | Satellite C645              | [bec8895749](https://linux-hardware.org/?probe=bec8895749) | Jun 29, 2020 |
| Toshiba       | Satellite S50-B             | [2e8165ca6a](https://linux-hardware.org/?probe=2e8165ca6a) | Jun 28, 2020 |
| Dell          | Inspiron 1525               | [754b2de717](https://linux-hardware.org/?probe=754b2de717) | Jun 27, 2020 |
| Dell          | System Vostro 3450          | [6ecdf91891](https://linux-hardware.org/?probe=6ecdf91891) | Jun 27, 2020 |
| Alienware     | M17x                        | [4a26920858](https://linux-hardware.org/?probe=4a26920858) | Jun 26, 2020 |
| Toshiba       | Satellite L655              | [d03c7bb948](https://linux-hardware.org/?probe=d03c7bb948) | Jun 26, 2020 |
| Toshiba       | Satellite L655              | [002ace5d32](https://linux-hardware.org/?probe=002ace5d32) | Jun 26, 2020 |
| Acer          | Aspire A515-51              | [636d176056](https://linux-hardware.org/?probe=636d176056) | Jun 25, 2020 |
| Dell          | Latitude E6440              | [1ffde1aa78](https://linux-hardware.org/?probe=1ffde1aa78) | Jun 24, 2020 |
| UMAX          | VisionBook 14Wg Pro         | [a50a75e674](https://linux-hardware.org/?probe=a50a75e674) | Jun 21, 2020 |
| Acer          | Aspire S3                   | [431c5f1360](https://linux-hardware.org/?probe=431c5f1360) | Jun 20, 2020 |
| Acer          | Aspire S3                   | [2ecc528f99](https://linux-hardware.org/?probe=2ecc528f99) | Jun 20, 2020 |
| ASUSTek       | TP300LA                     | [a24e3e59e4](https://linux-hardware.org/?probe=a24e3e59e4) | Jun 20, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [c2f7f39a83](https://linux-hardware.org/?probe=c2f7f39a83) | Jun 20, 2020 |
| HP            | ProBook 6470b               | [37be0cfc66](https://linux-hardware.org/?probe=37be0cfc66) | Jun 19, 2020 |
| Lenovo        | G50-30 80G0                 | [d9f9497fd7](https://linux-hardware.org/?probe=d9f9497fd7) | Jun 19, 2020 |
| Qbex          | K131                        | [4f86406fcd](https://linux-hardware.org/?probe=4f86406fcd) | Jun 18, 2020 |
| Toshiba       | Satellite C55D-B            | [8e66b0c5f9](https://linux-hardware.org/?probe=8e66b0c5f9) | Jun 17, 2020 |
| HP            | Pavilion dm1                | [cfa6ec6eee](https://linux-hardware.org/?probe=cfa6ec6eee) | Jun 17, 2020 |
| HP            | Laptop 15-bw0xx             | [b19bfe7909](https://linux-hardware.org/?probe=b19bfe7909) | Jun 16, 2020 |
| HP            | Compaq Mini                 | [bb593c0696](https://linux-hardware.org/?probe=bb593c0696) | Jun 16, 2020 |
| Dell          | Inspiron 14-3452            | [c83e4c2dd8](https://linux-hardware.org/?probe=c83e4c2dd8) | Jun 15, 2020 |
| Samsung       | N130                        | [4e60aa279e](https://linux-hardware.org/?probe=4e60aa279e) | Jun 14, 2020 |
| HP            | ProBook 6470b               | [f5cc0bfea1](https://linux-hardware.org/?probe=f5cc0bfea1) | Jun 14, 2020 |
| Toshiba       | Satellite C55-A             | [7c435001c2](https://linux-hardware.org/?probe=7c435001c2) | Jun 14, 2020 |
| HP            | EliteBook 6930p             | [521bd09de6](https://linux-hardware.org/?probe=521bd09de6) | Jun 13, 2020 |
| ASUSTek       | K75DE                       | [ab5984d317](https://linux-hardware.org/?probe=ab5984d317) | Jun 13, 2020 |
| ASUSTek       | K75DE                       | [3a77ccc6d1](https://linux-hardware.org/?probe=3a77ccc6d1) | Jun 13, 2020 |
| HP            | ProBook 450 G3              | [7c8e952de0](https://linux-hardware.org/?probe=7c8e952de0) | Jun 12, 2020 |
| HP            | ENVY TS m7                  | [3186cbcb82](https://linux-hardware.org/?probe=3186cbcb82) | Jun 12, 2020 |
| ASUSTek       | UX331UA                     | [064e95c086](https://linux-hardware.org/?probe=064e95c086) | Jun 10, 2020 |
| Apple         | MacBookAir3,1               | [e31264d63b](https://linux-hardware.org/?probe=e31264d63b) | Jun 09, 2020 |
| Apple         | MacBookAir3,1               | [7ebb47dc43](https://linux-hardware.org/?probe=7ebb47dc43) | Jun 09, 2020 |
| Acer          | AOD270                      | [3a0d567ba7](https://linux-hardware.org/?probe=3a0d567ba7) | Jun 09, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [27b21d21f9](https://linux-hardware.org/?probe=27b21d21f9) | Jun 09, 2020 |
| Toshiba       | PORTEGE Z20t-C              | [4e2285206e](https://linux-hardware.org/?probe=4e2285206e) | Jun 07, 2020 |
| HP            | Laptop 17-by0xxx            | [95415bf222](https://linux-hardware.org/?probe=95415bf222) | Jun 06, 2020 |
| HP            | Laptop 17-by0xxx            | [9fb0632ef6](https://linux-hardware.org/?probe=9fb0632ef6) | Jun 06, 2020 |
| Fujitsu Si... | LIFEBOOK S7220              | [f3c44830da](https://linux-hardware.org/?probe=f3c44830da) | Jun 06, 2020 |
| Toshiba       | Satellite A100              | [eddce8db1a](https://linux-hardware.org/?probe=eddce8db1a) | Jun 05, 2020 |
| HP            | Pavilion dv6700             | [a53258f04c](https://linux-hardware.org/?probe=a53258f04c) | Jun 05, 2020 |
| ASUSTek       | X555LD                      | [5fcb4e6866](https://linux-hardware.org/?probe=5fcb4e6866) | Jun 03, 2020 |
| Dell          | Latitude XT2                | [5970770ec5](https://linux-hardware.org/?probe=5970770ec5) | Jun 03, 2020 |
| Dell          | Latitude XT2                | [bc35b5f660](https://linux-hardware.org/?probe=bc35b5f660) | Jun 03, 2020 |
| Dell          | Latitude XT2                | [0f863604a4](https://linux-hardware.org/?probe=0f863604a4) | Jun 03, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [76c2001b93](https://linux-hardware.org/?probe=76c2001b93) | Jun 03, 2020 |
| ASUSTek       | UX331UA                     | [8ca766622f](https://linux-hardware.org/?probe=8ca766622f) | Jun 02, 2020 |
| HP            | EliteBook 8770w             | [9bba8e0daf](https://linux-hardware.org/?probe=9bba8e0daf) | Jun 01, 2020 |
| Lenovo        | ThinkPad W520 42844LG       | [9bc21e2e76](https://linux-hardware.org/?probe=9bc21e2e76) | Jun 01, 2020 |
| Dell          | Vostro 5470                 | [c519aedd88](https://linux-hardware.org/?probe=c519aedd88) | Jun 01, 2020 |
| Acer          | Aspire A315-51              | [b524806f7a](https://linux-hardware.org/?probe=b524806f7a) | May 31, 2020 |
| HP            | Pavilion dv6000 (RP986EA... | [1e4d134edf](https://linux-hardware.org/?probe=1e4d134edf) | May 30, 2020 |
| HP            | 635                         | [4c1e9766eb](https://linux-hardware.org/?probe=4c1e9766eb) | May 30, 2020 |
| HP            | Laptop 15-dw0xxx            | [3717bb5ab4](https://linux-hardware.org/?probe=3717bb5ab4) | May 29, 2020 |
| Notebook      | P570WM                      | [1694f6a1b4](https://linux-hardware.org/?probe=1694f6a1b4) | May 28, 2020 |
| Insyde        | TW36                        | [7038a5c61c](https://linux-hardware.org/?probe=7038a5c61c) | May 28, 2020 |
| Dell          | Inspiron 5480               | [aeaf1790c2](https://linux-hardware.org/?probe=aeaf1790c2) | May 28, 2020 |
| HP            | 635                         | [fec1f36696](https://linux-hardware.org/?probe=fec1f36696) | May 27, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [0508854129](https://linux-hardware.org/?probe=0508854129) | May 27, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [e6a298846b](https://linux-hardware.org/?probe=e6a298846b) | May 27, 2020 |
| Dell          | Latitude XT2                | [760d50a6bc](https://linux-hardware.org/?probe=760d50a6bc) | May 26, 2020 |
| Durabook      | S15H                        | [2599b1778a](https://linux-hardware.org/?probe=2599b1778a) | May 26, 2020 |
| Durabook      | S15H                        | [3563afb99e](https://linux-hardware.org/?probe=3563afb99e) | May 26, 2020 |
| Dell          | Inspiron 14-3452            | [f894499ac3](https://linux-hardware.org/?probe=f894499ac3) | May 26, 2020 |
| Dell          | Inspiron 1440               | [51cbf53227](https://linux-hardware.org/?probe=51cbf53227) | May 26, 2020 |
| HP            | 15                          | [c39075bd80](https://linux-hardware.org/?probe=c39075bd80) | May 25, 2020 |
| ASUSTek       | Z450LA                      | [e64dcdf564](https://linux-hardware.org/?probe=e64dcdf564) | May 24, 2020 |
| Lenovo        | ThinkPad X140e 20BMS00E0... | [edc9f5d43a](https://linux-hardware.org/?probe=edc9f5d43a) | May 24, 2020 |
| Acer          | Aspire one                  | [610bb91d45](https://linux-hardware.org/?probe=610bb91d45) | May 23, 2020 |
| ASUSTek       | P552SA                      | [cd07bb014c](https://linux-hardware.org/?probe=cd07bb014c) | May 23, 2020 |
| Acer          | Aspire 5755G                | [58e9aedfca](https://linux-hardware.org/?probe=58e9aedfca) | May 23, 2020 |
| Lenovo        | V145-15AST 81MT             | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| HP            | Pavilion (EC436AV#ABA)      | [16430a960e](https://linux-hardware.org/?probe=16430a960e) | May 22, 2020 |
| Acer          | AOD270                      | [e254f3b7e5](https://linux-hardware.org/?probe=e254f3b7e5) | May 22, 2020 |
| Sony          | VGN-AW11Z_B                 | [71a7a9f1f3](https://linux-hardware.org/?probe=71a7a9f1f3) | May 22, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [29131d3d86](https://linux-hardware.org/?probe=29131d3d86) | May 21, 2020 |
| HP            | ZBook 17 G5                 | [81b70e2c63](https://linux-hardware.org/?probe=81b70e2c63) | May 21, 2020 |
| ASUSTek       | 1005P                       | [a2b309ff12](https://linux-hardware.org/?probe=a2b309ff12) | May 21, 2020 |
| HP            | EliteBook 840 G1            | [a39e33b1f4](https://linux-hardware.org/?probe=a39e33b1f4) | May 20, 2020 |
| HP            | EliteBook 840 G1            | [4f773edbaa](https://linux-hardware.org/?probe=4f773edbaa) | May 20, 2020 |
| Dell          | Inspiron 1420               | [1269d54a19](https://linux-hardware.org/?probe=1269d54a19) | May 20, 2020 |
| ASUSTek       | K84L                        | [01c734a603](https://linux-hardware.org/?probe=01c734a603) | May 19, 2020 |
| Acer          | Aspire ES1-711              | [f0d922b2a0](https://linux-hardware.org/?probe=f0d922b2a0) | May 19, 2020 |
| ASUSTek       | K50AB                       | [96ccf326a8](https://linux-hardware.org/?probe=96ccf326a8) | May 19, 2020 |
| Advantec      | CX23200W                    | [3c46531687](https://linux-hardware.org/?probe=3c46531687) | May 18, 2020 |
| HP            | EliteBook 6930p             | [0659c564f2](https://linux-hardware.org/?probe=0659c564f2) | May 17, 2020 |
| Dell          | Latitude E5570              | [7e63fb0312](https://linux-hardware.org/?probe=7e63fb0312) | May 17, 2020 |
| HP            | Presario V5000 (EX096PA#... | [f3c46cc46c](https://linux-hardware.org/?probe=f3c46cc46c) | May 17, 2020 |
| Lenovo        | Unknown                     | [ff60458293](https://linux-hardware.org/?probe=ff60458293) | May 17, 2020 |
| Lenovo        | Unknown                     | [2176e7fb78](https://linux-hardware.org/?probe=2176e7fb78) | May 17, 2020 |
| Samsung       | N150P/N210P/N220P           | [ef94f890dd](https://linux-hardware.org/?probe=ef94f890dd) | May 16, 2020 |
| Acer          | V5-131                      | [9d9e227434](https://linux-hardware.org/?probe=9d9e227434) | May 16, 2020 |
| Acer          | AO722                       | [822175ace8](https://linux-hardware.org/?probe=822175ace8) | May 16, 2020 |
| Samsung       | R425D/R525D                 | [8e54082560](https://linux-hardware.org/?probe=8e54082560) | May 16, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [abf8542459](https://linux-hardware.org/?probe=abf8542459) | May 16, 2020 |
| ASUSTek       | UX331UA                     | [0a0319493d](https://linux-hardware.org/?probe=0a0319493d) | May 15, 2020 |
| Acer          | Aspire 8943G                | [1b520f3904](https://linux-hardware.org/?probe=1b520f3904) | May 15, 2020 |
| MSI           | GL63 8RD                    | [c291440c2f](https://linux-hardware.org/?probe=c291440c2f) | May 14, 2020 |
| MSI           | GL63 8RD                    | [96120d0ebb](https://linux-hardware.org/?probe=96120d0ebb) | May 14, 2020 |
| HP            | Pavilion dv7                | [d7bfa6ea91](https://linux-hardware.org/?probe=d7bfa6ea91) | May 13, 2020 |
| HP            | Notebook                    | [dbed542e5a](https://linux-hardware.org/?probe=dbed542e5a) | May 12, 2020 |
| Dell          | Latitude E6330              | [7f58dd399d](https://linux-hardware.org/?probe=7f58dd399d) | May 12, 2020 |
| Dell          | Latitude E6330              | [1e167b4d43](https://linux-hardware.org/?probe=1e167b4d43) | May 12, 2020 |
| Dell          | Precision M4800             | [028edf486d](https://linux-hardware.org/?probe=028edf486d) | May 11, 2020 |
| Durabook      | S15H                        | [1a1add4428](https://linux-hardware.org/?probe=1a1add4428) | May 11, 2020 |
| Lenovo        | ThinkPad X240 20AMS72T00    | [e24475b169](https://linux-hardware.org/?probe=e24475b169) | May 11, 2020 |
| Medion        | ERAZER X7853 MD60604        | [adfafba25e](https://linux-hardware.org/?probe=adfafba25e) | May 10, 2020 |
| Lenovo        | ThinkPad E585 20KV0010US    | [43f18a12b0](https://linux-hardware.org/?probe=43f18a12b0) | May 09, 2020 |
| HP            | EliteBook Folio 9480m       | [3956d54072](https://linux-hardware.org/?probe=3956d54072) | May 09, 2020 |
| ASUSTek       | X750JA                      | [d03ab2ced2](https://linux-hardware.org/?probe=d03ab2ced2) | May 08, 2020 |
| Acer          | AOD255                      | [c9feab0ae6](https://linux-hardware.org/?probe=c9feab0ae6) | May 07, 2020 |
| Acer          | AOD255                      | [685122de57](https://linux-hardware.org/?probe=685122de57) | May 07, 2020 |
| Acer          | AOD255                      | [8f8f4e61eb](https://linux-hardware.org/?probe=8f8f4e61eb) | May 07, 2020 |
| HP            | Pavilion dv7                | [886f774f58](https://linux-hardware.org/?probe=886f774f58) | May 07, 2020 |
| HP            | 15                          | [e4ffb09704](https://linux-hardware.org/?probe=e4ffb09704) | May 07, 2020 |
| Dell          | Vostro 3550                 | [aeb508b54b](https://linux-hardware.org/?probe=aeb508b54b) | May 07, 2020 |
| Acer          | Acadia V1.17                | [eed274f8c5](https://linux-hardware.org/?probe=eed274f8c5) | May 07, 2020 |
| HP            | Compaq 6735s                | [d5aff5abe3](https://linux-hardware.org/?probe=d5aff5abe3) | May 07, 2020 |
| Fujitsu       | LIFEBOOK S752               | [3150f82299](https://linux-hardware.org/?probe=3150f82299) | May 06, 2020 |
| HP            | Laptop 15-rb0xx             | [0d840277dc](https://linux-hardware.org/?probe=0d840277dc) | May 06, 2020 |
| ASUSTek       | T100TA                      | [84f83e4bff](https://linux-hardware.org/?probe=84f83e4bff) | May 06, 2020 |
| ASUSTek       | X302LA                      | [a994852110](https://linux-hardware.org/?probe=a994852110) | May 06, 2020 |
| HP            | Pavilion dv6                | [f1cc639edf](https://linux-hardware.org/?probe=f1cc639edf) | May 04, 2020 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [5e583d58df](https://linux-hardware.org/?probe=5e583d58df) | May 03, 2020 |
| Positivo      | S14CT01                     | [493497d221](https://linux-hardware.org/?probe=493497d221) | May 03, 2020 |
| Positivo      | S14CT01                     | [518301afe9](https://linux-hardware.org/?probe=518301afe9) | May 03, 2020 |
| Dell          | Inspiron 7548               | [b951e05771](https://linux-hardware.org/?probe=b951e05771) | May 03, 2020 |
| Dell          | Latitude E6400              | [a50bb7e32a](https://linux-hardware.org/?probe=a50bb7e32a) | May 03, 2020 |
| Dell          | Inspiron N4050              | [e64e5a4e36](https://linux-hardware.org/?probe=e64e5a4e36) | May 02, 2020 |
| ASUSTek       | UL20A                       | [de8a903a2b](https://linux-hardware.org/?probe=de8a903a2b) | May 01, 2020 |
| HP            | ProBook 450 G2              | [887a19760b](https://linux-hardware.org/?probe=887a19760b) | May 01, 2020 |
| HP            | Pavilion x2 Detachable      | [4b6ec5f44b](https://linux-hardware.org/?probe=4b6ec5f44b) | May 01, 2020 |
| Dell          | Studio 1737                 | [50af5c4e99](https://linux-hardware.org/?probe=50af5c4e99) | May 01, 2020 |
| HP            | EliteBook Folio 9480m       | [41b9926566](https://linux-hardware.org/?probe=41b9926566) | May 01, 2020 |
| Medion        | E5217                       | [a6b33d3a94](https://linux-hardware.org/?probe=a6b33d3a94) | Apr 30, 2020 |
| Acer          | Nitro AN515-42              | [8b9ad27475](https://linux-hardware.org/?probe=8b9ad27475) | Apr 29, 2020 |
| Dixonsxp      | Unknown                     | [e9bf36b6e0](https://linux-hardware.org/?probe=e9bf36b6e0) | Apr 29, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [bf1e5c9655](https://linux-hardware.org/?probe=bf1e5c9655) | Apr 29, 2020 |
| HP            | Pavilion dv6                | [887b97f4e8](https://linux-hardware.org/?probe=887b97f4e8) | Apr 28, 2020 |
| Dell          | Inspiron 5570               | [1e1ab08268](https://linux-hardware.org/?probe=1e1ab08268) | Apr 28, 2020 |
| IBM           | ThinkPad X40 2371H4G        | [190737f754](https://linux-hardware.org/?probe=190737f754) | Apr 28, 2020 |
| HP            | Compaq Presario CQ60        | [2539260c46](https://linux-hardware.org/?probe=2539260c46) | Apr 28, 2020 |
| ASUSTek       | T100TA                      | [bebdfd359d](https://linux-hardware.org/?probe=bebdfd359d) | Apr 27, 2020 |
| ASUSTek       | T100TA                      | [c1abf7906c](https://linux-hardware.org/?probe=c1abf7906c) | Apr 26, 2020 |
| Toshiba       | Satellite L550              | [73f10216d6](https://linux-hardware.org/?probe=73f10216d6) | Apr 25, 2020 |
| HP            | Laptop 15-da0xxx            | [34c85393d6](https://linux-hardware.org/?probe=34c85393d6) | Apr 24, 2020 |
| HP            | 15                          | [54d9c92866](https://linux-hardware.org/?probe=54d9c92866) | Apr 24, 2020 |
| ASUSTek       | UX331UA                     | [634f000249](https://linux-hardware.org/?probe=634f000249) | Apr 24, 2020 |
| ASUSTek       | UX331UA                     | [94be2c2ea7](https://linux-hardware.org/?probe=94be2c2ea7) | Apr 24, 2020 |
| Dell          | Inspiron 15-3567            | [0e9d3a198e](https://linux-hardware.org/?probe=0e9d3a198e) | Apr 24, 2020 |
| Notebook      | N750BU                      | [e3f870729f](https://linux-hardware.org/?probe=e3f870729f) | Apr 23, 2020 |
| ASUSTek       | T100TA                      | [6cd72a2a26](https://linux-hardware.org/?probe=6cd72a2a26) | Apr 23, 2020 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [f35ddd7bef](https://linux-hardware.org/?probe=f35ddd7bef) | Apr 22, 2020 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [53b078eba2](https://linux-hardware.org/?probe=53b078eba2) | Apr 22, 2020 |
| ASUSTek       | X553MA                      | [dabe283d4d](https://linux-hardware.org/?probe=dabe283d4d) | Apr 21, 2020 |
| HP            | Presario V3700              | [0eac5f43d5](https://linux-hardware.org/?probe=0eac5f43d5) | Apr 21, 2020 |
| Dell          | Inspiron 1720               | [5bbab2bc27](https://linux-hardware.org/?probe=5bbab2bc27) | Apr 21, 2020 |
| ASUSTek       | TP300LA                     | [c3f624dcbd](https://linux-hardware.org/?probe=c3f624dcbd) | Apr 20, 2020 |
| HP            | 255 G2                      | [2e24d05e40](https://linux-hardware.org/?probe=2e24d05e40) | Apr 19, 2020 |
| HP            | Pavilion dv1000 (ET735UA... | [6eea6e679b](https://linux-hardware.org/?probe=6eea6e679b) | Apr 19, 2020 |
| HP            | Pavilion dv9500             | [24a912a8a2](https://linux-hardware.org/?probe=24a912a8a2) | Apr 19, 2020 |
| Sony          | VPCEB3M1E                   | [de0457eba6](https://linux-hardware.org/?probe=de0457eba6) | Apr 19, 2020 |
| Dell          | Inspiron 7537               | [58c5b959e4](https://linux-hardware.org/?probe=58c5b959e4) | Apr 19, 2020 |
| HP            | 2133 (FU338EA)              | [d9b0c55ac8](https://linux-hardware.org/?probe=d9b0c55ac8) | Apr 18, 2020 |
| Sony          | VGN-AW11Z_B                 | [c831660ca5](https://linux-hardware.org/?probe=c831660ca5) | Apr 18, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [45f9fd21d8](https://linux-hardware.org/?probe=45f9fd21d8) | Apr 18, 2020 |
| Gateway       | MX3225                      | [2b23ba49b1](https://linux-hardware.org/?probe=2b23ba49b1) | Apr 18, 2020 |
| Gateway       | MX3225                      | [b3844e839e](https://linux-hardware.org/?probe=b3844e839e) | Apr 18, 2020 |
| Lenovo        | ThinkPad T420 42368H6       | [f65f8c3464](https://linux-hardware.org/?probe=f65f8c3464) | Apr 18, 2020 |
| HP            | 550                         | [078cde1a1b](https://linux-hardware.org/?probe=078cde1a1b) | Apr 18, 2020 |
| Lenovo        | ThinkPad T420 42368H6       | [806064d978](https://linux-hardware.org/?probe=806064d978) | Apr 18, 2020 |
| AXIOO         | NEON CNW                    | [64edfa7923](https://linux-hardware.org/?probe=64edfa7923) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [d27bf3c005](https://linux-hardware.org/?probe=d27bf3c005) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [5d25f725c9](https://linux-hardware.org/?probe=5d25f725c9) | Apr 18, 2020 |
| Sony          | VPCYB35AL                   | [a96bfb28b5](https://linux-hardware.org/?probe=a96bfb28b5) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [eae7b8a990](https://linux-hardware.org/?probe=eae7b8a990) | Apr 17, 2020 |
| ASUSTek       | N46VB                       | [ab1938abc6](https://linux-hardware.org/?probe=ab1938abc6) | Apr 17, 2020 |
| Clevo         | M7x0S                       | [2dc8a215f6](https://linux-hardware.org/?probe=2dc8a215f6) | Apr 17, 2020 |
| Clevo         | M7x0S                       | [562739a94b](https://linux-hardware.org/?probe=562739a94b) | Apr 17, 2020 |
| Acer          | E1-510                      | [933b2f30b0](https://linux-hardware.org/?probe=933b2f30b0) | Apr 17, 2020 |
| HP            | ProBook 450 G2              | [1ef49ff7a3](https://linux-hardware.org/?probe=1ef49ff7a3) | Apr 17, 2020 |
| HP            | EliteBook 8460p             | [41c3cb6523](https://linux-hardware.org/?probe=41c3cb6523) | Apr 17, 2020 |
| HP            | EliteBook 8460p             | [e5283d7a27](https://linux-hardware.org/?probe=e5283d7a27) | Apr 17, 2020 |
| Sony          | VGN-AW11Z_B                 | [57a0d65d23](https://linux-hardware.org/?probe=57a0d65d23) | Apr 16, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | [a63c3876d5](https://linux-hardware.org/?probe=a63c3876d5) | Apr 16, 2020 |
| ASUSTek       | T100TA                      | [487d046945](https://linux-hardware.org/?probe=487d046945) | Apr 16, 2020 |
| Dell          | Latitude E6440              | [d2eaa5d809](https://linux-hardware.org/?probe=d2eaa5d809) | Apr 16, 2020 |
| ASUSTek       | S400CA                      | [ddc5a34acb](https://linux-hardware.org/?probe=ddc5a34acb) | Apr 16, 2020 |
| ASUSTek       | S400CA                      | [959d3bcbb2](https://linux-hardware.org/?probe=959d3bcbb2) | Apr 16, 2020 |
| Acer          | Prespa1                     | [791259386e](https://linux-hardware.org/?probe=791259386e) | Apr 16, 2020 |
| HP            | Pavilion 17                 | [d54ff69694](https://linux-hardware.org/?probe=d54ff69694) | Apr 16, 2020 |
| HP            | Gaming PC                   | [472ccadaa3](https://linux-hardware.org/?probe=472ccadaa3) | Apr 16, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [e2a5957771](https://linux-hardware.org/?probe=e2a5957771) | Apr 15, 2020 |
| Lenovo        | ThinkPad Edge E440 20C50... | [bc9d3d1f9c](https://linux-hardware.org/?probe=bc9d3d1f9c) | Apr 15, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [7c86e73d6e](https://linux-hardware.org/?probe=7c86e73d6e) | Apr 15, 2020 |
| Dell          | Latitude E5550              | [37d3c8c386](https://linux-hardware.org/?probe=37d3c8c386) | Apr 15, 2020 |
| HP            | 2133 (FU338EA)              | [029ce5169b](https://linux-hardware.org/?probe=029ce5169b) | Apr 15, 2020 |
| Acer          | Aspire 5610Z                | [65a4d9621d](https://linux-hardware.org/?probe=65a4d9621d) | Apr 14, 2020 |
| Dell          | Latitude E6510              | [ca17782e8f](https://linux-hardware.org/?probe=ca17782e8f) | Apr 14, 2020 |
| Dell          | Latitude E6510              | [a276d0e4e8](https://linux-hardware.org/?probe=a276d0e4e8) | Apr 14, 2020 |
| Apple         | MacBookPro10,1              | [37327526d9](https://linux-hardware.org/?probe=37327526d9) | Apr 13, 2020 |
| Nuvision      | L1W6_I1101_G Hampoo Rese... | [0277194797](https://linux-hardware.org/?probe=0277194797) | Apr 13, 2020 |
| Dell          | Latitude E6410              | [54dd58d213](https://linux-hardware.org/?probe=54dd58d213) | Apr 13, 2020 |
| eMachines     | G630                        | [2f15422dcd](https://linux-hardware.org/?probe=2f15422dcd) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | [4d48cc531a](https://linux-hardware.org/?probe=4d48cc531a) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | [07a7a6e630](https://linux-hardware.org/?probe=07a7a6e630) | Apr 13, 2020 |
| MSI           | MS-1688                     | [e6a4077b27](https://linux-hardware.org/?probe=e6a4077b27) | Apr 13, 2020 |
| MSI           | MS-1688                     | [d0d5f98071](https://linux-hardware.org/?probe=d0d5f98071) | Apr 12, 2020 |
| Clevo         | D900C Revision D            | [1fb3feea04](https://linux-hardware.org/?probe=1fb3feea04) | Apr 12, 2020 |
| ASUSTek       | X200CA                      | [3c52d09634](https://linux-hardware.org/?probe=3c52d09634) | Apr 12, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [20eeb3f580](https://linux-hardware.org/?probe=20eeb3f580) | Apr 12, 2020 |
| Ematic        | EW147                       | [4dd070feda](https://linux-hardware.org/?probe=4dd070feda) | Apr 12, 2020 |
| Ematic        | EW147                       | [1176adc6a1](https://linux-hardware.org/?probe=1176adc6a1) | Apr 12, 2020 |
| Lenovo        | V130-15IGM 81HL             | [11251407bd](https://linux-hardware.org/?probe=11251407bd) | Apr 11, 2020 |
| Acer          | One S1002                   | [83314e9687](https://linux-hardware.org/?probe=83314e9687) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | [37f223475f](https://linux-hardware.org/?probe=37f223475f) | Apr 11, 2020 |
| HP            | Pavilion 15                 | [2f38c60e21](https://linux-hardware.org/?probe=2f38c60e21) | Apr 11, 2020 |
| HP            | Pavilion 15                 | [5b41ba3e4e](https://linux-hardware.org/?probe=5b41ba3e4e) | Apr 11, 2020 |
| Acer          | Extensa 5620                | [9501d84629](https://linux-hardware.org/?probe=9501d84629) | Apr 11, 2020 |
| Lenovo        | ThinkPad 11e 20DAS0YW00     | [15057e288d](https://linux-hardware.org/?probe=15057e288d) | Apr 11, 2020 |
| Apple         | MacBookAir4,2               | [5f84027e54](https://linux-hardware.org/?probe=5f84027e54) | Apr 11, 2020 |
| Acer          | Aspire 5741G                | [2a4c7dd1d5](https://linux-hardware.org/?probe=2a4c7dd1d5) | Apr 10, 2020 |
| Lenovo        | V130-15IGM 81HL             | [21a5c2580f](https://linux-hardware.org/?probe=21a5c2580f) | Apr 10, 2020 |
| Lenovo        | ThinkPad 11e 20DAS0YW00     | [90ca183e3d](https://linux-hardware.org/?probe=90ca183e3d) | Apr 10, 2020 |
| AXIOO         | NEON CNW                    | [b31fc0c0dd](https://linux-hardware.org/?probe=b31fc0c0dd) | Apr 10, 2020 |
| Fujitsu Si... | AMILO PRO V2030             | [67b8c113f9](https://linux-hardware.org/?probe=67b8c113f9) | Apr 10, 2020 |
| Fujitsu Si... | AMILO PRO V2030             | [432926e63e](https://linux-hardware.org/?probe=432926e63e) | Apr 10, 2020 |
| Lenovo        | G580 20157                  | [30a8d59bdc](https://linux-hardware.org/?probe=30a8d59bdc) | Apr 09, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [ba943d4bc5](https://linux-hardware.org/?probe=ba943d4bc5) | Apr 09, 2020 |
| Lenovo        | G580 20157                  | [fc6eaad779](https://linux-hardware.org/?probe=fc6eaad779) | Apr 09, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [0248492e22](https://linux-hardware.org/?probe=0248492e22) | Apr 08, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b19f7181b4](https://linux-hardware.org/?probe=b19f7181b4) | Apr 08, 2020 |
| Gateway       | ML6228                      | [3fd17b9f82](https://linux-hardware.org/?probe=3fd17b9f82) | Apr 08, 2020 |
| Packard Be... | EasyNote TJ65               | [3008be40c7](https://linux-hardware.org/?probe=3008be40c7) | Apr 06, 2020 |
| Lenovo        | ThinkPad T440s 20AQ009HU... | [695389401a](https://linux-hardware.org/?probe=695389401a) | Apr 06, 2020 |
| Toshiba       | Satellite A200              | [b66adc41e3](https://linux-hardware.org/?probe=b66adc41e3) | Apr 05, 2020 |
| Toshiba       | Satellite A200              | [9b9a8bf80f](https://linux-hardware.org/?probe=9b9a8bf80f) | Apr 05, 2020 |
| Toshiba       | Satellite A200              | [59ab95abbb](https://linux-hardware.org/?probe=59ab95abbb) | Apr 05, 2020 |
| Acer          | Aspire 5741G                | [8ea2a664b6](https://linux-hardware.org/?probe=8ea2a664b6) | Apr 05, 2020 |
| Dell          | Latitude E6400              | [5a96047b26](https://linux-hardware.org/?probe=5a96047b26) | Apr 05, 2020 |
| Dell          | Latitude D520               | [69f550a570](https://linux-hardware.org/?probe=69f550a570) | Apr 05, 2020 |
| Toshiba       | Satellite C850D-B810        | [bfa7a5b4b3](https://linux-hardware.org/?probe=bfa7a5b4b3) | Apr 04, 2020 |
| Toshiba       | Satellite C850D-B810        | [d911f2bb34](https://linux-hardware.org/?probe=d911f2bb34) | Apr 04, 2020 |
| Toshiba       | Satellite L450              | [b18b01a081](https://linux-hardware.org/?probe=b18b01a081) | Apr 04, 2020 |
| Acer          | Aspire 5742G                | [c83a4dfe3c](https://linux-hardware.org/?probe=c83a4dfe3c) | Apr 04, 2020 |
| HP            | Mini 5103                   | [c60a2a2852](https://linux-hardware.org/?probe=c60a2a2852) | Apr 04, 2020 |
| Dell          | Inspiron 3179               | [4f8f1dd9c8](https://linux-hardware.org/?probe=4f8f1dd9c8) | Apr 04, 2020 |
| HP            | G62                         | [65f362927c](https://linux-hardware.org/?probe=65f362927c) | Apr 04, 2020 |
| Dell          | Latitude X1                 | [47f2bd6300](https://linux-hardware.org/?probe=47f2bd6300) | Apr 03, 2020 |
| Dell          | Latitude X1                 | [d753de9b00](https://linux-hardware.org/?probe=d753de9b00) | Apr 03, 2020 |
| Acer          | Aspire A315-41              | [ec505d4ab7](https://linux-hardware.org/?probe=ec505d4ab7) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | [a602b4a98e](https://linux-hardware.org/?probe=a602b4a98e) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | [bc0996781f](https://linux-hardware.org/?probe=bc0996781f) | Apr 02, 2020 |
| Dell          | Latitude E6410              | [147488a290](https://linux-hardware.org/?probe=147488a290) | Apr 02, 2020 |
| Acer          | Nitro AN515-51              | [d6b01aa670](https://linux-hardware.org/?probe=d6b01aa670) | Apr 01, 2020 |
| Dell          | Latitude E6410              | [766122819f](https://linux-hardware.org/?probe=766122819f) | Apr 01, 2020 |
| Acer          | Extensa 5620                | [2cc79b3cc5](https://linux-hardware.org/?probe=2cc79b3cc5) | Mar 31, 2020 |
| Lenovo        | ThinkPad R400 7440WWQ       | [ac4c4ee6d7](https://linux-hardware.org/?probe=ac4c4ee6d7) | Mar 31, 2020 |
| HP            | ProBook 4525s               | [cb0a6c08db](https://linux-hardware.org/?probe=cb0a6c08db) | Mar 31, 2020 |
| Lenovo        | IdeaPad Y570 20091          | [2a38b92cb1](https://linux-hardware.org/?probe=2a38b92cb1) | Mar 31, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [2a761bfaee](https://linux-hardware.org/?probe=2a761bfaee) | Mar 30, 2020 |
| Acer          | Aspire A315-41              | [59c568e03a](https://linux-hardware.org/?probe=59c568e03a) | Mar 30, 2020 |
| Sony          | VPCM13M1E                   | [eb20399d8b](https://linux-hardware.org/?probe=eb20399d8b) | Mar 30, 2020 |
| Acer          | Aspire A315-41              | [592d008d70](https://linux-hardware.org/?probe=592d008d70) | Mar 30, 2020 |
| ASUSTek       | X553MA                      | [47e6377b3b](https://linux-hardware.org/?probe=47e6377b3b) | Mar 30, 2020 |
| ASUSTek       | X553MA                      | [63e00b46e2](https://linux-hardware.org/?probe=63e00b46e2) | Mar 30, 2020 |
| ASUSTek       | 1101HAGG                    | [1ecc8fa4d3](https://linux-hardware.org/?probe=1ecc8fa4d3) | Mar 29, 2020 |
| HP            | Notebook                    | [6d16eabcdb](https://linux-hardware.org/?probe=6d16eabcdb) | Mar 29, 2020 |
| ASUSTek       | 1101HAGG                    | [8d2c258ed7](https://linux-hardware.org/?probe=8d2c258ed7) | Mar 29, 2020 |
| HP            | OMEN by Laptop              | [eec0858042](https://linux-hardware.org/?probe=eec0858042) | Mar 29, 2020 |
| Dell          | Inspiron 1520               | [146388e7f0](https://linux-hardware.org/?probe=146388e7f0) | Mar 29, 2020 |
| HP            | ProBook 4525s               | [dc9164d939](https://linux-hardware.org/?probe=dc9164d939) | Mar 28, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bcbfe2da9a](https://linux-hardware.org/?probe=bcbfe2da9a) | Mar 28, 2020 |
| Samsung       | 305V4A/305V5A/3415VA        | [118b531086](https://linux-hardware.org/?probe=118b531086) | Mar 28, 2020 |
| Samsung       | 305V4A/305V5A/3415VA        | [4d70e47759](https://linux-hardware.org/?probe=4d70e47759) | Mar 28, 2020 |
| Samsung       | 800G5M/800G5W               | [f8a5c21d24](https://linux-hardware.org/?probe=f8a5c21d24) | Mar 28, 2020 |
| HP            | Pavilion g6                 | [cfe67dc8eb](https://linux-hardware.org/?probe=cfe67dc8eb) | Mar 27, 2020 |
| HP            | Pavilion g6                 | [058cce86bb](https://linux-hardware.org/?probe=058cce86bb) | Mar 27, 2020 |
| ASUSTek       | N750JK                      | [172ea4a7d1](https://linux-hardware.org/?probe=172ea4a7d1) | Mar 27, 2020 |
| Dell          | Inspiron 1520               | [0bd42bbb3a](https://linux-hardware.org/?probe=0bd42bbb3a) | Mar 27, 2020 |
| Dell          | Inspiron 5570               | [922814f637](https://linux-hardware.org/?probe=922814f637) | Mar 27, 2020 |
| Dell          | Inspiron 5570               | [b8ac8ae9e4](https://linux-hardware.org/?probe=b8ac8ae9e4) | Mar 27, 2020 |
| HP            | Pavilion 10 TS              | [87484a7033](https://linux-hardware.org/?probe=87484a7033) | Mar 27, 2020 |
| Panasonic     | CF-31ACJAXPM                | [44a7635515](https://linux-hardware.org/?probe=44a7635515) | Mar 27, 2020 |
| eMachines     | eME728                      | [26425bd7a4](https://linux-hardware.org/?probe=26425bd7a4) | Mar 26, 2020 |
| Acer          | Aspire A315-31              | [1755330821](https://linux-hardware.org/?probe=1755330821) | Mar 26, 2020 |
| HP            | Pavilion dv9700             | [7567e3c677](https://linux-hardware.org/?probe=7567e3c677) | Mar 26, 2020 |
| Dell          | Latitude E5440              | [d5e19d53dc](https://linux-hardware.org/?probe=d5e19d53dc) | Mar 25, 2020 |
| MSI           | GE62 6QF                    | [f951247a44](https://linux-hardware.org/?probe=f951247a44) | Mar 25, 2020 |
| HP            | ProBook 6550b               | [9cd41d9853](https://linux-hardware.org/?probe=9cd41d9853) | Mar 25, 2020 |
| Dell          | XPS 15 9560                 | [0f39d105a8](https://linux-hardware.org/?probe=0f39d105a8) | Mar 25, 2020 |
| Dell          | XPS 15 9560                 | [9453dadbd6](https://linux-hardware.org/?probe=9453dadbd6) | Mar 25, 2020 |
| HP            | Pavilion dv5                | [009a4aed18](https://linux-hardware.org/?probe=009a4aed18) | Mar 25, 2020 |
| HP            | Presario C500 (RY510EA#A... | [e69a3bef68](https://linux-hardware.org/?probe=e69a3bef68) | Mar 24, 2020 |
| Toshiba       | Satellite C660              | [38c32074a0](https://linux-hardware.org/?probe=38c32074a0) | Mar 24, 2020 |
| HP            | ZBook 14u G4                | [2843fde2a7](https://linux-hardware.org/?probe=2843fde2a7) | Mar 23, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [e274c73209](https://linux-hardware.org/?probe=e274c73209) | Mar 23, 2020 |
| Toshiba       | Satellite L455D             | [1d8583d691](https://linux-hardware.org/?probe=1d8583d691) | Mar 23, 2020 |
| HP            | Pavilion 15                 | [b37a8bd4ff](https://linux-hardware.org/?probe=b37a8bd4ff) | Mar 22, 2020 |
| HP            | Pavilion x2 Detachable      | [27c5f0f340](https://linux-hardware.org/?probe=27c5f0f340) | Mar 22, 2020 |
| Lenovo        | ThinkPad T510 4349AW2       | [e8351b04a1](https://linux-hardware.org/?probe=e8351b04a1) | Mar 22, 2020 |
| HP            | ProBook 6550b               | [08a8d59e31](https://linux-hardware.org/?probe=08a8d59e31) | Mar 22, 2020 |
| Lenovo        | G510 20238                  | [9130b68bf4](https://linux-hardware.org/?probe=9130b68bf4) | Mar 22, 2020 |
| Sony          | SVF15A17CLB                 | [6f9e42f276](https://linux-hardware.org/?probe=6f9e42f276) | Mar 22, 2020 |
| Lenovo        | ThinkPad T510 4349AW2       | [428a0150aa](https://linux-hardware.org/?probe=428a0150aa) | Mar 21, 2020 |
| Samsung       | R519/R719                   | [df651d6929](https://linux-hardware.org/?probe=df651d6929) | Mar 21, 2020 |
| HP            | Pavilion Notebook 15-bc5... | [712dd83a31](https://linux-hardware.org/?probe=712dd83a31) | Mar 21, 2020 |
| HP            | G62                         | [6f4776017d](https://linux-hardware.org/?probe=6f4776017d) | Mar 21, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [a2d8924557](https://linux-hardware.org/?probe=a2d8924557) | Mar 21, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [4511e5932e](https://linux-hardware.org/?probe=4511e5932e) | Mar 21, 2020 |
| ASUSTek       | F3Sg                        | [149527329c](https://linux-hardware.org/?probe=149527329c) | Mar 20, 2020 |
| Unknown       | Unknown                     | [268c0d4b3e](https://linux-hardware.org/?probe=268c0d4b3e) | Mar 20, 2020 |
| HP            | Pavilion 11 x360 PC         | [fd49842929](https://linux-hardware.org/?probe=fd49842929) | Mar 20, 2020 |
| HP            | Pavilion Notebook 15-bc5... | [b67aef950d](https://linux-hardware.org/?probe=b67aef950d) | Mar 19, 2020 |
| HP            | Pavilion Notebook 15-bc5... | [c2b75c6e1a](https://linux-hardware.org/?probe=c2b75c6e1a) | Mar 19, 2020 |
| HP            | Compaq 8510p                | [df003f9b94](https://linux-hardware.org/?probe=df003f9b94) | Mar 19, 2020 |
| HP            | Compaq 8510p                | [6a272fe91c](https://linux-hardware.org/?probe=6a272fe91c) | Mar 19, 2020 |
| HP            | Unknown                     | [0720ac35fc](https://linux-hardware.org/?probe=0720ac35fc) | Mar 19, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | [a351ec49d6](https://linux-hardware.org/?probe=a351ec49d6) | Mar 19, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | [824e8de596](https://linux-hardware.org/?probe=824e8de596) | Mar 19, 2020 |
| Dell          | Inspiron 1520               | [e603a6de90](https://linux-hardware.org/?probe=e603a6de90) | Mar 19, 2020 |
| HP            | G42                         | [81475e20fc](https://linux-hardware.org/?probe=81475e20fc) | Mar 19, 2020 |
| Lenovo        | ThinkPad L412 058542G       | [1bc705430b](https://linux-hardware.org/?probe=1bc705430b) | Mar 18, 2020 |
| HP            | Unknown                     | [7ebfd4d205](https://linux-hardware.org/?probe=7ebfd4d205) | Mar 18, 2020 |
| HP            | Pavilion tx1000             | [5f8a15817c](https://linux-hardware.org/?probe=5f8a15817c) | Mar 18, 2020 |
| HP            | Pavilion tx1000             | [76f5c62167](https://linux-hardware.org/?probe=76f5c62167) | Mar 18, 2020 |
| Toshiba       | Satellite L305              | [e3b6115f5e](https://linux-hardware.org/?probe=e3b6115f5e) | Mar 17, 2020 |
| Toshiba       | Satellite L305              | [7d2f3a78fe](https://linux-hardware.org/?probe=7d2f3a78fe) | Mar 17, 2020 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b19ba42878](https://linux-hardware.org/?probe=b19ba42878) | Mar 17, 2020 |
| HP            | ProBook 640 G4              | [9240c255ae](https://linux-hardware.org/?probe=9240c255ae) | Mar 16, 2020 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [86e1d115b9](https://linux-hardware.org/?probe=86e1d115b9) | Mar 15, 2020 |
| Dell          | Inspiron 6000               | [e81704d568](https://linux-hardware.org/?probe=e81704d568) | Mar 15, 2020 |
| HP            | Pavilion dv9700             | [60bcd3ac92](https://linux-hardware.org/?probe=60bcd3ac92) | Mar 15, 2020 |
| Lenovo        | Y70-70 Touch 80DU           | [6ab7a0c0f5](https://linux-hardware.org/?probe=6ab7a0c0f5) | Mar 15, 2020 |
| ASUSTek       | N750JK                      | [7b51fed304](https://linux-hardware.org/?probe=7b51fed304) | Mar 13, 2020 |
| Dell          | Inspiron 7560               | [bdfbbe481f](https://linux-hardware.org/?probe=bdfbbe481f) | Mar 13, 2020 |
| Acer          | Aspire E1-572G              | [cc8b5532c5](https://linux-hardware.org/?probe=cc8b5532c5) | Mar 12, 2020 |
| HP            | Pavilion dv7                | [61bbb3da8a](https://linux-hardware.org/?probe=61bbb3da8a) | Mar 12, 2020 |
| Acer          | Ferrari IV                  | [a1626355ea](https://linux-hardware.org/?probe=a1626355ea) | Mar 11, 2020 |
| Acer          | Ferrari IV                  | [fa404be8fd](https://linux-hardware.org/?probe=fa404be8fd) | Mar 11, 2020 |
| Dell          | Latitude E5440              | [7582be2134](https://linux-hardware.org/?probe=7582be2134) | Mar 11, 2020 |
| HP            | ProBook 4320s               | [92478c20d5](https://linux-hardware.org/?probe=92478c20d5) | Mar 11, 2020 |
| ASUSTek       | TAICHI21                    | [608a903011](https://linux-hardware.org/?probe=608a903011) | Mar 11, 2020 |
| Apple         | MacBookPro9,2               | [81823b3c54](https://linux-hardware.org/?probe=81823b3c54) | Mar 11, 2020 |
| Dell          | Latitude XT2                | [bf5cd05553](https://linux-hardware.org/?probe=bf5cd05553) | Mar 10, 2020 |
| Samsung       | N102                        | [40dba99330](https://linux-hardware.org/?probe=40dba99330) | Mar 10, 2020 |
| Apple         | MacBookPro9,2               | [ccde97eb8a](https://linux-hardware.org/?probe=ccde97eb8a) | Mar 10, 2020 |
| Apple         | MacBookPro9,2               | [289d3eb3d3](https://linux-hardware.org/?probe=289d3eb3d3) | Mar 10, 2020 |
| HP            | Compaq 615                  | [20f4720634](https://linux-hardware.org/?probe=20f4720634) | Mar 08, 2020 |
| Dell          | Latitude E5440              | [a03a2405a2](https://linux-hardware.org/?probe=a03a2405a2) | Mar 08, 2020 |
| Lenovo        | ThinkPad T430s 23563RB      | [a011b81975](https://linux-hardware.org/?probe=a011b81975) | Mar 07, 2020 |
| Lenovo        | ThinkPad T430s 23563RB      | [8ce2fe5d52](https://linux-hardware.org/?probe=8ce2fe5d52) | Mar 07, 2020 |
| HP            | EliteBook 840 G2            | [b23a6cc526](https://linux-hardware.org/?probe=b23a6cc526) | Mar 06, 2020 |
| Dixonsxp      | Unknown                     | [d51d943904](https://linux-hardware.org/?probe=d51d943904) | Mar 06, 2020 |
| HP            | Pavilion 11 x360 PC         | [e5d46d214b](https://linux-hardware.org/?probe=e5d46d214b) | Mar 05, 2020 |
| HP            | ProBook 4320s               | [96b40c5d0e](https://linux-hardware.org/?probe=96b40c5d0e) | Mar 05, 2020 |
| Lenovo        | Flex 2-15 20405             | [b673427507](https://linux-hardware.org/?probe=b673427507) | Mar 03, 2020 |
| Google        | Gnawty                      | [6f3ac8ce74](https://linux-hardware.org/?probe=6f3ac8ce74) | Mar 01, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [5b1e502fce](https://linux-hardware.org/?probe=5b1e502fce) | Mar 01, 2020 |
| Fujitsu Si... | AMILO M1451G Series         | [ae442cc174](https://linux-hardware.org/?probe=ae442cc174) | Feb 26, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [9344a74aa9](https://linux-hardware.org/?probe=9344a74aa9) | Feb 26, 2020 |
| ASUSTek       | X555LD                      | [c3ba184dbb](https://linux-hardware.org/?probe=c3ba184dbb) | Feb 25, 2020 |
| HP            | EliteBook 840 G1            | [cd0a628cc6](https://linux-hardware.org/?probe=cd0a628cc6) | Feb 23, 2020 |
| HP            | Pavilion dm1                | [e4a08b8741](https://linux-hardware.org/?probe=e4a08b8741) | Feb 23, 2020 |
| Google        | Enguarde                    | [1b6835ab9d](https://linux-hardware.org/?probe=1b6835ab9d) | Feb 21, 2020 |
| ASUSTek       | GX501VIK                    | [717e762d70](https://linux-hardware.org/?probe=717e762d70) | Feb 20, 2020 |
| Apple         | MacBook4,1                  | [4eb748a8df](https://linux-hardware.org/?probe=4eb748a8df) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b253180703](https://linux-hardware.org/?probe=b253180703) | Feb 20, 2020 |
| ASUSTek       | GX501VIK                    | [a8d5bc13f9](https://linux-hardware.org/?probe=a8d5bc13f9) | Feb 19, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ad43873fae](https://linux-hardware.org/?probe=ad43873fae) | Feb 19, 2020 |
| HP            | ProBook 4530s               | [639dbf3714](https://linux-hardware.org/?probe=639dbf3714) | Feb 16, 2020 |
| Bak USA Te... | Atlas                       | [faa71e71eb](https://linux-hardware.org/?probe=faa71e71eb) | Feb 16, 2020 |
| ASUSTek       | A6Km                        | [674156522d](https://linux-hardware.org/?probe=674156522d) | Feb 16, 2020 |
| Bak USA Te... | Atlas                       | [4e1dd1b730](https://linux-hardware.org/?probe=4e1dd1b730) | Feb 14, 2020 |
| NEC Comput... | PC-VY25AACZ9                | [87e4d3dd9a](https://linux-hardware.org/?probe=87e4d3dd9a) | Feb 14, 2020 |
| Toshiba       | PORTEGE Z30-A               | [897030a5ea](https://linux-hardware.org/?probe=897030a5ea) | Feb 13, 2020 |
| Dell          | Vostro 3550                 | [edfe8875af](https://linux-hardware.org/?probe=edfe8875af) | Feb 12, 2020 |
| IBM           | ThinkPad T43 26688AG        | [ce6973ce12](https://linux-hardware.org/?probe=ce6973ce12) | Feb 12, 2020 |
| Toshiba       | Satellite L55-C             | [acebd8101e](https://linux-hardware.org/?probe=acebd8101e) | Feb 11, 2020 |
| Dell          | System Vostro 3750          | [73e23c8357](https://linux-hardware.org/?probe=73e23c8357) | Feb 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [91ba437052](https://linux-hardware.org/?probe=91ba437052) | Feb 11, 2020 |
| Toshiba       | PORTEGE Z30-A               | [8b26c24d93](https://linux-hardware.org/?probe=8b26c24d93) | Feb 11, 2020 |
| ASUSTek       | E203NA                      | [09dbcdcddc](https://linux-hardware.org/?probe=09dbcdcddc) | Feb 10, 2020 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [d9fdcbf4d8](https://linux-hardware.org/?probe=d9fdcbf4d8) | Feb 10, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [10d5285055](https://linux-hardware.org/?probe=10d5285055) | Feb 07, 2020 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [d80811a73d](https://linux-hardware.org/?probe=d80811a73d) | Feb 05, 2020 |
| Lenovo        | G505 20240                  | [3208a023bf](https://linux-hardware.org/?probe=3208a023bf) | Feb 04, 2020 |
| Lenovo        | ThinkPad E550 20DF0040US    | [ce3ebef6dc](https://linux-hardware.org/?probe=ce3ebef6dc) | Feb 04, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | [e9238fd8ed](https://linux-hardware.org/?probe=e9238fd8ed) | Feb 03, 2020 |
| TrekStor      | Notebook Slim S130          | [e0e1b59385](https://linux-hardware.org/?probe=e0e1b59385) | Feb 01, 2020 |
| Acer          | Nitro AN515-42              | [a1d38e2afe](https://linux-hardware.org/?probe=a1d38e2afe) | Feb 01, 2020 |
| Acer          | Aspire 5735                 | [e517ff7dc7](https://linux-hardware.org/?probe=e517ff7dc7) | Jan 31, 2020 |
| HP            | Pavilion dv7                | [1359dd6ebc](https://linux-hardware.org/?probe=1359dd6ebc) | Jan 31, 2020 |
| Acer          | Aspire 5336                 | [7827c16291](https://linux-hardware.org/?probe=7827c16291) | Jan 30, 2020 |
| HP            | Pavilion dv6700             | [11b6b91acc](https://linux-hardware.org/?probe=11b6b91acc) | Jan 29, 2020 |
| HP            | Compaq Presario CQ50        | [1e88106854](https://linux-hardware.org/?probe=1e88106854) | Jan 28, 2020 |
| HP            | ProBook 450 G1              | [7393534af1](https://linux-hardware.org/?probe=7393534af1) | Jan 26, 2020 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | [7282fec433](https://linux-hardware.org/?probe=7282fec433) | Jan 26, 2020 |
| Toshiba       | Satellite L55-B             | [cbf62518f7](https://linux-hardware.org/?probe=cbf62518f7) | Jan 25, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [d84c64a7b4](https://linux-hardware.org/?probe=d84c64a7b4) | Jan 23, 2020 |
| Acer          | AOA150                      | [0b619b41c1](https://linux-hardware.org/?probe=0b619b41c1) | Jan 23, 2020 |
| Lenovo        | IdeaPad N581 7505           | [2d053580c5](https://linux-hardware.org/?probe=2d053580c5) | Jan 22, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c20e4254c8](https://linux-hardware.org/?probe=c20e4254c8) | Jan 18, 2020 |
| HP            | Split 13 x2 Detachable P... | [508422072e](https://linux-hardware.org/?probe=508422072e) | Jan 17, 2020 |
| HP            | Split 13 x2 Detachable P... | [8ef1114860](https://linux-hardware.org/?probe=8ef1114860) | Jan 17, 2020 |
| Lenovo        | V155-15API 81V5             | [62d9f6fd7f](https://linux-hardware.org/?probe=62d9f6fd7f) | Jan 16, 2020 |
| AMI           | Unknown                     | [4d89af9f9b](https://linux-hardware.org/?probe=4d89af9f9b) | Jan 16, 2020 |
| Acer          | AOA150                      | [94fa7756d5](https://linux-hardware.org/?probe=94fa7756d5) | Jan 15, 2020 |
| Toshiba       | Satellite L55-B             | [67b00cee9e](https://linux-hardware.org/?probe=67b00cee9e) | Jan 15, 2020 |
| Acer          | Aspire 5750                 | [b4b48d57a5](https://linux-hardware.org/?probe=b4b48d57a5) | Jan 15, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [db6935033e](https://linux-hardware.org/?probe=db6935033e) | Jan 11, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [c0265e0fd2](https://linux-hardware.org/?probe=c0265e0fd2) | Jan 11, 2020 |
| Samsung       | R710                        | [f9cd84fa75](https://linux-hardware.org/?probe=f9cd84fa75) | Jan 10, 2020 |
| Packard Be... | EasyNote MH36               | [ce56ea59c0](https://linux-hardware.org/?probe=ce56ea59c0) | Jan 06, 2020 |
| Packard Be... | EasyNote MH35               | [219fd394d3](https://linux-hardware.org/?probe=219fd394d3) | Jan 06, 2020 |
| Packard Be... | EasyNote MH35               | [c686755748](https://linux-hardware.org/?probe=c686755748) | Jan 06, 2020 |
| Acer          | Aspire 4752                 | [4e0f6ed499](https://linux-hardware.org/?probe=4e0f6ed499) | Jan 05, 2020 |
| Acer          | Aspire 4752                 | [ef80f122b5](https://linux-hardware.org/?probe=ef80f122b5) | Jan 05, 2020 |
| Toshiba       | Satellite A215              | [47dcd6e7bf](https://linux-hardware.org/?probe=47dcd6e7bf) | Jan 02, 2020 |
| Toshiba       | Satellite A215              | [746c66b8c6](https://linux-hardware.org/?probe=746c66b8c6) | Jan 02, 2020 |
| HP            | Laptop 15-bw0xx             | [defb99f1cc](https://linux-hardware.org/?probe=defb99f1cc) | Jan 01, 2020 |
| Packard Be... | EasyNote TJ65               | [11c8b385a6](https://linux-hardware.org/?probe=11c8b385a6) | Jan 01, 2020 |
| Dell          | Latitude E6420              | [22ac950018](https://linux-hardware.org/?probe=22ac950018) | Dec 31, 2019 |
| Dell          | Latitude E6420              | [c0dcaf12d6](https://linux-hardware.org/?probe=c0dcaf12d6) | Dec 31, 2019 |
| Lenovo        | V155-15API 81V5             | [c379f2d81b](https://linux-hardware.org/?probe=c379f2d81b) | Dec 31, 2019 |
| Dell          | Latitude E6420              | [57a24730d1](https://linux-hardware.org/?probe=57a24730d1) | Dec 31, 2019 |
| Samsung       | 340XAA/350XAA/550XAA        | [561a2b1118](https://linux-hardware.org/?probe=561a2b1118) | Dec 31, 2019 |
| Packard Be... | EasyNote MH36               | [2acbacb783](https://linux-hardware.org/?probe=2acbacb783) | Dec 30, 2019 |
| Dell          | Latitude D630               | [aa6eee7a18](https://linux-hardware.org/?probe=aa6eee7a18) | Dec 30, 2019 |
| MSI           | GT70                        | [c86693c4ea](https://linux-hardware.org/?probe=c86693c4ea) | Dec 29, 2019 |
| NEC Comput... | PC-LC900HJ                  | [76bec35362](https://linux-hardware.org/?probe=76bec35362) | Dec 29, 2019 |
| HP            | Presario F500 (GL935UA#A... | [974afae9cf](https://linux-hardware.org/?probe=974afae9cf) | Dec 27, 2019 |
| Toshiba       | Satellite L775D             | [936a9682fa](https://linux-hardware.org/?probe=936a9682fa) | Dec 27, 2019 |
| Dell          | Inspiron 5566               | [f0139b5341](https://linux-hardware.org/?probe=f0139b5341) | Dec 26, 2019 |
| Dell          | Latitude E6530              | [813731ab25](https://linux-hardware.org/?probe=813731ab25) | Dec 26, 2019 |
| Lenovo        | V155-15API 81V5             | [8a74f889ca](https://linux-hardware.org/?probe=8a74f889ca) | Dec 26, 2019 |
| Dell          | Latitude E6530              | [e27a23f80b](https://linux-hardware.org/?probe=e27a23f80b) | Dec 24, 2019 |
| HP            | EliteBook 2540p             | [4663deb0dd](https://linux-hardware.org/?probe=4663deb0dd) | Dec 23, 2019 |
| Unknown       | Unknown                     | [ebb7e1b084](https://linux-hardware.org/?probe=ebb7e1b084) | Dec 22, 2019 |
| AMI           | Cherry Trail FFD            | [c62d47b2a1](https://linux-hardware.org/?probe=c62d47b2a1) | Dec 22, 2019 |
| Unknown       | Unknown                     | [a0cdc78762](https://linux-hardware.org/?probe=a0cdc78762) | Dec 22, 2019 |
| HP            | Laptop 15-db0xxx            | [3b491b92b3](https://linux-hardware.org/?probe=3b491b92b3) | Dec 21, 2019 |
| HP            | EliteBook 2760p             | [6d298da4a5](https://linux-hardware.org/?probe=6d298da4a5) | Dec 20, 2019 |
| Dell          | Latitude E5420              | [4673399116](https://linux-hardware.org/?probe=4673399116) | Dec 19, 2019 |
| Dell          | Inspiron 7520               | [e5cda35a9a](https://linux-hardware.org/?probe=e5cda35a9a) | Dec 16, 2019 |
| Dell          | Latitude E6430              | [39d47c0f09](https://linux-hardware.org/?probe=39d47c0f09) | Dec 16, 2019 |
| Minix         | NEO Z83-4 V1.1              | [c298c38fa6](https://linux-hardware.org/?probe=c298c38fa6) | Dec 16, 2019 |
| HP            | EliteBook 2760p             | [6ca3976164](https://linux-hardware.org/?probe=6ca3976164) | Dec 16, 2019 |
| Minix         | NEO Z83-4 V1.1              | [8de9a4ef47](https://linux-hardware.org/?probe=8de9a4ef47) | Dec 15, 2019 |
| HP            | Compaq nc6220 (PL814AV)     | [a770cf025e](https://linux-hardware.org/?probe=a770cf025e) | Dec 15, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [f4689330d7](https://linux-hardware.org/?probe=f4689330d7) | Dec 14, 2019 |
| Acer          | Aspire ES1-531              | [0949108352](https://linux-hardware.org/?probe=0949108352) | Dec 14, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [d651477524](https://linux-hardware.org/?probe=d651477524) | Dec 14, 2019 |
| Dell          | Latitude E6430              | [65ccc430a7](https://linux-hardware.org/?probe=65ccc430a7) | Dec 14, 2019 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | [7c53a00cb0](https://linux-hardware.org/?probe=7c53a00cb0) | Dec 12, 2019 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | [4b9dba4d4a](https://linux-hardware.org/?probe=4b9dba4d4a) | Dec 12, 2019 |
| NEC Comput... | PC-VY25AACZ9                | [67db0cd3e1](https://linux-hardware.org/?probe=67db0cd3e1) | Dec 12, 2019 |
| MSI           | GT72 2PC                    | [dbe1269ea7](https://linux-hardware.org/?probe=dbe1269ea7) | Dec 11, 2019 |
| MSI           | GL62M 7RDX                  | [b8aa5ef26c](https://linux-hardware.org/?probe=b8aa5ef26c) | Dec 09, 2019 |
| MSI           | GL62M 7RDX                  | [9c863ea710](https://linux-hardware.org/?probe=9c863ea710) | Dec 09, 2019 |
| ASUSTek       | W2P                         | [bae8402d0d](https://linux-hardware.org/?probe=bae8402d0d) | Dec 08, 2019 |
| ASUSTek       | 1001PX                      | [e368a28816](https://linux-hardware.org/?probe=e368a28816) | Dec 04, 2019 |
| Dell          | Studio 1735                 | [586b67318a](https://linux-hardware.org/?probe=586b67318a) | Dec 03, 2019 |
| Dell          | Studio 1735                 | [b90b1732fc](https://linux-hardware.org/?probe=b90b1732fc) | Dec 03, 2019 |
| BQ            | Tesla2 W10                  | [d404a738dc](https://linux-hardware.org/?probe=d404a738dc) | Dec 03, 2019 |
| ASUSTek       | X550CC                      | [b2fb796fab](https://linux-hardware.org/?probe=b2fb796fab) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [5b4aff6fe8](https://linux-hardware.org/?probe=5b4aff6fe8) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [abeaa01348](https://linux-hardware.org/?probe=abeaa01348) | Dec 03, 2019 |
| HP            | EliteBook 6930p             | [94af8c86b1](https://linux-hardware.org/?probe=94af8c86b1) | Dec 03, 2019 |
| Dell          | Inspiron 15-3567            | [f952dc6f5d](https://linux-hardware.org/?probe=f952dc6f5d) | Dec 03, 2019 |
| Unknown       | Unknown                     | [8b11eb98d3](https://linux-hardware.org/?probe=8b11eb98d3) | Dec 02, 2019 |
| Unknown       | Unknown                     | [cd4af41624](https://linux-hardware.org/?probe=cd4af41624) | Nov 30, 2019 |
| ASUSTek       | 1000H                       | [22b31ccf0f](https://linux-hardware.org/?probe=22b31ccf0f) | Nov 29, 2019 |
| HP            | Pavilion dv6                | [fdc46ce1cd](https://linux-hardware.org/?probe=fdc46ce1cd) | Nov 26, 2019 |
| Dell          | Latitude E6540              | [25a99fe356](https://linux-hardware.org/?probe=25a99fe356) | Nov 25, 2019 |
| Dell          | Latitude E6540              | [fab2125ce9](https://linux-hardware.org/?probe=fab2125ce9) | Nov 25, 2019 |
| Apple         | MacBookPro11,1              | [25987883b0](https://linux-hardware.org/?probe=25987883b0) | Nov 24, 2019 |
| Dell          | Latitude E6520              | [4384225066](https://linux-hardware.org/?probe=4384225066) | Nov 21, 2019 |
| Compal        | Unknown                     | [718c425aa1](https://linux-hardware.org/?probe=718c425aa1) | Nov 19, 2019 |
| Medion        | S6421 MD60702               | [b2abbfcf51](https://linux-hardware.org/?probe=b2abbfcf51) | Nov 16, 2019 |
| Dell          | Latitude E6520              | [5f41cfdbb1](https://linux-hardware.org/?probe=5f41cfdbb1) | Nov 16, 2019 |
| Lenovo        | G710 20252                  | [d11fbec88a](https://linux-hardware.org/?probe=d11fbec88a) | Nov 14, 2019 |
| ASUSTek       | B9440UA                     | [7f6afd4c6b](https://linux-hardware.org/?probe=7f6afd4c6b) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | [370c185f25](https://linux-hardware.org/?probe=370c185f25) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | [79c10ef42c](https://linux-hardware.org/?probe=79c10ef42c) | Nov 11, 2019 |
| Alienware     | M14xR1                      | [8be5b82b62](https://linux-hardware.org/?probe=8be5b82b62) | Nov 10, 2019 |
| Lenovo        | G710 20252                  | [21ae1ec676](https://linux-hardware.org/?probe=21ae1ec676) | Nov 10, 2019 |
| HP            | ProBook 6470b               | [ef310ee8d7](https://linux-hardware.org/?probe=ef310ee8d7) | Nov 09, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [e3a70e566b](https://linux-hardware.org/?probe=e3a70e566b) | Nov 07, 2019 |
| Sony          | VPCZ227GG                   | [6e74a95929](https://linux-hardware.org/?probe=6e74a95929) | Oct 23, 2019 |
| HP            | 15                          | [918baa5980](https://linux-hardware.org/?probe=918baa5980) | Oct 22, 2019 |
| Lenovo        | G550 2958                   | [7a2714efe5](https://linux-hardware.org/?probe=7a2714efe5) | Oct 21, 2019 |
| Acer          | Makalu                      | [00dd5c3407](https://linux-hardware.org/?probe=00dd5c3407) | Oct 19, 2019 |
| Samsung       | 305E4A/305E5A/305E7A        | [460d3c193d](https://linux-hardware.org/?probe=460d3c193d) | Oct 18, 2019 |
| AMI           | Cherry Trail CR             | [b0d2ba14cc](https://linux-hardware.org/?probe=b0d2ba14cc) | Oct 17, 2019 |
| AMI           | Cherry Trail CR             | [0a982341da](https://linux-hardware.org/?probe=0a982341da) | Oct 15, 2019 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [a605c98275](https://linux-hardware.org/?probe=a605c98275) | Oct 13, 2019 |
| Toshiba       | Satellite A210              | [afeba73834](https://linux-hardware.org/?probe=afeba73834) | Oct 12, 2019 |
| Dell          | Latitude E6430              | [eb05a0d70d](https://linux-hardware.org/?probe=eb05a0d70d) | Oct 11, 2019 |
| Dell          | Latitude E6430              | [35e84bfd49](https://linux-hardware.org/?probe=35e84bfd49) | Oct 11, 2019 |
| Toshiba       | Satellite L845              | [f39187603d](https://linux-hardware.org/?probe=f39187603d) | Oct 09, 2019 |
| HP            | ProBook 450 G2              | [b87761d1c1](https://linux-hardware.org/?probe=b87761d1c1) | Oct 07, 2019 |
| HP            | EliteBook 8560p             | [ea58ac738c](https://linux-hardware.org/?probe=ea58ac738c) | Sep 25, 2019 |
| Toshiba       | Satellite A210              | [8017271f37](https://linux-hardware.org/?probe=8017271f37) | Sep 21, 2019 |
| Alienware     | M14xR2                      | [6bf9694a56](https://linux-hardware.org/?probe=6bf9694a56) | Sep 17, 2019 |
| HP            | ProBook 640 G2              | [c4ee36c621](https://linux-hardware.org/?probe=c4ee36c621) | Sep 15, 2019 |
| HP            | 630                         | [8cb4c328bb](https://linux-hardware.org/?probe=8cb4c328bb) | Sep 10, 2019 |
| Lenovo        | Z50-70 20354                | [93800ed65a](https://linux-hardware.org/?probe=93800ed65a) | Sep 06, 2019 |
| Lenovo        | Edge 2-1580 80QF            | [b1950e5bff](https://linux-hardware.org/?probe=b1950e5bff) | Sep 04, 2019 |
| Purism        | Librem 13 v2                | [fa805c25c3](https://linux-hardware.org/?probe=fa805c25c3) | Aug 31, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [2a2ba2584f](https://linux-hardware.org/?probe=2a2ba2584f) | Aug 30, 2019 |
| Positivo      | Mobile                      | [7ceaddd485](https://linux-hardware.org/?probe=7ceaddd485) | Aug 29, 2019 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6821f97b7e](https://linux-hardware.org/?probe=6821f97b7e) | Aug 28, 2019 |
| Dell          | Latitude E5470              | [0652d6a102](https://linux-hardware.org/?probe=0652d6a102) | Aug 26, 2019 |
| HP            | 15                          | [9bafe7cbbc](https://linux-hardware.org/?probe=9bafe7cbbc) | Aug 21, 2019 |
| Acer          | Nitro AN515-42              | [c5d12ef3a9](https://linux-hardware.org/?probe=c5d12ef3a9) | Aug 21, 2019 |
| Lenovo        | IdeaPad Z570 10243VU        | [b668fbf73f](https://linux-hardware.org/?probe=b668fbf73f) | Aug 20, 2019 |
| Panasonic     | CF-SX2JDQZF5                | [6986c9f2d2](https://linux-hardware.org/?probe=6986c9f2d2) | Aug 17, 2019 |
| Dell          | Latitude E6410              | [1ab976aaff](https://linux-hardware.org/?probe=1ab976aaff) | Aug 15, 2019 |
| Toshiba       | Satellite E45t-B            | [156d965d57](https://linux-hardware.org/?probe=156d965d57) | Aug 14, 2019 |
| HP            | 3085B                       | [eeb9f3af7f](https://linux-hardware.org/?probe=eeb9f3af7f) | Aug 11, 2019 |
| Panasonic     | CF-191FYC51M                | [beedf64235](https://linux-hardware.org/?probe=beedf64235) | Aug 11, 2019 |
| Panasonic     | CF-191FYC51M                | [77a0f7454e](https://linux-hardware.org/?probe=77a0f7454e) | Aug 11, 2019 |
| Dell          | Studio XPS 1640             | [549588a8f2](https://linux-hardware.org/?probe=549588a8f2) | Aug 10, 2019 |
| Acer          | Aspire E1-571               | [16eca8b913](https://linux-hardware.org/?probe=16eca8b913) | Aug 09, 2019 |
| Sony          | VPCEH17FG                   | [68a12a9dfa](https://linux-hardware.org/?probe=68a12a9dfa) | Aug 08, 2019 |
| Sony          | VPCEH17FG                   | [f5b54a27c8](https://linux-hardware.org/?probe=f5b54a27c8) | Aug 08, 2019 |
| Lenovo        | ThinkPad T460s 20FAS3J30... | [9ffffef6da](https://linux-hardware.org/?probe=9ffffef6da) | Aug 06, 2019 |
| Ematic        | EWT147                      | [7ccb76ba13](https://linux-hardware.org/?probe=7ccb76ba13) | Aug 06, 2019 |
| Lenovo        | ThinkPad T530 2392APU       | [364e945cdb](https://linux-hardware.org/?probe=364e945cdb) | Aug 04, 2019 |
| Intel         | Crestline & ICH8M Chipse... | [6b7d39e528](https://linux-hardware.org/?probe=6b7d39e528) | Aug 04, 2019 |
| Intel         | Crestline & ICH8M Chipse... | [12a25c12c5](https://linux-hardware.org/?probe=12a25c12c5) | Aug 04, 2019 |
| Dell          | Inspiron 5521               | [5e78d3fef1](https://linux-hardware.org/?probe=5e78d3fef1) | Jul 29, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [c61c9e33f6](https://linux-hardware.org/?probe=c61c9e33f6) | Jul 28, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [d0006f445b](https://linux-hardware.org/?probe=d0006f445b) | Jul 28, 2019 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [7957c03703](https://linux-hardware.org/?probe=7957c03703) | Jul 28, 2019 |
| HP            | ENVY m6                     | [a978f2ca38](https://linux-hardware.org/?probe=a978f2ca38) | Jul 25, 2019 |
| Dell          | XPS 15 9570                 | [7a9639f003](https://linux-hardware.org/?probe=7a9639f003) | Jul 24, 2019 |
| Dell          | XPS 15 9570                 | [9ca695a346](https://linux-hardware.org/?probe=9ca695a346) | Jul 24, 2019 |
| HP            | EliteBook 840 G1            | [a6a99375a8](https://linux-hardware.org/?probe=a6a99375a8) | Jul 22, 2019 |
| HP            | Pavilion tx1000             | [4a6a073320](https://linux-hardware.org/?probe=4a6a073320) | Jul 22, 2019 |
| TUXEDO        | Unknown                     | [087a8f3344](https://linux-hardware.org/?probe=087a8f3344) | Jul 21, 2019 |
| HP            | Compaq nc6400 (RM100ET#A... | [9f51d8d813](https://linux-hardware.org/?probe=9f51d8d813) | Jul 21, 2019 |
| Dell          | Inspiron 3521               | [b471f52a9a](https://linux-hardware.org/?probe=b471f52a9a) | Jul 20, 2019 |
| HP            | EliteBook 840 G1            | [b3bb828c5a](https://linux-hardware.org/?probe=b3bb828c5a) | Jul 19, 2019 |
| Apple         | MacBookPro5,1               | [e6f14346be](https://linux-hardware.org/?probe=e6f14346be) | Jul 15, 2019 |
| HP            | Pavilion g7                 | [fef9011be9](https://linux-hardware.org/?probe=fef9011be9) | Jul 13, 2019 |
| HP            | Pavilion g7                 | [586d054ba7](https://linux-hardware.org/?probe=586d054ba7) | Jul 13, 2019 |
| Toshiba       | Satellite C55D-A            | [98772b73bb](https://linux-hardware.org/?probe=98772b73bb) | Jul 12, 2019 |
| HP            | Laptop 15-dw0xxx            | [3c4f4aba16](https://linux-hardware.org/?probe=3c4f4aba16) | Jul 09, 2019 |
| Dell          | Inspiron 7520               | [8529fa049a](https://linux-hardware.org/?probe=8529fa049a) | Jul 04, 2019 |
| Dell          | Inspiron 7520               | [3227e98bbe](https://linux-hardware.org/?probe=3227e98bbe) | Jul 04, 2019 |
| Sony          | VPCZ227GG                   | [9109d4a264](https://linux-hardware.org/?probe=9109d4a264) | Jul 03, 2019 |
| HP            | ProBook 450 G4              | [4fb036ba95](https://linux-hardware.org/?probe=4fb036ba95) | Jul 03, 2019 |
| HP            | ProBook 4730s               | [ed98a45d81](https://linux-hardware.org/?probe=ed98a45d81) | Jul 01, 2019 |
| Sony          | SVF1521B1EW                 | [20f5b70678](https://linux-hardware.org/?probe=20f5b70678) | Jun 28, 2019 |
| Dell          | Latitude E7240              | [9cc6b87f3a](https://linux-hardware.org/?probe=9cc6b87f3a) | Jun 25, 2019 |
| ASUSTek       | X541UVK                     | [baf89919e7](https://linux-hardware.org/?probe=baf89919e7) | Jun 24, 2019 |
| ASUSTek       | T300CHI                     | [1211294e7c](https://linux-hardware.org/?probe=1211294e7c) | Jun 23, 2019 |
| Toshiba       | Satellite P755              | [d9fc00d39e](https://linux-hardware.org/?probe=d9fc00d39e) | Jun 17, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [7d66aa72d3](https://linux-hardware.org/?probe=7d66aa72d3) | Jun 10, 2019 |
| ASUSTek       | T102HA                      | [1a0e086ef8](https://linux-hardware.org/?probe=1a0e086ef8) | Jun 10, 2019 |
| HP            | Pavilion tx1000             | [a783eb7140](https://linux-hardware.org/?probe=a783eb7140) | Jun 08, 2019 |
| Toshiba       | Satellite A215              | [08d2d708f8](https://linux-hardware.org/?probe=08d2d708f8) | May 23, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.3.0-40-generic  | 67        | 6.29%   |
| 5.4.0-42-generic  | 60        | 5.63%   |
| 5.3.0-46-generic  | 53        | 4.98%   |
| 5.3.0-51-generic  | 47        | 4.41%   |
| 5.0.0-37-generic  | 47        | 4.41%   |
| 5.4.0-47-generic  | 38        | 3.57%   |
| 5.3.0-53-generic  | 37        | 3.47%   |
| 5.3.0-42-generic  | 36        | 3.38%   |
| 5.4.0-45-generic  | 33        | 3.1%    |
| 5.4.0-58-generic  | 31        | 2.91%   |
| 5.4.0-48-generic  | 31        | 2.91%   |
| 5.4.0-65-generic  | 28        | 2.63%   |
| 5.4.0-80-generic  | 26        | 2.44%   |
| 5.4.0-72-generic  | 23        | 2.16%   |
| 5.4.0-52-generic  | 23        | 2.16%   |
| 5.4.0-73-generic  | 20        | 1.88%   |
| 5.3.0-62-generic  | 20        | 1.88%   |
| 5.4.0-81-generic  | 19        | 1.78%   |
| 5.4.0-70-generic  | 19        | 1.78%   |
| 5.3.0-45-generic  | 18        | 1.69%   |
| 5.4.0-54-generic  | 17        | 1.6%    |
| 5.3.0-59-generic  | 17        | 1.6%    |
| 5.3.0-28-generic  | 17        | 1.6%    |
| 5.4.0-87-generic  | 16        | 1.5%    |
| 4.18.0-25-generic | 16        | 1.5%    |
| 5.4.0-91-generic  | 15        | 1.41%   |
| 5.4.0-66-generic  | 14        | 1.31%   |
| 4.18.0-21-generic | 14        | 1.31%   |
| 5.4.0-77-generic  | 13        | 1.22%   |
| 5.4.0-64-generic  | 13        | 1.22%   |
| 5.0.0-36-generic  | 13        | 1.22%   |
| 5.4.0-89-generic  | 12        | 1.13%   |
| 4.18.0-22-generic | 12        | 1.13%   |
| 5.4.0-74-generic  | 11        | 1.03%   |
| 5.4.0-56-generic  | 10        | 0.94%   |
| 5.4.0-53-generic  | 10        | 0.94%   |
| 5.3.0-61-generic  | 10        | 0.94%   |
| 5.4.0-90-generic  | 9         | 0.85%   |
| 5.4.0-62-generic  | 9         | 0.85%   |
| 5.3.0-26-generic  | 9         | 0.85%   |
| 5.4.0-99-generic  | 8         | 0.75%   |
| 5.4.0-67-generic  | 8         | 0.75%   |
| 5.4.0-84-generic  | 7         | 0.66%   |
| 5.4.0-51-generic  | 7         | 0.66%   |
| 5.4.0-100-generic | 7         | 0.66%   |
| 5.0.0-25-generic  | 7         | 0.66%   |
| 5.0.0-23-generic  | 7         | 0.66%   |
| 5.0.0-31-generic  | 6         | 0.56%   |
| 5.4.0-105-generic | 5         | 0.47%   |
| 5.0.0-32-generic  | 5         | 0.47%   |
| 5.4.0-94-generic  | 4         | 0.38%   |
| 5.4.0-60-generic  | 4         | 0.38%   |
| 5.4.0-122-generic | 4         | 0.38%   |
| 5.4.0-120-generic | 4         | 0.38%   |
| 5.4.0-97-generic  | 3         | 0.28%   |
| 5.4.0-86-generic  | 3         | 0.28%   |
| 5.4.0-59-generic  | 3         | 0.28%   |
| 5.4.0-121-generic | 3         | 0.28%   |
| 5.4.0-109-generic | 3         | 0.28%   |
| 5.4.0-107-generic | 3         | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 535       | 54.15%  |
| 5.3.0   | 312       | 31.58%  |
| 5.0.0   | 89        | 9.01%   |
| 4.18.0  | 44        | 4.45%   |
| 5.6.0   | 2         | 0.2%    |
| 5.9.12  | 1         | 0.1%    |
| 5.9.0   | 1         | 0.1%    |
| 5.7.1   | 1         | 0.1%    |
| 5.4.1   | 1         | 0.1%    |
| 5.10.35 | 1         | 0.1%    |
| 5.10.16 | 1         | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 536       | 54.25%  |
| 5.3     | 312       | 31.58%  |
| 5.0     | 89        | 9.01%   |
| 4.18    | 44        | 4.45%   |
| 5.9     | 2         | 0.2%    |
| 5.6     | 2         | 0.2%    |
| 5.10    | 2         | 0.2%    |
| 5.7     | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 760       | 79.25%  |
| i686   | 199       | 20.75%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 506       | 52.16%  |
| XFCE       | 368       | 37.94%  |
| Unknown    | 92        | 9.48%   |
| KDE        | 2         | 0.21%   |
| X-Cinnamon | 1         | 0.1%    |
| Unity      | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 892       | 92.15%  |
| Unknown | 63        | 6.51%   |
| Wayland | 13        | 1.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 858       | 88.27%  |
| LightDM | 70        | 7.2%    |
| GDM3    | 30        | 3.09%   |
| GDM     | 8         | 0.82%   |
| TDM     | 6         | 0.62%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 307       | 31.81%  |
| pt_BR   | 77        | 7.98%   |
| Unknown | 61        | 6.32%   |
| de_DE   | 49        | 5.08%   |
| it_IT   | 46        | 4.77%   |
| en_GB   | 44        | 4.56%   |
| en_IN   | 34        | 3.52%   |
| en_CA   | 30        | 3.11%   |
| pl_PL   | 25        | 2.59%   |
| es_ES   | 24        | 2.49%   |
| pt_PT   | 22        | 2.28%   |
| fr_FR   | 19        | 1.97%   |
| C       | 17        | 1.76%   |
| es_AR   | 16        | 1.66%   |
| ru_RU   | 13        | 1.35%   |
| cs_CZ   | 13        | 1.35%   |
| es_MX   | 12        | 1.24%   |
| en_AU   | 12        | 1.24%   |
| tr_TR   | 10        | 1.04%   |
| nl_NL   | 10        | 1.04%   |
| es_CL   | 9         | 0.93%   |
| fr_CA   | 8         | 0.83%   |
| en_ZA   | 8         | 0.83%   |
| ja_JP   | 7         | 0.73%   |
| sv_SE   | 6         | 0.62%   |
| en_NZ   | 6         | 0.62%   |
| el_GR   | 6         | 0.62%   |
| de_AT   | 6         | 0.62%   |
| da_DK   | 6         | 0.62%   |
| ro_RO   | 5         | 0.52%   |
| es_PE   | 5         | 0.52%   |
| ru_UA   | 4         | 0.41%   |
| hu_HU   | 4         | 0.41%   |
| es_CO   | 4         | 0.41%   |
| en_PH   | 4         | 0.41%   |
| sk_SK   | 3         | 0.31%   |
| sl_SI   | 2         | 0.21%   |
| nl_BE   | 2         | 0.21%   |
| hr_HR   | 2         | 0.21%   |
| fi_FI   | 2         | 0.21%   |
| es_VE   | 2         | 0.21%   |
| es_PA   | 2         | 0.21%   |
| es_EC   | 2         | 0.21%   |
| en_IL   | 2         | 0.21%   |
| de_CH   | 2         | 0.21%   |
| bg_BG   | 2         | 0.21%   |
| sr_RS   | 1         | 0.1%    |
| nb_NO   | 1         | 0.1%    |
| ko_KR   | 1         | 0.1%    |
| is_IS   | 1         | 0.1%    |
| id_ID   | 1         | 0.1%    |
| es_UY   | 1         | 0.1%    |
| es_SV   | 1         | 0.1%    |
| es_HN   | 1         | 0.1%    |
| en_ZM   | 1         | 0.1%    |
| en_SG   | 1         | 0.1%    |
| en_IE   | 1         | 0.1%    |
| de_BE   | 1         | 0.1%    |
| bs_BA   | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 663       | 68.42%  |
| EFI  | 306       | 31.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 905       | 94.17%  |
| Overlay | 30        | 3.12%   |
| Unknown | 14        | 1.46%   |
| Btrfs   | 6         | 0.62%   |
| Ext2    | 5         | 0.52%   |
| Ext3    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 940       | 98.12%  |
| MBR     | 11        | 1.15%   |
| GPT     | 7         | 0.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 882       | 91.4%   |
| Yes       | 83        | 8.6%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 709       | 73.55%  |
| Yes       | 255       | 26.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 236       | 24.63%  |
| Dell                           | 142       | 14.82%  |
| Lenovo                         | 121       | 12.63%  |
| ASUSTek Computer               | 86        | 8.98%   |
| Acer                           | 86        | 8.98%   |
| Toshiba                        | 63        | 6.58%   |
| Samsung Electronics            | 27        | 2.82%   |
| Sony                           | 20        | 2.09%   |
| Apple                          | 15        | 1.57%   |
| Unknown                        | 12        | 1.25%   |
| Packard Bell                   | 11        | 1.15%   |
| Fujitsu Siemens                | 11        | 1.15%   |
| Positivo                       | 8         | 0.84%   |
| MSI                            | 8         | 0.84%   |
| Fujitsu                        | 7         | 0.73%   |
| Panasonic                      | 6         | 0.63%   |
| Medion                         | 5         | 0.52%   |
| HUAWEI                         | 5         | 0.52%   |
| eMachines                      | 5         | 0.52%   |
| Notebook                       | 4         | 0.42%   |
| NEC Computers                  | 4         | 0.42%   |
| Gateway                        | 4         | 0.42%   |
| AMI                            | 4         | 0.42%   |
| Semp Toshiba                   | 3         | 0.31%   |
| Quanta                         | 3         | 0.31%   |
| Itautec                        | 3         | 0.31%   |
| Insyde                         | 3         | 0.31%   |
| Google                         | 3         | 0.31%   |
| Ematic                         | 3         | 0.31%   |
| Clevo                          | 3         | 0.31%   |
| Alienware                      | 3         | 0.31%   |
| TrekStor                       | 2         | 0.21%   |
| Intel                          | 2         | 0.21%   |
| IBM                            | 2         | 0.21%   |
| Durabook                       | 2         | 0.21%   |
| Digibras                       | 2         | 0.21%   |
| ARIMA                          | 2         | 0.21%   |
| WIPRO                          | 1         | 0.1%    |
| WinSome                        | 1         | 0.1%    |
| UMAX                           | 1         | 0.1%    |
| TWC                            | 1         | 0.1%    |
| TUXEDO                         | 1         | 0.1%    |
| SiS                            | 1         | 0.1%    |
| Qbex                           | 1         | 0.1%    |
| Purism                         | 1         | 0.1%    |
| Phoenix/SiS                    | 1         | 0.1%    |
| Philco                         | 1         | 0.1%    |
| Pendo Industries               | 1         | 0.1%    |
| Olidata                        | 1         | 0.1%    |
| Nuvision                       | 1         | 0.1%    |
| Multilaser                     | 1         | 0.1%    |
| Minix                          | 1         | 0.1%    |
| Matsushita Electric Industrial | 1         | 0.1%    |
| Hometech                       | 1         | 0.1%    |
| HCL Infosystems Limited        | 1         | 0.1%    |
| GPD                            | 1         | 0.1%    |
| Gigabyte Technology            | 1         | 0.1%    |
| ECS                            | 1         | 0.1%    |
| Dixonsxp                       | 1         | 0.1%    |
| Compaq                         | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 26        | 2.71%   |
| HP Notebook                         | 9         | 0.94%   |
| HP Pavilion dv6                     | 6         | 0.63%   |
| HP Pavilion dv7                     | 5         | 0.52%   |
| HP Pavilion dv6700                  | 5         | 0.52%   |
| Dell Latitude E6410                 | 5         | 0.52%   |
| Dell Latitude E6400                 | 5         | 0.52%   |
| Dell Inspiron 1545                  | 5         | 0.52%   |
| Toshiba Satellite C660              | 4         | 0.42%   |
| Positivo Mobile                     | 4         | 0.42%   |
| HP Laptop 15-bw0xx                  | 4         | 0.42%   |
| HP Compaq Presario CQ61             | 4         | 0.42%   |
| HP 530                              | 4         | 0.42%   |
| HP 15                               | 4         | 0.42%   |
| Dell Latitude D630                  | 4         | 0.42%   |
| Dell Inspiron 1525                  | 4         | 0.42%   |
| Toshiba Satellite C55-A             | 3         | 0.31%   |
| Samsung 340XAA/350XAA/550XAA        | 3         | 0.31%   |
| Packard Bell EasyNote TJ65          | 3         | 0.31%   |
| HUAWEI BOHK-WAX9X                   | 3         | 0.31%   |
| HP ProBook 4540s                    | 3         | 0.31%   |
| HP Pavilion Notebook                | 3         | 0.31%   |
| HP Pavilion g7                      | 3         | 0.31%   |
| HP Pavilion dv5                     | 3         | 0.31%   |
| HP Pavilion 17                      | 3         | 0.31%   |
| HP EliteBook 8460p                  | 3         | 0.31%   |
| HP EliteBook 840 G1                 | 3         | 0.31%   |
| HP EliteBook 6930p                  | 3         | 0.31%   |
| HP Compaq Presario CQ60             | 3         | 0.31%   |
| Dell Latitude D520                  | 3         | 0.31%   |
| Dell Inspiron N4010                 | 3         | 0.31%   |
| Dell Inspiron 7520                  | 3         | 0.31%   |
| Dell Inspiron 6000                  | 3         | 0.31%   |
| Dell Inspiron 3521                  | 3         | 0.31%   |
| Dell Inspiron 1520                  | 3         | 0.31%   |
| Dell Inspiron 15-3567               | 3         | 0.31%   |
| Acer Aspire one                     | 3         | 0.31%   |
| TrekStor Notebook Slim S130         | 2         | 0.21%   |
| Toshiba Satellite M70               | 2         | 0.21%   |
| Toshiba Satellite A215              | 2         | 0.21%   |
| Toshiba Satellite A100              | 2         | 0.21%   |
| Samsung 305E4A/305E5A/305E7A        | 2         | 0.21%   |
| Quanta MW1/HW1                      | 2         | 0.21%   |
| Positivo S14CT01                    | 2         | 0.21%   |
| Packard Bell EasyNote MH35          | 2         | 0.21%   |
| Lenovo Z50-70 20354                 | 2         | 0.21%   |
| Lenovo Y70-70 Touch 80DU            | 2         | 0.21%   |
| Lenovo V145-15AST 81MT              | 2         | 0.21%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS | 2         | 0.21%   |
| Lenovo IdeaPad S130-11IGM 81J1      | 2         | 0.21%   |
| Lenovo IdeaPad 330-15AST 81D6       | 2         | 0.21%   |
| Lenovo IdeaPad 330-14AST 81D5       | 2         | 0.21%   |
| Lenovo IdeaPad 100S-14IBR 80R9      | 2         | 0.21%   |
| Lenovo G40-30 80FY                  | 2         | 0.21%   |
| Itautec Infoway                     | 2         | 0.21%   |
| HP ProBook 450 G3                   | 2         | 0.21%   |
| HP ProBook 450 G2                   | 2         | 0.21%   |
| HP Pavilion x2 Detachable           | 2         | 0.21%   |
| HP Pavilion tx1000                  | 2         | 0.21%   |
| HP Pavilion Laptop 15-cs0xxx        | 2         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Dell Inspiron           | 68        | 7.1%    |
| Acer Aspire             | 61        | 6.37%   |
| HP Pavilion             | 59        | 6.16%   |
| Toshiba Satellite       | 56        | 5.85%   |
| Lenovo ThinkPad         | 51        | 5.32%   |
| Dell Latitude           | 47        | 4.91%   |
| Lenovo IdeaPad          | 37        | 3.86%   |
| HP EliteBook            | 26        | 2.71%   |
| Unknown                 | 26        | 2.71%   |
| HP Compaq               | 25        | 2.61%   |
| HP ProBook              | 24        | 2.51%   |
| HP Laptop               | 17        | 1.77%   |
| Packard Bell EasyNote   | 11        | 1.15%   |
| HP Presario             | 10        | 1.04%   |
| HP Notebook             | 9         | 0.94%   |
| Dell Vostro             | 8         | 0.84%   |
| HP Mini                 | 7         | 0.73%   |
| HP ENVY                 | 7         | 0.73%   |
| HP 255                  | 6         | 0.63%   |
| Fujitsu Siemens AMILO   | 6         | 0.63%   |
| HP ZBook                | 5         | 0.52%   |
| HP Stream               | 5         | 0.52%   |
| HP 530                  | 5         | 0.52%   |
| Dell XPS                | 5         | 0.52%   |
| ASUS VivoBook           | 5         | 0.52%   |
| Positivo Mobile         | 4         | 0.42%   |
| HP 15                   | 4         | 0.42%   |
| Fujitsu LIFEBOOK        | 4         | 0.42%   |
| Dell System             | 4         | 0.42%   |
| ASUS ZenBook            | 4         | 0.42%   |
| ASUS ROG                | 4         | 0.42%   |
| Acer Extensa            | 4         | 0.42%   |
| Samsung 340XAA          | 3         | 0.31%   |
| Itautec Infoway         | 3         | 0.31%   |
| HUAWEI BOHK-WAX9X       | 3         | 0.31%   |
| Fujitsu Siemens ESPRIMO | 3         | 0.31%   |
| Dell Studio             | 3         | 0.31%   |
| Dell Precision          | 3         | 0.31%   |
| Acer TravelMate         | 3         | 0.31%   |
| TrekStor Notebook       | 2         | 0.21%   |
| Toshiba QOSMIO          | 2         | 0.21%   |
| Toshiba PORTEGE         | 2         | 0.21%   |
| Samsung N150            | 2         | 0.21%   |
| Samsung 355V4C          | 2         | 0.21%   |
| Samsung 305E4A          | 2         | 0.21%   |
| Quanta MW1              | 2         | 0.21%   |
| Positivo S14CT01        | 2         | 0.21%   |
| Lenovo Z50-70           | 2         | 0.21%   |
| Lenovo Y70-70           | 2         | 0.21%   |
| Lenovo V145-15AST       | 2         | 0.21%   |
| Lenovo G560             | 2         | 0.21%   |
| Lenovo G550             | 2         | 0.21%   |
| Lenovo G40-30           | 2         | 0.21%   |
| IBM ThinkPad            | 2         | 0.21%   |
| HP G42                  | 2         | 0.21%   |
| HP 635                  | 2         | 0.21%   |
| HP 550                  | 2         | 0.21%   |
| HP 250                  | 2         | 0.21%   |
| HP 2000                 | 2         | 0.21%   |
| HP 14                   | 2         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 96        | 10.02%  |
| 2010    | 89        | 9.29%   |
| 2008    | 88        | 9.19%   |
| 2007    | 83        | 8.66%   |
| 2013    | 75        | 7.83%   |
| 2009    | 73        | 7.62%   |
| 2012    | 70        | 7.31%   |
| 2018    | 62        | 6.47%   |
| 2014    | 57        | 5.95%   |
| 2017    | 53        | 5.53%   |
| 2016    | 47        | 4.91%   |
| 2019    | 46        | 4.8%    |
| 2015    | 43        | 4.49%   |
| 2006    | 34        | 3.55%   |
| 2005    | 28        | 2.92%   |
| 2020    | 12        | 1.25%   |
| 2021    | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 958       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 892       | 93.01%  |
| Enabled  | 67        | 6.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 954       | 99.58%  |
| Yes  | 4         | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 313       | 32.4%   |
| 4.01-8.0    | 198       | 20.5%   |
| 1.01-2.0    | 174       | 18.01%  |
| 8.01-16.0   | 105       | 10.87%  |
| 2.01-3.0    | 62        | 6.42%   |
| 16.01-24.0  | 52        | 5.38%   |
| 0.51-1.0    | 50        | 5.18%   |
| 32.01-64.0  | 9         | 0.93%   |
| 24.01-32.0  | 2         | 0.21%   |
| 64.01-256.0 | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 496       | 48.63%  |
| 2.01-3.0  | 211       | 20.69%  |
| 0.51-1.0  | 171       | 16.76%  |
| 3.01-4.0  | 80        | 7.84%   |
| 4.01-8.0  | 50        | 4.9%    |
| 0.01-0.5  | 9         | 0.88%   |
| 8.01-16.0 | 3         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 748       | 77.03%  |
| 2      | 191       | 19.67%  |
| 3      | 22        | 2.27%   |
| 0      | 5         | 0.51%   |
| 5      | 2         | 0.21%   |
| 4      | 2         | 0.21%   |
| 6      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 558       | 58.06%  |
| No        | 403       | 41.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 855       | 89.06%  |
| No        | 105       | 10.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 932       | 97.18%  |
| No        | 27        | 2.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 540       | 55.96%  |
| No        | 425       | 44.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 177       | 18.4%   |
| Brazil       | 89        | 9.25%   |
| Germany      | 62        | 6.44%   |
| UK           | 49        | 5.09%   |
| Italy        | 47        | 4.89%   |
| Canada       | 42        | 4.37%   |
| India        | 38        | 3.95%   |
| Poland       | 27        | 2.81%   |
| Portugal     | 24        | 2.49%   |
| France       | 23        | 2.39%   |
| Spain        | 22        | 2.29%   |
| Netherlands  | 19        | 1.98%   |
| Mexico       | 19        | 1.98%   |
| Argentina    | 19        | 1.98%   |
| Czechia      | 16        | 1.66%   |
| Sweden       | 15        | 1.56%   |
| Romania      | 15        | 1.56%   |
| Australia    | 15        | 1.56%   |
| Indonesia    | 13        | 1.35%   |
| Greece       | 11        | 1.14%   |
| Turkey       | 10        | 1.04%   |
| South Africa | 10        | 1.04%   |
| Russia       | 10        | 1.04%   |
| Serbia       | 9         | 0.94%   |
| New Zealand  | 9         | 0.94%   |
| Switzerland  | 8         | 0.83%   |
| Chile        | 8         | 0.83%   |
| Austria      | 8         | 0.83%   |
| Japan        | 7         | 0.73%   |
| Denmark      | 7         | 0.73%   |
| Colombia     | 7         | 0.73%   |
| Ukraine      | 6         | 0.62%   |
| Philippines  | 6         | 0.62%   |
| Peru         | 6         | 0.62%   |
| Egypt        | 6         | 0.62%   |
| Belgium      | 6         | 0.62%   |
| Israel       | 5         | 0.52%   |
| Bulgaria     | 5         | 0.52%   |
| Slovakia     | 4         | 0.42%   |
| Panama       | 4         | 0.42%   |
| Norway       | 4         | 0.42%   |
| Kenya        | 4         | 0.42%   |
| Hungary      | 4         | 0.42%   |
| Ecuador      | 4         | 0.42%   |
| UAE          | 3         | 0.31%   |
| Tunisia      | 3         | 0.31%   |
| Thailand     | 3         | 0.31%   |
| Slovenia     | 3         | 0.31%   |
| Ireland      | 3         | 0.31%   |
| Finland      | 3         | 0.31%   |
| Croatia      | 3         | 0.31%   |
| Vietnam      | 2         | 0.21%   |
| Venezuela    | 2         | 0.21%   |
| Sri Lanka    | 2         | 0.21%   |
| South Korea  | 2         | 0.21%   |
| Singapore    | 2         | 0.21%   |
| Pakistan     | 2         | 0.21%   |
| Malaysia     | 2         | 0.21%   |
| Lithuania    | 2         | 0.21%   |
| Iraq         | 2         | 0.21%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 12        | 1.2%    |
| Milan          | 7         | 0.7%    |
| Vienna         | 6         | 0.6%    |
| Sydney         | 6         | 0.6%    |
| Prague         | 6         | 0.6%    |
| Johannesburg   | 6         | 0.6%    |
| Istanbul       | 6         | 0.6%    |
| Auckland       | 6         | 0.6%    |
| Warsaw         | 5         | 0.5%    |
| Rome           | 5         | 0.5%    |
| Rio de Janeiro | 5         | 0.5%    |
| Montreal       | 5         | 0.5%    |
| Mexico City    | 5         | 0.5%    |
| Cairo          | 5         | 0.5%    |
| Buenos Aires   | 5         | 0.5%    |
| Bucharest      | 5         | 0.5%    |
| Berlin         | 5         | 0.5%    |
| Zurich         | 4         | 0.4%    |
| Winnipeg       | 4         | 0.4%    |
| Tel Aviv       | 4         | 0.4%    |
| Stockholm      | 4         | 0.4%    |
| Sofia          | 4         | 0.4%    |
| Perth          | 4         | 0.4%    |
| Panama City    | 4         | 0.4%    |
| Nairobi        | 4         | 0.4%    |
| Munich         | 4         | 0.4%    |
| Lisbon         | 4         | 0.4%    |
| Lima           | 4         | 0.4%    |
| Brooklyn       | 4         | 0.4%    |
| Bengaluru      | 4         | 0.4%    |
| Belgrade       | 4         | 0.4%    |
| The Hague      | 3         | 0.3%    |
| Surabaya       | 3         | 0.3%    |
| Stuttgart      | 3         | 0.3%    |
| Seattle        | 3         | 0.3%    |
| Salvador       | 3         | 0.3%    |
| Pune           | 3         | 0.3%    |
| Portland       | 3         | 0.3%    |
| Paris          | 3         | 0.3%    |
| New Delhi      | 3         | 0.3%    |
| Moscow         | 3         | 0.3%    |
| Miami          | 3         | 0.3%    |
| Madrid         | 3         | 0.3%    |
| Kyiv           | 3         | 0.3%    |
| Krakow         | 3         | 0.3%    |
| Kolkata        | 3         | 0.3%    |
| Joao Pessoa    | 3         | 0.3%    |
| Jakarta        | 3         | 0.3%    |
| Hyderabad      | 3         | 0.3%    |
| Hamburg        | 3         | 0.3%    |
| Gdansk         | 3         | 0.3%    |
| Düsseldorf    | 3         | 0.3%    |
| Davis          | 3         | 0.3%    |
| Chennai        | 3         | 0.3%    |
| Belo Horizonte | 3         | 0.3%    |
| Belfast        | 3         | 0.3%    |
| Athens         | 3         | 0.3%    |
| Ankara         | 3         | 0.3%    |
| Acworth        | 3         | 0.3%    |
| Yuba City      | 2         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 172       | 203    | 15.94%  |
| Seagate                   | 165       | 193    | 15.29%  |
| Toshiba                   | 133       | 150    | 12.33%  |
| Samsung Electronics       | 102       | 132    | 9.45%   |
| Unknown                   | 89        | 122    | 8.25%   |
| Hitachi                   | 89        | 103    | 8.25%   |
| Kingston                  | 47        | 52     | 4.36%   |
| SanDisk                   | 39        | 47     | 3.61%   |
| HGST                      | 34        | 42     | 3.15%   |
| Crucial                   | 29        | 34     | 2.69%   |
| Fujitsu                   | 27        | 28     | 2.5%    |
| Intel                     | 20        | 23     | 1.85%   |
| SK hynix                  | 11        | 15     | 1.02%   |
| China                     | 8         | 8      | 0.74%   |
| A-DATA Technology         | 8         | 8      | 0.74%   |
| Transcend                 | 6         | 9      | 0.56%   |
| Micron Technology         | 6         | 7      | 0.56%   |
| Intenso                   | 6         | 6      | 0.56%   |
| Apple                     | 6         | 6      | 0.56%   |
| PNY                       | 5         | 7      | 0.46%   |
| Patriot                   | 5         | 6      | 0.46%   |
| LITEON                    | 5         | 7      | 0.46%   |
| Team                      | 4         | 4      | 0.37%   |
| Phison                    | 4         | 5      | 0.37%   |
| SABRENT                   | 3         | 3      | 0.28%   |
| OCZ                       | 3         | 3      | 0.28%   |
| LITEONIT                  | 3         | 3      | 0.28%   |
| Zheino                    | 2         | 2      | 0.19%   |
| TCSUNBOW                  | 2         | 2      | 0.19%   |
| SPCC                      | 2         | 2      | 0.19%   |
| Plextor                   | 2         | 2      | 0.19%   |
| KingDian                  | 2         | 2      | 0.19%   |
| JMicron Technology        | 2         | 2      | 0.19%   |
| IBM/Hitachi               | 2         | 3      | 0.19%   |
| Hewlett-Packard           | 2         | 2      | 0.19%   |
| Goodram                   | 2         | 2      | 0.19%   |
| ASMT                      | 2         | 2      | 0.19%   |
| Verbatim                  | 1         | 1      | 0.09%   |
| USB30                     | 1         | 1      | 0.09%   |
| TrekStor                  | 1         | 1      | 0.09%   |
| TO Exter                  | 1         | 2      | 0.09%   |
| Realtek Semiconductor     | 1         | 1      | 0.09%   |
| PNY USB                   | 1         | 1      | 0.09%   |
| Pioneer                   | 1         | 1      | 0.09%   |
| Pacific Sun               | 1         | 1      | 0.09%   |
| OWC                       | 1         | 1      | 0.09%   |
| moweek                    | 1         | 1      | 0.09%   |
| Micron/Crucial Technology | 1         | 1      | 0.09%   |
| Maxtor                    | 1         | 1      | 0.09%   |
| Leven                     | 1         | 1      | 0.09%   |
| Kston                     | 1         | 1      | 0.09%   |
| KIOXIA                    | 1         | 1      | 0.09%   |
| Kingmax                   | 1         | 1      | 0.09%   |
| KingFast                  | 1         | 1      | 0.09%   |
| HUAWEI                    | 1         | 1      | 0.09%   |
| HS-SSD-C100               | 1         | 1      | 0.09%   |
| Faspeed                   | 1         | 1      | 0.09%   |
| EMTEC                     | 1         | 1      | 0.09%   |
| Dogfish                   | 1         | 1      | 0.09%   |
| BIWIN                     | 1         | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 40        | 3.62%   |
| Toshiba MQ01ABF050 500GB             | 21        | 1.9%    |
| Unknown MMC Card  64GB               | 15        | 1.36%   |
| Seagate ST500LT012-1DG142 500GB      | 13        | 1.18%   |
| Seagate ST1000LM035-1RK172 1TB       | 12        | 1.09%   |
| Kingston SA400S37240G 240GB SSD      | 12        | 1.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 10        | 0.91%   |
| Unknown MMC Card  16GB               | 9         | 0.82%   |
| Toshiba MQ04ABF100 1TB               | 9         | 0.82%   |
| Toshiba MQ01ABD100 1TB               | 9         | 0.82%   |
| Seagate ST9500325AS 500GB            | 9         | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 0.82%   |
| Hitachi HTS545032B9A300 320GB        | 9         | 0.82%   |
| HGST HTS725050A7E630 500GB           | 9         | 0.82%   |
| Kingston SA400S37480G 480GB SSD      | 8         | 0.72%   |
| Crucial CT240BX500SSD1 240GB         | 8         | 0.72%   |
| Samsung NVMe SSD Drive 512GB         | 7         | 0.63%   |
| Samsung NVMe SSD Drive 256GB         | 7         | 0.63%   |
| Samsung HM160HI 160GB                | 7         | 0.63%   |
| Hitachi HTS543232A7A384 320GB        | 7         | 0.63%   |
| Unknown MMC Card  128GB              | 6         | 0.54%   |
| Seagate ST9320325AS 320GB            | 6         | 0.54%   |
| Seagate ST9250315AS 250GB            | 6         | 0.54%   |
| Seagate ST9160314AS 160GB            | 6         | 0.54%   |
| Samsung HM321HI 320GB                | 6         | 0.54%   |
| Kingston SA400S37120G 120GB SSD      | 6         | 0.54%   |
| HGST HTS541010A9E680 1TB             | 6         | 0.54%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 5         | 0.45%   |
| WDC WD10JPVX-60JC3T0 1TB             | 5         | 0.45%   |
| Seagate ST500LT012-9WS142 500GB      | 5         | 0.45%   |
| Samsung SSD 860 EVO 250GB            | 5         | 0.45%   |
| Samsung SSD 850 EVO 500GB            | 5         | 0.45%   |
| Intel NVMe SSD Drive 512GB           | 5         | 0.45%   |
| HGST HTS721010A9E630 1TB             | 5         | 0.45%   |
| HGST HTS545050A7E680 500GB           | 5         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 4         | 0.36%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 4         | 0.36%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 4         | 0.36%   |
| WDC WD2500BEVT-22A23T0 250GB         | 4         | 0.36%   |
| WDC WD1600BEVT-22A23T0 160GB         | 4         | 0.36%   |
| WDC WD10JPVX-60JC3T1 1TB             | 4         | 0.36%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 0.36%   |
| WDC WD10JPCX-24UE4T0 1TB             | 4         | 0.36%   |
| Toshiba MQ01ABD032 320GB             | 4         | 0.36%   |
| Seagate ST9250827AS 250GB            | 4         | 0.36%   |
| Seagate ST9160821AS 160GB            | 4         | 0.36%   |
| Seagate ST500LM021-1KJ152 500GB      | 4         | 0.36%   |
| Seagate ST2000LM007-1R8174 2TB       | 4         | 0.36%   |
| Seagate ST1000LM014-1EJ164 1TB       | 4         | 0.36%   |
| Seagate Expansion 1TB                | 4         | 0.36%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD | 4         | 0.36%   |
| Kingston SV300S37A120G 120GB SSD     | 4         | 0.36%   |
| Hitachi HTS547575A9E384 752GB        | 4         | 0.36%   |
| Hitachi HTS547550A9E384 500GB        | 4         | 0.36%   |
| Hitachi HTS545050A7E380 500GB        | 4         | 0.36%   |
| Hitachi HTS545016B9A300 160GB        | 4         | 0.36%   |
| Hitachi HTS543232L9A300 320GB        | 4         | 0.36%   |
| Hitachi HTS543216L9A300 160GB        | 4         | 0.36%   |
| Hitachi HTS541680J9SA00 80GB         | 4         | 0.36%   |
| Hitachi HTS541616J9SA00 160GB        | 4         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 163       | 188    | 25.91%  |
| WDC                 | 161       | 184    | 25.6%   |
| Toshiba             | 122       | 137    | 19.4%   |
| Hitachi             | 89        | 103    | 14.15%  |
| HGST                | 34        | 42     | 5.41%   |
| Fujitsu             | 27        | 28     | 4.29%   |
| Samsung Electronics | 23        | 27     | 3.66%   |
| SABRENT             | 3         | 3      | 0.48%   |
| Unknown             | 2         | 5      | 0.32%   |
| IBM/Hitachi         | 2         | 3      | 0.32%   |
| ASMT                | 2         | 2      | 0.32%   |
| Apple               | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 59        | 76     | 20.07%  |
| Kingston            | 41        | 45     | 13.95%  |
| SanDisk             | 29        | 35     | 9.86%   |
| Crucial             | 29        | 34     | 9.86%   |
| WDC                 | 14        | 19     | 4.76%   |
| Intel               | 14        | 15     | 4.76%   |
| SK hynix            | 9         | 13     | 3.06%   |
| China               | 8         | 8      | 2.72%   |
| A-DATA Technology   | 8         | 8      | 2.72%   |
| Toshiba             | 7         | 8      | 2.38%   |
| Transcend           | 6         | 9      | 2.04%   |
| PNY                 | 5         | 7      | 1.7%    |
| Patriot             | 5         | 6      | 1.7%    |
| Micron Technology   | 5         | 6      | 1.7%    |
| LITEON              | 5         | 7      | 1.7%    |
| Apple               | 5         | 5      | 1.7%    |
| Team                | 4         | 4      | 1.36%   |
| Intenso             | 4         | 4      | 1.36%   |
| OCZ                 | 3         | 3      | 1.02%   |
| LITEONIT            | 3         | 3      | 1.02%   |
| TCSUNBOW            | 2         | 2      | 0.68%   |
| SPCC                | 2         | 2      | 0.68%   |
| Plextor             | 2         | 2      | 0.68%   |
| KingDian            | 2         | 2      | 0.68%   |
| Goodram             | 2         | 2      | 0.68%   |
| Zheino              | 1         | 1      | 0.34%   |
| Verbatim            | 1         | 1      | 0.34%   |
| USB30               | 1         | 1      | 0.34%   |
| Unknown             | 1         | 1      | 0.34%   |
| TrekStor            | 1         | 1      | 0.34%   |
| TO Exter            | 1         | 2      | 0.34%   |
| Seagate             | 1         | 1      | 0.34%   |
| PNY USB             | 1         | 1      | 0.34%   |
| Pioneer             | 1         | 1      | 0.34%   |
| Pacific Sun         | 1         | 1      | 0.34%   |
| OWC                 | 1         | 1      | 0.34%   |
| Maxtor              | 1         | 1      | 0.34%   |
| Leven               | 1         | 1      | 0.34%   |
| Kingmax             | 1         | 1      | 0.34%   |
| Hewlett-Packard     | 1         | 1      | 0.34%   |
| EMTEC               | 1         | 1      | 0.34%   |
| Dogfish             | 1         | 1      | 0.34%   |
| BIWIN               | 1         | 1      | 0.34%   |
| BHT                 | 1         | 1      | 0.34%   |
| AS201               | 1         | 1      | 0.34%   |
| Apacer              | 1         | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 615       | 723    | 58.18%  |
| SSD     | 281       | 347    | 26.58%  |
| MMC     | 87        | 119    | 8.23%   |
| NVMe    | 56        | 70     | 5.3%    |
| Unknown | 18        | 20     | 1.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 857       | 1052   | 83.86%  |
| MMC  | 87        | 119    | 8.51%   |
| NVMe | 54        | 68     | 5.28%   |
| SAS  | 24        | 40     | 2.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 710       | 843    | 79.6%   |
| 0.51-1.0   | 172       | 215    | 19.28%  |
| 1.01-2.0   | 7         | 9      | 0.78%   |
| 3.01-4.0   | 2         | 2      | 0.22%   |
| 4.01-10.0  | 1         | 1      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 348       | 35.51%  |
| 251-500        | 247       | 25.2%   |
| 51-100         | 126       | 12.86%  |
| 501-1000       | 97        | 9.9%    |
| 21-50          | 74        | 7.55%   |
| 1-20           | 44        | 4.49%   |
| 1001-2000      | 31        | 3.16%   |
| More than 3000 | 6         | 0.61%   |
| Unknown        | 4         | 0.41%   |
| 2001-3000      | 3         | 0.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 636       | 62.91%  |
| 21-50          | 167       | 16.52%  |
| 51-100         | 78        | 7.72%   |
| 101-250        | 70        | 6.92%   |
| 251-500        | 34        | 3.36%   |
| 501-1000       | 11        | 1.09%   |
| 1001-2000      | 6         | 0.59%   |
| More than 3000 | 4         | 0.4%    |
| Unknown        | 4         | 0.4%    |
| 2001-3000      | 1         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 2         | 2      | 20%     |
| WDC WD3200BPVT-55ZEST0 320GB                        | 1         | 1      | 10%     |
| Toshiba MK5061GSY 500GB                             | 1         | 1      | 10%     |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 10%     |
| Seagate ST9160314AS 160GB                           | 1         | 1      | 10%     |
| Seagate ST9120822AS 120GB                           | 1         | 1      | 10%     |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 10%     |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 10%     |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 60%     |
| WDC               | 1         | 1      | 10%     |
| Toshiba           | 1         | 1      | 10%     |
| Micron Technology | 1         | 1      | 10%     |
| Hitachi           | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 66.67%  |
| WDC     | 1         | 1      | 11.11%  |
| Toshiba | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 90%     |
| SSD  | 1         | 1      | 10%     |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 931       | 1248   | 97.08%  |
| Works    | 18        | 21     | 1.88%   |
| Malfunc  | 10        | 10     | 1.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 718       | 74.48%  |
| AMD                              | 133       | 13.8%   |
| Samsung Electronics              | 25        | 2.59%   |
| Nvidia                           | 24        | 2.49%   |
| Silicon Integrated Systems [SiS] | 23        | 2.39%   |
| SanDisk                          | 8         | 0.83%   |
| VIA Technologies                 | 7         | 0.73%   |
| Kingston Technology Company      | 6         | 0.62%   |
| Toshiba America Info Systems     | 5         | 0.52%   |
| JMicron Technology               | 5         | 0.52%   |
| Phison Electronics               | 3         | 0.31%   |
| Union Memory (Shenzhen)          | 1         | 0.1%    |
| SK hynix                         | 1         | 0.1%    |
| Realtek Semiconductor            | 1         | 0.1%    |
| Micron/Crucial Technology        | 1         | 0.1%    |
| Micron Technology                | 1         | 0.1%    |
| Marvell Technology Group         | 1         | 0.1%    |
| KIOXIA                           | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 80        | 7.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 69        | 6.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 68        | 5.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 68        | 5.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 66        | 5.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 57        | 5.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 47        | 4.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 46        | 4.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 37        | 3.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 35        | 3.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 33        | 2.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 29        | 2.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 29        | 2.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 25        | 2.2%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 24        | 2.11%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 23        | 2.02%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 23        | 2.02%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 19        | 1.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 19        | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 16        | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 15        | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 14        | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 13        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 13        | 1.14%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 12        | 1.06%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 11        | 0.97%   |
| AMD IXP SB4x0 IDE Controller                                                           | 11        | 0.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 9         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 9         | 0.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 9         | 0.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 9         | 0.79%   |
| Nvidia MCP67 AHCI Controller                                                           | 7         | 0.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 7         | 0.62%   |
| AMD FCH IDE Controller                                                                 | 7         | 0.62%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 6         | 0.53%   |
| Nvidia MCP79 AHCI Controller                                                           | 6         | 0.53%   |
| Nvidia MCP67 IDE Controller                                                            | 6         | 0.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 6         | 0.53%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 6         | 0.53%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 6         | 0.53%   |
| Intel SSD 660P Series                                                                  | 5         | 0.44%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 5         | 0.44%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 5         | 0.44%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 5         | 0.44%   |
| AMD SB600 IDE                                                                          | 5         | 0.44%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 5         | 0.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 0.35%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                           | 4         | 0.35%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                       | 4         | 0.35%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 4         | 0.35%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 4         | 0.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 4         | 0.35%   |
| AMD IXP SB4x0 Serial ATA Controller                                                    | 4         | 0.35%   |
| VIA VT8237A SATA 2-Port Controller                                                     | 3         | 0.26%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 3         | 0.26%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 0.26%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 3         | 0.26%   |
| Nvidia MCP51 Serial ATA Controller                                                     | 3         | 0.26%   |
| Nvidia MCP51 IDE                                                                       | 3         | 0.26%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                            | 3         | 0.26%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 691       | 65.87%  |
| IDE  | 254       | 24.21%  |
| NVMe | 55        | 5.24%   |
| RAID | 49        | 4.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 805       | 84.03%  |
| AMD          | 152       | 15.87%  |
| CentaurHauls | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 1.46%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 14        | 1.46%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 12        | 1.25%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 12        | 1.25%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 12        | 1.25%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 11        | 1.15%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 11        | 1.15%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 1.04%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 9         | 0.94%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 9         | 0.94%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 9         | 0.94%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 9         | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 0.84%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 8         | 0.84%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 8         | 0.84%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 8         | 0.84%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 7         | 0.73%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 7         | 0.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.73%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 0.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 0.73%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 7         | 0.73%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 7         | 0.73%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 7         | 0.73%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 7         | 0.73%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 7         | 0.73%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 7         | 0.73%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.73%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 0.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 0.63%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.63%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 6         | 0.63%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 6         | 0.63%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 6         | 0.63%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 6         | 0.63%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 6         | 0.63%   |
| Intel Celeron CPU 550 @ 2.00GHz               | 6         | 0.63%   |
| AMD E-450 APU with Radeon HD Graphics         | 6         | 0.63%   |
| AMD C-50 Processor                            | 6         | 0.63%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 5         | 0.52%   |
| Intel Genuine CPU T2050 @ 1.60GHz             | 5         | 0.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.52%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 0.52%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 5         | 0.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.52%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.52%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 5         | 0.52%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 0.52%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 0.52%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 5         | 0.52%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 5         | 0.52%   |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 5         | 0.52%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 0.52%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 5         | 0.52%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 5         | 0.52%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 5         | 0.52%   |
| Intel Pentium M processor 1.73GHz             | 4         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 157       | 16.39%  |
| Intel Core i7           | 127       | 13.26%  |
| Intel Core 2 Duo        | 109       | 11.38%  |
| Intel Core i3           | 95        | 9.92%   |
| Intel Celeron           | 80        | 8.35%   |
| Intel Atom              | 78        | 8.14%   |
| Intel Pentium           | 29        | 3.03%   |
| Intel Genuine           | 27        | 2.82%   |
| Intel Pentium Dual-Core | 20        | 2.09%   |
| Intel Pentium M         | 18        | 1.88%   |
| Intel Pentium Dual      | 17        | 1.77%   |
| Intel Celeron M         | 17        | 1.77%   |
| AMD A6                  | 17        | 1.77%   |
| Intel Core 2            | 15        | 1.57%   |
| AMD A4                  | 14        | 1.46%   |
| AMD Ryzen 5             | 11        | 1.15%   |
| AMD Ryzen 3             | 11        | 1.15%   |
| AMD E                   | 10        | 1.04%   |
| AMD E1                  | 9         | 0.94%   |
| AMD Turion 64 X2 Mobile | 8         | 0.84%   |
| AMD Turion 64 Mobile    | 7         | 0.73%   |
| AMD Ryzen 7             | 6         | 0.63%   |
| AMD C-50                | 6         | 0.63%   |
| AMD A10                 | 6         | 0.63%   |
| Intel Celeron Dual-Core | 5         | 0.52%   |
| AMD Athlon 64 X2        | 5         | 0.52%   |
| AMD A8                  | 5         | 0.52%   |
| Intel Core Duo          | 4         | 0.42%   |
| AMD Mobile Sempron      | 4         | 0.42%   |
| AMD E2                  | 4         | 0.42%   |
| AMD C-60                | 4         | 0.42%   |
| AMD Athlon X2           | 4         | 0.42%   |
| Other                   | 3         | 0.31%   |
| AMD Sempron             | 3         | 0.31%   |
| AMD Turion Dual-Core    | 2         | 0.21%   |
| AMD Ryzen 9             | 2         | 0.21%   |
| AMD Phenom II           | 2         | 0.21%   |
| AMD Athlon II           | 2         | 0.21%   |
| Intel Xeon              | 1         | 0.1%    |
| Intel Pentium 4         | 1         | 0.1%    |
| Intel Core m7           | 1         | 0.1%    |
| Intel Core m3           | 1         | 0.1%    |
| Intel Core M            | 1         | 0.1%    |
| Intel Core 2 Quad       | 1         | 0.1%    |
| Intel Core 2 Extreme    | 1         | 0.1%    |
| CentaurHauls VIA C7     | 1         | 0.1%    |
| AMD V120                | 1         | 0.1%    |
| AMD Turion II Dual-Core | 1         | 0.1%    |
| AMD Turion II           | 1         | 0.1%    |
| AMD Quad-Core           | 1         | 0.1%    |
| AMD Athlon II Dual-Core | 1         | 0.1%    |
| AMD Athlon 64           | 1         | 0.1%    |
| AMD Athlon              | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 654       | 68.27%  |
| 4      | 160       | 16.7%   |
| 1      | 125       | 13.05%  |
| 6      | 13        | 1.36%   |
| 8      | 5         | 0.52%   |
| 3      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 958       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 488       | 50.94%  |
| 2      | 470       | 49.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 879       | 91.66%  |
| 32-bit         | 79        | 8.24%   |
| Unknown        | 1         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 98        | 10.11%  |
| 0x206a7    | 93        | 9.6%    |
| 0x1067a    | 70        | 7.22%   |
| 0x306a9    | 58        | 5.99%   |
| 0x6fd      | 48        | 4.95%   |
| 0x40651    | 40        | 4.13%   |
| 0x20655    | 32        | 3.3%    |
| 0x306c3    | 28        | 2.89%   |
| 0x406e3    | 27        | 2.79%   |
| 0x106ca    | 26        | 2.68%   |
| 0x806e9    | 22        | 2.27%   |
| 0x6e8      | 22        | 2.27%   |
| 0x306d4    | 22        | 2.27%   |
| 0x6d8      | 21        | 2.17%   |
| 0x10676    | 20        | 2.06%   |
| 0x406c4    | 19        | 1.96%   |
| 0x106c2    | 19        | 1.96%   |
| 0x806ea    | 18        | 1.86%   |
| 0x30678    | 17        | 1.75%   |
| 0x406c3    | 15        | 1.55%   |
| 0x10661    | 15        | 1.55%   |
| 0x6f6      | 14        | 1.44%   |
| 0x06006705 | 14        | 1.44%   |
| 0x05000119 | 13        | 1.34%   |
| 0x20652    | 12        | 1.24%   |
| 0x906ea    | 11        | 1.14%   |
| 0x6ec      | 11        | 1.14%   |
| 0x906e9    | 10        | 1.03%   |
| 0x6fb      | 10        | 1.03%   |
| 0x506c9    | 9         | 0.93%   |
| 0x05000029 | 9         | 0.93%   |
| 0x08108102 | 8         | 0.83%   |
| 0x0700010f | 8         | 0.83%   |
| 0x06001119 | 8         | 0.83%   |
| 0x806ec    | 7         | 0.72%   |
| 0x08108109 | 7         | 0.72%   |
| 0x806eb    | 6         | 0.62%   |
| 0x706a1    | 6         | 0.62%   |
| 0x0810100b | 6         | 0.62%   |
| 0x03000027 | 6         | 0.62%   |
| 0x30673    | 5         | 0.52%   |
| 0x07030105 | 5         | 0.52%   |
| 0x010000c8 | 5         | 0.52%   |
| 0x6fa      | 4         | 0.41%   |
| 0x02000057 | 4         | 0.41%   |
| 0x02000032 | 4         | 0.41%   |
| 0x706e5    | 3         | 0.31%   |
| 0x07030106 | 3         | 0.31%   |
| 0x6f2      | 2         | 0.21%   |
| 0x6d6      | 2         | 0.21%   |
| 0x506e3    | 2         | 0.21%   |
| 0x30661    | 2         | 0.21%   |
| 0x08600104 | 2         | 0.21%   |
| 0x08600102 | 2         | 0.21%   |
| 0x07030104 | 2         | 0.21%   |
| 0x07000110 | 2         | 0.21%   |
| 0x06006704 | 2         | 0.21%   |
| 0xf41      | 1         | 0.1%    |
| 0xa0660    | 1         | 0.1%    |
| 0xa0652    | 1         | 0.1%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Core            | 99        | 10.33%  |
| Penryn          | 98        | 10.23%  |
| SandyBridge     | 93        | 9.71%   |
| KabyLake        | 82        | 8.56%   |
| Haswell         | 74        | 7.72%   |
| Silvermont      | 67        | 6.99%   |
| IvyBridge       | 62        | 6.47%   |
| P6              | 57        | 5.95%   |
| Westmere        | 48        | 5.01%   |
| Bonnell         | 48        | 5.01%   |
| Skylake         | 32        | 3.34%   |
| K8 Hammer       | 27        | 2.82%   |
| Bobcat          | 23        | 2.4%    |
| Broadwell       | 22        | 2.3%    |
| Excavator       | 18        | 1.88%   |
| Zen+            | 15        | 1.57%   |
| Jaguar          | 11        | 1.15%   |
| Puma            | 10        | 1.04%   |
| Piledriver      | 9         | 0.94%   |
| Goldmont        | 9         | 0.94%   |
| K8 & K10 hybrid | 8         | 0.84%   |
| K10             | 8         | 0.84%   |
| Zen 2           | 7         | 0.73%   |
| Zen             | 7         | 0.73%   |
| Goldmont plus   | 7         | 0.73%   |
| K10 Llano       | 6         | 0.63%   |
| IceLake         | 3         | 0.31%   |
| Steamroller     | 2         | 0.21%   |
| CometLake       | 2         | 0.21%   |
| Unknown         | 2         | 0.21%   |
| NetBurst        | 1         | 0.1%    |
| Nehalem         | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 668       | 60.73%  |
| AMD                              | 220       | 20%     |
| Nvidia                           | 184       | 16.73%  |
| Silicon Integrated Systems [SiS] | 21        | 1.91%   |
| VIA Technologies                 | 7         | 0.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 82        | 6.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 58        | 4.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 57        | 4.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 50        | 4.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 42        | 3.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 42        | 3.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 42        | 3.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 39        | 3.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 39        | 3.22%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 31        | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 31        | 2.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 2.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 28        | 2.31%   |
| Intel HD Graphics 620                                                                    | 27        | 2.23%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 27        | 2.23%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 19        | 1.57%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 19        | 1.57%   |
| Intel HD Graphics 5500                                                                   | 19        | 1.57%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 17        | 1.4%    |
| Intel UHD Graphics 620                                                                   | 16        | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 0.99%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 12        | 0.99%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 0.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 0.74%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 9         | 0.74%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.74%   |
| Intel HD Graphics 630                                                                    | 8         | 0.66%   |
| Intel HD Graphics 500                                                                    | 8         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.58%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 7         | 0.58%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.58%   |
| AMD Renoir                                                                               | 7         | 0.58%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.58%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 6         | 0.5%    |
| AMD Wrestler [Radeon HD 6250]                                                            | 6         | 0.5%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 6         | 0.5%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 6         | 0.5%    |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.41%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.41%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 5         | 0.41%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 5         | 0.41%   |
| Nvidia C67 [GeForce 7150M / nForce 630M]                                                 | 5         | 0.41%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 5         | 0.41%   |
| AMD RV370/M22 [Mobility Radeon X300]                                                     | 5         | 0.41%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 5         | 0.41%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 0.41%   |
| AMD Kabini [Radeon HD 8210]                                                              | 5         | 0.41%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 4         | 0.33%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 4         | 0.33%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 4         | 0.33%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 4         | 0.33%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 4         | 0.33%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 0.33%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 4         | 0.33%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 4         | 0.33%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 4         | 0.33%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                                  | 4         | 0.33%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 530       | 55.21%  |
| 1 x AMD        | 155       | 16.15%  |
| Intel + Nvidia | 93        | 9.69%   |
| 1 x Nvidia     | 84        | 8.75%   |
| Intel + AMD    | 44        | 4.58%   |
| 1 x SiS        | 21        | 2.19%   |
| 2 x AMD        | 16        | 1.67%   |
| 1 x VIA        | 7         | 0.73%   |
| AMD + Nvidia   | 5         | 0.52%   |
| 2 x Nvidia     | 3         | 0.31%   |
| Other          | 2         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 825       | 85.76%  |
| Proprietary | 76        | 7.9%    |
| Unknown     | 61        | 6.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 641       | 66.42%  |
| 0.01-0.5   | 176       | 18.24%  |
| 1.01-2.0   | 63        | 6.53%   |
| 0.51-1.0   | 56        | 5.8%    |
| 3.01-4.0   | 23        | 2.38%   |
| 7.01-8.0   | 3         | 0.31%   |
| 5.01-6.0   | 2         | 0.21%   |
| 2.01-3.0   | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 190       | 20.72%  |
| LG Display              | 144       | 15.7%   |
| Samsung Electronics     | 143       | 15.59%  |
| Chimei Innolux          | 87        | 9.49%   |
| BOE                     | 73        | 7.96%   |
| Chi Mei Optoelectronics | 51        | 5.56%   |
| LG Philips              | 38        | 4.14%   |
| Apple                   | 17        | 1.85%   |
| Lenovo                  | 15        | 1.64%   |
| InfoVision              | 15        | 1.64%   |
| Toshiba                 | 12        | 1.31%   |
| Goldstar                | 11        | 1.2%    |
| Sharp                   | 9         | 0.98%   |
| HannStar                | 9         | 0.98%   |
| Dell                    | 9         | 0.98%   |
| CPT                     | 9         | 0.98%   |
| Quanta Display          | 8         | 0.87%   |
| Seiko/Epson             | 7         | 0.76%   |
| PANDA                   | 5         | 0.55%   |
| InnoLux Display         | 5         | 0.55%   |
| Sony                    | 4         | 0.44%   |
| Panasonic               | 4         | 0.44%   |
| LGD                     | 4         | 0.44%   |
| Hewlett-Packard         | 4         | 0.44%   |
| Eizo                    | 4         | 0.44%   |
| AOC                     | 4         | 0.44%   |
| Acer                    | 4         | 0.44%   |
| Unknown                 | 3         | 0.33%   |
| Nvidia                  | 3         | 0.33%   |
| ___                     | 2         | 0.22%   |
| ViewSonic               | 2         | 0.22%   |
| Philips                 | 2         | 0.22%   |
| Iiyama                  | 2         | 0.22%   |
| IBM                     | 2         | 0.22%   |
| BenQ                    | 2         | 0.22%   |
| Vizio                   | 1         | 0.11%   |
| Vestel Elektronik       | 1         | 0.11%   |
| Vestel                  | 1         | 0.11%   |
| Unknown (AAA)           | 1         | 0.11%   |
| TM@                     | 1         | 0.11%   |
| Tianma XM               | 1         | 0.11%   |
| TCL                     | 1         | 0.11%   |
| STD                     | 1         | 0.11%   |
| SKY                     | 1         | 0.11%   |
| MTD                     | 1         | 0.11%   |
| LPL                     | 1         | 0.11%   |
| KLF                     | 1         | 0.11%   |
| Daewoo                  | 1         | 0.11%   |
| cPATH                   | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 15        | 1.62%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 13        | 1.4%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.97%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 9         | 0.97%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 7         | 0.76%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 7         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.65%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 6         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 5         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 5         | 0.54%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 5         | 0.54%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 5         | 0.54%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 5         | 0.54%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 5         | 0.54%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 5         | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 222x125mm 10.0-inch | 5         | 0.54%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.54%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 0.54%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.54%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 5         | 0.54%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 4         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 4         | 0.43%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch              | 4         | 0.43%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch              | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 4         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch     | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch     | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 340x190mm 15.3-inch     | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 3         | 0.32%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 3         | 0.32%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 3         | 0.32%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 3         | 0.32%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 3         | 0.32%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch              | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 3         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 3         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 3         | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 3         | 0.32%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 0.32%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 3         | 0.32%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO733C 1366x768 309x173mm 13.9-inch            | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 293x165mm 13.2-inch           | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 401       | 44.26%  |
| 1920x1080 (FHD)    | 181       | 19.98%  |
| 1280x800 (WXGA)    | 111       | 12.25%  |
| 1600x900 (HD+)     | 65        | 7.17%   |
| 1024x600           | 33        | 3.64%   |
| 1440x900 (WXGA+)   | 30        | 3.31%   |
| 3840x2160 (4K)     | 15        | 1.66%   |
| 1920x1200 (WUXGA)  | 14        | 1.55%   |
| 1680x1050 (WSXGA+) | 10        | 1.1%    |
| 1024x768 (XGA)     | 7         | 0.77%   |
| 1280x768           | 6         | 0.66%   |
| 2560x1600          | 4         | 0.44%   |
| 1360x768           | 4         | 0.44%   |
| 1280x1024 (SXGA)   | 4         | 0.44%   |
| 2560x1440 (QHD)    | 3         | 0.33%   |
| 1400x1050          | 3         | 0.33%   |
| 1024x576           | 3         | 0.33%   |
| 1680x945           | 2         | 0.22%   |
| 5760x2160          | 1         | 0.11%   |
| 3840x1080          | 1         | 0.11%   |
| 3200x1800 (QHD+)   | 1         | 0.11%   |
| 2880x1800          | 1         | 0.11%   |
| 2560x1080          | 1         | 0.11%   |
| 2288x1287          | 1         | 0.11%   |
| 2160x1440          | 1         | 0.11%   |
| 2048x1152          | 1         | 0.11%   |
| 1920x540           | 1         | 0.11%   |
| Unknown            | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 416       | 45.27%  |
| 14      | 106       | 11.53%  |
| 13      | 105       | 11.43%  |
| 17      | 80        | 8.71%   |
| 10      | 37        | 4.03%   |
| 11      | 36        | 3.92%   |
| Unknown | 30        | 3.26%   |
| 12      | 22        | 2.39%   |
| 24      | 13        | 1.41%   |
| 21      | 12        | 1.31%   |
| 27      | 11        | 1.2%    |
| 23      | 7         | 0.76%   |
| 72      | 5         | 0.54%   |
| 18      | 5         | 0.54%   |
| 22      | 4         | 0.44%   |
| 20      | 4         | 0.44%   |
| 31      | 3         | 0.33%   |
| 8       | 3         | 0.33%   |
| 84      | 2         | 0.22%   |
| 54      | 2         | 0.22%   |
| 40      | 2         | 0.22%   |
| 34      | 2         | 0.22%   |
| 74      | 1         | 0.11%   |
| 59      | 1         | 0.11%   |
| 58      | 1         | 0.11%   |
| 49      | 1         | 0.11%   |
| 46      | 1         | 0.11%   |
| 44      | 1         | 0.11%   |
| 41      | 1         | 0.11%   |
| 33      | 1         | 0.11%   |
| 32      | 1         | 0.11%   |
| 29      | 1         | 0.11%   |
| 19      | 1         | 0.11%   |
| 16      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 572       | 62.45%  |
| 201-300     | 132       | 14.41%  |
| 351-400     | 96        | 10.48%  |
| 501-600     | 30        | 3.28%   |
| Unknown     | 30        | 3.28%   |
| 401-500     | 26        | 2.84%   |
| 1501-2000   | 8         | 0.87%   |
| 1001-1500   | 6         | 0.66%   |
| 601-700     | 5         | 0.55%   |
| 701-800     | 4         | 0.44%   |
| 101-200     | 3         | 0.33%   |
| 801-900     | 2         | 0.22%   |
| 901-1000    | 2         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 658       | 76.33%  |
| 16/10   | 161       | 18.68%  |
| Unknown | 25        | 2.9%    |
| 4/3     | 11        | 1.28%   |
| 5/4     | 4         | 0.46%   |
| 32/9    | 1         | 0.12%   |
| 3/2     | 1         | 0.12%   |
| 21/9    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 416       | 45.46%  |
| 81-90          | 179       | 19.56%  |
| 121-130        | 47        | 5.14%   |
| 41-50          | 37        | 4.04%   |
| 51-60          | 36        | 3.93%   |
| Unknown        | 30        | 3.28%   |
| 131-140        | 29        | 3.17%   |
| 71-80          | 27        | 2.95%   |
| 201-250        | 23        | 2.51%   |
| 61-70          | 22        | 2.4%    |
| More than 1000 | 12        | 1.31%   |
| 301-350        | 11        | 1.2%    |
| 151-200        | 11        | 1.2%    |
| 141-150        | 9         | 0.98%   |
| 351-500        | 7         | 0.77%   |
| 501-1000       | 7         | 0.77%   |
| 251-300        | 5         | 0.55%   |
| 91-100         | 4         | 0.44%   |
| 1-40           | 3         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 435       | 48.28%  |
| 121-160       | 206       | 22.86%  |
| 51-100        | 191       | 21.2%   |
| Unknown       | 30        | 3.33%   |
| 161-240       | 23        | 2.55%   |
| 1-50          | 11        | 1.22%   |
| More than 240 | 5         | 0.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 821       | 84.12%  |
| 2     | 85        | 8.71%   |
| 0     | 65        | 6.66%   |
| 3     | 5         | 0.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 485       | 29.83%  |
| Intel                                  | 356       | 21.89%  |
| Qualcomm Atheros                       | 297       | 18.27%  |
| Broadcom                               | 188       | 11.56%  |
| Broadcom Limited                       | 60        | 3.69%   |
| Marvell Technology Group               | 42        | 2.58%   |
| Silicon Integrated Systems [SiS]       | 23        | 1.41%   |
| Ralink                                 | 21        | 1.29%   |
| Nvidia                                 | 20        | 1.23%   |
| JMicron Technology                     | 12        | 0.74%   |
| TP-Link                                | 11        | 0.68%   |
| Ralink Technology                      | 9         | 0.55%   |
| Xiaomi                                 | 7         | 0.43%   |
| Sierra Wireless                        | 7         | 0.43%   |
| VIA Technologies                       | 6         | 0.37%   |
| Samsung Electronics                    | 6         | 0.37%   |
| ASUSTek Computer                       | 6         | 0.37%   |
| ASIX Electronics                       | 6         | 0.37%   |
| AMD                                    | 6         | 0.37%   |
| Qualcomm Atheros Communications        | 5         | 0.31%   |
| Dell                                   | 5         | 0.31%   |
| Motorola PCS                           | 4         | 0.25%   |
| Huawei Technologies                    | 4         | 0.25%   |
| Hewlett-Packard                        | 4         | 0.25%   |
| Edimax Technology                      | 4         | 0.25%   |
| NetGear                                | 3         | 0.18%   |
| MediaTek                               | 3         | 0.18%   |
| D-Link                                 | 3         | 0.18%   |
| Attansic Technology                    | 3         | 0.18%   |
| OPPO Electronics                       | 2         | 0.12%   |
| Micro Star International               | 2         | 0.12%   |
| DisplayLink                            | 2         | 0.12%   |
| Davicom Semiconductor                  | 2         | 0.12%   |
| ZyDAS                                  | 1         | 0.06%   |
| Toshiba                                | 1         | 0.06%   |
| T & A Mobile Phones                    | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Sitecom Europe                         | 1         | 0.06%   |
| Qcom                                   | 1         | 0.06%   |
| Lite-On Technology                     | 1         | 0.06%   |
| Linksys                                | 1         | 0.06%   |
| IMC Networks                           | 1         | 0.06%   |
| Ericsson Business Mobile Networks      | 1         | 0.06%   |
| D-Link System                          | 1         | 0.06%   |
| Belkin Components                      | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 224       | 11.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 159       | 8.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 64        | 3.29%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 44        | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 41        | 2.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 40        | 2.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 36        | 1.85%   |
| Intel Wireless 7260                                                     | 35        | 1.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 35        | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 34        | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 33        | 1.7%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 33        | 1.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 1.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 23        | 1.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 21        | 1.08%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 20        | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 1.03%   |
| Intel WiFi Link 5100                                                    | 19        | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 17        | 0.87%   |
| Intel Wireless 3165                                                     | 17        | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 17        | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                           | 17        | 0.87%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 17        | 0.87%   |
| Intel Wireless 8265 / 8275                                              | 16        | 0.82%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 15        | 0.77%   |
| Intel Wireless 7265                                                     | 14        | 0.72%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 14        | 0.72%   |
| Intel Ethernet Connection I218-LM                                       | 13        | 0.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 13        | 0.67%   |
| Broadcom BCM4401-B0 100Base-TX                                          | 13        | 0.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 12        | 0.62%   |
| Intel Wireless 3160                                                     | 12        | 0.62%   |
| Intel Ethernet Connection I217-LM                                       | 12        | 0.62%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 11        | 0.57%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 11        | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 11        | 0.57%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.57%   |
| Intel 82567LM Gigabit Network Connection                                | 11        | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 0.51%   |
| Intel Centrino Wireless-N 2230                                          | 10        | 0.51%   |
| Intel 82577LM Gigabit Network Connection                                | 10        | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 9         | 0.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 9         | 0.46%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 9         | 0.46%   |
| Intel 82566MM Gigabit Network Connection                                | 9         | 0.46%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 9         | 0.46%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 9         | 0.46%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 9         | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 8         | 0.41%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 8         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 8         | 0.41%   |
| Intel Wireless 8260                                                     | 8         | 0.41%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 0.41%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 8         | 0.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 0.41%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                         | 8         | 0.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 7         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 319       | 31.37%  |
| Qualcomm Atheros                | 253       | 24.88%  |
| Realtek Semiconductor           | 177       | 17.4%   |
| Broadcom                        | 137       | 13.47%  |
| Broadcom Limited                | 46        | 4.52%   |
| Ralink                          | 21        | 2.06%   |
| TP-Link                         | 10        | 0.98%   |
| Ralink Technology               | 9         | 0.88%   |
| Sierra Wireless                 | 7         | 0.69%   |
| ASUSTek Computer                | 6         | 0.59%   |
| Qualcomm Atheros Communications | 5         | 0.49%   |
| Edimax Technology               | 4         | 0.39%   |
| NetGear                         | 3         | 0.29%   |
| D-Link                          | 3         | 0.29%   |
| Micro Star International        | 2         | 0.2%    |
| MediaTek                        | 2         | 0.2%    |
| Hewlett-Packard                 | 2         | 0.2%    |
| Dell                            | 2         | 0.2%    |
| ZyDAS                           | 1         | 0.1%    |
| Xiaomi                          | 1         | 0.1%    |
| Sitecom Europe                  | 1         | 0.1%    |
| Qcom                            | 1         | 0.1%    |
| Lite-On Technology              | 1         | 0.1%    |
| Linksys                         | 1         | 0.1%    |
| IMC Networks                    | 1         | 0.1%    |
| D-Link System                   | 1         | 0.1%    |
| Belkin Components               | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 64        | 6.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 44        | 4.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 41        | 4%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 40        | 3.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 36        | 3.51%   |
| Intel Wireless 7260                                                           | 35        | 3.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 35        | 3.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 33        | 3.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 33        | 3.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 27        | 2.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 24        | 2.34%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 21        | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 20        | 1.95%   |
| Intel WiFi Link 5100                                                          | 19        | 1.85%   |
| Intel Wireless 3165                                                           | 17        | 1.66%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 17        | 1.66%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 17        | 1.66%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 17        | 1.66%   |
| Intel Wireless 8265 / 8275                                                    | 16        | 1.56%   |
| Intel Wireless 7265                                                           | 14        | 1.37%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 14        | 1.37%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 13        | 1.27%   |
| Intel Wireless 3160                                                           | 12        | 1.17%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 11        | 1.07%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 11        | 1.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 11        | 1.07%   |
| Intel Centrino Ultimate-N 6300                                                | 11        | 1.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 10        | 0.98%   |
| Intel Centrino Wireless-N 2230                                                | 10        | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 9         | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 9         | 0.88%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 9         | 0.88%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller           | 9         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 8         | 0.78%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 8         | 0.78%   |
| Intel Wireless 8260                                                           | 8         | 0.78%   |
| Intel Wi-Fi 6 AX200                                                           | 8         | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 8         | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 8         | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 7         | 0.68%   |
| Ralink MT7601U Wireless Adapter                                               | 7         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 7         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 7         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 7         | 0.68%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller   | 7         | 0.68%   |
| Intel Centrino Advanced-N 6235                                                | 6         | 0.59%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 6         | 0.59%   |
| Realtek 802.11ac NIC                                                          | 5         | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                               | 5         | 0.49%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 5         | 0.49%   |
| Intel Centrino Advanced-N 6200                                                | 5         | 0.49%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 5         | 0.49%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 4         | 0.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 4         | 0.39%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 4         | 0.39%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 4         | 0.39%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 4         | 0.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 4         | 0.39%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 4         | 0.39%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                    | 4         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 420       | 47.67%  |
| Intel                                  | 149       | 16.91%  |
| Qualcomm Atheros                       | 82        | 9.31%   |
| Broadcom                               | 73        | 8.29%   |
| Marvell Technology Group               | 42        | 4.77%   |
| Silicon Integrated Systems [SiS]       | 22        | 2.5%    |
| Nvidia                                 | 20        | 2.27%   |
| Broadcom Limited                       | 17        | 1.93%   |
| JMicron Technology                     | 12        | 1.36%   |
| Xiaomi                                 | 6         | 0.68%   |
| VIA Technologies                       | 6         | 0.68%   |
| Samsung Electronics                    | 6         | 0.68%   |
| ASIX Electronics                       | 6         | 0.68%   |
| Motorola PCS                           | 4         | 0.45%   |
| Huawei Technologies                    | 3         | 0.34%   |
| Attansic Technology                    | 3         | 0.34%   |
| OPPO Electronics                       | 2         | 0.23%   |
| DisplayLink                            | 2         | 0.23%   |
| Davicom Semiconductor                  | 2         | 0.23%   |
| TP-Link                                | 1         | 0.11%   |
| T & A Mobile Phones                    | 1         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.11%   |
| MediaTek                               | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 224       | 25.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 159       | 18.01%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 34        | 3.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 23        | 2.6%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 20        | 2.27%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 17        | 1.93%   |
| Intel Ethernet Connection I218-LM                                              | 13        | 1.47%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 13        | 1.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 12        | 1.36%   |
| Intel Ethernet Connection I217-LM                                              | 12        | 1.36%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 11        | 1.25%   |
| Intel 82567LM Gigabit Network Connection                                       | 11        | 1.25%   |
| Intel 82577LM Gigabit Network Connection                                       | 10        | 1.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 1.02%   |
| Intel 82566MM Gigabit Network Connection                                       | 9         | 1.02%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 9         | 1.02%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 9         | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 0.91%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 8         | 0.91%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 7         | 0.79%   |
| Nvidia MCP67 Ethernet                                                          | 7         | 0.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 7         | 0.79%   |
| Intel Ethernet Connection I219-LM                                              | 7         | 0.79%   |
| Intel 82579V Gigabit Network Connection                                        | 7         | 0.79%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 6         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.68%   |
| Nvidia MCP79 Ethernet                                                          | 6         | 0.68%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 6         | 0.68%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 6         | 0.68%   |
| Intel PRO/100 VE Network Connection                                            | 6         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                          | 6         | 0.68%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 6         | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 5         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 5         | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 5         | 0.57%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile           | 5         | 0.57%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 5         | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 5         | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 4         | 0.45%   |
| Nvidia MCP77 Ethernet                                                          | 4         | 0.45%   |
| Motorola PCS moto g(9) play                                                    | 4         | 0.45%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 4         | 0.45%   |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 0.45%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 4         | 0.45%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 4         | 0.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 4         | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3         | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.34%   |
| Nvidia MCP51 Ethernet Controller                                               | 3         | 0.34%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 3         | 0.34%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 3         | 0.34%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                           | 3         | 0.34%   |
| Intel WiMAX Connection 2400m                                                   | 3         | 0.34%   |
| Huawei LYA-L09                                                                 | 3         | 0.34%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 3         | 0.34%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                       | 3         | 0.34%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 3         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 931       | 51.13%  |
| Ethernet | 854       | 46.9%   |
| Modem    | 36        | 1.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 762       | 76.58%  |
| Ethernet | 233       | 23.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 799       | 83.4%   |
| 1     | 125       | 13.05%  |
| 0     | 31        | 3.24%   |
| 3     | 3         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 891       | 92.14%  |
| Yes  | 76        | 7.86%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 145       | 26.65%  |
| Qualcomm Atheros Communications | 75        | 13.79%  |
| Realtek Semiconductor           | 62        | 11.4%   |
| Broadcom                        | 59        | 10.85%  |
| Dell                            | 31        | 5.7%    |
| Hewlett-Packard                 | 29        | 5.33%   |
| Lite-On Technology              | 25        | 4.6%    |
| Foxconn / Hon Hai               | 19        | 3.49%   |
| IMC Networks                    | 16        | 2.94%   |
| Apple                           | 14        | 2.57%   |
| Toshiba                         | 11        | 2.02%   |
| Cambridge Silicon Radio         | 9         | 1.65%   |
| Alps Electric                   | 8         | 1.47%   |
| Realtek                         | 7         | 1.29%   |
| Ralink                          | 7         | 1.29%   |
| ASUSTek Computer                | 7         | 1.29%   |
| Foxconn International           | 5         | 0.92%   |
| Taiyo Yuden                     | 3         | 0.55%   |
| Ralink Technology               | 3         | 0.55%   |
| Dynex                           | 3         | 0.55%   |
| Askey Computer                  | 2         | 0.37%   |
| TP-Link                         | 1         | 0.18%   |
| Qcom                            | 1         | 0.18%   |
| MediaTek                        | 1         | 0.18%   |
| Chicony Electronics             | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 95        | 17.43%  |
| Realtek Bluetooth Radio                                                             | 37        | 6.79%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 35        | 6.42%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 23        | 4.22%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 17        | 3.12%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 14        | 2.57%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 14        | 2.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 13        | 2.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 11        | 2.02%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 10        | 1.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 9         | 1.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 1.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 9         | 1.65%   |
| Broadcom BCM2045 Bluetooth                                                          | 9         | 1.65%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 8         | 1.47%   |
| Intel Bluetooth Device                                                              | 8         | 1.47%   |
| Intel AX200 Bluetooth                                                               | 8         | 1.47%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 1.47%   |
| Realtek Bluetooth Radio                                                             | 7         | 1.28%   |
| Ralink RT3290 Bluetooth                                                             | 7         | 1.28%   |
| Dell Wireless 365 Bluetooth                                                         | 7         | 1.28%   |
| Apple Bluetooth Host Controller                                                     | 7         | 1.28%   |
| Dell DW375 Bluetooth Module                                                         | 6         | 1.1%    |
| IMC Networks Bluetooth Radio                                                        | 5         | 0.92%   |
| IMC Networks Bluetooth Device                                                       | 5         | 0.92%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 5         | 0.92%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.92%   |
| Dell Wireless 350 Bluetooth                                                         | 5         | 0.92%   |
| Broadcom BCM20702A0                                                                 | 5         | 0.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 5         | 0.92%   |
| Toshiba Bluetooth Device                                                            | 4         | 0.73%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 4         | 0.73%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.73%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 0.73%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 4         | 0.73%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 4         | 0.73%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 0.73%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 4         | 0.73%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 0.73%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 4         | 0.73%   |
| Intel AX201 Bluetooth                                                               | 3         | 0.55%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]                                       | 3         | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 0.55%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 3         | 0.55%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 3         | 0.55%   |
| Dell Wireless 360 Bluetooth                                                         | 3         | 0.55%   |
| Broadcom BCM2046 Bluetooth Device                                                   | 3         | 0.55%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 3         | 0.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 0.55%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 0.55%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 3         | 0.55%   |
| Toshiba Integrated Bluetooth HCI                                                    | 2         | 0.37%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 2         | 0.37%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.37%   |
| Ralink CSR BS8510                                                                   | 2         | 0.37%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.37%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.37%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 2         | 0.37%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.37%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 2         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 736       | 70.91%  |
| AMD                              | 162       | 15.61%  |
| Nvidia                           | 87        | 8.38%   |
| Silicon Integrated Systems [SiS] | 23        | 2.22%   |
| VIA Technologies                 | 7         | 0.67%   |
| C-Media Electronics              | 5         | 0.48%   |
| Tenx Technology                  | 3         | 0.29%   |
| Creative Technology              | 3         | 0.29%   |
| Yamaha                           | 2         | 0.19%   |
| Texas Instruments                | 2         | 0.19%   |
| Generalplus Technology           | 2         | 0.19%   |
| ZOOM                             | 1         | 0.1%    |
| Syntek                           | 1         | 0.1%    |
| OPPO Electronics                 | 1         | 0.1%    |
| Logitech                         | 1         | 0.1%    |
| Hewlett-Packard                  | 1         | 0.1%    |
| AKAI Professional M.I.           | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 93        | 7.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 82        | 6.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 77        | 6.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 77        | 6.17%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 76        | 6.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 63        | 5.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 49        | 3.93%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 43        | 3.45%   |
| Intel 8 Series HD Audio Controller                                                                | 43        | 3.45%   |
| AMD FCH Azalia Controller                                                                         | 42        | 3.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 38        | 3.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 31        | 2.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 30        | 2.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 2.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 22        | 1.76%   |
| Intel Broadwell-U Audio Controller                                                                | 22        | 1.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 22        | 1.76%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 20        | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 19        | 1.52%   |
| AMD Wrestler HDMI Audio                                                                           | 19        | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 18        | 1.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 18        | 1.44%   |
| AMD High Definition Audio Controller                                                              | 17        | 1.36%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 15        | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 1.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 1.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 0.88%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 0.72%   |
| AMD Trinity HDMI Audio Controller                                                                 | 9         | 0.72%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 0.64%   |
| Nvidia MCP79 High Definition Audio                                                                | 7         | 0.56%   |
| Nvidia MCP67 High Definition Audio                                                                | 7         | 0.56%   |
| Nvidia High Definition Audio Controller                                                           | 7         | 0.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 0.56%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 6         | 0.48%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 6         | 0.48%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 0.4%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.4%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.4%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.4%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 5         | 0.4%    |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 5         | 0.4%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 4         | 0.32%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 4         | 0.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.32%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 4         | 0.32%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 4         | 0.32%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 3         | 0.24%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 3         | 0.24%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.24%   |
| Nvidia MCP89 High Definition Audio                                                                | 3         | 0.24%   |
| Nvidia MCP51 High Definition Audio                                                                | 3         | 0.24%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.24%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.24%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.24%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.24%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 3         | 0.24%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.24%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 55        | 26.96%  |
| Samsung Electronics | 41        | 20.1%   |
| Unknown             | 33        | 16.18%  |
| Kingston            | 18        | 8.82%   |
| Micron Technology   | 16        | 7.84%   |
| Nanya Technology    | 9         | 4.41%   |
| Ramaxel Technology  | 5         | 2.45%   |
| Elpida              | 5         | 2.45%   |
| Smart               | 3         | 1.47%   |
| Unknown (ABCD)      | 2         | 0.98%   |
| Qimonda             | 2         | 0.98%   |
| High Bridge         | 2         | 0.98%   |
| A-DATA Technology   | 2         | 0.98%   |
| Walton Chaintech    | 1         | 0.49%   |
| Transcend           | 1         | 0.49%   |
| Toshiba             | 1         | 0.49%   |
| Team                | 1         | 0.49%   |
| Smart Brazil        | 1         | 0.49%   |
| SHARETRONIC         | 1         | 0.49%   |
| Nayna               | 1         | 0.49%   |
| HBS                 | 1         | 0.49%   |
| COS Memory          | 1         | 0.49%   |
| Corsair             | 1         | 0.49%   |
| Avant               | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 2.68%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 5         | 2.23%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 1.79%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 3         | 1.34%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 3         | 1.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.34%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.34%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 2         | 0.89%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.89%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 2         | 0.89%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.89%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 2         | 0.89%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 2         | 0.89%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 2         | 0.89%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 0.89%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                    | 2         | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.89%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.89%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.89%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.89%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.89%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.89%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 2         | 0.89%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 2         | 0.89%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.89%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s         | 2         | 0.89%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.89%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s             | 2         | 0.89%   |
| Walton Chaintech RAM AS2G833-13GH905 2048MB SODIMM DDR2          | 1         | 0.45%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 0.45%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.45%   |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                     | 1         | 0.45%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                       | 1         | 0.45%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.45%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DRAM                               | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 256MB SODIMM DRAM 400MT/s                     | 1         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.45%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.45%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.45%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.45%   |
| Unknown RAM Module 1GB SODIMM 400MT/s                            | 1         | 0.45%   |
| Unknown RAM Module 1GB DIMM DRAM                                 | 1         | 0.45%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 0.45%   |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 1024MB SODIMM DRAM 400MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.45%   |
| Unknown RAM ICF 2GB SODIMM DDR2                                  | 1         | 0.45%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s           | 1         | 0.45%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 0.45%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 75        | 42.37%  |
| DDR2    | 43        | 24.29%  |
| DDR4    | 30        | 16.95%  |
| SDRAM   | 13        | 7.34%   |
| DRAM    | 5         | 2.82%   |
| DDR     | 4         | 2.26%   |
| LPDDR4  | 3         | 1.69%   |
| LPDDR3  | 2         | 1.13%   |
| Unknown | 2         | 1.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 159       | 94.08%  |
| Row Of Chips | 5         | 2.96%   |
| DIMM         | 4         | 2.37%   |
| Chip         | 1         | 0.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 66        | 32.67%  |
| 4096  | 61        | 30.2%   |
| 8192  | 32        | 15.84%  |
| 1024  | 28        | 13.86%  |
| 512   | 9         | 4.46%   |
| 16384 | 4         | 1.98%   |
| 256   | 2         | 0.99%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 47        | 24.35%  |
| 2667    | 21        | 10.88%  |
| 667     | 20        | 10.36%  |
| Unknown | 16        | 8.29%   |
| 1334    | 15        | 7.77%   |
| 1333    | 10        | 5.18%   |
| 2133    | 9         | 4.66%   |
| 1066    | 8         | 4.15%   |
| 533     | 8         | 4.15%   |
| 4199    | 7         | 3.63%   |
| 975     | 7         | 3.63%   |
| 2400    | 6         | 3.11%   |
| 800     | 6         | 3.11%   |
| 2048    | 3         | 1.55%   |
| 400     | 3         | 1.55%   |
| 3266    | 2         | 1.04%   |
| 1067    | 2         | 1.04%   |
| 3733    | 1         | 0.52%   |
| 3200    | 1         | 0.52%   |
| 1639    | 1         | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 5         | 41.67%  |
| Canon              | 3         | 25%     |
| Brother Industries | 2         | 16.67%  |
| STMicroelectronics | 1         | 8.33%   |
| Seiko Epson        | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 8.33%   |
| Seiko Epson WF-2010 Series                                | 1         | 8.33%   |
| HP Laserjet P1505                                         | 1         | 8.33%   |
| HP LaserJet 1020                                          | 1         | 8.33%   |
| HP DeskJet 2700 series                                    | 1         | 8.33%   |
| HP Deskjet 1510                                           | 1         | 8.33%   |
| HP DeskJet 1110 series                                    | 1         | 8.33%   |
| Canon PIXMA MX340                                         | 1         | 8.33%   |
| Canon PIXMA MG3600 Series                                 | 1         | 8.33%   |
| Canon MG2100 series                                       | 1         | 8.33%   |
| Brother MFC-L2730DW series                                | 1         | 8.33%   |
| Brother DCP-T300                                          | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 199       | 27.99%  |
| Microdia                               | 70        | 9.85%   |
| Suyin                                  | 53        | 7.45%   |
| Realtek Semiconductor                  | 52        | 7.31%   |
| Acer                                   | 49        | 6.89%   |
| IMC Networks                           | 45        | 6.33%   |
| Sunplus Innovation Technology          | 36        | 5.06%   |
| Cheng Uei Precision Industry (Foxlink) | 27        | 3.8%    |
| Silicon Motion                         | 24        | 3.38%   |
| Quanta                                 | 18        | 2.53%   |
| Apple                                  | 16        | 2.25%   |
| Lite-On Technology                     | 15        | 2.11%   |
| Alcor Micro                            | 15        | 2.11%   |
| Syntek                                 | 13        | 1.83%   |
| Ricoh                                  | 12        | 1.69%   |
| Importek                               | 11        | 1.55%   |
| ALi                                    | 9         | 1.27%   |
| Z-Star Microelectronics                | 7         | 0.98%   |
| Samsung Electronics                    | 5         | 0.7%    |
| OmniVision Technologies                | 5         | 0.7%    |
| Logitech                               | 4         | 0.56%   |
| GEMBIRD                                | 4         | 0.56%   |
| Lenovo                                 | 3         | 0.42%   |
| Primax Electronics                     | 2         | 0.28%   |
| Luxvisions Innotech Limited            | 2         | 0.28%   |
| Genesys Logic                          | 2         | 0.28%   |
| YGTek                                  | 1         | 0.14%   |
| Trust                                  | 1         | 0.14%   |
| Sunplus Technology                     | 1         | 0.14%   |
| Microsoft                              | 1         | 0.14%   |
| LG Electronics                         | 1         | 0.14%   |
| Intel                                  | 1         | 0.14%   |
| Huawei Technologies                    | 1         | 0.14%   |
| Generalplus Technology                 | 1         | 0.14%   |
| Foxconn / Hon Hai                      | 1         | 0.14%   |
| eMPIA Technology                       | 1         | 0.14%   |
| Elecom                                 | 1         | 0.14%   |
| Creative Technology                    | 1         | 0.14%   |
| Camera                                 | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 17        | 2.39%   |
| Acer Lenovo EasyCamera                                         | 12        | 1.69%   |
| Realtek Integrated_Webcam_HD                                   | 11        | 1.54%   |
| Chicony USB 2.0 Camera                                         | 11        | 1.54%   |
| Microdia Integrated Webcam                                     | 10        | 1.4%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 10        | 1.4%    |
| Chicony EasyCamera                                             | 10        | 1.4%    |
| Microdia Sonix USB 2.0 Camera                                  | 9         | 1.26%   |
| Chicony HP Truevision HD camera                                | 9         | 1.26%   |
| Chicony HP Truevision HD                                       | 9         | 1.26%   |
| Suyin HP Truevision HD                                         | 8         | 1.12%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 8         | 1.12%   |
| Sunplus Integrated_Webcam_HD                                   | 8         | 1.12%   |
| Realtek Integrated Webcam                                      | 8         | 1.12%   |
| Chicony Lenovo EasyCamera                                      | 8         | 1.12%   |
| Chicony HP HD Webcam                                           | 8         | 1.12%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 7         | 0.98%   |
| Chicony VGA WebCam                                             | 7         | 0.98%   |
| Chicony TOSHIBA Web Camera - HD                                | 7         | 0.98%   |
| Chicony HP Webcam                                              | 7         | 0.98%   |
| ALi Gateway Webcam                                             | 7         | 0.98%   |
| Quanta HP Webcam                                               | 6         | 0.84%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 6         | 0.84%   |
| Microdia Integrated_Webcam_HD                                  | 6         | 0.84%   |
| Lite-On Integrated Camera                                      | 6         | 0.84%   |
| Chicony HD WebCam                                              | 6         | 0.84%   |
| Chicony CNF9055 Toshiba Webcam                                 | 6         | 0.84%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 6         | 0.84%   |
| Sunplus HP HD Webcam [Fixed]                                   | 5         | 0.7%    |
| Sunplus HD WebCam                                              | 5         | 0.7%    |
| Silicon Motion Web Camera                                      | 5         | 0.7%    |
| Samsung Galaxy A5 (MTP)                                        | 5         | 0.7%    |
| Chicony USB2.0 VGA UVC WebCam                                  | 5         | 0.7%    |
| Chicony USB2.0 HD UVC WebCam                                   | 5         | 0.7%    |
| Chicony HP Wide Vision HD Camera                               | 5         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 5         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 5         | 0.7%    |
| Alcor Micro USB 2.0 PC cam                                     | 5         | 0.7%    |
| Z-Star Webcam                                                  | 4         | 0.56%   |
| Syntek EasyCamera                                              | 4         | 0.56%   |
| Suyin Acer CrystalEye Webcam                                   | 4         | 0.56%   |
| Silicon Motion WebCam SCB-0355N                                | 4         | 0.56%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 4         | 0.56%   |
| Realtek USB2.0 HD UVC WebCam                                   | 4         | 0.56%   |
| Realtek HP Webcam-101                                          | 4         | 0.56%   |
| Quanta HP TrueVision HD Camera                                 | 4         | 0.56%   |
| Quanta HD Webcam                                               | 4         | 0.56%   |
| OmniVision OV2640 Webcam                                       | 4         | 0.56%   |
| Microdia Laptop_Integrated_Webcam_E4HD                         | 4         | 0.56%   |
| Microdia Integrated_Webcam_1.3M                                | 4         | 0.56%   |
| Importek TOSHIBA Web Camera - HD                               | 4         | 0.56%   |
| IMC Networks ov9734_azurewave_camera                           | 4         | 0.56%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]              | 4         | 0.56%   |
| Chicony USB2.0 UVC WebCam                                      | 4         | 0.56%   |
| Chicony Integrated HP HD Webcam                                | 4         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 4         | 0.56%   |
| Apple FaceTime Camera                                          | 4         | 0.56%   |
| Alcor Micro HP Webcam-101                                      | 4         | 0.56%   |
| Acer Lenovo Integrated Webcam                                  | 4         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 68        | 54.4%   |
| AuthenTec                  | 25        | 20%     |
| STMicroelectronics         | 9         | 7.2%    |
| Upek                       | 8         | 6.4%    |
| Shenzhen Goodix Technology | 6         | 4.8%    |
| Elan Microelectronics      | 5         | 4%      |
| Synaptics                  | 3         | 2.4%    |
| LighTuning Technology      | 1         | 0.8%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 12%     |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 8%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 8%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 7.2%    |
| STMicroelectronics Fingerprint Reader                                      | 9         | 7.2%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 7.2%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 6.4%    |
| Validity Sensors Fingerprint scanner                                       | 6         | 4.8%    |
| Validity Sensors VFS491                                                    | 5         | 4%      |
| AuthenTec AES2810                                                          | 5         | 4%      |
| AuthenTec AES1600                                                          | 5         | 4%      |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 3.2%    |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 3.2%    |
| Elan ELAN:Fingerprint                                                      | 4         | 3.2%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 2.4%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 2.4%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.6%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.6%    |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.6%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.8%    |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.8%    |
| Synaptics  WBDI                                                            | 1         | 0.8%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.8%    |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.8%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.8%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.8%    |
| Elan ELAN:ARM-M4                                                           | 1         | 0.8%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.8%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 24        | 46.15%  |
| O2 Micro              | 12        | 23.08%  |
| Alcor Micro           | 9         | 17.31%  |
| Lenovo                | 3         | 5.77%   |
| Upek                  | 2         | 3.85%   |
| SCM Microsystems      | 1         | 1.92%   |
| Realtek Semiconductor | 1         | 1.92%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 28.85%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 17.31%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 15.38%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 9.62%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 7.69%   |
| Broadcom 5880                                                                | 4         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 5.77%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.85%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.92%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.92%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 609       | 62.59%  |
| 1     | 293       | 30.11%  |
| 2     | 64        | 6.58%   |
| 3     | 5         | 0.51%   |
| 7     | 1         | 0.1%    |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 124       | 29.04%  |
| Graphics card            | 99        | 23.19%  |
| Net/wireless             | 68        | 15.93%  |
| Chipcard                 | 51        | 11.94%  |
| Modem                    | 20        | 4.68%   |
| Storage                  | 15        | 3.51%   |
| Bluetooth                | 10        | 2.34%   |
| Sound                    | 8         | 1.87%   |
| Flash memory             | 8         | 1.87%   |
| Multimedia controller    | 6         | 1.41%   |
| Camera                   | 6         | 1.41%   |
| Communication controller | 5         | 1.17%   |
| Net/ethernet             | 3         | 0.7%    |
| Card reader              | 2         | 0.47%   |
| Storage/ata              | 1         | 0.23%   |
| Network                  | 1         | 0.23%   |

