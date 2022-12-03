Nobara - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Nobara.

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

Total: 110

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Lenovo        | V14-IIL 82C4                | [407b574c57](https://linux-hardware.org/?probe=407b574c57) | Nov 28, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [91fa73480c](https://linux-hardware.org/?probe=91fa73480c) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [93576caa19](https://linux-hardware.org/?probe=93576caa19) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| HP            | ProBook 445 14 inch G9 N... | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [9324629428](https://linux-hardware.org/?probe=9324629428) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [22a1c81a68](https://linux-hardware.org/?probe=22a1c81a68) | Nov 24, 2022 |
| Coradir       | Coradir/ES10IS5             | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| HP            | Unknown                     | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Dell          | Studio 1737                 | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3ee89779cd](https://linux-hardware.org/?probe=3ee89779cd) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Acer          | Swift SFX14-41G             | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Dell          | Studio 1737                 | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| ASUSTek       | GL753VD                     | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| HP            | Unknown                     | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| Acer          | Nitro AN515-42              | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| ASUSTek       | GL502VMK                    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Toshiba       | Satellite L850              | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3912d818bd](https://linux-hardware.org/?probe=3912d818bd) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| Casper        | EXCALIBUR G770              | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [5f013faf39](https://linux-hardware.org/?probe=5f013faf39) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| HP            | 2000                        | [3341a26d0c](https://linux-hardware.org/?probe=3341a26d0c) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| Apple         | MacBookPro5,5               | [faef78b510](https://linux-hardware.org/?probe=faef78b510) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [2d464da9c8](https://linux-hardware.org/?probe=2d464da9c8) | Oct 07, 2022 |
| HP            | ZBook 17 G6                 | [c215e9e17e](https://linux-hardware.org/?probe=c215e9e17e) | Oct 07, 2022 |
| Dell          | Precision 5530              | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| KELYX ARGE... | KL9120                      | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Positivo      | N1250                       | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| HP            | 2000                        | [e6f8f7196d](https://linux-hardware.org/?probe=e6f8f7196d) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| HP            | 240 G7 Notebook PC          | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Toshiba       | Satellite L850              | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| EVOO          | EG-LP10                     | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| Acer          | Aspire VX5-591G             | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | [a423006d4c](https://linux-hardware.org/?probe=a423006d4c) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | [5dba6cf7fd](https://linux-hardware.org/?probe=5dba6cf7fd) | Sep 29, 2022 |
| Dell          | Inspiron 3542               | [6d35107941](https://linux-hardware.org/?probe=6d35107941) | Sep 28, 2022 |
| Apple         | MacBookPro8,3               | [74927fc7d2](https://linux-hardware.org/?probe=74927fc7d2) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [65f896ddab](https://linux-hardware.org/?probe=65f896ddab) | Sep 27, 2022 |
| Gateway       | NE56R                       | [f603edd045](https://linux-hardware.org/?probe=f603edd045) | Sep 23, 2022 |
| Toshiba       | TECRA A50-A                 | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| Alienware     | Area-51m R2 A00             | [0ebdec6dd0](https://linux-hardware.org/?probe=0ebdec6dd0) | Sep 20, 2022 |
| ASUSTek       | N56VZ                       | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Dell          | Precision M6400             | [67924c5333](https://linux-hardware.org/?probe=67924c5333) | Sep 19, 2022 |
| Dell          | Precision M6400             | [27a55639e4](https://linux-hardware.org/?probe=27a55639e4) | Sep 19, 2022 |
| HUAWEI        | KLVL-WXXW                   | [e0e49d51d0](https://linux-hardware.org/?probe=e0e49d51d0) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | [812ea842dc](https://linux-hardware.org/?probe=812ea842dc) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Lenovo        | ThinkPad P1 20MD0020US      | [a701fed148](https://linux-hardware.org/?probe=a701fed148) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Dell          | G5 5505                     | [25755e8605](https://linux-hardware.org/?probe=25755e8605) | Sep 16, 2022 |
| HP            | 15                          | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Acer          | Aspire A315-42              | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Dell          | Precision 3510              | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| ASUSTek       | TP500LA                     | [de395dddd8](https://linux-hardware.org/?probe=de395dddd8) | Aug 28, 2022 |
| Dell          | G15 5511                    | [44fa9bf084](https://linux-hardware.org/?probe=44fa9bf084) | Aug 21, 2022 |
| Notebook      | P7xxDM2(-G)                 | [f074899985](https://linux-hardware.org/?probe=f074899985) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| Apple         | MacBookPro14,2              | [c66d476513](https://linux-hardware.org/?probe=c66d476513) | Aug 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [df2cc1a299](https://linux-hardware.org/?probe=df2cc1a299) | Aug 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| Razer         | Blade                       | [cc3ce45956](https://linux-hardware.org/?probe=cc3ce45956) | Jul 31, 2022 |
| HP            | ZBook 15 G2                 | [3aa2fda09a](https://linux-hardware.org/?probe=3aa2fda09a) | Jul 26, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Nobara 36 | 85        | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Nobara | 85        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 5.19.14-201.fsync.fc36.x86_64 | 16        | 18.39%  |
| 5.19.9-201.fsync.fc36.x86_64  | 7         | 8.05%   |
| 5.19.7-204.fsync.fc36.x86_64  | 7         | 8.05%   |
| 6.0.7-201.fsync.fc36.x86_64   | 6         | 6.9%    |
| 6.0.5-201.fsync.fc36.x86_64   | 5         | 5.75%   |
| 5.19.12-201.fsync.fc36.x86_64 | 5         | 5.75%   |
| 5.19.8-201.fsync.fc36.x86_64  | 4         | 4.6%    |
| 5.19.16-201.fsync.fc36.x86_64 | 4         | 4.6%    |
| 5.19.11-201.fsync.fc36.x86_64 | 4         | 4.6%    |
| 6.0.9-202.fc36.x86_64         | 3         | 3.45%   |
| 6.0.9-201.fc36.x86_64         | 3         | 3.45%   |
| 5.18.16-201.fsync.fc36.x86_64 | 3         | 3.45%   |
| 5.18.13-201.fsync.fc36.x86_64 | 3         | 3.45%   |
| 6.0.8-201.fsync.fc36.x86_64   | 2         | 2.3%    |
| 6.0.10-201.fc36.x86_64        | 2         | 2.3%    |
| 5.19.4-201.fsync.fc36.x86_64  | 2         | 2.3%    |
| 5.19.15-202.fsync.fc36.x86_64 | 2         | 2.3%    |
| 5.18.17-201.fsync.fc36.x86_64 | 2         | 2.3%    |
| 6.0.7-202.fsync.fc36.x86_64   | 1         | 1.15%   |
| 6.0.2-xm1.0.fc36.x86_64       | 1         | 1.15%   |
| 5.19.7-203.fsync.fc36.x86_64  | 1         | 1.15%   |
| 5.19.13-202.fsync.fc36.x86_64 | 1         | 1.15%   |
| 5.19.10-201.fsync.fc36.x86_64 | 1         | 1.15%   |
| 5.18.19-201.fsync.fc36.x86_64 | 1         | 1.15%   |
| 5.18.18-201.fsync.fc36.x86_64 | 1         | 1.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.14 | 16        | 18.39%  |
| 5.19.7  | 8         | 9.2%    |
| 6.0.7   | 7         | 8.05%   |
| 5.19.9  | 7         | 8.05%   |
| 6.0.9   | 6         | 6.9%    |
| 6.0.5   | 5         | 5.75%   |
| 5.19.12 | 5         | 5.75%   |
| 5.19.8  | 4         | 4.6%    |
| 5.19.16 | 4         | 4.6%    |
| 5.19.11 | 4         | 4.6%    |
| 5.18.16 | 3         | 3.45%   |
| 5.18.13 | 3         | 3.45%   |
| 6.0.8   | 2         | 2.3%    |
| 6.0.10  | 2         | 2.3%    |
| 5.19.4  | 2         | 2.3%    |
| 5.19.15 | 2         | 2.3%    |
| 5.18.17 | 2         | 2.3%    |
| 6.0.2   | 1         | 1.15%   |
| 5.19.13 | 1         | 1.15%   |
| 5.19.10 | 1         | 1.15%   |
| 5.18.19 | 1         | 1.15%   |
| 5.18.18 | 1         | 1.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19    | 54        | 62.07%  |
| 6.0     | 23        | 26.44%  |
| 5.18    | 10        | 11.49%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 85        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 59        | 68.6%   |
| KDE5    | 23        | 26.74%  |
| Unknown | 4         | 4.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 71        | 82.56%  |
| X11     | 11        | 12.79%  |
| Unknown | 4         | 4.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 82.56%  |
| SDDM    | 10        | 11.63%  |
| GDM     | 5         | 5.81%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 45        | 52.33%  |
| pl_PL   | 4         | 4.65%   |
| pt_PT   | 3         | 3.49%   |
| it_IT   | 3         | 3.49%   |
| es_ES   | 3         | 3.49%   |
| es_AR   | 3         | 3.49%   |
| en_IN   | 3         | 3.49%   |
| en_GB   | 3         | 3.49%   |
| es_MX   | 2         | 2.33%   |
| de_DE   | 2         | 2.33%   |
| Unknown | 2         | 2.33%   |
| sv_SE   | 1         | 1.16%   |
| ru_RU   | 1         | 1.16%   |
| pt_BR   | 1         | 1.16%   |
| hu_HU   | 1         | 1.16%   |
| hr_HR   | 1         | 1.16%   |
| fi_FI   | 1         | 1.16%   |
| es_CR   | 1         | 1.16%   |
| es_CL   | 1         | 1.16%   |
| en_ZA   | 1         | 1.16%   |
| en_NZ   | 1         | 1.16%   |
| en_CA   | 1         | 1.16%   |
| en_AU   | 1         | 1.16%   |
| de_AT   | 1         | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 68        | 79.07%  |
| BIOS | 18        | 20.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 47        | 55.29%  |
| Btrfs | 37        | 43.53%  |
| Xfs   | 1         | 1.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 69        | 79.31%  |
| GPT     | 16        | 18.39%  |
| MBR     | 2         | 2.3%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 80        | 93.02%  |
| Yes       | 6         | 6.98%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 88.24%  |
| Yes       | 10        | 11.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 21        | 24.71%  |
| ASUSTek Computer    | 17        | 20%     |
| Hewlett-Packard     | 14        | 16.47%  |
| Dell                | 8         | 9.41%   |
| Apple               | 5         | 5.88%   |
| Acer                | 4         | 4.71%   |
| Toshiba             | 3         | 3.53%   |
| MSI                 | 2         | 2.35%   |
| Valve               | 1         | 1.18%   |
| Razer               | 1         | 1.18%   |
| Positivo            | 1         | 1.18%   |
| Notebook            | 1         | 1.18%   |
| HUAWEI              | 1         | 1.18%   |
| Gigabyte Technology | 1         | 1.18%   |
| Gateway             | 1         | 1.18%   |
| EVOO                | 1         | 1.18%   |
| Coradir             | 1         | 1.18%   |
| Casper              | 1         | 1.18%   |
| Alienware           | 1         | 1.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Lenovo IdeaPad Y700-15ISK 80NV        | 2         | 2.35%   |
| Unknown                               | 2         | 2.35%   |
| Valve Jupiter                         | 1         | 1.18%   |
| Toshiba TECRA A50-A                   | 1         | 1.18%   |
| Toshiba Satellite L850                | 1         | 1.18%   |
| Toshiba Satellite L650                | 1         | 1.18%   |
| Razer Blade                           | 1         | 1.18%   |
| Positivo N1250                        | 1         | 1.18%   |
| Notebook P7xxDM2(-G)                  | 1         | 1.18%   |
| MSI Pulse GL76 12UEK                  | 1         | 1.18%   |
| MSI GE60 0NC/GE60 0ND                 | 1         | 1.18%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 OD 82NK | 1         | 1.18%   |
| Lenovo V330-15IKB 81AX                | 1         | 1.18%   |
| Lenovo V14-IIL 82C4                   | 1         | 1.18%   |
| Lenovo ThinkPad X240 20AMA0LTAU       | 1         | 1.18%   |
| Lenovo ThinkPad P1 20MD0020US         | 1         | 1.18%   |
| Lenovo ThinkPad E14 Gen 3 20Y7CTO1WW  | 1         | 1.18%   |
| Lenovo ThinkBook 15 G3 ACL 21A4       | 1         | 1.18%   |
| Lenovo Legion S7 15ACH6 82K8          | 1         | 1.18%   |
| Lenovo Legion 5 Pro 16IAH7H 82RF      | 1         | 1.18%   |
| Lenovo Legion 5 15ARH05 82B5          | 1         | 1.18%   |
| Lenovo IdeaPadFlex 10 20324           | 1         | 1.18%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2   | 1         | 1.18%   |
| Lenovo IdeaPad C340-14API 81N6        | 1         | 1.18%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 1         | 1.18%   |
| Lenovo IdeaPad 320-15IKB 80YH         | 1         | 1.18%   |
| Lenovo IdeaPad 310-15IAP 80TT         | 1         | 1.18%   |
| Lenovo G580 20157                     | 1         | 1.18%   |
| Lenovo G580 20150                     | 1         | 1.18%   |
| Lenovo G50-30 80G0                    | 1         | 1.18%   |
| HUAWEI CREM-WXX9                      | 1         | 1.18%   |
| HP ZBook 17 G6                        | 1         | 1.18%   |
| HP ZBook 15 G2                        | 1         | 1.18%   |
| HP ProBook 445 14 inch G9 Notebook PC | 1         | 1.18%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 1         | 1.18%   |
| HP OMEN Notebook PC 15                | 1         | 1.18%   |
| HP OMEN Laptop 15-ek0xxx              | 1         | 1.18%   |
| HP Laptop 15-dw0xxx                   | 1         | 1.18%   |
| HP EliteBook 850 G2                   | 1         | 1.18%   |
| HP EliteBook 850 G1                   | 1         | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo IdeaPad       | 7         | 8.24%   |
| ASUS VivoBook        | 4         | 4.71%   |
| Lenovo ThinkPad      | 3         | 3.53%   |
| Lenovo Legion        | 3         | 3.53%   |
| Dell Precision       | 3         | 3.53%   |
| ASUS ROG             | 3         | 3.53%   |
| Toshiba Satellite    | 2         | 2.35%   |
| Lenovo G580          | 2         | 2.35%   |
| HP ZBook             | 2         | 2.35%   |
| HP OMEN              | 2         | 2.35%   |
| HP EliteBook         | 2         | 2.35%   |
| ASUS TUF             | 2         | 2.35%   |
| ASUS ASUS            | 2         | 2.35%   |
| Acer Aspire          | 2         | 2.35%   |
| Unknown              | 2         | 2.35%   |
| Valve Jupiter        | 1         | 1.18%   |
| Toshiba TECRA        | 1         | 1.18%   |
| Razer Blade          | 1         | 1.18%   |
| Positivo N1250       | 1         | 1.18%   |
| Notebook P7xxDM2(-G) | 1         | 1.18%   |
| MSI Pulse            | 1         | 1.18%   |
| MSI GE60             | 1         | 1.18%   |
| Lenovo Yoga          | 1         | 1.18%   |
| Lenovo V330-15IKB    | 1         | 1.18%   |
| Lenovo V14-IIL       | 1         | 1.18%   |
| Lenovo ThinkBook     | 1         | 1.18%   |
| Lenovo IdeaPadFlex   | 1         | 1.18%   |
| Lenovo G50-30        | 1         | 1.18%   |
| HUAWEI CREM-WXX9     | 1         | 1.18%   |
| HP ProBook           | 1         | 1.18%   |
| HP Pavilion          | 1         | 1.18%   |
| HP Laptop            | 1         | 1.18%   |
| HP 240               | 1         | 1.18%   |
| HP 2000              | 1         | 1.18%   |
| HP 15                | 1         | 1.18%   |
| Gigabyte B450        | 1         | 1.18%   |
| Gateway NE56R        | 1         | 1.18%   |
| EVOO EG-LP10         | 1         | 1.18%   |
| Dell Vostro          | 1         | 1.18%   |
| Dell Studio          | 1         | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 16        | 18.82%  |
| 2020 | 10        | 11.76%  |
| 2019 | 8         | 9.41%   |
| 2018 | 8         | 9.41%   |
| 2012 | 7         | 8.24%   |
| 2022 | 6         | 7.06%   |
| 2014 | 6         | 7.06%   |
| 2017 | 5         | 5.88%   |
| 2015 | 5         | 5.88%   |
| 2013 | 5         | 5.88%   |
| 2016 | 4         | 4.71%   |
| 2009 | 2         | 2.35%   |
| 2011 | 1         | 1.18%   |
| 2010 | 1         | 1.18%   |
| 2008 | 1         | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 85        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 85        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 85        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 22        | 25.88%  |
| 4.01-8.0   | 21        | 24.71%  |
| 16.01-24.0 | 16        | 18.82%  |
| 3.01-4.0   | 15        | 17.65%  |
| 32.01-64.0 | 8         | 9.41%   |
| 24.01-32.0 | 2         | 2.35%   |
| 1.01-2.0   | 1         | 1.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 41        | 47.67%  |
| 2.01-3.0  | 22        | 25.58%  |
| 3.01-4.0  | 18        | 20.93%  |
| 8.01-16.0 | 4         | 4.65%   |
| 1.01-2.0  | 1         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 70.59%  |
| 2      | 21        | 24.71%  |
| 3      | 4         | 4.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 77.65%  |
| Yes       | 19        | 22.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 77.65%  |
| No        | 19        | 22.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 84.71%  |
| No        | 13        | 15.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 26        | 30.59%  |
| Poland       | 5         | 5.88%   |
| India        | 4         | 4.71%   |
| Germany      | 4         | 4.71%   |
| Portugal     | 3         | 3.53%   |
| Mexico       | 3         | 3.53%   |
| Italy        | 3         | 3.53%   |
| Argentina    | 3         | 3.53%   |
| Vietnam      | 2         | 2.35%   |
| Philippines  | 2         | 2.35%   |
| Croatia      | 2         | 2.35%   |
| Chile        | 2         | 2.35%   |
| Brazil       | 2         | 2.35%   |
| Austria      | 2         | 2.35%   |
| UK           | 1         | 1.18%   |
| Taiwan       | 1         | 1.18%   |
| Sweden       | 1         | 1.18%   |
| Spain        | 1         | 1.18%   |
| South Africa | 1         | 1.18%   |
| Serbia       | 1         | 1.18%   |
| Russia       | 1         | 1.18%   |
| Romania      | 1         | 1.18%   |
| Pakistan     | 1         | 1.18%   |
| New Zealand  | 1         | 1.18%   |
| Morocco      | 1         | 1.18%   |
| Kenya        | 1         | 1.18%   |
| Indonesia    | 1         | 1.18%   |
| Hungary      | 1         | 1.18%   |
| Finland      | 1         | 1.18%   |
| Czechia      | 1         | 1.18%   |
| Cyprus       | 1         | 1.18%   |
| Costa Rica   | 1         | 1.18%   |
| Colombia     | 1         | 1.18%   |
| Canada       | 1         | 1.18%   |
| Belgium      | 1         | 1.18%   |
| Australia    | 1         | 1.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Wasilla           | 2         | 2.3%    |
| Schmalkalden      | 2         | 2.3%    |
| Poznan            | 2         | 2.3%    |
| Ochsenfurt        | 2         | 2.3%    |
| Guadalajara       | 2         | 2.3%    |
| Zamora            | 1         | 1.15%   |
| Zadar             | 1         | 1.15%   |
| Wesley Chapel     | 1         | 1.15%   |
| Wayne             | 1         | 1.15%   |
| Warsaw            | 1         | 1.15%   |
| Wabrzezno         | 1         | 1.15%   |
| Villarrica        | 1         | 1.15%   |
| Villa Nueva       | 1         | 1.15%   |
| Vienna            | 1         | 1.15%   |
| Veszprém         | 1         | 1.15%   |
| Varaždin         | 1         | 1.15%   |
| Vagos             | 1         | 1.15%   |
| Tulsa             | 1         | 1.15%   |
| Tomah             | 1         | 1.15%   |
| Tenna             | 1         | 1.15%   |
| Silves            | 1         | 1.15%   |
| Schenectady       | 1         | 1.15%   |
| San José         | 1         | 1.15%   |
| San Antonio Oeste | 1         | 1.15%   |
| San Antonio       | 1         | 1.15%   |
| Saltsjoebaden     | 1         | 1.15%   |
| Salem             | 1         | 1.15%   |
| Salamanca         | 1         | 1.15%   |
| Saint-Jerome      | 1         | 1.15%   |
| Rozsicka          | 1         | 1.15%   |
| Rome              | 1         | 1.15%   |
| Ranua             | 1         | 1.15%   |
| Ramos Mejia       | 1         | 1.15%   |
| Quezon City       | 1         | 1.15%   |
| Prichsenstadt     | 1         | 1.15%   |
| Panama City       | 1         | 1.15%   |
| Odessa            | 1         | 1.15%   |
| Novosibirsk       | 1         | 1.15%   |
| Nova Mutum        | 1         | 1.15%   |
| Nicosia           | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 23        | 27     | 21.1%   |
| Toshiba                      | 10        | 10     | 9.17%   |
| WDC                          | 9         | 10     | 8.26%   |
| Seagate                      | 8         | 8      | 7.34%   |
| Kingston                     | 7         | 7      | 6.42%   |
| SK hynix                     | 6         | 6      | 5.5%    |
| Sandisk                      | 6         | 6      | 5.5%    |
| Intel                        | 5         | 5      | 4.59%   |
| Crucial                      | 4         | 4      | 3.67%   |
| Micron/Crucial Technology    | 3         | 3      | 2.75%   |
| Micron Technology            | 3         | 3      | 2.75%   |
| Hitachi                      | 3         | 4      | 2.75%   |
| China                        | 3         | 3      | 2.75%   |
| Phison Electronics           | 2         | 2      | 1.83%   |
| LITEON                       | 2         | 2      | 1.83%   |
| KIOXIA                       | 2         | 2      | 1.83%   |
| HGST                         | 2         | 2      | 1.83%   |
| Apple                        | 2         | 3      | 1.83%   |
| Unknown                      | 2         | 2      | 1.83%   |
| Unknown                      | 1         | 1      | 0.92%   |
| Solid State Storage          | 1         | 1      | 0.92%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.92%   |
| Ramsta                       | 1         | 1      | 0.92%   |
| HGST HTS                     | 1         | 1      | 0.92%   |
| Fujitsu                      | 1         | 1      | 0.92%   |
| A-DATA Technology            | 1         | 1      | 0.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 3.51%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                | 3         | 2.63%   |
| Toshiba MQ04ABF100 1TB                            | 2         | 1.75%   |
| Toshiba MQ01ABF050 500GB                          | 2         | 1.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2         | 1.75%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB | 2         | 1.75%   |
| Samsung SSD 980 1TB                               | 2         | 1.75%   |
| Samsung NVMe SSD Drive 1024GB                     | 2         | 1.75%   |
| Samsung MZALQ512HBLU-00BL2 512GB                  | 2         | 1.75%   |
| Phison PS5013 E13 NVMe Controller 256GB           | 2         | 1.75%   |
| Micron/Crucial P2 NVMe PCIe SSD 250GB             | 2         | 1.75%   |
| Kingston SA400S37240G 240GB SSD                   | 2         | 1.75%   |
| Kingston NVMe SSD Drive 512GB                     | 2         | 1.75%   |
| Hitachi HTS547575A9E384 752GB                     | 2         | 1.75%   |
| China SATA SSD 120GB                              | 2         | 1.75%   |
| Unknown                                           | 2         | 1.75%   |
| WDC WDS500G3X0C-00SJG0 500GB                      | 1         | 0.88%   |
| WDC WDS100T2B0C-00PXH0 1TB                        | 1         | 0.88%   |
| WDC WD20EZRX-00DC0B0 2TB                          | 1         | 0.88%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 1         | 0.88%   |
| WDC WD10SPCX-24HWST1 1TB                          | 1         | 0.88%   |
| WDC WD10JPVT-22A1YT0 1TB                          | 1         | 0.88%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 1         | 0.88%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB              | 1         | 0.88%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB              | 1         | 0.88%   |
| Unknown SD/MMC/MS PRO 8GB                         | 1         | 0.88%   |
| Toshiba TR200 240GB SSD                           | 1         | 0.88%   |
| Toshiba MQ01ABD100 1TB                            | 1         | 0.88%   |
| Toshiba MQ01ABD050 500GB                          | 1         | 0.88%   |
| Toshiba MK7559GSXF 752GB                          | 1         | 0.88%   |
| Toshiba MK3265GSXN 320GB                          | 1         | 0.88%   |
| Toshiba KXG5AZNV512G 512GB                        | 1         | 0.88%   |
| Solid State Storage SSSTC CL1-8D256-HP 256GB      | 1         | 0.88%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB         | 1         | 0.88%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB              | 1         | 0.88%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB            | 1         | 0.88%   |
| SK hynix HFM512GD3JX016N 512GB                    | 1         | 0.88%   |
| SK hynix HFM256GDJTNG-8310A 256GB                 | 1         | 0.88%   |
| SK hynix C2S3T/120G 120GB                         | 1         | 0.88%   |
| Shenzhen Longsys Lexar SSD NM620 512GB            | 1         | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 8         | 8      | 27.59%  |
| Seagate  | 8         | 8      | 27.59%  |
| WDC      | 5         | 6      | 17.24%  |
| Hitachi  | 3         | 4      | 10.34%  |
| HGST     | 2         | 2      | 6.9%    |
| Unknown  | 1         | 1      | 3.45%   |
| HGST HTS | 1         | 1      | 3.45%   |
| Fujitsu  | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 26.92%  |
| Crucial             | 4         | 4      | 15.38%  |
| China               | 3         | 3      | 11.54%  |
| LITEON              | 2         | 2      | 7.69%   |
| Kingston            | 2         | 2      | 7.69%   |
| Intel               | 2         | 2      | 7.69%   |
| Toshiba             | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 1      | 3.85%   |
| SanDisk             | 1         | 1      | 3.85%   |
| Ramsta              | 1         | 1      | 3.85%   |
| Apple               | 1         | 1      | 3.85%   |
| A-DATA Technology   | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 46        | 57     | 45.1%   |
| HDD     | 28        | 31     | 27.45%  |
| SSD     | 26        | 26     | 25.49%  |
| Unknown | 2         | 2      | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 49        | 55     | 49.49%  |
| NVMe | 46        | 57     | 46.46%  |
| SAS  | 4         | 4      | 4.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 35     | 61.11%  |
| 0.51-1.0   | 19        | 20     | 35.19%  |
| 1.01-2.0   | 1         | 1      | 1.85%   |
| 4.01-10.0  | 1         | 1      | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 31.4%   |
| 251-500        | 25        | 29.07%  |
| 501-1000       | 19        | 22.09%  |
| 51-100         | 5         | 5.81%   |
| Unknown        | 5         | 5.81%   |
| 21-50          | 2         | 2.33%   |
| 1001-2000      | 2         | 2.33%   |
| More than 3000 | 1         | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 29        | 33.33%  |
| 21-50     | 23        | 26.44%  |
| 101-250   | 12        | 13.79%  |
| 51-100    | 9         | 10.34%  |
| 251-500   | 5         | 5.75%   |
| Unknown   | 5         | 5.75%   |
| 501-1000  | 3         | 3.45%   |
| 2001-3000 | 1         | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                  | Notebooks | Drives | Percent |
|------------------------|-----------|--------|---------|
| Ramsta SSD S800 240GB  | 1         | 1      | 50%     |
| Hitachi HTS54323 320GB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Ramsta  | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Detected | 71        | 89     | 78.02%  |
| Works    | 18        | 25     | 19.78%  |
| Malfunc  | 2         | 2      | 2.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 55        | 45.45%  |
| Samsung Electronics            | 17        | 14.05%  |
| AMD                            | 15        | 12.4%   |
| SanDisk                        | 8         | 6.61%   |
| SK hynix                       | 5         | 4.13%   |
| Kingston Technology Company    | 5         | 4.13%   |
| Micron/Crucial Technology      | 3         | 2.48%   |
| Micron Technology              | 3         | 2.48%   |
| Phison Electronics             | 2         | 1.65%   |
| KIOXIA                         | 2         | 1.65%   |
| Toshiba America Info Systems   | 1         | 0.83%   |
| Solid State Storage Technology | 1         | 0.83%   |
| Shenzhen Longsys Electronics   | 1         | 0.83%   |
| Nvidia                         | 1         | 0.83%   |
| Marvell Technology Group       | 1         | 0.83%   |
| Apple                          | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 11.72%  |
| Samsung NVMe SSD Controller 980                                                | 9         | 7.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 6.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 5.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 3.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 3.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 3.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 3.13%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 2.34%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 2.34%   |
| Micron Non-Volatile memory controller                                          | 3         | 2.34%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.34%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.56%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.56%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 1.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.56%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.78%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.78%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.78%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.78%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                    | 1         | 0.78%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.78%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.78%   |
| Micron/Crucial Non-Volatile memory controller                                  | 1         | 0.78%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.78%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 0.78%   |
| KIOXIA NVMe SSD                                                                | 1         | 0.78%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.78%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 1         | 0.78%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 0.78%   |
| Intel SSD 660P Series                                                          | 1         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 59        | 50%     |
| NVMe | 46        | 38.98%  |
| RAID | 12        | 10.17%  |
| IDE  | 1         | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 60        | 70.59%  |
| AMD    | 25        | 29.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 4         | 4.71%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 3         | 3.53%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 3.53%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 3.53%   |
| Intel Pentium CPU B960 @ 2.20GHz        | 2         | 2.35%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 2         | 2.35%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 2.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 2.35%   |
| Intel Core i3-4030U CPU @ 1.90GHz       | 2         | 2.35%   |
| Intel 12th Gen Core i7-12700H           | 2         | 2.35%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz | 2         | 2.35%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 2.35%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 1.18%   |
| Intel Core i7-9850H CPU @ 2.60GHz       | 1         | 1.18%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.18%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.18%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 1         | 1.18%   |
| Intel Core i7-7567U CPU @ 3.50GHz       | 1         | 1.18%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 1.18%   |
| Intel Core i7-6920HQ CPU @ 2.90GHz      | 1         | 1.18%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 1.18%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.18%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 1.18%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz      | 1         | 1.18%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 1.18%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz      | 1         | 1.18%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 1.18%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 1.18%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 1.18%   |
| Intel Core i7-3517U CPU @ 1.90GHz       | 1         | 1.18%   |
| Intel Core i7-2720QM CPU @ 2.20GHz      | 1         | 1.18%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 1         | 1.18%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 1.18%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 1         | 1.18%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 1         | 1.18%   |
| Intel Core i5-2557M CPU @ 1.70GHz       | 1         | 1.18%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 1         | 1.18%   |
| Intel Core i5 CPU M 480 @ 2.67GHz       | 1         | 1.18%   |
| Intel Core i3-7020U CPU @ 2.30GHz       | 1         | 1.18%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 1.18%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 27        | 31.76%  |
| Intel Core i5        | 11        | 12.94%  |
| AMD Ryzen 7          | 11        | 12.94%  |
| AMD Ryzen 5          | 9         | 10.59%  |
| Other                | 8         | 9.41%   |
| Intel Core i3        | 5         | 5.88%   |
| Intel Pentium        | 3         | 3.53%   |
| Intel Celeron        | 3         | 3.53%   |
| Intel Core 2 Duo     | 2         | 2.35%   |
| AMD Ryzen 9          | 2         | 2.35%   |
| Intel Core 2 Extreme | 1         | 1.18%   |
| Intel Atom           | 1         | 1.18%   |
| AMD E                | 1         | 1.18%   |
| AMD A6               | 1         | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 33        | 38.82%  |
| 2      | 27        | 31.76%  |
| 8      | 14        | 16.47%  |
| 6      | 9         | 10.59%  |
| 14     | 2         | 2.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 85        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 74        | 87.06%  |
| 1      | 11        | 12.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 85        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x0a50000c | 7         | 8.14%   |
| 0x906e9    | 5         | 5.81%   |
| 0x40651    | 5         | 5.81%   |
| 0x306a9    | 5         | 5.81%   |
| 0x506e3    | 4         | 4.65%   |
| 0x306c3    | 4         | 4.65%   |
| 0x206a7    | 4         | 4.65%   |
| Unknown    | 4         | 4.65%   |
| 0xa0652    | 3         | 3.49%   |
| 0x906ea    | 3         | 3.49%   |
| 0x806e9    | 3         | 3.49%   |
| 0x806c1    | 3         | 3.49%   |
| 0x08608103 | 3         | 3.49%   |
| 0x08600106 | 3         | 3.49%   |
| 0x08600104 | 3         | 3.49%   |
| 0x906a3    | 2         | 2.33%   |
| 0x806d1    | 2         | 2.33%   |
| 0x706e5    | 2         | 2.33%   |
| 0x30678    | 2         | 2.33%   |
| 0x10676    | 2         | 2.33%   |
| 0x08108109 | 2         | 2.33%   |
| 0xa0655    | 1         | 1.16%   |
| 0x906ed    | 1         | 1.16%   |
| 0x806ec    | 1         | 1.16%   |
| 0x806ea    | 1         | 1.16%   |
| 0x506c9    | 1         | 1.16%   |
| 0x306d4    | 1         | 1.16%   |
| 0x30661    | 1         | 1.16%   |
| 0x20655    | 1         | 1.16%   |
| 0x1067a    | 1         | 1.16%   |
| 0x0a50000d | 1         | 1.16%   |
| 0x08900201 | 1         | 1.16%   |
| 0x08108102 | 1         | 1.16%   |
| 0x08001138 | 1         | 1.16%   |
| 0x07030106 | 1         | 1.16%   |
| 0x0500010d | 1         | 1.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 14        | 16.47%  |
| Haswell          | 10        | 11.76%  |
| Zen 3            | 8         | 9.41%   |
| Zen 2            | 6         | 7.06%   |
| IvyBridge        | 5         | 5.88%   |
| Skylake          | 4         | 4.71%   |
| SandyBridge      | 4         | 4.71%   |
| Icelake          | 4         | 4.71%   |
| CometLake        | 4         | 4.71%   |
| Unknown          | 4         | 4.71%   |
| Zen+             | 3         | 3.53%   |
| TigerLake        | 3         | 3.53%   |
| Penryn           | 3         | 3.53%   |
| Zen              | 2         | 2.35%   |
| Silvermont       | 2         | 2.35%   |
| Alderlake Hybrid | 2         | 2.35%   |
| Westmere         | 1         | 1.18%   |
| Puma             | 1         | 1.18%   |
| Goldmont plus    | 1         | 1.18%   |
| Goldmont         | 1         | 1.18%   |
| Broadwell        | 1         | 1.18%   |
| Bonnell          | 1         | 1.18%   |
| Bobcat           | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 41.27%  |
| Nvidia | 42        | 33.33%  |
| AMD    | 32        | 25.4%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 7         | 5.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 5         | 3.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 5         | 3.85%   |
| AMD Renoir                                                                    | 5         | 3.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 3.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 4         | 3.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 4         | 3.08%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 3.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 3.08%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 3         | 2.31%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 3         | 2.31%   |
| Intel HD Graphics 630                                                         | 3         | 2.31%   |
| Intel HD Graphics 530                                                         | 3         | 2.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 2.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 2.31%   |
| AMD Lucienne                                                                  | 3         | 2.31%   |
| Nvidia TU117M [GeForce MX450]                                                 | 2         | 1.54%   |
| Nvidia TU117M                                                                 | 2         | 1.54%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 2         | 1.54%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 1.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 1.54%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 1.54%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.54%   |
| Intel HD Graphics 620                                                         | 2         | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 1.54%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 2         | 1.54%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 1.54%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]           | 2         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.77%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.77%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1         | 0.77%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                              | 1         | 0.77%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                        | 1         | 0.77%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 1         | 0.77%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                         | 1         | 0.77%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                  | 1         | 0.77%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                      | 1         | 0.77%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.77%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.77%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 1         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 26        | 30.59%  |
| 1 x Intel      | 20        | 23.53%  |
| 1 x AMD        | 14        | 16.47%  |
| AMD + Nvidia   | 9         | 10.59%  |
| 1 x Nvidia     | 7         | 8.24%   |
| Intel + AMD    | 5         | 5.88%   |
| 2 x AMD        | 4         | 4.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 52        | 60.47%  |
| Proprietary | 34        | 39.53%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 52.87%  |
| 0.01-0.5   | 17        | 19.54%  |
| 1.01-2.0   | 9         | 10.34%  |
| 0.51-1.0   | 6         | 6.9%    |
| 7.01-8.0   | 3         | 3.45%   |
| 5.01-6.0   | 3         | 3.45%   |
| 3.01-4.0   | 2         | 2.3%    |
| 8.01-16.0  | 1         | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 22        | 22.45%  |
| BOE                     | 12        | 12.24%  |
| Samsung Electronics     | 10        | 10.2%   |
| LG Display              | 10        | 10.2%   |
| Chimei Innolux          | 10        | 10.2%   |
| PANDA                   | 7         | 7.14%   |
| Apple                   | 5         | 5.1%    |
| Sharp                   | 4         | 4.08%   |
| InfoVision              | 2         | 2.04%   |
| Goldstar                | 2         | 2.04%   |
| Dell                    | 2         | 2.04%   |
| ___                     | 1         | 1.02%   |
| Vizio                   | 1         | 1.02%   |
| ViewSonic               | 1         | 1.02%   |
| Valve                   | 1         | 1.02%   |
| Unknown                 | 1         | 1.02%   |
| Sony                    | 1         | 1.02%   |
| MSI                     | 1         | 1.02%   |
| MLT                     | 1         | 1.02%   |
| Hewlett-Packard         | 1         | 1.02%   |
| Chi Mei Optoelectronics | 1         | 1.02%   |
| AOC                     | 1         | 1.02%   |
| Acer                    | 1         | 1.02%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 2.04%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 2.04%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 2.04%   |
| ___ LCD TV ___9000 1360x768                                           | 1         | 1.02%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                  | 1         | 1.02%   |
| ViewSonic VX2768-2KP VSC0A3B 2560x1440 597x336mm 27.0-inch            | 1         | 1.02%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 1.02%   |
| Unknown LCDTV 9000 1360x768 1600x900mm 72.3-inch                      | 1         | 1.02%   |
| Sony TV SNY1B02 1360x768                                              | 1         | 1.02%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 1         | 1.02%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 1.02%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 1.02%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 1.02%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 1.02%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch  | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SAM105F 1366x768 575x323mm 26.0-inch  | 1         | 1.02%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 1         | 1.02%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch               | 1         | 1.02%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.02%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 1.02%   |
| PANDA LCD Monitor NCP0029 1920x1080 344x194mm 15.5-inch               | 1         | 1.02%   |
| MSI G32CQ4 MSI3DB5 2560x1440 697x392mm 31.5-inch                      | 1         | 1.02%   |
| MLT MN101 MLT0236 1920x1080 530x280mm 23.6-inch                       | 1         | 1.02%   |
| LG Display LCD Monitor LGD40BA 1920x1080 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 1         | 1.02%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch           | 1         | 1.02%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch          | 1         | 1.02%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 47        | 51.09%  |
| 1366x768 (WXGA)    | 20        | 21.74%  |
| 2880x1800          | 4         | 4.35%   |
| 1440x900 (WXGA+)   | 4         | 4.35%   |
| 3840x2160 (4K)     | 3         | 3.26%   |
| 2560x1440 (QHD)    | 3         | 3.26%   |
| 1920x1200 (WUXGA)  | 2         | 2.17%   |
| 1360x768           | 2         | 2.17%   |
| 800x1280           | 1         | 1.09%   |
| 3200x1800 (QHD+)   | 1         | 1.09%   |
| 2560x1600          | 1         | 1.09%   |
| 2560x1080          | 1         | 1.09%   |
| 2520x1680          | 1         | 1.09%   |
| 1680x1050 (WSXGA+) | 1         | 1.09%   |
| 1280x800 (WXGA)    | 1         | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 52        | 53.06%  |
| 17      | 9         | 9.18%   |
| 13      | 8         | 8.16%   |
| 14      | 7         | 7.14%   |
| 31      | 3         | 3.06%   |
| 23      | 3         | 3.06%   |
| 72      | 2         | 2.04%   |
| 27      | 2         | 2.04%   |
| 16      | 2         | 2.04%   |
| 34      | 1         | 1.02%   |
| 26      | 1         | 1.02%   |
| 24      | 1         | 1.02%   |
| 21      | 1         | 1.02%   |
| 20      | 1         | 1.02%   |
| 18      | 1         | 1.02%   |
| 12      | 1         | 1.02%   |
| 10      | 1         | 1.02%   |
| 7       | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 66        | 67.35%  |
| 351-400     | 9         | 9.18%   |
| 501-600     | 7         | 7.14%   |
| 201-300     | 5         | 5.1%    |
| 601-700     | 3         | 3.06%   |
| 401-500     | 3         | 3.06%   |
| 1501-2000   | 2         | 2.04%   |
| 701-800     | 1         | 1.02%   |
| 1-100       | 1         | 1.02%   |
| Unknown     | 1         | 1.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 70        | 83.33%  |
| 16/10 | 11        | 13.1%   |
| 3/2   | 1         | 1.19%   |
| 21/9  | 1         | 1.19%   |
| 0.67  | 1         | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 52        | 53.06%  |
| 81-90          | 14        | 14.29%  |
| 121-130        | 7         | 7.14%   |
| 351-500        | 4         | 4.08%   |
| 201-250        | 4         | 4.08%   |
| More than 1000 | 2         | 2.04%   |
| 301-350        | 2         | 2.04%   |
| 251-300        | 2         | 2.04%   |
| 131-140        | 2         | 2.04%   |
| 111-120        | 2         | 2.04%   |
| 71-80          | 1         | 1.02%   |
| 61-70          | 1         | 1.02%   |
| 41-50          | 1         | 1.02%   |
| 1-40           | 1         | 1.02%   |
| 151-200        | 1         | 1.02%   |
| 141-150        | 1         | 1.02%   |
| Unknown        | 1         | 1.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 48        | 50%     |
| 101-120       | 22        | 22.92%  |
| 51-100        | 13        | 13.54%  |
| More than 240 | 6         | 6.25%   |
| 161-240       | 4         | 4.17%   |
| 1-50          | 2         | 2.08%   |
| Unknown       | 1         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 67        | 78.82%  |
| 2     | 13        | 15.29%  |
| 0     | 3         | 3.53%   |
| 3     | 2         | 2.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 48        | 35.29%  |
| Intel                 | 40        | 29.41%  |
| Qualcomm Atheros      | 18        | 13.24%  |
| Broadcom              | 10        | 7.35%   |
| MediaTek              | 6         | 4.41%   |
| ASIX Electronics      | 3         | 2.21%   |
| Xiaomi                | 2         | 1.47%   |
| Qualcomm              | 2         | 1.47%   |
| Broadcom Limited      | 2         | 1.47%   |
| Ralink                | 1         | 0.74%   |
| Nvidia                | 1         | 0.74%   |
| Google                | 1         | 0.74%   |
| ASUSTek Computer      | 1         | 0.74%   |
| Afatech               | 1         | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 22.01%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 4.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 3.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 3.14%   |
| Intel Wireless 7260                                               | 5         | 3.14%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 3.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 2.52%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 2.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.89%   |
| Intel Wireless 8260                                               | 3         | 1.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.89%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.26%   |
| Intel Wireless-AC 9260                                            | 2         | 1.26%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.26%   |
| Intel Wireless 7265                                               | 2         | 1.26%   |
| Intel WiFi Link 5100                                              | 2         | 1.26%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.26%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.26%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.26%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.26%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.26%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.63%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.63%   |
| Realtek Realtek Network controller                                | 1         | 0.63%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 39        | 45.35%  |
| Realtek Semiconductor | 16        | 18.6%   |
| Qualcomm Atheros      | 14        | 16.28%  |
| Broadcom              | 8         | 9.3%    |
| MediaTek              | 6         | 6.98%   |
| Ralink                | 1         | 1.16%   |
| Broadcom Limited      | 1         | 1.16%   |
| ASUSTek Computer      | 1         | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 7         | 8.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 5         | 5.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 5         | 5.81%   |
| Intel Wireless 7260                                           | 5         | 5.81%   |
| Intel Wi-Fi 6 AX200                                           | 5         | 5.81%   |
| Intel Comet Lake PCH CNVi WiFi                                | 4         | 4.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 3         | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 3         | 3.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 3.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 3.49%   |
| Intel Wireless 8260                                           | 3         | 3.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 3         | 3.49%   |
| Intel Wireless-AC 9260                                        | 2         | 2.33%   |
| Intel Wireless 8265 / 8275                                    | 2         | 2.33%   |
| Intel Wireless 7265                                           | 2         | 2.33%   |
| Intel WiFi Link 5100                                          | 2         | 2.33%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 2.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 2.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 2.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 2         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 2         | 2.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 1.16%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 1         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1         | 1.16%   |
| Realtek Realtek Network controller                            | 1         | 1.16%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 1         | 1.16%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter           | 1         | 1.16%   |
| Intel Wireless 3160                                           | 1         | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 1         | 1.16%   |
| Intel Centrino Wireless-N 135                                 | 1         | 1.16%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter   | 1         | 1.16%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 1         | 1.16%   |
| Broadcom BCM43228 802.11a/b/g/n                               | 1         | 1.16%   |
| Broadcom BCM43224 802.11a/b/g/n                               | 1         | 1.16%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller        | 1         | 1.16%   |
| ASUS 802.11ac WLAN Adapter                                    | 1         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 42        | 59.15%  |
| Intel                 | 10        | 14.08%  |
| Qualcomm Atheros      | 6         | 8.45%   |
| Broadcom              | 3         | 4.23%   |
| ASIX Electronics      | 3         | 4.23%   |
| Xiaomi                | 2         | 2.82%   |
| Qualcomm              | 2         | 2.82%   |
| Nvidia                | 1         | 1.41%   |
| Google                | 1         | 1.41%   |
| Broadcom Limited      | 1         | 1.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 48.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 5.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 2.78%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.78%   |
| Intel Ethernet Connection I217-V                                  | 2         | 2.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.39%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.39%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.39%   |
| Qualcomm Redmi Note 8                                             | 1         | 1.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.39%   |
| Qualcomm Android                                                  | 1         | 1.39%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.39%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.39%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.39%   |
| Google Pixel 7                                                    | 1         | 1.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.39%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.39%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 1.39%   |
| ASIX AX88772B                                                     | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 85        | 55.92%  |
| Ethernet | 66        | 43.42%  |
| Unknown  | 1         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 80.23%  |
| Ethernet | 17        | 19.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 62        | 72.94%  |
| 1     | 22        | 25.88%  |
| 0     | 1         | 1.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 73.26%  |
| Yes  | 23        | 26.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 50%     |
| Realtek Semiconductor           | 9         | 12.5%   |
| Qualcomm Atheros Communications | 5         | 6.94%   |
| Lite-On Technology              | 5         | 6.94%   |
| IMC Networks                    | 5         | 6.94%   |
| Foxconn / Hon Hai               | 5         | 6.94%   |
| Apple                           | 3         | 4.17%   |
| Toshiba                         | 1         | 1.39%   |
| Realtek                         | 1         | 1.39%   |
| Ralink                          | 1         | 1.39%   |
| Broadcom                        | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 16        | 22.22%  |
| Intel AX201 Bluetooth                          | 10        | 13.89%  |
| Realtek Bluetooth Radio                        | 9         | 12.5%   |
| Intel AX200 Bluetooth                          | 5         | 6.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 2         | 2.78%   |
| Lite-On Bluetooth Device                       | 2         | 2.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 2         | 2.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 2.78%   |
| IMC Networks Wireless_Device                   | 2         | 2.78%   |
| IMC Networks Bluetooth Radio                   | 2         | 2.78%   |
| Foxconn / Hon Hai Wireless_Device              | 2         | 2.78%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth  | 2         | 2.78%   |
| Apple Bluetooth Host Controller                | 2         | 2.78%   |
| Toshiba Askey Bluetooth Module                 | 1         | 1.39%   |
| Realtek Bluetooth Radio                        | 1         | 1.39%   |
| Ralink RT3290 Bluetooth                        | 1         | 1.39%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 1.39%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 1.39%   |
| Lite-On Wireless_Device                        | 1         | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 1.39%   |
| Lite-On Bluetooth Radio                        | 1         | 1.39%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 1.39%   |
| IMC Networks Bluetooth Device                  | 1         | 1.39%   |
| Foxconn / Hon Hai BT                           | 1         | 1.39%   |
| Broadcom HP Portable Bumble Bee                | 1         | 1.39%   |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 59        | 48.36%  |
| AMD                    | 31        | 25.41%  |
| Nvidia                 | 24        | 19.67%  |
| C-Media Electronics    | 3         | 2.46%   |
| SteelSeries ApS        | 1         | 0.82%   |
| Sony                   | 1         | 0.82%   |
| Logitech               | 1         | 0.82%   |
| Generalplus Technology | 1         | 0.82%   |
| Blue Microphones       | 1         | 0.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 21        | 13.73%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 9.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 4.58%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 3.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 3.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 3.27%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 3.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 3.27%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 2.61%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.61%   |
| Intel CM238 HD Audio Controller                                            | 4         | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.96%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.31%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.31%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 1.31%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.31%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.31%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.31%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.31%   |
| C-Media Electronics USB Audio Device                                       | 2         | 1.31%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 1.31%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.31%   |
| SteelSeries ApS SteelSeries Arctis 7X                                      | 1         | 0.65%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 0.65%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.65%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.65%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia Audio device                                                        | 1         | 0.65%   |
| Logitech PRO X Wireless Gaming Headset                                     | 1         | 0.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 40.74%  |
| SK hynix            | 7         | 25.93%  |
| Micron Technology   | 4         | 14.81%  |
| Unknown (ABCD)      | 1         | 3.7%    |
| Transcend           | 1         | 3.7%    |
| Nanya Technology    | 1         | 3.7%    |
| Kingston            | 1         | 3.7%    |
| Crucial             | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 7.14%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 7.14%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 7.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 3.57%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 3.57%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 3.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 3.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 3.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 3.57%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 3.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 3.57%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 3.57%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 3.57%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 3.57%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 3.57%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 3.57%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.57%   |
| Samsung RAM M4 70T5663RZ3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 3.57%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s           | 1         | 3.57%   |
| Nanya RAM M2S4G64CB8HG4N-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 3.57%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 1         | 3.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 3.57%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 3.57%   |
| Crucial RAM CB16GS2666.C8ET 16GB SODIMM DDR4 2667MT/s            | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 70%     |
| DDR3   | 3         | 15%     |
| LPDDR4 | 2         | 10%     |
| DDR2   | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 81.82%  |
| Row Of Chips | 4         | 18.18%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 15        | 65.22%  |
| 4096  | 3         | 13.04%  |
| 16384 | 2         | 8.7%    |
| 2048  | 2         | 8.7%    |
| 32768 | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 10        | 47.62%  |
| 2667  | 4         | 19.05%  |
| 1600  | 2         | 9.52%   |
| 4266  | 1         | 4.76%   |
| 2400  | 1         | 4.76%   |
| 2133  | 1         | 4.76%   |
| 1333  | 1         | 4.76%   |
| 975   | 1         | 4.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 14        | 18.18%  |
| IMC Networks                           | 12        | 15.58%  |
| Acer                                   | 7         | 9.09%   |
| Realtek Semiconductor                  | 6         | 7.79%   |
| Microdia                               | 5         | 6.49%   |
| Syntek                                 | 4         | 5.19%   |
| Sunplus Innovation Technology          | 4         | 5.19%   |
| Quanta                                 | 4         | 5.19%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.9%    |
| Apple                                  | 3         | 3.9%    |
| Suyin                                  | 2         | 2.6%    |
| Sonix Technology                       | 2         | 2.6%    |
| Logitech                               | 2         | 2.6%    |
| Tobii Technology AB                    | 1         | 1.3%    |
| SunplusIT                              | 1         | 1.3%    |
| Samsung Electronics                    | 1         | 1.3%    |
| Luxvisions Innotech Limited            | 1         | 1.3%    |
| Lite-On Technology                     | 1         | 1.3%    |
| Intel                                  | 1         | 1.3%    |
| Importek                               | 1         | 1.3%    |
| Goodong Industry                       | 1         | 1.3%    |
| DJKANA19IDX53W                         | 1         | 1.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 6         | 7.69%   |
| Syntek Integrated Camera                            | 3         | 3.85%   |
| Realtek USB Camera                                  | 3         | 3.85%   |
| Microdia Integrated_Webcam_HD                       | 3         | 3.85%   |
| Chicony Integrated Camera                           | 3         | 3.85%   |
| Acer Integrated Camera                              | 3         | 3.85%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.56%   |
| Sonix USB2.0 HD UVC WebCam                          | 2         | 2.56%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.56%   |
| IMC Networks Integrated Camera                      | 2         | 2.56%   |
| Chicony USB 2.0 Camera                              | 2         | 2.56%   |
| Acer Lenovo Integrated Webcam                       | 2         | 2.56%   |
| Acer HD Webcam                                      | 2         | 2.56%   |
| Tobii AB EyeChip                                    | 1         | 1.28%   |
| Syntek EasyCamera                                   | 1         | 1.28%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1.28%   |
| Suyin HP TrueVision Full HD                         | 1         | 1.28%   |
| SunplusIT MTD camera                                | 1         | 1.28%   |
| Sunplus HD WebCam                                   | 1         | 1.28%   |
| Sunplus Asus Webcam                                 | 1         | 1.28%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.28%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 1.28%   |
| Quanta VGA WebCam                                   | 1         | 1.28%   |
| Quanta USB2.0 VGA UVC WebCam                        | 1         | 1.28%   |
| Quanta USB HD Webcam                                | 1         | 1.28%   |
| Quanta HD Webcam                                    | 1         | 1.28%   |
| Microdia Lenovo EasyCamera                          | 1         | 1.28%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 1.28%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.28%   |
| Logitech QuickCam Communicate MP/S5500              | 1         | 1.28%   |
| Logitech HD Pro Webcam C920                         | 1         | 1.28%   |
| Lite-On HP HD Webcam                                | 1         | 1.28%   |
| Intel RealSense 3D Camera (Front F200)              | 1         | 1.28%   |
| Importek Laptop Integrated Webcam                   | 1         | 1.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 1.28%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 1.28%   |
| IMC Networks HP TrueVision HD Camera                | 1         | 1.28%   |
| IMC Networks HD Camera                              | 1         | 1.28%   |
| Goodong Industry USB2.0 HD UVC WebCam               | 1         | 1.28%   |
| DJKANA19IDX53W HP Wide Vision HD Camera             | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 33.33%  |
| Synaptics                  | 4         | 33.33%  |
| Shenzhen Goodix Technology | 3         | 25%     |
| Elan Microelectronics      | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 25%     |
| Shenzhen Goodix  Fingerprint Device                        | 3         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 8.33%   |
| Synaptics WBDI Device                                      | 1         | 8.33%   |
| Synaptics  WBDI                                            | 1         | 8.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 8.33%   |
| Elan ELAN:ARM-M4                                           | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 58        | 66.67%  |
| 1     | 22        | 25.29%  |
| 2     | 7         | 8.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 12        | 33.33%  |
| Graphics card         | 9         | 25%     |
| Multimedia controller | 8         | 22.22%  |
| Net/wireless          | 3         | 8.33%   |
| Bluetooth             | 2         | 5.56%   |
| Modem                 | 1         | 2.78%   |
| Chipcard              | 1         | 2.78%   |

