Pop!_OS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 7641

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Alpha 15 A3DDK              | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| HP            | EliteBook 8760w             | [d061b57b29](https://linux-hardware.org/?probe=d061b57b29) | Sep 07, 2023 |
| Alienware     | m15 R7                      | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| Apple         | MacBookPro11,3              | [bfdd099826](https://linux-hardware.org/?probe=bfdd099826) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | [611bb4fe1a](https://linux-hardware.org/?probe=611bb4fe1a) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | [38f9d1abd9](https://linux-hardware.org/?probe=38f9d1abd9) | Sep 05, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Dell          | Inspiron 14 5420            | [70d0d79f77](https://linux-hardware.org/?probe=70d0d79f77) | Sep 05, 2023 |
| Apple         | MacBookPro10,1              | [11c016fb1b](https://linux-hardware.org/?probe=11c016fb1b) | Sep 05, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ee1a881e82](https://linux-hardware.org/?probe=ee1a881e82) | Sep 04, 2023 |
| System76      | Lemur Pro                   | [9ea11da090](https://linux-hardware.org/?probe=9ea11da090) | Sep 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [68e90ee0cb](https://linux-hardware.org/?probe=68e90ee0cb) | Sep 04, 2023 |
| ASUSTek       | K53E                        | [5604fe515d](https://linux-hardware.org/?probe=5604fe515d) | Sep 04, 2023 |
| Dell          | XPS 17 9700                 | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2ddf0c5c61](https://linux-hardware.org/?probe=2ddf0c5c61) | Sep 03, 2023 |
| HP            | 240 G8 Notebook PC          | [092ae0b34d](https://linux-hardware.org/?probe=092ae0b34d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [f2f5e496f1](https://linux-hardware.org/?probe=f2f5e496f1) | Sep 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [515e1f4bce](https://linux-hardware.org/?probe=515e1f4bce) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Schenker      | VIA 15 Pro                  | [4a31ab4d2b](https://linux-hardware.org/?probe=4a31ab4d2b) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| ASUSTek       | N550JV                      | [b2effdc956](https://linux-hardware.org/?probe=b2effdc956) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| Acer          | Swift SFX14-41G             | [67f553625a](https://linux-hardware.org/?probe=67f553625a) | Sep 01, 2023 |
| Dell          | Latitude E7470              | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [1213d3bf46](https://linux-hardware.org/?probe=1213d3bf46) | Aug 31, 2023 |
| Acer          | Aspire E5-551G              | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [3b890e064f](https://linux-hardware.org/?probe=3b890e064f) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| Google        | Kefka                       | [284517c2b3](https://linux-hardware.org/?probe=284517c2b3) | Aug 31, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [5f995c7c48](https://linux-hardware.org/?probe=5f995c7c48) | Aug 30, 2023 |
| Apple         | MacBookPro5,5               | [641243c308](https://linux-hardware.org/?probe=641243c308) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Google        | Kefka                       | [a018ae3fb5](https://linux-hardware.org/?probe=a018ae3fb5) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [90a72df8ef](https://linux-hardware.org/?probe=90a72df8ef) | Aug 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [4904c007c7](https://linux-hardware.org/?probe=4904c007c7) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | [481b37b0fc](https://linux-hardware.org/?probe=481b37b0fc) | Aug 29, 2023 |
| Dell          | Latitude 5330               | [7e63575d10](https://linux-hardware.org/?probe=7e63575d10) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [2f669d797f](https://linux-hardware.org/?probe=2f669d797f) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [39f2feeed5](https://linux-hardware.org/?probe=39f2feeed5) | Aug 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | [de65d63e10](https://linux-hardware.org/?probe=de65d63e10) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | [dc9a79314c](https://linux-hardware.org/?probe=dc9a79314c) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | [ef97f75590](https://linux-hardware.org/?probe=ef97f75590) | Aug 28, 2023 |
| Dell          | Precision 5510              | [c6d08d9c28](https://linux-hardware.org/?probe=c6d08d9c28) | Aug 27, 2023 |
| HP            | EliteBook 865 16 inch G9... | [b07775a194](https://linux-hardware.org/?probe=b07775a194) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Precision M4600             | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Apple         | MacBookPro8,2               | [9e0b5b0b7e](https://linux-hardware.org/?probe=9e0b5b0b7e) | Aug 26, 2023 |
| Dell          | Precision M6800             | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| HP            | ProBook 4730s               | [32f610b810](https://linux-hardware.org/?probe=32f610b810) | Aug 26, 2023 |
| Google        | Kasumi                      | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| System76      | Gazelle                     | [b3fb438915](https://linux-hardware.org/?probe=b3fb438915) | Aug 25, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | [34fc2a5f83](https://linux-hardware.org/?probe=34fc2a5f83) | Aug 24, 2023 |
| Dell          | Latitude E7240              | [cb61859037](https://linux-hardware.org/?probe=cb61859037) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| Dell          | Latitude 7430               | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| Toshiba       | Satellite L655              | [18df557333](https://linux-hardware.org/?probe=18df557333) | Aug 24, 2023 |
| HP            | Pavilion Notebook           | [b0ca2ee250](https://linux-hardware.org/?probe=b0ca2ee250) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| Dell          | XPS 13 9310                 | [6f0e38b5e8](https://linux-hardware.org/?probe=6f0e38b5e8) | Aug 23, 2023 |
| Samsung       | 750TDA                      | [7b1ec96afa](https://linux-hardware.org/?probe=7b1ec96afa) | Aug 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [4cd19df49e](https://linux-hardware.org/?probe=4cd19df49e) | Aug 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2RV0... | [e8d2c8e1d5](https://linux-hardware.org/?probe=e8d2c8e1d5) | Aug 22, 2023 |
| System76      | Darter Pro                  | [a244cb8283](https://linux-hardware.org/?probe=a244cb8283) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [fdd24243bf](https://linux-hardware.org/?probe=fdd24243bf) | Aug 22, 2023 |
| Acer          | Aspire A715-75G             | [54794fb9e8](https://linux-hardware.org/?probe=54794fb9e8) | Aug 22, 2023 |
| HP            | ProBook 4730s               | [5b4d88bc67](https://linux-hardware.org/?probe=5b4d88bc67) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | [930d312c36](https://linux-hardware.org/?probe=930d312c36) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | [2bc8c24081](https://linux-hardware.org/?probe=2bc8c24081) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b66d308d42](https://linux-hardware.org/?probe=b66d308d42) | Aug 21, 2023 |
| MSI           | Modern 15 A5M               | [f9742049fc](https://linux-hardware.org/?probe=f9742049fc) | Aug 20, 2023 |
| System76      | Oryx Pro                    | [b7e0bd11e5](https://linux-hardware.org/?probe=b7e0bd11e5) | Aug 20, 2023 |
| Dell          | Precision 5520              | [42587aac96](https://linux-hardware.org/?probe=42587aac96) | Aug 20, 2023 |
| Dell          | Precision 5520              | [bec735d800](https://linux-hardware.org/?probe=bec735d800) | Aug 20, 2023 |
| System76      | Kudu Pro                    | [0fc481c5fc](https://linux-hardware.org/?probe=0fc481c5fc) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR    | [5d063a6e59](https://linux-hardware.org/?probe=5d063a6e59) | Aug 19, 2023 |
| Lenovo        | B490 377224P                | [0e516ea22b](https://linux-hardware.org/?probe=0e516ea22b) | Aug 19, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [a1ab007f7f](https://linux-hardware.org/?probe=a1ab007f7f) | Aug 18, 2023 |
| ASUSTek       | U38N                        | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| HP            | EliteBook 850 G3            | [a6a7224d63](https://linux-hardware.org/?probe=a6a7224d63) | Aug 17, 2023 |
| Dell          | XPS 13 9310                 | [680fae2274](https://linux-hardware.org/?probe=680fae2274) | Aug 17, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [43fd1aad67](https://linux-hardware.org/?probe=43fd1aad67) | Aug 17, 2023 |
| System76      | Lemur Pro                   | [af3b387574](https://linux-hardware.org/?probe=af3b387574) | Aug 16, 2023 |
| Acer          | Aspire 5750                 | [ec4afb1917](https://linux-hardware.org/?probe=ec4afb1917) | Aug 16, 2023 |
| A-DATA Tec... | XENIA 14                    | [59faf4a458](https://linux-hardware.org/?probe=59faf4a458) | Aug 15, 2023 |
| A-DATA Tec... | XENIA 14                    | [537cce8a8e](https://linux-hardware.org/?probe=537cce8a8e) | Aug 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c2cfa9bd7a](https://linux-hardware.org/?probe=c2cfa9bd7a) | Aug 15, 2023 |
| Apple         | MacBookAir6,2               | [431ac1b880](https://linux-hardware.org/?probe=431ac1b880) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| System76      | Galago Pro                  | [54348f9c55](https://linux-hardware.org/?probe=54348f9c55) | Aug 14, 2023 |
| Apple         | MacBookPro9,2               | [61ff7ac5f1](https://linux-hardware.org/?probe=61ff7ac5f1) | Aug 14, 2023 |
| Apple         | MacBookPro16,1              | [18b513f5f0](https://linux-hardware.org/?probe=18b513f5f0) | Aug 14, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [1f27d0f994](https://linux-hardware.org/?probe=1f27d0f994) | Aug 14, 2023 |
| HP            | ProBook 4540s               | [84dbf6b759](https://linux-hardware.org/?probe=84dbf6b759) | Aug 13, 2023 |
| Dell          | Inspiron 3542               | [ae586a02aa](https://linux-hardware.org/?probe=ae586a02aa) | Aug 13, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [823e276406](https://linux-hardware.org/?probe=823e276406) | Aug 13, 2023 |
| GPU Compan... | GWNR71517                   | [a38cee5cc9](https://linux-hardware.org/?probe=a38cee5cc9) | Aug 12, 2023 |
| Acer          | Aspire ES1-520              | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | [6ac135c81c](https://linux-hardware.org/?probe=6ac135c81c) | Aug 12, 2023 |
| ASUSTek       | K53TK                       | [db9f130ade](https://linux-hardware.org/?probe=db9f130ade) | Aug 12, 2023 |
| Dell          | G7 7588                     | [48faf46c2c](https://linux-hardware.org/?probe=48faf46c2c) | Aug 12, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |
| HP            | EliteBook 820 G3            | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [0d45e9e048](https://linux-hardware.org/?probe=0d45e9e048) | Aug 12, 2023 |
| Dell          | Precision M4600             | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [361e073b5c](https://linux-hardware.org/?probe=361e073b5c) | Aug 11, 2023 |
| Acer          | Nitro AN715-51              | [ea972c8686](https://linux-hardware.org/?probe=ea972c8686) | Aug 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e22f71b79d](https://linux-hardware.org/?probe=e22f71b79d) | Aug 11, 2023 |
| ASUSTek       | X751LD                      | [e98d8d116d](https://linux-hardware.org/?probe=e98d8d116d) | Aug 10, 2023 |
| Apple         | MacBookAir5,2               | [7f91d6f9d8](https://linux-hardware.org/?probe=7f91d6f9d8) | Aug 10, 2023 |
| Acer          | Nitro AN517-55              | [b77ff095f8](https://linux-hardware.org/?probe=b77ff095f8) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 4330s               | [5c854bed9f](https://linux-hardware.org/?probe=5c854bed9f) | Aug 09, 2023 |
| HP            | ProBook 4330s               | [d23ce497d2](https://linux-hardware.org/?probe=d23ce497d2) | Aug 09, 2023 |
| System76      | Darter Pro                  | [5162d61c01](https://linux-hardware.org/?probe=5162d61c01) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | [b041192310](https://linux-hardware.org/?probe=b041192310) | Aug 09, 2023 |
| Alienware     | 14                          | [192b13997d](https://linux-hardware.org/?probe=192b13997d) | Aug 09, 2023 |
| HP            | Victus by 15.6 inch Gami... | [67f88ab571](https://linux-hardware.org/?probe=67f88ab571) | Aug 08, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [afa081b440](https://linux-hardware.org/?probe=afa081b440) | Aug 08, 2023 |
| Acer          | Ferrari One 200             | [be688aa584](https://linux-hardware.org/?probe=be688aa584) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | [00b169d241](https://linux-hardware.org/?probe=00b169d241) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ec7a911951](https://linux-hardware.org/?probe=ec7a911951) | Aug 08, 2023 |
| Apple         | MacBookPro11,3              | [c415fd317b](https://linux-hardware.org/?probe=c415fd317b) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | [5e0c7f7bfc](https://linux-hardware.org/?probe=5e0c7f7bfc) | Aug 08, 2023 |
| Acer          | Aspire A715-75G             | [57f1225daf](https://linux-hardware.org/?probe=57f1225daf) | Aug 08, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [088a8fad47](https://linux-hardware.org/?probe=088a8fad47) | Aug 08, 2023 |
| System76      | Oryx Pro                    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| MSI           | Cyborg 15 A12VF             | [5fe9a17769](https://linux-hardware.org/?probe=5fe9a17769) | Aug 07, 2023 |
| MSI           | GP72 7RDX                   | [43eb53850c](https://linux-hardware.org/?probe=43eb53850c) | Aug 06, 2023 |
| Clevo         | W150HRM                     | [1ddcfcbecc](https://linux-hardware.org/?probe=1ddcfcbecc) | Aug 06, 2023 |
| Apple         | MacBookPro9,2               | [16936ef482](https://linux-hardware.org/?probe=16936ef482) | Aug 06, 2023 |
| MSI           | GP72 7RDX                   | [6d2bc8aa9e](https://linux-hardware.org/?probe=6d2bc8aa9e) | Aug 06, 2023 |
| Timi          | RedmiBook Pro 15S           | [576241bbd4](https://linux-hardware.org/?probe=576241bbd4) | Aug 06, 2023 |
| Notebook      | 1745                        | [3561a5dbbe](https://linux-hardware.org/?probe=3561a5dbbe) | Aug 06, 2023 |
| HP            | Pavilion dm4                | [521b8518ed](https://linux-hardware.org/?probe=521b8518ed) | Aug 06, 2023 |
| Dell          | Latitude 5430               | [f63444b0be](https://linux-hardware.org/?probe=f63444b0be) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | [a4a6f81455](https://linux-hardware.org/?probe=a4a6f81455) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | [ef010c9d51](https://linux-hardware.org/?probe=ef010c9d51) | Aug 05, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [7d17fc9ff6](https://linux-hardware.org/?probe=7d17fc9ff6) | Aug 05, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [0147060507](https://linux-hardware.org/?probe=0147060507) | Aug 04, 2023 |
| HP            | ProBook 650 G1              | [286cc8b0dd](https://linux-hardware.org/?probe=286cc8b0dd) | Aug 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS0GY0R    | [4d618e08b3](https://linux-hardware.org/?probe=4d618e08b3) | Aug 03, 2023 |
| System76      | Bonobo WS                   | [64ba21a272](https://linux-hardware.org/?probe=64ba21a272) | Aug 03, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | [a97312771e](https://linux-hardware.org/?probe=a97312771e) | Aug 03, 2023 |
| Dell          | XPS 13 9370                 | [cf49ff3004](https://linux-hardware.org/?probe=cf49ff3004) | Aug 03, 2023 |
| Dell          | Latitude E7240              | [ec5ec88e59](https://linux-hardware.org/?probe=ec5ec88e59) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [99ccd043cb](https://linux-hardware.org/?probe=99ccd043cb) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d4e267a214](https://linux-hardware.org/?probe=d4e267a214) | Aug 02, 2023 |
| HP            | ProBook 650 G4              | [d041df173b](https://linux-hardware.org/?probe=d041df173b) | Aug 02, 2023 |
| Apple         | MacBookPro11,3              | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | [0a3c5e5c4d](https://linux-hardware.org/?probe=0a3c5e5c4d) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | [9f852ea211](https://linux-hardware.org/?probe=9f852ea211) | Aug 02, 2023 |
| ASUSTek       | GL502VSK                    | [0ed7feaa05](https://linux-hardware.org/?probe=0ed7feaa05) | Aug 01, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [e1a79e094e](https://linux-hardware.org/?probe=e1a79e094e) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | [d252fa93be](https://linux-hardware.org/?probe=d252fa93be) | Aug 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3500               | [df5211a816](https://linux-hardware.org/?probe=df5211a816) | Aug 01, 2023 |
| Dell          | Latitude 5490               | [e24a9f877c](https://linux-hardware.org/?probe=e24a9f877c) | Aug 01, 2023 |
| System76      | Lemur Pro                   | [1ba844bc69](https://linux-hardware.org/?probe=1ba844bc69) | Aug 01, 2023 |
| System76      | Lemur Pro                   | [e019d33faf](https://linux-hardware.org/?probe=e019d33faf) | Aug 01, 2023 |
| MSI           | Katana GF66 12UC            | [d590bcd619](https://linux-hardware.org/?probe=d590bcd619) | Jul 31, 2023 |
| ASUSTek       | K95VM                       | [1ec08c4cf9](https://linux-hardware.org/?probe=1ec08c4cf9) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| Dell          | Latitude E7440              | [7509a5f756](https://linux-hardware.org/?probe=7509a5f756) | Jul 30, 2023 |
| System76      | Darter Pro                  | [0220d19f38](https://linux-hardware.org/?probe=0220d19f38) | Jul 30, 2023 |
| Dell          | Latitude E7240              | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| HP            | Pavilion 11 x360 PC         | [d693783e7a](https://linux-hardware.org/?probe=d693783e7a) | Jul 29, 2023 |
| Unknown       | Unknown                     | [73836c0a75](https://linux-hardware.org/?probe=73836c0a75) | Jul 29, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [59f0eb6b57](https://linux-hardware.org/?probe=59f0eb6b57) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [cb2f78abf0](https://linux-hardware.org/?probe=cb2f78abf0) | Jul 28, 2023 |
| Dell          | Precision 3550              | [0ecac77f90](https://linux-hardware.org/?probe=0ecac77f90) | Jul 28, 2023 |
| Dell          | Precision 3550              | [95ae018833](https://linux-hardware.org/?probe=95ae018833) | Jul 28, 2023 |
| System76      | Oryx Pro                    | [0ad8c1d8a7](https://linux-hardware.org/?probe=0ad8c1d8a7) | Jul 28, 2023 |
| Acer          | Aspire A315-42G             | [0e3aa83494](https://linux-hardware.org/?probe=0e3aa83494) | Jul 28, 2023 |
| HP            | EliteBook 840 G3            | [5a1f6f3395](https://linux-hardware.org/?probe=5a1f6f3395) | Jul 27, 2023 |
| Dell          | G15 5520                    | [7a5b503737](https://linux-hardware.org/?probe=7a5b503737) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4152e1f98e](https://linux-hardware.org/?probe=4152e1f98e) | Jul 27, 2023 |
| Dell          | Latitude E7440              | [619c6e4b99](https://linux-hardware.org/?probe=619c6e4b99) | Jul 27, 2023 |
| Samsung       | 300E5M/300E5L               | [23b23d59aa](https://linux-hardware.org/?probe=23b23d59aa) | Jul 27, 2023 |
| HP            | Dev One Notebook PC         | [b54bb52258](https://linux-hardware.org/?probe=b54bb52258) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [9920824f1f](https://linux-hardware.org/?probe=9920824f1f) | Jul 27, 2023 |
| Acer          | Nitro AN515-55              | [00e9bb8973](https://linux-hardware.org/?probe=00e9bb8973) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [22b2519a90](https://linux-hardware.org/?probe=22b2519a90) | Jul 26, 2023 |
| Acer          | Aspire A515-56              | [7e0e30c1cf](https://linux-hardware.org/?probe=7e0e30c1cf) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [b583a1fbee](https://linux-hardware.org/?probe=b583a1fbee) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [3d3696e8fa](https://linux-hardware.org/?probe=3d3696e8fa) | Jul 25, 2023 |
| HP            | Laptop 14-bs0xx             | [e074ee90be](https://linux-hardware.org/?probe=e074ee90be) | Jul 25, 2023 |
| MSI           | GF63 Thin 10SCXR            | [b34b7fa5fb](https://linux-hardware.org/?probe=b34b7fa5fb) | Jul 25, 2023 |
| Dell          | Inspiron 5490               | [25f155c61a](https://linux-hardware.org/?probe=25f155c61a) | Jul 24, 2023 |
| Dell          | Inspiron 5490               | [6b80b41fee](https://linux-hardware.org/?probe=6b80b41fee) | Jul 24, 2023 |
| Dell          | XPS 15 7590                 | [fa64a82283](https://linux-hardware.org/?probe=fa64a82283) | Jul 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [88cfdb061d](https://linux-hardware.org/?probe=88cfdb061d) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [61c84247e6](https://linux-hardware.org/?probe=61c84247e6) | Jul 24, 2023 |
| Apple         | MacBookAir4,2               | [e220379405](https://linux-hardware.org/?probe=e220379405) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [53bab7ac5e](https://linux-hardware.org/?probe=53bab7ac5e) | Jul 24, 2023 |
| Apple         | MacBookPro5,5               | [b2b0895194](https://linux-hardware.org/?probe=b2b0895194) | Jul 24, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [3d8ec4447b](https://linux-hardware.org/?probe=3d8ec4447b) | Jul 24, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [fe2ff0c21f](https://linux-hardware.org/?probe=fe2ff0c21f) | Jul 23, 2023 |
| Apple         | MacBookPro8,1               | [2cd0946aba](https://linux-hardware.org/?probe=2cd0946aba) | Jul 23, 2023 |
| Sony          | SVF1521A6EW                 | [3c39100c6f](https://linux-hardware.org/?probe=3c39100c6f) | Jul 23, 2023 |
| PC Special... | Standard                    | [992aec5bb8](https://linux-hardware.org/?probe=992aec5bb8) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Google        | Snappy                      | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Dell          | Latitude 3500               | [0755576e96](https://linux-hardware.org/?probe=0755576e96) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| Dell          | Vostro 3560                 | [05acc63d53](https://linux-hardware.org/?probe=05acc63d53) | Jul 22, 2023 |
| Dell          | Latitude 5410               | [82217114b4](https://linux-hardware.org/?probe=82217114b4) | Jul 21, 2023 |
| Dell          | Latitude 5520               | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| LG Electro... | S425-G.BC31P1               | [2f54821f3f](https://linux-hardware.org/?probe=2f54821f3f) | Jul 21, 2023 |
| Dell          | Precision 7530              | [0d2e753768](https://linux-hardware.org/?probe=0d2e753768) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | [243f0a8cab](https://linux-hardware.org/?probe=243f0a8cab) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | [f310abe0bb](https://linux-hardware.org/?probe=f310abe0bb) | Jul 20, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Dell          | Latitude E5270              | [9ea13fdc27](https://linux-hardware.org/?probe=9ea13fdc27) | Jul 20, 2023 |
| HP            | Laptop 15-da0xxx            | [6e17b916ee](https://linux-hardware.org/?probe=6e17b916ee) | Jul 20, 2023 |
| Acer          | Extensa 5635ZG              | [337f0cec05](https://linux-hardware.org/?probe=337f0cec05) | Jul 20, 2023 |
| Toshiba       | Satellite L750              | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| Dell          | XPS 13 9360                 | [ac1a8eea0e](https://linux-hardware.org/?probe=ac1a8eea0e) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [35944db669](https://linux-hardware.org/?probe=35944db669) | Jul 19, 2023 |
| Schenker      | XMG NEO (CML/E20)           | [9f99e57705](https://linux-hardware.org/?probe=9f99e57705) | Jul 19, 2023 |
| ASUSTek       | K53E                        | [7fddec038e](https://linux-hardware.org/?probe=7fddec038e) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [8cb16d19aa](https://linux-hardware.org/?probe=8cb16d19aa) | Jul 19, 2023 |
| Notebook      | NH5x_7xDPx                  | [098f2f58c7](https://linux-hardware.org/?probe=098f2f58c7) | Jul 18, 2023 |
| Apple         | MacBookPro16,1              | [dd5d384a71](https://linux-hardware.org/?probe=dd5d384a71) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [f5dc246f7c](https://linux-hardware.org/?probe=f5dc246f7c) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [abec03689c](https://linux-hardware.org/?probe=abec03689c) | Jul 18, 2023 |
| ASRock        | Z77 Performance             | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1cffa4bad9](https://linux-hardware.org/?probe=1cffa4bad9) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [cdaad6fa25](https://linux-hardware.org/?probe=cdaad6fa25) | Jul 18, 2023 |
| HP            | 635                         | [500e11147e](https://linux-hardware.org/?probe=500e11147e) | Jul 18, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1426cda0a7](https://linux-hardware.org/?probe=1426cda0a7) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c7a062709f](https://linux-hardware.org/?probe=c7a062709f) | Jul 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [86f515ebce](https://linux-hardware.org/?probe=86f515ebce) | Jul 17, 2023 |
| HUAWEI        | KLVC-WXX9                   | [0427f16143](https://linux-hardware.org/?probe=0427f16143) | Jul 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [0bbd5c68bb](https://linux-hardware.org/?probe=0bbd5c68bb) | Jul 17, 2023 |
| Dell          | Precision M6800             | [8ddd80db6c](https://linux-hardware.org/?probe=8ddd80db6c) | Jul 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4abe81669a](https://linux-hardware.org/?probe=4abe81669a) | Jul 17, 2023 |
| Lenovo        | ThinkPad X390 20Q1S67S00    | [be43004463](https://linux-hardware.org/?probe=be43004463) | Jul 17, 2023 |
| System76      | Serval WS                   | [a916a92726](https://linux-hardware.org/?probe=a916a92726) | Jul 17, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [55a5100039](https://linux-hardware.org/?probe=55a5100039) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [ad8f031cb2](https://linux-hardware.org/?probe=ad8f031cb2) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [51128412d5](https://linux-hardware.org/?probe=51128412d5) | Jul 16, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [437209972c](https://linux-hardware.org/?probe=437209972c) | Jul 15, 2023 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [91dbb2c969](https://linux-hardware.org/?probe=91dbb2c969) | Jul 15, 2023 |
| Dell          | G15 5510                    | [28b7a732f2](https://linux-hardware.org/?probe=28b7a732f2) | Jul 15, 2023 |
| System76      | Pangolin                    | [486df7ead2](https://linux-hardware.org/?probe=486df7ead2) | Jul 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0498e27f41](https://linux-hardware.org/?probe=0498e27f41) | Jul 14, 2023 |
| HP            | ENVY 15                     | [5cfb9d33bd](https://linux-hardware.org/?probe=5cfb9d33bd) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [21fc63e4dd](https://linux-hardware.org/?probe=21fc63e4dd) | Jul 14, 2023 |
| MSI           | GF63 Thin 10SC              | [d017610254](https://linux-hardware.org/?probe=d017610254) | Jul 14, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [e53c63af42](https://linux-hardware.org/?probe=e53c63af42) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | [fb022ada73](https://linux-hardware.org/?probe=fb022ada73) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e84bf83ac1](https://linux-hardware.org/?probe=e84bf83ac1) | Jul 13, 2023 |
| HP            | Compaq CQ58                 | [78977dd4de](https://linux-hardware.org/?probe=78977dd4de) | Jul 13, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire E5-576G              | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | [c82bb58705](https://linux-hardware.org/?probe=c82bb58705) | Jul 13, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | [5a675551df](https://linux-hardware.org/?probe=5a675551df) | Jul 13, 2023 |
| Dell          | G3 3590                     | [089bfa3da7](https://linux-hardware.org/?probe=089bfa3da7) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | [d4910e3f43](https://linux-hardware.org/?probe=d4910e3f43) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | [7a9624e7cc](https://linux-hardware.org/?probe=7a9624e7cc) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [618c0c975b](https://linux-hardware.org/?probe=618c0c975b) | Jul 12, 2023 |
| HP            | Laptop 17-cp0xxx            | [801537f1d4](https://linux-hardware.org/?probe=801537f1d4) | Jul 12, 2023 |
| Apple         | MacBookPro6,2               | [20e2180dc1](https://linux-hardware.org/?probe=20e2180dc1) | Jul 12, 2023 |
| MSI           | Cyborg 15 A12VF             | [2c4a8d9d63](https://linux-hardware.org/?probe=2c4a8d9d63) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| Apple         | MacBookAir3,2               | [cbfc272e87](https://linux-hardware.org/?probe=cbfc272e87) | Jul 11, 2023 |
| HP            | EliteBook 850 G6            | [556ef4473f](https://linux-hardware.org/?probe=556ef4473f) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | [a61e80c022](https://linux-hardware.org/?probe=a61e80c022) | Jul 11, 2023 |
| Apple         | MacBookAir7,2               | [1453f984c9](https://linux-hardware.org/?probe=1453f984c9) | Jul 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [5a7dbc5d7c](https://linux-hardware.org/?probe=5a7dbc5d7c) | Jul 10, 2023 |
| Apple         | MacBookPro6,2               | [293ddc3253](https://linux-hardware.org/?probe=293ddc3253) | Jul 10, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| Notebook      | P7xxTM1                     | [81c163ed4a](https://linux-hardware.org/?probe=81c163ed4a) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| Toshiba       | IS 1413G                    | [cf96aafbc0](https://linux-hardware.org/?probe=cf96aafbc0) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | [1f88a40c05](https://linux-hardware.org/?probe=1f88a40c05) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | [e1f22afb69](https://linux-hardware.org/?probe=e1f22afb69) | Jul 08, 2023 |
| MSI           | Cyborg 15 A12VF             | [a34d0d8290](https://linux-hardware.org/?probe=a34d0d8290) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| Acer          | Nitro AN515-57              | [12e3f9ecc7](https://linux-hardware.org/?probe=12e3f9ecc7) | Jul 07, 2023 |
| ASUSTek       | N55SL                       | [1223d8b536](https://linux-hardware.org/?probe=1223d8b536) | Jul 07, 2023 |
| MSI           | GS66 Stealth 10SE           | [e689bf355c](https://linux-hardware.org/?probe=e689bf355c) | Jul 07, 2023 |
| Panasonic     | FZ55-1                      | [4d12f02737](https://linux-hardware.org/?probe=4d12f02737) | Jul 07, 2023 |
| Dell          | Inspiron 3501               | [e657049abf](https://linux-hardware.org/?probe=e657049abf) | Jul 06, 2023 |
| Toshiba       | IS 1413G                    | [f2a99b72dc](https://linux-hardware.org/?probe=f2a99b72dc) | Jul 06, 2023 |
| Acer          | Predator PT515-51           | [9971e8a3da](https://linux-hardware.org/?probe=9971e8a3da) | Jul 05, 2023 |
| HP            | Laptop 15-da0xxx            | [f634e3942a](https://linux-hardware.org/?probe=f634e3942a) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [46e6f4b081](https://linux-hardware.org/?probe=46e6f4b081) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [6bf093ef61](https://linux-hardware.org/?probe=6bf093ef61) | Jul 05, 2023 |
| Dell          | XPS 17 9720                 | [a99946b8f0](https://linux-hardware.org/?probe=a99946b8f0) | Jul 04, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [09dffdde54](https://linux-hardware.org/?probe=09dffdde54) | Jul 04, 2023 |
| MSI           | Cyborg 15 A12VF             | [156f923a72](https://linux-hardware.org/?probe=156f923a72) | Jul 04, 2023 |
| Acer          | Aspire E1-470G              | [db4125a1c5](https://linux-hardware.org/?probe=db4125a1c5) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [dda9b242fd](https://linux-hardware.org/?probe=dda9b242fd) | Jul 03, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [e8ff92b585](https://linux-hardware.org/?probe=e8ff92b585) | Jul 03, 2023 |
| Acer          | Aspire A515-52              | [3861c91dd4](https://linux-hardware.org/?probe=3861c91dd4) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | [ab8898b9f3](https://linux-hardware.org/?probe=ab8898b9f3) | Jul 02, 2023 |
| Apple         | MacBookPro12,1              | [f89bdd4374](https://linux-hardware.org/?probe=f89bdd4374) | Jul 02, 2023 |
| Dell          | Precision 7510              | [46b90e25b0](https://linux-hardware.org/?probe=46b90e25b0) | Jul 02, 2023 |
| MSI           | GT72VR 6RD                  | [ea6887d031](https://linux-hardware.org/?probe=ea6887d031) | Jul 01, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6ee8b4e949](https://linux-hardware.org/?probe=6ee8b4e949) | Jul 01, 2023 |
| Dell          | Latitude 3500               | [8293ebc591](https://linux-hardware.org/?probe=8293ebc591) | Jul 01, 2023 |
| Toshiba       | IS 1413G                    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| Teclast       | F7 Plus                     | [cebd3b027c](https://linux-hardware.org/?probe=cebd3b027c) | Jun 30, 2023 |
| Dell          | XPS 13 9370                 | [ec4bf131f5](https://linux-hardware.org/?probe=ec4bf131f5) | Jun 30, 2023 |
| Positivo      | Mobile                      | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | [568380fd59](https://linux-hardware.org/?probe=568380fd59) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | [54013b2dfd](https://linux-hardware.org/?probe=54013b2dfd) | Jun 30, 2023 |
| Positivo      | H14CU02                     | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| MSI           | Vector GP76 12UH            | [b7035d78a6](https://linux-hardware.org/?probe=b7035d78a6) | Jun 29, 2023 |
| MSI           | GE70 2PL                    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| Acer          | Aspire A315-21              | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Acer          | Aspire E1-571               | [894f8583ea](https://linux-hardware.org/?probe=894f8583ea) | Jun 27, 2023 |
| Dell          | Vostro 15 3510              | [adb3a3de68](https://linux-hardware.org/?probe=adb3a3de68) | Jun 27, 2023 |
| Dell          | Precision M6800             | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Toshiba       | IS 1413G                    | [882bd512a2](https://linux-hardware.org/?probe=882bd512a2) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Dell          | Inspiron 3583               | [e1e76b3d77](https://linux-hardware.org/?probe=e1e76b3d77) | Jun 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | [5454a08ba6](https://linux-hardware.org/?probe=5454a08ba6) | Jun 26, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| Apple         | MacBookAir6,1               | [6b44c8513d](https://linux-hardware.org/?probe=6b44c8513d) | Jun 26, 2023 |
| Dell          | Precision M6800             | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| HP            | Notebook                    | [ea00ce6c5b](https://linux-hardware.org/?probe=ea00ce6c5b) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [b9a835920f](https://linux-hardware.org/?probe=b9a835920f) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [c462c4c75e](https://linux-hardware.org/?probe=c462c4c75e) | Jun 25, 2023 |
| HP            | ENVY NOTEBOOK PC            | [8bd62ffdf1](https://linux-hardware.org/?probe=8bd62ffdf1) | Jun 25, 2023 |
| Acer          | Swift SF314-512             | [12f361cd8c](https://linux-hardware.org/?probe=12f361cd8c) | Jun 24, 2023 |
| System76      | Oryx Pro                    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [737204f453](https://linux-hardware.org/?probe=737204f453) | Jun 24, 2023 |
| MSI           | Cyborg 15 A12VF             | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | [e8db86e014](https://linux-hardware.org/?probe=e8db86e014) | Jun 22, 2023 |
| ASUSTek       | X551MA                      | [5b2b7d4a7f](https://linux-hardware.org/?probe=5b2b7d4a7f) | Jun 22, 2023 |
| Dell          | Inspiron 3583               | [170d1f4f0b](https://linux-hardware.org/?probe=170d1f4f0b) | Jun 22, 2023 |
| HP            | Notebook                    | [35b8a2a187](https://linux-hardware.org/?probe=35b8a2a187) | Jun 22, 2023 |
| Lenovo        | B5400 80B6QB0               | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| Dell          | Inspiron 5567               | [8634954b1c](https://linux-hardware.org/?probe=8634954b1c) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [ebaceedccf](https://linux-hardware.org/?probe=ebaceedccf) | Jun 21, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [a168f45822](https://linux-hardware.org/?probe=a168f45822) | Jun 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [b255195205](https://linux-hardware.org/?probe=b255195205) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | IS 1413G                    | [14296e98e7](https://linux-hardware.org/?probe=14296e98e7) | Jun 21, 2023 |
| Dell          | Latitude E7240              | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | [383aed9129](https://linux-hardware.org/?probe=383aed9129) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | [3996492e80](https://linux-hardware.org/?probe=3996492e80) | Jun 20, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| System76      | Lemur Pro                   | [5074769fee](https://linux-hardware.org/?probe=5074769fee) | Jun 19, 2023 |
| Dell          | Latitude 7430               | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | [347c5ce944](https://linux-hardware.org/?probe=347c5ce944) | Jun 19, 2023 |
| HP            | Laptop 15-dy2xxx            | [0699537327](https://linux-hardware.org/?probe=0699537327) | Jun 19, 2023 |
| MSI           | Raider GE66 12UGS           | [73b20b76a3](https://linux-hardware.org/?probe=73b20b76a3) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Acer          | Aspire 5750G                | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [ae0a1a134a](https://linux-hardware.org/?probe=ae0a1a134a) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| Avell High... | A70 HYB                     | [10eb079da8](https://linux-hardware.org/?probe=10eb079da8) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [cf08c655b9](https://linux-hardware.org/?probe=cf08c655b9) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [272d8de237](https://linux-hardware.org/?probe=272d8de237) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | Pavilion dv6                | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| System76      | Gazelle                     | [79c4236cdd](https://linux-hardware.org/?probe=79c4236cdd) | Jun 15, 2023 |
| HP            | Laptop 14-dk0xxx            | [1e6fdd560b](https://linux-hardware.org/?probe=1e6fdd560b) | Jun 14, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | [667f0a20c1](https://linux-hardware.org/?probe=667f0a20c1) | Jun 14, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| System76      | Gazelle                     | [117f199b15](https://linux-hardware.org/?probe=117f199b15) | Jun 14, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [d7c90a9c25](https://linux-hardware.org/?probe=d7c90a9c25) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Dell          | Vostro 5470                 | [b5294ee338](https://linux-hardware.org/?probe=b5294ee338) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [fff5e11f1c](https://linux-hardware.org/?probe=fff5e11f1c) | Jun 13, 2023 |
| TUXEDO        | Unknown                     | [d730799661](https://linux-hardware.org/?probe=d730799661) | Jun 12, 2023 |
| Dell          | Latitude E7470              | [1253de4554](https://linux-hardware.org/?probe=1253de4554) | Jun 12, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [c09c4a0f69](https://linux-hardware.org/?probe=c09c4a0f69) | Jun 12, 2023 |
| Toshiba       | Satellite P55t-B            | [efc0f87778](https://linux-hardware.org/?probe=efc0f87778) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [fd388e00c3](https://linux-hardware.org/?probe=fd388e00c3) | Jun 10, 2023 |
| Samsung       | 550XCJ/550XCR               | [d8dac01c79](https://linux-hardware.org/?probe=d8dac01c79) | Jun 10, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | [4160d59c4f](https://linux-hardware.org/?probe=4160d59c4f) | Jun 10, 2023 |
| Acer          | Aspire 7750                 | [b0daafa057](https://linux-hardware.org/?probe=b0daafa057) | Jun 09, 2023 |
| ASUSTek       | UX32LN                      | [97ff235920](https://linux-hardware.org/?probe=97ff235920) | Jun 08, 2023 |
| Dell          | Latitude E7240              | [e21cc2151b](https://linux-hardware.org/?probe=e21cc2151b) | Jun 08, 2023 |
| Dell          | Latitude E6420              | [d408418ddd](https://linux-hardware.org/?probe=d408418ddd) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | [975246674d](https://linux-hardware.org/?probe=975246674d) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | [348173e172](https://linux-hardware.org/?probe=348173e172) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| HP            | Pavilion dv7                | [896e71aaaf](https://linux-hardware.org/?probe=896e71aaaf) | Jun 08, 2023 |
| Machcreato... | 14                          | [d889b02b13](https://linux-hardware.org/?probe=d889b02b13) | Jun 07, 2023 |
| Toshiba       | IS 1413G                    | [cc023db7a9](https://linux-hardware.org/?probe=cc023db7a9) | Jun 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| Dell          | Latitude E6420              | [620ca905d2](https://linux-hardware.org/?probe=620ca905d2) | Jun 07, 2023 |
| Machcreato... | 14                          | [f0a27a9f97](https://linux-hardware.org/?probe=f0a27a9f97) | Jun 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | [2834fee64f](https://linux-hardware.org/?probe=2834fee64f) | Jun 06, 2023 |
| HP            | Laptop 14-cf2xxx            | [e6bf4ead0a](https://linux-hardware.org/?probe=e6bf4ead0a) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Apple         | MacBookAir4,2               | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| Apple         | MacBook5,1                  | [804abce033](https://linux-hardware.org/?probe=804abce033) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| HP            | 15 Notebook PC              | [7c76016c9d](https://linux-hardware.org/?probe=7c76016c9d) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | [5dd18339de](https://linux-hardware.org/?probe=5dd18339de) | Jun 05, 2023 |
| Dell          | Inspiron 5437               | [d805b4ec1f](https://linux-hardware.org/?probe=d805b4ec1f) | Jun 03, 2023 |
| Dell          | Inspiron 7472               | [53b9d0dfa6](https://linux-hardware.org/?probe=53b9d0dfa6) | Jun 03, 2023 |
| Apple         | MacBookPro9,2               | [6964a1da79](https://linux-hardware.org/?probe=6964a1da79) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| System76      | Oryx Pro                    | [b3b398ba61](https://linux-hardware.org/?probe=b3b398ba61) | Jun 03, 2023 |
| MSI           | Prestige 16 A12UD           | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| Acer          | Predator PH517-51           | [1de529b11c](https://linux-hardware.org/?probe=1de529b11c) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| System76      | Adder WS                    | [5cfa553a01](https://linux-hardware.org/?probe=5cfa553a01) | May 31, 2023 |
| Toshiba       | IS 1413G                    | [d950f8b732](https://linux-hardware.org/?probe=d950f8b732) | May 31, 2023 |
| Acer          | Predator PH517-51           | [cc24e32ab1](https://linux-hardware.org/?probe=cc24e32ab1) | May 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [907448944d](https://linux-hardware.org/?probe=907448944d) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [83f869ee2a](https://linux-hardware.org/?probe=83f869ee2a) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [23af21bb34](https://linux-hardware.org/?probe=23af21bb34) | May 30, 2023 |
| Toshiba       | Satellite P755              | [5dc8f46db5](https://linux-hardware.org/?probe=5dc8f46db5) | May 29, 2023 |
| Avell High... | A70 MOB                     | [70e4c12911](https://linux-hardware.org/?probe=70e4c12911) | May 29, 2023 |
| Dell          | XPS 15 9510                 | [bcad978a06](https://linux-hardware.org/?probe=bcad978a06) | May 29, 2023 |
| Dell          | XPS 15 9510                 | [331bbabc0e](https://linux-hardware.org/?probe=331bbabc0e) | May 29, 2023 |
| Apple         | MacBookAir5,1               | [4fc496bcc4](https://linux-hardware.org/?probe=4fc496bcc4) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| System76      | Adder WS                    | [d6de84e0c6](https://linux-hardware.org/?probe=d6de84e0c6) | May 28, 2023 |
| System76      | Adder WS                    | [5624c5b0e8](https://linux-hardware.org/?probe=5624c5b0e8) | May 28, 2023 |
| System76      | Adder WS                    | [2522fb534f](https://linux-hardware.org/?probe=2522fb534f) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| Lenovo        | Yoga 700-11ISK 80QE         | [149dfccfe7](https://linux-hardware.org/?probe=149dfccfe7) | May 27, 2023 |
| Google        | Kohaku                      | [2b46417afd](https://linux-hardware.org/?probe=2b46417afd) | May 27, 2023 |
| Dell          | Inspiron 7520               | [07b70ac9e5](https://linux-hardware.org/?probe=07b70ac9e5) | May 27, 2023 |
| System76      | Galago Pro                  | [51cc594a01](https://linux-hardware.org/?probe=51cc594a01) | May 27, 2023 |
| Apple         | MacBookPro15,1              | [8d5c73bd4d](https://linux-hardware.org/?probe=8d5c73bd4d) | May 27, 2023 |
| Dell          | XPS 15 9570                 | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| ASUSTek       | X555LN                      | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| Dell          | XPS 15 9570                 | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | ZBook 17 G6                 | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [a12e26f683](https://linux-hardware.org/?probe=a12e26f683) | May 26, 2023 |
| Dell          | Inspiron 7520               | [6d237fdf95](https://linux-hardware.org/?probe=6d237fdf95) | May 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| ASUSTek       | X502CA                      | [7b19816353](https://linux-hardware.org/?probe=7b19816353) | May 25, 2023 |
| MSI           | Alpha 15 A3DDK              | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [fcecd714d6](https://linux-hardware.org/?probe=fcecd714d6) | May 25, 2023 |
| Apple         | MacBookPro6,1               | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Lenovo        | IdeaPad Y560                | [a8b595f03c](https://linux-hardware.org/?probe=a8b595f03c) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| Dell          | Precision 5470              | [e0a145106b](https://linux-hardware.org/?probe=e0a145106b) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| Dell          | G15 5511                    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | [b7d26b3293](https://linux-hardware.org/?probe=b7d26b3293) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | [e3a554c09d](https://linux-hardware.org/?probe=e3a554c09d) | May 24, 2023 |
| Apple         | MacBookPro6,1               | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| HP            | Spectre Pro x360 G1         | [90df3b7bfa](https://linux-hardware.org/?probe=90df3b7bfa) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | [0f0ad128aa](https://linux-hardware.org/?probe=0f0ad128aa) | May 23, 2023 |
| Lenovo        | ThinkPad E595 20NFS0TH00    | [c843de4a39](https://linux-hardware.org/?probe=c843de4a39) | May 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | [da701ce37f](https://linux-hardware.org/?probe=da701ce37f) | May 23, 2023 |
| HP            | Laptop 14-dq0xxx            | [77ccb1431b](https://linux-hardware.org/?probe=77ccb1431b) | May 23, 2023 |
| Lenovo        | Unknown                     | [144302ab2c](https://linux-hardware.org/?probe=144302ab2c) | May 23, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| ASUSTek       | X550CC                      | [8226c82b49](https://linux-hardware.org/?probe=8226c82b49) | May 21, 2023 |
| ASUSTek       | X550CC                      | [6a8e6201be](https://linux-hardware.org/?probe=6a8e6201be) | May 21, 2023 |
| Lenovo        | Unknown                     | [1288108e10](https://linux-hardware.org/?probe=1288108e10) | May 21, 2023 |
| Lenovo        | ThinkPad T440p              | [b6c59c331b](https://linux-hardware.org/?probe=b6c59c331b) | May 21, 2023 |
| Apple         | MacBookPro5,3               | [0df526f042](https://linux-hardware.org/?probe=0df526f042) | May 21, 2023 |
| Dell          | G15 5511                    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| HP            | EliteBook 840 G5            | [399ea93745](https://linux-hardware.org/?probe=399ea93745) | May 21, 2023 |
| Toshiba       | Satellite L855D             | [5be0280c53](https://linux-hardware.org/?probe=5be0280c53) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [23fb35880e](https://linux-hardware.org/?probe=23fb35880e) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [d52da23326](https://linux-hardware.org/?probe=d52da23326) | May 21, 2023 |
| Acer          | Aspire E5-575               | [fb1832d859](https://linux-hardware.org/?probe=fb1832d859) | May 20, 2023 |
| Toshiba       | IS 1413G                    | [4c5dce3a01](https://linux-hardware.org/?probe=4c5dce3a01) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [51f87ac309](https://linux-hardware.org/?probe=51f87ac309) | May 20, 2023 |
| HP            | Pavilion dv6                | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2cde0cc93d](https://linux-hardware.org/?probe=2cde0cc93d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [d51c5680e8](https://linux-hardware.org/?probe=d51c5680e8) | May 19, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [08df098150](https://linux-hardware.org/?probe=08df098150) | May 18, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| Acer          | Swift SFX14-51G             | [644878287e](https://linux-hardware.org/?probe=644878287e) | May 18, 2023 |
| Reliance C... | R141TL5                     | [a21525c003](https://linux-hardware.org/?probe=a21525c003) | May 18, 2023 |
| Dell          | Inspiron 5559               | [620177b4fa](https://linux-hardware.org/?probe=620177b4fa) | May 17, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |
| Dell          | Inspiron 14 5408            | [c1853f7df2](https://linux-hardware.org/?probe=c1853f7df2) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [dd1e6376c2](https://linux-hardware.org/?probe=dd1e6376c2) | May 17, 2023 |
| Google        | Blorb                       | [7537bc5890](https://linux-hardware.org/?probe=7537bc5890) | May 17, 2023 |
| Apple         | MacBookAir7,2               | [add6bcd4f7](https://linux-hardware.org/?probe=add6bcd4f7) | May 16, 2023 |
| Apple         | MacBookAir7,2               | [2616bd6b98](https://linux-hardware.org/?probe=2616bd6b98) | May 16, 2023 |
| HP            | Pavilion dv6                | [fd5291d10e](https://linux-hardware.org/?probe=fd5291d10e) | May 15, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | [2192ceeebd](https://linux-hardware.org/?probe=2192ceeebd) | May 15, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a7c2953571](https://linux-hardware.org/?probe=a7c2953571) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [681e1f8c61](https://linux-hardware.org/?probe=681e1f8c61) | May 15, 2023 |
| ASUSTek       | X541UJ                      | [9be042ca8a](https://linux-hardware.org/?probe=9be042ca8a) | May 14, 2023 |
| Dell          | Inspiron 3583               | [3d3bfc28a6](https://linux-hardware.org/?probe=3d3bfc28a6) | May 14, 2023 |
| HP            | Victus by Gaming Laptop ... | [c74505560b](https://linux-hardware.org/?probe=c74505560b) | May 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [f67b1d428b](https://linux-hardware.org/?probe=f67b1d428b) | May 14, 2023 |
| Toshiba       | TECRA R850                  | [e48ff4432d](https://linux-hardware.org/?probe=e48ff4432d) | May 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [effc7c876e](https://linux-hardware.org/?probe=effc7c876e) | May 14, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [d26275a2de](https://linux-hardware.org/?probe=d26275a2de) | May 14, 2023 |
| System76      | Oryx Pro                    | [4b3677634e](https://linux-hardware.org/?probe=4b3677634e) | May 13, 2023 |
| HP            | Pavilion dv6                | [e20ba378ac](https://linux-hardware.org/?probe=e20ba378ac) | May 13, 2023 |
| Dell          | G7 7700                     | [6568ba5b4d](https://linux-hardware.org/?probe=6568ba5b4d) | May 13, 2023 |
| Gigabyte      | P34V7                       | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| System76      | Galago Pro                  | [a30efb5622](https://linux-hardware.org/?probe=a30efb5622) | May 13, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [9a5e07f865](https://linux-hardware.org/?probe=9a5e07f865) | May 13, 2023 |
| Dell          | Precision 3571              | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [69a20b9c03](https://linux-hardware.org/?probe=69a20b9c03) | May 13, 2023 |
| System76      | Gazelle                     | [bd4e912b20](https://linux-hardware.org/?probe=bd4e912b20) | May 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [7dd8e30770](https://linux-hardware.org/?probe=7dd8e30770) | May 12, 2023 |
| Lenovo        | ThinkPad T590 20N4002WGE    | [6caedd8a7b](https://linux-hardware.org/?probe=6caedd8a7b) | May 12, 2023 |
| ASUSTek       | ZenBook UX431FN             | [ee40bf2168](https://linux-hardware.org/?probe=ee40bf2168) | May 12, 2023 |
| System76      | Gazelle                     | [83ef9e6d2d](https://linux-hardware.org/?probe=83ef9e6d2d) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [729a4181de](https://linux-hardware.org/?probe=729a4181de) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3010c8760e](https://linux-hardware.org/?probe=3010c8760e) | May 12, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [f54531cd16](https://linux-hardware.org/?probe=f54531cd16) | May 11, 2023 |
| MSI           | Stealth 16Studio A13VG      | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a7155be531](https://linux-hardware.org/?probe=a7155be531) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [f46fe8b9ee](https://linux-hardware.org/?probe=f46fe8b9ee) | May 11, 2023 |
| Dell          | Inspiron 5566               | [e1e22ae448](https://linux-hardware.org/?probe=e1e22ae448) | May 10, 2023 |
| Acer          | Aspire VN7-591G             | [1fe1a8fcd2](https://linux-hardware.org/?probe=1fe1a8fcd2) | May 09, 2023 |
| MSI           | GL65 Leopard 10SCSR         | [4d9a7df494](https://linux-hardware.org/?probe=4d9a7df494) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [28e1a5c2e9](https://linux-hardware.org/?probe=28e1a5c2e9) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [fed7278850](https://linux-hardware.org/?probe=fed7278850) | May 09, 2023 |
| Lenovo        | ThinkPad T410 2522AA6       | [82755e3688](https://linux-hardware.org/?probe=82755e3688) | May 08, 2023 |
| Acer          | Aspire A715-72G             | [da1c6920b6](https://linux-hardware.org/?probe=da1c6920b6) | May 08, 2023 |
| Alienware     | Area-51m R2 A00             | [3cc417c9d9](https://linux-hardware.org/?probe=3cc417c9d9) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6bc581f37c](https://linux-hardware.org/?probe=6bc581f37c) | May 08, 2023 |
| HP            | Pavilion dv6                | [978d2165ac](https://linux-hardware.org/?probe=978d2165ac) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [e81eb02947](https://linux-hardware.org/?probe=e81eb02947) | May 07, 2023 |
| Notebook      | N141CU                      | [535b4ca746](https://linux-hardware.org/?probe=535b4ca746) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [619dc53d25](https://linux-hardware.org/?probe=619dc53d25) | May 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [078d3ae45f](https://linux-hardware.org/?probe=078d3ae45f) | May 06, 2023 |
| Notebook      | P15SM                       | [dcea4ec037](https://linux-hardware.org/?probe=dcea4ec037) | May 06, 2023 |
| Packard Be... | EasyNote LM85               | [d37b9e6687](https://linux-hardware.org/?probe=d37b9e6687) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9001HUS    | [4bad3ee37e](https://linux-hardware.org/?probe=4bad3ee37e) | May 06, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [fbe46d0c6e](https://linux-hardware.org/?probe=fbe46d0c6e) | May 05, 2023 |
| Dell          | XPS 15 9510                 | [fbd91068d3](https://linux-hardware.org/?probe=fbd91068d3) | May 05, 2023 |
| Positivo      | N4350                       | [ec0df546f9](https://linux-hardware.org/?probe=ec0df546f9) | May 05, 2023 |
| ASUSTek       | ZenBook UX431FN             | [3194ab7fa2](https://linux-hardware.org/?probe=3194ab7fa2) | May 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [eaf28f6af4](https://linux-hardware.org/?probe=eaf28f6af4) | May 05, 2023 |
| Toshiba       | TECRA R850                  | [bb41171733](https://linux-hardware.org/?probe=bb41171733) | May 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [5022c3993a](https://linux-hardware.org/?probe=5022c3993a) | May 04, 2023 |
| Dell          | Latitude 7370               | [6beab237df](https://linux-hardware.org/?probe=6beab237df) | May 04, 2023 |
| Dell          | XPS 15 9510                 | [2ab4f57ff6](https://linux-hardware.org/?probe=2ab4f57ff6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [0767486bb6](https://linux-hardware.org/?probe=0767486bb6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [3c6e20e260](https://linux-hardware.org/?probe=3c6e20e260) | May 04, 2023 |
| HP            | Unknown                     | [311e275897](https://linux-hardware.org/?probe=311e275897) | May 04, 2023 |
| MSI           | GV62 7RE                    | [1b048994c9](https://linux-hardware.org/?probe=1b048994c9) | May 04, 2023 |
| System76      | Oryx Pro                    | [cae9fadc38](https://linux-hardware.org/?probe=cae9fadc38) | May 04, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [a4a894bb7a](https://linux-hardware.org/?probe=a4a894bb7a) | May 03, 2023 |
| HP            | Unknown                     | [122c1783c0](https://linux-hardware.org/?probe=122c1783c0) | May 03, 2023 |
| American M... | XA133PR110                  | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6cb7429ec6](https://linux-hardware.org/?probe=6cb7429ec6) | May 02, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [9322206a7d](https://linux-hardware.org/?probe=9322206a7d) | May 02, 2023 |
| Toshiba       | PORTEGE Z30-A               | [ccc620956f](https://linux-hardware.org/?probe=ccc620956f) | May 02, 2023 |
| System76      | Oryx Pro                    | [8bd4f39eaa](https://linux-hardware.org/?probe=8bd4f39eaa) | May 02, 2023 |
| Lenovo        | ThinkPad W541 20EGS0B010    | [3f87bce0eb](https://linux-hardware.org/?probe=3f87bce0eb) | May 01, 2023 |
| System76      | Gazelle                     | [8a8de3e027](https://linux-hardware.org/?probe=8a8de3e027) | May 01, 2023 |
| HP            | EliteBook 830 G5            | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [3c82fea068](https://linux-hardware.org/?probe=3c82fea068) | May 01, 2023 |
| Dell          | Precision 5530              | [c8878b0f0f](https://linux-hardware.org/?probe=c8878b0f0f) | May 01, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | [34b877bcb5](https://linux-hardware.org/?probe=34b877bcb5) | May 01, 2023 |
| ASUSTek       | X455LJ                      | [4e252eab9f](https://linux-hardware.org/?probe=4e252eab9f) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [9df1b688c0](https://linux-hardware.org/?probe=9df1b688c0) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [875ae124a1](https://linux-hardware.org/?probe=875ae124a1) | Apr 30, 2023 |
| Dell          | Latitude E6430              | [4c20239367](https://linux-hardware.org/?probe=4c20239367) | Apr 30, 2023 |
| Apple         | MacBookPro11,3              | [3feeeb3341](https://linux-hardware.org/?probe=3feeeb3341) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | [8e0692ebe3](https://linux-hardware.org/?probe=8e0692ebe3) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [af0c1ea83c](https://linux-hardware.org/?probe=af0c1ea83c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7c8c5a4668](https://linux-hardware.org/?probe=7c8c5a4668) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9b560392f5](https://linux-hardware.org/?probe=9b560392f5) | Apr 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | [39644ab1d4](https://linux-hardware.org/?probe=39644ab1d4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [a2cbf65767](https://linux-hardware.org/?probe=a2cbf65767) | Apr 28, 2023 |
| HP            | ENVY 15                     | [d870c486c7](https://linux-hardware.org/?probe=d870c486c7) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [f96c9382bd](https://linux-hardware.org/?probe=f96c9382bd) | Apr 27, 2023 |
| Dell          | Latitude D520               | [a643e2e424](https://linux-hardware.org/?probe=a643e2e424) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [a24f74af8e](https://linux-hardware.org/?probe=a24f74af8e) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| System76      | Gazelle                     | [ca2e23db8d](https://linux-hardware.org/?probe=ca2e23db8d) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [f797b7112c](https://linux-hardware.org/?probe=f797b7112c) | Apr 25, 2023 |
| HP            | ENVY 15                     | [3539894e49](https://linux-hardware.org/?probe=3539894e49) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | [05d2b26ee6](https://linux-hardware.org/?probe=05d2b26ee6) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | [0ef0676073](https://linux-hardware.org/?probe=0ef0676073) | Apr 25, 2023 |
| HP            | ENVY 15                     | [39d32b035a](https://linux-hardware.org/?probe=39d32b035a) | Apr 25, 2023 |
| Apple         | MacBookPro8,1               | [2f1eb3e6ee](https://linux-hardware.org/?probe=2f1eb3e6ee) | Apr 24, 2023 |
| Alienware     | 13 R2                       | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [1259bb0006](https://linux-hardware.org/?probe=1259bb0006) | Apr 24, 2023 |
| Alienware     | 13 R3                       | [f04b34f41d](https://linux-hardware.org/?probe=f04b34f41d) | Apr 23, 2023 |
| ASUSTek       | X551MA                      | [44ca7e29c0](https://linux-hardware.org/?probe=44ca7e29c0) | Apr 23, 2023 |
| Dell          | Inspiron 7737               | [50b75a71d3](https://linux-hardware.org/?probe=50b75a71d3) | Apr 23, 2023 |
| HP            | ZBook 15                    | [c7ae51efcd](https://linux-hardware.org/?probe=c7ae51efcd) | Apr 22, 2023 |
| Dell          | Inspiron 5567               | [f639b8e21a](https://linux-hardware.org/?probe=f639b8e21a) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [332fdb5298](https://linux-hardware.org/?probe=332fdb5298) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| GPU Compan... | GWTC116-2                   | [8f7df56d73](https://linux-hardware.org/?probe=8f7df56d73) | Apr 21, 2023 |
| HP            | ProBook 640 G1              | [b5022d8a2f](https://linux-hardware.org/?probe=b5022d8a2f) | Apr 21, 2023 |
| Dell          | Precision M6600             | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | [4c78af0e05](https://linux-hardware.org/?probe=4c78af0e05) | Apr 20, 2023 |
| Dell          | XPS 13 9343                 | [573d482e45](https://linux-hardware.org/?probe=573d482e45) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [f9415c65e9](https://linux-hardware.org/?probe=f9415c65e9) | Apr 20, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [6222d9b2b0](https://linux-hardware.org/?probe=6222d9b2b0) | Apr 19, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [fc27cf4b3e](https://linux-hardware.org/?probe=fc27cf4b3e) | Apr 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0187ac7a0c](https://linux-hardware.org/?probe=0187ac7a0c) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| American M... | XA133PR110                  | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [0f058078c9](https://linux-hardware.org/?probe=0f058078c9) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| Acer          | Aspire AV15-52              | [e1044f40e2](https://linux-hardware.org/?probe=e1044f40e2) | Apr 18, 2023 |
| Acer          | Aspire E5-575               | [58b159ef8f](https://linux-hardware.org/?probe=58b159ef8f) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [e779a9606f](https://linux-hardware.org/?probe=e779a9606f) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| MSI           | PS42 Modern 8RC             | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| American M... | XA133PR110                  | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| Toshiba       | Satellite E45-B             | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| Lenovo        | Legion 7 16IAX7 82TD        | [8f0188b2a1](https://linux-hardware.org/?probe=8f0188b2a1) | Apr 17, 2023 |
| Dell          | Inspiron 3541               | [dd409790ad](https://linux-hardware.org/?probe=dd409790ad) | Apr 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [55325c372c](https://linux-hardware.org/?probe=55325c372c) | Apr 17, 2023 |
| HP            | ENVY 17                     | [ba2c1aae76](https://linux-hardware.org/?probe=ba2c1aae76) | Apr 17, 2023 |
| HP            | Dev One Notebook PC         | [5e3f0907fa](https://linux-hardware.org/?probe=5e3f0907fa) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [beac478abb](https://linux-hardware.org/?probe=beac478abb) | Apr 16, 2023 |
| Dell          | XPS 13 9310                 | [3a7d52ef90](https://linux-hardware.org/?probe=3a7d52ef90) | Apr 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [6b126883e9](https://linux-hardware.org/?probe=6b126883e9) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [9ac7ca1a63](https://linux-hardware.org/?probe=9ac7ca1a63) | Apr 16, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [762ad80f82](https://linux-hardware.org/?probe=762ad80f82) | Apr 16, 2023 |
| Dell          | Inspiron 1525               | [3b20856ccc](https://linux-hardware.org/?probe=3b20856ccc) | Apr 16, 2023 |
| Acer          | Swift SFX14-41G             | [a0f08c4442](https://linux-hardware.org/?probe=a0f08c4442) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [f7ce1b2ab5](https://linux-hardware.org/?probe=f7ce1b2ab5) | Apr 15, 2023 |
| Medion        | E15415                      | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [1d253a4901](https://linux-hardware.org/?probe=1d253a4901) | Apr 15, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [f45051411c](https://linux-hardware.org/?probe=f45051411c) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | Pavilion g6                 | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Dell          | XPS 15 9560                 | [5ab7cc057f](https://linux-hardware.org/?probe=5ab7cc057f) | Apr 14, 2023 |
| Dell          | Precision 5550              | [1546772c9f](https://linux-hardware.org/?probe=1546772c9f) | Apr 14, 2023 |
| Dell          | Latitude E5440              | [a827218c2e](https://linux-hardware.org/?probe=a827218c2e) | Apr 14, 2023 |
| ASUSTek       | X551MA                      | [871fd53afd](https://linux-hardware.org/?probe=871fd53afd) | Apr 14, 2023 |
| HP            | Laptop 15z-fc000            | [df47336192](https://linux-hardware.org/?probe=df47336192) | Apr 14, 2023 |
| HP            | Notebook                    | [79541411b2](https://linux-hardware.org/?probe=79541411b2) | Apr 14, 2023 |
| Toshiba       | IS 1413G                    | [f57cf8ddf4](https://linux-hardware.org/?probe=f57cf8ddf4) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| System76      | Pangolin                    | [1750f20c8d](https://linux-hardware.org/?probe=1750f20c8d) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [1f12146974](https://linux-hardware.org/?probe=1f12146974) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9aadb88a2d](https://linux-hardware.org/?probe=9aadb88a2d) | Apr 12, 2023 |
| Apple         | MacBookPro8,1               | [94372e3520](https://linux-hardware.org/?probe=94372e3520) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0120f0db62](https://linux-hardware.org/?probe=0120f0db62) | Apr 12, 2023 |
| Dell          | G3 3579                     | [24d10a8497](https://linux-hardware.org/?probe=24d10a8497) | Apr 12, 2023 |
| Timi          | TM1707                      | [0e015e68ec](https://linux-hardware.org/?probe=0e015e68ec) | Apr 12, 2023 |
| Timi          | TM1707                      | [b611ba24ed](https://linux-hardware.org/?probe=b611ba24ed) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| Samsung       | 760XDA                      | [bdc1648c05](https://linux-hardware.org/?probe=bdc1648c05) | Apr 11, 2023 |
| Dell          | Latitude 5590               | [f8f0f0125f](https://linux-hardware.org/?probe=f8f0f0125f) | Apr 11, 2023 |
| MSI           | GF63 Thin 9RCX              | [c48286f8a2](https://linux-hardware.org/?probe=c48286f8a2) | Apr 10, 2023 |
| Apple         | MacBookPro11,4              | [85a39124f3](https://linux-hardware.org/?probe=85a39124f3) | Apr 09, 2023 |
| Apple         | MacBookPro12,1              | [0844c71fd0](https://linux-hardware.org/?probe=0844c71fd0) | Apr 07, 2023 |
| System76      | Oryx Pro                    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| HP            | ProBook 640 G1              | [769d886cc9](https://linux-hardware.org/?probe=769d886cc9) | Apr 05, 2023 |
| HP            | ProBook 640 G1              | [de7d3ba0c0](https://linux-hardware.org/?probe=de7d3ba0c0) | Apr 05, 2023 |
| Razer         | Blade                       | [351fe907cb](https://linux-hardware.org/?probe=351fe907cb) | Apr 05, 2023 |
| Apple         | MacBookPro12,1              | [c77ef60bcc](https://linux-hardware.org/?probe=c77ef60bcc) | Apr 05, 2023 |
| HP            | Laptop 14-dq0xxx            | [ba87782532](https://linux-hardware.org/?probe=ba87782532) | Apr 05, 2023 |
| Lenovo        | Edge 15 80K9                | [911d261c1b](https://linux-hardware.org/?probe=911d261c1b) | Apr 05, 2023 |
| ASUSTek       | N76VZ                       | [d87006e429](https://linux-hardware.org/?probe=d87006e429) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [3f886e678f](https://linux-hardware.org/?probe=3f886e678f) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [43e4869357](https://linux-hardware.org/?probe=43e4869357) | Apr 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [58f5904dec](https://linux-hardware.org/?probe=58f5904dec) | Apr 04, 2023 |
| Dell          | Inspiron 7375               | [0d8465f75c](https://linux-hardware.org/?probe=0d8465f75c) | Apr 04, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [d56565f374](https://linux-hardware.org/?probe=d56565f374) | Apr 04, 2023 |
| Dell          | XPS 15 9500                 | [84f877fde3](https://linux-hardware.org/?probe=84f877fde3) | Apr 04, 2023 |
| ASUSTek       | E201NA                      | [098fb721f8](https://linux-hardware.org/?probe=098fb721f8) | Apr 04, 2023 |
| Acer          | Swift SF314-43              | [a964b0aa55](https://linux-hardware.org/?probe=a964b0aa55) | Apr 04, 2023 |
| Razer         | Blade Stealth               | [2cf4a53eb5](https://linux-hardware.org/?probe=2cf4a53eb5) | Apr 04, 2023 |
| Dell          | Latitude E7240              | [fce3da8380](https://linux-hardware.org/?probe=fce3da8380) | Apr 04, 2023 |
| Unknown       | Unknown                     | [190b5364e1](https://linux-hardware.org/?probe=190b5364e1) | Apr 03, 2023 |
| Unknown       | Unknown                     | [a6a766a40a](https://linux-hardware.org/?probe=a6a766a40a) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9880810adc](https://linux-hardware.org/?probe=9880810adc) | Apr 03, 2023 |
| MSI           | GV62 7RE                    | [5d441311f4](https://linux-hardware.org/?probe=5d441311f4) | Apr 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [777f7d0fc4](https://linux-hardware.org/?probe=777f7d0fc4) | Apr 03, 2023 |
| MSI           | GL63 8RC                    | [8c90ec7da1](https://linux-hardware.org/?probe=8c90ec7da1) | Apr 03, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [f013c5ca48](https://linux-hardware.org/?probe=f013c5ca48) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | [edb2f4188e](https://linux-hardware.org/?probe=edb2f4188e) | Apr 03, 2023 |
| HP            | 650                         | [bcb4e8d60a](https://linux-hardware.org/?probe=bcb4e8d60a) | Apr 03, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [7274c8222b](https://linux-hardware.org/?probe=7274c8222b) | Apr 02, 2023 |
| Lenovo        | ThinkPad T460p 20FXS08N0... | [ffcf174547](https://linux-hardware.org/?probe=ffcf174547) | Apr 02, 2023 |
| Apple         | MacBook3,1                  | [44f31f3094](https://linux-hardware.org/?probe=44f31f3094) | Apr 02, 2023 |
| System76      | Kudu                        | [2baafe374c](https://linux-hardware.org/?probe=2baafe374c) | Apr 02, 2023 |
| Toshiba       | IS 1413G                    | [76a94d8c87](https://linux-hardware.org/?probe=76a94d8c87) | Apr 02, 2023 |
| Sony          | VPCSC1AFM                   | [854b8bfa02](https://linux-hardware.org/?probe=854b8bfa02) | Apr 01, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [51c7ed9156](https://linux-hardware.org/?probe=51c7ed9156) | Apr 01, 2023 |
| Lenovo        | Slim 7 16ARH7 82UX          | [cca7093e15](https://linux-hardware.org/?probe=cca7093e15) | Apr 01, 2023 |
| Lenovo        | IdeaPad U310                | [6add75e18c](https://linux-hardware.org/?probe=6add75e18c) | Apr 01, 2023 |
| Toshiba       | Satellite L45-B             | [6d4878cdbf](https://linux-hardware.org/?probe=6d4878cdbf) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| System76      | Lemur Pro                   | [5d57a3397e](https://linux-hardware.org/?probe=5d57a3397e) | Mar 31, 2023 |
| ASUSTek       | X751LD                      | [2ef82331de](https://linux-hardware.org/?probe=2ef82331de) | Mar 31, 2023 |
| Acer          | Aspire A515-56              | [bf846cebb9](https://linux-hardware.org/?probe=bf846cebb9) | Mar 30, 2023 |
| Acer          | Nitro AN515-58              | [27befad01f](https://linux-hardware.org/?probe=27befad01f) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | [21515b7373](https://linux-hardware.org/?probe=21515b7373) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | [080e22fdb2](https://linux-hardware.org/?probe=080e22fdb2) | Mar 30, 2023 |
| Toshiba       | IS 1413G                    | [13f35137bd](https://linux-hardware.org/?probe=13f35137bd) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [7ee1845d96](https://linux-hardware.org/?probe=7ee1845d96) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [bb80f561a2](https://linux-hardware.org/?probe=bb80f561a2) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [854490056d](https://linux-hardware.org/?probe=854490056d) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [af48722867](https://linux-hardware.org/?probe=af48722867) | Mar 28, 2023 |
| Dell          | G3 3590                     | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0667374075](https://linux-hardware.org/?probe=0667374075) | Mar 28, 2023 |
| Acer          | Nitro AN515-45              | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [7939320fa4](https://linux-hardware.org/?probe=7939320fa4) | Mar 28, 2023 |
| Positivo      | Mobile                      | [60fd382fbf](https://linux-hardware.org/?probe=60fd382fbf) | Mar 28, 2023 |
| Positivo      | Mobile                      | [b08c430903](https://linux-hardware.org/?probe=b08c430903) | Mar 28, 2023 |
| Razer         | Blade                       | [ffa791eb4a](https://linux-hardware.org/?probe=ffa791eb4a) | Mar 28, 2023 |
| ASUSTek       | X751LD                      | [61382d0bd8](https://linux-hardware.org/?probe=61382d0bd8) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Toshiba       | IS 1413G                    | [635309aff4](https://linux-hardware.org/?probe=635309aff4) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T400     | [5b4466c085](https://linux-hardware.org/?probe=5b4466c085) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [8ddee342c9](https://linux-hardware.org/?probe=8ddee342c9) | Mar 28, 2023 |
| Dell          | XPS 15 9570                 | [5be538736f](https://linux-hardware.org/?probe=5be538736f) | Mar 27, 2023 |
| Toshiba       | Satellite C55-C             | [d7ec0eb4b1](https://linux-hardware.org/?probe=d7ec0eb4b1) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | [a5c200217f](https://linux-hardware.org/?probe=a5c200217f) | Mar 26, 2023 |
| MSI           | GL63 8RC                    | [935b78c3da](https://linux-hardware.org/?probe=935b78c3da) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [905078c7b9](https://linux-hardware.org/?probe=905078c7b9) | Mar 26, 2023 |
| Dell          | Latitude E7240              | [3d91b46fda](https://linux-hardware.org/?probe=3d91b46fda) | Mar 26, 2023 |
| Dell          | XPS 13 9370                 | [3f3967267f](https://linux-hardware.org/?probe=3f3967267f) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| HP            | Spectre Laptop 13-af0xx     | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | [21c3ce9508](https://linux-hardware.org/?probe=21c3ce9508) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ac415822b8](https://linux-hardware.org/?probe=ac415822b8) | Mar 24, 2023 |
| HP            | Laptop 15-db0xxx            | [ad0e5c0483](https://linux-hardware.org/?probe=ad0e5c0483) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [e6afbbee47](https://linux-hardware.org/?probe=e6afbbee47) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| Alienware     | 17 R4                       | [3c456dc309](https://linux-hardware.org/?probe=3c456dc309) | Mar 24, 2023 |
| GPU Compan... | GWTN141-10                  | [9007c1d23f](https://linux-hardware.org/?probe=9007c1d23f) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [f8f47e3220](https://linux-hardware.org/?probe=f8f47e3220) | Mar 23, 2023 |
| Dell          | Precision 7710              | [25a4797475](https://linux-hardware.org/?probe=25a4797475) | Mar 23, 2023 |
| Toshiba       | IS 1413G                    | [3a75d7fb8d](https://linux-hardware.org/?probe=3a75d7fb8d) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [f6580b20d3](https://linux-hardware.org/?probe=f6580b20d3) | Mar 22, 2023 |
| Apple         | MacBook5,1                  | [bc6e3fa274](https://linux-hardware.org/?probe=bc6e3fa274) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | [627590f38c](https://linux-hardware.org/?probe=627590f38c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [a49ece0e6c](https://linux-hardware.org/?probe=a49ece0e6c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [315f2256c6](https://linux-hardware.org/?probe=315f2256c6) | Mar 22, 2023 |
| Apple         | MacBookPro8,1               | [b616377b13](https://linux-hardware.org/?probe=b616377b13) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | [aff8d829e0](https://linux-hardware.org/?probe=aff8d829e0) | Mar 22, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [99fe9f96c6](https://linux-hardware.org/?probe=99fe9f96c6) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | [af60ed4cde](https://linux-hardware.org/?probe=af60ed4cde) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | [3b3376e72c](https://linux-hardware.org/?probe=3b3376e72c) | Mar 21, 2023 |
| HUAWEI        | KPL-W0X                     | [afc1ff125b](https://linux-hardware.org/?probe=afc1ff125b) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [3c100c55be](https://linux-hardware.org/?probe=3c100c55be) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [039724e2c2](https://linux-hardware.org/?probe=039724e2c2) | Mar 21, 2023 |
| Dell          | G15 5511                    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | XPS L421X                   | [fd54af9534](https://linux-hardware.org/?probe=fd54af9534) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [afe8ca841c](https://linux-hardware.org/?probe=afe8ca841c) | Mar 21, 2023 |
| Acer          | Aspire 5349                 | [c0f5810e5c](https://linux-hardware.org/?probe=c0f5810e5c) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | [d6ff521952](https://linux-hardware.org/?probe=d6ff521952) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | [d6393f5710](https://linux-hardware.org/?probe=d6393f5710) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | [404c84b0ea](https://linux-hardware.org/?probe=404c84b0ea) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | [edf722e245](https://linux-hardware.org/?probe=edf722e245) | Mar 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | [2ff2eab844](https://linux-hardware.org/?probe=2ff2eab844) | Mar 21, 2023 |
| ASUSTek       | G74Sx                       | [d2b90b7d2f](https://linux-hardware.org/?probe=d2b90b7d2f) | Mar 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [afcac034a9](https://linux-hardware.org/?probe=afcac034a9) | Mar 20, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [d08f174747](https://linux-hardware.org/?probe=d08f174747) | Mar 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c9b4e3cf00](https://linux-hardware.org/?probe=c9b4e3cf00) | Mar 20, 2023 |
| Dell          | Latitude 5590               | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| MSI           | PS42 8M                     | [aad18852f4](https://linux-hardware.org/?probe=aad18852f4) | Mar 19, 2023 |
| ASUSTek       | G74Sx                       | [f7f92408dc](https://linux-hardware.org/?probe=f7f92408dc) | Mar 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6b6ceb1a1a](https://linux-hardware.org/?probe=6b6ceb1a1a) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e3410282c5](https://linux-hardware.org/?probe=e3410282c5) | Mar 19, 2023 |
| ASUSTek       | S551LB                      | [7d4485326f](https://linux-hardware.org/?probe=7d4485326f) | Mar 18, 2023 |
| GPU Compan... | GWTN141-10                  | [ff8db61ccf](https://linux-hardware.org/?probe=ff8db61ccf) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [dd296a8801](https://linux-hardware.org/?probe=dd296a8801) | Mar 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S11N00    | [60d80937ea](https://linux-hardware.org/?probe=60d80937ea) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| Dell          | Latitude E7240              | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| Positivo      | N1250                       | [e5ee22876a](https://linux-hardware.org/?probe=e5ee22876a) | Mar 17, 2023 |
| HP            | ProBook 4530s               | [f0abd32fe4](https://linux-hardware.org/?probe=f0abd32fe4) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | [a7a6cc1ab5](https://linux-hardware.org/?probe=a7a6cc1ab5) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | [204994be7f](https://linux-hardware.org/?probe=204994be7f) | Mar 17, 2023 |
| TUXEDO        | Pulse 14 Gen1               | [525b267c31](https://linux-hardware.org/?probe=525b267c31) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| Unknown       | Unknown                     | [3eb0bf05b4](https://linux-hardware.org/?probe=3eb0bf05b4) | Mar 17, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0RP0... | [f901058202](https://linux-hardware.org/?probe=f901058202) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d6f5cd9505](https://linux-hardware.org/?probe=d6f5cd9505) | Mar 16, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [5f48c46d68](https://linux-hardware.org/?probe=5f48c46d68) | Mar 16, 2023 |
| HP            | Laptop 15s-eq1xxx           | [59a304e790](https://linux-hardware.org/?probe=59a304e790) | Mar 15, 2023 |
| Acer          | Aspire A715-42G             | [8bdae79f7a](https://linux-hardware.org/?probe=8bdae79f7a) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| Razer         | Blade Stealth 13 (Early ... | [eb1d71edb4](https://linux-hardware.org/?probe=eb1d71edb4) | Mar 15, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | [af254fca4d](https://linux-hardware.org/?probe=af254fca4d) | Mar 15, 2023 |
| SAGER         | X8100                       | [90aaefeb9e](https://linux-hardware.org/?probe=90aaefeb9e) | Mar 15, 2023 |
| System76      | Pangolin                    | [4f39796131](https://linux-hardware.org/?probe=4f39796131) | Mar 15, 2023 |
| Dell          | Latitude E7240              | [d4ed345a47](https://linux-hardware.org/?probe=d4ed345a47) | Mar 14, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | [1161c07721](https://linux-hardware.org/?probe=1161c07721) | Mar 14, 2023 |
| Sony          | VPCZ12V9R                   | [28be5f7f2b](https://linux-hardware.org/?probe=28be5f7f2b) | Mar 14, 2023 |
| Dell          | Latitude E7240              | [4a7d442938](https://linux-hardware.org/?probe=4a7d442938) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | [44d9ce8acb](https://linux-hardware.org/?probe=44d9ce8acb) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | [986fe8c418](https://linux-hardware.org/?probe=986fe8c418) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| HP            | EliteBook 840 G6            | [874706952d](https://linux-hardware.org/?probe=874706952d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [de22b8a7e6](https://linux-hardware.org/?probe=de22b8a7e6) | Mar 14, 2023 |
| Dell          | Inspiron 7348               | [7459d24035](https://linux-hardware.org/?probe=7459d24035) | Mar 13, 2023 |
| Apple         | MacBookPro9,1               | [f85095c103](https://linux-hardware.org/?probe=f85095c103) | Mar 13, 2023 |
| Toshiba       | IS 1413G                    | [b93a4bdcbb](https://linux-hardware.org/?probe=b93a4bdcbb) | Mar 13, 2023 |
| Acer          | Aspire 4530                 | [84f4733a96](https://linux-hardware.org/?probe=84f4733a96) | Mar 13, 2023 |
| Acer          | Nitro AN515-58              | [7f2ecd927d](https://linux-hardware.org/?probe=7f2ecd927d) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | [663f73a08e](https://linux-hardware.org/?probe=663f73a08e) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | [5d1a30091e](https://linux-hardware.org/?probe=5d1a30091e) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| HUAWEI        | NBM-WXX9                    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Google        | Kefka                       | [4a54e34e44](https://linux-hardware.org/?probe=4a54e34e44) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [7090114437](https://linux-hardware.org/?probe=7090114437) | Mar 12, 2023 |
| Dell          | Inspiron 5452               | [2c8ca0e296](https://linux-hardware.org/?probe=2c8ca0e296) | Mar 12, 2023 |
| Positivo B... | VJFE41F11X-XXXXXX           | [99f410d801](https://linux-hardware.org/?probe=99f410d801) | Mar 11, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [e101a1c94c](https://linux-hardware.org/?probe=e101a1c94c) | Mar 11, 2023 |
| HONOR         | NMH-WCX9                    | [d8cf10f11d](https://linux-hardware.org/?probe=d8cf10f11d) | Mar 11, 2023 |
| HP            | ZBook 17                    | [a775bc33c5](https://linux-hardware.org/?probe=a775bc33c5) | Mar 11, 2023 |
| Maibenben     | P748                        | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Toshiba       | IS 1413G                    | [39cc207ce7](https://linux-hardware.org/?probe=39cc207ce7) | Mar 11, 2023 |
| Lenovo        | ThinkPad L440 20ASS0ET00    | [2ac6dfff4f](https://linux-hardware.org/?probe=2ac6dfff4f) | Mar 11, 2023 |
| GPD           | G1619-04                    | [302ff30130](https://linux-hardware.org/?probe=302ff30130) | Mar 11, 2023 |
| GPD           | G1619-04                    | [d8f5b9eec9](https://linux-hardware.org/?probe=d8f5b9eec9) | Mar 11, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [96f4bd0a52](https://linux-hardware.org/?probe=96f4bd0a52) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [969ab4279f](https://linux-hardware.org/?probe=969ab4279f) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [c44f0eab3e](https://linux-hardware.org/?probe=c44f0eab3e) | Mar 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [44867c946f](https://linux-hardware.org/?probe=44867c946f) | Mar 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [50dd87563b](https://linux-hardware.org/?probe=50dd87563b) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [410a5a70f3](https://linux-hardware.org/?probe=410a5a70f3) | Mar 10, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [eac4ae85a4](https://linux-hardware.org/?probe=eac4ae85a4) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [baffc24bef](https://linux-hardware.org/?probe=baffc24bef) | Mar 10, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [187761b57d](https://linux-hardware.org/?probe=187761b57d) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4e1196658a](https://linux-hardware.org/?probe=4e1196658a) | Mar 09, 2023 |
| HP            | ENVY Notebook               | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [a8d1bd3e81](https://linux-hardware.org/?probe=a8d1bd3e81) | Mar 09, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [7805fe229d](https://linux-hardware.org/?probe=7805fe229d) | Mar 08, 2023 |
| HP            | EliteBook 8570w             | [dfd9b7a9b9](https://linux-hardware.org/?probe=dfd9b7a9b9) | Mar 08, 2023 |
| Razer         | Blade 15 Advanced Model ... | [46fa9eab7d](https://linux-hardware.org/?probe=46fa9eab7d) | Mar 08, 2023 |
| Google        | Bobba                       | [01d8f57c7e](https://linux-hardware.org/?probe=01d8f57c7e) | Mar 08, 2023 |
| Lenovo        | IdeaPad U310                | [f666446ecb](https://linux-hardware.org/?probe=f666446ecb) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3ff5ff8f2d](https://linux-hardware.org/?probe=3ff5ff8f2d) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | [4a698cb3eb](https://linux-hardware.org/?probe=4a698cb3eb) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| Toshiba       | IS 1413G                    | [12954ccbdb](https://linux-hardware.org/?probe=12954ccbdb) | Mar 07, 2023 |
| Google        | Lillipup                    | [b924f92de8](https://linux-hardware.org/?probe=b924f92de8) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | [5a03b7e11e](https://linux-hardware.org/?probe=5a03b7e11e) | Mar 07, 2023 |
| Apple         | MacBookPro8,1               | [bef545e821](https://linux-hardware.org/?probe=bef545e821) | Mar 07, 2023 |
| Dell          | Inspiron 16 7610            | [625691c490](https://linux-hardware.org/?probe=625691c490) | Mar 06, 2023 |
| Dell          | Inspiron 16 7610            | [66b4f88fb7](https://linux-hardware.org/?probe=66b4f88fb7) | Mar 06, 2023 |
| HP            | 3115m                       | [87abd0ac9d](https://linux-hardware.org/?probe=87abd0ac9d) | Mar 06, 2023 |
| Dell          | G7 7588                     | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| HUAWEI        | KPL-W0X                     | [76ebbe553f](https://linux-hardware.org/?probe=76ebbe553f) | Mar 06, 2023 |
| Apple         | MacBookAir7,2               | [ae4d8e9128](https://linux-hardware.org/?probe=ae4d8e9128) | Mar 06, 2023 |
| MSI           | Vector GP76 12UHSO          | [e82fbd8c0a](https://linux-hardware.org/?probe=e82fbd8c0a) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | [a6c8ba1040](https://linux-hardware.org/?probe=a6c8ba1040) | Mar 05, 2023 |
| Apple         | MacBookAir7,2               | [fef18d1795](https://linux-hardware.org/?probe=fef18d1795) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [779113ef3c](https://linux-hardware.org/?probe=779113ef3c) | Mar 05, 2023 |
| HP            | Pavilion 15                 | [0c4050d1ef](https://linux-hardware.org/?probe=0c4050d1ef) | Mar 05, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [ff4621a345](https://linux-hardware.org/?probe=ff4621a345) | Mar 05, 2023 |
| Dell          | Latitude 5420               | [ea5ac72a44](https://linux-hardware.org/?probe=ea5ac72a44) | Mar 05, 2023 |
| Toshiba       | IS 1413G                    | [a655c49d8b](https://linux-hardware.org/?probe=a655c49d8b) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | [ca5a019457](https://linux-hardware.org/?probe=ca5a019457) | Mar 04, 2023 |
| Apple         | MacBookPro9,2               | [ba908d3339](https://linux-hardware.org/?probe=ba908d3339) | Mar 04, 2023 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [26ca476e1a](https://linux-hardware.org/?probe=26ca476e1a) | Mar 04, 2023 |
| Dell          | System XPS L321X            | [24d0d12eca](https://linux-hardware.org/?probe=24d0d12eca) | Mar 04, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | [ccda7b2155](https://linux-hardware.org/?probe=ccda7b2155) | Mar 04, 2023 |
| Gigabyte      | AORUS 17 XE4                | [6f6750ee73](https://linux-hardware.org/?probe=6f6750ee73) | Mar 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [db92a5f137](https://linux-hardware.org/?probe=db92a5f137) | Mar 03, 2023 |
| HP            | EliteBook 8440p             | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | [756ac6782b](https://linux-hardware.org/?probe=756ac6782b) | Mar 03, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Acer          | Swift SF314-54              | [62defb89e3](https://linux-hardware.org/?probe=62defb89e3) | Mar 02, 2023 |
| System76      | Lemur Pro                   | [e7ed83aaf7](https://linux-hardware.org/?probe=e7ed83aaf7) | Mar 01, 2023 |
| HP            | 15                          | [97985ac192](https://linux-hardware.org/?probe=97985ac192) | Mar 01, 2023 |
| HP            | EliteBook 830 G5            | [9abfe7631c](https://linux-hardware.org/?probe=9abfe7631c) | Mar 01, 2023 |
| ASUSTek       | X751LD                      | [46eecb2678](https://linux-hardware.org/?probe=46eecb2678) | Mar 01, 2023 |
| Dell          | Precision 3571              | [40348190de](https://linux-hardware.org/?probe=40348190de) | Mar 01, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [571d426262](https://linux-hardware.org/?probe=571d426262) | Mar 01, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [78ee2e145b](https://linux-hardware.org/?probe=78ee2e145b) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [bd4fd4080d](https://linux-hardware.org/?probe=bd4fd4080d) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [90d8927f0a](https://linux-hardware.org/?probe=90d8927f0a) | Mar 01, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [5aad25779a](https://linux-hardware.org/?probe=5aad25779a) | Feb 28, 2023 |
| Acer          | Aspire A515-57              | [6c511739eb](https://linux-hardware.org/?probe=6c511739eb) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | [ff84200b75](https://linux-hardware.org/?probe=ff84200b75) | Feb 28, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [88745e1f03](https://linux-hardware.org/?probe=88745e1f03) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [357c1abb1d](https://linux-hardware.org/?probe=357c1abb1d) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | [82a40f1881](https://linux-hardware.org/?probe=82a40f1881) | Feb 27, 2023 |
| Acer          | Aspire A515-56              | [97e3001416](https://linux-hardware.org/?probe=97e3001416) | Feb 26, 2023 |
| Dell          | XPS 13 7390                 | [2a8830034a](https://linux-hardware.org/?probe=2a8830034a) | Feb 26, 2023 |
| Acer          | Nitro AN515-58              | [1c93095718](https://linux-hardware.org/?probe=1c93095718) | Feb 26, 2023 |
| Sony          | VPCZ12V9R                   | [3014067c24](https://linux-hardware.org/?probe=3014067c24) | Feb 26, 2023 |
| GPU Compan... | GWTN141-10                  | [1550bec17e](https://linux-hardware.org/?probe=1550bec17e) | Feb 25, 2023 |
| GPU Compan... | GWTN141-10                  | [aa535b0731](https://linux-hardware.org/?probe=aa535b0731) | Feb 25, 2023 |
| Dell          | G7 7588                     | [82f1398a69](https://linux-hardware.org/?probe=82f1398a69) | Feb 25, 2023 |
| Alienware     | 15 R3                       | [72543030d5](https://linux-hardware.org/?probe=72543030d5) | Feb 25, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [42b9d60137](https://linux-hardware.org/?probe=42b9d60137) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| System76      | Galago Pro                  | [3e4391562b](https://linux-hardware.org/?probe=3e4391562b) | Feb 25, 2023 |
| Packard Be... | EasyNote TS11HR             | [0a63352761](https://linux-hardware.org/?probe=0a63352761) | Feb 25, 2023 |
| Dell          | XPS 15 9500                 | [96e6c2c201](https://linux-hardware.org/?probe=96e6c2c201) | Feb 25, 2023 |
| Dell          | Latitude 3310               | [d989647d9d](https://linux-hardware.org/?probe=d989647d9d) | Feb 25, 2023 |
| Acer          | Aspire A515-56              | [517a6211c9](https://linux-hardware.org/?probe=517a6211c9) | Feb 24, 2023 |
| HP            | ProBook 450 G1              | [f7c4b009f1](https://linux-hardware.org/?probe=f7c4b009f1) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [297c37ec04](https://linux-hardware.org/?probe=297c37ec04) | Feb 24, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [2f561a23c3](https://linux-hardware.org/?probe=2f561a23c3) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [041c57ebe6](https://linux-hardware.org/?probe=041c57ebe6) | Feb 24, 2023 |
| Apple         | MacBookPro9,2               | [c591acd5d6](https://linux-hardware.org/?probe=c591acd5d6) | Feb 24, 2023 |
| Dell          | Inspiron 5423               | [7cf47f3118](https://linux-hardware.org/?probe=7cf47f3118) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [bb0d8e868d](https://linux-hardware.org/?probe=bb0d8e868d) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| System76      | Gazelle                     | [609f452af9](https://linux-hardware.org/?probe=609f452af9) | Feb 23, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | [33a4731a5e](https://linux-hardware.org/?probe=33a4731a5e) | Feb 23, 2023 |
| Dell          | Latitude E7240              | [7f8278ff44](https://linux-hardware.org/?probe=7f8278ff44) | Feb 23, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [34016a67d9](https://linux-hardware.org/?probe=34016a67d9) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [312937f0d0](https://linux-hardware.org/?probe=312937f0d0) | Feb 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [6ab727e8c0](https://linux-hardware.org/?probe=6ab727e8c0) | Feb 22, 2023 |
| Apple         | MacBookPro11,4              | [c4eab564b3](https://linux-hardware.org/?probe=c4eab564b3) | Feb 22, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| HP            | EliteBook Folio 1040 G2     | [265018acd3](https://linux-hardware.org/?probe=265018acd3) | Feb 21, 2023 |
| Apple         | MacBookPro16,1              | [a5cff07fd8](https://linux-hardware.org/?probe=a5cff07fd8) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| Dell          | G15 5525                    | [63bd2ac7b9](https://linux-hardware.org/?probe=63bd2ac7b9) | Feb 21, 2023 |
| Acer          | Swift SF114-34              | [e9f5a9d293](https://linux-hardware.org/?probe=e9f5a9d293) | Feb 21, 2023 |
| Dell          | Precision M4800             | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| HP            | Laptop 14s-fq0xxx           | [0bc03f3b39](https://linux-hardware.org/?probe=0bc03f3b39) | Feb 20, 2023 |
| HP            | ProBook 450 G1              | [b5e8826f8c](https://linux-hardware.org/?probe=b5e8826f8c) | Feb 20, 2023 |
| Dell          | XPS 15 7590                 | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| Apple         | MacBook4,1                  | [2011c2060b](https://linux-hardware.org/?probe=2011c2060b) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| HP            | 240 G6 Notebook PC          | [fc39dde214](https://linux-hardware.org/?probe=fc39dde214) | Feb 18, 2023 |
| Dell          | Latitude E7240              | [461873da2d](https://linux-hardware.org/?probe=461873da2d) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [5cc4ff8271](https://linux-hardware.org/?probe=5cc4ff8271) | Feb 18, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pop!_OS 22.04 | 1879      | 34.19%  |
| Pop!_OS 20.04 | 1153      | 20.98%  |
| Pop!_OS 21.04 | 960       | 17.47%  |
| Pop!_OS 20.10 | 856       | 15.58%  |
| Pop!_OS 21.10 | 600       | 10.92%  |
| Pop!_OS 19.10 | 30        | 0.55%   |
| Pop!_OS 18.04 | 7         | 0.13%   |
| Pop!_OS 19.04 | 6         | 0.11%   |
| Pop!_OS 18.10 | 4         | 0.07%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Pop!_OS | 5236      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.2.6-76060206-generic   | 456       | 7.73%   |
| 5.11.0-7620-generic      | 443       | 7.51%   |
| 5.8.0-7630-generic       | 381       | 6.46%   |
| 5.4.0-7634-generic       | 346       | 5.87%   |
| 5.19.0-76051900-generic  | 273       | 4.63%   |
| 6.0.12-76060006-generic  | 264       | 4.48%   |
| 5.13.0-7614-generic      | 262       | 4.44%   |
| 5.4.0-7642-generic       | 256       | 4.34%   |
| 5.17.5-76051705-generic  | 251       | 4.26%   |
| 5.8.0-7642-generic       | 242       | 4.1%    |
| 5.11.0-7614-generic      | 227       | 3.85%   |
| 5.13.0-7620-generic      | 218       | 3.7%    |
| 6.0.6-76060006-generic   | 162       | 2.75%   |
| 5.15.15-76051515-generic | 154       | 2.61%   |
| 5.16.11-76051611-generic | 139       | 2.36%   |
| 5.11.0-7612-generic      | 128       | 2.17%   |
| 5.15.5-76051505-generic  | 123       | 2.09%   |
| 5.18.10-76051810-generic | 122       | 2.07%   |
| 5.8.0-7625-generic       | 105       | 1.78%   |
| 5.17.15-76051715-generic | 105       | 1.78%   |
| 5.11.0-7633-generic      | 99        | 1.68%   |
| 5.15.8-76051508-generic  | 98        | 1.66%   |
| 5.16.19-76051619-generic | 97        | 1.64%   |
| 6.4.6-76060406-generic   | 95        | 1.61%   |
| 5.16.15-76051615-generic | 92        | 1.56%   |
| 5.4.0-7626-generic       | 84        | 1.42%   |
| 6.2.0-76060200-generic   | 76        | 1.29%   |
| 5.15.11-76051511-generic | 63        | 1.07%   |
| 6.0.2-76060002-generic   | 59        | 1%      |
| 5.15.23-76051523-generic | 56        | 0.95%   |
| 6.1.11-76060111-generic  | 54        | 0.92%   |
| 5.4.0-7625-generic       | 44        | 0.75%   |
| 5.4.0-7629-generic       | 35        | 0.59%   |
| 6.0.3-76060003-generic   | 23        | 0.39%   |
| 5.19.16-76051916-generic | 21        | 0.36%   |
| 5.3.0-7625-generic       | 10        | 0.17%   |
| 5.3.0-7648-generic       | 6         | 0.1%    |
| 5.11.0-051100-generic    | 6         | 0.1%    |
| 6.0.12-76060012-generic  | 4         | 0.07%   |
| 5.3.0-7642-generic       | 4         | 0.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 875       | 15.1%   |
| 5.4.0   | 744       | 12.84%  |
| 5.8.0   | 698       | 12.05%  |
| 5.13.0  | 467       | 8.06%   |
| 6.2.6   | 457       | 7.89%   |
| 5.19.0  | 276       | 4.76%   |
| 6.0.12  | 268       | 4.63%   |
| 5.17.5  | 254       | 4.38%   |
| 6.0.6   | 162       | 2.8%    |
| 5.15.15 | 154       | 2.66%   |
| 5.16.11 | 139       | 2.4%    |
| 5.15.5  | 123       | 2.12%   |
| 5.18.10 | 122       | 2.11%   |
| 5.17.15 | 105       | 1.81%   |
| 5.15.8  | 98        | 1.69%   |
| 5.16.19 | 97        | 1.67%   |
| 6.4.6   | 95        | 1.64%   |
| 5.16.15 | 92        | 1.59%   |
| 6.2.0   | 76        | 1.31%   |
| 5.15.11 | 63        | 1.09%   |
| 6.0.2   | 60        | 1.04%   |
| 5.15.23 | 56        | 0.97%   |
| 6.1.11  | 54        | 0.93%   |
| 5.3.0   | 32        | 0.55%   |
| 6.0.3   | 23        | 0.4%    |
| 5.19.16 | 21        | 0.36%   |
| 5.0.0   | 6         | 0.1%    |
| 4.18.0  | 6         | 0.1%    |
| 5.7.0   | 4         | 0.07%   |
| 5.15.0  | 4         | 0.07%   |
| 5.8.6   | 3         | 0.05%   |
| 5.8.11  | 3         | 0.05%   |
| 5.7.1   | 3         | 0.05%   |
| 5.14.0  | 3         | 0.05%   |
| 5.12.14 | 3         | 0.05%   |
| 5.10.0  | 3         | 0.05%   |
| 6.4.0   | 2         | 0.03%   |
| 6.3.9   | 2         | 0.03%   |
| 6.3.7   | 2         | 0.03%   |
| 6.2.11  | 2         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 881       | 15.35%  |
| 5.4     | 745       | 12.98%  |
| 5.8     | 712       | 12.41%  |
| 6.2     | 534       | 9.31%   |
| 6.0     | 499       | 8.7%    |
| 5.15    | 494       | 8.61%   |
| 5.13    | 478       | 8.33%   |
| 5.17    | 359       | 6.26%   |
| 5.16    | 326       | 5.68%   |
| 5.19    | 299       | 5.21%   |
| 5.18    | 126       | 2.2%    |
| 6.4     | 99        | 1.73%   |
| 6.1     | 61        | 1.06%   |
| 5.3     | 32        | 0.56%   |
| 5.10    | 18        | 0.31%   |
| 5.12    | 13        | 0.23%   |
| 5.7     | 11        | 0.19%   |
| 5.14    | 11        | 0.19%   |
| 5.9     | 9         | 0.16%   |
| 6.3     | 7         | 0.12%   |
| 5.6     | 7         | 0.12%   |
| 4.18    | 7         | 0.12%   |
| 5.0     | 6         | 0.1%    |
| 4.15    | 2         | 0.03%   |
| 6.5     | 1         | 0.02%   |
| 4.9     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 5236      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 5070      | 96.35%  |
| KDE5            | 44        | 0.84%   |
| Unknown         | 44        | 0.84%   |
| KDE             | 25        | 0.48%   |
| X-Cinnamon      | 19        | 0.36%   |
| GNOME Flashback | 12        | 0.23%   |
| XFCE            | 9         | 0.17%   |
| MATE            | 9         | 0.17%   |
| LXQt            | 9         | 0.17%   |
| Unity           | 7         | 0.13%   |
| Cinnamon        | 7         | 0.13%   |
| Budgie          | 4         | 0.08%   |
| i3              | 1         | 0.02%   |
| Deepin          | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 5052      | 95.99%  |
| Wayland | 184       | 3.5%    |
| Unknown | 19        | 0.36%   |
| Tty     | 8         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3960      | 74.76%  |
| GDM     | 775       | 14.63%  |
| GDM3    | 546       | 10.31%  |
| SDDM    | 9         | 0.17%   |
| TDM     | 5         | 0.09%   |
| LightDM | 2         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 3045      | 57.78%  |
| pt_BR   | 383       | 7.27%   |
| en_GB   | 367       | 6.96%   |
| de_DE   | 220       | 4.17%   |
| C       | 135       | 2.56%   |
| it_IT   | 106       | 2.01%   |
| es_ES   | 106       | 2.01%   |
| fr_FR   | 105       | 1.99%   |
| en_AU   | 105       | 1.99%   |
| en_CA   | 92        | 1.75%   |
| ru_RU   | 74        | 1.4%    |
| Unknown | 56        | 1.06%   |
| pl_PL   | 49        | 0.93%   |
| pt_PT   | 46        | 0.87%   |
| sv_SE   | 34        | 0.65%   |
| en_IN   | 31        | 0.59%   |
| nb_NO   | 23        | 0.44%   |
| nl_NL   | 22        | 0.42%   |
| es_MX   | 20        | 0.38%   |
| en_ZA   | 20        | 0.38%   |
| fi_FI   | 18        | 0.34%   |
| tr_TR   | 16        | 0.3%    |
| en_NZ   | 15        | 0.28%   |
| fr_CA   | 11        | 0.21%   |
| es_AR   | 11        | 0.21%   |
| en_IE   | 11        | 0.21%   |
| cs_CZ   | 11        | 0.21%   |
| en_DK   | 9         | 0.17%   |
| da_DK   | 9         | 0.17%   |
| hu_HU   | 8         | 0.15%   |
| hr_HR   | 8         | 0.15%   |
| es_CL   | 8         | 0.15%   |
| de_CH   | 8         | 0.15%   |
| sk_SK   | 6         | 0.11%   |
| ro_RO   | 6         | 0.11%   |
| zh_CN   | 5         | 0.09%   |
| es_CO   | 5         | 0.09%   |
| de_AT   | 5         | 0.09%   |
| nl_BE   | 4         | 0.08%   |
| en_IL   | 4         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3696      | 69.54%  |
| EFI  | 1619      | 30.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 5016      | 95.49%  |
| Btrfs   | 130       | 2.47%   |
| Overlay | 80        | 1.52%   |
| Xfs     | 19        | 0.36%   |
| Unknown | 7         | 0.13%   |
| Zfs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3924      | 74.23%  |
| GPT     | 1245      | 23.55%  |
| MBR     | 117       | 2.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5123      | 97.56%  |
| Yes       | 128       | 2.44%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4772      | 90.74%  |
| Yes       | 487       | 9.26%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1028      | 19.63%  |
| Dell                   | 914       | 17.46%  |
| Hewlett-Packard        | 723       | 13.81%  |
| ASUSTek Computer       | 605       | 11.55%  |
| Acer                   | 411       | 7.85%   |
| Apple                  | 311       | 5.94%   |
| System76               | 190       | 3.63%   |
| MSI                    | 174       | 3.32%   |
| Toshiba                | 103       | 1.97%   |
| Samsung Electronics    | 93        | 1.78%   |
| HUAWEI                 | 63        | 1.2%    |
| Sony                   | 50        | 0.95%   |
| Notebook               | 48        | 0.92%   |
| Google                 | 42        | 0.8%    |
| Alienware              | 41        | 0.78%   |
| Positivo               | 29        | 0.55%   |
| Fujitsu                | 29        | 0.55%   |
| Razer                  | 25        | 0.48%   |
| Timi                   | 19        | 0.36%   |
| Gigabyte Technology    | 19        | 0.36%   |
| PC Specialist          | 17        | 0.32%   |
| TUXEDO                 | 14        | 0.27%   |
| Unknown                | 14        | 0.27%   |
| LG Electronics         | 13        | 0.25%   |
| GPU Company            | 13        | 0.25%   |
| Framework              | 13        | 0.25%   |
| Medion                 | 12        | 0.23%   |
| Packard Bell           | 11        | 0.21%   |
| Avell High Performance | 11        | 0.21%   |
| Teclast                | 7         | 0.13%   |
| Eluktronics            | 7         | 0.13%   |
| Clevo                  | 7         | 0.13%   |
| Schenker               | 6         | 0.11%   |
| Panasonic              | 6         | 0.11%   |
| Intel                  | 6         | 0.11%   |
| HONOR                  | 6         | 0.11%   |
| Gateway                | 6         | 0.11%   |
| Chuwi                  | 5         | 0.1%    |
| SLIMBOOK               | 4         | 0.08%   |
| Quanta                 | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| System76 Oryx Pro                         | 46        | 0.88%   |
| System76 Lemur Pro                        | 39        | 0.74%   |
| Dell XPS 15 7590                          | 32        | 0.61%   |
| Unknown                                   | 29        | 0.55%   |
| System76 Gazelle                          | 27        | 0.52%   |
| Apple MacBookPro9,2                       | 26        | 0.5%    |
| System76 Galago Pro                       | 23        | 0.44%   |
| Apple MacBookPro12,1                      | 23        | 0.44%   |
| Dell XPS 15 9500                          | 22        | 0.42%   |
| Apple MacBookPro8,1                       | 22        | 0.42%   |
| HP Pavilion Notebook                      | 20        | 0.38%   |
| HP Notebook                               | 20        | 0.38%   |
| Apple MacBookAir7,2                       | 19        | 0.36%   |
| System76 Darter Pro                       | 18        | 0.34%   |
| HP Pavilion 15                            | 17        | 0.32%   |
| HP Pavilion dv6                           | 16        | 0.31%   |
| Apple MacBookAir6,2                       | 16        | 0.31%   |
| Dell XPS 15 9570                          | 15        | 0.29%   |
| Dell XPS 15 9560                          | 15        | 0.29%   |
| Dell Latitude E6420                       | 14        | 0.27%   |
| Apple MacBookPro7,1                       | 14        | 0.27%   |
| Lenovo IdeaPad S145-15API 81V7            | 13        | 0.25%   |
| Apple MacBookPro5,5                       | 13        | 0.25%   |
| Apple MacBookPro11,3                      | 13        | 0.25%   |
| Dell XPS 17 9700                          | 12        | 0.23%   |
| Dell Latitude E7240                       | 12        | 0.23%   |
| Lenovo IdeaPad 330-15IKB 81FE             | 11        | 0.21%   |
| Lenovo IdeaPad 330-15IKB 81DE             | 11        | 0.21%   |
| HP Pavilion Laptop 15-cw1xxx              | 11        | 0.21%   |
| HP Pavilion g6                            | 11        | 0.21%   |
| Dell XPS 13 9380                          | 11        | 0.21%   |
| Dell XPS 13 9370                          | 11        | 0.21%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 11        | 0.21%   |
| Apple MacBookPro10,1                      | 11        | 0.21%   |
| Apple MacBook5,1                          | 11        | 0.21%   |
| Acer Aspire E5-575G                       | 11        | 0.21%   |
| Samsung 340XAA/350XAA/550XAA              | 10        | 0.19%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 10        | 0.19%   |
| Framework Laptop                          | 10        | 0.19%   |
| Dell XPS 13 9310                          | 10        | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 508       | 9.7%    |
| Dell Inspiron      | 293       | 5.6%    |
| Lenovo IdeaPad     | 278       | 5.31%   |
| Acer Aspire        | 277       | 5.29%   |
| Dell Latitude      | 219       | 4.18%   |
| Dell XPS           | 196       | 3.74%   |
| HP Pavilion        | 173       | 3.3%    |
| HP EliteBook       | 114       | 2.18%   |
| HP Laptop          | 105       | 2.01%   |
| ASUS VivoBook      | 97        | 1.85%   |
| ASUS ROG           | 93        | 1.78%   |
| Toshiba Satellite  | 89        | 1.7%    |
| HP ProBook         | 81        | 1.55%   |
| Lenovo Legion      | 79        | 1.51%   |
| Dell Precision     | 67        | 1.28%   |
| Acer Nitro         | 51        | 0.97%   |
| Dell Vostro        | 50        | 0.95%   |
| ASUS ASUS          | 50        | 0.95%   |
| System76 Oryx      | 46        | 0.88%   |
| System76 Lemur     | 42        | 0.8%    |
| Acer Swift         | 40        | 0.76%   |
| Apple MacBookPro11 | 39        | 0.74%   |
| HP ENVY            | 36        | 0.69%   |
| ASUS Zenbook       | 35        | 0.67%   |
| Apple MacBookPro9  | 33        | 0.63%   |
| ASUS TUF           | 32        | 0.61%   |
| Apple MacBookPro8  | 31        | 0.59%   |
| HP OMEN            | 30        | 0.57%   |
| System76 Gazelle   | 29        | 0.55%   |
| HP ZBook           | 29        | 0.55%   |
| Unknown            | 29        | 0.55%   |
| Apple MacBookPro5  | 27        | 0.52%   |
| System76 Galago    | 26        | 0.5%    |
| Lenovo ThinkBook   | 26        | 0.5%    |
| Razer Blade        | 25        | 0.48%   |
| Apple MacBookPro12 | 23        | 0.44%   |
| Lenovo Yoga        | 22        | 0.42%   |
| Fujitsu LIFEBOOK   | 22        | 0.42%   |
| HP Notebook        | 20        | 0.38%   |
| Apple MacBookAir7  | 20        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 651       | 12.43%  |
| 2020    | 614       | 11.73%  |
| 2021    | 538       | 10.28%  |
| 2018    | 499       | 9.53%   |
| 2012    | 374       | 7.14%   |
| 2013    | 346       | 6.61%   |
| 2017    | 316       | 6.04%   |
| 2011    | 315       | 6.02%   |
| 2015    | 311       | 5.94%   |
| 2016    | 276       | 5.27%   |
| 2014    | 247       | 4.72%   |
| 2022    | 226       | 4.32%   |
| 2010    | 197       | 3.76%   |
| 2009    | 129       | 2.46%   |
| 2008    | 115       | 2.2%    |
| 2007    | 36        | 0.69%   |
| 2023    | 31        | 0.59%   |
| 2006    | 10        | 0.19%   |
| Unknown | 3         | 0.06%   |
| 2005    | 1         | 0.02%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5236      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5233      | 99.94%  |
| Enabled  | 3         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5074      | 96.91%  |
| Yes  | 162       | 3.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1542      | 29.2%   |
| 16.01-24.0  | 1186      | 22.46%  |
| 8.01-16.0   | 978       | 18.52%  |
| 3.01-4.0    | 776       | 14.69%  |
| 32.01-64.0  | 507       | 9.6%    |
| 64.01-256.0 | 109       | 2.06%   |
| 24.01-32.0  | 76        | 1.44%   |
| 1.01-2.0    | 71        | 1.34%   |
| 2.01-3.0    | 36        | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1763      | 30.82%  |
| 1.01-2.0   | 1332      | 23.29%  |
| 4.01-8.0   | 1200      | 20.98%  |
| 3.01-4.0   | 1063      | 18.58%  |
| 8.01-16.0  | 296       | 5.17%   |
| 16.01-24.0 | 41        | 0.72%   |
| 24.01-32.0 | 12        | 0.21%   |
| 0.51-1.0   | 12        | 0.21%   |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3724      | 69.86%  |
| 2      | 1369      | 25.68%  |
| 3      | 178       | 3.34%   |
| 0      | 27        | 0.51%   |
| 4      | 24        | 0.45%   |
| 5      | 7         | 0.13%   |
| 7      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3797      | 72.3%   |
| Yes       | 1455      | 27.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4167      | 79.09%  |
| No        | 1102      | 20.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5175      | 98.78%  |
| No        | 64        | 1.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4425      | 83.79%  |
| No        | 856       | 16.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1413      | 26.85%  |
| Brazil       | 535       | 10.17%  |
| Germany      | 314       | 5.97%   |
| UK           | 233       | 4.43%   |
| India        | 221       | 4.2%    |
| Canada       | 185       | 3.52%   |
| Italy        | 167       | 3.17%   |
| France       | 152       | 2.89%   |
| Australia    | 123       | 2.34%   |
| Netherlands  | 108       | 2.05%   |
| Russia       | 99        | 1.88%   |
| Spain        | 92        | 1.75%   |
| Sweden       | 87        | 1.65%   |
| Poland       | 83        | 1.58%   |
| Portugal     | 77        | 1.46%   |
| Mexico       | 76        | 1.44%   |
| Romania      | 58        | 1.1%    |
| Norway       | 56        | 1.06%   |
| Switzerland  | 50        | 0.95%   |
| Turkey       | 49        | 0.93%   |
| South Africa | 49        | 0.93%   |
| Philippines  | 43        | 0.82%   |
| Indonesia    | 41        | 0.78%   |
| Finland      | 40        | 0.76%   |
| Greece       | 38        | 0.72%   |
| Denmark      | 38        | 0.72%   |
| Argentina    | 38        | 0.72%   |
| Belgium      | 37        | 0.7%    |
| New Zealand  | 36        | 0.68%   |
| Austria      | 35        | 0.67%   |
| Czechia      | 33        | 0.63%   |
| Chile        | 29        | 0.55%   |
| Croatia      | 26        | 0.49%   |
| Malaysia     | 23        | 0.44%   |
| Hungary      | 23        | 0.44%   |
| Ireland      | 22        | 0.42%   |
| Bulgaria     | 22        | 0.42%   |
| Vietnam      | 21        | 0.4%    |
| Colombia     | 21        | 0.4%    |
| Japan        | 20        | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 61        | 1.11%   |
| Bengaluru      | 35        | 0.64%   |
| Milan          | 33        | 0.6%    |
| Brisbane       | 32        | 0.58%   |
| Sydney         | 29        | 0.53%   |
| Rio de Janeiro | 27        | 0.49%   |
| Melbourne      | 27        | 0.49%   |
| Paris          | 26        | 0.47%   |
| Moscow         | 26        | 0.47%   |
| Dallas         | 26        | 0.47%   |
| Vienna         | 25        | 0.45%   |
| New York       | 25        | 0.45%   |
| Warsaw         | 24        | 0.44%   |
| London         | 24        | 0.44%   |
| Madrid         | 23        | 0.42%   |
| Bucharest      | 23        | 0.42%   |
| Berlin         | 23        | 0.42%   |
| Oslo           | 22        | 0.4%    |
| Istanbul       | 22        | 0.4%    |
| Helsinki       | 22        | 0.4%    |
| Amsterdam      | 22        | 0.4%    |
| Athens         | 21        | 0.38%   |
| Los Angeles    | 20        | 0.36%   |
| Rome           | 19        | 0.35%   |
| Chicago        | 19        | 0.35%   |
| Auckland       | 19        | 0.35%   |
| Johannesburg   | 18        | 0.33%   |
| Zagreb         | 17        | 0.31%   |
| Mexico City    | 17        | 0.31%   |
| Lisbon         | 17        | 0.31%   |
| Fortaleza      | 17        | 0.31%   |
| Toronto        | 16        | 0.29%   |
| Stockholm      | 16        | 0.29%   |
| St Petersburg  | 16        | 0.29%   |
| Sofia          | 16        | 0.29%   |
| Denver         | 16        | 0.29%   |
| Zurich         | 15        | 0.27%   |
| Calgary        | 15        | 0.27%   |
| Brasília      | 15        | 0.27%   |
| Singapore      | 14        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1219      | 1659   | 18.11%  |
| WDC                            | 699       | 805    | 10.38%  |
| Seagate                        | 638       | 753    | 9.48%   |
| SanDisk                        | 495       | 647    | 7.35%   |
| Toshiba                        | 422       | 499    | 6.27%   |
| Kingston                       | 360       | 426    | 5.35%   |
| SK hynix                       | 333       | 423    | 4.95%   |
| Unknown                        | 307       | 375    | 4.56%   |
| Crucial                        | 233       | 275    | 3.46%   |
| Intel                          | 228       | 281    | 3.39%   |
| Micron Technology              | 192       | 218    | 2.85%   |
| HGST                           | 189       | 219    | 2.81%   |
| Apple                          | 156       | 167    | 2.32%   |
| Hitachi                        | 104       | 114    | 1.55%   |
| A-DATA Technology              | 97        | 117    | 1.44%   |
| Phison                         | 77        | 94     | 1.14%   |
| China                          | 58        | 68     | 0.86%   |
| KIOXIA                         | 56        | 66     | 0.83%   |
| PNY                            | 51        | 62     | 0.76%   |
| Micron/Crucial Technology      | 49        | 65     | 0.73%   |
| LITEON                         | 43        | 49     | 0.64%   |
| Silicon Motion                 | 42        | 52     | 0.62%   |
| Transcend                      | 36        | 41     | 0.53%   |
| LITEONIT                       | 32        | 45     | 0.48%   |
| ADATA Technology               | 24        | 33     | 0.36%   |
| SPCC                           | 21        | 22     | 0.31%   |
| Team                           | 20        | 24     | 0.3%    |
| Phison Electronics             | 20        | 22     | 0.3%    |
| JMicron Technology             | 19        | 26     | 0.28%   |
| Fujitsu                        | 19        | 20     | 0.28%   |
| Kingston Technology Company    | 18        | 19     | 0.27%   |
| KingSpec                       | 17        | 19     | 0.25%   |
| Union Memory (Shenzhen)        | 16        | 19     | 0.24%   |
| Solid State Storage Technology | 16        | 19     | 0.24%   |
| Patriot                        | 15        | 17     | 0.22%   |
| Unknown                        | 15        | 19     | 0.22%   |
| Netac                          | 14        | 16     | 0.21%   |
| OCZ                            | 13        | 13     | 0.19%   |
| Intenso                        | 13        | 17     | 0.19%   |
| Hewlett-Packard                | 13        | 15     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 110       | 1.56%   |
| Kingston SA400S37240G 240GB SSD                       | 94        | 1.33%   |
| Samsung NVMe SSD Drive 512GB                          | 80        | 1.13%   |
| HGST HTS721010A9E630 1TB                              | 78        | 1.11%   |
| Unknown MMC Card  64GB                                | 73        | 1.04%   |
| Samsung NVMe SSD Drive 1TB                            | 64        | 0.91%   |
| Toshiba MQ01ABD100 1TB                                | 61        | 0.87%   |
| SK hynix NVMe SSD Drive 512GB                         | 59        | 0.84%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 57        | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 56        | 0.79%   |
| Unknown MMC Card  32GB                                | 55        | 0.78%   |
| SanDisk NVMe SSD Drive 512GB                          | 53        | 0.75%   |
| Samsung NVMe SSD Drive 500GB                          | 52        | 0.74%   |
| Toshiba MQ04ABF100 1TB                                | 50        | 0.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 50        | 0.71%   |
| Intel NVMe SSD Drive 512GB                            | 47        | 0.67%   |
| SanDisk NVMe SSD Drive 1TB                            | 43        | 0.61%   |
| WDC WD10SPZX-24Z10 1TB                                | 41        | 0.58%   |
| Samsung NVMe SSD Drive 1024GB                         | 40        | 0.57%   |
| Seagate ST9500325AS 500GB                             | 38        | 0.54%   |
| SanDisk NVMe SSD Drive 256GB                          | 36        | 0.51%   |
| Samsung SSD 860 EVO 500GB                             | 36        | 0.51%   |
| Seagate ST500LT012-1DG142 500GB                       | 35        | 0.5%    |
| Seagate ST1000LM049-2GH172 1TB                        | 35        | 0.5%    |
| Kingston SA400S37480G 480GB SSD                       | 35        | 0.5%    |
| WDC WD10SPZX-21Z10T0 1TB                              | 33        | 0.47%   |
| Unknown MMC Card  128GB                               | 33        | 0.47%   |
| Crucial CT500MX500SSD1 500GB                          | 33        | 0.47%   |
| Crucial CT240BX500SSD1 240GB                          | 32        | 0.45%   |
| SK hynix NVMe SSD Drive 1024GB                        | 31        | 0.44%   |
| Samsung SSD 850 EVO 250GB                             | 31        | 0.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 31        | 0.44%   |
| Kingston SA400S37120G 120GB SSD                       | 31        | 0.44%   |
| SK hynix NVMe SSD Drive 256GB                         | 29        | 0.41%   |
| SanDisk NVMe SSD Drive 500GB                          | 29        | 0.41%   |
| HGST HTS541010A9E680 1TB                              | 29        | 0.41%   |
| Apple SSD SM0128G 121GB                               | 29        | 0.41%   |
| Toshiba NVMe SSD Drive 512GB                          | 28        | 0.4%    |
| Samsung SSD 860 EVO 1TB                               | 27        | 0.38%   |
| Toshiba MQ01ABF050 500GB                              | 26        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 611       | 710    | 35.86%  |
| WDC                 | 420       | 466    | 24.65%  |
| Toshiba             | 260       | 294    | 15.26%  |
| HGST                | 189       | 219    | 11.09%  |
| Hitachi             | 104       | 114    | 6.1%    |
| Samsung Electronics | 31        | 32     | 1.82%   |
| Unknown             | 26        | 28     | 1.53%   |
| Fujitsu             | 19        | 20     | 1.12%   |
| Apple               | 16        | 18     | 0.94%   |
| SABRENT             | 6         | 8      | 0.35%   |
| External            | 4         | 4      | 0.23%   |
| PHD 3.0             | 3         | 3      | 0.18%   |
| Intenso             | 3         | 6      | 0.18%   |
| ASMT                | 3         | 5      | 0.18%   |
| JMicron Technology  | 2         | 6      | 0.12%   |
| USB3.0              | 1         | 1      | 0.06%   |
| StoreJet            | 1         | 1      | 0.06%   |
| RSH-339             | 1         | 1      | 0.06%   |
| Inateck             | 1         | 1      | 0.06%   |
| HGST HDN            | 1         | 1      | 0.06%   |
| DAS                 | 1         | 4      | 0.06%   |
| Asm                 | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 482       | 638    | 21.2%   |
| Kingston            | 276       | 314    | 12.14%  |
| SanDisk             | 229       | 284    | 10.07%  |
| Crucial             | 215       | 257    | 9.45%   |
| WDC                 | 142       | 175    | 6.24%   |
| Apple               | 118       | 124    | 5.19%   |
| A-DATA Technology   | 63        | 74     | 2.77%   |
| Micron Technology   | 61        | 66     | 2.68%   |
| SK hynix            | 60        | 69     | 2.64%   |
| China               | 58        | 68     | 2.55%   |
| Toshiba             | 54        | 64     | 2.37%   |
| PNY                 | 49        | 60     | 2.15%   |
| Intel               | 44        | 48     | 1.93%   |
| LITEON              | 40        | 46     | 1.76%   |
| Transcend           | 34        | 39     | 1.5%    |
| LITEONIT            | 32        | 45     | 1.41%   |
| SPCC                | 19        | 20     | 0.84%   |
| KingSpec            | 17        | 19     | 0.75%   |
| Seagate             | 14        | 15     | 0.62%   |
| Patriot             | 14        | 16     | 0.62%   |
| Team                | 13        | 17     | 0.57%   |
| OCZ                 | 13        | 13     | 0.57%   |
| Netac               | 11        | 13     | 0.48%   |
| JMicron Technology  | 11        | 13     | 0.48%   |
| Hewlett-Packard     | 10        | 12     | 0.44%   |
| Lexar               | 9         | 9      | 0.4%    |
| Corsair             | 9         | 10     | 0.4%    |
| Intenso             | 8         | 8      | 0.35%   |
| Dogfish             | 8         | 11     | 0.35%   |
| Apacer              | 8         | 13     | 0.35%   |
| KingDian            | 7         | 8      | 0.31%   |
| BHT                 | 6         | 6      | 0.26%   |
| TO Exter            | 5         | 5      | 0.22%   |
| Plextor             | 5         | 7      | 0.22%   |
| Mushkin             | 5         | 6      | 0.22%   |
| GOODRAM             | 5         | 6      | 0.22%   |
| Gigabyte Technology | 5         | 7      | 0.22%   |
| ASMT                | 5         | 5      | 0.22%   |
| Teclast             | 4         | 4      | 0.18%   |
| Maxtor              | 4         | 4      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2243      | 3139   | 35.4%   |
| SSD     | 2106      | 2725   | 33.24%  |
| HDD     | 1647      | 1943   | 25.99%  |
| MMC     | 257       | 312    | 4.06%   |
| Unknown | 83        | 113    | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3281      | 4473   | 54.55%  |
| NVMe | 2239      | 3132   | 37.22%  |
| MMC  | 257       | 312    | 4.27%   |
| SAS  | 238       | 315    | 3.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2363      | 3046   | 63.61%  |
| 0.51-1.0   | 1189      | 1412   | 32.01%  |
| 1.01-2.0   | 150       | 191    | 4.04%   |
| 4.01-10.0  | 6         | 10     | 0.16%   |
| 3.01-4.0   | 5         | 6      | 0.13%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |
| 10.01-20.0 | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1804      | 33.33%  |
| 251-500        | 1538      | 28.42%  |
| 501-1000       | 1008      | 18.63%  |
| 1001-2000      | 361       | 6.67%   |
| 51-100         | 262       | 4.84%   |
| 1-20           | 126       | 2.33%   |
| 21-50          | 123       | 2.27%   |
| 2001-3000      | 85        | 1.57%   |
| More than 3000 | 69        | 1.27%   |
| Unknown        | 36        | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2181      | 38.4%   |
| 21-50          | 1262      | 22.22%  |
| 101-250        | 750       | 13.21%  |
| 51-100         | 737       | 12.98%  |
| 251-500        | 396       | 6.97%   |
| 501-1000       | 209       | 3.68%   |
| 1001-2000      | 70        | 1.23%   |
| Unknown        | 36        | 0.63%   |
| More than 3000 | 21        | 0.37%   |
| 2001-3000      | 17        | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 5         | 5      | 3.91%   |
| HGST HTS725050A7E630 500GB               | 5         | 8      | 3.91%   |
| Seagate ST1000LX015-1U7172 1TB           | 4         | 4      | 3.13%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 3.13%   |
| SK hynix PC711 HFS001TDE9X073N 1TB       | 3         | 3      | 2.34%   |
| Seagate ST500LT012-9WS142 500GB          | 3         | 3      | 2.34%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 2.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 3         | 3      | 2.34%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 5      | 2.34%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.34%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 2         | 2      | 1.56%   |
| Toshiba MK7559GSXP 752GB                 | 2         | 2      | 1.56%   |
| SK hynix HFS128G39TND-N210A 128GB SSD    | 2         | 2      | 1.56%   |
| Seagate ST9500325AS 500GB                | 2         | 3      | 1.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.56%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD      | 2         | 2      | 1.56%   |
| Kingston SUV400S37120G 120GB SSD         | 2         | 2      | 1.56%   |
| Crucial CT1000P1SSD8 1TB                 | 2         | 2      | 1.56%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD         | 1         | 1      | 0.78%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.78%   |
| WDC WDS100T2B0B-00YS70 1TB SSD           | 1         | 1      | 0.78%   |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 1      | 0.78%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.78%   |
| WDC WD5000LPCX-21VHAT0 500GB             | 1         | 1      | 0.78%   |
| WDC WD5000BPVT-22HXZT3 500GB             | 1         | 1      | 0.78%   |
| WDC WD5000BPVT-08HXZT3 500GB             | 1         | 1      | 0.78%   |
| WDC WD3200BEKX-75B7WT0 320GB             | 1         | 1      | 0.78%   |
| WDC WD3200BEKT-60PVMT0 320GB             | 1         | 1      | 0.78%   |
| WDC WD2500BEVT-22A23T0 208GB             | 1         | 1      | 0.78%   |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.78%   |
| WDC WD10SPZX-75Z10T1 1TB                 | 1         | 1      | 0.78%   |
| WDC WD10SPZX-24Z10 1TB                   | 1         | 1      | 0.78%   |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 1      | 0.78%   |
| WDC WD10SPCX-24HWST1 1TB                 | 1         | 1      | 0.78%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 0.78%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.78%   |
| WDC WD10JPVX-60JC3T0 1TB                 | 1         | 1      | 0.78%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB     | 1         | 1      | 0.78%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.78%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 2      | 0.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 29     | 21.88%  |
| WDC                 | 22        | 22     | 17.19%  |
| HGST                | 14        | 17     | 10.94%  |
| Toshiba             | 13        | 14     | 10.16%  |
| SK hynix            | 10        | 12     | 7.81%   |
| Samsung Electronics | 6         | 6      | 4.69%   |
| Hitachi             | 6         | 8      | 4.69%   |
| Kingston            | 5         | 5      | 3.91%   |
| Crucial             | 5         | 5      | 3.91%   |
| A-DATA Technology   | 5         | 5      | 3.91%   |
| Micron Technology   | 4         | 4      | 3.13%   |
| Intel               | 4         | 4      | 3.13%   |
| SanDisk             | 2         | 2      | 1.56%   |
| Team                | 1         | 1      | 0.78%   |
| Lexar               | 1         | 1      | 0.78%   |
| Leven               | 1         | 1      | 0.78%   |
| China               | 1         | 1      | 0.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 28        | 29     | 36.84%  |
| WDC     | 18        | 18     | 23.68%  |
| HGST    | 14        | 17     | 18.42%  |
| Toshiba | 10        | 10     | 13.16%  |
| Hitachi | 6         | 8      | 7.89%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 76        | 82     | 59.38%  |
| SSD  | 33        | 36     | 25.78%  |
| NVMe | 19        | 19     | 14.84%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4019      | 6301   | 73.38%  |
| Works    | 1329      | 1793   | 24.27%  |
| Malfunc  | 128       | 137    | 2.34%   |
| Failed   | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3478      | 52.95%  |
| Samsung Electronics              | 820       | 12.48%  |
| AMD                              | 641       | 9.76%   |
| SanDisk                          | 392       | 5.97%   |
| SK hynix                         | 272       | 4.14%   |
| Micron Technology                | 131       | 1.99%   |
| Toshiba America Info Systems     | 120       | 1.83%   |
| Phison Electronics               | 101       | 1.54%   |
| Kingston Technology Company      | 101       | 1.54%   |
| Nvidia                           | 83        | 1.26%   |
| Micron/Crucial Technology        | 62        | 0.94%   |
| ADATA Technology                 | 60        | 0.91%   |
| KIOXIA                           | 57        | 0.87%   |
| Silicon Motion                   | 52        | 0.79%   |
| Solid State Storage Technology   | 43        | 0.65%   |
| Union Memory (Shenzhen)          | 31        | 0.47%   |
| Apple                            | 22        | 0.33%   |
| Marvell Technology Group         | 19        | 0.29%   |
| Realtek Semiconductor            | 18        | 0.27%   |
| Seagate Technology               | 12        | 0.18%   |
| Shenzhen Longsys Electronics     | 10        | 0.15%   |
| Silicon Integrated Systems [SiS] | 8         | 0.12%   |
| Lite-On Technology               | 7         | 0.11%   |
| Lenovo                           | 6         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.08%   |
| JMicron Technology               | 4         | 0.06%   |
| ASMedia Technology               | 3         | 0.05%   |
| INNOGRIT                         | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Transcend                        | 1         | 0.02%   |
| Silicon Image                    | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 608       | 8.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 427       | 6.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 413       | 6%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 351       | 5.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 325       | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 294       | 4.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 256       | 3.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 203       | 2.95%   |
| Intel Volume Management Device NVMe RAID Controller                            | 167       | 2.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 160       | 2.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 153       | 2.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 132       | 1.92%   |
| Samsung NVMe SSD Controller 980                                                | 130       | 1.89%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 109       | 1.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 101       | 1.47%   |
| Intel SSD 660P Series                                                          | 100       | 1.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 100       | 1.45%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 99        | 1.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 98        | 1.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 93        | 1.35%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 92        | 1.34%   |
| Intel Comet Lake SATA AHCI Controller                                          | 90        | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 80        | 1.16%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 70        | 1.02%   |
| Phison E12 NVMe Controller                                                     | 54        | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 54        | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                            | 53        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 52        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 52        | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 50        | 0.73%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 50        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 50        | 0.73%   |
| Nvidia MCP79 AHCI Controller                                                   | 48        | 0.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 45        | 0.65%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 45        | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 44        | 0.64%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 39        | 0.57%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 38        | 0.55%   |
| SK hynix BC511 NVMe SSD                                                        | 36        | 0.52%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 36        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3650      | 55.54%  |
| NVMe | 2235      | 34.01%  |
| RAID | 523       | 7.96%   |
| IDE  | 164       | 2.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 4243      | 81.04%  |
| AMD    | 993       | 18.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 133       | 2.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 104       | 1.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 98        | 1.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 94        | 1.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 92        | 1.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 79        | 1.51%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 78        | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 76        | 1.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 72        | 1.37%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 71        | 1.36%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 67        | 1.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 66        | 1.26%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 62        | 1.18%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 58        | 1.11%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 58        | 1.11%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 57        | 1.09%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 55        | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 50        | 0.95%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 48        | 0.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 45        | 0.86%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 43        | 0.82%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 43        | 0.82%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 42        | 0.8%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 41        | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 39        | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 39        | 0.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 38        | 0.73%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 37        | 0.71%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 37        | 0.71%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 36        | 0.69%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 36        | 0.69%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 35        | 0.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 35        | 0.67%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 35        | 0.67%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 33        | 0.63%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 32        | 0.61%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 32        | 0.61%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 31        | 0.59%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 31        | 0.59%   |
| Intel 12th Gen Core i7-12700H                 | 31        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1535      | 29.32%  |
| Intel Core i5           | 1318      | 25.17%  |
| Other                   | 471       | 9%      |
| Intel Core i3           | 325       | 6.21%   |
| AMD Ryzen 7             | 282       | 5.39%   |
| AMD Ryzen 5             | 279       | 5.33%   |
| Intel Core 2 Duo        | 183       | 3.5%    |
| Intel Celeron           | 171       | 3.27%   |
| AMD Ryzen 9             | 67        | 1.28%   |
| Intel Pentium           | 61        | 1.17%   |
| AMD Ryzen 3             | 58        | 1.11%   |
| Intel Core i9           | 53        | 1.01%   |
| AMD A6                  | 51        | 0.97%   |
| AMD Ryzen 7 PRO         | 39        | 0.74%   |
| AMD A8                  | 39        | 0.74%   |
| Intel Pentium Dual-Core | 33        | 0.63%   |
| AMD A10                 | 31        | 0.59%   |
| AMD A4                  | 25        | 0.48%   |
| Intel Atom              | 19        | 0.36%   |
| Intel Core 2            | 17        | 0.32%   |
| Intel Xeon              | 13        | 0.25%   |
| Intel Pentium Dual      | 13        | 0.25%   |
| Intel Genuine           | 13        | 0.25%   |
| AMD E1                  | 13        | 0.25%   |
| Intel Core m3           | 12        | 0.23%   |
| AMD Athlon              | 12        | 0.23%   |
| AMD Ryzen 5 PRO         | 10        | 0.19%   |
| AMD E                   | 10        | 0.19%   |
| Intel Pentium Silver    | 8         | 0.15%   |
| AMD FX                  | 7         | 0.13%   |
| AMD E2                  | 7         | 0.13%   |
| Intel Core M            | 6         | 0.11%   |
| AMD Turion 64 X2 Mobile | 6         | 0.11%   |
| AMD A12                 | 6         | 0.11%   |
| Intel Core m5           | 5         | 0.1%    |
| AMD Athlon X2           | 5         | 0.1%    |
| Intel Celeron Dual-Core | 4         | 0.08%   |
| AMD C-60                | 4         | 0.08%   |
| AMD Phenom II           | 3         | 0.06%   |
| AMD V120                | 2         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2217      | 42.34%  |
| 4      | 1818      | 34.72%  |
| 6      | 544       | 10.39%  |
| 8      | 497       | 9.49%   |
| 14     | 59        | 1.13%   |
| 12     | 34        | 0.65%   |
| 10     | 26        | 0.5%    |
| 1      | 25        | 0.48%   |
| 16     | 10        | 0.19%   |
| 24     | 3         | 0.06%   |
| 7      | 1         | 0.02%   |
| 5      | 1         | 0.02%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5236      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4407      | 84.1%   |
| 1      | 833       | 15.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5229      | 99.87%  |
| Unknown        | 7         | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3518      | 65.57%  |
| 0x906ea    | 152       | 2.83%   |
| 0x806ea    | 108       | 2.01%   |
| 0x306a9    | 101       | 1.88%   |
| 0x806ec    | 98        | 1.83%   |
| 0x806c1    | 93        | 1.73%   |
| 0x206a7    | 92        | 1.71%   |
| 0x406e3    | 86        | 1.6%    |
| 0x40651    | 80        | 1.49%   |
| 0xa0652    | 75        | 1.4%    |
| 0x806e9    | 61        | 1.14%   |
| 0x306c3    | 57        | 1.06%   |
| 0x0a50000c | 56        | 1.04%   |
| 0x906e9    | 53        | 0.99%   |
| 0x08108102 | 46        | 0.86%   |
| 0x306d4    | 40        | 0.75%   |
| 0x08600106 | 38        | 0.71%   |
| 0x806d1    | 37        | 0.69%   |
| 0x1067a    | 35        | 0.65%   |
| 0x806eb    | 34        | 0.63%   |
| 0x506e3    | 34        | 0.63%   |
| 0x08108109 | 30        | 0.56%   |
| 0x906ed    | 28        | 0.52%   |
| 0x906a3    | 25        | 0.47%   |
| 0x08600104 | 25        | 0.47%   |
| 0x08608103 | 23        | 0.43%   |
| 0x20655    | 22        | 0.41%   |
| 0x706e5    | 20        | 0.37%   |
| 0x08600103 | 19        | 0.35%   |
| 0x06006705 | 17        | 0.32%   |
| 0x0810100b | 15        | 0.28%   |
| 0x706a1    | 13        | 0.24%   |
| 0x0a404102 | 13        | 0.24%   |
| 0x0a404101 | 13        | 0.24%   |
| 0x40661    | 11        | 0.21%   |
| 0x10676    | 11        | 0.21%   |
| 0x0a50000d | 10        | 0.19%   |
| 0x07030105 | 10        | 0.19%   |
| 0xa0660    | 9         | 0.17%   |
| 0x06001119 | 9         | 0.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1225      | 23.37%  |
| Haswell          | 464       | 8.85%   |
| SandyBridge      | 375       | 7.16%   |
| IvyBridge        | 354       | 6.75%   |
| Skylake          | 296       | 5.65%   |
| Unknown          | 252       | 4.81%   |
| TigerLake        | 240       | 4.58%   |
| Zen+             | 207       | 3.95%   |
| CometLake        | 204       | 3.89%   |
| Penryn           | 197       | 3.76%   |
| Broadwell        | 193       | 3.68%   |
| Zen 2            | 191       | 3.64%   |
| Zen 3            | 173       | 3.3%    |
| Westmere         | 150       | 2.86%   |
| Icelake          | 100       | 1.91%   |
| Silvermont       | 82        | 1.56%   |
| Core             | 74        | 1.41%   |
| Excavator        | 68        | 1.3%    |
| Goldmont plus    | 64        | 1.22%   |
| Alderlake Hybrid | 57        | 1.09%   |
| Zen              | 52        | 0.99%   |
| Puma             | 43        | 0.82%   |
| Piledriver       | 38        | 0.73%   |
| Bobcat           | 24        | 0.46%   |
| Goldmont         | 23        | 0.44%   |
| Nehalem          | 17        | 0.32%   |
| Jaguar           | 15        | 0.29%   |
| Steamroller      | 14        | 0.27%   |
| K10 Llano        | 13        | 0.25%   |
| K8 Hammer        | 12        | 0.23%   |
| K10              | 9         | 0.17%   |
| K8 & K10 hybrid  | 8         | 0.15%   |
| Bonnell          | 4         | 0.08%   |
| Tremont          | 3         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3855      | 55.04%  |
| Nvidia                           | 1894      | 27.04%  |
| AMD                              | 1248      | 17.82%  |
| Silicon Integrated Systems [SiS] | 6         | 0.09%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 342       | 4.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 341       | 4.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 326       | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 247       | 3.45%   |
| Intel UHD Graphics 620                                                                   | 231       | 3.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 225       | 3.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 207       | 2.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 184       | 2.57%   |
| AMD Renoir                                                                               | 181       | 2.53%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 167       | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 159       | 2.22%   |
| Intel HD Graphics 620                                                                    | 154       | 2.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 153       | 2.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 151       | 2.11%   |
| Intel HD Graphics 5500                                                                   | 135       | 1.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 133       | 1.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 129       | 1.8%    |
| Intel HD Graphics 630                                                                    | 121       | 1.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 115       | 1.6%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 89        | 1.24%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 83        | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 82        | 1.14%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 82        | 1.14%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 82        | 1.14%   |
| Intel HD Graphics 530                                                                    | 74        | 1.03%   |
| AMD Lucienne                                                                             | 73        | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 70        | 0.98%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 61        | 0.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 61        | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 60        | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 58        | 0.81%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 57        | 0.8%    |
| Nvidia GP108M [GeForce MX150]                                                            | 55        | 0.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 55        | 0.77%   |
| Nvidia TU117M                                                                            | 52        | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 48        | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 47        | 0.66%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 47        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 47        | 0.66%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 45        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2364      | 44.83%  |
| Intel + Nvidia     | 1295      | 24.56%  |
| 1 x AMD            | 710       | 13.46%  |
| 1 x Nvidia         | 341       | 6.47%   |
| AMD + Nvidia       | 235       | 4.46%   |
| Intel + AMD        | 201       | 3.81%   |
| 2 x AMD            | 104       | 1.97%   |
| 2 x Nvidia         | 10        | 0.19%   |
| 1 x SiS            | 6         | 0.11%   |
| Other              | 3         | 0.06%   |
| Intel + 2 x Nvidia | 2         | 0.04%   |
| 2 x Intel          | 1         | 0.02%   |
| 1 x S3 Graphics    | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3654      | 69.1%   |
| Proprietary | 1501      | 28.39%  |
| Unknown     | 133       | 2.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4019      | 75.45%  |
| 1.01-2.0   | 344       | 6.46%   |
| 3.01-4.0   | 317       | 5.95%   |
| 0.01-0.5   | 215       | 4.04%   |
| 5.01-6.0   | 188       | 3.53%   |
| 7.01-8.0   | 107       | 2.01%   |
| 0.51-1.0   | 95        | 1.78%   |
| 2.01-3.0   | 29        | 0.54%   |
| 8.01-16.0  | 13        | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1079      | 17.74%  |
| Chimei Innolux          | 893       | 14.69%  |
| LG Display              | 831       | 13.67%  |
| BOE                     | 805       | 13.24%  |
| Samsung Electronics     | 545       | 8.96%   |
| Apple                   | 261       | 4.29%   |
| Sharp                   | 222       | 3.65%   |
| Dell                    | 184       | 3.03%   |
| Goldstar                | 183       | 3.01%   |
| PANDA                   | 149       | 2.45%   |
| Chi Mei Optoelectronics | 97        | 1.6%    |
| Lenovo                  | 80        | 1.32%   |
| Acer                    | 64        | 1.05%   |
| AOC                     | 62        | 1.02%   |
| Hewlett-Packard         | 60        | 0.99%   |
| InfoVision              | 50        | 0.82%   |
| Philips                 | 48        | 0.79%   |
| BenQ                    | 45        | 0.74%   |
| CSO                     | 36        | 0.59%   |
| ASUSTek Computer        | 35        | 0.58%   |
| Ancor Communications    | 35        | 0.58%   |
| ViewSonic               | 22        | 0.36%   |
| TMX                     | 16        | 0.26%   |
| Sony                    | 14        | 0.23%   |
| LG Philips              | 14        | 0.23%   |
| Panasonic               | 13        | 0.21%   |
| Iiyama                  | 12        | 0.2%    |
| Vizio                   | 11        | 0.18%   |
| InnoLux Display         | 10        | 0.16%   |
| Sceptre Tech            | 9         | 0.15%   |
| Toshiba                 | 8         | 0.13%   |
| MSI                     | 8         | 0.13%   |
| JDI                     | 8         | 0.13%   |
| Vestel Elektronik       | 6         | 0.1%    |
| NEC Computers           | 5         | 0.08%   |
| LGD                     | 5         | 0.08%   |
| Hitachi                 | 5         | 0.08%   |
| HannStar                | 5         | 0.08%   |
| TCL                     | 4         | 0.07%   |
| RTK                     | 4         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 57        | 0.93%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 56        | 0.91%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 50        | 0.81%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 49        | 0.8%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 49        | 0.8%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 44        | 0.72%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 38        | 0.62%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 37        | 0.6%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 33        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 29        | 0.47%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 28        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 28        | 0.46%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch       | 26        | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 26        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 26        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 25        | 0.41%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 24        | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 23        | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 23        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 21        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 21        | 0.34%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 21        | 0.34%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 20        | 0.33%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                   | 18        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 18        | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 18        | 0.29%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 18        | 0.29%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 18        | 0.29%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 17        | 0.28%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 17        | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 17        | 0.28%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 17        | 0.28%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                      | 17        | 0.28%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch          | 16        | 0.26%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 16        | 0.26%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 16        | 0.26%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 16        | 0.26%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch                   | 15        | 0.24%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                   | 15        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 15        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2685      | 47.11%  |
| 1366x768 (WXGA)    | 1426      | 25.02%  |
| 3840x2160 (4K)     | 294       | 5.16%   |
| 1600x900 (HD+)     | 227       | 3.98%   |
| 2560x1440 (QHD)    | 205       | 3.6%    |
| 1280x800 (WXGA)    | 138       | 2.42%   |
| 1920x1200 (WUXGA)  | 112       | 1.97%   |
| 1440x900 (WXGA+)   | 103       | 1.81%   |
| 2560x1600          | 89        | 1.56%   |
| 2880x1800          | 71        | 1.25%   |
| 2560x1080          | 51        | 0.89%   |
| 3840x2400          | 37        | 0.65%   |
| 3440x1440          | 35        | 0.61%   |
| 1680x1050 (WSXGA+) | 35        | 0.61%   |
| 3200x1800 (QHD+)   | 19        | 0.33%   |
| 2160x1440          | 19        | 0.33%   |
| 1360x768           | 18        | 0.32%   |
| 1280x1024 (SXGA)   | 16        | 0.28%   |
| 2256x1504          | 15        | 0.26%   |
| 1920x540           | 13        | 0.23%   |
| 3072x1920          | 10        | 0.18%   |
| 3000x2000          | 10        | 0.18%   |
| 3840x1080          | 9         | 0.16%   |
| 3456x2160          | 6         | 0.11%   |
| 3200x2000          | 6         | 0.11%   |
| Unknown            | 6         | 0.11%   |
| 3840x1100          | 4         | 0.07%   |
| 2560x1700          | 3         | 0.05%   |
| 2304x1440          | 3         | 0.05%   |
| 800x1280           | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |
| 3840x1200          | 2         | 0.04%   |
| 2288x1287          | 2         | 0.04%   |
| 2240x1400          | 2         | 0.04%   |
| 1920x515           | 2         | 0.04%   |
| 1920x1280          | 2         | 0.04%   |
| 1680x945           | 2         | 0.04%   |
| 1280x720 (HD)      | 2         | 0.04%   |
| 1024x768 (XGA)     | 2         | 0.04%   |
| 1024x600           | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2552      | 42.03%  |
| 13      | 934       | 15.38%  |
| 14      | 685       | 11.28%  |
| 17      | 441       | 7.26%   |
| 27      | 210       | 3.46%   |
| 24      | 174       | 2.87%   |
| 23      | 149       | 2.45%   |
| 12      | 127       | 2.09%   |
| 21      | 113       | 1.86%   |
| 16      | 95        | 1.56%   |
| 31      | 90        | 1.48%   |
| 11      | 78        | 1.28%   |
| 34      | 75        | 1.24%   |
| 18      | 51        | 0.84%   |
| Unknown | 43        | 0.71%   |
| 19      | 34        | 0.56%   |
| 32      | 22        | 0.36%   |
| 84      | 21        | 0.35%   |
| 40      | 21        | 0.35%   |
| 22      | 18        | 0.3%    |
| 20      | 18        | 0.3%    |
| 72      | 15        | 0.25%   |
| 54      | 11        | 0.18%   |
| 48      | 10        | 0.16%   |
| 25      | 9         | 0.15%   |
| 26      | 8         | 0.13%   |
| 52      | 6         | 0.1%    |
| 35      | 6         | 0.1%    |
| 28      | 6         | 0.1%    |
| 46      | 5         | 0.08%   |
| 33      | 5         | 0.08%   |
| 10      | 5         | 0.08%   |
| 65      | 4         | 0.07%   |
| 49      | 4         | 0.07%   |
| 39      | 4         | 0.07%   |
| 29      | 4         | 0.07%   |
| 37      | 3         | 0.05%   |
| 47      | 2         | 0.03%   |
| 8       | 2         | 0.03%   |
| 99      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3721      | 61.75%  |
| 201-300        | 668       | 11.09%  |
| 351-400        | 530       | 8.8%    |
| 501-600        | 489       | 8.11%   |
| 401-500        | 223       | 3.7%    |
| 601-700        | 125       | 2.07%   |
| 701-800        | 103       | 1.71%   |
| 1001-1500      | 46        | 0.76%   |
| Unknown        | 43        | 0.71%   |
| 1501-2000      | 38        | 0.63%   |
| 801-900        | 32        | 0.53%   |
| 901-1000       | 3         | 0.05%   |
| 101-200        | 2         | 0.03%   |
| 1-100          | 2         | 0.03%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4465      | 84.31%  |
| 16/10   | 611       | 11.54%  |
| 21/9    | 89        | 1.68%   |
| 3/2     | 58        | 1.1%    |
| Unknown | 23        | 0.43%   |
| 5/4     | 19        | 0.36%   |
| 32/9    | 10        | 0.19%   |
| 4/3     | 8         | 0.15%   |
| 3.40    | 4         | 0.08%   |
| 6/5     | 2         | 0.04%   |
| 3.73    | 2         | 0.04%   |
| 3.20    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.63    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2542      | 41.94%  |
| 81-90          | 1305      | 21.53%  |
| 121-130        | 400       | 6.6%    |
| 201-250        | 384       | 6.34%   |
| 71-80          | 307       | 5.07%   |
| 301-350        | 217       | 3.58%   |
| 351-500        | 197       | 3.25%   |
| 61-70          | 120       | 1.98%   |
| 111-120        | 100       | 1.65%   |
| 51-60          | 82        | 1.35%   |
| 151-200        | 78        | 1.29%   |
| More than 1000 | 70        | 1.15%   |
| 251-300        | 55        | 0.91%   |
| 141-150        | 55        | 0.91%   |
| 501-1000       | 48        | 0.79%   |
| Unknown        | 43        | 0.71%   |
| 131-140        | 37        | 0.61%   |
| 91-100         | 12        | 0.2%    |
| 41-50          | 5         | 0.08%   |
| 1-40           | 4         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2626      | 44.2%   |
| 101-120       | 1640      | 27.6%   |
| 51-100        | 818       | 13.77%  |
| 161-240       | 474       | 7.98%   |
| More than 240 | 266       | 4.48%   |
| 1-50          | 74        | 1.25%   |
| Unknown       | 43        | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4157      | 77.53%  |
| 2     | 915       | 17.06%  |
| 0     | 170       | 3.17%   |
| 3     | 113       | 2.11%   |
| 4     | 7         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2860      | 33.84%  |
| Intel                             | 2807      | 33.22%  |
| Qualcomm Atheros                  | 1137      | 13.45%  |
| Broadcom                          | 573       | 6.78%   |
| Broadcom Limited                  | 162       | 1.92%   |
| MediaTek                          | 148       | 1.75%   |
| Marvell Technology Group          | 68        | 0.8%    |
| ASIX Electronics                  | 60        | 0.71%   |
| Ralink                            | 59        | 0.7%    |
| Nvidia                            | 58        | 0.69%   |
| TP-Link                           | 52        | 0.62%   |
| Samsung Electronics               | 42        | 0.5%    |
| Ralink Technology                 | 41        | 0.49%   |
| DisplayLink                       | 32        | 0.38%   |
| Dell                              | 30        | 0.35%   |
| Lenovo                            | 26        | 0.31%   |
| Xiaomi                            | 25        | 0.3%    |
| Qualcomm                          | 24        | 0.28%   |
| Sierra Wireless                   | 22        | 0.26%   |
| Ericsson Business Mobile Networks | 22        | 0.26%   |
| JMicron Technology                | 19        | 0.22%   |
| Hewlett-Packard                   | 15        | 0.18%   |
| Google                            | 15        | 0.18%   |
| ASUSTek Computer                  | 13        | 0.15%   |
| OnePlus Technology (Shenzhen)     | 12        | 0.14%   |
| NetGear                           | 11        | 0.13%   |
| Huawei Technologies               | 11        | 0.13%   |
| OPPO Electronics                  | 10        | 0.12%   |
| Motorola PCS                      | 10        | 0.12%   |
| D-Link                            | 9         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.09%   |
| Linksys                           | 6         | 0.07%   |
| Edimax Technology                 | 6         | 0.07%   |
| Apple                             | 6         | 0.07%   |
| Fibocom                           | 5         | 0.06%   |
| Qualcomm Atheros Communications   | 4         | 0.05%   |
| Microsoft                         | 4         | 0.05%   |
| Arduino SA                        | 3         | 0.04%   |
| U-Blox                            | 2         | 0.02%   |
| T & A Mobile Phones               | 2         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1822      | 18.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 440       | 4.42%   |
| Intel Wi-Fi 6 AX200                                               | 349       | 3.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 245       | 2.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 234       | 2.35%   |
| Intel Wireless 8265 / 8275                                        | 216       | 2.17%   |
| Intel Wi-Fi 6 AX201                                               | 183       | 1.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 183       | 1.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 173       | 1.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 173       | 1.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 172       | 1.73%   |
| Intel Wireless 7260                                               | 170       | 1.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 163       | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 154       | 1.55%   |
| Intel Wireless 7265                                               | 151       | 1.52%   |
| Intel Wireless 8260                                               | 133       | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 131       | 1.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 123       | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 121       | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 109       | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 107       | 1.07%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 100       | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 94        | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 93        | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                     | 83        | 0.83%   |
| Intel Wireless 3165                                               | 75        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 73        | 0.73%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 67        | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 66        | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 64        | 0.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 62        | 0.62%   |
| Intel Ethernet Connection I219-LM                                 | 61        | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 60        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 59        | 0.59%   |
| Intel Wireless 3160                                               | 59        | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 58        | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 56        | 0.56%   |
| Intel Wireless-AC 9260                                            | 54        | 0.54%   |
| Intel Ethernet Connection I217-LM                                 | 53        | 0.53%   |
| Intel Centrino Ultimate-N 6300                                    | 53        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2711      | 49.71%  |
| Qualcomm Atheros                      | 950       | 17.42%  |
| Realtek Semiconductor                 | 744       | 13.64%  |
| Broadcom                              | 489       | 8.97%   |
| MediaTek                              | 144       | 2.64%   |
| Broadcom Limited                      | 130       | 2.38%   |
| Ralink                                | 59        | 1.08%   |
| TP-Link                               | 45        | 0.83%   |
| Ralink Technology                     | 41        | 0.75%   |
| Dell                                  | 25        | 0.46%   |
| Sierra Wireless                       | 22        | 0.4%    |
| Qualcomm                              | 20        | 0.37%   |
| ASUSTek Computer                      | 11        | 0.2%    |
| NetGear                               | 10        | 0.18%   |
| D-Link                                | 9         | 0.17%   |
| Hewlett-Packard                       | 6         | 0.11%   |
| Edimax Technology                     | 6         | 0.11%   |
| Fibocom                               | 5         | 0.09%   |
| Qualcomm Atheros Communications       | 4         | 0.07%   |
| Microsoft                             | 3         | 0.06%   |
| Linksys                               | 3         | 0.06%   |
| Ericsson Business Mobile Networks     | 3         | 0.06%   |
| D-Link System                         | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| ZyDAS                                 | 1         | 0.02%   |
| Wilocity                              | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Chu Yuen Enterprise                   | 1         | 0.02%   |
| Arduino SA                            | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 349       | 6.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 245       | 4.46%   |
| Intel Wireless 8265 / 8275                                     | 216       | 3.94%   |
| Intel Wi-Fi 6 AX201                                            | 183       | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 173       | 3.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 173       | 3.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 172       | 3.13%   |
| Intel Wireless 7260                                            | 170       | 3.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 163       | 2.97%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 154       | 2.81%   |
| Intel Wireless 7265                                            | 151       | 2.75%   |
| Intel Wireless 8260                                            | 133       | 2.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 131       | 2.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 123       | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 121       | 2.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 109       | 1.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 107       | 1.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 100       | 1.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 94        | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 93        | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                  | 83        | 1.51%   |
| Intel Wireless 3165                                            | 75        | 1.37%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 67        | 1.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 66        | 1.2%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 62        | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 60        | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 59        | 1.08%   |
| Intel Wireless 3160                                            | 59        | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 58        | 1.06%   |
| Intel Wireless-AC 9260                                         | 54        | 0.98%   |
| Intel Centrino Ultimate-N 6300                                 | 53        | 0.97%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 53        | 0.97%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 50        | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 49        | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 49        | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 45        | 0.82%   |
| Intel Centrino Advanced-N 6235                                 | 43        | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 41        | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 41        | 0.75%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 35        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2577      | 59.01%  |
| Intel                            | 827       | 18.94%  |
| Qualcomm Atheros                 | 301       | 6.89%   |
| Broadcom                         | 193       | 4.42%   |
| Marvell Technology Group         | 68        | 1.56%   |
| ASIX Electronics                 | 60        | 1.37%   |
| Nvidia                           | 58        | 1.33%   |
| Samsung Electronics              | 41        | 0.94%   |
| Broadcom Limited                 | 36        | 0.82%   |
| DisplayLink                      | 32        | 0.73%   |
| Lenovo                           | 26        | 0.6%    |
| Xiaomi                           | 25        | 0.57%   |
| JMicron Technology               | 19        | 0.44%   |
| Google                           | 15        | 0.34%   |
| OnePlus Technology (Shenzhen)    | 11        | 0.25%   |
| OPPO Electronics                 | 10        | 0.23%   |
| Silicon Integrated Systems [SiS] | 8         | 0.18%   |
| Huawei Technologies              | 8         | 0.18%   |
| TP-Link                          | 7         | 0.16%   |
| Motorola PCS                     | 7         | 0.16%   |
| Apple                            | 5         | 0.11%   |
| Qualcomm                         | 4         | 0.09%   |
| MediaTek                         | 3         | 0.07%   |
| Linksys                          | 3         | 0.07%   |
| Hewlett-Packard                  | 3         | 0.07%   |
| T & A Mobile Phones              | 2         | 0.05%   |
| LSI                              | 2         | 0.05%   |
| LG Electronics                   | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| ASUSTek Computer                 | 2         | 0.05%   |
| Aquantia                         | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| Research In Motion               | 1         | 0.02%   |
| NTmore                           | 1         | 0.02%   |
| NetGear                          | 1         | 0.02%   |
| Microsoft                        | 1         | 0.02%   |
| Foxconn / Hon Hai                | 1         | 0.02%   |
| Cypress Semiconductor            | 1         | 0.02%   |
| Attansic Technology              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1822      | 41.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 440       | 9.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 234       | 5.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 183       | 4.14%   |
| Intel Ethernet Connection (4) I219-LM                             | 73        | 1.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 64        | 1.45%   |
| Intel Ethernet Connection I219-LM                                 | 61        | 1.38%   |
| Intel Ethernet Connection I218-LM                                 | 56        | 1.27%   |
| Intel Ethernet Connection I217-LM                                 | 53        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 51        | 1.15%   |
| ASIX AX88179 Gigabit Ethernet                                     | 49        | 1.11%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 44        | 1%      |
| Nvidia MCP79 Ethernet                                             | 44        | 1%      |
| Intel Ethernet Connection (3) I218-LM                             | 41        | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 39        | 0.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 37        | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 34        | 0.77%   |
| Intel Ethernet Connection (4) I219-V                              | 34        | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 33        | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 31        | 0.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 29        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 29        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 29        | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 24        | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 22        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 22        | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 22        | 0.5%    |
| Intel 82567LM Gigabit Network Connection                          | 22        | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21        | 0.48%   |
| Intel Ethernet Connection (6) I219-V                              | 20        | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 20        | 0.45%   |
| Intel Ethernet Connection (13) I219-V                             | 20        | 0.45%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 20        | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 19        | 0.43%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 19        | 0.43%   |
| Intel Ethernet Connection I219-V                                  | 19        | 0.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 18        | 0.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 18        | 0.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 17        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5178      | 55.17%  |
| Ethernet | 4154      | 44.26%  |
| Modem    | 40        | 0.43%   |
| Unknown  | 14        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4407      | 78.98%  |
| Ethernet | 1173      | 21.02%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3777      | 72.08%  |
| 1     | 1390      | 26.53%  |
| 0     | 40        | 0.76%   |
| 3     | 33        | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4150      | 78.2%   |
| Yes  | 1157      | 21.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2287      | 51.31%  |
| Qualcomm Atheros Communications | 425       | 9.54%   |
| Realtek Semiconductor           | 387       | 8.68%   |
| Apple                           | 279       | 6.26%   |
| IMC Networks                    | 231       | 5.18%   |
| Lite-On Technology              | 204       | 4.58%   |
| Broadcom                        | 195       | 4.38%   |
| Foxconn / Hon Hai               | 143       | 3.21%   |
| Dell                            | 67        | 1.5%    |
| Cambridge Silicon Radio         | 42        | 0.94%   |
| Realtek                         | 33        | 0.74%   |
| Toshiba                         | 30        | 0.67%   |
| Ralink                          | 29        | 0.65%   |
| Hewlett-Packard                 | 29        | 0.65%   |
| ASUSTek Computer                | 15        | 0.34%   |
| Foxconn International           | 11        | 0.25%   |
| Ralink Technology               | 8         | 0.18%   |
| Alps Electric                   | 7         | 0.16%   |
| MediaTek                        | 5         | 0.11%   |
| Smart Modular Technologies      | 4         | 0.09%   |
| Askey Computer                  | 4         | 0.09%   |
| USI                             | 3         | 0.07%   |
| Taiyo Yuden                     | 3         | 0.07%   |
| Qcom                            | 3         | 0.07%   |
| Opticis                         | 3         | 0.07%   |
| TP-Link                         | 2         | 0.04%   |
| Fujitsu                         | 2         | 0.04%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| Actions                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 787       | 17.65%  |
| Intel AX201 Bluetooth                               | 464       | 10.41%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 367       | 8.23%   |
| Intel AX200 Bluetooth                               | 343       | 7.69%   |
| Realtek Bluetooth Radio                             | 245       | 5.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 235       | 5.27%   |
| Apple Bluetooth Host Controller                     | 161       | 3.61%   |
| Intel Bluetooth Device                              | 117       | 2.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 105       | 2.35%   |
| Apple Bluetooth USB Host Controller                 | 83        | 1.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 74        | 1.66%   |
| IMC Networks Bluetooth Radio                        | 74        | 1.66%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 67        | 1.5%    |
| IMC Networks Wireless_Device                        | 62        | 1.39%   |
| Intel AX210 Bluetooth                               | 56        | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 55        | 1.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 53        | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 48        | 1.08%   |
| IMC Networks Bluetooth Device                       | 46        | 1.03%   |
| Lite-On Bluetooth Device                            | 45        | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 44        | 0.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 42        | 0.94%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 41        | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 40        | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 38        | 0.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 33        | 0.74%   |
| Ralink RT3290 Bluetooth                             | 29        | 0.65%   |
| Realtek 802.11ac WLAN Adapter                       | 25        | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.56%   |
| Dell DW375 Bluetooth Module                         | 24        | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 23        | 0.52%   |
| Lite-On Wireless_Device                             | 22        | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 20        | 0.45%   |
| Apple Bluetooth HCI                                 | 20        | 0.45%   |
| Foxconn / Hon Hai Wireless_Device                   | 19        | 0.43%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 19        | 0.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 18        | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 18        | 0.4%    |
| Dell BCM20702A0 Bluetooth Module                    | 16        | 0.36%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 4140      | 60.21%  |
| Nvidia                                          | 1197      | 17.41%  |
| AMD                                             | 1079      | 15.69%  |
| C-Media Electronics                             | 55        | 0.8%    |
| Logitech                                        | 46        | 0.67%   |
| Realtek Semiconductor                           | 42        | 0.61%   |
| Lenovo                                          | 27        | 0.39%   |
| JMTek                                           | 24        | 0.35%   |
| GN Netcom                                       | 22        | 0.32%   |
| Kingston Technology                             | 18        | 0.26%   |
| Apple                                           | 17        | 0.25%   |
| Texas Instruments                               | 15        | 0.22%   |
| Generalplus Technology                          | 15        | 0.22%   |
| Sony                                            | 11        | 0.16%   |
| Razer USA                                       | 11        | 0.16%   |
| Hewlett-Packard                                 | 11        | 0.16%   |
| Corsair                                         | 11        | 0.16%   |
| Plantronics                                     | 10        | 0.15%   |
| SteelSeries ApS                                 | 9         | 0.13%   |
| Silicon Integrated Systems [SiS]                | 8         | 0.12%   |
| Focusrite-Novation                              | 7         | 0.1%    |
| Creative Technology                             | 5         | 0.07%   |
| ASUSTek Computer                                | 5         | 0.07%   |
| Sennheiser Communications                       | 4         | 0.06%   |
| FiiO Electronics Technology                     | 4         | 0.06%   |
| DSEA A/S                                        | 4         | 0.06%   |
| Yamaha                                          | 3         | 0.04%   |
| Tenx Technology                                 | 3         | 0.04%   |
| Samson Technologies                             | 3         | 0.04%   |
| No brand                                        | 3         | 0.04%   |
| GYROCOM C&C                                     | 3         | 0.04%   |
| Blue Microphones                                | 3         | 0.04%   |
| XMOS                                            | 2         | 0.03%   |
| Turtle Beach                                    | 2         | 0.03%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.03%   |
| TerraTec Electronic                             | 2         | 0.03%   |
| Pioneer DJ                                      | 2         | 0.03%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.03%   |
| CMX Systems                                     | 2         | 0.03%   |
| Bose                                            | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 723       | 8.68%   |
| Intel Sunrise Point-LP HD Audio                                            | 608       | 7.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 402       | 4.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 372       | 4.47%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 331       | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 325       | 3.9%    |
| Intel 8 Series HD Audio Controller                                         | 249       | 2.99%   |
| Intel Haswell-ULT HD Audio Controller                                      | 247       | 2.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 240       | 2.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 226       | 2.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 218       | 2.62%   |
| Intel Broadwell-U Audio Controller                                         | 193       | 2.32%   |
| Intel Comet Lake PCH cAVS                                                  | 187       | 2.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 185       | 2.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 169       | 2.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 167       | 2.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 161       | 1.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 152       | 1.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 151       | 1.81%   |
| Nvidia TU106 High Definition Audio Controller                              | 137       | 1.64%   |
| Intel CM238 HD Audio Controller                                            | 135       | 1.62%   |
| AMD FCH Azalia Controller                                                  | 134       | 1.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 117       | 1.4%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 111       | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 97        | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 93        | 1.12%   |
| Nvidia GA106 High Definition Audio Controller                              | 90        | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 88        | 1.06%   |
| Nvidia GA104 High Definition Audio Controller                              | 80        | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                   | 79        | 0.95%   |
| Nvidia Audio device                                                        | 78        | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 71        | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 67        | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 64        | 0.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 64        | 0.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 58        | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 56        | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                         | 52        | 0.62%   |
| Nvidia MCP79 High Definition Audio                                         | 48        | 0.58%   |
| AMD High Definition Audio Controller                                       | 47        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 515       | 29.34%  |
| SK hynix            | 401       | 22.85%  |
| Micron Technology   | 242       | 13.79%  |
| Kingston            | 142       | 8.09%   |
| Crucial             | 97        | 5.53%   |
| Unknown             | 56        | 3.19%   |
| A-DATA Technology   | 39        | 2.22%   |
| Smart               | 33        | 1.88%   |
| Ramaxel Technology  | 28        | 1.6%    |
| Corsair             | 27        | 1.54%   |
| Goldkey             | 21        | 1.2%    |
| Elpida              | 21        | 1.2%    |
| Neo Forza           | 19        | 1.08%   |
| G.Skill             | 16        | 0.91%   |
| Unknown (ABCD)      | 11        | 0.63%   |
| Unknown             | 11        | 0.63%   |
| Smart Brazil        | 10        | 0.57%   |
| Team                | 8         | 0.46%   |
| Teikon              | 6         | 0.34%   |
| Nanya Technology    | 6         | 0.34%   |
| Apacer              | 5         | 0.28%   |
| PNY                 | 4         | 0.23%   |
| Patriot             | 3         | 0.17%   |
| High Bridge         | 3         | 0.17%   |
| GSkill              | 3         | 0.17%   |
| Avant               | 3         | 0.17%   |
| Transcend           | 2         | 0.11%   |
| Timetec             | 2         | 0.11%   |
| GOODRAM             | 2         | 0.11%   |
| Gold Key            | 2         | 0.11%   |
| CSX                 | 2         | 0.11%   |
| ChangXin Memory     | 2         | 0.11%   |
| Unknown (8A02)      | 1         | 0.06%   |
| Unknown (898F)      | 1         | 0.06%   |
| Unknown (09B6)      | 1         | 0.06%   |
| Unknown (09A4)      | 1         | 0.06%   |
| Silicon Power       | 1         | 0.06%   |
| RZX                 | 1         | 0.06%   |
| PUSKILL             | 1         | 0.06%   |
| Multilaser          | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 48        | 2.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 30        | 1.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 26        | 1.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 1.31%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 19        | 1.03%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 1.03%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.98%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 18        | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 18        | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.92%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.92%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.92%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 0.82%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.82%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 14        | 0.76%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.71%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 13        | 0.71%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.65%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 0.65%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 11        | 0.6%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.6%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.6%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.6%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.6%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 0.6%    |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.6%    |
| Unknown                                                          | 11        | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.54%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.54%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 10        | 0.54%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 10        | 0.54%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 9         | 0.49%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 9         | 0.49%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.49%   |
| Neo Forza RAM NMSO432F82-3200E 32GB SODIMM DDR4 3200MT/s         | 9         | 0.49%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 961       | 65.51%  |
| DDR3    | 282       | 19.22%  |
| LPDDR4  | 74        | 5.04%   |
| LPDDR3  | 64        | 4.36%   |
| DDR5    | 42        | 2.86%   |
| LPDDR5  | 25        | 1.7%    |
| DDR2    | 10        | 0.68%   |
| SDRAM   | 5         | 0.34%   |
| Unknown | 4         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1285      | 86.07%  |
| Row Of Chips | 189       | 12.66%  |
| Chip         | 12        | 0.8%    |
| DIMM         | 4         | 0.27%   |
| Unknown      | 3         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 727       | 45.38%  |
| 4096  | 375       | 23.41%  |
| 16384 | 331       | 20.66%  |
| 32768 | 82        | 5.12%   |
| 2048  | 77        | 4.81%   |
| 1024  | 10        | 0.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 456       | 28.54%  |
| 3200    | 392       | 24.53%  |
| 1600    | 227       | 14.21%  |
| 2400    | 137       | 8.57%   |
| 2133    | 93        | 5.82%   |
| 4800    | 39        | 2.44%   |
| 4267    | 36        | 2.25%   |
| 1334    | 32        | 2%      |
| 3266    | 26        | 1.63%   |
| 6400    | 25        | 1.56%   |
| 1867    | 23        | 1.44%   |
| 1333    | 21        | 1.31%   |
| 8400    | 18        | 1.13%   |
| 4266    | 13        | 0.81%   |
| 1067    | 11        | 0.69%   |
| 800     | 9         | 0.56%   |
| 3733    | 7         | 0.44%   |
| 1866    | 5         | 0.31%   |
| 2933    | 4         | 0.25%   |
| 667     | 4         | 0.25%   |
| 4199    | 3         | 0.19%   |
| Unknown | 3         | 0.19%   |
| 5600    | 2         | 0.13%   |
| 3000    | 2         | 0.13%   |
| 2048    | 2         | 0.13%   |
| 1066    | 2         | 0.13%   |
| 5200    | 1         | 0.06%   |
| 3466    | 1         | 0.06%   |
| 3400    | 1         | 0.06%   |
| 3333    | 1         | 0.06%   |
| 1200    | 1         | 0.06%   |
| 666     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 29.63%  |
| Seiko Epson         | 5         | 18.52%  |
| Canon               | 5         | 18.52%  |
| Brother Industries  | 4         | 14.81%  |
| Samsung Electronics | 2         | 7.41%   |
| Xerox               | 1         | 3.7%    |
| MIIIW               | 1         | 3.7%    |
| ICS Advent          | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung M2020 Series            | 2         | 7.41%   |
| Canon PIXMA MX920 Series        | 2         | 7.41%   |
| Xerox B215                      | 1         | 3.7%    |
| Seiko Epson WF-3520 Series      | 1         | 3.7%    |
| Seiko Epson L6160 Series        | 1         | 3.7%    |
| Seiko Epson L3110 Series        | 1         | 3.7%    |
| Seiko Epson L132 Series         | 1         | 3.7%    |
| Seiko Epson ET-2700 Series      | 1         | 3.7%    |
| MIIIW MW Keyboard Air Mini      | 1         | 3.7%    |
| ICS Advent Parallel Adapter     | 1         | 3.7%    |
| HP OfficeJet 3830 series        | 1         | 3.7%    |
| HP Ink Tank Wireless 410 series | 1         | 3.7%    |
| HP ENVY Photo 7800 series       | 1         | 3.7%    |
| HP ENVY 4520 series             | 1         | 3.7%    |
| HP Deskjet 3050 J610 series     | 1         | 3.7%    |
| HP Deskjet 2540 series          | 1         | 3.7%    |
| HP Deskjet 2050 J510            | 1         | 3.7%    |
| HP Color LaserJet CP2025dn      | 1         | 3.7%    |
| Canon GX7000 series             | 1         | 3.7%    |
| Canon G4010 series              | 1         | 3.7%    |
| Canon E400 series               | 1         | 3.7%    |
| Brother HL-L2370DW series       | 1         | 3.7%    |
| Brother HL-L2320D series        | 1         | 3.7%    |
| Brother HL-3170CDW series       | 1         | 3.7%    |
| Brother HL-2270DW Laser Printer | 1         | 3.7%    |

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
| Chicony Electronics                    | 1107      | 23.59%  |
| IMC Networks                           | 511       | 10.89%  |
| Microdia                               | 467       | 9.95%   |
| Bison Electronics                      | 414       | 8.82%   |
| Realtek Semiconductor                  | 388       | 8.27%   |
| Sunplus Innovation Technology          | 258       | 5.5%    |
| Quanta                                 | 241       | 5.14%   |
| Apple                                  | 211       | 4.5%    |
| Cheng Uei Precision Industry (Foxlink) | 163       | 3.47%   |
| Suyin                                  | 127       | 2.71%   |
| Syntek                                 | 114       | 2.43%   |
| Lite-On Technology                     | 96        | 2.05%   |
| Luxvisions Innotech Limited            | 80        | 1.71%   |
| Acer                                   | 74        | 1.58%   |
| Silicon Motion                         | 66        | 1.41%   |
| Logitech                               | 63        | 1.34%   |
| Ricoh                                  | 39        | 0.83%   |
| Alcor Micro                            | 33        | 0.7%    |
| Samsung Electronics                    | 26        | 0.55%   |
| Sonix Technology                       | 24        | 0.51%   |
| SunplusIT                              | 15        | 0.32%   |
| ALi                                    | 14        | 0.3%    |
| Primax Electronics                     | 13        | 0.28%   |
| Lenovo                                 | 11        | 0.23%   |
| Importek                               | 11        | 0.23%   |
| Z-Star Microelectronics                | 10        | 0.21%   |
| Microsoft                              | 10        | 0.21%   |
| DigiTech                               | 10        | 0.21%   |
| Intel                                  | 8         | 0.17%   |
| OmniVision Technologies                | 6         | 0.13%   |
| Generalplus Technology                 | 6         | 0.13%   |
| Razer USA                              | 5         | 0.11%   |
| icSpring                               | 5         | 0.11%   |
| Tobii Technology AB                    | 4         | 0.09%   |
| MacroSilicon                           | 4         | 0.09%   |
| Foxconn / Hon Hai                      | 4         | 0.09%   |
| AVerMedia Technologies                 | 4         | 0.09%   |
| Unknown                                | 3         | 0.06%   |
| HRY                                    | 3         | 0.06%   |
| Alpha Imaging Technology               | 3         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 249       | 5.28%   |
| Chicony Integrated Camera                           | 212       | 4.5%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 170       | 3.61%   |
| Realtek Integrated_Webcam_HD                        | 155       | 3.29%   |
| IMC Networks Integrated Camera                      | 140       | 2.97%   |
| Chicony HD Webcam                                   | 128       | 2.72%   |
| Chicony USB2.0 Camera                               | 104       | 2.21%   |
| Bison BisonCam,NB Pro                               | 99        | 2.1%    |
| Bison Integrated Camera                             | 82        | 1.74%   |
| Sunplus Integrated_Webcam_HD                        | 77        | 1.63%   |
| Syntek Integrated Camera                            | 72        | 1.53%   |
| Apple Built-in iSight                               | 69        | 1.46%   |
| Apple FaceTime HD Camera                            | 65        | 1.38%   |
| Bison HD Webcam                                     | 59        | 1.25%   |
| Quanta HD User Facing                               | 58        | 1.23%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 50        | 1.06%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 46        | 0.98%   |
| Bison BisonCam, NB Pro                              | 38        | 0.81%   |
| Lite-On Integrated Camera                           | 37        | 0.78%   |
| Microdia Integrated Webcam                          | 36        | 0.76%   |
| Chicony USB 2.0 Camera                              | 36        | 0.76%   |
| Chicony HD User Facing                              | 36        | 0.76%   |
| Quanta HD Webcam                                    | 34        | 0.72%   |
| Chicony Integrated Camera (1280x720@30)             | 34        | 0.72%   |
| Chicony HP HD Camera                                | 34        | 0.72%   |
| Bison SunplusIT Integrated Camera                   | 34        | 0.72%   |
| Sunplus HD WebCam                                   | 33        | 0.7%    |
| Chicony TOSHIBA Web Camera - HD                     | 33        | 0.7%    |
| Chicony USB2.0 HD UVC WebCam                        | 32        | 0.68%   |
| Sunplus Asus Webcam                                 | 31        | 0.66%   |
| Quanta HP TrueVision HD Camera                      | 30        | 0.64%   |
| Realtek Integrated Webcam                           | 29        | 0.62%   |
| Chicony USB2.0 VGA UVC WebCam                       | 29        | 0.62%   |
| Microdia Laptop_Integrated_Webcam_HD                | 28        | 0.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 27        | 0.57%   |
| Chicony HP Truevision HD camera                     | 27        | 0.57%   |
| Realtek USB Camera                                  | 26        | 0.55%   |
| Chicony Integrated IR Camera                        | 26        | 0.55%   |
| Chicony HP Wide Vision HD Camera                    | 26        | 0.55%   |
| Samsung Galaxy series, misc. (MTP mode)             | 23        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 283       | 31.03%  |
| Validity Sensors                   | 277       | 30.37%  |
| Shenzhen Goodix Technology         | 162       | 17.76%  |
| Upek                               | 51        | 5.59%   |
| Elan Microelectronics              | 51        | 5.59%   |
| LighTuning Technology              | 38        | 4.17%   |
| AuthenTec                          | 29        | 3.18%   |
| STMicroelectronics                 | 7         | 0.77%   |
| Focal-systems.Corp                 | 5         | 0.55%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.44%   |
| HOLTEK                             | 3         | 0.33%   |
| Samsung Electronics                | 1         | 0.11%   |
| DigitalPersona                     | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 85        | 9.32%   |
| Shenzhen Goodix  Fingerprint Device                                        | 78        | 8.55%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 63        | 6.91%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 56        | 6.14%   |
| Shenzhen Goodix FingerPrint                                                | 50        | 5.48%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 46        | 5.04%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 40        | 4.39%   |
| Shenzhen Goodix Fingerprint Reader                                         | 34        | 3.73%   |
| Elan ELAN:Fingerprint                                                      | 31        | 3.4%    |
| Synaptics UWP WBDI                                                         | 28        | 3.07%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 21        | 2.3%    |
| Validity Sensors Synaptics WBDI                                            | 21        | 2.3%    |
| Validity Sensors Fingerprint scanner                                       | 21        | 2.3%    |
| Synaptics WBDI Device                                                      | 21        | 2.3%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 2.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 20        | 2.19%   |
| Validity Sensors VFS491                                                    | 19        | 2.08%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 19        | 2.08%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 17        | 1.86%   |
| Unknown                                                                    | 17        | 1.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 16        | 1.75%   |
| Elan ELAN:ARM-M4                                                           | 14        | 1.54%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 13        | 1.43%   |
| Synaptics Fingerprint reader [HP G6]                                       | 12        | 1.32%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.21%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 1.21%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 1.1%    |
| Synaptics  WBDI                                                            | 10        | 1.1%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 0.99%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 0.88%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 0.88%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.77%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.77%   |
| AuthenTec AES2810                                                          | 7         | 0.77%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 0.77%   |
| Elan WBF Fingerprint Sensor                                                | 6         | 0.66%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.55%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.55%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.55%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 0.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 164       | 48.52%  |
| Alcor Micro               | 94        | 27.81%  |
| Upek                      | 29        | 8.58%   |
| O2 Micro                  | 24        | 7.1%    |
| Lenovo                    | 18        | 5.33%   |
| Gemalto (was Gemplus)     | 2         | 0.59%   |
| Aladdin Knowledge Systems | 2         | 0.59%   |
| SCM Microsystems          | 1         | 0.3%    |
| OmniKey                   | 1         | 0.3%    |
| Giesecke & Devrient       | 1         | 0.3%    |
| Clay Logic                | 1         | 0.3%    |
| Advanced Card Systems     | 1         | 0.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 94        | 27.81%  |
| Broadcom BCM5880 Secure Applications Processor                               | 49        | 14.5%   |
| Broadcom 5880                                                                | 44        | 13.02%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 40        | 11.83%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 29        | 8.58%   |
| Broadcom 58200                                                               | 29        | 8.58%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 20        | 5.92%   |
| Lenovo Integrated Smart Card Reader                                          | 18        | 5.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.18%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.59%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.59%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.3%    |
| OmniKey CardMan 4321                                                         | 1         | 0.3%    |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.3%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.3%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.3%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.3%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3291      | 61.73%  |
| 1     | 1604      | 30.09%  |
| 2     | 372       | 6.98%   |
| 3     | 56        | 1.05%   |
| 4     | 6         | 0.11%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 889       | 36.11%  |
| Multimedia controller    | 333       | 13.53%  |
| Chipcard                 | 328       | 13.32%  |
| Graphics card            | 305       | 12.39%  |
| Net/wireless             | 286       | 11.62%  |
| Bluetooth                | 82        | 3.33%   |
| Camera                   | 62        | 2.52%   |
| Storage                  | 40        | 1.62%   |
| Sound                    | 31        | 1.26%   |
| Net/ethernet             | 30        | 1.22%   |
| Card reader              | 19        | 0.77%   |
| Communication controller | 18        | 0.73%   |
| Network                  | 13        | 0.53%   |
| Modem                    | 12        | 0.49%   |
| Storage/ide              | 5         | 0.2%    |
| Storage/nvme             | 3         | 0.12%   |
| Flash memory             | 2         | 0.08%   |
| Firewire controller      | 2         | 0.08%   |
| Unclassified device      | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |

