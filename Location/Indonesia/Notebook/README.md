Linux in Indonesia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

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

Total: 1402

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T440 20B7A1P700    | [d49a8fe4d4](https://linux-hardware.org/?probe=d49a8fe4d4) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [f1c9eab3f4](https://linux-hardware.org/?probe=f1c9eab3f4) | Dec 24, 2023 |
| ASUSTek       | X441BA                      | [04e5c55b92](https://linux-hardware.org/?probe=04e5c55b92) | Dec 23, 2023 |
| Dell          | Latitude E6400              | [67d4d37a04](https://linux-hardware.org/?probe=67d4d37a04) | Dec 20, 2023 |
| Lenovo        | ThinkPad T590 20N5S44300    | [5a90e712d1](https://linux-hardware.org/?probe=5a90e712d1) | Dec 19, 2023 |
| Lenovo        | V14-ADA 82C6                | [ec237cc638](https://linux-hardware.org/?probe=ec237cc638) | Dec 19, 2023 |
| Medion        | S17403                      | [250e479ad5](https://linux-hardware.org/?probe=250e479ad5) | Dec 18, 2023 |
| ASUSTek       | UX490UAR                    | [e8aa69b910](https://linux-hardware.org/?probe=e8aa69b910) | Dec 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b7194dbbb8](https://linux-hardware.org/?probe=b7194dbbb8) | Dec 15, 2023 |
| Acer          | Aspire E5-411G              | [f4af1a07e3](https://linux-hardware.org/?probe=f4af1a07e3) | Dec 15, 2023 |
| Lenovo        | ThinkPad L330 34701V0       | [d418989434](https://linux-hardware.org/?probe=d418989434) | Dec 15, 2023 |
| Samsung       | 300E5E/300E4E/300E5V/300... | [e7d5f85bea](https://linux-hardware.org/?probe=e7d5f85bea) | Dec 13, 2023 |
| Dell          | Latitude E7240              | [4fcd011c61](https://linux-hardware.org/?probe=4fcd011c61) | Dec 13, 2023 |
| Lenovo        | V110-14IAP 80TF             | [e7bbe1d5e7](https://linux-hardware.org/?probe=e7bbe1d5e7) | Dec 10, 2023 |
| Acer          | Aspire E5-411G              | [72c0c4e3a0](https://linux-hardware.org/?probe=72c0c4e3a0) | Dec 09, 2023 |
| Dell          | Latitude E6400              | [0f4aeac8ca](https://linux-hardware.org/?probe=0f4aeac8ca) | Dec 09, 2023 |
| HP            | EliteBook 745 G6            | [29a2194396](https://linux-hardware.org/?probe=29a2194396) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1b3b476186](https://linux-hardware.org/?probe=1b3b476186) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [58547d36b7](https://linux-hardware.org/?probe=58547d36b7) | Dec 06, 2023 |
| Acer          | Aspire A314-22              | [daa41db960](https://linux-hardware.org/?probe=daa41db960) | Dec 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [becdc5222d](https://linux-hardware.org/?probe=becdc5222d) | Dec 05, 2023 |
| ASUSTek       | X441BA                      | [272c82d8eb](https://linux-hardware.org/?probe=272c82d8eb) | Dec 05, 2023 |
| HP            | Laptop 14-em0xxx            | [b3a0f94dfd](https://linux-hardware.org/?probe=b3a0f94dfd) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | [b3bc756e27](https://linux-hardware.org/?probe=b3bc756e27) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | [9af224bc40](https://linux-hardware.org/?probe=9af224bc40) | Dec 04, 2023 |
| ASUSTek       | X441NA                      | [9a4c0266e8](https://linux-hardware.org/?probe=9a4c0266e8) | Dec 02, 2023 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [f43aaf1d39](https://linux-hardware.org/?probe=f43aaf1d39) | Nov 29, 2023 |
| HP            | EliteBook 840 G2            | [12e26441e1](https://linux-hardware.org/?probe=12e26441e1) | Nov 27, 2023 |
| Valve         | Jupiter                     | [a6240c8d6a](https://linux-hardware.org/?probe=a6240c8d6a) | Nov 20, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B30... | [5685f17122](https://linux-hardware.org/?probe=5685f17122) | Nov 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [95624a1d82](https://linux-hardware.org/?probe=95624a1d82) | Nov 18, 2023 |
| Dell          | XPS 9320                    | [04760461ba](https://linux-hardware.org/?probe=04760461ba) | Nov 17, 2023 |
| Acer          | Nitro AN515-57              | [39c7028c1e](https://linux-hardware.org/?probe=39c7028c1e) | Nov 15, 2023 |
| ADVAN         | 1405                        | [55a639a506](https://linux-hardware.org/?probe=55a639a506) | Nov 14, 2023 |
| ASUSTek       | T100TAS                     | [ff4068e60a](https://linux-hardware.org/?probe=ff4068e60a) | Nov 12, 2023 |
| Acer          | Swift SFX14-41G             | [be4c8862d0](https://linux-hardware.org/?probe=be4c8862d0) | Nov 11, 2023 |
| Acer          | Swift SF314-511             | [ba5db231dd](https://linux-hardware.org/?probe=ba5db231dd) | Nov 08, 2023 |
| Lenovo        | ThinkPad Edge E465 BE465... | [54b9aa1cac](https://linux-hardware.org/?probe=54b9aa1cac) | Nov 07, 2023 |
| Acer          | Swift SF314-511             | [1e2ba13164](https://linux-hardware.org/?probe=1e2ba13164) | Nov 06, 2023 |
| Lenovo        | IdeaPad S410p 20296         | [61828bc39f](https://linux-hardware.org/?probe=61828bc39f) | Nov 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [669430e32e](https://linux-hardware.org/?probe=669430e32e) | Nov 04, 2023 |
| Acidanther... | MacBookPro15,2              | [ae60650070](https://linux-hardware.org/?probe=ae60650070) | Nov 04, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [0ce0a4d87a](https://linux-hardware.org/?probe=0ce0a4d87a) | Nov 04, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | X456UR                      | [9a0a4dfd02](https://linux-hardware.org/?probe=9a0a4dfd02) | Nov 02, 2023 |
| Lenovo        | G40-45 80E1                 | [fffa5fb420](https://linux-hardware.org/?probe=fffa5fb420) | Nov 02, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [a7f47546e5](https://linux-hardware.org/?probe=a7f47546e5) | Nov 01, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [8901bca741](https://linux-hardware.org/?probe=8901bca741) | Nov 01, 2023 |
| HP            | EliteBook 2570p             | [bc8c6e67a9](https://linux-hardware.org/?probe=bc8c6e67a9) | Oct 28, 2023 |
| Acer          | Swift SFX14-41G             | [63b5c65c01](https://linux-hardware.org/?probe=63b5c65c01) | Oct 28, 2023 |
| Acer          | Aspire E5-411G              | [220dddac59](https://linux-hardware.org/?probe=220dddac59) | Oct 28, 2023 |
| Dell          | Precision 5530              | [e707fe59cc](https://linux-hardware.org/?probe=e707fe59cc) | Oct 27, 2023 |
| HP            | Notebook                    | [1f270f615f](https://linux-hardware.org/?probe=1f270f615f) | Oct 27, 2023 |
| Dell          | Inspiron One 2310           | [1a8d313e86](https://linux-hardware.org/?probe=1a8d313e86) | Oct 25, 2023 |
| Dell          | Latitude 5285               | [9af5195620](https://linux-hardware.org/?probe=9af5195620) | Oct 24, 2023 |
| Dell          | Latitude 5320               | [520c2effa3](https://linux-hardware.org/?probe=520c2effa3) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [5b608b97fc](https://linux-hardware.org/?probe=5b608b97fc) | Oct 23, 2023 |
| Dell          | Latitude 5285               | [9552613f54](https://linux-hardware.org/?probe=9552613f54) | Oct 23, 2023 |
| Dell          | Latitude E6320              | [c6965e07e3](https://linux-hardware.org/?probe=c6965e07e3) | Oct 21, 2023 |
| Dell          | Inspiron 3458               | [ff4adff045](https://linux-hardware.org/?probe=ff4adff045) | Oct 21, 2023 |
| Acer          | Aspire E5-411G              | [fe4a9ec4d0](https://linux-hardware.org/?probe=fe4a9ec4d0) | Oct 20, 2023 |
| ASUSTek       | S400CA                      | [1c0c1df851](https://linux-hardware.org/?probe=1c0c1df851) | Oct 20, 2023 |
| Toshiba       | dynabook R732/H             | [4852b6da95](https://linux-hardware.org/?probe=4852b6da95) | Oct 20, 2023 |
| HP            | Notebook                    | [3fb8313450](https://linux-hardware.org/?probe=3fb8313450) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | [71ffea0397](https://linux-hardware.org/?probe=71ffea0397) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | [9ab2c722a5](https://linux-hardware.org/?probe=9ab2c722a5) | Oct 19, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [459dc02cda](https://linux-hardware.org/?probe=459dc02cda) | Oct 18, 2023 |
| Acer          | Aspire E3-112M              | [11d6580d3e](https://linux-hardware.org/?probe=11d6580d3e) | Oct 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [329a5f99e0](https://linux-hardware.org/?probe=329a5f99e0) | Oct 18, 2023 |
| MicroByte     | ezbook                      | [c67055c10c](https://linux-hardware.org/?probe=c67055c10c) | Oct 17, 2023 |
| MicroByte     | ezbook                      | [5018eaffae](https://linux-hardware.org/?probe=5018eaffae) | Oct 17, 2023 |
| Toshiba       | Satellite L645              | [5bea545bf5](https://linux-hardware.org/?probe=5bea545bf5) | Oct 16, 2023 |
| Valve         | Jupiter                     | [ec059c9ea7](https://linux-hardware.org/?probe=ec059c9ea7) | Oct 15, 2023 |
| Acer          | Swift SF314-511             | [3d63dd4590](https://linux-hardware.org/?probe=3d63dd4590) | Oct 13, 2023 |
| Toshiba       | Satellite C55D-C            | [e083a8012f](https://linux-hardware.org/?probe=e083a8012f) | Oct 11, 2023 |
| HP            | 430                         | [e62771b9a7](https://linux-hardware.org/?probe=e62771b9a7) | Oct 09, 2023 |
| HP            | 430                         | [71211a4eda](https://linux-hardware.org/?probe=71211a4eda) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f3348806a2](https://linux-hardware.org/?probe=f3348806a2) | Oct 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f269e7a6ee](https://linux-hardware.org/?probe=f269e7a6ee) | Oct 09, 2023 |
| Lenovo        | G40-45 80E1                 | [1bb42f8755](https://linux-hardware.org/?probe=1bb42f8755) | Oct 09, 2023 |
| Acer          | Swift SF314-56G             | [2696a8d9c0](https://linux-hardware.org/?probe=2696a8d9c0) | Oct 08, 2023 |
| HP            | Laptop 14s-cf2xxx           | [c40356b94d](https://linux-hardware.org/?probe=c40356b94d) | Oct 05, 2023 |
| Acer          | Swift SF314-56G             | [15b613a264](https://linux-hardware.org/?probe=15b613a264) | Oct 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [0df81159a2](https://linux-hardware.org/?probe=0df81159a2) | Oct 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a3773ae099](https://linux-hardware.org/?probe=a3773ae099) | Oct 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [25211e6ce1](https://linux-hardware.org/?probe=25211e6ce1) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| Acer          | Aspire E5-411G              | [80ac43658d](https://linux-hardware.org/?probe=80ac43658d) | Sep 30, 2023 |
| Lenovo        | ThinkPad L530 24783R8       | [eda040f456](https://linux-hardware.org/?probe=eda040f456) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [d95e370c54](https://linux-hardware.org/?probe=d95e370c54) | Sep 29, 2023 |
| Acer          | Aspire E5-411G              | [eeb582da25](https://linux-hardware.org/?probe=eeb582da25) | Sep 28, 2023 |
| Dell          | Latitude 7490               | [6f5e4547fa](https://linux-hardware.org/?probe=6f5e4547fa) | Sep 27, 2023 |
| Dell          | Latitude 7490               | [8bb2e054ec](https://linux-hardware.org/?probe=8bb2e054ec) | Sep 26, 2023 |
| Acer          | Nitro AN515-54              | [6383f263a8](https://linux-hardware.org/?probe=6383f263a8) | Sep 25, 2023 |
| Toshiba       | dynabook R632/H             | [7279759e40](https://linux-hardware.org/?probe=7279759e40) | Sep 25, 2023 |
| Acer          | Aspire S3                   | [4b2b76bdb3](https://linux-hardware.org/?probe=4b2b76bdb3) | Sep 24, 2023 |
| Acer          | Aspire S3                   | [723a872112](https://linux-hardware.org/?probe=723a872112) | Sep 24, 2023 |
| HUAWEI        | KPL-W0X                     | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| HP            | Laptop 14-ep0xxx            | [ee7b0c8506](https://linux-hardware.org/?probe=ee7b0c8506) | Sep 21, 2023 |
| Lenovo        | V14 G3 IAP 82TS             | [2528381c0e](https://linux-hardware.org/?probe=2528381c0e) | Sep 21, 2023 |
| HUAWEI        | KPL-W0X                     | [efafe71bd6](https://linux-hardware.org/?probe=efafe71bd6) | Sep 21, 2023 |
| HP            | Laptop 14s-dq3xxx           | [a1356bddb2](https://linux-hardware.org/?probe=a1356bddb2) | Sep 21, 2023 |
| HP            | Laptop 14s-dq3xxx           | [77e008b6d9](https://linux-hardware.org/?probe=77e008b6d9) | Sep 20, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [98a32c8241](https://linux-hardware.org/?probe=98a32c8241) | Sep 19, 2023 |
| HP            | EliteBook 8470p             | [a8995def08](https://linux-hardware.org/?probe=a8995def08) | Sep 19, 2023 |
| Lenovo        | G40-45 80E1                 | [417ad95c4c](https://linux-hardware.org/?probe=417ad95c4c) | Sep 18, 2023 |
| Lenovo        | G40-45 80E1                 | [c27b81ea3e](https://linux-hardware.org/?probe=c27b81ea3e) | Sep 17, 2023 |
| realme        | RMNBXXXX                    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| HP            | 245 G7 Notebook PC          | [ab68dea087](https://linux-hardware.org/?probe=ab68dea087) | Sep 14, 2023 |
| HP            | EliteBook 2570p             | [6259de24be](https://linux-hardware.org/?probe=6259de24be) | Sep 11, 2023 |
| Acer          | Swift SF314-71              | [00e5dd81d7](https://linux-hardware.org/?probe=00e5dd81d7) | Sep 10, 2023 |
| Acer          | Aspire E5-411G              | [16c285bb07](https://linux-hardware.org/?probe=16c285bb07) | Sep 10, 2023 |
| Samsung       | RV413/RV513                 | [c59551fc6f](https://linux-hardware.org/?probe=c59551fc6f) | Sep 09, 2023 |
| ASUSTek       | X450CC                      | [5564e70c85](https://linux-hardware.org/?probe=5564e70c85) | Sep 09, 2023 |
| ASUSTek       | X201EP                      | [a714c5a35a](https://linux-hardware.org/?probe=a714c5a35a) | Sep 09, 2023 |
| HP            | Laptop 15-db1xxx            | [34e95a943a](https://linux-hardware.org/?probe=34e95a943a) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [cbd5cf3e4b](https://linux-hardware.org/?probe=cbd5cf3e4b) | Sep 08, 2023 |
| Sony          | VGN-CS108D                  | [24bf5bb06c](https://linux-hardware.org/?probe=24bf5bb06c) | Sep 05, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [1a1c5e43bc](https://linux-hardware.org/?probe=1a1c5e43bc) | Sep 05, 2023 |
| AXIOO         | Mybook 14E                  | [b6ddb628dc](https://linux-hardware.org/?probe=b6ddb628dc) | Sep 04, 2023 |
| Acer          | Aspire A314-35              | [6edc4e910d](https://linux-hardware.org/?probe=6edc4e910d) | Sep 04, 2023 |
| HP            | EliteBook Revolve 810 G2    | [3f102b35e3](https://linux-hardware.org/?probe=3f102b35e3) | Sep 04, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [e27673ed4c](https://linux-hardware.org/?probe=e27673ed4c) | Sep 03, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [959fb04734](https://linux-hardware.org/?probe=959fb04734) | Sep 03, 2023 |
| Sony          | VPCYB15AG                   | [e192029ff0](https://linux-hardware.org/?probe=e192029ff0) | Sep 03, 2023 |
| Acer          | Aspire E5-475G              | [55542f9b89](https://linux-hardware.org/?probe=55542f9b89) | Aug 31, 2023 |
| Dell          | Latitude E6410              | [c2337bbe75](https://linux-hardware.org/?probe=c2337bbe75) | Aug 31, 2023 |
| Acer          | Aspire E5-411G              | [13ec5c53cf](https://linux-hardware.org/?probe=13ec5c53cf) | Aug 31, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [5cfa9a748f](https://linux-hardware.org/?probe=5cfa9a748f) | Aug 31, 2023 |
| Dell          | Inspiron 3585               | [02708536f4](https://linux-hardware.org/?probe=02708536f4) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [aa10544f35](https://linux-hardware.org/?probe=aa10544f35) | Aug 30, 2023 |
| Fujitsu       | FMVU14003                   | [8da3625e06](https://linux-hardware.org/?probe=8da3625e06) | Aug 27, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [5b334ec725](https://linux-hardware.org/?probe=5b334ec725) | Aug 27, 2023 |
| Acer          | Aspire E5-411G              | [1986877980](https://linux-hardware.org/?probe=1986877980) | Aug 25, 2023 |
| HP            | Laptop 15-db1xxx            | [2a72d00223](https://linux-hardware.org/?probe=2a72d00223) | Aug 25, 2023 |
| HP            | Victus by Gaming Laptop ... | [f79de96905](https://linux-hardware.org/?probe=f79de96905) | Aug 23, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [abae84243d](https://linux-hardware.org/?probe=abae84243d) | Aug 23, 2023 |
| Dell          | Latitude E6410              | [fbaef9218f](https://linux-hardware.org/?probe=fbaef9218f) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8fd1db4fee](https://linux-hardware.org/?probe=8fd1db4fee) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [2cbbb89cd4](https://linux-hardware.org/?probe=2cbbb89cd4) | Aug 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c1a5eb75bf](https://linux-hardware.org/?probe=c1a5eb75bf) | Aug 21, 2023 |
| HP            | Victus by Gaming Laptop ... | [c47971e406](https://linux-hardware.org/?probe=c47971e406) | Aug 21, 2023 |
| Lenovo        | ThinkPad T540p 20BFS02S0... | [2f59ec7141](https://linux-hardware.org/?probe=2f59ec7141) | Aug 18, 2023 |
| Infinix       | INBOOK X2 GEN11             | [f368b5bf17](https://linux-hardware.org/?probe=f368b5bf17) | Aug 18, 2023 |
| Toshiba       | Satellite L510              | [f06d068ca0](https://linux-hardware.org/?probe=f06d068ca0) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [b7a28997df](https://linux-hardware.org/?probe=b7a28997df) | Aug 15, 2023 |
| Acer          | Swift SF314-71              | [b78f4bf01d](https://linux-hardware.org/?probe=b78f4bf01d) | Aug 15, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | [c192c37af2](https://linux-hardware.org/?probe=c192c37af2) | Aug 14, 2023 |
| MSI           | Katana GF66 11UD            | [e7e9bfd605](https://linux-hardware.org/?probe=e7e9bfd605) | Aug 13, 2023 |
| Samsung       | 960XFH                      | [b7f35fe8b5](https://linux-hardware.org/?probe=b7f35fe8b5) | Aug 13, 2023 |
| HP            | EliteBook 820 G3            | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| Acer          | TravelMate B113             | [5d3d27c8bb](https://linux-hardware.org/?probe=5d3d27c8bb) | Aug 12, 2023 |
| Acer          | One Z1402                   | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [fadee3e38d](https://linux-hardware.org/?probe=fadee3e38d) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | [49a3480efb](https://linux-hardware.org/?probe=49a3480efb) | Aug 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | [6de592988e](https://linux-hardware.org/?probe=6de592988e) | Aug 09, 2023 |
| Acer          | Aspire 4752                 | [1c68b4d24a](https://linux-hardware.org/?probe=1c68b4d24a) | Aug 08, 2023 |
| Acer          | Aspire 4750                 | [8491f5fc3b](https://linux-hardware.org/?probe=8491f5fc3b) | Aug 07, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [eab0544dc6](https://linux-hardware.org/?probe=eab0544dc6) | Aug 06, 2023 |
| HP            | ProBook 440 G3              | [abb19010d2](https://linux-hardware.org/?probe=abb19010d2) | Aug 05, 2023 |
| Dell          | Latitude E6410              | [ad46549b01](https://linux-hardware.org/?probe=ad46549b01) | Aug 04, 2023 |
| Dell          | Latitude E6410              | [e2364d5aac](https://linux-hardware.org/?probe=e2364d5aac) | Aug 04, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | [73e1dd94b2](https://linux-hardware.org/?probe=73e1dd94b2) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | [a13fd4044e](https://linux-hardware.org/?probe=a13fd4044e) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming FX505DD          | [e965235133](https://linux-hardware.org/?probe=e965235133) | Jul 29, 2023 |
| Acer          | Aspire A315-42              | [3afa5a3034](https://linux-hardware.org/?probe=3afa5a3034) | Jul 27, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [6632226064](https://linux-hardware.org/?probe=6632226064) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [24c092f0b0](https://linux-hardware.org/?probe=24c092f0b0) | Jul 26, 2023 |
| Lenovo        | ThinkPad X230 23246V9       | [e7bc7dac48](https://linux-hardware.org/?probe=e7bc7dac48) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Fujitsu       | FMVNC4BC4                   | [14249b136a](https://linux-hardware.org/?probe=14249b136a) | Jul 19, 2023 |
| Acer          | Aspire E5-476G              | [74af6477be](https://linux-hardware.org/?probe=74af6477be) | Jul 19, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [3649d91857](https://linux-hardware.org/?probe=3649d91857) | Jul 18, 2023 |
| Acer          | Swift SF314-71              | [462a41184d](https://linux-hardware.org/?probe=462a41184d) | Jul 17, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [94555c5887](https://linux-hardware.org/?probe=94555c5887) | Jul 10, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [de7dbebf49](https://linux-hardware.org/?probe=de7dbebf49) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | [fe9bfd5f77](https://linux-hardware.org/?probe=fe9bfd5f77) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | [d4dadd2e77](https://linux-hardware.org/?probe=d4dadd2e77) | Jul 10, 2023 |
| HP            | ProBook 4420s               | [51e917f03e](https://linux-hardware.org/?probe=51e917f03e) | Jul 09, 2023 |
| Acer          | Aspire 4720Z                | [312486a5b7](https://linux-hardware.org/?probe=312486a5b7) | Jul 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [06b52888f8](https://linux-hardware.org/?probe=06b52888f8) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0048149cd5](https://linux-hardware.org/?probe=0048149cd5) | Jul 08, 2023 |
| Toshiba       | PORTEGE R30-C               | [f07f4d423b](https://linux-hardware.org/?probe=f07f4d423b) | Jul 07, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c5fcc4bcf0](https://linux-hardware.org/?probe=c5fcc4bcf0) | Jul 06, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f05e91be82](https://linux-hardware.org/?probe=f05e91be82) | Jul 06, 2023 |
| Toshiba       | Satellite C640              | [680f3038da](https://linux-hardware.org/?probe=680f3038da) | Jul 06, 2023 |
| HP            | Laptop 15-fc0xxx            | [a0183085b8](https://linux-hardware.org/?probe=a0183085b8) | Jul 06, 2023 |
| AZW           | Z85                         | [ca44d0b498](https://linux-hardware.org/?probe=ca44d0b498) | Jul 05, 2023 |
| Acer          | Aspire V5-471G              | [6dd5e93eea](https://linux-hardware.org/?probe=6dd5e93eea) | Jul 05, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [f1ad74f37a](https://linux-hardware.org/?probe=f1ad74f37a) | Jul 05, 2023 |
| Dell          | Latitude E6540              | [17ec85df62](https://linux-hardware.org/?probe=17ec85df62) | Jul 05, 2023 |
| Dell          | Latitude 3410               | [11d9814008](https://linux-hardware.org/?probe=11d9814008) | Jul 02, 2023 |
| ASUSTek       | X201EV                      | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5873d04afe](https://linux-hardware.org/?probe=5873d04afe) | Jun 29, 2023 |
| UMAX          | N14R                        | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0c87fda1f9](https://linux-hardware.org/?probe=0c87fda1f9) | Jun 27, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [40cbc38a69](https://linux-hardware.org/?probe=40cbc38a69) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [01a9e10a34](https://linux-hardware.org/?probe=01a9e10a34) | Jun 24, 2023 |
| Toshiba       | PORTEGE Z930                | [0cad0d9955](https://linux-hardware.org/?probe=0cad0d9955) | Jun 22, 2023 |
| Notebook      | P870DM                      | [cd318aa5a4](https://linux-hardware.org/?probe=cd318aa5a4) | Jun 21, 2023 |
| Dell          | G7 7588                     | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Lenovo        | IdeaPad S410p 20296         | [6a6cfb05d6](https://linux-hardware.org/?probe=6a6cfb05d6) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| HP            | Laptop 17-ca0xxx            | [5296ca6ae2](https://linux-hardware.org/?probe=5296ca6ae2) | Jun 19, 2023 |
| HP            | Laptop 14s-dk1xxx           | [16bbd0f687](https://linux-hardware.org/?probe=16bbd0f687) | Jun 18, 2023 |
| HP            | Laptop 14-bw0xx             | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d7e9625e19](https://linux-hardware.org/?probe=d7e9625e19) | Jun 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire E5-411G              | [9a69b50d97](https://linux-hardware.org/?probe=9a69b50d97) | Jun 07, 2023 |
| Infinix       | INBook X1 Pro               | [c558de3b74](https://linux-hardware.org/?probe=c558de3b74) | Jun 05, 2023 |
| Infinix       | INBOOK X2                   | [0a82b1aed3](https://linux-hardware.org/?probe=0a82b1aed3) | Jun 05, 2023 |
| Acer          | Swift SF314-511             | [6754a25d1d](https://linux-hardware.org/?probe=6754a25d1d) | Jun 03, 2023 |
| HP            | Laptop 14-bw0xx             | [3958079ad5](https://linux-hardware.org/?probe=3958079ad5) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| AXIOO         | Mybook-14E                  | [cb04b551d8](https://linux-hardware.org/?probe=cb04b551d8) | May 31, 2023 |
| ASUSTek       | X456URK                     | [6de2588617](https://linux-hardware.org/?probe=6de2588617) | May 29, 2023 |
| ASUSTek       | X456URK                     | [369aa4fc93](https://linux-hardware.org/?probe=369aa4fc93) | May 29, 2023 |
| ASUSTek       | X455LF                      | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| AVITA         | NE14A2                      | [89c5edafbc](https://linux-hardware.org/?probe=89c5edafbc) | May 28, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [db7d7cf31d](https://linux-hardware.org/?probe=db7d7cf31d) | May 26, 2023 |
| Panasonic     | CFSZ5-2                     | [d5b1455382](https://linux-hardware.org/?probe=d5b1455382) | May 25, 2023 |
| HP            | Laptop 14s-cf2xxx           | [e51dec5daf](https://linux-hardware.org/?probe=e51dec5daf) | May 24, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [e752398b87](https://linux-hardware.org/?probe=e752398b87) | May 23, 2023 |
| HP            | Laptop 14s-dk1xxx           | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | [cfdb07c9ca](https://linux-hardware.org/?probe=cfdb07c9ca) | May 21, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | [379bcdafa9](https://linux-hardware.org/?probe=379bcdafa9) | May 21, 2023 |
| Sony          | VPCSB35FG                   | [81d2592989](https://linux-hardware.org/?probe=81d2592989) | May 20, 2023 |
| Sony          | VPCSB35FG                   | [828fb24994](https://linux-hardware.org/?probe=828fb24994) | May 20, 2023 |
| Acer          | One Z1402                   | [390a684064](https://linux-hardware.org/?probe=390a684064) | May 16, 2023 |
| ASUSTek       | GL502VMK                    | [0b7232826d](https://linux-hardware.org/?probe=0b7232826d) | May 13, 2023 |
| HP            | Laptop 14s-cf0xxx           | [6d0f055f82](https://linux-hardware.org/?probe=6d0f055f82) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | [7f90473be2](https://linux-hardware.org/?probe=7f90473be2) | May 11, 2023 |
| Infinix       | INBook X1                   | [c005323a1a](https://linux-hardware.org/?probe=c005323a1a) | May 11, 2023 |
| Dell          | Inspiron 3505               | [e8f10d5f7e](https://linux-hardware.org/?probe=e8f10d5f7e) | May 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [1b0786ec5e](https://linux-hardware.org/?probe=1b0786ec5e) | May 07, 2023 |
| ASUSTek       | K42Jc                       | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| ASUSTek       | K42Jc                       | [98d7593057](https://linux-hardware.org/?probe=98d7593057) | May 05, 2023 |
| Dell          | Latitude D630               | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| Dell          | Latitude D630               | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [9035ec79cd](https://linux-hardware.org/?probe=9035ec79cd) | May 02, 2023 |
| Acer          | Aspire A514-54G             | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Dell          | Latitude D630               | [a3c3e09675](https://linux-hardware.org/?probe=a3c3e09675) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c1616fcd6c](https://linux-hardware.org/?probe=c1616fcd6c) | Apr 28, 2023 |
| Dell          | Latitude D630               | [850df6e76f](https://linux-hardware.org/?probe=850df6e76f) | Apr 26, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| HP            | Laptop 14-cm0xxx            | [4591d1bf9d](https://linux-hardware.org/?probe=4591d1bf9d) | Apr 24, 2023 |
| Valve         | Jupiter                     | [ff8440808f](https://linux-hardware.org/?probe=ff8440808f) | Apr 22, 2023 |
| Acer          | Swift SF314-511             | [96fd44e94a](https://linux-hardware.org/?probe=96fd44e94a) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [6cf066b06b](https://linux-hardware.org/?probe=6cf066b06b) | Apr 19, 2023 |
| Acer          | Swift SFX14-41G             | [40ae403838](https://linux-hardware.org/?probe=40ae403838) | Apr 18, 2023 |
| AXIOO         | SlimBook 11                 | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| Dell          | Latitude 7300               | [1064b58edb](https://linux-hardware.org/?probe=1064b58edb) | Apr 13, 2023 |
| HP            | Laptop 14s-cf1xxx           | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| MSI           | Creator 15 A11UE            | [ca70d48c0e](https://linux-hardware.org/?probe=ca70d48c0e) | Apr 11, 2023 |
| HP            | Notebook                    | [584a741058](https://linux-hardware.org/?probe=584a741058) | Apr 08, 2023 |
| ASUSTek       | K46CM                       | [d878fad4d0](https://linux-hardware.org/?probe=d878fad4d0) | Apr 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [fcfcfdbbe7](https://linux-hardware.org/?probe=fcfcfdbbe7) | Apr 06, 2023 |
| Toshiba       | Satellite L640              | [8009d927db](https://linux-hardware.org/?probe=8009d927db) | Apr 05, 2023 |
| Lenovo        | ThinkPad Edge 0578RZ3       | [d37b6fa47b](https://linux-hardware.org/?probe=d37b6fa47b) | Apr 05, 2023 |
| Timi          | TM1703                      | [54b062157f](https://linux-hardware.org/?probe=54b062157f) | Apr 04, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| Dell          | Latitude 3410               | [0b29a27e88](https://linux-hardware.org/?probe=0b29a27e88) | Apr 03, 2023 |
| Dell          | Latitude 3410               | [9c8218ebd6](https://linux-hardware.org/?probe=9c8218ebd6) | Apr 03, 2023 |
| Acer          | Swift SFX14-41G             | [e60610d78a](https://linux-hardware.org/?probe=e60610d78a) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| Acer          | Aspire 4738Z                | [20e13078ef](https://linux-hardware.org/?probe=20e13078ef) | Apr 02, 2023 |
| Acer          | Aspire A515-56              | [a959d79d84](https://linux-hardware.org/?probe=a959d79d84) | Apr 01, 2023 |
| Acer          | Aspire A515-56              | [db53e1a333](https://linux-hardware.org/?probe=db53e1a333) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| Acer          | Aspire A514-53              | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| MSI           | Bravo 15 B5DD               | [6dac36ba2d](https://linux-hardware.org/?probe=6dac36ba2d) | Mar 28, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [0e8125dc1f](https://linux-hardware.org/?probe=0e8125dc1f) | Mar 28, 2023 |
| Acer          | Aspire E5-411G              | [4ac3cde372](https://linux-hardware.org/?probe=4ac3cde372) | Mar 27, 2023 |
| ASUSTek       | X555BA                      | [f7d51f3c2f](https://linux-hardware.org/?probe=f7d51f3c2f) | Mar 26, 2023 |
| Acer          | Swift SF314-511             | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| HP            | Pavilion 11 x360 PC         | [2c3c5a65a5](https://linux-hardware.org/?probe=2c3c5a65a5) | Mar 24, 2023 |
| MSI           | GF63 Thin 11SC              | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| Samsung       | RF511/RF411/RF711           | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| ASUSTek       | X540LJ                      | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [063ed79c8f](https://linux-hardware.org/?probe=063ed79c8f) | Mar 15, 2023 |
| Toshiba       | PORTEGE Z30t-C              | [7098d7537b](https://linux-hardware.org/?probe=7098d7537b) | Mar 15, 2023 |
| Lenovo        | G400s 20244                 | [fed6bb2c17](https://linux-hardware.org/?probe=fed6bb2c17) | Mar 13, 2023 |
| Dell          | Latitude E5440              | [fe81dc02b0](https://linux-hardware.org/?probe=fe81dc02b0) | Mar 13, 2023 |
| ASUSTek       | X455LF                      | [cda777dad9](https://linux-hardware.org/?probe=cda777dad9) | Mar 13, 2023 |
| AXIOO         | Mybook 14E                  | [1b6c10d1d8](https://linux-hardware.org/?probe=1b6c10d1d8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2AX0... | [d6854dc15a](https://linux-hardware.org/?probe=d6854dc15a) | Mar 12, 2023 |
| Valve         | Jupiter                     | [f4ad14a82a](https://linux-hardware.org/?probe=f4ad14a82a) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| ADVAN         | 1405                        | [7f96f0214f](https://linux-hardware.org/?probe=7f96f0214f) | Mar 08, 2023 |
| Lenovo        | G40-80 80E4                 | [01dae27177](https://linux-hardware.org/?probe=01dae27177) | Mar 07, 2023 |
| Dell          | G7 7588                     | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [2cdcded03e](https://linux-hardware.org/?probe=2cdcded03e) | Mar 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fa94a404fa](https://linux-hardware.org/?probe=fa94a404fa) | Mar 04, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [9857559bb5](https://linux-hardware.org/?probe=9857559bb5) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [096c600c1d](https://linux-hardware.org/?probe=096c600c1d) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [cd8d61c1b6](https://linux-hardware.org/?probe=cd8d61c1b6) | Mar 03, 2023 |
| Google        | Vorticon                    | [7e9f3425ab](https://linux-hardware.org/?probe=7e9f3425ab) | Mar 03, 2023 |
| Google        | Vorticon                    | [aaa620e932](https://linux-hardware.org/?probe=aaa620e932) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| ASUSTek       | E202SA                      | [bccde0c9a5](https://linux-hardware.org/?probe=bccde0c9a5) | Feb 28, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| ASUSTek       | GL553VD                     | [302b65ed41](https://linux-hardware.org/?probe=302b65ed41) | Feb 25, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| Dell          | Inspiron 3476               | [58bff0319e](https://linux-hardware.org/?probe=58bff0319e) | Feb 24, 2023 |
| ASUSTek       | X441UA                      | [cd870fc3d3](https://linux-hardware.org/?probe=cd870fc3d3) | Feb 23, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [2953555c08](https://linux-hardware.org/?probe=2953555c08) | Feb 19, 2023 |
| Lenovo        | B40-70 20392                | [7197aacb00](https://linux-hardware.org/?probe=7197aacb00) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| ASUSTek       | X200MA                      | [b01624da44](https://linux-hardware.org/?probe=b01624da44) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f6e519323b](https://linux-hardware.org/?probe=f6e519323b) | Feb 15, 2023 |
| Acer          | Aspire 4750                 | [ac80c33464](https://linux-hardware.org/?probe=ac80c33464) | Feb 14, 2023 |
| Acer          | Aspire 4732Z                | [abf9d41a29](https://linux-hardware.org/?probe=abf9d41a29) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [a8a5ef19de](https://linux-hardware.org/?probe=a8a5ef19de) | Feb 13, 2023 |
| HP            | EliteBook 745 G6            | [9fd578a21d](https://linux-hardware.org/?probe=9fd578a21d) | Feb 13, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [608ce76690](https://linux-hardware.org/?probe=608ce76690) | Feb 13, 2023 |
| Toshiba       | Satellite L510              | [706759d61d](https://linux-hardware.org/?probe=706759d61d) | Feb 12, 2023 |
| Dell          | Vostro 3400                 | [89365a25ee](https://linux-hardware.org/?probe=89365a25ee) | Feb 12, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [f8f0fb1a21](https://linux-hardware.org/?probe=f8f0fb1a21) | Feb 11, 2023 |
| Timi          | RedmiBook 15                | [6dffda8f11](https://linux-hardware.org/?probe=6dffda8f11) | Feb 10, 2023 |
| Dell          | Studio XPS 1340             | [4c96fdcf99](https://linux-hardware.org/?probe=4c96fdcf99) | Feb 09, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | [86297e5638](https://linux-hardware.org/?probe=86297e5638) | Feb 09, 2023 |
| Toshiba       | Satellite L735              | [99f282862c](https://linux-hardware.org/?probe=99f282862c) | Feb 08, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [06ffbacba3](https://linux-hardware.org/?probe=06ffbacba3) | Feb 08, 2023 |
| ASUSTek       | X455LF                      | [d60cd149fb](https://linux-hardware.org/?probe=d60cd149fb) | Feb 07, 2023 |
| ASUSTek       | P453UA                      | [476ff28577](https://linux-hardware.org/?probe=476ff28577) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [6fcc29607c](https://linux-hardware.org/?probe=6fcc29607c) | Feb 06, 2023 |
| Acer          | Aspire E5-476G              | [3b8e69dd3a](https://linux-hardware.org/?probe=3b8e69dd3a) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [cfc187a64c](https://linux-hardware.org/?probe=cfc187a64c) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [74bf135ed9](https://linux-hardware.org/?probe=74bf135ed9) | Jan 31, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [e0c723e305](https://linux-hardware.org/?probe=e0c723e305) | Jan 31, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [0c220851f3](https://linux-hardware.org/?probe=0c220851f3) | Jan 30, 2023 |
| Acer          | Swift SF314-71              | [41c052436a](https://linux-hardware.org/?probe=41c052436a) | Jan 30, 2023 |
| MSI           | Modern 14 A10RB             | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| ASUSTek       | X555LAB                     | [343025f50f](https://linux-hardware.org/?probe=343025f50f) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [3b41afb262](https://linux-hardware.org/?probe=3b41afb262) | Jan 27, 2023 |
| HP            | 14                          | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| Dell          | Inspiron 3585               | [b41a540bb4](https://linux-hardware.org/?probe=b41a540bb4) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [acf75dbe88](https://linux-hardware.org/?probe=acf75dbe88) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Acer          | Aspire E1-421               | [16277f992b](https://linux-hardware.org/?probe=16277f992b) | Jan 23, 2023 |
| HP            | EliteBook 745 G3            | [1fda4d1e4a](https://linux-hardware.org/?probe=1fda4d1e4a) | Jan 23, 2023 |
| Acer          | Swift SF314-71              | [9cee6edc8e](https://linux-hardware.org/?probe=9cee6edc8e) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| ASUSTek       | X455LF                      | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| Acer          | Aspire E1-421               | [855c9b8e45](https://linux-hardware.org/?probe=855c9b8e45) | Jan 18, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [58f2d0e1b4](https://linux-hardware.org/?probe=58f2d0e1b4) | Jan 12, 2023 |
| HP            | Laptop 14-bw0xx             | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| ASUSTek       | X456URK                     | [09c6b0ed0a](https://linux-hardware.org/?probe=09c6b0ed0a) | Jan 12, 2023 |
| Acer          | AO756                       | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| HP            | EliteBook 840 G3            | [5de089f4c0](https://linux-hardware.org/?probe=5de089f4c0) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | [d47b3555d6](https://linux-hardware.org/?probe=d47b3555d6) | Jan 08, 2023 |
| Dell          | Inspiron N4030              | [efaaf759cb](https://linux-hardware.org/?probe=efaaf759cb) | Jan 08, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [8056078760](https://linux-hardware.org/?probe=8056078760) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [b8e1b2ec8e](https://linux-hardware.org/?probe=b8e1b2ec8e) | Jan 07, 2023 |
| Acer          | Swift SF314-71              | [7fa69ddddb](https://linux-hardware.org/?probe=7fa69ddddb) | Jan 07, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| Lenovo        | B40-70 20392                | [71c1ae09af](https://linux-hardware.org/?probe=71c1ae09af) | Jan 05, 2023 |
| ASUSTek       | X453MA                      | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [d99426e3d5](https://linux-hardware.org/?probe=d99426e3d5) | Jan 01, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [7e7df16316](https://linux-hardware.org/?probe=7e7df16316) | Jan 01, 2023 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [56e961b0ca](https://linux-hardware.org/?probe=56e961b0ca) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| Acer          | TravelMate P214             | [436186d9e5](https://linux-hardware.org/?probe=436186d9e5) | Dec 30, 2022 |
| Lenovo        | ThinkPad X240 20AMS1J60B    | [1d8fcd4a75](https://linux-hardware.org/?probe=1d8fcd4a75) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b6413f9cf2](https://linux-hardware.org/?probe=b6413f9cf2) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [4ddf1fecb8](https://linux-hardware.org/?probe=4ddf1fecb8) | Dec 28, 2022 |
| Lenovo        | V310-14ISK 80SX             | [a1e4dd02b2](https://linux-hardware.org/?probe=a1e4dd02b2) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | [cedf39754e](https://linux-hardware.org/?probe=cedf39754e) | Dec 27, 2022 |
| Lenovo        | IdeaPad S110 20126          | [dd7fd03edd](https://linux-hardware.org/?probe=dd7fd03edd) | Dec 24, 2022 |
| Acer          | Swift SF314-71              | [36d833d9c2](https://linux-hardware.org/?probe=36d833d9c2) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | [c065eec185](https://linux-hardware.org/?probe=c065eec185) | Dec 20, 2022 |
| ASUSTek       | X45C                        | [80377ba23f](https://linux-hardware.org/?probe=80377ba23f) | Dec 17, 2022 |
| MSI           | Modern 14 B4MW              | [19e6ba206d](https://linux-hardware.org/?probe=19e6ba206d) | Dec 16, 2022 |
| Lenovo        | G40-30 80FY                 | [b9184a9ade](https://linux-hardware.org/?probe=b9184a9ade) | Dec 16, 2022 |
| Acer          | EX-215-52                   | [25201732ef](https://linux-hardware.org/?probe=25201732ef) | Dec 14, 2022 |
| Acer          | EX-215-52                   | [4cb72a8770](https://linux-hardware.org/?probe=4cb72a8770) | Dec 14, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [24fefa1408](https://linux-hardware.org/?probe=24fefa1408) | Dec 13, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [ed087084fb](https://linux-hardware.org/?probe=ed087084fb) | Dec 12, 2022 |
| Lenovo        | G40-30 80FY                 | [1a330e248d](https://linux-hardware.org/?probe=1a330e248d) | Dec 11, 2022 |
| ASUSTek       | T100TA                      | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| HP            | Laptop 14-bw0xx             | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5250630bdd](https://linux-hardware.org/?probe=5250630bdd) | Dec 09, 2022 |
| Acer          | Unknown                     | [b4eea49cf7](https://linux-hardware.org/?probe=b4eea49cf7) | Dec 09, 2022 |
| Lenovo        | ThinkPad L530 24783R8       | [406c066d36](https://linux-hardware.org/?probe=406c066d36) | Dec 08, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [c2d30310e8](https://linux-hardware.org/?probe=c2d30310e8) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [a978cbc03b](https://linux-hardware.org/?probe=a978cbc03b) | Dec 06, 2022 |
| Acer          | One Z1401                   | [835ad73eff](https://linux-hardware.org/?probe=835ad73eff) | Dec 05, 2022 |
| Toshiba       | dynabook R63/P              | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | [897f477f2d](https://linux-hardware.org/?probe=897f477f2d) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | [9f512598e2](https://linux-hardware.org/?probe=9f512598e2) | Dec 04, 2022 |
| Dell          | Latitude 3420               | [23e8b890d2](https://linux-hardware.org/?probe=23e8b890d2) | Dec 03, 2022 |
| Lenovo        | B40-70 20392                | [a527c5b6e6](https://linux-hardware.org/?probe=a527c5b6e6) | Dec 01, 2022 |
| ASUSTek       | E203NAH                     | [3d091ea214](https://linux-hardware.org/?probe=3d091ea214) | Nov 30, 2022 |
| Dell          | Latitude E6440              | [0c3dd709dd](https://linux-hardware.org/?probe=0c3dd709dd) | Nov 30, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4a49152177](https://linux-hardware.org/?probe=4a49152177) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Laptop 14s-dq5xxx           | [9bb72cb3e8](https://linux-hardware.org/?probe=9bb72cb3e8) | Nov 28, 2022 |
| HP            | Laptop 14s-dq5xxx           | [e5164649e1](https://linux-hardware.org/?probe=e5164649e1) | Nov 27, 2022 |
| Dell          | Inspiron 3521               | [74d291cf07](https://linux-hardware.org/?probe=74d291cf07) | Nov 24, 2022 |
| Dell          | Inspiron 3521               | [4f0d293e99](https://linux-hardware.org/?probe=4f0d293e99) | Nov 24, 2022 |
| Dell          | Latitude E6230              | [28b93e0f7c](https://linux-hardware.org/?probe=28b93e0f7c) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | [5f72d40c0e](https://linux-hardware.org/?probe=5f72d40c0e) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | [e6acabebb2](https://linux-hardware.org/?probe=e6acabebb2) | Nov 21, 2022 |
| ASUSTek       | X45C                        | [02a232c4ef](https://linux-hardware.org/?probe=02a232c4ef) | Nov 21, 2022 |
| ASUSTek       | X455YA                      | [70267d756a](https://linux-hardware.org/?probe=70267d756a) | Nov 21, 2022 |
| Dell          | Latitude E6520              | [855dc4dadd](https://linux-hardware.org/?probe=855dc4dadd) | Nov 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [4c05f821c1](https://linux-hardware.org/?probe=4c05f821c1) | Nov 16, 2022 |
| Acer          | Swift SF314-71              | [c1eca34f9c](https://linux-hardware.org/?probe=c1eca34f9c) | Nov 15, 2022 |
| Intel         | SandyBridge Platform        | [7019c7ba85](https://linux-hardware.org/?probe=7019c7ba85) | Nov 13, 2022 |
| Acer          | AO722                       | [5c51412f98](https://linux-hardware.org/?probe=5c51412f98) | Nov 12, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Lenovo        | ThinkPad P52s 20LB0026US    | [9443a4ceda](https://linux-hardware.org/?probe=9443a4ceda) | Nov 08, 2022 |
| Toshiba       | Satellite L15-B             | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| GPD           | G1619-04                    | [0c0542ac2e](https://linux-hardware.org/?probe=0c0542ac2e) | Nov 07, 2022 |
| MSI           | Modern 14 B5M               | [c2e7afc800](https://linux-hardware.org/?probe=c2e7afc800) | Nov 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [98e419a04d](https://linux-hardware.org/?probe=98e419a04d) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Intel         | SandyBridge Platform        | [88c15d34e4](https://linux-hardware.org/?probe=88c15d34e4) | Nov 03, 2022 |
| Acer          | Aspire A514-55              | [391048b46f](https://linux-hardware.org/?probe=391048b46f) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [49d6eb853f](https://linux-hardware.org/?probe=49d6eb853f) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [5de7efb403](https://linux-hardware.org/?probe=5de7efb403) | Nov 01, 2022 |
| Acer          | Aspire A514-55              | [142e1c0695](https://linux-hardware.org/?probe=142e1c0695) | Oct 31, 2022 |
| Acer          | Aspire A514-55              | [87f4a137dc](https://linux-hardware.org/?probe=87f4a137dc) | Oct 31, 2022 |
| ASUSTek       | X453MA                      | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| AXIOO         | Mybook 14H                  | [f8a7c19640](https://linux-hardware.org/?probe=f8a7c19640) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [0084d271e4](https://linux-hardware.org/?probe=0084d271e4) | Oct 28, 2022 |
| Acer          | Swift SFX14-41G             | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Lenovo        | V310-14IKB 80T2             | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3b87b259c8](https://linux-hardware.org/?probe=3b87b259c8) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [e438393dca](https://linux-hardware.org/?probe=e438393dca) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Dell          | Latitude 3490               | [a739a29b72](https://linux-hardware.org/?probe=a739a29b72) | Oct 16, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [babb66e9c9](https://linux-hardware.org/?probe=babb66e9c9) | Oct 16, 2022 |
| Acer          | Aspire A314-22              | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Intel         | SandyBridge Platform        | [3cc3d23297](https://linux-hardware.org/?probe=3cc3d23297) | Oct 14, 2022 |
| ASUSTek       | X455LD                      | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Apple         | MacBookPro5,3               | [814a533c23](https://linux-hardware.org/?probe=814a533c23) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46bc0c74c6](https://linux-hardware.org/?probe=46bc0c74c6) | Oct 11, 2022 |
| AXIOO         | Slimbook 13                 | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Acer          | Aspire 4736                 | [48b8af7bcf](https://linux-hardware.org/?probe=48b8af7bcf) | Oct 04, 2022 |
| HP            | 240 G7 Notebook PC          | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Acer          | Aspire ES1-522              | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| HP            | EliteBook 745 G6            | [ce8e31b40d](https://linux-hardware.org/?probe=ce8e31b40d) | Oct 02, 2022 |
| HP            | Compaq 420                  | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP            | EliteBook 745 G6            | [25e087916a](https://linux-hardware.org/?probe=25e087916a) | Oct 01, 2022 |
| ASUSTek       | X450EA                      | [345600d392](https://linux-hardware.org/?probe=345600d392) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [af7b986ff8](https://linux-hardware.org/?probe=af7b986ff8) | Sep 28, 2022 |
| Dell          | Latitude E6540              | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Acer          | Swift SF314-71              | [3414420bc7](https://linux-hardware.org/?probe=3414420bc7) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | [ab84311fcc](https://linux-hardware.org/?probe=ab84311fcc) | Sep 24, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | [48a40a2f04](https://linux-hardware.org/?probe=48a40a2f04) | Sep 24, 2022 |
| Acer          | Aspire A314-22              | [31b11c4544](https://linux-hardware.org/?probe=31b11c4544) | Sep 24, 2022 |
| ASUSTek       | X453SA                      | [b879e569d1](https://linux-hardware.org/?probe=b879e569d1) | Sep 24, 2022 |
| ASUSTek       | X450EA                      | [79d9dab7dc](https://linux-hardware.org/?probe=79d9dab7dc) | Sep 24, 2022 |
| HP            | Pavilion 14                 | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| AXIOO         | SlimBook 11                 | [c658e4f48c](https://linux-hardware.org/?probe=c658e4f48c) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [64ff44a074](https://linux-hardware.org/?probe=64ff44a074) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f24f78c803](https://linux-hardware.org/?probe=f24f78c803) | Sep 19, 2022 |
| Acer          | Swift SF314-71              | [0c383a03ad](https://linux-hardware.org/?probe=0c383a03ad) | Sep 17, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| Toshiba       | Satellite C660              | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0S10... | [0fd5868b54](https://linux-hardware.org/?probe=0fd5868b54) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| Lenovo        | ZHAOYANG E47                | [7f1fab5ff0](https://linux-hardware.org/?probe=7f1fab5ff0) | Sep 11, 2022 |
| Acer          | Aspire E3-112               | [bfa4cc7ddc](https://linux-hardware.org/?probe=bfa4cc7ddc) | Sep 10, 2022 |
| ASUSTek       | X441NA                      | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [983d14d741](https://linux-hardware.org/?probe=983d14d741) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [c073d9fb9f](https://linux-hardware.org/?probe=c073d9fb9f) | Sep 03, 2022 |
| Toshiba       | Satellite C660              | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| ASUSTek       | T100TA                      | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| Acer          | Aspire V5-431               | [5ac694007d](https://linux-hardware.org/?probe=5ac694007d) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | ThinkPad L512 259756M       | [3990fcfeed](https://linux-hardware.org/?probe=3990fcfeed) | Aug 30, 2022 |
| Infinix       | INBOOK X2                   | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [8fac02d016](https://linux-hardware.org/?probe=8fac02d016) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [d281087322](https://linux-hardware.org/?probe=d281087322) | Aug 28, 2022 |
| Dell          | Latitude 7280               | [d214e30b1e](https://linux-hardware.org/?probe=d214e30b1e) | Aug 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | One Z1402                   | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Dell          | Inspiron N5010              | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| ASUSTek       | X453MA                      | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| Acer          | Nitro AN515-43              | [a7d615e104](https://linux-hardware.org/?probe=a7d615e104) | Aug 14, 2022 |
| HP            | 14                          | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| ASUSTek       | K43E                        | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| Acer          | Aspire 4732Z                | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| ASUSTek       | K43E                        | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| Acer          | Aspire E5-476G              | [9c842ec71c](https://linux-hardware.org/?probe=9c842ec71c) | Aug 03, 2022 |
| HP            | 431                         | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Lenovo        | ThinkPad X230 23245NJ       | [3c85e43b86](https://linux-hardware.org/?probe=3c85e43b86) | Aug 01, 2022 |
| HP            | 240 G8 Notebook PC          | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| Acer          | Z476                        | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| Dell          | Latitude E7250              | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Sony          | VPCEA36FG                   | [6c742b6234](https://linux-hardware.org/?probe=6c742b6234) | Jul 30, 2022 |
| ASUSTek       | K43E                        | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| ASUSTek       | X455LF                      | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Acer          | Aspire 4732Z                | [3d23b4bbdc](https://linux-hardware.org/?probe=3d23b4bbdc) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Dell          | G3 3579                     | [96fab186c3](https://linux-hardware.org/?probe=96fab186c3) | Jul 24, 2022 |
| ASUSTek       | N56VZ                       | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [a6e3ee128e](https://linux-hardware.org/?probe=a6e3ee128e) | Jul 20, 2022 |
| Lenovo        | V310-14ISK 80SX             | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Acer          | Aspire E5-475G              | [1f7429b29d](https://linux-hardware.org/?probe=1f7429b29d) | Jul 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [54c99c7f2f](https://linux-hardware.org/?probe=54c99c7f2f) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [cf41c08ea5](https://linux-hardware.org/?probe=cf41c08ea5) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d651eb1f7d](https://linux-hardware.org/?probe=d651eb1f7d) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b04b2741a0](https://linux-hardware.org/?probe=b04b2741a0) | Jul 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b00361cdbd](https://linux-hardware.org/?probe=b00361cdbd) | Jul 13, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [cde5f69fef](https://linux-hardware.org/?probe=cde5f69fef) | Jul 13, 2022 |
| HP            | Pavilion g4                 | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Dell          | Latitude E6440              | [495237a0b0](https://linux-hardware.org/?probe=495237a0b0) | Jul 09, 2022 |
| Toshiba       | Satellite C640              | [cd8f69d739](https://linux-hardware.org/?probe=cd8f69d739) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Laptop 14s-cf2xxx           | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Lenovo        | ThinkPad L412 0585E86       | [ad82717c98](https://linux-hardware.org/?probe=ad82717c98) | Jul 01, 2022 |
| Acer          | Aspire 4732Z                | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| HP            | Laptop 14s-dk0xxx           | [97d88d7e00](https://linux-hardware.org/?probe=97d88d7e00) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | [3cec3cffbb](https://linux-hardware.org/?probe=3cec3cffbb) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | [bac4b49e55](https://linux-hardware.org/?probe=bac4b49e55) | Jun 30, 2022 |
| Acer          | Aspire A314-35              | [dfdd48254c](https://linux-hardware.org/?probe=dfdd48254c) | Jun 29, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| HP            | Pavilion g4                 | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Fujitsu       | FMVS02003                   | [3536a9951f](https://linux-hardware.org/?probe=3536a9951f) | Jun 23, 2022 |
| Dell          | Precision M4500             | [e41b9f3386](https://linux-hardware.org/?probe=e41b9f3386) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Aspire A315-41              | [00a254b4ff](https://linux-hardware.org/?probe=00a254b4ff) | Jun 21, 2022 |
| Acer          | Aspire A315-41              | [4ca3721cbb](https://linux-hardware.org/?probe=4ca3721cbb) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | [4d5fb8a789](https://linux-hardware.org/?probe=4d5fb8a789) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | [9f7b97f22f](https://linux-hardware.org/?probe=9f7b97f22f) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| AXIOO         | Mybook 14E                  | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Dell          | Inspiron 3442               | [b71d801e61](https://linux-hardware.org/?probe=b71d801e61) | Jun 18, 2022 |
| ASUSTek       | K46CB                       | [a6cc4351be](https://linux-hardware.org/?probe=a6cc4351be) | Jun 17, 2022 |
| ASUSTek       | K46CB                       | [fe4f649d9b](https://linux-hardware.org/?probe=fe4f649d9b) | Jun 17, 2022 |
| HP            | Laptop 14s-fq0xxx           | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| Acer          | AO756                       | [008fa33f13](https://linux-hardware.org/?probe=008fa33f13) | Jun 09, 2022 |
| Acer          | Aspire A514-54G             | [a74cd897c5](https://linux-hardware.org/?probe=a74cd897c5) | Jun 09, 2022 |
| MSI           | Prestige 14 A11SC           | [ea39fa65a1](https://linux-hardware.org/?probe=ea39fa65a1) | Jun 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [bdb3bbe37f](https://linux-hardware.org/?probe=bdb3bbe37f) | Jun 07, 2022 |
| Lenovo        | Z41-70 80K5                 | [3419d2fd18](https://linux-hardware.org/?probe=3419d2fd18) | Jun 06, 2022 |
| HP            | Pavilion 15                 | [5e4d9a126e](https://linux-hardware.org/?probe=5e4d9a126e) | Jun 05, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| Acer          | Aspire A514-54G             | [1019de0d68](https://linux-hardware.org/?probe=1019de0d68) | Jun 01, 2022 |
| ASUSTek       | N550JV                      | [2652284f1a](https://linux-hardware.org/?probe=2652284f1a) | May 31, 2022 |
| Acer          | Aspire 4720Z                | [a1dd5003f5](https://linux-hardware.org/?probe=a1dd5003f5) | May 30, 2022 |
| AXIOO         | NEON HNM MODEL              | [0fbd1cf4af](https://linux-hardware.org/?probe=0fbd1cf4af) | May 30, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | GL502VMK                    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| Lenovo        | G400 20235                  | [351b94ec15](https://linux-hardware.org/?probe=351b94ec15) | May 25, 2022 |
| HP            | 1000                        | [e83bc1e8fe](https://linux-hardware.org/?probe=e83bc1e8fe) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| ASUSTek       | K43U                        | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| MSI           | Modern 14 B11MO             | [c3b01c8c1b](https://linux-hardware.org/?probe=c3b01c8c1b) | May 20, 2022 |
| ASUSTek       | K43U                        | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [843a31b222](https://linux-hardware.org/?probe=843a31b222) | May 17, 2022 |
| Apple         | MacBookPro9,2               | [cfba770336](https://linux-hardware.org/?probe=cfba770336) | May 17, 2022 |
| Apple         | MacBookPro9,2               | [c19acfde6f](https://linux-hardware.org/?probe=c19acfde6f) | May 17, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [e633129a51](https://linux-hardware.org/?probe=e633129a51) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| MSI           | Modern 14 B5M               | [b207ce7566](https://linux-hardware.org/?probe=b207ce7566) | May 12, 2022 |
| Acer          | Aspire E5-476G              | [98b0999339](https://linux-hardware.org/?probe=98b0999339) | May 12, 2022 |
| Acer          | Aspire E5-476G              | [c4e0e740bb](https://linux-hardware.org/?probe=c4e0e740bb) | May 12, 2022 |
| Acer          | V1.24                       | [186531d4d8](https://linux-hardware.org/?probe=186531d4d8) | May 11, 2022 |
| Sony          | SVS13137PGB                 | [6dd2b49c52](https://linux-hardware.org/?probe=6dd2b49c52) | May 10, 2022 |
| Acer          | Nitro AN515-52              | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Acer          | Swift SF314-41              | [108b57a5a7](https://linux-hardware.org/?probe=108b57a5a7) | May 10, 2022 |
| Acer          | Aspire A514-54G             | [ec1fa8e360](https://linux-hardware.org/?probe=ec1fa8e360) | May 08, 2022 |
| Acer          | Aspire A514-54G             | [b4b52aad69](https://linux-hardware.org/?probe=b4b52aad69) | May 07, 2022 |
| Acer          | Aspire V5-431               | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [4dcc86a60e](https://linux-hardware.org/?probe=4dcc86a60e) | May 03, 2022 |
| MSI           | Modern 14 B5M               | [04dee023e6](https://linux-hardware.org/?probe=04dee023e6) | May 01, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [db2efb40d4](https://linux-hardware.org/?probe=db2efb40d4) | May 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| ASUSTek       | X200MA                      | [f93f8fcb35](https://linux-hardware.org/?probe=f93f8fcb35) | Apr 28, 2022 |
| Dell          | Latitude E6510              | [10d60e00c2](https://linux-hardware.org/?probe=10d60e00c2) | Apr 27, 2022 |
| ASUSTek       | X455LD                      | [9f98b410f6](https://linux-hardware.org/?probe=9f98b410f6) | Apr 26, 2022 |
| Gigabyte      | M912                        | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | X450LCP                     | [a2ed4903be](https://linux-hardware.org/?probe=a2ed4903be) | Apr 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c90694a42c](https://linux-hardware.org/?probe=c90694a42c) | Apr 23, 2022 |
| Gigabyte      | AERO 15XV8                  | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [345734b3fd](https://linux-hardware.org/?probe=345734b3fd) | Apr 07, 2022 |
| Acer          | Aspire 4720Z                | [eb44050489](https://linux-hardware.org/?probe=eb44050489) | Apr 07, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| ASUSTek       | X455YA                      | [cf17e2bba2](https://linux-hardware.org/?probe=cf17e2bba2) | Apr 03, 2022 |
| Acer          | Aspire 4720Z                | [c3651e4d3d](https://linux-hardware.org/?probe=c3651e4d3d) | Apr 01, 2022 |
| Dell          | Latitude E6230              | [c45161f6f3](https://linux-hardware.org/?probe=c45161f6f3) | Mar 31, 2022 |
| HP            | Pavilion 14                 | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Infinix       | INBook X1                   | [a06d137316](https://linux-hardware.org/?probe=a06d137316) | Mar 28, 2022 |
| MSI           | GF63 Thin 9SCXR             | [46acaeb2db](https://linux-hardware.org/?probe=46acaeb2db) | Mar 27, 2022 |
| Dell          | Latitude E7240              | [02c34ca310](https://linux-hardware.org/?probe=02c34ca310) | Mar 25, 2022 |
| ASUSTek       | X455YA                      | [b0469d5342](https://linux-hardware.org/?probe=b0469d5342) | Mar 25, 2022 |
| Sony          | VPCSB35FG                   | [79d0465072](https://linux-hardware.org/?probe=79d0465072) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | [1b7f98b34d](https://linux-hardware.org/?probe=1b7f98b34d) | Mar 23, 2022 |
| ASUSTek       | X456UQK                     | [863693cc0a](https://linux-hardware.org/?probe=863693cc0a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [f0047d02ea](https://linux-hardware.org/?probe=f0047d02ea) | Mar 22, 2022 |
| Dell          | Inspiron 13-5368            | [d98411620e](https://linux-hardware.org/?probe=d98411620e) | Mar 21, 2022 |
| ASUSTek       | K46CA                       | [08985cbe9e](https://linux-hardware.org/?probe=08985cbe9e) | Mar 21, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| Clevo         | W240HU/W250HUQ              | [222cbe9b4e](https://linux-hardware.org/?probe=222cbe9b4e) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| ASUSTek       | X441NA                      | [b7cf53ebcc](https://linux-hardware.org/?probe=b7cf53ebcc) | Mar 15, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | Notebook                    | [6ae78b432d](https://linux-hardware.org/?probe=6ae78b432d) | Mar 12, 2022 |
| Dell          | Latitude E7240              | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [e39d0d9111](https://linux-hardware.org/?probe=e39d0d9111) | Mar 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| ASUSTek       | GL553VD                     | [5e43e1dd7b](https://linux-hardware.org/?probe=5e43e1dd7b) | Mar 11, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [ed4db5233e](https://linux-hardware.org/?probe=ed4db5233e) | Mar 10, 2022 |
| ASUSTek       | X450EA                      | [a7394d72a0](https://linux-hardware.org/?probe=a7394d72a0) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| HP            | Pavilion g4                 | [3ff8cf8ed0](https://linux-hardware.org/?probe=3ff8cf8ed0) | Mar 08, 2022 |
| Sony          | VPCSB35FG                   | [b8a266ddc0](https://linux-hardware.org/?probe=b8a266ddc0) | Mar 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| Toshiba       | PORTEGE R835                | [67e8021c81](https://linux-hardware.org/?probe=67e8021c81) | Mar 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e7d5945f3d](https://linux-hardware.org/?probe=e7d5945f3d) | Mar 05, 2022 |
| Lenovo        | G40-45 80E1                 | [28f40df81d](https://linux-hardware.org/?probe=28f40df81d) | Mar 04, 2022 |
| ASUSTek       | UL20A                       | [c4efddb6b4](https://linux-hardware.org/?probe=c4efddb6b4) | Mar 02, 2022 |
| Fujitsu       | Unknown                     | [bc81b988ce](https://linux-hardware.org/?probe=bc81b988ce) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [621999b245](https://linux-hardware.org/?probe=621999b245) | Feb 24, 2022 |
| Dell          | Vostro 5470                 | [5ba37db2b4](https://linux-hardware.org/?probe=5ba37db2b4) | Feb 23, 2022 |
| Dell          | Latitude E7240              | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Acer          | Aspire 4720Z                | [eba3609129](https://linux-hardware.org/?probe=eba3609129) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| Acer          | One Z1402                   | [8746e0e3e7](https://linux-hardware.org/?probe=8746e0e3e7) | Feb 18, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1582806778](https://linux-hardware.org/?probe=1582806778) | Feb 17, 2022 |
| ASUSTek       | X540LA                      | [b2efca795b](https://linux-hardware.org/?probe=b2efca795b) | Feb 17, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [e3dfc424ca](https://linux-hardware.org/?probe=e3dfc424ca) | Feb 16, 2022 |
| Fujitsu       | FMVNA1SE                    | [e2cd0bdcb5](https://linux-hardware.org/?probe=e2cd0bdcb5) | Feb 14, 2022 |
| Toshiba       | Satellite C840              | [cb53c43003](https://linux-hardware.org/?probe=cb53c43003) | Feb 13, 2022 |
| Lenovo        | IdeaPad S205 Brazos         | [402bdafb5f](https://linux-hardware.org/?probe=402bdafb5f) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [46d98c991e](https://linux-hardware.org/?probe=46d98c991e) | Feb 12, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [5d4b14e3e0](https://linux-hardware.org/?probe=5d4b14e3e0) | Feb 12, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [eea0ec2b64](https://linux-hardware.org/?probe=eea0ec2b64) | Feb 12, 2022 |
| Toshiba       | Satellite C800D             | [5cdc03cbdf](https://linux-hardware.org/?probe=5cdc03cbdf) | Feb 10, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [54e246f496](https://linux-hardware.org/?probe=54e246f496) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [aa037a1c8c](https://linux-hardware.org/?probe=aa037a1c8c) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [0de3e1022e](https://linux-hardware.org/?probe=0de3e1022e) | Feb 09, 2022 |
| Acer          | Nitro AN515-54              | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [5e0e5de165](https://linux-hardware.org/?probe=5e0e5de165) | Feb 07, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [aaceb070e8](https://linux-hardware.org/?probe=aaceb070e8) | Feb 07, 2022 |
| ASUSTek       | X455LD                      | [324512f303](https://linux-hardware.org/?probe=324512f303) | Feb 06, 2022 |
| Lenovo        | ThinkPad W520 427637U       | [f9eb52038d](https://linux-hardware.org/?probe=f9eb52038d) | Feb 01, 2022 |
| Dell          | Inspiron 5480               | [85796c8359](https://linux-hardware.org/?probe=85796c8359) | Jan 28, 2022 |
| Dell          | Inspiron 5480               | [59b6841322](https://linux-hardware.org/?probe=59b6841322) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [774625ff90](https://linux-hardware.org/?probe=774625ff90) | Jan 24, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [e7c5bda932](https://linux-hardware.org/?probe=e7c5bda932) | Jan 24, 2022 |
| ASUSTek       | X450CP                      | [3f431523c1](https://linux-hardware.org/?probe=3f431523c1) | Jan 22, 2022 |
| Acer          | Swift SF314-43              | [567c5725d5](https://linux-hardware.org/?probe=567c5725d5) | Jan 22, 2022 |
| Sony          | SVE14A15FGB                 | [c35af68d7b](https://linux-hardware.org/?probe=c35af68d7b) | Jan 21, 2022 |
| Acer          | Aspire E5-471               | [a7c6bed4e1](https://linux-hardware.org/?probe=a7c6bed4e1) | Jan 21, 2022 |
| Sony          | SVD13213SGW                 | [ee9e63ab7c](https://linux-hardware.org/?probe=ee9e63ab7c) | Jan 21, 2022 |
| Acer          | Nitro AN515-52              | [e4791d09ec](https://linux-hardware.org/?probe=e4791d09ec) | Jan 20, 2022 |
| Lenovo        | IdeaPad 305-14IBD 80R1      | [f963f78bc6](https://linux-hardware.org/?probe=f963f78bc6) | Jan 20, 2022 |
| MSI           | Modern 14 B5M               | [ae605d8a23](https://linux-hardware.org/?probe=ae605d8a23) | Jan 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [c021e3bb40](https://linux-hardware.org/?probe=c021e3bb40) | Jan 18, 2022 |
| Acer          | Aspire E5-471               | [bf81e9a289](https://linux-hardware.org/?probe=bf81e9a289) | Jan 17, 2022 |
| Toshiba       | PORTEGE Z30-A               | [6df479c161](https://linux-hardware.org/?probe=6df479c161) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Lenovo        | G400s 20244                 | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| Dell          | Vostro 5581                 | [45f89f3b39](https://linux-hardware.org/?probe=45f89f3b39) | Jan 13, 2022 |
| MSI           | Modern 14 B5M               | [4822adcbc3](https://linux-hardware.org/?probe=4822adcbc3) | Jan 09, 2022 |
| MSI           | GL65 9SC                    | [24c204f7cf](https://linux-hardware.org/?probe=24c204f7cf) | Jan 09, 2022 |
| Dell          | Latitude E7250              | [e586dba516](https://linux-hardware.org/?probe=e586dba516) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Dell          | Inspiron 5570               | [2268237364](https://linux-hardware.org/?probe=2268237364) | Jan 08, 2022 |
| MSI           | Modern 14 B5M               | [ea82b6b417](https://linux-hardware.org/?probe=ea82b6b417) | Jan 08, 2022 |
| ASUSTek       | N43SL                       | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | U310                        | [47b64f9b71](https://linux-hardware.org/?probe=47b64f9b71) | Jan 04, 2022 |
| ASUSTek       | TP300LD                     | [2048e4ff56](https://linux-hardware.org/?probe=2048e4ff56) | Jan 04, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [954bd9f15e](https://linux-hardware.org/?probe=954bd9f15e) | Jan 03, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [5a0df8b1d8](https://linux-hardware.org/?probe=5a0df8b1d8) | Jan 03, 2022 |
| Acer          | Aspire 4720Z                | [1928762a58](https://linux-hardware.org/?probe=1928762a58) | Jan 02, 2022 |
| Acer          | Aspire E5-471               | [ad8cdd464b](https://linux-hardware.org/?probe=ad8cdd464b) | Jan 01, 2022 |
| ASUSTek       | TP300LD                     | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [a9e50f6f42](https://linux-hardware.org/?probe=a9e50f6f42) | Dec 28, 2021 |
| Lenovo        | G40-45 80E1                 | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| HP            | Pavilion 14                 | [b212043e80](https://linux-hardware.org/?probe=b212043e80) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Fujitsu       | FMVNA7BEC                   | [5a7719cad2](https://linux-hardware.org/?probe=5a7719cad2) | Dec 23, 2021 |
| Acer          | Aspire E1-471G              | [93b181f3fd](https://linux-hardware.org/?probe=93b181f3fd) | Dec 21, 2021 |
| Dell          | Latitude E5400              | [ea58337ba8](https://linux-hardware.org/?probe=ea58337ba8) | Dec 20, 2021 |
| Toshiba       | Dakar10FW8                  | [937d3de436](https://linux-hardware.org/?probe=937d3de436) | Dec 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [f279fb7b6f](https://linux-hardware.org/?probe=f279fb7b6f) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [635ec3d5d2](https://linux-hardware.org/?probe=635ec3d5d2) | Dec 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ee7ae7b860](https://linux-hardware.org/?probe=ee7ae7b860) | Dec 06, 2021 |
| ASUSTek       | X200MA                      | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | 700T                        | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| ASUSTek       | X455LD                      | [8fcb88c027](https://linux-hardware.org/?probe=8fcb88c027) | Nov 30, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [8cffa892b2](https://linux-hardware.org/?probe=8cffa892b2) | Nov 26, 2021 |
| Acer          | Aspire 4732Z                | [7376dc0d58](https://linux-hardware.org/?probe=7376dc0d58) | Nov 25, 2021 |
| Acer          | Aspire 4732Z                | [d020b5f5c5](https://linux-hardware.org/?probe=d020b5f5c5) | Nov 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a87f01aa8a](https://linux-hardware.org/?probe=a87f01aa8a) | Nov 25, 2021 |
| Acer          | Swift SF514-53T             | [09cc50e9eb](https://linux-hardware.org/?probe=09cc50e9eb) | Nov 23, 2021 |
| ASUSTek       | X455LD                      | [34d8f7fdbb](https://linux-hardware.org/?probe=34d8f7fdbb) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| HP            | ENVY TS 15                  | [ca6e82745c](https://linux-hardware.org/?probe=ca6e82745c) | Nov 22, 2021 |
| ASUSTek       | K45VD                       | [4a655e0c04](https://linux-hardware.org/?probe=4a655e0c04) | Nov 22, 2021 |
| Acer          | Swift SF514-53T             | [dbca729f8c](https://linux-hardware.org/?probe=dbca729f8c) | Nov 20, 2021 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | [34fb650910](https://linux-hardware.org/?probe=34fb650910) | Nov 16, 2021 |
| Dell          | Vostro 3400                 | [f6ba3e3359](https://linux-hardware.org/?probe=f6ba3e3359) | Nov 15, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Notebook      | P870DM                      | [7681edf3ee](https://linux-hardware.org/?probe=7681edf3ee) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | [fa2cb4cfff](https://linux-hardware.org/?probe=fa2cb4cfff) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | [53cf9a7e19](https://linux-hardware.org/?probe=53cf9a7e19) | Nov 12, 2021 |
| Acer          | Swift SF514-52T             | [020a93edbc](https://linux-hardware.org/?probe=020a93edbc) | Nov 10, 2021 |
| MSI           | GL62M 7RDX                  | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| ASUSTek       | X550ZE                      | [b27a794243](https://linux-hardware.org/?probe=b27a794243) | Nov 09, 2021 |
| HP            | Notebook                    | [9334c94844](https://linux-hardware.org/?probe=9334c94844) | Nov 07, 2021 |
| Acer          | Swift SF314-41              | [ef268f8220](https://linux-hardware.org/?probe=ef268f8220) | Nov 07, 2021 |
| Acer          | Swift SF314-56G             | [bf298c7d2d](https://linux-hardware.org/?probe=bf298c7d2d) | Nov 07, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [fe34c12d67](https://linux-hardware.org/?probe=fe34c12d67) | Nov 03, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a0bd3fa08](https://linux-hardware.org/?probe=3a0bd3fa08) | Nov 01, 2021 |
| Acer          | Swift SF314-43              | [4881a9a93c](https://linux-hardware.org/?probe=4881a9a93c) | Oct 31, 2021 |
| Lenovo        | G40-45 80E1                 | [0cdc6e9d84](https://linux-hardware.org/?probe=0cdc6e9d84) | Oct 28, 2021 |
| Dell          | Latitude E6440              | [00e8b6e3fd](https://linux-hardware.org/?probe=00e8b6e3fd) | Oct 24, 2021 |
| MSI           | Bravo 15 B5DD               | [afa573d049](https://linux-hardware.org/?probe=afa573d049) | Oct 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [78738c3586](https://linux-hardware.org/?probe=78738c3586) | Oct 22, 2021 |
| Dell          | G7 7588                     | [af1479f2fe](https://linux-hardware.org/?probe=af1479f2fe) | Oct 20, 2021 |
| Dell          | G7 7588                     | [0464fb8af6](https://linux-hardware.org/?probe=0464fb8af6) | Oct 20, 2021 |
| Dell          | Inspiron 1440               | [9e9967a3fa](https://linux-hardware.org/?probe=9e9967a3fa) | Oct 17, 2021 |
| Acer          | Aspire 4738Z                | [8962990035](https://linux-hardware.org/?probe=8962990035) | Oct 16, 2021 |
| ASUSTek       | U36SD                       | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| ASUSTek       | 1215B                       | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| ASUSTek       | K43SV                       | [6c0858f414](https://linux-hardware.org/?probe=6c0858f414) | Oct 08, 2021 |
| ASUSTek       | K43SV                       | [cff7419d9e](https://linux-hardware.org/?probe=cff7419d9e) | Oct 08, 2021 |
| HP            | Pavilion 14                 | [0c0ee7fe52](https://linux-hardware.org/?probe=0c0ee7fe52) | Oct 05, 2021 |
| Acer          | Aspire 4750                 | [b00fc610cd](https://linux-hardware.org/?probe=b00fc610cd) | Oct 05, 2021 |
| HP            | Laptop 14-bw0xx             | [5856720999](https://linux-hardware.org/?probe=5856720999) | Oct 04, 2021 |
| ASUSTek       | X441BA                      | [ae6206875f](https://linux-hardware.org/?probe=ae6206875f) | Oct 03, 2021 |
| ASUSTek       | X441BA                      | [692a1a1a57](https://linux-hardware.org/?probe=692a1a1a57) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | Laptop 14s-cf3xxx           | [1c4d130d6a](https://linux-hardware.org/?probe=1c4d130d6a) | Oct 01, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [2b03e34e82](https://linux-hardware.org/?probe=2b03e34e82) | Sep 30, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| HP            | EliteBook 2560p             | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Acer          | Swift SFX14-41G             | [cb763824f9](https://linux-hardware.org/?probe=cb763824f9) | Sep 25, 2021 |
| Acer          | Aspire 4752                 | [c68b87dd56](https://linux-hardware.org/?probe=c68b87dd56) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [39921c4f34](https://linux-hardware.org/?probe=39921c4f34) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| Lenovo        | ThinkBook 14s-IML 20RS      | [f93df3c890](https://linux-hardware.org/?probe=f93df3c890) | Sep 19, 2021 |
| Acer          | Aspire 4752                 | [c5758f5a05](https://linux-hardware.org/?probe=c5758f5a05) | Sep 18, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | [8ff619f5f3](https://linux-hardware.org/?probe=8ff619f5f3) | Sep 17, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | [57dc237470](https://linux-hardware.org/?probe=57dc237470) | Sep 17, 2021 |
| Acer          | Swift SF314-43              | [e5804af7f6](https://linux-hardware.org/?probe=e5804af7f6) | Sep 14, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [e84546c757](https://linux-hardware.org/?probe=e84546c757) | Sep 14, 2021 |
| Acer          | Aspire 4752                 | [2cc8dabf64](https://linux-hardware.org/?probe=2cc8dabf64) | Sep 11, 2021 |
| HP            | Compaq Presario CQ40        | [62284df376](https://linux-hardware.org/?probe=62284df376) | Sep 10, 2021 |
| HP            | Laptop 14s-cf3xxx           | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a629879646](https://linux-hardware.org/?probe=a629879646) | Sep 06, 2021 |
| Dell          | XPS 15 7590                 | [82904dfc03](https://linux-hardware.org/?probe=82904dfc03) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Acer          | Aspire 4750                 | [f88ba2a8ea](https://linux-hardware.org/?probe=f88ba2a8ea) | Sep 04, 2021 |
| HP            | 14                          | [9f574ea069](https://linux-hardware.org/?probe=9f574ea069) | Sep 04, 2021 |
| Acer          | Aspire V3-371               | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [0bfcbeeab5](https://linux-hardware.org/?probe=0bfcbeeab5) | Sep 02, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [808ff28683](https://linux-hardware.org/?probe=808ff28683) | Aug 31, 2021 |
| ASUSTek       | GL553VD                     | [d6a7f7807d](https://linux-hardware.org/?probe=d6a7f7807d) | Aug 26, 2021 |
| Acer          | Aspire A315-42              | [6e6129ddbe](https://linux-hardware.org/?probe=6e6129ddbe) | Aug 26, 2021 |
| HP            | ProBook 4430s               | [e764612d91](https://linux-hardware.org/?probe=e764612d91) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [49aac2eefe](https://linux-hardware.org/?probe=49aac2eefe) | Aug 24, 2021 |
| Acer          | Aspire V3-371               | [d34df8e36e](https://linux-hardware.org/?probe=d34df8e36e) | Aug 23, 2021 |
| Acer          | Aspire 4750                 | [6f5d61dc20](https://linux-hardware.org/?probe=6f5d61dc20) | Aug 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [b57e843f46](https://linux-hardware.org/?probe=b57e843f46) | Aug 22, 2021 |
| Acer          | Swift SF314-41              | [34d2f87751](https://linux-hardware.org/?probe=34d2f87751) | Aug 18, 2021 |
| Fujitsu       | FMVNA6HG                    | [3af7eec32c](https://linux-hardware.org/?probe=3af7eec32c) | Aug 16, 2021 |
| Toshiba       | Satellite R630              | [b2b7f07b7a](https://linux-hardware.org/?probe=b2b7f07b7a) | Aug 12, 2021 |
| HP            | ENVY Notebook               | [f2dea0236d](https://linux-hardware.org/?probe=f2dea0236d) | Aug 11, 2021 |
| HP            | ENVY Notebook               | [ce3be0798b](https://linux-hardware.org/?probe=ce3be0798b) | Aug 11, 2021 |
| Toshiba       | Satellite M100              | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | [3d8ebc06f6](https://linux-hardware.org/?probe=3d8ebc06f6) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | [bb3eb06270](https://linux-hardware.org/?probe=bb3eb06270) | Aug 09, 2021 |
| Acer          | Nitro AN515-56              | [867c7e2bb4](https://linux-hardware.org/?probe=867c7e2bb4) | Aug 09, 2021 |
| Lenovo        | G40-45 80E1                 | [a9947e6264](https://linux-hardware.org/?probe=a9947e6264) | Aug 08, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6d691b88f0](https://linux-hardware.org/?probe=6d691b88f0) | Aug 08, 2021 |
| Acer          | Aspire 4752                 | [16f9fcdeed](https://linux-hardware.org/?probe=16f9fcdeed) | Aug 08, 2021 |
| Acer          | Swift SF314-41              | [4f141cc864](https://linux-hardware.org/?probe=4f141cc864) | Aug 07, 2021 |
| Acer          | Swift SF314-41              | [31e6bda7a8](https://linux-hardware.org/?probe=31e6bda7a8) | Aug 07, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Lenovo        | G40-45 80E1                 | [346da0d23a](https://linux-hardware.org/?probe=346da0d23a) | Aug 06, 2021 |
| ASUSTek       | X455YA                      | [7ceff8b834](https://linux-hardware.org/?probe=7ceff8b834) | Aug 05, 2021 |
| HP            | Laptop 15s-fq2xxx           | [506b637bd3](https://linux-hardware.org/?probe=506b637bd3) | Aug 05, 2021 |
| Lenovo        | G40-45 80E1                 | [26d0a4788c](https://linux-hardware.org/?probe=26d0a4788c) | Aug 03, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1a72340ff4](https://linux-hardware.org/?probe=1a72340ff4) | Aug 01, 2021 |
| Lenovo        | G400s 20244                 | [43fe80380d](https://linux-hardware.org/?probe=43fe80380d) | Aug 01, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Lenovo        | G40-45 80E1                 | [597f4ff063](https://linux-hardware.org/?probe=597f4ff063) | Jul 29, 2021 |
| Dell          | Inspiron 3458               | [43d4236000](https://linux-hardware.org/?probe=43d4236000) | Jul 27, 2021 |
| Dell          | Vostro 14-3468              | [c222cecae0](https://linux-hardware.org/?probe=c222cecae0) | Jul 27, 2021 |
| Acer          | Swift SF314-43              | [690b0d3adc](https://linux-hardware.org/?probe=690b0d3adc) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | [3c2e8b0074](https://linux-hardware.org/?probe=3c2e8b0074) | Jul 26, 2021 |
| Acer          | Aspire A315-42              | [d59705a499](https://linux-hardware.org/?probe=d59705a499) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad X220 4291G75       | [fc0c3340bd](https://linux-hardware.org/?probe=fc0c3340bd) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [c466690f21](https://linux-hardware.org/?probe=c466690f21) | Jul 25, 2021 |
| Toshiba       | PORTEGE M800                | [6de34f58af](https://linux-hardware.org/?probe=6de34f58af) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [bfbf5b3302](https://linux-hardware.org/?probe=bfbf5b3302) | Jul 25, 2021 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [a8970607e0](https://linux-hardware.org/?probe=a8970607e0) | Jul 23, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [8d72c96d15](https://linux-hardware.org/?probe=8d72c96d15) | Jul 23, 2021 |
| Acer          | Aspire V5-431               | [0616ef50a5](https://linux-hardware.org/?probe=0616ef50a5) | Jul 22, 2021 |
| Apple         | MacBookPro6,2               | [22a976ce11](https://linux-hardware.org/?probe=22a976ce11) | Jul 21, 2021 |
| Lenovo        | G40-45 80E1                 | [c6b76cb1f9](https://linux-hardware.org/?probe=c6b76cb1f9) | Jul 21, 2021 |
| Acer          | Nitro AN515-45              | [714ce6dfc9](https://linux-hardware.org/?probe=714ce6dfc9) | Jul 19, 2021 |
| Acer          | Nitro AN515-45              | [e1d1356c93](https://linux-hardware.org/?probe=e1d1356c93) | Jul 19, 2021 |
| Acer          | Aspire V5-431               | [e0519d6c32](https://linux-hardware.org/?probe=e0519d6c32) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [d3561fadd3](https://linux-hardware.org/?probe=d3561fadd3) | Jul 18, 2021 |
| HP            | Laptop 14s-dk0xxx           | [6cc56f596f](https://linux-hardware.org/?probe=6cc56f596f) | Jul 17, 2021 |
| Lenovo        | ThinkPad X250 20CLA200ID    | [28c05ab175](https://linux-hardware.org/?probe=28c05ab175) | Jul 17, 2021 |
| Unknown       | Unknown                     | [1d1680d9c3](https://linux-hardware.org/?probe=1d1680d9c3) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4e75379022](https://linux-hardware.org/?probe=4e75379022) | Jul 16, 2021 |
| Dell          | Latitude E5520              | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [393ed0c954](https://linux-hardware.org/?probe=393ed0c954) | Jul 12, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [cd0155712e](https://linux-hardware.org/?probe=cd0155712e) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [9727587570](https://linux-hardware.org/?probe=9727587570) | Jul 10, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | [3e43acf8af](https://linux-hardware.org/?probe=3e43acf8af) | Jul 08, 2021 |
| Lenovo        | ThinkPad T430 2349SU6       | [9cd74fc6d1](https://linux-hardware.org/?probe=9cd74fc6d1) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | [196e6c6ec4](https://linux-hardware.org/?probe=196e6c6ec4) | Jul 08, 2021 |
| ASUSTek       | X450EA                      | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| ASUSTek       | K84L                        | [01c9e0cbe1](https://linux-hardware.org/?probe=01c9e0cbe1) | Jul 03, 2021 |
| Acer          | Aspire A515-45              | [42249c6e47](https://linux-hardware.org/?probe=42249c6e47) | Jul 02, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c980ba6ae7](https://linux-hardware.org/?probe=c980ba6ae7) | Jul 02, 2021 |
| Acer          | Aspire A315-41              | [67c143c435](https://linux-hardware.org/?probe=67c143c435) | Jul 01, 2021 |
| Dell          | Latitude E5410              | [b047bdb721](https://linux-hardware.org/?probe=b047bdb721) | Jun 25, 2021 |
| Acer          | Aspire 4752                 | [16a063ab28](https://linux-hardware.org/?probe=16a063ab28) | Jun 24, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e135f49903](https://linux-hardware.org/?probe=e135f49903) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [114ba38c36](https://linux-hardware.org/?probe=114ba38c36) | Jun 20, 2021 |
| Acer          | Aspire E5-475G              | [0d6df01751](https://linux-hardware.org/?probe=0d6df01751) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [0cb7e73af9](https://linux-hardware.org/?probe=0cb7e73af9) | Jun 19, 2021 |
| Acer          | Aspire E5-475G              | [c1c0f815dc](https://linux-hardware.org/?probe=c1c0f815dc) | Jun 15, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7572d1aea9](https://linux-hardware.org/?probe=7572d1aea9) | Jun 13, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [9551aa9271](https://linux-hardware.org/?probe=9551aa9271) | Jun 06, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [6d45501f90](https://linux-hardware.org/?probe=6d45501f90) | Jun 05, 2021 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [8af935f813](https://linux-hardware.org/?probe=8af935f813) | Jun 02, 2021 |
| Acer          | Aspire E5-476G              | [ecbaba7315](https://linux-hardware.org/?probe=ecbaba7315) | May 31, 2021 |
| HP            | EliteBook Folio 9470m       | [3e6a2f7b59](https://linux-hardware.org/?probe=3e6a2f7b59) | May 27, 2021 |
| ASUSTek       | K45DR                       | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Dell          | Latitude E6410              | [7e35c63842](https://linux-hardware.org/?probe=7e35c63842) | May 26, 2021 |
| Acer          | Aspire 4752                 | [7ca3035a20](https://linux-hardware.org/?probe=7ca3035a20) | May 26, 2021 |
| ASUSTek       | K45DR                       | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| ASUSTek       | X550JX                      | [c837a795d7](https://linux-hardware.org/?probe=c837a795d7) | May 19, 2021 |
| Acer          | Okinawa                     | [9579ede8a9](https://linux-hardware.org/?probe=9579ede8a9) | May 19, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [1ad049bf43](https://linux-hardware.org/?probe=1ad049bf43) | May 17, 2021 |
| Acer          | Aspire 4752                 | [b26958098c](https://linux-hardware.org/?probe=b26958098c) | May 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [9a69a064a2](https://linux-hardware.org/?probe=9a69a064a2) | May 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0d732d9421](https://linux-hardware.org/?probe=0d732d9421) | May 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0beb84ac05](https://linux-hardware.org/?probe=0beb84ac05) | Apr 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2fddce1bd1](https://linux-hardware.org/?probe=2fddce1bd1) | Apr 29, 2021 |
| ASUSTek       | X453SA                      | [e72a666c50](https://linux-hardware.org/?probe=e72a666c50) | Apr 28, 2021 |
| Acer          | Aspire 4750                 | [dcfd3e0bb5](https://linux-hardware.org/?probe=dcfd3e0bb5) | Apr 24, 2021 |
| Acer          | Aspire 4750                 | [5b1db085fc](https://linux-hardware.org/?probe=5b1db085fc) | Apr 24, 2021 |
| Dell          | Latitude 5400               | [a2fb8a380a](https://linux-hardware.org/?probe=a2fb8a380a) | Apr 23, 2021 |
| Dell          | Latitude 5400               | [e4a0edd922](https://linux-hardware.org/?probe=e4a0edd922) | Apr 23, 2021 |
| Acer          | Aspire A514-53              | [2a5c4baa8f](https://linux-hardware.org/?probe=2a5c4baa8f) | Apr 18, 2021 |
| Acer          | Swift SF314-41              | [fde9376452](https://linux-hardware.org/?probe=fde9376452) | Apr 16, 2021 |
| Acer          | Swift SF314-41              | [9f50b41201](https://linux-hardware.org/?probe=9f50b41201) | Apr 16, 2021 |
| ASUSTek       | X441UV                      | [8ee5e69c11](https://linux-hardware.org/?probe=8ee5e69c11) | Apr 16, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| Acer          | Aspire 4752                 | [dbc22d503d](https://linux-hardware.org/?probe=dbc22d503d) | Apr 12, 2021 |
| Acer          | Aspire 4752                 | [c6ef5b093d](https://linux-hardware.org/?probe=c6ef5b093d) | Apr 12, 2021 |
| HP            | EliteBook 840 G1            | [b14a1a07ac](https://linux-hardware.org/?probe=b14a1a07ac) | Apr 11, 2021 |
| Dell          | Inspiron 5570               | [059aa32bb7](https://linux-hardware.org/?probe=059aa32bb7) | Apr 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [4a05cec425](https://linux-hardware.org/?probe=4a05cec425) | Apr 10, 2021 |
| Acer          | Aspire 4741                 | [cf750140a8](https://linux-hardware.org/?probe=cf750140a8) | Apr 10, 2021 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | [156c9db184](https://linux-hardware.org/?probe=156c9db184) | Apr 10, 2021 |
| Lenovo        | IdeaPad Z410 20292          | [803bcbb44c](https://linux-hardware.org/?probe=803bcbb44c) | Apr 05, 2021 |
| HP            | EliteBook Folio 9470m       | [22fc47b193](https://linux-hardware.org/?probe=22fc47b193) | Apr 05, 2021 |
| HP            | Laptop 15-bw0xx             | [44efde8890](https://linux-hardware.org/?probe=44efde8890) | Apr 05, 2021 |
| HP            | 1000                        | [be995ccb43](https://linux-hardware.org/?probe=be995ccb43) | Apr 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [941b588cf9](https://linux-hardware.org/?probe=941b588cf9) | Apr 03, 2021 |
| Acer          | Aspire 4739                 | [19ba24510c](https://linux-hardware.org/?probe=19ba24510c) | Apr 02, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [c41ba66f79](https://linux-hardware.org/?probe=c41ba66f79) | Apr 01, 2021 |
| Lenovo        | V310-14ISK 80SX             | [463bdc0444](https://linux-hardware.org/?probe=463bdc0444) | Apr 01, 2021 |
| ASUSTek       | X550VX                      | [4d95cd31eb](https://linux-hardware.org/?probe=4d95cd31eb) | Mar 27, 2021 |
| Dell          | Latitude 5400               | [5cab0ca67e](https://linux-hardware.org/?probe=5cab0ca67e) | Mar 26, 2021 |
| ASUSTek       | K45VD                       | [74592068ee](https://linux-hardware.org/?probe=74592068ee) | Mar 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3d99b46431](https://linux-hardware.org/?probe=3d99b46431) | Mar 25, 2021 |
| Lenovo        | V310-14ISK 80SX             | [1ce5b4161e](https://linux-hardware.org/?probe=1ce5b4161e) | Mar 24, 2021 |
| ASUSTek       | X45U                        | [05632e634d](https://linux-hardware.org/?probe=05632e634d) | Mar 23, 2021 |
| Dell          | Vostro 3481                 | [63b8942776](https://linux-hardware.org/?probe=63b8942776) | Mar 12, 2021 |
| ASUSTek       | X441SA                      | [abec8a4c19](https://linux-hardware.org/?probe=abec8a4c19) | Mar 08, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [461b5d7b4b](https://linux-hardware.org/?probe=461b5d7b4b) | Mar 06, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [cb688e237f](https://linux-hardware.org/?probe=cb688e237f) | Mar 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [50a76385ba](https://linux-hardware.org/?probe=50a76385ba) | Mar 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [68d0129e2d](https://linux-hardware.org/?probe=68d0129e2d) | Mar 05, 2021 |
| Fujitsu       | LIFEBOOK AH544              | [80ce017529](https://linux-hardware.org/?probe=80ce017529) | Mar 04, 2021 |
| ASUSTek       | X442URR                     | [d8e04d832e](https://linux-hardware.org/?probe=d8e04d832e) | Mar 03, 2021 |
| ASUSTek       | UX303UB                     | [c4867a5743](https://linux-hardware.org/?probe=c4867a5743) | Mar 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [a5f08bd719](https://linux-hardware.org/?probe=a5f08bd719) | Mar 01, 2021 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [d3f1f06d5d](https://linux-hardware.org/?probe=d3f1f06d5d) | Feb 22, 2021 |
| HP            | Notebook                    | [e718153751](https://linux-hardware.org/?probe=e718153751) | Feb 22, 2021 |
| ASUSTek       | K42F                        | [2380c82b48](https://linux-hardware.org/?probe=2380c82b48) | Feb 20, 2021 |
| HP            | Notebook                    | [326de2e4f5](https://linux-hardware.org/?probe=326de2e4f5) | Feb 19, 2021 |
| ASUSTek       | U36SD                       | [981c7e8da7](https://linux-hardware.org/?probe=981c7e8da7) | Feb 19, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [f9abaeb3f9](https://linux-hardware.org/?probe=f9abaeb3f9) | Feb 18, 2021 |
| HP            | Laptop 14-bw0xx             | [1a3e26503a](https://linux-hardware.org/?probe=1a3e26503a) | Feb 17, 2021 |
| Acer          | Aspire E5-471G              | [3b58cbf4e6](https://linux-hardware.org/?probe=3b58cbf4e6) | Feb 17, 2021 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [5a09ac2a06](https://linux-hardware.org/?probe=5a09ac2a06) | Feb 16, 2021 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [9805e3bcb5](https://linux-hardware.org/?probe=9805e3bcb5) | Feb 16, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a0537ad7d5](https://linux-hardware.org/?probe=a0537ad7d5) | Feb 16, 2021 |
| Toshiba       | Satellite C855              | [60adcbc05d](https://linux-hardware.org/?probe=60adcbc05d) | Feb 16, 2021 |
| Timi          | TM1703                      | [4d64e40cca](https://linux-hardware.org/?probe=4d64e40cca) | Feb 14, 2021 |
| HP            | Pavilion Laptop 14-bf0xx    | [309266e981](https://linux-hardware.org/?probe=309266e981) | Feb 13, 2021 |
| ASUSTek       | X456UQK                     | [f0380f099d](https://linux-hardware.org/?probe=f0380f099d) | Feb 12, 2021 |
| ASUSTek       | K43E                        | [1604193c0f](https://linux-hardware.org/?probe=1604193c0f) | Feb 11, 2021 |
| Lenovo        | G50-80 80E5                 | [704dbacb0d](https://linux-hardware.org/?probe=704dbacb0d) | Feb 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [ec95272afa](https://linux-hardware.org/?probe=ec95272afa) | Feb 10, 2021 |
| Lenovo        | ThinkPad X131e 33741E0      | [4c52c9aa29](https://linux-hardware.org/?probe=4c52c9aa29) | Feb 06, 2021 |
| Acer          | NXHATSN00190808A906600      | [2ed3d18f0a](https://linux-hardware.org/?probe=2ed3d18f0a) | Feb 05, 2021 |
| ASUSTek       | N56VM                       | [d56280ec33](https://linux-hardware.org/?probe=d56280ec33) | Feb 05, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [f48cf2f332](https://linux-hardware.org/?probe=f48cf2f332) | Feb 05, 2021 |
| Compal        | PBL10                       | [5cf67578d7](https://linux-hardware.org/?probe=5cf67578d7) | Feb 04, 2021 |
| Compal        | PBL10                       | [a20e9d9588](https://linux-hardware.org/?probe=a20e9d9588) | Feb 04, 2021 |
| ASUSTek       | X442UQ                      | [f79d79fd99](https://linux-hardware.org/?probe=f79d79fd99) | Feb 04, 2021 |
| HP            | ZBook Studio G3             | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| HP            | EliteBook Folio 9470m       | [15b84d2abc](https://linux-hardware.org/?probe=15b84d2abc) | Feb 04, 2021 |
| ASUSTek       | X442UQ                      | [9b722252fa](https://linux-hardware.org/?probe=9b722252fa) | Feb 04, 2021 |
| HP            | Laptop 14-cm0xxx            | [2365556c9d](https://linux-hardware.org/?probe=2365556c9d) | Jan 31, 2021 |
| ASUSTek       | U36SD                       | [5267c17fbb](https://linux-hardware.org/?probe=5267c17fbb) | Jan 30, 2021 |
| HP            | ZBook 15 G2                 | [cebba8a2a8](https://linux-hardware.org/?probe=cebba8a2a8) | Jan 30, 2021 |
| Lenovo        | ThinkPad X280 20KES7YB00    | [b498c0fcba](https://linux-hardware.org/?probe=b498c0fcba) | Jan 29, 2021 |
| ASUSTek       | U36SD                       | [15288996d1](https://linux-hardware.org/?probe=15288996d1) | Jan 28, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Indonesia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 107       | 10.32%  |
| Ubuntu 18.04                 | 60        | 5.79%   |
| Ubuntu 22.04                 | 58        | 5.59%   |
| OpenMandriva 4.3             | 38        | 3.66%   |
| Arch Rolling                 | 29        | 2.8%    |
| OpenMandriva 4.2             | 23        | 2.22%   |
| Pop!_OS 22.04                | 20        | 1.93%   |
| KDE neon 20.04               | 19        | 1.83%   |
| Fedora 38                    | 18        | 1.74%   |
| Fedora 36                    | 18        | 1.74%   |
| Arch                         | 17        | 1.64%   |
| Manjaro                      | 15        | 1.45%   |
| Zorin 16                     | 14        | 1.35%   |
| Pop!_OS 20.04                | 14        | 1.35%   |
| ArcoLinux Rolling            | 14        | 1.35%   |
| Zorin 15                     | 13        | 1.25%   |
| Elementary 6.1               | 13        | 1.25%   |
| Debian 11                    | 13        | 1.25%   |
| Ubuntu 19.10                 | 12        | 1.16%   |
| OpenMandriva 23.08           | 12        | 1.16%   |
| Fedora 37                    | 12        | 1.16%   |
| Fedora 35                    | 12        | 1.16%   |
| Ubuntu 21.10                 | 11        | 1.06%   |
| OpenMandriva 23.03           | 11        | 1.06%   |
| Linux Mint 21.1              | 11        | 1.06%   |
| Linux Mint 20.3              | 11        | 1.06%   |
| Kubuntu 22.04                | 10        | 0.96%   |
| Xubuntu 20.04                | 9         | 0.87%   |
| OpenMandriva 23.01           | 9         | 0.87%   |
| Kubuntu 20.04                | 9         | 0.87%   |
| KDE neon 22.04               | 9         | 0.87%   |
| EndeavourOS Rolling          | 9         | 0.87%   |
| Linux Mint 20                | 8         | 0.77%   |
| Linux Mint 19.3              | 8         | 0.77%   |
| Debian 10                    | 8         | 0.77%   |
| Ubuntu 23.04                 | 7         | 0.68%   |
| Ubuntu 21.04                 | 7         | 0.68%   |
| Pop!_OS 21.04                | 7         | 0.68%   |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 0.68%   |
| Debian 12                    | 7         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 270       | 27.49%  |
| OpenMandriva  | 96        | 9.78%   |
| Fedora        | 72        | 7.33%   |
| Linux Mint    | 57        | 5.8%    |
| Pop!_OS       | 46        | 4.68%   |
| Arch          | 46        | 4.68%   |
| Manjaro       | 40        | 4.07%   |
| Debian        | 32        | 3.26%   |
| Zorin         | 30        | 3.05%   |
| KDE neon      | 29        | 2.95%   |
| Elementary    | 29        | 2.95%   |
| Kubuntu       | 26        | 2.65%   |
| Kali          | 24        | 2.44%   |
| Endless       | 21        | 2.14%   |
| Xubuntu       | 19        | 1.93%   |
| ArcoLinux     | 15        | 1.53%   |
| Lubuntu       | 14        | 1.43%   |
| Ubuntu MATE   | 10        | 1.02%   |
| ROSA          | 10        | 1.02%   |
| EndeavourOS   | 9         | 0.92%   |
| openSUSE      | 8         | 0.81%   |
| Parrot        | 6         | 0.61%   |
| Nobara        | 6         | 0.61%   |
| LMDE          | 6         | 0.61%   |
| Ubuntu Unity  | 5         | 0.51%   |
| Gentoo        | 5         | 0.51%   |
| SteamOS       | 4         | 0.41%   |
| MX            | 4         | 0.41%   |
| Deepin        | 4         | 0.41%   |
| Artix         | 4         | 0.41%   |
| Xero          | 3         | 0.31%   |
| Ubuntu Budgie | 3         | 0.31%   |
| Garuda Linux  | 3         | 0.31%   |
| Clear Linux   | 3         | 0.31%   |
| Solus         | 2         | 0.2%    |
| Chrome OS     | 2         | 0.2%    |
| CentOS        | 2         | 0.2%    |
| BlackPanther  | 2         | 0.2%    |
| AlmaLinux     | 2         | 0.2%    |
| Void Linux    | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 38        | 3.44%   |
| 5.10.14-desktop-1omv4002 | 23        | 2.08%   |
| 5.4.0-42-generic         | 16        | 1.45%   |
| 5.15.0-56-generic        | 13        | 1.18%   |
| 5.4.0-26-generic         | 12        | 1.09%   |
| 5.15.0-41-generic        | 11        | 1%      |
| 6.4.11-desktop-1omv2390  | 10        | 0.9%    |
| 6.2.6-desktop-1omv2390   | 10        | 0.9%    |
| 6.1.1-desktop-1omv2290   | 9         | 0.81%   |
| 5.4.0-52-generic         | 9         | 0.81%   |
| 5.15.0-46-generic        | 9         | 0.81%   |
| 5.15.0-48-generic        | 8         | 0.72%   |
| 5.15.0-47-generic        | 8         | 0.72%   |
| 5.0.0-25-generic         | 8         | 0.72%   |
| 4.18.0-15-generic        | 8         | 0.72%   |
| 5.4.0-58-generic         | 7         | 0.63%   |
| 5.4.0-54-generic         | 7         | 0.63%   |
| 5.15.0-58-generic        | 7         | 0.63%   |
| 5.11.0-37-generic        | 7         | 0.63%   |
| 5.8.0-48-generic         | 6         | 0.54%   |
| 5.3.0-46-generic         | 6         | 0.54%   |
| 5.19.0-35-generic        | 6         | 0.54%   |
| 5.15.0-52-generic        | 6         | 0.54%   |
| 5.15.0-43-generic        | 6         | 0.54%   |
| 6.2.0-26-generic         | 5         | 0.45%   |
| 5.8.0-41-generic         | 5         | 0.45%   |
| 5.4.0-80-generic         | 5         | 0.45%   |
| 5.4.0-45-generic         | 5         | 0.45%   |
| 5.19.0-46-generic        | 5         | 0.45%   |
| 5.15.0-53-generic        | 5         | 0.45%   |
| 5.11.0-7620-generic      | 5         | 0.45%   |
| 5.11.0-41-generic        | 5         | 0.45%   |
| 5.11.0-40-generic        | 5         | 0.45%   |
| 5.11.0-38-generic        | 5         | 0.45%   |
| 5.11.0-35-generic        | 5         | 0.45%   |
| 5.11.0-27-generic        | 5         | 0.45%   |
| 5.0.0-23-generic         | 5         | 0.45%   |
| 6.4.6-76060406-generic   | 4         | 0.36%   |
| 6.2.0-37-generic         | 4         | 0.36%   |
| 6.1.0-12-amd64           | 4         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 136       | 12.75%  |
| 5.15.0  | 109       | 10.22%  |
| 5.11.0  | 55        | 5.15%   |
| 5.8.0   | 41        | 3.84%   |
| 5.16.7  | 39        | 3.66%   |
| 5.13.0  | 37        | 3.47%   |
| 5.3.0   | 33        | 3.09%   |
| 5.0.0   | 30        | 2.81%   |
| 4.15.0  | 29        | 2.72%   |
| 6.2.0   | 28        | 2.62%   |
| 5.19.0  | 26        | 2.44%   |
| 5.10.0  | 25        | 2.34%   |
| 5.10.14 | 24        | 2.25%   |
| 6.1.0   | 18        | 1.69%   |
| 4.18.0  | 17        | 1.59%   |
| 6.4.11  | 13        | 1.22%   |
| 6.2.6   | 13        | 1.22%   |
| 4.19.0  | 13        | 1.22%   |
| 6.1.1   | 12        | 1.12%   |
| 6.5.5   | 10        | 0.94%   |
| 5.14.0  | 7         | 0.66%   |
| 6.5.0   | 6         | 0.56%   |
| 5.17.5  | 6         | 0.56%   |
| 5.16.0  | 6         | 0.56%   |
| 6.4.6   | 5         | 0.47%   |
| 6.5.3   | 4         | 0.37%   |
| 6.0.12  | 4         | 0.37%   |
| 5.15.12 | 4         | 0.37%   |
| 5.14.16 | 4         | 0.37%   |
| 4.4.0   | 4         | 0.37%   |
| 6.6.1   | 3         | 0.28%   |
| 6.5.6   | 3         | 0.28%   |
| 6.4.8   | 3         | 0.28%   |
| 6.4.10  | 3         | 0.28%   |
| 6.3.5   | 3         | 0.28%   |
| 6.3.3   | 3         | 0.28%   |
| 6.2.9   | 3         | 0.28%   |
| 6.2.8   | 3         | 0.28%   |
| 6.0.9   | 3         | 0.28%   |
| 6.0.0   | 3         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 144       | 13.71%  |
| 5.15    | 131       | 12.48%  |
| 5.10    | 74        | 7.05%   |
| 5.16    | 58        | 5.52%   |
| 5.11    | 58        | 5.52%   |
| 6.2     | 53        | 5.05%   |
| 5.8     | 52        | 4.95%   |
| 6.1     | 49        | 4.67%   |
| 5.13    | 41        | 3.9%    |
| 5.19    | 38        | 3.62%   |
| 5.3     | 35        | 3.33%   |
| 6.4     | 33        | 3.14%   |
| 5.0     | 32        | 3.05%   |
| 6.5     | 30        | 2.86%   |
| 4.15    | 29        | 2.76%   |
| 5.14    | 21        | 2%      |
| 6.0     | 20        | 1.9%    |
| 4.18    | 20        | 1.9%    |
| 5.17    | 18        | 1.71%   |
| 4.19    | 18        | 1.71%   |
| 6.3     | 15        | 1.43%   |
| 5.18    | 15        | 1.43%   |
| 5.9     | 12        | 1.14%   |
| 6.6     | 8         | 0.76%   |
| 4.9     | 8         | 0.76%   |
| 5.6     | 7         | 0.67%   |
| 5.12    | 6         | 0.57%   |
| 5.7     | 5         | 0.48%   |
| 5.5     | 5         | 0.48%   |
| 4.4     | 5         | 0.48%   |
| 5.2     | 2         | 0.19%   |
| 4.13    | 2         | 0.19%   |
| 4.10    | 2         | 0.19%   |
| 4.1     | 2         | 0.19%   |
| 5       | 1         | 0.1%    |
| 3.16    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 923       | 97.78%  |
| i686   | 21        | 2.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 410       | 41.54%  |
| KDE5            | 202       | 20.47%  |
| XFCE            | 82        | 8.31%   |
| Unknown         | 82        | 8.31%   |
| X-Cinnamon      | 56        | 5.67%   |
| Pantheon        | 28        | 2.84%   |
| MATE            | 25        | 2.53%   |
| KDE             | 18        | 1.82%   |
| LXQt            | 17        | 1.72%   |
| Cinnamon        | 12        | 1.22%   |
| Budgie          | 7         | 0.71%   |
| i3              | 6         | 0.61%   |
| Unity           | 5         | 0.51%   |
| Deepin          | 5         | 0.51%   |
| Hyprland        | 4         | 0.41%   |
| bspwm           | 4         | 0.41%   |
| sway            | 3         | 0.3%    |
| KDE4            | 3         | 0.3%    |
| GNOME Flashback | 3         | 0.3%    |
| dwm             | 3         | 0.3%    |
| qtile           | 2         | 0.2%    |
| ICEWM           | 2         | 0.2%    |
| Cutefish        | 2         | 0.2%    |
| xmonad          | 1         | 0.1%    |
| openbox         | 1         | 0.1%    |
| LXDE            | 1         | 0.1%    |
| Lubuntu         | 1         | 0.1%    |
| awesomeminimal  | 1         | 0.1%    |
| awesome         | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 712       | 73.1%   |
| Wayland | 199       | 20.43%  |
| Unknown | 56        | 5.75%   |
| Tty     | 7         | 0.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 403       | 41.29%  |
| SDDM    | 183       | 18.75%  |
| GDM     | 132       | 13.52%  |
| LightDM | 115       | 11.78%  |
| GDM3    | 107       | 10.96%  |
| TDM     | 29        | 2.97%   |
| KDM     | 3         | 0.31%   |
| SLiM    | 2         | 0.2%    |
| Ly      | 1         | 0.1%    |
| LXDM    | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 778       | 81.13%  |
| Unknown | 77        | 8.03%   |
| id_ID   | 65        | 6.78%   |
| en_GB   | 12        | 1.25%   |
| C       | 12        | 1.25%   |
| en_SG   | 3         | 0.31%   |
| en_AG   | 3         | 0.31%   |
| fr_FR   | 2         | 0.21%   |
| en_AU   | 2         | 0.21%   |
| de_DE   | 2         | 0.21%   |
| jv_ID   | 1         | 0.1%    |
| en_IN   | 1         | 0.1%    |
| de_CH   | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 572       | 59.27%  |
| BIOS | 393       | 40.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 723       | 74.84%  |
| Btrfs   | 109       | 11.28%  |
| Overlay | 67        | 6.94%   |
| Unknown | 25        | 2.59%   |
| Tmpfs   | 16        | 1.66%   |
| Xfs     | 10        | 1.04%   |
| Zfs     | 5         | 0.52%   |
| Ext2    | 5         | 0.52%   |
| F2fs    | 4         | 0.41%   |
| Ext3    | 2         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 425       | 44.09%  |
| Unknown | 420       | 43.57%  |
| MBR     | 119       | 12.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 835       | 87.07%  |
| Yes       | 124       | 12.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 549       | 57.07%  |
| Yes       | 413       | 42.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 232       | 24.58%  |
| ASUSTek Computer    | 204       | 21.61%  |
| Hewlett-Packard     | 145       | 15.36%  |
| Acer                | 138       | 14.62%  |
| Dell                | 78        | 8.26%   |
| Toshiba             | 34        | 3.6%    |
| MSI                 | 21        | 2.22%   |
| AXIOO               | 12        | 1.27%   |
| Apple               | 12        | 1.27%   |
| Sony                | 10        | 1.06%   |
| Fujitsu             | 9         | 0.95%   |
| Samsung Electronics | 7         | 0.74%   |
| Infinix             | 5         | 0.53%   |
| HUAWEI              | 4         | 0.42%   |
| Valve               | 3         | 0.32%   |
| Clevo               | 3         | 0.32%   |
| Timi                | 2         | 0.21%   |
| Panasonic           | 2         | 0.21%   |
| Intel               | 2         | 0.21%   |
| Gigabyte Technology | 2         | 0.21%   |
| ADVAN               | 2         | 0.21%   |
| Unknown             | 2         | 0.21%   |
| UMAX                | 1         | 0.11%   |
| Sole                | 1         | 0.11%   |
| realme              | 1         | 0.11%   |
| Phoenix/SiS         | 1         | 0.11%   |
| Notebook            | 1         | 0.11%   |
| MicroByte           | 1         | 0.11%   |
| Medion              | 1         | 0.11%   |
| Hampoo              | 1         | 0.11%   |
| GPD                 | 1         | 0.11%   |
| Google              | 1         | 0.11%   |
| Compal              | 1         | 0.11%   |
| Chuwi               | 1         | 0.11%   |
| AZW                 | 1         | 0.11%   |
| AVITA               | 1         | 0.11%   |
| Acidanthera         | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo IdeaPad 330-14AST 81D5           | 11        | 1.17%   |
| Lenovo G40-45 80E1                      | 11        | 1.17%   |
| HP Notebook                             | 11        | 1.17%   |
| HP Pavilion Aero Laptop 13-be0xxx       | 9         | 0.95%   |
| Acer Aspire 4752                        | 8         | 0.85%   |
| Lenovo IdeaPad S340-14API 81NB          | 6         | 0.64%   |
| Lenovo G400 20235                       | 6         | 0.64%   |
| HP Laptop 14-bw0xx                      | 6         | 0.64%   |
| HP 14                                   | 6         | 0.64%   |
| Acer Aspire 4750                        | 6         | 0.64%   |
| HP Pavilion g4                          | 5         | 0.53%   |
| ASUS X455YA                             | 5         | 0.53%   |
| ASUS X455LF                             | 5         | 0.53%   |
| ASUS X441BA                             | 5         | 0.53%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 5         | 0.53%   |
| ASUS GL553VD                            | 5         | 0.53%   |
| Apple MacBookPro12,1                    | 5         | 0.53%   |
| Acer Swift SFX14-41G                    | 5         | 0.53%   |
| Acer Swift SF314-71                     | 5         | 0.53%   |
| Acer One Z1402                          | 5         | 0.53%   |
| Unknown                                 | 5         | 0.53%   |
| Lenovo IdeaPad 320-14AST 80XU           | 4         | 0.42%   |
| Lenovo G40-30 80FY                      | 4         | 0.42%   |
| HP Pavilion 14                          | 4         | 0.42%   |
| HP Laptop 14-cm0xxx                     | 4         | 0.42%   |
| HP Laptop 14-bs0xx                      | 4         | 0.42%   |
| HP EliteBook 2570p                      | 4         | 0.42%   |
| HP 1000                                 | 4         | 0.42%   |
| ASUS X456URK                            | 4         | 0.42%   |
| ASUS X453SA                             | 4         | 0.42%   |
| ASUS X442URR                            | 4         | 0.42%   |
| ASUS X441NA                             | 4         | 0.42%   |
| ASUS X200MA                             | 4         | 0.42%   |
| Acer Swift SF314-56G                    | 4         | 0.42%   |
| Acer Aspire E5-476G                     | 4         | 0.42%   |
| Acer Aspire E5-475G                     | 4         | 0.42%   |
| Valve Jupiter                           | 3         | 0.32%   |
| Lenovo V310-14ISK 80SX                  | 3         | 0.32%   |
| Lenovo ThinkBook 14 G3 ACL 21A2         | 3         | 0.32%   |
| Lenovo IdeaPad 320-14ISK 80XG           | 3         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 88        | 9.32%   |
| Acer Aspire        | 82        | 8.69%   |
| Lenovo ThinkPad    | 80        | 8.47%   |
| HP Laptop          | 40        | 4.24%   |
| ASUS VivoBook      | 39        | 4.13%   |
| Dell Latitude      | 38        | 4.03%   |
| HP Pavilion        | 33        | 3.5%    |
| Toshiba Satellite  | 22        | 2.33%   |
| Acer Swift         | 22        | 2.33%   |
| HP EliteBook       | 20        | 2.12%   |
| Dell Inspiron      | 19        | 2.01%   |
| Lenovo G40-45      | 11        | 1.17%   |
| HP Notebook        | 11        | 1.17%   |
| Dell Vostro        | 10        | 1.06%   |
| Acer Nitro         | 10        | 1.06%   |
| Lenovo ThinkBook   | 9         | 0.95%   |
| Toshiba PORTEGE    | 7         | 0.74%   |
| HP ProBook         | 7         | 0.74%   |
| ASUS TUF           | 7         | 0.74%   |
| ASUS ASUS          | 7         | 0.74%   |
| MSI Modern         | 6         | 0.64%   |
| Lenovo Yoga        | 6         | 0.64%   |
| Lenovo G400        | 6         | 0.64%   |
| HP 14              | 6         | 0.64%   |
| Acer One           | 6         | 0.64%   |
| Infinix INBook     | 5         | 0.53%   |
| AXIOO Mybook       | 5         | 0.53%   |
| ASUS X455YA        | 5         | 0.53%   |
| ASUS X455LF        | 5         | 0.53%   |
| ASUS X441BA        | 5         | 0.53%   |
| ASUS ROG           | 5         | 0.53%   |
| ASUS GL553VD       | 5         | 0.53%   |
| Apple MacBookPro12 | 5         | 0.53%   |
| Unknown            | 5         | 0.53%   |
| Lenovo Legion      | 4         | 0.42%   |
| Lenovo G40-30      | 4         | 0.42%   |
| HP ENVY            | 4         | 0.42%   |
| HP 1000            | 4         | 0.42%   |
| ASUS ZenBook       | 4         | 0.42%   |
| ASUS X456URK       | 4         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 100       | 10.59%  |
| 2019 | 94        | 9.96%   |
| 2021 | 89        | 9.43%   |
| 2012 | 82        | 8.69%   |
| 2013 | 79        | 8.37%   |
| 2011 | 73        | 7.73%   |
| 2014 | 68        | 7.2%    |
| 2020 | 63        | 6.67%   |
| 2015 | 61        | 6.46%   |
| 2017 | 58        | 6.14%   |
| 2016 | 47        | 4.98%   |
| 2010 | 45        | 4.77%   |
| 2022 | 25        | 2.65%   |
| 2009 | 23        | 2.44%   |
| 2008 | 18        | 1.91%   |
| 2007 | 9         | 0.95%   |
| 2023 | 7         | 0.74%   |
| 2006 | 3         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 944       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 868       | 90.89%  |
| Enabled  | 87        | 9.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 943       | 99.89%  |
| Yes  | 1         | 0.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 316       | 33.12%  |
| 3.01-4.0    | 249       | 26.1%   |
| 8.01-16.0   | 161       | 16.88%  |
| 16.01-24.0  | 104       | 10.9%   |
| 1.01-2.0    | 84        | 8.81%   |
| 32.01-64.0  | 15        | 1.57%   |
| 2.01-3.0    | 10        | 1.05%   |
| 24.01-32.0  | 8         | 0.84%   |
| 0.51-1.0    | 5         | 0.52%   |
| 64.01-256.0 | 2         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 371       | 35.85%  |
| 2.01-3.0   | 288       | 27.83%  |
| 3.01-4.0   | 148       | 14.3%   |
| 4.01-8.0   | 138       | 13.33%  |
| 0.51-1.0   | 57        | 5.51%   |
| 8.01-16.0  | 27        | 2.61%   |
| 0.01-0.5   | 4         | 0.39%   |
| 16.01-24.0 | 2         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 680       | 70.76%  |
| 2      | 248       | 25.81%  |
| 3      | 25        | 2.6%    |
| 0      | 5         | 0.52%   |
| 4      | 3         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 621       | 65.23%  |
| Yes       | 331       | 34.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 758       | 80.21%  |
| No        | 187       | 19.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 929       | 98.31%  |
| No        | 16        | 1.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 741       | 77.84%  |
| No        | 211       | 22.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Indonesia | 944       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Jakarta         | 267       | 25.85%  |
| Surabaya        | 102       | 9.87%   |
| Bandung         | 69        | 6.68%   |
| Yogyakarta      | 39        | 3.78%   |
| Bogor           | 39        | 3.78%   |
| Semarang        | 35        | 3.39%   |
| Bekasi          | 30        | 2.9%    |
| Denpasar        | 25        | 2.42%   |
| Tangerang       | 21        | 2.03%   |
| Malang          | 21        | 2.03%   |
| South Tangerang | 19        | 1.84%   |
| Medan           | 17        | 1.65%   |
| Makassar        | 13        | 1.26%   |
| Depok           | 13        | 1.26%   |
| Palembang       | 12        | 1.16%   |
| Sleman          | 11        | 1.06%   |
| Samarinda       | 10        | 0.97%   |
| Balikpapan      | 10        | 0.97%   |
| Tasikmalaya     | 9         | 0.87%   |
| Banjarmasin     | 9         | 0.87%   |
| Banda Aceh      | 8         | 0.77%   |
| Surakarta       | 7         | 0.68%   |
| Blitar          | 7         | 0.68%   |
| Magelang        | 6         | 0.58%   |
| Kudus           | 6         | 0.58%   |
| Jember          | 6         | 0.58%   |
| Brebes          | 6         | 0.58%   |
| Pontianak       | 5         | 0.48%   |
| Kediri          | 5         | 0.48%   |
| Gresik          | 5         | 0.48%   |
| Demak           | 5         | 0.48%   |
| Cirebon         | 5         | 0.48%   |
| Pekanbaru       | 4         | 0.39%   |
| Pasuruan        | 4         | 0.39%   |
| Mataram         | 4         | 0.39%   |
| Jambi City      | 4         | 0.39%   |
| Batam           | 4         | 0.39%   |
| Tegal           | 3         | 0.29%   |
| Sukabumi        | 3         | 0.29%   |
| Sragen          | 3         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 183       | 233    | 15.12%  |
| WDC                   | 143       | 168    | 11.82%  |
| Toshiba               | 122       | 134    | 10.08%  |
| Samsung Electronics   | 112       | 154    | 9.26%   |
| HGST                  | 62        | 70     | 5.12%   |
| Hitachi               | 48        | 55     | 3.97%   |
| SanDisk               | 45        | 57     | 3.72%   |
| Unknown               | 43        | 52     | 3.55%   |
| Intel                 | 37        | 55     | 3.06%   |
| Kingston              | 34        | 42     | 2.81%   |
| SK hynix              | 33        | 38     | 2.73%   |
| V-GeN                 | 32        | 33     | 2.64%   |
| Micron Technology     | 30        | 42     | 2.48%   |
| A-DATA Technology     | 25        | 31     | 2.07%   |
| MidasForce            | 22        | 23     | 1.82%   |
| VISIPRO               | 13        | 16     | 1.07%   |
| China                 | 13        | 13     | 1.07%   |
| Unknown               | 13        | 14     | 1.07%   |
| Fujitsu               | 11        | 12     | 0.91%   |
| Team                  | 10        | 13     | 0.83%   |
| Silicon Motion        | 10        | 11     | 0.83%   |
| Apacer                | 10        | 10     | 0.83%   |
| JMicron Technology    | 9         | 10     | 0.74%   |
| EYOTA                 | 9         | 13     | 0.74%   |
| RX7                   | 8         | 9      | 0.66%   |
| Crucial               | 8         | 10     | 0.66%   |
| Apple                 | 7         | 8      | 0.58%   |
| Phison Electronics    | 6         | 7      | 0.5%    |
| Patriot               | 6         | 8      | 0.5%    |
| KIOXIA                | 5         | 5      | 0.41%   |
| Wellcomm              | 4         | 4      | 0.33%   |
| LITEON                | 4         | 5      | 0.33%   |
| External              | 4         | 4      | 0.33%   |
| Realtek Semiconductor | 3         | 3      | 0.25%   |
| Ramos Technology      | 3         | 10     | 0.25%   |
| PNY                   | 3         | 3      | 0.25%   |
| Pioneer               | 3         | 3      | 0.25%   |
| Phison                | 3         | 4      | 0.25%   |
| LITEONIT              | 3         | 4      | 0.25%   |
| FORESEE               | 3         | 3      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB         | 41        | 3.3%    |
| Seagate ST1000LM035-1RK172 1TB          | 39        | 3.14%   |
| Toshiba MQ01ABF050 500GB                | 25        | 2.01%   |
| Toshiba MQ04ABF100 1TB                  | 23        | 1.85%   |
| Toshiba MQ01ABD100 1TB                  | 19        | 1.53%   |
| HGST HTS545050A7E680 500GB              | 18        | 1.45%   |
| Unknown                                 | 13        | 1.05%   |
| A-DATA SU650 120GB SSD                  | 12        | 0.96%   |
| Seagate ST9500325AS 500GB               | 10        | 0.8%    |
| Seagate ST500LT012-9WS142 500GB         | 10        | 0.8%    |
| Hitachi HTS545050A7E380 500GB           | 10        | 0.8%    |
| Hitachi HTS543232A7A384 320GB           | 10        | 0.8%    |
| HGST HTS725050A7E630 500GB              | 10        | 0.8%    |
| SanDisk NVMe SSD Drive 512GB            | 9         | 0.72%   |
| Intel SSDPEKNW512G8 512GB               | 9         | 0.72%   |
| HGST HTS721010A9E630 1TB                | 9         | 0.72%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 8         | 0.64%   |
| WDC WD10SPZX-21Z10T0 1TB                | 8         | 0.64%   |
| MidasForce SSD 128GB                    | 8         | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 7         | 0.56%   |
| Unknown MMC Card  32GB                  | 7         | 0.56%   |
| Seagate ST9320325AS 320GB               | 7         | 0.56%   |
| Seagate ST2000LM007-1R8174 2TB          | 7         | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 7         | 0.56%   |
| Samsung SSD 850 EVO 250GB               | 7         | 0.56%   |
| WDC WD5000LPVX-80V0TT0 500GB            | 6         | 0.48%   |
| Seagate ST1000LX015-1U7172 1TB          | 6         | 0.48%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB    | 6         | 0.48%   |
| Samsung SSD 860 EVO 250GB               | 6         | 0.48%   |
| Kingston SA400S37240G 240GB SSD         | 6         | 0.48%   |
| HGST HTS545050A7E380 500GB              | 6         | 0.48%   |
| HGST HTS541010A9E680 1TB                | 6         | 0.48%   |
| WDC WD10JPCX-24UE4T0 1TB                | 5         | 0.4%    |
| Unknown MMC Card  64GB                  | 5         | 0.4%    |
| Unknown MMC Card  128GB                 | 5         | 0.4%    |
| Seagate ST500LM021-1KJ152 500GB         | 5         | 0.4%    |
| Seagate ST1000LM049-2GH172 1TB          | 5         | 0.4%    |
| Samsung SSD 860 EVO 500GB               | 5         | 0.4%    |
| Phison PS5013 E13 NVMe Controller 512GB | 5         | 0.4%    |
| MidasForce SSD 256GB                    | 5         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 181       | 228    | 33.96%  |
| WDC                 | 105       | 118    | 19.7%   |
| Toshiba             | 105       | 115    | 19.7%   |
| HGST                | 62        | 70     | 11.63%  |
| Hitachi             | 48        | 55     | 9.01%   |
| Fujitsu             | 9         | 9      | 1.69%   |
| Unknown             | 5         | 5      | 0.94%   |
| Samsung Electronics | 4         | 4      | 0.75%   |
| External            | 4         | 4      | 0.75%   |
| USB3.0              | 2         | 2      | 0.38%   |
| Pioneer             | 2         | 2      | 0.38%   |
| TO Exter            | 1         | 1      | 0.19%   |
| SYMTEC              | 1         | 1      | 0.19%   |
| JMicron Technology  | 1         | 1      | 0.19%   |
| HGST HTS            | 1         | 3      | 0.19%   |
| Hewlett-Packard     | 1         | 1      | 0.19%   |
| Apple               | 1         | 1      | 0.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 47        | 62     | 14.03%  |
| WDC                 | 22        | 31     | 6.57%   |
| V-GeN               | 22        | 23     | 6.57%   |
| MidasForce          | 22        | 23     | 6.57%   |
| SanDisk             | 20        | 30     | 5.97%   |
| Kingston            | 19        | 20     | 5.67%   |
| A-DATA Technology   | 18        | 23     | 5.37%   |
| China               | 13        | 13     | 3.88%   |
| VISIPRO             | 10        | 13     | 2.99%   |
| Apacer              | 10        | 10     | 2.99%   |
| Unknown             | 9         | 9      | 2.69%   |
| Team                | 8         | 11     | 2.39%   |
| Intel               | 8         | 12     | 2.39%   |
| EYOTA               | 8         | 11     | 2.39%   |
| Toshiba             | 7         | 8      | 2.09%   |
| Crucial             | 7         | 9      | 2.09%   |
| RX7                 | 6         | 7      | 1.79%   |
| Patriot             | 6         | 8      | 1.79%   |
| Micron Technology   | 5         | 7      | 1.49%   |
| JMicron Technology  | 5         | 5      | 1.49%   |
| Apple               | 5         | 5      | 1.49%   |
| Wellcomm            | 4         | 4      | 1.19%   |
| Seagate             | 4         | 4      | 1.19%   |
| LITEON              | 4         | 5      | 1.19%   |
| Ramos Technology    | 3         | 10     | 0.9%    |
| LITEONIT            | 3         | 4      | 0.9%    |
| XSTAR               | 2         | 2      | 0.6%    |
| Smart               | 2         | 2      | 0.6%    |
| SK hynix            | 2         | 2      | 0.6%    |
| PNY                 | 2         | 2      | 0.6%    |
| Netac               | 2         | 2      | 0.6%    |
| Lexar               | 2         | 2      | 0.6%    |
| Kingmax             | 2         | 2      | 0.6%    |
| GALAX               | 2         | 2      | 0.6%    |
| FORESEE             | 2         | 2      | 0.6%    |
| WellcommMaster      | 1         | 1      | 0.3%    |
| Vaseky              | 1         | 2      | 0.3%    |
| Varro               | 1         | 1      | 0.3%    |
| ValueTech           | 1         | 1      | 0.3%    |
| Union Memory        | 1         | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 510       | 620    | 43.85%  |
| SSD     | 318       | 408    | 27.34%  |
| NVMe    | 264       | 350    | 22.7%   |
| Unknown | 36        | 42     | 3.1%    |
| MMC     | 35        | 44     | 3.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 721       | 1029   | 68.08%  |
| NVMe | 264       | 349    | 24.93%  |
| SAS  | 39        | 42     | 3.68%   |
| MMC  | 35        | 44     | 3.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 546       | 736    | 70.27%  |
| 0.51-1.0   | 215       | 265    | 27.67%  |
| 1.01-2.0   | 15        | 26     | 1.93%   |
| 3.01-4.0   | 1         | 1      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 299       | 30.23%  |
| 251-500        | 252       | 25.48%  |
| 501-1000       | 118       | 11.93%  |
| 51-100         | 104       | 10.52%  |
| 1-20           | 66        | 6.67%   |
| 1001-2000      | 64        | 6.47%   |
| 21-50          | 60        | 6.07%   |
| Unknown        | 13        | 1.31%   |
| 2001-3000      | 7         | 0.71%   |
| More than 3000 | 6         | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 373       | 35.9%   |
| 21-50          | 209       | 20.12%  |
| 101-250        | 145       | 13.96%  |
| 51-100         | 134       | 12.9%   |
| 251-500        | 96        | 9.24%   |
| 501-1000       | 52        | 5%      |
| 1001-2000      | 13        | 1.25%   |
| Unknown        | 13        | 1.25%   |
| 2001-3000      | 3         | 0.29%   |
| More than 3000 | 1         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB       | 8         | 9      | 6.5%    |
| Seagate ST500LT012-1DG142 500GB  | 7         | 7      | 5.69%   |
| Seagate ST500LT012-9WS142 500GB  | 6         | 6      | 4.88%   |
| Seagate ST9500325AS 500GB        | 4         | 4      | 3.25%   |
| Toshiba MQ01ABF050 500GB         | 3         | 3      | 2.44%   |
| Toshiba MQ01ABD032 320GB         | 3         | 3      | 2.44%   |
| Seagate ST1000LM035-1RK172 1TB   | 3         | 3      | 2.44%   |
| Hitachi HTS545050A7E380 500GB    | 3         | 3      | 2.44%   |
| HGST HTS725050A7E630 500GB       | 3         | 3      | 2.44%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 2      | 1.63%   |
| WDC WD3200BEKT-60V5T1 320GB      | 2         | 2      | 1.63%   |
| WDC WD10JPCX-24UE4T0 1TB         | 2         | 3      | 1.63%   |
| Toshiba MQ01ABD100 1TB           | 2         | 2      | 1.63%   |
| Toshiba MQ01ABD050 500GB         | 2         | 2      | 1.63%   |
| Toshiba MK5059GSXP 500GB         | 2         | 2      | 1.63%   |
| Toshiba MK3265GSX 320GB          | 2         | 3      | 1.63%   |
| Seagate ST1000LX015-1U7172 1TB   | 2         | 3      | 1.63%   |
| Hitachi HTS545032B9A300 320GB    | 2         | 2      | 1.63%   |
| HGST HTS545050A7E380 500GB       | 2         | 2      | 1.63%   |
| WellcommMaster 128GB SSD         | 1         | 1      | 0.81%   |
| Wellcomm Master 128GB SSD        | 1         | 1      | 0.81%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 1      | 0.81%   |
| WDC WD5000LPVX-80V0TT0 500GB     | 1         | 1      | 0.81%   |
| WDC WD5000LPVT-22G33T0 500GB     | 1         | 1      | 0.81%   |
| WDC WD5000LPCX-22VHAT0 500GB     | 1         | 1      | 0.81%   |
| WDC WD5000L 500GB                | 1         | 1      | 0.81%   |
| WDC WD5000BPVT-60HXZT3 500GB     | 1         | 1      | 0.81%   |
| WDC WD5000BPVT-08HXZT3 500GB     | 1         | 1      | 0.81%   |
| WDC WD5000BPVT-00HXZT3 500GB     | 1         | 1      | 0.81%   |
| WDC WD3200BPVT-80JJ5T0 320GB     | 1         | 1      | 0.81%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 1      | 0.81%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1      | 0.81%   |
| VISIPRO SSD 256GB                | 1         | 3      | 0.81%   |
| ValueTech SSD 256GB              | 1         | 1      | 0.81%   |
| Toshiba MQ04ABF100 1TB           | 1         | 1      | 0.81%   |
| Toshiba MQ01ABD075 752GB         | 1         | 1      | 0.81%   |
| Toshiba MQ01ABD050V 500GB        | 1         | 1      | 0.81%   |
| Toshiba MK7575GSX 752GB          | 1         | 2      | 0.81%   |
| Toshiba MK5075GSX 500GB          | 1         | 1      | 0.81%   |
| Toshiba MK3276GSX 320GB          | 1         | 1      | 0.81%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 39     | 24.79%  |
| Toshiba             | 23        | 25     | 19.01%  |
| WDC                 | 17        | 18     | 14.05%  |
| HGST                | 17        | 19     | 14.05%  |
| Hitachi             | 13        | 13     | 10.74%  |
| Samsung Electronics | 3         | 4      | 2.48%   |
| Micron Technology   | 3         | 3      | 2.48%   |
| SanDisk             | 2         | 2      | 1.65%   |
| A-DATA Technology   | 2         | 4      | 1.65%   |
| WellcommMaster      | 1         | 1      | 0.83%   |
| Wellcomm            | 1         | 1      | 0.83%   |
| VISIPRO             | 1         | 3      | 0.83%   |
| ValueTech           | 1         | 1      | 0.83%   |
| SK hynix            | 1         | 1      | 0.83%   |
| RX7                 | 1         | 1      | 0.83%   |
| KLEVV               | 1         | 1      | 0.83%   |
| Intel               | 1         | 1      | 0.83%   |
| Crucial             | 1         | 1      | 0.83%   |
| China               | 1         | 1      | 0.83%   |
| Unknown             | 1         | 1      | 0.83%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 39     | 30%     |
| Toshiba             | 23        | 25     | 23%     |
| HGST                | 17        | 19     | 17%     |
| WDC                 | 16        | 17     | 16%     |
| Hitachi             | 13        | 13     | 13%     |
| Samsung Electronics | 1         | 1      | 1%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 98        | 114    | 82.35%  |
| SSD  | 18        | 22     | 15.13%  |
| NVMe | 3         | 4      | 2.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-60HXZT1 500GB      | 1         | 1      | 20%     |
| Toshiba MK2575GSX 250GB           | 1         | 1      | 20%     |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 20%     |
| Hitachi HTS543232A7A384 320GB     | 1         | 1      | 20%     |
| A-DATA Technology SX8200PNP 256GB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Hitachi           | 2         | 2      | 40%     |
| WDC               | 1         | 1      | 20%     |
| Toshiba           | 1         | 1      | 20%     |
| A-DATA Technology | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 489       | 737    | 47.85%  |
| Works    | 413       | 582    | 40.41%  |
| Malfunc  | 115       | 140    | 11.25%  |
| Failed   | 5         | 5      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 654       | 59.35%  |
| AMD                              | 188       | 17.06%  |
| Samsung Electronics              | 68        | 6.17%   |
| SanDisk                          | 42        | 3.81%   |
| SK hynix                         | 31        | 2.81%   |
| Micron Technology                | 25        | 2.27%   |
| Kingston Technology Company      | 17        | 1.54%   |
| Silicon Motion                   | 14        | 1.27%   |
| Phison Electronics               | 12        | 1.09%   |
| ADATA Technology                 | 9         | 0.82%   |
| Toshiba America Info Systems     | 8         | 0.73%   |
| KIOXIA                           | 7         | 0.64%   |
| Union Memory (Shenzhen)          | 4         | 0.36%   |
| Silicon Integrated Systems [SiS] | 4         | 0.36%   |
| Realtek Semiconductor            | 4         | 0.36%   |
| Shenzhen Longsys Electronics     | 3         | 0.27%   |
| Nvidia                           | 2         | 0.18%   |
| Micron/Crucial Technology        | 2         | 0.18%   |
| ASMedia Technology               | 2         | 0.18%   |
| Solid State Storage Technology   | 1         | 0.09%   |
| O2 Micro                         | 1         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.09%   |
| Lenovo                           | 1         | 0.09%   |
| INNOGRIT                         | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 176       | 15.02%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 90        | 7.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 82        | 7%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 53        | 4.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 51        | 4.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 47        | 4.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 35        | 2.99%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 30        | 2.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 29        | 2.47%   |
| Intel Volume Management Device NVMe RAID Controller                              | 25        | 2.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 22        | 1.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 22        | 1.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 19        | 1.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 19        | 1.62%   |
| Intel Tiger Lake-LP SATA Controller                                              | 17        | 1.45%   |
| Intel SSD 660P Series                                                            | 16        | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 16        | 1.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15        | 1.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14        | 1.19%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 13        | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 13        | 1.11%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 12        | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 12        | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 11        | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 11        | 0.94%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 10        | 0.85%   |
| SK hynix BC511 NVMe SSD                                                          | 10        | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 10        | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 10        | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 10        | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 9         | 0.77%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 8         | 0.68%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 7         | 0.6%    |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                            | 7         | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 7         | 0.6%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 7         | 0.6%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 7         | 0.6%    |
| Intel SSD 670p Series [Keystone Harbor]                                          | 7         | 0.6%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 7         | 0.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 758       | 66.49%  |
| NVMe | 265       | 23.25%  |
| RAID | 76        | 6.67%   |
| IDE  | 41        | 3.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 707       | 74.89%  |
| AMD    | 237       | 25.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.8%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 1.69%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 16        | 1.69%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 15        | 1.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 1.48%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 14        | 1.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.38%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 1.38%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 13        | 1.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 1.38%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 13        | 1.38%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 12        | 1.27%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 11        | 1.16%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 11        | 1.16%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 11        | 1.16%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 11        | 1.16%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 11        | 1.16%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 11        | 1.16%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 11        | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 1.06%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 1.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 1.06%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 10        | 1.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 0.95%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 9         | 0.95%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 9         | 0.95%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 9         | 0.95%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.95%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 8         | 0.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.85%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 8         | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 0.74%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 7         | 0.74%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 7         | 0.74%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 7         | 0.74%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 6         | 0.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 235       | 24.87%  |
| Intel Core i3           | 134       | 14.18%  |
| Intel Core i7           | 119       | 12.59%  |
| Other                   | 85        | 8.99%   |
| Intel Celeron           | 85        | 8.99%   |
| AMD Ryzen 5             | 58        | 6.14%   |
| Intel Core 2 Duo        | 30        | 3.17%   |
| AMD Ryzen 3             | 27        | 2.86%   |
| AMD A8                  | 22        | 2.33%   |
| AMD Ryzen 7             | 20        | 2.12%   |
| Intel Pentium           | 17        | 1.8%    |
| AMD A4                  | 14        | 1.48%   |
| Intel Atom              | 12        | 1.27%   |
| AMD E1                  | 10        | 1.06%   |
| AMD E                   | 9         | 0.95%   |
| AMD A6                  | 9         | 0.95%   |
| AMD E2                  | 7         | 0.74%   |
| AMD Athlon              | 7         | 0.74%   |
| Intel Pentium Dual-Core | 6         | 0.63%   |
| Intel Pentium Dual      | 5         | 0.53%   |
| Intel Genuine           | 5         | 0.53%   |
| AMD A10                 | 5         | 0.53%   |
| AMD Ryzen 9             | 4         | 0.42%   |
| Intel Core 2            | 3         | 0.32%   |
| AMD Ryzen 5 PRO         | 3         | 0.32%   |
| AMD FX                  | 3         | 0.32%   |
| AMD C-60                | 3         | 0.32%   |
| Intel Xeon              | 2         | 0.21%   |
| AMD A12                 | 2         | 0.21%   |
| Intel Pentium Silver    | 1         | 0.11%   |
| AMD Turion 64 Mobile    | 1         | 0.11%   |
| AMD PRO A10             | 1         | 0.11%   |
| AMD C-50                | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 609       | 64.44%  |
| 4      | 230       | 24.34%  |
| 6      | 61        | 6.46%   |
| 8      | 22        | 2.33%   |
| 1      | 10        | 1.06%   |
| 12     | 6         | 0.63%   |
| 10     | 5         | 0.53%   |
| 14     | 2         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 944       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 669       | 70.87%  |
| 1      | 275       | 29.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 930       | 98.52%  |
| Unknown        | 11        | 1.17%   |
| 32-bit         | 3         | 0.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 235       | 23.91%  |
| 0x206a7    | 68        | 6.92%   |
| 0x306a9    | 53        | 5.39%   |
| 0x40651    | 42        | 4.27%   |
| 0x306d4    | 34        | 3.46%   |
| 0x806ea    | 28        | 2.85%   |
| 0x06006705 | 28        | 2.85%   |
| 0x406e3    | 26        | 2.64%   |
| 0x806ec    | 25        | 2.54%   |
| 0x806e9    | 24        | 2.44%   |
| 0x08108109 | 24        | 2.44%   |
| 0x806c1    | 23        | 2.34%   |
| 0x20655    | 23        | 2.34%   |
| 0x1067a    | 21        | 2.14%   |
| 0x906ea    | 18        | 1.83%   |
| 0x0a50000c | 17        | 1.73%   |
| 0x806eb    | 15        | 1.53%   |
| 0x07030105 | 15        | 1.53%   |
| 0x08108102 | 14        | 1.42%   |
| 0x706e5    | 13        | 1.32%   |
| 0x30678    | 13        | 1.32%   |
| 0x6fd      | 11        | 1.12%   |
| 0x306c3    | 11        | 1.12%   |
| 0x706a8    | 10        | 1.02%   |
| 0x20652    | 10        | 1.02%   |
| 0x08608103 | 10        | 1.02%   |
| 0x406c4    | 8         | 0.81%   |
| 0x406c3    | 8         | 0.81%   |
| 0x08600104 | 8         | 0.81%   |
| 0x906e9    | 7         | 0.71%   |
| 0x06001119 | 7         | 0.71%   |
| 0x05000119 | 7         | 0.71%   |
| 0x906a3    | 6         | 0.61%   |
| 0x10676    | 6         | 0.61%   |
| 0x0810100b | 6         | 0.61%   |
| 0x0700010f | 6         | 0.61%   |
| 0x03000027 | 6         | 0.61%   |
| 0x506e3    | 5         | 0.51%   |
| 0x506c9    | 5         | 0.51%   |
| 0x06006704 | 5         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 157       | 16.61%  |
| SandyBridge      | 84        | 8.89%   |
| IvyBridge        | 74        | 7.83%   |
| Haswell          | 64        | 6.77%   |
| Excavator        | 48        | 5.08%   |
| Westmere         | 45        | 4.76%   |
| Zen+             | 44        | 4.66%   |
| Silvermont       | 42        | 4.44%   |
| Broadwell        | 42        | 4.44%   |
| Skylake          | 38        | 4.02%   |
| TigerLake        | 31        | 3.28%   |
| Penryn           | 30        | 3.17%   |
| Unknown          | 27        | 2.86%   |
| Puma             | 26        | 2.75%   |
| IceLake          | 23        | 2.43%   |
| Zen 3            | 22        | 2.33%   |
| Zen 2            | 19        | 2.01%   |
| Goldmont plus    | 17        | 1.8%    |
| Core             | 17        | 1.8%    |
| Bobcat           | 16        | 1.69%   |
| Zen              | 14        | 1.48%   |
| Alderlake Hybrid | 14        | 1.48%   |
| Goldmont         | 10        | 1.06%   |
| Piledriver       | 8         | 0.85%   |
| Jaguar           | 8         | 0.85%   |
| K10 Llano        | 6         | 0.63%   |
| CometLake        | 6         | 0.63%   |
| Bonnell          | 5         | 0.53%   |
| Tremont          | 3         | 0.32%   |
| Steamroller      | 2         | 0.21%   |
| P6               | 2         | 0.21%   |
| K8 Hammer        | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 685       | 56.24%  |
| AMD                              | 290       | 23.81%  |
| Nvidia                           | 238       | 19.54%  |
| Silicon Integrated Systems [SiS] | 4         | 0.33%   |
| Silicon Motion                   | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 81        | 6.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 72        | 5.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 50        | 3.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 45        | 3.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 39        | 3.06%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 39        | 3.06%   |
| Intel HD Graphics 5500                                                                   | 37        | 2.9%    |
| Intel UHD Graphics 620                                                                   | 34        | 2.67%   |
| Intel HD Graphics 620                                                                    | 32        | 2.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 2.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 2.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 1.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 1.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 22        | 1.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 21        | 1.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 1.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 1.57%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 20        | 1.57%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 20        | 1.57%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 20        | 1.57%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 19        | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 1.18%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 1.18%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 15        | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.1%    |
| AMD Lucienne                                                                             | 14        | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 1.02%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 1.02%   |
| Nvidia GP108M [GeForce MX150]                                                            | 11        | 0.86%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 11        | 0.86%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 11        | 0.86%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 11        | 0.86%   |
| Intel HD Graphics 500                                                                    | 10        | 0.78%   |
| Intel HD Graphics 630                                                                    | 9         | 0.71%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 9         | 0.71%   |
| Nvidia GP108M [GeForce MX250]                                                            | 8         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 439       | 46.26%  |
| Intel + Nvidia     | 198       | 20.86%  |
| 1 x AMD            | 178       | 18.76%  |
| Intel + AMD        | 46        | 4.85%   |
| 2 x AMD            | 36        | 3.79%   |
| AMD + Nvidia       | 30        | 3.16%   |
| 1 x Nvidia         | 8         | 0.84%   |
| 2 x Intel          | 6         | 0.63%   |
| 1 x SiS            | 4         | 0.42%   |
| 2 x Nvidia         | 2         | 0.21%   |
| Other              | 1         | 0.11%   |
| 1 x Silicon Motion | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 821       | 85.97%  |
| Proprietary | 119       | 12.46%  |
| Unknown     | 15        | 1.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 597       | 61.36%  |
| 1.01-2.0   | 155       | 15.93%  |
| 0.01-0.5   | 120       | 12.33%  |
| 0.51-1.0   | 47        | 4.83%   |
| 3.01-4.0   | 42        | 4.32%   |
| 5.01-6.0   | 8         | 0.82%   |
| 7.01-8.0   | 3         | 0.31%   |
| 2.01-3.0   | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 214       | 21.29%  |
| Chimei Innolux          | 198       | 19.7%   |
| BOE                     | 163       | 16.22%  |
| LG Display              | 135       | 13.43%  |
| Samsung Electronics     | 79        | 7.86%   |
| Goldstar                | 37        | 3.68%   |
| Lenovo                  | 19        | 1.89%   |
| PANDA                   | 16        | 1.59%   |
| Sharp                   | 15        | 1.49%   |
| InfoVision              | 13        | 1.29%   |
| Apple                   | 12        | 1.19%   |
| Chi Mei Optoelectronics | 11        | 1.09%   |
| InnoLux Display         | 8         | 0.8%    |
| Dell                    | 7         | 0.7%    |
| ViewSonic               | 6         | 0.6%    |
| LG Philips              | 6         | 0.6%    |
| Acer                    | 6         | 0.6%    |
| Philips                 | 5         | 0.5%    |
| AOC                     | 5         | 0.5%    |
| Toshiba                 | 4         | 0.4%    |
| KDC                     | 4         | 0.4%    |
| CPT                     | 4         | 0.4%    |
| Valve                   | 3         | 0.3%    |
| Sony                    | 3         | 0.3%    |
| Quanta Display          | 3         | 0.3%    |
| HKC                     | 3         | 0.3%    |
| Hewlett-Packard         | 3         | 0.3%    |
| HannStar                | 3         | 0.3%    |
| Seiko/Epson             | 2         | 0.2%    |
| Panasonic               | 2         | 0.2%    |
| HJC                     | 2         | 0.2%    |
| BenQ                    | 2         | 0.2%    |
| WST                     | 1         | 0.1%    |
| TMX                     | 1         | 0.1%    |
| SPC                     | 1         | 0.1%    |
| Mi                      | 1         | 0.1%    |
| JDI                     | 1         | 0.1%    |
| HUAWEI                  | 1         | 0.1%    |
| Hitachi                 | 1         | 0.1%    |
| HIC                     | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 20        | 1.98%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 19        | 1.88%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 18        | 1.78%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 17        | 1.68%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 13        | 1.29%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 12        | 1.19%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 12        | 1.19%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 11        | 1.09%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 11        | 1.09%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 11        | 1.09%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 10        | 0.99%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 10        | 0.99%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 9         | 0.89%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 9         | 0.89%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 9         | 0.89%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 8         | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 8         | 0.79%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 7         | 0.69%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 7         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 7         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch       | 7         | 0.69%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                  | 7         | 0.69%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 7         | 0.69%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6         | 0.59%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch           | 6         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch       | 6         | 0.59%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                  | 6         | 0.59%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 6         | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch  | 5         | 0.5%    |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 5         | 0.5%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 5         | 0.5%    |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 5         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 5         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 5         | 0.5%    |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                 | 5         | 0.5%    |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch         | 5         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 4         | 0.4%    |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch  | 4         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 522       | 54.09%  |
| 1920x1080 (FHD)   | 301       | 31.19%  |
| 1280x800 (WXGA)   | 25        | 2.59%   |
| 1600x900 (HD+)    | 22        | 2.28%   |
| 3840x2160 (4K)    | 13        | 1.35%   |
| 2560x1440 (QHD)   | 13        | 1.35%   |
| 1920x1200 (WUXGA) | 13        | 1.35%   |
| 1440x900 (WXGA+)  | 12        | 1.24%   |
| 2560x1600         | 10        | 1.04%   |
| 2880x1800         | 7         | 0.73%   |
| 1360x768          | 7         | 0.73%   |
| 1024x600          | 4         | 0.41%   |
| 800x1280          | 3         | 0.31%   |
| 3840x2400         | 2         | 0.21%   |
| 2560x1080         | 2         | 0.21%   |
| 3440x1440         | 1         | 0.1%    |
| 3200x1800 (QHD+)  | 1         | 0.1%    |
| 2966x900          | 1         | 0.1%    |
| 2736x1824         | 1         | 0.1%    |
| 2240x1400         | 1         | 0.1%    |
| 2160x1440         | 1         | 0.1%    |
| 1920x1280         | 1         | 0.1%    |
| 1024x768 (XGA)    | 1         | 0.1%    |
| Unknown           | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 303       | 30.15%  |
| 14      | 295       | 29.35%  |
| 15      | 194       | 19.3%   |
| 12      | 46        | 4.58%   |
| 11      | 33        | 3.28%   |
| 23      | 31        | 3.08%   |
| 18      | 24        | 2.39%   |
| 21      | 11        | 1.09%   |
| 24      | 10        | 1%      |
| 17      | 10        | 1%      |
| 19      | 9         | 0.9%    |
| 40      | 6         | 0.6%    |
| 16      | 5         | 0.5%    |
| 10      | 4         | 0.4%    |
| 34      | 3         | 0.3%    |
| 27      | 3         | 0.3%    |
| 7       | 3         | 0.3%    |
| Unknown | 3         | 0.3%    |
| 48      | 2         | 0.2%    |
| 31      | 2         | 0.2%    |
| 72      | 1         | 0.1%    |
| 60      | 1         | 0.1%    |
| 54      | 1         | 0.1%    |
| 52      | 1         | 0.1%    |
| 26      | 1         | 0.1%    |
| 25      | 1         | 0.1%    |
| 20      | 1         | 0.1%    |
| 9       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 722       | 72.34%  |
| 201-300     | 144       | 14.43%  |
| 501-600     | 45        | 4.51%   |
| 401-500     | 44        | 4.41%   |
| 351-400     | 19        | 1.9%    |
| 801-900     | 6         | 0.6%    |
| 1001-1500   | 5         | 0.5%    |
| 701-800     | 3         | 0.3%    |
| 601-700     | 3         | 0.3%    |
| 1-100       | 3         | 0.3%    |
| Unknown     | 3         | 0.3%    |
| 1501-2000   | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 834       | 90.75%  |
| 16/10   | 69        | 7.51%   |
| 3/2     | 5         | 0.54%   |
| 21/9    | 3         | 0.33%   |
| 0.67    | 3         | 0.33%   |
| Unknown | 3         | 0.33%   |
| 4/3     | 2         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 543       | 54.08%  |
| 101-110        | 192       | 19.12%  |
| 201-250        | 52        | 5.18%   |
| 71-80          | 50        | 4.98%   |
| 61-70          | 45        | 4.48%   |
| 51-60          | 33        | 3.29%   |
| 141-150        | 24        | 2.39%   |
| 151-200        | 10        | 1%      |
| 121-130        | 10        | 1%      |
| More than 1000 | 6         | 0.6%    |
| 501-1000       | 6         | 0.6%    |
| 91-100         | 6         | 0.6%    |
| 351-500        | 5         | 0.5%    |
| 41-50          | 5         | 0.5%    |
| 301-350        | 4         | 0.4%    |
| 111-120        | 4         | 0.4%    |
| 1-40           | 3         | 0.3%    |
| Unknown        | 3         | 0.3%    |
| 131-140        | 2         | 0.2%    |
| 251-300        | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 465       | 46.69%  |
| 121-160       | 338       | 33.94%  |
| 51-100        | 107       | 10.74%  |
| 161-240       | 56        | 5.62%   |
| More than 240 | 18        | 1.81%   |
| 1-50          | 9         | 0.9%    |
| Unknown       | 3         | 0.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 840       | 87.05%  |
| 2     | 100       | 10.36%  |
| 0     | 22        | 2.28%   |
| 3     | 3         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 570       | 37.43%  |
| Intel                             | 355       | 23.31%  |
| Qualcomm Atheros                  | 316       | 20.75%  |
| Broadcom                          | 102       | 6.7%    |
| MediaTek                          | 34        | 2.23%   |
| Xiaomi                            | 16        | 1.05%   |
| Broadcom Limited                  | 16        | 1.05%   |
| Ralink Technology                 | 13        | 0.85%   |
| Samsung Electronics               | 12        | 0.79%   |
| Marvell Technology Group          | 11        | 0.72%   |
| TP-Link                           | 10        | 0.66%   |
| Qualcomm Atheros Communications   | 9         | 0.59%   |
| OPPO Electronics                  | 9         | 0.59%   |
| Ralink                            | 8         | 0.53%   |
| JMicron Technology                | 6         | 0.39%   |
| Huawei Technologies               | 4         | 0.26%   |
| Ericsson Business Mobile Networks | 4         | 0.26%   |
| ASIX Electronics                  | 4         | 0.26%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.2%    |
| Qualcomm                          | 3         | 0.2%    |
| Attansic Technology               | 3         | 0.2%    |
| Sierra Wireless                   | 2         | 0.13%   |
| Nvidia                            | 2         | 0.13%   |
| ICS Advent                        | 2         | 0.13%   |
| Hewlett-Packard                   | 2         | 0.13%   |
| Lenovo                            | 1         | 0.07%   |
| HTC (High Tech Computer)          | 1         | 0.07%   |
| Foxconn / Hon Hai                 | 1         | 0.07%   |
| Fibocom                           | 1         | 0.07%   |
| D-Link                            | 1         | 0.07%   |
| ASUSTek Computer                  | 1         | 0.07%   |
| AboCom Systems                    | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 346       | 19.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 124       | 6.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 85        | 4.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 67        | 3.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 52        | 2.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 35        | 1.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 33        | 1.84%   |
| Intel Wireless 8265 / 8275                                        | 33        | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 28        | 1.56%   |
| Intel Wireless 7265                                               | 26        | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 26        | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 26        | 1.45%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 25        | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 23        | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 21        | 1.17%   |
| Intel Wireless 7260                                               | 21        | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 21        | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 20        | 1.11%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 1.11%   |
| Intel Wi-Fi 6 AX201                                               | 19        | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                     | 19        | 1.06%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 17        | 0.95%   |
| Intel Wi-Fi 6 AX200                                               | 17        | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 17        | 0.95%   |
| Intel Wireless 8260                                               | 15        | 0.84%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 12        | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 12        | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 12        | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 12        | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 0.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 10        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                   | 9         | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                   | 9         | 0.5%    |
| OPPO RMX3623                                                      | 9         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 325       | 33.3%   |
| Qualcomm Atheros                  | 286       | 29.3%   |
| Realtek Semiconductor             | 202       | 20.7%   |
| Broadcom                          | 81        | 8.3%    |
| MediaTek                          | 27        | 2.77%   |
| Ralink Technology                 | 13        | 1.33%   |
| Broadcom Limited                  | 12        | 1.23%   |
| Qualcomm Atheros Communications   | 9         | 0.92%   |
| Ralink                            | 8         | 0.82%   |
| TP-Link                           | 7         | 0.72%   |
| Sierra Wireless                   | 2         | 0.2%    |
| Fibocom                           | 1         | 0.1%    |
| Ericsson Business Mobile Networks | 1         | 0.1%    |
| D-Link                            | 1         | 0.1%    |
| AboCom Systems                    | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 85        | 8.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 67        | 6.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 52        | 5.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 35        | 3.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 33        | 3.36%   |
| Intel Wireless 8265 / 8275                                     | 33        | 3.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 28        | 2.85%   |
| Intel Wireless 7265                                            | 26        | 2.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 26        | 2.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 26        | 2.65%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 25        | 2.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 23        | 2.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 21        | 2.14%   |
| Intel Wireless 7260                                            | 21        | 2.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 21        | 2.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 20        | 2.04%   |
| Intel Wi-Fi 6 AX201                                            | 19        | 1.93%   |
| Broadcom BCM43142 802.11b/g/n                                  | 19        | 1.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 17        | 1.73%   |
| Intel Wi-Fi 6 AX200                                            | 17        | 1.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 17        | 1.73%   |
| Intel Wireless 8260                                            | 15        | 1.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 12        | 1.22%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12        | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 12        | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 10        | 1.02%   |
| Ralink MT7601U Wireless Adapter                                | 9         | 0.92%   |
| Qualcomm Atheros AR9271 802.11n                                | 9         | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9         | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 9         | 0.92%   |
| Realtek 802.11n WLAN Adapter                                   | 8         | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 8         | 0.81%   |
| Intel Wireless 3165                                            | 8         | 0.81%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 8         | 0.81%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 6         | 0.61%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 6         | 0.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 6         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 486       | 60.6%   |
| Intel                            | 126       | 15.71%  |
| Qualcomm Atheros                 | 69        | 8.6%    |
| Broadcom                         | 31        | 3.87%   |
| Xiaomi                           | 16        | 2%      |
| Marvell Technology Group         | 11        | 1.37%   |
| OPPO Electronics                 | 9         | 1.12%   |
| Samsung Electronics              | 8         | 1%      |
| MediaTek                         | 7         | 0.87%   |
| JMicron Technology               | 6         | 0.75%   |
| Broadcom Limited                 | 6         | 0.75%   |
| ASIX Electronics                 | 4         | 0.5%    |
| TP-Link                          | 3         | 0.37%   |
| Silicon Integrated Systems [SiS] | 3         | 0.37%   |
| Qualcomm                         | 3         | 0.37%   |
| Attansic Technology              | 3         | 0.37%   |
| Nvidia                           | 2         | 0.25%   |
| ICS Advent                       | 2         | 0.25%   |
| Hewlett-Packard                  | 2         | 0.25%   |
| Lenovo                           | 1         | 0.12%   |
| Huawei Technologies              | 1         | 0.12%   |
| HTC (High Tech Computer)         | 1         | 0.12%   |
| Foxconn / Hon Hai                | 1         | 0.12%   |
| ASUSTek Computer                 | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 346       | 43.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 124       | 15.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 4.35%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 2.49%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 1.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 12        | 1.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 1.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 1.49%   |
| OPPO RMX3623                                                      | 9         | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 1%      |
| Intel Ethernet Connection I219-LM                                 | 8         | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 8         | 1%      |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 7         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 0.87%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.75%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.75%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.62%   |
| MediaTek X55                                                      | 5         | 0.62%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 5         | 0.62%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.62%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 0.5%    |
| Intel Ethernet Connection I219-V                                  | 4         | 0.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.37%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.37%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.37%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 3         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 929       | 54.81%  |
| Ethernet | 756       | 44.6%   |
| Modem    | 10        | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 814       | 87.06%  |
| Ethernet | 120       | 12.83%  |
| Modem    | 1         | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 707       | 74.74%  |
| 1     | 221       | 23.36%  |
| 0     | 15        | 1.59%   |
| 3     | 3         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 877       | 91.64%  |
| Yes  | 80        | 8.36%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 250       | 33.56%  |
| Realtek Semiconductor           | 130       | 17.45%  |
| IMC Networks                    | 83        | 11.14%  |
| Qualcomm Atheros Communications | 71        | 9.53%   |
| Lite-On Technology              | 63        | 8.46%   |
| Broadcom                        | 47        | 6.31%   |
| Foxconn / Hon Hai               | 31        | 4.16%   |
| Toshiba                         | 14        | 1.88%   |
| Dell                            | 10        | 1.34%   |
| Cambridge Silicon Radio         | 10        | 1.34%   |
| Apple                           | 10        | 1.34%   |
| Ralink                          | 5         | 0.67%   |
| Hewlett-Packard                 | 5         | 0.67%   |
| Foxconn International           | 4         | 0.54%   |
| Realtek                         | 3         | 0.4%    |
| ASUSTek Computer                | 3         | 0.4%    |
| Micro Star International        | 2         | 0.27%   |
| MediaTek                        | 2         | 0.27%   |
| Chicony Electronics             | 1         | 0.13%   |
| Alps Electric                   | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 98        | 13.15%  |
| Realtek Bluetooth Radio                             | 72        | 9.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 67        | 8.99%   |
| IMC Networks Bluetooth Device                       | 48        | 6.44%   |
| Intel AX201 Bluetooth                               | 35        | 4.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 34        | 4.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 32        | 4.3%    |
| Lite-On Bluetooth Device                            | 24        | 3.22%   |
| Intel AX200 Bluetooth                               | 17        | 2.28%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 2.15%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 2.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 1.88%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 13        | 1.74%   |
| IMC Networks Bluetooth Radio                        | 13        | 1.74%   |
| Realtek RTL8723B Bluetooth                          | 11        | 1.48%   |
| Lite-On Wireless_Device                             | 11        | 1.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 1.34%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 1.34%   |
| Realtek 802.11ac WLAN Adapter                       | 8         | 1.07%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 1.07%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.94%   |
| Intel Bluetooth Device                              | 7         | 0.94%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 7         | 0.94%   |
| Lite-On Atheros Bluetooth                           | 6         | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 0.81%   |
| IMC Networks Wireless_Device                        | 6         | 0.81%   |
| Apple Bluetooth Host Controller                     | 6         | 0.81%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.67%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 0.67%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 5         | 0.67%   |
| Broadcom HP Portable SoftSailing                    | 5         | 0.67%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 5         | 0.67%   |
| Toshiba RT Bluetooth Radio                          | 4         | 0.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.54%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.54%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.54%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.54%   |
| Broadcom BCM43142A0 Bluetooth Device                | 4         | 0.54%   |
| Broadcom BCM20702A0                                 | 4         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 692       | 66.54%  |
| AMD                              | 242       | 23.27%  |
| Nvidia                           | 77        | 7.4%    |
| Silicon Integrated Systems [SiS] | 4         | 0.38%   |
| JMTek                            | 4         | 0.38%   |
| Generalplus Technology           | 4         | 0.38%   |
| Samson Technologies              | 3         | 0.29%   |
| Samsung Electronics              | 2         | 0.19%   |
| C-Media Electronics              | 2         | 0.19%   |
| BR25                             | 2         | 0.19%   |
| ASUSTek Computer                 | 2         | 0.19%   |
| SAVITECH                         | 1         | 0.1%    |
| Logitech                         | 1         | 0.1%    |
| FDUCE PRO AUDIO MADE             | 1         | 0.1%    |
| Cooler Master                    | 1         | 0.1%    |
| Conexant Systems                 | 1         | 0.1%    |
| Barco Display Systems            | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 119       | 8.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 100       | 7.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 95        | 6.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 61        | 4.46%   |
| AMD FCH Azalia Controller                                                                         | 56        | 4.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 52        | 3.8%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 50        | 3.66%   |
| Intel 8 Series HD Audio Controller                                                                | 50        | 3.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 48        | 3.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 48        | 3.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 45        | 3.29%   |
| AMD Kabini HDMI/DP Audio                                                                          | 43        | 3.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 42        | 3.07%   |
| Intel Broadwell-U Audio Controller                                                                | 42        | 3.07%   |
| AMD High Definition Audio Controller                                                              | 39        | 2.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 33        | 2.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 31        | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 26        | 1.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 24        | 1.76%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 22        | 1.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 22        | 1.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 17        | 1.24%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 17        | 1.24%   |
| AMD Wrestler HDMI Audio                                                                           | 15        | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 1.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 0.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 13        | 0.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 0.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 0.73%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 0.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 0.73%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 10        | 0.73%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.59%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 7         | 0.51%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 7         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 228       | 31.28%  |
| SK hynix                                | 143       | 19.62%  |
| Micron Technology                       | 87        | 11.93%  |
| Kingston                                | 58        | 7.96%   |
| Unknown                                 | 45        | 6.17%   |
| Team                                    | 25        | 3.43%   |
| Corsair                                 | 24        | 3.29%   |
| V-GeN                                   | 21        | 2.88%   |
| Ramaxel Technology                      | 19        | 2.61%   |
| Elpida                                  | 13        | 1.78%   |
| Nanya Technology                        | 11        | 1.51%   |
| Unknown (ABCD)                          | 10        | 1.37%   |
| A-DATA Technology                       | 8         | 1.1%    |
| Transcend                               | 4         | 0.55%   |
| Apacer                                  | 4         | 0.55%   |
| Unknown                                 | 4         | 0.55%   |
| Crucial                                 | 3         | 0.41%   |
| Visipro                                 | 2         | 0.27%   |
| SHARETRONIC                             | 2         | 0.27%   |
| Lexar                                   | 2         | 0.27%   |
| ASint Technology                        | 2         | 0.27%   |
| A Force                                 | 2         | 0.27%   |
| Unknown (8A02)                          | 1         | 0.14%   |
| Strontium                               | 1         | 0.14%   |
| Silicon Power Computer & Communications | 1         | 0.14%   |
| Silicon Power                           | 1         | 0.14%   |
| Qumo                                    | 1         | 0.14%   |
| Patriot                                 | 1         | 0.14%   |
| Kingmax                                 | 1         | 0.14%   |
| GOODRAM                                 | 1         | 0.14%   |
| Goldkey                                 | 1         | 0.14%   |
| Foxline                                 | 1         | 0.14%   |
| ff                                      | 1         | 0.14%   |
| 4ea5                                    | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 1.9%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 1.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 1.65%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 12        | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 10        | 1.27%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 10        | 1.27%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.14%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 9         | 1.14%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 1.02%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 8         | 1.02%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.02%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 8         | 1.02%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 1.02%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 8         | 1.02%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s            | 7         | 0.89%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 7         | 0.89%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.89%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.89%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.76%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.76%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.76%   |
| Micron RAM 4ATF51264HZ_3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.76%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.63%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.63%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.63%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 5         | 0.63%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s             | 5         | 0.63%   |
| Kingston RAM 9905625-004.A03LF 4GB SODIMM DDR3 3200MT/s          | 5         | 0.63%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 4         | 0.51%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.51%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.51%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s        | 4         | 0.51%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 0.51%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 4         | 0.51%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.51%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 250       | 44.4%   |
| DDR3    | 236       | 41.92%  |
| LPDDR4  | 30        | 5.33%   |
| DDR2    | 16        | 2.84%   |
| LPDDR3  | 11        | 1.95%   |
| SDRAM   | 8         | 1.42%   |
| LPDDR5  | 8         | 1.42%   |
| Unknown | 2         | 0.36%   |
| DRAM    | 1         | 0.18%   |
| DDR5    | 1         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 518       | 90.56%  |
| Row Of Chips | 47        | 8.22%   |
| Chip         | 5         | 0.87%   |
| Unknown      | 2         | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 267       | 40.83%  |
| 8192  | 221       | 33.79%  |
| 2048  | 87        | 13.3%   |
| 16384 | 52        | 7.95%   |
| 32768 | 16        | 2.45%   |
| 1024  | 10        | 1.53%   |
| 512   | 1         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 170       | 26.03%  |
| 2667    | 114       | 17.46%  |
| 3200    | 105       | 16.08%  |
| 2400    | 60        | 9.19%   |
| 2133    | 33        | 5.05%   |
| 1334    | 32        | 4.9%    |
| 1333    | 27        | 4.13%   |
| 1067    | 16        | 2.45%   |
| 3266    | 15        | 2.3%    |
| 4266    | 9         | 1.38%   |
| 800     | 9         | 1.38%   |
| Unknown | 9         | 1.38%   |
| 8400    | 7         | 1.07%   |
| 4267    | 7         | 1.07%   |
| 667     | 7         | 1.07%   |
| 6400    | 6         | 0.92%   |
| 1867    | 6         | 0.92%   |
| 4199    | 5         | 0.77%   |
| 533     | 3         | 0.46%   |
| 2048    | 2         | 0.31%   |
| 1866    | 2         | 0.31%   |
| 1066    | 2         | 0.31%   |
| 7467    | 1         | 0.15%   |
| 5500    | 1         | 0.15%   |
| 4800    | 1         | 0.15%   |
| 3333    | 1         | 0.15%   |
| 1776    | 1         | 0.15%   |
| 975     | 1         | 0.15%   |
| 333     | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 8         | 57.14%  |
| Canon              | 3         | 21.43%  |
| Brother Industries | 2         | 14.29%  |
| STMicroelectronics | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seiko Epson L360 Series                 | 2         | 14.29%  |
| Seiko Epson L310 Series                 | 2         | 14.29%  |
| Canon iP2700 series                     | 2         | 14.29%  |
| Brother DCP-T300                        | 2         | 14.29%  |
| STMicroelectronics USB Printing Support | 1         | 7.14%   |
| Seiko Epson L405 Series                 | 1         | 7.14%   |
| Seiko Epson L355 Series                 | 1         | 7.14%   |
| Seiko Epson L3210 Series                | 1         | 7.14%   |
| Seiko Epson L120 Series                 | 1         | 7.14%   |
| Canon CanoScan LiDE 300                 | 1         | 7.14%   |

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


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 4400F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 236       | 27.96%  |
| IMC Networks                           | 124       | 14.69%  |
| Realtek Semiconductor                  | 74        | 8.77%   |
| Bison Electronics                      | 64        | 7.58%   |
| Sunplus Innovation Technology          | 47        | 5.57%   |
| Quanta                                 | 46        | 5.45%   |
| Cheng Uei Precision Industry (Foxlink) | 40        | 4.74%   |
| Syntek                                 | 37        | 4.38%   |
| Microdia                               | 35        | 4.15%   |
| Suyin                                  | 24        | 2.84%   |
| Alcor Micro                            | 24        | 2.84%   |
| Lite-On Technology                     | 11        | 1.3%    |
| Acer                                   | 11        | 1.3%    |
| Luxvisions Innotech Limited            | 9         | 1.07%   |
| Apple                                  | 9         | 1.07%   |
| Silicon Motion                         | 7         | 0.83%   |
| Sonix Technology                       | 6         | 0.71%   |
| Ricoh                                  | 6         | 0.71%   |
| Importek                               | 6         | 0.71%   |
| Primax Electronics                     | 4         | 0.47%   |
| Lenovo                                 | 3         | 0.36%   |
| Sunplus Technology                     | 2         | 0.24%   |
| Jieli Technology                       | 2         | 0.24%   |
| ALi                                    | 2         | 0.24%   |
| Unknown                                | 2         | 0.24%   |
| Tripath Technology                     | 1         | 0.12%   |
| SunplusIT                              | 1         | 0.12%   |
| Pixart Imaging                         | 1         | 0.12%   |
| OPPO Electronics                       | 1         | 0.12%   |
| Omnivision                             | 1         | 0.12%   |
| Logitech                               | 1         | 0.12%   |
| Huawei Technologies                    | 1         | 0.12%   |
| HDR webcam                             | 1         | 0.12%   |
| Genesys Logic                          | 1         | 0.12%   |
| GEMBIRD                                | 1         | 0.12%   |
| eMPIA Technology                       | 1         | 0.12%   |
| DigiTech                               | 1         | 0.12%   |
| 8SSC20F27114V1SR0BK1X4S                | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 35        | 4.14%   |
| Chicony HD WebCam                                               | 33        | 3.9%    |
| Chicony Integrated Camera                                       | 32        | 3.78%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 30        | 3.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 27        | 3.19%   |
| Syntek Integrated Camera                                        | 22        | 2.6%    |
| IMC Networks Integrated Camera                                  | 21        | 2.48%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 17        | 2.01%   |
| Chicony USB2.0 HD UVC WebCam                                    | 17        | 2.01%   |
| Chicony HP TrueVision HD Camera                                 | 15        | 1.77%   |
| Microdia Integrated_Webcam_HD                                   | 14        | 1.65%   |
| Realtek USB Camera                                              | 13        | 1.54%   |
| Bison Integrated Camera                                         | 13        | 1.54%   |
| Quanta HD User Facing                                           | 12        | 1.42%   |
| IMC Networks Lenovo EasyCamera                                  | 12        | 1.42%   |
| Bison Lenovo EasyCamera                                         | 12        | 1.42%   |
| Realtek Integrated_Webcam_HD                                    | 11        | 1.3%    |
| IMC Networks EasyCamera                                         | 11        | 1.3%    |
| Sunplus Asus Webcam                                             | 10        | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 10        | 1.18%   |
| Microdia Integrated Webcam                                      | 9         | 1.06%   |
| Chicony Lenovo EasyCamera                                       | 9         | 1.06%   |
| Chicony HP Truevision HD                                        | 9         | 1.06%   |
| Chicony EasyCamera                                              | 9         | 1.06%   |
| Syntek EasyCamera                                               | 8         | 0.95%   |
| Realtek USB2.0 HD UVC WebCam                                    | 8         | 0.95%   |
| Chicony TOSHIBA Web Camera - HD                                 | 8         | 0.95%   |
| Bison EasyCamera                                                | 8         | 0.95%   |
| Alcor Micro USB 2.0 Camera                                      | 8         | 0.95%   |
| Suyin 1.3M HD WebCam                                            | 7         | 0.83%   |
| Sunplus Integrated_Webcam_HD                                    | 7         | 0.83%   |
| Quanta VGA WebCam                                               | 7         | 0.83%   |
| Quanta HP TrueVision HD Camera                                  | 7         | 0.83%   |
| Chicony HD User Facing                                          | 7         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 7         | 0.83%   |
| Bison HD Webcam                                                 | 7         | 0.83%   |
| Alcor Micro Asus Integrated Webcam                              | 7         | 0.83%   |
| Syntek Lenovo EasyCamera                                        | 6         | 0.71%   |
| Sonix USB2.0 HD UVC WebCam                                      | 6         | 0.71%   |
| Quanta HD Webcam                                                | 6         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 42        | 32.81%  |
| Elan Microelectronics      | 25        | 19.53%  |
| Synaptics                  | 21        | 16.41%  |
| LighTuning Technology      | 12        | 9.38%   |
| Shenzhen Goodix Technology | 11        | 8.59%   |
| AuthenTec                  | 9         | 7.03%   |
| Upek                       | 5         | 3.91%   |
| STMicroelectronics         | 2         | 1.56%   |
| DigitalPersona             | 1         | 0.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                       | 13        | 10.16%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 11        | 8.59%   |
| Elan ELAN:Fingerprint                                  | 11        | 8.59%   |
| Validity Sensors VFS495 Fingerprint Reader             | 9         | 7.03%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 8         | 6.25%   |
| Shenzhen Goodix  FingerPrint Device                    | 7         | 5.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 6         | 4.69%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 5         | 3.91%   |
| Validity Sensors Swipe Fingerprint Sensor              | 5         | 3.91%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 5         | 3.91%   |
| Validity Sensors VFS491                                | 4         | 3.13%   |
| Validity Sensors VFS Fingerprint sensor                | 4         | 3.13%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 3.13%   |
| Shenzhen Goodix Fingerprint Reader                     | 4         | 3.13%   |
| AuthenTec AES1600                                      | 4         | 3.13%   |
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 2.34%   |
| Synaptics  WBDI                                        | 3         | 2.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 1.56%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 2         | 1.56%   |
| Synaptics UWP WBDI                                     | 2         | 1.56%   |
| Synaptics Fingerprint reader [HP G6]                   | 2         | 1.56%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 1.56%   |
| AuthenTec Fingerprint Sensor                           | 2         | 1.56%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 2         | 1.56%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 0.78%   |
| Validity Sensors Synaptics WBDI                        | 1         | 0.78%   |
| Synaptics WBDI                                         | 1         | 0.78%   |
| Synaptics UWP WBDI Device                              | 1         | 0.78%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 0.78%   |
| Elan fingerprint sensor [FeinTech FPS00200]            | 1         | 0.78%   |
| DigitalPersona Fingerprint Reader                      | 1         | 0.78%   |
| AuthenTec AES2810                                      | 1         | 0.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 21        | 55.26%  |
| Alcor Micro | 6         | 15.79%  |
| O2 Micro    | 5         | 13.16%  |
| Upek        | 4         | 10.53%  |
| Lenovo      | 2         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 12        | 31.58%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 15.79%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 13.16%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 13.16%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 10.53%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.26%   |
| Broadcom 5880                                                                | 2         | 5.26%   |
| Broadcom 58200                                                               | 2         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 664       | 68.67%  |
| 1     | 239       | 24.72%  |
| 2     | 56        | 5.79%   |
| 3     | 7         | 0.72%   |
| 6     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 127       | 35.47%  |
| Graphics card            | 85        | 23.74%  |
| Net/wireless             | 38        | 10.61%  |
| Chipcard                 | 35        | 9.78%   |
| Multimedia controller    | 23        | 6.42%   |
| Bluetooth                | 18        | 5.03%   |
| Camera                   | 8         | 2.23%   |
| Communication controller | 6         | 1.68%   |
| Net/ethernet             | 5         | 1.4%    |
| Storage                  | 4         | 1.12%   |
| Sound                    | 2         | 0.56%   |
| Flash memory             | 2         | 0.56%   |
| Card reader              | 2         | 0.56%   |
| Video                    | 1         | 0.28%   |
| Network                  | 1         | 0.28%   |
| Modem                    | 1         | 0.28%   |

