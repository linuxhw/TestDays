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

Total: 579

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 05KX61 A00                  | Server      | [9f365307f3](https://linux-hardware.org/?probe=9f365307f3) | Dec 30, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| HP            | Compaq 6715b (RM174UT#AB... | Notebook    | [db3b8615f7](https://linux-hardware.org/?probe=db3b8615f7) | Dec 21, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | Notebook    | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| HP            | Compaq 6830s                | Notebook    | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [63487a2957](https://linux-hardware.org/?probe=63487a2957) | Nov 28, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [0b632b7ae8](https://linux-hardware.org/?probe=0b632b7ae8) | Nov 27, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [b37755877d](https://linux-hardware.org/?probe=b37755877d) | Nov 24, 2022 |
| HP            | 3048h                       | Desktop     | [33ced86304](https://linux-hardware.org/?probe=33ced86304) | Nov 19, 2022 |
| HP            | 3048h                       | Desktop     | [e5fdb1f67a](https://linux-hardware.org/?probe=e5fdb1f67a) | Nov 19, 2022 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [db28f53298](https://linux-hardware.org/?probe=db28f53298) | Nov 12, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [8a149b06a1](https://linux-hardware.org/?probe=8a149b06a1) | Nov 12, 2022 |
| Acer          | AOD255E                     | Notebook    | [817724283b](https://linux-hardware.org/?probe=817724283b) | Nov 11, 2022 |
| Toshiba       | Satellite L15-B             | Notebook    | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [3408fb4c36](https://linux-hardware.org/?probe=3408fb4c36) | Nov 07, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [f731a55cc1](https://linux-hardware.org/?probe=f731a55cc1) | Nov 05, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [eb15ca5b98](https://linux-hardware.org/?probe=eb15ca5b98) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [20824af437](https://linux-hardware.org/?probe=20824af437) | Nov 03, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a5712d3982](https://linux-hardware.org/?probe=a5712d3982) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [9b53e5c27d](https://linux-hardware.org/?probe=9b53e5c27d) | Oct 31, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [95238cc6e8](https://linux-hardware.org/?probe=95238cc6e8) | Oct 30, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [f416278476](https://linux-hardware.org/?probe=f416278476) | Oct 29, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [2501d67199](https://linux-hardware.org/?probe=2501d67199) | Oct 28, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| HP            | 431 Notebook                | Notebook    | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| AOpen         | D1007 0BBA                  | Desktop     | [b3597a7cbc](https://linux-hardware.org/?probe=b3597a7cbc) | Oct 10, 2022 |
| Acer          | Aspire 4739Z                | Notebook    | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
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
| 5.4.0-42-generic  | 32        | 7%      |
| 5.4.0-52-generic  | 22        | 4.81%   |
| 5.4.0-48-generic  | 13        | 2.84%   |
| 5.4.0-47-generic  | 12        | 2.63%   |
| 5.4.0-26-generic  | 12        | 2.63%   |
| 5.11.0-27-generic | 12        | 2.63%   |
| 5.4.0-54-generic  | 11        | 2.41%   |
| 5.4.0-40-generic  | 11        | 2.41%   |
| 5.13.0-28-generic | 11        | 2.41%   |
| 5.4.0-29-generic  | 10        | 2.19%   |
| 5.4.0-33-generic  | 9         | 1.97%   |
| 5.8.0-50-generic  | 8         | 1.75%   |
| 5.4.0-65-generic  | 8         | 1.75%   |
| 5.13.0-30-generic | 8         | 1.75%   |
| 5.11.0-38-generic | 8         | 1.75%   |
| 5.4.0-73-generic  | 7         | 1.53%   |
| 5.4.0-37-generic  | 7         | 1.53%   |
| 5.13.0-40-generic | 7         | 1.53%   |
| 5.8.0-53-generic  | 6         | 1.31%   |
| 5.8.0-41-generic  | 6         | 1.31%   |
| 5.4.0-72-generic  | 6         | 1.31%   |
| 5.4.0-67-generic  | 6         | 1.31%   |
| 5.11.0-43-generic | 6         | 1.31%   |
| 5.8.0-55-generic  | 5         | 1.09%   |
| 5.8.0-45-generic  | 5         | 1.09%   |
| 5.4.0-91-generic  | 5         | 1.09%   |
| 5.4.0-89-generic  | 5         | 1.09%   |
| 5.4.0-60-generic  | 5         | 1.09%   |
| 5.4.0-59-generic  | 5         | 1.09%   |
| 5.4.0-58-generic  | 5         | 1.09%   |
| 5.4.0-51-generic  | 5         | 1.09%   |
| 5.4.0-131-generic | 5         | 1.09%   |
| 5.4.0-122-generic | 5         | 1.09%   |
| 5.15.0-46-generic | 5         | 1.09%   |
| 5.15.0-41-generic | 5         | 1.09%   |
| 5.11.0-37-generic | 5         | 1.09%   |
| 5.8.0-63-generic  | 4         | 0.88%   |
| 5.8.0-59-generic  | 4         | 0.88%   |
| 5.4.0-77-generic  | 4         | 0.88%   |
| 5.4.0-66-generic  | 4         | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 258       | 60.14%  |
| 5.8.0   | 51        | 11.89%  |
| 5.11.0  | 48        | 11.19%  |
| 5.13.0  | 40        | 9.32%   |
| 5.15.0  | 21        | 4.9%    |
| 5.6.0   | 2         | 0.47%   |
| 5.9.0   | 1         | 0.23%   |
| 5.7.9   | 1         | 0.23%   |
| 5.6.15  | 1         | 0.23%   |
| 5.5.2   | 1         | 0.23%   |
| 5.4.30  | 1         | 0.23%   |
| 5.3.18  | 1         | 0.23%   |
| 5.16.5  | 1         | 0.23%   |
| 5.14.0  | 1         | 0.23%   |
| 5.10.0  | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 259       | 60.37%  |
| 5.8     | 51        | 11.89%  |
| 5.11    | 48        | 11.19%  |
| 5.13    | 40        | 9.32%   |
| 5.15    | 21        | 4.9%    |
| 5.6     | 3         | 0.7%    |
| 5.9     | 1         | 0.23%   |
| 5.7     | 1         | 0.23%   |
| 5.5     | 1         | 0.23%   |
| 5.3     | 1         | 0.23%   |
| 5.16    | 1         | 0.23%   |
| 5.14    | 1         | 0.23%   |
| 5.10    | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 423       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 401       | 94.35%  |
| LXDE       | 9         | 2.12%   |
| GNOME      | 6         | 1.41%   |
| i3         | 2         | 0.47%   |
| Cinnamon   | 2         | 0.47%   |
| XFCE       | 1         | 0.24%   |
| X-Cinnamon | 1         | 0.24%   |
| MATE       | 1         | 0.24%   |
| KDE5       | 1         | 0.24%   |
| KDE        | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 400       | 94.34%  |
| Tty     | 19        | 4.48%   |
| Wayland | 4         | 0.94%   |
| Unknown | 1         | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 230       | 53.36%  |
| Unknown | 128       | 29.7%   |
| GDM     | 27        | 6.26%   |
| LightDM | 25        | 5.8%    |
| TDM     | 17        | 3.94%   |
| GDM3    | 3         | 0.7%    |
| LXDM    | 1         | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 133       | 31.44%  |
| fr_FR   | 53        | 12.53%  |
| pt_BR   | 34        | 8.04%   |
| de_DE   | 27        | 6.38%   |
| it_IT   | 25        | 5.91%   |
| en_GB   | 23        | 5.44%   |
| C       | 19        | 4.49%   |
| ru_RU   | 13        | 3.07%   |
| es_ES   | 10        | 2.36%   |
| en_AU   | 9         | 2.13%   |
| pl_PL   | 6         | 1.42%   |
| ja_JP   | 5         | 1.18%   |
| hu_HU   | 4         | 0.95%   |
| es_MX   | 4         | 0.95%   |
| en_CA   | 4         | 0.95%   |
| nl_NL   | 3         | 0.71%   |
| fr_CH   | 3         | 0.71%   |
| fi_FI   | 3         | 0.71%   |
| es_AR   | 3         | 0.71%   |
| en_ZA   | 3         | 0.71%   |
| en_IN   | 3         | 0.71%   |
| en_IE   | 3         | 0.71%   |
| cs_CZ   | 3         | 0.71%   |
| fr_BE   | 2         | 0.47%   |
| es_CR   | 2         | 0.47%   |
| es_CL   | 2         | 0.47%   |
| en_SG   | 2         | 0.47%   |
| en_PH   | 2         | 0.47%   |
| en_NZ   | 2         | 0.47%   |
| el_GR   | 2         | 0.47%   |
| de_CH   | 2         | 0.47%   |
| Unknown | 2         | 0.47%   |
| tr_TR   | 1         | 0.24%   |
| sv_SE   | 1         | 0.24%   |
| ru_UA   | 1         | 0.24%   |
| pt_PT   | 1         | 0.24%   |
| nl_BE   | 1         | 0.24%   |
| lt_LT   | 1         | 0.24%   |
| fr_CA   | 1         | 0.24%   |
| es_UY   | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 246       | 58.16%  |
| EFI  | 177       | 41.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 389       | 91.96%  |
| Overlay | 20        | 4.73%   |
| Btrfs   | 7         | 1.65%   |
| Xfs     | 3         | 0.71%   |
| Zfs     | 1         | 0.24%   |
| F2fs    | 1         | 0.24%   |
| Ext2    | 1         | 0.24%   |
| Aufs    | 1         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 163       | 38.17%  |
| GPT     | 144       | 33.72%  |
| MBR     | 120       | 28.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 374       | 88%     |
| Yes       | 51        | 12%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 309       | 72.54%  |
| Yes       | 117       | 27.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 78        | 18.44%  |
| Lenovo                      | 54        | 12.77%  |
| Dell                        | 53        | 12.53%  |
| ASUSTek Computer            | 49        | 11.58%  |
| Acer                        | 23        | 5.44%   |
| MSI                         | 21        | 4.96%   |
| Gigabyte Technology         | 15        | 3.55%   |
| ASRock                      | 15        | 3.55%   |
| Toshiba                     | 14        | 3.31%   |
| Samsung Electronics         | 10        | 2.36%   |
| Intel                       | 10        | 2.36%   |
| Positivo                    | 7         | 1.65%   |
| Apple                       | 6         | 1.42%   |
| Notebook                    | 5         | 1.18%   |
| Fujitsu                     | 5         | 1.18%   |
| Sony                        | 4         | 0.95%   |
| Pegatron                    | 4         | 0.95%   |
| Packard Bell                | 4         | 0.95%   |
| Google                      | 4         | 0.95%   |
| AMI                         | 3         | 0.71%   |
| AAEON                       | 3         | 0.71%   |
| ZOTAC                       | 2         | 0.47%   |
| YASHI                       | 2         | 0.47%   |
| Fujitsu Siemens             | 2         | 0.47%   |
| Foxconn                     | 2         | 0.47%   |
| Biostar                     | 2         | 0.47%   |
| Unknown                     | 2         | 0.47%   |
| UNOWHY                      | 1         | 0.24%   |
| Timi                        | 1         | 0.24%   |
| Teclast                     | 1         | 0.24%   |
| Supermicro                  | 1         | 0.24%   |
| Star Labs                   | 1         | 0.24%   |
| Prestigio                   | 1         | 0.24%   |
| Panasonic                   | 1         | 0.24%   |
| Mediacom                    | 1         | 0.24%   |
| Lanix                       | 1         | 0.24%   |
| LAMINA                      | 1         | 0.24%   |
| Itautec                     | 1         | 0.24%   |
| IBM                         | 1         | 0.24%   |
| I-Life Digital Technologies | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| HP Notebook                   | 5         | 1.18%   |
| Unknown                       | 5         | 1.18%   |
| HP Pavilion dv6               | 3         | 0.71%   |
| Dell Latitude D630            | 3         | 0.71%   |
| AAEON MF-001                  | 3         | 0.71%   |
| YASHI MYBOOK 360              | 2         | 0.47%   |
| Positivo H14BT58              | 2         | 0.47%   |
| MSI MS-7C37                   | 2         | 0.47%   |
| MSI MS-7B89                   | 2         | 0.47%   |
| Lenovo IdeaPad 320-15AST 80XV | 2         | 0.47%   |
| HP ProBook 450 G6             | 2         | 0.47%   |
| HP ProBook 440 G8 Notebook PC | 2         | 0.47%   |
| HP ProBook 440 G7             | 2         | 0.47%   |
| HP Pavilion x2 Detachable     | 2         | 0.47%   |
| HP Pavilion g7                | 2         | 0.47%   |
| HP Compaq 6000 Pro SFF PC     | 2         | 0.47%   |
| Dell OptiPlex 790             | 2         | 0.47%   |
| Dell Inspiron N5010           | 2         | 0.47%   |
| Dell Inspiron 15-3567         | 2         | 0.47%   |
| ASUS M5A97 R2.0               | 2         | 0.47%   |
| ASUS 1015BX                   | 2         | 0.47%   |
| ASRock N68-VS3 UCC            | 2         | 0.47%   |
| ASRock FM2A85X Extreme6       | 2         | 0.47%   |
| Apple MacBookPro8,1           | 2         | 0.47%   |
| ZOTAC ZBOX-CI323NANO          | 1         | 0.24%   |
| ZOTAC NM10                    | 1         | 0.24%   |
| UNOWHY Y13G010S4EI            | 1         | 0.24%   |
| Toshiba Satellite S55-B       | 1         | 0.24%   |
| Toshiba Satellite Pro U400    | 1         | 0.24%   |
| Toshiba Satellite L840        | 1         | 0.24%   |
| Toshiba Satellite L70-B       | 1         | 0.24%   |
| Toshiba Satellite L305        | 1         | 0.24%   |
| Toshiba Satellite L15-B       | 1         | 0.24%   |
| Toshiba Satellite C875        | 1         | 0.24%   |
| Toshiba Satellite C855D       | 1         | 0.24%   |
| Toshiba Satellite C70D-B      | 1         | 0.24%   |
| Toshiba Satellite C670D-12N   | 1         | 0.24%   |
| Toshiba Satellite C55D-A      | 1         | 0.24%   |
| Toshiba Satellite A660        | 1         | 0.24%   |
| Toshiba Satellite A205        | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 20        | 4.73%   |
| Acer Aspire           | 18        | 4.26%   |
| Lenovo ThinkPad       | 17        | 4.02%   |
| Lenovo IdeaPad        | 16        | 3.78%   |
| HP Compaq             | 16        | 3.78%   |
| Toshiba Satellite     | 13        | 3.07%   |
| HP ProBook            | 13        | 3.07%   |
| HP Pavilion           | 13        | 3.07%   |
| Dell Latitude         | 8         | 1.89%   |
| Lenovo ThinkCentre    | 6         | 1.42%   |
| Dell OptiPlex         | 6         | 1.42%   |
| HP Notebook           | 5         | 1.18%   |
| HP EliteBook          | 5         | 1.18%   |
| ASUS VivoBook         | 5         | 1.18%   |
| Unknown               | 5         | 1.18%   |
| Dell XPS              | 4         | 0.95%   |
| Dell Vostro           | 4         | 0.95%   |
| Dell PowerEdge        | 4         | 0.95%   |
| HP Presario           | 3         | 0.71%   |
| HP Laptop             | 3         | 0.71%   |
| AAEON MF-001          | 3         | 0.71%   |
| YASHI MYBOOK          | 2         | 0.47%   |
| Positivo H14BT58      | 2         | 0.47%   |
| Packard Bell EasyNote | 2         | 0.47%   |
| Notebook W54          | 2         | 0.47%   |
| MSI MS-7C37           | 2         | 0.47%   |
| MSI MS-7B89           | 2         | 0.47%   |
| HP t620               | 2         | 0.47%   |
| HP Spectre            | 2         | 0.47%   |
| Gigabyte B450M        | 2         | 0.47%   |
| Fujitsu LIFEBOOK      | 2         | 0.47%   |
| Dell Studio           | 2         | 0.47%   |
| ASUS M5A97            | 2         | 0.47%   |
| ASUS 1015BX           | 2         | 0.47%   |
| ASRock N68-VS3        | 2         | 0.47%   |
| ASRock FM2A85X        | 2         | 0.47%   |
| Apple MacBookPro8     | 2         | 0.47%   |
| ZOTAC ZBOX-CI323NANO  | 1         | 0.24%   |
| ZOTAC NM10            | 1         | 0.24%   |
| UNOWHY Y13G010S4EI    | 1         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 37        | 8.75%   |
| 2011 | 34        | 8.04%   |
| 2019 | 33        | 7.8%    |
| 2010 | 33        | 7.8%    |
| 2013 | 30        | 7.09%   |
| 2014 | 29        | 6.86%   |
| 2008 | 28        | 6.62%   |
| 2007 | 27        | 6.38%   |
| 2017 | 26        | 6.15%   |
| 2009 | 26        | 6.15%   |
| 2020 | 23        | 5.44%   |
| 2016 | 23        | 5.44%   |
| 2015 | 23        | 5.44%   |
| 2018 | 19        | 4.49%   |
| 2021 | 14        | 3.31%   |
| 2006 | 13        | 3.07%   |
| 2005 | 4         | 0.95%   |
| 2004 | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 256       | 60.52%  |
| Desktop     | 146       | 34.52%  |
| Mini pc     | 6         | 1.42%   |
| Server      | 6         | 1.42%   |
| Convertible | 5         | 1.18%   |
| Tablet      | 2         | 0.47%   |
| All in one  | 2         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 395       | 93.16%  |
| Enabled  | 29        | 6.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 418       | 98.82%  |
| Yes  | 5         | 1.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 128       | 30.05%  |
| 4.01-8.0        | 88        | 20.66%  |
| 1.01-2.0        | 69        | 16.2%   |
| 8.01-16.0       | 55        | 12.91%  |
| 16.01-24.0      | 43        | 10.09%  |
| 32.01-64.0      | 15        | 3.52%   |
| 2.01-3.0        | 13        | 3.05%   |
| 24.01-32.0      | 5         | 1.17%   |
| 64.01-256.0     | 4         | 0.94%   |
| 0.51-1.0        | 4         | 0.94%   |
| More than 256.0 | 2         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 215       | 48.21%  |
| 0.51-1.0   | 76        | 17.04%  |
| 2.01-3.0   | 66        | 14.8%   |
| 4.01-8.0   | 45        | 10.09%  |
| 3.01-4.0   | 28        | 6.28%   |
| 0.01-0.5   | 9         | 2.02%   |
| 8.01-16.0  | 5         | 1.12%   |
| 32.01-64.0 | 1         | 0.22%   |
| 16.01-24.0 | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 281       | 65.81%  |
| 2      | 104       | 24.36%  |
| 4      | 14        | 3.28%   |
| 3      | 12        | 2.81%   |
| 5      | 7         | 1.64%   |
| 6      | 3         | 0.7%    |
| 7      | 2         | 0.47%   |
| 0      | 2         | 0.47%   |
| 17     | 1         | 0.23%   |
| 14     | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 221       | 51.76%  |
| No        | 206       | 48.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 378       | 89.15%  |
| No        | 46        | 10.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 316       | 74.7%   |
| No        | 107       | 25.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 233       | 54.44%  |
| Yes       | 195       | 45.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 68        | 15.96%  |
| France       | 56        | 13.15%  |
| Brazil       | 40        | 9.39%   |
| Italy        | 34        | 7.98%   |
| Germany      | 34        | 7.98%   |
| Russia       | 18        | 4.23%   |
| UK           | 15        | 3.52%   |
| Spain        | 12        | 2.82%   |
| Switzerland  | 10        | 2.35%   |
| Australia    | 10        | 2.35%   |
| Poland       | 8         | 1.88%   |
| Netherlands  | 8         | 1.88%   |
| Hungary      | 7         | 1.64%   |
| Finland      | 7         | 1.64%   |
| Mexico       | 6         | 1.41%   |
| Japan        | 5         | 1.17%   |
| Ireland      | 5         | 1.17%   |
| Czechia      | 5         | 1.17%   |
| Canada       | 5         | 1.17%   |
| Belgium      | 5         | 1.17%   |
| Ukraine      | 4         | 0.94%   |
| South Africa | 4         | 0.94%   |
| Indonesia    | 4         | 0.94%   |
| Romania      | 3         | 0.7%    |
| Norway       | 3         | 0.7%    |
| New Zealand  | 3         | 0.7%    |
| India        | 3         | 0.7%    |
| Greece       | 3         | 0.7%    |
| Argentina    | 3         | 0.7%    |
| Vietnam      | 2         | 0.47%   |
| Slovenia     | 2         | 0.47%   |
| Slovakia     | 2         | 0.47%   |
| Singapore    | 2         | 0.47%   |
| Puerto Rico  | 2         | 0.47%   |
| Philippines  | 2         | 0.47%   |
| Costa Rica   | 2         | 0.47%   |
| Colombia     | 2         | 0.47%   |
| Chile        | 2         | 0.47%   |
| Uruguay      | 1         | 0.23%   |
| Turkey       | 1         | 0.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Rome              | 6         | 1.37%   |
| Paris             | 6         | 1.37%   |
| Milan             | 5         | 1.14%   |
| Melbourne         | 5         | 1.14%   |
| Helsinki          | 4         | 0.92%   |
| Wellington        | 3         | 0.69%   |
| Salvador          | 3         | 0.69%   |
| Pécs             | 3         | 0.69%   |
| Munich            | 3         | 0.69%   |
| Moscow            | 3         | 0.69%   |
| Mexico City       | 3         | 0.69%   |
| Florence          | 3         | 0.69%   |
| Derry             | 3         | 0.69%   |
| Brasília         | 3         | 0.69%   |
| Athens            | 3         | 0.69%   |
| Zurich            | 2         | 0.46%   |
| Yekaterinburg     | 2         | 0.46%   |
| Vicosa            | 2         | 0.46%   |
| Stuttgart         | 2         | 0.46%   |
| Southampton       | 2         | 0.46%   |
| Sao Paulo         | 2         | 0.46%   |
| Raahe             | 2         | 0.46%   |
| Poznan            | 2         | 0.46%   |
| Porto Alegre      | 2         | 0.46%   |
| Oradea            | 2         | 0.46%   |
| Omsk              | 2         | 0.46%   |
| Mount Vernon      | 2         | 0.46%   |
| Krakow            | 2         | 0.46%   |
| Jurong West       | 2         | 0.46%   |
| Houston           | 2         | 0.46%   |
| Heredia           | 2         | 0.46%   |
| Hamburg           | 2         | 0.46%   |
| Frankfurt am Main | 2         | 0.46%   |
| Fortaleza         | 2         | 0.46%   |
| Figeac            | 2         | 0.46%   |
| Dublin            | 2         | 0.46%   |
| Curitiba          | 2         | 0.46%   |
| Cuernavaca        | 2         | 0.46%   |
| Cossington        | 2         | 0.46%   |
| Cayey             | 2         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 106       | 135    | 18.96%  |
| WDC                 | 100       | 142    | 17.89%  |
| Samsung Electronics | 62        | 87     | 11.09%  |
| Toshiba             | 37        | 39     | 6.62%   |
| Unknown             | 35        | 41     | 6.26%   |
| Hitachi             | 34        | 41     | 6.08%   |
| Kingston            | 25        | 26     | 4.47%   |
| Crucial             | 21        | 34     | 3.76%   |
| SanDisk             | 15        | 19     | 2.68%   |
| Intel               | 11        | 12     | 1.97%   |
| Fujitsu             | 9         | 9      | 1.61%   |
| China               | 9         | 9      | 1.61%   |
| A-DATA Technology   | 8         | 9      | 1.43%   |
| SK hynix            | 7         | 7      | 1.25%   |
| HGST                | 7         | 9      | 1.25%   |
| PNY                 | 4         | 4      | 0.72%   |
| Maxtor              | 4         | 4      | 0.72%   |
| Apacer              | 4         | 4      | 0.72%   |
| Team                | 3         | 3      | 0.54%   |
| Micron Technology   | 3         | 3      | 0.54%   |
| LITEONIT            | 3         | 3      | 0.54%   |
| LDLC                | 3         | 3      | 0.54%   |
| KIOXIA              | 3         | 3      | 0.54%   |
| JMicron Technology  | 3         | 3      | 0.54%   |
| Corsair             | 3         | 3      | 0.54%   |
| Unknown             | 3         | 4      | 0.54%   |
| USB                 | 2         | 2      | 0.36%   |
| Transcend           | 2         | 2      | 0.36%   |
| OCZ                 | 2         | 2      | 0.36%   |
| Intenso             | 2         | 2      | 0.36%   |
| Hewlett-Packard     | 2         | 7      | 0.36%   |
| Apple               | 2         | 4      | 0.36%   |
| Vaseky              | 1         | 1      | 0.18%   |
| TO Exter            | 1         | 1      | 0.18%   |
| TCSUNBOW            | 1         | 1      | 0.18%   |
| Star                | 1         | 1      | 0.18%   |
| SPCC                | 1         | 1      | 0.18%   |
| QGEEM               | 1         | 1      | 0.18%   |
| PNY USB             | 1         | 1      | 0.18%   |
| Phison Electronics  | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 8         | 1.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 7         | 1.17%   |
| Kingston SA400S37240G 240GB SSD      | 7         | 1.17%   |
| Toshiba MQ01ABF050 500GB             | 5         | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 0.83%   |
| Toshiba MQ01ABD100 1TB               | 4         | 0.67%   |
| Seagate ST9500325AS 500GB            | 4         | 0.67%   |
| Seagate ST500LT012-1DG142 500GB      | 4         | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 0.67%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.67%   |
| Crucial CT480BX500SSD1 480GB         | 4         | 0.67%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.67%   |
| A-DATA SU650 240GB SSD               | 4         | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 3         | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 0.5%    |
| WDC WD10SPZX-24Z10T0 1TB             | 3         | 0.5%    |
| WDC PC SN520 SDAPNUW-256G-1006 256GB | 3         | 0.5%    |
| Unknown SD/MMC/MS PRO 64GB           | 3         | 0.5%    |
| Seagate Backup+ Hub BK 8TB           | 3         | 0.5%    |
| Samsung SSD 850 EVO 250GB            | 3         | 0.5%    |
| Samsung HD502IJ 500GB                | 3         | 0.5%    |
| Samsung HD103SJ 1TB                  | 3         | 0.5%    |
| Hitachi HTS543232A7A384 320GB        | 3         | 0.5%    |
| Unknown                              | 3         | 0.5%    |
| WDC WD800JD-60LSA5 80GB              | 2         | 0.33%   |
| WDC WD7500BPVX-55JC3T3 752GB         | 2         | 0.33%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 2         | 0.33%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 0.33%   |
| WDC WD40EFRX-68N32N0 4TB             | 2         | 0.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.33%   |
| WDC WD2500AAKX-07U6AA1 250GB         | 2         | 0.33%   |
| WDC WD2500AAJS-75M0A0 249GB          | 2         | 0.33%   |
| WDC WD10EZEX-00WN4A0 1TB             | 2         | 0.33%   |
| WDC WD10EACS-00D6B0 1TB              | 2         | 0.33%   |
| USB 3.0 1TB                          | 2         | 0.33%   |
| Unknown MMC Card  64GB               | 2         | 0.33%   |
| Unknown MMC Card  16GB               | 2         | 0.33%   |
| Unknown MMC Card  128GB              | 2         | 0.33%   |
| Unknown M52516  16GB                 | 2         | 0.33%   |
| Unknown DA4064  64GB                 | 2         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 106       | 135    | 34.75%  |
| WDC                 | 86        | 123    | 28.2%   |
| Hitachi             | 34        | 41     | 11.15%  |
| Toshiba             | 29        | 31     | 9.51%   |
| Samsung Electronics | 23        | 28     | 7.54%   |
| Fujitsu             | 9         | 9      | 2.95%   |
| HGST                | 7         | 9      | 2.3%    |
| Unknown             | 3         | 3      | 0.98%   |
| Maxtor              | 3         | 3      | 0.98%   |
| USB                 | 2         | 2      | 0.66%   |
| LaCie               | 1         | 1      | 0.33%   |
| Hewlett-Packard     | 1         | 1      | 0.33%   |
| Apple               | 1         | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 36     | 16.37%  |
| Kingston            | 21        | 21     | 12.28%  |
| Crucial             | 21        | 34     | 12.28%  |
| WDC                 | 12        | 15     | 7.02%   |
| SanDisk             | 11        | 15     | 6.43%   |
| China               | 9         | 9      | 5.26%   |
| Intel               | 8         | 9      | 4.68%   |
| A-DATA Technology   | 6         | 7      | 3.51%   |
| Toshiba             | 5         | 5      | 2.92%   |
| PNY                 | 4         | 4      | 2.34%   |
| Apacer              | 4         | 4      | 2.34%   |
| Team                | 3         | 3      | 1.75%   |
| LITEONIT            | 3         | 3      | 1.75%   |
| Corsair             | 3         | 3      | 1.75%   |
| Transcend           | 2         | 2      | 1.17%   |
| SK hynix            | 2         | 2      | 1.17%   |
| OCZ                 | 2         | 2      | 1.17%   |
| LDLC                | 2         | 2      | 1.17%   |
| Intenso             | 2         | 2      | 1.17%   |
| Vaseky              | 1         | 1      | 0.58%   |
| Unknown             | 1         | 1      | 0.58%   |
| TO Exter            | 1         | 1      | 0.58%   |
| TCSUNBOW            | 1         | 1      | 0.58%   |
| Star                | 1         | 1      | 0.58%   |
| SPCC                | 1         | 1      | 0.58%   |
| PNY USB             | 1         | 1      | 0.58%   |
| Patriot             | 1         | 1      | 0.58%   |
| ORTIAL              | 1         | 1      | 0.58%   |
| Micron Technology   | 1         | 1      | 0.58%   |
| Maxtor              | 1         | 1      | 0.58%   |
| Londisk             | 1         | 1      | 0.58%   |
| LITEON              | 1         | 2      | 0.58%   |
| Lexar               | 1         | 1      | 0.58%   |
| Leven               | 1         | 2      | 0.58%   |
| KingSpec            | 1         | 1      | 0.58%   |
| KingDian            | 1         | 1      | 0.58%   |
| JMicron Technology  | 1         | 1      | 0.58%   |
| Integral            | 1         | 1      | 0.58%   |
| Hewlett-Packard     | 1         | 6      | 0.58%   |
| GOODRAM             | 1         | 1      | 0.58%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 263       | 387    | 51.77%  |
| SSD     | 161       | 210    | 31.69%  |
| NVMe    | 42        | 55     | 8.27%   |
| MMC     | 35        | 44     | 6.89%   |
| Unknown | 7         | 7      | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 364       | 576    | 78.96%  |
| NVMe | 41        | 54     | 8.89%   |
| MMC  | 35        | 44     | 7.59%   |
| SAS  | 21        | 29     | 4.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 296       | 396    | 69.32%  |
| 0.51-1.0   | 97        | 151    | 22.72%  |
| 1.01-2.0   | 20        | 26     | 4.68%   |
| 3.01-4.0   | 6         | 14     | 1.41%   |
| 2.01-3.0   | 5         | 6      | 1.17%   |
| 4.01-10.0  | 3         | 4      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 119       | 27.61%  |
| 251-500        | 111       | 25.75%  |
| 501-1000       | 50        | 11.6%   |
| 51-100         | 39        | 9.05%   |
| 1-20           | 29        | 6.73%   |
| 1001-2000      | 28        | 6.5%    |
| 21-50          | 22        | 5.1%    |
| More than 3000 | 21        | 4.87%   |
| 2001-3000      | 9         | 2.09%   |
| Unknown        | 3         | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 191       | 43.61%  |
| 21-50          | 77        | 17.58%  |
| 101-250        | 56        | 12.79%  |
| 51-100         | 35        | 7.99%   |
| 251-500        | 26        | 5.94%   |
| 501-1000       | 24        | 5.48%   |
| 1001-2000      | 12        | 2.74%   |
| More than 3000 | 9         | 2.05%   |
| 2001-3000      | 5         | 1.14%   |
| Unknown        | 3         | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 3.13%   |
| Seagate ST1000DM003-9YN162 1TB        | 2         | 2      | 3.13%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 1.56%   |
| WDC WD800BEVS-60RST0 80GB             | 1         | 1      | 1.56%   |
| WDC WD5000LUCT-62C26Y0 500GB          | 1         | 1      | 1.56%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 1      | 1.56%   |
| WDC WD400EB-00CPF0 40GB               | 1         | 1      | 1.56%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 1.56%   |
| WDC WD3200BEVT-75A23T0 320GB          | 1         | 1      | 1.56%   |
| WDC WD3200AAJS-00L7A0 320GB           | 1         | 1      | 1.56%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 2      | 1.56%   |
| WDC WD2500AAJS-75M0A0 249GB           | 1         | 1      | 1.56%   |
| WDC WD1600AAJS-60B4A0 160GB           | 1         | 2      | 1.56%   |
| WDC WD10EADS-65M2B0 1TB               | 1         | 1      | 1.56%   |
| Toshiba MK5059GSXP 500GB              | 1         | 1      | 1.56%   |
| TCSUNBOW X1 32GB SSD                  | 1         | 1      | 1.56%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 1.56%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 1.56%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 1.56%   |
| Seagate ST9250410AS 250GB             | 1         | 1      | 1.56%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.56%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.56%   |
| Seagate ST380815AS 80GB               | 1         | 1      | 1.56%   |
| Seagate ST360012A 64GB                | 1         | 1      | 1.56%   |
| Seagate ST3360320AS 360GB             | 1         | 1      | 1.56%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 1.56%   |
| Seagate ST3200822AS 200GB             | 1         | 1      | 1.56%   |
| Seagate ST3160812AS 160GB             | 1         | 1      | 1.56%   |
| Seagate ST3160318AS 160GB             | 1         | 1      | 1.56%   |
| Seagate ST2000DX002-2DV164 2TB        | 1         | 1      | 1.56%   |
| Seagate ST1000NM0095-2DC10C 1TB       | 1         | 6      | 1.56%   |
| Seagate ST1000DX001-1CM162 1TB        | 1         | 1      | 1.56%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 1      | 1.56%   |
| SanDisk SSD PLUS 120GB                | 1         | 1      | 1.56%   |
| Samsung Electronics HM160JI 160GB     | 1         | 1      | 1.56%   |
| Samsung Electronics HM121HI 120GB     | 1         | 2      | 1.56%   |
| Samsung Electronics HD502IJ 500GB     | 1         | 1      | 1.56%   |
| Maxtor STM3300622A 304GB              | 1         | 1      | 1.56%   |
| Maxtor 6Y080L0 81GB                   | 1         | 1      | 1.56%   |
| Maxtor 6B200M0 208GB                  | 1         | 1      | 1.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 24     | 30.16%  |
| WDC                 | 12        | 14     | 19.05%  |
| Hitachi             | 7         | 8      | 11.11%  |
| Samsung Electronics | 3         | 4      | 4.76%   |
| Maxtor              | 3         | 3      | 4.76%   |
| Kingston            | 3         | 3      | 4.76%   |
| HGST                | 3         | 3      | 4.76%   |
| Crucial             | 3         | 3      | 4.76%   |
| SK hynix            | 2         | 2      | 3.17%   |
| Toshiba             | 1         | 1      | 1.59%   |
| TCSUNBOW            | 1         | 1      | 1.59%   |
| SanDisk             | 1         | 1      | 1.59%   |
| LDLC                | 1         | 1      | 1.59%   |
| KingSpec            | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 1      | 1.59%   |
| Apacer              | 1         | 1      | 1.59%   |
| A-DATA Technology   | 1         | 1      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 24     | 39.58%  |
| WDC                 | 11        | 13     | 22.92%  |
| Hitachi             | 7         | 8      | 14.58%  |
| Samsung Electronics | 3         | 4      | 6.25%   |
| Maxtor              | 3         | 3      | 6.25%   |
| HGST                | 3         | 3      | 6.25%   |
| Toshiba             | 1         | 1      | 2.08%   |
| Fujitsu             | 1         | 1      | 2.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 57     | 75%     |
| SSD  | 15        | 15     | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 20%     |
| WDC WD1200BEVS-22UST0 120GB       | 1         | 1      | 20%     |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 20%     |
| Samsung Electronics SSD 850 250GB | 1         | 1      | 20%     |
| Samsung Electronics HD080HJ/ 80GB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 4      | 60%     |
| Samsung Electronics | 2         | 2      | 40%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 199       | 333    | 43.17%  |
| Works    | 199       | 292    | 43.17%  |
| Malfunc  | 58        | 72     | 12.58%  |
| Failed   | 5         | 6      | 1.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 289       | 64.37%  |
| AMD                              | 77        | 17.15%  |
| Nvidia                           | 21        | 4.68%   |
| Samsung Electronics              | 12        | 2.67%   |
| SanDisk                          | 6         | 1.34%   |
| JMicron Technology               | 6         | 1.34%   |
| Marvell Technology Group         | 5         | 1.11%   |
| LSI Logic / Symbios Logic        | 4         | 0.89%   |
| Kingston Technology Company      | 4         | 0.89%   |
| ASMedia Technology               | 4         | 0.89%   |
| Toshiba America Info Systems     | 3         | 0.67%   |
| SK hynix                         | 3         | 0.67%   |
| KIOXIA                           | 3         | 0.67%   |
| VIA Technologies                 | 2         | 0.45%   |
| Micron Technology                | 2         | 0.45%   |
| ADATA Technology                 | 2         | 0.45%   |
| Solid State Storage Technology   | 1         | 0.22%   |
| Silicon Motion                   | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Phison Electronics               | 1         | 0.22%   |
| Hewlett-Packard                  | 1         | 0.22%   |
| Broadcom / LSI                   | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 48        | 8.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 22        | 3.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 21        | 3.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 19        | 3.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 3.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 16        | 2.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 16        | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 14        | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 14        | 2.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 2.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 11        | 1.99%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 10        | 1.81%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 10        | 1.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9         | 1.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 1.62%   |
| Nvidia MCP61 SATA Controller                                                     | 8         | 1.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 8         | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 8         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 1.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 1.08%   |
| Nvidia MCP61 IDE                                                                 | 6         | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 1.08%   |
| Intel SATA Controller [RAID mode]                                                | 6         | 1.08%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 6         | 1.08%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 6         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 6         | 1.08%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 0.9%    |
| JMicron JMB363 SATA/IDE Controller                                               | 5         | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 0.9%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 5         | 0.9%    |
| Intel 4 Series Chipset PT IDER Controller                                        | 5         | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 5         | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 0.9%    |
| AMD 400 Series Chipset SATA Controller                                           | 5         | 0.9%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 4         | 0.72%   |
| Nvidia MCP51 Serial ATA Controller                                               | 4         | 0.72%   |
| Kingston Company Company Non-Volatile memory controller                          | 4         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 306       | 63.62%  |
| IDE  | 105       | 21.83%  |
| NVMe | 40        | 8.32%   |
| RAID | 28        | 5.82%   |
| SCSI | 2         | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 324       | 76.6%   |
| AMD    | 99        | 23.4%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 8         | 1.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz            | 6         | 1.42%   |
| Intel Core i3-6006U CPU @ 2.00GHz            | 6         | 1.42%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz         | 6         | 1.42%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz  | 5         | 1.18%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz         | 5         | 1.18%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz            | 5         | 1.18%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 4         | 0.95%   |
| Intel Celeron CPU 847 @ 1.10GHz              | 4         | 0.95%   |
| AMD E-300 APU with Radeon HD Graphics        | 4         | 0.95%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz     | 3         | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 3         | 0.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 3         | 0.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 3         | 0.71%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 3         | 0.71%   |
| Intel Core i5-2400 CPU @ 3.10GHz             | 3         | 0.71%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 3         | 0.71%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 3         | 0.71%   |
| Intel Core i3 CPU M 370 @ 2.40GHz            | 3         | 0.71%   |
| Intel Celeron N4020 CPU @ 1.10GHz            | 3         | 0.71%   |
| Intel Celeron CPU J1900 @ 1.99GHz            | 3         | 0.71%   |
| Intel Atom CPU Z3735F @ 1.33GHz              | 3         | 0.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 3         | 0.71%   |
| AMD Ryzen 7 4700U with Radeon Graphics       | 3         | 0.71%   |
| AMD Ryzen 7 3700X 8-Core Processor           | 3         | 0.71%   |
| AMD Ryzen 5 3600 6-Core Processor            | 3         | 0.71%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G | 3         | 0.71%   |
| AMD A10-6800K APU with Radeon HD Graphics    | 3         | 0.71%   |
| Intel Xeon CPU E5620 @ 2.40GHz               | 2         | 0.47%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz  | 2         | 0.47%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz  | 2         | 0.47%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 2         | 0.47%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 0.47%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 2         | 0.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 2         | 0.47%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 2         | 0.47%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 2         | 0.47%   |
| Intel Core i7-3770K CPU @ 3.50GHz            | 2         | 0.47%   |
| Intel Core i7-2640M CPU @ 2.80GHz            | 2         | 0.47%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 2         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 69        | 16.31%  |
| Intel Core i3           | 42        | 9.93%   |
| Intel Core i7           | 37        | 8.75%   |
| Intel Celeron           | 37        | 8.75%   |
| Intel Core 2 Duo        | 35        | 8.27%   |
| Intel Atom              | 32        | 7.57%   |
| Intel Pentium Dual-Core | 12        | 2.84%   |
| Other                   | 10        | 2.36%   |
| Intel Xeon              | 10        | 2.36%   |
| Intel Pentium           | 10        | 2.36%   |
| Intel Core 2            | 9         | 2.13%   |
| AMD Ryzen 7             | 9         | 2.13%   |
| AMD Ryzen 5             | 8         | 1.89%   |
| AMD Athlon 64 X2        | 8         | 1.89%   |
| Intel Pentium Dual      | 6         | 1.42%   |
| AMD E                   | 6         | 1.42%   |
| AMD Athlon II X2        | 6         | 1.42%   |
| Intel Core 2 Quad       | 5         | 1.18%   |
| AMD A10                 | 5         | 1.18%   |
| AMD Ryzen 3             | 4         | 0.95%   |
| AMD E1                  | 4         | 0.95%   |
| AMD A6                  | 4         | 0.95%   |
| AMD A4                  | 4         | 0.95%   |
| Intel Pentium Silver    | 3         | 0.71%   |
| Intel Celeron Dual-Core | 3         | 0.71%   |
| AMD Turion 64 X2 Mobile | 3         | 0.71%   |
| AMD FX                  | 3         | 0.71%   |
| AMD Athlon 64           | 3         | 0.71%   |
| Intel Pentium 4         | 2         | 0.47%   |
| AMD Sempron             | 2         | 0.47%   |
| AMD Ryzen Threadripper  | 2         | 0.47%   |
| AMD Ryzen 7 PRO         | 2         | 0.47%   |
| AMD Phenom II           | 2         | 0.47%   |
| AMD GX                  | 2         | 0.47%   |
| AMD Athlon X2           | 2         | 0.47%   |
| AMD A8                  | 2         | 0.47%   |
| Intel Pentium Gold      | 1         | 0.24%   |
| Intel Genuine           | 1         | 0.24%   |
| Intel Core m3           | 1         | 0.24%   |
| Intel Core 2 Solo       | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 256       | 60.52%  |
| 4      | 114       | 26.95%  |
| 1      | 19        | 4.49%   |
| 8      | 14        | 3.31%   |
| 6      | 12        | 2.84%   |
| 12     | 2         | 0.47%   |
| 3      | 2         | 0.47%   |
| 64     | 1         | 0.24%   |
| 40     | 1         | 0.24%   |
| 20     | 1         | 0.24%   |
| 16     | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 417       | 98.58%  |
| 2      | 5         | 1.18%   |
| 4      | 1         | 0.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 232       | 54.85%  |
| 2      | 191       | 45.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 423       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 10.54%  |
| 0x206a7    | 35        | 8.2%    |
| 0x1067a    | 25        | 5.85%   |
| 0x6fd      | 18        | 4.22%   |
| 0x306a9    | 18        | 4.22%   |
| 0x306c3    | 17        | 3.98%   |
| 0x406c4    | 13        | 3.04%   |
| 0x20655    | 13        | 3.04%   |
| 0x406e3    | 12        | 2.81%   |
| 0x40651    | 12        | 2.81%   |
| 0x30678    | 12        | 2.81%   |
| 0x10676    | 10        | 2.34%   |
| 0x806ec    | 9         | 2.11%   |
| 0x406c3    | 9         | 2.11%   |
| 0x06006705 | 9         | 2.11%   |
| 0x05000119 | 9         | 2.11%   |
| 0x706a1    | 7         | 1.64%   |
| 0x106ca    | 7         | 1.64%   |
| 0x6fb      | 6         | 1.41%   |
| 0x6f6      | 6         | 1.41%   |
| 0x306d4    | 6         | 1.41%   |
| 0x06001119 | 6         | 1.41%   |
| 0x010000c8 | 6         | 1.41%   |
| 0x806e9    | 5         | 1.17%   |
| 0x806c1    | 5         | 1.17%   |
| 0x20652    | 5         | 1.17%   |
| 0x906e9    | 4         | 0.94%   |
| 0x30661    | 4         | 0.94%   |
| 0x906ea    | 3         | 0.7%    |
| 0x806eb    | 3         | 0.7%    |
| 0x806ea    | 3         | 0.7%    |
| 0x706a8    | 3         | 0.7%    |
| 0x10661    | 3         | 0.7%    |
| 0x08701021 | 3         | 0.7%    |
| 0x08600106 | 3         | 0.7%    |
| 0x0800820d | 3         | 0.7%    |
| 0x07030105 | 3         | 0.7%    |
| 0x0700010f | 3         | 0.7%    |
| 0x06000852 | 3         | 0.7%    |
| 0xa0653    | 2         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 39        | 9.22%   |
| Core            | 39        | 9.22%   |
| Silvermont      | 37        | 8.75%   |
| Penryn          | 37        | 8.75%   |
| Haswell         | 34        | 8.04%   |
| KabyLake        | 31        | 7.33%   |
| Westmere        | 22        | 5.2%    |
| IvyBridge       | 20        | 4.73%   |
| Skylake         | 17        | 4.02%   |
| K8 Hammer       | 17        | 4.02%   |
| Zen 2           | 13        | 3.07%   |
| K10             | 13        | 3.07%   |
| Bonnell         | 12        | 2.84%   |
| Bobcat          | 11        | 2.6%    |
| Goldmont plus   | 10        | 2.36%   |
| Excavator       | 10        | 2.36%   |
| Zen+            | 9         | 2.13%   |
| Piledriver      | 9         | 2.13%   |
| Broadwell       | 7         | 1.65%   |
| TigerLake       | 6         | 1.42%   |
| Puma            | 6         | 1.42%   |
| CometLake       | 4         | 0.95%   |
| K8 & K10 hybrid | 3         | 0.71%   |
| Jaguar          | 3         | 0.71%   |
| IceLake         | 3         | 0.71%   |
| Goldmont        | 3         | 0.71%   |
| Zen 3           | 2         | 0.47%   |
| Zen             | 2         | 0.47%   |
| NetBurst        | 2         | 0.47%   |
| Steamroller     | 1         | 0.24%   |
| Nehalem         | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 258       | 55.48%  |
| AMD                              | 109       | 23.44%  |
| Nvidia                           | 92        | 19.78%  |
| Matrox Electronics Systems       | 5         | 1.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 6.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22        | 4.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 3.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 3.46%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 3.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 15        | 3.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 2.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 2.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 2.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 2.24%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 10        | 2.03%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.63%   |
| Nvidia GT218 [GeForce 210]                                                               | 7         | 1.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 1.42%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.22%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.22%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.22%   |
| AMD Renoir                                                                               | 6         | 1.22%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 5         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.02%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.02%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 0.81%   |
| Intel HD Graphics 620                                                                    | 4         | 0.81%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 0.81%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 0.81%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.81%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.81%   |
| AMD Richland [Radeon HD 8670D]                                                           | 4         | 0.81%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3         | 0.61%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.61%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.61%   |
| Intel HD Graphics 530                                                                    | 3         | 0.61%   |
| Intel HD Graphics 500                                                                    | 3         | 0.61%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 221       | 52.12%  |
| 1 x AMD         | 90        | 21.23%  |
| 1 x Nvidia      | 64        | 15.09%  |
| Intel + Nvidia  | 23        | 5.42%   |
| Intel + AMD     | 12        | 2.83%   |
| 2 x AMD         | 5         | 1.18%   |
| 1 x Matrox      | 4         | 0.94%   |
| AMD + Nvidia    | 2         | 0.47%   |
| 2 x Nvidia      | 1         | 0.24%   |
| 1 x SiS         | 1         | 0.24%   |
| Nvidia + Matrox | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 374       | 88.21%  |
| Proprietary | 45        | 10.61%  |
| Unknown     | 5         | 1.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 243       | 57.18%  |
| 0.01-0.5   | 92        | 21.65%  |
| 0.51-1.0   | 37        | 8.71%   |
| 1.01-2.0   | 32        | 7.53%   |
| 3.01-4.0   | 12        | 2.82%   |
| 7.01-8.0   | 3         | 0.71%   |
| 2.01-3.0   | 3         | 0.71%   |
| 8.01-16.0  | 2         | 0.47%   |
| 5.01-6.0   | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 56        | 12.99%  |
| AU Optronics            | 51        | 11.83%  |
| LG Display              | 42        | 9.74%   |
| BOE                     | 36        | 8.35%   |
| Chimei Innolux          | 35        | 8.12%   |
| Dell                    | 26        | 6.03%   |
| Goldstar                | 21        | 4.87%   |
| Acer                    | 18        | 4.18%   |
| Hewlett-Packard         | 15        | 3.48%   |
| Lenovo                  | 12        | 2.78%   |
| Chi Mei Optoelectronics | 9         | 2.09%   |
| Philips                 | 8         | 1.86%   |
| Iiyama                  | 7         | 1.62%   |
| BenQ                    | 7         | 1.62%   |
| LG Philips              | 6         | 1.39%   |
| Apple                   | 6         | 1.39%   |
| Vizio                   | 5         | 1.16%   |
| AOC                     | 5         | 1.16%   |
| Sharp                   | 4         | 0.93%   |
| InfoVision              | 4         | 0.93%   |
| Ancor Communications    | 4         | 0.93%   |
| Unknown                 | 3         | 0.7%    |
| Sony                    | 3         | 0.7%    |
| PANDA                   | 3         | 0.7%    |
| NEC Computers           | 3         | 0.7%    |
| HannStar                | 3         | 0.7%    |
| LG Electronics          | 2         | 0.46%   |
| Lenovo Group Limited    | 2         | 0.46%   |
| IOD                     | 2         | 0.46%   |
| InnoLux Display         | 2         | 0.46%   |
| FL_                     | 2         | 0.46%   |
| CVT                     | 2         | 0.46%   |
| CPT                     | 2         | 0.46%   |
| Compaq Computer         | 2         | 0.46%   |
| ___                     | 1         | 0.23%   |
| ViewSonic               | 1         | 0.23%   |
| Videoseven              | 1         | 0.23%   |
| Unknown (ADA)           | 1         | 0.23%   |
| SHD                     | 1         | 0.23%   |
| Sceptre Tech            | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 1.14%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch  | 3         | 0.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.69%   |
| Lenovo LCD Monitor LEN4031 1280x800 303x190mm 14.1-inch               | 3         | 0.69%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 3         | 0.69%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 0.69%   |
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch  | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch  | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 2         | 0.46%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 2         | 0.46%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2         | 0.46%   |
| Iiyama PL2283H IVM562E 1920x1080 496x292mm 22.7-inch                  | 2         | 0.46%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 410x260mm 19.1-inch            | 2         | 0.46%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch           | 2         | 0.46%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch             | 2         | 0.46%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                 | 2         | 0.46%   |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                      | 2         | 0.46%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2         | 0.46%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.46%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 2         | 0.46%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 0.46%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 0.46%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                  | 2         | 0.46%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                  | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch         | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 0.46%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 2         | 0.46%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 2         | 0.46%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.23%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 1         | 0.23%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1         | 0.23%   |
| Vizio VL320M VIZ0050 1920x1080 698x393mm 31.5-inch                    | 1         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 123       | 29.01%  |
| 1920x1080 (FHD)    | 119       | 28.07%  |
| 1280x1024 (SXGA)   | 31        | 7.31%   |
| 1280x800 (WXGA)    | 27        | 6.37%   |
| 1600x900 (HD+)     | 24        | 5.66%   |
| 1680x1050 (WSXGA+) | 22        | 5.19%   |
| 3840x2160 (4K)     | 15        | 3.54%   |
| 1440x900 (WXGA+)   | 14        | 3.3%    |
| 1920x1200 (WUXGA)  | 10        | 2.36%   |
| 2560x1440 (QHD)    | 9         | 2.12%   |
| 1024x768 (XGA)     | 7         | 1.65%   |
| 1024x600           | 5         | 1.18%   |
| 2560x1600          | 3         | 0.71%   |
| 3440x1440          | 2         | 0.47%   |
| 2560x1080          | 2         | 0.47%   |
| 1600x1200          | 2         | 0.47%   |
| 1360x768           | 2         | 0.47%   |
| 3840x2400          | 1         | 0.24%   |
| 3600x1200          | 1         | 0.24%   |
| 2288x1287          | 1         | 0.24%   |
| 2048x1152          | 1         | 0.24%   |
| 1280x768           | 1         | 0.24%   |
| 1280x720 (HD)      | 1         | 0.24%   |
| Unknown            | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 114       | 26.39%  |
| 13      | 43        | 9.95%   |
| 14      | 42        | 9.72%   |
| 17      | 40        | 9.26%   |
| 23      | 21        | 4.86%   |
| 27      | 19        | 4.4%    |
| 24      | 17        | 3.94%   |
| 21      | 17        | 3.94%   |
| 19      | 17        | 3.94%   |
| 11      | 15        | 3.47%   |
| Unknown | 15        | 3.47%   |
| 22      | 14        | 3.24%   |
| 20      | 11        | 2.55%   |
| 18      | 9         | 2.08%   |
| 10      | 8         | 1.85%   |
| 12      | 5         | 1.16%   |
| 84      | 3         | 0.69%   |
| 72      | 3         | 0.69%   |
| 34      | 3         | 0.69%   |
| 41      | 2         | 0.46%   |
| 39      | 2         | 0.46%   |
| 31      | 2         | 0.46%   |
| 52      | 1         | 0.23%   |
| 48      | 1         | 0.23%   |
| 47      | 1         | 0.23%   |
| 38      | 1         | 0.23%   |
| 37      | 1         | 0.23%   |
| 33      | 1         | 0.23%   |
| 29      | 1         | 0.23%   |
| 26      | 1         | 0.23%   |
| 7       | 1         | 0.23%   |
| 5       | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 194       | 45.33%  |
| 501-600     | 56        | 13.08%  |
| 401-500     | 56        | 13.08%  |
| 201-300     | 45        | 10.51%  |
| 351-400     | 37        | 8.64%   |
| Unknown     | 15        | 3.5%    |
| 1501-2000   | 6         | 1.4%    |
| 801-900     | 4         | 0.93%   |
| 701-800     | 4         | 0.93%   |
| 601-700     | 4         | 0.93%   |
| 1001-1500   | 3         | 0.7%    |
| 101-200     | 2         | 0.47%   |
| 901-1000    | 2         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 279       | 69.58%  |
| 16/10   | 66        | 16.46%  |
| 5/4     | 28        | 6.98%   |
| Unknown | 12        | 2.99%   |
| 4/3     | 9         | 2.24%   |
| 21/9    | 4         | 1%      |
| 6/5     | 2         | 0.5%    |
| 3/2     | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 112       | 26.05%  |
| 81-90          | 72        | 16.74%  |
| 201-250        | 59        | 13.72%  |
| 151-200        | 33        | 7.67%   |
| 141-150        | 24        | 5.58%   |
| 301-350        | 20        | 4.65%   |
| 121-130        | 17        | 3.95%   |
| 51-60          | 15        | 3.49%   |
| Unknown        | 15        | 3.49%   |
| 71-80          | 14        | 3.26%   |
| More than 1000 | 8         | 1.86%   |
| 41-50          | 8         | 1.86%   |
| 251-300        | 7         | 1.63%   |
| 501-1000       | 7         | 1.63%   |
| 351-500        | 6         | 1.4%    |
| 131-140        | 5         | 1.16%   |
| 61-70          | 4         | 0.93%   |
| 1-40           | 2         | 0.47%   |
| 111-120        | 1         | 0.23%   |
| 91-100         | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 152       | 36.19%  |
| 101-120       | 148       | 35.24%  |
| 121-160       | 83        | 19.76%  |
| Unknown       | 15        | 3.57%   |
| 161-240       | 12        | 2.86%   |
| 1-50          | 6         | 1.43%   |
| More than 240 | 4         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 367       | 85.95%  |
| 2     | 48        | 11.24%  |
| 0     | 8         | 1.87%   |
| 3     | 3         | 0.7%    |
| 4     | 1         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 234       | 36.68%  |
| Intel                             | 165       | 25.86%  |
| Qualcomm Atheros                  | 86        | 13.48%  |
| Broadcom                          | 45        | 7.05%   |
| Ralink Technology                 | 17        | 2.66%   |
| Nvidia                            | 17        | 2.66%   |
| Marvell Technology Group          | 17        | 2.66%   |
| Broadcom Limited                  | 12        | 1.88%   |
| Ralink                            | 8         | 1.25%   |
| TP-Link                           | 5         | 0.78%   |
| Samsung Electronics               | 4         | 0.63%   |
| ASIX Electronics                  | 4         | 0.63%   |
| NetGear                           | 2         | 0.31%   |
| Fibocom                           | 2         | 0.31%   |
| Dell                              | 2         | 0.31%   |
| Belkin Components                 | 2         | 0.31%   |
| Attansic Technology               | 2         | 0.31%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 136       | 18.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 48        | 6.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 18        | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 1.9%    |
| Intel Wireless 7260                                                     | 13        | 1.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 1.49%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 1.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 1.36%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 1.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.09%   |
| Nvidia MCP61 Ethernet                                                   | 8         | 1.09%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 0.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.95%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.81%   |
| Intel Wireless 7265                                                     | 6         | 0.81%   |
| Intel Wireless 3165                                                     | 6         | 0.81%   |
| Intel Wireless 3160                                                     | 6         | 0.81%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 0.81%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 6         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 0.68%   |
| Intel Wireless 8260                                                     | 5         | 0.68%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 0.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.54%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.54%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 4         | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                    | 4         | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 124       | 37.35%  |
| Qualcomm Atheros      | 73        | 21.99%  |
| Realtek Semiconductor | 64        | 19.28%  |
| Broadcom              | 26        | 7.83%   |
| Ralink Technology     | 17        | 5.12%   |
| Ralink                | 8         | 2.41%   |
| TP-Link               | 5         | 1.51%   |
| Broadcom Limited      | 4         | 1.2%    |
| NetGear               | 2         | 0.6%    |
| Fibocom               | 2         | 0.6%    |
| Belkin Components     | 2         | 0.6%    |
| ZyXEL Communications  | 1         | 0.3%    |
| Tenda                 | 1         | 0.3%    |
| Sitecom Europe        | 1         | 0.3%    |
| Logitec               | 1         | 0.3%    |
| Dell                  | 1         | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 18        | 5.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 4.2%    |
| Intel Wireless 7260                                                     | 13        | 3.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 3.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 3.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 3%      |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.4%    |
| Intel Wi-Fi 6 AX200                                                     | 8         | 2.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 2.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 2.1%    |
| Ralink MT7601U Wireless Adapter                                         | 7         | 2.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 2.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.8%    |
| Intel Wireless 7265                                                     | 6         | 1.8%    |
| Intel Wireless 3165                                                     | 6         | 1.8%    |
| Intel Wireless 3160                                                     | 6         | 1.8%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 1.8%    |
| Intel Wireless 8260                                                     | 5         | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.2%    |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.2%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 4         | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.2%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.2%    |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.2%    |
| Realtek RTL8187 Wireless Adapter                                        | 3         | 0.9%    |
| Realtek 802.11ac NIC                                                    | 3         | 0.9%    |
| Ralink RT5572 Wireless Adapter                                          | 3         | 0.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.9%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 3         | 0.9%    |
| Intel Wireless-AC 9260                                                  | 3         | 0.9%    |
| Intel Wireless 8265 / 8275                                              | 3         | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.9%    |
| Intel Centrino Wireless-N 100                                           | 3         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 208       | 53.33%  |
| Intel                    | 72        | 18.46%  |
| Broadcom                 | 28        | 7.18%   |
| Qualcomm Atheros         | 24        | 6.15%   |
| Nvidia                   | 17        | 4.36%   |
| Marvell Technology Group | 17        | 4.36%   |
| Broadcom Limited         | 8         | 2.05%   |
| Samsung Electronics      | 4         | 1.03%   |
| ASIX Electronics         | 4         | 1.03%   |
| Attansic Technology      | 2         | 0.51%   |
| Xiaomi                   | 1         | 0.26%   |
| VIA Technologies         | 1         | 0.26%   |
| MediaTek                 | 1         | 0.26%   |
| Huawei Technologies      | 1         | 0.26%   |
| Aquantia                 | 1         | 0.26%   |
| ADMtek                   | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 136       | 34.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 48        | 12.03%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 2.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9         | 2.26%   |
| Nvidia MCP61 Ethernet                                             | 8         | 2.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 1.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 1.25%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.25%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1%      |
| Intel 82579V Gigabit Network Connection                           | 4         | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1%      |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.75%   |
| Nvidia MCP51 Ethernet Controller                                  | 3         | 0.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.75%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.75%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.75%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3         | 0.75%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.75%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 3         | 0.75%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 3         | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.5%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.5%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.5%    |
| Nvidia CK804 Ethernet Controller                                  | 2         | 0.5%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 2         | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 378       | 54%     |
| WiFi     | 317       | 45.29%  |
| Modem    | 5         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 246       | 56.42%  |
| Ethernet | 190       | 43.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 236       | 55.79%  |
| 1     | 161       | 38.06%  |
| 0     | 16        | 3.78%   |
| 3     | 7         | 1.65%   |
| 4     | 3         | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 358       | 83.45%  |
| Yes  | 71        | 16.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 84        | 42%     |
| Qualcomm Atheros Communications | 20        | 10%     |
| Cambridge Silicon Radio         | 17        | 8.5%    |
| Broadcom                        | 17        | 8.5%    |
| Realtek Semiconductor           | 16        | 8%      |
| Lite-On Technology              | 10        | 5%      |
| IMC Networks                    | 6         | 3%      |
| Apple                           | 6         | 3%      |
| Dell                            | 5         | 2.5%    |
| ASUSTek Computer                | 5         | 2.5%    |
| Hewlett-Packard                 | 4         | 2%      |
| Toshiba                         | 2         | 1%      |
| Ralink Technology               | 2         | 1%      |
| Alps Electric                   | 2         | 1%      |
| Ralink                          | 1         | 0.5%    |
| Logitech                        | 1         | 0.5%    |
| Foxconn / Hon Hai               | 1         | 0.5%    |
| Chicony Electronics             | 1         | 0.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 42        | 21%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 17        | 8.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 15        | 7.5%    |
| Realtek Bluetooth Radio                             | 11        | 5.5%    |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 5.5%    |
| Intel AX200 Bluetooth                               | 7         | 3.5%    |
| Intel AX201 Bluetooth                               | 5         | 2.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 2%      |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 2%      |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 2%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.5%    |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 1.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.5%    |
| IMC Networks Bluetooth Radio                        | 3         | 1.5%    |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.5%    |
| Apple Bluetooth Host Controller                     | 3         | 1.5%    |
| Realtek RTL8821A Bluetooth                          | 2         | 1%      |
| Realtek RTL8723B Bluetooth                          | 2         | 1%      |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 2         | 1%      |
| Lite-On Bluetooth Device                            | 2         | 1%      |
| IMC Networks Bluetooth Device                       | 2         | 1%      |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1%      |
| Dell Wireless 365 Bluetooth                         | 2         | 1%      |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 1%      |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1%      |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 1%      |
| ASUS Bluetooth Device                               | 2         | 1%      |
| Apple Bluetooth USB Host Controller                 | 2         | 1%      |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.5%    |
| Toshiba Bluetooth Radio                             | 1         | 0.5%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.5%    |
| Ralink RT3290 Bluetooth                             | 1         | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.5%    |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 0.5%    |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.5%    |
| Lite-On Bluetooth Radio                             | 1         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 291       | 58.79%  |
| AMD                               | 104       | 21.01%  |
| Nvidia                            | 73        | 14.75%  |
| C-Media Electronics               | 6         | 1.21%   |
| Creative Labs                     | 4         | 0.81%   |
| GN Netcom                         | 3         | 0.61%   |
| XMOS                              | 2         | 0.4%    |
| Texas Instruments                 | 2         | 0.4%    |
| Logitech                          | 2         | 0.4%    |
| VIA Technologies                  | 1         | 0.2%    |
| Unknown                           | 1         | 0.2%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.2%    |
| Focusrite-Novation                | 1         | 0.2%    |
| Elitegroup Computer Systems (ECS) | 1         | 0.2%    |
| Creative Technology               | 1         | 0.2%    |
| ASUSTek Computer                  | 1         | 0.2%    |
| Asahi Kasei Microsystems          | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 29        | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 27        | 4.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 26        | 4.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 26        | 4.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 23        | 3.91%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 3.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 22        | 3.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 3.23%   |
| AMD FCH Azalia Controller                                                                         | 19        | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 2.89%   |
| Nvidia High Definition Audio Controller                                                           | 14        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 2.21%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 2.21%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 2.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 1.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 1.7%    |
| AMD High Definition Audio Controller                                                              | 10        | 1.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 1.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 1.53%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.53%   |
| Nvidia MCP61 High Definition Audio                                                                | 8         | 1.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.36%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 1.36%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 1.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.02%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.02%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.02%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 6         | 1.02%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 0.85%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 5         | 0.85%   |
| Nvidia MCP51 High Definition Audio                                                                | 4         | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 75        | 22.94%  |
| SK hynix            | 61        | 18.65%  |
| Unknown             | 52        | 15.9%   |
| Micron Technology   | 25        | 7.65%   |
| Kingston            | 19        | 5.81%   |
| Crucial             | 13        | 3.98%   |
| Nanya Technology    | 11        | 3.36%   |
| Corsair             | 10        | 3.06%   |
| G.Skill             | 9         | 2.75%   |
| A-DATA Technology   | 8         | 2.45%   |
| Unknown (ABCD)      | 6         | 1.83%   |
| Elpida              | 5         | 1.53%   |
| Smart               | 4         | 1.22%   |
| Patriot             | 4         | 1.22%   |
| Team                | 3         | 0.92%   |
| PNY                 | 3         | 0.92%   |
| Timetec             | 2         | 0.61%   |
| Qimonda             | 2         | 0.61%   |
| Unifosa             | 1         | 0.31%   |
| Transcend           | 1         | 0.31%   |
| Teikon              | 1         | 0.31%   |
| Sesame              | 1         | 0.31%   |
| Ramaxel Technology  | 1         | 0.31%   |
| Multilaser          | 1         | 0.31%   |
| GOODRAM             | 1         | 0.31%   |
| Goldkey             | 1         | 0.31%   |
| Goldenmars          | 1         | 0.31%   |
| e2e4                | 1         | 0.31%   |
| Digiboard           | 1         | 0.31%   |
| Avant               | 1         | 0.31%   |
| ASint Technology    | 1         | 0.31%   |
| Apacer              | 1         | 0.31%   |
| 48spaces            | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 5         | 1.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 1.43%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 5         | 1.43%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.14%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 4         | 1.14%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.86%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 3         | 0.86%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 0.86%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.86%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.86%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 3         | 0.86%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                   | 2         | 0.57%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 2         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 0.57%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 2         | 0.57%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 2         | 0.57%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 2         | 0.57%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 2         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 0.57%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 2         | 0.57%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                    | 2         | 0.57%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.57%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.57%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.57%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.57%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 2         | 0.57%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.57%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 0.57%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.57%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.57%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s           | 2         | 0.57%   |
| PNY RAM Module 8192MB SODIMM DDR3 1600MT/s                       | 2         | 0.57%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.57%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s               | 2         | 0.57%   |
| Micron RAM Module 8192MB SODIMM DDR4 2667MT/s                    | 2         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 129       | 45.58%  |
| DDR4    | 73        | 25.8%   |
| DDR2    | 38        | 13.43%  |
| SDRAM   | 16        | 5.65%   |
| LPDDR4  | 9         | 3.18%   |
| Unknown | 9         | 3.18%   |
| LPDDR3  | 6         | 2.12%   |
| DDR     | 3         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 179       | 64.62%  |
| DIMM         | 89        | 32.13%  |
| Row Of Chips | 7         | 2.53%   |
| Chip         | 1         | 0.36%   |
| Unknown      | 1         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 97        | 31.09%  |
| 2048  | 82        | 26.28%  |
| 8192  | 81        | 25.96%  |
| 1024  | 28        | 8.97%   |
| 16384 | 17        | 5.45%   |
| 32768 | 3         | 0.96%   |
| 512   | 3         | 0.96%   |
| 65536 | 1         | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 73        | 23.55%  |
| 2400    | 27        | 8.71%   |
| 1333    | 27        | 8.71%   |
| 2667    | 25        | 8.06%   |
| 1334    | 22        | 7.1%    |
| 667     | 20        | 6.45%   |
| 3200    | 18        | 5.81%   |
| 800     | 15        | 4.84%   |
| 2133    | 13        | 4.19%   |
| 2048    | 9         | 2.9%    |
| 1867    | 9         | 2.9%    |
| 1066    | 9         | 2.9%    |
| Unknown | 7         | 2.26%   |
| 1866    | 5         | 1.61%   |
| 533     | 5         | 1.61%   |
| 400     | 5         | 1.61%   |
| 3266    | 3         | 0.97%   |
| 3600    | 2         | 0.65%   |
| 3000    | 2         | 0.65%   |
| 1639    | 2         | 0.65%   |
| 1067    | 2         | 0.65%   |
| 49926   | 1         | 0.32%   |
| 8400    | 1         | 0.32%   |
| 4267    | 1         | 0.32%   |
| 3866    | 1         | 0.32%   |
| 3066    | 1         | 0.32%   |
| 2733    | 1         | 0.32%   |
| 1200    | 1         | 0.32%   |
| 333     | 1         | 0.32%   |
| 2       | 1         | 0.32%   |
| 1       | 1         | 0.32%   |

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
| Chicony Electronics                    | 61        | 25.31%  |
| Acer                                   | 21        | 8.71%   |
| Realtek Semiconductor                  | 20        | 8.3%    |
| IMC Networks                           | 16        | 6.64%   |
| Microdia                               | 15        | 6.22%   |
| Sunplus Innovation Technology          | 10        | 4.15%   |
| Alcor Micro                            | 10        | 4.15%   |
| Suyin                                  | 9         | 3.73%   |
| Quanta                                 | 8         | 3.32%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.32%   |
| Silicon Motion                         | 6         | 2.49%   |
| Lite-On Technology                     | 5         | 2.07%   |
| Apple                                  | 5         | 2.07%   |
| Ricoh                                  | 4         | 1.66%   |
| Luxvisions Innotech Limited            | 4         | 1.66%   |
| Logitech                               | 4         | 1.66%   |
| Z-Star Microelectronics                | 3         | 1.24%   |
| Syntek                                 | 3         | 1.24%   |
| Samsung Electronics                    | 3         | 1.24%   |
| Lenovo                                 | 3         | 1.24%   |
| Importek                               | 3         | 1.24%   |
| Generalplus Technology                 | 3         | 1.24%   |
| ALi                                    | 3         | 1.24%   |
| SJ-180517-N                            | 2         | 0.83%   |
| Y Media                                | 1         | 0.41%   |
| WCM_USB                                | 1         | 0.41%   |
| OmniVision Technologies                | 1         | 0.41%   |
| Nintendo                               | 1         | 0.41%   |
| Microsoft                              | 1         | 0.41%   |
| LG Electronics                         | 1         | 0.41%   |
| KYE Systems (Mouse Systems)            | 1         | 0.41%   |
| Guillemot                              | 1         | 0.41%   |
| Genesys Logic                          | 1         | 0.41%   |
| GEMBIRD                                | 1         | 0.41%   |
| DigiTech                               | 1         | 0.41%   |
| ARC International                      | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 8         | 3.29%   |
| Realtek Integrated_Webcam_HD                         | 7         | 2.88%   |
| Chicony TOSHIBA Web Camera - HD                      | 6         | 2.47%   |
| Alcor Micro USB 2.0 Camera                           | 6         | 2.47%   |
| Acer Lenovo EasyCamera                               | 5         | 2.06%   |
| Realtek USB Camera                                   | 4         | 1.65%   |
| Chicony HP HD Camera                                 | 4         | 1.65%   |
| Samsung Galaxy A5 (MTP)                              | 3         | 1.23%   |
| Realtek Integrated Webcam                            | 3         | 1.23%   |
| Luxvisions Innotech Limited HP HD Camera             | 3         | 1.23%   |
| Lite-On HP HD Camera                                 | 3         | 1.23%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 1.23%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 3         | 1.23%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 3         | 1.23%   |
| Chicony HD WebCam                                    | 3         | 1.23%   |
| Chicony EasyCamera                                   | 3         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101 | 3         | 1.23%   |
| Apple FaceTime HD Camera                             | 3         | 1.23%   |
| Alcor Micro Asus Integrated Webcam                   | 3         | 1.23%   |
| Acer VGA WebCam                                      | 3         | 1.23%   |
| Acer HD WebCam                                       | 3         | 1.23%   |
| Sunplus Laptop Integrated Webcam HD                  | 2         | 0.82%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 0.82%   |
| Sunplus HD WebCam                                    | 2         | 0.82%   |
| SJ-180517-N 1080P Webcam                             | 2         | 0.82%   |
| Realtek Lenovo EasyCamera                            | 2         | 0.82%   |
| Quanta VGA WebCam                                    | 2         | 0.82%   |
| Quanta HP Webcam                                     | 2         | 0.82%   |
| Quanta HP HD Camera                                  | 2         | 0.82%   |
| Microdia Sonix USB 2.0 Camera                        | 2         | 0.82%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 2         | 0.82%   |
| Microdia Integrated Webcam                           | 2         | 0.82%   |
| Microdia 1.3 MPixel Integrated Webcam                | 2         | 0.82%   |
| Logitech Webcam C270                                 | 2         | 0.82%   |
| Importek TOSHIBA Web Camera - HD                     | 2         | 0.82%   |
| IMC Networks USB 2.0 UVC VGA WebCam                  | 2         | 0.82%   |
| IMC Networks Integrated Camera                       | 2         | 0.82%   |
| Generalplus GENERAL WEBCAM                           | 2         | 0.82%   |
| Chicony USB 2.0 Camera                               | 2         | 0.82%   |
| Chicony Lenovo EasyCamera                            | 2         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 38.71%  |
| AuthenTec                  | 8         | 25.81%  |
| Synaptics                  | 3         | 9.68%   |
| Shenzhen Goodix Technology | 3         | 9.68%   |
| Upek                       | 2         | 6.45%   |
| STMicroelectronics         | 2         | 6.45%   |
| LighTuning Technology      | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                       | 3         | 9.68%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 6.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 6.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 2         | 6.45%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 6.45%   |
| STMicroelectronics Fingerprint Reader                      | 2         | 6.45%   |
| AuthenTec AES2810                                          | 2         | 6.45%   |
| AuthenTec AES1600                                          | 2         | 6.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 1         | 3.23%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 3.23%   |
| Validity Sensors VFS491                                    | 1         | 3.23%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 3.23%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 3.23%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 3.23%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 3.23%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 3.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 3.23%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 3.23%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 3.23%   |
| Shenzhen Goodix FingerPrint                                | 1         | 3.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 3.23%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 3.23%   |

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
| 0     | 340       | 79.81%  |
| 1     | 70        | 16.43%  |
| 2     | 16        | 3.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 31.96%  |
| Graphics card            | 17        | 17.53%  |
| Net/wireless             | 14        | 14.43%  |
| Chipcard                 | 9         | 9.28%   |
| Communication controller | 5         | 5.15%   |
| Unassigned class         | 3         | 3.09%   |
| Sound                    | 3         | 3.09%   |
| Multimedia controller    | 3         | 3.09%   |
| Camera                   | 3         | 3.09%   |
| Storage                  | 2         | 2.06%   |
| Net/ethernet             | 2         | 2.06%   |
| Dvb card                 | 2         | 2.06%   |
| Bluetooth                | 2         | 2.06%   |
| Flash memory             | 1         | 1.03%   |

