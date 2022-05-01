Lubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Lubuntu.

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

Total: 871

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Google        | Bobba360                    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| YASHI         | MYBOOK 360                  | [d44c4fd567](https://linux-hardware.org/?probe=d44c4fd567) | Apr 29, 2022 |
| HP            | Pavilion g4                 | [d225cb6b3d](https://linux-hardware.org/?probe=d225cb6b3d) | Apr 28, 2022 |
| HP            | Pavilion g4                 | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [753e3fda7d](https://linux-hardware.org/?probe=753e3fda7d) | Apr 26, 2022 |
| Dell          | Latitude 7480               | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| Gigabyte      | M912                        | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | 1215N                       | [b921f6fbae](https://linux-hardware.org/?probe=b921f6fbae) | Apr 24, 2022 |
| Mediacom      | GTZS                        | [41939828a4](https://linux-hardware.org/?probe=41939828a4) | Apr 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [c8f16c0d16](https://linux-hardware.org/?probe=c8f16c0d16) | Apr 22, 2022 |
| Google        | Droid                       | [b7b4dc6117](https://linux-hardware.org/?probe=b7b4dc6117) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ff77bbf8ae](https://linux-hardware.org/?probe=ff77bbf8ae) | Apr 22, 2022 |
| Mediacom      | GTZS                        | [edc22ef82a](https://linux-hardware.org/?probe=edc22ef82a) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| HP            | Pavilion dv4                | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| Intel         | W7650                       | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| HP            | Compaq Presario C700        | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Dell          | Inspiron 3180               | [9d280b4678](https://linux-hardware.org/?probe=9d280b4678) | Apr 14, 2022 |
| Dell          | Latitude E6410              | [e5e350a4a8](https://linux-hardware.org/?probe=e5e350a4a8) | Apr 13, 2022 |
| Google        | Kip                         | [4641a94428](https://linux-hardware.org/?probe=4641a94428) | Apr 13, 2022 |
| Dell          | Latitude E7240              | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| ASUSTek       | 1000H                       | [725f548eab](https://linux-hardware.org/?probe=725f548eab) | Apr 09, 2022 |
| Dell          | Inspiron N4010              | [0aac536dbf](https://linux-hardware.org/?probe=0aac536dbf) | Apr 04, 2022 |
| Samsung       | N100SP                      | [6a70399256](https://linux-hardware.org/?probe=6a70399256) | Mar 31, 2022 |
| Acer          | AOA150                      | [a59a005250](https://linux-hardware.org/?probe=a59a005250) | Mar 30, 2022 |
| Intel         | W7650                       | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| Haier         | U1520EM                     | [5fde1c39e9](https://linux-hardware.org/?probe=5fde1c39e9) | Mar 25, 2022 |
| Fujitsu Si... | AMILO Li3710                | [ab84e23108](https://linux-hardware.org/?probe=ab84e23108) | Mar 24, 2022 |
| AMI           | Cherry Trail CR             | [af80d44a27](https://linux-hardware.org/?probe=af80d44a27) | Mar 23, 2022 |
| HP            | Pavilion g7                 | [2c480cdfac](https://linux-hardware.org/?probe=2c480cdfac) | Mar 22, 2022 |
| IBM           | Unknown                     | [2bcbb8a946](https://linux-hardware.org/?probe=2bcbb8a946) | Mar 21, 2022 |
| HP            | EliteBook 745 G6            | [a3f94c2957](https://linux-hardware.org/?probe=a3f94c2957) | Mar 20, 2022 |
| Apple         | MacBookPro6,2               | [d4c7ecbc5e](https://linux-hardware.org/?probe=d4c7ecbc5e) | Mar 20, 2022 |
| Acer          | AO751h                      | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| Google        | Celes                       | [cfcec68610](https://linux-hardware.org/?probe=cfcec68610) | Mar 15, 2022 |
| HP            | Laptop 15-bs0xx             | [37a24fa0b8](https://linux-hardware.org/?probe=37a24fa0b8) | Mar 13, 2022 |
| HP            | Laptop 15-da0xxx            | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | [707be96775](https://linux-hardware.org/?probe=707be96775) | Mar 13, 2022 |
| ASUSTek       | X550LA                      | [eb7071ed13](https://linux-hardware.org/?probe=eb7071ed13) | Mar 12, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| Fujitsu Si... | AMILO Li3710                | [7a4a682f45](https://linux-hardware.org/?probe=7a4a682f45) | Mar 07, 2022 |
| Lenovo        | G50-30 80G0                 | [efc41b55f4](https://linux-hardware.org/?probe=efc41b55f4) | Mar 06, 2022 |
| Dell          | Inspiron 1090               | [31efa1bb6f](https://linux-hardware.org/?probe=31efa1bb6f) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | [6a97a96f56](https://linux-hardware.org/?probe=6a97a96f56) | Mar 01, 2022 |
| Dell          | Inspiron 1090               | [9d63b9e47f](https://linux-hardware.org/?probe=9d63b9e47f) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [9a59eff157](https://linux-hardware.org/?probe=9a59eff157) | Feb 26, 2022 |
| Toshiba       | Satellite S55-B             | [f07aaa2fd3](https://linux-hardware.org/?probe=f07aaa2fd3) | Feb 25, 2022 |
| Samsung       | RV415/RV515                 | [ba023e3489](https://linux-hardware.org/?probe=ba023e3489) | Feb 24, 2022 |
| Insyde        | N116                        | [a6dd43dfb4](https://linux-hardware.org/?probe=a6dd43dfb4) | Feb 21, 2022 |
| Toshiba       | Satellite S55-B             | [8551d043a9](https://linux-hardware.org/?probe=8551d043a9) | Feb 20, 2022 |
| Intel         | W7650                       | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |
| Alienware     | M17                         | [9d29db918d](https://linux-hardware.org/?probe=9d29db918d) | Feb 18, 2022 |
| HP            | Pavilion g6                 | [5601a4d596](https://linux-hardware.org/?probe=5601a4d596) | Feb 14, 2022 |
| HP            | Laptop 15-da0xxx            | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [1f9694d47d](https://linux-hardware.org/?probe=1f9694d47d) | Feb 12, 2022 |
| Sony          | VGN-SZ71WN_C                | [677d24e366](https://linux-hardware.org/?probe=677d24e366) | Feb 11, 2022 |
| Positivo      | N600                        | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Positivo      | N600                        | [1591046f31](https://linux-hardware.org/?probe=1591046f31) | Feb 08, 2022 |
| Dell          | Inspiron 11-3168            | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| Dell          | Latitude E5540              | [e895dcce0f](https://linux-hardware.org/?probe=e895dcce0f) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| HP            | 255 G6 Notebook PC          | [9c5efed237](https://linux-hardware.org/?probe=9c5efed237) | Feb 06, 2022 |
| Lenovo        | 3000 N200 0769ALU           | [695855f143](https://linux-hardware.org/?probe=695855f143) | Feb 05, 2022 |
| Lenovo        | 3000 N200 0769ALU           | [661ffedd80](https://linux-hardware.org/?probe=661ffedd80) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | [4c355aa7c2](https://linux-hardware.org/?probe=4c355aa7c2) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | [61fc6b2cb0](https://linux-hardware.org/?probe=61fc6b2cb0) | Feb 05, 2022 |
| Toshiba       | Satellite C875              | [1dd31ebdd6](https://linux-hardware.org/?probe=1dd31ebdd6) | Feb 02, 2022 |
| Insyde        | i101c                       | [375f7e61b2](https://linux-hardware.org/?probe=375f7e61b2) | Feb 02, 2022 |
| Lenovo        | ThinkPad T460 20FMS2J000    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Prestigio     | PSB141C01BFH                | [5adcd620f6](https://linux-hardware.org/?probe=5adcd620f6) | Jan 30, 2022 |
| Google        | Peppy                       | [15cd563f21](https://linux-hardware.org/?probe=15cd563f21) | Jan 27, 2022 |
| ASUSTek       | GL553VW                     | [7713319e74](https://linux-hardware.org/?probe=7713319e74) | Jan 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [433e46caa5](https://linux-hardware.org/?probe=433e46caa5) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | [f88ac2dd3e](https://linux-hardware.org/?probe=f88ac2dd3e) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | [6c56c2c8b3](https://linux-hardware.org/?probe=6c56c2c8b3) | Jan 19, 2022 |
| Apple         | MacBookPro10,1              | [1aa2cd2e8f](https://linux-hardware.org/?probe=1aa2cd2e8f) | Jan 19, 2022 |
| Dell          | Inspiron 15-3573            | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Apple         | MacBookPro10,2              | [804b4adedc](https://linux-hardware.org/?probe=804b4adedc) | Jan 15, 2022 |
| HP            | ProBook 450 G2              | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| HP            | Notebook                    | [847afd8ac5](https://linux-hardware.org/?probe=847afd8ac5) | Jan 12, 2022 |
| System76      | Lemur Pro                   | [fa22d4610e](https://linux-hardware.org/?probe=fa22d4610e) | Jan 11, 2022 |
| Positivo      | N600                        | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| HP            | Compaq 6910p (GX316UC#AB... | [0ffa23c15e](https://linux-hardware.org/?probe=0ffa23c15e) | Jan 07, 2022 |
| Toshiba       | Satellite L50D-B            | [e253741d9f](https://linux-hardware.org/?probe=e253741d9f) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | [66d00e2cd5](https://linux-hardware.org/?probe=66d00e2cd5) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | [7cf1327087](https://linux-hardware.org/?probe=7cf1327087) | Jan 05, 2022 |
| HP            | Pavilion dv2700             | [c8aafbbc8d](https://linux-hardware.org/?probe=c8aafbbc8d) | Jan 04, 2022 |
| Alienware     | m15                         | [a0d4f93250](https://linux-hardware.org/?probe=a0d4f93250) | Jan 04, 2022 |
| Apple         | MacBookPro8,1               | [eaf2e708d9](https://linux-hardware.org/?probe=eaf2e708d9) | Jan 03, 2022 |
| Acer          | Aspire 7715Z                | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| Lanix         | NeuronALV5                  | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| Dell          | Latitude 7480               | [a338b67d45](https://linux-hardware.org/?probe=a338b67d45) | Dec 30, 2021 |
| Sony          | VPCEJ1E1E                   | [0211323709](https://linux-hardware.org/?probe=0211323709) | Dec 28, 2021 |
| Dell          | Inspiron 15 3515            | [8d130910ab](https://linux-hardware.org/?probe=8d130910ab) | Dec 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [f5924cb8b4](https://linux-hardware.org/?probe=f5924cb8b4) | Dec 25, 2021 |
| Sony          | VPCEJ1E1E                   | [d8d2b553bf](https://linux-hardware.org/?probe=d8d2b553bf) | Dec 24, 2021 |
| I-Life Dig... | ZED AIR                     | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| Acer          | AOA150                      | [47cae573c1](https://linux-hardware.org/?probe=47cae573c1) | Dec 22, 2021 |
| Acer          | Aspire E1-572G              | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| Acer          | Aspire F5-573G              | [2e9fd50292](https://linux-hardware.org/?probe=2e9fd50292) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | [452b8c0ac4](https://linux-hardware.org/?probe=452b8c0ac4) | Dec 20, 2021 |
| Dell          | Latitude E6520              | [c7edb79be7](https://linux-hardware.org/?probe=c7edb79be7) | Dec 20, 2021 |
| Samsung       | 275E4E/275E5E               | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [b956646608](https://linux-hardware.org/?probe=b956646608) | Dec 12, 2021 |
| HP            | EliteBook 850 G3            | [7cf21876b0](https://linux-hardware.org/?probe=7cf21876b0) | Dec 12, 2021 |
| Acer          | Aspire 5742G                | [950da990e7](https://linux-hardware.org/?probe=950da990e7) | Dec 12, 2021 |
| HP            | OMEN by Laptop              | [8419e68dd3](https://linux-hardware.org/?probe=8419e68dd3) | Dec 12, 2021 |
| ASUSTek       | 1015BXO                     | [f9eb963d74](https://linux-hardware.org/?probe=f9eb963d74) | Dec 12, 2021 |
| MSI           | Katana GF76 11UC            | [73fd53a50c](https://linux-hardware.org/?probe=73fd53a50c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Positivo      | AT300b                      | [20b3635188](https://linux-hardware.org/?probe=20b3635188) | Dec 06, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [c5f877312c](https://linux-hardware.org/?probe=c5f877312c) | Dec 05, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [6c0aeae287](https://linux-hardware.org/?probe=6c0aeae287) | Dec 05, 2021 |
| HP            | Compaq 6510b (GR691EA#AB... | [4d657211eb](https://linux-hardware.org/?probe=4d657211eb) | Dec 04, 2021 |
| Acer          | AOD255E                     | [390afd35cb](https://linux-hardware.org/?probe=390afd35cb) | Dec 03, 2021 |
| HP            | ProBook 440 G7              | [155ec30920](https://linux-hardware.org/?probe=155ec30920) | Dec 03, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [edce40927f](https://linux-hardware.org/?probe=edce40927f) | Dec 01, 2021 |
| Toshiba       | Satellite C50-A-19U         | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| HP            | Compaq 6720s                | [2c62d9df9c](https://linux-hardware.org/?probe=2c62d9df9c) | Nov 28, 2021 |
| ASUSTek       | 1000HE                      | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| I-Life Dig... | ZED AIR                     | [a6e2e61f26](https://linux-hardware.org/?probe=a6e2e61f26) | Nov 24, 2021 |
| Toshiba       | Satellite L40               | [43d9bb451a](https://linux-hardware.org/?probe=43d9bb451a) | Nov 23, 2021 |
| Dell          | Latitude 3330               | [2c8f88588b](https://linux-hardware.org/?probe=2c8f88588b) | Nov 23, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | [867419b410](https://linux-hardware.org/?probe=867419b410) | Nov 21, 2021 |
| Medion        | P6630                       | [edc09031bd](https://linux-hardware.org/?probe=edc09031bd) | Nov 16, 2021 |
| HP            | Pavilion dv6                | [591f986631](https://linux-hardware.org/?probe=591f986631) | Nov 14, 2021 |
| ASUSTek       | 1015BX                      | [51933ea3ac](https://linux-hardware.org/?probe=51933ea3ac) | Nov 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [0e17c0b84d](https://linux-hardware.org/?probe=0e17c0b84d) | Nov 13, 2021 |
| HP            | ProBook 440 G7              | [35b6f85a28](https://linux-hardware.org/?probe=35b6f85a28) | Nov 10, 2021 |
| Acer          | AO751h                      | [e2beb798cc](https://linux-hardware.org/?probe=e2beb798cc) | Nov 10, 2021 |
| Dell          | Inspiron MM061              | [03bba840c5](https://linux-hardware.org/?probe=03bba840c5) | Nov 07, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | [4e3e71f6ab](https://linux-hardware.org/?probe=4e3e71f6ab) | Nov 07, 2021 |
| HP            | Laptop 15s-fq1xxx           | [25f858c7b1](https://linux-hardware.org/?probe=25f858c7b1) | Nov 05, 2021 |
| Mediacom      | GTZS                        | [a2a881793d](https://linux-hardware.org/?probe=a2a881793d) | Nov 03, 2021 |
| HP            | ProBook 4540s               | [fca622f4c4](https://linux-hardware.org/?probe=fca622f4c4) | Nov 01, 2021 |
| Samsung       | R40/R41                     | [5c44d1e88b](https://linux-hardware.org/?probe=5c44d1e88b) | Nov 01, 2021 |
| HP            | Pavilion dv6                | [e84cd86eb0](https://linux-hardware.org/?probe=e84cd86eb0) | Oct 31, 2021 |
| HP            | Pavilion Notebook           | [2c6c86b1fb](https://linux-hardware.org/?probe=2c6c86b1fb) | Oct 31, 2021 |
| HP            | ProBook 4540s               | [e12d7e47e6](https://linux-hardware.org/?probe=e12d7e47e6) | Oct 31, 2021 |
| HP            | ProBook 4540s               | [e565d7befe](https://linux-hardware.org/?probe=e565d7befe) | Oct 31, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f86520f5a7](https://linux-hardware.org/?probe=f86520f5a7) | Oct 28, 2021 |
| HP            | Presario CQ58               | [60d72bdce7](https://linux-hardware.org/?probe=60d72bdce7) | Oct 28, 2021 |
| HP            | Presario CQ58               | [8989debda6](https://linux-hardware.org/?probe=8989debda6) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | [e1e44b58f3](https://linux-hardware.org/?probe=e1e44b58f3) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | [42d3788463](https://linux-hardware.org/?probe=42d3788463) | Oct 27, 2021 |
| HP            | 2000                        | [65ec913842](https://linux-hardware.org/?probe=65ec913842) | Oct 27, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1663dc4946](https://linux-hardware.org/?probe=1663dc4946) | Oct 26, 2021 |
| Samsung       | N100SP                      | [7e4ef50289](https://linux-hardware.org/?probe=7e4ef50289) | Oct 26, 2021 |
| Samsung       | N100SP                      | [66b0ed9638](https://linux-hardware.org/?probe=66b0ed9638) | Oct 25, 2021 |
| Acer          | TravelMate P253             | [d74c10f41f](https://linux-hardware.org/?probe=d74c10f41f) | Oct 24, 2021 |
| Dell          | Inspiron 3583               | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Sony          | VGN-CR11Z_R                 | [538c03b235](https://linux-hardware.org/?probe=538c03b235) | Oct 23, 2021 |
| Samsung       | N100SP                      | [4d8eadf806](https://linux-hardware.org/?probe=4d8eadf806) | Oct 23, 2021 |
| Apple         | MacBookPro8,1               | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Sony          | VGN-CR11Z_R                 | [57043d09fe](https://linux-hardware.org/?probe=57043d09fe) | Oct 22, 2021 |
| Acer          | Aspire ES1-131              | [de7bee5c36](https://linux-hardware.org/?probe=de7bee5c36) | Oct 20, 2021 |
| Intel         | W7650                       | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| Toshiba       | Satellite C50D-A-13G        | [32f90e6cf8](https://linux-hardware.org/?probe=32f90e6cf8) | Oct 18, 2021 |
| MSI           | Modern 15 A10M              | [184c512c35](https://linux-hardware.org/?probe=184c512c35) | Oct 18, 2021 |
| Lenovo        | ThinkPad X61 76744NG        | [ee90608b54](https://linux-hardware.org/?probe=ee90608b54) | Oct 15, 2021 |
| Noblex        | E11IS2                      | [463e1f38e8](https://linux-hardware.org/?probe=463e1f38e8) | Oct 14, 2021 |
| HP            | Pavilion x2 Detachable      | [e5702172f9](https://linux-hardware.org/?probe=e5702172f9) | Oct 11, 2021 |
| HP            | Notebook                    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | 2000                        | [d84546de1b](https://linux-hardware.org/?probe=d84546de1b) | Oct 08, 2021 |
| HP            | Pavilion x2 Detachable      | [f81838645f](https://linux-hardware.org/?probe=f81838645f) | Oct 07, 2021 |
| HP            | Notebook                    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Dell          | Inspiron 15-3567            | [414e52d7a4](https://linux-hardware.org/?probe=414e52d7a4) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a927e8ff8e](https://linux-hardware.org/?probe=a927e8ff8e) | Oct 06, 2021 |
| HP            | Laptop 15-da0xxx            | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| Sony          | VPCSA2FGX                   | [60cfbaebef](https://linux-hardware.org/?probe=60cfbaebef) | Sep 29, 2021 |
| Toshiba       | Satellite L755D             | [aca989dcc4](https://linux-hardware.org/?probe=aca989dcc4) | Sep 29, 2021 |
| HP            | EliteBook 2560p             | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Apple         | MacBookPro8,1               | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| ASUSTek       | 1215B                       | [c45de8d3b1](https://linux-hardware.org/?probe=c45de8d3b1) | Sep 21, 2021 |
| Toshiba       | Satellite L20               | [654c60e971](https://linux-hardware.org/?probe=654c60e971) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Unknown       | Unknown                     | [64604612b2](https://linux-hardware.org/?probe=64604612b2) | Sep 19, 2021 |
| Lenovo        | G50-80 80L0                 | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| Dell          | Inspiron 3558               | [be96e8a7e1](https://linux-hardware.org/?probe=be96e8a7e1) | Sep 13, 2021 |
| Dell          | Inspiron 3558               | [f1414fdf7b](https://linux-hardware.org/?probe=f1414fdf7b) | Sep 13, 2021 |
| Apple         | MacBookPro8,1               | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| Lenovo        | G50-80 80L0                 | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| HP            | ProBook 450 G1              | [284c0763b3](https://linux-hardware.org/?probe=284c0763b3) | Sep 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| Toshiba       | Satellite A215              | [2d0d778e8e](https://linux-hardware.org/?probe=2d0d778e8e) | Aug 31, 2021 |
| Notebook      | NL40_50GU                   | [977812d04b](https://linux-hardware.org/?probe=977812d04b) | Aug 29, 2021 |
| Google        | Careena                     | [ab1bafda25](https://linux-hardware.org/?probe=ab1bafda25) | Aug 27, 2021 |
| Toshiba       | Satellite A205              | [50f9ce0180](https://linux-hardware.org/?probe=50f9ce0180) | Aug 26, 2021 |
| Dell          | XPS 13 9300                 | [6e1f484406](https://linux-hardware.org/?probe=6e1f484406) | Aug 24, 2021 |
| Toshiba       | Satellite A205              | [a4693372f9](https://linux-hardware.org/?probe=a4693372f9) | Aug 24, 2021 |
| Toshiba       | Satellite A205              | [f09b96d997](https://linux-hardware.org/?probe=f09b96d997) | Aug 20, 2021 |
| Toshiba       | Satellite A205              | [42151c3765](https://linux-hardware.org/?probe=42151c3765) | Aug 20, 2021 |
| Toshiba       | Satellite A205              | [63b870739f](https://linux-hardware.org/?probe=63b870739f) | Aug 19, 2021 |
| Toshiba       | Satellite A205              | [c696bffde7](https://linux-hardware.org/?probe=c696bffde7) | Aug 19, 2021 |
| Toshiba       | Satellite A205              | [90eb20e882](https://linux-hardware.org/?probe=90eb20e882) | Aug 17, 2021 |
| Toshiba       | Satellite A205              | [7c15d3c35d](https://linux-hardware.org/?probe=7c15d3c35d) | Aug 16, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Toshiba       | Satellite A205              | [bc09a1e988](https://linux-hardware.org/?probe=bc09a1e988) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406138U       | [a72c7ecd8a](https://linux-hardware.org/?probe=a72c7ecd8a) | Aug 14, 2021 |
| Dell          | Inspiron 3583               | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [798feee097](https://linux-hardware.org/?probe=798feee097) | Aug 07, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [9b893159ef](https://linux-hardware.org/?probe=9b893159ef) | Aug 06, 2021 |
| HP            | Pavilion g4                 | [f1d3ddf197](https://linux-hardware.org/?probe=f1d3ddf197) | Aug 06, 2021 |
| Dell          | G3 3500                     | [239b740235](https://linux-hardware.org/?probe=239b740235) | Aug 03, 2021 |
| Mediacom      | SmartBook 14 FullHD - SB... | [0719538c6e](https://linux-hardware.org/?probe=0719538c6e) | Aug 02, 2021 |
| HP            | OMEN by Laptop              | [7ca0de35b4](https://linux-hardware.org/?probe=7ca0de35b4) | Aug 01, 2021 |
| Dell          | Latitude E5450              | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| HP            | ProBook 6450b               | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| Acer          | Aspire 5735                 | [db933e0ebd](https://linux-hardware.org/?probe=db933e0ebd) | Jul 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d77a8cde0f](https://linux-hardware.org/?probe=d77a8cde0f) | Jul 23, 2021 |
| Dell          | Inspiron M5040              | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Dell          | Inspiron 1018               | [2e26e3540a](https://linux-hardware.org/?probe=2e26e3540a) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | [b74062f49d](https://linux-hardware.org/?probe=b74062f49d) | Jul 20, 2021 |
| Sony          | SVE1113M1EW                 | [b01beadd52](https://linux-hardware.org/?probe=b01beadd52) | Jul 16, 2021 |
| Toshiba       | K201                        | [85abf16ca0](https://linux-hardware.org/?probe=85abf16ca0) | Jul 15, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [d4852f4d01](https://linux-hardware.org/?probe=d4852f4d01) | Jul 14, 2021 |
| Google        | Winky                       | [696230b066](https://linux-hardware.org/?probe=696230b066) | Jul 14, 2021 |
| Google        | Winky                       | [6048ac2ff9](https://linux-hardware.org/?probe=6048ac2ff9) | Jul 14, 2021 |
| Apple         | MacBookPro10,2              | [0f8c7a6b66](https://linux-hardware.org/?probe=0f8c7a6b66) | Jul 12, 2021 |
| LEADER        | TW9/SW9                     | [6da16947e1](https://linux-hardware.org/?probe=6da16947e1) | Jul 07, 2021 |
| ASUSTek       | 1015PE                      | [051265df6e](https://linux-hardware.org/?probe=051265df6e) | Jul 05, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [b083bc08c4](https://linux-hardware.org/?probe=b083bc08c4) | Jul 04, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| Apple         | MacBook4,1                  | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| MSI           | GX780R/GT780R/GT780DXR/G... | [212a084b93](https://linux-hardware.org/?probe=212a084b93) | Jul 01, 2021 |
| Samsung       | RV415/RV515                 | [581180a4d8](https://linux-hardware.org/?probe=581180a4d8) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | [e09b0ac6cf](https://linux-hardware.org/?probe=e09b0ac6cf) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | [caa1dadc98](https://linux-hardware.org/?probe=caa1dadc98) | Jun 29, 2021 |
| Samsung       | RV415/RV515                 | [99a0739814](https://linux-hardware.org/?probe=99a0739814) | Jun 28, 2021 |
| HP            | EliteBook 840 G6            | [cfd34d8c5b](https://linux-hardware.org/?probe=cfd34d8c5b) | Jun 22, 2021 |
| ASUSTek       | T100TA                      | [8a1c5e9daf](https://linux-hardware.org/?probe=8a1c5e9daf) | Jun 21, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [d94415969c](https://linux-hardware.org/?probe=d94415969c) | Jun 19, 2021 |
| Notebook      | NHxxRZQ                     | [221e4d197b](https://linux-hardware.org/?probe=221e4d197b) | Jun 19, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [fdbc9729c1](https://linux-hardware.org/?probe=fdbc9729c1) | Jun 18, 2021 |
| HP            | EliteBook 2560p             | [b8cf45e412](https://linux-hardware.org/?probe=b8cf45e412) | Jun 15, 2021 |
| Positivo      | Mobile                      | [050aa55013](https://linux-hardware.org/?probe=050aa55013) | Jun 14, 2021 |
| Samsung       | RC512                       | [d8681e5e08](https://linux-hardware.org/?probe=d8681e5e08) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Google        | Kohaku                      | [6de3f99f1d](https://linux-hardware.org/?probe=6de3f99f1d) | Jun 08, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | [0a5cb29f98](https://linux-hardware.org/?probe=0a5cb29f98) | Jun 07, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | [29f66db2d1](https://linux-hardware.org/?probe=29f66db2d1) | Jun 07, 2021 |
| Acer          | Aspire 5715Z                | [5824a05a58](https://linux-hardware.org/?probe=5824a05a58) | Jun 05, 2021 |
| ASUSTek       | T100HAN                     | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| Lenovo        | ThinkPad T410s 2924C39      | [5dc4a1e557](https://linux-hardware.org/?probe=5dc4a1e557) | May 31, 2021 |
| Acer          | Aspire 5715Z                | [2e325cddc1](https://linux-hardware.org/?probe=2e325cddc1) | May 30, 2021 |
| Acer          | Aspire 5715Z                | [417206cc6a](https://linux-hardware.org/?probe=417206cc6a) | May 30, 2021 |
| Dell          | Latitude D820               | [5b23528d58](https://linux-hardware.org/?probe=5b23528d58) | May 29, 2021 |
| MSI           | Modern 15 A10M              | [23182c745b](https://linux-hardware.org/?probe=23182c745b) | May 27, 2021 |
| HP            | ProBook 6550b               | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | Latitude D630               | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| Acer          | Aspire 5715Z                | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Dell          | Inspiron MM061              | [3eb7729825](https://linux-hardware.org/?probe=3eb7729825) | May 23, 2021 |
| Lenovo        | G70-80 80FF                 | [fba07779e2](https://linux-hardware.org/?probe=fba07779e2) | May 21, 2021 |
| MSI           | Modern 15 A10M              | [001eb9ea2f](https://linux-hardware.org/?probe=001eb9ea2f) | May 21, 2021 |
| Lenovo        | ThinkPad W510 4318CTO       | [bc53ad8072](https://linux-hardware.org/?probe=bc53ad8072) | May 20, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | [6e24cb56ad](https://linux-hardware.org/?probe=6e24cb56ad) | May 19, 2021 |
| HP            | Presario V5000 (ET820UA#... | [f91a752d4d](https://linux-hardware.org/?probe=f91a752d4d) | May 19, 2021 |
| ASUSTek       | 1005HA                      | [e819e51835](https://linux-hardware.org/?probe=e819e51835) | May 18, 2021 |
| Acer          | Extensa 5620                | [2da2f6a795](https://linux-hardware.org/?probe=2da2f6a795) | May 17, 2021 |
| Acer          | Aspire 5715Z                | [aa3fceee37](https://linux-hardware.org/?probe=aa3fceee37) | May 17, 2021 |
| Apple         | MacBookPro8,1               | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Toshiba       | Satellite L70-B             | [aba62024a7](https://linux-hardware.org/?probe=aba62024a7) | May 15, 2021 |
| Sony          | VPCSB1V9E                   | [5682d68364](https://linux-hardware.org/?probe=5682d68364) | May 14, 2021 |
| Samsung       | R520/R522/R620              | [2216d5b0b1](https://linux-hardware.org/?probe=2216d5b0b1) | May 14, 2021 |
| Samsung       | R520/R522/R620              | [b724b0cc62](https://linux-hardware.org/?probe=b724b0cc62) | May 14, 2021 |
| Lenovo        | ThinkPad X240 20AMS2P400    | [9f6e7024d4](https://linux-hardware.org/?probe=9f6e7024d4) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | [d044706f11](https://linux-hardware.org/?probe=d044706f11) | May 13, 2021 |
| Lenovo        | G40-30 80FY                 | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | [25eb899222](https://linux-hardware.org/?probe=25eb899222) | May 12, 2021 |
| Unknown       | Unknown                     | [a54c655ae8](https://linux-hardware.org/?probe=a54c655ae8) | May 12, 2021 |
| Packard Be... | EasyNote MH35               | [b755c5449a](https://linux-hardware.org/?probe=b755c5449a) | May 11, 2021 |
| IBM           | ThinkPad Z60m 25303JM       | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [0b34a1f92d](https://linux-hardware.org/?probe=0b34a1f92d) | May 04, 2021 |
| HP            | Laptop 15-da0xxx            | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| HP            | Notebook                    | [ca99bba8dc](https://linux-hardware.org/?probe=ca99bba8dc) | May 02, 2021 |
| Lenovo        | 100-14IBY 80R7              | [61af9638d2](https://linux-hardware.org/?probe=61af9638d2) | Apr 30, 2021 |
| LG Electro... | S425-L.BC22P1               | [791fd9ff12](https://linux-hardware.org/?probe=791fd9ff12) | Apr 28, 2021 |
| Lenovo        | G460 20041                  | [4015285676](https://linux-hardware.org/?probe=4015285676) | Apr 26, 2021 |
| ASUSTek       | X102BA                      | [de8b267423](https://linux-hardware.org/?probe=de8b267423) | Apr 25, 2021 |
| ASUSTek       | X102BA                      | [c660d95c3f](https://linux-hardware.org/?probe=c660d95c3f) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | [e958267bec](https://linux-hardware.org/?probe=e958267bec) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | [cf6e170fcc](https://linux-hardware.org/?probe=cf6e170fcc) | Apr 25, 2021 |
| Dell          | Vostro A90                  | [21b167db8c](https://linux-hardware.org/?probe=21b167db8c) | Apr 25, 2021 |
| HP            | Laptop 15-da0xxx            | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Gateway       | Blade-K8F                   | [13e1a6028e](https://linux-hardware.org/?probe=13e1a6028e) | Apr 24, 2021 |
| Dell          | Inspiron N4020              | [9002772847](https://linux-hardware.org/?probe=9002772847) | Apr 21, 2021 |
| Intel Clie... | LAPQC71B                    | [272956b140](https://linux-hardware.org/?probe=272956b140) | Apr 20, 2021 |
| Acer          | Aspire V5-123               | [448b0afd35](https://linux-hardware.org/?probe=448b0afd35) | Apr 20, 2021 |
| Dell          | Inspiron N4020              | [f03d856fe1](https://linux-hardware.org/?probe=f03d856fe1) | Apr 20, 2021 |
| Lenovo        | Z50-70 20354                | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Apple         | MacBook2,1                  | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [6a22991dbe](https://linux-hardware.org/?probe=6a22991dbe) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Dell          | Inspiron 15-3567            | [0a367170ed](https://linux-hardware.org/?probe=0a367170ed) | Apr 17, 2021 |
| HP            | Laptop 15-da0xxx            | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Toshiba       | Satellite L35               | [1abffa2c4c](https://linux-hardware.org/?probe=1abffa2c4c) | Apr 16, 2021 |
| LG Electro... | S425-L.BC22P1               | [64a50f7bb8](https://linux-hardware.org/?probe=64a50f7bb8) | Apr 15, 2021 |
| Dell          | Inspiron N4020              | [e0086be941](https://linux-hardware.org/?probe=e0086be941) | Apr 15, 2021 |
| HP            | Compaq 6820s                | [551053e9d6](https://linux-hardware.org/?probe=551053e9d6) | Apr 15, 2021 |
| Lenovo        | G460 20041                  | [e2dea3ec01](https://linux-hardware.org/?probe=e2dea3ec01) | Apr 14, 2021 |
| Dell          | Studio 1555                 | [c161e182c2](https://linux-hardware.org/?probe=c161e182c2) | Apr 14, 2021 |
| Toshiba       | Satellite L450              | [2c5ef0687b](https://linux-hardware.org/?probe=2c5ef0687b) | Apr 13, 2021 |
| HP            | EliteBook 8440p (VV954AV... | [3e0b56daf3](https://linux-hardware.org/?probe=3e0b56daf3) | Apr 12, 2021 |
| ASHI          | Unknown                     | [68a2b34c2f](https://linux-hardware.org/?probe=68a2b34c2f) | Apr 12, 2021 |
| HP            | ProBook 6560b               | [8c2a2cfdef](https://linux-hardware.org/?probe=8c2a2cfdef) | Apr 12, 2021 |
| Toshiba       | Satellite L40               | [0f6ed90100](https://linux-hardware.org/?probe=0f6ed90100) | Apr 11, 2021 |
| HP            | Laptop 15s-eq1xxx           | [530be6ce7b](https://linux-hardware.org/?probe=530be6ce7b) | Apr 08, 2021 |
| Acer          | Aspire 5715Z                | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| GTZS          | Unknown                     | [5600074bc0](https://linux-hardware.org/?probe=5600074bc0) | Apr 07, 2021 |
| Samsung       | R520/R522/R620              | [a7f2749d3b](https://linux-hardware.org/?probe=a7f2749d3b) | Apr 06, 2021 |
| Toshiba       | Satellite C70D-B            | [f3e45414fa](https://linux-hardware.org/?probe=f3e45414fa) | Apr 04, 2021 |
| Toshiba       | Satellite C70D-B            | [eacca5eceb](https://linux-hardware.org/?probe=eacca5eceb) | Apr 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [db0eb79b4e](https://linux-hardware.org/?probe=db0eb79b4e) | Mar 31, 2021 |
| ASUSTek       | 1005PE                      | [d75411e5b3](https://linux-hardware.org/?probe=d75411e5b3) | Mar 30, 2021 |
| Lenovo        | IdeaPad Z580                | [6224897fde](https://linux-hardware.org/?probe=6224897fde) | Mar 29, 2021 |
| Toshiba       | Satellite L70-B             | [4f1445876a](https://linux-hardware.org/?probe=4f1445876a) | Mar 27, 2021 |
| Toshiba       | Satellite A200              | [b477c99ab7](https://linux-hardware.org/?probe=b477c99ab7) | Mar 27, 2021 |
| Dell          | Vostro 5470                 | [c9dfbce9bd](https://linux-hardware.org/?probe=c9dfbce9bd) | Mar 26, 2021 |
| ASUSTek       | K45VD                       | [74592068ee](https://linux-hardware.org/?probe=74592068ee) | Mar 25, 2021 |
| Dell          | Latitude D810               | [ca3886900f](https://linux-hardware.org/?probe=ca3886900f) | Mar 25, 2021 |
| Toshiba       | Satellite L70-B             | [e366c8c206](https://linux-hardware.org/?probe=e366c8c206) | Mar 24, 2021 |
| Toshiba       | Satellite L70-B             | [0baf745232](https://linux-hardware.org/?probe=0baf745232) | Mar 21, 2021 |
| Toshiba       | Satellite L70-B             | [961ef41a18](https://linux-hardware.org/?probe=961ef41a18) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | [82480a0f24](https://linux-hardware.org/?probe=82480a0f24) | Mar 21, 2021 |
| Lenovo        | S10-3                       | [42884278c4](https://linux-hardware.org/?probe=42884278c4) | Mar 19, 2021 |
| Dell          | XPS 15Z                     | [cb1bcbb365](https://linux-hardware.org/?probe=cb1bcbb365) | Mar 18, 2021 |
| Acer          | Aspire A315-57G             | [4235b59b38](https://linux-hardware.org/?probe=4235b59b38) | Mar 17, 2021 |
| Acer          | Aspire A315-57G             | [4b3b196273](https://linux-hardware.org/?probe=4b3b196273) | Mar 17, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| HP            | EliteBook 8460p             | [821bcfc074](https://linux-hardware.org/?probe=821bcfc074) | Mar 09, 2021 |
| HP            | EliteBook 8460p             | [47a0bdcb00](https://linux-hardware.org/?probe=47a0bdcb00) | Mar 08, 2021 |
| ASUSTek       | P53E                        | [3aacf8a497](https://linux-hardware.org/?probe=3aacf8a497) | Mar 07, 2021 |
| Toshiba       | Satellite L20               | [e40c220e30](https://linux-hardware.org/?probe=e40c220e30) | Mar 07, 2021 |
| IBM           | 2647KNG                     | [65d3c4c3c2](https://linux-hardware.org/?probe=65d3c4c3c2) | Mar 07, 2021 |
| IBM           | 2647KNG                     | [e4d4761cfe](https://linux-hardware.org/?probe=e4d4761cfe) | Mar 07, 2021 |
| Dell          | Vostro 3700                 | [0b9b8232f9](https://linux-hardware.org/?probe=0b9b8232f9) | Mar 05, 2021 |
| Dell          | Inspiron N5010              | [8273ed53f3](https://linux-hardware.org/?probe=8273ed53f3) | Mar 04, 2021 |
| HP            | Compaq Presario CQ60        | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| Dell          | Inspiron 1012               | [e66eef020e](https://linux-hardware.org/?probe=e66eef020e) | Mar 03, 2021 |
| Toshiba       | Satellite A135              | [05bbae8a9c](https://linux-hardware.org/?probe=05bbae8a9c) | Mar 02, 2021 |
| MSI           | MS-1453                     | [2be581dfbb](https://linux-hardware.org/?probe=2be581dfbb) | Mar 02, 2021 |
| MSI           | MS-1453                     | [bfaf417259](https://linux-hardware.org/?probe=bfaf417259) | Mar 02, 2021 |
| Toshiba       | Satellite A135              | [1986fa7acf](https://linux-hardware.org/?probe=1986fa7acf) | Mar 02, 2021 |
| Toshiba       | Satellite A660              | [70166b0f32](https://linux-hardware.org/?probe=70166b0f32) | Mar 01, 2021 |
| Lenovo        | S10-3                       | [6d4f0001a3](https://linux-hardware.org/?probe=6d4f0001a3) | Mar 01, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Acer          | Aspire 5610                 | [1cac0acc28](https://linux-hardware.org/?probe=1cac0acc28) | Feb 25, 2021 |
| Itautec       | Infoway w7430               | [72a0d46cbd](https://linux-hardware.org/?probe=72a0d46cbd) | Feb 25, 2021 |
| Timi          | TM1612                      | [517a0ea812](https://linux-hardware.org/?probe=517a0ea812) | Feb 23, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [c8fa1fd6d2](https://linux-hardware.org/?probe=c8fa1fd6d2) | Feb 23, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [bda750c182](https://linux-hardware.org/?probe=bda750c182) | Feb 23, 2021 |
| Dell          | Vostro 3700                 | [1063468eed](https://linux-hardware.org/?probe=1063468eed) | Feb 21, 2021 |
| Dell          | Vostro 3700                 | [234fac5997](https://linux-hardware.org/?probe=234fac5997) | Feb 21, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | [e79cbcdc53](https://linux-hardware.org/?probe=e79cbcdc53) | Feb 20, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | [eaeef8bb7b](https://linux-hardware.org/?probe=eaeef8bb7b) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| Dell          | Inspiron 1525               | [eeabc1752d](https://linux-hardware.org/?probe=eeabc1752d) | Feb 15, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [95b0ea2335](https://linux-hardware.org/?probe=95b0ea2335) | Feb 15, 2021 |
| HP            | Spectre Laptop 13-af0xx     | [e40f1f67bd](https://linux-hardware.org/?probe=e40f1f67bd) | Feb 15, 2021 |
| Dell          | Inspiron 15-3565            | [7c39aa2965](https://linux-hardware.org/?probe=7c39aa2965) | Feb 14, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [0f15feb522](https://linux-hardware.org/?probe=0f15feb522) | Feb 13, 2021 |
| HP            | ProBook 440 G6              | [715d525514](https://linux-hardware.org/?probe=715d525514) | Feb 07, 2021 |
| HP            | ProBook 440 G7              | [4fd36e0cb3](https://linux-hardware.org/?probe=4fd36e0cb3) | Feb 07, 2021 |
| Unknown       | Unknown                     | [bcad30556a](https://linux-hardware.org/?probe=bcad30556a) | Feb 07, 2021 |
| HP            | ProBook 440 G6              | [f943690f6e](https://linux-hardware.org/?probe=f943690f6e) | Feb 07, 2021 |
| HP            | Pavilion g7                 | [5151e90c72](https://linux-hardware.org/?probe=5151e90c72) | Feb 06, 2021 |
| HP            | G42                         | [b9fbeca924](https://linux-hardware.org/?probe=b9fbeca924) | Feb 05, 2021 |
| HP            | Compaq 6715b (GP690US#AB... | [e77dbfe4a6](https://linux-hardware.org/?probe=e77dbfe4a6) | Feb 05, 2021 |
| ASUSTek       | GL553VD                     | [51102bc7a6](https://linux-hardware.org/?probe=51102bc7a6) | Feb 04, 2021 |
| HP            | Pavilion dv6000 (RP154UA... | [44347b7399](https://linux-hardware.org/?probe=44347b7399) | Jan 31, 2021 |
| Lenovo        | ThinkPad L460 20FVS20700    | [e456ebd9cc](https://linux-hardware.org/?probe=e456ebd9cc) | Jan 29, 2021 |
| HP            | Notebook                    | [c83f3fcce6](https://linux-hardware.org/?probe=c83f3fcce6) | Jan 27, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [c654b7b4ad](https://linux-hardware.org/?probe=c654b7b4ad) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [20f7e526b4](https://linux-hardware.org/?probe=20f7e526b4) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| Samsung       | RV415/RV515                 | [8cf59ea427](https://linux-hardware.org/?probe=8cf59ea427) | Jan 23, 2021 |
| Apple         | MacBookPro10,2              | [19b2ebc706](https://linux-hardware.org/?probe=19b2ebc706) | Jan 22, 2021 |
| Dell          | Latitude 3440               | [ba52d4afcf](https://linux-hardware.org/?probe=ba52d4afcf) | Jan 22, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [304fa83224](https://linux-hardware.org/?probe=304fa83224) | Jan 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [09c2da07b2](https://linux-hardware.org/?probe=09c2da07b2) | Jan 21, 2021 |
| Apple         | MacBookPro10,2              | [3460a2d2a4](https://linux-hardware.org/?probe=3460a2d2a4) | Jan 21, 2021 |
| ASUSTek       | K53SD                       | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| HP            | ProBook 6360b               | [3e3cda2a19](https://linux-hardware.org/?probe=3e3cda2a19) | Jan 19, 2021 |
| Lenovo        | IdeaPad Y550 4186           | [d6ae69ca34](https://linux-hardware.org/?probe=d6ae69ca34) | Jan 17, 2021 |
| Toshiba       | Satellite A205              | [57f9413b16](https://linux-hardware.org/?probe=57f9413b16) | Jan 16, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| HP            | Pavilion g6                 | [23360e9a39](https://linux-hardware.org/?probe=23360e9a39) | Jan 12, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | [1f7fadda6e](https://linux-hardware.org/?probe=1f7fadda6e) | Jan 10, 2021 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [3aca8223d6](https://linux-hardware.org/?probe=3aca8223d6) | Jan 09, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [9764fca96a](https://linux-hardware.org/?probe=9764fca96a) | Jan 08, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [01626f040a](https://linux-hardware.org/?probe=01626f040a) | Jan 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [1bf71bd97d](https://linux-hardware.org/?probe=1bf71bd97d) | Jan 04, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [8f5c1dc1ca](https://linux-hardware.org/?probe=8f5c1dc1ca) | Jan 04, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [266231dab8](https://linux-hardware.org/?probe=266231dab8) | Jan 04, 2021 |
| Sony          | VPCYB35AL                   | [f82ea2b0dc](https://linux-hardware.org/?probe=f82ea2b0dc) | Jan 03, 2021 |
| Lenovo        | G50-45 80E3                 | [65ed0bcd53](https://linux-hardware.org/?probe=65ed0bcd53) | Jan 02, 2021 |
| Positivo      | S14CT01                     | [2b0f53fc1a](https://linux-hardware.org/?probe=2b0f53fc1a) | Jan 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [c11d9786f7](https://linux-hardware.org/?probe=c11d9786f7) | Dec 29, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [752fb8d0c7](https://linux-hardware.org/?probe=752fb8d0c7) | Dec 25, 2020 |
| Sony          | VPCYB35AL                   | [04597b3a72](https://linux-hardware.org/?probe=04597b3a72) | Dec 23, 2020 |
| Sony          | VPCYB35AL                   | [490e3a1b0a](https://linux-hardware.org/?probe=490e3a1b0a) | Dec 23, 2020 |
| Fujitsu       | FMVNFA50                    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| HP            | Pavilion TS 15              | [aea4de88ed](https://linux-hardware.org/?probe=aea4de88ed) | Dec 22, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0RK1... | [0377183ebd](https://linux-hardware.org/?probe=0377183ebd) | Dec 20, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0RK1... | [17467ac4ff](https://linux-hardware.org/?probe=17467ac4ff) | Dec 20, 2020 |
| Toshiba       | Satellite C55D-A            | [f29fb73181](https://linux-hardware.org/?probe=f29fb73181) | Dec 20, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8402e6dc04](https://linux-hardware.org/?probe=8402e6dc04) | Dec 18, 2020 |
| Acer          | Aspire 4720Z                | [88bd8075b2](https://linux-hardware.org/?probe=88bd8075b2) | Dec 16, 2020 |
| Acer          | Aspire 4720Z                | [93cfeab463](https://linux-hardware.org/?probe=93cfeab463) | Dec 16, 2020 |
| Sony          | VGN-S5XP_B                  | [50c6c9d78a](https://linux-hardware.org/?probe=50c6c9d78a) | Dec 15, 2020 |
| ASUSTek       | GL553VD                     | [8cf11c15f8](https://linux-hardware.org/?probe=8cf11c15f8) | Dec 13, 2020 |
| ASUSTek       | K53SD                       | [96067d7a81](https://linux-hardware.org/?probe=96067d7a81) | Dec 13, 2020 |
| Toshiba       | NB510                       | [41d6c29f97](https://linux-hardware.org/?probe=41d6c29f97) | Dec 13, 2020 |
| Gateway       | NE56R                       | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| Acer          | Aspire 5735                 | [8e251a6942](https://linux-hardware.org/?probe=8e251a6942) | Dec 10, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WP0... | [6ee5c7543b](https://linux-hardware.org/?probe=6ee5c7543b) | Dec 10, 2020 |
| Toshiba       | Satellite C55D-A            | [1c0400a8c0](https://linux-hardware.org/?probe=1c0400a8c0) | Dec 10, 2020 |
| ASUSTek       | X58L                        | [a7fd194aaa](https://linux-hardware.org/?probe=a7fd194aaa) | Dec 07, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | [80ecb8f763](https://linux-hardware.org/?probe=80ecb8f763) | Dec 06, 2020 |
| Lenovo        | IdeaPad Z580                | [f31b40572a](https://linux-hardware.org/?probe=f31b40572a) | Dec 02, 2020 |
| Gigabyte      | W466U                       | [527d2ea4da](https://linux-hardware.org/?probe=527d2ea4da) | Nov 30, 2020 |
| Panasonic     | CF-52PGNBE2M                | [e6e31de556](https://linux-hardware.org/?probe=e6e31de556) | Nov 28, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | [503449ba47](https://linux-hardware.org/?probe=503449ba47) | Nov 27, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | [f45a6362f7](https://linux-hardware.org/?probe=f45a6362f7) | Nov 27, 2020 |
| HP            | Presario F700 (KA698EA#A... | [19fd9647b4](https://linux-hardware.org/?probe=19fd9647b4) | Nov 23, 2020 |
| HP            | Presario F700 (KA698EA#A... | [b46ffd3c2e](https://linux-hardware.org/?probe=b46ffd3c2e) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| LG Electro... | C400-G.BG21P1               | [033a9d8cd0](https://linux-hardware.org/?probe=033a9d8cd0) | Nov 19, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [bb11d08947](https://linux-hardware.org/?probe=bb11d08947) | Nov 19, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [4f73e063d1](https://linux-hardware.org/?probe=4f73e063d1) | Nov 19, 2020 |
| HP            | Pavilion TS 11              | [a71dfc4983](https://linux-hardware.org/?probe=a71dfc4983) | Nov 19, 2020 |
| HP            | ProBook 455 G7              | [86e6b8d3b3](https://linux-hardware.org/?probe=86e6b8d3b3) | Nov 18, 2020 |
| Positivo      | S14BW01                     | [13fed8ca27](https://linux-hardware.org/?probe=13fed8ca27) | Nov 17, 2020 |
| HP            | EliteBook 2570p             | [3d005c24b6](https://linux-hardware.org/?probe=3d005c24b6) | Nov 17, 2020 |
| LG Electro... | C400-G.BG21P1               | [8a24bb0ec4](https://linux-hardware.org/?probe=8a24bb0ec4) | Nov 17, 2020 |
| Gateway       | NE56R                       | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| Toshiba       | Satellite L20               | [70c077066e](https://linux-hardware.org/?probe=70c077066e) | Nov 12, 2020 |
| HP            | ProBook 4720s               | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| Dell          | Inspiron 5423               | [3bd134ed30](https://linux-hardware.org/?probe=3bd134ed30) | Nov 11, 2020 |
| Unknown       | Unknown                     | [5ecd7c84ac](https://linux-hardware.org/?probe=5ecd7c84ac) | Nov 09, 2020 |
| Unknown       | Unknown                     | [abc04e2dfd](https://linux-hardware.org/?probe=abc04e2dfd) | Nov 09, 2020 |
| Apple         | MacBookPro10,2              | [86e840f6cb](https://linux-hardware.org/?probe=86e840f6cb) | Nov 08, 2020 |
| HP            | Unknown                     | [1cee50e485](https://linux-hardware.org/?probe=1cee50e485) | Nov 07, 2020 |
| Sony          | VGN-S5XP_B                  | [62453951ca](https://linux-hardware.org/?probe=62453951ca) | Nov 06, 2020 |
| Apple         | MacBookPro10,2              | [20951f6ce6](https://linux-hardware.org/?probe=20951f6ce6) | Nov 05, 2020 |
| Samsung       | SX11S                       | [7946db3be4](https://linux-hardware.org/?probe=7946db3be4) | Nov 05, 2020 |
| Samsung       | R530/R730/P530              | [f83b2806d0](https://linux-hardware.org/?probe=f83b2806d0) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| HP            | 650                         | [d1e41ec5c0](https://linux-hardware.org/?probe=d1e41ec5c0) | Nov 03, 2020 |
| Acer          | AOD257                      | [a45ddcc3ab](https://linux-hardware.org/?probe=a45ddcc3ab) | Nov 03, 2020 |
| Acer          | AOD257                      | [3daaf2fdad](https://linux-hardware.org/?probe=3daaf2fdad) | Nov 02, 2020 |
| Samsung       | RV408/RV508                 | [208f929309](https://linux-hardware.org/?probe=208f929309) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| ASUSTek       | E200HA                      | [7fd48df4aa](https://linux-hardware.org/?probe=7fd48df4aa) | Oct 31, 2020 |
| Lenovo        | 100-14IBY 80R7              | [2358ab2c86](https://linux-hardware.org/?probe=2358ab2c86) | Oct 31, 2020 |
| Lenovo        | 100-14IBY 80R7              | [48cb3a624d](https://linux-hardware.org/?probe=48cb3a624d) | Oct 31, 2020 |
| Fujitsu Si... | AMILO Li 2727               | [3e90cc2ba4](https://linux-hardware.org/?probe=3e90cc2ba4) | Oct 31, 2020 |
| Samsung       | N150P/N210P/N220P           | [986ac8d550](https://linux-hardware.org/?probe=986ac8d550) | Oct 30, 2020 |
| Toshiba       | Satellite L305              | [c2a545a417](https://linux-hardware.org/?probe=c2a545a417) | Oct 30, 2020 |
| Dell          | Inspiron 5759               | [a9f65003ad](https://linux-hardware.org/?probe=a9f65003ad) | Oct 29, 2020 |
| Samsung       | R530/R730/P530              | [855274d6b0](https://linux-hardware.org/?probe=855274d6b0) | Oct 29, 2020 |
| Notebook      | W740SU                      | [cd23f8c64d](https://linux-hardware.org/?probe=cd23f8c64d) | Oct 28, 2020 |
| Alienware     | 13 R3                       | [c0fc10a320](https://linux-hardware.org/?probe=c0fc10a320) | Oct 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS8CH0... | [bd938bf5fd](https://linux-hardware.org/?probe=bd938bf5fd) | Oct 28, 2020 |
| Positivo      | H14BT58                     | [84c73b4beb](https://linux-hardware.org/?probe=84c73b4beb) | Oct 27, 2020 |
| Itautec       | Infoway                     | [b67c3f6870](https://linux-hardware.org/?probe=b67c3f6870) | Oct 27, 2020 |
| MSI           | U180                        | [7b3f357ff5](https://linux-hardware.org/?probe=7b3f357ff5) | Oct 26, 2020 |
| Toshiba       | Satellite L20               | [9d18447b9c](https://linux-hardware.org/?probe=9d18447b9c) | Oct 26, 2020 |
| Toshiba       | Satellite L30               | [0504cfe362](https://linux-hardware.org/?probe=0504cfe362) | Oct 26, 2020 |
| Lenovo        | G575 4383                   | [43b5c51358](https://linux-hardware.org/?probe=43b5c51358) | Oct 25, 2020 |
| Acer          | Aspire F5-573               | [60b785b9cf](https://linux-hardware.org/?probe=60b785b9cf) | Oct 25, 2020 |
| Acer          | Extensa 4620                | [62e829d249](https://linux-hardware.org/?probe=62e829d249) | Oct 22, 2020 |
| Notebook      | W54_55SU1,SUW               | [9655c9ef29](https://linux-hardware.org/?probe=9655c9ef29) | Oct 21, 2020 |
| HP            | Presario V5000 (RE317EA#... | [87b9f12d09](https://linux-hardware.org/?probe=87b9f12d09) | Oct 19, 2020 |
| HP            | Presario V5000 (RE317EA#... | [e09f71e34f](https://linux-hardware.org/?probe=e09f71e34f) | Oct 19, 2020 |
| Acer          | Aspire E1-532P              | [95778c93aa](https://linux-hardware.org/?probe=95778c93aa) | Oct 18, 2020 |
| HP            | Pavilion zd8000 (EL017EA... | [944d295a6b](https://linux-hardware.org/?probe=944d295a6b) | Oct 16, 2020 |
| Toshiba       | Satellite L840              | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| Acer          | Extensa 4620                | [dd858548d7](https://linux-hardware.org/?probe=dd858548d7) | Oct 15, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | [a422be5fc0](https://linux-hardware.org/?probe=a422be5fc0) | Oct 15, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | [1717667731](https://linux-hardware.org/?probe=1717667731) | Oct 13, 2020 |
| LG Electro... | C400-G.BG21P1               | [feb6bd4cac](https://linux-hardware.org/?probe=feb6bd4cac) | Oct 13, 2020 |
| LAMINA        | T-1012B NORD                | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| Google        | Wolf                        | [0ebdfebf96](https://linux-hardware.org/?probe=0ebdfebf96) | Oct 10, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | [03d64c9c3d](https://linux-hardware.org/?probe=03d64c9c3d) | Oct 10, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | [5171d8bc33](https://linux-hardware.org/?probe=5171d8bc33) | Oct 08, 2020 |
| HP            | Pavilion dv6                | [0d0a5ac639](https://linux-hardware.org/?probe=0d0a5ac639) | Oct 07, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | [5e75a35a7d](https://linux-hardware.org/?probe=5e75a35a7d) | Oct 07, 2020 |
| HP            | Unknown                     | [6ff5164672](https://linux-hardware.org/?probe=6ff5164672) | Oct 07, 2020 |
| HP            | Unknown                     | [3815163813](https://linux-hardware.org/?probe=3815163813) | Oct 06, 2020 |
| Dell          | Latitude D630               | [df80a0678a](https://linux-hardware.org/?probe=df80a0678a) | Oct 04, 2020 |
| HP            | Laptop 15-da2xxx            | [a071c6ca32](https://linux-hardware.org/?probe=a071c6ca32) | Sep 30, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | [adb08b74c2](https://linux-hardware.org/?probe=adb08b74c2) | Sep 28, 2020 |
| Panasonic     | CF-31JAGAX1M                | [50fe0189f0](https://linux-hardware.org/?probe=50fe0189f0) | Sep 27, 2020 |
| ASUSTek       | X202EP                      | [7003257b9c](https://linux-hardware.org/?probe=7003257b9c) | Sep 26, 2020 |
| Dell          | Inspiron 1440               | [863493a36c](https://linux-hardware.org/?probe=863493a36c) | Sep 25, 2020 |
| Fujitsu       | LIFEBOOK P702               | [4f2bb45d77](https://linux-hardware.org/?probe=4f2bb45d77) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57e9fe3f34](https://linux-hardware.org/?probe=57e9fe3f34) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [2c253a5689](https://linux-hardware.org/?probe=2c253a5689) | Sep 23, 2020 |
| Samsung       | N230                        | [d4ba29fa0c](https://linux-hardware.org/?probe=d4ba29fa0c) | Sep 23, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [d62d875657](https://linux-hardware.org/?probe=d62d875657) | Sep 22, 2020 |
| Samsung       | N230                        | [786e9275d0](https://linux-hardware.org/?probe=786e9275d0) | Sep 22, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [cb4d6ae384](https://linux-hardware.org/?probe=cb4d6ae384) | Sep 22, 2020 |
| Dell          | Inspiron 1440               | [c30f194de1](https://linux-hardware.org/?probe=c30f194de1) | Sep 22, 2020 |
| Apple         | MacBook3,1                  | [900daa65d7](https://linux-hardware.org/?probe=900daa65d7) | Sep 20, 2020 |
| Fujitsu       | FMVA05008                   | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| Lenovo        | 3000 N200 0769ALU           | [16fb38706f](https://linux-hardware.org/?probe=16fb38706f) | Sep 17, 2020 |
| ASUSTek       | 1015PE                      | [9328bb0c6a](https://linux-hardware.org/?probe=9328bb0c6a) | Sep 16, 2020 |
| ASUSTek       | X202EP                      | [7331377f2b](https://linux-hardware.org/?probe=7331377f2b) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [bb9ff1e41f](https://linux-hardware.org/?probe=bb9ff1e41f) | Sep 15, 2020 |
| Sony          | VPCEG25EN                   | [10bd76f50c](https://linux-hardware.org/?probe=10bd76f50c) | Sep 14, 2020 |
| Acer          | Aspire 3050                 | [4310240814](https://linux-hardware.org/?probe=4310240814) | Sep 13, 2020 |
| Acer          | Aspire 3050                 | [dc7c7827ea](https://linux-hardware.org/?probe=dc7c7827ea) | Sep 13, 2020 |
| ASUSTek       | F7L                         | [0190224dc8](https://linux-hardware.org/?probe=0190224dc8) | Sep 12, 2020 |
| Dell          | MXG071                      | [5fc63c5480](https://linux-hardware.org/?probe=5fc63c5480) | Sep 12, 2020 |
| Apple         | MacBookPro10,2              | [3bc9d8ad1e](https://linux-hardware.org/?probe=3bc9d8ad1e) | Sep 10, 2020 |
| ASUSTek       | P553UA                      | [fca37591fc](https://linux-hardware.org/?probe=fca37591fc) | Sep 10, 2020 |
| Samsung       | SX11S                       | [748c8347e7](https://linux-hardware.org/?probe=748c8347e7) | Sep 10, 2020 |
| Samsung       | SX11S                       | [de5f3f5244](https://linux-hardware.org/?probe=de5f3f5244) | Sep 10, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | [2cca042481](https://linux-hardware.org/?probe=2cca042481) | Sep 10, 2020 |
| Lenovo        | Y50-70 20378                | [84a053df62](https://linux-hardware.org/?probe=84a053df62) | Sep 09, 2020 |
| Dell          | Latitude E5450              | [d5eebfddb5](https://linux-hardware.org/?probe=d5eebfddb5) | Sep 07, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c2a66820da](https://linux-hardware.org/?probe=c2a66820da) | Sep 06, 2020 |
| Google        | Gandof                      | [6b79edadc5](https://linux-hardware.org/?probe=6b79edadc5) | Sep 04, 2020 |
| HP            | Compaq Presario CQ50        | [18e30a3f69](https://linux-hardware.org/?probe=18e30a3f69) | Sep 02, 2020 |
| Acer          | Aspire ES1-522              | [c5e6143bbd](https://linux-hardware.org/?probe=c5e6143bbd) | Sep 02, 2020 |
| Acer          | Aspire ES1-523              | [e0afac617e](https://linux-hardware.org/?probe=e0afac617e) | Aug 31, 2020 |
| Dell          | XPS 13 9300                 | [121fd4e00e](https://linux-hardware.org/?probe=121fd4e00e) | Aug 30, 2020 |
| Dell          | XPS 13 9300                 | [3a0e9bb81b](https://linux-hardware.org/?probe=3a0e9bb81b) | Aug 30, 2020 |
| Toshiba       | Satellite L20               | [aa53cdd994](https://linux-hardware.org/?probe=aa53cdd994) | Aug 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5e37d8f34b](https://linux-hardware.org/?probe=5e37d8f34b) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | [ea7a9a7e0f](https://linux-hardware.org/?probe=ea7a9a7e0f) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | [b7beb93997](https://linux-hardware.org/?probe=b7beb93997) | Aug 28, 2020 |
| Apple         | MacBookPro10,2              | [b5a228d9bf](https://linux-hardware.org/?probe=b5a228d9bf) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [607ce70f10](https://linux-hardware.org/?probe=607ce70f10) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8dcd639b58](https://linux-hardware.org/?probe=8dcd639b58) | Aug 26, 2020 |
| Acer          | Aspire ES1-523              | [b0a8136f20](https://linux-hardware.org/?probe=b0a8136f20) | Aug 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [50f1173d1b](https://linux-hardware.org/?probe=50f1173d1b) | Aug 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [95dde54ab4](https://linux-hardware.org/?probe=95dde54ab4) | Aug 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1c32470733](https://linux-hardware.org/?probe=1c32470733) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [e95b44a1c2](https://linux-hardware.org/?probe=e95b44a1c2) | Aug 23, 2020 |
| Acer          | Aspire 5735                 | [043232c833](https://linux-hardware.org/?probe=043232c833) | Aug 20, 2020 |
| ASUSTek       | K50C                        | [dd9986741e](https://linux-hardware.org/?probe=dd9986741e) | Aug 19, 2020 |
| HP            | EliteBook 6930p             | [955c527ef0](https://linux-hardware.org/?probe=955c527ef0) | Aug 19, 2020 |
| Acer          | Aspire A315-21              | [72e40559e9](https://linux-hardware.org/?probe=72e40559e9) | Aug 17, 2020 |
| Digibras      | NH4CU03                     | [3ba7006e38](https://linux-hardware.org/?probe=3ba7006e38) | Aug 15, 2020 |
| HP            | ProBook 440 G2              | [18e6bfd3b5](https://linux-hardware.org/?probe=18e6bfd3b5) | Aug 14, 2020 |
| Toshiba       | Satellite C855D             | [ca848be2f0](https://linux-hardware.org/?probe=ca848be2f0) | Aug 12, 2020 |
| Toshiba       | Satellite C855D             | [723c72f289](https://linux-hardware.org/?probe=723c72f289) | Aug 12, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [a8401cc827](https://linux-hardware.org/?probe=a8401cc827) | Aug 12, 2020 |
| Philco        | 14M-W549                    | [d69911bb55](https://linux-hardware.org/?probe=d69911bb55) | Aug 12, 2020 |
| Lenovo        | ThinkPad T490 20N2000NMX    | [8f21de6e06](https://linux-hardware.org/?probe=8f21de6e06) | Aug 05, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [f8e01e00f5](https://linux-hardware.org/?probe=f8e01e00f5) | Aug 05, 2020 |
| Toshiba       | Satellite L310              | [eba63dd806](https://linux-hardware.org/?probe=eba63dd806) | Aug 03, 2020 |
| Samsung       | N150/N210/N220              | [e15da00326](https://linux-hardware.org/?probe=e15da00326) | Aug 02, 2020 |
| Positivo      | CHT14B                      | [bb848a6069](https://linux-hardware.org/?probe=bb848a6069) | Aug 01, 2020 |
| Apple         | MacBookPro10,2              | [29919d9aa9](https://linux-hardware.org/?probe=29919d9aa9) | Jul 30, 2020 |
| HP            | 245 G6                      | [eb51696edd](https://linux-hardware.org/?probe=eb51696edd) | Jul 29, 2020 |
| ASUSTek       | K52Je                       | [5e4fd0731b](https://linux-hardware.org/?probe=5e4fd0731b) | Jul 29, 2020 |
| Dell          | Latitude C840               | [5489df545b](https://linux-hardware.org/?probe=5489df545b) | Jul 28, 2020 |
| Dell          | Latitude C840               | [8a43fc9d72](https://linux-hardware.org/?probe=8a43fc9d72) | Jul 28, 2020 |
| ASUSTek       | X101CH                      | [92c248f423](https://linux-hardware.org/?probe=92c248f423) | Jul 27, 2020 |
| ASUSTek       | X101CH                      | [a729294016](https://linux-hardware.org/?probe=a729294016) | Jul 27, 2020 |
| Acer          | AO722                       | [75b6a0b9d5](https://linux-hardware.org/?probe=75b6a0b9d5) | Jul 27, 2020 |
| HP            | ProBook 445 G7              | [6507b9ca49](https://linux-hardware.org/?probe=6507b9ca49) | Jul 25, 2020 |
| Acer          | V5-171                      | [1f30ec8b2e](https://linux-hardware.org/?probe=1f30ec8b2e) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | [8b84442168](https://linux-hardware.org/?probe=8b84442168) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | [468608973e](https://linux-hardware.org/?probe=468608973e) | Jul 25, 2020 |
| Acer          | Aspire F5-573               | [af6c0b4c67](https://linux-hardware.org/?probe=af6c0b4c67) | Jul 24, 2020 |
| Positivo      | H14BT58                     | [3cb433c2cc](https://linux-hardware.org/?probe=3cb433c2cc) | Jul 24, 2020 |
| ASUSTek       | 1015BX                      | [5f48c6c53b](https://linux-hardware.org/?probe=5f48c6c53b) | Jul 24, 2020 |
| Apple         | MacBookPro10,2              | [a10d8d5d4f](https://linux-hardware.org/?probe=a10d8d5d4f) | Jul 22, 2020 |
| Apple         | MacBookPro10,2              | [d9470e64f2](https://linux-hardware.org/?probe=d9470e64f2) | Jul 22, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [3d1f4e7cb8](https://linux-hardware.org/?probe=3d1f4e7cb8) | Jul 21, 2020 |
| Apple         | MacBookPro10,2              | [ee73a556b1](https://linux-hardware.org/?probe=ee73a556b1) | Jul 19, 2020 |
| Apple         | MacBookPro10,2              | [33e46bd029](https://linux-hardware.org/?probe=33e46bd029) | Jul 19, 2020 |
| Dell          | Studio 1555                 | [0d511c045e](https://linux-hardware.org/?probe=0d511c045e) | Jul 16, 2020 |
| Dell          | Latitude D520               | [c41f563801](https://linux-hardware.org/?probe=c41f563801) | Jul 16, 2020 |
| ASUSTek       | GL553VD                     | [448b62138b](https://linux-hardware.org/?probe=448b62138b) | Jul 14, 2020 |
| ASUSTek       | Q302LA                      | [c453eada8f](https://linux-hardware.org/?probe=c453eada8f) | Jul 09, 2020 |
| HP            | Notebook                    | [10cadcd9b6](https://linux-hardware.org/?probe=10cadcd9b6) | Jul 09, 2020 |
| Toshiba       | Satellite C55D-A            | [9e35eb4bff](https://linux-hardware.org/?probe=9e35eb4bff) | Jul 08, 2020 |
| HP            | Pavilion 15                 | [9f54b2c875](https://linux-hardware.org/?probe=9f54b2c875) | Jul 06, 2020 |
| Acer          | Swift SF314-52G             | [8cd6b05831](https://linux-hardware.org/?probe=8cd6b05831) | Jul 03, 2020 |
| HP            | Pavilion dv6000 (RD870AV... | [921ea4c212](https://linux-hardware.org/?probe=921ea4c212) | Jul 03, 2020 |
| Acer          | Aspire ES1-331              | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| HP            | ProBook 450 G6              | [193cbfc862](https://linux-hardware.org/?probe=193cbfc862) | Jun 30, 2020 |
| HP            | Compaq 615                  | [38dc3f0f55](https://linux-hardware.org/?probe=38dc3f0f55) | Jun 29, 2020 |
| Toshiba       | Satellite L20               | [06b394c839](https://linux-hardware.org/?probe=06b394c839) | Jun 27, 2020 |
| Dell          | XPS 13 7390                 | [598acef23f](https://linux-hardware.org/?probe=598acef23f) | Jun 26, 2020 |
| ASUSTek       | 1011PX                      | [868f757bd9](https://linux-hardware.org/?probe=868f757bd9) | Jun 25, 2020 |
| Toshiba       | Satellite L20               | [189c3fc3a9](https://linux-hardware.org/?probe=189c3fc3a9) | Jun 25, 2020 |
| HP            | Compaq 6710b (RM338UT#AB... | [997dd3289c](https://linux-hardware.org/?probe=997dd3289c) | Jun 25, 2020 |
| OEM           | I41SI                       | [04a393c6ca](https://linux-hardware.org/?probe=04a393c6ca) | Jun 25, 2020 |
| HP            | Compaq 615                  | [d24b727a5b](https://linux-hardware.org/?probe=d24b727a5b) | Jun 24, 2020 |
| Acer          | Aspire one                  | [3eefd3d4df](https://linux-hardware.org/?probe=3eefd3d4df) | Jun 23, 2020 |
| Acer          | Aspire one                  | [68e2ee0c29](https://linux-hardware.org/?probe=68e2ee0c29) | Jun 23, 2020 |
| ASUSTek       | K52Je                       | [401a42e02d](https://linux-hardware.org/?probe=401a42e02d) | Jun 21, 2020 |
| HP            | Laptop 15-bw0xx             | [f7cfb3c14a](https://linux-hardware.org/?probe=f7cfb3c14a) | Jun 20, 2020 |
| OEM           | I41SI                       | [900d32d15b](https://linux-hardware.org/?probe=900d32d15b) | Jun 20, 2020 |
| Toshiba       | Satellite L20               | [412df08a10](https://linux-hardware.org/?probe=412df08a10) | Jun 18, 2020 |
| Apple         | MacBookPro8,1               | [93ced4c964](https://linux-hardware.org/?probe=93ced4c964) | Jun 18, 2020 |
| HP            | ProBook 645 G4              | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| Acer          | Aspire A515-51G             | [a612626f7b](https://linux-hardware.org/?probe=a612626f7b) | Jun 16, 2020 |
| HP            | ProBook 645 G4              | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| Dixonsxp      | Unknown                     | [dbbb512dc1](https://linux-hardware.org/?probe=dbbb512dc1) | Jun 11, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [cf72cf6048](https://linux-hardware.org/?probe=cf72cf6048) | Jun 11, 2020 |
| Toshiba       | Satellite L735              | [71df99e435](https://linux-hardware.org/?probe=71df99e435) | Jun 11, 2020 |
| HP            | Compaq Presario C700        | [5473d1a8e3](https://linux-hardware.org/?probe=5473d1a8e3) | Jun 10, 2020 |
| HP            | Compaq Presario C700        | [ad60c0409d](https://linux-hardware.org/?probe=ad60c0409d) | Jun 09, 2020 |
| Acer          | Aspire 5734Z                | [6af54cea15](https://linux-hardware.org/?probe=6af54cea15) | Jun 07, 2020 |
| Samsung       | RV413/RV513                 | [7c9043ca0a](https://linux-hardware.org/?probe=7c9043ca0a) | Jun 04, 2020 |
| Sony          | VGN-P610                    | [950506fe40](https://linux-hardware.org/?probe=950506fe40) | Jun 04, 2020 |
| HP            | Pavilion 15                 | [131d6a40c2](https://linux-hardware.org/?probe=131d6a40c2) | Jun 03, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | [ea9fb1590a](https://linux-hardware.org/?probe=ea9fb1590a) | Jun 03, 2020 |
| Sony          | VGN-P610                    | [6c66c60336](https://linux-hardware.org/?probe=6c66c60336) | Jun 02, 2020 |
| HUAWEI        | KPL-W0X                     | [89038c4214](https://linux-hardware.org/?probe=89038c4214) | Jun 01, 2020 |
| ASUSTek       | K45VM                       | [15c4339e00](https://linux-hardware.org/?probe=15c4339e00) | May 30, 2020 |
| HP            | Pavilion dv5                | [41390482f3](https://linux-hardware.org/?probe=41390482f3) | May 30, 2020 |
| Positivo      | S14CT01                     | [027689152b](https://linux-hardware.org/?probe=027689152b) | May 28, 2020 |
| HP            | Pavilion dv6                | [2431a0aa32](https://linux-hardware.org/?probe=2431a0aa32) | May 28, 2020 |
| ASUSTek       | 1015B                       | [4a7ecd1578](https://linux-hardware.org/?probe=4a7ecd1578) | May 28, 2020 |
| ASUSTek       | 1015B                       | [51f3309bfb](https://linux-hardware.org/?probe=51f3309bfb) | May 28, 2020 |
| Dell          | Latitude C840               | [f56665d93f](https://linux-hardware.org/?probe=f56665d93f) | May 27, 2020 |
| ASUSTek       | 1015B                       | [73d7cd6398](https://linux-hardware.org/?probe=73d7cd6398) | May 27, 2020 |
| ASUSTek       | 1015B                       | [a3759de413](https://linux-hardware.org/?probe=a3759de413) | May 27, 2020 |
| ASUSTek       | 1015B                       | [63b8cdead7](https://linux-hardware.org/?probe=63b8cdead7) | May 27, 2020 |
| Acer          | Aspire E1-531               | [663bfb0664](https://linux-hardware.org/?probe=663bfb0664) | May 27, 2020 |
| ASUSTek       | 1015B                       | [26bdbf2454](https://linux-hardware.org/?probe=26bdbf2454) | May 27, 2020 |
| ASUSTek       | 1015B                       | [cb7235636f](https://linux-hardware.org/?probe=cb7235636f) | May 27, 2020 |
| ASUSTek       | 1015B                       | [0493e9e9bc](https://linux-hardware.org/?probe=0493e9e9bc) | May 27, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [acacfa8d27](https://linux-hardware.org/?probe=acacfa8d27) | May 25, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [0686c2c434](https://linux-hardware.org/?probe=0686c2c434) | May 25, 2020 |
| HP            | Pavilion dv6                | [d2b5ccc307](https://linux-hardware.org/?probe=d2b5ccc307) | May 25, 2020 |
| Dell          | Latitude D420               | [40458ce50c](https://linux-hardware.org/?probe=40458ce50c) | May 25, 2020 |
| Dell          | Latitude C840               | [94307b80af](https://linux-hardware.org/?probe=94307b80af) | May 22, 2020 |
| Positivo      | Smash                       | [662402d21c](https://linux-hardware.org/?probe=662402d21c) | May 22, 2020 |
| Fujitsu Si... | AMILO Pi 1505               | [f231ceaf4a](https://linux-hardware.org/?probe=f231ceaf4a) | May 21, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | [78df8e8526](https://linux-hardware.org/?probe=78df8e8526) | May 21, 2020 |
| Fujitsu Si... | AMILO Pi 1505               | [4010948e4f](https://linux-hardware.org/?probe=4010948e4f) | May 20, 2020 |
| Dell          | Inspiron MM061              | [bdd3ec7fdf](https://linux-hardware.org/?probe=bdd3ec7fdf) | May 19, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | [a68c9e0a74](https://linux-hardware.org/?probe=a68c9e0a74) | May 18, 2020 |
| ASUSTek       | X201E                       | [aa1e3973cf](https://linux-hardware.org/?probe=aa1e3973cf) | May 18, 2020 |
| ASUSTek       | 1001HA                      | [973de18bf0](https://linux-hardware.org/?probe=973de18bf0) | May 17, 2020 |
| ASUSTek       | 1001HA                      | [ec49101a42](https://linux-hardware.org/?probe=ec49101a42) | May 17, 2020 |
| Packard Be... | EN Butterfly s              | [587286fd1b](https://linux-hardware.org/?probe=587286fd1b) | May 17, 2020 |
| ASUSTek       | F5N                         | [19a648832e](https://linux-hardware.org/?probe=19a648832e) | May 15, 2020 |
| Sony          | VGN-NR430E                  | [6e3da2829e](https://linux-hardware.org/?probe=6e3da2829e) | May 15, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | [c0cf69cb37](https://linux-hardware.org/?probe=c0cf69cb37) | May 13, 2020 |
| Positivo      | EC10IS1                     | [b66b7b1fe1](https://linux-hardware.org/?probe=b66b7b1fe1) | May 12, 2020 |
| ASUSTek       | F5N                         | [81878f74de](https://linux-hardware.org/?probe=81878f74de) | May 10, 2020 |
| Toshiba       | NB505                       | [26eaa80c8a](https://linux-hardware.org/?probe=26eaa80c8a) | May 10, 2020 |
| Acer          | Aspire 5742G                | [0e50f534db](https://linux-hardware.org/?probe=0e50f534db) | May 10, 2020 |
| Dixonsxp      | Unknown                     | [7ee061c41d](https://linux-hardware.org/?probe=7ee061c41d) | May 09, 2020 |
| HP            | Pavilion dv2500             | [794202d954](https://linux-hardware.org/?probe=794202d954) | May 08, 2020 |
| Dell          | Latitude D810               | [7391f06281](https://linux-hardware.org/?probe=7391f06281) | May 07, 2020 |
| HP            | Notebook                    | [0cab8a6d17](https://linux-hardware.org/?probe=0cab8a6d17) | May 07, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Dell          | Latitude D810               | [da4ecfc379](https://linux-hardware.org/?probe=da4ecfc379) | May 06, 2020 |
| Dixonsxp      | Unknown                     | [baf1cb6830](https://linux-hardware.org/?probe=baf1cb6830) | May 06, 2020 |
| Positivo      | Mobile                      | [d5e1de02bb](https://linux-hardware.org/?probe=d5e1de02bb) | May 05, 2020 |
| Positivo      | Mobile                      | [814d59f2a0](https://linux-hardware.org/?probe=814d59f2a0) | May 05, 2020 |
| Positivo      | Mobile                      | [84338255ae](https://linux-hardware.org/?probe=84338255ae) | May 05, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Positivo      | Smash                       | [02a9fd0d4a](https://linux-hardware.org/?probe=02a9fd0d4a) | May 03, 2020 |
| Positivo      | Smash                       | [f9734c79af](https://linux-hardware.org/?probe=f9734c79af) | May 03, 2020 |
| Toshiba       | TECRA A3X                   | [52ea725f65](https://linux-hardware.org/?probe=52ea725f65) | May 02, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| Acer          | Extensa 5630                | [2040fe8553](https://linux-hardware.org/?probe=2040fe8553) | Apr 30, 2020 |
| Toshiba       | TECRA A8                    | [6110d010ad](https://linux-hardware.org/?probe=6110d010ad) | Apr 28, 2020 |
| Dell          | Inspiron 1545               | [0fc9a3fc11](https://linux-hardware.org/?probe=0fc9a3fc11) | Apr 28, 2020 |
| Packard Be... | EasyNote_GN45               | [a06ff5e1c7](https://linux-hardware.org/?probe=a06ff5e1c7) | Apr 27, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [1a00b67e81](https://linux-hardware.org/?probe=1a00b67e81) | Apr 27, 2020 |
| Standard      | EF20EA                      | [11882357e0](https://linux-hardware.org/?probe=11882357e0) | Apr 26, 2020 |
| Apple         | MacBookPro9,2               | [74edb3ce25](https://linux-hardware.org/?probe=74edb3ce25) | Apr 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [86e4dd0977](https://linux-hardware.org/?probe=86e4dd0977) | Apr 26, 2020 |
| Toshiba       | Satellite U500              | [cbb92d0bb3](https://linux-hardware.org/?probe=cbb92d0bb3) | Apr 25, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [fb56e66f65](https://linux-hardware.org/?probe=fb56e66f65) | Apr 24, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [c194d8e6be](https://linux-hardware.org/?probe=c194d8e6be) | Apr 24, 2020 |
| MSI           | PR200                       | [4da6b718ee](https://linux-hardware.org/?probe=4da6b718ee) | Apr 22, 2020 |
| MSI           | PR200                       | [7b74d9f38e](https://linux-hardware.org/?probe=7b74d9f38e) | Apr 22, 2020 |
| MSI           | PR200                       | [bd6e464307](https://linux-hardware.org/?probe=bd6e464307) | Apr 22, 2020 |
| Samsung       | 600B4B/600B5B               | [66fdcd74f6](https://linux-hardware.org/?probe=66fdcd74f6) | Apr 22, 2020 |
| HP            | Compaq CQ58                 | [82172cc7b5](https://linux-hardware.org/?probe=82172cc7b5) | Apr 21, 2020 |
| Toshiba       | Satellite Pro S500          | [2acae4110c](https://linux-hardware.org/?probe=2acae4110c) | Apr 20, 2020 |
| Toshiba       | Satellite Pro S500          | [01b278ea81](https://linux-hardware.org/?probe=01b278ea81) | Apr 20, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [6e83174540](https://linux-hardware.org/?probe=6e83174540) | Apr 18, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [878a9628b9](https://linux-hardware.org/?probe=878a9628b9) | Apr 18, 2020 |
| ASUSTek       | K52Je                       | [2954b09134](https://linux-hardware.org/?probe=2954b09134) | Apr 17, 2020 |
| ASUSTek       | K52Je                       | [bd4175ea08](https://linux-hardware.org/?probe=bd4175ea08) | Apr 17, 2020 |
| Toshiba       | NB505                       | [174dd8b4cd](https://linux-hardware.org/?probe=174dd8b4cd) | Apr 16, 2020 |
| HP            | EliteBook 840 G1            | [4998a5a5b5](https://linux-hardware.org/?probe=4998a5a5b5) | Apr 15, 2020 |
| Dell          | Inspiron 13-5378            | [6500bad3f7](https://linux-hardware.org/?probe=6500bad3f7) | Apr 14, 2020 |
| Toshiba       | NB505                       | [a28c9ef432](https://linux-hardware.org/?probe=a28c9ef432) | Apr 12, 2020 |
| HP            | Compaq Presario CQ50        | [6c0d513235](https://linux-hardware.org/?probe=6c0d513235) | Apr 12, 2020 |
| ASUSTek       | A6R                         | [e298b642f1](https://linux-hardware.org/?probe=e298b642f1) | Apr 11, 2020 |
| Ematic        | EW147                       | [ea27684494](https://linux-hardware.org/?probe=ea27684494) | Apr 11, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | [734c5c160a](https://linux-hardware.org/?probe=734c5c160a) | Apr 11, 2020 |
| Ematic        | EW147                       | [3a6dad2abe](https://linux-hardware.org/?probe=3a6dad2abe) | Apr 11, 2020 |
| Ematic        | EW147                       | [a6d2f7cfcf](https://linux-hardware.org/?probe=a6d2f7cfcf) | Apr 11, 2020 |
| Phoenix/Si... | M7X0SU                      | [c86682fc32](https://linux-hardware.org/?probe=c86682fc32) | Apr 11, 2020 |
| ASUSTek       | X550LC                      | [05de338581](https://linux-hardware.org/?probe=05de338581) | Apr 09, 2020 |
| ASUSTek       | 1000H                       | [ee3f7c6ddc](https://linux-hardware.org/?probe=ee3f7c6ddc) | Apr 09, 2020 |
| ASUSTek       | 1005HA                      | [94dda7bdc8](https://linux-hardware.org/?probe=94dda7bdc8) | Apr 08, 2020 |
| Toshiba       | NB505                       | [c52e8296ad](https://linux-hardware.org/?probe=c52e8296ad) | Apr 06, 2020 |
| HP            | Pavilion 15                 | [b7c8f5e391](https://linux-hardware.org/?probe=b7c8f5e391) | Apr 05, 2020 |
| HP            | Pavilion 15                 | [7c02c74049](https://linux-hardware.org/?probe=7c02c74049) | Apr 05, 2020 |
| HP            | Pavilion 15                 | [bbd258ed84](https://linux-hardware.org/?probe=bbd258ed84) | Apr 05, 2020 |
| HP            | Pavilion 15                 | [812ce15917](https://linux-hardware.org/?probe=812ce15917) | Apr 05, 2020 |
| Apple         | MacBookPro5,5               | [9f7081cc76](https://linux-hardware.org/?probe=9f7081cc76) | Apr 04, 2020 |
| Toshiba       | Satellite Pro S500          | [053784b92f](https://linux-hardware.org/?probe=053784b92f) | Apr 03, 2020 |
| HP            | Pavilion dm1                | [f3ade8b8f4](https://linux-hardware.org/?probe=f3ade8b8f4) | Apr 02, 2020 |
| ASUSTek       | X550LC                      | [e8f51bac70](https://linux-hardware.org/?probe=e8f51bac70) | Apr 01, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [b112c2d6c6](https://linux-hardware.org/?probe=b112c2d6c6) | Mar 30, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [46150bf014](https://linux-hardware.org/?probe=46150bf014) | Mar 30, 2020 |
| ASUSTek       | X550LC                      | [a33d65ebf9](https://linux-hardware.org/?probe=a33d65ebf9) | Mar 29, 2020 |
| ASUSTek       | X550LC                      | [ceb9ae3821](https://linux-hardware.org/?probe=ceb9ae3821) | Mar 29, 2020 |
| Dell          | Inspiron MM061              | [d60d4df102](https://linux-hardware.org/?probe=d60d4df102) | Mar 29, 2020 |
| Itautec       | Infoway                     | [6df484929a](https://linux-hardware.org/?probe=6df484929a) | Mar 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [90da63892f](https://linux-hardware.org/?probe=90da63892f) | Mar 28, 2020 |
| ASUSTek       | X550LC                      | [779a3bf901](https://linux-hardware.org/?probe=779a3bf901) | Mar 27, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [daf3f5783d](https://linux-hardware.org/?probe=daf3f5783d) | Mar 27, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [d86fb5acc6](https://linux-hardware.org/?probe=d86fb5acc6) | Mar 27, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [7dee8ed61e](https://linux-hardware.org/?probe=7dee8ed61e) | Mar 26, 2020 |
| Dell          | Inspiron 910                | [5a445b86f5](https://linux-hardware.org/?probe=5a445b86f5) | Mar 26, 2020 |
| Sony          | VGN-CS325J                  | [a2f2fc1b18](https://linux-hardware.org/?probe=a2f2fc1b18) | Mar 25, 2020 |
| ASUSTek       | X550LC                      | [cdcf191c24](https://linux-hardware.org/?probe=cdcf191c24) | Mar 25, 2020 |
| Toshiba       | Satellite A100              | [f7fb11c89f](https://linux-hardware.org/?probe=f7fb11c89f) | Mar 25, 2020 |
| Acer          | Aspire V3-571G              | [be88d1499a](https://linux-hardware.org/?probe=be88d1499a) | Mar 25, 2020 |
| Dell          | Inspiron 910                | [6441625d8b](https://linux-hardware.org/?probe=6441625d8b) | Mar 24, 2020 |
| Sony          | VGN-CS325J                  | [628add2bae](https://linux-hardware.org/?probe=628add2bae) | Mar 23, 2020 |
| Sony          | VGN-FE21M                   | [b117ba3f2f](https://linux-hardware.org/?probe=b117ba3f2f) | Mar 22, 2020 |
| Dell          | Inspiron 910                | [50081ceef7](https://linux-hardware.org/?probe=50081ceef7) | Mar 22, 2020 |
| Sony          | VGN-CS325J                  | [3eeafc3bdb](https://linux-hardware.org/?probe=3eeafc3bdb) | Mar 22, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [b65f9246d0](https://linux-hardware.org/?probe=b65f9246d0) | Mar 21, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [a02304934f](https://linux-hardware.org/?probe=a02304934f) | Mar 21, 2020 |
| Acer          | Aspire E1-431               | [7a4eb7e049](https://linux-hardware.org/?probe=7a4eb7e049) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | [912c22a4fd](https://linux-hardware.org/?probe=912c22a4fd) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | [3a11fa91b5](https://linux-hardware.org/?probe=3a11fa91b5) | Mar 20, 2020 |
| HP            | Compaq Presario CQ50        | [210babb2ca](https://linux-hardware.org/?probe=210babb2ca) | Mar 19, 2020 |
| HP            | Compaq Presario CQ50        | [faba377964](https://linux-hardware.org/?probe=faba377964) | Mar 19, 2020 |
| Thomson       | NEO14A-4BK64                | [a0cc23a5cf](https://linux-hardware.org/?probe=a0cc23a5cf) | Mar 19, 2020 |
| Thomson       | NEO14A-4BK64                | [38b21006a6](https://linux-hardware.org/?probe=38b21006a6) | Mar 19, 2020 |
| Dell          | Inspiron 910                | [40deae1721](https://linux-hardware.org/?probe=40deae1721) | Mar 18, 2020 |
| Toshiba       | Satellite Pro S500          | [e8d667b1cf](https://linux-hardware.org/?probe=e8d667b1cf) | Mar 17, 2020 |
| Toshiba       | Satellite Pro S500          | [1361d9dfb7](https://linux-hardware.org/?probe=1361d9dfb7) | Mar 17, 2020 |
| Toshiba       | Satellite Pro S500          | [43a588f1dd](https://linux-hardware.org/?probe=43a588f1dd) | Mar 17, 2020 |
| Toshiba       | Satellite Pro S500          | [2cdafa2543](https://linux-hardware.org/?probe=2cdafa2543) | Mar 17, 2020 |
| ASUSTek       | 1001PXD                     | [011393aea9](https://linux-hardware.org/?probe=011393aea9) | Mar 12, 2020 |
| ASUSTek       | K43E                        | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | X51R                        | [27bb6f3f14](https://linux-hardware.org/?probe=27bb6f3f14) | Mar 11, 2020 |
| ASUSTek       | K43E                        | [2e3821b18f](https://linux-hardware.org/?probe=2e3821b18f) | Mar 11, 2020 |
| Toshiba       | Satellite Pro S500          | [30880bf78e](https://linux-hardware.org/?probe=30880bf78e) | Mar 11, 2020 |
| Dell          | Inspiron 910                | [b8ec7ce084](https://linux-hardware.org/?probe=b8ec7ce084) | Mar 10, 2020 |
| Acer          | Aspire ES1-571              | [6fa4f9484a](https://linux-hardware.org/?probe=6fa4f9484a) | Mar 10, 2020 |
| ASUSTek       | K43E                        | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |
| Acer          | Aspire ES1-571              | [7980f53bfc](https://linux-hardware.org/?probe=7980f53bfc) | Mar 10, 2020 |
| Acer          | Aspire 6930G                | [0ec678525f](https://linux-hardware.org/?probe=0ec678525f) | Mar 09, 2020 |
| Dell          | Inspiron 1464               | [d6a38ddcea](https://linux-hardware.org/?probe=d6a38ddcea) | Mar 08, 2020 |
| Toshiba       | Satellite Pro S500          | [339f91031b](https://linux-hardware.org/?probe=339f91031b) | Mar 04, 2020 |
| Toshiba       | Satellite Pro S500          | [8aca087539](https://linux-hardware.org/?probe=8aca087539) | Mar 03, 2020 |
| Sony          | VPCYB15AB                   | [af5e9fd3c4](https://linux-hardware.org/?probe=af5e9fd3c4) | Mar 03, 2020 |
| ASUSTek       | GL553VD                     | [db39fea346](https://linux-hardware.org/?probe=db39fea346) | Mar 02, 2020 |
| Positivo      | MOBILE                      | [3dc5b2844f](https://linux-hardware.org/?probe=3dc5b2844f) | Feb 29, 2020 |
| HP            | Compaq Presario CQ50        | [552f694c90](https://linux-hardware.org/?probe=552f694c90) | Feb 27, 2020 |
| Positivo      | MOBILE                      | [6908d01959](https://linux-hardware.org/?probe=6908d01959) | Feb 26, 2020 |
| HP            | Compaq Presario CQ50        | [0cac2c9b86](https://linux-hardware.org/?probe=0cac2c9b86) | Feb 26, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [108b4a03ac](https://linux-hardware.org/?probe=108b4a03ac) | Feb 26, 2020 |
| Toshiba       | Satellite Pro S500          | [54921e20ad](https://linux-hardware.org/?probe=54921e20ad) | Feb 23, 2020 |
| Toshiba       | Satellite C650D             | [fff96c147a](https://linux-hardware.org/?probe=fff96c147a) | Feb 20, 2020 |
| Dell          | Latitude D630               | [81239fd39f](https://linux-hardware.org/?probe=81239fd39f) | Feb 19, 2020 |
| ASUSTek       | 1005HA                      | [ea9e3ae02c](https://linux-hardware.org/?probe=ea9e3ae02c) | Feb 18, 2020 |
| ASUSTek       | 1005HA                      | [0f5187ce04](https://linux-hardware.org/?probe=0f5187ce04) | Feb 18, 2020 |
| HP            | Stream Notebook             | [413af6cde9](https://linux-hardware.org/?probe=413af6cde9) | Feb 18, 2020 |
| HP            | Stream Notebook             | [305ee95288](https://linux-hardware.org/?probe=305ee95288) | Feb 18, 2020 |
| HP            | Stream Notebook             | [3cc3c65c80](https://linux-hardware.org/?probe=3cc3c65c80) | Feb 18, 2020 |
| Acer          | AOD257                      | [42c2447bcf](https://linux-hardware.org/?probe=42c2447bcf) | Feb 18, 2020 |
| HP            | Pavilion g6                 | [147eea4e00](https://linux-hardware.org/?probe=147eea4e00) | Feb 17, 2020 |
| Acer          | Aspire 9420                 | [eb72545df3](https://linux-hardware.org/?probe=eb72545df3) | Feb 13, 2020 |
| Acer          | Aspire 9420                 | [7321cd7d41](https://linux-hardware.org/?probe=7321cd7d41) | Feb 13, 2020 |
| ASUSTek       | GL553VD                     | [42000d4c07](https://linux-hardware.org/?probe=42000d4c07) | Feb 10, 2020 |
| Samsung       | 275E4E/275E5E               | [15d64735e6](https://linux-hardware.org/?probe=15d64735e6) | Feb 07, 2020 |
| HP            | EliteBook 8540w             | [064e671b09](https://linux-hardware.org/?probe=064e671b09) | Feb 07, 2020 |
| HP            | EliteBook 840 G1            | [9f00848eda](https://linux-hardware.org/?probe=9f00848eda) | Feb 06, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | [00e62f0a24](https://linux-hardware.org/?probe=00e62f0a24) | Feb 04, 2020 |
| ASUSTek       | GL553VD                     | [c8da6705be](https://linux-hardware.org/?probe=c8da6705be) | Feb 02, 2020 |
| Acer          | Lugano M                    | [312fa4b009](https://linux-hardware.org/?probe=312fa4b009) | Feb 02, 2020 |
| HP            | ProBook 450 G2              | [10e8be6a70](https://linux-hardware.org/?probe=10e8be6a70) | Feb 02, 2020 |
| Acer          | Aspire E1-530               | [0e64af354b](https://linux-hardware.org/?probe=0e64af354b) | Jan 30, 2020 |
| Toshiba       | Satellite Pro S500          | [93f3eefff1](https://linux-hardware.org/?probe=93f3eefff1) | Jan 27, 2020 |
| Dell          | Vostro A90                  | [26217e36fd](https://linux-hardware.org/?probe=26217e36fd) | Jan 25, 2020 |
| Dell          | Vostro A90                  | [ea2668497d](https://linux-hardware.org/?probe=ea2668497d) | Jan 25, 2020 |
| HP            | Laptop 15s-fq1xxx           | [179223c787](https://linux-hardware.org/?probe=179223c787) | Jan 21, 2020 |
| TrekStor      | Surfbook A13B               | [a5b513e810](https://linux-hardware.org/?probe=a5b513e810) | Jan 18, 2020 |
| Toshiba       | Satellite Pro S500          | [b63e1a7dee](https://linux-hardware.org/?probe=b63e1a7dee) | Jan 15, 2020 |
| Toshiba       | Satellite Pro S500          | [b8f9fdb262](https://linux-hardware.org/?probe=b8f9fdb262) | Jan 14, 2020 |
| ASUSTek       | 1015PN                      | [5619d74a6f](https://linux-hardware.org/?probe=5619d74a6f) | Jan 13, 2020 |
| Toshiba       | Satellite L20               | [271d6dbfd3](https://linux-hardware.org/?probe=271d6dbfd3) | Jan 09, 2020 |
| Toshiba       | Satellite Pro S500          | [045a82f0f6](https://linux-hardware.org/?probe=045a82f0f6) | Jan 06, 2020 |
| Acer          | Aspire 5542                 | [aeeb077808](https://linux-hardware.org/?probe=aeeb077808) | Jan 05, 2020 |
| Toshiba       | Satellite Pro S500          | [464d7a82b6](https://linux-hardware.org/?probe=464d7a82b6) | Jan 05, 2020 |
| Acer          | Aspire 5542                 | [1458705a5f](https://linux-hardware.org/?probe=1458705a5f) | Jan 04, 2020 |
| Toshiba       | Satellite Pro S500          | [e5d9ec4712](https://linux-hardware.org/?probe=e5d9ec4712) | Dec 31, 2019 |
| Toshiba       | Satellite Pro S500          | [db0edb9f16](https://linux-hardware.org/?probe=db0edb9f16) | Dec 31, 2019 |
| Toshiba       | Satellite Pro S500          | [fdcb757efe](https://linux-hardware.org/?probe=fdcb757efe) | Dec 31, 2019 |
| Toshiba       | Satellite Pro S500          | [4cf474fd47](https://linux-hardware.org/?probe=4cf474fd47) | Dec 31, 2019 |
| Fujitsu       | LIFEBOOK S710               | [b3b0d2e40e](https://linux-hardware.org/?probe=b3b0d2e40e) | Dec 30, 2019 |
| HP            | Pavilion dv7                | [1147f13741](https://linux-hardware.org/?probe=1147f13741) | Dec 30, 2019 |
| Dell          | Studio 1555                 | [4507496780](https://linux-hardware.org/?probe=4507496780) | Dec 29, 2019 |
| HP            | Stream Laptop 11-y0XX       | [aca2eac05b](https://linux-hardware.org/?probe=aca2eac05b) | Dec 29, 2019 |
| Toshiba       | Satellite Pro S500          | [1bf57edaba](https://linux-hardware.org/?probe=1bf57edaba) | Dec 29, 2019 |
| Dell          | Studio 1555                 | [9aba9666d7](https://linux-hardware.org/?probe=9aba9666d7) | Dec 28, 2019 |
| Toshiba       | Satellite L20               | [2184b17801](https://linux-hardware.org/?probe=2184b17801) | Dec 28, 2019 |
| Samsung       | 275E4E/275E5E               | [666a988e9b](https://linux-hardware.org/?probe=666a988e9b) | Dec 28, 2019 |
| HP            | Compaq Presario CQ50        | [ad1aea7e39](https://linux-hardware.org/?probe=ad1aea7e39) | Dec 27, 2019 |
| Toshiba       | Satellite Pro S500          | [9be4f247b6](https://linux-hardware.org/?probe=9be4f247b6) | Dec 24, 2019 |
| Toshiba       | Satellite Pro S500          | [4199720757](https://linux-hardware.org/?probe=4199720757) | Dec 24, 2019 |
| HP            | Pavilion 15                 | [98e4efccb2](https://linux-hardware.org/?probe=98e4efccb2) | Dec 24, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | [011ab343ef](https://linux-hardware.org/?probe=011ab343ef) | Dec 22, 2019 |
| Samsung       | 275E4E/275E5E               | [80bfe1c21e](https://linux-hardware.org/?probe=80bfe1c21e) | Dec 22, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | [bb9da61133](https://linux-hardware.org/?probe=bb9da61133) | Dec 21, 2019 |
| Toshiba       | Satellite L20               | [563f05aae7](https://linux-hardware.org/?probe=563f05aae7) | Dec 18, 2019 |
| HP            | Compaq Presario CQ50        | [d672b4583e](https://linux-hardware.org/?probe=d672b4583e) | Dec 15, 2019 |
| HP            | Laptop 14-cm0xxx            | [3a1243a77f](https://linux-hardware.org/?probe=3a1243a77f) | Dec 12, 2019 |
| HP            | Laptop 14-cm0xxx            | [71a8ef2f9c](https://linux-hardware.org/?probe=71a8ef2f9c) | Dec 12, 2019 |
| Dell          | Inspiron MM061              | [74039c6d39](https://linux-hardware.org/?probe=74039c6d39) | Dec 01, 2019 |
| Toshiba       | Satellite Pro S500          | [45f548ba27](https://linux-hardware.org/?probe=45f548ba27) | Dec 01, 2019 |
| Toshiba       | Satellite Pro S500          | [5cf7a1f9b8](https://linux-hardware.org/?probe=5cf7a1f9b8) | Dec 01, 2019 |
| Toshiba       | Satellite Pro S500          | [03ab084bc4](https://linux-hardware.org/?probe=03ab084bc4) | Nov 30, 2019 |
| ASUSTek       | X51RL                       | [2d4367bb57](https://linux-hardware.org/?probe=2d4367bb57) | Nov 29, 2019 |
| Samsung       | 275E4E/275E5E               | [4e229f13aa](https://linux-hardware.org/?probe=4e229f13aa) | Nov 23, 2019 |
| AMI           | Cherry Trail CR             | [fd9a3df2b6](https://linux-hardware.org/?probe=fd9a3df2b6) | Nov 19, 2019 |
| HP            | Laptop 15-bw0xx             | [c4b7195697](https://linux-hardware.org/?probe=c4b7195697) | Nov 18, 2019 |
| Dell          | Inspiron MM061              | [c382fdc34a](https://linux-hardware.org/?probe=c382fdc34a) | Nov 14, 2019 |
| Sony          | SVE14A2V1EW                 | [e80c47963a](https://linux-hardware.org/?probe=e80c47963a) | Nov 12, 2019 |
| Acer          | Aspire V3-571G              | [2e7b8ff7ae](https://linux-hardware.org/?probe=2e7b8ff7ae) | Nov 11, 2019 |
| ASUSTek       | U32U                        | [656773dca2](https://linux-hardware.org/?probe=656773dca2) | Oct 22, 2019 |
| Toshiba       | Satellite L20               | [10173fe107](https://linux-hardware.org/?probe=10173fe107) | Aug 18, 2019 |
| Toshiba       | Satellite L20               | [9e524c52e7](https://linux-hardware.org/?probe=9e524c52e7) | Jul 31, 2019 |
| Acer          | Aspire one 1-431            | [33ff5f5399](https://linux-hardware.org/?probe=33ff5f5399) | Jul 14, 2019 |
| Toshiba       | Satellite L20               | [ba3f405ef7](https://linux-hardware.org/?probe=ba3f405ef7) | Jul 05, 2019 |
| ASUSTek       | 1215B                       | [5e3f89149f](https://linux-hardware.org/?probe=5e3f89149f) | Jun 29, 2019 |
| HP            | ProBook 430 G1              | [9be61e9a2d](https://linux-hardware.org/?probe=9be61e9a2d) | Jun 24, 2019 |
| Dell          | Inspiron 5566               | [a8122ef82d](https://linux-hardware.org/?probe=a8122ef82d) | Apr 26, 2019 |
| Toshiba       | Satellite L20               | [d9ee5a5ff8](https://linux-hardware.org/?probe=d9ee5a5ff8) | Apr 09, 2019 |
| ASUSTek       | K55VJ                       | [fac5cee3e3](https://linux-hardware.org/?probe=fac5cee3e3) | Apr 05, 2019 |
| Dell          | Inspiron 5566               | [e4dc78de4f](https://linux-hardware.org/?probe=e4dc78de4f) | Mar 28, 2019 |
| HP            | Pavilion Sleekbook 15       | [81ac047bce](https://linux-hardware.org/?probe=81ac047bce) | Mar 10, 2019 |
| HP            | Pavilion Sleekbook 15       | [26ccc6c647](https://linux-hardware.org/?probe=26ccc6c647) | Mar 10, 2019 |
| Acer          | Aspire F5-771G              | [8f2bbcbea8](https://linux-hardware.org/?probe=8f2bbcbea8) | Dec 23, 2018 |
| Toshiba       | Satellite L20               | [409df1d9a6](https://linux-hardware.org/?probe=409df1d9a6) | Oct 30, 2018 |
| Toshiba       | Satellite L300              | [c50c4eed87](https://linux-hardware.org/?probe=c50c4eed87) | Sep 02, 2018 |
| ASUSTek       | X200MA                      | [62851925f7](https://linux-hardware.org/?probe=62851925f7) | Jul 27, 2018 |
| Lenovo        | G580 20150                  | [69369b93d2](https://linux-hardware.org/?probe=69369b93d2) | Jul 09, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lubuntu 20.04   | 222       | 42.13%  |
| Lubuntu 18.04   | 112       | 21.25%  |
| Lubuntu 19.10   | 43        | 8.16%   |
| Lubuntu 21.10   | 40        | 7.59%   |
| Lubuntu 21.04   | 36        | 6.83%   |
| Lubuntu 20.10   | 29        | 5.5%    |
| Lubuntu 16.04   | 15        | 2.85%   |
| Lubuntu 19.04   | 12        | 2.28%   |
| Lubuntu 22.04   | 6         | 1.14%   |
| Lubuntu 18.10   | 6         | 1.14%   |
| Lubuntu         | 3         | 0.57%   |
| Lubuntu 20.04.1 | 1         | 0.19%   |
| Lubuntu 18.04.4 | 1         | 0.19%   |
| Lubuntu 17.10   | 1         | 0.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Lubuntu | 512       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.4.0-42-generic   | 24        | 4.01%   |
| 5.4.0-52-generic   | 15        | 2.51%   |
| 5.13.0-28-generic  | 11        | 1.84%   |
| 5.11.0-16-generic  | 11        | 1.84%   |
| 5.4.0-47-generic   | 10        | 1.67%   |
| 5.3.0-46-generic   | 10        | 1.67%   |
| 5.4.0-26-generic   | 9         | 1.51%   |
| 5.13.0-30-generic  | 9         | 1.51%   |
| 5.13.0-19-generic  | 9         | 1.51%   |
| 5.4.0-48-generic   | 8         | 1.34%   |
| 5.3.0-18-generic   | 8         | 1.34%   |
| 5.13.0-35-generic  | 8         | 1.34%   |
| 5.11.0-25-generic  | 8         | 1.34%   |
| 4.15.0-112-generic | 8         | 1.34%   |
| 5.4.0-73-generic   | 7         | 1.17%   |
| 5.4.0-65-generic   | 7         | 1.17%   |
| 5.4.0-40-generic   | 7         | 1.17%   |
| 4.15.0-96-generic  | 7         | 1.17%   |
| 5.8.0-63-generic   | 6         | 1%      |
| 5.4.0-72-generic   | 6         | 1%      |
| 5.4.0-51-generic   | 6         | 1%      |
| 5.4.0-29-generic   | 6         | 1%      |
| 5.3.0-51-generic   | 6         | 1%      |
| 5.3.0-40-generic   | 6         | 1%      |
| 5.13.0-22-generic  | 6         | 1%      |
| 5.11.0-38-generic  | 6         | 1%      |
| 5.11.0-37-generic  | 6         | 1%      |
| 4.15.0-91-generic  | 6         | 1%      |
| 4.15.0-136-generic | 6         | 1%      |
| 5.8.0-53-generic   | 5         | 0.84%   |
| 5.8.0-48-generic   | 5         | 0.84%   |
| 5.4.0-70-generic   | 5         | 0.84%   |
| 5.4.0-58-generic   | 5         | 0.84%   |
| 5.4.0-56-generic   | 5         | 0.84%   |
| 5.4.0-54-generic   | 5         | 0.84%   |
| 5.4.0-33-generic   | 5         | 0.84%   |
| 5.3.0-42-generic   | 5         | 0.84%   |
| 5.11.0-41-generic  | 5         | 0.84%   |
| 5.11.0-17-generic  | 5         | 0.84%   |
| 5.0.0-37-generic   | 5         | 0.84%   |
| 5.0.0-36-generic   | 5         | 0.84%   |
| 5.8.0-49-generic   | 4         | 0.67%   |
| 5.8.0-45-generic   | 4         | 0.67%   |
| 5.8.0-26-generic   | 4         | 0.67%   |
| 5.4.0-89-generic   | 4         | 0.67%   |
| 5.4.0-45-generic   | 4         | 0.67%   |
| 5.4.0-37-generic   | 4         | 0.67%   |
| 5.3.0-64-generic   | 4         | 0.67%   |
| 5.3.0-28-generic   | 4         | 0.67%   |
| 5.3.0-26-generic   | 4         | 0.67%   |
| 5.3.0-24-generic   | 4         | 0.67%   |
| 5.11.0-40-generic  | 4         | 0.67%   |
| 5.11.0-27-generic  | 4         | 0.67%   |
| 5.0.0-38-generic   | 4         | 0.67%   |
| 4.18.0-25-generic  | 4         | 0.67%   |
| 4.15.0-99-generic  | 4         | 0.67%   |
| 4.15.0-76-generic  | 4         | 0.67%   |
| 4.15.0-72-generic  | 4         | 0.67%   |
| 4.15.0-122-generic | 4         | 0.67%   |
| 4.15.0-106-generic | 4         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.4.0    | 179       | 33.52%  |
| 4.15.0   | 69        | 12.92%  |
| 5.11.0   | 65        | 12.17%  |
| 5.3.0    | 63        | 11.8%   |
| 5.13.0   | 59        | 11.05%  |
| 5.8.0    | 55        | 10.3%   |
| 5.0.0    | 16        | 3%      |
| 4.18.0   | 7         | 1.31%   |
| 5.15.0   | 6         | 1.12%   |
| 4.4.0    | 4         | 0.75%   |
| 4.13.0   | 2         | 0.37%   |
| 5.9.0    | 1         | 0.19%   |
| 5.7.9    | 1         | 0.19%   |
| 5.6.0    | 1         | 0.19%   |
| 5.5.2    | 1         | 0.19%   |
| 5.16.0   | 1         | 0.19%   |
| 5.10.0   | 1         | 0.19%   |
| 4.14.225 | 1         | 0.19%   |
| 4.13.9   | 1         | 0.19%   |
| 4.10.0   | 1         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 179       | 33.52%  |
| 4.15    | 69        | 12.92%  |
| 5.11    | 65        | 12.17%  |
| 5.3     | 63        | 11.8%   |
| 5.13    | 59        | 11.05%  |
| 5.8     | 55        | 10.3%   |
| 5.0     | 16        | 3%      |
| 4.18    | 7         | 1.31%   |
| 5.15    | 6         | 1.12%   |
| 4.4     | 4         | 0.75%   |
| 4.13    | 3         | 0.56%   |
| 5.9     | 1         | 0.19%   |
| 5.7     | 1         | 0.19%   |
| 5.6     | 1         | 0.19%   |
| 5.5     | 1         | 0.19%   |
| 5.16    | 1         | 0.19%   |
| 5.10    | 1         | 0.19%   |
| 4.14    | 1         | 0.19%   |
| 4.10    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 441       | 86.13%  |
| i686   | 71        | 13.87%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| LXQt            | 371       | 72.04%  |
| LXDE            | 110       | 21.36%  |
| Unknown         | 15        | 2.91%   |
| Openbox         | 6         | 1.17%   |
| GNOME           | 5         | 0.97%   |
| KDE5            | 2         | 0.39%   |
| Cinnamon        | 2         | 0.39%   |
| MATE            | 1         | 0.19%   |
| Lubuntu         | 1         | 0.19%   |
| KDE             | 1         | 0.19%   |
| GNOME Flashback | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 501       | 97.47%  |
| Tty     | 10        | 1.95%   |
| Wayland | 3         | 0.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 223       | 42.88%  |
| SDDM    | 197       | 37.88%  |
| TDM     | 43        | 8.27%   |
| LightDM | 35        | 6.73%   |
| GDM     | 18        | 3.46%   |
| GDM3    | 2         | 0.38%   |
| XDM     | 1         | 0.19%   |
| LXDM    | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 134       | 26.02%  |
| pt_BR   | 50        | 9.71%   |
| fr_FR   | 38        | 7.38%   |
| it_IT   | 32        | 6.21%   |
| en_GB   | 26        | 5.05%   |
| de_DE   | 26        | 5.05%   |
| ru_RU   | 20        | 3.88%   |
| pl_PL   | 18        | 3.5%    |
| C       | 18        | 3.5%    |
| Unknown | 17        | 3.3%    |
| es_ES   | 13        | 2.52%   |
| en_AU   | 10        | 1.94%   |
| en_CA   | 9         | 1.75%   |
| tr_TR   | 7         | 1.36%   |
| es_AR   | 7         | 1.36%   |
| en_IN   | 7         | 1.36%   |
| en_IE   | 6         | 1.17%   |
| nl_NL   | 5         | 0.97%   |
| hu_HU   | 5         | 0.97%   |
| es_CR   | 5         | 0.97%   |
| cs_CZ   | 5         | 0.97%   |
| fr_BE   | 4         | 0.78%   |
| es_CL   | 4         | 0.78%   |
| nl_BE   | 3         | 0.58%   |
| ja_JP   | 3         | 0.58%   |
| es_MX   | 3         | 0.58%   |
| zh_TW   | 2         | 0.39%   |
| id_ID   | 2         | 0.39%   |
| fr_CH   | 2         | 0.39%   |
| es_VE   | 2         | 0.39%   |
| es_UY   | 2         | 0.39%   |
| es_PE   | 2         | 0.39%   |
| es_CO   | 2         | 0.39%   |
| en_SG   | 2         | 0.39%   |
| en_NZ   | 2         | 0.39%   |
| el_GR   | 2         | 0.39%   |
| zh_CN   | 1         | 0.19%   |
| uk_UA   | 1         | 0.19%   |
| sr_RS   | 1         | 0.19%   |
| ru_UA   | 1         | 0.19%   |
| ro_RO   | 1         | 0.19%   |
| nb_NO   | 1         | 0.19%   |
| lt_LT   | 1         | 0.19%   |
| ko_KR   | 1         | 0.19%   |
| fr_CA   | 1         | 0.19%   |
| fi_FI   | 1         | 0.19%   |
| fa_IR   | 1         | 0.19%   |
| es_DO   | 1         | 0.19%   |
| en_ZM   | 1         | 0.19%   |
| en_ZA   | 1         | 0.19%   |
| en_PH   | 1         | 0.19%   |
| en_DE   | 1         | 0.19%   |
| en_CM   | 1         | 0.19%   |
| en_CH   | 1         | 0.19%   |
| de_AT   | 1         | 0.19%   |
| bg_BG   | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 333       | 64.29%  |
| EFI  | 185       | 35.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 478       | 93.18%  |
| Overlay | 18        | 3.51%   |
| Btrfs   | 8         | 1.56%   |
| Aufs    | 4         | 0.78%   |
| Unknown | 3         | 0.58%   |
| Ext3    | 2         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 262       | 50.78%  |
| GPT     | 135       | 26.16%  |
| MBR     | 119       | 23.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 476       | 92.07%  |
| Yes       | 41        | 7.93%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 391       | 75.92%  |
| Yes       | 124       | 24.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 112       | 21.88%  |
| Lenovo                      | 61        | 11.91%  |
| Dell                        | 56        | 10.94%  |
| ASUSTek Computer            | 52        | 10.16%  |
| Acer                        | 47        | 9.18%   |
| Toshiba                     | 35        | 6.84%   |
| Samsung Electronics         | 22        | 4.3%    |
| Sony                        | 16        | 3.13%   |
| Apple                       | 13        | 2.54%   |
| Positivo                    | 11        | 2.15%   |
| Google                      | 10        | 1.95%   |
| MSI                         | 8         | 1.56%   |
| Notebook                    | 5         | 0.98%   |
| Fujitsu Siemens             | 5         | 0.98%   |
| Packard Bell                | 4         | 0.78%   |
| Fujitsu                     | 4         | 0.78%   |
| Unknown                     | 4         | 0.78%   |
| Mediacom                    | 3         | 0.59%   |
| IBM                         | 3         | 0.59%   |
| Alienware                   | 3         | 0.59%   |
| Panasonic                   | 2         | 0.39%   |
| Itautec                     | 2         | 0.39%   |
| Insyde                      | 2         | 0.39%   |
| Gigabyte Technology         | 2         | 0.39%   |
| Dixonsxp                    | 2         | 0.39%   |
| AMI                         | 2         | 0.39%   |
| YASHI                       | 1         | 0.2%    |
| UNOWHY                      | 1         | 0.2%    |
| TrekStor                    | 1         | 0.2%    |
| Timi                        | 1         | 0.2%    |
| Thomson                     | 1         | 0.2%    |
| System76                    | 1         | 0.2%    |
| Standard                    | 1         | 0.2%    |
| Semp Toshiba                | 1         | 0.2%    |
| Prestigio                   | 1         | 0.2%    |
| Phoenix/SiS                 | 1         | 0.2%    |
| Philco                      | 1         | 0.2%    |
| OEM                         | 1         | 0.2%    |
| Noblex                      | 1         | 0.2%    |
| LG Electronics              | 1         | 0.2%    |
| LEADER                      | 1         | 0.2%    |
| Lanix                       | 1         | 0.2%    |
| LAMINA                      | 1         | 0.2%    |
| Intel                       | 1         | 0.2%    |
| I-Life Digital Technologies | 1         | 0.2%    |
| Hungaro Flotta Kft          | 1         | 0.2%    |
| HUAWEI                      | 1         | 0.2%    |
| Haier                       | 1         | 0.2%    |
| GTZS                        | 1         | 0.2%    |
| Gateway                     | 1         | 0.2%    |
| Digibras                    | 1         | 0.2%    |
| ASHI                        | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 11        | 2.15%   |
| HP Notebook                    | 6         | 1.17%   |
| Apple MacBookPro8,1            | 5         | 0.98%   |
| HP Pavilion dv6                | 4         | 0.78%   |
| Dell Latitude D630             | 4         | 0.78%   |
| HP ProBook 440 G7              | 3         | 0.59%   |
| HP Pavilion g6                 | 3         | 0.59%   |
| HP Pavilion 15                 | 3         | 0.59%   |
| Acer Aspire 5742G              | 3         | 0.59%   |
| Toshiba Satellite A205         | 2         | 0.39%   |
| Samsung RV415/RV515            | 2         | 0.39%   |
| Samsung 275E4E/275E5E          | 2         | 0.39%   |
| Positivo MOBILE                | 2         | 0.39%   |
| Positivo H14BT58               | 2         | 0.39%   |
| Mediacom GTZS                  | 2         | 0.39%   |
| Lenovo IdeaPad 330-17AST 81D7  | 2         | 0.39%   |
| Lenovo IdeaPad 320-15AST 80XV  | 2         | 0.39%   |
| Lenovo IdeaPad 100-15IBD 80QQ  | 2         | 0.39%   |
| Itautec Infoway                | 2         | 0.39%   |
| HP ProBook 450 G2              | 2         | 0.39%   |
| HP ProBook 440 G8 Notebook PC  | 2         | 0.39%   |
| HP Pavilion g7                 | 2         | 0.39%   |
| HP Pavilion g4                 | 2         | 0.39%   |
| HP Laptop 15-bw0xx             | 2         | 0.39%   |
| HP EliteBook 840 G1            | 2         | 0.39%   |
| HP EliteBook 2560p             | 2         | 0.39%   |
| HP Compaq Presario CQ50        | 2         | 0.39%   |
| HP Compaq Presario C700        | 2         | 0.39%   |
| Dell XPS 13 9300               | 2         | 0.39%   |
| Dell Studio 1555               | 2         | 0.39%   |
| Dell Latitude 7480             | 2         | 0.39%   |
| Dell Inspiron 15-3567          | 2         | 0.39%   |
| ASUS 1215B                     | 2         | 0.39%   |
| ASUS 1015PE                    | 2         | 0.39%   |
| ASUS 1015BX                    | 2         | 0.39%   |
| ASUS 1000H                     | 2         | 0.39%   |
| Acer Aspire 5735               | 2         | 0.39%   |
| Acer Aspire 5715Z              | 2         | 0.39%   |
| Acer AOD257                    | 2         | 0.39%   |
| YASHI MYBOOK 360               | 1         | 0.2%    |
| UNOWHY Y13G010S4EI             | 1         | 0.2%    |
| TrekStor Surfbook A13B         | 1         | 0.2%    |
| Toshiba TECRA A8               | 1         | 0.2%    |
| Toshiba TECRA A3X              | 1         | 0.2%    |
| Toshiba Satellite U500         | 1         | 0.2%    |
| Toshiba Satellite S55-B        | 1         | 0.2%    |
| Toshiba Satellite Pro U400     | 1         | 0.2%    |
| Toshiba Satellite Pro S500     | 1         | 0.2%    |
| Toshiba Satellite Pro C850-1GR | 1         | 0.2%    |
| Toshiba Satellite L840         | 1         | 0.2%    |
| Toshiba Satellite L755D        | 1         | 0.2%    |
| Toshiba Satellite L735         | 1         | 0.2%    |
| Toshiba Satellite L70-B        | 1         | 0.2%    |
| Toshiba Satellite L50D-B       | 1         | 0.2%    |
| Toshiba Satellite L450         | 1         | 0.2%    |
| Toshiba Satellite L40          | 1         | 0.2%    |
| Toshiba Satellite L35          | 1         | 0.2%    |
| Toshiba Satellite L305         | 1         | 0.2%    |
| Toshiba Satellite L300         | 1         | 0.2%    |
| Toshiba Satellite L30          | 1         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 35        | 6.84%   |
| HP Pavilion           | 32        | 6.25%   |
| Toshiba Satellite     | 31        | 6.05%   |
| Dell Inspiron         | 27        | 5.27%   |
| Lenovo ThinkPad       | 25        | 4.88%   |
| Lenovo IdeaPad        | 23        | 4.49%   |
| HP ProBook            | 21        | 4.1%    |
| Dell Latitude         | 18        | 3.52%   |
| HP EliteBook          | 14        | 2.73%   |
| HP Compaq             | 14        | 2.73%   |
| Unknown               | 11        | 2.15%   |
| HP Laptop             | 9         | 1.76%   |
| HP Notebook           | 6         | 1.17%   |
| Fujitsu Siemens AMILO | 5         | 0.98%   |
| ASUS VivoBook         | 5         | 0.98%   |
| Apple MacBookPro8     | 5         | 0.98%   |
| HP Presario           | 4         | 0.78%   |
| Dell XPS              | 4         | 0.78%   |
| Dell Vostro           | 4         | 0.78%   |
| Packard Bell EasyNote | 3         | 0.59%   |
| HP Stream             | 3         | 0.59%   |
| Acer Extensa          | 3         | 0.59%   |
| Toshiba TECRA         | 2         | 0.39%   |
| Samsung RV415         | 2         | 0.39%   |
| Samsung 275E4E        | 2         | 0.39%   |
| Positivo MOBILE       | 2         | 0.39%   |
| Positivo H14BT58      | 2         | 0.39%   |
| Notebook W54          | 2         | 0.39%   |
| Mediacom GTZS         | 2         | 0.39%   |
| Itautec Infoway       | 2         | 0.39%   |
| Fujitsu LIFEBOOK      | 2         | 0.39%   |
| Dell Studio           | 2         | 0.39%   |
| ASUS 1215B            | 2         | 0.39%   |
| ASUS 1015PE           | 2         | 0.39%   |
| ASUS 1015BX           | 2         | 0.39%   |
| ASUS 1000H            | 2         | 0.39%   |
| Apple MacBookPro10    | 2         | 0.39%   |
| Acer AOD257           | 2         | 0.39%   |
| YASHI MYBOOK          | 1         | 0.2%    |
| UNOWHY Y13G010S4EI    | 1         | 0.2%    |
| TrekStor Surfbook     | 1         | 0.2%    |
| Toshiba NB510         | 1         | 0.2%    |
| Toshiba NB505         | 1         | 0.2%    |
| Timi TM1612           | 1         | 0.2%    |
| Thomson NEO14A-4BK64  | 1         | 0.2%    |
| System76 Lemur        | 1         | 0.2%    |
| Standard EF20EA       | 1         | 0.2%    |
| Sony VPCYB35AL        | 1         | 0.2%    |
| Sony VPCYB15AB        | 1         | 0.2%    |
| Sony VPCSB1V9E        | 1         | 0.2%    |
| Sony VPCSA2FGX        | 1         | 0.2%    |
| Sony VPCEJ1E1E        | 1         | 0.2%    |
| Sony VPCEG25EN        | 1         | 0.2%    |
| Sony VGN-SZ71WN       | 1         | 0.2%    |
| Sony VGN-SZ670AN      | 1         | 0.2%    |
| Sony VGN-S5XP         | 1         | 0.2%    |
| Sony VGN-P610         | 1         | 0.2%    |
| Sony VGN-NR430E       | 1         | 0.2%    |
| Sony VGN-FE21M        | 1         | 0.2%    |
| Sony VGN-CS325J       | 1         | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 56        | 10.94%  |
| 2008    | 46        | 8.98%   |
| 2010    | 43        | 8.4%    |
| 2007    | 43        | 8.4%    |
| 2013    | 40        | 7.81%   |
| 2012    | 37        | 7.23%   |
| 2019    | 31        | 6.05%   |
| 2009    | 29        | 5.66%   |
| 2016    | 27        | 5.27%   |
| 2017    | 26        | 5.08%   |
| 2014    | 25        | 4.88%   |
| 2018    | 24        | 4.69%   |
| 2006    | 21        | 4.1%    |
| 2020    | 19        | 3.71%   |
| 2015    | 19        | 3.71%   |
| 2021    | 15        | 2.93%   |
| 2005    | 5         | 0.98%   |
| 2022    | 2         | 0.39%   |
| 2002    | 2         | 0.39%   |
| Unknown | 2         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 512       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 483       | 94.15%  |
| Enabled  | 30        | 5.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 501       | 97.85%  |
| Yes  | 11        | 2.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 168       | 32.5%   |
| 4.01-8.0   | 109       | 21.08%  |
| 1.01-2.0   | 109       | 21.08%  |
| 8.01-16.0  | 49        | 9.48%   |
| 2.01-3.0   | 29        | 5.61%   |
| 16.01-24.0 | 27        | 5.22%   |
| 0.51-1.0   | 19        | 3.68%   |
| 32.01-64.0 | 5         | 0.97%   |
| 0.01-0.5   | 2         | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 244       | 44.2%   |
| 0.51-1.0  | 150       | 27.17%  |
| 2.01-3.0  | 61        | 11.05%  |
| 0.01-0.5  | 37        | 6.7%    |
| 4.01-8.0  | 28        | 5.07%   |
| 3.01-4.0  | 28        | 5.07%   |
| 8.01-16.0 | 4         | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 391       | 75.63%  |
| 2      | 108       | 20.89%  |
| 0      | 12        | 2.32%   |
| 3      | 5         | 0.97%   |
| 4      | 1         | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 271       | 52.83%  |
| No        | 242       | 47.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 447       | 87.13%  |
| No        | 66        | 12.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 483       | 94.34%  |
| No        | 29        | 5.66%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 305       | 58.54%  |
| No        | 216       | 41.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 67        | 13.06%  |
| Brazil                 | 62        | 12.09%  |
| Italy                  | 39        | 7.6%    |
| France                 | 37        | 7.21%   |
| Germany                | 31        | 6.04%   |
| Russia                 | 30        | 5.85%   |
| UK                     | 26        | 5.07%   |
| Poland                 | 18        | 3.51%   |
| Canada                 | 15        | 2.92%   |
| Spain                  | 12        | 2.34%   |
| Turkey                 | 10        | 1.95%   |
| Netherlands            | 10        | 1.95%   |
| Belgium                | 10        | 1.95%   |
| Australia              | 9         | 1.75%   |
| Czechia                | 8         | 1.56%   |
| Ukraine                | 7         | 1.36%   |
| India                  | 7         | 1.36%   |
| Argentina              | 7         | 1.36%   |
| Mexico                 | 6         | 1.17%   |
| Indonesia              | 6         | 1.17%   |
| Switzerland            | 5         | 0.97%   |
| Ireland                | 5         | 0.97%   |
| Hungary                | 5         | 0.97%   |
| Costa Rica             | 5         | 0.97%   |
| Chile                  | 4         | 0.78%   |
| Serbia                 | 3         | 0.58%   |
| Malaysia               | 3         | 0.58%   |
| Lithuania              | 3         | 0.58%   |
| Finland                | 3         | 0.58%   |
| Colombia               | 3         | 0.58%   |
| Bulgaria               | 3         | 0.58%   |
| Uruguay                | 2         | 0.39%   |
| Tunisia                | 2         | 0.39%   |
| Taiwan                 | 2         | 0.39%   |
| Sweden                 | 2         | 0.39%   |
| Slovenia               | 2         | 0.39%   |
| Singapore              | 2         | 0.39%   |
| Romania                | 2         | 0.39%   |
| Portugal               | 2         | 0.39%   |
| Peru                   | 2         | 0.39%   |
| Norway                 | 2         | 0.39%   |
| New Zealand            | 2         | 0.39%   |
| Japan                  | 2         | 0.39%   |
| Greece                 | 2         | 0.39%   |
| Ecuador                | 2         | 0.39%   |
| Bosnia and Herzegovina | 2         | 0.39%   |
| Austria                | 2         | 0.39%   |
| Zambia                 | 1         | 0.19%   |
| Vietnam                | 1         | 0.19%   |
| Venezuela              | 1         | 0.19%   |
| Thailand               | 1         | 0.19%   |
| Sri Lanka              | 1         | 0.19%   |
| South Korea            | 1         | 0.19%   |
| South Africa           | 1         | 0.19%   |
| Slovakia               | 1         | 0.19%   |
| Philippines            | 1         | 0.19%   |
| Martinique             | 1         | 0.19%   |
| Luxembourg             | 1         | 0.19%   |
| Lebanon                | 1         | 0.19%   |
| Israel                 | 1         | 0.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 7         | 1.28%   |
| Milan             | 7         | 1.28%   |
| Rome              | 5         | 0.91%   |
| Moscow            | 5         | 0.91%   |
| Heredia           | 5         | 0.91%   |
| Warsaw            | 4         | 0.73%   |
| Teresina          | 4         | 0.73%   |
| Stuttgart         | 4         | 0.73%   |
| Istanbul          | 4         | 0.73%   |
| Glasgow           | 4         | 0.73%   |
| BrasГ­lia       | 4         | 0.73%   |
| Bengaluru         | 4         | 0.73%   |
| Yekaterinburg     | 3         | 0.55%   |
| Salvador          | 3         | 0.55%   |
| Porto Alegre      | 3         | 0.55%   |
| JoГЈo Pessoa    | 3         | 0.55%   |
| Ghent             | 3         | 0.55%   |
| Curitiba          | 3         | 0.55%   |
| Budapest          | 3         | 0.55%   |
| Berlin            | 3         | 0.55%   |
| Amsterdam         | 3         | 0.55%   |
| Zurich            | 2         | 0.36%   |
| Winnipeg          | 2         | 0.36%   |
| Westwood          | 2         | 0.36%   |
| VitГіria        | 2         | 0.36%   |
| Vicosa            | 2         | 0.36%   |
| Turin             | 2         | 0.36%   |
| Sydney            | 2         | 0.36%   |
| St Petersburg     | 2         | 0.36%   |
| Southampton       | 2         | 0.36%   |
| Singapore         | 2         | 0.36%   |
| Sao Paulo         | 2         | 0.36%   |
| Prague            | 2         | 0.36%   |
| Poznan            | 2         | 0.36%   |
| Petrolina         | 2         | 0.36%   |
| Parkdale          | 2         | 0.36%   |
| Ottawa            | 2         | 0.36%   |
| Oshawa            | 2         | 0.36%   |
| OrlГ©ans        | 2         | 0.36%   |
| Orlando           | 2         | 0.36%   |
| Olomouc           | 2         | 0.36%   |
| Nizhniy Novgorod  | 2         | 0.36%   |
| New York          | 2         | 0.36%   |
| Natal             | 2         | 0.36%   |
| Nantes            | 2         | 0.36%   |
| Munich            | 2         | 0.36%   |
| Montevideo        | 2         | 0.36%   |
| Mexico City       | 2         | 0.36%   |
| Melbourne         | 2         | 0.36%   |
| Loveland          | 2         | 0.36%   |
| Lille             | 2         | 0.36%   |
| Kyiv              | 2         | 0.36%   |
| Kuala Lumpur      | 2         | 0.36%   |
| Krakow            | 2         | 0.36%   |
| Kaunas            | 2         | 0.36%   |
| Houston           | 2         | 0.36%   |
| Helsinki          | 2         | 0.36%   |
| Frankfurt am Main | 2         | 0.36%   |
| Fortaleza         | 2         | 0.36%   |
| Edgware           | 2         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 88        | 99     | 15.55%  |
| WDC                 | 80        | 100    | 14.13%  |
| Toshiba             | 54        | 61     | 9.54%   |
| Hitachi             | 50        | 64     | 8.83%   |
| Unknown             | 46        | 57     | 8.13%   |
| Samsung Electronics | 45        | 65     | 7.95%   |
| Kingston            | 29        | 32     | 5.12%   |
| Crucial             | 23        | 26     | 4.06%   |
| Intel               | 17        | 21     | 3%      |
| HGST                | 17        | 20     | 3%      |
| Fujitsu             | 17        | 18     | 3%      |
| SanDisk             | 14        | 18     | 2.47%   |
| SK Hynix            | 8         | 8      | 1.41%   |
| Apacer              | 6         | 6      | 1.06%   |
| KIOXIA              | 5         | 5      | 0.88%   |
| China               | 5         | 7      | 0.88%   |
| A-DATA Technology   | 5         | 5      | 0.88%   |
| Micron Technology   | 4         | 4      | 0.71%   |
| Transcend           | 3         | 3      | 0.53%   |
| Patriot             | 3         | 3      | 0.53%   |
| OCZ                 | 3         | 3      | 0.53%   |
| LITEONIT            | 3         | 3      | 0.53%   |
| LITEON              | 3         | 4      | 0.53%   |
| Apple               | 3         | 9      | 0.53%   |
| Unknown             | 3         | 4      | 0.53%   |
| STEC                | 2         | 3      | 0.35%   |
| PNY                 | 2         | 2      | 0.35%   |
| LDLC                | 2         | 2      | 0.35%   |
| KingDian            | 2         | 2      | 0.35%   |
| IBM/Hitachi         | 2         | 3      | 0.35%   |
| Gigabyte Technology | 2         | 2      | 0.35%   |
| Dogfish             | 2         | 2      | 0.35%   |
| USB                 | 1         | 1      | 0.18%   |
| TEAM T25            | 1         | 1      | 0.18%   |
| TCSUNBOW            | 1         | 1      | 0.18%   |
| SPCC                | 1         | 1      | 0.18%   |
| Phison Electronics  | 1         | 1      | 0.18%   |
| Phison              | 1         | 5      | 0.18%   |
| NGFF                | 1         | 1      | 0.18%   |
| MyDigitalSSD        | 1         | 1      | 0.18%   |
| Mushkin             | 1         | 1      | 0.18%   |
| LS                  | 1         | 1      | 0.18%   |
| Lenovo              | 1         | 1      | 0.18%   |
| LaCie               | 1         | 2      | 0.18%   |
| KingSpec            | 1         | 11     | 0.18%   |
| JMicron             | 1         | 1      | 0.18%   |
| Integral            | 1         | 1      | 0.18%   |
| General             | 1         | 1      | 0.18%   |
| EMTEC               | 1         | 1      | 0.18%   |
| Dell                | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 12        | 2.05%   |
| Kingston SA400S37240G 240GB SSD      | 9         | 1.54%   |
| Toshiba MQ01ABF050 500GB             | 7         | 1.2%    |
| Toshiba MQ01ABD100 1TB               | 7         | 1.2%    |
| Seagate ST9500325AS 500GB            | 7         | 1.2%    |
| Seagate ST500LT012-1DG142 500GB      | 7         | 1.2%    |
| Seagate ST500LM012 HN-M500MBB 500GB  | 7         | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB       | 7         | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 7         | 1.2%    |
| Unknown MMC Card  64GB               | 5         | 0.85%   |
| Crucial CT240BX500SSD1 240GB         | 5         | 0.85%   |
| Unknown DA4064  64GB                 | 4         | 0.68%   |
| Toshiba MQ01ABD050 500GB             | 4         | 0.68%   |
| Seagate ST9320325AS 320GB            | 4         | 0.68%   |
| Seagate ST9250315AS 250GB            | 4         | 0.68%   |
| Samsung SSD 850 EVO 250GB            | 4         | 0.68%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.68%   |
| Hitachi HTS543216L9SA00 160GB        | 4         | 0.68%   |
| Hitachi HTS542512K9SA00 120GB        | 4         | 0.68%   |
| Crucial CT480BX500SSD1 480GB         | 4         | 0.68%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 3         | 0.51%   |
| WDC WD2500BEVT-80A23T0 250GB         | 3         | 0.51%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 3         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 0.51%   |
| Unknown MMC Card  16GB               | 3         | 0.51%   |
| Seagate ST98823AS 80GB               | 3         | 0.51%   |
| Seagate ST9250410AS 250GB            | 3         | 0.51%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 0.51%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 3         | 0.51%   |
| Samsung SSD 860 EVO 500GB            | 3         | 0.51%   |
| Samsung SSD 840 EVO 250GB            | 3         | 0.51%   |
| Samsung HN-M500MBB 500GB             | 3         | 0.51%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.51%   |
| Hitachi HTS541616J9SA00 160GB        | 3         | 0.51%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.51%   |
| HGST HTS545050A7E680 500GB           | 3         | 0.51%   |
| HGST HTS545050A7E380 500GB           | 3         | 0.51%   |
| HGST HTS541010A9E680 1TB             | 3         | 0.51%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 0.51%   |
| Unknown                              | 3         | 0.51%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 2         | 0.34%   |
| WDC WD3200BEVT-22A23T0 320GB         | 2         | 0.34%   |
| WDC WD1200BEVS-60UST0 120GB          | 2         | 0.34%   |
| WDC WD10SPZX-24Z10T0 1TB             | 2         | 0.34%   |
| WDC WD10JPVX-60JC3T1 1TB             | 2         | 0.34%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB | 2         | 0.34%   |
| Unknown NCard  32GB                  | 2         | 0.34%   |
| Unknown MMC Card  128GB              | 2         | 0.34%   |
| Unknown 128G32  128GB                | 2         | 0.34%   |
| Toshiba THNSFJ256GDNU A 256GB SSD    | 2         | 0.34%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.34%   |
| Toshiba MQ01ABF032 320GB             | 2         | 0.34%   |
| Toshiba MQ01ABD032 320GB             | 2         | 0.34%   |
| Toshiba MK2546GSX 250GB              | 2         | 0.34%   |
| Toshiba MK1646GSX 160GB              | 2         | 0.34%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 2         | 0.34%   |
| STEC PATA 16GB                       | 2         | 0.34%   |
| SK Hynix PC611 NVMe 512GB            | 2         | 0.34%   |
| SK Hynix HBG4e  32GB                 | 2         | 0.34%   |
| Seagate ST9750420AS 752GB            | 2         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 98     | 28.34%  |
| WDC                 | 71        | 89     | 23.13%  |
| Hitachi             | 50        | 64     | 16.29%  |
| Toshiba             | 45        | 50     | 14.66%  |
| HGST                | 17        | 20     | 5.54%   |
| Fujitsu             | 17        | 18     | 5.54%   |
| Samsung Electronics | 15        | 22     | 4.89%   |
| IBM/Hitachi         | 2         | 3      | 0.65%   |
| USB                 | 1         | 1      | 0.33%   |
| LaCie               | 1         | 1      | 0.33%   |
| Apple               | 1         | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 25        | 27     | 15.34%  |
| Samsung Electronics | 23        | 34     | 14.11%  |
| Crucial             | 22        | 25     | 13.5%   |
| Intel               | 14        | 18     | 8.59%   |
| SanDisk             | 10        | 14     | 6.13%   |
| WDC                 | 6         | 7      | 3.68%   |
| Apacer              | 6         | 6      | 3.68%   |
| Toshiba             | 5         | 6      | 3.07%   |
| China               | 5         | 7      | 3.07%   |
| A-DATA Technology   | 5         | 5      | 3.07%   |
| Transcend           | 3         | 3      | 1.84%   |
| Patriot             | 3         | 3      | 1.84%   |
| OCZ                 | 3         | 3      | 1.84%   |
| LITEONIT            | 3         | 3      | 1.84%   |
| LITEON              | 3         | 4      | 1.84%   |
| PNY                 | 2         | 2      | 1.23%   |
| Micron Technology   | 2         | 2      | 1.23%   |
| LDLC                | 2         | 2      | 1.23%   |
| KingDian            | 2         | 2      | 1.23%   |
| DOGFISH             | 2         | 2      | 1.23%   |
| Apple               | 2         | 8      | 1.23%   |
| Unknown             | 1         | 1      | 0.61%   |
| TEAM T25            | 1         | 1      | 0.61%   |
| TCSUNBOW            | 1         | 1      | 0.61%   |
| SPCC                | 1         | 1      | 0.61%   |
| SK Hynix            | 1         | 1      | 0.61%   |
| Seagate             | 1         | 1      | 0.61%   |
| NGFF                | 1         | 1      | 0.61%   |
| MyDigitalSSD        | 1         | 1      | 0.61%   |
| Mushkin             | 1         | 1      | 0.61%   |
| LS                  | 1         | 1      | 0.61%   |
| Lenovo              | 1         | 1      | 0.61%   |
| KingSpec            | 1         | 11     | 0.61%   |
| Integral            | 1         | 1      | 0.61%   |
| Gigabyte Technology | 1         | 1      | 0.61%   |
| Dell                | 1         | 1      | 0.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 303       | 367    | 54.5%   |
| SSD     | 158       | 208    | 28.42%  |
| MMC     | 49        | 62     | 8.81%   |
| NVMe    | 39        | 49     | 7.01%   |
| Unknown | 7         | 8      | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 434       | 566    | 80.97%  |
| MMC  | 49        | 62     | 9.14%   |
| NVMe | 39        | 49     | 7.28%   |
| SAS  | 14        | 17     | 2.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 356       | 459    | 78.94%  |
| 0.51-1.0   | 83        | 101    | 18.4%   |
| 1.01-2.0   | 8         | 11     | 1.77%   |
| 3.01-4.0   | 3         | 3      | 0.67%   |
| 4.01-10.0  | 1         | 1      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 154       | 29.56%  |
| 251-500        | 131       | 25.14%  |
| 51-100         | 60        | 11.52%  |
| 501-1000       | 54        | 10.36%  |
| 21-50          | 47        | 9.02%   |
| 1-20           | 46        | 8.83%   |
| 1001-2000      | 18        | 3.45%   |
| More than 3000 | 6         | 1.15%   |
| 2001-3000      | 4         | 0.77%   |
| Unknown        | 1         | 0.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 300       | 55.66%  |
| 21-50          | 95        | 17.63%  |
| 101-250        | 57        | 10.58%  |
| 51-100         | 40        | 7.42%   |
| 251-500        | 19        | 3.53%   |
| 501-1000       | 18        | 3.34%   |
| 1001-2000      | 6         | 1.11%   |
| More than 3000 | 2         | 0.37%   |
| 2001-3000      | 1         | 0.19%   |
| Unknown        | 1         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                      | Notebooks | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                  | 2         | 2      | 3.64%   |
| Seagate ST9320325AS 320GB                  | 2         | 2      | 3.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB         | 2         | 2      | 3.64%   |
| Hitachi HTS542512K9SA00 120GB              | 2         | 2      | 3.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD           | 1         | 1      | 1.82%   |
| WDC WD800BEVS-60RST0 80GB                  | 1         | 1      | 1.82%   |
| WDC WD3200BPVT-80ZEST0 320GB               | 1         | 1      | 1.82%   |
| WDC WD3200BEKT-60PVMT0 320GB               | 1         | 1      | 1.82%   |
| WDC WD2500BEVT-80A23T0 250GB               | 1         | 2      | 1.82%   |
| WDC WD1200BEVS-60UST0 120GB                | 1         | 1      | 1.82%   |
| WDC WD1200BEVS-07LAT0 120GB                | 1         | 1      | 1.82%   |
| WDC WD10JPVX-60JC3T1 1TB                   | 1         | 1      | 1.82%   |
| Toshiba MK3276GSX 320GB                    | 1         | 1      | 1.82%   |
| Toshiba MK2046GSX 200GB                    | 1         | 1      | 1.82%   |
| TCSUNBOW X1 32GB SSD                       | 1         | 1      | 1.82%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD      | 1         | 1      | 1.82%   |
| Seagate ST9250410AS 250GB                  | 1         | 1      | 1.82%   |
| Seagate ST9250315AS 250GB                  | 1         | 1      | 1.82%   |
| Seagate ST9160821AS 160GB                  | 1         | 1      | 1.82%   |
| Seagate ST500LT012-1DG142 500GB            | 1         | 1      | 1.82%   |
| Seagate ST500LM021-1KJ152 500GB            | 1         | 1      | 1.82%   |
| Seagate ST320LT007-9ZV142 320GB            | 1         | 1      | 1.82%   |
| Samsung Electronics HM160JI 160GB          | 1         | 1      | 1.82%   |
| Samsung Electronics HM121HI 120GB          | 1         | 3      | 1.82%   |
| OCZ VERTEX3 120GB SSD                      | 1         | 1      | 1.82%   |
| LITEON IT LST-16S9G-HP 16GB SSD            | 1         | 1      | 1.82%   |
| LITEON CV8-8E128-HP 128GB SSD              | 1         | 1      | 1.82%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD    | 1         | 1      | 1.82%   |
| KingSpec PA25-128 128GB SSD                | 1         | 11     | 1.82%   |
| Intel SSDSC2BF240A4L 240GB                 | 1         | 1      | 1.82%   |
| Intel SSDSC2BF180A5L 180GB                 | 1         | 1      | 1.82%   |
| Hitachi HTS725050A9A364 500GB              | 1         | 1      | 1.82%   |
| Hitachi HTS722012K9SA00 120GB              | 1         | 1      | 1.82%   |
| Hitachi HTS547564A9E384 640GB              | 1         | 1      | 1.82%   |
| Hitachi HTS545032B9A300 320GB              | 1         | 1      | 1.82%   |
| Hitachi HTS541616J9SA00 160GB              | 1         | 1      | 1.82%   |
| Hitachi HTS541040G9AT00 40GB               | 1         | 1      | 1.82%   |
| Hitachi HTS421280H9AT00 80GB               | 1         | 1      | 1.82%   |
| HGST HTS721010A9E630 1TB                   | 1         | 1      | 1.82%   |
| HGST HTS545050A7E680 500GB                 | 1         | 1      | 1.82%   |
| HGST HTS545050A7E380 500GB                 | 1         | 1      | 1.82%   |
| HGST HTS541075A9E680 752GB                 | 1         | 1      | 1.82%   |
| HGST HTS541010A9E680 1TB                   | 1         | 1      | 1.82%   |
| Fujitsu MHY2200BH 200GB                    | 1         | 1      | 1.82%   |
| Fujitsu MHW2080BH PL 80GB                  | 1         | 1      | 1.82%   |
| Crucial M4-CT512M4SSD2 512GB               | 1         | 1      | 1.82%   |
| Crucial CT960M500SSD1 960GB                | 1         | 1      | 1.82%   |
| Crucial CT500P1SSD8 500GB                  | 1         | 1      | 1.82%   |
| Crucial CT120M500SSD3 120GB                | 1         | 1      | 1.82%   |
| Crucial CT120M500SSD1 120GB                | 1         | 1      | 1.82%   |
| A-DATA Technology IM2S3334-256GD 256GB SSD | 1         | 1      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 21.82%  |
| Hitachi             | 9         | 9      | 16.36%  |
| WDC                 | 8         | 9      | 14.55%  |
| HGST                | 5         | 5      | 9.09%   |
| Crucial             | 5         | 5      | 9.09%   |
| Toshiba             | 2         | 2      | 3.64%   |
| Samsung Electronics | 2         | 4      | 3.64%   |
| LITEON              | 2         | 2      | 3.64%   |
| Intel               | 2         | 2      | 3.64%   |
| Fujitsu             | 2         | 2      | 3.64%   |
| TCSUNBOW            | 1         | 1      | 1.82%   |
| SK Hynix            | 1         | 1      | 1.82%   |
| OCZ                 | 1         | 1      | 1.82%   |
| Kingston            | 1         | 1      | 1.82%   |
| KingSpec            | 1         | 11     | 1.82%   |
| A-DATA Technology   | 1         | 1      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 30.77%  |
| Hitachi             | 9         | 9      | 23.08%  |
| WDC                 | 7         | 8      | 17.95%  |
| HGST                | 5         | 5      | 12.82%  |
| Toshiba             | 2         | 2      | 5.13%   |
| Samsung Electronics | 2         | 4      | 5.13%   |
| Fujitsu             | 2         | 2      | 5.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 42     | 70.91%  |
| SSD  | 15        | 25     | 27.27%  |
| NVMe | 1         | 1      | 1.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 33.33%  |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 33.33%  |
| Samsung Electronics HM320JI 320GB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 3      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 293       | 407    | 55.49%  |
| Works    | 177       | 215    | 33.52%  |
| Malfunc  | 55        | 68     | 10.42%  |
| Failed   | 3         | 4      | 0.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 363       | 72.17%  |
| AMD                              | 83        | 16.5%   |
| Nvidia                           | 10        | 1.99%   |
| Samsung Electronics              | 7         | 1.39%   |
| Silicon Integrated Systems [SiS] | 6         | 1.19%   |
| Sandisk                          | 6         | 1.19%   |
| SK Hynix                         | 5         | 0.99%   |
| KIOXIA                           | 5         | 0.99%   |
| Toshiba America Info Systems     | 4         | 0.8%    |
| Kingston Technology Company      | 4         | 0.8%    |
| VIA Technologies                 | 3         | 0.6%    |
| Phison Electronics               | 2         | 0.4%    |
| Micron Technology                | 2         | 0.4%    |
| Solid State Storage Technology   | 1         | 0.2%    |
| Micron/Crucial Technology        | 1         | 0.2%    |
| JMicron Technology               | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 47        | 7.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 40        | 6.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 35        | 5.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 32        | 5.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 30        | 5.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 29        | 4.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 24        | 4.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 23        | 3.89%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 20        | 3.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 20        | 3.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 17        | 2.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 17        | 2.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 16        | 2.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 12        | 2.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 12        | 2.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 10        | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 10        | 1.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 1.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 9         | 1.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 9         | 1.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 7         | 1.18%   |
| AMD IXP SB4x0 IDE Controller                                                           | 7         | 1.18%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 6         | 1.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 6         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 6         | 1.02%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 5         | 0.85%   |
| KIOXIA Non-Volatile memory controller                                                  | 5         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 5         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 5         | 0.85%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 5         | 0.85%   |
| Nvidia MCP67 AHCI Controller                                                           | 4         | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 0.68%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 4         | 0.68%   |
| AMD SB600 IDE                                                                          | 4         | 0.68%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 3         | 0.51%   |
| VIA VT8237A SATA 2-Port Controller                                                     | 3         | 0.51%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 0.51%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 3         | 0.51%   |
| Nvidia MCP67 IDE Controller                                                            | 3         | 0.51%   |
| Nvidia MCP51 Serial ATA Controller                                                     | 3         | 0.51%   |
| Nvidia MCP51 IDE                                                                       | 3         | 0.51%   |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 0.51%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 0.51%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 0.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 0.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 3         | 0.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 3         | 0.51%   |
| AMD IXP SB4x0 Serial ATA Controller                                                    | 3         | 0.51%   |
| SK Hynix Non-Volatile memory controller                                                | 2         | 0.34%   |
| SK Hynix BC511                                                                         | 2         | 0.34%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 0.34%   |
| Phison E12 NVMe Controller                                                             | 2         | 0.34%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                           | 2         | 0.34%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                       | 2         | 0.34%   |
| Micron Non-Volatile memory controller                                                  | 2         | 0.34%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 2         | 0.34%   |
| Intel SSD 660P Series                                                                  | 2         | 0.34%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 0.34%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 2         | 0.34%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 2         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 368       | 66.55%  |
| IDE  | 127       | 22.97%  |
| NVMe | 38        | 6.87%   |
| RAID | 20        | 3.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 420       | 82.03%  |
| AMD    | 92        | 17.97%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 9         | 1.76%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 9         | 1.76%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 1.37%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 1.17%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 6         | 1.17%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 1.17%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 6         | 1.17%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 6         | 1.17%   |
| AMD E-450 APU with Radeon HD Graphics         | 6         | 1.17%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 5         | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.98%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 5         | 0.98%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 5         | 0.98%   |
| AMD E-350 Processor                           | 5         | 0.98%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 4         | 0.78%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 4         | 0.78%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 4         | 0.78%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.78%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.78%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.78%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 0.78%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 0.78%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 4         | 0.78%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 4         | 0.78%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 0.78%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 0.78%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.59%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 3         | 0.59%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 3         | 0.59%   |
| Intel Pentium Dual CPU T2310 @ 1.46GHz        | 3         | 0.59%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.59%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 3         | 0.59%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 3         | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.59%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.59%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 0.59%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 0.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.59%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.59%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 3         | 0.59%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 3         | 0.59%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 3         | 0.59%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 3         | 0.59%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 3         | 0.59%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 0.59%   |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 3         | 0.59%   |
| Intel Core 2 CPU T5200 @ 1.60GHz              | 3         | 0.59%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.59%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 3         | 0.59%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 3         | 0.59%   |
| Intel Atom CPU N550 @ 1.50GHz                 | 3         | 0.59%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 3         | 0.59%   |
| AMD E1-1500 APU with Radeon HD Graphics       | 3         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 83        | 16.21%  |
| Intel Atom                     | 54        | 10.55%  |
| Intel Core i7                  | 53        | 10.35%  |
| Intel Celeron                  | 46        | 8.98%   |
| Intel Core i3                  | 43        | 8.4%    |
| Intel Core 2 Duo               | 43        | 8.4%    |
| Intel Pentium                  | 20        | 3.91%   |
| Intel Pentium Dual             | 17        | 3.32%   |
| AMD E                          | 14        | 2.73%   |
| Intel Pentium Dual-Core        | 13        | 2.54%   |
| Intel Genuine                  | 10        | 1.95%   |
| Intel Core 2                   | 10        | 1.95%   |
| AMD A4                         | 9         | 1.76%   |
| Other                          | 8         | 1.56%   |
| AMD E1                         | 8         | 1.56%   |
| AMD A6                         | 8         | 1.56%   |
| Intel Pentium M                | 5         | 0.98%   |
| Intel Celeron M                | 5         | 0.98%   |
| AMD Ryzen 7                    | 5         | 0.98%   |
| AMD Ryzen 5                    | 5         | 0.98%   |
| AMD E2                         | 5         | 0.98%   |
| AMD Mobile Sempron             | 4         | 0.78%   |
| Intel Pentium Silver           | 3         | 0.59%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.59%   |
| AMD Athlon 64 X2               | 3         | 0.59%   |
| AMD Athlon                     | 3         | 0.59%   |
| AMD A8                         | 3         | 0.59%   |
| Intel Pentium 4                | 2         | 0.39%   |
| Intel Core Duo                 | 2         | 0.39%   |
| Intel Celeron Dual-Core        | 2         | 0.39%   |
| AMD Ryzen 7 PRO                | 2         | 0.39%   |
| AMD Ryzen 3                    | 2         | 0.39%   |
| AMD C-60                       | 2         | 0.39%   |
| AMD C-50                       | 2         | 0.39%   |
| AMD Athlon X2                  | 2         | 0.39%   |
| Intel Mobile Pentium 4         | 1         | 0.2%    |
| Intel Core m3                  | 1         | 0.2%    |
| Intel Core 2 Solo              | 1         | 0.2%    |
| Intel Core 2 Extreme           | 1         | 0.2%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.2%    |
| AMD Turion 64 X2               | 1         | 0.2%    |
| AMD Turion 64 Mobile           | 1         | 0.2%    |
| AMD Ryzen 5 PRO                | 1         | 0.2%    |
| AMD Phenom II                  | 1         | 0.2%    |
| AMD C-70                       | 1         | 0.2%    |
| AMD C-30                       | 1         | 0.2%    |
| AMD Athlon II Dual-Core        | 1         | 0.2%    |
| AMD A10                        | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 355       | 69.34%  |
| 4      | 92        | 17.97%  |
| 1      | 53        | 10.35%  |
| 8      | 7         | 1.37%   |
| 6      | 5         | 0.98%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 512       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 277       | 54.1%   |
| 2      | 235       | 45.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 473       | 92.38%  |
| 32-bit         | 39        | 7.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 13.88%  |
| 0x206a7    | 39        | 7.41%   |
| 0x6fd      | 31        | 5.89%   |
| 0x1067a    | 23        | 4.37%   |
| 0x40651    | 22        | 4.18%   |
| 0x306a9    | 21        | 3.99%   |
| 0x20655    | 18        | 3.42%   |
| 0x106ca    | 17        | 3.23%   |
| 0x05000119 | 17        | 3.23%   |
| 0x406e3    | 16        | 3.04%   |
| 0x806ec    | 13        | 2.47%   |
| 0x406c4    | 13        | 2.47%   |
| 0x30678    | 12        | 2.28%   |
| 0x106c2    | 12        | 2.28%   |
| 0x406c3    | 10        | 1.9%    |
| 0x20652    | 10        | 1.9%    |
| 0x6f6      | 9         | 1.71%   |
| 0x6e8      | 9         | 1.71%   |
| 0x306c3    | 9         | 1.71%   |
| 0x10676    | 9         | 1.71%   |
| 0x6d8      | 8         | 1.52%   |
| 0x306d4    | 8         | 1.52%   |
| 0x05000029 | 8         | 1.52%   |
| 0x706a1    | 7         | 1.33%   |
| 0x06006705 | 7         | 1.33%   |
| 0x6fb      | 6         | 1.14%   |
| 0x806e9    | 5         | 0.95%   |
| 0x706a8    | 5         | 0.95%   |
| 0x30661    | 5         | 0.95%   |
| 0x10661    | 5         | 0.95%   |
| 0x906ea    | 4         | 0.76%   |
| 0x806eb    | 4         | 0.76%   |
| 0x806ea    | 4         | 0.76%   |
| 0x6ec      | 4         | 0.76%   |
| 0x0700010f | 4         | 0.76%   |
| 0x06006704 | 4         | 0.76%   |
| 0x706e5    | 3         | 0.57%   |
| 0x506c9    | 3         | 0.57%   |
| 0x30673    | 3         | 0.57%   |
| 0x08600106 | 3         | 0.57%   |
| 0x08600103 | 3         | 0.57%   |
| 0x0810100b | 3         | 0.57%   |
| 0x07030105 | 3         | 0.57%   |
| 0x806c1    | 2         | 0.38%   |
| 0x6fa      | 2         | 0.38%   |
| 0x506ca    | 2         | 0.38%   |
| 0x08108102 | 2         | 0.38%   |
| 0x07030106 | 2         | 0.38%   |
| 0x03000027 | 2         | 0.38%   |
| 0x02000057 | 2         | 0.38%   |
| 0x02000032 | 2         | 0.38%   |
| 0xf43      | 1         | 0.19%   |
| 0xf29      | 1         | 0.19%   |
| 0xf27      | 1         | 0.19%   |
| 0x906ed    | 1         | 0.19%   |
| 0x906e9    | 1         | 0.19%   |
| 0x806d1    | 1         | 0.19%   |
| 0x6b4      | 1         | 0.19%   |
| 0x506e3    | 1         | 0.19%   |
| 0x40661    | 1         | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Core            | 58        | 11.33%  |
| SandyBridge     | 44        | 8.59%   |
| Silvermont      | 41        | 8.01%   |
| KabyLake        | 36        | 7.03%   |
| Penryn          | 35        | 6.84%   |
| Haswell         | 35        | 6.84%   |
| Bonnell         | 34        | 6.64%   |
| Westmere        | 31        | 6.05%   |
| IvyBridge       | 26        | 5.08%   |
| Bobcat          | 26        | 5.08%   |
| P6              | 22        | 4.3%    |
| Skylake         | 19        | 3.71%   |
| Excavator       | 14        | 2.73%   |
| Goldmont plus   | 13        | 2.54%   |
| K8 Hammer       | 12        | 2.34%   |
| Broadwell       | 9         | 1.76%   |
| Puma            | 8         | 1.56%   |
| Zen 2           | 7         | 1.37%   |
| Zen             | 5         | 0.98%   |
| K8 & K10 hybrid | 5         | 0.98%   |
| Jaguar          | 5         | 0.98%   |
| Icelake         | 5         | 0.98%   |
| Goldmont        | 5         | 0.98%   |
| Zen+            | 4         | 0.78%   |
| TigerLake       | 3         | 0.59%   |
| NetBurst        | 3         | 0.59%   |
| Piledriver      | 2         | 0.39%   |
| K10 Llano       | 2         | 0.39%   |
| K10             | 2         | 0.39%   |
| Nehalem         | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 362       | 62.52%  |
| AMD                              | 129       | 22.28%  |
| Nvidia                           | 79        | 13.64%  |
| Silicon Integrated Systems [SiS] | 5         | 0.86%   |
| VIA Technologies                 | 3         | 0.52%   |
| S3 Graphics                      | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 39        | 6.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 36        | 5.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 36        | 5.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 26        | 4.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 25        | 3.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 25        | 3.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 3.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 23        | 3.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 21        | 3.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 2.5%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 16        | 2.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 2.18%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 13        | 2.03%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 13        | 2.03%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 10        | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.4%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 8         | 1.25%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 1.09%   |
| AMD Renoir                                                                               | 7         | 1.09%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                                 | 7         | 1.09%   |
| Intel HD Graphics 620                                                                    | 6         | 0.94%   |
| Intel HD Graphics 5500                                                                   | 6         | 0.94%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 6         | 0.94%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.94%   |
| Intel UHD Graphics 620                                                                   | 5         | 0.78%   |
| Intel HD Graphics 500                                                                    | 5         | 0.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 0.78%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 5         | 0.78%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 5         | 0.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 0.78%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 0.78%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 0.62%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 4         | 0.62%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 0.62%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 4         | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.62%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 0.47%   |
| Nvidia GT218M [NVS 3100M]                                                                | 3         | 0.47%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 3         | 0.47%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 3         | 0.47%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                                 | 3         | 0.47%   |
| Intel HD Graphics                                                                        | 3         | 0.47%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.47%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 3         | 0.47%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 3         | 0.47%   |
| AMD Kabini [Radeon HD 8210]                                                              | 3         | 0.47%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.31%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 0.31%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.31%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.31%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.31%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.31%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 2         | 0.31%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 0.31%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 2         | 0.31%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 2         | 0.31%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 2         | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 294       | 57.42%  |
| 1 x AMD         | 102       | 19.92%  |
| Intel + Nvidia  | 43        | 8.4%    |
| 1 x Nvidia      | 35        | 6.84%   |
| Intel + AMD     | 23        | 4.49%   |
| 1 x SiS         | 5         | 0.98%   |
| 2 x AMD         | 3         | 0.59%   |
| 1 x VIA         | 3         | 0.59%   |
| Other           | 2         | 0.39%   |
| 1 x S3 Graphics | 1         | 0.2%    |
| AMD + Nvidia    | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 466       | 90.84%  |
| Proprietary | 32        | 6.24%   |
| Unknown     | 15        | 2.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 305       | 58.99%  |
| 0.01-0.5   | 133       | 25.73%  |
| 1.01-2.0   | 38        | 7.35%   |
| 0.51-1.0   | 26        | 5.03%   |
| 3.01-4.0   | 11        | 2.13%   |
| 5.01-6.0   | 2         | 0.39%   |
| 2.01-3.0   | 2         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 95        | 18.66%  |
| Samsung Electronics     | 77        | 15.13%  |
| LG Display              | 66        | 12.97%  |
| Chimei Innolux          | 57        | 11.2%   |
| BOE                     | 53        | 10.41%  |
| Chi Mei Optoelectronics | 27        | 5.3%    |
| LG Philips              | 22        | 4.32%   |
| HannStar                | 16        | 3.14%   |
| Apple                   | 13        | 2.55%   |
| Lenovo                  | 9         | 1.77%   |
| CPT                     | 9         | 1.77%   |
| InfoVision              | 8         | 1.57%   |
| Goldstar                | 7         | 1.38%   |
| Acer                    | 7         | 1.38%   |
| Dell                    | 6         | 1.18%   |
| Hewlett-Packard         | 5         | 0.98%   |
| Sharp                   | 4         | 0.79%   |
| AOC                     | 3         | 0.59%   |
| Sony                    | 2         | 0.39%   |
| Philips                 | 2         | 0.39%   |
| PANDA                   | 2         | 0.39%   |
| NEC Computers           | 2         | 0.39%   |
| Vizio                   | 1         | 0.2%    |
| ViewSonic               | 1         | 0.2%    |
| Videoseven              | 1         | 0.2%    |
| Sceptre Tech            | 1         | 0.2%    |
| Panasonic               | 1         | 0.2%    |
| Nvidia                  | 1         | 0.2%    |
| NCS                     | 1         | 0.2%    |
| Lenovo Group Limited    | 1         | 0.2%    |
| KDC                     | 1         | 0.2%    |
| InnoLux Display         | 1         | 0.2%    |
| Iiyama                  | 1         | 0.2%    |
| IBM                     | 1         | 0.2%    |
| eMachines               | 1         | 0.2%    |
| DENON                   | 1         | 0.2%    |
| CVT                     | 1         | 0.2%    |
| BenQ                    | 1         | 0.2%    |
| ASUSTek Computer        | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 8         | 1.57%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 8         | 1.57%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 6         | 1.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 1.17%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.78%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 4         | 0.78%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 4         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 3         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.59%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch            | 3         | 0.59%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch              | 3         | 0.59%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 3         | 0.59%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 3         | 0.59%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 3         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 3         | 0.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 3         | 0.59%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 3         | 0.59%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 0.59%   |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                     | 3         | 0.59%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 3         | 0.59%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 0.59%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 3         | 0.59%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.59%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 3         | 0.59%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                  | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 2         | 0.39%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 2         | 0.39%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 2         | 0.39%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 2         | 0.39%   |
| CPT LCD Monitor CPT22CE 1024x600 210x127mm 9.7-inch                      | 2         | 0.39%   |
| CPT LCD Monitor CPT1BC7 1024x600 223x125mm 10.1-inch                     | 2         | 0.39%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch          | 2         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 2         | 0.39%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.39%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 0.39%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                     | 2         | 0.39%   |
| BOE LCD Monitor BOE05F0 1366x768 309x173mm 13.9-inch                     | 2         | 0.39%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch            | 2         | 0.39%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 2         | 0.39%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 2         | 0.39%   |
| AU Optronics LCD Monitor AUO6287 1440x900 370x230mm 17.2-inch            | 2         | 0.39%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 2         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 229       | 45.98%  |
| 1920x1080 (FHD)    | 90        | 18.07%  |
| 1280x800 (WXGA)    | 75        | 15.06%  |
| 1600x900 (HD+)     | 25        | 5.02%   |
| 1024x600           | 23        | 4.62%   |
| 1920x1200 (WUXGA)  | 14        | 2.81%   |
| 3840x2160 (4K)     | 8         | 1.61%   |
| 1680x1050 (WSXGA+) | 6         | 1.2%    |
| 1440x900 (WXGA+)   | 6         | 1.2%    |
| 2560x1440 (QHD)    | 4         | 0.8%    |
| 1280x1024 (SXGA)   | 4         | 0.8%    |
| 3840x2400          | 2         | 0.4%    |
| 1360x768           | 2         | 0.4%    |
| 3200x1800 (QHD+)   | 1         | 0.2%    |
| 3200x1080          | 1         | 0.2%    |
| 2880x1800          | 1         | 0.2%    |
| 2560x1600          | 1         | 0.2%    |
| 2288x1287          | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1280x768           | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |
| 1024x768 (XGA)     | 1         | 0.2%    |
| Unknown            | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 211       | 41.54%  |
| 14      | 74        | 14.57%  |
| 13      | 71        | 13.98%  |
| 11      | 28        | 5.51%   |
| 17      | 27        | 5.31%   |
| 10      | 22        | 4.33%   |
| 12      | 15        | 2.95%   |
| 27      | 8         | 1.57%   |
| Unknown | 8         | 1.57%   |
| 24      | 6         | 1.18%   |
| 21      | 6         | 1.18%   |
| 23      | 5         | 0.98%   |
| 22      | 5         | 0.98%   |
| 18      | 4         | 0.79%   |
| 19      | 3         | 0.59%   |
| 8       | 3         | 0.59%   |
| 72      | 2         | 0.39%   |
| 9       | 2         | 0.39%   |
| 84      | 1         | 0.2%    |
| 63      | 1         | 0.2%    |
| 48      | 1         | 0.2%    |
| 33      | 1         | 0.2%    |
| 31      | 1         | 0.2%    |
| 26      | 1         | 0.2%    |
| 25      | 1         | 0.2%    |
| 20      | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 317       | 62.65%  |
| 201-300     | 96        | 18.97%  |
| 351-400     | 37        | 7.31%   |
| 501-600     | 21        | 4.15%   |
| 401-500     | 17        | 3.36%   |
| Unknown     | 8         | 1.58%   |
| 1501-2000   | 3         | 0.59%   |
| 101-200     | 3         | 0.59%   |
| 1001-1500   | 2         | 0.4%    |
| 701-800     | 1         | 0.2%    |
| 601-700     | 1         | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 362       | 76.21%  |
| 16/10   | 103       | 21.68%  |
| Unknown | 4         | 0.84%   |
| 5/4     | 3         | 0.63%   |
| 4/3     | 3         | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 210       | 41.34%  |
| 81-90          | 123       | 24.21%  |
| 51-60          | 28        | 5.51%   |
| 71-80          | 24        | 4.72%   |
| 41-50          | 24        | 4.72%   |
| 121-130        | 20        | 3.94%   |
| 201-250        | 17        | 3.35%   |
| 61-70          | 13        | 2.56%   |
| 301-350        | 8         | 1.57%   |
| Unknown        | 8         | 1.57%   |
| 251-300        | 7         | 1.38%   |
| 131-140        | 6         | 1.18%   |
| More than 1000 | 5         | 0.98%   |
| 141-150        | 5         | 0.98%   |
| 151-200        | 4         | 0.79%   |
| 1-40           | 3         | 0.59%   |
| 351-500        | 2         | 0.39%   |
| 111-120        | 1         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 243       | 48.41%  |
| 121-160       | 127       | 25.3%   |
| 51-100        | 105       | 20.92%  |
| 161-240       | 9         | 1.79%   |
| Unknown       | 8         | 1.59%   |
| More than 240 | 6         | 1.2%    |
| 1-50          | 4         | 0.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 454       | 87.14%  |
| 2     | 53        | 10.17%  |
| 0     | 11        | 2.11%   |
| 3     | 3         | 0.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 264       | 31.21%  |
| Intel                             | 184       | 21.75%  |
| Qualcomm Atheros                  | 157       | 18.56%  |
| Broadcom                          | 88        | 10.4%   |
| Marvell Technology Group          | 26        | 3.07%   |
| Broadcom Limited                  | 23        | 2.72%   |
| Ralink                            | 19        | 2.25%   |
| Nvidia                            | 10        | 1.18%   |
| TP-Link                           | 9         | 1.06%   |
| Attansic Technology               | 9         | 1.06%   |
| Ralink Technology                 | 8         | 0.95%   |
| ASIX Electronics                  | 7         | 0.83%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.59%   |
| Xiaomi                            | 4         | 0.47%   |
| Samsung Electronics               | 4         | 0.47%   |
| AMD                               | 4         | 0.47%   |
| VIA Technologies                  | 3         | 0.35%   |
| Hewlett-Packard                   | 2         | 0.24%   |
| Dell                              | 2         | 0.24%   |
| Tenda                             | 1         | 0.12%   |
| Seeed                             | 1         | 0.12%   |
| Research In Motion                | 1         | 0.12%   |
| Qualcomm Atheros Communications   | 1         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.12%   |
| NetGear                           | 1         | 0.12%   |
| Microchip Technology              | 1         | 0.12%   |
| MEDIATEK                          | 1         | 0.12%   |
| Linksys                           | 1         | 0.12%   |
| LG Electronics                    | 1         | 0.12%   |
| Lab126                            | 1         | 0.12%   |
| JMicron Technology                | 1         | 0.12%   |
| Intersil                          | 1         | 0.12%   |
| Huawei Technologies               | 1         | 0.12%   |
| FIBOCOM                           | 1         | 0.12%   |
| Ericsson Business Mobile Networks | 1         | 0.12%   |
| Arduino SA                        | 1         | 0.12%   |
| 3Com                              | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 116       | 11.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 85        | 8.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 34        | 3.4%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 26        | 2.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 26        | 2.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 23        | 2.3%    |
| Intel Wireless 7260                                                           | 20        | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 18        | 1.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 17        | 1.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 17        | 1.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 17        | 1.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 11        | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 11        | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 10        | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                                    | 10        | 1%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 10        | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 10        | 1%      |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 10        | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 9         | 0.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 9         | 0.9%    |
| Intel 82577LM Gigabit Network Connection                                      | 9         | 0.9%    |
| Attansic AR8152 v2.0 Fast Ethernet                                            | 9         | 0.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 8         | 0.8%    |
| Intel Wireless 3160                                                           | 8         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 7         | 0.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 7         | 0.7%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 7         | 0.7%    |
| Intel Wireless 7265                                                           | 7         | 0.7%    |
| Intel WiFi Link 5100                                                          | 7         | 0.7%    |
| Intel Wi-Fi 6 AX200                                                           | 7         | 0.7%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 6         | 0.6%    |
| Realtek 802.11ac NIC                                                          | 6         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 6         | 0.6%    |
| Intel Wireless 8260                                                           | 6         | 0.6%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 6         | 0.6%    |
| Intel Ethernet Connection I218-LM                                             | 6         | 0.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 6         | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 6         | 0.6%    |
| Broadcom BCM4331 802.11a/b/g/n                                                | 6         | 0.6%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 6         | 0.6%    |
| Ralink MT7601U Wireless Adapter                                               | 5         | 0.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 5         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 5         | 0.5%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 5         | 0.5%    |
| Intel Wireless 8265 / 8275                                                    | 5         | 0.5%    |
| Intel Centrino Ultimate-N 6300                                                | 5         | 0.5%    |
| Intel 82567LM Gigabit Network Connection                                      | 5         | 0.5%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 5         | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 5         | 0.5%    |
| Broadcom BCM43142 802.11b/g/n                                                 | 5         | 0.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 4         | 0.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 4         | 0.4%    |
| Realtek RTL8723DE Wireless Network Adapter                                    | 4         | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 4         | 0.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4         | 0.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 4         | 0.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 4         | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 4         | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 4         | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 4         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 171       | 33.73%  |
| Qualcomm Atheros                | 137       | 27.02%  |
| Realtek Semiconductor           | 85        | 16.77%  |
| Broadcom                        | 57        | 11.24%  |
| Ralink                          | 19        | 3.75%   |
| Broadcom Limited                | 15        | 2.96%   |
| TP-Link                         | 9         | 1.78%   |
| Ralink Technology               | 8         | 1.58%   |
| Tenda                           | 1         | 0.2%    |
| Qualcomm Atheros Communications | 1         | 0.2%    |
| NetGear                         | 1         | 0.2%    |
| MEDIATEK                        | 1         | 0.2%    |
| Linksys                         | 1         | 0.2%    |
| Dell                            | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 34        | 6.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 26        | 5.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 26        | 5.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 23        | 4.5%    |
| Intel Wireless 7260                                                           | 20        | 3.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 17        | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 17        | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 17        | 3.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 11        | 2.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 10        | 1.96%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 10        | 1.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 10        | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 9         | 1.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 9         | 1.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 8         | 1.57%   |
| Intel Wireless 3160                                                           | 8         | 1.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 7         | 1.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 7         | 1.37%   |
| Intel Wireless 7265                                                           | 7         | 1.37%   |
| Intel WiFi Link 5100                                                          | 7         | 1.37%   |
| Intel Wi-Fi 6 AX200                                                           | 7         | 1.37%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 6         | 1.17%   |
| Realtek 802.11ac NIC                                                          | 6         | 1.17%   |
| Intel Wireless 8260                                                           | 6         | 1.17%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 6         | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 6         | 1.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 6         | 1.17%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 6         | 1.17%   |
| Ralink MT7601U Wireless Adapter                                               | 5         | 0.98%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 5         | 0.98%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 5         | 0.98%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 0.98%   |
| Intel Centrino Ultimate-N 6300                                                | 5         | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 5         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 4         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 4         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 4         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 4         | 0.78%   |
| Intel Wireless 3165                                                           | 4         | 0.78%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 4         | 0.78%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 4         | 0.78%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                   | 4         | 0.78%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 4         | 0.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 3         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 0.59%   |
| Realtek RTL8187B Wireless Adapter                                             | 3         | 0.59%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 3         | 0.59%   |
| Intel Wi-Fi 6 AX201                                                           | 3         | 0.59%   |
| Intel Ultimate N WiFi Link 5300                                               | 3         | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 0.59%   |
| Intel Centrino Wireless-N 130                                                 | 3         | 0.59%   |
| Intel Centrino Wireless-N 100                                                 | 3         | 0.59%   |
| Intel Centrino Advanced-N 6200                                                | 3         | 0.59%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 3         | 0.59%   |
| Broadcom Limited BCM4311 802.11a/b/g                                          | 3         | 0.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2         | 0.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2         | 0.39%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 2         | 0.39%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 2         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 232       | 49.57%  |
| Intel                            | 68        | 14.53%  |
| Qualcomm Atheros                 | 43        | 9.19%   |
| Broadcom                         | 40        | 8.55%   |
| Marvell Technology Group         | 26        | 5.56%   |
| Nvidia                           | 10        | 2.14%   |
| Attansic Technology              | 9         | 1.92%   |
| Broadcom Limited                 | 8         | 1.71%   |
| ASIX Electronics                 | 7         | 1.5%    |
| Silicon Integrated Systems [SiS] | 5         | 1.07%   |
| Xiaomi                           | 4         | 0.85%   |
| VIA Technologies                 | 3         | 0.64%   |
| Samsung Electronics              | 3         | 0.64%   |
| Research In Motion               | 1         | 0.21%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.21%   |
| Microchip Technology             | 1         | 0.21%   |
| LG Electronics                   | 1         | 0.21%   |
| Lab126                           | 1         | 0.21%   |
| JMicron Technology               | 1         | 0.21%   |
| Intersil                         | 1         | 0.21%   |
| Hewlett-Packard                  | 1         | 0.21%   |
| FIBOCOM                          | 1         | 0.21%   |
| 3Com                             | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 116       | 24.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 85        | 18.09%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 18        | 3.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 11        | 2.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 10        | 2.13%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                | 10        | 2.13%   |
| Intel 82577LM Gigabit Network Connection                             | 9         | 1.91%   |
| Attansic AR8152 v2.0 Fast Ethernet                                   | 9         | 1.91%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                 | 7         | 1.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 6         | 1.28%   |
| Intel Ethernet Connection I218-LM                                    | 6         | 1.28%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 6         | 1.28%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                | 5         | 1.06%   |
| Intel 82567LM Gigabit Network Connection                             | 5         | 1.06%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                    | 5         | 1.06%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                      | 5         | 1.06%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter        | 4         | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 4         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 4         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 4         | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 4         | 0.85%   |
| Nvidia MCP67 Ethernet                                                | 4         | 0.85%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller              | 4         | 0.85%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                 | 4         | 0.85%   |
| Intel Ethernet Connection I219-V                                     | 4         | 0.85%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express             | 4         | 0.85%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express       | 4         | 0.85%   |
| Broadcom BCM4401-B0 100Base-TX                                       | 4         | 0.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                         | 3         | 0.64%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                           | 3         | 0.64%   |
| Nvidia MCP51 Ethernet Controller                                     | 3         | 0.64%   |
| Intel PRO/100 VE Network Connection                                  | 3         | 0.64%   |
| Intel Ethernet Connection I217-LM                                    | 3         | 0.64%   |
| Intel 82579V Gigabit Network Connection                              | 3         | 0.64%   |
| Intel 82577LC Gigabit Network Connection                             | 3         | 0.64%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express               | 3         | 0.64%   |
| ASIX AX88772A Fast Ethernet                                          | 3         | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                        | 3         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 2         | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                 | 2         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 2         | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 2         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller            | 2         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 2         | 0.43%   |
| Nvidia MCP77 Ethernet                                                | 2         | 0.43%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller              | 2         | 0.43%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller              | 2         | 0.43%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller              | 2         | 0.43%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                 | 2         | 0.43%   |
| Intel Ethernet Connection I219-LM                                    | 2         | 0.43%   |
| Intel Ethernet Connection (4) I219-LM                                | 2         | 0.43%   |
| Intel 82573L Gigabit Ethernet Controller                             | 2         | 0.43%   |
| Intel 82566MM Gigabit Network Connection                             | 2         | 0.43%   |
| Intel 82562GT 10/100 Network Connection                              | 2         | 0.43%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 2         | 0.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                    | 2         | 0.43%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express              | 2         | 0.43%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express             | 2         | 0.43%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                      | 2         | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 2         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 484       | 51.05%  |
| Ethernet | 446       | 47.05%  |
| Modem    | 18        | 1.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 433       | 63.68%  |
| Ethernet | 246       | 36.18%  |
| Modem    | 1         | 0.15%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 403       | 78.71%  |
| 1     | 78        | 15.23%  |
| 0     | 26        | 5.08%   |
| 3     | 5         | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 458       | 88.08%  |
| Yes  | 62        | 11.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 91        | 29.45%  |
| Qualcomm Atheros Communications | 31        | 10.03%  |
| Realtek Semiconductor           | 30        | 9.71%   |
| Broadcom                        | 27        | 8.74%   |
| Cambridge Silicon Radio         | 17        | 5.5%    |
| Lite-On Technology              | 14        | 4.53%   |
| IMC Networks                    | 14        | 4.53%   |
| Hewlett-Packard                 | 14        | 4.53%   |
| Apple                           | 12        | 3.88%   |
| Foxconn / Hon Hai               | 11        | 3.56%   |
| Dell                            | 11        | 3.56%   |
| Toshiba                         | 9         | 2.91%   |
| Ralink                          | 8         | 2.59%   |
| Alps Electric                   | 8         | 2.59%   |
| ASUSTek Computer                | 4         | 1.29%   |
| Ralink Technology               | 2         | 0.65%   |
| Askey Computer                  | 2         | 0.65%   |
| Qcom                            | 1         | 0.32%   |
| Micro Star International        | 1         | 0.32%   |
| MediaTek                        | 1         | 0.32%   |
| Chicony Electronics             | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 53        | 17.1%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 17        | 5.48%   |
| Realtek Bluetooth Radio                                                             | 16        | 5.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 16        | 5.16%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 4.19%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 2.58%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 2.58%   |
| Apple Bluetooth Host Controller                                                     | 8         | 2.58%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 7         | 2.26%   |
| Intel AX200 Bluetooth                                                               | 7         | 2.26%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 1.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 1.94%   |
| Lite-On Bluetooth Device                                                            | 6         | 1.94%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1.94%   |
| Intel Bluetooth Device                                                              | 5         | 1.61%   |
| IMC Networks Bluetooth module                                                       | 5         | 1.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 5         | 1.61%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.61%   |
| Toshiba Integrated Bluetooth HCI                                                    | 4         | 1.29%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 1.29%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.29%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 1.29%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 1.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 0.97%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 0.97%   |
| IMC Networks Bluetooth Device                                                       | 3         | 0.97%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.97%   |
| Dell Wireless 365 Bluetooth                                                         | 3         | 0.97%   |
| Dell Wireless 350 Bluetooth                                                         | 3         | 0.97%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 0.97%   |
| Broadcom BCM2045 Bluetooth                                                          | 3         | 0.97%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.97%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                                     | 3         | 0.97%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.65%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.65%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 2         | 0.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.65%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.65%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.65%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 2         | 0.65%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 2         | 0.65%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.65%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.65%   |
| Askey Bluetooth Device                                                              | 2         | 0.65%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 2         | 0.65%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 2         | 0.65%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.32%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.32%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.32%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.32%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.32%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.32%   |
| Micro Star International Bluetooth EDR Device                                       | 1         | 0.32%   |
| MediaTek BT                                                                         | 1         | 0.32%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.32%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.32%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.32%   |
| IMC Networks Broadcom Bluetooth 2.1                                                 | 1         | 0.32%   |
| IMC Networks Bluetooth                                                              | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 382       | 70.35%  |
| AMD                               | 100       | 18.42%  |
| Nvidia                            | 42        | 7.73%   |
| Silicon Integrated Systems [SiS]  | 6         | 1.1%    |
| VIA Technologies                  | 3         | 0.55%   |
| GN Netcom                         | 3         | 0.55%   |
| Plantronics                       | 2         | 0.37%   |
| Logitech                          | 2         | 0.37%   |
| C-Media Electronics               | 2         | 0.37%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 49        | 7.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 42        | 6.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 37        | 5.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 33        | 5.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 33        | 5.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 32        | 4.86%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 4.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 26        | 3.95%   |
| Intel 8 Series HD Audio Controller                                                                | 25        | 3.8%    |
| AMD FCH Azalia Controller                                                                         | 25        | 3.8%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 24        | 3.65%   |
| AMD Wrestler HDMI Audio                                                                           | 23        | 3.5%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 2.43%   |
| AMD Kabini HDMI/DP Audio                                                                          | 14        | 2.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 13        | 1.98%   |
| AMD High Definition Audio Controller                                                              | 13        | 1.98%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 1.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 1.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.37%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 1.37%   |
| Nvidia High Definition Audio Controller                                                           | 8         | 1.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 0.91%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 5         | 0.76%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.76%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 0.76%   |
| Nvidia MCP67 High Definition Audio                                                                | 4         | 0.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.61%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 4         | 0.61%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 0.61%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 4         | 0.61%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.46%   |
| Nvidia MCP51 High Definition Audio                                                                | 3         | 0.46%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.46%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 3         | 0.46%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.3%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.3%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.3%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.3%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 0.3%    |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.3%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2         | 0.3%    |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 2         | 0.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.3%    |
| GN Netcom Jabra EVOLVE LINK                                                                       | 2         | 0.3%    |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.3%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.3%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.3%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.3%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.3%    |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.15%   |
| Plantronics GameCom 780/788                                                                       | 1         | 0.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 81        | 23.14%  |
| Unknown             | 73        | 20.86%  |
| SK Hynix            | 62        | 17.71%  |
| Micron Technology   | 31        | 8.86%   |
| Kingston            | 18        | 5.14%   |
| A-DATA Technology   | 12        | 3.43%   |
| Corsair             | 11        | 3.14%   |
| Crucial             | 10        | 2.86%   |
| Nanya Technology    | 9         | 2.57%   |
| Elpida              | 7         | 2%      |
| Unknown (ABCD)      | 6         | 1.71%   |
| Smart               | 5         | 1.43%   |
| Team                | 3         | 0.86%   |
| Teikon              | 2         | 0.57%   |
| Qimonda             | 2         | 0.57%   |
| Patriot             | 2         | 0.57%   |
| Apacer              | 2         | 0.57%   |
| Transcend           | 1         | 0.29%   |
| Toshiba             | 1         | 0.29%   |
| SMART Brazil        | 1         | 0.29%   |
| Sesame              | 1         | 0.29%   |
| Ramaxel Technology  | 1         | 0.29%   |
| PNY                 | 1         | 0.29%   |
| Neo Forza           | 1         | 0.29%   |
| Multilaser          | 1         | 0.29%   |
| High Bridge         | 1         | 0.29%   |
| Goldkey             | 1         | 0.29%   |
| G.Skill             | 1         | 0.29%   |
| DigiBoard           | 1         | 0.29%   |
| Avant               | 1         | 0.29%   |
| ASint Technology    | 1         | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 11        | 2.86%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 8         | 2.08%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 7         | 1.82%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 6         | 1.56%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 6         | 1.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 1.56%   |
| Unknown RAM Module 1024MB SODIMM DRAM                            | 5         | 1.3%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 5         | 1.3%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 1.04%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 4         | 1.04%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 4         | 1.04%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 4         | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.78%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 3         | 0.78%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 0.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR3 2400MT/s   | 3         | 0.78%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.78%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 3         | 0.78%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.78%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.78%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s         | 3         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.78%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.78%   |
| Kingston RAM ACR16D3LS1KNG/4G 4GB SODIMM DDR3 1600MT/s           | 3         | 0.78%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                        | 2         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 2         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 2         | 0.52%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.52%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 2         | 0.52%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 2         | 0.52%   |
| SK Hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.52%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.52%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.52%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 2         | 0.52%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.52%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.52%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 2         | 0.52%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 2         | 0.52%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.52%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.52%   |
| Samsung RAM M4 70T2864QZ3-CF7 1GB SODIMM DDR 2048MT/s            | 2         | 0.52%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.52%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.52%   |
| Micron RAM Module 8192MB SODIMM DDR4 2667MT/s                    | 2         | 0.52%   |
| Micron RAM Module 4096MB SODIMM DDR4 3200MT/s                    | 2         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.52%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s         | 2         | 0.52%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 0.52%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.52%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s                      | 2         | 0.52%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.52%   |
| Corsair RAM CMSO8GX3M1C1600C11 8192MB SODIMM DDR3 1600MT/s       | 2         | 0.52%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                | 2         | 0.52%   |
| Unknown RAM Q1040005.......... 4GB SODIMM DDR3 1067MT/s          | 1         | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 152       | 49.51%  |
| DDR4    | 65        | 21.17%  |
| DDR2    | 45        | 14.66%  |
| SDRAM   | 12        | 3.91%   |
| LPDDR4  | 10        | 3.26%   |
| LPDDR3  | 7         | 2.28%   |
| DRAM    | 7         | 2.28%   |
| DDR     | 6         | 1.95%   |
| Unknown | 3         | 0.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 283       | 93.71%  |
| Row Of Chips | 11        | 3.64%   |
| DIMM         | 5         | 1.66%   |
| Unknown      | 2         | 0.66%   |
| Chip         | 1         | 0.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 129       | 36.34%  |
| 2048  | 94        | 26.48%  |
| 8192  | 62        | 17.46%  |
| 1024  | 45        | 12.68%  |
| 16384 | 15        | 4.23%   |
| 512   | 7         | 1.97%   |
| 32768 | 1         | 0.28%   |
| 256   | 1         | 0.28%   |
| 128   | 1         | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 83        | 25.15%  |
| 1334    | 33        | 10%     |
| Unknown | 27        | 8.18%   |
| 2667    | 26        | 7.88%   |
| 2400    | 25        | 7.58%   |
| 667     | 25        | 7.58%   |
| 1333    | 24        | 7.27%   |
| 3200    | 16        | 4.85%   |
| 1067    | 11        | 3.33%   |
| 533     | 11        | 3.33%   |
| 2133    | 9         | 2.73%   |
| 1066    | 9         | 2.73%   |
| 3266    | 6         | 1.82%   |
| 2048    | 5         | 1.52%   |
| 800     | 5         | 1.52%   |
| 4199    | 3         | 0.91%   |
| 1867    | 3         | 0.91%   |
| 4267    | 2         | 0.61%   |
| 975     | 2         | 0.61%   |
| 8400    | 1         | 0.3%    |
| 1866    | 1         | 0.3%    |
| 1200    | 1         | 0.3%    |
| 2       | 1         | 0.3%    |
| 1       | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 3         | 27.27%  |
| Brother Industries    | 3         | 27.27%  |
| Samsung Electronics   | 2         | 18.18%  |
| STMicroelectronics    | 1         | 9.09%   |
| Lexmark International | 1         | 9.09%   |
| Canon                 | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| STMicroelectronics USB Printer P     | 1         | 9.09%   |
| Samsung SCX-4200 series              | 1         | 9.09%   |
| Samsung ML-1640 Series Laser Printer | 1         | 9.09%   |
| Lexmark International MS610de        | 1         | 9.09%   |
| HP LaserJet 1200                     | 1         | 9.09%   |
| HP Deskjet 3520 series               | 1         | 9.09%   |
| HP Deskjet 1050 J410                 | 1         | 9.09%   |
| Canon MF3110                         | 1         | 9.09%   |
| Brother PTUSB Printing               | 1         | 9.09%   |
| Brother PT-2450DX                    | 1         | 9.09%   |
| Brother DCP-7055W                    | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 50%     |
| Canon CanoScan LiDE 500F                                      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 112       | 27.93%  |
| IMC Networks                           | 33        | 8.23%   |
| Realtek Semiconductor                  | 30        | 7.48%   |
| Suyin                                  | 26        | 6.48%   |
| Microdia                               | 26        | 6.48%   |
| Acer                                   | 25        | 6.23%   |
| Silicon Motion                         | 17        | 4.24%   |
| Alcor Micro                            | 17        | 4.24%   |
| Sunplus Innovation Technology          | 14        | 3.49%   |
| Quanta                                 | 14        | 3.49%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.24%   |
| Apple                                  | 13        | 3.24%   |
| Syntek                                 | 9         | 2.24%   |
| Ricoh                                  | 9         | 2.24%   |
| Lite-On Technology                     | 8         | 2%      |
| Lenovo                                 | 6         | 1.5%    |
| Importek                               | 4         | 1%      |
| GEMBIRD                                | 3         | 0.75%   |
| Z-Star Microelectronics                | 2         | 0.5%    |
| USB Camera                             | 2         | 0.5%    |
| Samsung Electronics                    | 2         | 0.5%    |
| Luxvisions Innotech Limited            | 2         | 0.5%    |
| ALi                                    | 2         | 0.5%    |
| Y Media                                | 1         | 0.25%   |
| Toshiba                                | 1         | 0.25%   |
| OmniVision Technologies                | 1         | 0.25%   |
| Novatek Microelectronics               | 1         | 0.25%   |
| Nintendo                               | 1         | 0.25%   |
| Logitech                               | 1         | 0.25%   |
| LG Electronics                         | 1         | 0.25%   |
| Genesys Logic                          | 1         | 0.25%   |
| Generalplus Technology                 | 1         | 0.25%   |
| DigiTech                               | 1         | 0.25%   |
| Creative Technology                    | 1         | 0.25%   |
| CQG-5693-201019                        | 1         | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 10        | 2.48%   |
| Chicony Integrated Camera                           | 9         | 2.23%   |
| Alcor Micro USB 2.0 Web Camera                      | 9         | 2.23%   |
| Chicony HP Truevision HD                            | 7         | 1.73%   |
| IMC Networks UVC VGA Webcam                         | 6         | 1.49%   |
| Chicony TOSHIBA Web Camera - HD                     | 6         | 1.49%   |
| Chicony HP HD Webcam                                | 6         | 1.49%   |
| Silicon Motion WebCam SC-0311139N                   | 5         | 1.24%   |
| IMC Networks USB 2.0 UVC VGA WebCam                 | 5         | 1.24%   |
| Chicony HP Webcam                                   | 5         | 1.24%   |
| Chicony HD WebCam                                   | 5         | 1.24%   |
| Chicony EasyCamera                                  | 5         | 1.24%   |
| Apple FaceTime HD Camera                            | 5         | 1.24%   |
| Acer Lenovo EasyCamera                              | 5         | 1.24%   |
| Suyin Acer CrystalEye Webcam                        | 4         | 0.99%   |
| Sunplus HD WebCam                                   | 4         | 0.99%   |
| Quanta HP Webcam                                    | 4         | 0.99%   |
| Lenovo Integrated Webcam [R5U877]                   | 4         | 0.99%   |
| Chicony USB 2.0 Camera                              | 4         | 0.99%   |
| Chicony HP HD Camera                                | 4         | 0.99%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 4         | 0.99%   |
| Alcor Micro Asus Integrated Webcam                  | 4         | 0.99%   |
| Suyin WebCam                                        | 3         | 0.74%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 0.74%   |
| Realtek Integrated Webcam                           | 3         | 0.74%   |
| Quanta HP HD Camera                                 | 3         | 0.74%   |
| Microdia Sonix USB 2.0 Camera                       | 3         | 0.74%   |
| Microdia Laptop_Integrated_Webcam_2M                | 3         | 0.74%   |
| Microdia 1.3 MPixel Integrated Webcam               | 3         | 0.74%   |
| Lite-On TOSHIBA Web Camera - HD                     | 3         | 0.74%   |
| Lite-On HP HD Camera                                | 3         | 0.74%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 0.74%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 3         | 0.74%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 0.74%   |
| IMC Networks USB 2.0 Camera                         | 3         | 0.74%   |
| IMC Networks Lenovo EasyCamera                      | 3         | 0.74%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]   | 3         | 0.74%   |
| Chicony Lenovo EasyCamera                           | 3         | 0.74%   |
| Chicony Integrated HP HD Webcam                     | 3         | 0.74%   |
| Chicony HD WebCam (Acer)                            | 3         | 0.74%   |
| Chicony Camera                                      | 3         | 0.74%   |
| Apple iPhone 5/5C/5S/6/SE                           | 3         | 0.74%   |
| Acer VGA WebCam                                     | 3         | 0.74%   |
| Acer HD WebCam                                      | 3         | 0.74%   |
| USB Camera USB Camera                               | 2         | 0.5%    |
| Syntek Integrated Camera                            | 2         | 0.5%    |
| Syntek EasyCamera                                   | 2         | 0.5%    |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 0.5%    |
| Sunplus Laptop Integrated Webcam HD                 | 2         | 0.5%    |
| Sunplus Integrated_Webcam_HD                        | 2         | 0.5%    |
| Sunplus HP HD Webcam [Fixed]                        | 2         | 0.5%    |
| Silicon Motion WebCam SC-13HDL11939N                | 2         | 0.5%    |
| Silicon Motion WebCam SC-10HDD12636N                | 2         | 0.5%    |
| Samsung Galaxy A5 (MTP)                             | 2         | 0.5%    |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 2         | 0.5%    |
| Realtek USB2.0 HD UVC WebCam                        | 2         | 0.5%    |
| Realtek USB Camera                                  | 2         | 0.5%    |
| Realtek Lenovo EasyCamera                           | 2         | 0.5%    |
| Realtek Integrated Webcam HD                        | 2         | 0.5%    |
| Realtek HD WebCam                                   | 2         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 45.45%  |
| AuthenTec                  | 11        | 20%     |
| Upek                       | 7         | 12.73%  |
| STMicroelectronics         | 4         | 7.27%   |
| Shenzhen Goodix Technology | 4         | 7.27%   |
| Synaptics                  | 3         | 5.45%   |
| LighTuning Technology      | 1         | 1.82%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 6         | 10.91%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 5         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 4         | 7.27%   |
| STMicroelectronics Fingerprint Reader                      | 4         | 7.27%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 3         | 5.45%   |
| AuthenTec AES2810                                          | 3         | 5.45%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 3         | 5.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 3.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 3.64%   |
| Validity Sensors VFS491                                    | 2         | 3.64%   |
| Validity Sensors Fingerprint scanner                       | 2         | 3.64%   |
| Shenzhen Goodix FingerPrint                                | 2         | 3.64%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 2         | 3.64%   |
| AuthenTec AES1600                                          | 2         | 3.64%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.82%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.82%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 1.82%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 1.82%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.82%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 1.82%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.82%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 1.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 1.82%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 1.82%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 1.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 1.82%   |
| AuthenTec Fingerprint Sensor                               | 1         | 1.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| O2 Micro              | 6         | 30%     |
| Broadcom              | 6         | 30%     |
| Alcor Micro           | 6         | 30%     |
| Upek                  | 1         | 5%      |
| Realtek Semiconductor | 1         | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 30%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 15%     |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 10%     |
| Broadcom 5880                                                                | 2         | 10%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5%      |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 388       | 75.34%  |
| 1     | 102       | 19.81%  |
| 2     | 20        | 3.88%   |
| 3     | 4         | 0.78%   |
| 4     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 55        | 35.26%  |
| Graphics card            | 21        | 13.46%  |
| Net/wireless             | 20        | 12.82%  |
| Chipcard                 | 18        | 11.54%  |
| Bluetooth                | 10        | 6.41%   |
| Modem                    | 7         | 4.49%   |
| Storage                  | 5         | 3.21%   |
| Flash memory             | 4         | 2.56%   |
| Camera                   | 4         | 2.56%   |
| Net/ethernet             | 3         | 1.92%   |
| Multimedia controller    | 3         | 1.92%   |
| Communication controller | 3         | 1.92%   |
| Sound                    | 2         | 1.28%   |
| Card reader              | 1         | 0.64%   |

