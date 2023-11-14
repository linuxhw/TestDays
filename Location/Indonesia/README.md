Linux in Indonesia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Indonesia/Desktop/README.md) and [notebooks](/Location/Indonesia/Notebook/README.md).

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

Total: 1952

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [04327aa85c](https://linux-hardware.org/?probe=04327aa85c) | Nov 06, 2023 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [61828bc39f](https://linux-hardware.org/?probe=61828bc39f) | Nov 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [669430e32e](https://linux-hardware.org/?probe=669430e32e) | Nov 04, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [f0354d2416](https://linux-hardware.org/?probe=f0354d2416) | Nov 04, 2023 |
| Acidanther... | MacBookPro15,2              | Notebook    | [ae60650070](https://linux-hardware.org/?probe=ae60650070) | Nov 04, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [0ce0a4d87a](https://linux-hardware.org/?probe=0ce0a4d87a) | Nov 04, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | X456UR                      | Notebook    | [9a0a4dfd02](https://linux-hardware.org/?probe=9a0a4dfd02) | Nov 02, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [2b76c45313](https://linux-hardware.org/?probe=2b76c45313) | Nov 02, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [fffa5fb420](https://linux-hardware.org/?probe=fffa5fb420) | Nov 02, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [a7f47546e5](https://linux-hardware.org/?probe=a7f47546e5) | Nov 01, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [8901bca741](https://linux-hardware.org/?probe=8901bca741) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [5787618dae](https://linux-hardware.org/?probe=5787618dae) | Oct 31, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [bc8c6e67a9](https://linux-hardware.org/?probe=bc8c6e67a9) | Oct 28, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [63b5c65c01](https://linux-hardware.org/?probe=63b5c65c01) | Oct 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [220dddac59](https://linux-hardware.org/?probe=220dddac59) | Oct 28, 2023 |
| Dell          | Precision 5530              | Notebook    | [e707fe59cc](https://linux-hardware.org/?probe=e707fe59cc) | Oct 27, 2023 |
| Dell          | 0HH807                      | Desktop     | [7f15d65c22](https://linux-hardware.org/?probe=7f15d65c22) | Oct 27, 2023 |
| HP            | Notebook                    | Notebook    | [1f270f615f](https://linux-hardware.org/?probe=1f270f615f) | Oct 27, 2023 |
| Acer          | EG31M R01-C3                | Desktop     | [8a4232c8f0](https://linux-hardware.org/?probe=8a4232c8f0) | Oct 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [a70d4b8a0d](https://linux-hardware.org/?probe=a70d4b8a0d) | Oct 25, 2023 |
| HP            | 198E                        | Desktop     | [3102593d74](https://linux-hardware.org/?probe=3102593d74) | Oct 25, 2023 |
| Dell          | Inspiron One 2310           | Notebook    | [1a8d313e86](https://linux-hardware.org/?probe=1a8d313e86) | Oct 25, 2023 |
| Dell          | Latitude 5285               | Notebook    | [9af5195620](https://linux-hardware.org/?probe=9af5195620) | Oct 24, 2023 |
| Dell          | Latitude 5320               | Notebook    | [520c2effa3](https://linux-hardware.org/?probe=520c2effa3) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [5b608b97fc](https://linux-hardware.org/?probe=5b608b97fc) | Oct 23, 2023 |
| Dell          | Latitude 5285               | Notebook    | [9552613f54](https://linux-hardware.org/?probe=9552613f54) | Oct 23, 2023 |
| Dell          | Latitude E6320              | Notebook    | [c6965e07e3](https://linux-hardware.org/?probe=c6965e07e3) | Oct 21, 2023 |
| Dell          | Inspiron 3458               | Notebook    | [ff4adff045](https://linux-hardware.org/?probe=ff4adff045) | Oct 21, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [fe4a9ec4d0](https://linux-hardware.org/?probe=fe4a9ec4d0) | Oct 20, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [1c0c1df851](https://linux-hardware.org/?probe=1c0c1df851) | Oct 20, 2023 |
| MSI           | 770T-C45                    | Desktop     | [bbe901612f](https://linux-hardware.org/?probe=bbe901612f) | Oct 20, 2023 |
| Toshiba       | dynabook R732/H             | Notebook    | [4852b6da95](https://linux-hardware.org/?probe=4852b6da95) | Oct 20, 2023 |
| HP            | Notebook                    | Notebook    | [3fb8313450](https://linux-hardware.org/?probe=3fb8313450) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [71ffea0397](https://linux-hardware.org/?probe=71ffea0397) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [9ab2c722a5](https://linux-hardware.org/?probe=9ab2c722a5) | Oct 19, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [459dc02cda](https://linux-hardware.org/?probe=459dc02cda) | Oct 18, 2023 |
| Acer          | Aspire E3-112M              | Notebook    | [11d6580d3e](https://linux-hardware.org/?probe=11d6580d3e) | Oct 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [0270e71d5e](https://linux-hardware.org/?probe=0270e71d5e) | Oct 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [329a5f99e0](https://linux-hardware.org/?probe=329a5f99e0) | Oct 18, 2023 |
| MicroByte     | ezbook                      | Notebook    | [c67055c10c](https://linux-hardware.org/?probe=c67055c10c) | Oct 17, 2023 |
| MicroByte     | ezbook                      | Notebook    | [5018eaffae](https://linux-hardware.org/?probe=5018eaffae) | Oct 17, 2023 |
| Toshiba       | Satellite L645              | Notebook    | [5bea545bf5](https://linux-hardware.org/?probe=5bea545bf5) | Oct 16, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [bfbd0b0a49](https://linux-hardware.org/?probe=bfbd0b0a49) | Oct 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [ec059c9ea7](https://linux-hardware.org/?probe=ec059c9ea7) | Oct 15, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [3d63dd4590](https://linux-hardware.org/?probe=3d63dd4590) | Oct 13, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [c1e1d017af](https://linux-hardware.org/?probe=c1e1d017af) | Oct 13, 2023 |
| Toshiba       | Satellite C55D-C            | Notebook    | [e083a8012f](https://linux-hardware.org/?probe=e083a8012f) | Oct 11, 2023 |
| HP            | 430                         | Notebook    | [e62771b9a7](https://linux-hardware.org/?probe=e62771b9a7) | Oct 09, 2023 |
| HP            | 430                         | Notebook    | [71211a4eda](https://linux-hardware.org/?probe=71211a4eda) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f3348806a2](https://linux-hardware.org/?probe=f3348806a2) | Oct 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f269e7a6ee](https://linux-hardware.org/?probe=f269e7a6ee) | Oct 09, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [1bb42f8755](https://linux-hardware.org/?probe=1bb42f8755) | Oct 09, 2023 |
| Acer          | Swift SF314-56G             | Notebook    | [2696a8d9c0](https://linux-hardware.org/?probe=2696a8d9c0) | Oct 08, 2023 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [c40356b94d](https://linux-hardware.org/?probe=c40356b94d) | Oct 05, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [d48122086b](https://linux-hardware.org/?probe=d48122086b) | Oct 04, 2023 |
| Acer          | Swift SF314-56G             | Notebook    | [15b613a264](https://linux-hardware.org/?probe=15b613a264) | Oct 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [0df81159a2](https://linux-hardware.org/?probe=0df81159a2) | Oct 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a3773ae099](https://linux-hardware.org/?probe=a3773ae099) | Oct 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [25211e6ce1](https://linux-hardware.org/?probe=25211e6ce1) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| ASRock        | A88M-G                      | Desktop     | [a918b08771](https://linux-hardware.org/?probe=a918b08771) | Sep 30, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [80ac43658d](https://linux-hardware.org/?probe=80ac43658d) | Sep 30, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [79b4f4f30e](https://linux-hardware.org/?probe=79b4f4f30e) | Sep 30, 2023 |
| Gigabyte      | P31-ES3G                    | Desktop     | [bee14e504c](https://linux-hardware.org/?probe=bee14e504c) | Sep 30, 2023 |
| Lenovo        | ThinkPad L530 24783R8       | Notebook    | [eda040f456](https://linux-hardware.org/?probe=eda040f456) | Sep 30, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [7c8b825512](https://linux-hardware.org/?probe=7c8b825512) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [d95e370c54](https://linux-hardware.org/?probe=d95e370c54) | Sep 29, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [eeb582da25](https://linux-hardware.org/?probe=eeb582da25) | Sep 28, 2023 |
| Dell          | Latitude 7490               | Notebook    | [6f5e4547fa](https://linux-hardware.org/?probe=6f5e4547fa) | Sep 27, 2023 |
| ZOTAC         | NM10                        | Desktop     | [8932b16aa1](https://linux-hardware.org/?probe=8932b16aa1) | Sep 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [8bb2e054ec](https://linux-hardware.org/?probe=8bb2e054ec) | Sep 26, 2023 |
| Acer          | Aspire M5910                | Desktop     | [5b44d1de35](https://linux-hardware.org/?probe=5b44d1de35) | Sep 25, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [6383f263a8](https://linux-hardware.org/?probe=6383f263a8) | Sep 25, 2023 |
| Toshiba       | dynabook R632/H             | Notebook    | [7279759e40](https://linux-hardware.org/?probe=7279759e40) | Sep 25, 2023 |
| Acer          | Aspire S3                   | Notebook    | [4b2b76bdb3](https://linux-hardware.org/?probe=4b2b76bdb3) | Sep 24, 2023 |
| Acer          | Aspire S3                   | Notebook    | [723a872112](https://linux-hardware.org/?probe=723a872112) | Sep 24, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [4c12bddd77](https://linux-hardware.org/?probe=4c12bddd77) | Sep 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [80e28a9df2](https://linux-hardware.org/?probe=80e28a9df2) | Sep 22, 2023 |
| HP            | Laptop 14-ep0xxx            | Notebook    | [ee7b0c8506](https://linux-hardware.org/?probe=ee7b0c8506) | Sep 21, 2023 |
| Lenovo        | V14 G3 IAP 82TS             | Notebook    | [2528381c0e](https://linux-hardware.org/?probe=2528381c0e) | Sep 21, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [efafe71bd6](https://linux-hardware.org/?probe=efafe71bd6) | Sep 21, 2023 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [a1356bddb2](https://linux-hardware.org/?probe=a1356bddb2) | Sep 21, 2023 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [77e008b6d9](https://linux-hardware.org/?probe=77e008b6d9) | Sep 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [09433de4b0](https://linux-hardware.org/?probe=09433de4b0) | Sep 20, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [98a32c8241](https://linux-hardware.org/?probe=98a32c8241) | Sep 19, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [a8995def08](https://linux-hardware.org/?probe=a8995def08) | Sep 19, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [417ad95c4c](https://linux-hardware.org/?probe=417ad95c4c) | Sep 18, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c27b81ea3e](https://linux-hardware.org/?probe=c27b81ea3e) | Sep 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [378490ed0b](https://linux-hardware.org/?probe=378490ed0b) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| HP            | 245 G7 Notebook PC          | Notebook    | [ab68dea087](https://linux-hardware.org/?probe=ab68dea087) | Sep 14, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [877e70bb6f](https://linux-hardware.org/?probe=877e70bb6f) | Sep 14, 2023 |
| MSI           | MS-B9091                    | Desktop     | [5b1250945b](https://linux-hardware.org/?probe=5b1250945b) | Sep 11, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [6259de24be](https://linux-hardware.org/?probe=6259de24be) | Sep 11, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [00e5dd81d7](https://linux-hardware.org/?probe=00e5dd81d7) | Sep 10, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [16c285bb07](https://linux-hardware.org/?probe=16c285bb07) | Sep 10, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [c59551fc6f](https://linux-hardware.org/?probe=c59551fc6f) | Sep 09, 2023 |
| MSI           | MS-B9091                    | Desktop     | [226300a88d](https://linux-hardware.org/?probe=226300a88d) | Sep 09, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [5564e70c85](https://linux-hardware.org/?probe=5564e70c85) | Sep 09, 2023 |
| ASUSTek       | X201EP                      | Notebook    | [a714c5a35a](https://linux-hardware.org/?probe=a714c5a35a) | Sep 09, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [34e95a943a](https://linux-hardware.org/?probe=34e95a943a) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [cbd5cf3e4b](https://linux-hardware.org/?probe=cbd5cf3e4b) | Sep 08, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [89b56b4baf](https://linux-hardware.org/?probe=89b56b4baf) | Sep 06, 2023 |
| Intel         | NUC12WSBi5 M46425-304       | Mini pc     | [d75c936b50](https://linux-hardware.org/?probe=d75c936b50) | Sep 06, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [56f00eec4a](https://linux-hardware.org/?probe=56f00eec4a) | Sep 05, 2023 |
| Sony          | VGN-CS108D                  | Notebook    | [24bf5bb06c](https://linux-hardware.org/?probe=24bf5bb06c) | Sep 05, 2023 |
| Acer          | Veriton M480                | Desktop     | [0c97015cce](https://linux-hardware.org/?probe=0c97015cce) | Sep 05, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [1a1c5e43bc](https://linux-hardware.org/?probe=1a1c5e43bc) | Sep 05, 2023 |
| AXIOO         | Mybook 14E                  | Notebook    | [b6ddb628dc](https://linux-hardware.org/?probe=b6ddb628dc) | Sep 04, 2023 |
| Foxconn       | G31MX Series                | Desktop     | [4b4c5fb5f8](https://linux-hardware.org/?probe=4b4c5fb5f8) | Sep 04, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [6edc4e910d](https://linux-hardware.org/?probe=6edc4e910d) | Sep 04, 2023 |
| HP            | EliteBook Revolve 810 G2    | Notebook    | [3f102b35e3](https://linux-hardware.org/?probe=3f102b35e3) | Sep 04, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [e27673ed4c](https://linux-hardware.org/?probe=e27673ed4c) | Sep 03, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [959fb04734](https://linux-hardware.org/?probe=959fb04734) | Sep 03, 2023 |
| Sony          | VPCYB15AG                   | Notebook    | [e192029ff0](https://linux-hardware.org/?probe=e192029ff0) | Sep 03, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [2180bc1b72](https://linux-hardware.org/?probe=2180bc1b72) | Sep 01, 2023 |
| Acer          | Aspire E5-475G              | Notebook    | [55542f9b89](https://linux-hardware.org/?probe=55542f9b89) | Aug 31, 2023 |
| Dell          | Latitude E6410              | Notebook    | [c2337bbe75](https://linux-hardware.org/?probe=c2337bbe75) | Aug 31, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [13ec5c53cf](https://linux-hardware.org/?probe=13ec5c53cf) | Aug 31, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [5cfa9a748f](https://linux-hardware.org/?probe=5cfa9a748f) | Aug 31, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [02708536f4](https://linux-hardware.org/?probe=02708536f4) | Aug 30, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [f7a484830d](https://linux-hardware.org/?probe=f7a484830d) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aa10544f35](https://linux-hardware.org/?probe=aa10544f35) | Aug 30, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2a2adfdc2e](https://linux-hardware.org/?probe=2a2adfdc2e) | Aug 30, 2023 |
| Fujitsu       | FMVU14003                   | Notebook    | [8da3625e06](https://linux-hardware.org/?probe=8da3625e06) | Aug 27, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [5b334ec725](https://linux-hardware.org/?probe=5b334ec725) | Aug 27, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [1986877980](https://linux-hardware.org/?probe=1986877980) | Aug 25, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [2a72d00223](https://linux-hardware.org/?probe=2a72d00223) | Aug 25, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [f79de96905](https://linux-hardware.org/?probe=f79de96905) | Aug 23, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [abae84243d](https://linux-hardware.org/?probe=abae84243d) | Aug 23, 2023 |
| Dell          | Latitude E6410              | Notebook    | [fbaef9218f](https://linux-hardware.org/?probe=fbaef9218f) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [8fd1db4fee](https://linux-hardware.org/?probe=8fd1db4fee) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [2cbbb89cd4](https://linux-hardware.org/?probe=2cbbb89cd4) | Aug 21, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [1d023bc980](https://linux-hardware.org/?probe=1d023bc980) | Aug 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c1a5eb75bf](https://linux-hardware.org/?probe=c1a5eb75bf) | Aug 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c47971e406](https://linux-hardware.org/?probe=c47971e406) | Aug 21, 2023 |
| Intel         | H81                         | Desktop     | [70d2da2312](https://linux-hardware.org/?probe=70d2da2312) | Aug 20, 2023 |
| Lenovo        | ThinkPad T540p 20BFS02S0... | Notebook    | [2f59ec7141](https://linux-hardware.org/?probe=2f59ec7141) | Aug 18, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [f368b5bf17](https://linux-hardware.org/?probe=f368b5bf17) | Aug 18, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [7f7f077fda](https://linux-hardware.org/?probe=7f7f077fda) | Aug 18, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [2c4ded9440](https://linux-hardware.org/?probe=2c4ded9440) | Aug 18, 2023 |
| Toshiba       | Satellite L510              | Notebook    | [f06d068ca0](https://linux-hardware.org/?probe=f06d068ca0) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [b7a28997df](https://linux-hardware.org/?probe=b7a28997df) | Aug 15, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [b78f4bf01d](https://linux-hardware.org/?probe=b78f4bf01d) | Aug 15, 2023 |
| MSI           | 3666h                       | Desktop     | [d3f51a2bf0](https://linux-hardware.org/?probe=d3f51a2bf0) | Aug 15, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | Notebook    | [c192c37af2](https://linux-hardware.org/?probe=c192c37af2) | Aug 14, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [857539aaba](https://linux-hardware.org/?probe=857539aaba) | Aug 14, 2023 |
| Dell          | 03015M A01                  | Server      | [82a456951b](https://linux-hardware.org/?probe=82a456951b) | Aug 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0ecb69efbc](https://linux-hardware.org/?probe=0ecb69efbc) | Aug 14, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2a753fd907](https://linux-hardware.org/?probe=2a753fd907) | Aug 14, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [182445f47d](https://linux-hardware.org/?probe=182445f47d) | Aug 13, 2023 |
| MSI           | Katana GF66 11UD            | Notebook    | [e7e9bfd605](https://linux-hardware.org/?probe=e7e9bfd605) | Aug 13, 2023 |
| Samsung       | 960XFH                      | Notebook    | [b7f35fe8b5](https://linux-hardware.org/?probe=b7f35fe8b5) | Aug 13, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [5d3d27c8bb](https://linux-hardware.org/?probe=5d3d27c8bb) | Aug 12, 2023 |
| Acer          | One Z1402                   | Notebook    | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [fadee3e38d](https://linux-hardware.org/?probe=fadee3e38d) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [49a3480efb](https://linux-hardware.org/?probe=49a3480efb) | Aug 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | Notebook    | [6de592988e](https://linux-hardware.org/?probe=6de592988e) | Aug 09, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [f78ce03ad4](https://linux-hardware.org/?probe=f78ce03ad4) | Aug 08, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [60d9dcfa89](https://linux-hardware.org/?probe=60d9dcfa89) | Aug 08, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [1c68b4d24a](https://linux-hardware.org/?probe=1c68b4d24a) | Aug 08, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [8491f5fc3b](https://linux-hardware.org/?probe=8491f5fc3b) | Aug 07, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [eab0544dc6](https://linux-hardware.org/?probe=eab0544dc6) | Aug 06, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [738a42f72e](https://linux-hardware.org/?probe=738a42f72e) | Aug 05, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [abb19010d2](https://linux-hardware.org/?probe=abb19010d2) | Aug 05, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [50be5e5725](https://linux-hardware.org/?probe=50be5e5725) | Aug 05, 2023 |
| Dell          | Latitude E6410              | Notebook    | [ad46549b01](https://linux-hardware.org/?probe=ad46549b01) | Aug 04, 2023 |
| Dell          | Latitude E6410              | Notebook    | [e2364d5aac](https://linux-hardware.org/?probe=e2364d5aac) | Aug 04, 2023 |
| MSI           | H81M-E35 V2                 | Desktop     | [2e72dc6560](https://linux-hardware.org/?probe=2e72dc6560) | Aug 04, 2023 |
| Dell          | 0GTK4K A10                  | Desktop     | [b6586709f2](https://linux-hardware.org/?probe=b6586709f2) | Aug 03, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | Notebook    | [73e1dd94b2](https://linux-hardware.org/?probe=73e1dd94b2) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | Notebook    | [a13fd4044e](https://linux-hardware.org/?probe=a13fd4044e) | Aug 01, 2023 |
| Unknown       | Generic RK322x Tv Box       | Other       | [db0911c516](https://linux-hardware.org/?probe=db0911c516) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming FX505DD          | Notebook    | [e965235133](https://linux-hardware.org/?probe=e965235133) | Jul 29, 2023 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [7642eb12d5](https://linux-hardware.org/?probe=7642eb12d5) | Jul 29, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [3afa5a3034](https://linux-hardware.org/?probe=3afa5a3034) | Jul 27, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [6632226064](https://linux-hardware.org/?probe=6632226064) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [24c092f0b0](https://linux-hardware.org/?probe=24c092f0b0) | Jul 26, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [bf88e1114e](https://linux-hardware.org/?probe=bf88e1114e) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [69b707119e](https://linux-hardware.org/?probe=69b707119e) | Jul 25, 2023 |
| Lenovo        | ThinkPad X230 23246V9       | Notebook    | [e7bc7dac48](https://linux-hardware.org/?probe=e7bc7dac48) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c78c35de44](https://linux-hardware.org/?probe=c78c35de44) | Jul 23, 2023 |
| Unknown       | Generic RK322x Tv Box       | Other       | [18c7d0154b](https://linux-hardware.org/?probe=18c7d0154b) | Jul 22, 2023 |
| HP            | 2187 A01                    | Desktop     | [efd197811b](https://linux-hardware.org/?probe=efd197811b) | Jul 22, 2023 |
| Fujitsu       | FMVNC4BC4                   | Notebook    | [14249b136a](https://linux-hardware.org/?probe=14249b136a) | Jul 19, 2023 |
| Acer          | Aspire E5-476G              | Notebook    | [74af6477be](https://linux-hardware.org/?probe=74af6477be) | Jul 19, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [3649d91857](https://linux-hardware.org/?probe=3649d91857) | Jul 18, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [462a41184d](https://linux-hardware.org/?probe=462a41184d) | Jul 17, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [4c07b0b74c](https://linux-hardware.org/?probe=4c07b0b74c) | Jul 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [eaaf1d2a5a](https://linux-hardware.org/?probe=eaaf1d2a5a) | Jul 16, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [c1c039384c](https://linux-hardware.org/?probe=c1c039384c) | Jul 11, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [94555c5887](https://linux-hardware.org/?probe=94555c5887) | Jul 10, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [de7dbebf49](https://linux-hardware.org/?probe=de7dbebf49) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | Notebook    | [fe9bfd5f77](https://linux-hardware.org/?probe=fe9bfd5f77) | Jul 10, 2023 |
| Unknown       | Generic RK322x Tv Box       | Other       | [a5da218315](https://linux-hardware.org/?probe=a5da218315) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | Notebook    | [d4dadd2e77](https://linux-hardware.org/?probe=d4dadd2e77) | Jul 10, 2023 |
| HP            | ProBook 4420s               | Notebook    | [51e917f03e](https://linux-hardware.org/?probe=51e917f03e) | Jul 09, 2023 |
| Gigabyte      | P55-USB3L                   | Desktop     | [b225c530bd](https://linux-hardware.org/?probe=b225c530bd) | Jul 09, 2023 |
| Acer          | Aspire 4720Z                | Notebook    | [312486a5b7](https://linux-hardware.org/?probe=312486a5b7) | Jul 09, 2023 |
| Lenovo        | Unknown                     | Convertible | [7c4ddbebf7](https://linux-hardware.org/?probe=7c4ddbebf7) | Jul 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [06b52888f8](https://linux-hardware.org/?probe=06b52888f8) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0048149cd5](https://linux-hardware.org/?probe=0048149cd5) | Jul 08, 2023 |
| Unknown       | Unknown                     | Soc         | [e31f4bb359](https://linux-hardware.org/?probe=e31f4bb359) | Jul 08, 2023 |
| Toshiba       | PORTEGE R30-C               | Notebook    | [f07f4d423b](https://linux-hardware.org/?probe=f07f4d423b) | Jul 07, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c5fcc4bcf0](https://linux-hardware.org/?probe=c5fcc4bcf0) | Jul 06, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f05e91be82](https://linux-hardware.org/?probe=f05e91be82) | Jul 06, 2023 |
| Toshiba       | Satellite C640              | Notebook    | [680f3038da](https://linux-hardware.org/?probe=680f3038da) | Jul 06, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [a0183085b8](https://linux-hardware.org/?probe=a0183085b8) | Jul 06, 2023 |
| AZW           | Z85                         | Notebook    | [ca44d0b498](https://linux-hardware.org/?probe=ca44d0b498) | Jul 05, 2023 |
| Acer          | Aspire V5-471G              | Notebook    | [6dd5e93eea](https://linux-hardware.org/?probe=6dd5e93eea) | Jul 05, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [f1ad74f37a](https://linux-hardware.org/?probe=f1ad74f37a) | Jul 05, 2023 |
| Dell          | Latitude E6540              | Notebook    | [17ec85df62](https://linux-hardware.org/?probe=17ec85df62) | Jul 05, 2023 |
| Dell          | Latitude 3410               | Notebook    | [11d9814008](https://linux-hardware.org/?probe=11d9814008) | Jul 02, 2023 |
| HP            | 8061                        | Desktop     | [429534fab2](https://linux-hardware.org/?probe=429534fab2) | Jul 01, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5873d04afe](https://linux-hardware.org/?probe=5873d04afe) | Jun 29, 2023 |
| Microsoft     | Surface Pro 2               | Tablet      | [5b92d42213](https://linux-hardware.org/?probe=5b92d42213) | Jun 29, 2023 |
| Alurin        | Go Notebook                 | Notebook    | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
| Intel         | Unknown                     | Desktop     | [3c85a0c7b9](https://linux-hardware.org/?probe=3c85a0c7b9) | Jun 28, 2023 |
| Intel         | Unknown                     | Desktop     | [dbfbe4b6aa](https://linux-hardware.org/?probe=dbfbe4b6aa) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0c87fda1f9](https://linux-hardware.org/?probe=0c87fda1f9) | Jun 27, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [40cbc38a69](https://linux-hardware.org/?probe=40cbc38a69) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [01a9e10a34](https://linux-hardware.org/?probe=01a9e10a34) | Jun 24, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [0cad0d9955](https://linux-hardware.org/?probe=0cad0d9955) | Jun 22, 2023 |
| Notebook      | P870DM                      | Notebook    | [cd318aa5a4](https://linux-hardware.org/?probe=cd318aa5a4) | Jun 21, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [9bcbbbd906](https://linux-hardware.org/?probe=9bcbbbd906) | Jun 21, 2023 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [d432122ffe](https://linux-hardware.org/?probe=d432122ffe) | Jun 21, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [2d8b92b0e6](https://linux-hardware.org/?probe=2d8b92b0e6) | Jun 20, 2023 |
| Dell          | G7 7588                     | Notebook    | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [6a6cfb05d6](https://linux-hardware.org/?probe=6a6cfb05d6) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [5296ca6ae2](https://linux-hardware.org/?probe=5296ca6ae2) | Jun 19, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [16bbd0f687](https://linux-hardware.org/?probe=16bbd0f687) | Jun 18, 2023 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [b1d6af488d](https://linux-hardware.org/?probe=b1d6af488d) | Jun 18, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d7e9625e19](https://linux-hardware.org/?probe=d7e9625e19) | Jun 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [1050576987](https://linux-hardware.org/?probe=1050576987) | Jun 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [76c1fcc4e5](https://linux-hardware.org/?probe=76c1fcc4e5) | Jun 14, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [3e4b7afb1e](https://linux-hardware.org/?probe=3e4b7afb1e) | Jun 10, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [9a69b50d97](https://linux-hardware.org/?probe=9a69b50d97) | Jun 07, 2023 |
| Infinix       | INBook X1 Pro               | Notebook    | [c558de3b74](https://linux-hardware.org/?probe=c558de3b74) | Jun 05, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [0a82b1aed3](https://linux-hardware.org/?probe=0a82b1aed3) | Jun 05, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [6754a25d1d](https://linux-hardware.org/?probe=6754a25d1d) | Jun 03, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3958079ad5](https://linux-hardware.org/?probe=3958079ad5) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| AXIOO         | Mybook-14E                  | Notebook    | [cb04b551d8](https://linux-hardware.org/?probe=cb04b551d8) | May 31, 2023 |
| ASUSTek       | X456URK                     | Notebook    | [6de2588617](https://linux-hardware.org/?probe=6de2588617) | May 29, 2023 |
| ASUSTek       | X456URK                     | Notebook    | [369aa4fc93](https://linux-hardware.org/?probe=369aa4fc93) | May 29, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| AVITA         | NE14A2                      | Notebook    | [89c5edafbc](https://linux-hardware.org/?probe=89c5edafbc) | May 28, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [db7d7cf31d](https://linux-hardware.org/?probe=db7d7cf31d) | May 26, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [b88a90f9d3](https://linux-hardware.org/?probe=b88a90f9d3) | May 25, 2023 |
| Panasonic     | CFSZ5-2                     | Notebook    | [d5b1455382](https://linux-hardware.org/?probe=d5b1455382) | May 25, 2023 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [e51dec5daf](https://linux-hardware.org/?probe=e51dec5daf) | May 24, 2023 |
| MSI           | 2A9C                        | Desktop     | [acaff65dda](https://linux-hardware.org/?probe=acaff65dda) | May 24, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [e752398b87](https://linux-hardware.org/?probe=e752398b87) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cbda228a9](https://linux-hardware.org/?probe=9cbda228a9) | May 23, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | Notebook    | [cfdb07c9ca](https://linux-hardware.org/?probe=cfdb07c9ca) | May 21, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | Notebook    | [379bcdafa9](https://linux-hardware.org/?probe=379bcdafa9) | May 21, 2023 |
| Sony          | VPCSB35FG                   | Notebook    | [81d2592989](https://linux-hardware.org/?probe=81d2592989) | May 20, 2023 |
| Sony          | VPCSB35FG                   | Notebook    | [828fb24994](https://linux-hardware.org/?probe=828fb24994) | May 20, 2023 |
| MSI           | 2A9C                        | Desktop     | [78d54a3ebf](https://linux-hardware.org/?probe=78d54a3ebf) | May 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [59902928be](https://linux-hardware.org/?probe=59902928be) | May 18, 2023 |
| ASUSTek       | V241EA                      | All in one  | [e4f05ea74b](https://linux-hardware.org/?probe=e4f05ea74b) | May 16, 2023 |
| Acer          | One Z1402                   | Notebook    | [390a684064](https://linux-hardware.org/?probe=390a684064) | May 16, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [6353fe7194](https://linux-hardware.org/?probe=6353fe7194) | May 16, 2023 |
| ASUSTek       | GL502VMK                    | Notebook    | [0b7232826d](https://linux-hardware.org/?probe=0b7232826d) | May 13, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [6d0f055f82](https://linux-hardware.org/?probe=6d0f055f82) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [7f90473be2](https://linux-hardware.org/?probe=7f90473be2) | May 11, 2023 |
| Infinix       | INBook X1                   | Notebook    | [c005323a1a](https://linux-hardware.org/?probe=c005323a1a) | May 11, 2023 |
| Intel         | H61                         | Desktop     | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| HP            | 83EB                        | All in one  | [0abdbdd77b](https://linux-hardware.org/?probe=0abdbdd77b) | May 10, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [036d26ffb3](https://linux-hardware.org/?probe=036d26ffb3) | May 10, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [e8f10d5f7e](https://linux-hardware.org/?probe=e8f10d5f7e) | May 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1b0786ec5e](https://linux-hardware.org/?probe=1b0786ec5e) | May 07, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [5491fd5858](https://linux-hardware.org/?probe=5491fd5858) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [98d7593057](https://linux-hardware.org/?probe=98d7593057) | May 05, 2023 |
| Dell          | Latitude D630               | Notebook    | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [9035ec79cd](https://linux-hardware.org/?probe=9035ec79cd) | May 02, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [f1537beedf](https://linux-hardware.org/?probe=f1537beedf) | May 01, 2023 |
| Acer          | Aspire A514-54G             | Notebook    | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Dell          | Latitude D630               | Notebook    | [a3c3e09675](https://linux-hardware.org/?probe=a3c3e09675) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c1616fcd6c](https://linux-hardware.org/?probe=c1616fcd6c) | Apr 28, 2023 |
| Dell          | Latitude D630               | Notebook    | [850df6e76f](https://linux-hardware.org/?probe=850df6e76f) | Apr 26, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [4591d1bf9d](https://linux-hardware.org/?probe=4591d1bf9d) | Apr 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [ff8440808f](https://linux-hardware.org/?probe=ff8440808f) | Apr 22, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [96fd44e94a](https://linux-hardware.org/?probe=96fd44e94a) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [6cf066b06b](https://linux-hardware.org/?probe=6cf066b06b) | Apr 19, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [40ae403838](https://linux-hardware.org/?probe=40ae403838) | Apr 18, 2023 |
| AXIOO         | SlimBook 11                 | Notebook    | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| Intel         | H61                         | Desktop     | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| Intel         | H61                         | Desktop     | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| Dell          | Latitude 7300               | Notebook    | [1064b58edb](https://linux-hardware.org/?probe=1064b58edb) | Apr 13, 2023 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| MSI           | Creator 15 A11UE            | Notebook    | [ca70d48c0e](https://linux-hardware.org/?probe=ca70d48c0e) | Apr 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [fc811580c9](https://linux-hardware.org/?probe=fc811580c9) | Apr 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [ca58518a03](https://linux-hardware.org/?probe=ca58518a03) | Apr 09, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [dbdef76cc2](https://linux-hardware.org/?probe=dbdef76cc2) | Apr 09, 2023 |
| AZW           | U59                         | Desktop     | [404036be4e](https://linux-hardware.org/?probe=404036be4e) | Apr 09, 2023 |
| HP            | Notebook                    | Notebook    | [584a741058](https://linux-hardware.org/?probe=584a741058) | Apr 08, 2023 |
| ASUSTek       | K46CM                       | Notebook    | [d878fad4d0](https://linux-hardware.org/?probe=d878fad4d0) | Apr 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [fcfcfdbbe7](https://linux-hardware.org/?probe=fcfcfdbbe7) | Apr 06, 2023 |
| Acer          | EG31M R01-C3                | Desktop     | [a548c9e661](https://linux-hardware.org/?probe=a548c9e661) | Apr 05, 2023 |
| Toshiba       | Satellite L640              | Notebook    | [8009d927db](https://linux-hardware.org/?probe=8009d927db) | Apr 05, 2023 |
| Lenovo        | ThinkPad Edge 0578RZ3       | Notebook    | [d37b6fa47b](https://linux-hardware.org/?probe=d37b6fa47b) | Apr 05, 2023 |
| Timi          | TM1703                      | Notebook    | [54b062157f](https://linux-hardware.org/?probe=54b062157f) | Apr 04, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [606eb36d59](https://linux-hardware.org/?probe=606eb36d59) | Apr 04, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c59398619e](https://linux-hardware.org/?probe=c59398619e) | Apr 03, 2023 |
| Gigabyte      | H61M-S2P                    | Desktop     | [6d808d8c4d](https://linux-hardware.org/?probe=6d808d8c4d) | Apr 03, 2023 |
| Dell          | Latitude 3410               | Notebook    | [0b29a27e88](https://linux-hardware.org/?probe=0b29a27e88) | Apr 03, 2023 |
| Dell          | Latitude 3410               | Notebook    | [9c8218ebd6](https://linux-hardware.org/?probe=9c8218ebd6) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [e60610d78a](https://linux-hardware.org/?probe=e60610d78a) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| Acer          | Aspire 4738Z                | Notebook    | [20e13078ef](https://linux-hardware.org/?probe=20e13078ef) | Apr 02, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [a959d79d84](https://linux-hardware.org/?probe=a959d79d84) | Apr 01, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [db53e1a333](https://linux-hardware.org/?probe=db53e1a333) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| Gigabyte      | P41T-D3                     | Desktop     | [2941019778](https://linux-hardware.org/?probe=2941019778) | Mar 29, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [6dac36ba2d](https://linux-hardware.org/?probe=6dac36ba2d) | Mar 28, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [0e8125dc1f](https://linux-hardware.org/?probe=0e8125dc1f) | Mar 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [4ac3cde372](https://linux-hardware.org/?probe=4ac3cde372) | Mar 27, 2023 |
| ASUSTek       | X555BA                      | Notebook    | [f7d51f3c2f](https://linux-hardware.org/?probe=f7d51f3c2f) | Mar 26, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [2c3c5a65a5](https://linux-hardware.org/?probe=2c3c5a65a5) | Mar 24, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [8e9a11831c](https://linux-hardware.org/?probe=8e9a11831c) | Mar 24, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [4b6ecef29b](https://linux-hardware.org/?probe=4b6ecef29b) | Mar 19, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [063ed79c8f](https://linux-hardware.org/?probe=063ed79c8f) | Mar 15, 2023 |
| Toshiba       | PORTEGE Z30t-C              | Notebook    | [7098d7537b](https://linux-hardware.org/?probe=7098d7537b) | Mar 15, 2023 |
| Lenovo        | G400s 20244                 | Notebook    | [fed6bb2c17](https://linux-hardware.org/?probe=fed6bb2c17) | Mar 13, 2023 |
| Dell          | Latitude E5440              | Notebook    | [fe81dc02b0](https://linux-hardware.org/?probe=fe81dc02b0) | Mar 13, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [cda777dad9](https://linux-hardware.org/?probe=cda777dad9) | Mar 13, 2023 |
| AXIOO         | Mybook 14E                  | Notebook    | [1b6c10d1d8](https://linux-hardware.org/?probe=1b6c10d1d8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2AX0... | Notebook    | [d6854dc15a](https://linux-hardware.org/?probe=d6854dc15a) | Mar 12, 2023 |
| GALAX         | B550M                       | Desktop     | [7b8e9c7506](https://linux-hardware.org/?probe=7b8e9c7506) | Mar 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [f4ad14a82a](https://linux-hardware.org/?probe=f4ad14a82a) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| ADVAN         | 1405                        | Notebook    | [7f96f0214f](https://linux-hardware.org/?probe=7f96f0214f) | Mar 08, 2023 |
| Lenovo        | G40-80 80E4                 | Notebook    | [01dae27177](https://linux-hardware.org/?probe=01dae27177) | Mar 07, 2023 |
| Dell          | G7 7588                     | Notebook    | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [2cdcded03e](https://linux-hardware.org/?probe=2cdcded03e) | Mar 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fa94a404fa](https://linux-hardware.org/?probe=fa94a404fa) | Mar 04, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [9857559bb5](https://linux-hardware.org/?probe=9857559bb5) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [096c600c1d](https://linux-hardware.org/?probe=096c600c1d) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [cd8d61c1b6](https://linux-hardware.org/?probe=cd8d61c1b6) | Mar 03, 2023 |
| Google        | Vorticon                    | Notebook    | [7e9f3425ab](https://linux-hardware.org/?probe=7e9f3425ab) | Mar 03, 2023 |
| Google        | Vorticon                    | Notebook    | [aaa620e932](https://linux-hardware.org/?probe=aaa620e932) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| ASUSTek       | E202SA                      | Notebook    | [bccde0c9a5](https://linux-hardware.org/?probe=bccde0c9a5) | Feb 28, 2023 |
| Foxconn       | G31MX Series                | Desktop     | [79ee8e5da3](https://linux-hardware.org/?probe=79ee8e5da3) | Feb 28, 2023 |
| Intel         | H61                         | Desktop     | [b61ef1ed65](https://linux-hardware.org/?probe=b61ef1ed65) | Feb 27, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| MSI           | Z97-G43 GAMING              | Desktop     | [b13f16cb2f](https://linux-hardware.org/?probe=b13f16cb2f) | Feb 26, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [302b65ed41](https://linux-hardware.org/?probe=302b65ed41) | Feb 25, 2023 |
| ASRock        | 970A-G                      | Desktop     | [bfdb227a9d](https://linux-hardware.org/?probe=bfdb227a9d) | Feb 24, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| ASRock        | A88M-G                      | Desktop     | [917526ad4d](https://linux-hardware.org/?probe=917526ad4d) | Feb 24, 2023 |
| Dell          | Inspiron 3476               | Notebook    | [58bff0319e](https://linux-hardware.org/?probe=58bff0319e) | Feb 24, 2023 |
| ASUSTek       | X441UA                      | Notebook    | [cd870fc3d3](https://linux-hardware.org/?probe=cd870fc3d3) | Feb 23, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [e9cfac6aa3](https://linux-hardware.org/?probe=e9cfac6aa3) | Feb 21, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [2953555c08](https://linux-hardware.org/?probe=2953555c08) | Feb 19, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [7197aacb00](https://linux-hardware.org/?probe=7197aacb00) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [b01624da44](https://linux-hardware.org/?probe=b01624da44) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f6e519323b](https://linux-hardware.org/?probe=f6e519323b) | Feb 15, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [ac80c33464](https://linux-hardware.org/?probe=ac80c33464) | Feb 14, 2023 |
| Acer          | Aspire 4732Z                | Notebook    | [abf9d41a29](https://linux-hardware.org/?probe=abf9d41a29) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [a8a5ef19de](https://linux-hardware.org/?probe=a8a5ef19de) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [f41fcff6ff](https://linux-hardware.org/?probe=f41fcff6ff) | Feb 13, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [9fd578a21d](https://linux-hardware.org/?probe=9fd578a21d) | Feb 13, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [608ce76690](https://linux-hardware.org/?probe=608ce76690) | Feb 13, 2023 |
| Toshiba       | Satellite L510              | Notebook    | [706759d61d](https://linux-hardware.org/?probe=706759d61d) | Feb 12, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [89365a25ee](https://linux-hardware.org/?probe=89365a25ee) | Feb 12, 2023 |
| AZW           | U59                         | Desktop     | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [f8f0fb1a21](https://linux-hardware.org/?probe=f8f0fb1a21) | Feb 11, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [6dffda8f11](https://linux-hardware.org/?probe=6dffda8f11) | Feb 10, 2023 |
| Intel         | H61                         | Desktop     | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| Dell          | Studio XPS 1340             | Notebook    | [4c96fdcf99](https://linux-hardware.org/?probe=4c96fdcf99) | Feb 09, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | Notebook    | [86297e5638](https://linux-hardware.org/?probe=86297e5638) | Feb 09, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [99f282862c](https://linux-hardware.org/?probe=99f282862c) | Feb 08, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [06ffbacba3](https://linux-hardware.org/?probe=06ffbacba3) | Feb 08, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [d60cd149fb](https://linux-hardware.org/?probe=d60cd149fb) | Feb 07, 2023 |
| ASUSTek       | P453UA                      | Notebook    | [476ff28577](https://linux-hardware.org/?probe=476ff28577) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [6fcc29607c](https://linux-hardware.org/?probe=6fcc29607c) | Feb 06, 2023 |
| Acer          | Aspire E5-476G              | Notebook    | [3b8e69dd3a](https://linux-hardware.org/?probe=3b8e69dd3a) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [cfc187a64c](https://linux-hardware.org/?probe=cfc187a64c) | Feb 05, 2023 |
| ECS           | H81H3-MV                    | Desktop     | [e60810d8e6](https://linux-hardware.org/?probe=e60810d8e6) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| HP            | 198E                        | Desktop     | [7dedbbef80](https://linux-hardware.org/?probe=7dedbbef80) | Feb 04, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [74bf135ed9](https://linux-hardware.org/?probe=74bf135ed9) | Jan 31, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [e0c723e305](https://linux-hardware.org/?probe=e0c723e305) | Jan 31, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [0c220851f3](https://linux-hardware.org/?probe=0c220851f3) | Jan 30, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [41c052436a](https://linux-hardware.org/?probe=41c052436a) | Jan 30, 2023 |
| MSI           | Modern 14 A10RB             | Notebook    | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [343025f50f](https://linux-hardware.org/?probe=343025f50f) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [dac4a44a62](https://linux-hardware.org/?probe=dac4a44a62) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [3b41afb262](https://linux-hardware.org/?probe=3b41afb262) | Jan 27, 2023 |
| HP            | 14                          | Notebook    | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [b41a540bb4](https://linux-hardware.org/?probe=b41a540bb4) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [acf75dbe88](https://linux-hardware.org/?probe=acf75dbe88) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [16277f992b](https://linux-hardware.org/?probe=16277f992b) | Jan 23, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [1fda4d1e4a](https://linux-hardware.org/?probe=1fda4d1e4a) | Jan 23, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [9cee6edc8e](https://linux-hardware.org/?probe=9cee6edc8e) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | Notebook    | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [855c9b8e45](https://linux-hardware.org/?probe=855c9b8e45) | Jan 18, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [e2486858b9](https://linux-hardware.org/?probe=e2486858b9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
| Lenovo        | 3102 NO DPK                 | Desktop     | [fa7b131a50](https://linux-hardware.org/?probe=fa7b131a50) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| Unknown       | Unknown                     | Phone       | [71abbc8c47](https://linux-hardware.org/?probe=71abbc8c47) | Jan 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7fefb8d34c](https://linux-hardware.org/?probe=7fefb8d34c) | Jan 15, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [58f2d0e1b4](https://linux-hardware.org/?probe=58f2d0e1b4) | Jan 12, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| ASUSTek       | X456URK                     | Notebook    | [09c6b0ed0a](https://linux-hardware.org/?probe=09c6b0ed0a) | Jan 12, 2023 |
| Intel         | Unknown                     | Desktop     | [6928fe7911](https://linux-hardware.org/?probe=6928fe7911) | Jan 11, 2023 |
| Acer          | AO756                       | Notebook    | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [5de089f4c0](https://linux-hardware.org/?probe=5de089f4c0) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [d47b3555d6](https://linux-hardware.org/?probe=d47b3555d6) | Jan 08, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [efaaf759cb](https://linux-hardware.org/?probe=efaaf759cb) | Jan 08, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [8056078760](https://linux-hardware.org/?probe=8056078760) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [b8e1b2ec8e](https://linux-hardware.org/?probe=b8e1b2ec8e) | Jan 07, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [7fa69ddddb](https://linux-hardware.org/?probe=7fa69ddddb) | Jan 07, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [b2dfc2437e](https://linux-hardware.org/?probe=b2dfc2437e) | Jan 06, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fd8b340292](https://linux-hardware.org/?probe=fd8b340292) | Jan 05, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [71c1ae09af](https://linux-hardware.org/?probe=71c1ae09af) | Jan 05, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [bc36d65732](https://linux-hardware.org/?probe=bc36d65732) | Jan 02, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [d99426e3d5](https://linux-hardware.org/?probe=d99426e3d5) | Jan 01, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [7e7df16316](https://linux-hardware.org/?probe=7e7df16316) | Jan 01, 2023 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [56e961b0ca](https://linux-hardware.org/?probe=56e961b0ca) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| Biostar       | TA970                       | Desktop     | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Acer          | TravelMate P214             | Notebook    | [436186d9e5](https://linux-hardware.org/?probe=436186d9e5) | Dec 30, 2022 |
| Lenovo        | ThinkPad X240 20AMS1J60B    | Notebook    | [1d8fcd4a75](https://linux-hardware.org/?probe=1d8fcd4a75) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b6413f9cf2](https://linux-hardware.org/?probe=b6413f9cf2) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [4ddf1fecb8](https://linux-hardware.org/?probe=4ddf1fecb8) | Dec 28, 2022 |
| ASUSTek       | A4110                       | All in one  | [fa417dc5c7](https://linux-hardware.org/?probe=fa417dc5c7) | Dec 28, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [a1e4dd02b2](https://linux-hardware.org/?probe=a1e4dd02b2) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [cedf39754e](https://linux-hardware.org/?probe=cedf39754e) | Dec 27, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [7b4b133211](https://linux-hardware.org/?probe=7b4b133211) | Dec 27, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [68963cb64b](https://linux-hardware.org/?probe=68963cb64b) | Dec 25, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [dd7fd03edd](https://linux-hardware.org/?probe=dd7fd03edd) | Dec 24, 2022 |
| MSI           | H61M-P20                    | Desktop     | [07b5fe983c](https://linux-hardware.org/?probe=07b5fe983c) | Dec 24, 2022 |
| MSI           | H61M-P20                    | Desktop     | [e1d50cc8f4](https://linux-hardware.org/?probe=e1d50cc8f4) | Dec 24, 2022 |
| Khadas        | VIM2                        | Soc         | [2ead7fb94b](https://linux-hardware.org/?probe=2ead7fb94b) | Dec 23, 2022 |
| Dell          | 0JJW8N A03                  | Desktop     | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| Langchao      | NF5110                      | Server      | [3578ca8ceb](https://linux-hardware.org/?probe=3578ca8ceb) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [36d833d9c2](https://linux-hardware.org/?probe=36d833d9c2) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [c065eec185](https://linux-hardware.org/?probe=c065eec185) | Dec 20, 2022 |
| ASUSTek       | X45C                        | Notebook    | [80377ba23f](https://linux-hardware.org/?probe=80377ba23f) | Dec 17, 2022 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [00437ce174](https://linux-hardware.org/?probe=00437ce174) | Dec 16, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [19e6ba206d](https://linux-hardware.org/?probe=19e6ba206d) | Dec 16, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [b9184a9ade](https://linux-hardware.org/?probe=b9184a9ade) | Dec 16, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [d09b578699](https://linux-hardware.org/?probe=d09b578699) | Dec 15, 2022 |
| Acer          | EX-215-52                   | Notebook    | [25201732ef](https://linux-hardware.org/?probe=25201732ef) | Dec 14, 2022 |
| Acer          | EX-215-52                   | Notebook    | [4cb72a8770](https://linux-hardware.org/?probe=4cb72a8770) | Dec 14, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [24fefa1408](https://linux-hardware.org/?probe=24fefa1408) | Dec 13, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [ed087084fb](https://linux-hardware.org/?probe=ed087084fb) | Dec 12, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [1a330e248d](https://linux-hardware.org/?probe=1a330e248d) | Dec 11, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| Dell          | 0VC7DK A03                  | Server      | [5e9bc6749d](https://linux-hardware.org/?probe=5e9bc6749d) | Dec 10, 2022 |
| Dell          | 0VC7DK A03                  | Server      | [f7958003c5](https://linux-hardware.org/?probe=f7958003c5) | Dec 10, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [5ca8db90bb](https://linux-hardware.org/?probe=5ca8db90bb) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5250630bdd](https://linux-hardware.org/?probe=5250630bdd) | Dec 09, 2022 |
| Acer          | Unknown                     | Notebook    | [b4eea49cf7](https://linux-hardware.org/?probe=b4eea49cf7) | Dec 09, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| Lenovo        | ThinkPad L530 24783R8       | Notebook    | [406c066d36](https://linux-hardware.org/?probe=406c066d36) | Dec 08, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [7bde3abe5d](https://linux-hardware.org/?probe=7bde3abe5d) | Dec 08, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [c2d30310e8](https://linux-hardware.org/?probe=c2d30310e8) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [a978cbc03b](https://linux-hardware.org/?probe=a978cbc03b) | Dec 06, 2022 |
| Acer          | One Z1401                   | Notebook    | [835ad73eff](https://linux-hardware.org/?probe=835ad73eff) | Dec 05, 2022 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [1cd6da46f3](https://linux-hardware.org/?probe=1cd6da46f3) | Dec 05, 2022 |
| Toshiba       | dynabook R63/P              | Notebook    | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [897f477f2d](https://linux-hardware.org/?probe=897f477f2d) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [9f512598e2](https://linux-hardware.org/?probe=9f512598e2) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [abe82b0f58](https://linux-hardware.org/?probe=abe82b0f58) | Dec 04, 2022 |
| Dell          | Latitude 3420               | Notebook    | [23e8b890d2](https://linux-hardware.org/?probe=23e8b890d2) | Dec 03, 2022 |
| Intel         | DH55PJ AAE93812-302         | Desktop     | [de105b99e4](https://linux-hardware.org/?probe=de105b99e4) | Dec 03, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [62b19626ce](https://linux-hardware.org/?probe=62b19626ce) | Dec 03, 2022 |
| Langchao      | NF5110                      | Server      | [ae8b7868da](https://linux-hardware.org/?probe=ae8b7868da) | Dec 02, 2022 |
| Lenovo        | B40-70 20392                | Notebook    | [a527c5b6e6](https://linux-hardware.org/?probe=a527c5b6e6) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b52b8b590b](https://linux-hardware.org/?probe=b52b8b590b) | Nov 30, 2022 |
| ASUSTek       | E203NAH                     | Notebook    | [3d091ea214](https://linux-hardware.org/?probe=3d091ea214) | Nov 30, 2022 |
| Dell          | Latitude E6440              | Notebook    | [0c3dd709dd](https://linux-hardware.org/?probe=0c3dd709dd) | Nov 30, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [dc35eb3d09](https://linux-hardware.org/?probe=dc35eb3d09) | Nov 30, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [4a49152177](https://linux-hardware.org/?probe=4a49152177) | Nov 29, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Laptop 14s-dq5xxx           | Notebook    | [9bb72cb3e8](https://linux-hardware.org/?probe=9bb72cb3e8) | Nov 28, 2022 |
| HP            | Laptop 14s-dq5xxx           | Notebook    | [e5164649e1](https://linux-hardware.org/?probe=e5164649e1) | Nov 27, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [74d291cf07](https://linux-hardware.org/?probe=74d291cf07) | Nov 24, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [4f0d293e99](https://linux-hardware.org/?probe=4f0d293e99) | Nov 24, 2022 |
| Dell          | Latitude E6230              | Notebook    | [28b93e0f7c](https://linux-hardware.org/?probe=28b93e0f7c) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | Notebook    | [5f72d40c0e](https://linux-hardware.org/?probe=5f72d40c0e) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | Notebook    | [e6acabebb2](https://linux-hardware.org/?probe=e6acabebb2) | Nov 21, 2022 |
| ASUSTek       | X45C                        | Notebook    | [02a232c4ef](https://linux-hardware.org/?probe=02a232c4ef) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASUSTek       | X455YA                      | Notebook    | [70267d756a](https://linux-hardware.org/?probe=70267d756a) | Nov 21, 2022 |
| Dell          | Latitude E6520              | Notebook    | [855dc4dadd](https://linux-hardware.org/?probe=855dc4dadd) | Nov 20, 2022 |
| MSI           | H510M PRO                   | Desktop     | [182b91241d](https://linux-hardware.org/?probe=182b91241d) | Nov 20, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [4f230635de](https://linux-hardware.org/?probe=4f230635de) | Nov 19, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | Notebook    | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [4c05f821c1](https://linux-hardware.org/?probe=4c05f821c1) | Nov 16, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [c1eca34f9c](https://linux-hardware.org/?probe=c1eca34f9c) | Nov 15, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [f67cd83e31](https://linux-hardware.org/?probe=f67cd83e31) | Nov 14, 2022 |
| Intel         | SandyBridge Platform        | Notebook    | [7019c7ba85](https://linux-hardware.org/?probe=7019c7ba85) | Nov 13, 2022 |
| Acer          | AO722                       | Notebook    | [5c51412f98](https://linux-hardware.org/?probe=5c51412f98) | Nov 12, 2022 |
| MSI           | 2A9C                        | Desktop     | [a531fd4d8e](https://linux-hardware.org/?probe=a531fd4d8e) | Nov 11, 2022 |
| MSI           | 2A9C                        | Desktop     | [599470c2f4](https://linux-hardware.org/?probe=599470c2f4) | Nov 11, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Lenovo        | ThinkPad P52s 20LB0026US    | Notebook    | [9443a4ceda](https://linux-hardware.org/?probe=9443a4ceda) | Nov 08, 2022 |
| Toshiba       | Satellite L15-B             | Notebook    | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| GPD           | G1619-04                    | Notebook    | [0c0542ac2e](https://linux-hardware.org/?probe=0c0542ac2e) | Nov 07, 2022 |
| Lenovo        | 7Y51CTO1WW                  | Server      | [6331807ba3](https://linux-hardware.org/?probe=6331807ba3) | Nov 07, 2022 |
| Unknown       | Unknown                     | Server      | [3facb2e9a7](https://linux-hardware.org/?probe=3facb2e9a7) | Nov 07, 2022 |
| Lenovo        | 7X04CTO1WW                  | Server      | [433a068c09](https://linux-hardware.org/?probe=433a068c09) | Nov 07, 2022 |
| Lenovo        | 7X08CTO1WW                  | Server      | [a3236bc9e8](https://linux-hardware.org/?probe=a3236bc9e8) | Nov 07, 2022 |
| Lenovo        | 7X04CTO1WW                  | Server      | [fab16fdb8d](https://linux-hardware.org/?probe=fab16fdb8d) | Nov 07, 2022 |
| Lenovo        | 7Y51CTO1WW                  | Server      | [ce01f7d898](https://linux-hardware.org/?probe=ce01f7d898) | Nov 07, 2022 |
| Lenovo        | 7X04CTO1WW                  | Server      | [8b79ae4568](https://linux-hardware.org/?probe=8b79ae4568) | Nov 07, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [c2e7afc800](https://linux-hardware.org/?probe=c2e7afc800) | Nov 07, 2022 |
| Intel         | P61A-D3                     | Desktop     | [5561c81cf4](https://linux-hardware.org/?probe=5561c81cf4) | Nov 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [98e419a04d](https://linux-hardware.org/?probe=98e419a04d) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Intel         | SandyBridge Platform        | Notebook    | [88c15d34e4](https://linux-hardware.org/?probe=88c15d34e4) | Nov 03, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [391048b46f](https://linux-hardware.org/?probe=391048b46f) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [49d6eb853f](https://linux-hardware.org/?probe=49d6eb853f) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [5de7efb403](https://linux-hardware.org/?probe=5de7efb403) | Nov 01, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [142e1c0695](https://linux-hardware.org/?probe=142e1c0695) | Oct 31, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [87f4a137dc](https://linux-hardware.org/?probe=87f4a137dc) | Oct 31, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| AXIOO         | Mybook 14H                  | Notebook    | [f8a7c19640](https://linux-hardware.org/?probe=f8a7c19640) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [0084d271e4](https://linux-hardware.org/?probe=0084d271e4) | Oct 28, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6d5c1da4b7](https://linux-hardware.org/?probe=6d5c1da4b7) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3b87b259c8](https://linux-hardware.org/?probe=3b87b259c8) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [e438393dca](https://linux-hardware.org/?probe=e438393dca) | Oct 19, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7891f1e18c](https://linux-hardware.org/?probe=7891f1e18c) | Oct 18, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| Lenovo        | IdeaPadFlex 3 11IGL05 82... | Convertible | [6e32a194d3](https://linux-hardware.org/?probe=6e32a194d3) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Dell          | Latitude 3490               | Notebook    | [a739a29b72](https://linux-hardware.org/?probe=a739a29b72) | Oct 16, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [babb66e9c9](https://linux-hardware.org/?probe=babb66e9c9) | Oct 16, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Intel         | SandyBridge Platform        | Notebook    | [3cc3d23297](https://linux-hardware.org/?probe=3cc3d23297) | Oct 14, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [814a533c23](https://linux-hardware.org/?probe=814a533c23) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46bc0c74c6](https://linux-hardware.org/?probe=46bc0c74c6) | Oct 11, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [a6eb228e33](https://linux-hardware.org/?probe=a6eb228e33) | Oct 10, 2022 |
| AXIOO         | Slimbook 13                 | Notebook    | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Acer          | Aspire 4736                 | Notebook    | [48b8af7bcf](https://linux-hardware.org/?probe=48b8af7bcf) | Oct 04, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [ce8e31b40d](https://linux-hardware.org/?probe=ce8e31b40d) | Oct 02, 2022 |
| HP            | Compaq 420                  | Notebook    | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [25e087916a](https://linux-hardware.org/?probe=25e087916a) | Oct 01, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [6f6704ea90](https://linux-hardware.org/?probe=6f6704ea90) | Oct 01, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [5e9a9b60e6](https://linux-hardware.org/?probe=5e9a9b60e6) | Oct 01, 2022 |
| ASUSTek       | X450EA                      | Notebook    | [345600d392](https://linux-hardware.org/?probe=345600d392) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [af7b986ff8](https://linux-hardware.org/?probe=af7b986ff8) | Sep 28, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [4a285e2052](https://linux-hardware.org/?probe=4a285e2052) | Sep 27, 2022 |
| Dell          | Latitude E6540              | Notebook    | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [3414420bc7](https://linux-hardware.org/?probe=3414420bc7) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | Notebook    | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | Notebook    | [ab84311fcc](https://linux-hardware.org/?probe=ab84311fcc) | Sep 24, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | Notebook    | [48a40a2f04](https://linux-hardware.org/?probe=48a40a2f04) | Sep 24, 2022 |
| HP            | 198E                        | Desktop     | [ffa9a79cc0](https://linux-hardware.org/?probe=ffa9a79cc0) | Sep 24, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [31b11c4544](https://linux-hardware.org/?probe=31b11c4544) | Sep 24, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [b879e569d1](https://linux-hardware.org/?probe=b879e569d1) | Sep 24, 2022 |
| ASUSTek       | X450EA                      | Notebook    | [79d9dab7dc](https://linux-hardware.org/?probe=79d9dab7dc) | Sep 24, 2022 |
| HP            | Pavilion 14                 | Notebook    | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [c658e4f48c](https://linux-hardware.org/?probe=c658e4f48c) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | Notebook    | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [64ff44a074](https://linux-hardware.org/?probe=64ff44a074) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [f24f78c803](https://linux-hardware.org/?probe=f24f78c803) | Sep 19, 2022 |
| ECS           | A55F2-M4                    | Desktop     | [335d28e72c](https://linux-hardware.org/?probe=335d28e72c) | Sep 19, 2022 |
| ASUSTek       | ET2013I                     | All in one  | [fddeb02707](https://linux-hardware.org/?probe=fddeb02707) | Sep 18, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [0c383a03ad](https://linux-hardware.org/?probe=0c383a03ad) | Sep 17, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0S10... | Notebook    | [0fd5868b54](https://linux-hardware.org/?probe=0fd5868b54) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| Lenovo        | ZHAOYANG E47                | Notebook    | [7f1fab5ff0](https://linux-hardware.org/?probe=7f1fab5ff0) | Sep 11, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [bfa4cc7ddc](https://linux-hardware.org/?probe=bfa4cc7ddc) | Sep 10, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [e1b3cac9d8](https://linux-hardware.org/?probe=e1b3cac9d8) | Sep 07, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [983d14d741](https://linux-hardware.org/?probe=983d14d741) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [c073d9fb9f](https://linux-hardware.org/?probe=c073d9fb9f) | Sep 03, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | Notebook    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| Acer          | Aspire V5-431               | Notebook    | [5ac694007d](https://linux-hardware.org/?probe=5ac694007d) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | ThinkPad L512 259756M       | Notebook    | [3990fcfeed](https://linux-hardware.org/?probe=3990fcfeed) | Aug 30, 2022 |
| Infinix       | INBOOK X2                   | Notebook    | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [75a6e1e9a1](https://linux-hardware.org/?probe=75a6e1e9a1) | Aug 29, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [8fac02d016](https://linux-hardware.org/?probe=8fac02d016) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [d281087322](https://linux-hardware.org/?probe=d281087322) | Aug 28, 2022 |
| Dell          | Latitude 7280               | Notebook    | [d214e30b1e](https://linux-hardware.org/?probe=d214e30b1e) | Aug 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| Intel         | H61                         | Desktop     | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | Notebook    | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | One Z1402                   | Notebook    | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [9ac20fda5a](https://linux-hardware.org/?probe=9ac20fda5a) | Aug 16, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [0b95f78b15](https://linux-hardware.org/?probe=0b95f78b15) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [903fda443e](https://linux-hardware.org/?probe=903fda443e) | Aug 14, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [a7d615e104](https://linux-hardware.org/?probe=a7d615e104) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| HP            | 14                          | Notebook    | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| ASUSTek       | K43E                        | Notebook    | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [7dbc1a26ca](https://linux-hardware.org/?probe=7dbc1a26ca) | Aug 07, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6dbb0a4eb9](https://linux-hardware.org/?probe=6dbb0a4eb9) | Aug 06, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [4de0aa7ccf](https://linux-hardware.org/?probe=4de0aa7ccf) | Aug 05, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [1c95e4f03d](https://linux-hardware.org/?probe=1c95e4f03d) | Aug 04, 2022 |
| ASUSTek       | K43E                        | Notebook    | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [9c842ec71c](https://linux-hardware.org/?probe=9c842ec71c) | Aug 03, 2022 |
| HP            | 431                         | Notebook    | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | Notebook    | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Lenovo        | ThinkPad X230 23245NJ       | Notebook    | [3c85e43b86](https://linux-hardware.org/?probe=3c85e43b86) | Aug 01, 2022 |
| HP            | 240 G8 Notebook PC          | Notebook    | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| Acer          | Z476                        | Notebook    | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| Dell          | Latitude E7250              | Notebook    | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| Sony          | VPCEA36FG                   | Notebook    | [6c742b6234](https://linux-hardware.org/?probe=6c742b6234) | Jul 30, 2022 |
| ASUSTek       | K43E                        | Notebook    | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| ASUSTek       | X455LF                      | Notebook    | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [3d23b4bbdc](https://linux-hardware.org/?probe=3d23b4bbdc) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [527b25a7f3](https://linux-hardware.org/?probe=527b25a7f3) | Jul 25, 2022 |
| Dell          | G3 3579                     | Notebook    | [96fab186c3](https://linux-hardware.org/?probe=96fab186c3) | Jul 24, 2022 |
| MSI           | 2A9C                        | Desktop     | [b0441c833d](https://linux-hardware.org/?probe=b0441c833d) | Jul 24, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | Notebook    | [a6e3ee128e](https://linux-hardware.org/?probe=a6e3ee128e) | Jul 20, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [1f7429b29d](https://linux-hardware.org/?probe=1f7429b29d) | Jul 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [54c99c7f2f](https://linux-hardware.org/?probe=54c99c7f2f) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [cf41c08ea5](https://linux-hardware.org/?probe=cf41c08ea5) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d651eb1f7d](https://linux-hardware.org/?probe=d651eb1f7d) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [b04b2741a0](https://linux-hardware.org/?probe=b04b2741a0) | Jul 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b00361cdbd](https://linux-hardware.org/?probe=b00361cdbd) | Jul 13, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [cde5f69fef](https://linux-hardware.org/?probe=cde5f69fef) | Jul 13, 2022 |
| Dell          | 0WCWFJ A00                  | All in one  | [89a6f4711c](https://linux-hardware.org/?probe=89a6f4711c) | Jul 11, 2022 |
| HP            | Pavilion g4                 | Notebook    | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Dell          | Latitude E6440              | Notebook    | [495237a0b0](https://linux-hardware.org/?probe=495237a0b0) | Jul 09, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [80e2fc79da](https://linux-hardware.org/?probe=80e2fc79da) | Jul 07, 2022 |
| Toshiba       | Satellite C640              | Notebook    | [cd8f69d739](https://linux-hardware.org/?probe=cd8f69d739) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Lenovo        | ThinkPad L412 0585E86       | Notebook    | [ad82717c98](https://linux-hardware.org/?probe=ad82717c98) | Jul 01, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [97d88d7e00](https://linux-hardware.org/?probe=97d88d7e00) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [3cec3cffbb](https://linux-hardware.org/?probe=3cec3cffbb) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [bac4b49e55](https://linux-hardware.org/?probe=bac4b49e55) | Jun 30, 2022 |
| Biostar       | A68N-5600E                  | Desktop     | [d5cfa78343](https://linux-hardware.org/?probe=d5cfa78343) | Jun 29, 2022 |
| Acer          | Aspire A314-35              | Notebook    | [dfdd48254c](https://linux-hardware.org/?probe=dfdd48254c) | Jun 29, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| HP            | Pavilion g4                 | Notebook    | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [30692c3fdb](https://linux-hardware.org/?probe=30692c3fdb) | Jun 23, 2022 |
| Fujitsu       | FMVS02003                   | Notebook    | [3536a9951f](https://linux-hardware.org/?probe=3536a9951f) | Jun 23, 2022 |
| Dell          | Precision M4500             | Notebook    | [e41b9f3386](https://linux-hardware.org/?probe=e41b9f3386) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [00a254b4ff](https://linux-hardware.org/?probe=00a254b4ff) | Jun 21, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [4ca3721cbb](https://linux-hardware.org/?probe=4ca3721cbb) | Jun 20, 2022 |
| MSI           | 2A9C                        | Desktop     | [73dd2172d3](https://linux-hardware.org/?probe=73dd2172d3) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [4d5fb8a789](https://linux-hardware.org/?probe=4d5fb8a789) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [9f7b97f22f](https://linux-hardware.org/?probe=9f7b97f22f) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| AXIOO         | Mybook 14E                  | Notebook    | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [b71d801e61](https://linux-hardware.org/?probe=b71d801e61) | Jun 18, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [a6cc4351be](https://linux-hardware.org/?probe=a6cc4351be) | Jun 17, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [fe4f649d9b](https://linux-hardware.org/?probe=fe4f649d9b) | Jun 17, 2022 |
| Wearnes       | T1550-A1                    | Desktop     | [b131cd7e0d](https://linux-hardware.org/?probe=b131cd7e0d) | Jun 16, 2022 |
| Wearnes       | T1550-A1                    | Desktop     | [002ebf8c70](https://linux-hardware.org/?probe=002ebf8c70) | Jun 15, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| HP            | 2B43                        | Desktop     | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| Acer          | AO756                       | Notebook    | [008fa33f13](https://linux-hardware.org/?probe=008fa33f13) | Jun 09, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [a74cd897c5](https://linux-hardware.org/?probe=a74cd897c5) | Jun 09, 2022 |
| MSI           | Prestige 14 A11SC           | Notebook    | [ea39fa65a1](https://linux-hardware.org/?probe=ea39fa65a1) | Jun 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [bdb3bbe37f](https://linux-hardware.org/?probe=bdb3bbe37f) | Jun 07, 2022 |
| Lenovo        | Z41-70 80K5                 | Notebook    | [3419d2fd18](https://linux-hardware.org/?probe=3419d2fd18) | Jun 06, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5e4d9a126e](https://linux-hardware.org/?probe=5e4d9a126e) | Jun 05, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| MSI           | H81I                        | Desktop     | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [1019de0d68](https://linux-hardware.org/?probe=1019de0d68) | Jun 01, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [2652284f1a](https://linux-hardware.org/?probe=2652284f1a) | May 31, 2022 |
| ASRock        | A88M-G                      | Desktop     | [9b82b09acc](https://linux-hardware.org/?probe=9b82b09acc) | May 30, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [a1dd5003f5](https://linux-hardware.org/?probe=a1dd5003f5) | May 30, 2022 |
| AXIOO         | NEON HNM MODEL              | Notebook    | [0fbd1cf4af](https://linux-hardware.org/?probe=0fbd1cf4af) | May 30, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| Lenovo        | G400 20235                  | Notebook    | [351b94ec15](https://linux-hardware.org/?probe=351b94ec15) | May 25, 2022 |
| HP            | 1000                        | Notebook    | [e83bc1e8fe](https://linux-hardware.org/?probe=e83bc1e8fe) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Biostar       | GF8200C M2+                 | Desktop     | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| ASUSTek       | K43U                        | Notebook    | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| MSI           | Modern 14 B11MO             | Notebook    | [c3b01c8c1b](https://linux-hardware.org/?probe=c3b01c8c1b) | May 20, 2022 |
| ASRock        | A88M-G                      | Desktop     | [e2baae7114](https://linux-hardware.org/?probe=e2baae7114) | May 19, 2022 |
| ASUSTek       | K43U                        | Notebook    | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [a1b9d7e608](https://linux-hardware.org/?probe=a1b9d7e608) | May 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [843a31b222](https://linux-hardware.org/?probe=843a31b222) | May 17, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [cfba770336](https://linux-hardware.org/?probe=cfba770336) | May 17, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [c19acfde6f](https://linux-hardware.org/?probe=c19acfde6f) | May 17, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [2ee65efb9e](https://linux-hardware.org/?probe=2ee65efb9e) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [e633129a51](https://linux-hardware.org/?probe=e633129a51) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [b207ce7566](https://linux-hardware.org/?probe=b207ce7566) | May 12, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [98b0999339](https://linux-hardware.org/?probe=98b0999339) | May 12, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [c4e0e740bb](https://linux-hardware.org/?probe=c4e0e740bb) | May 12, 2022 |
| Acer          | V1.24                       | Notebook    | [186531d4d8](https://linux-hardware.org/?probe=186531d4d8) | May 11, 2022 |
| Sony          | SVS13137PGB                 | Notebook    | [6dd2b49c52](https://linux-hardware.org/?probe=6dd2b49c52) | May 10, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [19345cd924](https://linux-hardware.org/?probe=19345cd924) | May 10, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [108b57a5a7](https://linux-hardware.org/?probe=108b57a5a7) | May 10, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [ec1fa8e360](https://linux-hardware.org/?probe=ec1fa8e360) | May 08, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [56cecf6472](https://linux-hardware.org/?probe=56cecf6472) | May 07, 2022 |
| MSI           | H55M-P33                    | Desktop     | [0f6b0dc134](https://linux-hardware.org/?probe=0f6b0dc134) | May 07, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [b4b52aad69](https://linux-hardware.org/?probe=b4b52aad69) | May 07, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [c0bfa1dddf](https://linux-hardware.org/?probe=c0bfa1dddf) | May 06, 2022 |
| Acer          | Aspire V5-431               | Notebook    | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [4dcc86a60e](https://linux-hardware.org/?probe=4dcc86a60e) | May 03, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [04dee023e6](https://linux-hardware.org/?probe=04dee023e6) | May 01, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [db2efb40d4](https://linux-hardware.org/?probe=db2efb40d4) | May 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [f93f8fcb35](https://linux-hardware.org/?probe=f93f8fcb35) | Apr 28, 2022 |
| Dell          | Latitude E6510              | Notebook    | [10d60e00c2](https://linux-hardware.org/?probe=10d60e00c2) | Apr 27, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [9f98b410f6](https://linux-hardware.org/?probe=9f98b410f6) | Apr 26, 2022 |
| Gigabyte      | M912                        | Notebook    | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | X450LCP                     | Notebook    | [a2ed4903be](https://linux-hardware.org/?probe=a2ed4903be) | Apr 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c90694a42c](https://linux-hardware.org/?probe=c90694a42c) | Apr 23, 2022 |
| Gigabyte      | AERO 15XV8                  | Notebook    | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [345734b3fd](https://linux-hardware.org/?probe=345734b3fd) | Apr 07, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [eb44050489](https://linux-hardware.org/?probe=eb44050489) | Apr 07, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| ASUSTek       | X455YA                      | Notebook    | [cf17e2bba2](https://linux-hardware.org/?probe=cf17e2bba2) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [ca7ee75e52](https://linux-hardware.org/?probe=ca7ee75e52) | Apr 01, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [c3651e4d3d](https://linux-hardware.org/?probe=c3651e4d3d) | Apr 01, 2022 |
| Dell          | Latitude E6230              | Notebook    | [c45161f6f3](https://linux-hardware.org/?probe=c45161f6f3) | Mar 31, 2022 |
| HP            | 3641h                       | Desktop     | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [84625838c2](https://linux-hardware.org/?probe=84625838c2) | Mar 30, 2022 |
| Lenovo        | 36F2 SDK0Q55754 WIN 3273... | All in one  | [64bc773e5b](https://linux-hardware.org/?probe=64bc773e5b) | Mar 30, 2022 |
| HP            | Pavilion 14                 | Notebook    | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Infinix       | INBook X1                   | Notebook    | [a06d137316](https://linux-hardware.org/?probe=a06d137316) | Mar 28, 2022 |
| Koloe         | X58                         | Desktop     | [8025987817](https://linux-hardware.org/?probe=8025987817) | Mar 27, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [46acaeb2db](https://linux-hardware.org/?probe=46acaeb2db) | Mar 27, 2022 |
| Dell          | Latitude E7240              | Notebook    | [02c34ca310](https://linux-hardware.org/?probe=02c34ca310) | Mar 25, 2022 |
| ASUSTek       | X455YA                      | Notebook    | [b0469d5342](https://linux-hardware.org/?probe=b0469d5342) | Mar 25, 2022 |
| Colorful T... | C.H110M-K D3 PLUS V20       | Desktop     | [191dfebc88](https://linux-hardware.org/?probe=191dfebc88) | Mar 23, 2022 |
| Sony          | VPCSB35FG                   | Notebook    | [79d0465072](https://linux-hardware.org/?probe=79d0465072) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [1b7f98b34d](https://linux-hardware.org/?probe=1b7f98b34d) | Mar 23, 2022 |
| ASUSTek       | X456UQK                     | Notebook    | [863693cc0a](https://linux-hardware.org/?probe=863693cc0a) | Mar 23, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [f0047d02ea](https://linux-hardware.org/?probe=f0047d02ea) | Mar 22, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [dd7543bdb3](https://linux-hardware.org/?probe=dd7543bdb3) | Mar 21, 2022 |
| Dell          | Inspiron 13-5368            | Notebook    | [d98411620e](https://linux-hardware.org/?probe=d98411620e) | Mar 21, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [08985cbe9e](https://linux-hardware.org/?probe=08985cbe9e) | Mar 21, 2022 |
| Intel         | H55                         | Desktop     | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [991793e09e](https://linux-hardware.org/?probe=991793e09e) | Mar 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [222cbe9b4e](https://linux-hardware.org/?probe=222cbe9b4e) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [b7cf53ebcc](https://linux-hardware.org/?probe=b7cf53ebcc) | Mar 15, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | Notebook                    | Notebook    | [6ae78b432d](https://linux-hardware.org/?probe=6ae78b432d) | Mar 12, 2022 |
| ZYREX COMP... | TACTICAL                    | Desktop     | [73a4735670](https://linux-hardware.org/?probe=73a4735670) | Mar 12, 2022 |
| Dell          | Latitude E7240              | Notebook    | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e39d0d9111](https://linux-hardware.org/?probe=e39d0d9111) | Mar 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [5e43e1dd7b](https://linux-hardware.org/?probe=5e43e1dd7b) | Mar 11, 2022 |
| Biostar       | N68S3B                      | Desktop     | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [ed4db5233e](https://linux-hardware.org/?probe=ed4db5233e) | Mar 10, 2022 |
| ASUSTek       | X450EA                      | Notebook    | [a7394d72a0](https://linux-hardware.org/?probe=a7394d72a0) | Mar 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [2f6380807c](https://linux-hardware.org/?probe=2f6380807c) | Mar 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [4702507c0f](https://linux-hardware.org/?probe=4702507c0f) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| HP            | Pavilion g4                 | Notebook    | [3ff8cf8ed0](https://linux-hardware.org/?probe=3ff8cf8ed0) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [dbf296e963](https://linux-hardware.org/?probe=dbf296e963) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [7b670726c4](https://linux-hardware.org/?probe=7b670726c4) | Mar 08, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| Sony          | VPCSB35FG                   | Notebook    | [b8a266ddc0](https://linux-hardware.org/?probe=b8a266ddc0) | Mar 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | Notebook    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| Toshiba       | PORTEGE R835                | Notebook    | [67e8021c81](https://linux-hardware.org/?probe=67e8021c81) | Mar 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e7d5945f3d](https://linux-hardware.org/?probe=e7d5945f3d) | Mar 05, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [28f40df81d](https://linux-hardware.org/?probe=28f40df81d) | Mar 04, 2022 |
| ASUSTek       | UL20A                       | Notebook    | [c4efddb6b4](https://linux-hardware.org/?probe=c4efddb6b4) | Mar 02, 2022 |
| Fujitsu       | Unknown                     | Notebook    | [bc81b988ce](https://linux-hardware.org/?probe=bc81b988ce) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [621999b245](https://linux-hardware.org/?probe=621999b245) | Feb 24, 2022 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [3b3c38ec7d](https://linux-hardware.org/?probe=3b3c38ec7d) | Feb 24, 2022 |
| Acer          | Aspire M3970                | Desktop     | [ba6546f689](https://linux-hardware.org/?probe=ba6546f689) | Feb 24, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [cdc3afd163](https://linux-hardware.org/?probe=cdc3afd163) | Feb 24, 2022 |
| Dell          | 0GM819                      | Desktop     | [28011d003e](https://linux-hardware.org/?probe=28011d003e) | Feb 23, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [5ba37db2b4](https://linux-hardware.org/?probe=5ba37db2b4) | Feb 23, 2022 |
| Dell          | Latitude E7240              | Notebook    | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [eba3609129](https://linux-hardware.org/?probe=eba3609129) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | Notebook    | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| Acer          | One Z1402                   | Notebook    | [8746e0e3e7](https://linux-hardware.org/?probe=8746e0e3e7) | Feb 18, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [1582806778](https://linux-hardware.org/?probe=1582806778) | Feb 17, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [b2efca795b](https://linux-hardware.org/?probe=b2efca795b) | Feb 17, 2022 |
| Intel         | H61                         | Desktop     | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [e3dfc424ca](https://linux-hardware.org/?probe=e3dfc424ca) | Feb 16, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [1e54431036](https://linux-hardware.org/?probe=1e54431036) | Feb 15, 2022 |
| Fujitsu       | FMVNA1SE                    | Notebook    | [e2cd0bdcb5](https://linux-hardware.org/?probe=e2cd0bdcb5) | Feb 14, 2022 |
| Khadas        | VIM2                        | Soc         | [c3e2b43e74](https://linux-hardware.org/?probe=c3e2b43e74) | Feb 13, 2022 |
| ECS           | A58F2P-M4                   | Desktop     | [bae5185ab0](https://linux-hardware.org/?probe=bae5185ab0) | Feb 13, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [3a6bb92957](https://linux-hardware.org/?probe=3a6bb92957) | Feb 13, 2022 |
| Toshiba       | Satellite C840              | Notebook    | [cb53c43003](https://linux-hardware.org/?probe=cb53c43003) | Feb 13, 2022 |
| Lenovo        | IdeaPad S205 Brazos         | Notebook    | [402bdafb5f](https://linux-hardware.org/?probe=402bdafb5f) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [46d98c991e](https://linux-hardware.org/?probe=46d98c991e) | Feb 12, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [5d4b14e3e0](https://linux-hardware.org/?probe=5d4b14e3e0) | Feb 12, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [eea0ec2b64](https://linux-hardware.org/?probe=eea0ec2b64) | Feb 12, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [276233dff5](https://linux-hardware.org/?probe=276233dff5) | Feb 11, 2022 |
| Biostar       | A68MHE                      | Desktop     | [d66f9ea911](https://linux-hardware.org/?probe=d66f9ea911) | Feb 10, 2022 |
| Biostar       | A68MHE                      | Desktop     | [edc710a49e](https://linux-hardware.org/?probe=edc710a49e) | Feb 10, 2022 |
| Toshiba       | Satellite C800D             | Notebook    | [5cdc03cbdf](https://linux-hardware.org/?probe=5cdc03cbdf) | Feb 10, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [54e246f496](https://linux-hardware.org/?probe=54e246f496) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [aa037a1c8c](https://linux-hardware.org/?probe=aa037a1c8c) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [0de3e1022e](https://linux-hardware.org/?probe=0de3e1022e) | Feb 09, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [5e0e5de165](https://linux-hardware.org/?probe=5e0e5de165) | Feb 07, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [aaceb070e8](https://linux-hardware.org/?probe=aaceb070e8) | Feb 07, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [324512f303](https://linux-hardware.org/?probe=324512f303) | Feb 06, 2022 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [f9eb52038d](https://linux-hardware.org/?probe=f9eb52038d) | Feb 01, 2022 |
| Dell          | Inspiron 5480               | Notebook    | [85796c8359](https://linux-hardware.org/?probe=85796c8359) | Jan 28, 2022 |
| Dell          | Inspiron 5480               | Notebook    | [59b6841322](https://linux-hardware.org/?probe=59b6841322) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [774625ff90](https://linux-hardware.org/?probe=774625ff90) | Jan 24, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [e7c5bda932](https://linux-hardware.org/?probe=e7c5bda932) | Jan 24, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [3f431523c1](https://linux-hardware.org/?probe=3f431523c1) | Jan 22, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [567c5725d5](https://linux-hardware.org/?probe=567c5725d5) | Jan 22, 2022 |
| Sony          | SVE14A15FGB                 | Notebook    | [c35af68d7b](https://linux-hardware.org/?probe=c35af68d7b) | Jan 21, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [a7c6bed4e1](https://linux-hardware.org/?probe=a7c6bed4e1) | Jan 21, 2022 |
| Sony          | SVD13213SGW                 | Notebook    | [ee9e63ab7c](https://linux-hardware.org/?probe=ee9e63ab7c) | Jan 21, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [e4791d09ec](https://linux-hardware.org/?probe=e4791d09ec) | Jan 20, 2022 |
| Lenovo        | IdeaPad 305-14IBD 80R1      | Notebook    | [f963f78bc6](https://linux-hardware.org/?probe=f963f78bc6) | Jan 20, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [ae605d8a23](https://linux-hardware.org/?probe=ae605d8a23) | Jan 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [c021e3bb40](https://linux-hardware.org/?probe=c021e3bb40) | Jan 18, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [bf81e9a289](https://linux-hardware.org/?probe=bf81e9a289) | Jan 17, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [6df479c161](https://linux-hardware.org/?probe=6df479c161) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | Notebook    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Lenovo        | G400s 20244                 | Notebook    | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| Dell          | Vostro 5581                 | Notebook    | [45f89f3b39](https://linux-hardware.org/?probe=45f89f3b39) | Jan 13, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [4822adcbc3](https://linux-hardware.org/?probe=4822adcbc3) | Jan 09, 2022 |
| MSI           | GL65 9SC                    | Notebook    | [24c204f7cf](https://linux-hardware.org/?probe=24c204f7cf) | Jan 09, 2022 |
| Dell          | Latitude E7250              | Notebook    | [e586dba516](https://linux-hardware.org/?probe=e586dba516) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | Notebook    | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [2268237364](https://linux-hardware.org/?probe=2268237364) | Jan 08, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [ea82b6b417](https://linux-hardware.org/?probe=ea82b6b417) | Jan 08, 2022 |
| ASUSTek       | N43SL                       | Notebook    | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | U310                        | Notebook    | [47b64f9b71](https://linux-hardware.org/?probe=47b64f9b71) | Jan 04, 2022 |
| ASUSTek       | TP300LD                     | Notebook    | [2048e4ff56](https://linux-hardware.org/?probe=2048e4ff56) | Jan 04, 2022 |
| Biostar       | H81MHV3                     | Desktop     | [897c4f4fa5](https://linux-hardware.org/?probe=897c4f4fa5) | Jan 03, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [954bd9f15e](https://linux-hardware.org/?probe=954bd9f15e) | Jan 03, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [5a0df8b1d8](https://linux-hardware.org/?probe=5a0df8b1d8) | Jan 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [af3d4f8c4d](https://linux-hardware.org/?probe=af3d4f8c4d) | Jan 02, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [1928762a58](https://linux-hardware.org/?probe=1928762a58) | Jan 02, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [ad8cdd464b](https://linux-hardware.org/?probe=ad8cdd464b) | Jan 01, 2022 |
| ASUSTek       | TP300LD                     | Notebook    | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [2956508483](https://linux-hardware.org/?probe=2956508483) | Dec 31, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [a9e50f6f42](https://linux-hardware.org/?probe=a9e50f6f42) | Dec 28, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| HP            | Pavilion 14                 | Notebook    | [b212043e80](https://linux-hardware.org/?probe=b212043e80) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Lenovo        | CRESCENTBAY No DPK          | All in one  | [b5cd12bc15](https://linux-hardware.org/?probe=b5cd12bc15) | Dec 24, 2021 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [25ca0533b3](https://linux-hardware.org/?probe=25ca0533b3) | Dec 24, 2021 |
| Fujitsu       | FMVNA7BEC                   | Notebook    | [5a7719cad2](https://linux-hardware.org/?probe=5a7719cad2) | Dec 23, 2021 |
| Acer          | Aspire E1-471G              | Notebook    | [93b181f3fd](https://linux-hardware.org/?probe=93b181f3fd) | Dec 21, 2021 |
| Dell          | Latitude E5400              | Notebook    | [ea58337ba8](https://linux-hardware.org/?probe=ea58337ba8) | Dec 20, 2021 |
| Toshiba       | Dakar10FW8                  | Notebook    | [937d3de436](https://linux-hardware.org/?probe=937d3de436) | Dec 19, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b8967e6235](https://linux-hardware.org/?probe=b8967e6235) | Dec 18, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b55aea9c38](https://linux-hardware.org/?probe=b55aea9c38) | Dec 13, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [f279fb7b6f](https://linux-hardware.org/?probe=f279fb7b6f) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [635ec3d5d2](https://linux-hardware.org/?probe=635ec3d5d2) | Dec 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [ee7ae7b860](https://linux-hardware.org/?probe=ee7ae7b860) | Dec 06, 2021 |
| ASUSTek       | UX360UAK                    | Convertible | [76fcef9590](https://linux-hardware.org/?probe=76fcef9590) | Dec 05, 2021 |
| Foxconn       | 17A0                        | Desktop     | [f3b593c1cf](https://linux-hardware.org/?probe=f3b593c1cf) | Dec 04, 2021 |
| ASUSTek       | X200MA                      | Notebook    | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | 700T                        | Notebook    | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| Lenovo        | CRESCENTBAY No DPK          | All in one  | [473e7afa6d](https://linux-hardware.org/?probe=473e7afa6d) | Dec 01, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [8fcb88c027](https://linux-hardware.org/?probe=8fcb88c027) | Nov 30, 2021 |
| Foxconn       | 17A0                        | Desktop     | [9683f8f23c](https://linux-hardware.org/?probe=9683f8f23c) | Nov 29, 2021 |
| Lenovo        | ThinkCentre M58p 6137BG5    | Desktop     | [f5f0997eca](https://linux-hardware.org/?probe=f5f0997eca) | Nov 28, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [faf9c22988](https://linux-hardware.org/?probe=faf9c22988) | Nov 26, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [8cffa892b2](https://linux-hardware.org/?probe=8cffa892b2) | Nov 26, 2021 |
| Acer          | Aspire 4732Z                | Notebook    | [7376dc0d58](https://linux-hardware.org/?probe=7376dc0d58) | Nov 25, 2021 |
| Acer          | Aspire 4732Z                | Notebook    | [d020b5f5c5](https://linux-hardware.org/?probe=d020b5f5c5) | Nov 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a87f01aa8a](https://linux-hardware.org/?probe=a87f01aa8a) | Nov 25, 2021 |
| HP            | EliteBook x360 830 G7 No... | Convertible | [4c596fa022](https://linux-hardware.org/?probe=4c596fa022) | Nov 24, 2021 |
| Acer          | Swift SF514-53T             | Notebook    | [09cc50e9eb](https://linux-hardware.org/?probe=09cc50e9eb) | Nov 23, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [34d8f7fdbb](https://linux-hardware.org/?probe=34d8f7fdbb) | Nov 23, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Indonesia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 165       | 11.43%  |
| Ubuntu 18.04                 | 105       | 7.27%   |
| Ubuntu 22.04                 | 77        | 5.33%   |
| OpenMandriva 4.3             | 60        | 4.16%   |
| Arch Rolling                 | 36        | 2.49%   |
| OpenMandriva 4.2             | 32        | 2.22%   |
| KDE neon 20.04               | 26        | 1.8%    |
| Pop!_OS 22.04                | 24        | 1.66%   |
| Fedora 38                    | 24        | 1.66%   |
| Zorin 15                     | 23        | 1.59%   |
| Arch                         | 22        | 1.52%   |
| Fedora 36                    | 21        | 1.45%   |
| ArcoLinux Rolling            | 21        | 1.45%   |
| Zorin 16                     | 19        | 1.32%   |
| Manjaro                      | 19        | 1.32%   |
| Elementary 6.1               | 19        | 1.32%   |
| Pop!_OS 20.04                | 18        | 1.25%   |
| OpenMandriva 23.03           | 17        | 1.18%   |
| Debian 11                    | 17        | 1.18%   |
| Ubuntu 21.10                 | 16        | 1.11%   |
| Linux Mint 21.1              | 16        | 1.11%   |
| Linux Mint 20.3              | 16        | 1.11%   |
| Fedora 35                    | 16        | 1.11%   |
| Ubuntu 19.10                 | 15        | 1.04%   |
| Fedora 37                    | 15        | 1.04%   |
| OpenMandriva 23.01           | 14        | 0.97%   |
| Linux Mint 19.3              | 14        | 0.97%   |
| Xubuntu 20.04                | 13        | 0.9%    |
| Debian 12                    | 13        | 0.9%    |
| Linux Mint 20                | 11        | 0.76%   |
| EndeavourOS Rolling          | 11        | 0.76%   |
| Debian 10                    | 11        | 0.76%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.69%   |
| OpenMandriva 23.08           | 10        | 0.69%   |
| Fedora 32                    | 10        | 0.69%   |
| Ubuntu 23.04                 | 9         | 0.62%   |
| Ubuntu 21.04                 | 9         | 0.62%   |
| Ubuntu 16.04                 | 9         | 0.62%   |
| Pop!_OS 21.04                | 9         | 0.62%   |
| Kubuntu 22.04                | 9         | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 410       | 29.88%  |
| OpenMandriva  | 139       | 10.13%  |
| Fedora        | 93        | 6.78%   |
| Linux Mint    | 81        | 5.9%    |
| Arch          | 58        | 4.23%   |
| Pop!_OS       | 57        | 4.15%   |
| Manjaro       | 50        | 3.64%   |
| Zorin         | 46        | 3.35%   |
| Debian        | 45        | 3.28%   |
| Elementary    | 40        | 2.92%   |
| KDE neon      | 34        | 2.48%   |
| Endless       | 33        | 2.41%   |
| Kali          | 30        | 2.19%   |
| Xubuntu       | 27        | 1.97%   |
| Kubuntu       | 27        | 1.97%   |
| ArcoLinux     | 22        | 1.6%    |
| Lubuntu       | 18        | 1.31%   |
| ROSA          | 15        | 1.09%   |
| openSUSE      | 13        | 0.95%   |
| EndeavourOS   | 11        | 0.8%    |
| Ubuntu MATE   | 10        | 0.73%   |
| Ubuntu Unity  | 9         | 0.66%   |
| LMDE          | 8         | 0.58%   |
| Clear Linux   | 8         | 0.58%   |
| Nobara        | 7         | 0.51%   |
| Parrot        | 6         | 0.44%   |
| MX            | 6         | 0.44%   |
| Gentoo        | 6         | 0.44%   |
| Deepin        | 5         | 0.36%   |
| CentOS        | 5         | 0.36%   |
| Android       | 5         | 0.36%   |
| SteamOS       | 4         | 0.29%   |
| Artix         | 4         | 0.29%   |
| Ubuntu Budgie | 3         | 0.22%   |
| Sparky        | 3         | 0.22%   |
| Solus         | 3         | 0.22%   |
| Xero          | 2         | 0.15%   |
| UbuntuDDE     | 2         | 0.15%   |
| Rocky Linux   | 2         | 0.15%   |
| RHEL          | 2         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 59        | 3.81%   |
| 5.10.14-desktop-1omv4002 | 29        | 1.87%   |
| 5.4.0-42-generic         | 28        | 1.81%   |
| 5.15.0-56-generic        | 22        | 1.42%   |
| 5.4.0-26-generic         | 18        | 1.16%   |
| 6.2.6-desktop-1omv2390   | 16        | 1.03%   |
| 5.4.0-52-generic         | 16        | 1.03%   |
| 5.4.0-58-generic         | 15        | 0.97%   |
| 6.1.1-desktop-1omv2290   | 12        | 0.78%   |
| 4.18.0-15-generic        | 12        | 0.78%   |
| 5.15.0-41-generic        | 11        | 0.71%   |
| 5.0.0-25-generic         | 11        | 0.71%   |
| 5.15.0-48-generic        | 10        | 0.65%   |
| 5.15.0-46-generic        | 10        | 0.65%   |
| 5.15.0-43-generic        | 10        | 0.65%   |
| 5.4.0-80-generic         | 9         | 0.58%   |
| 5.11.0-37-generic        | 9         | 0.58%   |
| 6.4.11-desktop-1omv2390  | 8         | 0.52%   |
| 5.4.0-54-generic         | 8         | 0.52%   |
| 5.3.0-46-generic         | 8         | 0.52%   |
| 5.3.0-40-generic         | 8         | 0.52%   |
| 5.19.0-46-generic        | 8         | 0.52%   |
| 5.15.0-58-generic        | 8         | 0.52%   |
| 5.15.0-47-generic        | 8         | 0.52%   |
| 5.8.0-48-generic         | 7         | 0.45%   |
| 5.8.0-14-generic         | 7         | 0.45%   |
| 5.19.0-35-generic        | 7         | 0.45%   |
| 5.15.0-52-generic        | 7         | 0.45%   |
| 5.11.0-43-generic        | 7         | 0.45%   |
| 5.11.0-40-generic        | 7         | 0.45%   |
| 5.11.0-27-generic        | 7         | 0.45%   |
| 6.2.0-26-generic         | 6         | 0.39%   |
| 5.4.0-33-generic         | 6         | 0.39%   |
| 5.11.0-7620-generic      | 6         | 0.39%   |
| 5.11.0-38-generic        | 6         | 0.39%   |
| 5.11.0-35-generic        | 6         | 0.39%   |
| 5.0.0-32-generic         | 6         | 0.39%   |
| 5.0.0-23-generic         | 6         | 0.39%   |
| 6.5.5-desktop-1omv2390   | 5         | 0.32%   |
| 6.4.6-76060406-generic   | 5         | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 209       | 14.01%  |
| 5.15.0  | 138       | 9.25%   |
| 5.11.0  | 74        | 4.96%   |
| 5.8.0   | 61        | 4.09%   |
| 5.16.7  | 61        | 4.09%   |
| 4.15.0  | 55        | 3.69%   |
| 5.13.0  | 53        | 3.55%   |
| 5.3.0   | 51        | 3.42%   |
| 5.0.0   | 44        | 2.95%   |
| 5.19.0  | 36        | 2.41%   |
| 5.10.0  | 32        | 2.14%   |
| 4.18.0  | 32        | 2.14%   |
| 5.10.14 | 30        | 2.01%   |
| 6.2.0   | 27        | 1.81%   |
| 6.1.0   | 24        | 1.61%   |
| 6.2.6   | 20        | 1.34%   |
| 6.1.1   | 18        | 1.21%   |
| 4.19.0  | 15        | 1.01%   |
| 6.5.5   | 14        | 0.94%   |
| 6.4.11  | 11        | 0.74%   |
| 5.14.0  | 10        | 0.67%   |
| 5.17.5  | 8         | 0.54%   |
| 6.4.6   | 7         | 0.47%   |
| 4.4.0   | 7         | 0.47%   |
| 6.5.3   | 6         | 0.4%    |
| 5.16.0  | 6         | 0.4%    |
| 6.3.5   | 5         | 0.34%   |
| 5.9.16  | 5         | 0.34%   |
| 5.16.12 | 5         | 0.34%   |
| 6.5.0   | 4         | 0.27%   |
| 6.4.8   | 4         | 0.27%   |
| 6.3.8   | 4         | 0.27%   |
| 6.2.9   | 4         | 0.27%   |
| 6.2.8   | 4         | 0.27%   |
| 6.0.9   | 4         | 0.27%   |
| 6.0.6   | 4         | 0.27%   |
| 6.0.12  | 4         | 0.27%   |
| 6.0.10  | 4         | 0.27%   |
| 6.0.0   | 4         | 0.27%   |
| 5.8.12  | 4         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 219       | 14.91%  |
| 5.15    | 166       | 11.3%   |
| 5.10    | 100       | 6.81%   |
| 5.16    | 83        | 5.65%   |
| 5.11    | 83        | 5.65%   |
| 5.8     | 76        | 5.17%   |
| 6.1     | 65        | 4.42%   |
| 6.2     | 64        | 4.36%   |
| 5.13    | 61        | 4.15%   |
| 5.3     | 55        | 3.74%   |
| 4.15    | 55        | 3.74%   |
| 5.19    | 51        | 3.47%   |
| 5.0     | 46        | 3.13%   |
| 6.4     | 39        | 2.65%   |
| 4.18    | 35        | 2.38%   |
| 6.5     | 34        | 2.31%   |
| 6.0     | 31        | 2.11%   |
| 5.14    | 26        | 1.77%   |
| 6.3     | 23        | 1.57%   |
| 5.17    | 22        | 1.5%    |
| 4.19    | 20        | 1.36%   |
| 5.18    | 19        | 1.29%   |
| 5.9     | 16        | 1.09%   |
| 5.12    | 12        | 0.82%   |
| 4.9     | 12        | 0.82%   |
| 5.7     | 10        | 0.68%   |
| 5.6     | 10        | 0.68%   |
| 4.4     | 9         | 0.61%   |
| 5.5     | 6         | 0.41%   |
| 5.2     | 3         | 0.2%    |
| 4.13    | 3         | 0.2%    |
| 4.14    | 2         | 0.14%   |
| 4.10    | 2         | 0.14%   |
| 4.1     | 2         | 0.14%   |
| 3.10    | 2         | 0.14%   |
| 6       | 1         | 0.07%   |
| 5.1     | 1         | 0.07%   |
| 5       | 1         | 0.07%   |
| 4.3     | 1         | 0.07%   |
| 4.17    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1284      | 96.91%  |
| i686    | 30        | 2.26%   |
| aarch64 | 5         | 0.38%   |
| armv8l  | 3         | 0.23%   |
| armv7l  | 3         | 0.23%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 578       | 41.98%  |
| KDE5              | 265       | 19.24%  |
| Unknown           | 147       | 10.68%  |
| XFCE              | 109       | 7.92%   |
| X-Cinnamon        | 73        | 5.3%    |
| Pantheon          | 38        | 2.76%   |
| MATE              | 28        | 2.03%   |
| LXQt              | 22        | 1.6%    |
| KDE               | 22        | 1.6%    |
| Cinnamon          | 16        | 1.16%   |
| Unity             | 9         | 0.65%   |
| Budgie            | 9         | 0.65%   |
| Deepin            | 8         | 0.58%   |
| i3                | 7         | 0.51%   |
| KDE4              | 5         | 0.36%   |
| bspwm             | 5         | 0.36%   |
| Hyprland          | 4         | 0.29%   |
| GNOME Flashback   | 4         | 0.29%   |
| DWM               | 4         | 0.29%   |
| sway              | 3         | 0.22%   |
| ICEWM             | 3         | 0.22%   |
| Cutefish          | 3         | 0.22%   |
| Yaru:ubuntu:GNOME | 2         | 0.15%   |
| xmonad            | 2         | 0.15%   |
| qtile             | 2         | 0.15%   |
| LXDE              | 2         | 0.15%   |
| Phosh:GNOME       | 1         | 0.07%   |
| Peux Gnome        | 1         | 0.07%   |
| openbox           | 1         | 0.07%   |
| Lubuntu           | 1         | 0.07%   |
| lightdm-xsession  | 1         | 0.07%   |
| awesomeminimal    | 1         | 0.07%   |
| awesome           | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 993       | 72.8%   |
| Wayland | 251       | 18.4%   |
| Unknown | 101       | 7.4%    |
| Tty     | 19        | 1.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 620       | 45.32%  |
| SDDM    | 249       | 18.2%   |
| GDM     | 176       | 12.87%  |
| LightDM | 142       | 10.38%  |
| GDM3    | 134       | 9.8%    |
| TDM     | 37        | 2.7%    |
| KDM     | 5         | 0.37%   |
| SLiM    | 3         | 0.22%   |
| Ly      | 1         | 0.07%   |
| LXDM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1076      | 80%     |
| Unknown | 124       | 9.22%   |
| id_ID   | 91        | 6.77%   |
| C       | 18        | 1.34%   |
| en_GB   | 16        | 1.19%   |
| en_AG   | 5         | 0.37%   |
| en_SG   | 3         | 0.22%   |
| en_AU   | 3         | 0.22%   |
| fr_FR   | 2         | 0.15%   |
| jv_ID   | 1         | 0.07%   |
| it_IT   | 1         | 0.07%   |
| en_IN   | 1         | 0.07%   |
| en_CA   | 1         | 0.07%   |
| de_DE   | 1         | 0.07%   |
| de_CH   | 1         | 0.07%   |
| Default | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 721       | 53.29%  |
| BIOS | 632       | 46.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1013      | 74.87%  |
| Btrfs   | 134       | 9.9%    |
| Overlay | 103       | 7.61%   |
| Unknown | 45        | 3.33%   |
| Tmpfs   | 23        | 1.7%    |
| Xfs     | 18        | 1.33%   |
| Zfs     | 6         | 0.44%   |
| Ext2    | 5         | 0.37%   |
| F2fs    | 4         | 0.3%    |
| Ext3    | 2         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 629       | 46.52%  |
| GPT     | 545       | 40.31%  |
| MBR     | 178       | 13.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1168      | 86.78%  |
| Yes       | 178       | 13.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 787       | 58.3%   |
| Yes       | 563       | 41.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 273       | 20.6%   |
| ASUSTek Computer                     | 251       | 18.94%  |
| Hewlett-Packard                      | 177       | 13.36%  |
| Acer                                 | 144       | 10.87%  |
| Dell                                 | 100       | 7.55%   |
| MSI                                  | 62        | 4.68%   |
| Gigabyte Technology                  | 51        | 3.85%   |
| ASRock                               | 40        | 3.02%   |
| Toshiba                              | 34        | 2.57%   |
| Intel                                | 24        | 1.81%   |
| Biostar                              | 18        | 1.36%   |
| ECS                                  | 17        | 1.28%   |
| Apple                                | 14        | 1.06%   |
| Unknown                              | 14        | 1.06%   |
| AXIOO                                | 12        | 0.91%   |
| Sony                                 | 10        | 0.75%   |
| Fujitsu                              | 9         | 0.68%   |
| Samsung Electronics                  | 6         | 0.45%   |
| Infinix                              | 5         | 0.38%   |
| HUAWEI                               | 4         | 0.3%    |
| AZW                                  | 4         | 0.3%    |
| Foxconn                              | 3         | 0.23%   |
| Clevo                                | 3         | 0.23%   |
| Valve                                | 2         | 0.15%   |
| Timi                                 | 2         | 0.15%   |
| Supermicro                           | 2         | 0.15%   |
| Raspberry Pi Foundation              | 2         | 0.15%   |
| Pegatron                             | 2         | 0.15%   |
| Panasonic                            | 2         | 0.15%   |
| OEM                                  | 2         | 0.15%   |
| LORD ELECTRONICS                     | 2         | 0.15%   |
| Langchao                             | 2         | 0.15%   |
| ZYREX COMPUTER SYSTEMS               | 1         | 0.08%   |
| ZOTAC                                | 1         | 0.08%   |
| Wearnes                              | 1         | 0.08%   |
| SPECTRUM UTAMA                       | 1         | 0.08%   |
| Sole                                 | 1         | 0.08%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.08%   |
| Rockchip                             | 1         | 0.08%   |
| realme                               | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 21        | 1.58%   |
| Lenovo IdeaPad 330-14AST 81D5           | 11        | 0.83%   |
| Lenovo G40-45 80E1                      | 11        | 0.83%   |
| HP Notebook                             | 11        | 0.83%   |
| HP Pavilion Aero Laptop 13-be0xxx       | 9         | 0.68%   |
| Acer Aspire 4752                        | 8         | 0.6%    |
| Lenovo IdeaPad S340-14API 81NB          | 6         | 0.45%   |
| Intel H61                               | 6         | 0.45%   |
| HP Laptop 14-bw0xx                      | 6         | 0.45%   |
| HP 14                                   | 6         | 0.45%   |
| Acer Aspire 4750                        | 6         | 0.45%   |
| Lenovo G400 20235                       | 5         | 0.38%   |
| HP Pavilion g4                          | 5         | 0.38%   |
| ASUS X455YA                             | 5         | 0.38%   |
| ASUS X455LF                             | 5         | 0.38%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 5         | 0.38%   |
| ASUS GL553VD                            | 5         | 0.38%   |
| ASUS All Series                         | 5         | 0.38%   |
| Apple MacBookPro12,1                    | 5         | 0.38%   |
| Acer Swift SF314-71                     | 5         | 0.38%   |
| Acer One Z1402                          | 5         | 0.38%   |
| Lenovo Yoga C640-13IML 81UE             | 4         | 0.3%    |
| Lenovo IdeaPad 320-14AST 80XU           | 4         | 0.3%    |
| Lenovo G40-30 80FY                      | 4         | 0.3%    |
| HP Pavilion 14                          | 4         | 0.3%    |
| HP Laptop 14-cm0xxx                     | 4         | 0.3%    |
| HP Laptop 14-bs0xx                      | 4         | 0.3%    |
| HP EliteBook 2570p                      | 4         | 0.3%    |
| HP 1000                                 | 4         | 0.3%    |
| Gigabyte H61M-DS2                       | 4         | 0.3%    |
| Dell OptiPlex 7010                      | 4         | 0.3%    |
| ASUS X456URK                            | 4         | 0.3%    |
| ASUS X453SA                             | 4         | 0.3%    |
| ASUS X442URR                            | 4         | 0.3%    |
| ASUS X200MA                             | 4         | 0.3%    |
| Acer Swift SFX14-41G                    | 4         | 0.3%    |
| Acer Swift SF314-56G                    | 4         | 0.3%    |
| Acer Aspire E5-476G                     | 4         | 0.3%    |
| Acer Aspire E5-475G                     | 4         | 0.3%    |
| MSI MS-7A37                             | 3         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 94        | 7.09%   |
| Acer Aspire        | 84        | 6.34%   |
| Lenovo ThinkPad    | 78        | 5.89%   |
| HP Laptop          | 39        | 2.94%   |
| ASUS VivoBook      | 37        | 2.79%   |
| HP Pavilion        | 36        | 2.72%   |
| Dell Latitude      | 35        | 2.64%   |
| Dell Inspiron      | 23        | 1.74%   |
| Toshiba Satellite  | 22        | 1.66%   |
| Acer Swift         | 21        | 1.58%   |
| Unknown            | 21        | 1.58%   |
| HP EliteBook       | 19        | 1.43%   |
| Dell OptiPlex      | 14        | 1.06%   |
| Lenovo Yoga        | 12        | 0.91%   |
| Dell Vostro        | 12        | 0.91%   |
| ASUS ROG           | 12        | 0.91%   |
| Lenovo ThinkCentre | 11        | 0.83%   |
| Lenovo G40-45      | 11        | 0.83%   |
| HP Notebook        | 11        | 0.83%   |
| Lenovo ThinkBook   | 9         | 0.68%   |
| HP ENVY            | 9         | 0.68%   |
| ASUS TUF           | 9         | 0.68%   |
| Acer Nitro         | 9         | 0.68%   |
| Toshiba PORTEGE    | 7         | 0.53%   |
| HP ProBook         | 7         | 0.53%   |
| ASUS PRIME         | 7         | 0.53%   |
| ASUS ASUS          | 7         | 0.53%   |
| MSI Modern         | 6         | 0.45%   |
| Lenovo ThinkSystem | 6         | 0.45%   |
| Lenovo IdeaPadFlex | 6         | 0.45%   |
| Intel H61          | 6         | 0.45%   |
| HP Compaq          | 6         | 0.45%   |
| HP 14              | 6         | 0.45%   |
| Acer One           | 6         | 0.45%   |
| Lenovo G400        | 5         | 0.38%   |
| Infinix INBOOK     | 5         | 0.38%   |
| HP ProLiant        | 5         | 0.38%   |
| Gigabyte H61M-DS2  | 5         | 0.38%   |
| AXIOO Mybook       | 5         | 0.38%   |
| ASUS X455YA        | 5         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 128       | 9.66%   |
| 2018    | 128       | 9.66%   |
| 2013    | 113       | 8.53%   |
| 2012    | 109       | 8.23%   |
| 2021    | 106       | 8%      |
| 2011    | 104       | 7.85%   |
| 2020    | 96        | 7.25%   |
| 2014    | 93        | 7.02%   |
| 2017    | 89        | 6.72%   |
| 2015    | 79        | 5.96%   |
| 2010    | 75        | 5.66%   |
| 2016    | 63        | 4.75%   |
| 2009    | 40        | 3.02%   |
| 2022    | 31        | 2.34%   |
| 2008    | 31        | 2.34%   |
| 2007    | 17        | 1.28%   |
| Unknown | 10        | 0.75%   |
| 2023    | 9         | 0.68%   |
| 2006    | 4         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 913       | 68.91%  |
| Desktop        | 316       | 23.85%  |
| Convertible    | 35        | 2.64%   |
| Server         | 21        | 1.58%   |
| All in one     | 14        | 1.06%   |
| Tablet         | 8         | 0.6%    |
| Mini pc        | 7         | 0.53%   |
| Phone          | 5         | 0.38%   |
| System on chip | 5         | 0.38%   |
| Other          | 1         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1235      | 92.37%  |
| Enabled  | 102       | 7.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1324      | 99.92%  |
| Yes  | 1         | 0.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 397       | 29.63%  |
| 3.01-4.0        | 343       | 25.6%   |
| 8.01-16.0       | 244       | 18.21%  |
| 16.01-24.0      | 173       | 12.91%  |
| 1.01-2.0        | 98        | 7.31%   |
| 32.01-64.0      | 40        | 2.99%   |
| 2.01-3.0        | 15        | 1.12%   |
| 24.01-32.0      | 11        | 0.82%   |
| 64.01-256.0     | 10        | 0.75%   |
| 0.51-1.0        | 8         | 0.6%    |
| More than 256.0 | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 522       | 35.7%   |
| 2.01-3.0   | 405       | 27.7%   |
| 4.01-8.0   | 196       | 13.41%  |
| 3.01-4.0   | 193       | 13.2%   |
| 0.51-1.0   | 96        | 6.57%   |
| 8.01-16.0  | 35        | 2.39%   |
| 0.01-0.5   | 9         | 0.62%   |
| 16.01-24.0 | 5         | 0.34%   |
| Unknown    | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 892       | 65.88%  |
| 2       | 361       | 26.66%  |
| 3       | 61        | 4.51%   |
| 4       | 21        | 1.55%   |
| 0       | 10        | 0.74%   |
| 5       | 5         | 0.37%   |
| 6       | 2         | 0.15%   |
| 15      | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 906       | 67.71%  |
| Yes       | 432       | 32.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1103      | 83.18%  |
| No        | 223       | 16.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1139      | 85.38%  |
| No        | 195       | 14.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 851       | 63.65%  |
| No        | 486       | 36.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Indonesia | 1325      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Jakarta         | 391       | 27.1%   |
| Surabaya        | 128       | 8.87%   |
| Bandung         | 106       | 7.35%   |
| Yogyakarta      | 59        | 4.09%   |
| Semarang        | 44        | 3.05%   |
| Bogor           | 44        | 3.05%   |
| Tangerang       | 38        | 2.63%   |
| Bekasi          | 38        | 2.63%   |
| Malang          | 33        | 2.29%   |
| South Tangerang | 31        | 2.15%   |
| Medan           | 31        | 2.15%   |
| Denpasar        | 28        | 1.94%   |
| Depok           | 21        | 1.46%   |
| Makassar        | 15        | 1.04%   |
| Banjarmasin     | 15        | 1.04%   |
| Sleman          | 14        | 0.97%   |
| Palembang       | 14        | 0.97%   |
| Balikpapan      | 12        | 0.83%   |
| Tasikmalaya     | 10        | 0.69%   |
| Samarinda       | 10        | 0.69%   |
| Surakarta       | 9         | 0.62%   |
| Gresik          | 9         | 0.62%   |
| Blitar          | 9         | 0.62%   |
| Batam           | 9         | 0.62%   |
| Banda Aceh      | 9         | 0.62%   |
| Pasuruan        | 8         | 0.55%   |
| Magelang        | 8         | 0.55%   |
| Mataram         | 7         | 0.49%   |
| Brebes          | 7         | 0.49%   |
| Pontianak       | 6         | 0.42%   |
| Kudus           | 6         | 0.42%   |
| Kediri          | 6         | 0.42%   |
| Jember          | 6         | 0.42%   |
| Cirebon         | 6         | 0.42%   |
| Sukabumi        | 5         | 0.35%   |
| Pekan Baru      | 5         | 0.35%   |
| Demak           | 5         | 0.35%   |
| Bandar Lampung  | 5         | 0.35%   |
| Tanjung Pinang  | 4         | 0.28%   |
| Purwokerto      | 4         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 337       | 453    | 19.04%  |
| WDC                   | 247       | 327    | 13.95%  |
| Samsung Electronics   | 162       | 217    | 9.15%   |
| Toshiba               | 149       | 164    | 8.42%   |
| HGST                  | 71        | 83     | 4.01%   |
| Hitachi               | 65        | 81     | 3.67%   |
| Sandisk               | 61        | 76     | 3.45%   |
| Unknown               | 59        | 76     | 3.33%   |
| Intel                 | 45        | 64     | 2.54%   |
| V-GeN                 | 44        | 47     | 2.49%   |
| Kingston              | 43        | 53     | 2.43%   |
| A-DATA Technology     | 38        | 47     | 2.15%   |
| SK hynix              | 35        | 41     | 1.98%   |
| MidasForce            | 33        | 37     | 1.86%   |
| Micron Technology     | 31        | 42     | 1.75%   |
| China                 | 24        | 26     | 1.36%   |
| Unknown               | 22        | 23     | 1.24%   |
| Apacer                | 18        | 20     | 1.02%   |
| Silicon Motion        | 16        | 17     | 0.9%    |
| JMicron Technology    | 14        | 15     | 0.79%   |
| VISIPRO               | 13        | 16     | 0.73%   |
| Patriot               | 12        | 22     | 0.68%   |
| Team                  | 11        | 14     | 0.62%   |
| Fujitsu               | 11        | 12     | 0.62%   |
| EYOTA                 | 10        | 13     | 0.56%   |
| Apple                 | 10        | 11     | 0.56%   |
| Crucial               | 8         | 10     | 0.45%   |
| Transcend             | 7         | 11     | 0.4%    |
| RX7                   | 7         | 8      | 0.4%    |
| ADATA Technology      | 7         | 14     | 0.4%    |
| Pioneer               | 6         | 6      | 0.34%   |
| XPG                   | 5         | 8      | 0.28%   |
| Wellcomm              | 5         | 5      | 0.28%   |
| Realtek Semiconductor | 5         | 5      | 0.28%   |
| Ramos Technology      | 5         | 12     | 0.28%   |
| Phison Electronics    | 5         | 6      | 0.28%   |
| KIOXIA                | 5         | 5      | 0.28%   |
| Hewlett-Packard       | 5         | 5      | 0.28%   |
| External              | 5         | 5      | 0.28%   |
| PNY                   | 4         | 5      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB    | 42        | 2.24%   |
| Seagate ST1000LM035-1RK172 1TB     | 42        | 2.24%   |
| Toshiba MQ01ABF050 500GB           | 28        | 1.49%   |
| Toshiba MQ04ABF100 1TB             | 23        | 1.23%   |
| Toshiba MQ01ABD100 1TB             | 22        | 1.17%   |
| Unknown                            | 22        | 1.17%   |
| Seagate ST3500312CS 500GB          | 21        | 1.12%   |
| HGST HTS545050A7E680 500GB         | 20        | 1.07%   |
| Seagate ST500DM002-1BD142 500GB    | 18        | 0.96%   |
| A-DATA SU650 120GB SSD             | 18        | 0.96%   |
| Hitachi HTS543232A7A384 320GB      | 13        | 0.69%   |
| MidasForce SSD 128GB               | 12        | 0.64%   |
| Seagate ST9500325AS 500GB          | 11        | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB     | 11        | 0.59%   |
| HGST HTS721010A9E630 1TB           | 11        | 0.59%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 10        | 0.53%   |
| Seagate ST9320325AS 320GB          | 10        | 0.53%   |
| Seagate ST500LT012-9WS142 500GB    | 10        | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 10        | 0.53%   |
| SanDisk NVMe SSD Drive 512GB       | 10        | 0.53%   |
| Samsung SSD 860 EVO 250GB          | 10        | 0.53%   |
| Samsung SSD 850 EVO 250GB          | 10        | 0.53%   |
| Hitachi HTS545050A7E380 500GB      | 10        | 0.53%   |
| HGST HTS725050A7E630 500GB         | 10        | 0.53%   |
| HGST HTS545050A7E380 500GB         | 10        | 0.53%   |
| Unknown MMC Card  64GB             | 9         | 0.48%   |
| Seagate ST3250318AS 250GB          | 9         | 0.48%   |
| Seagate ST1000LM049-2GH172 1TB     | 9         | 0.48%   |
| Intel SSDPEKNW512G8 512GB          | 9         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 8         | 0.43%   |
| WDC WD10SPZX-21Z10T0 1TB           | 8         | 0.43%   |
| Unknown MMC Card  128GB            | 8         | 0.43%   |
| MidasForce SSD 120GB               | 8         | 0.43%   |
| JMicron Generic 256GB              | 8         | 0.43%   |
| Apacer AS340 240GB SSD             | 8         | 0.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 7         | 0.37%   |
| Unknown SD/MMC/MS PRO 16GB         | 7         | 0.37%   |
| Unknown MMC Card  32GB             | 7         | 0.37%   |
| Seagate ST2000LM007-1R8174 2TB     | 7         | 0.37%   |
| Seagate ST1000LX015-1U7172 1TB     | 7         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 334       | 446    | 39.25%  |
| WDC                 | 194       | 256    | 22.8%   |
| Toshiba             | 131       | 144    | 15.39%  |
| HGST                | 71        | 83     | 8.34%   |
| Hitachi             | 65        | 81     | 7.64%   |
| Samsung Electronics | 13        | 13     | 1.53%   |
| Fujitsu             | 9         | 9      | 1.06%   |
| Unknown             | 8         | 8      | 0.94%   |
| External            | 5         | 5      | 0.59%   |
| Maxtor              | 4         | 4      | 0.47%   |
| Apple               | 4         | 4      | 0.47%   |
| Hewlett-Packard     | 3         | 3      | 0.35%   |
| Pioneer             | 2         | 2      | 0.24%   |
| Unknown             | 2         | 2      | 0.24%   |
| USB3.0              | 1         | 1      | 0.12%   |
| SYMTEC              | 1         | 1      | 0.12%   |
| JMicron Technology  | 1         | 1      | 0.12%   |
| HGST HTS            | 1         | 3      | 0.12%   |
| ExcelStor           | 1         | 1      | 0.12%   |
| CLOVER              | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 72        | 95     | 15.19%  |
| WDC                 | 35        | 44     | 7.38%   |
| SanDisk             | 32        | 44     | 6.75%   |
| MidasForce          | 32        | 36     | 6.75%   |
| V-GeN               | 30        | 33     | 6.33%   |
| Kingston            | 27        | 30     | 5.7%    |
| A-DATA Technology   | 27        | 34     | 5.7%    |
| China               | 24        | 26     | 5.06%   |
| Apacer              | 18        | 20     | 3.8%    |
| Patriot             | 12        | 22     | 2.53%   |
| Unknown             | 11        | 11     | 2.32%   |
| VISIPRO             | 10        | 13     | 2.11%   |
| Intel               | 10        | 14     | 2.11%   |
| Team                | 9         | 12     | 1.9%    |
| EYOTA               | 8         | 10     | 1.69%   |
| Toshiba             | 7         | 8      | 1.48%   |
| Crucial             | 7         | 9      | 1.48%   |
| Seagate             | 6         | 6      | 1.27%   |
| Wellcomm            | 5         | 5      | 1.05%   |
| Transcend           | 5         | 8      | 1.05%   |
| Ramos Technology    | 5         | 12     | 1.05%   |
| Micron Technology   | 5         | 7      | 1.05%   |
| Apple               | 5         | 5      | 1.05%   |
| RX7                 | 4         | 5      | 0.84%   |
| Pioneer             | 4         | 4      | 0.84%   |
| Unknown             | 3         | 4      | 0.63%   |
| SK hynix            | 3         | 4      | 0.63%   |
| OCZ                 | 3         | 3      | 0.63%   |
| LITEONIT            | 3         | 4      | 0.63%   |
| LITEON              | 3         | 4      | 0.63%   |
| Kingmax             | 3         | 3      | 0.63%   |
| GALAX               | 3         | 3      | 0.63%   |
| XSTAR               | 2         | 2      | 0.42%   |
| TO Exter            | 2         | 2      | 0.42%   |
| SPCC                | 2         | 2      | 0.42%   |
| Smart               | 2         | 2      | 0.42%   |
| PNY                 | 2         | 2      | 0.42%   |
| Netac               | 2         | 2      | 0.42%   |
| Memory              | 2         | 2      | 0.42%   |
| Lexar               | 2         | 2      | 0.42%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 767       | 1068   | 46.85%  |
| SSD     | 436       | 586    | 26.63%  |
| NVMe    | 336       | 450    | 20.53%  |
| Unknown | 51        | 58     | 3.12%   |
| MMC     | 47        | 64     | 2.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1033      | 1656   | 70.32%  |
| NVMe | 330       | 439    | 22.46%  |
| SAS  | 59        | 67     | 4.02%   |
| MMC  | 47        | 64     | 3.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 790       | 1148   | 67.58%  |
| 0.51-1.0   | 306       | 400    | 26.18%  |
| 1.01-2.0   | 56        | 84     | 4.79%   |
| 3.01-4.0   | 9         | 14     | 0.77%   |
| 2.01-3.0   | 5         | 5      | 0.43%   |
| 4.01-10.0  | 3         | 3      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 399       | 28.77%  |
| 251-500        | 339       | 24.44%  |
| 501-1000       | 155       | 11.18%  |
| 51-100         | 149       | 10.74%  |
| 1-20           | 100       | 7.21%   |
| 1001-2000      | 95        | 6.85%   |
| 21-50          | 83        | 5.98%   |
| Unknown        | 28        | 2.02%   |
| More than 3000 | 22        | 1.59%   |
| 2001-3000      | 17        | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 546       | 37.68%  |
| 21-50          | 265       | 18.29%  |
| 101-250        | 191       | 13.18%  |
| 51-100         | 179       | 12.35%  |
| 251-500        | 125       | 8.63%   |
| 501-1000       | 78        | 5.38%   |
| Unknown        | 28        | 1.93%   |
| 1001-2000      | 23        | 1.59%   |
| More than 3000 | 9         | 0.62%   |
| 2001-3000      | 5         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB       | 9         | 10     | 4.48%   |
| Seagate ST500DM002-1BD142 500GB  | 7         | 9      | 3.48%   |
| Seagate ST500LT012-9WS142 500GB  | 6         | 6      | 2.99%   |
| Seagate ST500LT012-1DG142 500GB  | 6         | 6      | 2.99%   |
| Seagate ST9500325AS 500GB        | 5         | 5      | 2.49%   |
| HGST HTS545050A7E380 500GB       | 4         | 5      | 1.99%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 3         | 3      | 1.49%   |
| Toshiba MQ01ABF050 500GB         | 3         | 3      | 1.49%   |
| Toshiba MQ01ABD032 320GB         | 3         | 3      | 1.49%   |
| Seagate ST1000LX015-1U7172 1TB   | 3         | 4      | 1.49%   |
| Seagate ST1000LM035-1RK172 1TB   | 3         | 3      | 1.49%   |
| Hitachi HTS545050A7E380 500GB    | 3         | 3      | 1.49%   |
| HGST HTS725050A7E630 500GB       | 3         | 3      | 1.49%   |
| WDC WD800JD-08LSA0 80GB          | 2         | 2      | 1%      |
| WDC WD3200BEKT-60V5T1 320GB      | 2         | 2      | 1%      |
| WDC WD3200AAKS-61L9A0 320GB      | 2         | 3      | 1%      |
| WDC WD10JPCX-24UE4T0 1TB         | 2         | 3      | 1%      |
| WDC WD10EZEX-08M2NA0 1TB         | 2         | 2      | 1%      |
| Toshiba MQ01ABD100 1TB           | 2         | 2      | 1%      |
| Toshiba MQ01ABD050 500GB         | 2         | 2      | 1%      |
| Toshiba MK5059GSXP 500GB         | 2         | 2      | 1%      |
| Toshiba MK3265GSX 320GB          | 2         | 3      | 1%      |
| Seagate ST9500420AS 500GB        | 2         | 2      | 1%      |
| Seagate ST9320325AS 320GB        | 2         | 2      | 1%      |
| Seagate ST9250410AS 250GB        | 2         | 2      | 1%      |
| Seagate ST1000DM003-1ER162 1TB   | 2         | 2      | 1%      |
| SanDisk SSD PLUS 120 GB          | 2         | 2      | 1%      |
| Hitachi HTS545050B9A300 500GB    | 2         | 2      | 1%      |
| Hitachi HTS545032B9A300 320GB    | 2         | 2      | 1%      |
| Hitachi HTS545016B9A300 160GB    | 2         | 2      | 1%      |
| Hitachi HTS543232A7A384 320GB    | 2         | 2      | 1%      |
| Unknown                          | 2         | 2      | 1%      |
| WellcommMaster 128GB SSD         | 1         | 1      | 0.5%    |
| Wellcomm Master 128GB SSD        | 1         | 1      | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 1      | 0.5%    |
| WDC WD7500BPVT-55HXZT4 752GB     | 1         | 1      | 0.5%    |
| WDC WD6400AADS-00M2B0 640GB      | 1         | 1      | 0.5%    |
| WDC WD5000LPVX-80V0TT0 500GB     | 1         | 1      | 0.5%    |
| WDC WD5000LPVT-22G33T0 500GB     | 1         | 1      | 0.5%    |
| WDC WD5000LPCX-22VHAT0 500GB     | 1         | 1      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 66     | 27.46%  |
| WDC                 | 40        | 47     | 20.73%  |
| Toshiba             | 24        | 26     | 12.44%  |
| Hitachi             | 20        | 20     | 10.36%  |
| HGST                | 20        | 23     | 10.36%  |
| Samsung Electronics | 5         | 6      | 2.59%   |
| SanDisk             | 4         | 4      | 2.07%   |
| Micron Technology   | 3         | 3      | 1.55%   |
| Kingston            | 2         | 2      | 1.04%   |
| China               | 2         | 2      | 1.04%   |
| A-DATA Technology   | 2         | 4      | 1.04%   |
| Unknown             | 2         | 2      | 1.04%   |
| WellcommMaster      | 1         | 1      | 0.52%   |
| Wellcomm            | 1         | 1      | 0.52%   |
| VISIPRO             | 1         | 3      | 0.52%   |
| ValueTech           | 1         | 1      | 0.52%   |
| T-FORCE             | 1         | 1      | 0.52%   |
| SK hynix            | 1         | 1      | 0.52%   |
| Silicon Motion      | 1         | 1      | 0.52%   |
| RX7                 | 1         | 1      | 0.52%   |
| Maxtor              | 1         | 1      | 0.52%   |
| KLEVV               | 1         | 1      | 0.52%   |
| Intel               | 1         | 1      | 0.52%   |
| EYOTA               | 1         | 1      | 0.52%   |
| Crucial             | 1         | 1      | 0.52%   |
| CLOVER              | 1         | 1      | 0.52%   |
| Apple               | 1         | 1      | 0.52%   |
| Apacer              | 1         | 2      | 0.52%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 66     | 32.52%  |
| WDC                 | 39        | 46     | 23.93%  |
| Toshiba             | 24        | 26     | 14.72%  |
| Hitachi             | 20        | 20     | 12.27%  |
| HGST                | 20        | 23     | 12.27%  |
| Samsung Electronics | 3         | 3      | 1.84%   |
| Maxtor              | 1         | 1      | 0.61%   |
| CLOVER              | 1         | 1      | 0.61%   |
| Apple               | 1         | 1      | 0.61%   |
| Unknown             | 1         | 1      | 0.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 151       | 188    | 83.89%  |
| SSD  | 25        | 31     | 13.89%  |
| NVMe | 4         | 5      | 2.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3250318AS 250GB         | 2         | 2      | 28.57%  |
| WDC WD5000BPVT-60HXZT1 500GB      | 1         | 1      | 14.29%  |
| Toshiba MK2575GSX 250GB           | 1         | 1      | 14.29%  |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 14.29%  |
| Hitachi HTS543232A7A384 320GB     | 1         | 1      | 14.29%  |
| A-DATA Technology SX8200PNP 256GB | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 2         | 2      | 28.57%  |
| Hitachi           | 2         | 2      | 28.57%  |
| WDC               | 1         | 1      | 14.29%  |
| Toshiba           | 1         | 1      | 14.29%  |
| A-DATA Technology | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 728       | 1182   | 50.45%  |
| Works    | 533       | 813    | 36.94%  |
| Malfunc  | 175       | 224    | 12.13%  |
| Failed   | 7         | 7      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 914       | 59.04%  |
| AMD                              | 273       | 17.64%  |
| Samsung Electronics              | 84        | 5.43%   |
| SanDisk                          | 50        | 3.23%   |
| SK hynix                         | 31        | 2%      |
| Micron Technology                | 26        | 1.68%   |
| Silicon Motion                   | 24        | 1.55%   |
| ADATA Technology                 | 22        | 1.42%   |
| Kingston Technology Company      | 20        | 1.29%   |
| Phison Electronics               | 15        | 0.97%   |
| Toshiba America Info Systems     | 9         | 0.58%   |
| ASMedia Technology               | 9         | 0.58%   |
| Realtek Semiconductor            | 7         | 0.45%   |
| KIOXIA                           | 7         | 0.45%   |
| JMicron Technology               | 7         | 0.45%   |
| Union Memory (Shenzhen)          | 6         | 0.39%   |
| Broadcom / LSI                   | 6         | 0.39%   |
| Nvidia                           | 5         | 0.32%   |
| VIA Technologies                 | 4         | 0.26%   |
| Silicon Integrated Systems [SiS] | 4         | 0.26%   |
| Hewlett-Packard                  | 4         | 0.26%   |
| Shenzhen Longsys Electronics     | 3         | 0.19%   |
| Micron/Crucial Technology        | 3         | 0.19%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.19%   |
| Marvell Technology Group         | 3         | 0.19%   |
| LSI Logic / Symbios Logic        | 2         | 0.13%   |
| Adaptec                          | 2         | 0.13%   |
| Solid State Storage Technology   | 1         | 0.06%   |
| O2 Micro                         | 1         | 0.06%   |
| Lenovo                           | 1         | 0.06%   |
| Biwin Storage Technology         | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 215       | 12.22%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 87        | 4.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 87        | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 53        | 3.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 49        | 2.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 48        | 2.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 47        | 2.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 41        | 2.33%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 37        | 2.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 35        | 1.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 34        | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 30        | 1.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 29        | 1.65%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 27        | 1.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 22        | 1.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 22        | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 22        | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 22        | 1.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 21        | 1.19%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 20        | 1.14%   |
| Intel SSD 660P Series                                                                   | 19        | 1.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 19        | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 19        | 1.08%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 18        | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 17        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 17        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 17        | 0.97%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 17        | 0.97%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 15        | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 15        | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 15        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 15        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 15        | 0.85%   |
| AMD FCH IDE Controller                                                                  | 13        | 0.74%   |
| AMD 500 Series Chipset SATA Controller                                                  | 13        | 0.74%   |
| Micron 2210 NVMe SSD [Cobain]                                                           | 12        | 0.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 12        | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 12        | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 12        | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 12        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1010      | 63.05%  |
| NVMe | 330       | 20.6%   |
| IDE  | 161       | 10.05%  |
| RAID | 96        | 5.99%   |
| SAS  | 4         | 0.25%   |
| SCSI | 1         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 983       | 74.19%  |
| AMD      | 331       | 24.98%  |
| ARM      | 7         | 0.53%   |
| QUALCOMM | 4         | 0.3%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.28%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 16        | 1.21%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 1.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 1.13%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 15        | 1.13%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 14        | 1.06%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 14        | 1.06%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 0.98%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 13        | 0.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 0.98%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 13        | 0.98%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 12        | 0.9%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 12        | 0.9%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 12        | 0.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.83%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 11        | 0.83%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 11        | 0.83%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 0.75%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 10        | 0.75%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 10        | 0.75%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 0.75%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 10        | 0.75%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 10        | 0.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 0.68%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 0.68%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 9         | 0.68%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 9         | 0.68%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.68%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 9         | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.6%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 8         | 0.6%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 8         | 0.6%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 8         | 0.6%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 8         | 0.6%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 8         | 0.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.53%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 7         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 306       | 23.06%  |
| Intel Core i3           | 178       | 13.41%  |
| Intel Core i7           | 160       | 12.06%  |
| Other                   | 102       | 7.69%   |
| Intel Celeron           | 90        | 6.78%   |
| AMD Ryzen 5             | 83        | 6.25%   |
| Intel Core 2 Duo        | 53        | 3.99%   |
| AMD Ryzen 3             | 39        | 2.94%   |
| Intel Pentium           | 31        | 2.34%   |
| AMD Ryzen 7             | 31        | 2.34%   |
| AMD A8                  | 26        | 1.96%   |
| Intel Xeon              | 25        | 1.88%   |
| Intel Atom              | 18        | 1.36%   |
| Intel Pentium Dual-Core | 15        | 1.13%   |
| AMD A4                  | 15        | 1.13%   |
| AMD A6                  | 13        | 0.98%   |
| Intel Core 2 Quad       | 10        | 0.75%   |
| AMD E1                  | 10        | 0.75%   |
| AMD FX                  | 9         | 0.68%   |
| AMD E                   | 9         | 0.68%   |
| AMD Athlon              | 8         | 0.6%    |
| Intel Genuine           | 7         | 0.53%   |
| AMD Ryzen 9             | 7         | 0.53%   |
| AMD E2                  | 7         | 0.53%   |
| AMD A10                 | 7         | 0.53%   |
| Intel Pentium Dual      | 6         | 0.45%   |
| AMD Athlon II X2        | 6         | 0.45%   |
| Intel Core 2            | 5         | 0.38%   |
| Intel Xeon Bronze       | 4         | 0.3%    |
| AMD Phenom II X6        | 4         | 0.3%    |
| AMD Athlon X4           | 4         | 0.3%    |
| QUALCOMM AArch64        | 3         | 0.23%   |
| Intel Pentium Silver    | 3         | 0.23%   |
| Intel Pentium Gold      | 3         | 0.23%   |
| AMD Ryzen 5 PRO         | 3         | 0.23%   |
| AMD Phenom II X4        | 3         | 0.23%   |
| AMD C-60                | 3         | 0.23%   |
| Intel Xeon Silver       | 2         | 0.15%   |
| Intel Pentium D         | 2         | 0.15%   |
| AMD Ryzen 3 PRO         | 2         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 735       | 55.39%  |
| 4       | 386       | 29.09%  |
| 6       | 111       | 8.36%   |
| 8       | 49        | 3.69%   |
| 1       | 15        | 1.13%   |
| 12      | 12        | 0.9%    |
| 10      | 11        | 0.83%   |
| 3       | 3         | 0.23%   |
| 14      | 2         | 0.15%   |
| 44      | 1         | 0.08%   |
| 16      | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1312      | 99.02%  |
| 2       | 10        | 0.75%   |
| 3       | 2         | 0.15%   |
| Unknown | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 862       | 65.06%  |
| 1       | 462       | 34.87%  |
| Unknown | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1296      | 97.81%  |
| Unknown        | 22        | 1.66%   |
| 32-bit         | 4         | 0.3%    |
| 64-bit         | 3         | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 314       | 22.75%  |
| 0x206a7    | 90        | 6.52%   |
| 0x306a9    | 80        | 5.8%    |
| 0x1067a    | 49        | 3.55%   |
| 0x306c3    | 44        | 3.19%   |
| 0x40651    | 42        | 3.04%   |
| 0x306d4    | 34        | 2.46%   |
| 0x806ec    | 32        | 2.32%   |
| 0x906ea    | 30        | 2.17%   |
| 0x806ea    | 30        | 2.17%   |
| 0x06006705 | 27        | 1.96%   |
| 0x806e9    | 26        | 1.88%   |
| 0x806c1    | 26        | 1.88%   |
| 0x406e3    | 26        | 1.88%   |
| 0x08108109 | 25        | 1.81%   |
| 0x20655    | 24        | 1.74%   |
| 0x0a50000c | 21        | 1.52%   |
| 0x906e9    | 19        | 1.38%   |
| 0x08108102 | 17        | 1.23%   |
| 0x806eb    | 16        | 1.16%   |
| 0x6fd      | 16        | 1.16%   |
| 0x20652    | 15        | 1.09%   |
| 0x07030105 | 15        | 1.09%   |
| 0x706e5    | 13        | 0.94%   |
| 0x30678    | 13        | 0.94%   |
| 0x08608103 | 13        | 0.94%   |
| 0x706a8    | 11        | 0.8%    |
| 0x506e3    | 11        | 0.8%    |
| 0x406c4    | 11        | 0.8%    |
| 0x0810100b | 11        | 0.8%    |
| 0x406c3    | 10        | 0.72%   |
| 0x08600104 | 10        | 0.72%   |
| 0x06001119 | 10        | 0.72%   |
| 0x10676    | 9         | 0.65%   |
| 0x906a3    | 7         | 0.51%   |
| 0x6fb      | 7         | 0.51%   |
| 0x08101007 | 7         | 0.51%   |
| 0x0700010f | 7         | 0.51%   |
| 0x05000119 | 7         | 0.51%   |
| 0x03000027 | 7         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 206       | 15.54%  |
| SandyBridge      | 116       | 8.75%   |
| IvyBridge        | 107       | 8.07%   |
| Haswell          | 104       | 7.84%   |
| Penryn           | 64        | 4.83%   |
| Westmere         | 56        | 4.22%   |
| Skylake          | 52        | 3.92%   |
| Zen+             | 50        | 3.77%   |
| Unknown          | 49        | 3.7%    |
| Excavator        | 48        | 3.62%   |
| Silvermont       | 47        | 3.54%   |
| Broadwell        | 45        | 3.39%   |
| Zen 3            | 34        | 2.56%   |
| Zen              | 34        | 2.56%   |
| TigerLake        | 34        | 2.56%   |
| Zen 2            | 31        | 2.34%   |
| Core             | 31        | 2.34%   |
| Puma             | 27        | 2.04%   |
| Goldmont plus    | 22        | 1.66%   |
| IceLake          | 21        | 1.58%   |
| Piledriver       | 19        | 1.43%   |
| Alderlake Hybrid | 18        | 1.36%   |
| CometLake        | 17        | 1.28%   |
| Bobcat           | 17        | 1.28%   |
| K10              | 14        | 1.06%   |
| Jaguar           | 10        | 0.75%   |
| Goldmont         | 9         | 0.68%   |
| Bonnell          | 9         | 0.68%   |
| Steamroller      | 8         | 0.6%    |
| K10 Llano        | 8         | 0.6%    |
| Nehalem          | 7         | 0.53%   |
| Tremont          | 4         | 0.3%    |
| K8 Hammer        | 3         | 0.23%   |
| P6               | 2         | 0.15%   |
| NetBurst         | 2         | 0.15%   |
| Bulldozer        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 848       | 52.54%  |
| AMD                              | 411       | 25.46%  |
| Nvidia                           | 331       | 20.51%  |
| Matrox Electronics Systems       | 14        | 0.87%   |
| ASPEED Technology                | 5         | 0.31%   |
| Silicon Integrated Systems [SiS] | 4         | 0.25%   |
| Silicon Motion                   | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 98        | 5.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 70        | 4.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 50        | 2.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 48        | 2.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 43        | 2.57%   |
| Intel HD Graphics 5500                                                                   | 36        | 2.15%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 36        | 2.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 35        | 2.09%   |
| Intel UHD Graphics 620                                                                   | 35        | 2.09%   |
| Intel HD Graphics 620                                                                    | 35        | 2.09%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 1.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 28        | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 1.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 1.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 25        | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23        | 1.37%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 23        | 1.37%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 22        | 1.31%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 21        | 1.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 21        | 1.25%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 21        | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 20        | 1.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 20        | 1.19%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 20        | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 19        | 1.13%   |
| AMD Lucienne                                                                             | 17        | 1.01%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.89%   |
| Intel HD Graphics 630                                                                    | 15        | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 14        | 0.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 0.84%   |
| Nvidia GT218 [GeForce 210]                                                               | 13        | 0.78%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 13        | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 0.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 13        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 0.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 12        | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 585       | 43.82%  |
| 1 x AMD                | 290       | 21.72%  |
| Intel + Nvidia         | 201       | 15.06%  |
| 1 x Nvidia             | 94        | 7.04%   |
| Intel + AMD            | 51        | 3.82%   |
| 2 x AMD                | 39        | 2.92%   |
| AMD + Nvidia           | 31        | 2.32%   |
| 1 x Matrox             | 14        | 1.05%   |
| Other                  | 12        | 0.9%    |
| 2 x Intel              | 5         | 0.37%   |
| 1 x SiS                | 4         | 0.3%    |
| 1 x ASPEED             | 4         | 0.3%    |
| 2 x Nvidia             | 2         | 0.15%   |
| 1 x Silicon Motion     | 1         | 0.07%   |
| Nvidia + ASPEED        | 1         | 0.07%   |
| 1 x Intel + 4 x Nvidia | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1137      | 84.54%  |
| Proprietary | 165       | 12.27%  |
| Unknown     | 43        | 3.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 797       | 58.39%  |
| 1.01-2.0   | 207       | 15.16%  |
| 0.01-0.5   | 166       | 12.16%  |
| 0.51-1.0   | 91        | 6.67%   |
| 3.01-4.0   | 64        | 4.69%   |
| 5.01-6.0   | 17        | 1.25%   |
| 7.01-8.0   | 15        | 1.1%    |
| 8.01-16.0  | 5         | 0.37%   |
| 2.01-3.0   | 3         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 221       | 16.65%  |
| Chimei Innolux          | 197       | 14.85%  |
| BOE                     | 165       | 12.43%  |
| LG Display              | 131       | 9.87%   |
| Samsung Electronics     | 122       | 9.19%   |
| Goldstar                | 113       | 8.52%   |
| Dell                    | 45        | 3.39%   |
| Lenovo                  | 37        | 2.79%   |
| Hewlett-Packard         | 23        | 1.73%   |
| AOC                     | 21        | 1.58%   |
| Acer                    | 19        | 1.43%   |
| Philips                 | 17        | 1.28%   |
| InfoVision              | 17        | 1.28%   |
| Sharp                   | 16        | 1.21%   |
| PANDA                   | 16        | 1.21%   |
| ViewSonic               | 15        | 1.13%   |
| Apple                   | 13        | 0.98%   |
| Chi Mei Optoelectronics | 11        | 0.83%   |
| BenQ                    | 10        | 0.75%   |
| Toshiba                 | 9         | 0.68%   |
| InnoLux Display         | 8         | 0.6%    |
| LG Electronics          | 7         | 0.53%   |
| Ancor Communications    | 6         | 0.45%   |
| LG Philips              | 5         | 0.38%   |
| Sony                    | 4         | 0.3%    |
| Panasonic               | 4         | 0.3%    |
| Mi                      | 4         | 0.3%    |
| KDC                     | 4         | 0.3%    |
| HKC                     | 4         | 0.3%    |
| HannStar                | 4         | 0.3%    |
| CPT                     | 4         | 0.3%    |
| Unknown                 | 3         | 0.23%   |
| Quanta Display          | 3         | 0.23%   |
| QCM                     | 3         | 0.23%   |
| JRY                     | 3         | 0.23%   |
| ASUSTek Computer        | 3         | 0.23%   |
| Valve                   | 2         | 0.15%   |
| TMX                     | 2         | 0.15%   |
| SPC                     | 2         | 0.15%   |
| Seiko/Epson             | 2         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 20        | 1.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 18        | 1.34%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch      | 17        | 1.26%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 17        | 1.26%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 16        | 1.19%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 15        | 1.12%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 14        | 1.04%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 12        | 0.89%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 12        | 0.89%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 11        | 0.82%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                 | 11        | 0.82%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch        | 11        | 0.82%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 11        | 0.82%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 10        | 0.74%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch        | 10        | 0.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 9         | 0.67%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 9         | 0.67%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                 | 9         | 0.67%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 9         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 8         | 0.6%    |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 7         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 7         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch      | 7         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch      | 7         | 0.52%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 7         | 0.52%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch        | 7         | 0.52%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 6         | 0.45%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch          | 6         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch      | 6         | 0.45%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 6         | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 6         | 0.45%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 5         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch | 5         | 0.37%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch          | 5         | 0.37%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch     | 5         | 0.37%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                | 5         | 0.37%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch            | 4         | 0.3%    |
| Toshiba TV TSB010F 1920x1080 882x498mm 39.9-inch                     | 4         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 601       | 46.84%  |
| 1920x1080 (FHD)    | 438       | 34.14%  |
| 3840x2160 (4K)     | 37        | 2.88%   |
| 1440x900 (WXGA+)   | 32        | 2.49%   |
| 1600x900 (HD+)     | 30        | 2.34%   |
| 1280x800 (WXGA)    | 25        | 1.95%   |
| 2560x1440 (QHD)    | 19        | 1.48%   |
| 1360x768           | 16        | 1.25%   |
| 1920x1200 (WUXGA)  | 13        | 1.01%   |
| 2560x1600          | 10        | 0.78%   |
| 2560x1080          | 8         | 0.62%   |
| 1280x1024 (SXGA)   | 8         | 0.62%   |
| 2880x1800          | 7         | 0.55%   |
| 3440x1440          | 5         | 0.39%   |
| 1024x768 (XGA)     | 4         | 0.31%   |
| 1024x600           | 4         | 0.31%   |
| 2800x1752          | 3         | 0.23%   |
| Unknown            | 3         | 0.23%   |
| 800x1280           | 2         | 0.16%   |
| 3840x2400          | 2         | 0.16%   |
| 3840x1080          | 2         | 0.16%   |
| 1680x1050 (WSXGA+) | 2         | 0.16%   |
| 1280x720 (HD)      | 2         | 0.16%   |
| 640x480            | 1         | 0.08%   |
| 5760x2160          | 1         | 0.08%   |
| 3200x1800 (QHD+)   | 1         | 0.08%   |
| 2966x900           | 1         | 0.08%   |
| 2736x1824          | 1         | 0.08%   |
| 2240x1400          | 1         | 0.08%   |
| 2160x1440          | 1         | 0.08%   |
| 1920x1280          | 1         | 0.08%   |
| 1280x960           | 1         | 0.08%   |
| 1152x864           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 312       | 23.55%  |
| 14      | 295       | 22.26%  |
| 15      | 221       | 16.68%  |
| 18      | 86        | 6.49%   |
| 21      | 70        | 5.28%   |
| 23      | 66        | 4.98%   |
| 12      | 45        | 3.4%    |
| 11      | 36        | 2.72%   |
| 24      | 31        | 2.34%   |
| 19      | 31        | 2.34%   |
| Unknown | 25        | 1.89%   |
| 27      | 19        | 1.43%   |
| 17      | 15        | 1.13%   |
| 34      | 11        | 0.83%   |
| 40      | 9         | 0.68%   |
| 31      | 7         | 0.53%   |
| 16      | 7         | 0.53%   |
| 48      | 4         | 0.3%    |
| 20      | 4         | 0.3%    |
| 10      | 4         | 0.3%    |
| 67      | 3         | 0.23%   |
| 7       | 3         | 0.23%   |
| 84      | 2         | 0.15%   |
| 72      | 2         | 0.15%   |
| 60      | 2         | 0.15%   |
| 52      | 2         | 0.15%   |
| 37      | 2         | 0.15%   |
| 22      | 2         | 0.15%   |
| 65      | 1         | 0.08%   |
| 57      | 1         | 0.08%   |
| 54      | 1         | 0.08%   |
| 42      | 1         | 0.08%   |
| 39      | 1         | 0.08%   |
| 36      | 1         | 0.08%   |
| 35      | 1         | 0.08%   |
| 26      | 1         | 0.08%   |
| 9       | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 750       | 57.21%  |
| 401-500     | 184       | 14.04%  |
| 201-300     | 157       | 11.98%  |
| 501-600     | 112       | 8.54%   |
| 351-400     | 26        | 1.98%   |
| Unknown     | 25        | 1.91%   |
| 701-800     | 16        | 1.22%   |
| 801-900     | 13        | 0.99%   |
| 601-700     | 10        | 0.76%   |
| 1001-1500   | 10        | 0.76%   |
| 1501-2000   | 4         | 0.31%   |
| 1-100       | 2         | 0.15%   |
| 101-200     | 1         | 0.08%   |
| 901-1000    | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1073      | 87.59%  |
| 16/10   | 91        | 7.43%   |
| Unknown | 24        | 1.96%   |
| 21/9    | 12        | 0.98%   |
| 5/4     | 7         | 0.57%   |
| 4/3     | 7         | 0.57%   |
| 3/2     | 5         | 0.41%   |
| 0.45    | 3         | 0.24%   |
| 0.67    | 2         | 0.16%   |
| 0.56    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 543       | 41.07%  |
| 101-110        | 215       | 16.26%  |
| 201-250        | 144       | 10.89%  |
| 141-150        | 87        | 6.58%   |
| 71-80          | 59        | 4.46%   |
| 151-200        | 52        | 3.93%   |
| 61-70          | 44        | 3.33%   |
| 51-60          | 36        | 2.72%   |
| Unknown        | 25        | 1.89%   |
| 301-350        | 20        | 1.51%   |
| 351-500        | 19        | 1.44%   |
| More than 1000 | 18        | 1.36%   |
| 501-1000       | 14        | 1.06%   |
| 121-130        | 9         | 0.68%   |
| 91-100         | 9         | 0.68%   |
| 251-300        | 8         | 0.61%   |
| 111-120        | 7         | 0.53%   |
| 41-50          | 5         | 0.38%   |
| 131-140        | 5         | 0.38%   |
| 1-40           | 3         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 541       | 41.3%   |
| 121-160       | 346       | 26.41%  |
| 51-100        | 291       | 22.21%  |
| 161-240       | 68        | 5.19%   |
| Unknown       | 25        | 1.91%   |
| 1-50          | 20        | 1.53%   |
| More than 240 | 19        | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1152      | 85.21%  |
| 2     | 128       | 9.47%   |
| 0     | 69        | 5.1%    |
| 3     | 3         | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 825       | 39.66%  |
| Intel                             | 462       | 22.21%  |
| Qualcomm Atheros                  | 356       | 17.12%  |
| Broadcom                          | 121       | 5.82%   |
| Ralink Technology                 | 45        | 2.16%   |
| MediaTek                          | 38        | 1.83%   |
| TP-Link                           | 35        | 1.68%   |
| Xiaomi                            | 27        | 1.3%    |
| Samsung Electronics               | 22        | 1.06%   |
| Qualcomm Atheros Communications   | 17        | 0.82%   |
| Broadcom Limited                  | 17        | 0.82%   |
| Ralink                            | 15        | 0.72%   |
| Marvell Technology Group          | 13        | 0.63%   |
| OPPO Electronics                  | 11        | 0.53%   |
| ASIX Electronics                  | 7         | 0.34%   |
| Qualcomm                          | 6         | 0.29%   |
| JMicron Technology                | 6         | 0.29%   |
| IBM                               | 6         | 0.29%   |
| Huawei Technologies               | 5         | 0.24%   |
| Nvidia                            | 4         | 0.19%   |
| Ericsson Business Mobile Networks | 4         | 0.19%   |
| D-Link System                     | 4         | 0.19%   |
| D-Link                            | 4         | 0.19%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.14%   |
| ICS Advent                        | 3         | 0.14%   |
| Attansic Technology               | 3         | 0.14%   |
| AboCom Systems                    | 3         | 0.14%   |
| Sierra Wireless                   | 2         | 0.1%    |
| Lenovo                            | 2         | 0.1%    |
| HMD Global                        | 2         | 0.1%    |
| Hewlett-Packard                   | 2         | 0.1%    |
| ASUSTek Computer                  | 2         | 0.1%    |
| vivo                              | 1         | 0.05%   |
| VIA Technologies                  | 1         | 0.05%   |
| QinHeng Electronics               | 1         | 0.05%   |
| Microchip Technology              | 1         | 0.05%   |
| HTC (High Tech Computer)          | 1         | 0.05%   |
| Foxconn / Hon Hai                 | 1         | 0.05%   |
| Fibocom                           | 1         | 0.05%   |
| Edimax Technology                 | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 535       | 21.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 155       | 6.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 85        | 3.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 75        | 3.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 58        | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 45        | 1.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 40        | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 36        | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 33        | 1.35%   |
| Intel Wireless 8265 / 8275                                        | 33        | 1.35%   |
| Ralink MT7601U Wireless Adapter                                   | 31        | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 30        | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 29        | 1.19%   |
| Intel Wireless 7265                                               | 28        | 1.15%   |
| Intel Wi-Fi 6 AX200                                               | 26        | 1.07%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 25        | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 25        | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 24        | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 23        | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 23        | 0.94%   |
| Intel Wi-Fi 6 AX201                                               | 22        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 22        | 0.9%    |
| Intel Wireless 7260                                               | 21        | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20        | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 20        | 0.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 0.82%   |
| Broadcom BCM43142 802.11b/g/n                                     | 20        | 0.82%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 19        | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                   | 17        | 0.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 17        | 0.7%    |
| Intel Wireless 8260                                               | 17        | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 15        | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 15        | 0.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 13        | 0.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 13        | 0.53%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 0.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 12        | 0.49%   |
| Intel Wireless 3165                                               | 12        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 374       | 31.17%  |
| Qualcomm Atheros                  | 306       | 25.5%   |
| Realtek Semiconductor             | 273       | 22.75%  |
| Broadcom                          | 82        | 6.83%   |
| Ralink Technology                 | 45        | 3.75%   |
| TP-Link                           | 31        | 2.58%   |
| MediaTek                          | 29        | 2.42%   |
| Qualcomm Atheros Communications   | 17        | 1.42%   |
| Ralink                            | 15        | 1.25%   |
| Broadcom Limited                  | 13        | 1.08%   |
| D-Link                            | 4         | 0.33%   |
| AboCom Systems                    | 3         | 0.25%   |
| Sierra Wireless                   | 2         | 0.17%   |
| D-Link System                     | 2         | 0.17%   |
| Fibocom                           | 1         | 0.08%   |
| Ericsson Business Mobile Networks | 1         | 0.08%   |
| Edimax Technology                 | 1         | 0.08%   |
| ASUSTek Computer                  | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 85        | 7.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 75        | 6.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 58        | 4.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 40        | 3.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 36        | 2.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 33        | 2.73%   |
| Intel Wireless 8265 / 8275                                     | 33        | 2.73%   |
| Ralink MT7601U Wireless Adapter                                | 31        | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 30        | 2.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 29        | 2.4%    |
| Intel Wireless 7265                                            | 28        | 2.31%   |
| Intel Wi-Fi 6 AX200                                            | 26        | 2.15%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 25        | 2.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 25        | 2.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 24        | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 23        | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 23        | 1.9%    |
| Intel Wi-Fi 6 AX201                                            | 22        | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 22        | 1.82%   |
| Intel Wireless 7260                                            | 21        | 1.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 20        | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                  | 20        | 1.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 19        | 1.57%   |
| Qualcomm Atheros AR9271 802.11n                                | 17        | 1.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 17        | 1.4%    |
| Intel Wireless 8260                                            | 17        | 1.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 1.24%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 13        | 1.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13        | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 13        | 1.07%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 12        | 0.99%   |
| Intel Wireless 3165                                            | 12        | 0.99%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11        | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 10        | 0.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 10        | 0.83%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 9         | 0.74%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 9         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 9         | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.74%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 8         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 719       | 59.57%  |
| Intel                            | 200       | 16.57%  |
| Qualcomm Atheros                 | 90        | 7.46%   |
| Broadcom                         | 50        | 4.14%   |
| Xiaomi                           | 27        | 2.24%   |
| Samsung Electronics              | 22        | 1.82%   |
| Marvell Technology Group         | 13        | 1.08%   |
| OPPO Electronics                 | 11        | 0.91%   |
| MediaTek                         | 10        | 0.83%   |
| ASIX Electronics                 | 7         | 0.58%   |
| Qualcomm                         | 6         | 0.5%    |
| JMicron Technology               | 6         | 0.5%    |
| IBM                              | 6         | 0.5%    |
| Broadcom Limited                 | 6         | 0.5%    |
| TP-Link                          | 4         | 0.33%   |
| Nvidia                           | 4         | 0.33%   |
| Silicon Integrated Systems [SiS] | 3         | 0.25%   |
| ICS Advent                       | 3         | 0.25%   |
| Attansic Technology              | 3         | 0.25%   |
| Lenovo                           | 2         | 0.17%   |
| Huawei Technologies              | 2         | 0.17%   |
| HMD Global                       | 2         | 0.17%   |
| Hewlett-Packard                  | 2         | 0.17%   |
| D-Link System                    | 2         | 0.17%   |
| vivo                             | 1         | 0.08%   |
| VIA Technologies                 | 1         | 0.08%   |
| QinHeng Electronics              | 1         | 0.08%   |
| Microchip Technology             | 1         | 0.08%   |
| HTC (High Tech Computer)         | 1         | 0.08%   |
| Foxconn / Hon Hai                | 1         | 0.08%   |
| ASUSTek Computer                 | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 535       | 43.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 155       | 12.66%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 45        | 3.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20        | 1.63%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 1.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 1.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 15        | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 1.06%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 0.9%    |
| OPPO RMX2027                                                      | 11        | 0.9%    |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 0.74%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.65%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 7         | 0.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 7         | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 7         | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 7         | 0.57%   |
| MediaTek Wiko U316AT                                              | 7         | 0.57%   |
| Intel I211 Gigabit Network Connection                             | 7         | 0.57%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.49%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 6         | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 0.49%   |
| IBM RNDIS/Ethernet Gadget                                         | 6         | 0.49%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.49%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                  | 5         | 0.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 5         | 0.41%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.41%   |
| Intel Ethernet Connection (6) I219-LM                             | 5         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1139      | 50.69%  |
| Ethernet | 1102      | 49.04%  |
| Modem    | 6         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 961       | 73.81%  |
| Ethernet | 340       | 26.11%  |
| Modem    | 1         | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 795       | 59.73%  |
| 1     | 479       | 35.99%  |
| 0     | 29        | 2.18%   |
| 3     | 16        | 1.2%    |
| 4     | 10        | 0.75%   |
| 8     | 1         | 0.08%   |
| 6     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1241      | 92.61%  |
| Yes  | 99        | 7.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 298       | 34.77%  |
| Realtek Semiconductor           | 146       | 17.04%  |
| IMC Networks                    | 83        | 9.68%   |
| Qualcomm Atheros Communications | 81        | 9.45%   |
| Lite-On Technology              | 59        | 6.88%   |
| Broadcom                        | 49        | 5.72%   |
| Cambridge Silicon Radio         | 45        | 5.25%   |
| Foxconn / Hon Hai               | 33        | 3.85%   |
| Toshiba                         | 14        | 1.63%   |
| Apple                           | 12        | 1.4%    |
| Dell                            | 9         | 1.05%   |
| Ralink                          | 5         | 0.58%   |
| Hewlett-Packard                 | 5         | 0.58%   |
| Foxconn International           | 4         | 0.47%   |
| Realtek                         | 3         | 0.35%   |
| MediaTek                        | 3         | 0.35%   |
| ASUSTek Computer                | 3         | 0.35%   |
| Micro Star International        | 2         | 0.23%   |
| Marvell Semiconductor           | 1         | 0.12%   |
| Chicony Electronics             | 1         | 0.12%   |
| Alps Electric                   | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 112       | 13.07%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 78        | 9.1%    |
| Realtek Bluetooth Radio                             | 76        | 8.87%   |
| IMC Networks Bluetooth Device                       | 51        | 5.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 45        | 5.25%   |
| Intel AX201 Bluetooth                               | 42        | 4.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 39        | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 38        | 4.43%   |
| Intel AX200 Bluetooth                               | 26        | 3.03%   |
| Lite-On Bluetooth Device                            | 21        | 2.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 1.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 1.87%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 1.63%   |
| Realtek RTL8723B Bluetooth                          | 13        | 1.52%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 1.4%    |
| IMC Networks Bluetooth Radio                        | 11        | 1.28%   |
| Realtek RTL8821A Bluetooth                          | 10        | 1.17%   |
| Lite-On Wireless_Device                             | 10        | 1.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 1.17%   |
| Intel Bluetooth Device                              | 10        | 1.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 1.17%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 9         | 1.05%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 1.05%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 9         | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.93%   |
| Lite-On Atheros Bluetooth                           | 6         | 0.7%    |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.7%    |
| Apple Bluetooth Host Controller                     | 6         | 0.7%    |
| Ralink RT3290 Bluetooth                             | 5         | 0.58%   |
| Intel AX210 Bluetooth                               | 5         | 0.58%   |
| IMC Networks Wireless_Device                        | 5         | 0.58%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 5         | 0.58%   |
| Broadcom HP Portable SoftSailing                    | 5         | 0.58%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 5         | 0.58%   |
| Toshiba RT Bluetooth Radio                          | 4         | 0.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 0.47%   |
| Qualcomm Atheros Bluetooth                          | 4         | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.47%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.47%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 943       | 61.04%  |
| AMD                              | 376       | 24.34%  |
| Nvidia                           | 161       | 10.42%  |
| C-Media Electronics              | 11        | 0.71%   |
| Generalplus Technology           | 8         | 0.52%   |
| JMTek                            | 5         | 0.32%   |
| Silicon Integrated Systems [SiS] | 4         | 0.26%   |
| Samson Technologies              | 4         | 0.26%   |
| Texas Instruments                | 3         | 0.19%   |
| Logitech                         | 3         | 0.19%   |
| Jieli Technology                 | 3         | 0.19%   |
| Creative Labs                    | 3         | 0.19%   |
| ASUSTek Computer                 | 3         | 0.19%   |
| Samsung Electronics              | 2         | 0.13%   |
| KTMicro                          | 2         | 0.13%   |
| Barco Display Systems            | 2         | 0.13%   |
| Weltrend Semiconductor           | 1         | 0.06%   |
| STMicroelectronics               | 1         | 0.06%   |
| SteelSeries ApS                  | 1         | 0.06%   |
| Sony                             | 1         | 0.06%   |
| Solid State Logic                | 1         | 0.06%   |
| SAVITECH                         | 1         | 0.06%   |
| Razer USA                        | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| FDUCE PRO AUDIO MADE             | 1         | 0.06%   |
| Creative Technology              | 1         | 0.06%   |
| Cooler Master                    | 1         | 0.06%   |
| Conexant Systems                 | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 152       | 7.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 109       | 5.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 104       | 5.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 104       | 5.3%    |
| AMD FCH Azalia Controller                                                                         | 77        | 3.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 66        | 3.36%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 62        | 3.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 57        | 2.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 50        | 2.55%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 50        | 2.55%   |
| Intel 8 Series HD Audio Controller                                                                | 50        | 2.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 47        | 2.39%   |
| AMD Kabini HDMI/DP Audio                                                                          | 47        | 2.39%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 44        | 2.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 41        | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 41        | 2.09%   |
| Intel Broadwell-U Audio Controller                                                                | 41        | 2.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 38        | 1.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 36        | 1.83%   |
| AMD High Definition Audio Controller                                                              | 36        | 1.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 34        | 1.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 30        | 1.53%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 29        | 1.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 26        | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 22        | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 22        | 1.12%   |
| Nvidia High Definition Audio Controller                                                           | 19        | 0.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 19        | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 16        | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 16        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 0.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 0.81%   |
| AMD Wrestler HDMI Audio                                                                           | 16        | 0.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 15        | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 13        | 0.66%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 13        | 0.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 0.61%   |
| Intel 200 Series PCH HD Audio                                                                     | 12        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 255       | 27.16%  |
| SK hynix                                | 171       | 18.21%  |
| Micron Technology                       | 93        | 9.9%    |
| Kingston                                | 88        | 9.37%   |
| Unknown                                 | 82        | 8.73%   |
| Corsair                                 | 42        | 4.47%   |
| Team                                    | 39        | 4.15%   |
| V-GeN                                   | 27        | 2.88%   |
| Ramaxel Technology                      | 23        | 2.45%   |
| Elpida                                  | 19        | 2.02%   |
| Nanya Technology                        | 12        | 1.28%   |
| A-DATA Technology                       | 11        | 1.17%   |
| Unknown                                 | 11        | 1.17%   |
| Unknown (ABCD)                          | 10        | 1.06%   |
| G.Skill                                 | 8         | 0.85%   |
| Transcend                               | 5         | 0.53%   |
| Crucial                                 | 5         | 0.53%   |
| Apacer                                  | 4         | 0.43%   |
| Visipro                                 | 3         | 0.32%   |
| Patriot                                 | 3         | 0.32%   |
| Unknown (0x0DD5)                        | 2         | 0.21%   |
| Lexar                                   | 2         | 0.21%   |
| Kingmax                                 | 2         | 0.21%   |
| Hewlett-Packard                         | 2         | 0.21%   |
| ASint Technology                        | 2         | 0.21%   |
| A Force                                 | 2         | 0.21%   |
| Unknown (8AA1)                          | 1         | 0.11%   |
| Unknown (8A02)                          | 1         | 0.11%   |
| Super Talent                            | 1         | 0.11%   |
| Strontium                               | 1         | 0.11%   |
| Silicon Power Computer & Communications | 1         | 0.11%   |
| Silicon Power                           | 1         | 0.11%   |
| SHARETRONIC                             | 1         | 0.11%   |
| Qumo                                    | 1         | 0.11%   |
| HPE                                     | 1         | 0.11%   |
| GOODRAM                                 | 1         | 0.11%   |
| Goldkey                                 | 1         | 0.11%   |
| Foxline                                 | 1         | 0.11%   |
| ff                                      | 1         | 0.11%   |
| Essencore                               | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 1.87%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 1.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 1.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 12        | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 1.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.08%   |
| Unknown                                                          | 11        | 1.08%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 10        | 0.99%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 10        | 0.99%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 9         | 0.89%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 8         | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.79%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 8         | 0.79%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 8         | 0.79%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s            | 7         | 0.69%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 7         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.69%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.69%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.59%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.59%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.59%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.59%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 5         | 0.49%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.49%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.49%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 5         | 0.49%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s             | 5         | 0.49%   |
| Kingston RAM 9905625-004.A03LF 4GB SODIMM DDR3 3200MT/s          | 5         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 4         | 0.39%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 4         | 0.39%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.39%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 4         | 0.39%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.39%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s        | 4         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 328       | 43.79%  |
| DDR3    | 306       | 40.85%  |
| LPDDR4  | 30        | 4.01%   |
| DDR2    | 28        | 3.74%   |
| SDRAM   | 20        | 2.67%   |
| Unknown | 13        | 1.74%   |
| LPDDR3  | 11        | 1.47%   |
| LPDDR5  | 7         | 0.93%   |
| DDR5    | 3         | 0.4%    |
| DDR     | 2         | 0.27%   |
| DRAM    | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 543       | 72.21%  |
| DIMM         | 151       | 20.08%  |
| Row Of Chips | 51        | 6.78%   |
| Chip         | 5         | 0.66%   |
| Unknown      | 2         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 329       | 38.52%  |
| 8192  | 280       | 32.79%  |
| 2048  | 130       | 15.22%  |
| 16384 | 66        | 7.73%   |
| 32768 | 28        | 3.28%   |
| 1024  | 18        | 2.11%   |
| 512   | 2         | 0.23%   |
| 65536 | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 210       | 24.48%  |
| 2667    | 130       | 15.15%  |
| 3200    | 122       | 14.22%  |
| 2400    | 73        | 8.51%   |
| 1333    | 57        | 6.64%   |
| 2133    | 37        | 4.31%   |
| 1334    | 31        | 3.61%   |
| 1067    | 21        | 2.45%   |
| 3266    | 19        | 2.21%   |
| 800     | 18        | 2.1%    |
| Unknown | 15        | 1.75%   |
| 667     | 12        | 1.4%    |
| 1867    | 9         | 1.05%   |
| 4266    | 8         | 0.93%   |
| 1800    | 8         | 0.93%   |
| 8400    | 7         | 0.82%   |
| 4267    | 7         | 0.82%   |
| 6400    | 5         | 0.58%   |
| 4199    | 5         | 0.58%   |
| 3800    | 5         | 0.58%   |
| 3733    | 5         | 0.58%   |
| 3600    | 5         | 0.58%   |
| 1066    | 5         | 0.58%   |
| 1866    | 4         | 0.47%   |
| 533     | 4         | 0.47%   |
| 2666    | 3         | 0.35%   |
| 333     | 3         | 0.35%   |
| 3400    | 2         | 0.23%   |
| 3151    | 2         | 0.23%   |
| 3000    | 2         | 0.23%   |
| 2048    | 2         | 0.23%   |
| 50410   | 1         | 0.12%   |
| 7467    | 1         | 0.12%   |
| 5600    | 1         | 0.12%   |
| 5500    | 1         | 0.12%   |
| 5200    | 1         | 0.12%   |
| 4800    | 1         | 0.12%   |
| 4040    | 1         | 0.12%   |
| 3866    | 1         | 0.12%   |
| 3666    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 22        | 59.46%  |
| Hewlett-Packard    | 6         | 16.22%  |
| Canon              | 3         | 8.11%   |
| Brother Industries | 3         | 8.11%   |
| STMicroelectronics | 2         | 5.41%   |
| Fuji Xerox         | 1         | 2.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seiko Epson L120 Series                 | 6         | 16.22%  |
| Seiko Epson L360 Series                 | 5         | 13.51%  |
| Seiko Epson L310 Series                 | 3         | 8.11%   |
| Seiko Epson L3110 Series                | 2         | 5.41%   |
| Seiko Epson L300 Series                 | 2         | 5.41%   |
| Canon iP2700 series                     | 2         | 5.41%   |
| Brother DCP-T300                        | 2         | 5.41%   |
| STMicroelectronics USB Printing Support | 1         | 2.7%    |
| STMicroelectronics JRSVC Printer        | 1         | 2.7%    |
| Seiko Epson L405 Series                 | 1         | 2.7%    |
| Seiko Epson L355 Series                 | 1         | 2.7%    |
| Seiko Epson L3210 Series                | 1         | 2.7%    |
| Seiko Epson L1300 Series                | 1         | 2.7%    |
| HP LaserJet P1102                       | 1         | 2.7%    |
| HP LaserJet P1006                       | 1         | 2.7%    |
| HP LaserJet M101-M106                   | 1         | 2.7%    |
| HP Ink Tank 110 series                  | 1         | 2.7%    |
| HP DeskJet 5820 series                  | 1         | 2.7%    |
| HP DeskJet 2130 series                  | 1         | 2.7%    |
| Fuji Xerox DocuPrint M205 b             | 1         | 2.7%    |
| Canon LiDE 300                          | 1         | 2.7%    |
| Brother DCP-T310                        | 1         | 2.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 50%     |
| Canon CanoScan 4400F   | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 248       | 27.25%  |
| IMC Networks                           | 123       | 13.52%  |
| Realtek Semiconductor                  | 79        | 8.68%   |
| Bison Electronics                      | 61        | 6.7%    |
| Sunplus Innovation Technology          | 49        | 5.38%   |
| Quanta                                 | 49        | 5.38%   |
| Syntek                                 | 42        | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 42        | 4.62%   |
| Microdia                               | 38        | 4.18%   |
| Suyin                                  | 24        | 2.64%   |
| Alcor Micro                            | 24        | 2.64%   |
| Acer                                   | 16        | 1.76%   |
| Lite-On Technology                     | 12        | 1.32%   |
| Apple                                  | 12        | 1.32%   |
| Luxvisions Innotech Limited            | 10        | 1.1%    |
| Sonix Technology                       | 6         | 0.66%   |
| Silicon Motion                         | 6         | 0.66%   |
| Ricoh                                  | 6         | 0.66%   |
| Logitech                               | 6         | 0.66%   |
| Importek                               | 6         | 0.66%   |
| Primax Electronics                     | 4         | 0.44%   |
| Jieli Technology                       | 4         | 0.44%   |
| Lenovo                                 | 3         | 0.33%   |
| Generalplus Technology                 | 3         | 0.33%   |
| GEMBIRD                                | 3         | 0.33%   |
| ANYKA                                  | 3         | 0.33%   |
| Z-Star Microelectronics                | 2         | 0.22%   |
| Sunplus Technology                     | 2         | 0.22%   |
| SN0002                                 | 2         | 0.22%   |
| Huawei Technologies                    | 2         | 0.22%   |
| Cubeternet                             | 2         | 0.22%   |
| ALi                                    | 2         | 0.22%   |
| Unknown                                | 2         | 0.22%   |
| WCM_USB                                | 1         | 0.11%   |
| Tripath Technology                     | 1         | 0.11%   |
| SunplusIT                              | 1         | 0.11%   |
| Razer USA                              | 1         | 0.11%   |
| Pixart Imaging                         | 1         | 0.11%   |
| OPPO Electronics                       | 1         | 0.11%   |
| Omnivision                             | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 40        | 4.37%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 34        | 3.72%   |
| Chicony HD WebCam                                               | 33        | 3.61%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 29        | 3.17%   |
| Syntek Integrated Camera                                        | 27        | 2.95%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 24        | 2.62%   |
| IMC Networks Integrated Camera                                  | 20        | 2.19%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 17        | 1.86%   |
| Microdia Integrated_Webcam_HD                                   | 16        | 1.75%   |
| Chicony USB2.0 HD UVC WebCam                                    | 16        | 1.75%   |
| Chicony HP TrueVision HD Camera                                 | 15        | 1.64%   |
| Bison Integrated Camera                                         | 13        | 1.42%   |
| IMC Networks Lenovo EasyCamera                                  | 12        | 1.31%   |
| Bison Lenovo EasyCamera                                         | 12        | 1.31%   |
| Realtek Integrated_Webcam_HD                                    | 11        | 1.2%    |
| Quanta HD User Facing                                           | 11        | 1.2%    |
| IMC Networks EasyCamera                                         | 11        | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 11        | 1.2%    |
| Sunplus Asus Webcam                                             | 10        | 1.09%   |
| Chicony EasyCamera                                              | 10        | 1.09%   |
| Realtek USB2.0 HD UVC WebCam                                    | 9         | 0.98%   |
| Quanta VGA WebCam                                               | 9         | 0.98%   |
| Chicony Lenovo EasyCamera                                       | 9         | 0.98%   |
| Chicony HP Truevision HD                                        | 9         | 0.98%   |
| Syntek EasyCamera                                               | 8         | 0.87%   |
| Sunplus Integrated_Webcam_HD                                    | 8         | 0.87%   |
| Realtek USB Camera                                              | 8         | 0.87%   |
| Chicony TOSHIBA Web Camera - HD                                 | 8         | 0.87%   |
| Suyin 1.3M HD WebCam                                            | 7         | 0.77%   |
| Quanta HP TrueVision HD Camera                                  | 7         | 0.77%   |
| Microdia Integrated Webcam                                      | 7         | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 7         | 0.77%   |
| Bison HD Webcam                                                 | 7         | 0.77%   |
| Bison EasyCamera                                                | 7         | 0.77%   |
| Alcor Micro USB 2.0 Camera                                      | 7         | 0.77%   |
| Alcor Micro Asus Integrated Webcam                              | 7         | 0.77%   |
| Chicony HD User Facing                                          | 6         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 6         | 0.66%   |
| Bison VGA Webcam                                                | 6         | 0.66%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 6         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 41        | 27.89%  |
| Synaptics                  | 30        | 20.41%  |
| Elan Microelectronics      | 26        | 17.69%  |
| Shenzhen Goodix Technology | 19        | 12.93%  |
| LighTuning Technology      | 12        | 8.16%   |
| AuthenTec                  | 9         | 6.12%   |
| Upek                       | 5         | 3.4%    |
| STMicroelectronics         | 4         | 2.72%   |
| DigitalPersona             | 1         | 0.68%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                          | 14        | 9.52%   |
| Shenzhen Goodix Fingerprint Reader                        | 12        | 8.16%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 11        | 7.48%   |
| Elan ELAN:Fingerprint                                     | 11        | 7.48%   |
| Validity Sensors VFS495 Fingerprint Reader                | 8         | 5.44%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 8         | 5.44%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 7         | 4.76%   |
| Shenzhen Goodix  FingerPrint Device                       | 7         | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 5         | 3.4%    |
| Validity Sensors Swipe Fingerprint Sensor                 | 5         | 3.4%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 5         | 3.4%    |
| Synaptics WBDI                                            | 5         | 3.4%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 5         | 3.4%    |
| Validity Sensors VFS491                                   | 4         | 2.72%   |
| Validity Sensors VFS Fingerprint sensor                   | 4         | 2.72%   |
| Synaptics UWP WBDI                                        | 4         | 2.72%   |
| Synaptics  WBDI                                           | 4         | 2.72%   |
| STMicroelectronics Fingerprint Reader                     | 4         | 2.72%   |
| AuthenTec AES1600                                         | 4         | 2.72%   |
| Validity Sensors VFS471 Fingerprint Reader                | 3         | 2.04%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 2         | 1.36%   |
| Synaptics WBDI Fingerprint Reader USB 086                 | 2         | 1.36%   |
| AuthenTec Fingerprint Sensor                              | 2         | 1.36%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 2         | 1.36%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 0.68%   |
| Validity Sensors Synaptics WBDI                           | 1         | 0.68%   |
| Synaptics WBDI Fingerprint Reader USB 102                 | 1         | 0.68%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 0.68%   |
| Synaptics Fingerprint reader [HP G6]                      | 1         | 0.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 0.68%   |
| Elan fingerprint sensor [FeinTech FPS00200]               | 1         | 0.68%   |
| DigitalPersona Fingerprint Reader                         | 1         | 0.68%   |
| AuthenTec AES2810                                         | 1         | 0.68%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 18        | 51.43%  |
| Alcor Micro | 6         | 17.14%  |
| O2 Micro    | 5         | 14.29%  |
| Upek        | 4         | 11.43%  |
| Lenovo      | 2         | 5.71%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 28.57%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 17.14%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 11.43%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 11.43%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.71%   |
| Broadcom 5880                                                                | 2         | 5.71%   |
| Broadcom 58200                                                               | 2         | 5.71%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 982       | 72.58%  |
| 1     | 289       | 21.36%  |
| 2     | 65        | 4.8%    |
| 3     | 9         | 0.67%   |
| 4     | 6         | 0.44%   |
| 6     | 2         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 145       | 32.37%  |
| Graphics card            | 102       | 22.77%  |
| Net/wireless             | 55        | 12.28%  |
| Chipcard                 | 31        | 6.92%   |
| Multimedia controller    | 28        | 6.25%   |
| Communication controller | 24        | 5.36%   |
| Bluetooth                | 18        | 4.02%   |
| Unassigned class         | 11        | 2.46%   |
| Net/ethernet             | 10        | 2.23%   |
| Camera                   | 8         | 1.79%   |
| Storage                  | 4         | 0.89%   |
| Sound                    | 3         | 0.67%   |
| Flash memory             | 2         | 0.45%   |
| Card reader              | 2         | 0.45%   |
| Wireless                 | 1         | 0.22%   |
| Video                    | 1         | 0.22%   |
| Storage/ide              | 1         | 0.22%   |
| Network                  | 1         | 0.22%   |
| Modem                    | 1         | 0.22%   |

