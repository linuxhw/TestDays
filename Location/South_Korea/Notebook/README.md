Linux in South Korea - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in South Korea.

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

Total: 453

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion g6                 | [ea52acdc1b](https://linux-hardware.org/?probe=ea52acdc1b) | Dec 30, 2024 |
| Samsung       | 960XGK                      | [da507c038f](https://linux-hardware.org/?probe=da507c038f) | Dec 29, 2024 |
| Samsung       | 960XGK                      | [feec3e592b](https://linux-hardware.org/?probe=feec3e592b) | Dec 29, 2024 |
| Lenovo        | G500s Touch 20263           | [0dbe4fae1f](https://linux-hardware.org/?probe=0dbe4fae1f) | Dec 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [77f57a0535](https://linux-hardware.org/?probe=77f57a0535) | Dec 18, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [f27e2a89ad](https://linux-hardware.org/?probe=f27e2a89ad) | Dec 16, 2024 |
| Dell          | Inspiron 15 3520            | [42e7404664](https://linux-hardware.org/?probe=42e7404664) | Dec 16, 2024 |
| Dell          | Inspiron 5565               | [a7b0d7e13d](https://linux-hardware.org/?probe=a7b0d7e13d) | Dec 15, 2024 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [37664cf5d9](https://linux-hardware.org/?probe=37664cf5d9) | Dec 13, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [07dbf8694f](https://linux-hardware.org/?probe=07dbf8694f) | Dec 02, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [9c65e1c0fd](https://linux-hardware.org/?probe=9c65e1c0fd) | Nov 12, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [bea18d3e92](https://linux-hardware.org/?probe=bea18d3e92) | Nov 12, 2024 |
| Samsung       | 940XFG                      | [262a845d6d](https://linux-hardware.org/?probe=262a845d6d) | Nov 11, 2024 |
| Lenovo        | ThinkPad Edge E440 20C5A... | [1277be0ef5](https://linux-hardware.org/?probe=1277be0ef5) | Nov 09, 2024 |
| LG Electro... | 15ZD90S-GX56K               | [e9630cc537](https://linux-hardware.org/?probe=e9630cc537) | Oct 23, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [88c68a9636](https://linux-hardware.org/?probe=88c68a9636) | Oct 19, 2024 |
| HP            | Stream Laptop 11-y0XX       | [f52f0612c7](https://linux-hardware.org/?probe=f52f0612c7) | Oct 15, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [90b6d6089f](https://linux-hardware.org/?probe=90b6d6089f) | Oct 02, 2024 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [edbbf74e3b](https://linux-hardware.org/?probe=edbbf74e3b) | Oct 01, 2024 |
| Dell          | XPS 13 9343                 | [ff5e0232e9](https://linux-hardware.org/?probe=ff5e0232e9) | Sep 23, 2024 |
| Dell          | XPS 12 9Q23                 | [b842f0a090](https://linux-hardware.org/?probe=b842f0a090) | Sep 21, 2024 |
| ASUSTek       | Strix 15 GL503GE            | [550001d98f](https://linux-hardware.org/?probe=550001d98f) | Sep 20, 2024 |
| Samsung       | 960XGL                      | [a8d96a5b4b](https://linux-hardware.org/?probe=a8d96a5b4b) | Sep 20, 2024 |
| Lenovo        | ThinkPad E550 20DF004HKD    | [3f884bbbaa](https://linux-hardware.org/?probe=3f884bbbaa) | Sep 17, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [15d1dd3590](https://linux-hardware.org/?probe=15d1dd3590) | Aug 17, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c3958fd4a3](https://linux-hardware.org/?probe=c3958fd4a3) | Aug 15, 2024 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [24119bdb5e](https://linux-hardware.org/?probe=24119bdb5e) | Aug 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [5b4b2e4b60](https://linux-hardware.org/?probe=5b4b2e4b60) | Aug 05, 2024 |
| Samsung       | R530/R730                   | [74c1021e6f](https://linux-hardware.org/?probe=74c1021e6f) | Aug 03, 2024 |
| Unknown       | Unknown                     | [fa8cf70193](https://linux-hardware.org/?probe=fa8cf70193) | Jul 24, 2024 |
| HANSUNG CO... | TFX252XA                    | [ebd5e2f006](https://linux-hardware.org/?probe=ebd5e2f006) | Jul 17, 2024 |
| Lenovo        | ThinkBook 14 G5 ABP 21JE    | [908c65a585](https://linux-hardware.org/?probe=908c65a585) | Jun 25, 2024 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [af5c648347](https://linux-hardware.org/?probe=af5c648347) | Jun 22, 2024 |
| LG Electro... | 15Z90Q-GA76K                | [59a67bd575](https://linux-hardware.org/?probe=59a67bd575) | May 30, 2024 |
| Valve         | Jupiter                     | [4080a2a217](https://linux-hardware.org/?probe=4080a2a217) | May 22, 2024 |
| MiTAC         | 9525                        | [0088b01ddd](https://linux-hardware.org/?probe=0088b01ddd) | May 11, 2024 |
| MiTAC         | 9525                        | [943ec75005](https://linux-hardware.org/?probe=943ec75005) | May 11, 2024 |
| Unknown       | Unknown                     | [8876712f97](https://linux-hardware.org/?probe=8876712f97) | May 05, 2024 |
| Unknown       | Unknown                     | [7cbaf2743a](https://linux-hardware.org/?probe=7cbaf2743a) | May 05, 2024 |
| Valve         | Jupiter                     | [728da6c7b1](https://linux-hardware.org/?probe=728da6c7b1) | May 05, 2024 |
| Valve         | Jupiter                     | [5f8e391778](https://linux-hardware.org/?probe=5f8e391778) | May 04, 2024 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [614efe1b07](https://linux-hardware.org/?probe=614efe1b07) | May 02, 2024 |
| LG Electro... | 14Z90S-GA5HK                | [ba55286732](https://linux-hardware.org/?probe=ba55286732) | May 02, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [e39dfad279](https://linux-hardware.org/?probe=e39dfad279) | Apr 10, 2024 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | [d003568e7a](https://linux-hardware.org/?probe=d003568e7a) | Apr 08, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [4f2f3edceb](https://linux-hardware.org/?probe=4f2f3edceb) | Apr 04, 2024 |
| Valve         | Galileo                     | [d816b83ec2](https://linux-hardware.org/?probe=d816b83ec2) | Mar 10, 2024 |
| HP            | Pavilion dv5                | [b0752dc7dc](https://linux-hardware.org/?probe=b0752dc7dc) | Mar 04, 2024 |
| Chuwi         | Hi10 Go                     | [8f143f6874](https://linux-hardware.org/?probe=8f143f6874) | Mar 01, 2024 |
| Acer          | Swift SF314-71              | [52c7804b0e](https://linux-hardware.org/?probe=52c7804b0e) | Feb 29, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [995aadf8a1](https://linux-hardware.org/?probe=995aadf8a1) | Feb 28, 2024 |
| ASRock        | X670E PG Lightning          | [d3ef0930d7](https://linux-hardware.org/?probe=d3ef0930d7) | Feb 28, 2024 |
| Apple         | MacBookPro11,5              | [e342f33cae](https://linux-hardware.org/?probe=e342f33cae) | Feb 17, 2024 |
| Samsung       | 940XFG                      | [dd9f6ec593](https://linux-hardware.org/?probe=dd9f6ec593) | Feb 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [79819299d1](https://linux-hardware.org/?probe=79819299d1) | Feb 13, 2024 |
| Samsung       | 940XFG                      | [5dea9b20b4](https://linux-hardware.org/?probe=5dea9b20b4) | Jan 30, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [8dd7c2b2aa](https://linux-hardware.org/?probe=8dd7c2b2aa) | Jan 25, 2024 |
| LG Electro... | 15Z95P-GRLGL                | [ce6c983048](https://linux-hardware.org/?probe=ce6c983048) | Jan 24, 2024 |
| LG Electro... | 15Z95P-GRLGL                | [9dcc8bbc45](https://linux-hardware.org/?probe=9dcc8bbc45) | Jan 24, 2024 |
| Samsung       | 940XGK                      | [786fb90f91](https://linux-hardware.org/?probe=786fb90f91) | Jan 22, 2024 |
| Samsung       | 940XGK                      | [90cea105a0](https://linux-hardware.org/?probe=90cea105a0) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4fe05dec99](https://linux-hardware.org/?probe=4fe05dec99) | Jan 18, 2024 |
| Dell          | Inspiron 16 5620            | [6ee5c8e435](https://linux-hardware.org/?probe=6ee5c8e435) | Jan 11, 2024 |
| Dell          | Inspiron 5515               | [ced5a24737](https://linux-hardware.org/?probe=ced5a24737) | Jan 08, 2024 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [ddc660cbfb](https://linux-hardware.org/?probe=ddc660cbfb) | Jan 06, 2024 |
| Dell          | Inspiron 5515               | [32aeaa1e64](https://linux-hardware.org/?probe=32aeaa1e64) | Jan 06, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [d11d965739](https://linux-hardware.org/?probe=d11d965739) | Dec 29, 2023 |
| Samsung       | 940XFG                      | [ca5d181ce4](https://linux-hardware.org/?probe=ca5d181ce4) | Dec 25, 2023 |
| Apple         | MacBookPro11,3              | [ec4972e3b4](https://linux-hardware.org/?probe=ec4972e3b4) | Dec 22, 2023 |
| LG Electro... | 15ZD970-EX50K               | [f9836d5b54](https://linux-hardware.org/?probe=f9836d5b54) | Dec 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [147873adce](https://linux-hardware.org/?probe=147873adce) | Dec 18, 2023 |
| HP            | Laptop 14s-cf2xxx           | [ad3926b9b4](https://linux-hardware.org/?probe=ad3926b9b4) | Nov 24, 2023 |
| Acer          | Aspire A315-42              | [5b538b13b5](https://linux-hardware.org/?probe=5b538b13b5) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [0923bf86fb](https://linux-hardware.org/?probe=0923bf86fb) | Nov 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f4dc3b24c4](https://linux-hardware.org/?probe=f4dc3b24c4) | Nov 11, 2023 |
| Apple         | MacBookPro16,1              | [0e1711e674](https://linux-hardware.org/?probe=0e1711e674) | Oct 28, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [62d0c94205](https://linux-hardware.org/?probe=62d0c94205) | Oct 23, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [3de8a2af66](https://linux-hardware.org/?probe=3de8a2af66) | Oct 23, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [3036944fc9](https://linux-hardware.org/?probe=3036944fc9) | Oct 23, 2023 |
| IMUZ          | STORMBOOK14 APOLLO          | [6d8e8178b0](https://linux-hardware.org/?probe=6d8e8178b0) | Oct 19, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [67dcd68d2b](https://linux-hardware.org/?probe=67dcd68d2b) | Oct 06, 2023 |
| Lenovo        | ThinkPad X230 2325KZ5       | [7c10f1a5de](https://linux-hardware.org/?probe=7c10f1a5de) | Sep 30, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [7941c7c6cc](https://linux-hardware.org/?probe=7941c7c6cc) | Sep 27, 2023 |
| ASUSTek       | X542UN                      | [76f91b9954](https://linux-hardware.org/?probe=76f91b9954) | Sep 24, 2023 |
| HP            | OMEN by Transcend Gaming... | [866ab5c907](https://linux-hardware.org/?probe=866ab5c907) | Sep 11, 2023 |
| HP            | OMEN by Transcend Gaming... | [2afa6e66d2](https://linux-hardware.org/?probe=2afa6e66d2) | Sep 11, 2023 |
| Samsung       | 700T1C                      | [6240a5d18a](https://linux-hardware.org/?probe=6240a5d18a) | Sep 09, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [2a900ea3bd](https://linux-hardware.org/?probe=2a900ea3bd) | Sep 03, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | [3c811f59ba](https://linux-hardware.org/?probe=3c811f59ba) | Aug 23, 2023 |
| ASUSTek       | GL502VMZ                    | [65952bbced](https://linux-hardware.org/?probe=65952bbced) | Aug 23, 2023 |
| LG Electro... | 15Z990-VA5WK                | [51c419c795](https://linux-hardware.org/?probe=51c419c795) | Aug 23, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | [df8b84163a](https://linux-hardware.org/?probe=df8b84163a) | Aug 23, 2023 |
| Lenovo        | ThinkPad X230 2306AV4       | [d52720a4dc](https://linux-hardware.org/?probe=d52720a4dc) | Aug 21, 2023 |
| Valve         | Jupiter                     | [1d87714ed5](https://linux-hardware.org/?probe=1d87714ed5) | Aug 20, 2023 |
| HP            | EliteBook 865 16 inch G9... | [f99d3dca93](https://linux-hardware.org/?probe=f99d3dca93) | Aug 17, 2023 |
| HP            | EliteBook 845 14 inch G9... | [0650746552](https://linux-hardware.org/?probe=0650746552) | Aug 13, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [fee93b31f5](https://linux-hardware.org/?probe=fee93b31f5) | Aug 13, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5892469c5b](https://linux-hardware.org/?probe=5892469c5b) | Aug 12, 2023 |
| Notebook      | N650DU                      | [c04f4faa06](https://linux-hardware.org/?probe=c04f4faa06) | Jul 19, 2023 |
| HP            | Pavilion dv6                | [2abf53d250](https://linux-hardware.org/?probe=2abf53d250) | Jul 17, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [c9a443767b](https://linux-hardware.org/?probe=c9a443767b) | Jul 16, 2023 |
| Dell          | XPS 15 9570                 | [1c15fc53af](https://linux-hardware.org/?probe=1c15fc53af) | Jul 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [09419812ab](https://linux-hardware.org/?probe=09419812ab) | Jun 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [856acf81ed](https://linux-hardware.org/?probe=856acf81ed) | Jun 22, 2023 |
| Acer          | Predator PHN16-71           | [16f2ca887d](https://linux-hardware.org/?probe=16f2ca887d) | Jun 20, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [4777b096a3](https://linux-hardware.org/?probe=4777b096a3) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| HP            | Laptop 15-fc0xxx            | [af90ec4131](https://linux-hardware.org/?probe=af90ec4131) | Jun 16, 2023 |
| HP            | ENVY Notebook               | [4a4602250b](https://linux-hardware.org/?probe=4a4602250b) | Jun 15, 2023 |
| HP            | ENVY Notebook               | [54115f309f](https://linux-hardware.org/?probe=54115f309f) | Jun 15, 2023 |
| Samsung       | 760XDA                      | [f0decf4dbe](https://linux-hardware.org/?probe=f0decf4dbe) | Jun 14, 2023 |
| Samsung       | 910S3L                      | [f8e59b4c0f](https://linux-hardware.org/?probe=f8e59b4c0f) | Jun 08, 2023 |
| Samsung       | 910S3L                      | [2db0ae25d8](https://linux-hardware.org/?probe=2db0ae25d8) | Jun 06, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [95ec288436](https://linux-hardware.org/?probe=95ec288436) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [7720a9f71c](https://linux-hardware.org/?probe=7720a9f71c) | Jun 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [8a6ceb7d8b](https://linux-hardware.org/?probe=8a6ceb7d8b) | May 30, 2023 |
| Samsung       | 950XDC/951XDC/950XDX        | [105d3da269](https://linux-hardware.org/?probe=105d3da269) | May 30, 2023 |
| Samsung       | 900X5T                      | [9f1d226c85](https://linux-hardware.org/?probe=9f1d226c85) | May 25, 2023 |
| ASUSTek       | X542UN                      | [29547f8e99](https://linux-hardware.org/?probe=29547f8e99) | May 24, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [2d07f38ffa](https://linux-hardware.org/?probe=2d07f38ffa) | May 17, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [de6d4ede23](https://linux-hardware.org/?probe=de6d4ede23) | May 17, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | [64353c7d87](https://linux-hardware.org/?probe=64353c7d87) | May 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [efc35b1887](https://linux-hardware.org/?probe=efc35b1887) | May 11, 2023 |
| Unknown       | Unknown                     | [0225c3c300](https://linux-hardware.org/?probe=0225c3c300) | May 09, 2023 |
| Samsung       | 730QCJ/730QCR               | [4541d2e721](https://linux-hardware.org/?probe=4541d2e721) | May 02, 2023 |
| Lenovo        | E520-15IKB 80WA             | [abd1d98b9b](https://linux-hardware.org/?probe=abd1d98b9b) | Apr 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [62399bace9](https://linux-hardware.org/?probe=62399bace9) | Apr 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [1f3ed1329d](https://linux-hardware.org/?probe=1f3ed1329d) | Apr 16, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [91946b965a](https://linux-hardware.org/?probe=91946b965a) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [674533c5cd](https://linux-hardware.org/?probe=674533c5cd) | Apr 12, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [9ddd50e0ed](https://linux-hardware.org/?probe=9ddd50e0ed) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [36338ecf6e](https://linux-hardware.org/?probe=36338ecf6e) | Apr 05, 2023 |
| Apple         | MacBookPro9,2               | [f4343acc49](https://linux-hardware.org/?probe=f4343acc49) | Apr 03, 2023 |
| Apple         | MacBookPro9,2               | [3e558165a4](https://linux-hardware.org/?probe=3e558165a4) | Apr 02, 2023 |
| HP            | Laptop 15s-eq3xxx           | [758bb2556e](https://linux-hardware.org/?probe=758bb2556e) | Apr 01, 2023 |
| Notebook      | N650DU                      | [e8ec3c6462](https://linux-hardware.org/?probe=e8ec3c6462) | Mar 30, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [bf2f7820cd](https://linux-hardware.org/?probe=bf2f7820cd) | Mar 29, 2023 |
| Apple         | MacBook9,1                  | [9639f02d57](https://linux-hardware.org/?probe=9639f02d57) | Mar 25, 2023 |
| WEIPAI        | S15                         | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| Apple         | MacBookPro11,2              | [9404efe255](https://linux-hardware.org/?probe=9404efe255) | Mar 18, 2023 |
| Gigabyte      | GB-BSi7A-6500               | [5a9b5297c2](https://linux-hardware.org/?probe=5a9b5297c2) | Mar 16, 2023 |
| Valve         | Jupiter                     | [0d12931010](https://linux-hardware.org/?probe=0d12931010) | Mar 11, 2023 |
| Dell          | Latitude E5440              | [25cf039ffd](https://linux-hardware.org/?probe=25cf039ffd) | Feb 27, 2023 |
| Dell          | Latitude E5440              | [5546f00169](https://linux-hardware.org/?probe=5546f00169) | Feb 26, 2023 |
| Samsung       | 760XDA                      | [efa040a93f](https://linux-hardware.org/?probe=efa040a93f) | Feb 22, 2023 |
| Samsung       | 760XDA                      | [1ba36d420d](https://linux-hardware.org/?probe=1ba36d420d) | Feb 22, 2023 |
| Gigabyte      | GB-BSi7A-6500               | [6ec55330a7](https://linux-hardware.org/?probe=6ec55330a7) | Feb 21, 2023 |
| Samsung       | 940XFG                      | [56f236f8ab](https://linux-hardware.org/?probe=56f236f8ab) | Feb 16, 2023 |
| Samsung       | 900X5N                      | [91793918de](https://linux-hardware.org/?probe=91793918de) | Feb 07, 2023 |
| Unknown       | Unknown                     | [d1da7498da](https://linux-hardware.org/?probe=d1da7498da) | Feb 02, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [9b17a7541e](https://linux-hardware.org/?probe=9b17a7541e) | Jan 30, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| HP            | Notebook                    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| ASUSTek       | X540UA                      | [39f992a141](https://linux-hardware.org/?probe=39f992a141) | Jan 22, 2023 |
| ASUSTek       | X540UA                      | [dda62597f7](https://linux-hardware.org/?probe=dda62597f7) | Jan 21, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [dfca68067c](https://linux-hardware.org/?probe=dfca68067c) | Jan 10, 2023 |
| Samsung       | 760XDA                      | [06a850e558](https://linux-hardware.org/?probe=06a850e558) | Jan 10, 2023 |
| Samsung       | 760XDA                      | [180727ef64](https://linux-hardware.org/?probe=180727ef64) | Jan 10, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [a56af08eb5](https://linux-hardware.org/?probe=a56af08eb5) | Jan 07, 2023 |
| Valve         | Jupiter                     | [e47684954b](https://linux-hardware.org/?probe=e47684954b) | Jan 04, 2023 |
| Lenovo        | ThinkPad E585 20KVS06F00    | [8c3bdcc48c](https://linux-hardware.org/?probe=8c3bdcc48c) | Dec 25, 2022 |
| Jooyon Tec... | J6BF                        | [dabe200abe](https://linux-hardware.org/?probe=dabe200abe) | Dec 23, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | [f244715ee3](https://linux-hardware.org/?probe=f244715ee3) | Dec 22, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | [2ebd48d256](https://linux-hardware.org/?probe=2ebd48d256) | Dec 22, 2022 |
| Gigabyte      | AERO 15 YC                  | [24e48000be](https://linux-hardware.org/?probe=24e48000be) | Dec 22, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | [d6f3d14b20](https://linux-hardware.org/?probe=d6f3d14b20) | Dec 22, 2022 |
| LG Electro... | 15UD480-GX50K               | [16be4a033d](https://linux-hardware.org/?probe=16be4a033d) | Dec 19, 2022 |
| Valve         | Jupiter                     | [24182862cd](https://linux-hardware.org/?probe=24182862cd) | Dec 15, 2022 |
| Valve         | Jupiter                     | [cfe8d55199](https://linux-hardware.org/?probe=cfe8d55199) | Dec 14, 2022 |
| Samsung       | 550XED                      | [8e5bdc1eab](https://linux-hardware.org/?probe=8e5bdc1eab) | Dec 14, 2022 |
| Samsung       | 550XED                      | [3165e8b2df](https://linux-hardware.org/?probe=3165e8b2df) | Dec 14, 2022 |
| Lenovo        | ThinkPad X260 20F6007KKR    | [9b788f857e](https://linux-hardware.org/?probe=9b788f857e) | Dec 14, 2022 |
| Valve         | Jupiter                     | [a2f1af21a0](https://linux-hardware.org/?probe=a2f1af21a0) | Dec 13, 2022 |
| Valve         | Jupiter                     | [a505c76dfa](https://linux-hardware.org/?probe=a505c76dfa) | Dec 13, 2022 |
| LG Electro... | 15ND530-GX3FK               | [47b90cbe2a](https://linux-hardware.org/?probe=47b90cbe2a) | Dec 12, 2022 |
| Google        | Peppy                       | [59f9af1c52](https://linux-hardware.org/?probe=59f9af1c52) | Dec 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5S... | [7772d8b9f8](https://linux-hardware.org/?probe=7772d8b9f8) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [5254612ca4](https://linux-hardware.org/?probe=5254612ca4) | Dec 09, 2022 |
| Samsung       | 550XED                      | [705495532e](https://linux-hardware.org/?probe=705495532e) | Dec 09, 2022 |
| Samsung       | 550XED                      | [0df3845885](https://linux-hardware.org/?probe=0df3845885) | Dec 08, 2022 |
| Lenovo        | ThinkPad T61 889502U        | [b9d0a07e47](https://linux-hardware.org/?probe=b9d0a07e47) | Dec 08, 2022 |
| Lenovo        | ThinkPad T60 1953PKK        | [fc308e2f1c](https://linux-hardware.org/?probe=fc308e2f1c) | Dec 08, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [e13e889312](https://linux-hardware.org/?probe=e13e889312) | Dec 08, 2022 |
| Samsung       | 550XED                      | [0ce3bd481f](https://linux-hardware.org/?probe=0ce3bd481f) | Dec 07, 2022 |
| Lenovo        | ThinkPad E495 20NES0J800    | [17182155b5](https://linux-hardware.org/?probe=17182155b5) | Dec 07, 2022 |
| Samsung       | 550XED                      | [fee55cdb61](https://linux-hardware.org/?probe=fee55cdb61) | Dec 02, 2022 |
| Samsung       | 550XED                      | [d8894f602a](https://linux-hardware.org/?probe=d8894f602a) | Dec 01, 2022 |
| Dell          | Latitude E5440              | [90d18073d6](https://linux-hardware.org/?probe=90d18073d6) | Nov 29, 2022 |
| Dell          | Inspiron 15 5510            | [5ec5306c0f](https://linux-hardware.org/?probe=5ec5306c0f) | Nov 28, 2022 |
| Samsung       | 550XED                      | [143518e596](https://linux-hardware.org/?probe=143518e596) | Nov 26, 2022 |
| Unknown       | Unknown                     | [d96c2be612](https://linux-hardware.org/?probe=d96c2be612) | Nov 23, 2022 |
| Samsung       | 950XED                      | [48213c8f60](https://linux-hardware.org/?probe=48213c8f60) | Nov 23, 2022 |
| Samsung       | 950XED                      | [0c91469d8f](https://linux-hardware.org/?probe=0c91469d8f) | Nov 21, 2022 |
| Dell          | Latitude E5440              | [6d90726959](https://linux-hardware.org/?probe=6d90726959) | Nov 21, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [2bc3a22052](https://linux-hardware.org/?probe=2bc3a22052) | Nov 20, 2022 |
| MSI           | Vector GP66 12UGS           | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| Samsung       | 550XED                      | [06722b1fee](https://linux-hardware.org/?probe=06722b1fee) | Nov 16, 2022 |
| Samsung       | 950XED                      | [2558d99814](https://linux-hardware.org/?probe=2558d99814) | Nov 16, 2022 |
| Samsung       | 950XED                      | [ddcb4e15c7](https://linux-hardware.org/?probe=ddcb4e15c7) | Nov 14, 2022 |
| Samsung       | 550XED                      | [bbebe45363](https://linux-hardware.org/?probe=bbebe45363) | Nov 13, 2022 |
| Samsung       | 550XED                      | [60c1aa4cc9](https://linux-hardware.org/?probe=60c1aa4cc9) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [9cdaa4c88b](https://linux-hardware.org/?probe=9cdaa4c88b) | Nov 09, 2022 |
| Samsung       | 550XED                      | [fc6d96f9fe](https://linux-hardware.org/?probe=fc6d96f9fe) | Nov 06, 2022 |
| Samsung       | 550XED                      | [6db345f53d](https://linux-hardware.org/?probe=6db345f53d) | Nov 03, 2022 |
| Samsung       | 550XED                      | [6992db47be](https://linux-hardware.org/?probe=6992db47be) | Nov 02, 2022 |
| Samsung       | 950XED                      | [821bc59c17](https://linux-hardware.org/?probe=821bc59c17) | Nov 02, 2022 |
| Samsung       | 550XED                      | [3b04d21991](https://linux-hardware.org/?probe=3b04d21991) | Nov 01, 2022 |
| Apple         | MacBookPro16,1              | [025e3e7e4e](https://linux-hardware.org/?probe=025e3e7e4e) | Nov 01, 2022 |
| MS            | MPGIO                       | [4fc8637bf3](https://linux-hardware.org/?probe=4fc8637bf3) | Nov 01, 2022 |
| HP            | Pavilion dv6                | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| LG Electro... | 15Z980-HA76K                | [914156672d](https://linux-hardware.org/?probe=914156672d) | Oct 30, 2022 |
| Samsung       | 950XED                      | [350a0f9d44](https://linux-hardware.org/?probe=350a0f9d44) | Oct 28, 2022 |
| Samsung       | 550XED                      | [1ebb9be92b](https://linux-hardware.org/?probe=1ebb9be92b) | Oct 28, 2022 |
| Samsung       | 550XED                      | [110d85c2e0](https://linux-hardware.org/?probe=110d85c2e0) | Oct 27, 2022 |
| Samsung       | 950XED                      | [a636a02096](https://linux-hardware.org/?probe=a636a02096) | Oct 27, 2022 |
| LG Electro... | 15Z90N-HA76K                | [7805c272fb](https://linux-hardware.org/?probe=7805c272fb) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [866d0f49a2](https://linux-hardware.org/?probe=866d0f49a2) | Oct 20, 2022 |
| Dell          | Precision 7520              | [366eed3b66](https://linux-hardware.org/?probe=366eed3b66) | Oct 20, 2022 |
| Dell          | Precision 7520              | [8c2829bbb2](https://linux-hardware.org/?probe=8c2829bbb2) | Oct 19, 2022 |
| HP            | EliteBook 865 16 inch G9... | [8665ee6ba6](https://linux-hardware.org/?probe=8665ee6ba6) | Oct 19, 2022 |
| Apple         | MacBookPro12,1              | [7979753fa9](https://linux-hardware.org/?probe=7979753fa9) | Oct 15, 2022 |
| Apple         | MacBookPro16,1              | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d4797ada2a](https://linux-hardware.org/?probe=d4797ada2a) | Sep 28, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [e777d38fbd](https://linux-hardware.org/?probe=e777d38fbd) | Sep 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [82b3d89bf9](https://linux-hardware.org/?probe=82b3d89bf9) | Sep 20, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [22171cc2a6](https://linux-hardware.org/?probe=22171cc2a6) | Sep 07, 2022 |
| ASUSTek       | Zephyrus S GX531GX_GX531... | [0041774402](https://linux-hardware.org/?probe=0041774402) | Aug 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YJC... | [ce2df1e866](https://linux-hardware.org/?probe=ce2df1e866) | Jul 18, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [87edfcaadf](https://linux-hardware.org/?probe=87edfcaadf) | Jul 09, 2022 |
| Lenovo        | ThinkPad S2 20GJA00S00      | [44eb58334d](https://linux-hardware.org/?probe=44eb58334d) | Jun 24, 2022 |
| LG Electro... | 14Z90N-VA76K                | [9e606a176f](https://linux-hardware.org/?probe=9e606a176f) | Jun 24, 2022 |
| Samsung       | 670Z5E                      | [95ec23c2e9](https://linux-hardware.org/?probe=95ec23c2e9) | Jun 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | [014c9a184e](https://linux-hardware.org/?probe=014c9a184e) | Jun 06, 2022 |
| LG Electro... | Z360-GH6SK                  | [cb91c2c2bd](https://linux-hardware.org/?probe=cb91c2c2bd) | Jun 02, 2022 |
| HP            | Spectre 13 x2 PC            | [9b67243691](https://linux-hardware.org/?probe=9b67243691) | May 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4f941ba9fe](https://linux-hardware.org/?probe=4f941ba9fe) | May 24, 2022 |
| Dell          | Vostro 3500                 | [617edab20c](https://linux-hardware.org/?probe=617edab20c) | May 20, 2022 |
| LG Electro... | 15Z990-HA50K                | [e5cf57d2f4](https://linux-hardware.org/?probe=e5cf57d2f4) | May 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [7286fd4e36](https://linux-hardware.org/?probe=7286fd4e36) | May 11, 2022 |
| Toshiba       | Satellite P50-B-103         | [6df44e9098](https://linux-hardware.org/?probe=6df44e9098) | Apr 29, 2022 |
| Teclast       | tPAD                        | [2b86292373](https://linux-hardware.org/?probe=2b86292373) | Apr 20, 2022 |
| Wolfnfox      | WF-TBAT                     | [7d04cc8361](https://linux-hardware.org/?probe=7d04cc8361) | Apr 13, 2022 |
| Teclast       | tPAD                        | [a9f93e289b](https://linux-hardware.org/?probe=a9f93e289b) | Apr 13, 2022 |
| MECHREVO      | Taitan Series GM7TG0M       | [948d29a218](https://linux-hardware.org/?probe=948d29a218) | Apr 10, 2022 |
| Teclast       | tPAD                        | [5eddc816df](https://linux-hardware.org/?probe=5eddc816df) | Apr 07, 2022 |
| HP            | Stream Notebook PC 13       | [1874ac7edf](https://linux-hardware.org/?probe=1874ac7edf) | Apr 03, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [f22fa67906](https://linux-hardware.org/?probe=f22fa67906) | Apr 01, 2022 |
| HP            | Stream Notebook PC 11       | [8fc09857a6](https://linux-hardware.org/?probe=8fc09857a6) | Apr 01, 2022 |
| Intel         | powered classmate PC        | [8ce4fa1757](https://linux-hardware.org/?probe=8ce4fa1757) | Apr 01, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6c36c54313](https://linux-hardware.org/?probe=6c36c54313) | Mar 31, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a8cacc7845](https://linux-hardware.org/?probe=a8cacc7845) | Mar 27, 2022 |
| MSI           | GF75 Thin 9SCXR             | [df19241968](https://linux-hardware.org/?probe=df19241968) | Mar 20, 2022 |
| MSI           | GF75 Thin 9SCXR             | [b3458eda8f](https://linux-hardware.org/?probe=b3458eda8f) | Mar 14, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [f86d99b8a1](https://linux-hardware.org/?probe=f86d99b8a1) | Feb 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [95ff70277e](https://linux-hardware.org/?probe=95ff70277e) | Feb 24, 2022 |
| Dell          | Inspiron 15 5510            | [bb04a03420](https://linux-hardware.org/?probe=bb04a03420) | Feb 23, 2022 |
| Dell          | Inspiron 15 5510            | [38ad42c186](https://linux-hardware.org/?probe=38ad42c186) | Feb 22, 2022 |
| LG Electro... | 17UD70P-PX76K               | [968b189e38](https://linux-hardware.org/?probe=968b189e38) | Feb 21, 2022 |
| LG Electro... | 17UD70P-PX76K               | [d8f6d95994](https://linux-hardware.org/?probe=d8f6d95994) | Feb 14, 2022 |
| HANSUNG CO... | EX58                        | [7c2a023530](https://linux-hardware.org/?probe=7c2a023530) | Feb 10, 2022 |
| HP            | Spectre 13 x2 PC            | [ed95e4c1c7](https://linux-hardware.org/?probe=ed95e4c1c7) | Feb 09, 2022 |
| HP            | Spectre 13 x2 PC            | [a597b083c9](https://linux-hardware.org/?probe=a597b083c9) | Feb 08, 2022 |
| Google        | Ampton                      | [0f1564bb4a](https://linux-hardware.org/?probe=0f1564bb4a) | Feb 06, 2022 |
| Apple         | MacBookPro5,3               | [7742fa4642](https://linux-hardware.org/?probe=7742fa4642) | Feb 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [65a6ca3880](https://linux-hardware.org/?probe=65a6ca3880) | Feb 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [144717a1f1](https://linux-hardware.org/?probe=144717a1f1) | Feb 04, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [7f9793a709](https://linux-hardware.org/?probe=7f9793a709) | Jan 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [2c22ac6a5f](https://linux-hardware.org/?probe=2c22ac6a5f) | Jan 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [882dab7b0e](https://linux-hardware.org/?probe=882dab7b0e) | Jan 22, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [c081d60b2a](https://linux-hardware.org/?probe=c081d60b2a) | Jan 22, 2022 |
| Apple         | MacBookPro5,5               | [11d1870f98](https://linux-hardware.org/?probe=11d1870f98) | Jan 21, 2022 |
| LG Electro... | 17UD70P-PX76K               | [d0d21d2892](https://linux-hardware.org/?probe=d0d21d2892) | Jan 18, 2022 |
| LG Electro... | 16ZD90P-GX7LK               | [0870fd8772](https://linux-hardware.org/?probe=0870fd8772) | Dec 29, 2021 |
| Lenovo        | G480 20149                  | [08a0d07d28](https://linux-hardware.org/?probe=08a0d07d28) | Dec 28, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [a8fbe33d19](https://linux-hardware.org/?probe=a8fbe33d19) | Dec 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [ff620ffdcd](https://linux-hardware.org/?probe=ff620ffdcd) | Dec 07, 2021 |
| Jooyontech... | J3GP Pro                    | [6f13d68344](https://linux-hardware.org/?probe=6f13d68344) | Dec 04, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | [c7cc850f29](https://linux-hardware.org/?probe=c7cc850f29) | Dec 03, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | [901fdc3726](https://linux-hardware.org/?probe=901fdc3726) | Dec 03, 2021 |
| LG Electro... | 17UD70P-PX76K               | [b4c7522ea3](https://linux-hardware.org/?probe=b4c7522ea3) | Nov 15, 2021 |
| LG Electro... | 15Z990-HA50K                | [6f5255e0f2](https://linux-hardware.org/?probe=6f5255e0f2) | Nov 01, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [70074ebee1](https://linux-hardware.org/?probe=70074ebee1) | Nov 01, 2021 |
| ASUSTek       | X556URK                     | [212240b258](https://linux-hardware.org/?probe=212240b258) | Oct 29, 2021 |
| LG Electro... | 17ZD90P-GX7LK               | [23aa2c83ae](https://linux-hardware.org/?probe=23aa2c83ae) | Oct 27, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2f6634b953](https://linux-hardware.org/?probe=2f6634b953) | Oct 22, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fb8b55960a](https://linux-hardware.org/?probe=fb8b55960a) | Oct 20, 2021 |
| Lenovo        | ThinkPad W530 24475HU       | [b8973b3b0a](https://linux-hardware.org/?probe=b8973b3b0a) | Oct 02, 2021 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [e93b95fc3c](https://linux-hardware.org/?probe=e93b95fc3c) | Sep 30, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | [fbc7a613a6](https://linux-hardware.org/?probe=fbc7a613a6) | Sep 29, 2021 |
| HANSUNG CO... | TFX4150H                    | [11f2fbef85](https://linux-hardware.org/?probe=11f2fbef85) | Sep 29, 2021 |
| ASUSTek       | U36JC                       | [c6e87f1fb7](https://linux-hardware.org/?probe=c6e87f1fb7) | Sep 23, 2021 |
| Samsung       | 730QCJ/730QCR               | [54cd6887df](https://linux-hardware.org/?probe=54cd6887df) | Sep 21, 2021 |
| Clevo         | M740T/M760T                 | [7731b8340f](https://linux-hardware.org/?probe=7731b8340f) | Sep 17, 2021 |
| Samsung       | 400B4C/400B5C/200B4C/200... | [581ab7ecde](https://linux-hardware.org/?probe=581ab7ecde) | Sep 17, 2021 |
| HP            | Pavilion Laptop 15z-eh00... | [33233b370e](https://linux-hardware.org/?probe=33233b370e) | Aug 30, 2021 |
| LG Electro... | 14Z90N-VA76K                | [df36a7a61c](https://linux-hardware.org/?probe=df36a7a61c) | Aug 22, 2021 |
| Lenovo        | XiaoXin Air 13IWL 81J8      | [e68dfe0824](https://linux-hardware.org/?probe=e68dfe0824) | Aug 19, 2021 |
| Apple         | MacBookPro15,2              | [c722c00c56](https://linux-hardware.org/?probe=c722c00c56) | Aug 18, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e47beb0587](https://linux-hardware.org/?probe=e47beb0587) | Aug 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e7997203d4](https://linux-hardware.org/?probe=e7997203d4) | Aug 11, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [3147760301](https://linux-hardware.org/?probe=3147760301) | Aug 07, 2021 |
| Dell          | XPS 13 7390                 | [901bcb991b](https://linux-hardware.org/?probe=901bcb991b) | Jul 31, 2021 |
| LG Electro... | 17UD70P-PX76K               | [dc6d809e73](https://linux-hardware.org/?probe=dc6d809e73) | Jul 23, 2021 |
| LG Electro... | 17UD70P-PX76K               | [c0869b1919](https://linux-hardware.org/?probe=c0869b1919) | Jul 23, 2021 |
| HP            | OMEN by Laptop              | [2392366002](https://linux-hardware.org/?probe=2392366002) | Jul 16, 2021 |
| Dell          | Inspiron 14 Plus 7440       | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [fd48c4cd51](https://linux-hardware.org/?probe=fd48c4cd51) | Jul 02, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [d2f1ec957f](https://linux-hardware.org/?probe=d2f1ec957f) | Jun 27, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [9c2b77b3c6](https://linux-hardware.org/?probe=9c2b77b3c6) | Jun 24, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [99b25335b3](https://linux-hardware.org/?probe=99b25335b3) | Jun 22, 2021 |
| MSI           | GF63 Thin 9SC               | [98faadcfa3](https://linux-hardware.org/?probe=98faadcfa3) | Jun 10, 2021 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [5742c8e4e5](https://linux-hardware.org/?probe=5742c8e4e5) | May 28, 2021 |
| Lenovo        | G500 20236                  | [2aca6cd805](https://linux-hardware.org/?probe=2aca6cd805) | May 27, 2021 |
| Dell          | Latitude E6400              | [2a4c5f6eec](https://linux-hardware.org/?probe=2a4c5f6eec) | May 25, 2021 |
| Samsung       | R440/R480                   | [777c05d80b](https://linux-hardware.org/?probe=777c05d80b) | May 19, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [15a742842f](https://linux-hardware.org/?probe=15a742842f) | May 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f3cb68f8cf](https://linux-hardware.org/?probe=f3cb68f8cf) | May 13, 2021 |
| HP            | EliteBook 8540p (WQ983PA... | [28b1df49ae](https://linux-hardware.org/?probe=28b1df49ae) | May 11, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | [035481a413](https://linux-hardware.org/?probe=035481a413) | May 05, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [473f17b0f1](https://linux-hardware.org/?probe=473f17b0f1) | May 01, 2021 |
| LG Electro... | 15ND530-GX30K               | [9d700ce0b6](https://linux-hardware.org/?probe=9d700ce0b6) | Apr 30, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [84f31a5fd7](https://linux-hardware.org/?probe=84f31a5fd7) | Apr 28, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | [410e4fd232](https://linux-hardware.org/?probe=410e4fd232) | Apr 22, 2021 |
| HP            | Stream Notebook PC 13       | [0bf3f6f761](https://linux-hardware.org/?probe=0bf3f6f761) | Apr 15, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [c5e7a3d16e](https://linux-hardware.org/?probe=c5e7a3d16e) | Apr 09, 2021 |
| Notebook      | NL5xRU                      | [7cac175bde](https://linux-hardware.org/?probe=7cac175bde) | Apr 07, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [51931e3821](https://linux-hardware.org/?probe=51931e3821) | Apr 05, 2021 |
| Samsung       | 270E5J/2570EJ               | [b36716f462](https://linux-hardware.org/?probe=b36716f462) | Apr 02, 2021 |
| Samsung       | 400B4B/400B5B/200B4B/200... | [af785987c5](https://linux-hardware.org/?probe=af785987c5) | Mar 29, 2021 |
| LG Electro... | Z435-GE40K                  | [41dfc50f20](https://linux-hardware.org/?probe=41dfc50f20) | Mar 27, 2021 |
| Alienware     | m15 R4                      | [33977ceca8](https://linux-hardware.org/?probe=33977ceca8) | Mar 08, 2021 |
| Notebook      | W330SU2                     | [e5e71a4e94](https://linux-hardware.org/?probe=e5e71a4e94) | Mar 05, 2021 |
| Dell          | Inspiron 5590               | [94e3d38a99](https://linux-hardware.org/?probe=94e3d38a99) | Mar 04, 2021 |
| Notebook      | N650DU                      | [beef9a4540](https://linux-hardware.org/?probe=beef9a4540) | Feb 24, 2021 |
| HP            | Pavilion dv3                | [d563465019](https://linux-hardware.org/?probe=d563465019) | Jan 23, 2021 |
| HP            | Pavilion dv3                | [7140d63f79](https://linux-hardware.org/?probe=7140d63f79) | Jan 16, 2021 |
| LG Electro... | 13Z940-MF6BL                | [ee9f312333](https://linux-hardware.org/?probe=ee9f312333) | Jan 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [28d2ddf944](https://linux-hardware.org/?probe=28d2ddf944) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming FA706II_FA706... | [cbc872e471](https://linux-hardware.org/?probe=cbc872e471) | Dec 29, 2020 |
| HANSUNG CO... | TFX5470H                    | [4f038027ac](https://linux-hardware.org/?probe=4f038027ac) | Dec 27, 2020 |
| HANSUNG CO... | TFX5470H                    | [659c45927e](https://linux-hardware.org/?probe=659c45927e) | Dec 26, 2020 |
| HP            | Pavilion g6                 | [9b2e1ccb17](https://linux-hardware.org/?probe=9b2e1ccb17) | Dec 15, 2020 |
| HP            | Pavilion g6                 | [01bd113f0d](https://linux-hardware.org/?probe=01bd113f0d) | Dec 15, 2020 |
| MSI           | PS42 Modern 8MO             | [c469679bd0](https://linux-hardware.org/?probe=c469679bd0) | Dec 14, 2020 |
| HP            | ProBook 635 Aero G7 Note... | [9ff7890a24](https://linux-hardware.org/?probe=9ff7890a24) | Dec 11, 2020 |
| Samsung       | 760XBE                      | [7b117d1e93](https://linux-hardware.org/?probe=7b117d1e93) | Dec 08, 2020 |
| Samsung       | R440/R480                   | [2c57659a41](https://linux-hardware.org/?probe=2c57659a41) | Dec 06, 2020 |
| Acer          | Swift SF314-54              | [e387afac15](https://linux-hardware.org/?probe=e387afac15) | Nov 29, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [b6570c8388](https://linux-hardware.org/?probe=b6570c8388) | Nov 28, 2020 |
| Apple         | MacBookPro10,1              | [ecfaa7232b](https://linux-hardware.org/?probe=ecfaa7232b) | Nov 28, 2020 |
| HP            | EliteBook 840 G1            | [eb842cd3c4](https://linux-hardware.org/?probe=eb842cd3c4) | Nov 25, 2020 |
| HP            | EliteBook 840 G1            | [2a9cc167d3](https://linux-hardware.org/?probe=2a9cc167d3) | Nov 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| Samsung       | R59P/R60P/R61P              | [e4a465ff4c](https://linux-hardware.org/?probe=e4a465ff4c) | Nov 15, 2020 |
| Samsung       | R59P/R60P/R61P              | [8a39cadb17](https://linux-hardware.org/?probe=8a39cadb17) | Nov 14, 2020 |
| Samsung       | SX11S                       | [7946db3be4](https://linux-hardware.org/?probe=7946db3be4) | Nov 05, 2020 |
| Lenovo        | ThinkPad T580 20L9S06H00    | [4cda554e60](https://linux-hardware.org/?probe=4cda554e60) | Oct 31, 2020 |
| LG Electro... | 14ZB990-GP70ML              | [7184b7e890](https://linux-hardware.org/?probe=7184b7e890) | Oct 29, 2020 |
| HANSUNG CO... | TFX5470H                    | [7a0c7ef25d](https://linux-hardware.org/?probe=7a0c7ef25d) | Oct 22, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [7f2d533ddf](https://linux-hardware.org/?probe=7f2d533ddf) | Oct 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [57c9a2fdbb](https://linux-hardware.org/?probe=57c9a2fdbb) | Oct 12, 2020 |
| Acer          | Aspire A514-52              | [151c57e477](https://linux-hardware.org/?probe=151c57e477) | Oct 11, 2020 |
| Lenovo        | ThinkPad E595 20NFS01P00    | [5cce7e56d5](https://linux-hardware.org/?probe=5cce7e56d5) | Oct 02, 2020 |
| MSI           | MS-16F1                     | [94a744ecb7](https://linux-hardware.org/?probe=94a744ecb7) | Oct 01, 2020 |
| MSI           | GE75 Raider 10SF            | [c5f31d8ff8](https://linux-hardware.org/?probe=c5f31d8ff8) | Sep 21, 2020 |
| MSI           | GE75 Raider 10SF            | [80b54a584c](https://linux-hardware.org/?probe=80b54a584c) | Sep 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [335490808b](https://linux-hardware.org/?probe=335490808b) | Sep 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [611b4d4515](https://linux-hardware.org/?probe=611b4d4515) | Sep 12, 2020 |
| Samsung       | SX11S                       | [de5f3f5244](https://linux-hardware.org/?probe=de5f3f5244) | Sep 10, 2020 |
| Dell          | XPS 15 7590                 | [0ed21172b2](https://linux-hardware.org/?probe=0ed21172b2) | Sep 07, 2020 |
| HP            | Laptop 14s-cf1xxx           | [56e8c74784](https://linux-hardware.org/?probe=56e8c74784) | Sep 05, 2020 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [5b29fd8262](https://linux-hardware.org/?probe=5b29fd8262) | Sep 05, 2020 |
| HP            | Laptop 15s-du0xxx           | [226702f09a](https://linux-hardware.org/?probe=226702f09a) | Sep 05, 2020 |
| LG Electro... | 15ND530-GX30K               | [8f8a5ce10c](https://linux-hardware.org/?probe=8f8a5ce10c) | Sep 04, 2020 |
| Lenovo        | ThinkPad X390 20SCCTO1WW    | [765a0cde4c](https://linux-hardware.org/?probe=765a0cde4c) | Sep 03, 2020 |
| HP            | Laptop 15s-du0xxx           | [2ef3a6b6c8](https://linux-hardware.org/?probe=2ef3a6b6c8) | Sep 03, 2020 |
| Acer          | Swift SF315-41              | [c57a2c8249](https://linux-hardware.org/?probe=c57a2c8249) | Aug 26, 2020 |
| LG Electro... | A520-DEHRK                  | [33e6f6950c](https://linux-hardware.org/?probe=33e6f6950c) | Aug 20, 2020 |
| LG Electro... | ZD360-GD30K                 | [5f695a5cfd](https://linux-hardware.org/?probe=5f695a5cfd) | Aug 19, 2020 |
| Lenovo        | ThinkPad L420 7829AZ2       | [af5c485d91](https://linux-hardware.org/?probe=af5c485d91) | Aug 17, 2020 |
| ASUSTek       | UX31E                       | [107d53bd73](https://linux-hardware.org/?probe=107d53bd73) | Aug 14, 2020 |
| Lenovo        | ThinkPad Edge E440 20C50... | [e2a554e507](https://linux-hardware.org/?probe=e2a554e507) | Aug 11, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [4657a3e758](https://linux-hardware.org/?probe=4657a3e758) | Aug 11, 2020 |
| Lenovo        | ThinkPad T420s 417429U      | [a0cc9e062e](https://linux-hardware.org/?probe=a0cc9e062e) | Aug 09, 2020 |
| MSI           | GX60 3CC                    | [dabfcf887e](https://linux-hardware.org/?probe=dabfcf887e) | Aug 05, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [806b0f6ffc](https://linux-hardware.org/?probe=806b0f6ffc) | Aug 04, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [03dcb81800](https://linux-hardware.org/?probe=03dcb81800) | Aug 04, 2020 |
| LG Electro... | 14ZB990-GP70ML              | [953e68f29d](https://linux-hardware.org/?probe=953e68f29d) | Jul 29, 2020 |
| Samsung       | X120/X170/X171              | [d52c424e0f](https://linux-hardware.org/?probe=d52c424e0f) | Jul 12, 2020 |
| MSI           | PS63 Modern 8RC             | [1f2f8bb2cf](https://linux-hardware.org/?probe=1f2f8bb2cf) | Jul 06, 2020 |
| MSI           | PS63 Modern 8RC             | [ed2dc1f4eb](https://linux-hardware.org/?probe=ed2dc1f4eb) | Jul 05, 2020 |
| Sony          | SVF1421ESGW                 | [025b1a05fe](https://linux-hardware.org/?probe=025b1a05fe) | Jun 29, 2020 |
| ASUSTek       | X553SA                      | [de56d8fe26](https://linux-hardware.org/?probe=de56d8fe26) | Jun 23, 2020 |
| MSI           | GX60 3CC                    | [41702d8f8c](https://linux-hardware.org/?probe=41702d8f8c) | Jun 14, 2020 |
| MSI           | GX60 3CC                    | [16345ce4e3](https://linux-hardware.org/?probe=16345ce4e3) | Jun 14, 2020 |
| TG            | NXI-A7000 Series            | [20018e6c2a](https://linux-hardware.org/?probe=20018e6c2a) | Jun 07, 2020 |
| Dell          | G3 3579                     | [f21ec2528f](https://linux-hardware.org/?probe=f21ec2528f) | Jun 06, 2020 |
| Lenovo        | ThinkPad E495 20NES0WU00    | [bd7072c5e9](https://linux-hardware.org/?probe=bd7072c5e9) | May 27, 2020 |
| HP            | Laptop 15-db1xxx            | [229612b5fa](https://linux-hardware.org/?probe=229612b5fa) | May 26, 2020 |
| LG Electro... | 17UD790-PX76K               | [ac4f8e9cc6](https://linux-hardware.org/?probe=ac4f8e9cc6) | May 24, 2020 |
| LG Electro... | 17UD790-PX76K               | [9bb4fea940](https://linux-hardware.org/?probe=9bb4fea940) | May 24, 2020 |
| HP            | Laptop 15-db1xxx            | [65f85ef8e9](https://linux-hardware.org/?probe=65f85ef8e9) | May 20, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b3a561d5db](https://linux-hardware.org/?probe=b3a561d5db) | May 20, 2020 |
| MSI           | Prestige 15 A10SC           | [69c9f3bce6](https://linux-hardware.org/?probe=69c9f3bce6) | May 17, 2020 |
| Samsung       | 570Z5E/580Z5E               | [435579b481](https://linux-hardware.org/?probe=435579b481) | May 16, 2020 |
| Samsung       | 570Z5E/580Z5E               | [5e2ed0ac77](https://linux-hardware.org/?probe=5e2ed0ac77) | May 16, 2020 |
| LG Electro... | 14ZB990-GP70ML              | [dc05f2344d](https://linux-hardware.org/?probe=dc05f2344d) | May 16, 2020 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [5919a15425](https://linux-hardware.org/?probe=5919a15425) | May 11, 2020 |
| Lenovo        | ThinkPad X220 4290P39       | [1b5c469306](https://linux-hardware.org/?probe=1b5c469306) | May 02, 2020 |
| Dell          | XPS 15 7590                 | [0bbf773840](https://linux-hardware.org/?probe=0bbf773840) | Apr 27, 2020 |
| Dell          | XPS 15 7590                 | [5348bea534](https://linux-hardware.org/?probe=5348bea534) | Apr 27, 2020 |
| Lenovo        | ThinkPad X230 2325KZ5       | [150d9801f0](https://linux-hardware.org/?probe=150d9801f0) | Apr 21, 2020 |
| Lenovo        | ThinkPad E495 20NES0WU00    | [fb49bbe9f1](https://linux-hardware.org/?probe=fb49bbe9f1) | Apr 18, 2020 |
| Dell          | Latitude D630               | [0540c0a191](https://linux-hardware.org/?probe=0540c0a191) | Apr 15, 2020 |
| HP            | Pavilion Gaming Notebook    | [4d5a5a3a34](https://linux-hardware.org/?probe=4d5a5a3a34) | Apr 14, 2020 |
| LG Electro... | R490-KR6WK                  | [b0c23e23f7](https://linux-hardware.org/?probe=b0c23e23f7) | Mar 21, 2020 |
| HP            | Pavilion dv7                | [61bbb3da8a](https://linux-hardware.org/?probe=61bbb3da8a) | Mar 12, 2020 |
| LG Electro... | A505-K.AFC4L                | [33b72b423b](https://linux-hardware.org/?probe=33b72b423b) | Feb 26, 2020 |
| Toshiba       | Satellite L655              | [8212e2eb65](https://linux-hardware.org/?probe=8212e2eb65) | Feb 13, 2020 |
| MSI           | Prestige 14 A10SC           | [00af81dd32](https://linux-hardware.org/?probe=00af81dd32) | Feb 12, 2020 |
| MSI           | Prestige 14 A10SC           | [dac2e1709e](https://linux-hardware.org/?probe=dac2e1709e) | Feb 12, 2020 |
| MSI           | GF63 Thin 9SC               | [47b9bc192c](https://linux-hardware.org/?probe=47b9bc192c) | Jan 29, 2020 |
| MSI           | GF63 Thin 9SC               | [21dbcd5aca](https://linux-hardware.org/?probe=21dbcd5aca) | Jan 28, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [6515ce1c97](https://linux-hardware.org/?probe=6515ce1c97) | Jan 23, 2020 |
| HP            | ProBook 453                 | [ad3d1ff0fc](https://linux-hardware.org/?probe=ad3d1ff0fc) | Dec 27, 2019 |
| Lenovo        | ThinkPad E565 20EYA007KD    | [c1c9dd614a](https://linux-hardware.org/?probe=c1c9dd614a) | Dec 17, 2019 |
| HP            | Laptop 14s-cf1xxx           | [61765ee913](https://linux-hardware.org/?probe=61765ee913) | Dec 11, 2019 |
| HP            | Laptop 14s-cf1xxx           | [fa008b24fc](https://linux-hardware.org/?probe=fa008b24fc) | Dec 11, 2019 |
| HP            | Pavilion 15                 | [5f9b510e87](https://linux-hardware.org/?probe=5f9b510e87) | Oct 28, 2019 |
| MSI           | MS-1675                     | [c5bf6f209a](https://linux-hardware.org/?probe=c5bf6f209a) | Sep 07, 2019 |
| MSI           | MS-1675                     | [be1db420ea](https://linux-hardware.org/?probe=be1db420ea) | Sep 07, 2019 |
| AMI           | Cherry Trail CR             | [caaebe3071](https://linux-hardware.org/?probe=caaebe3071) | Sep 01, 2019 |
| AMI           | Cherry Trail CR             | [5637a7d5ca](https://linux-hardware.org/?probe=5637a7d5ca) | Sep 01, 2019 |
| Lenovo        | U41-70 80JV                 | [0af65c15a0](https://linux-hardware.org/?probe=0af65c15a0) | Aug 30, 2019 |
| IMUZ          | StormBook 15                | [daf3b9ea48](https://linux-hardware.org/?probe=daf3b9ea48) | Aug 07, 2019 |
| Samsung       | 800G5M/800G5W               | [01cb2e9401](https://linux-hardware.org/?probe=01cb2e9401) | May 22, 2019 |
| HP            | Laptop 15-db1xxx            | [e318a9dac5](https://linux-hardware.org/?probe=e318a9dac5) | May 10, 2019 |
| Sony          | VPCEA36FK                   | [6c4b2a047b](https://linux-hardware.org/?probe=6c4b2a047b) | May 01, 2019 |
| Dell          | Inspiron 7559               | [fb5730a29c](https://linux-hardware.org/?probe=fb5730a29c) | Apr 17, 2019 |
| Apple         | MacBookPro14,1              | [606c70c0db](https://linux-hardware.org/?probe=606c70c0db) | Apr 15, 2019 |
| Dell          | Inspiron 7570               | [f46c9c93f9](https://linux-hardware.org/?probe=f46c9c93f9) | Apr 12, 2019 |
| Dell          | Inspiron 7570               | [e1c522656b](https://linux-hardware.org/?probe=e1c522656b) | Apr 12, 2019 |
| Samsung       | 905S3G/906S3G/915S3G        | [8e21d7bf0c](https://linux-hardware.org/?probe=8e21d7bf0c) | Mar 30, 2019 |
| Lenovo        | ThinkPad P52s 20LBCTO1WW    | [ed9f709e73](https://linux-hardware.org/?probe=ed9f709e73) | Feb 20, 2019 |
| Samsung       | RC420/RC520/RC720           | [4a0abda7de](https://linux-hardware.org/?probe=4a0abda7de) | Dec 14, 2018 |
| AVERATEC      | 6600                        | [a55a983b35](https://linux-hardware.org/?probe=a55a983b35) | Nov 11, 2018 |
| AVERATEC      | 6600                        | [8ca54d992c](https://linux-hardware.org/?probe=8ca54d992c) | Nov 11, 2018 |
| Dell          | XPS 15 9560                 | [d5d9e2cef1](https://linux-hardware.org/?probe=d5d9e2cef1) | Nov 04, 2018 |
| LG Electro... | R510                        | [f7b3f1d4a5](https://linux-hardware.org/?probe=f7b3f1d4a5) | Oct 13, 2018 |
| ASUSTek       | N56JR                       | [27253306bc](https://linux-hardware.org/?probe=27253306bc) | Dec 28, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 57        | 16.52%  |
| Ubuntu 22.04      | 30        | 8.7%    |
| Ubuntu 18.04      | 21        | 6.09%   |
| Arch Rolling      | 11        | 3.19%   |
| HamoniKR 7.0      | 9         | 2.61%   |
| Gooroom           | 8         | 2.32%   |
| Ubuntu 21.10      | 7         | 2.03%   |
| Debian 12         | 7         | 2.03%   |
| Debian 11         | 7         | 2.03%   |
| Fedora 38         | 6         | 1.74%   |
| Arch              | 6         | 1.74%   |
| Fedora 40         | 5         | 1.45%   |
| Fedora 39         | 5         | 1.45%   |
| Zorin 16          | 4         | 1.16%   |
| Ubuntu 24.04      | 4         | 1.16%   |
| Ubuntu 23.10      | 4         | 1.16%   |
| Linux Mint 20.3   | 4         | 1.16%   |
| Linux Mint 20.1   | 4         | 1.16%   |
| Fedora 37         | 4         | 1.16%   |
| Fedora 36         | 4         | 1.16%   |
| Fedora 32         | 4         | 1.16%   |
| Ubuntu 19.10      | 3         | 0.87%   |
| Ubuntu 19.04      | 3         | 0.87%   |
| ROSA R11          | 3         | 0.87%   |
| OpenMandriva 4.2  | 3         | 0.87%   |
| Kubuntu 22.04     | 3         | 0.87%   |
| HamoniKR 4.0      | 3         | 0.87%   |
| Fedora 34         | 3         | 0.87%   |
| Debian 10         | 3         | 0.87%   |
| CentOS 8          | 3         | 0.87%   |
| Zorin 17          | 2         | 0.58%   |
| Zorin 15          | 2         | 0.58%   |
| Xubuntu 22.04     | 2         | 0.58%   |
| Ubuntu MATE 18.04 | 2         | 0.58%   |
| Ubuntu 22.10      | 2         | 0.58%   |
| SteamOS 3.5.19    | 2         | 0.58%   |
| SteamOS 3.4.4     | 2         | 0.58%   |
| ROSA R10          | 2         | 0.58%   |
| RHEL 9            | 2         | 0.58%   |
| Pop!_OS 21.10     | 2         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 132       | 39.64%  |
| Fedora        | 31        | 9.31%   |
| Debian        | 18        | 5.41%   |
| Linux Mint    | 15        | 4.5%    |
| Arch          | 15        | 4.5%    |
| HamoniKR      | 14        | 4.2%    |
| OpenMandriva  | 10        | 3%      |
| Manjaro       | 9         | 2.7%    |
| Gooroom       | 9         | 2.7%    |
| Zorin         | 8         | 2.4%    |
| SteamOS       | 8         | 2.4%    |
| Kubuntu       | 7         | 2.1%    |
| ROSA          | 6         | 1.8%    |
| No1 Linux     | 5         | 1.5%    |
| Endless       | 5         | 1.5%    |
| Pop!_OS       | 4         | 1.2%    |
| KDE neon      | 4         | 1.2%    |
| CentOS        | 4         | 1.2%    |
| Xubuntu       | 3         | 0.9%    |
| EndeavourOS   | 3         | 0.9%    |
| Ubuntu Unity  | 2         | 0.6%    |
| Ubuntu MATE   | 2         | 0.6%    |
| RHEL          | 2         | 0.6%    |
| LMDE          | 2         | 0.6%    |
| Kali          | 2         | 0.6%    |
| ArcoLinux     | 2         | 0.6%    |
| Xero          | 1         | 0.3%    |
| Ubuntu Budgie | 1         | 0.3%    |
| Trisquel      | 1         | 0.3%    |
| openSUSE      | 1         | 0.3%    |
| Lubuntu       | 1         | 0.3%    |
| Gentoo        | 1         | 0.3%    |
| Garuda Linux  | 1         | 0.3%    |
| Elementary    | 1         | 0.3%    |
| BigLinux      | 1         | 0.3%    |
| Alpine        | 1         | 0.3%    |
| AlmaLinux     | 1         | 0.3%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Notebooks | Percent |
|--------------------------------|-----------|---------|
| 5.15.0-53-generic              | 5         | 1.39%   |
| 5.10.0-19-amd64                | 5         | 1.39%   |
| 5.4.0-42-generic               | 4         | 1.11%   |
| 5.19.0-45-generic              | 4         | 1.11%   |
| 5.15.0-58-generic              | 4         | 1.11%   |
| 5.15.0-56-generic              | 4         | 1.11%   |
| 5.10.0-17-amd64                | 4         | 1.11%   |
| 4.19.0-9-amd64                 | 4         | 1.11%   |
| 6.1.52-valve16-1-neptune-61    | 3         | 0.83%   |
| 5.8.0-43-generic               | 3         | 0.83%   |
| 5.4.0-58-generic               | 3         | 0.83%   |
| 5.4.0-26-generic               | 3         | 0.83%   |
| 5.3.0-40-generic               | 3         | 0.83%   |
| 5.19.15-201.fc36.x86_64        | 3         | 0.83%   |
| 5.15.0-88-generic              | 3         | 0.83%   |
| 5.15.0-122-generic             | 3         | 0.83%   |
| 5.13.0-valve36-1-neptune       | 3         | 0.83%   |
| 5.13.0-28-generic              | 3         | 0.83%   |
| 5.11.0-37-generic              | 3         | 0.83%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 3         | 0.83%   |
| 6.8.0-50-generic               | 2         | 0.55%   |
| 6.8.0-31-generic               | 2         | 0.55%   |
| 6.5.0-21-generic               | 2         | 0.55%   |
| 6.5.0-14-generic               | 2         | 0.55%   |
| 6.1.1-desktop-1omv2290         | 2         | 0.55%   |
| 6.1.0-25-amd64                 | 2         | 0.55%   |
| 5.8.4-200.fc32.x86_64          | 2         | 0.55%   |
| 5.8.0-53-generic               | 2         | 0.55%   |
| 5.4.0-81-generic               | 2         | 0.55%   |
| 5.4.0-56-generic               | 2         | 0.55%   |
| 5.4.0-48-generic               | 2         | 0.55%   |
| 5.4.0-39-generic               | 2         | 0.55%   |
| 5.4.0-33-generic               | 2         | 0.55%   |
| 5.4.0-31-generic               | 2         | 0.55%   |
| 5.4.0-29-generic               | 2         | 0.55%   |
| 5.4.0-150-generic              | 2         | 0.55%   |
| 5.3.0-46-generic               | 2         | 0.55%   |
| 5.19.0-46-generic              | 2         | 0.55%   |
| 5.19.0-43-generic              | 2         | 0.55%   |
| 5.18.5-1-MANJARO               | 2         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 14.53%  |
| 5.15.0  | 45        | 12.82%  |
| 5.13.0  | 17        | 4.84%   |
| 5.19.0  | 15        | 4.27%   |
| 5.8.0   | 12        | 3.42%   |
| 5.10.0  | 12        | 3.42%   |
| 6.5.0   | 10        | 2.85%   |
| 5.11.0  | 10        | 2.85%   |
| 4.15.0  | 10        | 2.85%   |
| 6.1.0   | 9         | 2.56%   |
| 5.3.0   | 9         | 2.56%   |
| 6.8.0   | 7         | 1.99%   |
| 5.0.0   | 7         | 1.99%   |
| 4.19.0  | 7         | 1.99%   |
| 4.18.0  | 7         | 1.99%   |
| 5.14.0  | 4         | 1.14%   |
| 6.2.0   | 3         | 0.85%   |
| 6.10.9  | 3         | 0.85%   |
| 6.1.52  | 3         | 0.85%   |
| 5.19.15 | 3         | 0.85%   |
| 6.6.9   | 2         | 0.57%   |
| 6.2.8   | 2         | 0.57%   |
| 6.11.0  | 2         | 0.57%   |
| 6.1.1   | 2         | 0.57%   |
| 6.0.0   | 2         | 0.57%   |
| 5.8.4   | 2         | 0.57%   |
| 5.18.5  | 2         | 0.57%   |
| 5.16.19 | 2         | 0.57%   |
| 5.15.11 | 2         | 0.57%   |
| 5.10.14 | 2         | 0.57%   |
| 4.9.60  | 2         | 0.57%   |
| 6.9.5   | 1         | 0.28%   |
| 6.8.9   | 1         | 0.28%   |
| 6.8.7   | 1         | 0.28%   |
| 6.8.6   | 1         | 0.28%   |
| 6.8.5   | 1         | 0.28%   |
| 6.7.6   | 1         | 0.28%   |
| 6.7.4   | 1         | 0.28%   |
| 6.7.1   | 1         | 0.28%   |
| 6.6.60  | 1         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 54        | 15.47%  |
| 5.15    | 53        | 15.19%  |
| 6.1     | 20        | 5.73%   |
| 5.19    | 20        | 5.73%   |
| 5.13    | 18        | 5.16%   |
| 5.8     | 16        | 4.58%   |
| 5.10    | 16        | 4.58%   |
| 5.11    | 15        | 4.3%    |
| 6.2     | 12        | 3.44%   |
| 6.8     | 11        | 3.15%   |
| 6.5     | 11        | 3.15%   |
| 4.15    | 11        | 3.15%   |
| 5.3     | 10        | 2.87%   |
| 4.19    | 8         | 2.29%   |
| 4.18    | 8         | 2.29%   |
| 5.0     | 7         | 2.01%   |
| 6.6     | 6         | 1.72%   |
| 6.0     | 6         | 1.72%   |
| 5.14    | 6         | 1.72%   |
| 5.16    | 5         | 1.43%   |
| 5.12    | 5         | 1.43%   |
| 6.7     | 3         | 0.86%   |
| 6.3     | 3         | 0.86%   |
| 6.11    | 3         | 0.86%   |
| 6.10    | 3         | 0.86%   |
| 5.18    | 3         | 0.86%   |
| 6.4     | 2         | 0.57%   |
| 6.12    | 2         | 0.57%   |
| 5.6     | 2         | 0.57%   |
| 4.9     | 2         | 0.57%   |
| 6.9     | 1         | 0.29%   |
| 5.9     | 1         | 0.29%   |
| 5.7     | 1         | 0.29%   |
| 5.5     | 1         | 0.29%   |
| 5.2     | 1         | 0.29%   |
| 5.17    | 1         | 0.29%   |
| 4.16    | 1         | 0.29%   |
| 3.10    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 320       | 98.77%  |
| i686    | 3         | 0.93%   |
| aarch64 | 1         | 0.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 178       | 53.61%  |
| KDE5             | 48        | 14.46%  |
| X-Cinnamon       | 23        | 6.93%   |
| Unknown          | 21        | 6.33%   |
| XFCE             | 10        | 3.01%   |
| GNOME Flashback  | 9         | 2.71%   |
| LXDE             | 8         | 2.41%   |
| Cinnamon         | 6         | 1.81%   |
| i3               | 5         | 1.51%   |
| MATE             | 4         | 1.2%    |
| KDE6             | 4         | 1.2%    |
| Unity            | 3         | 0.9%    |
| KDE4             | 3         | 0.9%    |
| KDE              | 3         | 0.9%    |
| LXQt             | 2         | 0.6%    |
| wayfire          | 1         | 0.3%    |
| sway             | 1         | 0.3%    |
| Pantheon         | 1         | 0.3%    |
| lightdm-xsession | 1         | 0.3%    |
| Budgie           | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 211       | 63.94%  |
| Wayland | 92        | 27.88%  |
| Unknown | 16        | 4.85%   |
| Tty     | 11        | 3.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 133       | 39.82%  |
| GDM     | 62        | 18.56%  |
| GDM3    | 53        | 15.87%  |
| SDDM    | 37        | 11.08%  |
| LightDM | 32        | 9.58%   |
| TDM     | 13        | 3.89%   |
| KDM     | 3         | 0.9%    |
| XDM     | 1         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ko_KR   | 147       | 44.28%  |
| en_US   | 126       | 37.95%  |
| Unknown | 29        | 8.73%   |
| C       | 10        | 3.01%   |
| zh_CN   | 4         | 1.2%    |
| en_CA   | 4         | 1.2%    |
| id_ID   | 2         | 0.6%    |
| fr_FR   | 2         | 0.6%    |
| vi_VN   | 1         | 0.3%    |
| pt_BR   | 1         | 0.3%    |
| en_NZ   | 1         | 0.3%    |
| en_GB   | 1         | 0.3%    |
| el_GR   | 1         | 0.3%    |
| de_DE   | 1         | 0.3%    |
| ba_RU   | 1         | 0.3%    |
| ar_EG   | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 222       | 68.31%  |
| BIOS | 103       | 31.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 240       | 72.73%  |
| Btrfs   | 46        | 13.94%  |
| Tmpfs   | 14        | 4.24%   |
| Xfs     | 11        | 3.33%   |
| Overlay | 8         | 2.42%   |
| Unknown | 6         | 1.82%   |
| Zfs     | 4         | 1.21%   |
| Rootfs  | 1         | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 183       | 55.62%  |
| Unknown | 126       | 38.3%   |
| MBR     | 20        | 6.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 305       | 93.56%  |
| Yes       | 21        | 6.44%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 219       | 66.97%  |
| Yes       | 108       | 33.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 73        | 22.53%  |
| Samsung Electronics | 42        | 12.96%  |
| Hewlett-Packard     | 40        | 12.35%  |
| ASUSTek Computer    | 36        | 11.11%  |
| LG Electronics      | 27        | 8.33%   |
| Dell                | 24        | 7.41%   |
| Apple               | 13        | 4.01%   |
| MSI                 | 12        | 3.7%    |
| Valve               | 7         | 2.16%   |
| Acer                | 6         | 1.85%   |
| HANSUNG COMPUTER    | 5         | 1.54%   |
| Notebook            | 4         | 1.23%   |
| Unknown             | 4         | 1.23%   |
| Toshiba             | 2         | 0.62%   |
| Razer               | 2         | 0.62%   |
| IMUZ                | 2         | 0.62%   |
| Google              | 2         | 0.62%   |
| Gigabyte Technology | 2         | 0.62%   |
| Wolfnfox            | 1         | 0.31%   |
| WEIPAI              | 1         | 0.31%   |
| TG                  | 1         | 0.31%   |
| Teclast             | 1         | 0.31%   |
| Sony                | 1         | 0.31%   |
| SLIMBOOK            | 1         | 0.31%   |
| Pine Microsystems   | 1         | 0.31%   |
| ONE-NETBOOK         | 1         | 0.31%   |
| MS                  | 1         | 0.31%   |
| MiTAC               | 1         | 0.31%   |
| MECHREVO            | 1         | 0.31%   |
| Jooyontech Computer | 1         | 0.31%   |
| Jooyon Tech         | 1         | 0.31%   |
| Intel               | 1         | 0.31%   |
| HUAWEI              | 1         | 0.31%   |
| Clevo               | 1         | 0.31%   |
| Chuwi               | 1         | 0.31%   |
| AVERATEC            | 1         | 0.31%   |
| ASRock              | 1         | 0.31%   |
| AMI                 | 1         | 0.31%   |
| Alienware           | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Valve Jupiter                            | 6         | 1.85%   |
| Samsung 950XCJ/951XCJ/950XCR             | 6         | 1.85%   |
| Unknown                                  | 4         | 1.23%   |
| Samsung 950XED                           | 3         | 0.93%   |
| Samsung 940XFG                           | 3         | 0.93%   |
| Samsung 760XDA                           | 3         | 0.93%   |
| Razer Blade 17 (2022) - RZ09-0423        | 2         | 0.62%   |
| Notebook N650DU                          | 2         | 0.62%   |
| Lenovo ThinkPad L14 Gen 1 20U5S01S00     | 2         | 0.62%   |
| Lenovo IdeaPad 5 14ALC05 82LM            | 2         | 0.62%   |
| Lenovo IdeaPad 3 15IIL05 81WE            | 2         | 0.62%   |
| Lenovo IdeaPad 3 14ALC6 82KT             | 2         | 0.62%   |
| HP Stream Notebook PC 13                 | 2         | 0.62%   |
| HP Pavilion g6                           | 2         | 0.62%   |
| HP Pavilion dv6                          | 2         | 0.62%   |
| HP Laptop 15-db1xxx                      | 2         | 0.62%   |
| HP EliteBook 865 16 inch G9 Notebook PC  | 2         | 0.62%   |
| HP EliteBook 855 G7 Notebook PC          | 2         | 0.62%   |
| HANSUNG COMPUTER TFX5470H                | 2         | 0.62%   |
| Dell XPS 15 7590                         | 2         | 0.62%   |
| Dell Inspiron 15 5510                    | 2         | 0.62%   |
| ASUS Zenbook UM3402YA_UM3402YA           | 2         | 0.62%   |
| ASUS X542UN                              | 2         | 0.62%   |
| ASUS VivoBook_ASUSLaptop S5402ZA_S5402ZA | 2         | 0.62%   |
| Apple MacBookPro16,1                     | 2         | 0.62%   |
| Wolfnfox WF-TBAT                         | 1         | 0.31%   |
| WEIPAI S15                               | 1         | 0.31%   |
| Valve Galileo                            | 1         | 0.31%   |
| Toshiba Satellite P50-B-103              | 1         | 0.31%   |
| Toshiba Satellite L655                   | 1         | 0.31%   |
| TG NXI-A7000 Series                      | 1         | 0.31%   |
| Teclast tPAD                             | 1         | 0.31%   |
| Sony VPCEA36FK                           | 1         | 0.31%   |
| SLIMBOOK PROX15-AMD                      | 1         | 0.31%   |
| Samsung X120/X170/X171                   | 1         | 0.31%   |
| Samsung SX11S                            | 1         | 0.31%   |
| Samsung RC420/RC520/RC720                | 1         | 0.31%   |
| Samsung R59P/R60P/R61P                   | 1         | 0.31%   |
| Samsung R530/R730                        | 1         | 0.31%   |
| Samsung R440/R480                        | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 41        | 12.65%  |
| Lenovo IdeaPad            | 19        | 5.86%   |
| HP Pavilion               | 12        | 3.7%    |
| ASUS VivoBook             | 12        | 3.7%    |
| Dell Inspiron             | 11        | 3.4%    |
| HP Laptop                 | 7         | 2.16%   |
| HP EliteBook              | 7         | 2.16%   |
| Dell XPS                  | 7         | 2.16%   |
| Valve Jupiter             | 6         | 1.85%   |
| Samsung 950XCJ            | 6         | 1.85%   |
| ASUS ROG                  | 5         | 1.54%   |
| Lenovo ThinkBook          | 4         | 1.23%   |
| HP Stream                 | 4         | 1.23%   |
| ASUS Zenbook              | 4         | 1.23%   |
| Unknown                   | 4         | 1.23%   |
| Samsung 950XED            | 3         | 0.93%   |
| Samsung 940XFG            | 3         | 0.93%   |
| Samsung 760XDA            | 3         | 0.93%   |
| Dell Latitude             | 3         | 0.93%   |
| Apple MacBookPro11        | 3         | 0.93%   |
| Acer Swift                | 3         | 0.93%   |
| Toshiba Satellite         | 2         | 0.62%   |
| Razer Blade               | 2         | 0.62%   |
| Notebook N650DU           | 2         | 0.62%   |
| MSI Prestige              | 2         | 0.62%   |
| Lenovo Legion             | 2         | 0.62%   |
| HP ProBook                | 2         | 0.62%   |
| HP OMEN                   | 2         | 0.62%   |
| HP ENVY                   | 2         | 0.62%   |
| HANSUNG COMPUTER TFX5470H | 2         | 0.62%   |
| ASUS X542UN               | 2         | 0.62%   |
| ASUS TUF                  | 2         | 0.62%   |
| ASUS ASUS                 | 2         | 0.62%   |
| Apple MacBookPro5         | 2         | 0.62%   |
| Apple MacBookPro16        | 2         | 0.62%   |
| Acer Aspire               | 2         | 0.62%   |
| Wolfnfox WF-TBAT          | 1         | 0.31%   |
| WEIPAI S15                | 1         | 0.31%   |
| Valve Galileo             | 1         | 0.31%   |
| TG NXI-A7000              | 1         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 50        | 15.43%  |
| 2021    | 45        | 13.89%  |
| 2022    | 35        | 10.8%   |
| 2019    | 30        | 9.26%   |
| 2018    | 23        | 7.1%    |
| 2023    | 17        | 5.25%   |
| 2014    | 17        | 5.25%   |
| 2013    | 17        | 5.25%   |
| 2017    | 15        | 4.63%   |
| 2011    | 13        | 4.01%   |
| 2012    | 12        | 3.7%    |
| 2016    | 11        | 3.4%    |
| 2008    | 11        | 3.4%    |
| 2010    | 8         | 2.47%   |
| 2009    | 6         | 1.85%   |
| 2015    | 5         | 1.54%   |
| 2024    | 3         | 0.93%   |
| 2007    | 3         | 0.93%   |
| 2006    | 2         | 0.62%   |
| Unknown | 1         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 324       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 298       | 91.41%  |
| Enabled  | 28        | 8.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 322       | 99.38%  |
| Yes  | 2         | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Notebooks | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 83        | 25.38%  |
| 16.01-24.0      | 68        | 20.8%   |
| 8.01-16.0       | 68        | 20.8%   |
| 3.01-4.0        | 41        | 12.54%  |
| 32.01-64.0      | 31        | 9.48%   |
| 1.01-2.0        | 15        | 4.59%   |
| 64.01-256.0     | 13        | 3.98%   |
| 24.01-32.0      | 6         | 1.83%   |
| More than 256.0 | 1         | 0.31%   |
| 2.01-3.0        | 1         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 89        | 25.65%  |
| 1.01-2.0   | 88        | 25.36%  |
| 4.01-8.0   | 69        | 19.88%  |
| 3.01-4.0   | 61        | 17.58%  |
| 0.51-1.0   | 18        | 5.19%   |
| 8.01-16.0  | 16        | 4.61%   |
| 16.01-24.0 | 4         | 1.15%   |
| 24.01-32.0 | 1         | 0.29%   |
| 0.01-0.5   | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 213       | 64.16%  |
| 2      | 99        | 29.82%  |
| 3      | 17        | 5.12%   |
| 4      | 2         | 0.6%    |
| 0      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 277       | 85.49%  |
| Yes       | 47        | 14.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 209       | 63.91%  |
| No        | 118       | 36.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 312       | 96%     |
| No        | 13        | 4%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 284       | 87.12%  |
| No        | 42        | 12.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| South Korea | 324       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Seoul         | 51        | 14.91%  |
| Suwon         | 18        | 5.26%   |
| Seocho-gu     | 13        | 3.8%    |
| Seongnam-si   | 11        | 3.22%   |
| Jung-gu       | 8         | 2.34%   |
| Gwanak-gu     | 8         | 2.34%   |
| Yongin-si     | 7         | 2.05%   |
| Uiwang        | 7         | 2.05%   |
| Hwaseong-si   | 7         | 2.05%   |
| Anyang-si     | 7         | 2.05%   |
| Seongbuk-gu   | 6         | 1.75%   |
| Seo-gu        | 6         | 1.75%   |
| Jeonju        | 6         | 1.75%   |
| Bucheon-si    | 6         | 1.75%   |
| Yongsan-gu    | 5         | 1.46%   |
| Pyeongtaek-si | 5         | 1.46%   |
| Nam-gu        | 5         | 1.46%   |
| Mapo-gu       | 5         | 1.46%   |
| Incheon       | 5         | 1.46%   |
| Gangnam-gu    | 5         | 1.46%   |
| Gangbuk-gu    | 5         | 1.46%   |
| Daegu         | 5         | 1.46%   |
| Busan         | 5         | 1.46%   |
| Bupyeong-gu   | 5         | 1.46%   |
| Gwangju       | 4         | 1.17%   |
| Gimpo-si      | 4         | 1.17%   |
| Daejeon       | 4         | 1.17%   |
| Yuseong-gu    | 3         | 0.88%   |
| Yeonsu-gu     | 3         | 0.88%   |
| Yangcheon-gu  | 3         | 0.88%   |
| Namyangju     | 3         | 0.88%   |
| Jeju City     | 3         | 0.88%   |
| Goyang-si     | 3         | 0.88%   |
| Geumjeong-gu  | 3         | 0.88%   |
| Gangseo-gu    | 3         | 0.88%   |
| Dong-gu       | 3         | 0.88%   |
| Chuncheon     | 3         | 0.88%   |
| Cheongju-si   | 3         | 0.88%   |
| Buk-gu        | 3         | 0.88%   |
| Yongsan-dong  | 2         | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 108       | 137    | 25.12%  |
| WDC                       | 39        | 41     | 9.07%   |
| SanDisk                   | 32        | 32     | 7.44%   |
| SK hynix                  | 30        | 37     | 6.98%   |
| Unknown                   | 29        | 35     | 6.74%   |
| Seagate                   | 21        | 25     | 4.88%   |
| Micron Technology         | 17        | 18     | 3.95%   |
| Crucial                   | 15        | 17     | 3.49%   |
| Toshiba                   | 14        | 16     | 3.26%   |
| Intel                     | 12        | 17     | 2.79%   |
| Kingston                  | 8         | 10     | 1.86%   |
| Apple                     | 7         | 9      | 1.63%   |
| A-DATA Technology         | 7         | 7      | 1.63%   |
| Phison                    | 6         | 8      | 1.4%    |
| Phison Electronics        | 5         | 5      | 1.16%   |
| Micron/Crucial Technology | 5         | 5      | 1.16%   |
| Hitachi                   | 5         | 6      | 1.16%   |
| UMIS                      | 3         | 3      | 0.7%    |
| Team                      | 3         | 3      | 0.7%    |
| TAMMUZ                    | 3         | 5      | 0.7%    |
| Silicon Motion            | 3         | 4      | 0.7%    |
| KIOXIA                    | 3         | 3      | 0.7%    |
| JMicron Technology        | 3         | 3      | 0.7%    |
| Imation                   | 3         | 3      | 0.7%    |
| HGST                      | 3         | 4      | 0.7%    |
| TYPEC 1T                  | 2         | 2      | 0.47%   |
| SSSTC                     | 2         | 3      | 0.47%   |
| RevuAhn                   | 2         | 2      | 0.47%   |
| LITEONIT                  | 2         | 2      | 0.47%   |
| LITEON                    | 2         | 2      | 0.47%   |
| KingSpec                  | 2         | 2      | 0.47%   |
| Fujitsu                   | 2         | 2      | 0.47%   |
| China                     | 2         | 2      | 0.47%   |
| Biostar                   | 2         | 2      | 0.47%   |
| ASMT                      | 2         | 2      | 0.47%   |
| ZTC                       | 1         | 1      | 0.23%   |
| XPG                       | 1         | 2      | 0.23%   |
| WD_BLACK                  | 1         | 1      | 0.23%   |
| VIVA300s                  | 1         | 1      | 0.23%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 9         | 1.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 7         | 1.54%   |
| Unknown MMC Card  512GB                               | 4         | 0.88%   |
| Unknown MMC Card  32GB                                | 4         | 0.88%   |
| SK hynix SHGP31-1000GM-2 1TB                          | 4         | 0.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 4         | 0.88%   |
| SanDisk NVMe SSD Drive 512GB                          | 4         | 0.88%   |
| Samsung MZVL21T0HCLR-00B00 1TB                        | 4         | 0.88%   |
| WDC WDS100T2B0C-00PXH0 1TB                            | 3         | 0.66%   |
| Unknown MMC Card  256GB                               | 3         | 0.66%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 3         | 0.66%   |
| Samsung SSD 980 PRO 2TB                               | 3         | 0.66%   |
| Samsung SSD 860 EVO 500GB                             | 3         | 0.66%   |
| Samsung MZVLQ1T0HBLB-00B 1TB                          | 3         | 0.66%   |
| Samsung MZVLB256HBHQ-000 256GB                        | 3         | 0.66%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 3         | 0.66%   |
| Intel SSDPEKNU512GZ 512GB                             | 3         | 0.66%   |
| Crucial CT500MX500SSD1 500GB                          | 3         | 0.66%   |
| WDC WD50 00LPVX-22V0TT0 500GB                         | 2         | 0.44%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB                  | 2         | 0.44%   |
| Unknown SLD64G  64GB                                  | 2         | 0.44%   |
| Unknown SD/MMC/MS PRO 128GB                           | 2         | 0.44%   |
| Unknown MMC Card  128GB                               | 2         | 0.44%   |
| TYPEC 1T B PSSD 1TB                                   | 2         | 0.44%   |
| Toshiba KBG30ZMV256G 256GB                            | 2         | 0.44%   |
| SK hynix SHGP31-1000GM 1TB                            | 2         | 0.44%   |
| SK hynix NVMe SSD Drive 256GB                         | 2         | 0.44%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                 | 2         | 0.44%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 0.44%   |
| Seagate ST500LT012-1DG142 500GB                       | 2         | 0.44%   |
| Seagate ST1000LX015-1U7172 1TB                        | 2         | 0.44%   |
| Seagate ST1000LM048-2E7172 1TB                        | 2         | 0.44%   |
| Seagate ST1000LM035-1RK172 1TB                        | 2         | 0.44%   |
| Seagate Expansion 1TB                                 | 2         | 0.44%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 2         | 0.44%   |
| SanDisk SD8SBAT256G1122 256GB SSD                     | 2         | 0.44%   |
| SanDisk NVMe SSD Drive 256GB                          | 2         | 0.44%   |
| Samsung SSD 870 EVO 500GB                             | 2         | 0.44%   |
| Samsung SSD 870 EVO 1TB                               | 2         | 0.44%   |
| Samsung SSD 860 EVO 1TB                               | 2         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 24     | 32.79%  |
| WDC                 | 17        | 17     | 27.87%  |
| Toshiba             | 6         | 6      | 9.84%   |
| Hitachi             | 5         | 6      | 8.2%    |
| HGST                | 3         | 4      | 4.92%   |
| Unknown             | 2         | 2      | 3.28%   |
| Samsung Electronics | 2         | 2      | 3.28%   |
| Fujitsu             | 2         | 2      | 3.28%   |
| ASMT                | 2         | 2      | 3.28%   |
| JMicron Technology  | 1         | 1      | 1.64%   |
| ipTIME              | 1         | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 55     | 34.59%  |
| Crucial             | 13        | 15     | 9.77%   |
| SanDisk             | 12        | 12     | 9.02%   |
| WDC                 | 6         | 7      | 4.51%   |
| SK hynix            | 6         | 7      | 4.51%   |
| Intel               | 5         | 6      | 3.76%   |
| TAMMUZ              | 3         | 5      | 2.26%   |
| Micron Technology   | 3         | 4      | 2.26%   |
| Kingston            | 3         | 4      | 2.26%   |
| Apple               | 3         | 3      | 2.26%   |
| A-DATA Technology   | 3         | 3      | 2.26%   |
| TYPEC 1T            | 2         | 2      | 1.5%    |
| Team                | 2         | 2      | 1.5%    |
| LITEONIT            | 2         | 2      | 1.5%    |
| LITEON              | 2         | 2      | 1.5%    |
| KingSpec            | 2         | 2      | 1.5%    |
| China               | 2         | 2      | 1.5%    |
| Biostar             | 2         | 2      | 1.5%    |
| ZTC                 | 1         | 1      | 0.75%   |
| Transcend           | 1         | 2      | 0.75%   |
| Toshiba             | 1         | 1      | 0.75%   |
| T-FORCE             | 1         | 1      | 0.75%   |
| SSSTC               | 1         | 1      | 0.75%   |
| RevuAhn             | 1         | 1      | 0.75%   |
| Plextor             | 1         | 1      | 0.75%   |
| OUTTON              | 1         | 1      | 0.75%   |
| OCZ                 | 1         | 1      | 0.75%   |
| NT-1TB              | 1         | 1      | 0.75%   |
| MG                  | 1         | 1      | 0.75%   |
| KLEVV               | 1         | 1      | 0.75%   |
| IPLEX               | 1         | 1      | 0.75%   |
| Imation             | 1         | 1      | 0.75%   |
| Hewlett-Packard     | 1         | 1      | 0.75%   |
| Apacer              | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 184       | 244    | 46.12%  |
| SSD     | 123       | 152    | 30.83%  |
| HDD     | 60        | 67     | 15.04%  |
| MMC     | 27        | 33     | 6.77%   |
| Unknown | 5         | 6      | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 184       | 237    | 47.67%  |
| SATA | 147       | 200    | 38.08%  |
| SAS  | 28        | 32     | 7.25%   |
| MMC  | 27        | 33     | 6.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 124       | 154    | 69.27%  |
| 0.51-1.0   | 49        | 56     | 27.37%  |
| 1.01-2.0   | 5         | 8      | 2.79%   |
| 3.01-4.0   | 1         | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 114       | 33.83%  |
| 251-500        | 67        | 19.88%  |
| 501-1000       | 48        | 14.24%  |
| 1001-2000      | 32        | 9.5%    |
| 51-100         | 27        | 8.01%   |
| 1-20           | 14        | 4.15%   |
| More than 3000 | 12        | 3.56%   |
| 21-50          | 12        | 3.56%   |
| 2001-3000      | 8         | 2.37%   |
| Unknown        | 3         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 128       | 37.43%  |
| 21-50          | 72        | 21.05%  |
| 101-250        | 44        | 12.87%  |
| 51-100         | 37        | 10.82%  |
| 251-500        | 25        | 7.31%   |
| 501-1000       | 19        | 5.56%   |
| 1001-2000      | 8         | 2.34%   |
| 2001-3000      | 4         | 1.17%   |
| Unknown        | 3         | 0.88%   |
| More than 3000 | 2         | 0.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB             | 1         | 1      | 6.25%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 6.25%   |
| Toshiba MK5061GSYN 500GB                 | 1         | 1      | 6.25%   |
| Toshiba MK2565GSX 250GB                  | 1         | 1      | 6.25%   |
| SSSTC CVB-8D128-HP 128GB SSD             | 1         | 1      | 6.25%   |
| SK hynix HFS512G39TND-N210A 512GB SSD    | 1         | 1      | 6.25%   |
| SK hynix HFS128G3AMNM-1010A 128GB SSD    | 1         | 1      | 6.25%   |
| SanDisk SD9SN8W256G1009 256GB SSD        | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 830 Series 512GB | 1         | 1      | 6.25%   |
| Samsung Electronics SM961 NVMe 1024GB    | 1         | 1      | 6.25%   |
| Phison ES 512GB                          | 1         | 2      | 6.25%   |
| LITEONIT LMT-256M3M 256GB SSD            | 1         | 1      | 6.25%   |
| KLEVV NEO N400 SSD 480GB                 | 1         | 1      | 6.25%   |
| Kingston SHFS37A120G 120GB SSD           | 1         | 1      | 6.25%   |
| Hitachi HTS541616J9SA00 160GB            | 1         | 1      | 6.25%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 12.5%   |
| Toshiba             | 2         | 2      | 12.5%   |
| SK hynix            | 2         | 2      | 12.5%   |
| Samsung Electronics | 2         | 2      | 12.5%   |
| SSSTC               | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Phison              | 1         | 2      | 6.25%   |
| LITEONIT            | 1         | 1      | 6.25%   |
| KLEVV               | 1         | 1      | 6.25%   |
| Kingston            | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 33.33%  |
| Toshiba | 2         | 2      | 33.33%  |
| Hitachi | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 8         | 8      | 50%     |
| HDD  | 6         | 6      | 37.5%   |
| NVMe | 2         | 3      | 12.5%   |

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
| Detected | 174       | 260    | 50.14%  |
| Works    | 157       | 225    | 45.24%  |
| Malfunc  | 16        | 17     | 4.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 164       | 41.31%  |
| Samsung Electronics              | 62        | 15.62%  |
| AMD                              | 36        | 9.07%   |
| SanDisk                          | 34        | 8.56%   |
| SK hynix                         | 23        | 5.79%   |
| Phison Electronics               | 14        | 3.53%   |
| Micron Technology                | 14        | 3.53%   |
| Toshiba America Info Systems     | 7         | 1.76%   |
| Micron/Crucial Technology        | 7         | 1.76%   |
| Silicon Motion                   | 5         | 1.26%   |
| Kingston Technology Company      | 5         | 1.26%   |
| Union Memory (Shenzhen)          | 4         | 1.01%   |
| Apple                            | 4         | 1.01%   |
| ADATA Technology                 | 4         | 1.01%   |
| KIOXIA                           | 3         | 0.76%   |
| Solid State Storage Technology   | 2         | 0.5%    |
| Nvidia                           | 2         | 0.5%    |
| Solidigm                         | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| Realtek Semiconductor            | 1         | 0.25%   |
| O2 Micro                         | 1         | 0.25%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.25%   |
| Broadcom / LSI                   | 1         | 0.25%   |
| Biwin Storage Technology         | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 8.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 25        | 6.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 19        | 4.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 19        | 4.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 3.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 2.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 2.43%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 9         | 2.18%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 9         | 2.18%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 8         | 1.94%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 1.94%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 8         | 1.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 1.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 7         | 1.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 1.7%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 6         | 1.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 1.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.46%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 1.21%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.21%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 0.97%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 4         | 0.97%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 4         | 0.97%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 4         | 0.97%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 4         | 0.97%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 4         | 0.97%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.97%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 3         | 0.73%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 3         | 0.73%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 0.73%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 3         | 0.73%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 0.73%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 3         | 0.73%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 3         | 0.73%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                            | 3         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 184       | 47.18%  |
| SATA | 178       | 45.64%  |
| RAID | 19        | 4.87%   |
| IDE  | 9         | 2.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 246       | 75.93%  |
| AMD    | 77        | 23.77%  |
| ARM    | 1         | 0.31%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 2.47%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 2.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.85%   |
| AMD Custom APU 0405                           | 6         | 1.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 1.54%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.54%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 5         | 1.54%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.23%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.23%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 1.23%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.23%   |
| Intel 12th Gen Core i5-1240P                  | 4         | 1.23%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.93%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.93%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 3         | 0.93%   |
| Intel 12th Gen Core i9-12900H                 | 3         | 0.93%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 0.93%   |
| Intel 12th Gen Core i7-1260P                  | 3         | 0.93%   |
| Intel 12th Gen Core i5-1235U                  | 3         | 0.93%   |
| Intel 11th Gen Core i7-11600H @ 2.90GHz       | 3         | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.93%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 0.93%   |
| AMD Ryzen 5 7530U with Radeon Graphics        | 3         | 0.93%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 0.62%   |
| Intel Pentium CPU 6405U @ 2.40GHz             | 2         | 0.62%   |
| Intel Core Ultra 7 155H                       | 2         | 0.62%   |
| Intel Core Ultra 5 125H                       | 2         | 0.62%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 2         | 0.62%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 0.62%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.62%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 2         | 0.62%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 0.62%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.62%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 63        | 19.44%  |
| Intel Core i5           | 63        | 19.44%  |
| Other                   | 60        | 18.52%  |
| AMD Ryzen 5             | 24        | 7.41%   |
| AMD Ryzen 7             | 22        | 6.79%   |
| Intel Core i3           | 15        | 4.63%   |
| Intel Celeron           | 11        | 3.4%    |
| Intel Core 2 Duo        | 9         | 2.78%   |
| Intel Pentium           | 8         | 2.47%   |
| Intel Core              | 5         | 1.54%   |
| AMD Ryzen 7 PRO         | 5         | 1.54%   |
| Intel Core i9           | 4         | 1.23%   |
| Intel Atom              | 4         | 1.23%   |
| AMD Ryzen 9             | 4         | 1.23%   |
| Intel Genuine           | 3         | 0.93%   |
| AMD Ryzen 5 PRO         | 3         | 0.93%   |
| AMD Ryzen 3             | 3         | 0.93%   |
| Intel Pentium Silver    | 2         | 0.62%   |
| Intel Core 2            | 2         | 0.62%   |
| AMD A6                  | 2         | 0.62%   |
| AMD A4                  | 2         | 0.62%   |
| AMD A10                 | 2         | 0.62%   |
| Intel Xeon Gold         | 1         | 0.31%   |
| Intel Xeon              | 1         | 0.31%   |
| Intel Pentium Dual-Core | 1         | 0.31%   |
| Intel Pentium Dual      | 1         | 0.31%   |
| Intel Core m3           | 1         | 0.31%   |
| AMD Quad-Core           | 1         | 0.31%   |
| AMD Athlon II           | 1         | 0.31%   |
| AMD A12                 | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 108       | 33.33%  |
| 4       | 106       | 32.72%  |
| 8       | 37        | 11.42%  |
| 6       | 37        | 11.42%  |
| 12      | 13        | 4.01%   |
| 14      | 9         | 2.78%   |
| 10      | 6         | 1.85%   |
| 16      | 5         | 1.54%   |
| 32      | 1         | 0.31%   |
| 1       | 1         | 0.31%   |
| Unknown | 1         | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 322       | 99.38%  |
| 2      | 2         | 0.62%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 268       | 82.72%  |
| 1       | 55        | 16.98%  |
| Unknown | 1         | 0.31%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 319       | 98.46%  |
| Unknown        | 3         | 0.93%   |
| 64-bit         | 1         | 0.31%   |
| 32-bit         | 1         | 0.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 27.84%  |
| 0x806ec    | 17        | 5.09%   |
| 0x806c1    | 15        | 4.49%   |
| 0x306a9    | 13        | 3.89%   |
| 0x906a3    | 12        | 3.59%   |
| 0x806ea    | 11        | 3.29%   |
| 0x206a7    | 10        | 2.99%   |
| 0x0a50000c | 10        | 2.99%   |
| 0x20655    | 8         | 2.4%    |
| 0x906e9    | 7         | 2.1%    |
| 0x806eb    | 7         | 2.1%    |
| 0x08600106 | 7         | 2.1%    |
| 0x806e9    | 6         | 1.8%    |
| 0x40651    | 6         | 1.8%    |
| 0x08108102 | 6         | 1.8%    |
| 0x906ea    | 5         | 1.5%    |
| 0x706e5    | 5         | 1.5%    |
| 0x0a50000d | 5         | 1.5%    |
| 0x0a404102 | 5         | 1.5%    |
| 0x08608103 | 5         | 1.5%    |
| 0xa0652    | 4         | 1.2%    |
| 0x806d1    | 4         | 1.2%    |
| 0x706a1    | 4         | 1.2%    |
| 0x6fd      | 4         | 1.2%    |
| 0x406e3    | 4         | 1.2%    |
| 0x306d4    | 4         | 1.2%    |
| 0x306c3    | 4         | 1.2%    |
| 0x30678    | 4         | 1.2%    |
| 0x1067a    | 4         | 1.2%    |
| 0x906ed    | 3         | 0.9%    |
| 0xb06f2    | 2         | 0.6%    |
| 0xa0660    | 2         | 0.6%    |
| 0x6f6      | 2         | 0.6%    |
| 0x406c3    | 2         | 0.6%    |
| 0x20652    | 2         | 0.6%    |
| 0x10676    | 2         | 0.6%    |
| 0x08600103 | 2         | 0.6%    |
| 0x08108109 | 2         | 0.6%    |
| 0x0700010f | 2         | 0.6%    |
| 0x06001119 | 2         | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 69        | 21.23%  |
| Unknown           | 38        | 11.69%  |
| Zen 3             | 20        | 6.15%   |
| TigerLake         | 19        | 5.85%   |
| Haswell           | 18        | 5.54%   |
| Alderlake Hybrid  | 18        | 5.54%   |
| IvyBridge         | 16        | 4.92%   |
| Zen 2             | 14        | 4.31%   |
| SandyBridge       | 12        | 3.69%   |
| Westmere          | 11        | 3.38%   |
| IceLake           | 10        | 3.08%   |
| Zen+              | 9         | 2.77%   |
| Skylake           | 9         | 2.77%   |
| Silvermont        | 8         | 2.46%   |
| Penryn            | 8         | 2.46%   |
| CometLake         | 8         | 2.46%   |
| Core              | 7         | 2.15%   |
| Broadwell         | 6         | 1.85%   |
| Goldmont plus     | 5         | 1.54%   |
| Meteorlake Hybrid | 3         | 0.92%   |
| Jaguar            | 3         | 0.92%   |
| Excavator         | 3         | 0.92%   |
| Zen               | 2         | 0.62%   |
| Piledriver        | 2         | 0.62%   |
| Nehalem           | 2         | 0.62%   |
| Tremont           | 1         | 0.31%   |
| P6                | 1         | 0.31%   |
| K10               | 1         | 0.31%   |
| Goldmont          | 1         | 0.31%   |
| Bonnell           | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 226       | 55.67%  |
| Nvidia                           | 89        | 21.92%  |
| AMD                              | 89        | 21.92%  |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| Matrox Electronics Systems       | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 16        | 3.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 3.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 3.6%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 14        | 3.36%   |
| Intel UHD Graphics 620                                                                   | 13        | 3.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 3.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 2.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 2.88%   |
| AMD Barcelo                                                                              | 12        | 2.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.68%   |
| AMD Rembrandt [Radeon 680M]                                                              | 7         | 1.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 1.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 1.44%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 1.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.44%   |
| Intel HD Graphics 630                                                                    | 6         | 1.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.44%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.44%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 6         | 1.44%   |
| AMD Lucienne                                                                             | 6         | 1.44%   |
| Nvidia TU117M [GeForce MX450]                                                            | 5         | 1.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.2%    |
| Intel Meteor Lake-P [Intel Arc Graphics]                                                 | 5         | 1.2%    |
| Intel HD Graphics 620                                                                    | 5         | 1.2%    |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 0.96%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 0.96%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 0.96%   |
| Intel HD Graphics 5500                                                                   | 4         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.72%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.72%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 3         | 0.72%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 3         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 149       | 45.85%  |
| 1 x AMD         | 69        | 21.23%  |
| Intel + Nvidia  | 66        | 20.31%  |
| 1 x Nvidia      | 15        | 4.62%   |
| Intel + AMD     | 10        | 3.08%   |
| 2 x AMD         | 6         | 1.85%   |
| AMD + Nvidia    | 6         | 1.85%   |
| Other           | 1         | 0.31%   |
| 2 x Nvidia      | 1         | 0.31%   |
| 1 x SiS         | 1         | 0.31%   |
| Nvidia + Matrox | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 265       | 81.04%  |
| Proprietary | 43        | 13.15%  |
| Unknown     | 19        | 5.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 210       | 63.83%  |
| 0.01-0.5   | 36        | 10.94%  |
| 1.01-2.0   | 30        | 9.12%   |
| 3.01-4.0   | 25        | 7.6%    |
| 0.51-1.0   | 15        | 4.56%   |
| 7.01-8.0   | 5         | 1.52%   |
| 5.01-6.0   | 5         | 1.52%   |
| 8.01-16.0  | 2         | 0.61%   |
| 2.01-3.0   | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 61        | 16.35%  |
| AU Optronics            | 53        | 14.21%  |
| Samsung Electronics     | 48        | 12.87%  |
| BOE                     | 45        | 12.06%  |
| Chimei Innolux          | 43        | 11.53%  |
| Goldstar                | 17        | 4.56%   |
| Apple                   | 12        | 3.22%   |
| Sharp                   | 10        | 2.68%   |
| Dell                    | 9         | 2.41%   |
| Valve                   | 7         | 1.88%   |
| PANDA                   | 7         | 1.88%   |
| Lenovo                  | 5         | 1.34%   |
| JCH                     | 4         | 1.07%   |
| Chi Mei Optoelectronics | 4         | 1.07%   |
| BenQ                    | 4         | 1.07%   |
| Sony                    | 3         | 0.8%    |
| Philips                 | 3         | 0.8%    |
| InfoVision              | 3         | 0.8%    |
| CSO                     | 3         | 0.8%    |
| CPT                     | 3         | 0.8%    |
| ALP                     | 3         | 0.8%    |
| TMX                     | 2         | 0.54%   |
| Hewlett-Packard         | 2         | 0.54%   |
| AOC                     | 2         | 0.54%   |
| XHS                     | 1         | 0.27%   |
| WIT                     | 1         | 0.27%   |
| VMO                     | 1         | 0.27%   |
| Vizio                   | 1         | 0.27%   |
| Unknown (DEF)           | 1         | 0.27%   |
| STD                     | 1         | 0.27%   |
| Sceptre Tech            | 1         | 0.27%   |
| PRISM+                  | 1         | 0.27%   |
| Olevia                  | 1         | 0.27%   |
| MSI                     | 1         | 0.27%   |
| MSD                     | 1         | 0.27%   |
| LGD                     | 1         | 0.27%   |
| KVM                     | 1         | 0.27%   |
| HVR                     | 1         | 0.27%   |
| HKC                     | 1         | 0.27%   |
| HannStar                | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                 | 7         | 1.84%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 6         | 1.58%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 4         | 1.05%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 4         | 1.05%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 1.05%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.05%   |
| Samsung Electronics LCD Monitor SDC4186 2880x1800 302x189mm 14.0-inch | 3         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.79%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                 | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.79%   |
| Sony BW8 MS_9001 2560x1600                                            | 2         | 0.53%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.53%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4188 2880x1800 312x195mm 14.5-inch | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 2         | 0.53%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 2         | 0.53%   |
| PANDA LCD Monitor NCP0064 1920x1080 344x194mm 15.5-inch               | 2         | 0.53%   |
| LG Display LCD Monitor LGD0706 1920x1080 344x194mm 15.5-inch          | 2         | 0.53%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch          | 2         | 0.53%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 2         | 0.53%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch          | 2         | 0.53%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch          | 2         | 0.53%   |
| LG Display LCD Monitor LGD03FC 1600x900 309x174mm 14.0-inch           | 2         | 0.53%   |
| LG Display LCD Monitor LGD03B5 1920x1080 294x165mm 13.3-inch          | 2         | 0.53%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 2         | 0.53%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.53%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 2         | 0.53%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                 | 2         | 0.53%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 0.53%   |
| BOE LCD Monitor BOE06E8 1920x1080 332x186mm 15.0-inch                 | 2         | 0.53%   |
| BOE LCD Monitor BOE06D7 3840x2160 345x194mm 15.6-inch                 | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO749D 3840x2160 381x214mm 17.2-inch        | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO6A92 1920x1080 344x194mm 15.5-inch        | 2         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 180       | 50%     |
| 1366x768 (WXGA)    | 45        | 12.5%   |
| 3840x2160 (4K)     | 23        | 6.39%   |
| 2560x1600          | 17        | 4.72%   |
| 2880x1800          | 14        | 3.89%   |
| 1920x1200 (WUXGA)  | 14        | 3.89%   |
| 2560x1440 (QHD)    | 13        | 3.61%   |
| 1280x800 (WXGA)    | 9         | 2.5%    |
| 1600x900 (HD+)     | 8         | 2.22%   |
| 800x1280           | 7         | 1.94%   |
| 3440x1440          | 5         | 1.39%   |
| 3840x2400          | 4         | 1.11%   |
| 1440x900 (WXGA+)   | 3         | 0.83%   |
| 1280x1024 (SXGA)   | 3         | 0.83%   |
| 3072x1920          | 2         | 0.56%   |
| 2880x1620          | 2         | 0.56%   |
| 1680x1050 (WSXGA+) | 2         | 0.56%   |
| 2560x1080          | 1         | 0.28%   |
| 2160x3840          | 1         | 0.28%   |
| 2160x1350          | 1         | 0.28%   |
| 2160x1200          | 1         | 0.28%   |
| 1920x1280          | 1         | 0.28%   |
| 1680x945           | 1         | 0.28%   |
| 1600x2560          | 1         | 0.28%   |
| 1400x1050          | 1         | 0.28%   |
| 1024x768 (XGA)     | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 143       | 38.03%  |
| 13      | 49        | 13.03%  |
| 14      | 46        | 12.23%  |
| 16      | 17        | 4.52%   |
| 27      | 16        | 4.26%   |
| 17      | 13        | 3.46%   |
| 24      | 12        | 3.19%   |
| 23      | 12        | 3.19%   |
| 21      | 11        | 2.93%   |
| 31      | 9         | 2.39%   |
| 7       | 7         | 1.86%   |
| 12      | 6         | 1.6%    |
| 11      | 5         | 1.33%   |
| 34      | 4         | 1.06%   |
| 20      | 4         | 1.06%   |
| Unknown | 4         | 1.06%   |
| 8       | 3         | 0.8%    |
| 40      | 2         | 0.53%   |
| 19      | 2         | 0.53%   |
| 18      | 2         | 0.53%   |
| 74      | 1         | 0.27%   |
| 54      | 1         | 0.27%   |
| 49      | 1         | 0.27%   |
| 42      | 1         | 0.27%   |
| 32      | 1         | 0.27%   |
| 26      | 1         | 0.27%   |
| 25      | 1         | 0.27%   |
| 10      | 1         | 0.27%   |
| 5       | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 218       | 58.29%  |
| 201-300     | 45        | 12.03%  |
| 501-600     | 39        | 10.43%  |
| 351-400     | 19        | 5.08%   |
| 401-500     | 17        | 4.55%   |
| 601-700     | 10        | 2.67%   |
| 1-100       | 7         | 1.87%   |
| 701-800     | 5         | 1.34%   |
| 101-200     | 4         | 1.07%   |
| Unknown     | 4         | 1.07%   |
| 801-900     | 2         | 0.53%   |
| 1001-1500   | 2         | 0.53%   |
| 1501-2000   | 1         | 0.27%   |
| 901-1000    | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 242       | 73.33%  |
| 16/10   | 62        | 18.79%  |
| 0.67    | 6         | 1.82%   |
| 21/9    | 4         | 1.21%   |
| 0.62    | 4         | 1.21%   |
| 5/4     | 3         | 0.91%   |
| 3/2     | 3         | 0.91%   |
| Unknown | 3         | 0.91%   |
| 4/3     | 2         | 0.61%   |
| 0.56    | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 141       | 37.5%   |
| 81-90          | 66        | 17.55%  |
| 201-250        | 29        | 7.71%   |
| 71-80          | 26        | 6.91%   |
| 301-350        | 17        | 4.52%   |
| 111-120        | 16        | 4.26%   |
| 351-500        | 14        | 3.72%   |
| 121-130        | 12        | 3.19%   |
| 1-40           | 11        | 2.93%   |
| 151-200        | 7         | 1.86%   |
| 61-70          | 6         | 1.6%    |
| 251-300        | 6         | 1.6%    |
| 91-100         | 6         | 1.6%    |
| 51-60          | 5         | 1.33%   |
| Unknown        | 4         | 1.06%   |
| More than 1000 | 3         | 0.8%    |
| 141-150        | 3         | 0.8%    |
| 501-1000       | 3         | 0.8%    |
| 41-50          | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 153       | 41.58%  |
| 161-240       | 68        | 18.48%  |
| 101-120       | 61        | 16.58%  |
| 51-100        | 53        | 14.4%   |
| More than 240 | 26        | 7.07%   |
| Unknown       | 4         | 1.09%   |
| 1-50          | 3         | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 251       | 74.48%  |
| 2     | 62        | 18.4%   |
| 0     | 17        | 5.04%   |
| 3     | 6         | 1.78%   |
| 4     | 1         | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 203       | 41.6%   |
| Realtek Semiconductor            | 164       | 33.61%  |
| Qualcomm Atheros                 | 39        | 7.99%   |
| Broadcom                         | 29        | 5.94%   |
| MediaTek                         | 12        | 2.46%   |
| ASIX Electronics                 | 8         | 1.64%   |
| Samsung Electronics              | 4         | 0.82%   |
| Marvell Technology Group         | 4         | 0.82%   |
| Ralink Technology                | 3         | 0.61%   |
| Broadcom Limited                 | 3         | 0.61%   |
| Apple                            | 3         | 0.61%   |
| TP-Link                          | 2         | 0.41%   |
| Qualcomm                         | 2         | 0.41%   |
| Nvidia                           | 2         | 0.41%   |
| Lenovo                           | 2         | 0.41%   |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Ralink                           | 1         | 0.2%    |
| Quectel Wireless Solutions       | 1         | 0.2%    |
| Microsoft                        | 1         | 0.2%    |
| JMicron Technology               | 1         | 0.2%    |
| D-Link                           | 1         | 0.2%    |
| Comneon                          | 1         | 0.2%    |
| Arduino SA                       | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 98        | 17.69%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 30        | 5.42%   |
| Intel Wi-Fi 6 AX200                                                    | 28        | 5.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 20        | 3.61%   |
| Intel Wi-Fi 6 AX201                                                    | 16        | 2.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 2.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 15        | 2.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 12        | 2.17%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 9         | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 1.62%   |
| Intel Wireless 8265 / 8275                                             | 9         | 1.62%   |
| Intel Wireless 7260                                                    | 9         | 1.62%   |
| Intel Wireless 3165                                                    | 9         | 1.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 9         | 1.62%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 8         | 1.44%   |
| ASIX AX88179 Gigabit Ethernet                                          | 8         | 1.44%   |
| Realtek RTL8125 2.5GbE Controller                                      | 7         | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 1.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6         | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 0.9%    |
| Intel Wireless 7265                                                    | 5         | 0.9%    |
| Intel Meteor Lake PCH CNVi WiFi                                        | 5         | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 5         | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 0.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 5         | 0.9%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 0.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.72%   |
| Intel Wireless 3160                                                    | 4         | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 4         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 4         | 0.72%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 4         | 0.72%   |
| Intel Centrino Advanced-N 6235                                         | 4         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3         | 0.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 198       | 61.3%   |
| Realtek Semiconductor      | 45        | 13.93%  |
| Qualcomm Atheros           | 32        | 9.91%   |
| Broadcom                   | 25        | 7.74%   |
| MediaTek                   | 10        | 3.1%    |
| Ralink Technology          | 3         | 0.93%   |
| Broadcom Limited           | 3         | 0.93%   |
| TP-Link                    | 2         | 0.62%   |
| Qualcomm                   | 2         | 0.62%   |
| Ralink                     | 1         | 0.31%   |
| Quectel Wireless Solutions | 1         | 0.31%   |
| D-Link                     | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 28        | 8.62%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 20        | 6.15%   |
| Intel Wi-Fi 6 AX201                                            | 16        | 4.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 4.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 12        | 3.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 9         | 2.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 2.77%   |
| Intel Wireless 8265 / 8275                                     | 9         | 2.77%   |
| Intel Wireless 7260                                            | 9         | 2.77%   |
| Intel Wireless 3165                                            | 9         | 2.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 2.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 6         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 1.54%   |
| Intel Wireless 7265                                            | 5         | 1.54%   |
| Intel Meteor Lake PCH CNVi WiFi                                | 5         | 1.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.23%   |
| Intel Wireless 3160                                            | 4         | 1.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 1.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 4         | 1.23%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 0.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 0.92%   |
| Intel Wireless 8260                                            | 3         | 0.92%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 3         | 0.92%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 3         | 0.92%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 0.92%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 0.92%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter             | 3         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 145       | 67.44%  |
| Intel                            | 27        | 12.56%  |
| Qualcomm Atheros                 | 9         | 4.19%   |
| ASIX Electronics                 | 8         | 3.72%   |
| Broadcom                         | 6         | 2.79%   |
| Samsung Electronics              | 4         | 1.86%   |
| Marvell Technology Group         | 4         | 1.86%   |
| Apple                            | 3         | 1.4%    |
| Nvidia                           | 2         | 0.93%   |
| MediaTek                         | 2         | 0.93%   |
| Lenovo                           | 2         | 0.93%   |
| Silicon Integrated Systems [SiS] | 1         | 0.47%   |
| Microsoft                        | 1         | 0.47%   |
| JMicron Technology               | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 98        | 43.17%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 30        | 13.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 15        | 6.61%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 8         | 3.52%   |
| Realtek RTL8125 2.5GbE Controller                                              | 7         | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 2.2%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 4         | 1.76%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.32%   |
| Samsung USB LAN AA-AE3AUUB                                                     | 2         | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.88%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.88%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 2         | 0.88%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.88%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.88%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.88%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 0.88%   |
| Apple iBridge                                                                  | 2         | 0.88%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.44%   |
| Realtek USB 10/100/1G/2.5G LAN                                                 | 1         | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.44%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.44%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.44%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 0.44%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.44%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.44%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.44%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.44%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                            | 1         | 0.44%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.44%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.44%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 311       | 60.04%  |
| Ethernet | 205       | 39.58%  |
| Modem    | 2         | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 254       | 72.57%  |
| Ethernet | 96        | 27.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 163       | 50.15%  |
| 1     | 156       | 48%     |
| 0     | 4         | 1.23%   |
| 3     | 2         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 318       | 98.15%  |
| Yes  | 6         | 1.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 174       | 61.05%  |
| Realtek Semiconductor           | 27        | 9.47%   |
| IMC Networks                    | 23        | 8.07%   |
| Broadcom                        | 17        | 5.96%   |
| Qualcomm Atheros Communications | 13        | 4.56%   |
| Foxconn / Hon Hai               | 9         | 3.16%   |
| Apple                           | 8         | 2.81%   |
| Lite-On Technology              | 5         | 1.75%   |
| Cambridge Silicon Radio         | 4         | 1.4%    |
| TP-Link                         | 1         | 0.35%   |
| Realtek                         | 1         | 0.35%   |
| Qcom                            | 1         | 0.35%   |
| Micro Star International        | 1         | 0.35%   |
| Hewlett-Packard                 | 1         | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                         | 40        | 14.04%  |
| Intel AX201 Bluetooth                                      | 38        | 13.33%  |
| Intel AX200 Bluetooth                                      | 28        | 9.82%   |
| Intel AX211 Bluetooth                                      | 27        | 9.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)             | 24        | 8.42%   |
| Realtek Bluetooth Radio                                    | 18        | 6.32%   |
| IMC Networks Wireless_Device                               | 8         | 2.81%   |
| IMC Networks Bluetooth Radio                               | 8         | 2.81%   |
| Intel Centrino Bluetooth Wireless Transceiver              | 7         | 2.46%   |
| Apple Bluetooth Host Controller                            | 7         | 2.46%   |
| Qualcomm Atheros  Bluetooth Device                         | 6         | 2.11%   |
| Intel AX210 Bluetooth                                      | 6         | 2.11%   |
| Realtek  Bluetooth 4.2 Adapter                             | 4         | 1.4%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                     | 4         | 1.4%    |
| IMC Networks Bluetooth Device                              | 4         | 1.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)        | 4         | 1.4%    |
| Broadcom BCM2045B (BDC-2.1)                                | 4         | 1.4%    |
| Lite-On Bluetooth Device                                   | 3         | 1.05%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter          | 3         | 1.05%   |
| Foxconn / Hon Hai BCM2045A0                                | 3         | 1.05%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                       | 3         | 1.05%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                    | 2         | 0.7%    |
| Realtek 802.11ac WLAN Adapter                              | 2         | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                      | 2         | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                   | 2         | 0.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter           | 2         | 0.7%    |
| Foxconn / Hon Hai Wireless_Device                          | 2         | 0.7%    |
| Foxconn / Hon Hai Bluetooth Device                         | 2         | 0.7%    |
| Broadcom BCM43142A0 Bluetooth Device                       | 2         | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                 | 2         | 0.7%    |
| Broadcom BCM2070 Bluetooth Device                          | 2         | 0.7%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]           | 2         | 0.7%    |
| TP-Link TP-Link Bluetooth USB Adapter                      | 1         | 0.35%   |
| Realtek CSR BS8510                                         | 1         | 0.35%   |
| Realtek Bluetooth Radio                                    | 1         | 0.35%   |
| Qualcomm Atheros AR3011 Bluetooth                          | 1         | 0.35%   |
| Qcom Bluetooth USB                                         | 1         | 0.35%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device | 1         | 0.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                 | 1         | 0.35%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device               | 1         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 237       | 61.08%  |
| AMD                              | 84        | 21.65%  |
| Nvidia                           | 44        | 11.34%  |
| JMTek                            | 4         | 1.03%   |
| Lenovo                           | 3         | 0.77%   |
| Apple                            | 3         | 0.77%   |
| Texas Instruments                | 1         | 0.26%   |
| Sony                             | 1         | 0.26%   |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |
| Realtek Semiconductor            | 1         | 0.26%   |
| Razer USA                        | 1         | 0.26%   |
| No brand                         | 1         | 0.26%   |
| Native Instruments               | 1         | 0.26%   |
| KTMicro                          | 1         | 0.26%   |
| Generalplus Technology           | 1         | 0.26%   |
| Focusrite-Novation               | 1         | 0.26%   |
| Dell                             | 1         | 0.26%   |
| C-Media Electronics              | 1         | 0.26%   |
| Unknown                          | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 60        | 12.47%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 39        | 8.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 5.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 22        | 4.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 3.95%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 17        | 3.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 3.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 16        | 3.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 2.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 2.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.66%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.46%   |
| Intel CM238 HD Audio Controller                                                                   | 7         | 1.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.46%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 6         | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.25%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.25%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.25%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.04%   |
| Intel Meteor Lake-P HD Audio Controller                                                           | 5         | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.04%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.04%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.04%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 0.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.62%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.62%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 3         | 0.62%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 0.62%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 3         | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 111       | 47.84%  |
| SK hynix            | 53        | 22.84%  |
| Micron Technology   | 27        | 11.64%  |
| Unknown             | 10        | 4.31%   |
| Unknown             | 5         | 2.16%   |
| A-DATA Technology   | 4         | 1.72%   |
| Kingston            | 3         | 1.29%   |
| Elpida              | 3         | 1.29%   |
| Unknown (ABCD)      | 2         | 0.86%   |
| Team                | 2         | 0.86%   |
| Ramaxel Technology  | 2         | 0.86%   |
| Unknown (899D)      | 1         | 0.43%   |
| Unknown (09D5)      | 1         | 0.43%   |
| Silicon Power       | 1         | 0.43%   |
| PUSKILL             | 1         | 0.43%   |
| Nanya Technology    | 1         | 0.43%   |
| KLEVV               | 1         | 0.43%   |
| Imation             | 1         | 0.43%   |
| G.Skill             | 1         | 0.43%   |
| Essencore           | 1         | 0.43%   |
| Crucial             | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 9         | 3.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 8         | 3.19%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 5         | 1.99%   |
| Unknown                                                             | 5         | 1.99%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                    | 4         | 1.59%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 1.59%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 1.59%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 1.59%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 1.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 1.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 1.59%   |
| Samsung RAM M471A1G44AB0-CTD 8GB DDR4 2667MT/s                      | 4         | 1.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 1.2%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 1.2%    |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 3         | 1.2%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 1.2%    |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 3         | 1.2%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 1.2%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 3         | 1.2%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 3         | 1.2%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 1.2%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 1.2%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 1.2%    |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 3         | 1.2%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 3         | 1.2%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                           | 2         | 0.8%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 2         | 0.8%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.8%    |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.8%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.8%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.8%    |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s      | 2         | 0.8%    |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.8%    |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 2         | 0.8%    |
| Samsung RAM M471A1K43CB1-CTD 8GB DDR4 2667MT/s                      | 2         | 0.8%    |
| Samsung RAM M471A1G44CB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.8%    |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s            | 2         | 0.8%    |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s            | 2         | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 108       | 54%     |
| DDR3    | 34        | 17%     |
| LPDDR5  | 16        | 8%      |
| LPDDR4  | 16        | 8%      |
| LPDDR3  | 9         | 4.5%    |
| DDR5    | 8         | 4%      |
| DDR2    | 5         | 2.5%    |
| SDRAM   | 2         | 1%      |
| Unknown | 2         | 1%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 144       | 69.57%  |
| Row Of Chips | 51        | 24.64%  |
| Unknown      | 7         | 3.38%   |
| DIMM         | 4         | 1.93%   |
| Chip         | 1         | 0.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 97        | 44.7%   |
| 4096  | 46        | 21.2%   |
| 16384 | 38        | 17.51%  |
| 2048  | 20        | 9.22%   |
| 32768 | 13        | 5.99%   |
| 1024  | 2         | 0.92%   |
| 3072  | 1         | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 55        | 25.58%  |
| 2667    | 42        | 19.53%  |
| 1600    | 24        | 11.16%  |
| 2400    | 15        | 6.98%   |
| 6400    | 13        | 6.05%   |
| 2133    | 11        | 5.12%   |
| 4800    | 9         | 4.19%   |
| 4267    | 9         | 4.19%   |
| 3266    | 8         | 3.72%   |
| 1334    | 6         | 2.79%   |
| 8400    | 3         | 1.4%    |
| 7500    | 3         | 1.4%    |
| 4266    | 2         | 0.93%   |
| 1867    | 2         | 0.93%   |
| 1333    | 2         | 0.93%   |
| 1067    | 2         | 0.93%   |
| 800     | 2         | 0.93%   |
| 667     | 2         | 0.93%   |
| 8600    | 1         | 0.47%   |
| 7467    | 1         | 0.47%   |
| 4199    | 1         | 0.47%   |
| 2048    | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 66.67%  |
| Samsung Electronics | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Samsung M2020 Series     | 1         | 33.33%  |
| HP OfficeJet 4650 series | 1         | 33.33%  |
| HP HP LaserJet M14-M17   | 1         | 33.33%  |

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
| Chicony Electronics                    | 53        | 19.56%  |
| IMC Networks                           | 38        | 14.02%  |
| Bison Electronics                      | 23        | 8.49%   |
| Realtek Semiconductor                  | 17        | 6.27%   |
| Microdia                               | 17        | 6.27%   |
| Silicon Motion                         | 16        | 5.9%    |
| Quanta                                 | 15        | 5.54%   |
| Shenzhen Kingcome Optoelectronic       | 10        | 3.69%   |
| Apple                                  | 10        | 3.69%   |
| Syntek                                 | 8         | 2.95%   |
| SunplusIT                              | 8         | 2.95%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.95%   |
| Luxvisions Innotech Limited            | 7         | 2.58%   |
| Acer                                   | 7         | 2.58%   |
| Suyin                                  | 5         | 1.85%   |
| Sunplus Innovation Technology          | 5         | 1.85%   |
| Sonix Technology                       | 3         | 1.11%   |
| Logitech                               | 3         | 1.11%   |
| Z-Star Microelectronics                | 2         | 0.74%   |
| LG Electronics                         | 2         | 0.74%   |
| Lenovo                                 | 2         | 0.74%   |
| DigiTech                               | 2         | 0.74%   |
| Alcor Micro                            | 2         | 0.74%   |
| Shinetech                              | 1         | 0.37%   |
| Samsung Electronics                    | 1         | 0.37%   |
| OmniVision Technologies                | 1         | 0.37%   |
| Microsoft                              | 1         | 0.37%   |
| Goodong Industry                       | 1         | 0.37%   |
| Genesys Logic                          | 1         | 0.37%   |
| DRFCB0ABIHX4E3                         | 1         | 0.37%   |
| Cubeternet                             | 1         | 0.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 16        | 5.82%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 13        | 4.73%   |
| Bison Integrated Camera                                 | 11        | 4%      |
| Shenzhen Kingcome Optoelectronic 720p HD Camera         | 10        | 3.64%   |
| IMC Networks Integrated Camera                          | 10        | 3.64%   |
| Microdia Integrated_Webcam_HD                           | 9         | 3.27%   |
| Realtek LG Camera                                       | 6         | 2.18%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 6         | 2.18%   |
| Chicony HD Webcam                                       | 6         | 2.18%   |
| Syntek Integrated Camera                                | 5         | 1.82%   |
| Silicon Motion LG HD WebCam                             | 4         | 1.45%   |
| Chicony LG Camera                                       | 4         | 1.45%   |
| Bison HD Webcam                                         | 4         | 1.45%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 4         | 1.45%   |
| Suyin HP Truevision HD                                  | 3         | 1.09%   |
| SunplusIT 720p HD Camera                                | 3         | 1.09%   |
| SunplusIT 1080p FHD Camera                              | 3         | 1.09%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.09%   |
| Quanta HP TrueVision HD Camera                          | 3         | 1.09%   |
| Chicony USB 2.0 Camera                                  | 3         | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 3         | 1.09%   |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 1.09%   |
| Z-Star Webcam                                           | 2         | 0.73%   |
| Syntek Lenovo EasyCamera                                | 2         | 0.73%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 2         | 0.73%   |
| Silicon Motion 720p HD Camera                           | 2         | 0.73%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.73%   |
| Quanta LGE Camera                                       | 2         | 0.73%   |
| Quanta LG Webcam                                        | 2         | 0.73%   |
| Quanta HP Wide Vision HD Camera                         | 2         | 0.73%   |
| Quanta HP Webcam                                        | 2         | 0.73%   |
| Microdia USB 2.0 Camera                                 | 2         | 0.73%   |
| Luxvisions Innotech Limited Integrated Camera           | 2         | 0.73%   |
| Luxvisions Innotech Limited HP HD Camera                | 2         | 0.73%   |
| Logitech C922 Pro Stream Webcam                         | 2         | 0.73%   |
| IMC Networks USB HD Webcam                              | 2         | 0.73%   |
| IMC Networks Integrated RGB Camera                      | 2         | 0.73%   |
| Chicony LG HD WebCam                                    | 2         | 0.73%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 2         | 0.73%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 23        | 32.39%  |
| Validity Sensors                   | 13        | 18.31%  |
| Samsung Electronics                | 10        | 14.08%  |
| Shenzhen Goodix Technology         | 6         | 8.45%   |
| Realtek USB2.0 Finger Print Bridge | 6         | 8.45%   |
| Upek                               | 4         | 5.63%   |
| Elan Microelectronics              | 4         | 5.63%   |
| STMicroelectronics                 | 2         | 2.82%   |
| LighTuning Technology              | 2         | 2.82%   |
| AuthenTec                          | 1         | 1.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung Fingerprint Sensor Device - 730B                        | 7         | 9.86%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 6         | 8.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 5.63%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 4         | 5.63%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 4         | 5.63%   |
| Shenzhen Goodix  FingerPrint Device                             | 4         | 5.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 3         | 4.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 3         | 4.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 3         | 4.23%   |
| Samsung Fingerprint Device                                      | 3         | 4.23%   |
| Elan ELAN:ARM-M4                                                | 3         | 4.23%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 2.82%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 2         | 2.82%   |
| Synaptics WBDI                                                  | 2         | 2.82%   |
| Synaptics UWP WBDI Device                                       | 2         | 2.82%   |
| Synaptics Prometheus Fingerprint Reader                         | 2         | 2.82%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 2         | 2.82%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 2.82%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 2.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 2.82%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 1         | 1.41%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 1.41%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 1.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.41%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.41%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.41%   |
| Synaptics WBDI Device                                           | 1         | 1.41%   |
| Elan ELAN:Fingerprint                                           | 1         | 1.41%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 1.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Alcor Micro      | 3         | 33.33%  |
| Upek             | 2         | 22.22%  |
| Broadcom         | 2         | 22.22%  |
| SCM Microsystems | 1         | 11.11%  |
| O2 Micro         | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 33.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 22.22%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Broadcom 5880                                                                | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 191       | 57.88%  |
| 1     | 107       | 32.42%  |
| 2     | 24        | 7.27%   |
| 3     | 5         | 1.52%   |
| 6     | 1         | 0.3%    |
| 5     | 1         | 0.3%    |
| 4     | 1         | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 71        | 40.57%  |
| Graphics card            | 40        | 22.86%  |
| Net/wireless             | 23        | 13.14%  |
| Multimedia controller    | 15        | 8.57%   |
| Chipcard                 | 9         | 5.14%   |
| Sound                    | 5         | 2.86%   |
| Communication controller | 4         | 2.29%   |
| Bluetooth                | 3         | 1.71%   |
| Net/ethernet             | 2         | 1.14%   |
| Camera                   | 2         | 1.14%   |
| Unassigned class         | 1         | 0.57%   |

