MX 21 - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX_21/Desktop/README.md) and [notebooks](/Dist/MX_21/Notebook/README.md).

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

Total: 413

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3190               | Notebook    | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [e812a255a4](https://linux-hardware.org/?probe=e812a255a4) | May 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [539369db0e](https://linux-hardware.org/?probe=539369db0e) | Apr 28, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [014215365a](https://linux-hardware.org/?probe=014215365a) | Apr 27, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [4939e609de](https://linux-hardware.org/?probe=4939e609de) | Apr 24, 2023 |
| HP            | G42                         | Notebook    | [58b0a0981e](https://linux-hardware.org/?probe=58b0a0981e) | Apr 23, 2023 |
| HP            | 090Ch                       | Desktop     | [01d609bbab](https://linux-hardware.org/?probe=01d609bbab) | Apr 23, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [acb9cde3d7](https://linux-hardware.org/?probe=acb9cde3d7) | Apr 23, 2023 |
| Gateway       | DX4860                      | Desktop     | [5583641f1b](https://linux-hardware.org/?probe=5583641f1b) | Apr 22, 2023 |
| Compal        | HEL81I                      | Notebook    | [426788b00c](https://linux-hardware.org/?probe=426788b00c) | Apr 22, 2023 |
| Google        | Akali 360                   | Notebook    | [2d18714bb2](https://linux-hardware.org/?probe=2d18714bb2) | Apr 20, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1B30... | Notebook    | [c0207e5f9a](https://linux-hardware.org/?probe=c0207e5f9a) | Apr 19, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [843dd1e105](https://linux-hardware.org/?probe=843dd1e105) | Apr 18, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [c271ba95b9](https://linux-hardware.org/?probe=c271ba95b9) | Apr 16, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [494fc3e648](https://linux-hardware.org/?probe=494fc3e648) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [aa571700ad](https://linux-hardware.org/?probe=aa571700ad) | Apr 13, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | Notebook    | [3d53b9ee9e](https://linux-hardware.org/?probe=3d53b9ee9e) | Apr 12, 2023 |
| HP            | 3646h                       | Desktop     | [c36653d824](https://linux-hardware.org/?probe=c36653d824) | Apr 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c2a70674ac](https://linux-hardware.org/?probe=c2a70674ac) | Apr 10, 2023 |
| Lenovo        | ThinkPad X220 4290WC7       | Notebook    | [07ed4faaa0](https://linux-hardware.org/?probe=07ed4faaa0) | Apr 10, 2023 |
| HP            | 18E5                        | Desktop     | [441d2678ff](https://linux-hardware.org/?probe=441d2678ff) | Apr 07, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [aea33c89a1](https://linux-hardware.org/?probe=aea33c89a1) | Apr 05, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [86d8d7f80f](https://linux-hardware.org/?probe=86d8d7f80f) | Apr 05, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a1fa664431](https://linux-hardware.org/?probe=a1fa664431) | Apr 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9a5c9ee256](https://linux-hardware.org/?probe=9a5c9ee256) | Apr 02, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [ef684c34bb](https://linux-hardware.org/?probe=ef684c34bb) | Mar 28, 2023 |
| HP            | 3029h                       | Desktop     | [153b913406](https://linux-hardware.org/?probe=153b913406) | Mar 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [20d8516896](https://linux-hardware.org/?probe=20d8516896) | Mar 26, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [498bb39808](https://linux-hardware.org/?probe=498bb39808) | Mar 24, 2023 |
| Unknown       | GB01                        | Desktop     | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [2706ed39b7](https://linux-hardware.org/?probe=2706ed39b7) | Mar 23, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| HP            | 3048h                       | Desktop     | [cd326ce9fa](https://linux-hardware.org/?probe=cd326ce9fa) | Mar 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [978df2886a](https://linux-hardware.org/?probe=978df2886a) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ac5495bdb4](https://linux-hardware.org/?probe=ac5495bdb4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [45d6f54263](https://linux-hardware.org/?probe=45d6f54263) | Mar 19, 2023 |
| Samsung       | 950QDB                      | Convertible | [e16175f1c5](https://linux-hardware.org/?probe=e16175f1c5) | Mar 19, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| Dell          | Latitude E5570              | Notebook    | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [12e9972d5a](https://linux-hardware.org/?probe=12e9972d5a) | Mar 15, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [46cb84be25](https://linux-hardware.org/?probe=46cb84be25) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [9f3f315f73](https://linux-hardware.org/?probe=9f3f315f73) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [42653f8c2a](https://linux-hardware.org/?probe=42653f8c2a) | Mar 14, 2023 |
| MSI           | CSM-H87M-G43                | Desktop     | [9df13e200e](https://linux-hardware.org/?probe=9df13e200e) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [7ccc0f584e](https://linux-hardware.org/?probe=7ccc0f584e) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | Desktop     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| Dell          | Latitude 3190               | Notebook    | [97cc3ffc79](https://linux-hardware.org/?probe=97cc3ffc79) | Mar 13, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [7d35815562](https://linux-hardware.org/?probe=7d35815562) | Mar 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fd0eabacbf](https://linux-hardware.org/?probe=fd0eabacbf) | Mar 08, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | Notebook    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [153652da71](https://linux-hardware.org/?probe=153652da71) | Mar 07, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a3a4113ab4](https://linux-hardware.org/?probe=a3a4113ab4) | Mar 06, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| HP            | 255 G3                      | Notebook    | [9ccab85062](https://linux-hardware.org/?probe=9ccab85062) | Mar 04, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [a84948f124](https://linux-hardware.org/?probe=a84948f124) | Mar 04, 2023 |
| HP            | 8184 X4                     | Desktop     | [b42f6862c7](https://linux-hardware.org/?probe=b42f6862c7) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 620                         | Notebook    | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [5718d685e4](https://linux-hardware.org/?probe=5718d685e4) | Mar 02, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [5fe3c354ff](https://linux-hardware.org/?probe=5fe3c354ff) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [a15227fc75](https://linux-hardware.org/?probe=a15227fc75) | Mar 02, 2023 |
| Dell          | Latitude 3190               | Notebook    | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | 255 G3                      | Notebook    | [49dccf5753](https://linux-hardware.org/?probe=49dccf5753) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [73570a1c9a](https://linux-hardware.org/?probe=73570a1c9a) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [e82b3753f7](https://linux-hardware.org/?probe=e82b3753f7) | Feb 26, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [b6321ee5a4](https://linux-hardware.org/?probe=b6321ee5a4) | Feb 25, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [efc95d4697](https://linux-hardware.org/?probe=efc95d4697) | Feb 25, 2023 |
| Unknown       | 1.0                         | Desktop     | [bab30a1ac1](https://linux-hardware.org/?probe=bab30a1ac1) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [419493491e](https://linux-hardware.org/?probe=419493491e) | Feb 23, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [e386073c5d](https://linux-hardware.org/?probe=e386073c5d) | Feb 23, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [0e9172bdd5](https://linux-hardware.org/?probe=0e9172bdd5) | Feb 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [adc356a0a8](https://linux-hardware.org/?probe=adc356a0a8) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d09dc2494a](https://linux-hardware.org/?probe=d09dc2494a) | Feb 21, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| HP            | ProBook 445 G1              | Notebook    | [bcd5c952f1](https://linux-hardware.org/?probe=bcd5c952f1) | Feb 18, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [351a527308](https://linux-hardware.org/?probe=351a527308) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [aba30bb2d8](https://linux-hardware.org/?probe=aba30bb2d8) | Feb 17, 2023 |
| RTD Embedd... | CMA34CR                     | Notebook    | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [db10d61562](https://linux-hardware.org/?probe=db10d61562) | Feb 16, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [9d060a9cc6](https://linux-hardware.org/?probe=9d060a9cc6) | Feb 15, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [0cbe95253a](https://linux-hardware.org/?probe=0cbe95253a) | Feb 15, 2023 |
| Linx          | LINX1010B                   | Notebook    | [5ca377461f](https://linux-hardware.org/?probe=5ca377461f) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [482c922bbc](https://linux-hardware.org/?probe=482c922bbc) | Feb 14, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [dcb95dba09](https://linux-hardware.org/?probe=dcb95dba09) | Feb 12, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [86103b5293](https://linux-hardware.org/?probe=86103b5293) | Feb 12, 2023 |
| Medion        | P6634                       | Notebook    | [ec0002869f](https://linux-hardware.org/?probe=ec0002869f) | Feb 11, 2023 |
| Medion        | P6634                       | Notebook    | [15c3260ecf](https://linux-hardware.org/?probe=15c3260ecf) | Feb 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [13492935fd](https://linux-hardware.org/?probe=13492935fd) | Feb 09, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [d32909e1a4](https://linux-hardware.org/?probe=d32909e1a4) | Feb 09, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [700f0ded17](https://linux-hardware.org/?probe=700f0ded17) | Feb 08, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [b4c5f2e2de](https://linux-hardware.org/?probe=b4c5f2e2de) | Feb 08, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [11f3874a6f](https://linux-hardware.org/?probe=11f3874a6f) | Feb 07, 2023 |
| HP            | 450                         | Notebook    | [26d3505372](https://linux-hardware.org/?probe=26d3505372) | Feb 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [48f423dfae](https://linux-hardware.org/?probe=48f423dfae) | Feb 05, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [ed6c6cc366](https://linux-hardware.org/?probe=ed6c6cc366) | Feb 05, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [7e94a2328d](https://linux-hardware.org/?probe=7e94a2328d) | Feb 05, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [a2ab102eeb](https://linux-hardware.org/?probe=a2ab102eeb) | Feb 04, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [42e242e6bf](https://linux-hardware.org/?probe=42e242e6bf) | Feb 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [793f52c99a](https://linux-hardware.org/?probe=793f52c99a) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ddb7f53b34](https://linux-hardware.org/?probe=ddb7f53b34) | Feb 03, 2023 |
| ECS           | P4M800PRO-M                 | Desktop     | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
| Intel         | D34010WYK H14771-303        | Desktop     | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [dd017ac78a](https://linux-hardware.org/?probe=dd017ac78a) | Jan 31, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [a32a9ba13a](https://linux-hardware.org/?probe=a32a9ba13a) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [1d28352c0f](https://linux-hardware.org/?probe=1d28352c0f) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| BESSTAR Te... | UM340                       | Desktop     | [77efbbb270](https://linux-hardware.org/?probe=77efbbb270) | Jan 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [e81c0bcfc4](https://linux-hardware.org/?probe=e81c0bcfc4) | Jan 22, 2023 |
| AMI           | Intel                       | Notebook    | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [7671c99c3c](https://linux-hardware.org/?probe=7671c99c3c) | Jan 19, 2023 |
| Dell          | Latitude 3190               | Notebook    | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| HP            | 3396                        | Desktop     | [2085b91098](https://linux-hardware.org/?probe=2085b91098) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [4a07474fa4](https://linux-hardware.org/?probe=4a07474fa4) | Jan 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge 031925U       | Notebook    | [95feaf21b4](https://linux-hardware.org/?probe=95feaf21b4) | Jan 07, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Toshiba       | Satellite M70               | Notebook    | [616dbdfa63](https://linux-hardware.org/?probe=616dbdfa63) | Jan 05, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| Dell          | Latitude 3190               | Notebook    | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6c8ec40821](https://linux-hardware.org/?probe=6c8ec40821) | Dec 25, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [c195f58592](https://linux-hardware.org/?probe=c195f58592) | Dec 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [148add29a4](https://linux-hardware.org/?probe=148add29a4) | Dec 24, 2022 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | Desktop     | [70e125f0d0](https://linux-hardware.org/?probe=70e125f0d0) | Dec 23, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [916375929d](https://linux-hardware.org/?probe=916375929d) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | Notebook    | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [06e7a6dfe7](https://linux-hardware.org/?probe=06e7a6dfe7) | Dec 12, 2022 |
| Dell          | Latitude 3190               | Notebook    | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [a583a55071](https://linux-hardware.org/?probe=a583a55071) | Dec 10, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [2e76f24d6a](https://linux-hardware.org/?probe=2e76f24d6a) | Dec 09, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [36b349ff7f](https://linux-hardware.org/?probe=36b349ff7f) | Dec 08, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6487bbd7b7](https://linux-hardware.org/?probe=6487bbd7b7) | Dec 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | Desktop     | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| Acer          | Aspire ES1-732              | Notebook    | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [057b0039b7](https://linux-hardware.org/?probe=057b0039b7) | Dec 01, 2022 |
| HP            | 304Ah                       | Desktop     | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [8fc84889a5](https://linux-hardware.org/?probe=8fc84889a5) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b47217fa0c](https://linux-hardware.org/?probe=b47217fa0c) | Nov 25, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [3f08c2fb11](https://linux-hardware.org/?probe=3f08c2fb11) | Nov 25, 2022 |
| Sony          | VGN-TZ3RXN_B                | Notebook    | [5986f007c8](https://linux-hardware.org/?probe=5986f007c8) | Nov 22, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| GEO           | GeoFlex 340                 | Convertible | [6e930633c0](https://linux-hardware.org/?probe=6e930633c0) | Nov 18, 2022 |
| Dell          | 0J051K A00                  | Server      | [cb579ef51b](https://linux-hardware.org/?probe=cb579ef51b) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [9884754d7b](https://linux-hardware.org/?probe=9884754d7b) | Nov 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0e09796a40](https://linux-hardware.org/?probe=0e09796a40) | Nov 14, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [cb36e9d15c](https://linux-hardware.org/?probe=cb36e9d15c) | Nov 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0459e9f47e](https://linux-hardware.org/?probe=0459e9f47e) | Nov 06, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [91d85f8376](https://linux-hardware.org/?probe=91d85f8376) | Nov 05, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [9c72952af7](https://linux-hardware.org/?probe=9c72952af7) | Nov 04, 2022 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [c165c40a7e](https://linux-hardware.org/?probe=c165c40a7e) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [9819da96f2](https://linux-hardware.org/?probe=9819da96f2) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| SANTECH       | X170KM-G                    | Notebook    | [073f9a1d24](https://linux-hardware.org/?probe=073f9a1d24) | Nov 01, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Vulcan Ele... | Excursion XB                | Notebook    | [30ceac1216](https://linux-hardware.org/?probe=30ceac1216) | Oct 31, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [423ad57e72](https://linux-hardware.org/?probe=423ad57e72) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [f8b4ce6c3f](https://linux-hardware.org/?probe=f8b4ce6c3f) | Oct 29, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [6383143b5b](https://linux-hardware.org/?probe=6383143b5b) | Oct 28, 2022 |
| Biostar       | H61MH                       | Desktop     | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [226e4471e1](https://linux-hardware.org/?probe=226e4471e1) | Oct 27, 2022 |
| Lenovo        | 318E NOK                    | Desktop     | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [59dabaff86](https://linux-hardware.org/?probe=59dabaff86) | Oct 23, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d34df28814](https://linux-hardware.org/?probe=d34df28814) | Oct 22, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [aa571dded9](https://linux-hardware.org/?probe=aa571dded9) | Oct 22, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [c389b44ab5](https://linux-hardware.org/?probe=c389b44ab5) | Oct 21, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [95ca32a110](https://linux-hardware.org/?probe=95ca32a110) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e33a95e0b0](https://linux-hardware.org/?probe=e33a95e0b0) | Oct 18, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [b6c2cf5b2e](https://linux-hardware.org/?probe=b6c2cf5b2e) | Oct 17, 2022 |
| Dell          | Latitude 3190               | Notebook    | [342d7acb67](https://linux-hardware.org/?probe=342d7acb67) | Oct 17, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [1f6ff0e213](https://linux-hardware.org/?probe=1f6ff0e213) | Oct 17, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [09af41cbf8](https://linux-hardware.org/?probe=09af41cbf8) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b3267ce847](https://linux-hardware.org/?probe=b3267ce847) | Oct 15, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [209d243342](https://linux-hardware.org/?probe=209d243342) | Oct 15, 2022 |
| Pegatron      | NARRA3                      | Desktop     | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| Medion        | E7424 MD60750               | Notebook    | [7c9ea600ad](https://linux-hardware.org/?probe=7c9ea600ad) | Oct 11, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [f2c440fdf6](https://linux-hardware.org/?probe=f2c440fdf6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [8159009c50](https://linux-hardware.org/?probe=8159009c50) | Oct 05, 2022 |
| Google        | Setzer                      | Notebook    | [6bafaabd48](https://linux-hardware.org/?probe=6bafaabd48) | Oct 04, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| Dell          | Latitude 7490               | Notebook    | [872aafeb50](https://linux-hardware.org/?probe=872aafeb50) | Oct 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f97d2b97ad](https://linux-hardware.org/?probe=f97d2b97ad) | Oct 01, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [992cf7d019](https://linux-hardware.org/?probe=992cf7d019) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [5b7d4c6b7a](https://linux-hardware.org/?probe=5b7d4c6b7a) | Sep 27, 2022 |
| Dell          | Precision 7520              | Notebook    | [a7b1df0888](https://linux-hardware.org/?probe=a7b1df0888) | Sep 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [6182e4ef84](https://linux-hardware.org/?probe=6182e4ef84) | Sep 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [de3a2e822c](https://linux-hardware.org/?probe=de3a2e822c) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| HP            | 1632                        | Desktop     | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7702adff5d](https://linux-hardware.org/?probe=7702adff5d) | Sep 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | Notebook    | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | Notebook    | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Biostar       | A780L3B                     | Desktop     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [83e026f682](https://linux-hardware.org/?probe=83e026f682) | Aug 12, 2022 |
| Dell          | System XPS 15Z              | Notebook    | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Lenovo        | ThinkPad T560 20FJS0EP00    | Notebook    | [dda2c8f199](https://linux-hardware.org/?probe=dda2c8f199) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| Dell          | Precision 7720              | Notebook    | [9f17ade16f](https://linux-hardware.org/?probe=9f17ade16f) | Aug 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [68e632a5f6](https://linux-hardware.org/?probe=68e632a5f6) | Aug 08, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| MP            | MS-7848                     | Desktop     | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Dell          | 0DR845                      | Desktop     | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| Alienware     | 13 R2                       | Notebook    | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | Notebook    | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [77c632ea8e](https://linux-hardware.org/?probe=77c632ea8e) | Jul 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | Desktop     | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | Notebook    | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | Notebook    | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | Notebook    | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c21cd1f8f3](https://linux-hardware.org/?probe=c21cd1f8f3) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | Notebook    | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| AZW           | SER                         | Mini pc     | [9da3c6ca34](https://linux-hardware.org/?probe=9da3c6ca34) | May 18, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | Notebook    | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Intel         | V1.3                        | Desktop     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | Notebook    | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | Desktop     | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [7cc89d3cba](https://linux-hardware.org/?probe=7cc89d3cba) | Apr 14, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [5cd6adf199](https://linux-hardware.org/?probe=5cd6adf199) | Apr 14, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [084e2350e9](https://linux-hardware.org/?probe=084e2350e9) | Apr 05, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [83dab83528](https://linux-hardware.org/?probe=83dab83528) | Apr 01, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | Notebook    | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| Sony          | SVE1513Q1ESI                | Notebook    | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | Notebook    | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | Notebook    | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.0-21-amd64            | 36        | 11.76%  |
| 5.10.0-13-amd64            | 20        | 6.54%   |
| 5.10.0-18-amd64            | 19        | 6.21%   |
| 6.0.0-6mx-amd64            | 18        | 5.88%   |
| 5.10.0-9-amd64             | 18        | 5.88%   |
| 5.10.0-19-amd64            | 18        | 5.88%   |
| 5.10.0-20-amd64            | 17        | 5.56%   |
| 5.14.0-4mx-amd64           | 16        | 5.23%   |
| 5.16.0-5mx-amd64           | 13        | 4.25%   |
| 5.10.0-16-amd64            | 13        | 4.25%   |
| 5.10.0-11-amd64            | 8         | 2.61%   |
| 5.18.0-4mx-amd64           | 7         | 2.29%   |
| 5.10.0-15-amd64            | 6         | 1.96%   |
| 5.10.0-14-amd64            | 6         | 1.96%   |
| 6.0.0-4mx-amd64            | 5         | 1.63%   |
| 6.0.0-10.1-liquorix-amd64  | 4         | 1.31%   |
| 5.19.0-2mx-amd64           | 4         | 1.31%   |
| 5.10.0-17-amd64            | 4         | 1.31%   |
| 5.10.0-10-amd64            | 4         | 1.31%   |
| 6.0.0-3mx-amd64            | 3         | 0.98%   |
| 5.16.0-6mx-amd64           | 3         | 0.98%   |
| 6.1.15-2-liquorix-amd64    | 2         | 0.65%   |
| 6.1.0-4mx-amd64            | 2         | 0.65%   |
| 6.1.0-2mx-amd64            | 2         | 0.65%   |
| 5.17.0-3mx-amd64           | 2         | 0.65%   |
| 5.16.0-4mx-amd64           | 2         | 0.65%   |
| 5.16.0-18.1-liquorix-amd64 | 2         | 0.65%   |
| 5.14.0-3mx-amd64           | 2         | 0.65%   |
| 5.10.0-8-amd64             | 2         | 0.65%   |
| 5.10.0-20-686-pae          | 2         | 0.65%   |
| 5.10.0-18-686-pae          | 2         | 0.65%   |
| 5.10.0-13-686-pae          | 2         | 0.65%   |
| 5.10.0-12-amd64            | 2         | 0.65%   |
| 5.10.0-11-686-pae          | 2         | 0.65%   |
| 6.2.7-x64v4-xanmod1        | 1         | 0.33%   |
| 6.1.12-3-liquorix-amd64    | 1         | 0.33%   |
| 6.1.0-t2                   | 1         | 0.33%   |
| 6.1.0-8mx-ahs-amd64        | 1         | 0.33%   |
| 6.1.0-7mx-ahs-amd64        | 1         | 0.33%   |
| 6.0.5-x64v1-xanmod1        | 1         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 177       | 59.6%   |
| 6.0.0    | 33        | 11.11%  |
| 5.16.0   | 21        | 7.07%   |
| 5.14.0   | 19        | 6.4%    |
| 5.19.0   | 9         | 3.03%   |
| 5.18.0   | 9         | 3.03%   |
| 6.1.0    | 7         | 2.36%   |
| 5.17.0   | 6         | 2.02%   |
| 5.15.0   | 3         | 1.01%   |
| 6.1.15   | 2         | 0.67%   |
| 4.19.0   | 2         | 0.67%   |
| 6.2.7    | 1         | 0.34%   |
| 6.1.12   | 1         | 0.34%   |
| 6.0.5    | 1         | 0.34%   |
| 5.10.82  | 1         | 0.34%   |
| 5.10.52  | 1         | 0.34%   |
| 5.10.142 | 1         | 0.34%   |
| 5.10.113 | 1         | 0.34%   |
| 5.10.111 | 1         | 0.34%   |
| Unknown  | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 182       | 61.28%  |
| 6.0     | 34        | 11.45%  |
| 5.16    | 21        | 7.07%   |
| 5.14    | 19        | 6.4%    |
| 6.1     | 10        | 3.37%   |
| 5.19    | 9         | 3.03%   |
| 5.18    | 9         | 3.03%   |
| 5.17    | 6         | 2.02%   |
| 5.15    | 3         | 1.01%   |
| 4.19    | 2         | 0.67%   |
| 6.2     | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 274       | 96.14%  |
| i686   | 11        | 3.86%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 207       | 71.63%  |
| KDE5             | 63        | 21.8%   |
| lightdm-xsession | 4         | 1.38%   |
| GNOME            | 4         | 1.38%   |
| Budgie           | 3         | 1.04%   |
| Unknown          | 3         | 1.04%   |
| X-Cinnamon       | 1         | 0.35%   |
| LXQt             | 1         | 0.35%   |
| i3               | 1         | 0.35%   |
| GNOME Classic    | 1         | 0.35%   |
| fluxbox          | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 282       | 98.95%  |
| Tty     | 2         | 0.7%    |
| Wayland | 1         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 219       | 76.31%  |
| SDDM    | 60        | 20.91%  |
| SLiM    | 6         | 2.09%   |
| GDM     | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 133       | 46.34%  |
| de_DE   | 40        | 13.94%  |
| it_IT   | 16        | 5.57%   |
| en_GB   | 16        | 5.57%   |
| ru_RU   | 9         | 3.14%   |
| fr_FR   | 8         | 2.79%   |
| en_AU   | 7         | 2.44%   |
| pl_PL   | 6         | 2.09%   |
| es_ES   | 5         | 1.74%   |
| de_CH   | 5         | 1.74%   |
| es_AR   | 4         | 1.39%   |
| Unknown | 4         | 1.39%   |
| pt_BR   | 3         | 1.05%   |
| en_NZ   | 3         | 1.05%   |
| tr_TR   | 2         | 0.7%    |
| sv_SE   | 2         | 0.7%    |
| nl_NL   | 2         | 0.7%    |
| hu_HU   | 2         | 0.7%    |
| fi_FI   | 2         | 0.7%    |
| es_MX   | 2         | 0.7%    |
| es_CO   | 2         | 0.7%    |
| bg_BG   | 2         | 0.7%    |
| sk_SK   | 1         | 0.35%   |
| nb_NO   | 1         | 0.35%   |
| id_ID   | 1         | 0.35%   |
| hr_HR   | 1         | 0.35%   |
| fr_CA   | 1         | 0.35%   |
| fr_BE   | 1         | 0.35%   |
| eu_ES   | 1         | 0.35%   |
| es_VE   | 1         | 0.35%   |
| es_UY   | 1         | 0.35%   |
| es_PE   | 1         | 0.35%   |
| en_CA   | 1         | 0.35%   |
| da_DK   | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 183       | 64.21%  |
| BIOS | 102       | 35.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 242       | 84.32%  |
| Overlay  | 30        | 10.45%  |
| Btrfs    | 10        | 3.48%   |
| Xfs      | 2         | 0.7%    |
| Reiserfs | 1         | 0.35%   |
| F2fs     | 1         | 0.35%   |
| Ext3     | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 201       | 70.53%  |
| MBR     | 82        | 28.77%  |
| Unknown | 2         | 0.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 203       | 70.49%  |
| Yes       | 85        | 29.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 156       | 54.36%  |
| Yes       | 131       | 45.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 42        | 14.74%  |
| Lenovo                               | 39        | 13.68%  |
| ASUSTek Computer                     | 39        | 13.68%  |
| Dell                                 | 27        | 9.47%   |
| Apple                                | 17        | 5.96%   |
| MSI                                  | 14        | 4.91%   |
| Gigabyte Technology                  | 13        | 4.56%   |
| Acer                                 | 12        | 4.21%   |
| Sony                                 | 8         | 2.81%   |
| ASRock                               | 6         | 2.11%   |
| Medion                               | 5         | 1.75%   |
| Intel                                | 5         | 1.75%   |
| Toshiba                              | 4         | 1.4%    |
| Unknown                              | 4         | 1.4%    |
| Samsung Electronics                  | 3         | 1.05%   |
| Alienware                            | 3         | 1.05%   |
| ZOTAC                                | 2         | 0.7%    |
| TUXEDO                               | 2         | 0.7%    |
| Pegatron                             | 2         | 0.7%    |
| Microsoft                            | 2         | 0.7%    |
| Fujitsu Siemens                      | 2         | 0.7%    |
| Fujitsu                              | 2         | 0.7%    |
| Chuwi                                | 2         | 0.7%    |
| Biostar                              | 2         | 0.7%    |
| AZW                                  | 2         | 0.7%    |
| win element                          | 1         | 0.35%   |
| Vulcan Electronics                   | 1         | 0.35%   |
| Sun Microsystems                     | 1         | 0.35%   |
| SIRAGON                              | 1         | 0.35%   |
| Shenzhen Wangang Technology          | 1         | 0.35%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.35%   |
| SANTECH                              | 1         | 0.35%   |
| RTD Embedded Technologies            | 1         | 0.35%   |
| Notebook                             | 1         | 0.35%   |
| MP                                   | 1         | 0.35%   |
| Linx                                 | 1         | 0.35%   |
| Huanan                               | 1         | 0.35%   |
| Google                               | 1         | 0.35%   |
| GEO                                  | 1         | 0.35%   |
| Gateway                              | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| ASUS All Series                              | 7         | 2.46%   |
| Unknown                                      | 6         | 2.11%   |
| MSI MS-7C91                                  | 2         | 0.7%    |
| HP Laptop 17-ak0xx                           | 2         | 0.7%    |
| Gigabyte GA-MA785GM-US2H                     | 2         | 0.7%    |
| Dell OptiPlex 755                            | 2         | 0.7%    |
| Chuwi GemiBook Pro                           | 2         | 0.7%    |
| AZW SER                                      | 2         | 0.7%    |
| ASUS ROG Maximus XIII HERO                   | 2         | 0.7%    |
| Apple Macmini8,1                             | 2         | 0.7%    |
| Apple MacBookAir7,2                          | 2         | 0.7%    |
| Acer Nitro AN515-55                          | 2         | 0.7%    |
| ZOTAC ZBOX-ECM73070C/53060C                  | 1         | 0.35%   |
| win element MoreFine S500+                   | 1         | 0.35%   |
| Vulcan Excursion XB                          | 1         | 0.35%   |
| TUXEDO N7x0WU                                | 1         | 0.35%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)           | 1         | 0.35%   |
| Toshiba Satellite M70                        | 1         | 0.35%   |
| Toshiba Satellite L650                       | 1         | 0.35%   |
| Toshiba Satellite C845                       | 1         | 0.35%   |
| Toshiba PORTEGE Z30-C                        | 1         | 0.35%   |
| Sun Microsystems Sun Ultra 40 M2 Workstation | 1         | 0.35%   |
| Sony VPCYB3V1E                               | 1         | 0.35%   |
| Sony VPCSB1V9R                               | 1         | 0.35%   |
| Sony VPCF119FX                               | 1         | 0.35%   |
| Sony VPCEH2N1E                               | 1         | 0.35%   |
| Sony VPCEC3S1E                               | 1         | 0.35%   |
| Sony VPCCB32FD                               | 1         | 0.35%   |
| Sony VGN-TZ3RXN_B                            | 1         | 0.35%   |
| Sony SVE1513Q1ESI                            | 1         | 0.35%   |
| SIRAGON AIO-5150                             | 1         | 0.35%   |
| Shenzhen Wangang AERO 2 Pro                  | 1         | 0.35%   |
| Shenzhen Meigao Electronic Equipment UM450   | 1         | 0.35%   |
| SANTECH X170KM-G                             | 1         | 0.35%   |
| Samsung NC210/NC110                          | 1         | 0.35%   |
| Samsung 350V5C/351V5C/3540VC/3440VC          | 1         | 0.35%   |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 0.35%   |
| RTD Embedded CMA34CR                         | 1         | 0.35%   |
| Pegatron FQ425AA-ABA a6655f                  | 1         | 0.35%   |
| Pegatron 2AD5                                | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 19        | 6.67%   |
| Dell OptiPlex            | 7         | 2.46%   |
| ASUS All                 | 7         | 2.46%   |
| HP ProBook               | 6         | 2.11%   |
| HP EliteBook             | 6         | 2.11%   |
| HP Compaq                | 6         | 2.11%   |
| Dell Inspiron            | 6         | 2.11%   |
| Acer Aspire              | 6         | 2.11%   |
| Unknown                  | 6         | 2.11%   |
| Dell Latitude            | 5         | 1.75%   |
| ASUS ROG                 | 5         | 1.75%   |
| Lenovo IdeaPad           | 4         | 1.4%    |
| HP Laptop                | 4         | 1.4%    |
| ASUS TUF                 | 4         | 1.4%    |
| Toshiba Satellite        | 3         | 1.05%   |
| Dell Vostro              | 3         | 1.05%   |
| Dell Precision           | 3         | 1.05%   |
| Acer Nitro               | 3         | 1.05%   |
| MSI MS-7C91              | 2         | 0.7%    |
| Microsoft Surface        | 2         | 0.7%    |
| Lenovo ThinkCentre       | 2         | 0.7%    |
| Lenovo ThinkBook         | 2         | 0.7%    |
| Lenovo IdeaCentre        | 2         | 0.7%    |
| HP ZBook                 | 2         | 0.7%    |
| HP Pavilion              | 2         | 0.7%    |
| HP ENVY                  | 2         | 0.7%    |
| Gigabyte GA-MA785GM-US2H | 2         | 0.7%    |
| Gigabyte B550M           | 2         | 0.7%    |
| Chuwi GemiBook           | 2         | 0.7%    |
| AZW SER                  | 2         | 0.7%    |
| ASUS VivoBook            | 2         | 0.7%    |
| ASUS P5GC-MX             | 2         | 0.7%    |
| ASUS ASUS                | 2         | 0.7%    |
| Apple Macmini8           | 2         | 0.7%    |
| Apple Macmini6           | 2         | 0.7%    |
| Apple MacBookPro11       | 2         | 0.7%    |
| Apple MacBookAir7        | 2         | 0.7%    |
| Alienware m15            | 2         | 0.7%    |
| Acer Swift               | 2         | 0.7%    |
| ZOTAC ZBOX-ECM73070C     | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 42        | 14.74%  |
| 2020    | 24        | 8.42%   |
| 2011    | 22        | 7.72%   |
| 2018    | 20        | 7.02%   |
| 2022    | 18        | 6.32%   |
| 2016    | 18        | 6.32%   |
| 2015    | 18        | 6.32%   |
| 2019    | 17        | 5.96%   |
| 2013    | 17        | 5.96%   |
| 2012    | 17        | 5.96%   |
| 2010    | 17        | 5.96%   |
| 2014    | 13        | 4.56%   |
| 2009    | 9         | 3.16%   |
| 2008    | 9         | 3.16%   |
| 2007    | 9         | 3.16%   |
| 2017    | 8         | 2.81%   |
| 2006    | 3         | 1.05%   |
| 2005    | 2         | 0.7%    |
| 2004    | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 164       | 57.54%  |
| Desktop     | 93        | 32.63%  |
| Mini pc     | 11        | 3.86%   |
| Convertible | 7         | 2.46%   |
| All in one  | 6         | 2.11%   |
| Tablet      | 2         | 0.7%    |
| Server      | 2         | 0.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 283       | 99.3%   |
| Enabled  | 2         | 0.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 284       | 99.65%  |
| Yes  | 1         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 78        | 27.37%  |
| 8.01-16.0   | 60        | 21.05%  |
| 16.01-24.0  | 44        | 15.44%  |
| 32.01-64.0  | 35        | 12.28%  |
| 3.01-4.0    | 35        | 12.28%  |
| 1.01-2.0    | 11        | 3.86%   |
| 2.01-3.0    | 8         | 2.81%   |
| 64.01-256.0 | 6         | 2.11%   |
| 24.01-32.0  | 5         | 1.75%   |
| 0.51-1.0    | 3         | 1.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 95        | 31.88%  |
| 2.01-3.0   | 94        | 31.54%  |
| 3.01-4.0   | 48        | 16.11%  |
| 4.01-8.0   | 36        | 12.08%  |
| 0.51-1.0   | 14        | 4.7%    |
| 8.01-16.0  | 8         | 2.68%   |
| 0.01-0.5   | 2         | 0.67%   |
| 16.01-24.0 | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 168       | 58.13%  |
| 2      | 64        | 22.15%  |
| 3      | 34        | 11.76%  |
| 4      | 12        | 4.15%   |
| 5      | 5         | 1.73%   |
| 8      | 3         | 1.04%   |
| 0      | 2         | 0.69%   |
| 7      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 182       | 63.86%  |
| Yes       | 103       | 36.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 245       | 85.96%  |
| No        | 40        | 14.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 231       | 80.77%  |
| No        | 55        | 19.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 61.4%   |
| No        | 110       | 38.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 70        | 24.39%  |
| Germany     | 41        | 14.29%  |
| Italy       | 24        | 8.36%   |
| Canada      | 12        | 4.18%   |
| Russia      | 11        | 3.83%   |
| Australia   | 10        | 3.48%   |
| Poland      | 9         | 3.14%   |
| France      | 9         | 3.14%   |
| UK          | 7         | 2.44%   |
| India       | 7         | 2.44%   |
| Spain       | 6         | 2.09%   |
| Netherlands | 6         | 2.09%   |
| Switzerland | 5         | 1.74%   |
| Finland     | 5         | 1.74%   |
| Brazil      | 5         | 1.74%   |
| New Zealand | 4         | 1.39%   |
| Sweden      | 3         | 1.05%   |
| Serbia      | 3         | 1.05%   |
| Romania     | 3         | 1.05%   |
| Belgium     | 3         | 1.05%   |
| Argentina   | 3         | 1.05%   |
| Venezuela   | 2         | 0.7%    |
| Turkey      | 2         | 0.7%    |
| Mexico      | 2         | 0.7%    |
| Indonesia   | 2         | 0.7%    |
| Hungary     | 2         | 0.7%    |
| Greece      | 2         | 0.7%    |
| Egypt       | 2         | 0.7%    |
| Croatia     | 2         | 0.7%    |
| Colombia    | 2         | 0.7%    |
| Bulgaria    | 2         | 0.7%    |
| Bangladesh  | 2         | 0.7%    |
| Austria     | 2         | 0.7%    |
| Vietnam     | 1         | 0.35%   |
| Uruguay     | 1         | 0.35%   |
| Tunisia     | 1         | 0.35%   |
| Slovakia    | 1         | 0.35%   |
| Singapore   | 1         | 0.35%   |
| Peru        | 1         | 0.35%   |
| Norway      | 1         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Berlin        | 5         | 1.69%   |
| Sydney        | 4         | 1.36%   |
| St Petersburg | 4         | 1.36%   |
| Moscow        | 4         | 1.36%   |
| Rome          | 3         | 1.02%   |
| Milan         | 3         | 1.02%   |
| Melbourne     | 3         | 1.02%   |
| Cambridge     | 3         | 1.02%   |
| Amsterdam     | 3         | 1.02%   |
| Warsaw        | 2         | 0.68%   |
| Walled Lake   | 2         | 0.68%   |
| Vienna        | 2         | 0.68%   |
| Vasco da Gama | 2         | 0.68%   |
| Portland      | 2         | 0.68%   |
| Orange        | 2         | 0.68%   |
| New York      | 2         | 0.68%   |
| Montreal      | 2         | 0.68%   |
| Mesquite      | 2         | 0.68%   |
| Krakow        | 2         | 0.68%   |
| Istanbul      | 2         | 0.68%   |
| Houston       | 2         | 0.68%   |
| Helsinki      | 2         | 0.68%   |
| Hamburg       | 2         | 0.68%   |
| Florence      | 2         | 0.68%   |
| Ettingen      | 2         | 0.68%   |
| Doesburg      | 2         | 0.68%   |
| Dhaka         | 2         | 0.68%   |
| Delhi         | 2         | 0.68%   |
| Catania       | 2         | 0.68%   |
| Casale Litta  | 2         | 0.68%   |
| Canberra      | 2         | 0.68%   |
| Cairo         | 2         | 0.68%   |
| Buffalo       | 2         | 0.68%   |
| Budapest      | 2         | 0.68%   |
| Belgrade      | 2         | 0.68%   |
| Alma          | 2         | 0.68%   |
| Zurich        | 1         | 0.34%   |
| Zeven         | 1         | 0.34%   |
| Zagreb        | 1         | 0.34%   |
| Yekaterinburg | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 71        | 102    | 16.17%  |
| WDC                 | 58        | 66     | 13.21%  |
| Seagate             | 53        | 70     | 12.07%  |
| Kingston            | 35        | 38     | 7.97%   |
| Crucial             | 23        | 40     | 5.24%   |
| Toshiba             | 21        | 22     | 4.78%   |
| Unknown             | 20        | 24     | 4.56%   |
| SanDisk             | 15        | 18     | 3.42%   |
| SK hynix            | 14        | 15     | 3.19%   |
| Hitachi             | 12        | 14     | 2.73%   |
| Apple               | 9         | 13     | 2.05%   |
| Intel               | 8         | 10     | 1.82%   |
| China               | 7         | 8      | 1.59%   |
| PNY                 | 6         | 7      | 1.37%   |
| Transcend           | 5         | 5      | 1.14%   |
| SPCC                | 5         | 5      | 1.14%   |
| Micron Technology   | 5         | 5      | 1.14%   |
| LITEON              | 5         | 5      | 1.14%   |
| Corsair             | 5         | 5      | 1.14%   |
| Netac               | 4         | 4      | 0.91%   |
| KIOXIA              | 4         | 6      | 0.91%   |
| HGST                | 4         | 4      | 0.91%   |
| Unknown             | 4         | 4      | 0.91%   |
| Phison              | 3         | 4      | 0.68%   |
| Dogfish             | 3         | 3      | 0.68%   |
| Apacer              | 3         | 3      | 0.68%   |
| Team                | 2         | 2      | 0.46%   |
| Silicon Motion      | 2         | 2      | 0.46%   |
| OCZ                 | 2         | 2      | 0.46%   |
| GOODRAM             | 2         | 2      | 0.46%   |
| External            | 2         | 2      | 0.46%   |
| A-DATA Technology   | 2         | 2      | 0.46%   |
| USB                 | 1         | 1      | 0.23%   |
| SWORDBILL           | 1         | 2      | 0.23%   |
| SABRENT             | 1         | 1      | 0.23%   |
| RENICE              | 1         | 1      | 0.23%   |
| Phison Electronics  | 1         | 1      | 0.23%   |
| Patriot             | 1         | 1      | 0.23%   |
| Mushkin             | 1         | 1      | 0.23%   |
| MMY                 | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD        | 9         | 1.86%   |
| Samsung SSD 980 PRO 1TB                | 6         | 1.24%   |
| Samsung SSD 860 EVO 500GB              | 6         | 1.24%   |
| Samsung SSD 970 EVO Plus 1TB           | 5         | 1.04%   |
| Samsung SSD 850 EVO 250GB              | 5         | 1.04%   |
| Seagate ST500LM021-1KJ152 500GB        | 4         | 0.83%   |
| Kingston SV300S37A240G 240GB SSD       | 4         | 0.83%   |
| Kingston SA400S37240G 240GB SSD        | 4         | 0.83%   |
| Kingston SA400S37120G 120GB SSD        | 4         | 0.83%   |
| Crucial CT500MX500SSD1 500GB           | 4         | 0.83%   |
| Crucial CT480BX500SSD1 480GB           | 4         | 0.83%   |
| Crucial CT120BX500SSD1 120GB           | 4         | 0.83%   |
| Unknown                                | 4         | 0.83%   |
| Unknown SD32G  32GB                    | 3         | 0.62%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 0.62%   |
| Seagate ST3500413AS 500GB              | 3         | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB         | 3         | 0.62%   |
| Seagate ST2000DM001-1ER164 2TB         | 3         | 0.62%   |
| SanDisk SDSSDA240G 240GB               | 3         | 0.62%   |
| Samsung SSD 870 EVO 500GB              | 3         | 0.62%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.62%   |
| Samsung SSD 850 EVO 1TB                | 3         | 0.62%   |
| Samsung SSD 840 Series 120GB           | 3         | 0.62%   |
| Crucial CT240BX500SSD1 240GB           | 3         | 0.62%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.41%   |
| WDC WDS100T1X0E-00AFY0 1TB             | 2         | 0.41%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 0.41%   |
| Unknown SD/MMC/MS PRO 249GB            | 2         | 0.41%   |
| Unknown SD/MMC 2GB                     | 2         | 0.41%   |
| Unknown M.S./M.S.Pro/HG 16GB           | 2         | 0.41%   |
| Unknown DA4064  64GB                   | 2         | 0.41%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.41%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 2         | 0.41%   |
| Toshiba HDWD110 1TB                    | 2         | 0.41%   |
| Toshiba DT01ACA100 1TB                 | 2         | 0.41%   |
| SPCC Solid State Disk 256GB            | 2         | 0.41%   |
| SPCC Solid State Disk 1TB              | 2         | 0.41%   |
| SK hynix HFS128G39TND-N210A 128GB SSD  | 2         | 0.41%   |
| SK hynix HFM512GDJTNI-82A0A 512GB      | 2         | 0.41%   |
| Seagate ST500LT012-9WS142 500GB        | 2         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 70     | 38.97%  |
| WDC                 | 40        | 47     | 29.41%  |
| Toshiba             | 15        | 16     | 11.03%  |
| Hitachi             | 12        | 14     | 8.82%   |
| Samsung Electronics | 5         | 5      | 3.68%   |
| HGST                | 4         | 4      | 2.94%   |
| Unknown             | 2         | 2      | 1.47%   |
| Maxtor              | 1         | 1      | 0.74%   |
| Fujitsu             | 1         | 1      | 0.74%   |
| External            | 1         | 1      | 0.74%   |
| ASMT                | 1         | 1      | 0.74%   |
| Apple               | 1         | 1      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 42        | 52     | 23.46%  |
| Kingston            | 25        | 27     | 13.97%  |
| Crucial             | 20        | 35     | 11.17%  |
| SanDisk             | 12        | 14     | 6.7%    |
| China               | 7         | 8      | 3.91%   |
| WDC                 | 6         | 6      | 3.35%   |
| Apple               | 6         | 9      | 3.35%   |
| Transcend           | 5         | 5      | 2.79%   |
| SPCC                | 5         | 5      | 2.79%   |
| PNY                 | 5         | 5      | 2.79%   |
| Netac               | 4         | 4      | 2.23%   |
| LITEON              | 4         | 4      | 2.23%   |
| SK hynix            | 3         | 3      | 1.68%   |
| Dogfish             | 3         | 3      | 1.68%   |
| Toshiba             | 2         | 2      | 1.12%   |
| OCZ                 | 2         | 2      | 1.12%   |
| Micron Technology   | 2         | 2      | 1.12%   |
| GOODRAM             | 2         | 2      | 1.12%   |
| Apacer              | 2         | 2      | 1.12%   |
| A-DATA Technology   | 2         | 2      | 1.12%   |
| Unknown             | 2         | 2      | 1.12%   |
| Team                | 1         | 1      | 0.56%   |
| SWORDBILL           | 1         | 2      | 0.56%   |
| RENICE              | 1         | 1      | 0.56%   |
| Patriot             | 1         | 1      | 0.56%   |
| Mushkin             | 1         | 1      | 0.56%   |
| MMY                 | 1         | 1      | 0.56%   |
| Intel               | 1         | 1      | 0.56%   |
| Indilinx            | 1         | 1      | 0.56%   |
| Hewlett-Packard     | 1         | 1      | 0.56%   |
| Gigabyte Technology | 1         | 1      | 0.56%   |
| GeIL                | 1         | 1      | 0.56%   |
| External            | 1         | 1      | 0.56%   |
| CT500MX5            | 1         | 1      | 0.56%   |
| CT1000P3            | 1         | 1      | 0.56%   |
| CT1000MX            | 1         | 1      | 0.56%   |
| Corsair             | 1         | 1      | 0.56%   |
| Avant               | 1         | 1      | 0.56%   |
| Acer                | 1         | 1      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 151       | 213    | 38.13%  |
| HDD     | 119       | 163    | 30.05%  |
| NVMe    | 102       | 133    | 25.76%  |
| MMC     | 19        | 22     | 4.8%    |
| Unknown | 5         | 7      | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 209       | 361    | 60.58%  |
| NVMe | 102       | 132    | 29.57%  |
| MMC  | 19        | 22     | 5.51%   |
| SAS  | 15        | 23     | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 172       | 240    | 63.47%  |
| 0.51-1.0   | 67        | 91     | 24.72%  |
| 1.01-2.0   | 19        | 25     | 7.01%   |
| 3.01-4.0   | 5         | 5      | 1.85%   |
| 2.01-3.0   | 4         | 4      | 1.48%   |
| 4.01-10.0  | 3         | 10     | 1.11%   |
| 10.01-20.0 | 1         | 1      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 79        | 27.05%  |
| 251-500        | 66        | 22.6%   |
| 501-1000       | 38        | 13.01%  |
| 51-100         | 26        | 8.9%    |
| 21-50          | 24        | 8.22%   |
| 1001-2000      | 21        | 7.19%   |
| 1-20           | 15        | 5.14%   |
| 2001-3000      | 12        | 4.11%   |
| More than 3000 | 11        | 3.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 111       | 37.25%  |
| 21-50          | 52        | 17.45%  |
| 101-250        | 42        | 14.09%  |
| 51-100         | 36        | 12.08%  |
| 251-500        | 22        | 7.38%   |
| 501-1000       | 15        | 5.03%   |
| 1001-2000      | 13        | 4.36%   |
| More than 3000 | 4         | 1.34%   |
| 2001-3000      | 3         | 1.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB              | 2         | 2      | 3.64%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1      | 1.82%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 1.82%   |
| WDC WD5000AAKS-40V6A0 500GB                  | 1         | 1      | 1.82%   |
| WDC WD3200BPVT-80ZEST0 320GB                 | 1         | 1      | 1.82%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 1.82%   |
| WDC WD3200AAKS-00UU3A0 320GB                 | 1         | 1      | 1.82%   |
| WDC WD3200AAJS-00B4A0 320GB                  | 1         | 1      | 1.82%   |
| WDC WD2500AAJS-00B4A0 250GB                  | 1         | 1      | 1.82%   |
| WDC WD10EZRZ-00HTKB0 1TB                     | 1         | 1      | 1.82%   |
| WDC WD10EADS-98M2B0 1TB                      | 1         | 1      | 1.82%   |
| WDC WD10EADS-00M2B0 1TB                      | 1         | 1      | 1.82%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD         | 1         | 1      | 1.82%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 1.82%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD        | 1         | 1      | 1.82%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 1.82%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 1.82%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 1.82%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 1.82%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 1.82%   |
| Seagate ST380815AS 80GB                      | 1         | 1      | 1.82%   |
| Seagate ST3500413AS 500GB                    | 1         | 1      | 1.82%   |
| Seagate ST3360320AS 360GB                    | 1         | 1      | 1.82%   |
| Seagate ST320LT020-9YG142 320GB              | 1         | 1      | 1.82%   |
| Seagate ST320LT012-1DG14C 320GB              | 1         | 2      | 1.82%   |
| Seagate ST320LT007-9ZV142 320GB              | 1         | 1      | 1.82%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 1.82%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 1.82%   |
| Seagate ST1000VM002-1CT162 1TB               | 1         | 1      | 1.82%   |
| Seagate ST1000DM003-9YN162 1TB               | 1         | 1      | 1.82%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 1.82%   |
| Samsung Electronics SSD 850 EVO 500GB        | 1         | 1      | 1.82%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 2      | 1.82%   |
| Samsung Electronics SSD 840 Series 120GB     | 1         | 1      | 1.82%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 1.82%   |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 1      | 1.82%   |
| Samsung Electronics HM080HC 80GB             | 1         | 1      | 1.82%   |
| RENICE X2 64GB SSD                           | 1         | 1      | 1.82%   |
| Maxtor 4K040H2 40GB                          | 1         | 1      | 1.82%   |
| Kingston SA400S37480G 480GB SSD              | 1         | 1      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 31.48%  |
| WDC                 | 11        | 11     | 20.37%  |
| Samsung Electronics | 7         | 8      | 12.96%  |
| Hitachi             | 4         | 5      | 7.41%   |
| HGST                | 3         | 3      | 5.56%   |
| Toshiba             | 2         | 2      | 3.7%    |
| Kingston            | 2         | 2      | 3.7%    |
| SK hynix            | 1         | 1      | 1.85%   |
| RENICE              | 1         | 1      | 1.85%   |
| Maxtor              | 1         | 1      | 1.85%   |
| Intel               | 1         | 2      | 1.85%   |
| Indilinx            | 1         | 1      | 1.85%   |
| GOODRAM             | 1         | 1      | 1.85%   |
| Crucial             | 1         | 6      | 1.85%   |
| China               | 1         | 1      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 45.95%  |
| WDC                 | 10        | 10     | 27.03%  |
| Hitachi             | 4         | 5      | 10.81%  |
| HGST                | 3         | 3      | 8.11%   |
| Toshiba             | 1         | 1      | 2.7%    |
| Samsung Electronics | 1         | 1      | 2.7%    |
| Maxtor              | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 39     | 67.92%  |
| SSD  | 16        | 22     | 30.19%  |
| NVMe | 1         | 2      | 1.89%   |

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
| Works    | 242       | 422    | 72.02%  |
| Malfunc  | 53        | 63     | 15.77%  |
| Detected | 41        | 53     | 12.2%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 195       | 53.57%  |
| AMD                          | 43        | 11.81%  |
| Samsung Electronics          | 37        | 10.16%  |
| SanDisk                      | 14        | 3.85%   |
| Phison Electronics           | 11        | 3.02%   |
| SK hynix                     | 10        | 2.75%   |
| Kingston Technology Company  | 10        | 2.75%   |
| KIOXIA                       | 6         | 1.65%   |
| ASMedia Technology           | 6         | 1.65%   |
| Nvidia                       | 5         | 1.37%   |
| Micron/Crucial Technology    | 5         | 1.37%   |
| Silicon Motion               | 3         | 0.82%   |
| Micron Technology            | 3         | 0.82%   |
| Marvell Technology Group     | 3         | 0.82%   |
| Toshiba America Info Systems | 2         | 0.55%   |
| Silicon Image                | 2         | 0.55%   |
| Broadcom / LSI               | 2         | 0.55%   |
| Apple                        | 2         | 0.55%   |
| VIA Technologies             | 1         | 0.27%   |
| ULi Electronics              | 1         | 0.27%   |
| Shenzhen Longsys Electronics | 1         | 0.27%   |
| LSI Logic / Symbios Logic    | 1         | 0.27%   |
| Lite-On Technology           | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24        | 5.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 4.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 3.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 3.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 3.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 2.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 2.43%   |
| Samsung NVMe SSD Controller 980                                                | 8         | 1.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 1.95%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 1.7%    |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 1.7%    |
| Phison E12 NVMe Controller                                                     | 6         | 1.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 1.46%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 6         | 1.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.22%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 5         | 1.22%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 1.22%   |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 1.22%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 5         | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.22%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.22%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 0.97%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 0.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 0.97%   |
| SK hynix BC511                                                                 | 3         | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 0.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 0.73%   |
| SanDisk NVMe Controller                                                        | 3         | 0.73%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 0.73%   |
| Micron NVMe Storage Controller                                                 | 3         | 0.73%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 0.73%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 3         | 0.73%   |
| Intel Non-Volatile memory controller                                           | 3         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 212       | 57.61%  |
| NVMe | 101       | 27.45%  |
| IDE  | 37        | 10.05%  |
| RAID | 16        | 4.35%   |
| SCSI | 2         | 0.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 225       | 78.95%  |
| AMD    | 60        | 21.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 2.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 5         | 1.75%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 4         | 1.4%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 4         | 1.4%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 4         | 1.4%    |
| AMD Ryzen 7 5700U with Radeon Graphics  | 4         | 1.4%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 1.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 1.05%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 3         | 1.05%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 3         | 1.05%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 3         | 1.05%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 3         | 1.05%   |
| Intel 12th Gen Core i7-12700H           | 3         | 1.05%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 1.05%   |
| Intel Core i7-8700B CPU @ 3.20GHz       | 2         | 0.7%    |
| Intel Core i7-5820K CPU @ 3.30GHz       | 2         | 0.7%    |
| Intel Core i7-2640M CPU @ 2.80GHz       | 2         | 0.7%    |
| Intel Core i7-2600 CPU @ 3.40GHz        | 2         | 0.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.7%    |
| Intel Core i5-9600K CPU @ 3.70GHz       | 2         | 0.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 0.7%    |
| Intel Core i5-5350U CPU @ 1.80GHz       | 2         | 0.7%    |
| Intel Core i5-4690K CPU @ 3.50GHz       | 2         | 0.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz        | 2         | 0.7%    |
| Intel Core i5-3350P CPU @ 3.10GHz       | 2         | 0.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.7%    |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.7%    |
| Intel Core i5-2450M CPU @ 2.50GHz       | 2         | 0.7%    |
| Intel Core i5-2430M CPU @ 2.40GHz       | 2         | 0.7%    |
| Intel Core i3-10110U CPU @ 2.10GHz      | 2         | 0.7%    |
| Intel Core 2 CPU T5500 @ 1.66GHz        | 2         | 0.7%    |
| Intel Celeron N5105 @ 2.00GHz           | 2         | 0.7%    |
| Intel Celeron J4125 CPU @ 2.00GHz       | 2         | 0.7%    |
| Intel Celeron CPU N3450 @ 1.10GHz       | 2         | 0.7%    |
| Intel Celeron CPU N3060 @ 1.60GHz       | 2         | 0.7%    |
| Intel Atom CPU Z3735F @ 1.33GHz         | 2         | 0.7%    |
| Intel Atom CPU N570 @ 1.66GHz           | 2         | 0.7%    |
| AMD Ryzen 9 5900HX with Radeon Graphics | 2         | 0.7%    |
| AMD Ryzen 7 5800X 8-Core Processor      | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 54        | 18.95%  |
| Intel Core i7           | 51        | 17.89%  |
| Intel Core i3           | 28        | 9.82%   |
| Other                   | 27        | 9.47%   |
| Intel Celeron           | 18        | 6.32%   |
| AMD Ryzen 7             | 17        | 5.96%   |
| AMD Ryzen 5             | 17        | 5.96%   |
| Intel Core 2 Duo        | 15        | 5.26%   |
| Intel Atom              | 7         | 2.46%   |
| Intel Xeon              | 5         | 1.75%   |
| Intel Pentium           | 4         | 1.4%    |
| AMD Ryzen 3             | 4         | 1.4%    |
| Intel Pentium Dual-Core | 3         | 1.05%   |
| AMD Ryzen 9             | 3         | 1.05%   |
| AMD Athlon II X4        | 3         | 1.05%   |
| Intel Pentium Silver    | 2         | 0.7%    |
| Intel Pentium M         | 2         | 0.7%    |
| Intel Pentium 4         | 2         | 0.7%    |
| Intel Core i9           | 2         | 0.7%    |
| Intel Core 2            | 2         | 0.7%    |
| AMD Phenom              | 2         | 0.7%    |
| Intel Pentium Gold      | 1         | 0.35%   |
| Intel Pentium Dual      | 1         | 0.35%   |
| Intel Genuine           | 1         | 0.35%   |
| Intel Core M            | 1         | 0.35%   |
| AMD Turion 64 X2 Mobile | 1         | 0.35%   |
| AMD Sempron             | 1         | 0.35%   |
| AMD Ryzen Threadripper  | 1         | 0.35%   |
| AMD Ryzen 5 PRO         | 1         | 0.35%   |
| AMD Phenom II X4        | 1         | 0.35%   |
| AMD Phenom II           | 1         | 0.35%   |
| AMD E2                  | 1         | 0.35%   |
| AMD E1                  | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD Athlon              | 1         | 0.35%   |
| AMD A8                  | 1         | 0.35%   |
| AMD A6                  | 1         | 0.35%   |
| AMD A10                 | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 109       | 38.25%  |
| 4      | 102       | 35.79%  |
| 6      | 28        | 9.82%   |
| 8      | 25        | 8.77%   |
| 1      | 7         | 2.46%   |
| 12     | 6         | 2.11%   |
| 14     | 3         | 1.05%   |
| 10     | 3         | 1.05%   |
| 16     | 1         | 0.35%   |
| 5      | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 282       | 98.95%  |
| 2      | 3         | 1.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 185       | 64.91%  |
| 1      | 100       | 35.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 280       | 98.25%  |
| 32-bit         | 5         | 1.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 9.69%   |
| 0x206a7    | 21        | 7.27%   |
| 0x306a9    | 19        | 6.57%   |
| 0x306c3    | 14        | 4.84%   |
| 0x806c1    | 12        | 4.15%   |
| 0x1067a    | 11        | 3.81%   |
| 0x506e3    | 9         | 3.11%   |
| 0x0a50000c | 9         | 3.11%   |
| 0x406e3    | 8         | 2.77%   |
| 0x20655    | 8         | 2.77%   |
| 0x906ea    | 7         | 2.42%   |
| 0x806ec    | 5         | 1.73%   |
| 0x806ea    | 5         | 1.73%   |
| 0x806e9    | 5         | 1.73%   |
| 0x706a8    | 5         | 1.73%   |
| 0x08608103 | 5         | 1.73%   |
| 0xa0652    | 4         | 1.38%   |
| 0x906ed    | 4         | 1.38%   |
| 0x906a3    | 4         | 1.38%   |
| 0x6fd      | 4         | 1.38%   |
| 0x306d4    | 4         | 1.38%   |
| 0x30678    | 4         | 1.38%   |
| 0x08108109 | 4         | 1.38%   |
| 0x906c0    | 3         | 1.04%   |
| 0x906a4    | 3         | 1.04%   |
| 0x706a1    | 3         | 1.04%   |
| 0x406c4    | 3         | 1.04%   |
| 0x40651    | 3         | 1.04%   |
| 0x106e5    | 3         | 1.04%   |
| 0x08701021 | 3         | 1.04%   |
| 0x08600106 | 3         | 1.04%   |
| 0x0800820d | 3         | 1.04%   |
| 0x010000db | 3         | 1.04%   |
| 0xa0671    | 2         | 0.69%   |
| 0xa0653    | 2         | 0.69%   |
| 0x906e9    | 2         | 0.69%   |
| 0x806d1    | 2         | 0.69%   |
| 0x506c9    | 2         | 0.69%   |
| 0x306f2    | 2         | 0.69%   |
| 0x106ca    | 2         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 10.84%  |
| Haswell          | 24        | 8.39%   |
| SandyBridge      | 23        | 8.04%   |
| IvyBridge        | 20        | 6.99%   |
| Skylake          | 19        | 6.64%   |
| Zen 3            | 17        | 5.94%   |
| Penryn           | 14        | 4.9%    |
| TigerLake        | 13        | 4.55%   |
| Unknown          | 12        | 4.2%    |
| Zen+             | 11        | 3.85%   |
| Westmere         | 11        | 3.85%   |
| Silvermont       | 8         | 2.8%    |
| Goldmont plus    | 8         | 2.8%    |
| Zen 2            | 7         | 2.45%   |
| K10              | 7         | 2.45%   |
| Core             | 7         | 2.45%   |
| CometLake        | 7         | 2.45%   |
| IceLake          | 6         | 2.1%    |
| Nehalem          | 5         | 1.75%   |
| Broadwell        | 5         | 1.75%   |
| Alderlake Hybrid | 5         | 1.75%   |
| Zen              | 3         | 1.05%   |
| Tremont          | 3         | 1.05%   |
| P6               | 3         | 1.05%   |
| Goldmont         | 3         | 1.05%   |
| Bonnell          | 3         | 1.05%   |
| Puma             | 2         | 0.7%    |
| NetBurst         | 2         | 0.7%    |
| K8 Hammer        | 2         | 0.7%    |
| Excavator        | 2         | 0.7%    |
| Piledriver       | 1         | 0.35%   |
| K8 & K10 hybrid  | 1         | 0.35%   |
| Bobcat           | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 178       | 53.13%  |
| Nvidia                     | 81        | 24.18%  |
| AMD                        | 75        | 22.39%  |
| Matrox Electronics Systems | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 5.2%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 4.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 3.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 2.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.31%   |
| Intel HD Graphics 530                                                                    | 7         | 2.02%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.73%   |
| AMD Lucienne                                                                             | 6         | 1.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.45%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.45%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.16%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.16%   |
| Intel HD Graphics 620                                                                    | 4         | 1.16%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.16%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 1.16%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.16%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3         | 0.87%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.87%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.87%   |
| Intel HD Graphics 500                                                                    | 3         | 0.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.87%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.87%   |
| AMD Renoir                                                                               | 3         | 0.87%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 3         | 0.87%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 0.87%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 2         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 132       | 46.32%  |
| 1 x AMD        | 58        | 20.35%  |
| 1 x Nvidia     | 47        | 16.49%  |
| Intel + Nvidia | 29        | 10.18%  |
| Intel + AMD    | 9         | 3.16%   |
| 2 x AMD        | 4         | 1.4%    |
| AMD + Nvidia   | 4         | 1.4%    |
| 2 x Intel      | 1         | 0.35%   |
| 1 x Matrox     | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 234       | 80.69%  |
| Proprietary | 40        | 13.79%  |
| Unknown     | 16        | 5.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 182       | 62.98%  |
| 0.01-0.5   | 30        | 10.38%  |
| 3.01-4.0   | 19        | 6.57%   |
| 1.01-2.0   | 19        | 6.57%   |
| 0.51-1.0   | 17        | 5.88%   |
| 7.01-8.0   | 14        | 4.84%   |
| 8.01-16.0  | 5         | 1.73%   |
| 2.01-3.0   | 3         | 1.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 36        | 11.8%   |
| Chimei Innolux          | 34        | 11.15%  |
| AU Optronics            | 32        | 10.49%  |
| LG Display              | 20        | 6.56%   |
| Dell                    | 17        | 5.57%   |
| BOE                     | 17        | 5.57%   |
| Hewlett-Packard         | 15        | 4.92%   |
| Apple                   | 11        | 3.61%   |
| Acer                    | 10        | 3.28%   |
| Lenovo                  | 9         | 2.95%   |
| Goldstar                | 9         | 2.95%   |
| Sony                    | 8         | 2.62%   |
| PANDA                   | 8         | 2.62%   |
| Chi Mei Optoelectronics | 8         | 2.62%   |
| Ancor Communications    | 8         | 2.62%   |
| AOC                     | 6         | 1.97%   |
| Sharp                   | 4         | 1.31%   |
| Philips                 | 4         | 1.31%   |
| Fujitsu Siemens         | 4         | 1.31%   |
| Eizo                    | 4         | 1.31%   |
| Iiyama                  | 3         | 0.98%   |
| BenQ                    | 3         | 0.98%   |
| Panasonic               | 2         | 0.66%   |
| NEC Computers           | 2         | 0.66%   |
| MSI                     | 2         | 0.66%   |
| MiTAC                   | 2         | 0.66%   |
| Medion                  | 2         | 0.66%   |
| CPT                     | 2         | 0.66%   |
| Xiaomi                  | 1         | 0.33%   |
| Vizio                   | 1         | 0.33%   |
| ViewSonic               | 1         | 0.33%   |
| Vestel Elektronik       | 1         | 0.33%   |
| Sunplus                 | 1         | 0.33%   |
| STA                     | 1         | 0.33%   |
| SAC                     | 1         | 0.33%   |
| RTK                     | 1         | 0.33%   |
| PRI                     | 1         | 0.33%   |
| Packard Bell            | 1         | 0.33%   |
| ONN                     | 1         | 0.33%   |
| LTM                     | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 1.29%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.96%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                       | 2         | 0.64%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch        | 2         | 0.64%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.64%   |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                          | 2         | 0.64%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 0.64%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.64%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 2         | 0.64%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.64%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.64%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.64%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                         | 2         | 0.64%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 2         | 0.64%   |
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                       | 1         | 0.32%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                       | 1         | 0.32%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch                | 1         | 0.32%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 1         | 0.32%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.32%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.32%   |
| Sony TV SNY3001 1920x1080                                                | 1         | 0.32%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                     | 1         | 0.32%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                       | 1         | 0.32%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.32%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 1         | 0.32%   |
| Sony CPD-200SX SNY0570 1920x1080 698x392mm 31.5-inch                     | 1         | 0.32%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP1445 3840x2160 346x194mm 15.6-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.32%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch        | 1         | 0.32%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch     | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 127       | 43.49%  |
| 1366x768 (WXGA)    | 48        | 16.44%  |
| 3840x2160 (4K)     | 23        | 7.88%   |
| 1680x1050 (WSXGA+) | 13        | 4.45%   |
| 2560x1440 (QHD)    | 12        | 4.11%   |
| 1280x1024 (SXGA)   | 11        | 3.77%   |
| 1600x900 (HD+)     | 9         | 3.08%   |
| 1920x1200 (WUXGA)  | 6         | 2.05%   |
| 1440x900 (WXGA+)   | 6         | 2.05%   |
| 1280x800 (WXGA)    | 6         | 2.05%   |
| 2880x1800          | 3         | 1.03%   |
| 2560x1600          | 3         | 1.03%   |
| 2560x1080          | 3         | 1.03%   |
| 2160x1440          | 3         | 1.03%   |
| 1360x768           | 3         | 1.03%   |
| 3440x1440          | 2         | 0.68%   |
| 2256x1504          | 2         | 0.68%   |
| 1280x720 (HD)      | 2         | 0.68%   |
| 1024x768 (XGA)     | 2         | 0.68%   |
| 1024x600           | 2         | 0.68%   |
| Unknown            | 2         | 0.68%   |
| 3840x2400          | 1         | 0.34%   |
| 3840x1080          | 1         | 0.34%   |
| 2736x1824          | 1         | 0.34%   |
| 1400x1050          | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 81        | 26.82%  |
| 23      | 24        | 7.95%   |
| 13      | 23        | 7.62%   |
| 27      | 21        | 6.95%   |
| 24      | 21        | 6.95%   |
| 17      | 21        | 6.95%   |
| 14      | 17        | 5.63%   |
| 21      | 12        | 3.97%   |
| Unknown | 10        | 3.31%   |
| 31      | 9         | 2.98%   |
| 22      | 9         | 2.98%   |
| 11      | 8         | 2.65%   |
| 19      | 7         | 2.32%   |
| 34      | 5         | 1.66%   |
| 18      | 4         | 1.32%   |
| 12      | 4         | 1.32%   |
| 84      | 3         | 0.99%   |
| 40      | 3         | 0.99%   |
| 16      | 3         | 0.99%   |
| 10      | 3         | 0.99%   |
| 26      | 2         | 0.66%   |
| 20      | 2         | 0.66%   |
| 65      | 1         | 0.33%   |
| 61      | 1         | 0.33%   |
| 54      | 1         | 0.33%   |
| 47      | 1         | 0.33%   |
| 46      | 1         | 0.33%   |
| 43      | 1         | 0.33%   |
| 42      | 1         | 0.33%   |
| 36      | 1         | 0.33%   |
| 32      | 1         | 0.33%   |
| 25      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 112       | 37.46%  |
| 501-600     | 64        | 21.4%   |
| 401-500     | 28        | 9.36%   |
| 201-300     | 28        | 9.36%   |
| 351-400     | 27        | 9.03%   |
| 601-700     | 10        | 3.34%   |
| Unknown     | 10        | 3.34%   |
| 701-800     | 7         | 2.34%   |
| 1001-1500   | 5         | 1.67%   |
| 801-900     | 3         | 1%      |
| 1501-2000   | 3         | 1%      |
| 901-1000    | 2         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 209       | 74.64%  |
| 16/10   | 39        | 13.93%  |
| 5/4     | 11        | 3.93%   |
| 3/2     | 6         | 2.14%   |
| Unknown | 6         | 2.14%   |
| 21/9    | 5         | 1.79%   |
| 4/3     | 4         | 1.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 81        | 26.91%  |
| 201-250        | 54        | 17.94%  |
| 81-90          | 32        | 10.63%  |
| 301-350        | 22        | 7.31%   |
| 121-130        | 18        | 5.98%   |
| 151-200        | 16        | 5.32%   |
| 351-500        | 15        | 4.98%   |
| Unknown        | 10        | 3.32%   |
| 251-300        | 9         | 2.99%   |
| 71-80          | 8         | 2.66%   |
| 51-60          | 8         | 2.66%   |
| 501-1000       | 8         | 2.66%   |
| More than 1000 | 6         | 1.99%   |
| 141-150        | 5         | 1.66%   |
| 61-70          | 3         | 1%      |
| 41-50          | 3         | 1%      |
| 91-100         | 2         | 0.66%   |
| 111-120        | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 111       | 37.76%  |
| 121-160       | 83        | 28.23%  |
| 101-120       | 58        | 19.73%  |
| 161-240       | 17        | 5.78%   |
| Unknown       | 10        | 3.4%    |
| 1-50          | 8         | 2.72%   |
| More than 240 | 7         | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 228       | 78.62%  |
| 2     | 42        | 14.48%  |
| 0     | 15        | 5.17%   |
| 3     | 5         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 149       | 32.96%  |
| Intel                             | 143       | 31.64%  |
| Qualcomm Atheros                  | 46        | 10.18%  |
| Broadcom                          | 26        | 5.75%   |
| MediaTek                          | 12        | 2.65%   |
| TP-Link                           | 10        | 2.21%   |
| Broadcom Limited                  | 9         | 1.99%   |
| Ralink Technology                 | 7         | 1.55%   |
| Marvell Technology Group          | 7         | 1.55%   |
| Ralink                            | 5         | 1.11%   |
| Nvidia                            | 4         | 0.88%   |
| Qualcomm Atheros Communications   | 3         | 0.66%   |
| Microsoft                         | 3         | 0.66%   |
| AVM                               | 3         | 0.66%   |
| Sierra Wireless                   | 2         | 0.44%   |
| Samsung Electronics               | 2         | 0.44%   |
| Motorola PCS                      | 2         | 0.44%   |
| ASIX Electronics                  | 2         | 0.44%   |
| Xiaomi                            | 1         | 0.22%   |
| VIA Technologies                  | 1         | 0.22%   |
| Sweex                             | 1         | 0.22%   |
| OPPO Electronics                  | 1         | 0.22%   |
| NetGear                           | 1         | 0.22%   |
| Mercucys                          | 1         | 0.22%   |
| Linksys                           | 1         | 0.22%   |
| Lenovo                            | 1         | 0.22%   |
| JMicron Technology                | 1         | 0.22%   |
| Ericsson Business Mobile Networks | 1         | 0.22%   |
| Edimax Technology                 | 1         | 0.22%   |
| Dell                              | 1         | 0.22%   |
| D-Link                            | 1         | 0.22%   |
| Attansic Technology               | 1         | 0.22%   |
| ASUSTek Computer                  | 1         | 0.22%   |
| Aquantia                          | 1         | 0.22%   |
| Apple                             | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 99        | 18.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 2.66%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 2.09%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 1.9%    |
| Intel Wireless 8260                                               | 9         | 1.71%   |
| Intel Ethernet Controller I225-V                                  | 9         | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 1.14%   |
| Intel Wireless 7265                                               | 6         | 1.14%   |
| Intel Wireless 3165                                               | 6         | 1.14%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.14%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 5         | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.95%   |
| Intel Wireless 8265 / 8275                                        | 5         | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 5         | 0.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 0.95%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 0.95%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 0.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4         | 0.76%   |
| Intel Wireless 7260                                               | 4         | 0.76%   |
| Intel I211 Gigabit Network Connection                             | 4         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 0.76%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 0.76%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 4         | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.57%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 109       | 42.58%  |
| Realtek Semiconductor           | 43        | 16.8%   |
| Qualcomm Atheros                | 30        | 11.72%  |
| Broadcom                        | 18        | 7.03%   |
| MediaTek                        | 12        | 4.69%   |
| TP-Link                         | 9         | 3.52%   |
| Ralink Technology               | 7         | 2.73%   |
| Broadcom Limited                | 6         | 2.34%   |
| Ralink                          | 5         | 1.95%   |
| Qualcomm Atheros Communications | 3         | 1.17%   |
| AVM                             | 3         | 1.17%   |
| Sierra Wireless                 | 2         | 0.78%   |
| Sweex                           | 1         | 0.39%   |
| NetGear                         | 1         | 0.39%   |
| Microsoft                       | 1         | 0.39%   |
| Mercucys                        | 1         | 0.39%   |
| Marvell Technology Group        | 1         | 0.39%   |
| Linksys                         | 1         | 0.39%   |
| Edimax Technology               | 1         | 0.39%   |
| D-Link                          | 1         | 0.39%   |
| ASUSTek Computer                | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 13        | 5.08%   |
| Intel Wi-Fi 6 AX201                                            | 10        | 3.91%   |
| Intel Wireless 8260                                            | 9         | 3.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 2.34%   |
| Intel Wireless 7265                                            | 6         | 2.34%   |
| Intel Wireless 3165                                            | 6         | 2.34%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 5         | 1.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5         | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 1.95%   |
| Intel Wireless 8265 / 8275                                     | 5         | 1.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 5         | 1.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 1.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 1.95%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 1.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 1.56%   |
| Intel Wireless 7260                                            | 4         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.56%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 1.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.17%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 1.17%   |
| Intel Wireless 3160                                            | 3         | 1.17%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.17%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                     | 2         | 0.78%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 2         | 0.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.78%   |
| Realtek 802.11ac NIC                                           | 2         | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 128       | 49.81%  |
| Intel                    | 66        | 25.68%  |
| Qualcomm Atheros         | 20        | 7.78%   |
| Broadcom                 | 15        | 5.84%   |
| Marvell Technology Group | 6         | 2.33%   |
| Nvidia                   | 4         | 1.56%   |
| Broadcom Limited         | 3         | 1.17%   |
| Microsoft                | 2         | 0.78%   |
| ASIX Electronics         | 2         | 0.78%   |
| Xiaomi                   | 1         | 0.39%   |
| VIA Technologies         | 1         | 0.39%   |
| TP-Link                  | 1         | 0.39%   |
| Samsung Electronics      | 1         | 0.39%   |
| OPPO Electronics         | 1         | 0.39%   |
| Motorola PCS             | 1         | 0.39%   |
| Lenovo                   | 1         | 0.39%   |
| JMicron Technology       | 1         | 0.39%   |
| Attansic Technology      | 1         | 0.39%   |
| Aquantia                 | 1         | 0.39%   |
| Apple                    | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 99        | 37.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 5.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 4.15%   |
| Intel Ethernet Controller I225-V                                  | 9         | 3.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 2.26%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 2.26%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 1.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.51%   |
| Intel I211 Gigabit Network Connection                             | 4         | 1.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 1.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 1.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.13%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.13%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.13%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 1.13%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.13%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.75%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.75%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.75%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                 | 2         | 0.75%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.75%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.75%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.75%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.75%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.75%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.38%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.38%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 244       | 50.83%  |
| WiFi     | 231       | 48.13%  |
| Modem    | 4         | 0.83%   |
| Unknown  | 1         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 185       | 63.36%  |
| Ethernet | 107       | 36.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 161       | 56.29%  |
| 1     | 113       | 39.51%  |
| 3     | 7         | 2.45%   |
| 0     | 4         | 1.4%    |
| 4     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 204       | 71.08%  |
| Yes  | 83        | 28.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 81        | 45.51%  |
| Qualcomm Atheros Communications | 15        | 8.43%   |
| Apple                           | 15        | 8.43%   |
| Realtek Semiconductor           | 14        | 7.87%   |
| Cambridge Silicon Radio         | 10        | 5.62%   |
| Foxconn / Hon Hai               | 9         | 5.06%   |
| Broadcom                        | 9         | 5.06%   |
| IMC Networks                    | 5         | 2.81%   |
| MediaTek                        | 4         | 2.25%   |
| Lite-On Technology              | 4         | 2.25%   |
| Hewlett-Packard                 | 3         | 1.69%   |
| ASUSTek Computer                | 3         | 1.69%   |
| Ralink                          | 2         | 1.12%   |
| TP-Link                         | 1         | 0.56%   |
| Marvell Semiconductor           | 1         | 0.56%   |
| Dell                            | 1         | 0.56%   |
| Alps Electric                   | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 30        | 16.85%  |
| Intel AX201 Bluetooth                                                               | 16        | 8.99%   |
| Intel AX200 Bluetooth                                                               | 13        | 7.3%    |
| Realtek Bluetooth Radio                                                             | 12        | 6.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 5.62%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 5.62%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 4.49%   |
| Apple Bluetooth Host Controller                                                     | 6         | 3.37%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 2.81%   |
| MediaTek Wireless_Device                                                            | 4         | 2.25%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 2.25%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.69%   |
| Intel Bluetooth Device                                                              | 3         | 1.69%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.69%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.12%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.12%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.12%   |
| Lite-On Wireless_Device                                                             | 2         | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.12%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.12%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.12%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.12%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.12%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.12%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.12%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 1.12%   |
| Apple Bluetooth HCI                                                                 | 2         | 1.12%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.56%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.56%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.56%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.56%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.56%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.56%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.56%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 214       | 52.97%  |
| AMD                        | 73        | 18.07%  |
| Nvidia                     | 66        | 16.34%  |
| C-Media Electronics        | 7         | 1.73%   |
| Creative Labs              | 5         | 1.24%   |
| VIA Technologies           | 3         | 0.74%   |
| Texas Instruments          | 3         | 0.74%   |
| ROCCAT                     | 2         | 0.5%    |
| Realtek Semiconductor      | 2         | 0.5%    |
| JMTek                      | 2         | 0.5%    |
| Generalplus Technology     | 2         | 0.5%    |
| BEHRINGER International    | 2         | 0.5%    |
| Apple                      | 2         | 0.5%    |
| TerraTec Electronic        | 1         | 0.25%   |
| Shenzhen Riitek Technology | 1         | 0.25%   |
| Setek Elektronik           | 1         | 0.25%   |
| Schiit Audio               | 1         | 0.25%   |
| Razer USA                  | 1         | 0.25%   |
| Plantronics                | 1         | 0.25%   |
| Microsoft                  | 1         | 0.25%   |
| Logitech                   | 1         | 0.25%   |
| LG Electronics             | 1         | 0.25%   |
| Lenovo                     | 1         | 0.25%   |
| GYROCOM C&C                | 1         | 0.25%   |
| Guillemot                  | 1         | 0.25%   |
| GN Netcom                  | 1         | 0.25%   |
| Focusrite-Novation         | 1         | 0.25%   |
| FIFINE 683 Microphone      | 1         | 0.25%   |
| Ensoniq                    | 1         | 0.25%   |
| Digidesign                 | 1         | 0.25%   |
| Dell                       | 1         | 0.25%   |
| Creative Technology        | 1         | 0.25%   |
| Conexant Systems           | 1         | 0.25%   |
| CMX Systems                | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 31        | 6.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23        | 4.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 21        | 4.46%   |
| Intel Sunrise Point-LP HD Audio                                            | 20        | 4.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19        | 4.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 2.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 2.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 2.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 2.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9         | 1.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 1.7%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 1.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 1.49%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 1.49%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 1.27%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 1.06%   |
| Nvidia Audio device                                                        | 5         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.06%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 1.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 0.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 0.85%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.85%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4         | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4         | 0.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 0.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.64%   |
| Nvidia GM206 High Definition Audio Controller                              | 3         | 0.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.64%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 68        | 20.36%  |
| SK hynix            | 57        | 17.07%  |
| Unknown             | 37        | 11.08%  |
| Kingston            | 35        | 10.48%  |
| Micron Technology   | 27        | 8.08%   |
| Crucial             | 19        | 5.69%   |
| Corsair             | 16        | 4.79%   |
| G.Skill             | 11        | 3.29%   |
| A-DATA Technology   | 10        | 2.99%   |
| Ramaxel Technology  | 9         | 2.69%   |
| Elpida              | 8         | 2.4%    |
| Unknown (ABCD)      | 6         | 1.8%    |
| Unknown             | 5         | 1.5%    |
| Transcend           | 4         | 1.2%    |
| Nanya Technology    | 4         | 1.2%    |
| Smart               | 2         | 0.6%    |
| Avant               | 2         | 0.6%    |
| Wilk                | 1         | 0.3%    |
| Unknown (AB)        | 1         | 0.3%    |
| Unifosa             | 1         | 0.3%    |
| Team                | 1         | 0.3%    |
| PNY                 | 1         | 0.3%    |
| Patriot             | 1         | 0.3%    |
| Innodisk            | 1         | 0.3%    |
| Hewlett-Packard     | 1         | 0.3%    |
| Golden Empire       | 1         | 0.3%    |
| Essencore           | 1         | 0.3%    |
| CSX                 | 1         | 0.3%    |
| ASint Technology    | 1         | 0.3%    |
| Apacer              | 1         | 0.3%    |
| 48spaces            | 1         | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 1.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.4%    |
| Unknown                                                          | 5         | 1.4%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 4         | 1.12%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.12%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.12%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4         | 1.12%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.84%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.84%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 2         | 0.56%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 2         | 0.56%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 0.56%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.56%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.56%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s             | 2         | 0.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.56%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.56%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.56%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.56%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.56%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s              | 2         | 0.56%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.56%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s            | 2         | 0.56%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.56%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 0.56%   |
| Crucial RAM CT16G4SFRA32A.C16FR 16GB SODIMM DDR4 3200MT/s        | 2         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 123       | 42.56%  |
| DDR3    | 110       | 38.06%  |
| DDR2    | 15        | 5.19%   |
| LPDDR4  | 14        | 4.84%   |
| SDRAM   | 8         | 2.77%   |
| Unknown | 7         | 2.42%   |
| DDR     | 6         | 2.08%   |
| LPDDR3  | 4         | 1.38%   |
| DRAM    | 1         | 0.35%   |
| DDR5    | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 185       | 64.46%  |
| DIMM         | 86        | 29.97%  |
| Row Of Chips | 15        | 5.23%   |
| Unknown      | 1         | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 98        | 31.41%  |
| 4096  | 96        | 30.77%  |
| 2048  | 51        | 16.35%  |
| 16384 | 42        | 13.46%  |
| 1024  | 13        | 4.17%   |
| 32768 | 10        | 3.21%   |
| 512   | 1         | 0.32%   |
| 256   | 1         | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 63        | 20.52%  |
| 3200    | 51        | 16.61%  |
| 2667    | 31        | 10.1%   |
| 1333    | 28        | 9.12%   |
| 2400    | 22        | 7.17%   |
| Unknown | 14        | 4.56%   |
| 2133    | 12        | 3.91%   |
| 3600    | 11        | 3.58%   |
| 1334    | 11        | 3.58%   |
| 667     | 11        | 3.58%   |
| 1067    | 6         | 1.95%   |
| 800     | 5         | 1.63%   |
| 1867    | 4         | 1.3%    |
| 4267    | 3         | 0.98%   |
| 4199    | 3         | 0.98%   |
| 2666    | 3         | 0.98%   |
| 3733    | 2         | 0.65%   |
| 3400    | 2         | 0.65%   |
| 2933    | 2         | 0.65%   |
| 2048    | 2         | 0.65%   |
| 1066    | 2         | 0.65%   |
| 333     | 2         | 0.65%   |
| 8400    | 1         | 0.33%   |
| 4800    | 1         | 0.33%   |
| 4266    | 1         | 0.33%   |
| 4133    | 1         | 0.33%   |
| 3866    | 1         | 0.33%   |
| 3466    | 1         | 0.33%   |
| 3266    | 1         | 0.33%   |
| 3000    | 1         | 0.33%   |
| 2200    | 1         | 0.33%   |
| 2000    | 1         | 0.33%   |
| 1866    | 1         | 0.33%   |
| 1800    | 1         | 0.33%   |
| 1639    | 1         | 0.33%   |
| 975     | 1         | 0.33%   |
| 533     | 1         | 0.33%   |
| 400     | 1         | 0.33%   |
| 166     | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 4         | 44.44%  |
| Brother Industries | 3         | 33.33%  |
| Hewlett-Packard    | 2         | 22.22%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon MF641C             | 2         | 22.22%  |
| HP LaserJet P2055 series | 1         | 11.11%  |
| HP LaserJet 1022         | 1         | 11.11%  |
| Canon MG5700 series      | 1         | 11.11%  |
| Canon LiDE 400           | 1         | 11.11%  |
| Brother MFC-7340         | 1         | 11.11%  |
| Brother HL-2150N series  | 1         | 11.11%  |
| Brother DCP-L2540DW      | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |
| Canon CanoScan LiDE 210       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 39        | 22.81%  |
| Microdia                               | 15        | 8.77%   |
| Realtek Semiconductor                  | 12        | 7.02%   |
| IMC Networks                           | 11        | 6.43%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 5.85%   |
| Apple                                  | 9         | 5.26%   |
| Quanta                                 | 8         | 4.68%   |
| Acer                                   | 8         | 4.68%   |
| Logitech                               | 7         | 4.09%   |
| Bison Electronics                      | 7         | 4.09%   |
| Sunplus Innovation Technology          | 6         | 3.51%   |
| Suyin                                  | 5         | 2.92%   |
| Lite-On Technology                     | 5         | 2.92%   |
| Ricoh                                  | 4         | 2.34%   |
| Microsoft                              | 3         | 1.75%   |
| Luxvisions Innotech Limited            | 3         | 1.75%   |
| Lenovo                                 | 3         | 1.75%   |
| Silicon Motion                         | 2         | 1.17%   |
| Hewlett-Packard                        | 2         | 1.17%   |
| Alcor Micro                            | 2         | 1.17%   |
| Z-Star Microelectronics                | 1         | 0.58%   |
| Y Media                                | 1         | 0.58%   |
| Sonix Technology                       | 1         | 0.58%   |
| Primax Electronics                     | 1         | 0.58%   |
| Novatek Microelectronics               | 1         | 0.58%   |
| LG Electronics                         | 1         | 0.58%   |
| Goodong Industry                       | 1         | 0.58%   |
| Generalplus Technology                 | 1         | 0.58%   |
| GEMBIRD                                | 1         | 0.58%   |
| Arkmicro Technologies                  | 1         | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 7         | 4.07%   |
| Microdia Integrated_Webcam_HD                       | 5         | 2.91%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 2.91%   |
| Quanta HD User Facing                               | 4         | 2.33%   |
| Apple Built-in iSight                               | 4         | 2.33%   |
| Realtek Integrated_Webcam_HD                        | 3         | 1.74%   |
| IMC Networks Integrated Camera                      | 3         | 1.74%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.74%   |
| Chicony HD User Facing                              | 3         | 1.74%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 1.74%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 1.74%   |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 1.74%   |
| Acer Integrated Camera                              | 3         | 1.74%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.16%   |
| Sunplus HD 720P webcam                              | 2         | 1.16%   |
| Ricoh USB2.0 Camera                                 | 2         | 1.16%   |
| Realtek USB Camera                                  | 2         | 1.16%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.16%   |
| Microsoft LifeCam HD-3000                           | 2         | 1.16%   |
| Microdia Webcam Vitade AF                           | 2         | 1.16%   |
| Logitech Webcam C930e                               | 2         | 1.16%   |
| Logitech Webcam C270                                | 2         | 1.16%   |
| Lite-On HP HD Camera                                | 2         | 1.16%   |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 1.16%   |
| Chicony HD WebCam                                   | 2         | 1.16%   |
| Bison Integrated Camera                             | 2         | 1.16%   |
| Bison HD Webcam                                     | 2         | 1.16%   |
| Bison BisonCam,NB Pro                               | 2         | 1.16%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 0.58%   |
| Y Media USB Camera                                  | 1         | 0.58%   |
| Suyin Sony Visual Communication Camera              | 1         | 0.58%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.58%   |
| Suyin HP Webcam-101                                 | 1         | 0.58%   |
| Suyin HP Webcam                                     | 1         | 0.58%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.58%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 0.58%   |
| Sunplus ASUS Webcam                                 | 1         | 0.58%   |
| Sonix USB Camera                                    | 1         | 0.58%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.58%   |
| Silicon Motion Web Camera                           | 1         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 21.88%  |
| Synaptics                  | 7         | 21.88%  |
| Shenzhen Goodix Technology | 6         | 18.75%  |
| AuthenTec                  | 5         | 15.63%  |
| Upek                       | 3         | 9.38%   |
| Elan Microelectronics      | 2         | 6.25%   |
| Microsoft                  | 1         | 3.13%   |
| Focal-systems.Corp         | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                      | 5         | 15.63%  |
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 9.38%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 3         | 9.38%   |
| AuthenTec AES2810                                        | 3         | 9.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 2         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 2         | 6.25%   |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 3.13%   |
| Upek TCS5B Fingerprint sensor                            | 1         | 3.13%   |
| Synaptics WBDI Fingerprint Reader USB 102                | 1         | 3.13%   |
| Synaptics UWP WBDI Device                                | 1         | 3.13%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 3.13%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.13%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 3.13%   |
| Microsoft Fingerprint Reader                             | 1         | 3.13%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 3.13%   |
| Elan ELAN:Fingerprint                                    | 1         | 3.13%   |
| Elan ELAN:ARM-M4                                         | 1         | 3.13%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 3.13%   |
| AuthenTec AES1660 Fingerprint Sensor                     | 1         | 3.13%   |
| Unknown                                                  | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 41.67%  |
| Alcor Micro           | 5         | 41.67%  |
| Advanced Card Systems | 2         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 5         | 41.67%  |
| Broadcom 5880                                  | 4         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 8.33%   |
| Advanced Card Systems ACR38 SmartCard Reader   | 1         | 8.33%   |
| Advanced Card Systems ACR122U                  | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 200       | 68.49%  |
| 1     | 69        | 23.63%  |
| 2     | 19        | 6.51%   |
| 3     | 4         | 1.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 43        | 38.39%  |
| Fingerprint reader       | 32        | 28.57%  |
| Chipcard                 | 10        | 8.93%   |
| Net/wireless             | 7         | 6.25%   |
| Multimedia controller    | 5         | 4.46%   |
| Communication controller | 4         | 3.57%   |
| Unassigned class         | 3         | 2.68%   |
| Net/ethernet             | 2         | 1.79%   |
| Camera                   | 2         | 1.79%   |
| Sound                    | 1         | 0.89%   |
| Flash memory             | 1         | 0.89%   |
| Dvb card                 | 1         | 0.89%   |
| Bluetooth                | 1         | 0.89%   |

