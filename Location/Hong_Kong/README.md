Linux in Hong Kong - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Hong Kong.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Hong_Kong/Desktop/README.md) and [notebooks](/Location/Hong_Kong/Notebook/README.md).

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

Total: 471

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [ecf944f539](https://linux-hardware.org/?probe=ecf944f539) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [0031785936](https://linux-hardware.org/?probe=0031785936) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [4bd2096c80](https://linux-hardware.org/?probe=4bd2096c80) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [7b3c89637b](https://linux-hardware.org/?probe=7b3c89637b) | Dec 30, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [2154a332b0](https://linux-hardware.org/?probe=2154a332b0) | Dec 29, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [8a5b919c91](https://linux-hardware.org/?probe=8a5b919c91) | Dec 24, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [641b77c3da](https://linux-hardware.org/?probe=641b77c3da) | Dec 20, 2022 |
| GPD           | P2 MAX                      | Notebook    | [de5983ec37](https://linux-hardware.org/?probe=de5983ec37) | Dec 17, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | Notebook    | [8d631bb590](https://linux-hardware.org/?probe=8d631bb590) | Dec 17, 2022 |
| Dell          | Inspiron 7590               | Notebook    | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| GPD           | P2 MAX                      | Notebook    | [63c199f475](https://linux-hardware.org/?probe=63c199f475) | Dec 08, 2022 |
| Lenovo        | ThinkSystem SR358FV2 Res... | Server      | [3702b80721](https://linux-hardware.org/?probe=3702b80721) | Dec 07, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [706e40ed5a](https://linux-hardware.org/?probe=706e40ed5a) | Dec 04, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | Desktop     | [5476b73cb7](https://linux-hardware.org/?probe=5476b73cb7) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | Desktop     | [6d07106192](https://linux-hardware.org/?probe=6d07106192) | Dec 02, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [aff020417f](https://linux-hardware.org/?probe=aff020417f) | Dec 01, 2022 |
| Dell          | Latitude 7390               | Notebook    | [7214cac96d](https://linux-hardware.org/?probe=7214cac96d) | Nov 30, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [7b0cf2fa20](https://linux-hardware.org/?probe=7b0cf2fa20) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20A... | Convertible | [341287988f](https://linux-hardware.org/?probe=341287988f) | Nov 17, 2022 |
| GPD           | G1619-04                    | Notebook    | [ce6d16840e](https://linux-hardware.org/?probe=ce6d16840e) | Nov 07, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [468f8df590](https://linux-hardware.org/?probe=468f8df590) | Nov 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [895a345eb9](https://linux-hardware.org/?probe=895a345eb9) | Nov 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9d9d3a4967](https://linux-hardware.org/?probe=9d9d3a4967) | Nov 02, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| ASRock        | H470M-STX                   | Desktop     | [02f3177542](https://linux-hardware.org/?probe=02f3177542) | Oct 26, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [ce7a9a3171](https://linux-hardware.org/?probe=ce7a9a3171) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [a9c49ccd5d](https://linux-hardware.org/?probe=a9c49ccd5d) | Oct 21, 2022 |
| Lenovo        | ThinkPad T470 20HD002TCD    | Notebook    | [0b0ca5a5f6](https://linux-hardware.org/?probe=0b0ca5a5f6) | Oct 20, 2022 |
| HP            | 8956 010                    | Mini pc     | [d959cdb332](https://linux-hardware.org/?probe=d959cdb332) | Oct 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8ebbbf93e4](https://linux-hardware.org/?probe=8ebbbf93e4) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [7d3c652547](https://linux-hardware.org/?probe=7d3c652547) | Oct 11, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6207d55486](https://linux-hardware.org/?probe=6207d55486) | Oct 05, 2022 |
| HP            | ZHAN 66 Pro A 14 inch G5... | Notebook    | [c5587dbec5](https://linux-hardware.org/?probe=c5587dbec5) | Oct 04, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [2163cddbe4](https://linux-hardware.org/?probe=2163cddbe4) | Oct 04, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| Fujitsu       | FMVNU6G1C                   | Notebook    | [1351f25388](https://linux-hardware.org/?probe=1351f25388) | Sep 30, 2022 |
| HP            | 18E7                        | Desktop     | [132a87f746](https://linux-hardware.org/?probe=132a87f746) | Sep 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [7c8030e423](https://linux-hardware.org/?probe=7c8030e423) | Sep 26, 2022 |
| Dell          | Latitude E5250              | Notebook    | [e4ffe3583d](https://linux-hardware.org/?probe=e4ffe3583d) | Sep 26, 2022 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [e939330716](https://linux-hardware.org/?probe=e939330716) | Sep 25, 2022 |
| Unknown       | Apple iPad Pro (9.7-inch... | Desktop     | [822d20fcdb](https://linux-hardware.org/?probe=822d20fcdb) | Sep 25, 2022 |
| Unknown       | Apple iPad Pro (9.7-inch... | Desktop     | [92f244ac1c](https://linux-hardware.org/?probe=92f244ac1c) | Sep 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [7e4f539e70](https://linux-hardware.org/?probe=7e4f539e70) | Sep 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [64cd74457e](https://linux-hardware.org/?probe=64cd74457e) | Sep 24, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [89a019875a](https://linux-hardware.org/?probe=89a019875a) | Sep 24, 2022 |
| ASRock        | Z490 PG Velocita            | Desktop     | [eac045585b](https://linux-hardware.org/?probe=eac045585b) | Sep 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [76be3ff1db](https://linux-hardware.org/?probe=76be3ff1db) | Sep 22, 2022 |
| Huanan        | X99-TF                      | Desktop     | [657d78e891](https://linux-hardware.org/?probe=657d78e891) | Sep 21, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [3759658825](https://linux-hardware.org/?probe=3759658825) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f454a8f6a5](https://linux-hardware.org/?probe=f454a8f6a5) | Sep 19, 2022 |
| HUAWEI        | PGU-WBY0                    | Soc         | [3f3d475864](https://linux-hardware.org/?probe=3f3d475864) | Sep 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [5160feeaf2](https://linux-hardware.org/?probe=5160feeaf2) | Sep 13, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [876e87c7b6](https://linux-hardware.org/?probe=876e87c7b6) | Sep 13, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [1d95c5b6ef](https://linux-hardware.org/?probe=1d95c5b6ef) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4562797ebc](https://linux-hardware.org/?probe=4562797ebc) | Sep 08, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [32ab96441e](https://linux-hardware.org/?probe=32ab96441e) | Sep 08, 2022 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | Notebook    | [d0ddfb5815](https://linux-hardware.org/?probe=d0ddfb5815) | Sep 07, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [302c3f11ec](https://linux-hardware.org/?probe=302c3f11ec) | Aug 29, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [9a83e7ee58](https://linux-hardware.org/?probe=9a83e7ee58) | Aug 28, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [638f08fc43](https://linux-hardware.org/?probe=638f08fc43) | Aug 27, 2022 |
| Dell          | 0427JK A00                  | Desktop     | [8f6a2c8d0b](https://linux-hardware.org/?probe=8f6a2c8d0b) | Aug 22, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [90aed4d5d1](https://linux-hardware.org/?probe=90aed4d5d1) | Aug 20, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [58b22885a8](https://linux-hardware.org/?probe=58b22885a8) | Aug 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c32d69a956](https://linux-hardware.org/?probe=c32d69a956) | Aug 18, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [bd7c6f361d](https://linux-hardware.org/?probe=bd7c6f361d) | Aug 18, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [56ba58f5d0](https://linux-hardware.org/?probe=56ba58f5d0) | Aug 16, 2022 |
| Lenovo        | ThinkPad T490s 20NYS79X0... | Notebook    | [5fe4fba501](https://linux-hardware.org/?probe=5fe4fba501) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| HP            | ZBook 17 G3                 | Notebook    | [bc4cf926f2](https://linux-hardware.org/?probe=bc4cf926f2) | Aug 06, 2022 |
| KOHJINSHA     | SC series                   | Notebook    | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | Notebook    | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6A... | Notebook    | [76d752f0ad](https://linux-hardware.org/?probe=76d752f0ad) | Aug 01, 2022 |
| Fujitsu       | LIFEBOOK V1020              | Notebook    | [e33ac2916d](https://linux-hardware.org/?probe=e33ac2916d) | Jul 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d449f1aeb9](https://linux-hardware.org/?probe=d449f1aeb9) | Jul 27, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [353168b909](https://linux-hardware.org/?probe=353168b909) | Jul 18, 2022 |
| Huanan        | X99-TF                      | Desktop     | [55b43de5a6](https://linux-hardware.org/?probe=55b43de5a6) | Jul 17, 2022 |
| IBM           | 260921H                     | Notebook    | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | Notebook    | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | Notebook    | [f3e0ebd16e](https://linux-hardware.org/?probe=f3e0ebd16e) | Jul 15, 2022 |
| IBM           | 260921H                     | Notebook    | [5f9b0998d3](https://linux-hardware.org/?probe=5f9b0998d3) | Jul 11, 2022 |
| IBM           | 260921H                     | Notebook    | [f0430651fd](https://linux-hardware.org/?probe=f0430651fd) | Jul 10, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e9adf47b7a](https://linux-hardware.org/?probe=e9adf47b7a) | Jul 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [910a4f6587](https://linux-hardware.org/?probe=910a4f6587) | Jul 09, 2022 |
| Soyo          | SY-A68M FS V2.0             | Desktop     | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [bd4792ebd8](https://linux-hardware.org/?probe=bd4792ebd8) | Jul 02, 2022 |
| Compaq        | Tablet PC TC1000            | Notebook    | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | Notebook    | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | Notebook    | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [044be44d33](https://linux-hardware.org/?probe=044be44d33) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [5bd3ad4d01](https://linux-hardware.org/?probe=5bd3ad4d01) | Jun 24, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [518331cc83](https://linux-hardware.org/?probe=518331cc83) | Jun 21, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ec6f5cce04](https://linux-hardware.org/?probe=ec6f5cce04) | Jun 20, 2022 |
| Huanan        | X99-TF                      | Desktop     | [04dc5246af](https://linux-hardware.org/?probe=04dc5246af) | Jun 18, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | Desktop     | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [bdd4ec2ef9](https://linux-hardware.org/?probe=bdd4ec2ef9) | Jun 15, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [f4c7f13ff8](https://linux-hardware.org/?probe=f4c7f13ff8) | Jun 14, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | Notebook    | [e3df184136](https://linux-hardware.org/?probe=e3df184136) | Jun 12, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e373d39f20](https://linux-hardware.org/?probe=e373d39f20) | Jun 09, 2022 |
| Huanan        | X99-TF                      | Desktop     | [4e5364e832](https://linux-hardware.org/?probe=4e5364e832) | Jun 08, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [2f8215fb0a](https://linux-hardware.org/?probe=2f8215fb0a) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [4d4c32223e](https://linux-hardware.org/?probe=4d4c32223e) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [63fd75f1a8](https://linux-hardware.org/?probe=63fd75f1a8) | May 29, 2022 |
| Lenovo        | Legion Y7000P2020H 82AX     | Notebook    | [220325c031](https://linux-hardware.org/?probe=220325c031) | May 29, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [75d345243e](https://linux-hardware.org/?probe=75d345243e) | May 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [1f67896c5c](https://linux-hardware.org/?probe=1f67896c5c) | May 22, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [a227af798c](https://linux-hardware.org/?probe=a227af798c) | May 20, 2022 |
| Gigabyte      | HA65M-UD3H-B3               | Desktop     | [d368918a0b](https://linux-hardware.org/?probe=d368918a0b) | May 13, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e45fa22892](https://linux-hardware.org/?probe=e45fa22892) | May 11, 2022 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [f0b122c199](https://linux-hardware.org/?probe=f0b122c199) | May 09, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [99e0958898](https://linux-hardware.org/?probe=99e0958898) | May 01, 2022 |
| Dell          | Precision 7520              | Notebook    | [2dc98a1a8d](https://linux-hardware.org/?probe=2dc98a1a8d) | Apr 30, 2022 |
| MSI           | H87I                        | Desktop     | [af4a26a5ea](https://linux-hardware.org/?probe=af4a26a5ea) | Apr 30, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [0633ac7757](https://linux-hardware.org/?probe=0633ac7757) | Apr 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [9191742453](https://linux-hardware.org/?probe=9191742453) | Apr 26, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [56902c7998](https://linux-hardware.org/?probe=56902c7998) | Apr 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [a3aa6e30b9](https://linux-hardware.org/?probe=a3aa6e30b9) | Apr 21, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [3dd8282149](https://linux-hardware.org/?probe=3dd8282149) | Apr 20, 2022 |
| GPD           | P2 MAX                      | Notebook    | [ca842dc5fb](https://linux-hardware.org/?probe=ca842dc5fb) | Apr 19, 2022 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [d359794b2f](https://linux-hardware.org/?probe=d359794b2f) | Apr 19, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [7ea786c89b](https://linux-hardware.org/?probe=7ea786c89b) | Apr 18, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0ac1f4daf9](https://linux-hardware.org/?probe=0ac1f4daf9) | Apr 12, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [abed3ae34d](https://linux-hardware.org/?probe=abed3ae34d) | Apr 12, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| ASUSTek       | VM62                        | Desktop     | [ae684cdf71](https://linux-hardware.org/?probe=ae684cdf71) | Apr 05, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [bdca066ba3](https://linux-hardware.org/?probe=bdca066ba3) | Apr 05, 2022 |
| ASRock        | H410M-ITX/ac                | Desktop     | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [314bd42e78](https://linux-hardware.org/?probe=314bd42e78) | Mar 28, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [a881a875bd](https://linux-hardware.org/?probe=a881a875bd) | Mar 27, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [2d48cb4419](https://linux-hardware.org/?probe=2d48cb4419) | Mar 26, 2022 |
| Dell          | 0Y3R3K A03                  | Desktop     | [b772cf9d86](https://linux-hardware.org/?probe=b772cf9d86) | Mar 26, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [e7fb180535](https://linux-hardware.org/?probe=e7fb180535) | Mar 16, 2022 |
| Dell          | Latitude 7285               | Notebook    | [87e555f958](https://linux-hardware.org/?probe=87e555f958) | Mar 13, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [7320ed668a](https://linux-hardware.org/?probe=7320ed668a) | Mar 12, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [03b27c8ca4](https://linux-hardware.org/?probe=03b27c8ca4) | Mar 12, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [4998fff0f9](https://linux-hardware.org/?probe=4998fff0f9) | Mar 12, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [99d3e16ede](https://linux-hardware.org/?probe=99d3e16ede) | Mar 12, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [c68cec2207](https://linux-hardware.org/?probe=c68cec2207) | Mar 11, 2022 |
| Unknown       | Intel X79                   | Desktop     | [e947d6af7f](https://linux-hardware.org/?probe=e947d6af7f) | Mar 11, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [96b36779e0](https://linux-hardware.org/?probe=96b36779e0) | Mar 11, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4d16610cf3](https://linux-hardware.org/?probe=4d16610cf3) | Mar 10, 2022 |
| HP            | Notebook                    | Notebook    | [9c04c0776d](https://linux-hardware.org/?probe=9c04c0776d) | Mar 10, 2022 |
| HP            | Notebook                    | Notebook    | [c7d735dc99](https://linux-hardware.org/?probe=c7d735dc99) | Mar 10, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0b9a7acb84](https://linux-hardware.org/?probe=0b9a7acb84) | Feb 27, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [3c7daed552](https://linux-hardware.org/?probe=3c7daed552) | Feb 22, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [6c00869d7b](https://linux-hardware.org/?probe=6c00869d7b) | Feb 21, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [0f4fad19b2](https://linux-hardware.org/?probe=0f4fad19b2) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6e5689a733](https://linux-hardware.org/?probe=6e5689a733) | Jan 28, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 Rev ... | Soc         | [2a66f4b578](https://linux-hardware.org/?probe=2a66f4b578) | Jan 24, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [515465fd5a](https://linux-hardware.org/?probe=515465fd5a) | Jan 22, 2022 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [4c32bf6d7b](https://linux-hardware.org/?probe=4c32bf6d7b) | Jan 18, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| HP            | 8597                        | Desktop     | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c5fa4a0cec](https://linux-hardware.org/?probe=c5fa4a0cec) | Dec 24, 2021 |
| ASRock        | H410M-ITX/ac                | Desktop     | [99c341562a](https://linux-hardware.org/?probe=99c341562a) | Dec 21, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| MSI           | 870-G45                     | Desktop     | [e6317a2b91](https://linux-hardware.org/?probe=e6317a2b91) | Dec 19, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| Fujitsu       | LIFEBOOK LH530              | Notebook    | [8db7409ab5](https://linux-hardware.org/?probe=8db7409ab5) | Dec 14, 2021 |
| Unknown       | Intel X79                   | Desktop     | [985655e4b3](https://linux-hardware.org/?probe=985655e4b3) | Dec 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [739be994cb](https://linux-hardware.org/?probe=739be994cb) | Dec 09, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [024a42eb21](https://linux-hardware.org/?probe=024a42eb21) | Dec 08, 2021 |
| Unknown       | Intel X79                   | Desktop     | [6f32192557](https://linux-hardware.org/?probe=6f32192557) | Dec 08, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| MSI           | Boston                      | Desktop     | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| Supermicro    | C2SBC-Q                     | Desktop     | [1099e48366](https://linux-hardware.org/?probe=1099e48366) | Nov 28, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [58d43162d2](https://linux-hardware.org/?probe=58d43162d2) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ee13ae89af](https://linux-hardware.org/?probe=ee13ae89af) | Nov 26, 2021 |
| Apple         | MacBook10,1                 | Notebook    | [6cb99e6a5f](https://linux-hardware.org/?probe=6cb99e6a5f) | Nov 23, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [fc59694424](https://linux-hardware.org/?probe=fc59694424) | Nov 17, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [35b58ec233](https://linux-hardware.org/?probe=35b58ec233) | Nov 16, 2021 |
| Jumper        | EZbook                      | Notebook    | [5da2b95e2f](https://linux-hardware.org/?probe=5da2b95e2f) | Nov 12, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| Seco          | C40 C                       | Desktop     | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [9bcd3d5479](https://linux-hardware.org/?probe=9bcd3d5479) | Oct 29, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [c7fc01bd49](https://linux-hardware.org/?probe=c7fc01bd49) | Oct 27, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [c7a0fe2f88](https://linux-hardware.org/?probe=c7a0fe2f88) | Oct 26, 2021 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [6f87ece998](https://linux-hardware.org/?probe=6f87ece998) | Oct 26, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [3d42bc888b](https://linux-hardware.org/?probe=3d42bc888b) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [54e54e71bd](https://linux-hardware.org/?probe=54e54e71bd) | Oct 24, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [aedfc53de6](https://linux-hardware.org/?probe=aedfc53de6) | Oct 20, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [20dc49f637](https://linux-hardware.org/?probe=20dc49f637) | Oct 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [aee062d6e5](https://linux-hardware.org/?probe=aee062d6e5) | Oct 04, 2021 |
| Lenovo        | Legion Y9000P2021H 82JD     | Notebook    | [4c3be0fe24](https://linux-hardware.org/?probe=4c3be0fe24) | Oct 02, 2021 |
| MSI           | H61M-P23                    | Desktop     | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| GPD           | G1618-03                    | Notebook    | [41916177c2](https://linux-hardware.org/?probe=41916177c2) | Sep 01, 2021 |
| GPD           | G1618-03                    | Notebook    | [c2abcaf10c](https://linux-hardware.org/?probe=c2abcaf10c) | Sep 01, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [1440e244f6](https://linux-hardware.org/?probe=1440e244f6) | Aug 26, 2021 |
| Dell          | Precision 7550              | Notebook    | [42721343a3](https://linux-hardware.org/?probe=42721343a3) | Aug 16, 2021 |
| Lenovo        | XiaoXin-14API QC 2019 81... | Notebook    | [814eb97442](https://linux-hardware.org/?probe=814eb97442) | Aug 14, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [d920558127](https://linux-hardware.org/?probe=d920558127) | Aug 14, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5cd377c0e0](https://linux-hardware.org/?probe=5cd377c0e0) | Aug 13, 2021 |
| Gigabyte      | B75M-D2P                    | Desktop     | [5e54c2a102](https://linux-hardware.org/?probe=5e54c2a102) | Aug 12, 2021 |
| Lenovo        | ThinkPad T61 6465CTO        | Notebook    | [d93258840e](https://linux-hardware.org/?probe=d93258840e) | Aug 04, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [eb060cd2c4](https://linux-hardware.org/?probe=eb060cd2c4) | Aug 04, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [828a52387f](https://linux-hardware.org/?probe=828a52387f) | Aug 02, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [12b2c3e130](https://linux-hardware.org/?probe=12b2c3e130) | Aug 01, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [3af43c8ebe](https://linux-hardware.org/?probe=3af43c8ebe) | Jul 29, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [fa0aa86cef](https://linux-hardware.org/?probe=fa0aa86cef) | Jul 28, 2021 |
| HP            | 2B38                        | Desktop     | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [8fc32673b3](https://linux-hardware.org/?probe=8fc32673b3) | Jul 25, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [58b70e282d](https://linux-hardware.org/?probe=58b70e282d) | Jul 14, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [66cf378cf1](https://linux-hardware.org/?probe=66cf378cf1) | Jul 10, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [6496f18326](https://linux-hardware.org/?probe=6496f18326) | Jul 02, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [71da4978c9](https://linux-hardware.org/?probe=71da4978c9) | Jun 29, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [ed911e7e8c](https://linux-hardware.org/?probe=ed911e7e8c) | Jun 26, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [8785d98b0b](https://linux-hardware.org/?probe=8785d98b0b) | Jun 19, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [54e520ac17](https://linux-hardware.org/?probe=54e520ac17) | Jun 17, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [c2bfccf320](https://linux-hardware.org/?probe=c2bfccf320) | Jun 16, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [d3f69874dd](https://linux-hardware.org/?probe=d3f69874dd) | Jun 16, 2021 |
| Lenovo        | IdeaCentre B305 10052       | All in one  | [8399296d51](https://linux-hardware.org/?probe=8399296d51) | Jun 13, 2021 |
| Dell          | Precision M4800             | Notebook    | [298694c222](https://linux-hardware.org/?probe=298694c222) | Jun 12, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [76219e9cca](https://linux-hardware.org/?probe=76219e9cca) | Jun 09, 2021 |
| Acer          | Aspire E5-573               | Notebook    | [4193a2da9d](https://linux-hardware.org/?probe=4193a2da9d) | Jun 08, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [bcb80080a5](https://linux-hardware.org/?probe=bcb80080a5) | Jun 06, 2021 |
| Dell          | Precision M4800             | Notebook    | [67fb08d285](https://linux-hardware.org/?probe=67fb08d285) | Jun 06, 2021 |
| Dell          | Precision M4800             | Notebook    | [c72664a2f4](https://linux-hardware.org/?probe=c72664a2f4) | Jun 06, 2021 |
| HP            | 18E7                        | Desktop     | [9844f6635c](https://linux-hardware.org/?probe=9844f6635c) | May 30, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [81ffc7ba9e](https://linux-hardware.org/?probe=81ffc7ba9e) | May 26, 2021 |
| ASUSTek       | VM62                        | Desktop     | [486aeb5b89](https://linux-hardware.org/?probe=486aeb5b89) | May 25, 2021 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [e19475cd4c](https://linux-hardware.org/?probe=e19475cd4c) | May 22, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [a201bdfc36](https://linux-hardware.org/?probe=a201bdfc36) | May 19, 2021 |
| Fujitsu       | UH-X                        | Notebook    | [be65091e59](https://linux-hardware.org/?probe=be65091e59) | May 19, 2021 |
| ASUSTek       | M4A78-VM                    | Desktop     | [3313d34c41](https://linux-hardware.org/?probe=3313d34c41) | May 15, 2021 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [1409e11b30](https://linux-hardware.org/?probe=1409e11b30) | May 12, 2021 |
| Nvidia        | Tegra                       | Soc         | [54592ec1a2](https://linux-hardware.org/?probe=54592ec1a2) | May 08, 2021 |
| Nvidia        | Tegra                       | Soc         | [ab1c7d5eab](https://linux-hardware.org/?probe=ab1c7d5eab) | May 08, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [8d372d62b7](https://linux-hardware.org/?probe=8d372d62b7) | May 07, 2021 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [1b777c6f08](https://linux-hardware.org/?probe=1b777c6f08) | May 02, 2021 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [4c7956a34c](https://linux-hardware.org/?probe=4c7956a34c) | May 02, 2021 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [f35a966b00](https://linux-hardware.org/?probe=f35a966b00) | Apr 14, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [a917367457](https://linux-hardware.org/?probe=a917367457) | Apr 09, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [f7937503ac](https://linux-hardware.org/?probe=f7937503ac) | Apr 08, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [99d71b6ea5](https://linux-hardware.org/?probe=99d71b6ea5) | Apr 06, 2021 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [8253b70553](https://linux-hardware.org/?probe=8253b70553) | Apr 06, 2021 |
| MSI           | Boston                      | Desktop     | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [60600f6f0c](https://linux-hardware.org/?probe=60600f6f0c) | Mar 26, 2021 |
| HP            | 1632                        | Desktop     | [adf9ebb679](https://linux-hardware.org/?probe=adf9ebb679) | Mar 25, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [6a4196e0aa](https://linux-hardware.org/?probe=6a4196e0aa) | Mar 23, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [dc64c81c35](https://linux-hardware.org/?probe=dc64c81c35) | Mar 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [280785b873](https://linux-hardware.org/?probe=280785b873) | Mar 22, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [20d78f0b3a](https://linux-hardware.org/?probe=20d78f0b3a) | Mar 22, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [71ef988016](https://linux-hardware.org/?probe=71ef988016) | Mar 21, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [e44a5ce779](https://linux-hardware.org/?probe=e44a5ce779) | Mar 14, 2021 |
| ASUSTek       | UX302LA                     | Notebook    | [fe27a8e195](https://linux-hardware.org/?probe=fe27a8e195) | Mar 12, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [d23d84b5f6](https://linux-hardware.org/?probe=d23d84b5f6) | Mar 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [5051ba6156](https://linux-hardware.org/?probe=5051ba6156) | Mar 05, 2021 |
| MSI           | Boston                      | Desktop     | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [b94539c6dc](https://linux-hardware.org/?probe=b94539c6dc) | Mar 01, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [b2cb174b9a](https://linux-hardware.org/?probe=b2cb174b9a) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [2414020b54](https://linux-hardware.org/?probe=2414020b54) | Feb 26, 2021 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [ae61a5e1fa](https://linux-hardware.org/?probe=ae61a5e1fa) | Feb 26, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [87c36a9322](https://linux-hardware.org/?probe=87c36a9322) | Feb 23, 2021 |
| Lenovo        | ThinkPad E14 20RAA002CD     | Notebook    | [77ccb1ee60](https://linux-hardware.org/?probe=77ccb1ee60) | Feb 22, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [7d9f2bee38](https://linux-hardware.org/?probe=7d9f2bee38) | Feb 21, 2021 |
| ASUSTek       | VM45                        | Desktop     | [03eeb85521](https://linux-hardware.org/?probe=03eeb85521) | Feb 21, 2021 |
| ASUSTek       | VM65-K                      | Desktop     | [6b97cf71eb](https://linux-hardware.org/?probe=6b97cf71eb) | Feb 18, 2021 |
| ASUSTek       | VM65-K                      | Desktop     | [4f0bcd1276](https://linux-hardware.org/?probe=4f0bcd1276) | Feb 17, 2021 |
| ASUSTek       | VM40B                       | Desktop     | [6c0bf22f39](https://linux-hardware.org/?probe=6c0bf22f39) | Feb 17, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [d82924b12b](https://linux-hardware.org/?probe=d82924b12b) | Feb 16, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [ebc5645105](https://linux-hardware.org/?probe=ebc5645105) | Feb 11, 2021 |
| Lenovo        | IdeaCentre K330             | Desktop     | [78ce34058b](https://linux-hardware.org/?probe=78ce34058b) | Feb 11, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [f4c2a6bac8](https://linux-hardware.org/?probe=f4c2a6bac8) | Feb 07, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [d4f69c78fa](https://linux-hardware.org/?probe=d4f69c78fa) | Jan 31, 2021 |
| Fujitsu       | S6420                       | Notebook    | [b23c0f10e7](https://linux-hardware.org/?probe=b23c0f10e7) | Jan 28, 2021 |
| Fujitsu       | S6420                       | Notebook    | [0cf6376b40](https://linux-hardware.org/?probe=0cf6376b40) | Jan 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1d0000672d](https://linux-hardware.org/?probe=1d0000672d) | Jan 23, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [3d7ce778c6](https://linux-hardware.org/?probe=3d7ce778c6) | Jan 20, 2021 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [fe7d03f093](https://linux-hardware.org/?probe=fe7d03f093) | Jan 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [b8f5d6f1e4](https://linux-hardware.org/?probe=b8f5d6f1e4) | Jan 16, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [39bc70ca5d](https://linux-hardware.org/?probe=39bc70ca5d) | Jan 13, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [d2420f233b](https://linux-hardware.org/?probe=d2420f233b) | Jan 10, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| Dell          | 0TP412                      | Desktop     | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| Intel         | NUC6CAYB J23203-406         | Mini pc     | [038dce10fa](https://linux-hardware.org/?probe=038dce10fa) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [a8ac85cb5a](https://linux-hardware.org/?probe=a8ac85cb5a) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [8c7ba97457](https://linux-hardware.org/?probe=8c7ba97457) | Dec 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [01333c5b9e](https://linux-hardware.org/?probe=01333c5b9e) | Dec 29, 2020 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [728d7e48d4](https://linux-hardware.org/?probe=728d7e48d4) | Dec 27, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [1d4b16bb0d](https://linux-hardware.org/?probe=1d4b16bb0d) | Dec 22, 2020 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [cf7386e848](https://linux-hardware.org/?probe=cf7386e848) | Dec 18, 2020 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [88a7edec45](https://linux-hardware.org/?probe=88a7edec45) | Dec 18, 2020 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [1d6b7df7b4](https://linux-hardware.org/?probe=1d6b7df7b4) | Dec 08, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [8309aa39cf](https://linux-hardware.org/?probe=8309aa39cf) | Nov 30, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [ede3032fed](https://linux-hardware.org/?probe=ede3032fed) | Nov 29, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [f3012a2898](https://linux-hardware.org/?probe=f3012a2898) | Nov 29, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [37d5acae7d](https://linux-hardware.org/?probe=37d5acae7d) | Nov 27, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [3c4ff5bb58](https://linux-hardware.org/?probe=3c4ff5bb58) | Nov 27, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [97c485886b](https://linux-hardware.org/?probe=97c485886b) | Nov 25, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [8f55b945a1](https://linux-hardware.org/?probe=8f55b945a1) | Nov 20, 2020 |
| Fujitsu       | UH-X                        | Notebook    | [f55a6a6679](https://linux-hardware.org/?probe=f55a6a6679) | Nov 20, 2020 |
| Fujitsu       | UH-X                        | Notebook    | [7aea886f7a](https://linux-hardware.org/?probe=7aea886f7a) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [de597aa847](https://linux-hardware.org/?probe=de597aa847) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f5aa8c9150](https://linux-hardware.org/?probe=f5aa8c9150) | Nov 20, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a3c484b8ee](https://linux-hardware.org/?probe=a3c484b8ee) | Nov 16, 2020 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | Notebook    | [6254edfb10](https://linux-hardware.org/?probe=6254edfb10) | Nov 14, 2020 |
| Lenovo        | G770 20089                  | Notebook    | [6da9203114](https://linux-hardware.org/?probe=6da9203114) | Nov 13, 2020 |
| HP            | 2000                        | Notebook    | [f548e6d1cc](https://linux-hardware.org/?probe=f548e6d1cc) | Nov 11, 2020 |
| ASUSTek       | K501UX                      | Notebook    | [e1700b887e](https://linux-hardware.org/?probe=e1700b887e) | Nov 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [69fb29494b](https://linux-hardware.org/?probe=69fb29494b) | Nov 07, 2020 |
| HP            | 2000                        | Notebook    | [df76d279ad](https://linux-hardware.org/?probe=df76d279ad) | Nov 05, 2020 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [f90977870e](https://linux-hardware.org/?probe=f90977870e) | Nov 04, 2020 |
| Timi          | TM1607                      | Notebook    | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| ZOTAC         | ZBOX-ID92/ZBOX-IQ01         | Mini pc     | [fbba9f6a3b](https://linux-hardware.org/?probe=fbba9f6a3b) | Nov 02, 2020 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [e970e25954](https://linux-hardware.org/?probe=e970e25954) | Nov 02, 2020 |
| Acer          | Swift SF314-57              | Notebook    | [8395e5a946](https://linux-hardware.org/?probe=8395e5a946) | Oct 30, 2020 |
| Acer          | Swift SF314-57              | Notebook    | [123f60c868](https://linux-hardware.org/?probe=123f60c868) | Oct 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [f9d1166197](https://linux-hardware.org/?probe=f9d1166197) | Oct 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [77849f8db0](https://linux-hardware.org/?probe=77849f8db0) | Oct 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [77d6dd66e2](https://linux-hardware.org/?probe=77d6dd66e2) | Oct 23, 2020 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [1af7b2b551](https://linux-hardware.org/?probe=1af7b2b551) | Oct 13, 2020 |
| HP            | 2140                        | Notebook    | [bde3dc449f](https://linux-hardware.org/?probe=bde3dc449f) | Oct 07, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [1fe32b8f6d](https://linux-hardware.org/?probe=1fe32b8f6d) | Oct 04, 2020 |
| HP            | 2000                        | Notebook    | [fbd8bf0e69](https://linux-hardware.org/?probe=fbd8bf0e69) | Oct 01, 2020 |
| Fujitsu       | LIFEBOOK S904               | Notebook    | [5035864c45](https://linux-hardware.org/?probe=5035864c45) | Sep 27, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [37e6b406f7](https://linux-hardware.org/?probe=37e6b406f7) | Sep 27, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [bd8f561b0b](https://linux-hardware.org/?probe=bd8f561b0b) | Sep 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e292456297](https://linux-hardware.org/?probe=e292456297) | Sep 17, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e7b41f62a4](https://linux-hardware.org/?probe=e7b41f62a4) | Sep 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [20bdbc68b7](https://linux-hardware.org/?probe=20bdbc68b7) | Sep 12, 2020 |
| ASUSTek       | H81M-E                      | Desktop     | [43b8c677bc](https://linux-hardware.org/?probe=43b8c677bc) | Sep 10, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [24cad8bed5](https://linux-hardware.org/?probe=24cad8bed5) | Aug 28, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [3d4c2a283d](https://linux-hardware.org/?probe=3d4c2a283d) | Aug 28, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [64a249acd1](https://linux-hardware.org/?probe=64a249acd1) | Aug 28, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [6a91a7b38c](https://linux-hardware.org/?probe=6a91a7b38c) | Aug 25, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [e27db6fb31](https://linux-hardware.org/?probe=e27db6fb31) | Aug 24, 2020 |
| Samsung       | 930XBE                      | Notebook    | [92925e0656](https://linux-hardware.org/?probe=92925e0656) | Aug 24, 2020 |
| HP            | 802E                        | Desktop     | [653b11eec3](https://linux-hardware.org/?probe=653b11eec3) | Aug 11, 2020 |
| HP            | 802E                        | Desktop     | [6f32afeb2b](https://linux-hardware.org/?probe=6f32afeb2b) | Aug 10, 2020 |
| HP            | 802E                        | Desktop     | [25d8ddc0bb](https://linux-hardware.org/?probe=25d8ddc0bb) | Aug 10, 2020 |
| Dell          | Inspiron 5580               | Notebook    | [fbaf2b8f7f](https://linux-hardware.org/?probe=fbaf2b8f7f) | Aug 05, 2020 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [e7488a8b16](https://linux-hardware.org/?probe=e7488a8b16) | Aug 04, 2020 |
| Toshiba       | PORTEGE R830                | Notebook    | [fa44f09e6e](https://linux-hardware.org/?probe=fa44f09e6e) | Aug 03, 2020 |
| Dell          | G7 7588                     | Notebook    | [e85e2949de](https://linux-hardware.org/?probe=e85e2949de) | Aug 01, 2020 |
| Lenovo        | ZHAOYANG K47                | Notebook    | [fa5be40392](https://linux-hardware.org/?probe=fa5be40392) | Jul 24, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [50dc692a9e](https://linux-hardware.org/?probe=50dc692a9e) | Jul 23, 2020 |
| Lenovo        | ZHAOYANG K47                | Notebook    | [879b0d586f](https://linux-hardware.org/?probe=879b0d586f) | Jul 22, 2020 |
| Gigabyte      | Z170X-Gaming 5 Modified ... | Desktop     | [a62f520dc3](https://linux-hardware.org/?probe=a62f520dc3) | Jul 18, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [723898cdec](https://linux-hardware.org/?probe=723898cdec) | Jun 20, 2020 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [f897dd388f](https://linux-hardware.org/?probe=f897dd388f) | Jun 17, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [c90b1cb242](https://linux-hardware.org/?probe=c90b1cb242) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [74dadf599d](https://linux-hardware.org/?probe=74dadf599d) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [db21903e1a](https://linux-hardware.org/?probe=db21903e1a) | Jun 14, 2020 |
| Lenovo        | ThinkPad T480s 20L7005FU... | Notebook    | [2bc99eeca5](https://linux-hardware.org/?probe=2bc99eeca5) | Jun 09, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| HP            | 1998                        | Desktop     | [255863fefb](https://linux-hardware.org/?probe=255863fefb) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | Desktop     | [b159b440f2](https://linux-hardware.org/?probe=b159b440f2) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | Desktop     | [4181637bf3](https://linux-hardware.org/?probe=4181637bf3) | Jun 01, 2020 |
| Fujitsu       | LIFEBOOK AH556              | Notebook    | [c16b3d9827](https://linux-hardware.org/?probe=c16b3d9827) | May 30, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [55680319a1](https://linux-hardware.org/?probe=55680319a1) | May 29, 2020 |
| Biostar       | H110MHC                     | Desktop     | [98d1029698](https://linux-hardware.org/?probe=98d1029698) | May 26, 2020 |
| ASUSTek       | B150M-C                     | Desktop     | [2229b866b3](https://linux-hardware.org/?probe=2229b866b3) | May 26, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Apple         | MacBookPro7,1               | Notebook    | [956da1ac80](https://linux-hardware.org/?probe=956da1ac80) | May 11, 2020 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| Toshiba       | PORTEGE R830                | Notebook    | [08f3e97afe](https://linux-hardware.org/?probe=08f3e97afe) | May 02, 2020 |
| Lenovo        | 3000 G410                   | Notebook    | [2a909aaad5](https://linux-hardware.org/?probe=2a909aaad5) | May 02, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [179a82277c](https://linux-hardware.org/?probe=179a82277c) | May 01, 2020 |
| MSI           | 2A9C                        | Desktop     | [23df26e5de](https://linux-hardware.org/?probe=23df26e5de) | Apr 25, 2020 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [664ac5b85b](https://linux-hardware.org/?probe=664ac5b85b) | Apr 24, 2020 |
| MSI           | Boston                      | Desktop     | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [f11d6eedc7](https://linux-hardware.org/?probe=f11d6eedc7) | Apr 14, 2020 |
| HP            | G72                         | Notebook    | [6272536a26](https://linux-hardware.org/?probe=6272536a26) | Apr 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [f504649d96](https://linux-hardware.org/?probe=f504649d96) | Apr 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [3916938374](https://linux-hardware.org/?probe=3916938374) | Apr 11, 2020 |
| Gigabyte      | Z87-HD3                     | Desktop     | [52a7dab5ac](https://linux-hardware.org/?probe=52a7dab5ac) | Apr 09, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [9c72670aa1](https://linux-hardware.org/?probe=9c72670aa1) | Apr 05, 2020 |
| Google        | Eve                         | Notebook    | [17c248ca99](https://linux-hardware.org/?probe=17c248ca99) | Apr 04, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [37fb7cae94](https://linux-hardware.org/?probe=37fb7cae94) | Mar 30, 2020 |
| MSI           | B360M FIRE                  | Desktop     | [8bb021d2a6](https://linux-hardware.org/?probe=8bb021d2a6) | Mar 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [18b565a861](https://linux-hardware.org/?probe=18b565a861) | Mar 26, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [abce376627](https://linux-hardware.org/?probe=abce376627) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e6860a26ae](https://linux-hardware.org/?probe=e6860a26ae) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [5f2e14b65b](https://linux-hardware.org/?probe=5f2e14b65b) | Mar 16, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [1bcf8a4701](https://linux-hardware.org/?probe=1bcf8a4701) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [bd55777a4f](https://linux-hardware.org/?probe=bd55777a4f) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [137262daa3](https://linux-hardware.org/?probe=137262daa3) | Mar 05, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [597092ba51](https://linux-hardware.org/?probe=597092ba51) | Feb 28, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [71fc35ceea](https://linux-hardware.org/?probe=71fc35ceea) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [047acafb1a](https://linux-hardware.org/?probe=047acafb1a) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e8315b1469](https://linux-hardware.org/?probe=e8315b1469) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [04e5b85d84](https://linux-hardware.org/?probe=04e5b85d84) | Feb 28, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [310ae04477](https://linux-hardware.org/?probe=310ae04477) | Feb 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [046814376c](https://linux-hardware.org/?probe=046814376c) | Feb 20, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a417965167](https://linux-hardware.org/?probe=a417965167) | Feb 19, 2020 |
| Intel         | DH77DF AAG40293-301         | Desktop     | [ac00169b1c](https://linux-hardware.org/?probe=ac00169b1c) | Feb 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [cef9a00862](https://linux-hardware.org/?probe=cef9a00862) | Feb 12, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [dcc65f9ee3](https://linux-hardware.org/?probe=dcc65f9ee3) | Feb 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [900a11f8b3](https://linux-hardware.org/?probe=900a11f8b3) | Feb 10, 2020 |
| MSI           | GS73VR 7RG                  | Notebook    | [fbdf43d1d6](https://linux-hardware.org/?probe=fbdf43d1d6) | Feb 04, 2020 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [20d5a3bd6a](https://linux-hardware.org/?probe=20d5a3bd6a) | Feb 01, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cf4dbec684](https://linux-hardware.org/?probe=cf4dbec684) | Feb 01, 2020 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Gigabyte      | P55A-UD3                    | Desktop     | [7168fd0137](https://linux-hardware.org/?probe=7168fd0137) | Jan 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [1007637420](https://linux-hardware.org/?probe=1007637420) | Dec 31, 2019 |
| Unknown       | Unknown                     | Notebook    | [bb58a92938](https://linux-hardware.org/?probe=bb58a92938) | Dec 31, 2019 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [b2d6dabaa7](https://linux-hardware.org/?probe=b2d6dabaa7) | Dec 23, 2019 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [e3b6ce369a](https://linux-hardware.org/?probe=e3b6ce369a) | Dec 23, 2019 |
| Dell          | XPS 13 9370                 | Notebook    | [0f39165d62](https://linux-hardware.org/?probe=0f39165d62) | Dec 06, 2019 |
| Dell          | XPS 13 9370                 | Notebook    | [816ad4feea](https://linux-hardware.org/?probe=816ad4feea) | Dec 06, 2019 |
| ASUSTek       | X556URK                     | Notebook    | [78f15ad5f0](https://linux-hardware.org/?probe=78f15ad5f0) | Nov 30, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [49e2cab57b](https://linux-hardware.org/?probe=49e2cab57b) | Nov 28, 2019 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [042c4b3c5a](https://linux-hardware.org/?probe=042c4b3c5a) | Nov 22, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [f63dcc4fc8](https://linux-hardware.org/?probe=f63dcc4fc8) | Nov 07, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [15f84fa3f2](https://linux-hardware.org/?probe=15f84fa3f2) | Oct 26, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3497939f58](https://linux-hardware.org/?probe=3497939f58) | Oct 18, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a04ed98be8](https://linux-hardware.org/?probe=a04ed98be8) | Oct 18, 2019 |
| CompuLab      | Airtop                      | Mini pc     | [ff3ce414e4](https://linux-hardware.org/?probe=ff3ce414e4) | Oct 16, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [b2ebcf2c70](https://linux-hardware.org/?probe=b2ebcf2c70) | Oct 10, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [43a5e168a1](https://linux-hardware.org/?probe=43a5e168a1) | Oct 10, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [3392a03f3c](https://linux-hardware.org/?probe=3392a03f3c) | Oct 03, 2019 |
| Unknown       | Unknown                     | Notebook    | [f8f1207d2d](https://linux-hardware.org/?probe=f8f1207d2d) | Sep 29, 2019 |
| Unknown       | Unknown                     | Notebook    | [d19b3f1330](https://linux-hardware.org/?probe=d19b3f1330) | Sep 28, 2019 |
| Unknown       | Unknown                     | Notebook    | [a6d4347345](https://linux-hardware.org/?probe=a6d4347345) | Sep 28, 2019 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [4302e84025](https://linux-hardware.org/?probe=4302e84025) | Sep 24, 2019 |
| Acer          | Aspire S3-371               | Notebook    | [5086f9ddaa](https://linux-hardware.org/?probe=5086f9ddaa) | Sep 07, 2019 |
| Acer          | Aspire S3-371               | Notebook    | [aa8140a178](https://linux-hardware.org/?probe=aa8140a178) | Sep 03, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [e8ccb234ed](https://linux-hardware.org/?probe=e8ccb234ed) | Aug 30, 2019 |
| ASRock        | B75M R2.0                   | Desktop     | [1479826c17](https://linux-hardware.org/?probe=1479826c17) | Aug 28, 2019 |
| Hardkernel    | ODROID-H2                   | Desktop     | [26d6c60ad5](https://linux-hardware.org/?probe=26d6c60ad5) | Jul 06, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [ea2ad2bc4d](https://linux-hardware.org/?probe=ea2ad2bc4d) | Jun 05, 2019 |
| ASUSTek       | TUF GAMING FX504GM_FX80G... | Notebook    | [7e9553ea70](https://linux-hardware.org/?probe=7e9553ea70) | Jun 03, 2019 |
| Lenovo        | ThinkPad T430 2342AG4       | Notebook    | [cf7413e712](https://linux-hardware.org/?probe=cf7413e712) | May 31, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [e8a5c28644](https://linux-hardware.org/?probe=e8a5c28644) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [b67f52c0c2](https://linux-hardware.org/?probe=b67f52c0c2) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [c408ceb62e](https://linux-hardware.org/?probe=c408ceb62e) | May 29, 2019 |
| Dell          | Latitude E4310              | Notebook    | [134afc5b6b](https://linux-hardware.org/?probe=134afc5b6b) | May 08, 2019 |
| Lenovo        | ThinkPad T520 4242BC5       | Notebook    | [977c44b97a](https://linux-hardware.org/?probe=977c44b97a) | Apr 29, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | Notebook    | [5801835e32](https://linux-hardware.org/?probe=5801835e32) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | Notebook    | [0f4999f205](https://linux-hardware.org/?probe=0f4999f205) | Apr 27, 2019 |
| Dell          | 0CRH6C A01                  | Desktop     | [23dcf2aff6](https://linux-hardware.org/?probe=23dcf2aff6) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [61bb547684](https://linux-hardware.org/?probe=61bb547684) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [8549b6dfd8](https://linux-hardware.org/?probe=8549b6dfd8) | Apr 08, 2019 |
| Unknown       | A11-COMPUTER                | Notebook    | [fae06bb10f](https://linux-hardware.org/?probe=fae06bb10f) | Mar 28, 2019 |
| Unknown       | A11-COMPUTER                | Notebook    | [427daf4d4e](https://linux-hardware.org/?probe=427daf4d4e) | Mar 28, 2019 |
| Lenovo        | ThinkPad W530 24384KU       | Notebook    | [2064d92892](https://linux-hardware.org/?probe=2064d92892) | Dec 12, 2018 |
| Dell          | XPS 13 9350                 | Notebook    | [6fb539c340](https://linux-hardware.org/?probe=6fb539c340) | Oct 29, 2018 |
| ASRock        | Z270 Killer SLI             | Desktop     | [a03ea38833](https://linux-hardware.org/?probe=a03ea38833) | Jul 06, 2018 |
| HP            | ProBook 4540s               | Notebook    | [ace9a95fb7](https://linux-hardware.org/?probe=ace9a95fb7) | May 09, 2018 |
| HP            | ProBook 4540s               | Notebook    | [8f50260d94](https://linux-hardware.org/?probe=8f50260d94) | May 09, 2018 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [17f0958960](https://linux-hardware.org/?probe=17f0958960) | Oct 06, 2017 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 48        | 14.29%  |
| Ubuntu 18.04        | 23        | 6.85%   |
| Ubuntu 22.04        | 20        | 5.95%   |
| OpenMandriva 4.2    | 13        | 3.87%   |
| Arch Rolling        | 11        | 3.27%   |
| Arch                | 11        | 3.27%   |
| Debian 11           | 10        | 2.98%   |
| antiX 21            | 9         | 2.68%   |
| Ubuntu 19.10        | 8         | 2.38%   |
| OpenMandriva 4.3    | 7         | 2.08%   |
| KDE neon 20.04      | 7         | 2.08%   |
| Ubuntu 20.10        | 6         | 1.79%   |
| Pop!_OS 22.04       | 6         | 1.79%   |
| Gentoo 2.7          | 6         | 1.79%   |
| Fedora 35           | 6         | 1.79%   |
| Fedora 32           | 6         | 1.79%   |
| ArcoLinux Rolling   | 6         | 1.79%   |
| Fedora 36           | 5         | 1.49%   |
| EndeavourOS Rolling | 5         | 1.49%   |
| Ubuntu 21.04        | 4         | 1.19%   |
| Ubuntu 19.04        | 4         | 1.19%   |
| Pop!_OS 20.10       | 4         | 1.19%   |
| Linux Mint 20       | 4         | 1.19%   |
| Fedora 33           | 4         | 1.19%   |
| Ubuntu 21.10        | 3         | 0.89%   |
| Ubuntu 16.04        | 3         | 0.89%   |
| OpenMandriva 4.50   | 3         | 0.89%   |
| Linux Mint 20.3     | 3         | 0.89%   |
| Gentoo 2.8          | 3         | 0.89%   |
| Elementary 5.1.7    | 3         | 0.89%   |
| Chrome OS           | 3         | 0.89%   |
| Zorin 15            | 2         | 0.6%    |
| Ubuntu 22.10        | 2         | 0.6%    |
| SteamOS 3.3         | 2         | 0.6%    |
| Slackware 15.0      | 2         | 0.6%    |
| PostmarketOS Edge   | 2         | 0.6%    |
| Pop!_OS 21.04       | 2         | 0.6%    |
| Pop!_OS 20.04       | 2         | 0.6%    |
| Parrot 4.9          | 2         | 0.6%    |
| Manjaro 21.1.0      | 2         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 115       | 35.38%  |
| Fedora        | 28        | 8.62%   |
| OpenMandriva  | 24        | 7.38%   |
| Arch          | 22        | 6.77%   |
| Pop!_OS       | 15        | 4.62%   |
| Debian        | 12        | 3.69%   |
| Manjaro       | 10        | 3.08%   |
| Linux Mint    | 10        | 3.08%   |
| antiX         | 9         | 2.77%   |
| Gentoo        | 8         | 2.46%   |
| KDE neon      | 7         | 2.15%   |
| EndeavourOS   | 6         | 1.85%   |
| Clear Linux   | 6         | 1.85%   |
| ArcoLinux     | 6         | 1.85%   |
| Kubuntu       | 4         | 1.23%   |
| Elementary    | 4         | 1.23%   |
| Zorin         | 3         | 0.92%   |
| Ubuntu Unity  | 3         | 0.92%   |
| SteamOS       | 3         | 0.92%   |
| Slackware     | 3         | 0.92%   |
| ROSA          | 3         | 0.92%   |
| Chrome OS     | 3         | 0.92%   |
| CentOS        | 3         | 0.92%   |
| Ubuntu MATE   | 2         | 0.62%   |
| PostmarketOS  | 2         | 0.62%   |
| Parrot        | 2         | 0.62%   |
| Kali          | 2         | 0.62%   |
| Xubuntu       | 1         | 0.31%   |
| UbuntuDDE     | 1         | 0.31%   |
| Ubuntu Budgie | 1         | 0.31%   |
| Raspbian      | 1         | 0.31%   |
| PCLinuxOS     | 1         | 0.31%   |
| Oracle Linux  | 1         | 0.31%   |
| openSUSE      | 1         | 0.31%   |
| Lubuntu       | 1         | 0.31%   |
| BlackPanther  | 1         | 0.31%   |
| Artix         | 1         | 0.31%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002  | 12        | 3.28%   |
| 5.4.0-42-generic          | 9         | 2.46%   |
| 4.9.0-279-antix.1-486-smp | 8         | 2.19%   |
| 5.16.7-desktop-1omv4003   | 7         | 1.91%   |
| 5.15.0-46-generic         | 5         | 1.37%   |
| 5.15.0-52-generic         | 4         | 1.09%   |
| 5.13.0-39-generic         | 4         | 1.09%   |
| 5.13.0-35-generic         | 4         | 1.09%   |
| 5.8.0-7630-generic        | 3         | 0.82%   |
| 5.8.0-55-generic          | 3         | 0.82%   |
| 5.8.0-43-generic          | 3         | 0.82%   |
| 5.4.0-48-generic          | 3         | 0.82%   |
| 5.4.0-33-generic          | 3         | 0.82%   |
| 5.4.0-28-generic          | 3         | 0.82%   |
| 5.4.0-26-generic          | 3         | 0.82%   |
| 5.3.0-46-generic          | 3         | 0.82%   |
| 5.15.0-47-generic         | 3         | 0.82%   |
| 5.11.0-37-generic         | 3         | 0.82%   |
| 4.19.49+                  | 3         | 0.82%   |
| 6.1.1-arch1-1             | 2         | 0.55%   |
| 6.0.12-300.fc37.x86_64    | 2         | 0.55%   |
| 5.9.2-arch1-1             | 2         | 0.55%   |
| 5.5.0-1parrot1-amd64      | 2         | 0.55%   |
| 5.4.0-58-generic          | 2         | 0.55%   |
| 5.4.0-56-generic          | 2         | 0.55%   |
| 5.4.0-52-generic          | 2         | 0.55%   |
| 5.4.0-47-generic          | 2         | 0.55%   |
| 5.4.0-109-generic         | 2         | 0.55%   |
| 5.3.0-24-generic          | 2         | 0.55%   |
| 5.3.0-18-generic          | 2         | 0.55%   |
| 5.19.0-76051900-generic   | 2         | 0.55%   |
| 5.17.5-76051705-generic   | 2         | 0.55%   |
| 5.17.11-300.fc36.x86_64   | 2         | 0.55%   |
| 5.16.12-200.fc35.x86_64   | 2         | 0.55%   |
| 5.15.0-53-generic         | 2         | 0.55%   |
| 5.13.0-7614-generic       | 2         | 0.55%   |
| 5.13.0-21-generic         | 2         | 0.55%   |
| 5.11.0-43-generic         | 2         | 0.55%   |
| 5.11.0-41-generic         | 2         | 0.55%   |
| 5.11.0-25-generic         | 2         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 41        | 11.85%  |
| 5.15.0  | 24        | 6.94%   |
| 5.8.0   | 22        | 6.36%   |
| 5.13.0  | 21        | 6.07%   |
| 5.11.0  | 15        | 4.34%   |
| 4.15.0  | 14        | 4.05%   |
| 5.3.0   | 12        | 3.47%   |
| 5.10.14 | 12        | 3.47%   |
| 5.0.0   | 10        | 2.89%   |
| 4.9.0   | 9         | 2.6%    |
| 5.19.0  | 8         | 2.31%   |
| 5.10.0  | 8         | 2.31%   |
| 5.16.7  | 7         | 2.02%   |
| 4.18.0  | 5         | 1.45%   |
| 6.0.0   | 4         | 1.16%   |
| 5.17.5  | 4         | 1.16%   |
| 4.19.49 | 3         | 0.87%   |
| 6.1.1   | 2         | 0.58%   |
| 6.0.12  | 2         | 0.58%   |
| 5.9.2   | 2         | 0.58%   |
| 5.5.0   | 2         | 0.58%   |
| 5.19.13 | 2         | 0.58%   |
| 5.18.5  | 2         | 0.58%   |
| 5.17.4  | 2         | 0.58%   |
| 5.17.11 | 2         | 0.58%   |
| 5.16.12 | 2         | 0.58%   |
| 5.16.11 | 2         | 0.58%   |
| 5.14.14 | 2         | 0.58%   |
| 5.11.12 | 2         | 0.58%   |
| 5.10.76 | 2         | 0.58%   |
| 6.1.0   | 1         | 0.29%   |
| 6.0.10  | 1         | 0.29%   |
| 6.0.1   | 1         | 0.29%   |
| 5.9.8   | 1         | 0.29%   |
| 5.9.4   | 1         | 0.29%   |
| 5.9.3   | 1         | 0.29%   |
| 5.9.16  | 1         | 0.29%   |
| 5.9.14  | 1         | 0.29%   |
| 5.9.12  | 1         | 0.29%   |
| 5.9.10  | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 12.02%  |
| 5.15    | 34        | 9.97%   |
| 5.10    | 32        | 9.38%   |
| 5.8     | 28        | 8.21%   |
| 5.13    | 25        | 7.33%   |
| 5.11    | 22        | 6.45%   |
| 5.19    | 18        | 5.28%   |
| 5.3     | 15        | 4.4%    |
| 5.16    | 14        | 4.11%   |
| 4.15    | 14        | 4.11%   |
| 5.17    | 13        | 3.81%   |
| 4.9     | 13        | 3.81%   |
| 5.9     | 10        | 2.93%   |
| 5.0     | 10        | 2.93%   |
| 6.0     | 8         | 2.35%   |
| 5.18    | 7         | 2.05%   |
| 5.7     | 6         | 1.76%   |
| 5.14    | 6         | 1.76%   |
| 4.18    | 6         | 1.76%   |
| 6.1     | 3         | 0.88%   |
| 5.6     | 3         | 0.88%   |
| 5.5     | 3         | 0.88%   |
| 5.12    | 3         | 0.88%   |
| 4.19    | 3         | 0.88%   |
| 4.4     | 2         | 0.59%   |
| 4.17    | 1         | 0.29%   |
| 3.10    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 293       | 92.72%  |
| i686    | 12        | 3.8%    |
| aarch64 | 9         | 2.85%   |
| i586    | 1         | 0.32%   |
| armv7l  | 1         | 0.32%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 150       | 46.01%  |
| KDE5       | 64        | 19.63%  |
| Unknown    | 56        | 17.18%  |
| XFCE       | 12        | 3.68%   |
| KDE        | 8         | 2.45%   |
| X-Cinnamon | 7         | 2.15%   |
| MATE       | 4         | 1.23%   |
| i3         | 4         | 1.23%   |
| Pantheon   | 3         | 0.92%   |
| Unity      | 2         | 0.61%   |
| sway       | 2         | 0.61%   |
| Openbox    | 2         | 0.61%   |
| LXDE       | 2         | 0.61%   |
| dwm        | 2         | 0.61%   |
| Deepin     | 2         | 0.61%   |
| LXQt       | 1         | 0.31%   |
| KDE4       | 1         | 0.31%   |
| fvwm       | 1         | 0.31%   |
| Cinnamon   | 1         | 0.31%   |
| Budgie     | 1         | 0.31%   |
| awesome    | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 247       | 76%     |
| Wayland | 51        | 15.69%  |
| Unknown | 19        | 5.85%   |
| Tty     | 8         | 2.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 151       | 46.46%  |
| SDDM    | 63        | 19.38%  |
| GDM     | 46        | 14.15%  |
| GDM3    | 32        | 9.85%   |
| LightDM | 21        | 6.46%   |
| TDM     | 7         | 2.15%   |
| Ly      | 2         | 0.62%   |
| XDM     | 1         | 0.31%   |
| LXDM    | 1         | 0.31%   |
| KDM     | 1         | 0.31%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 123       | 37.39%  |
| en_HK   | 85        | 25.84%  |
| zh_CN   | 35        | 10.64%  |
| Unknown | 34        | 10.33%  |
| zh_TW   | 16        | 4.86%   |
| zh_HK   | 13        | 3.95%   |
| C       | 9         | 2.74%   |
| en_GB   | 8         | 2.43%   |
| en_AU   | 3         | 0.91%   |
| it_IT   | 1         | 0.3%    |
| en_ZA   | 1         | 0.3%    |
| de_DE   | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 196       | 61.06%  |
| BIOS | 125       | 38.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 238       | 73.46%  |
| Btrfs   | 38        | 11.73%  |
| Overlay | 21        | 6.48%   |
| Xfs     | 8         | 2.47%   |
| Unknown | 8         | 2.47%   |
| Zfs     | 6         | 1.85%   |
| Ext3    | 2         | 0.62%   |
| Ext2    | 2         | 0.62%   |
| F2fs    | 1         | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 146       | 45.48%  |
| Unknown | 141       | 43.93%  |
| MBR     | 34        | 10.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 274       | 85.36%  |
| Yes       | 47        | 14.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 210       | 65.22%  |
| Yes       | 112       | 34.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 65        | 20.57%  |
| ASUSTek Computer        | 46        | 14.56%  |
| Dell                    | 31        | 9.81%   |
| MSI                     | 26        | 8.23%   |
| Hewlett-Packard         | 26        | 8.23%   |
| Gigabyte Technology     | 22        | 6.96%   |
| ASRock                  | 14        | 4.43%   |
| Fujitsu                 | 12        | 3.8%    |
| Unknown                 | 12        | 3.8%    |
| Acer                    | 7         | 2.22%   |
| Apple                   | 6         | 1.9%    |
| HUAWEI                  | 5         | 1.58%   |
| Raspberry Pi Foundation | 4         | 1.27%   |
| Intel                   | 4         | 1.27%   |
| Supermicro              | 3         | 0.95%   |
| GPD                     | 3         | 0.95%   |
| AMI                     | 3         | 0.95%   |
| Toshiba                 | 2         | 0.63%   |
| Samsung Electronics     | 2         | 0.63%   |
| KOHJINSHA               | 2         | 0.63%   |
| IBM                     | 2         | 0.63%   |
| ZOTAC                   | 1         | 0.32%   |
| Timi                    | 1         | 0.32%   |
| Soyo                    | 1         | 0.32%   |
| Sony                    | 1         | 0.32%   |
| Seco                    | 1         | 0.32%   |
| Schenker                | 1         | 0.32%   |
| Panasonic               | 1         | 0.32%   |
| Nvidia                  | 1         | 0.32%   |
| Jumper                  | 1         | 0.32%   |
| Intel Client Systems    | 1         | 0.32%   |
| Huanan                  | 1         | 0.32%   |
| Hardkernel              | 1         | 0.32%   |
| Google                  | 1         | 0.32%   |
| Foxconn                 | 1         | 0.32%   |
| CompuLab                | 1         | 0.32%   |
| Compaq                  | 1         | 0.32%   |
| Chuwi                   | 1         | 0.32%   |
| Biostar                 | 1         | 0.32%   |
| AOKZOE                  | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 13        | 4.11%   |
| MSI MS-7C94                            | 3         | 0.95%   |
| Lenovo Legion R7000 2020 82B6          | 3         | 0.95%   |
| ASUS H110I-PLUS                        | 3         | 0.95%   |
| ASUS All Series                        | 3         | 0.95%   |
| RPi Raspberry Pi                       | 2         | 0.63%   |
| MSI MS-7D42                            | 2         | 0.63%   |
| MSI MS-7B93                            | 2         | 0.63%   |
| IBM 260921H                            | 2         | 0.63%   |
| HUAWEI KPRC-WX0                        | 2         | 0.63%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC       | 2         | 0.63%   |
| HP ProDesk 600 G1 SFF                  | 2         | 0.63%   |
| HP EliteBook 2540p                     | 2         | 0.63%   |
| Gigabyte X570 AORUS ELITE              | 2         | 0.63%   |
| Fujitsu UH-X                           | 2         | 0.63%   |
| Fujitsu LIFEBOOK AH544                 | 2         | 0.63%   |
| Dell XPS 13 9310                       | 2         | 0.63%   |
| Dell Inspiron 5580                     | 2         | 0.63%   |
| ASUS Z8NA-D6                           | 2         | 0.63%   |
| ASUS VM65                              | 2         | 0.63%   |
| ASUS VM62                              | 2         | 0.63%   |
| ASUS TUF Gaming FA506IU_FA506IU        | 2         | 0.63%   |
| ASRock H410M-ITX/ac                    | 2         | 0.63%   |
| ASRock H410M-HDV                       | 2         | 0.63%   |
| AMI Aptio CRB                          | 2         | 0.63%   |
| ZOTAC ZBOX-ID92/ZBOX-IQ01              | 1         | 0.32%   |
| Toshiba PORTEGE R830                   | 1         | 0.32%   |
| Toshiba dynabook R731/E                | 1         | 0.32%   |
| Timi TM1607                            | 1         | 0.32%   |
| Supermicro X9DRD-7LN4F(-JBOD)/X9DRD-EF | 1         | 0.32%   |
| Supermicro PIO-617R-TLN4F+-ST031       | 1         | 0.32%   |
| Supermicro C2SBC-Q                     | 1         | 0.32%   |
| Soyo SY-A68M FS V2.0                   | 1         | 0.32%   |
| Sony VPCCB17FG                         | 1         | 0.32%   |
| Seco C40                               | 1         | 0.32%   |
| Schenker XMG_APEX15_XAP15E20           | 1         | 0.32%   |
| Samsung SQ1S                           | 1         | 0.32%   |
| Samsung 930XBE                         | 1         | 0.32%   |
| RPi Raspberry Pi Zero 2 Rev 1.0        | 1         | 0.32%   |
| RPi Raspberry Pi 400 Rev 1.0           | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 27        | 8.54%   |
| Unknown            | 13        | 4.11%   |
| Dell Inspiron      | 10        | 3.16%   |
| Lenovo Legion      | 8         | 2.53%   |
| Fujitsu LIFEBOOK   | 8         | 2.53%   |
| Dell XPS           | 8         | 2.53%   |
| ASUS PRIME         | 7         | 2.22%   |
| ASUS TUF           | 6         | 1.9%    |
| Lenovo IdeaPad     | 5         | 1.58%   |
| Dell Precision     | 5         | 1.58%   |
| RPi Raspberry      | 4         | 1.27%   |
| Lenovo Yoga        | 4         | 1.27%   |
| Lenovo ThinkCentre | 4         | 1.27%   |
| Dell Latitude      | 4         | 1.27%   |
| ASUS ROG           | 4         | 1.27%   |
| Acer Aspire        | 4         | 1.27%   |
| MSI MS-7C94        | 3         | 0.95%   |
| HP ZHAN            | 3         | 0.95%   |
| HP ProDesk         | 3         | 0.95%   |
| HP EliteBook       | 3         | 0.95%   |
| Gigabyte X570      | 3         | 0.95%   |
| Dell OptiPlex      | 3         | 0.95%   |
| ASUS H110I-PLUS    | 3         | 0.95%   |
| ASUS All           | 3         | 0.95%   |
| Acer Swift         | 3         | 0.95%   |
| MSI MS-7D42        | 2         | 0.63%   |
| MSI MS-7B93        | 2         | 0.63%   |
| Lenovo ThinkBook   | 2         | 0.63%   |
| Lenovo IdeaPadFlex | 2         | 0.63%   |
| Lenovo IdeaCentre  | 2         | 0.63%   |
| IBM 260921H        | 2         | 0.63%   |
| HUAWEI KPRC-WX0    | 2         | 0.63%   |
| HP Pavilion        | 2         | 0.63%   |
| Gigabyte B450      | 2         | 0.63%   |
| Fujitsu UH-X       | 2         | 0.63%   |
| ASUS Z8NA-D6       | 2         | 0.63%   |
| ASUS VM65          | 2         | 0.63%   |
| ASUS VM62          | 2         | 0.63%   |
| ASRock H410M-ITX   | 2         | 0.63%   |
| ASRock H410M-HDV   | 2         | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 47        | 14.87%  |
| 2020    | 42        | 13.29%  |
| 2019    | 33        | 10.44%  |
| 2021    | 30        | 9.49%   |
| 2011    | 17        | 5.38%   |
| 2016    | 16        | 5.06%   |
| 2015    | 16        | 5.06%   |
| 2014    | 16        | 5.06%   |
| 2013    | 16        | 5.06%   |
| 2010    | 16        | 5.06%   |
| 2017    | 13        | 4.11%   |
| 2022    | 12        | 3.8%    |
| 2012    | 12        | 3.8%    |
| Unknown | 9         | 2.85%   |
| 2008    | 8         | 2.53%   |
| 2009    | 5         | 1.58%   |
| 2007    | 4         | 1.27%   |
| 1999    | 2         | 0.63%   |
| 2005    | 1         | 0.32%   |
| 2003    | 1         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 161       | 50.95%  |
| Desktop        | 129       | 40.82%  |
| Mini pc        | 8         | 2.53%   |
| System on chip | 6         | 1.9%    |
| Convertible    | 6         | 1.9%    |
| Tablet         | 2         | 0.63%   |
| All in one     | 2         | 0.63%   |
| Server         | 2         | 0.63%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 290       | 91.77%  |
| Enabled  | 26        | 8.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 315       | 99.68%  |
| Yes  | 1         | 0.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 73        | 22.88%  |
| 8.01-16.0   | 67        | 21%     |
| 4.01-8.0    | 54        | 16.93%  |
| 32.01-64.0  | 45        | 14.11%  |
| 3.01-4.0    | 34        | 10.66%  |
| 64.01-256.0 | 19        | 5.96%   |
| 24.01-32.0  | 7         | 2.19%   |
| 1.01-2.0    | 7         | 2.19%   |
| 2.01-3.0    | 6         | 1.88%   |
| 0.51-1.0    | 4         | 1.25%   |
| 0.01-0.5    | 3         | 0.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 96        | 28.24%  |
| 2.01-3.0   | 76        | 22.35%  |
| 4.01-8.0   | 58        | 17.06%  |
| 3.01-4.0   | 49        | 14.41%  |
| 8.01-16.0  | 21        | 6.18%   |
| 0.01-0.5   | 18        | 5.29%   |
| 0.51-1.0   | 15        | 4.41%   |
| 16.01-24.0 | 6         | 1.76%   |
| 24.01-32.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 174       | 53.05%  |
| 2      | 97        | 29.57%  |
| 3      | 31        | 9.45%   |
| 5      | 9         | 2.74%   |
| 4      | 7         | 2.13%   |
| 0      | 5         | 1.52%   |
| 9      | 2         | 0.61%   |
| 6      | 2         | 0.61%   |
| 7      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 243       | 76.18%  |
| Yes       | 76        | 23.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 258       | 81.39%  |
| No        | 59        | 18.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 245       | 76.56%  |
| No        | 75        | 23.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 203       | 63.24%  |
| No        | 118       | 36.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Hong Kong | 316       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Central          | 172       | 51.65%  |
| Kowloon          | 15        | 4.5%    |
| Shatin           | 13        | 3.9%    |
| Tuen Mun         | 12        | 3.6%    |
| Hong Kong        | 12        | 3.6%    |
| Tseung Kwan O    | 11        | 3.3%    |
| Wanchai          | 9         | 2.7%    |
| Tung Chung       | 6         | 1.8%    |
| Tai Po           | 6         | 1.8%    |
| Ngau Wu Tok      | 6         | 1.8%    |
| Hung Hom         | 6         | 1.8%    |
| Yuen Long        | 5         | 1.5%    |
| To Kwa Wan       | 4         | 1.2%    |
| Sai Kung         | 4         | 1.2%    |
| Quarry Bay       | 3         | 0.9%    |
| Ma On Shan Tsuen | 3         | 0.9%    |
| Kowloon Bay      | 3         | 0.9%    |
| Ho Man Tin       | 3         | 0.9%    |
| Wong Tai Sin     | 2         | 0.6%    |
| Tsimshatsui      | 2         | 0.6%    |
| Tai Wan To       | 2         | 0.6%    |
| Sheung Shui      | 2         | 0.6%    |
| Sha Tin Wai      | 2         | 0.6%    |
| Man Kok          | 2         | 0.6%    |
| Kwun Hang        | 2         | 0.6%    |
| Kwu Tung         | 2         | 0.6%    |
| Fanling          | 2         | 0.6%    |
| Discovery Bay    | 2         | 0.6%    |
| Cheung Sha Lan   | 2         | 0.6%    |
| Yau Tsim Mong    | 1         | 0.3%    |
| Tsuen Wan        | 1         | 0.3%    |
| Tin Shui Wai     | 1         | 0.3%    |
| Tai Wan          | 1         | 0.3%    |
| Tai Kok Tsui     | 1         | 0.3%    |
| So Kon Po        | 1         | 0.3%    |
| Shau Kei Wan     | 1         | 0.3%    |
| Sham Shui Po     | 1         | 0.3%    |
| North Point      | 1         | 0.3%    |
| North            | 1         | 0.3%    |
| Mong Kok         | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 71        | 91     | 14.43%  |
| WDC                         | 63        | 91     | 12.8%   |
| Seagate                     | 56        | 76     | 11.38%  |
| SanDisk                     | 28        | 31     | 5.69%   |
| Toshiba                     | 26        | 33     | 5.28%   |
| Kingston                    | 21        | 23     | 4.27%   |
| Unknown                     | 19        | 23     | 3.86%   |
| Hitachi                     | 16        | 21     | 3.25%   |
| SK hynix                    | 15        | 20     | 3.05%   |
| Intel                       | 15        | 21     | 3.05%   |
| A-DATA Technology           | 14        | 20     | 2.85%   |
| Crucial                     | 13        | 21     | 2.64%   |
| HGST                        | 10        | 11     | 2.03%   |
| Silicon Motion              | 8         | 9      | 1.63%   |
| Fujitsu                     | 8         | 15     | 1.63%   |
| Phison                      | 6         | 9      | 1.22%   |
| Micron Technology           | 6         | 7      | 1.22%   |
| JMicron Technology          | 6         | 10     | 1.22%   |
| Apple                       | 6         | 12     | 1.22%   |
| Transcend                   | 5         | 5      | 1.02%   |
| Plextor                     | 4         | 5      | 0.81%   |
| LITEON                      | 4         | 4      | 0.81%   |
| HS-SSD-C100                 | 4         | 5      | 0.81%   |
| Hikvision                   | 4         | 4      | 0.81%   |
| China                       | 4         | 5      | 0.81%   |
| Unknown                     | 4         | 4      | 0.81%   |
| Team                        | 3         | 3      | 0.61%   |
| KIOXIA                      | 3         | 3      | 0.61%   |
| DOGGO                       | 3         | 3      | 0.61%   |
| BIWIN                       | 3         | 3      | 0.61%   |
| ZHITAI                      | 2         | 3      | 0.41%   |
| Netac                       | 2         | 2      | 0.41%   |
| Lite-On                     | 2         | 4      | 0.41%   |
| Lexar                       | 2         | 2      | 0.41%   |
| KingSpec                    | 2         | 3      | 0.41%   |
| Gigabyte Technology         | 2         | 5      | 0.41%   |
| Apacer                      | 2         | 7      | 0.41%   |
| Yangtze Memory Technologies | 1         | 1      | 0.2%    |
| XPG                         | 1         | 1      | 0.2%    |
| Verbatim                    | 1         | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB               | 6         | 1.13%   |
| Samsung SSD 860 EVO 1TB              | 6         | 1.13%   |
| Samsung NVMe SSD Drive 512GB         | 6         | 1.13%   |
| JMicron Generic 240GB SSD            | 5         | 0.95%   |
| Fujitsu F300 480GB                   | 5         | 0.95%   |
| Crucial CT500MX500SSD1 500GB         | 5         | 0.95%   |
| A-DATA SP550 240GB SSD               | 5         | 0.95%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 4         | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 0.76%   |
| Unknown MMC Card  64GB               | 4         | 0.76%   |
| Unknown MMC Card  32GB               | 4         | 0.76%   |
| Toshiba DT01ACA050 500GB             | 4         | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 0.76%   |
| Samsung NVMe SSD Drive 1024GB        | 4         | 0.76%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.76%   |
| Unknown                              | 4         | 0.76%   |
| WDC WD30EZRX-00D8PB0 3TB             | 3         | 0.57%   |
| Seagate ST500DM002-1BD142 500GB      | 3         | 0.57%   |
| Seagate ST3500413AS 500GB            | 3         | 0.57%   |
| Seagate ST2000LM007-1R8174 2TB       | 3         | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 0.57%   |
| SanDisk NVMe SSD Drive 512GB         | 3         | 0.57%   |
| SanDisk NVMe SSD Drive 1TB           | 3         | 0.57%   |
| Samsung SSD 970 EVO Plus 2TB         | 3         | 0.57%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.57%   |
| Samsung NVMe SSD Drive 1TB           | 3         | 0.57%   |
| Samsung MZVL2512HCJQ-00BL7 512GB     | 3         | 0.57%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.57%   |
| DOGGO DQ-60G SSD                     | 3         | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.38%   |
| WDC WDS200T2B0A 2TB SSD              | 2         | 0.38%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 2         | 0.38%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 2         | 0.38%   |
| WDC WD10SPZX-22Z10T1 1TB             | 2         | 0.38%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 2         | 0.38%   |
| Unknown SD32G  32GB                  | 2         | 0.38%   |
| Unknown MMC Card  128GB              | 2         | 0.38%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.38%   |
| Toshiba DT01ACA300 3TB               | 2         | 0.38%   |
| SK hynix SC311 SATA 128GB SSD        | 2         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 56        | 76     | 37.33%  |
| WDC                 | 38        | 61     | 25.33%  |
| Toshiba             | 23        | 30     | 15.33%  |
| Hitachi             | 16        | 21     | 10.67%  |
| HGST                | 10        | 11     | 6.67%   |
| Fujitsu             | 2         | 2      | 1.33%   |
| Unknown             | 1         | 1      | 0.67%   |
| Samsung Electronics | 1         | 1      | 0.67%   |
| JMicron Technology  | 1         | 2      | 0.67%   |
| HGST HTS            | 1         | 1      | 0.67%   |
| Apple               | 1         | 1      | 0.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 35     | 16.45%  |
| Kingston            | 14        | 15     | 9.21%   |
| Crucial             | 12        | 20     | 7.89%   |
| A-DATA Technology   | 12        | 18     | 7.89%   |
| WDC                 | 10        | 10     | 6.58%   |
| SanDisk             | 7         | 7      | 4.61%   |
| Intel               | 6         | 10     | 3.95%   |
| Transcend           | 5         | 5      | 3.29%   |
| JMicron Technology  | 5         | 8      | 3.29%   |
| Fujitsu             | 5         | 12     | 3.29%   |
| China               | 4         | 5      | 2.63%   |
| Team                | 3         | 3      | 1.97%   |
| SK hynix            | 3         | 7      | 1.97%   |
| Plextor             | 3         | 4      | 1.97%   |
| LITEON              | 3         | 3      | 1.97%   |
| DOGGO               | 3         | 3      | 1.97%   |
| ZHITAI              | 2         | 2      | 1.32%   |
| Netac               | 2         | 2      | 1.32%   |
| Micron Technology   | 2         | 3      | 1.32%   |
| Lexar               | 2         | 2      | 1.32%   |
| HS-SSD-C100         | 2         | 2      | 1.32%   |
| Hikvision           | 2         | 2      | 1.32%   |
| Apple               | 2         | 2      | 1.32%   |
| Apacer              | 2         | 7      | 1.32%   |
| Verbatim            | 1         | 2      | 0.66%   |
| Unknown (CF)        | 1         | 1      | 0.66%   |
| TO Exter            | 1         | 1      | 0.66%   |
| tigo                | 1         | 1      | 0.66%   |
| SPCC                | 1         | 1      | 0.66%   |
| RECADATA            | 1         | 1      | 0.66%   |
| Ramsta              | 1         | 1      | 0.66%   |
| PNY                 | 1         | 1      | 0.66%   |
| OCZ                 | 1         | 1      | 0.66%   |
| Dogfish             | 1         | 1      | 0.66%   |
| DGM                 | 1         | 1      | 0.66%   |
| Corsair             | 1         | 1      | 0.66%   |
| BIWIN               | 1         | 1      | 0.66%   |
| Aoluska             | 1         | 1      | 0.66%   |
| AGI                 | 1         | 1      | 0.66%   |
| Unknown             | 1         | 1      | 0.66%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 144       | 198    | 33.18%  |
| HDD     | 130       | 207    | 29.95%  |
| SSD     | 129       | 204    | 29.72%  |
| MMC     | 20        | 24     | 4.61%   |
| Unknown | 11        | 14     | 2.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 204       | 392    | 51.91%  |
| NVMe | 144       | 197    | 36.64%  |
| SAS  | 25        | 34     | 6.36%   |
| MMC  | 20        | 24     | 5.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 148       | 242    | 56.06%  |
| 0.51-1.0   | 73        | 93     | 27.65%  |
| 1.01-2.0   | 23        | 28     | 8.71%   |
| 2.01-3.0   | 9         | 14     | 3.41%   |
| 3.01-4.0   | 7         | 28     | 2.65%   |
| 4.01-10.0  | 4         | 6      | 1.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 85        | 25.37%  |
| 251-500        | 63        | 18.81%  |
| 501-1000       | 46        | 13.73%  |
| 1001-2000      | 33        | 9.85%   |
| 1-20           | 29        | 8.66%   |
| 51-100         | 29        | 8.66%   |
| More than 3000 | 15        | 4.48%   |
| 2001-3000      | 14        | 4.18%   |
| Unknown        | 12        | 3.58%   |
| 21-50          | 9         | 2.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 148       | 42.41%  |
| 101-250        | 42        | 12.03%  |
| 251-500        | 37        | 10.6%   |
| 21-50          | 36        | 10.32%  |
| 51-100         | 35        | 10.03%  |
| 501-1000       | 18        | 5.16%   |
| 1001-2000      | 12        | 3.44%   |
| Unknown        | 12        | 3.44%   |
| 2001-3000      | 6         | 1.72%   |
| More than 3000 | 3         | 0.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WD8088AADS-00M2B0 809GB               | 1         | 1      | 3.45%   |
| WDC WD30EZRX-00D8PB0 3TB                  | 1         | 1      | 3.45%   |
| WDC WD10EZEX-60WN4A1 1TB                  | 1         | 1      | 3.45%   |
| WDC WD10EZEX-00RKKA0 1TB                  | 1         | 1      | 3.45%   |
| WDC WD10EALS-00Z8A0 1TB                   | 1         | 2      | 3.45%   |
| Toshiba MK1252GSX 120GB                   | 1         | 1      | 3.45%   |
| Toshiba DT01ACA100 1TB                    | 1         | 1      | 3.45%   |
| SK hynix BC711 HFM512GD3JX013N 512GB      | 1         | 1      | 3.45%   |
| Seagate ST9500325AS 500GB                 | 1         | 1      | 3.45%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 3.45%   |
| Seagate ST3500418AS 500GB                 | 1         | 1      | 3.45%   |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 3.45%   |
| Seagate ST3160815AS 160GB                 | 1         | 1      | 3.45%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB       | 1         | 1      | 3.45%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD       | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 860 EVO 1TB       | 1         | 1      | 3.45%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD | 1         | 1      | 3.45%   |
| Kingston SA400S37480G 480GB SSD           | 1         | 1      | 3.45%   |
| Intel SSDPEKKW128G7 128GB                 | 1         | 1      | 3.45%   |
| Hitachi HTS725050A7E630 500GB             | 1         | 1      | 3.45%   |
| Hitachi HTS723216L9A360 160GB             | 1         | 1      | 3.45%   |
| Hitachi HTS542512K9SA00 120GB             | 1         | 1      | 3.45%   |
| Hitachi HTC426040G8CE00 40GB              | 1         | 1      | 3.45%   |
| Hitachi DK23AA-60 6GB                     | 1         | 1      | 3.45%   |
| HGST TOURO Mobile 500GB                   | 1         | 1      | 3.45%   |
| HGST HTS 541010A9E680 1TB                 | 1         | 1      | 3.45%   |
| DGM SSD 120GB S3-120A                     | 1         | 1      | 3.45%   |
| Crucial CT500MX500SSD1 500GB              | 1         | 2      | 3.45%   |
| Crucial CT240M500SSD1 240GB               | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 21.43%  |
| Hitachi             | 5         | 5      | 17.86%  |
| WDC                 | 4         | 6      | 14.29%  |
| Toshiba             | 2         | 2      | 7.14%   |
| Crucial             | 2         | 3      | 7.14%   |
| SK hynix            | 1         | 1      | 3.57%   |
| SanDisk             | 1         | 1      | 3.57%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| LITEON              | 1         | 1      | 3.57%   |
| Kingston            | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| HGST HTS            | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| DGM                 | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 6         | 6      | 31.58%  |
| Hitachi  | 5         | 5      | 26.32%  |
| WDC      | 4         | 6      | 21.05%  |
| Toshiba  | 2         | 2      | 10.53%  |
| HGST HTS | 1         | 1      | 5.26%   |
| HGST     | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 21     | 66.67%  |
| SSD  | 7         | 8      | 25.93%  |
| NVMe | 2         | 2      | 7.41%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 165       | 334    | 47.97%  |
| Works    | 152       | 282    | 44.19%  |
| Malfunc  | 27        | 31     | 7.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 214       | 49.2%   |
| Samsung Electronics           | 50        | 11.49%  |
| AMD                           | 43        | 9.89%   |
| SanDisk                       | 36        | 8.28%   |
| SK hynix                      | 12        | 2.76%   |
| Silicon Motion                | 12        | 2.76%   |
| ASMedia Technology            | 10        | 2.3%    |
| Phison Electronics            | 9         | 2.07%   |
| Kingston Technology Company   | 7         | 1.61%   |
| Marvell Technology Group      | 5         | 1.15%   |
| Toshiba America Info Systems  | 4         | 0.92%   |
| Micron Technology             | 4         | 0.92%   |
| ADATA Technology              | 4         | 0.92%   |
| KIOXIA                        | 3         | 0.69%   |
| Yangtze Memory Technologies   | 2         | 0.46%   |
| VIA Technologies              | 2         | 0.46%   |
| Nvidia                        | 2         | 0.46%   |
| Micron/Crucial Technology     | 2         | 0.46%   |
| Lite-On Technology            | 2         | 0.46%   |
| JMicron Technology            | 2         | 0.46%   |
| Biwin Storage Technology      | 2         | 0.46%   |
| Apple                         | 2         | 0.46%   |
| MAXIO Technology (Hangzhou)   | 1         | 0.23%   |
| LSI Logic / Symbios Logic     | 1         | 0.23%   |
| Lenovo                        | 1         | 0.23%   |
| Integrated Technology Express | 1         | 0.23%   |
| Huawei Technologies           | 1         | 0.23%   |
| Broadcom / LSI                | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 29        | 6.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 28        | 5.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 19        | 3.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 15        | 3.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 2.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 12        | 2.51%   |
| AMD 400 Series Chipset SATA Controller                                         | 12        | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 2.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 2.09%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 1.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 1.88%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 9         | 1.88%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 8         | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 1.67%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 8         | 1.67%   |
| SanDisk Non-Volatile memory controller                                         | 7         | 1.46%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 1.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.46%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 1.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.46%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 6         | 1.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.25%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 6         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 1.25%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 1.04%   |
| Intel SSD 660P Series                                                          | 5         | 1.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.04%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 0.84%   |
| Micron Non-Volatile memory controller                                          | 4         | 0.84%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 0.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4         | 0.84%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 0.84%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 4         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 222       | 52.36%  |
| NVMe | 145       | 34.2%   |
| IDE  | 30        | 7.08%   |
| RAID | 25        | 5.9%    |
| SAS  | 2         | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 245       | 77.53%  |
| AMD          | 60        | 18.99%  |
| ARM          | 5         | 1.58%   |
| Unknown      | 3         | 0.95%   |
| Phytium      | 1         | 0.32%   |
| HISILICON    | 1         | 0.32%   |
| GenuineTMx86 | 1         | 0.32%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 2.21%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.58%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 1.26%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 4         | 1.26%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.26%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.26%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 1.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.26%   |
| ARM Processor                                 | 4         | 1.26%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 1.26%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.95%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 3         | 0.95%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 3         | 0.95%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 3         | 0.95%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 0.95%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 3         | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.95%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 0.95%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 3         | 0.95%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 0.95%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.95%   |
|                                               | 3         | 0.95%   |
| Intel Xeon CPU X5675 @ 3.07GHz                | 2         | 0.63%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 0.63%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 2         | 0.63%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.63%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.63%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 0.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.63%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 2         | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.63%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 2         | 0.63%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 65        | 20.5%   |
| Intel Core i5           | 62        | 19.56%  |
| Other                   | 40        | 12.62%  |
| Intel Core i3           | 22        | 6.94%   |
| AMD Ryzen 7             | 22        | 6.94%   |
| Intel Celeron           | 21        | 6.62%   |
| AMD Ryzen 5             | 19        | 5.99%   |
| Intel Xeon              | 12        | 3.79%   |
| AMD Ryzen 9             | 7         | 2.21%   |
| Intel Pentium           | 6         | 1.89%   |
| Intel Core 2 Duo        | 5         | 1.58%   |
| Intel Atom              | 5         | 1.58%   |
| Intel Core m3           | 3         | 0.95%   |
| AMD Phenom II X4        | 3         | 0.95%   |
| Intel Pentium Gold      | 2         | 0.63%   |
| Intel Pentium Dual-Core | 2         | 0.63%   |
| Intel Pentium Dual      | 2         | 0.63%   |
| Intel Core i9           | 2         | 0.63%   |
| AMD Ryzen 7 PRO         | 2         | 0.63%   |
| Intel Pentium Silver    | 1         | 0.32%   |
| Intel Pentium M         | 1         | 0.32%   |
| Intel Genuine           | 1         | 0.32%   |
| Intel Core 2 Quad       | 1         | 0.32%   |
| Intel Core 2 Extreme    | 1         | 0.32%   |
| Intel Core 2            | 1         | 0.32%   |
| ARM BCM                 | 1         | 0.32%   |
| AMD Ryzen Threadripper  | 1         | 0.32%   |
| AMD Ryzen Embedded      | 1         | 0.32%   |
| AMD Phenom II X6        | 1         | 0.32%   |
| AMD FX                  | 1         | 0.32%   |
| AMD Athlon II X3        | 1         | 0.32%   |
| AMD Athlon 64 X2        | 1         | 0.32%   |
| AMD A8                  | 1         | 0.32%   |
| AMD A10                 | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 117       | 36.91%  |
| 2       | 89        | 28.08%  |
| 8       | 41        | 12.93%  |
| 6       | 33        | 10.41%  |
| 12      | 12        | 3.79%   |
| 1       | 9         | 2.84%   |
| 10      | 4         | 1.26%   |
| 14      | 3         | 0.95%   |
| 24      | 2         | 0.63%   |
| 16      | 2         | 0.63%   |
| 3       | 2         | 0.63%   |
| Unknown | 2         | 0.63%   |
| 64      | 1         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 309       | 97.78%  |
| 2       | 5         | 1.58%   |
| Unknown | 2         | 0.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 223       | 70.13%  |
| 1       | 93        | 29.25%  |
| Unknown | 2         | 0.63%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 295       | 93.35%  |
| 32-bit         | 9         | 2.85%   |
| Unknown        | 9         | 2.85%   |
| 64-bit         | 3         | 0.95%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 21.74%  |
| 0x206a7    | 17        | 5.28%   |
| 0x306c3    | 16        | 4.97%   |
| 0x906ea    | 14        | 4.35%   |
| 0x806e9    | 13        | 4.04%   |
| 0x806ea    | 11        | 3.42%   |
| 0x306a9    | 11        | 3.42%   |
| 0x806c1    | 9         | 2.8%    |
| 0x506e3    | 8         | 2.48%   |
| 0x90672    | 7         | 2.17%   |
| 0x40651    | 7         | 2.17%   |
| 0x806eb    | 6         | 1.86%   |
| 0x0a50000c | 6         | 1.86%   |
| 0x906ed    | 5         | 1.55%   |
| 0x906e9    | 5         | 1.55%   |
| 0x506c9    | 5         | 1.55%   |
| 0x08600106 | 5         | 1.55%   |
| 0x806ec    | 4         | 1.24%   |
| 0x406e3    | 4         | 1.24%   |
| 0x20655    | 4         | 1.24%   |
| 0x106c2    | 4         | 1.24%   |
| 0x1067a    | 4         | 1.24%   |
| 0x08701013 | 4         | 1.24%   |
| 0xa0653    | 3         | 0.93%   |
| 0xa0652    | 3         | 0.93%   |
| 0x906a3    | 3         | 0.93%   |
| 0x706e5    | 3         | 0.93%   |
| 0x6fd      | 3         | 0.93%   |
| 0x306e4    | 3         | 0.93%   |
| 0x20652    | 3         | 0.93%   |
| 0x0a201009 | 3         | 0.93%   |
| 0x08600104 | 3         | 0.93%   |
| 0x08108102 | 3         | 0.93%   |
| 0x0800820d | 3         | 0.93%   |
| 0xa0671    | 2         | 0.62%   |
| 0x806d1    | 2         | 0.62%   |
| 0x706a8    | 2         | 0.62%   |
| 0x706a1    | 2         | 0.62%   |
| 0x66a      | 2         | 0.62%   |
| 0x306d4    | 2         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 64        | 20.19%  |
| Haswell          | 29        | 9.15%   |
| Zen 2            | 22        | 6.94%   |
| Unknown          | 22        | 6.94%   |
| SandyBridge      | 21        | 6.62%   |
| IvyBridge        | 18        | 5.68%   |
| Zen 3            | 16        | 5.05%   |
| Skylake          | 16        | 5.05%   |
| TigerLake        | 12        | 3.79%   |
| CometLake        | 11        | 3.47%   |
| Westmere         | 10        | 3.15%   |
| Zen+             | 9         | 2.84%   |
| Icelake          | 9         | 2.84%   |
| Alderlake Hybrid | 9         | 2.84%   |
| Penryn           | 6         | 1.89%   |
| Goldmont         | 6         | 1.89%   |
| Core             | 6         | 1.89%   |
| K10              | 5         | 1.58%   |
| Silvermont       | 4         | 1.26%   |
| Goldmont plus    | 4         | 1.26%   |
| Broadwell        | 4         | 1.26%   |
| Bonnell          | 4         | 1.26%   |
| Zen              | 2         | 0.63%   |
| Steamroller      | 2         | 0.63%   |
| P6               | 2         | 0.63%   |
| Tremont          | 1         | 0.32%   |
| Piledriver       | 1         | 0.32%   |
| Nehalem          | 1         | 0.32%   |
| K8 Hammer        | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 190       | 50.8%   |
| Nvidia                     | 112       | 29.95%  |
| AMD                        | 66        | 17.65%  |
| Neomagic                   | 2         | 0.53%   |
| ASPEED Technology          | 2         | 0.53%   |
| S3 Graphics                | 1         | 0.27%   |
| Matrox Electronics Systems | 1         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 16        | 4.19%   |
| Intel UHD Graphics 620                                                        | 11        | 2.88%   |
| AMD Renoir                                                                    | 11        | 2.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 10        | 2.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 10        | 2.62%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 10        | 2.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 9         | 2.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 9         | 2.36%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 8         | 2.09%   |
| Intel HD Graphics 620                                                         | 7         | 1.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 1.83%   |
| Intel HD Graphics 530                                                         | 6         | 1.57%   |
| Intel HD Graphics 500                                                         | 6         | 1.57%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 6         | 1.57%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 1.31%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 5         | 1.31%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 5         | 1.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 1.31%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 4         | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 4         | 1.05%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 4         | 1.05%   |
| Nvidia GM107 [GeForce GTX 750]                                                | 4         | 1.05%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 1.05%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 4         | 1.05%   |
| Intel HD Graphics 615                                                         | 4         | 1.05%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 4         | 1.05%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 1.05%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 4         | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 4         | 1.05%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                    | 4         | 1.05%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 4         | 1.05%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 3         | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 3         | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                                | 3         | 0.79%   |
| Nvidia GK208B [GeForce GT 710]                                                | 3         | 0.79%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 3         | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 0.79%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 0.79%   |
| Intel HD Graphics 610                                                         | 3         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 138       | 43.53%  |
| 1 x Nvidia      | 60        | 18.93%  |
| 1 x AMD         | 48        | 15.14%  |
| Intel + Nvidia  | 40        | 12.62%  |
| AMD + Nvidia    | 10        | 3.15%   |
| Other           | 8         | 2.52%   |
| Intel + AMD     | 6         | 1.89%   |
| 1 x Neomagic    | 2         | 0.63%   |
| 1 x ASPEED      | 2         | 0.63%   |
| 2 x AMD         | 1         | 0.32%   |
| 1 x S3 Graphics | 1         | 0.32%   |
| Nvidia + Matrox | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 236       | 74.21%  |
| Proprietary | 61        | 19.18%  |
| Unknown     | 21        | 6.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 189       | 58.88%  |
| 1.01-2.0   | 30        | 9.35%   |
| 0.51-1.0   | 23        | 7.17%   |
| 0.01-0.5   | 23        | 7.17%   |
| 7.01-8.0   | 22        | 6.85%   |
| 3.01-4.0   | 19        | 5.92%   |
| 5.01-6.0   | 10        | 3.12%   |
| 2.01-3.0   | 2         | 0.62%   |
| 8.01-16.0  | 2         | 0.62%   |
| 16.01-24.0 | 1         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 34        | 10.27%  |
| AU Optronics            | 32        | 9.67%   |
| Samsung Electronics     | 26        | 7.85%   |
| LG Display              | 23        | 6.95%   |
| Dell                    | 21        | 6.34%   |
| Goldstar                | 20        | 6.04%   |
| Chimei Innolux          | 20        | 6.04%   |
| AOC                     | 18        | 5.44%   |
| Philips                 | 13        | 3.93%   |
| Sharp                   | 9         | 2.72%   |
| Ancor Communications    | 9         | 2.72%   |
| Unknown                 | 7         | 2.11%   |
| Acer                    | 7         | 2.11%   |
| Lenovo                  | 6         | 1.81%   |
| AMO                     | 6         | 1.81%   |
| BenQ                    | 5         | 1.51%   |
| Apple                   | 5         | 1.51%   |
| ViewSonic               | 4         | 1.21%   |
| RTK                     | 4         | 1.21%   |
| Hewlett-Packard         | 4         | 1.21%   |
| IPS                     | 3         | 0.91%   |
| ASUSTek Computer        | 3         | 0.91%   |
| Mi                      | 2         | 0.6%    |
| LG Philips              | 2         | 0.6%    |
| InfoVision              | 2         | 0.6%    |
| HSO                     | 2         | 0.6%    |
| CSO                     | 2         | 0.6%    |
| CPT                     | 2         | 0.6%    |
| Chi Mei Optoelectronics | 2         | 0.6%    |
| AUS                     | 2         | 0.6%    |
| Xiaomi                  | 1         | 0.3%    |
| Xiangye                 | 1         | 0.3%    |
| Unknown (DAE)           | 1         | 0.3%    |
| Unknown (AAA)           | 1         | 0.3%    |
| TUO                     | 1         | 0.3%    |
| Toshiba                 | 1         | 0.3%    |
| TMX                     | 1         | 0.3%    |
| TCT                     | 1         | 0.3%    |
| Sony                    | 1         | 0.3%    |
| SKY                     | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AMO HS241P AMO2800 3840x2160 620x350mm 28.0-inch                      | 4         | 1.18%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 3         | 0.89%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 3         | 0.89%   |
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 0.89%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.89%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 3         | 0.89%   |
| AOC Q2790 AOC2790 2560x1440 597x336mm 27.0-inch                       | 3         | 0.89%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 3         | 0.89%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.59%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 0.59%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.59%   |
| RTK 7911D RTK2A3B 720x1280 720x1280mm 57.8-inch                       | 2         | 0.59%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 2         | 0.59%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 2         | 0.59%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch              | 2         | 0.59%   |
| IPS LCD Monitor IPS2700 2560x1440 597x336mm 27.0-inch                 | 2         | 0.59%   |
| HSO B2431M HSO2431 3840x2160 520x290mm 23.4-inch                      | 2         | 0.59%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.59%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.59%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2         | 0.59%   |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                   | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 2         | 0.59%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 0.59%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                 | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO233D 1920x1080 309x174mm 14.0-inch        | 2         | 0.59%   |
| AOC G2490W1G4 AOC2490 1920x1080 527x296mm 23.8-inch                   | 2         | 0.59%   |
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                    | 1         | 0.3%    |
| Xiangye XE2400 XYE2380 3840x2160 520x310mm 23.8-inch                  | 1         | 0.3%    |
| ViewSonic VX2260WM VSCFC21 1920x1080 477x268mm 21.5-inch              | 1         | 0.3%    |
| ViewSonic VX2239 SERIES VSC5225 1920x1080 480x270mm 21.7-inch         | 1         | 0.3%    |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 1         | 0.3%    |
| ViewSonic VA1616wSERIES VSC0021 1366x768 348x197mm 15.7-inch          | 1         | 0.3%    |
| Unknown LCD Monitor ROW AAA                                           | 1         | 0.3%    |
| Unknown LCD Monitor hp f1523 1024x768                                 | 1         | 0.3%    |
| Unknown LCD Monitor GBT G32QC A 2560x1440                             | 1         | 0.3%    |
| Unknown LCD Monitor FST V22T-1R LED 1920x1080                         | 1         | 0.3%    |
| Unknown (DAE) L32S6550BN DAE0010 1366x768 698x392mm 31.5-inch         | 1         | 0.3%    |
| Unknown (AAA) U270 AAA2700 3840x2160 596x335mm 26.9-inch              | 1         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 145       | 46.62%  |
| 3840x2160 (4K)     | 39        | 12.54%  |
| 1366x768 (WXGA)    | 27        | 8.68%   |
| 2560x1440 (QHD)    | 20        | 6.43%   |
| 1440x900 (WXGA+)   | 10        | 3.22%   |
| 1600x900 (HD+)     | 7         | 2.25%   |
| Unknown            | 7         | 2.25%   |
| 2560x1600          | 6         | 1.93%   |
| 1680x1050 (WSXGA+) | 5         | 1.61%   |
| 1280x800 (WXGA)    | 5         | 1.61%   |
| 3440x1440          | 4         | 1.29%   |
| 3840x1080          | 3         | 0.96%   |
| 2880x1800          | 3         | 0.96%   |
| 1360x768           | 3         | 0.96%   |
| 3840x2400          | 2         | 0.64%   |
| 2560x1080          | 2         | 0.64%   |
| 1920x1200 (WUXGA)  | 2         | 0.64%   |
| 1280x1024 (SXGA)   | 2         | 0.64%   |
| 1024x768 (XGA)     | 2         | 0.64%   |
| 5120x1440          | 1         | 0.32%   |
| 4480x1440          | 1         | 0.32%   |
| 3840x1600          | 1         | 0.32%   |
| 3520x1080          | 1         | 0.32%   |
| 3456x2160          | 1         | 0.32%   |
| 3200x2000          | 1         | 0.32%   |
| 3200x1800 (QHD+)   | 1         | 0.32%   |
| 3200x1080          | 1         | 0.32%   |
| 2880x1920          | 1         | 0.32%   |
| 2400x1600          | 1         | 0.32%   |
| 2304x1440          | 1         | 0.32%   |
| 2256x1504          | 1         | 0.32%   |
| 2240x1400          | 1         | 0.32%   |
| 2160x1440          | 1         | 0.32%   |
| 2160x1350          | 1         | 0.32%   |
| 1024x600           | 1         | 0.32%   |
| 1024x576           | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 59        | 18.15%  |
| 13      | 37        | 11.38%  |
| 14      | 31        | 9.54%   |
| 23      | 28        | 8.62%   |
| 21      | 28        | 8.62%   |
| 27      | 23        | 7.08%   |
| Unknown | 22        | 6.77%   |
| 24      | 19        | 5.85%   |
| 31      | 12        | 3.69%   |
| 12      | 10        | 3.08%   |
| 18      | 9         | 2.77%   |
| 17      | 6         | 1.85%   |
| 34      | 5         | 1.54%   |
| 28      | 5         | 1.54%   |
| 19      | 5         | 1.54%   |
| 40      | 3         | 0.92%   |
| 22      | 3         | 0.92%   |
| 10      | 3         | 0.92%   |
| 57      | 2         | 0.62%   |
| 25      | 2         | 0.62%   |
| 16      | 2         | 0.62%   |
| 84      | 1         | 0.31%   |
| 72      | 1         | 0.31%   |
| 65      | 1         | 0.31%   |
| 58      | 1         | 0.31%   |
| 52      | 1         | 0.31%   |
| 48      | 1         | 0.31%   |
| 37      | 1         | 0.31%   |
| 26      | 1         | 0.31%   |
| 20      | 1         | 0.31%   |
| 11      | 1         | 0.31%   |
| 8       | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 107       | 33.54%  |
| 501-600     | 68        | 21.32%  |
| 401-500     | 44        | 13.79%  |
| 201-300     | 36        | 11.29%  |
| Unknown     | 22        | 6.9%    |
| 601-700     | 18        | 5.64%   |
| 701-800     | 7         | 2.19%   |
| 351-400     | 6         | 1.88%   |
| 801-900     | 4         | 1.25%   |
| 1001-1500   | 4         | 1.25%   |
| 1501-2000   | 2         | 0.63%   |
| 101-200     | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 223       | 75.08%  |
| 16/10   | 39        | 13.13%  |
| Unknown | 18        | 6.06%   |
| 21/9    | 6         | 2.02%   |
| 3/2     | 4         | 1.35%   |
| 6/5     | 2         | 0.67%   |
| 0.56    | 2         | 0.67%   |
| 4/3     | 1         | 0.34%   |
| 32/9    | 1         | 0.34%   |
| 0.62    | 1         | 0.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 65        | 20.19%  |
| 101-110        | 59        | 18.32%  |
| 81-90          | 51        | 15.84%  |
| 301-350        | 29        | 9.01%   |
| Unknown        | 22        | 6.83%   |
| 71-80          | 18        | 5.59%   |
| 351-500        | 18        | 5.59%   |
| 151-200        | 16        | 4.97%   |
| 61-70          | 9         | 2.8%    |
| More than 1000 | 7         | 2.17%   |
| 251-300        | 6         | 1.86%   |
| 141-150        | 5         | 1.55%   |
| 121-130        | 5         | 1.55%   |
| 501-1000       | 4         | 1.24%   |
| 41-50          | 3         | 0.93%   |
| 51-60          | 1         | 0.31%   |
| 1-40           | 1         | 0.31%   |
| 131-140        | 1         | 0.31%   |
| 111-120        | 1         | 0.31%   |
| 91-100         | 1         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 86        | 27.13%  |
| 51-100        | 84        | 26.5%   |
| 101-120       | 64        | 20.19%  |
| 161-240       | 36        | 11.36%  |
| Unknown       | 22        | 6.94%   |
| More than 240 | 17        | 5.36%   |
| 1-50          | 8         | 2.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 253       | 79.31%  |
| 2     | 46        | 14.42%  |
| 0     | 18        | 5.64%   |
| 3     | 2         | 0.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 186       | 41.15%  |
| Realtek Semiconductor    | 150       | 33.19%  |
| Qualcomm Atheros         | 33        | 7.3%    |
| Broadcom                 | 20        | 4.42%   |
| MediaTek                 | 10        | 2.21%   |
| TP-Link                  | 8         | 1.77%   |
| Ralink Technology        | 8         | 1.77%   |
| ASIX Electronics         | 5         | 1.11%   |
| Qualcomm                 | 3         | 0.66%   |
| Microsoft                | 3         | 0.66%   |
| Marvell Technology Group | 3         | 0.66%   |
| Broadcom Limited         | 3         | 0.66%   |
| Xiaomi                   | 2         | 0.44%   |
| SEGGER                   | 2         | 0.44%   |
| Huawei Technologies      | 2         | 0.44%   |
| Texas Instruments        | 1         | 0.22%   |
| Ralink                   | 1         | 0.22%   |
| PEAK-System Technik      | 1         | 0.22%   |
| OPPO Electronics         | 1         | 0.22%   |
| Nvidia                   | 1         | 0.22%   |
| NetGear                  | 1         | 0.22%   |
| National Semiconductor   | 1         | 0.22%   |
| Lenovo                   | 1         | 0.22%   |
| ICS Advent               | 1         | 0.22%   |
| Fitbit                   | 1         | 0.22%   |
| DisplayLink              | 1         | 0.22%   |
| D-Link                   | 1         | 0.22%   |
| Belkin Components        | 1         | 0.22%   |
| Apple                    | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 100       | 18.28%  |
| Intel Wi-Fi 6 AX200                                                     | 29        | 5.3%    |
| Intel Wireless 8265 / 8275                                              | 13        | 2.38%   |
| Intel I211 Gigabit Network Connection                                   | 13        | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 12        | 2.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 12        | 2.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 10        | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                       | 9         | 1.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 1.65%   |
| Intel Wireless 7265                                                     | 8         | 1.46%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 1.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 1.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1.28%   |
| Intel Wireless 7260                                                     | 7         | 1.28%   |
| Intel Ethernet Connection (4) I219-V                                    | 7         | 1.28%   |
| Intel Ethernet Connection (2) I219-V                                    | 7         | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.28%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 1.1%    |
| Intel 82579V Gigabit Network Connection                                 | 6         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.91%   |
| Realtek 802.11n WLAN Adapter                                            | 5         | 0.91%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.91%   |
| Intel Wireless 8260                                                     | 5         | 0.91%   |
| Intel Ethernet Controller I225-V                                        | 5         | 0.91%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 5         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 0.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.73%   |
| Intel Ethernet Connection (11) I219-V                                   | 4         | 0.73%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.55%   |
| Microsoft XBOX ACC                                                      | 3         | 0.55%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.55%   |
| Intel I350 Gigabit Network Connection                                   | 3         | 0.55%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 148       | 57.36%  |
| Realtek Semiconductor | 30        | 11.63%  |
| Qualcomm Atheros      | 27        | 10.47%  |
| Broadcom              | 16        | 6.2%    |
| MediaTek              | 10        | 3.88%   |
| TP-Link               | 8         | 3.1%    |
| Ralink Technology     | 8         | 3.1%    |
| Qualcomm              | 3         | 1.16%   |
| Microsoft             | 3         | 1.16%   |
| Texas Instruments     | 1         | 0.39%   |
| Ralink                | 1         | 0.39%   |
| NetGear               | 1         | 0.39%   |
| Broadcom Limited      | 1         | 0.39%   |
| Belkin Components     | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 29        | 11.2%   |
| Intel Wireless 8265 / 8275                                              | 13        | 5.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 10        | 3.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 3.47%   |
| Intel Wireless 7265                                                     | 8         | 3.09%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 3.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.7%    |
| Intel Wireless 7260                                                     | 7         | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 2.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.93%   |
| Realtek 802.11n WLAN Adapter                                            | 5         | 1.93%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.93%   |
| Intel Wireless 8260                                                     | 5         | 1.93%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 5         | 1.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.16%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.16%   |
| Microsoft XBOX ACC                                                      | 3         | 1.16%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.16%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.16%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.77%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.77%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 2         | 0.77%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)               | 2         | 0.77%   |
| Realtek Realtek Network controller                                      | 2         | 0.77%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.77%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.77%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 138       | 50.36%  |
| Intel                    | 99        | 36.13%  |
| Qualcomm Atheros         | 9         | 3.28%   |
| Broadcom                 | 6         | 2.19%   |
| ASIX Electronics         | 5         | 1.82%   |
| Marvell Technology Group | 3         | 1.09%   |
| Xiaomi                   | 2         | 0.73%   |
| Huawei Technologies      | 2         | 0.73%   |
| Broadcom Limited         | 2         | 0.73%   |
| OPPO Electronics         | 1         | 0.36%   |
| Nvidia                   | 1         | 0.36%   |
| National Semiconductor   | 1         | 0.36%   |
| Lenovo                   | 1         | 0.36%   |
| ICS Advent               | 1         | 0.36%   |
| DisplayLink              | 1         | 0.36%   |
| D-Link                   | 1         | 0.36%   |
| Apple                    | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 100       | 35.46%  |
| Intel I211 Gigabit Network Connection                             | 13        | 4.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 4.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 4.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 3.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.84%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 2.48%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 2.48%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 2.13%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 2.13%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.42%   |
| Intel Ethernet Connection (11) I219-V                             | 4         | 1.42%   |
| Intel I350 Gigabit Network Connection                             | 3         | 1.06%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.06%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.06%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.06%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.71%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2         | 0.71%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.71%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.71%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.71%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.71%   |
| Realtek USB 10/100 LAN                                            | 1         | 0.35%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.35%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.35%   |
| OPPO RMX3263                                                      | 1         | 0.35%   |
| Nvidia MCP65 Ethernet                                             | 1         | 0.35%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1         | 0.35%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 257       | 50.59%  |
| WiFi     | 245       | 48.23%  |
| Modem    | 3         | 0.59%   |
| Unknown  | 3         | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 184       | 55.09%  |
| Ethernet | 150       | 44.91%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 163       | 51.1%   |
| 1     | 132       | 41.38%  |
| 0     | 15        | 4.7%    |
| 3     | 4         | 1.25%   |
| 4     | 3         | 0.94%   |
| 8     | 1         | 0.31%   |
| 7     | 1         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 312       | 98.11%  |
| Yes  | 6         | 1.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 126       | 61.17%  |
| Cambridge Silicon Radio         | 16        | 7.77%   |
| Realtek Semiconductor           | 8         | 3.88%   |
| Qualcomm Atheros Communications | 8         | 3.88%   |
| Foxconn / Hon Hai               | 8         | 3.88%   |
| Broadcom                        | 8         | 3.88%   |
| Lite-On Technology              | 5         | 2.43%   |
| Apple                           | 5         | 2.43%   |
| IMC Networks                    | 4         | 1.94%   |
| Realtek                         | 3         | 1.46%   |
| Hewlett-Packard                 | 3         | 1.46%   |
| Foxconn International           | 2         | 0.97%   |
| Dell                            | 2         | 0.97%   |
| ASUSTek Computer                | 2         | 0.97%   |
| Taiyo Yuden                     | 1         | 0.49%   |
| SINO WEALTH                     | 1         | 0.49%   |
| Micro Star International        | 1         | 0.49%   |
| MediaTek                        | 1         | 0.49%   |
| Fujitsu                         | 1         | 0.49%   |
| Askey Computer                  | 1         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 33        | 16.02%  |
| Intel AX200 Bluetooth                               | 29        | 14.08%  |
| Intel AX201 Bluetooth                               | 24        | 11.65%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 7.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16        | 7.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 4.37%   |
| Realtek Bluetooth Radio                             | 8         | 3.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.43%   |
| Intel Bluetooth Device                              | 5         | 2.43%   |
| Intel AX210 Bluetooth                               | 4         | 1.94%   |
| Realtek Bluetooth Radio                             | 3         | 1.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.46%   |
| IMC Networks Wireless_Device                        | 3         | 1.46%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.46%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.97%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.97%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.97%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.97%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.97%   |
| ASUS Bluetooth Radio                                | 2         | 0.97%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.97%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.97%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.49%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1         | 0.49%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.49%   |
| Micro Star International Bluetooth Dongle           | 1         | 0.49%   |
| MediaTek Wireless_Device                            | 1         | 0.49%   |
| Lite-On Bluetooth Radio                             | 1         | 0.49%   |
| Lite-On Bluetooth Device                            | 1         | 0.49%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.49%   |
| IMC Networks Bluetooth Device                       | 1         | 0.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.49%   |
| Fujitsu Bluetooth Device                            | 1         | 0.49%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.49%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.49%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.49%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 237       | 55.5%   |
| Nvidia                               | 83        | 19.44%  |
| AMD                                  | 71        | 16.63%  |
| C-Media Electronics                  | 9         | 2.11%   |
| Logitech                             | 3         | 0.7%    |
| FiiO Electronics Technology          | 3         | 0.7%    |
| Generalplus Technology               | 2         | 0.47%   |
| Focusrite-Novation                   | 2         | 0.47%   |
| ESS Technology                       | 2         | 0.47%   |
| Creative Labs                        | 2         | 0.47%   |
| XMOS                                 | 1         | 0.23%   |
| Winbond Electronics                  | 1         | 0.23%   |
| VIA Technologies                     | 1         | 0.23%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.23%   |
| Texas Instruments                    | 1         | 0.23%   |
| Sony                                 | 1         | 0.23%   |
| SAVITECH                             | 1         | 0.23%   |
| Realtek Semiconductor                | 1         | 0.23%   |
| Lynx                                 | 1         | 0.23%   |
| iCreate Technologies                 | 1         | 0.23%   |
| BY EDIFIER                           | 1         | 0.23%   |
| AudioQuest                           | 1         | 0.23%   |
| Apple                                | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 31        | 6.24%   |
| Intel Sunrise Point-LP HD Audio                                            | 29        | 5.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19        | 3.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19        | 3.82%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 3.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17        | 3.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16        | 3.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 3.02%   |
| AMD Starship/Matisse HD Audio Controller                                   | 15        | 3.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 2.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 2.41%   |
| Nvidia GP106 High Definition Audio Controller                              | 9         | 1.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 1.81%   |
| Intel Alder Lake-S HD Audio Controller                                     | 8         | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.61%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 1.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.41%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 1.41%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.41%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.41%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 1.21%   |
| Nvidia GM206 High Definition Audio Controller                              | 6         | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 1.21%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.21%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 6         | 1.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 1.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.01%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.01%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5         | 1.01%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.8%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.8%    |
| Intel Comet Lake PCH-V cAVS                                                | 4         | 0.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 20.56%  |
| SK hynix            | 42        | 19.63%  |
| Kingston            | 30        | 14.02%  |
| Micron Technology   | 21        | 9.81%   |
| Unknown             | 16        | 7.48%   |
| Corsair             | 13        | 6.07%   |
| A-DATA Technology   | 9         | 4.21%   |
| Crucial             | 7         | 3.27%   |
| Unknown             | 7         | 3.27%   |
| G.Skill             | 4         | 1.87%   |
| Team                | 3         | 1.4%    |
| Elpida              | 3         | 1.4%    |
| Unknown (ABCD)      | 2         | 0.93%   |
| Ramaxel Technology  | 2         | 0.93%   |
| Nanya Technology    | 2         | 0.93%   |
| Kingmax             | 2         | 0.93%   |
| Transcend           | 1         | 0.47%   |
| tigo                | 1         | 0.47%   |
| Lenovo              | 1         | 0.47%   |
| Juhor               | 1         | 0.47%   |
| GLOWAY              | 1         | 0.47%   |
| Essencore Limited   | 1         | 0.47%   |
| Apacer              | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 7         | 3.1%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 4         | 1.77%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 4         | 1.77%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 2         | 0.88%   |
| Unknown RAM Module 256MB SODIMM DRAM                         | 2         | 0.88%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 2         | 0.88%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                 | 2         | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.88%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 2         | 0.88%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.88%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 0.88%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 0.88%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 2         | 0.88%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 2         | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.88%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.88%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s        | 2         | 0.88%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.88%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s               | 2         | 0.88%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s          | 2         | 0.88%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s      | 2         | 0.88%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s        | 2         | 0.88%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 2         | 0.88%   |
| Corsair RAM CM4X16GC3600C18K2D 16GB DIMM DDR4 3600MT/s       | 2         | 0.88%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                     | 2         | 0.88%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                 | 1         | 0.44%   |
| Unknown RAM Module 512MB SODIMM DRAM                         | 1         | 0.44%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1         | 0.44%   |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s                  | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 333MT/s                   | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR                            | 1         | 0.44%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.44%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 0.44%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                | 1         | 0.44%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                       | 1         | 0.44%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s            | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 101       | 54.01%  |
| DDR3    | 41        | 21.93%  |
| LPDDR3  | 12        | 6.42%   |
| DDR2    | 9         | 4.81%   |
| LPDDR4  | 8         | 4.28%   |
| SDRAM   | 5         | 2.67%   |
| Unknown | 4         | 2.14%   |
| DRAM    | 3         | 1.6%    |
| DDR5    | 2         | 1.07%   |
| LPDDR5  | 1         | 0.53%   |
| DDR     | 1         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 46.24%  |
| DIMM         | 76        | 40.86%  |
| Row Of Chips | 23        | 12.37%  |
| Unknown      | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 72        | 35.64%  |
| 4096  | 43        | 21.29%  |
| 16384 | 39        | 19.31%  |
| 2048  | 21        | 10.4%   |
| 32768 | 15        | 7.43%   |
| 1024  | 6         | 2.97%   |
| 256   | 2         | 0.99%   |
| 64    | 2         | 0.99%   |
| 512   | 1         | 0.5%    |
| 232   | 1         | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 35        | 17.68%  |
| 2667    | 34        | 17.17%  |
| 1600    | 30        | 15.15%  |
| 2133    | 14        | 7.07%   |
| 2400    | 13        | 6.57%   |
| 1333    | 9         | 4.55%   |
| 3600    | 6         | 3.03%   |
| Unknown | 6         | 3.03%   |
| 2666    | 5         | 2.53%   |
| 1867    | 5         | 2.53%   |
| 4267    | 4         | 2.02%   |
| 667     | 4         | 2.02%   |
| 4800    | 3         | 1.52%   |
| 3466    | 3         | 1.52%   |
| 3266    | 2         | 1.01%   |
| 3000    | 2         | 1.01%   |
| 1334    | 2         | 1.01%   |
| 800     | 2         | 1.01%   |
| 533     | 2         | 1.01%   |
| 8400    | 1         | 0.51%   |
| 6400    | 1         | 0.51%   |
| 4266    | 1         | 0.51%   |
| 4199    | 1         | 0.51%   |
| 3866    | 1         | 0.51%   |
| 3800    | 1         | 0.51%   |
| 3733    | 1         | 0.51%   |
| 3400    | 1         | 0.51%   |
| 3007    | 1         | 0.51%   |
| 2933    | 1         | 0.51%   |
| 1866    | 1         | 0.51%   |
| 1800    | 1         | 0.51%   |
| 1067    | 1         | 0.51%   |
| 1066    | 1         | 0.51%   |
| 975     | 1         | 0.51%   |
| 333     | 1         | 0.51%   |
| 200     | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Xiaomi             | 1         | 20%     |
| Hewlett-Packard    | 1         | 20%     |
| Fuji Xerox         | 1         | 20%     |
| Canon              | 1         | 20%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                       | Computers | Percent |
|-----------------------------|-----------|---------|
| Xiaomi MiMouse 2            | 1         | 20%     |
| HP LaserJet P2035           | 1         | 20%     |
| Fuji Xerox DocuPrint P158 b | 1         | 20%     |
| Canon MP160                 | 1         | 20%     |
| Brother HL-L2320D series    | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 19.25%  |
| IMC Networks                           | 15        | 9.32%   |
| Acer                                   | 14        | 8.7%    |
| Microdia                               | 13        | 8.07%   |
| Logitech                               | 10        | 6.21%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 5.59%   |
| Realtek Semiconductor                  | 7         | 4.35%   |
| Apple                                  | 7         | 4.35%   |
| Luxvisions Innotech Limited            | 6         | 3.73%   |
| Syntek                                 | 5         | 3.11%   |
| Sunplus Innovation Technology          | 5         | 3.11%   |
| Suyin                                  | 3         | 1.86%   |
| Silicon Motion                         | 3         | 1.86%   |
| Quanta                                 | 3         | 1.86%   |
| Alcor Micro                            | 3         | 1.86%   |
| Lite-On Technology                     | 2         | 1.24%   |
| Importek                               | 2         | 1.24%   |
| eMPIA Technology                       | 2         | 1.24%   |
| Cubeternet                             | 2         | 1.24%   |
| Xiaomi                                 | 1         | 0.62%   |
| WaveRider Communications               | 1         | 0.62%   |
| USB Camera                             | 1         | 0.62%   |
| Unknown                                | 1         | 0.62%   |
| Tripath Technology                     | 1         | 0.62%   |
| Sonix Technology                       | 1         | 0.62%   |
| SN0002                                 | 1         | 0.62%   |
| Ricoh                                  | 1         | 0.62%   |
| Primax Electronics                     | 1         | 0.62%   |
| Nokia Mobile Phones                    | 1         | 0.62%   |
| Nebraska Furniture Mart                | 1         | 0.62%   |
| Microsoft                              | 1         | 0.62%   |
| lihappe8                               | 1         | 0.62%   |
| Google                                 | 1         | 0.62%   |
| Genesys Logic                          | 1         | 0.62%   |
| Essential Products                     | 1         | 0.62%   |
| DLTCT0A9IH1FFL                         | 1         | 0.62%   |
| ARC International                      | 1         | 0.62%   |
| A4Tech                                 | 1         | 0.62%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 10        | 6.1%    |
| Microdia Integrated_Webcam_HD                                              | 9         | 5.49%   |
| IMC Networks Integrated Camera                                             | 7         | 4.27%   |
| Acer Integrated Camera                                                     | 6         | 3.66%   |
| Syntek Integrated Camera                                                   | 5         | 3.05%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 3.05%   |
| Chicony FJ Camera                                                          | 5         | 3.05%   |
| Logitech Webcam C270                                                       | 4         | 2.44%   |
| Chicony HD Webcam                                                          | 4         | 2.44%   |
| Apple FaceTime HD Camera (Built-in)                                        | 4         | 2.44%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 1.83%   |
| Alcor Micro USB 2.0 Camera                                                 | 3         | 1.83%   |
| Sunplus HD WebCam                                                          | 2         | 1.22%   |
| Microdia USB 2.0 Camera                                                    | 2         | 1.22%   |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 1.22%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 1.22%   |
| Logitech B525 HD Webcam                                                    | 2         | 1.22%   |
| Lite-On Integrated Camera                                                  | 2         | 1.22%   |
| Importek FJ Camera                                                         | 2         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 2         | 1.22%   |
| Apple iPhone5/5C/5S/6                                                      | 2         | 1.22%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 1.22%   |
| Acer Lenovo EasyCamera                                                     | 2         | 1.22%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                                         | 1         | 0.61%   |
| WaveRider USB 2.0 Camera                                                   | 1         | 0.61%   |
| USB Camera USB Camera                                                      | 1         | 0.61%   |
| Unknown Integrated RGB Camera                                              | 1         | 0.61%   |
| Tripath PC Camera                                                          | 1         | 0.61%   |
| Suyin Integrated Webcam                                                    | 1         | 0.61%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 0.61%   |
| Suyin HP Truevision HD                                                     | 1         | 0.61%   |
| Sunplus ZCF-171115                                                         | 1         | 0.61%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 0.61%   |
| Sunplus HP Universal Camera                                                | 1         | 0.61%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 0.61%   |
| SN0002 2K USB Camera                                                       | 1         | 0.61%   |
| Silicon Motion Lenovo EasyCamera                                           | 1         | 0.61%   |
| Silicon Motion 720p HD Camera                                              | 1         | 0.61%   |
| Silicon Motion 300k Pixel Camera                                           | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 17        | 44.74%  |
| Validity Sensors           | 8         | 21.05%  |
| Shenzhen Goodix Technology | 6         | 15.79%  |
| AuthenTec                  | 3         | 7.89%   |
| Upek                       | 2         | 5.26%   |
| Samsung Electronics        | 1         | 2.63%   |
| LighTuning Technology      | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader       | 7         | 18.42%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 13.16%  |
| Validity Sensors Synaptics WBDI                        | 3         | 7.89%   |
| Unknown                                                | 3         | 7.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 5.26%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 5.26%   |
| Shenzhen Goodix FingerPrint                            | 2         | 5.26%   |
| AuthenTec Fingerprint Sensor                           | 2         | 5.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.63%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 2.63%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 2.63%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 2.63%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.63%   |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1         | 2.63%   |
| Synaptics  WBDI                                        | 1         | 2.63%   |
| Samsung Fingerprint Device                             | 1         | 2.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.63%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 2.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 31.25%  |
| Upek                  | 3         | 18.75%  |
| Lenovo                | 2         | 12.5%   |
| Alcor Micro           | 2         | 12.5%   |
| Advanced Card Systems | 2         | 12.5%   |
| Yubico.com            | 1         | 6.25%   |
| O2 Micro              | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 18.75%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 12.5%   |
| Broadcom 5880                                                                | 2         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 12.5%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 2         | 12.5%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 6.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 6.25%   |
| Broadcom 58200                                                               | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 215       | 65.95%  |
| 1     | 83        | 25.46%  |
| 2     | 19        | 5.83%   |
| 4     | 4         | 1.23%   |
| 3     | 4         | 1.23%   |
| 5     | 1         | 0.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 36        | 24%     |
| Fingerprint reader       | 35        | 23.33%  |
| Net/wireless             | 23        | 15.33%  |
| Chipcard                 | 15        | 10%     |
| Multimedia controller    | 11        | 7.33%   |
| Communication controller | 11        | 7.33%   |
| Bluetooth                | 4         | 2.67%   |
| Sound                    | 3         | 2%      |
| Unassigned class         | 2         | 1.33%   |
| Storage                  | 2         | 1.33%   |
| Net/ethernet             | 2         | 1.33%   |
| Camera                   | 2         | 1.33%   |
| Storage/raid             | 1         | 0.67%   |
| Storage/ata              | 1         | 0.67%   |
| Network                  | 1         | 0.67%   |
| Card reader              | 1         | 0.67%   |

