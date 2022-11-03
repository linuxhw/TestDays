Fedora 36 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 36.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 1444

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 7577               | [2a280dc7df](https://linux-hardware.org/?probe=2a280dc7df) | Nov 02, 2022 |
| Lenovo        | ThinkPad T61 6464A13        | [5f850cbab6](https://linux-hardware.org/?probe=5f850cbab6) | Nov 02, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [4fa32ec6af](https://linux-hardware.org/?probe=4fa32ec6af) | Nov 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2d931f9e99](https://linux-hardware.org/?probe=2d931f9e99) | Nov 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [335af8b89b](https://linux-hardware.org/?probe=335af8b89b) | Nov 02, 2022 |
| HP            | Pavilion g6                 | [22b32d9bac](https://linux-hardware.org/?probe=22b32d9bac) | Nov 02, 2022 |
| HUAWEI        | BOD-WXX9                    | [d4ac3a5f04](https://linux-hardware.org/?probe=d4ac3a5f04) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a156a7484d](https://linux-hardware.org/?probe=a156a7484d) | Nov 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [7b51138a0b](https://linux-hardware.org/?probe=7b51138a0b) | Nov 02, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [d3beec5427](https://linux-hardware.org/?probe=d3beec5427) | Nov 02, 2022 |
| HP            | Pavilion g6                 | [24c2a01761](https://linux-hardware.org/?probe=24c2a01761) | Nov 02, 2022 |
| Dell          | Latitude 5591               | [bcd8aef9a0](https://linux-hardware.org/?probe=bcd8aef9a0) | Nov 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [c90b358eb5](https://linux-hardware.org/?probe=c90b358eb5) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | [379443a5d6](https://linux-hardware.org/?probe=379443a5d6) | Nov 01, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | [5e099af04c](https://linux-hardware.org/?probe=5e099af04c) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [766e7fb0d0](https://linux-hardware.org/?probe=766e7fb0d0) | Nov 01, 2022 |
| Unknown       | Unknown                     | [9608724116](https://linux-hardware.org/?probe=9608724116) | Nov 01, 2022 |
| Dell          | Venue 8 Pro 5830            | [8890410dfc](https://linux-hardware.org/?probe=8890410dfc) | Nov 01, 2022 |
| Dell          | Latitude 3420               | [9c2b9ab298](https://linux-hardware.org/?probe=9c2b9ab298) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | [d63c5de91b](https://linux-hardware.org/?probe=d63c5de91b) | Nov 01, 2022 |
| HUAWEI        | BOHB-WAX9                   | [274a3383db](https://linux-hardware.org/?probe=274a3383db) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Samsung       | 800G5M/800G5W               | [c91800e8c1](https://linux-hardware.org/?probe=c91800e8c1) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | [46f1da66b6](https://linux-hardware.org/?probe=46f1da66b6) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | [1409a7f78d](https://linux-hardware.org/?probe=1409a7f78d) | Oct 31, 2022 |
| Acer          | Swift SF314-54              | [71cf98e6e8](https://linux-hardware.org/?probe=71cf98e6e8) | Oct 31, 2022 |
| ASUSTek       | X541UVK                     | [15bdbbf952](https://linux-hardware.org/?probe=15bdbbf952) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Dell          | Precision M6700             | [aa4b5e4400](https://linux-hardware.org/?probe=aa4b5e4400) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [002ab67e5e](https://linux-hardware.org/?probe=002ab67e5e) | Oct 31, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [76906648cb](https://linux-hardware.org/?probe=76906648cb) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [cf460716f9](https://linux-hardware.org/?probe=cf460716f9) | Oct 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| HP            | 15                          | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | ProBook 470 G5              | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [c52b1fe5fa](https://linux-hardware.org/?probe=c52b1fe5fa) | Oct 30, 2022 |
| Dell          | Inspiron 7720               | [f1478df888](https://linux-hardware.org/?probe=f1478df888) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [df654ca0b1](https://linux-hardware.org/?probe=df654ca0b1) | Oct 30, 2022 |
| Dell          | Latitude E7450              | [32a6333f4b](https://linux-hardware.org/?probe=32a6333f4b) | Oct 30, 2022 |
| Aquarius      | Cmp NS765                   | [5e519edbee](https://linux-hardware.org/?probe=5e519edbee) | Oct 30, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [1925c8ce1f](https://linux-hardware.org/?probe=1925c8ce1f) | Oct 29, 2022 |
| Acer          | Predator PH315-53           | [b3dd383a83](https://linux-hardware.org/?probe=b3dd383a83) | Oct 29, 2022 |
| ASUSTek       | X453MA                      | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| ASUSTek       | Q550LF                      | [383c45edce](https://linux-hardware.org/?probe=383c45edce) | Oct 29, 2022 |
| Dell          | Latitude E7450              | [012cd7214b](https://linux-hardware.org/?probe=012cd7214b) | Oct 29, 2022 |
| Dell          | Latitude E7450              | [635a60671d](https://linux-hardware.org/?probe=635a60671d) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [2f6e4235f7](https://linux-hardware.org/?probe=2f6e4235f7) | Oct 28, 2022 |
| Lenovo        | ThinkPad P52 20M9S1EM00     | [40de74c5c5](https://linux-hardware.org/?probe=40de74c5c5) | Oct 28, 2022 |
| HP            | Laptop 15s-fq4xxx           | [e06398e1bc](https://linux-hardware.org/?probe=e06398e1bc) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [83179a6cea](https://linux-hardware.org/?probe=83179a6cea) | Oct 28, 2022 |
| Sony          | VPCCB3S1R                   | [ee5b1465a1](https://linux-hardware.org/?probe=ee5b1465a1) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1d64fb48e7](https://linux-hardware.org/?probe=1d64fb48e7) | Oct 27, 2022 |
| Timi          | TM1701                      | [f246345845](https://linux-hardware.org/?probe=f246345845) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | [3a9f97607d](https://linux-hardware.org/?probe=3a9f97607d) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | [36b663cec7](https://linux-hardware.org/?probe=36b663cec7) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | [e00fd51503](https://linux-hardware.org/?probe=e00fd51503) | Oct 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [99152f7783](https://linux-hardware.org/?probe=99152f7783) | Oct 27, 2022 |
| MSI           | Prestige 14 A10SC           | [263d47772c](https://linux-hardware.org/?probe=263d47772c) | Oct 27, 2022 |
| HP            | EliteBook 8570w             | [7d30f96368](https://linux-hardware.org/?probe=7d30f96368) | Oct 27, 2022 |
| Lenovo        | ThinkPad X260 20F5S2WX05    | [710f95eab8](https://linux-hardware.org/?probe=710f95eab8) | Oct 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [85b4bc70fa](https://linux-hardware.org/?probe=85b4bc70fa) | Oct 26, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| LincPlus      | P1                          | [cc97e9ec36](https://linux-hardware.org/?probe=cc97e9ec36) | Oct 26, 2022 |
| MSI           | Modern 15 A11M              | [0a658be9fc](https://linux-hardware.org/?probe=0a658be9fc) | Oct 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [a8c29545e6](https://linux-hardware.org/?probe=a8c29545e6) | Oct 25, 2022 |
| Dell          | Inspiron 3501               | [6764a6860f](https://linux-hardware.org/?probe=6764a6860f) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | [c9123810fd](https://linux-hardware.org/?probe=c9123810fd) | Oct 25, 2022 |
| Dell          | Latitude 5500               | [6e1b321740](https://linux-hardware.org/?probe=6e1b321740) | Oct 25, 2022 |
| Apple         | MacBookPro11,4              | [29dd6b053b](https://linux-hardware.org/?probe=29dd6b053b) | Oct 25, 2022 |
| Timi          | Mi Laptop Pro 15            | [4474edfd79](https://linux-hardware.org/?probe=4474edfd79) | Oct 25, 2022 |
| Dell          | XPS 15 9510                 | [b14c37f999](https://linux-hardware.org/?probe=b14c37f999) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| ASUSTek       | X540SA                      | [a515dd93cd](https://linux-hardware.org/?probe=a515dd93cd) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [42647c28ba](https://linux-hardware.org/?probe=42647c28ba) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [e4d7dc5f38](https://linux-hardware.org/?probe=e4d7dc5f38) | Oct 25, 2022 |
| System76      | Galago UltraPro             | [caf6a992bb](https://linux-hardware.org/?probe=caf6a992bb) | Oct 24, 2022 |
| Acer          | Aspire ES1-520              | [44375f0b06](https://linux-hardware.org/?probe=44375f0b06) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [95ad909dc8](https://linux-hardware.org/?probe=95ad909dc8) | Oct 24, 2022 |
| HUAWEI        | KPL-W0X                     | [aea737fcab](https://linux-hardware.org/?probe=aea737fcab) | Oct 24, 2022 |
| Dell          | Latitude E6420              | [eb53f0d580](https://linux-hardware.org/?probe=eb53f0d580) | Oct 24, 2022 |
| ASUSTek       | UX310UQ                     | [5a928ace3b](https://linux-hardware.org/?probe=5a928ace3b) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | [c1a4fde481](https://linux-hardware.org/?probe=c1a4fde481) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | [80bf151a4d](https://linux-hardware.org/?probe=80bf151a4d) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [8922b0767c](https://linux-hardware.org/?probe=8922b0767c) | Oct 24, 2022 |
| Lenovo        | ThinkPad X240 20AMS56K00    | [efa84f3716](https://linux-hardware.org/?probe=efa84f3716) | Oct 24, 2022 |
| Acer          | Nitro AN515-46              | [cb2480b22c](https://linux-hardware.org/?probe=cb2480b22c) | Oct 23, 2022 |
| Acer          | Nitro AN515-46              | [846cfe5273](https://linux-hardware.org/?probe=846cfe5273) | Oct 23, 2022 |
| Dell          | Inspiron 3580               | [41dce71fbf](https://linux-hardware.org/?probe=41dce71fbf) | Oct 23, 2022 |
| Acer          | Aspire E5-575G              | [b6b5c1468c](https://linux-hardware.org/?probe=b6b5c1468c) | Oct 23, 2022 |
| Dell          | Inspiron 1564               | [754b4a0f04](https://linux-hardware.org/?probe=754b4a0f04) | Oct 23, 2022 |
| HP            | Notebook                    | [d713217453](https://linux-hardware.org/?probe=d713217453) | Oct 23, 2022 |
| HP            | Notebook                    | [ef9adb0e8a](https://linux-hardware.org/?probe=ef9adb0e8a) | Oct 22, 2022 |
| Purism        | Librem 13 v2                | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| Google        | Swanky                      | [19efb3ecc5](https://linux-hardware.org/?probe=19efb3ecc5) | Oct 21, 2022 |
| ASUSTek       | Q550LF                      | [0d24151944](https://linux-hardware.org/?probe=0d24151944) | Oct 21, 2022 |
| Itautec       | Infoway N8755               | [7eaba382a5](https://linux-hardware.org/?probe=7eaba382a5) | Oct 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [b374c2dff6](https://linux-hardware.org/?probe=b374c2dff6) | Oct 20, 2022 |
| Lenovo        | B560                        | [3a61700f49](https://linux-hardware.org/?probe=3a61700f49) | Oct 20, 2022 |
| Dell          | Inspiron 7460               | [879fabd350](https://linux-hardware.org/?probe=879fabd350) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | [f966d5d584](https://linux-hardware.org/?probe=f966d5d584) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7d35a56915](https://linux-hardware.org/?probe=7d35a56915) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [f81a40a71c](https://linux-hardware.org/?probe=f81a40a71c) | Oct 20, 2022 |
| Dell          | Precision 5510              | [bb7788ce01](https://linux-hardware.org/?probe=bb7788ce01) | Oct 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9594fcc1e0](https://linux-hardware.org/?probe=9594fcc1e0) | Oct 20, 2022 |
| ASUSTek       | K43SJ                       | [4c27c4945c](https://linux-hardware.org/?probe=4c27c4945c) | Oct 20, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [d0dcb7e6e3](https://linux-hardware.org/?probe=d0dcb7e6e3) | Oct 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [866d0f49a2](https://linux-hardware.org/?probe=866d0f49a2) | Oct 20, 2022 |
| Framework     | Laptop                      | [ade55fca33](https://linux-hardware.org/?probe=ade55fca33) | Oct 19, 2022 |
| Framework     | Laptop                      | [57af01b405](https://linux-hardware.org/?probe=57af01b405) | Oct 19, 2022 |
| Dell          | Precision 7760              | [a5ab2793ae](https://linux-hardware.org/?probe=a5ab2793ae) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [680823db07](https://linux-hardware.org/?probe=680823db07) | Oct 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [71734a9abe](https://linux-hardware.org/?probe=71734a9abe) | Oct 19, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HP            | EliteBook 865 16 inch G9... | [8665ee6ba6](https://linux-hardware.org/?probe=8665ee6ba6) | Oct 19, 2022 |
| Lenovo        | Yoga 900-13ISK2 80UE        | [efadc96c65](https://linux-hardware.org/?probe=efadc96c65) | Oct 19, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [eab0779b74](https://linux-hardware.org/?probe=eab0779b74) | Oct 19, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [28a1d15220](https://linux-hardware.org/?probe=28a1d15220) | Oct 18, 2022 |
| MSI           | Modern 14 C12M              | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [aaa41de825](https://linux-hardware.org/?probe=aaa41de825) | Oct 18, 2022 |
| Lenovo        | B560                        | [717af973da](https://linux-hardware.org/?probe=717af973da) | Oct 18, 2022 |
| Dell          | Inspiron M5010              | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| Acer          | Aspire E1-531               | [527c4e0728](https://linux-hardware.org/?probe=527c4e0728) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [76f9929a9c](https://linux-hardware.org/?probe=76f9929a9c) | Oct 17, 2022 |
| MSI           | Summit E16Flip A11UCT       | [f1ec40e34d](https://linux-hardware.org/?probe=f1ec40e34d) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | [9e1f6ae49e](https://linux-hardware.org/?probe=9e1f6ae49e) | Oct 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7f9219a85f](https://linux-hardware.org/?probe=7f9219a85f) | Oct 17, 2022 |
| Dell          | Inspiron 3584               | [c80df2b63c](https://linux-hardware.org/?probe=c80df2b63c) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | [2fd734cbfb](https://linux-hardware.org/?probe=2fd734cbfb) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [528fc3c5ec](https://linux-hardware.org/?probe=528fc3c5ec) | Oct 17, 2022 |
| Dell          | Inspiron 5759               | [f93d1bc535](https://linux-hardware.org/?probe=f93d1bc535) | Oct 17, 2022 |
| Dell          | Inspiron 13 5320            | [9ac52708ad](https://linux-hardware.org/?probe=9ac52708ad) | Oct 17, 2022 |
| Notebook      | W230SS                      | [abb5e7fda8](https://linux-hardware.org/?probe=abb5e7fda8) | Oct 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [f98ff2b890](https://linux-hardware.org/?probe=f98ff2b890) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [f20a72be72](https://linux-hardware.org/?probe=f20a72be72) | Oct 16, 2022 |
| HP            | ProBook 450 G7              | [6a9b93fdeb](https://linux-hardware.org/?probe=6a9b93fdeb) | Oct 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [77c8619d03](https://linux-hardware.org/?probe=77c8619d03) | Oct 16, 2022 |
| Dell          | XPS 13 7390                 | [c78fae026e](https://linux-hardware.org/?probe=c78fae026e) | Oct 16, 2022 |
| Acer          | Aspire E1-531               | [834248c556](https://linux-hardware.org/?probe=834248c556) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0cceedcb07](https://linux-hardware.org/?probe=0cceedcb07) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [dce51f4ce7](https://linux-hardware.org/?probe=dce51f4ce7) | Oct 16, 2022 |
| Lenovo        | ThinkPad X230 23257BG       | [6c8a42718a](https://linux-hardware.org/?probe=6c8a42718a) | Oct 16, 2022 |
| Dell          | Vostro 3400                 | [156e3942e5](https://linux-hardware.org/?probe=156e3942e5) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| Lenovo        | V145-15AST 81MT             | [d73a82b798](https://linux-hardware.org/?probe=d73a82b798) | Oct 15, 2022 |
| Dell          | Latitude E5450              | [68e2c17e2f](https://linux-hardware.org/?probe=68e2c17e2f) | Oct 15, 2022 |
| Acer          | Aspire A314-22              | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Apple         | MacBookPro12,1              | [7979753fa9](https://linux-hardware.org/?probe=7979753fa9) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [bf6d77aefd](https://linux-hardware.org/?probe=bf6d77aefd) | Oct 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ab212a80b4](https://linux-hardware.org/?probe=ab212a80b4) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e1bc46388d](https://linux-hardware.org/?probe=e1bc46388d) | Oct 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49821787e4](https://linux-hardware.org/?probe=49821787e4) | Oct 14, 2022 |
| Dell          | Vostro 3400                 | [f9c2c298c4](https://linux-hardware.org/?probe=f9c2c298c4) | Oct 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f4d190e864](https://linux-hardware.org/?probe=f4d190e864) | Oct 13, 2022 |
| Dell          | XPS 13 7390                 | [60b21aed9a](https://linux-hardware.org/?probe=60b21aed9a) | Oct 13, 2022 |
| HP            | Laptop 15s-du3xxx           | [5985f3564a](https://linux-hardware.org/?probe=5985f3564a) | Oct 13, 2022 |
| Lenovo        | ThinkPad X270 20HMS2R900    | [38739fd54f](https://linux-hardware.org/?probe=38739fd54f) | Oct 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [7af879de72](https://linux-hardware.org/?probe=7af879de72) | Oct 13, 2022 |
| UNOWHY        | Y13G011S4EI                 | [2be4dc3fc2](https://linux-hardware.org/?probe=2be4dc3fc2) | Oct 13, 2022 |
| Gigabyte      | P65Q                        | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| Dell          | XPS 13 9310                 | [8437ac2ffc](https://linux-hardware.org/?probe=8437ac2ffc) | Oct 12, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| Apple         | MacBookPro15,2              | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [0355b3f7b8](https://linux-hardware.org/?probe=0355b3f7b8) | Oct 11, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [60b02deb7f](https://linux-hardware.org/?probe=60b02deb7f) | Oct 11, 2022 |
| Dell          | Vostro 5402                 | [11f3146366](https://linux-hardware.org/?probe=11f3146366) | Oct 11, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [71c926fc14](https://linux-hardware.org/?probe=71c926fc14) | Oct 11, 2022 |
| Lenovo        | ThinkPad P50 20EQS5MP00     | [83858a99c3](https://linux-hardware.org/?probe=83858a99c3) | Oct 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5caff1861e](https://linux-hardware.org/?probe=5caff1861e) | Oct 10, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [dc3347c309](https://linux-hardware.org/?probe=dc3347c309) | Oct 10, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| HUAWEI        | BOD-WXX9                    | [49fff6123f](https://linux-hardware.org/?probe=49fff6123f) | Oct 10, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | [59f6b7653c](https://linux-hardware.org/?probe=59f6b7653c) | Oct 10, 2022 |
| Apple         | MacBookPro9,2               | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| Dell          | Inspiron 5570               | [cab829a52b](https://linux-hardware.org/?probe=cab829a52b) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [6c2f880759](https://linux-hardware.org/?probe=6c2f880759) | Oct 09, 2022 |
| Dell          | XPS 13 9380                 | [5d882bd47f](https://linux-hardware.org/?probe=5d882bd47f) | Oct 09, 2022 |
| HP            | 255 G8 Notebook PC          | [6a56a66eae](https://linux-hardware.org/?probe=6a56a66eae) | Oct 09, 2022 |
| Framework     | Laptop                      | [3d25e7f96c](https://linux-hardware.org/?probe=3d25e7f96c) | Oct 09, 2022 |
| Toshiba       | Satellite C660              | [01abf75c2e](https://linux-hardware.org/?probe=01abf75c2e) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| Acer          | Predator PH315-53           | [cc8b98a2ff](https://linux-hardware.org/?probe=cc8b98a2ff) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| Lenovo        | ThinkPad L470 20J4CTO1WW    | [3aee91df8c](https://linux-hardware.org/?probe=3aee91df8c) | Oct 08, 2022 |
| Dell          | Vostro 3501                 | [126b7b85f2](https://linux-hardware.org/?probe=126b7b85f2) | Oct 08, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3d968cc61a](https://linux-hardware.org/?probe=3d968cc61a) | Oct 08, 2022 |
| Lenovo        | Legion S7 16IAH7 82TF       | [9836cb655c](https://linux-hardware.org/?probe=9836cb655c) | Oct 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [973605d3af](https://linux-hardware.org/?probe=973605d3af) | Oct 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [74f6e9db69](https://linux-hardware.org/?probe=74f6e9db69) | Oct 07, 2022 |
| Dell          | XPS 15 7590                 | [fdab72c478](https://linux-hardware.org/?probe=fdab72c478) | Oct 07, 2022 |
| HP            | ProBook 455 G7              | [26dfdb5aed](https://linux-hardware.org/?probe=26dfdb5aed) | Oct 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [d67006c592](https://linux-hardware.org/?probe=d67006c592) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [08e98e28c2](https://linux-hardware.org/?probe=08e98e28c2) | Oct 07, 2022 |
| HP            | EliteBook 745 G6            | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| Dell          | Latitude 5580               | [4bcae73c95](https://linux-hardware.org/?probe=4bcae73c95) | Oct 07, 2022 |
| Acer          | Nitro AN515-58              | [6a9f611fd5](https://linux-hardware.org/?probe=6a9f611fd5) | Oct 07, 2022 |
| Apple         | MacBookPro9,2               | [d5247cbbc3](https://linux-hardware.org/?probe=d5247cbbc3) | Oct 06, 2022 |
| Dell          | Latitude 5400               | [00789b23c6](https://linux-hardware.org/?probe=00789b23c6) | Oct 06, 2022 |
| HP            | EliteBook 840 14 inch G9... | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [c8c6a428db](https://linux-hardware.org/?probe=c8c6a428db) | Oct 06, 2022 |
| ASUSTek       | X550LA                      | [c0c98c2051](https://linux-hardware.org/?probe=c0c98c2051) | Oct 06, 2022 |
| HP            | 15                          | [9f0981ed52](https://linux-hardware.org/?probe=9f0981ed52) | Oct 06, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | [4fe1810c2c](https://linux-hardware.org/?probe=4fe1810c2c) | Oct 06, 2022 |
| Dell          | Latitude 5400               | [14ed107028](https://linux-hardware.org/?probe=14ed107028) | Oct 05, 2022 |
| Apple         | MacBookPro9,2               | [77176ee82a](https://linux-hardware.org/?probe=77176ee82a) | Oct 05, 2022 |
| Dell          | XPS 17 9710                 | [7590ca8bff](https://linux-hardware.org/?probe=7590ca8bff) | Oct 05, 2022 |
| Dell          | XPS 15 9510                 | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Apple         | MacBookPro14,1              | [3d5136540e](https://linux-hardware.org/?probe=3d5136540e) | Oct 05, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [b78c69e096](https://linux-hardware.org/?probe=b78c69e096) | Oct 04, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [cb204abf9b](https://linux-hardware.org/?probe=cb204abf9b) | Oct 04, 2022 |
| Dell          | Inspiron 13 5310            | [128725bb4d](https://linux-hardware.org/?probe=128725bb4d) | Oct 04, 2022 |
| HP            | Laptop                      | [3a26ec874f](https://linux-hardware.org/?probe=3a26ec874f) | Oct 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [923a579655](https://linux-hardware.org/?probe=923a579655) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | [a9c2a1eca0](https://linux-hardware.org/?probe=a9c2a1eca0) | Oct 03, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [2f9e023d1e](https://linux-hardware.org/?probe=2f9e023d1e) | Oct 03, 2022 |
| Apple         | MacBookPro11,1              | [45a46cdb72](https://linux-hardware.org/?probe=45a46cdb72) | Oct 03, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [92aca0d081](https://linux-hardware.org/?probe=92aca0d081) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [8f24127ac0](https://linux-hardware.org/?probe=8f24127ac0) | Oct 02, 2022 |
| HP            | ProBook 470 G5              | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| Dell          | Inspiron 3543               | [9e5ab25f54](https://linux-hardware.org/?probe=9e5ab25f54) | Oct 02, 2022 |
| Dell          | Inspiron 17-7779            | [5bd534e938](https://linux-hardware.org/?probe=5bd534e938) | Oct 02, 2022 |
| MICROMAX      | Canvas Lapbook L1161        | [9efe9e89d6](https://linux-hardware.org/?probe=9efe9e89d6) | Oct 01, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Dell          | XPS 13 9300                 | [1fade0f247](https://linux-hardware.org/?probe=1fade0f247) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | [49bd2b0248](https://linux-hardware.org/?probe=49bd2b0248) | Oct 01, 2022 |
| Dell          | Inspiron 3442               | [af9b794734](https://linux-hardware.org/?probe=af9b794734) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d5407763a0](https://linux-hardware.org/?probe=d5407763a0) | Sep 30, 2022 |
| Dell          | Latitude E4300              | [a860d9a446](https://linux-hardware.org/?probe=a860d9a446) | Sep 30, 2022 |
| GPD           | G1621-02                    | [6ae9fc596e](https://linux-hardware.org/?probe=6ae9fc596e) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| HP            | ProBook 6570b               | [d9be946342](https://linux-hardware.org/?probe=d9be946342) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | [b15bae8e77](https://linux-hardware.org/?probe=b15bae8e77) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | [126b8dd3ec](https://linux-hardware.org/?probe=126b8dd3ec) | Sep 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | [33353fc67c](https://linux-hardware.org/?probe=33353fc67c) | Sep 30, 2022 |
| SK hynix      | HyBook                      | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [d2a3575975](https://linux-hardware.org/?probe=d2a3575975) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2c6b161d0f](https://linux-hardware.org/?probe=2c6b161d0f) | Sep 29, 2022 |
| Avell High... | A60 MUV                     | [888e375356](https://linux-hardware.org/?probe=888e375356) | Sep 29, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [18afdc2116](https://linux-hardware.org/?probe=18afdc2116) | Sep 29, 2022 |
| HP            | ProBook 440 G7              | [99f729e814](https://linux-hardware.org/?probe=99f729e814) | Sep 29, 2022 |
| Fujitsu       | LIFEBOOK P771               | [7325511d27](https://linux-hardware.org/?probe=7325511d27) | Sep 29, 2022 |
| ASUSTek       | X555LA                      | [5ec700ea0a](https://linux-hardware.org/?probe=5ec700ea0a) | Sep 29, 2022 |
| Acer          | Aspire 5742G                | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [067b155d9b](https://linux-hardware.org/?probe=067b155d9b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [058aa145d3](https://linux-hardware.org/?probe=058aa145d3) | Sep 29, 2022 |
| HP            | 15 Notebook PC              | [23c809d2a7](https://linux-hardware.org/?probe=23c809d2a7) | Sep 29, 2022 |
| Dell          | Precision 7550              | [75f2949521](https://linux-hardware.org/?probe=75f2949521) | Sep 29, 2022 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [9ac63cdce6](https://linux-hardware.org/?probe=9ac63cdce6) | Sep 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [d137298cb5](https://linux-hardware.org/?probe=d137298cb5) | Sep 28, 2022 |
| Dell          | Inspiron 5447               | [b30346135b](https://linux-hardware.org/?probe=b30346135b) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ARE 81W4        | [b784552e84](https://linux-hardware.org/?probe=b784552e84) | Sep 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [84187f87ed](https://linux-hardware.org/?probe=84187f87ed) | Sep 28, 2022 |
| Medion        | Unknown                     | [821c3c8fed](https://linux-hardware.org/?probe=821c3c8fed) | Sep 28, 2022 |
| Alienware     | 14                          | [2d46ecc50e](https://linux-hardware.org/?probe=2d46ecc50e) | Sep 28, 2022 |
| Dell          | Inspiron 5566               | [a4b44081c2](https://linux-hardware.org/?probe=a4b44081c2) | Sep 27, 2022 |
| Lenovo        | G40-80 80JE                 | [a6347449b3](https://linux-hardware.org/?probe=a6347449b3) | Sep 27, 2022 |
| Chuwi         | HeroBook Air                | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| MSI           | GS66 Stealth 10SGS          | [644efb07cf](https://linux-hardware.org/?probe=644efb07cf) | Sep 27, 2022 |
| HONOR         | HGE-WX6                     | [5c61df4d20](https://linux-hardware.org/?probe=5c61df4d20) | Sep 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6677830ce4](https://linux-hardware.org/?probe=6677830ce4) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [3d86bcf1b7](https://linux-hardware.org/?probe=3d86bcf1b7) | Sep 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [c60d7e3375](https://linux-hardware.org/?probe=c60d7e3375) | Sep 27, 2022 |
| HP            | ProBook 450 G4              | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| MSI           | GT72 6QE                    | [5535b3367e](https://linux-hardware.org/?probe=5535b3367e) | Sep 26, 2022 |
| Acer          | Aspire E1-570G              | [ed657bfbb6](https://linux-hardware.org/?probe=ed657bfbb6) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| Dell          | XPS 17 9700                 | [76166adede](https://linux-hardware.org/?probe=76166adede) | Sep 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [f1d78ca455](https://linux-hardware.org/?probe=f1d78ca455) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| MSI           | GT72 6QE                    | [d739812ce7](https://linux-hardware.org/?probe=d739812ce7) | Sep 26, 2022 |
| MSI           | GT72S 6QE                   | [7ec3a25453](https://linux-hardware.org/?probe=7ec3a25453) | Sep 26, 2022 |
| HP            | Laptop                      | [6d8fc869e4](https://linux-hardware.org/?probe=6d8fc869e4) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [52a86d0701](https://linux-hardware.org/?probe=52a86d0701) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [683aa83ea4](https://linux-hardware.org/?probe=683aa83ea4) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | [64fd780b2f](https://linux-hardware.org/?probe=64fd780b2f) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | [d557cdbe1c](https://linux-hardware.org/?probe=d557cdbe1c) | Sep 26, 2022 |
| HP            | Laptop                      | [be59fc7a97](https://linux-hardware.org/?probe=be59fc7a97) | Sep 26, 2022 |
| HP            | EliteBook Folio 9480m       | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f8b76ec5f4](https://linux-hardware.org/?probe=f8b76ec5f4) | Sep 25, 2022 |
| AZW           | SEi                         | [063c3cc52e](https://linux-hardware.org/?probe=063c3cc52e) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| Apple         | MacBookPro14,1              | [f5e9524bff](https://linux-hardware.org/?probe=f5e9524bff) | Sep 25, 2022 |
| Apple         | MacBookPro16,1              | [6e7d310781](https://linux-hardware.org/?probe=6e7d310781) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| HP            | Pavilion dv6                | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [2082a8668b](https://linux-hardware.org/?probe=2082a8668b) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | [72caf18b5f](https://linux-hardware.org/?probe=72caf18b5f) | Sep 23, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [c30d8893ca](https://linux-hardware.org/?probe=c30d8893ca) | Sep 23, 2022 |
| HONOR         | HGE-WX6                     | [337c1097ef](https://linux-hardware.org/?probe=337c1097ef) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [f72f370511](https://linux-hardware.org/?probe=f72f370511) | Sep 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a5e851730c](https://linux-hardware.org/?probe=a5e851730c) | Sep 23, 2022 |
| Acer          | Aspire A715-43G             | [5ecaaef0b1](https://linux-hardware.org/?probe=5ecaaef0b1) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [c916654073](https://linux-hardware.org/?probe=c916654073) | Sep 22, 2022 |
| VALE          | Notebook Classic C140       | [5a8e431c98](https://linux-hardware.org/?probe=5a8e431c98) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4d47a6bfcf](https://linux-hardware.org/?probe=4d47a6bfcf) | Sep 22, 2022 |
| Dell          | Precision 5540              | [0f09e447ea](https://linux-hardware.org/?probe=0f09e447ea) | Sep 22, 2022 |
| Dell          | Vostro 3558                 | [61f6c99c88](https://linux-hardware.org/?probe=61f6c99c88) | Sep 22, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [efaa235d34](https://linux-hardware.org/?probe=efaa235d34) | Sep 22, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [2250b3380d](https://linux-hardware.org/?probe=2250b3380d) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [ba5fdd39e6](https://linux-hardware.org/?probe=ba5fdd39e6) | Sep 21, 2022 |
| Framework     | Laptop                      | [8e2d92c817](https://linux-hardware.org/?probe=8e2d92c817) | Sep 21, 2022 |
| HP            | 15 Notebook PC              | [9515dd24c0](https://linux-hardware.org/?probe=9515dd24c0) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | [2e5553125e](https://linux-hardware.org/?probe=2e5553125e) | Sep 21, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [85cab20988](https://linux-hardware.org/?probe=85cab20988) | Sep 21, 2022 |
| Razer         | Blade                       | [c835fe2f90](https://linux-hardware.org/?probe=c835fe2f90) | Sep 21, 2022 |
| Acer          | Nitro AN515-57              | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | [deb8b0ca78](https://linux-hardware.org/?probe=deb8b0ca78) | Sep 21, 2022 |
| HP            | Pavilion Power Laptop 15... | [360e860fb1](https://linux-hardware.org/?probe=360e860fb1) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [7561f24877](https://linux-hardware.org/?probe=7561f24877) | Sep 20, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [32120dfcd4](https://linux-hardware.org/?probe=32120dfcd4) | Sep 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [98771092de](https://linux-hardware.org/?probe=98771092de) | Sep 20, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | [20c7b9dcf9](https://linux-hardware.org/?probe=20c7b9dcf9) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | [f4aade3998](https://linux-hardware.org/?probe=f4aade3998) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [21617c5cff](https://linux-hardware.org/?probe=21617c5cff) | Sep 20, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | [95c8201663](https://linux-hardware.org/?probe=95c8201663) | Sep 20, 2022 |
| HP            | ProBook 455 G7              | [80d61eb345](https://linux-hardware.org/?probe=80d61eb345) | Sep 20, 2022 |
| Lenovo        | ThinkPad T420 4180PBG       | [857b2acef0](https://linux-hardware.org/?probe=857b2acef0) | Sep 20, 2022 |
| Dell          | XPS 15 9550                 | [acf36b1555](https://linux-hardware.org/?probe=acf36b1555) | Sep 20, 2022 |
| HP            | ENVY 15                     | [6921f93893](https://linux-hardware.org/?probe=6921f93893) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| Apple         | MacBookPro9,2               | [a681a7cab8](https://linux-hardware.org/?probe=a681a7cab8) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [bed329dab4](https://linux-hardware.org/?probe=bed329dab4) | Sep 19, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0RK0... | [eaaf80509b](https://linux-hardware.org/?probe=eaaf80509b) | Sep 19, 2022 |
| Toshiba       | Satellite L40t-A            | [b09254248d](https://linux-hardware.org/?probe=b09254248d) | Sep 19, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [9b14ec4438](https://linux-hardware.org/?probe=9b14ec4438) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | [ede9aab3fb](https://linux-hardware.org/?probe=ede9aab3fb) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [db46d34737](https://linux-hardware.org/?probe=db46d34737) | Sep 19, 2022 |
| ASUSTek       | GL502VMK                    | [9776f2c20c](https://linux-hardware.org/?probe=9776f2c20c) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [474f619a29](https://linux-hardware.org/?probe=474f619a29) | Sep 19, 2022 |
| Dell          | Latitude E6520              | [ac5b5a53a2](https://linux-hardware.org/?probe=ac5b5a53a2) | Sep 19, 2022 |
| Dell          | Precision 5560              | [5e70cfd82f](https://linux-hardware.org/?probe=5e70cfd82f) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [bb8fdeb489](https://linux-hardware.org/?probe=bb8fdeb489) | Sep 19, 2022 |
| Dell          | Latitude 5420               | [1e5a1652cc](https://linux-hardware.org/?probe=1e5a1652cc) | Sep 19, 2022 |
| Lenovo        | ThinkPad T430 2349S4D       | [0c4d98868f](https://linux-hardware.org/?probe=0c4d98868f) | Sep 19, 2022 |
| Dell          | Vostro 3500                 | [f114799ded](https://linux-hardware.org/?probe=f114799ded) | Sep 18, 2022 |
| Dell          | Latitude 3420               | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [b9bb35af47](https://linux-hardware.org/?probe=b9bb35af47) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [2032e77931](https://linux-hardware.org/?probe=2032e77931) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [751df30316](https://linux-hardware.org/?probe=751df30316) | Sep 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECC... | [e09b077e89](https://linux-hardware.org/?probe=e09b077e89) | Sep 18, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [1f9f8ee511](https://linux-hardware.org/?probe=1f9f8ee511) | Sep 18, 2022 |
| Dell          | Inspiron N5110              | [fa2122b6ee](https://linux-hardware.org/?probe=fa2122b6ee) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| Apple         | MacBookPro12,1              | [ba54a7bf0c](https://linux-hardware.org/?probe=ba54a7bf0c) | Sep 17, 2022 |
| Dell          | Vostro 3500                 | [fd0bcfd41d](https://linux-hardware.org/?probe=fd0bcfd41d) | Sep 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [3b0169723f](https://linux-hardware.org/?probe=3b0169723f) | Sep 17, 2022 |
| Apple         | MacBookPro16,1              | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| Toshiba       | Satellite C660              | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| Dell          | G3 3779                     | [5c24653999](https://linux-hardware.org/?probe=5c24653999) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [70a944e816](https://linux-hardware.org/?probe=70a944e816) | Sep 16, 2022 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [50669d6ff9](https://linux-hardware.org/?probe=50669d6ff9) | Sep 16, 2022 |
| Acidanther... | iMac19,2                    | [94b79ac6e5](https://linux-hardware.org/?probe=94b79ac6e5) | Sep 16, 2022 |
| Dell          | Latitude 5511               | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| Acer          | Nitro AN515-58              | [a29728a871](https://linux-hardware.org/?probe=a29728a871) | Sep 16, 2022 |
| Dell          | Inspiron 5567               | [1cbebfbe09](https://linux-hardware.org/?probe=1cbebfbe09) | Sep 16, 2022 |
| ASUSTek       | X550JK                      | [5c399f4fb0](https://linux-hardware.org/?probe=5c399f4fb0) | Sep 15, 2022 |
| ASUSTek       | X550JK                      | [59df382a23](https://linux-hardware.org/?probe=59df382a23) | Sep 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [80638ed98f](https://linux-hardware.org/?probe=80638ed98f) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c70951aae5](https://linux-hardware.org/?probe=c70951aae5) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [4b19ce2aab](https://linux-hardware.org/?probe=4b19ce2aab) | Sep 15, 2022 |
| Dell          | Inspiron N5110              | [f566a009c8](https://linux-hardware.org/?probe=f566a009c8) | Sep 15, 2022 |
| HP            | Snappy                      | [d890c80994](https://linux-hardware.org/?probe=d890c80994) | Sep 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [6d4adb2a44](https://linux-hardware.org/?probe=6d4adb2a44) | Sep 14, 2022 |
| HP            | EliteBook 8460p             | [d34c655d2b](https://linux-hardware.org/?probe=d34c655d2b) | Sep 14, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [efb36530f1](https://linux-hardware.org/?probe=efb36530f1) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [bbc3c68696](https://linux-hardware.org/?probe=bbc3c68696) | Sep 14, 2022 |
| Dell          | Latitude 5521               | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3f34e5ed01](https://linux-hardware.org/?probe=3f34e5ed01) | Sep 14, 2022 |
| Dell          | Inspiron 5575               | [1ae871a545](https://linux-hardware.org/?probe=1ae871a545) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [d1b95841a4](https://linux-hardware.org/?probe=d1b95841a4) | Sep 13, 2022 |
| Dell          | Precision 5560              | [78809c82c2](https://linux-hardware.org/?probe=78809c82c2) | Sep 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| HP            | EliteBook 745 G6            | [61da5fee97](https://linux-hardware.org/?probe=61da5fee97) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [472668e67b](https://linux-hardware.org/?probe=472668e67b) | Sep 12, 2022 |
| Lanix         | AL V9                       | [e03f9aecc3](https://linux-hardware.org/?probe=e03f9aecc3) | Sep 12, 2022 |
| Dell          | Latitude 5495               | [23586ab4ef](https://linux-hardware.org/?probe=23586ab4ef) | Sep 12, 2022 |
| Lenovo        | ThinkPad P1 20MD0014RT      | [4935debbce](https://linux-hardware.org/?probe=4935debbce) | Sep 12, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [a901769629](https://linux-hardware.org/?probe=a901769629) | Sep 12, 2022 |
| AZW           | SEi                         | [3a4d2086b0](https://linux-hardware.org/?probe=3a4d2086b0) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a54854cd7](https://linux-hardware.org/?probe=4a54854cd7) | Sep 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [5bbf96fe23](https://linux-hardware.org/?probe=5bbf96fe23) | Sep 12, 2022 |
| ASUSTek       | ROG Strix G713QR_G713QR     | [d05595b19e](https://linux-hardware.org/?probe=d05595b19e) | Sep 12, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [47b15d6b6c](https://linux-hardware.org/?probe=47b15d6b6c) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [edb2842417](https://linux-hardware.org/?probe=edb2842417) | Sep 12, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [c6df51fa3b](https://linux-hardware.org/?probe=c6df51fa3b) | Sep 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [7064ea27f5](https://linux-hardware.org/?probe=7064ea27f5) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| Acer          | Nitro AN515-58              | [49fe1c56a3](https://linux-hardware.org/?probe=49fe1c56a3) | Sep 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| Apple         | MacBookPro12,1              | [4bb5badf61](https://linux-hardware.org/?probe=4bb5badf61) | Sep 10, 2022 |
| ASUSTek       | UX310UQK                    | [dc650f1d77](https://linux-hardware.org/?probe=dc650f1d77) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [8fb4287325](https://linux-hardware.org/?probe=8fb4287325) | Sep 10, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [0a7b65b735](https://linux-hardware.org/?probe=0a7b65b735) | Sep 09, 2022 |
| Dell          | Inspiron 3543               | [7fc528e246](https://linux-hardware.org/?probe=7fc528e246) | Sep 09, 2022 |
| Dell          | XPS 15 9570                 | [a54dae9e4b](https://linux-hardware.org/?probe=a54dae9e4b) | Sep 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [cada1ee58d](https://linux-hardware.org/?probe=cada1ee58d) | Sep 09, 2022 |
| Apple         | MacBookPro9,2               | [9f2534b22e](https://linux-hardware.org/?probe=9f2534b22e) | Sep 09, 2022 |
| Notebook      | W230SS                      | [9ea483f3dd](https://linux-hardware.org/?probe=9ea483f3dd) | Sep 09, 2022 |
| Dell          | Inspiron 5566               | [7d9ebaa4f8](https://linux-hardware.org/?probe=7d9ebaa4f8) | Sep 09, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [8242cc3cab](https://linux-hardware.org/?probe=8242cc3cab) | Sep 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [30488e19df](https://linux-hardware.org/?probe=30488e19df) | Sep 08, 2022 |
| Dell          | Latitude E5450              | [305ef21301](https://linux-hardware.org/?probe=305ef21301) | Sep 08, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | [0bcf279fb8](https://linux-hardware.org/?probe=0bcf279fb8) | Sep 08, 2022 |
| Dell          | Precision 5770              | [41e44b27f4](https://linux-hardware.org/?probe=41e44b27f4) | Sep 08, 2022 |
| Dell          | XPS 13 9305                 | [bc21b4b2a8](https://linux-hardware.org/?probe=bc21b4b2a8) | Sep 07, 2022 |
| Dell          | XPS 13 7390                 | [f91eeba2bd](https://linux-hardware.org/?probe=f91eeba2bd) | Sep 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [dce2728dad](https://linux-hardware.org/?probe=dce2728dad) | Sep 07, 2022 |
| Dell          | Latitude E6420              | [8885f409d8](https://linux-hardware.org/?probe=8885f409d8) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | [a90b385c8e](https://linux-hardware.org/?probe=a90b385c8e) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | [7a3494a230](https://linux-hardware.org/?probe=7a3494a230) | Sep 07, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | [673c26165e](https://linux-hardware.org/?probe=673c26165e) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [d3d092e789](https://linux-hardware.org/?probe=d3d092e789) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c905c86c47](https://linux-hardware.org/?probe=c905c86c47) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [424adc035f](https://linux-hardware.org/?probe=424adc035f) | Sep 07, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [ff127ee255](https://linux-hardware.org/?probe=ff127ee255) | Sep 06, 2022 |
| HP            | EliteBook 850 G6            | [7c202a088d](https://linux-hardware.org/?probe=7c202a088d) | Sep 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [826deb0c55](https://linux-hardware.org/?probe=826deb0c55) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [bffe658238](https://linux-hardware.org/?probe=bffe658238) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b327372b50](https://linux-hardware.org/?probe=b327372b50) | Sep 05, 2022 |
| MSI           | Prestige 15 A10SC           | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [3969240177](https://linux-hardware.org/?probe=3969240177) | Sep 05, 2022 |
| Dell          | Inspiron 16 5625            | [d38282759b](https://linux-hardware.org/?probe=d38282759b) | Sep 05, 2022 |
| Dell          | Latitude 7490               | [4a59725d2d](https://linux-hardware.org/?probe=4a59725d2d) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| Samsung       | 550P5C/550P7C               | [9d9451305b](https://linux-hardware.org/?probe=9d9451305b) | Sep 05, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [4641fe397a](https://linux-hardware.org/?probe=4641fe397a) | Sep 05, 2022 |
| Dell          | Latitude 5511               | [3193c29c67](https://linux-hardware.org/?probe=3193c29c67) | Sep 04, 2022 |
| Chuwi         | Hi10 Go                     | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [57f8a4e96b](https://linux-hardware.org/?probe=57f8a4e96b) | Sep 04, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [f0bcadac2f](https://linux-hardware.org/?probe=f0bcadac2f) | Sep 04, 2022 |
| Lenovo        | ThinkPad X230 2320HPU       | [a8ba64ec12](https://linux-hardware.org/?probe=a8ba64ec12) | Sep 04, 2022 |
| HUAWEI        | KLVD-WXX9                   | [cc383de755](https://linux-hardware.org/?probe=cc383de755) | Sep 04, 2022 |
| Lenovo        | ThinkPad E560 20EV000RGE    | [5b69ce9986](https://linux-hardware.org/?probe=5b69ce9986) | Sep 04, 2022 |
| Acer          | AS VN7-571G                 | [1c14fbaf96](https://linux-hardware.org/?probe=1c14fbaf96) | Sep 04, 2022 |
| Dell          | Latitude 5420               | [b236b791c1](https://linux-hardware.org/?probe=b236b791c1) | Sep 04, 2022 |
| Lenovo        | 3000 N200 0769BAG           | [33fcb3e2b3](https://linux-hardware.org/?probe=33fcb3e2b3) | Sep 04, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [c4db289b99](https://linux-hardware.org/?probe=c4db289b99) | Sep 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a0b2975bf7](https://linux-hardware.org/?probe=a0b2975bf7) | Sep 04, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [dc3fd2d992](https://linux-hardware.org/?probe=dc3fd2d992) | Sep 03, 2022 |
| HP            | EliteBook 8470p             | [109d233976](https://linux-hardware.org/?probe=109d233976) | Sep 03, 2022 |
| Samsung       | 550P5C/550P7C               | [6aac0a8c6c](https://linux-hardware.org/?probe=6aac0a8c6c) | Sep 03, 2022 |
| Dell          | Vostro 1320                 | [e66853cc37](https://linux-hardware.org/?probe=e66853cc37) | Sep 03, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [758f8d2184](https://linux-hardware.org/?probe=758f8d2184) | Sep 03, 2022 |
| ASUSTek       | UX310UQK                    | [ed392e6b79](https://linux-hardware.org/?probe=ed392e6b79) | Sep 03, 2022 |
| ASUSTek       | GL503VM                     | [43cbef1764](https://linux-hardware.org/?probe=43cbef1764) | Sep 03, 2022 |
| MSI           | GP72MVR 7RFX                | [f370d7bbc3](https://linux-hardware.org/?probe=f370d7bbc3) | Sep 03, 2022 |
| Dell          | XPS 15 9570                 | [b73e153667](https://linux-hardware.org/?probe=b73e153667) | Sep 03, 2022 |
| HP            | Stream Notebook PC 13       | [d6c9e33a55](https://linux-hardware.org/?probe=d6c9e33a55) | Sep 03, 2022 |
| MSI           | Modern 14 B11MOL            | [92d3e81be7](https://linux-hardware.org/?probe=92d3e81be7) | Sep 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [cec0b91aa9](https://linux-hardware.org/?probe=cec0b91aa9) | Sep 03, 2022 |
| Toshiba       | Satellite C850-C5K          | [51dbca1f4d](https://linux-hardware.org/?probe=51dbca1f4d) | Sep 03, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [1ce3a883a0](https://linux-hardware.org/?probe=1ce3a883a0) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001JIX     | [30eb9dcb39](https://linux-hardware.org/?probe=30eb9dcb39) | Sep 03, 2022 |
| Alienware     | 14                          | [f30f3ddf3d](https://linux-hardware.org/?probe=f30f3ddf3d) | Sep 03, 2022 |
| HP            | EliteBook 8470p             | [33ae7d4c4b](https://linux-hardware.org/?probe=33ae7d4c4b) | Sep 03, 2022 |
| Acer          | Swift SF315-41              | [634777751a](https://linux-hardware.org/?probe=634777751a) | Sep 02, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [006c26eaa0](https://linux-hardware.org/?probe=006c26eaa0) | Sep 02, 2022 |
| Acer          | Swift SF315-41              | [dd250df1ef](https://linux-hardware.org/?probe=dd250df1ef) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [aa9a637495](https://linux-hardware.org/?probe=aa9a637495) | Sep 02, 2022 |
| Lenovo        | V14-ADA 82C6                | [5e98ea70fb](https://linux-hardware.org/?probe=5e98ea70fb) | Sep 02, 2022 |
| Lenovo        | G50-45 80E3                 | [a8e1884f32](https://linux-hardware.org/?probe=a8e1884f32) | Sep 02, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [1f0f793a37](https://linux-hardware.org/?probe=1f0f793a37) | Sep 02, 2022 |
| Dell          | Inspiron 5558               | [203baa4d7f](https://linux-hardware.org/?probe=203baa4d7f) | Sep 02, 2022 |
| Dell          | Latitude E6400              | [c781ec4733](https://linux-hardware.org/?probe=c781ec4733) | Sep 02, 2022 |
| Chuwi         | HeroBook Air                | [1ac18273da](https://linux-hardware.org/?probe=1ac18273da) | Sep 02, 2022 |
| Dell          | Inspiron 5490               | [3ef6519b6d](https://linux-hardware.org/?probe=3ef6519b6d) | Sep 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [e4a4630b4e](https://linux-hardware.org/?probe=e4a4630b4e) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5ad5d3809b](https://linux-hardware.org/?probe=5ad5d3809b) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [b6b7c6dc62](https://linux-hardware.org/?probe=b6b7c6dc62) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [6b3c188071](https://linux-hardware.org/?probe=6b3c188071) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [b0d6660da8](https://linux-hardware.org/?probe=b0d6660da8) | Sep 01, 2022 |
| Dell          | Inspiron 3542               | [945ec7d987](https://linux-hardware.org/?probe=945ec7d987) | Sep 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [c86e73aed6](https://linux-hardware.org/?probe=c86e73aed6) | Sep 01, 2022 |
| ASUSTek       | X541UJ                      | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| Dell          | Latitude 7430               | [8876fb0448](https://linux-hardware.org/?probe=8876fb0448) | Aug 31, 2022 |
| Eluktronic... | MAG-15 2070                 | [d7fb373622](https://linux-hardware.org/?probe=d7fb373622) | Aug 31, 2022 |
| Dell          | Latitude E5570              | [91513d0ee3](https://linux-hardware.org/?probe=91513d0ee3) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [30457b898c](https://linux-hardware.org/?probe=30457b898c) | Aug 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [7399a32997](https://linux-hardware.org/?probe=7399a32997) | Aug 30, 2022 |
| HP            | 255 G8 Notebook PC          | [c96e8a8254](https://linux-hardware.org/?probe=c96e8a8254) | Aug 30, 2022 |
| Dell          | G3 3579                     | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| HP            | Laptop 14-fq1xxx            | [8ea91d6b4b](https://linux-hardware.org/?probe=8ea91d6b4b) | Aug 30, 2022 |
| HP            | 250 G7 Notebook PC          | [96a56c7cb9](https://linux-hardware.org/?probe=96a56c7cb9) | Aug 30, 2022 |
| Dell          | Inspiron 15 5510            | [346eda373e](https://linux-hardware.org/?probe=346eda373e) | Aug 29, 2022 |
| Dell          | Inspiron 15 5510            | [ecdb2875da](https://linux-hardware.org/?probe=ecdb2875da) | Aug 29, 2022 |
| Dell          | Inspiron 5721               | [d483434965](https://linux-hardware.org/?probe=d483434965) | Aug 29, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [473daa5ce3](https://linux-hardware.org/?probe=473daa5ce3) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c407e3a17c](https://linux-hardware.org/?probe=c407e3a17c) | Aug 29, 2022 |
| MSI           | Prestige 14Evo A11MO        | [22cf60f50b](https://linux-hardware.org/?probe=22cf60f50b) | Aug 29, 2022 |
| Infinix       | INBOOK X2                   | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [d82227c6d3](https://linux-hardware.org/?probe=d82227c6d3) | Aug 29, 2022 |
| Dell          | Precision 5750              | [2ee41b471e](https://linux-hardware.org/?probe=2ee41b471e) | Aug 28, 2022 |
| HUAWEI        | KLVL-WXXW                   | [829a45ed6f](https://linux-hardware.org/?probe=829a45ed6f) | Aug 28, 2022 |
| Google        | Eve                         | [4c83027c9a](https://linux-hardware.org/?probe=4c83027c9a) | Aug 28, 2022 |
| Dell          | Precision 5750              | [af9992756f](https://linux-hardware.org/?probe=af9992756f) | Aug 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [af00be0ff8](https://linux-hardware.org/?probe=af00be0ff8) | Aug 28, 2022 |
| HP            | ProBook 650 G1              | [7738c266d6](https://linux-hardware.org/?probe=7738c266d6) | Aug 28, 2022 |
| Apple         | MacBookPro8,1               | [5efa863ca3](https://linux-hardware.org/?probe=5efa863ca3) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Dell          | Inspiron 3442               | [46a68b981e](https://linux-hardware.org/?probe=46a68b981e) | Aug 27, 2022 |
| Apple         | MacBookAir6,2               | [0454b1e087](https://linux-hardware.org/?probe=0454b1e087) | Aug 27, 2022 |
| Acidanther... | MacBookPro12,1              | [9e48c5e245](https://linux-hardware.org/?probe=9e48c5e245) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [559d6f0e42](https://linux-hardware.org/?probe=559d6f0e42) | Aug 27, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [f4dd9de519](https://linux-hardware.org/?probe=f4dd9de519) | Aug 27, 2022 |
| Acer          | Nitro AN515-57              | [8d314e1557](https://linux-hardware.org/?probe=8d314e1557) | Aug 27, 2022 |
| Lenovo        | G50-45 80E3                 | [be9921e0e0](https://linux-hardware.org/?probe=be9921e0e0) | Aug 27, 2022 |
| HP            | EliteBook 840 G5            | [7bd19ce9a1](https://linux-hardware.org/?probe=7bd19ce9a1) | Aug 27, 2022 |
| Exo           | Smart Serie L               | [5cbaef571b](https://linux-hardware.org/?probe=5cbaef571b) | Aug 27, 2022 |
| Acer          | Aspire VN7-592G             | [cec4df79eb](https://linux-hardware.org/?probe=cec4df79eb) | Aug 26, 2022 |
| HP            | ProBook 4530s               | [be1270c998](https://linux-hardware.org/?probe=be1270c998) | Aug 26, 2022 |
| ASUSTek       | X541NA                      | [4755f121e3](https://linux-hardware.org/?probe=4755f121e3) | Aug 26, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Dell          | Inspiron 3593               | [c3ae4b86ac](https://linux-hardware.org/?probe=c3ae4b86ac) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| MSI           | Modern 14 A10RAS            | [af216b7b4a](https://linux-hardware.org/?probe=af216b7b4a) | Aug 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [2b52864870](https://linux-hardware.org/?probe=2b52864870) | Aug 25, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| HP            | Pavilion dv6                | [7fd7791035](https://linux-hardware.org/?probe=7fd7791035) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [4378f177a8](https://linux-hardware.org/?probe=4378f177a8) | Aug 24, 2022 |
| HP            | Laptop 15s-fq2xxx           | [f8213e35a4](https://linux-hardware.org/?probe=f8213e35a4) | Aug 24, 2022 |
| GPU Compan... | GWTC116-2                   | [f9090c46a9](https://linux-hardware.org/?probe=f9090c46a9) | Aug 24, 2022 |
| GPU Compan... | GWTC116-2                   | [ac93dd480f](https://linux-hardware.org/?probe=ac93dd480f) | Aug 24, 2022 |
| ASUSTek       | T100HAN                     | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [1e79d17c85](https://linux-hardware.org/?probe=1e79d17c85) | Aug 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [33c24103bf](https://linux-hardware.org/?probe=33c24103bf) | Aug 23, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [1b1c9cb460](https://linux-hardware.org/?probe=1b1c9cb460) | Aug 23, 2022 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | [2e88f854f8](https://linux-hardware.org/?probe=2e88f854f8) | Aug 23, 2022 |
| Dell          | Inspiron 5567               | [7b0f03259b](https://linux-hardware.org/?probe=7b0f03259b) | Aug 23, 2022 |
| Dell          | XPS L421X                   | [80a474140e](https://linux-hardware.org/?probe=80a474140e) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Aquarius      | Cmp NS765                   | [991487a61b](https://linux-hardware.org/?probe=991487a61b) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Apple         | MacBookPro5,5               | [f25926e1fa](https://linux-hardware.org/?probe=f25926e1fa) | Aug 22, 2022 |
| Apple         | MacBookPro5,5               | [784c6d89a6](https://linux-hardware.org/?probe=784c6d89a6) | Aug 22, 2022 |
| Apple         | MacBookPro11,2              | [9856ca2463](https://linux-hardware.org/?probe=9856ca2463) | Aug 21, 2022 |
| Acer          | TravelMate P215-52G         | [1d36fcbc9f](https://linux-hardware.org/?probe=1d36fcbc9f) | Aug 21, 2022 |
| HP            | Compaq 15                   | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| Acer          | Aspire E1-522               | [f4f0162d9a](https://linux-hardware.org/?probe=f4f0162d9a) | Aug 21, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [98b92cfe3a](https://linux-hardware.org/?probe=98b92cfe3a) | Aug 21, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [390e67b458](https://linux-hardware.org/?probe=390e67b458) | Aug 21, 2022 |
| Acer          | Popcorn                     | [1c3d0d6b87](https://linux-hardware.org/?probe=1c3d0d6b87) | Aug 21, 2022 |
| HUAWEI        | EMD-WXX                     | [1ee66f2c65](https://linux-hardware.org/?probe=1ee66f2c65) | Aug 20, 2022 |
| HP            | ENVY Notebook               | [7d790e2b4d](https://linux-hardware.org/?probe=7d790e2b4d) | Aug 20, 2022 |
| HONOR         | NBD-WXX9                    | [1fdf41de8b](https://linux-hardware.org/?probe=1fdf41de8b) | Aug 20, 2022 |
| Dell          | Latitude E6430              | [c7a98ce916](https://linux-hardware.org/?probe=c7a98ce916) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZE... | [8dd3a87210](https://linux-hardware.org/?probe=8dd3a87210) | Aug 20, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [93c259f492](https://linux-hardware.org/?probe=93c259f492) | Aug 20, 2022 |
| ASUSTek       | Zephyrus S GX531GX_GX531... | [0041774402](https://linux-hardware.org/?probe=0041774402) | Aug 20, 2022 |
| HP            | ProBook 655 G1              | [e37e59a165](https://linux-hardware.org/?probe=e37e59a165) | Aug 20, 2022 |
| Dell          | Inspiron M5010              | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| Fujitsu       | LIFEBOOK UH552              | [ad8ec93f74](https://linux-hardware.org/?probe=ad8ec93f74) | Aug 19, 2022 |
| Dell          | Inspiron 5490               | [98f795ee5f](https://linux-hardware.org/?probe=98f795ee5f) | Aug 19, 2022 |
| HUAWEI        | EMD-WXX                     | [9c4217c76b](https://linux-hardware.org/?probe=9c4217c76b) | Aug 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [81be616c6b](https://linux-hardware.org/?probe=81be616c6b) | Aug 19, 2022 |
| Apple         | MacBook6,1                  | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| ASUSTek       | K45A                        | [b007d7ae1d](https://linux-hardware.org/?probe=b007d7ae1d) | Aug 18, 2022 |
| Lenovo        | ThinkPad E520 1143CWG       | [bc6f3f891a](https://linux-hardware.org/?probe=bc6f3f891a) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| Acidanther... | MacBookPro12,1              | [6afa5c842e](https://linux-hardware.org/?probe=6afa5c842e) | Aug 18, 2022 |
| Acer          | Aspire A515-45              | [9e48793165](https://linux-hardware.org/?probe=9e48793165) | Aug 18, 2022 |
| Acer          | Aspire E5-573               | [1815c3a2f2](https://linux-hardware.org/?probe=1815c3a2f2) | Aug 17, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | [cfc3d5853c](https://linux-hardware.org/?probe=cfc3d5853c) | Aug 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7f3311afd4](https://linux-hardware.org/?probe=7f3311afd4) | Aug 17, 2022 |
| ASUSTek       | K45A                        | [cbbc0ff58a](https://linux-hardware.org/?probe=cbbc0ff58a) | Aug 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [8aea7a68ee](https://linux-hardware.org/?probe=8aea7a68ee) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f1d6bc684c](https://linux-hardware.org/?probe=f1d6bc684c) | Aug 17, 2022 |
| MSI           | Modern 14 B11SBL            | [ad56f2a352](https://linux-hardware.org/?probe=ad56f2a352) | Aug 17, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [f7102225ca](https://linux-hardware.org/?probe=f7102225ca) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [3a57a6329f](https://linux-hardware.org/?probe=3a57a6329f) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| Eluktronic... | MAX-17                      | [b0aec6f095](https://linux-hardware.org/?probe=b0aec6f095) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [3b35e8e9da](https://linux-hardware.org/?probe=3b35e8e9da) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [78ff8418f9](https://linux-hardware.org/?probe=78ff8418f9) | Aug 17, 2022 |
| MSI           | Delta 15 A5EFK              | [4b165c8f79](https://linux-hardware.org/?probe=4b165c8f79) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [0793e37f62](https://linux-hardware.org/?probe=0793e37f62) | Aug 17, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [1b12b01004](https://linux-hardware.org/?probe=1b12b01004) | Aug 16, 2022 |
| Acer          | Aspire A715-42G             | [fbeff3bff5](https://linux-hardware.org/?probe=fbeff3bff5) | Aug 16, 2022 |
| MSI           | GT72S 6QE                   | [20121e68c8](https://linux-hardware.org/?probe=20121e68c8) | Aug 16, 2022 |
| Acer          | Aspire E5-573               | [d3bd05f20b](https://linux-hardware.org/?probe=d3bd05f20b) | Aug 16, 2022 |
| HP            | Laptop 17-by0xxx            | [59db95ffee](https://linux-hardware.org/?probe=59db95ffee) | Aug 16, 2022 |
| Lenovo        | ThinkBook Plus 20TG         | [1f39fbc5a8](https://linux-hardware.org/?probe=1f39fbc5a8) | Aug 16, 2022 |
| Panasonic     | CFMX4-1                     | [01074aea14](https://linux-hardware.org/?probe=01074aea14) | Aug 16, 2022 |
| ASUSTek       | X453MA                      | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| HP            | Pavilion TS 15              | [22194522c7](https://linux-hardware.org/?probe=22194522c7) | Aug 15, 2022 |
| Acer          | Aspire A515-51G             | [9ee5f23f82](https://linux-hardware.org/?probe=9ee5f23f82) | Aug 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [d9f8a6ea69](https://linux-hardware.org/?probe=d9f8a6ea69) | Aug 15, 2022 |
| Apple         | MacBookPro10,1              | [c4738a316c](https://linux-hardware.org/?probe=c4738a316c) | Aug 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Notebook      | N15_17RD                    | [eef224fc6b](https://linux-hardware.org/?probe=eef224fc6b) | Aug 15, 2022 |
| Lenovo        | V110-15ISK 80TL             | [757de6f4df](https://linux-hardware.org/?probe=757de6f4df) | Aug 15, 2022 |
| Avell High... | A70 HYB                     | [c0e0f2d0a4](https://linux-hardware.org/?probe=c0e0f2d0a4) | Aug 15, 2022 |
| Sony          | VPCS131FM                   | [22e32938e6](https://linux-hardware.org/?probe=22e32938e6) | Aug 14, 2022 |
| Toshiba       | TECRA R940                  | [f7a6618519](https://linux-hardware.org/?probe=f7a6618519) | Aug 14, 2022 |
| Dell          | XPS 15 9500                 | [08ef9ef965](https://linux-hardware.org/?probe=08ef9ef965) | Aug 14, 2022 |
| Lenovo        | ThinkPad T430 2349V4B       | [0f919e20c7](https://linux-hardware.org/?probe=0f919e20c7) | Aug 14, 2022 |
| UNOWHY        | Y13G010S4EI                 | [b7352cd745](https://linux-hardware.org/?probe=b7352cd745) | Aug 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [7209cc1bd4](https://linux-hardware.org/?probe=7209cc1bd4) | Aug 14, 2022 |
| Dell          | XPS 15 9550                 | [ad3ad84c75](https://linux-hardware.org/?probe=ad3ad84c75) | Aug 14, 2022 |
| Apple         | MacBookPro5,5               | [76483c9f78](https://linux-hardware.org/?probe=76483c9f78) | Aug 14, 2022 |
| AXDIA Inte... | WINPAD V10                  | [a44a9b065b](https://linux-hardware.org/?probe=a44a9b065b) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a533aea5e5](https://linux-hardware.org/?probe=a533aea5e5) | Aug 14, 2022 |
| Dell          | Inspiron 13 5320            | [cee0d5a717](https://linux-hardware.org/?probe=cee0d5a717) | Aug 14, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [d5862f21f5](https://linux-hardware.org/?probe=d5862f21f5) | Aug 14, 2022 |
| Unknown       | Unknown                     | [dbf529a586](https://linux-hardware.org/?probe=dbf529a586) | Aug 14, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | [ca9974d27e](https://linux-hardware.org/?probe=ca9974d27e) | Aug 14, 2022 |
| Acer          | Aspire E5-521               | [c127df7597](https://linux-hardware.org/?probe=c127df7597) | Aug 13, 2022 |
| HP            | 14                          | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| Dell          | G3 3590                     | [fbe948e194](https://linux-hardware.org/?probe=fbe948e194) | Aug 13, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 15 9510                 | [3cb2744dbe](https://linux-hardware.org/?probe=3cb2744dbe) | Aug 12, 2022 |
| HP            | ProBook 6570b               | [d67ec558d4](https://linux-hardware.org/?probe=d67ec558d4) | Aug 12, 2022 |
| HP            | ProBook 440 G7              | [ee57cf772f](https://linux-hardware.org/?probe=ee57cf772f) | Aug 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [a7cdb45aa6](https://linux-hardware.org/?probe=a7cdb45aa6) | Aug 12, 2022 |
| MSI           | MS-16F1                     | [0a28da4f53](https://linux-hardware.org/?probe=0a28da4f53) | Aug 12, 2022 |
| HP            | Pavilion 17                 | [25a07691ec](https://linux-hardware.org/?probe=25a07691ec) | Aug 12, 2022 |
| Sony          | SVT15115CXS                 | [f7915ecf99](https://linux-hardware.org/?probe=f7915ecf99) | Aug 12, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [1604d7a824](https://linux-hardware.org/?probe=1604d7a824) | Aug 11, 2022 |
| Dell          | Latitude E6420              | [bd610e8bd8](https://linux-hardware.org/?probe=bd610e8bd8) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [26b1a32b84](https://linux-hardware.org/?probe=26b1a32b84) | Aug 11, 2022 |
| Acer          | Predator PH317-53           | [8578e9a77a](https://linux-hardware.org/?probe=8578e9a77a) | Aug 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [05042a439b](https://linux-hardware.org/?probe=05042a439b) | Aug 11, 2022 |
| AZW           | SEi                         | [fb26f11a19](https://linux-hardware.org/?probe=fb26f11a19) | Aug 11, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [15488377fb](https://linux-hardware.org/?probe=15488377fb) | Aug 10, 2022 |
| Dell          | XPS 13 7390                 | [149d92cd3e](https://linux-hardware.org/?probe=149d92cd3e) | Aug 10, 2022 |
| HP            | EliteBook 8460p             | [fe464db60d](https://linux-hardware.org/?probe=fe464db60d) | Aug 10, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [4c3d230572](https://linux-hardware.org/?probe=4c3d230572) | Aug 10, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [5484873fd7](https://linux-hardware.org/?probe=5484873fd7) | Aug 10, 2022 |
| Lenovo        | Z40-70 20366                | [2378dda760](https://linux-hardware.org/?probe=2378dda760) | Aug 10, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [21044cebb3](https://linux-hardware.org/?probe=21044cebb3) | Aug 10, 2022 |
| HUAWEI        | MACH-WX9                    | [18f9226bc0](https://linux-hardware.org/?probe=18f9226bc0) | Aug 09, 2022 |
| Timi          | TM1701                      | [676fc52004](https://linux-hardware.org/?probe=676fc52004) | Aug 09, 2022 |
| MSI           | Prestige 15 A10SC           | [9471547f71](https://linux-hardware.org/?probe=9471547f71) | Aug 09, 2022 |
| HUAWEI        | CREM-WXX9                   | [1a95dd7974](https://linux-hardware.org/?probe=1a95dd7974) | Aug 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1c9cd79646](https://linux-hardware.org/?probe=1c9cd79646) | Aug 09, 2022 |
| ASUSTek       | UX430UAR                    | [e11856fcbc](https://linux-hardware.org/?probe=e11856fcbc) | Aug 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [dee5c21fb7](https://linux-hardware.org/?probe=dee5c21fb7) | Aug 09, 2022 |
| Dell          | Precision 5510              | [02dd64eff3](https://linux-hardware.org/?probe=02dd64eff3) | Aug 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [9855f862c2](https://linux-hardware.org/?probe=9855f862c2) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e0403fe18f](https://linux-hardware.org/?probe=e0403fe18f) | Aug 08, 2022 |
| Lenovo        | ThinkPad X270 20HMS2R900    | [30a447f95c](https://linux-hardware.org/?probe=30a447f95c) | Aug 07, 2022 |
| HP            | Laptop 15-da0xxx            | [0e35955798](https://linux-hardware.org/?probe=0e35955798) | Aug 07, 2022 |
| Alienware     | x17 R2                      | [4e7fe87198](https://linux-hardware.org/?probe=4e7fe87198) | Aug 07, 2022 |
| Acer          | Aspire 7741                 | [bc1daa0005](https://linux-hardware.org/?probe=bc1daa0005) | Aug 07, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [9d837de022](https://linux-hardware.org/?probe=9d837de022) | Aug 07, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [438f5cce2a](https://linux-hardware.org/?probe=438f5cce2a) | Aug 07, 2022 |
| Toshiba       | Satellite Pro L300D         | [b3ed30ac52](https://linux-hardware.org/?probe=b3ed30ac52) | Aug 07, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [699bd44c36](https://linux-hardware.org/?probe=699bd44c36) | Aug 07, 2022 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [572cb48d3c](https://linux-hardware.org/?probe=572cb48d3c) | Aug 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7dc1825a38](https://linux-hardware.org/?probe=7dc1825a38) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0a6068ab6b](https://linux-hardware.org/?probe=0a6068ab6b) | Aug 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8f7a78b973](https://linux-hardware.org/?probe=8f7a78b973) | Aug 06, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [2eb53b5701](https://linux-hardware.org/?probe=2eb53b5701) | Aug 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [157da4bcd2](https://linux-hardware.org/?probe=157da4bcd2) | Aug 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d975e76a17](https://linux-hardware.org/?probe=d975e76a17) | Aug 05, 2022 |
| HP            | Laptop 15-da0xxx            | [75c4deee10](https://linux-hardware.org/?probe=75c4deee10) | Aug 05, 2022 |
| HP            | Laptop 17-by4xxx            | [7867c6d24c](https://linux-hardware.org/?probe=7867c6d24c) | Aug 05, 2022 |
| Acer          | Aspire 7741                 | [eae703cf6f](https://linux-hardware.org/?probe=eae703cf6f) | Aug 05, 2022 |
| Acer          | Aspire A515-51              | [6c5e2de730](https://linux-hardware.org/?probe=6c5e2de730) | Aug 05, 2022 |
| HP            | ZBook 15 G3                 | [d59939b336](https://linux-hardware.org/?probe=d59939b336) | Aug 05, 2022 |
| Acer          | Aspire V3-572               | [dadff5cef8](https://linux-hardware.org/?probe=dadff5cef8) | Aug 05, 2022 |
| Gateway       | NE56R                       | [44de22f108](https://linux-hardware.org/?probe=44de22f108) | Aug 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | [ec2efe1636](https://linux-hardware.org/?probe=ec2efe1636) | Aug 04, 2022 |
| MSI           | Modern 14 A10M              | [f8a0b1d6e6](https://linux-hardware.org/?probe=f8a0b1d6e6) | Aug 04, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [fcef4276cb](https://linux-hardware.org/?probe=fcef4276cb) | Aug 03, 2022 |
| Gateway       | NV55C                       | [cc3c8d23e4](https://linux-hardware.org/?probe=cc3c8d23e4) | Aug 03, 2022 |
| HP            | Snappy                      | [0a73175862](https://linux-hardware.org/?probe=0a73175862) | Aug 03, 2022 |
| HP            | Laptop 17-by4xxx            | [711cf515aa](https://linux-hardware.org/?probe=711cf515aa) | Aug 03, 2022 |
| ASUSTek       | GL552VW                     | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Dell          | Inspiron 3521               | [b947e19278](https://linux-hardware.org/?probe=b947e19278) | Aug 02, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [1b11fecca3](https://linux-hardware.org/?probe=1b11fecca3) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 4290KJ6       | [ef5ee2a01e](https://linux-hardware.org/?probe=ef5ee2a01e) | Aug 02, 2022 |
| HP            | Laptop 17-cp0xxx            | [492d014205](https://linux-hardware.org/?probe=492d014205) | Aug 02, 2022 |
| Dell          | Inspiron 5580               | [49d857e7bf](https://linux-hardware.org/?probe=49d857e7bf) | Aug 02, 2022 |
| Notebook      | NS50_70MU                   | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | [b4d00ecb36](https://linux-hardware.org/?probe=b4d00ecb36) | Aug 02, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | [6a1b44dfe0](https://linux-hardware.org/?probe=6a1b44dfe0) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | ProBook 4540s               | [c96c493e64](https://linux-hardware.org/?probe=c96c493e64) | Aug 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [2abfab93cb](https://linux-hardware.org/?probe=2abfab93cb) | Aug 02, 2022 |
| ASUSTek       | X750JN                      | [b321cd29a8](https://linux-hardware.org/?probe=b321cd29a8) | Aug 02, 2022 |
| Dell          | Precision 5530              | [a5177f0edb](https://linux-hardware.org/?probe=a5177f0edb) | Aug 02, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [16a3f81537](https://linux-hardware.org/?probe=16a3f81537) | Aug 01, 2022 |
| Dell          | Latitude D620               | [f378606941](https://linux-hardware.org/?probe=f378606941) | Aug 01, 2022 |
| HONOR         | NBR-WAX9                    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [c79c2bd215](https://linux-hardware.org/?probe=c79c2bd215) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [4b9354d287](https://linux-hardware.org/?probe=4b9354d287) | Jul 31, 2022 |
| HP            | Pavilion g6                 | [5867423d27](https://linux-hardware.org/?probe=5867423d27) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [b8daa2d973](https://linux-hardware.org/?probe=b8daa2d973) | Jul 30, 2022 |
| HP            | EliteBook 8570w             | [1876d4e53d](https://linux-hardware.org/?probe=1876d4e53d) | Jul 30, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0359549c36](https://linux-hardware.org/?probe=0359549c36) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire A715-41G             | [3881e3998f](https://linux-hardware.org/?probe=3881e3998f) | Jul 30, 2022 |
| Acer          | Nitro AN515-55              | [b279b1558f](https://linux-hardware.org/?probe=b279b1558f) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [320bc76144](https://linux-hardware.org/?probe=320bc76144) | Jul 30, 2022 |
| Dell          | Latitude E6520              | [0a7e1cdcaf](https://linux-hardware.org/?probe=0a7e1cdcaf) | Jul 30, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [e5e5cc4bbc](https://linux-hardware.org/?probe=e5e5cc4bbc) | Jul 29, 2022 |
| HP            | Victus by Gaming Laptop ... | [8d729c2a6b](https://linux-hardware.org/?probe=8d729c2a6b) | Jul 29, 2022 |
| Lenovo        | Yoga S740-14IIL 81RM        | [a308d89f1f](https://linux-hardware.org/?probe=a308d89f1f) | Jul 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [486ef751f0](https://linux-hardware.org/?probe=486ef751f0) | Jul 29, 2022 |
| Dell          | XPS 15 9560                 | [40ba0a0b07](https://linux-hardware.org/?probe=40ba0a0b07) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [3986399fe4](https://linux-hardware.org/?probe=3986399fe4) | Jul 29, 2022 |
| Lenovo        | ThinkPad X240 20AMS28505    | [f159c45adf](https://linux-hardware.org/?probe=f159c45adf) | Jul 29, 2022 |
| Dell          | Inspiron 7460               | [9f3420ac40](https://linux-hardware.org/?probe=9f3420ac40) | Jul 29, 2022 |
| HUAWEI        | WRT-WX9                     | [ed09406e6c](https://linux-hardware.org/?probe=ed09406e6c) | Jul 28, 2022 |
| HP            | EliteBook 820 G3            | [a96c616d62](https://linux-hardware.org/?probe=a96c616d62) | Jul 28, 2022 |
| HP            | 348 G4                      | [034e49f6dc](https://linux-hardware.org/?probe=034e49f6dc) | Jul 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [238fa8aa34](https://linux-hardware.org/?probe=238fa8aa34) | Jul 28, 2022 |
| Acer          | Aspire A515-45              | [47dee227ba](https://linux-hardware.org/?probe=47dee227ba) | Jul 28, 2022 |
| ASUSTek       | X750JN                      | [58fe3e4ae8](https://linux-hardware.org/?probe=58fe3e4ae8) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [1bc8715e4e](https://linux-hardware.org/?probe=1bc8715e4e) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c68abe4e1a](https://linux-hardware.org/?probe=c68abe4e1a) | Jul 27, 2022 |
| Clevo         | M570TU                      | [b1f3c16be7](https://linux-hardware.org/?probe=b1f3c16be7) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e3fff7dcf4](https://linux-hardware.org/?probe=e3fff7dcf4) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [c1ab099582](https://linux-hardware.org/?probe=c1ab099582) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f7d226a34a](https://linux-hardware.org/?probe=f7d226a34a) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [b690b57222](https://linux-hardware.org/?probe=b690b57222) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [af6e67c798](https://linux-hardware.org/?probe=af6e67c798) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| ASUSTek       | X750JN                      | [a4f3fc8ddd](https://linux-hardware.org/?probe=a4f3fc8ddd) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [c2fc2235eb](https://linux-hardware.org/?probe=c2fc2235eb) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [f18835e5a1](https://linux-hardware.org/?probe=f18835e5a1) | Jul 27, 2022 |
| HP            | Notebook                    | [f85df4e2d5](https://linux-hardware.org/?probe=f85df4e2d5) | Jul 26, 2022 |
| Dell          | Latitude E6520              | [b7436c1d3d](https://linux-hardware.org/?probe=b7436c1d3d) | Jul 26, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [0c145b1409](https://linux-hardware.org/?probe=0c145b1409) | Jul 25, 2022 |
| Dell          | Latitude 7320               | [83301910d0](https://linux-hardware.org/?probe=83301910d0) | Jul 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [52d58f31bb](https://linux-hardware.org/?probe=52d58f31bb) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| ASUSTek       | K55VJ                       | [7c0ae7deec](https://linux-hardware.org/?probe=7c0ae7deec) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2db0d89beb](https://linux-hardware.org/?probe=2db0d89beb) | Jul 25, 2022 |
| Aquarius      | Cmp NS765                   | [9c9200701e](https://linux-hardware.org/?probe=9c9200701e) | Jul 24, 2022 |
| Dell          | Latitude E5420              | [b298e3bffa](https://linux-hardware.org/?probe=b298e3bffa) | Jul 24, 2022 |
| HP            | Notebook                    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| Dell          | Latitude E6520              | [b5d9fa066a](https://linux-hardware.org/?probe=b5d9fa066a) | Jul 24, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [60dd75eca9](https://linux-hardware.org/?probe=60dd75eca9) | Jul 24, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [3721b1c82a](https://linux-hardware.org/?probe=3721b1c82a) | Jul 24, 2022 |
| Apple         | MacBookPro9,2               | [99ee81b243](https://linux-hardware.org/?probe=99ee81b243) | Jul 23, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [b16e17a798](https://linux-hardware.org/?probe=b16e17a798) | Jul 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [ce6a0d666e](https://linux-hardware.org/?probe=ce6a0d666e) | Jul 23, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [1c50bea602](https://linux-hardware.org/?probe=1c50bea602) | Jul 23, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e06aafac8c](https://linux-hardware.org/?probe=e06aafac8c) | Jul 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [1077085bf6](https://linux-hardware.org/?probe=1077085bf6) | Jul 23, 2022 |
| Lenovo        | 81FV                        | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| Dell          | Latitude E7440              | [d5ca3d7f7e](https://linux-hardware.org/?probe=d5ca3d7f7e) | Jul 22, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [090cc78b83](https://linux-hardware.org/?probe=090cc78b83) | Jul 22, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [fa8f2adca9](https://linux-hardware.org/?probe=fa8f2adca9) | Jul 22, 2022 |
| ASUSTek       | X750JN                      | [6bf181ed49](https://linux-hardware.org/?probe=6bf181ed49) | Jul 22, 2022 |
| Samsung       | 550XBE/350XBE               | [b23cfb57cf](https://linux-hardware.org/?probe=b23cfb57cf) | Jul 21, 2022 |
| HP            | 240 G4                      | [449fb8b8f8](https://linux-hardware.org/?probe=449fb8b8f8) | Jul 21, 2022 |
| Dell          | XPS 15 9520                 | [51ddccaf88](https://linux-hardware.org/?probe=51ddccaf88) | Jul 21, 2022 |
| ASUSTek       | X541NA                      | [51aefa0464](https://linux-hardware.org/?probe=51aefa0464) | Jul 21, 2022 |
| Lenovo        | ThinkPad T580 20LAS27000    | [a78a8e806f](https://linux-hardware.org/?probe=a78a8e806f) | Jul 21, 2022 |
| HP            | Laptop 17-by0xxx            | [afa7d8ba6c](https://linux-hardware.org/?probe=afa7d8ba6c) | Jul 21, 2022 |
| ASUSTek       | X541UVK                     | [a34ee52169](https://linux-hardware.org/?probe=a34ee52169) | Jul 21, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c1204438f8](https://linux-hardware.org/?probe=c1204438f8) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [ea200c839f](https://linux-hardware.org/?probe=ea200c839f) | Jul 20, 2022 |
| HP            | EliteBook 850 G5            | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [4cde663cf9](https://linux-hardware.org/?probe=4cde663cf9) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [effe49f996](https://linux-hardware.org/?probe=effe49f996) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [8d18b6813f](https://linux-hardware.org/?probe=8d18b6813f) | Jul 20, 2022 |
| Dell          | G3 3590                     | [920eed9524](https://linux-hardware.org/?probe=920eed9524) | Jul 19, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [56e3efd7bc](https://linux-hardware.org/?probe=56e3efd7bc) | Jul 19, 2022 |
| HP            | Notebook                    | [79c0f60f74](https://linux-hardware.org/?probe=79c0f60f74) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |
| HP            | EliteBook 8570w             | [6b8bf59f68](https://linux-hardware.org/?probe=6b8bf59f68) | Jul 19, 2022 |
| Lenovo        | IdeaPad U430 Touch 20270    | [2c43b01e55](https://linux-hardware.org/?probe=2c43b01e55) | Jul 18, 2022 |
| Dell          | Latitude E6230              | [a66cad27e9](https://linux-hardware.org/?probe=a66cad27e9) | Jul 18, 2022 |
| Dell          | Latitude E7470              | [709a460528](https://linux-hardware.org/?probe=709a460528) | Jul 18, 2022 |
| MSI           | MS-14Y1                     | [782beac866](https://linux-hardware.org/?probe=782beac866) | Jul 18, 2022 |
| Google        | Kohaku                      | [2f21de3ff6](https://linux-hardware.org/?probe=2f21de3ff6) | Jul 18, 2022 |
| Pegatron      | D15K                        | [7f8fa03161](https://linux-hardware.org/?probe=7f8fa03161) | Jul 17, 2022 |
| Framework     | Laptop                      | [84d20eb09a](https://linux-hardware.org/?probe=84d20eb09a) | Jul 17, 2022 |
| Framework     | Laptop                      | [0489cc39db](https://linux-hardware.org/?probe=0489cc39db) | Jul 17, 2022 |
| Dell          | Inspiron 5515               | [502c19838a](https://linux-hardware.org/?probe=502c19838a) | Jul 17, 2022 |
| Unknown       | Unknown                     | [251f348fe5](https://linux-hardware.org/?probe=251f348fe5) | Jul 17, 2022 |
| Dell          | Latitude E5440              | [c8e68471c1](https://linux-hardware.org/?probe=c8e68471c1) | Jul 16, 2022 |
| Acer          | Aspire A315-23              | [5f1ff52baa](https://linux-hardware.org/?probe=5f1ff52baa) | Jul 16, 2022 |
| HP            | 250 G5                      | [979d1aea6f](https://linux-hardware.org/?probe=979d1aea6f) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [40d837716b](https://linux-hardware.org/?probe=40d837716b) | Jul 16, 2022 |
| Alienware     | x17 R1                      | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| System76      | Bonobo Extreme              | [6c7f545300](https://linux-hardware.org/?probe=6c7f545300) | Jul 16, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [18d1378620](https://linux-hardware.org/?probe=18d1378620) | Jul 16, 2022 |
| Dell          | XPS 13 7390                 | [eff723b9f2](https://linux-hardware.org/?probe=eff723b9f2) | Jul 16, 2022 |
| Toshiba       | Satellite L505D             | [1d7b1ed7c8](https://linux-hardware.org/?probe=1d7b1ed7c8) | Jul 15, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [42de47cdc1](https://linux-hardware.org/?probe=42de47cdc1) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | [dd43fd4b04](https://linux-hardware.org/?probe=dd43fd4b04) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | [9ca58ddce1](https://linux-hardware.org/?probe=9ca58ddce1) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [329ce2f7f8](https://linux-hardware.org/?probe=329ce2f7f8) | Jul 15, 2022 |
| Dell          | G3 3590                     | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7812a0737e](https://linux-hardware.org/?probe=7812a0737e) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea97effc52](https://linux-hardware.org/?probe=ea97effc52) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Lenovo        | G400s VILG1                 | [fbaf6e2d8f](https://linux-hardware.org/?probe=fbaf6e2d8f) | Jul 13, 2022 |
| Lenovo        | G400s VILG1                 | [33853365fd](https://linux-hardware.org/?probe=33853365fd) | Jul 13, 2022 |
| Gigabyte      | AERO 17 KC                  | [b6398b12e2](https://linux-hardware.org/?probe=b6398b12e2) | Jul 13, 2022 |
| Lenovo        | ThinkPad P50 20EQA05JCL     | [43f5b3c05d](https://linux-hardware.org/?probe=43f5b3c05d) | Jul 13, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [f91143bc89](https://linux-hardware.org/?probe=f91143bc89) | Jul 13, 2022 |
| GPD           | G1621-02                    | [25da86e752](https://linux-hardware.org/?probe=25da86e752) | Jul 13, 2022 |
| Sony          | SVF1531V8CW                 | [bebf2fb162](https://linux-hardware.org/?probe=bebf2fb162) | Jul 13, 2022 |
| Dell          | Inspiron 5559               | [a687046e06](https://linux-hardware.org/?probe=a687046e06) | Jul 13, 2022 |
| Dell          | Inspiron 5559               | [c4b25937a7](https://linux-hardware.org/?probe=c4b25937a7) | Jul 13, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [de328d9562](https://linux-hardware.org/?probe=de328d9562) | Jul 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [f422c77bb1](https://linux-hardware.org/?probe=f422c77bb1) | Jul 12, 2022 |
| Lenovo        | ThinkPad T490s 20NYS0LY0... | [882680a962](https://linux-hardware.org/?probe=882680a962) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| HP            | Sona                        | [504fddb8e9](https://linux-hardware.org/?probe=504fddb8e9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [ea08980c33](https://linux-hardware.org/?probe=ea08980c33) | Jul 11, 2022 |
| VALE          | Notebook Classic C140       | [d6cc520dbe](https://linux-hardware.org/?probe=d6cc520dbe) | Jul 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [6b29072d9e](https://linux-hardware.org/?probe=6b29072d9e) | Jul 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ce42b6cb75](https://linux-hardware.org/?probe=ce42b6cb75) | Jul 11, 2022 |
| HP            | ProBook 6570b               | [5796920cf8](https://linux-hardware.org/?probe=5796920cf8) | Jul 11, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [c1ed74053e](https://linux-hardware.org/?probe=c1ed74053e) | Jul 11, 2022 |
| Framework     | Laptop                      | [a13ef2beee](https://linux-hardware.org/?probe=a13ef2beee) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [a379e2a103](https://linux-hardware.org/?probe=a379e2a103) | Jul 11, 2022 |
| Panasonic     | FZG1-3                      | [753cc1d311](https://linux-hardware.org/?probe=753cc1d311) | Jul 10, 2022 |
| Panasonic     | FZG1-3                      | [01d4651376](https://linux-hardware.org/?probe=01d4651376) | Jul 10, 2022 |
| MSI           | GL75 Leopard 10SEK          | [532348a02c](https://linux-hardware.org/?probe=532348a02c) | Jul 10, 2022 |
| Dell          | Inspiron 3558               | [14cacca8ad](https://linux-hardware.org/?probe=14cacca8ad) | Jul 09, 2022 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [269ebd1a4d](https://linux-hardware.org/?probe=269ebd1a4d) | Jul 09, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [8270068517](https://linux-hardware.org/?probe=8270068517) | Jul 09, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [36151ae5c3](https://linux-hardware.org/?probe=36151ae5c3) | Jul 09, 2022 |
| MSI           | Bravo 17 A4DDK              | [9f9d1cac61](https://linux-hardware.org/?probe=9f9d1cac61) | Jul 09, 2022 |
| Dell          | Vostro 3590                 | [7195de93ae](https://linux-hardware.org/?probe=7195de93ae) | Jul 09, 2022 |
| HP            | Laptop 17z-cp000            | [f6f0740c36](https://linux-hardware.org/?probe=f6f0740c36) | Jul 09, 2022 |
| HP            | ProBook 6570b               | [b90b75215d](https://linux-hardware.org/?probe=b90b75215d) | Jul 09, 2022 |
| Acer          | Predator PH315-53           | [b6c6516360](https://linux-hardware.org/?probe=b6c6516360) | Jul 09, 2022 |
| Dell          | Latitude 3400               | [6a36fb9dd9](https://linux-hardware.org/?probe=6a36fb9dd9) | Jul 09, 2022 |
| HP            | EliteBook 8470p             | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| MSI           | GF63 Thin 8RCS              | [886728c1b6](https://linux-hardware.org/?probe=886728c1b6) | Jul 08, 2022 |
| Lenovo        | V14-ADA 82C6                | [e72ccdd0c6](https://linux-hardware.org/?probe=e72ccdd0c6) | Jul 08, 2022 |
| ASUSTek       | X550CC                      | [a57dba854b](https://linux-hardware.org/?probe=a57dba854b) | Jul 08, 2022 |
| Notebook      | NH55RGQ                     | [37de891a60](https://linux-hardware.org/?probe=37de891a60) | Jul 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | Pavilion g6                 | [30085f92b1](https://linux-hardware.org/?probe=30085f92b1) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [a64c483143](https://linux-hardware.org/?probe=a64c483143) | Jul 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [84f475721b](https://linux-hardware.org/?probe=84f475721b) | Jul 08, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [e850b43a12](https://linux-hardware.org/?probe=e850b43a12) | Jul 07, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [39e56d90b1](https://linux-hardware.org/?probe=39e56d90b1) | Jul 07, 2022 |
| Acer          | Nitro AN515-55              | [85845c3282](https://linux-hardware.org/?probe=85845c3282) | Jul 07, 2022 |
| ASUSTek       | X555DG                      | [b7a2c97bf2](https://linux-hardware.org/?probe=b7a2c97bf2) | Jul 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e1f5b40789](https://linux-hardware.org/?probe=e1f5b40789) | Jul 07, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [106199561c](https://linux-hardware.org/?probe=106199561c) | Jul 07, 2022 |
| Dell          | XPS 17 9710                 | [81b2d3fa4f](https://linux-hardware.org/?probe=81b2d3fa4f) | Jul 06, 2022 |
| Toshiba       | Satellite L505D             | [cf5fedc6e5](https://linux-hardware.org/?probe=cf5fedc6e5) | Jul 06, 2022 |
| HP            | ProBook 450 G2              | [aeb16eb1eb](https://linux-hardware.org/?probe=aeb16eb1eb) | Jul 06, 2022 |
| Lenovo        | ThinkPad L380 20M5000FUS    | [9c6ab1a171](https://linux-hardware.org/?probe=9c6ab1a171) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c75201835c](https://linux-hardware.org/?probe=c75201835c) | Jul 06, 2022 |
| Dell          | Inspiron 16 5625            | [dcbe63005c](https://linux-hardware.org/?probe=dcbe63005c) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c8b9e41a50](https://linux-hardware.org/?probe=c8b9e41a50) | Jul 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [454fed051a](https://linux-hardware.org/?probe=454fed051a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5afb466a35](https://linux-hardware.org/?probe=5afb466a35) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [162080ffcf](https://linux-hardware.org/?probe=162080ffcf) | Jul 06, 2022 |
| Acer          | Aspire V3-572               | [8dbec85d36](https://linux-hardware.org/?probe=8dbec85d36) | Jul 06, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | [a3c85d395b](https://linux-hardware.org/?probe=a3c85d395b) | Jul 05, 2022 |
| System76      | Oryx Pro                    | [338a8ed5ab](https://linux-hardware.org/?probe=338a8ed5ab) | Jul 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [4009adaca2](https://linux-hardware.org/?probe=4009adaca2) | Jul 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [4826df34b3](https://linux-hardware.org/?probe=4826df34b3) | Jul 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4d4cd5bae0](https://linux-hardware.org/?probe=4d4cd5bae0) | Jul 05, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [2cbcdfe2db](https://linux-hardware.org/?probe=2cbcdfe2db) | Jul 05, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [7f64f81a29](https://linux-hardware.org/?probe=7f64f81a29) | Jul 04, 2022 |
| HP            | ProBook 645 G3              | [5c37a32531](https://linux-hardware.org/?probe=5c37a32531) | Jul 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [7bb2a0b59a](https://linux-hardware.org/?probe=7bb2a0b59a) | Jul 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | [59a1c1c8b1](https://linux-hardware.org/?probe=59a1c1c8b1) | Jul 04, 2022 |
| Chuwi         | GemiBook                    | [881c250e4f](https://linux-hardware.org/?probe=881c250e4f) | Jul 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [9e9a46d8ec](https://linux-hardware.org/?probe=9e9a46d8ec) | Jul 04, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [2ed808bbcc](https://linux-hardware.org/?probe=2ed808bbcc) | Jul 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [5a6c158296](https://linux-hardware.org/?probe=5a6c158296) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | [4cebce6bab](https://linux-hardware.org/?probe=4cebce6bab) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | [6ee62813e8](https://linux-hardware.org/?probe=6ee62813e8) | Jul 04, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Notebook                    | [b9eb2e4cdd](https://linux-hardware.org/?probe=b9eb2e4cdd) | Jul 04, 2022 |
| HP            | 255 G8 Notebook PC          | [af74b651d5](https://linux-hardware.org/?probe=af74b651d5) | Jul 04, 2022 |
| HP            | EliteBook 8470p             | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [d0e94cff94](https://linux-hardware.org/?probe=d0e94cff94) | Jul 03, 2022 |
| HP            | EliteBook 840 G1            | [9705c40e85](https://linux-hardware.org/?probe=9705c40e85) | Jul 03, 2022 |
| Apple         | MacBookPro5,1               | [ac53d2f956](https://linux-hardware.org/?probe=ac53d2f956) | Jul 02, 2022 |
| Dell          | XPS 13 9350                 | [0c8bcdbcb1](https://linux-hardware.org/?probe=0c8bcdbcb1) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480s 20L7004NM... | [716bd7e41f](https://linux-hardware.org/?probe=716bd7e41f) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | [576f59ec1b](https://linux-hardware.org/?probe=576f59ec1b) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | [1b45ef7d10](https://linux-hardware.org/?probe=1b45ef7d10) | Jul 01, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [16413aeb23](https://linux-hardware.org/?probe=16413aeb23) | Jul 01, 2022 |
| HP            | Laptop 14s-cf2xxx           | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Dell          | Inspiron M5010              | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2671f4ffe2](https://linux-hardware.org/?probe=2671f4ffe2) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c9d0d64896](https://linux-hardware.org/?probe=c9d0d64896) | Jul 01, 2022 |
| Framework     | Laptop                      | [1089f37daf](https://linux-hardware.org/?probe=1089f37daf) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3af286a188](https://linux-hardware.org/?probe=3af286a188) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| Acer          | Aspire A315-55G             | [e6d7a2a642](https://linux-hardware.org/?probe=e6d7a2a642) | Jun 30, 2022 |
| HP            | Laptop 15-da0xxx            | [9c512247ff](https://linux-hardware.org/?probe=9c512247ff) | Jun 30, 2022 |
| Lenovo        | ThinkPad T410 2518A37       | [4e15b37546](https://linux-hardware.org/?probe=4e15b37546) | Jun 30, 2022 |
| Dell          | Inspiron 3543               | [1f9d3b4a6c](https://linux-hardware.org/?probe=1f9d3b4a6c) | Jun 29, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| ASUSTek       | UX302LA                     | [6092e85ae8](https://linux-hardware.org/?probe=6092e85ae8) | Jun 29, 2022 |
| Getac         | B300-X                      | [eb752b6c15](https://linux-hardware.org/?probe=eb752b6c15) | Jun 29, 2022 |
| HUAWEI        | BOD-WXX9                    | [9c3e14320e](https://linux-hardware.org/?probe=9c3e14320e) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [43c87260b2](https://linux-hardware.org/?probe=43c87260b2) | Jun 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [7406ba0eb2](https://linux-hardware.org/?probe=7406ba0eb2) | Jun 29, 2022 |
| Alienware     | 17                          | [715b5b0dce](https://linux-hardware.org/?probe=715b5b0dce) | Jun 29, 2022 |
| Apple         | MacBookAir6,1               | [c3172fd9cf](https://linux-hardware.org/?probe=c3172fd9cf) | Jun 28, 2022 |
| Dell          | Precision M6800             | [027cb621ef](https://linux-hardware.org/?probe=027cb621ef) | Jun 28, 2022 |
| Dell          | Latitude 5511               | [c361c37273](https://linux-hardware.org/?probe=c361c37273) | Jun 28, 2022 |
| ASUSTek       | X750JN                      | [4ba4d14a1a](https://linux-hardware.org/?probe=4ba4d14a1a) | Jun 28, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d240efa39f](https://linux-hardware.org/?probe=d240efa39f) | Jun 28, 2022 |
| Apple         | MacBookPro12,1              | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Toshiba       | Satellite C855-12R          | [e94a109546](https://linux-hardware.org/?probe=e94a109546) | Jun 28, 2022 |
| Dell          | Inspiron N5110              | [239e8c86c0](https://linux-hardware.org/?probe=239e8c86c0) | Jun 28, 2022 |
| Dell          | Latitude E6520              | [f688527838](https://linux-hardware.org/?probe=f688527838) | Jun 27, 2022 |
| Gigabyte      | RC14UD                      | [d2b55252d8](https://linux-hardware.org/?probe=d2b55252d8) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| Apple         | MacBookPro5,1               | [1e14793557](https://linux-hardware.org/?probe=1e14793557) | Jun 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3a651b23fb](https://linux-hardware.org/?probe=3a651b23fb) | Jun 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [de3ca4e422](https://linux-hardware.org/?probe=de3ca4e422) | Jun 26, 2022 |
| Acer          | Swift SF114-32              | [25e6653354](https://linux-hardware.org/?probe=25e6653354) | Jun 26, 2022 |
| MSI           | GF63 Thin 9SCXR             | [db6195eed2](https://linux-hardware.org/?probe=db6195eed2) | Jun 26, 2022 |
| Timi          | A35S                        | [606e376264](https://linux-hardware.org/?probe=606e376264) | Jun 26, 2022 |
| Dell          | Latitude 7300               | [a7939aeb9e](https://linux-hardware.org/?probe=a7939aeb9e) | Jun 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [400eaba39f](https://linux-hardware.org/?probe=400eaba39f) | Jun 26, 2022 |
| HP            | Compaq CQ58                 | [5948b56a82](https://linux-hardware.org/?probe=5948b56a82) | Jun 25, 2022 |
| Dell          | XPS 13 9310                 | [fa3d29c80b](https://linux-hardware.org/?probe=fa3d29c80b) | Jun 25, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [81a9b9847d](https://linux-hardware.org/?probe=81a9b9847d) | Jun 25, 2022 |
| Dell          | Inspiron 5437               | [e206b319a2](https://linux-hardware.org/?probe=e206b319a2) | Jun 25, 2022 |
| Gigabyte      | G5 KC                       | [5ef620811f](https://linux-hardware.org/?probe=5ef620811f) | Jun 25, 2022 |
| HP            | Pavilion g6                 | [d2e82f01d9](https://linux-hardware.org/?probe=d2e82f01d9) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| HP            | OMEN Notebook PC 15         | [66f845b63e](https://linux-hardware.org/?probe=66f845b63e) | Jun 25, 2022 |
| Unknown       | Unknown                     | [6e62883390](https://linux-hardware.org/?probe=6e62883390) | Jun 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [3b78b34416](https://linux-hardware.org/?probe=3b78b34416) | Jun 24, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [58ab145788](https://linux-hardware.org/?probe=58ab145788) | Jun 24, 2022 |
| HP            | Laptop 15-ef2xxx            | [3e16709617](https://linux-hardware.org/?probe=3e16709617) | Jun 24, 2022 |
| Packard Be... | EasyNote TE69HW             | [d292d79bbe](https://linux-hardware.org/?probe=d292d79bbe) | Jun 24, 2022 |
| Lenovo        | ThinkPad T520 4243VE1       | [7fcfec26eb](https://linux-hardware.org/?probe=7fcfec26eb) | Jun 24, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [2c0b9c6402](https://linux-hardware.org/?probe=2c0b9c6402) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [bb8541d805](https://linux-hardware.org/?probe=bb8541d805) | Jun 24, 2022 |
| Acer          | Nitro AN515-54              | [afce38a95a](https://linux-hardware.org/?probe=afce38a95a) | Jun 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Dell          | Precision 5550              | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [ac634d8aa9](https://linux-hardware.org/?probe=ac634d8aa9) | Jun 23, 2022 |
| Dell          | Precision 5550              | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [926d4055f7](https://linux-hardware.org/?probe=926d4055f7) | Jun 23, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [223e43004a](https://linux-hardware.org/?probe=223e43004a) | Jun 23, 2022 |
| HP            | 250 G7 Notebook PC          | [6ec1b55ac0](https://linux-hardware.org/?probe=6ec1b55ac0) | Jun 23, 2022 |
| Lenovo        | G510 20238                  | [1b382e0eb0](https://linux-hardware.org/?probe=1b382e0eb0) | Jun 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [5dd91493a8](https://linux-hardware.org/?probe=5dd91493a8) | Jun 23, 2022 |
| ASUSTek       | K46CB                       | [65344cb089](https://linux-hardware.org/?probe=65344cb089) | Jun 23, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [f002062377](https://linux-hardware.org/?probe=f002062377) | Jun 22, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [1967dad271](https://linux-hardware.org/?probe=1967dad271) | Jun 22, 2022 |
| Positivo      | VJF155F11UAR                | [77c5ca4f1e](https://linux-hardware.org/?probe=77c5ca4f1e) | Jun 22, 2022 |
| Acer          | NC-E5-774G-75TJ             | [55fce68116](https://linux-hardware.org/?probe=55fce68116) | Jun 22, 2022 |
| HP            | ZBook 17 G4                 | [bf03eb0fa7](https://linux-hardware.org/?probe=bf03eb0fa7) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [dda5fb9c20](https://linux-hardware.org/?probe=dda5fb9c20) | Jun 21, 2022 |
| HUAWEI        | MACH-WX9                    | [c6f721f315](https://linux-hardware.org/?probe=c6f721f315) | Jun 21, 2022 |
| HP            | EliteBook 830 G6            | [7c7d9af667](https://linux-hardware.org/?probe=7c7d9af667) | Jun 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_36/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.17.5-300.fc36.x86_64       | 94        | 7.9%    |
| 5.18.13-200.fc36.x86_64      | 61        | 5.13%   |
| 5.18.11-200.fc36.x86_64      | 50        | 4.2%    |
| 5.17.11-300.fc36.x86_64      | 46        | 3.87%   |
| 5.18.16-200.fc36.x86_64      | 45        | 3.78%   |
| 5.19.16-200.fc36.x86_64      | 44        | 3.7%    |
| 5.17.6-300.fc36.x86_64       | 43        | 3.61%   |
| 5.19.9-200.fc36.x86_64       | 41        | 3.45%   |
| 5.18.5-200.fc36.x86_64       | 38        | 3.19%   |
| 5.18.17-200.fc36.x86_64      | 38        | 3.19%   |
| 5.19.8-200.fc36.x86_64       | 37        | 3.11%   |
| 5.19.6-200.fc36.x86_64       | 36        | 3.03%   |
| 5.17.13-300.fc36.x86_64      | 36        | 3.03%   |
| 5.19.4-200.fc36.x86_64       | 33        | 2.77%   |
| 5.19.15-201.fc36.x86_64      | 32        | 2.69%   |
| 5.19.11-200.fc36.x86_64      | 30        | 2.52%   |
| 5.17.8-300.fc36.x86_64       | 29        | 2.44%   |
| 5.18.9-200.fc36.x86_64       | 28        | 2.35%   |
| 5.17.12-300.fc36.x86_64      | 27        | 2.27%   |
| 5.18.6-200.fc36.x86_64       | 26        | 2.18%   |
| 6.0.5-200.fc36.x86_64        | 25        | 2.1%    |
| 5.19.13-200.fc36.x86_64      | 25        | 2.1%    |
| 5.18.19-200.fc36.x86_64      | 25        | 2.1%    |
| 5.19.14-200.fc36.x86_64      | 24        | 2.02%   |
| 5.17.7-300.fc36.x86_64       | 24        | 2.02%   |
| 5.18.7-200.fc36.x86_64       | 23        | 1.93%   |
| 5.18.18-200.fc36.x86_64      | 22        | 1.85%   |
| 5.18.10-200.fc36.x86_64      | 21        | 1.76%   |
| 5.17.9-300.fc36.x86_64       | 21        | 1.76%   |
| 5.19.12-200.fc36.x86_64      | 18        | 1.51%   |
| 5.17.1-300.fc36.x86_64       | 16        | 1.34%   |
| 5.17.3-302.fc36.x86_64       | 14        | 1.18%   |
| 5.17.2-300.fc36.x86_64       | 13        | 1.09%   |
| 5.19.10-200.fc36.x86_64      | 12        | 1.01%   |
| 5.17.0-0.rc7.116.fc36.x86_64 | 12        | 1.01%   |
| 5.19.7-200.fc36.x86_64       | 7         | 0.59%   |
| 5.18.15-200.fc36.x86_64      | 6         | 0.5%    |
| 5.17.14-300.fc36.x86_64      | 5         | 0.42%   |
| 5.18.5-201.fsync.fc36.x86_64 | 3         | 0.25%   |
| 5.18.1-200.fc36.x86_64       | 3         | 0.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.5  | 96        | 8.07%   |
| 5.18.13 | 62        | 5.21%   |
| 5.18.11 | 50        | 4.2%    |
| 5.18.16 | 46        | 3.87%   |
| 5.17.11 | 46        | 3.87%   |
| 5.19.16 | 44        | 3.7%    |
| 5.17.6  | 43        | 3.61%   |
| 5.19.9  | 42        | 3.53%   |
| 5.18.5  | 42        | 3.53%   |
| 5.18.17 | 38        | 3.19%   |
| 5.19.8  | 37        | 3.11%   |
| 5.19.6  | 37        | 3.11%   |
| 5.17.13 | 36        | 3.03%   |
| 5.19.4  | 34        | 2.86%   |
| 5.19.15 | 33        | 2.77%   |
| 5.19.11 | 30        | 2.52%   |
| 5.17.8  | 29        | 2.44%   |
| 5.18.9  | 28        | 2.35%   |
| 5.18.6  | 28        | 2.35%   |
| 5.17.12 | 27        | 2.27%   |
| 6.0.5   | 25        | 2.1%    |
| 5.19.13 | 25        | 2.1%    |
| 5.18.19 | 25        | 2.1%    |
| 5.18.18 | 25        | 2.1%    |
| 5.17.7  | 25        | 2.1%    |
| 5.19.14 | 24        | 2.02%   |
| 5.18.10 | 24        | 2.02%   |
| 5.18.7  | 23        | 1.93%   |
| 5.17.9  | 21        | 1.76%   |
| 5.19.12 | 19        | 1.6%    |
| 5.17.0  | 17        | 1.43%   |
| 5.17.1  | 16        | 1.34%   |
| 5.17.3  | 15        | 1.26%   |
| 5.17.2  | 13        | 1.09%   |
| 5.19.10 | 12        | 1.01%   |
| 5.19.7  | 7         | 0.59%   |
| 5.18.15 | 6         | 0.5%    |
| 6.0.2   | 5         | 0.42%   |
| 5.17.14 | 5         | 0.42%   |
| 5.15.0  | 5         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.18    | 385       | 33.57%  |
| 5.17    | 380       | 33.13%  |
| 5.19    | 337       | 29.38%  |
| 6.0     | 34        | 2.96%   |
| 5.15    | 5         | 0.44%   |
| 5.16    | 4         | 0.35%   |
| 5.14    | 2         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1084      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 850       | 77.63%  |
| KDE5          | 152       | 13.88%  |
| Unknown       | 27        | 2.47%   |
| XFCE          | 18        | 1.64%   |
| X-Cinnamon    | 12        | 1.1%    |
| i3            | 8         | 0.73%   |
| MATE          | 6         | 0.55%   |
| Cinnamon      | 6         | 0.55%   |
| LXQt          | 4         | 0.37%   |
| sway          | 2         | 0.18%   |
| GNOME Classic | 2         | 0.18%   |
| awesome       | 2         | 0.18%   |
| openbox       | 1         | 0.09%   |
| LXDE          | 1         | 0.09%   |
| KDE:old       | 1         | 0.09%   |
| fluxbox       | 1         | 0.09%   |
| Deepin        | 1         | 0.09%   |
| bspwm         | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 830       | 75.73%  |
| X11     | 245       | 22.35%  |
| Unknown | 16        | 1.46%   |
| Tty     | 5         | 0.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 549       | 50.18%  |
| GDM     | 411       | 37.57%  |
| SDDM    | 78        | 7.13%   |
| LightDM | 54        | 4.94%   |
| Ly      | 1         | 0.09%   |
| KDM     | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 608       | 55.93%  |
| ru_RU   | 70        | 6.44%   |
| en_GB   | 55        | 5.06%   |
| it_IT   | 49        | 4.51%   |
| pt_BR   | 41        | 3.77%   |
| de_DE   | 40        | 3.68%   |
| fr_FR   | 27        | 2.48%   |
| pl_PL   | 20        | 1.84%   |
| en_AU   | 20        | 1.84%   |
| es_ES   | 18        | 1.66%   |
| en_IN   | 15        | 1.38%   |
| en_CA   | 13        | 1.2%    |
| es_MX   | 12        | 1.1%    |
| es_CL   | 7         | 0.64%   |
| tr_TR   | 6         | 0.55%   |
| ru_UA   | 5         | 0.46%   |
| pt_PT   | 5         | 0.46%   |
| hu_HU   | 5         | 0.46%   |
| de_AT   | 5         | 0.46%   |
| Unknown | 5         | 0.46%   |
| nl_NL   | 4         | 0.37%   |
| es_AR   | 4         | 0.37%   |
| en_NZ   | 4         | 0.37%   |
| da_DK   | 4         | 0.37%   |
| sv_SE   | 3         | 0.28%   |
| fr_BE   | 3         | 0.28%   |
| en_IL   | 3         | 0.28%   |
| cs_CZ   | 3         | 0.28%   |
| nl_BE   | 2         | 0.18%   |
| nb_NO   | 2         | 0.18%   |
| hr_HR   | 2         | 0.18%   |
| en_ZA   | 2         | 0.18%   |
| en_DK   | 2         | 0.18%   |
| de_CH   | 2         | 0.18%   |
| zh_CN   | 1         | 0.09%   |
| sr_RS   | 1         | 0.09%   |
| ja_JP   | 1         | 0.09%   |
| id_ID   | 1         | 0.09%   |
| gl_ES   | 1         | 0.09%   |
| ga_IE   | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 920       | 84.48%  |
| BIOS | 169       | 15.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 878       | 80.85%  |
| Ext4    | 188       | 17.31%  |
| Xfs     | 17        | 1.57%   |
| F2fs    | 2         | 0.18%   |
| Unknown | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 555       | 50.68%  |
| GPT     | 487       | 44.47%  |
| MBR     | 53        | 4.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 983       | 90.18%  |
| Yes       | 107       | 9.82%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 869       | 79.58%  |
| Yes       | 223       | 20.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 318       | 29.34%  |
| Dell                   | 174       | 16.05%  |
| Hewlett-Packard        | 170       | 15.68%  |
| ASUSTek Computer       | 123       | 11.35%  |
| Acer                   | 55        | 5.07%   |
| Apple                  | 35        | 3.23%   |
| MSI                    | 31        | 2.86%   |
| HUAWEI                 | 26        | 2.4%    |
| Framework              | 12        | 1.11%   |
| Toshiba                | 11        | 1.01%   |
| Timi                   | 9         | 0.83%   |
| Samsung Electronics    | 9         | 0.83%   |
| Notebook               | 9         | 0.83%   |
| Sony                   | 8         | 0.74%   |
| Unknown                | 6         | 0.55%   |
| Gigabyte Technology    | 5         | 0.46%   |
| Chuwi                  | 5         | 0.46%   |
| Positivo               | 4         | 0.37%   |
| Alienware              | 4         | 0.37%   |
| VALE                   | 3         | 0.28%   |
| TUXEDO                 | 3         | 0.28%   |
| System76               | 3         | 0.28%   |
| Panasonic              | 3         | 0.28%   |
| LG Electronics         | 3         | 0.28%   |
| HONOR                  | 3         | 0.28%   |
| GPU Company            | 3         | 0.28%   |
| Google                 | 3         | 0.28%   |
| Fujitsu                | 3         | 0.28%   |
| Avell High Performance | 3         | 0.28%   |
| UNOWHY                 | 2         | 0.18%   |
| Razer                  | 2         | 0.18%   |
| Itautec                | 2         | 0.18%   |
| GPD                    | 2         | 0.18%   |
| Gateway                | 2         | 0.18%   |
| Acidanthera            | 2         | 0.18%   |
| Wiltronic              | 1         | 0.09%   |
| VIT                    | 1         | 0.09%   |
| Standard               | 1         | 0.09%   |
| SLIMBOOK               | 1         | 0.09%   |
| SKIKK                  | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 13        | 1.2%    |
| Framework Laptop                       | 9         | 0.83%   |
| Lenovo IdeaPad 3 15ITL6 82H8           | 6         | 0.55%   |
| HP Notebook                            | 6         | 0.55%   |
| Dell XPS 15 9570                       | 6         | 0.55%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 5         | 0.46%   |
| HP Pavilion g6                         | 5         | 0.46%   |
| HP EliteBook 8470p                     | 5         | 0.46%   |
| ASUS ROG Zephyrus G14 GA402RJ_GA402RJ  | 5         | 0.46%   |
| Apple MacBookPro12,1                   | 5         | 0.46%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 4         | 0.37%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY   | 4         | 0.37%   |
| HP Pavilion Aero Laptop 13-be0xxx      | 4         | 0.37%   |
| Dell XPS 15 9510                       | 4         | 0.37%   |
| Dell XPS 13 9310                       | 4         | 0.37%   |
| Dell Latitude E6420                    | 4         | 0.37%   |
| ASUS ROG Strix G513QY_G513QY           | 4         | 0.37%   |
| Apple MacBookPro9,2                    | 4         | 0.37%   |
| Timi Redmi Book Pro 15 2022            | 3         | 0.28%   |
| Lenovo ThinkBook 16p Gen 2 20YM        | 3         | 0.28%   |
| Lenovo ThinkBook 15 G3 ACL 21A4        | 3         | 0.28%   |
| Lenovo ThinkBook 14 G3 ACL 21A2        | 3         | 0.28%   |
| Lenovo IdeaPad S340-14API 81NB         | 3         | 0.28%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 3         | 0.28%   |
| Lenovo IdeaPad 5 15ITL05 82FG          | 3         | 0.28%   |
| Lenovo IdeaPad 5 14ARE05 81YM          | 3         | 0.28%   |
| HUAWEI NBLK-WAX9X                      | 3         | 0.28%   |
| HUAWEI NBLB-WAX9N                      | 3         | 0.28%   |
| HUAWEI KLVL-WXXW                       | 3         | 0.28%   |
| HUAWEI BOD-WXX9                        | 3         | 0.28%   |
| HP Pavilion Laptop 15-cs0xxx           | 3         | 0.28%   |
| HP EliteBook 8460p                     | 3         | 0.28%   |
| HP EliteBook 840 G3                    | 3         | 0.28%   |
| HP 250 G7 Notebook PC                  | 3         | 0.28%   |
| Framework Laptop (12th Gen Intel Core) | 3         | 0.28%   |
| Dell XPS 17 9710                       | 3         | 0.28%   |
| Dell XPS 13 7390                       | 3         | 0.28%   |
| Dell Latitude 5420                     | 3         | 0.28%   |
| Dell Inspiron 7460                     | 3         | 0.28%   |
| Dell Inspiron 5567                     | 3         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 169       | 15.59%  |
| Lenovo IdeaPad     | 83        | 7.66%   |
| Dell Inspiron      | 54        | 4.98%   |
| Dell Latitude      | 44        | 4.06%   |
| Dell XPS           | 41        | 3.78%   |
| HP Pavilion        | 36        | 3.32%   |
| ASUS ROG           | 32        | 2.95%   |
| ASUS VivoBook      | 29        | 2.68%   |
| Acer Aspire        | 29        | 2.68%   |
| HP EliteBook       | 28        | 2.58%   |
| HP Laptop          | 27        | 2.49%   |
| HP ProBook         | 24        | 2.21%   |
| Lenovo ThinkBook   | 20        | 1.85%   |
| Dell Precision     | 19        | 1.75%   |
| Lenovo Legion      | 14        | 1.29%   |
| ASUS ASUS          | 13        | 1.2%    |
| Unknown            | 13        | 1.2%    |
| HP ZBook           | 12        | 1.11%   |
| Framework Laptop   | 12        | 1.11%   |
| Lenovo Yoga        | 10        | 0.92%   |
| Dell Vostro        | 10        | 0.92%   |
| Toshiba Satellite  | 9         | 0.83%   |
| Acer Swift         | 9         | 0.83%   |
| Acer Nitro         | 9         | 0.83%   |
| MSI Modern         | 8         | 0.74%   |
| HP ENVY            | 8         | 0.74%   |
| HP Notebook        | 6         | 0.55%   |
| MSI Prestige       | 5         | 0.46%   |
| ASUS Zenbook       | 5         | 0.46%   |
| ASUS TUF           | 5         | 0.46%   |
| Apple MacBookPro12 | 5         | 0.46%   |
| HP OMEN            | 4         | 0.37%   |
| HP 250             | 4         | 0.37%   |
| Dell G3            | 4         | 0.37%   |
| Apple MacBookPro9  | 4         | 0.37%   |
| VALE Notebook      | 3         | 0.28%   |
| Timi Redmi         | 3         | 0.28%   |
| HUAWEI NBLK-WAX9X  | 3         | 0.28%   |
| HUAWEI NBLB-WAX9N  | 3         | 0.28%   |
| HUAWEI KLVL-WXXW   | 3         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 230       | 21.22%  |
| 2020 | 167       | 15.41%  |
| 2019 | 107       | 9.87%   |
| 2018 | 98        | 9.04%   |
| 2022 | 76        | 7.01%   |
| 2017 | 62        | 5.72%   |
| 2015 | 57        | 5.26%   |
| 2016 | 54        | 4.98%   |
| 2013 | 53        | 4.89%   |
| 2012 | 48        | 4.43%   |
| 2011 | 44        | 4.06%   |
| 2014 | 43        | 3.97%   |
| 2010 | 18        | 1.66%   |
| 2009 | 14        | 1.29%   |
| 2008 | 12        | 1.11%   |
| 2006 | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1084      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 863       | 79.25%  |
| Enabled  | 226       | 20.75%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1078      | 99.45%  |
| Yes  | 6         | 0.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 327       | 30%     |
| 16.01-24.0  | 240       | 22.02%  |
| 8.01-16.0   | 232       | 21.28%  |
| 32.01-64.0  | 134       | 12.29%  |
| 3.01-4.0    | 97        | 8.9%    |
| 64.01-256.0 | 25        | 2.29%   |
| 1.01-2.0    | 18        | 1.65%   |
| 24.01-32.0  | 15        | 1.38%   |
| 2.01-3.0    | 2         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 348       | 30.55%  |
| 2.01-3.0   | 299       | 26.25%  |
| 3.01-4.0   | 277       | 24.32%  |
| 1.01-2.0   | 128       | 11.24%  |
| 8.01-16.0  | 76        | 6.67%   |
| 16.01-24.0 | 5         | 0.44%   |
| 0.51-1.0   | 4         | 0.35%   |
| 24.01-32.0 | 2         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 800       | 73.39%  |
| 2      | 253       | 23.21%  |
| 3      | 29        | 2.66%   |
| 4      | 4         | 0.37%   |
| 5      | 2         | 0.18%   |
| 0      | 2         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 881       | 81.27%  |
| Yes       | 203       | 18.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 751       | 69.03%  |
| No        | 337       | 30.97%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1066      | 98.34%  |
| No        | 18        | 1.66%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 944       | 86.76%  |
| No        | 144       | 13.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 199       | 18.24%  |
| Russia      | 87        | 7.97%   |
| Italy       | 84        | 7.7%    |
| Germany     | 72        | 6.6%    |
| Brazil      | 58        | 5.32%   |
| India       | 49        | 4.49%   |
| Poland      | 34        | 3.12%   |
| France      | 32        | 2.93%   |
| Mexico      | 29        | 2.66%   |
| Australia   | 27        | 2.47%   |
| UK          | 26        | 2.38%   |
| Netherlands | 26        | 2.38%   |
| Spain       | 24        | 2.2%    |
| Turkey      | 22        | 2.02%   |
| Canada      | 20        | 1.83%   |
| Indonesia   | 17        | 1.56%   |
| Belgium     | 14        | 1.28%   |
| Argentina   | 14        | 1.28%   |
| Czechia     | 11        | 1.01%   |
| Austria     | 11        | 1.01%   |
| Hungary     | 10        | 0.92%   |
| Sweden      | 9         | 0.82%   |
| Portugal    | 9         | 0.82%   |
| Norway      | 9         | 0.82%   |
| Chile       | 9         | 0.82%   |
| Denmark     | 8         | 0.73%   |
| Belarus     | 8         | 0.73%   |
| Switzerland | 7         | 0.64%   |
| Romania     | 7         | 0.64%   |
| Ukraine     | 6         | 0.55%   |
| Kenya       | 6         | 0.55%   |
| Ireland     | 6         | 0.55%   |
| Finland     | 6         | 0.55%   |
| Croatia     | 6         | 0.55%   |
| Israel      | 5         | 0.46%   |
| Egypt       | 5         | 0.46%   |
| Colombia    | 5         | 0.46%   |
| Taiwan      | 4         | 0.37%   |
| South Korea | 4         | 0.37%   |
| Philippines | 4         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Moscow             | 26        | 2.31%   |
| St Petersburg      | 20        | 1.78%   |
| Sao Paulo          | 13        | 1.16%   |
| Istanbul           | 12        | 1.07%   |
| Warsaw             | 10        | 0.89%   |
| Milan              | 9         | 0.8%    |
| Melbourne          | 9         | 0.8%    |
| Rome               | 8         | 0.71%   |
| Mexico City        | 8         | 0.71%   |
| Berlin             | 8         | 0.71%   |
| Prague             | 7         | 0.62%   |
| Munich             | 7         | 0.62%   |
| Paris              | 6         | 0.53%   |
| Oslo               | 6         | 0.53%   |
| Nairobi            | 6         | 0.53%   |
| Minsk              | 6         | 0.53%   |
| Kolkata            | 6         | 0.53%   |
| Budapest           | 6         | 0.53%   |
| Brisbane           | 6         | 0.53%   |
| Bengaluru          | 6         | 0.53%   |
| Verona             | 5         | 0.44%   |
| Santiago           | 5         | 0.44%   |
| New York           | 5         | 0.44%   |
| Chicago            | 5         | 0.44%   |
| Chennai            | 5         | 0.44%   |
| Zagreb             | 4         | 0.36%   |
| Vienna             | 4         | 0.36%   |
| Stockholm          | 4         | 0.36%   |
| Sofia              | 4         | 0.36%   |
| Santo Domingo Este | 4         | 0.36%   |
| Samara             | 4         | 0.36%   |
| Rio de Janeiro     | 4         | 0.36%   |
| Mundelein          | 4         | 0.36%   |
| Mumbai             | 4         | 0.36%   |
| Lisbon             | 4         | 0.36%   |
| Jakarta            | 4         | 0.36%   |
| Izmir              | 4         | 0.36%   |
| Helsinki           | 4         | 0.36%   |
| Guadalajara        | 4         | 0.36%   |
| Denver             | 4         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 279       | 344    | 20.5%   |
| WDC                            | 124       | 135    | 9.11%   |
| SanDisk                        | 96        | 114    | 7.05%   |
| Seagate                        | 92        | 104    | 6.76%   |
| SK hynix                       | 84        | 91     | 6.17%   |
| Toshiba                        | 66        | 75     | 4.85%   |
| Unknown                        | 65        | 77     | 4.78%   |
| Intel                          | 63        | 74     | 4.63%   |
| Micron Technology              | 61        | 69     | 4.48%   |
| Kingston                       | 55        | 61     | 4.04%   |
| Crucial                        | 46        | 51     | 3.38%   |
| KIOXIA                         | 32        | 41     | 2.35%   |
| A-DATA Technology              | 21        | 23     | 1.54%   |
| HGST                           | 20        | 23     | 1.47%   |
| Apple                          | 18        | 19     | 1.32%   |
| Phison                         | 17        | 17     | 1.25%   |
| Silicon Motion                 | 14        | 14     | 1.03%   |
| Hitachi                        | 11        | 11     | 0.81%   |
| Unknown                        | 11        | 11     | 0.81%   |
| China                          | 10        | 11     | 0.73%   |
| LITEON                         | 9         | 9      | 0.66%   |
| SSSTC                          | 8         | 8      | 0.59%   |
| PNY                            | 8         | 10     | 0.59%   |
| UMIS                           | 7         | 8      | 0.51%   |
| ADATA Technology               | 7         | 7      | 0.51%   |
| Phison Electronics             | 6         | 6      | 0.44%   |
| XPG                            | 5         | 8      | 0.37%   |
| Transcend                      | 5         | 6      | 0.37%   |
| SPCC                           | 5         | 5      | 0.37%   |
| Patriot                        | 5         | 6      | 0.37%   |
| Netac                          | 5         | 5      | 0.37%   |
| Intenso                        | 5         | 5      | 0.37%   |
| Union Memory (Shenzhen)        | 4         | 5      | 0.29%   |
| Team                           | 4         | 4      | 0.29%   |
| SABRENT                        | 4         | 4      | 0.29%   |
| Realtek Semiconductor          | 4         | 4      | 0.29%   |
| Lenovo                         | 4         | 6      | 0.29%   |
| Solid State Storage Technology | 3         | 3      | 0.22%   |
| Micron/Crucial Technology      | 3         | 3      | 0.22%   |
| LITEONIT                       | 3         | 3      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| SanDisk NVMe SSD Drive 512GB                        | 23        | 1.62%   |
| Seagate ST1000LM035-1RK172 1TB                      | 20        | 1.41%   |
| Samsung NVMe SSD Drive 512GB                        | 19        | 1.34%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 18        | 1.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 16        | 1.13%   |
| Intel NVMe SSD Drive 512GB                          | 15        | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 14        | 0.99%   |
| Samsung NVMe SSD Drive 1TB                          | 13        | 0.91%   |
| Samsung NVMe SSD Drive 1024GB                       | 13        | 0.91%   |
| Unknown MMC Card  64GB                              | 12        | 0.84%   |
| SK hynix NVMe SSD Drive 512GB                       | 12        | 0.84%   |
| HGST HTS721010A9E630 1TB                            | 12        | 0.84%   |
| Micron NVMe SSD Drive 512GB                         | 11        | 0.77%   |
| Unknown                                             | 11        | 0.77%   |
| Kingston SA400S37240G 240GB SSD                     | 10        | 0.7%    |
| SanDisk NVMe SSD Drive 1024GB                       | 9         | 0.63%   |
| Samsung NVMe SSD Drive 500GB                        | 9         | 0.63%   |
| Unknown MMC Card  32GB                              | 8         | 0.56%   |
| Unknown MMC Card  128GB                             | 8         | 0.56%   |
| Samsung SSD 860 EVO 250GB                           | 8         | 0.56%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 8         | 0.56%   |
| KIOXIA NVMe SSD Drive 512GB                         | 8         | 0.56%   |
| Toshiba NVMe SSD Drive 512GB                        | 7         | 0.49%   |
| Toshiba MQ04ABF100 1TB                              | 7         | 0.49%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 0.49%   |
| SK hynix NVMe SSD Drive 256GB                       | 7         | 0.49%   |
| SK hynix NVMe SSD Drive 1024GB                      | 7         | 0.49%   |
| SanDisk NVMe SSD Drive 1TB                          | 7         | 0.49%   |
| Samsung SSD 980 PRO 1TB                             | 7         | 0.49%   |
| Samsung SSD 860 EVO 500GB                           | 7         | 0.49%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 7         | 0.49%   |
| Crucial CT500MX500SSD1 500GB                        | 7         | 0.49%   |
| Toshiba NVMe SSD Drive 256GB                        | 6         | 0.42%   |
| Seagate ST500LT012-1DG142 500GB                     | 6         | 0.42%   |
| Seagate ST1000LM048-2E7172 1TB                      | 6         | 0.42%   |
| Samsung SSD 860 EVO 1TB                             | 6         | 0.42%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                      | 6         | 0.42%   |
| Crucial CT480BX500SSD1 480GB                        | 6         | 0.42%   |
| Crucial CT1000MX500SSD1 1TB                         | 6         | 0.42%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 5         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 89        | 101    | 42.38%  |
| WDC      | 48        | 54     | 22.86%  |
| Toshiba  | 28        | 31     | 13.33%  |
| HGST     | 20        | 23     | 9.52%   |
| Hitachi  | 11        | 11     | 5.24%   |
| SABRENT  | 4         | 4      | 1.9%    |
| Unknown  | 3         | 4      | 1.43%   |
| Fujitsu  | 3         | 3      | 1.43%   |
| Apple    | 2         | 2      | 0.95%   |
| USB3.0   | 1         | 1      | 0.48%   |
| IB-AC703 | 1         | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 85        | 101    | 23.29%  |
| Crucial             | 40        | 45     | 10.96%  |
| SanDisk             | 33        | 43     | 9.04%   |
| Kingston            | 31        | 35     | 8.49%   |
| WDC                 | 18        | 20     | 4.93%   |
| Intel               | 15        | 18     | 4.11%   |
| Micron Technology   | 12        | 13     | 3.29%   |
| Apple               | 12        | 12     | 3.29%   |
| A-DATA Technology   | 10        | 11     | 2.74%   |
| SK hynix            | 9         | 9      | 2.47%   |
| China               | 9         | 10     | 2.47%   |
| PNY                 | 7         | 8      | 1.92%   |
| LITEON              | 7         | 7      | 1.92%   |
| Transcend           | 5         | 6      | 1.37%   |
| Netac               | 5         | 5      | 1.37%   |
| Patriot             | 4         | 5      | 1.1%    |
| Intenso             | 4         | 4      | 1.1%    |
| Unknown             | 4         | 4      | 1.1%    |
| Toshiba             | 3         | 3      | 0.82%   |
| SPCC                | 3         | 3      | 0.82%   |
| LITEONIT            | 3         | 3      | 0.82%   |
| Lexar               | 3         | 3      | 0.82%   |
| Team                | 2         | 2      | 0.55%   |
| Seagate             | 2         | 2      | 0.55%   |
| OCZ                 | 2         | 2      | 0.55%   |
| KingDian            | 2         | 2      | 0.55%   |
| GOODRAM             | 2         | 4      | 0.55%   |
| GLOWAY              | 2         | 2      | 0.55%   |
| Gigabyte Technology | 2         | 3      | 0.55%   |
| GALAX               | 2         | 2      | 0.55%   |
| Apacer              | 2         | 2      | 0.55%   |
| XrayDisk            | 1         | 1      | 0.27%   |
| Win Memory          | 1         | 1      | 0.27%   |
| WDC WDS2            | 1         | 1      | 0.27%   |
| walram              | 1         | 1      | 0.27%   |
| Vaseky              | 1         | 1      | 0.27%   |
| TO Exter            | 1         | 1      | 0.27%   |
| Teclast             | 1         | 1      | 0.27%   |
| StoreJet            | 1         | 1      | 0.27%   |
| Origin              | 1         | 1      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 656       | 809    | 51.37%  |
| SSD     | 331       | 417    | 25.92%  |
| HDD     | 206       | 235    | 16.13%  |
| MMC     | 65        | 80     | 5.09%   |
| Unknown | 19        | 19     | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 656       | 806    | 52.44%  |
| SATA | 485       | 621    | 38.77%  |
| MMC  | 65        | 80     | 5.2%    |
| SAS  | 45        | 53     | 3.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 332       | 395    | 60.04%  |
| 0.51-1.0   | 188       | 216    | 34%     |
| 1.01-2.0   | 28        | 36     | 5.06%   |
| 3.01-4.0   | 4         | 4      | 0.72%   |
| 4.01-10.0  | 1         | 1      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 248       | 22.4%   |
| 251-500        | 226       | 20.42%  |
| 101-250        | 160       | 14.45%  |
| 1-20           | 141       | 12.74%  |
| 1001-2000      | 128       | 11.56%  |
| Unknown        | 90        | 8.13%   |
| 51-100         | 47        | 4.25%   |
| More than 3000 | 30        | 2.71%   |
| 2001-3000      | 26        | 2.35%   |
| 21-50          | 11        | 0.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 382       | 33.69%  |
| 21-50          | 198       | 17.46%  |
| 101-250        | 148       | 13.05%  |
| 51-100         | 135       | 11.9%   |
| 251-500        | 104       | 9.17%   |
| Unknown        | 90        | 7.94%   |
| 501-1000       | 59        | 5.2%    |
| 1001-2000      | 12        | 1.06%   |
| More than 3000 | 3         | 0.26%   |
| 2001-3000      | 3         | 0.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB           | 3         | 5      | 6.98%   |
| HGST HTS721010A9E630 1TB                     | 3         | 3      | 6.98%   |
| WDC WD6400BEVT-22A0RT0 640GB                 | 1         | 1      | 2.33%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 2.33%   |
| WDC WD5000LPCX-24C6HT0 500GB                 | 1         | 1      | 2.33%   |
| WDC WD5000LPCX-00VHAT0 500GB                 | 1         | 1      | 2.33%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 1      | 2.33%   |
| walram SSD 120G                              | 1         | 1      | 2.33%   |
| Toshiba MK5055GSX 500GB                      | 1         | 1      | 2.33%   |
| Toshiba MK3275GSX 320GB                      | 1         | 1      | 2.33%   |
| Toshiba MK2556GSY 250GB                      | 1         | 1      | 2.33%   |
| SK hynix HFS512G39TND-N210A 512GB SSD        | 1         | 1      | 2.33%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 2.33%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 2.33%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 2.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 1         | 1      | 2.33%   |
| Seagate ST2000LM003 HN-M201RAD 2TB           | 1         | 1      | 2.33%   |
| Seagate ST1000LM048-2E7172 1TB               | 1         | 1      | 2.33%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 2.33%   |
| SanDisk SSD PLUS 1000GB                      | 1         | 1      | 2.33%   |
| SanDisk SD6SB1M128G1022 128GB SSD            | 1         | 1      | 2.33%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD          | 1         | 1      | 2.33%   |
| Samsung Electronics SSD 980 PRO 500GB        | 1         | 1      | 2.33%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 2      | 2.33%   |
| Samsung Electronics SSD 840 Series 250GB     | 1         | 1      | 2.33%   |
| Origin Inception TLC830 Pro Series 256GB SSD | 1         | 1      | 2.33%   |
| OCZ-VERTEX3 MI 120GB SSD                     | 1         | 1      | 2.33%   |
| Micron Technology 1100 SATA 256GB SSD        | 1         | 1      | 2.33%   |
| LITEONIT LCS-128M6S-HP 128GB SSD             | 1         | 1      | 2.33%   |
| Lenovo LENSE20512GMSP34MEAT2TA 512GB         | 1         | 2      | 2.33%   |
| Kingston SHFS37A120G 120GB SSD               | 1         | 1      | 2.33%   |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 2.33%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 2.33%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 2.33%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 1      | 2.33%   |
| Fujitsu MJA2500BH G1 500GB                   | 1         | 1      | 2.33%   |
| Crucial M4-CT128M4SSD2 128GB                 | 1         | 1      | 2.33%   |
| Crucial CT1050MX300SSD1 1050GB               | 1         | 1      | 2.33%   |
| A-DATA Technology IM2P33F3A NVMe 256GB       | 1         | 1      | 2.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 12     | 23.26%  |
| WDC                 | 5         | 5      | 11.63%  |
| Hitachi             | 4         | 4      | 9.3%    |
| Toshiba             | 3         | 3      | 6.98%   |
| SanDisk             | 3         | 3      | 6.98%   |
| Samsung Electronics | 3         | 4      | 6.98%   |
| HGST                | 3         | 3      | 6.98%   |
| Crucial             | 2         | 2      | 4.65%   |
| walram              | 1         | 1      | 2.33%   |
| SK hynix            | 1         | 1      | 2.33%   |
| Origin              | 1         | 1      | 2.33%   |
| OCZ-VERTEX3         | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| LITEONIT            | 1         | 1      | 2.33%   |
| Lenovo              | 1         | 2      | 2.33%   |
| Kingston            | 1         | 1      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 12     | 38.46%  |
| WDC     | 5         | 5      | 19.23%  |
| Hitachi | 4         | 4      | 15.38%  |
| Toshiba | 3         | 3      | 11.54%  |
| HGST    | 3         | 3      | 11.54%  |
| Fujitsu | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 28     | 60.47%  |
| SSD  | 14        | 15     | 32.56%  |
| NVMe | 3         | 4      | 6.98%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 623       | 897    | 54.32%  |
| Works    | 481       | 615    | 41.94%  |
| Malfunc  | 42        | 47     | 3.66%   |
| Failed   | 1         | 1      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 624       | 44.51%  |
| Samsung Electronics            | 207       | 14.76%  |
| SanDisk                        | 119       | 8.49%   |
| AMD                            | 118       | 8.42%   |
| SK hynix                       | 74        | 5.28%   |
| Micron Technology              | 48        | 3.42%   |
| Toshiba America Info Systems   | 39        | 2.78%   |
| KIOXIA                         | 28        | 2%      |
| Phison Electronics             | 26        | 1.85%   |
| Kingston Technology Company    | 26        | 1.85%   |
| ADATA Technology               | 21        | 1.5%    |
| Silicon Motion                 | 16        | 1.14%   |
| Solid State Storage Technology | 10        | 0.71%   |
| Union Memory (Shenzhen)        | 9         | 0.64%   |
| Micron/Crucial Technology      | 9         | 0.64%   |
| Realtek Semiconductor          | 4         | 0.29%   |
| Nvidia                         | 4         | 0.29%   |
| Marvell Technology Group       | 4         | 0.29%   |
| Lite-On Technology             | 4         | 0.29%   |
| Lenovo                         | 4         | 0.29%   |
| Apple                          | 4         | 0.29%   |
| Yangtze Memory Technologies    | 1         | 0.07%   |
| Unknown                        | 1         | 0.07%   |
| Biwin Storage Technology       | 1         | 0.07%   |
| Unknown                        | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 113       | 7.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 86        | 5.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 85        | 5.79%   |
| Intel Volume Management Device NVMe RAID Controller                            | 69        | 4.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 63        | 4.29%   |
| Samsung NVMe SSD Controller 980                                                | 60        | 4.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 53        | 3.61%   |
| Micron Non-Volatile memory controller                                          | 48        | 3.27%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 39        | 2.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 38        | 2.59%   |
| SK hynix Gold P31 SSD                                                          | 36        | 2.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 36        | 2.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 34        | 2.31%   |
| Intel Tiger Lake-LP SATA Controller                                            | 33        | 2.25%   |
| SanDisk Non-Volatile memory controller                                         | 30        | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 30        | 2.04%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 23        | 1.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 22        | 1.5%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 22        | 1.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 22        | 1.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 22        | 1.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 21        | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 20        | 1.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 19        | 1.29%   |
| Intel Non-Volatile memory controller                                           | 18        | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 1.23%   |
| Intel SSD 660P Series                                                          | 17        | 1.16%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 16        | 1.09%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 15        | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13        | 0.88%   |
| SK hynix BC511                                                                 | 12        | 0.82%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 12        | 0.82%   |
| Kingston Company Company Non-Volatile memory controller                        | 11        | 0.75%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 11        | 0.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 11        | 0.75%   |
| Solid State Storage Non-Volatile memory controller                             | 10        | 0.68%   |
| SK hynix Non-Volatile memory controller                                        | 10        | 0.68%   |
| Phison PS5013 E13 NVMe Controller                                              | 10        | 0.68%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 10        | 0.68%   |
| Phison E12 NVMe Controller                                                     | 9         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 652       | 46.14%  |
| SATA | 626       | 44.3%   |
| RAID | 123       | 8.7%    |
| IDE  | 12        | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 822       | 75.83%  |
| AMD     | 261       | 24.08%  |
| Unknown | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 40        | 3.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 39        | 3.6%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 26        | 2.4%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 24        | 2.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 23        | 2.12%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 21        | 1.94%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 21        | 1.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 20        | 1.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 18        | 1.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 1.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 1.29%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 1.2%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 13        | 1.2%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 13        | 1.2%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 12        | 1.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 12        | 1.11%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 1.11%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 12        | 1.11%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 12        | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 1.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.01%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 11        | 1.01%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 10        | 0.92%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 10        | 0.92%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 9         | 0.83%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 9         | 0.83%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 9         | 0.83%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 0.83%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.74%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 8         | 0.74%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 8         | 0.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 0.65%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 7         | 0.65%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.65%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 7         | 0.65%   |
| AMD Ryzen 9 6900HS with Radeon Graphics       | 7         | 0.65%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 7         | 0.65%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 7         | 0.65%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 7         | 0.65%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 6         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 276       | 25.46%  |
| Intel Core i5                  | 227       | 20.94%  |
| Other                          | 170       | 15.68%  |
| AMD Ryzen 5                    | 90        | 8.3%    |
| AMD Ryzen 7                    | 78        | 7.2%    |
| Intel Core i3                  | 54        | 4.98%   |
| Intel Celeron                  | 37        | 3.41%   |
| AMD Ryzen 9                    | 27        | 2.49%   |
| Intel Core 2 Duo               | 16        | 1.48%   |
| AMD Ryzen 7 PRO                | 16        | 1.48%   |
| Intel Pentium                  | 11        | 1.01%   |
| Intel Atom                     | 11        | 1.01%   |
| AMD Ryzen 3                    | 11        | 1.01%   |
| Intel Core i9                  | 10        | 0.92%   |
| AMD Ryzen 5 PRO                | 9         | 0.83%   |
| AMD A10                        | 9         | 0.83%   |
| Intel Pentium Silver           | 6         | 0.55%   |
| AMD A6                         | 4         | 0.37%   |
| Intel Xeon                     | 3         | 0.28%   |
| AMD E1                         | 3         | 0.28%   |
| AMD A8                         | 3         | 0.28%   |
| AMD A4                         | 3         | 0.28%   |
| Intel Pentium Dual-Core        | 1         | 0.09%   |
| Intel Core m5                  | 1         | 0.09%   |
| Intel Core 2                   | 1         | 0.09%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.09%   |
| AMD Turion 64 X2 Mobile        | 1         | 0.09%   |
| AMD PRO A8                     | 1         | 0.09%   |
| AMD Phenom II                  | 1         | 0.09%   |
| AMD Athlon II Dual-Core        | 1         | 0.09%   |
| AMD Athlon II                  | 1         | 0.09%   |
| AMD Athlon                     | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 427       | 39.39%  |
| 2      | 349       | 32.2%   |
| 8      | 142       | 13.1%   |
| 6      | 134       | 12.36%  |
| 14     | 14        | 1.29%   |
| 12     | 11        | 1.01%   |
| 10     | 4         | 0.37%   |
| 1      | 2         | 0.18%   |
| 3      | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1084      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 957       | 88.2%   |
| 1      | 128       | 11.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1084      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 104       | 9.56%   |
| 0x306a9    | 61        | 5.61%   |
| 0x806ea    | 56        | 5.15%   |
| 0x806ec    | 52        | 4.78%   |
| 0x0a50000c | 50        | 4.6%    |
| Unknown    | 49        | 4.5%    |
| 0x206a7    | 45        | 4.14%   |
| 0x906ea    | 43        | 3.95%   |
| 0x806e9    | 43        | 3.95%   |
| 0x40651    | 40        | 3.68%   |
| 0xa0652    | 35        | 3.22%   |
| 0x08108109 | 33        | 3.03%   |
| 0x306d4    | 32        | 2.94%   |
| 0x406e3    | 31        | 2.85%   |
| 0x08608103 | 30        | 2.76%   |
| 0x08600106 | 29        | 2.67%   |
| 0x906a3    | 23        | 2.11%   |
| 0x506e3    | 21        | 1.93%   |
| 0x306c3    | 21        | 1.93%   |
| 0x906e9    | 20        | 1.84%   |
| 0x806d1    | 20        | 1.84%   |
| 0x706a8    | 15        | 1.38%   |
| 0x0a404101 | 15        | 1.38%   |
| 0x706e5    | 14        | 1.29%   |
| 0x08108102 | 13        | 1.19%   |
| 0x806eb    | 11        | 1.01%   |
| 0x20655    | 11        | 1.01%   |
| 0x08600104 | 11        | 1.01%   |
| 0x806c2    | 10        | 0.92%   |
| 0x1067a    | 10        | 0.92%   |
| 0x0a404102 | 10        | 0.92%   |
| 0x30678    | 9         | 0.83%   |
| 0x08608102 | 8         | 0.74%   |
| 0x506c9    | 7         | 0.64%   |
| 0x08600103 | 7         | 0.64%   |
| 0x906ed    | 6         | 0.55%   |
| 0x706a1    | 6         | 0.55%   |
| 0x406c4    | 6         | 0.55%   |
| 0x10676    | 6         | 0.55%   |
| 0xa0660    | 5         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 247       | 22.79%  |
| TigerLake        | 117       | 10.79%  |
| Unknown          | 70        | 6.46%   |
| Haswell          | 65        | 6%      |
| IvyBridge        | 62        | 5.72%   |
| Zen 3            | 60        | 5.54%   |
| Skylake          | 54        | 4.98%   |
| Zen 2            | 51        | 4.7%    |
| Zen+             | 47        | 4.34%   |
| SandyBridge      | 45        | 4.15%   |
| CometLake        | 41        | 3.78%   |
| Icelake          | 35        | 3.23%   |
| Broadwell        | 32        | 2.95%   |
| Alderlake Hybrid | 27        | 2.49%   |
| Silvermont       | 21        | 1.94%   |
| Goldmont plus    | 21        | 1.94%   |
| Westmere         | 17        | 1.57%   |
| Penryn           | 17        | 1.57%   |
| Zen              | 10        | 0.92%   |
| Excavator        | 9         | 0.83%   |
| Goldmont         | 7         | 0.65%   |
| Tremont          | 5         | 0.46%   |
| Jaguar           | 5         | 0.46%   |
| Piledriver       | 4         | 0.37%   |
| Puma             | 3         | 0.28%   |
| Nehalem          | 3         | 0.28%   |
| K10              | 3         | 0.28%   |
| K8 Hammer        | 1         | 0.09%   |
| K8 & K10 hybrid  | 1         | 0.09%   |
| K10 Llano        | 1         | 0.09%   |
| Core             | 1         | 0.09%   |
| Bonnell          | 1         | 0.09%   |
| Bobcat           | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 775       | 53.71%  |
| Nvidia | 363       | 25.16%  |
| AMD    | 305       | 21.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 111       | 7.54%   |
| Intel UHD Graphics 620                                                                   | 58        | 3.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 55        | 3.73%   |
| AMD Cezanne                                                                              | 53        | 3.6%    |
| AMD Renoir                                                                               | 51        | 3.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 48        | 3.26%   |
| Intel HD Graphics 620                                                                    | 42        | 2.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 41        | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 40        | 2.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 2.65%   |
| AMD Lucienne                                                                             | 39        | 2.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 38        | 2.58%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 35        | 2.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 30        | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 1.9%    |
| AMD Rembrandt [Radeon 680M]                                                              | 26        | 1.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 25        | 1.7%    |
| Intel HD Graphics 5500                                                                   | 25        | 1.7%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 25        | 1.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 21        | 1.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 1.43%   |
| Intel HD Graphics 530                                                                    | 18        | 1.22%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 17        | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 16        | 1.09%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 15        | 1.02%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 0.95%   |
| Intel HD Graphics 630                                                                    | 14        | 0.95%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 13        | 0.88%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 13        | 0.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 10        | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 9         | 0.61%   |
| Nvidia TU117M                                                                            | 9         | 0.61%   |
| Nvidia GP108M [GeForce MX250]                                                            | 9         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 0.61%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 8         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 473       | 43.63%  |
| Intel + Nvidia | 267       | 24.63%  |
| 1 x AMD        | 190       | 17.53%  |
| AMD + Nvidia   | 57        | 5.26%   |
| 1 x Nvidia     | 37        | 3.41%   |
| Intel + AMD    | 33        | 3.04%   |
| 2 x AMD        | 25        | 2.31%   |
| Other          | 1         | 0.09%   |
| 2 x Nvidia     | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 915       | 84.18%  |
| Proprietary | 162       | 14.9%   |
| Unknown     | 10        | 0.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 616       | 56.46%  |
| 1.01-2.0   | 158       | 14.48%  |
| 0.01-0.5   | 141       | 12.92%  |
| 3.01-4.0   | 79        | 7.24%   |
| 0.51-1.0   | 54        | 4.95%   |
| 7.01-8.0   | 16        | 1.47%   |
| 5.01-6.0   | 16        | 1.47%   |
| 8.01-16.0  | 6         | 0.55%   |
| 2.01-3.0   | 5         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 247       | 18.68%  |
| BOE                     | 229       | 17.32%  |
| Chimei Innolux          | 170       | 12.86%  |
| LG Display              | 152       | 11.5%   |
| Samsung Electronics     | 83        | 6.28%   |
| Sharp                   | 51        | 3.86%   |
| Goldstar                | 51        | 3.86%   |
| Dell                    | 51        | 3.86%   |
| Apple                   | 36        | 2.72%   |
| PANDA                   | 30        | 2.27%   |
| Lenovo                  | 25        | 1.89%   |
| CSO                     | 24        | 1.82%   |
| Hewlett-Packard         | 21        | 1.59%   |
| Philips                 | 18        | 1.36%   |
| InfoVision              | 13        | 0.98%   |
| Chi Mei Optoelectronics | 13        | 0.98%   |
| BenQ                    | 12        | 0.91%   |
| TMX                     | 11        | 0.83%   |
| Acer                    | 9         | 0.68%   |
| ViewSonic               | 8         | 0.61%   |
| AOC                     | 8         | 0.61%   |
| Iiyama                  | 6         | 0.45%   |
| Ancor Communications    | 6         | 0.45%   |
| Vizio                   | 3         | 0.23%   |
| Toshiba                 | 3         | 0.23%   |
| MSI                     | 3         | 0.23%   |
| JDI                     | 3         | 0.23%   |
| SKY                     | 2         | 0.15%   |
| ONN                     | 2         | 0.15%   |
| Mi                      | 2         | 0.15%   |
| KDC                     | 2         | 0.15%   |
| HKC                     | 2         | 0.15%   |
| Gigabyte Technology     | 2         | 0.15%   |
| ASUSTek Computer        | 2         | 0.15%   |
| YCT                     | 1         | 0.08%   |
| VIE                     | 1         | 0.08%   |
| Unknown (XXX)           | 1         | 0.08%   |
| STA                     | 1         | 0.08%   |
| Sony                    | 1         | 0.08%   |
| SLD                     | 1         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch   | 13        | 0.97%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch | 12        | 0.89%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch            | 12        | 0.89%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch | 10        | 0.74%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch            | 10        | 0.74%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch          | 8         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch | 7         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch | 7         | 0.52%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch | 7         | 0.52%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch   | 7         | 0.52%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch   | 7         | 0.52%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch   | 7         | 0.52%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch     | 6         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch | 6         | 0.45%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch            | 6         | 0.45%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch            | 6         | 0.45%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch             | 6         | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch   | 6         | 0.45%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch   | 6         | 0.45%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch      | 5         | 0.37%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch         | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch | 5         | 0.37%   |
| BOE LCD Monitor BOE0A1D 2560x1600 302x189mm 14.0-inch            | 5         | 0.37%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch            | 5         | 0.37%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch   | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch   | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch    | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch    | 5         | 0.37%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch          | 4         | 0.3%    |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch          | 4         | 0.3%    |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch          | 4         | 0.3%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch          | 4         | 0.3%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch          | 4         | 0.3%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch     | 4         | 0.3%    |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch     | 4         | 0.3%    |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch     | 4         | 0.3%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch     | 4         | 0.3%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch     | 4         | 0.3%    |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch          | 4         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 635       | 51.92%  |
| 1366x768 (WXGA)    | 209       | 17.09%  |
| 3840x2160 (4K)     | 65        | 5.31%   |
| 2560x1440 (QHD)    | 53        | 4.33%   |
| 1920x1200 (WUXGA)  | 41        | 3.35%   |
| 1600x900 (HD+)     | 37        | 3.03%   |
| 2560x1600          | 31        | 2.53%   |
| 3840x2400          | 16        | 1.31%   |
| 2880x1800          | 16        | 1.31%   |
| 1280x800 (WXGA)    | 16        | 1.31%   |
| 3440x1440          | 15        | 1.23%   |
| 2256x1504          | 12        | 0.98%   |
| 1440x900 (WXGA+)   | 12        | 0.98%   |
| 2560x1080          | 10        | 0.82%   |
| 2160x1440          | 9         | 0.74%   |
| 1280x1024 (SXGA)   | 9         | 0.74%   |
| 3456x2160          | 5         | 0.41%   |
| 3200x2000          | 4         | 0.33%   |
| 3072x1920          | 3         | 0.25%   |
| 2520x1680          | 3         | 0.25%   |
| 2240x1400          | 3         | 0.25%   |
| 1680x1050 (WSXGA+) | 3         | 0.25%   |
| 1360x768           | 3         | 0.25%   |
| 3840x1600          | 2         | 0.16%   |
| 3200x1800 (QHD+)   | 2         | 0.16%   |
| 3000x2000          | 2         | 0.16%   |
| 2400x1600          | 1         | 0.08%   |
| 2304x1440          | 1         | 0.08%   |
| 1920x550           | 1         | 0.08%   |
| 1920x540           | 1         | 0.08%   |
| 1600x1200          | 1         | 0.08%   |
| 1024x768 (XGA)     | 1         | 0.08%   |
| 1024x600           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 492       | 37.08%  |
| 13      | 215       | 16.2%   |
| 14      | 213       | 16.05%  |
| 27      | 69        | 5.2%    |
| 17      | 69        | 5.2%    |
| 24      | 47        | 3.54%   |
| 23      | 35        | 2.64%   |
| 21      | 34        | 2.56%   |
| 16      | 27        | 2.03%   |
| 12      | 26        | 1.96%   |
| 34      | 20        | 1.51%   |
| 31      | 19        | 1.43%   |
| 11      | 12        | 0.9%    |
| 19      | 7         | 0.53%   |
| 20      | 6         | 0.45%   |
| 18      | 5         | 0.38%   |
| 84      | 4         | 0.3%    |
| Unknown | 4         | 0.3%    |
| 40      | 3         | 0.23%   |
| 35      | 3         | 0.23%   |
| 29      | 3         | 0.23%   |
| 22      | 3         | 0.23%   |
| 37      | 2         | 0.15%   |
| 32      | 2         | 0.15%   |
| 10      | 2         | 0.15%   |
| 69      | 1         | 0.08%   |
| 50      | 1         | 0.08%   |
| 39      | 1         | 0.08%   |
| 26      | 1         | 0.08%   |
| 25      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 825       | 62.88%  |
| 201-300     | 149       | 11.36%  |
| 501-600     | 138       | 10.52%  |
| 351-400     | 80        | 6.1%    |
| 401-500     | 52        | 3.96%   |
| 601-700     | 27        | 2.06%   |
| 701-800     | 21        | 1.6%    |
| 801-900     | 10        | 0.76%   |
| 1501-2000   | 5         | 0.38%   |
| Unknown     | 4         | 0.3%    |
| 1001-1500   | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 914       | 80.18%  |
| 16/10   | 158       | 13.86%  |
| 3/2     | 27        | 2.37%   |
| 21/9    | 27        | 2.37%   |
| 5/4     | 8         | 0.7%    |
| 4/3     | 3         | 0.26%   |
| 32/9    | 2         | 0.18%   |
| Unknown | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 494       | 37.34%  |
| 81-90          | 348       | 26.3%   |
| 201-250        | 91        | 6.88%   |
| 71-80          | 77        | 5.82%   |
| 301-350        | 72        | 5.44%   |
| 121-130        | 61        | 4.61%   |
| 351-500        | 44        | 3.33%   |
| 61-70          | 25        | 1.89%   |
| 111-120        | 25        | 1.89%   |
| 251-300        | 21        | 1.59%   |
| 151-200        | 19        | 1.44%   |
| 51-60          | 12        | 0.91%   |
| 141-150        | 9         | 0.68%   |
| More than 1000 | 6         | 0.45%   |
| 131-140        | 5         | 0.38%   |
| 501-1000       | 5         | 0.38%   |
| Unknown        | 4         | 0.3%    |
| 91-100         | 3         | 0.23%   |
| 41-50          | 2         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 630       | 48.57%  |
| 101-120       | 252       | 19.43%  |
| 51-100        | 171       | 13.18%  |
| 161-240       | 164       | 12.64%  |
| More than 240 | 74        | 5.71%   |
| Unknown       | 4         | 0.31%   |
| 1-50          | 2         | 0.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 834       | 75.68%  |
| 2     | 221       | 20.05%  |
| 3     | 25        | 2.27%   |
| 0     | 16        | 1.45%   |
| 4     | 5         | 0.45%   |
| 5     | 1         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 628       | 39.23%  |
| Realtek Semiconductor             | 551       | 34.42%  |
| Qualcomm Atheros                  | 151       | 9.43%   |
| Broadcom                          | 70        | 4.37%   |
| MediaTek                          | 58        | 3.62%   |
| Broadcom Limited                  | 20        | 1.25%   |
| Lenovo                            | 11        | 0.69%   |
| TP-Link                           | 9         | 0.56%   |
| Sierra Wireless                   | 9         | 0.56%   |
| Qualcomm                          | 8         | 0.5%    |
| ASIX Electronics                  | 8         | 0.5%    |
| Samsung Electronics               | 7         | 0.44%   |
| Ralink                            | 7         | 0.44%   |
| DisplayLink                       | 6         | 0.37%   |
| Ralink Technology                 | 5         | 0.31%   |
| T & A Mobile Phones               | 4         | 0.25%   |
| Nvidia                            | 4         | 0.25%   |
| Hewlett-Packard                   | 4         | 0.25%   |
| Ericsson Business Mobile Networks | 4         | 0.25%   |
| Huawei Technologies               | 3         | 0.19%   |
| Dell                              | 3         | 0.19%   |
| Apple                             | 3         | 0.19%   |
| Xiaomi                            | 2         | 0.12%   |
| OPPO Electronics                  | 2         | 0.12%   |
| Microsoft                         | 2         | 0.12%   |
| Marvell Technology Group          | 2         | 0.12%   |
| Google                            | 2         | 0.12%   |
| FIBOCOM                           | 2         | 0.12%   |
| D-Link                            | 2         | 0.12%   |
| Belkin Components                 | 2         | 0.12%   |
| Shenzhen Goodix Technology        | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.06%   |
| OnePlus                           | 1         | 0.06%   |
| MicroPython                       | 1         | 0.06%   |
| Microchip Technology              | 1         | 0.06%   |
| Linksys                           | 1         | 0.06%   |
| IMC Networks                      | 1         | 0.06%   |
| ICS Advent                        | 1         | 0.06%   |
| Edimax Technology                 | 1         | 0.06%   |
| D-Link System                     | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 318       | 16.4%   |
| Intel Wi-Fi 6 AX201                                               | 88        | 4.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 77        | 3.97%   |
| Intel Wi-Fi 6 AX200                                               | 67        | 3.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 3.2%    |
| Intel Wireless 8265 / 8275                                        | 53        | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 48        | 2.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 41        | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 41        | 2.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 40        | 2.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 36        | 1.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 36        | 1.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 34        | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 33        | 1.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 29        | 1.5%    |
| Intel Wireless 8260                                               | 27        | 1.39%   |
| Intel Wireless 7265                                               | 26        | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 26        | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 22        | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 22        | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 21        | 1.08%   |
| Intel Wireless 7260                                               | 21        | 1.08%   |
| Intel Centrino Ultimate-N 6300                                    | 19        | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 19        | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 18        | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 0.93%   |
| Intel Wireless 3165                                               | 17        | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 17        | 0.88%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 16        | 0.83%   |
| Intel Wireless-AC 9260                                            | 15        | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 0.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 0.67%   |
| Intel Ethernet Connection (13) I219-V                             | 13        | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 12        | 0.62%   |
| Intel Wireless 3160                                               | 11        | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 11        | 0.57%   |
| Broadcom BCM43142 802.11b/g/n                                     | 11        | 0.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 0.52%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 607       | 54.78%  |
| Realtek Semiconductor | 182       | 16.43%  |
| Qualcomm Atheros      | 138       | 12.45%  |
| Broadcom              | 59        | 5.32%   |
| MediaTek              | 57        | 5.14%   |
| Broadcom Limited      | 17        | 1.53%   |
| Sierra Wireless       | 9         | 0.81%   |
| TP-Link               | 7         | 0.63%   |
| Ralink                | 7         | 0.63%   |
| Qualcomm              | 7         | 0.63%   |
| Ralink Technology     | 5         | 0.45%   |
| Microsoft             | 2         | 0.18%   |
| FIBOCOM               | 2         | 0.18%   |
| Belkin Components     | 2         | 0.18%   |
| Linksys               | 1         | 0.09%   |
| IMC Networks          | 1         | 0.09%   |
| Edimax Technology     | 1         | 0.09%   |
| Dell                  | 1         | 0.09%   |
| D-Link System         | 1         | 0.09%   |
| D-Link                | 1         | 0.09%   |
| ASUSTek Computer      | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 88        | 7.91%   |
| Intel Wi-Fi 6 AX200                                            | 67        | 6.03%   |
| Intel Wireless 8265 / 8275                                     | 53        | 4.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 48        | 4.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 41        | 3.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 40        | 3.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 36        | 3.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 36        | 3.24%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 34        | 3.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 33        | 2.97%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 29        | 2.61%   |
| Intel Wireless 8260                                            | 27        | 2.43%   |
| Intel Wireless 7265                                            | 26        | 2.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 26        | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 22        | 1.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 22        | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 21        | 1.89%   |
| Intel Wireless 7260                                            | 21        | 1.89%   |
| Intel Centrino Ultimate-N 6300                                 | 19        | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 19        | 1.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 18        | 1.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 1.62%   |
| Intel Wireless 3165                                            | 17        | 1.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 17        | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 16        | 1.44%   |
| Intel Wireless-AC 9260                                         | 15        | 1.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 12        | 1.08%   |
| Intel Wireless 3160                                            | 11        | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 11        | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                  | 11        | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10        | 0.9%    |
| MediaTek WLAN controller                                       | 9         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.81%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 8         | 0.72%   |
| Realtek Realtek Network controller                             | 7         | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 7         | 0.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 7         | 0.63%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 7         | 0.63%   |
| Realtek 802.11ac NIC                                           | 6         | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 475       | 59.9%   |
| Intel                    | 209       | 26.36%  |
| Qualcomm Atheros         | 26        | 3.28%   |
| Broadcom                 | 21        | 2.65%   |
| Lenovo                   | 11        | 1.39%   |
| ASIX Electronics         | 8         | 1.01%   |
| Samsung Electronics      | 7         | 0.88%   |
| DisplayLink              | 6         | 0.76%   |
| Nvidia                   | 4         | 0.5%    |
| TP-Link                  | 3         | 0.38%   |
| Broadcom Limited         | 3         | 0.38%   |
| Apple                    | 3         | 0.38%   |
| Xiaomi                   | 2         | 0.25%   |
| OPPO Electronics         | 2         | 0.25%   |
| Marvell Technology Group | 2         | 0.25%   |
| Huawei Technologies      | 2         | 0.25%   |
| Google                   | 2         | 0.25%   |
| T & A Mobile Phones      | 1         | 0.13%   |
| Qualcomm                 | 1         | 0.13%   |
| OnePlus                  | 1         | 0.13%   |
| MediaTek                 | 1         | 0.13%   |
| ICS Advent               | 1         | 0.13%   |
| Hewlett-Packard          | 1         | 0.13%   |
| D-Link                   | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 318       | 39.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 77        | 9.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 7.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 41        | 5.07%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 2.1%    |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 1.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 1.61%   |
| Intel Ethernet Connection (13) I219-V                             | 13        | 1.61%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 1.24%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 1.24%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 9         | 1.11%   |
| Intel Ethernet Connection (10) I219-V                             | 9         | 1.11%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 0.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.87%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.74%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.62%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.62%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.62%   |
| Intel Ethernet Connection (6) I219-LM                             | 5         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 4         | 0.5%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 4         | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                             | 4         | 0.5%    |
| DisplayLink LAPDOCK                                               | 4         | 0.5%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 0.5%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 3         | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.37%   |
| Lenovo ThinkPad Lan                                               | 3         | 0.37%   |
| Intel Ethernet controller                                         | 3         | 0.37%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.37%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1067      | 58.18%  |
| Ethernet | 749       | 40.84%  |
| Modem    | 14        | 0.76%   |
| Unknown  | 4         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 941       | 82.47%  |
| Ethernet | 199       | 17.44%  |
| Modem    | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 657       | 60.61%  |
| 1     | 394       | 36.35%  |
| 0     | 20        | 1.85%   |
| 3     | 13        | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 818       | 74.91%  |
| Yes  | 274       | 25.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 515       | 54.21%  |
| Realtek Semiconductor           | 119       | 12.53%  |
| Qualcomm Atheros Communications | 81        | 8.53%   |
| IMC Networks                    | 51        | 5.37%   |
| Broadcom                        | 44        | 4.63%   |
| Foxconn / Hon Hai               | 40        | 4.21%   |
| Apple                           | 29        | 3.05%   |
| Lite-On Technology              | 26        | 2.74%   |
| Realtek                         | 11        | 1.16%   |
| Cambridge Silicon Radio         | 8         | 0.84%   |
| Ralink                          | 7         | 0.74%   |
| Toshiba                         | 4         | 0.42%   |
| Hewlett-Packard                 | 4         | 0.42%   |
| Dell                            | 4         | 0.42%   |
| Opticis                         | 2         | 0.21%   |
| ASUSTek Computer                | 2         | 0.21%   |
| USI                             | 1         | 0.11%   |
| Qcom                            | 1         | 0.11%   |
| Micro Star International        | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 148       | 15.56%  |
| Intel AX201 Bluetooth                               | 131       | 13.77%  |
| Realtek Bluetooth Radio                             | 86        | 9.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 86        | 9.04%   |
| Intel AX200 Bluetooth                               | 66        | 6.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 41        | 4.31%   |
| Intel AX210 Bluetooth                               | 34        | 3.58%   |
| IMC Networks Wireless_Device                        | 28        | 2.94%   |
| Foxconn / Hon Hai Wireless_Device                   | 21        | 2.21%   |
| Apple Bluetooth Host Controller                     | 19        | 2%      |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 1.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 18        | 1.89%   |
| Intel Bluetooth Device                              | 17        | 1.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 14        | 1.47%   |
| IMC Networks Bluetooth Radio                        | 12        | 1.26%   |
| Realtek Bluetooth Radio                             | 11        | 1.16%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 1.05%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 0.95%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 0.84%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 0.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 0.84%   |
| Apple Bluetooth USB Host Controller                 | 8         | 0.84%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.74%   |
| Lite-On Wireless_Device                             | 6         | 0.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.63%   |
| Lite-On Bluetooth Device                            | 6         | 0.63%   |
| Broadcom HP Portable SoftSailing                    | 6         | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.53%   |
| IMC Networks Bluetooth Device                       | 5         | 0.53%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.53%   |
| Realtek RTL8723B Bluetooth                          | 4         | 0.42%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.42%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.42%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 0.42%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.32%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.32%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.32%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 806       | 57.78%  |
| AMD                         | 272       | 19.5%   |
| Nvidia                      | 194       | 13.91%  |
| Lenovo                      | 14        | 1%      |
| Realtek Semiconductor       | 9         | 0.65%   |
| GN Netcom                   | 9         | 0.65%   |
| C-Media Electronics         | 9         | 0.65%   |
| Logitech                    | 7         | 0.5%    |
| Hewlett-Packard             | 7         | 0.5%    |
| Plantronics                 | 6         | 0.43%   |
| Conexant Systems            | 4         | 0.29%   |
| Apple                       | 4         | 0.29%   |
| XMOS                        | 3         | 0.22%   |
| Texas Instruments           | 3         | 0.22%   |
| Samson Technologies         | 3         | 0.22%   |
| Creative Technology         | 3         | 0.22%   |
| Corsair                     | 3         | 0.22%   |
| ASUSTek Computer            | 3         | 0.22%   |
| Yamaha                      | 2         | 0.14%   |
| Sony                        | 2         | 0.14%   |
| Sennheiser Communications   | 2         | 0.14%   |
| No brand                    | 2         | 0.14%   |
| Kingston Technology         | 2         | 0.14%   |
| JMTek                       | 2         | 0.14%   |
| Generalplus Technology      | 2         | 0.14%   |
| Focusrite-Novation          | 2         | 0.14%   |
| Syntek                      | 1         | 0.07%   |
| Samsung Electronics         | 1         | 0.07%   |
| RODE Microphones            | 1         | 0.07%   |
| RME                         | 1         | 0.07%   |
| Razer USA                   | 1         | 0.07%   |
| PreSonus Audio Electronics  | 1         | 0.07%   |
| Medeli Electronics          | 1         | 0.07%   |
| Jieli Technology            | 1         | 0.07%   |
| FiiO Electronics Technology | 1         | 0.07%   |
| fifinemicrophone.com        | 1         | 0.07%   |
| FIFINE Microphones          | 1         | 0.07%   |
| DisplayLink                 | 1         | 0.07%   |
| Cooler Master               | 1         | 0.07%   |
| CMX Systems                 | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 224       | 12.91%  |
| Intel Sunrise Point-LP HD Audio                                            | 138       | 7.95%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 130       | 7.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 117       | 6.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 71        | 4.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 53        | 3.05%   |
| Intel Cannon Lake PCH cAVS                                                 | 49        | 2.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 43        | 2.48%   |
| Intel Haswell-ULT HD Audio Controller                                      | 40        | 2.31%   |
| Intel 8 Series HD Audio Controller                                         | 40        | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 36        | 2.07%   |
| Intel Comet Lake PCH cAVS                                                  | 35        | 2.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 33        | 1.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 32        | 1.84%   |
| Intel Broadwell-U Audio Controller                                         | 32        | 1.84%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 30        | 1.73%   |
| Nvidia GA106 High Definition Audio Controller                              | 25        | 1.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 25        | 1.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 23        | 1.33%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 22        | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 22        | 1.27%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 22        | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21        | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 21        | 1.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 20        | 1.15%   |
| Nvidia GA104 High Definition Audio Controller                              | 19        | 1.1%    |
| Intel CM238 HD Audio Controller                                            | 19        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 0.98%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 15        | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                   | 15        | 0.86%   |
| AMD FCH Azalia Controller                                                  | 14        | 0.81%   |
| Nvidia Audio device                                                        | 13        | 0.75%   |
| Nvidia TU116 High Definition Audio Controller                              | 12        | 0.69%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11        | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                              | 10        | 0.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 0.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 9         | 0.52%   |
| Realtek Semiconductor USB Audio                                            | 8         | 0.46%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 8         | 0.46%   |
| Nvidia GF119 HDMI Audio Controller                                         | 8         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 210       | 31.58%  |
| SK hynix                                         | 142       | 21.35%  |
| Micron Technology                                | 106       | 15.94%  |
| Kingston                                         | 40        | 6.02%   |
| Crucial                                          | 38        | 5.71%   |
| Unknown                                          | 26        | 3.91%   |
| Ramaxel Technology                               | 19        | 2.86%   |
| A-DATA Technology                                | 16        | 2.41%   |
| Unknown (ABCD)                                   | 12        | 1.8%    |
| Unknown                                          | 8         | 1.2%    |
| Patriot                                          | 7         | 1.05%   |
| Smart                                            | 6         | 0.9%    |
| Team                                             | 5         | 0.75%   |
| Nanya Technology                                 | 5         | 0.75%   |
| G.Skill                                          | 5         | 0.75%   |
| Elpida                                           | 3         | 0.45%   |
| Silicon Power                                    | 2         | 0.3%    |
| ChangXin Memory                                  | 2         | 0.3%    |
| V-GEN                                            | 1         | 0.15%   |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.15%   |
| Unknown (0x4D342037305432393533455A332D43453620) | 1         | 0.15%   |
| Smart Brazil                                     | 1         | 0.15%   |
| Sesame                                           | 1         | 0.15%   |
| Qimonda                                          | 1         | 0.15%   |
| PNY                                              | 1         | 0.15%   |
| Neo Forza                                        | 1         | 0.15%   |
| Kllisre                                          | 1         | 0.15%   |
| Hikvision                                        | 1         | 0.15%   |
| Goldkey                                          | 1         | 0.15%   |
| Corsair                                          | 1         | 0.15%   |
| Atermiter                                        | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 16        | 2.32%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s    | 12        | 1.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 12        | 1.74%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 11        | 1.59%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 10        | 1.45%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 10        | 1.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 9         | 1.3%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 9         | 1.3%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 8         | 1.16%   |
| Unknown                                                             | 8         | 1.16%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 7         | 1.01%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 7         | 1.01%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 6         | 0.87%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s           | 6         | 0.87%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 6         | 0.87%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 6         | 0.87%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 0.72%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 5         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 0.72%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 0.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 5         | 0.72%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 5         | 0.72%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 0.72%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 5         | 0.72%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 5         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 4         | 0.58%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 4         | 0.58%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 4         | 0.58%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 4         | 0.58%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 4         | 0.58%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s           | 4         | 0.58%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 4         | 0.58%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 4         | 0.58%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s              | 4         | 0.58%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 3         | 0.43%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                        | 3         | 0.43%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 3         | 0.43%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 3         | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 3         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 327       | 58.81%  |
| DDR3    | 126       | 22.66%  |
| LPDDR4  | 45        | 8.09%   |
| LPDDR3  | 23        | 4.14%   |
| LPDDR5  | 12        | 2.16%   |
| DDR5    | 10        | 1.8%    |
| Unknown | 7         | 1.26%   |
| DDR2    | 4         | 0.72%   |
| SDRAM   | 1         | 0.18%   |
| DDR     | 1         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 470       | 81.46%  |
| Row Of Chips | 99        | 17.16%  |
| Chip         | 5         | 0.87%   |
| Unknown      | 2         | 0.35%   |
| DIMM         | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 244       | 40.87%  |
| 4096  | 184       | 30.82%  |
| 16384 | 100       | 16.75%  |
| 2048  | 40        | 6.7%    |
| 32768 | 23        | 3.85%   |
| 1024  | 4         | 0.67%   |
| 3072  | 2         | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 180       | 30.51%  |
| 2667    | 119       | 20.17%  |
| 1600    | 94        | 15.93%  |
| 2400    | 41        | 6.95%   |
| 2133    | 29        | 4.92%   |
| 4267    | 19        | 3.22%   |
| 6400    | 14        | 2.37%   |
| 1333    | 14        | 2.37%   |
| 4800    | 13        | 2.2%    |
| 1867    | 13        | 2.2%    |
| 1334    | 13        | 2.2%    |
| 3266    | 9         | 1.53%   |
| 1067    | 7         | 1.19%   |
| 8400    | 6         | 1.02%   |
| 4266    | 4         | 0.68%   |
| Unknown | 4         | 0.68%   |
| 3733    | 3         | 0.51%   |
| 667     | 3         | 0.51%   |
| 1066    | 2         | 0.34%   |
| 2048    | 1         | 0.17%   |
| 1200    | 1         | 0.17%   |
| 533     | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Canon              | 2         | 50%     |
| NXP Semiconductors | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| NXP Semiconductors Printer-80 | 1         | 25%     |
| Canon TR150 series            | 1         | 25%     |
| Canon PIXMA MG3500 Series     | 1         | 25%     |
| Brother DCP-T220              | 1         | 25%     |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 238       | 23.36%  |
| IMC Networks                           | 147       | 14.43%  |
| Microdia                               | 91        | 8.93%   |
| Realtek Semiconductor                  | 87        | 8.54%   |
| Acer                                   | 85        | 8.34%   |
| Quanta                                 | 63        | 6.18%   |
| Cheng Uei Precision Industry (Foxlink) | 45        | 4.42%   |
| Sunplus Innovation Technology          | 43        | 4.22%   |
| Syntek                                 | 32        | 3.14%   |
| Luxvisions Innotech Limited            | 31        | 3.04%   |
| Apple                                  | 25        | 2.45%   |
| Lite-On Technology                     | 24        | 2.36%   |
| Logitech                               | 19        | 1.86%   |
| Suyin                                  | 13        | 1.28%   |
| Ricoh                                  | 10        | 0.98%   |
| Silicon Motion                         | 9         | 0.88%   |
| Alcor Micro                            | 8         | 0.79%   |
| Samsung Electronics                    | 7         | 0.69%   |
| Primax Electronics                     | 6         | 0.59%   |
| SunplusIT                              | 5         | 0.49%   |
| Sonix Technology                       | 5         | 0.49%   |
| Lenovo                                 | 4         | 0.39%   |
| icSpring                               | 4         | 0.39%   |
| Hewlett-Packard                        | 2         | 0.2%    |
| BKX-210918                             | 2         | 0.2%    |
| Z-Star Microelectronics                | 1         | 0.1%    |
| Y Media                                | 1         | 0.1%    |
| Xiaomi                                 | 1         | 0.1%    |
| USB Camera CS                          | 1         | 0.1%    |
| ShineTech                              | 1         | 0.1%    |
| Razer USA                              | 1         | 0.1%    |
| OPPO Electronics                       | 1         | 0.1%    |
| KYE Systems (Mouse Systems)            | 1         | 0.1%    |
| Intel                                  | 1         | 0.1%    |
| Importek                               | 1         | 0.1%    |
| HTC (High Tech Computer)               | 1         | 0.1%    |
| Google                                 | 1         | 0.1%    |
| Generalplus Technology                 | 1         | 0.1%    |
| ARC International                      | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 89        | 8.67%   |
| Microdia Integrated_Webcam_HD                       | 62        | 6.04%   |
| IMC Networks Integrated Camera                      | 58        | 5.65%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 46        | 4.48%   |
| Realtek Integrated_Webcam_HD                        | 36        | 3.51%   |
| Acer Integrated Camera                              | 28        | 2.73%   |
| Chicony HD WebCam                                   | 25        | 2.44%   |
| Syntek Integrated Camera                            | 23        | 2.24%   |
| Sunplus Integrated_Webcam_HD                        | 17        | 1.66%   |
| Quanta HD User Facing                               | 15        | 1.46%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 15        | 1.46%   |
| Chicony Integrated Camera (1280x720@30)             | 14        | 1.36%   |
| Lite-On Integrated Camera                           | 12        | 1.17%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 11        | 1.07%   |
| Acer HD Webcam                                      | 11        | 1.07%   |
| Quanta HP TrueVision HD Camera                      | 10        | 0.97%   |
| Quanta HP HD Camera                                 | 10        | 0.97%   |
| Chicony HP Wide Vision HD Camera                    | 10        | 0.97%   |
| IMC Networks HD Camera                              | 9         | 0.88%   |
| Chicony HP Truevision HD camera                     | 9         | 0.88%   |
| Chicony HP HD Camera                                | 8         | 0.78%   |
| Acer Lenovo EasyCamera                              | 8         | 0.78%   |
| Samsung Galaxy series, misc. (MTP mode)             | 7         | 0.68%   |
| Chicony USB 2.0 Camera                              | 7         | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 7         | 0.68%   |
| Apple FaceTime HD Camera                            | 7         | 0.68%   |
| Acer HD Camera                                      | 7         | 0.68%   |
| Acer BisonCam, NB Pro                               | 7         | 0.68%   |
| Primax HP HD Webcam [Fixed]                         | 6         | 0.58%   |
| Luxvisions Innotech Limited Integrated Camera       | 6         | 0.58%   |
| Chicony USB2.0 HD UVC WebCam                        | 6         | 0.58%   |
| Chicony USB2.0 Camera                               | 6         | 0.58%   |
| Chicony EasyCamera                                  | 6         | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 6         | 0.58%   |
| Apple iPhone 5/5C/5S/6/SE                           | 6         | 0.58%   |
| Apple Built-in iSight                               | 6         | 0.58%   |
| Syntek EasyCamera                                   | 5         | 0.49%   |
| Sunplus HD WebCam                                   | 5         | 0.49%   |
| Realtek USB Camera                                  | 5         | 0.49%   |
| Realtek Integrated Webcam                           | 5         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 93        | 35.63%  |
| Validity Sensors           | 65        | 24.9%   |
| Shenzhen Goodix Technology | 55        | 21.07%  |
| Elan Microelectronics      | 14        | 5.36%   |
| LighTuning Technology      | 12        | 4.6%    |
| Upek                       | 10        | 3.83%   |
| AuthenTec                  | 7         | 2.68%   |
| Focal-systems.Corp         | 3         | 1.15%   |
| STMicroelectronics         | 1         | 0.38%   |
| Dell                       | 1         | 0.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 42        | 16.09%  |
| Shenzhen Goodix  Fingerprint Device                                        | 36        | 13.79%  |
| Unknown                                                                    | 20        | 7.66%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 17        | 6.51%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 4.98%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 3.83%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 3.83%   |
| Validity Sensors VFS491                                                    | 9         | 3.45%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 3.07%   |
| Elan ELAN:ARM-M4                                                           | 8         | 3.07%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 2.68%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 2.3%    |
| Elan ELAN:Fingerprint                                                      | 6         | 2.3%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.92%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.53%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 1.53%   |
| Synaptics  WBDI                                                            | 3         | 1.15%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.15%   |
| LighTuning EgisTec_ES603                                                   | 3         | 1.15%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 1.15%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.77%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.77%   |
| Synaptics WBDI Device                                                      | 2         | 0.77%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.77%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.77%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.77%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.77%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.38%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.38%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.38%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 1         | 0.38%   |
| AuthenTec AES2810                                                          | 1         | 0.38%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.38%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 43        | 47.78%  |
| Broadcom                   | 32        | 35.56%  |
| Upek                       | 6         | 6.67%   |
| Lenovo                     | 4         | 4.44%   |
| O2 Micro                   | 2         | 2.22%   |
| OmniKey                    | 1         | 1.11%   |
| Gemalto (was Gemplus)      | 1         | 1.11%   |
| Athena Smartcard Solutions | 1         | 1.11%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 42        | 46.67%  |
| Broadcom 58200                                                               | 12        | 13.33%  |
| Broadcom 5880                                                                | 8         | 8.89%   |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 7.78%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 5.56%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.44%   |
| OmniKey CardMan 1021                                                         | 1         | 1.11%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.11%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.11%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.11%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 1.11%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 1.11%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 603       | 54.87%  |
| 1     | 409       | 37.22%  |
| 2     | 74        | 6.73%   |
| 3     | 11        | 1%      |
| 8     | 1         | 0.09%   |
| 4     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 256       | 44.06%  |
| Graphics card         | 128       | 22.03%  |
| Multimedia controller | 60        | 10.33%  |
| Camera                | 34        | 5.85%   |
| Net/wireless          | 29        | 4.99%   |
| Chipcard              | 21        | 3.61%   |
| Bluetooth             | 18        | 3.1%    |
| Card reader           | 10        | 1.72%   |
| Storage               | 8         | 1.38%   |
| Network               | 8         | 1.38%   |
| Net/ethernet          | 4         | 0.69%   |
| Modem                 | 3         | 0.52%   |
| Sound                 | 2         | 0.34%   |

