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

Total: 134

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro8,1               | [97f93aa235](https://linux-hardware.org/?probe=97f93aa235) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [7ef5d874e9](https://linux-hardware.org/?probe=7ef5d874e9) | Dec 28, 2022 |
| HP            | ENVY Notebook               | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| Dell          | G15 5510                    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [03da9468fc](https://linux-hardware.org/?probe=03da9468fc) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [2a1a679e03](https://linux-hardware.org/?probe=2a1a679e03) | Dec 18, 2022 |
| Apple         | MacBookPro11,1              | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| HP            | EliteBook 8460p             | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | [6f9a9428b6](https://linux-hardware.org/?probe=6f9a9428b6) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | [28c00eabe8](https://linux-hardware.org/?probe=28c00eabe8) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | EliteBook 8570p             | [52f0fae7e4](https://linux-hardware.org/?probe=52f0fae7e4) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [be0c42b073](https://linux-hardware.org/?probe=be0c42b073) | Dec 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| Dynabook      | PORTEGE X30L-K              | [75a8aa38fc](https://linux-hardware.org/?probe=75a8aa38fc) | Dec 08, 2022 |
| Lenovo        | Z50-70 20354                | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| HP            | Laptop 14-cm1xxx            | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| Lenovo        | V14-IIL 82C4                | [e23dd27dc9](https://linux-hardware.org/?probe=e23dd27dc9) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [5ce6793478](https://linux-hardware.org/?probe=5ce6793478) | Dec 06, 2022 |
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
| Nobara 36 | 104       | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Nobara | 104       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 6.0.10-201.fc36.x86_64        | 17        | 16.04%  |
| 5.19.14-201.fsync.fc36.x86_64 | 16        | 15.09%  |
| 5.19.9-201.fsync.fc36.x86_64  | 7         | 6.6%    |
| 5.19.7-204.fsync.fc36.x86_64  | 7         | 6.6%    |
| 6.0.7-201.fsync.fc36.x86_64   | 6         | 5.66%   |
| 6.0.5-201.fsync.fc36.x86_64   | 5         | 4.72%   |
| 5.19.12-201.fsync.fc36.x86_64 | 5         | 4.72%   |
| 5.19.8-201.fsync.fc36.x86_64  | 4         | 3.77%   |
| 5.19.16-201.fsync.fc36.x86_64 | 4         | 3.77%   |
| 5.19.11-201.fsync.fc36.x86_64 | 4         | 3.77%   |
| 6.0.9-202.fc36.x86_64         | 3         | 2.83%   |
| 6.0.9-201.fc36.x86_64         | 3         | 2.83%   |
| 6.0.14-201.fsync.fc36.x86_64  | 3         | 2.83%   |
| 5.18.16-201.fsync.fc36.x86_64 | 3         | 2.83%   |
| 5.18.13-201.fsync.fc36.x86_64 | 3         | 2.83%   |
| 6.0.8-201.fsync.fc36.x86_64   | 2         | 1.89%   |
| 5.19.4-201.fsync.fc36.x86_64  | 2         | 1.89%   |
| 5.19.15-202.fsync.fc36.x86_64 | 2         | 1.89%   |
| 5.18.17-201.fsync.fc36.x86_64 | 2         | 1.89%   |
| 6.0.7-202.fsync.fc36.x86_64   | 1         | 0.94%   |
| 6.0.2-xm1.0.fc36.x86_64       | 1         | 0.94%   |
| 6.0.13-201.fsync.fc36.x86_64  | 1         | 0.94%   |
| 5.19.7-203.fsync.fc36.x86_64  | 1         | 0.94%   |
| 5.19.13-202.fsync.fc36.x86_64 | 1         | 0.94%   |
| 5.19.10-201.fsync.fc36.x86_64 | 1         | 0.94%   |
| 5.18.19-201.fsync.fc36.x86_64 | 1         | 0.94%   |
| 5.18.18-201.fsync.fc36.x86_64 | 1         | 0.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.10  | 17        | 16.04%  |
| 5.19.14 | 16        | 15.09%  |
| 5.19.7  | 8         | 7.55%   |
| 6.0.7   | 7         | 6.6%    |
| 5.19.9  | 7         | 6.6%    |
| 6.0.9   | 6         | 5.66%   |
| 6.0.5   | 5         | 4.72%   |
| 5.19.12 | 5         | 4.72%   |
| 5.19.8  | 4         | 3.77%   |
| 5.19.16 | 4         | 3.77%   |
| 5.19.11 | 4         | 3.77%   |
| 6.0.14  | 3         | 2.83%   |
| 5.18.16 | 3         | 2.83%   |
| 5.18.13 | 3         | 2.83%   |
| 6.0.8   | 2         | 1.89%   |
| 5.19.4  | 2         | 1.89%   |
| 5.19.15 | 2         | 1.89%   |
| 5.18.17 | 2         | 1.89%   |
| 6.0.2   | 1         | 0.94%   |
| 6.0.13  | 1         | 0.94%   |
| 5.19.13 | 1         | 0.94%   |
| 5.19.10 | 1         | 0.94%   |
| 5.18.19 | 1         | 0.94%   |
| 5.18.18 | 1         | 0.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19    | 54        | 50.94%  |
| 6.0     | 42        | 39.62%  |
| 5.18    | 10        | 9.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 104       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 75        | 71.43%  |
| KDE5    | 26        | 24.76%  |
| Unknown | 4         | 3.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 83        | 79.05%  |
| X11     | 18        | 17.14%  |
| Unknown | 4         | 3.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 87        | 82.86%  |
| SDDM    | 10        | 9.52%   |
| GDM     | 8         | 7.62%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 56        | 53.33%  |
| pl_PL   | 5         | 4.76%   |
| es_ES   | 5         | 4.76%   |
| en_GB   | 4         | 3.81%   |
| pt_PT   | 3         | 2.86%   |
| it_IT   | 3         | 2.86%   |
| es_MX   | 3         | 2.86%   |
| es_AR   | 3         | 2.86%   |
| en_IN   | 3         | 2.86%   |
| en_NZ   | 2         | 1.9%    |
| en_CA   | 2         | 1.9%    |
| de_DE   | 2         | 1.9%    |
| Unknown | 2         | 1.9%    |
| sv_SE   | 1         | 0.95%   |
| ru_RU   | 1         | 0.95%   |
| pt_BR   | 1         | 0.95%   |
| hu_HU   | 1         | 0.95%   |
| hr_HR   | 1         | 0.95%   |
| fi_FI   | 1         | 0.95%   |
| es_CR   | 1         | 0.95%   |
| es_CO   | 1         | 0.95%   |
| es_CL   | 1         | 0.95%   |
| en_ZA   | 1         | 0.95%   |
| en_AU   | 1         | 0.95%   |
| de_AT   | 1         | 0.95%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 86        | 81.9%   |
| BIOS | 19        | 18.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 53        | 50.96%  |
| Ext4  | 50        | 48.08%  |
| Xfs   | 1         | 0.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 85        | 80.19%  |
| GPT     | 19        | 17.92%  |
| MBR     | 2         | 1.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 98        | 93.33%  |
| Yes       | 7         | 6.67%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 92        | 88.46%  |
| Yes       | 12        | 11.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 26        | 25%     |
| ASUSTek Computer    | 20        | 19.23%  |
| Hewlett-Packard     | 19        | 18.27%  |
| Dell                | 9         | 8.65%   |
| Apple               | 7         | 6.73%   |
| Acer                | 6         | 5.77%   |
| Toshiba             | 3         | 2.88%   |
| MSI                 | 2         | 1.92%   |
| Valve               | 1         | 0.96%   |
| Razer               | 1         | 0.96%   |
| Positivo            | 1         | 0.96%   |
| Notebook            | 1         | 0.96%   |
| HUAWEI              | 1         | 0.96%   |
| Gigabyte Technology | 1         | 0.96%   |
| Gateway             | 1         | 0.96%   |
| EVOO                | 1         | 0.96%   |
| Dynabook            | 1         | 0.96%   |
| Coradir             | 1         | 0.96%   |
| Casper              | 1         | 0.96%   |
| Alienware           | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo IdeaPad Y700-15ISK 80NV              | 2         | 1.92%   |
| Unknown                                     | 2         | 1.92%   |
| Valve Jupiter                               | 1         | 0.96%   |
| Toshiba TECRA A50-A                         | 1         | 0.96%   |
| Toshiba Satellite L850                      | 1         | 0.96%   |
| Toshiba Satellite L650                      | 1         | 0.96%   |
| Razer Blade                                 | 1         | 0.96%   |
| Positivo N1250                              | 1         | 0.96%   |
| Notebook P7xxDM2(-G)                        | 1         | 0.96%   |
| MSI Pulse GL76 12UEK                        | 1         | 0.96%   |
| MSI GE60 0NC/GE60 0ND                       | 1         | 0.96%   |
| Lenovo Z50-70 20354                         | 1         | 0.96%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 OD 82NK       | 1         | 0.96%   |
| Lenovo V330-15IKB 81AX                      | 1         | 0.96%   |
| Lenovo V14-IIL 82C4                         | 1         | 0.96%   |
| Lenovo ThinkPad X240 20AMA0LTAU             | 1         | 0.96%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK0047US | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWS0ME00  | 1         | 0.96%   |
| Lenovo ThinkPad P1 20MD0020US               | 1         | 0.96%   |
| Lenovo ThinkPad E14 Gen 3 20Y7CTO1WW        | 1         | 0.96%   |
| Lenovo ThinkBook 15 G3 ACL 21A4             | 1         | 0.96%   |
| Lenovo Legion S7 15ACH6 82K8                | 1         | 0.96%   |
| Lenovo Legion 5 Pro 16IAH7H 82RF            | 1         | 0.96%   |
| Lenovo Legion 5 15ARH05 82B5                | 1         | 0.96%   |
| Lenovo Legion 5 15ACH6H 82JU                | 1         | 0.96%   |
| Lenovo IdeaPadFlex 10 20324                 | 1         | 0.96%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2         | 1         | 0.96%   |
| Lenovo IdeaPad C340-14API 81N6              | 1         | 0.96%   |
| Lenovo IdeaPad 5 15ARE05 81YQ               | 1         | 0.96%   |
| Lenovo IdeaPad 330-15IKB 81DE               | 1         | 0.96%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 0.96%   |
| Lenovo IdeaPad 310-15IAP 80TT               | 1         | 0.96%   |
| Lenovo G580 20157                           | 1         | 0.96%   |
| Lenovo G580 20150                           | 1         | 0.96%   |
| Lenovo G50-30 80G0                          | 1         | 0.96%   |
| HUAWEI CREM-WXX9                            | 1         | 0.96%   |
| HP ZBook 17 G6                              | 1         | 0.96%   |
| HP ZBook 15 G2                              | 1         | 0.96%   |
| HP ProBook 445 14 inch G9 Notebook PC       | 1         | 0.96%   |
| HP Pavilion Laptop 14-ec0xxx                | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo IdeaPad       | 8         | 7.69%   |
| Lenovo ThinkPad      | 5         | 4.81%   |
| ASUS VivoBook        | 5         | 4.81%   |
| Lenovo Legion        | 4         | 3.85%   |
| HP EliteBook         | 4         | 3.85%   |
| ASUS ROG             | 4         | 3.85%   |
| Acer Aspire          | 4         | 3.85%   |
| Dell Precision       | 3         | 2.88%   |
| ASUS ASUS            | 3         | 2.88%   |
| Toshiba Satellite    | 2         | 1.92%   |
| Lenovo G580          | 2         | 1.92%   |
| HP ZBook             | 2         | 1.92%   |
| HP Pavilion          | 2         | 1.92%   |
| HP OMEN              | 2         | 1.92%   |
| HP Laptop            | 2         | 1.92%   |
| Dell G15             | 2         | 1.92%   |
| ASUS TUF             | 2         | 1.92%   |
| Apple MacBookPro8    | 2         | 1.92%   |
| Unknown              | 2         | 1.92%   |
| Valve Jupiter        | 1         | 0.96%   |
| Toshiba TECRA        | 1         | 0.96%   |
| Razer Blade          | 1         | 0.96%   |
| Positivo N1250       | 1         | 0.96%   |
| Notebook P7xxDM2(-G) | 1         | 0.96%   |
| MSI Pulse            | 1         | 0.96%   |
| MSI GE60             | 1         | 0.96%   |
| Lenovo Z50-70        | 1         | 0.96%   |
| Lenovo Yoga          | 1         | 0.96%   |
| Lenovo V330-15IKB    | 1         | 0.96%   |
| Lenovo V14-IIL       | 1         | 0.96%   |
| Lenovo ThinkBook     | 1         | 0.96%   |
| Lenovo IdeaPadFlex   | 1         | 0.96%   |
| Lenovo G50-30        | 1         | 0.96%   |
| HUAWEI CREM-WXX9     | 1         | 0.96%   |
| HP ProBook           | 1         | 0.96%   |
| HP ENVY              | 1         | 0.96%   |
| HP 240               | 1         | 0.96%   |
| HP 2000              | 1         | 0.96%   |
| HP 15                | 1         | 0.96%   |
| Gigabyte B450        | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 20        | 19.23%  |
| 2020 | 12        | 11.54%  |
| 2022 | 9         | 8.65%   |
| 2019 | 9         | 8.65%   |
| 2018 | 9         | 8.65%   |
| 2014 | 9         | 8.65%   |
| 2012 | 8         | 7.69%   |
| 2017 | 6         | 5.77%   |
| 2013 | 6         | 5.77%   |
| 2015 | 5         | 4.81%   |
| 2016 | 4         | 3.85%   |
| 2011 | 3         | 2.88%   |
| 2009 | 2         | 1.92%   |
| 2010 | 1         | 0.96%   |
| 2008 | 1         | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 104       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 104       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 104       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 28        | 26.92%  |
| 4.01-8.0   | 26        | 25%     |
| 16.01-24.0 | 19        | 18.27%  |
| 3.01-4.0   | 18        | 17.31%  |
| 32.01-64.0 | 10        | 9.62%   |
| 24.01-32.0 | 2         | 1.92%   |
| 1.01-2.0   | 1         | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 48        | 45.71%  |
| 2.01-3.0  | 27        | 25.71%  |
| 3.01-4.0  | 21        | 20%     |
| 8.01-16.0 | 8         | 7.62%   |
| 1.01-2.0  | 1         | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 75        | 72.12%  |
| 2      | 25        | 24.04%  |
| 3      | 4         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 78.85%  |
| Yes       | 22        | 21.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 77.88%  |
| No        | 23        | 22.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 99.04%  |
| No        | 1         | 0.96%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 86.54%  |
| No        | 14        | 13.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 32        | 30.77%  |
| Poland       | 7         | 6.73%   |
| India        | 5         | 4.81%   |
| Germany      | 4         | 3.85%   |
| Spain        | 3         | 2.88%   |
| Portugal     | 3         | 2.88%   |
| Mexico       | 3         | 2.88%   |
| Italy        | 3         | 2.88%   |
| Chile        | 3         | 2.88%   |
| Argentina    | 3         | 2.88%   |
| Vietnam      | 2         | 1.92%   |
| UK           | 2         | 1.92%   |
| Philippines  | 2         | 1.92%   |
| New Zealand  | 2         | 1.92%   |
| Egypt        | 2         | 1.92%   |
| Croatia      | 2         | 1.92%   |
| Colombia     | 2         | 1.92%   |
| Canada       | 2         | 1.92%   |
| Brazil       | 2         | 1.92%   |
| Austria      | 2         | 1.92%   |
| Taiwan       | 1         | 0.96%   |
| Sweden       | 1         | 0.96%   |
| South Africa | 1         | 0.96%   |
| Serbia       | 1         | 0.96%   |
| Russia       | 1         | 0.96%   |
| Romania      | 1         | 0.96%   |
| Panama       | 1         | 0.96%   |
| Pakistan     | 1         | 0.96%   |
| Morocco      | 1         | 0.96%   |
| Kenya        | 1         | 0.96%   |
| Indonesia    | 1         | 0.96%   |
| Hungary      | 1         | 0.96%   |
| Finland      | 1         | 0.96%   |
| Czechia      | 1         | 0.96%   |
| Cyprus       | 1         | 0.96%   |
| Costa Rica   | 1         | 0.96%   |
| Belgium      | 1         | 0.96%   |
| Australia    | 1         | 0.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Wasilla           | 2         | 1.87%   |
| Warsaw            | 2         | 1.87%   |
| Schmalkalden      | 2         | 1.87%   |
| Poznan            | 2         | 1.87%   |
| Panama City       | 2         | 1.87%   |
| Ochsenfurt        | 2         | 1.87%   |
| Guadalajara       | 2         | 1.87%   |
| Auckland          | 2         | 1.87%   |
| Zamora            | 1         | 0.93%   |
| Zadar             | 1         | 0.93%   |
| Wesley Chapel     | 1         | 0.93%   |
| Wayne             | 1         | 0.93%   |
| Wabrzezno         | 1         | 0.93%   |
| Villarrica        | 1         | 0.93%   |
| Villa Nueva       | 1         | 0.93%   |
| Vienna            | 1         | 0.93%   |
| Veszprém         | 1         | 0.93%   |
| Varaždin         | 1         | 0.93%   |
| Vagos             | 1         | 0.93%   |
| Tulsa             | 1         | 0.93%   |
| Tomah             | 1         | 0.93%   |
| Tenna             | 1         | 0.93%   |
| Temuco            | 1         | 0.93%   |
| Tampa             | 1         | 0.93%   |
| Sunnyvale         | 1         | 0.93%   |
| Slawa             | 1         | 0.93%   |
| Silves            | 1         | 0.93%   |
| Schenectady       | 1         | 0.93%   |
| San José         | 1         | 0.93%   |
| San Antonio Oeste | 1         | 0.93%   |
| San Antonio       | 1         | 0.93%   |
| Saltsjoebaden     | 1         | 0.93%   |
| Salem             | 1         | 0.93%   |
| Salamanca         | 1         | 0.93%   |
| Saint-Jerome      | 1         | 0.93%   |
| Rozsicka          | 1         | 0.93%   |
| Rome              | 1         | 0.93%   |
| Ranua             | 1         | 0.93%   |
| Ramos Mejia       | 1         | 0.93%   |
| Quezon City       | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 28        | 33     | 21.05%  |
| WDC                          | 11        | 12     | 8.27%   |
| Toshiba                      | 11        | 11     | 8.27%   |
| Seagate                      | 10        | 10     | 7.52%   |
| Kingston                     | 8         | 8      | 6.02%   |
| Intel                        | 8         | 8      | 6.02%   |
| SK hynix                     | 7         | 7      | 5.26%   |
| SanDisk                      | 6         | 6      | 4.51%   |
| Micron Technology            | 4         | 4      | 3.01%   |
| Hitachi                      | 4         | 5      | 3.01%   |
| Crucial                      | 4         | 4      | 3.01%   |
| China                        | 4         | 4      | 3.01%   |
| Phison Electronics           | 3         | 3      | 2.26%   |
| Micron/Crucial Technology    | 3         | 3      | 2.26%   |
| HGST                         | 3         | 3      | 2.26%   |
| Apple                        | 3         | 4      | 2.26%   |
| LITEON                       | 2         | 2      | 1.5%    |
| KIOXIA                       | 2         | 2      | 1.5%    |
| HS-SSD-C100                  | 2         | 2      | 1.5%    |
| Unknown                      | 2         | 2      | 1.5%    |
| Unknown                      | 1         | 1      | 0.75%   |
| Solid State Storage          | 1         | 1      | 0.75%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.75%   |
| Ramsta                       | 1         | 1      | 0.75%   |
| HGST HTS                     | 1         | 1      | 0.75%   |
| Fujitsu                      | 1         | 1      | 0.75%   |
| ADATA Technology             | 1         | 1      | 0.75%   |
| A-DATA Technology            | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 5         | 3.62%   |
| Sandisk WD Blue SN550 NVMe SSD 500GB                | 3         | 2.17%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 1.45%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 1.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1.45%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 2         | 1.45%   |
| Samsung SSD 980 1TB                                 | 2         | 1.45%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 1.45%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 2         | 1.45%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 2         | 1.45%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB               | 2         | 1.45%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1.45%   |
| Kingston NVMe SSD Drive 512GB                       | 2         | 1.45%   |
| Intel SSDPEKNU512GZ 512GB                           | 2         | 1.45%   |
| Intel SSD 660P Series 1024GB                        | 2         | 1.45%   |
| HS-SSD-C100 120G                                    | 2         | 1.45%   |
| Hitachi HTS547575A9E384 752GB                       | 2         | 1.45%   |
| China SATA SSD 120GB                                | 2         | 1.45%   |
| Unknown                                             | 2         | 1.45%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1         | 0.72%   |
| WDC WDS100T2B0C-00PXH0 1TB                          | 1         | 0.72%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 0.72%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 1         | 0.72%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1         | 0.72%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 0.72%   |
| WDC WD10JPVT-22A1YT0 1TB                            | 1         | 0.72%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 0.72%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB                | 1         | 0.72%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 1         | 0.72%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB                | 1         | 0.72%   |
| Unknown SD/MMC/MS PRO 64GB                          | 1         | 0.72%   |
| Toshiba XG6 NVMe SSD Controller 256GB               | 1         | 0.72%   |
| Toshiba TR200 240GB SSD                             | 1         | 0.72%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.72%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 0.72%   |
| Toshiba MK7559GSXF 752GB                            | 1         | 0.72%   |
| Toshiba MK3265GSXN 320GB                            | 1         | 0.72%   |
| Toshiba KXG5AZNV512G 512GB                          | 1         | 0.72%   |
| Solid State Storage SSSTC CL1-8D256-HP 256GB        | 1         | 0.72%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB           | 1         | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 10        | 10     | 29.41%  |
| Toshiba  | 8         | 8      | 23.53%  |
| WDC      | 6         | 7      | 17.65%  |
| Hitachi  | 4         | 5      | 11.76%  |
| HGST     | 3         | 3      | 8.82%   |
| Unknown  | 1         | 1      | 2.94%   |
| HGST HTS | 1         | 1      | 2.94%   |
| Fujitsu  | 1         | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 28.13%  |
| Crucial             | 4         | 4      | 12.5%   |
| China               | 4         | 4      | 12.5%   |
| Kingston            | 3         | 3      | 9.38%   |
| LITEON              | 2         | 2      | 6.25%   |
| Intel               | 2         | 2      | 6.25%   |
| Apple               | 2         | 2      | 6.25%   |
| Toshiba             | 1         | 1      | 3.13%   |
| SK hynix            | 1         | 1      | 3.13%   |
| SanDisk             | 1         | 1      | 3.13%   |
| Ramsta              | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 54        | 69     | 43.9%   |
| HDD     | 33        | 36     | 26.83%  |
| SSD     | 32        | 32     | 26.02%  |
| Unknown | 4         | 4      | 3.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 66     | 49.58%  |
| NVMe | 54        | 69     | 45.38%  |
| SAS  | 6         | 6      | 5.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 41        | 43     | 63.08%  |
| 0.51-1.0   | 21        | 22     | 32.31%  |
| 3.01-4.0   | 2         | 2      | 3.08%   |
| 1.01-2.0   | 1         | 1      | 1.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 29.25%  |
| 501-1000       | 28        | 26.42%  |
| 251-500        | 27        | 25.47%  |
| 51-100         | 5         | 4.72%   |
| Unknown        | 5         | 4.72%   |
| 1001-2000      | 4         | 3.77%   |
| 21-50          | 3         | 2.83%   |
| More than 3000 | 2         | 1.89%   |
| 2001-3000      | 1         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 32        | 30.19%  |
| 21-50     | 29        | 27.36%  |
| 101-250   | 14        | 13.21%  |
| 51-100    | 10        | 9.43%   |
| 251-500   | 9         | 8.49%   |
| 501-1000  | 5         | 4.72%   |
| Unknown   | 5         | 4.72%   |
| 2001-3000 | 1         | 0.94%   |
| 1001-2000 | 1         | 0.94%   |

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
| Detected | 87        | 110    | 79.09%  |
| Works    | 21        | 29     | 19.09%  |
| Malfunc  | 2         | 2      | 1.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 64        | 44.76%  |
| Samsung Electronics            | 21        | 14.69%  |
| AMD                            | 19        | 13.29%  |
| SanDisk                        | 9         | 6.29%   |
| SK hynix                       | 6         | 4.2%    |
| Kingston Technology Company    | 5         | 3.5%    |
| Phison Electronics             | 3         | 2.1%    |
| Micron/Crucial Technology      | 3         | 2.1%    |
| Micron Technology              | 3         | 2.1%    |
| Toshiba America Info Systems   | 2         | 1.4%    |
| KIOXIA                         | 2         | 1.4%    |
| Solid State Storage Technology | 1         | 0.7%    |
| Shenzhen Longsys Electronics   | 1         | 0.7%    |
| Nvidia                         | 1         | 0.7%    |
| Marvell Technology Group       | 1         | 0.7%    |
| Apple                          | 1         | 0.7%    |
| ADATA Technology               | 1         | 0.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 12.67%  |
| Samsung NVMe SSD Controller 980                                                | 10        | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 5.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 5.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 4.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 3.33%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 2.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 2.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 2%      |
| Micron Non-Volatile memory controller                                          | 3         | 2%      |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2%      |
| Intel SSD 660P Series                                                          | 3         | 2%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.33%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.33%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.33%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 1.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.33%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.33%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.33%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.67%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.67%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.67%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.67%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                    | 1         | 0.67%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.67%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.67%   |
| Samsung Apple PCIe SSD                                                         | 1         | 0.67%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.67%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.67%   |
| Micron/Crucial Non-Volatile memory controller                                  | 1         | 0.67%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.67%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 0.67%   |
| KIOXIA NVMe SSD                                                                | 1         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 70        | 51.09%  |
| NVMe | 54        | 39.42%  |
| RAID | 12        | 8.76%   |
| IDE  | 1         | 0.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 73        | 70.19%  |
| AMD    | 31        | 29.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 4         | 3.85%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 3         | 2.88%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 2.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 2.88%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 2.88%   |
| Intel Pentium CPU B960 @ 2.20GHz        | 2         | 1.92%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 2         | 1.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 1.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 1.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 1.92%   |
| Intel Core i3-4030U CPU @ 1.90GHz       | 2         | 1.92%   |
| Intel 12th Gen Core i7-12700H           | 2         | 1.92%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz | 2         | 1.92%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 0.96%   |
| Intel Core i7-9850H CPU @ 2.60GHz       | 1         | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 0.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.96%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 1         | 0.96%   |
| Intel Core i7-7567U CPU @ 3.50GHz       | 1         | 0.96%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 0.96%   |
| Intel Core i7-6920HQ CPU @ 2.90GHz      | 1         | 0.96%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 0.96%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 0.96%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 0.96%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz      | 1         | 0.96%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 0.96%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz      | 1         | 0.96%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 0.96%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 0.96%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 0.96%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 0.96%   |
| Intel Core i7-3517U CPU @ 1.90GHz       | 1         | 0.96%   |
| Intel Core i7-2720QM CPU @ 2.20GHz      | 1         | 0.96%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 1         | 0.96%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 0.96%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 1         | 0.96%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 0.96%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 1         | 0.96%   |
| Intel Core i5-4278U CPU @ 2.60GHz       | 1         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 32        | 30.77%  |
| Intel Core i5        | 15        | 14.42%  |
| AMD Ryzen 7          | 13        | 12.5%   |
| Other                | 11        | 10.58%  |
| AMD Ryzen 5          | 10        | 9.62%   |
| Intel Core i3        | 5         | 4.81%   |
| Intel Celeron        | 4         | 3.85%   |
| Intel Pentium        | 3         | 2.88%   |
| Intel Core 2 Duo     | 2         | 1.92%   |
| AMD Ryzen 9          | 2         | 1.92%   |
| Intel Core 2 Extreme | 1         | 0.96%   |
| Intel Atom           | 1         | 0.96%   |
| AMD Ryzen 3          | 1         | 0.96%   |
| AMD FX               | 1         | 0.96%   |
| AMD E                | 1         | 0.96%   |
| AMD A6               | 1         | 0.96%   |
| AMD A10              | 1         | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 36        | 34.62%  |
| 4      | 35        | 33.65%  |
| 8      | 17        | 16.35%  |
| 6      | 12        | 11.54%  |
| 14     | 2         | 1.92%   |
| 12     | 1         | 0.96%   |
| 10     | 1         | 0.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 104       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 92        | 88.46%  |
| 1      | 12        | 11.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 104       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x0a50000c | 8         | 7.62%   |
| 0x40651    | 7         | 6.67%   |
| 0xa0652    | 6         | 5.71%   |
| 0x306a9    | 6         | 5.71%   |
| 0x206a7    | 6         | 5.71%   |
| 0x906e9    | 5         | 4.76%   |
| Unknown    | 5         | 4.76%   |
| 0x906a3    | 4         | 3.81%   |
| 0x806c1    | 4         | 3.81%   |
| 0x506e3    | 4         | 3.81%   |
| 0x306c3    | 4         | 3.81%   |
| 0x08608103 | 4         | 3.81%   |
| 0x906ea    | 3         | 2.86%   |
| 0x806e9    | 3         | 2.86%   |
| 0x08600106 | 3         | 2.86%   |
| 0x08600104 | 3         | 2.86%   |
| 0x08108109 | 3         | 2.86%   |
| 0x806ea    | 2         | 1.9%    |
| 0x806d1    | 2         | 1.9%    |
| 0x706e5    | 2         | 1.9%    |
| 0x30678    | 2         | 1.9%    |
| 0x10676    | 2         | 1.9%    |
| 0xa0655    | 1         | 0.95%   |
| 0x906ed    | 1         | 0.95%   |
| 0x806ec    | 1         | 0.95%   |
| 0x506c9    | 1         | 0.95%   |
| 0x306d4    | 1         | 0.95%   |
| 0x30661    | 1         | 0.95%   |
| 0x20655    | 1         | 0.95%   |
| 0x1067a    | 1         | 0.95%   |
| 0x0a50000d | 1         | 0.95%   |
| 0x0a404101 | 1         | 0.95%   |
| 0x08900201 | 1         | 0.95%   |
| 0x08108102 | 1         | 0.95%   |
| 0x08001138 | 1         | 0.95%   |
| 0x07030106 | 1         | 0.95%   |
| 0x06006110 | 1         | 0.95%   |
| 0x06003106 | 1         | 0.95%   |
| 0x0500010d | 1         | 0.95%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 15        | 14.42%  |
| Haswell          | 13        | 12.5%   |
| Zen 3            | 9         | 8.65%   |
| CometLake        | 7         | 6.73%   |
| Zen 2            | 6         | 5.77%   |
| SandyBridge      | 6         | 5.77%   |
| IvyBridge        | 6         | 5.77%   |
| Unknown          | 6         | 5.77%   |
| Zen+             | 4         | 3.85%   |
| TigerLake        | 4         | 3.85%   |
| Skylake          | 4         | 3.85%   |
| Icelake          | 4         | 3.85%   |
| Alderlake Hybrid | 4         | 3.85%   |
| Penryn           | 3         | 2.88%   |
| Zen              | 2         | 1.92%   |
| Silvermont       | 2         | 1.92%   |
| Westmere         | 1         | 0.96%   |
| Steamroller      | 1         | 0.96%   |
| Puma             | 1         | 0.96%   |
| Goldmont plus    | 1         | 0.96%   |
| Goldmont         | 1         | 0.96%   |
| Excavator        | 1         | 0.96%   |
| Broadwell        | 1         | 0.96%   |
| Bonnell          | 1         | 0.96%   |
| Bobcat           | 1         | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 63        | 41.18%  |
| Nvidia | 49        | 32.03%  |
| AMD    | 41        | 26.8%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 8         | 5.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 5.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 6         | 3.8%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 5         | 3.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 5         | 3.16%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 3.16%   |
| AMD Renoir                                                                    | 5         | 3.16%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 4         | 2.53%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 2.53%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 4         | 2.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 4         | 2.53%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 2.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 2.53%   |
| AMD Lucienne                                                                  | 4         | 2.53%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 3         | 1.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 1.9%    |
| Intel HD Graphics 630                                                         | 3         | 1.9%    |
| Intel HD Graphics 530                                                         | 3         | 1.9%    |
| Intel Alder Lake-P Integrated Graphics Controller                             | 3         | 1.9%    |
| Nvidia TU117M [GeForce MX450]                                                 | 2         | 1.27%   |
| Nvidia TU117M                                                                 | 2         | 1.27%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 1.27%   |
| Intel UHD Graphics 620                                                        | 2         | 1.27%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 1.27%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.27%   |
| Intel HD Graphics 620                                                         | 2         | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 1.27%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 1.27%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]           | 2         | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.63%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.63%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1         | 0.63%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                              | 1         | 0.63%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                        | 1         | 0.63%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 1         | 0.63%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                         | 1         | 0.63%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                  | 1         | 0.63%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                      | 1         | 0.63%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.63%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 31        | 29.81%  |
| 1 x Intel      | 25        | 24.04%  |
| 1 x AMD        | 19        | 18.27%  |
| AMD + Nvidia   | 11        | 10.58%  |
| 1 x Nvidia     | 7         | 6.73%   |
| Intel + AMD    | 6         | 5.77%   |
| 2 x AMD        | 5         | 4.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 66        | 62.86%  |
| Proprietary | 39        | 37.14%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 52.83%  |
| 0.01-0.5   | 20        | 18.87%  |
| 1.01-2.0   | 11        | 10.38%  |
| 0.51-1.0   | 9         | 8.49%   |
| 7.01-8.0   | 4         | 3.77%   |
| 5.01-6.0   | 3         | 2.83%   |
| 3.01-4.0   | 2         | 1.89%   |
| 8.01-16.0  | 1         | 0.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 23.33%  |
| LG Display              | 14        | 11.67%  |
| BOE                     | 14        | 11.67%  |
| Chimei Innolux          | 13        | 10.83%  |
| Samsung Electronics     | 11        | 9.17%   |
| PANDA                   | 7         | 5.83%   |
| Apple                   | 6         | 5%      |
| Sharp                   | 5         | 4.17%   |
| ViewSonic               | 2         | 1.67%   |
| MSI                     | 2         | 1.67%   |
| InfoVision              | 2         | 1.67%   |
| Goldstar                | 2         | 1.67%   |
| Dell                    | 2         | 1.67%   |
| Acer                    | 2         | 1.67%   |
| ___                     | 1         | 0.83%   |
| Vizio                   | 1         | 0.83%   |
| Valve                   | 1         | 0.83%   |
| Unknown                 | 1         | 0.83%   |
| Sony                    | 1         | 0.83%   |
| MLT                     | 1         | 0.83%   |
| Hewlett-Packard         | 1         | 0.83%   |
| CSO                     | 1         | 0.83%   |
| Chi Mei Optoelectronics | 1         | 0.83%   |
| AOC                     | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 1.67%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 2         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch       | 2         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch        | 2         | 1.67%   |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                  | 2         | 1.67%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch          | 2         | 1.67%   |
| ___ LCDTV16 ___9000 1360x768                                           | 1         | 0.83%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1         | 0.83%   |
| ViewSonic VX2768-2KP VSC0A3B 2560x1440 597x336mm 27.0-inch             | 1         | 0.83%   |
| ViewSonic VA2446 Series VSC732E 1920x1080 521x293mm 23.5-inch          | 1         | 0.83%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 1         | 0.83%   |
| Unknown LCDTV 9000 1360x768 1600x900mm 72.3-inch                       | 1         | 0.83%   |
| Sony TV SNY1B02 1360x768                                               | 1         | 0.83%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                | 1         | 0.83%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch                | 1         | 0.83%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.83%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                | 1         | 0.83%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.83%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch      | 1         | 0.83%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM105F 1366x768 575x323mm 26.0-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 1         | 0.83%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch                | 1         | 0.83%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch                | 1         | 0.83%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                | 1         | 0.83%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 0.83%   |
| PANDA LCD Monitor NCP0029 1920x1080 344x194mm 15.5-inch                | 1         | 0.83%   |
| MSI G32CQ4 MSI3DB5 2560x1440 697x392mm 31.5-inch                       | 1         | 0.83%   |
| MSI G27C4 MSI3CA9 1920x1080 598x336mm 27.0-inch                        | 1         | 0.83%   |
| MLT MN101 MLT0236 1920x1080 530x280mm 23.6-inch                        | 1         | 0.83%   |
| LG Display LCD Monitor LGD40BA 1920x1080 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD06F0 1920x1080 309x174mm 14.0-inch           | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 50.45%  |
| 1366x768 (WXGA)    | 25        | 22.52%  |
| 3840x2160 (4K)     | 4         | 3.6%    |
| 2880x1800          | 4         | 3.6%    |
| 1440x900 (WXGA+)   | 4         | 3.6%    |
| 2560x1440 (QHD)    | 3         | 2.7%    |
| 1920x1200 (WUXGA)  | 3         | 2.7%    |
| 2560x1600          | 2         | 1.8%    |
| 1360x768           | 2         | 1.8%    |
| 1280x800 (WXGA)    | 2         | 1.8%    |
| 800x1280           | 1         | 0.9%    |
| 3200x1800 (QHD+)   | 1         | 0.9%    |
| 2560x1080          | 1         | 0.9%    |
| 2520x1680          | 1         | 0.9%    |
| 1680x1050 (WSXGA+) | 1         | 0.9%    |
| 1600x900 (HD+)     | 1         | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 63        | 52.5%   |
| 13      | 11        | 9.17%   |
| 14      | 10        | 8.33%   |
| 17      | 9         | 7.5%    |
| 23      | 4         | 3.33%   |
| 31      | 3         | 2.5%    |
| 27      | 3         | 2.5%    |
| 16      | 3         | 2.5%    |
| 72      | 2         | 1.67%   |
| 24      | 2         | 1.67%   |
| 48      | 1         | 0.83%   |
| 34      | 1         | 0.83%   |
| 26      | 1         | 0.83%   |
| 21      | 1         | 0.83%   |
| 20      | 1         | 0.83%   |
| 18      | 1         | 0.83%   |
| 12      | 1         | 0.83%   |
| 10      | 1         | 0.83%   |
| 7       | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 82        | 68.91%  |
| 501-600     | 9         | 7.56%   |
| 351-400     | 9         | 7.56%   |
| 201-300     | 7         | 5.88%   |
| 601-700     | 3         | 2.52%   |
| 401-500     | 3         | 2.52%   |
| 1501-2000   | 2         | 1.68%   |
| 701-800     | 1         | 0.84%   |
| 1001-1500   | 1         | 0.84%   |
| 1-100       | 1         | 0.84%   |
| Unknown     | 1         | 0.84%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 86        | 83.5%   |
| 16/10 | 14        | 13.59%  |
| 3/2   | 1         | 0.97%   |
| 21/9  | 1         | 0.97%   |
| 0.67  | 1         | 0.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 63        | 52.94%  |
| 81-90          | 19        | 15.97%  |
| 121-130        | 7         | 5.88%   |
| 201-250        | 5         | 4.2%    |
| 351-500        | 4         | 3.36%   |
| More than 1000 | 3         | 2.52%   |
| 301-350        | 3         | 2.52%   |
| 111-120        | 3         | 2.52%   |
| 71-80          | 2         | 1.68%   |
| 251-300        | 2         | 1.68%   |
| 131-140        | 2         | 1.68%   |
| 61-70          | 1         | 0.84%   |
| 41-50          | 1         | 0.84%   |
| 1-40           | 1         | 0.84%   |
| 151-200        | 1         | 0.84%   |
| 141-150        | 1         | 0.84%   |
| Unknown        | 1         | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 56        | 47.86%  |
| 101-120       | 27        | 23.08%  |
| 51-100        | 16        | 13.68%  |
| More than 240 | 7         | 5.98%   |
| 161-240       | 7         | 5.98%   |
| 1-50          | 3         | 2.56%   |
| Unknown       | 1         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 84        | 80.77%  |
| 2     | 14        | 13.46%  |
| 3     | 3         | 2.88%   |
| 0     | 3         | 2.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Realtek Semiconductor  | 58        | 35.15%  |
| Intel                  | 50        | 30.3%   |
| Qualcomm Atheros       | 19        | 11.52%  |
| Broadcom               | 14        | 8.48%   |
| MediaTek               | 7         | 4.24%   |
| Broadcom Limited       | 3         | 1.82%   |
| ASIX Electronics       | 3         | 1.82%   |
| Xiaomi                 | 2         | 1.21%   |
| Qualcomm               | 2         | 1.21%   |
| Samsung Electronics    | 1         | 0.61%   |
| Ralink                 | 1         | 0.61%   |
| Panasonic (Matsushita) | 1         | 0.61%   |
| Nvidia                 | 1         | 0.61%   |
| Google                 | 1         | 0.61%   |
| ASUSTek Computer       | 1         | 0.61%   |
| Afatech                | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 22.68%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 3.61%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 3.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 3.09%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 5         | 2.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.58%   |
| Intel Wireless 7260                                               | 5         | 2.58%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 2.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 2.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 2.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 2.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.55%   |
| Intel Wireless 8260                                               | 3         | 1.55%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.03%   |
| Intel Wireless-AC 9260                                            | 2         | 1.03%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.03%   |
| Intel Wireless 7265                                               | 2         | 1.03%   |
| Intel WiFi Link 5100                                              | 2         | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.03%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.03%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.03%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 1.03%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.03%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.52%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 48        | 45.71%  |
| Realtek Semiconductor  | 19        | 18.1%   |
| Qualcomm Atheros       | 15        | 14.29%  |
| Broadcom               | 11        | 10.48%  |
| MediaTek               | 7         | 6.67%   |
| Broadcom Limited       | 2         | 1.9%    |
| Ralink                 | 1         | 0.95%   |
| Panasonic (Matsushita) | 1         | 0.95%   |
| ASUSTek Computer       | 1         | 0.95%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 7         | 6.67%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 7         | 6.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 6         | 5.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 5         | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5         | 4.76%   |
| Intel Wireless 7260                                                  | 5         | 4.76%   |
| Intel Wi-Fi 6 AX200                                                  | 5         | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 4         | 3.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 4         | 3.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 3.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 2.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 3         | 2.86%   |
| Intel Wireless 8260                                                  | 3         | 2.86%   |
| Intel Wi-Fi 6 AX201                                                  | 3         | 2.86%   |
| Intel Wireless-AC 9260                                               | 2         | 1.9%    |
| Intel Wireless 8265 / 8275                                           | 2         | 1.9%    |
| Intel Wireless 7265                                                  | 2         | 1.9%    |
| Intel WiFi Link 5100                                                 | 2         | 1.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 1.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 1.9%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 2         | 1.9%    |
| Broadcom BCM4331 802.11a/b/g/n                                       | 2         | 1.9%    |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 1.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 2         | 1.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.95%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 0.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 0.95%   |
| Realtek Realtek Network controller                                   | 1         | 0.95%   |
| Realtek 802.11n WLAN Adapter                                         | 1         | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.95%   |
| Panasonic (Matsushita) DY-WL10 802.11abgn Adapter [Broadcom BCM4323] | 1         | 0.95%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                  | 1         | 0.95%   |
| Intel Wireless 3165                                                  | 1         | 0.95%   |
| Intel Wireless 3160                                                  | 1         | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 0.95%   |
| Intel Centrino Wireless-N 135                                        | 1         | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 1         | 0.95%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter           | 1         | 0.95%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 52        | 59.77%  |
| Intel                 | 13        | 14.94%  |
| Qualcomm Atheros      | 6         | 6.9%    |
| Broadcom              | 5         | 5.75%   |
| ASIX Electronics      | 3         | 3.45%   |
| Xiaomi                | 2         | 2.3%    |
| Qualcomm              | 2         | 2.3%    |
| Samsung Electronics   | 1         | 1.15%   |
| Nvidia                | 1         | 1.15%   |
| Google                | 1         | 1.15%   |
| Broadcom Limited      | 1         | 1.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 4.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.27%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 2.27%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.27%   |
| Intel Ethernet Connection I217-V                                  | 2         | 2.27%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.27%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.14%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.14%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.14%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.14%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.14%   |
| Qualcomm MegaFon M150-4                                           | 1         | 1.14%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.14%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.14%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.14%   |
| Qualcomm Android                                                  | 1         | 1.14%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.14%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.14%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.14%   |
| Google Pixel 6a                                                   | 1         | 1.14%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.14%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.14%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.14%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 1.14%   |
| ASIX AX88772B                                                     | 1         | 1.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 103       | 55.68%  |
| Ethernet | 81        | 43.78%  |
| Unknown  | 1         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 78.1%   |
| Ethernet | 23        | 21.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 75        | 72.12%  |
| 1     | 28        | 26.92%  |
| 0     | 1         | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 73.33%  |
| Yes  | 28        | 26.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 48.89%  |
| Realtek Semiconductor           | 12        | 13.33%  |
| Lite-On Technology              | 6         | 6.67%   |
| IMC Networks                    | 6         | 6.67%   |
| Foxconn / Hon Hai               | 6         | 6.67%   |
| Qualcomm Atheros Communications | 5         | 5.56%   |
| Apple                           | 5         | 5.56%   |
| Broadcom                        | 2         | 2.22%   |
| Toshiba                         | 1         | 1.11%   |
| Realtek                         | 1         | 1.11%   |
| Ralink                          | 1         | 1.11%   |
| Foxconn International           | 1         | 1.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 18        | 20%     |
| Intel AX201 Bluetooth                             | 14        | 15.56%  |
| Realtek Bluetooth Radio                           | 11        | 12.22%  |
| Intel AX200 Bluetooth                             | 5         | 5.56%   |
| Apple Bluetooth Host Controller                   | 4         | 4.44%   |
| IMC Networks Wireless_Device                      | 3         | 3.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 2         | 2.22%   |
| Lite-On Bluetooth Device                          | 2         | 2.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 2         | 2.22%   |
| Intel Bluetooth Device                            | 2         | 2.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 2         | 2.22%   |
| IMC Networks Bluetooth Radio                      | 2         | 2.22%   |
| Foxconn / Hon Hai Wireless_Device                 | 2         | 2.22%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth     | 2         | 2.22%   |
| Toshiba Askey Bluetooth Module                    | 1         | 1.11%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 1.11%   |
| Realtek Bluetooth Radio                           | 1         | 1.11%   |
| Ralink RT3290 Bluetooth                           | 1         | 1.11%   |
| Qualcomm Atheros  Bluetooth Device                | 1         | 1.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 1.11%   |
| Lite-On Wireless_Device                           | 1         | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 1.11%   |
| Lite-On Bluetooth Radio                           | 1         | 1.11%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 1.11%   |
| Intel Wireless-AC 3168 Bluetooth                  | 1         | 1.11%   |
| IMC Networks Bluetooth Device                     | 1         | 1.11%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.11%   |
| Foxconn / Hon Hai BT                              | 1         | 1.11%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth   | 1         | 1.11%   |
| Broadcom HP Portable SoftSailing                  | 1         | 1.11%   |
| Broadcom HP Portable Bumble Bee                   | 1         | 1.11%   |
| Apple Built-in Bluetooth 2.0+EDR HCI              | 1         | 1.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 72        | 47.68%  |
| AMD                    | 38        | 25.17%  |
| Nvidia                 | 30        | 19.87%  |
| C-Media Electronics    | 3         | 1.99%   |
| SteelSeries ApS        | 1         | 0.66%   |
| Sony                   | 1         | 0.66%   |
| Logitech               | 1         | 0.66%   |
| Hewlett-Packard        | 1         | 0.66%   |
| Generalplus Technology | 1         | 0.66%   |
| Corsair                | 1         | 0.66%   |
| Blue Microphones       | 1         | 0.66%   |
| ASUSTek Computer       | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 24        | 12.7%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15        | 7.94%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 4.23%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 4.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 4.23%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 3.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 3.17%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 2.65%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 2.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 2.12%   |
| Intel CM238 HD Audio Controller                                            | 4         | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.12%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.59%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.59%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 1.59%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.59%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.06%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 1.06%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.06%   |
| Nvidia Audio device                                                        | 2         | 1.06%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.06%   |
| C-Media Electronics USB Audio Device                                       | 2         | 1.06%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.06%   |
| SteelSeries ApS SteelSeries Arctis 7X                                      | 1         | 0.53%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 0.53%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.53%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.53%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.53%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.53%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.53%   |
| Logitech PRO X Wireless Gaming Headset                                     | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 41.94%  |
| SK hynix            | 7         | 22.58%  |
| Micron Technology   | 6         | 19.35%  |
| Unknown (ABCD)      | 1         | 3.23%   |
| Transcend           | 1         | 3.23%   |
| Nanya Technology    | 1         | 3.23%   |
| Kingston            | 1         | 3.23%   |
| Crucial             | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 9.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 6.25%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 6.25%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 3.13%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 3.13%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 3.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.13%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 3.13%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 3.13%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 3.13%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 3.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 3.13%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 3.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.13%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 3.13%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 3.13%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.13%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM 4800MT/s              | 1         | 3.13%   |
| Samsung RAM M4 70T5663RZ3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 3.13%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s           | 1         | 3.13%   |
| Nanya RAM M2S4G64CB8HG4N-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 3.13%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s               | 1         | 3.13%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 1         | 3.13%   |
| Micron RAM Module 2GB Row Of Chips 6400MT/s                      | 1         | 3.13%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 3.13%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 3.13%   |
| Crucial RAM CB16GS2666.C8ET 16GB SODIMM DDR4 2667MT/s            | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 15        | 65.22%  |
| DDR3    | 3         | 13.04%  |
| LPDDR4  | 2         | 8.7%    |
| DDR5    | 1         | 4.35%   |
| DDR2    | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 80%     |
| Row Of Chips | 5         | 20%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 16        | 61.54%  |
| 16384 | 3         | 11.54%  |
| 4096  | 3         | 11.54%  |
| 2048  | 3         | 11.54%  |
| 32768 | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 11        | 45.83%  |
| 2667  | 4         | 16.67%  |
| 1600  | 2         | 8.33%   |
| 6400  | 1         | 4.17%   |
| 4800  | 1         | 4.17%   |
| 4266  | 1         | 4.17%   |
| 2400  | 1         | 4.17%   |
| 2133  | 1         | 4.17%   |
| 1333  | 1         | 4.17%   |
| 975   | 1         | 4.17%   |

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
| Chicony Electronics                    | 17        | 18.09%  |
| IMC Networks                           | 13        | 13.83%  |
| Acer                                   | 9         | 9.57%   |
| Realtek Semiconductor                  | 7         | 7.45%   |
| Sunplus Innovation Technology          | 6         | 6.38%   |
| Microdia                               | 6         | 6.38%   |
| Quanta                                 | 5         | 5.32%   |
| Syntek                                 | 4         | 4.26%   |
| Sonix Technology                       | 4         | 4.26%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.26%   |
| Apple                                  | 4         | 4.26%   |
| Luxvisions Innotech Limited            | 3         | 3.19%   |
| Logitech                               | 3         | 3.19%   |
| Suyin                                  | 2         | 2.13%   |
| Tobii Technology AB                    | 1         | 1.06%   |
| SunplusIT                              | 1         | 1.06%   |
| Samsung Electronics                    | 1         | 1.06%   |
| Lite-On Technology                     | 1         | 1.06%   |
| Intel                                  | 1         | 1.06%   |
| Importek                               | 1         | 1.06%   |
| Goodong Industry                       | 1         | 1.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 6         | 6.32%   |
| Syntek Integrated Camera                             | 3         | 3.16%   |
| Sonix USB2.0 HD UVC WebCam                           | 3         | 3.16%   |
| Realtek USB Camera                                   | 3         | 3.16%   |
| Microdia Integrated_Webcam_HD                        | 3         | 3.16%   |
| IMC Networks Integrated Camera                       | 3         | 3.16%   |
| Chicony Integrated Camera                            | 3         | 3.16%   |
| Acer Integrated Camera                               | 3         | 3.16%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 2.11%   |
| Realtek Integrated_Webcam_HD                         | 2         | 2.11%   |
| Chicony USB 2.0 Camera                               | 2         | 2.11%   |
| Chicony HP Truevision HD                             | 2         | 2.11%   |
| Apple FaceTime HD Camera                             | 2         | 2.11%   |
| Acer Lenovo Integrated Webcam                        | 2         | 2.11%   |
| Acer HD Webcam                                       | 2         | 2.11%   |
| Tobii AB EyeChip                                     | 1         | 1.05%   |
| Syntek EasyCamera                                    | 1         | 1.05%   |
| Suyin HP TrueVision HD Integrated Webcam             | 1         | 1.05%   |
| Suyin HP TrueVision Full HD                          | 1         | 1.05%   |
| SunplusIT MTD camera                                 | 1         | 1.05%   |
| Sunplus Laptop Integrated WebCam HD                  | 1         | 1.05%   |
| Sunplus HP HD Webcam [Fixed]                         | 1         | 1.05%   |
| Sunplus HD WebCam                                    | 1         | 1.05%   |
| Sunplus Asus Webcam                                  | 1         | 1.05%   |
| Sonix USB2.0 FHD UVC WebCam                          | 1         | 1.05%   |
| Samsung Galaxy A5 (MTP)                              | 1         | 1.05%   |
| Realtek HP Truevision HD integrated webcam           | 1         | 1.05%   |
| Realtek EasyCamera                                   | 1         | 1.05%   |
| Quanta VGA WebCam                                    | 1         | 1.05%   |
| Quanta USB2.0 VGA UVC WebCam                         | 1         | 1.05%   |
| Quanta USB HD Webcam                                 | 1         | 1.05%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.05%   |
| Quanta HD Webcam                                     | 1         | 1.05%   |
| Microdia USB 2.0 Camera                              | 1         | 1.05%   |
| Microdia Lenovo EasyCamera                           | 1         | 1.05%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.05%   |
| Luxvisions Innotech Limited Integrated Camera        | 1         | 1.05%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.05%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 1.05%   |
| Logitech QuickCam Pro 9000                           | 1         | 1.05%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 5         | 33.33%  |
| Validity Sensors                   | 4         | 26.67%  |
| Shenzhen Goodix Technology         | 3         | 20%     |
| Elan Microelectronics              | 2         | 13.33%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 3         | 20%     |
| Shenzhen Goodix  Fingerprint Device                             | 3         | 20%     |
| Elan ELAN:ARM-M4                                                | 2         | 13.33%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 6.67%   |
| Synaptics WBDI Device                                           | 1         | 6.67%   |
| Synaptics  WBDI                                                 | 1         | 6.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 6.67%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 6.67%   |

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
| 0     | 69        | 65.09%  |
| 1     | 28        | 26.42%  |
| 2     | 9         | 8.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 33.33%  |
| Graphics card         | 11        | 24.44%  |
| Multimedia controller | 9         | 20%     |
| Net/wireless          | 6         | 13.33%  |
| Bluetooth             | 2         | 4.44%   |
| Modem                 | 1         | 2.22%   |
| Chipcard              | 1         | 2.22%   |

