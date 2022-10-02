Lubuntu 20.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Lubuntu 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu_20.04/Desktop/README.md) and [notebooks](/Dist/Lubuntu_20.04/Notebook/README.md).

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

Total: 550

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | Maximus V FORMULA           | Desktop     | [cf8128637b](https://linux-hardware.org/?probe=cf8128637b) | Sep 24, 2022 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [e63b24acc3](https://linux-hardware.org/?probe=e63b24acc3) | Sep 24, 2022 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3468d8c911](https://linux-hardware.org/?probe=3468d8c911) | Sep 24, 2022 |
| ASUSTek       | X451CA                      | Notebook    | [bdfe92eb66](https://linux-hardware.org/?probe=bdfe92eb66) | Sep 21, 2022 |
| ASUSTek       | 1201N                       | Notebook    | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| Star Labs     | Lite                        | Notebook    | [c08b209f09](https://linux-hardware.org/?probe=c08b209f09) | Sep 09, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [7763040d56](https://linux-hardware.org/?probe=7763040d56) | Aug 30, 2022 |
| ASRock        | A520M-HVS                   | Desktop     | [842ad7d4d2](https://linux-hardware.org/?probe=842ad7d4d2) | Aug 22, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [49ba856687](https://linux-hardware.org/?probe=49ba856687) | Aug 03, 2022 |
| HP            | 240 G8 Notebook PC          | Notebook    | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [515c5375c1](https://linux-hardware.org/?probe=515c5375c1) | Jul 31, 2022 |
| Google        | Celes                       | Notebook    | [fae813e4dc](https://linux-hardware.org/?probe=fae813e4dc) | Jul 31, 2022 |
| HP            | Presario CQ56               | Notebook    | [aead18fee1](https://linux-hardware.org/?probe=aead18fee1) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [894bf232f8](https://linux-hardware.org/?probe=894bf232f8) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [eb752c319e](https://linux-hardware.org/?probe=eb752c319e) | Jul 28, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [3451f0e8b5](https://linux-hardware.org/?probe=3451f0e8b5) | Jul 26, 2022 |
| ASRock        | M3A785GMH/128M              | Desktop     | [87836918b2](https://linux-hardware.org/?probe=87836918b2) | Jul 25, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [55d8e5a779](https://linux-hardware.org/?probe=55d8e5a779) | Jul 24, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [826672a49e](https://linux-hardware.org/?probe=826672a49e) | Jul 22, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [cb9ba02bb3](https://linux-hardware.org/?probe=cb9ba02bb3) | Jul 20, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| MSI           | MS-AA1511                   | All in one  | [80c9ccb7c7](https://linux-hardware.org/?probe=80c9ccb7c7) | Jun 06, 2022 |
| HP            | G62                         | Notebook    | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| HP            | 3397                        | Desktop     | [2f3fb08195](https://linux-hardware.org/?probe=2f3fb08195) | Jun 03, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [8350bd6d87](https://linux-hardware.org/?probe=8350bd6d87) | May 30, 2022 |
| HP            | Berknip                     | Notebook    | [c81d3442c2](https://linux-hardware.org/?probe=c81d3442c2) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [9fa4c6beef](https://linux-hardware.org/?probe=9fa4c6beef) | May 26, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| ASUSTek       | X402CA                      | Notebook    | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [942f142f46](https://linux-hardware.org/?probe=942f142f46) | May 20, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [9254de4361](https://linux-hardware.org/?probe=9254de4361) | May 18, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [8ff47b2a2c](https://linux-hardware.org/?probe=8ff47b2a2c) | May 05, 2022 |
| Toshiba       | Satellite C670D-12N         | Notebook    | [f6bd692d1f](https://linux-hardware.org/?probe=f6bd692d1f) | May 05, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [5a36e4d0fc](https://linux-hardware.org/?probe=5a36e4d0fc) | May 04, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [bc88bd7582](https://linux-hardware.org/?probe=bc88bd7582) | May 04, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [c206790d1e](https://linux-hardware.org/?probe=c206790d1e) | May 01, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [2dffdad8a4](https://linux-hardware.org/?probe=2dffdad8a4) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [d44c4fd567](https://linux-hardware.org/?probe=d44c4fd567) | Apr 29, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6c4d2173a5](https://linux-hardware.org/?probe=6c4d2173a5) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a547974d27](https://linux-hardware.org/?probe=a547974d27) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [7be2e51c84](https://linux-hardware.org/?probe=7be2e51c84) | Apr 27, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [753e3fda7d](https://linux-hardware.org/?probe=753e3fda7d) | Apr 26, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [705fbe0501](https://linux-hardware.org/?probe=705fbe0501) | Apr 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [c8f16c0d16](https://linux-hardware.org/?probe=c8f16c0d16) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ff77bbf8ae](https://linux-hardware.org/?probe=ff77bbf8ae) | Apr 22, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [9d280b4678](https://linux-hardware.org/?probe=9d280b4678) | Apr 14, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [0aac536dbf](https://linux-hardware.org/?probe=0aac536dbf) | Apr 04, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Samsung       | N100SP                      | Notebook    | [6a70399256](https://linux-hardware.org/?probe=6a70399256) | Mar 31, 2022 |
| Intel         | W7650                       | Notebook    | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | Desktop     | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| Haier         | U1520EM                     | Notebook    | [5fde1c39e9](https://linux-hardware.org/?probe=5fde1c39e9) | Mar 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [2c480cdfac](https://linux-hardware.org/?probe=2c480cdfac) | Mar 22, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [a3f94c2957](https://linux-hardware.org/?probe=a3f94c2957) | Mar 20, 2022 |
| Google        | Celes                       | Notebook    | [cfcec68610](https://linux-hardware.org/?probe=cfcec68610) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| Dell          | Latitude D630               | Notebook    | [707be96775](https://linux-hardware.org/?probe=707be96775) | Mar 13, 2022 |
| ASRock        | Q1900M                      | Desktop     | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| HP            | 3647h                       | Desktop     | [11858412ec](https://linux-hardware.org/?probe=11858412ec) | Mar 06, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [efc41b55f4](https://linux-hardware.org/?probe=efc41b55f4) | Mar 06, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [31efa1bb6f](https://linux-hardware.org/?probe=31efa1bb6f) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [6a97a96f56](https://linux-hardware.org/?probe=6a97a96f56) | Mar 01, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [9d63b9e47f](https://linux-hardware.org/?probe=9d63b9e47f) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9a59eff157](https://linux-hardware.org/?probe=9a59eff157) | Feb 26, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [f07aaa2fd3](https://linux-hardware.org/?probe=f07aaa2fd3) | Feb 25, 2022 |
| HP            | 2AF7                        | Desktop     | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [8551d043a9](https://linux-hardware.org/?probe=8551d043a9) | Feb 20, 2022 |
| Alienware     | M17                         | Notebook    | [9d29db918d](https://linux-hardware.org/?probe=9d29db918d) | Feb 18, 2022 |
| Pegatron      | Narra6                      | Desktop     | [712b5069b6](https://linux-hardware.org/?probe=712b5069b6) | Feb 17, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [c70891d986](https://linux-hardware.org/?probe=c70891d986) | Feb 14, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [27e20ff1d8](https://linux-hardware.org/?probe=27e20ff1d8) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a72979e0f8](https://linux-hardware.org/?probe=a72979e0f8) | Feb 11, 2022 |
| Positivo      | N600                        | Notebook    | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| Dell          | Latitude E5540              | Notebook    | [e895dcce0f](https://linux-hardware.org/?probe=e895dcce0f) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [9c5efed237](https://linux-hardware.org/?probe=9c5efed237) | Feb 06, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1a0186c0a7](https://linux-hardware.org/?probe=1a0186c0a7) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | Desktop     | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| Toshiba       | Satellite C875              | Notebook    | [1dd31ebdd6](https://linux-hardware.org/?probe=1dd31ebdd6) | Feb 02, 2022 |
| Dell          | 0FJM8V A03                  | Server      | [398f8f6326](https://linux-hardware.org/?probe=398f8f6326) | Feb 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2J000    | Notebook    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [5adcd620f6](https://linux-hardware.org/?probe=5adcd620f6) | Jan 30, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| HP            | 3048h                       | Desktop     | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | Desktop     | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Pegatron      | EVE                         | Desktop     | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | Desktop     | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [433e46caa5](https://linux-hardware.org/?probe=433e46caa5) | Jan 19, 2022 |
| Dell          | Inspiron 15-3573            | Notebook    | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Positivo      | N600                        | Notebook    | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [66d00e2cd5](https://linux-hardware.org/?probe=66d00e2cd5) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [7cf1327087](https://linux-hardware.org/?probe=7cf1327087) | Jan 05, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| Acer          | Aspire 7715Z                | Notebook    | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| Lanix         | NeuronALV5                  | Notebook    | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| Sony          | VPCEJ1E1E                   | Notebook    | [0211323709](https://linux-hardware.org/?probe=0211323709) | Dec 28, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [d8d2b553bf](https://linux-hardware.org/?probe=d8d2b553bf) | Dec 24, 2021 |
| ASUSTek       | A8N5X                       | Desktop     | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ea7740294a](https://linux-hardware.org/?probe=ea7740294a) | Dec 24, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [c5c7ca1d56](https://linux-hardware.org/?probe=c5c7ca1d56) | Dec 20, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [175dda01f6](https://linux-hardware.org/?probe=175dda01f6) | Dec 15, 2021 |
| MSI           | Katana GF76 11UC            | Notebook    | [73fd53a50c](https://linux-hardware.org/?probe=73fd53a50c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [155ec30920](https://linux-hardware.org/?probe=155ec30920) | Dec 03, 2021 |
| ASUSTek       | CM1435                      | Desktop     | [febd571863](https://linux-hardware.org/?probe=febd571863) | Nov 28, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c4345f14ad](https://linux-hardware.org/?probe=c4345f14ad) | Nov 27, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [a6e2e61f26](https://linux-hardware.org/?probe=a6e2e61f26) | Nov 24, 2021 |
| Toshiba       | Satellite L40               | Notebook    | [43d9bb451a](https://linux-hardware.org/?probe=43d9bb451a) | Nov 23, 2021 |
| Gigabyte      | A520I AC                    | Desktop     | [ae985a32ad](https://linux-hardware.org/?probe=ae985a32ad) | Nov 23, 2021 |
| Dell          | Latitude 3330               | Notebook    | [2c8f88588b](https://linux-hardware.org/?probe=2c8f88588b) | Nov 23, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [867419b410](https://linux-hardware.org/?probe=867419b410) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [591f986631](https://linux-hardware.org/?probe=591f986631) | Nov 14, 2021 |
| ASUSTek       | 1015BX                      | Notebook    | [51933ea3ac](https://linux-hardware.org/?probe=51933ea3ac) | Nov 14, 2021 |
| Dell          | 0T568R A00                  | Desktop     | [bee032ad7d](https://linux-hardware.org/?probe=bee032ad7d) | Nov 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [0e17c0b84d](https://linux-hardware.org/?probe=0e17c0b84d) | Nov 13, 2021 |
| Acer          | Aspire X1700                | Desktop     | [c5f8009554](https://linux-hardware.org/?probe=c5f8009554) | Nov 11, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [4e3e71f6ab](https://linux-hardware.org/?probe=4e3e71f6ab) | Nov 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [57213f86cb](https://linux-hardware.org/?probe=57213f86cb) | Nov 05, 2021 |
| Foxconn       | 2AA9h                       | Desktop     | [92ec7d0070](https://linux-hardware.org/?probe=92ec7d0070) | Nov 03, 2021 |
| Samsung       | R40/R41                     | Notebook    | [5c44d1e88b](https://linux-hardware.org/?probe=5c44d1e88b) | Nov 01, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e84cd86eb0](https://linux-hardware.org/?probe=e84cd86eb0) | Oct 31, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e565d7befe](https://linux-hardware.org/?probe=e565d7befe) | Oct 31, 2021 |
| HP            | Presario CQ58               | Notebook    | [60d72bdce7](https://linux-hardware.org/?probe=60d72bdce7) | Oct 28, 2021 |
| HP            | Presario CQ58               | Notebook    | [8989debda6](https://linux-hardware.org/?probe=8989debda6) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [e1e44b58f3](https://linux-hardware.org/?probe=e1e44b58f3) | Oct 27, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [7b62ad7c35](https://linux-hardware.org/?probe=7b62ad7c35) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [42d3788463](https://linux-hardware.org/?probe=42d3788463) | Oct 27, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [45ba0657f1](https://linux-hardware.org/?probe=45ba0657f1) | Oct 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1663dc4946](https://linux-hardware.org/?probe=1663dc4946) | Oct 26, 2021 |
| MSI           | MS-7309                     | Desktop     | [72f1e0a452](https://linux-hardware.org/?probe=72f1e0a452) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [538c03b235](https://linux-hardware.org/?probe=538c03b235) | Oct 23, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [57043d09fe](https://linux-hardware.org/?probe=57043d09fe) | Oct 22, 2021 |
| Intel         | W7650                       | Notebook    | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [184c512c35](https://linux-hardware.org/?probe=184c512c35) | Oct 18, 2021 |
| Lenovo        | ThinkPad X61 76744NG        | Notebook    | [ee90608b54](https://linux-hardware.org/?probe=ee90608b54) | Oct 15, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [3f6dfebdf6](https://linux-hardware.org/?probe=3f6dfebdf6) | Oct 12, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e5702172f9](https://linux-hardware.org/?probe=e5702172f9) | Oct 11, 2021 |
| HP            | Notebook                    | Notebook    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f81838645f](https://linux-hardware.org/?probe=f81838645f) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0fe52aff1e](https://linux-hardware.org/?probe=0fe52aff1e) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0a715fa1e0](https://linux-hardware.org/?probe=0a715fa1e0) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [414e52d7a4](https://linux-hardware.org/?probe=414e52d7a4) | Oct 06, 2021 |
| Unknown       | X79M2-Q                     | Desktop     | [c864ea2ab2](https://linux-hardware.org/?probe=c864ea2ab2) | Oct 05, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| Pegatron      | Acacia                      | Desktop     | [645d85506e](https://linux-hardware.org/?probe=645d85506e) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Foxconn       | Priv                        | Desktop     | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Acer          | H57M01                      | Desktop     | [6e58f49020](https://linux-hardware.org/?probe=6e58f49020) | Sep 24, 2021 |
| Gigabyte      | H61M-DS2H                   | Desktop     | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| ASUSTek       | P8C WS                      | Desktop     | [e1dce50aa6](https://linux-hardware.org/?probe=e1dce50aa6) | Sep 18, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [f4c9642d6f](https://linux-hardware.org/?probe=f4c9642d6f) | Sep 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| Dell          | 01V648 A03                  | Server      | [f46a021c88](https://linux-hardware.org/?probe=f46a021c88) | Sep 02, 2021 |
| Notebook      | NL40_50GU                   | Notebook    | [977812d04b](https://linux-hardware.org/?probe=977812d04b) | Aug 29, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| ZOTAC         | NM10                        | Desktop     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | 760GM-E51                   | Desktop     | [1edbc1f4d8](https://linux-hardware.org/?probe=1edbc1f4d8) | Aug 19, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406138U       | Notebook    | [a72c7ecd8a](https://linux-hardware.org/?probe=a72c7ecd8a) | Aug 14, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [9b893159ef](https://linux-hardware.org/?probe=9b893159ef) | Aug 06, 2021 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [0719538c6e](https://linux-hardware.org/?probe=0719538c6e) | Aug 02, 2021 |
| Dell          | Latitude E5450              | Notebook    | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| HP            | 8299                        | Desktop     | [48455294be](https://linux-hardware.org/?probe=48455294be) | Jul 28, 2021 |
| HP            | ProBook 6450b               | Notebook    | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| Huanan        | X99-TF V2.0                 | Desktop     | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| HP            | 1495                        | Desktop     | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| Dell          | Inspiron M5040              | Notebook    | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Dell          | 0CN7X8 A05                  | Server      | [e5766c8331](https://linux-hardware.org/?probe=e5766c8331) | Jul 22, 2021 |
| HP            | 0A1Ch E                     | Desktop     | [6d6f2ce899](https://linux-hardware.org/?probe=6d6f2ce899) | Jul 21, 2021 |
| Gigabyte      | B450M H                     | Desktop     | [cb2babd945](https://linux-hardware.org/?probe=cb2babd945) | Jul 20, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [d4852f4d01](https://linux-hardware.org/?probe=d4852f4d01) | Jul 14, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [e0ff38374e](https://linux-hardware.org/?probe=e0ff38374e) | Jul 13, 2021 |
| Positivo      | POS-MI945AA                 | Desktop     | [2a1eda1972](https://linux-hardware.org/?probe=2a1eda1972) | Jul 07, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [456048c8ee](https://linux-hardware.org/?probe=456048c8ee) | Jul 06, 2021 |
| Hardkernel    | ODROID-H2                   | Desktop     | [37fdca8e63](https://linux-hardware.org/?probe=37fdca8e63) | Jul 06, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | Notebook    | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [2383fe9425](https://linux-hardware.org/?probe=2383fe9425) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [581180a4d8](https://linux-hardware.org/?probe=581180a4d8) | Jun 30, 2021 |
| Dell          | 0TW904 A01                  | Desktop     | [b98c7e4685](https://linux-hardware.org/?probe=b98c7e4685) | Jun 29, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [99a0739814](https://linux-hardware.org/?probe=99a0739814) | Jun 28, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [cfd34d8c5b](https://linux-hardware.org/?probe=cfd34d8c5b) | Jun 22, 2021 |
| Notebook      | NHxxRZQ                     | Notebook    | [221e4d197b](https://linux-hardware.org/?probe=221e4d197b) | Jun 19, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [5e9110ee62](https://linux-hardware.org/?probe=5e9110ee62) | Jun 18, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [fdbc9729c1](https://linux-hardware.org/?probe=fdbc9729c1) | Jun 18, 2021 |
| Dell          | 0TW904 A01                  | Desktop     | [51b0adff27](https://linux-hardware.org/?probe=51b0adff27) | Jun 17, 2021 |
| Samsung       | RC512                       | Notebook    | [d8681e5e08](https://linux-hardware.org/?probe=d8681e5e08) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | Notebook    | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Google        | Kohaku                      | Notebook    | [6de3f99f1d](https://linux-hardware.org/?probe=6de3f99f1d) | Jun 08, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | Desktop     | [ec208f5ad8](https://linux-hardware.org/?probe=ec208f5ad8) | Jun 06, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [23182c745b](https://linux-hardware.org/?probe=23182c745b) | May 27, 2021 |
| Dell          | Latitude D630               | Notebook    | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| ASUSTek       | K8N                         | Desktop     | [2bfbb90a8e](https://linux-hardware.org/?probe=2bfbb90a8e) | May 24, 2021 |
| HP            | 1905                        | Desktop     | [fd0f9e5ab1](https://linux-hardware.org/?probe=fd0f9e5ab1) | May 23, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| HP            | 09C4h                       | Desktop     | [a94946d561](https://linux-hardware.org/?probe=a94946d561) | May 23, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [fba07779e2](https://linux-hardware.org/?probe=fba07779e2) | May 21, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [001eb9ea2f](https://linux-hardware.org/?probe=001eb9ea2f) | May 21, 2021 |
| Dell          | 0HY175 A03                  | Desktop     | [d1b6626b26](https://linux-hardware.org/?probe=d1b6626b26) | May 20, 2021 |
| HP            | 1905                        | Desktop     | [28fb3ce7e8](https://linux-hardware.org/?probe=28fb3ce7e8) | May 20, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [e8f0220bba](https://linux-hardware.org/?probe=e8f0220bba) | May 19, 2021 |
| ASUSTek       | K8N                         | Desktop     | [1d266884ca](https://linux-hardware.org/?probe=1d266884ca) | May 19, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [aba62024a7](https://linux-hardware.org/?probe=aba62024a7) | May 15, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [5682d68364](https://linux-hardware.org/?probe=5682d68364) | May 14, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [2216d5b0b1](https://linux-hardware.org/?probe=2216d5b0b1) | May 14, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [b724b0cc62](https://linux-hardware.org/?probe=b724b0cc62) | May 14, 2021 |
| MSI           | H61M-E33                    | Desktop     | [23d2285e8a](https://linux-hardware.org/?probe=23d2285e8a) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [d044706f11](https://linux-hardware.org/?probe=d044706f11) | May 13, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [25eb899222](https://linux-hardware.org/?probe=25eb899222) | May 12, 2021 |
| ASUSTek       | K8N                         | Desktop     | [e692a4b6aa](https://linux-hardware.org/?probe=e692a4b6aa) | May 11, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0f9c2db369](https://linux-hardware.org/?probe=0f9c2db369) | May 07, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8c9dd0e965](https://linux-hardware.org/?probe=8c9dd0e965) | May 06, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [579414cef4](https://linux-hardware.org/?probe=579414cef4) | May 04, 2021 |
| HP            | Notebook                    | Notebook    | [ca99bba8dc](https://linux-hardware.org/?probe=ca99bba8dc) | May 02, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [9088160499](https://linux-hardware.org/?probe=9088160499) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [7feaa72545](https://linux-hardware.org/?probe=7feaa72545) | Apr 30, 2021 |
| LG Electro... | S425-L.BC22P1               | Notebook    | [791fd9ff12](https://linux-hardware.org/?probe=791fd9ff12) | Apr 28, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [ef051b442a](https://linux-hardware.org/?probe=ef051b442a) | Apr 28, 2021 |
| Packard Be... | IMEDIA S1350                | Desktop     | [781d544a3e](https://linux-hardware.org/?probe=781d544a3e) | Apr 27, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [4015285676](https://linux-hardware.org/?probe=4015285676) | Apr 26, 2021 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [25f6cfe2bb](https://linux-hardware.org/?probe=25f6cfe2bb) | Apr 26, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [145106a409](https://linux-hardware.org/?probe=145106a409) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | Notebook    | [e958267bec](https://linux-hardware.org/?probe=e958267bec) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | Notebook    | [cf6e170fcc](https://linux-hardware.org/?probe=cf6e170fcc) | Apr 25, 2021 |
| Dell          | Inspiron 7706 2n1           | Convertible | [82eb222c26](https://linux-hardware.org/?probe=82eb222c26) | Apr 23, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [9002772847](https://linux-hardware.org/?probe=9002772847) | Apr 21, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [6a22991dbe](https://linux-hardware.org/?probe=6a22991dbe) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [0a367170ed](https://linux-hardware.org/?probe=0a367170ed) | Apr 17, 2021 |
| LG Electro... | S425-L.BC22P1               | Notebook    | [64a50f7bb8](https://linux-hardware.org/?probe=64a50f7bb8) | Apr 15, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [e0086be941](https://linux-hardware.org/?probe=e0086be941) | Apr 15, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [e2dea3ec01](https://linux-hardware.org/?probe=e2dea3ec01) | Apr 14, 2021 |
| Dell          | Studio 1555                 | Notebook    | [c161e182c2](https://linux-hardware.org/?probe=c161e182c2) | Apr 14, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| GTZS          | Unknown                     | Notebook    | [5600074bc0](https://linux-hardware.org/?probe=5600074bc0) | Apr 07, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [f3e45414fa](https://linux-hardware.org/?probe=f3e45414fa) | Apr 04, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [eacca5eceb](https://linux-hardware.org/?probe=eacca5eceb) | Apr 04, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [2c58a29c2a](https://linux-hardware.org/?probe=2c58a29c2a) | Apr 02, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d36d3e1e58](https://linux-hardware.org/?probe=d36d3e1e58) | Apr 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [db0eb79b4e](https://linux-hardware.org/?probe=db0eb79b4e) | Mar 31, 2021 |
| ASUSTek       | 1005PE                      | Notebook    | [d75411e5b3](https://linux-hardware.org/?probe=d75411e5b3) | Mar 30, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [4f1445876a](https://linux-hardware.org/?probe=4f1445876a) | Mar 27, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [c9dfbce9bd](https://linux-hardware.org/?probe=c9dfbce9bd) | Mar 26, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [383cee85b7](https://linux-hardware.org/?probe=383cee85b7) | Mar 25, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [83716bfba8](https://linux-hardware.org/?probe=83716bfba8) | Mar 24, 2021 |
| HP            | 21D0                        | Desktop     | [ebf910609e](https://linux-hardware.org/?probe=ebf910609e) | Mar 23, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [961ef41a18](https://linux-hardware.org/?probe=961ef41a18) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [82480a0f24](https://linux-hardware.org/?probe=82480a0f24) | Mar 21, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e1adceeeeb](https://linux-hardware.org/?probe=e1adceeeeb) | Mar 20, 2021 |
| Lenovo        | S10-3                       | Notebook    | [42884278c4](https://linux-hardware.org/?probe=42884278c4) | Mar 19, 2021 |
| Dell          | System XPS 15Z              | Notebook    | [cb1bcbb365](https://linux-hardware.org/?probe=cb1bcbb365) | Mar 18, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [4235b59b38](https://linux-hardware.org/?probe=4235b59b38) | Mar 17, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [4b3b196273](https://linux-hardware.org/?probe=4b3b196273) | Mar 17, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a6b06d9421](https://linux-hardware.org/?probe=a6b06d9421) | Mar 16, 2021 |
| HP            | 8267 A01                    | Mini pc     | [3aa09cf72a](https://linux-hardware.org/?probe=3aa09cf72a) | Mar 15, 2021 |
| ASRock        | 775Dual-VSTA                | Desktop     | [6f870bccf3](https://linux-hardware.org/?probe=6f870bccf3) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| ASUSTek       | P53E                        | Notebook    | [3aacf8a497](https://linux-hardware.org/?probe=3aacf8a497) | Mar 07, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [0b9b8232f9](https://linux-hardware.org/?probe=0b9b8232f9) | Mar 05, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| Toshiba       | Satellite A660              | Notebook    | [70166b0f32](https://linux-hardware.org/?probe=70166b0f32) | Mar 01, 2021 |
| Lenovo        | S10-3                       | Notebook    | [6d4f0001a3](https://linux-hardware.org/?probe=6d4f0001a3) | Mar 01, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [3ed340b3ba](https://linux-hardware.org/?probe=3ed340b3ba) | Feb 28, 2021 |
| Dell          | 0RY007                      | Desktop     | [6172822ebb](https://linux-hardware.org/?probe=6172822ebb) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Itautec       | Infoway w7430               | Notebook    | [72a0d46cbd](https://linux-hardware.org/?probe=72a0d46cbd) | Feb 25, 2021 |
| Timi          | TM1612                      | Notebook    | [517a0ea812](https://linux-hardware.org/?probe=517a0ea812) | Feb 23, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [1063468eed](https://linux-hardware.org/?probe=1063468eed) | Feb 21, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [234fac5997](https://linux-hardware.org/?probe=234fac5997) | Feb 21, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | Notebook    | [e79cbcdc53](https://linux-hardware.org/?probe=e79cbcdc53) | Feb 20, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | Notebook    | [eaeef8bb7b](https://linux-hardware.org/?probe=eaeef8bb7b) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [eeabc1752d](https://linux-hardware.org/?probe=eeabc1752d) | Feb 15, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [95b0ea2335](https://linux-hardware.org/?probe=95b0ea2335) | Feb 15, 2021 |
| Intel         | ChiefRiver                  | Desktop     | [25476cfcb9](https://linux-hardware.org/?probe=25476cfcb9) | Feb 10, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9c1652cf08](https://linux-hardware.org/?probe=9c1652cf08) | Feb 10, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [715d525514](https://linux-hardware.org/?probe=715d525514) | Feb 07, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [4fd36e0cb3](https://linux-hardware.org/?probe=4fd36e0cb3) | Feb 07, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [f943690f6e](https://linux-hardware.org/?probe=f943690f6e) | Feb 07, 2021 |
| HP            | Pavilion g7                 | Notebook    | [5151e90c72](https://linux-hardware.org/?probe=5151e90c72) | Feb 06, 2021 |
| HP            | G42                         | Notebook    | [b9fbeca924](https://linux-hardware.org/?probe=b9fbeca924) | Feb 05, 2021 |
| HP            | Compaq 6715b (GP690US#AB... | Notebook    | [e77dbfe4a6](https://linux-hardware.org/?probe=e77dbfe4a6) | Feb 05, 2021 |
| Supermicro    | X8DA3                       | Server      | [039bf2c96a](https://linux-hardware.org/?probe=039bf2c96a) | Feb 04, 2021 |
| Supermicro    | X8DA3                       | Server      | [3731f93e51](https://linux-hardware.org/?probe=3731f93e51) | Feb 04, 2021 |
| HP            | 3048h                       | Desktop     | [59c1560e00](https://linux-hardware.org/?probe=59c1560e00) | Jan 30, 2021 |
| Lenovo        | ThinkPad L460 20FVS20700    | Notebook    | [e456ebd9cc](https://linux-hardware.org/?probe=e456ebd9cc) | Jan 29, 2021 |
| HP            | Notebook                    | Notebook    | [c83f3fcce6](https://linux-hardware.org/?probe=c83f3fcce6) | Jan 27, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [c654b7b4ad](https://linux-hardware.org/?probe=c654b7b4ad) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [20f7e526b4](https://linux-hardware.org/?probe=20f7e526b4) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| Lenovo        | IdeaPad Y550 4186           | Notebook    | [d6ae69ca34](https://linux-hardware.org/?probe=d6ae69ca34) | Jan 17, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [57f9413b16](https://linux-hardware.org/?probe=57f9413b16) | Jan 16, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [1f7fadda6e](https://linux-hardware.org/?probe=1f7fadda6e) | Jan 10, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [3ff4a460a2](https://linux-hardware.org/?probe=3ff4a460a2) | Jan 10, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [01626f040a](https://linux-hardware.org/?probe=01626f040a) | Jan 05, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [65ed0bcd53](https://linux-hardware.org/?probe=65ed0bcd53) | Jan 02, 2021 |
| Positivo      | S14CT01                     | Notebook    | [2b0f53fc1a](https://linux-hardware.org/?probe=2b0f53fc1a) | Jan 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [c11d9786f7](https://linux-hardware.org/?probe=c11d9786f7) | Dec 29, 2020 |
| Lenovo        | ThinkCentre M58p 6136A66    | Desktop     | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Dell          | 0WG864                      | Desktop     | [f5cb8c4f4a](https://linux-hardware.org/?probe=f5cb8c4f4a) | Dec 23, 2020 |
| Fujitsu       | FMVNFA50                    | Notebook    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| HP            | Pavilion TS 15              | Notebook    | [aea4de88ed](https://linux-hardware.org/?probe=aea4de88ed) | Dec 22, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [f29fb73181](https://linux-hardware.org/?probe=f29fb73181) | Dec 20, 2020 |
| ASUSTek       | K53SD                       | Notebook    | [96067d7a81](https://linux-hardware.org/?probe=96067d7a81) | Dec 13, 2020 |
| Toshiba       | NB510                       | Notebook    | [41d6c29f97](https://linux-hardware.org/?probe=41d6c29f97) | Dec 13, 2020 |
| Dell          | 0WG864                      | Desktop     | [de92f1f8e4](https://linux-hardware.org/?probe=de92f1f8e4) | Dec 11, 2020 |
| Gateway       | NE56R                       | Notebook    | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WP0... | Notebook    | [6ee5c7543b](https://linux-hardware.org/?probe=6ee5c7543b) | Dec 10, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [80ecb8f763](https://linux-hardware.org/?probe=80ecb8f763) | Dec 06, 2020 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [225f795531](https://linux-hardware.org/?probe=225f795531) | Dec 01, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [ce0a64067a](https://linux-hardware.org/?probe=ce0a64067a) | Nov 29, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [d7ac62fba3](https://linux-hardware.org/?probe=d7ac62fba3) | Nov 29, 2020 |
| Lenovo        | 367D 31900058 STD           | Desktop     | [40b28c6d37](https://linux-hardware.org/?probe=40b28c6d37) | Nov 29, 2020 |
| Panasonic     | CF-52PGNBE2M                | Notebook    | [e6e31de556](https://linux-hardware.org/?probe=e6e31de556) | Nov 28, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [503449ba47](https://linux-hardware.org/?probe=503449ba47) | Nov 27, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [f45a6362f7](https://linux-hardware.org/?probe=f45a6362f7) | Nov 27, 2020 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [761ecd0a1c](https://linux-hardware.org/?probe=761ecd0a1c) | Nov 25, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [5eae42eb75](https://linux-hardware.org/?probe=5eae42eb75) | Nov 25, 2020 |
| HP            | Presario F700 (KA698EA#A... | Notebook    | [19fd9647b4](https://linux-hardware.org/?probe=19fd9647b4) | Nov 23, 2020 |
| HP            | Presario F700 (KA698EA#A... | Notebook    | [b46ffd3c2e](https://linux-hardware.org/?probe=b46ffd3c2e) | Nov 23, 2020 |
| HP            | 2820h                       | Desktop     | [fc14726596](https://linux-hardware.org/?probe=fc14726596) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | Notebook    | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Pegatron      | Narra6                      | Desktop     | [7878c50c46](https://linux-hardware.org/?probe=7878c50c46) | Nov 20, 2020 |
| Positivo      | S14BW01                     | Notebook    | [13fed8ca27](https://linux-hardware.org/?probe=13fed8ca27) | Nov 17, 2020 |
| Gateway       | NE56R                       | Notebook    | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| HP            | 09F8h                       | Desktop     | [60fbac3096](https://linux-hardware.org/?probe=60fbac3096) | Nov 16, 2020 |
| HP            | ProBook 4720s               | Notebook    | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| MSI           | G41M-P28                    | Desktop     | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [5ecd7c84ac](https://linux-hardware.org/?probe=5ecd7c84ac) | Nov 09, 2020 |
| Unknown       | Unknown                     | Notebook    | [abc04e2dfd](https://linux-hardware.org/?probe=abc04e2dfd) | Nov 09, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [f83b2806d0](https://linux-hardware.org/?probe=f83b2806d0) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | Notebook    | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [3bc862c3f6](https://linux-hardware.org/?probe=3bc862c3f6) | Nov 03, 2020 |
| Acer          | AOD257                      | Notebook    | [a45ddcc3ab](https://linux-hardware.org/?probe=a45ddcc3ab) | Nov 03, 2020 |
| Acer          | AOD257                      | Notebook    | [3daaf2fdad](https://linux-hardware.org/?probe=3daaf2fdad) | Nov 02, 2020 |
| Samsung       | RV408/RV508                 | Notebook    | [208f929309](https://linux-hardware.org/?probe=208f929309) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [547d1a4d87](https://linux-hardware.org/?probe=547d1a4d87) | Nov 01, 2020 |
| HP            | 0AA8h                       | Desktop     | [f619ee9af9](https://linux-hardware.org/?probe=f619ee9af9) | Oct 31, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [7fd48df4aa](https://linux-hardware.org/?probe=7fd48df4aa) | Oct 31, 2020 |
| Intel         | STK1AW32SC H91596-300       | Desktop     | [64ad81c366](https://linux-hardware.org/?probe=64ad81c366) | Oct 31, 2020 |
| Toshiba       | Satellite L305              | Notebook    | [c2a545a417](https://linux-hardware.org/?probe=c2a545a417) | Oct 30, 2020 |
| Dell          | Inspiron 5759               | Notebook    | [a9f65003ad](https://linux-hardware.org/?probe=a9f65003ad) | Oct 29, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [855274d6b0](https://linux-hardware.org/?probe=855274d6b0) | Oct 29, 2020 |
| Notebook      | W740SU                      | Notebook    | [cd23f8c64d](https://linux-hardware.org/?probe=cd23f8c64d) | Oct 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS8CH0... | Notebook    | [bd938bf5fd](https://linux-hardware.org/?probe=bd938bf5fd) | Oct 28, 2020 |
| Positivo      | H14BT58                     | Notebook    | [84c73b4beb](https://linux-hardware.org/?probe=84c73b4beb) | Oct 27, 2020 |
| Itautec       | Infoway                     | Notebook    | [b67c3f6870](https://linux-hardware.org/?probe=b67c3f6870) | Oct 27, 2020 |
| MSI           | U180                        | Notebook    | [7b3f357ff5](https://linux-hardware.org/?probe=7b3f357ff5) | Oct 26, 2020 |
| Lenovo        | G575 4383                   | Notebook    | [43b5c51358](https://linux-hardware.org/?probe=43b5c51358) | Oct 25, 2020 |
| Dell          | 0J3C2F A02                  | Desktop     | [a0c7490384](https://linux-hardware.org/?probe=a0c7490384) | Oct 23, 2020 |
| Acer          | Extensa 4620                | Notebook    | [62e829d249](https://linux-hardware.org/?probe=62e829d249) | Oct 22, 2020 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [9655c9ef29](https://linux-hardware.org/?probe=9655c9ef29) | Oct 21, 2020 |
| ASRock        | G41M-GS3                    | Desktop     | [55872633b0](https://linux-hardware.org/?probe=55872633b0) | Oct 21, 2020 |
| HP            | 2187 A01                    | Desktop     | [ed8c0e270a](https://linux-hardware.org/?probe=ed8c0e270a) | Oct 21, 2020 |
| HP            | 2187 A01                    | Desktop     | [873e321107](https://linux-hardware.org/?probe=873e321107) | Oct 20, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c1a4649fc7](https://linux-hardware.org/?probe=c1a4649fc7) | Oct 20, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [003da597cd](https://linux-hardware.org/?probe=003da597cd) | Oct 19, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [95778c93aa](https://linux-hardware.org/?probe=95778c93aa) | Oct 18, 2020 |
| Toshiba       | Satellite L840              | Notebook    | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| Acer          | Extensa 4620                | Notebook    | [dd858548d7](https://linux-hardware.org/?probe=dd858548d7) | Oct 15, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | Notebook    | [a422be5fc0](https://linux-hardware.org/?probe=a422be5fc0) | Oct 15, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [1717667731](https://linux-hardware.org/?probe=1717667731) | Oct 13, 2020 |
| LAMINA        | T-1012B NORD                | Notebook    | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| Google        | Wolf                        | Notebook    | [0ebdfebf96](https://linux-hardware.org/?probe=0ebdfebf96) | Oct 10, 2020 |
| MSI           | H97M-E35                    | Desktop     | [583794cac0](https://linux-hardware.org/?probe=583794cac0) | Oct 10, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [03d64c9c3d](https://linux-hardware.org/?probe=03d64c9c3d) | Oct 10, 2020 |
| HP            | Pavilion dv6                | Notebook    | [0d0a5ac639](https://linux-hardware.org/?probe=0d0a5ac639) | Oct 07, 2020 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [53ecc0af0c](https://linux-hardware.org/?probe=53ecc0af0c) | Oct 07, 2020 |
| HP            | Unknown                     | Notebook    | [6ff5164672](https://linux-hardware.org/?probe=6ff5164672) | Oct 07, 2020 |
| MSI           | H110M ECO                   | Desktop     | [21fea178f7](https://linux-hardware.org/?probe=21fea178f7) | Oct 06, 2020 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [9a5387bb3b](https://linux-hardware.org/?probe=9a5387bb3b) | Oct 04, 2020 |
| Dell          | Latitude D630               | Notebook    | [df80a0678a](https://linux-hardware.org/?probe=df80a0678a) | Oct 04, 2020 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [a112988e2e](https://linux-hardware.org/?probe=a112988e2e) | Sep 28, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7003257b9c](https://linux-hardware.org/?probe=7003257b9c) | Sep 26, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [863493a36c](https://linux-hardware.org/?probe=863493a36c) | Sep 25, 2020 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [4f2bb45d77](https://linux-hardware.org/?probe=4f2bb45d77) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57e9fe3f34](https://linux-hardware.org/?probe=57e9fe3f34) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [2c253a5689](https://linux-hardware.org/?probe=2c253a5689) | Sep 23, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [d62d875657](https://linux-hardware.org/?probe=d62d875657) | Sep 22, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [cb4d6ae384](https://linux-hardware.org/?probe=cb4d6ae384) | Sep 22, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e7728895a3](https://linux-hardware.org/?probe=e7728895a3) | Sep 20, 2020 |
| Fujitsu       | FMVA05008                   | Notebook    | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7331377f2b](https://linux-hardware.org/?probe=7331377f2b) | Sep 16, 2020 |
| HP            | Pavilion x2 Detachable      | Tablet      | [5c305017e8](https://linux-hardware.org/?probe=5c305017e8) | Sep 13, 2020 |
| Acer          | Prespa M                    | Notebook    | [4310240814](https://linux-hardware.org/?probe=4310240814) | Sep 13, 2020 |
| ASRock        | A320M-DGS                   | Desktop     | [0ee0a67ae6](https://linux-hardware.org/?probe=0ee0a67ae6) | Sep 13, 2020 |
| Acer          | Prespa M                    | Notebook    | [dc7c7827ea](https://linux-hardware.org/?probe=dc7c7827ea) | Sep 13, 2020 |
| ASUSTek       | F7L                         | Notebook    | [0190224dc8](https://linux-hardware.org/?probe=0190224dc8) | Sep 12, 2020 |
| Dell          | MXG071                      | Notebook    | [5fc63c5480](https://linux-hardware.org/?probe=5fc63c5480) | Sep 12, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [0362c81208](https://linux-hardware.org/?probe=0362c81208) | Sep 11, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [3bc9d8ad1e](https://linux-hardware.org/?probe=3bc9d8ad1e) | Sep 10, 2020 |
| ASUSTek       | P553UA                      | Notebook    | [fca37591fc](https://linux-hardware.org/?probe=fca37591fc) | Sep 10, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | Notebook    | [2cca042481](https://linux-hardware.org/?probe=2cca042481) | Sep 10, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [84a053df62](https://linux-hardware.org/?probe=84a053df62) | Sep 09, 2020 |
| Dell          | Latitude E5450              | Notebook    | [d5eebfddb5](https://linux-hardware.org/?probe=d5eebfddb5) | Sep 07, 2020 |
| Google        | Gandof                      | Notebook    | [6b79edadc5](https://linux-hardware.org/?probe=6b79edadc5) | Sep 04, 2020 |
| Acer          | Aspire ES1-522              | Notebook    | [c5e6143bbd](https://linux-hardware.org/?probe=c5e6143bbd) | Sep 02, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [121fd4e00e](https://linux-hardware.org/?probe=121fd4e00e) | Aug 30, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [3a0e9bb81b](https://linux-hardware.org/?probe=3a0e9bb81b) | Aug 30, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [ea7a9a7e0f](https://linux-hardware.org/?probe=ea7a9a7e0f) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [b7beb93997](https://linux-hardware.org/?probe=b7beb93997) | Aug 28, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [b5a228d9bf](https://linux-hardware.org/?probe=b5a228d9bf) | Aug 26, 2020 |
| Dell          | 0CU409                      | Desktop     | [d226085fe5](https://linux-hardware.org/?probe=d226085fe5) | Aug 26, 2020 |
| ASRock        | A320M-HD                    | Desktop     | [8e8b3d8d21](https://linux-hardware.org/?probe=8e8b3d8d21) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e95b44a1c2](https://linux-hardware.org/?probe=e95b44a1c2) | Aug 23, 2020 |
| ASUSTek       | K50C                        | Notebook    | [dd9986741e](https://linux-hardware.org/?probe=dd9986741e) | Aug 19, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [72e40559e9](https://linux-hardware.org/?probe=72e40559e9) | Aug 17, 2020 |
| Digibras      | NH4CU03                     | Notebook    | [3ba7006e38](https://linux-hardware.org/?probe=3ba7006e38) | Aug 15, 2020 |
| HP            | ProBook 440 G2              | Notebook    | [18e6bfd3b5](https://linux-hardware.org/?probe=18e6bfd3b5) | Aug 14, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [ca848be2f0](https://linux-hardware.org/?probe=ca848be2f0) | Aug 12, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [723c72f289](https://linux-hardware.org/?probe=723c72f289) | Aug 12, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [a8401cc827](https://linux-hardware.org/?probe=a8401cc827) | Aug 12, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| Lenovo        | ThinkCentre M58p 7220W21    | Desktop     | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
| Lenovo        | SDK0E50515 STD              | Desktop     | [def93851d7](https://linux-hardware.org/?probe=def93851d7) | Jul 27, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [b4e6ad4325](https://linux-hardware.org/?probe=b4e6ad4325) | Jul 25, 2020 |
| HP            | ProBook 445 G7              | Notebook    | [6507b9ca49](https://linux-hardware.org/?probe=6507b9ca49) | Jul 25, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [aea6ae732a](https://linux-hardware.org/?probe=aea6ae732a) | Jul 25, 2020 |
| Acer          | V5-171                      | Notebook    | [1f30ec8b2e](https://linux-hardware.org/?probe=1f30ec8b2e) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [8b84442168](https://linux-hardware.org/?probe=8b84442168) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [468608973e](https://linux-hardware.org/?probe=468608973e) | Jul 25, 2020 |
| ASUSTek       | P7P55 LX                    | Desktop     | [b907d5353a](https://linux-hardware.org/?probe=b907d5353a) | Jul 25, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [fd15d7f633](https://linux-hardware.org/?probe=fd15d7f633) | Jul 24, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [e79c3ae616](https://linux-hardware.org/?probe=e79c3ae616) | Jul 24, 2020 |
| Intel         | H55                         | Desktop     | [f9399791b8](https://linux-hardware.org/?probe=f9399791b8) | Jul 24, 2020 |
| Positivo      | H14BT58                     | Notebook    | [3cb433c2cc](https://linux-hardware.org/?probe=3cb433c2cc) | Jul 24, 2020 |
| ASUSTek       | 1015BX                      | Notebook    | [5f48c6c53b](https://linux-hardware.org/?probe=5f48c6c53b) | Jul 24, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [cf22d23381](https://linux-hardware.org/?probe=cf22d23381) | Jul 22, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [3d1f4e7cb8](https://linux-hardware.org/?probe=3d1f4e7cb8) | Jul 21, 2020 |
| IBM           | eServer x3105 -[434722J]... | Desktop     | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [ee73a556b1](https://linux-hardware.org/?probe=ee73a556b1) | Jul 19, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [33e46bd029](https://linux-hardware.org/?probe=33e46bd029) | Jul 19, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [09f9209cda](https://linux-hardware.org/?probe=09f9209cda) | Jul 18, 2020 |
| Dell          | Studio 1555                 | Notebook    | [0d511c045e](https://linux-hardware.org/?probe=0d511c045e) | Jul 16, 2020 |
| Dell          | Latitude D520               | Notebook    | [c41f563801](https://linux-hardware.org/?probe=c41f563801) | Jul 16, 2020 |
| ASUSTek       | Q302LA                      | Notebook    | [c453eada8f](https://linux-hardware.org/?probe=c453eada8f) | Jul 09, 2020 |
| HP            | Notebook                    | Notebook    | [10cadcd9b6](https://linux-hardware.org/?probe=10cadcd9b6) | Jul 09, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [9e35eb4bff](https://linux-hardware.org/?probe=9e35eb4bff) | Jul 08, 2020 |
| HP            | Pavilion 15                 | Notebook    | [9f54b2c875](https://linux-hardware.org/?probe=9f54b2c875) | Jul 06, 2020 |
| HP            | 3396                        | Desktop     | [820e05ee01](https://linux-hardware.org/?probe=820e05ee01) | Jul 03, 2020 |
| Acer          | Swift SF314-52G             | Notebook    | [8cd6b05831](https://linux-hardware.org/?probe=8cd6b05831) | Jul 03, 2020 |
| HP            | Pavilion dv6000 (RD870AV... | Notebook    | [921ea4c212](https://linux-hardware.org/?probe=921ea4c212) | Jul 03, 2020 |
| Acer          | Aspire ES1-331              | Notebook    | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [193cbfc862](https://linux-hardware.org/?probe=193cbfc862) | Jun 30, 2020 |
| HP            | Compaq 615                  | Notebook    | [38dc3f0f55](https://linux-hardware.org/?probe=38dc3f0f55) | Jun 29, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [598acef23f](https://linux-hardware.org/?probe=598acef23f) | Jun 26, 2020 |
| HP            | Compaq 6710b (RM338UT#AB... | Notebook    | [997dd3289c](https://linux-hardware.org/?probe=997dd3289c) | Jun 25, 2020 |
| HP            | Compaq 615                  | Notebook    | [d24b727a5b](https://linux-hardware.org/?probe=d24b727a5b) | Jun 24, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [8d3308bf38](https://linux-hardware.org/?probe=8d3308bf38) | Jun 23, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [e6ee210f6d](https://linux-hardware.org/?probe=e6ee210f6d) | Jun 23, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [c64fcf2a5d](https://linux-hardware.org/?probe=c64fcf2a5d) | Jun 21, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [21bd837ffa](https://linux-hardware.org/?probe=21bd837ffa) | Jun 20, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [33713a0404](https://linux-hardware.org/?probe=33713a0404) | Jun 18, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [93ced4c964](https://linux-hardware.org/?probe=93ced4c964) | Jun 18, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| MSI           | 0A48                        | Desktop     | [e9c8fd5217](https://linux-hardware.org/?probe=e9c8fd5217) | Jun 17, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [a612626f7b](https://linux-hardware.org/?probe=a612626f7b) | Jun 16, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [5473d1a8e3](https://linux-hardware.org/?probe=5473d1a8e3) | Jun 10, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [ad60c0409d](https://linux-hardware.org/?probe=ad60c0409d) | Jun 09, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [7232340ccc](https://linux-hardware.org/?probe=7232340ccc) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [4400ee29ed](https://linux-hardware.org/?probe=4400ee29ed) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [d730ecdbd6](https://linux-hardware.org/?probe=d730ecdbd6) | Jun 08, 2020 |
| Acer          | Aspire 5734Z                | Notebook    | [6af54cea15](https://linux-hardware.org/?probe=6af54cea15) | Jun 07, 2020 |
| HP            | Pavilion 15                 | Notebook    | [131d6a40c2](https://linux-hardware.org/?probe=131d6a40c2) | Jun 03, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [ea9fb1590a](https://linux-hardware.org/?probe=ea9fb1590a) | Jun 03, 2020 |
| HUAWEI        | KPL-W0X                     | Notebook    | [89038c4214](https://linux-hardware.org/?probe=89038c4214) | Jun 01, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [ee417d15f0](https://linux-hardware.org/?probe=ee417d15f0) | May 31, 2020 |
| HP            | Pavilion dv5                | Notebook    | [41390482f3](https://linux-hardware.org/?probe=41390482f3) | May 30, 2020 |
| Dell          | 0PM561 A00                  | All in one  | [6e0b7c86d5](https://linux-hardware.org/?probe=6e0b7c86d5) | May 30, 2020 |
| Dell          | 0PM561 A00                  | All in one  | [9a4a664a94](https://linux-hardware.org/?probe=9a4a664a94) | May 30, 2020 |
| Positivo      | S14CT01                     | Notebook    | [027689152b](https://linux-hardware.org/?probe=027689152b) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [4a7ecd1578](https://linux-hardware.org/?probe=4a7ecd1578) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [51f3309bfb](https://linux-hardware.org/?probe=51f3309bfb) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [73d7cd6398](https://linux-hardware.org/?probe=73d7cd6398) | May 27, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [663bfb0664](https://linux-hardware.org/?probe=663bfb0664) | May 27, 2020 |
| Biostar       | GF7025-M2                   | Desktop     | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [0686c2c434](https://linux-hardware.org/?probe=0686c2c434) | May 25, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [78df8e8526](https://linux-hardware.org/?probe=78df8e8526) | May 21, 2020 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [4da7cc2128](https://linux-hardware.org/?probe=4da7cc2128) | May 21, 2020 |
| HP            | 21B4 A01                    | Desktop     | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [a68c9e0a74](https://linux-hardware.org/?probe=a68c9e0a74) | May 18, 2020 |
| ASUSTek       | X201E                       | Notebook    | [aa1e3973cf](https://linux-hardware.org/?probe=aa1e3973cf) | May 18, 2020 |
| Packard Be... | EN Butterfly s              | Notebook    | [587286fd1b](https://linux-hardware.org/?probe=587286fd1b) | May 17, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| Gigabyte      | K8M800-8237                 | Desktop     | [8e2c1f0e62](https://linux-hardware.org/?probe=8e2c1f0e62) | May 13, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [c0cf69cb37](https://linux-hardware.org/?probe=c0cf69cb37) | May 13, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [a8c07c11cb](https://linux-hardware.org/?probe=a8c07c11cb) | May 09, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [dd51c6c85e](https://linux-hardware.org/?probe=dd51c6c85e) | May 09, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [7ee061c41d](https://linux-hardware.org/?probe=7ee061c41d) | May 09, 2020 |
| Acer          | Aspire XC-703G              | Desktop     | [87c5ee1001](https://linux-hardware.org/?probe=87c5ee1001) | May 07, 2020 |
| HP            | Notebook                    | Notebook    | [0cab8a6d17](https://linux-hardware.org/?probe=0cab8a6d17) | May 07, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [baf1cb6830](https://linux-hardware.org/?probe=baf1cb6830) | May 06, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | Notebook    | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| HP            | 17E2                        | Mini pc     | [fe57173b3f](https://linux-hardware.org/?probe=fe57173b3f) | May 01, 2020 |
| Intel         | DN2800MT AAG23738-801       | Desktop     | [eba41acd95](https://linux-hardware.org/?probe=eba41acd95) | Apr 29, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [1a00b67e81](https://linux-hardware.org/?probe=1a00b67e81) | Apr 27, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [74edb3ce25](https://linux-hardware.org/?probe=74edb3ce25) | Apr 26, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [734c5c160a](https://linux-hardware.org/?probe=734c5c160a) | Apr 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Lubuntu_20.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 32        | 7.34%   |
| 5.4.0-52-generic  | 22        | 5.05%   |
| 5.4.0-48-generic  | 13        | 2.98%   |
| 5.4.0-47-generic  | 12        | 2.75%   |
| 5.4.0-26-generic  | 12        | 2.75%   |
| 5.4.0-54-generic  | 11        | 2.52%   |
| 5.4.0-40-generic  | 11        | 2.52%   |
| 5.13.0-28-generic | 11        | 2.52%   |
| 5.11.0-27-generic | 11        | 2.52%   |
| 5.4.0-29-generic  | 10        | 2.29%   |
| 5.4.0-33-generic  | 9         | 2.06%   |
| 5.8.0-50-generic  | 8         | 1.83%   |
| 5.4.0-65-generic  | 8         | 1.83%   |
| 5.13.0-30-generic | 8         | 1.83%   |
| 5.11.0-38-generic | 8         | 1.83%   |
| 5.4.0-37-generic  | 7         | 1.61%   |
| 5.13.0-40-generic | 7         | 1.61%   |
| 5.8.0-53-generic  | 6         | 1.38%   |
| 5.8.0-41-generic  | 6         | 1.38%   |
| 5.4.0-73-generic  | 6         | 1.38%   |
| 5.4.0-72-generic  | 6         | 1.38%   |
| 5.4.0-67-generic  | 6         | 1.38%   |
| 5.11.0-43-generic | 6         | 1.38%   |
| 5.8.0-55-generic  | 5         | 1.15%   |
| 5.8.0-45-generic  | 5         | 1.15%   |
| 5.4.0-91-generic  | 5         | 1.15%   |
| 5.4.0-89-generic  | 5         | 1.15%   |
| 5.4.0-60-generic  | 5         | 1.15%   |
| 5.4.0-59-generic  | 5         | 1.15%   |
| 5.4.0-58-generic  | 5         | 1.15%   |
| 5.4.0-51-generic  | 5         | 1.15%   |
| 5.4.0-122-generic | 5         | 1.15%   |
| 5.15.0-41-generic | 5         | 1.15%   |
| 5.11.0-37-generic | 5         | 1.15%   |
| 5.8.0-63-generic  | 4         | 0.92%   |
| 5.8.0-59-generic  | 4         | 0.92%   |
| 5.4.0-77-generic  | 4         | 0.92%   |
| 5.4.0-66-generic  | 4         | 0.92%   |
| 5.4.0-56-generic  | 4         | 0.92%   |
| 5.4.0-45-generic  | 4         | 0.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 248       | 60.78%  |
| 5.8.0   | 51        | 12.5%   |
| 5.11.0  | 47        | 11.52%  |
| 5.13.0  | 40        | 9.8%    |
| 5.15.0  | 11        | 2.7%    |
| 5.6.0   | 2         | 0.49%   |
| 5.9.0   | 1         | 0.25%   |
| 5.7.9   | 1         | 0.25%   |
| 5.6.15  | 1         | 0.25%   |
| 5.5.2   | 1         | 0.25%   |
| 5.4.30  | 1         | 0.25%   |
| 5.3.18  | 1         | 0.25%   |
| 5.16.5  | 1         | 0.25%   |
| 5.14.0  | 1         | 0.25%   |
| 5.10.0  | 1         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 249       | 61.03%  |
| 5.8     | 51        | 12.5%   |
| 5.11    | 47        | 11.52%  |
| 5.13    | 40        | 9.8%    |
| 5.15    | 11        | 2.7%    |
| 5.6     | 3         | 0.74%   |
| 5.9     | 1         | 0.25%   |
| 5.7     | 1         | 0.25%   |
| 5.5     | 1         | 0.25%   |
| 5.3     | 1         | 0.25%   |
| 5.16    | 1         | 0.25%   |
| 5.14    | 1         | 0.25%   |
| 5.10    | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 402       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 381       | 94.31%  |
| LXDE       | 9         | 2.23%   |
| GNOME      | 6         | 1.49%   |
| Cinnamon   | 2         | 0.5%    |
| XFCE       | 1         | 0.25%   |
| X-Cinnamon | 1         | 0.25%   |
| MATE       | 1         | 0.25%   |
| KDE5       | 1         | 0.25%   |
| KDE        | 1         | 0.25%   |
| i3         | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 382       | 94.79%  |
| Tty     | 18        | 4.47%   |
| Wayland | 2         | 0.5%    |
| Unknown | 1         | 0.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 216       | 52.68%  |
| Unknown | 127       | 30.98%  |
| GDM     | 25        | 6.1%    |
| LightDM | 21        | 5.12%   |
| TDM     | 17        | 4.15%   |
| GDM3    | 3         | 0.73%   |
| LXDM    | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 125       | 31.09%  |
| fr_FR   | 49        | 12.19%  |
| pt_BR   | 34        | 8.46%   |
| de_DE   | 26        | 6.47%   |
| en_GB   | 22        | 5.47%   |
| it_IT   | 21        | 5.22%   |
| C       | 18        | 4.48%   |
| ru_RU   | 13        | 3.23%   |
| es_ES   | 10        | 2.49%   |
| en_AU   | 9         | 2.24%   |
| pl_PL   | 6         | 1.49%   |
| ja_JP   | 5         | 1.24%   |
| hu_HU   | 4         | 1%      |
| es_MX   | 4         | 1%      |
| en_CA   | 4         | 1%      |
| nl_NL   | 3         | 0.75%   |
| fr_CH   | 3         | 0.75%   |
| fi_FI   | 3         | 0.75%   |
| es_AR   | 3         | 0.75%   |
| en_ZA   | 3         | 0.75%   |
| en_IE   | 3         | 0.75%   |
| cs_CZ   | 3         | 0.75%   |
| fr_BE   | 2         | 0.5%    |
| es_CR   | 2         | 0.5%    |
| es_CL   | 2         | 0.5%    |
| en_SG   | 2         | 0.5%    |
| en_NZ   | 2         | 0.5%    |
| en_IN   | 2         | 0.5%    |
| el_GR   | 2         | 0.5%    |
| de_CH   | 2         | 0.5%    |
| Unknown | 2         | 0.5%    |
| tr_TR   | 1         | 0.25%   |
| sv_SE   | 1         | 0.25%   |
| ru_UA   | 1         | 0.25%   |
| pt_PT   | 1         | 0.25%   |
| nl_BE   | 1         | 0.25%   |
| lt_LT   | 1         | 0.25%   |
| fr_CA   | 1         | 0.25%   |
| es_UY   | 1         | 0.25%   |
| es_PE   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 232       | 57.71%  |
| EFI  | 170       | 42.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 370       | 92.04%  |
| Overlay | 19        | 4.73%   |
| Btrfs   | 6         | 1.49%   |
| Xfs     | 3         | 0.75%   |
| Zfs     | 1         | 0.25%   |
| F2fs    | 1         | 0.25%   |
| Ext2    | 1         | 0.25%   |
| Aufs    | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 162       | 39.9%   |
| GPT     | 134       | 33%     |
| MBR     | 110       | 27.09%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 356       | 88.12%  |
| Yes       | 48        | 11.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 291       | 71.85%  |
| Yes       | 114       | 28.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 72        | 17.91%  |
| Lenovo                      | 51        | 12.69%  |
| Dell                        | 51        | 12.69%  |
| ASUSTek Computer            | 48        | 11.94%  |
| MSI                         | 21        | 5.22%   |
| Acer                        | 21        | 5.22%   |
| Gigabyte Technology         | 15        | 3.73%   |
| ASRock                      | 15        | 3.73%   |
| Toshiba                     | 13        | 3.23%   |
| Samsung Electronics         | 10        | 2.49%   |
| Intel                       | 9         | 2.24%   |
| Positivo                    | 7         | 1.74%   |
| Notebook                    | 5         | 1.24%   |
| Fujitsu                     | 5         | 1.24%   |
| Apple                       | 5         | 1.24%   |
| Sony                        | 4         | 1%      |
| Pegatron                    | 4         | 1%      |
| Packard Bell                | 4         | 1%      |
| Google                      | 4         | 1%      |
| AAEON                       | 3         | 0.75%   |
| ZOTAC                       | 2         | 0.5%    |
| YASHI                       | 2         | 0.5%    |
| Foxconn                     | 2         | 0.5%    |
| Biostar                     | 2         | 0.5%    |
| AMI                         | 2         | 0.5%    |
| Unknown                     | 2         | 0.5%    |
| UNOWHY                      | 1         | 0.25%   |
| Timi                        | 1         | 0.25%   |
| Supermicro                  | 1         | 0.25%   |
| Star Labs                   | 1         | 0.25%   |
| Prestigio                   | 1         | 0.25%   |
| Panasonic                   | 1         | 0.25%   |
| Mediacom                    | 1         | 0.25%   |
| Lanix                       | 1         | 0.25%   |
| LAMINA                      | 1         | 0.25%   |
| Itautec                     | 1         | 0.25%   |
| IBM                         | 1         | 0.25%   |
| I-Life Digital Technologies | 1         | 0.25%   |
| Hungaro Flotta Kft          | 1         | 0.25%   |
| HUAWEI                      | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| HP Notebook                   | 5         | 1.24%   |
| Unknown                       | 5         | 1.24%   |
| HP Pavilion dv6               | 3         | 0.75%   |
| Dell Latitude D630            | 3         | 0.75%   |
| AAEON MF-001                  | 3         | 0.75%   |
| YASHI MYBOOK 360              | 2         | 0.5%    |
| Positivo H14BT58              | 2         | 0.5%    |
| MSI MS-7C37                   | 2         | 0.5%    |
| MSI MS-7B89                   | 2         | 0.5%    |
| Lenovo IdeaPad 320-15AST 80XV | 2         | 0.5%    |
| HP ProBook 450 G6             | 2         | 0.5%    |
| HP ProBook 440 G8 Notebook PC | 2         | 0.5%    |
| HP ProBook 440 G7             | 2         | 0.5%    |
| HP Pavilion x2 Detachable     | 2         | 0.5%    |
| HP Pavilion g7                | 2         | 0.5%    |
| HP Compaq 6000 Pro SFF PC     | 2         | 0.5%    |
| Dell OptiPlex 790             | 2         | 0.5%    |
| Dell Inspiron 15-3567         | 2         | 0.5%    |
| ASUS M5A97 R2.0               | 2         | 0.5%    |
| ASUS 1015BX                   | 2         | 0.5%    |
| ASRock N68-VS3 UCC            | 2         | 0.5%    |
| ASRock FM2A85X Extreme6       | 2         | 0.5%    |
| Apple MacBookPro8,1           | 2         | 0.5%    |
| ZOTAC ZBOX-CI323NANO          | 1         | 0.25%   |
| ZOTAC NM10                    | 1         | 0.25%   |
| UNOWHY Y13G010S4EI            | 1         | 0.25%   |
| Toshiba Satellite S55-B       | 1         | 0.25%   |
| Toshiba Satellite Pro U400    | 1         | 0.25%   |
| Toshiba Satellite L840        | 1         | 0.25%   |
| Toshiba Satellite L70-B       | 1         | 0.25%   |
| Toshiba Satellite L305        | 1         | 0.25%   |
| Toshiba Satellite C875        | 1         | 0.25%   |
| Toshiba Satellite C855D       | 1         | 0.25%   |
| Toshiba Satellite C70D-B      | 1         | 0.25%   |
| Toshiba Satellite C670D-12N   | 1         | 0.25%   |
| Toshiba Satellite C55D-A      | 1         | 0.25%   |
| Toshiba Satellite A660        | 1         | 0.25%   |
| Toshiba Satellite A205        | 1         | 0.25%   |
| Toshiba NB510                 | 1         | 0.25%   |
| Timi TM1612                   | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 19        | 4.73%   |
| Acer Aspire           | 17        | 4.23%   |
| Lenovo ThinkPad       | 16        | 3.98%   |
| Lenovo IdeaPad        | 16        | 3.98%   |
| HP ProBook            | 13        | 3.23%   |
| HP Pavilion           | 13        | 3.23%   |
| HP Compaq             | 13        | 3.23%   |
| Toshiba Satellite     | 12        | 2.99%   |
| Dell Latitude         | 8         | 1.99%   |
| Dell OptiPlex         | 6         | 1.49%   |
| Lenovo ThinkCentre    | 5         | 1.24%   |
| HP Notebook           | 5         | 1.24%   |
| ASUS VivoBook         | 5         | 1.24%   |
| Unknown               | 5         | 1.24%   |
| HP EliteBook          | 4         | 1%      |
| Dell XPS              | 4         | 1%      |
| Dell Vostro           | 4         | 1%      |
| HP Presario           | 3         | 0.75%   |
| Dell PowerEdge        | 3         | 0.75%   |
| AAEON MF-001          | 3         | 0.75%   |
| YASHI MYBOOK          | 2         | 0.5%    |
| Positivo H14BT58      | 2         | 0.5%    |
| Packard Bell EasyNote | 2         | 0.5%    |
| Notebook W54          | 2         | 0.5%    |
| MSI MS-7C37           | 2         | 0.5%    |
| MSI MS-7B89           | 2         | 0.5%    |
| HP t620               | 2         | 0.5%    |
| HP Spectre            | 2         | 0.5%    |
| HP Laptop             | 2         | 0.5%    |
| Gigabyte B450M        | 2         | 0.5%    |
| Fujitsu LIFEBOOK      | 2         | 0.5%    |
| Dell Studio           | 2         | 0.5%    |
| ASUS M5A97            | 2         | 0.5%    |
| ASUS 1015BX           | 2         | 0.5%    |
| ASRock N68-VS3        | 2         | 0.5%    |
| ASRock FM2A85X        | 2         | 0.5%    |
| Apple MacBookPro8     | 2         | 0.5%    |
| ZOTAC ZBOX-CI323NANO  | 1         | 0.25%   |
| ZOTAC NM10            | 1         | 0.25%   |
| UNOWHY Y13G010S4EI    | 1         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 35        | 8.71%   |
| 2019 | 33        | 8.21%   |
| 2011 | 32        | 7.96%   |
| 2014 | 29        | 7.21%   |
| 2013 | 29        | 7.21%   |
| 2010 | 29        | 7.21%   |
| 2008 | 28        | 6.97%   |
| 2017 | 25        | 6.22%   |
| 2009 | 24        | 5.97%   |
| 2007 | 24        | 5.97%   |
| 2020 | 23        | 5.72%   |
| 2016 | 23        | 5.72%   |
| 2015 | 20        | 4.98%   |
| 2018 | 18        | 4.48%   |
| 2021 | 14        | 3.48%   |
| 2006 | 11        | 2.74%   |
| 2005 | 4         | 1%      |
| 2004 | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 243       | 60.45%  |
| Desktop     | 140       | 34.83%  |
| Convertible | 5         | 1.24%   |
| Mini pc     | 5         | 1.24%   |
| Server      | 5         | 1.24%   |
| Tablet      | 2         | 0.5%    |
| All in one  | 2         | 0.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 374       | 92.8%   |
| Enabled  | 29        | 7.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 397       | 98.76%  |
| Yes  | 5         | 1.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 122       | 30.12%  |
| 4.01-8.0        | 84        | 20.74%  |
| 1.01-2.0        | 63        | 15.56%  |
| 8.01-16.0       | 54        | 13.33%  |
| 16.01-24.0      | 40        | 9.88%   |
| 32.01-64.0      | 15        | 3.7%    |
| 2.01-3.0        | 13        | 3.21%   |
| 24.01-32.0      | 5         | 1.23%   |
| 64.01-256.0     | 4         | 0.99%   |
| 0.51-1.0        | 3         | 0.74%   |
| More than 256.0 | 2         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 207       | 48.71%  |
| 0.51-1.0   | 71        | 16.71%  |
| 2.01-3.0   | 64        | 15.06%  |
| 4.01-8.0   | 43        | 10.12%  |
| 3.01-4.0   | 25        | 5.88%   |
| 0.01-0.5   | 9         | 2.12%   |
| 8.01-16.0  | 4         | 0.94%   |
| 32.01-64.0 | 1         | 0.24%   |
| 16.01-24.0 | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 265       | 65.27%  |
| 2      | 99        | 24.38%  |
| 4      | 14        | 3.45%   |
| 3      | 12        | 2.96%   |
| 5      | 7         | 1.72%   |
| 6      | 3         | 0.74%   |
| 7      | 2         | 0.49%   |
| 0      | 2         | 0.49%   |
| 17     | 1         | 0.25%   |
| 14     | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 206       | 50.86%  |
| No        | 199       | 49.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 358       | 88.83%  |
| No        | 45        | 11.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 300       | 74.63%  |
| No        | 102       | 25.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 223       | 54.79%  |
| Yes       | 184       | 45.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 65        | 16.05%  |
| France       | 52        | 12.84%  |
| Brazil       | 40        | 9.88%   |
| Germany      | 32        | 7.9%    |
| Italy        | 30        | 7.41%   |
| Russia       | 18        | 4.44%   |
| UK           | 15        | 3.7%    |
| Spain        | 12        | 2.96%   |
| Australia    | 10        | 2.47%   |
| Switzerland  | 9         | 2.22%   |
| Poland       | 8         | 1.98%   |
| Netherlands  | 8         | 1.98%   |
| Hungary      | 7         | 1.73%   |
| Finland      | 7         | 1.73%   |
| Mexico       | 6         | 1.48%   |
| Japan        | 5         | 1.23%   |
| Czechia      | 5         | 1.23%   |
| Canada       | 5         | 1.23%   |
| Belgium      | 5         | 1.23%   |
| Ukraine      | 4         | 0.99%   |
| South Africa | 4         | 0.99%   |
| Ireland      | 4         | 0.99%   |
| Romania      | 3         | 0.74%   |
| New Zealand  | 3         | 0.74%   |
| Indonesia    | 3         | 0.74%   |
| Greece       | 3         | 0.74%   |
| Argentina    | 3         | 0.74%   |
| Slovenia     | 2         | 0.49%   |
| Slovakia     | 2         | 0.49%   |
| Singapore    | 2         | 0.49%   |
| Puerto Rico  | 2         | 0.49%   |
| Norway       | 2         | 0.49%   |
| India        | 2         | 0.49%   |
| Costa Rica   | 2         | 0.49%   |
| Colombia     | 2         | 0.49%   |
| Chile        | 2         | 0.49%   |
| Vietnam      | 1         | 0.25%   |
| Uruguay      | 1         | 0.25%   |
| Turkey       | 1         | 0.25%   |
| Tunisia      | 1         | 0.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Rome          | 6         | 1.44%   |
| Paris         | 6         | 1.44%   |
| Milan         | 5         | 1.2%    |
| Melbourne     | 5         | 1.2%    |
| Helsinki      | 4         | 0.96%   |
| Wellington    | 3         | 0.72%   |
| Salvador      | 3         | 0.72%   |
| Pécs         | 3         | 0.72%   |
| Munich        | 3         | 0.72%   |
| Moscow        | 3         | 0.72%   |
| Mexico City   | 3         | 0.72%   |
| Florence      | 3         | 0.72%   |
| Derry         | 3         | 0.72%   |
| Brasília     | 3         | 0.72%   |
| Zurich        | 2         | 0.48%   |
| Yekaterinburg | 2         | 0.48%   |
| Vicosa        | 2         | 0.48%   |
| Stuttgart     | 2         | 0.48%   |
| Southampton   | 2         | 0.48%   |
| Sao Paulo     | 2         | 0.48%   |
| Raahe         | 2         | 0.48%   |
| Poznan        | 2         | 0.48%   |
| Porto Alegre  | 2         | 0.48%   |
| Oradea        | 2         | 0.48%   |
| Omsk          | 2         | 0.48%   |
| Mount Vernon  | 2         | 0.48%   |
| Krakow        | 2         | 0.48%   |
| Jurong West   | 2         | 0.48%   |
| Houston       | 2         | 0.48%   |
| Heredia       | 2         | 0.48%   |
| Hamburg       | 2         | 0.48%   |
| Fortaleza     | 2         | 0.48%   |
| Figeac        | 2         | 0.48%   |
| Curitiba      | 2         | 0.48%   |
| Cuernavaca    | 2         | 0.48%   |
| Cossington    | 2         | 0.48%   |
| Cayey         | 2         | 0.48%   |
| Cape Town     | 2         | 0.48%   |
| Budapest      | 2         | 0.48%   |
| Brooklyn      | 2         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 103       | 132    | 19.29%  |
| WDC                 | 95        | 136    | 17.79%  |
| Samsung Electronics | 59        | 83     | 11.05%  |
| Toshiba             | 36        | 38     | 6.74%   |
| Hitachi             | 34        | 41     | 6.37%   |
| Unknown             | 33        | 39     | 6.18%   |
| Kingston            | 24        | 25     | 4.49%   |
| Crucial             | 21        | 34     | 3.93%   |
| SanDisk             | 14        | 18     | 2.62%   |
| Intel               | 10        | 11     | 1.87%   |
| China               | 9         | 9      | 1.69%   |
| A-DATA Technology   | 8         | 9      | 1.5%    |
| SK hynix            | 7         | 7      | 1.31%   |
| HGST                | 7         | 9      | 1.31%   |
| Fujitsu             | 7         | 7      | 1.31%   |
| PNY                 | 4         | 4      | 0.75%   |
| Maxtor              | 4         | 4      | 0.75%   |
| Apacer              | 4         | 4      | 0.75%   |
| Team                | 3         | 3      | 0.56%   |
| Micron Technology   | 3         | 3      | 0.56%   |
| LITEONIT            | 3         | 3      | 0.56%   |
| LDLC                | 3         | 3      | 0.56%   |
| KIOXIA              | 3         | 3      | 0.56%   |
| JMicron Technology  | 3         | 3      | 0.56%   |
| Corsair             | 3         | 3      | 0.56%   |
| USB                 | 2         | 2      | 0.37%   |
| Transcend           | 2         | 2      | 0.37%   |
| OCZ                 | 2         | 2      | 0.37%   |
| Intenso             | 2         | 2      | 0.37%   |
| Unknown             | 2         | 3      | 0.37%   |
| TO Exter            | 1         | 1      | 0.19%   |
| TCSUNBOW            | 1         | 1      | 0.19%   |
| Star                | 1         | 1      | 0.19%   |
| SPCC                | 1         | 1      | 0.19%   |
| PNY USB             | 1         | 1      | 0.19%   |
| Phison Electronics  | 1         | 1      | 0.19%   |
| Patriot             | 1         | 1      | 0.19%   |
| ORTIAL              | 1         | 1      | 0.19%   |
| Londisk             | 1         | 1      | 0.19%   |
| LITEON              | 1         | 2      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 8         | 1.39%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 7         | 1.22%   |
| Kingston SA400S37240G 240GB SSD      | 7         | 1.22%   |
| Toshiba MQ01ABF050 500GB             | 5         | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 0.87%   |
| Toshiba MQ01ABD100 1TB               | 4         | 0.7%    |
| Seagate ST500LT012-1DG142 500GB      | 4         | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 0.7%    |
| Samsung SSD 850 EVO 500GB            | 4         | 0.7%    |
| Crucial CT480BX500SSD1 480GB         | 4         | 0.7%    |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.7%    |
| A-DATA SU650 240GB SSD               | 4         | 0.7%    |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 3         | 0.52%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 0.52%   |
| WDC WD10SPZX-24Z10T0 1TB             | 3         | 0.52%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB | 3         | 0.52%   |
| Unknown SD/MMC/MS PRO 2GB            | 3         | 0.52%   |
| Seagate ST9500325AS 500GB            | 3         | 0.52%   |
| Seagate Backup+ Hub BK 8TB           | 3         | 0.52%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.52%   |
| Samsung HD502IJ 500GB                | 3         | 0.52%   |
| Samsung HD103SJ 1TB                  | 3         | 0.52%   |
| Hitachi HTS543232A7A384 320GB        | 3         | 0.52%   |
| WDC WD800JD-60LSA5 80GB              | 2         | 0.35%   |
| WDC WD7500BPVX-55JC3T3 752GB         | 2         | 0.35%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 0.35%   |
| WDC WD40EFRX-68N32N0 4TB             | 2         | 0.35%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.35%   |
| WDC WD2500AAKX-07U6AA1 250GB         | 2         | 0.35%   |
| WDC WD2500AAJS-75M0A0 250GB          | 2         | 0.35%   |
| WDC WD10EZEX-00WN4A0 1TB             | 2         | 0.35%   |
| WDC WD10EACS-00D6B0 1TB              | 2         | 0.35%   |
| USB 3.0 3TB                          | 2         | 0.35%   |
| Unknown MMC Card  64GB               | 2         | 0.35%   |
| Unknown MMC Card  16GB               | 2         | 0.35%   |
| Unknown MMC Card  128GB              | 2         | 0.35%   |
| Unknown M52516  16GB                 | 2         | 0.35%   |
| Unknown DA4064  64GB                 | 2         | 0.35%   |
| Unknown 128G32  128GB                | 2         | 0.35%   |
| Toshiba THNSFJ256GDNU A 256GB SSD    | 2         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 103       | 132    | 35.15%  |
| WDC                 | 81        | 117    | 27.65%  |
| Hitachi             | 34        | 41     | 11.6%   |
| Toshiba             | 29        | 31     | 9.9%    |
| Samsung Electronics | 23        | 28     | 7.85%   |
| HGST                | 7         | 9      | 2.39%   |
| Fujitsu             | 7         | 7      | 2.39%   |
| Unknown             | 3         | 3      | 1.02%   |
| Maxtor              | 3         | 3      | 1.02%   |
| USB                 | 2         | 2      | 0.68%   |
| LaCie               | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 33     | 16.05%  |
| Crucial             | 21        | 34     | 12.96%  |
| Kingston            | 20        | 20     | 12.35%  |
| WDC                 | 12        | 15     | 7.41%   |
| SanDisk             | 10        | 14     | 6.17%   |
| China               | 9         | 9      | 5.56%   |
| Intel               | 7         | 8      | 4.32%   |
| A-DATA Technology   | 6         | 7      | 3.7%    |
| Toshiba             | 4         | 4      | 2.47%   |
| PNY                 | 4         | 4      | 2.47%   |
| Apacer              | 4         | 4      | 2.47%   |
| Team                | 3         | 3      | 1.85%   |
| LITEONIT            | 3         | 3      | 1.85%   |
| Corsair             | 3         | 3      | 1.85%   |
| Transcend           | 2         | 2      | 1.23%   |
| SK hynix            | 2         | 2      | 1.23%   |
| OCZ                 | 2         | 2      | 1.23%   |
| LDLC                | 2         | 2      | 1.23%   |
| Intenso             | 2         | 2      | 1.23%   |
| Unknown             | 1         | 1      | 0.62%   |
| TO Exter            | 1         | 1      | 0.62%   |
| TCSUNBOW            | 1         | 1      | 0.62%   |
| Star                | 1         | 1      | 0.62%   |
| SPCC                | 1         | 1      | 0.62%   |
| PNY USB             | 1         | 1      | 0.62%   |
| Patriot             | 1         | 1      | 0.62%   |
| ORTIAL              | 1         | 1      | 0.62%   |
| Micron Technology   | 1         | 1      | 0.62%   |
| Maxtor              | 1         | 1      | 0.62%   |
| Londisk             | 1         | 1      | 0.62%   |
| LITEON              | 1         | 2      | 0.62%   |
| Lexar               | 1         | 1      | 0.62%   |
| Leven               | 1         | 2      | 0.62%   |
| KingDian            | 1         | 1      | 0.62%   |
| Integral            | 1         | 1      | 0.62%   |
| Hewlett-Packard     | 1         | 6      | 0.62%   |
| GOODRAM             | 1         | 1      | 0.62%   |
| Dell                | 1         | 1      | 0.62%   |
| Apple               | 1         | 3      | 0.62%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 251       | 374    | 51.75%  |
| SSD     | 153       | 200    | 31.55%  |
| NVMe    | 42        | 55     | 8.66%   |
| MMC     | 33        | 41     | 6.8%    |
| Unknown | 6         | 6      | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 344       | 554    | 78.72%  |
| NVMe | 40        | 53     | 9.15%   |
| MMC  | 33        | 41     | 7.55%   |
| SAS  | 20        | 28     | 4.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 279       | 379    | 68.72%  |
| 0.51-1.0   | 93        | 145    | 22.91%  |
| 1.01-2.0   | 19        | 25     | 4.68%   |
| 2.01-3.0   | 7         | 8      | 1.72%   |
| 3.01-4.0   | 5         | 13     | 1.23%   |
| 4.01-10.0  | 3         | 4      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 108       | 26.41%  |
| 251-500        | 106       | 25.92%  |
| 501-1000       | 49        | 11.98%  |
| 51-100         | 38        | 9.29%   |
| 1-20           | 28        | 6.85%   |
| 1001-2000      | 26        | 6.36%   |
| 21-50          | 22        | 5.38%   |
| More than 3000 | 21        | 5.13%   |
| 2001-3000      | 9         | 2.2%    |
| Unknown        | 2         | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 180       | 43.27%  |
| 21-50          | 74        | 17.79%  |
| 101-250        | 53        | 12.74%  |
| 51-100         | 34        | 8.17%   |
| 251-500        | 25        | 6.01%   |
| 501-1000       | 24        | 5.77%   |
| 1001-2000      | 10        | 2.4%    |
| More than 3000 | 9         | 2.16%   |
| 2001-3000      | 5         | 1.2%    |
| Unknown        | 2         | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 3.23%   |
| Seagate ST1000DM003-9YN162 1TB        | 2         | 2      | 3.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 1.61%   |
| WDC WD800BEVS-60RST0 80GB             | 1         | 1      | 1.61%   |
| WDC WD5000LUCT-62C26Y0 500GB          | 1         | 1      | 1.61%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 1      | 1.61%   |
| WDC WD400EB-00CPF0 40GB               | 1         | 1      | 1.61%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 1.61%   |
| WDC WD3200BEVT-75A23T0 320GB          | 1         | 1      | 1.61%   |
| WDC WD3200AAJS-00L7A0 320GB           | 1         | 1      | 1.61%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 2      | 1.61%   |
| WDC WD2500AAJS-75M0A0 250GB           | 1         | 1      | 1.61%   |
| WDC WD1600AAJS-60B4A0 160GB           | 1         | 2      | 1.61%   |
| WDC WD10EADS-65M2B0 1TB               | 1         | 1      | 1.61%   |
| Toshiba MK5059GSXP 500GB              | 1         | 1      | 1.61%   |
| TCSUNBOW X1 32GB SSD                  | 1         | 1      | 1.61%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 1.61%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 1.61%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 1.61%   |
| Seagate ST9250410AS 250GB             | 1         | 1      | 1.61%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.61%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.61%   |
| Seagate ST380815AS 80GB               | 1         | 1      | 1.61%   |
| Seagate ST360012A 64GB                | 1         | 1      | 1.61%   |
| Seagate ST3360320AS 360GB             | 1         | 1      | 1.61%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 1.61%   |
| Seagate ST3200822AS 200GB             | 1         | 1      | 1.61%   |
| Seagate ST3160318AS 160GB             | 1         | 1      | 1.61%   |
| Seagate ST2000DX002-2DV164 2TB        | 1         | 1      | 1.61%   |
| Seagate ST1000NM0095-2DC10C 1TB       | 1         | 6      | 1.61%   |
| Seagate ST1000DX001-1CM162 1TB        | 1         | 1      | 1.61%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 1      | 1.61%   |
| SanDisk SSD PLUS 120GB                | 1         | 1      | 1.61%   |
| Samsung Electronics HM160JI 160GB     | 1         | 1      | 1.61%   |
| Samsung Electronics HM121HI 120GB     | 1         | 2      | 1.61%   |
| Samsung Electronics HD502IJ 500GB     | 1         | 1      | 1.61%   |
| Maxtor STM3300622A 304GB              | 1         | 1      | 1.61%   |
| Maxtor 6Y080L0 81GB                   | 1         | 1      | 1.61%   |
| Maxtor 6B200M0 208GB                  | 1         | 1      | 1.61%   |
| LDLC SSD 120GB                        | 1         | 1      | 1.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 23     | 29.51%  |
| WDC                 | 12        | 14     | 19.67%  |
| Hitachi             | 7         | 8      | 11.48%  |
| Samsung Electronics | 3         | 4      | 4.92%   |
| Maxtor              | 3         | 3      | 4.92%   |
| Kingston            | 3         | 3      | 4.92%   |
| HGST                | 3         | 3      | 4.92%   |
| Crucial             | 3         | 3      | 4.92%   |
| SK hynix            | 2         | 2      | 3.28%   |
| Toshiba             | 1         | 1      | 1.64%   |
| TCSUNBOW            | 1         | 1      | 1.64%   |
| SanDisk             | 1         | 1      | 1.64%   |
| LDLC                | 1         | 1      | 1.64%   |
| Fujitsu             | 1         | 1      | 1.64%   |
| Apacer              | 1         | 1      | 1.64%   |
| A-DATA Technology   | 1         | 1      | 1.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 23     | 38.3%   |
| WDC                 | 11        | 13     | 23.4%   |
| Hitachi             | 7         | 8      | 14.89%  |
| Samsung Electronics | 3         | 4      | 6.38%   |
| Maxtor              | 3         | 3      | 6.38%   |
| HGST                | 3         | 3      | 6.38%   |
| Toshiba             | 1         | 1      | 2.13%   |
| Fujitsu             | 1         | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 56     | 75.86%  |
| SSD  | 14        | 14     | 24.14%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 25%     |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 25%     |
| Samsung Electronics SSD 850 250GB | 1         | 1      | 25%     |
| Samsung Electronics HD080HJ/ 80GB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 3      | 50%     |
| Samsung Electronics | 2         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 191       | 323    | 43.61%  |
| Works    | 187       | 278    | 42.69%  |
| Malfunc  | 56        | 70     | 12.79%  |
| Failed   | 4         | 5      | 0.91%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 272       | 63.55%  |
| AMD                              | 75        | 17.52%  |
| Nvidia                           | 20        | 4.67%   |
| Samsung Electronics              | 11        | 2.57%   |
| SanDisk                          | 6         | 1.4%    |
| JMicron Technology               | 6         | 1.4%    |
| Marvell Technology Group         | 5         | 1.17%   |
| LSI Logic / Symbios Logic        | 4         | 0.93%   |
| Kingston Technology Company      | 4         | 0.93%   |
| ASMedia Technology               | 4         | 0.93%   |
| Toshiba America Info Systems     | 3         | 0.7%    |
| SK hynix                         | 3         | 0.7%    |
| KIOXIA                           | 3         | 0.7%    |
| VIA Technologies                 | 2         | 0.47%   |
| Micron Technology                | 2         | 0.47%   |
| ADATA Technology                 | 2         | 0.47%   |
| Solid State Storage Technology   | 1         | 0.23%   |
| Silicon Motion                   | 1         | 0.23%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| Phison Electronics               | 1         | 0.23%   |
| Hewlett-Packard                  | 1         | 0.23%   |
| Broadcom / LSI                   | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 47        | 8.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 20        | 3.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 19        | 3.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 18        | 3.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 3.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 2.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 14        | 2.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 14        | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 2.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 2.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 10        | 1.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 1.89%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 9         | 1.7%    |
| Nvidia MCP61 SATA Controller                                                     | 8         | 1.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 8         | 1.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 8         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 1.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 1.14%   |
| Nvidia MCP61 IDE                                                                 | 6         | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 1.14%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 1.14%   |
| Intel SATA Controller [RAID mode]                                                | 6         | 1.14%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 6         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 6         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 1.14%   |
| JMicron JMB363 SATA/IDE Controller                                               | 5         | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 0.95%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 5         | 0.95%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 5         | 0.95%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 5         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 5         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 0.95%   |
| AMD 400 Series Chipset SATA Controller                                           | 5         | 0.95%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 4         | 0.76%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 0.76%   |
| Kingston Company Company Non-Volatile memory controller                          | 4         | 0.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 290       | 63.32%  |
| IDE  | 100       | 21.83%  |
| NVMe | 39        | 8.52%   |
| RAID | 27        | 5.9%    |
| SCSI | 2         | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 306       | 76.12%  |
| AMD    | 96        | 23.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 7         | 1.74%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 6         | 1.49%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 6         | 1.49%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 5         | 1.24%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 5         | 1.24%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 5         | 1.24%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4         | 1%      |
| Intel Celeron CPU 847 @ 1.10GHz             | 4         | 1%      |
| AMD E-300 APU with Radeon HD Graphics       | 4         | 1%      |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 3         | 0.75%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 0.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 0.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 0.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 0.75%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 0.75%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 0.75%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3         | 0.75%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 0.75%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 3         | 0.75%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3         | 0.75%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3         | 0.75%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 3         | 0.75%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 2         | 0.5%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 2         | 0.5%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2         | 0.5%    |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 2         | 0.5%    |
| Intel Pentium CPU N3710 @ 1.60GHz           | 2         | 0.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 0.5%    |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 0.5%    |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 0.5%    |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2         | 0.5%    |
| Intel Core i7-2640M CPU @ 2.80GHz           | 2         | 0.5%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 2         | 0.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 0.5%    |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 2         | 0.5%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 0.5%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 66        | 16.42%  |
| Intel Core i3           | 37        | 9.2%    |
| Intel Core i7           | 36        | 8.96%   |
| Intel Celeron           | 34        | 8.46%   |
| Intel Core 2 Duo        | 32        | 7.96%   |
| Intel Atom              | 30        | 7.46%   |
| Intel Pentium Dual-Core | 12        | 2.99%   |
| Other                   | 10        | 2.49%   |
| Intel Xeon              | 10        | 2.49%   |
| Intel Pentium           | 9         | 2.24%   |
| Intel Core 2            | 9         | 2.24%   |
| AMD Ryzen 7             | 9         | 2.24%   |
| AMD Ryzen 5             | 8         | 1.99%   |
| AMD Athlon 64 X2        | 7         | 1.74%   |
| Intel Pentium Dual      | 6         | 1.49%   |
| AMD E                   | 6         | 1.49%   |
| AMD Athlon II X2        | 6         | 1.49%   |
| Intel Core 2 Quad       | 5         | 1.24%   |
| AMD A10                 | 5         | 1.24%   |
| AMD Ryzen 3             | 4         | 1%      |
| AMD E1                  | 4         | 1%      |
| AMD A6                  | 4         | 1%      |
| Intel Pentium Silver    | 3         | 0.75%   |
| Intel Celeron Dual-Core | 3         | 0.75%   |
| AMD FX                  | 3         | 0.75%   |
| AMD Athlon 64           | 3         | 0.75%   |
| AMD A4                  | 3         | 0.75%   |
| Intel Pentium 4         | 2         | 0.5%    |
| AMD Turion 64 X2 Mobile | 2         | 0.5%    |
| AMD Sempron             | 2         | 0.5%    |
| AMD Ryzen Threadripper  | 2         | 0.5%    |
| AMD Ryzen 7 PRO         | 2         | 0.5%    |
| AMD Phenom II           | 2         | 0.5%    |
| AMD GX                  | 2         | 0.5%    |
| AMD Athlon X2           | 2         | 0.5%    |
| AMD A8                  | 2         | 0.5%    |
| Intel Pentium Gold      | 1         | 0.25%   |
| Intel Genuine           | 1         | 0.25%   |
| Intel Core m3           | 1         | 0.25%   |
| Intel Core 2 Solo       | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 241       | 59.95%  |
| 4      | 110       | 27.36%  |
| 1      | 17        | 4.23%   |
| 8      | 14        | 3.48%   |
| 6      | 12        | 2.99%   |
| 12     | 2         | 0.5%    |
| 3      | 2         | 0.5%    |
| 64     | 1         | 0.25%   |
| 40     | 1         | 0.25%   |
| 20     | 1         | 0.25%   |
| 16     | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 396       | 98.51%  |
| 2      | 5         | 1.24%   |
| 4      | 1         | 0.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 221       | 54.98%  |
| 2      | 181       | 45.02%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 402       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 10.37%  |
| 0x206a7    | 34        | 8.4%    |
| 0x1067a    | 23        | 5.68%   |
| 0x6fd      | 17        | 4.2%    |
| 0x306c3    | 16        | 3.95%   |
| 0x306a9    | 16        | 3.95%   |
| 0x406e3    | 12        | 2.96%   |
| 0x406c4    | 12        | 2.96%   |
| 0x40651    | 12        | 2.96%   |
| 0x30678    | 11        | 2.72%   |
| 0x10676    | 10        | 2.47%   |
| 0x806ec    | 9         | 2.22%   |
| 0x406c3    | 9         | 2.22%   |
| 0x20655    | 9         | 2.22%   |
| 0x05000119 | 9         | 2.22%   |
| 0x06006705 | 8         | 1.98%   |
| 0x706a1    | 6         | 1.48%   |
| 0x6fb      | 6         | 1.48%   |
| 0x6f6      | 6         | 1.48%   |
| 0x306d4    | 6         | 1.48%   |
| 0x106ca    | 6         | 1.48%   |
| 0x06001119 | 6         | 1.48%   |
| 0x010000c8 | 6         | 1.48%   |
| 0x806e9    | 5         | 1.23%   |
| 0x806c1    | 5         | 1.23%   |
| 0x20652    | 5         | 1.23%   |
| 0x906e9    | 4         | 0.99%   |
| 0x30661    | 4         | 0.99%   |
| 0x906ea    | 3         | 0.74%   |
| 0x806eb    | 3         | 0.74%   |
| 0x706a8    | 3         | 0.74%   |
| 0x08701021 | 3         | 0.74%   |
| 0x08600106 | 3         | 0.74%   |
| 0x0800820d | 3         | 0.74%   |
| 0x07030105 | 3         | 0.74%   |
| 0x0700010f | 3         | 0.74%   |
| 0x06000852 | 3         | 0.74%   |
| 0xa0653    | 2         | 0.49%   |
| 0x906ed    | 2         | 0.49%   |
| 0x706e5    | 2         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 38        | 9.45%   |
| Core            | 37        | 9.2%    |
| Silvermont      | 35        | 8.71%   |
| Penryn          | 35        | 8.71%   |
| Haswell         | 33        | 8.21%   |
| KabyLake        | 29        | 7.21%   |
| Westmere        | 18        | 4.48%   |
| IvyBridge       | 18        | 4.48%   |
| Skylake         | 17        | 4.23%   |
| K8 Hammer       | 15        | 3.73%   |
| Zen 2           | 13        | 3.23%   |
| K10             | 13        | 3.23%   |
| Bonnell         | 11        | 2.74%   |
| Bobcat          | 11        | 2.74%   |
| Zen+            | 9         | 2.24%   |
| Piledriver      | 9         | 2.24%   |
| Goldmont plus   | 9         | 2.24%   |
| Excavator       | 9         | 2.24%   |
| Broadwell       | 7         | 1.74%   |
| TigerLake       | 6         | 1.49%   |
| Puma            | 6         | 1.49%   |
| CometLake       | 4         | 1%      |
| K8 & K10 hybrid | 3         | 0.75%   |
| Jaguar          | 3         | 0.75%   |
| Icelake         | 3         | 0.75%   |
| Goldmont        | 3         | 0.75%   |
| Zen 3           | 2         | 0.5%    |
| Zen             | 2         | 0.5%    |
| NetBurst        | 2         | 0.5%    |
| Steamroller     | 1         | 0.25%   |
| Nehalem         | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 242       | 54.75%  |
| AMD                              | 105       | 23.76%  |
| Nvidia                           | 90        | 20.36%  |
| Matrox Electronics Systems       | 4         | 0.9%    |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 32        | 6.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 4.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 3.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 3.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 3.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 3%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 2.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 2.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 1.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 1.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.71%   |
| Nvidia GT218 [GeForce 210]                                                               | 6         | 1.28%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 1.28%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.28%   |
| AMD Renoir                                                                               | 6         | 1.28%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 5         | 1.07%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.07%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 1.07%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.07%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 0.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 0.86%   |
| Intel HD Graphics 620                                                                    | 4         | 0.86%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 0.86%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 0.86%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.86%   |
| AMD Richland [Radeon HD 8670D]                                                           | 4         | 0.86%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.64%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.64%   |
| Intel HD Graphics 530                                                                    | 3         | 0.64%   |
| Intel HD Graphics 500                                                                    | 3         | 0.64%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.64%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.64%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.64%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 207       | 51.36%  |
| 1 x AMD         | 87        | 21.59%  |
| 1 x Nvidia      | 63        | 15.63%  |
| Intel + Nvidia  | 22        | 5.46%   |
| Intel + AMD     | 11        | 2.73%   |
| 2 x AMD         | 5         | 1.24%   |
| 1 x Matrox      | 3         | 0.74%   |
| AMD + Nvidia    | 2         | 0.5%    |
| 2 x Nvidia      | 1         | 0.25%   |
| 1 x SiS         | 1         | 0.25%   |
| Nvidia + Matrox | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 354       | 87.84%  |
| Proprietary | 44        | 10.92%  |
| Unknown     | 5         | 1.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 228       | 56.44%  |
| 0.01-0.5   | 88        | 21.78%  |
| 0.51-1.0   | 36        | 8.91%   |
| 1.01-2.0   | 31        | 7.67%   |
| 3.01-4.0   | 12        | 2.97%   |
| 7.01-8.0   | 3         | 0.74%   |
| 2.01-3.0   | 3         | 0.74%   |
| 8.01-16.0  | 2         | 0.5%    |
| 5.01-6.0   | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 53        | 12.9%   |
| AU Optronics            | 50        | 12.17%  |
| LG Display              | 40        | 9.73%   |
| BOE                     | 34        | 8.27%   |
| Chimei Innolux          | 33        | 8.03%   |
| Dell                    | 26        | 6.33%   |
| Goldstar                | 20        | 4.87%   |
| Acer                    | 18        | 4.38%   |
| Hewlett-Packard         | 15        | 3.65%   |
| Lenovo                  | 11        | 2.68%   |
| Chi Mei Optoelectronics | 8         | 1.95%   |
| Philips                 | 7         | 1.7%    |
| BenQ                    | 7         | 1.7%    |
| Apple                   | 6         | 1.46%   |
| Vizio                   | 5         | 1.22%   |
| LG Philips              | 5         | 1.22%   |
| Iiyama                  | 5         | 1.22%   |
| Sharp                   | 4         | 0.97%   |
| InfoVision              | 4         | 0.97%   |
| AOC                     | 4         | 0.97%   |
| Ancor Communications    | 4         | 0.97%   |
| Unknown                 | 3         | 0.73%   |
| Sony                    | 3         | 0.73%   |
| PANDA                   | 3         | 0.73%   |
| NEC Computers           | 3         | 0.73%   |
| HannStar                | 3         | 0.73%   |
| LG Electronics          | 2         | 0.49%   |
| Lenovo Group Limited    | 2         | 0.49%   |
| IOD                     | 2         | 0.49%   |
| InnoLux Display         | 2         | 0.49%   |
| FL_                     | 2         | 0.49%   |
| CVT                     | 2         | 0.49%   |
| CPT                     | 2         | 0.49%   |
| ___                     | 1         | 0.24%   |
| ViewSonic               | 1         | 0.24%   |
| Videoseven              | 1         | 0.24%   |
| Unknown (ADA)           | 1         | 0.24%   |
| SHD                     | 1         | 0.24%   |
| Sceptre Tech            | 1         | 0.24%   |
| Proview                 | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 1.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 3         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 3         | 0.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.72%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 3         | 0.72%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 0.72%   |
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch  | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 2         | 0.48%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 2         | 0.48%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2         | 0.48%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch               | 2         | 0.48%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 2         | 0.48%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch           | 2         | 0.48%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch             | 2         | 0.48%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                 | 2         | 0.48%   |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                      | 2         | 0.48%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2         | 0.48%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.48%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 2         | 0.48%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 0.48%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 0.48%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                  | 2         | 0.48%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                  | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch         | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 0.48%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 2         | 0.48%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 2         | 0.48%   |
| ___ TV ___9000 1360x768                                               | 1         | 0.24%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 1         | 0.24%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1         | 0.24%   |
| Vizio VL320M VIZ0050 1920x1080 698x393mm 31.5-inch                    | 1         | 0.24%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                    | 1         | 0.24%   |
| Vizio E500AR VIZ0090 1920x1080 477x268mm 21.5-inch                    | 1         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 117       | 28.96%  |
| 1920x1080 (FHD)    | 111       | 27.48%  |
| 1280x1024 (SXGA)   | 30        | 7.43%   |
| 1280x800 (WXGA)    | 25        | 6.19%   |
| 1600x900 (HD+)     | 24        | 5.94%   |
| 1680x1050 (WSXGA+) | 21        | 5.2%    |
| 1440x900 (WXGA+)   | 14        | 3.47%   |
| 3840x2160 (4K)     | 13        | 3.22%   |
| 1920x1200 (WUXGA)  | 10        | 2.48%   |
| 2560x1440 (QHD)    | 9         | 2.23%   |
| 1024x768 (XGA)     | 7         | 1.73%   |
| 1024x600           | 4         | 0.99%   |
| 2560x1600          | 3         | 0.74%   |
| 3440x1440          | 2         | 0.5%    |
| 2560x1080          | 2         | 0.5%    |
| 1600x1200          | 2         | 0.5%    |
| 1360x768           | 2         | 0.5%    |
| 3840x2400          | 1         | 0.25%   |
| 3600x1200          | 1         | 0.25%   |
| 2288x1287          | 1         | 0.25%   |
| 2048x1152          | 1         | 0.25%   |
| 1920x540           | 1         | 0.25%   |
| 1280x768           | 1         | 0.25%   |
| 1280x720 (HD)      | 1         | 0.25%   |
| Unknown            | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 108       | 26.21%  |
| 13      | 42        | 10.19%  |
| 17      | 40        | 9.71%   |
| 14      | 39        | 9.47%   |
| 27      | 19        | 4.61%   |
| 23      | 18        | 4.37%   |
| 21      | 17        | 4.13%   |
| 19      | 17        | 4.13%   |
| 24      | 16        | 3.88%   |
| 11      | 14        | 3.4%    |
| Unknown | 14        | 3.4%    |
| 22      | 13        | 3.16%   |
| 20      | 11        | 2.67%   |
| 18      | 8         | 1.94%   |
| 10      | 7         | 1.7%    |
| 12      | 5         | 1.21%   |
| 72      | 3         | 0.73%   |
| 34      | 3         | 0.73%   |
| 84      | 2         | 0.49%   |
| 41      | 2         | 0.49%   |
| 39      | 2         | 0.49%   |
| 31      | 2         | 0.49%   |
| 52      | 1         | 0.24%   |
| 48      | 1         | 0.24%   |
| 47      | 1         | 0.24%   |
| 38      | 1         | 0.24%   |
| 37      | 1         | 0.24%   |
| 33      | 1         | 0.24%   |
| 29      | 1         | 0.24%   |
| 26      | 1         | 0.24%   |
| 7       | 1         | 0.24%   |
| 5       | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 184       | 45.1%   |
| 401-500     | 54        | 13.24%  |
| 501-600     | 52        | 12.75%  |
| 201-300     | 43        | 10.54%  |
| 351-400     | 37        | 9.07%   |
| Unknown     | 14        | 3.43%   |
| 1501-2000   | 5         | 1.23%   |
| 801-900     | 4         | 0.98%   |
| 701-800     | 4         | 0.98%   |
| 601-700     | 4         | 0.98%   |
| 1001-1500   | 3         | 0.74%   |
| 101-200     | 2         | 0.49%   |
| 901-1000    | 2         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 264       | 69.11%  |
| 16/10   | 63        | 16.49%  |
| 5/4     | 27        | 7.07%   |
| Unknown | 12        | 3.14%   |
| 4/3     | 9         | 2.36%   |
| 21/9    | 4         | 1.05%   |
| 6/5     | 2         | 0.52%   |
| 3/2     | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 106       | 25.85%  |
| 81-90          | 68        | 16.59%  |
| 201-250        | 54        | 13.17%  |
| 151-200        | 33        | 8.05%   |
| 141-150        | 23        | 5.61%   |
| 301-350        | 20        | 4.88%   |
| 121-130        | 17        | 4.15%   |
| 71-80          | 14        | 3.41%   |
| 51-60          | 14        | 3.41%   |
| Unknown        | 14        | 3.41%   |
| More than 1000 | 7         | 1.71%   |
| 41-50          | 7         | 1.71%   |
| 251-300        | 7         | 1.71%   |
| 501-1000       | 7         | 1.71%   |
| 351-500        | 6         | 1.46%   |
| 131-140        | 5         | 1.22%   |
| 61-70          | 4         | 0.98%   |
| 1-40           | 2         | 0.49%   |
| 111-120        | 1         | 0.24%   |
| 91-100         | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 144       | 36%     |
| 101-120       | 142       | 35.5%   |
| 121-160       | 78        | 19.5%   |
| Unknown       | 14        | 3.5%    |
| 161-240       | 12        | 3%      |
| 1-50          | 6         | 1.5%    |
| More than 240 | 4         | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 348       | 85.71%  |
| 2     | 46        | 11.33%  |
| 0     | 8         | 1.97%   |
| 3     | 3         | 0.74%   |
| 4     | 1         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 224       | 36.78%  |
| Intel                             | 156       | 25.62%  |
| Qualcomm Atheros                  | 82        | 13.46%  |
| Broadcom                          | 43        | 7.06%   |
| Ralink Technology                 | 16        | 2.63%   |
| Nvidia                            | 16        | 2.63%   |
| Marvell Technology Group          | 16        | 2.63%   |
| Broadcom Limited                  | 11        | 1.81%   |
| Ralink                            | 8         | 1.31%   |
| TP-Link                           | 5         | 0.82%   |
| Samsung Electronics               | 4         | 0.66%   |
| ASIX Electronics                  | 4         | 0.66%   |
| NetGear                           | 2         | 0.33%   |
| Fibocom                           | 2         | 0.33%   |
| Dell                              | 2         | 0.33%   |
| Belkin Components                 | 2         | 0.33%   |
| Attansic Technology               | 2         | 0.33%   |
| ZyXEL Communications              | 1         | 0.16%   |
| Xiaomi                            | 1         | 0.16%   |
| VIA Technologies                  | 1         | 0.16%   |
| U-Blox                            | 1         | 0.16%   |
| Tenda                             | 1         | 0.16%   |
| Sitecom Europe                    | 1         | 0.16%   |
| Seeed                             | 1         | 0.16%   |
| MediaTek                          | 1         | 0.16%   |
| Logitec                           | 1         | 0.16%   |
| Huawei Technologies               | 1         | 0.16%   |
| Hewlett-Packard                   | 1         | 0.16%   |
| Ericsson Business Mobile Networks | 1         | 0.16%   |
| Aquantia                          | 1         | 0.16%   |
| ADMtek                            | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 131       | 18.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 45        | 6.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 16        | 2.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 2%      |
| Intel Wireless 7260                                                     | 13        | 1.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 1.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 1.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 1.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 1.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.29%   |
| Nvidia MCP61 Ethernet                                                   | 8         | 1.14%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 1%      |
| Ralink MT7601U Wireless Adapter                                         | 7         | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.86%   |
| Intel Wireless 7265                                                     | 6         | 0.86%   |
| Intel Wireless 3160                                                     | 6         | 0.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 0.72%   |
| Intel Wireless 8260                                                     | 5         | 0.72%   |
| Intel Wireless 3165                                                     | 5         | 0.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.72%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 5         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.57%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.57%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.57%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 4         | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                    | 4         | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 117       | 37.26%  |
| Qualcomm Atheros      | 70        | 22.29%  |
| Realtek Semiconductor | 58        | 18.47%  |
| Broadcom              | 25        | 7.96%   |
| Ralink Technology     | 16        | 5.1%    |
| Ralink                | 8         | 2.55%   |
| TP-Link               | 5         | 1.59%   |
| Broadcom Limited      | 4         | 1.27%   |
| NetGear               | 2         | 0.64%   |
| Fibocom               | 2         | 0.64%   |
| Belkin Components     | 2         | 0.64%   |
| ZyXEL Communications  | 1         | 0.32%   |
| Tenda                 | 1         | 0.32%   |
| Sitecom Europe        | 1         | 0.32%   |
| Logitec               | 1         | 0.32%   |
| Dell                  | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 16        | 5.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 4.44%   |
| Intel Wireless 7260                                                     | 13        | 4.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 3.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 3.17%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 2.86%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 2.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 2.22%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 1.9%    |
| Intel Wireless 7265                                                     | 6         | 1.9%    |
| Intel Wireless 3160                                                     | 6         | 1.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.59%   |
| Intel Wireless 8260                                                     | 5         | 1.59%   |
| Intel Wireless 3165                                                     | 5         | 1.59%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.27%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.27%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.27%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 4         | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 1.27%   |
| Realtek RTL8187 Wireless Adapter                                        | 3         | 0.95%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.95%   |
| Ralink RT5572 Wireless Adapter                                          | 3         | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.95%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 3         | 0.95%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.95%   |
| Intel Centrino Wireless-N 100                                           | 3         | 0.95%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.95%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.95%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 200       | 54.05%  |
| Intel                    | 67        | 18.11%  |
| Broadcom                 | 26        | 7.03%   |
| Qualcomm Atheros         | 22        | 5.95%   |
| Nvidia                   | 16        | 4.32%   |
| Marvell Technology Group | 16        | 4.32%   |
| Broadcom Limited         | 7         | 1.89%   |
| Samsung Electronics      | 4         | 1.08%   |
| ASIX Electronics         | 4         | 1.08%   |
| Attansic Technology      | 2         | 0.54%   |
| Xiaomi                   | 1         | 0.27%   |
| VIA Technologies         | 1         | 0.27%   |
| MediaTek                 | 1         | 0.27%   |
| Huawei Technologies      | 1         | 0.27%   |
| Aquantia                 | 1         | 0.27%   |
| ADMtek                   | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 131       | 34.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45        | 11.87%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 2.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9         | 2.37%   |
| Nvidia MCP61 Ethernet                                             | 8         | 2.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.32%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5         | 1.32%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 1.06%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.06%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1.06%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.06%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.79%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.79%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.79%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.79%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3         | 0.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.79%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 3         | 0.79%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.53%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.53%   |
| Nvidia MCP51 Ethernet Controller                                  | 2         | 0.53%   |
| Nvidia CK804 Ethernet Controller                                  | 2         | 0.53%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.53%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 2         | 0.53%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2         | 0.53%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 358       | 53.92%  |
| WiFi     | 301       | 45.33%  |
| Modem    | 5         | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 235       | 56.63%  |
| Ethernet | 180       | 43.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 222       | 55.22%  |
| 1     | 154       | 38.31%  |
| 0     | 16        | 3.98%   |
| 3     | 7         | 1.74%   |
| 4     | 3         | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 345       | 84.56%  |
| Yes  | 63        | 15.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 82        | 43.39%  |
| Qualcomm Atheros Communications | 19        | 10.05%  |
| Cambridge Silicon Radio         | 16        | 8.47%   |
| Broadcom                        | 16        | 8.47%   |
| Realtek Semiconductor           | 14        | 7.41%   |
| Lite-On Technology              | 10        | 5.29%   |
| IMC Networks                    | 6         | 3.17%   |
| Apple                           | 5         | 2.65%   |
| Hewlett-Packard                 | 4         | 2.12%   |
| Dell                            | 4         | 2.12%   |
| ASUSTek Computer                | 4         | 2.12%   |
| Ralink Technology               | 2         | 1.06%   |
| Alps Electric                   | 2         | 1.06%   |
| Toshiba                         | 1         | 0.53%   |
| Ralink                          | 1         | 0.53%   |
| Logitech                        | 1         | 0.53%   |
| Foxconn / Hon Hai               | 1         | 0.53%   |
| Chicony Electronics             | 1         | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 40        | 21.16%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 16        | 8.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 15        | 7.94%   |
| Realtek Bluetooth Radio                                                             | 12        | 6.35%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 5.82%   |
| Intel AX200 Bluetooth                                                               | 7         | 3.7%    |
| Intel AX201 Bluetooth                                                               | 5         | 2.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 2.12%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 2.12%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 2.12%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.59%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.59%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.59%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.59%   |
| Apple Bluetooth Host Controller                                                     | 3         | 1.59%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 1.06%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 1.06%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.06%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.06%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.06%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.06%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.06%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.06%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.06%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.53%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.53%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 0.53%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.53%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.53%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.53%   |
| IMC Networks Bluetooth module                                                       | 1         | 0.53%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.53%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.53%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.53%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.53%   |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 275       | 57.89%  |
| AMD                               | 102       | 21.47%  |
| Nvidia                            | 72        | 15.16%  |
| C-Media Electronics               | 6         | 1.26%   |
| Creative Labs                     | 4         | 0.84%   |
| GN Netcom                         | 3         | 0.63%   |
| XMOS                              | 2         | 0.42%   |
| Logitech                          | 2         | 0.42%   |
| VIA Technologies                  | 1         | 0.21%   |
| Unknown                           | 1         | 0.21%   |
| Texas Instruments                 | 1         | 0.21%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.21%   |
| Focusrite-Novation                | 1         | 0.21%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.21%   |
| Creative Technology               | 1         | 0.21%   |
| ASUSTek Computer                  | 1         | 0.21%   |
| Asahi Kasei Microsystems          | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 4.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 4.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 25        | 4.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 24        | 4.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 22        | 3.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 21        | 3.72%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 3.54%   |
| AMD FCH Azalia Controller                                                                         | 19        | 3.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 2.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 2.83%   |
| Nvidia High Definition Audio Controller                                                           | 13        | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.3%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 2.3%    |
| Intel 8 Series HD Audio Controller                                                                | 13        | 2.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 2.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 1.77%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.59%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.59%   |
| AMD High Definition Audio Controller                                                              | 9         | 1.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 1.59%   |
| Nvidia MCP61 High Definition Audio                                                                | 8         | 1.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.42%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 1.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.06%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.06%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 1.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 5         | 0.88%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.88%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 5         | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.71%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 71        | 23.2%   |
| SK hynix            | 57        | 18.63%  |
| Unknown             | 47        | 15.36%  |
| Micron Technology   | 24        | 7.84%   |
| Kingston            | 19        | 6.21%   |
| Crucial             | 12        | 3.92%   |
| Nanya Technology    | 11        | 3.59%   |
| G.Skill             | 9         | 2.94%   |
| Corsair             | 9         | 2.94%   |
| A-DATA Technology   | 8         | 2.61%   |
| Unknown (ABCD)      | 5         | 1.63%   |
| Elpida              | 5         | 1.63%   |
| Smart               | 4         | 1.31%   |
| Patriot             | 4         | 1.31%   |
| Team                | 3         | 0.98%   |
| Timetec             | 2         | 0.65%   |
| Qimonda             | 2         | 0.65%   |
| Unifosa             | 1         | 0.33%   |
| Transcend           | 1         | 0.33%   |
| Teikon              | 1         | 0.33%   |
| Sesame              | 1         | 0.33%   |
| Ramaxel Technology  | 1         | 0.33%   |
| PNY                 | 1         | 0.33%   |
| Multilaser          | 1         | 0.33%   |
| Goldkey             | 1         | 0.33%   |
| e2e4                | 1         | 0.33%   |
| Digiboard           | 1         | 0.33%   |
| Avant               | 1         | 0.33%   |
| ASint Technology    | 1         | 0.33%   |
| Apacer              | 1         | 0.33%   |
| 48spaces            | 1         | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 5         | 1.52%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 1.52%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 5         | 1.52%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 4         | 1.22%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 3         | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 3         | 0.91%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 3         | 0.91%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.91%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.91%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 3         | 0.91%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                   | 2         | 0.61%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 2         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 2         | 0.61%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 2         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 2         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s  | 2         | 0.61%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 2         | 0.61%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.61%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.61%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 2         | 0.61%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.61%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.61%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.61%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.61%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s              | 2         | 0.61%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.61%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s               | 2         | 0.61%   |
| Micron RAM Module 8192MB SODIMM DDR4 2667MT/s                    | 2         | 0.61%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.61%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.61%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s          | 2         | 0.61%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 0.3%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1333MT/s                   | 1         | 0.3%    |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 120       | 44.94%  |
| DDR4    | 71        | 26.59%  |
| DDR2    | 34        | 12.73%  |
| SDRAM   | 16        | 5.99%   |
| Unknown | 9         | 3.37%   |
| LPDDR4  | 8         | 3%      |
| LPDDR3  | 6         | 2.25%   |
| DDR     | 3         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 167       | 63.98%  |
| DIMM         | 85        | 32.57%  |
| Row Of Chips | 7         | 2.68%   |
| Chip         | 1         | 0.38%   |
| Unknown      | 1         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 97        | 32.99%  |
| 2048  | 76        | 25.85%  |
| 8192  | 73        | 24.83%  |
| 1024  | 24        | 8.16%   |
| 16384 | 17        | 5.78%   |
| 32768 | 3         | 1.02%   |
| 512   | 3         | 1.02%   |
| 65536 | 1         | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 69        | 23.55%  |
| 1333    | 26        | 8.87%   |
| 2400    | 25        | 8.53%   |
| 2667    | 23        | 7.85%   |
| 1334    | 22        | 7.51%   |
| 3200    | 18        | 6.14%   |
| 667     | 17        | 5.8%    |
| 800     | 15        | 5.12%   |
| 2133    | 13        | 4.44%   |
| 2048    | 9         | 3.07%   |
| 1867    | 8         | 2.73%   |
| 1066    | 7         | 2.39%   |
| Unknown | 7         | 2.39%   |
| 1866    | 5         | 1.71%   |
| 400     | 5         | 1.71%   |
| 3266    | 3         | 1.02%   |
| 533     | 3         | 1.02%   |
| 3600    | 2         | 0.68%   |
| 3000    | 2         | 0.68%   |
| 1639    | 2         | 0.68%   |
| 1067    | 2         | 0.68%   |
| 49926   | 1         | 0.34%   |
| 8400    | 1         | 0.34%   |
| 4267    | 1         | 0.34%   |
| 3466    | 1         | 0.34%   |
| 3066    | 1         | 0.34%   |
| 2733    | 1         | 0.34%   |
| 1200    | 1         | 0.34%   |
| 333     | 1         | 0.34%   |
| 2       | 1         | 0.34%   |
| 1       | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 50%     |
| Brother Industries  | 2         | 33.33%  |
| Samsung Electronics | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4200 series | 1         | 16.67%  |
| HP DeskJet 3630 series  | 1         | 16.67%  |
| HP Deskjet 3520 series  | 1         | 16.67%  |
| HP Deskjet 1050 J410    | 1         | 16.67%  |
| Brother PTUSB Printing  | 1         | 16.67%  |
| Brother DCP-7055W       | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 50%     |
| HP scanjet 8270                                               | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 58        | 25.22%  |
| Realtek Semiconductor                  | 20        | 8.7%    |
| Acer                                   | 20        | 8.7%    |
| IMC Networks                           | 16        | 6.96%   |
| Microdia                               | 14        | 6.09%   |
| Sunplus Innovation Technology          | 10        | 4.35%   |
| Suyin                                  | 9         | 3.91%   |
| Alcor Micro                            | 9         | 3.91%   |
| Quanta                                 | 8         | 3.48%   |
| Silicon Motion                         | 6         | 2.61%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.61%   |
| Lite-On Technology                     | 5         | 2.17%   |
| Apple                                  | 5         | 2.17%   |
| Ricoh                                  | 4         | 1.74%   |
| Luxvisions Innotech Limited            | 4         | 1.74%   |
| Logitech                               | 4         | 1.74%   |
| Z-Star Microelectronics                | 3         | 1.3%    |
| Syntek                                 | 3         | 1.3%    |
| Samsung Electronics                    | 3         | 1.3%    |
| Lenovo                                 | 3         | 1.3%    |
| Importek                               | 3         | 1.3%    |
| Generalplus Technology                 | 3         | 1.3%    |
| SJ-180517-N                            | 2         | 0.87%   |
| Y Media                                | 1         | 0.43%   |
| OmniVision Technologies                | 1         | 0.43%   |
| Nintendo                               | 1         | 0.43%   |
| Microsoft                              | 1         | 0.43%   |
| LG Electronics                         | 1         | 0.43%   |
| KYE Systems (Mouse Systems)            | 1         | 0.43%   |
| Guillemot                              | 1         | 0.43%   |
| Genesys Logic                          | 1         | 0.43%   |
| GEMBIRD                                | 1         | 0.43%   |
| DigiTech                               | 1         | 0.43%   |
| ARC International                      | 1         | 0.43%   |
| ALi                                    | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 8         | 3.45%   |
| Realtek Integrated_Webcam_HD             | 7         | 3.02%   |
| Chicony TOSHIBA Web Camera - HD          | 5         | 2.16%   |
| Acer Lenovo EasyCamera                   | 5         | 2.16%   |
| Chicony HP HD Camera                     | 4         | 1.72%   |
| Alcor Micro SHUNCCM2MP                   | 4         | 1.72%   |
| Acer HD WebCam                           | 4         | 1.72%   |
| Samsung Galaxy A5 (MTP)                  | 3         | 1.29%   |
| Realtek USB Camera                       | 3         | 1.29%   |
| Realtek Integrated Webcam                | 3         | 1.29%   |
| Luxvisions Innotech Limited HP HD Camera | 3         | 1.29%   |
| Lite-On HP HD Camera                     | 3         | 1.29%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 3         | 1.29%   |
| IMC Networks USB2.0 UVC HD Webcam        | 3         | 1.29%   |
| IMC Networks USB2.0 HD UVC WebCam        | 3         | 1.29%   |
| Chicony HD WebCam                        | 3         | 1.29%   |
| Chicony EasyCamera                       | 3         | 1.29%   |
| Apple FaceTime HD Camera                 | 3         | 1.29%   |
| Alcor Micro Asus Integrated Webcam       | 3         | 1.29%   |
| Acer VGA WebCam                          | 3         | 1.29%   |
| Sunplus Laptop Integrated Webcam HD      | 2         | 0.86%   |
| Sunplus Integrated_Webcam_HD             | 2         | 0.86%   |
| Sunplus HD WebCam                        | 2         | 0.86%   |
| SJ-180517-N 1080P Webcam                 | 2         | 0.86%   |
| Realtek Lenovo EasyCamera                | 2         | 0.86%   |
| Quanta VGA WebCam                        | 2         | 0.86%   |
| Quanta HP Webcam                         | 2         | 0.86%   |
| Quanta HP HD Camera                      | 2         | 0.86%   |
| Microdia Sonix USB 2.0 Camera            | 2         | 0.86%   |
| Microdia Laptop_Integrated_Webcam_2M     | 2         | 0.86%   |
| Microdia Integrated Webcam               | 2         | 0.86%   |
| Logitech Webcam C270                     | 2         | 0.86%   |
| Importek TOSHIBA Web Camera - HD         | 2         | 0.86%   |
| IMC Networks USB 2.0 UVC VGA WebCam      | 2         | 0.86%   |
| IMC Networks Integrated Camera           | 2         | 0.86%   |
| Generalplus GENERAL WEBCAM               | 2         | 0.86%   |
| Chicony USB 2.0 Camera                   | 2         | 0.86%   |
| Chicony Lenovo EasyCamera                | 2         | 0.86%   |
| Chicony HP Webcam                        | 2         | 0.86%   |
| Chicony HD WebCam (Acer)                 | 2         | 0.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 41.38%  |
| AuthenTec                  | 7         | 24.14%  |
| Synaptics                  | 3         | 10.34%  |
| Shenzhen Goodix Technology | 3         | 10.34%  |
| Upek                       | 2         | 6.9%    |
| STMicroelectronics         | 1         | 3.45%   |
| LighTuning Technology      | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 6.9%    |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 6.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 2         | 6.9%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 6.9%    |
| AuthenTec AES2810                                          | 2         | 6.9%    |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 6.9%    |
| AuthenTec AES1600                                          | 2         | 6.9%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 1         | 3.45%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 3.45%   |
| Validity Sensors VFS491                                    | 1         | 3.45%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 3.45%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 3.45%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 3.45%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 3.45%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 3.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 3.45%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 3.45%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 3.45%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 3.45%   |
| Shenzhen Goodix FingerPrint                                | 1         | 3.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 3.45%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 3         | 33.33%  |
| Alcor Micro | 3         | 33.33%  |
| Broadcom    | 2         | 22.22%  |
| Upek        | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 33.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 321       | 79.26%  |
| 1     | 69        | 17.04%  |
| 2     | 15        | 3.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 29        | 30.85%  |
| Graphics card            | 16        | 17.02%  |
| Net/wireless             | 14        | 14.89%  |
| Chipcard                 | 9         | 9.57%   |
| Communication controller | 5         | 5.32%   |
| Unassigned class         | 3         | 3.19%   |
| Sound                    | 3         | 3.19%   |
| Multimedia controller    | 3         | 3.19%   |
| Camera                   | 3         | 3.19%   |
| Storage                  | 2         | 2.13%   |
| Net/ethernet             | 2         | 2.13%   |
| Dvb card                 | 2         | 2.13%   |
| Bluetooth                | 2         | 2.13%   |
| Flash memory             | 1         | 1.06%   |

