Fedora 37 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 37.

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

Total: 1747

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [9e217a08be](https://linux-hardware.org/?probe=9e217a08be) | Dec 16, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [6a493a834d](https://linux-hardware.org/?probe=6a493a834d) | Dec 14, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [9d34609e0d](https://linux-hardware.org/?probe=9d34609e0d) | Dec 14, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [d31e9bc5eb](https://linux-hardware.org/?probe=d31e9bc5eb) | Dec 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [140789380e](https://linux-hardware.org/?probe=140789380e) | Dec 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2cc6eaff05](https://linux-hardware.org/?probe=2cc6eaff05) | Dec 08, 2023 |
| Dynabook      | PORTEGE X50-G               | [65a2f2f3d5](https://linux-hardware.org/?probe=65a2f2f3d5) | Dec 01, 2023 |
| HP            | EliteBook 850 G6            | [597c5faf3a](https://linux-hardware.org/?probe=597c5faf3a) | Nov 27, 2023 |
| Matsushita... | CF-30FCDALAM                | [94d60b91d5](https://linux-hardware.org/?probe=94d60b91d5) | Nov 25, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [2b2ac91a50](https://linux-hardware.org/?probe=2b2ac91a50) | Nov 24, 2023 |
| Lenovo        | ThinkPad T490 20N2000NRT    | [fa750668a7](https://linux-hardware.org/?probe=fa750668a7) | Nov 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [47d681f4e6](https://linux-hardware.org/?probe=47d681f4e6) | Nov 13, 2023 |
| Lenovo        | ThinkPad T490 20N2000NRT    | [fe5dd30b3d](https://linux-hardware.org/?probe=fe5dd30b3d) | Nov 10, 2023 |
| ASUSTek       | N552VW                      | [b8f226f7f0](https://linux-hardware.org/?probe=b8f226f7f0) | Nov 07, 2023 |
| HP            | Dragonfly Folio 13.5 inc... | [ffb075a639](https://linux-hardware.org/?probe=ffb075a639) | Oct 24, 2023 |
| ASUSTek       | X510UQ                      | [0494369566](https://linux-hardware.org/?probe=0494369566) | Oct 12, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [60a4c67d48](https://linux-hardware.org/?probe=60a4c67d48) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [65a1ff3587](https://linux-hardware.org/?probe=65a1ff3587) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [a1ae219e54](https://linux-hardware.org/?probe=a1ae219e54) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ee95e8f5fd](https://linux-hardware.org/?probe=ee95e8f5fd) | Oct 05, 2023 |
| Dell          | Inspiron 5459               | [965f7580d3](https://linux-hardware.org/?probe=965f7580d3) | Oct 05, 2023 |
| HP            | EliteBook 840 G1            | [2447ea5d85](https://linux-hardware.org/?probe=2447ea5d85) | Oct 04, 2023 |
| HP            | EliteBook 735 G5            | [5600a75dba](https://linux-hardware.org/?probe=5600a75dba) | Oct 04, 2023 |
| HP            | EliteBook 745 G3            | [700c901144](https://linux-hardware.org/?probe=700c901144) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | [16f4068970](https://linux-hardware.org/?probe=16f4068970) | Sep 30, 2023 |
| HP            | ProBook 430 G5              | [9e68b6e2be](https://linux-hardware.org/?probe=9e68b6e2be) | Sep 28, 2023 |
| Dell          | Inspiron 7577               | [a90c8128d1](https://linux-hardware.org/?probe=a90c8128d1) | Sep 26, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [b7d1f6f3cf](https://linux-hardware.org/?probe=b7d1f6f3cf) | Sep 20, 2023 |
| MSI           | Summit E15 A11SCST          | [aa908f1cea](https://linux-hardware.org/?probe=aa908f1cea) | Sep 19, 2023 |
| Acer          | Aspire A315-59              | [d00d3fed03](https://linux-hardware.org/?probe=d00d3fed03) | Sep 18, 2023 |
| Lenovo        | G505 20240                  | [db2962124c](https://linux-hardware.org/?probe=db2962124c) | Sep 14, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [92762d264f](https://linux-hardware.org/?probe=92762d264f) | Sep 11, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [b37cf7f8cf](https://linux-hardware.org/?probe=b37cf7f8cf) | Aug 30, 2023 |
| HP            | Laptop 17-by0xxx            | [4617fe766a](https://linux-hardware.org/?probe=4617fe766a) | Aug 29, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [6e84e686ec](https://linux-hardware.org/?probe=6e84e686ec) | Aug 25, 2023 |
| ASUSTek       | X540UP                      | [7041925c33](https://linux-hardware.org/?probe=7041925c33) | Aug 23, 2023 |
| Toshiba       | Satellite L515              | [fa5d7d5547](https://linux-hardware.org/?probe=fa5d7d5547) | Aug 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [34f09bffb0](https://linux-hardware.org/?probe=34f09bffb0) | Aug 20, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [bbf57bf744](https://linux-hardware.org/?probe=bbf57bf744) | Aug 17, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [83879b8247](https://linux-hardware.org/?probe=83879b8247) | Aug 11, 2023 |
| Fujitsu       | UH-X                        | [e26b430aef](https://linux-hardware.org/?probe=e26b430aef) | Aug 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [2980681052](https://linux-hardware.org/?probe=2980681052) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [08b395f8d6](https://linux-hardware.org/?probe=08b395f8d6) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [4dec7b692a](https://linux-hardware.org/?probe=4dec7b692a) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2771828543](https://linux-hardware.org/?probe=2771828543) | Aug 06, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | [ca0d3636a5](https://linux-hardware.org/?probe=ca0d3636a5) | Aug 03, 2023 |
| Lenovo        | ThinkPad X240 20AMS1RR0D    | [dcf2bedb58](https://linux-hardware.org/?probe=dcf2bedb58) | Aug 03, 2023 |
| MSI           | GE75 Raider 10SE            | [995b9ae73e](https://linux-hardware.org/?probe=995b9ae73e) | Jul 31, 2023 |
| ASUSTek       | PRIME X570-P                | [fa1452d305](https://linux-hardware.org/?probe=fa1452d305) | Jul 28, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [87d69792fb](https://linux-hardware.org/?probe=87d69792fb) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [83097985a2](https://linux-hardware.org/?probe=83097985a2) | Jul 26, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [6c0c0671df](https://linux-hardware.org/?probe=6c0c0671df) | Jul 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20HE... | [e6320dd4ae](https://linux-hardware.org/?probe=e6320dd4ae) | Jul 22, 2023 |
| Toshiba       | TECRA A50-A                 | [e96ff00334](https://linux-hardware.org/?probe=e96ff00334) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [a1f316c8c9](https://linux-hardware.org/?probe=a1f316c8c9) | Jul 20, 2023 |
| Lenovo        | ThinkPad T61 6465CTO        | [fcf6ce5b9e](https://linux-hardware.org/?probe=fcf6ce5b9e) | Jul 13, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [b4d926a4bc](https://linux-hardware.org/?probe=b4d926a4bc) | Jul 08, 2023 |
| MSI           | GF65 Thin 10UE              | [8dd1516457](https://linux-hardware.org/?probe=8dd1516457) | Jul 08, 2023 |
| HP            | Laptop 15-dw3xxx            | [2ed128676f](https://linux-hardware.org/?probe=2ed128676f) | Jul 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0b4200c1e4](https://linux-hardware.org/?probe=0b4200c1e4) | Jul 07, 2023 |
| Lenovo        | ThinkPad P52 20MAS17228     | [cb869cfeab](https://linux-hardware.org/?probe=cb869cfeab) | Jul 07, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [b50c5ad983](https://linux-hardware.org/?probe=b50c5ad983) | Jul 06, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [dfd88b9f78](https://linux-hardware.org/?probe=dfd88b9f78) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [ca25e859c3](https://linux-hardware.org/?probe=ca25e859c3) | Jul 04, 2023 |
| MSI           | Raider GE77HX 12UHS         | [87cc790852](https://linux-hardware.org/?probe=87cc790852) | Jul 03, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [4586b855ca](https://linux-hardware.org/?probe=4586b855ca) | Jul 02, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [40cbc38a69](https://linux-hardware.org/?probe=40cbc38a69) | Jun 25, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [e44e80fc33](https://linux-hardware.org/?probe=e44e80fc33) | Jun 23, 2023 |
| Apple         | MacBookAir5,2               | [8f6d75c75e](https://linux-hardware.org/?probe=8f6d75c75e) | Jun 22, 2023 |
| HP            | EliteBook 865 16 inch G9... | [e4407d328d](https://linux-hardware.org/?probe=e4407d328d) | Jun 22, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [3be3d70197](https://linux-hardware.org/?probe=3be3d70197) | Jun 20, 2023 |
| Lenovo        | Legion 5 82B5               | [146ef72817](https://linux-hardware.org/?probe=146ef72817) | Jun 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [e3e61eef7a](https://linux-hardware.org/?probe=e3e61eef7a) | Jun 15, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [57b3c23d43](https://linux-hardware.org/?probe=57b3c23d43) | Jun 14, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [b9c83e1b8a](https://linux-hardware.org/?probe=b9c83e1b8a) | Jun 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e28668e147](https://linux-hardware.org/?probe=e28668e147) | Jun 08, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC0F    | [581602e921](https://linux-hardware.org/?probe=581602e921) | Jun 07, 2023 |
| Dell          | Latitude 5300               | [1eea10cfa3](https://linux-hardware.org/?probe=1eea10cfa3) | Jun 07, 2023 |
| Lenovo        | ThinkPad P51 20HH0011US     | [4766608bc1](https://linux-hardware.org/?probe=4766608bc1) | Jun 06, 2023 |
| ASUSTek       | X540UP                      | [b6613930a2](https://linux-hardware.org/?probe=b6613930a2) | Jun 05, 2023 |
| ASUSTek       | X540UP                      | [5102ecc266](https://linux-hardware.org/?probe=5102ecc266) | Jun 04, 2023 |
| Acer          | Aspire AV15-51              | [41e5c1790c](https://linux-hardware.org/?probe=41e5c1790c) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [d583c74274](https://linux-hardware.org/?probe=d583c74274) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [7ed9ba7165](https://linux-hardware.org/?probe=7ed9ba7165) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1aa286ccff](https://linux-hardware.org/?probe=1aa286ccff) | Jun 03, 2023 |
| Dell          | Latitude 7490               | [3cb9ad156f](https://linux-hardware.org/?probe=3cb9ad156f) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | [f3dc10c852](https://linux-hardware.org/?probe=f3dc10c852) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | [1d128e6153](https://linux-hardware.org/?probe=1d128e6153) | Jun 01, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [287ebf0b10](https://linux-hardware.org/?probe=287ebf0b10) | May 30, 2023 |
| HP            | EliteBook 6930p             | [882f43330b](https://linux-hardware.org/?probe=882f43330b) | May 30, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [360e8fd5e5](https://linux-hardware.org/?probe=360e8fd5e5) | May 30, 2023 |
| MSI           | GF65 Thin 10UE              | [98e2096ab6](https://linux-hardware.org/?probe=98e2096ab6) | May 29, 2023 |
| Dell          | Inspiron 7577               | [94e5a63c07](https://linux-hardware.org/?probe=94e5a63c07) | May 29, 2023 |
| Dell          | XPS 9320                    | [33e7d964ad](https://linux-hardware.org/?probe=33e7d964ad) | May 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [dc2b5e538f](https://linux-hardware.org/?probe=dc2b5e538f) | May 27, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [f068d88c01](https://linux-hardware.org/?probe=f068d88c01) | May 27, 2023 |
| AAEON         | AEC-6637                    | [19050f7ccd](https://linux-hardware.org/?probe=19050f7ccd) | May 26, 2023 |
| Intel Clie... | LAPBC510                    | [fe45f8ba3c](https://linux-hardware.org/?probe=fe45f8ba3c) | May 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [29d761bff5](https://linux-hardware.org/?probe=29d761bff5) | May 26, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [5dd56ed986](https://linux-hardware.org/?probe=5dd56ed986) | May 25, 2023 |
| Dell          | Precision 7530              | [5cf37f39f4](https://linux-hardware.org/?probe=5cf37f39f4) | May 24, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1280876877](https://linux-hardware.org/?probe=1280876877) | May 24, 2023 |
| HP            | ENVY 15                     | [85a97390d5](https://linux-hardware.org/?probe=85a97390d5) | May 23, 2023 |
| HP            | ENVY 15                     | [21a38278ca](https://linux-hardware.org/?probe=21a38278ca) | May 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [8ec7bb4682](https://linux-hardware.org/?probe=8ec7bb4682) | May 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0f8329fecb](https://linux-hardware.org/?probe=0f8329fecb) | May 20, 2023 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [30950ddd01](https://linux-hardware.org/?probe=30950ddd01) | May 19, 2023 |
| MSI           | Stealth 15M B12UE           | [d6e14242b8](https://linux-hardware.org/?probe=d6e14242b8) | May 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [f811501691](https://linux-hardware.org/?probe=f811501691) | May 18, 2023 |
| HP            | ENVY 15                     | [4576cea8b0](https://linux-hardware.org/?probe=4576cea8b0) | May 17, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [9dda4f6b83](https://linux-hardware.org/?probe=9dda4f6b83) | May 13, 2023 |
| HP            | ENVY 15                     | [e188fe21b7](https://linux-hardware.org/?probe=e188fe21b7) | May 12, 2023 |
| Lenovo        | YangTian V340-15-IML 81V... | [cedb6136dc](https://linux-hardware.org/?probe=cedb6136dc) | May 12, 2023 |
| Dell          | Precision M3800             | [f5f8f44c9e](https://linux-hardware.org/?probe=f5f8f44c9e) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b791be35c2](https://linux-hardware.org/?probe=b791be35c2) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7058baf75d](https://linux-hardware.org/?probe=7058baf75d) | May 10, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [80a4bfeb08](https://linux-hardware.org/?probe=80a4bfeb08) | May 10, 2023 |
| SK hynix      | HyBook Plus                 | [817a46f154](https://linux-hardware.org/?probe=817a46f154) | May 09, 2023 |
| Dell          | XPS 15 9500                 | [0a72d00670](https://linux-hardware.org/?probe=0a72d00670) | May 09, 2023 |
| Notebook      | P750ZM                      | [2cbd56abdc](https://linux-hardware.org/?probe=2cbd56abdc) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [d782846579](https://linux-hardware.org/?probe=d782846579) | May 08, 2023 |
| Dell          | Inspiron 5490               | [6e2a4689b5](https://linux-hardware.org/?probe=6e2a4689b5) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [b8a363f717](https://linux-hardware.org/?probe=b8a363f717) | May 04, 2023 |
| Dell          | Precision 5540              | [3139d97ce0](https://linux-hardware.org/?probe=3139d97ce0) | May 04, 2023 |
| Toshiba       | PORTEGE Z830                | [a8cc4a63c2](https://linux-hardware.org/?probe=a8cc4a63c2) | May 03, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [143b75f514](https://linux-hardware.org/?probe=143b75f514) | May 02, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | [6c58138c35](https://linux-hardware.org/?probe=6c58138c35) | May 01, 2023 |
| ASUSTek       | X555QG                      | [5263b174b2](https://linux-hardware.org/?probe=5263b174b2) | Apr 30, 2023 |
| HP            | EliteBook 840 G3            | [c262e81ab9](https://linux-hardware.org/?probe=c262e81ab9) | Apr 30, 2023 |
| Dell          | XPS 13 9380                 | [c6591b0852](https://linux-hardware.org/?probe=c6591b0852) | Apr 29, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | [edf1d60e46](https://linux-hardware.org/?probe=edf1d60e46) | Apr 29, 2023 |
| MSI           | Modern 14 B11MOU            | [6b3fcf3fcc](https://linux-hardware.org/?probe=6b3fcf3fcc) | Apr 29, 2023 |
| ASUSTek       | X555QG                      | [b33f41d3c3](https://linux-hardware.org/?probe=b33f41d3c3) | Apr 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [e0ef7894af](https://linux-hardware.org/?probe=e0ef7894af) | Apr 28, 2023 |
| Lenovo        | ThinkPad X230 2325O32       | [b38ef1a717](https://linux-hardware.org/?probe=b38ef1a717) | Apr 27, 2023 |
| Lenovo        | ThinkPad T420 4177QKU       | [cbabefb1fa](https://linux-hardware.org/?probe=cbabefb1fa) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [3a6e27c6ce](https://linux-hardware.org/?probe=3a6e27c6ce) | Apr 26, 2023 |
| MSI           | Creator 15 A10SGS           | [1b364e385a](https://linux-hardware.org/?probe=1b364e385a) | Apr 26, 2023 |
| HP            | Laptop 15-fc0xxx            | [cc994920bf](https://linux-hardware.org/?probe=cc994920bf) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [c0d8e6e6b5](https://linux-hardware.org/?probe=c0d8e6e6b5) | Apr 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | [1b26b3f89b](https://linux-hardware.org/?probe=1b26b3f89b) | Apr 24, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | [2f3390afca](https://linux-hardware.org/?probe=2f3390afca) | Apr 24, 2023 |
| Notebook      | NLxxPUx                     | [3648be5b0f](https://linux-hardware.org/?probe=3648be5b0f) | Apr 23, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [a8644a5b03](https://linux-hardware.org/?probe=a8644a5b03) | Apr 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0e798db6a8](https://linux-hardware.org/?probe=0e798db6a8) | Apr 23, 2023 |
| ASUSTek       | X550CC                      | [f51db9e4de](https://linux-hardware.org/?probe=f51db9e4de) | Apr 23, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [b7f138b04c](https://linux-hardware.org/?probe=b7f138b04c) | Apr 20, 2023 |
| Dell          | G15 5510                    | [724945ee92](https://linux-hardware.org/?probe=724945ee92) | Apr 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHS... | [59d7ef5ddd](https://linux-hardware.org/?probe=59d7ef5ddd) | Apr 20, 2023 |
| Toshiba       | Satellite L515              | [5262a186b5](https://linux-hardware.org/?probe=5262a186b5) | Apr 20, 2023 |
| Dell          | Precision 5540              | [66b58fad6c](https://linux-hardware.org/?probe=66b58fad6c) | Apr 19, 2023 |
| Dell          | Precision 5540              | [e114fb911c](https://linux-hardware.org/?probe=e114fb911c) | Apr 19, 2023 |
| HP            | Pavilion 17                 | [66df49c906](https://linux-hardware.org/?probe=66df49c906) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [1a5add814c](https://linux-hardware.org/?probe=1a5add814c) | Apr 18, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [67a6474ece](https://linux-hardware.org/?probe=67a6474ece) | Apr 18, 2023 |
| Fujitsu       | LIFEBOOK U7510              | [21605e555f](https://linux-hardware.org/?probe=21605e555f) | Apr 18, 2023 |
| Lenovo        | ThinkPad Edge 031946U       | [f9d813509a](https://linux-hardware.org/?probe=f9d813509a) | Apr 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS11D00     | [c2227e5f29](https://linux-hardware.org/?probe=c2227e5f29) | Apr 18, 2023 |
| Lenovo        | Unknown                     | [99a0c76ea9](https://linux-hardware.org/?probe=99a0c76ea9) | Apr 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS11D00     | [f56edbb1d1](https://linux-hardware.org/?probe=f56edbb1d1) | Apr 18, 2023 |
| Acer          | Nitro AN515-54              | [7b3a68ca48](https://linux-hardware.org/?probe=7b3a68ca48) | Apr 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [90c4ba9f6e](https://linux-hardware.org/?probe=90c4ba9f6e) | Apr 17, 2023 |
| Lenovo        | Unknown                     | [653cf225b8](https://linux-hardware.org/?probe=653cf225b8) | Apr 17, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [f8a45caf43](https://linux-hardware.org/?probe=f8a45caf43) | Apr 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [7ca92cfada](https://linux-hardware.org/?probe=7ca92cfada) | Apr 17, 2023 |
| HP            | Pavilion 17                 | [a09113d5ab](https://linux-hardware.org/?probe=a09113d5ab) | Apr 17, 2023 |
| HUAWEI        | HVY-WXX9                    | [3d14cefd78](https://linux-hardware.org/?probe=3d14cefd78) | Apr 17, 2023 |
| HP            | EliteBook 845 14 inch G9... | [fd256ca124](https://linux-hardware.org/?probe=fd256ca124) | Apr 16, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [2092251807](https://linux-hardware.org/?probe=2092251807) | Apr 16, 2023 |
| HP            | 15-dc1018ur                 | [7df35a90ad](https://linux-hardware.org/?probe=7df35a90ad) | Apr 16, 2023 |
| Framework     | Laptop                      | [c03bcdf19a](https://linux-hardware.org/?probe=c03bcdf19a) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [afc478cf27](https://linux-hardware.org/?probe=afc478cf27) | Apr 16, 2023 |
| Dell          | Inspiron 3501               | [19b858e5f8](https://linux-hardware.org/?probe=19b858e5f8) | Apr 16, 2023 |
| Sony          | VPCCA1S1E                   | [05ab5df066](https://linux-hardware.org/?probe=05ab5df066) | Apr 16, 2023 |
| Acer          | Nitro AN515-54              | [73c46e2901](https://linux-hardware.org/?probe=73c46e2901) | Apr 15, 2023 |
| Google        | Dragonair                   | [be10ee5035](https://linux-hardware.org/?probe=be10ee5035) | Apr 15, 2023 |
| Sony          | VPCCA1S1E                   | [30625007d9](https://linux-hardware.org/?probe=30625007d9) | Apr 15, 2023 |
| Google        | Dragonair                   | [cb2aa57d07](https://linux-hardware.org/?probe=cb2aa57d07) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | [53c9fe0b8d](https://linux-hardware.org/?probe=53c9fe0b8d) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | [99f95937d4](https://linux-hardware.org/?probe=99f95937d4) | Apr 15, 2023 |
| Apple         | MacBookAir6,1               | [c649f1b898](https://linux-hardware.org/?probe=c649f1b898) | Apr 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [37eee19e22](https://linux-hardware.org/?probe=37eee19e22) | Apr 15, 2023 |
| HONOR         | HYM-WXX                     | [109b28f217](https://linux-hardware.org/?probe=109b28f217) | Apr 15, 2023 |
| Panasonic     | CF-C2CCEZXCM                | [361573ef78](https://linux-hardware.org/?probe=361573ef78) | Apr 14, 2023 |
| Dell          | Inspiron 7460               | [ae861b54cd](https://linux-hardware.org/?probe=ae861b54cd) | Apr 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b60b4dbb07](https://linux-hardware.org/?probe=b60b4dbb07) | Apr 14, 2023 |
| Dell          | Precision 5560              | [b6d20ef4bf](https://linux-hardware.org/?probe=b6d20ef4bf) | Apr 14, 2023 |
| Dell          | Precision 5560              | [b76f840bd9](https://linux-hardware.org/?probe=b76f840bd9) | Apr 14, 2023 |
| HP            | ZBook 15                    | [c5397a7fbb](https://linux-hardware.org/?probe=c5397a7fbb) | Apr 14, 2023 |
| HP            | Laptop 15-db0xxx            | [f02a5fef82](https://linux-hardware.org/?probe=f02a5fef82) | Apr 14, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [9cb53e6d6f](https://linux-hardware.org/?probe=9cb53e6d6f) | Apr 13, 2023 |
| HP            | ZBook 15                    | [aaaa838a8f](https://linux-hardware.org/?probe=aaaa838a8f) | Apr 13, 2023 |
| 3Logic Gro... | Graviton N15i-K2            | [7b75b7b08e](https://linux-hardware.org/?probe=7b75b7b08e) | Apr 13, 2023 |
| Dell          | Inspiron 5515               | [e7306b2521](https://linux-hardware.org/?probe=e7306b2521) | Apr 13, 2023 |
| Lenovo        | ThinkPad T490 20N2000NRT    | [ea97cd752d](https://linux-hardware.org/?probe=ea97cd752d) | Apr 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [2d321f3134](https://linux-hardware.org/?probe=2d321f3134) | Apr 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [77384847ef](https://linux-hardware.org/?probe=77384847ef) | Apr 12, 2023 |
| Dell          | XPS 13 9370                 | [66924704d2](https://linux-hardware.org/?probe=66924704d2) | Apr 12, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [16a7a866f1](https://linux-hardware.org/?probe=16a7a866f1) | Apr 12, 2023 |
| HUAWEI        | HVY-WXX9                    | [10da0191c4](https://linux-hardware.org/?probe=10da0191c4) | Apr 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5662df110d](https://linux-hardware.org/?probe=5662df110d) | Apr 11, 2023 |
| Dell          | XPS 13 7390                 | [da86532b55](https://linux-hardware.org/?probe=da86532b55) | Apr 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3792cccd19](https://linux-hardware.org/?probe=3792cccd19) | Apr 11, 2023 |
| Notebook      | NH55RGQ                     | [7fc1310fc2](https://linux-hardware.org/?probe=7fc1310fc2) | Apr 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3c1e7c6f4a](https://linux-hardware.org/?probe=3c1e7c6f4a) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [9d3c5ea28d](https://linux-hardware.org/?probe=9d3c5ea28d) | Apr 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ac983c99b9](https://linux-hardware.org/?probe=ac983c99b9) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | [11ecb91fec](https://linux-hardware.org/?probe=11ecb91fec) | Apr 09, 2023 |
| ASUSTek       | P552LA                      | [803ac095e7](https://linux-hardware.org/?probe=803ac095e7) | Apr 08, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [a334fb8e82](https://linux-hardware.org/?probe=a334fb8e82) | Apr 08, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [c06058447c](https://linux-hardware.org/?probe=c06058447c) | Apr 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5605228f3b](https://linux-hardware.org/?probe=5605228f3b) | Apr 08, 2023 |
| ASUSTek       | X553MA                      | [0a307c8c2b](https://linux-hardware.org/?probe=0a307c8c2b) | Apr 07, 2023 |
| HP            | Pavilion dv7                | [3a159264b1](https://linux-hardware.org/?probe=3a159264b1) | Apr 07, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [8c1127cfab](https://linux-hardware.org/?probe=8c1127cfab) | Apr 07, 2023 |
| Dell          | Latitude 7490               | [01957ea955](https://linux-hardware.org/?probe=01957ea955) | Apr 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [8d68ef79c3](https://linux-hardware.org/?probe=8d68ef79c3) | Apr 06, 2023 |
| Clevo         | M815P                       | [e5194b9fea](https://linux-hardware.org/?probe=e5194b9fea) | Apr 06, 2023 |
| Dell          | XPS 9320                    | [ff14e0074a](https://linux-hardware.org/?probe=ff14e0074a) | Apr 06, 2023 |
| MSI           | Katana 17 B12VGK            | [0f8f9e8ba8](https://linux-hardware.org/?probe=0f8f9e8ba8) | Apr 06, 2023 |
| Samsung       | 760XDA                      | [625178fa5a](https://linux-hardware.org/?probe=625178fa5a) | Apr 06, 2023 |
| NEC Comput... | PC-VK27MCZCK                | [e9572ebd2e](https://linux-hardware.org/?probe=e9572ebd2e) | Apr 06, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [320195c782](https://linux-hardware.org/?probe=320195c782) | Apr 06, 2023 |
| MSI           | Delta 15 A5EFK              | [d3066bb3d4](https://linux-hardware.org/?probe=d3066bb3d4) | Apr 06, 2023 |
| ASUSTek       | GL552VW                     | [ab450c0ddd](https://linux-hardware.org/?probe=ab450c0ddd) | Apr 06, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [d741226152](https://linux-hardware.org/?probe=d741226152) | Apr 06, 2023 |
| Dell          | Latitude E7470              | [64721a0d8a](https://linux-hardware.org/?probe=64721a0d8a) | Apr 05, 2023 |
| ASUSTek       | T100TAF                     | [fed8f42482](https://linux-hardware.org/?probe=fed8f42482) | Apr 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a64c365f62](https://linux-hardware.org/?probe=a64c365f62) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f98b9efce7](https://linux-hardware.org/?probe=f98b9efce7) | Apr 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [7e5be74f0b](https://linux-hardware.org/?probe=7e5be74f0b) | Apr 05, 2023 |
| Lenovo        | G50-80 80E5                 | [b469666726](https://linux-hardware.org/?probe=b469666726) | Apr 05, 2023 |
| Apple         | MacBookPro9,2               | [3a70dc24db](https://linux-hardware.org/?probe=3a70dc24db) | Apr 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [4710939159](https://linux-hardware.org/?probe=4710939159) | Apr 05, 2023 |
| HP            | 255 G8 Notebook PC          | [4c46d2ae80](https://linux-hardware.org/?probe=4c46d2ae80) | Apr 04, 2023 |
| ASUSTek       | X550JK                      | [b75b9b9fa2](https://linux-hardware.org/?probe=b75b9b9fa2) | Apr 04, 2023 |
| HP            | Notebook                    | [935131a649](https://linux-hardware.org/?probe=935131a649) | Apr 04, 2023 |
| HP            | Notebook                    | [f35bee3b90](https://linux-hardware.org/?probe=f35bee3b90) | Apr 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [c2240b20c2](https://linux-hardware.org/?probe=c2240b20c2) | Apr 04, 2023 |
| Notebook      | L140PU                      | [628319771e](https://linux-hardware.org/?probe=628319771e) | Apr 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [ddbd47af34](https://linux-hardware.org/?probe=ddbd47af34) | Apr 04, 2023 |
| Dell          | Vostro 15 3515              | [95a98c59b1](https://linux-hardware.org/?probe=95a98c59b1) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK U747               | [868448ea4b](https://linux-hardware.org/?probe=868448ea4b) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [e6a732e9b0](https://linux-hardware.org/?probe=e6a732e9b0) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [0b97a5a77a](https://linux-hardware.org/?probe=0b97a5a77a) | Apr 03, 2023 |
| Dell          | Inspiron 7577               | [ada2cb6e08](https://linux-hardware.org/?probe=ada2cb6e08) | Apr 02, 2023 |
| Dell          | Inspiron 7577               | [a761c8f978](https://linux-hardware.org/?probe=a761c8f978) | Apr 02, 2023 |
| Toshiba       | Satellite C55-B             | [da341e3be8](https://linux-hardware.org/?probe=da341e3be8) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [f995b3a81f](https://linux-hardware.org/?probe=f995b3a81f) | Apr 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [65cee818b6](https://linux-hardware.org/?probe=65cee818b6) | Apr 02, 2023 |
| Samsung       | 550P5C/550P7C               | [8e6191f4bb](https://linux-hardware.org/?probe=8e6191f4bb) | Apr 02, 2023 |
| ilife         | S806                        | [d089301e66](https://linux-hardware.org/?probe=d089301e66) | Apr 02, 2023 |
| Lenovo        | ThinkPad E14 20RAS0D800     | [ea2f5b484f](https://linux-hardware.org/?probe=ea2f5b484f) | Apr 02, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [f64cf6a2ae](https://linux-hardware.org/?probe=f64cf6a2ae) | Apr 02, 2023 |
| HP            | Snappy                      | [993161a4c7](https://linux-hardware.org/?probe=993161a4c7) | Apr 02, 2023 |
| ilife         | S806                        | [3a3ccd7c55](https://linux-hardware.org/?probe=3a3ccd7c55) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [dabe76e4ca](https://linux-hardware.org/?probe=dabe76e4ca) | Apr 01, 2023 |
| HP            | ProBook 6475b               | [680348d948](https://linux-hardware.org/?probe=680348d948) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | [5be9a0230e](https://linux-hardware.org/?probe=5be9a0230e) | Apr 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [36fab57ba7](https://linux-hardware.org/?probe=36fab57ba7) | Mar 31, 2023 |
| Dell          | Inspiron 7577               | [5800e3859c](https://linux-hardware.org/?probe=5800e3859c) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [c76f4f4354](https://linux-hardware.org/?probe=c76f4f4354) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [3a74487ae8](https://linux-hardware.org/?probe=3a74487ae8) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | [277dba9c1f](https://linux-hardware.org/?probe=277dba9c1f) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | [8a5046cad7](https://linux-hardware.org/?probe=8a5046cad7) | Mar 31, 2023 |
| MSI           | GS66 Stealth 10SF           | [a2589dd6f5](https://linux-hardware.org/?probe=a2589dd6f5) | Mar 31, 2023 |
| Google        | Cave                        | [8bd24407be](https://linux-hardware.org/?probe=8bd24407be) | Mar 31, 2023 |
| Dell          | Latitude D620               | [801ede47a2](https://linux-hardware.org/?probe=801ede47a2) | Mar 31, 2023 |
| Acer          | Swift SFA16-41              | [e110fbb7d6](https://linux-hardware.org/?probe=e110fbb7d6) | Mar 31, 2023 |
| HP            | EliteBook 6930p             | [5b087b11f5](https://linux-hardware.org/?probe=5b087b11f5) | Mar 30, 2023 |
| Dell          | Precision 5510              | [4bbf7f5ef2](https://linux-hardware.org/?probe=4bbf7f5ef2) | Mar 30, 2023 |
| AIR           | CX30500                     | [2ea4d0ec83](https://linux-hardware.org/?probe=2ea4d0ec83) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | [6af08c4bfe](https://linux-hardware.org/?probe=6af08c4bfe) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | [6f0d3fd82b](https://linux-hardware.org/?probe=6f0d3fd82b) | Mar 30, 2023 |
| HUAWEI        | KLVL-WXXW                   | [ab31f6f63d](https://linux-hardware.org/?probe=ab31f6f63d) | Mar 30, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [5cf96e41e0](https://linux-hardware.org/?probe=5cf96e41e0) | Mar 30, 2023 |
| Dell          | G15 5515                    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| HP            | 250 G6 Notebook PC          | [159d154fca](https://linux-hardware.org/?probe=159d154fca) | Mar 30, 2023 |
| Dell          | Latitude 5580               | [84157deda8](https://linux-hardware.org/?probe=84157deda8) | Mar 29, 2023 |
| Dell          | XPS 13 7390                 | [2eb96be1ee](https://linux-hardware.org/?probe=2eb96be1ee) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | [6023df2b8b](https://linux-hardware.org/?probe=6023df2b8b) | Mar 29, 2023 |
| Dell          | Latitude 5420               | [aee5c648e7](https://linux-hardware.org/?probe=aee5c648e7) | Mar 29, 2023 |
| Dell          | Latitude 7430               | [3f3b04c185](https://linux-hardware.org/?probe=3f3b04c185) | Mar 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [2f6655b77c](https://linux-hardware.org/?probe=2f6655b77c) | Mar 29, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [bf2f7820cd](https://linux-hardware.org/?probe=bf2f7820cd) | Mar 29, 2023 |
| Notebook      | L140CU                      | [e24f4b285d](https://linux-hardware.org/?probe=e24f4b285d) | Mar 29, 2023 |
| Notebook      | L140CU                      | [b1b0a5fc03](https://linux-hardware.org/?probe=b1b0a5fc03) | Mar 29, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [c8f2b78c09](https://linux-hardware.org/?probe=c8f2b78c09) | Mar 29, 2023 |
| Clevo         | M815P                       | [ac4eae2a0b](https://linux-hardware.org/?probe=ac4eae2a0b) | Mar 29, 2023 |
| HP            | Pavilion g7                 | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [5520b0fc5f](https://linux-hardware.org/?probe=5520b0fc5f) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [67789fc0d1](https://linux-hardware.org/?probe=67789fc0d1) | Mar 28, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | [7f5fb11940](https://linux-hardware.org/?probe=7f5fb11940) | Mar 28, 2023 |
| ASUSTek       | TX201LA                     | [27c77d0b6c](https://linux-hardware.org/?probe=27c77d0b6c) | Mar 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [70715024f2](https://linux-hardware.org/?probe=70715024f2) | Mar 28, 2023 |
| HP            | Compaq 6720s                | [9998cb9bfb](https://linux-hardware.org/?probe=9998cb9bfb) | Mar 27, 2023 |
| HP            | 250 G1                      | [75cf798dde](https://linux-hardware.org/?probe=75cf798dde) | Mar 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3173dc99b6](https://linux-hardware.org/?probe=3173dc99b6) | Mar 27, 2023 |
| Dell          | Latitude E5250              | [7d9e678484](https://linux-hardware.org/?probe=7d9e678484) | Mar 27, 2023 |
| Alienware     | 17 R4                       | [4a61d300b5](https://linux-hardware.org/?probe=4a61d300b5) | Mar 27, 2023 |
| Acer          | Predator PT515-51           | [2ac6541cf1](https://linux-hardware.org/?probe=2ac6541cf1) | Mar 27, 2023 |
| Dell          | Latitude 7280               | [409cf549eb](https://linux-hardware.org/?probe=409cf549eb) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [0ab4054ab9](https://linux-hardware.org/?probe=0ab4054ab9) | Mar 26, 2023 |
| Dell          | G15 5515                    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | G50-80 80E5                 | [250e0a99d1](https://linux-hardware.org/?probe=250e0a99d1) | Mar 26, 2023 |
| Acer          | Nitro AN515-55              | [36d5ba7071](https://linux-hardware.org/?probe=36d5ba7071) | Mar 26, 2023 |
| Acer          | Nitro AN515-54              | [2163c72a12](https://linux-hardware.org/?probe=2163c72a12) | Mar 25, 2023 |
| Dell          | Vostro 15 3515              | [a999580cf7](https://linux-hardware.org/?probe=a999580cf7) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [31788e7103](https://linux-hardware.org/?probe=31788e7103) | Mar 25, 2023 |
| Dell          | Latitude E6230              | [1a248bdc33](https://linux-hardware.org/?probe=1a248bdc33) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [0096d3d3b1](https://linux-hardware.org/?probe=0096d3d3b1) | Mar 25, 2023 |
| ASUSTek       | GL503VS                     | [8e066fcf6e](https://linux-hardware.org/?probe=8e066fcf6e) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [24784bc54d](https://linux-hardware.org/?probe=24784bc54d) | Mar 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [c2255f36b2](https://linux-hardware.org/?probe=c2255f36b2) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [cbb1418cfa](https://linux-hardware.org/?probe=cbb1418cfa) | Mar 24, 2023 |
| Acer          | Aspire E5-574               | [51a085fb56](https://linux-hardware.org/?probe=51a085fb56) | Mar 24, 2023 |
| Dell          | G15 5515                    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| Dell          | Precision 3551              | [bc979e320b](https://linux-hardware.org/?probe=bc979e320b) | Mar 24, 2023 |
| Dell          | Precision 3551              | [0509bee16a](https://linux-hardware.org/?probe=0509bee16a) | Mar 24, 2023 |
| ASUSTek       | ZenBook UX433FN_BX433FN     | [d8e67b032e](https://linux-hardware.org/?probe=d8e67b032e) | Mar 24, 2023 |
| MSI           | Modern 14 B4MW              | [c81d9f3b07](https://linux-hardware.org/?probe=c81d9f3b07) | Mar 24, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [56d564423e](https://linux-hardware.org/?probe=56d564423e) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| Dell          | Latitude 5580               | [d4ad4c55a6](https://linux-hardware.org/?probe=d4ad4c55a6) | Mar 24, 2023 |
| Dell          | Latitude 5285               | [a8114ded15](https://linux-hardware.org/?probe=a8114ded15) | Mar 23, 2023 |
| HP            | 250 G4                      | [e0ff721413](https://linux-hardware.org/?probe=e0ff721413) | Mar 23, 2023 |
| Dell          | Latitude 5285               | [baa8f358cf](https://linux-hardware.org/?probe=baa8f358cf) | Mar 23, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [aeb25bc22b](https://linux-hardware.org/?probe=aeb25bc22b) | Mar 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2d44e8f5c2](https://linux-hardware.org/?probe=2d44e8f5c2) | Mar 23, 2023 |
| Dell          | Latitude 5480               | [ff60b91842](https://linux-hardware.org/?probe=ff60b91842) | Mar 23, 2023 |
| Acer          | Aspire E3-112               | [721e804a03](https://linux-hardware.org/?probe=721e804a03) | Mar 23, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [950e4b69e8](https://linux-hardware.org/?probe=950e4b69e8) | Mar 23, 2023 |
| Dell          | Inspiron N5110              | [69e58cde56](https://linux-hardware.org/?probe=69e58cde56) | Mar 23, 2023 |
| Lenovo        | ThinkPad L380 20M6S3Q000    | [aab8aada0e](https://linux-hardware.org/?probe=aab8aada0e) | Mar 22, 2023 |
| Lenovo        | Legion 5 82B5               | [5298c41263](https://linux-hardware.org/?probe=5298c41263) | Mar 22, 2023 |
| Dell          | Inspiron N5110              | [2be6f0d943](https://linux-hardware.org/?probe=2be6f0d943) | Mar 22, 2023 |
| Apple         | MacBookPro11,5              | [ac5768cd3f](https://linux-hardware.org/?probe=ac5768cd3f) | Mar 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | [ea18262536](https://linux-hardware.org/?probe=ea18262536) | Mar 22, 2023 |
| Dell          | XPS 13 9310                 | [386f37d114](https://linux-hardware.org/?probe=386f37d114) | Mar 22, 2023 |
| Samsung       | 550XDA                      | [b145c438d7](https://linux-hardware.org/?probe=b145c438d7) | Mar 22, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [4ee498d9fc](https://linux-hardware.org/?probe=4ee498d9fc) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [5207701ff8](https://linux-hardware.org/?probe=5207701ff8) | Mar 22, 2023 |
| Lenovo        | Legion 5 82B5               | [8dfc670e24](https://linux-hardware.org/?probe=8dfc670e24) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [23e4353a34](https://linux-hardware.org/?probe=23e4353a34) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| Lenovo        | B50-10 80QR                 | [134bf99094](https://linux-hardware.org/?probe=134bf99094) | Mar 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [b4d5442d02](https://linux-hardware.org/?probe=b4d5442d02) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [6d96576431](https://linux-hardware.org/?probe=6d96576431) | Mar 21, 2023 |
| Acer          | Aspire F5-573G              | [ec2390af74](https://linux-hardware.org/?probe=ec2390af74) | Mar 21, 2023 |
| Dell          | Vostro 14-5480              | [ee892df403](https://linux-hardware.org/?probe=ee892df403) | Mar 21, 2023 |
| Notebook      | W51XTU                      | [de60f3fcba](https://linux-hardware.org/?probe=de60f3fcba) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [57663c8d60](https://linux-hardware.org/?probe=57663c8d60) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [f5cbd1977f](https://linux-hardware.org/?probe=f5cbd1977f) | Mar 20, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [e7eb855568](https://linux-hardware.org/?probe=e7eb855568) | Mar 20, 2023 |
| HP            | Laptop 15-dy1xxx            | [1686ba2df4](https://linux-hardware.org/?probe=1686ba2df4) | Mar 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [762762da77](https://linux-hardware.org/?probe=762762da77) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7fb78c1c79](https://linux-hardware.org/?probe=7fb78c1c79) | Mar 20, 2023 |
| Acer          | Aspire F5-573G              | [e3e0efa236](https://linux-hardware.org/?probe=e3e0efa236) | Mar 20, 2023 |
| Dell          | Latitude 5290 2-in-1        | [1840c57073](https://linux-hardware.org/?probe=1840c57073) | Mar 20, 2023 |
| Dell          | XPS 15 9570                 | [4ad2d5c249](https://linux-hardware.org/?probe=4ad2d5c249) | Mar 19, 2023 |
| Prestigio     | PSB141C01BFH                | [9190e0a0e7](https://linux-hardware.org/?probe=9190e0a0e7) | Mar 19, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4223bbbf7e](https://linux-hardware.org/?probe=4223bbbf7e) | Mar 19, 2023 |
| Avell High... | B.ON                        | [b215c2fd75](https://linux-hardware.org/?probe=b215c2fd75) | Mar 19, 2023 |
| HP            | 250 G7 Notebook PC          | [5033dda127](https://linux-hardware.org/?probe=5033dda127) | Mar 19, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [63b182c7d6](https://linux-hardware.org/?probe=63b182c7d6) | Mar 19, 2023 |
| Toshiba       | Satellite C75D-B            | [1ff56ed31f](https://linux-hardware.org/?probe=1ff56ed31f) | Mar 19, 2023 |
| HP            | G62                         | [2cb4092da0](https://linux-hardware.org/?probe=2cb4092da0) | Mar 19, 2023 |
| HP            | G62                         | [76d7e36f21](https://linux-hardware.org/?probe=76d7e36f21) | Mar 19, 2023 |
| HONOR         | GLO-FX6P                    | [0fb3ebc365](https://linux-hardware.org/?probe=0fb3ebc365) | Mar 19, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [88b7883383](https://linux-hardware.org/?probe=88b7883383) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [cbad8c5f1e](https://linux-hardware.org/?probe=cbad8c5f1e) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | [49b005770d](https://linux-hardware.org/?probe=49b005770d) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | [6af556d727](https://linux-hardware.org/?probe=6af556d727) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | [3b0eb35766](https://linux-hardware.org/?probe=3b0eb35766) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | [7743b2a5a9](https://linux-hardware.org/?probe=7743b2a5a9) | Mar 18, 2023 |
| ASUSTek       | X750JN                      | [7dd8257bc8](https://linux-hardware.org/?probe=7dd8257bc8) | Mar 18, 2023 |
| MSI           | GF65 Thin 10UE              | [8d2db4b0fe](https://linux-hardware.org/?probe=8d2db4b0fe) | Mar 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| ASUSTek       | X750JN                      | [7ee3dac323](https://linux-hardware.org/?probe=7ee3dac323) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | [d79a6ae160](https://linux-hardware.org/?probe=d79a6ae160) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | [691f338c53](https://linux-hardware.org/?probe=691f338c53) | Mar 17, 2023 |
| ASUSTek       | X555LB                      | [a00be2eabe](https://linux-hardware.org/?probe=a00be2eabe) | Mar 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2ab659150c](https://linux-hardware.org/?probe=2ab659150c) | Mar 16, 2023 |
| HONOR         | BMH-WCX9                    | [47a9ec2aa1](https://linux-hardware.org/?probe=47a9ec2aa1) | Mar 16, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [03123126d0](https://linux-hardware.org/?probe=03123126d0) | Mar 16, 2023 |
| HP            | EliteBook 850 G2            | [f2b9853f35](https://linux-hardware.org/?probe=f2b9853f35) | Mar 16, 2023 |
| Lenovo        | ThinkPad T540p 20BFS1N00... | [03b210c1f8](https://linux-hardware.org/?probe=03b210c1f8) | Mar 16, 2023 |
| Dell          | Latitude D620               | [1731735e10](https://linux-hardware.org/?probe=1731735e10) | Mar 16, 2023 |
| LG Electro... | 15Z980-G.BH72P1             | [0bba01d850](https://linux-hardware.org/?probe=0bba01d850) | Mar 16, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [5667e8416e](https://linux-hardware.org/?probe=5667e8416e) | Mar 16, 2023 |
| Dell          | Latitude E5470              | [cc4f08349d](https://linux-hardware.org/?probe=cc4f08349d) | Mar 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [5bf235f5d3](https://linux-hardware.org/?probe=5bf235f5d3) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [907581c9cc](https://linux-hardware.org/?probe=907581c9cc) | Mar 16, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0AF00    | [fe02ac3290](https://linux-hardware.org/?probe=fe02ac3290) | Mar 15, 2023 |
| HP            | Pavilion Notebook           | [db96098c80](https://linux-hardware.org/?probe=db96098c80) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | [d19eaf791f](https://linux-hardware.org/?probe=d19eaf791f) | Mar 15, 2023 |
| Dell          | Latitude 7430               | [58024877c3](https://linux-hardware.org/?probe=58024877c3) | Mar 15, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [1e802bfcd0](https://linux-hardware.org/?probe=1e802bfcd0) | Mar 15, 2023 |
| Dell          | Latitude 5530               | [aac966a8af](https://linux-hardware.org/?probe=aac966a8af) | Mar 15, 2023 |
| Dell          | Latitude 7390               | [7cc6b3a278](https://linux-hardware.org/?probe=7cc6b3a278) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | [a519acdd2e](https://linux-hardware.org/?probe=a519acdd2e) | Mar 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [96f3739077](https://linux-hardware.org/?probe=96f3739077) | Mar 15, 2023 |
| HP            | 245 G8 Notebook PC          | [6c73c46184](https://linux-hardware.org/?probe=6c73c46184) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| Toshiba       | Satellite P55t-B            | [7bd981d445](https://linux-hardware.org/?probe=7bd981d445) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [fb73add0f6](https://linux-hardware.org/?probe=fb73add0f6) | Mar 14, 2023 |
| Dell          | Inspiron 7375               | [430599b2da](https://linux-hardware.org/?probe=430599b2da) | Mar 14, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | [a9db94aee2](https://linux-hardware.org/?probe=a9db94aee2) | Mar 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [112d979fc6](https://linux-hardware.org/?probe=112d979fc6) | Mar 14, 2023 |
| Exo           | Smart XS1                   | [e1e04684eb](https://linux-hardware.org/?probe=e1e04684eb) | Mar 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [933110cc30](https://linux-hardware.org/?probe=933110cc30) | Mar 14, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [d23ddde885](https://linux-hardware.org/?probe=d23ddde885) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [eac2f2ae40](https://linux-hardware.org/?probe=eac2f2ae40) | Mar 14, 2023 |
| System76      | Gazelle                     | [d45f36e46f](https://linux-hardware.org/?probe=d45f36e46f) | Mar 14, 2023 |
| MSI           | Katana GF76 11UD            | [37edbdcce5](https://linux-hardware.org/?probe=37edbdcce5) | Mar 14, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [2c2920d462](https://linux-hardware.org/?probe=2c2920d462) | Mar 14, 2023 |
| HP            | ProBook 450 G3              | [d422d0d291](https://linux-hardware.org/?probe=d422d0d291) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [e6792912bf](https://linux-hardware.org/?probe=e6792912bf) | Mar 14, 2023 |
| MSI           | Stealth GS77 12UHS          | [fe00606a03](https://linux-hardware.org/?probe=fe00606a03) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [59d2c50a02](https://linux-hardware.org/?probe=59d2c50a02) | Mar 14, 2023 |
| Toshiba       | Satellite L40               | [bfc73429bb](https://linux-hardware.org/?probe=bfc73429bb) | Mar 13, 2023 |
| Dell          | Inspiron 13 5320            | [efbe50cd5c](https://linux-hardware.org/?probe=efbe50cd5c) | Mar 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | [ca456dde7d](https://linux-hardware.org/?probe=ca456dde7d) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [70de894994](https://linux-hardware.org/?probe=70de894994) | Mar 13, 2023 |
| ASUSTek       | X510UAR                     | [815dfc26ec](https://linux-hardware.org/?probe=815dfc26ec) | Mar 13, 2023 |
| Samsung       | 300E5M/300E5L               | [8567b21f41](https://linux-hardware.org/?probe=8567b21f41) | Mar 13, 2023 |
| HUAWEI        | BOD-WXX9                    | [74452c1274](https://linux-hardware.org/?probe=74452c1274) | Mar 13, 2023 |
| Acer          | Aspire R7-371T              | [b6aef449b6](https://linux-hardware.org/?probe=b6aef449b6) | Mar 13, 2023 |
| Lenovo        | IdeaPad U300s 20111         | [aaaee5fcf5](https://linux-hardware.org/?probe=aaaee5fcf5) | Mar 12, 2023 |
| Lenovo        | IdeaPad U300s 20111         | [3f3945f7e3](https://linux-hardware.org/?probe=3f3945f7e3) | Mar 12, 2023 |
| TECNO         | MEGABOOK T1                 | [000c3e4761](https://linux-hardware.org/?probe=000c3e4761) | Mar 12, 2023 |
| Dell          | Inspiron 5565               | [9415690de2](https://linux-hardware.org/?probe=9415690de2) | Mar 12, 2023 |
| Insyde        | BayTrail                    | [8d0337a8ee](https://linux-hardware.org/?probe=8d0337a8ee) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5c45eb6864](https://linux-hardware.org/?probe=5c45eb6864) | Mar 12, 2023 |
| HUAWEI        | BOD-WXX9                    | [1875fd875d](https://linux-hardware.org/?probe=1875fd875d) | Mar 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [28769bd85b](https://linux-hardware.org/?probe=28769bd85b) | Mar 12, 2023 |
| Dell          | Vostro 14-5480              | [3ea64e75d4](https://linux-hardware.org/?probe=3ea64e75d4) | Mar 12, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [8a8b88087b](https://linux-hardware.org/?probe=8a8b88087b) | Mar 12, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [8aff6217a5](https://linux-hardware.org/?probe=8aff6217a5) | Mar 11, 2023 |
| Dell          | XPS 13 9310                 | [599f8de7ba](https://linux-hardware.org/?probe=599f8de7ba) | Mar 11, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [2a0539c2b1](https://linux-hardware.org/?probe=2a0539c2b1) | Mar 11, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [5d69c96eca](https://linux-hardware.org/?probe=5d69c96eca) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | [3f12a2f32e](https://linux-hardware.org/?probe=3f12a2f32e) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | [a6ba9c1545](https://linux-hardware.org/?probe=a6ba9c1545) | Mar 11, 2023 |
| Proline       | V146SH                      | [460deab2ea](https://linux-hardware.org/?probe=460deab2ea) | Mar 11, 2023 |
| Dell          | XPS 13 9300                 | [d3b7f2f978](https://linux-hardware.org/?probe=d3b7f2f978) | Mar 11, 2023 |
| ASUSTek       | G752VL                      | [4a4ea6f987](https://linux-hardware.org/?probe=4a4ea6f987) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK U759               | [01025c7c43](https://linux-hardware.org/?probe=01025c7c43) | Mar 11, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | [9b38c9668e](https://linux-hardware.org/?probe=9b38c9668e) | Mar 10, 2023 |
| Dell          | XPS 13 9310                 | [037f2e4a2d](https://linux-hardware.org/?probe=037f2e4a2d) | Mar 10, 2023 |
| HONOR         | NMH-WCX9                    | [f9cf8b06f6](https://linux-hardware.org/?probe=f9cf8b06f6) | Mar 10, 2023 |
| Lenovo        | ThinkPad T460 20LPS3K002    | [c375b36f4a](https://linux-hardware.org/?probe=c375b36f4a) | Mar 10, 2023 |
| Acer          | Swift SFX14-41G             | [80ecfacebf](https://linux-hardware.org/?probe=80ecfacebf) | Mar 10, 2023 |
| Unknown       | Unknown                     | [cd382356be](https://linux-hardware.org/?probe=cd382356be) | Mar 10, 2023 |
| HP            | Laptop 14-cm0xxx            | [d35d11c64e](https://linux-hardware.org/?probe=d35d11c64e) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d35772b8bc](https://linux-hardware.org/?probe=d35772b8bc) | Mar 09, 2023 |
| HP            | Notebook                    | [b5ee32f085](https://linux-hardware.org/?probe=b5ee32f085) | Mar 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [780937bb9f](https://linux-hardware.org/?probe=780937bb9f) | Mar 09, 2023 |
| Dell          | XPS 15 9530                 | [d7129009b0](https://linux-hardware.org/?probe=d7129009b0) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [e4164a80cd](https://linux-hardware.org/?probe=e4164a80cd) | Mar 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [c50daaf3b9](https://linux-hardware.org/?probe=c50daaf3b9) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [5535b412ed](https://linux-hardware.org/?probe=5535b412ed) | Mar 09, 2023 |
| Dell          | Inspiron 7375               | [2dbb99bbb2](https://linux-hardware.org/?probe=2dbb99bbb2) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [2664be8926](https://linux-hardware.org/?probe=2664be8926) | Mar 09, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [dc915e443d](https://linux-hardware.org/?probe=dc915e443d) | Mar 09, 2023 |
| HP            | Laptop 15-dy2xxx            | [97698bd9a9](https://linux-hardware.org/?probe=97698bd9a9) | Mar 09, 2023 |
| Google        | Cave                        | [37d6d413b7](https://linux-hardware.org/?probe=37d6d413b7) | Mar 09, 2023 |
| Dell          | Inspiron 3505               | [5ffa875792](https://linux-hardware.org/?probe=5ffa875792) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b349a8eedd](https://linux-hardware.org/?probe=b349a8eedd) | Mar 08, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [ac772ea51f](https://linux-hardware.org/?probe=ac772ea51f) | Mar 08, 2023 |
| Lenovo        | ThinkPad T450s 20BX0013G... | [11cf435bfe](https://linux-hardware.org/?probe=11cf435bfe) | Mar 08, 2023 |
| Acer          | Aspire A315-58              | [f4de2d1a2a](https://linux-hardware.org/?probe=f4de2d1a2a) | Mar 08, 2023 |
| HP            | OMEN by Laptop              | [a3a369de93](https://linux-hardware.org/?probe=a3a369de93) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| Dell          | Inspiron 14 5420            | [cb6ec54195](https://linux-hardware.org/?probe=cb6ec54195) | Mar 08, 2023 |
| Dell          | Latitude 5400               | [3d2504745e](https://linux-hardware.org/?probe=3d2504745e) | Mar 08, 2023 |
| HP            | ProBook 440 G7              | [7f4678dcf1](https://linux-hardware.org/?probe=7f4678dcf1) | Mar 07, 2023 |
| Dell          | Latitude 7290               | [38f12088b2](https://linux-hardware.org/?probe=38f12088b2) | Mar 07, 2023 |
| HUAWEI        | CREM-WXX9                   | [1aaf3d1b9f](https://linux-hardware.org/?probe=1aaf3d1b9f) | Mar 07, 2023 |
| MSI           | Modern 15 A5M               | [e88ffa7e1d](https://linux-hardware.org/?probe=e88ffa7e1d) | Mar 07, 2023 |
| Acer          | One S1001                   | [b43d7f0a84](https://linux-hardware.org/?probe=b43d7f0a84) | Mar 06, 2023 |
| HUAWEI        | KLVD-WXX9                   | [1209c224e1](https://linux-hardware.org/?probe=1209c224e1) | Mar 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [798d6e74da](https://linux-hardware.org/?probe=798d6e74da) | Mar 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [bd9c4997b0](https://linux-hardware.org/?probe=bd9c4997b0) | Mar 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [98a2c9f264](https://linux-hardware.org/?probe=98a2c9f264) | Mar 06, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [4e05d0a0e9](https://linux-hardware.org/?probe=4e05d0a0e9) | Mar 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [4b6c93e678](https://linux-hardware.org/?probe=4b6c93e678) | Mar 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [0fca5ee94e](https://linux-hardware.org/?probe=0fca5ee94e) | Mar 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d256faa9fc](https://linux-hardware.org/?probe=d256faa9fc) | Mar 06, 2023 |
| Dell          | Inspiron 15 3525            | [cc3e080ded](https://linux-hardware.org/?probe=cc3e080ded) | Mar 06, 2023 |
| Dell          | Inspiron 3593               | [f33f04396c](https://linux-hardware.org/?probe=f33f04396c) | Mar 05, 2023 |
| Acer          | Aspire A515-57T             | [ebd1e9103e](https://linux-hardware.org/?probe=ebd1e9103e) | Mar 05, 2023 |
| Google        | Lillipup                    | [6c7cf4cd9e](https://linux-hardware.org/?probe=6c7cf4cd9e) | Mar 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | [0811163639](https://linux-hardware.org/?probe=0811163639) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [42469e8f5d](https://linux-hardware.org/?probe=42469e8f5d) | Mar 05, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [d42a19d17b](https://linux-hardware.org/?probe=d42a19d17b) | Mar 05, 2023 |
| Dell          | Latitude 5410               | [6f55e8bbfe](https://linux-hardware.org/?probe=6f55e8bbfe) | Mar 05, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [fb996384c6](https://linux-hardware.org/?probe=fb996384c6) | Mar 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [925e02d1dc](https://linux-hardware.org/?probe=925e02d1dc) | Mar 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [e2ad6f0e57](https://linux-hardware.org/?probe=e2ad6f0e57) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [7d9acf8639](https://linux-hardware.org/?probe=7d9acf8639) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [a28f5eeec0](https://linux-hardware.org/?probe=a28f5eeec0) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | [bd108fcfba](https://linux-hardware.org/?probe=bd108fcfba) | Mar 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [6f7115f084](https://linux-hardware.org/?probe=6f7115f084) | Mar 04, 2023 |
| Purism        | Librem 14                   | [fbae41cbd5](https://linux-hardware.org/?probe=fbae41cbd5) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bd5e51c339](https://linux-hardware.org/?probe=bd5e51c339) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | [e3f1423c39](https://linux-hardware.org/?probe=e3f1423c39) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [1bcec582e3](https://linux-hardware.org/?probe=1bcec582e3) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1ee7b087a8](https://linux-hardware.org/?probe=1ee7b087a8) | Mar 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4b20311834](https://linux-hardware.org/?probe=4b20311834) | Mar 03, 2023 |
| HP            | EliteBook 830 G5            | [cd6c75d08e](https://linux-hardware.org/?probe=cd6c75d08e) | Mar 03, 2023 |
| Chuwi         | HeroBook Air                | [43248e0ae9](https://linux-hardware.org/?probe=43248e0ae9) | Mar 03, 2023 |
| Toshiba       | Satellite L515              | [daf95cc1e5](https://linux-hardware.org/?probe=daf95cc1e5) | Mar 03, 2023 |
| MSI           | GS63VR 6RF                  | [dd60a9c73b](https://linux-hardware.org/?probe=dd60a9c73b) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5906e1b848](https://linux-hardware.org/?probe=5906e1b848) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c4c7ebf544](https://linux-hardware.org/?probe=c4c7ebf544) | Mar 03, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [e5b411431c](https://linux-hardware.org/?probe=e5b411431c) | Mar 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [22c9e146ee](https://linux-hardware.org/?probe=22c9e146ee) | Mar 02, 2023 |
| Apple         | MacBookAir5,2               | [6b7925d129](https://linux-hardware.org/?probe=6b7925d129) | Mar 02, 2023 |
| HP            | 255 G3                      | [78c4cd0a9c](https://linux-hardware.org/?probe=78c4cd0a9c) | Mar 01, 2023 |
| HUAWEI        | KLVD-WXX9                   | [8c878d99a1](https://linux-hardware.org/?probe=8c878d99a1) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9ba7cfbdeb](https://linux-hardware.org/?probe=9ba7cfbdeb) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [94809b7bc2](https://linux-hardware.org/?probe=94809b7bc2) | Mar 01, 2023 |
| Apple         | MacBookPro7,1               | [4d1bdc90ea](https://linux-hardware.org/?probe=4d1bdc90ea) | Mar 01, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [6a99428156](https://linux-hardware.org/?probe=6a99428156) | Mar 01, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [3db8300147](https://linux-hardware.org/?probe=3db8300147) | Mar 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [1c09e468d0](https://linux-hardware.org/?probe=1c09e468d0) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [165c0356a5](https://linux-hardware.org/?probe=165c0356a5) | Mar 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [22d51a725f](https://linux-hardware.org/?probe=22d51a725f) | Feb 28, 2023 |
| Dell          | Latitude E7270              | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| HP            | ProBook 635 Aero G8 Note... | [93ee76f198](https://linux-hardware.org/?probe=93ee76f198) | Feb 28, 2023 |
| Acer          | Aspire A315-59              | [9a897f5d7c](https://linux-hardware.org/?probe=9a897f5d7c) | Feb 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [b5a4a1809f](https://linux-hardware.org/?probe=b5a4a1809f) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | [3d003c6d17](https://linux-hardware.org/?probe=3d003c6d17) | Feb 28, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [ed67c567d2](https://linux-hardware.org/?probe=ed67c567d2) | Feb 28, 2023 |
| Standard      | Unknown                     | [63732ac2da](https://linux-hardware.org/?probe=63732ac2da) | Feb 28, 2023 |
| Dell          | Precision 5570              | [7e8d7c37cb](https://linux-hardware.org/?probe=7e8d7c37cb) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| HP            | EliteBook Folio 9470m       | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| HUAWEI        | MACHR-WX9                   | [b1ef7c7ea1](https://linux-hardware.org/?probe=b1ef7c7ea1) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | [1c1dc86eb1](https://linux-hardware.org/?probe=1c1dc86eb1) | Feb 27, 2023 |
| HP            | EliteBook 845 14 inch G9... | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [dd5ce2c6db](https://linux-hardware.org/?probe=dd5ce2c6db) | Feb 27, 2023 |
| Toshiba       | Satellite P870              | [6d9216b866](https://linux-hardware.org/?probe=6d9216b866) | Feb 27, 2023 |
| Dell          | Inspiron 15 3511            | [4c96506f38](https://linux-hardware.org/?probe=4c96506f38) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d7e55bb97e](https://linux-hardware.org/?probe=d7e55bb97e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [091e4e3188](https://linux-hardware.org/?probe=091e4e3188) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | [058ecdce01](https://linux-hardware.org/?probe=058ecdce01) | Feb 27, 2023 |
| Lenovo        | ThinkPad X395 20NL0006US    | [9030fac261](https://linux-hardware.org/?probe=9030fac261) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [fe8735a027](https://linux-hardware.org/?probe=fe8735a027) | Feb 26, 2023 |
| HP            | Notebook                    | [ab0dddc914](https://linux-hardware.org/?probe=ab0dddc914) | Feb 26, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [6b712e555f](https://linux-hardware.org/?probe=6b712e555f) | Feb 26, 2023 |
| Dell          | Vostro 3578                 | [da6968c8ac](https://linux-hardware.org/?probe=da6968c8ac) | Feb 26, 2023 |
| Samsung       | 370E4K                      | [7b769eb33e](https://linux-hardware.org/?probe=7b769eb33e) | Feb 26, 2023 |
| HUAWEI        | CREM-WXX9                   | [c026a25fb2](https://linux-hardware.org/?probe=c026a25fb2) | Feb 26, 2023 |
| HP            | 250 G6 Notebook PC          | [af6a897a26](https://linux-hardware.org/?probe=af6a897a26) | Feb 26, 2023 |
| Timi          | TM1612                      | [eb4a3f330e](https://linux-hardware.org/?probe=eb4a3f330e) | Feb 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [d3b6621252](https://linux-hardware.org/?probe=d3b6621252) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | [f589c3687b](https://linux-hardware.org/?probe=f589c3687b) | Feb 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d610badec8](https://linux-hardware.org/?probe=d610badec8) | Feb 26, 2023 |
| Lenovo        | ThinkPad T61 6464A13        | [e981803528](https://linux-hardware.org/?probe=e981803528) | Feb 26, 2023 |
| Standard      | Unknown                     | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| Lenovo        | Legion 5 82B5               | [8db23a7237](https://linux-hardware.org/?probe=8db23a7237) | Feb 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| Dell          | Vostro 14-5459              | [1f96898a48](https://linux-hardware.org/?probe=1f96898a48) | Feb 25, 2023 |
| Dell          | Latitude E6420              | [7ae4fe9340](https://linux-hardware.org/?probe=7ae4fe9340) | Feb 25, 2023 |
| Dell          | Latitude 5511               | [4402838fb3](https://linux-hardware.org/?probe=4402838fb3) | Feb 25, 2023 |
| Google        | Voxel                       | [ce917fe8ec](https://linux-hardware.org/?probe=ce917fe8ec) | Feb 25, 2023 |
| Google        | Voxel                       | [93ea143f69](https://linux-hardware.org/?probe=93ea143f69) | Feb 25, 2023 |
| Dell          | Inspiron 5759               | [be0b15660e](https://linux-hardware.org/?probe=be0b15660e) | Feb 25, 2023 |
| HUAWEI        | MACH-WX9                    | [52924074db](https://linux-hardware.org/?probe=52924074db) | Feb 25, 2023 |
| Dell          | Precision 5520              | [c41014658b](https://linux-hardware.org/?probe=c41014658b) | Feb 25, 2023 |
| Dell          | System XPS L321X            | [4de5ba1c80](https://linux-hardware.org/?probe=4de5ba1c80) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [9cbbaaf012](https://linux-hardware.org/?probe=9cbbaaf012) | Feb 24, 2023 |
| Chuwi         | GemiBook Pro                | [f8f1005d73](https://linux-hardware.org/?probe=f8f1005d73) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [787270bc9e](https://linux-hardware.org/?probe=787270bc9e) | Feb 24, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | [ade006d016](https://linux-hardware.org/?probe=ade006d016) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f7063f868f](https://linux-hardware.org/?probe=f7063f868f) | Feb 24, 2023 |
| HP            | 245 G8 Notebook PC          | [7686bcd76d](https://linux-hardware.org/?probe=7686bcd76d) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | [7858955f02](https://linux-hardware.org/?probe=7858955f02) | Feb 24, 2023 |
| Toshiba       | Satellite L515              | [969c2042b9](https://linux-hardware.org/?probe=969c2042b9) | Feb 24, 2023 |
| Dell          | G5 5587                     | [1f43871064](https://linux-hardware.org/?probe=1f43871064) | Feb 24, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [f92ac89547](https://linux-hardware.org/?probe=f92ac89547) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4b0436b55d](https://linux-hardware.org/?probe=4b0436b55d) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [a4c4313238](https://linux-hardware.org/?probe=a4c4313238) | Feb 23, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [bb2bef71e0](https://linux-hardware.org/?probe=bb2bef71e0) | Feb 23, 2023 |
| Lenovo        | ThinkPad X230 2325CS6       | [ed9501bbcb](https://linux-hardware.org/?probe=ed9501bbcb) | Feb 23, 2023 |
| Dell          | Inspiron 13-7359            | [39d95063c3](https://linux-hardware.org/?probe=39d95063c3) | Feb 23, 2023 |
| ASUSTek       | K56CA                       | [d8475e4c48](https://linux-hardware.org/?probe=d8475e4c48) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e23562af05](https://linux-hardware.org/?probe=e23562af05) | Feb 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [becb5b0ba1](https://linux-hardware.org/?probe=becb5b0ba1) | Feb 22, 2023 |
| CyberPower... | Tracer IV GM5MQ8W           | [284e8a4fb1](https://linux-hardware.org/?probe=284e8a4fb1) | Feb 22, 2023 |
| Dell          | Latitude E5570              | [338538c1c9](https://linux-hardware.org/?probe=338538c1c9) | Feb 22, 2023 |
| Gigabyte      | G5 KD                       | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [7d3442e2a7](https://linux-hardware.org/?probe=7d3442e2a7) | Feb 22, 2023 |
| Alienware     | x14                         | [0b32a33625](https://linux-hardware.org/?probe=0b32a33625) | Feb 22, 2023 |
| Alienware     | x14                         | [04094754b6](https://linux-hardware.org/?probe=04094754b6) | Feb 22, 2023 |
| HP            | Notebook                    | [f6d3ba25ba](https://linux-hardware.org/?probe=f6d3ba25ba) | Feb 22, 2023 |
| Samsung       | 767XCL                      | [3fb09fb626](https://linux-hardware.org/?probe=3fb09fb626) | Feb 22, 2023 |
| Dell          | Latitude 5491               | [fd68ba9595](https://linux-hardware.org/?probe=fd68ba9595) | Feb 21, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [a459216464](https://linux-hardware.org/?probe=a459216464) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [7ead9488ae](https://linux-hardware.org/?probe=7ead9488ae) | Feb 21, 2023 |
| Apple         | MacBookAir6,1               | [b9117f0c6f](https://linux-hardware.org/?probe=b9117f0c6f) | Feb 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [c0733771d5](https://linux-hardware.org/?probe=c0733771d5) | Feb 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [039bb422e0](https://linux-hardware.org/?probe=039bb422e0) | Feb 21, 2023 |
| Acer          | Aspire SW3-013              | [f0111df214](https://linux-hardware.org/?probe=f0111df214) | Feb 21, 2023 |
| Alienware     | 15 R2                       | [96aa09ae59](https://linux-hardware.org/?probe=96aa09ae59) | Feb 21, 2023 |
| HP            | EliteBook 2540p             | [bf037f7503](https://linux-hardware.org/?probe=bf037f7503) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d1f67d5e08](https://linux-hardware.org/?probe=d1f67d5e08) | Feb 21, 2023 |
| Acer          | Nitro AN515-52              | [9989903f85](https://linux-hardware.org/?probe=9989903f85) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | [2b329d108f](https://linux-hardware.org/?probe=2b329d108f) | Feb 21, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [53737369e8](https://linux-hardware.org/?probe=53737369e8) | Feb 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b8c4b41baf](https://linux-hardware.org/?probe=b8c4b41baf) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | [a3ed8101b1](https://linux-hardware.org/?probe=a3ed8101b1) | Feb 20, 2023 |
| MSI           | Modern 15 A5M               | [f6c80ff7a9](https://linux-hardware.org/?probe=f6c80ff7a9) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK E559               | [5e4c3607c7](https://linux-hardware.org/?probe=5e4c3607c7) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a813f73ea2](https://linux-hardware.org/?probe=a813f73ea2) | Feb 20, 2023 |
| MSI           | Bravo 15 B5ED               | [a0b7f1b5f8](https://linux-hardware.org/?probe=a0b7f1b5f8) | Feb 20, 2023 |
| Lenovo        | ThinkPad T530 239265U       | [9f60ca6bf5](https://linux-hardware.org/?probe=9f60ca6bf5) | Feb 20, 2023 |
| Dell          | XPS 13 7390                 | [542077cc42](https://linux-hardware.org/?probe=542077cc42) | Feb 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [057dcdc86b](https://linux-hardware.org/?probe=057dcdc86b) | Feb 20, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d8abf7361b](https://linux-hardware.org/?probe=d8abf7361b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [89eb85b36f](https://linux-hardware.org/?probe=89eb85b36f) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | [7432db815e](https://linux-hardware.org/?probe=7432db815e) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | [aaee9da394](https://linux-hardware.org/?probe=aaee9da394) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [72f074b930](https://linux-hardware.org/?probe=72f074b930) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [c6d06c27c7](https://linux-hardware.org/?probe=c6d06c27c7) | Feb 19, 2023 |
| Dell          | Latitude E6430              | [23c0ff9281](https://linux-hardware.org/?probe=23c0ff9281) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [b1d168b6ce](https://linux-hardware.org/?probe=b1d168b6ce) | Feb 19, 2023 |
| Dell          | Latitude E6430              | [d97087b55f](https://linux-hardware.org/?probe=d97087b55f) | Feb 19, 2023 |
| Lenovo        | ThinkPad E555 20DH000TUK    | [b2d5c9de8b](https://linux-hardware.org/?probe=b2d5c9de8b) | Feb 19, 2023 |
| Standard      | Unknown                     | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [ee24b75c39](https://linux-hardware.org/?probe=ee24b75c39) | Feb 19, 2023 |
| Dell          | Precision M4500             | [b0d8bf3c56](https://linux-hardware.org/?probe=b0d8bf3c56) | Feb 19, 2023 |
| Apple         | MacBookAir6,1               | [5cade7cfc3](https://linux-hardware.org/?probe=5cade7cfc3) | Feb 19, 2023 |
| Google        | Kled                        | [788d726509](https://linux-hardware.org/?probe=788d726509) | Feb 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [9b53b2b842](https://linux-hardware.org/?probe=9b53b2b842) | Feb 18, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [cdfcc639d3](https://linux-hardware.org/?probe=cdfcc639d3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | [b835147a32](https://linux-hardware.org/?probe=b835147a32) | Feb 18, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [fb2cbe3576](https://linux-hardware.org/?probe=fb2cbe3576) | Feb 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a424b3aa47](https://linux-hardware.org/?probe=a424b3aa47) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [e7988c5ab6](https://linux-hardware.org/?probe=e7988c5ab6) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [6d2b283e83](https://linux-hardware.org/?probe=6d2b283e83) | Feb 18, 2023 |
| Dell          | Precision 5560              | [24e5de4a3d](https://linux-hardware.org/?probe=24e5de4a3d) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [53ef9ffad8](https://linux-hardware.org/?probe=53ef9ffad8) | Feb 17, 2023 |
| Dell          | Latitude 5491               | [8a3298cdff](https://linux-hardware.org/?probe=8a3298cdff) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [e4483255db](https://linux-hardware.org/?probe=e4483255db) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Dell          | Inspiron 5566               | [502adcba49](https://linux-hardware.org/?probe=502adcba49) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | [c1abb80cb1](https://linux-hardware.org/?probe=c1abb80cb1) | Feb 17, 2023 |
| Lenovo        | ZIWB2                       | [8ade075157](https://linux-hardware.org/?probe=8ade075157) | Feb 16, 2023 |
| HP            | 245 G8 Notebook PC          | [c48e458030](https://linux-hardware.org/?probe=c48e458030) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4657fc266d](https://linux-hardware.org/?probe=4657fc266d) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| Samsung       | 940XFG                      | [56f236f8ab](https://linux-hardware.org/?probe=56f236f8ab) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [5a3b0950b3](https://linux-hardware.org/?probe=5a3b0950b3) | Feb 16, 2023 |
| Lenovo        | Y50-70 20378                | [09301690c5](https://linux-hardware.org/?probe=09301690c5) | Feb 15, 2023 |
| HP            | Notebook                    | [9fe647f9a1](https://linux-hardware.org/?probe=9fe647f9a1) | Feb 15, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [36f57d56f8](https://linux-hardware.org/?probe=36f57d56f8) | Feb 15, 2023 |
| HP            | Notebook                    | [c4516fb37a](https://linux-hardware.org/?probe=c4516fb37a) | Feb 15, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7fd55795a0](https://linux-hardware.org/?probe=7fd55795a0) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [92a9452070](https://linux-hardware.org/?probe=92a9452070) | Feb 15, 2023 |
| Dell          | Inspiron 7375               | [3916d619ed](https://linux-hardware.org/?probe=3916d619ed) | Feb 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1ca19c3d1d](https://linux-hardware.org/?probe=1ca19c3d1d) | Feb 14, 2023 |
| ASUSTek       | UL30A                       | [90114a4fe4](https://linux-hardware.org/?probe=90114a4fe4) | Feb 14, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [390686f5f6](https://linux-hardware.org/?probe=390686f5f6) | Feb 14, 2023 |
| HP            | ProBook 440 G7              | [bc4811db07](https://linux-hardware.org/?probe=bc4811db07) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Dell          | Latitude E7270              | [03199b7612](https://linux-hardware.org/?probe=03199b7612) | Feb 14, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 81BL     | [008d06fbf8](https://linux-hardware.org/?probe=008d06fbf8) | Feb 14, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [561e1a6160](https://linux-hardware.org/?probe=561e1a6160) | Feb 14, 2023 |
| Dell          | Latitude 7430               | [82dcb0a8a2](https://linux-hardware.org/?probe=82dcb0a8a2) | Feb 14, 2023 |
| Dell          | G3 3579                     | [35c8b69b8c](https://linux-hardware.org/?probe=35c8b69b8c) | Feb 14, 2023 |
| HP            | EliteBook 840 G5            | [2f78b0c253](https://linux-hardware.org/?probe=2f78b0c253) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [ac71e5b8ef](https://linux-hardware.org/?probe=ac71e5b8ef) | Feb 14, 2023 |
| Dell          | Inspiron 14 5420            | [45862fde09](https://linux-hardware.org/?probe=45862fde09) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [1f0e965483](https://linux-hardware.org/?probe=1f0e965483) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | [8153aeb3fb](https://linux-hardware.org/?probe=8153aeb3fb) | Feb 13, 2023 |
| Dell          | XPS 15 9560                 | [01319ac289](https://linux-hardware.org/?probe=01319ac289) | Feb 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f701208fd4](https://linux-hardware.org/?probe=f701208fd4) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [3b7765dfcc](https://linux-hardware.org/?probe=3b7765dfcc) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [6add161dbe](https://linux-hardware.org/?probe=6add161dbe) | Feb 13, 2023 |
| Dell          | Latitude 5511               | [161095d97a](https://linux-hardware.org/?probe=161095d97a) | Feb 13, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [7e90fe56d1](https://linux-hardware.org/?probe=7e90fe56d1) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | [abd464b0d3](https://linux-hardware.org/?probe=abd464b0d3) | Feb 13, 2023 |
| HP            | ProBook 445 G7              | [7fdcffc633](https://linux-hardware.org/?probe=7fdcffc633) | Feb 13, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [0560a363b8](https://linux-hardware.org/?probe=0560a363b8) | Feb 12, 2023 |
| Dell          | Venue 10 Pro 5055           | [7afcfff799](https://linux-hardware.org/?probe=7afcfff799) | Feb 12, 2023 |
| Acer          | Aspire A715-74G             | [cdd913ae48](https://linux-hardware.org/?probe=cdd913ae48) | Feb 12, 2023 |
| Dell          | Latitude E6420              | [6ffa1ea310](https://linux-hardware.org/?probe=6ffa1ea310) | Feb 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [04cfa15383](https://linux-hardware.org/?probe=04cfa15383) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3c8717baf4](https://linux-hardware.org/?probe=3c8717baf4) | Feb 12, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [8f74caf33e](https://linux-hardware.org/?probe=8f74caf33e) | Feb 12, 2023 |
| HP            | EliteBook 840 G5            | [b569293b7b](https://linux-hardware.org/?probe=b569293b7b) | Feb 12, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [a4b4558244](https://linux-hardware.org/?probe=a4b4558244) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1e3ceef5e6](https://linux-hardware.org/?probe=1e3ceef5e6) | Feb 12, 2023 |
| HP            | Notebook                    | [729f2b5250](https://linux-hardware.org/?probe=729f2b5250) | Feb 12, 2023 |
| HP            | Notebook                    | [155c8fa16e](https://linux-hardware.org/?probe=155c8fa16e) | Feb 12, 2023 |
| ASUSTek       | X510UAR                     | [365b6606cd](https://linux-hardware.org/?probe=365b6606cd) | Feb 12, 2023 |
| HUAWEI        | NBD-WXX9                    | [c8caa92db3](https://linux-hardware.org/?probe=c8caa92db3) | Feb 11, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [321710ca2d](https://linux-hardware.org/?probe=321710ca2d) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [40116058d1](https://linux-hardware.org/?probe=40116058d1) | Feb 11, 2023 |
| HONOR         | BBR-WAX9                    | [de54b14304](https://linux-hardware.org/?probe=de54b14304) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [8e00bdf032](https://linux-hardware.org/?probe=8e00bdf032) | Feb 11, 2023 |
| Dell          | Vostro 15 3515              | [22d5eabee5](https://linux-hardware.org/?probe=22d5eabee5) | Feb 11, 2023 |
| HP            | Pavilion Power Laptop 15... | [2beb0c0b30](https://linux-hardware.org/?probe=2beb0c0b30) | Feb 11, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [a1133b56be](https://linux-hardware.org/?probe=a1133b56be) | Feb 11, 2023 |
| ASUSTek       | G75VW                       | [e2eeee26af](https://linux-hardware.org/?probe=e2eeee26af) | Feb 11, 2023 |
| Acer          | Aspire A315-23              | [f56c83d6dd](https://linux-hardware.org/?probe=f56c83d6dd) | Feb 11, 2023 |
| Dell          | Latitude E7270              | [c684709755](https://linux-hardware.org/?probe=c684709755) | Feb 11, 2023 |
| Acer          | TravelMate 7730             | [a9a9e21b5a](https://linux-hardware.org/?probe=a9a9e21b5a) | Feb 10, 2023 |
| Dell          | Inspiron 7559               | [956a602343](https://linux-hardware.org/?probe=956a602343) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [da12318597](https://linux-hardware.org/?probe=da12318597) | Feb 10, 2023 |
| Dell          | XPS 13 9310                 | [0461c55b4a](https://linux-hardware.org/?probe=0461c55b4a) | Feb 10, 2023 |
| MSI           | Raider GE77HX 12UHS         | [d77cac7fb6](https://linux-hardware.org/?probe=d77cac7fb6) | Feb 10, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [9b8563ab53](https://linux-hardware.org/?probe=9b8563ab53) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [3f4b71a601](https://linux-hardware.org/?probe=3f4b71a601) | Feb 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [25e4994344](https://linux-hardware.org/?probe=25e4994344) | Feb 09, 2023 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [6a55f84594](https://linux-hardware.org/?probe=6a55f84594) | Feb 09, 2023 |
| HP            | EliteBook 8460p             | [91de8b5956](https://linux-hardware.org/?probe=91de8b5956) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | [edc2a0bc35](https://linux-hardware.org/?probe=edc2a0bc35) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | [8d1a082e35](https://linux-hardware.org/?probe=8d1a082e35) | Feb 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8d2e488f38](https://linux-hardware.org/?probe=8d2e488f38) | Feb 09, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [467c3e9149](https://linux-hardware.org/?probe=467c3e9149) | Feb 09, 2023 |
| HP            | 2000                        | [f76b7389d7](https://linux-hardware.org/?probe=f76b7389d7) | Feb 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [81a3a141ba](https://linux-hardware.org/?probe=81a3a141ba) | Feb 08, 2023 |
| Acer          | Aspire A315-59              | [78d55087bb](https://linux-hardware.org/?probe=78d55087bb) | Feb 08, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [26fb33ec6c](https://linux-hardware.org/?probe=26fb33ec6c) | Feb 08, 2023 |
| Dell          | Latitude 3570               | [dc460632ef](https://linux-hardware.org/?probe=dc460632ef) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [bc2ea675c8](https://linux-hardware.org/?probe=bc2ea675c8) | Feb 08, 2023 |
| ASUSTek       | X510UAR                     | [0b2a31bed4](https://linux-hardware.org/?probe=0b2a31bed4) | Feb 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [9bf97a14cf](https://linux-hardware.org/?probe=9bf97a14cf) | Feb 08, 2023 |
| ASUSTek       | X510UAR                     | [b440353d20](https://linux-hardware.org/?probe=b440353d20) | Feb 08, 2023 |
| Google        | Delbin                      | [268fbe9849](https://linux-hardware.org/?probe=268fbe9849) | Feb 08, 2023 |
| Google        | Delbin                      | [1afd4fec8d](https://linux-hardware.org/?probe=1afd4fec8d) | Feb 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [5e5ec021d0](https://linux-hardware.org/?probe=5e5ec021d0) | Feb 08, 2023 |
| Apple         | MacBookPro10,1              | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| HP            | Pavilion 17                 | [9bd81582a4](https://linux-hardware.org/?probe=9bd81582a4) | Feb 07, 2023 |
| HP            | Pavilion 17                 | [45eb87271b](https://linux-hardware.org/?probe=45eb87271b) | Feb 07, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | [9e019a0396](https://linux-hardware.org/?probe=9e019a0396) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | [325806b7cc](https://linux-hardware.org/?probe=325806b7cc) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | [870a2912c9](https://linux-hardware.org/?probe=870a2912c9) | Feb 07, 2023 |
| HUAWEI        | MACH-WX9                    | [263101d492](https://linux-hardware.org/?probe=263101d492) | Feb 07, 2023 |
| Dell          | Latitude 5330               | [30cd96be4d](https://linux-hardware.org/?probe=30cd96be4d) | Feb 07, 2023 |
| Timi          | TM1613                      | [503133b0db](https://linux-hardware.org/?probe=503133b0db) | Feb 07, 2023 |
| Samsung       | 900X5N                      | [91793918de](https://linux-hardware.org/?probe=91793918de) | Feb 07, 2023 |
| HP            | Laptop 15-bw0xx             | [da8dac3c03](https://linux-hardware.org/?probe=da8dac3c03) | Feb 07, 2023 |
| Google        | Kefka                       | [5f290f685b](https://linux-hardware.org/?probe=5f290f685b) | Feb 06, 2023 |
| Dell          | Latitude 5490               | [95de125f35](https://linux-hardware.org/?probe=95de125f35) | Feb 06, 2023 |
| ASUSTek       | P453UA                      | [476ff28577](https://linux-hardware.org/?probe=476ff28577) | Feb 06, 2023 |
| MSI           | Stealth 15M B12UE           | [44de7ac1aa](https://linux-hardware.org/?probe=44de7ac1aa) | Feb 06, 2023 |
| ASUSTek       | G73Sw                       | [42e7c32817](https://linux-hardware.org/?probe=42e7c32817) | Feb 06, 2023 |
| Dell          | Inspiron 5749               | [2fbf439175](https://linux-hardware.org/?probe=2fbf439175) | Feb 06, 2023 |
| HONOR         | NMH-WCX9                    | [1f2418bafb](https://linux-hardware.org/?probe=1f2418bafb) | Feb 06, 2023 |
| Toshiba       | Satellite L50-B             | [fe59cbe322](https://linux-hardware.org/?probe=fe59cbe322) | Feb 06, 2023 |
| HP            | 2000                        | [5e672192b6](https://linux-hardware.org/?probe=5e672192b6) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f3ec6a2ed1](https://linux-hardware.org/?probe=f3ec6a2ed1) | Feb 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [da270fa237](https://linux-hardware.org/?probe=da270fa237) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [de72d92ada](https://linux-hardware.org/?probe=de72d92ada) | Feb 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | [c222b31f37](https://linux-hardware.org/?probe=c222b31f37) | Feb 05, 2023 |
| Google        | Kefka                       | [59e3f92752](https://linux-hardware.org/?probe=59e3f92752) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [a0fea9707e](https://linux-hardware.org/?probe=a0fea9707e) | Feb 05, 2023 |
| ASUSTek       | X556UV                      | [ae90dba4ca](https://linux-hardware.org/?probe=ae90dba4ca) | Feb 04, 2023 |
| Dell          | Inspiron 3593               | [2e87d3f607](https://linux-hardware.org/?probe=2e87d3f607) | Feb 04, 2023 |
| Dell          | Vostro 15 3515              | [c4c5c0888a](https://linux-hardware.org/?probe=c4c5c0888a) | Feb 04, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [8771985f5b](https://linux-hardware.org/?probe=8771985f5b) | Feb 04, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [9592836c3b](https://linux-hardware.org/?probe=9592836c3b) | Feb 04, 2023 |
| Dell          | XPS 15 9550                 | [200495d065](https://linux-hardware.org/?probe=200495d065) | Feb 04, 2023 |
| ASUSTek       | X200CA                      | [38cdc2564e](https://linux-hardware.org/?probe=38cdc2564e) | Feb 04, 2023 |
| HP            | Laptop 17-ak0xx             | [2ec4deba0b](https://linux-hardware.org/?probe=2ec4deba0b) | Feb 04, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cfaa43cc81](https://linux-hardware.org/?probe=cfaa43cc81) | Feb 04, 2023 |
| ASUSTek       | X200CA                      | [8c2a91c204](https://linux-hardware.org/?probe=8c2a91c204) | Feb 04, 2023 |
| SiComputer    | Nauta 01C                   | [1579a837f7](https://linux-hardware.org/?probe=1579a837f7) | Feb 04, 2023 |
| HUAWEI        | CREM-WXX9                   | [43a0910ff6](https://linux-hardware.org/?probe=43a0910ff6) | Feb 04, 2023 |
| Lenovo        | ThinkPad P72 20MB0005GE     | [6322972a9c](https://linux-hardware.org/?probe=6322972a9c) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | [c0434c976e](https://linux-hardware.org/?probe=c0434c976e) | Feb 04, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [1e38d08821](https://linux-hardware.org/?probe=1e38d08821) | Feb 03, 2023 |
| Dell          | Latitude 5530               | [dd0a933124](https://linux-hardware.org/?probe=dd0a933124) | Feb 03, 2023 |
| Dynabook      | PORTEGE X30L-K              | [af43366b45](https://linux-hardware.org/?probe=af43366b45) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | [fa1e255519](https://linux-hardware.org/?probe=fa1e255519) | Feb 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [d7fff6982b](https://linux-hardware.org/?probe=d7fff6982b) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | [ada6dd2b76](https://linux-hardware.org/?probe=ada6dd2b76) | Feb 03, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [a1073e64f7](https://linux-hardware.org/?probe=a1073e64f7) | Feb 03, 2023 |
| Dell          | Latitude E6430              | [10b3b0cfbb](https://linux-hardware.org/?probe=10b3b0cfbb) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9c5cfbc1a1](https://linux-hardware.org/?probe=9c5cfbc1a1) | Feb 03, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b660fd4859](https://linux-hardware.org/?probe=b660fd4859) | Feb 03, 2023 |
| ASUSTek       | UL30A                       | [11885376b2](https://linux-hardware.org/?probe=11885376b2) | Feb 03, 2023 |
| HP            | ProBook 440 G7              | [f9a4f80656](https://linux-hardware.org/?probe=f9a4f80656) | Feb 03, 2023 |
| ASUSTek       | G751JT                      | [2085089213](https://linux-hardware.org/?probe=2085089213) | Feb 03, 2023 |
| HUAWEI        | CREM-WXX9                   | [f794d33e76](https://linux-hardware.org/?probe=f794d33e76) | Feb 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8c9b8348a4](https://linux-hardware.org/?probe=8c9b8348a4) | Feb 02, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [bd19e14a45](https://linux-hardware.org/?probe=bd19e14a45) | Feb 02, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e49b22de8a](https://linux-hardware.org/?probe=e49b22de8a) | Feb 02, 2023 |
| Acer          | Aspire F5-573G              | [ba43497e32](https://linux-hardware.org/?probe=ba43497e32) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | [a169951063](https://linux-hardware.org/?probe=a169951063) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | [7dd8dceb80](https://linux-hardware.org/?probe=7dd8dceb80) | Feb 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [27c816b62a](https://linux-hardware.org/?probe=27c816b62a) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | [3339c49f38](https://linux-hardware.org/?probe=3339c49f38) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1c6ed7ede6](https://linux-hardware.org/?probe=1c6ed7ede6) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [367646ee16](https://linux-hardware.org/?probe=367646ee16) | Feb 02, 2023 |
| Lenovo        | ZIWB2                       | [b7ff6b4dd5](https://linux-hardware.org/?probe=b7ff6b4dd5) | Feb 02, 2023 |
| ASUSTek       | K54L                        | [8568b17267](https://linux-hardware.org/?probe=8568b17267) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | [45890fca78](https://linux-hardware.org/?probe=45890fca78) | Feb 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [159a453649](https://linux-hardware.org/?probe=159a453649) | Feb 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0538afb301](https://linux-hardware.org/?probe=0538afb301) | Feb 02, 2023 |
| Dell          | XPS 15 9510                 | [78ea388883](https://linux-hardware.org/?probe=78ea388883) | Feb 02, 2023 |
| Dell          | Latitude E6430              | [55c398146b](https://linux-hardware.org/?probe=55c398146b) | Feb 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [8bc290ef67](https://linux-hardware.org/?probe=8bc290ef67) | Feb 01, 2023 |
| MSI           | Modern 14 B11MOU            | [542173e9a2](https://linux-hardware.org/?probe=542173e9a2) | Feb 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ab31f6153e](https://linux-hardware.org/?probe=ab31f6153e) | Feb 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [22abfb4a79](https://linux-hardware.org/?probe=22abfb4a79) | Feb 01, 2023 |
| Lenovo        | ThinkPad A485 20MVS0U500    | [b398a8e8e6](https://linux-hardware.org/?probe=b398a8e8e6) | Feb 01, 2023 |
| ASUSTek       | N552VW                      | [1ebeeec517](https://linux-hardware.org/?probe=1ebeeec517) | Feb 01, 2023 |
| Dell          | Inspiron 7501               | [426493e8a5](https://linux-hardware.org/?probe=426493e8a5) | Feb 01, 2023 |
| HP            | Laptop 14-dq4xxx            | [c102edf6a0](https://linux-hardware.org/?probe=c102edf6a0) | Feb 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [6b9dc508e1](https://linux-hardware.org/?probe=6b9dc508e1) | Feb 01, 2023 |
| Dell          | Inspiron 5748               | [7ee6505f8d](https://linux-hardware.org/?probe=7ee6505f8d) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [1d212c67b2](https://linux-hardware.org/?probe=1d212c67b2) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| HUAWEI        | HN-WX9X                     | [4b8ddf5d09](https://linux-hardware.org/?probe=4b8ddf5d09) | Jan 31, 2023 |
| Dell          | Inspiron 5748               | [ecbd4ac8b6](https://linux-hardware.org/?probe=ecbd4ac8b6) | Jan 31, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | [85ac6a588d](https://linux-hardware.org/?probe=85ac6a588d) | Jan 31, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [4dcc88b215](https://linux-hardware.org/?probe=4dcc88b215) | Jan 31, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [2df9f60f2e](https://linux-hardware.org/?probe=2df9f60f2e) | Jan 31, 2023 |
| Acer          | Predator PH315-52           | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [a64ae29757](https://linux-hardware.org/?probe=a64ae29757) | Jan 31, 2023 |
| Samsung       | 550XCJ/550XCR               | [75fad3daf3](https://linux-hardware.org/?probe=75fad3daf3) | Jan 31, 2023 |
| Dell          | XPS 15 9570                 | [ee60c1c921](https://linux-hardware.org/?probe=ee60c1c921) | Jan 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [87904d9d06](https://linux-hardware.org/?probe=87904d9d06) | Jan 31, 2023 |
| Dell          | Vostro 15 3515              | [357d14774f](https://linux-hardware.org/?probe=357d14774f) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Latitude 7480               | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ecef01472](https://linux-hardware.org/?probe=1ecef01472) | Jan 30, 2023 |
| HP            | Pavilion 15                 | [6ceccb3d73](https://linux-hardware.org/?probe=6ceccb3d73) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | [5802e6b9b9](https://linux-hardware.org/?probe=5802e6b9b9) | Jan 30, 2023 |
| Dell          | XPS 15 9570                 | [1d06f2715a](https://linux-hardware.org/?probe=1d06f2715a) | Jan 30, 2023 |
| Dell          | Vostro 7620                 | [b6d43b8741](https://linux-hardware.org/?probe=b6d43b8741) | Jan 29, 2023 |
| HP            | Laptop 14-cm0xxx            | [9b93652159](https://linux-hardware.org/?probe=9b93652159) | Jan 29, 2023 |
| Acer          | Aspire V5-573G              | [e253d5b49b](https://linux-hardware.org/?probe=e253d5b49b) | Jan 29, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [32d5472e21](https://linux-hardware.org/?probe=32d5472e21) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| TECNO         | MEGABOOK T1                 | [db0e6c89b4](https://linux-hardware.org/?probe=db0e6c89b4) | Jan 29, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [41d33a9029](https://linux-hardware.org/?probe=41d33a9029) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| Dell          | XPS 13 7390                 | [60c03ee1f7](https://linux-hardware.org/?probe=60c03ee1f7) | Jan 29, 2023 |
| HP            | EliteBook 840 G1            | [30549ebd3a](https://linux-hardware.org/?probe=30549ebd3a) | Jan 28, 2023 |
| HP            | Laptop 15-da2xxx            | [8384a02b4b](https://linux-hardware.org/?probe=8384a02b4b) | Jan 28, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [53015adc9d](https://linux-hardware.org/?probe=53015adc9d) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ed1ce46901](https://linux-hardware.org/?probe=ed1ce46901) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [844e4e4b2a](https://linux-hardware.org/?probe=844e4e4b2a) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ab3f84f96b](https://linux-hardware.org/?probe=ab3f84f96b) | Jan 28, 2023 |
| Apple         | MacBookPro11,4              | [8a5423443a](https://linux-hardware.org/?probe=8a5423443a) | Jan 28, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [7e6cf30d81](https://linux-hardware.org/?probe=7e6cf30d81) | Jan 28, 2023 |
| Timi          | A35S                        | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [fb7b1bdaf5](https://linux-hardware.org/?probe=fb7b1bdaf5) | Jan 27, 2023 |
| Lenovo        | ThinkPad T450s 20BWS23W0... | [41c82dbadb](https://linux-hardware.org/?probe=41c82dbadb) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a69331d2ea](https://linux-hardware.org/?probe=a69331d2ea) | Jan 27, 2023 |
| Acer          | Swift SF314-511             | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| HONOR         | BMH-WCX9                    | [882bb3b505](https://linux-hardware.org/?probe=882bb3b505) | Jan 27, 2023 |
| MECHREVO      | Code10-7CC6U                | [86e769b2a3](https://linux-hardware.org/?probe=86e769b2a3) | Jan 27, 2023 |
| Dell          | Precision 3550              | [4c42615cef](https://linux-hardware.org/?probe=4c42615cef) | Jan 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [00e21c8359](https://linux-hardware.org/?probe=00e21c8359) | Jan 27, 2023 |
| Dynabook      | TECRA A50-J                 | [a2ad3f4eb3](https://linux-hardware.org/?probe=a2ad3f4eb3) | Jan 27, 2023 |
| Dynabook      | TECRA A50-J                 | [3921b100b4](https://linux-hardware.org/?probe=3921b100b4) | Jan 27, 2023 |
| ASUSTek       | X550VX                      | [37d2157b37](https://linux-hardware.org/?probe=37d2157b37) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [9dfc820ceb](https://linux-hardware.org/?probe=9dfc820ceb) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [0168a5cae2](https://linux-hardware.org/?probe=0168a5cae2) | Jan 26, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [4024f7c3bd](https://linux-hardware.org/?probe=4024f7c3bd) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [a1dfc58700](https://linux-hardware.org/?probe=a1dfc58700) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [303593899d](https://linux-hardware.org/?probe=303593899d) | Jan 26, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Multilaser    | PC150                       | [1c4ace00d1](https://linux-hardware.org/?probe=1c4ace00d1) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [8725d530e5](https://linux-hardware.org/?probe=8725d530e5) | Jan 26, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ea142e4848](https://linux-hardware.org/?probe=ea142e4848) | Jan 25, 2023 |
| HP            | EliteBook 2540p             | [f03240c746](https://linux-hardware.org/?probe=f03240c746) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [af63cfc79a](https://linux-hardware.org/?probe=af63cfc79a) | Jan 25, 2023 |
| Clevo         | M815P                       | [cfc5f6689f](https://linux-hardware.org/?probe=cfc5f6689f) | Jan 25, 2023 |
| MSI           | GL63 8RC                    | [138e8de541](https://linux-hardware.org/?probe=138e8de541) | Jan 25, 2023 |
| Acer          | Aspire A315-59              | [33292253d0](https://linux-hardware.org/?probe=33292253d0) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| Dynabook      | TECRA A50-J                 | [2f24f18672](https://linux-hardware.org/?probe=2f24f18672) | Jan 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [993ba3e73b](https://linux-hardware.org/?probe=993ba3e73b) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [aa6488b6b8](https://linux-hardware.org/?probe=aa6488b6b8) | Jan 25, 2023 |
| Fujitsu Si... | AMILO Notebook Xa 3530      | [e8384494a3](https://linux-hardware.org/?probe=e8384494a3) | Jan 25, 2023 |
| Dell          | Inspiron 5402               | [d8df4aafe8](https://linux-hardware.org/?probe=d8df4aafe8) | Jan 25, 2023 |
| Dell          | Inspiron 5468               | [3e59c1f38b](https://linux-hardware.org/?probe=3e59c1f38b) | Jan 25, 2023 |
| Acer          | Nitro AN515-42              | [cb02367642](https://linux-hardware.org/?probe=cb02367642) | Jan 25, 2023 |
| Dell          | Latitude 5420               | [cd6dc3695e](https://linux-hardware.org/?probe=cd6dc3695e) | Jan 24, 2023 |
| Dell          | Latitude 5520               | [662284824b](https://linux-hardware.org/?probe=662284824b) | Jan 24, 2023 |
| HP            | ProBook 6570b               | [841250ba59](https://linux-hardware.org/?probe=841250ba59) | Jan 24, 2023 |
| Dell          | Latitude E6410              | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Lenovo        | ThinkPad T500 2082BPG       | [08a30fd24c](https://linux-hardware.org/?probe=08a30fd24c) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [3fb25133ec](https://linux-hardware.org/?probe=3fb25133ec) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| Google        | Treeya                      | [27a381272a](https://linux-hardware.org/?probe=27a381272a) | Jan 24, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a227de29c5](https://linux-hardware.org/?probe=a227de29c5) | Jan 24, 2023 |
| Dell          | Precision 3551              | [1338d3df20](https://linux-hardware.org/?probe=1338d3df20) | Jan 23, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [335275777a](https://linux-hardware.org/?probe=335275777a) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [e40bb2f01f](https://linux-hardware.org/?probe=e40bb2f01f) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [31789ae630](https://linux-hardware.org/?probe=31789ae630) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [091effd2ac](https://linux-hardware.org/?probe=091effd2ac) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | [0a597ba033](https://linux-hardware.org/?probe=0a597ba033) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | [90884b19a9](https://linux-hardware.org/?probe=90884b19a9) | Jan 23, 2023 |
| Lenovo        | ThinkPad P50 20EQS12Q3M     | [e46b5a8b46](https://linux-hardware.org/?probe=e46b5a8b46) | Jan 23, 2023 |
| Dell          | Latitude E6500              | [ba7c36fe15](https://linux-hardware.org/?probe=ba7c36fe15) | Jan 23, 2023 |
| Dynabook      | TECRA A50-J                 | [689fe06d4d](https://linux-hardware.org/?probe=689fe06d4d) | Jan 23, 2023 |
| Dynabook      | TECRA A50-J                 | [92690b43cd](https://linux-hardware.org/?probe=92690b43cd) | Jan 23, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d03b7c0a68](https://linux-hardware.org/?probe=d03b7c0a68) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [07005e3e32](https://linux-hardware.org/?probe=07005e3e32) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [d999192dbf](https://linux-hardware.org/?probe=d999192dbf) | Jan 22, 2023 |
| HP            | EliteBook 820 G3            | [3edd4ab0dc](https://linux-hardware.org/?probe=3edd4ab0dc) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [523d0331a1](https://linux-hardware.org/?probe=523d0331a1) | Jan 21, 2023 |
| HP            | Victus by Gaming Laptop ... | [0aa98390a7](https://linux-hardware.org/?probe=0aa98390a7) | Jan 21, 2023 |
| Acer          | Predator G9-591             | [0544a1b07c](https://linux-hardware.org/?probe=0544a1b07c) | Jan 21, 2023 |
| Dell          | XPS 9315                    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [e8a0c0066b](https://linux-hardware.org/?probe=e8a0c0066b) | Jan 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [adeb24c41e](https://linux-hardware.org/?probe=adeb24c41e) | Jan 21, 2023 |
| Dell          | G5 5587                     | [96ca22c550](https://linux-hardware.org/?probe=96ca22c550) | Jan 21, 2023 |
| Dell          | G5 5587                     | [a070a8ba69](https://linux-hardware.org/?probe=a070a8ba69) | Jan 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [c228c064b7](https://linux-hardware.org/?probe=c228c064b7) | Jan 20, 2023 |
| Dell          | Venue 8 Pro 5830            | [4f815d5b4f](https://linux-hardware.org/?probe=4f815d5b4f) | Jan 20, 2023 |
| Acer          | Aspire A315-42G             | [ed4c536efa](https://linux-hardware.org/?probe=ed4c536efa) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| Acer          | Aspire A515-45              | [9d5faff505](https://linux-hardware.org/?probe=9d5faff505) | Jan 20, 2023 |
| MSI           | GS66 Stealth 10UE           | [d5a2a6aaa8](https://linux-hardware.org/?probe=d5a2a6aaa8) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | [15c0522754](https://linux-hardware.org/?probe=15c0522754) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | [e81652a68c](https://linux-hardware.org/?probe=e81652a68c) | Jan 19, 2023 |
| Dell          | Precision 3551              | [4ff5a0ab8d](https://linux-hardware.org/?probe=4ff5a0ab8d) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [0f079e1dc7](https://linux-hardware.org/?probe=0f079e1dc7) | Jan 19, 2023 |
| Acer          | Aspire A315-23              | [90049e4bb7](https://linux-hardware.org/?probe=90049e4bb7) | Jan 19, 2023 |
| Acer          | Nitro AN515-42              | [d6a24ede85](https://linux-hardware.org/?probe=d6a24ede85) | Jan 19, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [6a47296f0c](https://linux-hardware.org/?probe=6a47296f0c) | Jan 19, 2023 |
| Dell          | Latitude 3410               | [187aebc2cd](https://linux-hardware.org/?probe=187aebc2cd) | Jan 19, 2023 |
| Intel Clie... | LAPRC510                    | [6d570a1aee](https://linux-hardware.org/?probe=6d570a1aee) | Jan 19, 2023 |
| ASUSTek       | X455LF                      | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| Dell          | Latitude 5290 2-in-1        | [ff6ad7bf11](https://linux-hardware.org/?probe=ff6ad7bf11) | Jan 18, 2023 |
| HP            | Victus by Gaming Laptop ... | [533d99e2f1](https://linux-hardware.org/?probe=533d99e2f1) | Jan 18, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [d27ca45841](https://linux-hardware.org/?probe=d27ca45841) | Jan 18, 2023 |
| Dell          | Precision 3561              | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Acer          | Swift SFX14-41G             | [1b916fe30d](https://linux-hardware.org/?probe=1b916fe30d) | Jan 18, 2023 |
| Lenovo        | Yoga 500-14IHW 80N5         | [e233e8d6d2](https://linux-hardware.org/?probe=e233e8d6d2) | Jan 18, 2023 |
| Acer          | Nitro AN515-54              | [4a997fa99d](https://linux-hardware.org/?probe=4a997fa99d) | Jan 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| HP            | Laptop 17-ca0xxx            | [a8fbe01fc5](https://linux-hardware.org/?probe=a8fbe01fc5) | Jan 17, 2023 |
| Acer          | Aspire A315-59              | [469c40ec75](https://linux-hardware.org/?probe=469c40ec75) | Jan 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | [3dbc34a913](https://linux-hardware.org/?probe=3dbc34a913) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [681de2b0c1](https://linux-hardware.org/?probe=681de2b0c1) | Jan 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b36d7e8eb](https://linux-hardware.org/?probe=7b36d7e8eb) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [f1ee502754](https://linux-hardware.org/?probe=f1ee502754) | Jan 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0d91852ebf](https://linux-hardware.org/?probe=0d91852ebf) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c16356f056](https://linux-hardware.org/?probe=c16356f056) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [70b8007dcc](https://linux-hardware.org/?probe=70b8007dcc) | Jan 17, 2023 |
| Acer          | Aspire AV14-51              | [596219796d](https://linux-hardware.org/?probe=596219796d) | Jan 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b39c4fc9b7](https://linux-hardware.org/?probe=b39c4fc9b7) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [1c81e8c322](https://linux-hardware.org/?probe=1c81e8c322) | Jan 16, 2023 |
| Dell          | Inspiron 11 - 3147          | [af542a44ad](https://linux-hardware.org/?probe=af542a44ad) | Jan 16, 2023 |
| PC Special... | Recoil II RTX               | [33850c8810](https://linux-hardware.org/?probe=33850c8810) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [b53dd87f87](https://linux-hardware.org/?probe=b53dd87f87) | Jan 16, 2023 |
| Schenker      | XMG CORE 15 (M22)           | [6c2b631f12](https://linux-hardware.org/?probe=6c2b631f12) | Jan 16, 2023 |
| HP            | 15                          | [ae082994e2](https://linux-hardware.org/?probe=ae082994e2) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | [1de96d005a](https://linux-hardware.org/?probe=1de96d005a) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | [f0eab1c81a](https://linux-hardware.org/?probe=f0eab1c81a) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e1aa5d3186](https://linux-hardware.org/?probe=e1aa5d3186) | Jan 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1a51848ffb](https://linux-hardware.org/?probe=1a51848ffb) | Jan 16, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [b36eb94e80](https://linux-hardware.org/?probe=b36eb94e80) | Jan 16, 2023 |
| HP            | 255 G6 Notebook PC          | [4d2e9f3ee4](https://linux-hardware.org/?probe=4d2e9f3ee4) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | [cb2e9f2623](https://linux-hardware.org/?probe=cb2e9f2623) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9ac2f0ab83](https://linux-hardware.org/?probe=9ac2f0ab83) | Jan 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_37/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.0.7-301.fc37.x86_64   | 92        | 6.68%   |
| 6.0.15-300.fc37.x86_64  | 76        | 5.52%   |
| 6.1.14-200.fc37.x86_64  | 61        | 4.43%   |
| 6.1.7-200.fc37.x86_64   | 56        | 4.07%   |
| 6.0.8-300.fc37.x86_64   | 56        | 4.07%   |
| 6.0.9-300.fc37.x86_64   | 52        | 3.78%   |
| 6.1.18-200.fc37.x86_64  | 51        | 3.7%    |
| 6.0.12-300.fc37.x86_64  | 51        | 3.7%    |
| 6.2.8-200.fc37.x86_64   | 46        | 3.34%   |
| 6.1.8-200.fc37.x86_64   | 43        | 3.12%   |
| 6.1.11-200.fc37.x86_64  | 42        | 3.05%   |
| 6.1.9-200.fc37.x86_64   | 40        | 2.9%    |
| 6.2.7-200.fc37.x86_64   | 38        | 2.76%   |
| 6.0.11-300.fc37.x86_64  | 37        | 2.69%   |
| 6.2.9-200.fc37.x86_64   | 36        | 2.61%   |
| 6.1.6-200.fc37.x86_64   | 36        | 2.61%   |
| 6.1.13-200.fc37.x86_64  | 36        | 2.61%   |
| 6.1.10-200.fc37.x86_64  | 36        | 2.61%   |
| 6.0.10-300.fc37.x86_64  | 35        | 2.54%   |
| 6.0.18-300.fc37.x86_64  | 32        | 2.32%   |
| 6.0.16-300.fc37.x86_64  | 31        | 2.25%   |
| 6.1.15-200.fc37.x86_64  | 29        | 2.11%   |
| 5.19.16-301.fc37.x86_64 | 25        | 1.82%   |
| 6.1.5-200.fc37.x86_64   | 21        | 1.53%   |
| 6.2.15-200.fc37.x86_64  | 19        | 1.38%   |
| 6.0.17-300.fc37.x86_64  | 18        | 1.31%   |
| 6.1.12-200.fc37.x86_64  | 17        | 1.23%   |
| 6.0.14-300.fc37.x86_64  | 17        | 1.23%   |
| 6.0.13-300.fc37.x86_64  | 16        | 1.16%   |
| 6.2.10-200.fc37.x86_64  | 14        | 1.02%   |
| 6.3.8-100.fc37.x86_64   | 10        | 0.73%   |
| 6.2.14-200.fc37.x86_64  | 10        | 0.73%   |
| 5.19.8-300.fc37.x86_64  | 10        | 0.73%   |
| 6.2.11-200.fc37.x86_64  | 9         | 0.65%   |
| 5.19.7-300.fc37.x86_64  | 9         | 0.65%   |
| 5.19.13-300.fc37.x86_64 | 9         | 0.65%   |
| 6.2.12-200.fc37.x86_64  | 8         | 0.58%   |
| 5.19.14-300.fc37.x86_64 | 7         | 0.51%   |
| 5.19.11-300.fc37.x86_64 | 7         | 0.51%   |
| 6.0.6-300.fc37.x86_64   | 6         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.7   | 92        | 6.68%   |
| 6.0.15  | 78        | 5.66%   |
| 6.1.14  | 62        | 4.5%    |
| 6.0.8   | 60        | 4.36%   |
| 6.0.9   | 58        | 4.21%   |
| 6.1.7   | 56        | 4.07%   |
| 6.1.18  | 51        | 3.7%    |
| 6.0.12  | 51        | 3.7%    |
| 6.2.8   | 46        | 3.34%   |
| 6.1.8   | 44        | 3.2%    |
| 6.1.11  | 44        | 3.2%    |
| 6.1.9   | 41        | 2.98%   |
| 6.2.7   | 38        | 2.76%   |
| 6.1.10  | 38        | 2.76%   |
| 6.2.9   | 37        | 2.69%   |
| 6.0.11  | 37        | 2.69%   |
| 6.1.6   | 36        | 2.61%   |
| 6.1.13  | 36        | 2.61%   |
| 6.0.10  | 36        | 2.61%   |
| 6.0.18  | 32        | 2.32%   |
| 6.0.16  | 31        | 2.25%   |
| 6.1.15  | 29        | 2.11%   |
| 5.19.16 | 29        | 2.11%   |
| 6.1.5   | 21        | 1.53%   |
| 6.2.15  | 19        | 1.38%   |
| 6.1.12  | 18        | 1.31%   |
| 6.0.17  | 18        | 1.31%   |
| 6.0.14  | 17        | 1.23%   |
| 6.0.13  | 16        | 1.16%   |
| 6.2.10  | 15        | 1.09%   |
| 6.3.8   | 10        | 0.73%   |
| 6.2.14  | 10        | 0.73%   |
| 5.19.8  | 10        | 0.73%   |
| 6.2.11  | 9         | 0.65%   |
| 5.19.7  | 9         | 0.65%   |
| 5.19.13 | 9         | 0.65%   |
| 6.2.12  | 8         | 0.58%   |
| 5.19.15 | 8         | 0.58%   |
| 6.1.0   | 7         | 0.51%   |
| 5.19.14 | 7         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 509       | 38.74%  |
| 6.1     | 460       | 35.01%  |
| 6.2     | 183       | 13.93%  |
| 5.19    | 98        | 7.46%   |
| 6.3     | 26        | 1.98%   |
| 6.4     | 16        | 1.22%   |
| 6.5     | 15        | 1.14%   |
| 5.18    | 2         | 0.15%   |
| 5.17    | 2         | 0.15%   |
| 5.15    | 2         | 0.15%   |
| 5.10    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1238      | 99.92%  |
| aarch64 | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 922       | 73.82%  |
| KDE5          | 210       | 16.81%  |
| XFCE          | 26        | 2.08%   |
| Unknown       | 25        | 2%      |
| X-Cinnamon    | 15        | 1.2%    |
| MATE          | 13        | 1.04%   |
| i3            | 12        | 0.96%   |
| Cinnamon      | 5         | 0.4%    |
| sway          | 4         | 0.32%   |
| LXDE          | 3         | 0.24%   |
| LXQt          | 2         | 0.16%   |
| KDE           | 2         | 0.16%   |
| GNOME-Classic | 2         | 0.16%   |
| xmonad        | 1         | 0.08%   |
| xinit-compat  | 1         | 0.08%   |
| qtile         | 1         | 0.08%   |
| Hyprland      | 1         | 0.08%   |
| GNOME Classic | 1         | 0.08%   |
| fluxbox       | 1         | 0.08%   |
| Deepin        | 1         | 0.08%   |
| custom        | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 945       | 75.06%  |
| X11     | 292       | 23.19%  |
| Unknown | 13        | 1.03%   |
| Tty     | 9         | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 587       | 46.92%  |
| GDM     | 479       | 38.29%  |
| SDDM    | 113       | 9.03%   |
| LightDM | 68        | 5.44%   |
| LXDM    | 3         | 0.24%   |
| GREETD  | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 659       | 52.85%  |
| en_GB   | 88        | 7.06%   |
| ru_RU   | 85        | 6.82%   |
| pt_BR   | 48        | 3.85%   |
| de_DE   | 46        | 3.69%   |
| fr_FR   | 39        | 3.13%   |
| it_IT   | 37        | 2.97%   |
| en_IN   | 22        | 1.76%   |
| es_ES   | 21        | 1.68%   |
| en_AU   | 19        | 1.52%   |
| en_CA   | 18        | 1.44%   |
| pl_PL   | 15        | 1.2%    |
| es_MX   | 13        | 1.04%   |
| zh_CN   | 12        | 0.96%   |
| es_CL   | 12        | 0.96%   |
| tr_TR   | 10        | 0.8%    |
| de_AT   | 6         | 0.48%   |
| C       | 6         | 0.48%   |
| Unknown | 6         | 0.48%   |
| es_AR   | 5         | 0.4%    |
| en_ZA   | 5         | 0.4%    |
| zh_TW   | 4         | 0.32%   |
| hu_HU   | 4         | 0.32%   |
| sv_SE   | 3         | 0.24%   |
| nl_NL   | 3         | 0.24%   |
| es_CO   | 3         | 0.24%   |
| en_PH   | 3         | 0.24%   |
| en_IE   | 3         | 0.24%   |
| en_DK   | 3         | 0.24%   |
| de_CH   | 3         | 0.24%   |
| cs_CZ   | 3         | 0.24%   |
| pt_PT   | 2         | 0.16%   |
| fr_CA   | 2         | 0.16%   |
| fr_BE   | 2         | 0.16%   |
| fi_FI   | 2         | 0.16%   |
| es_VE   | 2         | 0.16%   |
| es_PE   | 2         | 0.16%   |
| es_GT   | 2         | 0.16%   |
| en_SG   | 2         | 0.16%   |
| en_IL   | 2         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1086      | 87.3%   |
| BIOS | 158       | 12.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 1017      | 81.75%  |
| Ext4    | 204       | 16.4%   |
| Xfs     | 17        | 1.37%   |
| Overlay | 5         | 0.4%    |
| Unknown | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 651       | 52.25%  |
| Unknown | 567       | 45.51%  |
| MBR     | 28        | 2.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1126      | 90.3%   |
| Yes       | 121       | 9.7%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1001      | 80.4%   |
| Yes       | 244       | 19.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 353       | 28.49%  |
| Hewlett-Packard      | 186       | 15.01%  |
| Dell                 | 185       | 14.93%  |
| ASUSTek Computer     | 158       | 12.75%  |
| Acer                 | 78        | 6.3%    |
| HUAWEI               | 41        | 3.31%   |
| MSI                  | 39        | 3.15%   |
| Apple                | 20        | 1.61%   |
| Toshiba              | 17        | 1.37%   |
| Samsung Electronics  | 14        | 1.13%   |
| Google               | 14        | 1.13%   |
| Timi                 | 13        | 1.05%   |
| TUXEDO               | 8         | 0.65%   |
| Notebook             | 8         | 0.65%   |
| HONOR                | 7         | 0.56%   |
| Fujitsu              | 7         | 0.56%   |
| Framework            | 6         | 0.48%   |
| GPD                  | 5         | 0.4%    |
| Alienware            | 5         | 0.4%    |
| System76             | 4         | 0.32%   |
| Schenker             | 4         | 0.32%   |
| Sony                 | 3         | 0.24%   |
| Dynabook             | 3         | 0.24%   |
| Chuwi                | 3         | 0.24%   |
| Unknown              | 3         | 0.24%   |
| TECNO                | 2         | 0.16%   |
| Standard             | 2         | 0.16%   |
| SLIMBOOK             | 2         | 0.16%   |
| Pegatron             | 2         | 0.16%   |
| MACHENIKE            | 2         | 0.16%   |
| LG Electronics       | 2         | 0.16%   |
| Intel Client Systems | 2         | 0.16%   |
| Intel                | 2         | 0.16%   |
| ilife                | 2         | 0.16%   |
| Valve                | 1         | 0.08%   |
| UNOWHY               | 1         | 0.08%   |
| SK hynix             | 1         | 0.08%   |
| SiComputer           | 1         | 0.08%   |
| Razer                | 1         | 0.08%   |
| Purism               | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 7         | 0.56%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 6         | 0.48%   |
| Lenovo ThinkBook 15 G3 ACL 21A4             | 6         | 0.48%   |
| HUAWEI CREM-WXX9                            | 6         | 0.48%   |
| HP Notebook                                 | 5         | 0.4%    |
| Dell XPS 13 7390                            | 5         | 0.4%    |
| MSI Modern 14 B11MOU                        | 4         | 0.32%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5            | 4         | 0.32%   |
| Lenovo IdeaPad 330-15IKB 81DE               | 4         | 0.32%   |
| HUAWEI MACH-WX9                             | 4         | 0.32%   |
| HUAWEI HVY-WXX9                             | 4         | 0.32%   |
| HP OMEN by Laptop 16-c0xxx                  | 4         | 0.32%   |
| Framework Laptop (12th Gen Intel Core)      | 4         | 0.32%   |
| Dell XPS 13 9310                            | 4         | 0.32%   |
| Dell Latitude 7490                          | 4         | 0.32%   |
| Dell Latitude 5420                          | 4         | 0.32%   |
| Dell Inspiron 5566                          | 4         | 0.32%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA      | 4         | 0.32%   |
| Acer Nitro AN515-54                         | 4         | 0.32%   |
| Lenovo Legion 5 15ACH6H 82JU                | 3         | 0.24%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK       | 3         | 0.24%   |
| HUAWEI NBLK-WAX9X                           | 3         | 0.24%   |
| HUAWEI NBLB-WAX9N                           | 3         | 0.24%   |
| HUAWEI KLVL-WXX9                            | 3         | 0.24%   |
| HUAWEI BOHK-WAX9X                           | 3         | 0.24%   |
| HP ProBook 440 G7                           | 3         | 0.24%   |
| HP Pavilion Laptop 15-eg0xxx                | 3         | 0.24%   |
| HP Laptop 15-dw3xxx                         | 3         | 0.24%   |
| HP EliteBook 845 14 inch G9 Notebook PC     | 3         | 0.24%   |
| HP EliteBook 840 G3                         | 3         | 0.24%   |
| GPD G1619-04                                | 3         | 0.24%   |
| Dell XPS 9320                               | 3         | 0.24%   |
| Dell XPS 15 9570                            | 3         | 0.24%   |
| Dell XPS 15 9520                            | 3         | 0.24%   |
| Dell XPS 15 9510                            | 3         | 0.24%   |
| Dell XPS 13 9380                            | 3         | 0.24%   |
| Dell Latitude E7270                         | 3         | 0.24%   |
| Dell Latitude 7480                          | 3         | 0.24%   |
| Dell Latitude 7430                          | 3         | 0.24%   |
| Dell Inspiron 7577                          | 3         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 209       | 16.87%  |
| Lenovo IdeaPad      | 70        | 5.65%   |
| Dell Latitude       | 63        | 5.08%   |
| Dell Inspiron       | 51        | 4.12%   |
| ASUS VivoBook       | 43        | 3.47%   |
| Acer Aspire         | 43        | 3.47%   |
| HP Pavilion         | 37        | 2.99%   |
| HP EliteBook        | 37        | 2.99%   |
| Dell XPS            | 35        | 2.82%   |
| HP Laptop           | 30        | 2.42%   |
| Lenovo ThinkBook    | 29        | 2.34%   |
| HP ProBook          | 24        | 1.94%   |
| ASUS ROG            | 24        | 1.94%   |
| ASUS ASUS           | 23        | 1.86%   |
| ASUS ZenBook        | 16        | 1.29%   |
| Acer Nitro          | 16        | 1.29%   |
| Lenovo Legion       | 15        | 1.21%   |
| Toshiba Satellite   | 13        | 1.05%   |
| Dell Precision      | 13        | 1.05%   |
| HP ZBook            | 11        | 0.89%   |
| HP OMEN             | 11        | 0.89%   |
| Dell Vostro         | 11        | 0.89%   |
| MSI Modern          | 9         | 0.73%   |
| Lenovo Yoga         | 9         | 0.73%   |
| HP ENVY             | 7         | 0.56%   |
| Acer Predator       | 7         | 0.56%   |
| Unknown             | 7         | 0.56%   |
| HUAWEI CREM-WXX9    | 6         | 0.48%   |
| HP 250              | 6         | 0.48%   |
| Fujitsu LIFEBOOK    | 6         | 0.48%   |
| Framework Laptop    | 6         | 0.48%   |
| Acer Swift          | 6         | 0.48%   |
| MSI Stealth         | 5         | 0.4%    |
| HP Notebook         | 5         | 0.4%    |
| TUXEDO InfinityBook | 4         | 0.32%   |
| HUAWEI MACH-WX9     | 4         | 0.32%   |
| HUAWEI HVY-WXX9     | 4         | 0.32%   |
| HP Victus           | 4         | 0.32%   |
| Dell G15            | 4         | 0.32%   |
| Apple MacBookPro9   | 4         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 239       | 19.29%  |
| 2020    | 194       | 15.66%  |
| 2022    | 179       | 14.45%  |
| 2019    | 118       | 9.52%   |
| 2018    | 118       | 9.52%   |
| 2017    | 79        | 6.38%   |
| 2016    | 53        | 4.28%   |
| 2014    | 52        | 4.2%    |
| 2012    | 52        | 4.2%    |
| 2013    | 46        | 3.71%   |
| 2015    | 41        | 3.31%   |
| 2011    | 21        | 1.69%   |
| 2010    | 13        | 1.05%   |
| 2008    | 12        | 0.97%   |
| 2023    | 10        | 0.81%   |
| 2007    | 5         | 0.4%    |
| 2009    | 3         | 0.24%   |
| 2006    | 2         | 0.16%   |
| Unknown | 2         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1239      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 903       | 72.36%  |
| Enabled  | 345       | 27.64%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1221      | 98.55%  |
| Yes  | 18        | 1.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 326       | 26.23%  |
| 16.01-24.0  | 283       | 22.77%  |
| 8.01-16.0   | 274       | 22.04%  |
| 32.01-64.0  | 178       | 14.32%  |
| 3.01-4.0    | 97        | 7.8%    |
| 24.01-32.0  | 32        | 2.57%   |
| 64.01-256.0 | 30        | 2.41%   |
| 1.01-2.0    | 21        | 1.69%   |
| 2.01-3.0    | 2         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 448       | 33.91%  |
| 3.01-4.0   | 309       | 23.39%  |
| 2.01-3.0   | 305       | 23.09%  |
| 8.01-16.0  | 119       | 9.01%   |
| 1.01-2.0   | 103       | 7.8%    |
| 16.01-24.0 | 17        | 1.29%   |
| 0.51-1.0   | 14        | 1.06%   |
| 24.01-32.0 | 4         | 0.3%    |
| 32.01-64.0 | 2         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 929       | 74.44%  |
| 2      | 276       | 22.12%  |
| 3      | 28        | 2.24%   |
| 4      | 7         | 0.56%   |
| 0      | 7         | 0.56%   |
| 6      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1076      | 86.77%  |
| Yes       | 164       | 13.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 842       | 67.85%  |
| No        | 399       | 32.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1221      | 98.47%  |
| No        | 19        | 1.53%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1080      | 86.96%  |
| No        | 162       | 13.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 173       | 13.9%   |
| Russia       | 106       | 8.51%   |
| Germany      | 94        | 7.55%   |
| Italy        | 73        | 5.86%   |
| Brazil       | 71        | 5.7%    |
| India        | 53        | 4.26%   |
| France       | 47        | 3.78%   |
| Poland       | 41        | 3.29%   |
| Canada       | 36        | 2.89%   |
| UK           | 34        | 2.73%   |
| Spain        | 31        | 2.49%   |
| Netherlands  | 30        | 2.41%   |
| Turkey       | 28        | 2.25%   |
| Australia    | 25        | 2.01%   |
| Mexico       | 21        | 1.69%   |
| Austria      | 19        | 1.53%   |
| Switzerland  | 14        | 1.12%   |
| Sweden       | 14        | 1.12%   |
| Czechia      | 13        | 1.04%   |
| Chile        | 13        | 1.04%   |
| Indonesia    | 12        | 0.96%   |
| Hungary      | 11        | 0.88%   |
| Taiwan       | 10        | 0.8%    |
| Portugal     | 10        | 0.8%    |
| Belgium      | 10        | 0.8%    |
| Argentina    | 10        | 0.8%    |
| Israel       | 9         | 0.72%   |
| Japan        | 8         | 0.64%   |
| Hong Kong    | 8         | 0.64%   |
| Finland      | 8         | 0.64%   |
| South Africa | 7         | 0.56%   |
| Slovakia     | 7         | 0.56%   |
| Iran         | 7         | 0.56%   |
| Vietnam      | 6         | 0.48%   |
| Thailand     | 6         | 0.48%   |
| Serbia       | 6         | 0.48%   |
| Romania      | 6         | 0.48%   |
| Norway       | 6         | 0.48%   |
| Denmark      | 6         | 0.48%   |
| China        | 6         | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 31        | 2.4%    |
| Berlin            | 15        | 1.16%   |
| St Petersburg     | 14        | 1.08%   |
| Madrid            | 13        | 1.01%   |
| Vienna            | 11        | 0.85%   |
| Istanbul          | 10        | 0.77%   |
| Sao Paulo         | 9         | 0.7%    |
| Milan             | 9         | 0.7%    |
| Warsaw            | 8         | 0.62%   |
| Frankfurt am Main | 8         | 0.62%   |
| Delft             | 8         | 0.62%   |
| Paris             | 7         | 0.54%   |
| Melbourne         | 7         | 0.54%   |
| Jakarta           | 7         | 0.54%   |
| Brisbane          | 7         | 0.54%   |
| Bengaluru         | 7         | 0.54%   |
| Amsterdam         | 7         | 0.54%   |
| Perm              | 6         | 0.46%   |
| Montreal          | 6         | 0.46%   |
| Milano            | 6         | 0.46%   |
| Wroclaw           | 5         | 0.39%   |
| Sydney            | 5         | 0.39%   |
| Singapore         | 5         | 0.39%   |
| Santiago          | 5         | 0.39%   |
| London            | 5         | 0.39%   |
| Lisbon            | 5         | 0.39%   |
| Helsinki          | 5         | 0.39%   |
| Gdansk            | 5         | 0.39%   |
| Central           | 5         | 0.39%   |
| Budapest          | 5         | 0.39%   |
| Zurich            | 4         | 0.31%   |
| Tokyo             | 4         | 0.31%   |
| Temuco            | 4         | 0.31%   |
| Tel Aviv          | 4         | 0.31%   |
| Sofia             | 4         | 0.31%   |
| Pune              | 4         | 0.31%   |
| Prague            | 4         | 0.31%   |
| Porto Alegre      | 4         | 0.31%   |
| Portland          | 4         | 0.31%   |
| Oslo              | 4         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 369       | 441    | 23.96%  |
| WDC                         | 130       | 149    | 8.44%   |
| Sandisk                     | 129       | 150    | 8.38%   |
| SK hynix                    | 110       | 125    | 7.14%   |
| Kingston                    | 76        | 85     | 4.94%   |
| Micron Technology           | 74        | 86     | 4.81%   |
| Toshiba                     | 73        | 81     | 4.74%   |
| Unknown                     | 66        | 78     | 4.29%   |
| Seagate                     | 66        | 74     | 4.29%   |
| Intel                       | 64        | 76     | 4.16%   |
| Crucial                     | 50        | 58     | 3.25%   |
| KIOXIA                      | 39        | 49     | 2.53%   |
| HGST                        | 24        | 26     | 1.56%   |
| A-DATA Technology           | 18        | 19     | 1.17%   |
| Micron/Crucial Technology   | 14        | 15     | 0.91%   |
| Apple                       | 14        | 23     | 0.91%   |
| Kingston Technology Company | 12        | 12     | 0.78%   |
| Phison Electronics          | 11        | 12     | 0.71%   |
| PNY                         | 10        | 11     | 0.65%   |
| LITEON                      | 10        | 10     | 0.65%   |
| ADATA Technology            | 10        | 12     | 0.65%   |
| Phison                      | 9         | 9      | 0.58%   |
| China                       | 8         | 9      | 0.52%   |
| Hitachi                     | 7         | 7      | 0.45%   |
| Unknown                     | 7         | 11     | 0.45%   |
| UMIS                        | 6         | 6      | 0.39%   |
| Silicon Motion              | 6         | 6      | 0.39%   |
| JMicron Technology          | 6         | 6      | 0.39%   |
| SPCC                        | 5         | 5      | 0.32%   |
| Realtek Semiconductor       | 5         | 5      | 0.32%   |
| Netac                       | 4         | 7      | 0.26%   |
| Lexar                       | 4         | 5      | 0.26%   |
| Lenovo                      | 4         | 4      | 0.26%   |
| Intenso                     | 4         | 5      | 0.26%   |
| HS-SSD-E100                 | 4         | 4      | 0.26%   |
| Gigabyte Technology         | 4         | 6      | 0.26%   |
| FORESEE                     | 4         | 5      | 0.26%   |
| YMTC                        | 3         | 3      | 0.19%   |
| XPG                         | 3         | 3      | 0.19%   |
| SABRENT                     | 3         | 3      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 65        | 4.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 34        | 2.14%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 24        | 1.51%   |
| Toshiba MQ04ABF100 1TB                              | 18        | 1.13%   |
| Seagate ST1000LM035-1RK172 1TB                      | 18        | 1.13%   |
| Intel SSDPEKNU512GZ 512GB                           | 18        | 1.13%   |
| Unknown MMC Card  32GB                              | 13        | 0.82%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 12        | 0.76%   |
| Kingston SA400S37240G 240GB SSD                     | 12        | 0.76%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 500GB     | 11        | 0.69%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 11        | 0.69%   |
| Crucial CT240BX500SSD1 240GB                        | 11        | 0.69%   |
| Kingston SA400S37480G 480GB SSD                     | 10        | 0.63%   |
| Intel SSD 660P Series 512GB                         | 10        | 0.63%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 9         | 0.57%   |
| Samsung SSD 980 1TB                                 | 9         | 0.57%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 9         | 0.57%   |
| HGST HTS721010A9E630 1TB                            | 9         | 0.57%   |
| Crucial CT1000MX500SSD1 1TB                         | 9         | 0.57%   |
| Unknown MMC Card  64GB                              | 8         | 0.5%    |
| Sandisk WD Black SN850 1024GB                       | 8         | 0.5%    |
| Samsung MZALQ512HALU-000L2 512GB                    | 8         | 0.5%    |
| Micron 2210_MTFDHBA512QFD 512GB                     | 8         | 0.5%    |
| Unknown MMC Card  128GB                             | 7         | 0.44%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB              | 7         | 0.44%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 7         | 0.44%   |
| Samsung SSD 980 PRO 1TB                             | 7         | 0.44%   |
| Samsung SSD 860 EVO 500GB                           | 7         | 0.44%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                    | 7         | 0.44%   |
| KIOXIA KBG40ZNV512G 512GB                           | 7         | 0.44%   |
| Unknown                                             | 7         | 0.44%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 6         | 0.38%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 6         | 0.38%   |
| SanDisk NVMe SSD Drive 1TB                          | 6         | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB                      | 6         | 0.38%   |
| Samsung SSD 860 EVO 250GB                           | 6         | 0.38%   |
| Samsung MZVLQ512HBLU-00B00 512GB                    | 6         | 0.38%   |
| Intel SSD Pro 7600p/760p/E 6100p Series 1TB         | 6         | 0.38%   |
| HGST HTS725050A7E630 500GB                          | 6         | 0.38%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 5         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 64        | 72     | 31.68%  |
| WDC      | 54        | 61     | 26.73%  |
| Toshiba  | 45        | 47     | 22.28%  |
| HGST     | 24        | 26     | 11.88%  |
| Hitachi  | 7         | 7      | 3.47%   |
| Unknown  | 3         | 5      | 1.49%   |
| TO Exter | 1         | 1      | 0.5%    |
| Intenso  | 1         | 1      | 0.5%    |
| HGST HTS | 1         | 1      | 0.5%    |
| Fujitsu  | 1         | 1      | 0.5%    |
| External | 1         | 1      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 83        | 93     | 22.31%  |
| Kingston            | 46        | 50     | 12.37%  |
| Crucial             | 41        | 48     | 11.02%  |
| SanDisk             | 28        | 30     | 7.53%   |
| WDC                 | 26        | 29     | 6.99%   |
| SK hynix            | 18        | 18     | 4.84%   |
| Micron Technology   | 13        | 14     | 3.49%   |
| Apple               | 10        | 11     | 2.69%   |
| PNY                 | 9         | 10     | 2.42%   |
| A-DATA Technology   | 9         | 9      | 2.42%   |
| LITEON              | 8         | 8      | 2.15%   |
| China               | 8         | 9      | 2.15%   |
| Toshiba             | 7         | 8      | 1.88%   |
| JMicron Technology  | 4         | 4      | 1.08%   |
| Intenso             | 4         | 4      | 1.08%   |
| Intel               | 4         | 4      | 1.08%   |
| Gigabyte Technology | 4         | 6      | 1.08%   |
| SPCC                | 3         | 3      | 0.81%   |
| Netac               | 3         | 5      | 0.81%   |
| Lexar               | 3         | 4      | 0.81%   |
| GOODRAM             | 3         | 4      | 0.81%   |
| Apacer              | 3         | 4      | 0.81%   |
| Team                | 2         | 3      | 0.54%   |
| Patriot             | 2         | 2      | 0.54%   |
| LITEONIT            | 2         | 2      | 0.54%   |
| KingSpec            | 2         | 3      | 0.54%   |
| FORESEE             | 2         | 2      | 0.54%   |
| Corsair             | 2         | 2      | 0.54%   |
| Unknown             | 2         | 2      | 0.54%   |
| XrayDisk            | 1         | 1      | 0.27%   |
| WDC WDS2            | 1         | 1      | 0.27%   |
| Verbatim            | 1         | 1      | 0.27%   |
| Transcend           | 1         | 1      | 0.27%   |
| Teclast             | 1         | 2      | 0.27%   |
| Ramaxel Technology  | 1         | 1      | 0.27%   |
| OCZ                 | 1         | 1      | 0.27%   |
| Mushkin             | 1         | 1      | 0.27%   |
| MidasForce          | 1         | 1      | 0.27%   |
| Leven               | 1         | 1      | 0.27%   |
| Lenovo              | 1         | 1      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 819       | 1045   | 56.4%   |
| SSD     | 348       | 414    | 23.97%  |
| HDD     | 196       | 223    | 13.5%   |
| MMC     | 69        | 79     | 4.75%   |
| Unknown | 20        | 23     | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 817       | 1037   | 57.82%  |
| SATA | 477       | 609    | 33.76%  |
| MMC  | 69        | 79     | 4.88%   |
| SAS  | 50        | 59     | 3.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 337       | 407    | 62.06%  |
| 0.51-1.0   | 181       | 202    | 33.33%  |
| 1.01-2.0   | 19        | 22     | 3.5%    |
| 4.01-10.0  | 4         | 4      | 0.74%   |
| 3.01-4.0   | 2         | 2      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 283       | 22.39%  |
| 251-500        | 263       | 20.81%  |
| 1-20           | 169       | 13.37%  |
| 1001-2000      | 168       | 13.29%  |
| 101-250        | 154       | 12.18%  |
| Unknown        | 110       | 8.7%    |
| More than 3000 | 32        | 2.53%   |
| 51-100         | 32        | 2.53%   |
| 21-50          | 28        | 2.22%   |
| 2001-3000      | 25        | 1.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 379       | 29.22%  |
| 21-50          | 204       | 15.73%  |
| 101-250        | 188       | 14.49%  |
| 51-100         | 157       | 12.1%   |
| 251-500        | 134       | 10.33%  |
| Unknown        | 110       | 8.48%   |
| 501-1000       | 92        | 7.09%   |
| 1001-2000      | 25        | 1.93%   |
| 2001-3000      | 5         | 0.39%   |
| More than 3000 | 3         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB                                 | 3         | 3      | 6.67%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                                | 2         | 2      | 4.44%   |
| Seagate ST500LT012-1DG142 500GB                                 | 2         | 2      | 4.44%   |
| HGST HTS725050A7E630 500GB                                      | 2         | 2      | 4.44%   |
| HGST HTS721010A9E630 1TB                                        | 2         | 2      | 4.44%   |
| WDC WD5000LPVX-22V0TT0 500GB                                    | 1         | 1      | 2.22%   |
| WDC WD10JPVX-60JC3T1 1TB                                        | 1         | 1      | 2.22%   |
| Toshiba MQ01ABD075 752GB                                        | 1         | 1      | 2.22%   |
| Toshiba MK5061GSY 500GB                                         | 1         | 1      | 2.22%   |
| Toshiba MK3265GSX 320GB                                         | 1         | 1      | 2.22%   |
| Toshiba MK1237GSX 120GB                                         | 1         | 1      | 2.22%   |
| SK hynix SC308 SATA 128GB SSD                                   | 1         | 1      | 2.22%   |
| SK hynix HFS256G39MND-2300A 256GB SSD                           | 1         | 1      | 2.22%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 1         | 1      | 2.22%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                            | 1         | 1      | 2.22%   |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 2.22%   |
| Seagate ST9320325AS 320GB                                       | 1         | 1      | 2.22%   |
| Seagate ST750LM022 HN-M750MBB 752GB                             | 1         | 1      | 2.22%   |
| Seagate ST500LT012-9WS142 500GB                                 | 1         | 1      | 2.22%   |
| Seagate ST500LM012 HN-M500MBB 500GB                             | 1         | 1      | 2.22%   |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 2.22%   |
| Seagate ST500LM000-1EJ162 500GB                                 | 1         | 1      | 2.22%   |
| Seagate ST4000LM024-2AN17V 4TB                                  | 1         | 1      | 2.22%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                              | 1         | 1      | 2.22%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 2.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 1         | 1      | 2.22%   |
| SanDisk iSSD P4 8GB                                             | 1         | 1      | 2.22%   |
| Samsung Electronics SSD 870 EVO 500GB                           | 1         | 2      | 2.22%   |
| Samsung Electronics PM9A1 NVMe 1024GB                           | 1         | 1      | 2.22%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 250GB | 1         | 1      | 2.22%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD             | 1         | 1      | 2.22%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD                  | 1         | 1      | 2.22%   |
| Micron Technology 1100 SATA 512GB SSD                           | 1         | 1      | 2.22%   |
| Kingston SNV425S264GB SSD                                       | 1         | 1      | 2.22%   |
| HGST HTS541075A9E680 752GB                                      | 1         | 1      | 2.22%   |
| HGST HTS 545050A7E680 500GB                                     | 1         | 1      | 2.22%   |
| Crucial CT525MX300SSD1 528GB                                    | 1         | 1      | 2.22%   |
| Crucial CT1050MX300SSD1 1050GB                                  | 1         | 1      | 2.22%   |
| Unknown                                                         | 1         | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 28.89%  |
| Samsung Electronics | 6         | 7      | 13.33%  |
| HGST                | 5         | 5      | 11.11%  |
| WDC                 | 4         | 4      | 8.89%   |
| Toshiba             | 4         | 4      | 8.89%   |
| SK hynix            | 4         | 4      | 8.89%   |
| Micron Technology   | 3         | 3      | 6.67%   |
| Crucial             | 2         | 2      | 4.44%   |
| SanDisk             | 1         | 1      | 2.22%   |
| Kingston            | 1         | 1      | 2.22%   |
| HGST HTS            | 1         | 1      | 2.22%   |
| Unknown             | 1         | 1      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 13        | 13     | 52%     |
| HGST     | 5         | 5      | 20%     |
| Toshiba  | 4         | 4      | 16%     |
| WDC      | 2         | 2      | 8%      |
| HGST HTS | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 25     | 55.56%  |
| SSD  | 14        | 15     | 31.11%  |
| NVMe | 6         | 6      | 13.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 50%     |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 668       | 966    | 51.31%  |
| Works    | 588       | 770    | 45.16%  |
| Malfunc  | 44        | 46     | 3.38%   |
| Failed   | 2         | 2      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 649       | 40.11%  |
| Samsung Electronics            | 297       | 18.36%  |
| SanDisk                        | 152       | 9.39%   |
| AMD                            | 144       | 8.9%    |
| SK hynix                       | 92        | 5.69%   |
| Micron Technology              | 62        | 3.83%   |
| Kingston Technology Company    | 42        | 2.6%    |
| KIOXIA                         | 34        | 2.1%    |
| Toshiba America Info Systems   | 29        | 1.79%   |
| Phison Electronics             | 22        | 1.36%   |
| Micron/Crucial Technology      | 20        | 1.24%   |
| ADATA Technology               | 19        | 1.17%   |
| Union Memory (Shenzhen)        | 9         | 0.56%   |
| Silicon Motion                 | 7         | 0.43%   |
| Realtek Semiconductor          | 7         | 0.43%   |
| Solid State Storage Technology | 5         | 0.31%   |
| Shenzhen Longsys Electronics   | 5         | 0.31%   |
| Lite-On Technology             | 5         | 0.31%   |
| Yangtze Memory Technologies    | 4         | 0.25%   |
| MAXIO Technology (Hangzhou)    | 3         | 0.19%   |
| Lenovo                         | 3         | 0.19%   |
| Apple                          | 3         | 0.19%   |
| Biwin Storage Technology       | 2         | 0.12%   |
| Nvidia                         | 1         | 0.06%   |
| Netac Technology               | 1         | 0.06%   |
| Marvell Technology Group       | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 139       | 8.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 115       | 6.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 101       | 5.94%   |
| Intel Volume Management Device NVMe RAID Controller                            | 98        | 5.76%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 92        | 5.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 72        | 4.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 66        | 3.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 51        | 3%      |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 50        | 2.94%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 39        | 2.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 36        | 2.12%   |
| Intel Tiger Lake-LP SATA Controller                                            | 35        | 2.06%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 30        | 1.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 26        | 1.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 25        | 1.47%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 25        | 1.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 1.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 21        | 1.23%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 19        | 1.12%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 18        | 1.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 18        | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 17        | 1%      |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 16        | 0.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 16        | 0.94%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 15        | 0.88%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 14        | 0.82%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 14        | 0.82%   |
| Intel SSD 660P Series                                                          | 14        | 0.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 14        | 0.82%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 13        | 0.76%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 13        | 0.76%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 13        | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 12        | 0.71%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 12        | 0.71%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 12        | 0.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 12        | 0.71%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 11        | 0.65%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 10        | 0.59%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 9         | 0.53%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 9         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 816       | 50.18%  |
| SATA | 629       | 38.68%  |
| RAID | 167       | 10.27%  |
| IDE  | 14        | 0.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 919       | 74.17%  |
| AMD     | 319       | 25.75%  |
| Unknown | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 45        | 3.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 32        | 2.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 24        | 1.94%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 24        | 1.94%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 23        | 1.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 21        | 1.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 21        | 1.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 1.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 19        | 1.53%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 18        | 1.45%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 17        | 1.37%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 17        | 1.37%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 17        | 1.37%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 17        | 1.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 15        | 1.21%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 15        | 1.21%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 1.21%   |
| Intel 12th Gen Core i7-12700H                 | 15        | 1.21%   |
| Intel 12th Gen Core i7-1260P                  | 15        | 1.21%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 13        | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 1.05%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 13        | 1.05%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 1.05%   |
| Intel 12th Gen Core i5-1235U                  | 13        | 1.05%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 1.05%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 12        | 0.97%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 12        | 0.97%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 12        | 0.97%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 12        | 0.97%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 12        | 0.97%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 11        | 0.89%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.89%   |
| Intel 12th Gen Core i7-1255U                  | 11        | 0.89%   |
| Intel 12th Gen Core i5-1240P                  | 11        | 0.89%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 11        | 0.89%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 10        | 0.81%   |
| Intel 12th Gen Core i9-12900H                 | 10        | 0.81%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 9         | 0.73%   |
| Intel 12th Gen Core i5-12500H                 | 9         | 0.73%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 9         | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 262       | 21.13%  |
| Other                                | 261       | 21.05%  |
| Intel Core i7                        | 250       | 20.16%  |
| AMD Ryzen 7                          | 104       | 8.39%   |
| AMD Ryzen 5                          | 98        | 7.9%    |
| Intel Core i3                        | 57        | 4.6%    |
| Intel Celeron                        | 29        | 2.34%   |
| AMD Ryzen 7 PRO                      | 29        | 2.34%   |
| AMD Ryzen 9                          | 25        | 2.02%   |
| AMD Ryzen 3                          | 19        | 1.53%   |
| Intel Core 2 Duo                     | 17        | 1.37%   |
| Intel Atom                           | 16        | 1.29%   |
| AMD Ryzen 5 PRO                      | 16        | 1.29%   |
| Intel Pentium                        | 9         | 0.73%   |
| Intel Core i9                        | 7         | 0.56%   |
| AMD A6                               | 6         | 0.48%   |
| AMD A4                               | 5         | 0.4%    |
| AMD A12                              | 4         | 0.32%   |
| AMD A10                              | 4         | 0.32%   |
| Intel Pentium Silver                 | 3         | 0.24%   |
| Intel Core m3                        | 3         | 0.24%   |
| Intel Pentium Dual-Core              | 2         | 0.16%   |
| Intel Core 2                         | 2         | 0.16%   |
| AMD E1                               | 2         | 0.16%   |
| AMD A8                               | 2         | 0.16%   |
| Intel Pentium Dual                   | 1         | 0.08%   |
| Intel Genuine                        | 1         | 0.08%   |
| Intel Core m7                        | 1         | 0.08%   |
| Intel Core m5                        | 1         | 0.08%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.08%   |
| AMD PRO A8                           | 1         | 0.08%   |
| AMD E                                | 1         | 0.08%   |
| AMD Athlon II                        | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 458       | 36.97%  |
| 2      | 332       | 26.8%   |
| 8      | 182       | 14.69%  |
| 6      | 156       | 12.59%  |
| 12     | 41        | 3.31%   |
| 14     | 34        | 2.74%   |
| 10     | 29        | 2.34%   |
| 16     | 4         | 0.32%   |
| 1      | 2         | 0.16%   |
| 5      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1239      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1119      | 90.24%  |
| 1      | 121       | 9.76%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1238      | 99.92%  |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 228       | 18.02%  |
| 0x806c1    | 93        | 7.35%   |
| 0x0a50000c | 70        | 5.53%   |
| 0x806ec    | 65        | 5.14%   |
| 0x806ea    | 60        | 4.74%   |
| 0x906a3    | 58        | 4.58%   |
| 0x306a9    | 42        | 3.32%   |
| 0x406e3    | 41        | 3.24%   |
| 0x906ea    | 38        | 3%      |
| 0x08608103 | 36        | 2.85%   |
| 0x08600106 | 32        | 2.53%   |
| 0xa0652    | 31        | 2.45%   |
| 0x806e9    | 29        | 2.29%   |
| 0x306d4    | 27        | 2.13%   |
| 0x0a404102 | 25        | 1.98%   |
| 0x08108109 | 25        | 1.98%   |
| 0x806d1    | 24        | 1.9%    |
| 0x906a4    | 23        | 1.82%   |
| 0x40651    | 20        | 1.58%   |
| 0x206a7    | 20        | 1.58%   |
| 0x706e5    | 17        | 1.34%   |
| 0x506e3    | 16        | 1.26%   |
| 0x906e9    | 15        | 1.19%   |
| 0x306c3    | 15        | 1.19%   |
| 0x0a50000d | 15        | 1.19%   |
| 0x08600104 | 15        | 1.19%   |
| 0x806c2    | 12        | 0.95%   |
| 0x30678    | 12        | 0.95%   |
| 0x0a404101 | 11        | 0.87%   |
| 0x0810100b | 10        | 0.79%   |
| 0x806eb    | 9         | 0.71%   |
| 0x706a8    | 9         | 0.71%   |
| 0x1067a    | 9         | 0.71%   |
| 0x08608102 | 9         | 0.71%   |
| 0x406c4    | 6         | 0.47%   |
| 0x06006705 | 6         | 0.47%   |
| 0x08600103 | 5         | 0.4%    |
| 0x08108102 | 5         | 0.4%    |
| 0xa0660    | 4         | 0.32%   |
| 0x906ed    | 4         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 286       | 23.08%  |
| TigerLake        | 122       | 9.85%   |
| Alderlake Hybrid | 107       | 8.64%   |
| Zen 3            | 97        | 7.83%   |
| Unknown          | 95        | 7.67%   |
| Skylake          | 73        | 5.89%   |
| Zen 2            | 60        | 4.84%   |
| IvyBridge        | 52        | 4.2%    |
| Haswell          | 48        | 3.87%   |
| CometLake        | 47        | 3.79%   |
| IceLake          | 44        | 3.55%   |
| Zen+             | 31        | 2.5%    |
| Silvermont       | 30        | 2.42%   |
| Broadwell        | 29        | 2.34%   |
| SandyBridge      | 24        | 1.94%   |
| Zen              | 16        | 1.29%   |
| Penryn           | 14        | 1.13%   |
| Excavator        | 13        | 1.05%   |
| Goldmont plus    | 10        | 0.81%   |
| Westmere         | 8         | 0.65%   |
| Core             | 8         | 0.65%   |
| Goldmont         | 5         | 0.4%    |
| Tremont          | 4         | 0.32%   |
| Piledriver       | 3         | 0.24%   |
| Jaguar           | 3         | 0.24%   |
| Steamroller      | 2         | 0.16%   |
| Puma             | 2         | 0.16%   |
| Nehalem          | 1         | 0.08%   |
| K8 & K10 hybrid  | 1         | 0.08%   |
| K10 Llano        | 1         | 0.08%   |
| K10              | 1         | 0.08%   |
| Bonnell          | 1         | 0.08%   |
| Bobcat           | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 882       | 54.11%  |
| Nvidia | 388       | 23.8%   |
| AMD    | 360       | 22.09%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 108       | 6.48%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 76        | 4.56%   |
| Intel UHD Graphics 620                                                                   | 68        | 4.08%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 62        | 3.72%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 58        | 3.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 50        | 3%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 50        | 3%      |
| AMD Lucienne                                                                             | 48        | 2.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 47        | 2.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 47        | 2.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 45        | 2.7%    |
| Intel HD Graphics 620                                                                    | 44        | 2.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 39        | 2.34%   |
| AMD Rembrandt [Radeon 680M]                                                              | 37        | 2.22%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 36        | 2.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 33        | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 31        | 1.86%   |
| Intel HD Graphics 5500                                                                   | 27        | 1.62%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 25        | 1.5%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 24        | 1.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 24        | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 1.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 1.26%   |
| Intel HD Graphics 630                                                                    | 19        | 1.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 18        | 1.08%   |
| AMD Barcelo                                                                              | 18        | 1.08%   |
| Intel HD Graphics 530                                                                    | 17        | 1.02%   |
| Nvidia GP108M [GeForce MX150]                                                            | 16        | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 16        | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 14        | 0.84%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 14        | 0.84%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 13        | 0.78%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 13        | 0.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 13        | 0.78%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 12        | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 11        | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 0.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 0.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 542       | 43.74%  |
| Intel + Nvidia     | 299       | 24.13%  |
| 1 x AMD            | 248       | 20.02%  |
| AMD + Nvidia       | 55        | 4.44%   |
| Intel + AMD        | 32        | 2.58%   |
| 1 x Nvidia         | 31        | 2.5%    |
| 2 x AMD            | 25        | 2.02%   |
| 2 x Intel          | 5         | 0.4%    |
| Other              | 1         | 0.08%   |
| Intel + 2 x Nvidia | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1018      | 81.64%  |
| Proprietary | 205       | 16.44%  |
| Unknown     | 24        | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 755       | 60.35%  |
| 0.01-0.5   | 168       | 13.43%  |
| 1.01-2.0   | 129       | 10.31%  |
| 3.01-4.0   | 85        | 6.79%   |
| 0.51-1.0   | 61        | 4.88%   |
| 5.01-6.0   | 27        | 2.16%   |
| 7.01-8.0   | 15        | 1.2%    |
| 8.01-16.0  | 7         | 0.56%   |
| 2.01-3.0   | 4         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 272       | 18.11%  |
| BOE                     | 269       | 17.91%  |
| Chimei Innolux          | 221       | 14.71%  |
| LG Display              | 166       | 11.05%  |
| Samsung Electronics     | 92        | 6.13%   |
| Dell                    | 59        | 3.93%   |
| Sharp                   | 54        | 3.6%    |
| Goldstar                | 36        | 2.4%    |
| CSO                     | 30        | 2%      |
| PANDA                   | 29        | 1.93%   |
| Lenovo                  | 28        | 1.86%   |
| Hewlett-Packard         | 22        | 1.46%   |
| AOC                     | 21        | 1.4%    |
| Apple                   | 20        | 1.33%   |
| BenQ                    | 17        | 1.13%   |
| Acer                    | 16        | 1.07%   |
| InfoVision              | 13        | 0.87%   |
| Philips                 | 10        | 0.67%   |
| ASUSTek Computer        | 10        | 0.67%   |
| Chi Mei Optoelectronics | 9         | 0.6%    |
| ViewSonic               | 8         | 0.53%   |
| TMX                     | 7         | 0.47%   |
| JDI                     | 7         | 0.47%   |
| Iiyama                  | 6         | 0.4%    |
| Toshiba                 | 5         | 0.33%   |
| Sony                    | 5         | 0.33%   |
| Mi                      | 5         | 0.33%   |
| LG Philips              | 5         | 0.33%   |
| Ancor Communications    | 5         | 0.33%   |
| MSI                     | 4         | 0.27%   |
| Vestel Elektronik       | 3         | 0.2%    |
| Tianma XM               | 3         | 0.2%    |
| Panasonic               | 3         | 0.2%    |
| HUAWEI                  | 3         | 0.2%    |
| NEC Computers           | 2         | 0.13%   |
| NCS                     | 2         | 0.13%   |
| IBM                     | 2         | 0.13%   |
| Fujitsu Siemens         | 2         | 0.13%   |
| CTO                     | 2         | 0.13%   |
| Vizio                   | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 19        | 1.25%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 15        | 0.99%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 15        | 0.99%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 14        | 0.92%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 12        | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 12        | 0.79%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 10        | 0.66%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 10        | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 9         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 0.53%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 8         | 0.53%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 8         | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 7         | 0.46%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 7         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 6         | 0.39%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 6         | 0.39%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                 | 6         | 0.39%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 6         | 0.39%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 6         | 0.39%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 6         | 0.39%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 6         | 0.39%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 5         | 0.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 5         | 0.33%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 5         | 0.33%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 5         | 0.33%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 5         | 0.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4         | 0.26%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch          | 4         | 0.26%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 4         | 0.26%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 4         | 0.26%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 4         | 0.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.26%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 4         | 0.26%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 4         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 743       | 53.72%  |
| 1366x768 (WXGA)    | 188       | 13.59%  |
| 3840x2160 (4K)     | 78        | 5.64%   |
| 2560x1440 (QHD)    | 62        | 4.48%   |
| 1920x1200 (WUXGA)  | 55        | 3.98%   |
| 2560x1600          | 45        | 3.25%   |
| 1600x900 (HD+)     | 38        | 2.75%   |
| 2880x1800          | 26        | 1.88%   |
| 3440x1440          | 23        | 1.66%   |
| 3840x2400          | 17        | 1.23%   |
| 1280x800 (WXGA)    | 13        | 0.94%   |
| 2160x1440          | 10        | 0.72%   |
| 2560x1080          | 9         | 0.65%   |
| 2256x1504          | 8         | 0.58%   |
| 1440x900 (WXGA+)   | 8         | 0.58%   |
| 3000x2000          | 7         | 0.51%   |
| 2520x1680          | 6         | 0.43%   |
| 1680x1050 (WSXGA+) | 5         | 0.36%   |
| 1280x1024 (SXGA)   | 5         | 0.36%   |
| 3456x2160          | 4         | 0.29%   |
| 1360x768           | 4         | 0.29%   |
| 3840x1080          | 3         | 0.22%   |
| 3200x2000          | 3         | 0.22%   |
| 3200x1800 (QHD+)   | 3         | 0.22%   |
| 1920x1280          | 3         | 0.22%   |
| 3072x1920          | 2         | 0.14%   |
| 2240x1400          | 2         | 0.14%   |
| 2160x1350          | 2         | 0.14%   |
| 1024x768 (XGA)     | 2         | 0.14%   |
| 800x1280           | 1         | 0.07%   |
| 3840x1600          | 1         | 0.07%   |
| 2880x864           | 1         | 0.07%   |
| 2880x1620          | 1         | 0.07%   |
| 2304x1440          | 1         | 0.07%   |
| 2288x1287          | 1         | 0.07%   |
| 1920x540           | 1         | 0.07%   |
| 1680x945           | 1         | 0.07%   |
| 1024x600           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 571       | 37.97%  |
| 13      | 234       | 15.56%  |
| 14      | 206       | 13.7%   |
| 27      | 73        | 4.85%   |
| 24      | 64        | 4.26%   |
| 17      | 64        | 4.26%   |
| 16      | 58        | 3.86%   |
| 23      | 38        | 2.53%   |
| 12      | 32        | 2.13%   |
| 21      | 29        | 1.93%   |
| 34      | 26        | 1.73%   |
| 31      | 14        | 0.93%   |
| 11      | 12        | 0.8%    |
| 40      | 10        | 0.66%   |
| 18      | 10        | 0.66%   |
| 19      | 7         | 0.47%   |
| 84      | 5         | 0.33%   |
| 25      | 5         | 0.33%   |
| Unknown | 5         | 0.33%   |
| 72      | 4         | 0.27%   |
| 32      | 4         | 0.27%   |
| 29      | 4         | 0.27%   |
| 28      | 4         | 0.27%   |
| 20      | 4         | 0.27%   |
| 86      | 3         | 0.2%    |
| 48      | 3         | 0.2%    |
| 54      | 2         | 0.13%   |
| 35      | 2         | 0.13%   |
| 142     | 1         | 0.07%   |
| 74      | 1         | 0.07%   |
| 69      | 1         | 0.07%   |
| 47      | 1         | 0.07%   |
| 39      | 1         | 0.07%   |
| 38      | 1         | 0.07%   |
| 37      | 1         | 0.07%   |
| 26      | 1         | 0.07%   |
| 22      | 1         | 0.07%   |
| 10      | 1         | 0.07%   |
| 7       | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 935       | 62.88%  |
| 501-600        | 163       | 10.96%  |
| 201-300        | 157       | 10.56%  |
| 351-400        | 85        | 5.72%   |
| 401-500        | 47        | 3.16%   |
| 701-800        | 30        | 2.02%   |
| 601-700        | 28        | 1.88%   |
| 801-900        | 14        | 0.94%   |
| 1501-2000      | 11        | 0.74%   |
| 1001-1500      | 9         | 0.61%   |
| Unknown        | 5         | 0.34%   |
| More than 2000 | 1         | 0.07%   |
| 901-1000       | 1         | 0.07%   |
| 1-100          | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1021      | 79.15%  |
| 16/10   | 181       | 14.03%  |
| 3/2     | 35        | 2.71%   |
| 21/9    | 32        | 2.48%   |
| 4/3     | 6         | 0.47%   |
| 5/4     | 5         | 0.39%   |
| 32/9    | 3         | 0.23%   |
| 0.56    | 3         | 0.23%   |
| 3.33    | 1         | 0.08%   |
| 1.00    | 1         | 0.08%   |
| 0.67    | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 579       | 38.6%   |
| 81-90          | 353       | 23.53%  |
| 201-250        | 103       | 6.87%   |
| 71-80          | 84        | 5.6%    |
| 301-350        | 74        | 4.93%   |
| 121-130        | 59        | 3.93%   |
| 351-500        | 52        | 3.47%   |
| 111-120        | 48        | 3.2%    |
| 61-70          | 28        | 1.87%   |
| 251-300        | 24        | 1.6%    |
| 151-200        | 22        | 1.47%   |
| More than 1000 | 17        | 1.13%   |
| 501-1000       | 17        | 1.13%   |
| 51-60          | 12        | 0.8%    |
| 91-100         | 9         | 0.6%    |
| 141-150        | 8         | 0.53%   |
| Unknown        | 5         | 0.33%   |
| 131-140        | 4         | 0.27%   |
| 41-50          | 1         | 0.07%   |
| 1-40           | 1         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 700       | 47.75%  |
| 101-120       | 249       | 16.98%  |
| 51-100        | 211       | 14.39%  |
| 161-240       | 200       | 13.64%  |
| More than 240 | 88        | 6%      |
| 1-50          | 13        | 0.89%   |
| Unknown       | 5         | 0.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 933       | 73.7%   |
| 2     | 265       | 20.93%  |
| 3     | 33        | 2.61%   |
| 0     | 30        | 2.37%   |
| 4     | 3         | 0.24%   |
| 5     | 2         | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 758       | 41.65%  |
| Realtek Semiconductor                  | 625       | 34.34%  |
| Qualcomm Atheros                       | 148       | 8.13%   |
| MediaTek                               | 85        | 4.67%   |
| Broadcom                               | 54        | 2.97%   |
| Qualcomm                               | 19        | 1.04%   |
| Lenovo                                 | 19        | 1.04%   |
| ASIX Electronics                       | 12        | 0.66%   |
| Xiaomi                                 | 9         | 0.49%   |
| Broadcom Limited                       | 9         | 0.49%   |
| Sierra Wireless                        | 8         | 0.44%   |
| Dell                                   | 8         | 0.44%   |
| TP-Link                                | 7         | 0.38%   |
| Samsung Electronics                    | 7         | 0.38%   |
| DisplayLink                            | 7         | 0.38%   |
| Hewlett-Packard                        | 6         | 0.33%   |
| Ralink                                 | 5         | 0.27%   |
| Ralink Technology                      | 4         | 0.22%   |
| ASUSTek Computer                       | 4         | 0.22%   |
| Marvell Technology Group               | 3         | 0.16%   |
| Google                                 | 3         | 0.16%   |
| Ericsson Business Mobile Networks      | 3         | 0.16%   |
| Huawei Technologies                    | 2         | 0.11%   |
| Fibocom                                | 2         | 0.11%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.05%   |
| T & A Mobile Phones                    | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| OPPO Electronics                       | 1         | 0.05%   |
| Microsoft                              | 1         | 0.05%   |
| Linksys                                | 1         | 0.05%   |
| JMicron Technology                     | 1         | 0.05%   |
| D-Link System                          | 1         | 0.05%   |
| D-Link                                 | 1         | 0.05%   |
| Arduino SA                             | 1         | 0.05%   |
| Aquantia                               | 1         | 0.05%   |
| Apple                                  | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 373       | 17.05%  |
| Intel Wi-Fi 6 AX201                                               | 100       | 4.57%   |
| Intel Wi-Fi 6 AX200                                               | 87        | 3.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 84        | 3.84%   |
| Intel Wireless 8265 / 8275                                        | 75        | 3.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 66        | 3.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 62        | 2.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 60        | 2.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 60        | 2.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 41        | 1.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 38        | 1.74%   |
| Intel Wireless 8260                                               | 36        | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 36        | 1.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 33        | 1.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 32        | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 32        | 1.46%   |
| Intel Wireless 7265                                               | 31        | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 29        | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 27        | 1.23%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 25        | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 25        | 1.14%   |
| Intel Wireless 7260                                               | 24        | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 1.01%   |
| Intel Ethernet Connection I219-LM                                 | 19        | 0.87%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 18        | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 17        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 17        | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 17        | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16        | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 15        | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 0.64%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 14        | 0.64%   |
| Intel Ethernet Connection (16) I219-V                             | 13        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.55%   |
| Broadcom BCM43142 802.11b/g/n                                     | 12        | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 0.55%   |
| Intel Ethernet Connection (6) I219-LM                             | 11        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 742       | 58.52%  |
| Realtek Semiconductor                 | 204       | 16.09%  |
| Qualcomm Atheros                      | 124       | 9.78%   |
| MediaTek                              | 83        | 6.55%   |
| Broadcom                              | 46        | 3.63%   |
| Qualcomm                              | 16        | 1.26%   |
| Broadcom Limited                      | 9         | 0.71%   |
| Sierra Wireless                       | 8         | 0.63%   |
| Dell                                  | 7         | 0.55%   |
| TP-Link                               | 5         | 0.39%   |
| Ralink                                | 5         | 0.39%   |
| Ralink Technology                     | 4         | 0.32%   |
| Hewlett-Packard                       | 4         | 0.32%   |
| ASUSTek Computer                      | 4         | 0.32%   |
| Fibocom                               | 2         | 0.16%   |
| Linksys                               | 1         | 0.08%   |
| Ericsson Business Mobile Networks     | 1         | 0.08%   |
| D-Link System                         | 1         | 0.08%   |
| D-Link                                | 1         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 100       | 7.88%   |
| Intel Wi-Fi 6 AX200                                            | 87        | 6.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 84        | 6.62%   |
| Intel Wireless 8265 / 8275                                     | 75        | 5.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 62        | 4.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 60        | 4.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 41        | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 38        | 2.99%   |
| Intel Wireless 8260                                            | 36        | 2.84%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 36        | 2.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 33        | 2.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 32        | 2.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 32        | 2.52%   |
| Intel Wireless 7265                                            | 31        | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 29        | 2.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 27        | 2.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 25        | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 25        | 1.97%   |
| Intel Wireless 7260                                            | 24        | 1.89%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 17        | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 17        | 1.34%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 17        | 1.34%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 17        | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 1.26%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 15        | 1.18%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 14        | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 13        | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 0.95%   |
| Intel Centrino Ultimate-N 6300                                 | 11        | 0.87%   |
| Intel Wireless-AC 9260                                         | 10        | 0.79%   |
| Intel Wireless 3160                                            | 10        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 0.63%   |
| Intel Wireless 3165                                            | 8         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 0.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 0.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 5         | 0.39%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 5         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 530       | 59.09%  |
| Intel                                  | 243       | 27.09%  |
| Qualcomm Atheros                       | 31        | 3.46%   |
| Lenovo                                 | 18        | 2.01%   |
| Broadcom                               | 18        | 2.01%   |
| ASIX Electronics                       | 12        | 1.34%   |
| Xiaomi                                 | 9         | 1%      |
| DisplayLink                            | 7         | 0.78%   |
| Samsung Electronics                    | 6         | 0.67%   |
| Qualcomm                               | 3         | 0.33%   |
| Marvell Technology Group               | 3         | 0.33%   |
| Google                                 | 3         | 0.33%   |
| TP-Link                                | 2         | 0.22%   |
| MediaTek                               | 2         | 0.22%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.11%   |
| T & A Mobile Phones                    | 1         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.11%   |
| OPPO Electronics                       | 1         | 0.11%   |
| Microsoft                              | 1         | 0.11%   |
| JMicron Technology                     | 1         | 0.11%   |
| Huawei Technologies                    | 1         | 0.11%   |
| Hewlett-Packard                        | 1         | 0.11%   |
| Aquantia                               | 1         | 0.11%   |
| Apple                                  | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 373       | 40.99%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 66        | 7.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 60        | 6.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 3.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 2.42%   |
| Intel Ethernet Connection I219-LM                                 | 19        | 2.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 1.54%   |
| Intel Ethernet Connection (16) I219-V                             | 13        | 1.43%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 1.32%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 1.32%   |
| Intel Ethernet Connection (6) I219-LM                             | 11        | 1.21%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 1.21%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 1.21%   |
| Intel Ethernet Connection (10) I219-V                             | 10        | 1.1%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 9         | 0.99%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 9         | 0.99%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 8         | 0.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.88%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 7         | 0.77%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.66%   |
| Realtek Killer E3000 2.5GbE Controller                            | 6         | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 0.66%   |
| Intel Ethernet Connection (10) I219-LM                            | 6         | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.66%   |
| Lenovo USB-C Dock Ethernet                                        | 5         | 0.55%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.55%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.55%   |
| Intel Ethernet Connection (11) I219-LM                            | 5         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.44%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.44%   |
| Intel Ethernet Connection (16) I219-LM                            | 4         | 0.44%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.44%   |
| Realtek PCIe GbE Family Controller                                | 3         | 0.33%   |
| Qualcomm Redmi 9T                                                 | 3         | 0.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1221      | 58.96%  |
| Ethernet | 841       | 40.61%  |
| Modem    | 8         | 0.39%   |
| Unknown  | 1         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1065      | 81.92%  |
| Ethernet | 235       | 18.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 735       | 59.27%  |
| 1     | 466       | 37.58%  |
| 0     | 20        | 1.61%   |
| 3     | 19        | 1.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 930       | 74.34%  |
| Yes  | 321       | 25.66%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 652       | 60.15%  |
| Realtek Semiconductor           | 124       | 11.44%  |
| Qualcomm Atheros Communications | 62        | 5.72%   |
| Foxconn / Hon Hai               | 57        | 5.26%   |
| IMC Networks                    | 54        | 4.98%   |
| Lite-On Technology              | 40        | 3.69%   |
| Broadcom                        | 23        | 2.12%   |
| Realtek                         | 19        | 1.75%   |
| Apple                           | 17        | 1.57%   |
| Dell                            | 5         | 0.46%   |
| USI                             | 4         | 0.37%   |
| Toshiba                         | 4         | 0.37%   |
| Opticis                         | 4         | 0.37%   |
| MediaTek                        | 4         | 0.37%   |
| Hewlett-Packard                 | 4         | 0.37%   |
| Cambridge Silicon Radio         | 3         | 0.28%   |
| Ralink                          | 2         | 0.18%   |
| ASUSTek Computer                | 2         | 0.18%   |
| Foxconn International           | 1         | 0.09%   |
| Corsair                         | 1         | 0.09%   |
| Chicony Electronics             | 1         | 0.09%   |
| Alps Electric                   | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 180       | 16.61%  |
| Intel Bluetooth wireless interface                  | 161       | 14.85%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 104       | 9.59%   |
| Intel AX200 Bluetooth                               | 85        | 7.84%   |
| Realtek Bluetooth Radio                             | 81        | 7.47%   |
| Intel Bluetooth Device                              | 61        | 5.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 40        | 3.69%   |
| Intel AX210 Bluetooth                               | 32        | 2.95%   |
| IMC Networks Wireless_Device                        | 29        | 2.68%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 24        | 2.21%   |
| Realtek 802.11ac WLAN Adapter                       | 20        | 1.85%   |
| Realtek 802.11ac WLAN Adapter                       | 19        | 1.75%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 1.66%   |
| IMC Networks Bluetooth Radio                        | 14        | 1.29%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 1.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 1.11%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 1.11%   |
| Lite-On Bluetooth Device                            | 11        | 1.01%   |
| Foxconn / Hon Hai Wireless_Device                   | 11        | 1.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 0.92%   |
| Apple Bluetooth Host Controller                     | 10        | 0.92%   |
| Lite-On Wireless_Device                             | 9         | 0.83%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 0.65%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 0.65%   |
| IMC Networks Bluetooth Device                       | 7         | 0.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.55%   |
| Apple Bluetooth USB Host Controller                 | 5         | 0.46%   |
| USI Bluetooth Device                                | 4         | 0.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.37%   |
| Opticis Bluetooth Radio                             | 4         | 0.37%   |
| MediaTek Wireless_Device                            | 4         | 0.37%   |
| Lite-On Bluetooth Radio                             | 4         | 0.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.28%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.28%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 0.28%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.28%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.28%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.28%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 0.28%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 3         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 902       | 56.84%  |
| AMD                                  | 325       | 20.48%  |
| Nvidia                               | 213       | 13.42%  |
| Lenovo                               | 21        | 1.32%   |
| Logitech                             | 15        | 0.95%   |
| C-Media Electronics                  | 15        | 0.95%   |
| GN Netcom                            | 11        | 0.69%   |
| Realtek Semiconductor                | 9         | 0.57%   |
| Plantronics                          | 8         | 0.5%    |
| Hewlett-Packard                      | 6         | 0.38%   |
| Kingston Technology                  | 5         | 0.32%   |
| JMTek                                | 4         | 0.25%   |
| ASUSTek Computer                     | 4         | 0.25%   |
| Samsung Electronics                  | 3         | 0.19%   |
| Razer USA                            | 3         | 0.19%   |
| Creative Technology                  | 3         | 0.19%   |
| Corsair                              | 3         | 0.19%   |
| Blue Microphones                     | 3         | 0.19%   |
| SteelSeries ApS                      | 2         | 0.13%   |
| RODE Microphones                     | 2         | 0.13%   |
| No brand                             | 2         | 0.13%   |
| Generalplus Technology               | 2         | 0.13%   |
| Focusrite-Novation                   | 2         | 0.13%   |
| Dell                                 | 2         | 0.13%   |
| Asahi Kasei Microsystems             | 2         | 0.13%   |
| Apple                                | 2         | 0.13%   |
| Yamaha                               | 1         | 0.06%   |
| Unknown                              | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.06%   |
| Samson Technologies                  | 1         | 0.06%   |
| Quanta                               | 1         | 0.06%   |
| Power Delivery                       | 1         | 0.06%   |
| Native Instruments                   | 1         | 0.06%   |
| Microsoft                            | 1         | 0.06%   |
| Microchip Technology                 | 1         | 0.06%   |
| Micro Star International             | 1         | 0.06%   |
| M-Audio                              | 1         | 0.06%   |
| Huawei Technologies                  | 1         | 0.06%   |
| Google                               | 1         | 0.06%   |
| Fujitsu                              | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 278       | 14.23%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 182       | 9.32%   |
| Intel Sunrise Point-LP HD Audio                                            | 167       | 8.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 121       | 6.2%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 105       | 5.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 56        | 2.87%   |
| Intel Comet Lake PCH-LP cAVS                                               | 54        | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 52        | 2.66%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 49        | 2.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 46        | 2.36%   |
| Intel Comet Lake PCH cAVS                                                  | 43        | 2.2%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 36        | 1.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 34        | 1.74%   |
| Nvidia GA106 High Definition Audio Controller                              | 34        | 1.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 29        | 1.48%   |
| Intel Broadwell-U Audio Controller                                         | 29        | 1.48%   |
| Nvidia Audio device                                                        | 26        | 1.33%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 25        | 1.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 24        | 1.23%   |
| Intel 8 Series HD Audio Controller                                         | 24        | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 23        | 1.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 23        | 1.18%   |
| Nvidia TU106 High Definition Audio Controller                              | 21        | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21        | 1.08%   |
| Intel CM238 HD Audio Controller                                            | 20        | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20        | 1.02%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 19        | 0.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17        | 0.87%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 14        | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                              | 13        | 0.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 12        | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 11        | 0.56%   |
| AMD Kabini HDMI/DP Audio                                                   | 11        | 0.56%   |
| AMD FCH Azalia Controller                                                  | 11        | 0.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 0.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 10        | 0.51%   |
| Realtek Semiconductor USB Audio                                            | 9         | 0.46%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9         | 0.46%   |
| Nvidia GF108 High Definition Audio Controller                              | 9         | 0.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 246       | 30.56%  |
| SK hynix            | 188       | 23.35%  |
| Micron Technology   | 127       | 15.78%  |
| Crucial             | 48        | 5.96%   |
| Kingston            | 43        | 5.34%   |
| Unknown             | 34        | 4.22%   |
| A-DATA Technology   | 20        | 2.48%   |
| Ramaxel Technology  | 14        | 1.74%   |
| Corsair             | 12        | 1.49%   |
| Team                | 8         | 0.99%   |
| G.Skill             | 7         | 0.87%   |
| Elpida              | 7         | 0.87%   |
| Unknown             | 7         | 0.87%   |
| Smart               | 5         | 0.62%   |
| Unknown (ABCD)      | 3         | 0.37%   |
| Transcend           | 3         | 0.37%   |
| Patriot             | 3         | 0.37%   |
| Smart Brazil        | 2         | 0.25%   |
| PUSKILL             | 2         | 0.25%   |
| Nanya Technology    | 2         | 0.25%   |
| Goldkey             | 2         | 0.25%   |
| Avant               | 2         | 0.25%   |
| Wilk                | 1         | 0.12%   |
| V-Color             | 1         | 0.12%   |
| Unknown (F288)      | 1         | 0.12%   |
| Unknown (0x0B5E)    | 1         | 0.12%   |
| Unknown (08C8)      | 1         | 0.12%   |
| Timetec             | 1         | 0.12%   |
| Teikon              | 1         | 0.12%   |
| Silicon Power       | 1         | 0.12%   |
| Qumo                | 1         | 0.12%   |
| PNY                 | 1         | 0.12%   |
| Miron               | 1         | 0.12%   |
| Lexar Co Limited    | 1         | 0.12%   |
| Lexar               | 1         | 0.12%   |
| Kllisre             | 1         | 0.12%   |
| High Bridge         | 1         | 0.12%   |
| Hewlett-Packard     | 1         | 0.12%   |
| GOODRAM             | 1         | 0.12%   |
| Foxline             | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.77%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 1.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 1.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 1.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 1.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 12        | 1.41%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.3%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 10        | 1.18%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.94%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.82%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 7         | 0.82%   |
| Unknown                                                          | 7         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 6         | 0.71%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 6         | 0.71%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 6         | 0.71%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 6         | 0.71%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.71%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 6         | 0.71%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 5         | 0.59%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.59%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.59%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 5         | 0.59%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.59%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.59%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.59%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 5         | 0.59%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 5         | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.47%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.47%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 4         | 0.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.47%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.47%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 4         | 0.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.47%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 4         | 0.47%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 431       | 63.85%  |
| DDR3   | 102       | 15.11%  |
| LPDDR4 | 45        | 6.67%   |
| LPDDR5 | 37        | 5.48%   |
| LPDDR3 | 26        | 3.85%   |
| DDR5   | 25        | 3.7%    |
| DDR2   | 8         | 1.19%   |
| SDRAM  | 1         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 549       | 79.45%  |
| Row Of Chips | 131       | 18.96%  |
| Unknown      | 7         | 1.01%   |
| Chip         | 3         | 0.43%   |
| DIMM         | 1         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 352       | 47.83%  |
| 16384 | 150       | 20.38%  |
| 4096  | 130       | 17.66%  |
| 2048  | 53        | 7.2%    |
| 32768 | 44        | 5.98%   |
| 1024  | 6         | 0.82%   |
| 12288 | 1         | 0.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 265       | 36.75%  |
| 2667    | 149       | 20.67%  |
| 1600    | 72        | 9.99%   |
| 2133    | 41        | 5.69%   |
| 6400    | 36        | 4.99%   |
| 2400    | 35        | 4.85%   |
| 4800    | 24        | 3.33%   |
| 4267    | 21        | 2.91%   |
| 1333    | 16        | 2.22%   |
| 1867    | 12        | 1.66%   |
| 4266    | 10        | 1.39%   |
| 3266    | 7         | 0.97%   |
| 8400    | 5         | 0.69%   |
| 3733    | 4         | 0.55%   |
| 1334    | 4         | 0.55%   |
| 1066    | 3         | 0.42%   |
| 800     | 3         | 0.42%   |
| 667     | 3         | 0.42%   |
| Unknown | 3         | 0.42%   |
| 5600    | 1         | 0.14%   |
| 5500    | 1         | 0.14%   |
| 2048    | 1         | 0.14%   |
| 1866    | 1         | 0.14%   |
| 1067    | 1         | 0.14%   |
| 975     | 1         | 0.14%   |
| 933     | 1         | 0.14%   |
| 533     | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 50%     |
| MiiiW              | 1         | 25%     |
| Hewlett-Packard    | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| MiiiW MW USB Receiver    | 1         | 25%     |
| HP Officejet 2620 series | 1         | 25%     |
| Brother DCP-7025 Printer | 1         | 25%     |
| Brother DCP-1600         | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 285       | 24.91%  |
| IMC Networks                           | 167       | 14.6%   |
| Microdia                               | 105       | 9.18%   |
| Quanta                                 | 103       | 9%      |
| Bison Electronics                      | 95        | 8.3%    |
| Realtek Semiconductor                  | 62        | 5.42%   |
| Sunplus Innovation Technology          | 50        | 4.37%   |
| Cheng Uei Precision Industry (Foxlink) | 41        | 3.58%   |
| Luxvisions Innotech Limited            | 39        | 3.41%   |
| Syntek                                 | 35        | 3.06%   |
| Logitech                               | 27        | 2.36%   |
| Lite-On Technology                     | 23        | 2.01%   |
| Sonix Technology                       | 20        | 1.75%   |
| Apple                                  | 13        | 1.14%   |
| Silicon Motion                         | 11        | 0.96%   |
| Suyin                                  | 9         | 0.79%   |
| Acer                                   | 8         | 0.7%    |
| SunplusIT                              | 5         | 0.44%   |
| Alcor Micro                            | 5         | 0.44%   |
| Tripath Technology                     | 3         | 0.26%   |
| Samsung Electronics                    | 3         | 0.26%   |
| Primax Electronics                     | 3         | 0.26%   |
| Microsoft                              | 3         | 0.26%   |
| Ricoh                                  | 2         | 0.17%   |
| MacroSilicon                           | 2         | 0.17%   |
| Lenovo                                 | 2         | 0.17%   |
| kingcome                               | 2         | 0.17%   |
| Importek                               | 2         | 0.17%   |
| icSpring                               | 2         | 0.17%   |
| Generalplus Technology                 | 2         | 0.17%   |
| AVerMedia Technologies                 | 2         | 0.17%   |
| Y Media                                | 1         | 0.09%   |
| Xiongmai                               | 1         | 0.09%   |
| WaveRider Communications               | 1         | 0.09%   |
| ValueHD                                | 1         | 0.09%   |
| USB Camera CS                          | 1         | 0.09%   |
| Tobii Technology AB                    | 1         | 0.09%   |
| Novatek Microelectronics               | 1         | 0.09%   |
| Jieli Technology                       | 1         | 0.09%   |
| Hewlett-Packard                        | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 102       | 8.85%   |
| Microdia Integrated_Webcam_HD                       | 61        | 5.3%    |
| IMC Networks Integrated Camera                      | 53        | 4.6%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 52        | 4.51%   |
| Bison Integrated Camera                             | 39        | 3.39%   |
| Realtek Integrated_Webcam_HD                        | 32        | 2.78%   |
| Chicony HD Webcam                                   | 25        | 2.17%   |
| Syntek Integrated Camera                            | 24        | 2.08%   |
| Quanta HD User Facing                               | 22        | 1.91%   |
| Sunplus Integrated_Webcam_HD                        | 19        | 1.65%   |
| IMC Networks HD Camera                              | 19        | 1.65%   |
| Quanta HP Wide Vision HD Camera                     | 17        | 1.48%   |
| Quanta HP HD Camera                                 | 15        | 1.3%    |
| Microdia Integrated_Webcam_FHD                      | 14        | 1.22%   |
| Sonix USB2.0 HD UVC WebCam                          | 13        | 1.13%   |
| Chicony Integrated Camera (1280x720@30)             | 13        | 1.13%   |
| Chicony HP TrueVision HD Camera                     | 12        | 1.04%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 11        | 0.95%   |
| Bison SunplusIT Integrated Camera                   | 10        | 0.87%   |
| Quanta HP TrueVision HD Camera                      | 9         | 0.78%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 9         | 0.78%   |
| Luxvisions Innotech Limited Integrated Camera       | 9         | 0.78%   |
| Lite-On Integrated Camera                           | 9         | 0.78%   |
| IMC Networks ov9734_azurewave_camera                | 9         | 0.78%   |
| Chicony USB2.0 VGA UVC WebCam                       | 9         | 0.78%   |
| Chicony HP HD Camera                                | 9         | 0.78%   |
| Chicony HD User Facing                              | 9         | 0.78%   |
| Bison HD Webcam                                     | 9         | 0.78%   |
| Lite-On HP HD Camera                                | 8         | 0.69%   |
| Chicony HP Wide Vision HD Camera                    | 8         | 0.69%   |
| Chicony EasyCamera                                  | 8         | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 8         | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 8         | 0.69%   |
| Chicony USB2.0 Camera                               | 7         | 0.61%   |
| Chicony TOSHIBA Web Camera - HD                     | 7         | 0.61%   |
| Chicony FJ Camera                                   | 7         | 0.61%   |
| Bison HD Camera                                     | 7         | 0.61%   |
| Syntek Lenovo EasyCamera                            | 6         | 0.52%   |
| Realtek USB Camera                                  | 6         | 0.52%   |
| Quanta VGA WebCam                                   | 6         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 111       | 39.78%  |
| Shenzhen Goodix Technology         | 72        | 25.81%  |
| Validity Sensors                   | 59        | 21.15%  |
| Elan Microelectronics              | 19        | 6.81%   |
| LighTuning Technology              | 6         | 2.15%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 1.43%   |
| AuthenTec                          | 4         | 1.43%   |
| Upek                               | 2         | 0.72%   |
| STMicroelectronics                 | 1         | 0.36%   |
| Samsung Electronics                | 1         | 0.36%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 58        | 20.79%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 54        | 19.35%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 20        | 7.17%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 4.66%   |
| Elan ELAN:ARM-M4                                                           | 12        | 4.3%    |
| Validity Sensors Synaptics WBDI                                            | 11        | 3.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 3.58%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 3.58%   |
| Shenzhen Goodix FingerPrint                                                | 8         | 2.87%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.51%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.15%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 2.15%   |
| Synaptics UWP WBDI Device                                                  | 6         | 2.15%   |
| Synaptics  WBDI                                                            | 6         | 2.15%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 2.15%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.79%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.43%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.43%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 1.43%   |
| Validity Sensors VFS491                                                    | 3         | 1.08%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 1.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.08%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.72%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 0.72%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 0.72%   |
| AuthenTec AES2810                                                          | 2         | 0.72%   |
| AuthenTec AES1600                                                          | 2         | 0.72%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.36%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.36%   |
| Synaptics WBDI Device                                                      | 1         | 0.36%   |
| Synaptics WBDI                                                             | 1         | 0.36%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.36%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.36%   |
| Samsung Fingerprint Device                                                 | 1         | 0.36%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 48        | 43.64%  |
| Broadcom              | 45        | 40.91%  |
| Upek                  | 6         | 5.45%   |
| O2 Micro              | 3         | 2.73%   |
| Lenovo                | 3         | 2.73%   |
| Gemalto (was Gemplus) | 3         | 2.73%   |
| Yubico.com            | 1         | 0.91%   |
| Purism, SPC           | 1         | 0.91%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 48        | 43.64%  |
| Broadcom 5880                                                                | 19        | 17.27%  |
| Broadcom 58200                                                               | 17        | 15.45%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 6.36%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 5.45%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.73%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 2.73%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.82%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 1.82%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.91%   |
| Purism, SPC Librem Key                                                       | 1         | 0.91%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 0.91%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 735       | 58.43%  |
| 1     | 438       | 34.82%  |
| 2     | 69        | 5.48%   |
| 3     | 5         | 0.4%    |
| 7     | 4         | 0.32%   |
| 5     | 4         | 0.32%   |
| 4     | 3         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 276       | 43.88%  |
| Graphics card            | 150       | 23.85%  |
| Multimedia controller    | 68        | 10.81%  |
| Net/wireless             | 37        | 5.88%   |
| Camera                   | 30        | 4.77%   |
| Chipcard                 | 22        | 3.5%    |
| Card reader              | 12        | 1.91%   |
| Sound                    | 11        | 1.75%   |
| Bluetooth                | 11        | 1.75%   |
| Communication controller | 4         | 0.64%   |
| Storage                  | 3         | 0.48%   |
| Net/ethernet             | 3         | 0.48%   |
| Network                  | 1         | 0.16%   |
| Firewire controller      | 1         | 0.16%   |

