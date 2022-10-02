OpenMandriva - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

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

Total: 4300

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 1545               | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| Itautec       | Infoway a7420               | [bb52fe66cf](https://linux-hardware.org/?probe=bb52fe66cf) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| ASUSTek       | UX303UB                     | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [68b0c0ca1a](https://linux-hardware.org/?probe=68b0c0ca1a) | Oct 01, 2022 |
| ASUSTek       | K53SM                       | [f05f33fa9b](https://linux-hardware.org/?probe=f05f33fa9b) | Oct 01, 2022 |
| HP            | Pavilion dv2700             | [0da9fb0afd](https://linux-hardware.org/?probe=0da9fb0afd) | Oct 01, 2022 |
| Dell          | Inspiron 3451               | [aee33639b9](https://linux-hardware.org/?probe=aee33639b9) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [24aefc4138](https://linux-hardware.org/?probe=24aefc4138) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | [646f4ffa8e](https://linux-hardware.org/?probe=646f4ffa8e) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| Dell          | Inspiron 11-3162            | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| Dell          | Latitude E6520              | [04817b4ceb](https://linux-hardware.org/?probe=04817b4ceb) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |
| Dell          | Latitude 3310               | [3c4874fa51](https://linux-hardware.org/?probe=3c4874fa51) | Sep 30, 2022 |
| HP            | Laptop 15-bs0xx             | [7ed786bee9](https://linux-hardware.org/?probe=7ed786bee9) | Sep 30, 2022 |
| HP            | 250 G5 Notebook PC          | [26961d1b30](https://linux-hardware.org/?probe=26961d1b30) | Sep 29, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| Toshiba       | Satellite L505              | [3e91e2bfaf](https://linux-hardware.org/?probe=3e91e2bfaf) | Sep 29, 2022 |
| Dell          | Latitude D531               | [331cad8b98](https://linux-hardware.org/?probe=331cad8b98) | Sep 29, 2022 |
| HP            | Laptop 14s-fq1xxx           | [3990ec6cb0](https://linux-hardware.org/?probe=3990ec6cb0) | Sep 29, 2022 |
| HP            | Compaq 6720s                | [ddb5163310](https://linux-hardware.org/?probe=ddb5163310) | Sep 29, 2022 |
| Apple         | MacBook7,1                  | [88d57c6319](https://linux-hardware.org/?probe=88d57c6319) | Sep 29, 2022 |
| Dell          | Inspiron 15-3552            | [9414d73ae0](https://linux-hardware.org/?probe=9414d73ae0) | Sep 29, 2022 |
| Dell          | XPS 13 9360                 | [6f1ecca2f0](https://linux-hardware.org/?probe=6f1ecca2f0) | Sep 28, 2022 |
| Dell          | Latitude 3310               | [c21a321dce](https://linux-hardware.org/?probe=c21a321dce) | Sep 28, 2022 |
| Dell          | Inspiron 5558               | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Dell          | Vostro 5391                 | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| Toshiba       | dynabook T653/46JR          | [9a613eaf66](https://linux-hardware.org/?probe=9a613eaf66) | Sep 28, 2022 |
| Sony          | VPCEH1S1R                   | [5214bb023f](https://linux-hardware.org/?probe=5214bb023f) | Sep 27, 2022 |
| Dell          | Latitude 3300               | [365349d964](https://linux-hardware.org/?probe=365349d964) | Sep 27, 2022 |
| Dell          | Latitude 3310               | [313ab64584](https://linux-hardware.org/?probe=313ab64584) | Sep 27, 2022 |
| Toshiba       | Satellite C850-1LK          | [f0240dcb2d](https://linux-hardware.org/?probe=f0240dcb2d) | Sep 27, 2022 |
| Lenovo        | IdeaPad Z580                | [a33ab40c8b](https://linux-hardware.org/?probe=a33ab40c8b) | Sep 27, 2022 |
| Positivo      | SW6H                        | [4cfa6665bb](https://linux-hardware.org/?probe=4cfa6665bb) | Sep 27, 2022 |
| Packard Be... | EasyNote LS44SB             | [184a0768bd](https://linux-hardware.org/?probe=184a0768bd) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [898f9bf963](https://linux-hardware.org/?probe=898f9bf963) | Sep 26, 2022 |
| Dell          | Latitude 3420               | [ee7c1fce66](https://linux-hardware.org/?probe=ee7c1fce66) | Sep 26, 2022 |
| Dell          | Latitude 3310               | [0f1fb4687f](https://linux-hardware.org/?probe=0f1fb4687f) | Sep 26, 2022 |
| Dell          | Latitude 3310               | [a6ce17cd6b](https://linux-hardware.org/?probe=a6ce17cd6b) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Dell          | Latitude 3310               | [87af9a8980](https://linux-hardware.org/?probe=87af9a8980) | Sep 26, 2022 |
| Dell          | Latitude E5250              | [e4ffe3583d](https://linux-hardware.org/?probe=e4ffe3583d) | Sep 26, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [07554a7a2b](https://linux-hardware.org/?probe=07554a7a2b) | Sep 25, 2022 |
| HP            | Laptop 17-by3xxx            | [41db205ec7](https://linux-hardware.org/?probe=41db205ec7) | Sep 25, 2022 |
| Acer          | Aspire A315-51              | [21121aa007](https://linux-hardware.org/?probe=21121aa007) | Sep 25, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | [6c2b4ce4b1](https://linux-hardware.org/?probe=6c2b4ce4b1) | Sep 25, 2022 |
| HP            | 250 G5 Notebook PC          | [6c6ae30eba](https://linux-hardware.org/?probe=6c6ae30eba) | Sep 24, 2022 |
| HP            | Pavilion 15                 | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| Dell          | Inspiron 3721               | [7411a700cf](https://linux-hardware.org/?probe=7411a700cf) | Sep 24, 2022 |
| HP            | Laptop 17-cp0xxx            | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Dell          | Latitude 3310               | [4c5dc33267](https://linux-hardware.org/?probe=4c5dc33267) | Sep 23, 2022 |
| Apple         | MacBook4,1                  | [69a66aefdd](https://linux-hardware.org/?probe=69a66aefdd) | Sep 23, 2022 |
| Dell          | Latitude 7480               | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [2b37d81d4c](https://linux-hardware.org/?probe=2b37d81d4c) | Sep 22, 2022 |
| HP            | ProBook 450 G1              | [2527dc6ea0](https://linux-hardware.org/?probe=2527dc6ea0) | Sep 22, 2022 |
| Acer          | Nitro AN515-31              | [9b451feb14](https://linux-hardware.org/?probe=9b451feb14) | Sep 22, 2022 |
| HP            | Compaq 15                   | [345fe48777](https://linux-hardware.org/?probe=345fe48777) | Sep 22, 2022 |
| Lenovo        | ThinkPad X200s 7470WWD      | [268aa65de3](https://linux-hardware.org/?probe=268aa65de3) | Sep 22, 2022 |
| ASUSTek       | K70AD                       | [49dff3ffb5](https://linux-hardware.org/?probe=49dff3ffb5) | Sep 22, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [c1edc96aa7](https://linux-hardware.org/?probe=c1edc96aa7) | Sep 21, 2022 |
| ASUSTek       | X441BA                      | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| Toshiba       | dynabook T653/46JR          | [ee93820bdf](https://linux-hardware.org/?probe=ee93820bdf) | Sep 21, 2022 |
| Dell          | G5 5505                     | [82017aa2ae](https://linux-hardware.org/?probe=82017aa2ae) | Sep 21, 2022 |
| ASUSTek       | UX303LAB                    | [2165b4b046](https://linux-hardware.org/?probe=2165b4b046) | Sep 20, 2022 |
| Dell          | XPS 9320                    | [cd57903024](https://linux-hardware.org/?probe=cd57903024) | Sep 20, 2022 |
| Dell          | Precision M3800             | [2d5d8707dd](https://linux-hardware.org/?probe=2d5d8707dd) | Sep 20, 2022 |
| Acer          | Aspire A315-23              | [dd730980b1](https://linux-hardware.org/?probe=dd730980b1) | Sep 20, 2022 |
| Acer          | Aspire V3-471               | [b04cc2ea05](https://linux-hardware.org/?probe=b04cc2ea05) | Sep 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8003baae8c](https://linux-hardware.org/?probe=8003baae8c) | Sep 19, 2022 |
| Acer          | Nitro AN515-31              | [33e582251a](https://linux-hardware.org/?probe=33e582251a) | Sep 19, 2022 |
| Lenovo        | G50-80 80R0                 | [f04ed15344](https://linux-hardware.org/?probe=f04ed15344) | Sep 19, 2022 |
| Samsung       | R530/R730                   | [0d4e13e70f](https://linux-hardware.org/?probe=0d4e13e70f) | Sep 19, 2022 |
| Dell          | Latitude 3310               | [0e1784b38d](https://linux-hardware.org/?probe=0e1784b38d) | Sep 19, 2022 |
| Dell          | Latitude 3310               | [55332651e0](https://linux-hardware.org/?probe=55332651e0) | Sep 19, 2022 |
| Dell          | Latitude 3120               | [558e95141d](https://linux-hardware.org/?probe=558e95141d) | Sep 19, 2022 |
| Toshiba       | PORTEGE Z30-A               | [419bf72e22](https://linux-hardware.org/?probe=419bf72e22) | Sep 19, 2022 |
| Dell          | Latitude 3300               | [a2513a9849](https://linux-hardware.org/?probe=a2513a9849) | Sep 19, 2022 |
| HP            | Laptop 15-ef2xxx            | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| Positivo      | C14CR21                     | [e72ef2677b](https://linux-hardware.org/?probe=e72ef2677b) | Sep 19, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | [892c3fb361](https://linux-hardware.org/?probe=892c3fb361) | Sep 18, 2022 |
| HP            | EliteBook 2740p             | [6643773237](https://linux-hardware.org/?probe=6643773237) | Sep 18, 2022 |
| NEC Comput... | PC-VK26MXZCE                | [db8f5e4181](https://linux-hardware.org/?probe=db8f5e4181) | Sep 18, 2022 |
| ASUSTek       | X510UQ                      | [eb619ed1c5](https://linux-hardware.org/?probe=eb619ed1c5) | Sep 18, 2022 |
| Dell          | Vostro 3500                 | [08bd4157a3](https://linux-hardware.org/?probe=08bd4157a3) | Sep 18, 2022 |
| Lenovo        | ThinkPad T430 23501M2       | [b9503c9c28](https://linux-hardware.org/?probe=b9503c9c28) | Sep 18, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [65c4f113d8](https://linux-hardware.org/?probe=65c4f113d8) | Sep 18, 2022 |
| HP            | ProBook 6470b               | [3821322b95](https://linux-hardware.org/?probe=3821322b95) | Sep 18, 2022 |
| HP            | Notebook                    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | B50-45 20388                | [d55d9fad24](https://linux-hardware.org/?probe=d55d9fad24) | Sep 17, 2022 |
| Lenovo        | ThinkPad E570 20H5009NUS    | [c64258edc0](https://linux-hardware.org/?probe=c64258edc0) | Sep 17, 2022 |
| Dell          | Latitude 7390               | [64c9b13553](https://linux-hardware.org/?probe=64c9b13553) | Sep 17, 2022 |
| Toshiba       | TECRA S10                   | [602d81b7c5](https://linux-hardware.org/?probe=602d81b7c5) | Sep 17, 2022 |
| NEC Comput... | PC-VY21AEZ75                | [a24d79ffc2](https://linux-hardware.org/?probe=a24d79ffc2) | Sep 17, 2022 |
| Toshiba       | Satellite P845T             | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| Dell          | Precision 7720              | [9658507a0b](https://linux-hardware.org/?probe=9658507a0b) | Sep 17, 2022 |
| HP            | Laptop 15-ef0xxx            | [19d0260ef6](https://linux-hardware.org/?probe=19d0260ef6) | Sep 17, 2022 |
| HP            | 255 G5 Notebook PC          | [6d8f7ffe97](https://linux-hardware.org/?probe=6d8f7ffe97) | Sep 17, 2022 |
| Toshiba       | dynabook T653/46JR          | [7f9cf09305](https://linux-hardware.org/?probe=7f9cf09305) | Sep 17, 2022 |
| Dell          | Latitude 5290 2-in-1        | [21620af2bb](https://linux-hardware.org/?probe=21620af2bb) | Sep 16, 2022 |
| Apple         | MacBook6,1                  | [93b43e5bb5](https://linux-hardware.org/?probe=93b43e5bb5) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Valve         | Jupiter                     | [d5464b13f9](https://linux-hardware.org/?probe=d5464b13f9) | Sep 16, 2022 |
| HP            | Compaq Presario CQ50        | [41dcd9ffc4](https://linux-hardware.org/?probe=41dcd9ffc4) | Sep 16, 2022 |
| Dell          | Inspiron 3451               | [fcdfa43a37](https://linux-hardware.org/?probe=fcdfa43a37) | Sep 15, 2022 |
| Chuwi         | HeroBook Pro                | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| Lenovo        | IdeaPad Y570 20091          | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Lenovo        | ThinkPad T530 2429F33       | [790a0f2a25](https://linux-hardware.org/?probe=790a0f2a25) | Sep 14, 2022 |
| Lenovo        | V330-15IKB 81AX             | [0a91582802](https://linux-hardware.org/?probe=0a91582802) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Dell          | Inspiron 14-3467            | [e92b56817a](https://linux-hardware.org/?probe=e92b56817a) | Sep 14, 2022 |
| Dell          | Latitude E7470              | [9d15a7c8a2](https://linux-hardware.org/?probe=9d15a7c8a2) | Sep 14, 2022 |
| Toshiba       | Satellite C660              | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| Dell          | Inspiron 5584               | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Timi          | TM1612                      | [536fc04dcb](https://linux-hardware.org/?probe=536fc04dcb) | Sep 14, 2022 |
| Lenovo        | ThinkPad X230 2324GA1       | [c4e6cc1489](https://linux-hardware.org/?probe=c4e6cc1489) | Sep 14, 2022 |
| Toshiba       | Satellite L55-B             | [b593ff9e20](https://linux-hardware.org/?probe=b593ff9e20) | Sep 14, 2022 |
| HP            | Notebook                    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| Dell          | Inspiron 3451               | [f06aa45765](https://linux-hardware.org/?probe=f06aa45765) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| Compal        | NCL60/61                    | [f1f5499af8](https://linux-hardware.org/?probe=f1f5499af8) | Sep 12, 2022 |
| Toshiba       | Satellite C655              | [16a4aa3cd8](https://linux-hardware.org/?probe=16a4aa3cd8) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| MSI           | GP73 Leopard 8RE            | [21744558cb](https://linux-hardware.org/?probe=21744558cb) | Sep 12, 2022 |
| HP            | ProBook 440 G1              | [58b48039ce](https://linux-hardware.org/?probe=58b48039ce) | Sep 12, 2022 |
| HP            | Laptop 15-dy2xxx            | [5523f4050c](https://linux-hardware.org/?probe=5523f4050c) | Sep 11, 2022 |
| ASUSTek       | UX31E                       | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| HP            | Notebook                    | [2984aef090](https://linux-hardware.org/?probe=2984aef090) | Sep 11, 2022 |
| ASUSTek       | K46CA                       | [9e730cbd6a](https://linux-hardware.org/?probe=9e730cbd6a) | Sep 11, 2022 |
| HUAWEI        | KPL-W0X                     | [eff4400b7d](https://linux-hardware.org/?probe=eff4400b7d) | Sep 10, 2022 |
| Lenovo        | Unknown                     | [b5842ca017](https://linux-hardware.org/?probe=b5842ca017) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| HP            | Pavilion g6                 | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| LG Electro... | U560-G.BG31P1               | [741c3eddbe](https://linux-hardware.org/?probe=741c3eddbe) | Sep 10, 2022 |
| Samsung       | SX60P                       | [1e0ea8e787](https://linux-hardware.org/?probe=1e0ea8e787) | Sep 09, 2022 |
| Acer          | Aspire E1-572               | [1cfbfd9b91](https://linux-hardware.org/?probe=1cfbfd9b91) | Sep 09, 2022 |
| Dell          | Precision 7560              | [3e2d1a120c](https://linux-hardware.org/?probe=3e2d1a120c) | Sep 09, 2022 |
| Dell          | Latitude E4300              | [634c1467f8](https://linux-hardware.org/?probe=634c1467f8) | Sep 09, 2022 |
| Acer          | Aspire 5738                 | [5c21c2acc6](https://linux-hardware.org/?probe=5c21c2acc6) | Sep 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [628d805267](https://linux-hardware.org/?probe=628d805267) | Sep 09, 2022 |
| Positivo      | H14BT58                     | [669a466b1c](https://linux-hardware.org/?probe=669a466b1c) | Sep 09, 2022 |
| Lenovo        | IdeaPad S400 20195          | [6bd3292f42](https://linux-hardware.org/?probe=6bd3292f42) | Sep 08, 2022 |
| HP            | Laptop 15-bw0xx             | [2154b21ff3](https://linux-hardware.org/?probe=2154b21ff3) | Sep 08, 2022 |
| ASUSTek       | K53U                        | [d13ff70895](https://linux-hardware.org/?probe=d13ff70895) | Sep 08, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [e3976254ee](https://linux-hardware.org/?probe=e3976254ee) | Sep 08, 2022 |
| Dell          | G5 5505                     | [e26e58afac](https://linux-hardware.org/?probe=e26e58afac) | Sep 08, 2022 |
| Lenovo        | B5400 20278                 | [1c9d752f91](https://linux-hardware.org/?probe=1c9d752f91) | Sep 07, 2022 |
| HP            | Pavilion dv7                | [4a39ae67d5](https://linux-hardware.org/?probe=4a39ae67d5) | Sep 07, 2022 |
| Lenovo        | G580                        | [922ede2a50](https://linux-hardware.org/?probe=922ede2a50) | Sep 07, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [22171cc2a6](https://linux-hardware.org/?probe=22171cc2a6) | Sep 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [14f91e3a08](https://linux-hardware.org/?probe=14f91e3a08) | Sep 07, 2022 |
| Samsung       | RC420/RC520/RC720           | [a6b07acfe5](https://linux-hardware.org/?probe=a6b07acfe5) | Sep 07, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [cf398ae303](https://linux-hardware.org/?probe=cf398ae303) | Sep 07, 2022 |
| HP            | ProBook 430 G1              | [cca59cbb3c](https://linux-hardware.org/?probe=cca59cbb3c) | Sep 07, 2022 |
| Positivo      | Mobile                      | [1378222b07](https://linux-hardware.org/?probe=1378222b07) | Sep 07, 2022 |
| LG Electro... | A530-T.BE76P1               | [46161b573f](https://linux-hardware.org/?probe=46161b573f) | Sep 06, 2022 |
| Lenovo        | ThinkPad Edge E531 68856... | [498682ac13](https://linux-hardware.org/?probe=498682ac13) | Sep 06, 2022 |
| Sony          | VPCSB3X9E                   | [03bd901e4f](https://linux-hardware.org/?probe=03bd901e4f) | Sep 06, 2022 |
| Acer          | TravelMate B118-M           | [614d44ff70](https://linux-hardware.org/?probe=614d44ff70) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4236PNP       | [7c3dc0af20](https://linux-hardware.org/?probe=7c3dc0af20) | Sep 06, 2022 |
| Toshiba       | Satellite C75D-B            | [78e0cb1ca2](https://linux-hardware.org/?probe=78e0cb1ca2) | Sep 06, 2022 |
| Acer          | Aspire 5745                 | [39bc7728ac](https://linux-hardware.org/?probe=39bc7728ac) | Sep 06, 2022 |
| Dell          | Latitude E4300              | [4589ef4489](https://linux-hardware.org/?probe=4589ef4489) | Sep 06, 2022 |
| Lenovo        | B71-80 80RJ                 | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Lenovo        | ThinkPad L440 20ASS11T00    | [526d97c730](https://linux-hardware.org/?probe=526d97c730) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5d61bcd114](https://linux-hardware.org/?probe=5d61bcd114) | Sep 06, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [6f848cd309](https://linux-hardware.org/?probe=6f848cd309) | Sep 06, 2022 |
| Dell          | Vostro 14-5480              | [fb3ae25db8](https://linux-hardware.org/?probe=fb3ae25db8) | Sep 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [5263a99ed8](https://linux-hardware.org/?probe=5263a99ed8) | Sep 05, 2022 |
| Dell          | Latitude E6220              | [af87786838](https://linux-hardware.org/?probe=af87786838) | Sep 05, 2022 |
| Lenovo        | ThinkPad T530 2429W4Y       | [572b46f025](https://linux-hardware.org/?probe=572b46f025) | Sep 05, 2022 |
| Lenovo        | ThinkPad T470 20HD005GUS    | [af984a6d00](https://linux-hardware.org/?probe=af984a6d00) | Sep 05, 2022 |
| ASUSTek       | K53BY                       | [efbc2be1a7](https://linux-hardware.org/?probe=efbc2be1a7) | Sep 05, 2022 |
| HP            | ProBook 450 G1              | [d9a3103936](https://linux-hardware.org/?probe=d9a3103936) | Sep 05, 2022 |
| Toshiba       | Satellite C55-A-157         | [483a0f4f49](https://linux-hardware.org/?probe=483a0f4f49) | Sep 05, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [a783dcd3ca](https://linux-hardware.org/?probe=a783dcd3ca) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| HP            | OMEN by Laptop 17-cb1xxx    | [f0a6826f9d](https://linux-hardware.org/?probe=f0a6826f9d) | Sep 05, 2022 |
| Acer          | Aspire S5-371               | [ed31a97b57](https://linux-hardware.org/?probe=ed31a97b57) | Sep 05, 2022 |
| ASUSTek       | X45C                        | [7267b251b6](https://linux-hardware.org/?probe=7267b251b6) | Sep 05, 2022 |
| Apple         | MacBookPro8,1               | [113f737135](https://linux-hardware.org/?probe=113f737135) | Sep 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [96d17dc188](https://linux-hardware.org/?probe=96d17dc188) | Sep 04, 2022 |
| ASUSTek       | X540LA                      | [3ba0635033](https://linux-hardware.org/?probe=3ba0635033) | Sep 04, 2022 |
| MSI           | MS-168B                     | [a0a6645eef](https://linux-hardware.org/?probe=a0a6645eef) | Sep 04, 2022 |
| Jumper        | EZbook                      | [d67fae436c](https://linux-hardware.org/?probe=d67fae436c) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d7c3304983](https://linux-hardware.org/?probe=d7c3304983) | Sep 04, 2022 |
| Toshiba       | dynabook T653/46JR          | [adfeeb4193](https://linux-hardware.org/?probe=adfeeb4193) | Sep 04, 2022 |
| Samsung       | 300E5M/300E5L               | [3d542c8484](https://linux-hardware.org/?probe=3d542c8484) | Sep 03, 2022 |
| Sony          | VGN-FZ31Z                   | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Acer          | Extensa 5635ZG              | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| HP            | Compaq Presario CQ60        | [c2251f33ef](https://linux-hardware.org/?probe=c2251f33ef) | Sep 03, 2022 |
| HP            | 620                         | [34002dc814](https://linux-hardware.org/?probe=34002dc814) | Sep 02, 2022 |
| ASUSTek       | UX31E                       | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| UMAX          | VisionBook 14Wr Plus        | [6a2cb26049](https://linux-hardware.org/?probe=6a2cb26049) | Sep 02, 2022 |
| Getac         | B300-X                      | [927b99c2e0](https://linux-hardware.org/?probe=927b99c2e0) | Sep 02, 2022 |
| Toshiba       | Satellite C660              | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| Dell          | Latitude 3120               | [8716f564d8](https://linux-hardware.org/?probe=8716f564d8) | Sep 02, 2022 |
| HP            | Laptop 17-by4xxx            | [b9502cc4a9](https://linux-hardware.org/?probe=b9502cc4a9) | Sep 02, 2022 |
| HP            | Laptop 15-ef1xxx            | [d27c20dcf9](https://linux-hardware.org/?probe=d27c20dcf9) | Sep 01, 2022 |
| Packard Be... | DOT S                       | [b5b03f1cf7](https://linux-hardware.org/?probe=b5b03f1cf7) | Sep 01, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [7b6028e52d](https://linux-hardware.org/?probe=7b6028e52d) | Sep 01, 2022 |
| Acer          | Aspire 5715Z                | [82086ce1c6](https://linux-hardware.org/?probe=82086ce1c6) | Sep 01, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [c83430605e](https://linux-hardware.org/?probe=c83430605e) | Sep 01, 2022 |
| HP            | ZBook 17 G2                 | [e2fc506c38](https://linux-hardware.org/?probe=e2fc506c38) | Sep 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| Dell          | Latitude 3190               | [d30269b33c](https://linux-hardware.org/?probe=d30269b33c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6566bc7d09](https://linux-hardware.org/?probe=6566bc7d09) | Sep 01, 2022 |
| ASUSTek       | X550ZE                      | [187a6feadf](https://linux-hardware.org/?probe=187a6feadf) | Sep 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | [1a173c5ea0](https://linux-hardware.org/?probe=1a173c5ea0) | Sep 01, 2022 |
| HP            | Pavilion g6                 | [cc725d880c](https://linux-hardware.org/?probe=cc725d880c) | Aug 31, 2022 |
| Apple         | MacBookPro9,2               | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [ad6c7ea5ab](https://linux-hardware.org/?probe=ad6c7ea5ab) | Aug 31, 2022 |
| Dell          | Inspiron 15-3567            | [710d1e9a9b](https://linux-hardware.org/?probe=710d1e9a9b) | Aug 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [b895a2ae7c](https://linux-hardware.org/?probe=b895a2ae7c) | Aug 31, 2022 |
| HP            | Notebook                    | [2ca7fbbfa9](https://linux-hardware.org/?probe=2ca7fbbfa9) | Aug 31, 2022 |
| Dell          | Precision M6400             | [3cf32e24fa](https://linux-hardware.org/?probe=3cf32e24fa) | Aug 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [a2940c76f5](https://linux-hardware.org/?probe=a2940c76f5) | Aug 30, 2022 |
| Dell          | Latitude 3300               | [bea8e53929](https://linux-hardware.org/?probe=bea8e53929) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| Lenovo        | V14-ADA 82C6                | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | [9336d821f8](https://linux-hardware.org/?probe=9336d821f8) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| Dell          | Studio 1735                 | [912f409b37](https://linux-hardware.org/?probe=912f409b37) | Aug 28, 2022 |
| Acer          | Aspire A315-23              | [4c16a58579](https://linux-hardware.org/?probe=4c16a58579) | Aug 28, 2022 |
| HP            | 620                         | [b16c60f4cf](https://linux-hardware.org/?probe=b16c60f4cf) | Aug 28, 2022 |
| Acer          | AO722                       | [377ad8686f](https://linux-hardware.org/?probe=377ad8686f) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [d6c013a669](https://linux-hardware.org/?probe=d6c013a669) | Aug 27, 2022 |
| Toshiba       | dynabook T653/46JR          | [b97366daa0](https://linux-hardware.org/?probe=b97366daa0) | Aug 27, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| Lenovo        | G570 4334                   | [7bea18122c](https://linux-hardware.org/?probe=7bea18122c) | Aug 27, 2022 |
| HP            | 15                          | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [72888e9acb](https://linux-hardware.org/?probe=72888e9acb) | Aug 25, 2022 |
| HP            | Laptop 15-dy2xxx            | [26572efe76](https://linux-hardware.org/?probe=26572efe76) | Aug 25, 2022 |
| HP            | Laptop 14-dk0xxx            | [82da7782ec](https://linux-hardware.org/?probe=82da7782ec) | Aug 25, 2022 |
| HP            | Laptop 15-dy2xxx            | [bcd578a016](https://linux-hardware.org/?probe=bcd578a016) | Aug 25, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | [a7c9d17455](https://linux-hardware.org/?probe=a7c9d17455) | Aug 25, 2022 |
| HP            | Notebook                    | [0d4422145a](https://linux-hardware.org/?probe=0d4422145a) | Aug 25, 2022 |
| HP            | Laptop 15-dy1xxx            | [b201192ebb](https://linux-hardware.org/?probe=b201192ebb) | Aug 25, 2022 |
| Dell          | Latitude E5510              | [c237161d31](https://linux-hardware.org/?probe=c237161d31) | Aug 24, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [f20e68e820](https://linux-hardware.org/?probe=f20e68e820) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | [81b42d221d](https://linux-hardware.org/?probe=81b42d221d) | Aug 24, 2022 |
| Dell          | XPS 13 7390                 | [d609bf3253](https://linux-hardware.org/?probe=d609bf3253) | Aug 24, 2022 |
| Acer          | Aspire A315-54K             | [685d6acc51](https://linux-hardware.org/?probe=685d6acc51) | Aug 23, 2022 |
| Dell          | Latitude E5470              | [4cf5f4680f](https://linux-hardware.org/?probe=4cf5f4680f) | Aug 23, 2022 |
| Google        | Galtic                      | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Acer          | Enduro EUN314-51WG          | [aa9ea3d520](https://linux-hardware.org/?probe=aa9ea3d520) | Aug 22, 2022 |
| Acer          | TravelMate 5760             | [3d9c208d81](https://linux-hardware.org/?probe=3d9c208d81) | Aug 22, 2022 |
| Dell          | Latitude 3300               | [e8b139ecad](https://linux-hardware.org/?probe=e8b139ecad) | Aug 22, 2022 |
| Dell          | Latitude 3310               | [dedda1b96c](https://linux-hardware.org/?probe=dedda1b96c) | Aug 22, 2022 |
| Acer          | TravelMate 5730             | [ec6fd6cddb](https://linux-hardware.org/?probe=ec6fd6cddb) | Aug 22, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [8c7493d7d1](https://linux-hardware.org/?probe=8c7493d7d1) | Aug 22, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | [fdbec5aab2](https://linux-hardware.org/?probe=fdbec5aab2) | Aug 22, 2022 |
| Fujitsu       | LIFEBOOK UH552              | [15a1f49654](https://linux-hardware.org/?probe=15a1f49654) | Aug 21, 2022 |
| Acer          | AO725                       | [5eed64f77d](https://linux-hardware.org/?probe=5eed64f77d) | Aug 21, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| Acer          | Predator G9-791             | [782f581f0b](https://linux-hardware.org/?probe=782f581f0b) | Aug 21, 2022 |
| ASUSTek       | UX31E                       | [84ed4c9d73](https://linux-hardware.org/?probe=84ed4c9d73) | Aug 20, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [ee75702cd5](https://linux-hardware.org/?probe=ee75702cd5) | Aug 20, 2022 |
| HP            | Pavilion dv6                | [0aae35eb95](https://linux-hardware.org/?probe=0aae35eb95) | Aug 19, 2022 |
| HP            | 15                          | [d519e672ca](https://linux-hardware.org/?probe=d519e672ca) | Aug 19, 2022 |
| HP            | Pavilion dm4                | [46bb1c7064](https://linux-hardware.org/?probe=46bb1c7064) | Aug 19, 2022 |
| Dell          | XPS 13 9360                 | [74b0bedd54](https://linux-hardware.org/?probe=74b0bedd54) | Aug 19, 2022 |
| Dell          | Latitude E5430 non-vPro     | [ac7fb69037](https://linux-hardware.org/?probe=ac7fb69037) | Aug 19, 2022 |
| HP            | ProBook 440 G1              | [eb86fd2237](https://linux-hardware.org/?probe=eb86fd2237) | Aug 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c954da96ad](https://linux-hardware.org/?probe=c954da96ad) | Aug 18, 2022 |
| ASUSTek       | X75A1                       | [870fcf0f3c](https://linux-hardware.org/?probe=870fcf0f3c) | Aug 18, 2022 |
| Acer          | Aspire 7750G                | [6110ab7d79](https://linux-hardware.org/?probe=6110ab7d79) | Aug 18, 2022 |
| Dell          | Latitude E5510              | [c7defb71d5](https://linux-hardware.org/?probe=c7defb71d5) | Aug 18, 2022 |
| Medion        | Akoya E6418 MD99620         | [6817b38103](https://linux-hardware.org/?probe=6817b38103) | Aug 18, 2022 |
| Acer          | Aspire A515-51G             | [d29438c201](https://linux-hardware.org/?probe=d29438c201) | Aug 18, 2022 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [d78fb85708](https://linux-hardware.org/?probe=d78fb85708) | Aug 18, 2022 |
| Toshiba       | dynabook T653/46JR          | [decfecaa20](https://linux-hardware.org/?probe=decfecaa20) | Aug 18, 2022 |
| Positivo B... | S14SL03                     | [558f5a2f24](https://linux-hardware.org/?probe=558f5a2f24) | Aug 18, 2022 |
| Packard Be... | EasyNote TK37               | [996a14d9f4](https://linux-hardware.org/?probe=996a14d9f4) | Aug 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [93b2d066d6](https://linux-hardware.org/?probe=93b2d066d6) | Aug 17, 2022 |
| Acer          | Nitro AN515-31              | [471659ffff](https://linux-hardware.org/?probe=471659ffff) | Aug 17, 2022 |
| Dell          | Latitude 3380               | [a99b3cef26](https://linux-hardware.org/?probe=a99b3cef26) | Aug 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [9bdceca056](https://linux-hardware.org/?probe=9bdceca056) | Aug 17, 2022 |
| ASUSTek       | N75SF                       | [3b6f89e145](https://linux-hardware.org/?probe=3b6f89e145) | Aug 17, 2022 |
| NEC Comput... | PC-LJ730MG6W                | [c0e6c7edb7](https://linux-hardware.org/?probe=c0e6c7edb7) | Aug 17, 2022 |
| Dell          | Latitude 3310               | [92f66bf3aa](https://linux-hardware.org/?probe=92f66bf3aa) | Aug 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [59080cc039](https://linux-hardware.org/?probe=59080cc039) | Aug 17, 2022 |
| ASUSTek       | Z550SA                      | [03ef043fd9](https://linux-hardware.org/?probe=03ef043fd9) | Aug 17, 2022 |
| HP            | Laptop 14s-fq1xxx           | [92c0a6fe2a](https://linux-hardware.org/?probe=92c0a6fe2a) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [a880d764be](https://linux-hardware.org/?probe=a880d764be) | Aug 16, 2022 |
| Lenovo        | ThinkPad L412 0585A84       | [637fa23dca](https://linux-hardware.org/?probe=637fa23dca) | Aug 16, 2022 |
| Dell          | Latitude 3310               | [1694bfcea7](https://linux-hardware.org/?probe=1694bfcea7) | Aug 16, 2022 |
| Packard Be... | EasyNote TE11BZ             | [2a8e801b4e](https://linux-hardware.org/?probe=2a8e801b4e) | Aug 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [b4757c5ff7](https://linux-hardware.org/?probe=b4757c5ff7) | Aug 16, 2022 |
| TUXEDO        | Book BA1510                 | [6d8040e80b](https://linux-hardware.org/?probe=6d8040e80b) | Aug 15, 2022 |
| Acer          | Aspire ES1-532G             | [cf05c858ab](https://linux-hardware.org/?probe=cf05c858ab) | Aug 15, 2022 |
| Dell          | Latitude E6430              | [6c31827147](https://linux-hardware.org/?probe=6c31827147) | Aug 15, 2022 |
| Dell          | Inspiron 1501               | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| HP            | Notebook                    | [975f3e38e3](https://linux-hardware.org/?probe=975f3e38e3) | Aug 15, 2022 |
| Samsung       | NC210/NC110                 | [3dcdc1dc6a](https://linux-hardware.org/?probe=3dcdc1dc6a) | Aug 15, 2022 |
| HP            | Laptop 14-bs1xx             | [4b603b6b08](https://linux-hardware.org/?probe=4b603b6b08) | Aug 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [4b1440875b](https://linux-hardware.org/?probe=4b1440875b) | Aug 14, 2022 |
| ASUSTek       | X540LA                      | [15ffff65c0](https://linux-hardware.org/?probe=15ffff65c0) | Aug 14, 2022 |
| HP            | ProBook 4330s               | [62ff6ffc08](https://linux-hardware.org/?probe=62ff6ffc08) | Aug 14, 2022 |
| Acer          | Aspire M5-581T              | [7efdb0e467](https://linux-hardware.org/?probe=7efdb0e467) | Aug 14, 2022 |
| Acer          | Aspire A515-54G             | [e9c64a8a5c](https://linux-hardware.org/?probe=e9c64a8a5c) | Aug 14, 2022 |
| Acer          | Aspire 5680                 | [20c2c97a69](https://linux-hardware.org/?probe=20c2c97a69) | Aug 14, 2022 |
| Acer          | Aspire VN7-571G             | [0d6dfdd6e0](https://linux-hardware.org/?probe=0d6dfdd6e0) | Aug 14, 2022 |
| HP            | Pavilion dv9500             | [fd3bd18049](https://linux-hardware.org/?probe=fd3bd18049) | Aug 14, 2022 |
| Toshiba       | Satellite P200              | [83fcabac55](https://linux-hardware.org/?probe=83fcabac55) | Aug 13, 2022 |
| Dell          | Vostro 1520                 | [9dab88f3ee](https://linux-hardware.org/?probe=9dab88f3ee) | Aug 13, 2022 |
| Positivo      | EC10IS1                     | [b66cd42f99](https://linux-hardware.org/?probe=b66cd42f99) | Aug 13, 2022 |
| HP            | Unknown                     | [7375604d06](https://linux-hardware.org/?probe=7375604d06) | Aug 13, 2022 |
| Toshiba       | Satellite L500              | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| Positivo      | Mobile                      | [bddf3b59d4](https://linux-hardware.org/?probe=bddf3b59d4) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T61 64665DG        | [ff1be50f8c](https://linux-hardware.org/?probe=ff1be50f8c) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| Fujitsu       | LIFEBOOK S904               | [0e3107a650](https://linux-hardware.org/?probe=0e3107a650) | Aug 12, 2022 |
| ASUSTek       | K73BR                       | [67f5d3f176](https://linux-hardware.org/?probe=67f5d3f176) | Aug 12, 2022 |
| Acer          | Aspire 4330 V1.22           | [dee8895134](https://linux-hardware.org/?probe=dee8895134) | Aug 12, 2022 |
| HP            | EliteBook 820 G3            | [c1b14847f1](https://linux-hardware.org/?probe=c1b14847f1) | Aug 12, 2022 |
| Dell          | Latitude 7420               | [26cd6bbb87](https://linux-hardware.org/?probe=26cd6bbb87) | Aug 12, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [d949d71a19](https://linux-hardware.org/?probe=d949d71a19) | Aug 12, 2022 |
| Lenovo        | Unknown                     | [79688945e1](https://linux-hardware.org/?probe=79688945e1) | Aug 11, 2022 |
| Gateway       | MT6723                      | [368de1c083](https://linux-hardware.org/?probe=368de1c083) | Aug 11, 2022 |
| Dell          | G5 5505                     | [cbbcb7c9a2](https://linux-hardware.org/?probe=cbbcb7c9a2) | Aug 11, 2022 |
| Dell          | Vostro 3401                 | [29f3354492](https://linux-hardware.org/?probe=29f3354492) | Aug 11, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [cac00fb432](https://linux-hardware.org/?probe=cac00fb432) | Aug 11, 2022 |
| HP            | Pavilion dm3                | [7152a48ede](https://linux-hardware.org/?probe=7152a48ede) | Aug 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| HP            | 240 G3                      | [77225815d2](https://linux-hardware.org/?probe=77225815d2) | Aug 10, 2022 |
| HUAWEI        | BOHB-WAX9                   | [9d55b54de7](https://linux-hardware.org/?probe=9d55b54de7) | Aug 10, 2022 |
| HP            | Laptop 17-ca1xxx            | [f57b28ff2c](https://linux-hardware.org/?probe=f57b28ff2c) | Aug 10, 2022 |
| HP            | Pavilion HDX9200            | [079cb2197b](https://linux-hardware.org/?probe=079cb2197b) | Aug 10, 2022 |
| Compaq        | Presario CQ-31              | [d22794a255](https://linux-hardware.org/?probe=d22794a255) | Aug 09, 2022 |
| Toshiba       | Satellite A300              | [4f83e69c06](https://linux-hardware.org/?probe=4f83e69c06) | Aug 09, 2022 |
| Sony          | VPCYB3V1E                   | [a6cd208cf2](https://linux-hardware.org/?probe=a6cd208cf2) | Aug 09, 2022 |
| HP            | 630                         | [fc9bc69e9a](https://linux-hardware.org/?probe=fc9bc69e9a) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9d6be5eb68](https://linux-hardware.org/?probe=9d6be5eb68) | Aug 08, 2022 |
| Acer          | Nitro AN515-31              | [0dbab56588](https://linux-hardware.org/?probe=0dbab56588) | Aug 08, 2022 |
| HP            | 15                          | [ef66e0296e](https://linux-hardware.org/?probe=ef66e0296e) | Aug 08, 2022 |
| HP            | ProBook 430 G4              | [616a031820](https://linux-hardware.org/?probe=616a031820) | Aug 08, 2022 |
| Dell          | Latitude E7240              | [1f20b0f54b](https://linux-hardware.org/?probe=1f20b0f54b) | Aug 08, 2022 |
| ASUSTek       | X550CL                      | [83626d765b](https://linux-hardware.org/?probe=83626d765b) | Aug 08, 2022 |
| Dell          | Latitude E6420              | [3817e724ac](https://linux-hardware.org/?probe=3817e724ac) | Aug 08, 2022 |
| HP            | Compaq 15                   | [de4b6e0511](https://linux-hardware.org/?probe=de4b6e0511) | Aug 07, 2022 |
| ASUSTek       | X555LA                      | [0a98c50d83](https://linux-hardware.org/?probe=0a98c50d83) | Aug 07, 2022 |
| Apple         | MacBookPro9,2               | [85dc12b4d1](https://linux-hardware.org/?probe=85dc12b4d1) | Aug 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b85ec0e551](https://linux-hardware.org/?probe=b85ec0e551) | Aug 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f9850e0a1e](https://linux-hardware.org/?probe=f9850e0a1e) | Aug 07, 2022 |
| Timi          | RedmiBook Pro 15S           | [4e36acba35](https://linux-hardware.org/?probe=4e36acba35) | Aug 07, 2022 |
| Dell          | Latitude 3189               | [63c2818521](https://linux-hardware.org/?probe=63c2818521) | Aug 07, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [810a9d1c2c](https://linux-hardware.org/?probe=810a9d1c2c) | Aug 07, 2022 |
| MSI           | GL75 Leopard 10SDK          | [bfceb8ba35](https://linux-hardware.org/?probe=bfceb8ba35) | Aug 07, 2022 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | [f3a36d0f3a](https://linux-hardware.org/?probe=f3a36d0f3a) | Aug 07, 2022 |
| Acer          | Swift SF114-31              | [b1cba472dc](https://linux-hardware.org/?probe=b1cba472dc) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430s 2356LNG      | [255560d675](https://linux-hardware.org/?probe=255560d675) | Aug 06, 2022 |
| ASUSTek       | X555LN                      | [77092711a0](https://linux-hardware.org/?probe=77092711a0) | Aug 06, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [6b1d79046a](https://linux-hardware.org/?probe=6b1d79046a) | Aug 06, 2022 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [2577ffae50](https://linux-hardware.org/?probe=2577ffae50) | Aug 06, 2022 |
| ASUSTek       | UX303UA                     | [73145490fa](https://linux-hardware.org/?probe=73145490fa) | Aug 06, 2022 |
| Dell          | Latitude E6540              | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [b9a68ae76c](https://linux-hardware.org/?probe=b9a68ae76c) | Aug 06, 2022 |
| Lenovo        | ThinkPad R500 27148UG       | [1b7557ac14](https://linux-hardware.org/?probe=1b7557ac14) | Aug 05, 2022 |
| Acer          | E1-510                      | [05ea3ff386](https://linux-hardware.org/?probe=05ea3ff386) | Aug 05, 2022 |
| Dell          | Latitude 3310               | [97ac18f196](https://linux-hardware.org/?probe=97ac18f196) | Aug 05, 2022 |
| Lenovo        | G50-30 80G0                 | [2cd0131bb6](https://linux-hardware.org/?probe=2cd0131bb6) | Aug 05, 2022 |
| Dell          | Latitude 3410               | [8181c3588f](https://linux-hardware.org/?probe=8181c3588f) | Aug 05, 2022 |
| Dell          | Precision M4700             | [25efd53898](https://linux-hardware.org/?probe=25efd53898) | Aug 05, 2022 |
| Compaq        | 430                         | [581a8bbf00](https://linux-hardware.org/?probe=581a8bbf00) | Aug 05, 2022 |
| Dell          | Latitude E4310              | [dc6787d2b7](https://linux-hardware.org/?probe=dc6787d2b7) | Aug 05, 2022 |
| HP            | ProBook 6450b               | [699b27e34f](https://linux-hardware.org/?probe=699b27e34f) | Aug 05, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [0a34d32db6](https://linux-hardware.org/?probe=0a34d32db6) | Aug 05, 2022 |
| Lenovo        | ThinkPad X230 2325U9T       | [0f0e8ec24f](https://linux-hardware.org/?probe=0f0e8ec24f) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Dell          | Latitude 3490               | [fa1c5f753f](https://linux-hardware.org/?probe=fa1c5f753f) | Aug 04, 2022 |
| Dell          | Latitude 3310               | [9b9bed6ac6](https://linux-hardware.org/?probe=9b9bed6ac6) | Aug 04, 2022 |
| Dell          | Latitude E6430              | [388b301ced](https://linux-hardware.org/?probe=388b301ced) | Aug 04, 2022 |
| Dell          | Latitude E5470              | [9e78351999](https://linux-hardware.org/?probe=9e78351999) | Aug 04, 2022 |
| Dell          | System Inspiron N4110       | [22938e2e62](https://linux-hardware.org/?probe=22938e2e62) | Aug 03, 2022 |
| Lenovo        | ThinkPad T530 2429W4Z       | [2d95f7cc7e](https://linux-hardware.org/?probe=2d95f7cc7e) | Aug 03, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [f1d5a6ab3f](https://linux-hardware.org/?probe=f1d5a6ab3f) | Aug 03, 2022 |
| ASUSTek       | 1225B                       | [a5fb38b287](https://linux-hardware.org/?probe=a5fb38b287) | Aug 03, 2022 |
| Lenovo        | ThinkPad SL510 28477NG      | [5ddf195177](https://linux-hardware.org/?probe=5ddf195177) | Aug 03, 2022 |
| ASUSTek       | K50IE                       | [0472e4609b](https://linux-hardware.org/?probe=0472e4609b) | Aug 03, 2022 |
| MSI           | GE62VR 7RF                  | [e5f6f7e14c](https://linux-hardware.org/?probe=e5f6f7e14c) | Aug 03, 2022 |
| HP            | Notebook                    | [5320991330](https://linux-hardware.org/?probe=5320991330) | Aug 02, 2022 |
| Lenovo        | ThinkPad T61 76653JG        | [0fae1da16b](https://linux-hardware.org/?probe=0fae1da16b) | Aug 02, 2022 |
| HP            | EliteBook 2570p             | [b352b7e051](https://linux-hardware.org/?probe=b352b7e051) | Aug 02, 2022 |
| Dell          | Latitude E6430              | [15e26c7cc5](https://linux-hardware.org/?probe=15e26c7cc5) | Aug 02, 2022 |
| Dell          | Latitude 3410               | [b2d717d59e](https://linux-hardware.org/?probe=b2d717d59e) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [71c6ba6061](https://linux-hardware.org/?probe=71c6ba6061) | Aug 01, 2022 |
| HP            | Pavilion 15                 | [442aaa6069](https://linux-hardware.org/?probe=442aaa6069) | Aug 01, 2022 |
| Dell          | Latitude E7450              | [38051fe609](https://linux-hardware.org/?probe=38051fe609) | Aug 01, 2022 |
| Toshiba       | Satellite L500              | [21d4b0ac95](https://linux-hardware.org/?probe=21d4b0ac95) | Aug 01, 2022 |
| Packard Be... | EasyNote TK13BZ             | [530d3ad8db](https://linux-hardware.org/?probe=530d3ad8db) | Aug 01, 2022 |
| Apple         | MacBookPro5,5               | [4eeca116f8](https://linux-hardware.org/?probe=4eeca116f8) | Aug 01, 2022 |
| HP            | ProBook 440 G2              | [00dd80ba31](https://linux-hardware.org/?probe=00dd80ba31) | Aug 01, 2022 |
| ASUSTek       | X555LAB                     | [33a1712f4d](https://linux-hardware.org/?probe=33a1712f4d) | Aug 01, 2022 |
| Acer          | Z476                        | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| Toshiba       | Satellite-C845              | [6ee9ea90a5](https://linux-hardware.org/?probe=6ee9ea90a5) | Aug 01, 2022 |
| GPU Compan... | GWNR71517                   | [72278643e8](https://linux-hardware.org/?probe=72278643e8) | Aug 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [6e8a2d15be](https://linux-hardware.org/?probe=6e8a2d15be) | Aug 01, 2022 |
| Acer          | Aspire ES1-523              | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [15382de4bf](https://linux-hardware.org/?probe=15382de4bf) | Aug 01, 2022 |
| Acer          | Aspire E1-571               | [7102c56d5b](https://linux-hardware.org/?probe=7102c56d5b) | Aug 01, 2022 |
| Packard Be... | EasyNote TM85               | [a6df06f9e5](https://linux-hardware.org/?probe=a6df06f9e5) | Jul 31, 2022 |
| Lenovo        | ThinkPad T460 20FMS02R0G    | [0aa31e3c39](https://linux-hardware.org/?probe=0aa31e3c39) | Jul 31, 2022 |
| Acer          | TravelMate B118-M           | [490edd75cf](https://linux-hardware.org/?probe=490edd75cf) | Jul 31, 2022 |
| HP            | ProBook 6570b               | [333a24bdee](https://linux-hardware.org/?probe=333a24bdee) | Jul 31, 2022 |
| Acer          | Aspire VN7-791G             | [3e72040097](https://linux-hardware.org/?probe=3e72040097) | Jul 31, 2022 |
| HP            | Pavilion Notebook           | [f312865dc0](https://linux-hardware.org/?probe=f312865dc0) | Jul 31, 2022 |
| HP            | ProBook 450 G7              | [ebbca00473](https://linux-hardware.org/?probe=ebbca00473) | Jul 31, 2022 |
| HP            | 250 G7 Notebook PC          | [6204ce9d95](https://linux-hardware.org/?probe=6204ce9d95) | Jul 31, 2022 |
| Micro Elec... | MG-VCP17I-3080              | [06191acfe0](https://linux-hardware.org/?probe=06191acfe0) | Jul 31, 2022 |
| HP            | Laptop 15-dy2xxx            | [6fe07f99fd](https://linux-hardware.org/?probe=6fe07f99fd) | Jul 31, 2022 |
| eMachines     | Unknown                     | [8c6dcb08a7](https://linux-hardware.org/?probe=8c6dcb08a7) | Jul 31, 2022 |
| Lenovo        | IdeaPad Z570 1024AMU        | [3d5ec8319b](https://linux-hardware.org/?probe=3d5ec8319b) | Jul 31, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | [7b0b52e138](https://linux-hardware.org/?probe=7b0b52e138) | Jul 31, 2022 |
| Acer          | Nitro AN515-43              | [79117d81e0](https://linux-hardware.org/?probe=79117d81e0) | Jul 31, 2022 |
| Lenovo        | ThinkPad W500 406132U       | [6f403cb15a](https://linux-hardware.org/?probe=6f403cb15a) | Jul 30, 2022 |
| Compaq        | Presario CQ-23              | [76ea82c314](https://linux-hardware.org/?probe=76ea82c314) | Jul 30, 2022 |
| Fujitsu       | LIFEBOOK U727               | [7aa483a43c](https://linux-hardware.org/?probe=7aa483a43c) | Jul 30, 2022 |
| HP            | 250 G2                      | [43d1d3ae24](https://linux-hardware.org/?probe=43d1d3ae24) | Jul 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [34958fdaac](https://linux-hardware.org/?probe=34958fdaac) | Jul 30, 2022 |
| HP            | EliteBook 8470p             | [2171abfd3d](https://linux-hardware.org/?probe=2171abfd3d) | Jul 30, 2022 |
| Apple         | MacBookPro7,1               | [b846739765](https://linux-hardware.org/?probe=b846739765) | Jul 30, 2022 |
| ASUSTek       | K501LX                      | [8ea0c7daa9](https://linux-hardware.org/?probe=8ea0c7daa9) | Jul 30, 2022 |
| HP            | Laptop 15s-eq1xxx           | [ee5c151c3a](https://linux-hardware.org/?probe=ee5c151c3a) | Jul 30, 2022 |
| Lenovo        | IdeaPad Y470 0855           | [395d0c25d7](https://linux-hardware.org/?probe=395d0c25d7) | Jul 30, 2022 |
| ASUSTek       | K53E                        | [3ca340212e](https://linux-hardware.org/?probe=3ca340212e) | Jul 30, 2022 |
| Lenovo        | G570 4334                   | [a29c1c816a](https://linux-hardware.org/?probe=a29c1c816a) | Jul 30, 2022 |
| Fujitsu       | LIFEBOOK V1020              | [e33ac2916d](https://linux-hardware.org/?probe=e33ac2916d) | Jul 30, 2022 |
| Toshiba       | dynabook T653/46JR          | [ea8bb6486b](https://linux-hardware.org/?probe=ea8bb6486b) | Jul 30, 2022 |
| MSI           | GF63 8RD                    | [fdb72c3ec3](https://linux-hardware.org/?probe=fdb72c3ec3) | Jul 29, 2022 |
| Lenovo        | G700 20251                  | [24a9e92897](https://linux-hardware.org/?probe=24a9e92897) | Jul 29, 2022 |
| Acer          | Aspire A317-33              | [ab07e43574](https://linux-hardware.org/?probe=ab07e43574) | Jul 29, 2022 |
| ASUSTek       | K50ID                       | [2c1dddeaea](https://linux-hardware.org/?probe=2c1dddeaea) | Jul 29, 2022 |
| Acer          | Swift SF114-32              | [9e219bd7c2](https://linux-hardware.org/?probe=9e219bd7c2) | Jul 29, 2022 |
| Sony          | VPCEA45FL                   | [8079ec1351](https://linux-hardware.org/?probe=8079ec1351) | Jul 29, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | [5b91ff037d](https://linux-hardware.org/?probe=5b91ff037d) | Jul 29, 2022 |
| HP            | ProBook 6570b               | [231ebd2edc](https://linux-hardware.org/?probe=231ebd2edc) | Jul 29, 2022 |
| Acer          | Aspire 7741                 | [02e9f6a808](https://linux-hardware.org/?probe=02e9f6a808) | Jul 29, 2022 |
| Dell          | Vostro 15-3568              | [a42627d17e](https://linux-hardware.org/?probe=a42627d17e) | Jul 29, 2022 |
| Dell          | Latitude E6410              | [f2220a772e](https://linux-hardware.org/?probe=f2220a772e) | Jul 29, 2022 |
| Lenovo        | ThinkPad S5 Yoga 15 20DR... | [147d305ac1](https://linux-hardware.org/?probe=147d305ac1) | Jul 29, 2022 |
| Lenovo        | ThinkPad X230 23253B3       | [fa19ec3adf](https://linux-hardware.org/?probe=fa19ec3adf) | Jul 29, 2022 |
| Acer          | Aspire A315-51              | [e6f2cdc55e](https://linux-hardware.org/?probe=e6f2cdc55e) | Jul 29, 2022 |
| Gigabyte      | GB-BSi7A-6500               | [048b38a923](https://linux-hardware.org/?probe=048b38a923) | Jul 29, 2022 |
| Google        | Candy                       | [cba2906cfd](https://linux-hardware.org/?probe=cba2906cfd) | Jul 29, 2022 |
| HP            | ProBook 430 G5              | [f424705bd7](https://linux-hardware.org/?probe=f424705bd7) | Jul 29, 2022 |
| Acer          | Aspire 5750                 | [e3f2dd0271](https://linux-hardware.org/?probe=e3f2dd0271) | Jul 29, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [03b39a36f1](https://linux-hardware.org/?probe=03b39a36f1) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4bb1d70cf2](https://linux-hardware.org/?probe=4bb1d70cf2) | Jul 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [46bb82fece](https://linux-hardware.org/?probe=46bb82fece) | Jul 29, 2022 |
| Dell          | Precision 7510              | [fb6266c1dc](https://linux-hardware.org/?probe=fb6266c1dc) | Jul 29, 2022 |
| Lenovo        | G50-45 80E3                 | [61a6277614](https://linux-hardware.org/?probe=61a6277614) | Jul 28, 2022 |
| ASUSTek       | X551MA                      | [668a02296d](https://linux-hardware.org/?probe=668a02296d) | Jul 28, 2022 |
| HP            | ProBook 4515s               | [b9759d3b5d](https://linux-hardware.org/?probe=b9759d3b5d) | Jul 28, 2022 |
| Dell          | Latitude E6430s             | [356556d83a](https://linux-hardware.org/?probe=356556d83a) | Jul 28, 2022 |
| HP            | 250 G5 Notebook PC          | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| ASUSTek       | K53U                        | [7db28a1538](https://linux-hardware.org/?probe=7db28a1538) | Jul 28, 2022 |
| ASUSTek       | N751JK                      | [ca6cba3420](https://linux-hardware.org/?probe=ca6cba3420) | Jul 28, 2022 |
| Dell          | Latitude E6400              | [1c067a436c](https://linux-hardware.org/?probe=1c067a436c) | Jul 28, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [7356bc9abc](https://linux-hardware.org/?probe=7356bc9abc) | Jul 28, 2022 |
| Acer          | Aspire 3100                 | [26c6af2a55](https://linux-hardware.org/?probe=26c6af2a55) | Jul 28, 2022 |
| Toshiba       | Satellite P50-B-118         | [b46f72c280](https://linux-hardware.org/?probe=b46f72c280) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [057703210a](https://linux-hardware.org/?probe=057703210a) | Jul 28, 2022 |
| Acer          | Aspire 5742                 | [4e2290847d](https://linux-hardware.org/?probe=4e2290847d) | Jul 28, 2022 |
| HP            | 2000                        | [531b786836](https://linux-hardware.org/?probe=531b786836) | Jul 28, 2022 |
| Toshiba       | dynabook B350/22A           | [7a5344db19](https://linux-hardware.org/?probe=7a5344db19) | Jul 28, 2022 |
| HP            | Laptop 17z-ca300            | [e2dd650164](https://linux-hardware.org/?probe=e2dd650164) | Jul 28, 2022 |
| Wortmann      | TERRA_MOBILE_1528P/1748P    | [7bcdc30be3](https://linux-hardware.org/?probe=7bcdc30be3) | Jul 28, 2022 |
| Dell          | Vostro 3550                 | [db7097f5f3](https://linux-hardware.org/?probe=db7097f5f3) | Jul 28, 2022 |
| Toshiba       | Satellite C655              | [2a2e3da71d](https://linux-hardware.org/?probe=2a2e3da71d) | Jul 28, 2022 |
| Digibras      | NH4CU03                     | [bf8a8c589a](https://linux-hardware.org/?probe=bf8a8c589a) | Jul 28, 2022 |
| Acer          | Aspire 5742G                | [e42501aacb](https://linux-hardware.org/?probe=e42501aacb) | Jul 28, 2022 |
| Dell          | Latitude E6540              | [40b854996f](https://linux-hardware.org/?probe=40b854996f) | Jul 28, 2022 |
| ASUSTek       | X555YA                      | [ddd00fbeea](https://linux-hardware.org/?probe=ddd00fbeea) | Jul 28, 2022 |
| Dell          | Inspiron 3421               | [67e0e7d1ba](https://linux-hardware.org/?probe=67e0e7d1ba) | Jul 28, 2022 |
| Positivo      | H14BT58                     | [7f271e5d68](https://linux-hardware.org/?probe=7f271e5d68) | Jul 28, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | [c8edf4d8b4](https://linux-hardware.org/?probe=c8edf4d8b4) | Jul 28, 2022 |
| Dell          | Inspiron 5735               | [76b13b0dc6](https://linux-hardware.org/?probe=76b13b0dc6) | Jul 28, 2022 |
| Toshiba       | Satellite C850D-11K         | [544f2db462](https://linux-hardware.org/?probe=544f2db462) | Jul 28, 2022 |
| Sony          | VPCS110FL                   | [8576955f3c](https://linux-hardware.org/?probe=8576955f3c) | Jul 28, 2022 |
| Dell          | XPS 17 9710                 | [6f5c79f0da](https://linux-hardware.org/?probe=6f5c79f0da) | Jul 27, 2022 |
| LG Electro... | 17Z90Q-K.ADC9U1             | [64635e88c9](https://linux-hardware.org/?probe=64635e88c9) | Jul 27, 2022 |
| ASUSTek       | N76VB                       | [15cea344b9](https://linux-hardware.org/?probe=15cea344b9) | Jul 27, 2022 |
| Dell          | Latitude E6430              | [f04523ef5a](https://linux-hardware.org/?probe=f04523ef5a) | Jul 27, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [5660ecabaa](https://linux-hardware.org/?probe=5660ecabaa) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [94a6b79798](https://linux-hardware.org/?probe=94a6b79798) | Jul 27, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d449f1aeb9](https://linux-hardware.org/?probe=d449f1aeb9) | Jul 27, 2022 |
| Samsung       | 550XBE/350XBE               | [b7fabad758](https://linux-hardware.org/?probe=b7fabad758) | Jul 27, 2022 |
| HP            | Pavilion g7                 | [75fa7f0ce4](https://linux-hardware.org/?probe=75fa7f0ce4) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [e18d9dc7f2](https://linux-hardware.org/?probe=e18d9dc7f2) | Jul 27, 2022 |
| Acer          | Aspire V3-371               | [0da78400c9](https://linux-hardware.org/?probe=0da78400c9) | Jul 27, 2022 |
| Dell          | XPS 13 9300                 | [8f0daaf341](https://linux-hardware.org/?probe=8f0daaf341) | Jul 27, 2022 |
| ASUSTek       | S551LB                      | [8660a06086](https://linux-hardware.org/?probe=8660a06086) | Jul 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [910067609e](https://linux-hardware.org/?probe=910067609e) | Jul 27, 2022 |
| Dell          | Latitude E6330              | [5ee8d985ed](https://linux-hardware.org/?probe=5ee8d985ed) | Jul 27, 2022 |
| Wortmann      | MS-1727                     | [4697b4b4e5](https://linux-hardware.org/?probe=4697b4b4e5) | Jul 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [17f64584bb](https://linux-hardware.org/?probe=17f64584bb) | Jul 27, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b3df887fe1](https://linux-hardware.org/?probe=b3df887fe1) | Jul 27, 2022 |
| HP            | 250 G4 Notebook PC          | [fbe3850683](https://linux-hardware.org/?probe=fbe3850683) | Jul 27, 2022 |
| HP            | Compaq 6720s                | [d8546f791c](https://linux-hardware.org/?probe=d8546f791c) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| Acer          | TravelMate P633-M           | [7d346db799](https://linux-hardware.org/?probe=7d346db799) | Jul 27, 2022 |
| Dell          | Latitude E7250              | [26a8591f1d](https://linux-hardware.org/?probe=26a8591f1d) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [f005e0566d](https://linux-hardware.org/?probe=f005e0566d) | Jul 27, 2022 |
| Lenovo        | ThinkPad T420 4236CTO       | [6797b09b3b](https://linux-hardware.org/?probe=6797b09b3b) | Jul 27, 2022 |
| Apple         | MacBookPro8,1               | [cf1f919243](https://linux-hardware.org/?probe=cf1f919243) | Jul 27, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [44954e91a2](https://linux-hardware.org/?probe=44954e91a2) | Jul 27, 2022 |
| HP            | G62                         | [dd114592c4](https://linux-hardware.org/?probe=dd114592c4) | Jul 27, 2022 |
| Sony          | VPCEB26FG                   | [49c139799c](https://linux-hardware.org/?probe=49c139799c) | Jul 27, 2022 |
| HP            | Compaq Presario CQ60        | [06fe56588b](https://linux-hardware.org/?probe=06fe56588b) | Jul 27, 2022 |
| Dell          | Latitude E7240              | [6af993caf7](https://linux-hardware.org/?probe=6af993caf7) | Jul 27, 2022 |
| Toshiba       | Satellite C870D-116         | [d92af8246c](https://linux-hardware.org/?probe=d92af8246c) | Jul 26, 2022 |
| HP            | ProBook 645 G1              | [457c35707a](https://linux-hardware.org/?probe=457c35707a) | Jul 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [94f1822d11](https://linux-hardware.org/?probe=94f1822d11) | Jul 26, 2022 |
| Acer          | Aspire 3810T                | [92f9c99b5e](https://linux-hardware.org/?probe=92f9c99b5e) | Jul 26, 2022 |
| Acer          | Aspire 5742G                | [5f287317e6](https://linux-hardware.org/?probe=5f287317e6) | Jul 26, 2022 |
| Dell          | Latitude 131L               | [ec8717bc3f](https://linux-hardware.org/?probe=ec8717bc3f) | Jul 26, 2022 |
| Dell          | Latitude 3300               | [64cf4b87d9](https://linux-hardware.org/?probe=64cf4b87d9) | Jul 26, 2022 |
| Dell          | Latitude E6540              | [d5f66c66fa](https://linux-hardware.org/?probe=d5f66c66fa) | Jul 26, 2022 |
| Toshiba       | dynabook R734/K             | [a5e7d4c919](https://linux-hardware.org/?probe=a5e7d4c919) | Jul 26, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [a1605eaae0](https://linux-hardware.org/?probe=a1605eaae0) | Jul 26, 2022 |
| Dell          | Inspiron 13 5310            | [3824fcc8a6](https://linux-hardware.org/?probe=3824fcc8a6) | Jul 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2a9595e780](https://linux-hardware.org/?probe=2a9595e780) | Jul 26, 2022 |
| NEC Comput... | U2                          | [22314f4475](https://linux-hardware.org/?probe=22314f4475) | Jul 25, 2022 |
| Dell          | Vostro 15-3568              | [da71f235a2](https://linux-hardware.org/?probe=da71f235a2) | Jul 25, 2022 |
| HP            | Pavilion Notebook           | [660665c762](https://linux-hardware.org/?probe=660665c762) | Jul 25, 2022 |
| Dell          | Latitude 3310               | [0fe12d0d48](https://linux-hardware.org/?probe=0fe12d0d48) | Jul 25, 2022 |
| Acer          | Aspire 5741G                | [a4f8482423](https://linux-hardware.org/?probe=a4f8482423) | Jul 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [375ba933ba](https://linux-hardware.org/?probe=375ba933ba) | Jul 25, 2022 |
| Lenovo        | G50-45 80E3                 | [e6b9106560](https://linux-hardware.org/?probe=e6b9106560) | Jul 24, 2022 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [93ec0d85ab](https://linux-hardware.org/?probe=93ec0d85ab) | Jul 24, 2022 |
| Toshiba       | Portable PC                 | [00cd85e866](https://linux-hardware.org/?probe=00cd85e866) | Jul 24, 2022 |
| Apple         | MacBookAir9,1               | [cf4d815653](https://linux-hardware.org/?probe=cf4d815653) | Jul 24, 2022 |
| HP            | Notebook                    | [17893fb905](https://linux-hardware.org/?probe=17893fb905) | Jul 24, 2022 |
| ASUSTek       | X455LJ                      | [49af56cbe0](https://linux-hardware.org/?probe=49af56cbe0) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| Dell          | Latitude E6430              | [8bc3b0f962](https://linux-hardware.org/?probe=8bc3b0f962) | Jul 23, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c4c41ad0b5](https://linux-hardware.org/?probe=c4c41ad0b5) | Jul 23, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [acdc35979c](https://linux-hardware.org/?probe=acdc35979c) | Jul 23, 2022 |
| ASUSTek       | UX31E                       | [1ae28afad9](https://linux-hardware.org/?probe=1ae28afad9) | Jul 22, 2022 |
| AZW           | GT-R                        | [eb7604ea1c](https://linux-hardware.org/?probe=eb7604ea1c) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | [fe5dae3d4a](https://linux-hardware.org/?probe=fe5dae3d4a) | Jul 22, 2022 |
| Lenovo        | ThinkPad T61 6458W4B        | [3d51bdb900](https://linux-hardware.org/?probe=3d51bdb900) | Jul 22, 2022 |
| Acer          | Aspire 5738                 | [8b9c2d3dc0](https://linux-hardware.org/?probe=8b9c2d3dc0) | Jul 22, 2022 |
| Lenovo        | ThinkPad Helix 36986EU      | [294d96aff6](https://linux-hardware.org/?probe=294d96aff6) | Jul 22, 2022 |
| Positivo      | J14AL11                     | [7510e905d8](https://linux-hardware.org/?probe=7510e905d8) | Jul 22, 2022 |
| HP            | Notebook                    | [e859de5718](https://linux-hardware.org/?probe=e859de5718) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [bc6103f96b](https://linux-hardware.org/?probe=bc6103f96b) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [abe159e82a](https://linux-hardware.org/?probe=abe159e82a) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [d90f147df3](https://linux-hardware.org/?probe=d90f147df3) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [324b95a49a](https://linux-hardware.org/?probe=324b95a49a) | Jul 21, 2022 |
| METAPHYUNI    | MetamechBook                | [169a9a0636](https://linux-hardware.org/?probe=169a9a0636) | Jul 21, 2022 |
| Sony          | SVE1513R1EB                 | [61c51541dd](https://linux-hardware.org/?probe=61c51541dd) | Jul 21, 2022 |
| Dell          | Latitude E5450              | [c8243bf1a8](https://linux-hardware.org/?probe=c8243bf1a8) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9863a7ed67](https://linux-hardware.org/?probe=9863a7ed67) | Jul 20, 2022 |
| Lenovo        | V130-15IKB 81HN             | [fe2f5a993c](https://linux-hardware.org/?probe=fe2f5a993c) | Jul 20, 2022 |
| Dell          | Latitude 3310               | [086f88be40](https://linux-hardware.org/?probe=086f88be40) | Jul 20, 2022 |
| Dell          | Inspiron 5579               | [52e88ad171](https://linux-hardware.org/?probe=52e88ad171) | Jul 20, 2022 |
| Dell          | Latitude 3310               | [0cb2abc6bc](https://linux-hardware.org/?probe=0cb2abc6bc) | Jul 20, 2022 |
| Dell          | Latitude 3310               | [dbd9b101c2](https://linux-hardware.org/?probe=dbd9b101c2) | Jul 20, 2022 |
| Dell          | Latitude 5285               | [2b46125d79](https://linux-hardware.org/?probe=2b46125d79) | Jul 20, 2022 |
| HP            | Dev One Notebook PC         | [e386bc211b](https://linux-hardware.org/?probe=e386bc211b) | Jul 20, 2022 |
| HP            | Laptop 14-ck0xxx            | [78c2b82b87](https://linux-hardware.org/?probe=78c2b82b87) | Jul 19, 2022 |
| HP            | 250 G6 Notebook PC          | [83d1355e61](https://linux-hardware.org/?probe=83d1355e61) | Jul 19, 2022 |
| Gateway       | NV53A                       | [2674f3160f](https://linux-hardware.org/?probe=2674f3160f) | Jul 19, 2022 |
| Acer          | Aspire A515-51G             | [4414dd4c1b](https://linux-hardware.org/?probe=4414dd4c1b) | Jul 19, 2022 |
| Samsung       | 270E5G/270E5U               | [c26ed846e9](https://linux-hardware.org/?probe=c26ed846e9) | Jul 19, 2022 |
| Acer          | Aspire E3-112               | [475d626fd5](https://linux-hardware.org/?probe=475d626fd5) | Jul 19, 2022 |
| HUAWEI        | MateBook D                  | [5d7a616dd1](https://linux-hardware.org/?probe=5d7a616dd1) | Jul 18, 2022 |
| Acer          | Aspire ES1-411              | [5d551a94bd](https://linux-hardware.org/?probe=5d551a94bd) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [68a78a8ed1](https://linux-hardware.org/?probe=68a78a8ed1) | Jul 18, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [f9f25bbbfe](https://linux-hardware.org/?probe=f9f25bbbfe) | Jul 17, 2022 |
| Teclast       | F15 Plus                    | [6201934176](https://linux-hardware.org/?probe=6201934176) | Jul 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [14d23344e2](https://linux-hardware.org/?probe=14d23344e2) | Jul 17, 2022 |
| HP            | ProBook 4441s               | [b108eaada9](https://linux-hardware.org/?probe=b108eaada9) | Jul 17, 2022 |
| Digibras      | NH4CU03                     | [803b7d3211](https://linux-hardware.org/?probe=803b7d3211) | Jul 16, 2022 |
| Sony          | VPCEA3M1R                   | [0bdfc50874](https://linux-hardware.org/?probe=0bdfc50874) | Jul 16, 2022 |
| Digibras      | NH4CU53                     | [f6b402afe8](https://linux-hardware.org/?probe=f6b402afe8) | Jul 16, 2022 |
| MSI           | GP62 6QE                    | [7e7c05c6b6](https://linux-hardware.org/?probe=7e7c05c6b6) | Jul 16, 2022 |
| Acer          | Nitro AN517-54              | [68f6109054](https://linux-hardware.org/?probe=68f6109054) | Jul 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b511d2883b](https://linux-hardware.org/?probe=b511d2883b) | Jul 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| Sony          | SVE1513H1EW                 | [6e4d66c2ee](https://linux-hardware.org/?probe=6e4d66c2ee) | Jul 15, 2022 |
| HP            | ProBook 4545s               | [12575a32d1](https://linux-hardware.org/?probe=12575a32d1) | Jul 15, 2022 |
| MSI           | GE72 6QL                    | [7c22c38989](https://linux-hardware.org/?probe=7c22c38989) | Jul 15, 2022 |
| Dell          | Latitude E6530              | [67eec0ba19](https://linux-hardware.org/?probe=67eec0ba19) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | [4d653cf4e6](https://linux-hardware.org/?probe=4d653cf4e6) | Jul 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | [7e9ba006f3](https://linux-hardware.org/?probe=7e9ba006f3) | Jul 15, 2022 |
| HP            | Pavilion dv7                | [4065c23b56](https://linux-hardware.org/?probe=4065c23b56) | Jul 15, 2022 |
| HP            | EliteBook 8540p             | [52a3abee65](https://linux-hardware.org/?probe=52a3abee65) | Jul 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [7a661a1449](https://linux-hardware.org/?probe=7a661a1449) | Jul 15, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | [b85cc7c80c](https://linux-hardware.org/?probe=b85cc7c80c) | Jul 14, 2022 |
| HP            | Pavilion dv6700             | [c8bf7e091c](https://linux-hardware.org/?probe=c8bf7e091c) | Jul 14, 2022 |
| HP            | EliteBook 8460p             | [c3f5c82808](https://linux-hardware.org/?probe=c3f5c82808) | Jul 14, 2022 |
| ASUSTek       | UX301LA                     | [3d4655e7cf](https://linux-hardware.org/?probe=3d4655e7cf) | Jul 14, 2022 |
| Purism        | Librem 14                   | [5a0337506b](https://linux-hardware.org/?probe=5a0337506b) | Jul 14, 2022 |
| Notebook      | NL40_50GU                   | [d4e652dc65](https://linux-hardware.org/?probe=d4e652dc65) | Jul 13, 2022 |
| Dell          | Inspiron 3451               | [c95dd7e491](https://linux-hardware.org/?probe=c95dd7e491) | Jul 13, 2022 |
| Toshiba       | Satellite Pro R50-C         | [25d6e4de23](https://linux-hardware.org/?probe=25d6e4de23) | Jul 13, 2022 |
| HP            | Dev One Notebook PC         | [24c64c6221](https://linux-hardware.org/?probe=24c64c6221) | Jul 13, 2022 |
| ASUSTek       | UX31E                       | [004f74eaf4](https://linux-hardware.org/?probe=004f74eaf4) | Jul 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | [1c3c80b88e](https://linux-hardware.org/?probe=1c3c80b88e) | Jul 13, 2022 |
| Dell          | XPS 13 9360                 | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| Acer          | Predator PH315-51           | [37b04a8093](https://linux-hardware.org/?probe=37b04a8093) | Jul 12, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [b0b89af62e](https://linux-hardware.org/?probe=b0b89af62e) | Jul 12, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [bbb311969a](https://linux-hardware.org/?probe=bbb311969a) | Jul 12, 2022 |
| Lenovo        | G575 4383                   | [8bd6296a3e](https://linux-hardware.org/?probe=8bd6296a3e) | Jul 12, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1599e9e013](https://linux-hardware.org/?probe=1599e9e013) | Jul 11, 2022 |
| HP            | Pavilion g4                 | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [d088d6021c](https://linux-hardware.org/?probe=d088d6021c) | Jul 11, 2022 |
| Apple         | MacBookAir3,2               | [e3f89d4d16](https://linux-hardware.org/?probe=e3f89d4d16) | Jul 10, 2022 |
| HP            | Laptop 15-dy1xxx            | [36b1a0480d](https://linux-hardware.org/?probe=36b1a0480d) | Jul 10, 2022 |
| Acer          | Aspire A515-44              | [c0d1086ae8](https://linux-hardware.org/?probe=c0d1086ae8) | Jul 09, 2022 |
| Acer          | Swift SF114-34              | [cf0d8e217c](https://linux-hardware.org/?probe=cf0d8e217c) | Jul 09, 2022 |
| Lenovo        | V15-ADA 82C7                | [3324f369f7](https://linux-hardware.org/?probe=3324f369f7) | Jul 09, 2022 |
| Lenovo        | G40-30 80FY                 | [35d55776f6](https://linux-hardware.org/?probe=35d55776f6) | Jul 09, 2022 |
| Framework     | Laptop                      | [09fa73cc57](https://linux-hardware.org/?probe=09fa73cc57) | Jul 09, 2022 |
| HP            | Pavilion g6                 | [2f0de52d8e](https://linux-hardware.org/?probe=2f0de52d8e) | Jul 08, 2022 |
| Dell          | Vostro 15 3515              | [c6e9a42a66](https://linux-hardware.org/?probe=c6e9a42a66) | Jul 08, 2022 |
| HP            | ProBook 4510s               | [ae51b4e466](https://linux-hardware.org/?probe=ae51b4e466) | Jul 08, 2022 |
| ASUSTek       | S551LN                      | [1e64e5d64e](https://linux-hardware.org/?probe=1e64e5d64e) | Jul 08, 2022 |
| HP            | Notebook                    | [0dc44e8da9](https://linux-hardware.org/?probe=0dc44e8da9) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [4f02f261b3](https://linux-hardware.org/?probe=4f02f261b3) | Jul 08, 2022 |
| Toshiba       | Satellite C75D-B            | [3624ac1024](https://linux-hardware.org/?probe=3624ac1024) | Jul 08, 2022 |
| Acer          | Aspire ES1-512              | [aa2ad87835](https://linux-hardware.org/?probe=aa2ad87835) | Jul 08, 2022 |
| HP            | EliteBook 8460p             | [4f0cf74fe4](https://linux-hardware.org/?probe=4f0cf74fe4) | Jul 07, 2022 |
| HP            | ProBook 4310s               | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| ASUSTek       | GL553VD                     | [6b5e1735a7](https://linux-hardware.org/?probe=6b5e1735a7) | Jul 07, 2022 |
| HP            | G56                         | [5c38722298](https://linux-hardware.org/?probe=5c38722298) | Jul 07, 2022 |
| Acer          | Aspire V3-471               | [75664ddf0f](https://linux-hardware.org/?probe=75664ddf0f) | Jul 07, 2022 |
| Gateway       | NE56R                       | [69f2805432](https://linux-hardware.org/?probe=69f2805432) | Jul 06, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0KE0... | [2d63b4ba76](https://linux-hardware.org/?probe=2d63b4ba76) | Jul 06, 2022 |
| Unknown       | Unknown                     | [e4a8ad0984](https://linux-hardware.org/?probe=e4a8ad0984) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | [498f4edafb](https://linux-hardware.org/?probe=498f4edafb) | Jul 05, 2022 |
| ASUSTek       | K53SC                       | [4f31f807cb](https://linux-hardware.org/?probe=4f31f807cb) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | [1264fab131](https://linux-hardware.org/?probe=1264fab131) | Jul 05, 2022 |
| HP            | Compaq CQ58                 | [d46da7be57](https://linux-hardware.org/?probe=d46da7be57) | Jul 05, 2022 |
| HP            | EliteBook 8570p             | [8782b09be9](https://linux-hardware.org/?probe=8782b09be9) | Jul 05, 2022 |
| Dell          | Inspiron 14-3467            | [b9a61ec06d](https://linux-hardware.org/?probe=b9a61ec06d) | Jul 05, 2022 |
| HP            | Laptop 15-da0xxx            | [5c39c57896](https://linux-hardware.org/?probe=5c39c57896) | Jul 04, 2022 |
| ASUSTek       | GL703VD                     | [dc966787de](https://linux-hardware.org/?probe=dc966787de) | Jul 04, 2022 |
| Sony          | VGN-FZ31Z                   | [62d8b20ff8](https://linux-hardware.org/?probe=62d8b20ff8) | Jul 04, 2022 |
| HP            | Pavilion dv4                | [d40a5bd13e](https://linux-hardware.org/?probe=d40a5bd13e) | Jul 04, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [03bede7266](https://linux-hardware.org/?probe=03bede7266) | Jul 03, 2022 |
| Dell          | Inspiron 3451               | [a57cf9cc46](https://linux-hardware.org/?probe=a57cf9cc46) | Jul 03, 2022 |
| ASUSTek       | X542UA                      | [f5da6492ca](https://linux-hardware.org/?probe=f5da6492ca) | Jul 03, 2022 |
| Dell          | Latitude D630               | [df3001a64d](https://linux-hardware.org/?probe=df3001a64d) | Jul 02, 2022 |
| Notebook      | MIM 2200                    | [85748618b6](https://linux-hardware.org/?probe=85748618b6) | Jul 02, 2022 |
| ASUSTek       | UX31E                       | [7504f06baa](https://linux-hardware.org/?probe=7504f06baa) | Jul 02, 2022 |
| Dell          | Latitude E7450              | [6dc8d46993](https://linux-hardware.org/?probe=6dc8d46993) | Jul 02, 2022 |
| Dell          | Precision M6800             | [ba446bde45](https://linux-hardware.org/?probe=ba446bde45) | Jul 02, 2022 |
| Samsung       | 300E5M/300E5L               | [497939c649](https://linux-hardware.org/?probe=497939c649) | Jul 02, 2022 |
| Samsung       | Q210/P210                   | [dfc97062be](https://linux-hardware.org/?probe=dfc97062be) | Jul 01, 2022 |
| Acer          | Extensa 5220                | [1ee1e31b52](https://linux-hardware.org/?probe=1ee1e31b52) | Jul 01, 2022 |
| ASUSTek       | UX31E                       | [d3f27ab291](https://linux-hardware.org/?probe=d3f27ab291) | Jul 01, 2022 |
| Apple         | MacBookPro8,1               | [88e0a63fab](https://linux-hardware.org/?probe=88e0a63fab) | Jun 30, 2022 |
| Acer          | Aspire 4732Z                | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| Dell          | Precision M6800             | [1eccdbb04e](https://linux-hardware.org/?probe=1eccdbb04e) | Jun 30, 2022 |
| Dell          | Inspiron 3451               | [6cf63ca19e](https://linux-hardware.org/?probe=6cf63ca19e) | Jun 30, 2022 |
| Acer          | Aspire 5735                 | [b930fd3fcd](https://linux-hardware.org/?probe=b930fd3fcd) | Jun 29, 2022 |
| Dell          | Precision M6800             | [5b30cb4b9a](https://linux-hardware.org/?probe=5b30cb4b9a) | Jun 29, 2022 |
| AMI           | Intel                       | [2b592e2f4a](https://linux-hardware.org/?probe=2b592e2f4a) | Jun 29, 2022 |
| HP            | Compaq CQ45                 | [74948790d0](https://linux-hardware.org/?probe=74948790d0) | Jun 29, 2022 |
| Dell          | Precision M6800             | [49b1b7edec](https://linux-hardware.org/?probe=49b1b7edec) | Jun 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ed40a2bae5](https://linux-hardware.org/?probe=ed40a2bae5) | Jun 28, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | [a767fd4cb1](https://linux-hardware.org/?probe=a767fd4cb1) | Jun 28, 2022 |
| HP            | Laptop 14-dk1xxx            | [6932a00eed](https://linux-hardware.org/?probe=6932a00eed) | Jun 28, 2022 |
| Lenovo        | Z40-75 80DW                 | [1fc3b34132](https://linux-hardware.org/?probe=1fc3b34132) | Jun 27, 2022 |
| Acer          | Aspire A515-41G             | [cbb6f48321](https://linux-hardware.org/?probe=cbb6f48321) | Jun 27, 2022 |
| Dell          | Latitude E6430              | [76c22c2645](https://linux-hardware.org/?probe=76c22c2645) | Jun 26, 2022 |
| ASUSTek       | UX31E                       | [a346ece8f5](https://linux-hardware.org/?probe=a346ece8f5) | Jun 26, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [240018e48a](https://linux-hardware.org/?probe=240018e48a) | Jun 26, 2022 |
| Lenovo        | S20-30 Touch 20434          | [b4ebe70967](https://linux-hardware.org/?probe=b4ebe70967) | Jun 26, 2022 |
| Toshiba       | Satellite C855-2CF          | [9e062a8425](https://linux-hardware.org/?probe=9e062a8425) | Jun 26, 2022 |
| HP            | Pavilion dv6700             | [352a224c3f](https://linux-hardware.org/?probe=352a224c3f) | Jun 26, 2022 |
| Toshiba       | Satellite C660D             | [fc25883979](https://linux-hardware.org/?probe=fc25883979) | Jun 25, 2022 |
| ASUSTek       | X555QG                      | [53e208736b](https://linux-hardware.org/?probe=53e208736b) | Jun 25, 2022 |
| ASUSTek       | X551MA                      | [e5780aff8c](https://linux-hardware.org/?probe=e5780aff8c) | Jun 24, 2022 |
| Dell          | Latitude 3420               | [027b943645](https://linux-hardware.org/?probe=027b943645) | Jun 24, 2022 |
| ASUSTek       | N61Vn                       | [72d62f755d](https://linux-hardware.org/?probe=72d62f755d) | Jun 24, 2022 |
| HP            | ZBook 15 G2                 | [cfa8a05299](https://linux-hardware.org/?probe=cfa8a05299) | Jun 23, 2022 |
| Fujitsu       | FMVS02003                   | [3536a9951f](https://linux-hardware.org/?probe=3536a9951f) | Jun 23, 2022 |
| Dell          | Latitude E5570              | [7f3b4b77f7](https://linux-hardware.org/?probe=7f3b4b77f7) | Jun 23, 2022 |
| Shuttle       | DS47D                       | [685a228ad8](https://linux-hardware.org/?probe=685a228ad8) | Jun 23, 2022 |
| Acer          | Aspire E1-531               | [415b93724e](https://linux-hardware.org/?probe=415b93724e) | Jun 22, 2022 |
| Dell          | Latitude 3300               | [5275529516](https://linux-hardware.org/?probe=5275529516) | Jun 22, 2022 |
| HP            | Spectre x2 Detachable       | [f42403915a](https://linux-hardware.org/?probe=f42403915a) | Jun 22, 2022 |
| eMachines     | E527                        | [a987a6cac2](https://linux-hardware.org/?probe=a987a6cac2) | Jun 22, 2022 |
| Dell          | Latitude E7250              | [790850da0b](https://linux-hardware.org/?probe=790850da0b) | Jun 22, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [212cd0ac63](https://linux-hardware.org/?probe=212cd0ac63) | Jun 22, 2022 |
| Dell          | Vostro 15 3515              | [f8a037663f](https://linux-hardware.org/?probe=f8a037663f) | Jun 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8a530af324](https://linux-hardware.org/?probe=8a530af324) | Jun 21, 2022 |
| HP            | Laptop 15-bs1xx             | [11f173103f](https://linux-hardware.org/?probe=11f173103f) | Jun 21, 2022 |
| Acer          | Aspire E5-771G              | [dac3ae2eba](https://linux-hardware.org/?probe=dac3ae2eba) | Jun 21, 2022 |
| Acer          | Extensa 5635ZG              | [d1c48399ae](https://linux-hardware.org/?probe=d1c48399ae) | Jun 20, 2022 |
| Dell          | Latitude 3190               | [14521bc3eb](https://linux-hardware.org/?probe=14521bc3eb) | Jun 20, 2022 |
| HP            | Laptop 17-by4xxx            | [13fd86fd67](https://linux-hardware.org/?probe=13fd86fd67) | Jun 20, 2022 |
| Dell          | Inspiron 3451               | [d9ac6a3f41](https://linux-hardware.org/?probe=d9ac6a3f41) | Jun 19, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [ee2f7822c9](https://linux-hardware.org/?probe=ee2f7822c9) | Jun 18, 2022 |
| Acer          | Swift SF314-41              | [735d7a92b5](https://linux-hardware.org/?probe=735d7a92b5) | Jun 18, 2022 |
| HP            | Laptop 14-fq0xxx            | [bc61209d78](https://linux-hardware.org/?probe=bc61209d78) | Jun 18, 2022 |
| ASUSTek       | N71Vg                       | [6926193d76](https://linux-hardware.org/?probe=6926193d76) | Jun 18, 2022 |
| HP            | Pavilion dv6                | [1ba5e6c491](https://linux-hardware.org/?probe=1ba5e6c491) | Jun 18, 2022 |
| Dell          | Latitude 3380               | [0ccd773de6](https://linux-hardware.org/?probe=0ccd773de6) | Jun 17, 2022 |
| Lenovo        | ThinkPad T460s 20FAS76R0... | [21d6816b13](https://linux-hardware.org/?probe=21d6816b13) | Jun 17, 2022 |
| Dell          | Latitude 3420               | [178e3cbcba](https://linux-hardware.org/?probe=178e3cbcba) | Jun 17, 2022 |
| Dell          | Latitude 3300               | [ed133c13de](https://linux-hardware.org/?probe=ed133c13de) | Jun 17, 2022 |
| Dell          | Latitude 3310               | [4715235090](https://linux-hardware.org/?probe=4715235090) | Jun 17, 2022 |
| Sony          | VGN-NW310F                  | [318b17f951](https://linux-hardware.org/?probe=318b17f951) | Jun 17, 2022 |
| Lenovo        | ThinkPad T60 2007FUG        | [2c1a306677](https://linux-hardware.org/?probe=2c1a306677) | Jun 16, 2022 |
| Acer          | Aspire A515-44              | [5da40d4fd6](https://linux-hardware.org/?probe=5da40d4fd6) | Jun 16, 2022 |
| Dell          | Latitude 3310               | [549b7595b7](https://linux-hardware.org/?probe=549b7595b7) | Jun 16, 2022 |
| ASUSTek       | ET2040I                     | [45273f0675](https://linux-hardware.org/?probe=45273f0675) | Jun 15, 2022 |
| HP            | Pavilion g4                 | [193875edcc](https://linux-hardware.org/?probe=193875edcc) | Jun 15, 2022 |
| Unknown       | Unknown                     | [00090936e8](https://linux-hardware.org/?probe=00090936e8) | Jun 15, 2022 |
| Acer          | Extensa 5220                | [dd0d362582](https://linux-hardware.org/?probe=dd0d362582) | Jun 15, 2022 |
| HP            | Laptop 14-fq0xxx            | [d7cccd8f1d](https://linux-hardware.org/?probe=d7cccd8f1d) | Jun 14, 2022 |
| Dell          | Inspiron 3451               | [7ca7f789d8](https://linux-hardware.org/?probe=7ca7f789d8) | Jun 14, 2022 |
| HP            | Compaq Presario CQ41        | [95ffc69f82](https://linux-hardware.org/?probe=95ffc69f82) | Jun 14, 2022 |
| Acer          | AO722                       | [29c2adc56d](https://linux-hardware.org/?probe=29c2adc56d) | Jun 13, 2022 |
| Dell          | Latitude E5450              | [b8d806d8a4](https://linux-hardware.org/?probe=b8d806d8a4) | Jun 13, 2022 |
| ASUSTek       | N53SV                       | [fa9f250b51](https://linux-hardware.org/?probe=fa9f250b51) | Jun 13, 2022 |
| TUXEDO        | Unknown                     | [c351e553d3](https://linux-hardware.org/?probe=c351e553d3) | Jun 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b65abaf14a](https://linux-hardware.org/?probe=b65abaf14a) | Jun 12, 2022 |
| Dell          | Inspiron N4050              | [32f413134f](https://linux-hardware.org/?probe=32f413134f) | Jun 12, 2022 |
| ASUSTek       | X553MA                      | [1794b92b61](https://linux-hardware.org/?probe=1794b92b61) | Jun 12, 2022 |
| Acer          | Aspire ES1-523              | [89fbabafb5](https://linux-hardware.org/?probe=89fbabafb5) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3910                | [4abeebc707](https://linux-hardware.org/?probe=4abeebc707) | Jun 12, 2022 |
| ASUSTek       | K53BR                       | [b64b9e0f4a](https://linux-hardware.org/?probe=b64b9e0f4a) | Jun 12, 2022 |
| Dell          | Vostro 3500                 | [1eda18f249](https://linux-hardware.org/?probe=1eda18f249) | Jun 12, 2022 |
| HP            | Pavilion dv6                | [0bf35c5293](https://linux-hardware.org/?probe=0bf35c5293) | Jun 11, 2022 |
| Dell          | Latitude E6410              | [184348232a](https://linux-hardware.org/?probe=184348232a) | Jun 11, 2022 |
| HP            | ProBook 450 G0              | [2d87379b89](https://linux-hardware.org/?probe=2d87379b89) | Jun 11, 2022 |
| Acer          | Aspire A515-51G             | [785b725767](https://linux-hardware.org/?probe=785b725767) | Jun 10, 2022 |
| HP            | Laptop 17-bs0xx             | [a4587cc1de](https://linux-hardware.org/?probe=a4587cc1de) | Jun 10, 2022 |
| HUAWEI        | HN-WX9X                     | [d57d295c58](https://linux-hardware.org/?probe=d57d295c58) | Jun 10, 2022 |
| Dell          | Latitude 5290               | [930e34a606](https://linux-hardware.org/?probe=930e34a606) | Jun 10, 2022 |
| HP            | Pavilion g6                 | [63dcba0c57](https://linux-hardware.org/?probe=63dcba0c57) | Jun 10, 2022 |
| Dell          | Latitude E5550              | [95baf2f400](https://linux-hardware.org/?probe=95baf2f400) | Jun 10, 2022 |
| Acer          | AO756                       | [008fa33f13](https://linux-hardware.org/?probe=008fa33f13) | Jun 09, 2022 |
| Dell          | Inspiron 1545               | [7ed42ed0a1](https://linux-hardware.org/?probe=7ed42ed0a1) | Jun 09, 2022 |
| HP            | ProBook 450 G5              | [cec4cb4af4](https://linux-hardware.org/?probe=cec4cb4af4) | Jun 09, 2022 |
| HP            | EliteBook 8570p             | [bd545aec1b](https://linux-hardware.org/?probe=bd545aec1b) | Jun 09, 2022 |
| Dell          | Latitude E5430 non-vPro     | [ff7b51ffc8](https://linux-hardware.org/?probe=ff7b51ffc8) | Jun 08, 2022 |
| ASUSTek       | UX31E                       | [4abfa2a1d0](https://linux-hardware.org/?probe=4abfa2a1d0) | Jun 08, 2022 |
| HP            | ProBook 640 G1              | [34ecb184f9](https://linux-hardware.org/?probe=34ecb184f9) | Jun 08, 2022 |
| Sony          | VGN-Z71JB                   | [95a370d4e4](https://linux-hardware.org/?probe=95a370d4e4) | Jun 08, 2022 |
| Lenovo        | ThinkPad T400 2767AL9       | [8084a9ed95](https://linux-hardware.org/?probe=8084a9ed95) | Jun 08, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c6975f2914](https://linux-hardware.org/?probe=c6975f2914) | Jun 07, 2022 |
| Acer          | Aspire A315-32              | [a610c5537a](https://linux-hardware.org/?probe=a610c5537a) | Jun 07, 2022 |
| LG Electro... | 15Z970-E.BH71P1             | [cc464203ff](https://linux-hardware.org/?probe=cc464203ff) | Jun 07, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4eb8e0924d](https://linux-hardware.org/?probe=4eb8e0924d) | Jun 07, 2022 |
| Dell          | Inspiron 3451               | [a6feb9dcd2](https://linux-hardware.org/?probe=a6feb9dcd2) | Jun 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [039d0b1cdc](https://linux-hardware.org/?probe=039d0b1cdc) | Jun 07, 2022 |
| HP            | Laptop 14-fq0xxx            | [d88feaaf5e](https://linux-hardware.org/?probe=d88feaaf5e) | Jun 06, 2022 |
| Unknown       | Unknown                     | [c0625a957b](https://linux-hardware.org/?probe=c0625a957b) | Jun 06, 2022 |
| DNS           | MB50II1                     | [b4882bff99](https://linux-hardware.org/?probe=b4882bff99) | Jun 06, 2022 |
| HP            | ProBook 4530s               | [0ff1032a69](https://linux-hardware.org/?probe=0ff1032a69) | Jun 06, 2022 |
| Alienware     | 13 R3                       | [1431b0b659](https://linux-hardware.org/?probe=1431b0b659) | Jun 06, 2022 |
| TUXEDO        | Unknown                     | [ef40511693](https://linux-hardware.org/?probe=ef40511693) | Jun 05, 2022 |
| Dell          | Inspiron 15 3511            | [8f0924eb80](https://linux-hardware.org/?probe=8f0924eb80) | Jun 05, 2022 |
| Acer          | Aspire ES1-572              | [9c48d4f977](https://linux-hardware.org/?probe=9c48d4f977) | Jun 05, 2022 |
| AZW           | GT-R                        | [d86ab00f24](https://linux-hardware.org/?probe=d86ab00f24) | Jun 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ff882995b0](https://linux-hardware.org/?probe=ff882995b0) | Jun 05, 2022 |
| Dell          | Latitude D630               | [fb28805860](https://linux-hardware.org/?probe=fb28805860) | Jun 05, 2022 |
| HP            | Pavilion 15                 | [5e4d9a126e](https://linux-hardware.org/?probe=5e4d9a126e) | Jun 05, 2022 |
| Acer          | Aspire A315-32              | [124288f4e9](https://linux-hardware.org/?probe=124288f4e9) | Jun 05, 2022 |
| Dell          | Latitude E7450              | [29219339b2](https://linux-hardware.org/?probe=29219339b2) | Jun 05, 2022 |
| HYPA          | FLUX                        | [76b0337ef8](https://linux-hardware.org/?probe=76b0337ef8) | Jun 05, 2022 |
| Fujitsu       | FMVA0800C                   | [bacd4a55bb](https://linux-hardware.org/?probe=bacd4a55bb) | Jun 05, 2022 |
| HP            | Laptop 14-fq0xxx            | [3ebcdc19fa](https://linux-hardware.org/?probe=3ebcdc19fa) | Jun 04, 2022 |
| Acer          | Swift SF314-41G             | [aad6ae85d1](https://linux-hardware.org/?probe=aad6ae85d1) | Jun 04, 2022 |
| Sony          | VGN-FZ31Z                   | [f9b7b79d5a](https://linux-hardware.org/?probe=f9b7b79d5a) | Jun 04, 2022 |
| Sony          | VPCSB4AFX                   | [b676e37b94](https://linux-hardware.org/?probe=b676e37b94) | Jun 04, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [058bd1f6b9](https://linux-hardware.org/?probe=058bd1f6b9) | Jun 04, 2022 |
| ASUSTek       | UX31E                       | [250825e17e](https://linux-hardware.org/?probe=250825e17e) | Jun 03, 2022 |
| Dell          | Inspiron 5515               | [997f034219](https://linux-hardware.org/?probe=997f034219) | Jun 03, 2022 |
| Dell          | Latitude 3189               | [f1899ceede](https://linux-hardware.org/?probe=f1899ceede) | Jun 03, 2022 |
| Dell          | Inspiron 3451               | [ba5e3a5d77](https://linux-hardware.org/?probe=ba5e3a5d77) | Jun 02, 2022 |
| LG Electro... | 15Z970-E.BH71P1             | [e073539ce5](https://linux-hardware.org/?probe=e073539ce5) | Jun 02, 2022 |
| Acer          | AO722                       | [73850c23ac](https://linux-hardware.org/?probe=73850c23ac) | Jun 02, 2022 |
| LG Electro... | 15Z970-E.BH71P1             | [3b5f142164](https://linux-hardware.org/?probe=3b5f142164) | Jun 02, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [a27fbb040b](https://linux-hardware.org/?probe=a27fbb040b) | Jun 02, 2022 |
| Acer          | AOD260                      | [f5c031faa5](https://linux-hardware.org/?probe=f5c031faa5) | Jun 02, 2022 |
| Dell          | Latitude E6540              | [9cbdc3f892](https://linux-hardware.org/?probe=9cbdc3f892) | Jun 02, 2022 |
| HP            | EliteBook 840 G2            | [8aff04335d](https://linux-hardware.org/?probe=8aff04335d) | Jun 01, 2022 |
| Medion        | E7220                       | [d4a700af57](https://linux-hardware.org/?probe=d4a700af57) | Jun 01, 2022 |
| Dell          | Inspiron 3451               | [04e9ce0ba0](https://linux-hardware.org/?probe=04e9ce0ba0) | Jun 01, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [ee8d9751b0](https://linux-hardware.org/?probe=ee8d9751b0) | Jun 01, 2022 |
| Lenovo        | Yoga 2 11 20332             | [ad92325747](https://linux-hardware.org/?probe=ad92325747) | Jun 01, 2022 |
| Lenovo        | IdeaPad S300 20197          | [fcb07ac9aa](https://linux-hardware.org/?probe=fcb07ac9aa) | May 31, 2022 |
| HYPA          | FLUX                        | [8a69e3a34e](https://linux-hardware.org/?probe=8a69e3a34e) | May 31, 2022 |
| Philco        | 10D                         | [b4fc893791](https://linux-hardware.org/?probe=b4fc893791) | May 31, 2022 |
| Lenovo        | ThinkPad T430 2349BS7       | [2369e183ec](https://linux-hardware.org/?probe=2369e183ec) | May 30, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | [dc9d61a80b](https://linux-hardware.org/?probe=dc9d61a80b) | May 30, 2022 |
| Dell          | Vostro 5468                 | [551400dba1](https://linux-hardware.org/?probe=551400dba1) | May 29, 2022 |
| Dell          | Inspiron 3451               | [8ad9f9f5d9](https://linux-hardware.org/?probe=8ad9f9f5d9) | May 29, 2022 |
| System76      | Lemur Pro                   | [4a6174b7a4](https://linux-hardware.org/?probe=4a6174b7a4) | May 29, 2022 |
| Toshiba       | Satellite C850-1KN          | [60b2c12831](https://linux-hardware.org/?probe=60b2c12831) | May 29, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [8e577a4a1a](https://linux-hardware.org/?probe=8e577a4a1a) | May 29, 2022 |
| AZW           | GT-R                        | [7823df6a86](https://linux-hardware.org/?probe=7823df6a86) | May 29, 2022 |
| ASUSTek       | UX31E                       | [201add5732](https://linux-hardware.org/?probe=201add5732) | May 29, 2022 |
| Acer          | Aspire 4349                 | [3d1051c72e](https://linux-hardware.org/?probe=3d1051c72e) | May 29, 2022 |
| TUXEDO        | Unknown                     | [6bda60151b](https://linux-hardware.org/?probe=6bda60151b) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [d1c3a33e75](https://linux-hardware.org/?probe=d1c3a33e75) | May 28, 2022 |
| Dell          | Inspiron 15-3567            | [ba66fccfa1](https://linux-hardware.org/?probe=ba66fccfa1) | May 28, 2022 |
| Lenovo        | G50-70 20351                | [1150f03cf0](https://linux-hardware.org/?probe=1150f03cf0) | May 28, 2022 |
| ASUSTek       | Strix 17 GL703GE            | [5d5ba64239](https://linux-hardware.org/?probe=5d5ba64239) | May 28, 2022 |
| Dell          | Inspiron 3451               | [798f65546b](https://linux-hardware.org/?probe=798f65546b) | May 27, 2022 |
| HP            | EliteBook 840 G2            | [eeab3d23c4](https://linux-hardware.org/?probe=eeab3d23c4) | May 27, 2022 |
| TUXEDO        | Unknown                     | [2d5566dd3f](https://linux-hardware.org/?probe=2d5566dd3f) | May 27, 2022 |
| Apple         | MacBookPro5,5               | [75eebad111](https://linux-hardware.org/?probe=75eebad111) | May 27, 2022 |
| ASUSTek       | U31Jg                       | [b761173e5e](https://linux-hardware.org/?probe=b761173e5e) | May 26, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [36d7baa56d](https://linux-hardware.org/?probe=36d7baa56d) | May 26, 2022 |
| Dell          | Latitude E5410              | [fcb77d9c00](https://linux-hardware.org/?probe=fcb77d9c00) | May 26, 2022 |
| Acer          | Aspire E5-571               | [b43bf0505e](https://linux-hardware.org/?probe=b43bf0505e) | May 25, 2022 |
| Clevo         | W55xEU                      | [c5fd2417f4](https://linux-hardware.org/?probe=c5fd2417f4) | May 25, 2022 |
| HP            | Pavilion g4                 | [0c943e458a](https://linux-hardware.org/?probe=0c943e458a) | May 25, 2022 |
| ASUSTek       | X540LJ                      | [dbbcdcd2b5](https://linux-hardware.org/?probe=dbbcdcd2b5) | May 25, 2022 |
| Lenovo        | ThinkPad W520 428223G       | [5672a27a7e](https://linux-hardware.org/?probe=5672a27a7e) | May 24, 2022 |
| ASUSTek       | UX31E                       | [3905de150e](https://linux-hardware.org/?probe=3905de150e) | May 24, 2022 |
| HP            | 255 G3                      | [a6e7ea804b](https://linux-hardware.org/?probe=a6e7ea804b) | May 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | [4a88ea0c1f](https://linux-hardware.org/?probe=4a88ea0c1f) | May 24, 2022 |
| HP            | 1000                        | [e83bc1e8fe](https://linux-hardware.org/?probe=e83bc1e8fe) | May 24, 2022 |
| Acer          | Aspire E5-411               | [7c3a3077ff](https://linux-hardware.org/?probe=7c3a3077ff) | May 24, 2022 |
| HP            | Compaq 15                   | [262d99131a](https://linux-hardware.org/?probe=262d99131a) | May 23, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [db944454c8](https://linux-hardware.org/?probe=db944454c8) | May 23, 2022 |
| HP            | ProBook 450 G1              | [0097404cab](https://linux-hardware.org/?probe=0097404cab) | May 23, 2022 |
| HP            | 240 G7                      | [687546391a](https://linux-hardware.org/?probe=687546391a) | May 23, 2022 |
| HP            | ProBook 6475b               | [5202cf8c75](https://linux-hardware.org/?probe=5202cf8c75) | May 23, 2022 |
| Toshiba       | Satellite A100              | [a789d51565](https://linux-hardware.org/?probe=a789d51565) | May 23, 2022 |
| HP            | Laptop 14-dk1xxx            | [f05080d3fd](https://linux-hardware.org/?probe=f05080d3fd) | May 22, 2022 |
| Lenovo        | ThinkPad T61 7661BM5        | [9a6d69d512](https://linux-hardware.org/?probe=9a6d69d512) | May 22, 2022 |
| Acer          | Aspire E1-530               | [48747611a5](https://linux-hardware.org/?probe=48747611a5) | May 22, 2022 |
| MSI           | GF63 Thin 8RCS              | [8cd1ebfa12](https://linux-hardware.org/?probe=8cd1ebfa12) | May 22, 2022 |
| Dell          | Inspiron 3451               | [38c450f343](https://linux-hardware.org/?probe=38c450f343) | May 21, 2022 |
| Dell          | Latitude E6320              | [7f2af32493](https://linux-hardware.org/?probe=7f2af32493) | May 21, 2022 |
| ASUSTek       | UX31E                       | [12407852be](https://linux-hardware.org/?probe=12407852be) | May 21, 2022 |
| Unknown       | Unknown                     | [261a0bf179](https://linux-hardware.org/?probe=261a0bf179) | May 21, 2022 |
| Lenovo        | Z50-75 80EC                 | [adddbe7947](https://linux-hardware.org/?probe=adddbe7947) | May 21, 2022 |
| Lenovo        | G50-70 20351                | [b6f469418c](https://linux-hardware.org/?probe=b6f469418c) | May 21, 2022 |
| Medion        | P6624                       | [ed8bd28269](https://linux-hardware.org/?probe=ed8bd28269) | May 21, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [1c63e5e513](https://linux-hardware.org/?probe=1c63e5e513) | May 21, 2022 |
| Lenovo        | Z710 20250                  | [ce719211e5](https://linux-hardware.org/?probe=ce719211e5) | May 21, 2022 |
| ASUSTek       | F7L                         | [f5bcd583ac](https://linux-hardware.org/?probe=f5bcd583ac) | May 21, 2022 |
| ASUSTek       | K73SD                       | [8c77e10639](https://linux-hardware.org/?probe=8c77e10639) | May 21, 2022 |
| Notebook      | N8xxEP6                     | [ae2202ea9e](https://linux-hardware.org/?probe=ae2202ea9e) | May 21, 2022 |
| ASUSTek       | K42Jc                       | [29538e9e80](https://linux-hardware.org/?probe=29538e9e80) | May 21, 2022 |
| Acer          | Aspire 5332                 | [f48da95c17](https://linux-hardware.org/?probe=f48da95c17) | May 21, 2022 |
| Dell          | Inspiron 3451               | [d14ff2c62e](https://linux-hardware.org/?probe=d14ff2c62e) | May 20, 2022 |
| Acer          | Aspire 7750G                | [0fd6c8569c](https://linux-hardware.org/?probe=0fd6c8569c) | May 20, 2022 |
| Positivo      | S15KL                       | [71fffe977a](https://linux-hardware.org/?probe=71fffe977a) | May 20, 2022 |
| ASUSTek       | TUF Gaming FX705DU_FX705... | [a3e1bf045d](https://linux-hardware.org/?probe=a3e1bf045d) | May 20, 2022 |
| Acer          | Aspire A314-22              | [b476e4fd95](https://linux-hardware.org/?probe=b476e4fd95) | May 20, 2022 |
| Dell          | Inspiron 3502               | [0d26fe46da](https://linux-hardware.org/?probe=0d26fe46da) | May 19, 2022 |
| Dell          | Inspiron 5520               | [0e7bf88677](https://linux-hardware.org/?probe=0e7bf88677) | May 19, 2022 |
| Lenovo        | V15-ADA 82C7                | [b42178398a](https://linux-hardware.org/?probe=b42178398a) | May 19, 2022 |
| Compaq        | Presario CQ-25              | [4412b90950](https://linux-hardware.org/?probe=4412b90950) | May 19, 2022 |
| Dell          | Latitude 7400               | [caf85903ad](https://linux-hardware.org/?probe=caf85903ad) | May 19, 2022 |
| Positivo      | Mobile                      | [1ef43bb988](https://linux-hardware.org/?probe=1ef43bb988) | May 19, 2022 |
| Dell          | Inspiron 3437               | [fcd1a7ae14](https://linux-hardware.org/?probe=fcd1a7ae14) | May 19, 2022 |
| Sony          | VGN-NR32L_S                 | [2709583292](https://linux-hardware.org/?probe=2709583292) | May 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a18c103de9](https://linux-hardware.org/?probe=a18c103de9) | May 18, 2022 |
| ASUSTek       | UX305FA                     | [5ec0821cdf](https://linux-hardware.org/?probe=5ec0821cdf) | May 18, 2022 |
| ASUSTek       | 1015PE                      | [3ca5e4d427](https://linux-hardware.org/?probe=3ca5e4d427) | May 18, 2022 |
| Lenovo        | ThinkPad T61 6463Y3W        | [065aa2538b](https://linux-hardware.org/?probe=065aa2538b) | May 18, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | [3b3d6ba1e3](https://linux-hardware.org/?probe=3b3d6ba1e3) | May 18, 2022 |
| Dell          | Latitude E7450              | [26b07c8dfc](https://linux-hardware.org/?probe=26b07c8dfc) | May 18, 2022 |
| HP            | EliteBook 8570p             | [703787dd00](https://linux-hardware.org/?probe=703787dd00) | May 17, 2022 |
| Toshiba       | Satellite L350D             | [ff1e87338a](https://linux-hardware.org/?probe=ff1e87338a) | May 17, 2022 |
| Dell          | Studio 1555                 | [2f84ca8885](https://linux-hardware.org/?probe=2f84ca8885) | May 17, 2022 |
| Toshiba       | Satellite C850              | [5927aac0b7](https://linux-hardware.org/?probe=5927aac0b7) | May 17, 2022 |
| Dell          | Inspiron 3459               | [b36df0b4df](https://linux-hardware.org/?probe=b36df0b4df) | May 17, 2022 |
| HP            | ENVY Notebook 13-ab0XX      | [26ed58e99a](https://linux-hardware.org/?probe=26ed58e99a) | May 16, 2022 |
| Dell          | Latitude E6400              | [d89696196c](https://linux-hardware.org/?probe=d89696196c) | May 16, 2022 |
| Lenovo        | ThinkPad T530 23594LU       | [cbed91f90e](https://linux-hardware.org/?probe=cbed91f90e) | May 16, 2022 |
| Sony          | VPCCB3S1E                   | [e6451d9a9a](https://linux-hardware.org/?probe=e6451d9a9a) | May 15, 2022 |
| Dell          | Inspiron 1750               | [b37b4cdbbb](https://linux-hardware.org/?probe=b37b4cdbbb) | May 15, 2022 |
| Dell          | Inspiron 3520               | [a045c6d50f](https://linux-hardware.org/?probe=a045c6d50f) | May 15, 2022 |
| Dell          | Inspiron 11-3162            | [d1e811474c](https://linux-hardware.org/?probe=d1e811474c) | May 15, 2022 |
| Fujitsu Si... | LIFEBOOK S7110              | [8586a581d0](https://linux-hardware.org/?probe=8586a581d0) | May 15, 2022 |
| Toshiba       | Satellite C670D-126         | [9df3447b21](https://linux-hardware.org/?probe=9df3447b21) | May 14, 2022 |
| Packard Be... | EasyNote ENTF71BM           | [e8808a770a](https://linux-hardware.org/?probe=e8808a770a) | May 14, 2022 |
| ASUSTek       | UX31E                       | [85613b8729](https://linux-hardware.org/?probe=85613b8729) | May 14, 2022 |
| Lenovo        | ThinkPad T410 2522W6S       | [79cd5bf620](https://linux-hardware.org/?probe=79cd5bf620) | May 14, 2022 |
| Packard Be... | EasyNote MH35               | [f3180b0817](https://linux-hardware.org/?probe=f3180b0817) | May 13, 2022 |
| Dell          | Studio 1558                 | [ccffb59f97](https://linux-hardware.org/?probe=ccffb59f97) | May 13, 2022 |
| ASUSTek       | UX31E                       | [b83f4f894e](https://linux-hardware.org/?probe=b83f4f894e) | May 13, 2022 |
| Dell          | Precision M2800             | [266af2c2b7](https://linux-hardware.org/?probe=266af2c2b7) | May 13, 2022 |
| Lenovo        | B70-80 80MR                 | [73a1a28362](https://linux-hardware.org/?probe=73a1a28362) | May 12, 2022 |
| Lenovo        | ThinkPad T510 43147UG       | [e4f5ef2c77](https://linux-hardware.org/?probe=e4f5ef2c77) | May 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | [ed11a30da0](https://linux-hardware.org/?probe=ed11a30da0) | May 12, 2022 |
| Lenovo        | ThinkPad W530 2463A64       | [f45c19aa6c](https://linux-hardware.org/?probe=f45c19aa6c) | May 11, 2022 |
| Samsung       | R519/R719                   | [8deee99c2d](https://linux-hardware.org/?probe=8deee99c2d) | May 11, 2022 |
| Compaq        | 420                         | [1525a9b616](https://linux-hardware.org/?probe=1525a9b616) | May 10, 2022 |
| Alienware     | 17                          | [b30786ba0e](https://linux-hardware.org/?probe=b30786ba0e) | May 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [ee9f39e915](https://linux-hardware.org/?probe=ee9f39e915) | May 10, 2022 |
| Acer          | AO722                       | [645156f92d](https://linux-hardware.org/?probe=645156f92d) | May 10, 2022 |
| Apple         | MacBookPro7,1               | [e2430a36a4](https://linux-hardware.org/?probe=e2430a36a4) | May 09, 2022 |
| Fujitsu       | FMVNTCAKB                   | [66083f4e27](https://linux-hardware.org/?probe=66083f4e27) | May 09, 2022 |
| HP            | Pavilion Laptop 15-cc0xx    | [324d23305d](https://linux-hardware.org/?probe=324d23305d) | May 09, 2022 |
| Dell          | Latitude E6410              | [0cac068895](https://linux-hardware.org/?probe=0cac068895) | May 08, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [877b9a8dea](https://linux-hardware.org/?probe=877b9a8dea) | May 08, 2022 |
| Dell          | Latitude E6220              | [f5ba7cbb31](https://linux-hardware.org/?probe=f5ba7cbb31) | May 08, 2022 |
| Lenovo        | ThinkPad T530 24296G9       | [934e13a24c](https://linux-hardware.org/?probe=934e13a24c) | May 08, 2022 |
| ASUSTek       | N501VW                      | [71d02059fa](https://linux-hardware.org/?probe=71d02059fa) | May 06, 2022 |
| Dell          | Latitude 3120               | [0da044ae6c](https://linux-hardware.org/?probe=0da044ae6c) | May 06, 2022 |
| Packard Be... | EasyNote TS44HR             | [2eff4001dc](https://linux-hardware.org/?probe=2eff4001dc) | May 06, 2022 |
| HP            | Compaq 15                   | [25db1ef15f](https://linux-hardware.org/?probe=25db1ef15f) | May 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a49301cdaf](https://linux-hardware.org/?probe=a49301cdaf) | May 05, 2022 |
| Toshiba       | Satellite C670D             | [3eedd8ce6b](https://linux-hardware.org/?probe=3eedd8ce6b) | May 05, 2022 |
| ASUSTek       | X551MA                      | [4a12d6b5d9](https://linux-hardware.org/?probe=4a12d6b5d9) | May 05, 2022 |
| Dell          | Latitude E7440              | [8496c35f54](https://linux-hardware.org/?probe=8496c35f54) | May 05, 2022 |
| Lenovo        | V110-15ISK 80TL             | [d9436bb9f5](https://linux-hardware.org/?probe=d9436bb9f5) | May 05, 2022 |
| Apple         | MacBookAir7,2               | [c08ef3e666](https://linux-hardware.org/?probe=c08ef3e666) | May 04, 2022 |
| HP            | ProBook 470 G0              | [17a1e97761](https://linux-hardware.org/?probe=17a1e97761) | May 04, 2022 |
| ASUSTek       | X75A1                       | [78e4325ae6](https://linux-hardware.org/?probe=78e4325ae6) | May 04, 2022 |
| HP            | ProBook 6560b               | [10ed31948a](https://linux-hardware.org/?probe=10ed31948a) | May 04, 2022 |
| Toshiba       | Satellite C645D             | [53153cb65d](https://linux-hardware.org/?probe=53153cb65d) | May 04, 2022 |
| Lenovo        | IdeaPad Z370                | [be37f3c962](https://linux-hardware.org/?probe=be37f3c962) | May 04, 2022 |
| HP            | Compaq CQ58                 | [e42824ac37](https://linux-hardware.org/?probe=e42824ac37) | May 03, 2022 |
| Dell          | Latitude E7470              | [7991dfd7a5](https://linux-hardware.org/?probe=7991dfd7a5) | May 03, 2022 |
| Lenovo        | ThinkPad R500 27326FG       | [1ed6992177](https://linux-hardware.org/?probe=1ed6992177) | May 03, 2022 |
| Dell          | Latitude 3310               | [2b74207996](https://linux-hardware.org/?probe=2b74207996) | May 02, 2022 |
| Acer          | Nitro AN515-45              | [8115992c41](https://linux-hardware.org/?probe=8115992c41) | May 02, 2022 |
| Acer          | Aspire F5-573               | [f571b0dc6f](https://linux-hardware.org/?probe=f571b0dc6f) | May 02, 2022 |
| HP            | 255 G1                      | [48c43a229d](https://linux-hardware.org/?probe=48c43a229d) | May 01, 2022 |
| Lenovo        | G710 20252                  | [9390db3498](https://linux-hardware.org/?probe=9390db3498) | May 01, 2022 |
| ASUSTek       | UX31E                       | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Sony          | VGN-FZ31Z                   | [ebe91972ba](https://linux-hardware.org/?probe=ebe91972ba) | May 01, 2022 |
| HP            | Pavilion g6                 | [bc4107a3bf](https://linux-hardware.org/?probe=bc4107a3bf) | May 01, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [ea3bd2e330](https://linux-hardware.org/?probe=ea3bd2e330) | May 01, 2022 |
| Dell          | Latitude E5550              | [42a576bd39](https://linux-hardware.org/?probe=42a576bd39) | May 01, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [db2efb40d4](https://linux-hardware.org/?probe=db2efb40d4) | May 01, 2022 |
| Dell          | Inspiron 3793               | [9d2383d1f8](https://linux-hardware.org/?probe=9d2383d1f8) | Apr 30, 2022 |
| HP            | 650                         | [1332a3196c](https://linux-hardware.org/?probe=1332a3196c) | Apr 30, 2022 |
| Dell          | Latitude 3330               | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Lenovo        | Z50-70 20354                | [f253fe8221](https://linux-hardware.org/?probe=f253fe8221) | Apr 30, 2022 |
| Apple         | MacBookAir5,1               | [45c12c8fc4](https://linux-hardware.org/?probe=45c12c8fc4) | Apr 30, 2022 |
| Philco        | 14I                         | [03bb0fdeef](https://linux-hardware.org/?probe=03bb0fdeef) | Apr 30, 2022 |
| HP            | Laptop 17-by4xxx            | [767590ac38](https://linux-hardware.org/?probe=767590ac38) | Apr 29, 2022 |
| ASUSTek       | S551LN                      | [a5f0e1cee7](https://linux-hardware.org/?probe=a5f0e1cee7) | Apr 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [2c8a1c2444](https://linux-hardware.org/?probe=2c8a1c2444) | Apr 29, 2022 |
| ASUSTek       | UX31E                       | [8f165f54aa](https://linux-hardware.org/?probe=8f165f54aa) | Apr 29, 2022 |
| TUXEDO        | Book BM15 Gen10             | [45b5b1bba9](https://linux-hardware.org/?probe=45b5b1bba9) | Apr 29, 2022 |
| Dell          | Inspiron 3593               | [54087491d8](https://linux-hardware.org/?probe=54087491d8) | Apr 28, 2022 |
| Acer          | Extensa 5635G               | [6e69a86d63](https://linux-hardware.org/?probe=6e69a86d63) | Apr 28, 2022 |
| HUAWEI        | NBM-WXX9                    | [4f15ab06cc](https://linux-hardware.org/?probe=4f15ab06cc) | Apr 28, 2022 |
| Samsung       | RC530/RC730                 | [2e44e9228e](https://linux-hardware.org/?probe=2e44e9228e) | Apr 28, 2022 |
| ASUSTek       | UX31E                       | [ef86b0396a](https://linux-hardware.org/?probe=ef86b0396a) | Apr 27, 2022 |
| Dell          | Latitude E4310              | [41db45879c](https://linux-hardware.org/?probe=41db45879c) | Apr 27, 2022 |
| ASUSTek       | X505BA                      | [30972759d1](https://linux-hardware.org/?probe=30972759d1) | Apr 27, 2022 |
| Notebook      | W130SV                      | [a88535a3a5](https://linux-hardware.org/?probe=a88535a3a5) | Apr 27, 2022 |
| Positivo      | S14SL01                     | [f8bdbe707d](https://linux-hardware.org/?probe=f8bdbe707d) | Apr 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [14f1d071ae](https://linux-hardware.org/?probe=14f1d071ae) | Apr 26, 2022 |
| PC Special... | NJ50_70CU                   | [a9b4399cad](https://linux-hardware.org/?probe=a9b4399cad) | Apr 26, 2022 |
| HP            | ZBook 17 G3                 | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Intel         | Unknown                     | [41b673dda8](https://linux-hardware.org/?probe=41b673dda8) | Apr 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [64cd863479](https://linux-hardware.org/?probe=64cd863479) | Apr 26, 2022 |
| Medion        | S17402 MD63000              | [fe73d0023a](https://linux-hardware.org/?probe=fe73d0023a) | Apr 25, 2022 |
| Dell          | Latitude E6410              | [bc9515e4a7](https://linux-hardware.org/?probe=bc9515e4a7) | Apr 25, 2022 |
| Dell          | Inspiron 3537               | [2fcc2371d9](https://linux-hardware.org/?probe=2fcc2371d9) | Apr 25, 2022 |
| Dell          | Latitude E7270              | [d8dedbd4f6](https://linux-hardware.org/?probe=d8dedbd4f6) | Apr 25, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [7423afe5a1](https://linux-hardware.org/?probe=7423afe5a1) | Apr 25, 2022 |
| Dell          | Inspiron 7460               | [6a67f6de58](https://linux-hardware.org/?probe=6a67f6de58) | Apr 25, 2022 |
| Fujitsu       | FMVA06004                   | [4c63e1bcc2](https://linux-hardware.org/?probe=4c63e1bcc2) | Apr 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [2fcb2f9b19](https://linux-hardware.org/?probe=2fcb2f9b19) | Apr 24, 2022 |
| Lenovo        | ThinkPad W520 4284BL9       | [a7dd5a566e](https://linux-hardware.org/?probe=a7dd5a566e) | Apr 24, 2022 |
| Lenovo        | ThinkPad X220 42875TU       | [6748d74892](https://linux-hardware.org/?probe=6748d74892) | Apr 24, 2022 |
| Lenovo        | ThinkPad E460 20ET000YLM    | [c82beac367](https://linux-hardware.org/?probe=c82beac367) | Apr 23, 2022 |
| ASUSTek       | X705UQR                     | [e4a27bf740](https://linux-hardware.org/?probe=e4a27bf740) | Apr 23, 2022 |
| Chuwi         | AeroBook Pro                | [a123315898](https://linux-hardware.org/?probe=a123315898) | Apr 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3e3f727deb](https://linux-hardware.org/?probe=3e3f727deb) | Apr 23, 2022 |
| Acer          | Aspire V5-571G              | [e76a1e5467](https://linux-hardware.org/?probe=e76a1e5467) | Apr 23, 2022 |
| ASUSTek       | K55VD                       | [8c2253380a](https://linux-hardware.org/?probe=8c2253380a) | Apr 23, 2022 |
| Lenovo        | ThinkPad X220 42875TU       | [2dd8baa591](https://linux-hardware.org/?probe=2dd8baa591) | Apr 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [7988499108](https://linux-hardware.org/?probe=7988499108) | Apr 23, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [6fbbf00053](https://linux-hardware.org/?probe=6fbbf00053) | Apr 23, 2022 |
| HP            | Pavilion 15                 | [a1b094c360](https://linux-hardware.org/?probe=a1b094c360) | Apr 22, 2022 |
| Acer          | Aspire A515-54G             | [9eeb0ced39](https://linux-hardware.org/?probe=9eeb0ced39) | Apr 22, 2022 |
| Dell          | Precision 3560              | [cc7a9c5fe2](https://linux-hardware.org/?probe=cc7a9c5fe2) | Apr 22, 2022 |
| HP            | Laptop 15-ra0xx             | [bc175803f2](https://linux-hardware.org/?probe=bc175803f2) | Apr 22, 2022 |
| Dell          | Inspiron 1545               | [8869defd9c](https://linux-hardware.org/?probe=8869defd9c) | Apr 22, 2022 |
| Toshiba       | Satellite C850-A786         | [e57aca482e](https://linux-hardware.org/?probe=e57aca482e) | Apr 22, 2022 |
| HP            | ProBook 4540s               | [17272efb83](https://linux-hardware.org/?probe=17272efb83) | Apr 22, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| OpenMandriva 4.2    | 2150      | 50.98%  |
| OpenMandriva 4.3    | 1624      | 38.51%  |
| OpenMandriva 4.50   | 302       | 7.16%   |
| OpenMandriva 4.90   | 134       | 3.18%   |
| OpenMandriva 4.1    | 4         | 0.09%   |
| OpenMandriva 3.0    | 2         | 0.05%   |
| OpenMandriva 2014.0 | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| OpenMandriva | 4208      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Notebooks | Percent |
|--------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002       | 2065      | 48.69%  |
| 5.16.7-desktop-1omv4003        | 1567      | 36.95%  |
| 5.12.4-desktop-1omv4050        | 148       | 3.49%   |
| 5.18.12-desktop-3omv4090       | 117       | 2.76%   |
| 5.11.12-desktop-1omv4002       | 94        | 2.22%   |
| 5.14.7-desktop-1omv4050        | 80        | 1.89%   |
| 5.16.13-desktop-1omv4003       | 39        | 0.92%   |
| 5.19.5-desktop-1omv4090        | 35        | 0.83%   |
| 5.14.14-desktop-1omv4050       | 16        | 0.38%   |
| 5.17.1-desktop-2omv4050        | 12        | 0.28%   |
| 5.12.7-desktop-1omv4003        | 11        | 0.26%   |
| 5.19.1-desktop-1omv4090        | 5         | 0.12%   |
| 5.11.0-desktop-clang-1omv4002  | 5         | 0.12%   |
| 5.5.12-desktop-1omv4001        | 3         | 0.07%   |
| 5.16.9-desktop-1omv4003        | 3         | 0.07%   |
| 5.9.12-desktop-1omv4002        | 2         | 0.05%   |
| 5.19.3-desktop-1omv4090        | 2         | 0.05%   |
| 5.18.9-desktop-gcc-1omv4090    | 2         | 0.05%   |
| 5.18.13-desktop-1omv4090       | 2         | 0.05%   |
| 5.17.1-desktop-clang-2omv4050  | 2         | 0.05%   |
| 5.8.13-desktop-1omv4002        | 1         | 0.02%   |
| 5.5.0-desktop-1omv4001         | 1         | 0.02%   |
| 5.19.2-desktop-1omv4090        | 1         | 0.02%   |
| 5.19.12-desktop-2omv4090       | 1         | 0.02%   |
| 5.19.11-desktop-2omv4090       | 1         | 0.02%   |
| 5.18.11-desktop-gcc-3omv4090   | 1         | 0.02%   |
| 5.18.11-desktop-3omv4090       | 1         | 0.02%   |
| 5.16.9-desktop-1omv4050        | 1         | 0.02%   |
| 5.16.7-desktop-2omv4050        | 1         | 0.02%   |
| 5.16.5-desktop-2omv4003        | 1         | 0.02%   |
| 5.16.3-desktop-2omv4050        | 1         | 0.02%   |
| 5.16.2-desktop-2omv4050        | 1         | 0.02%   |
| 5.16.13-desktop-1omv4050       | 1         | 0.02%   |
| 5.16.0-desktop-1omv4050        | 1         | 0.02%   |
| 5.15.14-1-lts                  | 1         | 0.02%   |
| 5.15.13-desktop-1omv4050       | 1         | 0.02%   |
| 5.13.2-desktop-2.0mjn4.5       | 1         | 0.02%   |
| 5.12.8-desktop-clang-1omv4050  | 1         | 0.02%   |
| 5.12.7-desktop-clang-1omv4003  | 1         | 0.02%   |
| 5.11.16-desktop-clang-1omv4050 | 1         | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.14 | 2065      | 48.69%  |
| 5.16.7  | 1568      | 36.97%  |
| 5.12.4  | 148       | 3.49%   |
| 5.18.12 | 117       | 2.76%   |
| 5.11.12 | 94        | 2.22%   |
| 5.14.7  | 80        | 1.89%   |
| 5.16.13 | 40        | 0.94%   |
| 5.19.5  | 35        | 0.83%   |
| 5.14.14 | 16        | 0.38%   |
| 5.17.1  | 14        | 0.33%   |
| 5.12.7  | 12        | 0.28%   |
| 5.11.0  | 7         | 0.17%   |
| 5.19.1  | 5         | 0.12%   |
| 5.16.9  | 4         | 0.09%   |
| 5.5.12  | 3         | 0.07%   |
| 5.9.12  | 2         | 0.05%   |
| 5.19.3  | 2         | 0.05%   |
| 5.18.9  | 2         | 0.05%   |
| 5.18.13 | 2         | 0.05%   |
| 5.18.11 | 2         | 0.05%   |
| 5.8.13  | 1         | 0.02%   |
| 5.5.0   | 1         | 0.02%   |
| 5.19.2  | 1         | 0.02%   |
| 5.19.12 | 1         | 0.02%   |
| 5.19.11 | 1         | 0.02%   |
| 5.16.5  | 1         | 0.02%   |
| 5.16.3  | 1         | 0.02%   |
| 5.16.2  | 1         | 0.02%   |
| 5.16.0  | 1         | 0.02%   |
| 5.15.14 | 1         | 0.02%   |
| 5.15.13 | 1         | 0.02%   |
| 5.13.2  | 1         | 0.02%   |
| 5.12.8  | 1         | 0.02%   |
| 5.11.16 | 1         | 0.02%   |
| 5.11.14 | 1         | 0.02%   |
| 5.11.13 | 1         | 0.02%   |
| 5.11.1  | 1         | 0.02%   |
| 5.10.2  | 1         | 0.02%   |
| 5.10.12 | 1         | 0.02%   |
| 4.19.38 | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2067      | 48.75%  |
| 5.16    | 1616      | 38.11%  |
| 5.12    | 160       | 3.77%   |
| 5.18    | 123       | 2.9%    |
| 5.11    | 105       | 2.48%   |
| 5.14    | 96        | 2.26%   |
| 5.19    | 45        | 1.06%   |
| 5.17    | 14        | 0.33%   |
| 5.5     | 4         | 0.09%   |
| 5.9     | 2         | 0.05%   |
| 5.15    | 2         | 0.05%   |
| 4.19    | 2         | 0.05%   |
| 5.8     | 1         | 0.02%   |
| 5.13    | 1         | 0.02%   |
| 4.1     | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 4207      | 99.98%  |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 4192      | 99.6%   |
| Unknown  | 7         | 0.17%   |
| LXQt     | 6         | 0.14%   |
| KDE4     | 1         | 0.02%   |
| GNOME    | 1         | 0.02%   |
| Cinnamon | 1         | 0.02%   |
| Budgie   | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 4198      | 99.76%  |
| Wayland | 9         | 0.21%   |
| Tty     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 4205      | 99.9%   |
| Unknown | 2         | 0.05%   |
| LightDM | 1         | 0.02%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2231      | 52.87%  |
| de_DE   | 351       | 8.32%   |
| fr_FR   | 234       | 5.55%   |
| pl_PL   | 188       | 4.45%   |
| ru_RU   | 186       | 4.41%   |
| pt_BR   | 179       | 4.24%   |
| it_IT   | 131       | 3.1%    |
| cs_CZ   | 130       | 3.08%   |
| en_GB   | 100       | 2.37%   |
| es_ES   | 95        | 2.25%   |
| es_MX   | 37        | 0.88%   |
| es_AR   | 32        | 0.76%   |
| hu_HU   | 22        | 0.52%   |
| de_AT   | 22        | 0.52%   |
| es_CO   | 18        | 0.43%   |
| fr_BE   | 16        | 0.38%   |
| pt_PT   | 15        | 0.36%   |
| nl_NL   | 15        | 0.36%   |
| es_CL   | 15        | 0.36%   |
| en_IN   | 14        | 0.33%   |
| en_CA   | 14        | 0.33%   |
| fr_CH   | 12        | 0.28%   |
| en_AU   | 12        | 0.28%   |
| nl_BE   | 11        | 0.26%   |
| de_CH   | 11        | 0.26%   |
| ru_UA   | 10        | 0.24%   |
| ro_RO   | 10        | 0.24%   |
| da_DK   | 10        | 0.24%   |
| Unknown | 10        | 0.24%   |
| tr_TR   | 9         | 0.21%   |
| fr_CA   | 8         | 0.19%   |
| nb_NO   | 6         | 0.14%   |
| es_PE   | 6         | 0.14%   |
| en_NZ   | 6         | 0.14%   |
| es_VE   | 5         | 0.12%   |
| es_CR   | 5         | 0.12%   |
| uk_UA   | 4         | 0.09%   |
| es_UY   | 4         | 0.09%   |
| es_EC   | 3         | 0.07%   |
| es_BO   | 3         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 2196      | 52.15%  |
| EFI  | 2015      | 47.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Overlay | 3294      | 77.73%  |
| Ext4    | 901       | 21.26%  |
| Btrfs   | 15        | 0.35%   |
| F2fs    | 10        | 0.24%   |
| Xfs     | 6         | 0.14%   |
| Ext2    | 5         | 0.12%   |
| Unknown | 4         | 0.09%   |
| Ext3    | 2         | 0.05%   |
| Jfs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2629      | 62.37%  |
| MBR     | 1582      | 37.53%  |
| Unknown | 4         | 0.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2168      | 51.33%  |
| No        | 2056      | 48.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2437      | 57.87%  |
| Yes       | 1774      | 42.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 782       | 18.58%  |
| Hewlett-Packard       | 747       | 17.75%  |
| Dell                  | 630       | 14.97%  |
| ASUSTek Computer      | 536       | 12.74%  |
| Acer                  | 470       | 11.17%  |
| Toshiba               | 212       | 5.04%   |
| Sony                  | 113       | 2.69%   |
| Samsung Electronics   | 98        | 2.33%   |
| Apple                 | 68        | 1.62%   |
| MSI                   | 63        | 1.5%    |
| Fujitsu               | 57        | 1.35%   |
| Packard Bell          | 38        | 0.9%    |
| Positivo              | 36        | 0.86%   |
| Medion                | 32        | 0.76%   |
| HUAWEI                | 23        | 0.55%   |
| eMachines             | 20        | 0.48%   |
| Notebook              | 19        | 0.45%   |
| Unknown               | 19        | 0.45%   |
| TUXEDO                | 18        | 0.43%   |
| Philco                | 17        | 0.4%    |
| Fujitsu Siemens       | 13        | 0.31%   |
| LG Electronics        | 12        | 0.29%   |
| Chuwi                 | 10        | 0.24%   |
| Clevo                 | 8         | 0.19%   |
| Timi                  | 7         | 0.17%   |
| NEC Computers         | 7         | 0.17%   |
| Gateway               | 7         | 0.17%   |
| System76              | 6         | 0.14%   |
| Positivo Bahia - VAIO | 6         | 0.14%   |
| Compaq                | 6         | 0.14%   |
| Alienware             | 6         | 0.14%   |
| Wortmann AG           | 5         | 0.12%   |
| Teclast               | 5         | 0.12%   |
| PC Specialist         | 5         | 0.12%   |
| Intel                 | 5         | 0.12%   |
| Gigabyte Technology   | 5         | 0.12%   |
| Digibras              | 5         | 0.12%   |
| UMAX                  | 4         | 0.1%    |
| Panasonic             | 4         | 0.1%    |
| Framework             | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| ASUS UX31E                                 | 98        | 2.33%   |
| Unknown                                    | 46        | 1.09%   |
| HP Notebook                                | 41        | 0.97%   |
| Dell Latitude 3310                         | 29        | 0.69%   |
| Dell Inspiron 3451                         | 27        | 0.64%   |
| HP Pavilion g6                             | 23        | 0.55%   |
| HP Pavilion dv6                            | 20        | 0.48%   |
| Sony VGN-FZ31Z                             | 19        | 0.45%   |
| Dell Latitude E6430                        | 18        | 0.43%   |
| HP Pavilion 15                             | 15        | 0.36%   |
| Dell Latitude D630                         | 14        | 0.33%   |
| Dell Latitude E6410                        | 13        | 0.31%   |
| Positivo Mobile                            | 12        | 0.29%   |
| Dell Latitude E6420                        | 11        | 0.26%   |
| Lenovo IdeaPad S145-15AST 81N3             | 10        | 0.24%   |
| HP 15                                      | 10        | 0.24%   |
| Dell Inspiron 15-3567                      | 10        | 0.24%   |
| Toshiba Satellite A300                     | 9         | 0.21%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 9         | 0.21%   |
| HP 2000                                    | 9         | 0.21%   |
| Dell Latitude E7450                        | 9         | 0.21%   |
| Dell Inspiron N5110                        | 9         | 0.21%   |
| Apple MacBookPro9,2                        | 9         | 0.21%   |
| Acer Aspire 5738                           | 9         | 0.21%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 8         | 0.19%   |
| Lenovo IdeaPad 1 14ADA05 82GW              | 8         | 0.19%   |
| HP Pavilion Notebook                       | 8         | 0.19%   |
| HP Pavilion dv7                            | 8         | 0.19%   |
| HP Laptop 15-bs0xx                         | 8         | 0.19%   |
| HP EliteBook 8470p                         | 8         | 0.19%   |
| HP EliteBook 8440p                         | 8         | 0.19%   |
| Dell Latitude E6500                        | 8         | 0.19%   |
| Dell Latitude E6400                        | 8         | 0.19%   |
| Dell Latitude 3300                         | 8         | 0.19%   |
| Acer Aspire A515-51G                       | 8         | 0.19%   |
| Toshiba dynabook T653/46JR                 | 7         | 0.17%   |
| Philco 14I                                 | 7         | 0.17%   |
| Lenovo Z50-70 20354                        | 7         | 0.17%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 7         | 0.17%   |
| Lenovo G50-45 80E3                         | 7         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 340       | 8.08%   |
| Dell Latitude         | 330       | 7.84%   |
| Lenovo ThinkPad       | 320       | 7.6%    |
| Lenovo IdeaPad        | 250       | 5.94%   |
| Dell Inspiron         | 180       | 4.28%   |
| Toshiba Satellite     | 169       | 4.02%   |
| HP Pavilion           | 168       | 3.99%   |
| HP Laptop             | 120       | 2.85%   |
| ASUS UX31E            | 98        | 2.33%   |
| HP ProBook            | 88        | 2.09%   |
| HP EliteBook          | 82        | 1.95%   |
| ASUS VivoBook         | 77        | 1.83%   |
| HP Compaq             | 58        | 1.38%   |
| Unknown               | 46        | 1.09%   |
| Fujitsu LIFEBOOK      | 43        | 1.02%   |
| HP Notebook           | 41        | 0.97%   |
| Packard Bell EasyNote | 32        | 0.76%   |
| Dell Vostro           | 32        | 0.76%   |
| Acer Extensa          | 29        | 0.69%   |
| Acer TravelMate       | 26        | 0.62%   |
| Dell XPS              | 25        | 0.59%   |
| Dell Precision        | 23        | 0.55%   |
| Acer Swift            | 23        | 0.55%   |
| HP 250                | 21        | 0.5%    |
| Toshiba dynabook      | 19        | 0.45%   |
| Sony VGN-FZ31Z        | 19        | 0.45%   |
| Acer Nitro            | 19        | 0.45%   |
| HP ENVY               | 16        | 0.38%   |
| ASUS ZenBook          | 15        | 0.36%   |
| HP Stream             | 13        | 0.31%   |
| HP 255                | 13        | 0.31%   |
| Dell Studio           | 13        | 0.31%   |
| Positivo Mobile       | 12        | 0.29%   |
| HP OMEN               | 12        | 0.29%   |
| Apple MacBookPro9     | 12        | 0.29%   |
| Lenovo Legion         | 11        | 0.26%   |
| HP 15                 | 11        | 0.26%   |
| Dell System           | 11        | 0.26%   |
| ASUS TUF              | 10        | 0.24%   |
| Apple MacBookPro8     | 10        | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 547       | 13%     |
| 2012    | 418       | 9.93%   |
| 2013    | 341       | 8.1%    |
| 2019    | 323       | 7.68%   |
| 2010    | 310       | 7.37%   |
| 2014    | 305       | 7.25%   |
| 2020    | 254       | 6.04%   |
| 2008    | 245       | 5.82%   |
| 2016    | 244       | 5.8%    |
| 2015    | 244       | 5.8%    |
| 2018    | 219       | 5.2%    |
| 2017    | 217       | 5.16%   |
| 2009    | 197       | 4.68%   |
| 2007    | 155       | 3.68%   |
| 2021    | 149       | 3.54%   |
| 2006    | 22        | 0.52%   |
| 2022    | 9         | 0.21%   |
| Unknown | 6         | 0.14%   |
| 2005    | 2         | 0.05%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4208      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4208      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4199      | 99.79%  |
| Yes  | 9         | 0.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 1579      | 37.49%  |
| 4.01-8.0    | 1341      | 31.84%  |
| 8.01-16.0   | 560       | 13.3%   |
| 16.01-24.0  | 345       | 8.19%   |
| 1.01-2.0    | 193       | 4.58%   |
| 2.01-3.0    | 88        | 2.09%   |
| 32.01-64.0  | 72        | 1.71%   |
| 24.01-32.0  | 15        | 0.36%   |
| 0.51-1.0    | 10        | 0.24%   |
| 64.01-256.0 | 8         | 0.19%   |
| Unknown     | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 3437      | 81.33%  |
| 0.51-1.0  | 439       | 10.39%  |
| 2.01-3.0  | 281       | 6.65%   |
| 0.01-0.5  | 40        | 0.95%   |
| 3.01-4.0  | 16        | 0.38%   |
| 4.01-8.0  | 9         | 0.21%   |
| 8.01-16.0 | 3         | 0.07%   |
| Unknown   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3148      | 74.76%  |
| 2      | 882       | 20.95%  |
| 3      | 96        | 2.28%   |
| 0      | 68        | 1.61%   |
| 4      | 15        | 0.36%   |
| 5      | 2         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2202      | 52.3%   |
| No        | 2008      | 47.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3708      | 88.12%  |
| No        | 500       | 11.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4176      | 99.24%  |
| No        | 32        | 0.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2940      | 69.85%  |
| No        | 1269      | 30.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 490       | 11.64%  |
| USA          | 445       | 10.57%  |
| France       | 297       | 7.06%   |
| Brazil       | 290       | 6.89%   |
| Poland       | 273       | 6.49%   |
| Russia       | 239       | 5.68%   |
| Italy        | 198       | 4.7%    |
| Czechia      | 149       | 3.54%   |
| UK           | 138       | 3.28%   |
| Spain        | 137       | 3.25%   |
| Netherlands  | 104       | 2.47%   |
| Canada       | 98        | 2.33%   |
| Mexico       | 79        | 1.88%   |
| India        | 64        | 1.52%   |
| Portugal     | 58        | 1.38%   |
| Indonesia    | 55        | 1.31%   |
| Japan        | 52        | 1.24%   |
| Australia    | 51        | 1.21%   |
| Ukraine      | 47        | 1.12%   |
| Sweden       | 43        | 1.02%   |
| Argentina    | 43        | 1.02%   |
| Romania      | 42        | 1%      |
| Belgium      | 41        | 0.97%   |
| Switzerland  | 40        | 0.95%   |
| Hungary      | 36        | 0.86%   |
| Austria      | 34        | 0.81%   |
| Colombia     | 33        | 0.78%   |
| Greece       | 30        | 0.71%   |
| Bulgaria     | 29        | 0.69%   |
| China        | 28        | 0.67%   |
| Turkey       | 27        | 0.64%   |
| Finland      | 27        | 0.64%   |
| Slovakia     | 24        | 0.57%   |
| Chile        | 22        | 0.52%   |
| Norway       | 19        | 0.45%   |
| New Zealand  | 19        | 0.45%   |
| Denmark      | 18        | 0.43%   |
| South Africa | 17        | 0.4%    |
| Serbia       | 16        | 0.38%   |
| Belarus      | 15        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Prague         | 95        | 2.25%   |
| Schagen        | 56        | 1.32%   |
| Moscow         | 47        | 1.11%   |
| Paris          | 45        | 1.06%   |
| Warsaw         | 41        | 0.97%   |
| Krakow         | 39        | 0.92%   |
| Berlin         | 38        | 0.9%    |
| Milan          | 32        | 0.76%   |
| Sao Paulo      | 31        | 0.73%   |
| Munich         | 26        | 0.62%   |
| St Petersburg  | 22        | 0.52%   |
| Rome           | 21        | 0.5%    |
| Mexico City    | 21        | 0.5%    |
| Funchal        | 20        | 0.47%   |
| Vienna         | 19        | 0.45%   |
| Rio de Janeiro | 17        | 0.4%    |
| Wroclaw        | 16        | 0.38%   |
| Sydney         | 16        | 0.38%   |
| Madrid         | 15        | 0.35%   |
| Krasnodar      | 15        | 0.35%   |
| Helsinki       | 15        | 0.35%   |
| Hamburg        | 15        | 0.35%   |
| Stuttgart      | 14        | 0.33%   |
| Bucharest      | 12        | 0.28%   |
| Thessaloniki   | 11        | 0.26%   |
| Queens         | 11        | 0.26%   |
| Jakarta        | 11        | 0.26%   |
| Gdansk         | 11        | 0.26%   |
| Buenos Aires   | 11        | 0.26%   |
| Bengaluru      | 11        | 0.26%   |
| Belgrade       | 11        | 0.26%   |
| Athens         | 11        | 0.26%   |
| Yekaterinburg  | 10        | 0.24%   |
| Sofia          | 10        | 0.24%   |
| Poznan         | 10        | 0.24%   |
| Lima           | 10        | 0.24%   |
| Dortmund       | 10        | 0.24%   |
| Curitiba       | 10        | 0.24%   |
| Cologne        | 10        | 0.24%   |
| Brno           | 10        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 750       | 772    | 15.33%  |
| Seagate             | 645       | 663    | 13.18%  |
| Samsung Electronics | 556       | 597    | 11.37%  |
| Toshiba             | 482       | 499    | 9.85%   |
| Kingston            | 283       | 291    | 5.78%   |
| SanDisk             | 269       | 274    | 5.5%    |
| Hitachi             | 249       | 251    | 5.09%   |
| Unknown             | 188       | 193    | 3.84%   |
| Crucial             | 172       | 182    | 3.52%   |
| HGST                | 155       | 158    | 3.17%   |
| SK hynix            | 143       | 148    | 2.92%   |
| Intel               | 92        | 102    | 1.88%   |
| A-DATA Technology   | 86        | 87     | 1.76%   |
| Micron Technology   | 62        | 63     | 1.27%   |
| Fujitsu             | 47        | 47     | 0.96%   |
| China               | 38        | 38     | 0.78%   |
| GOODRAM             | 36        | 38     | 0.74%   |
| PNY                 | 33        | 33     | 0.67%   |
| LITEON              | 33        | 33     | 0.67%   |
| Apple               | 30        | 32     | 0.61%   |
| Unknown             | 28        | 29     | 0.57%   |
| KIOXIA              | 27        | 28     | 0.55%   |
| Intenso             | 26        | 27     | 0.53%   |
| JMicron Technology  | 24        | 24     | 0.49%   |
| Patriot             | 23        | 25     | 0.47%   |
| SPCC                | 21        | 21     | 0.43%   |
| Transcend           | 20        | 20     | 0.41%   |
| OCZ                 | 17        | 17     | 0.35%   |
| Phison              | 15        | 15     | 0.31%   |
| ASMT                | 15        | 15     | 0.31%   |
| Apacer              | 15        | 15     | 0.31%   |
| LITEONIT            | 14        | 15     | 0.29%   |
| KingSpec            | 14        | 14     | 0.29%   |
| Hewlett-Packard     | 13        | 13     | 0.27%   |
| Silicon Motion      | 12        | 13     | 0.25%   |
| SABRENT             | 12        | 14     | 0.25%   |
| Corsair             | 11        | 11     | 0.22%   |
| UMIS                | 10        | 10     | 0.2%    |
| Gigabyte Technology | 10        | 10     | 0.2%    |
| SSSTC               | 9         | 9      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB              | 98        | 1.97%   |
| Seagate ST500LT012-1DG142 500GB     | 94        | 1.89%   |
| Toshiba MQ01ABF050 500GB            | 80        | 1.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 75        | 1.51%   |
| Toshiba MQ01ABD100 1TB              | 60        | 1.21%   |
| Seagate ST1000LM035-1RK172 1TB      | 60        | 1.21%   |
| Kingston SA400S37240G 240GB SSD     | 51        | 1.03%   |
| Toshiba MQ04ABF100 1TB              | 46        | 0.93%   |
| Seagate ST9500325AS 500GB           | 40        | 0.81%   |
| Kingston SA400S37120G 120GB SSD     | 37        | 0.74%   |
| Samsung SSD 860 EVO 500GB           | 35        | 0.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 32        | 0.64%   |
| Kingston SA400S37480G 480GB SSD     | 32        | 0.64%   |
| HGST HTS721010A9E630 1TB            | 32        | 0.64%   |
| HGST HTS541010A9E680 1TB            | 32        | 0.64%   |
| Crucial CT240BX500SSD1 240GB        | 32        | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB            | 31        | 0.62%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 30        | 0.6%    |
| HGST HTS545050A7E680 500GB          | 28        | 0.56%   |
| Unknown                             | 28        | 0.56%   |
| Hitachi HTS547550A9E384 500GB       | 26        | 0.52%   |
| Unknown SD/MMC/MS PRO 2GB           | 24        | 0.48%   |
| Seagate ST500LT012-9WS142 500GB     | 24        | 0.48%   |
| Samsung SSD 850 EVO 500GB           | 24        | 0.48%   |
| Samsung SSD 850 EVO 250GB           | 24        | 0.48%   |
| Kingston SV300S37A120G 120GB SSD    | 23        | 0.46%   |
| Hitachi HTS543232A7A384 320GB       | 22        | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 21        | 0.42%   |
| Seagate ST9320325AS 320GB           | 20        | 0.4%    |
| WDC WD10SPZX-21Z10T0 1TB            | 19        | 0.38%   |
| PNY CS900 120GB SSD                 | 19        | 0.38%   |
| HGST HTS545050A7E380 500GB          | 19        | 0.38%   |
| Crucial CT500MX500SSD1 500GB        | 19        | 0.38%   |
| Toshiba MQ01ABD075 752GB            | 18        | 0.36%   |
| JMicron Generic 120GB               | 18        | 0.36%   |
| Samsung SSD 860 EVO 250GB           | 17        | 0.34%   |
| Hitachi HTS545050A7E380 500GB       | 17        | 0.34%   |
| WDC WD10JPCX-24UE4T0 1TB            | 16        | 0.32%   |
| Toshiba MQ01ABD050 500GB            | 16        | 0.32%   |
| Seagate ST500LM021-1KJ152 500GB     | 16        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 637       | 653    | 29.29%  |
| WDC                 | 559       | 571    | 25.7%   |
| Toshiba             | 423       | 434    | 19.45%  |
| Hitachi             | 249       | 251    | 11.45%  |
| HGST                | 155       | 158    | 7.13%   |
| Samsung Electronics | 49        | 51     | 2.25%   |
| Fujitsu             | 47        | 47     | 2.16%   |
| Unknown             | 24        | 24     | 1.1%    |
| Apple               | 11        | 11     | 0.51%   |
| ASMT                | 3         | 3      | 0.14%   |
| ASMedia             | 3         | 3      | 0.14%   |
| SAGE                | 2         | 2      | 0.09%   |
| SABRENT             | 2         | 3      | 0.09%   |
| HGST HTS            | 2         | 2      | 0.09%   |
| WD MediaMax         | 1         | 1      | 0.05%   |
| USB3.0              | 1         | 1      | 0.05%   |
| USB                 | 1         | 1      | 0.05%   |
| SATAFIRM            | 1         | 1      | 0.05%   |
| QC-FT-D             | 1         | 1      | 0.05%   |
| Magnetic Data       | 1         | 1      | 0.05%   |
| Intenso             | 1         | 1      | 0.05%   |
| IBM/Hitachi         | 1         | 1      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 361       | 378    | 19.55%  |
| SanDisk             | 251       | 255    | 13.59%  |
| Kingston            | 237       | 244    | 12.83%  |
| Crucial             | 160       | 170    | 8.66%   |
| WDC                 | 96        | 96     | 5.2%    |
| A-DATA Technology   | 66        | 67     | 3.57%   |
| SK hynix            | 51        | 53     | 2.76%   |
| Micron Technology   | 44        | 45     | 2.38%   |
| Toshiba             | 40        | 43     | 2.17%   |
| Intel               | 38        | 39     | 2.06%   |
| China               | 38        | 38     | 2.06%   |
| GOODRAM             | 36        | 38     | 1.95%   |
| PNY                 | 31        | 31     | 1.68%   |
| LITEON              | 30        | 30     | 1.62%   |
| Patriot             | 23        | 25     | 1.25%   |
| Intenso             | 23        | 24     | 1.25%   |
| Transcend           | 19        | 19     | 1.03%   |
| SPCC                | 18        | 18     | 0.97%   |
| OCZ                 | 17        | 17     | 0.92%   |
| Apple               | 16        | 16     | 0.87%   |
| Apacer              | 15        | 15     | 0.81%   |
| Unknown             | 15        | 15     | 0.81%   |
| LITEONIT            | 14        | 15     | 0.76%   |
| KingSpec            | 14        | 14     | 0.76%   |
| Unknown             | 9         | 9      | 0.49%   |
| Plextor             | 9         | 9      | 0.49%   |
| Hewlett-Packard     | 9         | 9      | 0.49%   |
| ASMT                | 9         | 9      | 0.49%   |
| Corsair             | 8         | 8      | 0.43%   |
| KingDian            | 7         | 7      | 0.38%   |
| Netac               | 6         | 6      | 0.32%   |
| Teclast             | 5         | 5      | 0.27%   |
| Lexar               | 5         | 5      | 0.27%   |
| INNOVATION IT       | 5         | 5      | 0.27%   |
| Gigabyte Technology | 5         | 5      | 0.27%   |
| Dogfish             | 5         | 5      | 0.27%   |
| BHT                 | 5         | 5      | 0.27%   |
| TCSUNBOW            | 4         | 4      | 0.22%   |
| Leven               | 4         | 4      | 0.22%   |
| KIOXIA-EXCERIA      | 4         | 4      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2123      | 2222   | 44.93%  |
| SSD     | 1745      | 1900   | 36.93%  |
| NVMe    | 629       | 693    | 13.31%  |
| MMC     | 184       | 195    | 3.89%   |
| Unknown | 44        | 45     | 0.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3565      | 3992   | 78.49%  |
| NVMe | 610       | 662    | 13.43%  |
| MMC  | 184       | 195    | 4.05%   |
| SAS  | 183       | 206    | 4.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2874      | 3140   | 75.39%  |
| 0.51-1.0   | 857       | 898    | 22.48%  |
| 1.01-2.0   | 71        | 74     | 1.86%   |
| 3.01-4.0   | 7         | 7      | 0.18%   |
| 4.01-10.0  | 3         | 3      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2403      | 56.74%  |
| 101-250        | 647       | 15.28%  |
| 251-500        | 443       | 10.46%  |
| 501-1000       | 191       | 4.51%   |
| 51-100         | 189       | 4.46%   |
| Unknown        | 171       | 4.04%   |
| 21-50          | 146       | 3.45%   |
| 1001-2000      | 39        | 0.92%   |
| 2001-3000      | 4         | 0.09%   |
| More than 3000 | 2         | 0.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 3741      | 88.36%  |
| Unknown        | 171       | 4.04%   |
| 21-50          | 109       | 2.57%   |
| 101-250        | 79        | 1.87%   |
| 51-100         | 71        | 1.68%   |
| 251-500        | 42        | 0.99%   |
| 501-1000       | 11        | 0.26%   |
| 1001-2000      | 7         | 0.17%   |
| More than 3000 | 1         | 0.02%   |
| 2001-3000      | 1         | 0.02%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB              | 98        | 98     | 8.81%   |
| Seagate ST500LT012-1DG142 500GB     | 29        | 29     | 2.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 28        | 28     | 2.52%   |
| Seagate ST9500325AS 500GB           | 27        | 29     | 2.43%   |
| Toshiba MQ01ABF050 500GB            | 25        | 25     | 2.25%   |
| Seagate ST500LT012-9WS142 500GB     | 22        | 23     | 1.98%   |
| HGST HTS541010A9E680 1TB            | 20        | 20     | 1.8%    |
| HGST HTS545050A7E680 500GB          | 19        | 19     | 1.71%   |
| Seagate ST9320325AS 320GB           | 17        | 17     | 1.53%   |
| Hitachi HTS543232A7A384 320GB       | 14        | 14     | 1.26%   |
| Toshiba MQ01ABD075 752GB            | 13        | 13     | 1.17%   |
| Hitachi HTS545050A7E380 500GB       | 12        | 12     | 1.08%   |
| Crucial CT240M500SSD1 240GB         | 12        | 12     | 1.08%   |
| Toshiba MQ01ABD100 1TB              | 11        | 11     | 0.99%   |
| Toshiba MQ01ABD050 500GB            | 11        | 11     | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB      | 11        | 11     | 0.99%   |
| Hitachi HTS547550A9E384 500GB       | 11        | 12     | 0.99%   |
| WDC WD10JPVX-22JC3T0 1TB            | 10        | 10     | 0.9%    |
| Kingston SV300S37A120G 120GB SSD    | 10        | 10     | 0.9%    |
| HGST HTS545050A7E380 500GB          | 10        | 10     | 0.9%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 9         | 9      | 0.81%   |
| Toshiba MK3265GSX 320GB             | 9         | 9      | 0.81%   |
| HGST HTS725050A7E630 500GB          | 9         | 9      | 0.81%   |
| Seagate ST9250827AS 250GB           | 8         | 8      | 0.72%   |
| Seagate ST9250315AS 250GB           | 8         | 8      | 0.72%   |
| Seagate ST500LM021-1KJ152 500GB     | 8         | 8      | 0.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 8         | 8      | 0.72%   |
| HGST HTS541075A9E680 752GB          | 8         | 8      | 0.72%   |
| Seagate ST9500420AS 500GB           | 7         | 7      | 0.63%   |
| Seagate ST9250410AS 250GB           | 7         | 8      | 0.63%   |
| Hitachi HTS547575A9E384 752GB       | 7         | 7      | 0.63%   |
| Hitachi HTS547564A9E384 640GB       | 7         | 7      | 0.63%   |
| Hitachi HTS545025B9A300 250GB       | 7         | 7      | 0.63%   |
| Hitachi HTS542516K9SA00 160GB       | 7         | 7      | 0.63%   |
| HGST HTS721010A9E630 1TB            | 7         | 7      | 0.63%   |
| Seagate ST9320423AS 320GB           | 6         | 6      | 0.54%   |
| WDC WD3200BEVT-60A23T0 320GB        | 5         | 5      | 0.45%   |
| WDC WD10SPZX-24Z10T0 1TB            | 5         | 5      | 0.45%   |
| Seagate ST500LM000-1EJ162 500GB     | 5         | 5      | 0.45%   |
| Seagate ST320LT007-9ZV142 320GB     | 5         | 5      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 253       | 258    | 22.77%  |
| Toshiba             | 168       | 169    | 15.12%  |
| WDC                 | 155       | 156    | 13.95%  |
| Hitachi             | 147       | 148    | 13.23%  |
| SanDisk             | 116       | 116    | 10.44%  |
| HGST                | 79        | 79     | 7.11%   |
| Samsung Electronics | 45        | 46     | 4.05%   |
| Crucial             | 25        | 25     | 2.25%   |
| Kingston            | 22        | 22     | 1.98%   |
| Fujitsu             | 18        | 18     | 1.62%   |
| SK hynix            | 12        | 13     | 1.08%   |
| Intel               | 11        | 11     | 0.99%   |
| A-DATA Technology   | 11        | 12     | 0.99%   |
| Micron Technology   | 6         | 6      | 0.54%   |
| China               | 5         | 5      | 0.45%   |
| OCZ                 | 3         | 3      | 0.27%   |
| LITEON              | 3         | 3      | 0.27%   |
| Apple               | 3         | 3      | 0.27%   |
| Transcend           | 2         | 2      | 0.18%   |
| KingSpec            | 2         | 2      | 0.18%   |
| Dogfish             | 2         | 2      | 0.18%   |
| Corsair             | 2         | 2      | 0.18%   |
| ASMedia             | 2         | 2      | 0.18%   |
| Vaseky              | 1         | 1      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |
| TakeMS              | 1         | 1      | 0.09%   |
| SPCC                | 1         | 1      | 0.09%   |
| Smartbuy            | 1         | 1      | 0.09%   |
| PNY                 | 1         | 1      | 0.09%   |
| Plextor             | 1         | 1      | 0.09%   |
| Platinet            | 1         | 1      | 0.09%   |
| Magnetic Data       | 1         | 1      | 0.09%   |
| LITEONIT            | 1         | 1      | 0.09%   |
| KingDian            | 1         | 1      | 0.09%   |
| Intenso             | 1         | 1      | 0.09%   |
| IBM/Hitachi         | 1         | 1      | 0.09%   |
| Hewlett-Packard     | 1         | 1      | 0.09%   |
| GOODRAM             | 1         | 1      | 0.09%   |
| Drevo               | 1         | 1      | 0.09%   |
| Colorful            | 1         | 1      | 0.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 253       | 258    | 30.15%  |
| Toshiba             | 165       | 166    | 19.67%  |
| Hitachi             | 147       | 148    | 17.52%  |
| WDC                 | 145       | 146    | 17.28%  |
| HGST                | 79        | 79     | 9.42%   |
| Samsung Electronics | 26        | 27     | 3.1%    |
| Fujitsu             | 18        | 18     | 2.15%   |
| ASMedia             | 2         | 2      | 0.24%   |
| Apple               | 2         | 2      | 0.24%   |
| Magnetic Data       | 1         | 1      | 0.12%   |
| IBM/Hitachi         | 1         | 1      | 0.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 834       | 848    | 75.41%  |
| SSD  | 263       | 265    | 23.78%  |
| NVMe | 9         | 9      | 0.81%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 6.9%    |
| WDC WD2500BEVS-22UST0 250GB           | 2         | 2      | 6.9%    |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 6.9%    |
| Crucial CT500P2SSD8 500GB             | 2         | 2      | 6.9%    |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB      | 1         | 1      | 3.45%   |
| WDC WD5000LPLX-75ZNTT0 500GB          | 1         | 1      | 3.45%   |
| WDC WD5000BPVT-60HXZT1 500GB          | 1         | 1      | 3.45%   |
| WDC WD5000BEVT-22ZAT0 500GB           | 1         | 1      | 3.45%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 3.45%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 1      | 3.45%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 3.45%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 3.45%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 3.45%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 3.45%   |
| Toshiba MK3265GSXN 320GB              | 1         | 1      | 3.45%   |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 3.45%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 3.45%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 3.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 3.45%   |
| Samsung Electronics SSD PM800 TM 64GB | 1         | 1      | 3.45%   |
| Samsung Electronics HM321HI 320GB     | 1         | 1      | 3.45%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 3.45%   |
| Intel SSDSA2BW160G3 160GB             | 1         | 1      | 3.45%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 3.45%   |
| Apple HDD HTS545050A7E362 500GB       | 1         | 1      | 3.45%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 41.38%  |
| Toshiba             | 4         | 4      | 13.79%  |
| Samsung Electronics | 3         | 3      | 10.34%  |
| Seagate             | 2         | 2      | 6.9%    |
| Hitachi             | 2         | 2      | 6.9%    |
| Crucial             | 2         | 2      | 6.9%    |
| SK hynix            | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3035      | 3522   | 67.46%  |
| Malfunc  | 1097      | 1122   | 24.38%  |
| Detected | 338       | 382    | 7.51%   |
| Failed   | 29        | 29     | 0.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3288      | 72.41%  |
| AMD                              | 602       | 13.26%  |
| Samsung Electronics              | 171       | 3.77%   |
| SanDisk                          | 102       | 2.25%   |
| SK hynix                         | 84        | 1.85%   |
| Kingston Technology Company      | 47        | 1.04%   |
| Nvidia                           | 42        | 0.92%   |
| Phison Electronics               | 30        | 0.66%   |
| KIOXIA                           | 28        | 0.62%   |
| Toshiba America Info Systems     | 20        | 0.44%   |
| Silicon Motion                   | 19        | 0.42%   |
| Micron Technology                | 19        | 0.42%   |
| Union Memory (Shenzhen)          | 14        | 0.31%   |
| ADATA Technology                 | 13        | 0.29%   |
| Micron/Crucial Technology        | 11        | 0.24%   |
| Solid State Storage Technology   | 9         | 0.2%    |
| Realtek Semiconductor            | 8         | 0.18%   |
| Silicon Integrated Systems [SiS] | 6         | 0.13%   |
| ASMedia Technology               | 5         | 0.11%   |
| JMicron Technology               | 4         | 0.09%   |
| Silicon Image                    | 3         | 0.07%   |
| Lite-On Technology               | 3         | 0.07%   |
| Biwin Storage Technology         | 3         | 0.07%   |
| Apple                            | 3         | 0.07%   |
| Seagate Technology               | 2         | 0.04%   |
| Marvell Technology Group         | 2         | 0.04%   |
| Lenovo                           | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 448       | 9.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 443       | 8.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 401       | 8.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 344       | 6.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 268       | 5.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 244       | 4.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 180       | 3.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 179       | 3.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 157       | 3.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 151       | 3.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 130       | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 115       | 2.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 113       | 2.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 97        | 1.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 78        | 1.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 75        | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 73        | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 66        | 1.33%   |
| Samsung NVMe SSD Controller 980                                                        | 58        | 1.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 55        | 1.11%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 52        | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 42        | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 41        | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 37        | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 37        | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 36        | 0.73%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 35        | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 32        | 0.65%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 29        | 0.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 29        | 0.59%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 27        | 0.55%   |
| SK hynix BC511                                                                         | 26        | 0.53%   |
| Intel SSD 660P Series                                                                  | 26        | 0.53%   |
| SK hynix Gold P31 SSD                                                                  | 24        | 0.49%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 24        | 0.49%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 24        | 0.49%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 24        | 0.49%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 24        | 0.49%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 23        | 0.47%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 22        | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3473      | 72.57%  |
| NVMe | 610       | 12.75%  |
| IDE  | 408       | 8.52%   |
| RAID | 295       | 6.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3475      | 82.58%  |
| AMD    | 733       | 17.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 98        | 2.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 65        | 1.54%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 62        | 1.47%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 59        | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 53        | 1.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 53        | 1.26%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 49        | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 46        | 1.09%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 45        | 1.07%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 43        | 1.02%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 41        | 0.97%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 40        | 0.95%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 37        | 0.88%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 35        | 0.83%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 35        | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 34        | 0.81%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 34        | 0.81%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 0.78%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 33        | 0.78%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 33        | 0.78%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 33        | 0.78%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 32        | 0.76%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 31        | 0.74%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 31        | 0.74%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 31        | 0.74%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 29        | 0.69%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 29        | 0.69%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 28        | 0.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 27        | 0.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 27        | 0.64%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 27        | 0.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 26        | 0.62%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 26        | 0.62%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 25        | 0.59%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 25        | 0.59%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 24        | 0.57%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 24        | 0.57%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 24        | 0.57%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 23        | 0.55%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 23        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1039      | 24.69%  |
| Intel Core i7           | 634       | 15.07%  |
| Intel Core i3           | 540       | 12.83%  |
| Intel Celeron           | 390       | 9.27%   |
| Intel Core 2 Duo        | 361       | 8.58%   |
| Intel Pentium           | 188       | 4.47%   |
| AMD Ryzen 5             | 116       | 2.76%   |
| Other                   | 109       | 2.59%   |
| Intel Pentium Dual-Core | 79        | 1.88%   |
| AMD Ryzen 7             | 73        | 1.73%   |
| AMD E                   | 56        | 1.33%   |
| AMD A6                  | 55        | 1.31%   |
| AMD E1                  | 51        | 1.21%   |
| Intel Pentium Dual      | 44        | 1.05%   |
| AMD A8                  | 44        | 1.05%   |
| AMD A4                  | 41        | 0.97%   |
| AMD Ryzen 3             | 37        | 0.88%   |
| Intel Atom              | 32        | 0.76%   |
| AMD E2                  | 32        | 0.76%   |
| AMD A10                 | 32        | 0.76%   |
| Intel Pentium Silver    | 25        | 0.59%   |
| AMD C-60                | 22        | 0.52%   |
| Intel Core 2            | 20        | 0.48%   |
| AMD Athlon              | 19        | 0.45%   |
| Intel Celeron Dual-Core | 14        | 0.33%   |
| Intel Genuine           | 13        | 0.31%   |
| AMD Ryzen 9             | 9         | 0.21%   |
| AMD Athlon II           | 9         | 0.21%   |
| AMD Turion 64 X2 Mobile | 8         | 0.19%   |
| AMD Phenom II           | 8         | 0.19%   |
| AMD Athlon X2           | 7         | 0.17%   |
| AMD Athlon 64 X2        | 7         | 0.17%   |
| Intel Core m3           | 6         | 0.14%   |
| AMD Turion II Dual-Core | 6         | 0.14%   |
| AMD C-70                | 6         | 0.14%   |
| AMD Sempron             | 5         | 0.12%   |
| AMD Ryzen 7 PRO         | 5         | 0.12%   |
| AMD Mobile Sempron      | 5         | 0.12%   |
| AMD A12                 | 5         | 0.12%   |
| AMD FX                  | 4         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3062      | 72.77%  |
| 4      | 872       | 20.72%  |
| 6      | 102       | 2.42%   |
| 1      | 90        | 2.14%   |
| 8      | 76        | 1.81%   |
| 12     | 2         | 0.05%   |
| 3      | 2         | 0.05%   |
| 10     | 1         | 0.02%   |
| 5      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4208      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2587      | 61.48%  |
| 1      | 1612      | 38.31%  |
| 8      | 9         | 0.21%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4205      | 99.93%  |
| Unknown        | 3         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 533       | 12.66%  |
| 0x306a9    | 397       | 9.43%   |
| 0x1067a    | 260       | 6.18%   |
| 0x20655    | 209       | 4.96%   |
| 0x406e3    | 168       | 3.99%   |
| 0x40651    | 168       | 3.99%   |
| 0x306d4    | 153       | 3.63%   |
| 0x806e9    | 140       | 3.33%   |
| 0x6fd      | 131       | 3.11%   |
| Unknown    | 116       | 2.76%   |
| 0x306c3    | 112       | 2.66%   |
| 0x806ea    | 110       | 2.61%   |
| 0x30678    | 105       | 2.49%   |
| 0x10676    | 100       | 2.38%   |
| 0x806ec    | 99        | 2.35%   |
| 0x08108109 | 74        | 1.76%   |
| 0x406c4    | 68        | 1.62%   |
| 0x706e5    | 65        | 1.54%   |
| 0x20652    | 65        | 1.54%   |
| 0x06006705 | 58        | 1.38%   |
| 0x906ea    | 55        | 1.31%   |
| 0x07030105 | 51        | 1.21%   |
| 0x806c1    | 50        | 1.19%   |
| 0x506c9    | 50        | 1.19%   |
| 0x706a1    | 48        | 1.14%   |
| 0x0500010d | 48        | 1.14%   |
| 0x506e3    | 47        | 1.12%   |
| 0x08108102 | 43        | 1.02%   |
| 0x706a8    | 35        | 0.83%   |
| 0x906e9    | 29        | 0.69%   |
| 0x6fb      | 27        | 0.64%   |
| 0x08600106 | 25        | 0.59%   |
| 0x05000101 | 23        | 0.55%   |
| 0x08608103 | 22        | 0.52%   |
| 0x05000119 | 22        | 0.52%   |
| 0xa0652    | 21        | 0.5%    |
| 0x406c3    | 20        | 0.48%   |
| 0x06001119 | 19        | 0.45%   |
| 0x0a50000c | 18        | 0.43%   |
| 0x0700010b | 18        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 538       | 12.79%  |
| KabyLake         | 465       | 11.05%  |
| IvyBridge        | 401       | 9.53%   |
| Penryn           | 361       | 8.58%   |
| Haswell          | 286       | 6.8%    |
| Westmere         | 277       | 6.58%   |
| Skylake          | 224       | 5.32%   |
| Core             | 210       | 4.99%   |
| Silvermont       | 207       | 4.92%   |
| Broadwell        | 156       | 3.71%   |
| Zen+             | 126       | 2.99%   |
| Bobcat           | 117       | 2.78%   |
| Excavator        | 87        | 2.07%   |
| Goldmont plus    | 83        | 1.97%   |
| Puma             | 77        | 1.83%   |
| IceLake          | 69        | 1.64%   |
| Zen 2            | 57        | 1.35%   |
| TigerLake        | 54        | 1.28%   |
| Goldmont         | 52        | 1.24%   |
| Zen              | 39        | 0.93%   |
| Piledriver       | 38        | 0.9%    |
| Unknown          | 38        | 0.9%    |
| Jaguar           | 34        | 0.81%   |
| K10              | 33        | 0.78%   |
| CometLake        | 30        | 0.71%   |
| K8 Hammer        | 29        | 0.69%   |
| Bonnell          | 27        | 0.64%   |
| Zen 3            | 24        | 0.57%   |
| K10 Llano        | 17        | 0.4%    |
| Nehalem          | 15        | 0.36%   |
| K8 & K10 hybrid  | 14        | 0.33%   |
| Tremont          | 11        | 0.26%   |
| Steamroller      | 10        | 0.24%   |
| Alderlake Hybrid | 2         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3078      | 62.11%  |
| AMD                              | 1005      | 20.28%  |
| Nvidia                           | 867       | 17.49%  |
| Silicon Integrated Systems [SiS] | 6         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 499       | 9.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 376       | 7.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 234       | 4.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 202       | 3.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 167       | 3.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 152       | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 142       | 2.75%   |
| Intel HD Graphics 5500                                                                   | 137       | 2.65%   |
| Intel HD Graphics 620                                                                    | 125       | 2.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 119       | 2.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 117       | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 117       | 2.27%   |
| Intel UHD Graphics 620                                                                   | 97        | 1.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 97        | 1.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 88        | 1.7%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 68        | 1.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 67        | 1.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 65        | 1.26%   |
| AMD Renoir                                                                               | 54        | 1.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 53        | 1.03%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 52        | 1.01%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 50        | 0.97%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 48        | 0.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 48        | 0.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 43        | 0.83%   |
| Intel HD Graphics 530                                                                    | 40        | 0.77%   |
| Intel HD Graphics 500                                                                    | 40        | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 40        | 0.77%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 35        | 0.68%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 34        | 0.66%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 33        | 0.64%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 29        | 0.56%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 28        | 0.54%   |
| AMD Lucienne                                                                             | 28        | 0.54%   |
| Intel HD Graphics 630                                                                    | 26        | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 25        | 0.48%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 24        | 0.46%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 23        | 0.45%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 23        | 0.45%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 22        | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 2351      | 55.87%  |
| 1 x AMD        | 753       | 17.89%  |
| Intel + Nvidia | 577       | 13.71%  |
| 1 x Nvidia     | 254       | 6.04%   |
| Intel + AMD    | 139       | 3.3%    |
| 2 x AMD        | 82        | 1.95%   |
| AMD + Nvidia   | 31        | 0.74%   |
| 2 x Intel      | 10        | 0.24%   |
| 1 x SiS        | 6         | 0.14%   |
| 2 x Nvidia     | 5         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4172      | 99.1%   |
| Unknown     | 35        | 0.83%   |
| Proprietary | 3         | 0.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2463      | 58.52%  |
| 0.01-0.5   | 712       | 16.92%  |
| 1.01-2.0   | 469       | 11.14%  |
| 0.51-1.0   | 359       | 8.53%   |
| 3.01-4.0   | 126       | 2.99%   |
| 5.01-6.0   | 40        | 0.95%   |
| 7.01-8.0   | 25        | 0.59%   |
| 2.01-3.0   | 13        | 0.31%   |
| 8.01-16.0  | 2         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 899       | 20.79%  |
| LG Display              | 744       | 17.21%  |
| Chimei Innolux          | 588       | 13.6%   |
| BOE                     | 561       | 12.97%  |
| Samsung Electronics     | 534       | 12.35%  |
| Chi Mei Optoelectronics | 167       | 3.86%   |
| CPT                     | 116       | 2.68%   |
| Lenovo                  | 112       | 2.59%   |
| Apple                   | 67        | 1.55%   |
| LG Philips              | 62        | 1.43%   |
| Sharp                   | 43        | 0.99%   |
| Eizo                    | 38        | 0.88%   |
| InfoVision              | 36        | 0.83%   |
| Dell                    | 34        | 0.79%   |
| Goldstar                | 33        | 0.76%   |
| PANDA                   | 26        | 0.6%    |
| Hewlett-Packard         | 25        | 0.58%   |
| Philips                 | 21        | 0.49%   |
| Acer                    | 21        | 0.49%   |
| Sony                    | 19        | 0.44%   |
| BenQ                    | 16        | 0.37%   |
| AOC                     | 16        | 0.37%   |
| Toshiba                 | 13        | 0.3%    |
| InnoLux Display         | 11        | 0.25%   |
| Iiyama                  | 11        | 0.25%   |
| Ancor Communications    | 8         | 0.19%   |
| ViewSonic               | 7         | 0.16%   |
| HannStar                | 7         | 0.16%   |
| CSO                     | 7         | 0.16%   |
| ASUSTek Computer        | 6         | 0.14%   |
| Vizio                   | 5         | 0.12%   |
| Unknown                 | 5         | 0.12%   |
| Panasonic               | 5         | 0.12%   |
| Fujitsu Siemens         | 5         | 0.12%   |
| Quanta Display          | 4         | 0.09%   |
| ___                     | 3         | 0.07%   |
| Vestel Elektronik       | 3         | 0.07%   |
| NEC Computers           | 3         | 0.07%   |
| Unknown (XXX)           | 2         | 0.05%   |
| Sceptre Tech            | 2         | 0.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 98        | 2.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 52        | 1.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 40        | 0.92%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 38        | 0.88%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 37        | 0.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 35        | 0.81%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 34        | 0.78%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 32        | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 32        | 0.74%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 29        | 0.67%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 29        | 0.67%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 27        | 0.62%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 26        | 0.6%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 25        | 0.58%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 23        | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.48%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch           | 20        | 0.46%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 20        | 0.46%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 19        | 0.44%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 19        | 0.44%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 18        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 18        | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 18        | 0.42%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 18        | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 17        | 0.39%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 17        | 0.39%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 17        | 0.39%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 17        | 0.39%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 16        | 0.37%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 16        | 0.37%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 16        | 0.37%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 16        | 0.37%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 15        | 0.35%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 15        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 15        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 15        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 15        | 0.35%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 15        | 0.35%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 15        | 0.35%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 15        | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 1970      | 46.36%  |
| 1920x1080 (FHD)    | 1180      | 27.77%  |
| 1600x900 (HD+)     | 418       | 9.84%   |
| 1280x800 (WXGA)    | 272       | 6.4%    |
| 1440x900 (WXGA+)   | 98        | 2.31%   |
| 3840x2160 (4K)     | 84        | 1.98%   |
| 1680x1050 (WSXGA+) | 38        | 0.89%   |
| 1920x1200 (WUXGA)  | 32        | 0.75%   |
| 2560x1440 (QHD)    | 31        | 0.73%   |
| 2560x1600          | 14        | 0.33%   |
| 1024x600           | 14        | 0.33%   |
| 1280x1024 (SXGA)   | 13        | 0.31%   |
| 3200x1800 (QHD+)   | 11        | 0.26%   |
| 1024x768 (XGA)     | 9         | 0.21%   |
| 1360x768           | 8         | 0.19%   |
| 2880x1800          | 7         | 0.16%   |
| 1680x945           | 7         | 0.16%   |
| 2256x1504          | 6         | 0.14%   |
| 2160x1440          | 5         | 0.12%   |
| 1920x1280          | 5         | 0.12%   |
| 2560x1080          | 3         | 0.07%   |
| 1920x540           | 3         | 0.07%   |
| 1400x1050          | 3         | 0.07%   |
| 3840x2400          | 2         | 0.05%   |
| 3456x2160          | 2         | 0.05%   |
| 2288x1287          | 2         | 0.05%   |
| 800x1280           | 1         | 0.02%   |
| 3840x1100          | 1         | 0.02%   |
| 3840x1080          | 1         | 0.02%   |
| 3440x1440          | 1         | 0.02%   |
| 3300x2200          | 1         | 0.02%   |
| 3200x2000          | 1         | 0.02%   |
| 3000x2000          | 1         | 0.02%   |
| 2304x1440          | 1         | 0.02%   |
| 2240x1400          | 1         | 0.02%   |
| 1600x1200          | 1         | 0.02%   |
| 1360x765           | 1         | 0.02%   |
| 1280x720 (HD)      | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2025      | 46.76%  |
| 13      | 714       | 16.49%  |
| 14      | 478       | 11.04%  |
| 17      | 430       | 9.93%   |
| 12      | 149       | 3.44%   |
| 11      | 99        | 2.29%   |
| 23      | 59        | 1.36%   |
| 31      | 53        | 1.22%   |
| 27      | 50        | 1.15%   |
| 24      | 40        | 0.92%   |
| 21      | 38        | 0.88%   |
| 18      | 36        | 0.83%   |
| 16      | 20        | 0.46%   |
| 10      | 20        | 0.46%   |
| 20      | 18        | 0.42%   |
| 19      | 14        | 0.32%   |
| 22      | 11        | 0.25%   |
| 54      | 10        | 0.23%   |
| 84      | 7         | 0.16%   |
| 72      | 6         | 0.14%   |
| 32      | 6         | 0.14%   |
| 26      | 6         | 0.14%   |
| 65      | 4         | 0.09%   |
| 34      | 4         | 0.09%   |
| 25      | 4         | 0.09%   |
| Unknown | 4         | 0.09%   |
| 48      | 3         | 0.07%   |
| 142     | 2         | 0.05%   |
| 74      | 2         | 0.05%   |
| 55      | 2         | 0.05%   |
| 47      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |
| 42      | 2         | 0.05%   |
| 40      | 2         | 0.05%   |
| 37      | 2         | 0.05%   |
| 50      | 1         | 0.02%   |
| 49      | 1         | 0.02%   |
| 39      | 1         | 0.02%   |
| 36      | 1         | 0.02%   |
| 33      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2791      | 64.62%  |
| 201-300        | 622       | 14.4%   |
| 351-400        | 522       | 12.09%  |
| 501-600        | 152       | 3.52%   |
| 401-500        | 107       | 2.48%   |
| 601-700        | 59        | 1.37%   |
| 1001-1500      | 25        | 0.58%   |
| 1501-2000      | 15        | 0.35%   |
| 701-800        | 12        | 0.28%   |
| 801-900        | 5         | 0.12%   |
| Unknown        | 4         | 0.09%   |
| More than 2000 | 2         | 0.05%   |
| 901-1000       | 2         | 0.05%   |
| 1-100          | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 3541      | 86.81%  |
| 16/10 | 470       | 11.52%  |
| 3/2   | 29        | 0.71%   |
| 4/3   | 16        | 0.39%   |
| 5/4   | 14        | 0.34%   |
| 21/9  | 4         | 0.1%    |
| 1.00  | 2         | 0.05%   |
| 32/9  | 1         | 0.02%   |
| 3.40  | 1         | 0.02%   |
| 0.67  | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2025      | 46.75%  |
| 81-90          | 879       | 20.29%  |
| 121-130        | 357       | 8.24%   |
| 71-80          | 311       | 7.18%   |
| 61-70          | 145       | 3.35%   |
| 201-250        | 132       | 3.05%   |
| 51-60          | 101       | 2.33%   |
| 131-140        | 69        | 1.59%   |
| 351-500        | 65        | 1.5%    |
| 301-350        | 52        | 1.2%    |
| 151-200        | 39        | 0.9%    |
| 141-150        | 39        | 0.9%    |
| More than 1000 | 37        | 0.85%   |
| 251-300        | 20        | 0.46%   |
| 41-50          | 19        | 0.44%   |
| 91-100         | 15        | 0.35%   |
| 501-1000       | 13        | 0.3%    |
| 111-120        | 9         | 0.21%   |
| Unknown        | 4         | 0.09%   |
| 1-40           | 1         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 2010      | 47.12%  |
| 121-160       | 1368      | 32.07%  |
| 51-100        | 650       | 15.24%  |
| 161-240       | 162       | 3.8%    |
| More than 240 | 36        | 0.84%   |
| 1-50          | 36        | 0.84%   |
| Unknown       | 4         | 0.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3855      | 91.57%  |
| 2     | 330       | 7.84%   |
| 0     | 19        | 0.45%   |
| 3     | 5         | 0.12%   |
| 4     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2278      | 33.12%  |
| Intel                             | 1800      | 26.17%  |
| Qualcomm Atheros                  | 1466      | 21.32%  |
| Broadcom                          | 467       | 6.79%   |
| Marvell Technology Group          | 133       | 1.93%   |
| Broadcom Limited                  | 112       | 1.63%   |
| Samsung Electronics               | 111       | 1.61%   |
| Ralink                            | 96        | 1.4%    |
| JMicron Technology                | 47        | 0.68%   |
| Dell                              | 42        | 0.61%   |
| Huawei Technologies               | 40        | 0.58%   |
| Ericsson Business Mobile Networks | 34        | 0.49%   |
| MediaTek                          | 30        | 0.44%   |
| Nvidia                            | 26        | 0.38%   |
| TP-Link                           | 24        | 0.35%   |
| Ralink Technology                 | 23        | 0.33%   |
| Sierra Wireless                   | 15        | 0.22%   |
| Hewlett-Packard                   | 12        | 0.17%   |
| Qualcomm Atheros Communications   | 11        | 0.16%   |
| Xiaomi                            | 10        | 0.15%   |
| ASIX Electronics                  | 10        | 0.15%   |
| Motorola PCS                      | 9         | 0.13%   |
| D-Link                            | 8         | 0.12%   |
| Silicon Integrated Systems [SiS]  | 6         | 0.09%   |
| DisplayLink                       | 6         | 0.09%   |
| Qualcomm                          | 5         | 0.07%   |
| Linksys                           | 5         | 0.07%   |
| NetGear                           | 4         | 0.06%   |
| OPPO Electronics                  | 3         | 0.04%   |
| Google                            | 3         | 0.04%   |
| Belkin Components                 | 3         | 0.04%   |
| AVM                               | 3         | 0.04%   |
| ASUSTek Computer                  | 3         | 0.04%   |
| T & A Mobile Phones               | 2         | 0.03%   |
| Sitecom Europe                    | 2         | 0.03%   |
| Shenzhen Goodix Technology        | 2         | 0.03%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.03%   |
| Lenovo                            | 2         | 0.03%   |
| ICS Advent                        | 2         | 0.03%   |
| Edimax Technology                 | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1310      | 15.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 608       | 7.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 274       | 3.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 264       | 3.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 242       | 2.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 221       | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 209       | 2.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 156       | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 137       | 1.67%   |
| Intel Wireless 7265                                                     | 124       | 1.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 114       | 1.39%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 107       | 1.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 106       | 1.29%   |
| Intel Wireless 8265 / 8275                                              | 95        | 1.16%   |
| Intel Wireless 7260                                                     | 93        | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 91        | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 81        | 0.99%   |
| Intel Wireless 8260                                                     | 77        | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 76        | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 74        | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 74        | 0.9%    |
| Intel 82577LM Gigabit Network Connection                                | 72        | 0.88%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 71        | 0.87%   |
| Intel Wireless 3165                                                     | 70        | 0.85%   |
| Intel WiFi Link 5100                                                    | 70        | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 69        | 0.84%   |
| Intel Wi-Fi 6 AX200                                                     | 67        | 0.82%   |
| Intel Wireless 3160                                                     | 63        | 0.77%   |
| Intel Centrino Advanced-N 6200                                          | 63        | 0.77%   |
| Intel 82567LM Gigabit Network Connection                                | 61        | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 55        | 0.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 54        | 0.66%   |
| Intel Centrino Ultimate-N 6300                                          | 53        | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 51        | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 50        | 0.61%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 50        | 0.61%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 49        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 48        | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 46        | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                           | 45        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1701      | 39.48%  |
| Qualcomm Atheros                  | 1293      | 30.01%  |
| Realtek Semiconductor             | 719       | 16.69%  |
| Broadcom                          | 307       | 7.13%   |
| Ralink                            | 96        | 2.23%   |
| Broadcom Limited                  | 52        | 1.21%   |
| MediaTek                          | 25        | 0.58%   |
| Ralink Technology                 | 23        | 0.53%   |
| Dell                              | 23        | 0.53%   |
| Sierra Wireless                   | 15        | 0.35%   |
| Qualcomm Atheros Communications   | 11        | 0.26%   |
| TP-Link                           | 8         | 0.19%   |
| Ericsson Business Mobile Networks | 5         | 0.12%   |
| D-Link                            | 5         | 0.12%   |
| Linksys                           | 4         | 0.09%   |
| Hewlett-Packard                   | 3         | 0.07%   |
| Belkin Components                 | 3         | 0.07%   |
| AVM                               | 3         | 0.07%   |
| ASUSTek Computer                  | 3         | 0.07%   |
| NetGear                           | 2         | 0.05%   |
| Edimax Technology                 | 2         | 0.05%   |
| D-Link System                     | 2         | 0.05%   |
| Sitecom Europe                    | 1         | 0.02%   |
| Senao                             | 1         | 0.02%   |
| Qcom                              | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 274       | 6.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 264       | 6.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 242       | 5.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 221       | 5.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 156       | 3.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 137       | 3.17%   |
| Intel Wireless 7265                                                     | 124       | 2.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 114       | 2.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 106       | 2.45%   |
| Intel Wireless 8265 / 8275                                              | 95        | 2.2%    |
| Intel Wireless 7260                                                     | 93        | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 91        | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 81        | 1.88%   |
| Intel Wireless 8260                                                     | 77        | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 74        | 1.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 71        | 1.64%   |
| Intel Wireless 3165                                                     | 70        | 1.62%   |
| Intel WiFi Link 5100                                                    | 70        | 1.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 69        | 1.6%    |
| Intel Wi-Fi 6 AX200                                                     | 67        | 1.55%   |
| Intel Wireless 3160                                                     | 63        | 1.46%   |
| Intel Centrino Advanced-N 6200                                          | 63        | 1.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 55        | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 54        | 1.25%   |
| Intel Centrino Ultimate-N 6300                                          | 53        | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 51        | 1.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 50        | 1.16%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 50        | 1.16%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 49        | 1.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 48        | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 46        | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                           | 45        | 1.04%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 43        | 1%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 42        | 0.97%   |
| Intel Centrino Wireless-N 2230                                          | 42        | 0.97%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 40        | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 38        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 37        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 36        | 0.83%   |
| Intel Wi-Fi 6 AX201                                                     | 32        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2017      | 53.22%  |
| Intel                            | 682       | 17.99%  |
| Qualcomm Atheros                 | 350       | 9.23%   |
| Broadcom                         | 229       | 6.04%   |
| Marvell Technology Group         | 133       | 3.51%   |
| Samsung Electronics              | 111       | 2.93%   |
| Broadcom Limited                 | 62        | 1.64%   |
| JMicron Technology               | 47        | 1.24%   |
| Huawei Technologies              | 35        | 0.92%   |
| Nvidia                           | 25        | 0.66%   |
| TP-Link                          | 16        | 0.42%   |
| Xiaomi                           | 10        | 0.26%   |
| ASIX Electronics                 | 10        | 0.26%   |
| Motorola PCS                     | 7         | 0.18%   |
| Silicon Integrated Systems [SiS] | 6         | 0.16%   |
| DisplayLink                      | 6         | 0.16%   |
| Qualcomm                         | 5         | 0.13%   |
| MediaTek                         | 5         | 0.13%   |
| Hewlett-Packard                  | 4         | 0.11%   |
| OPPO Electronics                 | 3         | 0.08%   |
| Google                           | 3         | 0.08%   |
| D-Link                           | 3         | 0.08%   |
| T & A Mobile Phones              | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.05%   |
| NetGear                          | 2         | 0.05%   |
| Lenovo                           | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| Apple                            | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| Spreadtrum Communications        | 1         | 0.03%   |
| Sitecom Europe                   | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| HTC (High Tech Computer)         | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |
| Attansic Technology              | 1         | 0.03%   |
| Archos                           | 1         | 0.03%   |
| Allwinner Technology             | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1310      | 34.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 608       | 15.95%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 209       | 5.48%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 107       | 2.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 76        | 1.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 74        | 1.94%   |
| Intel 82577LM Gigabit Network Connection                                       | 72        | 1.89%   |
| Intel 82567LM Gigabit Network Connection                                       | 61        | 1.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 43        | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                                          | 42        | 1.1%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 41        | 1.08%   |
| Intel Ethernet Connection I218-LM                                              | 38        | 1%      |
| Intel Ethernet Connection I219-LM                                              | 37        | 0.97%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 34        | 0.89%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 32        | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 31        | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 30        | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 29        | 0.76%   |
| Intel Ethernet Connection I217-LM                                              | 29        | 0.76%   |
| Huawei E353/E3131                                                              | 29        | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 28        | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 28        | 0.73%   |
| Intel 82566MM Gigabit Network Connection                                       | 27        | 0.71%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 27        | 0.71%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 27        | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 24        | 0.63%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 23        | 0.6%    |
| Intel 82579V Gigabit Network Connection                                        | 23        | 0.6%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 22        | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                                          | 22        | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 22        | 0.58%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 19        | 0.5%    |
| Intel Ethernet Connection I219-V                                               | 18        | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 18        | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 16        | 0.42%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 15        | 0.39%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 14        | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 14        | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 14        | 0.37%   |
| Nvidia MCP79 Ethernet                                                          | 14        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4177      | 52.53%  |
| Ethernet | 3706      | 46.6%   |
| Modem    | 64        | 0.8%    |
| Unknown  | 5         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2826      | 68.43%  |
| Ethernet | 1304      | 31.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3386      | 80.47%  |
| 1     | 778       | 18.49%  |
| 0     | 28        | 0.67%   |
| 3     | 16        | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3139      | 74.53%  |
| Yes  | 1073      | 25.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1028      | 34.84%  |
| Qualcomm Atheros Communications | 394       | 13.35%  |
| Realtek Semiconductor           | 325       | 11.01%  |
| Broadcom                        | 248       | 8.4%    |
| Lite-On Technology              | 208       | 7.05%   |
| IMC Networks                    | 144       | 4.88%   |
| Foxconn / Hon Hai               | 127       | 4.3%    |
| Dell                            | 92        | 3.12%   |
| Toshiba                         | 71        | 2.41%   |
| Apple                           | 65        | 2.2%    |
| Hewlett-Packard                 | 57        | 1.93%   |
| Ralink                          | 42        | 1.42%   |
| Cambridge Silicon Radio         | 39        | 1.32%   |
| Realtek                         | 17        | 0.58%   |
| ASUSTek Computer                | 16        | 0.54%   |
| Foxconn International           | 15        | 0.51%   |
| Ralink Technology               | 13        | 0.44%   |
| Alps Electric                   | 13        | 0.44%   |
| Chicony Electronics             | 11        | 0.37%   |
| Askey Computer                  | 7         | 0.24%   |
| Taiyo Yuden                     | 4         | 0.14%   |
| Fujitsu                         | 4         | 0.14%   |
| Micro Star International        | 3         | 0.1%    |
| MediaTek                        | 3         | 0.1%    |
| USI                             | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| D-Link System                   | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 549       | 18.6%   |
| Realtek Bluetooth Radio                                                             | 200       | 6.78%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 183       | 6.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 140       | 4.74%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 90        | 3.05%   |
| Intel AX201 Bluetooth                                                               | 86        | 2.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 78        | 2.64%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 69        | 2.34%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 68        | 2.3%    |
| Intel AX200 Bluetooth                                                               | 67        | 2.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 65        | 2.2%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 59        | 2%      |
| Lite-On Atheros AR3012 Bluetooth                                                    | 52        | 1.76%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 52        | 1.76%   |
| IMC Networks Bluetooth Radio                                                        | 49        | 1.66%   |
| Lite-On Bluetooth Device                                                            | 46        | 1.56%   |
| IMC Networks Bluetooth Device                                                       | 46        | 1.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 43        | 1.46%   |
| Ralink RT3290 Bluetooth                                                             | 42        | 1.42%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 42        | 1.42%   |
| Dell DW375 Bluetooth Module                                                         | 42        | 1.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 39        | 1.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 39        | 1.32%   |
| Apple Bluetooth Host Controller                                                     | 38        | 1.29%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 37        | 1.25%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 32        | 1.08%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 30        | 1.02%   |
| Realtek RTL8723B Bluetooth                                                          | 27        | 0.91%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 26        | 0.88%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 24        | 0.81%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 24        | 0.81%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 23        | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 21        | 0.71%   |
| Toshiba Bluetooth Device                                                            | 20        | 0.68%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 20        | 0.68%   |
| Apple Bluetooth USB Host Controller                                                 | 20        | 0.68%   |
| Broadcom HP Portable SoftSailing                                                    | 18        | 0.61%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 18        | 0.61%   |
| Realtek Bluetooth Radio                                                             | 17        | 0.58%   |
| Broadcom BCM2045 Bluetooth                                                          | 17        | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3435      | 71.1%   |
| AMD                                          | 854       | 17.68%  |
| Nvidia                                       | 460       | 9.52%   |
| Logitech                                     | 11        | 0.23%   |
| C-Media Electronics                          | 7         | 0.14%   |
| Silicon Integrated Systems [SiS]             | 6         | 0.12%   |
| Realtek Semiconductor                        | 6         | 0.12%   |
| JMTek                                        | 6         | 0.12%   |
| Generalplus Technology                       | 5         | 0.1%    |
| Texas Instruments                            | 4         | 0.08%   |
| Creative Technology                          | 4         | 0.08%   |
| Lenovo                                       | 3         | 0.06%   |
| Plantronics                                  | 2         | 0.04%   |
| M-Audio                                      | 2         | 0.04%   |
| Focusrite-Novation                           | 2         | 0.04%   |
| Conexant Systems                             | 2         | 0.04%   |
| ASUSTek Computer                             | 2         | 0.04%   |
| Apple                                        | 2         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| XMOS                                         | 1         | 0.02%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.02%   |
| TerraTec Electronic                          | 1         | 0.02%   |
| TEAC                                         | 1         | 0.02%   |
| Schiit Audio                                 | 1         | 0.02%   |
| Samsung Electronics                          | 1         | 0.02%   |
| Samson Technologies                          | 1         | 0.02%   |
| Razer USA                                    | 1         | 0.02%   |
| Phison Electronics                           | 1         | 0.02%   |
| Native Instruments                           | 1         | 0.02%   |
| GN Netcom                                    | 1         | 0.02%   |
| ESS Technology                               | 1         | 0.02%   |
| Elitegroup Computer Systems (ECS)            | 1         | 0.02%   |
| Dell                                         | 1         | 0.02%   |
| Cambridge Audio                              | 1         | 0.02%   |
| Bose                                         | 1         | 0.02%   |
| AudioQuest                                   | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 500       | 8.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 439       | 7.43%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 428       | 7.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 320       | 5.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 292       | 4.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 273       | 4.62%   |
| AMD FCH Azalia Controller                                                                         | 214       | 3.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 194       | 3.28%   |
| Intel 8 Series HD Audio Controller                                                                | 169       | 2.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 167       | 2.82%   |
| Intel Broadwell-U Audio Controller                                                                | 156       | 2.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 155       | 2.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 153       | 2.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 139       | 2.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 130       | 2.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 119       | 2.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 118       | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 101       | 1.71%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 97        | 1.64%   |
| AMD Wrestler HDMI Audio                                                                           | 95        | 1.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 87        | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 86        | 1.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 86        | 1.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 82        | 1.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 73        | 1.23%   |
| AMD High Definition Audio Controller                                                              | 68        | 1.15%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 64        | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 57        | 0.96%   |
| Intel Cannon Lake PCH cAVS                                                                        | 57        | 0.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 54        | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 52        | 0.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 49        | 0.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 47        | 0.79%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 40        | 0.68%   |
| AMD Trinity HDMI Audio Controller                                                                 | 38        | 0.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 32        | 0.54%   |
| Intel CM238 HD Audio Controller                                                                   | 31        | 0.52%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 30        | 0.51%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 29        | 0.49%   |
| Nvidia High Definition Audio Controller                                                           | 28        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1340      | 26.55%  |
| SK hynix            | 1059      | 20.98%  |
| Micron Technology   | 473       | 9.37%   |
| Unknown             | 468       | 9.27%   |
| Kingston            | 443       | 8.78%   |
| Elpida              | 241       | 4.78%   |
| Crucial             | 154       | 3.05%   |
| Ramaxel Technology  | 133       | 2.64%   |
| A-DATA Technology   | 124       | 2.46%   |
| Nanya Technology    | 102       | 2.02%   |
| Smart               | 80        | 1.59%   |
| Corsair             | 50        | 0.99%   |
| Unknown (ABCD)      | 44        | 0.87%   |
| G.Skill             | 27        | 0.53%   |
| ASint Technology    | 25        | 0.5%    |
| Teikon              | 22        | 0.44%   |
| Unknown             | 22        | 0.44%   |
| Transcend           | 17        | 0.34%   |
| High Bridge         | 17        | 0.34%   |
| Apacer              | 16        | 0.32%   |
| Patriot             | 15        | 0.3%    |
| AMD                 | 14        | 0.28%   |
| Team                | 13        | 0.26%   |
| Toshiba             | 12        | 0.24%   |
| Smart Brazil        | 11        | 0.22%   |
| Qimonda             | 11        | 0.22%   |
| Goodram             | 7         | 0.14%   |
| CSX                 | 7         | 0.14%   |
| Silicon Power       | 6         | 0.12%   |
| Multilaser          | 5         | 0.1%    |
| SHARETRONIC         | 4         | 0.08%   |
| PNY                 | 4         | 0.08%   |
| Kingmax             | 4         | 0.08%   |
| Goldkey             | 4         | 0.08%   |
| Avant               | 4         | 0.08%   |
| 48spaces            | 4         | 0.08%   |
| Qumo                | 3         | 0.06%   |
| HT Micron           | 3         | 0.06%   |
| Carry               | 3         | 0.06%   |
| Unknown (8A02)      | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 106       | 1.96%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 100       | 1.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 92        | 1.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 88        | 1.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 79        | 1.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 76        | 1.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 75        | 1.39%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 73        | 1.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 68        | 1.26%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 52        | 0.96%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 52        | 0.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 50        | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 49        | 0.91%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 45        | 0.83%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 42        | 0.78%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 40        | 0.74%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 40        | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 39        | 0.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 39        | 0.72%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 36        | 0.67%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 35        | 0.65%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 35        | 0.65%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 33        | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 33        | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 33        | 0.61%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 32        | 0.59%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 32        | 0.59%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 32        | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 31        | 0.57%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 29        | 0.54%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 29        | 0.54%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 28        | 0.52%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 27        | 0.5%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 26        | 0.48%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 26        | 0.48%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 25        | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 24        | 0.44%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 23        | 0.43%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 23        | 0.43%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 23        | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 2290      | 54.56%  |
| DDR4    | 1100      | 26.21%  |
| DDR2    | 428       | 10.2%   |
| SDRAM   | 137       | 3.26%   |
| LPDDR4  | 122       | 2.91%   |
| LPDDR3  | 42        | 1%      |
| Unknown | 41        | 0.98%   |
| DRAM    | 20        | 0.48%   |
| DDR     | 13        | 0.31%   |
| LPDDR5  | 2         | 0.05%   |
| DDR5    | 2         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3980      | 95.79%  |
| Row Of Chips | 135       | 3.25%   |
| Chip         | 18        | 0.43%   |
| DIMM         | 15        | 0.36%   |
| Unknown      | 7         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 2135      | 45.85%  |
| 2048  | 1123      | 24.12%  |
| 8192  | 1006      | 21.61%  |
| 1024  | 204       | 4.38%   |
| 16384 | 153       | 3.29%   |
| 32768 | 28        | 0.6%    |
| 512   | 7         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 1440      | 30.69%  |
| 2667    | 599       | 12.77%  |
| 1334    | 458       | 9.76%   |
| 1333    | 383       | 8.16%   |
| 2400    | 311       | 6.63%   |
| 3200    | 258       | 5.5%    |
| 667     | 227       | 4.84%   |
| 1067    | 156       | 3.32%   |
| Unknown | 148       | 3.15%   |
| 2133    | 127       | 2.71%   |
| 800     | 117       | 2.49%   |
| 4199    | 76        | 1.62%   |
| 3266    | 73        | 1.56%   |
| 2048    | 52        | 1.11%   |
| 975     | 49        | 1.04%   |
| 1867    | 46        | 0.98%   |
| 1066    | 44        | 0.94%   |
| 533     | 31        | 0.66%   |
| 4267    | 23        | 0.49%   |
| 1866    | 14        | 0.3%    |
| 8400    | 10        | 0.21%   |
| 4266    | 10        | 0.21%   |
| 1639    | 8         | 0.17%   |
| 333     | 8         | 0.17%   |
| 3733    | 4         | 0.09%   |
| 2933    | 4         | 0.09%   |
| 400     | 3         | 0.06%   |
| 6400    | 2         | 0.04%   |
| 4800    | 2         | 0.04%   |
| 2267    | 2         | 0.04%   |
| 1200    | 2         | 0.04%   |
| 266     | 2         | 0.04%   |
| 1776    | 1         | 0.02%   |
| 933     | 1         | 0.02%   |
| 666     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 17        | 41.46%  |
| Canon                 | 7         | 17.07%  |
| Brother Industries    | 6         | 14.63%  |
| Samsung Electronics   | 5         | 12.2%   |
| Seiko Epson           | 4         | 9.76%   |
| Xerox                 | 1         | 2.44%   |
| Lexmark International | 1         | 2.44%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Brother DCP-7055W                       | 4         | 9.76%   |
| Samsung ML-1640 Series Laser Printer    | 2         | 4.88%   |
| HP LaserJet 1020                        | 2         | 4.88%   |
| HP DeskJet 3630 series                  | 2         | 4.88%   |
| Canon PIXMA MG2500 Series               | 2         | 4.88%   |
| Xerox Phaser 6000B                      | 1         | 2.44%   |
| Seiko Epson L312 Series                 | 1         | 2.44%   |
| Seiko Epson L222 Series                 | 1         | 2.44%   |
| Seiko Epson L210 Series                 | 1         | 2.44%   |
| Seiko Epson ET-2710 Series              | 1         | 2.44%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 2.44%   |
| Samsung SCX-3400 Series                 | 1         | 2.44%   |
| Samsung M2070 Series                    | 1         | 2.44%   |
| Lexmark International E360d             | 1         | 2.44%   |
| HP OfficeJet Pro 69                     | 1         | 2.44%   |
| HP OfficeJet 4300                       | 1         | 2.44%   |
| HP LaserJet P1102                       | 1         | 2.44%   |
| HP LaserJet 200 colorMFP M275nw         | 1         | 2.44%   |
| HP LaserJet 1018                        | 1         | 2.44%   |
| HP ENVY Photo 6200 series               | 1         | 2.44%   |
| HP ENVY 6000 series                     | 1         | 2.44%   |
| HP ENVY 4520 series                     | 1         | 2.44%   |
| HP DeskJet D1360                        | 1         | 2.44%   |
| HP DeskJet 6122                         | 1         | 2.44%   |
| HP DeskJet 2300 series                  | 1         | 2.44%   |
| HP DeskJet 2130 series                  | 1         | 2.44%   |
| HP Deskjet 2050 J510                    | 1         | 2.44%   |
| Canon PIXMA MP280                       | 1         | 2.44%   |
| Canon PIXMA MG3500 Series               | 1         | 2.44%   |
| Canon MP160                             | 1         | 2.44%   |
| Canon LBP2900                           | 1         | 2.44%   |
| Canon G3000 series                      | 1         | 2.44%   |
| Brother MFC-J5330DW                     | 1         | 2.44%   |
| Brother DCP-L3550CDW                    | 1         | 2.44%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 42.86%  |
| Seiko Epson     | 2         | 28.57%  |
| Hewlett-Packard | 2         | 28.57%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| HP ScanJet 5590                                          | 2         | 28.57%  |
| Seiko Epson Scanner                                      | 1         | 14.29%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 14.29%  |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 14.29%  |
| Canon CanoScan LiDE 600F                                 | 1         | 14.29%  |
| Canon CanoScan LiDE 110                                  | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 987       | 28.03%  |
| Realtek Semiconductor                  | 301       | 8.55%   |
| Microdia                               | 291       | 8.26%   |
| IMC Networks                           | 275       | 7.81%   |
| Acer                                   | 249       | 7.07%   |
| Suyin                                  | 243       | 6.9%    |
| Sunplus Innovation Technology          | 178       | 5.06%   |
| Cheng Uei Precision Industry (Foxlink) | 156       | 4.43%   |
| Quanta                                 | 139       | 3.95%   |
| Syntek                                 | 113       | 3.21%   |
| Lite-On Technology                     | 79        | 2.24%   |
| Silicon Motion                         | 77        | 2.19%   |
| Ricoh                                  | 77        | 2.19%   |
| Alcor Micro                            | 60        | 1.7%    |
| Apple                                  | 53        | 1.51%   |
| Lenovo                                 | 40        | 1.14%   |
| Importek                               | 29        | 0.82%   |
| ALi                                    | 29        | 0.82%   |
| Luxvisions Innotech Limited            | 26        | 0.74%   |
| Primax Electronics                     | 24        | 0.68%   |
| DigiTech                               | 16        | 0.45%   |
| Z-Star Microelectronics                | 11        | 0.31%   |
| OmniVision Technologies                | 10        | 0.28%   |
| Sonix Technology                       | 9         | 0.26%   |
| Logitech                               | 7         | 0.2%    |
| Genesys Logic                          | 5         | 0.14%   |
| Sunplus Technology                     | 4         | 0.11%   |
| Samsung Electronics                    | 3         | 0.09%   |
| Nebraska Furniture Mart                | 3         | 0.09%   |
| GEMBIRD                                | 3         | 0.09%   |
| Foxconn / Hon Hai                      | 3         | 0.09%   |
| Cubeternet                             | 3         | 0.09%   |
| WaveRider Communications               | 2         | 0.06%   |
| Intel                                  | 2         | 0.06%   |
| Unknown                                | 1         | 0.03%   |
| Tobii Technology AB                    | 1         | 0.03%   |
| SunplusIT                              | 1         | 0.03%   |
| Pixart Imaging                         | 1         | 0.03%   |
| Novatek Microelectronics               | 1         | 0.03%   |
| Nokia Mobile Phones                    | 1         | 0.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                       | 106       | 3.01%   |
| Chicony Integrated Camera                               | 103       | 2.92%   |
| Microdia Integrated_Webcam_HD                           | 86        | 2.44%   |
| Realtek Integrated_Webcam_HD                            | 67        | 1.9%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 58        | 1.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 53        | 1.5%    |
| Chicony USB 2.0 Camera                                  | 53        | 1.5%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 47        | 1.33%   |
| Sunplus Integrated_Webcam_HD                            | 45        | 1.28%   |
| Microdia Integrated Webcam                              | 45        | 1.28%   |
| Acer Lenovo EasyCamera                                  | 45        | 1.28%   |
| Chicony VGA WebCam                                      | 44        | 1.25%   |
| Realtek USB Camera                                      | 42        | 1.19%   |
| Syntek Integrated Camera                                | 39        | 1.11%   |
| IMC Networks Integrated Camera                          | 38        | 1.08%   |
| Chicony USB2.0 HD UVC WebCam                            | 37        | 1.05%   |
| Chicony TOSHIBA Web Camera - HD                         | 36        | 1.02%   |
| Acer Integrated Camera                                  | 35        | 0.99%   |
| Chicony USB2.0 VGA UVC WebCam                           | 34        | 0.96%   |
| Chicony Lenovo EasyCamera                               | 34        | 0.96%   |
| Chicony HP TrueVision HD                                | 34        | 0.96%   |
| Sunplus HD WebCam                                       | 33        | 0.94%   |
| Syntek Lenovo EasyCamera                                | 32        | 0.91%   |
| Suyin Integrated_Webcam_HD                              | 31        | 0.88%   |
| Chicony EasyCamera                                      | 31        | 0.88%   |
| Acer Lenovo Integrated Webcam                           | 30        | 0.85%   |
| Lite-On Integrated Camera                               | 28        | 0.79%   |
| Chicony FJ Camera                                       | 28        | 0.79%   |
| Quanta HP Webcam                                        | 26        | 0.74%   |
| Chicony HP Truevision HD camera                         | 26        | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 26        | 0.74%   |
| Chicony HP Webcam                                       | 25        | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 25        | 0.71%   |
| Acer EasyCamera                                         | 25        | 0.71%   |
| IMC Networks UVC VGA Webcam                             | 24        | 0.68%   |
| Syntek EasyCamera                                       | 23        | 0.65%   |
| Quanta VGA WebCam                                       | 23        | 0.65%   |
| Quanta HP TrueVision HD Camera                          | 23        | 0.65%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 23        | 0.65%   |
| Apple Built-in iSight                                   | 23        | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 177       | 38.99%  |
| AuthenTec                  | 77        | 16.96%  |
| Upek                       | 49        | 10.79%  |
| Synaptics                  | 35        | 7.71%   |
| Elan Microelectronics      | 35        | 7.71%   |
| Shenzhen Goodix Technology | 30        | 6.61%   |
| LighTuning Technology      | 24        | 5.29%   |
| STMicroelectronics         | 23        | 5.07%   |
| Focal-systems.Corp         | 2         | 0.44%   |
| Samsung Electronics        | 1         | 0.22%   |
| HOLTEK                     | 1         | 0.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 44        | 9.69%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 34        | 7.49%   |
| AuthenTec AES2810                                                          | 28        | 6.17%   |
| Shenzhen Goodix  FingerPrint Device                                        | 25        | 5.51%   |
| STMicroelectronics Fingerprint Reader                                      | 23        | 5.07%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 22        | 4.85%   |
| Elan ELAN:Fingerprint                                                      | 21        | 4.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 21        | 4.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 4.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 17        | 3.74%   |
| Validity Sensors VFS491                                                    | 16        | 3.52%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 3.08%   |
| Elan ELAN:ARM-M4                                                           | 14        | 3.08%   |
| AuthenTec AES1600                                                          | 12        | 2.64%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 2.42%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.42%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 2.2%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 10        | 2.2%    |
| AuthenTec Fingerprint Sensor                                               | 10        | 2.2%    |
| Validity Sensors Fingerprint scanner                                       | 8         | 1.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 1.76%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 7         | 1.54%   |
| Synaptics  WBDI                                                            | 7         | 1.54%   |
| Unknown                                                                    | 7         | 1.54%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 1.32%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 1.1%    |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.88%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.88%   |
| Synaptics WBDI Device                                                      | 3         | 0.66%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.66%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.66%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 0.66%   |
| LighTuning Fingerprint Reader                                              | 3         | 0.66%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.44%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 0.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.44%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 0.44%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 0.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 148       | 55.02%  |
| O2 Micro              | 39        | 14.5%   |
| Alcor Micro           | 34        | 12.64%  |
| Lenovo                | 21        | 7.81%   |
| Upek                  | 20        | 7.43%   |
| SCM Microsystems      | 3         | 1.12%   |
| OmniKey               | 1         | 0.37%   |
| Microchip Technology  | 1         | 0.37%   |
| Hewlett-Packard       | 1         | 0.37%   |
| Gemalto (was Gemplus) | 1         | 0.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 84        | 31.23%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 38        | 14.13%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 38        | 14.13%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 33        | 12.27%  |
| Lenovo Integrated Smart Card Reader                                          | 21        | 7.81%   |
| Broadcom 5880                                                                | 21        | 7.81%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 20        | 7.43%   |
| Broadcom 58200                                                               | 5         | 1.86%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 1.12%   |
| OmniKey CardMan 4321                                                         | 1         | 0.37%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.37%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.37%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.37%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.37%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.37%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3271      | 77.7%   |
| 1     | 800       | 19%     |
| 2     | 130       | 3.09%   |
| 3     | 8         | 0.19%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 454       | 42.35%  |
| Chipcard                 | 263       | 24.53%  |
| Graphics card            | 92        | 8.58%   |
| Net/wireless             | 68        | 6.34%   |
| Bluetooth                | 64        | 5.97%   |
| Storage                  | 56        | 5.22%   |
| Multimedia controller    | 29        | 2.71%   |
| Camera                   | 20        | 1.87%   |
| Communication controller | 9         | 0.84%   |
| Flash memory             | 5         | 0.47%   |
| Sound                    | 4         | 0.37%   |
| Network                  | 4         | 0.37%   |
| Card reader              | 3         | 0.28%   |
| Modem                    | 1         | 0.09%   |

