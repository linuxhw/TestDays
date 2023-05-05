MX - Tested Hardware & Statistics
---------------------------------

A project to collect tested hardware configurations for MX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX/Desktop/README.md) and [notebooks](/Dist/MX/Notebook/README.md).

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

Total: 740

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3190               | Notebook    | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [e812a255a4](https://linux-hardware.org/?probe=e812a255a4) | May 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [539369db0e](https://linux-hardware.org/?probe=539369db0e) | Apr 28, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [014215365a](https://linux-hardware.org/?probe=014215365a) | Apr 27, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [a37deef915](https://linux-hardware.org/?probe=a37deef915) | Apr 24, 2023 |
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
| Positivo      | POS-PQ45AU POSITIVO         | Desktop     | [8ed6dacaa7](https://linux-hardware.org/?probe=8ed6dacaa7) | Feb 23, 2023 |
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
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [e6f4812d50](https://linux-hardware.org/?probe=e6f4812d50) | Feb 07, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [11f3874a6f](https://linux-hardware.org/?probe=11f3874a6f) | Feb 07, 2023 |
| HP            | 450                         | Notebook    | [26d3505372](https://linux-hardware.org/?probe=26d3505372) | Feb 06, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [a255954f75](https://linux-hardware.org/?probe=a255954f75) | Feb 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [48f423dfae](https://linux-hardware.org/?probe=48f423dfae) | Feb 05, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [ed6c6cc366](https://linux-hardware.org/?probe=ed6c6cc366) | Feb 05, 2023 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [dc948f9e70](https://linux-hardware.org/?probe=dc948f9e70) | Feb 05, 2023 |
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
| Dell          | Latitude 7480               | Notebook    | [2e485b361c](https://linux-hardware.org/?probe=2e485b361c) | Nov 14, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [cb36e9d15c](https://linux-hardware.org/?probe=cb36e9d15c) | Nov 09, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [732e924bbb](https://linux-hardware.org/?probe=732e924bbb) | Nov 07, 2022 |
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
| ASRock        | H370M-ITX/ac                | Desktop     | [fa925dcefb](https://linux-hardware.org/?probe=fa925dcefb) | Oct 24, 2022 |
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
| Lenovo        | ThinkPad T420 4236TL7       | Notebook    | [8a639f4457](https://linux-hardware.org/?probe=8a639f4457) | Oct 10, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [f2c440fdf6](https://linux-hardware.org/?probe=f2c440fdf6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [8159009c50](https://linux-hardware.org/?probe=8159009c50) | Oct 05, 2022 |
| Google        | Setzer                      | Notebook    | [6bafaabd48](https://linux-hardware.org/?probe=6bafaabd48) | Oct 04, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [bb43eb5333](https://linux-hardware.org/?probe=bb43eb5333) | Oct 04, 2022 |
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
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | Notebook    | [f8f2a6263a](https://linux-hardware.org/?probe=f8f2a6263a) | Sep 04, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [1a577be107](https://linux-hardware.org/?probe=1a577be107) | Sep 04, 2022 |
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
| Acer          | Extensa 5630                | Notebook    | [9ea053d8e8](https://linux-hardware.org/?probe=9ea053d8e8) | Aug 12, 2022 |
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
| UMAX          | VisionBook-N12R             | Notebook    | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
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
| ASUSTek       | M4A785-M                    | Desktop     | [03878be4ec](https://linux-hardware.org/?probe=03878be4ec) | Apr 20, 2022 |
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
| Gigabyte      | P35-DS3P                    | Desktop     | [9c4373296f](https://linux-hardware.org/?probe=9c4373296f) | Mar 21, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Acer          | Extensa 5630                | Notebook    | [32cab1f9fc](https://linux-hardware.org/?probe=32cab1f9fc) | Mar 14, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [4521c22268](https://linux-hardware.org/?probe=4521c22268) | Mar 06, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [ecc5ad7332](https://linux-hardware.org/?probe=ecc5ad7332) | Feb 25, 2022 |
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
| ASRock        | FM2A68M-HD+ R2.0            | Desktop     | [d0ba3786b2](https://linux-hardware.org/?probe=d0ba3786b2) | Feb 03, 2022 |
| HP            | ProBook 6460b               | Notebook    | [5f936a65be](https://linux-hardware.org/?probe=5f936a65be) | Feb 02, 2022 |
| Intel         | H81                         | Desktop     | [c1763fe2cf](https://linux-hardware.org/?probe=c1763fe2cf) | Jan 29, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Acer          | Spin SP111-31               | Convertible | [21bfc2a904](https://linux-hardware.org/?probe=21bfc2a904) | Jan 16, 2022 |
| IBM           | 8183B2U                     | Desktop     | [d070680dfb](https://linux-hardware.org/?probe=d070680dfb) | Jan 14, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| Gigabyte      | F2A88X-UP4                  | Desktop     | [52e09bab91](https://linux-hardware.org/?probe=52e09bab91) | Jan 02, 2022 |
| HP            | 2000                        | Notebook    | [5d64fe5b92](https://linux-hardware.org/?probe=5d64fe5b92) | Jan 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | Notebook    | [63d7055c5e](https://linux-hardware.org/?probe=63d7055c5e) | Dec 18, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Toshiba       | Satellite L850-CJK          | Notebook    | [0dc076ad15](https://linux-hardware.org/?probe=0dc076ad15) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | Unknown                     | Notebook    | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| ECS           | A55F-M3                     | Desktop     | [5439a8e37c](https://linux-hardware.org/?probe=5439a8e37c) | Nov 27, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [ad9fb758a6](https://linux-hardware.org/?probe=ad9fb758a6) | Nov 09, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| Google        | Akemi                       | Notebook    | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | Notebook    | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| MSI           | B460M PRO                   | Desktop     | [ae3e01fef8](https://linux-hardware.org/?probe=ae3e01fef8) | Oct 31, 2021 |
| ECS           | A55F-M3                     | Desktop     | [27e84aca95](https://linux-hardware.org/?probe=27e84aca95) | Oct 31, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Dell          | Latitude E7450              | Notebook    | [91837758ac](https://linux-hardware.org/?probe=91837758ac) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | Notebook    | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Dell          | Latitude 3190               | Notebook    | [d08efa2ef3](https://linux-hardware.org/?probe=d08efa2ef3) | Oct 25, 2021 |
| Lenovo        | ThinkPad L520 78595VG       | Notebook    | [4aff5a6a0c](https://linux-hardware.org/?probe=4aff5a6a0c) | Oct 24, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [08e803937e](https://linux-hardware.org/?probe=08e803937e) | Oct 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| Dell          | 0P611C A00                  | Desktop     | [c11bd1c981](https://linux-hardware.org/?probe=c11bd1c981) | Oct 11, 2021 |
| HP            | 21D0                        | Desktop     | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| Sony          | SVT13115FBS                 | Notebook    | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| GreatWall     | U320                        | Desktop     | [483d23be23](https://linux-hardware.org/?probe=483d23be23) | Oct 06, 2021 |
| GreatWall     | U320                        | Desktop     | [043d1121f4](https://linux-hardware.org/?probe=043d1121f4) | Oct 06, 2021 |
| Lenovo        | ThinkPad T530 2394CJ9       | Notebook    | [b36a94241d](https://linux-hardware.org/?probe=b36a94241d) | Oct 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [3549222788](https://linux-hardware.org/?probe=3549222788) | Oct 02, 2021 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [536f6d67e3](https://linux-hardware.org/?probe=536f6d67e3) | Oct 02, 2021 |
| Intel         | Unknown                     | Desktop     | [e97eb92439](https://linux-hardware.org/?probe=e97eb92439) | Oct 01, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [8699437e9e](https://linux-hardware.org/?probe=8699437e9e) | Oct 01, 2021 |
| Lenovo        | ThinkPad L490 20Q5S0PR00    | Notebook    | [bbf6b89f02](https://linux-hardware.org/?probe=bbf6b89f02) | Oct 01, 2021 |
| Acer          | Aspire 4820T                | Notebook    | [a91911ca90](https://linux-hardware.org/?probe=a91911ca90) | Oct 01, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [2bf98ef81c](https://linux-hardware.org/?probe=2bf98ef81c) | Sep 24, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [8c1a085f29](https://linux-hardware.org/?probe=8c1a085f29) | Sep 20, 2021 |
| Lenovo        | ThinkPad P51 20HJS0TP00     | Notebook    | [2774c819ea](https://linux-hardware.org/?probe=2774c819ea) | Sep 18, 2021 |
| Lenovo        | B40-45 20394                | Notebook    | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [e76ffa7805](https://linux-hardware.org/?probe=e76ffa7805) | Sep 06, 2021 |
| GTZS          | Unknown                     | Notebook    | [3df799f341](https://linux-hardware.org/?probe=3df799f341) | Sep 05, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Dell          | 0P611C A00                  | Desktop     | [eadaa5e6cb](https://linux-hardware.org/?probe=eadaa5e6cb) | Aug 20, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| Pixus         | Rise                        | Notebook    | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | Notebook    | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [3c5ac88729](https://linux-hardware.org/?probe=3c5ac88729) | Aug 08, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [6949bed845](https://linux-hardware.org/?probe=6949bed845) | Aug 05, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [e94701caeb](https://linux-hardware.org/?probe=e94701caeb) | Aug 03, 2021 |
| Lenovo        | ThinkPad T420 4236MBU       | Notebook    | [7e0b868c64](https://linux-hardware.org/?probe=7e0b868c64) | Jul 29, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [bc56fe50dd](https://linux-hardware.org/?probe=bc56fe50dd) | Jul 24, 2021 |
| Acer          | Aspire E5-574G              | Notebook    | [b09280946d](https://linux-hardware.org/?probe=b09280946d) | Jul 21, 2021 |
| ASRock        | H170M Pro4                  | Desktop     | [f291edbc4a](https://linux-hardware.org/?probe=f291edbc4a) | Jul 18, 2021 |
| Dell          | Vostro 5515                 | Notebook    | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Dell          | Latitude 3340               | Notebook    | [c47b83476b](https://linux-hardware.org/?probe=c47b83476b) | Jul 12, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [192043ebbd](https://linux-hardware.org/?probe=192043ebbd) | Jul 12, 2021 |
| Acer          | Aspire one                  | Notebook    | [2c266e91ae](https://linux-hardware.org/?probe=2c266e91ae) | Jul 09, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [b85b636b73](https://linux-hardware.org/?probe=b85b636b73) | Jun 26, 2021 |
| Medion        | P6669 MD60147               | Notebook    | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Medion        | E6234                       | Notebook    | [313ec752ab](https://linux-hardware.org/?probe=313ec752ab) | May 24, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [4ed89e1092](https://linux-hardware.org/?probe=4ed89e1092) | May 22, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [57a69c7c0d](https://linux-hardware.org/?probe=57a69c7c0d) | May 20, 2021 |
| HP            | Mini 110-3500               | Notebook    | [f94c828225](https://linux-hardware.org/?probe=f94c828225) | May 19, 2021 |
| ASUSTek       | N56VZ                       | Notebook    | [c69cd5aceb](https://linux-hardware.org/?probe=c69cd5aceb) | May 18, 2021 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [bae9a4e960](https://linux-hardware.org/?probe=bae9a4e960) | May 16, 2021 |
| Irbis         | TW94                        | Notebook    | [dc56e23810](https://linux-hardware.org/?probe=dc56e23810) | May 15, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| Dell          | Latitude E6320              | Notebook    | [fa8bcef5a9](https://linux-hardware.org/?probe=fa8bcef5a9) | May 09, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [506efba999](https://linux-hardware.org/?probe=506efba999) | May 02, 2021 |
| Acer          | Extensa 5620                | Notebook    | [a06636ba79](https://linux-hardware.org/?probe=a06636ba79) | Apr 24, 2021 |
| Dell          | 0UW744??????                | Notebook    | [32c3521a2e](https://linux-hardware.org/?probe=32c3521a2e) | Apr 22, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | Notebook    | [73f2bd0075](https://linux-hardware.org/?probe=73f2bd0075) | Apr 16, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | Notebook    | [75e60ebdf4](https://linux-hardware.org/?probe=75e60ebdf4) | Apr 16, 2021 |
| Intel         | ChiefRiver                  | Notebook    | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| eMachines     | E727                        | Notebook    | [048da4f23b](https://linux-hardware.org/?probe=048da4f23b) | Apr 12, 2021 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [7159579bb8](https://linux-hardware.org/?probe=7159579bb8) | Apr 12, 2021 |
| ASRock        | B560M Pro4                  | Desktop     | [d4484f50cd](https://linux-hardware.org/?probe=d4484f50cd) | Apr 08, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [6d6b869b27](https://linux-hardware.org/?probe=6d6b869b27) | Apr 08, 2021 |
| HP            | Falco                       | Notebook    | [9bb0bf9ac8](https://linux-hardware.org/?probe=9bb0bf9ac8) | Apr 07, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [4959cfd244](https://linux-hardware.org/?probe=4959cfd244) | Apr 07, 2021 |
| ASUSTek       | 1025C                       | Notebook    | [33d6531353](https://linux-hardware.org/?probe=33d6531353) | Apr 06, 2021 |
| ASUSTek       | P5K-E                       | Desktop     | [f0c435ead1](https://linux-hardware.org/?probe=f0c435ead1) | Apr 01, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [8d8771e1ef](https://linux-hardware.org/?probe=8d8771e1ef) | Mar 30, 2021 |
| Dell          | 0W7H8C A02                  | Server      | [1a32b081a7](https://linux-hardware.org/?probe=1a32b081a7) | Mar 30, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [04145c0b36](https://linux-hardware.org/?probe=04145c0b36) | Mar 29, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d77d6984e4](https://linux-hardware.org/?probe=d77d6984e4) | Mar 19, 2021 |
| MSI           | MS-7210 100                 | Desktop     | [e8723eb58b](https://linux-hardware.org/?probe=e8723eb58b) | Mar 17, 2021 |
| HP            | ZBook 17 G6                 | Notebook    | [046176e590](https://linux-hardware.org/?probe=046176e590) | Mar 16, 2021 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [dcc5bdef7d](https://linux-hardware.org/?probe=dcc5bdef7d) | Mar 12, 2021 |
| Dell          | Latitude E5470              | Notebook    | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| HP            | Notebook                    | Notebook    | [113644885d](https://linux-hardware.org/?probe=113644885d) | Mar 04, 2021 |
| Acer          | AOD255                      | Notebook    | [f8501e519f](https://linux-hardware.org/?probe=f8501e519f) | Mar 03, 2021 |
| Google        | Gnawty                      | Notebook    | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Latitude D430               | Notebook    | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | Notebook    | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [ce881d4659](https://linux-hardware.org/?probe=ce881d4659) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | Notebook    | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Lenovo        | ThinkPad E425 1198CTO       | Notebook    | [67304f1ffa](https://linux-hardware.org/?probe=67304f1ffa) | Feb 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [6f34bc4f67](https://linux-hardware.org/?probe=6f34bc4f67) | Feb 19, 2021 |
| Medion        | E1235T MD99743              | Tablet      | [314aa4d200](https://linux-hardware.org/?probe=314aa4d200) | Feb 18, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [7552dacfb9](https://linux-hardware.org/?probe=7552dacfb9) | Feb 17, 2021 |
| HP            | Mini 110-3500               | Notebook    | [bb5cf4031b](https://linux-hardware.org/?probe=bb5cf4031b) | Feb 13, 2021 |
| HP            | Notebook                    | Notebook    | [69f70d7a09](https://linux-hardware.org/?probe=69f70d7a09) | Feb 10, 2021 |
| HP            | 15                          | Notebook    | [437cb08f68](https://linux-hardware.org/?probe=437cb08f68) | Feb 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4789c5df48](https://linux-hardware.org/?probe=4789c5df48) | Feb 06, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [a6324a9e06](https://linux-hardware.org/?probe=a6324a9e06) | Feb 05, 2021 |
| Clevo         | P170EM                      | Notebook    | [eff7a04dad](https://linux-hardware.org/?probe=eff7a04dad) | Feb 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | Notebook    | [b6ebe98655](https://linux-hardware.org/?probe=b6ebe98655) | Feb 01, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [9021b90504](https://linux-hardware.org/?probe=9021b90504) | Jan 22, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a147ddbe9d](https://linux-hardware.org/?probe=a147ddbe9d) | Jan 20, 2021 |
| HP            | Mini 110-3500               | Notebook    | [3c2a01636e](https://linux-hardware.org/?probe=3c2a01636e) | Jan 19, 2021 |
| HP            | Pavilion g6                 | Notebook    | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [3dfb714393](https://linux-hardware.org/?probe=3dfb714393) | Jan 15, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| Dell          | Latitude D430               | Notebook    | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [62ab746796](https://linux-hardware.org/?probe=62ab746796) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [00e4deffa2](https://linux-hardware.org/?probe=00e4deffa2) | Jan 14, 2021 |
| Dell          | Latitude E5520              | Notebook    | [1d46b26326](https://linux-hardware.org/?probe=1d46b26326) | Jan 03, 2021 |
| HP            | Presario CQ57               | Notebook    | [351ae067b6](https://linux-hardware.org/?probe=351ae067b6) | Dec 31, 2020 |
| HP            | Presario CQ57               | Notebook    | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [7f351d7c49](https://linux-hardware.org/?probe=7f351d7c49) | Dec 30, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [98c8e4f3a6](https://linux-hardware.org/?probe=98c8e4f3a6) | Dec 20, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5de3914984](https://linux-hardware.org/?probe=5de3914984) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ebb2dc7bff](https://linux-hardware.org/?probe=ebb2dc7bff) | Dec 15, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [5783b64146](https://linux-hardware.org/?probe=5783b64146) | Dec 11, 2020 |
| Lenovo        | ThinkPad X220 4291WMQ       | Notebook    | [165b895e27](https://linux-hardware.org/?probe=165b895e27) | Dec 01, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [d3e3aa3011](https://linux-hardware.org/?probe=d3e3aa3011) | Nov 28, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [b51d9808ea](https://linux-hardware.org/?probe=b51d9808ea) | Nov 28, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6a65eeffd1](https://linux-hardware.org/?probe=6a65eeffd1) | Nov 27, 2020 |
| HP            | 1905                        | Desktop     | [03a91e7ecc](https://linux-hardware.org/?probe=03a91e7ecc) | Nov 27, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b7fec4788f](https://linux-hardware.org/?probe=b7fec4788f) | Nov 25, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4f8648d28](https://linux-hardware.org/?probe=d4f8648d28) | Nov 24, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [282590eccb](https://linux-hardware.org/?probe=282590eccb) | Nov 24, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| Acer          | Aspire E5-571G              | Notebook    | [7f5f7e9fff](https://linux-hardware.org/?probe=7f5f7e9fff) | Nov 17, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [309a3f69e8](https://linux-hardware.org/?probe=309a3f69e8) | Nov 16, 2020 |
| ASRock        | H110M-ITX                   | Desktop     | [e3ca7996d2](https://linux-hardware.org/?probe=e3ca7996d2) | Nov 13, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | Notebook    | [554dfc3cfe](https://linux-hardware.org/?probe=554dfc3cfe) | Nov 12, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | Notebook    | [2dc30b7928](https://linux-hardware.org/?probe=2dc30b7928) | Nov 12, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a7bb20fa67](https://linux-hardware.org/?probe=a7bb20fa67) | Nov 08, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fe6cbf555a](https://linux-hardware.org/?probe=fe6cbf555a) | Nov 08, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [96e87a665b](https://linux-hardware.org/?probe=96e87a665b) | Nov 01, 2020 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [c4f4df2ec5](https://linux-hardware.org/?probe=c4f4df2ec5) | Oct 31, 2020 |
| Dell          | 0D28YY A00                  | Desktop     | [584335af3e](https://linux-hardware.org/?probe=584335af3e) | Oct 29, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [470c0ca72b](https://linux-hardware.org/?probe=470c0ca72b) | Oct 23, 2020 |
| Dell          | Latitude 5175               | Tablet      | [5144248c79](https://linux-hardware.org/?probe=5144248c79) | Oct 19, 2020 |
| HP            | Compaq 8510p (KM229AV)      | Notebook    | [30634ffde6](https://linux-hardware.org/?probe=30634ffde6) | Oct 12, 2020 |
| Acer          | Aspire SW5-015              | Notebook    | [b125bdb89e](https://linux-hardware.org/?probe=b125bdb89e) | Oct 07, 2020 |
| HP            | Pavilion 15                 | Notebook    | [8e6632f1a3](https://linux-hardware.org/?probe=8e6632f1a3) | Oct 06, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [7155397289](https://linux-hardware.org/?probe=7155397289) | Oct 03, 2020 |
| Hometech      | Wi11T                       | Tablet      | [78d63aeadc](https://linux-hardware.org/?probe=78d63aeadc) | Sep 30, 2020 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [995b1a3a3d](https://linux-hardware.org/?probe=995b1a3a3d) | Sep 29, 2020 |
| Dell          | 0M9KCM A02                  | Desktop     | [3e66c830f8](https://linux-hardware.org/?probe=3e66c830f8) | Sep 22, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [a5f308c899](https://linux-hardware.org/?probe=a5f308c899) | Sep 21, 2020 |
| Lenovo        | ThinkPad T60 20085TG        | Notebook    | [31cd0f06c2](https://linux-hardware.org/?probe=31cd0f06c2) | Sep 16, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a2151aadf5](https://linux-hardware.org/?probe=a2151aadf5) | Sep 14, 2020 |
| HP            | 838B 0100                   | All in one  | [c3133d1a1c](https://linux-hardware.org/?probe=c3133d1a1c) | Sep 09, 2020 |
| HP            | 8265                        | Desktop     | [38f924e8f9](https://linux-hardware.org/?probe=38f924e8f9) | Sep 07, 2020 |
| Teclast       | F5                          | Convertible | [1003072bc5](https://linux-hardware.org/?probe=1003072bc5) | Sep 06, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [356bacc97a](https://linux-hardware.org/?probe=356bacc97a) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Acer          | Aspire A114-32              | Notebook    | [7f178a7089](https://linux-hardware.org/?probe=7f178a7089) | Aug 20, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [9b4d2c057e](https://linux-hardware.org/?probe=9b4d2c057e) | Aug 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [57e274292b](https://linux-hardware.org/?probe=57e274292b) | Aug 16, 2020 |
| Acer          | Aspire 7520                 | Notebook    | [d878dbb71e](https://linux-hardware.org/?probe=d878dbb71e) | Aug 13, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [f138fd7e0c](https://linux-hardware.org/?probe=f138fd7e0c) | Aug 09, 2020 |
| HP            | ProLiant DL380 G6           | Server      | [e01126d9bd](https://linux-hardware.org/?probe=e01126d9bd) | Aug 06, 2020 |
| HP            | ProLiant DL380 G6           | Server      | [7a48a3ced3](https://linux-hardware.org/?probe=7a48a3ced3) | Aug 06, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [2f71e9b242](https://linux-hardware.org/?probe=2f71e9b242) | Aug 03, 2020 |
| HP            | 3031h                       | Desktop     | [205dd10b09](https://linux-hardware.org/?probe=205dd10b09) | Jul 29, 2020 |
| HP            | 3031h                       | Desktop     | [22ebc88fac](https://linux-hardware.org/?probe=22ebc88fac) | Jul 29, 2020 |
| HP            | Pavilion dv7                | Notebook    | [3494105666](https://linux-hardware.org/?probe=3494105666) | Jul 28, 2020 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | Notebook    | [c0d166e020](https://linux-hardware.org/?probe=c0d166e020) | Jul 27, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [9a488079c3](https://linux-hardware.org/?probe=9a488079c3) | Jul 23, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [2233b1466b](https://linux-hardware.org/?probe=2233b1466b) | Jul 06, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [c70f8ee92e](https://linux-hardware.org/?probe=c70f8ee92e) | Jul 06, 2020 |
| Sony          | VPCF23P1E                   | Notebook    | [2e0915f8a9](https://linux-hardware.org/?probe=2e0915f8a9) | Jun 18, 2020 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [54a69351ae](https://linux-hardware.org/?probe=54a69351ae) | Jun 17, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b93dafce99](https://linux-hardware.org/?probe=b93dafce99) | Jun 09, 2020 |
| Lenovo        | ThinkPad X250 20CLS4YA00    | Notebook    | [72150af905](https://linux-hardware.org/?probe=72150af905) | Jun 06, 2020 |
| ASUSTek       | X540UP                      | Notebook    | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Sony          | VGN-NR310FH                 | Notebook    | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| MSI           | 970A-G43                    | Desktop     | [ada20a047e](https://linux-hardware.org/?probe=ada20a047e) | May 27, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [665b2837c7](https://linux-hardware.org/?probe=665b2837c7) | May 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c85746245d](https://linux-hardware.org/?probe=c85746245d) | May 26, 2020 |
| Lenovo        | B590 20206                  | Notebook    | [8f4a7e2b6e](https://linux-hardware.org/?probe=8f4a7e2b6e) | May 26, 2020 |
| Gigabyte      | P55-USB3                    | Desktop     | [901dfafdbf](https://linux-hardware.org/?probe=901dfafdbf) | May 21, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | Notebook    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| Lenovo        | MIIX 3-1030 80HV            | Tablet      | [34335c5fb5](https://linux-hardware.org/?probe=34335c5fb5) | Apr 24, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a7d4e8b1e4](https://linux-hardware.org/?probe=a7d4e8b1e4) | Apr 10, 2020 |
| Samsung       | R780/R778                   | Notebook    | [eb0bb63c6d](https://linux-hardware.org/?probe=eb0bb63c6d) | Apr 09, 2020 |
| Intel         | DCP847SKE G80890-105        | Desktop     | [0357ef50d4](https://linux-hardware.org/?probe=0357ef50d4) | Apr 05, 2020 |
| Dell          | Latitude 3390 2-in-1        | Convertible | [60ae29c5ac](https://linux-hardware.org/?probe=60ae29c5ac) | Apr 04, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [893f6857b2](https://linux-hardware.org/?probe=893f6857b2) | Apr 04, 2020 |
| ASUSTek       | Z97-E                       | Desktop     | [42c2810369](https://linux-hardware.org/?probe=42c2810369) | Apr 03, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ec1375a9f8](https://linux-hardware.org/?probe=ec1375a9f8) | Apr 02, 2020 |
| MSI           | 760GM-P23                   | Desktop     | [67de432cb4](https://linux-hardware.org/?probe=67de432cb4) | Apr 01, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [67d9f2023b](https://linux-hardware.org/?probe=67d9f2023b) | Apr 01, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [104b035076](https://linux-hardware.org/?probe=104b035076) | Apr 01, 2020 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [27d1900fba](https://linux-hardware.org/?probe=27d1900fba) | Mar 28, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [617031b37d](https://linux-hardware.org/?probe=617031b37d) | Mar 28, 2020 |
| Clevo         | P150HMx                     | Notebook    | [196b689717](https://linux-hardware.org/?probe=196b689717) | Mar 27, 2020 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [73690787f9](https://linux-hardware.org/?probe=73690787f9) | Mar 26, 2020 |
| Dell          | Latitude E7440              | Notebook    | [c6fe81343e](https://linux-hardware.org/?probe=c6fe81343e) | Mar 26, 2020 |
| Dell          | 0F373D A00                  | Desktop     | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| ASUSTek       | X455LAB                     | Notebook    | [4a5174a726](https://linux-hardware.org/?probe=4a5174a726) | Mar 24, 2020 |
| Notebook      | W65_W67RZ1                  | Notebook    | [aaffd10ebf](https://linux-hardware.org/?probe=aaffd10ebf) | Mar 24, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [242a7e4fdc](https://linux-hardware.org/?probe=242a7e4fdc) | Mar 24, 2020 |
| Clevo         | P150HMx                     | Notebook    | [8f9823569b](https://linux-hardware.org/?probe=8f9823569b) | Mar 24, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1243c4a0d9](https://linux-hardware.org/?probe=1243c4a0d9) | Mar 24, 2020 |
| Dell          | Inspiron N5010              | Notebook    | [8654fde26b](https://linux-hardware.org/?probe=8654fde26b) | Mar 24, 2020 |
| HP            | 1790                        | Desktop     | [68a167efd3](https://linux-hardware.org/?probe=68a167efd3) | Mar 24, 2020 |
| Medion        | Akoya E1318T                | Notebook    | [d6be35c8af](https://linux-hardware.org/?probe=d6be35c8af) | Mar 20, 2020 |
| Dell          | Latitude 3190               | Notebook    | [1bab98d664](https://linux-hardware.org/?probe=1bab98d664) | Mar 20, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [e5925f1349](https://linux-hardware.org/?probe=e5925f1349) | Mar 07, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [296f21e934](https://linux-hardware.org/?probe=296f21e934) | Mar 03, 2020 |
| Acer          | Aspire 8943G                | Notebook    | [f8e194e907](https://linux-hardware.org/?probe=f8e194e907) | Mar 01, 2020 |
| ASUSTek       | M4A77T                      | Desktop     | [75d0b42f08](https://linux-hardware.org/?probe=75d0b42f08) | Mar 01, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [370f5d5063](https://linux-hardware.org/?probe=370f5d5063) | Feb 26, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T11... | Notebook    | [9c888bfdde](https://linux-hardware.org/?probe=9c888bfdde) | Feb 11, 2020 |
| Lenovo        | ThinkPad X201 3680MY9       | Notebook    | [26a7c0e493](https://linux-hardware.org/?probe=26a7c0e493) | Feb 09, 2020 |
| Google        | Gnawty                      | Notebook    | [4a2e211ce1](https://linux-hardware.org/?probe=4a2e211ce1) | Feb 08, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | Notebook    | [8865e9546b](https://linux-hardware.org/?probe=8865e9546b) | Feb 03, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | Notebook    | [f4779c95ce](https://linux-hardware.org/?probe=f4779c95ce) | Feb 03, 2020 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [ed464b4172](https://linux-hardware.org/?probe=ed464b4172) | Jan 23, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [f703814098](https://linux-hardware.org/?probe=f703814098) | Jan 23, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [48912b8dc6](https://linux-hardware.org/?probe=48912b8dc6) | Jan 19, 2020 |
| ASRock        | K8A780LM                    | Desktop     | [e0d3030787](https://linux-hardware.org/?probe=e0d3030787) | Jan 18, 2020 |
| ASUSTek       | TUF Gaming FX505GT_TUF50... | Notebook    | [0abd5b1d73](https://linux-hardware.org/?probe=0abd5b1d73) | Jan 18, 2020 |
| ASRock        | K8A780LM                    | Desktop     | [83dca94e72](https://linux-hardware.org/?probe=83dca94e72) | Jan 17, 2020 |
| ASRock        | K8A780LM                    | Desktop     | [a5e0479887](https://linux-hardware.org/?probe=a5e0479887) | Jan 16, 2020 |
| Toshiba       | Satellite P875              | Notebook    | [b267e93d40](https://linux-hardware.org/?probe=b267e93d40) | Jan 15, 2020 |
| Toshiba       | Satellite P875              | Notebook    | [7e579fcba2](https://linux-hardware.org/?probe=7e579fcba2) | Jan 15, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [811669dbdd](https://linux-hardware.org/?probe=811669dbdd) | Jan 13, 2020 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [03401edcb4](https://linux-hardware.org/?probe=03401edcb4) | Jan 13, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [8a0171b4b0](https://linux-hardware.org/?probe=8a0171b4b0) | Jan 13, 2020 |
| Gateway       | SX2185                      | Desktop     | [74f9db3262](https://linux-hardware.org/?probe=74f9db3262) | Jan 13, 2020 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [0a8865c437](https://linux-hardware.org/?probe=0a8865c437) | Jan 13, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [f10553e785](https://linux-hardware.org/?probe=f10553e785) | Jan 13, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [aa52528043](https://linux-hardware.org/?probe=aa52528043) | Jan 13, 2020 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [ba3b839fa4](https://linux-hardware.org/?probe=ba3b839fa4) | Jan 12, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [7f8e86e96b](https://linux-hardware.org/?probe=7f8e86e96b) | Jan 12, 2020 |
| Dell          | 088DT1 A01                  | Desktop     | [3c957a3758](https://linux-hardware.org/?probe=3c957a3758) | Dec 23, 2019 |
| HP            | Pavilion g6                 | Notebook    | [9c722b6763](https://linux-hardware.org/?probe=9c722b6763) | Dec 21, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [2a979257ab](https://linux-hardware.org/?probe=2a979257ab) | Dec 21, 2019 |
| MSI           | MS-7199                     | Desktop     | [8fe7e9e6a6](https://linux-hardware.org/?probe=8fe7e9e6a6) | Dec 21, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [b7165ade10](https://linux-hardware.org/?probe=b7165ade10) | Dec 21, 2019 |
| Toshiba       | Satellite C50-A-12K         | Notebook    | [a413f419ef](https://linux-hardware.org/?probe=a413f419ef) | Dec 17, 2019 |
| Dell          | G3 3579                     | Notebook    | [c4fe97cca2](https://linux-hardware.org/?probe=c4fe97cca2) | Dec 04, 2019 |
| Dell          | G3 3579                     | Notebook    | [ada421696a](https://linux-hardware.org/?probe=ada421696a) | Dec 04, 2019 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [c96e6bc37c](https://linux-hardware.org/?probe=c96e6bc37c) | Dec 02, 2019 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [02ae0c5f5b](https://linux-hardware.org/?probe=02ae0c5f5b) | Dec 02, 2019 |
| MSI           | MS-N033                     | Notebook    | [a5ee4c1dc1](https://linux-hardware.org/?probe=a5ee4c1dc1) | Nov 17, 2019 |
| ASUSTek       | 1005HA                      | Notebook    | [bd953e0701](https://linux-hardware.org/?probe=bd953e0701) | Nov 17, 2019 |
| MSI           | B75MA-E33                   | Desktop     | [a08cc9782c](https://linux-hardware.org/?probe=a08cc9782c) | Nov 17, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | Notebook    | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Lenovo        | ThinkPad X301 2776LBU       | Notebook    | [993b5f104a](https://linux-hardware.org/?probe=993b5f104a) | Nov 17, 2019 |
| Gigabyte      | P43-ES3G                    | Desktop     | [96fa353482](https://linux-hardware.org/?probe=96fa353482) | Nov 07, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [585b07ffaf](https://linux-hardware.org/?probe=585b07ffaf) | Nov 04, 2019 |
| ASUSTek       | X101CH                      | Notebook    | [b17de4dbad](https://linux-hardware.org/?probe=b17de4dbad) | Nov 04, 2019 |
| HP            | Pavilion g6                 | Notebook    | [2cb09606ed](https://linux-hardware.org/?probe=2cb09606ed) | Nov 01, 2019 |
| HP            | ProBook 4440s               | Notebook    | [fc67acaa63](https://linux-hardware.org/?probe=fc67acaa63) | Oct 29, 2019 |
| ASRock        | H81M-ITX                    | Desktop     | [431ea0cbed](https://linux-hardware.org/?probe=431ea0cbed) | Oct 25, 2019 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [6a706da421](https://linux-hardware.org/?probe=6a706da421) | Oct 23, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [df3af7b333](https://linux-hardware.org/?probe=df3af7b333) | Oct 23, 2019 |
| HP            | EliteBook 8540w             | Notebook    | [ea8ef5afc7](https://linux-hardware.org/?probe=ea8ef5afc7) | Oct 23, 2019 |
| Dell          | 0F8096                      | Desktop     | [d1f6910c12](https://linux-hardware.org/?probe=d1f6910c12) | Oct 20, 2019 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f4fcd6e28c](https://linux-hardware.org/?probe=f4fcd6e28c) | Oct 20, 2019 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [cb80682975](https://linux-hardware.org/?probe=cb80682975) | Oct 20, 2019 |
| ZOTAC         | ZBOX-ID18                   | Mini pc     | [4c4d77145b](https://linux-hardware.org/?probe=4c4d77145b) | Oct 20, 2019 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [71373d2071](https://linux-hardware.org/?probe=71373d2071) | Oct 20, 2019 |
| ASRock        | H81M-ITX                    | Desktop     | [c5f47f2f27](https://linux-hardware.org/?probe=c5f47f2f27) | Oct 20, 2019 |
| HP            | Pavilion g6                 | Notebook    | [6bde777445](https://linux-hardware.org/?probe=6bde777445) | Oct 20, 2019 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [13dbc6f66d](https://linux-hardware.org/?probe=13dbc6f66d) | Oct 06, 2019 |
| Lenovo        | ThinkPad X220 4291F52       | Notebook    | [e024139431](https://linux-hardware.org/?probe=e024139431) | Aug 29, 2019 |
| Lenovo        | ThinkPad X201s 5413A19      | Notebook    | [673c3629dc](https://linux-hardware.org/?probe=673c3629dc) | Aug 22, 2019 |
| Panasonic     | CF-C1BT02EGE                | Notebook    | [acbec08287](https://linux-hardware.org/?probe=acbec08287) | Aug 15, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [6a9aa2dd84](https://linux-hardware.org/?probe=6a9aa2dd84) | Jul 22, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [bf82fba8fd](https://linux-hardware.org/?probe=bf82fba8fd) | Apr 29, 2019 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [e42fd626b2](https://linux-hardware.org/?probe=e42fd626b2) | Apr 23, 2019 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [8469904453](https://linux-hardware.org/?probe=8469904453) | Apr 17, 2019 |
| ASUSTek       | K55VM                       | Notebook    | [e967dd6404](https://linux-hardware.org/?probe=e967dd6404) | Mar 27, 2019 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [c68bd6bce7](https://linux-hardware.org/?probe=c68bd6bce7) | Feb 23, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [67b484c4a0](https://linux-hardware.org/?probe=67b484c4a0) | Jan 19, 2019 |
| Acer          | Aspire C22-760              | All in one  | [ff0b5db4bf](https://linux-hardware.org/?probe=ff0b5db4bf) | Dec 18, 2018 |
| Acer          | Aspire C22-760              | All in one  | [7909d2b661](https://linux-hardware.org/?probe=7909d2b661) | Nov 09, 2018 |
| Toshiba       | Satellite C70-B             | Notebook    | [9b54677f2e](https://linux-hardware.org/?probe=9b54677f2e) | Oct 27, 2018 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [ec89febb0c](https://linux-hardware.org/?probe=ec89febb0c) | Oct 27, 2018 |
| Dell          | Inspiron ME051              | Notebook    | [f789720dc4](https://linux-hardware.org/?probe=f789720dc4) | Nov 26, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/MX/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| MX 21          | 285       | 52.97%  |
| MX 19          | 144       | 26.77%  |
| MX 20          | 74        | 13.75%  |
| MX 18          | 27        | 5.02%   |
| MX 17          | 4         | 0.74%   |
| MX 23          | 1         | 0.19%   |
| MX 22          | 1         | 0.19%   |
| MX 16-migrated | 1         | 0.19%   |
| MX 16          | 1         | 0.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| MX   | 527       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 4.19.0-6-amd64            | 57        | 9.86%   |
| 5.10.0-21-amd64           | 37        | 6.4%    |
| 5.10.0-5mx-amd64          | 23        | 3.98%   |
| 5.10.0-13-amd64           | 20        | 3.46%   |
| 5.10.0-18-amd64           | 19        | 3.29%   |
| 6.0.0-6mx-amd64           | 18        | 3.11%   |
| 5.10.0-9-amd64            | 18        | 3.11%   |
| 5.10.0-19-amd64           | 18        | 3.11%   |
| 5.10.0-20-amd64           | 17        | 2.94%   |
| 5.14.0-4mx-amd64          | 16        | 2.77%   |
| 5.8.0-3-amd64             | 15        | 2.6%    |
| 5.6.0-2-amd64             | 15        | 2.6%    |
| 5.16.0-5mx-amd64          | 13        | 2.25%   |
| 5.10.0-16-amd64           | 13        | 2.25%   |
| 4.19.0-14-amd64           | 10        | 1.73%   |
| 4.19.0-13-amd64           | 10        | 1.73%   |
| 4.19.0-17-amd64           | 9         | 1.56%   |
| 5.18.0-4mx-amd64          | 8         | 1.38%   |
| 5.10.0-11-amd64           | 8         | 1.38%   |
| 4.19.0-16-amd64           | 8         | 1.38%   |
| 4.19.0-5-amd64            | 7         | 1.21%   |
| 5.10.0-15-amd64           | 6         | 1.04%   |
| 5.10.0-14-amd64           | 6         | 1.04%   |
| 4.19.0-1-amd64            | 6         | 1.04%   |
| 6.0.0-4mx-amd64           | 5         | 0.87%   |
| 5.4.0-3-amd64             | 5         | 0.87%   |
| 5.10.0-8mx-amd64          | 5         | 0.87%   |
| 4.19.0-18-amd64           | 5         | 0.87%   |
| 4.19.0-12-amd64           | 5         | 0.87%   |
| 6.0.0-10.1-liquorix-amd64 | 4         | 0.69%   |
| 5.8.16-antix.1-amd64-smp  | 4         | 0.69%   |
| 5.19.0-2mx-amd64          | 4         | 0.69%   |
| 5.10.0-17-amd64           | 4         | 0.69%   |
| 5.10.0-10-amd64           | 4         | 0.69%   |
| 4.19.0-11-amd64           | 4         | 0.69%   |
| 4.15.0-1-amd64            | 4         | 0.69%   |
| 6.0.0-3mx-amd64           | 3         | 0.52%   |
| 5.2.21-antix.2-amd64-smp  | 3         | 0.52%   |
| 5.16.0-6mx-amd64          | 3         | 0.52%   |
| 4.19.0-9-amd64            | 3         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 211       | 37.88%  |
| 4.19.0   | 133       | 23.88%  |
| 6.0.0    | 33        | 5.92%   |
| 5.16.0   | 21        | 3.77%   |
| 5.14.0   | 19        | 3.41%   |
| 5.6.0    | 17        | 3.05%   |
| 5.8.0    | 15        | 2.69%   |
| 5.18.0   | 10        | 1.8%    |
| 5.4.0    | 9         | 1.62%   |
| 5.19.0   | 9         | 1.62%   |
| 6.1.0    | 7         | 1.26%   |
| 5.5.0    | 6         | 1.08%   |
| 5.17.0   | 6         | 1.08%   |
| 4.15.0   | 6         | 1.08%   |
| 5.15.0   | 5         | 0.9%    |
| 5.8.16   | 4         | 0.72%   |
| 5.3.0    | 4         | 0.72%   |
| 5.2.21   | 4         | 0.72%   |
| 5.6.10   | 3         | 0.54%   |
| 6.1.15   | 2         | 0.36%   |
| 5.4.7    | 2         | 0.36%   |
| 5.11.0   | 2         | 0.36%   |
| 4.9.193  | 2         | 0.36%   |
| 4.18.0   | 2         | 0.36%   |
| 6.2.7    | 1         | 0.18%   |
| 6.1.12   | 1         | 0.18%   |
| 6.0.5    | 1         | 0.18%   |
| 5.9.1    | 1         | 0.18%   |
| 5.7.0    | 1         | 0.18%   |
| 5.4.10   | 1         | 0.18%   |
| 5.3.10   | 1         | 0.18%   |
| 5.2.8    | 1         | 0.18%   |
| 5.2.15   | 1         | 0.18%   |
| 5.2.0    | 1         | 0.18%   |
| 5.13.0   | 1         | 0.18%   |
| 5.10.82  | 1         | 0.18%   |
| 5.10.52  | 1         | 0.18%   |
| 5.10.142 | 1         | 0.18%   |
| 5.10.113 | 1         | 0.18%   |
| 5.10.111 | 1         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 217       | 38.96%  |
| 4.19    | 134       | 24.06%  |
| 6.0     | 34        | 6.1%    |
| 5.16    | 21        | 3.77%   |
| 5.6     | 20        | 3.59%   |
| 5.8     | 19        | 3.41%   |
| 5.14    | 19        | 3.41%   |
| 5.4     | 12        | 2.15%   |
| 6.1     | 10        | 1.8%    |
| 5.18    | 10        | 1.8%    |
| 5.19    | 9         | 1.62%   |
| 5.2     | 7         | 1.26%   |
| 5.5     | 6         | 1.08%   |
| 5.17    | 6         | 1.08%   |
| 4.15    | 6         | 1.08%   |
| 5.3     | 5         | 0.9%    |
| 5.15    | 5         | 0.9%    |
| 4.9     | 5         | 0.9%    |
| 5.11    | 2         | 0.36%   |
| 4.18    | 2         | 0.36%   |
| 6.2     | 1         | 0.18%   |
| 5.9     | 1         | 0.18%   |
| 5.7     | 1         | 0.18%   |
| 5.13    | 1         | 0.18%   |
| 5.1     | 1         | 0.18%   |
| 5.0     | 1         | 0.18%   |
| 3.16    | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 501       | 94.89%  |
| i686   | 27        | 5.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 395       | 73.56%  |
| KDE5             | 91        | 16.95%  |
| Unknown          | 8         | 1.49%   |
| Budgie           | 7         | 1.3%    |
| i3               | 5         | 0.93%   |
| GNOME            | 5         | 0.93%   |
| MATE             | 4         | 0.74%   |
| LXQt             | 4         | 0.74%   |
| lightdm-xsession | 4         | 0.74%   |
| X-Cinnamon       | 3         | 0.56%   |
| fluxbox          | 2         | 0.37%   |
| Cinnamon         | 2         | 0.37%   |
| Trinity          | 1         | 0.19%   |
| spectrwm         | 1         | 0.19%   |
| LXDE             | 1         | 0.19%   |
| KDE4             | 1         | 0.19%   |
| KDE              | 1         | 0.19%   |
| GNOME Flashback  | 1         | 0.19%   |
| GNOME Classic    | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 522       | 99.05%  |
| Tty     | 4         | 0.76%   |
| Wayland | 1         | 0.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 425       | 79.74%  |
| SDDM    | 80        | 15.01%  |
| TDM     | 13        | 2.44%   |
| SLiM    | 12        | 2.25%   |
| Unknown | 2         | 0.38%   |
| GDM     | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 199       | 36.65%  |
| Unknown | 103       | 18.97%  |
| de_DE   | 53        | 9.76%   |
| en_GB   | 30        | 5.52%   |
| it_IT   | 21        | 3.87%   |
| ru_RU   | 15        | 2.76%   |
| es_ES   | 13        | 2.39%   |
| sk_SK   | 12        | 2.21%   |
| pl_PL   | 11        | 2.03%   |
| fr_FR   | 11        | 2.03%   |
| pt_BR   | 10        | 1.84%   |
| en_AU   | 9         | 1.66%   |
| tr_TR   | 5         | 0.92%   |
| de_CH   | 5         | 0.92%   |
| es_AR   | 4         | 0.74%   |
| nl_NL   | 3         | 0.55%   |
| hu_HU   | 3         | 0.55%   |
| es_MX   | 3         | 0.55%   |
| es_CO   | 3         | 0.55%   |
| en_NZ   | 3         | 0.55%   |
| en_IE   | 3         | 0.55%   |
| uk_UA   | 2         | 0.37%   |
| sv_SE   | 2         | 0.37%   |
| fr_BE   | 2         | 0.37%   |
| fi_FI   | 2         | 0.37%   |
| es_VE   | 2         | 0.37%   |
| bg_BG   | 2         | 0.37%   |
| zh_CN   | 1         | 0.18%   |
| nb_NO   | 1         | 0.18%   |
| id_ID   | 1         | 0.18%   |
| hr_HR   | 1         | 0.18%   |
| fr_CH   | 1         | 0.18%   |
| fr_CA   | 1         | 0.18%   |
| eu_ES   | 1         | 0.18%   |
| es_UY   | 1         | 0.18%   |
| es_PE   | 1         | 0.18%   |
| en_CA   | 1         | 0.18%   |
| da_DK   | 1         | 0.18%   |
| cs_CZ   | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 281       | 53.32%  |
| BIOS | 246       | 46.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 459       | 86.6%   |
| Overlay  | 48        | 9.06%   |
| Btrfs    | 15        | 2.83%   |
| Xfs      | 3         | 0.57%   |
| Unknown  | 2         | 0.38%   |
| Reiserfs | 1         | 0.19%   |
| F2fs     | 1         | 0.19%   |
| Ext3     | 1         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 331       | 62.57%  |
| MBR     | 191       | 36.11%  |
| Unknown | 7         | 1.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 396       | 73.61%  |
| Yes       | 142       | 26.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 292       | 55.09%  |
| Yes       | 238       | 44.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 75        | 14.23%  |
| Hewlett-Packard                      | 75        | 14.23%  |
| ASUSTek Computer                     | 74        | 14.04%  |
| Dell                                 | 58        | 11.01%  |
| Acer                                 | 30        | 5.69%   |
| Gigabyte Technology                  | 29        | 5.5%    |
| MSI                                  | 27        | 5.12%   |
| Apple                                | 19        | 3.61%   |
| ASRock                               | 17        | 3.23%   |
| Toshiba                              | 11        | 2.09%   |
| Sony                                 | 11        | 2.09%   |
| Intel                                | 11        | 2.09%   |
| Medion                               | 9         | 1.71%   |
| Samsung Electronics                  | 5         | 0.95%   |
| Unknown                              | 5         | 0.95%   |
| ZOTAC                                | 4         | 0.76%   |
| Fujitsu Siemens                      | 4         | 0.76%   |
| Google                               | 3         | 0.57%   |
| Alienware                            | 3         | 0.57%   |
| TUXEDO                               | 2         | 0.38%   |
| Pegatron                             | 2         | 0.38%   |
| Notebook                             | 2         | 0.38%   |
| Microsoft                            | 2         | 0.38%   |
| Gateway                              | 2         | 0.38%   |
| Fujitsu                              | 2         | 0.38%   |
| ECS                                  | 2         | 0.38%   |
| Clevo                                | 2         | 0.38%   |
| Chuwi                                | 2         | 0.38%   |
| Biostar                              | 2         | 0.38%   |
| AZW                                  | 2         | 0.38%   |
| win element                          | 1         | 0.19%   |
| Vulcan Electronics                   | 1         | 0.19%   |
| UMAX                                 | 1         | 0.19%   |
| Teclast                              | 1         | 0.19%   |
| Sun Microsystems                     | 1         | 0.19%   |
| SLIMBOOK                             | 1         | 0.19%   |
| SIRAGON                              | 1         | 0.19%   |
| Shenzhen Wangang Technology          | 1         | 0.19%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.19%   |
| SANTECH                              | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 9         | 1.71%   |
| Unknown                            | 9         | 1.71%   |
| MSI MS-7C91                        | 2         | 0.38%   |
| MSI MS-7A34                        | 2         | 0.38%   |
| HP Stream Laptop 14-cb0XX          | 2         | 0.38%   |
| HP ProBook 650 G1                  | 2         | 0.38%   |
| HP Laptop 17-ak0xx                 | 2         | 0.38%   |
| Gigabyte GA-MA785GM-US2H           | 2         | 0.38%   |
| Dell Studio 540                    | 2         | 0.38%   |
| Dell OptiPlex 9010                 | 2         | 0.38%   |
| Dell OptiPlex 790                  | 2         | 0.38%   |
| Dell OptiPlex 755                  | 2         | 0.38%   |
| Chuwi GemiBook Pro                 | 2         | 0.38%   |
| AZW SER                            | 2         | 0.38%   |
| ASUS ZenBook UX363EA_UX363EA       | 2         | 0.38%   |
| ASUS X200CA                        | 2         | 0.38%   |
| ASUS ROG Maximus XIII HERO         | 2         | 0.38%   |
| ASUS PRIME B450M-A                 | 2         | 0.38%   |
| ASRock K8A780LM                    | 2         | 0.38%   |
| Apple Macmini8,1                   | 2         | 0.38%   |
| Apple MacBookAir7,2                | 2         | 0.38%   |
| Acer Nitro AN515-55                | 2         | 0.38%   |
| ZOTAC ZBOX-ID18                    | 1         | 0.19%   |
| ZOTAC ZBOX-ECM73070C/53060C        | 1         | 0.19%   |
| ZOTAC ZBOX-BI320                   | 1         | 0.19%   |
| win element MoreFine S500+         | 1         | 0.19%   |
| Vulcan Excursion XB                | 1         | 0.19%   |
| UMAX VisionBook-N12R               | 1         | 0.19%   |
| TUXEDO N7x0WU                      | 1         | 0.19%   |
| TUXEDO InfinityBook Pro Gen7 (MK1) | 1         | 0.19%   |
| Toshiba Satellite P875             | 1         | 0.19%   |
| Toshiba Satellite M70              | 1         | 0.19%   |
| Toshiba Satellite L850-CJK         | 1         | 0.19%   |
| Toshiba Satellite L650             | 1         | 0.19%   |
| Toshiba Satellite C845             | 1         | 0.19%   |
| Toshiba Satellite C70-B            | 1         | 0.19%   |
| Toshiba Satellite C660             | 1         | 0.19%   |
| Toshiba Satellite C50-A-12K        | 1         | 0.19%   |
| Toshiba Satellite A300             | 1         | 0.19%   |
| Toshiba PORTEGE Z30-C              | 1         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 46        | 8.73%   |
| Acer Aspire              | 18        | 3.42%   |
| Dell Latitude            | 15        | 2.85%   |
| Dell OptiPlex            | 13        | 2.47%   |
| Dell Inspiron            | 13        | 2.47%   |
| HP ProBook               | 10        | 1.9%    |
| Toshiba Satellite        | 9         | 1.71%   |
| ASUS All                 | 9         | 1.71%   |
| Unknown                  | 9         | 1.71%   |
| HP Pavilion              | 8         | 1.52%   |
| HP EliteBook             | 8         | 1.52%   |
| ASUS TUF                 | 8         | 1.52%   |
| Lenovo IdeaPad           | 7         | 1.33%   |
| HP Compaq                | 7         | 1.33%   |
| ASUS ROG                 | 7         | 1.33%   |
| HP Laptop                | 6         | 1.14%   |
| Dell Vostro              | 5         | 0.95%   |
| ASUS PRIME               | 5         | 0.95%   |
| HP ZBook                 | 4         | 0.76%   |
| ASUS VivoBook            | 4         | 0.76%   |
| HP Spectre               | 3         | 0.57%   |
| HP ENVY                  | 3         | 0.57%   |
| Dell Precision           | 3         | 0.57%   |
| ASUS ZenBook             | 3         | 0.57%   |
| Acer Swift               | 3         | 0.57%   |
| Acer Nitro               | 3         | 0.57%   |
| Toshiba PORTEGE          | 2         | 0.38%   |
| MSI MS-7C91              | 2         | 0.38%   |
| MSI MS-7A34              | 2         | 0.38%   |
| Microsoft Surface        | 2         | 0.38%   |
| Medion Akoya             | 2         | 0.38%   |
| Lenovo ThinkCentre       | 2         | 0.38%   |
| Lenovo ThinkBook         | 2         | 0.38%   |
| Lenovo IdeaCentre        | 2         | 0.38%   |
| Lenovo B590              | 2         | 0.38%   |
| HP Stream                | 2         | 0.38%   |
| HP 15                    | 2         | 0.38%   |
| Gigabyte Z390            | 2         | 0.38%   |
| Gigabyte GA-MA785GM-US2H | 2         | 0.38%   |
| Gigabyte B550M           | 2         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 50        | 9.49%   |
| 2018    | 47        | 8.92%   |
| 2011    | 47        | 8.92%   |
| 2012    | 42        | 7.97%   |
| 2013    | 39        | 7.4%    |
| 2010    | 39        | 7.4%    |
| 2020    | 35        | 6.64%   |
| 2019    | 31        | 5.88%   |
| 2016    | 30        | 5.69%   |
| 2014    | 28        | 5.31%   |
| 2015    | 26        | 4.93%   |
| 2017    | 25        | 4.74%   |
| 2008    | 23        | 4.36%   |
| 2022    | 18        | 3.42%   |
| 2009    | 17        | 3.23%   |
| 2007    | 15        | 2.85%   |
| 2006    | 8         | 1.52%   |
| 2005    | 5         | 0.95%   |
| 2004    | 1         | 0.19%   |
| Unknown | 1         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 302       | 57.31%  |
| Desktop     | 176       | 33.4%   |
| Mini pc     | 16        | 3.04%   |
| Convertible | 13        | 2.47%   |
| Tablet      | 8         | 1.52%   |
| All in one  | 8         | 1.52%   |
| Server      | 4         | 0.76%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 525       | 99.62%  |
| Enabled  | 2         | 0.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 522       | 99.05%  |
| Yes  | 5         | 0.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 130       | 24.57%  |
| 8.01-16.0   | 111       | 20.98%  |
| 16.01-24.0  | 88        | 16.64%  |
| 3.01-4.0    | 82        | 15.5%   |
| 32.01-64.0  | 47        | 8.88%   |
| 1.01-2.0    | 36        | 6.81%   |
| 2.01-3.0    | 13        | 2.46%   |
| 24.01-32.0  | 8         | 1.51%   |
| 0.51-1.0    | 8         | 1.51%   |
| 64.01-256.0 | 6         | 1.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 194       | 34.77%  |
| 2.01-3.0   | 150       | 26.88%  |
| 3.01-4.0   | 82        | 14.7%   |
| 4.01-8.0   | 59        | 10.57%  |
| 0.51-1.0   | 52        | 9.32%   |
| 8.01-16.0  | 13        | 2.33%   |
| 0.01-0.5   | 7         | 1.25%   |
| 16.01-24.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 317       | 58.81%  |
| 2      | 130       | 24.12%  |
| 3      | 52        | 9.65%   |
| 4      | 18        | 3.34%   |
| 5      | 11        | 2.04%   |
| 0      | 6         | 1.11%   |
| 8      | 3         | 0.56%   |
| 7      | 1         | 0.19%   |
| 6      | 1         | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 323       | 60.94%  |
| Yes       | 207       | 39.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 464       | 88.05%  |
| No        | 63        | 11.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 407       | 77.08%  |
| No        | 121       | 22.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 301       | 57.01%  |
| No        | 227       | 42.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 121       | 22.87%  |
| Germany     | 58        | 10.96%  |
| Italy       | 31        | 5.86%   |
| UK          | 24        | 4.54%   |
| Russia      | 21        | 3.97%   |
| Spain       | 19        | 3.59%   |
| Canada      | 19        | 3.59%   |
| Slovakia    | 17        | 3.21%   |
| Poland      | 16        | 3.02%   |
| France      | 16        | 3.02%   |
| India       | 15        | 2.84%   |
| Australia   | 15        | 2.84%   |
| Brazil      | 14        | 2.65%   |
| Netherlands | 12        | 2.27%   |
| Finland     | 9         | 1.7%    |
| Austria     | 7         | 1.32%   |
| Switzerland | 6         | 1.13%   |
| Sweden      | 6         | 1.13%   |
| Serbia      | 6         | 1.13%   |
| Mexico      | 6         | 1.13%   |
| Ukraine     | 5         | 0.95%   |
| Turkey      | 5         | 0.95%   |
| Romania     | 4         | 0.76%   |
| New Zealand | 4         | 0.76%   |
| Indonesia   | 4         | 0.76%   |
| Hungary     | 4         | 0.76%   |
| Colombia    | 4         | 0.76%   |
| Belgium     | 4         | 0.76%   |
| Venezuela   | 3         | 0.57%   |
| Thailand    | 3         | 0.57%   |
| Greece      | 3         | 0.57%   |
| Denmark     | 3         | 0.57%   |
| Czechia     | 3         | 0.57%   |
| Chile       | 3         | 0.57%   |
| Argentina   | 3         | 0.57%   |
| Vietnam     | 2         | 0.38%   |
| Portugal    | 2         | 0.38%   |
| Philippines | 2         | 0.38%   |
| Norway      | 2         | 0.38%   |
| Ireland     | 2         | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Bratislava     | 16        | 2.93%   |
| Berlin         | 9         | 1.65%   |
| Vienna         | 7         | 1.28%   |
| Sydney         | 5         | 0.92%   |
| St Petersburg  | 5         | 0.92%   |
| Moscow         | 5         | 0.92%   |
| Melbourne      | 5         | 0.92%   |
| Warsaw         | 4         | 0.73%   |
| Rome           | 4         | 0.73%   |
| Milan          | 4         | 0.73%   |
| Belgrade       | 4         | 0.73%   |
| Amsterdam      | 4         | 0.73%   |
| Patna          | 3         | 0.55%   |
| Oxford         | 3         | 0.55%   |
| Munich         | 3         | 0.55%   |
| Montreal       | 3         | 0.55%   |
| Madrid         | 3         | 0.55%   |
| Los Angeles    | 3         | 0.55%   |
| Istanbul       | 3         | 0.55%   |
| Helsinki       | 3         | 0.55%   |
| Hamburg        | 3         | 0.55%   |
| Florianópolis | 3         | 0.55%   |
| Catania        | 3         | 0.55%   |
| Cambridge      | 3         | 0.55%   |
| Calgary        | 3         | 0.55%   |
| Buffalo        | 3         | 0.55%   |
| Budapest       | 3         | 0.55%   |
| Bogotá        | 3         | 0.55%   |
| Bengaluru      | 3         | 0.55%   |
| Barcelona      | 3         | 0.55%   |
| Walled Lake    | 2         | 0.37%   |
| Vera           | 2         | 0.37%   |
| Vasco da Gama  | 2         | 0.37%   |
| Valencia       | 2         | 0.37%   |
| Tacoma         | 2         | 0.37%   |
| Stockholm      | 2         | 0.37%   |
| Prague         | 2         | 0.37%   |
| Portland       | 2         | 0.37%   |
| Orange         | 2         | 0.37%   |
| New York       | 2         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 118       | 137    | 14.84%  |
| Samsung Electronics       | 112       | 156    | 14.09%  |
| Seagate                   | 102       | 134    | 12.83%  |
| Kingston                  | 59        | 63     | 7.42%   |
| Toshiba                   | 44        | 51     | 5.53%   |
| Crucial                   | 42        | 67     | 5.28%   |
| Unknown                   | 35        | 44     | 4.4%    |
| SanDisk                   | 34        | 40     | 4.28%   |
| Hitachi                   | 32        | 38     | 4.03%   |
| SK hynix                  | 20        | 21     | 2.52%   |
| Intel                     | 17        | 24     | 2.14%   |
| HGST                      | 12        | 17     | 1.51%   |
| A-DATA Technology         | 12        | 14     | 1.51%   |
| PNY                       | 9         | 10     | 1.13%   |
| Apple                     | 9         | 13     | 1.13%   |
| Micron Technology         | 8         | 12     | 1.01%   |
| China                     | 8         | 9      | 1.01%   |
| SPCC                      | 7         | 7      | 0.88%   |
| Corsair                   | 7         | 7      | 0.88%   |
| Transcend                 | 6         | 6      | 0.75%   |
| LITEON                    | 6         | 6      | 0.75%   |
| GOODRAM                   | 6         | 7      | 0.75%   |
| Maxtor                    | 5         | 6      | 0.63%   |
| Unknown                   | 5         | 5      | 0.63%   |
| Phison                    | 4         | 5      | 0.5%    |
| Netac                     | 4         | 4      | 0.5%    |
| KIOXIA                    | 4         | 6      | 0.5%    |
| Team                      | 3         | 3      | 0.38%   |
| Mushkin                   | 3         | 3      | 0.38%   |
| Fujitsu                   | 3         | 3      | 0.38%   |
| Dogfish                   | 3         | 3      | 0.38%   |
| Apacer                    | 3         | 3      | 0.38%   |
| Silicon Motion            | 2         | 2      | 0.25%   |
| Phison Electronics        | 2         | 3      | 0.25%   |
| Patriot                   | 2         | 2      | 0.25%   |
| OCZ                       | 2         | 2      | 0.25%   |
| Micron/Crucial Technology | 2         | 2      | 0.25%   |
| KingSpec                  | 2         | 2      | 0.25%   |
| KingFast                  | 2         | 2      | 0.25%   |
| KingDian                  | 2         | 2      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 12        | 1.38%   |
| Kingston SA400S37480G 480GB SSD        | 11        | 1.27%   |
| Kingston SA400S37240G 240GB SSD        | 8         | 0.92%   |
| Samsung SSD 850 EVO 250GB              | 7         | 0.81%   |
| Kingston SV300S37A120G 120GB SSD       | 7         | 0.81%   |
| Kingston SA400S37120G 120GB SSD        | 7         | 0.81%   |
| Seagate ST1000LM035-1RK172 970GB       | 6         | 0.69%   |
| Samsung SSD 980 PRO 1TB                | 6         | 0.69%   |
| Samsung SSD 970 EVO Plus 1TB           | 6         | 0.69%   |
| Crucial CT500MX500SSD1 500GB           | 6         | 0.69%   |
| Crucial CT120BX500SSD1 120GB           | 6         | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB         | 5         | 0.58%   |
| Seagate ST1000LM048-2E7172 1TB         | 5         | 0.58%   |
| Unknown                                | 5         | 0.58%   |
| Toshiba MQ01ABF050 500GB               | 4         | 0.46%   |
| Toshiba DT01ACA100 1TB                 | 4         | 0.46%   |
| Seagate ST500LM021-1KJ152 500GB        | 4         | 0.46%   |
| Seagate ST500DM002-1BD142 500GB        | 4         | 0.46%   |
| Seagate ST4000DM004-2CV104 4TB         | 4         | 0.46%   |
| Seagate ST3500413AS 500GB              | 4         | 0.46%   |
| Seagate ST1000DM010-2EP102 1TB         | 4         | 0.46%   |
| Samsung SSD 870 EVO 500GB              | 4         | 0.46%   |
| Samsung SSD 860 EVO 250GB              | 4         | 0.46%   |
| Samsung SSD 850 EVO 500GB              | 4         | 0.46%   |
| Kingston SV300S37A240G 240GB SSD       | 4         | 0.46%   |
| Hitachi HTS543232A7A384 320GB          | 4         | 0.46%   |
| HGST HTS721010A9E630 1TB               | 4         | 0.46%   |
| Crucial CT480BX500SSD1 480GB           | 4         | 0.46%   |
| A-DATA SP600 32GB SSD                  | 4         | 0.46%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 0.35%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 3         | 0.35%   |
| Unknown SD32G  32GB                    | 3         | 0.35%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 0.35%   |
| Seagate ST2000DM001-1ER164 2TB         | 3         | 0.35%   |
| SanDisk SDSSDA240G 240GB               | 3         | 0.35%   |
| SanDisk SDSSDA120G 120GB               | 3         | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB         | 3         | 0.35%   |
| Samsung SSD 970 EVO 1TB                | 3         | 0.35%   |
| Samsung SSD 860 EVO 1TB                | 3         | 0.35%   |
| Samsung SSD 850 EVO 1TB                | 3         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 102       | 133    | 35.17%  |
| WDC                 | 88        | 104    | 30.34%  |
| Toshiba             | 33        | 40     | 11.38%  |
| Hitachi             | 32        | 38     | 11.03%  |
| HGST                | 12        | 17     | 4.14%   |
| Samsung Electronics | 9         | 11     | 3.1%    |
| Maxtor              | 5         | 6      | 1.72%   |
| Fujitsu             | 3         | 3      | 1.03%   |
| Unknown             | 2         | 2      | 0.69%   |
| IBM/Hitachi         | 1         | 1      | 0.34%   |
| External            | 1         | 1      | 0.34%   |
| ASMT                | 1         | 1      | 0.34%   |
| Apple               | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 68        | 86     | 20.8%   |
| Kingston            | 47        | 50     | 14.37%  |
| Crucial             | 38        | 56     | 11.62%  |
| SanDisk             | 29        | 33     | 8.87%   |
| WDC                 | 14        | 15     | 4.28%   |
| A-DATA Technology   | 11        | 13     | 3.36%   |
| PNY                 | 8         | 8      | 2.45%   |
| China               | 8         | 9      | 2.45%   |
| SPCC                | 7         | 7      | 2.14%   |
| SK hynix            | 7         | 7      | 2.14%   |
| Transcend           | 6         | 6      | 1.83%   |
| GOODRAM             | 6         | 7      | 1.83%   |
| Apple               | 6         | 9      | 1.83%   |
| Micron Technology   | 5         | 9      | 1.53%   |
| LITEON              | 5         | 5      | 1.53%   |
| Intel               | 5         | 9      | 1.53%   |
| Toshiba             | 4         | 4      | 1.22%   |
| Netac               | 4         | 4      | 1.22%   |
| Dogfish             | 3         | 3      | 0.92%   |
| Team                | 2         | 2      | 0.61%   |
| Patriot             | 2         | 2      | 0.61%   |
| OCZ                 | 2         | 2      | 0.61%   |
| Mushkin             | 2         | 2      | 0.61%   |
| KingSpec            | 2         | 2      | 0.61%   |
| KingFast            | 2         | 2      | 0.61%   |
| KingDian            | 2         | 2      | 0.61%   |
| Intenso             | 2         | 2      | 0.61%   |
| Indilinx            | 2         | 4      | 0.61%   |
| Gigabyte Technology | 2         | 2      | 0.61%   |
| Corsair             | 2         | 2      | 0.61%   |
| Apacer              | 2         | 2      | 0.61%   |
| Unknown             | 2         | 2      | 0.61%   |
| ZTC                 | 1         | 1      | 0.31%   |
| Yeyian              | 1         | 1      | 0.31%   |
| WDC WDS1            | 1         | 1      | 0.31%   |
| Teclast             | 1         | 1      | 0.31%   |
| SWORDBILL           | 1         | 2      | 0.31%   |
| Smart               | 1         | 1      | 0.31%   |
| RENICE              | 1         | 1      | 0.31%   |
| Phison              | 1         | 1      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 281       | 391    | 39.8%   |
| HDD     | 245       | 358    | 34.7%   |
| NVMe    | 136       | 178    | 19.26%  |
| MMC     | 37        | 47     | 5.24%   |
| Unknown | 7         | 9      | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 411       | 729    | 68.05%  |
| NVMe | 136       | 177    | 22.52%  |
| MMC  | 37        | 47     | 6.13%   |
| SAS  | 20        | 30     | 3.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 340       | 481    | 63.31%  |
| 0.51-1.0   | 136       | 186    | 25.33%  |
| 1.01-2.0   | 33        | 43     | 6.15%   |
| 3.01-4.0   | 10        | 11     | 1.86%   |
| 2.01-3.0   | 10        | 11     | 1.86%   |
| 4.01-10.0  | 7         | 16     | 1.3%    |
| 10.01-20.0 | 1         | 1      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 149       | 27.24%  |
| 251-500        | 108       | 19.74%  |
| 501-1000       | 75        | 13.71%  |
| 51-100         | 62        | 11.33%  |
| 21-50          | 44        | 8.04%   |
| 1001-2000      | 41        | 7.5%    |
| 1-20           | 26        | 4.75%   |
| More than 3000 | 22        | 4.02%   |
| 2001-3000      | 18        | 3.29%   |
| Unknown        | 2         | 0.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 208       | 37.55%  |
| 21-50          | 84        | 15.16%  |
| 101-250        | 76        | 13.72%  |
| 51-100         | 67        | 12.09%  |
| 251-500        | 52        | 9.39%   |
| 501-1000       | 30        | 5.42%   |
| 1001-2000      | 20        | 3.61%   |
| More than 3000 | 8         | 1.44%   |
| 2001-3000      | 7         | 1.26%   |
| Unknown        | 2         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 970GB      | 3         | 3      | 2.59%   |
| Toshiba MK7575GSX 752GB               | 2         | 3      | 1.72%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 1.72%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 1.72%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 2      | 1.72%   |
| Indilinx IND-S325S120G 120GB SSD      | 2         | 4      | 1.72%   |
| A-DATA Technology SU650 240GB SSD     | 2         | 2      | 1.72%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 1      | 0.86%   |
| WDC WD5003ABYX-01WERA1 500GB          | 1         | 1      | 0.86%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.86%   |
| WDC WD5000BPVT-60HXZT3 500GB          | 1         | 1      | 0.86%   |
| WDC WD5000AAKS-40V6A0 500GB           | 1         | 1      | 0.86%   |
| WDC WD3200LPVX-22V0TT0 320GB          | 1         | 1      | 0.86%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 0.86%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 1      | 0.86%   |
| WDC WD3200BEKT-60PVMT0 320GB          | 1         | 1      | 0.86%   |
| WDC WD3200AAKS-00UU3A0 320GB          | 1         | 1      | 0.86%   |
| WDC WD3200AAJS-00B4A0 320GB           | 1         | 1      | 0.86%   |
| WDC WD2500AAJS-00B4A0 250GB           | 1         | 1      | 0.86%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1         | 1      | 0.86%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 0.86%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1         | 1      | 0.86%   |
| WDC WD1600BEVT-22A23T0 160GB          | 1         | 1      | 0.86%   |
| WDC WD1600AVVS-63L2B0 160GB           | 1         | 1      | 0.86%   |
| WDC WD15EADS-11P8B2 1TB               | 1         | 1      | 0.86%   |
| WDC WD10EZRZ-00HTKB0 1TB              | 1         | 1      | 0.86%   |
| WDC WD10EZEX-75WN4A0 1TB              | 1         | 1      | 0.86%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 1      | 0.86%   |
| WDC WD10EAVS-00D7B1 1TB               | 1         | 1      | 0.86%   |
| WDC WD10EADS-98M2B0 1TB               | 1         | 1      | 0.86%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 0.86%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD  | 1         | 1      | 0.86%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 0.86%   |
| Toshiba MK6465GSX 640GB               | 1         | 1      | 0.86%   |
| Toshiba MK5059GSXP 500GB              | 1         | 1      | 0.86%   |
| Toshiba MK2565GSX 250GB               | 1         | 1      | 0.86%   |
| SPCC Solid State Disk 512GB           | 1         | 1      | 0.86%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD | 1         | 1      | 0.86%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 0.86%   |
| Seagate ST9320421AS 320GB             | 1         | 1      | 0.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 30     | 24.56%  |
| WDC                 | 24        | 24     | 21.05%  |
| Hitachi             | 12        | 13     | 10.53%  |
| Samsung Electronics | 9         | 12     | 7.89%   |
| Toshiba             | 7         | 8      | 6.14%   |
| HGST                | 6         | 7      | 5.26%   |
| Crucial             | 5         | 15     | 4.39%   |
| Maxtor              | 4         | 4      | 3.51%   |
| Kingston            | 4         | 4      | 3.51%   |
| Indilinx            | 2         | 4      | 1.75%   |
| Fujitsu             | 2         | 2      | 1.75%   |
| A-DATA Technology   | 2         | 2      | 1.75%   |
| SPCC                | 1         | 1      | 0.88%   |
| SK hynix            | 1         | 1      | 0.88%   |
| SanDisk             | 1         | 1      | 0.88%   |
| RENICE              | 1         | 1      | 0.88%   |
| Intenso             | 1         | 1      | 0.88%   |
| Intel               | 1         | 2      | 0.88%   |
| IBM/Hitachi         | 1         | 1      | 0.88%   |
| GOODRAM             | 1         | 1      | 0.88%   |
| China               | 1         | 1      | 0.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 30     | 32.94%  |
| WDC                 | 23        | 23     | 27.06%  |
| Hitachi             | 12        | 13     | 14.12%  |
| Toshiba             | 6         | 7      | 7.06%   |
| HGST                | 6         | 7      | 7.06%   |
| Maxtor              | 4         | 4      | 4.71%   |
| Samsung Electronics | 3         | 5      | 3.53%   |
| Fujitsu             | 2         | 2      | 2.35%   |
| IBM/Hitachi         | 1         | 1      | 1.18%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 82        | 92     | 73.87%  |
| SSD  | 27        | 35     | 24.32%  |
| NVMe | 2         | 8      | 1.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Toshiba MK5065GSX 500GB   | 2         | 2      | 66.67%  |
| Seagate ST3500418AS 500GB | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| Seagate | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 434       | 752    | 70.57%  |
| Malfunc  | 107       | 135    | 17.4%   |
| Detected | 71        | 92     | 11.54%  |
| Failed   | 3         | 4      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 364       | 57.59%  |
| AMD                          | 87        | 13.77%  |
| Samsung Electronics          | 49        | 7.75%   |
| SanDisk                      | 19        | 3.01%   |
| Phison Electronics           | 13        | 2.06%   |
| Kingston Technology Company  | 12        | 1.9%    |
| SK hynix                     | 11        | 1.74%   |
| Nvidia                       | 11        | 1.74%   |
| ASMedia Technology           | 10        | 1.58%   |
| Micron/Crucial Technology    | 7         | 1.11%   |
| Marvell Technology Group     | 7         | 1.11%   |
| KIOXIA                       | 7         | 1.11%   |
| JMicron Technology           | 7         | 1.11%   |
| Silicon Motion               | 5         | 0.79%   |
| Toshiba America Info Systems | 4         | 0.63%   |
| Micron Technology            | 3         | 0.47%   |
| VIA Technologies             | 2         | 0.32%   |
| ULi Electronics              | 2         | 0.32%   |
| Silicon Image                | 2         | 0.32%   |
| Broadcom / LSI               | 2         | 0.32%   |
| Apple                        | 2         | 0.32%   |
| Shenzhen Longsys Electronics | 1         | 0.16%   |
| LSI Logic / Symbios Logic    | 1         | 0.16%   |
| Lite-On Technology           | 1         | 0.16%   |
| Lenovo                       | 1         | 0.16%   |
| Hewlett-Packard              | 1         | 0.16%   |
| ADATA Technology             | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 51        | 7%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 34        | 4.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 28        | 3.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 24        | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 24        | 3.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 21        | 2.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 14        | 1.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 12        | 1.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 12        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 12        | 1.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 11        | 1.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 11        | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 11        | 1.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 1.37%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10        | 1.37%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 10        | 1.37%   |
| AMD 500 Series Chipset SATA Controller                                         | 10        | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 1.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9         | 1.23%   |
| Samsung NVMe SSD Controller 980                                                | 8         | 1.1%    |
| Phison E12 NVMe Controller                                                     | 8         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 8         | 1.1%    |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 0.96%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 7         | 0.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 0.82%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 6         | 0.82%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 6         | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6         | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 6         | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 0.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 6         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 0.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 0.82%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 391       | 60.53%  |
| NVMe | 134       | 20.74%  |
| IDE  | 83        | 12.85%  |
| RAID | 36        | 5.57%   |
| SCSI | 2         | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 417       | 79.13%  |
| AMD          | 109       | 20.68%  |
| CentaurHauls | 1         | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 9         | 1.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 8         | 1.52%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 7         | 1.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 7         | 1.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 6         | 1.14%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5         | 0.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 0.95%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5         | 0.95%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 5         | 0.95%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 5         | 0.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 4         | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 0.76%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 0.76%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 4         | 0.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 0.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 0.76%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 4         | 0.76%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 4         | 0.76%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4         | 0.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 0.57%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 3         | 0.57%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 3         | 0.57%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 0.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 0.57%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 0.57%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 3         | 0.57%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3         | 0.57%   |
| Intel Core i3-4000M CPU @ 2.40GHz           | 3         | 0.57%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 0.57%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 3         | 0.57%   |
| Intel Celeron N4100 CPU @ 1.10GHz           | 3         | 0.57%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 3         | 0.57%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 0.57%   |
| Intel 12th Gen Core i7-12700H               | 3         | 0.57%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 3         | 0.57%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3         | 0.57%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3         | 0.57%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.38%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 2         | 0.38%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2         | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 109       | 20.68%  |
| Intel Core i7           | 97        | 18.41%  |
| Intel Core i3           | 41        | 7.78%   |
| Intel Celeron           | 36        | 6.83%   |
| Other                   | 33        | 6.26%   |
| AMD Ryzen 5             | 27        | 5.12%   |
| Intel Core 2 Duo        | 26        | 4.93%   |
| AMD Ryzen 7             | 25        | 4.74%   |
| Intel Atom              | 21        | 3.98%   |
| Intel Pentium           | 11        | 2.09%   |
| Intel Xeon              | 8         | 1.52%   |
| Intel Pentium Dual-Core | 5         | 0.95%   |
| Intel Core 2 Quad       | 5         | 0.95%   |
| AMD Ryzen 3             | 5         | 0.95%   |
| Intel Pentium 4         | 4         | 0.76%   |
| AMD E1                  | 4         | 0.76%   |
| AMD A6                  | 4         | 0.76%   |
| Intel Core i9           | 3         | 0.57%   |
| Intel Core 2            | 3         | 0.57%   |
| AMD Turion 64 X2 Mobile | 3         | 0.57%   |
| AMD Sempron             | 3         | 0.57%   |
| AMD Ryzen 9             | 3         | 0.57%   |
| AMD Phenom II X4        | 3         | 0.57%   |
| AMD E                   | 3         | 0.57%   |
| AMD Athlon II X4        | 3         | 0.57%   |
| AMD Athlon II X2        | 3         | 0.57%   |
| AMD A8                  | 3         | 0.57%   |
| AMD A4                  | 3         | 0.57%   |
| Intel Pentium Silver    | 2         | 0.38%   |
| Intel Pentium M         | 2         | 0.38%   |
| Intel Pentium Gold      | 2         | 0.38%   |
| Intel Celeron M         | 2         | 0.38%   |
| AMD Phenom II X6        | 2         | 0.38%   |
| AMD Phenom              | 2         | 0.38%   |
| AMD Athlon 64 X2        | 2         | 0.38%   |
| AMD Athlon              | 2         | 0.38%   |
| AMD A10                 | 2         | 0.38%   |
| Intel Pentium Dual      | 1         | 0.19%   |
| Intel Pentium D         | 1         | 0.19%   |
| Intel Genuine           | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 230       | 43.64%  |
| 4      | 180       | 34.16%  |
| 6      | 45        | 8.54%   |
| 8      | 37        | 7.02%   |
| 1      | 21        | 3.98%   |
| 12     | 6         | 1.14%   |
| 14     | 3         | 0.57%   |
| 10     | 3         | 0.57%   |
| 16     | 1         | 0.19%   |
| 5      | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 523       | 99.24%  |
| 2      | 4         | 0.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 324       | 61.48%  |
| 1      | 203       | 38.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 513       | 97.16%  |
| 32-bit         | 15        | 2.84%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 10.86%  |
| 0x206a7    | 41        | 7.68%   |
| 0x306a9    | 36        | 6.74%   |
| 0x306c3    | 28        | 5.24%   |
| 0x1067a    | 19        | 3.56%   |
| 0x806c1    | 16        | 3%      |
| 0x406e3    | 16        | 3%      |
| 0x20655    | 14        | 2.62%   |
| 0x906ea    | 11        | 2.06%   |
| 0x506e3    | 11        | 2.06%   |
| 0x40651    | 11        | 2.06%   |
| 0x806ea    | 10        | 1.87%   |
| 0x806e9    | 10        | 1.87%   |
| 0x0a50000c | 9         | 1.69%   |
| 0x806ec    | 8         | 1.5%    |
| 0x306d4    | 8         | 1.5%    |
| 0x30678    | 8         | 1.5%    |
| 0x906ed    | 7         | 1.31%   |
| 0x406c4    | 7         | 1.31%   |
| 0x08701021 | 7         | 1.31%   |
| 0x906e9    | 6         | 1.12%   |
| 0x706a8    | 6         | 1.12%   |
| 0x706a1    | 6         | 1.12%   |
| 0x20652    | 6         | 1.12%   |
| 0x08608103 | 6         | 1.12%   |
| 0x0800820d | 6         | 1.12%   |
| 0x6fd      | 5         | 0.94%   |
| 0x106e5    | 5         | 0.94%   |
| 0x10676    | 5         | 0.94%   |
| 0xa0671    | 4         | 0.75%   |
| 0xa0653    | 4         | 0.75%   |
| 0xa0652    | 4         | 0.75%   |
| 0x906a3    | 4         | 0.75%   |
| 0x506c9    | 4         | 0.75%   |
| 0x106ca    | 4         | 0.75%   |
| 0x106c2    | 4         | 0.75%   |
| 0x08600106 | 4         | 0.75%   |
| 0x08108109 | 4         | 0.75%   |
| 0x03000027 | 4         | 0.75%   |
| 0x010000db | 4         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 61        | 11.55%  |
| SandyBridge      | 49        | 9.28%   |
| Haswell          | 46        | 8.71%   |
| IvyBridge        | 41        | 7.77%   |
| Skylake          | 30        | 5.68%   |
| Penryn           | 30        | 5.68%   |
| Westmere         | 22        | 4.17%   |
| Silvermont       | 20        | 3.79%   |
| Zen 3            | 17        | 3.22%   |
| TigerLake        | 17        | 3.22%   |
| Zen+             | 16        | 3.03%   |
| K10              | 15        | 2.84%   |
| Unknown          | 15        | 2.84%   |
| Zen 2            | 13        | 2.46%   |
| Goldmont plus    | 12        | 2.27%   |
| Core             | 12        | 2.27%   |
| Bonnell          | 11        | 2.08%   |
| Zen              | 10        | 1.89%   |
| IceLake          | 9         | 1.7%    |
| CometLake        | 9         | 1.7%    |
| Broadwell        | 9         | 1.7%    |
| Nehalem          | 8         | 1.52%   |
| K8 Hammer        | 8         | 1.52%   |
| P6               | 6         | 1.14%   |
| NetBurst         | 6         | 1.14%   |
| Puma             | 5         | 0.95%   |
| Goldmont         | 5         | 0.95%   |
| Alderlake Hybrid | 5         | 0.95%   |
| K10 Llano        | 4         | 0.76%   |
| Excavator        | 4         | 0.76%   |
| Tremont          | 3         | 0.57%   |
| Jaguar           | 3         | 0.57%   |
| Bobcat           | 3         | 0.57%   |
| Steamroller      | 1         | 0.19%   |
| Piledriver       | 1         | 0.19%   |
| K8 & K10 hybrid  | 1         | 0.19%   |
| Bulldozer        | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 325       | 53.02%  |
| Nvidia                     | 147       | 23.98%  |
| AMD                        | 139       | 22.68%  |
| VIA Technologies           | 1         | 0.16%   |
| Matrox Electronics Systems | 1         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 37        | 5.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 4.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 2.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 2.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 2.19%   |
| Intel UHD Graphics 620                                                                   | 11        | 1.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 1.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 1.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 1.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 1.57%   |
| Intel HD Graphics 620                                                                    | 9         | 1.41%   |
| Intel HD Graphics 530                                                                    | 9         | 1.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 1.41%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 1.25%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7         | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 1.1%    |
| AMD Lucienne                                                                             | 7         | 1.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 5         | 0.78%   |
| Intel HD Graphics 630                                                                    | 5         | 0.78%   |
| Intel HD Graphics 5500                                                                   | 5         | 0.78%   |
| AMD Renoir                                                                               | 5         | 0.78%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.63%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.63%   |
| Intel HD Graphics 500                                                                    | 4         | 0.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.63%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 0.63%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 246       | 46.42%  |
| 1 x AMD        | 108       | 20.38%  |
| 1 x Nvidia     | 92        | 17.36%  |
| Intel + Nvidia | 49        | 9.25%   |
| Intel + AMD    | 17        | 3.21%   |
| 2 x AMD        | 9         | 1.7%    |
| AMD + Nvidia   | 5         | 0.94%   |
| 3 x AMD        | 1         | 0.19%   |
| 2 x Intel      | 1         | 0.19%   |
| 1 x VIA        | 1         | 0.19%   |
| 1 x Matrox     | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 445       | 83.18%  |
| Proprietary | 68        | 12.71%  |
| Unknown     | 22        | 4.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 321       | 59.89%  |
| 0.01-0.5   | 63        | 11.75%  |
| 1.01-2.0   | 48        | 8.96%   |
| 0.51-1.0   | 43        | 8.02%   |
| 3.01-4.0   | 29        | 5.41%   |
| 7.01-8.0   | 19        | 3.54%   |
| 8.01-16.0  | 5         | 0.93%   |
| 5.01-6.0   | 4         | 0.75%   |
| 2.01-3.0   | 4         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 76        | 13.57%  |
| AU Optronics            | 65        | 11.61%  |
| Chimei Innolux          | 53        | 9.46%   |
| LG Display              | 45        | 8.04%   |
| BOE                     | 35        | 6.25%   |
| Dell                    | 29        | 5.18%   |
| Goldstar                | 28        | 5%      |
| Hewlett-Packard         | 21        | 3.75%   |
| Lenovo                  | 19        | 3.39%   |
| Acer                    | 19        | 3.39%   |
| Chi Mei Optoelectronics | 15        | 2.68%   |
| Apple                   | 12        | 2.14%   |
| Ancor Communications    | 12        | 2.14%   |
| PANDA                   | 10        | 1.79%   |
| Sony                    | 9         | 1.61%   |
| AOC                     | 9         | 1.61%   |
| Philips                 | 8         | 1.43%   |
| BenQ                    | 7         | 1.25%   |
| ViewSonic               | 5         | 0.89%   |
| Iiyama                  | 5         | 0.89%   |
| HannStar                | 5         | 0.89%   |
| Fujitsu Siemens         | 5         | 0.89%   |
| Eizo                    | 5         | 0.89%   |
| Sharp                   | 4         | 0.71%   |
| LG Philips              | 4         | 0.71%   |
| InfoVision              | 4         | 0.71%   |
| ASUSTek Computer        | 4         | 0.71%   |
| Vizio                   | 3         | 0.54%   |
| Vestel Elektronik       | 3         | 0.54%   |
| MSI                     | 3         | 0.54%   |
| CPT                     | 3         | 0.54%   |
| Sceptre Tech            | 2         | 0.36%   |
| Panasonic               | 2         | 0.36%   |
| NEC Computers           | 2         | 0.36%   |
| MiTAC                   | 2         | 0.36%   |
| Medion                  | 2         | 0.36%   |
| Xiaomi                  | 1         | 0.18%   |
| Videoseven              | 1         | 0.18%   |
| Sunplus                 | 1         | 0.18%   |
| STA                     | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 8         | 1.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 1.06%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 0.71%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 0.71%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 3         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.53%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.53%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 3         | 0.53%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                       | 2         | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.35%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch        | 2         | 0.35%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.35%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 0.35%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.35%   |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                          | 2         | 0.35%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 0.35%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 2         | 0.35%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.35%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                    | 2         | 0.35%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.35%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 798x334mm 34.1-inch                 | 2         | 0.35%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.35%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.35%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                    | 2         | 0.35%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.35%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 2         | 0.35%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 2         | 0.35%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                    | 2         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 230       | 42.44%  |
| 1366x768 (WXGA)    | 108       | 19.93%  |
| 3840x2160 (4K)     | 32        | 5.9%    |
| 1600x900 (HD+)     | 22        | 4.06%   |
| 1680x1050 (WSXGA+) | 21        | 3.87%   |
| 2560x1440 (QHD)    | 20        | 3.69%   |
| 1280x1024 (SXGA)   | 20        | 3.69%   |
| 1280x800 (WXGA)    | 14        | 2.58%   |
| 1440x900 (WXGA+)   | 12        | 2.21%   |
| 1600x1200          | 9         | 1.66%   |
| 1920x1200 (WUXGA)  | 8         | 1.48%   |
| 1024x600           | 8         | 1.48%   |
| 2560x1080          | 5         | 0.92%   |
| 1360x768           | 5         | 0.92%   |
| 3440x1440          | 3         | 0.55%   |
| 2880x1800          | 3         | 0.55%   |
| 2560x1600          | 3         | 0.55%   |
| 2160x1440          | 3         | 0.55%   |
| 1024x768 (XGA)     | 3         | 0.55%   |
| 2256x1504          | 2         | 0.37%   |
| 1400x1050          | 2         | 0.37%   |
| 1280x720 (HD)      | 2         | 0.37%   |
| Unknown            | 2         | 0.37%   |
| 3840x2400          | 1         | 0.18%   |
| 3840x1080          | 1         | 0.18%   |
| 3000x2000          | 1         | 0.18%   |
| 2736x1824          | 1         | 0.18%   |
| 2048x1536          | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 144       | 25.85%  |
| 13      | 48        | 8.62%   |
| 23      | 39        | 7%      |
| 14      | 38        | 6.82%   |
| 24      | 37        | 6.64%   |
| 27      | 36        | 6.46%   |
| 17      | 33        | 5.92%   |
| 21      | 32        | 5.75%   |
| 19      | 15        | 2.69%   |
| 11      | 13        | 2.33%   |
| 31      | 12        | 2.15%   |
| 22      | 12        | 2.15%   |
| 18      | 12        | 2.15%   |
| 12      | 11        | 1.97%   |
| 10      | 10        | 1.8%    |
| Unknown | 10        | 1.8%    |
| 20      | 9         | 1.62%   |
| 34      | 8         | 1.44%   |
| 84      | 7         | 1.26%   |
| 16      | 4         | 0.72%   |
| 65      | 3         | 0.54%   |
| 40      | 3         | 0.54%   |
| 26      | 3         | 0.54%   |
| 25      | 3         | 0.54%   |
| 43      | 2         | 0.36%   |
| 42      | 2         | 0.36%   |
| 32      | 2         | 0.36%   |
| 72      | 1         | 0.18%   |
| 61      | 1         | 0.18%   |
| 54      | 1         | 0.18%   |
| 49      | 1         | 0.18%   |
| 47      | 1         | 0.18%   |
| 46      | 1         | 0.18%   |
| 39      | 1         | 0.18%   |
| 37      | 1         | 0.18%   |
| 36      | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 209       | 38%     |
| 501-600     | 109       | 19.82%  |
| 401-500     | 67        | 12.18%  |
| 201-300     | 58        | 10.55%  |
| 351-400     | 47        | 8.55%   |
| 601-700     | 14        | 2.55%   |
| 701-800     | 11        | 2%      |
| Unknown     | 10        | 1.82%   |
| 1501-2000   | 8         | 1.45%   |
| 1001-1500   | 8         | 1.45%   |
| 801-900     | 5         | 0.91%   |
| 901-1000    | 4         | 0.73%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 397       | 76.64%  |
| 16/10   | 63        | 12.16%  |
| 5/4     | 20        | 3.86%   |
| 4/3     | 15        | 2.9%    |
| 3/2     | 9         | 1.74%   |
| 21/9    | 8         | 1.54%   |
| Unknown | 6         | 1.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 143       | 25.86%  |
| 201-250        | 102       | 18.44%  |
| 81-90          | 68        | 12.3%   |
| 301-350        | 37        | 6.69%   |
| 151-200        | 34        | 6.15%   |
| 121-130        | 26        | 4.7%    |
| 351-500        | 22        | 3.98%   |
| 71-80          | 18        | 3.25%   |
| More than 1000 | 14        | 2.53%   |
| 251-300        | 14        | 2.53%   |
| 141-150        | 14        | 2.53%   |
| 51-60          | 13        | 2.35%   |
| 501-1000       | 12        | 2.17%   |
| 61-70          | 10        | 1.81%   |
| 41-50          | 10        | 1.81%   |
| Unknown        | 10        | 1.81%   |
| 111-120        | 3         | 0.54%   |
| 91-100         | 2         | 0.36%   |
| 131-140        | 1         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 207       | 38.33%  |
| 101-120       | 138       | 25.56%  |
| 121-160       | 137       | 25.37%  |
| 161-240       | 27        | 5%      |
| 1-50          | 12        | 2.22%   |
| Unknown       | 10        | 1.85%   |
| More than 240 | 9         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 440       | 82.4%   |
| 2     | 72        | 13.48%  |
| 0     | 17        | 3.18%   |
| 3     | 5         | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 271       | 33.5%   |
| Intel                             | 258       | 31.89%  |
| Qualcomm Atheros                  | 97        | 11.99%  |
| Broadcom                          | 49        | 6.06%   |
| TP-Link                           | 13        | 1.61%   |
| MediaTek                          | 13        | 1.61%   |
| Broadcom Limited                  | 12        | 1.48%   |
| Marvell Technology Group          | 11        | 1.36%   |
| Ralink Technology                 | 10        | 1.24%   |
| Ralink                            | 10        | 1.24%   |
| Nvidia                            | 9         | 1.11%   |
| ASIX Electronics                  | 5         | 0.62%   |
| Sierra Wireless                   | 4         | 0.49%   |
| Qualcomm Atheros Communications   | 3         | 0.37%   |
| Microsoft                         | 3         | 0.37%   |
| Huawei Technologies               | 3         | 0.37%   |
| Ericsson Business Mobile Networks | 3         | 0.37%   |
| AVM                               | 3         | 0.37%   |
| Attansic Technology               | 3         | 0.37%   |
| VIA Technologies                  | 2         | 0.25%   |
| Samsung Electronics               | 2         | 0.25%   |
| NetGear                           | 2         | 0.25%   |
| Motorola PCS                      | 2         | 0.25%   |
| JMicron Technology                | 2         | 0.25%   |
| Edimax Technology                 | 2         | 0.25%   |
| ASUSTek Computer                  | 2         | 0.25%   |
| Xiaomi                            | 1         | 0.12%   |
| U-Blox                            | 1         | 0.12%   |
| Sweex                             | 1         | 0.12%   |
| Qualcomm                          | 1         | 0.12%   |
| OPPO Electronics                  | 1         | 0.12%   |
| Mercucys                          | 1         | 0.12%   |
| Linksys                           | 1         | 0.12%   |
| Lenovo                            | 1         | 0.12%   |
| Hewlett-Packard                   | 1         | 0.12%   |
| Google                            | 1         | 0.12%   |
| Dell                              | 1         | 0.12%   |
| D-Link System                     | 1         | 0.12%   |
| D-Link                            | 1         | 0.12%   |
| Aquantia                          | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 185       | 19.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 32        | 3.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 19        | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 18        | 1.89%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 15        | 1.58%   |
| Intel Wireless 8260                                                     | 14        | 1.47%   |
| Intel Wi-Fi 6 AX201                                                     | 14        | 1.47%   |
| Intel Wireless 8265 / 8275                                              | 13        | 1.37%   |
| Intel Wireless 7260                                                     | 13        | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 1.26%   |
| Intel Wireless 3165                                                     | 12        | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 1.16%   |
| Intel Ethernet Connection I217-LM                                       | 11        | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.05%   |
| Intel Wireless 7265                                                     | 10        | 1.05%   |
| Intel Ethernet Controller I225-V                                        | 10        | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                       | 8         | 0.84%   |
| Intel I211 Gigabit Network Connection                                   | 8         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                                | 8         | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 0.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 7         | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 7         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 0.74%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 7         | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 0.63%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 5         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.53%   |
| Intel Ethernet Connection (7) I219-V                                    | 5         | 0.53%   |
| Intel Ethernet Connection (2) I219-V                                    | 5         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                                   | 5         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 194       | 44.09%  |
| Realtek Semiconductor           | 71        | 16.14%  |
| Qualcomm Atheros                | 70        | 15.91%  |
| Broadcom                        | 32        | 7.27%   |
| TP-Link                         | 12        | 2.73%   |
| MediaTek                        | 12        | 2.73%   |
| Ralink Technology               | 10        | 2.27%   |
| Ralink                          | 10        | 2.27%   |
| Broadcom Limited                | 7         | 1.59%   |
| Sierra Wireless                 | 3         | 0.68%   |
| Qualcomm Atheros Communications | 3         | 0.68%   |
| AVM                             | 3         | 0.68%   |
| NetGear                         | 2         | 0.45%   |
| Edimax Technology               | 2         | 0.45%   |
| ASUSTek Computer                | 2         | 0.45%   |
| Sweex                           | 1         | 0.23%   |
| Microsoft                       | 1         | 0.23%   |
| Mercucys                        | 1         | 0.23%   |
| Marvell Technology Group        | 1         | 0.23%   |
| Linksys                         | 1         | 0.23%   |
| Hewlett-Packard                 | 1         | 0.23%   |
| D-Link                          | 1         | 0.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 18        | 4.08%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 3.85%   |
| Intel Wireless 8260                                                     | 14        | 3.17%   |
| Intel Wi-Fi 6 AX201                                                     | 14        | 3.17%   |
| Intel Wireless 8265 / 8275                                              | 13        | 2.95%   |
| Intel Wireless 7260                                                     | 13        | 2.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 2.72%   |
| Intel Wireless 3165                                                     | 12        | 2.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.27%   |
| Intel Wireless 7265                                                     | 10        | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 1.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 7         | 1.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 7         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 1.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 1.59%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 1.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.36%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.36%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.13%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.91%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4         | 0.91%   |
| Intel Wireless-AC 9260                                                  | 4         | 0.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.91%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 0.91%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 3         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.68%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 240       | 49.28%  |
| Intel                    | 134       | 27.52%  |
| Qualcomm Atheros         | 37        | 7.6%    |
| Broadcom                 | 25        | 5.13%   |
| Marvell Technology Group | 10        | 2.05%   |
| Nvidia                   | 9         | 1.85%   |
| Broadcom Limited         | 5         | 1.03%   |
| ASIX Electronics         | 5         | 1.03%   |
| Attansic Technology      | 3         | 0.62%   |
| VIA Technologies         | 2         | 0.41%   |
| Microsoft                | 2         | 0.41%   |
| JMicron Technology       | 2         | 0.41%   |
| Xiaomi                   | 1         | 0.21%   |
| TP-Link                  | 1         | 0.21%   |
| Sierra Wireless          | 1         | 0.21%   |
| Samsung Electronics      | 1         | 0.21%   |
| Qualcomm                 | 1         | 0.21%   |
| OPPO Electronics         | 1         | 0.21%   |
| Motorola PCS             | 1         | 0.21%   |
| MediaTek                 | 1         | 0.21%   |
| Lenovo                   | 1         | 0.21%   |
| Huawei Technologies      | 1         | 0.21%   |
| D-Link System            | 1         | 0.21%   |
| Aquantia                 | 1         | 0.21%   |
| Apple                    | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 185       | 37%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 6.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 3.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 3%      |
| Intel Ethernet Connection I217-LM                                 | 11        | 2.2%    |
| Intel Ethernet Controller I225-V                                  | 10        | 2%      |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 1.6%    |
| Intel I211 Gigabit Network Connection                             | 8         | 1.6%    |
| Intel 82577LM Gigabit Network Connection                          | 8         | 1.6%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 7         | 1.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1%      |
| Intel Ethernet Connection (7) I219-V                              | 5         | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1%      |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 1%      |
| Intel Ethernet Connection (2) I218-V                              | 5         | 1%      |
| Intel 82567LM Gigabit Network Connection                          | 5         | 1%      |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 1%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5         | 1%      |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.8%    |
| Intel Ethernet Connection I219-V                                  | 4         | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.8%    |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.8%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3         | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 3         | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.6%    |
| Attansic AR8152 v2.0 Fast Ethernet                                | 3         | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.4%    |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.4%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.4%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 463       | 52.55%  |
| WiFi     | 407       | 46.2%   |
| Modem    | 9         | 1.02%   |
| Unknown  | 2         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 325       | 60.3%   |
| Ethernet | 213       | 39.52%  |
| Unknown  | 1         | 0.19%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 303       | 57.39%  |
| 1     | 202       | 38.26%  |
| 3     | 11        | 2.08%   |
| 0     | 10        | 1.89%   |
| 12    | 1         | 0.19%   |
| 4     | 1         | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 430       | 80.98%  |
| Yes  | 101       | 19.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 139       | 45.28%  |
| Realtek Semiconductor           | 26        | 8.47%   |
| Qualcomm Atheros Communications | 26        | 8.47%   |
| Broadcom                        | 23        | 7.49%   |
| Cambridge Silicon Radio         | 17        | 5.54%   |
| Apple                           | 17        | 5.54%   |
| IMC Networks                    | 11        | 3.58%   |
| Foxconn / Hon Hai               | 11        | 3.58%   |
| Lite-On Technology              | 9         | 2.93%   |
| Hewlett-Packard                 | 7         | 2.28%   |
| MediaTek                        | 4         | 1.3%    |
| ASUSTek Computer                | 4         | 1.3%    |
| Toshiba                         | 3         | 0.98%   |
| Ralink                          | 3         | 0.98%   |
| Dell                            | 3         | 0.98%   |
| Alps Electric                   | 2         | 0.65%   |
| TP-Link                         | 1         | 0.33%   |
| Marvell Semiconductor           | 1         | 0.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 62        | 20.2%   |
| Intel AX201 Bluetooth                                                               | 23        | 7.49%   |
| Realtek Bluetooth Radio                                                             | 17        | 5.54%   |
| Intel AX200 Bluetooth                                                               | 17        | 5.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 17        | 5.54%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 14        | 4.56%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 4.23%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 2.28%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 2.28%   |
| Apple Bluetooth Host Controller                                                     | 7         | 2.28%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1.95%   |
| Apple Bluetooth USB Host Controller                                                 | 6         | 1.95%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 1.63%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 1.63%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.3%    |
| MediaTek Wireless_Device                                                            | 4         | 1.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 1.3%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 1.3%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 1.3%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 4         | 1.3%    |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.98%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 0.98%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 0.98%   |
| Intel Bluetooth Device                                                              | 3         | 0.98%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.98%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 0.98%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 0.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.65%   |
| Lite-On Wireless_Device                                                             | 2         | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.65%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.65%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.65%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.65%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.65%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 393       | 54.13%  |
| AMD                        | 137       | 18.87%  |
| Nvidia                     | 120       | 16.53%  |
| C-Media Electronics        | 11        | 1.52%   |
| Creative Labs              | 10        | 1.38%   |
| VIA Technologies           | 4         | 0.55%   |
| Texas Instruments          | 4         | 0.55%   |
| JMTek                      | 4         | 0.55%   |
| GN Netcom                  | 3         | 0.41%   |
| Focusrite-Novation         | 3         | 0.41%   |
| ROCCAT                     | 2         | 0.28%   |
| Realtek Semiconductor      | 2         | 0.28%   |
| Microsoft                  | 2         | 0.28%   |
| Logitech                   | 2         | 0.28%   |
| Generalplus Technology     | 2         | 0.28%   |
| BEHRINGER International    | 2         | 0.28%   |
| Apple                      | 2         | 0.28%   |
| ULi Electronics            | 1         | 0.14%   |
| TerraTec Electronic        | 1         | 0.14%   |
| Tenx Technology            | 1         | 0.14%   |
| SteelSeries ApS            | 1         | 0.14%   |
| Shenzhen Riitek Technology | 1         | 0.14%   |
| Setek Elektronik           | 1         | 0.14%   |
| Schiit Audio               | 1         | 0.14%   |
| Razer USA                  | 1         | 0.14%   |
| Plantronics                | 1         | 0.14%   |
| Mark of the Unicorn        | 1         | 0.14%   |
| LG Electronics             | 1         | 0.14%   |
| Lenovo                     | 1         | 0.14%   |
| Kingston Technology        | 1         | 0.14%   |
| GYROCOM C&C                | 1         | 0.14%   |
| Guillemot                  | 1         | 0.14%   |
| Fortemedia                 | 1         | 0.14%   |
| FIFINE 683 Microphone      | 1         | 0.14%   |
| Ensoniq                    | 1         | 0.14%   |
| Digidesign                 | 1         | 0.14%   |
| Dell                       | 1         | 0.14%   |
| Creative Technology        | 1         | 0.14%   |
| Conexant Systems           | 1         | 0.14%   |
| CMX Systems                | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 47        | 5.57%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 40        | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 39        | 4.62%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 39        | 4.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 3.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 24        | 2.84%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 24        | 2.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 20        | 2.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 20        | 2.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 19        | 2.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 18        | 2.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 1.9%    |
| AMD FCH Azalia Controller                                                                         | 15        | 1.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 1.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 12        | 1.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 12        | 1.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 1.3%    |
| Intel 8 Series HD Audio Controller                                                                | 11        | 1.3%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 11        | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 9         | 1.07%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 0.95%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 0.95%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 8         | 0.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8         | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 7         | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 0.71%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 0.71%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 6         | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 6         | 0.71%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 6         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 117       | 18.99%  |
| SK hynix                     | 102       | 16.56%  |
| Unknown                      | 83        | 13.47%  |
| Kingston                     | 70        | 11.36%  |
| Micron Technology            | 53        | 8.6%    |
| Crucial                      | 32        | 5.19%   |
| Corsair                      | 30        | 4.87%   |
| G.Skill                      | 20        | 3.25%   |
| Ramaxel Technology           | 15        | 2.44%   |
| A-DATA Technology            | 15        | 2.44%   |
| Elpida                       | 12        | 1.95%   |
| Unknown (ABCD)               | 10        | 1.62%   |
| Nanya Technology             | 7         | 1.14%   |
| Transcend                    | 6         | 0.97%   |
| Unknown                      | 6         | 0.97%   |
| Smart                        | 5         | 0.81%   |
| Patriot                      | 4         | 0.65%   |
| Apacer                       | 4         | 0.65%   |
| Teikon                       | 2         | 0.32%   |
| Team                         | 2         | 0.32%   |
| PNY                          | 2         | 0.32%   |
| Avant                        | 2         | 0.32%   |
| Wilk                         | 1         | 0.16%   |
| Unknown (F301)               | 1         | 0.16%   |
| Unknown (AB)                 | 1         | 0.16%   |
| Unifosa                      | 1         | 0.16%   |
| TRS STAR                     | 1         | 0.16%   |
| RZX                          | 1         | 0.16%   |
| Patriot Memory (PDP Systems) | 1         | 0.16%   |
| OCZ                          | 1         | 0.16%   |
| Innodisk                     | 1         | 0.16%   |
| High Bridge                  | 1         | 0.16%   |
| Hewlett-Packard              | 1         | 0.16%   |
| Golden Empire                | 1         | 0.16%   |
| Essencore                    | 1         | 0.16%   |
| CSX                          | 1         | 0.16%   |
| Axiom                        | 1         | 0.16%   |
| ASint Technology             | 1         | 0.16%   |
| 48spaces                     | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 7         | 1.04%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.89%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.89%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 6         | 0.89%   |
| Unknown                                                          | 6         | 0.89%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.74%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.74%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.74%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.6%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.6%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.6%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 0.6%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 3         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 3         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.45%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 3         | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 3         | 0.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.45%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 0.45%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 3         | 0.45%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.45%   |
| Samsung RAM M471B5273BH1-CF8 4096MB SODIMM DDR3 1067MT/s         | 3         | 0.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.45%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 3         | 0.45%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 0.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s         | 3         | 0.45%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.3%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.3%    |
| Unknown RAM Module 4GB DIMM SDRAM                                | 2         | 0.3%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.3%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 2         | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 228       | 42.86%  |
| DDR4    | 188       | 35.34%  |
| DDR2    | 35        | 6.58%   |
| LPDDR4  | 21        | 3.95%   |
| Unknown | 18        | 3.38%   |
| SDRAM   | 15        | 2.82%   |
| DDR     | 14        | 2.63%   |
| LPDDR3  | 9         | 1.69%   |
| DRAM    | 3         | 0.56%   |
| DDR5    | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 336       | 63.52%  |
| DIMM         | 167       | 31.57%  |
| Row Of Chips | 21        | 3.97%   |
| Chip         | 3         | 0.57%   |
| Unknown      | 2         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 199       | 34.13%  |
| 8192  | 171       | 29.33%  |
| 2048  | 103       | 17.67%  |
| 16384 | 62        | 10.63%  |
| 1024  | 32        | 5.49%   |
| 32768 | 11        | 1.89%   |
| 512   | 4         | 0.69%   |
| 256   | 1         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 136       | 23.45%  |
| 3200    | 64        | 11.03%  |
| 1333    | 56        | 9.66%   |
| 2667    | 55        | 9.48%   |
| 2400    | 38        | 6.55%   |
| 1334    | 31        | 5.34%   |
| Unknown | 27        | 4.66%   |
| 2133    | 22        | 3.79%   |
| 667     | 22        | 3.79%   |
| 800     | 15        | 2.59%   |
| 3600    | 14        | 2.41%   |
| 1067    | 12        | 2.07%   |
| 1867    | 11        | 1.9%    |
| 3000    | 6         | 1.03%   |
| 4267    | 5         | 0.86%   |
| 4199    | 5         | 0.86%   |
| 3466    | 5         | 0.86%   |
| 3266    | 5         | 0.86%   |
| 2933    | 4         | 0.69%   |
| 2666    | 4         | 0.69%   |
| 533     | 4         | 0.69%   |
| 333     | 4         | 0.69%   |
| 3733    | 3         | 0.52%   |
| 2048    | 3         | 0.52%   |
| 1800    | 3         | 0.52%   |
| 1639    | 3         | 0.52%   |
| 400     | 3         | 0.52%   |
| 49926   | 2         | 0.34%   |
| 8400    | 2         | 0.34%   |
| 3400    | 2         | 0.34%   |
| 1066    | 2         | 0.34%   |
| 4800    | 1         | 0.17%   |
| 4266    | 1         | 0.17%   |
| 4133    | 1         | 0.17%   |
| 3866    | 1         | 0.17%   |
| 3100    | 1         | 0.17%   |
| 2200    | 1         | 0.17%   |
| 2000    | 1         | 0.17%   |
| 1866    | 1         | 0.17%   |
| 975     | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Canon                 | 4         | 26.67%  |
| Brother Industries    | 4         | 26.67%  |
| Hewlett-Packard       | 3         | 20%     |
| Seiko Epson           | 1         | 6.67%   |
| Samsung Electronics   | 1         | 6.67%   |
| Lexmark International | 1         | 6.67%   |
| Konica Minolta        | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon MF641C                       | 2         | 13.33%  |
| Brother DCP-L2540DW                | 2         | 13.33%  |
| Seiko Epson L380 Series            | 1         | 6.67%   |
| Samsung ML-1610 Mono Laser Printer | 1         | 6.67%   |
| Lexmark International CS417dn      | 1         | 6.67%   |
| Konica Minolta 206                 | 1         | 6.67%   |
| HP LaserJet P2055 series           | 1         | 6.67%   |
| HP LaserJet M101-M106              | 1         | 6.67%   |
| HP LaserJet 1022                   | 1         | 6.67%   |
| Canon MG5700 series                | 1         | 6.67%   |
| Canon LiDE 400                     | 1         | 6.67%   |
| Brother MFC-7340                   | 1         | 6.67%   |
| Brother HL-2150N series            | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 5         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 20%     |
| Canon CanoScan LiDE 700F           | 1         | 20%     |
| Canon CanoScan LIDE 25             | 1         | 20%     |
| Canon CanoScan LiDE 210            | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 70        | 22.65%  |
| Realtek Semiconductor                  | 25        | 8.09%   |
| Microdia                               | 21        | 6.8%    |
| IMC Networks                           | 18        | 5.83%   |
| Sunplus Innovation Technology          | 17        | 5.5%    |
| Cheng Uei Precision Industry (Foxlink) | 17        | 5.5%    |
| Acer                                   | 16        | 5.18%   |
| Quanta                                 | 14        | 4.53%   |
| Logitech                               | 13        | 4.21%   |
| Bison Electronics                      | 11        | 3.56%   |
| Suyin                                  | 10        | 3.24%   |
| Lite-On Technology                     | 10        | 3.24%   |
| Apple                                  | 10        | 3.24%   |
| Lenovo                                 | 8         | 2.59%   |
| Microsoft                              | 6         | 1.94%   |
| Ricoh                                  | 5         | 1.62%   |
| Luxvisions Innotech Limited            | 4         | 1.29%   |
| Z-Star Microelectronics                | 3         | 0.97%   |
| Syntek                                 | 3         | 0.97%   |
| Silicon Motion                         | 3         | 0.97%   |
| Alcor Micro                            | 3         | 0.97%   |
| Hewlett-Packard                        | 2         | 0.65%   |
| Generalplus Technology                 | 2         | 0.65%   |
| GEMBIRD                                | 2         | 0.65%   |
| Y Media                                | 1         | 0.32%   |
| Xiongmai                               | 1         | 0.32%   |
| WaveRider Communications               | 1         | 0.32%   |
| Trust                                  | 1         | 0.32%   |
| Sunplus Technology                     | 1         | 0.32%   |
| Sonix Technology                       | 1         | 0.32%   |
| Samsung Electronics                    | 1         | 0.32%   |
| Primax Electronics                     | 1         | 0.32%   |
| Novatek Microelectronics               | 1         | 0.32%   |
| LG Electronics                         | 1         | 0.32%   |
| Importek                               | 1         | 0.32%   |
| icSpring                               | 1         | 0.32%   |
| Huawei Technologies                    | 1         | 0.32%   |
| Goodong Industry                       | 1         | 0.32%   |
| Cubeternet                             | 1         | 0.32%   |
| Arkmicro Technologies                  | 1         | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 15        | 4.84%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 9         | 2.9%    |
| Realtek Integrated_Webcam_HD                                | 7         | 2.26%   |
| Microdia Integrated_Webcam_HD                               | 6         | 1.94%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 1.61%   |
| Lite-On Integrated Camera                                   | 5         | 1.61%   |
| Chicony HD WebCam                                           | 5         | 1.61%   |
| Apple Built-in iSight                                       | 5         | 1.61%   |
| Quanta HD User Facing                                       | 4         | 1.29%   |
| Microsoft LifeCam HD-3000                                   | 4         | 1.29%   |
| Lenovo Integrated Webcam [R5U877]                           | 4         | 1.29%   |
| Chicony USB 2.0 Camera                                      | 4         | 1.29%   |
| Chicony TOSHIBA Web Camera - HD                             | 4         | 1.29%   |
| Chicony HP TrueVision HD Camera                             | 4         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 4         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 4         | 1.29%   |
| Bison Integrated Camera                                     | 4         | 1.29%   |
| Syntek EasyCamera                                           | 3         | 0.97%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 3         | 0.97%   |
| Sunplus ASUS Webcam                                         | 3         | 0.97%   |
| Ricoh USB2.0 Camera                                         | 3         | 0.97%   |
| Realtek USB Camera                                          | 3         | 0.97%   |
| Logitech Webcam C270                                        | 3         | 0.97%   |
| Lenovo Integrated Webcam                                    | 3         | 0.97%   |
| IMC Networks Integrated Camera                              | 3         | 0.97%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 0.97%   |
| Chicony HD User Facing                                      | 3         | 0.97%   |
| Apple FaceTime HD Camera (Built-in)                         | 3         | 0.97%   |
| Acer Integrated Camera                                      | 3         | 0.97%   |
| Acer BisonCam, NB Pro                                       | 3         | 0.97%   |
| Sunplus HD WebCam                                           | 2         | 0.65%   |
| Sunplus HD 720P webcam                                      | 2         | 0.65%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 0.65%   |
| Realtek USB2.0 camera                                       | 2         | 0.65%   |
| Realtek Integrated Webcam HD                                | 2         | 0.65%   |
| Quanta VGA WebCam                                           | 2         | 0.65%   |
| Quanta HP Wide Vision HD Camera                             | 2         | 0.65%   |
| Quanta HP TrueVision HD Camera                              | 2         | 0.65%   |
| Microdia Webcam Vitade AF                                   | 2         | 0.65%   |
| Microdia USB 2.0 Camera                                     | 2         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 29.31%  |
| Synaptics                  | 11        | 18.97%  |
| Upek                       | 8         | 13.79%  |
| Shenzhen Goodix Technology | 7         | 12.07%  |
| AuthenTec                  | 7         | 12.07%  |
| Elan Microelectronics      | 3         | 5.17%   |
| LighTuning Technology      | 2         | 3.45%   |
| STMicroelectronics         | 1         | 1.72%   |
| Microsoft                  | 1         | 1.72%   |
| Focal-systems.Corp         | 1         | 1.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 6         | 10.34%  |
| Shenzhen Goodix  FingerPrint Device                        | 5         | 8.62%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 6.9%    |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 6.9%    |
| AuthenTec AES2810                                          | 4         | 6.9%    |
| Validity Sensors Synaptics WBDI                            | 3         | 5.17%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 3.45%   |
| Upek TCS5B Fingerprint sensor                              | 2         | 3.45%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 3.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 3.45%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 3.45%   |
| Elan ELAN:Fingerprint                                      | 2         | 3.45%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 3.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 1.72%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 1.72%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 1.72%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.72%   |
| Synaptics WBDI Fingerprint Reader USB 102                  | 1         | 1.72%   |
| Synaptics UWP WBDI Device                                  | 1         | 1.72%   |
| Synaptics UWP WBDI                                         | 1         | 1.72%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.72%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 1.72%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 1.72%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.72%   |
| Microsoft Fingerprint Reader                               | 1         | 1.72%   |
| LighTuning Fingerprint Reader                              | 1         | 1.72%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 1.72%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.72%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.72%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 1.72%   |
| Unknown                                                    | 1         | 1.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 9         | 39.13%  |
| Broadcom              | 8         | 34.78%  |
| Lenovo                | 3         | 13.04%  |
| Advanced Card Systems | 2         | 8.7%    |
| O2 Micro              | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 39.13%  |
| Broadcom 5880                                                                | 5         | 21.74%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 13.04%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 8.7%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.35%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 4.35%   |
| Advanced Card Systems ACR122U                                                | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 375       | 69.7%   |
| 1     | 124       | 23.05%  |
| 2     | 32        | 5.95%   |
| 3     | 7         | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 76        | 38.38%  |
| Fingerprint reader       | 58        | 29.29%  |
| Chipcard                 | 20        | 10.1%   |
| Net/wireless             | 10        | 5.05%   |
| Multimedia controller    | 10        | 5.05%   |
| Communication controller | 8         | 4.04%   |
| Unassigned class         | 3         | 1.52%   |
| Storage                  | 3         | 1.52%   |
| Camera                   | 3         | 1.52%   |
| Net/ethernet             | 2         | 1.01%   |
| Bluetooth                | 2         | 1.01%   |
| Sound                    | 1         | 0.51%   |
| Flash memory             | 1         | 0.51%   |
| Dvb card                 | 1         | 0.51%   |

