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

Total: 1363

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Alurin        | Go Notebook                 | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
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
| Acer          | Aspire 4752                 | [2e5b64f391](https://linux-hardware.org/?probe=2e5b64f391) | Jan 27, 2021 |
| Acer          | Aspire 4752                 | [f068345e45](https://linux-hardware.org/?probe=f068345e45) | Jan 27, 2021 |
| Acer          | AOD255E                     | [b346230927](https://linux-hardware.org/?probe=b346230927) | Jan 27, 2021 |
| ASUSTek       | N56VM                       | [e6d527734c](https://linux-hardware.org/?probe=e6d527734c) | Jan 27, 2021 |
| Acer          | One Z1402                   | [1b8a4dfe38](https://linux-hardware.org/?probe=1b8a4dfe38) | Jan 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4cacca5cdf](https://linux-hardware.org/?probe=4cacca5cdf) | Jan 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d18f1e2124](https://linux-hardware.org/?probe=d18f1e2124) | Jan 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [16b5d3f4ca](https://linux-hardware.org/?probe=16b5d3f4ca) | Jan 23, 2021 |
| Acer          | Swift SF514-52T             | [be049e723f](https://linux-hardware.org/?probe=be049e723f) | Jan 21, 2021 |
| ASUSTek       | N56VM                       | [81c592d723](https://linux-hardware.org/?probe=81c592d723) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [dc16c8d7a4](https://linux-hardware.org/?probe=dc16c8d7a4) | Jan 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f9b1a75983](https://linux-hardware.org/?probe=f9b1a75983) | Jan 19, 2021 |
| Lenovo        | ThinkPad T480 20L5A02JID    | [0599ce4883](https://linux-hardware.org/?probe=0599ce4883) | Jan 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f34a9b325b](https://linux-hardware.org/?probe=f34a9b325b) | Jan 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [be559d7b11](https://linux-hardware.org/?probe=be559d7b11) | Jan 17, 2021 |
| Lenovo        | IdeaPad Z370                | [728438c7eb](https://linux-hardware.org/?probe=728438c7eb) | Jan 16, 2021 |
| Lenovo        | IdeaPad Z370                | [6e3c415308](https://linux-hardware.org/?probe=6e3c415308) | Jan 16, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [82728c7a68](https://linux-hardware.org/?probe=82728c7a68) | Jan 15, 2021 |
| Dell          | Vostro 5470                 | [8e785a29dd](https://linux-hardware.org/?probe=8e785a29dd) | Jan 15, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [bb99db17ed](https://linux-hardware.org/?probe=bb99db17ed) | Jan 15, 2021 |
| HP            | G42                         | [63dd848e66](https://linux-hardware.org/?probe=63dd848e66) | Jan 14, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [0cfe91c011](https://linux-hardware.org/?probe=0cfe91c011) | Jan 13, 2021 |
| HP            | ZBook 15 G2                 | [da387b9871](https://linux-hardware.org/?probe=da387b9871) | Jan 09, 2021 |
| ASUSTek       | G750JM                      | [794d86e07e](https://linux-hardware.org/?probe=794d86e07e) | Jan 07, 2021 |
| ASUSTek       | G750JM                      | [a32f193a0d](https://linux-hardware.org/?probe=a32f193a0d) | Jan 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [692f320444](https://linux-hardware.org/?probe=692f320444) | Jan 07, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [8a573087bd](https://linux-hardware.org/?probe=8a573087bd) | Jan 07, 2021 |
| MSI           | Modern 15 A10RBS            | [d4ded10aed](https://linux-hardware.org/?probe=d4ded10aed) | Jan 06, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [ea36c16e10](https://linux-hardware.org/?probe=ea36c16e10) | Jan 05, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [89d2d898df](https://linux-hardware.org/?probe=89d2d898df) | Jan 05, 2021 |
| ASUSTek       | K43SD                       | [79f04bb2b4](https://linux-hardware.org/?probe=79f04bb2b4) | Jan 04, 2021 |
| HP            | ZBook 15 G2                 | [6ebc8c1b1c](https://linux-hardware.org/?probe=6ebc8c1b1c) | Jan 03, 2021 |
| ASUSTek       | X455LAB                     | [1c55bbde2e](https://linux-hardware.org/?probe=1c55bbde2e) | Jan 01, 2021 |
| HP            | 1000                        | [981fa79f13](https://linux-hardware.org/?probe=981fa79f13) | Jan 01, 2021 |
| ASUSTek       | X455LAB                     | [8cbb6c5afe](https://linux-hardware.org/?probe=8cbb6c5afe) | Dec 31, 2020 |
| Sole          | Unknown                     | [04bc36aa05](https://linux-hardware.org/?probe=04bc36aa05) | Dec 30, 2020 |
| HP            | ZBook 15 G2                 | [87757ee4f2](https://linux-hardware.org/?probe=87757ee4f2) | Dec 30, 2020 |
| Dell          | Vostro A840                 | [76e7e81662](https://linux-hardware.org/?probe=76e7e81662) | Dec 28, 2020 |
| Lenovo        | ThinkPad T530 24294V4       | [50625b08c9](https://linux-hardware.org/?probe=50625b08c9) | Dec 26, 2020 |

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
| Ubuntu 20.04                 | 107       | 10.64%  |
| Ubuntu 18.04                 | 60        | 5.96%   |
| Ubuntu 22.04                 | 56        | 5.57%   |
| OpenMandriva 4.3             | 37        | 3.68%   |
| Arch Rolling                 | 28        | 2.78%   |
| OpenMandriva 4.2             | 23        | 2.29%   |
| KDE neon 20.04               | 19        | 1.89%   |
| Pop!_OS 22.04                | 18        | 1.79%   |
| Fedora 38                    | 18        | 1.79%   |
| Fedora 36                    | 18        | 1.79%   |
| Arch                         | 17        | 1.69%   |
| Manjaro                      | 15        | 1.49%   |
| Zorin 16                     | 14        | 1.39%   |
| Pop!_OS 20.04                | 14        | 1.39%   |
| ArcoLinux Rolling            | 14        | 1.39%   |
| Zorin 15                     | 13        | 1.29%   |
| Elementary 6.1               | 13        | 1.29%   |
| Debian 11                    | 13        | 1.29%   |
| Ubuntu 19.10                 | 12        | 1.19%   |
| Fedora 37                    | 12        | 1.19%   |
| Fedora 35                    | 12        | 1.19%   |
| Ubuntu 21.10                 | 11        | 1.09%   |
| OpenMandriva 23.03           | 11        | 1.09%   |
| Linux Mint 21.1              | 11        | 1.09%   |
| Linux Mint 20.3              | 11        | 1.09%   |
| OpenMandriva 23.08           | 10        | 0.99%   |
| Xubuntu 20.04                | 9         | 0.89%   |
| OpenMandriva 23.01           | 9         | 0.89%   |
| Kubuntu 20.04                | 9         | 0.89%   |
| Linux Mint 19.3              | 8         | 0.8%    |
| Kubuntu 22.04                | 8         | 0.8%    |
| EndeavourOS Rolling          | 8         | 0.8%    |
| Debian 10                    | 8         | 0.8%    |
| Ubuntu 23.04                 | 7         | 0.7%    |
| Ubuntu 21.04                 | 7         | 0.7%    |
| Pop!_OS 21.04                | 7         | 0.7%    |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 0.7%    |
| Linux Mint 20                | 7         | 0.7%    |
| KDE neon 22.04               | 7         | 0.7%    |
| Debian 12                    | 7         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 266       | 27.97%  |
| OpenMandriva  | 91        | 9.57%   |
| Fedora        | 70        | 7.36%   |
| Linux Mint    | 54        | 5.68%   |
| Arch          | 45        | 4.73%   |
| Pop!_OS       | 44        | 4.63%   |
| Manjaro       | 40        | 4.21%   |
| Debian        | 32        | 3.36%   |
| Zorin         | 30        | 3.15%   |
| Elementary    | 29        | 3.05%   |
| KDE neon      | 27        | 2.84%   |
| Kali          | 24        | 2.52%   |
| Kubuntu       | 23        | 2.42%   |
| Endless       | 20        | 2.1%    |
| Xubuntu       | 19        | 2%      |
| ArcoLinux     | 15        | 1.58%   |
| Lubuntu       | 13        | 1.37%   |
| ROSA          | 10        | 1.05%   |
| Ubuntu MATE   | 9         | 0.95%   |
| openSUSE      | 8         | 0.84%   |
| EndeavourOS   | 8         | 0.84%   |
| Nobara        | 6         | 0.63%   |
| LMDE          | 6         | 0.63%   |
| Ubuntu Unity  | 5         | 0.53%   |
| Parrot        | 5         | 0.53%   |
| Gentoo        | 5         | 0.53%   |
| MX            | 4         | 0.42%   |
| Deepin        | 4         | 0.42%   |
| Artix         | 4         | 0.42%   |
| Ubuntu Budgie | 3         | 0.32%   |
| SteamOS       | 3         | 0.32%   |
| Clear Linux   | 3         | 0.32%   |
| Xero          | 2         | 0.21%   |
| Solus         | 2         | 0.21%   |
| Garuda Linux  | 2         | 0.21%   |
| Chrome OS     | 2         | 0.21%   |
| CentOS        | 2         | 0.21%   |
| BlackPanther  | 2         | 0.21%   |
| AlmaLinux     | 2         | 0.21%   |
| Void Linux    | 1         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 37        | 3.45%   |
| 5.10.14-desktop-1omv4002 | 23        | 2.15%   |
| 5.4.0-42-generic         | 16        | 1.49%   |
| 5.15.0-56-generic        | 13        | 1.21%   |
| 5.4.0-26-generic         | 12        | 1.12%   |
| 5.15.0-41-generic        | 11        | 1.03%   |
| 6.2.6-desktop-1omv2390   | 10        | 0.93%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.84%   |
| 5.4.0-52-generic         | 9         | 0.84%   |
| 5.15.0-46-generic        | 9         | 0.84%   |
| 6.4.11-desktop-1omv2390  | 8         | 0.75%   |
| 5.15.0-48-generic        | 8         | 0.75%   |
| 5.0.0-25-generic         | 8         | 0.75%   |
| 4.18.0-15-generic        | 8         | 0.75%   |
| 5.4.0-58-generic         | 7         | 0.65%   |
| 5.4.0-54-generic         | 7         | 0.65%   |
| 5.15.0-58-generic        | 7         | 0.65%   |
| 5.15.0-47-generic        | 7         | 0.65%   |
| 5.11.0-37-generic        | 7         | 0.65%   |
| 5.8.0-48-generic         | 6         | 0.56%   |
| 5.3.0-46-generic         | 6         | 0.56%   |
| 5.19.0-35-generic        | 6         | 0.56%   |
| 5.15.0-52-generic        | 6         | 0.56%   |
| 5.15.0-43-generic        | 6         | 0.56%   |
| 6.2.0-26-generic         | 5         | 0.47%   |
| 5.8.0-41-generic         | 5         | 0.47%   |
| 5.4.0-80-generic         | 5         | 0.47%   |
| 5.4.0-45-generic         | 5         | 0.47%   |
| 5.19.0-46-generic        | 5         | 0.47%   |
| 5.15.0-53-generic        | 5         | 0.47%   |
| 5.11.0-7620-generic      | 5         | 0.47%   |
| 5.11.0-41-generic        | 5         | 0.47%   |
| 5.11.0-40-generic        | 5         | 0.47%   |
| 5.11.0-38-generic        | 5         | 0.47%   |
| 5.11.0-35-generic        | 5         | 0.47%   |
| 5.11.0-27-generic        | 5         | 0.47%   |
| 5.0.0-23-generic         | 5         | 0.47%   |
| 6.4.6-76060406-generic   | 4         | 0.37%   |
| 6.1.0-12-amd64           | 4         | 0.37%   |
| 5.4.0-7634-generic       | 4         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 135       | 13.06%  |
| 5.15.0  | 104       | 10.06%  |
| 5.11.0  | 55        | 5.32%   |
| 5.8.0   | 41        | 3.97%   |
| 5.16.7  | 38        | 3.68%   |
| 5.13.0  | 37        | 3.58%   |
| 5.3.0   | 33        | 3.19%   |
| 5.0.0   | 30        | 2.9%    |
| 4.15.0  | 29        | 2.8%    |
| 5.19.0  | 26        | 2.51%   |
| 5.10.14 | 24        | 2.32%   |
| 5.10.0  | 24        | 2.32%   |
| 6.2.0   | 22        | 2.13%   |
| 6.1.0   | 17        | 1.64%   |
| 4.18.0  | 17        | 1.64%   |
| 6.2.6   | 13        | 1.26%   |
| 4.19.0  | 13        | 1.26%   |
| 6.1.1   | 12        | 1.16%   |
| 6.4.11  | 11        | 1.06%   |
| 6.5.5   | 10        | 0.97%   |
| 5.14.0  | 7         | 0.68%   |
| 5.17.5  | 6         | 0.58%   |
| 5.16.0  | 6         | 0.58%   |
| 6.4.6   | 5         | 0.48%   |
| 6.5.3   | 4         | 0.39%   |
| 6.5.0   | 4         | 0.39%   |
| 6.0.12  | 4         | 0.39%   |
| 5.15.12 | 4         | 0.39%   |
| 5.14.16 | 4         | 0.39%   |
| 4.4.0   | 4         | 0.39%   |
| 6.4.8   | 3         | 0.29%   |
| 6.4.10  | 3         | 0.29%   |
| 6.3.5   | 3         | 0.29%   |
| 6.3.3   | 3         | 0.29%   |
| 6.2.9   | 3         | 0.29%   |
| 6.2.8   | 3         | 0.29%   |
| 6.0.9   | 3         | 0.29%   |
| 6.0.0   | 3         | 0.29%   |
| 5.9.11  | 3         | 0.29%   |
| 5.9.1   | 3         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 143       | 14.05%  |
| 5.15    | 126       | 12.38%  |
| 5.10    | 73        | 7.17%   |
| 5.11    | 58        | 5.7%    |
| 5.16    | 57        | 5.6%    |
| 5.8     | 52        | 5.11%   |
| 6.2     | 47        | 4.62%   |
| 6.1     | 46        | 4.52%   |
| 5.13    | 41        | 4.03%   |
| 5.19    | 38        | 3.73%   |
| 5.3     | 35        | 3.44%   |
| 5.0     | 32        | 3.14%   |
| 6.4     | 31        | 3.05%   |
| 4.15    | 29        | 2.85%   |
| 6.5     | 25        | 2.46%   |
| 5.14    | 21        | 2.06%   |
| 6.0     | 20        | 1.96%   |
| 4.18    | 20        | 1.96%   |
| 5.17    | 18        | 1.77%   |
| 4.19    | 18        | 1.77%   |
| 6.3     | 15        | 1.47%   |
| 5.18    | 15        | 1.47%   |
| 5.9     | 12        | 1.18%   |
| 4.9     | 8         | 0.79%   |
| 5.6     | 7         | 0.69%   |
| 5.12    | 6         | 0.59%   |
| 5.7     | 5         | 0.49%   |
| 5.5     | 5         | 0.49%   |
| 4.4     | 5         | 0.49%   |
| 5.2     | 2         | 0.2%    |
| 4.13    | 2         | 0.2%    |
| 4.10    | 2         | 0.2%    |
| 4.1     | 2         | 0.2%    |
| 5       | 1         | 0.1%    |
| 3.16    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 892       | 97.7%   |
| i686   | 21        | 2.3%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 401       | 41.95%  |
| KDE5            | 189       | 19.77%  |
| XFCE            | 81        | 8.47%   |
| Unknown         | 81        | 8.47%   |
| X-Cinnamon      | 54        | 5.65%   |
| Pantheon        | 28        | 2.93%   |
| MATE            | 22        | 2.3%    |
| KDE             | 18        | 1.88%   |
| LXQt            | 16        | 1.67%   |
| Cinnamon        | 12        | 1.26%   |
| Budgie          | 7         | 0.73%   |
| Unity           | 5         | 0.52%   |
| i3              | 5         | 0.52%   |
| Deepin          | 5         | 0.52%   |
| Hyprland        | 4         | 0.42%   |
| bspwm           | 4         | 0.42%   |
| sway            | 3         | 0.31%   |
| KDE4            | 3         | 0.31%   |
| GNOME Flashback | 3         | 0.31%   |
| DWM             | 3         | 0.31%   |
| qtile           | 2         | 0.21%   |
| ICEWM           | 2         | 0.21%   |
| Cutefish        | 2         | 0.21%   |
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
| X11     | 692       | 73.38%  |
| Wayland | 188       | 19.94%  |
| Unknown | 56        | 5.94%   |
| Tty     | 7         | 0.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 392       | 41.48%  |
| SDDM    | 176       | 18.62%  |
| GDM     | 130       | 13.76%  |
| LightDM | 108       | 11.43%  |
| GDM3    | 103       | 10.9%   |
| TDM     | 29        | 3.07%   |
| KDM     | 3         | 0.32%   |
| SLiM    | 2         | 0.21%   |
| Ly      | 1         | 0.11%   |
| LXDM    | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 749       | 80.71%  |
| Unknown | 77        | 8.3%    |
| id_ID   | 65        | 7%      |
| C       | 12        | 1.29%   |
| en_GB   | 11        | 1.19%   |
| en_SG   | 3         | 0.32%   |
| en_AG   | 3         | 0.32%   |
| fr_FR   | 2         | 0.22%   |
| en_AU   | 2         | 0.22%   |
| jv_ID   | 1         | 0.11%   |
| en_IN   | 1         | 0.11%   |
| de_DE   | 1         | 0.11%   |
| de_CH   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 552       | 59.1%   |
| BIOS | 382       | 40.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 699       | 74.76%  |
| Btrfs   | 105       | 11.23%  |
| Overlay | 65        | 6.95%   |
| Unknown | 25        | 2.67%   |
| Tmpfs   | 15        | 1.6%    |
| Xfs     | 10        | 1.07%   |
| Zfs     | 5         | 0.53%   |
| Ext2    | 5         | 0.53%   |
| F2fs    | 4         | 0.43%   |
| Ext3    | 2         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 409       | 43.84%  |
| GPT     | 408       | 43.73%  |
| MBR     | 116       | 12.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 808       | 87.07%  |
| Yes       | 120       | 12.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 528       | 56.71%  |
| Yes       | 403       | 43.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 223       | 24.42%  |
| ASUSTek Computer    | 196       | 21.47%  |
| Hewlett-Packard     | 142       | 15.55%  |
| Acer                | 135       | 14.79%  |
| Dell                | 74        | 8.11%   |
| Toshiba             | 34        | 3.72%   |
| MSI                 | 21        | 2.3%    |
| AXIOO               | 12        | 1.31%   |
| Apple               | 12        | 1.31%   |
| Sony                | 10        | 1.1%    |
| Fujitsu             | 9         | 0.99%   |
| Samsung Electronics | 6         | 0.66%   |
| Infinix             | 5         | 0.55%   |
| HUAWEI              | 4         | 0.44%   |
| Clevo               | 3         | 0.33%   |
| Valve               | 2         | 0.22%   |
| Timi                | 2         | 0.22%   |
| Panasonic           | 2         | 0.22%   |
| Intel               | 2         | 0.22%   |
| Gigabyte Technology | 2         | 0.22%   |
| Unknown             | 2         | 0.22%   |
| Sole                | 1         | 0.11%   |
| realme              | 1         | 0.11%   |
| Phoenix/SiS         | 1         | 0.11%   |
| Notebook            | 1         | 0.11%   |
| MicroByte           | 1         | 0.11%   |
| Hampoo              | 1         | 0.11%   |
| GPD                 | 1         | 0.11%   |
| Google              | 1         | 0.11%   |
| Compal              | 1         | 0.11%   |
| Chuwi               | 1         | 0.11%   |
| AZW                 | 1         | 0.11%   |
| AVITA               | 1         | 0.11%   |
| Alurin              | 1         | 0.11%   |
| ADVAN               | 1         | 0.11%   |
| Acidanthera         | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo IdeaPad 330-14AST 81D5           | 11        | 1.2%    |
| Lenovo G40-45 80E1                      | 11        | 1.2%    |
| HP Notebook                             | 11        | 1.2%    |
| HP Pavilion Aero Laptop 13-be0xxx       | 9         | 0.99%   |
| Acer Aspire 4752                        | 8         | 0.88%   |
| Lenovo IdeaPad S340-14API 81NB          | 6         | 0.66%   |
| HP Laptop 14-bw0xx                      | 6         | 0.66%   |
| HP 14                                   | 6         | 0.66%   |
| Acer Aspire 4750                        | 6         | 0.66%   |
| Lenovo G400 20235                       | 5         | 0.55%   |
| HP Pavilion g4                          | 5         | 0.55%   |
| ASUS X455YA                             | 5         | 0.55%   |
| ASUS X455LF                             | 5         | 0.55%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 5         | 0.55%   |
| ASUS GL553VD                            | 5         | 0.55%   |
| Apple MacBookPro12,1                    | 5         | 0.55%   |
| Acer Swift SF314-71                     | 5         | 0.55%   |
| Acer One Z1402                          | 5         | 0.55%   |
| Unknown                                 | 5         | 0.55%   |
| Lenovo IdeaPad 320-14AST 80XU           | 4         | 0.44%   |
| Lenovo G40-30 80FY                      | 4         | 0.44%   |
| HP Pavilion 14                          | 4         | 0.44%   |
| HP Laptop 14-cm0xxx                     | 4         | 0.44%   |
| HP Laptop 14-bs0xx                      | 4         | 0.44%   |
| HP EliteBook 2570p                      | 4         | 0.44%   |
| HP 1000                                 | 4         | 0.44%   |
| ASUS X456URK                            | 4         | 0.44%   |
| ASUS X453SA                             | 4         | 0.44%   |
| ASUS X442URR                            | 4         | 0.44%   |
| ASUS X200MA                             | 4         | 0.44%   |
| Acer Swift SFX14-41G                    | 4         | 0.44%   |
| Acer Swift SF314-56G                    | 4         | 0.44%   |
| Acer Aspire E5-476G                     | 4         | 0.44%   |
| Acer Aspire E5-475G                     | 4         | 0.44%   |
| Lenovo V310-14ISK 80SX                  | 3         | 0.33%   |
| Lenovo ThinkBook 14 G3 ACL 21A2         | 3         | 0.33%   |
| Lenovo IdeaPad 320-14ISK 80XG           | 3         | 0.33%   |
| Lenovo IdeaPad 3 14ITL6 82H7            | 3         | 0.33%   |
| Lenovo IdeaPad 3 14ARE05 81W3           | 3         | 0.33%   |
| Lenovo IdeaPad 100-14IBD 80RK           | 3         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 88        | 9.64%   |
| Acer Aspire        | 81        | 8.87%   |
| Lenovo ThinkPad    | 75        | 8.21%   |
| HP Laptop          | 39        | 4.27%   |
| ASUS VivoBook      | 37        | 4.05%   |
| Dell Latitude      | 35        | 3.83%   |
| HP Pavilion        | 33        | 3.61%   |
| Toshiba Satellite  | 22        | 2.41%   |
| Acer Swift         | 21        | 2.3%    |
| Dell Inspiron      | 19        | 2.08%   |
| HP EliteBook       | 18        | 1.97%   |
| Lenovo G40-45      | 11        | 1.2%    |
| HP Notebook        | 11        | 1.2%    |
| Dell Vostro        | 10        | 1.1%    |
| Lenovo ThinkBook   | 9         | 0.99%   |
| Acer Nitro         | 9         | 0.99%   |
| Toshiba PORTEGE    | 7         | 0.77%   |
| HP ProBook         | 7         | 0.77%   |
| ASUS TUF           | 7         | 0.77%   |
| MSI Modern         | 6         | 0.66%   |
| HP 14              | 6         | 0.66%   |
| ASUS ASUS          | 6         | 0.66%   |
| Acer One           | 6         | 0.66%   |
| Lenovo Yoga        | 5         | 0.55%   |
| Lenovo G400        | 5         | 0.55%   |
| Infinix INBook     | 5         | 0.55%   |
| AXIOO Mybook       | 5         | 0.55%   |
| ASUS X455YA        | 5         | 0.55%   |
| ASUS X455LF        | 5         | 0.55%   |
| ASUS ROG           | 5         | 0.55%   |
| ASUS GL553VD       | 5         | 0.55%   |
| Apple MacBookPro12 | 5         | 0.55%   |
| Unknown            | 5         | 0.55%   |
| Lenovo Legion      | 4         | 0.44%   |
| Lenovo G40-30      | 4         | 0.44%   |
| HP ENVY            | 4         | 0.44%   |
| HP 1000            | 4         | 0.44%   |
| ASUS ZenBook       | 4         | 0.44%   |
| ASUS X456URK       | 4         | 0.44%   |
| ASUS X453SA        | 4         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 95        | 10.41%  |
| 2019 | 92        | 10.08%  |
| 2021 | 85        | 9.31%   |
| 2012 | 81        | 8.87%   |
| 2013 | 76        | 8.32%   |
| 2011 | 73        | 8%      |
| 2014 | 66        | 7.23%   |
| 2015 | 60        | 6.57%   |
| 2020 | 59        | 6.46%   |
| 2017 | 56        | 6.13%   |
| 2016 | 47        | 5.15%   |
| 2010 | 45        | 4.93%   |
| 2009 | 23        | 2.52%   |
| 2022 | 21        | 2.3%    |
| 2008 | 16        | 1.75%   |
| 2007 | 9         | 0.99%   |
| 2023 | 6         | 0.66%   |
| 2006 | 3         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 913       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 841       | 91.02%  |
| Enabled  | 83        | 8.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 912       | 99.89%  |
| Yes  | 1         | 0.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 304       | 32.94%  |
| 3.01-4.0    | 242       | 26.22%  |
| 8.01-16.0   | 155       | 16.79%  |
| 16.01-24.0  | 102       | 11.05%  |
| 1.01-2.0    | 83        | 8.99%   |
| 32.01-64.0  | 13        | 1.41%   |
| 2.01-3.0    | 10        | 1.08%   |
| 24.01-32.0  | 7         | 0.76%   |
| 0.51-1.0    | 5         | 0.54%   |
| 64.01-256.0 | 2         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 359       | 35.76%  |
| 2.01-3.0   | 283       | 28.19%  |
| 3.01-4.0   | 138       | 13.75%  |
| 4.01-8.0   | 134       | 13.35%  |
| 0.51-1.0   | 57        | 5.68%   |
| 8.01-16.0  | 27        | 2.69%   |
| 0.01-0.5   | 4         | 0.4%    |
| 16.01-24.0 | 2         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 659       | 70.86%  |
| 2      | 241       | 25.91%  |
| 3      | 23        | 2.47%   |
| 0      | 4         | 0.43%   |
| 4      | 3         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 601       | 65.26%  |
| Yes       | 320       | 34.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 741       | 81.07%  |
| No        | 173       | 18.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 899       | 98.36%  |
| No        | 15        | 1.64%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 715       | 77.63%  |
| No        | 206       | 22.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Indonesia | 913       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Jakarta         | 263       | 26.27%  |
| Surabaya        | 100       | 9.99%   |
| Bandung         | 66        | 6.59%   |
| Yogyakarta      | 37        | 3.7%    |
| Bogor           | 37        | 3.7%    |
| Semarang        | 33        | 3.3%    |
| Bekasi          | 29        | 2.9%    |
| Denpasar        | 24        | 2.4%    |
| Malang          | 21        | 2.1%    |
| Tangerang       | 19        | 1.9%    |
| South Tangerang | 17        | 1.7%    |
| Medan           | 16        | 1.6%    |
| Makassar        | 13        | 1.3%    |
| Depok           | 13        | 1.3%    |
| Sleman          | 11        | 1.1%    |
| Samarinda       | 10        | 1%      |
| Palembang       | 10        | 1%      |
| Banjarmasin     | 9         | 0.9%    |
| Balikpapan      | 9         | 0.9%    |
| Tasikmalaya     | 8         | 0.8%    |
| Surakarta       | 7         | 0.7%    |
| Blitar          | 7         | 0.7%    |
| Banda Aceh      | 7         | 0.7%    |
| Magelang        | 6         | 0.6%    |
| Kudus           | 6         | 0.6%    |
| Brebes          | 6         | 0.6%    |
| Pontianak       | 5         | 0.5%    |
| Kediri          | 5         | 0.5%    |
| Gresik          | 5         | 0.5%    |
| Demak           | 5         | 0.5%    |
| Cirebon         | 5         | 0.5%    |
| Pekanbaru       | 4         | 0.4%    |
| Pasuruan        | 4         | 0.4%    |
| Mataram         | 4         | 0.4%    |
| Jember          | 4         | 0.4%    |
| Jambi City      | 4         | 0.4%    |
| Batam           | 4         | 0.4%    |
| Tegal           | 3         | 0.3%    |
| Sukabumi        | 3         | 0.3%    |
| Sragen          | 3         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 178       | 228    | 15.23%  |
| WDC                   | 141       | 166    | 12.06%  |
| Toshiba               | 120       | 132    | 10.27%  |
| Samsung Electronics   | 109       | 150    | 9.32%   |
| HGST                  | 61        | 69     | 5.22%   |
| Hitachi               | 47        | 54     | 4.02%   |
| SanDisk               | 41        | 53     | 3.51%   |
| Unknown               | 40        | 48     | 3.42%   |
| Intel                 | 36        | 54     | 3.08%   |
| Kingston              | 33        | 41     | 2.82%   |
| SK hynix              | 32        | 37     | 2.74%   |
| V-GeN                 | 31        | 32     | 2.65%   |
| Micron Technology     | 29        | 40     | 2.48%   |
| A-DATA Technology     | 23        | 29     | 1.97%   |
| MidasForce            | 22        | 23     | 1.88%   |
| VISIPRO               | 13        | 16     | 1.11%   |
| China                 | 13        | 13     | 1.11%   |
| Unknown               | 13        | 14     | 1.11%   |
| Fujitsu               | 11        | 12     | 0.94%   |
| Apacer                | 10        | 10     | 0.86%   |
| Team                  | 9         | 12     | 0.77%   |
| Silicon Motion        | 9         | 10     | 0.77%   |
| JMicron Technology    | 9         | 10     | 0.77%   |
| EYOTA                 | 8         | 11     | 0.68%   |
| Crucial               | 8         | 10     | 0.68%   |
| Apple                 | 7         | 8      | 0.6%    |
| Patriot               | 6         | 8      | 0.51%   |
| RX7                   | 5         | 6      | 0.43%   |
| Phison Electronics    | 5         | 6      | 0.43%   |
| KIOXIA                | 5         | 5      | 0.43%   |
| Wellcomm              | 4         | 4      | 0.34%   |
| External              | 4         | 4      | 0.34%   |
| Realtek Semiconductor | 3         | 3      | 0.26%   |
| Ramos Technology      | 3         | 10     | 0.26%   |
| PNY                   | 3         | 3      | 0.26%   |
| Pioneer               | 3         | 3      | 0.26%   |
| LITEONIT              | 3         | 4      | 0.26%   |
| LITEON                | 3         | 4      | 0.26%   |
| FORESEE               | 3         | 3      | 0.26%   |
| Union Memory          | 2         | 2      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB    | 40        | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB     | 38        | 3.16%   |
| Toshiba MQ01ABF050 500GB           | 25        | 2.08%   |
| Toshiba MQ04ABF100 1TB             | 22        | 1.83%   |
| Toshiba MQ01ABD100 1TB             | 19        | 1.58%   |
| HGST HTS545050A7E680 500GB         | 18        | 1.5%    |
| Unknown                            | 13        | 1.08%   |
| A-DATA SU650 120GB SSD             | 11        | 0.92%   |
| Seagate ST9500325AS 500GB          | 10        | 0.83%   |
| Hitachi HTS545050A7E380 500GB      | 10        | 0.83%   |
| HGST HTS725050A7E630 500GB         | 10        | 0.83%   |
| Seagate ST500LT012-9WS142 500GB    | 9         | 0.75%   |
| SanDisk NVMe SSD Drive 512GB       | 9         | 0.75%   |
| Intel SSDPEKNW512G8 512GB          | 9         | 0.75%   |
| Hitachi HTS543232A7A384 320GB      | 9         | 0.75%   |
| HGST HTS721010A9E630 1TB           | 9         | 0.75%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 8         | 0.67%   |
| WDC WD10SPZX-21Z10T0 1TB           | 8         | 0.67%   |
| MidasForce SSD 128GB               | 8         | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 7         | 0.58%   |
| Seagate ST9320325AS 320GB          | 7         | 0.58%   |
| Seagate ST2000LM007-1R8174 2TB     | 7         | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 7         | 0.58%   |
| Samsung SSD 850 EVO 250GB          | 7         | 0.58%   |
| WDC WD5000LPVX-80V0TT0 500GB       | 6         | 0.5%    |
| Unknown MMC Card  32GB             | 6         | 0.5%    |
| Seagate ST1000LX015-1U7172 1TB     | 6         | 0.5%    |
| Samsung SSD 860 EVO 250GB          | 6         | 0.5%    |
| Kingston SA400S37240G 240GB SSD    | 6         | 0.5%    |
| HGST HTS545050A7E380 500GB         | 6         | 0.5%    |
| HGST HTS541010A9E680 1TB           | 6         | 0.5%    |
| WDC WD10JPCX-24UE4T0 1TB           | 5         | 0.42%   |
| Unknown MMC Card  64GB             | 5         | 0.42%   |
| Seagate ST500LM021-1KJ152 500GB    | 5         | 0.42%   |
| Seagate ST1000LM049-2GH172 1TB     | 5         | 0.42%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB | 5         | 0.42%   |
| Samsung SSD 860 EVO 500GB          | 5         | 0.42%   |
| MidasForce SSD 256GB               | 5         | 0.42%   |
| Micron 2450_MTFDKBA512TFK 512GB    | 5         | 0.42%   |
| JMicron Generic 256GB              | 5         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 176       | 223    | 33.72%  |
| WDC                 | 104       | 117    | 19.92%  |
| Toshiba             | 104       | 114    | 19.92%  |
| HGST                | 61        | 69     | 11.69%  |
| Hitachi             | 47        | 54     | 9%      |
| Fujitsu             | 9         | 9      | 1.72%   |
| Unknown             | 5         | 5      | 0.96%   |
| Samsung Electronics | 4         | 4      | 0.77%   |
| External            | 4         | 4      | 0.77%   |
| Pioneer             | 2         | 2      | 0.38%   |
| USB3.0              | 1         | 1      | 0.19%   |
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
| Samsung Electronics | 46        | 60     | 14.6%   |
| WDC                 | 22        | 31     | 6.98%   |
| V-GeN               | 22        | 23     | 6.98%   |
| MidasForce          | 22        | 23     | 6.98%   |
| SanDisk             | 18        | 28     | 5.71%   |
| Kingston            | 18        | 19     | 5.71%   |
| A-DATA Technology   | 17        | 22     | 5.4%    |
| China               | 13        | 13     | 4.13%   |
| VISIPRO             | 10        | 13     | 3.17%   |
| Apacer              | 10        | 10     | 3.17%   |
| Unknown             | 9         | 9      | 2.86%   |
| Intel               | 8         | 12     | 2.54%   |
| Team                | 7         | 10     | 2.22%   |
| EYOTA               | 7         | 9      | 2.22%   |
| Crucial             | 7         | 9      | 2.22%   |
| Toshiba             | 6         | 7      | 1.9%    |
| Patriot             | 6         | 8      | 1.9%    |
| Micron Technology   | 5         | 7      | 1.59%   |
| Apple               | 5         | 5      | 1.59%   |
| Wellcomm            | 4         | 4      | 1.27%   |
| Seagate             | 4         | 4      | 1.27%   |
| RX7                 | 3         | 4      | 0.95%   |
| Ramos Technology    | 3         | 10     | 0.95%   |
| LITEONIT            | 3         | 4      | 0.95%   |
| LITEON              | 3         | 4      | 0.95%   |
| Smart               | 2         | 2      | 0.63%   |
| SK hynix            | 2         | 2      | 0.63%   |
| PNY                 | 2         | 2      | 0.63%   |
| Netac               | 2         | 2      | 0.63%   |
| Lexar               | 2         | 2      | 0.63%   |
| Kingmax             | 2         | 2      | 0.63%   |
| GALAX               | 2         | 2      | 0.63%   |
| FORESEE             | 2         | 2      | 0.63%   |
| XSTAR               | 1         | 1      | 0.32%   |
| WellcommMaster      | 1         | 1      | 0.32%   |
| Vaseky              | 1         | 2      | 0.32%   |
| Varro               | 1         | 1      | 0.32%   |
| ValueTech           | 1         | 1      | 0.32%   |
| Union Memory        | 1         | 1      | 0.32%   |
| UNIC2               | 1         | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 501       | 609    | 44.65%  |
| SSD     | 298       | 386    | 26.56%  |
| NVMe    | 256       | 342    | 22.82%  |
| Unknown | 35        | 41     | 3.12%   |
| MMC     | 32        | 41     | 2.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 702       | 1003   | 68.55%  |
| NVMe | 253       | 335    | 24.71%  |
| SAS  | 37        | 40     | 3.61%   |
| MMC  | 32        | 41     | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 529       | 710    | 70.16%  |
| 0.51-1.0   | 205       | 253    | 27.19%  |
| 1.01-2.0   | 19        | 31     | 2.52%   |
| 3.01-4.0   | 1         | 1      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 287       | 29.96%  |
| 251-500        | 246       | 25.68%  |
| 501-1000       | 112       | 11.69%  |
| 51-100         | 102       | 10.65%  |
| 1-20           | 65        | 6.78%   |
| 1001-2000      | 63        | 6.58%   |
| 21-50          | 58        | 6.05%   |
| Unknown        | 12        | 1.25%   |
| 2001-3000      | 7         | 0.73%   |
| More than 3000 | 6         | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 360       | 35.75%  |
| 21-50          | 203       | 20.16%  |
| 101-250        | 139       | 13.8%   |
| 51-100         | 131       | 13.01%  |
| 251-500        | 94        | 9.33%   |
| 501-1000       | 52        | 5.16%   |
| 1001-2000      | 12        | 1.19%   |
| Unknown        | 12        | 1.19%   |
| 2001-3000      | 3         | 0.3%    |
| More than 3000 | 1         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB       | 8         | 9      | 6.67%   |
| Seagate ST500LT012-9WS142 500GB  | 6         | 6      | 5%      |
| Seagate ST500LT012-1DG142 500GB  | 6         | 6      | 5%      |
| Seagate ST9500325AS 500GB        | 4         | 4      | 3.33%   |
| Toshiba MQ01ABF050 500GB         | 3         | 3      | 2.5%    |
| Toshiba MQ01ABD032 320GB         | 3         | 3      | 2.5%    |
| Seagate ST1000LM035-1RK172 1TB   | 3         | 3      | 2.5%    |
| Hitachi HTS545050A7E380 500GB    | 3         | 3      | 2.5%    |
| HGST HTS725050A7E630 500GB       | 3         | 3      | 2.5%    |
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 2      | 1.67%   |
| WDC WD3200BEKT-60V5T1 320GB      | 2         | 2      | 1.67%   |
| WDC WD10JPCX-24UE4T0 1TB         | 2         | 3      | 1.67%   |
| Toshiba MQ01ABD100 1TB           | 2         | 2      | 1.67%   |
| Toshiba MQ01ABD050 500GB         | 2         | 2      | 1.67%   |
| Toshiba MK5059GSXP 500GB         | 2         | 2      | 1.67%   |
| Toshiba MK3265GSX 320GB          | 2         | 3      | 1.67%   |
| Seagate ST1000LX015-1U7172 1TB   | 2         | 3      | 1.67%   |
| Hitachi HTS545032B9A300 320GB    | 2         | 2      | 1.67%   |
| HGST HTS545050A7E380 500GB       | 2         | 2      | 1.67%   |
| WellcommMaster 128GB SSD         | 1         | 1      | 0.83%   |
| Wellcomm Master 128GB SSD        | 1         | 1      | 0.83%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 1      | 0.83%   |
| WDC WD5000LPVX-80V0TT0 500GB     | 1         | 1      | 0.83%   |
| WDC WD5000LPVT-22G33T0 500GB     | 1         | 1      | 0.83%   |
| WDC WD5000LPCX-22VHAT0 500GB     | 1         | 1      | 0.83%   |
| WDC WD5000L 500GB                | 1         | 1      | 0.83%   |
| WDC WD5000BPVT-60HXZT3 500GB     | 1         | 1      | 0.83%   |
| WDC WD5000BPVT-08HXZT3 500GB     | 1         | 1      | 0.83%   |
| WDC WD5000BPVT-00HXZT3 500GB     | 1         | 1      | 0.83%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 1      | 0.83%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1      | 0.83%   |
| VISIPRO SSD 256GB                | 1         | 3      | 0.83%   |
| ValueTech SSD 256GB              | 1         | 1      | 0.83%   |
| Toshiba MQ04ABF100 1TB           | 1         | 1      | 0.83%   |
| Toshiba MQ01ABD075 752GB         | 1         | 1      | 0.83%   |
| Toshiba MQ01ABD050V 497GB        | 1         | 1      | 0.83%   |
| Toshiba MK7575GSX 752GB          | 1         | 2      | 0.83%   |
| Toshiba MK5075GSX 500GB          | 1         | 1      | 0.83%   |
| Toshiba MK3276GSX 320GB          | 1         | 1      | 0.83%   |
| Toshiba MK3275GSX 320GB          | 1         | 1      | 0.83%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 37     | 23.73%  |
| Toshiba             | 23        | 25     | 19.49%  |
| HGST                | 17        | 19     | 14.41%  |
| WDC                 | 16        | 17     | 13.56%  |
| Hitachi             | 13        | 13     | 11.02%  |
| Samsung Electronics | 3         | 4      | 2.54%   |
| Micron Technology   | 3         | 3      | 2.54%   |
| SanDisk             | 2         | 2      | 1.69%   |
| A-DATA Technology   | 2         | 4      | 1.69%   |
| WellcommMaster      | 1         | 1      | 0.85%   |
| Wellcomm            | 1         | 1      | 0.85%   |
| VISIPRO             | 1         | 3      | 0.85%   |
| ValueTech           | 1         | 1      | 0.85%   |
| SK hynix            | 1         | 1      | 0.85%   |
| RX7                 | 1         | 1      | 0.85%   |
| KLEVV               | 1         | 1      | 0.85%   |
| Intel               | 1         | 1      | 0.85%   |
| Crucial             | 1         | 1      | 0.85%   |
| China               | 1         | 1      | 0.85%   |
| Unknown             | 1         | 1      | 0.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 37     | 28.87%  |
| Toshiba             | 23        | 25     | 23.71%  |
| HGST                | 17        | 19     | 17.53%  |
| WDC                 | 15        | 16     | 15.46%  |
| Hitachi             | 13        | 13     | 13.4%   |
| Samsung Electronics | 1         | 1      | 1.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 96        | 111    | 82.05%  |
| SSD  | 18        | 22     | 15.38%  |
| NVMe | 3         | 4      | 2.56%   |

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
| Detected | 477       | 718    | 48.13%  |
| Works    | 396       | 559    | 39.96%  |
| Malfunc  | 113       | 137    | 11.4%   |
| Failed   | 5         | 5      | 0.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 637       | 59.81%  |
| AMD                              | 182       | 17.09%  |
| Samsung Electronics              | 65        | 6.1%    |
| SanDisk                          | 39        | 3.66%   |
| SK hynix                         | 29        | 2.72%   |
| Micron Technology                | 24        | 2.25%   |
| Kingston Technology Company      | 17        | 1.6%    |
| Silicon Motion                   | 13        | 1.22%   |
| Phison Electronics               | 11        | 1.03%   |
| Toshiba America Info Systems     | 8         | 0.75%   |
| ADATA Technology                 | 8         | 0.75%   |
| KIOXIA                           | 7         | 0.66%   |
| Union Memory (Shenzhen)          | 4         | 0.38%   |
| Silicon Integrated Systems [SiS] | 4         | 0.38%   |
| Realtek Semiconductor            | 4         | 0.38%   |
| Shenzhen Longsys Electronics     | 3         | 0.28%   |
| Nvidia                           | 2         | 0.19%   |
| Micron/Crucial Technology        | 2         | 0.19%   |
| Solid State Storage Technology   | 1         | 0.09%   |
| O2 Micro                         | 1         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.09%   |
| Lenovo                           | 1         | 0.09%   |
| ASMedia Technology               | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 170       | 15%     |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 87        | 7.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 82        | 7.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 53        | 4.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 49        | 4.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 46        | 4.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 34        | 3%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 29        | 2.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 29        | 2.56%   |
| Intel Volume Management Device NVMe RAID Controller                              | 23        | 2.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 22        | 1.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 21        | 1.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 19        | 1.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 18        | 1.59%   |
| Intel Tiger Lake-LP SATA Controller                                              | 17        | 1.5%    |
| Intel SSD 660P Series                                                            | 16        | 1.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 15        | 1.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 14        | 1.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14        | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 13        | 1.15%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 12        | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 12        | 1.06%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 11        | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 11        | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 11        | 0.97%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 10        | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 10        | 0.88%   |
| SK hynix BC511 NVMe SSD                                                          | 9         | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 9         | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                            | 9         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 8         | 0.71%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 7         | 0.62%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                            | 7         | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 7         | 0.62%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 7         | 0.62%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 7         | 0.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 0.62%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 7         | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 6         | 0.53%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 6         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 739       | 66.94%  |
| NVMe | 253       | 22.92%  |
| RAID | 71        | 6.43%   |
| IDE  | 41        | 3.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 686       | 75.14%  |
| AMD    | 227       | 24.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.86%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 16        | 1.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 15        | 1.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 1.53%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 14        | 1.53%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 14        | 1.53%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.42%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 1.42%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 13        | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 1.42%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 13        | 1.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 11        | 1.2%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 11        | 1.2%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 11        | 1.2%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 11        | 1.2%    |
| AMD Ryzen 5 5600U with Radeon Graphics        | 11        | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 1.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 1.09%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 1.09%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 10        | 1.09%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 1.09%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 10        | 1.09%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 10        | 1.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 0.98%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 9         | 0.98%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.98%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 8         | 0.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.88%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 8         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.77%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 0.77%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 7         | 0.77%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 7         | 0.77%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 7         | 0.77%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 7         | 0.77%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 7         | 0.77%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 6         | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 0.66%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 229       | 25.05%  |
| Intel Core i3           | 134       | 14.66%  |
| Intel Core i7           | 117       | 12.8%   |
| Intel Celeron           | 80        | 8.75%   |
| Other                   | 78        | 8.53%   |
| AMD Ryzen 5             | 56        | 6.13%   |
| Intel Core 2 Duo        | 28        | 3.06%   |
| AMD Ryzen 3             | 26        | 2.84%   |
| AMD A8                  | 22        | 2.41%   |
| AMD Ryzen 7             | 20        | 2.19%   |
| Intel Pentium           | 16        | 1.75%   |
| AMD A4                  | 14        | 1.53%   |
| Intel Atom              | 11        | 1.2%    |
| AMD E1                  | 10        | 1.09%   |
| AMD E                   | 9         | 0.98%   |
| AMD E2                  | 7         | 0.77%   |
| AMD A6                  | 7         | 0.77%   |
| Intel Pentium Dual-Core | 6         | 0.66%   |
| AMD Athlon              | 6         | 0.66%   |
| Intel Pentium Dual      | 5         | 0.55%   |
| Intel Genuine           | 5         | 0.55%   |
| AMD A10                 | 5         | 0.55%   |
| AMD Ryzen 9             | 4         | 0.44%   |
| Intel Core 2            | 3         | 0.33%   |
| AMD FX                  | 3         | 0.33%   |
| AMD C-60                | 3         | 0.33%   |
| Intel Xeon              | 2         | 0.22%   |
| AMD Ryzen 5 PRO         | 2         | 0.22%   |
| AMD A12                 | 2         | 0.22%   |
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
| 2      | 591       | 64.66%  |
| 4      | 223       | 24.4%   |
| 6      | 59        | 6.46%   |
| 8      | 20        | 2.19%   |
| 1      | 9         | 0.98%   |
| 12     | 6         | 0.66%   |
| 10     | 4         | 0.44%   |
| 14     | 2         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 913       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 651       | 71.3%   |
| 1      | 262       | 28.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 899       | 98.47%  |
| Unknown        | 11        | 1.2%    |
| 32-bit         | 3         | 0.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 215       | 22.58%  |
| 0x206a7    | 68        | 7.14%   |
| 0x306a9    | 53        | 5.57%   |
| 0x40651    | 41        | 4.31%   |
| 0x306d4    | 34        | 3.57%   |
| 0x806ea    | 28        | 2.94%   |
| 0x06006705 | 27        | 2.84%   |
| 0x406e3    | 26        | 2.73%   |
| 0x806ec    | 24        | 2.52%   |
| 0x806e9    | 24        | 2.52%   |
| 0x806c1    | 23        | 2.42%   |
| 0x20655    | 23        | 2.42%   |
| 0x08108109 | 22        | 2.31%   |
| 0x1067a    | 20        | 2.1%    |
| 0x906ea    | 18        | 1.89%   |
| 0x0a50000c | 17        | 1.79%   |
| 0x806eb    | 15        | 1.58%   |
| 0x07030105 | 15        | 1.58%   |
| 0x08108102 | 14        | 1.47%   |
| 0x706e5    | 13        | 1.37%   |
| 0x30678    | 13        | 1.37%   |
| 0x6fd      | 11        | 1.16%   |
| 0x306c3    | 11        | 1.16%   |
| 0x20652    | 10        | 1.05%   |
| 0x08608103 | 10        | 1.05%   |
| 0x706a8    | 9         | 0.95%   |
| 0x406c4    | 8         | 0.84%   |
| 0x406c3    | 8         | 0.84%   |
| 0x08600104 | 8         | 0.84%   |
| 0x906e9    | 7         | 0.74%   |
| 0x06001119 | 7         | 0.74%   |
| 0x05000119 | 7         | 0.74%   |
| 0x906a3    | 6         | 0.63%   |
| 0x10676    | 6         | 0.63%   |
| 0x0810100b | 6         | 0.63%   |
| 0x0700010f | 6         | 0.63%   |
| 0x03000027 | 6         | 0.63%   |
| 0x506e3    | 5         | 0.53%   |
| 0x06006704 | 5         | 0.53%   |
| 0x0600611a | 5         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 154       | 16.85%  |
| SandyBridge      | 83        | 9.08%   |
| IvyBridge        | 72        | 7.88%   |
| Haswell          | 62        | 6.78%   |
| Westmere         | 45        | 4.92%   |
| Excavator        | 44        | 4.81%   |
| Zen+             | 41        | 4.49%   |
| Silvermont       | 41        | 4.49%   |
| Broadwell        | 41        | 4.49%   |
| Skylake          | 38        | 4.16%   |
| TigerLake        | 31        | 3.39%   |
| Penryn           | 28        | 3.06%   |
| Puma             | 26        | 2.84%   |
| Unknown          | 24        | 2.63%   |
| Zen 3            | 22        | 2.41%   |
| IceLake          | 20        | 2.19%   |
| Zen 2            | 19        | 2.08%   |
| Core             | 17        | 1.86%   |
| Goldmont plus    | 16        | 1.75%   |
| Bobcat           | 16        | 1.75%   |
| Zen              | 14        | 1.53%   |
| Alderlake Hybrid | 12        | 1.31%   |
| Piledriver       | 8         | 0.88%   |
| Jaguar           | 8         | 0.88%   |
| Goldmont         | 8         | 0.88%   |
| K10 Llano        | 6         | 0.66%   |
| CometLake        | 6         | 0.66%   |
| Bonnell          | 5         | 0.55%   |
| Tremont          | 2         | 0.22%   |
| Steamroller      | 2         | 0.22%   |
| P6               | 2         | 0.22%   |
| K8 Hammer        | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 664       | 56.22%  |
| AMD                              | 279       | 23.62%  |
| Nvidia                           | 233       | 19.73%  |
| Silicon Integrated Systems [SiS] | 4         | 0.34%   |
| Silicon Motion                   | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 80        | 6.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 70        | 5.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 48        | 3.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 42        | 3.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 39        | 3.15%   |
| Intel HD Graphics 5500                                                                   | 36        | 2.91%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 36        | 2.91%   |
| Intel UHD Graphics 620                                                                   | 33        | 2.67%   |
| Intel HD Graphics 620                                                                    | 32        | 2.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 30        | 2.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 2.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 2.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23        | 1.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 22        | 1.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 21        | 1.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 1.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 20        | 1.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 1.62%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 20        | 1.62%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 20        | 1.62%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 20        | 1.62%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 19        | 1.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 1.29%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 1.21%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 14        | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 1.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 1.05%   |
| AMD Lucienne                                                                             | 13        | 1.05%   |
| Nvidia GP108M [GeForce MX150]                                                            | 11        | 0.89%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 11        | 0.89%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 11        | 0.89%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 9         | 0.73%   |
| Intel HD Graphics 630                                                                    | 9         | 0.73%   |
| Nvidia GP108M [GeForce MX250]                                                            | 8         | 0.65%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 8         | 0.65%   |
| Intel HD Graphics 500                                                                    | 8         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 424       | 46.19%  |
| Intel + Nvidia     | 194       | 21.13%  |
| 1 x AMD            | 169       | 18.41%  |
| Intel + AMD        | 45        | 4.9%    |
| 2 x AMD            | 36        | 3.92%   |
| AMD + Nvidia       | 29        | 3.16%   |
| 1 x Nvidia         | 8         | 0.87%   |
| 2 x Intel          | 5         | 0.54%   |
| 1 x SiS            | 4         | 0.44%   |
| 2 x Nvidia         | 2         | 0.22%   |
| Other              | 1         | 0.11%   |
| 1 x Silicon Motion | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 793       | 85.82%  |
| Proprietary | 116       | 12.55%  |
| Unknown     | 15        | 1.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 573       | 60.83%  |
| 1.01-2.0   | 153       | 16.24%  |
| 0.01-0.5   | 117       | 12.42%  |
| 0.51-1.0   | 46        | 4.88%   |
| 3.01-4.0   | 41        | 4.35%   |
| 5.01-6.0   | 8         | 0.85%   |
| 7.01-8.0   | 3         | 0.32%   |
| 2.01-3.0   | 1         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 207       | 21.3%   |
| Chimei Innolux          | 189       | 19.44%  |
| BOE                     | 158       | 16.26%  |
| LG Display              | 130       | 13.37%  |
| Samsung Electronics     | 78        | 8.02%   |
| Goldstar                | 35        | 3.6%    |
| Lenovo                  | 19        | 1.95%   |
| PANDA                   | 16        | 1.65%   |
| Sharp                   | 14        | 1.44%   |
| InfoVision              | 13        | 1.34%   |
| Apple                   | 12        | 1.23%   |
| Chi Mei Optoelectronics | 11        | 1.13%   |
| InnoLux Display         | 8         | 0.82%   |
| ViewSonic               | 6         | 0.62%   |
| Dell                    | 6         | 0.62%   |
| Acer                    | 6         | 0.62%   |
| Philips                 | 5         | 0.51%   |
| LG Philips              | 5         | 0.51%   |
| AOC                     | 5         | 0.51%   |
| Toshiba                 | 4         | 0.41%   |
| KDC                     | 4         | 0.41%   |
| CPT                     | 4         | 0.41%   |
| Sony                    | 3         | 0.31%   |
| Quanta Display          | 3         | 0.31%   |
| HKC                     | 3         | 0.31%   |
| Hewlett-Packard         | 3         | 0.31%   |
| HannStar                | 3         | 0.31%   |
| Valve                   | 2         | 0.21%   |
| Seiko/Epson             | 2         | 0.21%   |
| Panasonic               | 2         | 0.21%   |
| HJC                     | 2         | 0.21%   |
| BenQ                    | 2         | 0.21%   |
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
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 20        | 2.05%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 17        | 1.74%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 17        | 1.74%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 17        | 1.74%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 12        | 1.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 12        | 1.23%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 11        | 1.13%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 11        | 1.13%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 11        | 1.13%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 11        | 1.13%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 10        | 1.02%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 10        | 1.02%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 9         | 0.92%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 9         | 0.92%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 9         | 0.92%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 7         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 7         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 7         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch       | 7         | 0.72%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                  | 7         | 0.72%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 7         | 0.72%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6         | 0.61%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 6         | 0.61%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch           | 6         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch       | 6         | 0.61%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                  | 6         | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch  | 5         | 0.51%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 5         | 0.51%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 5         | 0.51%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 5         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 5         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 5         | 0.51%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                 | 5         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch  | 4         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 0.41%   |
| LG Display LCD Monitor LGD06B9 1920x1200 286x179mm 13.3-inch          | 4         | 0.41%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 4         | 0.41%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 4         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 509       | 54.56%  |
| 1920x1080 (FHD)   | 291       | 31.19%  |
| 1280x800 (WXGA)   | 25        | 2.68%   |
| 1600x900 (HD+)    | 20        | 2.14%   |
| 3840x2160 (4K)    | 13        | 1.39%   |
| 2560x1440 (QHD)   | 11        | 1.18%   |
| 1920x1200 (WUXGA) | 11        | 1.18%   |
| 2560x1600         | 10        | 1.07%   |
| 1440x900 (WXGA+)  | 10        | 1.07%   |
| 2880x1800         | 7         | 0.75%   |
| 1360x768          | 7         | 0.75%   |
| 1024x600          | 4         | 0.43%   |
| 800x1280          | 2         | 0.21%   |
| 3840x2400         | 2         | 0.21%   |
| 2560x1080         | 2         | 0.21%   |
| 3440x1440         | 1         | 0.11%   |
| 3200x1800 (QHD+)  | 1         | 0.11%   |
| 2966x900          | 1         | 0.11%   |
| 2736x1824         | 1         | 0.11%   |
| 2240x1400         | 1         | 0.11%   |
| 2160x1440         | 1         | 0.11%   |
| 1920x1280         | 1         | 0.11%   |
| 1024x768 (XGA)    | 1         | 0.11%   |
| Unknown           | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 292       | 30.04%  |
| 14      | 284       | 29.22%  |
| 15      | 189       | 19.44%  |
| 12      | 45        | 4.63%   |
| 11      | 33        | 3.4%    |
| 23      | 31        | 3.19%   |
| 18      | 23        | 2.37%   |
| 21      | 11        | 1.13%   |
| 24      | 10        | 1.03%   |
| 17      | 9         | 0.93%   |
| 19      | 8         | 0.82%   |
| 40      | 6         | 0.62%   |
| 16      | 5         | 0.51%   |
| 10      | 4         | 0.41%   |
| 34      | 3         | 0.31%   |
| 27      | 3         | 0.31%   |
| Unknown | 3         | 0.31%   |
| 48      | 2         | 0.21%   |
| 31      | 2         | 0.21%   |
| 7       | 2         | 0.21%   |
| 72      | 1         | 0.1%    |
| 60      | 1         | 0.1%    |
| 54      | 1         | 0.1%    |
| 52      | 1         | 0.1%    |
| 26      | 1         | 0.1%    |
| 20      | 1         | 0.1%    |
| 9       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 699       | 72.44%  |
| 201-300     | 140       | 14.51%  |
| 501-600     | 44        | 4.56%   |
| 401-500     | 42        | 4.35%   |
| 351-400     | 17        | 1.76%   |
| 801-900     | 6         | 0.62%   |
| 1001-1500   | 5         | 0.52%   |
| 701-800     | 3         | 0.31%   |
| 601-700     | 3         | 0.31%   |
| Unknown     | 3         | 0.31%   |
| 1-100       | 2         | 0.21%   |
| 1501-2000   | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 808       | 90.99%  |
| 16/10   | 65        | 7.32%   |
| 3/2     | 5         | 0.56%   |
| 21/9    | 3         | 0.34%   |
| Unknown | 3         | 0.34%   |
| 4/3     | 2         | 0.23%   |
| 0.67    | 2         | 0.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 524       | 53.96%  |
| 101-110        | 187       | 19.26%  |
| 201-250        | 52        | 5.36%   |
| 71-80          | 47        | 4.84%   |
| 61-70          | 44        | 4.53%   |
| 51-60          | 33        | 3.4%    |
| 141-150        | 23        | 2.37%   |
| 151-200        | 9         | 0.93%   |
| 121-130        | 9         | 0.93%   |
| More than 1000 | 6         | 0.62%   |
| 501-1000       | 6         | 0.62%   |
| 91-100         | 6         | 0.62%   |
| 351-500        | 5         | 0.51%   |
| 41-50          | 5         | 0.51%   |
| 301-350        | 4         | 0.41%   |
| 111-120        | 4         | 0.41%   |
| Unknown        | 3         | 0.31%   |
| 1-40           | 2         | 0.21%   |
| 131-140        | 2         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 453       | 47.04%  |
| 121-160       | 324       | 33.64%  |
| 51-100        | 104       | 10.8%   |
| 161-240       | 52        | 5.4%    |
| More than 240 | 18        | 1.87%   |
| 1-50          | 9         | 0.93%   |
| Unknown       | 3         | 0.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 812       | 86.94%  |
| 2     | 97        | 10.39%  |
| 0     | 22        | 2.36%   |
| 3     | 3         | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 554       | 37.53%  |
| Intel                             | 338       | 22.9%   |
| Qualcomm Atheros                  | 311       | 21.07%  |
| Broadcom                          | 98        | 6.64%   |
| MediaTek                          | 32        | 2.17%   |
| Broadcom Limited                  | 16        | 1.08%   |
| Xiaomi                            | 14        | 0.95%   |
| Samsung Electronics               | 12        | 0.81%   |
| Ralink Technology                 | 12        | 0.81%   |
| Marvell Technology Group          | 11        | 0.75%   |
| TP-Link                           | 10        | 0.68%   |
| Qualcomm Atheros Communications   | 9         | 0.61%   |
| OPPO Electronics                  | 9         | 0.61%   |
| Ralink                            | 8         | 0.54%   |
| JMicron Technology                | 6         | 0.41%   |
| Huawei Technologies               | 4         | 0.27%   |
| Ericsson Business Mobile Networks | 4         | 0.27%   |
| ASIX Electronics                  | 4         | 0.27%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.2%    |
| Qualcomm                          | 3         | 0.2%    |
| Attansic Technology               | 3         | 0.2%    |
| Sierra Wireless                   | 2         | 0.14%   |
| Nvidia                            | 2         | 0.14%   |
| ICS Advent                        | 2         | 0.14%   |
| Hewlett-Packard                   | 2         | 0.14%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 341       | 19.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 120       | 6.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 81        | 4.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 67        | 3.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 52        | 2.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 35        | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 2%      |
| Intel Wireless 8265 / 8275                                        | 32        | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 27        | 1.55%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 25        | 1.43%   |
| Intel Wireless 7265                                               | 25        | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 25        | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 25        | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 23        | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 21        | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 21        | 1.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 1.15%   |
| Intel Wireless 7260                                               | 19        | 1.09%   |
| Intel Wi-Fi 6 AX201                                               | 19        | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 18        | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                     | 18        | 1.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 17        | 0.97%   |
| Intel Wi-Fi 6 AX200                                               | 17        | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 0.92%   |
| Intel Wireless 8260                                               | 15        | 0.86%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 12        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11        | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 11        | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 11        | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 0.57%   |
| Ralink MT7601U Wireless Adapter                                   | 9         | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                   | 9         | 0.52%   |
| OPPO RMX2027                                                      | 9         | 0.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 9         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 311       | 32.91%  |
| Qualcomm Atheros                  | 282       | 29.84%  |
| Realtek Semiconductor             | 196       | 20.74%  |
| Broadcom                          | 77        | 8.15%   |
| MediaTek                          | 25        | 2.65%   |
| Ralink Technology                 | 12        | 1.27%   |
| Broadcom Limited                  | 12        | 1.27%   |
| Qualcomm Atheros Communications   | 9         | 0.95%   |
| Ralink                            | 8         | 0.85%   |
| TP-Link                           | 7         | 0.74%   |
| Sierra Wireless                   | 2         | 0.21%   |
| Fibocom                           | 1         | 0.11%   |
| Ericsson Business Mobile Networks | 1         | 0.11%   |
| D-Link                            | 1         | 0.11%   |
| AboCom Systems                    | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 81        | 8.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 67        | 7.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 52        | 5.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 35        | 3.68%   |
| Intel Wireless 8265 / 8275                                     | 32        | 3.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 31        | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 27        | 2.84%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 25        | 2.63%   |
| Intel Wireless 7265                                            | 25        | 2.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 25        | 2.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 25        | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 23        | 2.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 21        | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 21        | 2.21%   |
| Intel Wireless 7260                                            | 19        | 2%      |
| Intel Wi-Fi 6 AX201                                            | 19        | 2%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 18        | 1.89%   |
| Broadcom BCM43142 802.11b/g/n                                  | 18        | 1.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 17        | 1.79%   |
| Intel Wi-Fi 6 AX200                                            | 17        | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 16        | 1.68%   |
| Intel Wireless 8260                                            | 15        | 1.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 12        | 1.26%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11        | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 11        | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.05%   |
| Ralink MT7601U Wireless Adapter                                | 9         | 0.95%   |
| Qualcomm Atheros AR9271 802.11n                                | 9         | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 9         | 0.95%   |
| Realtek 802.11n WLAN Adapter                                   | 8         | 0.84%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 8         | 0.84%   |
| Intel Wireless 3165                                            | 8         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 8         | 0.84%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 8         | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 7         | 0.74%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 6         | 0.63%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 6         | 0.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 6         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 475       | 60.36%  |
| Intel                            | 121       | 15.37%  |
| Qualcomm Atheros                 | 68        | 8.64%   |
| Broadcom                         | 31        | 3.94%   |
| Xiaomi                           | 14        | 1.78%   |
| Samsung Electronics              | 12        | 1.52%   |
| Marvell Technology Group         | 11        | 1.4%    |
| OPPO Electronics                 | 9         | 1.14%   |
| MediaTek                         | 7         | 0.89%   |
| JMicron Technology               | 6         | 0.76%   |
| Broadcom Limited                 | 6         | 0.76%   |
| ASIX Electronics                 | 4         | 0.51%   |
| TP-Link                          | 3         | 0.38%   |
| Silicon Integrated Systems [SiS] | 3         | 0.38%   |
| Qualcomm                         | 3         | 0.38%   |
| Attansic Technology              | 3         | 0.38%   |
| Nvidia                           | 2         | 0.25%   |
| ICS Advent                       | 2         | 0.25%   |
| Hewlett-Packard                  | 2         | 0.25%   |
| Lenovo                           | 1         | 0.13%   |
| Huawei Technologies              | 1         | 0.13%   |
| HTC (High Tech Computer)         | 1         | 0.13%   |
| Foxconn / Hon Hai                | 1         | 0.13%   |
| ASUSTek Computer                 | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 341       | 43.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 120       | 15.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 4.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 2.53%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 1.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 1.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11        | 1.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 1.39%   |
| OPPO RMX2027                                                      | 9         | 1.14%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 1.01%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 1.01%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 7         | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.76%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.76%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.76%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.63%   |
| MediaTek Wiko U316AT                                              | 5         | 0.63%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 5         | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 0.51%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.51%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 0.38%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.38%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.38%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.38%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.38%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.38%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 3         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 899       | 54.65%  |
| Ethernet | 740       | 44.98%  |
| Modem    | 6         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 786       | 86.85%  |
| Ethernet | 118       | 13.04%  |
| Modem    | 1         | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 691       | 75.52%  |
| 1     | 207       | 22.62%  |
| 0     | 14        | 1.53%   |
| 3     | 3         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 848       | 91.58%  |
| Yes  | 78        | 8.42%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 238       | 33.1%   |
| Realtek Semiconductor           | 127       | 17.66%  |
| IMC Networks                    | 79        | 10.99%  |
| Qualcomm Atheros Communications | 71        | 9.87%   |
| Lite-On Technology              | 59        | 8.21%   |
| Broadcom                        | 46        | 6.4%    |
| Foxconn / Hon Hai               | 30        | 4.17%   |
| Toshiba                         | 14        | 1.95%   |
| Cambridge Silicon Radio         | 10        | 1.39%   |
| Apple                           | 10        | 1.39%   |
| Dell                            | 9         | 1.25%   |
| Ralink                          | 5         | 0.7%    |
| Hewlett-Packard                 | 5         | 0.7%    |
| Foxconn International           | 4         | 0.56%   |
| Realtek                         | 3         | 0.42%   |
| ASUSTek Computer                | 3         | 0.42%   |
| Micro Star International        | 2         | 0.28%   |
| MediaTek                        | 2         | 0.28%   |
| Chicony Electronics             | 1         | 0.14%   |
| Alps Electric                   | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 95        | 13.21%  |
| Realtek Bluetooth Radio                             | 67        | 9.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 65        | 9.04%   |
| IMC Networks Bluetooth Device                       | 47        | 6.54%   |
| Qualcomm Atheros  Bluetooth Device                  | 34        | 4.73%   |
| Intel AX201 Bluetooth                               | 33        | 4.59%   |
| Realtek  Bluetooth 4.2 Adapter                      | 32        | 4.45%   |
| Lite-On Bluetooth Device                            | 21        | 2.92%   |
| Intel AX200 Bluetooth                               | 17        | 2.36%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 2.23%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 2.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 1.95%   |
| Realtek RTL8723B Bluetooth                          | 11        | 1.53%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 11        | 1.53%   |
| IMC Networks Bluetooth Radio                        | 11        | 1.53%   |
| Realtek RTL8821A Bluetooth                          | 10        | 1.39%   |
| Lite-On Wireless_Device                             | 10        | 1.39%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 1.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 1.39%   |
| Intel Bluetooth Device                              | 8         | 1.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 1.11%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.97%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 7         | 0.97%   |
| Lite-On Atheros Bluetooth                           | 6         | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 0.83%   |
| Apple Bluetooth Host Controller                     | 6         | 0.83%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 0.7%    |
| IMC Networks Wireless_Device                        | 5         | 0.7%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 5         | 0.7%    |
| Broadcom HP Portable SoftSailing                    | 5         | 0.7%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 5         | 0.7%    |
| Toshiba RT Bluetooth Radio                          | 4         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.56%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.56%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.56%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.56%   |
| Broadcom BCM43142A0 Bluetooth Device                | 4         | 0.56%   |
| Broadcom BCM20702A0                                 | 4         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 672       | 66.8%   |
| AMD                              | 232       | 23.06%  |
| Nvidia                           | 75        | 7.46%   |
| Silicon Integrated Systems [SiS] | 4         | 0.4%    |
| Samson Technologies              | 3         | 0.3%    |
| JMTek                            | 3         | 0.3%    |
| Generalplus Technology           | 3         | 0.3%    |
| Samsung Electronics              | 2         | 0.2%    |
| Jieli Technology                 | 2         | 0.2%    |
| C-Media Electronics              | 2         | 0.2%    |
| ASUSTek Computer                 | 2         | 0.2%    |
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
| AMD Family 17h/19h HD Audio Controller                                                            | 114       | 8.63%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 99        | 7.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 92        | 6.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 61        | 4.62%   |
| AMD FCH Azalia Controller                                                                         | 56        | 4.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 49        | 3.71%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 48        | 3.63%   |
| Intel 8 Series HD Audio Controller                                                                | 48        | 3.63%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 47        | 3.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 45        | 3.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 44        | 3.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 42        | 3.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 41        | 3.1%    |
| Intel Broadwell-U Audio Controller                                                                | 41        | 3.1%    |
| AMD High Definition Audio Controller                                                              | 36        | 2.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 32        | 2.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 31        | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 26        | 1.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 22        | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 22        | 1.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 1.59%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 16        | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 16        | 1.21%   |
| AMD Wrestler HDMI Audio                                                                           | 15        | 1.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 1.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 11        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 0.76%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 0.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 8         | 0.61%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.61%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 8         | 0.61%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 7         | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 218       | 30.92%  |
| SK hynix                                | 138       | 19.57%  |
| Micron Technology                       | 85        | 12.06%  |
| Kingston                                | 58        | 8.23%   |
| Unknown                                 | 44        | 6.24%   |
| Team                                    | 24        | 3.4%    |
| Corsair                                 | 23        | 3.26%   |
| V-GeN                                   | 20        | 2.84%   |
| Ramaxel Technology                      | 19        | 2.7%    |
| Elpida                                  | 13        | 1.84%   |
| Nanya Technology                        | 11        | 1.56%   |
| Unknown (ABCD)                          | 10        | 1.42%   |
| A-DATA Technology                       | 8         | 1.13%   |
| Transcend                               | 4         | 0.57%   |
| Apacer                                  | 4         | 0.57%   |
| Unknown                                 | 3         | 0.43%   |
| Visipro                                 | 2         | 0.28%   |
| Lexar                                   | 2         | 0.28%   |
| Crucial                                 | 2         | 0.28%   |
| ASint Technology                        | 2         | 0.28%   |
| A Force                                 | 2         | 0.28%   |
| Unknown (8A02)                          | 1         | 0.14%   |
| Strontium                               | 1         | 0.14%   |
| Silicon Power Computer & Communications | 1         | 0.14%   |
| Silicon Power                           | 1         | 0.14%   |
| SHARETRONIC                             | 1         | 0.14%   |
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
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 1.97%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 1.84%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 1.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 12        | 1.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 10        | 1.31%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 10        | 1.31%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 1.05%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 8         | 1.05%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.05%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 8         | 1.05%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 8         | 1.05%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 8         | 1.05%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s            | 7         | 0.92%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 7         | 0.92%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.92%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.92%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.79%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.79%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.79%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.66%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.66%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.66%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 5         | 0.66%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s             | 5         | 0.66%   |
| Kingston RAM 9905625-004.A03LF 4GB SODIMM DDR3 3200MT/s          | 5         | 0.66%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 4         | 0.52%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.52%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.52%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s        | 4         | 0.52%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 0.52%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 4         | 0.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.52%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 242       | 44.4%   |
| DDR3    | 232       | 42.57%  |
| LPDDR4  | 28        | 5.14%   |
| DDR2    | 14        | 2.57%   |
| LPDDR3  | 10        | 1.83%   |
| SDRAM   | 8         | 1.47%   |
| LPDDR5  | 7         | 1.28%   |
| Unknown | 2         | 0.37%   |
| DRAM    | 1         | 0.18%   |
| DDR5    | 1         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 504       | 90.97%  |
| Row Of Chips | 43        | 7.76%   |
| Chip         | 5         | 0.9%    |
| Unknown      | 2         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 260       | 41.14%  |
| 8192  | 217       | 34.34%  |
| 2048  | 83        | 13.13%  |
| 16384 | 46        | 7.28%   |
| 32768 | 15        | 2.37%   |
| 1024  | 10        | 1.58%   |
| 512   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 167       | 26.42%  |
| 2667    | 113       | 17.88%  |
| 3200    | 98        | 15.51%  |
| 2400    | 59        | 9.34%   |
| 2133    | 31        | 4.91%   |
| 1334    | 31        | 4.91%   |
| 1333    | 25        | 3.96%   |
| 1067    | 17        | 2.69%   |
| 3266    | 15        | 2.37%   |
| Unknown | 9         | 1.42%   |
| 4266    | 8         | 1.27%   |
| 800     | 8         | 1.27%   |
| 8400    | 7         | 1.11%   |
| 4267    | 6         | 0.95%   |
| 1867    | 6         | 0.95%   |
| 667     | 6         | 0.95%   |
| 6400    | 5         | 0.79%   |
| 4199    | 5         | 0.79%   |
| 1066    | 3         | 0.47%   |
| 533     | 3         | 0.47%   |
| 2048    | 2         | 0.32%   |
| 7467    | 1         | 0.16%   |
| 5500    | 1         | 0.16%   |
| 4800    | 1         | 0.16%   |
| 3333    | 1         | 0.16%   |
| 1866    | 1         | 0.16%   |
| 1776    | 1         | 0.16%   |
| 975     | 1         | 0.16%   |
| 333     | 1         | 0.16%   |

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
| Canon LiDE 300                          | 1         | 7.14%   |

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
| Chicony Electronics                    | 228       | 27.98%  |
| IMC Networks                           | 117       | 14.36%  |
| Realtek Semiconductor                  | 73        | 8.96%   |
| Bison Electronics                      | 58        | 7.12%   |
| Sunplus Innovation Technology          | 47        | 5.77%   |
| Quanta                                 | 44        | 5.4%    |
| Cheng Uei Precision Industry (Foxlink) | 39        | 4.79%   |
| Syntek                                 | 36        | 4.42%   |
| Microdia                               | 32        | 3.93%   |
| Suyin                                  | 24        | 2.94%   |
| Alcor Micro                            | 24        | 2.94%   |
| Acer                                   | 14        | 1.72%   |
| Lite-On Technology                     | 11        | 1.35%   |
| Luxvisions Innotech Limited            | 9         | 1.1%    |
| Apple                                  | 8         | 0.98%   |
| Silicon Motion                         | 6         | 0.74%   |
| Ricoh                                  | 6         | 0.74%   |
| Importek                               | 6         | 0.74%   |
| Sonix Technology                       | 5         | 0.61%   |
| Primax Electronics                     | 4         | 0.49%   |
| Lenovo                                 | 3         | 0.37%   |
| Sunplus Technology                     | 2         | 0.25%   |
| Jieli Technology                       | 2         | 0.25%   |
| ALi                                    | 2         | 0.25%   |
| Unknown                                | 2         | 0.25%   |
| Tripath Technology                     | 1         | 0.12%   |
| SunplusIT                              | 1         | 0.12%   |
| Pixart Imaging                         | 1         | 0.12%   |
| OPPO Electronics                       | 1         | 0.12%   |
| Omnivision                             | 1         | 0.12%   |
| Logitech                               | 1         | 0.12%   |
| Huawei Technologies                    | 1         | 0.12%   |
| HD 2MP WEBCAM                          | 1         | 0.12%   |
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
| IMC Networks USB2.0 HD UVC WebCam                               | 34        | 4.16%   |
| Chicony HD WebCam                                               | 33        | 4.04%   |
| Chicony Integrated Camera                                       | 30        | 3.67%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 29        | 3.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 23        | 2.82%   |
| Syntek Integrated Camera                                        | 22        | 2.69%   |
| IMC Networks Integrated Camera                                  | 19        | 2.33%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 17        | 2.08%   |
| Chicony USB2.0 HD UVC WebCam                                    | 16        | 1.96%   |
| Chicony HP TrueVision HD Camera                                 | 15        | 1.84%   |
| Microdia Integrated_Webcam_HD                                   | 14        | 1.71%   |
| IMC Networks Lenovo EasyCamera                                  | 12        | 1.47%   |
| Bison Lenovo EasyCamera                                         | 12        | 1.47%   |
| Realtek Integrated_Webcam_HD                                    | 11        | 1.35%   |
| Quanta HD User Facing                                           | 11        | 1.35%   |
| IMC Networks EasyCamera                                         | 11        | 1.35%   |
| Sunplus Asus Webcam                                             | 10        | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 10        | 1.22%   |
| Bison Integrated Camera                                         | 10        | 1.22%   |
| Quanta VGA WebCam                                               | 9         | 1.1%    |
| Chicony Lenovo EasyCamera                                       | 9         | 1.1%    |
| Chicony HP Truevision HD                                        | 9         | 1.1%    |
| Chicony EasyCamera                                              | 9         | 1.1%    |
| Syntek EasyCamera                                               | 8         | 0.98%   |
| Realtek USB2.0 HD UVC WebCam                                    | 8         | 0.98%   |
| Realtek USB Camera                                              | 8         | 0.98%   |
| Chicony TOSHIBA Web Camera - HD                                 | 8         | 0.98%   |
| Suyin 1.3M HD WebCam                                            | 7         | 0.86%   |
| Sunplus Integrated_Webcam_HD                                    | 7         | 0.86%   |
| Quanta HP TrueVision HD Camera                                  | 7         | 0.86%   |
| Microdia Integrated Webcam                                      | 7         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 7         | 0.86%   |
| Bison HD Webcam                                                 | 7         | 0.86%   |
| Bison EasyCamera                                                | 7         | 0.86%   |
| Alcor Micro USB 2.0 Camera                                      | 7         | 0.86%   |
| Alcor Micro Asus Integrated Webcam                              | 7         | 0.86%   |
| Chicony HD User Facing                                          | 6         | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 6         | 0.73%   |
| Bison VGA Webcam                                                | 6         | 0.73%   |
| Syntek Lenovo EasyCamera                                        | 5         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 41        | 33.33%  |
| Elan Microelectronics      | 24        | 19.51%  |
| Synaptics                  | 18        | 14.63%  |
| LighTuning Technology      | 12        | 9.76%   |
| Shenzhen Goodix Technology | 11        | 8.94%   |
| AuthenTec                  | 9         | 7.32%   |
| Upek                       | 5         | 4.07%   |
| STMicroelectronics         | 2         | 1.63%   |
| DigitalPersona             | 1         | 0.81%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                       | 13        | 10.57%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 11        | 8.94%   |
| Elan ELAN:Fingerprint                                  | 10        | 8.13%   |
| Validity Sensors VFS495 Fingerprint Reader             | 8         | 6.5%    |
| Validity Sensors VFS 5011 fingerprint sensor           | 8         | 6.5%    |
| Shenzhen Goodix  FingerPrint Device                    | 7         | 5.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 6         | 4.88%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 5         | 4.07%   |
| Validity Sensors Swipe Fingerprint Sensor              | 5         | 4.07%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 5         | 4.07%   |
| Validity Sensors VFS491                                | 4         | 3.25%   |
| Validity Sensors VFS Fingerprint sensor                | 4         | 3.25%   |
| Shenzhen Goodix Fingerprint Reader                     | 4         | 3.25%   |
| AuthenTec AES1600                                      | 4         | 3.25%   |
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 2.44%   |
| Synaptics  WBDI                                        | 3         | 2.44%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 3         | 2.44%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 1.63%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 2         | 1.63%   |
| Synaptics UWP WBDI                                     | 2         | 1.63%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 1.63%   |
| AuthenTec Fingerprint Sensor                           | 2         | 1.63%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 2         | 1.63%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 0.81%   |
| Validity Sensors Synaptics WBDI                        | 1         | 0.81%   |
| Synaptics WBDI                                         | 1         | 0.81%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 0.81%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 0.81%   |
| Elan fingerprint sensor [FeinTech FPS00200]            | 1         | 0.81%   |
| DigitalPersona Fingerprint Reader                      | 1         | 0.81%   |
| AuthenTec AES2810                                      | 1         | 0.81%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 18        | 52.94%  |
| O2 Micro    | 5         | 14.71%  |
| Alcor Micro | 5         | 14.71%  |
| Upek        | 4         | 11.76%  |
| Lenovo      | 2         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 29.41%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 14.71%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 14.71%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 11.76%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 11.76%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.88%   |
| Broadcom 5880                                                                | 2         | 5.88%   |
| Broadcom 58200                                                               | 2         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 645       | 68.91%  |
| 1     | 226       | 24.15%  |
| 2     | 58        | 6.2%    |
| 3     | 6         | 0.64%   |
| 6     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 122       | 35.36%  |
| Graphics card            | 83        | 24.06%  |
| Net/wireless             | 37        | 10.72%  |
| Chipcard                 | 31        | 8.99%   |
| Multimedia controller    | 23        | 6.67%   |
| Bluetooth                | 18        | 5.22%   |
| Camera                   | 7         | 2.03%   |
| Communication controller | 6         | 1.74%   |
| Net/ethernet             | 5         | 1.45%   |
| Storage                  | 4         | 1.16%   |
| Sound                    | 2         | 0.58%   |
| Flash memory             | 2         | 0.58%   |
| Card reader              | 2         | 0.58%   |
| Video                    | 1         | 0.29%   |
| Network                  | 1         | 0.29%   |
| Modem                    | 1         | 0.29%   |

