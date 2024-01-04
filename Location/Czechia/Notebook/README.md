Linux in Czechia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

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

Total: 1962

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro9,2               | [7f113211a4](https://linux-hardware.org/?probe=7f113211a4) | Dec 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [3185001cb4](https://linux-hardware.org/?probe=3185001cb4) | Dec 30, 2023 |
| HP            | Compaq 610                  | [d0849e0580](https://linux-hardware.org/?probe=d0849e0580) | Dec 30, 2023 |
| Dell          | XPS 13 9380                 | [1148fbe6b6](https://linux-hardware.org/?probe=1148fbe6b6) | Dec 29, 2023 |
| HP            | 2000                        | [eac2251c15](https://linux-hardware.org/?probe=eac2251c15) | Dec 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f2e13b11bd](https://linux-hardware.org/?probe=f2e13b11bd) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d23b5553ca](https://linux-hardware.org/?probe=d23b5553ca) | Dec 27, 2023 |
| Dell          | Inspiron N5110              | [87efb02531](https://linux-hardware.org/?probe=87efb02531) | Dec 27, 2023 |
| Dell          | Latitude 5591               | [99b2702a06](https://linux-hardware.org/?probe=99b2702a06) | Dec 27, 2023 |
| Valve         | Jupiter                     | [eeac675274](https://linux-hardware.org/?probe=eeac675274) | Dec 27, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [f91e53f3e0](https://linux-hardware.org/?probe=f91e53f3e0) | Dec 26, 2023 |
| HP            | 2000                        | [057698e1aa](https://linux-hardware.org/?probe=057698e1aa) | Dec 26, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [b08bd5ba2c](https://linux-hardware.org/?probe=b08bd5ba2c) | Dec 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [d7b7e34741](https://linux-hardware.org/?probe=d7b7e34741) | Dec 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [a79885417a](https://linux-hardware.org/?probe=a79885417a) | Dec 23, 2023 |
| HP            | ProBook 4540s               | [fbed208acc](https://linux-hardware.org/?probe=fbed208acc) | Dec 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS25R00    | [91820391fd](https://linux-hardware.org/?probe=91820391fd) | Dec 23, 2023 |
| ASUSTek       | X555LA                      | [2f52e3fdc9](https://linux-hardware.org/?probe=2f52e3fdc9) | Dec 22, 2023 |
| HP            | ProBook 4540s               | [27155e8350](https://linux-hardware.org/?probe=27155e8350) | Dec 22, 2023 |
| Dell          | Latitude 7490               | [d0ea360540](https://linux-hardware.org/?probe=d0ea360540) | Dec 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ef2e756e7b](https://linux-hardware.org/?probe=ef2e756e7b) | Dec 21, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a7044c8c2a](https://linux-hardware.org/?probe=a7044c8c2a) | Dec 19, 2023 |
| Dell          | Precision M2800             | [8800042fb5](https://linux-hardware.org/?probe=8800042fb5) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | [42706222be](https://linux-hardware.org/?probe=42706222be) | Dec 19, 2023 |
| Sony          | VGN-FW455J                  | [f16255f9d1](https://linux-hardware.org/?probe=f16255f9d1) | Dec 17, 2023 |
| Apple         | MacBookPro9,2               | [4c8c4e1c68](https://linux-hardware.org/?probe=4c8c4e1c68) | Dec 17, 2023 |
| Packard Be... | EasyNote TE11HC             | [a155267edc](https://linux-hardware.org/?probe=a155267edc) | Dec 17, 2023 |
| Dell          | Latitude 7490               | [a5431ec5e0](https://linux-hardware.org/?probe=a5431ec5e0) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [9e63ff66cb](https://linux-hardware.org/?probe=9e63ff66cb) | Dec 15, 2023 |
| Acer          | Aspire A515-57G             | [638a0b8c0c](https://linux-hardware.org/?probe=638a0b8c0c) | Dec 15, 2023 |
| HP            | ZBook 15u G6                | [4467debb1c](https://linux-hardware.org/?probe=4467debb1c) | Dec 15, 2023 |
| ASUSTek       | X550CA                      | [fe7ad66674](https://linux-hardware.org/?probe=fe7ad66674) | Dec 13, 2023 |
| HP            | 2000                        | [40929a84a0](https://linux-hardware.org/?probe=40929a84a0) | Dec 10, 2023 |
| HP            | Laptop 15-fc0xxx            | [e55319a16a](https://linux-hardware.org/?probe=e55319a16a) | Dec 09, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ba71538aed](https://linux-hardware.org/?probe=ba71538aed) | Dec 08, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [01f7b97e5d](https://linux-hardware.org/?probe=01f7b97e5d) | Dec 08, 2023 |
| Dell          | Latitude 5591               | [1961ebb904](https://linux-hardware.org/?probe=1961ebb904) | Dec 07, 2023 |
| Dell          | Latitude 5591               | [b9f6d020e8](https://linux-hardware.org/?probe=b9f6d020e8) | Dec 07, 2023 |
| Dell          | Precision 3550              | [da173d0ccc](https://linux-hardware.org/?probe=da173d0ccc) | Dec 07, 2023 |
| Valve         | Jupiter                     | [93bf1ceeec](https://linux-hardware.org/?probe=93bf1ceeec) | Dec 05, 2023 |
| Sony          | VPCS13S9E                   | [0cd7cfa9de](https://linux-hardware.org/?probe=0cd7cfa9de) | Dec 02, 2023 |
| Dynabook      | PORTEGE X50-G               | [65a2f2f3d5](https://linux-hardware.org/?probe=65a2f2f3d5) | Dec 01, 2023 |
| Lenovo        | ThinkPad T430 2349AK2       | [53a55a0da2](https://linux-hardware.org/?probe=53a55a0da2) | Dec 01, 2023 |
| Dell          | XPS 15 9560                 | [17577fa161](https://linux-hardware.org/?probe=17577fa161) | Dec 01, 2023 |
| Dell          | Latitude E6420              | [ebd186f423](https://linux-hardware.org/?probe=ebd186f423) | Dec 01, 2023 |
| Lenovo        | G700 20251                  | [e4e63d5300](https://linux-hardware.org/?probe=e4e63d5300) | Nov 30, 2023 |
| Apple         | MacBookPro9,2               | [cfeac0b40f](https://linux-hardware.org/?probe=cfeac0b40f) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [71cf2f0a79](https://linux-hardware.org/?probe=71cf2f0a79) | Nov 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [685ce27fae](https://linux-hardware.org/?probe=685ce27fae) | Nov 29, 2023 |
| Acer          | Nitro AN515-58              | [c4a56c14f5](https://linux-hardware.org/?probe=c4a56c14f5) | Nov 29, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [d1dc329e65](https://linux-hardware.org/?probe=d1dc329e65) | Nov 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [d0c3893980](https://linux-hardware.org/?probe=d0c3893980) | Nov 29, 2023 |
| Dell          | Latitude E6540              | [ae3c1282c2](https://linux-hardware.org/?probe=ae3c1282c2) | Nov 29, 2023 |
| UMAX          | N14R                        | [a0d4963838](https://linux-hardware.org/?probe=a0d4963838) | Nov 28, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [8ef4fb91ac](https://linux-hardware.org/?probe=8ef4fb91ac) | Nov 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [cb6d17a69a](https://linux-hardware.org/?probe=cb6d17a69a) | Nov 26, 2023 |
| UMAX          | VisionBook-N12R             | [e77e8d6999](https://linux-hardware.org/?probe=e77e8d6999) | Nov 26, 2023 |
| Acer          | Swift SF314-42              | [bebbc2f6c4](https://linux-hardware.org/?probe=bebbc2f6c4) | Nov 25, 2023 |
| Dell          | Latitude 5511               | [254abd404f](https://linux-hardware.org/?probe=254abd404f) | Nov 25, 2023 |
| HP            | EliteBook 840 G5            | [320763e400](https://linux-hardware.org/?probe=320763e400) | Nov 25, 2023 |
| HP            | Compaq 6730b (NB027EA#AK... | [3b3bf03eee](https://linux-hardware.org/?probe=3b3bf03eee) | Nov 25, 2023 |
| Lenovo        | ThinkPad E450 20DC008DMC    | [56fc21d585](https://linux-hardware.org/?probe=56fc21d585) | Nov 23, 2023 |
| ASUSTek       | K54LY                       | [4ebc53e69c](https://linux-hardware.org/?probe=4ebc53e69c) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S9GM01    | [9c8590e300](https://linux-hardware.org/?probe=9c8590e300) | Nov 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [0337023dbe](https://linux-hardware.org/?probe=0337023dbe) | Nov 22, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [b305b3da28](https://linux-hardware.org/?probe=b305b3da28) | Nov 22, 2023 |
| Acer          | Aspire A315-34              | [336fe65e03](https://linux-hardware.org/?probe=336fe65e03) | Nov 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [af566d6f0c](https://linux-hardware.org/?probe=af566d6f0c) | Nov 22, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [748ea9f21b](https://linux-hardware.org/?probe=748ea9f21b) | Nov 21, 2023 |
| Dell          | Latitude E6430              | [dc02cb2409](https://linux-hardware.org/?probe=dc02cb2409) | Nov 20, 2023 |
| UMAX          | VisionBook-N12R             | [89e41854be](https://linux-hardware.org/?probe=89e41854be) | Nov 19, 2023 |
| Lenovo        | ThinkPad X201 3680DE3       | [38290dc3e7](https://linux-hardware.org/?probe=38290dc3e7) | Nov 17, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [ca7747546b](https://linux-hardware.org/?probe=ca7747546b) | Nov 17, 2023 |
| Dell          | Inspiron 7577               | [62e08b2285](https://linux-hardware.org/?probe=62e08b2285) | Nov 15, 2023 |
| Acer          | Aspire A315-34              | [8179414a49](https://linux-hardware.org/?probe=8179414a49) | Nov 14, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [2204427cc1](https://linux-hardware.org/?probe=2204427cc1) | Nov 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [46cfd3f6bf](https://linux-hardware.org/?probe=46cfd3f6bf) | Nov 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [001dd47e7d](https://linux-hardware.org/?probe=001dd47e7d) | Nov 12, 2023 |
| Acer          | Aspire E1-531               | [41e1f90785](https://linux-hardware.org/?probe=41e1f90785) | Nov 11, 2023 |
| Sony          | VPCEB4J0E                   | [c1e2a1a0da](https://linux-hardware.org/?probe=c1e2a1a0da) | Nov 11, 2023 |
| Chuwi         | HeroBook Pro                | [65a7263504](https://linux-hardware.org/?probe=65a7263504) | Nov 09, 2023 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [47557dd574](https://linux-hardware.org/?probe=47557dd574) | Nov 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [41fd02095e](https://linux-hardware.org/?probe=41fd02095e) | Nov 07, 2023 |
| Lenovo        | G505 20240                  | [ef019ff242](https://linux-hardware.org/?probe=ef019ff242) | Nov 06, 2023 |
| Dell          | Latitude E7440              | [5a151e929f](https://linux-hardware.org/?probe=5a151e929f) | Nov 05, 2023 |
| Lenovo        | ThinkPad W541 20EGS0QG1Z    | [ae8881b2b2](https://linux-hardware.org/?probe=ae8881b2b2) | Nov 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS0QG1Z    | [a3d91609e9](https://linux-hardware.org/?probe=a3d91609e9) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [60187ba0be](https://linux-hardware.org/?probe=60187ba0be) | Nov 04, 2023 |
| HP            | EliteBook 840 G5            | [a42017f05d](https://linux-hardware.org/?probe=a42017f05d) | Nov 02, 2023 |
| Dell          | Latitude 5480               | [567a2774f8](https://linux-hardware.org/?probe=567a2774f8) | Nov 01, 2023 |
| Dell          | Latitude E5470              | [b1be043dc0](https://linux-hardware.org/?probe=b1be043dc0) | Oct 31, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [15573e8d54](https://linux-hardware.org/?probe=15573e8d54) | Oct 30, 2023 |
| HP            | 250 G3                      | [784033212e](https://linux-hardware.org/?probe=784033212e) | Oct 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a718d2e0ba](https://linux-hardware.org/?probe=a718d2e0ba) | Oct 28, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [c866e0068b](https://linux-hardware.org/?probe=c866e0068b) | Oct 28, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [e08a8fa43b](https://linux-hardware.org/?probe=e08a8fa43b) | Oct 28, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [bdf8012e05](https://linux-hardware.org/?probe=bdf8012e05) | Oct 27, 2023 |
| Dell          | Inspiron 5737               | [6ed0863a43](https://linux-hardware.org/?probe=6ed0863a43) | Oct 27, 2023 |
| ASUSTek       | X550CL                      | [a95ddd6798](https://linux-hardware.org/?probe=a95ddd6798) | Oct 26, 2023 |
| HP            | 250 G3                      | [43fbeb0886](https://linux-hardware.org/?probe=43fbeb0886) | Oct 26, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [819d596b2e](https://linux-hardware.org/?probe=819d596b2e) | Oct 24, 2023 |
| HP            | EliteBook 840 G4            | [a6d732c859](https://linux-hardware.org/?probe=a6d732c859) | Oct 24, 2023 |
| Lenovo        | Unknown                     | [21cf9c327a](https://linux-hardware.org/?probe=21cf9c327a) | Oct 22, 2023 |
| Dell          | Vostro 3560                 | [8f65236e52](https://linux-hardware.org/?probe=8f65236e52) | Oct 22, 2023 |
| Dell          | System Vostro 3750          | [33345af29b](https://linux-hardware.org/?probe=33345af29b) | Oct 22, 2023 |
| Dell          | Vostro 3560                 | [a523689a60](https://linux-hardware.org/?probe=a523689a60) | Oct 21, 2023 |
| Acer          | Swift SF314-42              | [e19b58f8be](https://linux-hardware.org/?probe=e19b58f8be) | Oct 21, 2023 |
| Acer          | Aspire R3-131T              | [f8d2d274e1](https://linux-hardware.org/?probe=f8d2d274e1) | Oct 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [f35c9d006e](https://linux-hardware.org/?probe=f35c9d006e) | Oct 20, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [79a2d6de1a](https://linux-hardware.org/?probe=79a2d6de1a) | Oct 19, 2023 |
| Dell          | XPS 13 9310                 | [3a6514e61a](https://linux-hardware.org/?probe=3a6514e61a) | Oct 19, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [dd8ebeda53](https://linux-hardware.org/?probe=dd8ebeda53) | Oct 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [52e7bc3407](https://linux-hardware.org/?probe=52e7bc3407) | Oct 18, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | [6193aa3ed1](https://linux-hardware.org/?probe=6193aa3ed1) | Oct 17, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [f53079d2c1](https://linux-hardware.org/?probe=f53079d2c1) | Oct 16, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [dcb416db8f](https://linux-hardware.org/?probe=dcb416db8f) | Oct 16, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | [ba4661ac35](https://linux-hardware.org/?probe=ba4661ac35) | Oct 15, 2023 |
| HP            | Pavilion dv7                | [feb4113e4e](https://linux-hardware.org/?probe=feb4113e4e) | Oct 15, 2023 |
| HP            | Pavilion dv7                | [6bb631736f](https://linux-hardware.org/?probe=6bb631736f) | Oct 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b2250f3c59](https://linux-hardware.org/?probe=b2250f3c59) | Oct 14, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [17b0ef31ee](https://linux-hardware.org/?probe=17b0ef31ee) | Oct 13, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e38dfab96d](https://linux-hardware.org/?probe=e38dfab96d) | Oct 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [41d5ccfd3f](https://linux-hardware.org/?probe=41d5ccfd3f) | Oct 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [7d1fea3001](https://linux-hardware.org/?probe=7d1fea3001) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [749e1a7e28](https://linux-hardware.org/?probe=749e1a7e28) | Oct 09, 2023 |
| UMAX          | N14R                        | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| Dell          | Latitude 5431               | [a85fc8f829](https://linux-hardware.org/?probe=a85fc8f829) | Oct 06, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [3b423be827](https://linux-hardware.org/?probe=3b423be827) | Oct 06, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [7b888eeb58](https://linux-hardware.org/?probe=7b888eeb58) | Oct 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [3b55566de3](https://linux-hardware.org/?probe=3b55566de3) | Oct 05, 2023 |
| HP            | Pavilion Notebook           | [59c0b6ce9c](https://linux-hardware.org/?probe=59c0b6ce9c) | Oct 04, 2023 |
| Samsung       | 550XBE/350XBE               | [442ef4b7be](https://linux-hardware.org/?probe=442ef4b7be) | Oct 04, 2023 |
| Dell          | Latitude E6420              | [55c45fb7cb](https://linux-hardware.org/?probe=55c45fb7cb) | Oct 01, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [4575deef12](https://linux-hardware.org/?probe=4575deef12) | Sep 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S1K400    | [fd03530876](https://linux-hardware.org/?probe=fd03530876) | Sep 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [2d1ada9dbe](https://linux-hardware.org/?probe=2d1ada9dbe) | Sep 30, 2023 |
| Sony          | VPCEB4J0E                   | [05864978df](https://linux-hardware.org/?probe=05864978df) | Sep 29, 2023 |
| ASUSTek       | UX31E                       | [1b6440f722](https://linux-hardware.org/?probe=1b6440f722) | Sep 29, 2023 |
| Dell          | Precision 7710              | [89731f9b0e](https://linux-hardware.org/?probe=89731f9b0e) | Sep 29, 2023 |
| Dell          | Inspiron 5515               | [5889ba673d](https://linux-hardware.org/?probe=5889ba673d) | Sep 27, 2023 |
| Sony          | VPCEB4J0E                   | [354e2be55e](https://linux-hardware.org/?probe=354e2be55e) | Sep 27, 2023 |
| HP            | EliteBook 8470p             | [a1fa543905](https://linux-hardware.org/?probe=a1fa543905) | Sep 27, 2023 |
| Acer          | Swift SF14-71T              | [10b657bd75](https://linux-hardware.org/?probe=10b657bd75) | Sep 25, 2023 |
| Dell          | Precision 7720              | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [336d5fe8c8](https://linux-hardware.org/?probe=336d5fe8c8) | Sep 25, 2023 |
| Dell          | Latitude 7400               | [f537b79d15](https://linux-hardware.org/?probe=f537b79d15) | Sep 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a6ff891fa1](https://linux-hardware.org/?probe=a6ff891fa1) | Sep 23, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [4bb581fb16](https://linux-hardware.org/?probe=4bb581fb16) | Sep 19, 2023 |
| Acer          | Aspire ES1-420              | [db308e1798](https://linux-hardware.org/?probe=db308e1798) | Sep 19, 2023 |
| Lenovo        | ThinkPad T480 20L6SCYF0P    | [c406bf7b56](https://linux-hardware.org/?probe=c406bf7b56) | Sep 18, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [bc597f4c0c](https://linux-hardware.org/?probe=bc597f4c0c) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [8f3c4bff98](https://linux-hardware.org/?probe=8f3c4bff98) | Sep 13, 2023 |
| Dell          | G3 3500                     | [293bbfe2d6](https://linux-hardware.org/?probe=293bbfe2d6) | Sep 12, 2023 |
| Acer          | Aspire E5-575G              | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [53139247c9](https://linux-hardware.org/?probe=53139247c9) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| HP            | 240 G8 Notebook PC          | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| Dell          | Latitude 7400               | [e1ea4eb614](https://linux-hardware.org/?probe=e1ea4eb614) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | [30bf3f1f45](https://linux-hardware.org/?probe=30bf3f1f45) | Sep 05, 2023 |
| UMAX          | 13Wr                        | [574937c731](https://linux-hardware.org/?probe=574937c731) | Sep 02, 2023 |
| HP            | Unknown                     | [3809d7ad85](https://linux-hardware.org/?probe=3809d7ad85) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | [864a10779f](https://linux-hardware.org/?probe=864a10779f) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [e5a1a106cb](https://linux-hardware.org/?probe=e5a1a106cb) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [96d825f112](https://linux-hardware.org/?probe=96d825f112) | Aug 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS0LR00    | [a85743e60e](https://linux-hardware.org/?probe=a85743e60e) | Aug 31, 2023 |
| Acer          | Swift SF314-42              | [80bebab849](https://linux-hardware.org/?probe=80bebab849) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d6bca74de6](https://linux-hardware.org/?probe=d6bca74de6) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| ASUSTek       | K53E                        | [fa5eab9e81](https://linux-hardware.org/?probe=fa5eab9e81) | Aug 28, 2023 |
| Acer          | Aspire E1-532               | [037143c4fd](https://linux-hardware.org/?probe=037143c4fd) | Aug 27, 2023 |
| ASUSTek       | UX31E                       | [0557e95830](https://linux-hardware.org/?probe=0557e95830) | Aug 27, 2023 |
| Google        | Robo                        | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [c288ff6b78](https://linux-hardware.org/?probe=c288ff6b78) | Aug 25, 2023 |
| HP            | ZBook 14 G2                 | [7fcd619af1](https://linux-hardware.org/?probe=7fcd619af1) | Aug 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| Lenovo        | IdeaPad Z580                | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | [fcbebfc95a](https://linux-hardware.org/?probe=fcbebfc95a) | Aug 23, 2023 |
| Valve         | Jupiter                     | [904e60e2d7](https://linux-hardware.org/?probe=904e60e2d7) | Aug 23, 2023 |
| Dell          | XPS 15 9560                 | [e751db6fd4](https://linux-hardware.org/?probe=e751db6fd4) | Aug 22, 2023 |
| Valve         | Jupiter                     | [57038f50cd](https://linux-hardware.org/?probe=57038f50cd) | Aug 20, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [681310709d](https://linux-hardware.org/?probe=681310709d) | Aug 19, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [b8e5fd59d3](https://linux-hardware.org/?probe=b8e5fd59d3) | Aug 18, 2023 |
| Dell          | Latitude 7440               | [aef57d5421](https://linux-hardware.org/?probe=aef57d5421) | Aug 17, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [1fcc89106f](https://linux-hardware.org/?probe=1fcc89106f) | Aug 15, 2023 |
| HP            | Laptop 17-cp0xxx            | [620d12291b](https://linux-hardware.org/?probe=620d12291b) | Aug 15, 2023 |
| Lenovo        | ThinkPad X250 20CM001RMC    | [618a7e3e29](https://linux-hardware.org/?probe=618a7e3e29) | Aug 14, 2023 |
| Dell          | XPS 13 7390                 | [f4e6886bd8](https://linux-hardware.org/?probe=f4e6886bd8) | Aug 13, 2023 |
| HP            | ZBook 17 G3                 | [475b07d2dc](https://linux-hardware.org/?probe=475b07d2dc) | Aug 12, 2023 |
| HP            | 250 G3                      | [6ba303bc6b](https://linux-hardware.org/?probe=6ba303bc6b) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ffa9b97bf7](https://linux-hardware.org/?probe=ffa9b97bf7) | Aug 10, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [82dde7d058](https://linux-hardware.org/?probe=82dde7d058) | Aug 10, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [e1462f1e3a](https://linux-hardware.org/?probe=e1462f1e3a) | Aug 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 455 G7              | [bd9f67ee72](https://linux-hardware.org/?probe=bd9f67ee72) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | [30d8fefda4](https://linux-hardware.org/?probe=30d8fefda4) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | [f1cef350fb](https://linux-hardware.org/?probe=f1cef350fb) | Aug 07, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [b69ff09aa4](https://linux-hardware.org/?probe=b69ff09aa4) | Aug 05, 2023 |
| Dell          | Latitude E6420              | [3636e69adb](https://linux-hardware.org/?probe=3636e69adb) | Aug 05, 2023 |
| Acer          | Aspire E5-572G              | [846dce7b1b](https://linux-hardware.org/?probe=846dce7b1b) | Aug 05, 2023 |
| Dell          | Latitude E5500              | [95ddcb321c](https://linux-hardware.org/?probe=95ddcb321c) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | [12ee4ed8f6](https://linux-hardware.org/?probe=12ee4ed8f6) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | [5a2ed78e49](https://linux-hardware.org/?probe=5a2ed78e49) | Aug 05, 2023 |
| Dell          | Latitude 7400               | [48e2858e56](https://linux-hardware.org/?probe=48e2858e56) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [195716ccf3](https://linux-hardware.org/?probe=195716ccf3) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [5a9a057759](https://linux-hardware.org/?probe=5a9a057759) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [367f14eae6](https://linux-hardware.org/?probe=367f14eae6) | Aug 04, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [1317097350](https://linux-hardware.org/?probe=1317097350) | Aug 03, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [e5be227d11](https://linux-hardware.org/?probe=e5be227d11) | Aug 03, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [589f0a8599](https://linux-hardware.org/?probe=589f0a8599) | Aug 01, 2023 |
| Acer          | Aspire 1810TZ               | [8cbec4eb45](https://linux-hardware.org/?probe=8cbec4eb45) | Jul 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [5ce91f2c11](https://linux-hardware.org/?probe=5ce91f2c11) | Jul 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [6ec734b217](https://linux-hardware.org/?probe=6ec734b217) | Jul 30, 2023 |
| Acer          | Aspire 5742                 | [37be5a1c80](https://linux-hardware.org/?probe=37be5a1c80) | Jul 30, 2023 |
| ASUSTek       | UX31E                       | [a7b390cdf4](https://linux-hardware.org/?probe=a7b390cdf4) | Jul 29, 2023 |
| Google        | Edgar                       | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5497a92cf](https://linux-hardware.org/?probe=f5497a92cf) | Jul 28, 2023 |
| Acer          | Aspire A315-24P             | [6799c4be4a](https://linux-hardware.org/?probe=6799c4be4a) | Jul 27, 2023 |
| Toshiba       | Satellite A135              | [91f5602ed7](https://linux-hardware.org/?probe=91f5602ed7) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [74adf4cb3d](https://linux-hardware.org/?probe=74adf4cb3d) | Jul 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [9f384d336d](https://linux-hardware.org/?probe=9f384d336d) | Jul 23, 2023 |
| Dell          | Latitude E7440              | [ffa2aad2b5](https://linux-hardware.org/?probe=ffa2aad2b5) | Jul 21, 2023 |
| Dell          | Latitude E5530 non-vPro     | [2c2c4bdcf2](https://linux-hardware.org/?probe=2c2c4bdcf2) | Jul 21, 2023 |
| Lenovo        | B5400 80B6QB0               | [7108435241](https://linux-hardware.org/?probe=7108435241) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [cf9bdab1ee](https://linux-hardware.org/?probe=cf9bdab1ee) | Jul 13, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [f742573138](https://linux-hardware.org/?probe=f742573138) | Jul 12, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [d09af80a65](https://linux-hardware.org/?probe=d09af80a65) | Jul 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Lenovo        | ThinkPad E570 20H50074MC    | [029e84bf8a](https://linux-hardware.org/?probe=029e84bf8a) | Jul 06, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [bedadd4478](https://linux-hardware.org/?probe=bedadd4478) | Jul 05, 2023 |
| HP            | EliteBook 8770w             | [8f298fa9aa](https://linux-hardware.org/?probe=8f298fa9aa) | Jul 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [73e054c849](https://linux-hardware.org/?probe=73e054c849) | Jul 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [5d2bd9c3ce](https://linux-hardware.org/?probe=5d2bd9c3ce) | Jul 04, 2023 |
| AMI           | Intel                       | [65aafdb0b0](https://linux-hardware.org/?probe=65aafdb0b0) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [05394ee8a5](https://linux-hardware.org/?probe=05394ee8a5) | Jul 02, 2023 |
| ASUSTek       | UX31E                       | [37a73c8939](https://linux-hardware.org/?probe=37a73c8939) | Jul 01, 2023 |
| Acer          | Swift SF314-42              | [c5820f8068](https://linux-hardware.org/?probe=c5820f8068) | Jul 01, 2023 |
| UMAX          | VisionBook-N12R             | [6144190349](https://linux-hardware.org/?probe=6144190349) | Jun 30, 2023 |
| Acer          | NC-A515-51G-59DM            | [a521f2cc60](https://linux-hardware.org/?probe=a521f2cc60) | Jun 29, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [223911e8f0](https://linux-hardware.org/?probe=223911e8f0) | Jun 25, 2023 |
| HP            | EliteBook 840 G3            | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Lenovo        | G570 20079                  | [5879c3e9ad](https://linux-hardware.org/?probe=5879c3e9ad) | Jun 22, 2023 |
| ASUSTek       | GL552VX                     | [348e36123f](https://linux-hardware.org/?probe=348e36123f) | Jun 22, 2023 |
| ASUSTek       | UX31E                       | [51b4c8d9ef](https://linux-hardware.org/?probe=51b4c8d9ef) | Jun 22, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [61ba243843](https://linux-hardware.org/?probe=61ba243843) | Jun 21, 2023 |
| Acer          | Aspire ES1-420              | [76aab864d4](https://linux-hardware.org/?probe=76aab864d4) | Jun 19, 2023 |
| Dell          | Latitude E6540              | [3721b0046f](https://linux-hardware.org/?probe=3721b0046f) | Jun 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [0806a6be0a](https://linux-hardware.org/?probe=0806a6be0a) | Jun 19, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| Dell          | Latitude 5420               | [d3327c76f1](https://linux-hardware.org/?probe=d3327c76f1) | Jun 15, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| Acer          | Aspire ES1-420              | [5c3a2078ca](https://linux-hardware.org/?probe=5c3a2078ca) | Jun 14, 2023 |
| Dell          | XPS 15 9500                 | [77ce1af9f8](https://linux-hardware.org/?probe=77ce1af9f8) | Jun 13, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [edf817eef9](https://linux-hardware.org/?probe=edf817eef9) | Jun 12, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [5c98700539](https://linux-hardware.org/?probe=5c98700539) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f6e70e460f](https://linux-hardware.org/?probe=f6e70e460f) | Jun 11, 2023 |
| Dell          | Latitude 5420               | [956a995580](https://linux-hardware.org/?probe=956a995580) | Jun 09, 2023 |
| HP            | Laptop 15s-fq2xxx           | [09ba95bf3b](https://linux-hardware.org/?probe=09ba95bf3b) | Jun 08, 2023 |
| HP            | Laptop 15s-fq2xxx           | [9d0aa12b81](https://linux-hardware.org/?probe=9d0aa12b81) | Jun 06, 2023 |
| ASUSTek       | UX31E                       | [92d0de412b](https://linux-hardware.org/?probe=92d0de412b) | Jun 06, 2023 |
| Dell          | Latitude 7400               | [9968377d89](https://linux-hardware.org/?probe=9968377d89) | Jun 06, 2023 |
| Acer          | Nitro AN515-44              | [d7a2c59432](https://linux-hardware.org/?probe=d7a2c59432) | Jun 05, 2023 |
| Lenovo        | ThinkPad T420 4236WQD       | [69a63f31e1](https://linux-hardware.org/?probe=69a63f31e1) | Jun 03, 2023 |
| Timi          | A35S                        | [c9ce47a446](https://linux-hardware.org/?probe=c9ce47a446) | Jun 01, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [643710864a](https://linux-hardware.org/?probe=643710864a) | May 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | [ea6330526c](https://linux-hardware.org/?probe=ea6330526c) | May 29, 2023 |
| Acer          | Aspire 7540                 | [82fcb3124c](https://linux-hardware.org/?probe=82fcb3124c) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [56fca4583d](https://linux-hardware.org/?probe=56fca4583d) | May 28, 2023 |
| Lenovo        | ThinkPad P51 20HJS01Q04     | [520eb0074c](https://linux-hardware.org/?probe=520eb0074c) | May 26, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DQ02    | [bb00a96df8](https://linux-hardware.org/?probe=bb00a96df8) | May 25, 2023 |
| Unknown       | Unknown                     | [cfaffcaa0a](https://linux-hardware.org/?probe=cfaffcaa0a) | May 25, 2023 |
| Dell          | G15 5511                    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| Dell          | G5 5587                     | [18faf1497f](https://linux-hardware.org/?probe=18faf1497f) | May 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [2fffd70abb](https://linux-hardware.org/?probe=2fffd70abb) | May 23, 2023 |
| Dell          | Vostro 5620                 | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| Dell          | G15 5511                    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0f8329fecb](https://linux-hardware.org/?probe=0f8329fecb) | May 20, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| HP            | ProBook 4540s               | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| Dell          | Latitude 5521               | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [b4e8e5504e](https://linux-hardware.org/?probe=b4e8e5504e) | May 15, 2023 |
| HP            | 250 G8 Notebook PC          | [14aeaeafe8](https://linux-hardware.org/?probe=14aeaeafe8) | May 15, 2023 |
| ASUSTek       | UX31E                       | [53f535546a](https://linux-hardware.org/?probe=53f535546a) | May 12, 2023 |
| Dell          | Latitude 7400               | [14de9baf53](https://linux-hardware.org/?probe=14de9baf53) | May 12, 2023 |
| Dell          | Vostro 5620                 | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| eMachines     | E620                        | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| HP            | EliteBook 8470p             | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Dell          | Latitude E7450              | [0eff8f87c6](https://linux-hardware.org/?probe=0eff8f87c6) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [0767486bb6](https://linux-hardware.org/?probe=0767486bb6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [3c6e20e260](https://linux-hardware.org/?probe=3c6e20e260) | May 04, 2023 |
| Valve         | Jupiter                     | [1f41754528](https://linux-hardware.org/?probe=1f41754528) | May 03, 2023 |
| Apple         | MacBookAir3,1               | [97d802a5d6](https://linux-hardware.org/?probe=97d802a5d6) | May 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS0B010    | [3f87bce0eb](https://linux-hardware.org/?probe=3f87bce0eb) | May 01, 2023 |
| ASUSTek       | UX31E                       | [1fb0ca13ff](https://linux-hardware.org/?probe=1fb0ca13ff) | May 01, 2023 |
| Acer          | Extensa 5620                | [415396fa78](https://linux-hardware.org/?probe=415396fa78) | Apr 30, 2023 |
| ASUSTek       | UX31E                       | [e2c8068a7d](https://linux-hardware.org/?probe=e2c8068a7d) | Apr 28, 2023 |
| Acer          | Aspire E1-572G              | [6c35501215](https://linux-hardware.org/?probe=6c35501215) | Apr 27, 2023 |
| HP            | Victus by Gaming Laptop ... | [486535a4d3](https://linux-hardware.org/?probe=486535a4d3) | Apr 27, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | [fa228f68e4](https://linux-hardware.org/?probe=fa228f68e4) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | [33bc801258](https://linux-hardware.org/?probe=33bc801258) | Apr 26, 2023 |
| HP            | ProBook 4540s               | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Valve         | Jupiter                     | [9b44e9bc2c](https://linux-hardware.org/?probe=9b44e9bc2c) | Apr 25, 2023 |
| Valve         | Jupiter                     | [7c7421ffeb](https://linux-hardware.org/?probe=7c7421ffeb) | Apr 25, 2023 |
| Dell          | System XPS L502X            | [4fd4992d0f](https://linux-hardware.org/?probe=4fd4992d0f) | Apr 24, 2023 |
| HP            | ProBook 4540s               | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [db069c8b89](https://linux-hardware.org/?probe=db069c8b89) | Apr 21, 2023 |
| Acer          | Nitro AN515-45              | [91f538e2ab](https://linux-hardware.org/?probe=91f538e2ab) | Apr 21, 2023 |
| UMAX          | VisionBook 14Wa Pro         | [525241657b](https://linux-hardware.org/?probe=525241657b) | Apr 20, 2023 |
| UMAX          | VisionBook 14Wa Pro         | [07e2728dfe](https://linux-hardware.org/?probe=07e2728dfe) | Apr 20, 2023 |
| Lenovo        | ThinkPad P52 20MAS5KM00     | [06ab19cc37](https://linux-hardware.org/?probe=06ab19cc37) | Apr 20, 2023 |
| HP            | Laptop 15-db1xxx            | [f158ac4161](https://linux-hardware.org/?probe=f158ac4161) | Apr 17, 2023 |
| Acer          | Aspire ES1-731G             | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [59d15de09e](https://linux-hardware.org/?probe=59d15de09e) | Apr 15, 2023 |
| ASUSTek       | UX31E                       | [429e68a4ac](https://linux-hardware.org/?probe=429e68a4ac) | Apr 14, 2023 |
| HP            | ProBook 450 G6              | [3364cf411c](https://linux-hardware.org/?probe=3364cf411c) | Apr 13, 2023 |
| Acer          | Aspire one                  | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [9a592d3392](https://linux-hardware.org/?probe=9a592d3392) | Apr 11, 2023 |
| Acer          | Aspire A515-47              | [8a78c5b08f](https://linux-hardware.org/?probe=8a78c5b08f) | Apr 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [2652354b7a](https://linux-hardware.org/?probe=2652354b7a) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [e5393f2dd6](https://linux-hardware.org/?probe=e5393f2dd6) | Apr 07, 2023 |
| ASUSTek       | UX31E                       | [3a1b0cca6b](https://linux-hardware.org/?probe=3a1b0cca6b) | Apr 04, 2023 |
| Apple         | MacBookPro12,1              | [b1168b92c0](https://linux-hardware.org/?probe=b1168b92c0) | Apr 03, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [f013c5ca48](https://linux-hardware.org/?probe=f013c5ca48) | Apr 03, 2023 |
| Notebook      | NJ50GU                      | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e3078a63c3](https://linux-hardware.org/?probe=e3078a63c3) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1c8c26f5c0](https://linux-hardware.org/?probe=1c8c26f5c0) | Apr 02, 2023 |
| HP            | 250 G3                      | [2030ba57b9](https://linux-hardware.org/?probe=2030ba57b9) | Apr 02, 2023 |
| Dell          | Latitude 5511               | [86b4fcff61](https://linux-hardware.org/?probe=86b4fcff61) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420s 4173R44      | [84e9a5f3d9](https://linux-hardware.org/?probe=84e9a5f3d9) | Apr 01, 2023 |
| UMAX          | VisionBook 14Wa Plus        | [ea8016c4a5](https://linux-hardware.org/?probe=ea8016c4a5) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0014e52bf3](https://linux-hardware.org/?probe=0014e52bf3) | Mar 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0ffc78eac6](https://linux-hardware.org/?probe=0ffc78eac6) | Mar 30, 2023 |
| ASUSTek       | F7L                         | [8d6f90f843](https://linux-hardware.org/?probe=8d6f90f843) | Mar 29, 2023 |
| ASUSTek       | F7L                         | [cdc5ab3b8a](https://linux-hardware.org/?probe=cdc5ab3b8a) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | [6599d32d74](https://linux-hardware.org/?probe=6599d32d74) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | [64bef0aff5](https://linux-hardware.org/?probe=64bef0aff5) | Mar 29, 2023 |
| Lenovo        | ThinkPad T580 20LAS4L216    | [9c3464baf9](https://linux-hardware.org/?probe=9c3464baf9) | Mar 27, 2023 |
| HP            | 250 G6 Notebook PC          | [eb82e949b2](https://linux-hardware.org/?probe=eb82e949b2) | Mar 27, 2023 |
| Lenovo        | G780                        | [1ad87e5add](https://linux-hardware.org/?probe=1ad87e5add) | Mar 23, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [aa102c68bf](https://linux-hardware.org/?probe=aa102c68bf) | Mar 23, 2023 |
| HP            | ProBook 450 G2              | [47992266f4](https://linux-hardware.org/?probe=47992266f4) | Mar 22, 2023 |
| HP            | ProBook 450 G2              | [dc56e35adc](https://linux-hardware.org/?probe=dc56e35adc) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Dell          | Latitude 5590               | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Acer          | TravelMate 2490             | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| ASUSTek       | UX31E                       | [b637fa75c8](https://linux-hardware.org/?probe=b637fa75c8) | Mar 18, 2023 |
| Acer          | TravelMate 7750ZG           | [5108cfe57c](https://linux-hardware.org/?probe=5108cfe57c) | Mar 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [5bf235f5d3](https://linux-hardware.org/?probe=5bf235f5d3) | Mar 16, 2023 |
| Dell          | Inspiron 5767               | [b7c8484508](https://linux-hardware.org/?probe=b7c8484508) | Mar 14, 2023 |
| ASUSTek       | UX31E                       | [7f3525f6ef](https://linux-hardware.org/?probe=7f3525f6ef) | Mar 12, 2023 |
| Dell          | Inspiron 5748               | [ef020a54d0](https://linux-hardware.org/?probe=ef020a54d0) | Mar 12, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| ASUSTek       | K54LY                       | [a846675d7f](https://linux-hardware.org/?probe=a846675d7f) | Mar 09, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | [fda0cb7297](https://linux-hardware.org/?probe=fda0cb7297) | Mar 08, 2023 |
| Dell          | Latitude E6420              | [c3384b7787](https://linux-hardware.org/?probe=c3384b7787) | Mar 07, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | [707155405b](https://linux-hardware.org/?probe=707155405b) | Mar 07, 2023 |
| MSI           | Modern 15 A5M               | [e88ffa7e1d](https://linux-hardware.org/?probe=e88ffa7e1d) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| ASUSTek       | UX31E                       | [ba97297cf9](https://linux-hardware.org/?probe=ba97297cf9) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G531GT            | [810e15295b](https://linux-hardware.org/?probe=810e15295b) | Mar 03, 2023 |
| Dell          | Latitude 5421               | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| ASUSTek       | 1016P                       | [739984c8cf](https://linux-hardware.org/?probe=739984c8cf) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [ceb6fb20b2](https://linux-hardware.org/?probe=ceb6fb20b2) | Mar 02, 2023 |
| ASUSTek       | 1016P                       | [29798857a5](https://linux-hardware.org/?probe=29798857a5) | Mar 02, 2023 |
| ASUSTek       | X555LA                      | [5dbbffb04e](https://linux-hardware.org/?probe=5dbbffb04e) | Mar 02, 2023 |
| UMAX          | VisionBook-N12R             | [2477ae9a0e](https://linux-hardware.org/?probe=2477ae9a0e) | Feb 27, 2023 |
| Standard      | Unknown                     | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [f0fa613cd2](https://linux-hardware.org/?probe=f0fa613cd2) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | Latitude 5420               | [231c7534d3](https://linux-hardware.org/?probe=231c7534d3) | Feb 21, 2023 |
| HP            | Laptop 15-rb0xx             | [3dd7359a43](https://linux-hardware.org/?probe=3dd7359a43) | Feb 20, 2023 |
| HP            | Laptop 15-rb0xx             | [53ef54922c](https://linux-hardware.org/?probe=53ef54922c) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| Toshiba       | Satellite L50D-B            | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| Dell          | Vostro1710                  | [91b1af7ed6](https://linux-hardware.org/?probe=91b1af7ed6) | Feb 19, 2023 |
| Standard      | Unknown                     | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | UX31E                       | [4c3c50a992](https://linux-hardware.org/?probe=4c3c50a992) | Feb 18, 2023 |
| ASUSTek       | UX31E                       | [e6391763b2](https://linux-hardware.org/?probe=e6391763b2) | Feb 17, 2023 |
| HP            | Laptop 17-cn0xxx            | [0e2199617b](https://linux-hardware.org/?probe=0e2199617b) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [6c8bdf1f73](https://linux-hardware.org/?probe=6c8bdf1f73) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [89f9d45c66](https://linux-hardware.org/?probe=89f9d45c66) | Feb 17, 2023 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [f546833d76](https://linux-hardware.org/?probe=f546833d76) | Feb 17, 2023 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [1026c10fa9](https://linux-hardware.org/?probe=1026c10fa9) | Feb 16, 2023 |
| ASUSTek       | UX31E                       | [0255141f61](https://linux-hardware.org/?probe=0255141f61) | Feb 15, 2023 |
| HP            | ProBook 470 G4              | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| HP            | Pavilion g6                 | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| HP            | OMEN by Laptop              | [849a50c7fd](https://linux-hardware.org/?probe=849a50c7fd) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| Acer          | Swift SF314-42              | [938edcc32a](https://linux-hardware.org/?probe=938edcc32a) | Feb 15, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| MSI           | GX700                       | [11154709fd](https://linux-hardware.org/?probe=11154709fd) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| ASUSTek       | UX31E                       | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [16d6cdad97](https://linux-hardware.org/?probe=16d6cdad97) | Feb 09, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| HP            | Laptop 15-db0xxx            | [8cb1801046](https://linux-hardware.org/?probe=8cb1801046) | Feb 07, 2023 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [e9082b6ebf](https://linux-hardware.org/?probe=e9082b6ebf) | Feb 04, 2023 |
| HP            | OMEN by Laptop              | [330da24dc9](https://linux-hardware.org/?probe=330da24dc9) | Feb 04, 2023 |
| HP            | ProBook 4530s               | [9ff88cbe9a](https://linux-hardware.org/?probe=9ff88cbe9a) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | [922ee5ede0](https://linux-hardware.org/?probe=922ee5ede0) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [0b73c3afe8](https://linux-hardware.org/?probe=0b73c3afe8) | Feb 03, 2023 |
| HP            | Stream Notebook PC 14       | [69628da41b](https://linux-hardware.org/?probe=69628da41b) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | [3bcca39276](https://linux-hardware.org/?probe=3bcca39276) | Feb 02, 2023 |
| HP            | OMEN by Laptop              | [1651e1e5af](https://linux-hardware.org/?probe=1651e1e5af) | Feb 02, 2023 |
| ASUSTek       | GL702VT                     | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| Lenovo        | ThinkPad E520 1143JYG       | [87735dd3b0](https://linux-hardware.org/?probe=87735dd3b0) | Feb 01, 2023 |
| HP            | Laptop 15-bw0xx             | [b7fce61d74](https://linux-hardware.org/?probe=b7fce61d74) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
| HP            | Compaq CQ58                 | [63dfd6ca48](https://linux-hardware.org/?probe=63dfd6ca48) | Jan 30, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| ASUSTek       | X200MA                      | [1c1f2d4d5b](https://linux-hardware.org/?probe=1c1f2d4d5b) | Jan 28, 2023 |
| Timi          | A35S                        | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| ASUSTek       | UX31E                       | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| HP            | EliteBook 8460p             | [bb83f545f7](https://linux-hardware.org/?probe=bb83f545f7) | Jan 24, 2023 |
| Dell          | Latitude 5530               | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Dell          | Precision 3530              | [f0fa541c85](https://linux-hardware.org/?probe=f0fa541c85) | Jan 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| ASUSTek       | UX303LN                     | [60f8946cdf](https://linux-hardware.org/?probe=60f8946cdf) | Jan 21, 2023 |
| Lenovo        | Yoga 700-14ISK 80QD         | [4e07ace043](https://linux-hardware.org/?probe=4e07ace043) | Jan 21, 2023 |
| ASUSTek       | UX303LN                     | [846e3df466](https://linux-hardware.org/?probe=846e3df466) | Jan 21, 2023 |
| HP            | EliteBook 8570p             | [66c806fbfe](https://linux-hardware.org/?probe=66c806fbfe) | Jan 21, 2023 |
| ASUSTek       | X555LF                      | [7220c25a3b](https://linux-hardware.org/?probe=7220c25a3b) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6c2dd878d0](https://linux-hardware.org/?probe=6c2dd878d0) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5f73278ca0](https://linux-hardware.org/?probe=5f73278ca0) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f7fcfb7b18](https://linux-hardware.org/?probe=f7fcfb7b18) | Jan 19, 2023 |
| ASUSTek       | 1011PX                      | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad E550 20DF0081MC    | [1b7e734f36](https://linux-hardware.org/?probe=1b7e734f36) | Jan 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [5b0e671bb8](https://linux-hardware.org/?probe=5b0e671bb8) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [395a44652b](https://linux-hardware.org/?probe=395a44652b) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [fa4fd9061f](https://linux-hardware.org/?probe=fa4fd9061f) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [6841633faf](https://linux-hardware.org/?probe=6841633faf) | Jan 16, 2023 |
| HP            | Pavilion dv6500             | [33985f088a](https://linux-hardware.org/?probe=33985f088a) | Jan 16, 2023 |
| HP            | 250 G3                      | [717fbc7972](https://linux-hardware.org/?probe=717fbc7972) | Jan 15, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [32f2651aa1](https://linux-hardware.org/?probe=32f2651aa1) | Jan 14, 2023 |
| HP            | ProBook 6560b               | [a9eba68b79](https://linux-hardware.org/?probe=a9eba68b79) | Jan 14, 2023 |
| ASUSTek       | UX31E                       | [d60bab803e](https://linux-hardware.org/?probe=d60bab803e) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Lenovo        | ThinkPad T450 20BUA0UG00    | [b0854ecbf8](https://linux-hardware.org/?probe=b0854ecbf8) | Jan 12, 2023 |
| Acer          | Extensa 2519                | [c044faaa05](https://linux-hardware.org/?probe=c044faaa05) | Jan 11, 2023 |
| Dell          | Precision 7710              | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| HP            | Laptop 15-rb0xx             | [fd8d969adb](https://linux-hardware.org/?probe=fd8d969adb) | Jan 11, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [e4c19089b5](https://linux-hardware.org/?probe=e4c19089b5) | Jan 11, 2023 |
| Dell          | Precision 5510              | [22a344ddad](https://linux-hardware.org/?probe=22a344ddad) | Jan 09, 2023 |
| HP            | EliteBook 840 G1            | [42f10f6d45](https://linux-hardware.org/?probe=42f10f6d45) | Jan 09, 2023 |
| Dell          | Precision 7710              | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| Lenovo        | ThinkPad X230 2320JNG       | [29d3023af5](https://linux-hardware.org/?probe=29d3023af5) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | [667330c83f](https://linux-hardware.org/?probe=667330c83f) | Jan 07, 2023 |
| UMAX          | VisionBook N14G Plus        | [412180b4de](https://linux-hardware.org/?probe=412180b4de) | Jan 06, 2023 |
| Acer          | TravelMate B115-M           | [c39cf71ff8](https://linux-hardware.org/?probe=c39cf71ff8) | Jan 05, 2023 |
| ASUSTek       | X405UA                      | [c56206ea8a](https://linux-hardware.org/?probe=c56206ea8a) | Jan 05, 2023 |
| Acer          | Aspire E1-531G              | [9b5a0200df](https://linux-hardware.org/?probe=9b5a0200df) | Jan 04, 2023 |
| Acer          | Aspire E1-531G              | [47813fa627](https://linux-hardware.org/?probe=47813fa627) | Jan 03, 2023 |
| HP            | ProBook 635 Aero G8         | [f710248f3c](https://linux-hardware.org/?probe=f710248f3c) | Jan 02, 2023 |
| Google        | Chell                       | [02a0ae3bea](https://linux-hardware.org/?probe=02a0ae3bea) | Jan 02, 2023 |
| Valve         | Jupiter                     | [dc3612b4e1](https://linux-hardware.org/?probe=dc3612b4e1) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Acer          | Aspire A515-47              | [aaf0830ffc](https://linux-hardware.org/?probe=aaf0830ffc) | Jan 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [bd53b75b7b](https://linux-hardware.org/?probe=bd53b75b7b) | Dec 30, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [2b646304f0](https://linux-hardware.org/?probe=2b646304f0) | Dec 29, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [74f8dcfbb4](https://linux-hardware.org/?probe=74f8dcfbb4) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK E736               | [8d54484965](https://linux-hardware.org/?probe=8d54484965) | Dec 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| UMAX          | VisionBook 14Wa Pro         | [7eb49ce0ab](https://linux-hardware.org/?probe=7eb49ce0ab) | Dec 24, 2022 |
| UMAX          | VisionBook 14Wa Pro         | [4123115ef0](https://linux-hardware.org/?probe=4123115ef0) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2b25ab8790](https://linux-hardware.org/?probe=2b25ab8790) | Dec 22, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [af14f0c425](https://linux-hardware.org/?probe=af14f0c425) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [e7393fd2b7](https://linux-hardware.org/?probe=e7393fd2b7) | Dec 20, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c20be92503](https://linux-hardware.org/?probe=c20be92503) | Dec 19, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [3fe5be03b1](https://linux-hardware.org/?probe=3fe5be03b1) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [b34d0f3a2c](https://linux-hardware.org/?probe=b34d0f3a2c) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | [651fa58fbd](https://linux-hardware.org/?probe=651fa58fbd) | Dec 12, 2022 |
| HP            | Pavilion TS 11              | [db2a3e8ebb](https://linux-hardware.org/?probe=db2a3e8ebb) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | [b5d4116615](https://linux-hardware.org/?probe=b5d4116615) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | [144f698515](https://linux-hardware.org/?probe=144f698515) | Dec 11, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [6e2cf6514a](https://linux-hardware.org/?probe=6e2cf6514a) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [b9ea8b5b2b](https://linux-hardware.org/?probe=b9ea8b5b2b) | Dec 08, 2022 |
| ASUSTek       | X55A                        | [283ef64c76](https://linux-hardware.org/?probe=283ef64c76) | Dec 08, 2022 |
| ASUSTek       | UX31E                       | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| MSI           | Prestige 14 A11SCX          | [2b5a2c145c](https://linux-hardware.org/?probe=2b5a2c145c) | Dec 06, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [2f14f32399](https://linux-hardware.org/?probe=2f14f32399) | Dec 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS2291X    | [312119ddbd](https://linux-hardware.org/?probe=312119ddbd) | Dec 06, 2022 |
| MSI           | Prestige 14 A11SCX          | [ca5bc5dfe6](https://linux-hardware.org/?probe=ca5bc5dfe6) | Dec 05, 2022 |
| ASUSTek       | UX31E                       | [7bde8b90c7](https://linux-hardware.org/?probe=7bde8b90c7) | Dec 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [e44ba4a41b](https://linux-hardware.org/?probe=e44ba4a41b) | Dec 03, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [2b1a977b21](https://linux-hardware.org/?probe=2b1a977b21) | Dec 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5955142015](https://linux-hardware.org/?probe=5955142015) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ea8b9066f6](https://linux-hardware.org/?probe=ea8b9066f6) | Nov 30, 2022 |
| HP            | 620                         | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| Fujitsu       | LIFEBOOK E756               | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [53b311f78c](https://linux-hardware.org/?probe=53b311f78c) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| HP            | 620                         | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| MSI           | Modern 14 B5M               | [2bd9abfe2c](https://linux-hardware.org/?probe=2bd9abfe2c) | Nov 20, 2022 |
| ASUSTek       | N73SV                       | [10840bac50](https://linux-hardware.org/?probe=10840bac50) | Nov 20, 2022 |
| ASUSTek       | K50IJ                       | [c57a9ae3d5](https://linux-hardware.org/?probe=c57a9ae3d5) | Nov 19, 2022 |
| ASUSTek       | K50IJ                       | [99ed91b58d](https://linux-hardware.org/?probe=99ed91b58d) | Nov 19, 2022 |
| Dell          | Precision 5510              | [a9467ec69d](https://linux-hardware.org/?probe=a9467ec69d) | Nov 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3eaa12ef7a](https://linux-hardware.org/?probe=3eaa12ef7a) | Nov 16, 2022 |
| ASUSTek       | K50IJ                       | [c7ac1636bc](https://linux-hardware.org/?probe=c7ac1636bc) | Nov 15, 2022 |
| ASUSTek       | N61Jv                       | [c8c143ccdd](https://linux-hardware.org/?probe=c8c143ccdd) | Nov 14, 2022 |
| ASUSTek       | N61Jv                       | [bc9518dbad](https://linux-hardware.org/?probe=bc9518dbad) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | [a7e35fd231](https://linux-hardware.org/?probe=a7e35fd231) | Nov 12, 2022 |
| Dell          | Latitude 7480               | [62d1e401a4](https://linux-hardware.org/?probe=62d1e401a4) | Nov 12, 2022 |
| HP            | Pavilion g6                 | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| Dell          | Latitude 7480               | [350e3f7ee2](https://linux-hardware.org/?probe=350e3f7ee2) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| HP            | Pavilion dv7                | [5b01559647](https://linux-hardware.org/?probe=5b01559647) | Nov 11, 2022 |
| ASUSTek       | K54LY                       | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| ASUSTek       | X550VXK                     | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Packard Be... | EasyNote TK85               | [8a4f5a2c29](https://linux-hardware.org/?probe=8a4f5a2c29) | Nov 07, 2022 |
| HP            | ProBook 4530s               | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| Dell          | Inspiron 5515               | [fcb59bae39](https://linux-hardware.org/?probe=fcb59bae39) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | [001308a248](https://linux-hardware.org/?probe=001308a248) | Nov 06, 2022 |
| HP            | Pavilion g6                 | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| HP            | Pavilion g6                 | [38b8d5a898](https://linux-hardware.org/?probe=38b8d5a898) | Nov 04, 2022 |
| Acer          | Aspire 5738                 | [f5ac63680f](https://linux-hardware.org/?probe=f5ac63680f) | Nov 04, 2022 |
| SLIMBOOK      | Executive                   | [cff86cc921](https://linux-hardware.org/?probe=cff86cc921) | Nov 04, 2022 |
| Sony          | VPCYB1S1E                   | [54d0a26de9](https://linux-hardware.org/?probe=54d0a26de9) | Nov 03, 2022 |
| UMAX          | VisionBook N15G Plus        | [eba9cd6286](https://linux-hardware.org/?probe=eba9cd6286) | Nov 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | [e4f3828910](https://linux-hardware.org/?probe=e4f3828910) | Nov 01, 2022 |
| ASUSTek       | UX31E                       | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| UMAX          | VisionBook 12Wi 64G         | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| Lenovo        | B590 20206                  | [8a8967999b](https://linux-hardware.org/?probe=8a8967999b) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Dell          | Latitude E6440              | [307356784a](https://linux-hardware.org/?probe=307356784a) | Oct 26, 2022 |
| Apple         | MacBookPro10,1              | [212ce8900d](https://linux-hardware.org/?probe=212ce8900d) | Oct 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| HP            | Pavilion dv7                | [4c6edfec3e](https://linux-hardware.org/?probe=4c6edfec3e) | Oct 18, 2022 |
| HP            | Pavilion dv7                | [22031176a8](https://linux-hardware.org/?probe=22031176a8) | Oct 18, 2022 |
| ASUSTek       | UX31E                       | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| Dell          | XPS 15 9550                 | [00d5f7c4b1](https://linux-hardware.org/?probe=00d5f7c4b1) | Oct 13, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| SmbiosType... | SmbiosType1_SystemProduc... | [d105b4c1f7](https://linux-hardware.org/?probe=d105b4c1f7) | Oct 11, 2022 |
| ASUSTek       | UX31E                       | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| Dell          | Latitude E7250              | [5ecb7bbb6c](https://linux-hardware.org/?probe=5ecb7bbb6c) | Oct 07, 2022 |
| ASUSTek       | 1001PXD                     | [524e4ab046](https://linux-hardware.org/?probe=524e4ab046) | Oct 06, 2022 |
| HP            | EliteBook 1040 G4           | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| Timi          | A35S                        | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | [7c19c1f557](https://linux-hardware.org/?probe=7c19c1f557) | Oct 02, 2022 |
| Acer          | Aspire 7540                 | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| ASUSTek       | K54LY                       | [98197c818f](https://linux-hardware.org/?probe=98197c818f) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [92f9efe077](https://linux-hardware.org/?probe=92f9efe077) | Sep 30, 2022 |
| Notebook      | NJ50GU                      | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [9377d23abd](https://linux-hardware.org/?probe=9377d23abd) | Sep 28, 2022 |
| Timi          | A35S                        | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | K53SV                       | [d2801f9560](https://linux-hardware.org/?probe=d2801f9560) | Sep 26, 2022 |
| Lenovo        | 3000 V100 076346G           | [0575c1ea4f](https://linux-hardware.org/?probe=0575c1ea4f) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| Timi          | RedmiBook 16                | [0a65bab615](https://linux-hardware.org/?probe=0a65bab615) | Sep 25, 2022 |
| Acer          | Aspire VN7-592G             | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| HP            | ProBook 450 G5              | [262ff53f6a](https://linux-hardware.org/?probe=262ff53f6a) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | [d1ed6b20cf](https://linux-hardware.org/?probe=d1ed6b20cf) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | [9e04fb330b](https://linux-hardware.org/?probe=9e04fb330b) | Sep 24, 2022 |
| Timi          | A35S                        | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Valve         | Jupiter                     | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Acer          | Nitro AN515-57              | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [dce5b5917c](https://linux-hardware.org/?probe=dce5b5917c) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| Lenovo        | IdeaPad Y570 20091          | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Dell          | Latitude 5430               | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| Lenovo        | ThinkPad T540p 20BF002CM... | [3343da6005](https://linux-hardware.org/?probe=3343da6005) | Sep 12, 2022 |
| ASUSTek       | UX31E                       | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 23444ZG       | [d83eee9752](https://linux-hardware.org/?probe=d83eee9752) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| UMAX          | VisionBook N15G Plus        | [d17fb4f8f9](https://linux-hardware.org/?probe=d17fb4f8f9) | Sep 11, 2022 |
| Dell          | Latitude 5531               | [66eac260ef](https://linux-hardware.org/?probe=66eac260ef) | Sep 09, 2022 |
| Dell          | Precision 3551              | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
| Lenovo        | B71-80 80RJ                 | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Dell          | Latitude 5531               | [dff44a5e24](https://linux-hardware.org/?probe=dff44a5e24) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| Google        | Coral                       | [af898f9be4](https://linux-hardware.org/?probe=af898f9be4) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| ASUSTek       | UX31E                       | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [60b4add0a0](https://linux-hardware.org/?probe=60b4add0a0) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [2a3eb4b772](https://linux-hardware.org/?probe=2a3eb4b772) | Sep 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cc30fbdce2](https://linux-hardware.org/?probe=cc30fbdce2) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| HP            | EliteBook 650 15.6 inch ... | [918418e0fc](https://linux-hardware.org/?probe=918418e0fc) | Aug 29, 2022 |
| ASUSTek       | X553MA                      | [108e0c7803](https://linux-hardware.org/?probe=108e0c7803) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [bddbedffed](https://linux-hardware.org/?probe=bddbedffed) | Aug 29, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Valve         | Jupiter                     | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| MSI           | GS73VR 6RF                  | [870534e620](https://linux-hardware.org/?probe=870534e620) | Aug 23, 2022 |
| Dell          | Latitude 5490               | [a37eabe03f](https://linux-hardware.org/?probe=a37eabe03f) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2e77015116](https://linux-hardware.org/?probe=2e77015116) | Aug 21, 2022 |
| ASUSTek       | UX31E                       | [84ed4c9d73](https://linux-hardware.org/?probe=84ed4c9d73) | Aug 20, 2022 |
| HP            | ElitePad 1000 G2            | [ed06ba603c](https://linux-hardware.org/?probe=ed06ba603c) | Aug 19, 2022 |
| Lenovo        | ThinkPad Edge E431 62774... | [b7d37d0c4c](https://linux-hardware.org/?probe=b7d37d0c4c) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| HP            | ZBook 15 G3                 | [f89a185aa6](https://linux-hardware.org/?probe=f89a185aa6) | Aug 17, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Acer          | Aspire 3100                 | [8ea61dbd3c](https://linux-hardware.org/?probe=8ea61dbd3c) | Aug 14, 2022 |
| Acer          | Aspire A515-56              | [e93f8de88b](https://linux-hardware.org/?probe=e93f8de88b) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | [e429237c05](https://linux-hardware.org/?probe=e429237c05) | Aug 13, 2022 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [0f367345a0](https://linux-hardware.org/?probe=0f367345a0) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| Dell          | XPS 13 9360                 | [a78c885366](https://linux-hardware.org/?probe=a78c885366) | Aug 12, 2022 |
| Lenovo        | ThinkPad E590 20NB0029MC    | [233b3cdd54](https://linux-hardware.org/?probe=233b3cdd54) | Aug 11, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [8b0ede5e40](https://linux-hardware.org/?probe=8b0ede5e40) | Aug 10, 2022 |
| HUAWEI        | BOHB-WAX9                   | [9d55b54de7](https://linux-hardware.org/?probe=9d55b54de7) | Aug 10, 2022 |
| Dell          | Latitude 5421               | [b088f6b599](https://linux-hardware.org/?probe=b088f6b599) | Aug 10, 2022 |
| Dell          | Latitude 5531               | [64998a7d5a](https://linux-hardware.org/?probe=64998a7d5a) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [9c945add4e](https://linux-hardware.org/?probe=9c945add4e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [d1ab7d1d36](https://linux-hardware.org/?probe=d1ab7d1d36) | Aug 06, 2022 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [2577ffae50](https://linux-hardware.org/?probe=2577ffae50) | Aug 06, 2022 |
| Dell          | Inspiron 5558               | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| HP            | 250 G5 Notebook PC          | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [45e79d015c](https://linux-hardware.org/?probe=45e79d015c) | Jul 23, 2022 |
| ASUSTek       | UX31E                       | [1ae28afad9](https://linux-hardware.org/?probe=1ae28afad9) | Jul 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [c000bcc566](https://linux-hardware.org/?probe=c000bcc566) | Jul 20, 2022 |
| HP            | ProBook 450 G5              | [47c85dbefd](https://linux-hardware.org/?probe=47c85dbefd) | Jul 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [179267a713](https://linux-hardware.org/?probe=179267a713) | Jul 15, 2022 |
| Dell          | G3 3590                     | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | K54LY                       | [9b66e8ad0e](https://linux-hardware.org/?probe=9b66e8ad0e) | Jul 14, 2022 |
| ASUSTek       | UX31E                       | [004f74eaf4](https://linux-hardware.org/?probe=004f74eaf4) | Jul 13, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| HP            | ProBook 450 G5              | [e3962f34e4](https://linux-hardware.org/?probe=e3962f34e4) | Jul 11, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | ProBook 450 G5              | [90f45f2ebc](https://linux-hardware.org/?probe=90f45f2ebc) | Jul 08, 2022 |
| Dell          | XPS 15 9510                 | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6a78826e86](https://linux-hardware.org/?probe=6a78826e86) | Jul 07, 2022 |
| ASUSTek       | X542UQR                     | [04cc10b779](https://linux-hardware.org/?probe=04cc10b779) | Jul 07, 2022 |
| Dell          | Inspiron 3542               | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| HP            | ProBook 4530s               | [db207530bc](https://linux-hardware.org/?probe=db207530bc) | Jul 06, 2022 |
| HP            | Notebook                    | [9b87d6ee2d](https://linux-hardware.org/?probe=9b87d6ee2d) | Jul 06, 2022 |
| Dell          | Latitude 7520               | [531ccedcf2](https://linux-hardware.org/?probe=531ccedcf2) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| HP            | 625                         | [0acc5581d4](https://linux-hardware.org/?probe=0acc5581d4) | Jul 03, 2022 |
| ASUSTek       | UX31E                       | [7504f06baa](https://linux-hardware.org/?probe=7504f06baa) | Jul 02, 2022 |
| Lenovo        | Z70-80 80FG                 | [eaf34443c7](https://linux-hardware.org/?probe=eaf34443c7) | Jul 01, 2022 |
| ASUSTek       | UX31E                       | [d3f27ab291](https://linux-hardware.org/?probe=d3f27ab291) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [bef849e3d1](https://linux-hardware.org/?probe=bef849e3d1) | Jun 29, 2022 |
| Lenovo        | ThinkPad S5-S540 20B3001... | [d5be9c4fca](https://linux-hardware.org/?probe=d5be9c4fca) | Jun 29, 2022 |
| Valve         | Jupiter                     | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| ASUSTek       | UX31E                       | [a346ece8f5](https://linux-hardware.org/?probe=a346ece8f5) | Jun 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| Dell          | Precision 5550              | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| Dell          | Precision 5550              | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [6ed235813a](https://linux-hardware.org/?probe=6ed235813a) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [af51b1d9da](https://linux-hardware.org/?probe=af51b1d9da) | Jun 19, 2022 |
| Dell          | Latitude E5470              | [e18ba2b5d7](https://linux-hardware.org/?probe=e18ba2b5d7) | Jun 18, 2022 |
| HP            | Compaq nc6120 (PN936AV)     | [c1ecdd7b5a](https://linux-hardware.org/?probe=c1ecdd7b5a) | Jun 17, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [4a8b021e76](https://linux-hardware.org/?probe=4a8b021e76) | Jun 11, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| Lenovo        | ThinkPad T460s 20FA003JM... | [417d162cab](https://linux-hardware.org/?probe=417d162cab) | Jun 09, 2022 |
| ASUSTek       | UX31E                       | [4abfa2a1d0](https://linux-hardware.org/?probe=4abfa2a1d0) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | [81335c6978](https://linux-hardware.org/?probe=81335c6978) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | [62d39f4677](https://linux-hardware.org/?probe=62d39f4677) | Jun 08, 2022 |
| ASUSTek       | K54LY                       | [39ad69783e](https://linux-hardware.org/?probe=39ad69783e) | Jun 08, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c6975f2914](https://linux-hardware.org/?probe=c6975f2914) | Jun 07, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [77b282aaaa](https://linux-hardware.org/?probe=77b282aaaa) | Jun 05, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [b320ea6050](https://linux-hardware.org/?probe=b320ea6050) | Jun 05, 2022 |
| MSI           | GP72 7QF                    | [ad0e85dbf9](https://linux-hardware.org/?probe=ad0e85dbf9) | Jun 05, 2022 |
| ASUSTek       | UX31E                       | [250825e17e](https://linux-hardware.org/?probe=250825e17e) | Jun 03, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [ac88b5f927](https://linux-hardware.org/?probe=ac88b5f927) | Jun 03, 2022 |
| HP            | ProBook 450 G7              | [010b492184](https://linux-hardware.org/?probe=010b492184) | May 31, 2022 |
| ASUSTek       | UX31E                       | [201add5732](https://linux-hardware.org/?probe=201add5732) | May 29, 2022 |
| HP            | Pavilion dv6                | [3623a980f8](https://linux-hardware.org/?probe=3623a980f8) | May 28, 2022 |
| HP            | EliteBook 8760w             | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| ASUSTek       | UX31E                       | [3905de150e](https://linux-hardware.org/?probe=3905de150e) | May 24, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [9f202f07cd](https://linux-hardware.org/?probe=9f202f07cd) | May 24, 2022 |
| Lenovo        | ThinkPad T420 42362L0       | [3aa17b879d](https://linux-hardware.org/?probe=3aa17b879d) | May 22, 2022 |
| Toshiba       | Satellite L10W-C            | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| ASUSTek       | UX31E                       | [12407852be](https://linux-hardware.org/?probe=12407852be) | May 21, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| Acer          | Swift SF314-52              | [4c199417ea](https://linux-hardware.org/?probe=4c199417ea) | May 19, 2022 |
| Acer          | Aspire 3100                 | [47e42883f4](https://linux-hardware.org/?probe=47e42883f4) | May 18, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| Acer          | Swift SF314-52              | [a532101bbf](https://linux-hardware.org/?probe=a532101bbf) | May 17, 2022 |
| HP            | ProBook 455 G7              | [95daa19596](https://linux-hardware.org/?probe=95daa19596) | May 17, 2022 |
| HP            | ProBook 455 G7              | [a96c7163a5](https://linux-hardware.org/?probe=a96c7163a5) | May 17, 2022 |
| Dell          | Vostro 5568                 | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| ASUSTek       | X101CH                      | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| ASUSTek       | X555LB                      | [2c2e8fcf67](https://linux-hardware.org/?probe=2c2e8fcf67) | May 15, 2022 |
| ASUSTek       | UX31E                       | [85613b8729](https://linux-hardware.org/?probe=85613b8729) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| ASUSTek       | UX31E                       | [b83f4f894e](https://linux-hardware.org/?probe=b83f4f894e) | May 13, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Chuwi         | MiniBook X                  | [541609a32e](https://linux-hardware.org/?probe=541609a32e) | May 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [52fa4973d5](https://linux-hardware.org/?probe=52fa4973d5) | May 10, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | [a70f694f0b](https://linux-hardware.org/?probe=a70f694f0b) | May 09, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [badd8c8562](https://linux-hardware.org/?probe=badd8c8562) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | [73714bdb43](https://linux-hardware.org/?probe=73714bdb43) | May 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [dcff76e99c](https://linux-hardware.org/?probe=dcff76e99c) | May 02, 2022 |
| ASUSTek       | UX31E                       | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Dell          | Latitude 3330               | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| ASUSTek       | UX31E                       | [8f165f54aa](https://linux-hardware.org/?probe=8f165f54aa) | Apr 29, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-45              | [aee7cca97f](https://linux-hardware.org/?probe=aee7cca97f) | Apr 28, 2022 |
| ASUSTek       | UX31E                       | [ef86b0396a](https://linux-hardware.org/?probe=ef86b0396a) | Apr 27, 2022 |
| Acer          | Aspire 5742G                | [313e7bcf23](https://linux-hardware.org/?probe=313e7bcf23) | Apr 27, 2022 |
| HP            | ZBook 17 G3                 | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Dell          | Latitude 7390 2-in-1        | [8391ca514e](https://linux-hardware.org/?probe=8391ca514e) | Apr 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| Lenovo        | ThinkPad E15 20RD001EMC     | [d98ca42427](https://linux-hardware.org/?probe=d98ca42427) | Apr 20, 2022 |
| Dell          | Latitude 5480               | [811930e65e](https://linux-hardware.org/?probe=811930e65e) | Apr 20, 2022 |
| Lenovo        | B50-80 80EW                 | [2d1471986b](https://linux-hardware.org/?probe=2d1471986b) | Apr 19, 2022 |
| Acer          | Aspire V3-112P              | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |
| ASUSTek       | UX31E                       | [fa535559e0](https://linux-hardware.org/?probe=fa535559e0) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [fccfb454e4](https://linux-hardware.org/?probe=fccfb454e4) | Apr 16, 2022 |
| Lenovo        | ThinkPad T400 6474AH2       | [f5e7108c33](https://linux-hardware.org/?probe=f5e7108c33) | Apr 15, 2022 |
| Lenovo        | E31-80 80MX                 | [ea96e85c49](https://linux-hardware.org/?probe=ea96e85c49) | Apr 14, 2022 |
| Lenovo        | B50-80 80EW                 | [d180d3831a](https://linux-hardware.org/?probe=d180d3831a) | Apr 10, 2022 |
| Acer          | TravelMate 4670             | [f5067e581b](https://linux-hardware.org/?probe=f5067e581b) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | [7f4e9c9158](https://linux-hardware.org/?probe=7f4e9c9158) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | [7249da837c](https://linux-hardware.org/?probe=7249da837c) | Apr 06, 2022 |
| Acer          | Extensa 5630                | [7ff131392d](https://linux-hardware.org/?probe=7ff131392d) | Apr 05, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [59eedbbc1b](https://linux-hardware.org/?probe=59eedbbc1b) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Dell          | XPS 15 9550                 | [487aa8af18](https://linux-hardware.org/?probe=487aa8af18) | Apr 03, 2022 |
| Acer          | Extensa 5630                | [4c6f7067bc](https://linux-hardware.org/?probe=4c6f7067bc) | Apr 02, 2022 |
| ASUSTek       | UX31E                       | [beb645df2c](https://linux-hardware.org/?probe=beb645df2c) | Apr 02, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [96e4eca691](https://linux-hardware.org/?probe=96e4eca691) | Apr 01, 2022 |
| ASUSTek       | UX31E                       | [54717b42d3](https://linux-hardware.org/?probe=54717b42d3) | Mar 31, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [e69dbda259](https://linux-hardware.org/?probe=e69dbda259) | Mar 31, 2022 |
| Acer          | Aspire E5-573G              | [39d3a3ac9d](https://linux-hardware.org/?probe=39d3a3ac9d) | Mar 30, 2022 |
| Acer          | Aspire P3-171               | [972861cbcc](https://linux-hardware.org/?probe=972861cbcc) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AWA07B0... | [4e67f54e53](https://linux-hardware.org/?probe=4e67f54e53) | Mar 29, 2022 |
| ASUSTek       | UX31E                       | [d83c6588f2](https://linux-hardware.org/?probe=d83c6588f2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [649bc1b13a](https://linux-hardware.org/?probe=649bc1b13a) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [d1638977bc](https://linux-hardware.org/?probe=d1638977bc) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | [67c079dd83](https://linux-hardware.org/?probe=67c079dd83) | Mar 28, 2022 |
| HP            | Compaq 615                  | [77439caf8f](https://linux-hardware.org/?probe=77439caf8f) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | [582d76d560](https://linux-hardware.org/?probe=582d76d560) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Acer          | Aspire 3000                 | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | [6df7f8330c](https://linux-hardware.org/?probe=6df7f8330c) | Mar 25, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [c6ed527183](https://linux-hardware.org/?probe=c6ed527183) | Mar 25, 2022 |
| Lenovo        | ThinkPad X61s 7667CB5       | [05a3f6eba9](https://linux-hardware.org/?probe=05a3f6eba9) | Mar 25, 2022 |
| ASUSTek       | UX31E                       | [ad8feeb6a4](https://linux-hardware.org/?probe=ad8feeb6a4) | Mar 24, 2022 |
| HP            | Compaq 615                  | [c61f5e75c7](https://linux-hardware.org/?probe=c61f5e75c7) | Mar 24, 2022 |
| Dell          | Latitude E6430s             | [8ac18b3ae9](https://linux-hardware.org/?probe=8ac18b3ae9) | Mar 24, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [26443633b7](https://linux-hardware.org/?probe=26443633b7) | Mar 23, 2022 |
| ASUSTek       | UX31E                       | [3f268da44f](https://linux-hardware.org/?probe=3f268da44f) | Mar 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [9fb46d3913](https://linux-hardware.org/?probe=9fb46d3913) | Mar 22, 2022 |
| HP            | ProBook 450 G6              | [e8072f850f](https://linux-hardware.org/?probe=e8072f850f) | Mar 22, 2022 |
| ASUSTek       | UX31E                       | [86242fab56](https://linux-hardware.org/?probe=86242fab56) | Mar 21, 2022 |
| Acer          | Aspire E5-521               | [ad4ffeb6d5](https://linux-hardware.org/?probe=ad4ffeb6d5) | Mar 20, 2022 |
| Acer          | Aspire E5-521               | [7f37d7148d](https://linux-hardware.org/?probe=7f37d7148d) | Mar 20, 2022 |
| HP            | Pavilion Notebook 15-dp0... | [4824a016cc](https://linux-hardware.org/?probe=4824a016cc) | Mar 18, 2022 |
| HP            | Pavilion Notebook 15-dp0... | [847871aa63](https://linux-hardware.org/?probe=847871aa63) | Mar 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [12249482c6](https://linux-hardware.org/?probe=12249482c6) | Mar 17, 2022 |
| Dell          | Latitude E4200              | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| ASUSTek       | X550VXK                     | [9d51869d37](https://linux-hardware.org/?probe=9d51869d37) | Mar 15, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [d627d6a6a0](https://linux-hardware.org/?probe=d627d6a6a0) | Mar 14, 2022 |
| ASUSTek       | UX31E                       | [620772c443](https://linux-hardware.org/?probe=620772c443) | Mar 11, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| Acer          | Aspire 3100                 | [0429db8c01](https://linux-hardware.org/?probe=0429db8c01) | Mar 11, 2022 |
| HP            | Laptop 15-db0xxx            | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Toshiba       | Satellite L750D             | [84ccdf8375](https://linux-hardware.org/?probe=84ccdf8375) | Mar 10, 2022 |
| ASUSTek       | UX31E                       | [62f3b41d12](https://linux-hardware.org/?probe=62f3b41d12) | Mar 09, 2022 |
| Acer          | TP-SW5-012-16UW             | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| Toshiba       | Satellite L750D             | [71d5919c2d](https://linux-hardware.org/?probe=71d5919c2d) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | [889c1ad7d2](https://linux-hardware.org/?probe=889c1ad7d2) | Mar 07, 2022 |
| Acer          | Aspire 5349                 | [cd3380a8b4](https://linux-hardware.org/?probe=cd3380a8b4) | Mar 07, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [3667f5b9e9](https://linux-hardware.org/?probe=3667f5b9e9) | Mar 07, 2022 |
| Acer          | Extensa 5620                | [3104016080](https://linux-hardware.org/?probe=3104016080) | Mar 06, 2022 |
| ASUSTek       | UX31E                       | [885cc74a20](https://linux-hardware.org/?probe=885cc74a20) | Mar 05, 2022 |
| HP            | ProBook 455 G7              | [311c6da8e0](https://linux-hardware.org/?probe=311c6da8e0) | Mar 05, 2022 |
| Dell          | Latitude E5470              | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [3333e54277](https://linux-hardware.org/?probe=3333e54277) | Mar 04, 2022 |
| Dell          | Latitude 7520               | [023fba74f0](https://linux-hardware.org/?probe=023fba74f0) | Mar 04, 2022 |
| ASUSTek       | UX31E                       | [c4106a59b1](https://linux-hardware.org/?probe=c4106a59b1) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [6d96f7e645](https://linux-hardware.org/?probe=6d96f7e645) | Mar 02, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [66cdff8786](https://linux-hardware.org/?probe=66cdff8786) | Mar 02, 2022 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [21b4f724b8](https://linux-hardware.org/?probe=21b4f724b8) | Mar 02, 2022 |
| Dell          | Latitude 7520               | [d31adbbcad](https://linux-hardware.org/?probe=d31adbbcad) | Mar 02, 2022 |
| ASUSTek       | UX31E                       | [36ea5044b6](https://linux-hardware.org/?probe=36ea5044b6) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [cab4f22396](https://linux-hardware.org/?probe=cab4f22396) | Feb 28, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [55773feeee](https://linux-hardware.org/?probe=55773feeee) | Feb 27, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [9ffeec636e](https://linux-hardware.org/?probe=9ffeec636e) | Feb 26, 2022 |
| ASUSTek       | UX31E                       | [477b323b68](https://linux-hardware.org/?probe=477b323b68) | Feb 25, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [4cb3686ee5](https://linux-hardware.org/?probe=4cb3686ee5) | Feb 24, 2022 |
| ASUSTek       | UX31E                       | [a6dae44349](https://linux-hardware.org/?probe=a6dae44349) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [245600d3fd](https://linux-hardware.org/?probe=245600d3fd) | Feb 23, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [bedd29ee73](https://linux-hardware.org/?probe=bedd29ee73) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56496468de](https://linux-hardware.org/?probe=56496468de) | Feb 21, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [6cb1c24dd7](https://linux-hardware.org/?probe=6cb1c24dd7) | Feb 20, 2022 |
| ASUSTek       | X75A1                       | [232712babb](https://linux-hardware.org/?probe=232712babb) | Feb 19, 2022 |
| ASUSTek       | UX31E                       | [5651fbf2c8](https://linux-hardware.org/?probe=5651fbf2c8) | Feb 18, 2022 |
| Google        | Chell                       | [46b95ce3a4](https://linux-hardware.org/?probe=46b95ce3a4) | Feb 17, 2022 |
| Acer          | Aspire E5-573G              | [e162c17653](https://linux-hardware.org/?probe=e162c17653) | Feb 17, 2022 |
| Lenovo        | IdeaPad Z580                | [26e55e169b](https://linux-hardware.org/?probe=26e55e169b) | Feb 16, 2022 |
| Gigabyte      | GB-BSi7A-6500               | [9cfc09f66c](https://linux-hardware.org/?probe=9cfc09f66c) | Feb 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5JW0... | [df9633e08e](https://linux-hardware.org/?probe=df9633e08e) | Feb 13, 2022 |
| ASUSTek       | UX31E                       | [7b2a1e633f](https://linux-hardware.org/?probe=7b2a1e633f) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | [b78e30f502](https://linux-hardware.org/?probe=b78e30f502) | Feb 11, 2022 |
| Dell          | Latitude 5480               | [eddd68780f](https://linux-hardware.org/?probe=eddd68780f) | Feb 09, 2022 |
| ASUSTek       | UX31E                       | [f70763fe0a](https://linux-hardware.org/?probe=f70763fe0a) | Feb 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [3fa68165ea](https://linux-hardware.org/?probe=3fa68165ea) | Feb 07, 2022 |
| ASUSTek       | UX31E                       | [4346690bc8](https://linux-hardware.org/?probe=4346690bc8) | Feb 06, 2022 |
| Acer          | Aspire SW3-016              | [6375ec93db](https://linux-hardware.org/?probe=6375ec93db) | Feb 05, 2022 |
| ASUSTek       | UX31E                       | [1eceff18e2](https://linux-hardware.org/?probe=1eceff18e2) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| Lenovo        | G710 20252                  | [ffc1b2ca5a](https://linux-hardware.org/?probe=ffc1b2ca5a) | Feb 04, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| Lenovo        | G50-70 20351                | [c31d2c4893](https://linux-hardware.org/?probe=c31d2c4893) | Feb 04, 2022 |
| ASUSTek       | F5RL                        | [09497d2017](https://linux-hardware.org/?probe=09497d2017) | Feb 02, 2022 |
| ASUSTek       | F5RL                        | [77baf7aac1](https://linux-hardware.org/?probe=77baf7aac1) | Feb 02, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | [449f0842a4](https://linux-hardware.org/?probe=449f0842a4) | Feb 01, 2022 |
| Lenovo        | ThinkPad W530 2441B88       | [9c15c47f51](https://linux-hardware.org/?probe=9c15c47f51) | Feb 01, 2022 |
| Dell          | Latitude 7490               | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cd876e95b9](https://linux-hardware.org/?probe=cd876e95b9) | Jan 29, 2022 |
| ASUSTek       | X556UQ                      | [b9589b97a3](https://linux-hardware.org/?probe=b9589b97a3) | Jan 28, 2022 |
| HP            | ProBook 445 G7              | [a386252eaa](https://linux-hardware.org/?probe=a386252eaa) | Jan 28, 2022 |
| Unknown       | Unknown                     | [a6e928b122](https://linux-hardware.org/?probe=a6e928b122) | Jan 28, 2022 |
| Dell          | XPS 15 9560                 | [ee50dc0bb1](https://linux-hardware.org/?probe=ee50dc0bb1) | Jan 27, 2022 |
| ASUSTek       | K50ID                       | [fed48cd01d](https://linux-hardware.org/?probe=fed48cd01d) | Jan 27, 2022 |
| ASUSTek       | UX31E                       | [d6d51a7ce7](https://linux-hardware.org/?probe=d6d51a7ce7) | Jan 26, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S7D300    | [3fcdce23b5](https://linux-hardware.org/?probe=3fcdce23b5) | Jan 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [ab4eb272cb](https://linux-hardware.org/?probe=ab4eb272cb) | Jan 24, 2022 |
| Acer          | NC-E1-572-54208G            | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| UMAX          | MediaBook 14                | [87cb50f680](https://linux-hardware.org/?probe=87cb50f680) | Jan 23, 2022 |
| ASUSTek       | UX31E                       | [c64e8bdde9](https://linux-hardware.org/?probe=c64e8bdde9) | Jan 22, 2022 |
| Lenovo        | ThinkPad X395 20NL000HMC    | [6c07e3f92a](https://linux-hardware.org/?probe=6c07e3f92a) | Jan 21, 2022 |
| ASUSTek       | UX31E                       | [08320d55cd](https://linux-hardware.org/?probe=08320d55cd) | Jan 21, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [e5d8911653](https://linux-hardware.org/?probe=e5d8911653) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | [3f0a902b2e](https://linux-hardware.org/?probe=3f0a902b2e) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | [0b31274785](https://linux-hardware.org/?probe=0b31274785) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c76a20872b](https://linux-hardware.org/?probe=c76a20872b) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [11d1f56125](https://linux-hardware.org/?probe=11d1f56125) | Jan 18, 2022 |
| Dell          | Latitude 5420               | [dd45d8465d](https://linux-hardware.org/?probe=dd45d8465d) | Jan 17, 2022 |
| HP            | EliteBook 840 G6            | [c6b20915de](https://linux-hardware.org/?probe=c6b20915de) | Jan 17, 2022 |
| Notebook      | NS50MU                      | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| ASUSTek       | UX31E                       | [77c7eedd86](https://linux-hardware.org/?probe=77c7eedd86) | Jan 15, 2022 |
| Toshiba       | Satellite C55-A-19N         | [b53c0c9b39](https://linux-hardware.org/?probe=b53c0c9b39) | Jan 14, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [ba41989095](https://linux-hardware.org/?probe=ba41989095) | Jan 14, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [9111c65725](https://linux-hardware.org/?probe=9111c65725) | Jan 12, 2022 |
| HP            | ZBook 17 G2                 | [232d1f1cb4](https://linux-hardware.org/?probe=232d1f1cb4) | Jan 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | [94d85b9f5b](https://linux-hardware.org/?probe=94d85b9f5b) | Jan 12, 2022 |
| Dell          | Inspiron 13 5310            | [f45f45197a](https://linux-hardware.org/?probe=f45f45197a) | Jan 11, 2022 |
| HP            | ProBook 6450b               | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Lenovo        | ThinkPad E590 20NB001WMC    | [f114fe6200](https://linux-hardware.org/?probe=f114fe6200) | Jan 08, 2022 |
| Toshiba       | Satellite C55-A-1NU         | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| HP            | EliteBook 8540p             | [20b9948e89](https://linux-hardware.org/?probe=20b9948e89) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [13c6bafd04](https://linux-hardware.org/?probe=13c6bafd04) | Jan 08, 2022 |
| ASUSTek       | UX31E                       | [b976b5921e](https://linux-hardware.org/?probe=b976b5921e) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e50bae67a6](https://linux-hardware.org/?probe=e50bae67a6) | Jan 08, 2022 |
| Lenovo        | Yoga 2 13 20344             | [581a4abb8e](https://linux-hardware.org/?probe=581a4abb8e) | Jan 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| HP            | ProBook 4510s               | [50904e6b69](https://linux-hardware.org/?probe=50904e6b69) | Jan 06, 2022 |
| HP            | ProBook 4510s               | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Precision M4500             | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| Dell          | Latitude 3470               | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d774f42123](https://linux-hardware.org/?probe=d774f42123) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| Dell          | Inspiron 5570               | [3e6d1befd6](https://linux-hardware.org/?probe=3e6d1befd6) | Jan 03, 2022 |
| Dell          | Latitude 7480               | [24244e5717](https://linux-hardware.org/?probe=24244e5717) | Jan 02, 2022 |
| Acer          | Swift SF114-34              | [94b665863b](https://linux-hardware.org/?probe=94b665863b) | Jan 02, 2022 |
| ASUSTek       | UX31E                       | [926c4f82d1](https://linux-hardware.org/?probe=926c4f82d1) | Jan 01, 2022 |
| HP            | EliteBook 820 G1            | [90deec9056](https://linux-hardware.org/?probe=90deec9056) | Dec 30, 2021 |
| Dell          | Inspiron 7559               | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| HP            | ProBook 4540s               | [20af449f2a](https://linux-hardware.org/?probe=20af449f2a) | Dec 29, 2021 |
| HP            | ProBook 4540s               | [99fb3303bb](https://linux-hardware.org/?probe=99fb3303bb) | Dec 29, 2021 |
| Acer          | Aspire ES1-571              | [ae601c56b8](https://linux-hardware.org/?probe=ae601c56b8) | Dec 28, 2021 |
| ASUSTek       | UX31E                       | [cd8cc790a0](https://linux-hardware.org/?probe=cd8cc790a0) | Dec 27, 2021 |
| HP            | Laptop 17-cp0xxx            | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| HUAWEI        | HVY-WXX9                    | [2c33c2931e](https://linux-hardware.org/?probe=2c33c2931e) | Dec 26, 2021 |
| Lenovo        | G710 20252                  | [961341534c](https://linux-hardware.org/?probe=961341534c) | Dec 26, 2021 |
| Acer          | Swift SF315-41              | [92f264978e](https://linux-hardware.org/?probe=92f264978e) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | [d94d38f29b](https://linux-hardware.org/?probe=d94d38f29b) | Dec 25, 2021 |
| ASUSTek       | X705NC                      | [c3cdc81bd8](https://linux-hardware.org/?probe=c3cdc81bd8) | Dec 25, 2021 |
| ASUSTek       | UX31E                       | [62488dea12](https://linux-hardware.org/?probe=62488dea12) | Dec 25, 2021 |
| Dell          | Latitude 5400               | [692bc521a6](https://linux-hardware.org/?probe=692bc521a6) | Dec 20, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| HP            | EliteBook 850 G6            | [0f1c42ef5d](https://linux-hardware.org/?probe=0f1c42ef5d) | Dec 18, 2021 |
| ASUSTek       | UX31E                       | [8c6db8aa19](https://linux-hardware.org/?probe=8c6db8aa19) | Dec 17, 2021 |
| Acer          | Aspire A515-56              | [a50b285530](https://linux-hardware.org/?probe=a50b285530) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440 20B7S1MW07    | [21baa9b1cc](https://linux-hardware.org/?probe=21baa9b1cc) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [a0ec890791](https://linux-hardware.org/?probe=a0ec890791) | Dec 15, 2021 |
| ASUSTek       | X751LN                      | [f7489ee0ae](https://linux-hardware.org/?probe=f7489ee0ae) | Dec 15, 2021 |
| ASUSTek       | UX31E                       | [f5d5138937](https://linux-hardware.org/?probe=f5d5138937) | Dec 13, 2021 |
| HP            | EliteBook 840 G6            | [a20ecb525c](https://linux-hardware.org/?probe=a20ecb525c) | Dec 13, 2021 |
| Acer          | Aspire E5-721               | [53ab8f6179](https://linux-hardware.org/?probe=53ab8f6179) | Dec 12, 2021 |
| HP            | Laptop 14-cf0xxx            | [2f4ec869f9](https://linux-hardware.org/?probe=2f4ec869f9) | Dec 12, 2021 |
| ASUSTek       | UX31E                       | [d48bfc96ce](https://linux-hardware.org/?probe=d48bfc96ce) | Dec 12, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Dell          | Latitude E4300              | [3dd32ae25d](https://linux-hardware.org/?probe=3dd32ae25d) | Dec 10, 2021 |
| Acer          | Extensa 5220                | [2572d3336d](https://linux-hardware.org/?probe=2572d3336d) | Dec 09, 2021 |
| Acer          | Extensa 5220                | [524256971b](https://linux-hardware.org/?probe=524256971b) | Dec 09, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [2694c27280](https://linux-hardware.org/?probe=2694c27280) | Dec 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| ASUSTek       | UX31E                       | [04c3a4b6c7](https://linux-hardware.org/?probe=04c3a4b6c7) | Dec 03, 2021 |
| Lenovo        | G770 20089                  | [6a4de555a2](https://linux-hardware.org/?probe=6a4de555a2) | Dec 03, 2021 |
| UMAX          | VisionBook N15G Plus        | [4b16e8ea9d](https://linux-hardware.org/?probe=4b16e8ea9d) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| Google        | Akemi                       | [0867d0658c](https://linux-hardware.org/?probe=0867d0658c) | Dec 01, 2021 |
| Google        | Akemi                       | [2344df2c6b](https://linux-hardware.org/?probe=2344df2c6b) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ae6614d6fb](https://linux-hardware.org/?probe=ae6614d6fb) | Nov 29, 2021 |
| ASUSTek       | UX31E                       | [0af8133ca3](https://linux-hardware.org/?probe=0af8133ca3) | Nov 29, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [9dd7b3ad9b](https://linux-hardware.org/?probe=9dd7b3ad9b) | Nov 29, 2021 |
| Acer          | P4LJ0                       | [0f57f6b606](https://linux-hardware.org/?probe=0f57f6b606) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [f047b9db0a](https://linux-hardware.org/?probe=f047b9db0a) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [d8d17c1820](https://linux-hardware.org/?probe=d8d17c1820) | Nov 27, 2021 |
| Lenovo        | G780                        | [ffeaa607f9](https://linux-hardware.org/?probe=ffeaa607f9) | Nov 27, 2021 |
| Lenovo        | G780                        | [26ea5410e6](https://linux-hardware.org/?probe=26ea5410e6) | Nov 27, 2021 |
| Fujitsu       | LIFEBOOK T901               | [d9b8b1c304](https://linux-hardware.org/?probe=d9b8b1c304) | Nov 27, 2021 |
| ASUSTek       | X751LN                      | [2c8e1bfecd](https://linux-hardware.org/?probe=2c8e1bfecd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| ASUSTek       | X751LN                      | [50d304e970](https://linux-hardware.org/?probe=50d304e970) | Nov 22, 2021 |
| Unknown       | Unknown                     | [81e2289408](https://linux-hardware.org/?probe=81e2289408) | Nov 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6b2b37cfc2](https://linux-hardware.org/?probe=6b2b37cfc2) | Nov 20, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [c174aa242d](https://linux-hardware.org/?probe=c174aa242d) | Nov 20, 2021 |
| HP            | OMEN by Laptop              | [0b8f3a5da9](https://linux-hardware.org/?probe=0b8f3a5da9) | Nov 19, 2021 |
| ASUSTek       | UX31E                       | [27fde62ce2](https://linux-hardware.org/?probe=27fde62ce2) | Nov 18, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [f3bf7b971f](https://linux-hardware.org/?probe=f3bf7b971f) | Nov 18, 2021 |
| HP            | ProBook 4510s               | [46c61312c4](https://linux-hardware.org/?probe=46c61312c4) | Nov 18, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [66fd774069](https://linux-hardware.org/?probe=66fd774069) | Nov 17, 2021 |
| HP            | ProBook 4510s               | [cf53b2e2db](https://linux-hardware.org/?probe=cf53b2e2db) | Nov 17, 2021 |
| Fujitsu       | LIFEBOOK E754               | [9569f15e49](https://linux-hardware.org/?probe=9569f15e49) | Nov 16, 2021 |
| Dell          | Latitude E6420              | [71905152a8](https://linux-hardware.org/?probe=71905152a8) | Nov 14, 2021 |
| HP            | ProBook 455 G6              | [2a37f0ed64](https://linux-hardware.org/?probe=2a37f0ed64) | Nov 14, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [bf655cd438](https://linux-hardware.org/?probe=bf655cd438) | Nov 13, 2021 |
| HUAWEI        | HN-WX9X                     | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [1fe63ecbee](https://linux-hardware.org/?probe=1fe63ecbee) | Nov 13, 2021 |
| HP            | ProBook 640 G1              | [72d5b9727b](https://linux-hardware.org/?probe=72d5b9727b) | Nov 12, 2021 |
| HP            | OMEN by Laptop              | [207d9a7985](https://linux-hardware.org/?probe=207d9a7985) | Nov 12, 2021 |
| HP            | Pavilion g6                 | [0332d112e9](https://linux-hardware.org/?probe=0332d112e9) | Nov 12, 2021 |
| HP            | ProBook 455 G6              | [6045aa2b3a](https://linux-hardware.org/?probe=6045aa2b3a) | Nov 12, 2021 |
| Dell          | Latitude E5440              | [310f365903](https://linux-hardware.org/?probe=310f365903) | Nov 10, 2021 |
| Timi          | A35                         | [f8818e4273](https://linux-hardware.org/?probe=f8818e4273) | Nov 10, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 159       | 10.71%  |
| Ubuntu 18.04                 | 83        | 5.59%   |
| Ubuntu 22.04                 | 78        | 5.25%   |
| OpenMandriva 4.2             | 75        | 5.05%   |
| OpenMandriva 4.50            | 58        | 3.91%   |
| OpenMandriva 4.3             | 40        | 2.69%   |
| Ubuntu 21.10                 | 29        | 1.95%   |
| Fedora 38                    | 28        | 1.89%   |
| Pop!_OS 22.04                | 26        | 1.75%   |
| Zorin 16                     | 22        | 1.48%   |
| Ubuntu 19.10                 | 22        | 1.48%   |
| Fedora 34                    | 22        | 1.48%   |
| Ubuntu 20.10                 | 21        | 1.41%   |
| openSUSE Tumbleweed-XXXXXXXX | 21        | 1.41%   |
| OpenMandriva 23.01           | 21        | 1.41%   |
| Arch Rolling                 | 21        | 1.41%   |
| Zorin 15                     | 20        | 1.35%   |
| Linux Mint 21.1              | 19        | 1.28%   |
| Debian 11                    | 19        | 1.28%   |
| Ubuntu 21.04                 | 18        | 1.21%   |
| Linux Mint 20                | 17        | 1.14%   |
| Arch                         | 17        | 1.14%   |
| Linux Mint 20.2              | 16        | 1.08%   |
| Linux Mint 19.3              | 16        | 1.08%   |
| Linux Mint 20.3              | 15        | 1.01%   |
| OpenMandriva 23.03           | 14        | 0.94%   |
| Manjaro                      | 14        | 0.94%   |
| Linux Mint 21.2              | 14        | 0.94%   |
| Fedora 35                    | 14        | 0.94%   |
| Fedora 33                    | 14        | 0.94%   |
| Debian 12                    | 14        | 0.94%   |
| Linux Mint 21                | 13        | 0.88%   |
| Linux Mint 20.1              | 13        | 0.88%   |
| Fedora 37                    | 13        | 0.88%   |
| Fedora 32                    | 13        | 0.88%   |
| Fedora 31                    | 13        | 0.88%   |
| Xubuntu 20.04                | 12        | 0.81%   |
| Ubuntu 19.04                 | 12        | 0.81%   |
| Kubuntu 22.04                | 12        | 0.81%   |
| Fedora 36                    | 12        | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 422       | 30.25%  |
| OpenMandriva  | 223       | 15.99%  |
| Fedora        | 132       | 9.46%   |
| Linux Mint    | 123       | 8.82%   |
| Debian        | 48        | 3.44%   |
| Zorin         | 43        | 3.08%   |
| Pop!_OS       | 41        | 2.94%   |
| Xubuntu       | 38        | 2.72%   |
| Arch          | 38        | 2.72%   |
| Manjaro       | 37        | 2.65%   |
| Kubuntu       | 33        | 2.37%   |
| openSUSE      | 27        | 1.94%   |
| Gentoo        | 25        | 1.79%   |
| ROSA          | 19        | 1.36%   |
| Lubuntu       | 13        | 0.93%   |
| KDE neon      | 13        | 0.93%   |
| Kali          | 13        | 0.93%   |
| ArcoLinux     | 10        | 0.72%   |
| Elementary    | 9         | 0.65%   |
| SteamOS       | 8         | 0.57%   |
| Endless       | 8         | 0.57%   |
| Ubuntu MATE   | 7         | 0.5%    |
| RHEL          | 6         | 0.43%   |
| Ubuntu Unity  | 5         | 0.36%   |
| Ubuntu Budgie | 4         | 0.29%   |
| Parrot        | 4         | 0.29%   |
| NixOS         | 4         | 0.29%   |
| MX            | 4         | 0.29%   |
| EndeavourOS   | 4         | 0.29%   |
| BlackPanther  | 3         | 0.22%   |
| Rocky Linux   | 2         | 0.14%   |
| Nobara        | 2         | 0.14%   |
| LMDE          | 2         | 0.14%   |
| LinuxFX       | 2         | 0.14%   |
| Garuda Linux  | 2         | 0.14%   |
| Artix         | 2         | 0.14%   |
| Void Linux    | 1         | 0.07%   |
| UbuntuDDE     | 1         | 0.07%   |
| TUXEDO OS     | 1         | 0.07%   |
| SystemRescue  | 1         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 74        | 4.62%   |
| 5.14.7-desktop-1omv4050  | 55        | 3.43%   |
| 5.16.7-desktop-1omv4003  | 39        | 2.43%   |
| 5.4.0-42-generic         | 23        | 1.43%   |
| 6.1.1-desktop-1omv2290   | 20        | 1.25%   |
| 5.4.0-52-generic         | 15        | 0.94%   |
| 5.15.0-46-generic        | 15        | 0.94%   |
| 6.2.6-desktop-1omv2390   | 13        | 0.81%   |
| 5.4.0-26-generic         | 13        | 0.81%   |
| 5.15.0-56-generic        | 13        | 0.81%   |
| 5.4.0-58-generic         | 12        | 0.75%   |
| 5.3.0-40-generic         | 11        | 0.69%   |
| 6.2.0-26-generic         | 10        | 0.62%   |
| 5.15.0-58-generic        | 10        | 0.62%   |
| 5.4.0-65-generic         | 9         | 0.56%   |
| 5.15.0-48-generic        | 9         | 0.56%   |
| 5.0.0-37-generic         | 9         | 0.56%   |
| 5.8.0-59-generic         | 8         | 0.5%    |
| 5.4.0-48-generic         | 8         | 0.5%    |
| 5.4.0-40-generic         | 8         | 0.5%    |
| 5.15.0-78-generic        | 8         | 0.5%    |
| 5.15.0-52-generic        | 8         | 0.5%    |
| 5.13.0-21-generic        | 8         | 0.5%    |
| 6.4.11-desktop-1omv2390  | 7         | 0.44%   |
| 6.2.6-76060206-generic   | 7         | 0.44%   |
| 5.4.0-91-generic         | 7         | 0.44%   |
| 5.19.0-32-generic        | 7         | 0.44%   |
| 5.11.0-27-generic        | 7         | 0.44%   |
| 6.1.0-13-amd64           | 6         | 0.37%   |
| 5.8.0-53-generic         | 6         | 0.37%   |
| 5.4.0-70-generic         | 6         | 0.37%   |
| 5.4.0-56-generic         | 6         | 0.37%   |
| 5.4.0-37-generic         | 6         | 0.37%   |
| 5.4.0-29-generic         | 6         | 0.37%   |
| 5.3.0-46-generic         | 6         | 0.37%   |
| 5.3.0-42-generic         | 6         | 0.37%   |
| 5.3.0-28-generic         | 6         | 0.37%   |
| 5.13.0-30-generic        | 6         | 0.37%   |
| 5.13.0-22-generic        | 6         | 0.37%   |
| 5.13.0-19-generic        | 6         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 195       | 12.89%  |
| 5.15.0  | 121       | 8%      |
| 5.10.14 | 74        | 4.89%   |
| 5.3.0   | 68        | 4.49%   |
| 5.13.0  | 67        | 4.43%   |
| 5.11.0  | 63        | 4.16%   |
| 5.8.0   | 58        | 3.83%   |
| 4.15.0  | 58        | 3.83%   |
| 5.14.7  | 56        | 3.7%    |
| 5.0.0   | 44        | 2.91%   |
| 5.16.7  | 40        | 2.64%   |
| 6.2.0   | 39        | 2.58%   |
| 5.19.0  | 38        | 2.51%   |
| 5.10.0  | 28        | 1.85%   |
| 4.18.0  | 26        | 1.72%   |
| 6.1.1   | 23        | 1.52%   |
| 6.2.6   | 20        | 1.32%   |
| 6.1.0   | 20        | 1.32%   |
| 6.5.0   | 13        | 0.86%   |
| 6.5.6   | 10        | 0.66%   |
| 4.19.0  | 8         | 0.53%   |
| 6.4.11  | 7         | 0.46%   |
| 6.6.2   | 6         | 0.4%    |
| 6.2.9   | 6         | 0.4%    |
| 6.0.0   | 6         | 0.4%    |
| 6.2.15  | 5         | 0.33%   |
| 5.15.12 | 5         | 0.33%   |
| 5.14.0  | 5         | 0.33%   |
| 4.13.0  | 5         | 0.33%   |
| 6.6.1   | 4         | 0.26%   |
| 6.5.5   | 4         | 0.26%   |
| 6.4.6   | 4         | 0.26%   |
| 6.3.8   | 4         | 0.26%   |
| 5.9.0   | 4         | 0.26%   |
| 5.6.16  | 4         | 0.26%   |
| 5.3.18  | 4         | 0.26%   |
| 5.17.0  | 4         | 0.26%   |
| 5.16.11 | 4         | 0.26%   |
| 5.11.12 | 4         | 0.26%   |
| 5.10.74 | 4         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 211       | 14.06%  |
| 5.15    | 152       | 10.13%  |
| 5.10    | 129       | 8.59%   |
| 5.11    | 84        | 5.6%    |
| 6.2     | 81        | 5.4%    |
| 5.13    | 80        | 5.33%   |
| 5.3     | 76        | 5.06%   |
| 5.8     | 74        | 4.93%   |
| 5.14    | 74        | 4.93%   |
| 6.1     | 68        | 4.53%   |
| 4.15    | 60        | 4%      |
| 5.16    | 57        | 3.8%    |
| 5.19    | 53        | 3.53%   |
| 5.0     | 46        | 3.06%   |
| 6.5     | 37        | 2.47%   |
| 4.18    | 28        | 1.87%   |
| 6.4     | 26        | 1.73%   |
| 6.0     | 23        | 1.53%   |
| 5.17    | 20        | 1.33%   |
| 6.6     | 17        | 1.13%   |
| 5.9     | 15        | 1%      |
| 5.6     | 15        | 1%      |
| 5.18    | 15        | 1%      |
| 4.19    | 12        | 0.8%    |
| 6.3     | 7         | 0.47%   |
| 5.12    | 7         | 0.47%   |
| 4.9     | 7         | 0.47%   |
| 5.7     | 6         | 0.4%    |
| 5.5     | 6         | 0.4%    |
| 4.13    | 5         | 0.33%   |
| 4.4     | 4         | 0.27%   |
| 5.1     | 2         | 0.13%   |
| 4.8     | 1         | 0.07%   |
| 4.17    | 1         | 0.07%   |
| 4.14    | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1326      | 97%     |
| i686   | 41        | 3%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 567       | 40.07%  |
| KDE5            | 362       | 25.58%  |
| Unknown         | 141       | 9.96%   |
| XFCE            | 112       | 7.92%   |
| X-Cinnamon      | 73        | 5.16%   |
| MATE            | 38        | 2.69%   |
| KDE             | 23        | 1.63%   |
| Cinnamon        | 19        | 1.34%   |
| LXQt            | 16        | 1.13%   |
| Pantheon        | 9         | 0.64%   |
| LXDE            | 7         | 0.49%   |
| Unity           | 6         | 0.42%   |
| KDE4            | 6         | 0.42%   |
| GNOME Flashback | 6         | 0.42%   |
| i3              | 5         | 0.35%   |
| Budgie          | 5         | 0.35%   |
| awesome         | 4         | 0.28%   |
| sway            | 2         | 0.14%   |
| qtile           | 2         | 0.14%   |
| openbox         | 2         | 0.14%   |
| Hyprland        | 2         | 0.14%   |
| XSession        | 1         | 0.07%   |
| xinitrc         | 1         | 0.07%   |
| xinit-compat    | 1         | 0.07%   |
| GNUstep         | 1         | 0.07%   |
| Enlightenment   | 1         | 0.07%   |
| DWM             | 1         | 0.07%   |
| Deepin          | 1         | 0.07%   |
| custom          | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1041      | 74.04%  |
| Wayland | 267       | 18.99%  |
| Unknown | 83        | 5.9%    |
| Tty     | 15        | 1.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 580       | 40.99%  |
| SDDM    | 345       | 24.38%  |
| GDM3    | 155       | 10.95%  |
| GDM     | 145       | 10.25%  |
| LightDM | 133       | 9.4%    |
| TDM     | 39        | 2.76%   |
| KDM     | 5         | 0.35%   |
| XDM     | 4         | 0.28%   |
| SLiM    | 4         | 0.28%   |
| LXDM    | 3         | 0.21%   |
| Ly      | 1         | 0.07%   |
| GREETD  | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| cs_CZ   | 734       | 52.69%  |
| en_US   | 429       | 30.8%   |
| Unknown | 124       | 8.9%    |
| en_GB   | 29        | 2.08%   |
| C       | 27        | 1.94%   |
| ru_RU   | 18        | 1.29%   |
| sk_SK   | 5         | 0.36%   |
| pl_PL   | 4         | 0.29%   |
| uk_UA   | 3         | 0.22%   |
| POSIX   | 3         | 0.22%   |
| de_DE   | 3         | 0.22%   |
| it_IT   | 2         | 0.14%   |
| fr_FR   | 2         | 0.14%   |
| tr_TR   | 1         | 0.07%   |
| ro_RO   | 1         | 0.07%   |
| pt_PT   | 1         | 0.07%   |
| es_ES   | 1         | 0.07%   |
| en_NG   | 1         | 0.07%   |
| en_CA   | 1         | 0.07%   |
| en_150  | 1         | 0.07%   |
| el_GR   | 1         | 0.07%   |
| de_CH   | 1         | 0.07%   |
| bg_BG   | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 701       | 50.07%  |
| BIOS | 699       | 49.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 906       | 64.9%   |
| Overlay  | 231       | 16.55%  |
| Btrfs    | 145       | 10.39%  |
| Tmpfs    | 36        | 2.58%   |
| Unknown  | 33        | 2.36%   |
| Xfs      | 27        | 1.93%   |
| Zfs      | 9         | 0.64%   |
| Ext3     | 3         | 0.21%   |
| Ext2     | 2         | 0.14%   |
| Aufs     | 2         | 0.14%   |
| Reiserfs | 1         | 0.07%   |
| F2fs     | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 608       | 43.74%  |
| GPT     | 544       | 39.14%  |
| MBR     | 238       | 17.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1251      | 90.78%  |
| Yes       | 127       | 9.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 903       | 64.78%  |
| Yes       | 491       | 35.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 359       | 26.26%  |
| ASUSTek Computer               | 267       | 19.53%  |
| Hewlett-Packard                | 252       | 18.43%  |
| Dell                           | 194       | 14.19%  |
| Acer                           | 128       | 9.36%   |
| UMAX                           | 22        | 1.61%   |
| MSI                            | 18        | 1.32%   |
| Toshiba                        | 17        | 1.24%   |
| Sony                           | 17        | 1.24%   |
| Fujitsu                        | 11        | 0.8%    |
| Valve                          | 8         | 0.59%   |
| Apple                          | 8         | 0.59%   |
| HUAWEI                         | 7         | 0.51%   |
| Unknown                        | 6         | 0.44%   |
| TUXEDO                         | 5         | 0.37%   |
| Google                         | 5         | 0.37%   |
| Timi                           | 4         | 0.29%   |
| Packard Bell                   | 4         | 0.29%   |
| Fujitsu Siemens                | 4         | 0.29%   |
| Notebook                       | 3         | 0.22%   |
| Insyde                         | 2         | 0.15%   |
| Dynabook                       | 2         | 0.15%   |
| Chuwi                          | 2         | 0.15%   |
| Alienware                      | 2         | 0.15%   |
| Standard                       | 1         | 0.07%   |
| SmbiosType1_SystemManufacturer | 1         | 0.07%   |
| SLIMBOOK                       | 1         | 0.07%   |
| Samsung Electronics            | 1         | 0.07%   |
| Purism                         | 1         | 0.07%   |
| Prestigio                      | 1         | 0.07%   |
| Panasonic                      | 1         | 0.07%   |
| Medion                         | 1         | 0.07%   |
| Jumper                         | 1         | 0.07%   |
| Intel                          | 1         | 0.07%   |
| INET                           | 1         | 0.07%   |
| In-Sing                        | 1         | 0.07%   |
| IBM                            | 1         | 0.07%   |
| Gigabyte Technology            | 1         | 0.07%   |
| EUROCOM                        | 1         | 0.07%   |
| eMachines                      | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ASUS UX31E                            | 127       | 9.29%   |
| Unknown                               | 10        | 0.73%   |
| Valve Jupiter                         | 8         | 0.59%   |
| HP ProBook 455 G7                     | 7         | 0.51%   |
| Dell Latitude E6420                   | 7         | 0.51%   |
| HP ProBook 4540s                      | 6         | 0.44%   |
| HP EliteBook 845 G8 Notebook PC       | 6         | 0.44%   |
| Lenovo ThinkPad E14 20RA001LMC        | 5         | 0.37%   |
| Lenovo IdeaPad S145-15AST 81N3        | 5         | 0.37%   |
| HP ProBook 4530s                      | 5         | 0.37%   |
| HP ProBook 450 G5                     | 5         | 0.37%   |
| HP Pavilion dv7                       | 5         | 0.37%   |
| HP EliteBook 840 G6                   | 5         | 0.37%   |
| HP EliteBook 840 G3                   | 5         | 0.37%   |
| Dell XPS 15 9560                      | 5         | 0.37%   |
| Dell Latitude E6400                   | 5         | 0.37%   |
| Dell Latitude 5401                    | 5         | 0.37%   |
| HP Notebook                           | 4         | 0.29%   |
| HP 250 G6 Notebook PC                 | 4         | 0.29%   |
| Dell XPS 15 7590                      | 4         | 0.29%   |
| Dell Precision M6500                  | 4         | 0.29%   |
| Dell Latitude E7440                   | 4         | 0.29%   |
| Dell Latitude E5470                   | 4         | 0.29%   |
| Dell Latitude 5480                    | 4         | 0.29%   |
| Acer Extensa 5620                     | 4         | 0.29%   |
| UMAX VisionBook-N12R                  | 3         | 0.22%   |
| UMAX VisionBook 15Wg Plus             | 3         | 0.22%   |
| Lenovo Z50-75 80EC                    | 3         | 0.22%   |
| Lenovo ThinkPad T14 Gen 1 20UES2WA00  | 3         | 0.22%   |
| Lenovo Legion 5 15ACH6H 82JU          | 3         | 0.22%   |
| Lenovo IdeaPad Z580                   | 3         | 0.22%   |
| Lenovo IdeaPad S130-11IGM 81J1        | 3         | 0.22%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL | 3         | 0.22%   |
| Lenovo IdeaPad 5 14ARE05 81YM         | 3         | 0.22%   |
| Lenovo IdeaPad 5 14ALC05 82LM         | 3         | 0.22%   |
| Lenovo IdeaPad 5 14ABA7 82SE          | 3         | 0.22%   |
| Lenovo IdeaPad 3 15ARE05 81W4         | 3         | 0.22%   |
| HP Victus by Laptop 16-e0xxx          | 3         | 0.22%   |
| HP ProBook 4510s                      | 3         | 0.22%   |
| HP Pavilion dv6                       | 3         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 189       | 13.83%  |
| ASUS UX31E            | 127       | 9.29%   |
| Dell Latitude         | 100       | 7.32%   |
| Lenovo IdeaPad        | 79        | 5.78%   |
| Acer Aspire           | 77        | 5.63%   |
| HP EliteBook          | 68        | 4.97%   |
| HP ProBook            | 64        | 4.68%   |
| Dell XPS              | 28        | 2.05%   |
| HP Pavilion           | 27        | 1.98%   |
| Dell Inspiron         | 23        | 1.68%   |
| Dell Precision        | 21        | 1.54%   |
| HP ZBook              | 18        | 1.32%   |
| Lenovo Yoga           | 17        | 1.24%   |
| ASUS VivoBook         | 17        | 1.24%   |
| Toshiba Satellite     | 16        | 1.17%   |
| Lenovo Legion         | 16        | 1.17%   |
| HP Laptop             | 16        | 1.17%   |
| HP Compaq             | 16        | 1.17%   |
| ASUS ZenBook          | 15        | 1.1%    |
| UMAX VisionBook       | 14        | 1.02%   |
| Acer Extensa          | 14        | 1.02%   |
| Acer TravelMate       | 12        | 0.88%   |
| Acer Swift            | 12        | 0.88%   |
| HP 250                | 11        | 0.8%    |
| Fujitsu LIFEBOOK      | 11        | 0.8%    |
| Lenovo ThinkBook      | 10        | 0.73%   |
| Unknown               | 10        | 0.73%   |
| Dell Vostro           | 9         | 0.66%   |
| ASUS ASUS             | 9         | 0.66%   |
| Valve Jupiter         | 8         | 0.59%   |
| ASUS ROG              | 8         | 0.59%   |
| Acer Nitro            | 6         | 0.44%   |
| Packard Bell EasyNote | 4         | 0.29%   |
| HP Victus             | 4         | 0.29%   |
| HP Notebook           | 4         | 0.29%   |
| Dell G5               | 4         | 0.29%   |
| UMAX VisionBook-N12R  | 3         | 0.22%   |
| Lenovo Z50-75         | 3         | 0.22%   |
| Lenovo G780           | 3         | 0.22%   |
| HP OMEN               | 3         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 208       | 15.22%  |
| 2020    | 128       | 9.36%   |
| 2021    | 123       | 9%      |
| 2019    | 115       | 8.41%   |
| 2018    | 95        | 6.95%   |
| 2012    | 88        | 6.44%   |
| 2014    | 74        | 5.41%   |
| 2017    | 73        | 5.34%   |
| 2013    | 72        | 5.27%   |
| 2015    | 68        | 4.97%   |
| 2016    | 61        | 4.46%   |
| 2008    | 60        | 4.39%   |
| 2022    | 55        | 4.02%   |
| 2010    | 50        | 3.66%   |
| 2007    | 32        | 2.34%   |
| 2009    | 29        | 2.12%   |
| 2023    | 16        | 1.17%   |
| 2006    | 13        | 0.95%   |
| 2005    | 3         | 0.22%   |
| 2004    | 2         | 0.15%   |
| Unknown | 2         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1367      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1209      | 87.17%  |
| Enabled  | 178       | 12.83%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1361      | 99.56%  |
| Yes  | 6         | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 383       | 27.63%  |
| 4.01-8.0    | 294       | 21.21%  |
| 8.01-16.0   | 237       | 17.1%   |
| 16.01-24.0  | 201       | 14.5%   |
| 32.01-64.0  | 121       | 8.73%   |
| 1.01-2.0    | 69        | 4.98%   |
| 2.01-3.0    | 27        | 1.95%   |
| 24.01-32.0  | 24        | 1.73%   |
| 64.01-256.0 | 15        | 1.08%   |
| 0.51-1.0    | 14        | 1.01%   |
| 0.01-0.5    | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 545       | 36.19%  |
| 2.01-3.0   | 325       | 21.58%  |
| 4.01-8.0   | 238       | 15.8%   |
| 3.01-4.0   | 192       | 12.75%  |
| 8.01-16.0  | 86        | 5.71%   |
| 0.51-1.0   | 82        | 5.44%   |
| 0.01-0.5   | 19        | 1.26%   |
| 16.01-24.0 | 15        | 1%      |
| 32.01-64.0 | 2         | 0.13%   |
| 24.01-32.0 | 2         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1093      | 78.18%  |
| 2      | 256       | 18.31%  |
| 3      | 32        | 2.29%   |
| 0      | 14        | 1%      |
| 4      | 2         | 0.14%   |
| 7      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 971       | 70.72%  |
| Yes       | 402       | 29.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1143      | 83.01%  |
| No        | 234       | 16.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1346      | 98.39%  |
| No        | 22        | 1.61%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1013      | 73.25%  |
| No        | 370       | 26.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Czechia | 1367      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Prague               | 583       | 40.91%  |
| Brno                 | 119       | 8.35%   |
| Ostrava              | 44        | 3.09%   |
| Pilsen               | 29        | 2.04%   |
| Olomouc              | 21        | 1.47%   |
| Pardubice            | 18        | 1.26%   |
| Liberec              | 17        | 1.19%   |
| Hradec Králové     | 14        | 0.98%   |
| České Budějovice  | 14        | 0.98%   |
| Brdo                 | 13        | 0.91%   |
| Chomutov             | 11        | 0.77%   |
| Most                 | 10        | 0.7%    |
| Havířov            | 10        | 0.7%    |
| Jihlava              | 8         | 0.56%   |
| Znojmo               | 7         | 0.49%   |
| Zlín                | 7         | 0.49%   |
| Karlovy Vary         | 7         | 0.49%   |
| Ústí nad Labem     | 6         | 0.42%   |
| Tábor               | 6         | 0.42%   |
| Roznov pod Radhostem | 6         | 0.42%   |
| Příbram            | 6         | 0.42%   |
| Opava                | 6         | 0.42%   |
| Kladno               | 6         | 0.42%   |
| Přerov              | 5         | 0.35%   |
| Mariánské Lázně  | 5         | 0.35%   |
| Jedovnice            | 5         | 0.35%   |
| Ceska Kamenice       | 5         | 0.35%   |
| Třebíč            | 4         | 0.28%   |
| Teplice              | 4         | 0.28%   |
| Slavkov u Brna       | 4         | 0.28%   |
| Šlapanice           | 4         | 0.28%   |
| Prelouc              | 4         | 0.28%   |
| Pelhrimov            | 4         | 0.28%   |
| Mladá Boleslav      | 4         | 0.28%   |
| Milovice             | 4         | 0.28%   |
| Frýdek-Místek      | 4         | 0.28%   |
| Česká Lípa        | 4         | 0.28%   |
| Celakovice           | 4         | 0.28%   |
| Vitkov               | 3         | 0.21%   |
| Uvaly                | 3         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 290       | 380    | 17.69%  |
| SanDisk                        | 209       | 223    | 12.75%  |
| WDC                            | 157       | 187    | 9.58%   |
| Seagate                        | 154       | 207    | 9.4%    |
| Toshiba                        | 118       | 141    | 7.2%    |
| Kingston                       | 89        | 96     | 5.43%   |
| Unknown                        | 83        | 113    | 5.06%   |
| SK hynix                       | 77        | 93     | 4.7%    |
| Micron Technology              | 55        | 70     | 3.36%   |
| Hitachi                        | 52        | 61     | 3.17%   |
| Intel                          | 49        | 57     | 2.99%   |
| HGST                           | 44        | 55     | 2.68%   |
| A-DATA Technology              | 28        | 31     | 1.71%   |
| Patriot                        | 25        | 30     | 1.53%   |
| Crucial                        | 25        | 35     | 1.53%   |
| KIOXIA                         | 22        | 35     | 1.34%   |
| Unknown                        | 12        | 13     | 0.73%   |
| Transcend                      | 11        | 12     | 0.67%   |
| Apacer                         | 11        | 16     | 0.67%   |
| LITEONIT                       | 9         | 11     | 0.55%   |
| Fujitsu                        | 7         | 7      | 0.43%   |
| China                          | 7         | 8      | 0.43%   |
| Apple                          | 7         | 8      | 0.43%   |
| Verbatim                       | 6         | 6      | 0.37%   |
| Phison                         | 6         | 13     | 0.37%   |
| LITEON                         | 6         | 6      | 0.37%   |
| Silicon Motion                 | 5         | 5      | 0.31%   |
| Phison Electronics             | 5         | 5      | 0.31%   |
| UMAX                           | 4         | 4      | 0.24%   |
| Micron/Crucial Technology      | 4         | 4      | 0.24%   |
| JMicron Technology             | 4         | 4      | 0.24%   |
| Gigabyte Technology            | 4         | 9      | 0.24%   |
| ASMedia                        | 4         | 6      | 0.24%   |
| Team                           | 3         | 3      | 0.18%   |
| Solid State Storage Technology | 3         | 3      | 0.18%   |
| Lenovo                         | 3         | 4      | 0.18%   |
| Kingston Technology Company    | 3         | 3      | 0.18%   |
| GOODRAM                        | 3         | 4      | 0.18%   |
| UMIS                           | 2         | 2      | 0.12%   |
| Realtek Semiconductor          | 2         | 3      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB                              | 126       | 7.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 20        | 1.17%   |
| Unknown MMC Card  32GB                              | 17        | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB                      | 17        | 0.99%   |
| Samsung NVMe SSD Drive 512GB                        | 17        | 0.99%   |
| HGST HTS721010A9E630 1TB                            | 16        | 0.94%   |
| Samsung SSD 860 EVO 500GB                           | 13        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 13        | 0.76%   |
| Kingston SA400S37480G 480GB SSD                     | 12        | 0.7%    |
| Unknown                                             | 12        | 0.7%    |
| Unknown MMC Card  64GB                              | 11        | 0.64%   |
| SanDisk NVMe SSD Drive 512GB                        | 11        | 0.64%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                      | 11        | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 10        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 10        | 0.59%   |
| Kingston SA400S37240G 240GB SSD                     | 10        | 0.59%   |
| Unknown MMC Card  16GB                              | 9         | 0.53%   |
| Toshiba MQ01ABD100 1TB                              | 9         | 0.53%   |
| HGST HTS725050A7E630 500GB                          | 9         | 0.53%   |
| Toshiba NVMe SSD Drive 256GB                        | 8         | 0.47%   |
| Toshiba MQ01ABF050 500GB                            | 8         | 0.47%   |
| SK hynix NVMe SSD Drive 512GB                       | 8         | 0.47%   |
| Seagate ST500LT012-1DG142 500GB                     | 8         | 0.47%   |
| Samsung SSD 850 EVO 250GB                           | 8         | 0.47%   |
| Toshiba MQ04ABF100 1TB                              | 7         | 0.41%   |
| Seagate ST9500420AS 500GB                           | 7         | 0.41%   |
| SanDisk NVMe SSD Drive 1024GB                       | 7         | 0.41%   |
| Patriot Burst 480GB SSD                             | 7         | 0.41%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 7         | 0.41%   |
| Kingston SA400S37120G 120GB SSD                     | 7         | 0.41%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 6         | 0.35%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 6         | 0.35%   |
| Unknown MMC Card  128GB                             | 6         | 0.35%   |
| Toshiba NVMe SSD Drive 512GB                        | 6         | 0.35%   |
| Seagate ST500LM000-1EJ162 500GB                     | 6         | 0.35%   |
| Seagate ST2000LM007-1R8174 2TB                      | 6         | 0.35%   |
| SanDisk DF4032  32GB                                | 6         | 0.35%   |
| Samsung SSD 980 1TB                                 | 6         | 0.35%   |
| Samsung SSD 970 EVO 1TB                             | 6         | 0.35%   |
| Samsung SSD 860 EVO 250GB                           | 6         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 152       | 205    | 35.85%  |
| WDC                 | 92        | 108    | 21.7%   |
| Toshiba             | 68        | 76     | 16.04%  |
| Hitachi             | 52        | 61     | 12.26%  |
| HGST                | 44        | 55     | 10.38%  |
| Fujitsu             | 7         | 7      | 1.65%   |
| Samsung Electronics | 2         | 2      | 0.47%   |
| USB3.0              | 1         | 1      | 0.24%   |
| Unknown             | 1         | 1      | 0.24%   |
| TO Exter            | 1         | 2      | 0.24%   |
| StoreJet            | 1         | 1      | 0.24%   |
| SABRENT             | 1         | 1      | 0.24%   |
| IBM/Hitachi         | 1         | 1      | 0.24%   |
| Apple               | 1         | 2      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 160       | 164    | 27.35%  |
| Samsung Electronics | 118       | 143    | 20.17%  |
| Kingston            | 65        | 71     | 11.11%  |
| WDC                 | 29        | 40     | 4.96%   |
| Patriot             | 25        | 30     | 4.27%   |
| A-DATA Technology   | 25        | 28     | 4.27%   |
| Crucial             | 22        | 32     | 3.76%   |
| Intel               | 19        | 21     | 3.25%   |
| Micron Technology   | 16        | 21     | 2.74%   |
| SK hynix            | 13        | 14     | 2.22%   |
| Transcend           | 11        | 12     | 1.88%   |
| Toshiba             | 11        | 13     | 1.88%   |
| Apacer              | 11        | 16     | 1.88%   |
| LITEONIT            | 9         | 11     | 1.54%   |
| China               | 7         | 8      | 1.2%    |
| Verbatim            | 6         | 6      | 1.03%   |
| Apple               | 5         | 5      | 0.85%   |
| UMAX                | 4         | 4      | 0.68%   |
| LITEON              | 4         | 4      | 0.68%   |
| Gigabyte Technology | 3         | 7      | 0.51%   |
| ASMedia             | 3         | 4      | 0.51%   |
| Team                | 2         | 2      | 0.34%   |
| JMicron Technology  | 2         | 2      | 0.34%   |
| GOODRAM             | 2         | 3      | 0.34%   |
| ASMT                | 2         | 2      | 0.34%   |
| UMIS                | 1         | 1      | 0.17%   |
| ShanDianZhe         | 1         | 1      | 0.17%   |
| Seagate             | 1         | 1      | 0.17%   |
| OCZ                 | 1         | 4      | 0.17%   |
| Netac               | 1         | 1      | 0.17%   |
| Mushkin             | 1         | 1      | 0.17%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.17%   |
| HPE                 | 1         | 1      | 0.17%   |
| Hewlett-Packard     | 1         | 1      | 0.17%   |
| CT500MX5            | 1         | 1      | 0.17%   |
| ADATA SU            | 1         | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 562       | 677    | 35.66%  |
| NVMe    | 493       | 668    | 31.28%  |
| HDD     | 411       | 523    | 26.08%  |
| MMC     | 100       | 131    | 6.35%   |
| Unknown | 10        | 13     | 0.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 882       | 1156   | 57.99%  |
| NVMe | 492       | 666    | 32.35%  |
| MMC  | 100       | 131    | 6.57%   |
| SAS  | 47        | 59     | 3.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 702       | 862    | 73.28%  |
| 0.51-1.0   | 225       | 293    | 23.49%  |
| 1.01-2.0   | 27        | 39     | 2.82%   |
| 10.01-20.0 | 3         | 4      | 0.31%   |
| 3.01-4.0   | 1         | 2      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 343       | 24.07%  |
| 251-500        | 335       | 23.51%  |
| 1-20           | 244       | 17.12%  |
| 501-1000       | 193       | 13.54%  |
| 51-100         | 94        | 6.6%    |
| 1001-2000      | 73        | 5.12%   |
| 21-50          | 54        | 3.79%   |
| Unknown        | 50        | 3.51%   |
| More than 3000 | 25        | 1.75%   |
| 2001-3000      | 14        | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 666       | 44.94%  |
| 21-50          | 204       | 13.77%  |
| 101-250        | 189       | 12.75%  |
| 51-100         | 156       | 10.53%  |
| 251-500        | 128       | 8.64%   |
| 501-1000       | 53        | 3.58%   |
| Unknown        | 50        | 3.37%   |
| 1001-2000      | 24        | 1.62%   |
| More than 3000 | 7         | 0.47%   |
| 2001-3000      | 5         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                | 126       | 127    | 61.46%  |
| HGST HTS725050A7E630 500GB            | 4         | 5      | 1.95%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 3         | 4      | 1.46%   |
| Toshiba MQ01ABD075 752GB              | 2         | 2      | 0.98%   |
| Toshiba MK1234GSX 120GB               | 2         | 2      | 0.98%   |
| Seagate ST9500420AS 500GB             | 2         | 3      | 0.98%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 2      | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 0.98%   |
| Hitachi HTS541610J9SA00 100GB         | 2         | 2      | 0.98%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.98%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.49%   |
| WDC WD7500BPVT-22HXZT3 752GB          | 1         | 1      | 0.49%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 0.49%   |
| WDC WD6400BPVT-60HXZT1 640GB          | 1         | 1      | 0.49%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 0.49%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 0.49%   |
| Toshiba MK8037GSX 80GB                | 1         | 1      | 0.49%   |
| Toshiba MK7559GSXP 752GB              | 1         | 1      | 0.49%   |
| Toshiba MK6465GSXN 640GB              | 1         | 1      | 0.49%   |
| Toshiba MK5056GSY 500GB               | 1         | 1      | 0.49%   |
| Toshiba MK2561GSYN 250GB              | 1         | 1      | 0.49%   |
| Toshiba MK2552GSX 250GB               | 1         | 1      | 0.49%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 0.49%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD | 1         | 1      | 0.49%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 0.49%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 0.49%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 0.49%   |
| Seagate ST9500420ASG 500GB            | 1         | 1      | 0.49%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 0.49%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 0.49%   |
| Seagate ST9250410ASG 250GB            | 1         | 1      | 0.49%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 0.49%   |
| Seagate ST9200420ASG 200GB            | 1         | 1      | 0.49%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 1      | 0.49%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 0.49%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 1      | 0.49%   |
| SanDisk SD8SBAT-032G-1006 32GB SSD    | 1         | 1      | 0.49%   |
| SanDisk SD7SB3Q256G1002 256GB SSD     | 1         | 1      | 0.49%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 0.49%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 128       | 129    | 62.44%  |
| Seagate             | 17        | 18     | 8.29%   |
| Hitachi             | 13        | 13     | 6.34%   |
| Toshiba             | 11        | 11     | 5.37%   |
| HGST                | 8         | 9      | 3.9%    |
| Samsung Electronics | 7         | 8      | 3.41%   |
| SK hynix            | 6         | 7      | 2.93%   |
| WDC                 | 5         | 5      | 2.44%   |
| Intel               | 2         | 2      | 0.98%   |
| A-DATA Technology   | 2         | 3      | 0.98%   |
| Micron Technology   | 1         | 1      | 0.49%   |
| LITEONIT            | 1         | 1      | 0.49%   |
| Kingston            | 1         | 1      | 0.49%   |
| IBM/Hitachi         | 1         | 1      | 0.49%   |
| Fujitsu             | 1         | 1      | 0.49%   |
| Crucial             | 1         | 1      | 0.49%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 17        | 18     | 30.91%  |
| Hitachi     | 13        | 13     | 23.64%  |
| Toshiba     | 11        | 11     | 20%     |
| HGST        | 8         | 9      | 14.55%  |
| WDC         | 4         | 4      | 7.27%   |
| IBM/Hitachi | 1         | 1      | 1.82%   |
| Fujitsu     | 1         | 1      | 1.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 143       | 145    | 70.1%   |
| HDD  | 54        | 57     | 26.47%  |
| NVMe | 7         | 9      | 3.43%   |

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
| Detected | 727       | 1153   | 50.59%  |
| Works    | 507       | 648    | 35.28%  |
| Malfunc  | 203       | 211    | 14.13%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 939       | 58.5%   |
| Samsung Electronics              | 180       | 11.21%  |
| AMD                              | 152       | 9.47%   |
| SanDisk                          | 77        | 4.8%    |
| SK hynix                         | 61        | 3.8%    |
| Micron Technology                | 39        | 2.43%   |
| Toshiba America Info Systems     | 38        | 2.37%   |
| Kingston Technology Company      | 27        | 1.68%   |
| KIOXIA                           | 25        | 1.56%   |
| Phison Electronics               | 15        | 0.93%   |
| Silicon Motion                   | 7         | 0.44%   |
| Micron/Crucial Technology        | 7         | 0.44%   |
| Union Memory (Shenzhen)          | 5         | 0.31%   |
| ADATA Technology                 | 5         | 0.31%   |
| Lite-On Technology               | 4         | 0.25%   |
| Solid State Storage Technology   | 3         | 0.19%   |
| Silicon Integrated Systems [SiS] | 3         | 0.19%   |
| Nvidia                           | 3         | 0.19%   |
| Lenovo                           | 3         | 0.19%   |
| Realtek Semiconductor            | 2         | 0.12%   |
| JMicron Technology               | 2         | 0.12%   |
| ASMedia Technology               | 2         | 0.12%   |
| VIA Technologies                 | 1         | 0.06%   |
| O2 Micro                         | 1         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.06%   |
| Marvell Technology Group         | 1         | 0.06%   |
| Biwin Storage Technology         | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 192       | 11.16%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 127       | 7.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 86        | 5%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 80        | 4.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 74        | 4.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 63        | 3.66%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 56        | 3.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 50        | 2.91%   |
| Intel Volume Management Device NVMe RAID Controller                              | 46        | 2.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 39        | 2.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 38        | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 35        | 2.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 32        | 1.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 28        | 1.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 28        | 1.63%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 27        | 1.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 27        | 1.57%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 24        | 1.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 24        | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 23        | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 22        | 1.28%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 20        | 1.16%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 18        | 1.05%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 16        | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 16        | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 16        | 0.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 15        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                            | 15        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 13        | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 13        | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 12        | 0.7%    |
| Intel SSD 660P Series                                                            | 11        | 0.64%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 11        | 0.64%   |
| SK hynix BC511 NVMe SSD                                                          | 10        | 0.58%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 10        | 0.58%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 10        | 0.58%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 10        | 0.58%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 9         | 0.52%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 9         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 949       | 57.58%  |
| NVMe | 495       | 30.04%  |
| RAID | 115       | 6.98%   |
| IDE  | 89        | 5.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1112      | 81.35%  |
| AMD    | 255       | 18.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 127       | 9.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 21        | 1.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 20        | 1.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 1.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 16        | 1.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 15        | 1.1%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 15        | 1.1%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 15        | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 1.02%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 14        | 1.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 0.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 13        | 0.95%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 13        | 0.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 0.95%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 0.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 12        | 0.88%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 12        | 0.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 11        | 0.8%    |
| Intel Core i7-10850H CPU @ 2.70GHz            | 11        | 0.8%    |
| AMD Ryzen 5 5600H with Radeon Graphics        | 11        | 0.8%    |
| Intel Celeron N4100 CPU @ 1.10GHz             | 10        | 0.73%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 0.73%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 9         | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 9         | 0.66%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.66%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.66%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 0.66%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.66%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.58%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 8         | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 8         | 0.58%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 8         | 0.58%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 8         | 0.58%   |
| AMD Custom APU 0405                           | 8         | 0.58%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 7         | 0.51%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 7         | 0.51%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 7         | 0.51%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 7         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 403       | 29.46%  |
| Intel Core i5           | 267       | 19.52%  |
| Other                   | 114       | 8.33%   |
| Intel Celeron           | 86        | 6.29%   |
| Intel Core 2 Duo        | 78        | 5.7%    |
| Intel Core i3           | 70        | 5.12%   |
| AMD Ryzen 5             | 65        | 4.75%   |
| AMD Ryzen 7             | 53        | 3.87%   |
| Intel Pentium           | 34        | 2.49%   |
| AMD Ryzen 7 PRO         | 26        | 1.9%    |
| Intel Atom              | 25        | 1.83%   |
| AMD A6                  | 13        | 0.95%   |
| AMD A4                  | 13        | 0.95%   |
| AMD Ryzen 5 PRO         | 10        | 0.73%   |
| AMD Ryzen 3             | 9         | 0.66%   |
| AMD A8                  | 8         | 0.58%   |
| Intel Celeron M         | 7         | 0.51%   |
| Intel Pentium Dual-Core | 6         | 0.44%   |
| Intel Core 2            | 6         | 0.44%   |
| AMD E1                  | 6         | 0.44%   |
| Intel Pentium Silver    | 5         | 0.37%   |
| Intel Genuine           | 5         | 0.37%   |
| Intel Celeron Dual-Core | 5         | 0.37%   |
| Intel Pentium M         | 4         | 0.29%   |
| Intel Pentium Dual      | 4         | 0.29%   |
| AMD Turion II           | 4         | 0.29%   |
| AMD Ryzen 9             | 4         | 0.29%   |
| AMD E                   | 4         | 0.29%   |
| Intel Xeon              | 3         | 0.22%   |
| Intel Core i9           | 3         | 0.22%   |
| AMD Turion 64 X2 Mobile | 3         | 0.22%   |
| AMD Mobile Sempron      | 3         | 0.22%   |
| AMD FX                  | 3         | 0.22%   |
| AMD E2                  | 3         | 0.22%   |
| AMD A10                 | 3         | 0.22%   |
| AMD Athlon X2           | 2         | 0.15%   |
| AMD Athlon II Dual-Core | 2         | 0.15%   |
| AMD A12                 | 2         | 0.15%   |
| Intel Core m5           | 1         | 0.07%   |
| Intel Core Duo          | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 696       | 50.88%  |
| 4       | 396       | 28.95%  |
| 6       | 117       | 8.55%   |
| 8       | 90        | 6.58%   |
| 1       | 33        | 2.41%   |
| 14      | 11        | 0.8%    |
| 12      | 11        | 0.8%    |
| 10      | 10        | 0.73%   |
| 16      | 2         | 0.15%   |
| 24      | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1367      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1010      | 73.83%  |
| 1       | 357       | 26.1%   |
| Unknown | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1333      | 97.23%  |
| 32-bit         | 20        | 1.46%   |
| Unknown        | 17        | 1.24%   |
| 64-bit         | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 355       | 25.09%  |
| 0x206a7    | 183       | 12.93%  |
| 0x306a9    | 50        | 3.53%   |
| 0x806ec    | 42        | 2.97%   |
| 0x806ea    | 41        | 2.9%    |
| 0x1067a    | 39        | 2.76%   |
| 0x406e3    | 37        | 2.61%   |
| 0x806c1    | 34        | 2.4%    |
| 0x40651    | 33        | 2.33%   |
| 0x0a50000c | 31        | 2.19%   |
| 0x906ea    | 30        | 2.12%   |
| 0x08600106 | 29        | 2.05%   |
| 0x306c3    | 28        | 1.98%   |
| 0x806e9    | 26        | 1.84%   |
| 0x306d4    | 25        | 1.77%   |
| 0x6fd      | 21        | 1.48%   |
| 0x30678    | 19        | 1.34%   |
| 0xa0652    | 16        | 1.13%   |
| 0x20655    | 16        | 1.13%   |
| 0x506e3    | 15        | 1.06%   |
| 0x706a1    | 14        | 0.99%   |
| 0x08608103 | 14        | 0.99%   |
| 0x906e9    | 13        | 0.92%   |
| 0x10676    | 13        | 0.92%   |
| 0x08108102 | 13        | 0.92%   |
| 0x706e5    | 12        | 0.85%   |
| 0x406c3    | 12        | 0.85%   |
| 0x06006705 | 12        | 0.85%   |
| 0x406c4    | 11        | 0.78%   |
| 0x906ed    | 10        | 0.71%   |
| 0x906a3    | 10        | 0.71%   |
| 0x08600104 | 10        | 0.71%   |
| 0x506c9    | 8         | 0.57%   |
| 0x08600103 | 8         | 0.57%   |
| 0x07030105 | 8         | 0.57%   |
| 0x806eb    | 7         | 0.49%   |
| 0x806d1    | 7         | 0.49%   |
| 0x6e8      | 7         | 0.49%   |
| 0x20652    | 7         | 0.49%   |
| 0x106e5    | 7         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 228       | 16.68%  |
| SandyBridge      | 212       | 15.51%  |
| Haswell          | 87        | 6.36%   |
| IvyBridge        | 75        | 5.49%   |
| Skylake          | 68        | 4.97%   |
| Penryn           | 65        | 4.75%   |
| Zen 2            | 60        | 4.39%   |
| Silvermont       | 54        | 3.95%   |
| Zen 3            | 53        | 3.88%   |
| Unknown          | 50        | 3.66%   |
| TigerLake        | 49        | 3.58%   |
| Core             | 44        | 3.22%   |
| Westmere         | 33        | 2.41%   |
| Broadwell        | 33        | 2.41%   |
| Alderlake Hybrid | 31        | 2.27%   |
| Goldmont plus    | 29        | 2.12%   |
| CometLake        | 23        | 1.68%   |
| Icelake          | 21        | 1.54%   |
| Excavator        | 21        | 1.54%   |
| Zen+             | 20        | 1.46%   |
| P6               | 12        | 0.88%   |
| Bonnell          | 12        | 0.88%   |
| Puma             | 11        | 0.8%    |
| Goldmont         | 11        | 0.8%    |
| Nehalem          | 9         | 0.66%   |
| Bobcat           | 9         | 0.66%   |
| Piledriver       | 8         | 0.59%   |
| K8 Hammer        | 7         | 0.51%   |
| K10              | 7         | 0.51%   |
| Steamroller      | 6         | 0.44%   |
| Jaguar           | 6         | 0.44%   |
| Zen              | 5         | 0.37%   |
| Tremont          | 4         | 0.29%   |
| K8 & K10 hybrid  | 3         | 0.22%   |
| K10 Llano        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1013      | 59.31%  |
| Nvidia                           | 349       | 20.43%  |
| AMD                              | 342       | 20.02%  |
| Silicon Integrated Systems [SiS] | 2         | 0.12%   |
| VIA Technologies                 | 1         | 0.06%   |
| ATI Technologies                 | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 203       | 11.45%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 70        | 3.95%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 59        | 3.33%   |
| Intel UHD Graphics 620                                                                   | 55        | 3.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 2.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 41        | 2.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 41        | 2.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 41        | 2.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 40        | 2.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 37        | 2.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 37        | 2.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 35        | 1.97%   |
| Intel HD Graphics 620                                                                    | 31        | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 1.69%   |
| Intel HD Graphics 5500                                                                   | 29        | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 28        | 1.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 1.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 25        | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 21        | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 21        | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 20        | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 1.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 1.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 20        | 1.13%   |
| AMD Lucienne                                                                             | 20        | 1.13%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 19        | 1.07%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 19        | 1.07%   |
| Intel HD Graphics 630                                                                    | 18        | 1.02%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 18        | 1.02%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 17        | 0.96%   |
| Intel HD Graphics 530                                                                    | 16        | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 0.73%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 13        | 0.73%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 12        | 0.68%   |
| Intel HD Graphics 500                                                                    | 11        | 0.62%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 0.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 10        | 0.56%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 10        | 0.56%   |
| Nvidia TU117M [GeForce MX450]                                                            | 9         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 697       | 50.99%  |
| Intel + Nvidia | 251       | 18.36%  |
| 1 x AMD        | 228       | 16.68%  |
| 1 x Nvidia     | 67        | 4.9%    |
| Intel + AMD    | 58        | 4.24%   |
| AMD + Nvidia   | 30        | 2.19%   |
| 2 x AMD        | 26        | 1.9%    |
| 2 x Intel      | 6         | 0.44%   |
| 1 x SiS        | 2         | 0.15%   |
| Other          | 1         | 0.07%   |
| 1 x VIA        | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1177      | 85.41%  |
| Proprietary | 164       | 11.9%   |
| Unknown     | 37        | 2.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 932       | 66.52%  |
| 0.01-0.5   | 169       | 12.06%  |
| 1.01-2.0   | 154       | 10.99%  |
| 0.51-1.0   | 65        | 4.64%   |
| 3.01-4.0   | 52        | 3.71%   |
| 5.01-6.0   | 18        | 1.28%   |
| 7.01-8.0   | 6         | 0.43%   |
| 2.01-3.0   | 4         | 0.29%   |
| 8.01-16.0  | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 307       | 18.49%  |
| LG Display              | 203       | 12.23%  |
| BOE                     | 168       | 10.12%  |
| Chimei Innolux          | 163       | 9.82%   |
| Samsung Electronics     | 151       | 9.1%    |
| CPT                     | 129       | 7.77%   |
| Dell                    | 70        | 4.22%   |
| Eizo                    | 62        | 3.73%   |
| Sharp                   | 43        | 2.59%   |
| Lenovo                  | 40        | 2.41%   |
| Chi Mei Optoelectronics | 33        | 1.99%   |
| PANDA                   | 31        | 1.87%   |
| Hewlett-Packard         | 31        | 1.87%   |
| Philips                 | 25        | 1.51%   |
| Goldstar                | 21        | 1.27%   |
| BenQ                    | 19        | 1.14%   |
| AOC                     | 18        | 1.08%   |
| LG Philips              | 17        | 1.02%   |
| CSO                     | 13        | 0.78%   |
| Acer                    | 13        | 0.78%   |
| InfoVision              | 11        | 0.66%   |
| Iiyama                  | 9         | 0.54%   |
| Apple                   | 8         | 0.48%   |
| Sony                    | 7         | 0.42%   |
| Ancor Communications    | 7         | 0.42%   |
| Quanta Display          | 6         | 0.36%   |
| Valve                   | 5         | 0.3%    |
| Panasonic               | 5         | 0.3%    |
| HannStar                | 5         | 0.3%    |
| Toshiba                 | 4         | 0.24%   |
| NEC Computers           | 4         | 0.24%   |
| ASUSTek Computer        | 4         | 0.24%   |
| Vestel Elektronik       | 2         | 0.12%   |
| Unknown                 | 2         | 0.12%   |
| OEM                     | 2         | 0.12%   |
| JDI                     | 2         | 0.12%   |
| Hitachi                 | 2         | 0.12%   |
| Fujitsu Siemens         | 2         | 0.12%   |
| DENON                   | 2         | 0.12%   |
| ViewSonic               | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                      | 127       | 7.48%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                         | 57        | 3.36%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 14        | 0.82%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 12        | 0.71%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 12        | 0.71%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 10        | 0.59%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.53%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 8         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 8         | 0.47%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 7         | 0.41%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 7         | 0.41%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 7         | 0.41%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 7         | 0.41%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 7         | 0.41%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch            | 7         | 0.41%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 6         | 0.35%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 6         | 0.35%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch               | 6         | 0.35%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                         | 6         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 6         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 6         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 6         | 0.35%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 6         | 0.35%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 6         | 0.35%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 6         | 0.35%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 6         | 0.35%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 5         | 0.29%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 5         | 0.29%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 5         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 5         | 0.29%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch      | 5         | 0.29%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 5         | 0.29%   |
| Hewlett-Packard Z24n HWP320E 1920x1200 518x324mm 24.1-inch                | 5         | 0.29%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                         | 5         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 5         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO1520 1680x1050 331x207mm 15.4-inch | 5         | 0.29%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                     | 5         | 0.29%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch            | 5         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 659       | 42.63%  |
| 1366x768 (WXGA)    | 277       | 17.92%  |
| 1600x900 (HD+)     | 202       | 13.07%  |
| 3840x2160 (4K)     | 109       | 7.05%   |
| 1280x800 (WXGA)    | 65        | 4.2%    |
| 2560x1440 (QHD)    | 54        | 3.49%   |
| 1920x1200 (WUXGA)  | 44        | 2.85%   |
| 2560x1600          | 19        | 1.23%   |
| 1680x1050 (WSXGA+) | 19        | 1.23%   |
| 1440x900 (WXGA+)   | 18        | 1.16%   |
| 1280x1024 (SXGA)   | 8         | 0.52%   |
| 1024x600           | 8         | 0.52%   |
| 2880x1800          | 6         | 0.39%   |
| 800x1280           | 5         | 0.32%   |
| 1024x768 (XGA)     | 5         | 0.32%   |
| 3840x2400          | 4         | 0.26%   |
| 3440x1440          | 4         | 0.26%   |
| 1360x768           | 4         | 0.26%   |
| 3456x2160          | 3         | 0.19%   |
| 3000x2000          | 3         | 0.19%   |
| 2160x1440          | 3         | 0.19%   |
| 1920x540           | 3         | 0.19%   |
| Unknown            | 3         | 0.19%   |
| 3840x1200          | 2         | 0.13%   |
| 3200x1800 (QHD+)   | 2         | 0.13%   |
| 2880x1620          | 2         | 0.13%   |
| 2160x1350          | 2         | 0.13%   |
| 1400x1050          | 2         | 0.13%   |
| 8320x2160          | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 3840x1080          | 1         | 0.06%   |
| 3200x2000          | 1         | 0.06%   |
| 3072x1920          | 1         | 0.06%   |
| 2560x1080          | 1         | 0.06%   |
| 2288x1287          | 1         | 0.06%   |
| 2256x1504          | 1         | 0.06%   |
| 2240x1400          | 1         | 0.06%   |
| 1920x515           | 1         | 0.06%   |
| 1280x720 (HD)      | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 567       | 34.03%  |
| 13      | 301       | 18.07%  |
| 14      | 196       | 11.76%  |
| 17      | 98        | 5.88%   |
| 24      | 94        | 5.64%   |
| 31      | 72        | 4.32%   |
| 27      | 68        | 4.08%   |
| 23      | 44        | 2.64%   |
| 12      | 32        | 1.92%   |
| 11      | 32        | 1.92%   |
| 21      | 26        | 1.56%   |
| 16      | 24        | 1.44%   |
| Unknown | 14        | 0.84%   |
| 22      | 11        | 0.66%   |
| 10      | 11        | 0.66%   |
| 84      | 8         | 0.48%   |
| 18      | 8         | 0.48%   |
| 20      | 6         | 0.36%   |
| 19      | 6         | 0.36%   |
| 34      | 5         | 0.3%    |
| 33      | 5         | 0.3%    |
| 7       | 5         | 0.3%    |
| 40      | 4         | 0.24%   |
| 32      | 4         | 0.24%   |
| 26      | 4         | 0.24%   |
| 25      | 4         | 0.24%   |
| 54      | 3         | 0.18%   |
| 43      | 3         | 0.18%   |
| 72      | 2         | 0.12%   |
| 49      | 2         | 0.12%   |
| 142     | 1         | 0.06%   |
| 60      | 1         | 0.06%   |
| 52      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 38      | 1         | 0.06%   |
| 29      | 1         | 0.06%   |
| 28      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 864       | 52.65%  |
| 201-300        | 279       | 17%     |
| 501-600        | 187       | 11.4%   |
| 351-400        | 117       | 7.13%   |
| 601-700        | 82        | 5%      |
| 401-500        | 52        | 3.17%   |
| 701-800        | 14        | 0.85%   |
| Unknown        | 14        | 0.85%   |
| 1501-2000      | 10        | 0.61%   |
| 1001-1500      | 10        | 0.61%   |
| 801-900        | 5         | 0.3%    |
| 1-100          | 5         | 0.3%    |
| More than 2000 | 1         | 0.06%   |
| 901-1000       | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1149      | 82.6%   |
| 16/10   | 192       | 13.8%   |
| 3/2     | 11        | 0.79%   |
| Unknown | 10        | 0.72%   |
| 5/4     | 8         | 0.58%   |
| 4/3     | 7         | 0.5%    |
| 21/9    | 5         | 0.36%   |
| 0.67    | 5         | 0.36%   |
| 3.20    | 2         | 0.14%   |
| 3.73    | 1         | 0.07%   |
| 1.00    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 561       | 33.84%  |
| 81-90          | 301       | 18.15%  |
| 71-80          | 193       | 11.64%  |
| 201-250        | 130       | 7.84%   |
| 351-500        | 87        | 5.25%   |
| 121-130        | 79        | 4.76%   |
| 301-350        | 73        | 4.4%    |
| 251-300        | 37        | 2.23%   |
| 61-70          | 32        | 1.93%   |
| 51-60          | 32        | 1.93%   |
| 111-120        | 23        | 1.39%   |
| 151-200        | 18        | 1.09%   |
| More than 1000 | 17        | 1.03%   |
| 131-140        | 16        | 0.97%   |
| Unknown        | 14        | 0.84%   |
| 41-50          | 11        | 0.66%   |
| 141-150        | 11        | 0.66%   |
| 501-1000       | 9         | 0.54%   |
| 91-100         | 9         | 0.54%   |
| 1-40           | 5         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 770       | 49.11%  |
| 101-120       | 329       | 20.98%  |
| 51-100        | 296       | 18.88%  |
| 161-240       | 114       | 7.27%   |
| More than 240 | 33        | 2.1%    |
| Unknown       | 14        | 0.89%   |
| 1-50          | 12        | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1021      | 72.21%  |
| 2     | 312       | 22.07%  |
| 3     | 42        | 2.97%   |
| 0     | 38        | 2.69%   |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 725       | 32.53%  |
| Realtek Semiconductor                  | 586       | 26.29%  |
| Qualcomm Atheros                       | 389       | 17.45%  |
| Samsung Electronics                    | 130       | 5.83%   |
| Broadcom                               | 122       | 5.47%   |
| Broadcom Limited                       | 47        | 2.11%   |
| MediaTek                               | 43        | 1.93%   |
| Lenovo                                 | 24        | 1.08%   |
| Marvell Technology Group               | 23        | 1.03%   |
| Dell                                   | 17        | 0.76%   |
| ASIX Electronics                       | 15        | 0.67%   |
| Ralink                                 | 12        | 0.54%   |
| Sierra Wireless                        | 11        | 0.49%   |
| DisplayLink                            | 11        | 0.49%   |
| Ralink Technology                      | 10        | 0.45%   |
| TP-Link                                | 9         | 0.4%    |
| Qualcomm Atheros Communications        | 8         | 0.36%   |
| Qualcomm                               | 7         | 0.31%   |
| Ericsson Business Mobile Networks      | 5         | 0.22%   |
| Attansic Technology                    | 5         | 0.22%   |
| Hewlett-Packard                        | 4         | 0.18%   |
| Xiaomi                                 | 3         | 0.13%   |
| Fibocom                                | 3         | 0.13%   |
| Spreadtrum Communications              | 2         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.09%   |
| Huawei Technologies                    | 2         | 0.09%   |
| D-Link                                 | 2         | 0.09%   |
| VIA Technologies                       | 1         | 0.04%   |
| Prusa                                  | 1         | 0.04%   |
| Motorola PCS                           | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| Google                                 | 1         | 0.04%   |
| Fujitsu Siemens Computers              | 1         | 0.04%   |
| Foxconn / Hon Hai                      | 1         | 0.04%   |
| ASUSTek Computer                       | 1         | 0.04%   |
| Arduino SA                             | 1         | 0.04%   |
| AMD                                    | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 366       | 13.73%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 155       | 5.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 127       | 4.76%   |
| Intel Wi-Fi 6 AX200                                               | 84        | 3.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 82        | 3.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 65        | 2.44%   |
| Intel Wireless 8265 / 8275                                        | 62        | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 54        | 2.03%   |
| Intel Wireless 7260                                               | 50        | 1.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 41        | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 40        | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 40        | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 38        | 1.43%   |
| Intel Wi-Fi 6 AX201                                               | 37        | 1.39%   |
| Intel Wireless 8260                                               | 36        | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 34        | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 31        | 1.16%   |
| Intel Wireless 7265                                               | 29        | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                             | 29        | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 28        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 28        | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 27        | 1.01%   |
| Intel Wireless 3165                                               | 27        | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 26        | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 23        | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 23        | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 19        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 18        | 0.68%   |
| Intel WiFi Link 5100                                              | 18        | 0.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 18        | 0.68%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 17        | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                     | 17        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 16        | 0.6%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 16        | 0.6%    |
| Intel Wireless 3160                                               | 15        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 704       | 49.82%  |
| Qualcomm Atheros                  | 342       | 24.2%   |
| Realtek Semiconductor             | 147       | 10.4%   |
| Broadcom                          | 78        | 5.52%   |
| MediaTek                          | 39        | 2.76%   |
| Broadcom Limited                  | 25        | 1.77%   |
| Dell                              | 14        | 0.99%   |
| Ralink                            | 12        | 0.85%   |
| Sierra Wireless                   | 11        | 0.78%   |
| Ralink Technology                 | 10        | 0.71%   |
| TP-Link                           | 8         | 0.57%   |
| Qualcomm Atheros Communications   | 8         | 0.57%   |
| Qualcomm                          | 6         | 0.42%   |
| Fibocom                           | 3         | 0.21%   |
| Hewlett-Packard                   | 2         | 0.14%   |
| Fujitsu Siemens Computers         | 1         | 0.07%   |
| Ericsson Business Mobile Networks | 1         | 0.07%   |
| D-Link                            | 1         | 0.07%   |
| ASUSTek Computer                  | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 155       | 10.94%  |
| Intel Wi-Fi 6 AX200                                                     | 84        | 5.93%   |
| Intel Wireless 8265 / 8275                                              | 62        | 4.38%   |
| Intel Wireless 7260                                                     | 50        | 3.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 2.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 40        | 2.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 40        | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 38        | 2.68%   |
| Intel Wi-Fi 6 AX201                                                     | 37        | 2.61%   |
| Intel Wireless 8260                                                     | 36        | 2.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 34        | 2.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 31        | 2.19%   |
| Intel Wireless 7265                                                     | 29        | 2.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 28        | 1.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 28        | 1.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 1.91%   |
| Intel Wireless 3165                                                     | 27        | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 26        | 1.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 23        | 1.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 23        | 1.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 19        | 1.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 18        | 1.27%   |
| Intel WiFi Link 5100                                                    | 18        | 1.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.2%    |
| Broadcom BCM43142 802.11b/g/n                                           | 17        | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 16        | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 1.13%   |
| Intel Wireless 3160                                                     | 15        | 1.06%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 11        | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 0.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 11        | 0.78%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 0.71%   |
| Intel Ultimate N WiFi Link 5300                                         | 10        | 0.71%   |
| Intel Centrino Wireless-N 2230                                          | 10        | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 9         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 517       | 42.87%  |
| Intel                                  | 301       | 24.96%  |
| Samsung Electronics                    | 127       | 10.53%  |
| Qualcomm Atheros                       | 86        | 7.13%   |
| Broadcom                               | 53        | 4.39%   |
| Lenovo                                 | 24        | 1.99%   |
| Marvell Technology Group               | 23        | 1.91%   |
| Broadcom Limited                       | 22        | 1.82%   |
| ASIX Electronics                       | 15        | 1.24%   |
| DisplayLink                            | 11        | 0.91%   |
| Attansic Technology                    | 5         | 0.41%   |
| MediaTek                               | 4         | 0.33%   |
| Xiaomi                                 | 3         | 0.25%   |
| Spreadtrum Communications              | 2         | 0.17%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.17%   |
| VIA Technologies                       | 1         | 0.08%   |
| TP-Link                                | 1         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.08%   |
| Qualcomm                               | 1         | 0.08%   |
| Motorola PCS                           | 1         | 0.08%   |
| ICS Advent                             | 1         | 0.08%   |
| Huawei Technologies                    | 1         | 0.08%   |
| Hewlett-Packard                        | 1         | 0.08%   |
| Google                                 | 1         | 0.08%   |
| Foxconn / Hon Hai                      | 1         | 0.08%   |
| D-Link                                 | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 366       | 29.8%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 127       | 10.34%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 82        | 6.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 65        | 5.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 54        | 4.4%    |
| Intel Ethernet Connection (4) I219-LM                                          | 29        | 2.36%   |
| Intel Ethernet Connection I217-LM                                              | 18        | 1.47%   |
| Intel 82567LM Gigabit Network Connection                                       | 18        | 1.47%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 1.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 16        | 1.3%    |
| Intel Ethernet Connection I219-LM                                              | 16        | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 14        | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                           | 14        | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 14        | 1.14%   |
| Intel Ethernet Connection (6) I219-V                                           | 13        | 1.06%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 13        | 1.06%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 12        | 0.98%   |
| Intel Ethernet Connection (7) I219-LM                                          | 12        | 0.98%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 0.9%    |
| Intel Ethernet Connection (6) I219-LM                                          | 9         | 0.73%   |
| Intel Ethernet Connection (10) I219-LM                                         | 9         | 0.73%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 9         | 0.73%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 8         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 8         | 0.65%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 0.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 7         | 0.57%   |
| Intel Ethernet Connection I219-V                                               | 7         | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 6         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 6         | 0.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 6         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 6         | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 0.49%   |
| Intel Ethernet Connection (16) I219-LM                                         | 6         | 0.49%   |
| Intel Ethernet Connection (11) I219-LM                                         | 6         | 0.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 6         | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 5         | 0.41%   |
| Intel Ethernet Connection I217-V                                               | 5         | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1347      | 53.73%  |
| Ethernet | 1139      | 45.43%  |
| Modem    | 20        | 0.8%    |
| Unknown  | 1         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1004      | 69.34%  |
| Ethernet | 443       | 30.59%  |
| Modem    | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 917       | 66.98%  |
| 1     | 413       | 30.17%  |
| 0     | 26        | 1.9%    |
| 3     | 13        | 0.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1176      | 84.6%   |
| Yes  | 214       | 15.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 508       | 49.85%  |
| Realtek Semiconductor           | 99        | 9.72%   |
| Qualcomm Atheros Communications | 76        | 7.46%   |
| IMC Networks                    | 74        | 7.26%   |
| Broadcom                        | 55        | 5.4%    |
| Foxconn / Hon Hai               | 53        | 5.2%    |
| Lite-On Technology              | 43        | 4.22%   |
| Hewlett-Packard                 | 28        | 2.75%   |
| Dell                            | 18        | 1.77%   |
| ASUSTek Computer                | 15        | 1.47%   |
| Ralink                          | 9         | 0.88%   |
| Apple                           | 7         | 0.69%   |
| Cambridge Silicon Radio         | 6         | 0.59%   |
| MediaTek                        | 5         | 0.49%   |
| Alps Electric                   | 5         | 0.49%   |
| Toshiba                         | 4         | 0.39%   |
| Realtek                         | 4         | 0.39%   |
| Foxconn International           | 3         | 0.29%   |
| USI                             | 2         | 0.2%    |
| Ralink Technology               | 2         | 0.2%    |
| Micro Star International        | 1         | 0.1%    |
| Fujitsu Siemens Computers       | 1         | 0.1%    |
| Askey Computer                  | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 206       | 20.22%  |
| Intel Bluetooth Device                                                              | 113       | 11.09%  |
| Intel AX200 Bluetooth                                                               | 84        | 8.24%   |
| Realtek Bluetooth Radio                                                             | 68        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 65        | 6.38%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 31        | 3.04%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 24        | 2.36%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 18        | 1.77%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 16        | 1.57%   |
| IMC Networks Bluetooth Device                                                       | 16        | 1.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 15        | 1.47%   |
| IMC Networks Wireless_Device                                                        | 15        | 1.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 15        | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 14        | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 13        | 1.28%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 12        | 1.18%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 12        | 1.18%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 12        | 1.18%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 11        | 1.08%   |
| Dell DW375 Bluetooth Module                                                         | 10        | 0.98%   |
| Broadcom BCM2045 Bluetooth                                                          | 10        | 0.98%   |
| Ralink RT3290 Bluetooth                                                             | 9         | 0.88%   |
| IMC Networks Bluetooth Radio                                                        | 9         | 0.88%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 9         | 0.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 0.79%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 8         | 0.79%   |
| IMC Networks 802.11ac WLAN Adapter                                                  | 8         | 0.79%   |
| Broadcom HP Portable SoftSailing                                                    | 8         | 0.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 0.79%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 8         | 0.79%   |
| Qualcomm Atheros Bluetooth                                                          | 6         | 0.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 0.59%   |
| Intel AX210 Bluetooth                                                               | 6         | 0.59%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 6         | 0.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 0.59%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 6         | 0.59%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 5         | 0.49%   |
| Lite-On Bluetooth Device                                                            | 5         | 0.49%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 0.39%   |
| Realtek Bluetooth Radio                                                             | 4         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1089      | 63.95%  |
| AMD                                  | 288       | 16.91%  |
| Nvidia                               | 168       | 9.86%   |
| Lenovo                               | 31        | 1.82%   |
| Realtek Semiconductor                | 20        | 1.17%   |
| C-Media Electronics                  | 19        | 1.12%   |
| GN Netcom                            | 16        | 0.94%   |
| Logitech                             | 8         | 0.47%   |
| Hewlett-Packard                      | 8         | 0.47%   |
| JMTek                                | 5         | 0.29%   |
| Plantronics                          | 4         | 0.23%   |
| Creative Technology                  | 4         | 0.23%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.18%   |
| Kingston Technology                  | 3         | 0.18%   |
| Yamaha                               | 2         | 0.12%   |
| Sennheiser Communications            | 2         | 0.12%   |
| RODE Microphones                     | 2         | 0.12%   |
| Razer USA                            | 2         | 0.12%   |
| Harman                               | 2         | 0.12%   |
| GYROCOM C&C                          | 2         | 0.12%   |
| Dell                                 | 2         | 0.12%   |
| BEHRINGER International              | 2         | 0.12%   |
| Yealink Network Technology           | 1         | 0.06%   |
| VIA Technologies                     | 1         | 0.06%   |
| Trust                                | 1         | 0.06%   |
| Toshiba                              | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.06%   |
| Texas Instruments                    | 1         | 0.06%   |
| Syntek                               | 1         | 0.06%   |
| SteelSeries ApS                      | 1         | 0.06%   |
| Samson Technologies                  | 1         | 0.06%   |
| Orbbec 3D Technology International   | 1         | 0.06%   |
| M-Audio                              | 1         | 0.06%   |
| Generalplus Technology               | 1         | 0.06%   |
| Focusrite-Novation                   | 1         | 0.06%   |
| ELMCU                                | 1         | 0.06%   |
| DSEA A/S                             | 1         | 0.06%   |
| DigiTech                             | 1         | 0.06%   |
| Datelink Technology                  | 1         | 0.06%   |
| Conexant Systems                     | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 198       | 9.73%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 166       | 8.16%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 135       | 6.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 107       | 5.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 87        | 4.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 59        | 2.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 49        | 2.41%   |
| Intel Cannon Lake PCH cAVS                                                                        | 48        | 2.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 47        | 2.31%   |
| Intel 8 Series HD Audio Controller                                                                | 47        | 2.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 42        | 2.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 42        | 2.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 40        | 1.97%   |
| AMD FCH Azalia Controller                                                                         | 37        | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 36        | 1.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 34        | 1.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 33        | 1.62%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 33        | 1.62%   |
| Intel Broadwell-U Audio Controller                                                                | 33        | 1.62%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 31        | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 29        | 1.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 28        | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 25        | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 23        | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 21        | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 21        | 1.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 21        | 1.03%   |
| Realtek Semiconductor USB Audio                                                                   | 20        | 0.98%   |
| Intel Comet Lake PCH cAVS                                                                         | 20        | 0.98%   |
| Intel CM238 HD Audio Controller                                                                   | 20        | 0.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 20        | 0.98%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 19        | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 19        | 0.93%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 19        | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 19        | 0.93%   |
| AMD High Definition Audio Controller                                                              | 19        | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 0.79%   |
| Nvidia Audio device                                                                               | 13        | 0.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 13        | 0.64%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 12        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 233       | 24.68%  |
| SK hynix             | 189       | 20.02%  |
| Elpida               | 143       | 15.15%  |
| Micron Technology    | 127       | 13.45%  |
| Kingston             | 98        | 10.38%  |
| Unknown              | 41        | 4.34%   |
| Crucial              | 28        | 2.97%   |
| Ramaxel Technology   | 23        | 2.44%   |
| Unknown (ABCD)       | 14        | 1.48%   |
| Corsair              | 12        | 1.27%   |
| A-DATA Technology    | 10        | 1.06%   |
| Nanya Technology     | 8         | 0.85%   |
| Patriot              | 4         | 0.42%   |
| Transcend            | 3         | 0.32%   |
| Unknown              | 2         | 0.21%   |
| Unknown (AB)         | 1         | 0.11%   |
| ProMos/Mosel Vitelic | 1         | 0.11%   |
| OnBoard              | 1         | 0.11%   |
| Nayna                | 1         | 0.11%   |
| Golden Empire        | 1         | 0.11%   |
| G.Skill              | 1         | 0.11%   |
| fef5                 | 1         | 0.11%   |
| ASint Technology     | 1         | 0.11%   |
| 48spaces             | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 126       | 12.79%  |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 1.62%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 1.42%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 12        | 1.22%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 1.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 11        | 1.12%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.91%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 9         | 0.91%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.91%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.81%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.81%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 7         | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.71%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 7         | 0.71%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.71%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.71%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.71%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.71%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 7         | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.51%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.51%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 5         | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.51%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 5         | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 5         | 0.51%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 5         | 0.51%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.51%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.41%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.41%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 4         | 0.41%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.41%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.41%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 354       | 43.44%  |
| DDR3    | 321       | 39.39%  |
| LPDDR4  | 52        | 6.38%   |
| DDR2    | 28        | 3.44%   |
| LPDDR3  | 20        | 2.45%   |
| SDRAM   | 14        | 1.72%   |
| LPDDR5  | 13        | 1.6%    |
| DDR5    | 6         | 0.74%   |
| DDR     | 4         | 0.49%   |
| Unknown | 3         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 732       | 89.38%  |
| Row Of Chips | 72        | 8.79%   |
| Chip         | 10        | 1.22%   |
| Unknown      | 3         | 0.37%   |
| DIMM         | 2         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 300       | 34.13%  |
| 2048  | 203       | 23.09%  |
| 4096  | 180       | 20.48%  |
| 16384 | 147       | 16.72%  |
| 32768 | 25        | 2.84%   |
| 1024  | 19        | 2.16%   |
| 512   | 2         | 0.23%   |
| 6144  | 1         | 0.11%   |
| 3072  | 1         | 0.11%   |
| 256   | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 176       | 20.37%  |
| 1333    | 146       | 16.9%   |
| 1600    | 133       | 15.39%  |
| 2667    | 125       | 14.47%  |
| 2400    | 65        | 7.52%   |
| 2133    | 36        | 4.17%   |
| 1334    | 34        | 3.94%   |
| 4267    | 20        | 2.31%   |
| Unknown | 14        | 1.62%   |
| 667     | 13        | 1.5%    |
| 1067    | 12        | 1.39%   |
| 6400    | 11        | 1.27%   |
| 3266    | 11        | 1.27%   |
| 1867    | 11        | 1.27%   |
| 800     | 7         | 0.81%   |
| 4199    | 6         | 0.69%   |
| 2048    | 6         | 0.69%   |
| 4800    | 5         | 0.58%   |
| 4266    | 5         | 0.58%   |
| 975     | 5         | 0.58%   |
| 533     | 5         | 0.58%   |
| 8400    | 4         | 0.46%   |
| 1066    | 4         | 0.46%   |
| 3733    | 3         | 0.35%   |
| 5600    | 2         | 0.23%   |
| 7500    | 1         | 0.12%   |
| 5500    | 1         | 0.12%   |
| 2933    | 1         | 0.12%   |
| 1639    | 1         | 0.12%   |
| 1400    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 2         | 33.33%  |
| Xerox               | 1         | 16.67%  |
| Samsung Electronics | 1         | 16.67%  |
| Prolific Technology | 1         | 16.67%  |
| Hewlett-Packard     | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Xerox Phaser 3260                | 1         | 16.67%  |
| Samsung M2070 Series             | 1         | 16.67%  |
| Prolific PL2305 Parallel Port    | 1         | 16.67%  |
| HP LaserJet Professional P 1102w | 1         | 16.67%  |
| Canon LBP3010/LBP3018/LBP3050    | 1         | 16.67%  |
| Canon G2020 series               | 1         | 16.67%  |

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
| Chicony Electronics                    | 294       | 26.68%  |
| Realtek Semiconductor                  | 109       | 9.89%   |
| IMC Networks                           | 106       | 9.62%   |
| Microdia                               | 90        | 8.17%   |
| Bison Electronics                      | 89        | 8.08%   |
| Sunplus Innovation Technology          | 72        | 6.53%   |
| Quanta                                 | 49        | 4.45%   |
| Lite-On Technology                     | 46        | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 42        | 3.81%   |
| Suyin                                  | 35        | 3.18%   |
| Syntek                                 | 30        | 2.72%   |
| Acer                                   | 24        | 2.18%   |
| Apple                                  | 14        | 1.27%   |
| Luxvisions Innotech Limited            | 13        | 1.18%   |
| Ricoh                                  | 12        | 1.09%   |
| Lenovo                                 | 11        | 1%      |
| Alcor Micro                            | 11        | 1%      |
| Logitech                               | 9         | 0.82%   |
| Sonix Technology                       | 6         | 0.54%   |
| Samsung Electronics                    | 6         | 0.54%   |
| Primax Electronics                     | 5         | 0.45%   |
| icSpring                               | 4         | 0.36%   |
| Microsoft                              | 2         | 0.18%   |
| Intel                                  | 2         | 0.18%   |
| Z-Star Microelectronics                | 1         | 0.09%   |
| Sunplus Technology                     | 1         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| Silicon Motion                         | 1         | 0.09%   |
| Ruision                                | 1         | 0.09%   |
| Pixart Imaging                         | 1         | 0.09%   |
| Orbbec 3D Technology International     | 1         | 0.09%   |
| OPPO Electronics                       | 1         | 0.09%   |
| lihappe8                               | 1         | 0.09%   |
| KYE Systems (Mouse Systems)            | 1         | 0.09%   |
| Hopewin Electronic Material            | 1         | 0.09%   |
| Goodong Industry                       | 1         | 0.09%   |
| Genesys Logic                          | 1         | 0.09%   |
| GEMBIRD                                | 1         | 0.09%   |
| eMPIA Technology                       | 1         | 0.09%   |
| Elecom                                 | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 79        | 7.14%   |
| IMC Networks Integrated Camera                | 46        | 4.16%   |
| Microdia Integrated_Webcam_HD                 | 42        | 3.79%   |
| Realtek Integrated_Webcam_HD                  | 34        | 3.07%   |
| Bison Integrated Camera                       | 31        | 2.8%    |
| Chicony HD WebCam                             | 30        | 2.71%   |
| Chicony HP HD Camera                          | 29        | 2.62%   |
| IMC Networks USB2.0 HD UVC WebCam             | 24        | 2.17%   |
| Lite-On HP HD Camera                          | 23        | 2.08%   |
| Syntek Integrated Camera                      | 17        | 1.54%   |
| Sunplus Integrated_Webcam_HD                  | 17        | 1.54%   |
| Realtek USB Camera                            | 17        | 1.54%   |
| Chicony Integrated Camera (1280x720@30)       | 14        | 1.26%   |
| Bison Lenovo EasyCamera                       | 14        | 1.26%   |
| Quanta HP HD Camera                           | 12        | 1.08%   |
| Lite-On Integrated Camera                     | 12        | 1.08%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 12        | 1.08%   |
| Bison SunplusIT Integrated Camera             | 12        | 1.08%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 11        | 0.99%   |
| Microdia Integrated Webcam                    | 11        | 0.99%   |
| Sunplus HD WebCam                             | 10        | 0.9%    |
| Quanta HD User Facing                         | 10        | 0.9%    |
| Chicony USB2.0 VGA UVC WebCam                 | 10        | 0.9%    |
| Apple iPhone 5/5C/5S/6/SE                     | 10        | 0.9%    |
| Chicony Lenovo EasyCamera                     | 9         | 0.81%   |
| Bison Lenovo Integrated Webcam                | 9         | 0.81%   |
| Realtek Integrated Webcam HD                  | 8         | 0.72%   |
| Lenovo Integrated Webcam                      | 8         | 0.72%   |
| Chicony HP HD Webcam                          | 8         | 0.72%   |
| Syntek Lenovo EasyCamera                      | 7         | 0.63%   |
| Sunplus Laptop Integrated Webcam HD           | 7         | 0.63%   |
| Chicony FJ Camera                             | 7         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 7         | 0.63%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 6         | 0.54%   |
| Sunplus HP HD Webcam [Fixed]                  | 6         | 0.54%   |
| Sunplus ASUS USB2.0 Webcam                    | 6         | 0.54%   |
| Samsung Galaxy series, misc. (MTP mode)       | 6         | 0.54%   |
| Realtek USB2.0 VGA UVC WebCam                 | 6         | 0.54%   |
| Realtek USB2.0 HD UVC WebCam                  | 6         | 0.54%   |
| Realtek Acer 640 x 480 laptop camera          | 6         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 106       | 34.87%  |
| Validity Sensors                   | 101       | 33.22%  |
| Shenzhen Goodix Technology         | 34        | 11.18%  |
| AuthenTec                          | 29        | 9.54%   |
| Upek                               | 14        | 4.61%   |
| Elan Microelectronics              | 9         | 2.96%   |
| LighTuning Technology              | 7         | 2.3%    |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.66%   |
| STMicroelectronics                 | 1         | 0.33%   |
| Microsoft                          | 1         | 0.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 30        | 9.87%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 9.21%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 19        | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 5.92%   |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 5.92%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 15        | 4.93%   |
| Synaptics Fingerprint reader [HP G6]                                       | 14        | 4.61%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 4.28%   |
| AuthenTec AES2810                                                          | 12        | 3.95%   |
| Validity Sensors VFS491                                                    | 11        | 3.62%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 3.29%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 3.29%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 2.96%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 2.96%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.3%    |
| Shenzhen Goodix FingerPrint                                                | 7         | 2.3%    |
| AuthenTec AES1600                                                          | 7         | 2.3%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 1.97%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.97%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.64%   |
| Elan ELAN:Fingerprint                                                      | 5         | 1.64%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 0.99%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 0.99%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 0.99%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.99%   |
| Synaptics  WBDI                                                            | 3         | 0.99%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.66%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.66%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.66%   |
| Synaptics WBDI                                                             | 2         | 0.66%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.66%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.66%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.33%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.33%   |
| Synaptics WBDI Device                                                      | 1         | 0.33%   |
| Synaptics UWP WBDI                                                         | 1         | 0.33%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.33%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 76        | 55.47%  |
| Alcor Micro               | 40        | 29.2%   |
| O2 Micro                  | 9         | 6.57%   |
| Lenovo                    | 5         | 3.65%   |
| Upek                      | 2         | 1.46%   |
| SCM Microsystems          | 2         | 1.46%   |
| Purism, SPC               | 1         | 0.73%   |
| Gemalto (was Gemplus)     | 1         | 0.73%   |
| Aladdin Knowledge Systems | 1         | 0.73%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 40        | 29.2%   |
| Broadcom 58200                                                               | 24        | 17.52%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 14.6%   |
| Broadcom 5880                                                                | 18        | 13.14%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 10.22%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 5.84%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.65%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.46%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.46%   |
| Purism, SPC Librem Key                                                       | 1         | 0.73%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.73%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.73%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.73%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 799       | 57.32%  |
| 1     | 445       | 31.92%  |
| 2     | 124       | 8.9%    |
| 3     | 20        | 1.43%   |
| 5     | 3         | 0.22%   |
| 4     | 3         | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 299       | 39.5%   |
| Graphics card            | 140       | 18.49%  |
| Chipcard                 | 118       | 15.59%  |
| Net/wireless             | 48        | 6.34%   |
| Multimedia controller    | 34        | 4.49%   |
| Camera                   | 25        | 3.3%    |
| Storage                  | 23        | 3.04%   |
| Bluetooth                | 21        | 2.77%   |
| Communication controller | 13        | 1.72%   |
| Card reader              | 12        | 1.59%   |
| Flash memory             | 7         | 0.92%   |
| Net/ethernet             | 6         | 0.79%   |
| Modem                    | 5         | 0.66%   |
| Sound                    | 4         | 0.53%   |
| Storage/ata              | 1         | 0.13%   |
| Network                  | 1         | 0.13%   |

