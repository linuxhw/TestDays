Linux in South Korea - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in South Korea.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/South_Korea/Desktop/README.md) and [notebooks](/Location/South_Korea/Notebook/README.md).

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

Total: 897

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Pelco by S... | DS-SRV2 S584XF01            | Desktop     | [7ed2a57a58](https://linux-hardware.org/?probe=7ed2a57a58) | Jan 03, 2025 |
| ASUSTek       | PN53                        | Mini pc     | [2029a257eb](https://linux-hardware.org/?probe=2029a257eb) | Jan 01, 2025 |
| HP            | Pavilion g6                 | Notebook    | [ea52acdc1b](https://linux-hardware.org/?probe=ea52acdc1b) | Dec 30, 2024 |
| Samsung       | 960XGK                      | Notebook    | [da507c038f](https://linux-hardware.org/?probe=da507c038f) | Dec 29, 2024 |
| Samsung       | 960XGK                      | Notebook    | [feec3e592b](https://linux-hardware.org/?probe=feec3e592b) | Dec 29, 2024 |
| Lenovo        | G500s Touch 20263           | Notebook    | [0dbe4fae1f](https://linux-hardware.org/?probe=0dbe4fae1f) | Dec 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [77f57a0535](https://linux-hardware.org/?probe=77f57a0535) | Dec 18, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [f27e2a89ad](https://linux-hardware.org/?probe=f27e2a89ad) | Dec 16, 2024 |
| Dell          | Inspiron 15 3520            | Notebook    | [42e7404664](https://linux-hardware.org/?probe=42e7404664) | Dec 16, 2024 |
| Dell          | Inspiron 5565               | Notebook    | [a7b0d7e13d](https://linux-hardware.org/?probe=a7b0d7e13d) | Dec 15, 2024 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [f51b8777e8](https://linux-hardware.org/?probe=f51b8777e8) | Dec 14, 2024 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [37664cf5d9](https://linux-hardware.org/?probe=37664cf5d9) | Dec 13, 2024 |
| Gigabyte      | AX370-Gaming 3-CF           | Desktop     | [0124649cba](https://linux-hardware.org/?probe=0124649cba) | Dec 10, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [07dbf8694f](https://linux-hardware.org/?probe=07dbf8694f) | Dec 02, 2024 |
| Samsung       | DB400TDA-Y0J/C SGLA933A0... | Desktop     | [60318edf7e](https://linux-hardware.org/?probe=60318edf7e) | Dec 02, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1666d53ef2](https://linux-hardware.org/?probe=1666d53ef2) | Nov 29, 2024 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [005802da6e](https://linux-hardware.org/?probe=005802da6e) | Nov 27, 2024 |
| ASUSTek       | PN53                        | Mini pc     | [a0eb126c3b](https://linux-hardware.org/?probe=a0eb126c3b) | Nov 26, 2024 |
| ASRock        | Z370 Pro4                   | Desktop     | [444d9d7d0b](https://linux-hardware.org/?probe=444d9d7d0b) | Nov 25, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [582b81fd6f](https://linux-hardware.org/?probe=582b81fd6f) | Nov 22, 2024 |
| Gigabyte      | H310M DS2V                  | Desktop     | [dbdc4d0b28](https://linux-hardware.org/?probe=dbdc4d0b28) | Nov 16, 2024 |
| Gigabyte      | H310M DS2V                  | Desktop     | [d7105643fd](https://linux-hardware.org/?probe=d7105643fd) | Nov 16, 2024 |
| MSI           | H110M PRO-D                 | Desktop     | [452d20c7fd](https://linux-hardware.org/?probe=452d20c7fd) | Nov 13, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [9c65e1c0fd](https://linux-hardware.org/?probe=9c65e1c0fd) | Nov 12, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [bea18d3e92](https://linux-hardware.org/?probe=bea18d3e92) | Nov 12, 2024 |
| Dell          | 0JRJM9 A06                  | Server      | [ca722566db](https://linux-hardware.org/?probe=ca722566db) | Nov 12, 2024 |
| Samsung       | 940XFG                      | Notebook    | [262a845d6d](https://linux-hardware.org/?probe=262a845d6d) | Nov 11, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [f33ffb3943](https://linux-hardware.org/?probe=f33ffb3943) | Nov 09, 2024 |
| Lenovo        | ThinkPad Edge E440 20C5A... | Notebook    | [1277be0ef5](https://linux-hardware.org/?probe=1277be0ef5) | Nov 09, 2024 |
| Intel         | NUC7JYB M37316-502          | Mini pc     | [5eeef27c54](https://linux-hardware.org/?probe=5eeef27c54) | Nov 08, 2024 |
| MSI           | H110M PRO-D                 | Desktop     | [57f9a23010](https://linux-hardware.org/?probe=57f9a23010) | Nov 08, 2024 |
| MACHINIST     | B450 TFA AM4 Ver:1.00       | Desktop     | [1c53ab0ce4](https://linux-hardware.org/?probe=1c53ab0ce4) | Nov 03, 2024 |
| ASRock        | B650 LiveMixer              | Desktop     | [1cae9e87fc](https://linux-hardware.org/?probe=1cae9e87fc) | Oct 25, 2024 |
| LG Electro... | 15ZD90S-GX56K               | Notebook    | [e9630cc537](https://linux-hardware.org/?probe=e9630cc537) | Oct 23, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [88c68a9636](https://linux-hardware.org/?probe=88c68a9636) | Oct 19, 2024 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [f52f0612c7](https://linux-hardware.org/?probe=f52f0612c7) | Oct 15, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [90b6d6089f](https://linux-hardware.org/?probe=90b6d6089f) | Oct 02, 2024 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [edbbf74e3b](https://linux-hardware.org/?probe=edbbf74e3b) | Oct 01, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [ba5edb5b03](https://linux-hardware.org/?probe=ba5edb5b03) | Sep 24, 2024 |
| Dell          | XPS 13 9343                 | Notebook    | [ff5e0232e9](https://linux-hardware.org/?probe=ff5e0232e9) | Sep 23, 2024 |
| MSI           | Z68A-G45                    | Desktop     | [1ce550c189](https://linux-hardware.org/?probe=1ce550c189) | Sep 23, 2024 |
| Dell          | XPS 12 9Q23                 | Notebook    | [b842f0a090](https://linux-hardware.org/?probe=b842f0a090) | Sep 21, 2024 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [550001d98f](https://linux-hardware.org/?probe=550001d98f) | Sep 20, 2024 |
| Samsung       | 960XGL                      | Notebook    | [a8d96a5b4b](https://linux-hardware.org/?probe=a8d96a5b4b) | Sep 20, 2024 |
| Samsung       | 950QCG                      | Convertible | [622f53b194](https://linux-hardware.org/?probe=622f53b194) | Sep 17, 2024 |
| Lenovo        | ThinkPad E550 20DF004HKD    | Notebook    | [3f884bbbaa](https://linux-hardware.org/?probe=3f884bbbaa) | Sep 17, 2024 |
| ASRock        | B660M Pro RS                | Desktop     | [e76b66c215](https://linux-hardware.org/?probe=e76b66c215) | Sep 10, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [126ae0aa3e](https://linux-hardware.org/?probe=126ae0aa3e) | Sep 07, 2024 |
| SZQFTX        | MI2-SC                      | Desktop     | [354ecda750](https://linux-hardware.org/?probe=354ecda750) | Sep 06, 2024 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [a2599a2d08](https://linux-hardware.org/?probe=a2599a2d08) | Sep 03, 2024 |
| HP            | Elite x2 G4                 | Tablet      | [2f639c1b11](https://linux-hardware.org/?probe=2f639c1b11) | Sep 01, 2024 |
| MSI           | MPG Z790 EDGE TI MAX WIF... | Desktop     | [65e4e049fb](https://linux-hardware.org/?probe=65e4e049fb) | Aug 26, 2024 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [cb33d4fa31](https://linux-hardware.org/?probe=cb33d4fa31) | Aug 25, 2024 |
| ASUSTek       | Z87-C                       | Desktop     | [8950e85ffb](https://linux-hardware.org/?probe=8950e85ffb) | Aug 23, 2024 |
| Intel         | NUC10i5FNB M38063-308       | Mini pc     | [5a70530a45](https://linux-hardware.org/?probe=5a70530a45) | Aug 22, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [15d1dd3590](https://linux-hardware.org/?probe=15d1dd3590) | Aug 17, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c3958fd4a3](https://linux-hardware.org/?probe=c3958fd4a3) | Aug 15, 2024 |
| ASRock        | B650 LiveMixer              | Desktop     | [5570dc6d1f](https://linux-hardware.org/?probe=5570dc6d1f) | Aug 13, 2024 |
| Nvidia        | Jetson Orin NX Engineeri... | Soc         | [698590cbb5](https://linux-hardware.org/?probe=698590cbb5) | Aug 11, 2024 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [24119bdb5e](https://linux-hardware.org/?probe=24119bdb5e) | Aug 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [5b4b2e4b60](https://linux-hardware.org/?probe=5b4b2e4b60) | Aug 05, 2024 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [c4eb58cf86](https://linux-hardware.org/?probe=c4eb58cf86) | Aug 05, 2024 |
| Samsung       | R530/R730                   | Notebook    | [74c1021e6f](https://linux-hardware.org/?probe=74c1021e6f) | Aug 03, 2024 |
| ASRock        | 970A-G                      | Desktop     | [7d66332210](https://linux-hardware.org/?probe=7d66332210) | Jul 26, 2024 |
| Unknown       | Unknown                     | Notebook    | [fa8cf70193](https://linux-hardware.org/?probe=fa8cf70193) | Jul 24, 2024 |
| MSI           | MPG Z690 EDGE WIFI          | Desktop     | [48f334b6ed](https://linux-hardware.org/?probe=48f334b6ed) | Jul 19, 2024 |
| Supermicro    | X11SCL-F                    | Server      | [aef6db08c4](https://linux-hardware.org/?probe=aef6db08c4) | Jul 18, 2024 |
| HANSUNG CO... | TFX252XA                    | Notebook    | [ebd5e2f006](https://linux-hardware.org/?probe=ebd5e2f006) | Jul 17, 2024 |
| ASRock        | X300M-STX                   | Desktop     | [724187bcd6](https://linux-hardware.org/?probe=724187bcd6) | Jul 13, 2024 |
| Samsung       | 950QCG                      | Convertible | [f30ac28568](https://linux-hardware.org/?probe=f30ac28568) | Jul 10, 2024 |
| SZQFTX        | MI2-SC                      | Desktop     | [c95dd74d91](https://linux-hardware.org/?probe=c95dd74d91) | Jul 07, 2024 |
| Lenovo        | ThinkBook 14 G5 ABP 21JE    | Notebook    | [908c65a585](https://linux-hardware.org/?probe=908c65a585) | Jun 25, 2024 |
| ASUSTek       | H310M-C/HDMI R2.0           | Desktop     | [8767868edd](https://linux-hardware.org/?probe=8767868edd) | Jun 25, 2024 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [eeb56a32fb](https://linux-hardware.org/?probe=eeb56a32fb) | Jun 23, 2024 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | Notebook    | [af5c648347](https://linux-hardware.org/?probe=af5c648347) | Jun 22, 2024 |
| Gigabyte      | F2A88X-UP4                  | Desktop     | [0c0aa2515c](https://linux-hardware.org/?probe=0c0aa2515c) | Jun 18, 2024 |
| Gigabyte      | F2A88X-UP4                  | Desktop     | [385923ca25](https://linux-hardware.org/?probe=385923ca25) | Jun 10, 2024 |
| ASUSTek       | ROG Maximus Z790 FORMULA    | Desktop     | [99d8c9e8b1](https://linux-hardware.org/?probe=99d8c9e8b1) | Jun 02, 2024 |
| Lenovo        | 310B NOK                    | Mini pc     | [051456a924](https://linux-hardware.org/?probe=051456a924) | May 30, 2024 |
| LG Electro... | 15Z90Q-GA76K                | Notebook    | [59a67bd575](https://linux-hardware.org/?probe=59a67bd575) | May 30, 2024 |
| ASUSTek       | Z10PE-D16 Series            | Desktop     | [52a0a645ba](https://linux-hardware.org/?probe=52a0a645ba) | May 27, 2024 |
| Shuttle       | FH170                       | Desktop     | [0a04e61b00](https://linux-hardware.org/?probe=0a04e61b00) | May 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [4080a2a217](https://linux-hardware.org/?probe=4080a2a217) | May 22, 2024 |
| Shuttle       | FH170                       | Desktop     | [5103536dc4](https://linux-hardware.org/?probe=5103536dc4) | May 18, 2024 |
| ASUSTek       | H110M-A                     | Desktop     | [16c08bf32a](https://linux-hardware.org/?probe=16c08bf32a) | May 14, 2024 |
| MiTAC         | 9525                        | Notebook    | [0088b01ddd](https://linux-hardware.org/?probe=0088b01ddd) | May 11, 2024 |
| MiTAC         | 9525                        | Notebook    | [943ec75005](https://linux-hardware.org/?probe=943ec75005) | May 11, 2024 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [40478abcae](https://linux-hardware.org/?probe=40478abcae) | May 10, 2024 |
| Samsung       | 930QED                      | Convertible | [efc32670b1](https://linux-hardware.org/?probe=efc32670b1) | May 09, 2024 |
| Unknown       | Unknown                     | Notebook    | [8876712f97](https://linux-hardware.org/?probe=8876712f97) | May 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [7cbaf2743a](https://linux-hardware.org/?probe=7cbaf2743a) | May 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [728da6c7b1](https://linux-hardware.org/?probe=728da6c7b1) | May 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [5f8e391778](https://linux-hardware.org/?probe=5f8e391778) | May 04, 2024 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [614efe1b07](https://linux-hardware.org/?probe=614efe1b07) | May 02, 2024 |
| LG Electro... | 14Z90S-GA5HK                | Notebook    | [ba55286732](https://linux-hardware.org/?probe=ba55286732) | May 02, 2024 |
| Gigabyte      | H110M-DS2V-CF               | Desktop     | [40fe788bf0](https://linux-hardware.org/?probe=40fe788bf0) | Apr 14, 2024 |
| SZQFTX        | MI2-SC                      | Desktop     | [be8172007e](https://linux-hardware.org/?probe=be8172007e) | Apr 11, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [e39dfad279](https://linux-hardware.org/?probe=e39dfad279) | Apr 10, 2024 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | Notebook    | [d003568e7a](https://linux-hardware.org/?probe=d003568e7a) | Apr 08, 2024 |
| ASRock        | B150M Pro4                  | Desktop     | [75a5d3af57](https://linux-hardware.org/?probe=75a5d3af57) | Apr 06, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [4f2f3edceb](https://linux-hardware.org/?probe=4f2f3edceb) | Apr 04, 2024 |
| Gigabyte      | H81M-D2V                    | Desktop     | [6bc3e596e6](https://linux-hardware.org/?probe=6bc3e596e6) | Mar 28, 2024 |
| SZQFTX        | MI2-SC                      | Desktop     | [4364c74d90](https://linux-hardware.org/?probe=4364c74d90) | Mar 26, 2024 |
| ASUSTek       | H110M-A                     | Desktop     | [fc2fe23179](https://linux-hardware.org/?probe=fc2fe23179) | Mar 22, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [d63edacb71](https://linux-hardware.org/?probe=d63edacb71) | Mar 15, 2024 |
| Samsung       | 950QED                      | Convertible | [c560f5e8e7](https://linux-hardware.org/?probe=c560f5e8e7) | Mar 14, 2024 |
| Valve         | Galileo                     | Notebook    | [d816b83ec2](https://linux-hardware.org/?probe=d816b83ec2) | Mar 10, 2024 |
| Google        | Panther                     | Desktop     | [9fee846e7c](https://linux-hardware.org/?probe=9fee846e7c) | Mar 09, 2024 |
| Google        | Panther                     | Desktop     | [9b94bb7555](https://linux-hardware.org/?probe=9b94bb7555) | Mar 09, 2024 |
| INRUKO        | HM87S V2.5                  | Desktop     | [b422e4c8ab](https://linux-hardware.org/?probe=b422e4c8ab) | Mar 06, 2024 |
| HP            | Pavilion dv5                | Notebook    | [b0752dc7dc](https://linux-hardware.org/?probe=b0752dc7dc) | Mar 04, 2024 |
| Chuwi         | Hi10 Go                     | Notebook    | [8f143f6874](https://linux-hardware.org/?probe=8f143f6874) | Mar 01, 2024 |
| Acer          | Swift SF314-71              | Notebook    | [52c7804b0e](https://linux-hardware.org/?probe=52c7804b0e) | Feb 29, 2024 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [995aadf8a1](https://linux-hardware.org/?probe=995aadf8a1) | Feb 28, 2024 |
| ASRock        | X670E PG Lightning          | Notebook    | [d3ef0930d7](https://linux-hardware.org/?probe=d3ef0930d7) | Feb 28, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [7bc1964f22](https://linux-hardware.org/?probe=7bc1964f22) | Feb 24, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [f537e67907](https://linux-hardware.org/?probe=f537e67907) | Feb 23, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [225c50ba01](https://linux-hardware.org/?probe=225c50ba01) | Feb 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [13504f6300](https://linux-hardware.org/?probe=13504f6300) | Feb 20, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [4fb324edd0](https://linux-hardware.org/?probe=4fb324edd0) | Feb 19, 2024 |
| Apple         | MacBookPro11,5              | Notebook    | [e342f33cae](https://linux-hardware.org/?probe=e342f33cae) | Feb 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [d4ffec2f30](https://linux-hardware.org/?probe=d4ffec2f30) | Feb 15, 2024 |
| Samsung       | 940XFG                      | Notebook    | [dd9f6ec593](https://linux-hardware.org/?probe=dd9f6ec593) | Feb 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [79819299d1](https://linux-hardware.org/?probe=79819299d1) | Feb 13, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [7d93273d71](https://linux-hardware.org/?probe=7d93273d71) | Feb 08, 2024 |
| Samsung       | 940XFG                      | Notebook    | [5dea9b20b4](https://linux-hardware.org/?probe=5dea9b20b4) | Jan 30, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [8dd7c2b2aa](https://linux-hardware.org/?probe=8dd7c2b2aa) | Jan 25, 2024 |
| LG Electro... | 15Z95P-GRLGL                | Notebook    | [ce6c983048](https://linux-hardware.org/?probe=ce6c983048) | Jan 24, 2024 |
| LG Electro... | 15Z95P-GRLGL                | Notebook    | [9dcc8bbc45](https://linux-hardware.org/?probe=9dcc8bbc45) | Jan 24, 2024 |
| Samsung       | 940XGK                      | Notebook    | [786fb90f91](https://linux-hardware.org/?probe=786fb90f91) | Jan 22, 2024 |
| Samsung       | 940XGK                      | Notebook    | [90cea105a0](https://linux-hardware.org/?probe=90cea105a0) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4fe05dec99](https://linux-hardware.org/?probe=4fe05dec99) | Jan 18, 2024 |
| Dell          | Inspiron 16 5620            | Notebook    | [6ee5c8e435](https://linux-hardware.org/?probe=6ee5c8e435) | Jan 11, 2024 |
| Dell          | Inspiron 5515               | Notebook    | [ced5a24737](https://linux-hardware.org/?probe=ced5a24737) | Jan 08, 2024 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [ddc660cbfb](https://linux-hardware.org/?probe=ddc660cbfb) | Jan 06, 2024 |
| Dell          | Inspiron 5515               | Notebook    | [32aeaa1e64](https://linux-hardware.org/?probe=32aeaa1e64) | Jan 06, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [7baccc479c](https://linux-hardware.org/?probe=7baccc479c) | Dec 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [d11d965739](https://linux-hardware.org/?probe=d11d965739) | Dec 29, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [cb215ce5f6](https://linux-hardware.org/?probe=cb215ce5f6) | Dec 28, 2023 |
| AZW           | SER V1                      | Desktop     | [9491b3dfb6](https://linux-hardware.org/?probe=9491b3dfb6) | Dec 28, 2023 |
| Samsung       | 940XFG                      | Notebook    | [ca5d181ce4](https://linux-hardware.org/?probe=ca5d181ce4) | Dec 25, 2023 |
| HP            | 212B                        | Desktop     | [8fa44a703b](https://linux-hardware.org/?probe=8fa44a703b) | Dec 22, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [ec4972e3b4](https://linux-hardware.org/?probe=ec4972e3b4) | Dec 22, 2023 |
| LG Electro... | 15ZD970-EX50K               | Notebook    | [f9836d5b54](https://linux-hardware.org/?probe=f9836d5b54) | Dec 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [147873adce](https://linux-hardware.org/?probe=147873adce) | Dec 18, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [18d321d9d6](https://linux-hardware.org/?probe=18d321d9d6) | Dec 06, 2023 |
| Unknown       | G-GLK01                     | Desktop     | [5c5efbafff](https://linux-hardware.org/?probe=5c5efbafff) | Dec 06, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [360f0c3419](https://linux-hardware.org/?probe=360f0c3419) | Nov 26, 2023 |
| Samsung       | 930SBE/931SBE/930SBV        | Convertible | [15675df06b](https://linux-hardware.org/?probe=15675df06b) | Nov 25, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [44bd871680](https://linux-hardware.org/?probe=44bd871680) | Nov 25, 2023 |
| Samsung       | 930SBE/931SBE/930SBV        | Convertible | [8c9cb8fcb0](https://linux-hardware.org/?probe=8c9cb8fcb0) | Nov 24, 2023 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [ad3926b9b4](https://linux-hardware.org/?probe=ad3926b9b4) | Nov 24, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [5b538b13b5](https://linux-hardware.org/?probe=5b538b13b5) | Nov 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [de44cb2821](https://linux-hardware.org/?probe=de44cb2821) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [0923bf86fb](https://linux-hardware.org/?probe=0923bf86fb) | Nov 23, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [79a1012336](https://linux-hardware.org/?probe=79a1012336) | Nov 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [4f49f31e87](https://linux-hardware.org/?probe=4f49f31e87) | Nov 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f4dc3b24c4](https://linux-hardware.org/?probe=f4dc3b24c4) | Nov 11, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [8e450b21e1](https://linux-hardware.org/?probe=8e450b21e1) | Nov 10, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [907a7f6dd8](https://linux-hardware.org/?probe=907a7f6dd8) | Nov 05, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [0e1711e674](https://linux-hardware.org/?probe=0e1711e674) | Oct 28, 2023 |
| Samsung       | DM700A4K-KN27 SGL8559A1A... | All in one  | [e6c0db51c1](https://linux-hardware.org/?probe=e6c0db51c1) | Oct 28, 2023 |
| Samsung       | 935QDB                      | Convertible | [0b2ea617b5](https://linux-hardware.org/?probe=0b2ea617b5) | Oct 27, 2023 |
| Samsung       | 935QDB                      | Convertible | [a132043246](https://linux-hardware.org/?probe=a132043246) | Oct 25, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [8f09f37e41](https://linux-hardware.org/?probe=8f09f37e41) | Oct 25, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [62d0c94205](https://linux-hardware.org/?probe=62d0c94205) | Oct 23, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3de8a2af66](https://linux-hardware.org/?probe=3de8a2af66) | Oct 23, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3036944fc9](https://linux-hardware.org/?probe=3036944fc9) | Oct 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [feee3cfca0](https://linux-hardware.org/?probe=feee3cfca0) | Oct 20, 2023 |
| IMUZ          | STORMBOOK14 APOLLO          | Notebook    | [6d8e8178b0](https://linux-hardware.org/?probe=6d8e8178b0) | Oct 19, 2023 |
| Lenovo        | 330B NOK                    | Mini pc     | [deeb2a4420](https://linux-hardware.org/?probe=deeb2a4420) | Oct 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [23768d9009](https://linux-hardware.org/?probe=23768d9009) | Oct 15, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [3d6223857b](https://linux-hardware.org/?probe=3d6223857b) | Oct 14, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | Desktop     | [bf515bb1b4](https://linux-hardware.org/?probe=bf515bb1b4) | Oct 12, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [67dcd68d2b](https://linux-hardware.org/?probe=67dcd68d2b) | Oct 06, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [691c015f6f](https://linux-hardware.org/?probe=691c015f6f) | Oct 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a8bea5ed82](https://linux-hardware.org/?probe=a8bea5ed82) | Sep 30, 2023 |
| Lenovo        | ThinkPad X230 2325KZ5       | Notebook    | [7c10f1a5de](https://linux-hardware.org/?probe=7c10f1a5de) | Sep 30, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [55c34c64a6](https://linux-hardware.org/?probe=55c34c64a6) | Sep 27, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [7941c7c6cc](https://linux-hardware.org/?probe=7941c7c6cc) | Sep 27, 2023 |
| ASRock        | H81M-DG6                    | Desktop     | [ac6944c3df](https://linux-hardware.org/?probe=ac6944c3df) | Sep 25, 2023 |
| ASUSTek       | X542UN                      | Notebook    | [76f91b9954](https://linux-hardware.org/?probe=76f91b9954) | Sep 24, 2023 |
| Dell          | 0CN7X8 A07                  | Server      | [3687b4358b](https://linux-hardware.org/?probe=3687b4358b) | Sep 19, 2023 |
| HP            | OMEN by Transcend Gaming... | Notebook    | [866ab5c907](https://linux-hardware.org/?probe=866ab5c907) | Sep 11, 2023 |
| HP            | OMEN by Transcend Gaming... | Notebook    | [2afa6e66d2](https://linux-hardware.org/?probe=2afa6e66d2) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [aa67f256bc](https://linux-hardware.org/?probe=aa67f256bc) | Sep 09, 2023 |
| Samsung       | 700T1C                      | Notebook    | [6240a5d18a](https://linux-hardware.org/?probe=6240a5d18a) | Sep 09, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [ecd59bd254](https://linux-hardware.org/?probe=ecd59bd254) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [2a900ea3bd](https://linux-hardware.org/?probe=2a900ea3bd) | Sep 03, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [da16406c15](https://linux-hardware.org/?probe=da16406c15) | Sep 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [269a4ac17d](https://linux-hardware.org/?probe=269a4ac17d) | Aug 28, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [215ff35620](https://linux-hardware.org/?probe=215ff35620) | Aug 27, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [2bb217b4df](https://linux-hardware.org/?probe=2bb217b4df) | Aug 23, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | Notebook    | [3c811f59ba](https://linux-hardware.org/?probe=3c811f59ba) | Aug 23, 2023 |
| Dell          | 07978V A10                  | Server      | [dcd73b2802](https://linux-hardware.org/?probe=dcd73b2802) | Aug 23, 2023 |
| ASUSTek       | GL502VMZ                    | Notebook    | [65952bbced](https://linux-hardware.org/?probe=65952bbced) | Aug 23, 2023 |
| Lenovo        | YB1-X91F                    | Tablet      | [0122f2caab](https://linux-hardware.org/?probe=0122f2caab) | Aug 23, 2023 |
| LG Electro... | 15Z990-VA5WK                | Notebook    | [51c419c795](https://linux-hardware.org/?probe=51c419c795) | Aug 23, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | Notebook    | [df8b84163a](https://linux-hardware.org/?probe=df8b84163a) | Aug 23, 2023 |
| Lenovo        | ThinkPad X230 2306AV4       | Notebook    | [d52720a4dc](https://linux-hardware.org/?probe=d52720a4dc) | Aug 21, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [b9701cd43c](https://linux-hardware.org/?probe=b9701cd43c) | Aug 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [1d87714ed5](https://linux-hardware.org/?probe=1d87714ed5) | Aug 20, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [f99d3dca93](https://linux-hardware.org/?probe=f99d3dca93) | Aug 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [b223cba859](https://linux-hardware.org/?probe=b223cba859) | Aug 14, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [0650746552](https://linux-hardware.org/?probe=0650746552) | Aug 13, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [fee93b31f5](https://linux-hardware.org/?probe=fee93b31f5) | Aug 13, 2023 |
| Lenovo        | IdeaPad Duet 3 11IAN8 82... | Tablet      | [b61e23d1ec](https://linux-hardware.org/?probe=b61e23d1ec) | Aug 12, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5892469c5b](https://linux-hardware.org/?probe=5892469c5b) | Aug 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [a9f30f8dd0](https://linux-hardware.org/?probe=a9f30f8dd0) | Aug 11, 2023 |
| HPE           | ProLiant DL380 Gen10        | Server      | [1db6058b8f](https://linux-hardware.org/?probe=1db6058b8f) | Aug 10, 2023 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a71dc0067b](https://linux-hardware.org/?probe=a71dc0067b) | Aug 07, 2023 |
| Notebook      | N650DU                      | Notebook    | [c04f4faa06](https://linux-hardware.org/?probe=c04f4faa06) | Jul 19, 2023 |
| HP            | Pavilion dv6                | Notebook    | [2abf53d250](https://linux-hardware.org/?probe=2abf53d250) | Jul 17, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [c9a443767b](https://linux-hardware.org/?probe=c9a443767b) | Jul 16, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [1c15fc53af](https://linux-hardware.org/?probe=1c15fc53af) | Jul 16, 2023 |
| Unknown       | NVIDIA Jetson Xavier NX ... | Soc         | [b9b08fd326](https://linux-hardware.org/?probe=b9b08fd326) | Jul 15, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [87a26e01e6](https://linux-hardware.org/?probe=87a26e01e6) | Jul 06, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [669754af36](https://linux-hardware.org/?probe=669754af36) | Jul 02, 2023 |
| Gigabyte      | A620M GAMING X              | Desktop     | [76238267ab](https://linux-hardware.org/?probe=76238267ab) | Jul 01, 2023 |
| Samsung       | Galaxy Book 12              | Tablet      | [570e99d65f](https://linux-hardware.org/?probe=570e99d65f) | Jun 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [09419812ab](https://linux-hardware.org/?probe=09419812ab) | Jun 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [856acf81ed](https://linux-hardware.org/?probe=856acf81ed) | Jun 22, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [16f2ca887d](https://linux-hardware.org/?probe=16f2ca887d) | Jun 20, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [4777b096a3](https://linux-hardware.org/?probe=4777b096a3) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | Notebook    | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [af90ec4131](https://linux-hardware.org/?probe=af90ec4131) | Jun 16, 2023 |
| HP            | ENVY Notebook               | Notebook    | [4a4602250b](https://linux-hardware.org/?probe=4a4602250b) | Jun 15, 2023 |
| HP            | ENVY Notebook               | Notebook    | [54115f309f](https://linux-hardware.org/?probe=54115f309f) | Jun 15, 2023 |
| Samsung       | 760XDA                      | Notebook    | [f0decf4dbe](https://linux-hardware.org/?probe=f0decf4dbe) | Jun 14, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [2fe8080014](https://linux-hardware.org/?probe=2fe8080014) | Jun 11, 2023 |
| Samsung       | 910S3L                      | Notebook    | [f8e59b4c0f](https://linux-hardware.org/?probe=f8e59b4c0f) | Jun 08, 2023 |
| Samsung       | 910S3L                      | Notebook    | [2db0ae25d8](https://linux-hardware.org/?probe=2db0ae25d8) | Jun 06, 2023 |
| ASRock        | B150M Pro4                  | Desktop     | [0b59eacbd3](https://linux-hardware.org/?probe=0b59eacbd3) | Jun 05, 2023 |
| ASRock        | X670E Taichi                | Desktop     | [6616151cda](https://linux-hardware.org/?probe=6616151cda) | Jun 04, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [95ec288436](https://linux-hardware.org/?probe=95ec288436) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [7720a9f71c](https://linux-hardware.org/?probe=7720a9f71c) | Jun 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [8a6ceb7d8b](https://linux-hardware.org/?probe=8a6ceb7d8b) | May 30, 2023 |
| Samsung       | 950XDC/951XDC/950XDX        | Notebook    | [105d3da269](https://linux-hardware.org/?probe=105d3da269) | May 30, 2023 |
| Samsung       | 900X5T                      | Notebook    | [9f1d226c85](https://linux-hardware.org/?probe=9f1d226c85) | May 25, 2023 |
| ASUSTek       | X542UN                      | Notebook    | [29547f8e99](https://linux-hardware.org/?probe=29547f8e99) | May 24, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [e197af6a9f](https://linux-hardware.org/?probe=e197af6a9f) | May 20, 2023 |
| ECS           | PB02CF                      | Server      | [ae43167b8a](https://linux-hardware.org/?probe=ae43167b8a) | May 19, 2023 |
| ECS           | PB02CF                      | Server      | [b2830721b2](https://linux-hardware.org/?probe=b2830721b2) | May 19, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [f4fce509ae](https://linux-hardware.org/?probe=f4fce509ae) | May 18, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [2d07f38ffa](https://linux-hardware.org/?probe=2d07f38ffa) | May 17, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [de6d4ede23](https://linux-hardware.org/?probe=de6d4ede23) | May 17, 2023 |
| ASUSTek       | PN51-S1                     | Mini pc     | [18e6ede132](https://linux-hardware.org/?probe=18e6ede132) | May 12, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [64353c7d87](https://linux-hardware.org/?probe=64353c7d87) | May 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [efc35b1887](https://linux-hardware.org/?probe=efc35b1887) | May 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [0225c3c300](https://linux-hardware.org/?probe=0225c3c300) | May 09, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [abb92fef7d](https://linux-hardware.org/?probe=abb92fef7d) | May 06, 2023 |
| Lenovo        | 7Y51CTO1WW                  | Server      | [a2fd0bc88c](https://linux-hardware.org/?probe=a2fd0bc88c) | May 04, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [5195c623c0](https://linux-hardware.org/?probe=5195c623c0) | May 02, 2023 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [4541d2e721](https://linux-hardware.org/?probe=4541d2e721) | May 02, 2023 |
| ASRock        | Z370 Extreme4               | Desktop     | [0f126ade53](https://linux-hardware.org/?probe=0f126ade53) | Apr 29, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [dca43563dd](https://linux-hardware.org/?probe=dca43563dd) | Apr 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [658450824e](https://linux-hardware.org/?probe=658450824e) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [bab80153bf](https://linux-hardware.org/?probe=bab80153bf) | Apr 22, 2023 |
| Lenovo        | E520-15IKB 80WA             | Notebook    | [abd1d98b9b](https://linux-hardware.org/?probe=abd1d98b9b) | Apr 20, 2023 |
| Dell          | 0MR5MV A00                  | Desktop     | [ed13b58a51](https://linux-hardware.org/?probe=ed13b58a51) | Apr 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [62399bace9](https://linux-hardware.org/?probe=62399bace9) | Apr 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [1f3ed1329d](https://linux-hardware.org/?probe=1f3ed1329d) | Apr 16, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [91946b965a](https://linux-hardware.org/?probe=91946b965a) | Apr 13, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [30fdc58d69](https://linux-hardware.org/?probe=30fdc58d69) | Apr 12, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [9b39bc4979](https://linux-hardware.org/?probe=9b39bc4979) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [674533c5cd](https://linux-hardware.org/?probe=674533c5cd) | Apr 12, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [9ddd50e0ed](https://linux-hardware.org/?probe=9ddd50e0ed) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [36338ecf6e](https://linux-hardware.org/?probe=36338ecf6e) | Apr 05, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f4343acc49](https://linux-hardware.org/?probe=f4343acc49) | Apr 03, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [3e558165a4](https://linux-hardware.org/?probe=3e558165a4) | Apr 02, 2023 |
| Gigabyte      | GA-6LXSG 01234567           | Server      | [92bff0d0ac](https://linux-hardware.org/?probe=92bff0d0ac) | Apr 01, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [758bb2556e](https://linux-hardware.org/?probe=758bb2556e) | Apr 01, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [dfd9900ccf](https://linux-hardware.org/?probe=dfd9900ccf) | Mar 30, 2023 |
| Notebook      | N650DU                      | Notebook    | [e8ec3c6462](https://linux-hardware.org/?probe=e8ec3c6462) | Mar 30, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [bf2f7820cd](https://linux-hardware.org/?probe=bf2f7820cd) | Mar 29, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [7febdf82c0](https://linux-hardware.org/?probe=7febdf82c0) | Mar 28, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [fa7272f576](https://linux-hardware.org/?probe=fa7272f576) | Mar 27, 2023 |
| Apple         | MacBook9,1                  | Notebook    | [9639f02d57](https://linux-hardware.org/?probe=9639f02d57) | Mar 25, 2023 |
| WEIPAI        | S15                         | Notebook    | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | Desktop     | [19a060d86d](https://linux-hardware.org/?probe=19a060d86d) | Mar 20, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [9404efe255](https://linux-hardware.org/?probe=9404efe255) | Mar 18, 2023 |
| Gigabyte      | GB-BSi7A-6500               | Notebook    | [5a9b5297c2](https://linux-hardware.org/?probe=5a9b5297c2) | Mar 16, 2023 |
| ECS2          | EASTWOOD2 V1.0              | Desktop     | [822e4fa621](https://linux-hardware.org/?probe=822e4fa621) | Mar 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [0d12931010](https://linux-hardware.org/?probe=0d12931010) | Mar 11, 2023 |
| Dell          | 0TNXNR A01                  | Desktop     | [30fa0c9cb7](https://linux-hardware.org/?probe=30fa0c9cb7) | Mar 09, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [09ce898081](https://linux-hardware.org/?probe=09ce898081) | Mar 02, 2023 |
| Dell          | Latitude E5440              | Notebook    | [25cf039ffd](https://linux-hardware.org/?probe=25cf039ffd) | Feb 27, 2023 |
| Dell          | Latitude E5440              | Notebook    | [5546f00169](https://linux-hardware.org/?probe=5546f00169) | Feb 26, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [484e0755de](https://linux-hardware.org/?probe=484e0755de) | Feb 26, 2023 |
| HP            | Elite Dragonfly G2 Noteb... | Convertible | [51e3518d50](https://linux-hardware.org/?probe=51e3518d50) | Feb 24, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [a3ea522d78](https://linux-hardware.org/?probe=a3ea522d78) | Feb 23, 2023 |
| Samsung       | 760XDA                      | Notebook    | [efa040a93f](https://linux-hardware.org/?probe=efa040a93f) | Feb 22, 2023 |
| Samsung       | 760XDA                      | Notebook    | [1ba36d420d](https://linux-hardware.org/?probe=1ba36d420d) | Feb 22, 2023 |
| Gigabyte      | GB-BSi7A-6500               | Notebook    | [6ec55330a7](https://linux-hardware.org/?probe=6ec55330a7) | Feb 21, 2023 |
| Samsung       | DB400T7Y-Z202C SGL9325A0... | Desktop     | [b75c596e7f](https://linux-hardware.org/?probe=b75c596e7f) | Feb 21, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | Desktop     | [5b452754c0](https://linux-hardware.org/?probe=5b452754c0) | Feb 19, 2023 |
| HPE           | ProLiant DL380 Gen10        | Server      | [c03dee89f6](https://linux-hardware.org/?probe=c03dee89f6) | Feb 17, 2023 |
| HP            | Elite Dragonfly G2 Noteb... | Convertible | [a9d6ae7b72](https://linux-hardware.org/?probe=a9d6ae7b72) | Feb 17, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [bafba5486b](https://linux-hardware.org/?probe=bafba5486b) | Feb 16, 2023 |
| Samsung       | 940XFG                      | Notebook    | [56f236f8ab](https://linux-hardware.org/?probe=56f236f8ab) | Feb 16, 2023 |
| ASRock        | Z790 Pro RS WiFi            | Desktop     | [c530bf4283](https://linux-hardware.org/?probe=c530bf4283) | Feb 11, 2023 |
| Samsung       | 900X5N                      | Notebook    | [91793918de](https://linux-hardware.org/?probe=91793918de) | Feb 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [d1da7498da](https://linux-hardware.org/?probe=d1da7498da) | Feb 02, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [b9fb1c5111](https://linux-hardware.org/?probe=b9fb1c5111) | Feb 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [9b17a7541e](https://linux-hardware.org/?probe=9b17a7541e) | Jan 30, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [697b0d8654](https://linux-hardware.org/?probe=697b0d8654) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [bb5e9ccd98](https://linux-hardware.org/?probe=bb5e9ccd98) | Jan 27, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [d54e25d6fb](https://linux-hardware.org/?probe=d54e25d6fb) | Jan 27, 2023 |
| HP            | Notebook                    | Notebook    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| ASUSTek       | X540UA                      | Notebook    | [39f992a141](https://linux-hardware.org/?probe=39f992a141) | Jan 22, 2023 |
| ASUSTek       | X540UA                      | Notebook    | [dda62597f7](https://linux-hardware.org/?probe=dda62597f7) | Jan 21, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [6c8d492f56](https://linux-hardware.org/?probe=6c8d492f56) | Jan 19, 2023 |
| HPE           | ProLiant DL380 Gen10        | Server      | [2ddc21d71f](https://linux-hardware.org/?probe=2ddc21d71f) | Jan 16, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [8975ee2ce6](https://linux-hardware.org/?probe=8975ee2ce6) | Jan 14, 2023 |
| HPE           | ProLiant DL380 Gen10        | Server      | [2f6c800e41](https://linux-hardware.org/?probe=2f6c800e41) | Jan 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [dfca68067c](https://linux-hardware.org/?probe=dfca68067c) | Jan 10, 2023 |
| Samsung       | 760XDA                      | Notebook    | [06a850e558](https://linux-hardware.org/?probe=06a850e558) | Jan 10, 2023 |
| Samsung       | 760XDA                      | Notebook    | [180727ef64](https://linux-hardware.org/?probe=180727ef64) | Jan 10, 2023 |
| HPE           | ProLiant DL380 Gen10        | Server      | [37818477e0](https://linux-hardware.org/?probe=37818477e0) | Jan 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [49d1097b37](https://linux-hardware.org/?probe=49d1097b37) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [2fbec34211](https://linux-hardware.org/?probe=2fbec34211) | Jan 07, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [a56af08eb5](https://linux-hardware.org/?probe=a56af08eb5) | Jan 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [e47684954b](https://linux-hardware.org/?probe=e47684954b) | Jan 04, 2023 |
| ELSKY         | M219FN-6C                   | Desktop     | [95862529f8](https://linux-hardware.org/?probe=95862529f8) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eda96539d7](https://linux-hardware.org/?probe=eda96539d7) | Dec 26, 2022 |
| Lenovo        | ThinkPad E585 20KVS06F00    | Notebook    | [8c3bdcc48c](https://linux-hardware.org/?probe=8c3bdcc48c) | Dec 25, 2022 |
| Jooyon Tec... | J6BF                        | Notebook    | [dabe200abe](https://linux-hardware.org/?probe=dabe200abe) | Dec 23, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [f244715ee3](https://linux-hardware.org/?probe=f244715ee3) | Dec 22, 2022 |
| ASRock        | H470M Pro4                  | Desktop     | [b69ccc3353](https://linux-hardware.org/?probe=b69ccc3353) | Dec 22, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [2ebd48d256](https://linux-hardware.org/?probe=2ebd48d256) | Dec 22, 2022 |
| Gigabyte      | AERO 15 YC                  | Notebook    | [24e48000be](https://linux-hardware.org/?probe=24e48000be) | Dec 22, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [d6f3d14b20](https://linux-hardware.org/?probe=d6f3d14b20) | Dec 22, 2022 |
| Gigabyte      | Z490 AORUS XTREME WF        | Desktop     | [7020686bc7](https://linux-hardware.org/?probe=7020686bc7) | Dec 19, 2022 |
| LG Electro... | 15UD480-GX50K               | Notebook    | [16be4a033d](https://linux-hardware.org/?probe=16be4a033d) | Dec 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [24182862cd](https://linux-hardware.org/?probe=24182862cd) | Dec 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [cfe8d55199](https://linux-hardware.org/?probe=cfe8d55199) | Dec 14, 2022 |
| Samsung       | 550XED                      | Notebook    | [8e5bdc1eab](https://linux-hardware.org/?probe=8e5bdc1eab) | Dec 14, 2022 |
| Samsung       | 550XED                      | Notebook    | [3165e8b2df](https://linux-hardware.org/?probe=3165e8b2df) | Dec 14, 2022 |
| ASUSTek       | Zenbook UP6502ZA_UP6502Z... | Convertible | [85c2b907d7](https://linux-hardware.org/?probe=85c2b907d7) | Dec 14, 2022 |
| Lenovo        | ThinkPad X260 20F6007KKR    | Notebook    | [9b788f857e](https://linux-hardware.org/?probe=9b788f857e) | Dec 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [a2f1af21a0](https://linux-hardware.org/?probe=a2f1af21a0) | Dec 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [a505c76dfa](https://linux-hardware.org/?probe=a505c76dfa) | Dec 13, 2022 |
| LG Electro... | 15ND530-GX3FK               | Notebook    | [47b90cbe2a](https://linux-hardware.org/?probe=47b90cbe2a) | Dec 12, 2022 |
| Google        | Peppy                       | Notebook    | [59f9af1c52](https://linux-hardware.org/?probe=59f9af1c52) | Dec 10, 2022 |
| Huanan        | X58-RX3.0 V110              | Desktop     | [32e6a4d219](https://linux-hardware.org/?probe=32e6a4d219) | Dec 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5S... | Notebook    | [7772d8b9f8](https://linux-hardware.org/?probe=7772d8b9f8) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [5254612ca4](https://linux-hardware.org/?probe=5254612ca4) | Dec 09, 2022 |
| Samsung       | 550XED                      | Notebook    | [705495532e](https://linux-hardware.org/?probe=705495532e) | Dec 09, 2022 |
| Samsung       | 550XED                      | Notebook    | [0df3845885](https://linux-hardware.org/?probe=0df3845885) | Dec 08, 2022 |
| Lenovo        | ThinkPad T61 889502U        | Notebook    | [b9d0a07e47](https://linux-hardware.org/?probe=b9d0a07e47) | Dec 08, 2022 |
| Lenovo        | ThinkPad T60 1953PKK        | Notebook    | [fc308e2f1c](https://linux-hardware.org/?probe=fc308e2f1c) | Dec 08, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [e13e889312](https://linux-hardware.org/?probe=e13e889312) | Dec 08, 2022 |
| Samsung       | 550XED                      | Notebook    | [0ce3bd481f](https://linux-hardware.org/?probe=0ce3bd481f) | Dec 07, 2022 |
| Lenovo        | ThinkPad E495 20NES0J800    | Notebook    | [17182155b5](https://linux-hardware.org/?probe=17182155b5) | Dec 07, 2022 |
| Lenovo        | 370A NOK                    | Desktop     | [b06728a8bf](https://linux-hardware.org/?probe=b06728a8bf) | Dec 05, 2022 |
| Dell          | 00D7V6 A00                  | Desktop     | [6047fbcb06](https://linux-hardware.org/?probe=6047fbcb06) | Dec 05, 2022 |
| Dell          | 00D7V6 A00                  | Desktop     | [9aebb424cc](https://linux-hardware.org/?probe=9aebb424cc) | Dec 05, 2022 |
| Samsung       | 550XED                      | Notebook    | [fee55cdb61](https://linux-hardware.org/?probe=fee55cdb61) | Dec 02, 2022 |
| Samsung       | 550XED                      | Notebook    | [d8894f602a](https://linux-hardware.org/?probe=d8894f602a) | Dec 01, 2022 |
| Gigabyte      | Z490 AORUS XTREME WF        | Desktop     | [6d4f229020](https://linux-hardware.org/?probe=6d4f229020) | Nov 29, 2022 |
| Dell          | Latitude E5440              | Notebook    | [90d18073d6](https://linux-hardware.org/?probe=90d18073d6) | Nov 29, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [5ec5306c0f](https://linux-hardware.org/?probe=5ec5306c0f) | Nov 28, 2022 |
| Samsung       | 550XED                      | Notebook    | [143518e596](https://linux-hardware.org/?probe=143518e596) | Nov 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [d96c2be612](https://linux-hardware.org/?probe=d96c2be612) | Nov 23, 2022 |
| Samsung       | 950XED                      | Notebook    | [48213c8f60](https://linux-hardware.org/?probe=48213c8f60) | Nov 23, 2022 |
| TMAX          | TM101W638L                  | Tablet      | [ac8adad039](https://linux-hardware.org/?probe=ac8adad039) | Nov 22, 2022 |
| Samsung       | 950XED                      | Notebook    | [0c91469d8f](https://linux-hardware.org/?probe=0c91469d8f) | Nov 21, 2022 |
| Dell          | Latitude E5440              | Notebook    | [6d90726959](https://linux-hardware.org/?probe=6d90726959) | Nov 21, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [2bc3a22052](https://linux-hardware.org/?probe=2bc3a22052) | Nov 20, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [d5c76baafa](https://linux-hardware.org/?probe=d5c76baafa) | Nov 18, 2022 |
| Samsung       | 550XED                      | Notebook    | [06722b1fee](https://linux-hardware.org/?probe=06722b1fee) | Nov 16, 2022 |
| Samsung       | 950XED                      | Notebook    | [2558d99814](https://linux-hardware.org/?probe=2558d99814) | Nov 16, 2022 |
| Samsung       | 950XED                      | Notebook    | [ddcb4e15c7](https://linux-hardware.org/?probe=ddcb4e15c7) | Nov 14, 2022 |
| Samsung       | 550XED                      | Notebook    | [bbebe45363](https://linux-hardware.org/?probe=bbebe45363) | Nov 13, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [9d91de9f87](https://linux-hardware.org/?probe=9d91de9f87) | Nov 12, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [da754cf27a](https://linux-hardware.org/?probe=da754cf27a) | Nov 11, 2022 |
| Samsung       | 550XED                      | Notebook    | [60c1aa4cc9](https://linux-hardware.org/?probe=60c1aa4cc9) | Nov 10, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [0ccbbf67e8](https://linux-hardware.org/?probe=0ccbbf67e8) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [9cdaa4c88b](https://linux-hardware.org/?probe=9cdaa4c88b) | Nov 09, 2022 |
| Samsung       | 550XED                      | Notebook    | [fc6d96f9fe](https://linux-hardware.org/?probe=fc6d96f9fe) | Nov 06, 2022 |
| Samsung       | 550XED                      | Notebook    | [6db345f53d](https://linux-hardware.org/?probe=6db345f53d) | Nov 03, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| Samsung       | 550XED                      | Notebook    | [6992db47be](https://linux-hardware.org/?probe=6992db47be) | Nov 02, 2022 |
| Samsung       | 950XED                      | Notebook    | [821bc59c17](https://linux-hardware.org/?probe=821bc59c17) | Nov 02, 2022 |
| Samsung       | 550XED                      | Notebook    | [3b04d21991](https://linux-hardware.org/?probe=3b04d21991) | Nov 01, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [025e3e7e4e](https://linux-hardware.org/?probe=025e3e7e4e) | Nov 01, 2022 |
| MS            | MPGIO                       | Notebook    | [4fc8637bf3](https://linux-hardware.org/?probe=4fc8637bf3) | Nov 01, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| WTM           | W-N95 B0                    | Desktop     | [56611d3c8f](https://linux-hardware.org/?probe=56611d3c8f) | Oct 31, 2022 |
| LG Electro... | 15Z980-HA76K                | Notebook    | [914156672d](https://linux-hardware.org/?probe=914156672d) | Oct 30, 2022 |
| Samsung       | 950XED                      | Notebook    | [350a0f9d44](https://linux-hardware.org/?probe=350a0f9d44) | Oct 28, 2022 |
| Samsung       | 550XED                      | Notebook    | [1ebb9be92b](https://linux-hardware.org/?probe=1ebb9be92b) | Oct 28, 2022 |
| Samsung       | 550XED                      | Notebook    | [110d85c2e0](https://linux-hardware.org/?probe=110d85c2e0) | Oct 27, 2022 |
| Samsung       | 950XED                      | Notebook    | [a636a02096](https://linux-hardware.org/?probe=a636a02096) | Oct 27, 2022 |
| HP            | 8425                        | Desktop     | [6d26af6597](https://linux-hardware.org/?probe=6d26af6597) | Oct 27, 2022 |
| LG Electro... | 15Z90N-HA76K                | Notebook    | [7805c272fb](https://linux-hardware.org/?probe=7805c272fb) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [866d0f49a2](https://linux-hardware.org/?probe=866d0f49a2) | Oct 20, 2022 |
| Dell          | Precision 7520              | Notebook    | [366eed3b66](https://linux-hardware.org/?probe=366eed3b66) | Oct 20, 2022 |
| Dell          | Precision 7520              | Notebook    | [8c2829bbb2](https://linux-hardware.org/?probe=8c2829bbb2) | Oct 19, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [8665ee6ba6](https://linux-hardware.org/?probe=8665ee6ba6) | Oct 19, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [7979753fa9](https://linux-hardware.org/?probe=7979753fa9) | Oct 15, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [ad1d808caa](https://linux-hardware.org/?probe=ad1d808caa) | Oct 14, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6580d55237](https://linux-hardware.org/?probe=6580d55237) | Oct 09, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [40dd630e96](https://linux-hardware.org/?probe=40dd630e96) | Oct 05, 2022 |
| Lenovo        | 3135 NOK                    | Mini pc     | [bffdecaf8f](https://linux-hardware.org/?probe=bffdecaf8f) | Oct 04, 2022 |
| Lenovo        | 3135 NOK                    | Mini pc     | [4b13ced18f](https://linux-hardware.org/?probe=4b13ced18f) | Oct 04, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [d4797ada2a](https://linux-hardware.org/?probe=d4797ada2a) | Sep 28, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [ff511df5c2](https://linux-hardware.org/?probe=ff511df5c2) | Sep 27, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [2fccc9ec66](https://linux-hardware.org/?probe=2fccc9ec66) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [e777d38fbd](https://linux-hardware.org/?probe=e777d38fbd) | Sep 26, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [5c2eac6d83](https://linux-hardware.org/?probe=5c2eac6d83) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [82b3d89bf9](https://linux-hardware.org/?probe=82b3d89bf9) | Sep 20, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [ea7d5b0424](https://linux-hardware.org/?probe=ea7d5b0424) | Sep 18, 2022 |
| Alienware     | 0CPDXD A00                  | Desktop     | [f65bdb053d](https://linux-hardware.org/?probe=f65bdb053d) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [22171cc2a6](https://linux-hardware.org/?probe=22171cc2a6) | Sep 07, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [156da35e98](https://linux-hardware.org/?probe=156da35e98) | Aug 24, 2022 |
| ASUSTek       | Zephyrus S GX531GX_GX531... | Notebook    | [0041774402](https://linux-hardware.org/?probe=0041774402) | Aug 20, 2022 |
| Samsung       | 950QDA                      | Convertible | [e03a1c1a0d](https://linux-hardware.org/?probe=e03a1c1a0d) | Aug 16, 2022 |
| MSI           | MAG B660M MORTAR WIFI       | Desktop     | [4e1b75908c](https://linux-hardware.org/?probe=4e1b75908c) | Aug 13, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [ab0da3a7ec](https://linux-hardware.org/?probe=ab0da3a7ec) | Aug 07, 2022 |
| ASRock        | B250M Pro4                  | Desktop     | [59704c823a](https://linux-hardware.org/?probe=59704c823a) | Jul 29, 2022 |
| PCPartner     | MILANO-P Rev.00             | Desktop     | [1b6d72c5ac](https://linux-hardware.org/?probe=1b6d72c5ac) | Jul 18, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5bdae5b8f7](https://linux-hardware.org/?probe=5bdae5b8f7) | Jul 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YJC... | Notebook    | [ce2df1e866](https://linux-hardware.org/?probe=ce2df1e866) | Jul 18, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [cf71ced9a0](https://linux-hardware.org/?probe=cf71ced9a0) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [cf470317b1](https://linux-hardware.org/?probe=cf470317b1) | Jul 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [87edfcaadf](https://linux-hardware.org/?probe=87edfcaadf) | Jul 09, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [8971b67abc](https://linux-hardware.org/?probe=8971b67abc) | Jul 08, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [251bc4d58d](https://linux-hardware.org/?probe=251bc4d58d) | Jul 04, 2022 |
| Gigabyte      | C621-SD8 M18802             | Server      | [52aeaedd47](https://linux-hardware.org/?probe=52aeaedd47) | Jun 30, 2022 |
| Gigabyte      | MQLP5AP-00                  | Desktop     | [8014a14842](https://linux-hardware.org/?probe=8014a14842) | Jun 30, 2022 |
| LG Electro... | 14T90N-VR56K                | Convertible | [22f978c26c](https://linux-hardware.org/?probe=22f978c26c) | Jun 26, 2022 |
| Lenovo        | ThinkPad S2 20GJA00S00      | Notebook    | [44eb58334d](https://linux-hardware.org/?probe=44eb58334d) | Jun 24, 2022 |
| LG Electro... | 14Z90N-VA76K                | Notebook    | [9e606a176f](https://linux-hardware.org/?probe=9e606a176f) | Jun 24, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [b93d65dd64](https://linux-hardware.org/?probe=b93d65dd64) | Jun 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [3e3fb0129e](https://linux-hardware.org/?probe=3e3fb0129e) | Jun 18, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [95ec23c2e9](https://linux-hardware.org/?probe=95ec23c2e9) | Jun 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | Notebook    | [014c9a184e](https://linux-hardware.org/?probe=014c9a184e) | Jun 06, 2022 |
| LG Electro... | Z360-GH6SK                  | Notebook    | [cb91c2c2bd](https://linux-hardware.org/?probe=cb91c2c2bd) | Jun 02, 2022 |
| HP            | Spectre 13 x2 PC            | Notebook    | [9b67243691](https://linux-hardware.org/?probe=9b67243691) | May 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4f941ba9fe](https://linux-hardware.org/?probe=4f941ba9fe) | May 24, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [617edab20c](https://linux-hardware.org/?probe=617edab20c) | May 20, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [6aea229376](https://linux-hardware.org/?probe=6aea229376) | May 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [feb7ce77bf](https://linux-hardware.org/?probe=feb7ce77bf) | May 18, 2022 |
| Gigabyte      | TRX40 AORUS XTREME          | Desktop     | [2d23125cd0](https://linux-hardware.org/?probe=2d23125cd0) | May 15, 2022 |
| LG Electro... | 15Z990-HA50K                | Notebook    | [e5cf57d2f4](https://linux-hardware.org/?probe=e5cf57d2f4) | May 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [7286fd4e36](https://linux-hardware.org/?probe=7286fd4e36) | May 11, 2022 |
| Gigabyte      | X99-SLI-CF                  | Desktop     | [55f1cc4480](https://linux-hardware.org/?probe=55f1cc4480) | May 10, 2022 |
| Lenovo        | ThinkPad 8 20BN0002KR       | Tablet      | [8e59716f95](https://linux-hardware.org/?probe=8e59716f95) | May 07, 2022 |
| Alienware     | 0CPDXD A00                  | Desktop     | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [80bdc044eb](https://linux-hardware.org/?probe=80bdc044eb) | May 01, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [6df44e9098](https://linux-hardware.org/?probe=6df44e9098) | Apr 29, 2022 |
| Teclast       | tPAD                        | Notebook    | [2b86292373](https://linux-hardware.org/?probe=2b86292373) | Apr 20, 2022 |
| Samsung       | Galaxy Book 12              | Tablet      | [a4d7160eb9](https://linux-hardware.org/?probe=a4d7160eb9) | Apr 17, 2022 |
| Samsung       | Galaxy Book 12              | Tablet      | [71624fff28](https://linux-hardware.org/?probe=71624fff28) | Apr 17, 2022 |
| Wolfnfox      | WF-TBAT                     | Notebook    | [7d04cc8361](https://linux-hardware.org/?probe=7d04cc8361) | Apr 13, 2022 |
| Teclast       | tPAD                        | Notebook    | [a9f93e289b](https://linux-hardware.org/?probe=a9f93e289b) | Apr 13, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [9a15614b1e](https://linux-hardware.org/?probe=9a15614b1e) | Apr 13, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [ed880374c4](https://linux-hardware.org/?probe=ed880374c4) | Apr 10, 2022 |
| MECHREVO      | Taitan Series GM7TG0M       | Notebook    | [948d29a218](https://linux-hardware.org/?probe=948d29a218) | Apr 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [ccbdd7504c](https://linux-hardware.org/?probe=ccbdd7504c) | Apr 08, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [14b7f50736](https://linux-hardware.org/?probe=14b7f50736) | Apr 08, 2022 |
| Teclast       | tPAD                        | Notebook    | [5eddc816df](https://linux-hardware.org/?probe=5eddc816df) | Apr 07, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [1874ac7edf](https://linux-hardware.org/?probe=1874ac7edf) | Apr 03, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [f22fa67906](https://linux-hardware.org/?probe=f22fa67906) | Apr 01, 2022 |
| HP            | Stream Notebook PC 11       | Notebook    | [8fc09857a6](https://linux-hardware.org/?probe=8fc09857a6) | Apr 01, 2022 |
| Intel         | powered classmate PC        | Notebook    | [8ce4fa1757](https://linux-hardware.org/?probe=8ce4fa1757) | Apr 01, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [90aa422ea2](https://linux-hardware.org/?probe=90aa422ea2) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [6c36c54313](https://linux-hardware.org/?probe=6c36c54313) | Mar 31, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a8cacc7845](https://linux-hardware.org/?probe=a8cacc7845) | Mar 27, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [fa4526e9f3](https://linux-hardware.org/?probe=fa4526e9f3) | Mar 24, 2022 |
| MSI           | GF75 Thin 9SCXR             | Notebook    | [df19241968](https://linux-hardware.org/?probe=df19241968) | Mar 20, 2022 |
| ECS           | PB02CF                      | Server      | [0600880dba](https://linux-hardware.org/?probe=0600880dba) | Mar 19, 2022 |
| MSI           | GF75 Thin 9SCXR             | Notebook    | [b3458eda8f](https://linux-hardware.org/?probe=b3458eda8f) | Mar 14, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [4d5412852b](https://linux-hardware.org/?probe=4d5412852b) | Mar 13, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [05cdb119e9](https://linux-hardware.org/?probe=05cdb119e9) | Mar 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [f86d99b8a1](https://linux-hardware.org/?probe=f86d99b8a1) | Feb 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [95ff70277e](https://linux-hardware.org/?probe=95ff70277e) | Feb 24, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [bb04a03420](https://linux-hardware.org/?probe=bb04a03420) | Feb 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [38ad42c186](https://linux-hardware.org/?probe=38ad42c186) | Feb 22, 2022 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [968b189e38](https://linux-hardware.org/?probe=968b189e38) | Feb 21, 2022 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [d8f6d95994](https://linux-hardware.org/?probe=d8f6d95994) | Feb 14, 2022 |
| HANSUNG CO... | EX58                        | Notebook    | [7c2a023530](https://linux-hardware.org/?probe=7c2a023530) | Feb 10, 2022 |
| HP            | Spectre 13 x2 PC            | Notebook    | [ed95e4c1c7](https://linux-hardware.org/?probe=ed95e4c1c7) | Feb 09, 2022 |
| HP            | Spectre 13 x2 PC            | Notebook    | [a597b083c9](https://linux-hardware.org/?probe=a597b083c9) | Feb 08, 2022 |
| Google        | Ampton                      | Notebook    | [0f1564bb4a](https://linux-hardware.org/?probe=0f1564bb4a) | Feb 06, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [7742fa4642](https://linux-hardware.org/?probe=7742fa4642) | Feb 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [65a6ca3880](https://linux-hardware.org/?probe=65a6ca3880) | Feb 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [144717a1f1](https://linux-hardware.org/?probe=144717a1f1) | Feb 04, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [14f8855baa](https://linux-hardware.org/?probe=14f8855baa) | Feb 03, 2022 |
| ECS           | PB02CF                      | Server      | [9f7f807004](https://linux-hardware.org/?probe=9f7f807004) | Jan 30, 2022 |
| ECS           | PB02CF                      | Server      | [594030dfa1](https://linux-hardware.org/?probe=594030dfa1) | Jan 30, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [7f9793a709](https://linux-hardware.org/?probe=7f9793a709) | Jan 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [2c22ac6a5f](https://linux-hardware.org/?probe=2c22ac6a5f) | Jan 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [882dab7b0e](https://linux-hardware.org/?probe=882dab7b0e) | Jan 22, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [c081d60b2a](https://linux-hardware.org/?probe=c081d60b2a) | Jan 22, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [11d1870f98](https://linux-hardware.org/?probe=11d1870f98) | Jan 21, 2022 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [d0d21d2892](https://linux-hardware.org/?probe=d0d21d2892) | Jan 18, 2022 |
| LG Electro... | 16ZD90P-GX7LK               | Notebook    | [0870fd8772](https://linux-hardware.org/?probe=0870fd8772) | Dec 29, 2021 |
| Lenovo        | G480 20149                  | Notebook    | [08a0d07d28](https://linux-hardware.org/?probe=08a0d07d28) | Dec 28, 2021 |
| Quanta        | QSSC-98J_C2 31S98MB0040     | Server      | [23e536f087](https://linux-hardware.org/?probe=23e536f087) | Dec 28, 2021 |
| Quanta        | QSSC-98J_C2 31S98MB0040     | Server      | [1f4a9c160f](https://linux-hardware.org/?probe=1f4a9c160f) | Dec 28, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [a8fbe33d19](https://linux-hardware.org/?probe=a8fbe33d19) | Dec 26, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7843ddc3fb](https://linux-hardware.org/?probe=7843ddc3fb) | Dec 24, 2021 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | Desktop     | [151434ab61](https://linux-hardware.org/?probe=151434ab61) | Dec 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [ff620ffdcd](https://linux-hardware.org/?probe=ff620ffdcd) | Dec 07, 2021 |
| ECS           | PB02CF                      | Server      | [ac300533fe](https://linux-hardware.org/?probe=ac300533fe) | Dec 04, 2021 |
| Jooyontech... | J3GP Pro                    | Notebook    | [6f13d68344](https://linux-hardware.org/?probe=6f13d68344) | Dec 04, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | Notebook    | [c7cc850f29](https://linux-hardware.org/?probe=c7cc850f29) | Dec 03, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | Notebook    | [901fdc3726](https://linux-hardware.org/?probe=901fdc3726) | Dec 03, 2021 |
| Lenovo        | 1036 SDK0T76457 WIN 3915... | Desktop     | [f894442edc](https://linux-hardware.org/?probe=f894442edc) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [4d11bd6b59](https://linux-hardware.org/?probe=4d11bd6b59) | Nov 20, 2021 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [b4c7522ea3](https://linux-hardware.org/?probe=b4c7522ea3) | Nov 15, 2021 |
| Samsung       | 950QDA                      | Convertible | [45d49f2001](https://linux-hardware.org/?probe=45d49f2001) | Nov 13, 2021 |
| LG Electro... | 15Z990-HA50K                | Notebook    | [6f5255e0f2](https://linux-hardware.org/?probe=6f5255e0f2) | Nov 01, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [70074ebee1](https://linux-hardware.org/?probe=70074ebee1) | Nov 01, 2021 |
| ASUSTek       | X556URK                     | Notebook    | [212240b258](https://linux-hardware.org/?probe=212240b258) | Oct 29, 2021 |
| LG Electro... | 17ZD90P-GX7LK               | Notebook    | [23aa2c83ae](https://linux-hardware.org/?probe=23aa2c83ae) | Oct 27, 2021 |
| Intel         | NUC11PABi7 K90104-303       | Mini pc     | [0279a35638](https://linux-hardware.org/?probe=0279a35638) | Oct 27, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [19eba77c24](https://linux-hardware.org/?probe=19eba77c24) | Oct 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2f6634b953](https://linux-hardware.org/?probe=2f6634b953) | Oct 22, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fb8b55960a](https://linux-hardware.org/?probe=fb8b55960a) | Oct 20, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [4d966dec54](https://linux-hardware.org/?probe=4d966dec54) | Oct 03, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [de6577e71a](https://linux-hardware.org/?probe=de6577e71a) | Oct 03, 2021 |
| Lenovo        | ThinkPad W530 24475HU       | Notebook    | [b8973b3b0a](https://linux-hardware.org/?probe=b8973b3b0a) | Oct 02, 2021 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [e93b95fc3c](https://linux-hardware.org/?probe=e93b95fc3c) | Sep 30, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [fbc7a613a6](https://linux-hardware.org/?probe=fbc7a613a6) | Sep 29, 2021 |
| HANSUNG CO... | TFX4150H                    | Notebook    | [11f2fbef85](https://linux-hardware.org/?probe=11f2fbef85) | Sep 29, 2021 |
| ASUSTek       | U36JC                       | Notebook    | [c6e87f1fb7](https://linux-hardware.org/?probe=c6e87f1fb7) | Sep 23, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [23cf6f38e8](https://linux-hardware.org/?probe=23cf6f38e8) | Sep 21, 2021 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [54cd6887df](https://linux-hardware.org/?probe=54cd6887df) | Sep 21, 2021 |
| Clevo         | M740T/M760T                 | Notebook    | [7731b8340f](https://linux-hardware.org/?probe=7731b8340f) | Sep 17, 2021 |
| Samsung       | 400B4C/400B5C/200B4C/200... | Notebook    | [581ab7ecde](https://linux-hardware.org/?probe=581ab7ecde) | Sep 17, 2021 |
| LG Electro... | 16TD90P-GX56K               | Convertible | [448fe0cf6a](https://linux-hardware.org/?probe=448fe0cf6a) | Sep 11, 2021 |
| ECS           | PB02CF                      | Server      | [6aeb74b9f1](https://linux-hardware.org/?probe=6aeb74b9f1) | Sep 03, 2021 |
| ASRock        | AB350M Pro4                 | Desktop     | [24de612862](https://linux-hardware.org/?probe=24de612862) | Aug 31, 2021 |
| HP            | Pavilion Laptop 15z-eh00... | Notebook    | [33233b370e](https://linux-hardware.org/?probe=33233b370e) | Aug 30, 2021 |
| LG Electro... | 14Z90N-VA76K                | Notebook    | [df36a7a61c](https://linux-hardware.org/?probe=df36a7a61c) | Aug 22, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [3abd60af90](https://linux-hardware.org/?probe=3abd60af90) | Aug 22, 2021 |
| Lenovo        | XiaoXin Air 13IWL 81J8      | Notebook    | [e68dfe0824](https://linux-hardware.org/?probe=e68dfe0824) | Aug 19, 2021 |
| Apple         | MacBookPro15,2              | Notebook    | [c722c00c56](https://linux-hardware.org/?probe=c722c00c56) | Aug 18, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e47beb0587](https://linux-hardware.org/?probe=e47beb0587) | Aug 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e7997203d4](https://linux-hardware.org/?probe=e7997203d4) | Aug 11, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [3147760301](https://linux-hardware.org/?probe=3147760301) | Aug 07, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [e523ad86d2](https://linux-hardware.org/?probe=e523ad86d2) | Aug 02, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [901bcb991b](https://linux-hardware.org/?probe=901bcb991b) | Jul 31, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [1e96b02bf3](https://linux-hardware.org/?probe=1e96b02bf3) | Jul 28, 2021 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [dc6d809e73](https://linux-hardware.org/?probe=dc6d809e73) | Jul 23, 2021 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [c0869b1919](https://linux-hardware.org/?probe=c0869b1919) | Jul 23, 2021 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [972c061d3c](https://linux-hardware.org/?probe=972c061d3c) | Jul 22, 2021 |
| Gigabyte      | Z390 D                      | Desktop     | [8bf86066a5](https://linux-hardware.org/?probe=8bf86066a5) | Jul 22, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [4c15433f48](https://linux-hardware.org/?probe=4c15433f48) | Jul 21, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [2392366002](https://linux-hardware.org/?probe=2392366002) | Jul 16, 2021 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| HP            | 3397                        | Desktop     | [b9b07bdc0a](https://linux-hardware.org/?probe=b9b07bdc0a) | Jul 09, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae45f90535](https://linux-hardware.org/?probe=ae45f90535) | Jul 05, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [fd48c4cd51](https://linux-hardware.org/?probe=fd48c4cd51) | Jul 02, 2021 |
| Lenovo        | 14ARE05 81X2                | Convertible | [3cd1b703c4](https://linux-hardware.org/?probe=3cd1b703c4) | Jun 28, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [d2f1ec957f](https://linux-hardware.org/?probe=d2f1ec957f) | Jun 27, 2021 |
| ASRockRack    | WC621D8A-2T                 | Desktop     | [d9c47162dc](https://linux-hardware.org/?probe=d9c47162dc) | Jun 25, 2021 |
| ASRockRack    | WC621D8A-2T                 | Desktop     | [b568edaa5e](https://linux-hardware.org/?probe=b568edaa5e) | Jun 25, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [9c2b77b3c6](https://linux-hardware.org/?probe=9c2b77b3c6) | Jun 24, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [99b25335b3](https://linux-hardware.org/?probe=99b25335b3) | Jun 22, 2021 |
| WB            | J3160                       | All in one  | [88c472d69e](https://linux-hardware.org/?probe=88c472d69e) | Jun 18, 2021 |
| WB            | J3160                       | All in one  | [b889890a54](https://linux-hardware.org/?probe=b889890a54) | Jun 11, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [98faadcfa3](https://linux-hardware.org/?probe=98faadcfa3) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a19b25100c](https://linux-hardware.org/?probe=a19b25100c) | Jun 08, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [9aaad9b2d4](https://linux-hardware.org/?probe=9aaad9b2d4) | Jun 07, 2021 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [5742c8e4e5](https://linux-hardware.org/?probe=5742c8e4e5) | May 28, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | Desktop     | [be07a70b2e](https://linux-hardware.org/?probe=be07a70b2e) | May 27, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [2aca6cd805](https://linux-hardware.org/?probe=2aca6cd805) | May 27, 2021 |
| Dell          | Latitude E6400              | Notebook    | [2a4c5f6eec](https://linux-hardware.org/?probe=2a4c5f6eec) | May 25, 2021 |
| Samsung       | R440/R480                   | Notebook    | [777c05d80b](https://linux-hardware.org/?probe=777c05d80b) | May 19, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [15a742842f](https://linux-hardware.org/?probe=15a742842f) | May 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f3cb68f8cf](https://linux-hardware.org/?probe=f3cb68f8cf) | May 13, 2021 |
| HP            | EliteBook 8540p (WQ983PA... | Notebook    | [28b1df49ae](https://linux-hardware.org/?probe=28b1df49ae) | May 11, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [3d6a52dd8e](https://linux-hardware.org/?probe=3d6a52dd8e) | May 11, 2021 |
| Intel         | NUC7i7BNB J31145-309        | Mini pc     | [a9245eb585](https://linux-hardware.org/?probe=a9245eb585) | May 11, 2021 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [965bc51c8d](https://linux-hardware.org/?probe=965bc51c8d) | May 06, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | Notebook    | [035481a413](https://linux-hardware.org/?probe=035481a413) | May 05, 2021 |
| ASRock        | A75M-ITX                    | Desktop     | [1ad3e30eec](https://linux-hardware.org/?probe=1ad3e30eec) | May 03, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [473f17b0f1](https://linux-hardware.org/?probe=473f17b0f1) | May 01, 2021 |
| LG Electro... | 15ND530-GX30K               | Notebook    | [9d700ce0b6](https://linux-hardware.org/?probe=9d700ce0b6) | Apr 30, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [84f31a5fd7](https://linux-hardware.org/?probe=84f31a5fd7) | Apr 28, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [167aa11de4](https://linux-hardware.org/?probe=167aa11de4) | Apr 26, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [72d14b2ed7](https://linux-hardware.org/?probe=72d14b2ed7) | Apr 23, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | Notebook    | [410e4fd232](https://linux-hardware.org/?probe=410e4fd232) | Apr 22, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2300013263](https://linux-hardware.org/?probe=2300013263) | Apr 18, 2021 |
| HP            | Stream Notebook PC 13       | Notebook    | [0bf3f6f761](https://linux-hardware.org/?probe=0bf3f6f761) | Apr 15, 2021 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [fdac2fa1fd](https://linux-hardware.org/?probe=fdac2fa1fd) | Apr 14, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [b17bb9b31a](https://linux-hardware.org/?probe=b17bb9b31a) | Apr 12, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [a0686a3f62](https://linux-hardware.org/?probe=a0686a3f62) | Apr 11, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [7e77253d59](https://linux-hardware.org/?probe=7e77253d59) | Apr 11, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [c5e7a3d16e](https://linux-hardware.org/?probe=c5e7a3d16e) | Apr 09, 2021 |
| Notebook      | NL5xRU                      | Notebook    | [7cac175bde](https://linux-hardware.org/?probe=7cac175bde) | Apr 07, 2021 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [d4399ab9d0](https://linux-hardware.org/?probe=d4399ab9d0) | Apr 06, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [51931e3821](https://linux-hardware.org/?probe=51931e3821) | Apr 05, 2021 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [b36716f462](https://linux-hardware.org/?probe=b36716f462) | Apr 02, 2021 |
| Samsung       | 400B4B/400B5B/200B4B/200... | Notebook    | [af785987c5](https://linux-hardware.org/?probe=af785987c5) | Mar 29, 2021 |
| LG Electro... | Z435-GE40K                  | Notebook    | [41dfc50f20](https://linux-hardware.org/?probe=41dfc50f20) | Mar 27, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Lenovo        | ThinkPad 10 20C1001VKR      | Tablet      | [9b7a2a3d3b](https://linux-hardware.org/?probe=9b7a2a3d3b) | Mar 25, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [b55dc75624](https://linux-hardware.org/?probe=b55dc75624) | Mar 20, 2021 |
| Gigabyte      | B360M DS3H                  | Desktop     | [f7740321e0](https://linux-hardware.org/?probe=f7740321e0) | Mar 18, 2021 |
| MSI           | B75MA-E33                   | Desktop     | [e459ded47c](https://linux-hardware.org/?probe=e459ded47c) | Mar 10, 2021 |
| Alienware     | m15 R4                      | Notebook    | [33977ceca8](https://linux-hardware.org/?probe=33977ceca8) | Mar 08, 2021 |
| Notebook      | W330SU2                     | Notebook    | [e5e71a4e94](https://linux-hardware.org/?probe=e5e71a4e94) | Mar 05, 2021 |
| Dell          | Inspiron 5590               | Notebook    | [94e3d38a99](https://linux-hardware.org/?probe=94e3d38a99) | Mar 04, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [15c42588c8](https://linux-hardware.org/?probe=15c42588c8) | Mar 04, 2021 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [541a436664](https://linux-hardware.org/?probe=541a436664) | Mar 02, 2021 |
| ASRock        | H110M-HDVP2                 | Desktop     | [8e6128682d](https://linux-hardware.org/?probe=8e6128682d) | Feb 28, 2021 |
| ASRock        | H110M-HDVP2                 | Desktop     | [778fcc3093](https://linux-hardware.org/?probe=778fcc3093) | Feb 28, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [774a5efd77](https://linux-hardware.org/?probe=774a5efd77) | Feb 25, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8dd1ebdfb8](https://linux-hardware.org/?probe=8dd1ebdfb8) | Feb 25, 2021 |
| Notebook      | N650DU                      | Notebook    | [beef9a4540](https://linux-hardware.org/?probe=beef9a4540) | Feb 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [7ffa9ae08a](https://linux-hardware.org/?probe=7ffa9ae08a) | Feb 17, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [a222f11ebf](https://linux-hardware.org/?probe=a222f11ebf) | Feb 09, 2021 |
| ECS           | PB02CF                      | Server      | [598d43b1f2](https://linux-hardware.org/?probe=598d43b1f2) | Feb 08, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [0de61d3d11](https://linux-hardware.org/?probe=0de61d3d11) | Feb 06, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [65aa2efd23](https://linux-hardware.org/?probe=65aa2efd23) | Feb 05, 2021 |
| ASRock        | H110M-HDVP2                 | Desktop     | [27d324f7e1](https://linux-hardware.org/?probe=27d324f7e1) | Feb 04, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [fc703c19dd](https://linux-hardware.org/?probe=fc703c19dd) | Feb 02, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [ba5f1e074b](https://linux-hardware.org/?probe=ba5f1e074b) | Feb 02, 2021 |
| MSI           | B360M PRO-VDH               | Desktop     | [59b7bd58df](https://linux-hardware.org/?probe=59b7bd58df) | Jan 30, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [a29449d114](https://linux-hardware.org/?probe=a29449d114) | Jan 27, 2021 |
| ECS           | PB02CF                      | Server      | [4c644b0fa9](https://linux-hardware.org/?probe=4c644b0fa9) | Jan 26, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [9595d4107b](https://linux-hardware.org/?probe=9595d4107b) | Jan 26, 2021 |
| sunxi         | Unknown                     | Soc         | [49e15041c4](https://linux-hardware.org/?probe=49e15041c4) | Jan 26, 2021 |
| HP            | Pavilion dv3                | Notebook    | [d563465019](https://linux-hardware.org/?probe=d563465019) | Jan 23, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [a6226b7401](https://linux-hardware.org/?probe=a6226b7401) | Jan 20, 2021 |
| HP            | Pavilion dv3                | Notebook    | [7140d63f79](https://linux-hardware.org/?probe=7140d63f79) | Jan 16, 2021 |
| LG Electro... | 13Z940-MF6BL                | Notebook    | [ee9f312333](https://linux-hardware.org/?probe=ee9f312333) | Jan 16, 2021 |
| ECS           | PB02CF                      | Server      | [79ed88ad12](https://linux-hardware.org/?probe=79ed88ad12) | Jan 13, 2021 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [ffa2d06213](https://linux-hardware.org/?probe=ffa2d06213) | Jan 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [28d2ddf944](https://linux-hardware.org/?probe=28d2ddf944) | Jan 04, 2021 |
| HP            | 18E7                        | Desktop     | [e9590ba71a](https://linux-hardware.org/?probe=e9590ba71a) | Jan 01, 2021 |
| LG Electro... | 10T370-L860K                | Tablet      | [a6ab074bb5](https://linux-hardware.org/?probe=a6ab074bb5) | Jan 01, 2021 |
| LG Electro... | 10T370-L860K                | Tablet      | [7a21765d3b](https://linux-hardware.org/?probe=7a21765d3b) | Jan 01, 2021 |
| ASUSTek       | TUF Gaming FA706II_FA706... | Notebook    | [cbc872e471](https://linux-hardware.org/?probe=cbc872e471) | Dec 29, 2020 |
| HANSUNG CO... | TFX5470H                    | Notebook    | [4f038027ac](https://linux-hardware.org/?probe=4f038027ac) | Dec 27, 2020 |
| HANSUNG CO... | TFX5470H                    | Notebook    | [659c45927e](https://linux-hardware.org/?probe=659c45927e) | Dec 26, 2020 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [deb549d3e1](https://linux-hardware.org/?probe=deb549d3e1) | Dec 21, 2020 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [4245e53af4](https://linux-hardware.org/?probe=4245e53af4) | Dec 20, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [77ad294d93](https://linux-hardware.org/?probe=77ad294d93) | Dec 20, 2020 |
| HP            | Pavilion g6                 | Notebook    | [9b2e1ccb17](https://linux-hardware.org/?probe=9b2e1ccb17) | Dec 15, 2020 |
| HP            | Pavilion g6                 | Notebook    | [01bd113f0d](https://linux-hardware.org/?probe=01bd113f0d) | Dec 15, 2020 |
| MSI           | PS42 Modern 8MO             | Notebook    | [c469679bd0](https://linux-hardware.org/?probe=c469679bd0) | Dec 14, 2020 |
| MSI           | B360M PRO-VDH               | Desktop     | [ae9a14bb34](https://linux-hardware.org/?probe=ae9a14bb34) | Dec 11, 2020 |
| HP            | ProBook 635 Aero G7 Note... | Notebook    | [9ff7890a24](https://linux-hardware.org/?probe=9ff7890a24) | Dec 11, 2020 |
| Gigabyte      | C621-SU8 M18818             | Server      | [7e93e1b694](https://linux-hardware.org/?probe=7e93e1b694) | Dec 11, 2020 |
| Gigabyte      | C621-SU8 M18818             | Server      | [6343846b09](https://linux-hardware.org/?probe=6343846b09) | Dec 11, 2020 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [b1476b4c51](https://linux-hardware.org/?probe=b1476b4c51) | Dec 09, 2020 |
| Samsung       | 760XBE                      | Notebook    | [7b117d1e93](https://linux-hardware.org/?probe=7b117d1e93) | Dec 08, 2020 |
| Samsung       | R440/R480                   | Notebook    | [2c57659a41](https://linux-hardware.org/?probe=2c57659a41) | Dec 06, 2020 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [a706242b44](https://linux-hardware.org/?probe=a706242b44) | Dec 05, 2020 |
| MSI           | B360M PRO-VDH               | Desktop     | [f16f5d30de](https://linux-hardware.org/?probe=f16f5d30de) | Dec 05, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [425fda9034](https://linux-hardware.org/?probe=425fda9034) | Dec 04, 2020 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [e6f9b2cf07](https://linux-hardware.org/?probe=e6f9b2cf07) | Dec 04, 2020 |
| Acer          | Swift SF314-54              | Notebook    | [e387afac15](https://linux-hardware.org/?probe=e387afac15) | Nov 29, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [b6570c8388](https://linux-hardware.org/?probe=b6570c8388) | Nov 28, 2020 |
| Apple         | MacBookPro10,1              | Notebook    | [ecfaa7232b](https://linux-hardware.org/?probe=ecfaa7232b) | Nov 28, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [eb842cd3c4](https://linux-hardware.org/?probe=eb842cd3c4) | Nov 25, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [2a9cc167d3](https://linux-hardware.org/?probe=2a9cc167d3) | Nov 25, 2020 |
| ASRock        | B85M Pro4                   | Desktop     | [0354f4d9bc](https://linux-hardware.org/?probe=0354f4d9bc) | Nov 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| ASRock        | B85M Pro4                   | Desktop     | [8dcc7ce213](https://linux-hardware.org/?probe=8dcc7ce213) | Nov 22, 2020 |
| Gigabyte      | H97M-D3H                    | Desktop     | [f9b97f5918](https://linux-hardware.org/?probe=f9b97f5918) | Nov 22, 2020 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [e4a465ff4c](https://linux-hardware.org/?probe=e4a465ff4c) | Nov 15, 2020 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [8a39cadb17](https://linux-hardware.org/?probe=8a39cadb17) | Nov 14, 2020 |
| ECS           | G31T-M7                     | Desktop     | [f93ce4415e](https://linux-hardware.org/?probe=f93ce4415e) | Nov 12, 2020 |
| PC Partner... | A236 0A                     | Desktop     | [14030da2e5](https://linux-hardware.org/?probe=14030da2e5) | Nov 10, 2020 |
| PC Partner... | A236 0A                     | Desktop     | [fc118d784c](https://linux-hardware.org/?probe=fc118d784c) | Nov 10, 2020 |
| ASUSTek       | P7P55D                      | Desktop     | [11e315efbd](https://linux-hardware.org/?probe=11e315efbd) | Nov 07, 2020 |
| Samsung       | SX11S                       | Notebook    | [7946db3be4](https://linux-hardware.org/?probe=7946db3be4) | Nov 05, 2020 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [9b33944102](https://linux-hardware.org/?probe=9b33944102) | Nov 04, 2020 |
| Samsung       | 930QAA                      | Convertible | [ed50ef80ea](https://linux-hardware.org/?probe=ed50ef80ea) | Nov 01, 2020 |
| Lenovo        | ThinkPad T580 20L9S06H00    | Notebook    | [4cda554e60](https://linux-hardware.org/?probe=4cda554e60) | Oct 31, 2020 |
| Samsung       | 930QAA                      | Convertible | [e0defd416b](https://linux-hardware.org/?probe=e0defd416b) | Oct 31, 2020 |
| LG Electro... | 14ZB990-GP70ML              | Notebook    | [7184b7e890](https://linux-hardware.org/?probe=7184b7e890) | Oct 29, 2020 |
| HANSUNG CO... | TFX5470H                    | Notebook    | [7a0c7ef25d](https://linux-hardware.org/?probe=7a0c7ef25d) | Oct 22, 2020 |
| ECS           | PB02CF                      | Server      | [d2a218790a](https://linux-hardware.org/?probe=d2a218790a) | Oct 18, 2020 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [39cc53a5e3](https://linux-hardware.org/?probe=39cc53a5e3) | Oct 13, 2020 |
| ECS           | PB02CF                      | Server      | [872240bfee](https://linux-hardware.org/?probe=872240bfee) | Oct 12, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [7f2d533ddf](https://linux-hardware.org/?probe=7f2d533ddf) | Oct 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [57c9a2fdbb](https://linux-hardware.org/?probe=57c9a2fdbb) | Oct 12, 2020 |
| Acer          | Aspire A514-52              | Notebook    | [151c57e477](https://linux-hardware.org/?probe=151c57e477) | Oct 11, 2020 |
| ECS           | PB02CF                      | Server      | [ee5e0d54ac](https://linux-hardware.org/?probe=ee5e0d54ac) | Oct 10, 2020 |
| ECS           | PB02CF                      | Server      | [2584572329](https://linux-hardware.org/?probe=2584572329) | Oct 10, 2020 |
| ECS           | PB02CF                      | Server      | [9ff606fe05](https://linux-hardware.org/?probe=9ff606fe05) | Oct 09, 2020 |
| Lenovo        | ThinkPad E595 20NFS01P00    | Notebook    | [5cce7e56d5](https://linux-hardware.org/?probe=5cce7e56d5) | Oct 02, 2020 |
| MSI           | MS-16F1                     | Notebook    | [94a744ecb7](https://linux-hardware.org/?probe=94a744ecb7) | Oct 01, 2020 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [3aba059c2c](https://linux-hardware.org/?probe=3aba059c2c) | Sep 24, 2020 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [c535500f86](https://linux-hardware.org/?probe=c535500f86) | Sep 24, 2020 |
| ASRock        | H310M-STX/COM               | Desktop     | [5b22b538ee](https://linux-hardware.org/?probe=5b22b538ee) | Sep 23, 2020 |
| MSI           | GE75 Raider 10SF            | Notebook    | [c5f31d8ff8](https://linux-hardware.org/?probe=c5f31d8ff8) | Sep 21, 2020 |
| MSI           | GE75 Raider 10SF            | Notebook    | [80b54a584c](https://linux-hardware.org/?probe=80b54a584c) | Sep 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [335490808b](https://linux-hardware.org/?probe=335490808b) | Sep 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [611b4d4515](https://linux-hardware.org/?probe=611b4d4515) | Sep 12, 2020 |
| Samsung       | SX11S                       | Notebook    | [de5f3f5244](https://linux-hardware.org/?probe=de5f3f5244) | Sep 10, 2020 |
| ASUSTek       | P5LD2                       | Desktop     | [56efa94b22](https://linux-hardware.org/?probe=56efa94b22) | Sep 09, 2020 |
| ASUSTek       | P5LD2                       | Desktop     | [00f5eba2ea](https://linux-hardware.org/?probe=00f5eba2ea) | Sep 09, 2020 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [e9eb75e83c](https://linux-hardware.org/?probe=e9eb75e83c) | Sep 09, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [934bb9c2ef](https://linux-hardware.org/?probe=934bb9c2ef) | Sep 09, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [7acf41575b](https://linux-hardware.org/?probe=7acf41575b) | Sep 09, 2020 |
| ASRock        | H81M-HDS                    | Desktop     | [8b55873fbd](https://linux-hardware.org/?probe=8b55873fbd) | Sep 07, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [0ed21172b2](https://linux-hardware.org/?probe=0ed21172b2) | Sep 07, 2020 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [56e8c74784](https://linux-hardware.org/?probe=56e8c74784) | Sep 05, 2020 |
| Lenovo        | ThinkPad T410s 2912AJ7      | Notebook    | [5b29fd8262](https://linux-hardware.org/?probe=5b29fd8262) | Sep 05, 2020 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [226702f09a](https://linux-hardware.org/?probe=226702f09a) | Sep 05, 2020 |
| LG Electro... | 15ND530-GX30K               | Notebook    | [8f8a5ce10c](https://linux-hardware.org/?probe=8f8a5ce10c) | Sep 04, 2020 |
| Foxconn       | H61MXE                      | Desktop     | [7a31014e98](https://linux-hardware.org/?probe=7a31014e98) | Sep 04, 2020 |
| ECS           | PB02CF                      | Server      | [4d441244a7](https://linux-hardware.org/?probe=4d441244a7) | Sep 03, 2020 |
| Lenovo        | ThinkPad X390 20SCCTO1WW    | Notebook    | [765a0cde4c](https://linux-hardware.org/?probe=765a0cde4c) | Sep 03, 2020 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [2ef3a6b6c8](https://linux-hardware.org/?probe=2ef3a6b6c8) | Sep 03, 2020 |
| Acer          | Swift SF315-41              | Notebook    | [c57a2c8249](https://linux-hardware.org/?probe=c57a2c8249) | Aug 26, 2020 |
| LG Electro... | A520-DEHRK                  | Notebook    | [33e6f6950c](https://linux-hardware.org/?probe=33e6f6950c) | Aug 20, 2020 |
| LG Electro... | ZD360-GD30K                 | Notebook    | [5f695a5cfd](https://linux-hardware.org/?probe=5f695a5cfd) | Aug 19, 2020 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [4eb75f039b](https://linux-hardware.org/?probe=4eb75f039b) | Aug 17, 2020 |
| Lenovo        | ThinkPad L420 7829AZ2       | Notebook    | [af5c485d91](https://linux-hardware.org/?probe=af5c485d91) | Aug 17, 2020 |
| ASUSTek       | UX31E                       | Notebook    | [107d53bd73](https://linux-hardware.org/?probe=107d53bd73) | Aug 14, 2020 |
| Lenovo        | ThinkPad Edge E440 20C50... | Notebook    | [e2a554e507](https://linux-hardware.org/?probe=e2a554e507) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [03abb9daf3](https://linux-hardware.org/?probe=03abb9daf3) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [2d296ca69c](https://linux-hardware.org/?probe=2d296ca69c) | Aug 11, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [4657a3e758](https://linux-hardware.org/?probe=4657a3e758) | Aug 11, 2020 |
| Lenovo        | ThinkPad T420s 417429U      | Notebook    | [a0cc9e062e](https://linux-hardware.org/?probe=a0cc9e062e) | Aug 09, 2020 |
| MSI           | GX60 3CC                    | Notebook    | [dabfcf887e](https://linux-hardware.org/?probe=dabfcf887e) | Aug 05, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [806b0f6ffc](https://linux-hardware.org/?probe=806b0f6ffc) | Aug 04, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [03dcb81800](https://linux-hardware.org/?probe=03dcb81800) | Aug 04, 2020 |
| Nvidia        | Tegra                       | Soc         | [db3eb249a1](https://linux-hardware.org/?probe=db3eb249a1) | Aug 02, 2020 |
| Nvidia        | Tegra                       | Soc         | [ce759d1ef8](https://linux-hardware.org/?probe=ce759d1ef8) | Aug 02, 2020 |
| LG Electro... | 14ZB990-GP70ML              | Notebook    | [953e68f29d](https://linux-hardware.org/?probe=953e68f29d) | Jul 29, 2020 |
| ASRock        | H61M-HVGS                   | Desktop     | [36c19012ed](https://linux-hardware.org/?probe=36c19012ed) | Jul 25, 2020 |
| ASRock        | H61M-HVGS                   | Desktop     | [ea9287adc1](https://linux-hardware.org/?probe=ea9287adc1) | Jul 25, 2020 |
| Samsung       | X120/X170/X171              | Notebook    | [d52c424e0f](https://linux-hardware.org/?probe=d52c424e0f) | Jul 12, 2020 |
| MSI           | PS63 Modern 8RC             | Notebook    | [1f2f8bb2cf](https://linux-hardware.org/?probe=1f2f8bb2cf) | Jul 06, 2020 |
| MSI           | PS63 Modern 8RC             | Notebook    | [ed2dc1f4eb](https://linux-hardware.org/?probe=ed2dc1f4eb) | Jul 05, 2020 |
| Sony          | SVF1421ESGW                 | Notebook    | [025b1a05fe](https://linux-hardware.org/?probe=025b1a05fe) | Jun 29, 2020 |
| ASRock        | Z390 Taichi                 | Desktop     | [ce94a11d8b](https://linux-hardware.org/?probe=ce94a11d8b) | Jun 26, 2020 |
| Huanan        | X99-F8                      | Desktop     | [74f9976527](https://linux-hardware.org/?probe=74f9976527) | Jun 25, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [cbd4390e56](https://linux-hardware.org/?probe=cbd4390e56) | Jun 23, 2020 |
| ASUSTek       | X553SA                      | Notebook    | [de56d8fe26](https://linux-hardware.org/?probe=de56d8fe26) | Jun 23, 2020 |
| ASRock        | Z390 Taichi                 | Desktop     | [6989759d9c](https://linux-hardware.org/?probe=6989759d9c) | Jun 21, 2020 |
| ASRock        | Z390M Pro4                  | Desktop     | [eb53bb80ea](https://linux-hardware.org/?probe=eb53bb80ea) | Jun 20, 2020 |
| ECS           | H81H3-MV                    | Desktop     | [d39e7a605d](https://linux-hardware.org/?probe=d39e7a605d) | Jun 20, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [c05f965fec](https://linux-hardware.org/?probe=c05f965fec) | Jun 17, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [835aa152dd](https://linux-hardware.org/?probe=835aa152dd) | Jun 16, 2020 |
| MSI           | GX60 3CC                    | Notebook    | [41702d8f8c](https://linux-hardware.org/?probe=41702d8f8c) | Jun 14, 2020 |
| MSI           | GX60 3CC                    | Notebook    | [16345ce4e3](https://linux-hardware.org/?probe=16345ce4e3) | Jun 14, 2020 |
| TG            | NXI-A7000 Series            | Notebook    | [20018e6c2a](https://linux-hardware.org/?probe=20018e6c2a) | Jun 07, 2020 |
| Dell          | G3 3579                     | Notebook    | [f21ec2528f](https://linux-hardware.org/?probe=f21ec2528f) | Jun 06, 2020 |
| ECS           | PB02CF                      | Server      | [e4fe65609d](https://linux-hardware.org/?probe=e4fe65609d) | May 28, 2020 |
| ECS           | PB02CF                      | Server      | [277941a55d](https://linux-hardware.org/?probe=277941a55d) | May 27, 2020 |
| Lenovo        | ThinkPad E495 20NES0WU00    | Notebook    | [bd7072c5e9](https://linux-hardware.org/?probe=bd7072c5e9) | May 27, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [229612b5fa](https://linux-hardware.org/?probe=229612b5fa) | May 26, 2020 |
| LG Electro... | 17UD790-PX76K               | Notebook    | [ac4f8e9cc6](https://linux-hardware.org/?probe=ac4f8e9cc6) | May 24, 2020 |
| LG Electro... | 17UD790-PX76K               | Notebook    | [9bb4fea940](https://linux-hardware.org/?probe=9bb4fea940) | May 24, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [65f85ef8e9](https://linux-hardware.org/?probe=65f85ef8e9) | May 20, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b3a561d5db](https://linux-hardware.org/?probe=b3a561d5db) | May 20, 2020 |
| Unknown       | Unknown                     | Desktop     | [e6e0a356a2](https://linux-hardware.org/?probe=e6e0a356a2) | May 19, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [69c9f3bce6](https://linux-hardware.org/?probe=69c9f3bce6) | May 17, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [e526204afd](https://linux-hardware.org/?probe=e526204afd) | May 16, 2020 |
| Samsung       | 570Z5E/580Z5E               | Notebook    | [435579b481](https://linux-hardware.org/?probe=435579b481) | May 16, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [24ce1a41e9](https://linux-hardware.org/?probe=24ce1a41e9) | May 16, 2020 |
| Samsung       | 570Z5E/580Z5E               | Notebook    | [5e2ed0ac77](https://linux-hardware.org/?probe=5e2ed0ac77) | May 16, 2020 |
| LG Electro... | 14ZB990-GP70ML              | Notebook    | [dc05f2344d](https://linux-hardware.org/?probe=dc05f2344d) | May 16, 2020 |
| Lenovo        | ThinkPad 8 20BNA00GKR       | Tablet      | [344a9c1bfa](https://linux-hardware.org/?probe=344a9c1bfa) | May 14, 2020 |
| HP            | 158A                        | Desktop     | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [5919a15425](https://linux-hardware.org/?probe=5919a15425) | May 11, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [d5b8f91a79](https://linux-hardware.org/?probe=d5b8f91a79) | May 10, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [c259824b35](https://linux-hardware.org/?probe=c259824b35) | May 09, 2020 |
| ASRock        | X470 Taichi                 | Desktop     | [261241bb2f](https://linux-hardware.org/?probe=261241bb2f) | May 07, 2020 |
| Biostar       | H61MH                       | Desktop     | [aacc6bcb68](https://linux-hardware.org/?probe=aacc6bcb68) | May 07, 2020 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [36cbf906a0](https://linux-hardware.org/?probe=36cbf906a0) | May 07, 2020 |
| Lenovo        | ThinkPad X220 4290P39       | Notebook    | [1b5c469306](https://linux-hardware.org/?probe=1b5c469306) | May 02, 2020 |
| Gigabyte      | B75M-D3V                    | Desktop     | [a4130d0549](https://linux-hardware.org/?probe=a4130d0549) | Apr 29, 2020 |
| ASRock        | G31M-S                      | Desktop     | [6a55997759](https://linux-hardware.org/?probe=6a55997759) | Apr 28, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [0bbf773840](https://linux-hardware.org/?probe=0bbf773840) | Apr 27, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [5348bea534](https://linux-hardware.org/?probe=5348bea534) | Apr 27, 2020 |
| Lenovo        | ThinkPad X230 2325KZ5       | Notebook    | [150d9801f0](https://linux-hardware.org/?probe=150d9801f0) | Apr 21, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [5d58ef4cec](https://linux-hardware.org/?probe=5d58ef4cec) | Apr 19, 2020 |
| Lenovo        | ThinkPad E495 20NES0WU00    | Notebook    | [fb49bbe9f1](https://linux-hardware.org/?probe=fb49bbe9f1) | Apr 18, 2020 |
| Lenovo        | ThinkPad 8 20BNA00GKR       | Tablet      | [aa72454483](https://linux-hardware.org/?probe=aa72454483) | Apr 16, 2020 |
| Dell          | Latitude D630               | Notebook    | [0540c0a191](https://linux-hardware.org/?probe=0540c0a191) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [a78c0430fb](https://linux-hardware.org/?probe=a78c0430fb) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [6e7470b8c3](https://linux-hardware.org/?probe=6e7470b8c3) | Apr 15, 2020 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [4d5a5a3a34](https://linux-hardware.org/?probe=4d5a5a3a34) | Apr 14, 2020 |
| MSI           | B250M PRO-VD                | Desktop     | [d797379451](https://linux-hardware.org/?probe=d797379451) | Apr 13, 2020 |
| LG Electro... | 15U340-LT1FK                | Tablet      | [b78bd157c9](https://linux-hardware.org/?probe=b78bd157c9) | Apr 12, 2020 |
| LG Electro... | 15U340-LT1FK                | Tablet      | [29cad9bafb](https://linux-hardware.org/?probe=29cad9bafb) | Apr 12, 2020 |
| Gigabyte      | TRX40 AORUS XTREME          | Desktop     | [0f078bd16f](https://linux-hardware.org/?probe=0f078bd16f) | Apr 11, 2020 |
| Dell          | 0Y2MRG A01                  | Desktop     | [053b33bcbc](https://linux-hardware.org/?probe=053b33bcbc) | Apr 05, 2020 |
| ASUSTek       | P5K                         | Desktop     | [8ec1f94a9f](https://linux-hardware.org/?probe=8ec1f94a9f) | Apr 05, 2020 |
| ASUSTek       | H110M-F                     | Desktop     | [c5861fb518](https://linux-hardware.org/?probe=c5861fb518) | Mar 31, 2020 |
| LG Electro... | R490-KR6WK                  | Notebook    | [b0c23e23f7](https://linux-hardware.org/?probe=b0c23e23f7) | Mar 21, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b3782f0e54](https://linux-hardware.org/?probe=b3782f0e54) | Mar 20, 2020 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [c54c1dcc2f](https://linux-hardware.org/?probe=c54c1dcc2f) | Mar 18, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [de7d898371](https://linux-hardware.org/?probe=de7d898371) | Mar 16, 2020 |
| Hanis         | Rugged86H                   | Tablet      | [f85527148f](https://linux-hardware.org/?probe=f85527148f) | Mar 16, 2020 |
| Hanis         | Rugged86H                   | Tablet      | [9526ed2d93](https://linux-hardware.org/?probe=9526ed2d93) | Mar 16, 2020 |
| ECS           | PB02CF                      | Server      | [68979eba8f](https://linux-hardware.org/?probe=68979eba8f) | Mar 15, 2020 |
| ECS           | PB02CF                      | Server      | [351516c86f](https://linux-hardware.org/?probe=351516c86f) | Mar 14, 2020 |
| ECS           | PB02CF                      | Server      | [fc1afc7ed7](https://linux-hardware.org/?probe=fc1afc7ed7) | Mar 12, 2020 |
| HP            | Pavilion dv7                | Notebook    | [61bbb3da8a](https://linux-hardware.org/?probe=61bbb3da8a) | Mar 12, 2020 |
| ECS           | PB02CF                      | Server      | [9d62420812](https://linux-hardware.org/?probe=9d62420812) | Mar 09, 2020 |
| ASRock        | FM2A88M-HD+ R3.0            | Desktop     | [b5def2acfb](https://linux-hardware.org/?probe=b5def2acfb) | Mar 03, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [ca363a8ddc](https://linux-hardware.org/?probe=ca363a8ddc) | Mar 03, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [2b56d27ead](https://linux-hardware.org/?probe=2b56d27ead) | Mar 02, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [8b42886c6f](https://linux-hardware.org/?probe=8b42886c6f) | Mar 02, 2020 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [fd4e08618e](https://linux-hardware.org/?probe=fd4e08618e) | Feb 28, 2020 |
| ECS           | PB02CF                      | Server      | [8553d515a9](https://linux-hardware.org/?probe=8553d515a9) | Feb 27, 2020 |
| LG Electro... | A505-K.AFC4L                | Notebook    | [33b72b423b](https://linux-hardware.org/?probe=33b72b423b) | Feb 26, 2020 |
| ECS           | PB02CF                      | Server      | [7b029b9193](https://linux-hardware.org/?probe=7b029b9193) | Feb 25, 2020 |
| ECS           | PB02CF                      | Server      | [82e1b966c4](https://linux-hardware.org/?probe=82e1b966c4) | Feb 25, 2020 |
| ECS           | PB02CF                      | Server      | [c81fd255b8](https://linux-hardware.org/?probe=c81fd255b8) | Feb 25, 2020 |
| ECS           | PB02CF                      | Server      | [855276d27c](https://linux-hardware.org/?probe=855276d27c) | Feb 22, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [8212e2eb65](https://linux-hardware.org/?probe=8212e2eb65) | Feb 13, 2020 |
| MSI           | Prestige 14 A10SC           | Notebook    | [00af81dd32](https://linux-hardware.org/?probe=00af81dd32) | Feb 12, 2020 |
| MSI           | Prestige 14 A10SC           | Notebook    | [dac2e1709e](https://linux-hardware.org/?probe=dac2e1709e) | Feb 12, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| LattePanda    | Alpha                       | Desktop     | [eb27db2005](https://linux-hardware.org/?probe=eb27db2005) | Feb 01, 2020 |
| LattePanda    | Alpha                       | Desktop     | [72a1cd44a0](https://linux-hardware.org/?probe=72a1cd44a0) | Feb 01, 2020 |
| MSI           | GF63 Thin 9SC               | Notebook    | [47b9bc192c](https://linux-hardware.org/?probe=47b9bc192c) | Jan 29, 2020 |
| Nvidia        | Tegra                       | Soc         | [7d929b52dc](https://linux-hardware.org/?probe=7d929b52dc) | Jan 29, 2020 |
| MSI           | GF63 Thin 9SC               | Notebook    | [21dbcd5aca](https://linux-hardware.org/?probe=21dbcd5aca) | Jan 28, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [6515ce1c97](https://linux-hardware.org/?probe=6515ce1c97) | Jan 23, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [3f4a3ca42f](https://linux-hardware.org/?probe=3f4a3ca42f) | Jan 19, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek       | P5B-PLUS Series             | Desktop     | [b0a90d8478](https://linux-hardware.org/?probe=b0a90d8478) | Jan 02, 2020 |
| HP            | ProBook 453                 | Notebook    | [ad3d1ff0fc](https://linux-hardware.org/?probe=ad3d1ff0fc) | Dec 27, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2fb35125e3](https://linux-hardware.org/?probe=2fb35125e3) | Dec 22, 2019 |
| Lenovo        | ThinkPad E565 20EYA007KD    | Notebook    | [c1c9dd614a](https://linux-hardware.org/?probe=c1c9dd614a) | Dec 17, 2019 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [61765ee913](https://linux-hardware.org/?probe=61765ee913) | Dec 11, 2019 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [fa008b24fc](https://linux-hardware.org/?probe=fa008b24fc) | Dec 11, 2019 |
| Gigabyte      | 945GM-S2                    | Desktop     | [c6b23ec021](https://linux-hardware.org/?probe=c6b23ec021) | Dec 07, 2019 |
| HP            | Pavilion 15                 | Notebook    | [5f9b510e87](https://linux-hardware.org/?probe=5f9b510e87) | Oct 28, 2019 |
| ECS           | H81H3-M4                    | Desktop     | [2a11653db0](https://linux-hardware.org/?probe=2a11653db0) | Oct 05, 2019 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [37c348afcc](https://linux-hardware.org/?probe=37c348afcc) | Sep 11, 2019 |
| MSI           | MS-1675                     | Notebook    | [c5bf6f209a](https://linux-hardware.org/?probe=c5bf6f209a) | Sep 07, 2019 |
| MSI           | MS-1675                     | Notebook    | [be1db420ea](https://linux-hardware.org/?probe=be1db420ea) | Sep 07, 2019 |
| Hanis         | RuggedPadY16                | Tablet      | [70f839c5cb](https://linux-hardware.org/?probe=70f839c5cb) | Sep 04, 2019 |
| AMI           | Cherry Trail CR             | Notebook    | [caaebe3071](https://linux-hardware.org/?probe=caaebe3071) | Sep 01, 2019 |
| AMI           | Cherry Trail CR             | Notebook    | [5637a7d5ca](https://linux-hardware.org/?probe=5637a7d5ca) | Sep 01, 2019 |
| ASUSTek       | T101HA                      | Tablet      | [b08e9c4371](https://linux-hardware.org/?probe=b08e9c4371) | Aug 31, 2019 |
| Lenovo        | U41-70 80JV                 | Notebook    | [0af65c15a0](https://linux-hardware.org/?probe=0af65c15a0) | Aug 30, 2019 |
| ECS           | G41T-M6                     | Desktop     | [91cafa3b5b](https://linux-hardware.org/?probe=91cafa3b5b) | Aug 30, 2019 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [68069aeff1](https://linux-hardware.org/?probe=68069aeff1) | Aug 21, 2019 |
| IMUZ          | StormBook 15                | Notebook    | [daf3b9ea48](https://linux-hardware.org/?probe=daf3b9ea48) | Aug 07, 2019 |
| Supermicro    | X11DPG-OT-CPU               | Server      | [8e73f804f5](https://linux-hardware.org/?probe=8e73f804f5) | Jul 16, 2019 |
| ASRock        | Z390 Extreme4               | Desktop     | [8c8af8b557](https://linux-hardware.org/?probe=8c8af8b557) | Jul 13, 2019 |
| ASRock        | AB350M Pro4                 | Desktop     | [88354e515f](https://linux-hardware.org/?probe=88354e515f) | Jul 08, 2019 |
| ASRock        | AB350M Pro4                 | Desktop     | [7506cb2993](https://linux-hardware.org/?probe=7506cb2993) | Jul 08, 2019 |
| Gigabyte      | GA-MA790FX-DS5              | Desktop     | [727b2b7099](https://linux-hardware.org/?probe=727b2b7099) | Jun 27, 2019 |
| AMD           | R690A-M2T                   | Desktop     | [da36474b90](https://linux-hardware.org/?probe=da36474b90) | Jun 18, 2019 |
| Gigabyte      | AB350M-DS2-CF               | Desktop     | [553908ddb3](https://linux-hardware.org/?probe=553908ddb3) | Jun 09, 2019 |
| ASUSTek       | PRIME X399-A                | Desktop     | [ae94045380](https://linux-hardware.org/?probe=ae94045380) | May 29, 2019 |
| Lenovo        | NO DPK                      | Desktop     | [b89b8c9364](https://linux-hardware.org/?probe=b89b8c9364) | May 27, 2019 |
| Samsung       | 800G5M/800G5W               | Notebook    | [01cb2e9401](https://linux-hardware.org/?probe=01cb2e9401) | May 22, 2019 |
| HP            | Laptop 15-db1xxx            | Notebook    | [e318a9dac5](https://linux-hardware.org/?probe=e318a9dac5) | May 10, 2019 |
| ASRock        | H61M-DGS                    | Desktop     | [6dc8ccd0f6](https://linux-hardware.org/?probe=6dc8ccd0f6) | May 08, 2019 |
| Sony          | VPCEA36FK                   | Notebook    | [6c4b2a047b](https://linux-hardware.org/?probe=6c4b2a047b) | May 01, 2019 |
| Foxconn       | P35A01                      | Desktop     | [f2685edfa8](https://linux-hardware.org/?probe=f2685edfa8) | Apr 21, 2019 |
| Dell          | Inspiron 7559               | Notebook    | [fb5730a29c](https://linux-hardware.org/?probe=fb5730a29c) | Apr 17, 2019 |
| Apple         | MacBookPro14,1              | Notebook    | [606c70c0db](https://linux-hardware.org/?probe=606c70c0db) | Apr 15, 2019 |
| Dell          | Inspiron 7570               | Notebook    | [f46c9c93f9](https://linux-hardware.org/?probe=f46c9c93f9) | Apr 12, 2019 |
| Dell          | Inspiron 7570               | Notebook    | [e1c522656b](https://linux-hardware.org/?probe=e1c522656b) | Apr 12, 2019 |
| ASUSTek       | Z170-A                      | Desktop     | [322d76fe62](https://linux-hardware.org/?probe=322d76fe62) | Apr 04, 2019 |
| ASUSTek       | Z170-A                      | Desktop     | [0fa2f9b10a](https://linux-hardware.org/?probe=0fa2f9b10a) | Apr 04, 2019 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [8e21d7bf0c](https://linux-hardware.org/?probe=8e21d7bf0c) | Mar 30, 2019 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [45f363040f](https://linux-hardware.org/?probe=45f363040f) | Mar 30, 2019 |
| Lenovo        | ThinkPad P52s 20LBCTO1WW    | Notebook    | [ed9f709e73](https://linux-hardware.org/?probe=ed9f709e73) | Feb 20, 2019 |
| HP            | ProLiant DL380 Gen9         | Server      | [c9d389b2a3](https://linux-hardware.org/?probe=c9d389b2a3) | Jan 26, 2019 |
| ASRock        | P55 Pro                     | Desktop     | [041e899a1b](https://linux-hardware.org/?probe=041e899a1b) | Jan 15, 2019 |
| Gigabyte      | H55M-S2V                    | Desktop     | [36d1703d67](https://linux-hardware.org/?probe=36d1703d67) | Dec 23, 2018 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [4a0abda7de](https://linux-hardware.org/?probe=4a0abda7de) | Dec 14, 2018 |
| LattePanda    | Alpha                       | Desktop     | [287f0d8110](https://linux-hardware.org/?probe=287f0d8110) | Nov 27, 2018 |
| LattePanda    | Alpha                       | Desktop     | [37c9db1d31](https://linux-hardware.org/?probe=37c9db1d31) | Nov 27, 2018 |
| AVERATEC      | 6600                        | Notebook    | [a55a983b35](https://linux-hardware.org/?probe=a55a983b35) | Nov 11, 2018 |
| AVERATEC      | 6600                        | Notebook    | [8ca54d992c](https://linux-hardware.org/?probe=8ca54d992c) | Nov 11, 2018 |
| Dell          | XPS 15 9560                 | Notebook    | [d5d9e2cef1](https://linux-hardware.org/?probe=d5d9e2cef1) | Nov 04, 2018 |
| LG Electro... | R510                        | Notebook    | [f7b3f1d4a5](https://linux-hardware.org/?probe=f7b3f1d4a5) | Oct 13, 2018 |
| Gigabyte      | P55-US3L                    | Desktop     | [e216d60f26](https://linux-hardware.org/?probe=e216d60f26) | Sep 19, 2018 |
| Gigabyte      | B75M-D3H                    | Desktop     | [08f9437e06](https://linux-hardware.org/?probe=08f9437e06) | Jul 10, 2018 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [16f456428f](https://linux-hardware.org/?probe=16f456428f) | May 10, 2018 |
| ECS           | A55F2-M3                    | Desktop     | [e4af897158](https://linux-hardware.org/?probe=e4af897158) | May 10, 2018 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [f3036847e4](https://linux-hardware.org/?probe=f3036847e4) | May 10, 2018 |
| ECS           | A55F2-M3                    | Desktop     | [eb58cea516](https://linux-hardware.org/?probe=eb58cea516) | May 10, 2018 |
| ASRock        | G41M-VS3                    | Desktop     | [18d59d7ea8](https://linux-hardware.org/?probe=18d59d7ea8) | Apr 13, 2018 |
| ASUSTek       | N56JR                       | Notebook    | [27253306bc](https://linux-hardware.org/?probe=27253306bc) | Dec 28, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/South_Korea/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 116       | 17.19%  |
| Ubuntu 22.04                 | 71        | 10.52%  |
| Ubuntu 18.04                 | 49        | 7.26%   |
| Arch Rolling                 | 20        | 2.96%   |
| HamoniKR 7.0                 | 15        | 2.22%   |
| Debian 12                    | 14        | 2.07%   |
| Arch                         | 11        | 1.63%   |
| Gooroom                      | 10        | 1.48%   |
| Debian 11                    | 10        | 1.48%   |
| Ubuntu 21.10                 | 9         | 1.33%   |
| Ubuntu 19.10                 | 9         | 1.33%   |
| Fedora 40                    | 9         | 1.33%   |
| Fedora 39                    | 9         | 1.33%   |
| Ubuntu 24.04                 | 8         | 1.19%   |
| Ubuntu 20.10                 | 8         | 1.19%   |
| Ubuntu 23.10                 | 7         | 1.04%   |
| Fedora 38                    | 7         | 1.04%   |
| Fedora 37                    | 7         | 1.04%   |
| Fedora 32                    | 7         | 1.04%   |
| Zorin 16                     | 6         | 0.89%   |
| Ubuntu 19.04                 | 6         | 0.89%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 0.89%   |
| Linux Mint 20.1              | 6         | 0.89%   |
| Fedora 36                    | 6         | 0.89%   |
| ArcoLinux Rolling            | 6         | 0.89%   |
| Pop!_OS 22.04                | 5         | 0.74%   |
| HamoniKR 4.0                 | 5         | 0.74%   |
| Fedora 34                    | 5         | 0.74%   |
| Debian 10                    | 5         | 0.74%   |
| Zorin 15                     | 4         | 0.59%   |
| Ubuntu 16.04                 | 4         | 0.59%   |
| OpenMandriva 4.2             | 4         | 0.59%   |
| OpenMandriva 23.03           | 4         | 0.59%   |
| OpenMandriva 23.01           | 4         | 0.59%   |
| Linux Mint 21.1              | 4         | 0.59%   |
| Linux Mint 20.3              | 4         | 0.59%   |
| Linux Mint 20                | 4         | 0.59%   |
| CentOS 8                     | 4         | 0.59%   |
| CentOS 7                     | 4         | 0.59%   |
| Zorin 17                     | 3         | 0.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 288       | 44.44%  |
| Fedora           | 52        | 8.02%   |
| Debian           | 31        | 4.78%   |
| Arch             | 29        | 4.48%   |
| Linux Mint       | 27        | 4.17%   |
| HamoniKR         | 27        | 4.17%   |
| OpenMandriva     | 20        | 3.09%   |
| Zorin            | 13        | 2.01%   |
| Manjaro          | 13        | 2.01%   |
| Gooroom          | 11        | 1.7%    |
| No1 Linux        | 10        | 1.54%   |
| Kubuntu          | 10        | 1.54%   |
| CentOS           | 10        | 1.54%   |
| SteamOS          | 9         | 1.39%   |
| Pop!_OS          | 9         | 1.39%   |
| ROSA             | 8         | 1.23%   |
| Endless          | 8         | 1.23%   |
| openSUSE         | 7         | 1.08%   |
| KDE neon         | 6         | 0.93%   |
| ArcoLinux        | 6         | 0.93%   |
| Ubuntu Unity     | 5         | 0.77%   |
| Xubuntu          | 4         | 0.62%   |
| Rocky Linux      | 4         | 0.62%   |
| RHEL             | 4         | 0.62%   |
| EndeavourOS      | 4         | 0.62%   |
| LMDE             | 3         | 0.46%   |
| Kali             | 3         | 0.46%   |
| Ubuntu MATE      | 2         | 0.31%   |
| TmaxOS           | 2         | 0.31%   |
| Lubuntu          | 2         | 0.31%   |
| Gentoo           | 2         | 0.31%   |
| Elementary       | 2         | 0.31%   |
| Chrome OS        | 2         | 0.31%   |
| ChimeraOS        | 2         | 0.31%   |
| AlmaLinux        | 2         | 0.31%   |
| Xero             | 1         | 0.15%   |
| Ubuntu Budgie    | 1         | 0.15%   |
| Trisquel         | 1         | 0.15%   |
| org.kde.Platform | 1         | 0.15%   |
| Nobara           | 1         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.3.0-40-generic            | 8         | 1.1%    |
| 5.4.0-42-generic            | 7         | 0.96%   |
| 5.15.0-58-generic           | 7         | 0.96%   |
| 5.15.0-53-generic           | 7         | 0.96%   |
| 5.4.0-29-generic            | 6         | 0.83%   |
| 5.4.0-26-generic            | 6         | 0.83%   |
| 5.4.0-58-generic            | 5         | 0.69%   |
| 5.4.0-56-generic            | 5         | 0.69%   |
| 5.19.0-45-generic           | 5         | 0.69%   |
| 5.15.0-56-generic           | 5         | 0.69%   |
| 5.10.0-19-amd64             | 5         | 0.69%   |
| 6.8.0-48-generic            | 4         | 0.55%   |
| 6.2.6-desktop-1omv2390      | 4         | 0.55%   |
| 6.1.1-desktop-1omv2290      | 4         | 0.55%   |
| 5.19.0-46-generic           | 4         | 0.55%   |
| 5.19.0-41-generic           | 4         | 0.55%   |
| 5.19.0-38-generic           | 4         | 0.55%   |
| 5.19.0-35-generic           | 4         | 0.55%   |
| 5.15.0-89-generic           | 4         | 0.55%   |
| 5.15.0-88-generic           | 4         | 0.55%   |
| 5.15.0-52-generic           | 4         | 0.55%   |
| 5.15.0-43-generic           | 4         | 0.55%   |
| 5.15.0-41-generic           | 4         | 0.55%   |
| 5.15.0-122-generic          | 4         | 0.55%   |
| 5.10.0-17-amd64             | 4         | 0.55%   |
| 5.0.0-25-generic            | 4         | 0.55%   |
| 4.19.0-9-amd64              | 4         | 0.55%   |
| 6.8.0-49-generic            | 3         | 0.41%   |
| 6.8.0-40-generic            | 3         | 0.41%   |
| 6.8.0-31-generic            | 3         | 0.41%   |
| 6.5.6-300.fc39.x86_64       | 3         | 0.41%   |
| 6.5.0-35-generic            | 3         | 0.41%   |
| 6.5.0-14-generic            | 3         | 0.41%   |
| 6.1.52-valve16-1-neptune-61 | 3         | 0.41%   |
| 6.1.0-21-amd64              | 3         | 0.41%   |
| 5.8.0-59-generic            | 3         | 0.41%   |
| 5.8.0-50-generic            | 3         | 0.41%   |
| 5.8.0-43-generic            | 3         | 0.41%   |
| 5.8.0-38-generic            | 3         | 0.41%   |
| 5.4.0-91-generic            | 3         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 98        | 14.06%  |
| 5.15.0  | 88        | 12.63%  |
| 5.8.0   | 31        | 4.45%   |
| 4.15.0  | 28        | 4.02%   |
| 5.19.0  | 27        | 3.87%   |
| 5.13.0  | 24        | 3.44%   |
| 5.3.0   | 23        | 3.3%    |
| 6.8.0   | 18        | 2.58%   |
| 4.18.0  | 18        | 2.58%   |
| 6.5.0   | 17        | 2.44%   |
| 5.10.0  | 16        | 2.3%    |
| 6.1.0   | 15        | 2.15%   |
| 5.11.0  | 13        | 1.87%   |
| 5.0.0   | 12        | 1.72%   |
| 5.14.0  | 11        | 1.58%   |
| 4.19.0  | 11        | 1.58%   |
| 6.2.0   | 10        | 1.43%   |
| 5.16.19 | 5         | 0.72%   |
| 6.5.6   | 4         | 0.57%   |
| 6.2.6   | 4         | 0.57%   |
| 6.1.1   | 4         | 0.57%   |
| 6.7.4   | 3         | 0.43%   |
| 6.2.8   | 3         | 0.43%   |
| 6.10.9  | 3         | 0.43%   |
| 6.1.52  | 3         | 0.43%   |
| 6.1.11  | 3         | 0.43%   |
| 6.0.0   | 3         | 0.43%   |
| 5.19.15 | 3         | 0.43%   |
| 5.18.5  | 3         | 0.43%   |
| 5.16.7  | 3         | 0.43%   |
| 5.10.14 | 3         | 0.43%   |
| 4.9.60  | 3         | 0.43%   |
| 3.10.0  | 3         | 0.43%   |
| 6.9.5   | 2         | 0.29%   |
| 6.9.12  | 2         | 0.29%   |
| 6.8.9   | 2         | 0.29%   |
| 6.6.9   | 2         | 0.29%   |
| 6.6.60  | 2         | 0.29%   |
| 6.6.2   | 2         | 0.29%   |
| 6.5.9   | 2         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 104       | 15.07%  |
| 5.15    | 99        | 14.35%  |
| 5.8     | 40        | 5.8%    |
| 6.1     | 36        | 5.22%   |
| 5.19    | 34        | 4.93%   |
| 4.15    | 30        | 4.35%   |
| 6.5     | 27        | 3.91%   |
| 5.10    | 26        | 3.77%   |
| 5.13    | 25        | 3.62%   |
| 6.2     | 24        | 3.48%   |
| 5.3     | 24        | 3.48%   |
| 6.8     | 23        | 3.33%   |
| 5.11    | 20        | 2.9%    |
| 4.18    | 20        | 2.9%    |
| 5.14    | 17        | 2.46%   |
| 6.0     | 14        | 2.03%   |
| 6.6     | 13        | 1.88%   |
| 5.0     | 13        | 1.88%   |
| 4.19    | 13        | 1.88%   |
| 5.16    | 11        | 1.59%   |
| 6.9     | 7         | 1.01%   |
| 6.7     | 7         | 1.01%   |
| 6.10    | 7         | 1.01%   |
| 5.18    | 7         | 1.01%   |
| 5.12    | 6         | 0.87%   |
| 4.9     | 6         | 0.87%   |
| 6.4     | 5         | 0.72%   |
| 6.11    | 5         | 0.72%   |
| 5.6     | 4         | 0.58%   |
| 6.3     | 3         | 0.43%   |
| 6.12    | 3         | 0.43%   |
| 3.10    | 3         | 0.43%   |
| 5.9     | 2         | 0.29%   |
| 5.7     | 2         | 0.29%   |
| 4.13    | 2         | 0.29%   |
| 2.6     | 2         | 0.29%   |
| 5.5     | 1         | 0.14%   |
| 5.2     | 1         | 0.14%   |
| 5.17    | 1         | 0.14%   |
| 4.4     | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 618       | 97.32%  |
| aarch64 | 11        | 1.73%   |
| i686    | 5         | 0.79%   |
| armv7l  | 1         | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 346       | 53.15%  |
| KDE5             | 85        | 13.06%  |
| Unknown          | 74        | 11.37%  |
| X-Cinnamon       | 45        | 6.91%   |
| XFCE             | 21        | 3.23%   |
| GNOME Flashback  | 11        | 1.69%   |
| LXDE             | 10        | 1.54%   |
| Cinnamon         | 9         | 1.38%   |
| KDE6             | 7         | 1.08%   |
| i3               | 7         | 1.08%   |
| Unity            | 6         | 0.92%   |
| MATE             | 5         | 0.77%   |
| KDE              | 5         | 0.77%   |
| KDE4             | 4         | 0.61%   |
| TOS:GNOME        | 2         | 0.31%   |
| Pantheon         | 2         | 0.31%   |
| LXQt             | 2         | 0.31%   |
| Hyprland         | 2         | 0.31%   |
| wayfire          | 1         | 0.15%   |
| sway             | 1         | 0.15%   |
| Openbox          | 1         | 0.15%   |
| lightdm-xsession | 1         | 0.15%   |
| GNOME Classic    | 1         | 0.15%   |
| Enlightenment    | 1         | 0.15%   |
| Deepin           | 1         | 0.15%   |
| Budgie           | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 411       | 63.33%  |
| Wayland | 157       | 24.19%  |
| Unknown | 50        | 7.7%    |
| Tty     | 31        | 4.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 292       | 44.79%  |
| GDM3    | 109       | 16.72%  |
| GDM     | 99        | 15.18%  |
| SDDM    | 71        | 10.89%  |
| LightDM | 60        | 9.2%    |
| TDM     | 16        | 2.45%   |
| KDM     | 3         | 0.46%   |
| XDM     | 1         | 0.15%   |
| SLiM    | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| ko_KR       | 289       | 44.6%   |
| en_US       | 246       | 37.96%  |
| Unknown     | 65        | 10.03%  |
| C           | 16        | 2.47%   |
| zh_CN       | 5         | 0.77%   |
| en_CA       | 5         | 0.77%   |
| en_GB       | 4         | 0.62%   |
| id_ID       | 3         | 0.46%   |
| fr_FR       | 3         | 0.46%   |
| pt_BR       | 2         | 0.31%   |
| vi_VN       | 1         | 0.15%   |
| ru_UA       | 1         | 0.15%   |
| ru_RU       | 1         | 0.15%   |
| ko_KR.euckr | 1         | 0.15%   |
| en_NZ       | 1         | 0.15%   |
| en_AU       | 1         | 0.15%   |
| el_GR       | 1         | 0.15%   |
| de_DE       | 1         | 0.15%   |
| ba_RU       | 1         | 0.15%   |
| ar_EG       | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 407       | 63.3%   |
| BIOS | 236       | 36.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 482       | 74.27%  |
| Btrfs   | 76        | 11.71%  |
| Xfs     | 24        | 3.7%    |
| Tmpfs   | 24        | 3.7%    |
| Unknown | 17        | 2.62%   |
| Overlay | 15        | 2.31%   |
| Zfs     | 8         | 1.23%   |
| Rootfs  | 2         | 0.31%   |
| F2fs    | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 329       | 51.01%  |
| Unknown | 273       | 42.33%  |
| MBR     | 43        | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 569       | 88.77%  |
| Yes       | 72        | 11.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 443       | 68.79%  |
| Yes       | 201       | 31.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 97        | 15.28%  |
| ASUSTek Computer        | 95        | 14.96%  |
| Samsung Electronics     | 60        | 9.45%   |
| Gigabyte Technology     | 55        | 8.66%   |
| Hewlett-Packard         | 49        | 7.72%   |
| ASRock                  | 40        | 6.3%    |
| MSI                     | 39        | 6.14%   |
| LG Electronics          | 31        | 4.88%   |
| Dell                    | 31        | 4.88%   |
| Apple                   | 14        | 2.2%    |
| Unknown                 | 12        | 1.89%   |
| ECS                     | 10        | 1.57%   |
| Valve                   | 7         | 1.1%    |
| Acer                    | 6         | 0.94%   |
| Intel                   | 5         | 0.79%   |
| HANSUNG COMPUTER        | 5         | 0.79%   |
| Raspberry Pi Foundation | 4         | 0.63%   |
| Notebook                | 4         | 0.63%   |
| Nvidia                  | 3         | 0.47%   |
| Google                  | 3         | 0.47%   |
| Foxconn                 | 3         | 0.47%   |
| Toshiba                 | 2         | 0.31%   |
| Supermicro              | 2         | 0.31%   |
| Razer                   | 2         | 0.31%   |
| Quanta                  | 2         | 0.31%   |
| Microsoft               | 2         | 0.31%   |
| LattePanda              | 2         | 0.31%   |
| IMUZ                    | 2         | 0.31%   |
| Huanan                  | 2         | 0.31%   |
| HPE                     | 2         | 0.31%   |
| Hanis                   | 2         | 0.31%   |
| Chuwi                   | 2         | 0.31%   |
| Alienware               | 2         | 0.31%   |
| WTM                     | 1         | 0.16%   |
| Wolfnfox                | 1         | 0.16%   |
| WEIPAI                  | 1         | 0.16%   |
| WB                      | 1         | 0.16%   |
| TMAX                    | 1         | 0.16%   |
| TG                      | 1         | 0.16%   |
| Teclast                 | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 13        | 2.05%   |
| Valve Jupiter                           | 6         | 0.94%   |
| Samsung 950XCJ/951XCJ/950XCR            | 6         | 0.94%   |
| Samsung DeskTop System                  | 5         | 0.79%   |
| MSI MS-7B89                             | 4         | 0.63%   |
| Samsung 950XED                          | 3         | 0.47%   |
| Samsung 940XFG                          | 3         | 0.47%   |
| Samsung 760XDA                          | 3         | 0.47%   |
| Gigabyte B75M-D3H                       | 3         | 0.47%   |
| ECS LIVA Q2                             | 3         | 0.47%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4    | 3         | 0.47%   |
| ASUS PRIME B350M-A                      | 3         | 0.47%   |
| ASUS PRIME A320M-K                      | 3         | 0.47%   |
| ASUS All Series                         | 3         | 0.47%   |
| Razer Blade 17 (2022) - RZ09-0423       | 2         | 0.31%   |
| Quanta QSSC-98J_C2                      | 2         | 0.31%   |
| Nvidia Tegra                            | 2         | 0.31%   |
| Notebook N650DU                         | 2         | 0.31%   |
| MSI MS-7D91                             | 2         | 0.31%   |
| MSI MS-7D42                             | 2         | 0.31%   |
| MSI MS-7C94                             | 2         | 0.31%   |
| Lenovo Yoga 6 13ARE05 82FN              | 2         | 0.31%   |
| Lenovo ThinkPad L14 Gen 1 20U5S01S00    | 2         | 0.31%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2       | 2         | 0.31%   |
| Lenovo IdeaPad 5 14ALC05 82LM           | 2         | 0.31%   |
| Lenovo IdeaPad 3 15IIL05 81WE           | 2         | 0.31%   |
| Lenovo IdeaPad 3 14ALC6 82KT            | 2         | 0.31%   |
| LattePanda Alpha                        | 2         | 0.31%   |
| HPE ProLiant DL380 Gen10                | 2         | 0.31%   |
| HP Stream Notebook PC 13                | 2         | 0.31%   |
| HP Pavilion g6                          | 2         | 0.31%   |
| HP Pavilion dv6                         | 2         | 0.31%   |
| HP Laptop 15-db1xxx                     | 2         | 0.31%   |
| HP EliteBook 865 16 inch G9 Notebook PC | 2         | 0.31%   |
| HP EliteBook 855 G7 Notebook PC         | 2         | 0.31%   |
| HANSUNG COMPUTER TFX5470H               | 2         | 0.31%   |
| Gigabyte TRX40 AORUS XTREME             | 2         | 0.31%   |
| Gigabyte H81M-DS2V                      | 2         | 0.31%   |
| Gigabyte B75M-D3V                       | 2         | 0.31%   |
| Gigabyte B360M-D3H                      | 2         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 47        | 7.4%    |
| Lenovo IdeaPad      | 20        | 3.15%   |
| ASUS ROG            | 17        | 2.68%   |
| ASUS PRIME          | 16        | 2.52%   |
| HP Pavilion         | 13        | 2.05%   |
| Unknown             | 13        | 2.05%   |
| ASUS VivoBook       | 12        | 1.89%   |
| Dell Inspiron       | 11        | 1.73%   |
| HP Laptop           | 7         | 1.1%    |
| HP EliteBook        | 7         | 1.1%    |
| Dell XPS            | 7         | 1.1%    |
| Valve Jupiter       | 6         | 0.94%   |
| Samsung 950XCJ      | 6         | 0.94%   |
| ASUS Zenbook        | 6         | 0.94%   |
| Samsung DeskTop     | 5         | 0.79%   |
| RPi Raspberry       | 4         | 0.63%   |
| MSI MS-7B89         | 4         | 0.63%   |
| Lenovo ThinkStation | 4         | 0.63%   |
| Lenovo ThinkBook    | 4         | 0.63%   |
| HP Stream           | 4         | 0.63%   |
| ASUS TUF            | 4         | 0.63%   |
| Samsung 950XED      | 3         | 0.47%   |
| Samsung 940XFG      | 3         | 0.47%   |
| Samsung 760XDA      | 3         | 0.47%   |
| Lenovo Yoga         | 3         | 0.47%   |
| Lenovo ThinkCentre  | 3         | 0.47%   |
| HP Elite            | 3         | 0.47%   |
| Gigabyte TRX40      | 3         | 0.47%   |
| Gigabyte B75M-D3H   | 3         | 0.47%   |
| ECS LIVA            | 3         | 0.47%   |
| Dell Vostro         | 3         | 0.47%   |
| Dell PowerEdge      | 3         | 0.47%   |
| Dell Latitude       | 3         | 0.47%   |
| ASUS All            | 3         | 0.47%   |
| Apple MacBookPro11  | 3         | 0.47%   |
| Acer Swift          | 3         | 0.47%   |
| Toshiba Satellite   | 2         | 0.31%   |
| Samsung Galaxy      | 2         | 0.31%   |
| Razer Blade         | 2         | 0.31%   |
| Quanta QSSC-98J     | 2         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 80        | 12.6%   |
| 2021    | 72        | 11.34%  |
| 2022    | 63        | 9.92%   |
| 2018    | 55        | 8.66%   |
| 2019    | 52        | 8.19%   |
| 2017    | 43        | 6.77%   |
| 2014    | 35        | 5.51%   |
| 2023    | 32        | 5.04%   |
| 2013    | 32        | 5.04%   |
| 2012    | 30        | 4.72%   |
| 2016    | 26        | 4.09%   |
| 2015    | 21        | 3.31%   |
| 2011    | 20        | 3.15%   |
| 2008    | 17        | 2.68%   |
| 2010    | 15        | 2.36%   |
| 2009    | 14        | 2.2%    |
| 2007    | 9         | 1.42%   |
| Unknown | 8         | 1.26%   |
| 2024    | 6         | 0.94%   |
| 2006    | 4         | 0.63%   |
| 2005    | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 324       | 51.02%  |
| Desktop        | 231       | 36.38%  |
| Convertible    | 21        | 3.31%   |
| Tablet         | 18        | 2.83%   |
| Server         | 17        | 2.68%   |
| System on chip | 11        | 1.73%   |
| Mini pc        | 10        | 1.57%   |
| All in one     | 3         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 594       | 93.1%   |
| Enabled  | 44        | 6.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 632       | 99.53%  |
| Yes  | 3         | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 133       | 20.72%  |
| 8.01-16.0       | 126       | 19.63%  |
| 16.01-24.0      | 117       | 18.22%  |
| 32.01-64.0      | 78        | 12.15%  |
| 3.01-4.0        | 78        | 12.15%  |
| 64.01-256.0     | 58        | 9.03%   |
| 1.01-2.0        | 24        | 3.74%   |
| 24.01-32.0      | 19        | 2.96%   |
| More than 256.0 | 4         | 0.62%   |
| 2.01-3.0        | 3         | 0.47%   |
| 0.51-1.0        | 1         | 0.16%   |
| 0.01-0.5        | 1         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 182       | 26.53%  |
| 2.01-3.0   | 162       | 23.62%  |
| 4.01-8.0   | 127       | 18.51%  |
| 3.01-4.0   | 122       | 17.78%  |
| 8.01-16.0  | 35        | 5.1%    |
| 0.51-1.0   | 34        | 4.96%   |
| 16.01-24.0 | 9         | 1.31%   |
| 0.01-0.5   | 6         | 0.87%   |
| 32.01-64.0 | 4         | 0.58%   |
| 24.01-32.0 | 3         | 0.44%   |
| Unknown    | 2         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 359       | 55.15%  |
| 2       | 193       | 29.65%  |
| 3       | 50        | 7.68%   |
| 4       | 20        | 3.07%   |
| 5       | 12        | 1.84%   |
| 6       | 6         | 0.92%   |
| 7       | 3         | 0.46%   |
| 8       | 2         | 0.31%   |
| 0       | 2         | 0.31%   |
| 15      | 1         | 0.15%   |
| 10      | 1         | 0.15%   |
| 9       | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 522       | 81.95%  |
| Yes       | 115       | 18.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 482       | 75.43%  |
| No        | 157       | 24.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 460       | 72.21%  |
| No        | 177       | 27.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 436       | 68.02%  |
| No        | 205       | 31.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| South Korea | 635       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Seoul           | 76        | 11.14%  |
| Suwon           | 30        | 4.4%    |
| Seongnam-si     | 30        | 4.4%    |
| Yongin-si       | 20        | 2.93%   |
| Seocho-gu       | 14        | 2.05%   |
| Seo-gu          | 13        | 1.91%   |
| Jung-gu         | 13        | 1.91%   |
| Gwanak-gu       | 13        | 1.91%   |
| Incheon         | 12        | 1.76%   |
| Hwaseong-si     | 12        | 1.76%   |
| Anyang-si       | 12        | 1.76%   |
| Gangbuk-gu      | 11        | 1.61%   |
| Busan           | 11        | 1.61%   |
| Bucheon-si      | 11        | 1.61%   |
| Yongsan-gu      | 10        | 1.47%   |
| Pyeongtaek-si   | 10        | 1.47%   |
| Mapo-gu         | 10        | 1.47%   |
| Uiwang          | 9         | 1.32%   |
| Seongbuk-gu     | 9         | 1.32%   |
| Namyangju       | 9         | 1.32%   |
| Daejeon         | 9         | 1.32%   |
| Cheonan         | 9         | 1.32%   |
| Nam-gu          | 8         | 1.17%   |
| Goyang-si       | 8         | 1.17%   |
| Gangnam-gu      | 8         | 1.17%   |
| Dongjak-gu      | 8         | 1.17%   |
| Buk-gu          | 8         | 1.17%   |
| Yuseong-gu      | 7         | 1.03%   |
| Yangcheon-gu    | 7         | 1.03%   |
| Songpa-gu       | 7         | 1.03%   |
| Jeonju          | 7         | 1.03%   |
| Gwangju         | 7         | 1.03%   |
| Gimpo-si        | 7         | 1.03%   |
| Gangseo-gu      | 7         | 1.03%   |
| Daegu           | 7         | 1.03%   |
| Cheongju-si     | 7         | 1.03%   |
| Jungnang-gu     | 6         | 0.88%   |
| Bupyeong-gu     | 6         | 0.88%   |
| Yeongdeungpo-gu | 5         | 0.73%   |
| Icheon-si       | 5         | 0.73%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 211       | 289    | 22.05%  |
| WDC                       | 116       | 171    | 12.12%  |
| Seagate                   | 81        | 120    | 8.46%   |
| SanDisk                   | 68        | 76     | 7.11%   |
| Unknown                   | 62        | 90     | 6.48%   |
| SK hynix                  | 53        | 67     | 5.54%   |
| Toshiba                   | 45        | 75     | 4.7%    |
| Crucial                   | 42        | 51     | 4.39%   |
| Micron Technology         | 23        | 25     | 2.4%    |
| Hitachi                   | 19        | 21     | 1.99%   |
| Intel                     | 18        | 25     | 1.88%   |
| A-DATA Technology         | 14        | 14     | 1.46%   |
| HGST                      | 11        | 14     | 1.15%   |
| Silicon Motion            | 10        | 13     | 1.04%   |
| Transcend                 | 9         | 10     | 0.94%   |
| Kingston                  | 8         | 10     | 0.84%   |
| Phison Electronics        | 7         | 8      | 0.73%   |
| Phison                    | 7         | 10     | 0.73%   |
| Micron/Crucial Technology | 7         | 7      | 0.73%   |
| Apple                     | 7         | 9      | 0.73%   |
| Team                      | 6         | 6      | 0.63%   |
| TAMMUZ                    | 6         | 9      | 0.63%   |
| RevuAhn                   | 5         | 7      | 0.52%   |
| Plextor                   | 5         | 9      | 0.52%   |
| LITEON                    | 5         | 5      | 0.52%   |
| Imation                   | 5         | 6      | 0.52%   |
| Hewlett-Packard           | 5         | 5      | 0.52%   |
| China                     | 5         | 5      | 0.52%   |
| SPCC                      | 4         | 4      | 0.42%   |
| OCZ                       | 4         | 5      | 0.42%   |
| KIOXIA                    | 4         | 7      | 0.42%   |
| JMicron Technology        | 4         | 4      | 0.42%   |
| Unknown                   | 4         | 4      | 0.42%   |
| UMIS                      | 3         | 3      | 0.31%   |
| KingSpec                  | 3         | 3      | 0.31%   |
| Fujitsu                   | 3         | 3      | 0.31%   |
| Biostar                   | 3         | 3      | 0.31%   |
| XPG                       | 2         | 3      | 0.21%   |
| Union Memory              | 2         | 2      | 0.21%   |
| TYPEC 1T                  | 2         | 2      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 16        | 1.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 11        | 1.04%   |
| Crucial CT500MX500SSD1 500GB                          | 11        | 1.04%   |
| Unknown MMC Card  32GB                                | 9         | 0.85%   |
| Unknown MMC Card  64GB                                | 8         | 0.75%   |
| Toshiba DT01ACA300 3TB                                | 8         | 0.75%   |
| Samsung MZVL21T0HCLR-00B00 1TB                        | 7         | 0.66%   |
| Crucial CT240BX500SSD1 240GB                          | 7         | 0.66%   |
| Unknown MMC Card  128GB                               | 6         | 0.57%   |
| SK hynix SHGP31-2000GM 2TB                            | 6         | 0.57%   |
| Seagate ST500DM002-1BD142 500GB                       | 6         | 0.57%   |
| Samsung NVMe SSD Drive 256GB                          | 6         | 0.57%   |
| Unknown SD/MMC/MS PRO 128GB                           | 5         | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB                        | 5         | 0.47%   |
| Seagate ST1000DM010-2EP102 1TB                        | 5         | 0.47%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 5         | 0.47%   |
| Samsung SSD 980 1TB                                   | 5         | 0.47%   |
| Samsung SSD 860 EVO 500GB                             | 5         | 0.47%   |
| Samsung SSD 850 EVO 120GB                             | 5         | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 4         | 0.38%   |
| WDC WDS100T2B0C-00PXH0 1TB                            | 4         | 0.38%   |
| WDC WD5000AAKX-00ERMA0 500GB                          | 4         | 0.38%   |
| Unknown MMC Card  512GB                               | 4         | 0.38%   |
| Toshiba DT01ACA200 2TB                                | 4         | 0.38%   |
| Toshiba DT01ACA050 500GB                              | 4         | 0.38%   |
| SK hynix SHGP31-500GM 500GB                           | 4         | 0.38%   |
| SK hynix SHGP31-1000GM-2 1TB                          | 4         | 0.38%   |
| SK hynix SHGP31-1000GM 1TB                            | 4         | 0.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 4         | 0.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 4         | 0.38%   |
| SanDisk SD8SBAT128G1122 128GB SSD                     | 4         | 0.38%   |
| SanDisk NVMe SSD Drive 512GB                          | 4         | 0.38%   |
| SanDisk NVMe SSD Drive 256GB                          | 4         | 0.38%   |
| Samsung SSD 850 PRO 256GB                             | 4         | 0.38%   |
| Samsung SSD 850 EVO 250GB                             | 4         | 0.38%   |
| Samsung NVMe SSD Drive 512GB                          | 4         | 0.38%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 4         | 0.38%   |
| HGST HTS721010A9E630 1TB                              | 4         | 0.38%   |
| Crucial CT1000MX500SSD1 1TB                           | 4         | 0.38%   |
| Unknown                                               | 4         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 82        | 125    | 32.16%  |
| Seagate             | 77        | 113    | 30.2%   |
| Toshiba             | 33        | 54     | 12.94%  |
| Hitachi             | 19        | 21     | 7.45%   |
| Samsung Electronics | 14        | 16     | 5.49%   |
| HGST                | 11        | 14     | 4.31%   |
| Unknown             | 5         | 6      | 1.96%   |
| Fujitsu             | 3         | 3      | 1.18%   |
| JMicron Technology  | 2         | 2      | 0.78%   |
| Hewlett-Packard     | 2         | 1      | 0.78%   |
| ASMT                | 2         | 2      | 0.78%   |
| MARVELL             | 1         | 1      | 0.39%   |
| Lenovo              | 1         | 2      | 0.39%   |
| LaCie               | 1         | 1      | 0.39%   |
| ipTIME              | 1         | 1      | 0.39%   |
| DELLBOSS            | 1         | 1      | 0.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 87        | 110    | 27.71%  |
| Crucial             | 38        | 47     | 12.1%   |
| SanDisk             | 34        | 39     | 10.83%  |
| WDC                 | 21        | 26     | 6.69%   |
| Intel               | 10        | 13     | 3.18%   |
| Transcend           | 9         | 10     | 2.87%   |
| SK hynix            | 9         | 13     | 2.87%   |
| A-DATA Technology   | 9         | 9      | 2.87%   |
| TAMMUZ              | 6         | 9      | 1.91%   |
| Toshiba             | 5         | 12     | 1.59%   |
| LITEON              | 5         | 5      | 1.59%   |
| China               | 5         | 5      | 1.59%   |
| Team                | 4         | 4      | 1.27%   |
| SPCC                | 4         | 4      | 1.27%   |
| Seagate             | 4         | 5      | 1.27%   |
| RevuAhn             | 4         | 6      | 1.27%   |
| Plextor             | 4         | 8      | 1.27%   |
| OCZ                 | 4         | 5      | 1.27%   |
| Micron Technology   | 4         | 5      | 1.27%   |
| Kingston            | 3         | 4      | 0.96%   |
| KingSpec            | 3         | 3      | 0.96%   |
| Imation             | 3         | 4      | 0.96%   |
| Biostar             | 3         | 3      | 0.96%   |
| Apple               | 3         | 3      | 0.96%   |
| Unknown             | 3         | 3      | 0.96%   |
| TYPEC 1T            | 2         | 2      | 0.64%   |
| QNIX                | 2         | 2      | 0.64%   |
| PNY                 | 2         | 2      | 0.64%   |
| LITEONIT            | 2         | 2      | 0.64%   |
| HPE                 | 2         | 5      | 0.64%   |
| Gigabyte Technology | 2         | 2      | 0.64%   |
| Apacer              | 2         | 2      | 0.64%   |
| ZTC                 | 1         | 1      | 0.32%   |
| VIEW                | 1         | 1      | 0.32%   |
| T-FORCE             | 1         | 1      | 0.32%   |
| SSSTC               | 1         | 1      | 0.32%   |
| Ramsta              | 1         | 3      | 0.32%   |
| PHINOCOM            | 1         | 1      | 0.32%   |
| OUTTON              | 1         | 1      | 0.32%   |
| OSCOO               | 1         | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 303       | 426    | 35.73%  |
| SSD     | 274       | 390    | 32.31%  |
| HDD     | 208       | 363    | 24.53%  |
| MMC     | 54        | 80     | 6.37%   |
| Unknown | 9         | 11     | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 362       | 716    | 47.32%  |
| NVMe | 303       | 418    | 39.61%  |
| MMC  | 54        | 80     | 7.06%   |
| SAS  | 46        | 56     | 6.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 291       | 424    | 57.06%  |
| 0.51-1.0   | 114       | 162    | 22.35%  |
| 1.01-2.0   | 46        | 62     | 9.02%   |
| 3.01-4.0   | 26        | 47     | 5.1%    |
| 4.01-10.0  | 16        | 29     | 3.14%   |
| 2.01-3.0   | 12        | 18     | 2.35%   |
| 10.01-20.0 | 4         | 10     | 0.78%   |
| 20.01-50.0 | 1         | 1      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 191       | 28.9%   |
| 251-500        | 120       | 18.15%  |
| 501-1000       | 99        | 14.98%  |
| 1001-2000      | 65        | 9.83%   |
| 51-100         | 53        | 8.02%   |
| More than 3000 | 45        | 6.81%   |
| 21-50          | 30        | 4.54%   |
| 2001-3000      | 26        | 3.93%   |
| 1-20           | 23        | 3.48%   |
| Unknown        | 9         | 1.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 250       | 36.71%  |
| 21-50          | 119       | 17.47%  |
| 101-250        | 95        | 13.95%  |
| 51-100         | 72        | 10.57%  |
| 251-500        | 54        | 7.93%   |
| 501-1000       | 40        | 5.87%   |
| 1001-2000      | 18        | 2.64%   |
| More than 3000 | 12        | 1.76%   |
| 2001-3000      | 12        | 1.76%   |
| Unknown        | 9         | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 2         | 2      | 4.55%   |
| WDC WD7500BPVT-22HXZT1 752GB                                    | 1         | 1      | 2.27%   |
| WDC WD7500AACS-00D6B0 752GB                                     | 1         | 1      | 2.27%   |
| WDC WD5000AAKX-75U6AA0 500GB                                    | 1         | 1      | 2.27%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 1         | 1      | 2.27%   |
| WDC WD40EZRZ-00WN9B0 4TB                                        | 1         | 1      | 2.27%   |
| WDC WD3200AAJS-00L7A0 320GB                                     | 1         | 2      | 2.27%   |
| WDC WD2000F9YZ-09N20L1 2TB                                      | 1         | 1      | 2.27%   |
| WDC WD1600BEVT-22A23T0 160GB                                    | 1         | 1      | 2.27%   |
| WDC WD10JPVX-75JC3T0 1TB                                        | 1         | 1      | 2.27%   |
| WDC WD10EZEX-60ZF5A0 1TB                                        | 1         | 1      | 2.27%   |
| WDC WD1003FBYX-01Y7B0 1TB                                       | 1         | 1      | 2.27%   |
| WDC WD1001FALS-00J7B1 1TB                                       | 1         | 1      | 2.27%   |
| Toshiba MK5061GSYN 500GB                                        | 1         | 1      | 2.27%   |
| Toshiba MK2565GSX 250GB                                         | 1         | 1      | 2.27%   |
| SSSTC CVB-8D128-HP 128GB SSD                                    | 1         | 1      | 2.27%   |
| SPCC Solid State Disk 128GB                                     | 1         | 1      | 2.27%   |
| SK hynix HFS512G39TND-N210A 512GB SSD                           | 1         | 1      | 2.27%   |
| SK hynix HFS128G3AMNM-1010A 128GB SSD                           | 1         | 1      | 2.27%   |
| Seagate ST500DM009-2F110A 500GB                                 | 1         | 1      | 2.27%   |
| Seagate ST4000DM000-1F2168 4TB                                  | 1         | 1      | 2.27%   |
| Seagate ST3500418AS 500GB                                       | 1         | 1      | 2.27%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 1         | 1      | 2.27%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 1         | 1      | 2.27%   |
| SanDisk SD9SN8W256G1009 256GB SSD                               | 1         | 1      | 2.27%   |
| Samsung Electronics SSD 830 Series 512GB                        | 1         | 1      | 2.27%   |
| Samsung Electronics SM961 NVMe 1024GB                           | 1         | 1      | 2.27%   |
| Samsung Electronics HM160HI 160GB                               | 1         | 1      | 2.27%   |
| Samsung Electronics HD160JJ 160GB                               | 1         | 1      | 2.27%   |
| Ramsta SSD S600 480GB                                           | 1         | 3      | 2.27%   |
| Phison ES 512GB                                                 | 1         | 2      | 2.27%   |
| LITEONIT LMT-256M3M 256GB SSD                                   | 1         | 1      | 2.27%   |
| LITEON LMH-128V2M 128GB SSD                                     | 1         | 1      | 2.27%   |
| KLEVV NEO N400 SSD 480GB                                        | 1         | 1      | 2.27%   |
| Kingston SHFS37A120G 120GB SSD                                  | 1         | 1      | 2.27%   |
| Intel SSDSA2CW120G3 120GB                                       | 1         | 1      | 2.27%   |
| Hitachi HTS543216L9A300 160GB                                   | 1         | 1      | 2.27%   |
| Hitachi HTS541616J9SA00 160GB                                   | 1         | 1      | 2.27%   |
| Hitachi HDS721050CLA362 500GB                                   | 1         | 1      | 2.27%   |
| Hitachi HDS721010CLA632 1TB                                     | 1         | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 13     | 27.27%  |
| Samsung Electronics | 6         | 6      | 13.64%  |
| Seagate             | 5         | 5      | 11.36%  |
| Hitachi             | 4         | 4      | 9.09%   |
| Toshiba             | 2         | 2      | 4.55%   |
| SK hynix            | 2         | 2      | 4.55%   |
| HGST                | 2         | 2      | 4.55%   |
| SSSTC               | 1         | 1      | 2.27%   |
| SPCC                | 1         | 1      | 2.27%   |
| SanDisk             | 1         | 1      | 2.27%   |
| Ramsta              | 1         | 3      | 2.27%   |
| Phison              | 1         | 2      | 2.27%   |
| LITEONIT            | 1         | 1      | 2.27%   |
| LITEON              | 1         | 1      | 2.27%   |
| KLEVV               | 1         | 1      | 2.27%   |
| Kingston            | 1         | 1      | 2.27%   |
| Intel               | 1         | 1      | 2.27%   |
| A-DATA Technology   | 1         | 1      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 13     | 44.44%  |
| Seagate             | 5         | 5      | 18.52%  |
| Hitachi             | 4         | 4      | 14.81%  |
| Toshiba             | 2         | 2      | 7.41%   |
| Samsung Electronics | 2         | 2      | 7.41%   |
| HGST                | 2         | 2      | 7.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 28     | 57.5%   |
| SSD  | 13        | 15     | 32.5%   |
| NVMe | 4         | 5      | 10%     |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 350       | 669    | 51.02%  |
| Works    | 296       | 553    | 43.15%  |
| Malfunc  | 40        | 48     | 5.83%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 346       | 40.75%  |
| Samsung Electronics              | 122       | 14.37%  |
| AMD                              | 112       | 13.19%  |
| SanDisk                          | 47        | 5.54%   |
| SK hynix                         | 43        | 5.06%   |
| ASMedia Technology               | 26        | 3.06%   |
| Phison Electronics               | 21        | 2.47%   |
| Micron Technology                | 19        | 2.24%   |
| Silicon Motion                   | 14        | 1.65%   |
| Micron/Crucial Technology        | 11        | 1.3%    |
| JMicron Technology               | 11        | 1.3%    |
| Toshiba America Info Systems     | 7         | 0.82%   |
| Broadcom / LSI                   | 7         | 0.82%   |
| Union Memory (Shenzhen)          | 6         | 0.71%   |
| Marvell Technology Group         | 6         | 0.71%   |
| ADATA Technology                 | 6         | 0.71%   |
| Kingston Technology Company      | 5         | 0.59%   |
| KIOXIA                           | 4         | 0.47%   |
| Apple                            | 4         | 0.47%   |
| Seagate Technology               | 3         | 0.35%   |
| LSI Logic / Symbios Logic        | 3         | 0.35%   |
| Biwin Storage Technology         | 3         | 0.35%   |
| Solidigm                         | 2         | 0.24%   |
| Solid State Storage Technology   | 2         | 0.24%   |
| Realtek Semiconductor            | 2         | 0.24%   |
| Nvidia                           | 2         | 0.24%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.24%   |
| Adaptec                          | 2         | 0.24%   |
| VIA Technologies                 | 1         | 0.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |
| Shenzhen Longsys Electronics     | 1         | 0.12%   |
| O2 Micro                         | 1         | 0.12%   |
| Lite-On Technology               | 1         | 0.12%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.12%   |
| Lenovo                           | 1         | 0.12%   |
| INNOGRIT                         | 1         | 0.12%   |
| Hosin Global Electronics         | 1         | 0.12%   |
| Hewlett-Packard                  | 1         | 0.12%   |
| 3ware                            | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 78        | 8.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 51        | 5.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 35        | 3.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 30        | 3.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 25        | 2.61%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 25        | 2.61%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 22        | 2.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19        | 1.99%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 18        | 1.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 17        | 1.78%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 15        | 1.57%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 14        | 1.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 14        | 1.46%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 12        | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 11        | 1.15%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 11        | 1.15%   |
| AMD 600 Series Chipset SATA Controller                                                  | 11        | 1.15%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11        | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10        | 1.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 10        | 1.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 1.04%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 10        | 1.04%   |
| AMD 300 Series Chipset SATA Controller                                                  | 10        | 1.04%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9         | 0.94%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 8         | 0.84%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8         | 0.84%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 8         | 0.84%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 8         | 0.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 0.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 0.84%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 7         | 0.73%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 7         | 0.73%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7         | 0.73%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 7         | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 7         | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 405       | 50.19%  |
| NVMe | 305       | 37.79%  |
| IDE  | 51        | 6.32%   |
| RAID | 40        | 4.96%   |
| SAS  | 4         | 0.5%    |
| SCSI | 2         | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 458       | 72.13%  |
| AMD     | 165       | 25.98%  |
| ARM     | 11        | 1.73%   |
| Unknown | 1         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 1.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 10        | 1.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 9         | 1.42%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 9         | 1.42%   |
| ARM Processor                                 | 9         | 1.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 0.94%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 6         | 0.94%   |
| Intel 12th Gen Core i5-1240P                  | 6         | 0.94%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 6         | 0.94%   |
| AMD Custom APU 0405                           | 6         | 0.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.79%   |
| Intel Core i5-8500 CPU @ 3.00GHz              | 5         | 0.79%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.79%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 0.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.79%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 5         | 0.79%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.79%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 4         | 0.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 0.63%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.63%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 4         | 0.63%   |
| Intel 12th Gen Core i7-1260P                  | 4         | 0.63%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 4         | 0.63%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4         | 0.63%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 4         | 0.63%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.63%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 4         | 0.63%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3         | 0.47%   |
| Intel Core i9-14900K                          | 3         | 0.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.47%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.47%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 3         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 111       | 17.48%  |
| Other                   | 100       | 15.75%  |
| Intel Core i7           | 90        | 14.17%  |
| AMD Ryzen 5             | 54        | 8.5%    |
| AMD Ryzen 7             | 38        | 5.98%   |
| Intel Core i3           | 28        | 4.41%   |
| Intel Xeon              | 25        | 3.94%   |
| Intel Celeron           | 25        | 3.94%   |
| Intel Pentium           | 20        | 3.15%   |
| AMD Ryzen 9             | 15        | 2.36%   |
| Intel Core i9           | 14        | 2.2%    |
| Intel Atom              | 13        | 2.05%   |
| Intel Core 2 Duo        | 12        | 1.89%   |
| AMD Ryzen 3             | 10        | 1.57%   |
| AMD Ryzen Threadripper  | 7         | 1.1%    |
| Intel Xeon Silver       | 6         | 0.94%   |
| Intel Core 2 Quad       | 6         | 0.94%   |
| AMD Ryzen 7 PRO         | 6         | 0.94%   |
| AMD Ryzen 5 PRO         | 6         | 0.94%   |
| Intel Core              | 5         | 0.79%   |
| AMD A10                 | 5         | 0.79%   |
| Intel Core m3           | 4         | 0.63%   |
| Intel Pentium Dual-Core | 3         | 0.47%   |
| Intel Genuine           | 3         | 0.47%   |
| Intel Core 2            | 3         | 0.47%   |
| Intel Pentium Silver    | 2         | 0.31%   |
| Intel Pentium Gold      | 2         | 0.31%   |
| Intel Pentium 4         | 2         | 0.31%   |
| AMD FX                  | 2         | 0.31%   |
| AMD A8                  | 2         | 0.31%   |
| AMD A6                  | 2         | 0.31%   |
| AMD A4                  | 2         | 0.31%   |
| Intel Xeon Gold         | 1         | 0.16%   |
| Intel Pentium Dual      | 1         | 0.16%   |
| ARM AArch64             | 1         | 0.16%   |
| AMD Ryzen Embedded      | 1         | 0.16%   |
| AMD Quad-Core           | 1         | 0.16%   |
| AMD Phenom II X6        | 1         | 0.16%   |
| AMD Phenom              | 1         | 0.16%   |
| AMD Athlon II X2        | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 221       | 34.8%   |
| 2       | 165       | 25.98%  |
| 6       | 90        | 14.17%  |
| 8       | 68        | 10.71%  |
| 12      | 26        | 4.09%   |
| 16      | 19        | 2.99%   |
| 10      | 13        | 2.05%   |
| 14      | 10        | 1.57%   |
| 24      | 5         | 0.79%   |
| 32      | 4         | 0.63%   |
| 20      | 3         | 0.47%   |
| 1       | 3         | 0.47%   |
| 28      | 2         | 0.31%   |
| Unknown | 2         | 0.31%   |
| 64      | 1         | 0.16%   |
| 40      | 1         | 0.16%   |
| 22      | 1         | 0.16%   |
| 18      | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 621       | 97.8%   |
| 2       | 12        | 1.89%   |
| 4       | 1         | 0.16%   |
| Unknown | 1         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 450       | 70.75%  |
| 1       | 184       | 28.93%  |
| Unknown | 2         | 0.31%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 624       | 98.11%  |
| Unknown        | 10        | 1.57%   |
| 64-bit         | 1         | 0.16%   |
| 32-bit         | 1         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 206       | 31.6%   |
| 0x306a9    | 31        | 4.75%   |
| 0x306c3    | 22        | 3.37%   |
| 0x806c1    | 21        | 3.22%   |
| 0x806ec    | 18        | 2.76%   |
| 0x906ea    | 15        | 2.3%    |
| 0x906e9    | 14        | 2.15%   |
| 0x206a7    | 14        | 2.15%   |
| 0x906a3    | 13        | 1.99%   |
| 0x08600106 | 13        | 1.99%   |
| 0x806ea    | 12        | 1.84%   |
| 0x806e9    | 12        | 1.84%   |
| 0x0a50000c | 11        | 1.69%   |
| 0x1067a    | 9         | 1.38%   |
| 0x906ed    | 8         | 1.23%   |
| 0x20655    | 8         | 1.23%   |
| 0x806eb    | 7         | 1.07%   |
| 0x706a1    | 7         | 1.07%   |
| 0x506e3    | 7         | 1.07%   |
| 0x406c4    | 7         | 1.07%   |
| 0x0a50000d | 7         | 1.07%   |
| 0x40651    | 6         | 0.92%   |
| 0x30678    | 6         | 0.92%   |
| 0x08108102 | 6         | 0.92%   |
| 0xb0671    | 5         | 0.77%   |
| 0x706e5    | 5         | 0.77%   |
| 0x306f2    | 5         | 0.77%   |
| 0x306d4    | 5         | 0.77%   |
| 0x106e5    | 5         | 0.77%   |
| 0x0a404102 | 5         | 0.77%   |
| 0x08608103 | 5         | 0.77%   |
| 0x08001138 | 5         | 0.77%   |
| 0xa0652    | 4         | 0.61%   |
| 0x806d1    | 4         | 0.61%   |
| 0x6fd      | 4         | 0.61%   |
| 0x6fb      | 4         | 0.61%   |
| 0x50657    | 4         | 0.61%   |
| 0x406e3    | 4         | 0.61%   |
| 0x08108109 | 4         | 0.61%   |
| 0x08101016 | 4         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 115       | 18.08%  |
| Unknown           | 77        | 12.11%  |
| Haswell           | 51        | 8.02%   |
| IvyBridge         | 37        | 5.82%   |
| Zen 3             | 34        | 5.35%   |
| Zen 2             | 32        | 5.03%   |
| Skylake           | 31        | 4.87%   |
| Alderlake Hybrid  | 31        | 4.87%   |
| TigerLake         | 25        | 3.93%   |
| Zen               | 21        | 3.3%    |
| Silvermont        | 21        | 3.3%    |
| Zen+              | 18        | 2.83%   |
| SandyBridge       | 16        | 2.52%   |
| Penryn            | 16        | 2.52%   |
| Westmere          | 15        | 2.36%   |
| Icelake           | 13        | 2.04%   |
| CometLake         | 13        | 2.04%   |
| Core              | 12        | 1.89%   |
| Goldmont plus     | 11        | 1.73%   |
| Broadwell         | 10        | 1.57%   |
| Piledriver        | 6         | 0.94%   |
| Nehalem           | 6         | 0.94%   |
| K10               | 4         | 0.63%   |
| Meteorlake Hybrid | 3         | 0.47%   |
| Jaguar            | 3         | 0.47%   |
| Excavator         | 3         | 0.47%   |
| Steamroller       | 2         | 0.31%   |
| NetBurst          | 2         | 0.31%   |
| Gracemont         | 2         | 0.31%   |
| Tremont           | 1         | 0.16%   |
| P6                | 1         | 0.16%   |
| K8 Hammer         | 1         | 0.16%   |
| K10 Llano         | 1         | 0.16%   |
| Goldmont          | 1         | 0.16%   |
| Bonnell           | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 354       | 47.45%  |
| Nvidia                           | 213       | 28.55%  |
| AMD                              | 161       | 21.58%  |
| ASPEED Technology                | 9         | 1.21%   |
| Matrox Electronics Systems       | 8         | 1.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 23        | 3.01%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 20        | 2.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 2.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 15        | 1.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 1.96%   |
| Intel UHD Graphics 620                                                                   | 14        | 1.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 1.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 1.57%   |
| AMD Barcelo                                                                              | 12        | 1.57%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 1.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.31%   |
| AMD Rembrandt [Radeon 680M]                                                              | 10        | 1.31%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 1.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 1.31%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 1.18%   |
| Intel HD Graphics 630                                                                    | 9         | 1.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 1.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.18%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 9         | 1.18%   |
| AMD Raphael                                                                              | 9         | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 1.05%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 8         | 1.05%   |
| Intel HD Graphics 620                                                                    | 8         | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 1.05%   |
| AMD Lucienne                                                                             | 8         | 1.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 0.92%   |
| Nvidia TU117M [GeForce MX450]                                                            | 6         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 0.78%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 6         | 0.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 0.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 0.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.78%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 6         | 0.78%   |
| Nvidia GP108M [GeForce MX250]                                                            | 5         | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x Intel                 | 255       | 39.84%  |
| 1 x AMD                   | 127       | 19.84%  |
| 1 x Nvidia                | 118       | 18.44%  |
| Intel + Nvidia            | 72        | 11.25%  |
| AMD + Nvidia              | 14        | 2.19%   |
| Other                     | 12        | 1.88%   |
| Intel + AMD               | 11        | 1.72%   |
| 2 x AMD                   | 10        | 1.56%   |
| 1 x Matrox                | 6         | 0.94%   |
| 1 x ASPEED                | 5         | 0.78%   |
| Nvidia + ASPEED           | 3         | 0.47%   |
| 2 x Nvidia                | 2         | 0.31%   |
| Nvidia + Matrox           | 2         | 0.31%   |
| 1 x SiS                   | 1         | 0.16%   |
| AMD + 2 x Nvidia          | 1         | 0.16%   |
| AMD + Nvidia + 1 x ASPEED | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 475       | 73.99%  |
| Proprietary | 119       | 18.54%  |
| Unknown     | 48        | 7.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 381       | 58.89%  |
| 1.01-2.0   | 59        | 9.12%   |
| 0.01-0.5   | 57        | 8.81%   |
| 3.01-4.0   | 43        | 6.65%   |
| 0.51-1.0   | 41        | 6.34%   |
| 7.01-8.0   | 26        | 4.02%   |
| 8.01-16.0  | 16        | 2.47%   |
| 5.01-6.0   | 11        | 1.7%    |
| 2.01-3.0   | 5         | 0.77%   |
| 16.01-24.0 | 5         | 0.77%   |
| 6.01-7.0   | 1         | 0.15%   |
| 32.01-64.0 | 1         | 0.15%   |
| 4.01-5.0   | 1         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 103       | 15.51%  |
| Goldstar                | 73        | 10.99%  |
| LG Display              | 66        | 9.94%   |
| AU Optronics            | 60        | 9.04%   |
| BOE                     | 50        | 7.53%   |
| Chimei Innolux          | 45        | 6.78%   |
| Dell                    | 23        | 3.46%   |
| Apple                   | 13        | 1.96%   |
| AOC                     | 13        | 1.96%   |
| Philips                 | 12        | 1.81%   |
| Unknown                 | 11        | 1.66%   |
| Sharp                   | 11        | 1.66%   |
| Hewlett-Packard         | 11        | 1.66%   |
| BenQ                    | 10        | 1.51%   |
| LG Electronics          | 8         | 1.2%    |
| Valve                   | 7         | 1.05%   |
| PANDA                   | 7         | 1.05%   |
| Lenovo                  | 7         | 1.05%   |
| JCH                     | 7         | 1.05%   |
| ALP                     | 7         | 1.05%   |
| PRISM+                  | 6         | 0.9%    |
| OUT                     | 5         | 0.75%   |
| Unknown (ADE)           | 4         | 0.6%    |
| RTK                     | 4         | 0.6%    |
| InfoVision              | 4         | 0.6%    |
| Chi Mei Optoelectronics | 4         | 0.6%    |
| Sony                    | 3         | 0.45%   |
| JRY                     | 3         | 0.45%   |
| CSO                     | 3         | 0.45%   |
| CPT                     | 3         | 0.45%   |
| Ancor Communications    | 3         | 0.45%   |
| ZTL                     | 2         | 0.3%    |
| XUE                     | 2         | 0.3%    |
| Xiangye                 | 2         | 0.3%    |
| WIT                     | 2         | 0.3%    |
| TMX                     | 2         | 0.3%    |
| SANYO                   | 2         | 0.3%    |
| ORM                     | 2         | 0.3%    |
| OOO                     | 2         | 0.3%    |
| MStar                   | 2         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 10        | 1.46%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 9         | 1.32%   |
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                 | 9         | 1.32%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 6         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 4         | 0.59%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 4         | 0.59%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 4         | 0.59%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.59%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch     | 3         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4186 2880x1800 302x189mm 14.0-inch | 3         | 0.44%   |
| OUT HDMI OUT0240 1920x1200 341x256mm 16.8-inch                        | 3         | 0.44%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch          | 3         | 0.44%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 3         | 0.44%   |
| JCH UDEA Monitor JCHE321 1920x1080 443x249mm 20.0-inch                | 3         | 0.44%   |
| Goldstar W2261 GSM56CF 1920x1080 477x268mm 21.5-inch                  | 3         | 0.44%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 3         | 0.44%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                 | 3         | 0.44%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 3         | 0.44%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 3         | 0.44%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                 | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.44%   |
| ALP 2400 ADS ALP2400 1920x1080 528x297mm 23.9-inch                    | 3         | 0.44%   |
| ZTL ZM29W1 ZTL1506 2560x1080 1600x1000mm 74.3-inch                    | 2         | 0.29%   |
| XUE Type-C XUE1600 2560x1600 360x190mm 16.0-inch                      | 2         | 0.29%   |
| Xiangye N2408HZ XYE2700 1920x1080 597x336mm 27.0-inch                 | 2         | 0.29%   |
| WIT HDMI WIT5082 2560x1440 596x335mm 26.9-inch                        | 2         | 0.29%   |
| Sony BW8 MS_9001 2560x1600                                            | 2         | 0.29%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.29%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch  | 2         | 0.29%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 2         | 0.29%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4188 2880x1800 312x195mm 14.5-inch | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 321       | 49.54%  |
| 3840x2160 (4K)     | 63        | 9.72%   |
| 1366x768 (WXGA)    | 46        | 7.1%    |
| 2560x1440 (QHD)    | 43        | 6.64%   |
| 1920x1200 (WUXGA)  | 23        | 3.55%   |
| 2560x1600          | 21        | 3.24%   |
| 1280x1024 (SXGA)   | 16        | 2.47%   |
| 2880x1800          | 15        | 2.31%   |
| 3440x1440          | 13        | 2.01%   |
| 1600x900 (HD+)     | 10        | 1.54%   |
| 2560x1080          | 9         | 1.39%   |
| 1680x1050 (WSXGA+) | 9         | 1.39%   |
| 1280x800 (WXGA)    | 9         | 1.39%   |
| 800x1280           | 7         | 1.08%   |
| 1440x900 (WXGA+)   | 6         | 0.93%   |
| Unknown            | 5         | 0.77%   |
| 3840x2400          | 4         | 0.62%   |
| 2880x1620          | 3         | 0.46%   |
| 3840x1080          | 2         | 0.31%   |
| 3072x1920          | 2         | 0.31%   |
| 1920x1280          | 2         | 0.31%   |
| 1600x2560          | 2         | 0.31%   |
| 4880x2560          | 1         | 0.15%   |
| 3840x1600          | 1         | 0.15%   |
| 3286x1080          | 1         | 0.15%   |
| 3200x1080          | 1         | 0.15%   |
| 3000x2000          | 1         | 0.15%   |
| 2288x1287          | 1         | 0.15%   |
| 2160x3840          | 1         | 0.15%   |
| 2160x1440          | 1         | 0.15%   |
| 2160x1350          | 1         | 0.15%   |
| 2160x1200          | 1         | 0.15%   |
| 1920x540           | 1         | 0.15%   |
| 1680x945           | 1         | 0.15%   |
| 1600x1200          | 1         | 0.15%   |
| 1400x1050          | 1         | 0.15%   |
| 1280x960           | 1         | 0.15%   |
| 1128x1504          | 1         | 0.15%   |
| 1024x768 (XGA)     | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 153       | 22.94%  |
| 13      | 61        | 9.15%   |
| 27      | 58        | 8.7%    |
| 14      | 51        | 7.65%   |
| Unknown | 43        | 6.45%   |
| 24      | 41        | 6.15%   |
| 23      | 38        | 5.7%    |
| 31      | 35        | 5.25%   |
| 16      | 29        | 4.35%   |
| 21      | 28        | 4.2%    |
| 17      | 16        | 2.4%    |
| 34      | 12        | 1.8%    |
| 20      | 12        | 1.8%    |
| 19      | 11        | 1.65%   |
| 12      | 7         | 1.05%   |
| 7       | 7         | 1.05%   |
| 40      | 5         | 0.75%   |
| 18      | 5         | 0.75%   |
| 11      | 5         | 0.75%   |
| 8       | 4         | 0.6%    |
| 84      | 3         | 0.45%   |
| 74      | 3         | 0.45%   |
| 42      | 3         | 0.45%   |
| 29      | 3         | 0.45%   |
| 25      | 3         | 0.45%   |
| 22      | 3         | 0.45%   |
| 10      | 3         | 0.45%   |
| 54      | 2         | 0.3%    |
| 52      | 2         | 0.3%    |
| 49      | 2         | 0.3%    |
| 39      | 2         | 0.3%    |
| 35      | 2         | 0.3%    |
| 32      | 2         | 0.3%    |
| 28      | 2         | 0.3%    |
| 26      | 2         | 0.3%    |
| 142     | 1         | 0.15%   |
| 72      | 1         | 0.15%   |
| 57      | 1         | 0.15%   |
| 48      | 1         | 0.15%   |
| 46      | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 245       | 37.18%  |
| 501-600        | 131       | 19.88%  |
| 201-300        | 58        | 8.8%    |
| 401-500        | 49        | 7.44%   |
| 601-700        | 43        | 6.53%   |
| Unknown        | 43        | 6.53%   |
| 351-400        | 32        | 4.86%   |
| 701-800        | 15        | 2.28%   |
| 801-900        | 10        | 1.52%   |
| 1001-1500      | 9         | 1.37%   |
| 1501-2000      | 7         | 1.06%   |
| 1-100          | 7         | 1.06%   |
| 101-200        | 5         | 0.76%   |
| 901-1000       | 4         | 0.61%   |
| More than 2000 | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 414       | 69.12%  |
| 16/10   | 84        | 14.02%  |
| Unknown | 37        | 6.18%   |
| 21/9    | 16        | 2.67%   |
| 5/4     | 14        | 2.34%   |
| 4/3     | 10        | 1.67%   |
| 3/2     | 7         | 1.17%   |
| 0.67    | 6         | 1%      |
| 0.62    | 4         | 0.67%   |
| 32/9    | 3         | 0.5%    |
| 6/5     | 1         | 0.17%   |
| 1.00    | 1         | 0.17%   |
| 0.58    | 1         | 0.17%   |
| 0.56    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 153       | 23.01%  |
| 201-250        | 89        | 13.38%  |
| 81-90          | 74        | 11.13%  |
| 301-350        | 61        | 9.17%   |
| 351-500        | 57        | 8.57%   |
| Unknown        | 43        | 6.47%   |
| 71-80          | 35        | 5.26%   |
| 151-200        | 28        | 4.21%   |
| 111-120        | 20        | 3.01%   |
| 251-300        | 19        | 2.86%   |
| More than 1000 | 14        | 2.11%   |
| 501-1000       | 14        | 2.11%   |
| 1-40           | 12        | 1.8%    |
| 121-130        | 12        | 1.8%    |
| 61-70          | 7         | 1.05%   |
| 141-150        | 7         | 1.05%   |
| 51-60          | 6         | 0.9%    |
| 131-140        | 6         | 0.9%    |
| 91-100         | 6         | 0.9%    |
| 41-50          | 2         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 186       | 28.93%  |
| 51-100        | 180       | 27.99%  |
| 101-120       | 103       | 16.02%  |
| 161-240       | 88        | 13.69%  |
| Unknown       | 43        | 6.69%   |
| More than 240 | 30        | 4.67%   |
| 1-50          | 13        | 2.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 498       | 76.73%  |
| 2     | 95        | 14.64%  |
| 0     | 48        | 7.4%    |
| 3     | 7         | 1.08%   |
| 4     | 1         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 351       | 39.31%  |
| Intel                             | 337       | 37.74%  |
| Qualcomm Atheros                  | 55        | 6.16%   |
| Broadcom                          | 39        | 4.37%   |
| MediaTek                          | 25        | 2.8%    |
| Ralink Technology                 | 10        | 1.12%   |
| ASIX Electronics                  | 10        | 1.12%   |
| Marvell Technology Group          | 8         | 0.9%    |
| Broadcom Limited                  | 7         | 0.78%   |
| Samsung Electronics               | 6         | 0.67%   |
| Ralink                            | 4         | 0.45%   |
| U-Blox                            | 3         | 0.34%   |
| Apple                             | 3         | 0.34%   |
| Van Ooijen Technische Informatica | 2         | 0.22%   |
| TP-Link                           | 2         | 0.22%   |
| Qualcomm                          | 2         | 0.22%   |
| Nvidia                            | 2         | 0.22%   |
| Lenovo                            | 2         | 0.22%   |
| Exar                              | 2         | 0.22%   |
| D-Link                            | 2         | 0.22%   |
| Arduino SA                        | 2         | 0.22%   |
| Aquantia                          | 2         | 0.22%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.11%   |
| Wilocity                          | 1         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.11%   |
| Raspberry Pi                      | 1         | 0.11%   |
| Quectel Wireless Solutions        | 1         | 0.11%   |
| Qualcomm Technologies             | 1         | 0.11%   |
| Qualcomm Atheros Communications   | 1         | 0.11%   |
| PEAK-System Technik               | 1         | 0.11%   |
| NetGear                           | 1         | 0.11%   |
| Microsoft                         | 1         | 0.11%   |
| Microchip Technology              | 1         | 0.11%   |
| Kinesis                           | 1         | 0.11%   |
| JMicron Technology                | 1         | 0.11%   |
| IBM                               | 1         | 0.11%   |
| Comneon                           | 1         | 0.11%   |
| Chelsio Communications            | 1         | 0.11%   |
| American Megatrends               | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 242       | 23.22%  |
| Intel Wi-Fi 6 AX200                                                    | 47        | 4.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 43        | 4.13%   |
| Realtek RTL8125 2.5GbE Controller                                      | 25        | 2.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 24        | 2.3%    |
| Intel Wi-Fi 6 AX201                                                    | 21        | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 18        | 1.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 1.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 17        | 1.63%   |
| Intel Wireless 3165                                                    | 16        | 1.54%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 15        | 1.44%   |
| Intel Wireless 8265 / 8275                                             | 15        | 1.44%   |
| Intel Ethernet Controller I225-V                                       | 15        | 1.44%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 13        | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 12        | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 11        | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 11        | 1.06%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 10        | 0.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 10        | 0.96%   |
| Intel Wireless 7260                                                    | 10        | 0.96%   |
| ASIX AX88179 Gigabit Ethernet                                          | 10        | 0.96%   |
| Intel I210 Gigabit Network Connection                                  | 9         | 0.86%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 0.86%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 8         | 0.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 0.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 7         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 7         | 0.67%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 7         | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 6         | 0.58%   |
| Intel Wireless 7265                                                    | 6         | 0.58%   |
| Intel Wireless 3160                                                    | 6         | 0.58%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 6         | 0.58%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 6         | 0.58%   |
| Intel Ethernet Connection (7) I219-V                                   | 6         | 0.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5         | 0.48%   |
| Realtek 802.11ac NIC                                                   | 5         | 0.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 0.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 274       | 57.08%  |
| Realtek Semiconductor           | 83        | 17.29%  |
| Qualcomm Atheros                | 42        | 8.75%   |
| Broadcom                        | 28        | 5.83%   |
| MediaTek                        | 21        | 4.38%   |
| Ralink Technology               | 10        | 2.08%   |
| Broadcom Limited                | 5         | 1.04%   |
| Ralink                          | 4         | 0.83%   |
| TP-Link                         | 2         | 0.42%   |
| Qualcomm                        | 2         | 0.42%   |
| D-Link                          | 2         | 0.42%   |
| Wilocity                        | 1         | 0.21%   |
| Quectel Wireless Solutions      | 1         | 0.21%   |
| Qualcomm Technologies           | 1         | 0.21%   |
| Qualcomm Atheros Communications | 1         | 0.21%   |
| NetGear                         | 1         | 0.21%   |
| Marvell Technology Group        | 1         | 0.21%   |
| Arduino SA                      | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 47        | 9.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 24        | 4.96%   |
| Intel Wi-Fi 6 AX201                                            | 21        | 4.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 18        | 3.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 17        | 3.51%   |
| Intel Wireless 3165                                            | 16        | 3.31%   |
| Intel Wireless 8265 / 8275                                     | 15        | 3.1%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 13        | 2.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 12        | 2.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 2.27%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 11        | 2.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 11        | 2.27%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 10        | 2.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 2.07%   |
| Intel Wireless 7260                                            | 10        | 2.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8         | 1.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 7         | 1.45%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 7         | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.24%   |
| Intel Wireless 7265                                            | 6         | 1.24%   |
| Intel Wireless 3160                                            | 6         | 1.24%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 1.24%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 6         | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 1.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 1.03%   |
| Realtek 802.11ac NIC                                           | 5         | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 1.03%   |
| Intel Meteor Lake PCH CNVi WiFi                                | 5         | 1.03%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 5         | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 0.83%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 4         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 0.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 0.83%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 0.83%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 4         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 323       | 62.96%  |
| Intel                            | 116       | 22.61%  |
| Qualcomm Atheros                 | 15        | 2.92%   |
| Broadcom                         | 13        | 2.53%   |
| ASIX Electronics                 | 10        | 1.95%   |
| Marvell Technology Group         | 7         | 1.36%   |
| Samsung Electronics              | 6         | 1.17%   |
| MediaTek                         | 4         | 0.78%   |
| Apple                            | 3         | 0.58%   |
| Nvidia                           | 2         | 0.39%   |
| Lenovo                           | 2         | 0.39%   |
| Broadcom Limited                 | 2         | 0.39%   |
| Aquantia                         | 2         | 0.39%   |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |
| Raspberry Pi                     | 1         | 0.19%   |
| Microsoft                        | 1         | 0.19%   |
| Microchip Technology             | 1         | 0.19%   |
| JMicron Technology               | 1         | 0.19%   |
| IBM                              | 1         | 0.19%   |
| Chelsio Communications           | 1         | 0.19%   |
| American Megatrends              | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 242       | 44.32%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 43        | 7.88%   |
| Realtek RTL8125 2.5GbE Controller                                      | 25        | 4.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 3.11%   |
| Intel Ethernet Controller I225-V                                       | 15        | 2.75%   |
| ASIX AX88179 Gigabit Ethernet                                          | 10        | 1.83%   |
| Intel I210 Gigabit Network Connection                                  | 9         | 1.65%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 1.65%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 1.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 7         | 1.28%   |
| Intel Ethernet Connection (7) I219-V                                   | 6         | 1.1%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.73%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.73%   |
| Intel Ethernet Controller X550                                         | 4         | 0.73%   |
| Intel Ethernet Controller I226-V                                       | 4         | 0.73%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 0.73%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.73%   |
| Intel 82574L Gigabit Network Connection                                | 4         | 0.73%   |
| Intel I350 Gigabit Network Connection                                  | 3         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.55%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 0.55%   |
| Intel Ethernet Connection (2) I218-V                                   | 3         | 0.55%   |
| Intel Ethernet Connection (2) I218-LM                                  | 3         | 0.55%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.55%   |
| Intel 82576 Gigabit Network Connection                                 | 3         | 0.55%   |
| Samsung USB LAN AA-AE3AUUB                                             | 2         | 0.37%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 2         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.37%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.37%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 0.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.37%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2        | 2         | 0.37%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.37%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.37%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.37%   |
| Intel Ethernet Connection (11) I219-V                                  | 2         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 478       | 50.53%  |
| WiFi     | 458       | 48.41%  |
| Modem    | 9         | 0.95%   |
| Unknown  | 1         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 344       | 52.2%   |
| Ethernet | 315       | 47.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 333       | 52.36%  |
| 2     | 261       | 41.04%  |
| 3     | 17        | 2.67%   |
| 0     | 14        | 2.2%    |
| 4     | 9         | 1.42%   |
| 5     | 2         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 628       | 98.74%  |
| Yes  | 8         | 1.26%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 249       | 56.85%  |
| Realtek Semiconductor           | 43        | 9.82%   |
| Cambridge Silicon Radio         | 32        | 7.31%   |
| IMC Networks                    | 31        | 7.08%   |
| Broadcom                        | 21        | 4.79%   |
| Qualcomm Atheros Communications | 19        | 4.34%   |
| Foxconn / Hon Hai               | 13        | 2.97%   |
| Apple                           | 9         | 2.05%   |
| MediaTek                        | 5         | 1.14%   |
| Lite-On Technology              | 5         | 1.14%   |
| ASUSTek Computer                | 3         | 0.68%   |
| TP-Link                         | 2         | 0.46%   |
| Realtek                         | 1         | 0.23%   |
| Qcom                            | 1         | 0.23%   |
| Micro Star International        | 1         | 0.23%   |
| Marvell Semiconductor           | 1         | 0.23%   |
| Hewlett-Packard                 | 1         | 0.23%   |
| Unknown                         | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 57        | 12.98%  |
| Intel AX201 Bluetooth                               | 51        | 11.62%  |
| Intel AX200 Bluetooth                               | 45        | 10.25%  |
| Intel AX211 Bluetooth                               | 37        | 8.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 32        | 7.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 31        | 7.06%   |
| Realtek Bluetooth Radio                             | 28        | 6.38%   |
| Intel AX210 Bluetooth                               | 12        | 2.73%   |
| IMC Networks Wireless_Device                        | 12        | 2.73%   |
| IMC Networks Bluetooth Radio                        | 10        | 2.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 9         | 2.05%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.59%   |
| Apple Bluetooth Host Controller                     | 7         | 1.59%   |
| Realtek 802.11ac WLAN Adapter                       | 6         | 1.37%   |
| IMC Networks Bluetooth Device                       | 6         | 1.37%   |
| MediaTek Wireless_Device                            | 5         | 1.14%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 0.91%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.91%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 0.91%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.91%   |
| Lite-On Bluetooth Device                            | 3         | 0.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.68%   |
| Foxconn / Hon Hai BCM2045A0                         | 3         | 0.68%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 3         | 0.68%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 2         | 0.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.46%   |
| Realtek Bluetooth 5.3 Radio                         | 2         | 0.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.46%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.46%   |
| Intel Bluetooth Device                              | 2         | 0.46%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.46%   |
| Broadcom BCM2070 Bluetooth Device                   | 2         | 0.46%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.46%   |
| Realtek CSR BS8510                                  | 1         | 0.23%   |
| Realtek Bluetooth Radio                             | 1         | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 425       | 50%     |
| AMD                                          | 186       | 21.88%  |
| Nvidia                                       | 159       | 18.71%  |
| C-Media Electronics                          | 12        | 1.41%   |
| ASUSTek Computer                             | 8         | 0.94%   |
| Micro Star International                     | 6         | 0.71%   |
| JMTek                                        | 6         | 0.71%   |
| Texas Instruments                            | 3         | 0.35%   |
| Lenovo                                       | 3         | 0.35%   |
| Giga-Byte Technology                         | 3         | 0.35%   |
| Apple                                        | 3         | 0.35%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.24%   |
| TTGK Technology                              | 2         | 0.24%   |
| Sony                                         | 2         | 0.24%   |
| Generalplus Technology                       | 2         | 0.24%   |
| Focusrite-Novation                           | 2         | 0.24%   |
| Conexant Systems                             | 2         | 0.24%   |
| XMOS                                         | 1         | 0.12%   |
| VIA Technologies                             | 1         | 0.12%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.12%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.12%   |
| Samsung Electronics                          | 1         | 0.12%   |
| Realtek Semiconductor                        | 1         | 0.12%   |
| Razer USA                                    | 1         | 0.12%   |
| No brand                                     | 1         | 0.12%   |
| Native Instruments                           | 1         | 0.12%   |
| Medeli Electronics                           | 1         | 0.12%   |
| KTMicro                                      | 1         | 0.12%   |
| Kingston Technology                          | 1         | 0.12%   |
| Fry's Electronics                            | 1         | 0.12%   |
| EGO SYStems                                  | 1         | 0.12%   |
| DigiTech                                     | 1         | 0.12%   |
| Dell                                         | 1         | 0.12%   |
| Corsair                                      | 1         | 0.12%   |
| CMX Systems                                  | 1         | 0.12%   |
| BEHRINGER International                      | 1         | 0.12%   |
| Barco Display Systems                        | 1         | 0.12%   |
| B & W Group                                  | 1         | 0.12%   |
| Audient                                      | 1         | 0.12%   |
| ASRock                                       | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 97        | 9.54%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 55        | 5.41%   |
| Intel Sunrise Point-LP HD Audio                                            | 36        | 3.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 32        | 3.15%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 28        | 2.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 26        | 2.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 26        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 26        | 2.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 25        | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21        | 2.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 20        | 1.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 20        | 1.97%   |
| Intel Comet Lake PCH-LP cAVS                                               | 19        | 1.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 1.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 17        | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 17        | 1.67%   |
| Intel 200 Series PCH HD Audio                                              | 17        | 1.67%   |
| AMD Starship/Matisse HD Audio Controller                                   | 17        | 1.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16        | 1.57%   |
| Nvidia GP106 High Definition Audio Controller                              | 12        | 1.18%   |
| Nvidia GA102 High Definition Audio Controller                              | 11        | 1.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 11        | 1.08%   |
| Intel Alder Lake-S HD Audio Controller                                     | 11        | 1.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 0.98%   |
| Intel Comet Lake PCH cAVS                                                  | 10        | 0.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 0.98%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 0.98%   |
| AMD FCH Azalia Controller                                                  | 10        | 0.98%   |
| Nvidia High Definition Audio Controller                                    | 9         | 0.88%   |
| Nvidia GA106 High Definition Audio Controller                              | 9         | 0.88%   |
| Intel Raptor Lake High Definition Audio Controller                         | 9         | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 8         | 0.79%   |
| ASUSTek Computer USB Audio                                                 | 8         | 0.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 0.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 0.69%   |
| Intel CM238 HD Audio Controller                                            | 7         | 0.69%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7         | 0.69%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 217       | 53.58%  |
| SK hynix                   | 66        | 16.3%   |
| Micron Technology          | 30        | 7.41%   |
| Unknown                    | 17        | 4.2%    |
| Unknown                    | 10        | 2.47%   |
| Kingston                   | 9         | 2.22%   |
| Team                       | 7         | 1.73%   |
| Crucial                    | 7         | 1.73%   |
| KLEVV                      | 5         | 1.23%   |
| G.Skill                    | 5         | 1.23%   |
| A-DATA Technology          | 5         | 1.23%   |
| Elpida                     | 3         | 0.74%   |
| Unknown (ABCD)             | 2         | 0.49%   |
| Ramaxel Technology         | 2         | 0.49%   |
| PUSKILL                    | 2         | 0.49%   |
| NOT SUPPORT                | 2         | 0.49%   |
| Imation                    | 2         | 0.49%   |
| Unknown (899D)             | 1         | 0.25%   |
| Unknown (09D5)             | 1         | 0.25%   |
| Transcend                  | 1         | 0.25%   |
| Silicon Power              | 1         | 0.25%   |
| Shenzhen Jinge Information | 1         | 0.25%   |
| PNY                        | 1         | 0.25%   |
| Nanya Technology           | 1         | 0.25%   |
| HPE                        | 1         | 0.25%   |
| Hewlett-Packard            | 1         | 0.25%   |
| GeIL                       | 1         | 0.25%   |
| Essencore Limited          | 1         | 0.25%   |
| Essencore                  | 1         | 0.25%   |
| Corsair                    | 1         | 0.25%   |
| Apacer                     | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown                                                             | 10        | 2.26%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 9         | 2.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 8         | 1.81%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s                | 8         | 1.81%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s                 | 7         | 1.58%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 6         | 1.35%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 5         | 1.13%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 5         | 1.13%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 1.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 5         | 1.13%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s                | 5         | 1.13%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                    | 4         | 0.9%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 0.9%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 0.9%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.9%    |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s      | 4         | 0.9%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 4         | 0.9%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 0.9%    |
| Samsung RAM M471A1G44AB0-CTD 8GB DDR4 2667MT/s                      | 4         | 0.9%    |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s                 | 4         | 0.9%    |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s        | 4         | 0.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 0.68%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 3         | 0.68%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 0.68%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.68%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 3         | 0.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 0.68%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.68%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 3         | 0.68%   |
| Samsung RAM M378B5273EB0-CK0 8GB DIMM DDR3 1800MT/s                 | 3         | 0.68%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s                 | 3         | 0.68%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s              | 3         | 0.68%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s                | 3         | 0.68%   |
| Samsung RAM M378A2K43EB1-CWE 16GB DIMM DDR4 3933MT/s                | 3         | 0.68%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s                 | 3         | 0.68%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s                 | 3         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 204       | 55.59%  |
| DDR3    | 70        | 19.07%  |
| DDR5    | 23        | 6.27%   |
| LPDDR4  | 21        | 5.72%   |
| LPDDR5  | 20        | 5.45%   |
| LPDDR3  | 14        | 3.81%   |
| DDR2    | 5         | 1.36%   |
| Unknown | 5         | 1.36%   |
| SDRAM   | 4         | 1.09%   |
| DRAM    | 1         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 169       | 45.19%  |
| DIMM         | 130       | 34.76%  |
| Row Of Chips | 66        | 17.65%  |
| Unknown      | 7         | 1.87%   |
| Chip         | 2         | 0.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 156       | 39.49%  |
| 16384 | 81        | 20.51%  |
| 4096  | 81        | 20.51%  |
| 32768 | 40        | 10.13%  |
| 2048  | 26        | 6.58%   |
| 1024  | 5         | 1.27%   |
| 65536 | 2         | 0.51%   |
| 49152 | 2         | 0.51%   |
| 24576 | 1         | 0.25%   |
| 3072  | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 95        | 23.93%  |
| 2667    | 56        | 14.11%  |
| 1600    | 47        | 11.84%  |
| 2400    | 25        | 6.3%    |
| 2133    | 22        | 5.54%   |
| 6400    | 18        | 4.53%   |
| 4800    | 14        | 3.53%   |
| 4267    | 14        | 3.53%   |
| 3266    | 11        | 2.77%   |
| 1867    | 8         | 2.02%   |
| 5600    | 7         | 1.76%   |
| 3500    | 7         | 1.76%   |
| 1334    | 6         | 1.51%   |
| 1333    | 6         | 1.51%   |
| 8400    | 5         | 1.26%   |
| 2666    | 5         | 1.26%   |
| 3466    | 4         | 1.01%   |
| 3066    | 4         | 1.01%   |
| 1800    | 4         | 1.01%   |
| 7500    | 3         | 0.76%   |
| 3933    | 3         | 0.76%   |
| 3400    | 3         | 0.76%   |
| 3000    | 3         | 0.76%   |
| 1866    | 3         | 0.76%   |
| 1066    | 3         | 0.76%   |
| Unknown | 3         | 0.76%   |
| 4266    | 2         | 0.5%    |
| 2933    | 2         | 0.5%    |
| 1067    | 2         | 0.5%    |
| 800     | 2         | 0.5%    |
| 667     | 2         | 0.5%    |
| 8600    | 1         | 0.25%   |
| 7467    | 1         | 0.25%   |
| 5200    | 1         | 0.25%   |
| 4802    | 1         | 0.25%   |
| 4199    | 1         | 0.25%   |
| 4000    | 1         | 0.25%   |
| 3733    | 1         | 0.25%   |
| 2048    | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 5         | 38.46%  |
| Samsung Electronics | 3         | 23.08%  |
| Seiko Epson         | 2         | 15.38%  |
| Hewlett-Packard     | 2         | 15.38%  |
| Brother Industries  | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson L360 Series    | 1         | 7.69%   |
| Seiko Epson ET-4850 Series | 1         | 7.69%   |
| Samsung M203x Series       | 1         | 7.69%   |
| Samsung M2020 Series       | 1         | 7.69%   |
| Samsung CLX-3180 Series    | 1         | 7.69%   |
| HP OfficeJet 4650 series   | 1         | 7.69%   |
| HP HP LaserJet M14-M17     | 1         | 7.69%   |
| Canon PIXMA MP280          | 1         | 7.69%   |
| Canon PIXMA MG3000 series  | 1         | 7.69%   |
| Canon MF4800 Series        | 1         | 7.69%   |
| Canon G4010 series         | 1         | 7.69%   |
| Canon E560 series          | 1         | 7.69%   |
| Brother DCP-T310           | 1         | 7.69%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 56        | 17.13%  |
| IMC Networks                           | 45        | 13.76%  |
| Bison Electronics                      | 23        | 7.03%   |
| Realtek Semiconductor                  | 19        | 5.81%   |
| Microdia                               | 19        | 5.81%   |
| Silicon Motion                         | 17        | 5.2%    |
| Quanta                                 | 17        | 5.2%    |
| Sunplus Innovation Technology          | 13        | 3.98%   |
| Shenzhen Kingcome Optoelectronic       | 13        | 3.98%   |
| Syntek                                 | 11        | 3.36%   |
| Apple                                  | 11        | 3.36%   |
| SunplusIT                              | 8         | 2.45%   |
| Logitech                               | 8         | 2.45%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.45%   |
| Luxvisions Innotech Limited            | 7         | 2.14%   |
| Acer                                   | 7         | 2.14%   |
| Suyin                                  | 5         | 1.53%   |
| Z-Star Microelectronics                | 3         | 0.92%   |
| Sonix Technology                       | 3         | 0.92%   |
| Samsung Electronics                    | 3         | 0.92%   |
| lihappe8                               | 3         | 0.92%   |
| LG Electronics                         | 3         | 0.92%   |
| Sony                                   | 2         | 0.61%   |
| Microsoft                              | 2         | 0.61%   |
| Lenovo                                 | 2         | 0.61%   |
| DigiTech                               | 2         | 0.61%   |
| Canon                                  | 2         | 0.61%   |
| Alcor Micro                            | 2         | 0.61%   |
| Trust                                  | 1         | 0.31%   |
| Teslong Camera                         | 1         | 0.31%   |
| Telmax Communications                  | 1         | 0.31%   |
| Shinetech                              | 1         | 0.31%   |
| OmniVision Technologies                | 1         | 0.31%   |
| Goodong Industry                       | 1         | 0.31%   |
| Genesys Logic                          | 1         | 0.31%   |
| GEMBIRD                                | 1         | 0.31%   |
| DRFCB0ABIHX4E3                         | 1         | 0.31%   |
| Cubeternet                             | 1         | 0.31%   |
| ARC International                      | 1         | 0.31%   |
| Anchor Chips                           | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 17        | 5.12%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 16        | 4.82%   |
| IMC Networks Integrated Camera                          | 14        | 4.22%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera         | 13        | 3.92%   |
| Bison Integrated Camera                                 | 11        | 3.31%   |
| Microdia Integrated_Webcam_HD                           | 9         | 2.71%   |
| Syntek Integrated Camera                                | 8         | 2.41%   |
| Realtek LG Camera                                       | 6         | 1.81%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 6         | 1.81%   |
| Chicony HD Webcam                                       | 6         | 1.81%   |
| Silicon Motion LG HD WebCam                             | 5         | 1.51%   |
| Chicony LG Camera                                       | 4         | 1.2%    |
| Bison HD Webcam                                         | 4         | 1.2%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 4         | 1.2%    |
| Suyin HP Truevision HD                                  | 3         | 0.9%    |
| SunplusIT 720p HD Camera                                | 3         | 0.9%    |
| SunplusIT 1080p FHD Camera                              | 3         | 0.9%    |
| Samsung Galaxy series, misc. (MTP mode)                 | 3         | 0.9%    |
| Realtek Integrated_Webcam_HD                            | 3         | 0.9%    |
| Quanta HP TrueVision HD Camera                          | 3         | 0.9%    |
| Logitech C922 Pro Stream Webcam                         | 3         | 0.9%    |
| lihappe8 USB 2.0 Camera                                 | 3         | 0.9%    |
| Chicony USB 2.0 Camera                                  | 3         | 0.9%    |
| Chicony LG HD WebCam                                    | 3         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 3         | 0.9%    |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 0.9%    |
| Apple Built-in iSight                                   | 3         | 0.9%    |
| Z-Star Webcam                                           | 2         | 0.6%    |
| Syntek Lenovo EasyCamera                                | 2         | 0.6%    |
| Sunplus DICOTA 4K                                       | 2         | 0.6%    |
| Sunplus 1080p FHD Camera                                | 2         | 0.6%    |
| Sony ILCE-7S                                            | 2         | 0.6%    |
| Silicon Motion WebCam SC-10HDP12631N                    | 2         | 0.6%    |
| Silicon Motion 720p HD Camera                           | 2         | 0.6%    |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.6%    |
| Quanta USB HD Webcam                                    | 2         | 0.6%    |
| Quanta LGE Camera                                       | 2         | 0.6%    |
| Quanta LG Webcam                                        | 2         | 0.6%    |
| Quanta HP Wide Vision HD Camera                         | 2         | 0.6%    |
| Quanta HP Webcam                                        | 2         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 29        | 34.52%  |
| Validity Sensors                   | 14        | 16.67%  |
| Samsung Electronics                | 14        | 16.67%  |
| Shenzhen Goodix Technology         | 8         | 9.52%   |
| Realtek USB2.0 Finger Print Bridge | 6         | 7.14%   |
| Upek                               | 4         | 4.76%   |
| Elan Microelectronics              | 4         | 4.76%   |
| STMicroelectronics                 | 2         | 2.38%   |
| LighTuning Technology              | 2         | 2.38%   |
| AuthenTec                          | 1         | 1.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung Fingerprint Sensor Device - 730B                        | 9         | 10.71%  |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 6         | 7.14%   |
| Synaptics WBDI                                                  | 5         | 5.95%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 5         | 5.95%   |
| Samsung Fingerprint Device                                      | 5         | 5.95%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 4.76%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 4         | 4.76%   |
| Shenzhen Goodix  FingerPrint Device                             | 4         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                              | 4         | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 3         | 3.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 3         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 3         | 3.57%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 3         | 3.57%   |
| Elan ELAN:ARM-M4                                                | 3         | 3.57%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 2.38%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 2         | 2.38%   |
| Synaptics UWP WBDI Device                                       | 2         | 2.38%   |
| Synaptics Prometheus Fingerprint Reader                         | 2         | 2.38%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 2.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 2.38%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 1         | 1.19%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 1.19%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 1.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.19%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 1.19%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.19%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.19%   |
| Synaptics WBDI Device                                           | 1         | 1.19%   |
| Synaptics Fingerprint reader [HP G6]                            | 1         | 1.19%   |
| Elan ELAN:Fingerprint                                           | 1         | 1.19%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 1.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
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


| Model                                                                        | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 432       | 66.67%  |
| 1     | 162       | 25%     |
| 2     | 36        | 5.56%   |
| 3     | 8         | 1.23%   |
| 4     | 5         | 0.77%   |
| 5     | 3         | 0.46%   |
| 6     | 2         | 0.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 84        | 30.11%  |
| Graphics card            | 67        | 24.01%  |
| Net/wireless             | 34        | 12.19%  |
| Multimedia controller    | 20        | 7.17%   |
| Unassigned class         | 18        | 6.45%   |
| Communication controller | 17        | 6.09%   |
| Chipcard                 | 9         | 3.23%   |
| Sound                    | 8         | 2.87%   |
| Net/ethernet             | 7         | 2.51%   |
| Camera                   | 7         | 2.51%   |
| Bluetooth                | 4         | 1.43%   |
| Network                  | 3         | 1.08%   |
| Storage/raid             | 1         | 0.36%   |

