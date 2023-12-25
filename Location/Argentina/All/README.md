Linux in Argentina - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Argentina.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Argentina/Desktop/README.md) and [notebooks](/Location/Argentina/Notebook/README.md).

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

Total: 3022

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | NF725M-P43                  | Desktop     | [43756d6fad](https://linux-hardware.org/?probe=43756d6fad) | Dec 21, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [c8c0737175](https://linux-hardware.org/?probe=c8c0737175) | Dec 20, 2023 |
| Dell          | Latitude 3420               | Notebook    | [35a3241602](https://linux-hardware.org/?probe=35a3241602) | Dec 20, 2023 |
| Clevo         | W240BU                      | Notebook    | [a0d883bb3d](https://linux-hardware.org/?probe=a0d883bb3d) | Dec 20, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [55a83cf2cb](https://linux-hardware.org/?probe=55a83cf2cb) | Dec 19, 2023 |
| MSI           | MEG Z690 UNIFY              | Desktop     | [33f139b941](https://linux-hardware.org/?probe=33f139b941) | Dec 19, 2023 |
| ASUSTek       | Q304UAK                     | Convertible | [fab514effd](https://linux-hardware.org/?probe=fab514effd) | Dec 18, 2023 |
| System76      | Lemur Pro                   | Notebook    | [85b70f2fdb](https://linux-hardware.org/?probe=85b70f2fdb) | Dec 18, 2023 |
| Dell          | Latitude 3420               | Notebook    | [59784d2788](https://linux-hardware.org/?probe=59784d2788) | Dec 18, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [52f641256c](https://linux-hardware.org/?probe=52f641256c) | Dec 18, 2023 |
| System76      | Lemur Pro                   | Notebook    | [6ec95bc2bc](https://linux-hardware.org/?probe=6ec95bc2bc) | Dec 17, 2023 |
| Lenovo        | ThinkPad T440p 20AWA0W9A... | Notebook    | [e97e362650](https://linux-hardware.org/?probe=e97e362650) | Dec 17, 2023 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | Notebook    | [3834ee3d70](https://linux-hardware.org/?probe=3834ee3d70) | Dec 15, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [313b058c8c](https://linux-hardware.org/?probe=313b058c8c) | Dec 14, 2023 |
| ECS           | G41T-M                      | Desktop     | [a0017f196c](https://linux-hardware.org/?probe=a0017f196c) | Dec 14, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [e1deaf47e9](https://linux-hardware.org/?probe=e1deaf47e9) | Dec 14, 2023 |
| Lenovo        | ThinkPad X201 3626W1P       | Notebook    | [bf54dfd215](https://linux-hardware.org/?probe=bf54dfd215) | Dec 13, 2023 |
| Lenovo        | ThinkPad X201 3626W1P       | Notebook    | [695a85cd79](https://linux-hardware.org/?probe=695a85cd79) | Dec 12, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [68ba082c42](https://linux-hardware.org/?probe=68ba082c42) | Dec 12, 2023 |
| NVN-ED01      | Unknown                     | Notebook    | [3705f36f2b](https://linux-hardware.org/?probe=3705f36f2b) | Dec 11, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bc892e5d3b](https://linux-hardware.org/?probe=bc892e5d3b) | Dec 09, 2023 |
| HP            | Compaq 515                  | Notebook    | [025d4116ed](https://linux-hardware.org/?probe=025d4116ed) | Dec 09, 2023 |
| Lenovo        | G470 20078                  | Notebook    | [190ba583a3](https://linux-hardware.org/?probe=190ba583a3) | Dec 09, 2023 |
| System76      | Lemur Pro                   | Notebook    | [c8313d9e6f](https://linux-hardware.org/?probe=c8313d9e6f) | Dec 07, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [d1288cac0c](https://linux-hardware.org/?probe=d1288cac0c) | Dec 07, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [108ddf7f8e](https://linux-hardware.org/?probe=108ddf7f8e) | Dec 07, 2023 |
| Exo           | Smart XQ7                   | Notebook    | [f1ebc77dfc](https://linux-hardware.org/?probe=f1ebc77dfc) | Dec 05, 2023 |
| Exo           | Smart XQ7                   | Notebook    | [3d56eb720e](https://linux-hardware.org/?probe=3d56eb720e) | Dec 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6d4537080b](https://linux-hardware.org/?probe=6d4537080b) | Dec 05, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [8d46bb6a3c](https://linux-hardware.org/?probe=8d46bb6a3c) | Dec 05, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [578cbbda94](https://linux-hardware.org/?probe=578cbbda94) | Dec 05, 2023 |
| Intel         | ChiefRiver                  | Desktop     | [6a4b7aebe9](https://linux-hardware.org/?probe=6a4b7aebe9) | Dec 05, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [b71e5d49a4](https://linux-hardware.org/?probe=b71e5d49a4) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S3ED18    | Notebook    | [03866b12cd](https://linux-hardware.org/?probe=03866b12cd) | Dec 04, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [638021e67d](https://linux-hardware.org/?probe=638021e67d) | Dec 04, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [ce304df98f](https://linux-hardware.org/?probe=ce304df98f) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d25f6b4dd3](https://linux-hardware.org/?probe=d25f6b4dd3) | Dec 02, 2023 |
| Gigabyte      | GA-E6010N                   | Desktop     | [f36369aec0](https://linux-hardware.org/?probe=f36369aec0) | Dec 02, 2023 |
| Gigabyte      | A520M AORUS ELITE           | Desktop     | [ae6274f798](https://linux-hardware.org/?probe=ae6274f798) | Nov 30, 2023 |
| Kelyx Arge... | Kelyx KL3450                | Notebook    | [0d6ca3bd1a](https://linux-hardware.org/?probe=0d6ca3bd1a) | Nov 30, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ea1580fdae](https://linux-hardware.org/?probe=ea1580fdae) | Nov 28, 2023 |
| Gigabyte      | A55M-DS2                    | Desktop     | [bb5c7bef3f](https://linux-hardware.org/?probe=bb5c7bef3f) | Nov 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [d848c8ed0e](https://linux-hardware.org/?probe=d848c8ed0e) | Nov 27, 2023 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [23f26e0c45](https://linux-hardware.org/?probe=23f26e0c45) | Nov 27, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [fdfc56bb5f](https://linux-hardware.org/?probe=fdfc56bb5f) | Nov 26, 2023 |
| Lenovo        | IdeaPad Slim 3 14IAN8 82... | Notebook    | [7eed706de5](https://linux-hardware.org/?probe=7eed706de5) | Nov 26, 2023 |
| Gigabyte      | AM1M-S2H                    | Desktop     | [c3bdc08988](https://linux-hardware.org/?probe=c3bdc08988) | Nov 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | Notebook    | [06170c8841](https://linux-hardware.org/?probe=06170c8841) | Nov 25, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [be0df0a38d](https://linux-hardware.org/?probe=be0df0a38d) | Nov 25, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [5ead75f7bc](https://linux-hardware.org/?probe=5ead75f7bc) | Nov 25, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [d781187df4](https://linux-hardware.org/?probe=d781187df4) | Nov 24, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [c397c51bfb](https://linux-hardware.org/?probe=c397c51bfb) | Nov 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [7caae1b1a0](https://linux-hardware.org/?probe=7caae1b1a0) | Nov 24, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [65c6061eb3](https://linux-hardware.org/?probe=65c6061eb3) | Nov 23, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [eeae51d065](https://linux-hardware.org/?probe=eeae51d065) | Nov 23, 2023 |
| System76      | Lemur Pro                   | Notebook    | [45a6298cb5](https://linux-hardware.org/?probe=45a6298cb5) | Nov 22, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [df5747727b](https://linux-hardware.org/?probe=df5747727b) | Nov 22, 2023 |
| Grupo Nucl... | Eurocase MB40               | Notebook    | [aaedd81604](https://linux-hardware.org/?probe=aaedd81604) | Nov 21, 2023 |
| Grupo Nucl... | Eurocase MB40               | Notebook    | [6c601d96d9](https://linux-hardware.org/?probe=6c601d96d9) | Nov 21, 2023 |
| MSI           | G31M3                       | Desktop     | [d9e2a5683a](https://linux-hardware.org/?probe=d9e2a5683a) | Nov 20, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [82c49fc608](https://linux-hardware.org/?probe=82c49fc608) | Nov 19, 2023 |
| BANGHO        | Suma 1025                   | Tablet      | [a933d36c63](https://linux-hardware.org/?probe=a933d36c63) | Nov 18, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [079ab24f27](https://linux-hardware.org/?probe=079ab24f27) | Nov 17, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [1a59332837](https://linux-hardware.org/?probe=1a59332837) | Nov 17, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [da8f5fa2e5](https://linux-hardware.org/?probe=da8f5fa2e5) | Nov 17, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [3c0851b65b](https://linux-hardware.org/?probe=3c0851b65b) | Nov 17, 2023 |
| Samsung       | R430/R480/R440              | Notebook    | [0c90ddcfcf](https://linux-hardware.org/?probe=0c90ddcfcf) | Nov 15, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [0c9c1b8513](https://linux-hardware.org/?probe=0c9c1b8513) | Nov 15, 2023 |
| BANGHO        | 1025                        | Notebook    | [d1d51fc17a](https://linux-hardware.org/?probe=d1d51fc17a) | Nov 15, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [b158de590e](https://linux-hardware.org/?probe=b158de590e) | Nov 14, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [25455f055b](https://linux-hardware.org/?probe=25455f055b) | Nov 14, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [780d61593a](https://linux-hardware.org/?probe=780d61593a) | Nov 14, 2023 |
| MSI           | MS-7309                     | Desktop     | [c6ca259cae](https://linux-hardware.org/?probe=c6ca259cae) | Nov 13, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [fe9c673ae1](https://linux-hardware.org/?probe=fe9c673ae1) | Nov 13, 2023 |
| BANGHO        | 1025                        | Notebook    | [97b39ed05d](https://linux-hardware.org/?probe=97b39ed05d) | Nov 13, 2023 |
| Advantec      | CX23500W                    | Notebook    | [30382192a1](https://linux-hardware.org/?probe=30382192a1) | Nov 11, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | Notebook    | [46e69016d1](https://linux-hardware.org/?probe=46e69016d1) | Nov 11, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [6406ede8d4](https://linux-hardware.org/?probe=6406ede8d4) | Nov 11, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [2b545ce55f](https://linux-hardware.org/?probe=2b545ce55f) | Nov 10, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | Notebook    | [1e2c26c06a](https://linux-hardware.org/?probe=1e2c26c06a) | Nov 09, 2023 |
| Exo           | Intel powered classmate ... | Notebook    | [135b2008b7](https://linux-hardware.org/?probe=135b2008b7) | Nov 09, 2023 |
| Sony          | SVF15N17CXB                 | Notebook    | [e8497bf6f6](https://linux-hardware.org/?probe=e8497bf6f6) | Nov 08, 2023 |
| System76      | Lemur Pro                   | Notebook    | [92d1345459](https://linux-hardware.org/?probe=92d1345459) | Nov 07, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [25b39b698c](https://linux-hardware.org/?probe=25b39b698c) | Nov 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [f5cd797cc8](https://linux-hardware.org/?probe=f5cd797cc8) | Nov 05, 2023 |
| Lenovo        | S145-15IWL 81MV             | Notebook    | [d38fdaf0eb](https://linux-hardware.org/?probe=d38fdaf0eb) | Nov 04, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [3f631dfb6e](https://linux-hardware.org/?probe=3f631dfb6e) | Nov 04, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e7d16a3fc2](https://linux-hardware.org/?probe=e7d16a3fc2) | Nov 03, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5ac9818b1f](https://linux-hardware.org/?probe=5ac9818b1f) | Nov 03, 2023 |
| BANGHO        | Suma 1025                   | Tablet      | [a0ed1238ea](https://linux-hardware.org/?probe=a0ed1238ea) | Nov 03, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [fbbb34a0cb](https://linux-hardware.org/?probe=fbbb34a0cb) | Nov 03, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [e1edc2410b](https://linux-hardware.org/?probe=e1edc2410b) | Nov 03, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [43a85c50bf](https://linux-hardware.org/?probe=43a85c50bf) | Nov 02, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2d1120d99a](https://linux-hardware.org/?probe=2d1120d99a) | Nov 02, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [59d963de5b](https://linux-hardware.org/?probe=59d963de5b) | Nov 02, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8c9de8be4f](https://linux-hardware.org/?probe=8c9de8be4f) | Nov 02, 2023 |
| HP            | Pavilion g6                 | Notebook    | [c35f9a55aa](https://linux-hardware.org/?probe=c35f9a55aa) | Nov 02, 2023 |
| PCChips       | P49G                        | Desktop     | [6b1de00356](https://linux-hardware.org/?probe=6b1de00356) | Nov 02, 2023 |
| Novatech      | C141EK5-CI5TX               | Notebook    | [ee65041e06](https://linux-hardware.org/?probe=ee65041e06) | Nov 01, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [af59fd3af9](https://linux-hardware.org/?probe=af59fd3af9) | Nov 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [847ae1ea8d](https://linux-hardware.org/?probe=847ae1ea8d) | Nov 01, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [7296b22122](https://linux-hardware.org/?probe=7296b22122) | Oct 31, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [9775caad00](https://linux-hardware.org/?probe=9775caad00) | Oct 31, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [45280b44d0](https://linux-hardware.org/?probe=45280b44d0) | Oct 31, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [f6db4cc5a7](https://linux-hardware.org/?probe=f6db4cc5a7) | Oct 31, 2023 |
| Lenovo        | ThinkPad X230 2325T55       | Notebook    | [bb4d04c61d](https://linux-hardware.org/?probe=bb4d04c61d) | Oct 31, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [35fabc6811](https://linux-hardware.org/?probe=35fabc6811) | Oct 31, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [eccf9444b3](https://linux-hardware.org/?probe=eccf9444b3) | Oct 31, 2023 |
| Dell          | Precision M6800             | Notebook    | [a5e2100522](https://linux-hardware.org/?probe=a5e2100522) | Oct 29, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [df6ef51245](https://linux-hardware.org/?probe=df6ef51245) | Oct 28, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [9dad78d2eb](https://linux-hardware.org/?probe=9dad78d2eb) | Oct 27, 2023 |
| System76      | Lemur Pro                   | Notebook    | [e5b2c76907](https://linux-hardware.org/?probe=e5b2c76907) | Oct 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [acc4051b9c](https://linux-hardware.org/?probe=acc4051b9c) | Oct 26, 2023 |
| Exo           | Smart Serie R               | Notebook    | [d68b300ca7](https://linux-hardware.org/?probe=d68b300ca7) | Oct 26, 2023 |
| Novatech      | C141EK5-CI5TX               | Notebook    | [71f7f1372a](https://linux-hardware.org/?probe=71f7f1372a) | Oct 26, 2023 |
| Intel         | H61                         | Desktop     | [cb396f193e](https://linux-hardware.org/?probe=cb396f193e) | Oct 26, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [b66ca0672b](https://linux-hardware.org/?probe=b66ca0672b) | Oct 25, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [64908ddca3](https://linux-hardware.org/?probe=64908ddca3) | Oct 25, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [a71b3ca73a](https://linux-hardware.org/?probe=a71b3ca73a) | Oct 24, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [2100dab18e](https://linux-hardware.org/?probe=2100dab18e) | Oct 23, 2023 |
| Toshiba       | Satellite L635              | Notebook    | [6bc7726e0e](https://linux-hardware.org/?probe=6bc7726e0e) | Oct 22, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [f6a5fcd391](https://linux-hardware.org/?probe=f6a5fcd391) | Oct 21, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [150a11b476](https://linux-hardware.org/?probe=150a11b476) | Oct 21, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [673aa81f04](https://linux-hardware.org/?probe=673aa81f04) | Oct 21, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2fb4202e3f](https://linux-hardware.org/?probe=2fb4202e3f) | Oct 21, 2023 |
| BANGHO        | M7x0K                       | Notebook    | [1f72eb6b91](https://linux-hardware.org/?probe=1f72eb6b91) | Oct 20, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [821b9544cf](https://linux-hardware.org/?probe=821b9544cf) | Oct 19, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [b02f1b04e3](https://linux-hardware.org/?probe=b02f1b04e3) | Oct 19, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [9998c3eea0](https://linux-hardware.org/?probe=9998c3eea0) | Oct 19, 2023 |
| Positivo      | AT300b                      | Notebook    | [a39989b55b](https://linux-hardware.org/?probe=a39989b55b) | Oct 18, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [0566ab2287](https://linux-hardware.org/?probe=0566ab2287) | Oct 18, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [bb941b90f8](https://linux-hardware.org/?probe=bb941b90f8) | Oct 18, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [ea7e37eb5d](https://linux-hardware.org/?probe=ea7e37eb5d) | Oct 17, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [61c4ebff0f](https://linux-hardware.org/?probe=61c4ebff0f) | Oct 16, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [b0adb13b97](https://linux-hardware.org/?probe=b0adb13b97) | Oct 16, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [6b4c286aca](https://linux-hardware.org/?probe=6b4c286aca) | Oct 16, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [3a8e72ab3b](https://linux-hardware.org/?probe=3a8e72ab3b) | Oct 15, 2023 |
| System76      | Lemur Pro                   | Notebook    | [f969d7a459](https://linux-hardware.org/?probe=f969d7a459) | Oct 15, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [8625166ef3](https://linux-hardware.org/?probe=8625166ef3) | Oct 14, 2023 |
| Sony          | VAIO                        | All in one  | [653a82e6b9](https://linux-hardware.org/?probe=653a82e6b9) | Oct 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [0d088b07f0](https://linux-hardware.org/?probe=0d088b07f0) | Oct 14, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a03109d57a](https://linux-hardware.org/?probe=a03109d57a) | Oct 14, 2023 |
| Novatech      | C141EK5-CI5TX               | Notebook    | [798d514e79](https://linux-hardware.org/?probe=798d514e79) | Oct 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4d6379353d](https://linux-hardware.org/?probe=4d6379353d) | Oct 13, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [99092f3766](https://linux-hardware.org/?probe=99092f3766) | Oct 12, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [0723750e07](https://linux-hardware.org/?probe=0723750e07) | Oct 12, 2023 |
| ECS           | H61H2-M2                    | Desktop     | [a06a09b119](https://linux-hardware.org/?probe=a06a09b119) | Oct 12, 2023 |
| MSI           | A68HM-E33                   | Desktop     | [71c8888ea4](https://linux-hardware.org/?probe=71c8888ea4) | Oct 12, 2023 |
| Compal        | PCW20                       | Notebook    | [94330b69a9](https://linux-hardware.org/?probe=94330b69a9) | Oct 11, 2023 |
| Gigabyte      | Z690 UD AX DDR4             | Desktop     | [78f21c3253](https://linux-hardware.org/?probe=78f21c3253) | Oct 10, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [801a2a4abf](https://linux-hardware.org/?probe=801a2a4abf) | Oct 09, 2023 |
| Biostar       | A320MH                      | Desktop     | [73bce2d7a8](https://linux-hardware.org/?probe=73bce2d7a8) | Oct 08, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [ad00ca7536](https://linux-hardware.org/?probe=ad00ca7536) | Oct 07, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [192654dc77](https://linux-hardware.org/?probe=192654dc77) | Oct 06, 2023 |
| Lenovo        | 100-14IBY 80R7              | Notebook    | [f6389f0244](https://linux-hardware.org/?probe=f6389f0244) | Oct 06, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4b7adf3cf6](https://linux-hardware.org/?probe=4b7adf3cf6) | Oct 06, 2023 |
| Exo           | Smart Serie L               | Notebook    | [812041d985](https://linux-hardware.org/?probe=812041d985) | Oct 05, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [6a56e8a819](https://linux-hardware.org/?probe=6a56e8a819) | Oct 05, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [84d68335c3](https://linux-hardware.org/?probe=84d68335c3) | Oct 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [a6849f7516](https://linux-hardware.org/?probe=a6849f7516) | Oct 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b978b6c62f](https://linux-hardware.org/?probe=b978b6c62f) | Oct 03, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [a8875273fb](https://linux-hardware.org/?probe=a8875273fb) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [4462bfcb6d](https://linux-hardware.org/?probe=4462bfcb6d) | Oct 02, 2023 |
| System76      | Lemur Pro                   | Notebook    | [8486fb3080](https://linux-hardware.org/?probe=8486fb3080) | Oct 02, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1e825c5574](https://linux-hardware.org/?probe=1e825c5574) | Oct 01, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [b2b359c659](https://linux-hardware.org/?probe=b2b359c659) | Sep 30, 2023 |
| ASUSTek       | Z450LA                      | Notebook    | [afa96a084e](https://linux-hardware.org/?probe=afa96a084e) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [b4a58da74c](https://linux-hardware.org/?probe=b4a58da74c) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [ccb9b4e795](https://linux-hardware.org/?probe=ccb9b4e795) | Sep 30, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [b867aa1824](https://linux-hardware.org/?probe=b867aa1824) | Sep 30, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e2560d6378](https://linux-hardware.org/?probe=e2560d6378) | Sep 30, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [306bc123c4](https://linux-hardware.org/?probe=306bc123c4) | Sep 29, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [af9350dd38](https://linux-hardware.org/?probe=af9350dd38) | Sep 28, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [d40624877e](https://linux-hardware.org/?probe=d40624877e) | Sep 28, 2023 |
| System76      | Lemur Pro                   | Notebook    | [6013ab7f8a](https://linux-hardware.org/?probe=6013ab7f8a) | Sep 27, 2023 |
| Gigabyte      | GA-880GM-USB3L              | Desktop     | [f160911c14](https://linux-hardware.org/?probe=f160911c14) | Sep 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [92eb612b66](https://linux-hardware.org/?probe=92eb612b66) | Sep 26, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [742cfeafb0](https://linux-hardware.org/?probe=742cfeafb0) | Sep 26, 2023 |
| AIR           | CX28000W                    | Notebook    | [b4a65a0403](https://linux-hardware.org/?probe=b4a65a0403) | Sep 26, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [355aaa1b07](https://linux-hardware.org/?probe=355aaa1b07) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | Notebook    | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [44c939ded2](https://linux-hardware.org/?probe=44c939ded2) | Sep 26, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [79309ad820](https://linux-hardware.org/?probe=79309ad820) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a834cee874](https://linux-hardware.org/?probe=a834cee874) | Sep 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [0e22f551b9](https://linux-hardware.org/?probe=0e22f551b9) | Sep 24, 2023 |
| Dell          | Latitude 3410               | Notebook    | [c5473f5f6c](https://linux-hardware.org/?probe=c5473f5f6c) | Sep 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [c4b66b8208](https://linux-hardware.org/?probe=c4b66b8208) | Sep 23, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [80928b2dc9](https://linux-hardware.org/?probe=80928b2dc9) | Sep 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [290e0fd96b](https://linux-hardware.org/?probe=290e0fd96b) | Sep 21, 2023 |
| ASUSTek       | X455LD                      | Notebook    | [1e79e3536c](https://linux-hardware.org/?probe=1e79e3536c) | Sep 20, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [6861d58ee0](https://linux-hardware.org/?probe=6861d58ee0) | Sep 20, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0c71c0240e](https://linux-hardware.org/?probe=0c71c0240e) | Sep 20, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [e4dae2f7c8](https://linux-hardware.org/?probe=e4dae2f7c8) | Sep 19, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [79e8bd0911](https://linux-hardware.org/?probe=79e8bd0911) | Sep 19, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [fe4ef48e82](https://linux-hardware.org/?probe=fe4ef48e82) | Sep 19, 2023 |
| ECS           | H61H2-M2                    | Desktop     | [fe16b7a5a1](https://linux-hardware.org/?probe=fe16b7a5a1) | Sep 19, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [67e6231304](https://linux-hardware.org/?probe=67e6231304) | Sep 18, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9c94944d56](https://linux-hardware.org/?probe=9c94944d56) | Sep 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [5fa6a632ae](https://linux-hardware.org/?probe=5fa6a632ae) | Sep 18, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [fa9bd484cd](https://linux-hardware.org/?probe=fa9bd484cd) | Sep 17, 2023 |
| Unknown       | X79M2-Q                     | Desktop     | [670ca9e147](https://linux-hardware.org/?probe=670ca9e147) | Sep 17, 2023 |
| BANGHO        | Suma 1025                   | Tablet      | [755399496c](https://linux-hardware.org/?probe=755399496c) | Sep 16, 2023 |
| ASRock        | B650E Steel Legend WiFi     | Desktop     | [0f87ffad72](https://linux-hardware.org/?probe=0f87ffad72) | Sep 15, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [f9e5e93aba](https://linux-hardware.org/?probe=f9e5e93aba) | Sep 15, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [994cdaee5b](https://linux-hardware.org/?probe=994cdaee5b) | Sep 15, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [2d0ccc33ef](https://linux-hardware.org/?probe=2d0ccc33ef) | Sep 15, 2023 |
| ASUSTek       | P5N72-T PREMIUM             | Desktop     | [e5afd4ceda](https://linux-hardware.org/?probe=e5afd4ceda) | Sep 13, 2023 |
| ASUSTek       | M3N78-VM                    | Desktop     | [79e5a35fa4](https://linux-hardware.org/?probe=79e5a35fa4) | Sep 12, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [e793b9e3d9](https://linux-hardware.org/?probe=e793b9e3d9) | Sep 12, 2023 |
| ASRock        | H570M Pro4                  | Desktop     | [4124ca4b35](https://linux-hardware.org/?probe=4124ca4b35) | Sep 10, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [7c04fe4f52](https://linux-hardware.org/?probe=7c04fe4f52) | Sep 10, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [cd512452f9](https://linux-hardware.org/?probe=cd512452f9) | Sep 09, 2023 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [edb578f198](https://linux-hardware.org/?probe=edb578f198) | Sep 09, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [fc7937d763](https://linux-hardware.org/?probe=fc7937d763) | Sep 09, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [2385447c50](https://linux-hardware.org/?probe=2385447c50) | Sep 07, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [8d4c48dd2f](https://linux-hardware.org/?probe=8d4c48dd2f) | Sep 06, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [eb05baece5](https://linux-hardware.org/?probe=eb05baece5) | Sep 05, 2023 |
| System76      | Lemur Pro                   | Notebook    | [9ea11da090](https://linux-hardware.org/?probe=9ea11da090) | Sep 04, 2023 |
| Gigabyte      | B550M K                     | Desktop     | [95d0f9505b](https://linux-hardware.org/?probe=95d0f9505b) | Sep 03, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [70172e3461](https://linux-hardware.org/?probe=70172e3461) | Sep 03, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [af96cda252](https://linux-hardware.org/?probe=af96cda252) | Sep 02, 2023 |
| Dell          | Latitude 5285               | Notebook    | [f1f48163f3](https://linux-hardware.org/?probe=f1f48163f3) | Sep 02, 2023 |
| SiS           | M672 Board SI94B-20+SI96... | Notebook    | [4b309ad43c](https://linux-hardware.org/?probe=4b309ad43c) | Sep 02, 2023 |
| Biostar       | N68S3B                      | Desktop     | [fc063709f7](https://linux-hardware.org/?probe=fc063709f7) | Sep 02, 2023 |
| Biostar       | A320MH                      | Desktop     | [8791e4dd20](https://linux-hardware.org/?probe=8791e4dd20) | Sep 02, 2023 |
| Intel         | powered classmate PC        | Notebook    | [f852524db2](https://linux-hardware.org/?probe=f852524db2) | Sep 01, 2023 |
| BGH           | C46G                        | Notebook    | [c56474510e](https://linux-hardware.org/?probe=c56474510e) | Sep 01, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [0e82099e8f](https://linux-hardware.org/?probe=0e82099e8f) | Sep 01, 2023 |
| Positivo      | ONE500                      | Desktop     | [1e84a5bf44](https://linux-hardware.org/?probe=1e84a5bf44) | Aug 31, 2023 |
| BANGHO        | GM-15Z12 RTX3060 i7         | Notebook    | [4e77460452](https://linux-hardware.org/?probe=4e77460452) | Aug 31, 2023 |
| HP            | 3115m                       | Notebook    | [85325be2ba](https://linux-hardware.org/?probe=85325be2ba) | Aug 31, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [c222da255e](https://linux-hardware.org/?probe=c222da255e) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [33b5107930](https://linux-hardware.org/?probe=33b5107930) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d169572a6b](https://linux-hardware.org/?probe=d169572a6b) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bd35d44f1](https://linux-hardware.org/?probe=2bd35d44f1) | Aug 29, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [c8bed4c7e6](https://linux-hardware.org/?probe=c8bed4c7e6) | Aug 29, 2023 |
| BANGHO        | Suma 1025                   | Tablet      | [fd3953acee](https://linux-hardware.org/?probe=fd3953acee) | Aug 28, 2023 |
| ASRock        | AM1B-M                      | Desktop     | [d35e6acf9a](https://linux-hardware.org/?probe=d35e6acf9a) | Aug 28, 2023 |
| NSX           | SB142G                      | Notebook    | [43b576c576](https://linux-hardware.org/?probe=43b576c576) | Aug 27, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [08748d2c86](https://linux-hardware.org/?probe=08748d2c86) | Aug 27, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [78df724503](https://linux-hardware.org/?probe=78df724503) | Aug 26, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [7da367fdec](https://linux-hardware.org/?probe=7da367fdec) | Aug 25, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [a45010b5bb](https://linux-hardware.org/?probe=a45010b5bb) | Aug 25, 2023 |
| ASRock        | AM1B-M                      | Desktop     | [fe8df93529](https://linux-hardware.org/?probe=fe8df93529) | Aug 25, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [7486221845](https://linux-hardware.org/?probe=7486221845) | Aug 23, 2023 |
| Lenovo        | ThinkPad E495 20NES0KM00    | Notebook    | [783db5b84d](https://linux-hardware.org/?probe=783db5b84d) | Aug 23, 2023 |
| Biostar       | B450MH                      | Desktop     | [21f8924d2c](https://linux-hardware.org/?probe=21f8924d2c) | Aug 23, 2023 |
| BANGHO        | Suma 1025                   | Tablet      | [5dab721f9a](https://linux-hardware.org/?probe=5dab721f9a) | Aug 21, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [a8ec62d51f](https://linux-hardware.org/?probe=a8ec62d51f) | Aug 21, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [64d2950d7a](https://linux-hardware.org/?probe=64d2950d7a) | Aug 21, 2023 |
| Dell          | Inspiron 5447               | Notebook    | [811b2451ba](https://linux-hardware.org/?probe=811b2451ba) | Aug 20, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [f3151f84cb](https://linux-hardware.org/?probe=f3151f84cb) | Aug 20, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [2ba4151315](https://linux-hardware.org/?probe=2ba4151315) | Aug 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6249529a81](https://linux-hardware.org/?probe=6249529a81) | Aug 18, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [d4849fe5f4](https://linux-hardware.org/?probe=d4849fe5f4) | Aug 18, 2023 |
| Biostar       | A68MHE                      | Desktop     | [9295c879b8](https://linux-hardware.org/?probe=9295c879b8) | Aug 18, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [0ba07cce6b](https://linux-hardware.org/?probe=0ba07cce6b) | Aug 17, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [06aebc0204](https://linux-hardware.org/?probe=06aebc0204) | Aug 17, 2023 |
| System76      | Lemur Pro                   | Notebook    | [af3b387574](https://linux-hardware.org/?probe=af3b387574) | Aug 16, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [bb4bf558dd](https://linux-hardware.org/?probe=bb4bf558dd) | Aug 15, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [19221dff96](https://linux-hardware.org/?probe=19221dff96) | Aug 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b53cba2654](https://linux-hardware.org/?probe=b53cba2654) | Aug 15, 2023 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [f059d25382](https://linux-hardware.org/?probe=f059d25382) | Aug 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [15b52f0cde](https://linux-hardware.org/?probe=15b52f0cde) | Aug 14, 2023 |
| BANGHO        | MOV                         | Notebook    | [db4769bd96](https://linux-hardware.org/?probe=db4769bd96) | Aug 13, 2023 |
| Sony          | VAIO                        | All in one  | [a134fd35ac](https://linux-hardware.org/?probe=a134fd35ac) | Aug 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [3bb3eaed7b](https://linux-hardware.org/?probe=3bb3eaed7b) | Aug 13, 2023 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [eedc2f2406](https://linux-hardware.org/?probe=eedc2f2406) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [e03e2f8abc](https://linux-hardware.org/?probe=e03e2f8abc) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [f7ab4aa00a](https://linux-hardware.org/?probe=f7ab4aa00a) | Aug 12, 2023 |
| BANGHO        | BES T5                      | Notebook    | [9631e13d8b](https://linux-hardware.org/?probe=9631e13d8b) | Aug 12, 2023 |
| MSI           | A55M-E33                    | Desktop     | [7d538db764](https://linux-hardware.org/?probe=7d538db764) | Aug 12, 2023 |
| MSI           | A55M-E33                    | Desktop     | [9e64865fbc](https://linux-hardware.org/?probe=9e64865fbc) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [73f0314b31](https://linux-hardware.org/?probe=73f0314b31) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [d1a19f992d](https://linux-hardware.org/?probe=d1a19f992d) | Aug 12, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [607103b8f5](https://linux-hardware.org/?probe=607103b8f5) | Aug 11, 2023 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [88fcbf292a](https://linux-hardware.org/?probe=88fcbf292a) | Aug 10, 2023 |
| BANGHO        | MAX L5                      | Notebook    | [4661b7a0f7](https://linux-hardware.org/?probe=4661b7a0f7) | Aug 10, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [b95e28ab5d](https://linux-hardware.org/?probe=b95e28ab5d) | Aug 09, 2023 |
| DEXP          | Aquilon C14                 | Notebook    | [08d7c1d923](https://linux-hardware.org/?probe=08d7c1d923) | Aug 09, 2023 |
| BANGHO        | MAX L5                      | Notebook    | [b21781af81](https://linux-hardware.org/?probe=b21781af81) | Aug 08, 2023 |
| MSI           | Z270 PC MATE                | Desktop     | [aa107173a1](https://linux-hardware.org/?probe=aa107173a1) | Aug 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [40b0ea74b1](https://linux-hardware.org/?probe=40b0ea74b1) | Aug 07, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [4323af2ade](https://linux-hardware.org/?probe=4323af2ade) | Aug 07, 2023 |
| Sony          | VAIO                        | All in one  | [e924df8ac8](https://linux-hardware.org/?probe=e924df8ac8) | Aug 07, 2023 |
| Sony          | VAIO                        | All in one  | [8349b185e4](https://linux-hardware.org/?probe=8349b185e4) | Aug 07, 2023 |
| Acer          | Aspire 5551                 | Notebook    | [4db1866796](https://linux-hardware.org/?probe=4db1866796) | Aug 06, 2023 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [763d98ad86](https://linux-hardware.org/?probe=763d98ad86) | Aug 06, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [6622cd2887](https://linux-hardware.org/?probe=6622cd2887) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [44556227ff](https://linux-hardware.org/?probe=44556227ff) | Aug 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [e2dee68ce7](https://linux-hardware.org/?probe=e2dee68ce7) | Aug 05, 2023 |
| HP            | Pavilion g6                 | Notebook    | [fafbd706de](https://linux-hardware.org/?probe=fafbd706de) | Aug 05, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [d930261042](https://linux-hardware.org/?probe=d930261042) | Aug 04, 2023 |
| Toshiba       | Satellite L505              | Notebook    | [bab52bec2c](https://linux-hardware.org/?probe=bab52bec2c) | Aug 04, 2023 |
| ASUSTek       | M4A785T-M                   | Desktop     | [f297c8efa8](https://linux-hardware.org/?probe=f297c8efa8) | Aug 04, 2023 |
| GFAST         | N150                        | Notebook    | [bccc2874df](https://linux-hardware.org/?probe=bccc2874df) | Aug 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8767df67f4](https://linux-hardware.org/?probe=8767df67f4) | Aug 02, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [8c4c50cef9](https://linux-hardware.org/?probe=8c4c50cef9) | Aug 02, 2023 |
| System76      | Lemur Pro                   | Notebook    | [1ba844bc69](https://linux-hardware.org/?probe=1ba844bc69) | Aug 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [e019d33faf](https://linux-hardware.org/?probe=e019d33faf) | Aug 01, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [483fbca861](https://linux-hardware.org/?probe=483fbca861) | Jul 31, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| Gigabyte      | B550M AORUS PRO AX          | Desktop     | [f53eed4658](https://linux-hardware.org/?probe=f53eed4658) | Jul 28, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [37440e19b5](https://linux-hardware.org/?probe=37440e19b5) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [f321614376](https://linux-hardware.org/?probe=f321614376) | Jul 25, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [b731684f10](https://linux-hardware.org/?probe=b731684f10) | Jul 25, 2023 |
| Positivo      | G800                        | Notebook    | [5dd0f188f8](https://linux-hardware.org/?probe=5dd0f188f8) | Jul 25, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [849a99d897](https://linux-hardware.org/?probe=849a99d897) | Jul 25, 2023 |
| Dell          | Latitude E5410              | Notebook    | [e26148754b](https://linux-hardware.org/?probe=e26148754b) | Jul 25, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [fe2ff0c21f](https://linux-hardware.org/?probe=fe2ff0c21f) | Jul 23, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [21edb88f94](https://linux-hardware.org/?probe=21edb88f94) | Jul 23, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [9c64742080](https://linux-hardware.org/?probe=9c64742080) | Jul 23, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [be58f943df](https://linux-hardware.org/?probe=be58f943df) | Jul 22, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [b6432541ed](https://linux-hardware.org/?probe=b6432541ed) | Jul 21, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [243f0a8cab](https://linux-hardware.org/?probe=243f0a8cab) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [f310abe0bb](https://linux-hardware.org/?probe=f310abe0bb) | Jul 20, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [69a0cd41e0](https://linux-hardware.org/?probe=69a0cd41e0) | Jul 20, 2023 |
| Dell          | Latitude 3520               | Notebook    | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a5359c62e0](https://linux-hardware.org/?probe=a5359c62e0) | Jul 20, 2023 |
| Dell          | Latitude 3520               | Notebook    | [e41e794381](https://linux-hardware.org/?probe=e41e794381) | Jul 20, 2023 |
| Dell          | Latitude 3520               | Notebook    | [bd2589c749](https://linux-hardware.org/?probe=bd2589c749) | Jul 20, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e6bbbc4d41](https://linux-hardware.org/?probe=e6bbbc4d41) | Jul 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2f067394f6](https://linux-hardware.org/?probe=2f067394f6) | Jul 19, 2023 |
| Dell          | XPS L501X                   | Notebook    | [0879ff6b9d](https://linux-hardware.org/?probe=0879ff6b9d) | Jul 18, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [b986a103da](https://linux-hardware.org/?probe=b986a103da) | Jul 18, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [801b25d335](https://linux-hardware.org/?probe=801b25d335) | Jul 18, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [a58b13cf37](https://linux-hardware.org/?probe=a58b13cf37) | Jul 17, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [692ba8a4af](https://linux-hardware.org/?probe=692ba8a4af) | Jul 17, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | Notebook    | [2294cf035b](https://linux-hardware.org/?probe=2294cf035b) | Jul 16, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | Notebook    | [b26a172e92](https://linux-hardware.org/?probe=b26a172e92) | Jul 16, 2023 |
| HP            | 3396                        | Desktop     | [5713dca497](https://linux-hardware.org/?probe=5713dca497) | Jul 15, 2023 |
| Intel         | D425KT AAE93083-400         | Mini pc     | [dc0f48314d](https://linux-hardware.org/?probe=dc0f48314d) | Jul 15, 2023 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [571080a9d5](https://linux-hardware.org/?probe=571080a9d5) | Jul 14, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [19fdd69149](https://linux-hardware.org/?probe=19fdd69149) | Jul 14, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [cbdd93f7d6](https://linux-hardware.org/?probe=cbdd93f7d6) | Jul 14, 2023 |
| AIR           | CX30500                     | Notebook    | [ee0b27d980](https://linux-hardware.org/?probe=ee0b27d980) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d16093199e](https://linux-hardware.org/?probe=d16093199e) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1a0add8887](https://linux-hardware.org/?probe=1a0add8887) | Jul 11, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [0549d09ceb](https://linux-hardware.org/?probe=0549d09ceb) | Jul 11, 2023 |
| Acer          | SF714-52T                   | Notebook    | [97b079be51](https://linux-hardware.org/?probe=97b079be51) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [8fb942eccd](https://linux-hardware.org/?probe=8fb942eccd) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [ff650dc0df](https://linux-hardware.org/?probe=ff650dc0df) | Jul 10, 2023 |
| Dell          | Latitude 3490               | Notebook    | [67de502259](https://linux-hardware.org/?probe=67de502259) | Jul 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e394b88e49](https://linux-hardware.org/?probe=e394b88e49) | Jul 08, 2023 |
| Alienware     | 17                          | Notebook    | [b8b8032da9](https://linux-hardware.org/?probe=b8b8032da9) | Jul 08, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [be65f2aa45](https://linux-hardware.org/?probe=be65f2aa45) | Jul 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7cbaa33271](https://linux-hardware.org/?probe=7cbaa33271) | Jul 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e9709930a9](https://linux-hardware.org/?probe=e9709930a9) | Jul 07, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [4b952291ac](https://linux-hardware.org/?probe=4b952291ac) | Jul 07, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [dcf48c7be4](https://linux-hardware.org/?probe=dcf48c7be4) | Jul 07, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [e9b7499b4d](https://linux-hardware.org/?probe=e9b7499b4d) | Jul 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [818272b52c](https://linux-hardware.org/?probe=818272b52c) | Jul 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [ab0a17ec87](https://linux-hardware.org/?probe=ab0a17ec87) | Jul 04, 2023 |
| Lenovo        | IdeaPad 310S-14AST 80UL     | Notebook    | [f897f42089](https://linux-hardware.org/?probe=f897f42089) | Jul 03, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [3861c91dd4](https://linux-hardware.org/?probe=3861c91dd4) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [ab8898b9f3](https://linux-hardware.org/?probe=ab8898b9f3) | Jul 02, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [ec9ab3662c](https://linux-hardware.org/?probe=ec9ab3662c) | Jul 01, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [2ee9ffdaa0](https://linux-hardware.org/?probe=2ee9ffdaa0) | Jun 30, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [6ab7575bed](https://linux-hardware.org/?probe=6ab7575bed) | Jun 30, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [196daaa768](https://linux-hardware.org/?probe=196daaa768) | Jun 30, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [8e7db66929](https://linux-hardware.org/?probe=8e7db66929) | Jun 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5d632e53c6](https://linux-hardware.org/?probe=5d632e53c6) | Jun 30, 2023 |
| Acer          | Aspire 5551                 | Notebook    | [0b4df3165f](https://linux-hardware.org/?probe=0b4df3165f) | Jun 30, 2023 |
| BANGHO        | BES G0304                   | Notebook    | [7b9e2a7570](https://linux-hardware.org/?probe=7b9e2a7570) | Jun 30, 2023 |
| Dell          | Latitude E6400              | Notebook    | [a5af3e134e](https://linux-hardware.org/?probe=a5af3e134e) | Jun 30, 2023 |
| Acer          | Aspire 5551                 | Notebook    | [73a0f2fd37](https://linux-hardware.org/?probe=73a0f2fd37) | Jun 30, 2023 |
| Dell          | Inspiron 7373               | Convertible | [e7edaad244](https://linux-hardware.org/?probe=e7edaad244) | Jun 30, 2023 |
| Dell          | Latitude E4310              | Notebook    | [725b89a524](https://linux-hardware.org/?probe=725b89a524) | Jun 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ef275e1249](https://linux-hardware.org/?probe=ef275e1249) | Jun 29, 2023 |
| Lenovo        | ThinkBook 14s-IML 20RS      | Notebook    | [e3d095fc9f](https://linux-hardware.org/?probe=e3d095fc9f) | Jun 29, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b1b4052442](https://linux-hardware.org/?probe=b1b4052442) | Jun 28, 2023 |
| ASUSTek       | K53E                        | Notebook    | [8e1f4ee31f](https://linux-hardware.org/?probe=8e1f4ee31f) | Jun 27, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [f94b4ddd1b](https://linux-hardware.org/?probe=f94b4ddd1b) | Jun 27, 2023 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [d2d1f5b2a5](https://linux-hardware.org/?probe=d2d1f5b2a5) | Jun 27, 2023 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [d6a1e61945](https://linux-hardware.org/?probe=d6a1e61945) | Jun 26, 2023 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [824c084cce](https://linux-hardware.org/?probe=824c084cce) | Jun 26, 2023 |
| BANGHO        | Suma 1025                   | Tablet      | [c3e666ed19](https://linux-hardware.org/?probe=c3e666ed19) | Jun 26, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [a31908b24b](https://linux-hardware.org/?probe=a31908b24b) | Jun 25, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [a65485d236](https://linux-hardware.org/?probe=a65485d236) | Jun 25, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [7baa53c127](https://linux-hardware.org/?probe=7baa53c127) | Jun 25, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [a6c7992001](https://linux-hardware.org/?probe=a6c7992001) | Jun 24, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [89116ab6be](https://linux-hardware.org/?probe=89116ab6be) | Jun 24, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [ed70d540cd](https://linux-hardware.org/?probe=ed70d540cd) | Jun 24, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [dd17969875](https://linux-hardware.org/?probe=dd17969875) | Jun 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [798efb2213](https://linux-hardware.org/?probe=798efb2213) | Jun 24, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [ddc5e387cb](https://linux-hardware.org/?probe=ddc5e387cb) | Jun 24, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [bd39971c52](https://linux-hardware.org/?probe=bd39971c52) | Jun 23, 2023 |
| Dell          | Latitude 3520               | Notebook    | [ada304545e](https://linux-hardware.org/?probe=ada304545e) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | Satellite-L845              | Notebook    | [cfe5a81354](https://linux-hardware.org/?probe=cfe5a81354) | Jun 18, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [f7dd657c90](https://linux-hardware.org/?probe=f7dd657c90) | Jun 17, 2023 |
| Dell          | Inspiron 5535               | Notebook    | [88a1d18ea0](https://linux-hardware.org/?probe=88a1d18ea0) | Jun 17, 2023 |
| BANGHO        | MAX L5                      | Notebook    | [47f4fd7822](https://linux-hardware.org/?probe=47f4fd7822) | Jun 17, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [269309f364](https://linux-hardware.org/?probe=269309f364) | Jun 16, 2023 |
| BANGHO        | MAX L5                      | Notebook    | [5027ce5059](https://linux-hardware.org/?probe=5027ce5059) | Jun 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [fe65868ffe](https://linux-hardware.org/?probe=fe65868ffe) | Jun 15, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [affb2b7e01](https://linux-hardware.org/?probe=affb2b7e01) | Jun 15, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [850c71b72c](https://linux-hardware.org/?probe=850c71b72c) | Jun 15, 2023 |
| Lenovo        | G470 20078                  | Notebook    | [cc77cad35d](https://linux-hardware.org/?probe=cc77cad35d) | Jun 14, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [7ffe62cc40](https://linux-hardware.org/?probe=7ffe62cc40) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2ecd3dd29b](https://linux-hardware.org/?probe=2ecd3dd29b) | Jun 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e676294e36](https://linux-hardware.org/?probe=e676294e36) | Jun 13, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [d22b8a57cf](https://linux-hardware.org/?probe=d22b8a57cf) | Jun 13, 2023 |
| Unknown       | Unknown                     | Other       | [00ad49fe2f](https://linux-hardware.org/?probe=00ad49fe2f) | Jun 12, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6b1f9dec93](https://linux-hardware.org/?probe=6b1f9dec93) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0d07b35562](https://linux-hardware.org/?probe=0d07b35562) | Jun 11, 2023 |
| ECS           | G41T-M                      | Desktop     | [2c148573fc](https://linux-hardware.org/?probe=2c148573fc) | Jun 11, 2023 |
| Exo           | Smart Serie LT              | Notebook    | [bbecad1cea](https://linux-hardware.org/?probe=bbecad1cea) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [fc025a599d](https://linux-hardware.org/?probe=fc025a599d) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [f32fbdf6ea](https://linux-hardware.org/?probe=f32fbdf6ea) | Jun 10, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [abc3a3d8a1](https://linux-hardware.org/?probe=abc3a3d8a1) | Jun 09, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [fc826b3cb1](https://linux-hardware.org/?probe=fc826b3cb1) | Jun 09, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [b457e63434](https://linux-hardware.org/?probe=b457e63434) | Jun 09, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [fd3b70424a](https://linux-hardware.org/?probe=fd3b70424a) | Jun 09, 2023 |
| HP            | Notebook                    | Notebook    | [e292bb9d5a](https://linux-hardware.org/?probe=e292bb9d5a) | Jun 09, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [24f6f6e727](https://linux-hardware.org/?probe=24f6f6e727) | Jun 08, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [931b9e2b05](https://linux-hardware.org/?probe=931b9e2b05) | Jun 08, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [8d4e2bedde](https://linux-hardware.org/?probe=8d4e2bedde) | Jun 08, 2023 |
| Colorful T... | A520M-K PRO V14             | Desktop     | [48c4aa3d8c](https://linux-hardware.org/?probe=48c4aa3d8c) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [31a7447d8b](https://linux-hardware.org/?probe=31a7447d8b) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [267154b0d2](https://linux-hardware.org/?probe=267154b0d2) | Jun 08, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [ee2b6b0279](https://linux-hardware.org/?probe=ee2b6b0279) | Jun 08, 2023 |
| Intel         | HURONRIVER                  | Notebook    | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [e45ed702a4](https://linux-hardware.org/?probe=e45ed702a4) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | Desktop     | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [43cffb0d0f](https://linux-hardware.org/?probe=43cffb0d0f) | Jun 04, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [cef2bf28c9](https://linux-hardware.org/?probe=cef2bf28c9) | Jun 04, 2023 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [e6492d37d8](https://linux-hardware.org/?probe=e6492d37d8) | Jun 03, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [c6ee1e5e32](https://linux-hardware.org/?probe=c6ee1e5e32) | Jun 02, 2023 |
| HP            | Split 13 x2 PC              | Notebook    | [5e3ae671cc](https://linux-hardware.org/?probe=5e3ae671cc) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [4a2e70149f](https://linux-hardware.org/?probe=4a2e70149f) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [b8fb5e55bc](https://linux-hardware.org/?probe=b8fb5e55bc) | Jun 01, 2023 |
| Positivo      | C500                        | Notebook    | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [670044aef5](https://linux-hardware.org/?probe=670044aef5) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1ea9c869ff](https://linux-hardware.org/?probe=1ea9c869ff) | May 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [b8e68f9227](https://linux-hardware.org/?probe=b8e68f9227) | May 29, 2023 |
| PCBOX         | Kant                        | Notebook    | [1e2f772d05](https://linux-hardware.org/?probe=1e2f772d05) | May 29, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [21261aa270](https://linux-hardware.org/?probe=21261aa270) | May 28, 2023 |
| Intel         | X99                         | Desktop     | [70895d913f](https://linux-hardware.org/?probe=70895d913f) | May 28, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bbd09f3d8f](https://linux-hardware.org/?probe=bbd09f3d8f) | May 27, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [184afbb9c3](https://linux-hardware.org/?probe=184afbb9c3) | May 26, 2023 |
| Lenovo        | ThinkPad E495 20NES0RS00    | Notebook    | [6f507e12bc](https://linux-hardware.org/?probe=6f507e12bc) | May 25, 2023 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [63ba811050](https://linux-hardware.org/?probe=63ba811050) | May 25, 2023 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [380b9a5005](https://linux-hardware.org/?probe=380b9a5005) | May 25, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a4690b7476](https://linux-hardware.org/?probe=a4690b7476) | May 25, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [82183f4762](https://linux-hardware.org/?probe=82183f4762) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8fb981666f](https://linux-hardware.org/?probe=8fb981666f) | May 24, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e4c9c425f8](https://linux-hardware.org/?probe=e4c9c425f8) | May 23, 2023 |
| MSI           | B460M PRO                   | Desktop     | [94ce62125f](https://linux-hardware.org/?probe=94ce62125f) | May 23, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [8ae80f0665](https://linux-hardware.org/?probe=8ae80f0665) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [584c6658c6](https://linux-hardware.org/?probe=584c6658c6) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [e7d7c8f7d8](https://linux-hardware.org/?probe=e7d7c8f7d8) | May 23, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [e250801798](https://linux-hardware.org/?probe=e250801798) | May 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [069d442d0d](https://linux-hardware.org/?probe=069d442d0d) | May 22, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [cb61728cb7](https://linux-hardware.org/?probe=cb61728cb7) | May 22, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [c2d03bd839](https://linux-hardware.org/?probe=c2d03bd839) | May 22, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [1dda8d01ad](https://linux-hardware.org/?probe=1dda8d01ad) | May 20, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [fe4d0a2ec3](https://linux-hardware.org/?probe=fe4d0a2ec3) | May 20, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [b7655822d2](https://linux-hardware.org/?probe=b7655822d2) | May 19, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c571a25585](https://linux-hardware.org/?probe=c571a25585) | May 19, 2023 |
| Lenovo        | IdeaPad U530 Touch 20289    | Notebook    | [72e254e4ee](https://linux-hardware.org/?probe=72e254e4ee) | May 19, 2023 |
| Philco        | PHN14C                      | Notebook    | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bd7e95bf66](https://linux-hardware.org/?probe=bd7e95bf66) | May 18, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [ca3fda27b5](https://linux-hardware.org/?probe=ca3fda27b5) | May 18, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [f720713dda](https://linux-hardware.org/?probe=f720713dda) | May 13, 2023 |
| HP            | 339A                        | Desktop     | [2ba14f8397](https://linux-hardware.org/?probe=2ba14f8397) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1713b94d26](https://linux-hardware.org/?probe=1713b94d26) | May 12, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [81711fd069](https://linux-hardware.org/?probe=81711fd069) | May 11, 2023 |
| Unknown       | M-140BI3                    | Notebook    | [eb6507c151](https://linux-hardware.org/?probe=eb6507c151) | May 11, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | Desktop     | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [efca4bf9af](https://linux-hardware.org/?probe=efca4bf9af) | May 10, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [e914b76fef](https://linux-hardware.org/?probe=e914b76fef) | May 10, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [35750a650a](https://linux-hardware.org/?probe=35750a650a) | May 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [813acd1225](https://linux-hardware.org/?probe=813acd1225) | May 10, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [fbe7b6d2bf](https://linux-hardware.org/?probe=fbe7b6d2bf) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [26e8efdd69](https://linux-hardware.org/?probe=26e8efdd69) | May 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [89ccdd7262](https://linux-hardware.org/?probe=89ccdd7262) | May 08, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [d63bc9aeca](https://linux-hardware.org/?probe=d63bc9aeca) | May 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [18dcba612c](https://linux-hardware.org/?probe=18dcba612c) | May 07, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [67b9224d87](https://linux-hardware.org/?probe=67b9224d87) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [6ec1762e12](https://linux-hardware.org/?probe=6ec1762e12) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [6816b3dddd](https://linux-hardware.org/?probe=6816b3dddd) | May 07, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [e5488a0dc9](https://linux-hardware.org/?probe=e5488a0dc9) | May 06, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [2d41ef08f2](https://linux-hardware.org/?probe=2d41ef08f2) | May 05, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7cf447e261](https://linux-hardware.org/?probe=7cf447e261) | May 05, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [2e4e7c801d](https://linux-hardware.org/?probe=2e4e7c801d) | May 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [e7f4d1fdda](https://linux-hardware.org/?probe=e7f4d1fdda) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [1f3953650c](https://linux-hardware.org/?probe=1f3953650c) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [417be33443](https://linux-hardware.org/?probe=417be33443) | May 05, 2023 |
| MSI           | 760GM-P34                   | Desktop     | [cb75fca473](https://linux-hardware.org/?probe=cb75fca473) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [218ba5d6a5](https://linux-hardware.org/?probe=218ba5d6a5) | May 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [92c9651e22](https://linux-hardware.org/?probe=92c9651e22) | May 04, 2023 |
| Intel         | DG43GT AAE62768-300         | Desktop     | [e0f10df0f9](https://linux-hardware.org/?probe=e0f10df0f9) | May 03, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2fabcbe5dc](https://linux-hardware.org/?probe=2fabcbe5dc) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fa453d9183](https://linux-hardware.org/?probe=fa453d9183) | May 02, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [f62abcbed6](https://linux-hardware.org/?probe=f62abcbed6) | May 02, 2023 |
| ASUSTek       | A55M-E                      | Desktop     | [927efc8106](https://linux-hardware.org/?probe=927efc8106) | May 02, 2023 |
| iQual         | NQ4X                        | Notebook    | [256ae92f40](https://linux-hardware.org/?probe=256ae92f40) | May 02, 2023 |
| ASUSTek       | A55M-E                      | Desktop     | [ee1054dc5c](https://linux-hardware.org/?probe=ee1054dc5c) | May 01, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [67da6cebd3](https://linux-hardware.org/?probe=67da6cebd3) | Apr 29, 2023 |
| HP            | Unknown                     | Notebook    | [bba45b8ff0](https://linux-hardware.org/?probe=bba45b8ff0) | Apr 27, 2023 |
| Dell          | Latitude E5410              | Notebook    | [1efb62110c](https://linux-hardware.org/?probe=1efb62110c) | Apr 27, 2023 |
| Dell          | Latitude E5410              | Notebook    | [02be2c8f0b](https://linux-hardware.org/?probe=02be2c8f0b) | Apr 26, 2023 |
| HP            | 81BB                        | All in one  | [65fb6f51d1](https://linux-hardware.org/?probe=65fb6f51d1) | Apr 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9e926f5c65](https://linux-hardware.org/?probe=9e926f5c65) | Apr 24, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [971055139b](https://linux-hardware.org/?probe=971055139b) | Apr 24, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| HP            | 090Ch                       | Desktop     | [01d609bbab](https://linux-hardware.org/?probe=01d609bbab) | Apr 23, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [7a1a8bb421](https://linux-hardware.org/?probe=7a1a8bb421) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [3fa24b1a91](https://linux-hardware.org/?probe=3fa24b1a91) | Apr 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [c8ec222920](https://linux-hardware.org/?probe=c8ec222920) | Apr 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [2a02b4695b](https://linux-hardware.org/?probe=2a02b4695b) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [bf1dbf49a8](https://linux-hardware.org/?probe=bf1dbf49a8) | Apr 22, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [32ba023e2a](https://linux-hardware.org/?probe=32ba023e2a) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [cde822d71c](https://linux-hardware.org/?probe=cde822d71c) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5f61e3a174](https://linux-hardware.org/?probe=5f61e3a174) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b0b94f2462](https://linux-hardware.org/?probe=b0b94f2462) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d429a2c865](https://linux-hardware.org/?probe=d429a2c865) | Apr 21, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [f89cce4966](https://linux-hardware.org/?probe=f89cce4966) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f5da23bee0](https://linux-hardware.org/?probe=f5da23bee0) | Apr 20, 2023 |
| MSI           | GE62 6QD                    | Notebook    | [785d4c1655](https://linux-hardware.org/?probe=785d4c1655) | Apr 20, 2023 |
| Dell          | Latitude E6440              | Notebook    | [027d51d72d](https://linux-hardware.org/?probe=027d51d72d) | Apr 19, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6696ce8fd6](https://linux-hardware.org/?probe=6696ce8fd6) | Apr 17, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [b4e51d0af3](https://linux-hardware.org/?probe=b4e51d0af3) | Apr 17, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [a6ba0d9290](https://linux-hardware.org/?probe=a6ba0d9290) | Apr 17, 2023 |
| iQual         | NQ4X                        | Notebook    | [425ccf4057](https://linux-hardware.org/?probe=425ccf4057) | Apr 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7b5363bc3e](https://linux-hardware.org/?probe=7b5363bc3e) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [9b23be6c48](https://linux-hardware.org/?probe=9b23be6c48) | Apr 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c5f2678609](https://linux-hardware.org/?probe=c5f2678609) | Apr 15, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [6419c7fb77](https://linux-hardware.org/?probe=6419c7fb77) | Apr 15, 2023 |
| Gigabyte      | B365 HD3                    | Desktop     | [9d18bebcd7](https://linux-hardware.org/?probe=9d18bebcd7) | Apr 15, 2023 |
| Gigabyte      | B365 HD3                    | Desktop     | [921a57413c](https://linux-hardware.org/?probe=921a57413c) | Apr 15, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [d1ed9e6040](https://linux-hardware.org/?probe=d1ed9e6040) | Apr 14, 2023 |
| HP            | Compaq Presario F700        | Notebook    | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Dell          | Latitude 5490               | Notebook    | [38ebdedf58](https://linux-hardware.org/?probe=38ebdedf58) | Apr 12, 2023 |
| HP            | 81BB                        | All in one  | [ef22a07523](https://linux-hardware.org/?probe=ef22a07523) | Apr 12, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [1649a1f9b5](https://linux-hardware.org/?probe=1649a1f9b5) | Apr 12, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [497756c5ab](https://linux-hardware.org/?probe=497756c5ab) | Apr 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [dc55b7997e](https://linux-hardware.org/?probe=dc55b7997e) | Apr 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b35d9a7487](https://linux-hardware.org/?probe=b35d9a7487) | Apr 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE1M    | Notebook    | [eb794b0dc7](https://linux-hardware.org/?probe=eb794b0dc7) | Apr 10, 2023 |
| Positivo      | A1000BW                     | Notebook    | [02295facdc](https://linux-hardware.org/?probe=02295facdc) | Apr 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [916db99ea5](https://linux-hardware.org/?probe=916db99ea5) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5a900adcdc](https://linux-hardware.org/?probe=5a900adcdc) | Apr 07, 2023 |
| Samsung       | NC110P/NC108P/NC111P        | Notebook    | [91fcea0b0f](https://linux-hardware.org/?probe=91fcea0b0f) | Apr 07, 2023 |
| Gigabyte      | AORUS 15P KD                | Notebook    | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [bb95a52e54](https://linux-hardware.org/?probe=bb95a52e54) | Apr 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [58f5904dec](https://linux-hardware.org/?probe=58f5904dec) | Apr 04, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [9f251621b1](https://linux-hardware.org/?probe=9f251621b1) | Apr 04, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f801258fa5](https://linux-hardware.org/?probe=f801258fa5) | Apr 04, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [47c6d88922](https://linux-hardware.org/?probe=47c6d88922) | Apr 03, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 80XB     | Convertible | [1e1b34725b](https://linux-hardware.org/?probe=1e1b34725b) | Apr 03, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [71f34e6ebc](https://linux-hardware.org/?probe=71f34e6ebc) | Apr 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [676156b5df](https://linux-hardware.org/?probe=676156b5df) | Apr 02, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5fc258772a](https://linux-hardware.org/?probe=5fc258772a) | Apr 01, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [2addcb84c6](https://linux-hardware.org/?probe=2addcb84c6) | Apr 01, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [f54ccba86f](https://linux-hardware.org/?probe=f54ccba86f) | Apr 01, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [3c163a3b34](https://linux-hardware.org/?probe=3c163a3b34) | Mar 31, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [8d2858a444](https://linux-hardware.org/?probe=8d2858a444) | Mar 31, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [45a242d18f](https://linux-hardware.org/?probe=45a242d18f) | Mar 31, 2023 |
| Exo           | Smart XL4                   | Notebook    | [6421142cb6](https://linux-hardware.org/?probe=6421142cb6) | Mar 31, 2023 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [193d27ceac](https://linux-hardware.org/?probe=193d27ceac) | Mar 31, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [2ca1607b80](https://linux-hardware.org/?probe=2ca1607b80) | Mar 30, 2023 |
| AIR           | CX30500                     | Notebook    | [2ea4d0ec83](https://linux-hardware.org/?probe=2ea4d0ec83) | Mar 30, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [41a76fad3f](https://linux-hardware.org/?probe=41a76fad3f) | Mar 30, 2023 |
| Lenovo        | G470 20078                  | Notebook    | [1e510aad42](https://linux-hardware.org/?probe=1e510aad42) | Mar 30, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [25cc7bfca2](https://linux-hardware.org/?probe=25cc7bfca2) | Mar 28, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b6184e813b](https://linux-hardware.org/?probe=b6184e813b) | Mar 28, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [f281edd494](https://linux-hardware.org/?probe=f281edd494) | Mar 28, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [709242697d](https://linux-hardware.org/?probe=709242697d) | Mar 27, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [a9ca07dc80](https://linux-hardware.org/?probe=a9ca07dc80) | Mar 27, 2023 |
| Sony          | VJFE52A0711H                | Notebook    | [f2186a4bc4](https://linux-hardware.org/?probe=f2186a4bc4) | Mar 27, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [dca4079e12](https://linux-hardware.org/?probe=dca4079e12) | Mar 26, 2023 |
| Intel         | DG41CN AAE82429-102         | Desktop     | [c671afb118](https://linux-hardware.org/?probe=c671afb118) | Mar 26, 2023 |
| HP            | G42                         | Notebook    | [f1b5695907](https://linux-hardware.org/?probe=f1b5695907) | Mar 25, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [3677f24e87](https://linux-hardware.org/?probe=3677f24e87) | Mar 25, 2023 |
| Dell          | Latitude 5480               | Notebook    | [5886784510](https://linux-hardware.org/?probe=5886784510) | Mar 22, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [dcae89c3e5](https://linux-hardware.org/?probe=dcae89c3e5) | Mar 21, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9ff80f0344](https://linux-hardware.org/?probe=9ff80f0344) | Mar 21, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [708f22e8d7](https://linux-hardware.org/?probe=708f22e8d7) | Mar 19, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [eea214ee38](https://linux-hardware.org/?probe=eea214ee38) | Mar 18, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [0ac96925cd](https://linux-hardware.org/?probe=0ac96925cd) | Mar 16, 2023 |
| ECS           | A55F-M4                     | Desktop     | [eaee63c0f9](https://linux-hardware.org/?probe=eaee63c0f9) | Mar 14, 2023 |
| ECS           | A55F-M4                     | Desktop     | [667ab38865](https://linux-hardware.org/?probe=667ab38865) | Mar 14, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | Notebook    | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Exo           | Smart XS1                   | Notebook    | [e1e04684eb](https://linux-hardware.org/?probe=e1e04684eb) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [97504eea44](https://linux-hardware.org/?probe=97504eea44) | Mar 13, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e035b82dec](https://linux-hardware.org/?probe=e035b82dec) | Mar 13, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [07ebf171d6](https://linux-hardware.org/?probe=07ebf171d6) | Mar 12, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [309d95f00f](https://linux-hardware.org/?probe=309d95f00f) | Mar 11, 2023 |
| Intel         | H61                         | Desktop     | [5650f6d211](https://linux-hardware.org/?probe=5650f6d211) | Mar 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [284d2d79f0](https://linux-hardware.org/?probe=284d2d79f0) | Mar 11, 2023 |
| BANGHO        | LITE E34                    | Desktop     | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [1815783cfe](https://linux-hardware.org/?probe=1815783cfe) | Mar 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [7236313c80](https://linux-hardware.org/?probe=7236313c80) | Mar 09, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [bb3776e45d](https://linux-hardware.org/?probe=bb3776e45d) | Mar 09, 2023 |
| eMachines     | eME730                      | Notebook    | [0e1683ee34](https://linux-hardware.org/?probe=0e1683ee34) | Mar 08, 2023 |
| eMachines     | eME730                      | Notebook    | [db15f88805](https://linux-hardware.org/?probe=db15f88805) | Mar 08, 2023 |
| Lenovo        | ThinkPad X240 20AMA3PVAR    | Notebook    | [367f53195a](https://linux-hardware.org/?probe=367f53195a) | Mar 07, 2023 |
| Exo           | Smart Serie M               | Notebook    | [99c93d693a](https://linux-hardware.org/?probe=99c93d693a) | Mar 04, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [82994d7312](https://linux-hardware.org/?probe=82994d7312) | Mar 04, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [5523730c91](https://linux-hardware.org/?probe=5523730c91) | Mar 04, 2023 |
| Exo           | Smart Serie M               | Notebook    | [e7b817f5ed](https://linux-hardware.org/?probe=e7b817f5ed) | Mar 04, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [abb62fe86f](https://linux-hardware.org/?probe=abb62fe86f) | Mar 04, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [3c2ed7f053](https://linux-hardware.org/?probe=3c2ed7f053) | Mar 04, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ae8045e8dd](https://linux-hardware.org/?probe=ae8045e8dd) | Mar 04, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [aefca0b663](https://linux-hardware.org/?probe=aefca0b663) | Feb 28, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [12ccf2fe8b](https://linux-hardware.org/?probe=12ccf2fe8b) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [c7bb2ebe8b](https://linux-hardware.org/?probe=c7bb2ebe8b) | Feb 24, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [c19b7cd0f5](https://linux-hardware.org/?probe=c19b7cd0f5) | Feb 24, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [916f372721](https://linux-hardware.org/?probe=916f372721) | Feb 24, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [6e82a5c5d6](https://linux-hardware.org/?probe=6e82a5c5d6) | Feb 24, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [f7d34fdd3a](https://linux-hardware.org/?probe=f7d34fdd3a) | Feb 24, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [a37b20471b](https://linux-hardware.org/?probe=a37b20471b) | Feb 23, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [2f9c2ec647](https://linux-hardware.org/?probe=2f9c2ec647) | Feb 23, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a5f65720f5](https://linux-hardware.org/?probe=a5f65720f5) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [cfcf2ff473](https://linux-hardware.org/?probe=cfcf2ff473) | Feb 21, 2023 |
| Exo           | Smart XL4                   | Notebook    | [6e97a3ff67](https://linux-hardware.org/?probe=6e97a3ff67) | Feb 21, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [bbef057c8f](https://linux-hardware.org/?probe=bbef057c8f) | Feb 21, 2023 |
| Dell          | Inspiron 3502               | Notebook    | [224f4edab7](https://linux-hardware.org/?probe=224f4edab7) | Feb 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [008d5e19e1](https://linux-hardware.org/?probe=008d5e19e1) | Feb 20, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b4b87d47fb](https://linux-hardware.org/?probe=b4b87d47fb) | Feb 17, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [38a92c4ace](https://linux-hardware.org/?probe=38a92c4ace) | Feb 15, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [ba53e8885b](https://linux-hardware.org/?probe=ba53e8885b) | Feb 13, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [74d6af0f75](https://linux-hardware.org/?probe=74d6af0f75) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| BANGHO        | GM-15Z11 GF1650 i5          | Notebook    | [6cdb04950c](https://linux-hardware.org/?probe=6cdb04950c) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [a64bb02ece](https://linux-hardware.org/?probe=a64bb02ece) | Feb 10, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [a07b2a4444](https://linux-hardware.org/?probe=a07b2a4444) | Feb 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f8de6e450a](https://linux-hardware.org/?probe=f8de6e450a) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| ASRock        | B560 Pro4                   | Desktop     | [0243fe3621](https://linux-hardware.org/?probe=0243fe3621) | Feb 07, 2023 |
| Lenovo        | G470 20078                  | Notebook    | [eca9b95b61](https://linux-hardware.org/?probe=eca9b95b61) | Feb 07, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [a1f33b7267](https://linux-hardware.org/?probe=a1f33b7267) | Feb 06, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [5ae73f08c5](https://linux-hardware.org/?probe=5ae73f08c5) | Feb 06, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [32f4028033](https://linux-hardware.org/?probe=32f4028033) | Feb 05, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [93ee4435a2](https://linux-hardware.org/?probe=93ee4435a2) | Feb 03, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [86667a843f](https://linux-hardware.org/?probe=86667a843f) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [03540bd8e5](https://linux-hardware.org/?probe=03540bd8e5) | Feb 02, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [a6584159ac](https://linux-hardware.org/?probe=a6584159ac) | Feb 02, 2023 |
| ECS           | P4M800PRO-M                 | Desktop     | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| ECS           | A55F-M4                     | Desktop     | [08af507321](https://linux-hardware.org/?probe=08af507321) | Feb 01, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [f6d37d568c](https://linux-hardware.org/?probe=f6d37d568c) | Feb 01, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [9fab32d6a5](https://linux-hardware.org/?probe=9fab32d6a5) | Feb 01, 2023 |
| Samsung       | SQ35S                       | Notebook    | [7ad1c8a94b](https://linux-hardware.org/?probe=7ad1c8a94b) | Feb 01, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [298b411767](https://linux-hardware.org/?probe=298b411767) | Jan 31, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5abc8dccdb](https://linux-hardware.org/?probe=5abc8dccdb) | Jan 31, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [e8f09a159a](https://linux-hardware.org/?probe=e8f09a159a) | Jan 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [5122097b1e](https://linux-hardware.org/?probe=5122097b1e) | Jan 29, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [d25a13d2c4](https://linux-hardware.org/?probe=d25a13d2c4) | Jan 28, 2023 |
| Lenovo        | ThinkPad X230 23254UY       | Notebook    | [130aeb9cc4](https://linux-hardware.org/?probe=130aeb9cc4) | Jan 27, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b2c04ca4b9](https://linux-hardware.org/?probe=b2c04ca4b9) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [1099a3c6c9](https://linux-hardware.org/?probe=1099a3c6c9) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [4944e0cddd](https://linux-hardware.org/?probe=4944e0cddd) | Jan 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [055d033d99](https://linux-hardware.org/?probe=055d033d99) | Jan 24, 2023 |
| Sony          | VPCEA30EL                   | Notebook    | [7de250ffe6](https://linux-hardware.org/?probe=7de250ffe6) | Jan 24, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| ECS           | A55F-M4                     | Desktop     | [db65e68855](https://linux-hardware.org/?probe=db65e68855) | Jan 23, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [458bb94702](https://linux-hardware.org/?probe=458bb94702) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [7ecc4d20c3](https://linux-hardware.org/?probe=7ecc4d20c3) | Jan 19, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [b0716d3518](https://linux-hardware.org/?probe=b0716d3518) | Jan 19, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [cb4c89a390](https://linux-hardware.org/?probe=cb4c89a390) | Jan 18, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| BANGHO        | MOV                         | Notebook    | [bc4f98d4ff](https://linux-hardware.org/?probe=bc4f98d4ff) | Jan 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b51cc41cb3](https://linux-hardware.org/?probe=b51cc41cb3) | Jan 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [212fa962a2](https://linux-hardware.org/?probe=212fa962a2) | Jan 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [ca60f249a9](https://linux-hardware.org/?probe=ca60f249a9) | Jan 13, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [08638b9441](https://linux-hardware.org/?probe=08638b9441) | Jan 13, 2023 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [4a07474fa4](https://linux-hardware.org/?probe=4a07474fa4) | Jan 12, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [8243f25120](https://linux-hardware.org/?probe=8243f25120) | Jan 12, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [86a6601ce5](https://linux-hardware.org/?probe=86a6601ce5) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [46679246b9](https://linux-hardware.org/?probe=46679246b9) | Jan 11, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [790736a10e](https://linux-hardware.org/?probe=790736a10e) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8c480c028a](https://linux-hardware.org/?probe=8c480c028a) | Jan 10, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [ff6c949737](https://linux-hardware.org/?probe=ff6c949737) | Jan 09, 2023 |
| Dell          | Latitude 3490               | Notebook    | [7cf81f6b69](https://linux-hardware.org/?probe=7cf81f6b69) | Jan 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4334ec8d00](https://linux-hardware.org/?probe=4334ec8d00) | Jan 08, 2023 |
| ASUSTek       | M2N68-AM SE                 | Desktop     | [52a0fe59db](https://linux-hardware.org/?probe=52a0fe59db) | Jan 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [7ce97bb3ec](https://linux-hardware.org/?probe=7ce97bb3ec) | Jan 08, 2023 |
| HP            | 240 G8                      | Notebook    | [efc7e61483](https://linux-hardware.org/?probe=efc7e61483) | Jan 06, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [290ccc3261](https://linux-hardware.org/?probe=290ccc3261) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cddb2a7b81](https://linux-hardware.org/?probe=cddb2a7b81) | Jan 06, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [95db7fffba](https://linux-hardware.org/?probe=95db7fffba) | Jan 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [aa23d3d6f0](https://linux-hardware.org/?probe=aa23d3d6f0) | Jan 04, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a4473dafda](https://linux-hardware.org/?probe=a4473dafda) | Jan 03, 2023 |
| Positivo      | Z100                        | Notebook    | [58b7c4d1ff](https://linux-hardware.org/?probe=58b7c4d1ff) | Jan 02, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [c6c0626dd1](https://linux-hardware.org/?probe=c6c0626dd1) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [5fbe1632b0](https://linux-hardware.org/?probe=5fbe1632b0) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [5a479fed95](https://linux-hardware.org/?probe=5a479fed95) | Dec 31, 2022 |
| Dell          | Latitude E6430              | Notebook    | [de9b03cf29](https://linux-hardware.org/?probe=de9b03cf29) | Dec 31, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [97f08bd689](https://linux-hardware.org/?probe=97f08bd689) | Dec 30, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [24574296e5](https://linux-hardware.org/?probe=24574296e5) | Dec 29, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [7a7f335c4a](https://linux-hardware.org/?probe=7a7f335c4a) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [ed5315b768](https://linux-hardware.org/?probe=ed5315b768) | Dec 29, 2022 |
| Acer          | AO756                       | Notebook    | [d0cf64acd1](https://linux-hardware.org/?probe=d0cf64acd1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [e12c24fd74](https://linux-hardware.org/?probe=e12c24fd74) | Dec 28, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [8cbb4aa960](https://linux-hardware.org/?probe=8cbb4aa960) | Dec 28, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [d6e7a07be2](https://linux-hardware.org/?probe=d6e7a07be2) | Dec 28, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [6d56c4c392](https://linux-hardware.org/?probe=6d56c4c392) | Dec 27, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [d6a12148ec](https://linux-hardware.org/?probe=d6a12148ec) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [2195143f19](https://linux-hardware.org/?probe=2195143f19) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [73e9da47ae](https://linux-hardware.org/?probe=73e9da47ae) | Dec 27, 2022 |
| Exo           | Smart Serie M               | Notebook    | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c7babe827f](https://linux-hardware.org/?probe=c7babe827f) | Dec 26, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [5004189ba4](https://linux-hardware.org/?probe=5004189ba4) | Dec 26, 2022 |
| ASRock        | FM2A78M-HD+ R2.0            | Desktop     | [ff69d47b58](https://linux-hardware.org/?probe=ff69d47b58) | Dec 24, 2022 |
| ASRock        | FM2A78M-HD+ R2.0            | Desktop     | [696403dae4](https://linux-hardware.org/?probe=696403dae4) | Dec 24, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [7de172c3b1](https://linux-hardware.org/?probe=7de172c3b1) | Dec 23, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [668dac3d4c](https://linux-hardware.org/?probe=668dac3d4c) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [d592546f0a](https://linux-hardware.org/?probe=d592546f0a) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [52f1e32fc8](https://linux-hardware.org/?probe=52f1e32fc8) | Dec 23, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [af0433651a](https://linux-hardware.org/?probe=af0433651a) | Dec 22, 2022 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [1f8d567742](https://linux-hardware.org/?probe=1f8d567742) | Dec 20, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [aaaf436994](https://linux-hardware.org/?probe=aaaf436994) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b34ce3474d](https://linux-hardware.org/?probe=b34ce3474d) | Dec 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [ae3789203b](https://linux-hardware.org/?probe=ae3789203b) | Dec 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [97aa100931](https://linux-hardware.org/?probe=97aa100931) | Dec 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [33bbc3a179](https://linux-hardware.org/?probe=33bbc3a179) | Dec 18, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [04cc986bf6](https://linux-hardware.org/?probe=04cc986bf6) | Dec 15, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [ccb746cd73](https://linux-hardware.org/?probe=ccb746cd73) | Dec 15, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f18234034f](https://linux-hardware.org/?probe=f18234034f) | Dec 15, 2022 |
| Dell          | Latitude 5520               | Notebook    | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| Exo           | Smart Serie M               | Notebook    | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [9866855d37](https://linux-hardware.org/?probe=9866855d37) | Dec 13, 2022 |
| Clevo         | M740TU/M760TU               | Notebook    | [5f1a4b58fb](https://linux-hardware.org/?probe=5f1a4b58fb) | Dec 13, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [260a382d54](https://linux-hardware.org/?probe=260a382d54) | Dec 12, 2022 |
| MSI           | A55M-E33                    | Desktop     | [327967e6a4](https://linux-hardware.org/?probe=327967e6a4) | Dec 11, 2022 |
| Dell          | Latitude E6430              | Notebook    | [f28775142d](https://linux-hardware.org/?probe=f28775142d) | Dec 09, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| ASRock        | 945GCM-S                    | Desktop     | [926787ea67](https://linux-hardware.org/?probe=926787ea67) | Dec 09, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| Dell          | G15 5515                    | Notebook    | [861bd0cabf](https://linux-hardware.org/?probe=861bd0cabf) | Dec 08, 2022 |
| HP            | Notebook                    | Notebook    | [37eead7e86](https://linux-hardware.org/?probe=37eead7e86) | Dec 07, 2022 |
| BANGHO        | BES T5                      | Notebook    | [db1db74a86](https://linux-hardware.org/?probe=db1db74a86) | Dec 06, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [7d42818fc5](https://linux-hardware.org/?probe=7d42818fc5) | Dec 06, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [3b87d266c2](https://linux-hardware.org/?probe=3b87d266c2) | Dec 02, 2022 |
| Dell          | Latitude E5450              | Notebook    | [305bf364f6](https://linux-hardware.org/?probe=305bf364f6) | Dec 01, 2022 |
| Dell          | Latitude E5450              | Notebook    | [2b934a729c](https://linux-hardware.org/?probe=2b934a729c) | Dec 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [becc2328fd](https://linux-hardware.org/?probe=becc2328fd) | Dec 01, 2022 |
| Lenovo        | ThinkCentre M70e 0809D1Y    | Desktop     | [0cd85fa9f3](https://linux-hardware.org/?probe=0cd85fa9f3) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | Notebook    | [81eca2f60e](https://linux-hardware.org/?probe=81eca2f60e) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | Notebook    | [5841aa11f1](https://linux-hardware.org/?probe=5841aa11f1) | Nov 30, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [3f545fe7c9](https://linux-hardware.org/?probe=3f545fe7c9) | Nov 29, 2022 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [8b3da34947](https://linux-hardware.org/?probe=8b3da34947) | Nov 28, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Foxconn       | A74ML-K                     | Desktop     | [438e3ff761](https://linux-hardware.org/?probe=438e3ff761) | Nov 27, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5f1188d448](https://linux-hardware.org/?probe=5f1188d448) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [771019bcc6](https://linux-hardware.org/?probe=771019bcc6) | Nov 26, 2022 |
| Lenovo        | ThinkPad E14 20RBS3LE00     | Notebook    | [83203a04f2](https://linux-hardware.org/?probe=83203a04f2) | Nov 25, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [036dcac9fa](https://linux-hardware.org/?probe=036dcac9fa) | Nov 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [fdafa2db2a](https://linux-hardware.org/?probe=fdafa2db2a) | Nov 22, 2022 |
| HP            | Notebook                    | Notebook    | [ab824250b9](https://linux-hardware.org/?probe=ab824250b9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [498c078586](https://linux-hardware.org/?probe=498c078586) | Nov 21, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [abda5b4aaf](https://linux-hardware.org/?probe=abda5b4aaf) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7ffd8149f4](https://linux-hardware.org/?probe=7ffd8149f4) | Nov 21, 2022 |
| Dell          | Latitude E6510              | Notebook    | [c8b9fa9d0a](https://linux-hardware.org/?probe=c8b9fa9d0a) | Nov 20, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [86159f4ef3](https://linux-hardware.org/?probe=86159f4ef3) | Nov 20, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0734f58b03](https://linux-hardware.org/?probe=0734f58b03) | Nov 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [ebceee7ddf](https://linux-hardware.org/?probe=ebceee7ddf) | Nov 18, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [d22a7fff30](https://linux-hardware.org/?probe=d22a7fff30) | Nov 18, 2022 |
| ASUSTek       | K52Jc                       | Notebook    | [375bc280d3](https://linux-hardware.org/?probe=375bc280d3) | Nov 18, 2022 |
| Exo           | Smart XS1                   | Notebook    | [d51bf05ac5](https://linux-hardware.org/?probe=d51bf05ac5) | Nov 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [3964f95a8c](https://linux-hardware.org/?probe=3964f95a8c) | Nov 17, 2022 |
| Dell          | G15 5515                    | Notebook    | [bb76ce58ad](https://linux-hardware.org/?probe=bb76ce58ad) | Nov 17, 2022 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [ef34a2a126](https://linux-hardware.org/?probe=ef34a2a126) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [d82617ae65](https://linux-hardware.org/?probe=d82617ae65) | Nov 15, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [97b0a5f239](https://linux-hardware.org/?probe=97b0a5f239) | Nov 14, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [c6e254c4ed](https://linux-hardware.org/?probe=c6e254c4ed) | Nov 14, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [83e4ef99fb](https://linux-hardware.org/?probe=83e4ef99fb) | Nov 13, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7e9c7562d6](https://linux-hardware.org/?probe=7e9c7562d6) | Nov 13, 2022 |
| ASUSTek       | UX410UAK                    | Notebook    | [6653b6c4a5](https://linux-hardware.org/?probe=6653b6c4a5) | Nov 13, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [842f768168](https://linux-hardware.org/?probe=842f768168) | Nov 12, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [9b43ddbe11](https://linux-hardware.org/?probe=9b43ddbe11) | Nov 09, 2022 |
| Lenovo        | ThinkPad W541 20EGS0V700    | Notebook    | [d03ec65abc](https://linux-hardware.org/?probe=d03ec65abc) | Nov 08, 2022 |
| HP            | 240 G8                      | Notebook    | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | Notebook    | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d71ebfae8b](https://linux-hardware.org/?probe=d71ebfae8b) | Nov 07, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [8e89ed396e](https://linux-hardware.org/?probe=8e89ed396e) | Nov 05, 2022 |
| BANGHO        | W240HU/W250HUQ              | Notebook    | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Juana Mans... | SF20GM7                     | Notebook    | [8e8c4f52f4](https://linux-hardware.org/?probe=8e8c4f52f4) | Nov 04, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [f427764e2c](https://linux-hardware.org/?probe=f427764e2c) | Nov 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [c90b358eb5](https://linux-hardware.org/?probe=c90b358eb5) | Nov 01, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [deac1b706f](https://linux-hardware.org/?probe=deac1b706f) | Oct 31, 2022 |
| Intel         | powered classmate PC        | Notebook    | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [a4e0449df5](https://linux-hardware.org/?probe=a4e0449df5) | Oct 30, 2022 |
| Lenovo        | ThinkPad T440 20B7S18Y0Y    | Notebook    | [9cf3beb13f](https://linux-hardware.org/?probe=9cf3beb13f) | Oct 30, 2022 |
| Lenovo        | ThinkPad T440 20B7S18Y0Y    | Notebook    | [36b3303b35](https://linux-hardware.org/?probe=36b3303b35) | Oct 30, 2022 |
| ASUSTek       | TUF H370-PRO GAMING WIFI    | Desktop     | [48cbfa7a78](https://linux-hardware.org/?probe=48cbfa7a78) | Oct 28, 2022 |
| Compaq        | Presario 21 VerX            | Notebook    | [97ee92b9d1](https://linux-hardware.org/?probe=97ee92b9d1) | Oct 28, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [3eeb2624bf](https://linux-hardware.org/?probe=3eeb2624bf) | Oct 27, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [c923b6d506](https://linux-hardware.org/?probe=c923b6d506) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1bc5db124b](https://linux-hardware.org/?probe=1bc5db124b) | Oct 27, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [9c19f9e755](https://linux-hardware.org/?probe=9c19f9e755) | Oct 27, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [87ee863ba2](https://linux-hardware.org/?probe=87ee863ba2) | Oct 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [eca0e58bd8](https://linux-hardware.org/?probe=eca0e58bd8) | Oct 25, 2022 |
| Dell          | Precision 5560              | Notebook    | [c6cfa3f96d](https://linux-hardware.org/?probe=c6cfa3f96d) | Oct 25, 2022 |
| Dell          | Precision 5560              | Notebook    | [e0dce17c1f](https://linux-hardware.org/?probe=e0dce17c1f) | Oct 25, 2022 |
| ASRock        | N68-S                       | Desktop     | [f1f502f834](https://linux-hardware.org/?probe=f1f502f834) | Oct 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [0c60239460](https://linux-hardware.org/?probe=0c60239460) | Oct 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3749438ef1](https://linux-hardware.org/?probe=3749438ef1) | Oct 24, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [25db15ea87](https://linux-hardware.org/?probe=25db15ea87) | Oct 24, 2022 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [8f793706c2](https://linux-hardware.org/?probe=8f793706c2) | Oct 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [4a17b0a89d](https://linux-hardware.org/?probe=4a17b0a89d) | Oct 22, 2022 |
| Intel         | Montevina CRB               | Notebook    | [11cb344c52](https://linux-hardware.org/?probe=11cb344c52) | Oct 22, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [c8a0b8e94f](https://linux-hardware.org/?probe=c8a0b8e94f) | Oct 20, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [2413dd813b](https://linux-hardware.org/?probe=2413dd813b) | Oct 19, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [d565cdf4a5](https://linux-hardware.org/?probe=d565cdf4a5) | Oct 19, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [3b8ac4e243](https://linux-hardware.org/?probe=3b8ac4e243) | Oct 19, 2022 |
| Positivo      | AT300i                      | Notebook    | [02190f570b](https://linux-hardware.org/?probe=02190f570b) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c4a0f6af56](https://linux-hardware.org/?probe=c4a0f6af56) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [cde8c87a3a](https://linux-hardware.org/?probe=cde8c87a3a) | Oct 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1be458024b](https://linux-hardware.org/?probe=1be458024b) | Oct 15, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [603fc4f4cd](https://linux-hardware.org/?probe=603fc4f4cd) | Oct 15, 2022 |
| Dell          | Latitude E5450              | Notebook    | [68e2c17e2f](https://linux-hardware.org/?probe=68e2c17e2f) | Oct 15, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [85f4236c50](https://linux-hardware.org/?probe=85f4236c50) | Oct 15, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| BANGHO        | B801 IP-M23.62.06           | All in one  | [5a66a855a8](https://linux-hardware.org/?probe=5a66a855a8) | Oct 14, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [a14b57c22c](https://linux-hardware.org/?probe=a14b57c22c) | Oct 14, 2022 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [6a810d253c](https://linux-hardware.org/?probe=6a810d253c) | Oct 13, 2022 |
| Dell          | Latitude 7420               | Convertible | [dade6a2b21](https://linux-hardware.org/?probe=dade6a2b21) | Oct 13, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [13e68d4364](https://linux-hardware.org/?probe=13e68d4364) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [1444f8cc5b](https://linux-hardware.org/?probe=1444f8cc5b) | Oct 12, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [31fbbb40a0](https://linux-hardware.org/?probe=31fbbb40a0) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [77d21da9a2](https://linux-hardware.org/?probe=77d21da9a2) | Oct 11, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [477851891a](https://linux-hardware.org/?probe=477851891a) | Oct 11, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7dcd7050ae](https://linux-hardware.org/?probe=7dcd7050ae) | Oct 10, 2022 |
| Positivo      | AT300i                      | Notebook    | [62b9d61028](https://linux-hardware.org/?probe=62b9d61028) | Oct 09, 2022 |
| Positivo      | AT300i                      | Notebook    | [8bbd312832](https://linux-hardware.org/?probe=8bbd312832) | Oct 09, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [6ea2c2d73b](https://linux-hardware.org/?probe=6ea2c2d73b) | Oct 08, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [7f78dda318](https://linux-hardware.org/?probe=7f78dda318) | Oct 07, 2022 |
| HP            | 339A                        | Desktop     | [0cb27058b8](https://linux-hardware.org/?probe=0cb27058b8) | Oct 07, 2022 |
| ASUSTek       | X505BP                      | Notebook    | [3ebba89d5e](https://linux-hardware.org/?probe=3ebba89d5e) | Oct 07, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [c621294169](https://linux-hardware.org/?probe=c621294169) | Oct 07, 2022 |
| Samsung       | 530U4E/540U4E               | Notebook    | [11ed7b9f37](https://linux-hardware.org/?probe=11ed7b9f37) | Oct 07, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| BANGHO        | GAMER GM-X 15s              | Notebook    | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [0a022a22c6](https://linux-hardware.org/?probe=0a022a22c6) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7ed786bee9](https://linux-hardware.org/?probe=7ed786bee9) | Sep 30, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [51a7f36a69](https://linux-hardware.org/?probe=51a7f36a69) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| Biostar       | H55 HD                      | Desktop     | [bde8e0a133](https://linux-hardware.org/?probe=bde8e0a133) | Sep 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [d5a4d2ae41](https://linux-hardware.org/?probe=d5a4d2ae41) | Sep 28, 2022 |
| Positivo      | SW6H                        | Notebook    | [4cfa6665bb](https://linux-hardware.org/?probe=4cfa6665bb) | Sep 27, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| System76      | Lemur Pro                   | Notebook    | [35340e6221](https://linux-hardware.org/?probe=35340e6221) | Sep 26, 2022 |
| NSX           | Celeron 14                  | Notebook    | [b8fdb14beb](https://linux-hardware.org/?probe=b8fdb14beb) | Sep 25, 2022 |
| NSX           | Celeron 14                  | Notebook    | [1d358a2828](https://linux-hardware.org/?probe=1d358a2828) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [f038a5908f](https://linux-hardware.org/?probe=f038a5908f) | Sep 23, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [2250b3380d](https://linux-hardware.org/?probe=2250b3380d) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [628fd0d32d](https://linux-hardware.org/?probe=628fd0d32d) | Sep 21, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [b07937de6a](https://linux-hardware.org/?probe=b07937de6a) | Sep 20, 2022 |
| BANGHO        | BES G1529                   | Notebook    | [ce0db88361](https://linux-hardware.org/?probe=ce0db88361) | Sep 20, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [75854836f7](https://linux-hardware.org/?probe=75854836f7) | Sep 20, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [e4e09c23e5](https://linux-hardware.org/?probe=e4e09c23e5) | Sep 19, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [f52b35d82d](https://linux-hardware.org/?probe=f52b35d82d) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b3350b3f69](https://linux-hardware.org/?probe=b3350b3f69) | Sep 17, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ee09885560](https://linux-hardware.org/?probe=ee09885560) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d4d8cc3f34](https://linux-hardware.org/?probe=d4d8cc3f34) | Sep 16, 2022 |
| Exo           | Smart XL4                   | Notebook    | [96f159b86f](https://linux-hardware.org/?probe=96f159b86f) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | Desktop     | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| HP            | Pavilion 17                 | Notebook    | [5d9be9b086](https://linux-hardware.org/?probe=5d9be9b086) | Sep 13, 2022 |
| Dell          | Precision 5550              | Notebook    | [82eebd67fd](https://linux-hardware.org/?probe=82eebd67fd) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [89339e48f1](https://linux-hardware.org/?probe=89339e48f1) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [d39dcbc8ed](https://linux-hardware.org/?probe=d39dcbc8ed) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [105dae5731](https://linux-hardware.org/?probe=105dae5731) | Sep 11, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [c9b78bb640](https://linux-hardware.org/?probe=c9b78bb640) | Sep 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [7d108d27ee](https://linux-hardware.org/?probe=7d108d27ee) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [a877bbf17d](https://linux-hardware.org/?probe=a877bbf17d) | Sep 09, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [86af6e4676](https://linux-hardware.org/?probe=86af6e4676) | Sep 08, 2022 |
| HP            | 245 G6                      | Notebook    | [054d226709](https://linux-hardware.org/?probe=054d226709) | Sep 07, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [35ead5350d](https://linux-hardware.org/?probe=35ead5350d) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c905c86c47](https://linux-hardware.org/?probe=c905c86c47) | Sep 07, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [efb1e9883d](https://linux-hardware.org/?probe=efb1e9883d) | Sep 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [20178af23f](https://linux-hardware.org/?probe=20178af23f) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [fc5e3d8261](https://linux-hardware.org/?probe=fc5e3d8261) | Sep 05, 2022 |
| Intel         | powered classmate PC        | Notebook    | [ed36baccf9](https://linux-hardware.org/?probe=ed36baccf9) | Aug 31, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [115b09b849](https://linux-hardware.org/?probe=115b09b849) | Aug 30, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [373a11a297](https://linux-hardware.org/?probe=373a11a297) | Aug 29, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [505eb9a97c](https://linux-hardware.org/?probe=505eb9a97c) | Aug 29, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [c107217cf8](https://linux-hardware.org/?probe=c107217cf8) | Aug 28, 2022 |
| BANGHO        | AERO X2 I1002               | Notebook    | [f24ddb9619](https://linux-hardware.org/?probe=f24ddb9619) | Aug 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [11cd220cfd](https://linux-hardware.org/?probe=11cd220cfd) | Aug 27, 2022 |
| Exo           | Smart Serie L               | Notebook    | [5cbaef571b](https://linux-hardware.org/?probe=5cbaef571b) | Aug 27, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [9fe64d4a60](https://linux-hardware.org/?probe=9fe64d4a60) | Aug 27, 2022 |
| HP            | Notebook                    | Notebook    | [2d11bc2975](https://linux-hardware.org/?probe=2d11bc2975) | Aug 26, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [c824203d0a](https://linux-hardware.org/?probe=c824203d0a) | Aug 24, 2022 |
| Standard      | AHV                         | Notebook    | [1a4d477350](https://linux-hardware.org/?probe=1a4d477350) | Aug 24, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [c3ddddae2c](https://linux-hardware.org/?probe=c3ddddae2c) | Aug 24, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6c0183592b](https://linux-hardware.org/?probe=6c0183592b) | Aug 23, 2022 |
| Sony          | VGN-NR210FH                 | Notebook    | [8c007bfa55](https://linux-hardware.org/?probe=8c007bfa55) | Aug 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [d4a7a111a7](https://linux-hardware.org/?probe=d4a7a111a7) | Aug 21, 2022 |
| Novatech      | C141WP-I5HS                 | Notebook    | [767c02caeb](https://linux-hardware.org/?probe=767c02caeb) | Aug 20, 2022 |
| Compaq        | Presario 21 VerX            | Notebook    | [97aa39b2ca](https://linux-hardware.org/?probe=97aa39b2ca) | Aug 19, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | Notebook    | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [0dbc32a26d](https://linux-hardware.org/?probe=0dbc32a26d) | Aug 17, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [58f88a4494](https://linux-hardware.org/?probe=58f88a4494) | Aug 17, 2022 |
| HP            | Notebook                    | Notebook    | [784ad31f68](https://linux-hardware.org/?probe=784ad31f68) | Aug 17, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [e68b5affa4](https://linux-hardware.org/?probe=e68b5affa4) | Aug 16, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [7c3e324e4f](https://linux-hardware.org/?probe=7c3e324e4f) | Aug 16, 2022 |
| PCBOX         | Kant                        | Notebook    | [1b5c160d93](https://linux-hardware.org/?probe=1b5c160d93) | Aug 16, 2022 |
| Dell          | Latitude E6510              | Notebook    | [2a4c496cce](https://linux-hardware.org/?probe=2a4c496cce) | Aug 15, 2022 |
| ASRock        | H55M                        | Desktop     | [8d0bd0d2d2](https://linux-hardware.org/?probe=8d0bd0d2d2) | Aug 15, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [d5862f21f5](https://linux-hardware.org/?probe=d5862f21f5) | Aug 14, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [c001e6e62b](https://linux-hardware.org/?probe=c001e6e62b) | Aug 12, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [d08cbbc3d8](https://linux-hardware.org/?probe=d08cbbc3d8) | Aug 12, 2022 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [6b5082a45c](https://linux-hardware.org/?probe=6b5082a45c) | Aug 12, 2022 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [d77caddb55](https://linux-hardware.org/?probe=d77caddb55) | Aug 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [2f3db9cd91](https://linux-hardware.org/?probe=2f3db9cd91) | Aug 12, 2022 |
| HP            | Pavilion 17                 | Notebook    | [25a07691ec](https://linux-hardware.org/?probe=25a07691ec) | Aug 12, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [fad6aace6a](https://linux-hardware.org/?probe=fad6aace6a) | Aug 11, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [cac00fb432](https://linux-hardware.org/?probe=cac00fb432) | Aug 11, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [15488377fb](https://linux-hardware.org/?probe=15488377fb) | Aug 10, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [5484873fd7](https://linux-hardware.org/?probe=5484873fd7) | Aug 10, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [31bdc504d4](https://linux-hardware.org/?probe=31bdc504d4) | Aug 10, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [a6f68827fb](https://linux-hardware.org/?probe=a6f68827fb) | Aug 09, 2022 |
| NVN-ED01      | Unknown                     | Notebook    | [0a677cad6c](https://linux-hardware.org/?probe=0a677cad6c) | Aug 09, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [b8ae818291](https://linux-hardware.org/?probe=b8ae818291) | Aug 08, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [b07157a232](https://linux-hardware.org/?probe=b07157a232) | Aug 08, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [18d8a04343](https://linux-hardware.org/?probe=18d8a04343) | Aug 08, 2022 |
| Toshiba       | Satellite Pro L300D         | Notebook    | [b3ed30ac52](https://linux-hardware.org/?probe=b3ed30ac52) | Aug 07, 2022 |
| MSI           | CR620                       | Notebook    | [517b816cd7](https://linux-hardware.org/?probe=517b816cd7) | Aug 06, 2022 |
| Intel         | 945GCT-M                    | Desktop     | [0481d5180e](https://linux-hardware.org/?probe=0481d5180e) | Aug 06, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [ab52d0fc52](https://linux-hardware.org/?probe=ab52d0fc52) | Aug 05, 2022 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [0b4eaa2b43](https://linux-hardware.org/?probe=0b4eaa2b43) | Aug 03, 2022 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [beaaaa6f6e](https://linux-hardware.org/?probe=beaaaa6f6e) | Aug 03, 2022 |
| LG Electro... | R480-L.B211P1               | Notebook    | [307f422c53](https://linux-hardware.org/?probe=307f422c53) | Aug 03, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [e586e6ee53](https://linux-hardware.org/?probe=e586e6ee53) | Aug 02, 2022 |
| Intel         | DH55HC AAE70933-502         | Desktop     | [a484fb9cc8](https://linux-hardware.org/?probe=a484fb9cc8) | Aug 02, 2022 |
| Exo           | Exomate X352                | Notebook    | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [0b8452087a](https://linux-hardware.org/?probe=0b8452087a) | Aug 02, 2022 |
| Toshiba       | Satellite-C845              | Notebook    | [6ee9ea90a5](https://linux-hardware.org/?probe=6ee9ea90a5) | Aug 01, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [72278643e8](https://linux-hardware.org/?probe=72278643e8) | Aug 01, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [047d3c88ad](https://linux-hardware.org/?probe=047d3c88ad) | Jul 31, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [5a3ed0cf62](https://linux-hardware.org/?probe=5a3ed0cf62) | Jul 30, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [719bbf817c](https://linux-hardware.org/?probe=719bbf817c) | Jul 30, 2022 |
| MSI           | B550M-A PRO                 | Desktop     | [14bbcb7e47](https://linux-hardware.org/?probe=14bbcb7e47) | Jul 30, 2022 |
| ASRock        | Z97 Pro4                    | Desktop     | [0db03812df](https://linux-hardware.org/?probe=0db03812df) | Jul 29, 2022 |
| MSI           | Z370 GAMING M5              | Desktop     | [b9ec9e3dd4](https://linux-hardware.org/?probe=b9ec9e3dd4) | Jul 28, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [eb92148078](https://linux-hardware.org/?probe=eb92148078) | Jul 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | ThinkPad T480s 20L8S31T0... | Notebook    | [60449c872b](https://linux-hardware.org/?probe=60449c872b) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [cea12b9c9c](https://linux-hardware.org/?probe=cea12b9c9c) | Jul 27, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [a2c2f04e29](https://linux-hardware.org/?probe=a2c2f04e29) | Jul 26, 2022 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [88b45b1956](https://linux-hardware.org/?probe=88b45b1956) | Jul 26, 2022 |
| ASUSTek       | X550ZA                      | Notebook    | [00126a3052](https://linux-hardware.org/?probe=00126a3052) | Jul 25, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [7ffde486ac](https://linux-hardware.org/?probe=7ffde486ac) | Jul 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f84af529bb](https://linux-hardware.org/?probe=f84af529bb) | Jul 24, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [df98c1834c](https://linux-hardware.org/?probe=df98c1834c) | Jul 23, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [72a44c6eea](https://linux-hardware.org/?probe=72a44c6eea) | Jul 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [73a12fbe59](https://linux-hardware.org/?probe=73a12fbe59) | Jul 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Argentina/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 251       | 11.56%  |
| Ubuntu 18.04                 | 177       | 8.15%   |
| Ubuntu 22.04                 | 133       | 6.12%   |
| Debian 11                    | 75        | 3.45%   |
| OpenMandriva 4.3             | 57        | 2.62%   |
| OpenMandriva 4.2             | 56        | 2.58%   |
| Zorin 16                     | 39        | 1.8%    |
| Arch Rolling                 | 39        | 1.8%    |
| Zorin 15                     | 37        | 1.7%    |
| Manjaro                      | 33        | 1.52%   |
| Linux Mint 20.3              | 31        | 1.43%   |
| Linux Mint 20.2              | 31        | 1.43%   |
| Fedora 38                    | 28        | 1.29%   |
| Xubuntu 20.04                | 26        | 1.2%    |
| Linux Mint 20.1              | 26        | 1.2%    |
| Linux Mint 20                | 26        | 1.2%    |
| ArcoLinux Rolling            | 26        | 1.2%    |
| KDE neon 20.04               | 25        | 1.15%   |
| Pop!_OS 22.04                | 24        | 1.1%    |
| Linux Mint 19.3              | 24        | 1.1%    |
| Fedora 36                    | 24        | 1.1%    |
| BlackPanther 18.1            | 24        | 1.1%    |
| Linux Mint 21.1              | 23        | 1.06%   |
| Linux Mint 21.2              | 22        | 1.01%   |
| Ubuntu 19.04                 | 21        | 0.97%   |
| OpenMandriva 23.03           | 21        | 0.97%   |
| Arch                         | 20        | 0.92%   |
| Xubuntu 18.04                | 18        | 0.83%   |
| Fedora 33                    | 18        | 0.83%   |
| openSUSE Tumbleweed-XXXXXXXX | 17        | 0.78%   |
| Ubuntu 19.10                 | 16        | 0.74%   |
| Pop!_OS 21.04                | 16        | 0.74%   |
| Kubuntu 20.04                | 16        | 0.74%   |
| Ubuntu MATE 20.04            | 15        | 0.69%   |
| Ubuntu 21.04                 | 15        | 0.69%   |
| Kubuntu 22.04                | 15        | 0.69%   |
| Ubuntu 21.10                 | 14        | 0.64%   |
| Fedora 37                    | 14        | 0.64%   |
| Fedora 34                    | 14        | 0.64%   |
| Fedora 32                    | 14        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 655       | 31.69%  |
| Linux Mint    | 199       | 9.63%   |
| OpenMandriva  | 160       | 7.74%   |
| Fedora        | 126       | 6.1%    |
| Debian        | 117       | 5.66%   |
| Zorin         | 78        | 3.77%   |
| Pop!_OS       | 66        | 3.19%   |
| Xubuntu       | 58        | 2.81%   |
| Manjaro       | 58        | 2.81%   |
| Arch          | 57        | 2.76%   |
| Kubuntu       | 40        | 1.94%   |
| Endless       | 40        | 1.94%   |
| KDE neon      | 34        | 1.64%   |
| ArcoLinux     | 27        | 1.31%   |
| Elementary    | 26        | 1.26%   |
| Ubuntu MATE   | 24        | 1.16%   |
| BlackPanther  | 24        | 1.16%   |
| ROSA          | 23        | 1.11%   |
| Lubuntu       | 23        | 1.11%   |
| openSUSE      | 21        | 1.02%   |
| Nobara        | 19        | 0.92%   |
| Ubuntu Budgie | 14        | 0.68%   |
| Ubuntu Unity  | 12        | 0.58%   |
| LMDE          | 12        | 0.58%   |
| EndeavourOS   | 12        | 0.58%   |
| Clear Linux   | 12        | 0.58%   |
| Xero          | 11        | 0.53%   |
| Kali          | 9         | 0.44%   |
| Peppermint    | 8         | 0.39%   |
| Gentoo        | 8         | 0.39%   |
| MX            | 7         | 0.34%   |
| UbuntuDDE     | 6         | 0.29%   |
| Huayra        | 5         | 0.24%   |
| LinuxFX       | 4         | 0.19%   |
| Void Linux    | 3         | 0.15%   |
| SteamOS       | 3         | 0.15%   |
| Solus         | 3         | 0.15%   |
| Rocky Linux   | 3         | 0.15%   |
| RHEL          | 3         | 0.15%   |
| Parrot        | 3         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 54        | 2.28%   |
| 5.16.7-desktop-1omv4003  | 53        | 2.24%   |
| 5.4.0-42-generic         | 44        | 1.86%   |
| 5.4.0-26-generic         | 25        | 1.06%   |
| 4.18.16-desktop-1bP      | 23        | 0.97%   |
| 6.2.6-desktop-1omv2390   | 20        | 0.85%   |
| 5.4.0-52-generic         | 20        | 0.85%   |
| 5.4.0-48-generic         | 20        | 0.85%   |
| 5.3.0-40-generic         | 17        | 0.72%   |
| 5.15.0-41-generic        | 16        | 0.68%   |
| 5.15.0-52-generic        | 15        | 0.63%   |
| 5.4.0-91-generic         | 14        | 0.59%   |
| 5.4.0-40-generic         | 14        | 0.59%   |
| 5.4.0-37-generic         | 14        | 0.59%   |
| 5.3.0-28-generic         | 14        | 0.59%   |
| 5.4.0-74-generic         | 13        | 0.55%   |
| 5.3.0-46-generic         | 13        | 0.55%   |
| 5.15.0-56-generic        | 13        | 0.55%   |
| 5.8.0-53-generic         | 12        | 0.51%   |
| 5.4.0-72-generic         | 12        | 0.51%   |
| 5.4.0-58-generic         | 12        | 0.51%   |
| 5.4.0-29-generic         | 12        | 0.51%   |
| 5.3.0-53-generic         | 12        | 0.51%   |
| 5.15.0-46-generic        | 12        | 0.51%   |
| 5.11.0-27-generic        | 12        | 0.51%   |
| 6.2.0-26-generic         | 11        | 0.47%   |
| 5.4.0-80-generic         | 11        | 0.47%   |
| 5.4.0-47-generic         | 11        | 0.47%   |
| 5.4.0-19-generic         | 11        | 0.47%   |
| 5.19.0-35-generic        | 11        | 0.47%   |
| 5.15.0-76-generic        | 11        | 0.47%   |
| 5.15.0-48-generic        | 11        | 0.47%   |
| 5.13.0-28-generic        | 11        | 0.47%   |
| 5.8.0-43-generic         | 10        | 0.42%   |
| 5.4.0-45-generic         | 10        | 0.42%   |
| 5.15.0-78-generic        | 10        | 0.42%   |
| 5.11.0-37-generic        | 10        | 0.42%   |
| 4.18.0-15-generic        | 10        | 0.42%   |
| 6.4.11-desktop-1omv2390  | 9         | 0.38%   |
| 6.2.0-35-generic         | 9         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 378       | 17%     |
| 5.15.0  | 199       | 8.95%   |
| 4.15.0  | 122       | 5.49%   |
| 5.8.0   | 97        | 4.36%   |
| 5.3.0   | 96        | 4.32%   |
| 5.10.0  | 86        | 3.87%   |
| 5.11.0  | 78        | 3.51%   |
| 5.13.0  | 74        | 3.33%   |
| 5.19.0  | 63        | 2.83%   |
| 6.2.0   | 59        | 2.65%   |
| 5.10.14 | 55        | 2.47%   |
| 5.0.0   | 55        | 2.47%   |
| 5.16.7  | 53        | 2.38%   |
| 4.18.0  | 52        | 2.34%   |
| 6.2.6   | 28        | 1.26%   |
| 4.19.0  | 28        | 1.26%   |
| 6.1.0   | 24        | 1.08%   |
| 4.18.16 | 24        | 1.08%   |
| 6.4.11  | 13        | 0.58%   |
| 6.1.1   | 11        | 0.49%   |
| 5.14.0  | 10        | 0.45%   |
| 6.6.2   | 8         | 0.36%   |
| 6.5.5   | 8         | 0.36%   |
| 5.17.5  | 8         | 0.36%   |
| 6.5.0   | 7         | 0.31%   |
| 6.4.8   | 7         | 0.31%   |
| 6.3.5   | 7         | 0.31%   |
| 6.2.8   | 7         | 0.31%   |
| 5.15.5  | 7         | 0.31%   |
| 5.11.12 | 7         | 0.31%   |
| 4.4.0   | 7         | 0.31%   |
| 6.5.9   | 6         | 0.27%   |
| 6.0.8   | 6         | 0.27%   |
| 6.0.0   | 6         | 0.27%   |
| 5.18.0  | 6         | 0.27%   |
| 5.13.13 | 6         | 0.27%   |
| 6.4.12  | 5         | 0.22%   |
| 6.0.9   | 5         | 0.22%   |
| 5.18.5  | 5         | 0.22%   |
| 5.18.16 | 5         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 393       | 17.95%  |
| 5.15    | 242       | 11.05%  |
| 5.10    | 175       | 7.99%   |
| 4.15    | 122       | 5.57%   |
| 5.8     | 120       | 5.48%   |
| 6.2     | 111       | 5.07%   |
| 5.11    | 99        | 4.52%   |
| 5.3     | 98        | 4.47%   |
| 5.13    | 95        | 4.34%   |
| 5.19    | 87        | 3.97%   |
| 5.16    | 78        | 3.56%   |
| 4.18    | 78        | 3.56%   |
| 6.1     | 61        | 2.79%   |
| 5.0     | 59        | 2.69%   |
| 6.4     | 40        | 1.83%   |
| 6.5     | 38        | 1.74%   |
| 5.18    | 37        | 1.69%   |
| 6.0     | 36        | 1.64%   |
| 4.19    | 31        | 1.42%   |
| 5.17    | 24        | 1.1%    |
| 6.3     | 22        | 1%      |
| 5.14    | 22        | 1%      |
| 6.6     | 18        | 0.82%   |
| 5.9     | 18        | 0.82%   |
| 4.9     | 18        | 0.82%   |
| 5.6     | 16        | 0.73%   |
| 5.7     | 12        | 0.55%   |
| 5.12    | 12        | 0.55%   |
| 4.4     | 8         | 0.37%   |
| 5.5     | 6         | 0.27%   |
| 4.1     | 3         | 0.14%   |
| 4.20    | 2         | 0.09%   |
| 4.13    | 2         | 0.09%   |
| 3.10    | 2         | 0.09%   |
| 5.2     | 1         | 0.05%   |
| 5.1     | 1         | 0.05%   |
| 4.17    | 1         | 0.05%   |
| 4.10    | 1         | 0.05%   |
| 3.16    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1897      | 95.23%  |
| i686    | 90        | 4.52%   |
| aarch64 | 3         | 0.15%   |
| armv7l  | 2         | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 836       | 40.39%  |
| KDE5             | 353       | 17.05%  |
| Unknown          | 211       | 10.19%  |
| XFCE             | 206       | 9.95%   |
| X-Cinnamon       | 136       | 6.57%   |
| MATE             | 93        | 4.49%   |
| KDE              | 42        | 2.03%   |
| LXQt             | 31        | 1.5%    |
| Pantheon         | 24        | 1.16%   |
| LXDE             | 22        | 1.06%   |
| Cinnamon         | 17        | 0.82%   |
| Budgie           | 16        | 0.77%   |
| KDE4             | 14        | 0.68%   |
| Unity            | 12        | 0.58%   |
| i3               | 12        | 0.58%   |
| Deepin           | 9         | 0.43%   |
| Qtile            | 4         | 0.19%   |
| lightdm-xsession | 4         | 0.19%   |
| xmonad           | 3         | 0.14%   |
| GNOME Flashback  | 3         | 0.14%   |
| dwm              | 3         | 0.14%   |
| bspwm            | 3         | 0.14%   |
| trinity          | 2         | 0.1%    |
| openbox          | 2         | 0.1%    |
| i3-with-shmlog   | 2         | 0.1%    |
| Hyprland         | 2         | 0.1%    |
| Cutefish         | 2         | 0.1%    |
| UKUI             | 1         | 0.05%   |
| sway             | 1         | 0.05%   |
| icewm            | 1         | 0.05%   |
| Enlightenment    | 1         | 0.05%   |
| BunsenLabs       | 1         | 0.05%   |
| awesome          | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1570      | 76.85%  |
| Wayland | 340       | 16.64%  |
| Unknown | 114       | 5.58%   |
| Tty     | 19        | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1062      | 51.53%  |
| SDDM    | 324       | 15.72%  |
| LightDM | 212       | 10.29%  |
| GDM3    | 200       | 9.7%    |
| GDM     | 184       | 8.93%   |
| TDM     | 49        | 2.38%   |
| KDM     | 14        | 0.68%   |
| LXDM    | 5         | 0.24%   |
| SLiM    | 4         | 0.19%   |
| XDM     | 3         | 0.15%   |
| GREETD  | 2         | 0.1%    |
| SLIMSKI | 1         | 0.05%   |
| Ly      | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| es_AR       | 1114      | 54.24%  |
| en_US       | 481       | 23.42%  |
| Unknown     | 211       | 10.27%  |
| es_ES       | 120       | 5.84%   |
| es_MX       | 54        | 2.63%   |
| C           | 32        | 1.56%   |
| en_GB       | 13        | 0.63%   |
| pt_BR       | 5         | 0.24%   |
| POSIX       | 3         | 0.15%   |
| es_US       | 3         | 0.15%   |
| es_CL       | 3         | 0.15%   |
| it_IT       | 2         | 0.1%    |
| es_UY       | 2         | 0.1%    |
| en_AG       | 2         | 0.1%    |
| UTF-8       | 1         | 0.05%   |
| ru_RU       | 1         | 0.05%   |
| fr_FR       | 1         | 0.05%   |
| es_DO       | 1         | 0.05%   |
| es_AR.UtF-8 | 1         | 0.05%   |
| en_UTF-8    | 1         | 0.05%   |
| en_US.UTF8  | 1         | 0.05%   |
| en_CA       | 1         | 0.05%   |
| C.UTF8      | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1143      | 56.06%  |
| EFI  | 896       | 43.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1561      | 76.3%   |
| Overlay | 179       | 8.75%   |
| Btrfs   | 161       | 7.87%   |
| Unknown | 52        | 2.54%   |
| Tmpfs   | 51        | 2.49%   |
| Xfs     | 23        | 1.12%   |
| Zfs     | 8         | 0.39%   |
| Ext2    | 5         | 0.24%   |
| Ext3    | 3         | 0.15%   |
| F2fs    | 2         | 0.1%    |
| Aufs    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1116      | 54.79%  |
| GPT     | 668       | 32.79%  |
| MBR     | 253       | 12.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1731      | 85.48%  |
| Yes       | 294       | 14.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1380      | 68.11%  |
| Yes       | 646       | 31.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 367       | 18.42%  |
| Lenovo                  | 271       | 13.6%   |
| Gigabyte Technology     | 250       | 12.55%  |
| Hewlett-Packard         | 164       | 8.23%   |
| Dell                    | 152       | 7.63%   |
| MSI                     | 125       | 6.28%   |
| ASRock                  | 107       | 5.37%   |
| BANGHO                  | 58        | 2.91%   |
| Intel                   | 55        | 2.76%   |
| Acer                    | 53        | 2.66%   |
| Exo                     | 36        | 1.81%   |
| Toshiba                 | 34        | 1.71%   |
| Samsung Electronics     | 29        | 1.46%   |
| Positivo                | 27        | 1.36%   |
| ECS                     | 22        | 1.1%    |
| Sony                    | 19        | 0.95%   |
| Apple                   | 19        | 0.95%   |
| Unknown                 | 18        | 0.9%    |
| Biostar                 | 16        | 0.8%    |
| Juana Manso             | 9         | 0.45%   |
| Compal                  | 9         | 0.45%   |
| AMI                     | 9         | 0.45%   |
| Clevo                   | 8         | 0.4%    |
| Coradir                 | 7         | 0.35%   |
| Foxconn                 | 6         | 0.3%    |
| Advantec                | 6         | 0.3%    |
| Standard                | 5         | 0.25%   |
| Quanta                  | 5         | 0.25%   |
| NSX                     | 5         | 0.25%   |
| Novatech                | 5         | 0.25%   |
| NOBLEX                  | 5         | 0.25%   |
| HUAWEI                  | 5         | 0.25%   |
| System76                | 4         | 0.2%    |
| A-DATA Technology       | 4         | 0.2%    |
| Raspberry Pi Foundation | 3         | 0.15%   |
| PCChips                 | 3         | 0.15%   |
| PCBOX                   | 3         | 0.15%   |
| Kelyx Argentina         | 3         | 0.15%   |
| Kanji                   | 3         | 0.15%   |
| AIR                     | 3         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 33        | 1.66%   |
| MSI MS-7721                            | 25        | 1.26%   |
| ASUS All Series                        | 19        | 0.95%   |
| ASUS PRIME A320M-K                     | 18        | 0.9%    |
| Gigabyte F2A68HM-H                     | 14        | 0.7%    |
| Gigabyte H81M-H                        | 12        | 0.6%    |
| BANGHO Suma 1025                       | 12        | 0.6%    |
| Lenovo V330-15IKB 81AX                 | 10        | 0.5%    |
| BANGHO MOV                             | 10        | 0.5%    |
| Juana Manso SF20GM7                    | 9         | 0.45%   |
| ASUS PRIME B450M-A                     | 9         | 0.45%   |
| MSI MS-7C52                            | 8         | 0.4%    |
| HP Notebook                            | 8         | 0.4%    |
| Gigabyte M68MT-S2                      | 8         | 0.4%    |
| Gigabyte H110M-H                       | 8         | 0.4%    |
| Gigabyte A320M-S2H                     | 8         | 0.4%    |
| ASUS P5KPL-AM SE                       | 8         | 0.4%    |
| Lenovo ThinkPad L15 Gen 2 20X4S27200   | 7         | 0.35%   |
| Lenovo G470 20078                      | 7         | 0.35%   |
| Intel powered classmate PC             | 7         | 0.35%   |
| HP Laptop 15-bs0xx                     | 7         | 0.35%   |
| Gigabyte H61M-S1                       | 7         | 0.35%   |
| Coradir Coradir/ES10IS5                | 7         | 0.35%   |
| BANGHO MAX G0101                       | 7         | 0.35%   |
| ASUS H61M-K                            | 7         | 0.35%   |
| MSI MS-7A15                            | 6         | 0.3%    |
| HP Pavilion dv6                        | 6         | 0.3%    |
| Gigabyte F2A55M-HD2                    | 6         | 0.3%    |
| Gigabyte A320M-H                       | 6         | 0.3%    |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA | 6         | 0.3%    |
| ASUS ROG STRIX B550-F GAMING           | 6         | 0.3%    |
| ASRock N68-VS3 FX                      | 6         | 0.3%    |
| ASRock FM2A68M-DG3+                    | 6         | 0.3%    |
| MSI MS-7309                            | 5         | 0.25%   |
| Lenovo G550 2958                       | 5         | 0.25%   |
| Gigabyte A320M-S2H V2                  | 5         | 0.25%   |
| Exo CloudbookE15                       | 5         | 0.25%   |
| ECS H81H3-M4                           | 5         | 0.25%   |
| Dell Latitude 3520                     | 5         | 0.25%   |
| Dell Inspiron 1525                     | 5         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 92        | 4.62%   |
| Dell Inspiron       | 71        | 3.56%   |
| ASUS PRIME          | 62        | 3.11%   |
| Lenovo IdeaPad      | 56        | 2.81%   |
| Dell Latitude       | 51        | 2.56%   |
| HP Pavilion         | 44        | 2.21%   |
| Acer Aspire         | 44        | 2.21%   |
| ASUS VivoBook       | 42        | 2.11%   |
| Unknown             | 33        | 1.66%   |
| MSI MS-7721         | 25        | 1.26%   |
| HP Laptop           | 23        | 1.15%   |
| Toshiba Satellite   | 21        | 1.05%   |
| ASUS All            | 19        | 0.95%   |
| HP Compaq           | 17        | 0.85%   |
| Exo Smart           | 16        | 0.8%    |
| Lenovo ThinkBook    | 15        | 0.75%   |
| ASUS ROG            | 15        | 0.75%   |
| Gigabyte F2A68HM-H  | 14        | 0.7%    |
| Gigabyte A320M-S2H  | 13        | 0.65%   |
| BANGHO Suma         | 13        | 0.65%   |
| Gigabyte H81M-H     | 12        | 0.6%    |
| BANGHO MAX          | 12        | 0.6%    |
| HP 250              | 11        | 0.55%   |
| Dell OptiPlex       | 11        | 0.55%   |
| ASUS M5A78L-M       | 11        | 0.55%   |
| Lenovo V330-15IKB   | 10        | 0.5%    |
| Lenovo ThinkCentre  | 10        | 0.5%    |
| BANGHO MOV          | 10        | 0.5%    |
| Juana Manso SF20GM7 | 9         | 0.45%   |
| HP EliteBook        | 9         | 0.45%   |
| Gigabyte B450M      | 9         | 0.45%   |
| ASUS TUF            | 9         | 0.45%   |
| MSI MS-7C52         | 8         | 0.4%    |
| Lenovo Yoga         | 8         | 0.4%    |
| HP Notebook         | 8         | 0.4%    |
| Gigabyte M68MT-S2   | 8         | 0.4%    |
| Gigabyte H110M-H    | 8         | 0.4%    |
| Gigabyte B450       | 8         | 0.4%    |
| ASUS ZenBook        | 8         | 0.4%    |
| ASUS P5KPL-AM       | 8         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 180       | 9.04%   |
| 2017    | 175       | 8.79%   |
| 2021    | 149       | 7.48%   |
| 2018    | 147       | 7.38%   |
| 2011    | 145       | 7.28%   |
| 2020    | 144       | 7.23%   |
| 2019    | 140       | 7.03%   |
| 2014    | 139       | 6.98%   |
| 2013    | 132       | 6.63%   |
| 2010    | 126       | 6.33%   |
| 2015    | 113       | 5.67%   |
| 2016    | 96        | 4.82%   |
| 2009    | 83        | 4.17%   |
| 2008    | 80        | 4.02%   |
| 2007    | 53        | 2.66%   |
| 2006    | 37        | 1.86%   |
| 2022    | 25        | 1.26%   |
| Unknown | 11        | 0.55%   |
| 2023    | 8         | 0.4%    |
| 2004    | 5         | 0.25%   |
| 2005    | 3         | 0.15%   |
| 2001    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1058      | 53.11%  |
| Desktop        | 847       | 42.52%  |
| Convertible    | 32        | 1.61%   |
| Tablet         | 20        | 1%      |
| Mini pc        | 15        | 0.75%   |
| All in one     | 14        | 0.7%    |
| System on chip | 4         | 0.2%    |
| Other          | 1         | 0.05%   |
| Server         | 1         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1874      | 93.42%  |
| Enabled  | 132       | 6.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1990      | 99.9%   |
| Yes  | 2         | 0.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 491       | 24.26%  |
| 4.01-8.0    | 488       | 24.11%  |
| 8.01-16.0   | 374       | 18.48%  |
| 16.01-24.0  | 282       | 13.93%  |
| 1.01-2.0    | 166       | 8.2%    |
| 32.01-64.0  | 109       | 5.39%   |
| 2.01-3.0    | 44        | 2.17%   |
| 0.51-1.0    | 28        | 1.38%   |
| 24.01-32.0  | 27        | 1.33%   |
| 64.01-256.0 | 14        | 0.69%   |
| 0.01-0.5    | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 798       | 36.36%  |
| 2.01-3.0   | 532       | 24.24%  |
| 4.01-8.0   | 287       | 13.08%  |
| 3.01-4.0   | 257       | 11.71%  |
| 0.51-1.0   | 194       | 8.84%   |
| 8.01-16.0  | 83        | 3.78%   |
| 0.01-0.5   | 32        | 1.46%   |
| 16.01-24.0 | 11        | 0.5%    |
| 24.01-32.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1272      | 62.26%  |
| 2      | 520       | 25.45%  |
| 3      | 158       | 7.73%   |
| 4      | 60        | 2.94%   |
| 5      | 13        | 0.64%   |
| 0      | 11        | 0.54%   |
| 6      | 4         | 0.2%    |
| 7      | 3         | 0.15%   |
| 28     | 1         | 0.05%   |
| 20     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1302      | 64.74%  |
| Yes       | 709       | 35.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1766      | 88.57%  |
| No        | 228       | 11.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1479      | 73.47%  |
| No        | 534       | 26.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1055      | 52.44%  |
| Yes       | 957       | 47.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Argentina | 1992      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Buenos Aires                | 456       | 21.88%  |
| Córdoba                    | 132       | 6.33%   |
| Rosario                     | 94        | 4.51%   |
| La Plata                    | 55        | 2.64%   |
| Mar del Plata               | 52        | 2.5%    |
| Avellaneda                  | 29        | 1.39%   |
| San Miguel de Tucumán      | 28        | 1.34%   |
| Corrientes                  | 28        | 1.34%   |
| Lanus                       | 27        | 1.3%    |
| Mendoza                     | 25        | 1.2%    |
| Quilmes                     | 23        | 1.1%    |
| Lomas de Zamora             | 23        | 1.1%    |
| Resistencia                 | 20        | 0.96%   |
| Villa Ballester             | 19        | 0.91%   |
| Santa Fe                    | 19        | 0.91%   |
| Ituzaingo                   | 19        | 0.91%   |
| Bahía Blanca               | 18        | 0.86%   |
| Paraná                     | 17        | 0.82%   |
| Salta                       | 16        | 0.77%   |
| Ramos Mejia                 | 16        | 0.77%   |
| Posadas                     | 15        | 0.72%   |
| Neuquén                    | 15        | 0.72%   |
| Viedma                      | 14        | 0.67%   |
| Tandil                      | 14        | 0.67%   |
| Florencio Varela            | 14        | 0.67%   |
| Olivos                      | 13        | 0.62%   |
| San Juan                    | 12        | 0.58%   |
| Caseros                     | 12        | 0.58%   |
| Bariloche                   | 12        | 0.58%   |
| San Luis                    | 11        | 0.53%   |
| Burzaco                     | 11        | 0.53%   |
| Tigre                       | 10        | 0.48%   |
| San Telmo                   | 10        | 0.48%   |
| Pilar                       | 10        | 0.48%   |
| Martinez                    | 10        | 0.48%   |
| Godoy Cruz                  | 10        | 0.48%   |
| Villa Nueva                 | 9         | 0.43%   |
| San Nicolás de los Arroyos | 9         | 0.43%   |
| San Martín de los Andes    | 9         | 0.43%   |
| San Francisco               | 9         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 753       | 1144   | 27.32%  |
| Seagate                     | 362       | 469    | 13.13%  |
| Kingston                    | 362       | 456    | 13.13%  |
| Samsung Electronics         | 241       | 333    | 8.74%   |
| Toshiba                     | 218       | 274    | 7.91%   |
| Hitachi                     | 92        | 106    | 3.34%   |
| Sandisk                     | 78        | 111    | 2.83%   |
| Unknown                     | 70        | 89     | 2.54%   |
| HGST                        | 59        | 64     | 2.14%   |
| Gigabyte Technology         | 48        | 73     | 1.74%   |
| A-DATA Technology           | 47        | 53     | 1.71%   |
| SK hynix                    | 46        | 54     | 1.67%   |
| Crucial                     | 45        | 69     | 1.63%   |
| Intel                       | 23        | 42     | 0.83%   |
| Hewlett-Packard             | 20        | 27     | 0.73%   |
| Micron Technology           | 19        | 24     | 0.69%   |
| PNY                         | 15        | 26     | 0.54%   |
| Maxtor                      | 15        | 17     | 0.54%   |
| China                       | 15        | 17     | 0.54%   |
| Corsair                     | 13        | 14     | 0.47%   |
| Realtek Semiconductor       | 11        | 13     | 0.4%    |
| Lexar                       | 11        | 12     | 0.4%    |
| Patriot                     | 10        | 12     | 0.36%   |
| KIOXIA                      | 10        | 10     | 0.36%   |
| XPG                         | 9         | 11     | 0.33%   |
| ADATA Technology            | 9         | 11     | 0.33%   |
| Silicon Motion              | 8         | 9      | 0.29%   |
| Phison Electronics          | 8         | 9      | 0.29%   |
| Kingston Technology Company | 8         | 9      | 0.29%   |
| Unknown                     | 8         | 8      | 0.29%   |
| Kimtigo                     | 7         | 7      | 0.25%   |
| HS-SSD-C100                 | 7         | 10     | 0.25%   |
| Colorful                    | 7         | 8      | 0.25%   |
| Union Memory                | 5         | 6      | 0.18%   |
| Phison                      | 5         | 6      | 0.18%   |
| Neo                         | 5         | 5      | 0.18%   |
| Micron/Crucial Technology   | 5         | 7      | 0.18%   |
| MAXIO Technology (Hangzhou) | 5         | 5      | 0.18%   |
| Team                        | 4         | 4      | 0.15%   |
| Hikvision                   | 4         | 4      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 112       | 3.7%    |
| Kingston SA400S37480G 480GB SSD      | 66        | 2.18%   |
| Seagate ST1000LM035-1RK172 1TB       | 46        | 1.52%   |
| WDC WD10EZEX-08WN4A0 1TB             | 45        | 1.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 40        | 1.32%   |
| Kingston SA400S37120G 120GB SSD      | 37        | 1.22%   |
| Toshiba MQ01ABF050 500GB             | 31        | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 30        | 0.99%   |
| Toshiba MQ01ABD100 1TB               | 28        | 0.92%   |
| Seagate ST1000DM010-2EP102 1TB       | 26        | 0.86%   |
| Seagate ST500DM002-1BD142 500GB      | 25        | 0.83%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 23        | 0.76%   |
| Kingston SV300S37A120G 120GB SSD     | 23        | 0.76%   |
| WDC WD5000AAKX-001CA0 500GB          | 20        | 0.66%   |
| WDC WD10EZEX-00BN5A0 1TB             | 20        | 0.66%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 18        | 0.59%   |
| Unknown MMC Card  32GB               | 18        | 0.59%   |
| Toshiba MQ04ABF100 1TB               | 18        | 0.59%   |
| Kingston SA400S37960G 960GB SSD      | 17        | 0.56%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 17        | 0.56%   |
| Toshiba DT01ACA050 500GB             | 16        | 0.53%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 15        | 0.5%    |
| Toshiba DT01ACA100 1TB               | 15        | 0.5%    |
| Kingston SV300S37A240G 240GB SSD     | 15        | 0.5%    |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 14        | 0.46%   |
| WDC WD1600AABS-00PRA0 160GB          | 14        | 0.46%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 14        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB      | 14        | 0.46%   |
| Seagate ST500LM030-2E717D 500GB      | 14        | 0.46%   |
| Kingston SUV400S37240G 240GB SSD     | 14        | 0.46%   |
| Gigabyte GP-GSTFS31240GNTD 240GB     | 14        | 0.46%   |
| Crucial CT240BX500SSD1 240GB         | 14        | 0.46%   |
| HGST HTS721010A9E630 1TB             | 13        | 0.43%   |
| A-DATA SU630 240GB SSD               | 13        | 0.43%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 12        | 0.4%    |
| WDC WD10EZEX-21WN4A0 1TB             | 12        | 0.4%    |
| Toshiba MQ01ABD032 320GB             | 12        | 0.4%    |
| WDC WD20EZRX-00D8PB0 2TB             | 11        | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 10        | 0.33%   |
| WDC WD10EZEX-00WN4A0 1TB             | 10        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 628       | 918    | 42.58%  |
| Seagate             | 356       | 461    | 24.14%  |
| Toshiba             | 198       | 249    | 13.42%  |
| Samsung Electronics | 116       | 160    | 7.86%   |
| Hitachi             | 92        | 106    | 6.24%   |
| HGST                | 59        | 64     | 4%      |
| Maxtor              | 12        | 12     | 0.81%   |
| Unknown             | 6         | 6      | 0.41%   |
| Fujitsu             | 3         | 3      | 0.2%    |
| USB3.0              | 1         | 1      | 0.07%   |
| Quantum             | 1         | 1      | 0.07%   |
| Inateck             | 1         | 1      | 0.07%   |
| ExcelStor           | 1         | 1      | 0.07%   |
| ASMT                | 1         | 2      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 322       | 408    | 38.7%   |
| WDC                 | 128       | 165    | 15.38%  |
| Samsung Electronics | 46        | 70     | 5.53%   |
| Gigabyte Technology | 43        | 68     | 5.17%   |
| Crucial             | 42        | 66     | 5.05%   |
| A-DATA Technology   | 40        | 44     | 4.81%   |
| SanDisk             | 36        | 45     | 4.33%   |
| PNY                 | 15        | 26     | 1.8%    |
| Hewlett-Packard     | 12        | 16     | 1.44%   |
| China               | 12        | 14     | 1.44%   |
| SK hynix            | 11        | 12     | 1.32%   |
| Lexar               | 11        | 12     | 1.32%   |
| Corsair             | 10        | 11     | 1.2%    |
| Patriot             | 8         | 10     | 0.96%   |
| Toshiba             | 7         | 7      | 0.84%   |
| Kimtigo             | 7         | 7      | 0.84%   |
| Intel               | 7         | 8      | 0.84%   |
| Colorful            | 7         | 8      | 0.84%   |
| Micron Technology   | 6         | 8      | 0.72%   |
| Team                | 4         | 4      | 0.48%   |
| Seagate             | 4         | 6      | 0.48%   |
| FORESEE             | 4         | 4      | 0.48%   |
| Wodposit            | 3         | 3      | 0.36%   |
| OCZ                 | 3         | 3      | 0.36%   |
| Netac               | 3         | 5      | 0.36%   |
| Maxtor              | 3         | 5      | 0.36%   |
| LITEONIT            | 3         | 3      | 0.36%   |
| HS-SSD-C100         | 3         | 6      | 0.36%   |
| Hikvision           | 3         | 3      | 0.36%   |
| WDC WDS2            | 2         | 2      | 0.24%   |
| Super Talent        | 2         | 2      | 0.24%   |
| SPCC                | 2         | 2      | 0.24%   |
| GLOWAY              | 2         | 2      | 0.24%   |
| Apple               | 2         | 2      | 0.24%   |
| Unknown             | 2         | 2      | 0.24%   |
| XrayDisk            | 1         | 1      | 0.12%   |
| WALRAM              | 1         | 1      | 0.12%   |
| Transcend           | 1         | 1      | 0.12%   |
| tecmiyo             | 1         | 4      | 0.12%   |
| SMI                 | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1279      | 1985   | 50.83%  |
| SSD     | 776       | 1091   | 30.84%  |
| NVMe    | 368       | 531    | 14.63%  |
| MMC     | 68        | 88     | 2.7%    |
| Unknown | 25        | 23     | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1706      | 3062   | 78.47%  |
| NVMe | 367       | 529    | 16.88%  |
| MMC  | 68        | 88     | 3.13%   |
| SAS  | 33        | 39     | 1.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1308      | 1988   | 63.74%  |
| 0.51-1.0        | 596       | 862    | 29.04%  |
| 1.01-2.0        | 103       | 142    | 5.02%   |
| 3.01-4.0        | 18        | 28     | 0.88%   |
| 4.01-10.0       | 13        | 21     | 0.63%   |
| 2.01-3.0        | 12        | 15     | 0.58%   |
| More than 100.0 | 1         | 1      | 0.05%   |
| 10.01-20.0      | 1         | 19     | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 615       | 29%     |
| 251-500        | 493       | 23.24%  |
| 501-1000       | 322       | 15.18%  |
| 1001-2000      | 171       | 8.06%   |
| 1-20           | 146       | 6.88%   |
| 51-100         | 135       | 6.36%   |
| 21-50          | 98        | 4.62%   |
| 2001-3000      | 49        | 2.31%   |
| Unknown        | 48        | 2.26%   |
| More than 3000 | 44        | 2.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 872       | 39.98%  |
| 21-50          | 374       | 17.15%  |
| 101-250        | 299       | 13.71%  |
| 51-100         | 243       | 11.14%  |
| 251-500        | 162       | 7.43%   |
| 501-1000       | 110       | 5.04%   |
| 1001-2000      | 54        | 2.48%   |
| Unknown        | 48        | 2.2%    |
| 2001-3000      | 10        | 0.46%   |
| More than 3000 | 9         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB        | 7         | 9      | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB     | 7         | 7      | 2.78%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 4         | 4      | 1.59%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 4         | 4      | 1.59%   |
| WDC WD10EZEX-00BN5A0 1TB           | 4         | 4      | 1.59%   |
| WDC WD10EARS-00Y5B1 1TB            | 4         | 4      | 1.59%   |
| Kingston SA400S37240G 240GB SSD    | 4         | 4      | 1.59%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 3         | 3      | 1.19%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 3      | 1.19%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 3         | 3      | 1.19%   |
| Toshiba MQ01ABF050 500GB           | 3         | 3      | 1.19%   |
| Toshiba MQ01ABD100 1TB             | 3         | 6      | 1.19%   |
| Toshiba MK1665GSX 160GB            | 3         | 3      | 1.19%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 4      | 1.19%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 1.19%   |
| Seagate ST1000DM003-1SB10C 1TB     | 3         | 3      | 1.19%   |
| HGST HTS721010A9E630 1TB           | 3         | 5      | 1.19%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 1.19%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 2         | 5      | 0.79%   |
| WDC WD5000AAKX-08ERMA0 500GB       | 2         | 2      | 0.79%   |
| WDC WD3200AAKS-00L9A0 320GB        | 2         | 2      | 0.79%   |
| WDC WD20EZRX-00D8PB0 2TB           | 2         | 2      | 0.79%   |
| WDC WD10EZEX-00RKKA0 1TB           | 2         | 2      | 0.79%   |
| WDC WD1003FZEX-00K3CA0 1TB         | 2         | 2      | 0.79%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 2         | 2      | 0.79%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 0.79%   |
| Toshiba MK7559GSXP 752GB           | 2         | 2      | 0.79%   |
| Toshiba MK6475GSX 640GB            | 2         | 2      | 0.79%   |
| Toshiba DT01ACA050 500GB           | 2         | 2      | 0.79%   |
| Seagate ST9500325AS 500GB          | 2         | 2      | 0.79%   |
| Seagate ST9320325AS 320GB          | 2         | 2      | 0.79%   |
| Seagate ST9250315AS 250GB          | 2         | 2      | 0.79%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 5      | 0.79%   |
| Seagate ST500LM030-2E717D 500GB    | 2         | 2      | 0.79%   |
| Seagate ST1500DL003-9VT16L 1TB     | 2         | 2      | 0.79%   |
| Seagate ST1000DM003-9YN162 1TB     | 2         | 2      | 0.79%   |
| Seagate ST1000DM003-1CH162 1TB     | 2         | 2      | 0.79%   |
| Samsung Electronics SP0411N 40GB   | 2         | 3      | 0.79%   |
| Samsung Electronics HN-M101MBB 1TB | 2         | 2      | 0.79%   |
| Samsung Electronics HM161GI 160GB  | 2         | 2      | 0.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 92        | 110    | 38.17%  |
| Seagate             | 49        | 56     | 20.33%  |
| Toshiba             | 28        | 32     | 11.62%  |
| Samsung Electronics | 24        | 26     | 9.96%   |
| Hitachi             | 15        | 17     | 6.22%   |
| HGST                | 12        | 14     | 4.98%   |
| Kingston            | 10        | 10     | 4.15%   |
| Maxtor              | 3         | 3      | 1.24%   |
| A-DATA Technology   | 3         | 3      | 1.24%   |
| XPG                 | 1         | 1      | 0.41%   |
| tecmiyo             | 1         | 4      | 0.41%   |
| SMI                 | 1         | 1      | 0.41%   |
| Quantum             | 1         | 1      | 0.41%   |
| LITEONIT            | 1         | 1      | 0.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 82        | 97     | 38.86%  |
| Seagate             | 49        | 56     | 23.22%  |
| Toshiba             | 28        | 32     | 13.27%  |
| Samsung Electronics | 21        | 23     | 9.95%   |
| Hitachi             | 15        | 17     | 7.11%   |
| HGST                | 12        | 14     | 5.69%   |
| Maxtor              | 3         | 3      | 1.42%   |
| Quantum             | 1         | 1      | 0.47%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 199       | 243    | 86.9%   |
| SSD  | 27        | 33     | 11.79%  |
| NVMe | 3         | 3      | 1.31%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB       | 2         | 2      | 28.57%  |
| WDC WD1600BEVT-80A23T0 160GB      | 1         | 1      | 14.29%  |
| Toshiba MK6475GSX 640GB           | 1         | 1      | 14.29%  |
| Toshiba MK1665GSX 160GB           | 1         | 1      | 14.29%  |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 14.29%  |
| Samsung Electronics HD103SJ 1TB   | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 42.86%  |
| Toshiba             | 2         | 2      | 28.57%  |
| Samsung Electronics | 2         | 2      | 28.57%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1216      | 2234   | 56.58%  |
| Works    | 702       | 1198   | 32.67%  |
| Malfunc  | 224       | 279    | 10.42%  |
| Failed   | 7         | 7      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1252      | 55.06%  |
| AMD                              | 465       | 20.45%  |
| Nvidia                           | 86        | 3.78%   |
| Samsung Electronics              | 85        | 3.74%   |
| SanDisk                          | 78        | 3.43%   |
| Kingston Technology Company      | 50        | 2.2%    |
| SK hynix                         | 35        | 1.54%   |
| VIA Technologies                 | 29        | 1.28%   |
| Phison Electronics               | 22        | 0.97%   |
| Realtek Semiconductor            | 20        | 0.88%   |
| Silicon Integrated Systems [SiS] | 16        | 0.7%    |
| Toshiba America Info Systems     | 15        | 0.66%   |
| Silicon Motion                   | 15        | 0.66%   |
| ASMedia Technology               | 14        | 0.62%   |
| Micron Technology                | 12        | 0.53%   |
| Marvell Technology Group         | 12        | 0.53%   |
| KIOXIA                           | 12        | 0.53%   |
| JMicron Technology               | 12        | 0.53%   |
| ADATA Technology                 | 12        | 0.53%   |
| Micron/Crucial Technology        | 8         | 0.35%   |
| Union Memory (Shenzhen)          | 7         | 0.31%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.31%   |
| Silicon Image                    | 2         | 0.09%   |
| Promise Technology               | 1         | 0.04%   |
| Nextorage                        | 1         | 0.04%   |
| Lite-On Technology               | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| Broadcom / LSI                   | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |
| Adaptec                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 291       | 10.41%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 132       | 4.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 100       | 3.58%   |
| Nvidia MCP61 SATA Controller                                                            | 71        | 2.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 70        | 2.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 70        | 2.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 62        | 2.22%   |
| Nvidia MCP61 IDE                                                                        | 61        | 2.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 61        | 2.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 61        | 2.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 59        | 2.11%   |
| AMD FCH SATA Controller D                                                               | 59        | 2.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 53        | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 48        | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 47        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 46        | 1.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 42        | 1.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 41        | 1.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 36        | 1.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 34        | 1.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 33        | 1.18%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 33        | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 32        | 1.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 32        | 1.14%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 32        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 31        | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 30        | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 30        | 1.07%   |
| AMD FCH IDE Controller                                                                  | 30        | 1.07%   |
| AMD 500 Series Chipset SATA Controller                                                  | 30        | 1.07%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 28        | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 28        | 1%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 25        | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 25        | 0.89%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 24        | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 20        | 0.72%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 20        | 0.72%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 19        | 0.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 19        | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 19        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1458      | 61.81%  |
| IDE  | 426       | 18.06%  |
| NVMe | 369       | 15.64%  |
| RAID | 105       | 4.45%   |
| SCSI | 1         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1390      | 69.74%  |
| AMD    | 598       | 30.01%  |
| ARM    | 5         | 0.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 31        | 1.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 29        | 1.45%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 24        | 1.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 20        | 1%      |
| Intel Core i7-6500U CPU @ 2.50GHz             | 19        | 0.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 19        | 0.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 0.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 0.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 17        | 0.85%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 17        | 0.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 16        | 0.8%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 16        | 0.8%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 16        | 0.8%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 16        | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 15        | 0.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 15        | 0.75%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 15        | 0.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 14        | 0.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 13        | 0.65%   |
| AMD Ryzen 5 3600 6-Core Processor             | 13        | 0.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 12        | 0.6%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 12        | 0.6%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 12        | 0.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 11        | 0.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 0.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 10        | 0.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 0.5%    |
| Intel Core i5-4460 CPU @ 3.20GHz              | 10        | 0.5%    |
| Intel Core i5-4440 CPU @ 3.10GHz              | 10        | 0.5%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 10        | 0.5%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 10        | 0.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 10        | 0.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 0.5%    |
| AMD FX-4100 Quad-Core Processor               | 10        | 0.5%    |
| AMD Athlon II X2 250 Processor                | 10        | 0.5%    |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 10        | 0.5%    |
| AMD A4-4000 APU with Radeon HD Graphics       | 10        | 0.5%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 9         | 0.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 9         | 0.45%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 9         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 368       | 18.44%  |
| Intel Core i7           | 256       | 12.83%  |
| Intel Core i3           | 195       | 9.77%   |
| Intel Celeron           | 160       | 8.02%   |
| AMD Ryzen 5             | 116       | 5.81%   |
| Other                   | 109       | 5.46%   |
| Intel Pentium           | 65        | 3.26%   |
| Intel Atom              | 63        | 3.16%   |
| AMD Ryzen 7             | 62        | 3.11%   |
| Intel Core 2 Duo        | 53        | 2.66%   |
| Intel Pentium Dual-Core | 49        | 2.45%   |
| AMD A8                  | 41        | 2.05%   |
| AMD FX                  | 40        | 2%      |
| AMD Ryzen 3             | 35        | 1.75%   |
| AMD A6                  | 34        | 1.7%    |
| AMD A4                  | 31        | 1.55%   |
| AMD A10                 | 27        | 1.35%   |
| Intel Pentium Dual      | 25        | 1.25%   |
| AMD Athlon II X2        | 25        | 1.25%   |
| AMD Athlon 64 X2        | 22        | 1.1%    |
| AMD Athlon              | 22        | 1.1%    |
| AMD Sempron             | 19        | 0.95%   |
| AMD Phenom II X4        | 18        | 0.9%    |
| AMD Ryzen 9             | 13        | 0.65%   |
| Intel Core 2            | 11        | 0.55%   |
| Intel Pentium 4         | 10        | 0.5%    |
| Intel Pentium D         | 9         | 0.45%   |
| Intel Genuine           | 9         | 0.45%   |
| AMD Phenom II X6        | 9         | 0.45%   |
| AMD Athlon II X4        | 9         | 0.45%   |
| Intel Xeon              | 7         | 0.35%   |
| Intel Core 2 Quad       | 7         | 0.35%   |
| AMD E1                  | 6         | 0.3%    |
| AMD Athlon II           | 6         | 0.3%    |
| AMD A12                 | 6         | 0.3%    |
| AMD Athlon II X3        | 5         | 0.25%   |
| Intel Pentium Gold      | 4         | 0.2%    |
| AMD Phenom II X2        | 4         | 0.2%    |
| AMD Phenom              | 4         | 0.2%    |
| AMD E                   | 4         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1012      | 50.7%   |
| 4       | 601       | 30.11%  |
| 6       | 129       | 6.46%   |
| 1       | 122       | 6.11%   |
| 8       | 84        | 4.21%   |
| 3       | 20        | 1%      |
| 16      | 8         | 0.4%    |
| 12      | 7         | 0.35%   |
| 10      | 7         | 0.35%   |
| Unknown | 3         | 0.15%   |
| 14      | 2         | 0.1%    |
| 24      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1988      | 99.8%   |
| 2       | 3         | 0.15%   |
| Unknown | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1199      | 60.1%   |
| 1       | 793       | 39.75%  |
| Unknown | 3         | 0.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1937      | 97%     |
| Unknown        | 33        | 1.65%   |
| 32-bit         | 20        | 1%      |
| 64-bit         | 7         | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 533       | 25.61%  |
| 0x206a7    | 104       | 5%      |
| 0x306a9    | 103       | 4.95%   |
| 0x306c3    | 68        | 3.27%   |
| 0x1067a    | 65        | 3.12%   |
| 0x806e9    | 49        | 2.35%   |
| 0x806ec    | 46        | 2.21%   |
| 0x806c1    | 40        | 1.92%   |
| 0x08108109 | 40        | 1.92%   |
| 0x010000c8 | 40        | 1.92%   |
| 0x406e3    | 37        | 1.78%   |
| 0x906e9    | 36        | 1.73%   |
| 0x6fd      | 36        | 1.73%   |
| 0x30678    | 34        | 1.63%   |
| 0x806ea    | 33        | 1.59%   |
| 0x06001119 | 31        | 1.49%   |
| 0x306d4    | 30        | 1.44%   |
| 0x906ea    | 28        | 1.35%   |
| 0x40651    | 27        | 1.3%    |
| 0x20655    | 27        | 1.3%    |
| 0x506e3    | 26        | 1.25%   |
| 0x406c4    | 24        | 1.15%   |
| 0x08701021 | 24        | 1.15%   |
| 0x06003106 | 24        | 1.15%   |
| 0x706e5    | 20        | 0.96%   |
| 0x106ca    | 19        | 0.91%   |
| 0x0a50000c | 18        | 0.86%   |
| 0x706a1    | 16        | 0.77%   |
| 0x506c9    | 16        | 0.77%   |
| 0x08101016 | 16        | 0.77%   |
| 0x706a8    | 15        | 0.72%   |
| 0x30661    | 15        | 0.72%   |
| 0x0600611a | 15        | 0.72%   |
| 0x06000852 | 14        | 0.67%   |
| 0xa0653    | 13        | 0.62%   |
| 0x0800820d | 13        | 0.62%   |
| 0x06006705 | 13        | 0.62%   |
| 0x06006118 | 13        | 0.62%   |
| 0x0600063e | 13        | 0.62%   |
| 0x20652    | 12        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 277       | 13.88%  |
| IvyBridge        | 132       | 6.61%   |
| SandyBridge      | 129       | 6.46%   |
| Haswell          | 124       | 6.21%   |
| Penryn           | 102       | 5.11%   |
| K10              | 102       | 5.11%   |
| Silvermont       | 96        | 4.81%   |
| Skylake          | 79        | 3.96%   |
| Zen+             | 78        | 3.91%   |
| TigerLake        | 62        | 3.11%   |
| Piledriver       | 62        | 3.11%   |
| Core             | 62        | 3.11%   |
| Zen 2            | 52        | 2.61%   |
| Westmere         | 50        | 2.51%   |
| Excavator        | 49        | 2.45%   |
| Zen 3            | 48        | 2.4%    |
| Goldmont plus    | 46        | 2.3%    |
| Zen              | 44        | 2.2%    |
| Bonnell          | 40        | 2%      |
| Unknown          | 39        | 1.95%   |
| IceLake          | 38        | 1.9%    |
| Steamroller      | 37        | 1.85%   |
| K8 Hammer        | 36        | 1.8%    |
| CometLake        | 36        | 1.8%    |
| Broadwell        | 36        | 1.8%    |
| NetBurst         | 22        | 1.1%    |
| Goldmont         | 18        | 0.9%    |
| Bulldozer        | 18        | 0.9%    |
| K10 Llano        | 16        | 0.8%    |
| Jaguar           | 12        | 0.6%    |
| Bobcat           | 12        | 0.6%    |
| P6               | 11        | 0.55%   |
| Alderlake Hybrid | 9         | 0.45%   |
| Puma             | 8         | 0.4%    |
| Nehalem          | 8         | 0.4%    |
| K8 & K10 hybrid  | 3         | 0.15%   |
| K6               | 2         | 0.1%    |
| Gracemont        | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1187      | 54.2%   |
| AMD                              | 562       | 25.66%  |
| Nvidia                           | 414       | 18.9%   |
| Silicon Integrated Systems [SiS] | 13        | 0.59%   |
| VIA Technologies                 | 11        | 0.5%    |
| ATI Technologies                 | 3         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 114       | 5.04%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 81        | 3.58%   |
| Intel HD Graphics 620                                                                    | 67        | 2.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 56        | 2.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 55        | 2.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 55        | 2.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 47        | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 46        | 2.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 46        | 2.04%   |
| Intel UHD Graphics 620                                                                   | 42        | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 41        | 1.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 39        | 1.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 38        | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 37        | 1.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 35        | 1.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 1.5%    |
| Intel HD Graphics 5500                                                                   | 33        | 1.46%   |
| Intel HD Graphics 630                                                                    | 32        | 1.42%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 30        | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 29        | 1.28%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 26        | 1.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 25        | 1.11%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 24        | 1.06%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 22        | 0.97%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 22        | 0.97%   |
| Nvidia GT218 [GeForce 210]                                                               | 21        | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 21        | 0.93%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 21        | 0.93%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 21        | 0.93%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 20        | 0.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 0.88%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 20        | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 19        | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 0.84%   |
| Intel HD Graphics 530                                                                    | 18        | 0.8%    |
| Intel HD Graphics 500                                                                    | 18        | 0.8%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 18        | 0.8%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 18        | 0.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 17        | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1014      | 50.6%   |
| 1 x AMD        | 480       | 23.95%  |
| 1 x Nvidia     | 266       | 13.27%  |
| Intel + Nvidia | 121       | 6.04%   |
| Intel + AMD    | 41        | 2.05%   |
| 2 x AMD        | 24        | 1.2%    |
| AMD + Nvidia   | 24        | 1.2%    |
| 1 x SiS        | 13        | 0.65%   |
| 1 x VIA        | 11        | 0.55%   |
| Other          | 5         | 0.25%   |
| 2 x Intel      | 3         | 0.15%   |
| 2 x Nvidia     | 2         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1721      | 85.71%  |
| Proprietary | 188       | 9.36%   |
| Unknown     | 99        | 4.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1215      | 59.36%  |
| 0.01-0.5   | 258       | 12.6%   |
| 1.01-2.0   | 228       | 11.14%  |
| 0.51-1.0   | 153       | 7.47%   |
| 3.01-4.0   | 107       | 5.23%   |
| 7.01-8.0   | 42        | 2.05%   |
| 5.01-6.0   | 23        | 1.12%   |
| 2.01-3.0   | 10        | 0.49%   |
| 8.01-16.0  | 10        | 0.49%   |
| 16.01-24.0 | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 506       | 23.81%  |
| Goldstar                | 247       | 11.62%  |
| Chimei Innolux          | 204       | 9.6%    |
| AU Optronics            | 202       | 9.51%   |
| BOE                     | 185       | 8.71%   |
| LG Display              | 147       | 6.92%   |
| InfoVision              | 49        | 2.31%   |
| Dell                    | 43        | 2.02%   |
| Philips                 | 41        | 1.93%   |
| ViewSonic               | 35        | 1.65%   |
| BenQ                    | 32        | 1.51%   |
| Lenovo                  | 24        | 1.13%   |
| Hitachi                 | 24        | 1.13%   |
| Hewlett-Packard         | 24        | 1.13%   |
| Chi Mei Optoelectronics | 23        | 1.08%   |
| SKY                     | 22        | 1.04%   |
| LG Electronics          | 22        | 1.04%   |
| Apple                   | 19        | 0.89%   |
| PANDA                   | 17        | 0.8%    |
| Unknown                 | 14        | 0.66%   |
| LG Philips              | 12        | 0.56%   |
| AOC                     | 12        | 0.56%   |
| Sony                    | 11        | 0.52%   |
| InnoLux Display         | 11        | 0.52%   |
| STA                     | 10        | 0.47%   |
| Sharp                   | 9         | 0.42%   |
| SAC                     | 9         | 0.42%   |
| HannStar                | 9         | 0.42%   |
| ASUSTek Computer        | 9         | 0.42%   |
| Acer                    | 8         | 0.38%   |
| HKC                     | 7         | 0.33%   |
| CPT                     | 7         | 0.33%   |
| MStar                   | 6         | 0.28%   |
| UTV                     | 5         | 0.24%   |
| Unknown (XXX)           | 5         | 0.24%   |
| KDC                     | 5         | 0.24%   |
| SANYO                   | 4         | 0.19%   |
| RTK                     | 4         | 0.19%   |
| JRY                     | 4         | 0.19%   |
| ITE                     | 4         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 24        | 1.1%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 22        | 1.01%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 22        | 1.01%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 20        | 0.92%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch         | 20        | 0.92%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 19        | 0.87%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 17        | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 14        | 0.64%   |
| Hitachi HDMI HEC0088 1920x540                                        | 14        | 0.64%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                 | 14        | 0.64%   |
| SKY TV-monitor SKY0001 1360x768 890x500mm 40.2-inch                  | 12        | 0.55%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 12        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 12        | 0.55%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 11        | 0.5%    |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 11        | 0.5%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 11        | 0.5%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 11        | 0.5%    |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 10        | 0.46%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 10        | 0.46%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 10        | 0.46%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                | 10        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 10        | 0.46%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 10        | 0.46%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 9         | 0.41%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 9         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 9         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 9         | 0.41%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch    | 8         | 0.37%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch    | 8         | 0.37%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 8         | 0.37%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 8         | 0.37%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 8         | 0.37%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch    | 7         | 0.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 7         | 0.32%   |
| Goldstar W2353 GSM56EE 1920x1080 474x296mm 22.0-inch                 | 7         | 0.32%   |
| Goldstar E2340 GSM57C7 1920x1080 510x290mm 23.1-inch                 | 7         | 0.32%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 7         | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 7         | 0.32%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 7         | 0.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 7         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 744       | 36.31%  |
| 1366x768 (WXGA)    | 705       | 34.41%  |
| 3840x2160 (4K)     | 78        | 3.81%   |
| 1600x900 (HD+)     | 70        | 3.42%   |
| 1280x1024 (SXGA)   | 66        | 3.22%   |
| 1360x768           | 59        | 2.88%   |
| 1440x900 (WXGA+)   | 50        | 2.44%   |
| 1280x800 (WXGA)    | 50        | 2.44%   |
| 1680x1050 (WSXGA+) | 49        | 2.39%   |
| 1920x1200 (WUXGA)  | 29        | 1.42%   |
| 1920x540           | 19        | 0.93%   |
| 2560x1440 (QHD)    | 14        | 0.68%   |
| 1024x600           | 13        | 0.63%   |
| Unknown            | 13        | 0.63%   |
| 1024x768 (XGA)     | 12        | 0.59%   |
| 2560x1080          | 11        | 0.54%   |
| 1280x720 (HD)      | 9         | 0.44%   |
| 3200x1800 (QHD+)   | 5         | 0.24%   |
| 3840x1080          | 4         | 0.2%    |
| 2560x1600          | 4         | 0.2%    |
| 2288x1287          | 4         | 0.2%    |
| 1152x864           | 4         | 0.2%    |
| 3840x2400          | 3         | 0.15%   |
| 3440x1440          | 3         | 0.15%   |
| 2880x1800          | 3         | 0.15%   |
| 3456x2160          | 2         | 0.1%    |
| 2160x1440          | 2         | 0.1%    |
| 2048x1152          | 2         | 0.1%    |
| 1280x960           | 2         | 0.1%    |
| 800x1280           | 1         | 0.05%   |
| 4093x4093          | 1         | 0.05%   |
| 3840x1100          | 1         | 0.05%   |
| 3600x1200          | 1         | 0.05%   |
| 3286x1080          | 1         | 0.05%   |
| 3280x1080          | 1         | 0.05%   |
| 3072x1920          | 1         | 0.05%   |
| 3046x1050          | 1         | 0.05%   |
| 3000x2000          | 1         | 0.05%   |
| 2880x1620          | 1         | 0.05%   |
| 2736x1824          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 549       | 25.59%  |
| 14      | 213       | 9.93%   |
| 13      | 208       | 9.7%    |
| 21      | 171       | 7.97%   |
| 23      | 169       | 7.88%   |
| 18      | 148       | 6.9%    |
| 17      | 70        | 3.26%   |
| Unknown | 67        | 3.12%   |
| 24      | 63        | 2.94%   |
| 19      | 57        | 2.66%   |
| 27      | 56        | 2.61%   |
| 20      | 56        | 2.61%   |
| 40      | 37        | 1.72%   |
| 10      | 34        | 1.59%   |
| 22      | 24        | 1.12%   |
| 16      | 23        | 1.07%   |
| 11      | 22        | 1.03%   |
| 12      | 21        | 0.98%   |
| 31      | 20        | 0.93%   |
| 48      | 18        | 0.84%   |
| 84      | 17        | 0.79%   |
| 52      | 17        | 0.79%   |
| 32      | 15        | 0.7%    |
| 54      | 12        | 0.56%   |
| 46      | 12        | 0.56%   |
| 34      | 12        | 0.56%   |
| 72      | 5         | 0.23%   |
| 142     | 4         | 0.19%   |
| 65      | 4         | 0.19%   |
| 39      | 3         | 0.14%   |
| 55      | 2         | 0.09%   |
| 43      | 2         | 0.09%   |
| 41      | 2         | 0.09%   |
| 30      | 2         | 0.09%   |
| 26      | 2         | 0.09%   |
| 25      | 2         | 0.09%   |
| 86      | 1         | 0.05%   |
| 64      | 1         | 0.05%   |
| 58      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 930       | 43.99%  |
| 401-500        | 436       | 20.62%  |
| 501-600        | 269       | 12.72%  |
| 201-300        | 133       | 6.29%   |
| 351-400        | 80        | 3.78%   |
| 1001-1500      | 67        | 3.17%   |
| Unknown        | 67        | 3.17%   |
| 801-900        | 41        | 1.94%   |
| 601-700        | 32        | 1.51%   |
| 701-800        | 27        | 1.28%   |
| 1501-2000      | 22        | 1.04%   |
| 901-1000       | 5         | 0.24%   |
| More than 2000 | 4         | 0.19%   |
| 1-100          | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1538      | 80.78%  |
| 16/10   | 168       | 8.82%   |
| Unknown | 58        | 3.05%   |
| 5/4     | 46        | 2.42%   |
| 4/3     | 44        | 2.31%   |
| 1.96    | 14        | 0.74%   |
| 21/9    | 13        | 0.68%   |
| 3/2     | 12        | 0.63%   |
| 1.00    | 4         | 0.21%   |
| 32/9    | 2         | 0.11%   |
| 6/5     | 1         | 0.05%   |
| 3.40    | 1         | 0.05%   |
| 0.89    | 1         | 0.05%   |
| 0.67    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 529       | 24.91%  |
| 201-250        | 382       | 17.98%  |
| 81-90          | 377       | 17.75%  |
| 141-150        | 173       | 8.15%   |
| 151-200        | 143       | 6.73%   |
| 501-1000       | 72        | 3.39%   |
| Unknown        | 67        | 3.15%   |
| More than 1000 | 65        | 3.06%   |
| 301-350        | 57        | 2.68%   |
| 351-500        | 49        | 2.31%   |
| 71-80          | 43        | 2.02%   |
| 121-130        | 38        | 1.79%   |
| 41-50          | 34        | 1.6%    |
| 111-120        | 33        | 1.55%   |
| 51-60          | 23        | 1.08%   |
| 61-70          | 15        | 0.71%   |
| 251-300        | 10        | 0.47%   |
| 131-140        | 7         | 0.33%   |
| 91-100         | 6         | 0.28%   |
| 1-40           | 1         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 789       | 38.01%  |
| 51-100        | 697       | 33.57%  |
| 121-160       | 354       | 17.05%  |
| 1-50          | 106       | 5.11%   |
| Unknown       | 67        | 3.23%   |
| 161-240       | 44        | 2.12%   |
| More than 240 | 19        | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1636      | 80.2%   |
| 2     | 303       | 14.85%  |
| 0     | 84        | 4.12%   |
| 3     | 16        | 0.78%   |
| 5     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 1322      | 44.97%  |
| Intel                                 | 610       | 20.75%  |
| Qualcomm Atheros                      | 353       | 12.01%  |
| Broadcom                              | 104       | 3.54%   |
| TP-Link                               | 79        | 2.69%   |
| Nvidia                                | 75        | 2.55%   |
| Ralink Technology                     | 47        | 1.6%    |
| Qualcomm Atheros Communications       | 36        | 1.22%   |
| Marvell Technology Group              | 35        | 1.19%   |
| Broadcom Limited                      | 34        | 1.16%   |
| JMicron Technology                    | 28        | 0.95%   |
| Samsung Electronics                   | 27        | 0.92%   |
| Ralink                                | 27        | 0.92%   |
| VIA Technologies                      | 20        | 0.68%   |
| MediaTek                              | 20        | 0.68%   |
| Motorola PCS                          | 18        | 0.61%   |
| Silicon Integrated Systems [SiS]      | 16        | 0.54%   |
| Microsoft                             | 11        | 0.37%   |
| ASIX Electronics                      | 7         | 0.24%   |
| Xiaomi                                | 5         | 0.17%   |
| NetGear                               | 4         | 0.14%   |
| D-Link System                         | 4         | 0.14%   |
| T & A Mobile Phones                   | 3         | 0.1%    |
| Sundance Technology Inc / IC Plus     | 3         | 0.1%    |
| ICS Advent                            | 3         | 0.1%    |
| Ericsson Business Mobile Networks     | 3         | 0.1%    |
| DisplayLink                           | 3         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.1%    |
| 3Com                                  | 3         | 0.1%    |
| ZTE WCDMA Technologies MSM            | 2         | 0.07%   |
| Standard Microsystems                 | 2         | 0.07%   |
| Spreadtrum Communications             | 2         | 0.07%   |
| Ovislink                              | 2         | 0.07%   |
| Linksys                               | 2         | 0.07%   |
| LG Electronics                        | 2         | 0.07%   |
| Lenovo                                | 2         | 0.07%   |
| Huawei Technologies                   | 2         | 0.07%   |
| Encore Electronics                    | 2         | 0.07%   |
| Davicom Semiconductor                 | 2         | 0.07%   |
| D-Link                                | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 893       | 25.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 203       | 5.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 64        | 1.84%   |
| Nvidia MCP61 Ethernet                                             | 64        | 1.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 60        | 1.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 52        | 1.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 50        | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 47        | 1.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 46        | 1.32%   |
| Intel Wi-Fi 6 AX201                                               | 42        | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 41        | 1.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 40        | 1.15%   |
| Intel Wi-Fi 6 AX200                                               | 37        | 1.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 34        | 0.98%   |
| Intel Wireless 3160                                               | 34        | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 33        | 0.95%   |
| Qualcomm Atheros AR9271 802.11n                                   | 32        | 0.92%   |
| Intel Wireless 3165                                               | 30        | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 29        | 0.84%   |
| Intel Wireless 8265 / 8275                                        | 29        | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 25        | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 24        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 24        | 0.69%   |
| Ralink MT7601U Wireless Adapter                                   | 24        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 24        | 0.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 24        | 0.69%   |
| Intel Wireless 7260                                               | 24        | 0.69%   |
| Intel Ethernet Connection (2) I219-V                              | 24        | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 23        | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 23        | 0.66%   |
| Intel Wireless 7265                                               | 23        | 0.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 23        | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 22        | 0.63%   |
| Intel I211 Gigabit Network Connection                             | 21        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 21        | 0.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 20        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 20        | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 18        | 0.52%   |
| Intel Ethernet Controller I225-V                                  | 17        | 0.49%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 16        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 486       | 31.35%  |
| Realtek Semiconductor                 | 432       | 27.87%  |
| Qualcomm Atheros                      | 292       | 18.84%  |
| Broadcom                              | 87        | 5.61%   |
| TP-Link                               | 70        | 4.52%   |
| Ralink Technology                     | 47        | 3.03%   |
| Qualcomm Atheros Communications       | 36        | 2.32%   |
| Ralink                                | 27        | 1.74%   |
| Broadcom Limited                      | 19        | 1.23%   |
| MediaTek                              | 15        | 0.97%   |
| Microsoft                             | 10        | 0.65%   |
| NetGear                               | 4         | 0.26%   |
| Marvell Technology Group              | 4         | 0.26%   |
| D-Link System                         | 4         | 0.26%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.19%   |
| Ovislink                              | 2         | 0.13%   |
| Linksys                               | 2         | 0.13%   |
| Encore Electronics                    | 2         | 0.13%   |
| D-Link                                | 2         | 0.13%   |
| ZyDAS                                 | 1         | 0.06%   |
| Sierra Wireless                       | 1         | 0.06%   |
| Samsung Electronics                   | 1         | 0.06%   |
| Ericsson Business Mobile Networks     | 1         | 0.06%   |
| Dell                                  | 1         | 0.06%   |
| Cisco Aironet Wireless Communications | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 64        | 4.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 60        | 3.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 52        | 3.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 50        | 3.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 47        | 3%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 46        | 2.94%   |
| Intel Wi-Fi 6 AX201                                                     | 42        | 2.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 41        | 2.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 40        | 2.56%   |
| Intel Wi-Fi 6 AX200                                                     | 37        | 2.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 34        | 2.17%   |
| Intel Wireless 3160                                                     | 34        | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 33        | 2.11%   |
| Qualcomm Atheros AR9271 802.11n                                         | 32        | 2.04%   |
| Intel Wireless 3165                                                     | 30        | 1.92%   |
| Intel Wireless 8265 / 8275                                              | 29        | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 25        | 1.6%    |
| Ralink MT7601U Wireless Adapter                                         | 24        | 1.53%   |
| Intel Wireless 7260                                                     | 24        | 1.53%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 23        | 1.47%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 23        | 1.47%   |
| Intel Wireless 7265                                                     | 23        | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 21        | 1.34%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 20        | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 20        | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 18        | 1.15%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 16        | 1.02%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 16        | 1.02%   |
| Realtek 802.11n WLAN Adapter                                            | 16        | 1.02%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 16        | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 16        | 1.02%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 15        | 0.96%   |
| Intel Wireless 8260                                                     | 15        | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 15        | 0.96%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 15        | 0.96%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 13        | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1169      | 62.61%  |
| Intel                             | 260       | 13.93%  |
| Qualcomm Atheros                  | 124       | 6.64%   |
| Nvidia                            | 75        | 4.02%   |
| Marvell Technology Group          | 31        | 1.66%   |
| Broadcom                          | 31        | 1.66%   |
| JMicron Technology                | 28        | 1.5%    |
| Samsung Electronics               | 24        | 1.29%   |
| VIA Technologies                  | 20        | 1.07%   |
| Silicon Integrated Systems [SiS]  | 16        | 0.86%   |
| Motorola PCS                      | 16        | 0.86%   |
| Broadcom Limited                  | 15        | 0.8%    |
| TP-Link                           | 10        | 0.54%   |
| ASIX Electronics                  | 7         | 0.37%   |
| Xiaomi                            | 5         | 0.27%   |
| MediaTek                          | 5         | 0.27%   |
| T & A Mobile Phones               | 3         | 0.16%   |
| Sundance Technology Inc / IC Plus | 3         | 0.16%   |
| ICS Advent                        | 3         | 0.16%   |
| DisplayLink                       | 3         | 0.16%   |
| 3Com                              | 3         | 0.16%   |
| Standard Microsystems             | 2         | 0.11%   |
| Spreadtrum Communications         | 2         | 0.11%   |
| Lenovo                            | 2         | 0.11%   |
| Davicom Semiconductor             | 2         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.05%   |
| Microsoft                         | 1         | 0.05%   |
| Macronix [MXIC]                   | 1         | 0.05%   |
| LG Electronics                    | 1         | 0.05%   |
| Huawei Technologies               | 1         | 0.05%   |
| Digitech Systems                  | 1         | 0.05%   |
| Aquantia                          | 1         | 0.05%   |
| 3DSP                              | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 893       | 47.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 203       | 10.76%  |
| Nvidia MCP61 Ethernet                                             | 64        | 3.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 29        | 1.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 24        | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 24        | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 24        | 1.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 24        | 1.27%   |
| Intel Ethernet Connection (2) I219-V                              | 24        | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 23        | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 22        | 1.17%   |
| Intel I211 Gigabit Network Connection                             | 21        | 1.11%   |
| Intel Ethernet Controller I225-V                                  | 17        | 0.9%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 16        | 0.85%   |
| Motorola PCS moto g62 5G                                          | 16        | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 0.8%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 14        | 0.74%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 13        | 0.69%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 13        | 0.69%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 13        | 0.69%   |
| Intel Ethernet Connection (13) I219-V                             | 13        | 0.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 11        | 0.58%   |
| Intel Ethernet Connection (10) I219-V                             | 11        | 0.58%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.58%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 10        | 0.53%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 0.48%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.37%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.37%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.37%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 6         | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.32%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 6         | 0.32%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.32%   |
| Intel PRO/100 VE Network Connection                               | 6         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1765      | 54.09%  |
| WiFi     | 1478      | 45.3%   |
| Modem    | 17        | 0.52%   |
| Unknown  | 3         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1216      | 59.64%  |
| Ethernet | 822       | 40.31%  |
| Unknown  | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1040      | 51.95%  |
| 1     | 876       | 43.76%  |
| 0     | 56        | 2.8%    |
| 3     | 26        | 1.3%    |
| 4     | 2         | 0.1%    |
| 32    | 1         | 0.05%   |
| 7     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1726      | 85.57%  |
| Yes  | 291       | 14.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 397       | 41.18%  |
| Realtek Semiconductor           | 176       | 18.26%  |
| Qualcomm Atheros Communications | 75        | 7.78%   |
| Cambridge Silicon Radio         | 72        | 7.47%   |
| IMC Networks                    | 53        | 5.5%    |
| Broadcom                        | 43        | 4.46%   |
| Lite-On Technology              | 36        | 3.73%   |
| Foxconn / Hon Hai               | 23        | 2.39%   |
| Apple                           | 17        | 1.76%   |
| Dell                            | 13        | 1.35%   |
| Toshiba                         | 11        | 1.14%   |
| ASUSTek Computer                | 8         | 0.83%   |
| TP-Link                         | 7         | 0.73%   |
| Ralink                          | 7         | 0.73%   |
| Integrated System Solution      | 5         | 0.52%   |
| Hewlett-Packard                 | 3         | 0.31%   |
| USI                             | 2         | 0.21%   |
| Qcom                            | 2         | 0.21%   |
| Marvell Semiconductor           | 2         | 0.21%   |
| Alps Electric                   | 2         | 0.21%   |
| Syntek                          | 1         | 0.1%    |
| Roper                           | 1         | 0.1%    |
| Realtek                         | 1         | 0.1%    |
| Ralink Technology               | 1         | 0.1%    |
| MediaTek                        | 1         | 0.1%    |
| Logitech                        | 1         | 0.1%    |
| Foxconn International           | 1         | 0.1%    |
| Edimax Technology               | 1         | 0.1%    |
| Conwise Technology              | 1         | 0.1%    |
| Unknown                         | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 159       | 16.48%  |
| Realtek Bluetooth Radio                             | 102       | 10.57%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 72        | 7.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 70        | 7.25%   |
| Intel AX201 Bluetooth                               | 66        | 6.84%   |
| Realtek  Bluetooth 4.2 Adapter                      | 45        | 4.66%   |
| Qualcomm Atheros  Bluetooth Device                  | 39        | 4.04%   |
| Intel AX200 Bluetooth                               | 38        | 3.94%   |
| Realtek RTL8723B Bluetooth                          | 23        | 2.38%   |
| IMC Networks Bluetooth Radio                        | 22        | 2.28%   |
| Intel Wireless-AC 3168 Bluetooth                    | 20        | 2.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 1.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 1.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 1.35%   |
| IMC Networks Bluetooth Device                       | 13        | 1.35%   |
| Lite-On Bluetooth Device                            | 12        | 1.24%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 9         | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 9         | 0.93%   |
| Intel AX210 Bluetooth                               | 8         | 0.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.83%   |
| TP-Link TP-Cdj+ UB5A Adapter                        | 7         | 0.73%   |
| Toshiba Bluetooth USB Host Controller               | 7         | 0.73%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.73%   |
| IMC Networks Wireless_Device                        | 7         | 0.73%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 7         | 0.73%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 7         | 0.73%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 0.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 0.62%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 6         | 0.62%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.62%   |
| Apple Bluetooth USB Host Controller                 | 6         | 0.62%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 5         | 0.52%   |
| Intel Bluetooth Device                              | 5         | 0.52%   |
| Dell Wireless 365 Bluetooth                         | 5         | 0.52%   |
| Realtek 802.11ac WLAN Adapter                       | 4         | 0.41%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 4         | 0.41%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.41%   |
| Apple Bluetooth HCI                                 | 4         | 0.41%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.31%   |
| Lite-On Bluetooth Radio                             | 3         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1328      | 53.25%  |
| AMD                                             | 594       | 23.82%  |
| Nvidia                                          | 316       | 12.67%  |
| Logitech                                        | 41        | 1.64%   |
| C-Media Electronics                             | 40        | 1.6%    |
| Kingston Technology                             | 19        | 0.76%   |
| VIA Technologies                                | 18        | 0.72%   |
| Silicon Integrated Systems [SiS]                | 16        | 0.64%   |
| Generalplus Technology                          | 10        | 0.4%    |
| Texas Instruments                               | 9         | 0.36%   |
| Creative Labs                                   | 9         | 0.36%   |
| Focusrite-Novation                              | 7         | 0.28%   |
| Plantronics                                     | 6         | 0.24%   |
| M-Audio                                         | 5         | 0.2%    |
| Elite Silicon                                   | 5         | 0.2%    |
| JMTek                                           | 4         | 0.16%   |
| GN Netcom                                       | 4         | 0.16%   |
| Creative Technology                             | 4         | 0.16%   |
| ATI Technologies                                | 4         | 0.16%   |
| Samson Technologies                             | 3         | 0.12%   |
| Microsoft                                       | 3         | 0.12%   |
| Micro Star International                        | 3         | 0.12%   |
| Licensed by Sony Computer Entertainment America | 3         | 0.12%   |
| Fry's Electronics                               | 3         | 0.12%   |
| ESI Audiotechnik                                | 3         | 0.12%   |
| BEHRINGER International                         | 3         | 0.12%   |
| ASUSTek Computer                                | 3         | 0.12%   |
| Astro Gaming                                    | 3         | 0.12%   |
| TEAC                                            | 2         | 0.08%   |
| Realtek Semiconductor                           | 2         | 0.08%   |
| Razer USA                                       | 2         | 0.08%   |
| Lenovo                                          | 2         | 0.08%   |
| Hewlett-Packard                                 | 2         | 0.08%   |
| Ensoniq                                         | 2         | 0.08%   |
| Corsair                                         | 2         | 0.08%   |
| Yamaha                                          | 1         | 0.04%   |
| Sony                                            | 1         | 0.04%   |
| Samsung Electronics                             | 1         | 0.04%   |
| Pro-Ject                                        | 1         | 0.04%   |
| Holtek Semiconductor                            | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 159       | 5.21%   |
| AMD Family 17h/19h HD Audio Controller                                     | 157       | 5.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 141       | 4.62%   |
| AMD FCH Azalia Controller                                                  | 122       | 3.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 118       | 3.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 115       | 3.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 99        | 3.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 84        | 2.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 72        | 2.36%   |
| Nvidia MCP61 High Definition Audio                                         | 68        | 2.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 62        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 61        | 2%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 57        | 1.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 56        | 1.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 53        | 1.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 53        | 1.74%   |
| AMD Starship/Matisse HD Audio Controller                                   | 50        | 1.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 47        | 1.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 46        | 1.51%   |
| AMD Kabini HDMI/DP Audio                                                   | 43        | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 41        | 1.34%   |
| Intel Comet Lake PCH-LP cAVS                                               | 40        | 1.31%   |
| Intel Broadwell-U Audio Controller                                         | 36        | 1.18%   |
| Intel 200 Series PCH HD Audio                                              | 36        | 1.18%   |
| Intel Haswell-ULT HD Audio Controller                                      | 35        | 1.15%   |
| Intel 8 Series HD Audio Controller                                         | 35        | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 35        | 1.15%   |
| AMD Trinity HDMI Audio Controller                                          | 34        | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 32        | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 31        | 1.02%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 31        | 1.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 30        | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 29        | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 29        | 0.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 29        | 0.95%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 29        | 0.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 27        | 0.88%   |
| Nvidia High Definition Audio Controller                                    | 26        | 0.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 25        | 0.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 24        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Kingston                                         | 291       | 23.7%   |
| Samsung Electronics                              | 211       | 17.18%  |
| Unknown                                          | 140       | 11.4%   |
| SK hynix                                         | 140       | 11.4%   |
| Micron Technology                                | 70        | 5.7%    |
| Crucial                                          | 61        | 4.97%   |
| A-DATA Technology                                | 45        | 3.66%   |
| Corsair                                          | 40        | 3.26%   |
| Unknown (ABCD)                                   | 19        | 1.55%   |
| Magnum Tech                                      | 17        | 1.38%   |
| Nanya Technology                                 | 16        | 1.3%    |
| Unknown                                          | 14        | 1.14%   |
| Novatech                                         | 13        | 1.06%   |
| Goldkey                                          | 12        | 0.98%   |
| Elpida                                           | 11        | 0.9%    |
| G.Skill                                          | 10        | 0.81%   |
| Avant                                            | 9         | 0.73%   |
| Ramaxel Technology                               | 8         | 0.65%   |
| Patriot                                          | 8         | 0.65%   |
| Saikano                                          | 6         | 0.49%   |
| PNY                                              | 6         | 0.49%   |
| Hewlett-Packard                                  | 6         | 0.49%   |
| Transcend                                        | 5         | 0.41%   |
| Team                                             | 5         | 0.41%   |
| Super Talent                                     | 5         | 0.41%   |
| Neo Forza                                        | 5         | 0.41%   |
| Memox                                            | 5         | 0.41%   |
| CSX                                              | 4         | 0.33%   |
| 48spaces                                         | 4         | 0.33%   |
| Unknown (0x0B45)                                 | 3         | 0.24%   |
| Kingmax                                          | 3         | 0.24%   |
| Apacer                                           | 3         | 0.24%   |
| Teikon                                           | 2         | 0.16%   |
| Ramos Technology                                 | 2         | 0.16%   |
| Netac                                            | 2         | 0.16%   |
| Lexar                                            | 2         | 0.16%   |
| Innodisk                                         | 2         | 0.16%   |
| Hikvision                                        | 2         | 0.16%   |
| Visipro                                          | 1         | 0.08%   |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 20        | 1.5%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 18        | 1.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 1.13%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s              | 15        | 1.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 1.05%   |
| Unknown                                                          | 14        | 1.05%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 13        | 0.98%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 11        | 0.83%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.68%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 9         | 0.68%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 9         | 0.68%   |
| Kingston RAM 99U5471-054.A00LF 8192MB DIMM DDR3 1600MT/s         | 9         | 0.68%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 8         | 0.6%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.6%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 8         | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.45%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.45%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.45%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s              | 6         | 0.45%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s            | 6         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 5         | 0.38%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 5         | 0.38%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 5         | 0.38%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 5         | 0.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 5         | 0.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.38%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.38%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.38%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 5         | 0.38%   |
| Saikano RAM Memory 4GB SODIMM DDR3 1333MT/s                      | 5         | 0.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.38%   |
| Kingston RAM KHX1866C10D3/ 8GB DIMM DDR3 1866MT/s                | 5         | 0.38%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 5         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 457       | 44.28%  |
| DDR3    | 380       | 36.82%  |
| DDR2    | 53        | 5.14%   |
| Unknown | 49        | 4.75%   |
| LPDDR4  | 32        | 3.1%    |
| SDRAM   | 26        | 2.52%   |
| LPDDR3  | 13        | 1.26%   |
| DDR     | 9         | 0.87%   |
| DRAM    | 5         | 0.48%   |
| LPDDR5  | 4         | 0.39%   |
| DDR5    | 4         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 576       | 55.87%  |
| DIMM         | 403       | 39.09%  |
| Row Of Chips | 49        | 4.75%   |
| Chip         | 2         | 0.19%   |
| Unknown      | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 453       | 38.59%  |
| 4096  | 348       | 29.64%  |
| 2048  | 179       | 15.25%  |
| 16384 | 122       | 10.39%  |
| 1024  | 36        | 3.07%   |
| 32768 | 29        | 2.47%   |
| 512   | 5         | 0.43%   |
| 6144  | 1         | 0.09%   |
| 256   | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 219       | 18.8%   |
| 2667    | 176       | 15.11%  |
| 3200    | 155       | 13.3%   |
| 1333    | 127       | 10.9%   |
| 2400    | 99        | 8.5%    |
| 2133    | 51        | 4.38%   |
| 1334    | 41        | 3.52%   |
| Unknown | 36        | 3.09%   |
| 667     | 28        | 2.4%    |
| 3600    | 27        | 2.32%   |
| 800     | 18        | 1.55%   |
| 3400    | 14        | 1.2%    |
| 1066    | 14        | 1.2%    |
| 3266    | 13        | 1.12%   |
| 1067    | 13        | 1.12%   |
| 3466    | 12        | 1.03%   |
| 1866    | 11        | 0.94%   |
| 533     | 11        | 0.94%   |
| 4199    | 8         | 0.69%   |
| 2666    | 8         | 0.69%   |
| 333     | 8         | 0.69%   |
| 1867    | 7         | 0.6%    |
| 3000    | 6         | 0.52%   |
| 2933    | 6         | 0.52%   |
| 400     | 6         | 0.52%   |
| 6400    | 4         | 0.34%   |
| 4800    | 4         | 0.34%   |
| 4267    | 4         | 0.34%   |
| 2800    | 4         | 0.34%   |
| 975     | 4         | 0.34%   |
| 3733    | 3         | 0.26%   |
| 2048    | 3         | 0.26%   |
| 8400    | 2         | 0.17%   |
| 4266    | 2         | 0.17%   |
| 3933    | 2         | 0.17%   |
| 3151    | 2         | 0.17%   |
| 3007    | 2         | 0.17%   |
| 1800    | 2         | 0.17%   |
| 52217   | 1         | 0.09%   |
| 3866    | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 30        | 48.39%  |
| Brother Industries  | 17        | 27.42%  |
| Seiko Epson         | 6         | 9.68%   |
| Samsung Electronics | 3         | 4.84%   |
| Ricoh               | 1         | 1.61%   |
| QinHeng Electronics | 1         | 1.61%   |
| Pantum              | 1         | 1.61%   |
| NXP Semiconductors  | 1         | 1.61%   |
| Kyocera             | 1         | 1.61%   |
| Graphtec America    | 1         | 1.61%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| HP LaserJet Professional P1102w               | 5         | 8.06%   |
| Brother HL-1200 series                        | 4         | 6.45%   |
| Brother HL-1110 series                        | 4         | 6.45%   |
| HP LaserJet Professional P 1102w              | 3         | 4.84%   |
| Brother HL-1210W series                       | 3         | 4.84%   |
| Samsung M2020 Series                          | 2         | 3.23%   |
| HP LaserJet P1006                             | 2         | 3.23%   |
| HP LaserJet P1005                             | 2         | 3.23%   |
| HP Ink Tank 110 series                        | 2         | 3.23%   |
| HP DeskJet 2620 All-in-One Printer            | 2         | 3.23%   |
| Brother HL-2130 series                        | 2         | 3.23%   |
| Brother DCP-7055 scanner/printer              | 2         | 3.23%   |
| Seiko Epson XP-240 Series                     | 1         | 1.61%   |
| Seiko Epson Printer                           | 1         | 1.61%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.61%   |
| Seiko Epson L355 Series                       | 1         | 1.61%   |
| Seiko Epson L120 Series                       | 1         | 1.61%   |
| Seiko Epson ET-2700 Series                    | 1         | 1.61%   |
| Samsung Xerox Phaser 3117 Laser Printer       | 1         | 1.61%   |
| Ricoh Printing Support                        | 1         | 1.61%   |
| QinHeng CH340S                                | 1         | 1.61%   |
| Pantum P2500W series                          | 1         | 1.61%   |
| NXP Semiconductors Printer-80                 | 1         | 1.61%   |
| Kyocera ECOSYS M3550idn                       | 1         | 1.61%   |
| HP PSC 1400                                   | 1         | 1.61%   |
| HP Officejet 4500 G510a-f                     | 1         | 1.61%   |
| HP Laserjet P1505                             | 1         | 1.61%   |
| HP LaserJet M203-M206                         | 1         | 1.61%   |
| HP LaserJet 3050                              | 1         | 1.61%   |
| HP LaserJet 1020                              | 1         | 1.61%   |
| HP Ink Tank Wireless 410 series               | 1         | 1.61%   |
| HP DeskJet F4100 Printer series               | 1         | 1.61%   |
| HP DeskJet F300 series                        | 1         | 1.61%   |
| HP DeskJet 810c/812c                          | 1         | 1.61%   |
| HP DeskJet 3630 series                        | 1         | 1.61%   |
| HP Deskjet 3050 J610 series                   | 1         | 1.61%   |
| HP Deskjet 2050 J510                          | 1         | 1.61%   |
| HP Color LaserJet Pro M478f-9f                | 1         | 1.61%   |
| Graphtec America Graphtec Printer             | 1         | 1.61%   |
| Brother DCP-1610NW                            | 1         | 1.61%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP ScanJet 2400c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 231       | 19.51%  |
| IMC Networks                           | 110       | 9.29%   |
| Microdia                               | 95        | 8.02%   |
| Realtek Semiconductor                  | 92        | 7.77%   |
| Bison Electronics                      | 86        | 7.26%   |
| Logitech                               | 49        | 4.14%   |
| Syntek                                 | 44        | 3.72%   |
| Sunplus Innovation Technology          | 42        | 3.55%   |
| Quanta                                 | 42        | 3.55%   |
| Suyin                                  | 41        | 3.46%   |
| Alcor Micro                            | 36        | 3.04%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 2.96%   |
| Silicon Motion                         | 34        | 2.87%   |
| Acer                                   | 30        | 2.53%   |
| Apple                                  | 21        | 1.77%   |
| Samsung Electronics                    | 18        | 1.52%   |
| Z-Star Microelectronics                | 16        | 1.35%   |
| Generalplus Technology                 | 16        | 1.35%   |
| KYE Systems (Mouse Systems)            | 15        | 1.27%   |
| Ricoh                                  | 12        | 1.01%   |
| Lite-On Technology                     | 12        | 1.01%   |
| SunplusIT                              | 10        | 0.84%   |
| Luxvisions Innotech Limited            | 8         | 0.68%   |
| Sonix Technology                       | 7         | 0.59%   |
| OmniVision Technologies                | 7         | 0.59%   |
| Microsoft                              | 7         | 0.59%   |
| Jieli Technology                       | 7         | 0.59%   |
| icSpring                               | 7         | 0.59%   |
| 8SSC20F27114V1SR0BK1X4S                | 5         | 0.42%   |
| Lenovo                                 | 4         | 0.34%   |
| GEMBIRD                                | 4         | 0.34%   |
| Cubeternet                             | 4         | 0.34%   |
| ALi                                    | 4         | 0.34%   |
| Y Media                                | 3         | 0.25%   |
| Pixart Imaging                         | 3         | 0.25%   |
| MacroSilicon                           | 3         | 0.25%   |
| Importek                               | 3         | 0.25%   |
| Razer USA                              | 2         | 0.17%   |
| Intel                                  | 2         | 0.17%   |
| Genesys Logic                          | 2         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                         | 41        | 3.44%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 34        | 2.85%   |
| IMC Networks Integrated Camera                                 | 34        | 2.85%   |
| Bison Integrated Camera                                        | 30        | 2.52%   |
| Alcor Micro USB 2.0 Camera                                     | 26        | 2.18%   |
| Microdia Integrated_Webcam_HD                                  | 25        | 2.1%    |
| Realtek USB Camera                                             | 24        | 2.02%   |
| Chicony Integrated Camera                                      | 23        | 1.93%   |
| Realtek Integrated_Webcam_HD                                   | 20        | 1.68%   |
| Syntek Integrated Camera                                       | 18        | 1.51%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 17        | 1.43%   |
| Chicony Lenovo EasyCamera                                      | 16        | 1.34%   |
| Logitech Webcam C270                                           | 14        | 1.18%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 14        | 1.18%   |
| Chicony HD Webcam                                              | 14        | 1.18%   |
| Sunplus Integrated_Webcam_HD                                   | 13        | 1.09%   |
| Bison Lenovo EasyCamera                                        | 12        | 1.01%   |
| Chicony TOSHIBA Web Camera - HD                                | 11        | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 11        | 0.92%   |
| Microdia USB Camera                                            | 10        | 0.84%   |
| Logitech C922 Pro Stream Webcam                                | 10        | 0.84%   |
| Generalplus GENERAL WEBCAM                                     | 10        | 0.84%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                             | 10        | 0.84%   |
| SunplusIT USB 2M Camera                                        | 9         | 0.76%   |
| Chicony USB2.0 Camera                                          | 9         | 0.76%   |
| Chicony HP Wide Vision HD Camera                               | 9         | 0.76%   |
| Bison SunplusIT Integrated Camera                              | 9         | 0.76%   |
| Acer BisonCam, NB Pro                                          | 9         | 0.76%   |
| Syntek EasyCamera                                              | 8         | 0.67%   |
| Silicon Motion WebCam SC-0311139N                              | 8         | 0.67%   |
| Microdia Webcam Vitade AF                                      | 8         | 0.67%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 8         | 0.67%   |
| Chicony Integrated Camera (1280x720@30)                        | 8         | 0.67%   |
| Z-Star Webcam                                                  | 7         | 0.59%   |
| Syntek Lenovo EasyCamera                                       | 7         | 0.59%   |
| Microdia Integrated Webcam                                     | 7         | 0.59%   |
| Logitech HD Pro Webcam C920                                    | 7         | 0.59%   |
| Jieli USB PHY 2.0                                              | 7         | 0.59%   |
| icSpring camera                                                | 7         | 0.59%   |
| Chicony HP TrueVision HD Camera                                | 7         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 49        | 34.27%  |
| Validity Sensors                   | 37        | 25.87%  |
| Shenzhen Goodix Technology         | 27        | 18.88%  |
| Elan Microelectronics              | 8         | 5.59%   |
| AuthenTec                          | 7         | 4.9%    |
| Upek                               | 6         | 4.2%    |
| LighTuning Technology              | 5         | 3.5%    |
| STMicroelectronics                 | 1         | 0.7%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.7%    |
| Focal-systems.Corp                 | 1         | 0.7%    |
| DigitalPersona                     | 1         | 0.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 13.99%  |
| Shenzhen Goodix  FingerPrint Device                                        | 20        | 13.99%  |
| Synaptics  WBDI                                                            | 14        | 9.79%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 6.99%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.2%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 4.2%    |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 4.2%    |
| Elan ELAN:Fingerprint                                                      | 5         | 3.5%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 2.8%    |
| Synaptics WBDI                                                             | 4         | 2.8%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.8%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 2.1%    |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.1%    |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.1%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 2.1%    |
| Elan ELAN:ARM-M4                                                           | 3         | 2.1%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.4%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.4%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.4%    |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 1.4%    |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.4%    |
| AuthenTec AES2810                                                          | 2         | 1.4%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.4%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.7%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.7%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.7%    |
| Synaptics UWP WBDI Device                                                  | 1         | 0.7%    |
| Synaptics TouchPad                                                         | 1         | 0.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.7%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.7%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.7%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.7%    |
| LighTuning Fingerprint Sensor                                              | 1         | 0.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.7%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.7%    |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.7%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.7%    |
| Unknown                                                                    | 1         | 0.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 25        | 64.1%   |
| Upek        | 10        | 25.64%  |
| Lenovo      | 2         | 5.13%   |
| O2 Micro    | 1         | 2.56%   |
| Alcor Micro | 1         | 2.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 25.64%  |
| Broadcom 58200                                                               | 8         | 20.51%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 17.95%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 17.95%  |
| Broadcom 5880                                                                | 3         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.13%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.56%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 2.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1541      | 75.99%  |
| 1     | 425       | 20.96%  |
| 2     | 53        | 2.61%   |
| 3     | 5         | 0.25%   |
| 8     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |
| 4     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 170       | 30.8%   |
| Fingerprint reader       | 141       | 25.54%  |
| Net/wireless             | 87        | 15.76%  |
| Chipcard                 | 36        | 6.52%   |
| Camera                   | 23        | 4.17%   |
| Multimedia controller    | 21        | 3.8%    |
| Communication controller | 16        | 2.9%    |
| Bluetooth                | 15        | 2.72%   |
| Sound                    | 11        | 1.99%   |
| Net/ethernet             | 10        | 1.81%   |
| Modem                    | 5         | 0.91%   |
| Unassigned class         | 4         | 0.72%   |
| Network                  | 4         | 0.72%   |
| Storage/ide              | 2         | 0.36%   |
| Flash memory             | 2         | 0.36%   |
| Firewire controller      | 2         | 0.36%   |
| Card reader              | 2         | 0.36%   |
| Dvb card                 | 1         | 0.18%   |

