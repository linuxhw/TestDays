Linux in UAE - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Linux in UAE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UAE/Desktop/README.md) and [notebooks](/Location/UAE/Notebook/README.md).

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

Total: 443

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [47b95e50dc](https://linux-hardware.org/?probe=47b95e50dc) | Jan 02, 2025 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [d5dae00d07](https://linux-hardware.org/?probe=d5dae00d07) | Dec 31, 2024 |
| Trigkey       | Green G4 10                 | Desktop     | [abe47751df](https://linux-hardware.org/?probe=abe47751df) | Dec 19, 2024 |
| HP            | 81C5 MVB                    | Desktop     | [598ed0a0e1](https://linux-hardware.org/?probe=598ed0a0e1) | Dec 19, 2024 |
| HP            | Pavilion Laptop 15-eh3xx... | Notebook    | [2b58ebfebe](https://linux-hardware.org/?probe=2b58ebfebe) | Dec 16, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [64f23b9876](https://linux-hardware.org/?probe=64f23b9876) | Dec 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [b81aceb033](https://linux-hardware.org/?probe=b81aceb033) | Dec 09, 2024 |
| Acer          | TravelMate Spin B118-G2-... | Convertible | [83d6d9d602](https://linux-hardware.org/?probe=83d6d9d602) | Dec 05, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [1496432b74](https://linux-hardware.org/?probe=1496432b74) | Dec 04, 2024 |
| HP            | Pavilion Laptop 15-eh3xx... | Notebook    | [ed79db6569](https://linux-hardware.org/?probe=ed79db6569) | Nov 27, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | Notebook    | [fa8c5128c6](https://linux-hardware.org/?probe=fa8c5128c6) | Nov 25, 2024 |
| Alienware     | 17 R3                       | Notebook    | [d6363a7652](https://linux-hardware.org/?probe=d6363a7652) | Nov 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [01d5857ef9](https://linux-hardware.org/?probe=01d5857ef9) | Nov 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [228a34d78e](https://linux-hardware.org/?probe=228a34d78e) | Nov 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [fc95853dd8](https://linux-hardware.org/?probe=fc95853dd8) | Nov 19, 2024 |
| Apple         | Mac-F2218FC8                | All in one  | [962eef9779](https://linux-hardware.org/?probe=962eef9779) | Nov 12, 2024 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [364e24bd93](https://linux-hardware.org/?probe=364e24bd93) | Nov 12, 2024 |
| Apple         | Mac-F2218FC8                | All in one  | [c9ef441418](https://linux-hardware.org/?probe=c9ef441418) | Nov 11, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [32ae84417a](https://linux-hardware.org/?probe=32ae84417a) | Nov 11, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [a78f5dd558](https://linux-hardware.org/?probe=a78f5dd558) | Nov 11, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [3d3f18fab8](https://linux-hardware.org/?probe=3d3f18fab8) | Nov 06, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9093f85751](https://linux-hardware.org/?probe=9093f85751) | Nov 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [c36723680e](https://linux-hardware.org/?probe=c36723680e) | Nov 04, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [b6327b1771](https://linux-hardware.org/?probe=b6327b1771) | Oct 27, 2024 |
| Alienware     | x17 R2                      | Notebook    | [ead78bb072](https://linux-hardware.org/?probe=ead78bb072) | Oct 24, 2024 |
| Alienware     | x17 R2                      | Notebook    | [9e6b5acd94](https://linux-hardware.org/?probe=9e6b5acd94) | Oct 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [b40269dd83](https://linux-hardware.org/?probe=b40269dd83) | Oct 22, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [c31e6ce172](https://linux-hardware.org/?probe=c31e6ce172) | Oct 20, 2024 |
| MSI           | PRO Z790-S WIFI             | Desktop     | [067881f9af](https://linux-hardware.org/?probe=067881f9af) | Oct 16, 2024 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [5de475d8be](https://linux-hardware.org/?probe=5de475d8be) | Oct 08, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [4d89b5ebcb](https://linux-hardware.org/?probe=4d89b5ebcb) | Oct 08, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [0e2f27c078](https://linux-hardware.org/?probe=0e2f27c078) | Oct 08, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [8253f323a0](https://linux-hardware.org/?probe=8253f323a0) | Oct 07, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [6273853b03](https://linux-hardware.org/?probe=6273853b03) | Oct 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [98801dba2b](https://linux-hardware.org/?probe=98801dba2b) | Oct 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [f72decd0b9](https://linux-hardware.org/?probe=f72decd0b9) | Oct 02, 2024 |
| Dell          | Latitude E5470              | Notebook    | [77e0c3eadc](https://linux-hardware.org/?probe=77e0c3eadc) | Sep 29, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [f267e0be7a](https://linux-hardware.org/?probe=f267e0be7a) | Sep 29, 2024 |
| ASUSTek       | Pro WS WRX90E-SAGE SE       | Desktop     | [31f821497b](https://linux-hardware.org/?probe=31f821497b) | Sep 27, 2024 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [61b7158fe5](https://linux-hardware.org/?probe=61b7158fe5) | Sep 23, 2024 |
| ASUSTek       | X541UJ                      | Notebook    | [cc2936a90c](https://linux-hardware.org/?probe=cc2936a90c) | Sep 22, 2024 |
| Dell          | Latitude E5470              | Notebook    | [b03d8fc762](https://linux-hardware.org/?probe=b03d8fc762) | Sep 15, 2024 |
| Dell          | Latitude E6540              | Notebook    | [1181675540](https://linux-hardware.org/?probe=1181675540) | Sep 14, 2024 |
| Neousys Te... | NVS-6108 Rev. A1            | Server      | [7414e2296d](https://linux-hardware.org/?probe=7414e2296d) | Sep 11, 2024 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [4adc2f2b9b](https://linux-hardware.org/?probe=4adc2f2b9b) | Sep 08, 2024 |
| MSI           | Creator Z16 A11UE           | Notebook    | [146049daab](https://linux-hardware.org/?probe=146049daab) | Sep 01, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [381d377e54](https://linux-hardware.org/?probe=381d377e54) | Aug 30, 2024 |
| HP            | ENVY 15                     | Notebook    | [bb6e6b46f0](https://linux-hardware.org/?probe=bb6e6b46f0) | Aug 29, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | Notebook    | [c62daa5e9a](https://linux-hardware.org/?probe=c62daa5e9a) | Aug 28, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4627f152d7](https://linux-hardware.org/?probe=4627f152d7) | Aug 22, 2024 |
| Lenovo        | ThinkPad T440p 20AWA02M0... | Notebook    | [37adaec870](https://linux-hardware.org/?probe=37adaec870) | Aug 19, 2024 |
| Apple         | MacBookPro14,3              | Notebook    | [9553d16dbc](https://linux-hardware.org/?probe=9553d16dbc) | Aug 18, 2024 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [adbf48a938](https://linux-hardware.org/?probe=adbf48a938) | Aug 14, 2024 |
| Lenovo        | ThinkPad T540p 20BE00AXA... | Notebook    | [c87a2a98f7](https://linux-hardware.org/?probe=c87a2a98f7) | Aug 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [ac95e09d3d](https://linux-hardware.org/?probe=ac95e09d3d) | Aug 13, 2024 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c9c6d489a1](https://linux-hardware.org/?probe=c9c6d489a1) | Aug 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [8908b97b57](https://linux-hardware.org/?probe=8908b97b57) | Aug 05, 2024 |
| Lenovo        | ThinkPad T480 20L6S4KR00    | Notebook    | [124704efaa](https://linux-hardware.org/?probe=124704efaa) | Aug 03, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [1c41f0d25c](https://linux-hardware.org/?probe=1c41f0d25c) | Jul 28, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [8c28e82d86](https://linux-hardware.org/?probe=8c28e82d86) | Jul 28, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [100dfc761e](https://linux-hardware.org/?probe=100dfc761e) | Jul 28, 2024 |
| Lenovo        | ThinkPad T490 20N3SCND00    | Notebook    | [d366cdfef1](https://linux-hardware.org/?probe=d366cdfef1) | Jul 26, 2024 |
| Lenovo        | ThinkPad T490 20N3SCND00    | Notebook    | [5d9ee468e3](https://linux-hardware.org/?probe=5d9ee468e3) | Jul 26, 2024 |
| Lenovo        | C320                        | All in one  | [d03627f2dd](https://linux-hardware.org/?probe=d03627f2dd) | Jul 25, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [b43115fc35](https://linux-hardware.org/?probe=b43115fc35) | Jul 25, 2024 |
| Win Elemen... | S500+                       | Desktop     | [3aa986ddc3](https://linux-hardware.org/?probe=3aa986ddc3) | Jul 24, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d322eab289](https://linux-hardware.org/?probe=d322eab289) | Jul 23, 2024 |
| Pegatron      | 2AB6                        | Desktop     | [0671cbc932](https://linux-hardware.org/?probe=0671cbc932) | Jul 14, 2024 |
| Lenovo        | C320                        | All in one  | [5a7c44d636](https://linux-hardware.org/?probe=5a7c44d636) | Jul 13, 2024 |
| ASUSTek       | Rampage IV BLACK EDITION    | Desktop     | [0456096b3c](https://linux-hardware.org/?probe=0456096b3c) | Jul 13, 2024 |
| Unknown       | OnePlus 6                   | Soc         | [3af4c7e44b](https://linux-hardware.org/?probe=3af4c7e44b) | Jul 13, 2024 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [e7b913d07d](https://linux-hardware.org/?probe=e7b913d07d) | Jul 08, 2024 |
| Dell          | 0T656F A01                  | Desktop     | [ecdd487673](https://linux-hardware.org/?probe=ecdd487673) | Jul 05, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [43eb169014](https://linux-hardware.org/?probe=43eb169014) | Jul 02, 2024 |
| Samsung       | 950QDB                      | Convertible | [9be770e082](https://linux-hardware.org/?probe=9be770e082) | Jun 28, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [ac4cddaec8](https://linux-hardware.org/?probe=ac4cddaec8) | Jun 22, 2024 |
| ASUSTek       | ROG Strix G512LW_2nd2LW     | Notebook    | [c29d8bf39f](https://linux-hardware.org/?probe=c29d8bf39f) | Jun 19, 2024 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [3e62aea70e](https://linux-hardware.org/?probe=3e62aea70e) | Jun 17, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3595b48d6f](https://linux-hardware.org/?probe=3595b48d6f) | Jun 17, 2024 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [4a0a5de54c](https://linux-hardware.org/?probe=4a0a5de54c) | Jun 15, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [9b30ebc629](https://linux-hardware.org/?probe=9b30ebc629) | Jun 15, 2024 |
| Dell          | Latitude E5570              | Notebook    | [aa3048d0b3](https://linux-hardware.org/?probe=aa3048d0b3) | Jun 13, 2024 |
| Dell          | XPS L501X                   | Notebook    | [396ec3b48f](https://linux-hardware.org/?probe=396ec3b48f) | Jun 13, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [2ae5830f06](https://linux-hardware.org/?probe=2ae5830f06) | Jun 05, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [12de7f6310](https://linux-hardware.org/?probe=12de7f6310) | Jun 04, 2024 |
| SZMZ          | B75-MS V1.0                 | Desktop     | [8465c076a5](https://linux-hardware.org/?probe=8465c076a5) | Jun 02, 2024 |
| Lenovo        | ThinkPad T460 20FMS77B0D    | Notebook    | [48b925a3b1](https://linux-hardware.org/?probe=48b925a3b1) | Jun 02, 2024 |
| Dell          | Latitude E6540              | Notebook    | [64a38f3167](https://linux-hardware.org/?probe=64a38f3167) | Jun 01, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [ceb3eb9275](https://linux-hardware.org/?probe=ceb3eb9275) | May 31, 2024 |
| Dell          | XPS 15 9520                 | Notebook    | [dec3f4b80d](https://linux-hardware.org/?probe=dec3f4b80d) | May 30, 2024 |
| Lenovo        | ThinkPad X240 20AMS39F0E    | Notebook    | [8c697fb84c](https://linux-hardware.org/?probe=8c697fb84c) | May 28, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [7b942d00c3](https://linux-hardware.org/?probe=7b942d00c3) | May 26, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [4e8bf013a2](https://linux-hardware.org/?probe=4e8bf013a2) | May 26, 2024 |
| Dell          | Latitude E6540              | Notebook    | [b74e867eb2](https://linux-hardware.org/?probe=b74e867eb2) | May 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9d438abd6e](https://linux-hardware.org/?probe=9d438abd6e) | May 24, 2024 |
| HP            | ProBook 430 G4              | Notebook    | [986474f731](https://linux-hardware.org/?probe=986474f731) | May 21, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [3387f387e2](https://linux-hardware.org/?probe=3387f387e2) | May 19, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [b7158b3151](https://linux-hardware.org/?probe=b7158b3151) | May 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [5ecbd0cbbc](https://linux-hardware.org/?probe=5ecbd0cbbc) | May 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [fac2c941b9](https://linux-hardware.org/?probe=fac2c941b9) | May 17, 2024 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [df01e00ae4](https://linux-hardware.org/?probe=df01e00ae4) | May 17, 2024 |
| Nvidia        | Tegra                       | Soc         | [31fafc00d1](https://linux-hardware.org/?probe=31fafc00d1) | May 15, 2024 |
| Nvidia        | Tegra                       | Soc         | [13eace5813](https://linux-hardware.org/?probe=13eace5813) | May 15, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [375e987cd3](https://linux-hardware.org/?probe=375e987cd3) | May 14, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [815681c523](https://linux-hardware.org/?probe=815681c523) | May 14, 2024 |
| Dell          | XPS 15 9520                 | Notebook    | [ef8de4b0d9](https://linux-hardware.org/?probe=ef8de4b0d9) | May 09, 2024 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [e475e36ab0](https://linux-hardware.org/?probe=e475e36ab0) | May 06, 2024 |
| HP            | HPPavilionLaptop15-eh0xx... | Notebook    | [2d309668c0](https://linux-hardware.org/?probe=2d309668c0) | May 04, 2024 |
| AZW           | SER V10                     | Mini pc     | [3c76958b8b](https://linux-hardware.org/?probe=3c76958b8b) | Apr 24, 2024 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [c12789125b](https://linux-hardware.org/?probe=c12789125b) | Apr 24, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [ddb98658ed](https://linux-hardware.org/?probe=ddb98658ed) | Apr 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [3f58323ccb](https://linux-hardware.org/?probe=3f58323ccb) | Apr 02, 2024 |
| Lenovo        | ThinkPad T480s 20L8S07A0... | Notebook    | [b136c2a573](https://linux-hardware.org/?probe=b136c2a573) | Mar 26, 2024 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [16c311a8b2](https://linux-hardware.org/?probe=16c311a8b2) | Mar 13, 2024 |
| ASRock        | B660M-HDV                   | Desktop     | [427836e454](https://linux-hardware.org/?probe=427836e454) | Mar 02, 2024 |
| ASRock        | B660M-HDV                   | Desktop     | [68b50166f3](https://linux-hardware.org/?probe=68b50166f3) | Mar 02, 2024 |
| HUAWEI        | DRR-WXX                     | Tablet      | [8797322d65](https://linux-hardware.org/?probe=8797322d65) | Mar 02, 2024 |
| Intel         | NUC11TNBi7 M11895-403       | Mini pc     | [6bc129fa19](https://linux-hardware.org/?probe=6bc129fa19) | Feb 27, 2024 |
| Lenovo        | ThinkPad X240 20AMS39F0E    | Notebook    | [28e62d76d4](https://linux-hardware.org/?probe=28e62d76d4) | Feb 25, 2024 |
| Lenovo        | ThinkPad P50 20EN002WAD     | Notebook    | [19f5064a8e](https://linux-hardware.org/?probe=19f5064a8e) | Feb 24, 2024 |
| Lenovo        | ThinkPad P50 20EN002WAD     | Notebook    | [d6e9ae9de6](https://linux-hardware.org/?probe=d6e9ae9de6) | Feb 24, 2024 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [65d3a89e4e](https://linux-hardware.org/?probe=65d3a89e4e) | Feb 23, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [82828b68cb](https://linux-hardware.org/?probe=82828b68cb) | Feb 20, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [813c2cba09](https://linux-hardware.org/?probe=813c2cba09) | Feb 17, 2024 |
| Lenovo        | ThinkPad E14 20RA007TUE     | Notebook    | [84059a6773](https://linux-hardware.org/?probe=84059a6773) | Feb 16, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [95e1c6903c](https://linux-hardware.org/?probe=95e1c6903c) | Feb 16, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [6637baf0a5](https://linux-hardware.org/?probe=6637baf0a5) | Feb 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [4bfb818f2f](https://linux-hardware.org/?probe=4bfb818f2f) | Feb 12, 2024 |
| Lenovo        | ThinkPad E570 20H50067AD    | Notebook    | [a51f602de8](https://linux-hardware.org/?probe=a51f602de8) | Feb 11, 2024 |
| Lenovo        | ThinkPad E570 20H50067AD    | Notebook    | [2752e93d4b](https://linux-hardware.org/?probe=2752e93d4b) | Feb 08, 2024 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | Notebook    | [4c292546e2](https://linux-hardware.org/?probe=4c292546e2) | Jan 27, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [3de8476f0b](https://linux-hardware.org/?probe=3de8476f0b) | Jan 21, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [3373e374fb](https://linux-hardware.org/?probe=3373e374fb) | Jan 14, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [3ea676a743](https://linux-hardware.org/?probe=3ea676a743) | Jan 14, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [e3c1908003](https://linux-hardware.org/?probe=e3c1908003) | Jan 13, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [382558433d](https://linux-hardware.org/?probe=382558433d) | Jan 11, 2024 |
| Apple         | MacBookAir5,1               | Notebook    | [26c37b7e05](https://linux-hardware.org/?probe=26c37b7e05) | Jan 02, 2024 |
| Apple         | MacBookAir5,1               | Notebook    | [5c7029f981](https://linux-hardware.org/?probe=5c7029f981) | Dec 23, 2023 |
| Lenovo        | ThinkPad T440p 20AWA02M0... | Notebook    | [c977bbe2c4](https://linux-hardware.org/?probe=c977bbe2c4) | Dec 03, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [91df918363](https://linux-hardware.org/?probe=91df918363) | Nov 28, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [e22c72e9d4](https://linux-hardware.org/?probe=e22c72e9d4) | Nov 26, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [dfa296fd96](https://linux-hardware.org/?probe=dfa296fd96) | Nov 25, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [9218c25c70](https://linux-hardware.org/?probe=9218c25c70) | Nov 21, 2023 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [340f007a69](https://linux-hardware.org/?probe=340f007a69) | Nov 14, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [9c08dba7b5](https://linux-hardware.org/?probe=9c08dba7b5) | Nov 13, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [e384b513f0](https://linux-hardware.org/?probe=e384b513f0) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [e7f5173a86](https://linux-hardware.org/?probe=e7f5173a86) | Nov 12, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [0d5d11180c](https://linux-hardware.org/?probe=0d5d11180c) | Nov 07, 2023 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [600445b726](https://linux-hardware.org/?probe=600445b726) | Nov 05, 2023 |
| HP            | HPPavilionLaptop15-eh0xx... | Notebook    | [436064bfba](https://linux-hardware.org/?probe=436064bfba) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [92ed6d25c3](https://linux-hardware.org/?probe=92ed6d25c3) | Nov 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [f4cbcd5ba1](https://linux-hardware.org/?probe=f4cbcd5ba1) | Nov 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [34a347877f](https://linux-hardware.org/?probe=34a347877f) | Nov 05, 2023 |
| HP            | 1589                        | Desktop     | [61922d4b43](https://linux-hardware.org/?probe=61922d4b43) | Nov 05, 2023 |
| Gigabyte      | A5 X1                       | Notebook    | [981be88a61](https://linux-hardware.org/?probe=981be88a61) | Oct 30, 2023 |
| Lenovo        | ThinkPad E490 20N80006UE    | Notebook    | [4bb8e497d3](https://linux-hardware.org/?probe=4bb8e497d3) | Oct 28, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [2937846c1b](https://linux-hardware.org/?probe=2937846c1b) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [8678e7aace](https://linux-hardware.org/?probe=8678e7aace) | Oct 08, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [e6e1c9bac9](https://linux-hardware.org/?probe=e6e1c9bac9) | Sep 30, 2023 |
| I-Life Dig... | ZED AIR PRO                 | Notebook    | [7cb30879f6](https://linux-hardware.org/?probe=7cb30879f6) | Sep 28, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [64a85b8eb3](https://linux-hardware.org/?probe=64a85b8eb3) | Sep 28, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [17bbb23241](https://linux-hardware.org/?probe=17bbb23241) | Sep 22, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [89bf6e640b](https://linux-hardware.org/?probe=89bf6e640b) | Sep 12, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [7f0de230c8](https://linux-hardware.org/?probe=7f0de230c8) | Sep 12, 2023 |
| Google        | Lick                        | Notebook    | [11aec9d97c](https://linux-hardware.org/?probe=11aec9d97c) | Sep 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [53b237137d](https://linux-hardware.org/?probe=53b237137d) | Aug 30, 2023 |
| HP            | 8446                        | All in one  | [9d508328d5](https://linux-hardware.org/?probe=9d508328d5) | Aug 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [0585143fdc](https://linux-hardware.org/?probe=0585143fdc) | Aug 19, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [de0ce7c424](https://linux-hardware.org/?probe=de0ce7c424) | Aug 06, 2023 |
| Dell          | Latitude 3420               | Notebook    | [cdecb64c4a](https://linux-hardware.org/?probe=cdecb64c4a) | Aug 04, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [c741db51a0](https://linux-hardware.org/?probe=c741db51a0) | Aug 03, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [18eceddda0](https://linux-hardware.org/?probe=18eceddda0) | Jul 26, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [3466d6ab26](https://linux-hardware.org/?probe=3466d6ab26) | Jul 23, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [94df828438](https://linux-hardware.org/?probe=94df828438) | Jul 22, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3539141ba9](https://linux-hardware.org/?probe=3539141ba9) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [0c592730d7](https://linux-hardware.org/?probe=0c592730d7) | Jul 16, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [9b3b477b44](https://linux-hardware.org/?probe=9b3b477b44) | Jul 11, 2023 |
| ASRock        | E3C224D4I-14S               | Desktop     | [bd2d074d07](https://linux-hardware.org/?probe=bd2d074d07) | Jul 09, 2023 |
| Dell          | G15 Special Edition 5521    | Notebook    | [42890cd134](https://linux-hardware.org/?probe=42890cd134) | Jul 04, 2023 |
| Dell          | G15 Special Edition 5521    | Notebook    | [8a3a0f9375](https://linux-hardware.org/?probe=8a3a0f9375) | Jul 04, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [884a5ecd03](https://linux-hardware.org/?probe=884a5ecd03) | Jun 28, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [53ef3811fc](https://linux-hardware.org/?probe=53ef3811fc) | Jun 21, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [7dd15a9fa4](https://linux-hardware.org/?probe=7dd15a9fa4) | Jun 19, 2023 |
| Intel         | NUC9VXQNB K47179-402        | Mini pc     | [f3c7611dd0](https://linux-hardware.org/?probe=f3c7611dd0) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [0c81d929ca](https://linux-hardware.org/?probe=0c81d929ca) | Jun 04, 2023 |
| HP            | 0B54h D                     | Desktop     | [f9634b51b9](https://linux-hardware.org/?probe=f9634b51b9) | May 28, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [589112cb44](https://linux-hardware.org/?probe=589112cb44) | May 25, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [2ae74516a9](https://linux-hardware.org/?probe=2ae74516a9) | May 24, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [cbd7b1dcc7](https://linux-hardware.org/?probe=cbd7b1dcc7) | May 24, 2023 |
| Lenovo        | ThinkPad T490 20N2004JAD    | Notebook    | [c765eed46d](https://linux-hardware.org/?probe=c765eed46d) | May 16, 2023 |
| Toshiba       | Satellite L850-B434         | Notebook    | [54e6cd2fc6](https://linux-hardware.org/?probe=54e6cd2fc6) | May 13, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [89747b6213](https://linux-hardware.org/?probe=89747b6213) | May 12, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [0a639ba55d](https://linux-hardware.org/?probe=0a639ba55d) | May 08, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [aabb19e388](https://linux-hardware.org/?probe=aabb19e388) | May 06, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [b9ef1562db](https://linux-hardware.org/?probe=b9ef1562db) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [02fa09745c](https://linux-hardware.org/?probe=02fa09745c) | May 05, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [856494ea85](https://linux-hardware.org/?probe=856494ea85) | May 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [c6e5e310b9](https://linux-hardware.org/?probe=c6e5e310b9) | May 02, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [1704454cdb](https://linux-hardware.org/?probe=1704454cdb) | May 02, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [d2f8737b9d](https://linux-hardware.org/?probe=d2f8737b9d) | May 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [78a3abdc19](https://linux-hardware.org/?probe=78a3abdc19) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [59c225df6e](https://linux-hardware.org/?probe=59c225df6e) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6e2da1e766](https://linux-hardware.org/?probe=6e2da1e766) | Apr 21, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [a0cf4fd00d](https://linux-hardware.org/?probe=a0cf4fd00d) | Apr 19, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7ce26d7fd9](https://linux-hardware.org/?probe=7ce26d7fd9) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| HP            | 15-dc1018ur                 | Notebook    | [7df35a90ad](https://linux-hardware.org/?probe=7df35a90ad) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [a7b2caaba8](https://linux-hardware.org/?probe=a7b2caaba8) | Apr 16, 2023 |
| HP            | Pavilion 15                 | Notebook    | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [59db7a4f11](https://linux-hardware.org/?probe=59db7a4f11) | Apr 10, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [125884d17a](https://linux-hardware.org/?probe=125884d17a) | Apr 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1U20... | Notebook    | [99ea485cee](https://linux-hardware.org/?probe=99ea485cee) | Mar 27, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [83fb0eaf6e](https://linux-hardware.org/?probe=83fb0eaf6e) | Mar 26, 2023 |
| ASUSTek       | Q551LN                      | Notebook    | [3385f39150](https://linux-hardware.org/?probe=3385f39150) | Mar 26, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [1a46276700](https://linux-hardware.org/?probe=1a46276700) | Mar 05, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [2a8830034a](https://linux-hardware.org/?probe=2a8830034a) | Feb 26, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [452bd46c01](https://linux-hardware.org/?probe=452bd46c01) | Feb 22, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [fe78ef8424](https://linux-hardware.org/?probe=fe78ef8424) | Feb 22, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [83bef528a7](https://linux-hardware.org/?probe=83bef528a7) | Feb 19, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [64c385ee36](https://linux-hardware.org/?probe=64c385ee36) | Feb 16, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [54f7f241bf](https://linux-hardware.org/?probe=54f7f241bf) | Feb 15, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [8fc284c3b5](https://linux-hardware.org/?probe=8fc284c3b5) | Feb 15, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [3b09c5ed9e](https://linux-hardware.org/?probe=3b09c5ed9e) | Feb 04, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [be3ef90301](https://linux-hardware.org/?probe=be3ef90301) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9fb41ee5bc](https://linux-hardware.org/?probe=9fb41ee5bc) | Feb 01, 2023 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [a64ae29757](https://linux-hardware.org/?probe=a64ae29757) | Jan 31, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [f308688189](https://linux-hardware.org/?probe=f308688189) | Jan 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [83d050bdbe](https://linux-hardware.org/?probe=83d050bdbe) | Jan 25, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [9a930173a0](https://linux-hardware.org/?probe=9a930173a0) | Jan 24, 2023 |
| HP            | 1998                        | Desktop     | [5fcedbdb28](https://linux-hardware.org/?probe=5fcedbdb28) | Jan 22, 2023 |
| Dell          | G5 5587                     | Notebook    | [96ca22c550](https://linux-hardware.org/?probe=96ca22c550) | Jan 21, 2023 |
| Dell          | G5 5587                     | Notebook    | [a070a8ba69](https://linux-hardware.org/?probe=a070a8ba69) | Jan 21, 2023 |
| Acer          | Aspire E5-471P              | Notebook    | [c50e807e64](https://linux-hardware.org/?probe=c50e807e64) | Jan 12, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [6d3966411f](https://linux-hardware.org/?probe=6d3966411f) | Jan 09, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [1405e2a7c8](https://linux-hardware.org/?probe=1405e2a7c8) | Jan 09, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [6206409322](https://linux-hardware.org/?probe=6206409322) | Jan 08, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [eab8778810](https://linux-hardware.org/?probe=eab8778810) | Dec 30, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [89c0ffe36d](https://linux-hardware.org/?probe=89c0ffe36d) | Dec 29, 2022 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [d27a1b703b](https://linux-hardware.org/?probe=d27a1b703b) | Dec 26, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [f048f7fcdb](https://linux-hardware.org/?probe=f048f7fcdb) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [9f1097843c](https://linux-hardware.org/?probe=9f1097843c) | Dec 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [fae62b5114](https://linux-hardware.org/?probe=fae62b5114) | Dec 11, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [c74d870263](https://linux-hardware.org/?probe=c74d870263) | Dec 04, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| Dell          | 0F9N89 A00                  | Server      | [3a917876ba](https://linux-hardware.org/?probe=3a917876ba) | Nov 23, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [79119cca36](https://linux-hardware.org/?probe=79119cca36) | Nov 19, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [1b30c252bb](https://linux-hardware.org/?probe=1b30c252bb) | Nov 19, 2022 |
| HP            | 0AECh D                     | Desktop     | [9e2ddc5dbd](https://linux-hardware.org/?probe=9e2ddc5dbd) | Nov 18, 2022 |
| HP            | 0AECh D                     | Desktop     | [95b36ddda4](https://linux-hardware.org/?probe=95b36ddda4) | Nov 18, 2022 |
| HP            | 1495                        | Desktop     | [c4535d8ea8](https://linux-hardware.org/?probe=c4535d8ea8) | Nov 15, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [faf014b2e6](https://linux-hardware.org/?probe=faf014b2e6) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d9af542480](https://linux-hardware.org/?probe=d9af542480) | Nov 08, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [7d3eac2c7d](https://linux-hardware.org/?probe=7d3eac2c7d) | Nov 05, 2022 |
| Gigabyte      | Q270M-D3H                   | Desktop     | [46874cc0a1](https://linux-hardware.org/?probe=46874cc0a1) | Nov 02, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | Notebook    | [910b452558](https://linux-hardware.org/?probe=910b452558) | Oct 30, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [7406489511](https://linux-hardware.org/?probe=7406489511) | Oct 21, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [e8e0acd06e](https://linux-hardware.org/?probe=e8e0acd06e) | Oct 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [fdab72c478](https://linux-hardware.org/?probe=fdab72c478) | Oct 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [b1590cf8fa](https://linux-hardware.org/?probe=b1590cf8fa) | Oct 03, 2022 |
| Intel         | NUC10i3FNB K61362-306       | Mini pc     | [e8130be6f2](https://linux-hardware.org/?probe=e8130be6f2) | Oct 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [472668e67b](https://linux-hardware.org/?probe=472668e67b) | Sep 12, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [512c793b51](https://linux-hardware.org/?probe=512c793b51) | Sep 06, 2022 |
| Lenovo        | ThinkPad T61 76653JG        | Notebook    | [0fae1da16b](https://linux-hardware.org/?probe=0fae1da16b) | Aug 02, 2022 |
| Lenovo        | 81FV                        | Notebook    | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PA... | Notebook    | [de71ab8780](https://linux-hardware.org/?probe=de71ab8780) | Jul 21, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [b847a4a45d](https://linux-hardware.org/?probe=b847a4a45d) | Jul 03, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [0aa196cd0c](https://linux-hardware.org/?probe=0aa196cd0c) | Jul 03, 2022 |
| Dell          | 0MGK50 A02                  | Desktop     | [eca7a31c46](https://linux-hardware.org/?probe=eca7a31c46) | Jun 23, 2022 |
| Dell          | 0MGK50 A02                  | Desktop     | [134bf128f7](https://linux-hardware.org/?probe=134bf128f7) | Jun 23, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [0fbbdf9197](https://linux-hardware.org/?probe=0fbbdf9197) | Jun 07, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [ad2442631e](https://linux-hardware.org/?probe=ad2442631e) | May 28, 2022 |
| HP            | 8446                        | All in one  | [821752cb21](https://linux-hardware.org/?probe=821752cb21) | May 11, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [6c498d2ce5](https://linux-hardware.org/?probe=6c498d2ce5) | Apr 29, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS4... | Notebook    | [28c774c6de](https://linux-hardware.org/?probe=28c774c6de) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [718b671125](https://linux-hardware.org/?probe=718b671125) | Apr 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [5e0763131c](https://linux-hardware.org/?probe=5e0763131c) | Mar 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [8dda7f6478](https://linux-hardware.org/?probe=8dda7f6478) | Mar 06, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4edc1d31b5](https://linux-hardware.org/?probe=4edc1d31b5) | Mar 06, 2022 |
| Google        | Terra                       | Notebook    | [54163369b2](https://linux-hardware.org/?probe=54163369b2) | Feb 23, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [f014fcba4f](https://linux-hardware.org/?probe=f014fcba4f) | Feb 14, 2022 |
| Dell          | Latitude E6230              | Notebook    | [a8aeb155b0](https://linux-hardware.org/?probe=a8aeb155b0) | Feb 10, 2022 |
| Biostar       | TZ77XE4                     | Desktop     | [081c3be70e](https://linux-hardware.org/?probe=081c3be70e) | Feb 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [8aafebe07c](https://linux-hardware.org/?probe=8aafebe07c) | Feb 03, 2022 |
| Dell          | Latitude E5440              | Notebook    | [ebbb8ee138](https://linux-hardware.org/?probe=ebbb8ee138) | Jan 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S3FV0... | Notebook    | [78080db667](https://linux-hardware.org/?probe=78080db667) | Jan 13, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4670daefab](https://linux-hardware.org/?probe=4670daefab) | Jan 04, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [c36553e3a3](https://linux-hardware.org/?probe=c36553e3a3) | Dec 27, 2021 |
| Google        | Akemi                       | Notebook    | [aaf0a3e10e](https://linux-hardware.org/?probe=aaf0a3e10e) | Dec 20, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [927497310e](https://linux-hardware.org/?probe=927497310e) | Nov 16, 2021 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [7b77d5463d](https://linux-hardware.org/?probe=7b77d5463d) | Nov 13, 2021 |
| win elemen... | MoreFine S500+              | Notebook    | [ace08cf199](https://linux-hardware.org/?probe=ace08cf199) | Nov 11, 2021 |
| win elemen... | MoreFine S500+              | Notebook    | [0e31d4b6fa](https://linux-hardware.org/?probe=0e31d4b6fa) | Nov 11, 2021 |
| MSI           | PS63 Modern 8RD             | Notebook    | [519048dea2](https://linux-hardware.org/?probe=519048dea2) | Nov 01, 2021 |
| MSI           | PS63 Modern 8RD             | Notebook    | [6d3cd2f117](https://linux-hardware.org/?probe=6d3cd2f117) | Nov 01, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [24d1bd52cc](https://linux-hardware.org/?probe=24d1bd52cc) | Oct 28, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [41ff21e8e8](https://linux-hardware.org/?probe=41ff21e8e8) | Oct 06, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [6654adaf99](https://linux-hardware.org/?probe=6654adaf99) | Oct 04, 2021 |
| HP            | ProBook 6475b               | Notebook    | [9d60bf5397](https://linux-hardware.org/?probe=9d60bf5397) | Oct 02, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [eccb23bda1](https://linux-hardware.org/?probe=eccb23bda1) | Sep 24, 2021 |
| Apple         | MacBook9,1                  | Notebook    | [888ca9b5de](https://linux-hardware.org/?probe=888ca9b5de) | Sep 04, 2021 |
| Apple         | MacBook9,1                  | Notebook    | [69119d1952](https://linux-hardware.org/?probe=69119d1952) | Sep 04, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [e1f91ca6de](https://linux-hardware.org/?probe=e1f91ca6de) | Sep 02, 2021 |
| HP            | 8446                        | All in one  | [430c02980a](https://linux-hardware.org/?probe=430c02980a) | Aug 13, 2021 |
| Sony          | VGN-NS10J_S                 | Notebook    | [31d1e0e91d](https://linux-hardware.org/?probe=31d1e0e91d) | Aug 12, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [e25c41c312](https://linux-hardware.org/?probe=e25c41c312) | Jul 03, 2021 |
| LG Electro... | C500-G.AEF5BE1              | Notebook    | [b78f4cd34d](https://linux-hardware.org/?probe=b78f4cd34d) | Jun 14, 2021 |
| Toshiba       | Satellite C850-A966         | Notebook    | [391d22d993](https://linux-hardware.org/?probe=391d22d993) | Jun 02, 2021 |
| Sony          | SVE14A25CAB                 | Notebook    | [78ddb916b5](https://linux-hardware.org/?probe=78ddb916b5) | May 30, 2021 |
| Sony          | SVE14A25CAB                 | Notebook    | [0a2c5cf1cd](https://linux-hardware.org/?probe=0a2c5cf1cd) | May 30, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5707e7ae37](https://linux-hardware.org/?probe=5707e7ae37) | May 28, 2021 |
| Dell          | OptiPlex 980                | Desktop     | [1fe360b027](https://linux-hardware.org/?probe=1fe360b027) | May 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [66cc8bd4a5](https://linux-hardware.org/?probe=66cc8bd4a5) | May 19, 2021 |
| Dell          | G5 5587                     | Notebook    | [2d2cf67a2d](https://linux-hardware.org/?probe=2d2cf67a2d) | May 08, 2021 |
| Dell          | Latitude E6510              | Notebook    | [06d38294ab](https://linux-hardware.org/?probe=06d38294ab) | May 03, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [e3b22a36fb](https://linux-hardware.org/?probe=e3b22a36fb) | Apr 22, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [f5715022b7](https://linux-hardware.org/?probe=f5715022b7) | Apr 22, 2021 |
| HP            | 8446                        | All in one  | [a52aa6f1bd](https://linux-hardware.org/?probe=a52aa6f1bd) | Mar 10, 2021 |
| Acer          | Aspire 5755G                | Notebook    | [6b82d5c050](https://linux-hardware.org/?probe=6b82d5c050) | Mar 07, 2021 |
| Acer          | Aspire 5755G                | Notebook    | [227244211b](https://linux-hardware.org/?probe=227244211b) | Mar 07, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [3c9d39abce](https://linux-hardware.org/?probe=3c9d39abce) | Mar 06, 2021 |
| Lenovo        | ThinkPad X230 2325DV8       | Notebook    | [11d5145d10](https://linux-hardware.org/?probe=11d5145d10) | Feb 12, 2021 |
| HP            | Elite Dragonfly             | Convertible | [87b2f82af5](https://linux-hardware.org/?probe=87b2f82af5) | Feb 01, 2021 |
| HP            | Elite Dragonfly             | Convertible | [6e1ef1920c](https://linux-hardware.org/?probe=6e1ef1920c) | Jan 31, 2021 |
| HP            | Elite Dragonfly             | Convertible | [215ff8ccba](https://linux-hardware.org/?probe=215ff8ccba) | Jan 31, 2021 |
| HP            | Pavilion dv6                | Notebook    | [317b81878c](https://linux-hardware.org/?probe=317b81878c) | Jan 27, 2021 |
| Lenovo        | 3098 NOK                    | Desktop     | [d0ccf5266d](https://linux-hardware.org/?probe=d0ccf5266d) | Jan 27, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [3d8ea2b061](https://linux-hardware.org/?probe=3d8ea2b061) | Jan 27, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [a3c15a6f74](https://linux-hardware.org/?probe=a3c15a6f74) | Jan 18, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [58bf01b1e7](https://linux-hardware.org/?probe=58bf01b1e7) | Jan 18, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [2e84869a9a](https://linux-hardware.org/?probe=2e84869a9a) | Jan 11, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1c5ef3cfe4](https://linux-hardware.org/?probe=1c5ef3cfe4) | Jan 11, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d071e37713](https://linux-hardware.org/?probe=d071e37713) | Jan 10, 2021 |
| HP            | 8446                        | All in one  | [a07d483bab](https://linux-hardware.org/?probe=a07d483bab) | Jan 07, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [6a02570e23](https://linux-hardware.org/?probe=6a02570e23) | Jan 03, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [092666f171](https://linux-hardware.org/?probe=092666f171) | Dec 31, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [93e3d5b038](https://linux-hardware.org/?probe=93e3d5b038) | Dec 25, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [d24a3c768e](https://linux-hardware.org/?probe=d24a3c768e) | Dec 24, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cb1c064071](https://linux-hardware.org/?probe=cb1c064071) | Dec 16, 2020 |
| Dell          | Latitude E6410              | Notebook    | [a2a46d21e9](https://linux-hardware.org/?probe=a2a46d21e9) | Dec 15, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [e2816ed19c](https://linux-hardware.org/?probe=e2816ed19c) | Nov 27, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [12a3adede5](https://linux-hardware.org/?probe=12a3adede5) | Nov 06, 2020 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [91e0e6c6bc](https://linux-hardware.org/?probe=91e0e6c6bc) | Nov 04, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6f0218a447](https://linux-hardware.org/?probe=6f0218a447) | Oct 28, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7ad824c6f9](https://linux-hardware.org/?probe=7ad824c6f9) | Oct 26, 2020 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [54531ec292](https://linux-hardware.org/?probe=54531ec292) | Oct 21, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f372424ac5](https://linux-hardware.org/?probe=f372424ac5) | Oct 18, 2020 |
| Intel         | D865PERL AAC27648-207       | Desktop     | [387171a87d](https://linux-hardware.org/?probe=387171a87d) | Oct 08, 2020 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [b1cd303933](https://linux-hardware.org/?probe=b1cd303933) | Oct 08, 2020 |
| HP            | 2AA2                        | Desktop     | [ceebc6a90b](https://linux-hardware.org/?probe=ceebc6a90b) | Oct 04, 2020 |
| Intel         | D865PERL AAC27648-207       | Desktop     | [7d3672caff](https://linux-hardware.org/?probe=7d3672caff) | Oct 04, 2020 |
| Intel         | D865PERL AAC27648-207       | Desktop     | [2a18eaa0ab](https://linux-hardware.org/?probe=2a18eaa0ab) | Oct 04, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [f9f212a509](https://linux-hardware.org/?probe=f9f212a509) | Oct 01, 2020 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [ab392f30cb](https://linux-hardware.org/?probe=ab392f30cb) | Sep 30, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [42c8711bea](https://linux-hardware.org/?probe=42c8711bea) | Sep 29, 2020 |
| Acer          | ChiefRiver Platform         | Notebook    | [23e2162b8e](https://linux-hardware.org/?probe=23e2162b8e) | Sep 20, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [22369a8f3c](https://linux-hardware.org/?probe=22369a8f3c) | Sep 20, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [d026d40366](https://linux-hardware.org/?probe=d026d40366) | Sep 17, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [18778a34f2](https://linux-hardware.org/?probe=18778a34f2) | Sep 10, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [ff1f32c975](https://linux-hardware.org/?probe=ff1f32c975) | Sep 10, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [94cbf8e66c](https://linux-hardware.org/?probe=94cbf8e66c) | Sep 10, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a25d4e5346](https://linux-hardware.org/?probe=a25d4e5346) | Sep 09, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c4c1a329af](https://linux-hardware.org/?probe=c4c1a329af) | Sep 06, 2020 |
| Dell          | Inspiron 5537               | Notebook    | [4ddf924081](https://linux-hardware.org/?probe=4ddf924081) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | Notebook    | [23a0e05047](https://linux-hardware.org/?probe=23a0e05047) | Sep 05, 2020 |
| Dell          | Latitude E6540              | Notebook    | [9abf14d168](https://linux-hardware.org/?probe=9abf14d168) | Aug 31, 2020 |
| HP            | 8446                        | All in one  | [08b9600cae](https://linux-hardware.org/?probe=08b9600cae) | Aug 29, 2020 |
| Dell          | Precision 5540              | Notebook    | [76f1cfa736](https://linux-hardware.org/?probe=76f1cfa736) | Aug 23, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [19af27b191](https://linux-hardware.org/?probe=19af27b191) | Aug 20, 2020 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [f555bad747](https://linux-hardware.org/?probe=f555bad747) | Aug 14, 2020 |
| I-Life Dig... | ZED AIR                     | Notebook    | [b40d7e9c7c](https://linux-hardware.org/?probe=b40d7e9c7c) | Aug 10, 2020 |
| I-Life Dig... | ZED AIR                     | Notebook    | [5662aa186c](https://linux-hardware.org/?probe=5662aa186c) | Aug 10, 2020 |
| HP            | 2AA2                        | Desktop     | [f20932c5c3](https://linux-hardware.org/?probe=f20932c5c3) | Aug 09, 2020 |
| Lenovo        | ThinkPad L480 20LS0012AD    | Notebook    | [81d46e4c4a](https://linux-hardware.org/?probe=81d46e4c4a) | Aug 02, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [670cc8a66c](https://linux-hardware.org/?probe=670cc8a66c) | Jul 26, 2020 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [aea3470496](https://linux-hardware.org/?probe=aea3470496) | Jul 21, 2020 |
| HP            | 2AA2                        | Desktop     | [424f0397a7](https://linux-hardware.org/?probe=424f0397a7) | Jul 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [b3dbd3f2af](https://linux-hardware.org/?probe=b3dbd3f2af) | Jul 14, 2020 |
| Toshiba       | TECRA A50-C                 | Notebook    | [adf7a73571](https://linux-hardware.org/?probe=adf7a73571) | Jul 03, 2020 |
| ASUSTek       | FX503VD                     | Notebook    | [d6c0a21749](https://linux-hardware.org/?probe=d6c0a21749) | Jul 02, 2020 |
| HP            | Pavilion 15                 | Notebook    | [499f0c72ee](https://linux-hardware.org/?probe=499f0c72ee) | Jun 29, 2020 |
| ASUSTek       | P7P55 LX                    | Desktop     | [dc74d7b188](https://linux-hardware.org/?probe=dc74d7b188) | Jun 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [dd5c9e8d9f](https://linux-hardware.org/?probe=dd5c9e8d9f) | Jun 23, 2020 |
| Dell          | Latitude E6410              | Notebook    | [06055ff260](https://linux-hardware.org/?probe=06055ff260) | Jun 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [b53cc32ed0](https://linux-hardware.org/?probe=b53cc32ed0) | Jun 19, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [fdc9496e84](https://linux-hardware.org/?probe=fdc9496e84) | Jun 19, 2020 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [fdbf1ae7da](https://linux-hardware.org/?probe=fdbf1ae7da) | Jun 19, 2020 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [0d398d9227](https://linux-hardware.org/?probe=0d398d9227) | Jun 14, 2020 |
| HP            | 2AA2                        | Desktop     | [24c07d9d0d](https://linux-hardware.org/?probe=24c07d9d0d) | Jun 11, 2020 |
| HP            | 8446                        | All in one  | [d64a9cef98](https://linux-hardware.org/?probe=d64a9cef98) | Jun 11, 2020 |
| Dell          | Latitude E6410              | Notebook    | [1b73d74e65](https://linux-hardware.org/?probe=1b73d74e65) | Jun 09, 2020 |
| Lenovo        | ThinkPad L480 20LS0012AD    | Notebook    | [e9b38b78d7](https://linux-hardware.org/?probe=e9b38b78d7) | May 30, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [83ae823929](https://linux-hardware.org/?probe=83ae823929) | May 23, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [af063f022b](https://linux-hardware.org/?probe=af063f022b) | May 23, 2020 |
| HP            | Presario C300 (RH208UA#A... | Notebook    | [50e95ff237](https://linux-hardware.org/?probe=50e95ff237) | May 14, 2020 |
| HP            | Presario C300 (RH208UA#A... | Notebook    | [6b4a8eab4c](https://linux-hardware.org/?probe=6b4a8eab4c) | May 14, 2020 |
| Toshiba       | TECRA X40-D                 | Notebook    | [3255796d07](https://linux-hardware.org/?probe=3255796d07) | May 10, 2020 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [49363e9553](https://linux-hardware.org/?probe=49363e9553) | May 07, 2020 |
| HP            | 8446                        | All in one  | [96d169caae](https://linux-hardware.org/?probe=96d169caae) | May 06, 2020 |
| HP            | 8446                        | All in one  | [835b1abcee](https://linux-hardware.org/?probe=835b1abcee) | May 02, 2020 |
| HP            | 8446                        | All in one  | [aa03445e30](https://linux-hardware.org/?probe=aa03445e30) | May 01, 2020 |
| HP            | 8446                        | All in one  | [d9db887931](https://linux-hardware.org/?probe=d9db887931) | May 01, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [887a19760b](https://linux-hardware.org/?probe=887a19760b) | May 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS6GB00    | Notebook    | [3fa804be21](https://linux-hardware.org/?probe=3fa804be21) | May 01, 2020 |
| HP            | 8446                        | All in one  | [eab561395e](https://linux-hardware.org/?probe=eab561395e) | Apr 27, 2020 |
| HP            | 8446                        | All in one  | [ad2491858f](https://linux-hardware.org/?probe=ad2491858f) | Apr 25, 2020 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [d2328783da](https://linux-hardware.org/?probe=d2328783da) | Apr 24, 2020 |
| Dell          | Vostro 14-5480              | Notebook    | [1bba68101c](https://linux-hardware.org/?probe=1bba68101c) | Apr 20, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [aac474f532](https://linux-hardware.org/?probe=aac474f532) | Apr 18, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [1ef49ff7a3](https://linux-hardware.org/?probe=1ef49ff7a3) | Apr 17, 2020 |
| HP            | Notebook                    | Notebook    | [4f154f82b0](https://linux-hardware.org/?probe=4f154f82b0) | Apr 01, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [5cd86dffe9](https://linux-hardware.org/?probe=5cd86dffe9) | Mar 16, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [7f0b4db18a](https://linux-hardware.org/?probe=7f0b4db18a) | Mar 12, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [87df29714d](https://linux-hardware.org/?probe=87df29714d) | Mar 11, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [04da794ff5](https://linux-hardware.org/?probe=04da794ff5) | Feb 25, 2020 |
| HP            | EliteBook 2760p             | Notebook    | [40333472c7](https://linux-hardware.org/?probe=40333472c7) | Feb 21, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [b12186f161](https://linux-hardware.org/?probe=b12186f161) | Feb 13, 2020 |
| HP            | Notebook                    | Notebook    | [a25a67e533](https://linux-hardware.org/?probe=a25a67e533) | Feb 02, 2020 |
| Lenovo        | ThinkPad T460 20FMS1A200    | Notebook    | [c2a7159d3a](https://linux-hardware.org/?probe=c2a7159d3a) | Jan 04, 2020 |
| Lenovo        | ThinkPad T460 20FMS1A200    | Notebook    | [028d728043](https://linux-hardware.org/?probe=028d728043) | Jan 04, 2020 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [d1ca80edff](https://linux-hardware.org/?probe=d1ca80edff) | Dec 24, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [420c738977](https://linux-hardware.org/?probe=420c738977) | Oct 15, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [036dc7e829](https://linux-hardware.org/?probe=036dc7e829) | Oct 15, 2019 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [ab1c14d729](https://linux-hardware.org/?probe=ab1c14d729) | Oct 12, 2019 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [558c01fdce](https://linux-hardware.org/?probe=558c01fdce) | Oct 07, 2019 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [d4ad7906b5](https://linux-hardware.org/?probe=d4ad7906b5) | Sep 11, 2019 |
| Dell          | 0NK70N A03                  | Desktop     | [8aa5224a4a](https://linux-hardware.org/?probe=8aa5224a4a) | Aug 01, 2019 |
| I-Life Dig... | ZED AIR                     | Notebook    | [514c494f7f](https://linux-hardware.org/?probe=514c494f7f) | Jul 23, 2019 |
| I-Life Dig... | ZED AIR                     | Notebook    | [a9fe92aa3c](https://linux-hardware.org/?probe=a9fe92aa3c) | Jul 23, 2019 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [309f371381](https://linux-hardware.org/?probe=309f371381) | May 27, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [1f8a20b199](https://linux-hardware.org/?probe=1f8a20b199) | May 25, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [60d0e8dd5d](https://linux-hardware.org/?probe=60d0e8dd5d) | May 25, 2019 |
| HP            | ProBook 4540s               | Notebook    | [271be85705](https://linux-hardware.org/?probe=271be85705) | May 15, 2019 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [ab25f83cd0](https://linux-hardware.org/?probe=ab25f83cd0) | Mar 27, 2019 |
| ASUSTek       | ROG STRIX X299-XE GAMING    | Desktop     | [c8fdc5e958](https://linux-hardware.org/?probe=c8fdc5e958) | Dec 25, 2018 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [c48aa05e74](https://linux-hardware.org/?probe=c48aa05e74) | Oct 08, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 35        | 10.9%   |
| Ubuntu 22.04                 | 30        | 9.35%   |
| Ubuntu 18.04                 | 18        | 5.61%   |
| Arch Rolling                 | 15        | 4.67%   |
| Ubuntu 24.04                 | 12        | 3.74%   |
| Pop!_OS 22.04                | 11        | 3.43%   |
| Fedora 40                    | 9         | 2.8%    |
| Debian 12                    | 9         | 2.8%    |
| Debian 11                    | 6         | 1.87%   |
| ArcoLinux Rolling            | 6         | 1.87%   |
| Fedora 38                    | 5         | 1.56%   |
| Fedora 37                    | 5         | 1.56%   |
| Arch                         | 5         | 1.56%   |
| Zorin 16                     | 4         | 1.25%   |
| Ubuntu 22.10                 | 4         | 1.25%   |
| Ubuntu 19.10                 | 4         | 1.25%   |
| Linux Mint 21.3              | 4         | 1.25%   |
| Linux Mint 20.3              | 4         | 1.25%   |
| Kubuntu 22.04                | 4         | 1.25%   |
| Fedora 39                    | 4         | 1.25%   |
| Fedora 36                    | 4         | 1.25%   |
| Zorin 15                     | 3         | 0.93%   |
| Ubuntu 23.04                 | 3         | 0.93%   |
| Ubuntu 20.10                 | 3         | 0.93%   |
| SteamOS 3.6.20               | 3         | 0.93%   |
| Linux Mint 21.2              | 3         | 0.93%   |
| Kubuntu 24.04                | 3         | 0.93%   |
| KDE neon 22.04               | 3         | 0.93%   |
| Debian 10                    | 3         | 0.93%   |
| Ubuntu 24.10                 | 2         | 0.62%   |
| Ubuntu 21.10                 | 2         | 0.62%   |
| Ubuntu 16.04                 | 2         | 0.62%   |
| SteamOS 3.5.19               | 2         | 0.62%   |
| SteamOS 3.4.6                | 2         | 0.62%   |
| Pop!_OS 20.10                | 2         | 0.62%   |
| Pop!_OS 20.04                | 2         | 0.62%   |
| Parrot 6.0                   | 2         | 0.62%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.62%   |
| OpenMandriva 4.3             | 2         | 0.62%   |
| OpenMandriva 24.07           | 2         | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 115       | 36.98%  |
| Fedora       | 32        | 10.29%  |
| Arch         | 20        | 6.43%   |
| Debian       | 19        | 6.11%   |
| Pop!_OS      | 15        | 4.82%   |
| Linux Mint   | 15        | 4.82%   |
| OpenMandriva | 12        | 3.86%   |
| SteamOS      | 10        | 3.22%   |
| Kubuntu      | 9         | 2.89%   |
| Zorin        | 7         | 2.25%   |
| Manjaro      | 6         | 1.93%   |
| ArcoLinux    | 6         | 1.93%   |
| KDE neon     | 5         | 1.61%   |
| Kali         | 5         | 1.61%   |
| Parrot       | 3         | 0.96%   |
| Xubuntu      | 2         | 0.64%   |
| openSUSE     | 2         | 0.64%   |
| Nobara       | 2         | 0.64%   |
| Lubuntu      | 2         | 0.64%   |
| Endless      | 2         | 0.64%   |
| Elementary   | 2         | 0.64%   |
| BlackPanther | 2         | 0.64%   |
| Ubuntu Unity | 1         | 0.32%   |
| Ubuntu MATE  | 1         | 0.32%   |
| Sparky       | 1         | 0.32%   |
| ROSA         | 1         | 0.32%   |
| Rocky Linux  | 1         | 0.32%   |
| Reborn OS    | 1         | 0.32%   |
| PostmarketOS | 1         | 0.32%   |
| NixOS        | 1         | 0.32%   |
| MX           | 1         | 0.32%   |
| Guix         | 1         | 0.32%   |
| GNOME OS     | 1         | 0.32%   |
| Gentoo       | 1         | 0.32%   |
| Garuda Linux | 1         | 0.32%   |
| Feren OS     | 1         | 0.32%   |
| EndeavourOS  | 1         | 0.32%   |
| CachyOS      | 1         | 0.32%   |
| Bazzite      | 1         | 0.32%   |
| Alpine       | 1         | 0.32%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                  | Computers | Percent |
|------------------------------------------|-----------|---------|
| 5.4.0-42-generic                         | 7         | 2.06%   |
| 6.8.0-40-generic                         | 4         | 1.18%   |
| 6.1.0-21-amd64                           | 4         | 1.18%   |
| 5.4.0-58-generic                         | 4         | 1.18%   |
| 5.4.0-26-generic                         | 4         | 1.18%   |
| 5.13.0-valve36-1-neptune                 | 4         | 1.18%   |
| 6.9.3-76060903-generic                   | 3         | 0.88%   |
| 6.8.5-301.fc40.x86_64                    | 3         | 0.88%   |
| 6.8.0-31-generic                         | 3         | 0.88%   |
| 6.5.0-valve22-1-neptune-65-g9a338ed8a75e | 3         | 0.88%   |
| 6.2.0-33-generic                         | 3         | 0.88%   |
| 6.1.52-valve16-1-neptune-61              | 3         | 0.88%   |
| 5.4.0-37-generic                         | 3         | 0.88%   |
| 5.11.0-40-generic                        | 3         | 0.88%   |
| 4.15.0-50-generic                        | 3         | 0.88%   |
| 6.8.0-51-generic                         | 2         | 0.59%   |
| 6.8.0-38-generic                         | 2         | 0.59%   |
| 6.8.0-36-generic                         | 2         | 0.59%   |
| 6.8.0-35-generic                         | 2         | 0.59%   |
| 6.5.6-300.fc39.x86_64                    | 2         | 0.59%   |
| 6.5.0-kali3-amd64                        | 2         | 0.59%   |
| 6.5.0-45-generic                         | 2         | 0.59%   |
| 6.5.0-35-generic                         | 2         | 0.59%   |
| 6.4.8-desktop-2omv2390                   | 2         | 0.59%   |
| 6.4.7-200.fc38.x86_64                    | 2         | 0.59%   |
| 6.2.0-32-generic                         | 2         | 0.59%   |
| 6.2.0-26-generic                         | 2         | 0.59%   |
| 6.11.8-300.fc41.x86_64                   | 2         | 0.59%   |
| 6.11.6-arch1-1                           | 2         | 0.59%   |
| 6.11.0-9-generic                         | 2         | 0.59%   |
| 6.1.1-desktop-1omv2290                   | 2         | 0.59%   |
| 6.1.0-kali5-amd64                        | 2         | 0.59%   |
| 6.1.0-18-amd64                           | 2         | 0.59%   |
| 6.1.0-13-amd64                           | 2         | 0.59%   |
| 6.0.6-76060006-generic                   | 2         | 0.59%   |
| 5.8.0-40-generic                         | 2         | 0.59%   |
| 5.4.0-81-generic                         | 2         | 0.59%   |
| 5.4.0-48-generic                         | 2         | 0.59%   |
| 5.4.0-33-generic                         | 2         | 0.59%   |
| 5.4.0-29-generic                         | 2         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 36        | 11.08%  |
| 6.8.0   | 21        | 6.46%   |
| 5.15.0  | 21        | 6.46%   |
| 6.5.0   | 16        | 4.92%   |
| 5.19.0  | 16        | 4.92%   |
| 4.15.0  | 14        | 4.31%   |
| 6.1.0   | 13        | 4%      |
| 6.2.0   | 12        | 3.69%   |
| 5.8.0   | 9         | 2.77%   |
| 5.11.0  | 9         | 2.77%   |
| 5.13.0  | 8         | 2.46%   |
| 5.10.0  | 7         | 2.15%   |
| 5.3.0   | 6         | 1.85%   |
| 6.9.3   | 4         | 1.23%   |
| 6.8.5   | 4         | 1.23%   |
| 6.1.52  | 4         | 1.23%   |
| 6.7.4   | 3         | 0.92%   |
| 6.5.6   | 3         | 0.92%   |
| 6.4.8   | 3         | 0.92%   |
| 6.11.0  | 3         | 0.92%   |
| 6.0.12  | 3         | 0.92%   |
| 5.0.0   | 3         | 0.92%   |
| 6.8.9   | 2         | 0.62%   |
| 6.8.7   | 2         | 0.62%   |
| 6.6.1   | 2         | 0.62%   |
| 6.5.9   | 2         | 0.62%   |
| 6.4.7   | 2         | 0.62%   |
| 6.2.10  | 2         | 0.62%   |
| 6.12.1  | 2         | 0.62%   |
| 6.11.8  | 2         | 0.62%   |
| 6.11.6  | 2         | 0.62%   |
| 6.11.3  | 2         | 0.62%   |
| 6.10.6  | 2         | 0.62%   |
| 6.10.4  | 2         | 0.62%   |
| 6.1.1   | 2         | 0.62%   |
| 6.0.6   | 2         | 0.62%   |
| 5.7.14  | 2         | 0.62%   |
| 5.16.7  | 2         | 0.62%   |
| 5.14.0  | 2         | 0.62%   |
| 4.18.0  | 2         | 0.62%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 38        | 11.8%   |
| 6.8     | 31        | 9.63%   |
| 5.15    | 26        | 8.07%   |
| 6.1     | 25        | 7.76%   |
| 6.5     | 22        | 6.83%   |
| 5.19    | 19        | 5.9%    |
| 6.2     | 16        | 4.97%   |
| 4.15    | 14        | 4.35%   |
| 5.8     | 11        | 3.42%   |
| 6.9     | 10        | 3.11%   |
| 6.11    | 10        | 3.11%   |
| 5.10    | 10        | 3.11%   |
| 5.13    | 9         | 2.8%    |
| 5.11    | 9         | 2.8%    |
| 6.6     | 7         | 2.17%   |
| 6.4     | 7         | 2.17%   |
| 6.10    | 7         | 2.17%   |
| 5.3     | 6         | 1.86%   |
| 6.7     | 5         | 1.55%   |
| 6.0     | 5         | 1.55%   |
| 5.16    | 5         | 1.55%   |
| 5.9     | 3         | 0.93%   |
| 5.7     | 3         | 0.93%   |
| 5.14    | 3         | 0.93%   |
| 5.0     | 3         | 0.93%   |
| 4.18    | 3         | 0.93%   |
| 6.3     | 2         | 0.62%   |
| 6.12    | 2         | 0.62%   |
| 5.6     | 2         | 0.62%   |
| 5.18    | 2         | 0.62%   |
| 5.17    | 2         | 0.62%   |
| 4.19    | 2         | 0.62%   |
| 5.5     | 1         | 0.31%   |
| 5.12    | 1         | 0.31%   |
| 4.4     | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 293       | 98.32%  |
| aarch64 | 3         | 1.01%   |
| i686    | 2         | 0.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 165       | 53.05%  |
| KDE5       | 48        | 15.43%  |
| Unknown    | 27        | 8.68%   |
| X-Cinnamon | 15        | 4.82%   |
| KDE6       | 15        | 4.82%   |
| XFCE       | 14        | 4.5%    |
| MATE       | 6         | 1.93%   |
| LXQt       | 4         | 1.29%   |
| KDE        | 4         | 1.29%   |
| Pantheon   | 2         | 0.64%   |
| i3         | 2         | 0.64%   |
| wlroots    | 1         | 0.32%   |
| Unity      | 1         | 0.32%   |
| Hyprland   | 1         | 0.32%   |
| gamescope  | 1         | 0.32%   |
| DWM        | 1         | 0.32%   |
| Cinnamon   | 1         | 0.32%   |
| Budgie     | 1         | 0.32%   |
| bspwm      | 1         | 0.32%   |
| awesome    | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 184       | 59.93%  |
| Wayland | 102       | 33.22%  |
| Unknown | 13        | 4.23%   |
| Tty     | 8         | 2.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 152       | 49.03%  |
| GDM3    | 55        | 17.74%  |
| SDDM    | 41        | 13.23%  |
| GDM     | 35        | 11.29%  |
| LightDM | 25        | 8.06%   |
| TDM     | 2         | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 238       | 78.55%  |
| Unknown | 18        | 5.94%   |
| en_GB   | 17        | 5.61%   |
| C       | 13        | 4.29%   |
| ru_RU   | 4         | 1.32%   |
| en_IN   | 2         | 0.66%   |
| en_AU   | 2         | 0.66%   |
| ar_AE   | 2         | 0.66%   |
| pl_PL   | 1         | 0.33%   |
| hu_HU   | 1         | 0.33%   |
| en_PH   | 1         | 0.33%   |
| en_NG   | 1         | 0.33%   |
| en_AG   | 1         | 0.33%   |
| el_GR   | 1         | 0.33%   |
| de_DE   | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 170       | 54.66%  |
| BIOS | 141       | 45.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 201       | 66.34%  |
| Btrfs   | 55        | 18.15%  |
| Tmpfs   | 21        | 6.93%   |
| Overlay | 16        | 5.28%   |
| Xfs     | 6         | 1.98%   |
| Zfs     | 1         | 0.33%   |
| F2fs    | 1         | 0.33%   |
| Ext2    | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 147       | 48.2%   |
| GPT     | 142       | 46.56%  |
| MBR     | 16        | 5.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 271       | 90.03%  |
| Yes       | 30        | 9.97%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 203       | 66.78%  |
| Yes       | 101       | 33.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 73        | 24.5%   |
| Hewlett-Packard             | 56        | 18.79%  |
| ASUSTek Computer            | 42        | 14.09%  |
| Dell                        | 31        | 10.4%   |
| Valve                       | 10        | 3.36%   |
| Apple                       | 9         | 3.02%   |
| Toshiba                     | 8         | 2.68%   |
| MSI                         | 8         | 2.68%   |
| Acer                        | 8         | 2.68%   |
| Intel                       | 7         | 2.35%   |
| Gigabyte Technology         | 7         | 2.35%   |
| Notebook                    | 3         | 1.01%   |
| Microsoft                   | 3         | 1.01%   |
| HUAWEI                      | 3         | 1.01%   |
| Google                      | 3         | 1.01%   |
| win element                 | 2         | 0.67%   |
| Sony                        | 2         | 0.67%   |
| Razer                       | 2         | 0.67%   |
| I-Life Digital Technologies | 2         | 0.67%   |
| AZW                         | 2         | 0.67%   |
| ASRock                      | 2         | 0.67%   |
| Alienware                   | 2         | 0.67%   |
| YJKC                        | 1         | 0.34%   |
| Trigkey                     | 1         | 0.34%   |
| SZMZ                        | 1         | 0.34%   |
| Samsung Electronics         | 1         | 0.34%   |
| Raspberry Pi Foundation     | 1         | 0.34%   |
| Pegatron                    | 1         | 0.34%   |
| Nvidia                      | 1         | 0.34%   |
| Neousys Technology          | 1         | 0.34%   |
| LG Electronics              | 1         | 0.34%   |
| ECS                         | 1         | 0.34%   |
| Biostar                     | 1         | 0.34%   |
| A-DATA Technology           | 1         | 0.34%   |
| Unknown                     | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 10        | 3.36%   |
| HP All-in-One 22-c0xx                                 | 3         | 1.01%   |
| ASUS VivoBook_ASUSLaptop X1404VA_X1404VA              | 3         | 1.01%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 2         | 0.67%   |
| Microsoft Surface Pro 4                               | 2         | 0.67%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU                     | 2         | 0.67%   |
| HP ProBook 450 G2                                     | 2         | 0.67%   |
| HP Pavilion Notebook                                  | 2         | 0.67%   |
| HP Pavilion 15                                        | 2         | 0.67%   |
| HP ENVY Laptop 13-aq0xxx                              | 2         | 0.67%   |
| Dell Latitude E6540                                   | 2         | 0.67%   |
| Dell G5 5587                                          | 2         | 0.67%   |
| ASUS ROG STRIX X670E-E GAMING WIFI                    | 2         | 0.67%   |
| ASUS All Series                                       | 2         | 0.67%   |
| YJKC vBOOK Plus                                       | 1         | 0.34%   |
| Win Element S500+                                     | 1         | 0.34%   |
| win element MoreFine S500+                            | 1         | 0.34%   |
| Trigkey Green G4                                      | 1         | 0.34%   |
| Toshiba TECRA X40-D                                   | 1         | 0.34%   |
| Toshiba TECRA A50-C                                   | 1         | 0.34%   |
| Toshiba Satellite L850-B434                           | 1         | 0.34%   |
| Toshiba Satellite L750                                | 1         | 0.34%   |
| Toshiba Satellite C850-A966                           | 1         | 0.34%   |
| Toshiba Satellite C660                                | 1         | 0.34%   |
| Toshiba Satellite A300                                | 1         | 0.34%   |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.34%   |
| SZMZ B75-MS                                           | 1         | 0.34%   |
| Sony VGN-NS10J_S                                      | 1         | 0.34%   |
| Sony SVE14A25CAB                                      | 1         | 0.34%   |
| Samsung 950QDB                                        | 1         | 0.34%   |
| RPi Raspberry Pi 4 Model B Rev 1.1                    | 1         | 0.34%   |
| Pegatron s5-1050jp                                    | 1         | 0.34%   |
| Nvidia Tegra                                          | 1         | 0.34%   |
| Notebook PD5x_7xPNP_PNN_PNT                           | 1         | 0.34%   |
| Notebook P95_96_97Ex,Rx                               | 1         | 0.34%   |
| Notebook NV4XMB,ME,MZ                                 | 1         | 0.34%   |
| Neousys Nuvo-6108GC                                   | 1         | 0.34%   |
| MSI PS63 Modern 8RD                                   | 1         | 0.34%   |
| MSI MS-7D91                                           | 1         | 0.34%   |
| MSI MS-7D88                                           | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 39        | 13.09%  |
| HP Pavilion          | 13        | 4.36%   |
| ASUS ROG             | 13        | 4.36%   |
| Lenovo IdeaPad       | 11        | 3.69%   |
| Valve Jupiter        | 10        | 3.36%   |
| HP Laptop            | 9         | 3.02%   |
| Dell Latitude        | 9         | 3.02%   |
| HP EliteBook         | 7         | 2.35%   |
| HP ProBook           | 6         | 2.01%   |
| Dell XPS             | 6         | 2.01%   |
| ASUS VivoBook        | 6         | 2.01%   |
| ASUS PRIME           | 6         | 2.01%   |
| Toshiba Satellite    | 5         | 1.68%   |
| Lenovo Yoga          | 5         | 1.68%   |
| Lenovo Legion        | 5         | 1.68%   |
| Acer Aspire          | 5         | 1.68%   |
| Lenovo IdeaPadFlex   | 4         | 1.34%   |
| HP ENVY              | 4         | 1.34%   |
| Dell Inspiron        | 4         | 1.34%   |
| Microsoft Surface    | 3         | 1.01%   |
| Lenovo ThinkCentre   | 3         | 1.01%   |
| HP All-in-One        | 3         | 1.01%   |
| Dell Precision       | 3         | 1.01%   |
| Dell OptiPlex        | 3         | 1.01%   |
| ASUS ASUS            | 3         | 1.01%   |
| Toshiba TECRA        | 2         | 0.67%   |
| Razer Blade          | 2         | 0.67%   |
| I-Life Digital ZED   | 2         | 0.67%   |
| Dell Vostro          | 2         | 0.67%   |
| Dell G5              | 2         | 0.67%   |
| ASUS ZenBook         | 2         | 0.67%   |
| ASUS All             | 2         | 0.67%   |
| YJKC vBOOK           | 1         | 0.34%   |
| Win Element S500+    | 1         | 0.34%   |
| win element MoreFine | 1         | 0.34%   |
| Trigkey Green        | 1         | 0.34%   |
| Toshiba PORTEGE      | 1         | 0.34%   |
| SZMZ B75-MS          | 1         | 0.34%   |
| Sony VGN-NS10J       | 1         | 0.34%   |
| Sony SVE14A25CAB     | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 38        | 12.75%  |
| 2020    | 29        | 9.73%   |
| 2018    | 26        | 8.72%   |
| 2022    | 25        | 8.39%   |
| 2019    | 23        | 7.72%   |
| 2016    | 22        | 7.38%   |
| 2023    | 21        | 7.05%   |
| 2013    | 20        | 6.71%   |
| 2012    | 16        | 5.37%   |
| 2017    | 14        | 4.7%    |
| 2014    | 12        | 4.03%   |
| 2010    | 12        | 4.03%   |
| 2015    | 9         | 3.02%   |
| 2011    | 9         | 3.02%   |
| 2008    | 7         | 2.35%   |
| 2024    | 4         | 1.34%   |
| 2007    | 4         | 1.34%   |
| 2009    | 3         | 1.01%   |
| Unknown | 3         | 1.01%   |
| 2005    | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 201       | 67.45%  |
| Desktop        | 59        | 19.8%   |
| Convertible    | 15        | 5.03%   |
| All in one     | 7         | 2.35%   |
| Mini pc        | 6         | 2.01%   |
| Tablet         | 5         | 1.68%   |
| System on chip | 3         | 1.01%   |
| Server         | 2         | 0.67%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 273       | 90.4%   |
| Enabled  | 29        | 9.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 295       | 98.99%  |
| Yes  | 3         | 1.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 75        | 25.08%  |
| 4.01-8.0        | 61        | 20.4%   |
| 16.01-24.0      | 59        | 19.73%  |
| 32.01-64.0      | 35        | 11.71%  |
| 3.01-4.0        | 31        | 10.37%  |
| 64.01-256.0     | 20        | 6.69%   |
| 24.01-32.0      | 7         | 2.34%   |
| 2.01-3.0        | 3         | 1%      |
| 1.01-2.0        | 3         | 1%      |
| 0.51-1.0        | 3         | 1%      |
| More than 256.0 | 2         | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 80        | 24.77%  |
| 2.01-3.0   | 80        | 24.77%  |
| 1.01-2.0   | 68        | 21.05%  |
| 3.01-4.0   | 63        | 19.5%   |
| 8.01-16.0  | 16        | 4.95%   |
| 0.51-1.0   | 8         | 2.48%   |
| 16.01-24.0 | 4         | 1.24%   |
| 0.01-0.5   | 3         | 0.93%   |
| 24.01-32.0 | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 198       | 65.56%  |
| 2      | 64        | 21.19%  |
| 3      | 19        | 6.29%   |
| 4      | 7         | 2.32%   |
| 6      | 4         | 1.32%   |
| 5      | 3         | 0.99%   |
| 0      | 3         | 0.99%   |
| 9      | 2         | 0.66%   |
| 11     | 1         | 0.33%   |
| 8      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 233       | 77.67%  |
| Yes       | 67        | 22.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 220       | 73.09%  |
| No        | 81        | 26.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 260       | 86.96%  |
| No        | 39        | 13.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 232       | 77.08%  |
| No        | 69        | 22.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UAE     | 298       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Dubai            | 153       | 50.33%  |
| Abu Dhabi        | 81        | 26.64%  |
| Sharjah          | 32        | 10.53%  |
| Al Ain City      | 19        | 6.25%   |
| Ajman            | 10        | 3.29%   |
| Al Fujairah City | 4         | 1.32%   |
| Ras al-Khaimah   | 3         | 0.99%   |
| Deira            | 1         | 0.33%   |
| Al Halah         | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 77        | 110    | 18.47%  |
| WDC                            | 55        | 69     | 13.19%  |
| Seagate                        | 41        | 57     | 9.83%   |
| Toshiba                        | 26        | 31     | 6.24%   |
| Unknown                        | 23        | 35     | 5.52%   |
| SanDisk                        | 19        | 22     | 4.56%   |
| Crucial                        | 18        | 20     | 4.32%   |
| Micron Technology              | 16        | 17     | 3.84%   |
| Intel                          | 15        | 19     | 3.6%    |
| HGST                           | 12        | 15     | 2.88%   |
| SK hynix                       | 11        | 15     | 2.64%   |
| Phison Electronics             | 10        | 10     | 2.4%    |
| Kingston Technology Company    | 8         | 8      | 1.92%   |
| Kingston                       | 8         | 8      | 1.92%   |
| Micron/Crucial Technology      | 6         | 7      | 1.44%   |
| Apple                          | 5         | 6      | 1.2%    |
| Team                           | 4         | 4      | 0.96%   |
| Lexar                          | 4         | 4      | 0.96%   |
| Hitachi                        | 4         | 4      | 0.96%   |
| Silicon Motion                 | 3         | 3      | 0.72%   |
| Realtek Semiconductor          | 3         | 6      | 0.72%   |
| Phison                         | 3         | 3      | 0.72%   |
| External                       | 3         | 3      | 0.72%   |
| Corsair                        | 3         | 6      | 0.72%   |
| ASMT                           | 3         | 13     | 0.72%   |
| Unknown                        | 3         | 3      | 0.72%   |
| USB3.0                         | 2         | 2      | 0.48%   |
| Transcend                      | 2         | 2      | 0.48%   |
| Patriot                        | 2         | 3      | 0.48%   |
| LaCie                          | 2         | 2      | 0.48%   |
| KIOXIA                         | 2         | 6      | 0.48%   |
| JMicron Technology             | 2         | 2      | 0.48%   |
| China                          | 2         | 2      | 0.48%   |
| ADATA Technology               | 2         | 2      | 0.48%   |
| A-DATA Technology              | 2         | 2      | 0.48%   |
| USB                            | 1         | 1      | 0.24%   |
| Super Talent                   | 1         | 1      | 0.24%   |
| Solid State Storage Technology | 1         | 1      | 0.24%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.24%   |
| Pliant                         | 1         | 4      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 7         | 1.57%   |
| Phison E12 NVMe Controller 480GB                      | 6         | 1.35%   |
| HGST HTS721010A9E630 1TB                              | 6         | 1.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 5         | 1.12%   |
| WDC WD10SPZX-08Z10 1TB                                | 4         | 0.9%    |
| Unknown MMC Card  64GB                                | 4         | 0.9%    |
| Toshiba DT01ACA100 1TB                                | 4         | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB                        | 4         | 0.9%    |
| Samsung NVMe SSD Drive 256GB                          | 4         | 0.9%    |
| HGST HTS725050A7E630 500GB                            | 4         | 0.9%    |
| WDC WD10JPCX-24UE4T0 1TB                              | 3         | 0.67%   |
| Unknown SD/MMC/MS PRO 128GB                           | 3         | 0.67%   |
| Unknown MMC Card  512GB                               | 3         | 0.67%   |
| Unknown MMC Card  32GB                                | 3         | 0.67%   |
| Unknown MMC Card  256GB                               | 3         | 0.67%   |
| Unknown MMC Card  16GB                                | 3         | 0.67%   |
| Toshiba MQ01ABD075 752GB                              | 3         | 0.67%   |
| Seagate ST500LT012-1DG142 500GB                       | 3         | 0.67%   |
| Seagate ST500DM002-1BD142 500GB                       | 3         | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB                        | 3         | 0.67%   |
| Samsung SSD 980 PRO 1TB                               | 3         | 0.67%   |
| Samsung SSD 970 EVO Plus 1TB                          | 3         | 0.67%   |
| Samsung SSD 850 PRO 1TB                               | 3         | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 3         | 0.67%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 3         | 0.67%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 3         | 0.67%   |
| Micron 2400_MTFDKBA512QFM 512GB                       | 3         | 0.67%   |
| Intel NVMe SSD Drive 512GB                            | 3         | 0.67%   |
| External USB3.0 1TB                                   | 3         | 0.67%   |
| Crucial CT500MX500SSD1 500GB                          | 3         | 0.67%   |
| Crucial CT1000BX500SSD1 1TB                           | 3         | 0.67%   |
| Unknown                                               | 3         | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 2         | 0.45%   |
| WDC WD20EFRX-68EUZN0 2TB                              | 2         | 0.45%   |
| WDC WD1002FAEX-00Z3A0 1TB                             | 2         | 0.45%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                    | 2         | 0.45%   |
| USB3.0 Super Speed 500GB SSD                          | 2         | 0.45%   |
| SK hynix HFM001TD3JX013N 1024GB                       | 2         | 0.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 0.45%   |
| Seagate ST500VT000-1DK142 500GB                       | 2         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 41        | 55     | 31.3%   |
| Seagate             | 40        | 56     | 30.53%  |
| Toshiba             | 20        | 25     | 15.27%  |
| HGST                | 12        | 15     | 9.16%   |
| Hitachi             | 4         | 4      | 3.05%   |
| Unknown             | 3         | 6      | 2.29%   |
| External            | 3         | 3      | 2.29%   |
| ASMT                | 2         | 12     | 1.53%   |
| Apple               | 2         | 2      | 1.53%   |
| Samsung Electronics | 1         | 1      | 0.76%   |
| Maxtor              | 1         | 1      | 0.76%   |
| JMicron Technology  | 1         | 1      | 0.76%   |
| Fujitsu             | 1         | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 36     | 26.09%  |
| Crucial             | 14        | 16     | 15.22%  |
| WDC                 | 9         | 9      | 9.78%   |
| SanDisk             | 8         | 9      | 8.7%    |
| Kingston            | 4         | 4      | 4.35%   |
| Team                | 3         | 3      | 3.26%   |
| Intel               | 3         | 4      | 3.26%   |
| USB3.0              | 2         | 2      | 2.17%   |
| Transcend           | 2         | 2      | 2.17%   |
| Patriot             | 2         | 3      | 2.17%   |
| Lexar               | 2         | 2      | 2.17%   |
| LaCie               | 2         | 2      | 2.17%   |
| Corsair             | 2         | 5      | 2.17%   |
| China               | 2         | 2      | 2.17%   |
| Apple               | 2         | 2      | 2.17%   |
| Toshiba             | 1         | 1      | 1.09%   |
| Super Talent        | 1         | 1      | 1.09%   |
| SK hynix            | 1         | 1      | 1.09%   |
| Micron Technology   | 1         | 1      | 1.09%   |
| MAX                 | 1         | 1      | 1.09%   |
| KingSpec            | 1         | 2      | 1.09%   |
| HXY                 | 1         | 1      | 1.09%   |
| Gigabyte Technology | 1         | 1      | 1.09%   |
| Carlstein           | 1         | 1      | 1.09%   |
| ASMT                | 1         | 1      | 1.09%   |
| Unknown             | 1         | 1      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 162       | 213    | 42.63%  |
| HDD     | 116       | 182    | 30.53%  |
| SSD     | 79        | 113    | 20.79%  |
| MMC     | 19        | 27     | 5%      |
| Unknown | 4         | 7      | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 161       | 212    | 44.97%  |
| SATA | 160       | 263    | 44.69%  |
| MMC  | 19        | 27     | 5.31%   |
| SAS  | 18        | 40     | 5.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 94        | 126    | 46.31%  |
| 0.51-1.0   | 75        | 99     | 36.95%  |
| 1.01-2.0   | 20        | 33     | 9.85%   |
| 3.01-4.0   | 8         | 17     | 3.94%   |
| 10.01-20.0 | 3         | 7      | 1.48%   |
| 4.01-10.0  | 3         | 13     | 1.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 87        | 27.8%   |
| 101-250        | 64        | 20.45%  |
| 501-1000       | 40        | 12.78%  |
| 1001-2000      | 33        | 10.54%  |
| 51-100         | 22        | 7.03%   |
| 21-50          | 17        | 5.43%   |
| 1-20           | 17        | 5.43%   |
| More than 3000 | 13        | 4.15%   |
| 2001-3000      | 11        | 3.51%   |
| Unknown        | 9         | 2.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 116       | 35.91%  |
| 21-50          | 74        | 22.91%  |
| 101-250        | 38        | 11.76%  |
| 51-100         | 34        | 10.53%  |
| 501-1000       | 21        | 6.5%    |
| 251-500        | 20        | 6.19%   |
| Unknown        | 9         | 2.79%   |
| 1001-2000      | 6         | 1.86%   |
| More than 3000 | 4         | 1.24%   |
| 2001-3000      | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Computers | Drives | Percent |
|-----------------------------------------------------------|-----------|--------|---------|
| WDC WD40PURZ-85TTDY0 4TB                                  | 1         | 2      | 5.26%   |
| WDC WD40EFRX-68WT0N0 4TB                                  | 1         | 2      | 5.26%   |
| WDC WD20EADS-00R6B0 2TB                                   | 1         | 1      | 5.26%   |
| WDC WD10JPVX-60JC3T1 1TB                                  | 1         | 1      | 5.26%   |
| WDC WD10EARS-00MVWB0 1TB                                  | 1         | 1      | 5.26%   |
| WDC WD Blue SA510 2.5 500GB                               | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD050V 500GB                                 | 1         | 1      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB                           | 1         | 1      | 5.26%   |
| Seagate ST500LM000-1EJ162 500GB                           | 1         | 2      | 5.26%   |
| Seagate ST20000NM007D-3DJ103 20TB                         | 1         | 1      | 5.26%   |
| Seagate ST1000LM035-1RK172 1TB                            | 1         | 1      | 5.26%   |
| Seagate ST1000DM003-1ER162 1TB                            | 1         | 1      | 5.26%   |
| SanDisk SD9SN8W512G1002 512GB SSD                         | 1         | 1      | 5.26%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                       | 1         | 2      | 5.26%   |
| Samsung Electronics MZVLQ256HBJD-00BH1 256GB              | 1         | 1      | 5.26%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 256GB | 1         | 1      | 5.26%   |
| Micron Technology 1100 SATA 512GB SSD                     | 1         | 1      | 5.26%   |
| Intel SSDSCKKF256H6 SATA 256GB                            | 1         | 1      | 5.26%   |
| Intel SSDSC2BB480G7 480GB                                 | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 6         | 8      | 31.58%  |
| Seagate               | 5         | 6      | 26.32%  |
| SanDisk               | 2         | 3      | 10.53%  |
| Intel                 | 2         | 2      | 10.53%  |
| Toshiba               | 1         | 1      | 5.26%   |
| Samsung Electronics   | 1         | 1      | 5.26%   |
| Realtek Semiconductor | 1         | 1      | 5.26%   |
| Micron Technology     | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 7      | 45.45%  |
| Seagate | 5         | 6      | 45.45%  |
| Toshiba | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 14     | 56.25%  |
| SSD  | 5         | 7      | 31.25%  |
| NVMe | 2         | 2      | 12.5%   |

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
| Detected | 186       | 333    | 58.86%  |
| Works    | 115       | 186    | 36.39%  |
| Malfunc  | 15        | 23     | 4.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 191       | 49.35%  |
| Samsung Electronics            | 57        | 14.73%  |
| AMD                            | 17        | 4.39%   |
| SanDisk                        | 16        | 4.13%   |
| Micron Technology              | 15        | 3.88%   |
| Phison Electronics             | 14        | 3.62%   |
| Kingston Technology Company    | 12        | 3.1%    |
| SK hynix                       | 10        | 2.58%   |
| Micron/Crucial Technology      | 9         | 2.33%   |
| ASMedia Technology             | 6         | 1.55%   |
| Toshiba America Info Systems   | 5         | 1.29%   |
| Silicon Motion                 | 5         | 1.29%   |
| Realtek Semiconductor          | 3         | 0.78%   |
| LSI Logic / Symbios Logic      | 3         | 0.78%   |
| ADATA Technology               | 3         | 0.78%   |
| Shenzhen Longsys Electronics   | 2         | 0.52%   |
| Nvidia                         | 2         | 0.52%   |
| Marvell Technology Group       | 2         | 0.52%   |
| KIOXIA                         | 2         | 0.52%   |
| JMicron Technology             | 2         | 0.52%   |
| Broadcom / LSI                 | 2         | 0.52%   |
| VIA Technologies               | 1         | 0.26%   |
| Solidigm                       | 1         | 0.26%   |
| Solid State Storage Technology | 1         | 0.26%   |
| Seagate Technology             | 1         | 0.26%   |
| OCZ Technology Group           | 1         | 0.26%   |
| O2 Micro                       | 1         | 0.26%   |
| Lite-On Technology             | 1         | 0.26%   |
| Lenovo                         | 1         | 0.26%   |
| Apple                          | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 4.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 4.33%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 18        | 4.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 4.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12        | 2.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 2.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 2.88%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 2.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 2.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 9         | 2.16%   |
| Phison E12 NVMe Controller                                                     | 8         | 1.92%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 1.68%   |
| Intel SSD 660P Series                                                          | 7         | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 1.68%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 6         | 1.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 1.44%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 1.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 1.44%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 6         | 1.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.2%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 4         | 0.96%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 0.96%   |
| Micron 2550 NVMe SSD (DRAM-less)                                               | 4         | 0.96%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 4         | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 0.96%   |
| AMD 600 Series Chipset SATA Controller                                         | 4         | 0.96%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 3         | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 0.72%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 3         | 0.72%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 3         | 0.72%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 3         | 0.72%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 3         | 0.72%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 3         | 0.72%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 0.72%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 163       | 43.01%  |
| NVMe | 161       | 42.48%  |
| RAID | 41        | 10.82%  |
| IDE  | 10        | 2.64%   |
| SAS  | 3         | 0.79%   |
| SCSI | 1         | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 244       | 81.88%  |
| AMD      | 51        | 17.11%  |
| Qualcomm | 1         | 0.34%   |
| ARM      | 1         | 0.34%   |
| Unknown  | 1         | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Custom APU 0405                     | 10        | 3.36%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 9         | 3.02%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 6         | 2.01%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 6         | 2.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 5         | 1.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 1.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 5         | 1.68%   |
| Intel 12th Gen Core i7-12700H           | 5         | 1.68%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 5         | 1.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 1.34%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.34%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 4         | 1.34%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 1.34%   |
| Intel 13th Gen Core i7-1355U            | 4         | 1.34%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 4         | 1.34%   |
| Intel Xeon CPU E5620 @ 2.40GHz          | 3         | 1.01%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 3         | 1.01%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 1.01%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 3         | 1.01%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.01%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 3         | 1.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 1.01%   |
| Intel Core i5-9400T CPU @ 1.80GHz       | 3         | 1.01%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 3         | 1.01%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 1.01%   |
| Intel Core i3-10110U CPU @ 2.10GHz      | 3         | 1.01%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 3         | 1.01%   |
| Intel Core i9-10885H CPU @ 2.40GHz      | 2         | 0.67%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 2         | 0.67%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 2         | 0.67%   |
| Intel Core i7-4790S CPU @ 3.20GHz       | 2         | 0.67%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 2         | 0.67%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 2         | 0.67%   |
| Intel Core i7-10875H CPU @ 2.30GHz      | 2         | 0.67%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 2         | 0.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.67%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 2         | 0.67%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 2         | 0.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 82        | 27.52%  |
| Intel Core i5           | 69        | 23.15%  |
| Other                   | 60        | 20.13%  |
| AMD Ryzen 7             | 13        | 4.36%   |
| Intel Core i3           | 12        | 4.03%   |
| AMD Ryzen 9             | 10        | 3.36%   |
| AMD Ryzen 5             | 9         | 3.02%   |
| Intel Xeon              | 8         | 2.68%   |
| Intel Celeron           | 7         | 2.35%   |
| Intel Core 2 Duo        | 6         | 2.01%   |
| Intel Core i9           | 5         | 1.68%   |
| Intel Atom              | 2         | 0.67%   |
| AMD Ryzen Threadripper  | 2         | 0.67%   |
| AMD Ryzen 7 PRO         | 2         | 0.67%   |
| Intel Xeon Silver       | 1         | 0.34%   |
| Intel Pentium Dual-Core | 1         | 0.34%   |
| Intel Pentium 4         | 1         | 0.34%   |
| Intel Pentium           | 1         | 0.34%   |
| Intel Core m5           | 1         | 0.34%   |
| Intel Core 2 Quad       | 1         | 0.34%   |
| Intel Core              | 1         | 0.34%   |
| Intel Celeron M         | 1         | 0.34%   |
| AMD Sempron             | 1         | 0.34%   |
| AMD Ryzen 3             | 1         | 0.34%   |
| AMD A6                  | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 105       | 35.23%  |
| 2       | 91        | 30.54%  |
| 8       | 38        | 12.75%  |
| 6       | 28        | 9.4%    |
| 14      | 10        | 3.36%   |
| 10      | 8         | 2.68%   |
| 12      | 6         | 2.01%   |
| 16      | 5         | 1.68%   |
| 1       | 4         | 1.34%   |
| 64      | 1         | 0.34%   |
| 24      | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 293       | 98.32%  |
| 2       | 4         | 1.34%   |
| Unknown | 1         | 0.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 251       | 84.23%  |
| 1       | 46        | 15.44%  |
| Unknown | 1         | 0.34%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 294       | 98.66%  |
| 32-bit         | 2         | 0.67%   |
| 64-bit         | 1         | 0.34%   |
| Unknown        | 1         | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 156       | 50.81%  |
| 0x306a9    | 12        | 3.91%   |
| 0x406e3    | 10        | 3.26%   |
| 0x806ec    | 9         | 2.93%   |
| 0x906ea    | 8         | 2.61%   |
| 0x806c1    | 8         | 2.61%   |
| 0x40651    | 8         | 2.61%   |
| 0x306c3    | 7         | 2.28%   |
| 0x206a7    | 7         | 2.28%   |
| 0x906e9    | 5         | 1.63%   |
| 0x806ea    | 5         | 1.63%   |
| 0x806e9    | 5         | 1.63%   |
| 0x906a3    | 4         | 1.3%    |
| 0xb06a3    | 3         | 0.98%   |
| 0xa0652    | 3         | 0.98%   |
| 0x906ed    | 3         | 0.98%   |
| 0x506e3    | 3         | 0.98%   |
| 0x206c2    | 3         | 0.98%   |
| 0x20655    | 3         | 0.98%   |
| 0x0a50000c | 3         | 0.98%   |
| 0xb0671    | 2         | 0.65%   |
| 0xa0655    | 2         | 0.65%   |
| 0x806eb    | 2         | 0.65%   |
| 0x6fd      | 2         | 0.65%   |
| 0x306f2    | 2         | 0.65%   |
| 0x306d4    | 2         | 0.65%   |
| 0x106e5    | 2         | 0.65%   |
| 0x1067a    | 2         | 0.65%   |
| 0x08608103 | 2         | 0.65%   |
| 0x08600104 | 2         | 0.65%   |
| 0x08108109 | 2         | 0.65%   |
| 0xf29      | 1         | 0.33%   |
| 0x806d1    | 1         | 0.33%   |
| 0x706a1    | 1         | 0.33%   |
| 0x6fb      | 1         | 0.33%   |
| 0x6e8      | 1         | 0.33%   |
| 0x506c9    | 1         | 0.33%   |
| 0x406c4    | 1         | 0.33%   |
| 0x406c3    | 1         | 0.33%   |
| 0x306e4    | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 64        | 21.48%  |
| Unknown           | 42        | 14.09%  |
| Haswell           | 29        | 9.73%   |
| Skylake           | 25        | 8.39%   |
| TigerLake         | 18        | 6.04%   |
| IvyBridge         | 18        | 6.04%   |
| Zen 3             | 15        | 5.03%   |
| SandyBridge       | 14        | 4.7%    |
| CometLake         | 11        | 3.69%   |
| Alderlake Hybrid  | 11        | 3.69%   |
| Westmere          | 8         | 2.68%   |
| Broadwell         | 6         | 2.01%   |
| Zen 2             | 5         | 1.68%   |
| Penryn            | 5         | 1.68%   |
| Zen+              | 4         | 1.34%   |
| Silvermont        | 4         | 1.34%   |
| IceLake           | 3         | 1.01%   |
| Goldmont plus     | 3         | 1.01%   |
| Core              | 3         | 1.01%   |
| Nehalem           | 2         | 0.67%   |
| Zen               | 1         | 0.34%   |
| Piledriver        | 1         | 0.34%   |
| P6                | 1         | 0.34%   |
| NetBurst          | 1         | 0.34%   |
| Meteorlake Hybrid | 1         | 0.34%   |
| K8 Hammer         | 1         | 0.34%   |
| Gracemont         | 1         | 0.34%   |
| Goldmont          | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 200       | 51.55%  |
| Nvidia                     | 118       | 30.41%  |
| AMD                        | 68        | 17.53%  |
| Matrox Electronics Systems | 1         | 0.26%   |
| ASPEED Technology          | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 4.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 3.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 3.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 3.3%    |
| Intel HD Graphics 620                                                                    | 10        | 2.54%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 2.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 2.54%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 10        | 2.54%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 9         | 2.28%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 2.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 2.03%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 2.03%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 1.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.78%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 6         | 1.52%   |
| Nvidia GM108M [GeForce MX130]                                                            | 5         | 1.27%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.27%   |
| Intel HD Graphics 530                                                                    | 5         | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.27%   |
| AMD Lucienne                                                                             | 5         | 1.27%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.02%   |
| Intel HD Graphics 630                                                                    | 4         | 1.02%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.02%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.02%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 4         | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.76%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.76%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.76%   |
| AMD Raphael                                                                              | 3         | 0.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.51%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 2         | 0.51%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 114       | 38.13%  |
| Intel + Nvidia     | 67        | 22.41%  |
| 1 x AMD            | 42        | 14.05%  |
| 1 x Nvidia         | 41        | 13.71%  |
| Intel + AMD        | 16        | 5.35%   |
| AMD + Nvidia       | 7         | 2.34%   |
| Other              | 3         | 1%      |
| 2 x AMD            | 3         | 1%      |
| 2 x Nvidia         | 2         | 0.67%   |
| 2 x Intel          | 1         | 0.33%   |
| 1 x Matrox         | 1         | 0.33%   |
| Intel + 2 x Nvidia | 1         | 0.33%   |
| 1 x ASPEED         | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 224       | 74.67%  |
| Proprietary | 56        | 18.67%  |
| Unknown     | 20        | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 196       | 64.9%   |
| 1.01-2.0   | 34        | 11.26%  |
| 0.01-0.5   | 21        | 6.95%   |
| 3.01-4.0   | 16        | 5.3%    |
| 7.01-8.0   | 9         | 2.98%   |
| 8.01-16.0  | 8         | 2.65%   |
| 0.51-1.0   | 6         | 1.99%   |
| 5.01-6.0   | 5         | 1.66%   |
| 16.01-24.0 | 3         | 0.99%   |
| 2.01-3.0   | 2         | 0.66%   |
| 32.01-64.0 | 1         | 0.33%   |
| 4.01-5.0   | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 46        | 14.42%  |
| BOE                     | 39        | 12.23%  |
| Samsung Electronics     | 38        | 11.91%  |
| Chimei Innolux          | 35        | 10.97%  |
| LG Display              | 29        | 9.09%   |
| Goldstar                | 17        | 5.33%   |
| Hewlett-Packard         | 12        | 3.76%   |
| Dell                    | 10        | 3.13%   |
| Valve                   | 9         | 2.82%   |
| BenQ                    | 9         | 2.82%   |
| Apple                   | 9         | 2.82%   |
| Lenovo                  | 7         | 2.19%   |
| InfoVision              | 6         | 1.88%   |
| Ancor Communications    | 6         | 1.88%   |
| Philips                 | 4         | 1.25%   |
| CSO                     | 4         | 1.25%   |
| ASUSTek Computer        | 4         | 1.25%   |
| ViewSonic               | 3         | 0.94%   |
| Sharp                   | 3         | 0.94%   |
| HKC                     | 3         | 0.94%   |
| Sony                    | 2         | 0.63%   |
| Mi                      | 2         | 0.63%   |
| LGD                     | 2         | 0.63%   |
| LG Philips              | 2         | 0.63%   |
| Chi Mei Optoelectronics | 2         | 0.63%   |
| WBT                     | 1         | 0.31%   |
| TMX                     | 1         | 0.31%   |
| Seiko/Epson             | 1         | 0.31%   |
| RTK                     | 1         | 0.31%   |
| PANDA                   | 1         | 0.31%   |
| Panasonic               | 1         | 0.31%   |
| LG Electronics          | 1         | 0.31%   |
| Hitachi                 | 1         | 0.31%   |
| Hannspree               | 1         | 0.31%   |
| Gigabyte Technology     | 1         | 0.31%   |
| CTX                     | 1         | 0.31%   |
| CMN                     | 1         | 0.31%   |
| Aosiman                 | 1         | 0.31%   |
| AOC                     | 1         | 0.31%   |
| Analogix                | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 9         | 2.77%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 5         | 1.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 3         | 0.92%   |
| Hewlett-Packard ALL-in-One HPN401F 1920x1080 476x268mm 21.5-inch        | 3         | 0.92%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                    | 3         | 0.92%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch          | 3         | 0.92%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch          | 3         | 0.92%   |
| ASUSTek Computer PG32UQ AUS32E1 3840x2160 708x399mm 32.0-inch           | 3         | 0.92%   |
| Sony BM320 SNY050A 1920x1080 708x399mm 32.0-inch                        | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch   | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 2         | 0.62%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch     | 2         | 0.62%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                        | 2         | 0.62%   |
| LGD LCD Monitor 1366x768                                                | 2         | 0.62%   |
| LG Display LCD Monitor LGD0575 1920x1080 309x174mm 14.0-inch            | 2         | 0.62%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch             | 2         | 0.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 0.62%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch            | 2         | 0.62%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch             | 2         | 0.62%   |
| Hewlett-Packard E233 HPN3460 1920x1080 509x286mm 23.0-inch              | 2         | 0.62%   |
| CSO LCD Monitor CSO1603 2560x1600 344x215mm 16.0-inch                   | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 2         | 0.62%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                   | 2         | 0.62%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 2         | 0.62%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                    | 2         | 0.62%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                       | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO272B 3840x2160 293x165mm 13.2-inch          | 2         | 0.62%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                    | 2         | 0.62%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch        | 2         | 0.62%   |
| WBT GOP28UHD144I WBT2800 3840x2160 630x330mm 28.0-inch                  | 1         | 0.31%   |
| ViewSonic VX2718 Series VSCE439 1920x1080 598x336mm 27.0-inch           | 1         | 0.31%   |
| ViewSonic VG2439 SERIES VSCD22B 1920x1080 521x293mm 23.5-inch           | 1         | 0.31%   |
| ViewSonic VA1918wm VSCC821 1440x900 410x256mm 19.0-inch                 | 1         | 0.31%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                 | 1         | 0.31%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                 | 1         | 0.31%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                 | 1         | 0.31%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                 | 1         | 0.31%   |
| Seiko/Epson LCD Monitor 1280x800                                        | 1         | 0.31%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 0.31%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch       | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 140       | 45.31%  |
| 1366x768 (WXGA)   | 59        | 19.09%  |
| 3840x2160 (4K)    | 31        | 10.03%  |
| 2560x1440 (QHD)   | 11        | 3.56%   |
| 800x1280          | 10        | 3.24%   |
| 1920x1200 (WUXGA) | 9         | 2.91%   |
| 1600x900 (HD+)    | 7         | 2.27%   |
| 3440x1440         | 5         | 1.62%   |
| 2880x1800         | 5         | 1.62%   |
| 1280x800 (WXGA)   | 5         | 1.62%   |
| 2560x1600         | 4         | 1.29%   |
| 2560x1080         | 3         | 0.97%   |
| 1440x900 (WXGA+)  | 3         | 0.97%   |
| 3840x1080         | 2         | 0.65%   |
| 2736x1824         | 2         | 0.65%   |
| 2160x1440         | 2         | 0.65%   |
| Unknown           | 2         | 0.65%   |
| 3456x2160         | 1         | 0.32%   |
| 3200x2000         | 1         | 0.32%   |
| 3200x1800 (QHD+)  | 1         | 0.32%   |
| 3072x1920         | 1         | 0.32%   |
| 2880x1920         | 1         | 0.32%   |
| 2304x1440         | 1         | 0.32%   |
| 2240x1400         | 1         | 0.32%   |
| 1920x515          | 1         | 0.32%   |
| 1360x768          | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 84        | 26.33%  |
| 14      | 42        | 13.17%  |
| 13      | 38        | 11.91%  |
| 27      | 15        | 4.7%    |
| 24      | 15        | 4.7%    |
| 23      | 13        | 4.08%   |
| 21      | 12        | 3.76%   |
| Unknown | 12        | 3.76%   |
| 16      | 10        | 3.13%   |
| 12      | 10        | 3.13%   |
| 7       | 9         | 2.82%   |
| 31      | 8         | 2.51%   |
| 11      | 8         | 2.51%   |
| 84      | 4         | 1.25%   |
| 34      | 4         | 1.25%   |
| 20      | 4         | 1.25%   |
| 18      | 4         | 1.25%   |
| 17      | 4         | 1.25%   |
| 32      | 3         | 0.94%   |
| 19      | 3         | 0.94%   |
| 65      | 2         | 0.63%   |
| 41      | 2         | 0.63%   |
| 72      | 1         | 0.31%   |
| 54      | 1         | 0.31%   |
| 52      | 1         | 0.31%   |
| 49      | 1         | 0.31%   |
| 48      | 1         | 0.31%   |
| 46      | 1         | 0.31%   |
| 44      | 1         | 0.31%   |
| 42      | 1         | 0.31%   |
| 40      | 1         | 0.31%   |
| 35      | 1         | 0.31%   |
| 29      | 1         | 0.31%   |
| 28      | 1         | 0.31%   |
| 3       | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 152       | 48.1%   |
| 501-600     | 40        | 12.66%  |
| 201-300     | 38        | 12.03%  |
| 401-500     | 22        | 6.96%   |
| 601-700     | 12        | 3.8%    |
| Unknown     | 12        | 3.8%    |
| 1-100       | 10        | 3.16%   |
| 701-800     | 7         | 2.22%   |
| 1001-1500   | 7         | 2.22%   |
| 351-400     | 6         | 1.9%    |
| 1501-2000   | 5         | 1.58%   |
| 901-1000    | 3         | 0.95%   |
| 801-900     | 2         | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 223       | 77.43%  |
| 16/10   | 30        | 10.42%  |
| Unknown | 11        | 3.82%   |
| 0.67    | 9         | 3.13%   |
| 21/9    | 7         | 2.43%   |
| 3/2     | 3         | 1.04%   |
| 6/5     | 2         | 0.69%   |
| 32/9    | 2         | 0.69%   |
| 3.73    | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 83        | 26.02%  |
| 81-90          | 63        | 19.75%  |
| 201-250        | 29        | 9.09%   |
| 301-350        | 17        | 5.33%   |
| 71-80          | 16        | 5.02%   |
| 351-500        | 16        | 5.02%   |
| 151-200        | 13        | 4.08%   |
| Unknown        | 12        | 3.76%   |
| 61-70          | 10        | 3.13%   |
| 1-40           | 10        | 3.13%   |
| 111-120        | 10        | 3.13%   |
| More than 1000 | 9         | 2.82%   |
| 51-60          | 8         | 2.51%   |
| 501-1000       | 8         | 2.51%   |
| 251-300        | 5         | 1.57%   |
| 121-130        | 5         | 1.57%   |
| 141-150        | 4         | 1.25%   |
| 91-100         | 1         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 111       | 35.81%  |
| 101-120       | 64        | 20.65%  |
| 51-100        | 64        | 20.65%  |
| 161-240       | 40        | 12.9%   |
| More than 240 | 15        | 4.84%   |
| Unknown       | 12        | 3.87%   |
| 1-50          | 4         | 1.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 234       | 77.48%  |
| 2     | 45        | 14.9%   |
| 0     | 19        | 6.29%   |
| 3     | 4         | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 178       | 40.92%  |
| Realtek Semiconductor    | 137       | 31.49%  |
| Qualcomm Atheros         | 27        | 6.21%   |
| Broadcom                 | 23        | 5.29%   |
| MediaTek                 | 15        | 3.45%   |
| TP-Link                  | 7         | 1.61%   |
| Ralink                   | 7         | 1.61%   |
| ASIX Electronics         | 7         | 1.61%   |
| Marvell Technology Group | 6         | 1.38%   |
| Xiaomi                   | 4         | 0.92%   |
| Broadcom Limited         | 4         | 0.92%   |
| Sigma Designs            | 2         | 0.46%   |
| Nvidia                   | 2         | 0.46%   |
| Wilocity                 | 1         | 0.23%   |
| VIA Technologies         | 1         | 0.23%   |
| SILICON Laboratories     | 1         | 0.23%   |
| Sierra Wireless          | 1         | 0.23%   |
| Samsung Electronics      | 1         | 0.23%   |
| Ralink Technology        | 1         | 0.23%   |
| Qualcomm                 | 1         | 0.23%   |
| QinHeng Electronics      | 1         | 0.23%   |
| NetGear                  | 1         | 0.23%   |
| Motorola PCS             | 1         | 0.23%   |
| Microsoft                | 1         | 0.23%   |
| Microchip Technology     | 1         | 0.23%   |
| Lenovo                   | 1         | 0.23%   |
| D-Link                   | 1         | 0.23%   |
| Aquantia                 | 1         | 0.23%   |
| American Megatrends      | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 71        | 13.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 3.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 15        | 2.85%   |
| Intel Wi-Fi 6 AX201                                                    | 14        | 2.66%   |
| Intel Wireless 8260                                                    | 12        | 2.28%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 12        | 2.28%   |
| Intel Wi-Fi 6 AX200                                                    | 12        | 2.28%   |
| Intel Wireless 8265 / 8275                                             | 11        | 2.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 10        | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 1.9%    |
| Intel Wireless 7260                                                    | 10        | 1.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 10        | 1.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 9         | 1.71%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 1.52%   |
| Intel Ethernet Controller I225-V                                       | 7         | 1.33%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 7         | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 6         | 1.14%   |
| Intel Wireless 7265                                                    | 6         | 1.14%   |
| Intel I210 Gigabit Network Connection                                  | 6         | 1.14%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 1.14%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 5         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 5         | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 5         | 0.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 0.95%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 4         | 0.76%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 0.76%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.76%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.76%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 3         | 0.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 3         | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 143       | 52.19%  |
| Realtek Semiconductor    | 51        | 18.61%  |
| Qualcomm Atheros         | 22        | 8.03%   |
| Broadcom                 | 17        | 6.2%    |
| MediaTek                 | 14        | 5.11%   |
| TP-Link                  | 7         | 2.55%   |
| Ralink                   | 7         | 2.55%   |
| Broadcom Limited         | 4         | 1.46%   |
| Marvell Technology Group | 3         | 1.09%   |
| Wilocity                 | 1         | 0.36%   |
| Sierra Wireless          | 1         | 0.36%   |
| Ralink Technology        | 1         | 0.36%   |
| NetGear                  | 1         | 0.36%   |
| Microsoft                | 1         | 0.36%   |
| D-Link                   | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 15        | 5.43%   |
| Intel Wi-Fi 6 AX201                                            | 14        | 5.07%   |
| Intel Wireless 8260                                            | 12        | 4.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 12        | 4.35%   |
| Intel Wi-Fi 6 AX200                                            | 12        | 4.35%   |
| Intel Wireless 8265 / 8275                                     | 11        | 3.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 3.62%   |
| Intel Wireless 7260                                            | 10        | 3.62%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 10        | 3.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 3.26%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 2.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 2.17%   |
| Intel Wireless 7265                                            | 6         | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 1.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 1.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 1.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 1.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.81%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 3         | 1.09%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 1.09%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 3         | 1.09%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 3         | 1.09%   |
| Intel Wireless 3165                                            | 3         | 1.09%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 3         | 1.09%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.09%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.09%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3         | 1.09%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.72%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 0.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 0.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.72%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 0.72%   |
| Intel Wireless 3160                                            | 2         | 0.72%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 107       | 45.92%  |
| Intel                    | 86        | 36.91%  |
| Broadcom                 | 8         | 3.43%   |
| Qualcomm Atheros         | 7         | 3%      |
| ASIX Electronics         | 7         | 3%      |
| Xiaomi                   | 4         | 1.72%   |
| Marvell Technology Group | 3         | 1.29%   |
| Nvidia                   | 2         | 0.86%   |
| VIA Technologies         | 1         | 0.43%   |
| Samsung Electronics      | 1         | 0.43%   |
| Qualcomm                 | 1         | 0.43%   |
| QinHeng Electronics      | 1         | 0.43%   |
| Motorola PCS             | 1         | 0.43%   |
| MediaTek                 | 1         | 0.43%   |
| Lenovo                   | 1         | 0.43%   |
| Aquantia                 | 1         | 0.43%   |
| American Megatrends      | 1         | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 71        | 28.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 6.91%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 4.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 3.66%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 3.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 3.25%   |
| Intel Ethernet Controller I225-V                                       | 7         | 2.85%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 2.85%   |
| Intel I210 Gigabit Network Connection                                  | 6         | 2.44%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 2.44%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 2.03%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 4         | 1.63%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 1.63%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.63%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 1.22%   |
| Intel Ethernet Controller I226-V                                       | 3         | 1.22%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.22%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.22%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.81%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.81%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.81%   |
| Intel Ethernet Connection (2) I218-V                                   | 2         | 0.81%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.81%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 0.81%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.41%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.41%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.41%   |
| Qualcomm Airtel 4G                                                     | 1         | 0.41%   |
| QinHeng USB 10/100 LAN                                                 | 1         | 0.41%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 259       | 53.96%  |
| Ethernet | 217       | 45.21%  |
| Modem    | 4         | 0.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 215       | 70.49%  |
| Ethernet | 90        | 29.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 162       | 54.18%  |
| 1     | 121       | 40.47%  |
| 3     | 9         | 3.01%   |
| 0     | 5         | 1.67%   |
| 8     | 1         | 0.33%   |
| 4     | 1         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 218       | 71.95%  |
| Yes  | 85        | 28.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 121       | 51.93%  |
| Realtek Semiconductor           | 24        | 10.3%   |
| IMC Networks                    | 19        | 8.15%   |
| Qualcomm Atheros Communications | 12        | 5.15%   |
| Apple                           | 8         | 3.43%   |
| Foxconn / Hon Hai               | 7         | 3%      |
| Cambridge Silicon Radio         | 7         | 3%      |
| Broadcom                        | 6         | 2.58%   |
| Ralink                          | 5         | 2.15%   |
| ASUSTek Computer                | 5         | 2.15%   |
| Toshiba                         | 4         | 1.72%   |
| MediaTek                        | 3         | 1.29%   |
| Marvell Semiconductor           | 3         | 1.29%   |
| Lite-On Technology              | 3         | 1.29%   |
| Hewlett-Packard                 | 2         | 0.86%   |
| Dell                            | 2         | 0.86%   |
| TP-Link                         | 1         | 0.43%   |
| Unknown                         | 1         | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 35        | 14.96%  |
| Intel AX201 Bluetooth                                 | 25        | 10.68%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 23        | 9.83%   |
| Realtek Bluetooth Radio                               | 14        | 5.98%   |
| Intel AX200 Bluetooth                                 | 12        | 5.13%   |
| Intel AX211 Bluetooth                                 | 11        | 4.7%    |
| Intel AX210 Bluetooth                                 | 11        | 4.7%    |
| IMC Networks Bluetooth Radio                          | 11        | 4.7%    |
| IMC Networks Wireless_Device                          | 8         | 3.42%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7         | 2.99%   |
| Realtek  Bluetooth 4.2 Adapter                        | 6         | 2.56%   |
| Ralink RT3290 Bluetooth                               | 5         | 2.14%   |
| Qualcomm Atheros  Bluetooth Device                    | 5         | 2.14%   |
| Apple Bluetooth USB Host Controller                   | 4         | 1.71%   |
| MediaTek Wireless_Device                              | 3         | 1.28%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 1.28%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 3         | 1.28%   |
| Toshiba Bluetooth USB Host Controller                 | 2         | 0.85%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 2         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2         | 0.85%   |
| Marvell Bluetooth and Wireless LAN Composite          | 2         | 0.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 2         | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                      | 2         | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2         | 0.85%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2         | 0.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 2         | 0.85%   |
| TP-Link TP-Link Bluetooth USB Adapter                 | 1         | 0.43%   |
| Toshiba RT Bluetooth Radio                            | 1         | 0.43%   |
| Toshiba Integrated Bluetooth HCI                      | 1         | 0.43%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.43%   |
| Realtek 802.11ac WLAN Adapter                         | 1         | 0.43%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1         | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1         | 0.43%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 0.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1         | 0.43%   |
| Lite-On Bluetooth Device                              | 1         | 0.43%   |
| Lite-On Atheros AR3012 Bluetooth                      | 1         | 0.43%   |
| Foxconn / Hon Hai Wireless_Device                     | 1         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 240       | 59.11%  |
| Nvidia                   | 78        | 19.21%  |
| AMD                      | 59        | 14.53%  |
| Logitech                 | 5         | 1.23%   |
| ASUSTek Computer         | 5         | 1.23%   |
| SteelSeries ApS          | 3         | 0.74%   |
| Lenovo                   | 3         | 0.74%   |
| JMTek                    | 3         | 0.74%   |
| Razer USA                | 2         | 0.49%   |
| Solid State Logic        | 1         | 0.25%   |
| Samsung Electronics      | 1         | 0.25%   |
| Realtek Semiconductor    | 1         | 0.25%   |
| Micro Star International | 1         | 0.25%   |
| Hewlett-Packard          | 1         | 0.25%   |
| Griffin Technology       | 1         | 0.25%   |
| Dell                     | 1         | 0.25%   |
| Apogee Electronics       | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 33        | 7.04%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 30        | 6.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 3.84%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 18        | 3.84%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 17        | 3.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 3.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 15        | 3.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 3.2%    |
| Intel 8 Series HD Audio Controller                                         | 15        | 3.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 14        | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 2.77%   |
| Nvidia GA106 High Definition Audio Controller                              | 11        | 2.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 11        | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 2.13%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 1.92%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 1.71%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 1.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 1.49%   |
| Nvidia TU104 HD Audio Controller                                           | 6         | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 1.28%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 6         | 1.28%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 1.07%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.07%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 1.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5         | 1.07%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 1.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.85%   |
| Nvidia GA107 High Definition Audio Controller                              | 4         | 0.85%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.85%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.85%   |
| ASUSTek Computer USB Audio                                                 | 4         | 0.85%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.64%   |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 0.64%   |
| Nvidia AD102 High Definition Audio Controller                              | 3         | 0.64%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 56        | 32.94%  |
| SK hynix            | 30        | 17.65%  |
| Micron Technology   | 27        | 15.88%  |
| Crucial             | 16        | 9.41%   |
| Kingston            | 10        | 5.88%   |
| Corsair             | 10        | 5.88%   |
| Unknown             | 5         | 2.94%   |
| Ramaxel Technology  | 4         | 2.35%   |
| Timetec             | 2         | 1.18%   |
| G.Skill             | 2         | 1.18%   |
| Wilk                | 1         | 0.59%   |
| Nanya Technology    | 1         | 0.59%   |
| Lexar               | 1         | 0.59%   |
| Innodisk            | 1         | 0.59%   |
| Gold Key            | 1         | 0.59%   |
| A-DATA Technology   | 1         | 0.59%   |
| 4ea5                | 1         | 0.59%   |
| Unknown             | 1         | 0.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s     | 4         | 2.14%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s    | 3         | 1.6%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s     | 3         | 1.6%    |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s      | 3         | 1.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2         | 1.07%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 1.07%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s  | 2         | 1.07%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 1.07%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s    | 2         | 1.07%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s    | 2         | 1.07%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 1.07%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 1.07%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s   | 2         | 1.07%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 2         | 1.07%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s   | 2         | 1.07%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s      | 2         | 1.07%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s | 2         | 1.07%   |
| Wilk RAM W-HK32S32O 32GB SODIMM DDR4 3200MT/s             | 1         | 0.53%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                 | 1         | 0.53%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s            | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.53%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 1         | 0.53%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                | 1         | 0.53%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.53%   |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.53%   |
| Timetec RAM S8G-1600 8GB Chip DDR3 1600MT/s               | 1         | 0.53%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 1         | 0.53%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 0.53%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s              | 1         | 0.53%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1333MT/s      | 1         | 0.53%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s    | 1         | 0.53%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 0.53%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1450MT/s      | 1         | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 0.53%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM DDR3 1333MT/s   | 1         | 0.53%   |
| SK hynix RAM HMT125S6TFR8C-G7 2GB SODIMM DDR3 1067MT/s    | 1         | 0.53%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s    | 1         | 0.53%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s    | 1         | 0.53%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s   | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 84        | 59.57%  |
| DDR3    | 30        | 21.28%  |
| DDR5    | 10        | 7.09%   |
| LPDDR4  | 5         | 3.55%   |
| LPDDR5  | 4         | 2.84%   |
| LPDDR3  | 4         | 2.84%   |
| DDR2    | 3         | 2.13%   |
| Unknown | 1         | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 97        | 66.9%   |
| DIMM         | 27        | 18.62%  |
| Row Of Chips | 18        | 12.41%  |
| Chip         | 2         | 1.38%   |
| Unknown      | 1         | 0.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 70        | 43.75%  |
| 16384 | 37        | 23.13%  |
| 4096  | 29        | 18.13%  |
| 2048  | 11        | 6.88%   |
| 32768 | 9         | 5.63%   |
| 65536 | 2         | 1.25%   |
| 49152 | 1         | 0.63%   |
| 1024  | 1         | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 41        | 25.79%  |
| 2667  | 31        | 19.5%   |
| 1600  | 18        | 11.32%  |
| 2400  | 11        | 6.92%   |
| 2133  | 11        | 6.92%   |
| 4800  | 6         | 3.77%   |
| 1333  | 5         | 3.14%   |
| 6400  | 3         | 1.89%   |
| 5600  | 3         | 1.89%   |
| 4267  | 3         | 1.89%   |
| 1334  | 3         | 1.89%   |
| 7500  | 2         | 1.26%   |
| 3400  | 2         | 1.26%   |
| 3000  | 2         | 1.26%   |
| 1867  | 2         | 1.26%   |
| 1866  | 2         | 1.26%   |
| 1067  | 2         | 1.26%   |
| 667   | 2         | 1.26%   |
| 6000  | 1         | 0.63%   |
| 4266  | 1         | 0.63%   |
| 3800  | 1         | 0.63%   |
| 3733  | 1         | 0.63%   |
| 3600  | 1         | 0.63%   |
| 3466  | 1         | 0.63%   |
| 2933  | 1         | 0.63%   |
| 2666  | 1         | 0.63%   |
| 1450  | 1         | 0.63%   |
| 800   | 1         | 0.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 40%     |
| Canon              | 2         | 40%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| HP Deskjet F2280 series   | 1         | 20%     |
| HP DeskJet 2300 series    | 1         | 20%     |
| Canon TR150 series        | 1         | 20%     |
| Canon PIXMA MG3600 Series | 1         | 20%     |
| Brother MFC-9330CDW       | 1         | 20%     |

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
| Chicony Electronics                    | 58        | 26.85%  |
| IMC Networks                           | 22        | 10.19%  |
| Microdia                               | 14        | 6.48%   |
| Bison Electronics                      | 14        | 6.48%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 5.56%   |
| Syntek                                 | 10        | 4.63%   |
| Realtek Semiconductor                  | 10        | 4.63%   |
| Luxvisions Innotech Limited            | 10        | 4.63%   |
| Apple                                  | 10        | 4.63%   |
| Sunplus Innovation Technology          | 9         | 4.17%   |
| Quanta                                 | 8         | 3.7%    |
| Lite-On Technology                     | 5         | 2.31%   |
| Samsung Electronics                    | 4         | 1.85%   |
| Acer                                   | 4         | 1.85%   |
| Sonix Technology                       | 3         | 1.39%   |
| Ricoh                                  | 3         | 1.39%   |
| Microsoft                              | 3         | 1.39%   |
| Alcor Micro                            | 3         | 1.39%   |
| Suyin                                  | 2         | 0.93%   |
| Logitech                               | 2         | 0.93%   |
| Creative Technology                    | 2         | 0.93%   |
| Z-Star Microelectronics                | 1         | 0.46%   |
| Shinetech                              | 1         | 0.46%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.46%   |
| Ruision                                | 1         | 0.46%   |
| LG Electronics                         | 1         | 0.46%   |
| Lenovo                                 | 1         | 0.46%   |
| KYE Systems (Mouse Systems)            | 1         | 0.46%   |
| Google                                 | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 25        | 11.52%  |
| IMC Networks USB2.0 HD UVC WebCam                               | 10        | 4.61%   |
| Syntek Integrated Camera                                        | 9         | 4.15%   |
| Microdia Integrated_Webcam_HD                                   | 8         | 3.69%   |
| IMC Networks Integrated Camera                                  | 6         | 2.76%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                              | 6         | 2.76%   |
| Sunplus Integrated_Webcam_HD                                    | 5         | 2.3%    |
| Chicony Integrated Camera (1280x720@30)                         | 5         | 2.3%    |
| Samsung Galaxy series, misc. (MTP mode)                         | 4         | 1.84%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 4         | 1.84%   |
| Bison Integrated Camera                                         | 4         | 1.84%   |
| Realtek Integrated_Webcam_HD                                    | 3         | 1.38%   |
| Realtek HP Truevision HD                                        | 3         | 1.38%   |
| Quanta HP TrueVision HD Camera                                  | 3         | 1.38%   |
| Lite-On HP Wide Vision HD Camera                                | 3         | 1.38%   |
| Chicony EasyCamera                                              | 3         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 3         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 3         | 1.38%   |
| Alcor Micro USB 2.0 Camera                                      | 3         | 1.38%   |
| Sunplus HP HD Webcam [Fixed]                                    | 2         | 0.92%   |
| Sonix USB2.0 HD UVC WebCam                                      | 2         | 0.92%   |
| Ricoh HD Webcam                                                 | 2         | 0.92%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 2         | 0.92%   |
| Microdia Integrated Webcam                                      | 2         | 0.92%   |
| Luxvisions Innotech Limited Integrated Camera                   | 2         | 0.92%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 2         | 0.92%   |
| Logitech Webcam C270                                            | 2         | 0.92%   |
| Lite-On HP HD Camera                                            | 2         | 0.92%   |
| Chicony TOSHIBA Web Camera - HD                                 | 2         | 0.92%   |
| Chicony TOSHIBA Web Camera - FHD                                | 2         | 0.92%   |
| Chicony Lenovo EasyCamera                                       | 2         | 0.92%   |
| Chicony HP Wide Vision HD Camera                                | 2         | 0.92%   |
| Chicony HP Truevision HD                                        | 2         | 0.92%   |
| Chicony HP HD Webcam [Fixed]                                    | 2         | 0.92%   |
| Chicony HP HD Webcam                                            | 2         | 0.92%   |
| Chicony HD WebCam                                               | 2         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam             | 2         | 0.92%   |
| Bison SunplusIT Integrated Camera                               | 2         | 0.92%   |
| Apple Built-in iSight                                           | 2         | 0.92%   |
| Acer BisonCam,NB Pro                                            | 2         | 0.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 28        | 42.42%  |
| Validity Sensors                   | 21        | 31.82%  |
| Elan Microelectronics              | 7         | 10.61%  |
| Shenzhen Goodix Technology         | 6         | 9.09%   |
| STMicroelectronics                 | 2         | 3.03%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.52%   |
| LighTuning Technology              | 1         | 1.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 7         | 10.61%  |
| Elan ELAN:ARM-M4                                                | 7         | 10.61%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 6         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 5         | 7.58%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 4.55%   |
| Synaptics UWP WBDI Device                                       | 3         | 4.55%   |
| Synaptics UWP WBDI                                              | 3         | 4.55%   |
| Synaptics Prometheus Fingerprint Reader                         | 3         | 4.55%   |
| Shenzhen Goodix  Fingerprint Device                             | 3         | 4.55%   |
| Shenzhen Goodix Fingerprint Reader                              | 3         | 4.55%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 3.03%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 2         | 3.03%   |
| Validity Sensors VFS491                                         | 2         | 3.03%   |
| Synaptics WBDI                                                  | 2         | 3.03%   |
| Synaptics Fingerprint reader [HP G6]                            | 2         | 3.03%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 3.03%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.52%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 1.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.52%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.52%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.52%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 1         | 1.52%   |
| Synaptics TouchPad                                              | 1         | 1.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 1.52%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 1.52%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.52%   |
| LighTuning Fingerprint Sensor                                   | 1         | 1.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 5         | 45.45%  |
| Broadcom    | 4         | 36.36%  |
| Upek        | 1         | 9.09%   |
| Aktiv       | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 45.45%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 18.18%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom 5880                                                                | 1         | 9.09%   |
| Aktiv Rutoken lite                                                           | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 164       | 53.77%  |
| 1     | 103       | 33.77%  |
| 2     | 29        | 9.51%   |
| 3     | 9         | 2.95%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 63        | 35.2%   |
| Graphics card            | 43        | 24.02%  |
| Net/wireless             | 21        | 11.73%  |
| Multimedia controller    | 13        | 7.26%   |
| Chipcard                 | 9         | 5.03%   |
| Camera                   | 9         | 5.03%   |
| Communication controller | 5         | 2.79%   |
| Bluetooth                | 5         | 2.79%   |
| Unassigned class         | 3         | 1.68%   |
| Sound                    | 3         | 1.68%   |
| Wireless                 | 2         | 1.12%   |
| Net/ethernet             | 1         | 0.56%   |
| Modem                    | 1         | 0.56%   |
| Card reader              | 1         | 0.56%   |

