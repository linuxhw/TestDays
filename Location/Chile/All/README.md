Linux in Chile - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Chile.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Chile/Desktop/README.md) and [notebooks](/Location/Chile/Notebook/README.md).

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

Total: 969

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Sony          | VPCEA45FL                   | Notebook    | [8079ec1351](https://linux-hardware.org/?probe=8079ec1351) | Jul 29, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [71b03b93a2](https://linux-hardware.org/?probe=71b03b93a2) | Jul 27, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a58ae4eb60](https://linux-hardware.org/?probe=a58ae4eb60) | Jul 24, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [51aefa0464](https://linux-hardware.org/?probe=51aefa0464) | Jul 21, 2022 |
| Samsung       | 750XED                      | Notebook    | [546562ffbb](https://linux-hardware.org/?probe=546562ffbb) | Jul 21, 2022 |
| Olidata       | Unknown                     | Desktop     | [ac7a530d9d](https://linux-hardware.org/?probe=ac7a530d9d) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| Dell          | MXG061                      | Notebook    | [9301162b93](https://linux-hardware.org/?probe=9301162b93) | Jul 18, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | Notebook    | [75cfb6ffa8](https://linux-hardware.org/?probe=75cfb6ffa8) | Jul 17, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [8a0a0ed167](https://linux-hardware.org/?probe=8a0a0ed167) | Jul 16, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [e94723280f](https://linux-hardware.org/?probe=e94723280f) | Jul 16, 2022 |
| Samsung       | 750XED                      | Notebook    | [eb7c27f7ff](https://linux-hardware.org/?probe=eb7c27f7ff) | Jul 15, 2022 |
| HP            | Pavilion g4                 | Notebook    | [40067cace0](https://linux-hardware.org/?probe=40067cace0) | Jul 14, 2022 |
| HP            | Pavilion g4                 | Notebook    | [26859467e9](https://linux-hardware.org/?probe=26859467e9) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [c21113bf90](https://linux-hardware.org/?probe=c21113bf90) | Jul 14, 2022 |
| Lenovo        | ThinkPad P50 20EQA05JCL     | Notebook    | [43f5b3c05d](https://linux-hardware.org/?probe=43f5b3c05d) | Jul 13, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| HP            | Notebook                    | Notebook    | [1358a12fdf](https://linux-hardware.org/?probe=1358a12fdf) | Jul 13, 2022 |
| HP            | Pavilion g4                 | Notebook    | [96ba266748](https://linux-hardware.org/?probe=96ba266748) | Jul 11, 2022 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [269ebd1a4d](https://linux-hardware.org/?probe=269ebd1a4d) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c96551a28](https://linux-hardware.org/?probe=0c96551a28) | Jul 09, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [f69a70c4b4](https://linux-hardware.org/?probe=f69a70c4b4) | Jul 08, 2022 |
| Lenovo        | ThinkPad T61 6457B5S        | Notebook    | [34e97dae1e](https://linux-hardware.org/?probe=34e97dae1e) | Jul 08, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [bcb40b4a21](https://linux-hardware.org/?probe=bcb40b4a21) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c8b9e41a50](https://linux-hardware.org/?probe=c8b9e41a50) | Jul 06, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [de014d917d](https://linux-hardware.org/?probe=de014d917d) | Jul 05, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [03dd055ce5](https://linux-hardware.org/?probe=03dd055ce5) | Jun 30, 2022 |
| HP            | Compaq 15                   | Notebook    | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | Notebook    | [5b8770aaf7](https://linux-hardware.org/?probe=5b8770aaf7) | Jun 27, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | Notebook    | [d80f5059d2](https://linux-hardware.org/?probe=d80f5059d2) | Jun 27, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | Notebook    | [89b9650228](https://linux-hardware.org/?probe=89b9650228) | Jun 27, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b56f69ff9c](https://linux-hardware.org/?probe=b56f69ff9c) | Jun 26, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [5dc08ee2d7](https://linux-hardware.org/?probe=5dc08ee2d7) | Jun 22, 2022 |
| Samsung       | 750XED                      | Notebook    | [49322b3456](https://linux-hardware.org/?probe=49322b3456) | Jun 21, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [463461920a](https://linux-hardware.org/?probe=463461920a) | Jun 21, 2022 |
| Packard Be... | EasyNote MH36               | Notebook    | [ecd7a50e8e](https://linux-hardware.org/?probe=ecd7a50e8e) | Jun 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [bbb3795dc2](https://linux-hardware.org/?probe=bbb3795dc2) | Jun 20, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [234a9c1523](https://linux-hardware.org/?probe=234a9c1523) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cb268bf1ab](https://linux-hardware.org/?probe=cb268bf1ab) | Jun 18, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [f5d7a0bba4](https://linux-hardware.org/?probe=f5d7a0bba4) | Jun 17, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [7d8683dfac](https://linux-hardware.org/?probe=7d8683dfac) | Jun 16, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7adac78ac0](https://linux-hardware.org/?probe=7adac78ac0) | Jun 15, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [77c4dc4a62](https://linux-hardware.org/?probe=77c4dc4a62) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [cf08ff4333](https://linux-hardware.org/?probe=cf08ff4333) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [4b4bd76de7](https://linux-hardware.org/?probe=4b4bd76de7) | Jun 14, 2022 |
| Sony          | VPCM120AL                   | Notebook    | [9eb0e19bd0](https://linux-hardware.org/?probe=9eb0e19bd0) | Jun 13, 2022 |
| HP            | 240 G7                      | Notebook    | [2af5911cf8](https://linux-hardware.org/?probe=2af5911cf8) | Jun 12, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| HP            | 240 G7                      | Notebook    | [bf52288eb2](https://linux-hardware.org/?probe=bf52288eb2) | Jun 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [576c9acdaa](https://linux-hardware.org/?probe=576c9acdaa) | Jun 08, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [73ba6fe3c0](https://linux-hardware.org/?probe=73ba6fe3c0) | Jun 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [83b786e73a](https://linux-hardware.org/?probe=83b786e73a) | Jun 04, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [d561d8dbdb](https://linux-hardware.org/?probe=d561d8dbdb) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [b1fe95fd93](https://linux-hardware.org/?probe=b1fe95fd93) | May 31, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [4ad762abcb](https://linux-hardware.org/?probe=4ad762abcb) | May 31, 2022 |
| ECS           | MCP61M-M3                   | Desktop     | [b785b68657](https://linux-hardware.org/?probe=b785b68657) | May 29, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b7b419d941](https://linux-hardware.org/?probe=b7b419d941) | May 28, 2022 |
| HP            | 240 G7                      | Notebook    | [687546391a](https://linux-hardware.org/?probe=687546391a) | May 23, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [ea99252046](https://linux-hardware.org/?probe=ea99252046) | May 20, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [73bd0df4ae](https://linux-hardware.org/?probe=73bd0df4ae) | May 19, 2022 |
| Unknown       | Unknown                     | Notebook    | [834d86e9da](https://linux-hardware.org/?probe=834d86e9da) | May 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [713dcb3d05](https://linux-hardware.org/?probe=713dcb3d05) | May 17, 2022 |
| HP            | 2ADE                        | Desktop     | [77c2ea750b](https://linux-hardware.org/?probe=77c2ea750b) | May 17, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [be93982cf0](https://linux-hardware.org/?probe=be93982cf0) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [84ae0966e6](https://linux-hardware.org/?probe=84ae0966e6) | May 15, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [a7fb96d9aa](https://linux-hardware.org/?probe=a7fb96d9aa) | May 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f2f965ba56](https://linux-hardware.org/?probe=f2f965ba56) | May 13, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [74d92cc46f](https://linux-hardware.org/?probe=74d92cc46f) | May 11, 2022 |
| LG Electro... | 15Z995-U.ARS5U1             | Notebook    | [4efbc907db](https://linux-hardware.org/?probe=4efbc907db) | May 11, 2022 |
| Acer          | Aspire R7-371T              | Notebook    | [207110a3d4](https://linux-hardware.org/?probe=207110a3d4) | May 07, 2022 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [21e4e874a2](https://linux-hardware.org/?probe=21e4e874a2) | May 06, 2022 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [37e77cbfe5](https://linux-hardware.org/?probe=37e77cbfe5) | May 06, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [c275c52e93](https://linux-hardware.org/?probe=c275c52e93) | May 04, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [799038a9eb](https://linux-hardware.org/?probe=799038a9eb) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [afad13fa01](https://linux-hardware.org/?probe=afad13fa01) | May 04, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [cd1e81afae](https://linux-hardware.org/?probe=cd1e81afae) | May 03, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [bf6d6784ab](https://linux-hardware.org/?probe=bf6d6784ab) | May 03, 2022 |
| MSI           | B450M BAZOOKA               | Desktop     | [a913401ce9](https://linux-hardware.org/?probe=a913401ce9) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | Desktop     | [726be8a4f1](https://linux-hardware.org/?probe=726be8a4f1) | May 02, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [0fa0b3d5f4](https://linux-hardware.org/?probe=0fa0b3d5f4) | May 01, 2022 |
| Lenovo        | ThinkPad T61 7659A39        | Notebook    | [e5c32846e2](https://linux-hardware.org/?probe=e5c32846e2) | Apr 30, 2022 |
| Acer          | Aspire E5-411G              | Notebook    | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [876baf36d7](https://linux-hardware.org/?probe=876baf36d7) | Apr 29, 2022 |
| HP            | Pavilion 14                 | Notebook    | [84bde5e223](https://linux-hardware.org/?probe=84bde5e223) | Apr 29, 2022 |
| HP            | Pavilion g4                 | Notebook    | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [f40f12b9be](https://linux-hardware.org/?probe=f40f12b9be) | Apr 27, 2022 |
| Intel         | Unknown                     | Notebook    | [41b673dda8](https://linux-hardware.org/?probe=41b673dda8) | Apr 26, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [6fbbf00053](https://linux-hardware.org/?probe=6fbbf00053) | Apr 23, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [6dac014a49](https://linux-hardware.org/?probe=6dac014a49) | Apr 22, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [d103edc70e](https://linux-hardware.org/?probe=d103edc70e) | Apr 21, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [e5d8c4e246](https://linux-hardware.org/?probe=e5d8c4e246) | Apr 21, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [cb4bc274b3](https://linux-hardware.org/?probe=cb4bc274b3) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4e2119abc8](https://linux-hardware.org/?probe=4e2119abc8) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d43a69ef63](https://linux-hardware.org/?probe=d43a69ef63) | Apr 21, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [c83cb969dc](https://linux-hardware.org/?probe=c83cb969dc) | Apr 19, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [79eb10a5ef](https://linux-hardware.org/?probe=79eb10a5ef) | Apr 19, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ff9197cd63](https://linux-hardware.org/?probe=ff9197cd63) | Apr 17, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d0cde0bcd](https://linux-hardware.org/?probe=7d0cde0bcd) | Apr 13, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [28897f0c7b](https://linux-hardware.org/?probe=28897f0c7b) | Apr 13, 2022 |
| ASUSTek       | X405UQ                      | Notebook    | [4b63447e77](https://linux-hardware.org/?probe=4b63447e77) | Apr 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [4c367d8a9c](https://linux-hardware.org/?probe=4c367d8a9c) | Apr 08, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [f531f62c1b](https://linux-hardware.org/?probe=f531f62c1b) | Apr 03, 2022 |
| Dell          | Vostro A860                 | Notebook    | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [4ad9fe021c](https://linux-hardware.org/?probe=4ad9fe021c) | Mar 31, 2022 |
| HP            | 1998                        | Desktop     | [13b901f36a](https://linux-hardware.org/?probe=13b901f36a) | Mar 29, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [e02f2032f1](https://linux-hardware.org/?probe=e02f2032f1) | Mar 28, 2022 |
| Dell          | Latitude E5450              | Notebook    | [776f0672a0](https://linux-hardware.org/?probe=776f0672a0) | Mar 23, 2022 |
| Dell          | Latitude E5450              | Notebook    | [fb7f18d5a2](https://linux-hardware.org/?probe=fb7f18d5a2) | Mar 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9183654349](https://linux-hardware.org/?probe=9183654349) | Mar 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [95acb8d0af](https://linux-hardware.org/?probe=95acb8d0af) | Mar 21, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [baae82b163](https://linux-hardware.org/?probe=baae82b163) | Mar 19, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [539ebb7dd9](https://linux-hardware.org/?probe=539ebb7dd9) | Mar 15, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [95c6b15672](https://linux-hardware.org/?probe=95c6b15672) | Mar 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [82cfb46909](https://linux-hardware.org/?probe=82cfb46909) | Mar 13, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [671a3fc70b](https://linux-hardware.org/?probe=671a3fc70b) | Mar 12, 2022 |
| Packard Be... | EasyNote MH35               | Notebook    | [66bff1bcfd](https://linux-hardware.org/?probe=66bff1bcfd) | Mar 08, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [379733b3e7](https://linux-hardware.org/?probe=379733b3e7) | Mar 07, 2022 |
| Elife         | series                      | Notebook    | [dddf04aa69](https://linux-hardware.org/?probe=dddf04aa69) | Mar 05, 2022 |
| Elife         | series                      | Notebook    | [979e43c05a](https://linux-hardware.org/?probe=979e43c05a) | Mar 05, 2022 |
| HP            | 2140                        | Notebook    | [6956607bfd](https://linux-hardware.org/?probe=6956607bfd) | Mar 02, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [332a3f936b](https://linux-hardware.org/?probe=332a3f936b) | Feb 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2f1bb56767](https://linux-hardware.org/?probe=2f1bb56767) | Feb 28, 2022 |
| Lenovo        | ThinkPad T490 20RXS0VX00    | Notebook    | [8f42f6fd5f](https://linux-hardware.org/?probe=8f42f6fd5f) | Feb 28, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [3f97cefeb4](https://linux-hardware.org/?probe=3f97cefeb4) | Feb 26, 2022 |
| Sony          | VAIO                        | All in one  | [4d477a343a](https://linux-hardware.org/?probe=4d477a343a) | Feb 26, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [8dfdb07f98](https://linux-hardware.org/?probe=8dfdb07f98) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| Lenovo        | ThinkPad T495 20NJ0004US    | Notebook    | [d8002e9eae](https://linux-hardware.org/?probe=d8002e9eae) | Feb 23, 2022 |
| Google        | Barla                       | Notebook    | [12180ab1ff](https://linux-hardware.org/?probe=12180ab1ff) | Feb 22, 2022 |
| Toshiba       | Satellite L505              | Notebook    | [16e608fb6b](https://linux-hardware.org/?probe=16e608fb6b) | Feb 22, 2022 |
| HP            | ENVY 15                     | Notebook    | [9758bb9b66](https://linux-hardware.org/?probe=9758bb9b66) | Feb 20, 2022 |
| Dell          | 0CT017                      | Desktop     | [27a31fcb1b](https://linux-hardware.org/?probe=27a31fcb1b) | Feb 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [46021e669f](https://linux-hardware.org/?probe=46021e669f) | Feb 17, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4de3659979](https://linux-hardware.org/?probe=4de3659979) | Feb 16, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [c81bbf6c93](https://linux-hardware.org/?probe=c81bbf6c93) | Feb 16, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [309f440466](https://linux-hardware.org/?probe=309f440466) | Feb 15, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [81f2a365be](https://linux-hardware.org/?probe=81f2a365be) | Feb 13, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [18fa19a4f0](https://linux-hardware.org/?probe=18fa19a4f0) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [824518037a](https://linux-hardware.org/?probe=824518037a) | Feb 10, 2022 |
| Pegatron      | 2ACB                        | Desktop     | [b7987fdaa7](https://linux-hardware.org/?probe=b7987fdaa7) | Feb 10, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [dae40dba1f](https://linux-hardware.org/?probe=dae40dba1f) | Feb 09, 2022 |
| Gigabyte      | B560M DS3H                  | Desktop     | [3c0ad9ce1b](https://linux-hardware.org/?probe=3c0ad9ce1b) | Feb 08, 2022 |
| MSI           | H310M GAMING ARCTIC         | Desktop     | [842ee88335](https://linux-hardware.org/?probe=842ee88335) | Jan 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [3060acc083](https://linux-hardware.org/?probe=3060acc083) | Jan 22, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [02368f5bb1](https://linux-hardware.org/?probe=02368f5bb1) | Jan 22, 2022 |
| Lenovo        | G400 20235                  | Notebook    | [cba5cda239](https://linux-hardware.org/?probe=cba5cda239) | Jan 21, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [d6706833ff](https://linux-hardware.org/?probe=d6706833ff) | Jan 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [c00dd7c570](https://linux-hardware.org/?probe=c00dd7c570) | Jan 18, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [ca729da91f](https://linux-hardware.org/?probe=ca729da91f) | Jan 16, 2022 |
| Lenovo        | ThinkPad T480 20L6A0UGCL    | Notebook    | [e9dbb29c83](https://linux-hardware.org/?probe=e9dbb29c83) | Jan 16, 2022 |
| Acer          | AOD255E                     | Notebook    | [cf1f3ab0e0](https://linux-hardware.org/?probe=cf1f3ab0e0) | Jan 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [95f3d87b66](https://linux-hardware.org/?probe=95f3d87b66) | Jan 09, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [edc40344ef](https://linux-hardware.org/?probe=edc40344ef) | Jan 08, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [979f80197d](https://linux-hardware.org/?probe=979f80197d) | Jan 07, 2022 |
| MSI           | B85M-E33 V2                 | Desktop     | [ef65c0c144](https://linux-hardware.org/?probe=ef65c0c144) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [8107f2613f](https://linux-hardware.org/?probe=8107f2613f) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [704e9c09ad](https://linux-hardware.org/?probe=704e9c09ad) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | Notebook    | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [0346ff374d](https://linux-hardware.org/?probe=0346ff374d) | Dec 26, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [d1d6054fc3](https://linux-hardware.org/?probe=d1d6054fc3) | Dec 22, 2021 |
| Google        | Barla                       | Notebook    | [cfdb4935cd](https://linux-hardware.org/?probe=cfdb4935cd) | Dec 21, 2021 |
| Google        | Barla                       | Notebook    | [0629410759](https://linux-hardware.org/?probe=0629410759) | Dec 21, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [46dab8c74a](https://linux-hardware.org/?probe=46dab8c74a) | Dec 16, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2e00250378](https://linux-hardware.org/?probe=2e00250378) | Dec 16, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [5113655631](https://linux-hardware.org/?probe=5113655631) | Dec 14, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| Samsung       | R510/P510                   | Notebook    | [37a9793570](https://linux-hardware.org/?probe=37a9793570) | Dec 08, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [c53e56384e](https://linux-hardware.org/?probe=c53e56384e) | Dec 07, 2021 |
| Samsung       | R510/P510                   | Notebook    | [f55c0c88cc](https://linux-hardware.org/?probe=f55c0c88cc) | Dec 07, 2021 |
| Lenovo        | ThinkPad T460 20FMA03MCL    | Notebook    | [aecb392c83](https://linux-hardware.org/?probe=aecb392c83) | Dec 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [18da52385a](https://linux-hardware.org/?probe=18da52385a) | Dec 04, 2021 |
| MSI           | 3664h                       | Desktop     | [c4bc6c8049](https://linux-hardware.org/?probe=c4bc6c8049) | Nov 29, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [6490a6beba](https://linux-hardware.org/?probe=6490a6beba) | Nov 29, 2021 |
| Acer          | Swift SF113-31              | Notebook    | [f1e3d8c722](https://linux-hardware.org/?probe=f1e3d8c722) | Nov 29, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [baa3bf4a04](https://linux-hardware.org/?probe=baa3bf4a04) | Nov 27, 2021 |
| Dell          | Inspiron M5010              | Notebook    | [489679b294](https://linux-hardware.org/?probe=489679b294) | Nov 27, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [e9b3a62560](https://linux-hardware.org/?probe=e9b3a62560) | Nov 26, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | Notebook    | [93b6cabcb6](https://linux-hardware.org/?probe=93b6cabcb6) | Nov 25, 2021 |
| HP            | 245 G6                      | Notebook    | [103da5dd76](https://linux-hardware.org/?probe=103da5dd76) | Nov 25, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [93e8bc8935](https://linux-hardware.org/?probe=93e8bc8935) | Nov 24, 2021 |
| Acer          | Aspire V5-471P              | Notebook    | [bf3b81cbb6](https://linux-hardware.org/?probe=bf3b81cbb6) | Nov 20, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [befb5b9afe](https://linux-hardware.org/?probe=befb5b9afe) | Nov 18, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [787fc2d581](https://linux-hardware.org/?probe=787fc2d581) | Nov 18, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [d26e2fac89](https://linux-hardware.org/?probe=d26e2fac89) | Nov 17, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [10a3cb9d12](https://linux-hardware.org/?probe=10a3cb9d12) | Nov 15, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [2bca77430e](https://linux-hardware.org/?probe=2bca77430e) | Nov 14, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | Notebook    | [d0f383a016](https://linux-hardware.org/?probe=d0f383a016) | Nov 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [a61385548e](https://linux-hardware.org/?probe=a61385548e) | Nov 13, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [8b26cea464](https://linux-hardware.org/?probe=8b26cea464) | Nov 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [835c948f68](https://linux-hardware.org/?probe=835c948f68) | Nov 13, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [31bc59dcb9](https://linux-hardware.org/?probe=31bc59dcb9) | Nov 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [ab746b7399](https://linux-hardware.org/?probe=ab746b7399) | Nov 12, 2021 |
| HP            | 2215                        | Desktop     | [4e65fa6078](https://linux-hardware.org/?probe=4e65fa6078) | Nov 09, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c0671f26c9](https://linux-hardware.org/?probe=c0671f26c9) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [258e2f1594](https://linux-hardware.org/?probe=258e2f1594) | Nov 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1dd0c3ba0a](https://linux-hardware.org/?probe=1dd0c3ba0a) | Nov 05, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d6eff141a3](https://linux-hardware.org/?probe=d6eff141a3) | Nov 04, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [e53f2b7fd5](https://linux-hardware.org/?probe=e53f2b7fd5) | Nov 03, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [922c058537](https://linux-hardware.org/?probe=922c058537) | Nov 03, 2021 |
| MSI           | B365M PRO-VH                | Desktop     | [c2976ad59c](https://linux-hardware.org/?probe=c2976ad59c) | Nov 03, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [594175a2ac](https://linux-hardware.org/?probe=594175a2ac) | Nov 01, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [befb41472e](https://linux-hardware.org/?probe=befb41472e) | Oct 23, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [2713972f14](https://linux-hardware.org/?probe=2713972f14) | Oct 22, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3f67c7622c](https://linux-hardware.org/?probe=3f67c7622c) | Oct 22, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| Nvidia        | NF-MCP61                    | Desktop     | [666f204c08](https://linux-hardware.org/?probe=666f204c08) | Oct 18, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [7076268ecc](https://linux-hardware.org/?probe=7076268ecc) | Oct 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f7524634b9](https://linux-hardware.org/?probe=f7524634b9) | Oct 16, 2021 |
| HP            | Compaq CQ45                 | Notebook    | [e51cebc629](https://linux-hardware.org/?probe=e51cebc629) | Oct 16, 2021 |
| HP            | Compaq CQ45                 | Notebook    | [18a1e9d294](https://linux-hardware.org/?probe=18a1e9d294) | Oct 16, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [8f7c7a493b](https://linux-hardware.org/?probe=8f7c7a493b) | Oct 16, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [36e45017ff](https://linux-hardware.org/?probe=36e45017ff) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [06b7518f72](https://linux-hardware.org/?probe=06b7518f72) | Oct 14, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [a0e3e93f48](https://linux-hardware.org/?probe=a0e3e93f48) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [ad35db71c7](https://linux-hardware.org/?probe=ad35db71c7) | Oct 12, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [36d8e83f29](https://linux-hardware.org/?probe=36d8e83f29) | Oct 11, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | Notebook    | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | Notebook    | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| HP            | Notebook                    | Notebook    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | Notebook                    | Notebook    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Alienware     | M17xR3                      | Notebook    | [740de1796c](https://linux-hardware.org/?probe=740de1796c) | Oct 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [8ea6adfced](https://linux-hardware.org/?probe=8ea6adfced) | Oct 03, 2021 |
| ASUSTek       | X555LB                      | Notebook    | [3af223c792](https://linux-hardware.org/?probe=3af223c792) | Sep 30, 2021 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [0055a963ef](https://linux-hardware.org/?probe=0055a963ef) | Sep 30, 2021 |
| Gigabyte      | A520M DS3H                  | Desktop     | [228b36fb26](https://linux-hardware.org/?probe=228b36fb26) | Sep 28, 2021 |
| Dell          | G3 3590                     | Notebook    | [519cea3f38](https://linux-hardware.org/?probe=519cea3f38) | Sep 25, 2021 |
| Dell          | G3 3590                     | Notebook    | [bb25c895cf](https://linux-hardware.org/?probe=bb25c895cf) | Sep 25, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [7360f8d859](https://linux-hardware.org/?probe=7360f8d859) | Sep 23, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| Huanan        | X79 249PC V2.3              | Desktop     | [feb9cf5a3f](https://linux-hardware.org/?probe=feb9cf5a3f) | Sep 20, 2021 |
| Huanan        | X79 249PC V2.3              | Desktop     | [0025ab8888](https://linux-hardware.org/?probe=0025ab8888) | Sep 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [99773cf00e](https://linux-hardware.org/?probe=99773cf00e) | Sep 19, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [079bf76915](https://linux-hardware.org/?probe=079bf76915) | Sep 18, 2021 |
| ASRock        | Z490 Phantom Gaming 4G      | Desktop     | [7857ce2ffa](https://linux-hardware.org/?probe=7857ce2ffa) | Sep 16, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [ef87caa5ba](https://linux-hardware.org/?probe=ef87caa5ba) | Sep 12, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [27a6448b5e](https://linux-hardware.org/?probe=27a6448b5e) | Sep 12, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [e2df45f5f6](https://linux-hardware.org/?probe=e2df45f5f6) | Sep 12, 2021 |
| Intel         | X79M-S                      | Desktop     | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [feea6f3fec](https://linux-hardware.org/?probe=feea6f3fec) | Sep 11, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [36685ad5ea](https://linux-hardware.org/?probe=36685ad5ea) | Sep 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [15ed5db330](https://linux-hardware.org/?probe=15ed5db330) | Sep 09, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | Notebook    | [890790d388](https://linux-hardware.org/?probe=890790d388) | Sep 07, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | Notebook    | [341d88eae9](https://linux-hardware.org/?probe=341d88eae9) | Sep 07, 2021 |
| HP            | 339A                        | Desktop     | [ae80063e20](https://linux-hardware.org/?probe=ae80063e20) | Sep 07, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [14536c9a37](https://linux-hardware.org/?probe=14536c9a37) | Sep 06, 2021 |
| Intel         | X79M-S                      | Desktop     | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a8f9c859be](https://linux-hardware.org/?probe=a8f9c859be) | Sep 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3c5b6aa997](https://linux-hardware.org/?probe=3c5b6aa997) | Sep 05, 2021 |
| HP            | 339A                        | Desktop     | [ceb91782c2](https://linux-hardware.org/?probe=ceb91782c2) | Sep 05, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [3697a37403](https://linux-hardware.org/?probe=3697a37403) | Sep 04, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [e4d2306204](https://linux-hardware.org/?probe=e4d2306204) | Sep 04, 2021 |
| HP            | 339A                        | Desktop     | [2c96fd74fb](https://linux-hardware.org/?probe=2c96fd74fb) | Sep 04, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [f6df33267b](https://linux-hardware.org/?probe=f6df33267b) | Sep 02, 2021 |
| Lenovo        | G480 20156                  | Notebook    | [436287e7dc](https://linux-hardware.org/?probe=436287e7dc) | Sep 02, 2021 |
| Lenovo        | G480 20156                  | Notebook    | [a89f3e4acf](https://linux-hardware.org/?probe=a89f3e4acf) | Sep 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [6bf33dd2cb](https://linux-hardware.org/?probe=6bf33dd2cb) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [93a7aa0485](https://linux-hardware.org/?probe=93a7aa0485) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [190ef257e8](https://linux-hardware.org/?probe=190ef257e8) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Toshiba       | Satellite C845D             | Notebook    | [ac992ef3e5](https://linux-hardware.org/?probe=ac992ef3e5) | Aug 29, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [f6049274c5](https://linux-hardware.org/?probe=f6049274c5) | Aug 27, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [a2afd00e64](https://linux-hardware.org/?probe=a2afd00e64) | Aug 26, 2021 |
| Lenovo        | ThinkPad X260 20F5S3J00D    | Notebook    | [eeb6586c28](https://linux-hardware.org/?probe=eeb6586c28) | Aug 26, 2021 |
| Sony          | VGN-NW215T                  | Notebook    | [3b59710f01](https://linux-hardware.org/?probe=3b59710f01) | Aug 25, 2021 |
| Supermicro    | H8DG6/H8DGi                 | Server      | [1fe97b31a1](https://linux-hardware.org/?probe=1fe97b31a1) | Aug 24, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [207f0c8966](https://linux-hardware.org/?probe=207f0c8966) | Aug 24, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [849c1fe7e3](https://linux-hardware.org/?probe=849c1fe7e3) | Aug 22, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [80aa412668](https://linux-hardware.org/?probe=80aa412668) | Aug 22, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [2a0bf4d1a9](https://linux-hardware.org/?probe=2a0bf4d1a9) | Aug 21, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [28d8feb60d](https://linux-hardware.org/?probe=28d8feb60d) | Aug 20, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [f207dc8e9a](https://linux-hardware.org/?probe=f207dc8e9a) | Aug 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [ab27a12603](https://linux-hardware.org/?probe=ab27a12603) | Aug 18, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [0eb2abca1d](https://linux-hardware.org/?probe=0eb2abca1d) | Aug 18, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [9c25f25e8f](https://linux-hardware.org/?probe=9c25f25e8f) | Aug 16, 2021 |
| Pegatron      | 2ADC                        | Desktop     | [48cc7f548e](https://linux-hardware.org/?probe=48cc7f548e) | Aug 13, 2021 |
| MSI           | B75MA-E33                   | Desktop     | [8a1743cb75](https://linux-hardware.org/?probe=8a1743cb75) | Aug 10, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [b99b48660a](https://linux-hardware.org/?probe=b99b48660a) | Aug 08, 2021 |
| Sony          | SVE14A27CLS                 | Notebook    | [53a5965063](https://linux-hardware.org/?probe=53a5965063) | Aug 07, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [4d0bb591af](https://linux-hardware.org/?probe=4d0bb591af) | Aug 06, 2021 |
| Dell          | G3 3590                     | Notebook    | [16bdb588e1](https://linux-hardware.org/?probe=16bdb588e1) | Aug 05, 2021 |
| Dell          | G3 3590                     | Notebook    | [01a9560f9c](https://linux-hardware.org/?probe=01a9560f9c) | Aug 05, 2021 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [482c64a9c9](https://linux-hardware.org/?probe=482c64a9c9) | Aug 03, 2021 |
| Packard Be... | EasyNote MH35               | Notebook    | [e053c132dc](https://linux-hardware.org/?probe=e053c132dc) | Aug 02, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [acc597c748](https://linux-hardware.org/?probe=acc597c748) | Aug 02, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [60b58b4557](https://linux-hardware.org/?probe=60b58b4557) | Jul 28, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2e753f12ce](https://linux-hardware.org/?probe=2e753f12ce) | Jul 28, 2021 |
| Medion        | Unknown                     | Notebook    | [021ba4d5b5](https://linux-hardware.org/?probe=021ba4d5b5) | Jul 25, 2021 |
| Medion        | Unknown                     | Notebook    | [e9c5e99e0b](https://linux-hardware.org/?probe=e9c5e99e0b) | Jul 25, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [cae2419e98](https://linux-hardware.org/?probe=cae2419e98) | Jul 25, 2021 |
| MSI           | 3664h                       | Desktop     | [491117f46c](https://linux-hardware.org/?probe=491117f46c) | Jul 25, 2021 |
| MSI           | 3664h                       | Desktop     | [c9f3c48709](https://linux-hardware.org/?probe=c9f3c48709) | Jul 24, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [1d0f458592](https://linux-hardware.org/?probe=1d0f458592) | Jul 23, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [f8812e14cb](https://linux-hardware.org/?probe=f8812e14cb) | Jul 23, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [0d3be70373](https://linux-hardware.org/?probe=0d3be70373) | Jul 20, 2021 |
| MSI           | H81M-E33                    | Desktop     | [f56f54e2fa](https://linux-hardware.org/?probe=f56f54e2fa) | Jul 18, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [783a5cafc2](https://linux-hardware.org/?probe=783a5cafc2) | Jul 18, 2021 |
| HP            | ENVY 15                     | Notebook    | [d2a3149a9a](https://linux-hardware.org/?probe=d2a3149a9a) | Jul 17, 2021 |
| eMachines     | EL1352                      | Desktop     | [83c494c15a](https://linux-hardware.org/?probe=83c494c15a) | Jul 17, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [2db57969aa](https://linux-hardware.org/?probe=2db57969aa) | Jul 17, 2021 |
| R-StyleCom... | ALICON AI2S-A21 00.69       | Desktop     | [85a8017eaf](https://linux-hardware.org/?probe=85a8017eaf) | Jul 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5320824c78](https://linux-hardware.org/?probe=5320824c78) | Jul 11, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [efc4c63ac7](https://linux-hardware.org/?probe=efc4c63ac7) | Jul 09, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9f7d75d241](https://linux-hardware.org/?probe=9f7d75d241) | Jul 09, 2021 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [bfef4cded0](https://linux-hardware.org/?probe=bfef4cded0) | Jul 09, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [ef9a6d3444](https://linux-hardware.org/?probe=ef9a6d3444) | Jul 08, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [e3ea65a467](https://linux-hardware.org/?probe=e3ea65a467) | Jul 07, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [1888baa539](https://linux-hardware.org/?probe=1888baa539) | Jul 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a87404851f](https://linux-hardware.org/?probe=a87404851f) | Jul 01, 2021 |
| MSI           | A75MA-G55                   | Desktop     | [3611191f22](https://linux-hardware.org/?probe=3611191f22) | Jun 30, 2021 |
| HP            | Notebook                    | Notebook    | [3087e92283](https://linux-hardware.org/?probe=3087e92283) | Jun 29, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [771f0fed2a](https://linux-hardware.org/?probe=771f0fed2a) | Jun 27, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [48a1dddc38](https://linux-hardware.org/?probe=48a1dddc38) | Jun 27, 2021 |
| Intel         | X79 V2.72B                  | Desktop     | [c78b66e96e](https://linux-hardware.org/?probe=c78b66e96e) | Jun 25, 2021 |
| ASUSTek       | N551JX                      | Notebook    | [3ef394cafb](https://linux-hardware.org/?probe=3ef394cafb) | Jun 24, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [fe7063735e](https://linux-hardware.org/?probe=fe7063735e) | Jun 24, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [9d80703f35](https://linux-hardware.org/?probe=9d80703f35) | Jun 23, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [22f31e0de1](https://linux-hardware.org/?probe=22f31e0de1) | Jun 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [aa0efa1872](https://linux-hardware.org/?probe=aa0efa1872) | Jun 19, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [a53fb9eb09](https://linux-hardware.org/?probe=a53fb9eb09) | Jun 19, 2021 |
| Unknown       | Intel X79                   | Desktop     | [5be1e4c74c](https://linux-hardware.org/?probe=5be1e4c74c) | Jun 18, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [82a162c683](https://linux-hardware.org/?probe=82a162c683) | Jun 18, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [033cd8c9eb](https://linux-hardware.org/?probe=033cd8c9eb) | Jun 17, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8bb06ce851](https://linux-hardware.org/?probe=8bb06ce851) | Jun 16, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [d37cfc0abc](https://linux-hardware.org/?probe=d37cfc0abc) | Jun 13, 2021 |
| HP            | Notebook                    | Notebook    | [f1263ec1fc](https://linux-hardware.org/?probe=f1263ec1fc) | Jun 13, 2021 |
| MSI           | 970A-G46                    | Desktop     | [f7b1001ef1](https://linux-hardware.org/?probe=f7b1001ef1) | Jun 13, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [6529cc537c](https://linux-hardware.org/?probe=6529cc537c) | Jun 13, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [2aa173f32b](https://linux-hardware.org/?probe=2aa173f32b) | Jun 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [16d75c0003](https://linux-hardware.org/?probe=16d75c0003) | Jun 11, 2021 |
| Samsung       | 670Z5E                      | Notebook    | [252e20c152](https://linux-hardware.org/?probe=252e20c152) | Jun 11, 2021 |
| Intel         | DZ77GA-70K AAG39009-401     | Desktop     | [a88c5c7685](https://linux-hardware.org/?probe=a88c5c7685) | Jun 09, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [0ffe39ef8d](https://linux-hardware.org/?probe=0ffe39ef8d) | Jun 09, 2021 |
| Sony          | SVE14113ELW                 | Notebook    | [738c72c21c](https://linux-hardware.org/?probe=738c72c21c) | Jun 09, 2021 |
| HP            | ENVY 15                     | Notebook    | [8d7a772e05](https://linux-hardware.org/?probe=8d7a772e05) | Jun 07, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [587e4453b3](https://linux-hardware.org/?probe=587e4453b3) | Jun 04, 2021 |
| Dell          | Precision 5520              | Notebook    | [199dec46c7](https://linux-hardware.org/?probe=199dec46c7) | Jun 01, 2021 |
| HP            | 1000                        | Notebook    | [21fb6389e7](https://linux-hardware.org/?probe=21fb6389e7) | Jun 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [b1500a1319](https://linux-hardware.org/?probe=b1500a1319) | May 28, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [abc55fc46d](https://linux-hardware.org/?probe=abc55fc46d) | May 28, 2021 |
| Intel         | NUC7i5BNB J31144-309        | Mini pc     | [1761317692](https://linux-hardware.org/?probe=1761317692) | May 28, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9654da138c](https://linux-hardware.org/?probe=9654da138c) | May 28, 2021 |
| Personal C... | Iris                        | Notebook    | [835df5c61e](https://linux-hardware.org/?probe=835df5c61e) | May 27, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [afd83c5750](https://linux-hardware.org/?probe=afd83c5750) | May 25, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [86060380c8](https://linux-hardware.org/?probe=86060380c8) | May 23, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [66e4f1aeff](https://linux-hardware.org/?probe=66e4f1aeff) | May 23, 2021 |
| ASUSTek       | P5K3 Deluxe                 | Desktop     | [458525ba70](https://linux-hardware.org/?probe=458525ba70) | May 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [5287ceef8d](https://linux-hardware.org/?probe=5287ceef8d) | May 17, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [0be7d156c5](https://linux-hardware.org/?probe=0be7d156c5) | May 17, 2021 |
| Toshiba       | Satellite L45-B             | Notebook    | [544d468137](https://linux-hardware.org/?probe=544d468137) | May 16, 2021 |
| HP            | 435                         | Notebook    | [65bbde1e13](https://linux-hardware.org/?probe=65bbde1e13) | May 16, 2021 |
| HP            | 435                         | Notebook    | [fe5a82cf02](https://linux-hardware.org/?probe=fe5a82cf02) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [493edc40c4](https://linux-hardware.org/?probe=493edc40c4) | May 15, 2021 |
| Dell          | 0CN7X8 A04                  | Server      | [e4dee6faf7](https://linux-hardware.org/?probe=e4dee6faf7) | May 15, 2021 |
| Dell          | 0CN7X8 A04                  | Server      | [aa08de711d](https://linux-hardware.org/?probe=aa08de711d) | May 15, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [a98d93888d](https://linux-hardware.org/?probe=a98d93888d) | May 14, 2021 |
| Intel         | YL-3160L2                   | Desktop     | [c282d94246](https://linux-hardware.org/?probe=c282d94246) | May 13, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c533165389](https://linux-hardware.org/?probe=c533165389) | May 13, 2021 |
| Lenovo        | ThinkCentre M55 8808E19     | Desktop     | [a53c13a5c9](https://linux-hardware.org/?probe=a53c13a5c9) | May 12, 2021 |
| MSI           | X58 PLATINUM SLI            | Desktop     | [1fba25dbcf](https://linux-hardware.org/?probe=1fba25dbcf) | May 12, 2021 |
| MSI           | X58 PLATINUM SLI            | Desktop     | [c71715672c](https://linux-hardware.org/?probe=c71715672c) | May 12, 2021 |
| Samsung       | RF712                       | Notebook    | [a3624b29fa](https://linux-hardware.org/?probe=a3624b29fa) | May 11, 2021 |
| Samsung       | RF712                       | Notebook    | [652fb28adb](https://linux-hardware.org/?probe=652fb28adb) | May 11, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [2e4262cb53](https://linux-hardware.org/?probe=2e4262cb53) | May 11, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [aacf9438d2](https://linux-hardware.org/?probe=aacf9438d2) | May 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [2196430972](https://linux-hardware.org/?probe=2196430972) | May 09, 2021 |
| Olidata       | Unknown                     | Desktop     | [1dc7094a4d](https://linux-hardware.org/?probe=1dc7094a4d) | May 09, 2021 |
| HP            | 339A                        | Desktop     | [c103096e94](https://linux-hardware.org/?probe=c103096e94) | May 09, 2021 |
| HP            | 339A                        | Desktop     | [1b94801e8b](https://linux-hardware.org/?probe=1b94801e8b) | May 09, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [08d59f23ab](https://linux-hardware.org/?probe=08d59f23ab) | May 09, 2021 |
| Olidata       | Unknown                     | Desktop     | [0c2f6b27a9](https://linux-hardware.org/?probe=0c2f6b27a9) | May 08, 2021 |
| HP            | 1000                        | Notebook    | [4205750e24](https://linux-hardware.org/?probe=4205750e24) | May 08, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ce41256b96](https://linux-hardware.org/?probe=ce41256b96) | May 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [566133628f](https://linux-hardware.org/?probe=566133628f) | May 07, 2021 |
| Toshiba       | Satellite U505              | Notebook    | [50baa8508f](https://linux-hardware.org/?probe=50baa8508f) | May 05, 2021 |
| Toshiba       | Satellite U505              | Notebook    | [c5785176bd](https://linux-hardware.org/?probe=c5785176bd) | May 05, 2021 |
| MSI           | H81M-E33                    | Desktop     | [47447aaec1](https://linux-hardware.org/?probe=47447aaec1) | May 05, 2021 |
| Packard Be... | EasyNote TM98               | Notebook    | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| HUAWEI        | WRTB-WXX9                   | Notebook    | [f9ceb7c523](https://linux-hardware.org/?probe=f9ceb7c523) | May 02, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [009abcd381](https://linux-hardware.org/?probe=009abcd381) | May 02, 2021 |
| Dell          | Latitude D630               | Notebook    | [40a03f054f](https://linux-hardware.org/?probe=40a03f054f) | May 02, 2021 |
| Acer          | Aspire ES1-431              | Notebook    | [cc8dd98cc6](https://linux-hardware.org/?probe=cc8dd98cc6) | May 01, 2021 |
| HP            | 14                          | Notebook    | [f2874ea965](https://linux-hardware.org/?probe=f2874ea965) | May 01, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [ef811a6184](https://linux-hardware.org/?probe=ef811a6184) | May 01, 2021 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [18b8d3d480](https://linux-hardware.org/?probe=18b8d3d480) | Apr 30, 2021 |
| HP            | Pavilion dm4                | Notebook    | [dd8938cac1](https://linux-hardware.org/?probe=dd8938cac1) | Apr 29, 2021 |
| Dell          | System Inspiron N4110       | Notebook    | [17b9bc8eb3](https://linux-hardware.org/?probe=17b9bc8eb3) | Apr 27, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [c3acaeb030](https://linux-hardware.org/?probe=c3acaeb030) | Apr 26, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [de3298645e](https://linux-hardware.org/?probe=de3298645e) | Apr 26, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8ff356e9be](https://linux-hardware.org/?probe=8ff356e9be) | Apr 25, 2021 |
| Chuwi         | Hi10 plus tablet            | Tablet      | [03f22f7870](https://linux-hardware.org/?probe=03f22f7870) | Apr 25, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [8ed2b2284e](https://linux-hardware.org/?probe=8ed2b2284e) | Apr 24, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9a9bc27310](https://linux-hardware.org/?probe=9a9bc27310) | Apr 23, 2021 |
| Packard Be... | EasyNote_BU45               | Notebook    | [83204d550c](https://linux-hardware.org/?probe=83204d550c) | Apr 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | Notebook    | [998919a455](https://linux-hardware.org/?probe=998919a455) | Apr 18, 2021 |
| ASUSTek       | P5K SE                      | Desktop     | [73a2ad1fd9](https://linux-hardware.org/?probe=73a2ad1fd9) | Apr 18, 2021 |
| ECS           | MCP61M-M3                   | Desktop     | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [0761ed6181](https://linux-hardware.org/?probe=0761ed6181) | Apr 16, 2021 |
| Dell          | Latitude 7410               | Notebook    | [7792c66c17](https://linux-hardware.org/?probe=7792c66c17) | Apr 15, 2021 |
| MSI           | H81M-E33                    | Desktop     | [a5ebd5e702](https://linux-hardware.org/?probe=a5ebd5e702) | Apr 13, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | Notebook    | [8eeff8c77c](https://linux-hardware.org/?probe=8eeff8c77c) | Apr 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [a13b6fcbcd](https://linux-hardware.org/?probe=a13b6fcbcd) | Apr 12, 2021 |
| Dell          | Latitude 7400               | Notebook    | [41a2361010](https://linux-hardware.org/?probe=41a2361010) | Apr 11, 2021 |
| Acer          | Aspire ES1-431              | Notebook    | [9109f31570](https://linux-hardware.org/?probe=9109f31570) | Apr 10, 2021 |
| Acer          | Aspire ES1-431              | Notebook    | [df53cbed23](https://linux-hardware.org/?probe=df53cbed23) | Apr 10, 2021 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [5a1bc2f8fe](https://linux-hardware.org/?probe=5a1bc2f8fe) | Apr 10, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [dd16cda442](https://linux-hardware.org/?probe=dd16cda442) | Apr 10, 2021 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [79f36c06be](https://linux-hardware.org/?probe=79f36c06be) | Apr 09, 2021 |
| ASUSTek       | N46VB                       | Notebook    | [a425e290d7](https://linux-hardware.org/?probe=a425e290d7) | Apr 09, 2021 |
| Personal C... | Iris                        | Notebook    | [add36a3a7c](https://linux-hardware.org/?probe=add36a3a7c) | Apr 09, 2021 |
| Personal C... | Iris                        | Notebook    | [4ec2ee9e6d](https://linux-hardware.org/?probe=4ec2ee9e6d) | Apr 09, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [adb7fbfc0d](https://linux-hardware.org/?probe=adb7fbfc0d) | Apr 08, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [9b9172e5a7](https://linux-hardware.org/?probe=9b9172e5a7) | Apr 08, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [3c44770d1a](https://linux-hardware.org/?probe=3c44770d1a) | Apr 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [3a85124409](https://linux-hardware.org/?probe=3a85124409) | Apr 07, 2021 |
| HP            | ENVY Notebook               | Notebook    | [83a0078309](https://linux-hardware.org/?probe=83a0078309) | Apr 06, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [f3b9205a6c](https://linux-hardware.org/?probe=f3b9205a6c) | Apr 06, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [8e2a8be8ce](https://linux-hardware.org/?probe=8e2a8be8ce) | Apr 06, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [ace9676e8c](https://linux-hardware.org/?probe=ace9676e8c) | Apr 05, 2021 |
| HP            | 15                          | Notebook    | [69d2aa2538](https://linux-hardware.org/?probe=69d2aa2538) | Apr 05, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | Notebook    | [8d5f33367e](https://linux-hardware.org/?probe=8d5f33367e) | Apr 04, 2021 |
| Lenovo        | IdeaPad Y480                | Notebook    | [d0aeb8aafc](https://linux-hardware.org/?probe=d0aeb8aafc) | Apr 03, 2021 |
| Foxconn       | G31MV/G31MV-K FAB           | Desktop     | [18047eb612](https://linux-hardware.org/?probe=18047eb612) | Apr 01, 2021 |
| Dell          | Inspiron 3420               | Notebook    | [4d76b6366d](https://linux-hardware.org/?probe=4d76b6366d) | Apr 01, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [742b7afcc8](https://linux-hardware.org/?probe=742b7afcc8) | Apr 01, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [8856c82ed6](https://linux-hardware.org/?probe=8856c82ed6) | Mar 31, 2021 |
| HP            | ENVY 15                     | Notebook    | [31c601923e](https://linux-hardware.org/?probe=31c601923e) | Mar 31, 2021 |
| HP            | ENVY 15                     | Notebook    | [3628d88bc1](https://linux-hardware.org/?probe=3628d88bc1) | Mar 31, 2021 |
| ASUSTek       | P5K SE                      | Desktop     | [fb06c3aee0](https://linux-hardware.org/?probe=fb06c3aee0) | Mar 31, 2021 |
| ASUSTek       | P5K SE                      | Desktop     | [22e69da73a](https://linux-hardware.org/?probe=22e69da73a) | Mar 30, 2021 |
| HP            | 250 G4 Notebook PC          | Notebook    | [e3119c3a18](https://linux-hardware.org/?probe=e3119c3a18) | Mar 30, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [3a4703f85d](https://linux-hardware.org/?probe=3a4703f85d) | Mar 27, 2021 |
| MSI           | 970A-G46                    | Desktop     | [09083497aa](https://linux-hardware.org/?probe=09083497aa) | Mar 26, 2021 |
| MSI           | 970A-G46                    | Desktop     | [dfb535cf31](https://linux-hardware.org/?probe=dfb535cf31) | Mar 26, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [22e5f1f5df](https://linux-hardware.org/?probe=22e5f1f5df) | Mar 25, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [867936010e](https://linux-hardware.org/?probe=867936010e) | Mar 25, 2021 |
| HP            | 18E9                        | Desktop     | [db74abc8b8](https://linux-hardware.org/?probe=db74abc8b8) | Mar 23, 2021 |
| HP            | 18E9                        | Desktop     | [13bfb17279](https://linux-hardware.org/?probe=13bfb17279) | Mar 23, 2021 |
| HP            | ProLiant ML10               | Desktop     | [1b448e4a71](https://linux-hardware.org/?probe=1b448e4a71) | Mar 23, 2021 |
| HP            | ProLiant ML10               | Desktop     | [cd6b0c3826](https://linux-hardware.org/?probe=cd6b0c3826) | Mar 22, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [398c74f08f](https://linux-hardware.org/?probe=398c74f08f) | Mar 21, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [c99084051b](https://linux-hardware.org/?probe=c99084051b) | Mar 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d1bd246775](https://linux-hardware.org/?probe=d1bd246775) | Mar 19, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1892b65b62](https://linux-hardware.org/?probe=1892b65b62) | Mar 18, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [6079a062b3](https://linux-hardware.org/?probe=6079a062b3) | Mar 18, 2021 |
| HP            | 240 G7 Notebook PC          | Notebook    | [669e53f097](https://linux-hardware.org/?probe=669e53f097) | Mar 16, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [0f95174924](https://linux-hardware.org/?probe=0f95174924) | Mar 15, 2021 |
| ASUSTek       | H110M-D                     | Desktop     | [da2dd5ad1a](https://linux-hardware.org/?probe=da2dd5ad1a) | Mar 15, 2021 |
| HP            | Notebook                    | Notebook    | [9c176242dd](https://linux-hardware.org/?probe=9c176242dd) | Mar 14, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [e2e99630ca](https://linux-hardware.org/?probe=e2e99630ca) | Mar 14, 2021 |
| HP            | 15                          | Notebook    | [08b381f369](https://linux-hardware.org/?probe=08b381f369) | Mar 12, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [0611d13dff](https://linux-hardware.org/?probe=0611d13dff) | Mar 11, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [fc6181a7c1](https://linux-hardware.org/?probe=fc6181a7c1) | Mar 11, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [38042c5772](https://linux-hardware.org/?probe=38042c5772) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| ECS           | A740GM-M                    | Desktop     | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| Intel         | X79 V1.x                    | Desktop     | [2b98f9b956](https://linux-hardware.org/?probe=2b98f9b956) | Mar 08, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [a1a9e12988](https://linux-hardware.org/?probe=a1a9e12988) | Mar 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1f2c6bc8af](https://linux-hardware.org/?probe=1f2c6bc8af) | Mar 05, 2021 |
| MSI           | Stealth 15M A11SEK          | Notebook    | [1187156178](https://linux-hardware.org/?probe=1187156178) | Mar 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [7991d50dfd](https://linux-hardware.org/?probe=7991d50dfd) | Mar 01, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [78e3ef84ba](https://linux-hardware.org/?probe=78e3ef84ba) | Feb 28, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [000cba3fb5](https://linux-hardware.org/?probe=000cba3fb5) | Feb 28, 2021 |
| Unknown       | Unknown                     | Notebook    | [e8359056f7](https://linux-hardware.org/?probe=e8359056f7) | Feb 26, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [485a4f1e98](https://linux-hardware.org/?probe=485a4f1e98) | Feb 25, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [45dfe3c2b1](https://linux-hardware.org/?probe=45dfe3c2b1) | Feb 24, 2021 |
| Unknown       | AD12-B                      | Desktop     | [8167d089b9](https://linux-hardware.org/?probe=8167d089b9) | Feb 20, 2021 |
| Dell          | Vostro V13                  | Notebook    | [f9b40741e7](https://linux-hardware.org/?probe=f9b40741e7) | Feb 19, 2021 |
| Toshiba       | Satellite C845D             | Notebook    | [6a73d1fd72](https://linux-hardware.org/?probe=6a73d1fd72) | Feb 19, 2021 |
| Packard Be... | EasyNote TM85               | Notebook    | [972a7d0f8c](https://linux-hardware.org/?probe=972a7d0f8c) | Feb 17, 2021 |
| MSI           | MS-7267                     | Desktop     | [79cfa785c3](https://linux-hardware.org/?probe=79cfa785c3) | Feb 16, 2021 |
| MSI           | MS-7267                     | Desktop     | [9677e2392c](https://linux-hardware.org/?probe=9677e2392c) | Feb 16, 2021 |
| ASUSTek       | GL502VMK                    | Notebook    | [54b49d2dc7](https://linux-hardware.org/?probe=54b49d2dc7) | Feb 15, 2021 |
| ASUSTek       | GL502VMK                    | Notebook    | [514a434029](https://linux-hardware.org/?probe=514a434029) | Feb 15, 2021 |
| Dell          | Latitude 3440               | Notebook    | [d2806294ef](https://linux-hardware.org/?probe=d2806294ef) | Feb 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [acd23bb798](https://linux-hardware.org/?probe=acd23bb798) | Feb 13, 2021 |
| Sony          | VPCEG15FL                   | Notebook    | [48a16e8a4a](https://linux-hardware.org/?probe=48a16e8a4a) | Feb 10, 2021 |
| Dell          | System Inspiron N411Z       | Notebook    | [eed8ecb624](https://linux-hardware.org/?probe=eed8ecb624) | Feb 08, 2021 |
| Dell          | 0CRH6C A01                  | Desktop     | [31da132ae8](https://linux-hardware.org/?probe=31da132ae8) | Feb 08, 2021 |
| Dell          | 0CRH6C A01                  | Desktop     | [8e9e7ffea0](https://linux-hardware.org/?probe=8e9e7ffea0) | Feb 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd F... | Notebook    | [799c301ad6](https://linux-hardware.org/?probe=799c301ad6) | Feb 08, 2021 |
| Dell          | System Inspiron N411Z       | Notebook    | [f6ea43033f](https://linux-hardware.org/?probe=f6ea43033f) | Feb 07, 2021 |
| Unknown       | AD12-B                      | Desktop     | [6635cbda4d](https://linux-hardware.org/?probe=6635cbda4d) | Feb 06, 2021 |
| Unknown       | AD12-B                      | Desktop     | [05ad299f0e](https://linux-hardware.org/?probe=05ad299f0e) | Feb 06, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [121e3e7d2d](https://linux-hardware.org/?probe=121e3e7d2d) | Feb 02, 2021 |
| Toshiba       | Satellite L745              | Notebook    | [01a4eafbb6](https://linux-hardware.org/?probe=01a4eafbb6) | Feb 02, 2021 |
| Toshiba       | Satellite L745              | Notebook    | [9cc5c245d0](https://linux-hardware.org/?probe=9cc5c245d0) | Feb 02, 2021 |
| HP            | 2ADE                        | Desktop     | [2ee5093250](https://linux-hardware.org/?probe=2ee5093250) | Feb 02, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [2ba1c141b8](https://linux-hardware.org/?probe=2ba1c141b8) | Feb 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [3f400fbc08](https://linux-hardware.org/?probe=3f400fbc08) | Jan 31, 2021 |
| ECS           | MCP61M-M3                   | Desktop     | [445f06dbde](https://linux-hardware.org/?probe=445f06dbde) | Jan 29, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1a8312f66a](https://linux-hardware.org/?probe=1a8312f66a) | Jan 29, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [b024bfc145](https://linux-hardware.org/?probe=b024bfc145) | Jan 29, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [e32eec7802](https://linux-hardware.org/?probe=e32eec7802) | Jan 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [bf3c21f60b](https://linux-hardware.org/?probe=bf3c21f60b) | Jan 25, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [8289f3c10b](https://linux-hardware.org/?probe=8289f3c10b) | Jan 24, 2021 |
| HP            | Pavilion 15                 | Notebook    | [b83dc673fd](https://linux-hardware.org/?probe=b83dc673fd) | Jan 23, 2021 |
| HP            | 14                          | Notebook    | [7c1ff6f4a8](https://linux-hardware.org/?probe=7c1ff6f4a8) | Jan 22, 2021 |
| Dell          | Vostro 1520                 | Notebook    | [36392e13b5](https://linux-hardware.org/?probe=36392e13b5) | Jan 22, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [c1df3dc860](https://linux-hardware.org/?probe=c1df3dc860) | Jan 21, 2021 |
| IBM           | 813311S                     | Desktop     | [c65634928d](https://linux-hardware.org/?probe=c65634928d) | Jan 20, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [5f648131f5](https://linux-hardware.org/?probe=5f648131f5) | Jan 19, 2021 |
| IBM           | 813311S                     | Desktop     | [9dc5e1fd39](https://linux-hardware.org/?probe=9dc5e1fd39) | Jan 19, 2021 |
| Huanan        | X79 VAA1                    | Desktop     | [d88d20e6fc](https://linux-hardware.org/?probe=d88d20e6fc) | Jan 15, 2021 |
| ASUSTek       | UX310UQK                    | Notebook    | [7006cf4aa0](https://linux-hardware.org/?probe=7006cf4aa0) | Jan 13, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [4b69e8576c](https://linux-hardware.org/?probe=4b69e8576c) | Jan 11, 2021 |
| MSI           | B360M PRO-VH                | Desktop     | [f666aa301e](https://linux-hardware.org/?probe=f666aa301e) | Jan 08, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [7ae430600b](https://linux-hardware.org/?probe=7ae430600b) | Jan 07, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [5d26e74a5d](https://linux-hardware.org/?probe=5d26e74a5d) | Jan 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [1ce6d33d5b](https://linux-hardware.org/?probe=1ce6d33d5b) | Jan 07, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [fb8fa788e3](https://linux-hardware.org/?probe=fb8fa788e3) | Jan 07, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [fb56fb77b9](https://linux-hardware.org/?probe=fb56fb77b9) | Jan 07, 2021 |
| HP            | Notebook                    | Notebook    | [38341a3370](https://linux-hardware.org/?probe=38341a3370) | Jan 06, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [724662dec7](https://linux-hardware.org/?probe=724662dec7) | Jan 05, 2021 |
| Sony          | SVE14113ELW                 | Notebook    | [695f68585f](https://linux-hardware.org/?probe=695f68585f) | Jan 05, 2021 |
| Sony          | SVE14113ELW                 | Notebook    | [88ef270eb5](https://linux-hardware.org/?probe=88ef270eb5) | Jan 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [019f053a89](https://linux-hardware.org/?probe=019f053a89) | Jan 02, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [997d30ab91](https://linux-hardware.org/?probe=997d30ab91) | Jan 01, 2021 |
| HP            | Notebook                    | Notebook    | [cf3a2917d1](https://linux-hardware.org/?probe=cf3a2917d1) | Dec 28, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [0a8ed33e62](https://linux-hardware.org/?probe=0a8ed33e62) | Dec 26, 2020 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [74ccd1687d](https://linux-hardware.org/?probe=74ccd1687d) | Dec 24, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [9a02f6b2cf](https://linux-hardware.org/?probe=9a02f6b2cf) | Dec 22, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [98c8e4f3a6](https://linux-hardware.org/?probe=98c8e4f3a6) | Dec 20, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [ad2cafcbe8](https://linux-hardware.org/?probe=ad2cafcbe8) | Dec 13, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [43e55c9de6](https://linux-hardware.org/?probe=43e55c9de6) | Dec 13, 2020 |
| HP            | EliteBook 840r G4           | Notebook    | [ebc64db4ca](https://linux-hardware.org/?probe=ebc64db4ca) | Dec 12, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [f29c073cfb](https://linux-hardware.org/?probe=f29c073cfb) | Dec 11, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [5783b64146](https://linux-hardware.org/?probe=5783b64146) | Dec 11, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [5bae11079c](https://linux-hardware.org/?probe=5bae11079c) | Dec 09, 2020 |
| Toshiba       | Satellite C645              | Notebook    | [0e17d5e680](https://linux-hardware.org/?probe=0e17d5e680) | Dec 09, 2020 |
| Toshiba       | Satellite C645              | Notebook    | [0fcca906f6](https://linux-hardware.org/?probe=0fcca906f6) | Dec 09, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [d9258de65c](https://linux-hardware.org/?probe=d9258de65c) | Dec 09, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [7469e3af08](https://linux-hardware.org/?probe=7469e3af08) | Dec 08, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [fd5f6edfb2](https://linux-hardware.org/?probe=fd5f6edfb2) | Dec 08, 2020 |
| Acer          | One S1003                   | Tablet      | [99ca8fdec1](https://linux-hardware.org/?probe=99ca8fdec1) | Dec 04, 2020 |
| HP            | ProBook 440 G7              | Notebook    | [01b2a334c8](https://linux-hardware.org/?probe=01b2a334c8) | Dec 04, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [38fa279b2b](https://linux-hardware.org/?probe=38fa279b2b) | Dec 04, 2020 |
| Lenovo        | IdeaPad Z400 20201          | Notebook    | [9f4318e1fa](https://linux-hardware.org/?probe=9f4318e1fa) | Dec 03, 2020 |
| Lenovo        | K2450 20243                 | Notebook    | [33409ba105](https://linux-hardware.org/?probe=33409ba105) | Dec 03, 2020 |
| Dell          | Latitude E7470              | Notebook    | [ff5ee269cb](https://linux-hardware.org/?probe=ff5ee269cb) | Dec 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [9be5961a82](https://linux-hardware.org/?probe=9be5961a82) | Nov 25, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [2ce0bde22b](https://linux-hardware.org/?probe=2ce0bde22b) | Nov 21, 2020 |
| ASUSTek       | X405UA                      | Notebook    | [e27b62e8d8](https://linux-hardware.org/?probe=e27b62e8d8) | Nov 19, 2020 |
| Lenovo        | K2450 20243                 | Notebook    | [4d44042257](https://linux-hardware.org/?probe=4d44042257) | Nov 19, 2020 |
| HP            | EliteBook 840r G4           | Notebook    | [4782db92e6](https://linux-hardware.org/?probe=4782db92e6) | Nov 19, 2020 |
| Lenovo        | IdeaPad S206 20154          | Notebook    | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Lenovo        | SDK0F82990 WIN              | All in one  | [824c055b5b](https://linux-hardware.org/?probe=824c055b5b) | Nov 18, 2020 |
| Lenovo        | G400 20235                  | Notebook    | [7cdfc8df41](https://linux-hardware.org/?probe=7cdfc8df41) | Nov 17, 2020 |
| Lenovo        | G400 20235                  | Notebook    | [9d19c00f4e](https://linux-hardware.org/?probe=9d19c00f4e) | Nov 17, 2020 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [df5beb221f](https://linux-hardware.org/?probe=df5beb221f) | Nov 15, 2020 |
| Positivo      | Mobile                      | Notebook    | [87704474ae](https://linux-hardware.org/?probe=87704474ae) | Nov 12, 2020 |
| HP            | 1000                        | Notebook    | [a79972678b](https://linux-hardware.org/?probe=a79972678b) | Nov 10, 2020 |
| Lenovo        | ThinkPad T400 6474AU5       | Notebook    | [1b3d0a7938](https://linux-hardware.org/?probe=1b3d0a7938) | Nov 09, 2020 |
| HP            | 420                         | Notebook    | [8b2ce5df27](https://linux-hardware.org/?probe=8b2ce5df27) | Nov 09, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [60a084dcdf](https://linux-hardware.org/?probe=60a084dcdf) | Nov 06, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2c19015153](https://linux-hardware.org/?probe=2c19015153) | Nov 05, 2020 |
| Unknown       | Unknown                     | Notebook    | [8651ede6c2](https://linux-hardware.org/?probe=8651ede6c2) | Nov 04, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [764cabc447](https://linux-hardware.org/?probe=764cabc447) | Nov 03, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [323e8e18f8](https://linux-hardware.org/?probe=323e8e18f8) | Nov 02, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [237294dbc3](https://linux-hardware.org/?probe=237294dbc3) | Nov 01, 2020 |
| ECS           | A785GM-M                    | Desktop     | [fa61acdd56](https://linux-hardware.org/?probe=fa61acdd56) | Oct 30, 2020 |
| HP            | Pavilion dv4                | Notebook    | [80f9a1311e](https://linux-hardware.org/?probe=80f9a1311e) | Oct 30, 2020 |
| Toshiba       | Satellite C45-A             | Notebook    | [bbfec71882](https://linux-hardware.org/?probe=bbfec71882) | Oct 30, 2020 |
| Lenovo        | SDK0F82990 WIN              | All in one  | [012b6a56ef](https://linux-hardware.org/?probe=012b6a56ef) | Oct 26, 2020 |
| HP            | Laptop 14-cf0xxx            | Notebook    | [5ae192d7e1](https://linux-hardware.org/?probe=5ae192d7e1) | Oct 26, 2020 |
| HP            | Laptop 14-cf0xxx            | Notebook    | [8999670eb2](https://linux-hardware.org/?probe=8999670eb2) | Oct 25, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [628265bca0](https://linux-hardware.org/?probe=628265bca0) | Oct 25, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [e31a805419](https://linux-hardware.org/?probe=e31a805419) | Oct 24, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [e2a0899961](https://linux-hardware.org/?probe=e2a0899961) | Oct 23, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [e1ac94acb7](https://linux-hardware.org/?probe=e1ac94acb7) | Oct 23, 2020 |
| Lenovo        | IdeaPad S300 20197          | Notebook    | [d03e3dc110](https://linux-hardware.org/?probe=d03e3dc110) | Oct 23, 2020 |
| Intel         | X99                         | Desktop     | [53e51e0b25](https://linux-hardware.org/?probe=53e51e0b25) | Oct 22, 2020 |
| Intel         | X99                         | Desktop     | [194038048f](https://linux-hardware.org/?probe=194038048f) | Oct 22, 2020 |
| Dell          | Latitude E6440              | Notebook    | [46a2699a96](https://linux-hardware.org/?probe=46a2699a96) | Oct 21, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [01143e194b](https://linux-hardware.org/?probe=01143e194b) | Oct 20, 2020 |
| ASUSTek       | X555LB                      | Notebook    | [75ba1f9ee4](https://linux-hardware.org/?probe=75ba1f9ee4) | Oct 19, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [78a57e6fb8](https://linux-hardware.org/?probe=78a57e6fb8) | Oct 13, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [63831d979c](https://linux-hardware.org/?probe=63831d979c) | Oct 06, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [887dc701b4](https://linux-hardware.org/?probe=887dc701b4) | Oct 05, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [eed07ba536](https://linux-hardware.org/?probe=eed07ba536) | Oct 05, 2020 |
| MSI           | B75MA-E33                   | Desktop     | [1616dff15a](https://linux-hardware.org/?probe=1616dff15a) | Oct 04, 2020 |
| Unknown       | Unknown                     | Notebook    | [afc109116d](https://linux-hardware.org/?probe=afc109116d) | Oct 01, 2020 |
| HP            | 530                         | Notebook    | [c330f06c15](https://linux-hardware.org/?probe=c330f06c15) | Sep 30, 2020 |
| Intel         | DH55PJ AAE93812-301         | Desktop     | [f6a0fd4389](https://linux-hardware.org/?probe=f6a0fd4389) | Sep 30, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ad0d202176](https://linux-hardware.org/?probe=ad0d202176) | Sep 29, 2020 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [6f97a1bc53](https://linux-hardware.org/?probe=6f97a1bc53) | Sep 28, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [5e196929f0](https://linux-hardware.org/?probe=5e196929f0) | Sep 28, 2020 |
| Lenovo        | ThinkPad T460 20FMS05G4L    | Notebook    | [2934114047](https://linux-hardware.org/?probe=2934114047) | Sep 28, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [bd632f89ef](https://linux-hardware.org/?probe=bd632f89ef) | Sep 26, 2020 |
| HP            | EliteBook 840r G4           | Notebook    | [2ed34e371e](https://linux-hardware.org/?probe=2ed34e371e) | Sep 26, 2020 |
| Unknown       | Unknown                     | Notebook    | [be59c4d6c4](https://linux-hardware.org/?probe=be59c4d6c4) | Sep 23, 2020 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [0ad4bcad78](https://linux-hardware.org/?probe=0ad4bcad78) | Sep 23, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [42e3c550cb](https://linux-hardware.org/?probe=42e3c550cb) | Sep 22, 2020 |
| ASUSTek       | X556URK                     | Notebook    | [1c0033b367](https://linux-hardware.org/?probe=1c0033b367) | Sep 20, 2020 |
| ASUSTek       | G55VW                       | Notebook    | [8bfec34af2](https://linux-hardware.org/?probe=8bfec34af2) | Sep 20, 2020 |
| HP            | 245 G5 Notebook PC          | Notebook    | [d2e8cd8f97](https://linux-hardware.org/?probe=d2e8cd8f97) | Sep 15, 2020 |
| HP            | 245 G5 Notebook PC          | Notebook    | [da0f03edfc](https://linux-hardware.org/?probe=da0f03edfc) | Sep 14, 2020 |
| Acer          | Aspire 5542                 | Notebook    | [da115e748b](https://linux-hardware.org/?probe=da115e748b) | Sep 14, 2020 |
| HP            | 2ADE                        | Desktop     | [0ac3191171](https://linux-hardware.org/?probe=0ac3191171) | Sep 10, 2020 |
| HP            | 2ADE                        | Desktop     | [1cf059d943](https://linux-hardware.org/?probe=1cf059d943) | Sep 10, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [1f5bd64812](https://linux-hardware.org/?probe=1f5bd64812) | Sep 09, 2020 |
| HP            | Pavilion 15                 | Notebook    | [df560484b4](https://linux-hardware.org/?probe=df560484b4) | Sep 09, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [8222d70ff5](https://linux-hardware.org/?probe=8222d70ff5) | Sep 09, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [44782a039e](https://linux-hardware.org/?probe=44782a039e) | Sep 07, 2020 |
| Lenovo        | ThinkPad A485 20MVS0N300    | Notebook    | [6ad17e6cf7](https://linux-hardware.org/?probe=6ad17e6cf7) | Sep 05, 2020 |
| HP            | Notebook                    | Notebook    | [c5d0ec5edb](https://linux-hardware.org/?probe=c5d0ec5edb) | Aug 30, 2020 |
| Acer          | Aspire E1-422               | Notebook    | [a239e53a11](https://linux-hardware.org/?probe=a239e53a11) | Aug 29, 2020 |
| MSI           | H61M-P20                    | Desktop     | [9eafb382df](https://linux-hardware.org/?probe=9eafb382df) | Aug 28, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [02f9010c71](https://linux-hardware.org/?probe=02f9010c71) | Aug 26, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [341b0f6231](https://linux-hardware.org/?probe=341b0f6231) | Aug 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [be74487ec4](https://linux-hardware.org/?probe=be74487ec4) | Aug 23, 2020 |
| HP            | 81C3                        | Desktop     | [d558ddad9e](https://linux-hardware.org/?probe=d558ddad9e) | Aug 22, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [fcee1a2241](https://linux-hardware.org/?probe=fcee1a2241) | Aug 21, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [43f35553ae](https://linux-hardware.org/?probe=43f35553ae) | Aug 21, 2020 |
| HP            | Pavilion 15                 | Notebook    | [d9c1a66672](https://linux-hardware.org/?probe=d9c1a66672) | Aug 20, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f6678c3632](https://linux-hardware.org/?probe=f6678c3632) | Aug 17, 2020 |
| Lenovo        | ThinkPad E420 1141DAS       | Notebook    | [ab579f2102](https://linux-hardware.org/?probe=ab579f2102) | Aug 17, 2020 |
| Lenovo        | ThinkPad E420 1141DAS       | Notebook    | [d4beb495bd](https://linux-hardware.org/?probe=d4beb495bd) | Aug 17, 2020 |
| PCPartner     | G43-F71862                  | Desktop     | [6f7db25de0](https://linux-hardware.org/?probe=6f7db25de0) | Aug 12, 2020 |
| Colorful T... | C.Q1900M PRO V20            | Desktop     | [55195790be](https://linux-hardware.org/?probe=55195790be) | Aug 10, 2020 |
| HP            | 82A5                        | Mini pc     | [1840b7c2d6](https://linux-hardware.org/?probe=1840b7c2d6) | Aug 10, 2020 |
| Acer          | Aspire Z1-601               | All in one  | [b3e778a640](https://linux-hardware.org/?probe=b3e778a640) | Aug 08, 2020 |
| AMI           | Cherry Trail CR             | Desktop     | [69e0a22aed](https://linux-hardware.org/?probe=69e0a22aed) | Aug 07, 2020 |
| Gigabyte      | H310M H x.x                 | Desktop     | [8067b679a3](https://linux-hardware.org/?probe=8067b679a3) | Aug 06, 2020 |
| ZOTAC         | ZBOXNANO-AD10               | Mini pc     | [80da000793](https://linux-hardware.org/?probe=80da000793) | Aug 06, 2020 |
| ASUSTek       | FX503VD                     | Notebook    | [26ce95f067](https://linux-hardware.org/?probe=26ce95f067) | Aug 03, 2020 |
| MSI           | H61M-P20                    | Desktop     | [594f095da2](https://linux-hardware.org/?probe=594f095da2) | Aug 02, 2020 |
| HP            | 82DC 1100                   | All in one  | [34270155d0](https://linux-hardware.org/?probe=34270155d0) | Aug 01, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [467112cf04](https://linux-hardware.org/?probe=467112cf04) | Jul 31, 2020 |
| Acer          | One S1003                   | Tablet      | [9a705bc331](https://linux-hardware.org/?probe=9a705bc331) | Jul 30, 2020 |
| HP            | ProBook 440 G3              | Notebook    | [9a34cb7ec7](https://linux-hardware.org/?probe=9a34cb7ec7) | Jul 28, 2020 |
| Acer          | Aspire ES1-572              | Notebook    | [1db75aee39](https://linux-hardware.org/?probe=1db75aee39) | Jul 27, 2020 |
| Acer          | Aspire R3-431T              | Notebook    | [b3bc6f8d90](https://linux-hardware.org/?probe=b3bc6f8d90) | Jul 24, 2020 |
| HP            | Pavilion 15                 | Notebook    | [7410d46ef8](https://linux-hardware.org/?probe=7410d46ef8) | Jul 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [dbb48c14f0](https://linux-hardware.org/?probe=dbb48c14f0) | Jul 22, 2020 |
| HP            | Notebook                    | Notebook    | [431d1d1482](https://linux-hardware.org/?probe=431d1d1482) | Jul 22, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [3216dbc594](https://linux-hardware.org/?probe=3216dbc594) | Jul 18, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f8c9b50bc3](https://linux-hardware.org/?probe=f8c9b50bc3) | Jul 18, 2020 |
| Sony          | VGN-FW360TJ                 | Notebook    | [8b037cac91](https://linux-hardware.org/?probe=8b037cac91) | Jul 18, 2020 |
| Acer          | One S1003                   | Tablet      | [7cdd981945](https://linux-hardware.org/?probe=7cdd981945) | Jul 16, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Dell          | 0GDG8Y A00                  | Desktop     | [a1fb518075](https://linux-hardware.org/?probe=a1fb518075) | Jul 12, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [f53c9923c4](https://linux-hardware.org/?probe=f53c9923c4) | Jul 11, 2020 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8bb25da515](https://linux-hardware.org/?probe=8bb25da515) | Jul 09, 2020 |
| HP            | Presario CQ43               | Notebook    | [48fe8649ca](https://linux-hardware.org/?probe=48fe8649ca) | Jul 08, 2020 |
| HP            | Presario CQ43               | Notebook    | [db6a9d6546](https://linux-hardware.org/?probe=db6a9d6546) | Jul 06, 2020 |
| HP            | ProBook 4440s               | Notebook    | [48a7e1a88c](https://linux-hardware.org/?probe=48a7e1a88c) | Jul 05, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [bd30f237dd](https://linux-hardware.org/?probe=bd30f237dd) | Jul 05, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [06da0a5ed7](https://linux-hardware.org/?probe=06da0a5ed7) | Jul 05, 2020 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [07a40e042c](https://linux-hardware.org/?probe=07a40e042c) | Jul 02, 2020 |
| Acer          | Aspire ES1-331              | Notebook    | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [4788e05f08](https://linux-hardware.org/?probe=4788e05f08) | Jul 01, 2020 |
| HP            | ProBook 640 G1              | Notebook    | [1a2462dee7](https://linux-hardware.org/?probe=1a2462dee7) | Jul 01, 2020 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [d33d8295b1](https://linux-hardware.org/?probe=d33d8295b1) | Jun 29, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [8b9bb2543f](https://linux-hardware.org/?probe=8b9bb2543f) | Jun 28, 2020 |
| Corporativ... | LX4SI                       | Notebook    | [3a15f8865d](https://linux-hardware.org/?probe=3a15f8865d) | Jun 26, 2020 |
| ASUSTek       | X450LN                      | Notebook    | [347ebd88a5](https://linux-hardware.org/?probe=347ebd88a5) | Jun 25, 2020 |
| ASUSTek       | X450LN                      | Notebook    | [10dd68f147](https://linux-hardware.org/?probe=10dd68f147) | Jun 25, 2020 |
| Corporativ... | LX4SI                       | Notebook    | [f9e67e8a5f](https://linux-hardware.org/?probe=f9e67e8a5f) | Jun 25, 2020 |
| HP            | 240 G6 Notebook PC          | Notebook    | [c43e5357b0](https://linux-hardware.org/?probe=c43e5357b0) | Jun 24, 2020 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [ee35b699fa](https://linux-hardware.org/?probe=ee35b699fa) | Jun 24, 2020 |
| Packard Be... | DOT S                       | Notebook    | [d2cd9b2728](https://linux-hardware.org/?probe=d2cd9b2728) | Jun 24, 2020 |
| Lenovo        | IdeaPad 500-14ISK 80NS      | Notebook    | [1af5a3043b](https://linux-hardware.org/?probe=1af5a3043b) | Jun 23, 2020 |
| HP            | ProBook 430 G2              | Notebook    | [d988a74820](https://linux-hardware.org/?probe=d988a74820) | Jun 23, 2020 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | Notebook    | [0fbefbc62c](https://linux-hardware.org/?probe=0fbefbc62c) | Jun 21, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [646f93ec3a](https://linux-hardware.org/?probe=646f93ec3a) | Jun 20, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [08ce018dd0](https://linux-hardware.org/?probe=08ce018dd0) | Jun 20, 2020 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | Notebook    | [a281f8c305](https://linux-hardware.org/?probe=a281f8c305) | Jun 19, 2020 |
| MSI           | MS-7379                     | Desktop     | [b7f52ad261](https://linux-hardware.org/?probe=b7f52ad261) | Jun 18, 2020 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [90725b3c8a](https://linux-hardware.org/?probe=90725b3c8a) | Jun 18, 2020 |
| HP            | 245 G4 Notebook PC          | Notebook    | [4f96cc852f](https://linux-hardware.org/?probe=4f96cc852f) | Jun 18, 2020 |
| HP            | 245 G4 Notebook PC          | Notebook    | [2c0356727d](https://linux-hardware.org/?probe=2c0356727d) | Jun 18, 2020 |
| Dell          | Inspiron 3420               | Notebook    | [5101d0c83c](https://linux-hardware.org/?probe=5101d0c83c) | Jun 17, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [c83e4c2dd8](https://linux-hardware.org/?probe=c83e4c2dd8) | Jun 15, 2020 |
| Lenovo        | IdeaPad Z470                | Notebook    | [7167c9a1eb](https://linux-hardware.org/?probe=7167c9a1eb) | Jun 10, 2020 |
| Elo TouchS... | ESY1XDX                     | Desktop     | [64aded4262](https://linux-hardware.org/?probe=64aded4262) | Jun 09, 2020 |
| Packard Be... | ENNS11HR                    | Notebook    | [952d5d4772](https://linux-hardware.org/?probe=952d5d4772) | Jun 05, 2020 |
| HP            | ProBook 4440s               | Notebook    | [730e093bc4](https://linux-hardware.org/?probe=730e093bc4) | Jun 05, 2020 |
| HP            | 0AA8h                       | Desktop     | [2f692488e5](https://linux-hardware.org/?probe=2f692488e5) | Jun 05, 2020 |
| HP            | 0AA8h                       | Desktop     | [1ee6fa5fb7](https://linux-hardware.org/?probe=1ee6fa5fb7) | Jun 03, 2020 |
| HP            | 0AA8h                       | Desktop     | [3226f7a8da](https://linux-hardware.org/?probe=3226f7a8da) | Jun 03, 2020 |
| Acer          | Aspire V5-132               | Notebook    | [44a89c002a](https://linux-hardware.org/?probe=44a89c002a) | Jun 02, 2020 |
| Acer          | Aspire V5-132               | Notebook    | [5b82f8d7d3](https://linux-hardware.org/?probe=5b82f8d7d3) | Jun 02, 2020 |
| Elo TouchS... | ESY1XDX                     | Desktop     | [467adf2413](https://linux-hardware.org/?probe=467adf2413) | Jun 01, 2020 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [fbccea1bb2](https://linux-hardware.org/?probe=fbccea1bb2) | May 29, 2020 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [6661e20292](https://linux-hardware.org/?probe=6661e20292) | May 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [9a867c7a5b](https://linux-hardware.org/?probe=9a867c7a5b) | May 28, 2020 |
| Dell          | Latitude E7450              | Notebook    | [c3eab25bca](https://linux-hardware.org/?probe=c3eab25bca) | May 28, 2020 |
| Gigabyte      | GA-MA790FX-DS5              | Desktop     | [bc3ed232f3](https://linux-hardware.org/?probe=bc3ed232f3) | May 28, 2020 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [9fac55b56b](https://linux-hardware.org/?probe=9fac55b56b) | May 28, 2020 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [9403cfc9c4](https://linux-hardware.org/?probe=9403cfc9c4) | May 27, 2020 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [216a9db389](https://linux-hardware.org/?probe=216a9db389) | May 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [38e63a05e2](https://linux-hardware.org/?probe=38e63a05e2) | May 26, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [f894499ac3](https://linux-hardware.org/?probe=f894499ac3) | May 26, 2020 |
| HP            | OMEN by Laptop              | Notebook    | [6cea5aa3fd](https://linux-hardware.org/?probe=6cea5aa3fd) | May 26, 2020 |
| HP            | OMEN by Laptop              | Notebook    | [a621749c2d](https://linux-hardware.org/?probe=a621749c2d) | May 26, 2020 |
| Acer          | ES1-111M                    | Notebook    | [53e45e403c](https://linux-hardware.org/?probe=53e45e403c) | May 23, 2020 |
| Olidata       | Unknown                     | Desktop     | [4d13b52bae](https://linux-hardware.org/?probe=4d13b52bae) | May 23, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9216a7cd89](https://linux-hardware.org/?probe=9216a7cd89) | May 21, 2020 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [fae71925c5](https://linux-hardware.org/?probe=fae71925c5) | May 21, 2020 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [aa6df4c02b](https://linux-hardware.org/?probe=aa6df4c02b) | May 21, 2020 |
| Acer          | Aspire 4739Z                | Notebook    | [f51ee0fe5a](https://linux-hardware.org/?probe=f51ee0fe5a) | May 20, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [910d27523a](https://linux-hardware.org/?probe=910d27523a) | May 20, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [ffe1142072](https://linux-hardware.org/?probe=ffe1142072) | May 19, 2020 |
| Acer          | Aspire A114-32              | Notebook    | [35ddb37c29](https://linux-hardware.org/?probe=35ddb37c29) | May 17, 2020 |
| Acer          | Aspire E5-551G              | Notebook    | [cda77789ec](https://linux-hardware.org/?probe=cda77789ec) | May 17, 2020 |
| Acer          | Aspire E5-551G              | Notebook    | [ee3ddbe726](https://linux-hardware.org/?probe=ee3ddbe726) | May 17, 2020 |
| Dell          | Latitude E6420              | Notebook    | [46a7b9904a](https://linux-hardware.org/?probe=46a7b9904a) | May 17, 2020 |
| Dell          | Latitude E6420              | Notebook    | [15d9716666](https://linux-hardware.org/?probe=15d9716666) | May 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [55850d2bd2](https://linux-hardware.org/?probe=55850d2bd2) | May 17, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [f170547556](https://linux-hardware.org/?probe=f170547556) | May 16, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [65292593ee](https://linux-hardware.org/?probe=65292593ee) | May 15, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | Notebook    | [fd09b801b7](https://linux-hardware.org/?probe=fd09b801b7) | May 14, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [825d07d907](https://linux-hardware.org/?probe=825d07d907) | May 14, 2020 |
| Dell          | Precision 7520              | Notebook    | [bf1d29844b](https://linux-hardware.org/?probe=bf1d29844b) | May 13, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [917741e728](https://linux-hardware.org/?probe=917741e728) | May 13, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | Notebook    | [8006d3f65a](https://linux-hardware.org/?probe=8006d3f65a) | May 12, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | Notebook    | [9767ed89e1](https://linux-hardware.org/?probe=9767ed89e1) | May 12, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f15c21aabd](https://linux-hardware.org/?probe=f15c21aabd) | May 11, 2020 |
| Toshiba       | NB505                       | Notebook    | [26eaa80c8a](https://linux-hardware.org/?probe=26eaa80c8a) | May 10, 2020 |
| ASUSTek       | TP203NA                     | Convertible | [b6fc10efa8](https://linux-hardware.org/?probe=b6fc10efa8) | May 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [ebf32d4cbf](https://linux-hardware.org/?probe=ebf32d4cbf) | May 08, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6f3a5a041d](https://linux-hardware.org/?probe=6f3a5a041d) | May 08, 2020 |
| ASUSTek       | K50AB                       | Notebook    | [ac598fedba](https://linux-hardware.org/?probe=ac598fedba) | May 06, 2020 |
| ASUSTek       | K50AB                       | Notebook    | [9e3de662ae](https://linux-hardware.org/?probe=9e3de662ae) | May 06, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [3abae5c4a3](https://linux-hardware.org/?probe=3abae5c4a3) | May 05, 2020 |
| ASUSTek       | TP203NA                     | Convertible | [54a0fffbbb](https://linux-hardware.org/?probe=54a0fffbbb) | May 05, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [b995e0664a](https://linux-hardware.org/?probe=b995e0664a) | May 03, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6ccb883203](https://linux-hardware.org/?probe=6ccb883203) | May 02, 2020 |
| Intel         | D54250WYK H13922-304        | Desktop     | [cc19077417](https://linux-hardware.org/?probe=cc19077417) | May 01, 2020 |
| HP            | ElitePad 1000 G2            | Notebook    | [40df66d7b8](https://linux-hardware.org/?probe=40df66d7b8) | Apr 29, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [111e5e4411](https://linux-hardware.org/?probe=111e5e4411) | Apr 29, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [d6abc4c56c](https://linux-hardware.org/?probe=d6abc4c56c) | Apr 29, 2020 |
| ECS           | A740GM-M                    | Desktop     | [8af834c918](https://linux-hardware.org/?probe=8af834c918) | Apr 28, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [c814274f99](https://linux-hardware.org/?probe=c814274f99) | Apr 27, 2020 |
| HP            | 240 G6 Notebook PC          | Notebook    | [542ddefbc5](https://linux-hardware.org/?probe=542ddefbc5) | Apr 25, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [a105a62c55](https://linux-hardware.org/?probe=a105a62c55) | Apr 23, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [3fd8a137d5](https://linux-hardware.org/?probe=3fd8a137d5) | Apr 21, 2020 |
| HP            | 240 G6 Notebook PC          | Notebook    | [e96b3b2ace](https://linux-hardware.org/?probe=e96b3b2ace) | Apr 21, 2020 |
| HP            | 240 G6 Notebook PC          | Notebook    | [5058e946ea](https://linux-hardware.org/?probe=5058e946ea) | Apr 21, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [a7e6d42571](https://linux-hardware.org/?probe=a7e6d42571) | Apr 21, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [384b1e8269](https://linux-hardware.org/?probe=384b1e8269) | Apr 20, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [57feb728c2](https://linux-hardware.org/?probe=57feb728c2) | Apr 19, 2020 |
| Toshiba       | NB505                       | Notebook    | [174dd8b4cd](https://linux-hardware.org/?probe=174dd8b4cd) | Apr 16, 2020 |
| HP            | ENVY 15                     | Notebook    | [d38936efb2](https://linux-hardware.org/?probe=d38936efb2) | Apr 16, 2020 |
| Toshiba       | NB505                       | Notebook    | [a28c9ef432](https://linux-hardware.org/?probe=a28c9ef432) | Apr 12, 2020 |
| HP            | Pavilion g4                 | Notebook    | [ee7f720be3](https://linux-hardware.org/?probe=ee7f720be3) | Apr 12, 2020 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [309b26e9a7](https://linux-hardware.org/?probe=309b26e9a7) | Apr 12, 2020 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [ca7cea286a](https://linux-hardware.org/?probe=ca7cea286a) | Apr 12, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [bdf169950d](https://linux-hardware.org/?probe=bdf169950d) | Apr 10, 2020 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [9411f4e22a](https://linux-hardware.org/?probe=9411f4e22a) | Apr 09, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [cf13d07d7d](https://linux-hardware.org/?probe=cf13d07d7d) | Apr 08, 2020 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [77cf46ddde](https://linux-hardware.org/?probe=77cf46ddde) | Apr 06, 2020 |
| Toshiba       | NB505                       | Notebook    | [c52e8296ad](https://linux-hardware.org/?probe=c52e8296ad) | Apr 06, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cc0d36466f](https://linux-hardware.org/?probe=cc0d36466f) | Apr 06, 2020 |
| HP            | Notebook                    | Notebook    | [60ebb42480](https://linux-hardware.org/?probe=60ebb42480) | Apr 05, 2020 |
| HP            | Notebook                    | Notebook    | [6102146f30](https://linux-hardware.org/?probe=6102146f30) | Apr 04, 2020 |
| Toshiba       | Satellite P745D             | Notebook    | [82c4813a13](https://linux-hardware.org/?probe=82c4813a13) | Apr 02, 2020 |
| Toshiba       | Satellite P745D             | Notebook    | [dd172e55aa](https://linux-hardware.org/?probe=dd172e55aa) | Apr 02, 2020 |
| Toshiba       | Satellite P745D             | Notebook    | [a04d4d7bcb](https://linux-hardware.org/?probe=a04d4d7bcb) | Apr 02, 2020 |
| HP            | 250 G5 Notebook PC          | Notebook    | [ccc351f3a5](https://linux-hardware.org/?probe=ccc351f3a5) | Apr 01, 2020 |
| ASUSTek       | X580VD                      | Notebook    | [e8c7cfc3af](https://linux-hardware.org/?probe=e8c7cfc3af) | Mar 31, 2020 |
| ECS           | A780GM-A                    | Desktop     | [3530b26663](https://linux-hardware.org/?probe=3530b26663) | Mar 30, 2020 |
| Lenovo        | ThinkPad T410 2537M82       | Notebook    | [7c71cd5a53](https://linux-hardware.org/?probe=7c71cd5a53) | Mar 30, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [54fd8a8ef3](https://linux-hardware.org/?probe=54fd8a8ef3) | Mar 27, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [872a291771](https://linux-hardware.org/?probe=872a291771) | Mar 26, 2020 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [62d04b32f4](https://linux-hardware.org/?probe=62d04b32f4) | Mar 25, 2020 |
| ASUSTek       | X455LAB                     | Notebook    | [cfe6c04671](https://linux-hardware.org/?probe=cfe6c04671) | Mar 19, 2020 |
| Acer          | Aspire 4332                 | Notebook    | [1ffe28f950](https://linux-hardware.org/?probe=1ffe28f950) | Mar 19, 2020 |
| Acer          | Aspire 4332                 | Notebook    | [4ef79a9f26](https://linux-hardware.org/?probe=4ef79a9f26) | Mar 19, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [d512b89622](https://linux-hardware.org/?probe=d512b89622) | Mar 13, 2020 |
| Acer          | TravelMate P258-M           | Notebook    | [6275f9d007](https://linux-hardware.org/?probe=6275f9d007) | Feb 22, 2020 |
| Samsung       | 450R4E/450R5E/450R4V/450... | Notebook    | [6e0ef2fa11](https://linux-hardware.org/?probe=6e0ef2fa11) | Feb 22, 2020 |
| Samsung       | 450R4E/450R5E/450R4V/450... | Notebook    | [152883e525](https://linux-hardware.org/?probe=152883e525) | Feb 22, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [811ba67ee3](https://linux-hardware.org/?probe=811ba67ee3) | Feb 21, 2020 |
| HP            | 245 G5 Notebook PC          | Notebook    | [ecbab8f357](https://linux-hardware.org/?probe=ecbab8f357) | Feb 19, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fec78461bd](https://linux-hardware.org/?probe=fec78461bd) | Feb 18, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ab20239127](https://linux-hardware.org/?probe=ab20239127) | Feb 09, 2020 |
| Samsung       | R540/R580/R780/SA41/E452    | Notebook    | [b72d68e62c](https://linux-hardware.org/?probe=b72d68e62c) | Jan 31, 2020 |
| Sony          | VPCEG20EL                   | Notebook    | [d2ac041c40](https://linux-hardware.org/?probe=d2ac041c40) | Jan 22, 2020 |
| HP            | Presario CQ56               | Notebook    | [cafdaff7c6](https://linux-hardware.org/?probe=cafdaff7c6) | Jan 16, 2020 |
| AMI           | Unknown                     | Notebook    | [4d89af9f9b](https://linux-hardware.org/?probe=4d89af9f9b) | Jan 16, 2020 |
| ECS           | A960M-MV                    | Desktop     | [b5991a8181](https://linux-hardware.org/?probe=b5991a8181) | Jan 13, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [ba1b65c973](https://linux-hardware.org/?probe=ba1b65c973) | Jan 13, 2020 |
| Acer          | Aspire E3-111               | Notebook    | [87473b8d1c](https://linux-hardware.org/?probe=87473b8d1c) | Jan 07, 2020 |
| Dell          | Latitude E7440              | Notebook    | [de95222539](https://linux-hardware.org/?probe=de95222539) | Dec 28, 2019 |
| Insyde        | CherryTrail                 | Notebook    | [9f7a2725e5](https://linux-hardware.org/?probe=9f7a2725e5) | Dec 07, 2019 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ad5138a45f](https://linux-hardware.org/?probe=ad5138a45f) | Dec 04, 2019 |
| Dell          | Latitude E5470              | Notebook    | [5bf1258e74](https://linux-hardware.org/?probe=5bf1258e74) | Dec 03, 2019 |
| HP            | 245 G5 Notebook PC          | Notebook    | [8c201c4443](https://linux-hardware.org/?probe=8c201c4443) | Nov 30, 2019 |
| ASUSTek       | FX503VD                     | Notebook    | [f5dc0694e1](https://linux-hardware.org/?probe=f5dc0694e1) | Nov 28, 2019 |
| ASUSTek       | X406UAR                     | Notebook    | [a1d52e4665](https://linux-hardware.org/?probe=a1d52e4665) | Nov 25, 2019 |
| ASUSTek       | FX503VD                     | Notebook    | [5f33fb689d](https://linux-hardware.org/?probe=5f33fb689d) | Nov 24, 2019 |
| MSI           | GS65 Stealth 9SF            | Notebook    | [dfb909840b](https://linux-hardware.org/?probe=dfb909840b) | Nov 22, 2019 |
| ASUSTek       | FX503VD                     | Notebook    | [a5ad247bdc](https://linux-hardware.org/?probe=a5ad247bdc) | Nov 21, 2019 |
| Gigabyte      | G41MT-S2                    | Desktop     | [1b60792885](https://linux-hardware.org/?probe=1b60792885) | Nov 12, 2019 |
| ASUSTek       | E402NA                      | Notebook    | [07bf7c4021](https://linux-hardware.org/?probe=07bf7c4021) | Nov 10, 2019 |
| Toshiba       | Satellite L745              | Notebook    | [93ab04c913](https://linux-hardware.org/?probe=93ab04c913) | Nov 07, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [0e1f45ae13](https://linux-hardware.org/?probe=0e1f45ae13) | Oct 22, 2019 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [a0de23ca8b](https://linux-hardware.org/?probe=a0de23ca8b) | Oct 21, 2019 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [3f7beb5458](https://linux-hardware.org/?probe=3f7beb5458) | Oct 20, 2019 |
| Intel         | DG31PR AAD97573-204         | Desktop     | [3ca8dab2bd](https://linux-hardware.org/?probe=3ca8dab2bd) | Oct 14, 2019 |
| ASUSTek       | H81M-A                      | Desktop     | [dbb29527ff](https://linux-hardware.org/?probe=dbb29527ff) | Oct 08, 2019 |
| ASUSTek       | H81M-A                      | Desktop     | [3337b6ddbf](https://linux-hardware.org/?probe=3337b6ddbf) | Oct 08, 2019 |
| ASUSTek       | FX503VD                     | Notebook    | [f95cd75d9e](https://linux-hardware.org/?probe=f95cd75d9e) | Oct 08, 2019 |
| Dell          | Inspiron 5421               | Notebook    | [0403587941](https://linux-hardware.org/?probe=0403587941) | Oct 05, 2019 |
| Dell          | Inspiron 5570               | Notebook    | [3fec0285f1](https://linux-hardware.org/?probe=3fec0285f1) | Oct 05, 2019 |
| HP            | Pavilion 15                 | Notebook    | [c6002f59ca](https://linux-hardware.org/?probe=c6002f59ca) | Oct 02, 2019 |
| OX            | PC-9890166 D0.05T45.18.1... | Notebook    | [75abcb1b69](https://linux-hardware.org/?probe=75abcb1b69) | Sep 29, 2019 |
| OX            | PC-9890166 D0.05T45.18.1... | Notebook    | [9c2460c5e0](https://linux-hardware.org/?probe=9c2460c5e0) | Sep 29, 2019 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [711b77b300](https://linux-hardware.org/?probe=711b77b300) | Sep 28, 2019 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5cebf9dcc4](https://linux-hardware.org/?probe=5cebf9dcc4) | Sep 25, 2019 |
| Acer          | Aspire 4736Z                | Notebook    | [a1a9c940fb](https://linux-hardware.org/?probe=a1a9c940fb) | Sep 22, 2019 |
| Sony          | VGN-NR330FE                 | Notebook    | [71126383fe](https://linux-hardware.org/?probe=71126383fe) | Sep 20, 2019 |
| Dell          | Latitude E6420              | Notebook    | [683f31db53](https://linux-hardware.org/?probe=683f31db53) | Sep 19, 2019 |
| HP            | G42                         | Notebook    | [5addde0384](https://linux-hardware.org/?probe=5addde0384) | Sep 15, 2019 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [e8a0b17de8](https://linux-hardware.org/?probe=e8a0b17de8) | Sep 13, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [45a420f97b](https://linux-hardware.org/?probe=45a420f97b) | Sep 12, 2019 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [6cbeb4c5dd](https://linux-hardware.org/?probe=6cbeb4c5dd) | Sep 10, 2019 |
| HP            | Unknown                     | Notebook    | [f4e6748e0d](https://linux-hardware.org/?probe=f4e6748e0d) | Sep 06, 2019 |
| Creative V... | C14CT series                | Notebook    | [fe141371eb](https://linux-hardware.org/?probe=fe141371eb) | Sep 04, 2019 |
| ASUSTek       | B75M-A                      | Desktop     | [58ec049231](https://linux-hardware.org/?probe=58ec049231) | Sep 04, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [407ab6ce27](https://linux-hardware.org/?probe=407ab6ce27) | Aug 26, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [48697f4bda](https://linux-hardware.org/?probe=48697f4bda) | Aug 22, 2019 |
| OEM           | V40SI2                      | Notebook    | [0ef7e2c60f](https://linux-hardware.org/?probe=0ef7e2c60f) | Aug 22, 2019 |
| ASUSTek       | P5QC                        | Desktop     | [441e7f2005](https://linux-hardware.org/?probe=441e7f2005) | Aug 19, 2019 |
| ASUSTek       | P5QC                        | Desktop     | [68e31b6013](https://linux-hardware.org/?probe=68e31b6013) | Aug 19, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [017c004a48](https://linux-hardware.org/?probe=017c004a48) | Aug 12, 2019 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [43fd056268](https://linux-hardware.org/?probe=43fd056268) | Aug 11, 2019 |
| ASUSTek       | FX503VD                     | Notebook    | [b4d34b6e82](https://linux-hardware.org/?probe=b4d34b6e82) | Aug 09, 2019 |
| Acer          | Swift SF314-52G             | Notebook    | [39291bfee6](https://linux-hardware.org/?probe=39291bfee6) | Aug 06, 2019 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [db521911e3](https://linux-hardware.org/?probe=db521911e3) | Aug 06, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [f82cbc8005](https://linux-hardware.org/?probe=f82cbc8005) | Aug 05, 2019 |
| ECS           | A960M-MV                    | Desktop     | [4a3c832524](https://linux-hardware.org/?probe=4a3c832524) | Aug 05, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f416d66db4](https://linux-hardware.org/?probe=f416d66db4) | Jul 31, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [71e60872ea](https://linux-hardware.org/?probe=71e60872ea) | Jul 31, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0ab5bf5b1a](https://linux-hardware.org/?probe=0ab5bf5b1a) | Jul 27, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [11487c8b52](https://linux-hardware.org/?probe=11487c8b52) | Jul 26, 2019 |
| HP            | Notebook                    | Notebook    | [8ec780e92f](https://linux-hardware.org/?probe=8ec780e92f) | Jul 18, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [7875ecd5a5](https://linux-hardware.org/?probe=7875ecd5a5) | Jul 17, 2019 |
| Dell          | Inspiron 3437               | Notebook    | [30c4e0f323](https://linux-hardware.org/?probe=30c4e0f323) | Jul 16, 2019 |
| Lenovo        | ThinkPad E420 1141RH3       | Notebook    | [72424367ad](https://linux-hardware.org/?probe=72424367ad) | Jul 07, 2019 |
| Samsung       | R430/P430                   | Notebook    | [ec62fdb035](https://linux-hardware.org/?probe=ec62fdb035) | Jul 04, 2019 |
| Toshiba       | Satellite L515              | Notebook    | [3832002e7f](https://linux-hardware.org/?probe=3832002e7f) | Jul 01, 2019 |
| MSI           | X399 SLI PLUS               | Desktop     | [db1a79ac69](https://linux-hardware.org/?probe=db1a79ac69) | Jun 29, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [e97a9cf2c6](https://linux-hardware.org/?probe=e97a9cf2c6) | Jun 29, 2019 |
| Dell          | Latitude E6420              | Notebook    | [3cf5c7994e](https://linux-hardware.org/?probe=3cf5c7994e) | Jun 24, 2019 |
| Sony          | SVF14325CLW                 | Notebook    | [67abaeea89](https://linux-hardware.org/?probe=67abaeea89) | Jun 20, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [e333e77665](https://linux-hardware.org/?probe=e333e77665) | Jun 18, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [dc8d42d5d1](https://linux-hardware.org/?probe=dc8d42d5d1) | Jun 15, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [b189962fa8](https://linux-hardware.org/?probe=b189962fa8) | Jun 14, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [3166cd0be4](https://linux-hardware.org/?probe=3166cd0be4) | Jun 14, 2019 |
| Acer          | Aspire E1-422               | Notebook    | [8ba524cf2d](https://linux-hardware.org/?probe=8ba524cf2d) | Jun 14, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [b08781392f](https://linux-hardware.org/?probe=b08781392f) | Jun 13, 2019 |
| ASUSTek       | X302LJ                      | Notebook    | [ca06e39372](https://linux-hardware.org/?probe=ca06e39372) | Jun 11, 2019 |
| ASUSTek       | X302LJ                      | Notebook    | [38ba3bc487](https://linux-hardware.org/?probe=38ba3bc487) | Jun 11, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [872526f7f7](https://linux-hardware.org/?probe=872526f7f7) | Jun 10, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [fcc5af7203](https://linux-hardware.org/?probe=fcc5af7203) | Jun 10, 2019 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [461345008c](https://linux-hardware.org/?probe=461345008c) | Jun 10, 2019 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [4421365140](https://linux-hardware.org/?probe=4421365140) | Jun 10, 2019 |
| ASUSTek       | X302LJ                      | Notebook    | [96aa51f787](https://linux-hardware.org/?probe=96aa51f787) | Jun 09, 2019 |
| ASUSTek       | X302LJ                      | Notebook    | [b1c95fbf3d](https://linux-hardware.org/?probe=b1c95fbf3d) | Jun 09, 2019 |
| Apple         | MacBookPro9,2               | Notebook    | [6819d18bc8](https://linux-hardware.org/?probe=6819d18bc8) | Jun 08, 2019 |
| HP            | 0AA8h                       | Desktop     | [6d02866e6c](https://linux-hardware.org/?probe=6d02866e6c) | Jun 05, 2019 |
| ASUSTek       | FX503VD                     | Notebook    | [b8b7156cd0](https://linux-hardware.org/?probe=b8b7156cd0) | Jun 04, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [09ccaf8ccf](https://linux-hardware.org/?probe=09ccaf8ccf) | Jun 03, 2019 |
| Lenovo        | ThinkPad T450 20BUS1DH00    | Notebook    | [3686a559e0](https://linux-hardware.org/?probe=3686a559e0) | May 28, 2019 |
| MSI           | B250M GAMING PRO            | Desktop     | [a935e6e9c7](https://linux-hardware.org/?probe=a935e6e9c7) | May 27, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [10159a71f6](https://linux-hardware.org/?probe=10159a71f6) | May 25, 2019 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [d1f1be1b36](https://linux-hardware.org/?probe=d1f1be1b36) | May 24, 2019 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [77f0aad272](https://linux-hardware.org/?probe=77f0aad272) | May 24, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [5e20d7d4e0](https://linux-hardware.org/?probe=5e20d7d4e0) | May 20, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [bc3ec67a48](https://linux-hardware.org/?probe=bc3ec67a48) | May 20, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [329c7ece42](https://linux-hardware.org/?probe=329c7ece42) | May 20, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [1988815ca4](https://linux-hardware.org/?probe=1988815ca4) | May 20, 2019 |
| HP            | 0AA8h                       | Desktop     | [f2fbc75122](https://linux-hardware.org/?probe=f2fbc75122) | May 16, 2019 |
| Dell          | Inspiron M5040              | Notebook    | [6621280c03](https://linux-hardware.org/?probe=6621280c03) | May 14, 2019 |
| MSI           | H61M-P31/W8                 | Desktop     | [915fd7548f](https://linux-hardware.org/?probe=915fd7548f) | May 13, 2019 |
| HP            | ProBook 5330m               | Notebook    | [79b5425192](https://linux-hardware.org/?probe=79b5425192) | May 11, 2019 |
| HP            | 0AA8h                       | Desktop     | [f0d1f05c8e](https://linux-hardware.org/?probe=f0d1f05c8e) | May 10, 2019 |
| ECS           | A780LM-M                    | Desktop     | [ca438dd2a7](https://linux-hardware.org/?probe=ca438dd2a7) | May 08, 2019 |
| HP            | EliteBook 8470p             | Notebook    | [9489581964](https://linux-hardware.org/?probe=9489581964) | May 08, 2019 |
| HP            | EliteBook 8470p             | Notebook    | [55b280af12](https://linux-hardware.org/?probe=55b280af12) | May 07, 2019 |
| HP            | 2B1F                        | All in one  | [f01e3c859d](https://linux-hardware.org/?probe=f01e3c859d) | May 07, 2019 |
| HP            | 2B1F                        | All in one  | [912fb9c119](https://linux-hardware.org/?probe=912fb9c119) | May 07, 2019 |
| Gigabyte      | A320M-S2H                   | Desktop     | [b4d5cdee78](https://linux-hardware.org/?probe=b4d5cdee78) | May 07, 2019 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [c780e50507](https://linux-hardware.org/?probe=c780e50507) | May 05, 2019 |
| Gigabyte      | EP45-DS3R                   | Desktop     | [8c9b60b665](https://linux-hardware.org/?probe=8c9b60b665) | May 01, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [2d0e845055](https://linux-hardware.org/?probe=2d0e845055) | May 01, 2019 |
| Dell          | Inspiron M5040              | Notebook    | [bc2495b50a](https://linux-hardware.org/?probe=bc2495b50a) | May 01, 2019 |
| Dell          | Inspiron M5040              | Notebook    | [17879a2dfc](https://linux-hardware.org/?probe=17879a2dfc) | May 01, 2019 |
| Dell          | 0GXM1W A02                  | Desktop     | [3841c32f4a](https://linux-hardware.org/?probe=3841c32f4a) | May 01, 2019 |
| Dell          | 0GXM1W A02                  | Desktop     | [e9c14efd74](https://linux-hardware.org/?probe=e9c14efd74) | Apr 30, 2019 |
| HP            | Presario V3000 (GG542LA#... | Notebook    | [e964514e68](https://linux-hardware.org/?probe=e964514e68) | Apr 28, 2019 |
| Pegatron      | 2AA1h                       | Desktop     | [df47c88db6](https://linux-hardware.org/?probe=df47c88db6) | Apr 23, 2019 |
| Pegatron      | 2AA1h                       | Desktop     | [70922676a8](https://linux-hardware.org/?probe=70922676a8) | Apr 23, 2019 |
| Pegatron      | 2AA1h                       | Desktop     | [07c7ac4546](https://linux-hardware.org/?probe=07c7ac4546) | Apr 23, 2019 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [37ced39aa5](https://linux-hardware.org/?probe=37ced39aa5) | Apr 23, 2019 |
| Dell          | Inspiron M5040              | Notebook    | [bfc540e551](https://linux-hardware.org/?probe=bfc540e551) | Apr 20, 2019 |
| Dell          | Inspiron M5040              | Notebook    | [6833cf2d42](https://linux-hardware.org/?probe=6833cf2d42) | Apr 20, 2019 |
| MSI           | A58M-E33                    | Desktop     | [987015c03b](https://linux-hardware.org/?probe=987015c03b) | Apr 18, 2019 |
| HP            | 14                          | Notebook    | [fb281475c9](https://linux-hardware.org/?probe=fb281475c9) | Apr 15, 2019 |
| HP            | 14                          | Notebook    | [178f0eb4e7](https://linux-hardware.org/?probe=178f0eb4e7) | Apr 15, 2019 |
| HP            | ENVY m6                     | Notebook    | [4180a07245](https://linux-hardware.org/?probe=4180a07245) | Apr 13, 2019 |
| HP            | 1000                        | Notebook    | [82d8e28c9e](https://linux-hardware.org/?probe=82d8e28c9e) | Apr 13, 2019 |
| HP            | 1000                        | Notebook    | [445d946c9f](https://linux-hardware.org/?probe=445d946c9f) | Apr 12, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [01b46e3429](https://linux-hardware.org/?probe=01b46e3429) | Apr 10, 2019 |
| Sony          | SVE11115ELB                 | Notebook    | [8cd5213bb6](https://linux-hardware.org/?probe=8cd5213bb6) | Apr 10, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [ca36723635](https://linux-hardware.org/?probe=ca36723635) | Apr 10, 2019 |
| Toshiba       | Satellite L305              | Notebook    | [e39a1f246e](https://linux-hardware.org/?probe=e39a1f246e) | Mar 31, 2019 |
| Acer          | Aspire ES1-433G             | Notebook    | [e667efbc30](https://linux-hardware.org/?probe=e667efbc30) | Mar 24, 2019 |
| HP            | ENVY 14                     | Notebook    | [6c4e6833ab](https://linux-hardware.org/?probe=6c4e6833ab) | Mar 24, 2019 |
| HP            | EliteBook 8530w             | Notebook    | [3f7f390254](https://linux-hardware.org/?probe=3f7f390254) | Mar 24, 2019 |
| Lenovo        | G40-70 20369                | Notebook    | [663bc4d39a](https://linux-hardware.org/?probe=663bc4d39a) | Mar 23, 2019 |
| HP            | Mini 110-1000               | Notebook    | [e718456945](https://linux-hardware.org/?probe=e718456945) | Mar 20, 2019 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [f4b4b7905c](https://linux-hardware.org/?probe=f4b4b7905c) | Mar 13, 2019 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [d317fbeb81](https://linux-hardware.org/?probe=d317fbeb81) | Mar 11, 2019 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | Notebook    | [bb2ab44009](https://linux-hardware.org/?probe=bb2ab44009) | Feb 26, 2019 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | Notebook    | [fff09a2435](https://linux-hardware.org/?probe=fff09a2435) | Feb 26, 2019 |
| Toshiba       | Satellite L305              | Notebook    | [b8b1e3027d](https://linux-hardware.org/?probe=b8b1e3027d) | Feb 17, 2019 |
| HP            | 0B4Ch D                     | Desktop     | [8dc7a1b1e8](https://linux-hardware.org/?probe=8dc7a1b1e8) | Feb 14, 2019 |
| Quanta        | 2AC7 011                    | Desktop     | [7a9d5af1ce](https://linux-hardware.org/?probe=7a9d5af1ce) | Jan 27, 2019 |
| Quanta        | 2AC7 011                    | Desktop     | [a2533c8043](https://linux-hardware.org/?probe=a2533c8043) | Jan 27, 2019 |
| Unknown       | Unknown                     | Notebook    | [e0bb4e4cb4](https://linux-hardware.org/?probe=e0bb4e4cb4) | Jan 14, 2019 |
| ASUSTek       | F2A85-M LE                  | Desktop     | [efbf81762c](https://linux-hardware.org/?probe=efbf81762c) | Jan 09, 2019 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [09848aacf0](https://linux-hardware.org/?probe=09848aacf0) | Dec 26, 2018 |
| Toshiba       | Satellite L305              | Notebook    | [9e67a0eae4](https://linux-hardware.org/?probe=9e67a0eae4) | Dec 22, 2018 |
| HP            | Mini 110-1000               | Notebook    | [69af53ff8e](https://linux-hardware.org/?probe=69af53ff8e) | Dec 21, 2018 |
| HP            | 245 G5 Notebook PC          | Notebook    | [20db28aad6](https://linux-hardware.org/?probe=20db28aad6) | Dec 08, 2018 |
| Dell          | Latitude E6400              | Notebook    | [719eebfabf](https://linux-hardware.org/?probe=719eebfabf) | Nov 20, 2018 |
| Dell          | Latitude E6400              | Notebook    | [99cbd8eb33](https://linux-hardware.org/?probe=99cbd8eb33) | Nov 10, 2018 |
| Dell          | Latitude E6400              | Notebook    | [6078573db4](https://linux-hardware.org/?probe=6078573db4) | Nov 10, 2018 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [7f0c38474e](https://linux-hardware.org/?probe=7f0c38474e) | Oct 29, 2018 |
| HP            | Laptop 15-da0xxx            | Notebook    | [88bdb4e503](https://linux-hardware.org/?probe=88bdb4e503) | Oct 27, 2018 |
| HP            | Laptop 15-da0xxx            | Notebook    | [19b85d2469](https://linux-hardware.org/?probe=19b85d2469) | Oct 27, 2018 |
| ASUSTek       | P5KC                        | Desktop     | [8ee7c3b1f4](https://linux-hardware.org/?probe=8ee7c3b1f4) | Sep 23, 2018 |
| Apple         | MacBookPro9,2               | Notebook    | [ce4d1a0c42](https://linux-hardware.org/?probe=ce4d1a0c42) | Apr 01, 2018 |
| HP            | Pavilion dv4                | Notebook    | [fead4bde0c](https://linux-hardware.org/?probe=fead4bde0c) | Nov 04, 2017 |
| HP            | Pavilion dv4                | Notebook    | [43c72d9707](https://linux-hardware.org/?probe=43c72d9707) | Oct 26, 2017 |
| Dell          | Precision M6400             | Notebook    | [d399313d03](https://linux-hardware.org/?probe=d399313d03) | Oct 24, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 95        | 13.79%  |
| Ubuntu 18.04                 | 74        | 10.74%  |
| Ubuntu 19.04                 | 22        | 3.19%   |
| Arch                         | 22        | 3.19%   |
| OpenMandriva 4.2             | 19        | 2.76%   |
| Debian 10                    | 17        | 2.47%   |
| Fedora 34                    | 16        | 2.32%   |
| Manjaro                      | 15        | 2.18%   |
| Linux Mint 20.1              | 15        | 2.18%   |
| Zorin 15                     | 14        | 2.03%   |
| Fedora 35                    | 14        | 2.03%   |
| Zorin 16                     | 13        | 1.89%   |
| Pop!_OS 20.04                | 13        | 1.89%   |
| Ubuntu 19.10                 | 12        | 1.74%   |
| KDE neon 20.04               | 12        | 1.74%   |
| Ubuntu 21.10                 | 11        | 1.6%    |
| Ubuntu 20.10                 | 11        | 1.6%    |
| Fedora 32                    | 11        | 1.6%    |
| Debian 11                    | 11        | 1.6%    |
| Ubuntu 22.04                 | 10        | 1.45%   |
| OpenMandriva 4.3             | 10        | 1.45%   |
| Fedora 33                    | 10        | 1.45%   |
| Ubuntu 21.04                 | 9         | 1.31%   |
| Pop!_OS 20.10                | 8         | 1.16%   |
| Linux Mint 19.3              | 8         | 1.16%   |
| Debian Testing               | 8         | 1.16%   |
| Arch Rolling                 | 8         | 1.16%   |
| ROSA R10                     | 7         | 1.02%   |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 1.02%   |
| Linux Mint 20                | 7         | 1.02%   |
| Fedora 36                    | 7         | 1.02%   |
| Ubuntu 18.10                 | 6         | 0.87%   |
| Ubuntu 16.04                 | 6         | 0.87%   |
| Linux Mint 20.2              | 6         | 0.87%   |
| Kubuntu 20.04                | 6         | 0.87%   |
| ArcoLinux Rolling            | 6         | 0.87%   |
| Pop!_OS 22.04                | 5         | 0.73%   |
| Pop!_OS 21.10                | 5         | 0.73%   |
| Linux Mint 19.1              | 5         | 0.73%   |
| KDE neon 18.04               | 5         | 0.73%   |
| Xubuntu 20.04                | 4         | 0.58%   |
| Elementary 6.1               | 4         | 0.58%   |
| Xubuntu 18.04                | 3         | 0.44%   |
| Ubuntu MATE 20.04            | 3         | 0.44%   |
| Ubuntu MATE 18.04            | 3         | 0.44%   |
| ROSA R11                     | 3         | 0.44%   |
| Pop!_OS 21.04                | 3         | 0.44%   |
| Linux Mint 20.3              | 3         | 0.44%   |
| Linux Mint 19.2              | 3         | 0.44%   |
| Ubuntu Budgie 21.04          | 2         | 0.29%   |
| Ubuntu Budgie 20.04          | 2         | 0.29%   |
| ROSA R9                      | 2         | 0.29%   |
| OpenMandriva 4.50            | 2         | 0.29%   |
| MX 19                        | 2         | 0.29%   |
| Manjaro 21.0                 | 2         | 0.29%   |
| Lubuntu 20.04                | 2         | 0.29%   |
| Lubuntu 18.04                | 2         | 0.29%   |
| LMDE 5                       | 2         | 0.29%   |
| LMDE 4                       | 2         | 0.29%   |
| Kubuntu 19.10                | 2         | 0.29%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu            | 252       | 38.01%  |
| Fedora            | 52        | 7.84%   |
| Linux Mint        | 46        | 6.94%   |
| Debian            | 35        | 5.28%   |
| Pop!_OS           | 34        | 5.13%   |
| OpenMandriva      | 30        | 4.52%   |
| Arch              | 30        | 4.52%   |
| Zorin             | 28        | 4.22%   |
| Manjaro           | 21        | 3.17%   |
| KDE neon          | 17        | 2.56%   |
| ROSA              | 14        | 2.11%   |
| Xubuntu           | 9         | 1.36%   |
| Kubuntu           | 8         | 1.21%   |
| Elementary        | 8         | 1.21%   |
| openSUSE          | 7         | 1.06%   |
| Endless           | 7         | 1.06%   |
| Ubuntu MATE       | 6         | 0.9%    |
| Lubuntu           | 6         | 0.9%    |
| ArcoLinux         | 6         | 0.9%    |
| Clear Linux       | 5         | 0.75%   |
| Ubuntu Budgie     | 4         | 0.6%    |
| LMDE              | 4         | 0.6%    |
| Deepin            | 4         | 0.6%    |
| Kali              | 3         | 0.45%   |
| Gentoo            | 3         | 0.45%   |
| Solus             | 2         | 0.3%    |
| MX                | 2         | 0.3%    |
| Linux Lite        | 2         | 0.3%    |
| GNOME OS          | 2         | 0.3%    |
| CentOS            | 2         | 0.3%    |
| Ultramarine Linux | 1         | 0.15%   |
| Sparky            | 1         | 0.15%   |
| Slackware         | 1         | 0.15%   |
| RHEL              | 1         | 0.15%   |
| Reborn OS         | 1         | 0.15%   |
| Parrot            | 1         | 0.15%   |
| LinuxFX           | 1         | 0.15%   |
| Garuda Linux      | 1         | 0.15%   |
| Feren OS          | 1         | 0.15%   |
| EndeavourOS       | 1         | 0.15%   |
| BlackPanther      | 1         | 0.15%   |
| Artix             | 1         | 0.15%   |
| antiX             | 1         | 0.15%   |
| antergos          | 1         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 17        | 2.28%   |
| 5.4.0-42-generic                | 13        | 1.74%   |
| 5.16.7-desktop-1omv4003         | 10        | 1.34%   |
| 5.4.0-26-generic                | 9         | 1.21%   |
| 5.0.0-13-generic                | 9         | 1.21%   |
| 5.8.0-50-generic                | 8         | 1.07%   |
| 5.8.0-48-generic                | 8         | 1.07%   |
| 5.4.0-58-generic                | 8         | 1.07%   |
| 5.4.0-48-generic                | 7         | 0.94%   |
| 5.4.0-47-generic                | 7         | 0.94%   |
| 5.11.0-27-generic               | 7         | 0.94%   |
| 5.0.0-23-generic                | 7         | 0.94%   |
| 4.18.0-15-generic               | 7         | 0.94%   |
| 5.4.0-56-generic                | 6         | 0.8%    |
| 5.4.0-52-generic                | 6         | 0.8%    |
| 5.4.0-29-generic                | 6         | 0.8%    |
| 5.11.0-37-generic               | 6         | 0.8%    |
| 5.4.0-77-generic                | 5         | 0.67%   |
| 5.4.0-72-generic                | 5         | 0.67%   |
| 5.4.0-37-generic                | 5         | 0.67%   |
| 5.4.0-33-generic                | 5         | 0.67%   |
| 5.3.0-53-generic                | 5         | 0.67%   |
| 5.3.0-46-generic                | 5         | 0.67%   |
| 5.3.0-42-generic                | 5         | 0.67%   |
| 5.13.0-30-generic               | 5         | 0.67%   |
| 5.11.0-7614-generic             | 5         | 0.67%   |
| 5.0.0-32-generic                | 5         | 0.67%   |
| 5.0.0-27-generic                | 5         | 0.67%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 5         | 0.67%   |
| 4.18.0-18-generic               | 5         | 0.67%   |
| 4.18.0-17-generic               | 5         | 0.67%   |
| 5.9.16-1-MANJARO                | 4         | 0.54%   |
| 5.8.0-59-generic                | 4         | 0.54%   |
| 5.8.0-43-generic                | 4         | 0.54%   |
| 5.4.0-7634-generic              | 4         | 0.54%   |
| 5.4.0-73-generic                | 4         | 0.54%   |
| 5.4.0-70-generic                | 4         | 0.54%   |
| 5.4.0-66-generic                | 4         | 0.54%   |
| 5.4.0-28-generic                | 4         | 0.54%   |
| 5.3.0-51-generic                | 4         | 0.54%   |
| 5.15.0-41-generic               | 4         | 0.54%   |
| 5.15.0-39-generic               | 4         | 0.54%   |
| 5.14.0-12.1-liquorix-amd64      | 4         | 0.54%   |
| 5.11.0-41-generic               | 4         | 0.54%   |
| 5.11.0-34-generic               | 4         | 0.54%   |
| 5.0.0-29-generic                | 4         | 0.54%   |
| 4.19.0-12-amd64                 | 4         | 0.54%   |
| 4.15.0-20-generic               | 4         | 0.54%   |
| 5.8.0-55-generic                | 3         | 0.4%    |
| 5.8.0-44-generic                | 3         | 0.4%    |
| 5.4.0-91-generic                | 3         | 0.4%    |
| 5.4.0-89-generic                | 3         | 0.4%    |
| 5.4.0-65-generic                | 3         | 0.4%    |
| 5.4.0-59-generic                | 3         | 0.4%    |
| 5.4.0-53-generic                | 3         | 0.4%    |
| 5.4.0-39-generic                | 3         | 0.4%    |
| 5.3.0-40-generic                | 3         | 0.4%    |
| 5.3.0-23-generic                | 3         | 0.4%    |
| 5.17.13-300.fc36.x86_64         | 3         | 0.4%    |
| 5.13.0-21-generic               | 3         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 146       | 20.65%  |
| 5.11.0  | 49        | 6.93%   |
| 5.8.0   | 47        | 6.65%   |
| 5.0.0   | 45        | 6.36%   |
| 4.15.0  | 40        | 5.66%   |
| 5.3.0   | 38        | 5.37%   |
| 5.13.0  | 28        | 3.96%   |
| 4.18.0  | 27        | 3.82%   |
| 5.10.14 | 17        | 2.4%    |
| 5.15.0  | 16        | 2.26%   |
| 5.10.0  | 15        | 2.12%   |
| 4.19.0  | 13        | 1.84%   |
| 5.16.7  | 10        | 1.41%   |
| 5.14.0  | 9         | 1.27%   |
| 5.9.16  | 6         | 0.85%   |
| 4.9.60  | 6         | 0.85%   |
| 5.8.12  | 4         | 0.57%   |
| 5.17.5  | 4         | 0.57%   |
| 5.16.11 | 4         | 0.57%   |
| 5.13.13 | 4         | 0.57%   |
| 5.12.0  | 4         | 0.57%   |
| 5.9.1   | 3         | 0.42%   |
| 5.5.0   | 3         | 0.42%   |
| 5.18.10 | 3         | 0.42%   |
| 5.17.4  | 3         | 0.42%   |
| 5.17.3  | 3         | 0.42%   |
| 5.17.13 | 3         | 0.42%   |
| 5.13.19 | 3         | 0.42%   |
| 5.13.12 | 3         | 0.42%   |
| 5.11.6  | 3         | 0.42%   |
| 5.11.12 | 3         | 0.42%   |
| 5.11.10 | 3         | 0.42%   |
| 4.4.0   | 3         | 0.42%   |
| 5.9.8   | 2         | 0.28%   |
| 5.9.0   | 2         | 0.28%   |
| 5.7.6   | 2         | 0.28%   |
| 5.6.11  | 2         | 0.28%   |
| 5.6.0   | 2         | 0.28%   |
| 5.18.9  | 2         | 0.28%   |
| 5.18.1  | 2         | 0.28%   |
| 5.17.0  | 2         | 0.28%   |
| 5.16.18 | 2         | 0.28%   |
| 5.16.16 | 2         | 0.28%   |
| 5.15.23 | 2         | 0.28%   |
| 5.15.15 | 2         | 0.28%   |
| 5.14.15 | 2         | 0.28%   |
| 5.12.6  | 2         | 0.28%   |
| 5.12.11 | 2         | 0.28%   |
| 5.11.22 | 2         | 0.28%   |
| 5.11.14 | 2         | 0.28%   |
| 5.11.11 | 2         | 0.28%   |
| 5.10.9  | 2         | 0.28%   |
| 4.9.124 | 2         | 0.28%   |
| 5.9.9   | 1         | 0.14%   |
| 5.9.6   | 1         | 0.14%   |
| 5.9.3   | 1         | 0.14%   |
| 5.9.10  | 1         | 0.14%   |
| 5.8.10  | 1         | 0.14%   |
| 5.7.8   | 1         | 0.14%   |
| 5.7.10  | 1         | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 152       | 21.78%  |
| 5.11    | 66        | 9.46%   |
| 5.10    | 53        | 7.59%   |
| 5.8     | 52        | 7.45%   |
| 5.0     | 48        | 6.88%   |
| 5.13    | 44        | 6.3%    |
| 5.3     | 40        | 5.73%   |
| 4.15    | 40        | 5.73%   |
| 4.18    | 28        | 4.01%   |
| 5.16    | 24        | 3.44%   |
| 5.15    | 24        | 3.44%   |
| 5.17    | 19        | 2.72%   |
| 5.14    | 17        | 2.44%   |
| 5.9     | 16        | 2.29%   |
| 5.12    | 15        | 2.15%   |
| 4.19    | 14        | 2.01%   |
| 4.9     | 10        | 1.43%   |
| 5.18    | 9         | 1.29%   |
| 5.6     | 7         | 1%      |
| 5.5     | 6         | 0.86%   |
| 5.7     | 4         | 0.57%   |
| 4.4     | 4         | 0.57%   |
| 5.1     | 3         | 0.43%   |
| 4.13    | 1         | 0.14%   |
| 3.10    | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 630       | 96.92%  |
| i686    | 18        | 2.77%   |
| aarch64 | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 301       | 45.2%   |
| Unknown         | 107       | 16.07%  |
| KDE5            | 74        | 11.11%  |
| XFCE            | 41        | 6.16%   |
| X-Cinnamon      | 39        | 5.86%   |
| KDE             | 28        | 4.2%    |
| MATE            | 11        | 1.65%   |
| KDE4            | 10        | 1.5%    |
| Pantheon        | 8         | 1.2%    |
| i3              | 8         | 1.2%    |
| Budgie          | 8         | 1.2%    |
| Cinnamon        | 7         | 1.05%   |
| LXQt            | 4         | 0.6%    |
| Deepin          | 4         | 0.6%    |
| Unity           | 3         | 0.45%   |
| LXDE            | 3         | 0.45%   |
| xmonad          | 2         | 0.3%    |
| qtile           | 2         | 0.3%    |
| GNOME Flashback | 2         | 0.3%    |
| Trinity         | 1         | 0.15%   |
| icewm           | 1         | 0.15%   |
| bspwm           | 1         | 0.15%   |
| awesome         | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 514       | 77.64%  |
| Wayland | 78        | 11.78%  |
| Unknown | 65        | 9.82%   |
| Tty     | 5         | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 425       | 63.91%  |
| GDM     | 76        | 11.43%  |
| SDDM    | 66        | 9.92%   |
| LightDM | 34        | 5.11%   |
| TDM     | 26        | 3.91%   |
| GDM3    | 22        | 3.31%   |
| KDM     | 10        | 1.5%    |
| XDM     | 4         | 0.6%    |
| SLIMSKI | 1         | 0.15%   |
| LXDM    | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_CL      | 342       | 51.74%  |
| en_US      | 133       | 20.12%  |
| Unknown    | 110       | 16.64%  |
| es_ES      | 37        | 5.6%    |
| es_MX      | 8         | 1.21%   |
| en_GB      | 8         | 1.21%   |
| C          | 8         | 1.21%   |
| fr_FR      | 2         | 0.3%    |
| es_VE      | 2         | 0.3%    |
| es_AR      | 2         | 0.3%    |
| ru_RU      | 1         | 0.15%   |
| pt_BR      | 1         | 0.15%   |
| nl_NL      | 1         | 0.15%   |
| es_UY      | 1         | 0.15%   |
| es_CO      | 1         | 0.15%   |
| es_CL.UTF8 | 1         | 0.15%   |
| es_BO      | 1         | 0.15%   |
| en_CA      | 1         | 0.15%   |
| de_DE      | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 329       | 50.08%  |
| EFI  | 328       | 49.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 526       | 79.82%  |
| Btrfs   | 49        | 7.44%   |
| Unknown | 40        | 6.07%   |
| Overlay | 30        | 4.55%   |
| Xfs     | 6         | 0.91%   |
| Ext2    | 4         | 0.61%   |
| Zfs     | 3         | 0.46%   |
| Ext3    | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 449       | 67.82%  |
| GPT     | 161       | 24.32%  |
| MBR     | 52        | 7.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 591       | 89.95%  |
| Yes       | 66        | 10.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 468       | 70.59%  |
| Yes       | 195       | 29.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Hewlett-Packard           | 152       | 23.42%  |
| ASUSTek Computer          | 99        | 15.25%  |
| Lenovo                    | 85        | 13.1%   |
| Dell                      | 56        | 8.63%   |
| Acer                      | 41        | 6.32%   |
| MSI                       | 36        | 5.55%   |
| Samsung Electronics       | 23        | 3.54%   |
| Gigabyte Technology       | 21        | 3.24%   |
| Intel                     | 17        | 2.62%   |
| Toshiba                   | 16        | 2.47%   |
| Apple                     | 14        | 2.16%   |
| Sony                      | 13        | 2%      |
| ECS                       | 9         | 1.39%   |
| Unknown                   | 9         | 1.39%   |
| Packard Bell              | 8         | 1.23%   |
| HUAWEI                    | 5         | 0.77%   |
| ASRock                    | 4         | 0.62%   |
| Pegatron                  | 3         | 0.46%   |
| TPV-INVENTA               | 2         | 0.31%   |
| Huanan                    | 2         | 0.31%   |
| Chuwi                     | 2         | 0.31%   |
| AMI                       | 2         | 0.31%   |
| ZOTAC                     | 1         | 0.15%   |
| Supermicro                | 1         | 0.15%   |
| Raspberry Pi Foundation   | 1         | 0.15%   |
| R-StyleComputers          | 1         | 0.15%   |
| Quanta                    | 1         | 0.15%   |
| Positivo                  | 1         | 0.15%   |
| Personal Computer Factory | 1         | 0.15%   |
| PCPartner                 | 1         | 0.15%   |
| OX                        | 1         | 0.15%   |
| Olidata                   | 1         | 0.15%   |
| OEM                       | 1         | 0.15%   |
| Nvidia                    | 1         | 0.15%   |
| Medion                    | 1         | 0.15%   |
| MACHINIST                 | 1         | 0.15%   |
| LG Electronics            | 1         | 0.15%   |
| Insyde                    | 1         | 0.15%   |
| IBM                       | 1         | 0.15%   |
| HONOR                     | 1         | 0.15%   |
| HC                        | 1         | 0.15%   |
| Google                    | 1         | 0.15%   |
| Foxconn                   | 1         | 0.15%   |
| eMachines                 | 1         | 0.15%   |
| Elo TouchSystems          | 1         | 0.15%   |
| Elife                     | 1         | 0.15%   |
| Creative Vision           | 1         | 0.15%   |
| Corporativo Lanix         | 1         | 0.15%   |
| Colorful Technology       | 1         | 0.15%   |
| Clevo                     | 1         | 0.15%   |
| BESSTAR Tech              | 1         | 0.15%   |
| Alienware                 | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                           | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Unknown                                        | 14        | 2.16%   |
| HP Notebook                                    | 10        | 1.54%   |
| HP Pavilion Notebook                           | 6         | 0.92%   |
| HP 240 G6 Notebook PC                          | 6         | 0.92%   |
| ASUS All Series                                | 6         | 0.92%   |
| HP Pavilion 15                                 | 4         | 0.62%   |
| HP ENVY 15                                     | 4         | 0.62%   |
| ASUS PRIME B450M-A                             | 4         | 0.62%   |
| MSI MS-7A34                                    | 3         | 0.46%   |
| MSI MS-7817                                    | 3         | 0.46%   |
| MSI MS-7788                                    | 3         | 0.46%   |
| Lenovo Legion Y530-15ICH 81FV                  | 3         | 0.46%   |
| HP ProBook 440 G3                              | 3         | 0.46%   |
| HP Pavilion g4                                 | 3         | 0.46%   |
| HP EliteBook 840 G6                            | 3         | 0.46%   |
| HP EliteBook 2560p                             | 3         | 0.46%   |
| HP 14                                          | 3         | 0.46%   |
| HP 1000                                        | 3         | 0.46%   |
| Dell Latitude E6420                            | 3         | 0.46%   |
| Dell Inspiron 14-3467                          | 3         | 0.46%   |
| ASUS PRIME A320M-K                             | 3         | 0.46%   |
| Apple MacBookPro9,2                            | 3         | 0.46%   |
| Acer Aspire ES1-111M                           | 3         | 0.46%   |
| Toshiba Satellite L745                         | 2         | 0.31%   |
| Toshiba Satellite C845D                        | 2         | 0.31%   |
| Samsung RF511/RF411/RF711                      | 2         | 0.31%   |
| Samsung 750XED                                 | 2         | 0.31%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV | 2         | 0.31%   |
| Packard Bell EasyNote MH35                     | 2         | 0.31%   |
| MSI Pro 3000/3080                              | 2         | 0.31%   |
| MSI MS-7A65                                    | 2         | 0.31%   |
| Lenovo Y520-15IKBN 80WK                        | 2         | 0.31%   |
| Lenovo MIIX 310-10ICR 80SG                     | 2         | 0.31%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY           | 2         | 0.31%   |
| Lenovo IdeaPad 720S-14IKB 80XC                 | 2         | 0.31%   |
| Lenovo IdeaPad 330S-15ARR 81FB                 | 2         | 0.31%   |
| Lenovo IdeaPad 320-15ABR 80XS                  | 2         | 0.31%   |
| Lenovo G400 20235                              | 2         | 0.31%   |
| HUAWEI BOHK-WAX9X                              | 2         | 0.31%   |
| HP ProBook 640 G1                              | 2         | 0.31%   |
| HP Pavilion Laptop 15-eh0xxx                   | 2         | 0.31%   |
| HP Pavilion Laptop 15-cw1xxx                   | 2         | 0.31%   |
| HP Pavilion Laptop 15-cw0xxx                   | 2         | 0.31%   |
| HP Pavilion dv4                                | 2         | 0.31%   |
| HP Laptop 15-da0xxx                            | 2         | 0.31%   |
| HP Laptop 15-bs0xx                             | 2         | 0.31%   |
| HP ENVY x360 Convertible 13-ag0xxx             | 2         | 0.31%   |
| HP ENVY 17 Leap Motion SE NB PC                | 2         | 0.31%   |
| HP EliteBook 840 G5                            | 2         | 0.31%   |
| HP Compaq Pro 6300 SFF                         | 2         | 0.31%   |
| HP Compaq Pro 4300 SFF PC                      | 2         | 0.31%   |
| HP 250 G5 Notebook PC                          | 2         | 0.31%   |
| HP 245 G5 Notebook PC                          | 2         | 0.31%   |
| HP 15                                          | 2         | 0.31%   |
| Gigabyte B450M DS3H V2                         | 2         | 0.31%   |
| Gigabyte B450 AORUS PRO WIFI                   | 2         | 0.31%   |
| ECS MCP61M-M3                                  | 2         | 0.31%   |
| ECS A960M-MV                                   | 2         | 0.31%   |
| ECS A740GM-M                                   | 2         | 0.31%   |
| Dell Inspiron N5110                            | 2         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 34        | 5.24%   |
| HP Pavilion           | 34        | 5.24%   |
| Acer Aspire           | 30        | 4.62%   |
| Lenovo IdeaPad        | 27        | 4.16%   |
| Dell Inspiron         | 22        | 3.39%   |
| HP EliteBook          | 15        | 2.31%   |
| HP ENVY               | 14        | 2.16%   |
| Dell Latitude         | 14        | 2.16%   |
| ASUS PRIME            | 14        | 2.16%   |
| Unknown               | 14        | 2.16%   |
| Toshiba Satellite     | 12        | 1.85%   |
| HP ProBook            | 10        | 1.54%   |
| HP Notebook           | 10        | 1.54%   |
| HP Laptop             | 10        | 1.54%   |
| ASUS VivoBook         | 10        | 1.54%   |
| ASUS TUF              | 10        | 1.54%   |
| HP Compaq             | 8         | 1.23%   |
| HP 240                | 8         | 1.23%   |
| Packard Bell EasyNote | 6         | 0.92%   |
| HP 245                | 6         | 0.92%   |
| ASUS All              | 6         | 0.92%   |
| Acer Swift            | 6         | 0.92%   |
| Lenovo Legion         | 5         | 0.77%   |
| Dell Vostro           | 5         | 0.77%   |
| ASUS ZenBook          | 5         | 0.77%   |
| HP 250                | 4         | 0.62%   |
| Dell Precision        | 4         | 0.62%   |
| ASUS ROG              | 4         | 0.62%   |
| Toshiba PORTEGE       | 3         | 0.46%   |
| Samsung 300E5EV       | 3         | 0.46%   |
| MSI MS-7A34           | 3         | 0.46%   |
| MSI MS-7817           | 3         | 0.46%   |
| MSI MS-7788           | 3         | 0.46%   |
| Lenovo ThinkCentre    | 3         | 0.46%   |
| HP Presario           | 3         | 0.46%   |
| HP 14                 | 3         | 0.46%   |
| HP 1000               | 3         | 0.46%   |
| Gigabyte B450M        | 3         | 0.46%   |
| Dell XPS              | 3         | 0.46%   |
| ASUS M5A78L-M         | 3         | 0.46%   |
| ASUS ASUS             | 3         | 0.46%   |
| Apple MacBookPro9     | 3         | 0.46%   |
| Samsung RF511         | 2         | 0.31%   |
| Samsung 750XED        | 2         | 0.31%   |
| MSI Pro               | 2         | 0.31%   |
| MSI MS-7A65           | 2         | 0.31%   |
| Lenovo Y520-15IKBN    | 2         | 0.31%   |
| Lenovo MIIX           | 2         | 0.31%   |
| Lenovo IdeaPadFlex    | 2         | 0.31%   |
| Lenovo G400           | 2         | 0.31%   |
| Intel D54250WYK       | 2         | 0.31%   |
| HUAWEI BOHK-WAX9X     | 2         | 0.31%   |
| Huanan X79            | 2         | 0.31%   |
| HP Spectre            | 2         | 0.31%   |
| HP ProDesk            | 2         | 0.31%   |
| HP EliteDesk          | 2         | 0.31%   |
| HP 15                 | 2         | 0.31%   |
| Gigabyte B450         | 2         | 0.31%   |
| ECS MCP61M-M3         | 2         | 0.31%   |
| ECS A960M-MV          | 2         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2017    | 71        | 10.94%  |
| 2018    | 60        | 9.24%   |
| 2020    | 59        | 9.09%   |
| 2012    | 56        | 8.63%   |
| 2011    | 56        | 8.63%   |
| 2013    | 54        | 8.32%   |
| 2019    | 52        | 8.01%   |
| 2014    | 44        | 6.78%   |
| 2016    | 37        | 5.7%    |
| 2015    | 37        | 5.7%    |
| 2010    | 29        | 4.47%   |
| 2008    | 25        | 3.85%   |
| 2009    | 22        | 3.39%   |
| 2007    | 22        | 3.39%   |
| 2021    | 19        | 2.93%   |
| 2022    | 3         | 0.46%   |
| 2006    | 1         | 0.15%   |
| 2005    | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 435       | 67.03%  |
| Desktop        | 177       | 27.27%  |
| Convertible    | 12        | 1.85%   |
| All in one     | 8         | 1.23%   |
| Mini pc        | 7         | 1.08%   |
| Tablet         | 6         | 0.92%   |
| Server         | 3         | 0.46%   |
| System on chip | 1         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 591       | 90.23%  |
| Enabled  | 64        | 9.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 648       | 99.85%  |
| Yes  | 1         | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 180       | 27.48%  |
| 3.01-4.0    | 146       | 22.29%  |
| 8.01-16.0   | 126       | 19.24%  |
| 16.01-24.0  | 94        | 14.35%  |
| 1.01-2.0    | 40        | 6.11%   |
| 32.01-64.0  | 36        | 5.5%    |
| 2.01-3.0    | 14        | 2.14%   |
| 24.01-32.0  | 12        | 1.83%   |
| 64.01-256.0 | 4         | 0.61%   |
| 0.51-1.0    | 2         | 0.31%   |
| Unknown     | 1         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 265       | 37.54%  |
| 2.01-3.0   | 178       | 25.21%  |
| 3.01-4.0   | 98        | 13.88%  |
| 4.01-8.0   | 95        | 13.46%  |
| 0.51-1.0   | 42        | 5.95%   |
| 8.01-16.0  | 21        | 2.97%   |
| 0.01-0.5   | 5         | 0.71%   |
| 24.01-32.0 | 1         | 0.14%   |
| Unknown    | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 436       | 66.26%  |
| 2      | 158       | 24.01%  |
| 3      | 35        | 5.32%   |
| 4      | 17        | 2.58%   |
| 0      | 6         | 0.91%   |
| 5      | 4         | 0.61%   |
| 7      | 1         | 0.15%   |
| 6      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 414       | 63.69%  |
| Yes       | 236       | 36.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 573       | 88.15%  |
| No        | 77        | 11.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 544       | 83.82%  |
| No        | 105       | 16.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 411       | 62.84%  |
| No        | 243       | 37.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Chile   | 649       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Santiago            | 180       | 26.35%  |
| Las Condes          | 32        | 4.69%   |
| Viña del Mar       | 31        | 4.54%   |
| Puente Alto         | 28        | 4.1%    |
| Concepción         | 26        | 3.81%   |
| Maipu               | 25        | 3.66%   |
| La Florida          | 20        | 2.93%   |
| Nunoa               | 19        | 2.78%   |
| Temuco              | 18        | 2.64%   |
| Providencia         | 17        | 2.49%   |
| San Miguel          | 15        | 2.2%    |
| Antofagasta         | 13        | 1.9%    |
| Valdivia            | 12        | 1.76%   |
| La Serena           | 12        | 1.76%   |
| Port Montt          | 10        | 1.46%   |
| Coronel             | 9         | 1.32%   |
| Rancagua            | 8         | 1.17%   |
| Quilpué            | 8         | 1.17%   |
| Valparaíso         | 7         | 1.02%   |
| Los Ángeles        | 7         | 1.02%   |
| Iquique             | 7         | 1.02%   |
| Coquimbo            | 7         | 1.02%   |
| Colina              | 7         | 1.02%   |
| Penalolen           | 6         | 0.88%   |
| Osorno              | 6         | 0.88%   |
| Vitacura            | 5         | 0.73%   |
| San Pedro de la Paz | 5         | 0.73%   |
| San Bernardo        | 5         | 0.73%   |
| El Bosque           | 5         | 0.73%   |
| Copiapó            | 5         | 0.73%   |
| Villa Alemana       | 4         | 0.59%   |
| Talcahuano          | 4         | 0.59%   |
| Melipilla           | 4         | 0.59%   |
| La Reina            | 4         | 0.59%   |
| Independencia       | 4         | 0.59%   |
| Curicó             | 4         | 0.59%   |
| Chillan             | 4         | 0.59%   |
| Central             | 4         | 0.59%   |
| Tome                | 3         | 0.44%   |
| Talca               | 3         | 0.44%   |
| Quillota            | 3         | 0.44%   |
| Quilicura           | 3         | 0.44%   |
| Punta Arenas        | 3         | 0.44%   |
| Puerto Natales      | 3         | 0.44%   |
| Pudahuel            | 3         | 0.44%   |
| Macul               | 3         | 0.44%   |
| Los Andes           | 3         | 0.44%   |
| La Cisterna         | 3         | 0.44%   |
| La Calera           | 3         | 0.44%   |
| Concon              | 3         | 0.44%   |
| Villa Alegre        | 2         | 0.29%   |
| Vallenar            | 2         | 0.29%   |
| San Joaquin         | 2         | 0.29%   |
| San Javier          | 2         | 0.29%   |
| Recoleta            | 2         | 0.29%   |
| Penaflor            | 2         | 0.29%   |
| Padre Las Casas     | 2         | 0.29%   |
| Molina              | 2         | 0.29%   |
| Lo Prado            | 2         | 0.29%   |
| Linares             | 2         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 176       | 250    | 20.37%  |
| Seagate                   | 129       | 168    | 14.93%  |
| Toshiba                   | 83        | 91     | 9.61%   |
| Kingston                  | 72        | 95     | 8.33%   |
| Samsung Electronics       | 69        | 91     | 7.99%   |
| Crucial                   | 55        | 67     | 6.37%   |
| Hitachi                   | 37        | 42     | 4.28%   |
| Unknown                   | 36        | 57     | 4.17%   |
| SanDisk                   | 34        | 35     | 3.94%   |
| HGST                      | 24        | 24     | 2.78%   |
| SK hynix                  | 18        | 19     | 2.08%   |
| Intel                     | 15        | 24     | 1.74%   |
| Apple                     | 12        | 12     | 1.39%   |
| Micron Technology         | 10        | 14     | 1.16%   |
| China                     | 9         | 12     | 1.04%   |
| Silicon Motion            | 8         | 8      | 0.93%   |
| KingSpec                  | 6         | 13     | 0.69%   |
| Corsair                   | 6         | 11     | 0.69%   |
| JMicron Technology        | 5         | 5      | 0.58%   |
| A-DATA Technology         | 5         | 7      | 0.58%   |
| XrayDisk                  | 3         | 3      | 0.35%   |
| XPG                       | 3         | 4      | 0.35%   |
| Micron/Crucial Technology | 3         | 6      | 0.35%   |
| LITEON                    | 3         | 3      | 0.35%   |
| Lexar                     | 3         | 7      | 0.35%   |
| KIOXIA                    | 3         | 4      | 0.35%   |
| WALRAM                    | 2         | 3      | 0.23%   |
| SSSTC                     | 2         | 2      | 0.23%   |
| Realtek Semiconductor     | 2         | 2      | 0.23%   |
| Netac                     | 2         | 2      | 0.23%   |
| Maxtor                    | 2         | 2      | 0.23%   |
| Mass                      | 2         | 2      | 0.23%   |
| Gigabyte Technology       | 2         | 2      | 0.23%   |
| Wdxsky                    | 1         | 1      | 0.12%   |
| Vaseky                    | 1         | 1      | 0.12%   |
| UMIS                      | 1         | 1      | 0.12%   |
| Transcend                 | 1         | 1      | 0.12%   |
| StoreJet                  | 1         | 1      | 0.12%   |
| Phison                    | 1         | 1      | 0.12%   |
| Patriot                   | 1         | 1      | 0.12%   |
| OCZ                       | 1         | 2      | 0.12%   |
| NGFF                      | 1         | 1      | 0.12%   |
| NE-1TB                    | 1         | 1      | 0.12%   |
| LITEONIT                  | 1         | 1      | 0.12%   |
| KingDian                  | 1         | 2      | 0.12%   |
| JASTER                    | 1         | 2      | 0.12%   |
| Intenso                   | 1         | 1      | 0.12%   |
| HUAWEI                    | 1         | 1      | 0.12%   |
| Hewlett-Packard           | 1         | 1      | 0.12%   |
| Fujitsu                   | 1         | 1      | 0.12%   |
| FORESEE                   | 1         | 2      | 0.12%   |
| Faspeed                   | 1         | 1      | 0.12%   |
| BIWIN                     | 1         | 1      | 0.12%   |
| ASMT                      | 1         | 1      | 0.12%   |
| ASMedia                   | 1         | 2      | 0.12%   |
| Unknown                   | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD    | 16        | 1.71%   |
| Kingston SA400S37240G 240GB SSD     | 14        | 1.5%    |
| Toshiba MQ01ABF050 500GB            | 13        | 1.39%   |
| Seagate ST1000LM035-1RK172 1TB      | 13        | 1.39%   |
| Seagate ST500DM002-1BD142 500GB     | 12        | 1.29%   |
| Unknown MMC Card  32GB              | 10        | 1.07%   |
| Kingston SA400S37480G 480GB SSD     | 10        | 1.07%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 9         | 0.96%   |
| Crucial CT240BX500SSD1 240GB        | 9         | 0.96%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 8         | 0.86%   |
| Toshiba MQ01ABD100 1TB              | 8         | 0.86%   |
| Toshiba HDWD110 1TB                 | 8         | 0.86%   |
| Toshiba DT01ACA100 1TB              | 8         | 0.86%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 0.86%   |
| Samsung NVMe SSD Drive 512GB        | 8         | 0.86%   |
| Crucial CT120BX500SSD1 120GB        | 8         | 0.86%   |
| WDC WD10EZEX-08WN4A0 1TB            | 7         | 0.75%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 7         | 0.75%   |
| SanDisk NVMe SSD Drive 500GB        | 7         | 0.75%   |
| Kingston SA400S37120G 120GB SSD     | 7         | 0.75%   |
| HGST HTS545050A7E680 500GB          | 7         | 0.75%   |
| Crucial CT480BX500SSD1 480GB        | 7         | 0.75%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 6         | 0.64%   |
| Unknown MMC Card  64GB              | 6         | 0.64%   |
| Toshiba MQ04ABF100 1TB              | 6         | 0.64%   |
| Intel NVMe SSD Drive 512GB          | 6         | 0.64%   |
| Crucial CT120BX300SSD1 120GB        | 6         | 0.64%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 5         | 0.54%   |
| WDC WD5000AAKX-001CA0 500GB         | 5         | 0.54%   |
| Toshiba MQ01ABD075 752GB            | 5         | 0.54%   |
| Seagate ST9500325AS 500GB           | 5         | 0.54%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 0.54%   |
| Seagate ST3500418AS 500GB           | 5         | 0.54%   |
| Samsung SSD 850 EVO 250GB           | 5         | 0.54%   |
| Samsung NVMe SSD Drive 1024GB       | 5         | 0.54%   |
| Hitachi HTS545050B9A300 500GB       | 5         | 0.54%   |
| Crucial CT500MX500SSD1 500GB        | 5         | 0.54%   |
| Crucial CT1000MX500SSD1 1TB         | 5         | 0.54%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 4         | 0.43%   |
| WDC WD10SPZX-60Z10T0 1TB            | 4         | 0.43%   |
| WDC WD10EZEX-00BN5A0 1TB            | 4         | 0.43%   |
| Unknown MMC Card  128GB             | 4         | 0.43%   |
| Toshiba MQ01ACF050 500GB            | 4         | 0.43%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 0.43%   |
| Seagate ST3320418AS 320GB           | 4         | 0.43%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 0.43%   |
| SanDisk NVMe SSD Drive 1TB          | 4         | 0.43%   |
| Samsung HN-M500MBB 500GB            | 4         | 0.43%   |
| Kingston SUV400S37240G 240GB SSD    | 4         | 0.43%   |
| HGST HTS541010B7E610 1TB            | 4         | 0.43%   |
| HGST HTS541010A9E680 1TB            | 4         | 0.43%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 3         | 0.32%   |
| WDC WDS250G2B0A-00SM50 250GB SSD    | 3         | 0.32%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD    | 3         | 0.32%   |
| WDC WDS120G1G0A-00SS50 120GB SSD    | 3         | 0.32%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 3         | 0.32%   |
| WDC WD5000LPCX-21VHAT0 500GB        | 3         | 0.32%   |
| WDC WD2500LPVX-22V0TT0 250GB        | 3         | 0.32%   |
| WDC WD10SPZX-75Z10T2 1TB            | 3         | 0.32%   |
| WDC WD10SPZX-24Z10 1TB              | 3         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 129       | 168    | 30.86%  |
| WDC                 | 127       | 166    | 30.38%  |
| Toshiba             | 77        | 82     | 18.42%  |
| Hitachi             | 37        | 42     | 8.85%   |
| HGST                | 24        | 24     | 5.74%   |
| Samsung Electronics | 11        | 15     | 2.63%   |
| Apple               | 8         | 8      | 1.91%   |
| Maxtor              | 2         | 2      | 0.48%   |
| Unknown             | 1         | 1      | 0.24%   |
| Fujitsu             | 1         | 1      | 0.24%   |
| ASMedia             | 1         | 2      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 62        | 76     | 22.55%  |
| Crucial             | 55        | 66     | 20%     |
| WDC                 | 52        | 69     | 18.91%  |
| Samsung Electronics | 27        | 29     | 9.82%   |
| SanDisk             | 15        | 15     | 5.45%   |
| China               | 9         | 12     | 3.27%   |
| KingSpec            | 6         | 13     | 2.18%   |
| Corsair             | 6         | 11     | 2.18%   |
| Micron Technology   | 4         | 4      | 1.45%   |
| Apple               | 4         | 4      | 1.45%   |
| Lexar               | 3         | 7      | 1.09%   |
| Intel               | 3         | 5      | 1.09%   |
| A-DATA Technology   | 3         | 5      | 1.09%   |
| XrayDisk            | 2         | 2      | 0.73%   |
| SK hynix            | 2         | 2      | 0.73%   |
| LITEON              | 2         | 2      | 0.73%   |
| Gigabyte Technology | 2         | 2      | 0.73%   |
| Wdxsky              | 1         | 1      | 0.36%   |
| WALRAM              | 1         | 1      | 0.36%   |
| Vaseky              | 1         | 1      | 0.36%   |
| Toshiba             | 1         | 4      | 0.36%   |
| StoreJet            | 1         | 1      | 0.36%   |
| Patriot             | 1         | 1      | 0.36%   |
| OCZ                 | 1         | 2      | 0.36%   |
| NGFF                | 1         | 1      | 0.36%   |
| Netac               | 1         | 1      | 0.36%   |
| LITEONIT            | 1         | 1      | 0.36%   |
| KingDian            | 1         | 2      | 0.36%   |
| Intenso             | 1         | 1      | 0.36%   |
| Hewlett-Packard     | 1         | 1      | 0.36%   |
| FORESEE             | 1         | 2      | 0.36%   |
| Faspeed             | 1         | 1      | 0.36%   |
| BIWIN               | 1         | 1      | 0.36%   |
| ASMT                | 1         | 1      | 0.36%   |
| Unknown             | 1         | 1      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 372       | 511    | 46.5%   |
| SSD     | 247       | 348    | 30.88%  |
| NVMe    | 135       | 189    | 16.88%  |
| MMC     | 34        | 54     | 4.25%   |
| Unknown | 12        | 13     | 1.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 540       | 853    | 74.59%  |
| NVMe | 132       | 186    | 18.23%  |
| MMC  | 34        | 54     | 4.7%    |
| SAS  | 18        | 22     | 2.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 401       | 583    | 65.85%  |
| 0.51-1.0   | 180       | 235    | 29.56%  |
| 1.01-2.0   | 20        | 27     | 3.28%   |
| 3.01-4.0   | 3         | 3      | 0.49%   |
| 2.01-3.0   | 3         | 8      | 0.49%   |
| 4.01-10.0  | 2         | 3      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 205       | 30.33%  |
| 101-250        | 177       | 26.18%  |
| 501-1000       | 99        | 14.64%  |
| 1-20           | 44        | 6.51%   |
| 51-100         | 40        | 5.92%   |
| 1001-2000      | 36        | 5.33%   |
| 21-50          | 28        | 4.14%   |
| More than 3000 | 17        | 2.51%   |
| 2001-3000      | 16        | 2.37%   |
| Unknown        | 14        | 2.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 288       | 41.2%   |
| 21-50          | 131       | 18.74%  |
| 101-250        | 86        | 12.3%   |
| 51-100         | 75        | 10.73%  |
| 251-500        | 49        | 7.01%   |
| 501-1000       | 31        | 4.43%   |
| 1001-2000      | 16        | 2.29%   |
| Unknown        | 14        | 2%      |
| More than 3000 | 6         | 0.86%   |
| 2001-3000      | 3         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB      | 3         | 3      | 5.36%   |
| HGST HTS545050A7E680 500GB           | 3         | 3      | 5.36%   |
| Hitachi HTS545050B9A300 500GB        | 2         | 2      | 3.57%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 2      | 3.57%   |
| XrayDisk SSD 256GB                   | 1         | 1      | 1.79%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 1      | 1.79%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 1      | 1.79%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1      | 1.79%   |
| WDC WD5000LPLX-60ZNTT1 500GB         | 1         | 1      | 1.79%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1      | 1.79%   |
| WDC WD5000AAKX-083CA1 500GB          | 1         | 1      | 1.79%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1         | 1      | 1.79%   |
| WDC WD5000AAKX-001CA0 500GB          | 1         | 2      | 1.79%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 1      | 1.79%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1      | 1.79%   |
| WDC WD10EARS-003BB1 1TB              | 1         | 1      | 1.79%   |
| Vaseky V820/1TB 1024GB               | 1         | 1      | 1.79%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 1.79%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 1.79%   |
| Toshiba MK1652GSX 160GB              | 1         | 1      | 1.79%   |
| Seagate ST9750420AS 752GB            | 1         | 1      | 1.79%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 1.79%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 1.79%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1         | 1      | 1.79%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB | 1         | 1      | 1.79%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 1      | 1.79%   |
| Seagate ST3500418AS 500GB            | 1         | 1      | 1.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 5      | 1.79%   |
| Samsung Electronics SSD 870 EVO 1TB  | 1         | 1      | 1.79%   |
| Samsung Electronics HD250HJ 250GB    | 1         | 2      | 1.79%   |
| Samsung Electronics HD081GJ 80GB     | 1         | 1      | 1.79%   |
| LITEON CV8-8E128-HP 128GB SSD        | 1         | 1      | 1.79%   |
| Kingston SVP200S3120G 120GB SSD      | 1         | 1      | 1.79%   |
| Kingston SA400S37480G 480GB SSD      | 1         | 1      | 1.79%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 1      | 1.79%   |
| Intel SSDSC2BX400G4R 400GB           | 1         | 2      | 1.79%   |
| Hitachi HTS722016K9A300 160GB        | 1         | 1      | 1.79%   |
| Hitachi HTS547564A9E384 640GB        | 1         | 2      | 1.79%   |
| Hitachi HTS547550A9E384 500GB        | 1         | 1      | 1.79%   |
| Hitachi HTS543232L9A300 320GB        | 1         | 1      | 1.79%   |
| Hitachi HDS721050CLA660 500GB        | 1         | 1      | 1.79%   |
| Hitachi HDS721032CLA362 320GB        | 1         | 1      | 1.79%   |
| HGST HTS725032A7E630 320GB           | 1         | 1      | 1.79%   |
| HGST HTS545050A7E660 500GB           | 1         | 1      | 1.79%   |
| HGST HTS545050A7E380 500GB           | 1         | 1      | 1.79%   |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 1.79%   |
| HGST HTS541010B7E610 1TB             | 1         | 1      | 1.79%   |
| Faspeed H5-500G SSD                  | 1         | 1      | 1.79%   |
| Crucial CT480M500SSD1 480GB          | 1         | 1      | 1.79%   |
| A-DATA Technology SX8100NP 1TB       | 1         | 1      | 1.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 12     | 20.37%  |
| Seagate             | 11        | 15     | 20.37%  |
| Hitachi             | 9         | 11     | 16.67%  |
| HGST                | 8         | 8      | 14.81%  |
| Toshiba             | 3         | 3      | 5.56%   |
| Kingston            | 3         | 3      | 5.56%   |
| Samsung Electronics | 2         | 4      | 3.7%    |
| XrayDisk            | 1         | 1      | 1.85%   |
| Vaseky              | 1         | 1      | 1.85%   |
| LITEON              | 1         | 1      | 1.85%   |
| Intel               | 1         | 2      | 1.85%   |
| Faspeed             | 1         | 1      | 1.85%   |
| Crucial             | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 15     | 26.83%  |
| WDC                 | 9         | 10     | 21.95%  |
| Hitachi             | 9         | 11     | 21.95%  |
| HGST                | 8         | 8      | 19.51%  |
| Toshiba             | 3         | 3      | 7.32%   |
| Samsung Electronics | 1         | 3      | 2.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 50     | 75%     |
| SSD  | 12        | 13     | 23.08%  |
| NVMe | 1         | 1      | 1.92%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 457       | 771    | 66.33%  |
| Works    | 180       | 279    | 26.12%  |
| Malfunc  | 51        | 64     | 7.4%    |
| Failed   | 1         | 1      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 418       | 56.79%  |
| AMD                              | 153       | 20.79%  |
| Samsung Electronics              | 37        | 5.03%   |
| SanDisk                          | 29        | 3.94%   |
| SK hynix                         | 16        | 2.17%   |
| Kingston Technology Company      | 11        | 1.49%   |
| Silicon Motion                   | 10        | 1.36%   |
| Nvidia                           | 8         | 1.09%   |
| JMicron Technology               | 7         | 0.95%   |
| Realtek Semiconductor            | 6         | 0.82%   |
| Micron Technology                | 6         | 0.82%   |
| Marvell Technology Group         | 6         | 0.82%   |
| Toshiba America Info Systems     | 5         | 0.68%   |
| Silicon Integrated Systems [SiS] | 4         | 0.54%   |
| Micron/Crucial Technology        | 4         | 0.54%   |
| ASMedia Technology               | 4         | 0.54%   |
| KIOXIA                           | 3         | 0.41%   |
| Solid State Storage Technology   | 2         | 0.27%   |
| VIA Technologies                 | 1         | 0.14%   |
| Union Memory (Shenzhen)          | 1         | 0.14%   |
| Shenzhen Longsys Electronics     | 1         | 0.14%   |
| Phison Electronics               | 1         | 0.14%   |
| Lite-On Technology               | 1         | 0.14%   |
| Broadcom / LSI                   | 1         | 0.14%   |
| ADATA Technology                 | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 108       | 12.75%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 58        | 6.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 38        | 4.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 25        | 2.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23        | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 21        | 2.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 21        | 2.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 19        | 2.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 18        | 2.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 18        | 2.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 15        | 1.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15        | 1.77%   |
| AMD 400 Series Chipset SATA Controller                                                  | 15        | 1.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 13        | 1.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 11        | 1.3%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 10        | 1.18%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10        | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 10        | 1.18%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 9         | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 1.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 9         | 1.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 0.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8         | 0.94%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 7         | 0.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 7         | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7         | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6         | 0.71%   |
| SanDisk Non-Volatile memory controller                                                  | 6         | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6         | 0.71%   |
| Samsung NVMe SSD Controller 980                                                         | 6         | 0.71%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 6         | 0.71%   |
| Micron Non-Volatile memory controller                                                   | 6         | 0.71%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6         | 0.71%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6         | 0.71%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6         | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 0.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6         | 0.71%   |
| AMD FCH SATA Controller D                                                               | 6         | 0.71%   |
| SK hynix BC511                                                                          | 5         | 0.59%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5         | 0.59%   |
| Intel SSD 660P Series                                                                   | 5         | 0.59%   |
| Intel Non-Volatile memory controller                                                    | 5         | 0.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 5         | 0.59%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 0.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 5         | 0.59%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5         | 0.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 0.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 5         | 0.59%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 5         | 0.59%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5         | 0.59%   |
| SK hynix Non-Volatile memory controller                                                 | 4         | 0.47%   |
| SK hynix Gold P31 SSD                                                                   | 4         | 0.47%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 4         | 0.47%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4         | 0.47%   |
| Nvidia MCP61 SATA Controller                                                            | 4         | 0.47%   |
| Nvidia MCP61 IDE                                                                        | 4         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 487       | 65.19%  |
| NVMe | 133       | 17.8%   |
| IDE  | 88        | 11.78%  |
| RAID | 39        | 5.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 468       | 72.11%  |
| AMD    | 180       | 27.73%  |
| ARM    | 1         | 0.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 1.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 1.53%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 1.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 1.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.07%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 7         | 1.07%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 6         | 0.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 0.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.92%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 6         | 0.92%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.77%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 0.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.77%   |
| AMD FX-6300 Six-Core Processor                | 5         | 0.77%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 4         | 0.61%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 4         | 0.61%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 4         | 0.61%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.61%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 4         | 0.61%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 4         | 0.61%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 4         | 0.61%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.61%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 0.61%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 4         | 0.61%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 3         | 0.46%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.46%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 3         | 0.46%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 0.46%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 3         | 0.46%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.46%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.46%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 3         | 0.46%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3         | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.46%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.46%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 0.46%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.46%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 3         | 0.46%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.46%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 3         | 0.46%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 3         | 0.46%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.46%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 3         | 0.46%   |
| Intel Celeron CPU 3955U @ 2.00GHz             | 3         | 0.46%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 3         | 0.46%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.46%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.46%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.46%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 3         | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 0.46%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.46%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.46%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 3         | 0.46%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 3         | 0.46%   |
| AMD FX-8350 Eight-Core Processor              | 3         | 0.46%   |
| AMD E2-1800 APU with Radeon HD Graphics       | 3         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 136       | 20.86%  |
| Intel Core i7           | 95        | 14.57%  |
| Intel Core i3           | 58        | 8.9%    |
| Intel Celeron           | 43        | 6.6%    |
| Intel Pentium           | 29        | 4.45%   |
| AMD Ryzen 5             | 29        | 4.45%   |
| Intel Core 2 Duo        | 24        | 3.68%   |
| AMD Ryzen 7             | 23        | 3.53%   |
| Intel Atom              | 20        | 3.07%   |
| Intel Xeon              | 18        | 2.76%   |
| AMD Ryzen 3             | 13        | 1.99%   |
| Other                   | 12        | 1.84%   |
| AMD A10                 | 12        | 1.84%   |
| AMD A6                  | 11        | 1.69%   |
| Intel Pentium Dual-Core | 10        | 1.53%   |
| AMD FX                  | 10        | 1.53%   |
| AMD A8                  | 9         | 1.38%   |
| AMD E                   | 8         | 1.23%   |
| Intel Pentium Dual      | 7         | 1.07%   |
| AMD E2                  | 6         | 0.92%   |
| AMD E1                  | 6         | 0.92%   |
| AMD Athlon              | 6         | 0.92%   |
| AMD Ryzen 9             | 5         | 0.77%   |
| AMD A4                  | 4         | 0.61%   |
| AMD A12                 | 4         | 0.61%   |
| Intel Genuine           | 3         | 0.46%   |
| Intel Celeron Dual-Core | 3         | 0.46%   |
| AMD Turion II Dual-Core | 3         | 0.46%   |
| AMD Ryzen 5 PRO         | 3         | 0.46%   |
| AMD Phenom              | 3         | 0.46%   |
| AMD Athlon II X2        | 3         | 0.46%   |
| AMD Athlon II           | 3         | 0.46%   |
| Intel Pentium Silver    | 2         | 0.31%   |
| Intel Pentium Gold      | 2         | 0.31%   |
| Intel Pentium 4         | 2         | 0.31%   |
| Intel Core i9           | 2         | 0.31%   |
| Intel Core 2            | 2         | 0.31%   |
| AMD Ryzen 7 PRO         | 2         | 0.31%   |
| AMD Phenom II X6        | 2         | 0.31%   |
| AMD Phenom II X4        | 2         | 0.31%   |
| AMD Mobile Sempron      | 2         | 0.31%   |
| AMD C-60                | 2         | 0.31%   |
| AMD Athlon 64 X2        | 2         | 0.31%   |
| Intel Xeon Silver       | 1         | 0.15%   |
| Intel Core m5           | 1         | 0.15%   |
| Intel Core Duo          | 1         | 0.15%   |
| Intel Core 2 Quad       | 1         | 0.15%   |
| Intel Core 2 Extreme    | 1         | 0.15%   |
| AMD Ryzen Threadripper  | 1         | 0.15%   |
| AMD Opteron             | 1         | 0.15%   |
| AMD C-50                | 1         | 0.15%   |
| AMD Athlon X4           | 1         | 0.15%   |
| AMD Athlon X2           | 1         | 0.15%   |
| AMD Athlon II X4        | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 326       | 49.92%  |
| 4       | 226       | 34.61%  |
| 6       | 32        | 4.9%    |
| 8       | 30        | 4.59%   |
| 1       | 14        | 2.14%   |
| 3       | 7         | 1.07%   |
| Unknown | 6         | 0.92%   |
| 12      | 4         | 0.61%   |
| 10      | 4         | 0.61%   |
| 16      | 3         | 0.46%   |
| 20      | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 643       | 99.08%  |
| 2       | 4         | 0.62%   |
| 4       | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 388       | 59.6%   |
| 1       | 257       | 39.48%  |
| Unknown | 6         | 0.92%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 624       | 95.85%  |
| Unknown        | 15        | 2.3%    |
| 64-bit         | 6         | 0.92%   |
| 32-bit         | 6         | 0.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 123       | 18.5%   |
| 0x206a7    | 37        | 5.56%   |
| 0x306a9    | 33        | 4.96%   |
| 0x406e3    | 27        | 4.06%   |
| 0x1067a    | 22        | 3.31%   |
| 0x806e9    | 20        | 3.01%   |
| 0x40651    | 20        | 3.01%   |
| 0x306c3    | 19        | 2.86%   |
| 0x30678    | 17        | 2.56%   |
| 0x806ec    | 15        | 2.26%   |
| 0x806ea    | 14        | 2.11%   |
| 0x906ea    | 13        | 1.95%   |
| 0x906e9    | 12        | 1.8%    |
| 0x6fd      | 12        | 1.8%    |
| 0x406c4    | 12        | 1.8%    |
| 0x20655    | 11        | 1.65%   |
| 0x08108109 | 11        | 1.65%   |
| 0x05000119 | 11        | 1.65%   |
| 0x306d4    | 10        | 1.5%    |
| 0x10676    | 9         | 1.35%   |
| 0x08701021 | 9         | 1.35%   |
| 0x0810100b | 9         | 1.35%   |
| 0x0a50000c | 7         | 1.05%   |
| 0x08600106 | 7         | 1.05%   |
| 0x08108102 | 7         | 1.05%   |
| 0x0700010f | 7         | 1.05%   |
| 0x06000852 | 7         | 1.05%   |
| 0x706a1    | 6         | 0.9%    |
| 0x506c9    | 6         | 0.9%    |
| 0x03000027 | 6         | 0.9%    |
| 0xa0653    | 5         | 0.75%   |
| 0x806c1    | 5         | 0.75%   |
| 0x506e3    | 5         | 0.75%   |
| 0x406c3    | 5         | 0.75%   |
| 0x06001119 | 5         | 0.75%   |
| 0x010000c8 | 5         | 0.75%   |
| 0xa0652    | 4         | 0.6%    |
| 0x706e5    | 4         | 0.6%    |
| 0x6fb      | 4         | 0.6%    |
| 0x106ca    | 4         | 0.6%    |
| 0x0800820d | 4         | 0.6%    |
| 0x07030106 | 4         | 0.6%    |
| 0x07030105 | 4         | 0.6%    |
| 0x806eb    | 3         | 0.45%   |
| 0x706a8    | 3         | 0.45%   |
| 0x306f2    | 3         | 0.45%   |
| 0x306e4    | 3         | 0.45%   |
| 0x20652    | 3         | 0.45%   |
| 0x106c2    | 3         | 0.45%   |
| 0x08101016 | 3         | 0.45%   |
| 0x0600611a | 3         | 0.45%   |
| 0x06003106 | 3         | 0.45%   |
| 0x0600063e | 3         | 0.45%   |
| 0x05000029 | 3         | 0.45%   |
| 0x40661    | 2         | 0.3%    |
| 0x206d7    | 2         | 0.3%    |
| 0x106a5    | 2         | 0.3%    |
| 0x08600104 | 2         | 0.3%    |
| 0x08600103 | 2         | 0.3%    |
| 0x08600102 | 2         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 102       | 15.69%  |
| Haswell          | 53        | 8.15%   |
| SandyBridge      | 47        | 7.23%   |
| IvyBridge        | 45        | 6.92%   |
| Skylake          | 38        | 5.85%   |
| Silvermont       | 38        | 5.85%   |
| Penryn           | 38        | 5.85%   |
| Zen+             | 25        | 3.85%   |
| Zen 2            | 25        | 3.85%   |
| Zen              | 18        | 2.77%   |
| Westmere         | 18        | 2.77%   |
| Core             | 18        | 2.77%   |
| Piledriver       | 17        | 2.62%   |
| K10              | 17        | 2.62%   |
| Bobcat           | 16        | 2.46%   |
| Excavator        | 14        | 2.15%   |
| CometLake        | 13        | 2%      |
| Broadwell        | 13        | 2%      |
| Zen 3            | 11        | 1.69%   |
| Puma             | 9         | 1.38%   |
| Jaguar           | 9         | 1.38%   |
| Goldmont plus    | 9         | 1.38%   |
| TigerLake        | 8         | 1.23%   |
| Bonnell          | 8         | 1.23%   |
| K10 Llano        | 7         | 1.08%   |
| Goldmont         | 6         | 0.92%   |
| K8 Hammer        | 4         | 0.62%   |
| IceLake          | 4         | 0.62%   |
| Unknown          | 4         | 0.62%   |
| Steamroller      | 3         | 0.46%   |
| Nehalem          | 3         | 0.46%   |
| Bulldozer        | 3         | 0.46%   |
| P6               | 2         | 0.31%   |
| NetBurst         | 2         | 0.31%   |
| Tremont          | 1         | 0.15%   |
| K8 & K10 hybrid  | 1         | 0.15%   |
| Alderlake Hybrid | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 391       | 51.38%  |
| AMD                              | 192       | 25.23%  |
| Nvidia                           | 168       | 22.08%  |
| Silicon Integrated Systems [SiS] | 4         | 0.53%   |
| Matrox Electronics Systems       | 3         | 0.39%   |
| ATI Technologies                 | 2         | 0.26%   |
| VIA Technologies                 | 1         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 42        | 5.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 26        | 3.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 3.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 2.76%   |
| Intel HD Graphics 620                                                                    | 21        | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 20        | 2.51%   |
| Intel UHD Graphics 620                                                                   | 18        | 2.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 2.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 2.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 2.01%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 1.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 1.63%   |
| AMD Renoir                                                                               | 13        | 1.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.51%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 12        | 1.51%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12        | 1.51%   |
| Intel HD Graphics 630                                                                    | 11        | 1.38%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 1.38%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.13%   |
| Intel HD Graphics 5500                                                                   | 8         | 1%      |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 8         | 1%      |
| Nvidia GM108M [GeForce 940MX]                                                            | 7         | 0.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.88%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 0.88%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6         | 0.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 0.75%   |
| AMD Cezanne                                                                              | 6         | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 0.63%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.63%   |
| Intel HD Graphics 530                                                                    | 5         | 0.63%   |
| Intel HD Graphics 510                                                                    | 5         | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.63%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 5         | 0.63%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.63%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 5         | 0.63%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5         | 0.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5         | 0.63%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5         | 0.63%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 0.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.5%    |
| Nvidia TU117M                                                                            | 4         | 0.5%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.5%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.5%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 4         | 0.5%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 0.5%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.5%    |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 4         | 0.5%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 3         | 0.38%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.38%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.38%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 0.38%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 294       | 45.3%   |
| 1 x AMD        | 132       | 20.34%  |
| 1 x Nvidia     | 81        | 12.48%  |
| Intel + Nvidia | 74        | 11.4%   |
| 2 x AMD        | 26        | 4.01%   |
| Intel + AMD    | 20        | 3.08%   |
| AMD + Nvidia   | 13        | 2%      |
| 1 x SiS        | 4         | 0.62%   |
| 1 x Matrox     | 2         | 0.31%   |
| Other          | 1         | 0.15%   |
| 1 x VIA        | 1         | 0.15%   |
| AMD + Matrox   | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 538       | 82.64%  |
| Proprietary | 88        | 13.52%  |
| Unknown     | 25        | 3.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 362       | 55.18%  |
| 1.01-2.0   | 92        | 14.02%  |
| 0.01-0.5   | 90        | 13.72%  |
| 0.51-1.0   | 49        | 7.47%   |
| 3.01-4.0   | 38        | 5.79%   |
| 5.01-6.0   | 8         | 1.22%   |
| 7.01-8.0   | 7         | 1.07%   |
| 2.01-3.0   | 5         | 0.76%   |
| 8.01-16.0  | 5         | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 113       | 16.31%  |
| AU Optronics            | 96        | 13.85%  |
| BOE                     | 85        | 12.27%  |
| Chimei Innolux          | 69        | 9.96%   |
| LG Display              | 66        | 9.52%   |
| Goldstar                | 54        | 7.79%   |
| Hewlett-Packard         | 18        | 2.6%    |
| Lenovo                  | 17        | 2.45%   |
| Dell                    | 15        | 2.16%   |
| AOC                     | 15        | 2.16%   |
| ViewSonic               | 11        | 1.59%   |
| LG Electronics          | 10        | 1.44%   |
| Unknown                 | 9         | 1.3%    |
| Sony                    | 9         | 1.3%    |
| Apple                   | 9         | 1.3%    |
| Sharp                   | 8         | 1.15%   |
| Chi Mei Optoelectronics | 8         | 1.15%   |
| PANDA                   | 6         | 0.87%   |
| InfoVision              | 6         | 0.87%   |
| ___                     | 5         | 0.72%   |
| SAC                     | 5         | 0.72%   |
| Envision                | 5         | 0.72%   |
| ASUSTek Computer        | 5         | 0.72%   |
| Acer                    | 5         | 0.72%   |
| Packard Bell            | 4         | 0.58%   |
| LG Philips              | 3         | 0.43%   |
| KTC                     | 3         | 0.43%   |
| Hitachi                 | 3         | 0.43%   |
| CSO                     | 3         | 0.43%   |
| Ancor Communications    | 3         | 0.43%   |
| SKY                     | 2         | 0.29%   |
| Plain Tree Systems      | 2         | 0.29%   |
| Philips                 | 2         | 0.29%   |
| MSI                     | 2         | 0.29%   |
| LGD                     | 2         | 0.29%   |
| CPT                     | 2         | 0.29%   |
| Westinghouse            | 1         | 0.14%   |
| Unknown (XXX)           | 1         | 0.14%   |
| STA                     | 1         | 0.14%   |
| SGT                     | 1         | 0.14%   |
| PAR                     | 1         | 0.14%   |
| NCS                     | 1         | 0.14%   |
| InnoLux Display         | 1         | 0.14%   |
| HKC                     | 1         | 0.14%   |
| HannStar                | 1         | 0.14%   |
| ELD                     | 1         | 0.14%   |
| CHR                     | 1         | 0.14%   |
| BenQ                    | 1         | 0.14%   |
| Unknown                 | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 10        | 1.41%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 9         | 1.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 6         | 0.85%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 6         | 0.85%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 5         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 5         | 0.7%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 5         | 0.7%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 5         | 0.7%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 4         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 4         | 0.56%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.56%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 4         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 4         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 4         | 0.56%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 4         | 0.56%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 4         | 0.56%   |
| ___ LCD TV ___9000 1360x768                                           | 3         | 0.42%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 3         | 0.42%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 3         | 0.42%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 3         | 0.42%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch     | 3         | 0.42%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                 | 3         | 0.42%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 3         | 0.42%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 3         | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.42%   |
| Lenovo LEN S22e-19 LEN61C9 1920x1080 476x268mm 21.5-inch              | 3         | 0.42%   |
| Goldstar HDR WFHD GSM5B9F 2560x1080 798x334mm 34.1-inch               | 3         | 0.42%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 3         | 0.42%   |
| Envision L32W931 EPI2009 1360x768 696x392mm 31.4-inch                 | 3         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch       | 3         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 3         | 0.42%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 3         | 0.42%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 0.42%   |
| BOE LCD Monitor BOE0628 1366x768 309x173mm 13.9-inch                  | 3         | 0.42%   |
| BOE LCD Monitor BOE0602 1366x768 309x173mm 13.9-inch                  | 3         | 0.42%   |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                  | 3         | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.42%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 3         | 0.42%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 3         | 0.42%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                        | 3         | 0.42%   |
| ___ LCD TV ___0101 1360x768                                           | 2         | 0.28%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                    | 2         | 0.28%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 2         | 0.28%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2         | 0.28%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 440x250mm 19.9-inch      | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch  | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 310x170mm 13.9-inch  | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch  | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 890x500mm 40.2-inch | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768                      | 2         | 0.28%   |
| Philips 190P PHL0831 1280x1024 376x301mm 19.0-inch                    | 2         | 0.28%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 2         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 251       | 37.8%   |
| 1920x1080 (FHD)    | 218       | 32.83%  |
| 1600x900 (HD+)     | 29        | 4.37%   |
| 3840x2160 (4K)     | 25        | 3.77%   |
| 1360x768           | 24        | 3.61%   |
| 1440x900 (WXGA+)   | 19        | 2.86%   |
| 1280x800 (WXGA)    | 16        | 2.41%   |
| 1280x1024 (SXGA)   | 13        | 1.96%   |
| 2560x1080          | 10        | 1.51%   |
| 2560x1440 (QHD)    | 9         | 1.36%   |
| 1680x1050 (WSXGA+) | 7         | 1.05%   |
| 1920x1200 (WUXGA)  | 6         | 0.9%    |
| Unknown            | 6         | 0.9%    |
| 1024x600           | 4         | 0.6%    |
| 3840x1080          | 3         | 0.45%   |
| 3440x1440          | 3         | 0.45%   |
| 2560x1600          | 3         | 0.45%   |
| 1024x768 (XGA)     | 3         | 0.45%   |
| 2160x1440          | 2         | 0.3%    |
| 1024x576           | 2         | 0.3%    |
| 5760x1080          | 1         | 0.15%   |
| 5440x1800          | 1         | 0.15%   |
| 3840x2400          | 1         | 0.15%   |
| 3840x1100          | 1         | 0.15%   |
| 3286x1080          | 1         | 0.15%   |
| 3000x2000          | 1         | 0.15%   |
| 2288x1287          | 1         | 0.15%   |
| 1920x540           | 1         | 0.15%   |
| 1680x945           | 1         | 0.15%   |
| 1280x768           | 1         | 0.15%   |
| 1280x720 (HD)      | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 156       | 22.45%  |
| 13      | 119       | 17.12%  |
| 14      | 106       | 15.25%  |
| 23      | 49        | 7.05%   |
| 21      | 45        | 6.47%   |
| Unknown | 30        | 4.32%   |
| 19      | 21        | 3.02%   |
| 17      | 19        | 2.73%   |
| 24      | 17        | 2.45%   |
| 27      | 16        | 2.3%    |
| 18      | 15        | 2.16%   |
| 34      | 12        | 1.73%   |
| 31      | 11        | 1.58%   |
| 20      | 11        | 1.58%   |
| 72      | 10        | 1.44%   |
| 12      | 9         | 1.29%   |
| 11      | 8         | 1.15%   |
| 10      | 8         | 1.15%   |
| 54      | 6         | 0.86%   |
| 84      | 5         | 0.72%   |
| 40      | 4         | 0.58%   |
| 22      | 4         | 0.58%   |
| 32      | 3         | 0.43%   |
| 48      | 2         | 0.29%   |
| 37      | 2         | 0.29%   |
| 16      | 2         | 0.29%   |
| 142     | 1         | 0.14%   |
| 55      | 1         | 0.14%   |
| 43      | 1         | 0.14%   |
| 28      | 1         | 0.14%   |
| 26      | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 346       | 50.51%  |
| 401-500        | 83        | 12.12%  |
| 501-600        | 76        | 11.09%  |
| 201-300        | 62        | 9.05%   |
| Unknown        | 30        | 4.38%   |
| 351-400        | 26        | 3.8%    |
| 701-800        | 15        | 2.19%   |
| 601-700        | 15        | 2.19%   |
| 1501-2000      | 15        | 2.19%   |
| 1001-1500      | 9         | 1.31%   |
| 801-900        | 6         | 0.88%   |
| More than 2000 | 1         | 0.15%   |
| 901-1000       | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 499       | 81.4%   |
| 16/10   | 56        | 9.14%   |
| Unknown | 22        | 3.59%   |
| 5/4     | 13        | 2.12%   |
| 21/9    | 12        | 1.96%   |
| 4/3     | 5         | 0.82%   |
| 3/2     | 3         | 0.49%   |
| 3.40    | 1         | 0.16%   |
| 1.96    | 1         | 0.16%   |
| 1.00    | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 190       | 27.62%  |
| 101-110        | 154       | 22.38%  |
| 201-250        | 95        | 13.81%  |
| 151-200        | 41        | 5.96%   |
| 71-80          | 33        | 4.8%    |
| Unknown        | 30        | 4.36%   |
| 351-500        | 27        | 3.92%   |
| More than 1000 | 24        | 3.49%   |
| 141-150        | 19        | 2.76%   |
| 301-350        | 17        | 2.47%   |
| 121-130        | 10        | 1.45%   |
| 51-60          | 9         | 1.31%   |
| 61-70          | 8         | 1.16%   |
| 41-50          | 8         | 1.16%   |
| 501-1000       | 8         | 1.16%   |
| 251-300        | 5         | 0.73%   |
| 131-140        | 4         | 0.58%   |
| 111-120        | 3         | 0.44%   |
| 91-100         | 3         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 290       | 42.34%  |
| 51-100        | 173       | 25.26%  |
| 121-160       | 129       | 18.83%  |
| Unknown       | 30        | 4.38%   |
| 1-50          | 29        | 4.23%   |
| 161-240       | 27        | 3.94%   |
| More than 240 | 7         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 510       | 77.51%  |
| 2     | 106       | 16.11%  |
| 0     | 32        | 4.86%   |
| 3     | 10        | 1.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 425       | 41.95%  |
| Intel                            | 219       | 21.62%  |
| Qualcomm Atheros                 | 131       | 12.93%  |
| Broadcom                         | 62        | 6.12%   |
| Ralink                           | 28        | 2.76%   |
| Ralink Technology                | 21        | 2.07%   |
| Broadcom Limited                 | 16        | 1.58%   |
| TP-Link                          | 15        | 1.48%   |
| Huawei Technologies              | 12        | 1.18%   |
| Marvell Technology Group         | 11        | 1.09%   |
| Xiaomi                           | 10        | 0.99%   |
| Samsung Electronics              | 7         | 0.69%   |
| Qualcomm Atheros Communications  | 7         | 0.69%   |
| Nvidia                           | 7         | 0.69%   |
| D-Link System                    | 5         | 0.49%   |
| Silicon Integrated Systems [SiS] | 4         | 0.39%   |
| MediaTek                         | 4         | 0.39%   |
| JMicron Technology               | 4         | 0.39%   |
| D-Link                           | 4         | 0.39%   |
| ICS Advent                       | 3         | 0.3%    |
| VIA Technologies                 | 2         | 0.2%    |
| Motorola PCS                     | 2         | 0.2%    |
| Microsoft                        | 2         | 0.2%    |
| DisplayLink                      | 2         | 0.2%    |
| Qcom                             | 1         | 0.1%    |
| Padix (Rockfire)                 | 1         | 0.1%    |
| Oculus VR                        | 1         | 0.1%    |
| Microchip Technology             | 1         | 0.1%    |
| Manta                            | 1         | 0.1%    |
| HMD Global                       | 1         | 0.1%    |
| Hewlett-Packard                  | 1         | 0.1%    |
| ASUSTek Computer                 | 1         | 0.1%    |
| ASIX Electronics                 | 1         | 0.1%    |
| Arduino SA                       | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 273       | 22.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 95        | 7.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 2.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 26        | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 21        | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 19        | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 1.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 17        | 1.42%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 1.42%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 16        | 1.33%   |
| Intel Wireless 8265 / 8275                                              | 16        | 1.33%   |
| Intel Wireless 8260                                                     | 16        | 1.33%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 14        | 1.17%   |
| Intel Wireless 7260                                                     | 14        | 1.17%   |
| Intel Wireless 7265                                                     | 13        | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 1.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 12        | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.92%   |
| Ralink MT7601U Wireless Adapter                                         | 11        | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 0.92%   |
| Huawei LYA-L09                                                          | 10        | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 9         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 9         | 0.75%   |
| Intel Ethernet Connection I219-LM                                       | 9         | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 7         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                       | 6         | 0.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 6         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.5%    |
| Intel Wi-Fi 6 AX201                                                     | 6         | 0.5%    |
| Intel I211 Gigabit Network Connection                                   | 6         | 0.5%    |
| Intel Ethernet Connection I217-V                                        | 6         | 0.5%    |
| Intel Ethernet Connection I217-LM                                       | 6         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                    | 6         | 0.5%    |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 0.5%    |
| TP-Link 802.11ac WLAN Adapter                                           | 5         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 0.42%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.42%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 5         | 0.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.42%   |
| Intel Wireless 3165                                                     | 5         | 0.42%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 0.42%   |
| Intel Ethernet Connection (6) I219-V                                    | 5         | 0.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.42%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 0.42%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 4         | 0.33%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.33%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 4         | 0.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 188       | 32.36%  |
| Realtek Semiconductor           | 135       | 23.24%  |
| Qualcomm Atheros                | 112       | 19.28%  |
| Broadcom                        | 48        | 8.26%   |
| Ralink                          | 28        | 4.82%   |
| Ralink Technology               | 21        | 3.61%   |
| TP-Link                         | 14        | 2.41%   |
| Broadcom Limited                | 12        | 2.07%   |
| Qualcomm Atheros Communications | 7         | 1.2%    |
| MediaTek                        | 4         | 0.69%   |
| D-Link System                   | 3         | 0.52%   |
| D-Link                          | 3         | 0.52%   |
| Microsoft                       | 2         | 0.34%   |
| Samsung Electronics             | 1         | 0.17%   |
| Qcom                            | 1         | 0.17%   |
| Hewlett-Packard                 | 1         | 0.17%   |
| ASUSTek Computer                | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 4.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 26        | 4.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 21        | 3.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 19        | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 3.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 17        | 2.92%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 2.92%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 16        | 2.74%   |
| Intel Wireless 8265 / 8275                                              | 16        | 2.74%   |
| Intel Wireless 8260                                                     | 16        | 2.74%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 14        | 2.4%    |
| Intel Wireless 7260                                                     | 14        | 2.4%    |
| Intel Wireless 7265                                                     | 13        | 2.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.89%   |
| Ralink MT7601U Wireless Adapter                                         | 11        | 1.89%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 1.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 1.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 1.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 7         | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 1.03%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 6         | 1.03%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.03%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 1.03%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.03%   |
| TP-Link 802.11ac WLAN Adapter                                           | 5         | 0.86%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.86%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 5         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.86%   |
| Intel Wireless 3165                                                     | 5         | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.86%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 0.86%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.69%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 4         | 0.69%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.69%   |
| Intel Wireless-AC 9260                                                  | 4         | 0.69%   |
| Intel Wireless 3160                                                     | 4         | 0.69%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.69%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 4         | 0.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 3         | 0.51%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 3         | 0.51%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.51%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 0.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.51%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.51%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.51%   |
| Intel Centrino Wireless-N 130                                           | 3         | 0.51%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 0.51%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 386       | 63.7%   |
| Intel                            | 93        | 15.35%  |
| Qualcomm Atheros                 | 30        | 4.95%   |
| Broadcom                         | 25        | 4.13%   |
| Marvell Technology Group         | 11        | 1.82%   |
| Huawei Technologies              | 11        | 1.82%   |
| Xiaomi                           | 10        | 1.65%   |
| Nvidia                           | 7         | 1.16%   |
| Samsung Electronics              | 6         | 0.99%   |
| Silicon Integrated Systems [SiS] | 4         | 0.66%   |
| JMicron Technology               | 4         | 0.66%   |
| Broadcom Limited                 | 4         | 0.66%   |
| ICS Advent                       | 3         | 0.5%    |
| VIA Technologies                 | 2         | 0.33%   |
| DisplayLink                      | 2         | 0.33%   |
| D-Link System                    | 2         | 0.33%   |
| TP-Link                          | 1         | 0.17%   |
| Motorola PCS                     | 1         | 0.17%   |
| Microchip Technology             | 1         | 0.17%   |
| HMD Global                       | 1         | 0.17%   |
| D-Link                           | 1         | 0.17%   |
| ASIX Electronics                 | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 273       | 44.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 95        | 15.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 1.96%   |
| Huawei LYA-L09                                                    | 10        | 1.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 9         | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.47%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 0.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.98%   |
| Intel I211 Gigabit Network Connection                             | 6         | 0.98%   |
| Intel Ethernet Connection I217-V                                  | 6         | 0.98%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.82%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.82%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 4         | 0.65%   |
| Nvidia MCP61 Ethernet                                             | 4         | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.65%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.65%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.49%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.33%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2         | 0.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.33%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.33%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.33%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.33%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.33%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.33%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.33%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.33%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.33%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.33%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.33%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.33%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.33%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.33%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 2         | 0.33%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.33%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.33%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 2         | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.16%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.16%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.16%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.16%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.16%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 572       | 50.98%  |
| WiFi     | 544       | 48.48%  |
| Modem    | 3         | 0.27%   |
| Unknown  | 3         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 425       | 64.1%   |
| Ethernet | 238       | 35.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 410       | 63.17%  |
| 1     | 212       | 32.67%  |
| 3     | 13        | 2%      |
| 0     | 12        | 1.85%   |
| 4     | 2         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 619       | 94.94%  |
| Yes  | 33        | 5.06%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 150       | 35.89%  |
| Realtek Semiconductor           | 79        | 18.9%   |
| Qualcomm Atheros Communications | 33        | 7.89%   |
| Broadcom                        | 33        | 7.89%   |
| Cambridge Silicon Radio         | 21        | 5.02%   |
| IMC Networks                    | 20        | 4.78%   |
| Lite-On Technology              | 19        | 4.55%   |
| Apple                           | 14        | 3.35%   |
| Foxconn / Hon Hai               | 13        | 3.11%   |
| Ralink                          | 8         | 1.91%   |
| Dell                            | 7         | 1.67%   |
| Realtek                         | 5         | 1.2%    |
| Hewlett-Packard                 | 4         | 0.96%   |
| Toshiba                         | 3         | 0.72%   |
| Ralink Technology               | 3         | 0.72%   |
| ASUSTek Computer                | 3         | 0.72%   |
| Foxconn International           | 2         | 0.48%   |
| Alps Electric                   | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 69        | 16.51%  |
| Realtek Bluetooth Radio                                                             | 42        | 10.05%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 31        | 7.42%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 21        | 5.02%   |
| Intel AX201 Bluetooth                                                               | 18        | 4.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 17        | 4.07%   |
| Intel AX200 Bluetooth                                                               | 17        | 4.07%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 3.83%   |
| Intel Bluetooth Device                                                              | 10        | 2.39%   |
| Apple Bluetooth USB Host Controller                                                 | 10        | 2.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 9         | 2.15%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 9         | 2.15%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 1.91%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 8         | 1.91%   |
| IMC Networks Bluetooth Device                                                       | 8         | 1.91%   |
| IMC Networks Bluetooth Radio                                                        | 6         | 1.44%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 6         | 1.44%   |
| Realtek RTL8821A Bluetooth                                                          | 5         | 1.2%    |
| Realtek Bluetooth Radio                                                             | 5         | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 1.2%    |
| Lite-On Bluetooth Device                                                            | 5         | 1.2%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 1.2%    |
| Intel AX210 Bluetooth                                                               | 5         | 1.2%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 4         | 0.96%   |
| Broadcom Bluetooth 3.0 USB Dongle                                                   | 4         | 0.96%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 4         | 0.96%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.72%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 3         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 0.72%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.72%   |
| Dell Wireless 365 Bluetooth                                                         | 3         | 0.72%   |
| Broadcom HP Portable Bumble Bee                                                     | 3         | 0.72%   |
| Apple Bluetooth Host Controller                                                     | 3         | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.48%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 2         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.48%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.48%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.48%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.48%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.48%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.48%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.48%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.48%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.48%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.48%   |
| ASUS BCM20702A0                                                                     | 2         | 0.48%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.24%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.24%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.24%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.24%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.24%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 1         | 0.24%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.24%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth                                     | 1         | 0.24%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.24%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.24%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.24%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.24%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 445       | 54.87%  |
| AMD                              | 197       | 24.29%  |
| Nvidia                           | 101       | 12.45%  |
| C-Media Electronics              | 13        | 1.6%    |
| Logitech                         | 5         | 0.62%   |
| Generalplus Technology           | 5         | 0.62%   |
| Creative Labs                    | 5         | 0.62%   |
| Silicon Integrated Systems [SiS] | 4         | 0.49%   |
| Texas Instruments                | 3         | 0.37%   |
| VIA Technologies                 | 2         | 0.25%   |
| Kingston Technology              | 2         | 0.25%   |
| Focusrite-Novation               | 2         | 0.25%   |
| Creative Technology              | 2         | 0.25%   |
| Arturia                          | 2         | 0.25%   |
| Apple                            | 2         | 0.25%   |
| Unknown                          | 1         | 0.12%   |
| Shenzhen Riitek Technology       | 1         | 0.12%   |
| Razer USA                        | 1         | 0.12%   |
| PreSonus Audio Electronics       | 1         | 0.12%   |
| Plantronics                      | 1         | 0.12%   |
| Pixart Imaging                   | 1         | 0.12%   |
| Native Instruments               | 1         | 0.12%   |
| Microsoft                        | 1         | 0.12%   |
| Micro Star International         | 1         | 0.12%   |
| Lenovo                           | 1         | 0.12%   |
| JMTek                            | 1         | 0.12%   |
| Hewlett-Packard                  | 1         | 0.12%   |
| GYROCOM C&C                      | 1         | 0.12%   |
| ESS Technology                   | 1         | 0.12%   |
| eMPIA Technology                 | 1         | 0.12%   |
| DigiTech                         | 1         | 0.12%   |
| Corsair                          | 1         | 0.12%   |
| Blue Microphones                 | 1         | 0.12%   |
| ATI Technologies                 | 1         | 0.12%   |
| Afatech                          | 1         | 0.12%   |
| Unknown                          | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 74        | 7.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 56        | 5.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 48        | 4.8%    |
| AMD FCH Azalia Controller                                                                         | 44        | 4.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 38        | 3.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 33        | 3.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 27        | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 26        | 2.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 26        | 2.6%    |
| AMD Kabini HDMI/DP Audio                                                                          | 26        | 2.6%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 21        | 2.1%    |
| Intel 8 Series HD Audio Controller                                                                | 21        | 2.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 19        | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 17        | 1.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 16        | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 16        | 1.6%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 16        | 1.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 14        | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                                        | 14        | 1.4%    |
| Intel Broadwell-U Audio Controller                                                                | 13        | 1.3%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 1.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 1.2%    |
| Intel CM238 HD Audio Controller                                                                   | 10        | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 1%      |
| AMD Wrestler HDMI Audio                                                                           | 10        | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 0.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 9         | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 8         | 0.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 0.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 0.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 0.8%    |
| AMD Trinity HDMI Audio Controller                                                                 | 7         | 0.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 0.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 7         | 0.7%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 6         | 0.6%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 6         | 0.6%    |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 0.6%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6         | 0.6%    |
| AMD Navi 10 HDMI Audio                                                                            | 6         | 0.6%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 6         | 0.6%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 6         | 0.6%    |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.5%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 5         | 0.5%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 0.5%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.5%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 5         | 0.5%    |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 0.5%    |
| Generalplus Technology USB Audio Device                                                           | 5         | 0.5%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 5         | 0.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 0.5%    |
| AMD High Definition Audio Controller                                                              | 5         | 0.5%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 0.4%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.4%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 105       | 28.61%  |
| SK hynix            | 57        | 15.53%  |
| Kingston            | 46        | 12.53%  |
| Micron Technology   | 42        | 11.44%  |
| Crucial             | 40        | 10.9%   |
| Unknown             | 21        | 5.72%   |
| Ramaxel Technology  | 12        | 3.27%   |
| Corsair             | 11        | 3%      |
| A-DATA Technology   | 6         | 1.63%   |
| G.Skill             | 5         | 1.36%   |
| Nanya Technology    | 3         | 0.82%   |
| Unknown (ABCD)      | 2         | 0.54%   |
| Elpida              | 2         | 0.54%   |
| Unknown             | 2         | 0.54%   |
| Unknown (090E)      | 1         | 0.27%   |
| Unknown (08C8)      | 1         | 0.27%   |
| Smart               | 1         | 0.27%   |
| PNY                 | 1         | 0.27%   |
| Patriot             | 1         | 0.27%   |
| Kreton              | 1         | 0.27%   |
| Kllisre             | 1         | 0.27%   |
| Goldenmars          | 1         | 0.27%   |
| GLOWAY              | 1         | 0.27%   |
| Avant               | 1         | 0.27%   |
| Atermiter           | 1         | 0.27%   |
| ASint Technology    | 1         | 0.27%   |
| Ankowall            | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 9         | 2.3%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.28%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.28%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.28%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.28%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 1.28%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 1.02%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.02%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.02%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 1.02%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 4         | 1.02%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.77%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.77%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 3         | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.77%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.77%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.77%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.77%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 3         | 0.77%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s              | 3         | 0.77%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                          | 2         | 0.51%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 0.51%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.51%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.51%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.51%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.51%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.51%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.51%   |
| Samsung RAM K4U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s     | 2         | 0.51%   |
| Samsung RAM 16HTF25664HY-667E1 4096MB SODIMM DDR2 800MT/s        | 2         | 0.51%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 0.51%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 0.51%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.51%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.51%   |
| Kingston RAM KHX3466C17D4/16GX 16384MB DIMM DDR4 3466MT/s        | 2         | 0.51%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 2         | 0.51%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.51%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB SODIMM DDR4 3200MT/s          | 2         | 0.51%   |
| Crucial RAM CT51264AC800.C16FC 4GB SODIMM DDR2 800MT/s           | 2         | 0.51%   |
| Crucial RAM CT4G4DFS6266.C4FJ 4096MB DIMM DDR4 2666MT/s          | 2         | 0.51%   |
| Unknown                                                          | 2         | 0.51%   |
| Unknown RAM Module 8GB SODIMM LPDDR4 4266MT/s                    | 1         | 0.26%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.26%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.26%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1333MT/s                   | 1         | 0.26%   |
| Unknown RAM Module 8192MB SODIMM DDR3                            | 1         | 0.26%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.26%   |
| Unknown RAM Module 8192MB DIMM DDR3                              | 1         | 0.26%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.26%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.26%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.26%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 1         | 0.26%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 1         | 0.26%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.26%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.26%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 1         | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 131       | 44.86%  |
| DDR3    | 112       | 38.36%  |
| LPDDR4  | 13        | 4.45%   |
| DDR2    | 13        | 4.45%   |
| LPDDR3  | 10        | 3.42%   |
| SDRAM   | 7         | 2.4%    |
| Unknown | 4         | 1.37%   |
| RAM     | 1         | 0.34%   |
| DDR     | 1         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 195       | 68.18%  |
| DIMM         | 71        | 24.83%  |
| Row Of Chips | 19        | 6.64%   |
| Unknown      | 1         | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 136       | 41.85%  |
| 8192  | 113       | 34.77%  |
| 2048  | 40        | 12.31%  |
| 16384 | 30        | 9.23%   |
| 1024  | 4         | 1.23%   |
| 32768 | 1         | 0.31%   |
| 64    | 1         | 0.31%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 78        | 23.21%  |
| 2667    | 59        | 17.56%  |
| 2400    | 30        | 8.93%   |
| 3200    | 29        | 8.63%   |
| 2133    | 26        | 7.74%   |
| 1333    | 21        | 6.25%   |
| 1334    | 12        | 3.57%   |
| 3266    | 10        | 2.98%   |
| 667     | 9         | 2.68%   |
| 3600    | 6         | 1.79%   |
| 800     | 6         | 1.79%   |
| 4267    | 5         | 1.49%   |
| 3466    | 5         | 1.49%   |
| Unknown | 5         | 1.49%   |
| 1067    | 4         | 1.19%   |
| 1066    | 4         | 1.19%   |
| 4199    | 3         | 0.89%   |
| 1867    | 3         | 0.89%   |
| 1866    | 3         | 0.89%   |
| 4266    | 2         | 0.6%    |
| 2666    | 2         | 0.6%    |
| 2048    | 2         | 0.6%    |
| 8400    | 1         | 0.3%    |
| 6400    | 1         | 0.3%    |
| 4000    | 1         | 0.3%    |
| 3800    | 1         | 0.3%    |
| 3400    | 1         | 0.3%    |
| 3134    | 1         | 0.3%    |
| 3000    | 1         | 0.3%    |
| 2933    | 1         | 0.3%    |
| 2800    | 1         | 0.3%    |
| 975     | 1         | 0.3%    |
| 933     | 1         | 0.3%    |
| 533     | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 33.33%  |
| Brother Industries  | 4         | 26.67%  |
| Canon               | 3         | 20%     |
| Seiko Epson         | 2         | 13.33%  |
| QinHeng Electronics | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Brother HL-1200 series    | 3         | 20%     |
| Seiko Epson Printer       | 1         | 6.67%   |
| Seiko Epson L3150 Series  | 1         | 6.67%   |
| QinHeng CH340S            | 1         | 6.67%   |
| HP Officejet 4500 G510a-f | 1         | 6.67%   |
| HP LaserJet P1005         | 1         | 6.67%   |
| HP Deskjet 4640 series    | 1         | 6.67%   |
| HP Deskjet 4620 series    | 1         | 6.67%   |
| HP DeskJet 2130 series    | 1         | 6.67%   |
| Canon PIXMA MP250         | 1         | 6.67%   |
| Canon G2000 series        | 1         | 6.67%   |
| Canon G1000 series        | 1         | 6.67%   |
| Brother DCP-1600          | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 50%     |
| Canon       | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 1         | 25%     |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 25%     |
| Canon CanoScan LiDE 110                       | 1         | 25%     |
| Canon CanoScan D1250U2                        | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 109       | 23.19%  |
| IMC Networks                           | 48        | 10.21%  |
| Realtek Semiconductor                  | 35        | 7.45%   |
| Microdia                               | 33        | 7.02%   |
| Cheng Uei Precision Industry (Foxlink) | 30        | 6.38%   |
| Sunplus Innovation Technology          | 28        | 5.96%   |
| Acer                                   | 23        | 4.89%   |
| Suyin                                  | 19        | 4.04%   |
| Lite-On Technology                     | 18        | 3.83%   |
| Silicon Motion                         | 16        | 3.4%    |
| Apple                                  | 14        | 2.98%   |
| Quanta                                 | 13        | 2.77%   |
| Logitech                               | 12        | 2.55%   |
| Syntek                                 | 8         | 1.7%    |
| Luxvisions Innotech Limited            | 5         | 1.06%   |
| Z-Star Microelectronics                | 4         | 0.85%   |
| Ricoh                                  | 4         | 0.85%   |
| Generalplus Technology                 | 4         | 0.85%   |
| Alcor Micro                            | 4         | 0.85%   |
| Samsung Electronics                    | 3         | 0.64%   |
| Microsoft                              | 3         | 0.64%   |
| Lenovo                                 | 3         | 0.64%   |
| KYE Systems (Mouse Systems)            | 3         | 0.64%   |
| Importek                               | 3         | 0.64%   |
| SunplusIT                              | 2         | 0.43%   |
| Sonix Technology                       | 2         | 0.43%   |
| OmniVision Technologies                | 2         | 0.43%   |
| Leap Motion                            | 2         | 0.43%   |
| Huawei Technologies                    | 2         | 0.43%   |
| Foxconn / Hon Hai                      | 2         | 0.43%   |
| DigiTech                               | 2         | 0.43%   |
| ALi                                    | 2         | 0.43%   |
| Unknown                                | 1         | 0.21%   |
| Sunplus Technology                     | 1         | 0.21%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.21%   |
| Ruision                                | 1         | 0.21%   |
| Mimaki Engineering                     | 1         | 0.21%   |
| MacroSilicon                           | 1         | 0.21%   |
| Jieli Technology                       | 1         | 0.21%   |
| Intel                                  | 1         | 0.21%   |
| GEMBIRD                                | 1         | 0.21%   |
| AVerMedia Technologies                 | 1         | 0.21%   |
| Arkmicro Technologies                  | 1         | 0.21%   |
| ARC International                      | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 19        | 4.01%   |
| Chicony Integrated Camera                                       | 12        | 2.53%   |
| Chicony HD WebCam                                               | 9         | 1.9%    |
| IMC Networks Integrated Camera                                  | 8         | 1.69%   |
| Realtek HP Truevision HD                                        | 7         | 1.48%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 7         | 1.48%   |
| Suyin HP TrueVision HD                                          | 6         | 1.27%   |
| Realtek Integrated_Webcam_HD                                    | 6         | 1.27%   |
| Lite-On Integrated Camera                                       | 6         | 1.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 6         | 1.27%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 6         | 1.27%   |
| Chicony HP Wide Vision HD Camera                                | 6         | 1.27%   |
| Chicony HP Webcam                                               | 6         | 1.27%   |
| Sunplus HP TrueVision HD Camera                                 | 5         | 1.05%   |
| Microdia HP Webcam                                              | 5         | 1.05%   |
| Lite-On HP Wide Vision HD Camera                                | 5         | 1.05%   |
| Chicony HP Truevision HD camera                                 | 5         | 1.05%   |
| Chicony HP Truevision HD                                        | 5         | 1.05%   |
| Chicony EasyCamera                                              | 5         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 5         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 5         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD         | 5         | 1.05%   |
| Acer Integrated Camera                                          | 5         | 1.05%   |
| Syntek Integrated Camera                                        | 4         | 0.84%   |
| Sunplus Laptop Integrated WebCam HD                             | 4         | 0.84%   |
| Silicon Motion WebCam SCB-1100N                                 | 4         | 0.84%   |
| Realtek HP "Truevision HD" laptop camera                        | 4         | 0.84%   |
| Microdia Integrated_Webcam_HD                                   | 4         | 0.84%   |
| Logitech C922 Pro Stream Webcam                                 | 4         | 0.84%   |
| Lite-On HP HD Camera                                            | 4         | 0.84%   |
| Generalplus WEB CAM                                             | 4         | 0.84%   |
| Chicony VGA Webcam                                              | 4         | 0.84%   |
| Chicony HP HD Camera                                            | 4         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 4         | 0.84%   |
| Acer EasyCamera                                                 | 4         | 0.84%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 3         | 0.63%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 3         | 0.63%   |
| Sunplus HD Webcam                                               | 3         | 0.63%   |
| Samsung Galaxy A5 (MTP)                                         | 3         | 0.63%   |
| Realtek USB Camera                                              | 3         | 0.63%   |
| Quanta HP TrueVision HD Camera                                  | 3         | 0.63%   |
| Quanta HD User Facing                                           | 3         | 0.63%   |
| Microdia Webcam SC-10HDD12636P                                  | 3         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 3         | 0.63%   |
| Microdia Amcrest AWC2198 USB Webcam                             | 3         | 0.63%   |
| Logitech Webcam C270                                            | 3         | 0.63%   |
| IMC Networks ov9734_azurewave_camera                            | 3         | 0.63%   |
| Chicony HP 0.3MP Webcam                                         | 3         | 0.63%   |
| Apple FaceTime HD Camera (Built-in)                             | 3         | 0.63%   |
| Apple FaceTime HD Camera                                        | 3         | 0.63%   |
| Syntek Lenovo EasyCamera                                        | 2         | 0.42%   |
| Syntek EasyCamera                                               | 2         | 0.42%   |
| Suyin Integrated_Webcam_HD                                      | 2         | 0.42%   |
| Suyin HD WebCam                                                 | 2         | 0.42%   |
| SunplusIT 720p HD Camera                                        | 2         | 0.42%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 2         | 0.42%   |
| Sunplus Integrated_Webcam_HD                                    | 2         | 0.42%   |
| Sunplus HP Universal Camera                                     | 2         | 0.42%   |
| Sunplus HD 720P webcam                                          | 2         | 0.42%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 28        | 43.08%  |
| Synaptics                  | 18        | 27.69%  |
| Shenzhen Goodix Technology | 4         | 6.15%   |
| AuthenTec                  | 4         | 6.15%   |
| Upek                       | 3         | 4.62%   |
| Elan Microelectronics      | 3         | 4.62%   |
| STMicroelectronics         | 2         | 3.08%   |
| LighTuning Technology      | 2         | 3.08%   |
| Focal-systems.Corp         | 1         | 1.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 10.77%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 9.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 6.15%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 6.15%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 4.62%   |
| Synaptics  WBDI                                                            | 3         | 4.62%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 4.62%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.62%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 4.62%   |
| AuthenTec AES2810                                                          | 3         | 4.62%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.08%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.08%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 3.08%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.08%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.08%   |
| Unknown                                                                    | 2         | 3.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.54%   |
| Validity Sensors VFS491                                                    | 1         | 1.54%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.54%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.54%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.54%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.54%   |
| AuthenTec AES1600                                                          | 1         | 1.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 13        | 81.25%  |
| O2 Micro | 2         | 12.5%   |
| Upek     | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 31.25%  |
| Broadcom 5880                                                                | 4         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 18.75%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 6.25%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 6.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.25%   |
| Broadcom 58200                                                               | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 475       | 72.3%   |
| 1     | 146       | 22.22%  |
| 2     | 31        | 4.72%   |
| 3     | 3         | 0.46%   |
| 5     | 1         | 0.15%   |
| 4     | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 65        | 30.52%  |
| Graphics card            | 45        | 21.13%  |
| Net/wireless             | 35        | 16.43%  |
| Chipcard                 | 15        | 7.04%   |
| Multimedia controller    | 12        | 5.63%   |
| Bluetooth                | 12        | 5.63%   |
| Communication controller | 8         | 3.76%   |
| Unassigned class         | 4         | 1.88%   |
| Storage                  | 4         | 1.88%   |
| Sound                    | 3         | 1.41%   |
| Net/ethernet             | 3         | 1.41%   |
| Camera                   | 3         | 1.41%   |
| Card reader              | 2         | 0.94%   |
| Network                  | 1         | 0.47%   |
| Firewire controller      | 1         | 0.47%   |

