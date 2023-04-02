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

Total: 383

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.0-21-amd64            | 25        | 8.87%   |
| 5.10.0-13-amd64            | 20        | 7.09%   |
| 5.10.0-9-amd64             | 18        | 6.38%   |
| 5.10.0-19-amd64            | 18        | 6.38%   |
| 5.10.0-18-amd64            | 18        | 6.38%   |
| 5.14.0-4mx-amd64           | 16        | 5.67%   |
| 5.10.0-20-amd64            | 16        | 5.67%   |
| 6.0.0-6mx-amd64            | 15        | 5.32%   |
| 5.16.0-5mx-amd64           | 13        | 4.61%   |
| 5.10.0-16-amd64            | 13        | 4.61%   |
| 5.10.0-11-amd64            | 8         | 2.84%   |
| 5.18.0-4mx-amd64           | 7         | 2.48%   |
| 5.10.0-15-amd64            | 6         | 2.13%   |
| 5.10.0-14-amd64            | 6         | 2.13%   |
| 6.0.0-4mx-amd64            | 4         | 1.42%   |
| 6.0.0-10.1-liquorix-amd64  | 4         | 1.42%   |
| 5.19.0-2mx-amd64           | 4         | 1.42%   |
| 5.10.0-17-amd64            | 4         | 1.42%   |
| 5.10.0-10-amd64            | 4         | 1.42%   |
| 6.0.0-3mx-amd64            | 3         | 1.06%   |
| 5.16.0-6mx-amd64           | 3         | 1.06%   |
| 6.1.0-4mx-amd64            | 2         | 0.71%   |
| 6.1.0-2mx-amd64            | 2         | 0.71%   |
| 5.17.0-3mx-amd64           | 2         | 0.71%   |
| 5.16.0-4mx-amd64           | 2         | 0.71%   |
| 5.16.0-18.1-liquorix-amd64 | 2         | 0.71%   |
| 5.14.0-3mx-amd64           | 2         | 0.71%   |
| 5.10.0-8-amd64             | 2         | 0.71%   |
| 5.10.0-18-686-pae          | 2         | 0.71%   |
| 5.10.0-13-686-pae          | 2         | 0.71%   |
| 5.10.0-12-amd64            | 2         | 0.71%   |
| 5.10.0-11-686-pae          | 2         | 0.71%   |
| 6.1.15-2-liquorix-amd64    | 1         | 0.35%   |
| 6.1.12-3-liquorix-amd64    | 1         | 0.35%   |
| 6.1.0-t2                   | 1         | 0.35%   |
| 6.0.5-x64v1-xanmod1        | 1         | 0.35%   |
| 6.0.0-4mx-rt-amd64         | 1         | 0.35%   |
| 6.0.0-13.3-liquorix-amd64  | 1         | 0.35%   |
| 6.0.0-11.2-liquorix-amd64  | 1         | 0.35%   |
| 5.19.0-4.2-liquorix-amd64  | 1         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 161       | 58.97%  |
| 6.0.0    | 29        | 10.62%  |
| 5.16.0   | 21        | 7.69%   |
| 5.14.0   | 19        | 6.96%   |
| 5.19.0   | 9         | 3.3%    |
| 5.18.0   | 9         | 3.3%    |
| 5.17.0   | 6         | 2.2%    |
| 6.1.0    | 5         | 1.83%   |
| 5.15.0   | 3         | 1.1%    |
| 4.19.0   | 2         | 0.73%   |
| 6.1.15   | 1         | 0.37%   |
| 6.1.12   | 1         | 0.37%   |
| 6.0.5    | 1         | 0.37%   |
| 5.10.82  | 1         | 0.37%   |
| 5.10.52  | 1         | 0.37%   |
| 5.10.142 | 1         | 0.37%   |
| 5.10.113 | 1         | 0.37%   |
| 5.10.111 | 1         | 0.37%   |
| Unknown  | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 166       | 60.81%  |
| 6.0     | 30        | 10.99%  |
| 5.16    | 21        | 7.69%   |
| 5.14    | 19        | 6.96%   |
| 5.19    | 9         | 3.3%    |
| 5.18    | 9         | 3.3%    |
| 6.1     | 7         | 2.56%   |
| 5.17    | 6         | 2.2%    |
| 5.15    | 3         | 1.1%    |
| 4.19    | 2         | 0.73%   |
| Unknown | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 252       | 96.55%  |
| i686   | 9         | 3.45%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 188       | 70.94%  |
| KDE5             | 58        | 21.89%  |
| lightdm-xsession | 4         | 1.51%   |
| GNOME            | 4         | 1.51%   |
| Budgie           | 3         | 1.13%   |
| Unknown          | 3         | 1.13%   |
| X-Cinnamon       | 1         | 0.38%   |
| LXQt             | 1         | 0.38%   |
| i3               | 1         | 0.38%   |
| GNOME Classic    | 1         | 0.38%   |
| fluxbox          | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 258       | 98.85%  |
| Tty     | 2         | 0.77%   |
| Wayland | 1         | 0.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 200       | 76.05%  |
| SDDM    | 55        | 20.91%  |
| SLiM    | 6         | 2.28%   |
| GDM     | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 123       | 46.77%  |
| de_DE   | 36        | 13.69%  |
| it_IT   | 16        | 6.08%   |
| en_GB   | 15        | 5.7%    |
| ru_RU   | 7         | 2.66%   |
| pl_PL   | 6         | 2.28%   |
| en_AU   | 6         | 2.28%   |
| fr_FR   | 5         | 1.9%    |
| es_ES   | 5         | 1.9%    |
| de_CH   | 5         | 1.9%    |
| Unknown | 4         | 1.52%   |
| pt_BR   | 3         | 1.14%   |
| en_NZ   | 3         | 1.14%   |
| tr_TR   | 2         | 0.76%   |
| sv_SE   | 2         | 0.76%   |
| nl_NL   | 2         | 0.76%   |
| hu_HU   | 2         | 0.76%   |
| fi_FI   | 2         | 0.76%   |
| es_MX   | 2         | 0.76%   |
| es_CO   | 2         | 0.76%   |
| es_AR   | 2         | 0.76%   |
| bg_BG   | 2         | 0.76%   |
| sk_SK   | 1         | 0.38%   |
| nb_NO   | 1         | 0.38%   |
| id_ID   | 1         | 0.38%   |
| fr_CA   | 1         | 0.38%   |
| fr_BE   | 1         | 0.38%   |
| eu_ES   | 1         | 0.38%   |
| es_VE   | 1         | 0.38%   |
| es_UY   | 1         | 0.38%   |
| es_PE   | 1         | 0.38%   |
| en_CA   | 1         | 0.38%   |
| da_DK   | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 171       | 65.52%  |
| BIOS | 90        | 34.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 220       | 83.65%  |
| Overlay  | 30        | 11.41%  |
| Btrfs    | 8         | 3.04%   |
| Xfs      | 2         | 0.76%   |
| Reiserfs | 1         | 0.38%   |
| F2fs     | 1         | 0.38%   |
| Ext3     | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 188       | 72.03%  |
| MBR     | 71        | 27.2%   |
| Unknown | 2         | 0.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 186       | 70.45%  |
| Yes       | 78        | 29.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 140       | 53.23%  |
| Yes       | 123       | 46.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 36        | 13.79%  |
| Hewlett-Packard                      | 35        | 13.41%  |
| ASUSTek Computer                     | 32        | 12.26%  |
| Dell                                 | 27        | 10.34%  |
| Apple                                | 16        | 6.13%   |
| MSI                                  | 14        | 5.36%   |
| Gigabyte Technology                  | 13        | 4.98%   |
| Acer                                 | 12        | 4.6%    |
| Sony                                 | 8         | 3.07%   |
| Medion                               | 5         | 1.92%   |
| Intel                                | 5         | 1.92%   |
| ASRock                               | 5         | 1.92%   |
| Toshiba                              | 4         | 1.53%   |
| Unknown                              | 4         | 1.53%   |
| Samsung Electronics                  | 3         | 1.15%   |
| Alienware                            | 3         | 1.15%   |
| ZOTAC                                | 2         | 0.77%   |
| TUXEDO                               | 2         | 0.77%   |
| Pegatron                             | 2         | 0.77%   |
| Microsoft                            | 2         | 0.77%   |
| Fujitsu Siemens                      | 2         | 0.77%   |
| Fujitsu                              | 2         | 0.77%   |
| Chuwi                                | 2         | 0.77%   |
| Biostar                              | 2         | 0.77%   |
| AZW                                  | 2         | 0.77%   |
| win element                          | 1         | 0.38%   |
| Vulcan Electronics                   | 1         | 0.38%   |
| Sun Microsystems                     | 1         | 0.38%   |
| SIRAGON                              | 1         | 0.38%   |
| Shenzhen Wangang Technology          | 1         | 0.38%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.38%   |
| SANTECH                              | 1         | 0.38%   |
| RTD Embedded Technologies            | 1         | 0.38%   |
| Notebook                             | 1         | 0.38%   |
| MP                                   | 1         | 0.38%   |
| Linx                                 | 1         | 0.38%   |
| Huanan                               | 1         | 0.38%   |
| GEO                                  | 1         | 0.38%   |
| GALAX                                | 1         | 0.38%   |
| Framework                            | 1         | 0.38%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 6         | 2.3%    |
| ASUS All Series                              | 4         | 1.53%   |
| MSI MS-7C91                                  | 2         | 0.77%   |
| HP Laptop 17-ak0xx                           | 2         | 0.77%   |
| Gigabyte GA-MA785GM-US2H                     | 2         | 0.77%   |
| Dell OptiPlex 755                            | 2         | 0.77%   |
| Chuwi GemiBook Pro                           | 2         | 0.77%   |
| AZW SER                                      | 2         | 0.77%   |
| ASUS ROG Maximus XIII HERO                   | 2         | 0.77%   |
| Apple Macmini8,1                             | 2         | 0.77%   |
| Apple MacBookAir7,2                          | 2         | 0.77%   |
| Acer Nitro AN515-55                          | 2         | 0.77%   |
| ZOTAC ZBOX-ECM73070C/53060C                  | 1         | 0.38%   |
| win element MoreFine S500+                   | 1         | 0.38%   |
| Vulcan Excursion XB                          | 1         | 0.38%   |
| TUXEDO N7x0WU                                | 1         | 0.38%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)           | 1         | 0.38%   |
| Toshiba Satellite M70                        | 1         | 0.38%   |
| Toshiba Satellite L650                       | 1         | 0.38%   |
| Toshiba Satellite C845                       | 1         | 0.38%   |
| Toshiba PORTEGE Z30-C                        | 1         | 0.38%   |
| Sun Microsystems Sun Ultra 40 M2 Workstation | 1         | 0.38%   |
| Sony VPCYB3V1E                               | 1         | 0.38%   |
| Sony VPCSB1V9R                               | 1         | 0.38%   |
| Sony VPCF119FX                               | 1         | 0.38%   |
| Sony VPCEH2N1E                               | 1         | 0.38%   |
| Sony VPCEC3S1E                               | 1         | 0.38%   |
| Sony VPCCB32FD                               | 1         | 0.38%   |
| Sony VGN-TZ3RXN_B                            | 1         | 0.38%   |
| Sony SVE1513Q1ESI                            | 1         | 0.38%   |
| SIRAGON AIO-5150                             | 1         | 0.38%   |
| Shenzhen Wangang AERO 2 Pro                  | 1         | 0.38%   |
| Shenzhen Meigao Electronic Equipment UM450   | 1         | 0.38%   |
| SANTECH X170KM-G                             | 1         | 0.38%   |
| Samsung NC210/NC110                          | 1         | 0.38%   |
| Samsung 350V5C/351V5C/3540VC/3440VC          | 1         | 0.38%   |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 0.38%   |
| RTD Embedded CMA34CR                         | 1         | 0.38%   |
| Pegatron FQ425AA-ABA a6655f                  | 1         | 0.38%   |
| Pegatron 2AD5                                | 1         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 17        | 6.51%   |
| Dell OptiPlex            | 7         | 2.68%   |
| HP ProBook               | 6         | 2.3%    |
| HP Compaq                | 6         | 2.3%    |
| Dell Inspiron            | 6         | 2.3%    |
| Acer Aspire              | 6         | 2.3%    |
| Unknown                  | 6         | 2.3%    |
| HP EliteBook             | 5         | 1.92%   |
| Dell Latitude            | 5         | 1.92%   |
| Lenovo IdeaPad           | 4         | 1.53%   |
| ASUS ROG                 | 4         | 1.53%   |
| ASUS All                 | 4         | 1.53%   |
| Toshiba Satellite        | 3         | 1.15%   |
| HP Laptop                | 3         | 1.15%   |
| Dell Vostro              | 3         | 1.15%   |
| Dell Precision           | 3         | 1.15%   |
| ASUS TUF                 | 3         | 1.15%   |
| Acer Nitro               | 3         | 1.15%   |
| MSI MS-7C91              | 2         | 0.77%   |
| Microsoft Surface        | 2         | 0.77%   |
| Lenovo ThinkCentre       | 2         | 0.77%   |
| Lenovo ThinkBook         | 2         | 0.77%   |
| Lenovo IdeaCentre        | 2         | 0.77%   |
| HP ZBook                 | 2         | 0.77%   |
| HP ENVY                  | 2         | 0.77%   |
| Gigabyte GA-MA785GM-US2H | 2         | 0.77%   |
| Gigabyte B550M           | 2         | 0.77%   |
| Chuwi GemiBook           | 2         | 0.77%   |
| AZW SER                  | 2         | 0.77%   |
| ASUS VivoBook            | 2         | 0.77%   |
| ASUS P5GC-MX             | 2         | 0.77%   |
| ASUS ASUS                | 2         | 0.77%   |
| Apple Macmini8           | 2         | 0.77%   |
| Apple Macmini6           | 2         | 0.77%   |
| Apple MacBookPro11       | 2         | 0.77%   |
| Apple MacBookAir7        | 2         | 0.77%   |
| Alienware m15            | 2         | 0.77%   |
| Acer Swift               | 2         | 0.77%   |
| ZOTAC ZBOX-ECM73070C     | 1         | 0.38%   |
| win element MoreFine     | 1         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 37        | 14.18%  |
| 2020    | 24        | 9.2%    |
| 2018    | 20        | 7.66%   |
| 2016    | 18        | 6.9%    |
| 2015    | 18        | 6.9%    |
| 2012    | 17        | 6.51%   |
| 2011    | 17        | 6.51%   |
| 2019    | 16        | 6.13%   |
| 2022    | 15        | 5.75%   |
| 2010    | 15        | 5.75%   |
| 2013    | 14        | 5.36%   |
| 2014    | 11        | 4.21%   |
| 2009    | 9         | 3.45%   |
| 2007    | 9         | 3.45%   |
| 2017    | 8         | 3.07%   |
| 2008    | 8         | 3.07%   |
| 2006    | 2         | 0.77%   |
| 2005    | 2         | 0.77%   |
| Unknown | 1         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 151       | 57.85%  |
| Desktop     | 83        | 31.8%   |
| Mini pc     | 10        | 3.83%   |
| Convertible | 7         | 2.68%   |
| All in one  | 6         | 2.3%    |
| Tablet      | 2         | 0.77%   |
| Server      | 2         | 0.77%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 259       | 99.23%  |
| Enabled  | 2         | 0.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 261       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 70        | 26.82%  |
| 8.01-16.0   | 56        | 21.46%  |
| 16.01-24.0  | 41        | 15.71%  |
| 3.01-4.0    | 33        | 12.64%  |
| 32.01-64.0  | 32        | 12.26%  |
| 1.01-2.0    | 10        | 3.83%   |
| 2.01-3.0    | 7         | 2.68%   |
| 64.01-256.0 | 6         | 2.3%    |
| 24.01-32.0  | 4         | 1.53%   |
| 0.51-1.0    | 2         | 0.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 90        | 32.85%  |
| 2.01-3.0   | 83        | 30.29%  |
| 3.01-4.0   | 44        | 16.06%  |
| 4.01-8.0   | 35        | 12.77%  |
| 0.51-1.0   | 13        | 4.74%   |
| 8.01-16.0  | 7         | 2.55%   |
| 16.01-24.0 | 1         | 0.36%   |
| 0.01-0.5   | 1         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 152       | 57.36%  |
| 2      | 61        | 23.02%  |
| 3      | 32        | 12.08%  |
| 4      | 10        | 3.77%   |
| 5      | 4         | 1.51%   |
| 8      | 3         | 1.13%   |
| 0      | 2         | 0.75%   |
| 7      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 166       | 63.6%   |
| Yes       | 95        | 36.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 224       | 85.82%  |
| No        | 37        | 14.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 213       | 81.3%   |
| No        | 49        | 18.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 62.84%  |
| No        | 97        | 37.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 65        | 24.71%  |
| Germany     | 37        | 14.07%  |
| Italy       | 24        | 9.13%   |
| Canada      | 11        | 4.18%   |
| Russia      | 9         | 3.42%   |
| Poland      | 9         | 3.42%   |
| Australia   | 8         | 3.04%   |
| UK          | 6         | 2.28%   |
| Spain       | 6         | 2.28%   |
| Netherlands | 6         | 2.28%   |
| India       | 6         | 2.28%   |
| France      | 6         | 2.28%   |
| Switzerland | 5         | 1.9%    |
| Finland     | 5         | 1.9%    |
| Brazil      | 5         | 1.9%    |
| New Zealand | 4         | 1.52%   |
| Sweden      | 3         | 1.14%   |
| Romania     | 3         | 1.14%   |
| Belgium     | 3         | 1.14%   |
| Venezuela   | 2         | 0.76%   |
| Turkey      | 2         | 0.76%   |
| Serbia      | 2         | 0.76%   |
| Mexico      | 2         | 0.76%   |
| Indonesia   | 2         | 0.76%   |
| Hungary     | 2         | 0.76%   |
| Greece      | 2         | 0.76%   |
| Egypt       | 2         | 0.76%   |
| Colombia    | 2         | 0.76%   |
| Bulgaria    | 2         | 0.76%   |
| Bangladesh  | 2         | 0.76%   |
| Austria     | 2         | 0.76%   |
| Argentina   | 2         | 0.76%   |
| Vietnam     | 1         | 0.38%   |
| Uruguay     | 1         | 0.38%   |
| Tunisia     | 1         | 0.38%   |
| Slovakia    | 1         | 0.38%   |
| Singapore   | 1         | 0.38%   |
| Peru        | 1         | 0.38%   |
| Norway      | 1         | 0.38%   |
| Malaysia    | 1         | 0.38%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| St Petersburg  | 4         | 1.48%   |
| Berlin         | 4         | 1.48%   |
| Rome           | 3         | 1.11%   |
| Moscow         | 3         | 1.11%   |
| Milan          | 3         | 1.11%   |
| Melbourne      | 3         | 1.11%   |
| Cambridge      | 3         | 1.11%   |
| Amsterdam      | 3         | 1.11%   |
| Warsaw         | 2         | 0.74%   |
| Walled Lake    | 2         | 0.74%   |
| Vienna         | 2         | 0.74%   |
| Vasco da Gama  | 2         | 0.74%   |
| Sydney         | 2         | 0.74%   |
| Portland       | 2         | 0.74%   |
| Orange         | 2         | 0.74%   |
| New York       | 2         | 0.74%   |
| Montreal       | 2         | 0.74%   |
| Mesquite       | 2         | 0.74%   |
| Krakow         | 2         | 0.74%   |
| Istanbul       | 2         | 0.74%   |
| Houston        | 2         | 0.74%   |
| Helsinki       | 2         | 0.74%   |
| Florence       | 2         | 0.74%   |
| Ettingen       | 2         | 0.74%   |
| Doesburg       | 2         | 0.74%   |
| Dhaka          | 2         | 0.74%   |
| Catania        | 2         | 0.74%   |
| Casale Litta   | 2         | 0.74%   |
| Canberra       | 2         | 0.74%   |
| Cairo          | 2         | 0.74%   |
| Buffalo        | 2         | 0.74%   |
| Budapest       | 2         | 0.74%   |
| Zurich         | 1         | 0.37%   |
| Zeven          | 1         | 0.37%   |
| Yekaterinburg  | 1         | 0.37%   |
| Wilde          | 1         | 0.37%   |
| Wermelskirchen | 1         | 0.37%   |
| Waycross       | 1         | 0.37%   |
| Volos          | 1         | 0.37%   |
| Voghera        | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 65        | 94     | 16.17%  |
| Seagate             | 50        | 66     | 12.44%  |
| WDC                 | 48        | 56     | 11.94%  |
| Kingston            | 32        | 35     | 7.96%   |
| Crucial             | 22        | 37     | 5.47%   |
| Unknown             | 18        | 22     | 4.48%   |
| Toshiba             | 18        | 19     | 4.48%   |
| SK hynix            | 14        | 15     | 3.48%   |
| SanDisk             | 14        | 16     | 3.48%   |
| Hitachi             | 12        | 14     | 2.99%   |
| Apple               | 9         | 13     | 2.24%   |
| Intel               | 8         | 10     | 1.99%   |
| China               | 7         | 8      | 1.74%   |
| PNY                 | 6         | 7      | 1.49%   |
| Transcend           | 5         | 5      | 1.24%   |
| SPCC                | 5         | 5      | 1.24%   |
| Netac               | 4         | 4      | 1%      |
| Micron Technology   | 4         | 4      | 1%      |
| LITEON              | 4         | 4      | 1%      |
| KIOXIA              | 4         | 6      | 1%      |
| HGST                | 4         | 4      | 1%      |
| Corsair             | 4         | 4      | 1%      |
| Phison              | 3         | 4      | 0.75%   |
| Dogfish             | 3         | 3      | 0.75%   |
| Apacer              | 3         | 3      | 0.75%   |
| Team                | 2         | 2      | 0.5%    |
| Silicon Motion      | 2         | 2      | 0.5%    |
| OCZ                 | 2         | 2      | 0.5%    |
| GOODRAM             | 2         | 2      | 0.5%    |
| External            | 2         | 2      | 0.5%    |
| A-DATA Technology   | 2         | 2      | 0.5%    |
| Unknown             | 2         | 2      | 0.5%    |
| USB                 | 1         | 1      | 0.25%   |
| SWORDBILL           | 1         | 2      | 0.25%   |
| SABRENT             | 1         | 1      | 0.25%   |
| RENICE              | 1         | 1      | 0.25%   |
| Phison Electronics  | 1         | 1      | 0.25%   |
| Patriot             | 1         | 1      | 0.25%   |
| Mushkin             | 1         | 1      | 0.25%   |
| MMY                 | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD        | 8         | 1.81%   |
| Samsung SSD 860 EVO 500GB              | 6         | 1.35%   |
| Samsung SSD 980 PRO 1TB                | 5         | 1.13%   |
| Samsung SSD 850 EVO 250GB              | 5         | 1.13%   |
| Seagate ST500LM021-1KJ152 500GB        | 4         | 0.9%    |
| Samsung SSD 970 EVO Plus 1TB           | 4         | 0.9%    |
| Kingston SA400S37240G 240GB SSD        | 4         | 0.9%    |
| Kingston SA400S37120G 120GB SSD        | 4         | 0.9%    |
| Crucial CT480BX500SSD1 480GB           | 4         | 0.9%    |
| Crucial CT120BX500SSD1 120GB           | 4         | 0.9%    |
| Unknown SD32G  32GB                    | 3         | 0.68%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB         | 3         | 0.68%   |
| Seagate ST2000DM001-1ER164 2TB         | 3         | 0.68%   |
| SanDisk SDSSDA240G 240GB               | 3         | 0.68%   |
| Samsung SSD 870 EVO 500GB              | 3         | 0.68%   |
| Samsung SSD 840 Series 120GB           | 3         | 0.68%   |
| Kingston SV300S37A240G 240GB SSD       | 3         | 0.68%   |
| Crucial CT500MX500SSD1 500GB           | 3         | 0.68%   |
| Crucial CT240BX500SSD1 240GB           | 3         | 0.68%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.45%   |
| WDC WDS100T1X0E-00AFY0 1TB             | 2         | 0.45%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 0.45%   |
| Unknown SD/MMC/MS PRO 64GB             | 2         | 0.45%   |
| Unknown SD/MMC 2GB                     | 2         | 0.45%   |
| Unknown M.S./M.S.Pro/HG 16GB           | 2         | 0.45%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.45%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 2         | 0.45%   |
| Toshiba HDWD110 1TB                    | 2         | 0.45%   |
| Toshiba DT01ACA100 1TB                 | 2         | 0.45%   |
| SPCC Solid State Disk 256GB            | 2         | 0.45%   |
| SPCC Solid State Disk 1TB              | 2         | 0.45%   |
| SK hynix HFS128G39TND-N210A 128GB SSD  | 2         | 0.45%   |
| SK hynix HFM512GDJTNI-82A0A 512GB      | 2         | 0.45%   |
| Seagate ST500LT012-9WS142 500GB        | 2         | 0.45%   |
| Seagate ST3500413AS 500GB              | 2         | 0.45%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 0.45%   |
| Seagate ST1000LM035-1RK172 1TB         | 2         | 0.45%   |
| Samsung SSD 980 1TB                    | 2         | 0.45%   |
| Samsung SSD 970 PRO 512GB              | 2         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 66     | 40.65%  |
| WDC                 | 33        | 40     | 26.83%  |
| Toshiba             | 12        | 13     | 9.76%   |
| Hitachi             | 12        | 14     | 9.76%   |
| Samsung Electronics | 4         | 4      | 3.25%   |
| HGST                | 4         | 4      | 3.25%   |
| Unknown             | 2         | 2      | 1.63%   |
| SABRENT             | 1         | 1      | 0.81%   |
| Maxtor              | 1         | 1      | 0.81%   |
| Fujitsu             | 1         | 1      | 0.81%   |
| External            | 1         | 1      | 0.81%   |
| ASMT                | 1         | 1      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 49     | 23.49%  |
| Kingston            | 23        | 25     | 13.86%  |
| Crucial             | 19        | 32     | 11.45%  |
| SanDisk             | 12        | 14     | 7.23%   |
| China               | 7         | 8      | 4.22%   |
| Apple               | 6         | 9      | 3.61%   |
| Transcend           | 5         | 5      | 3.01%   |
| SPCC                | 5         | 5      | 3.01%   |
| PNY                 | 5         | 5      | 3.01%   |
| Netac               | 4         | 4      | 2.41%   |
| WDC                 | 3         | 3      | 1.81%   |
| SK hynix            | 3         | 3      | 1.81%   |
| LITEON              | 3         | 3      | 1.81%   |
| Dogfish             | 3         | 3      | 1.81%   |
| Toshiba             | 2         | 2      | 1.2%    |
| OCZ                 | 2         | 2      | 1.2%    |
| GOODRAM             | 2         | 2      | 1.2%    |
| Apacer              | 2         | 2      | 1.2%    |
| A-DATA Technology   | 2         | 2      | 1.2%    |
| Team                | 1         | 1      | 0.6%    |
| SWORDBILL           | 1         | 2      | 0.6%    |
| RENICE              | 1         | 1      | 0.6%    |
| Patriot             | 1         | 1      | 0.6%    |
| Mushkin             | 1         | 1      | 0.6%    |
| MMY                 | 1         | 1      | 0.6%    |
| Micron Technology   | 1         | 1      | 0.6%    |
| Intel               | 1         | 1      | 0.6%    |
| Indilinx            | 1         | 1      | 0.6%    |
| Hewlett-Packard     | 1         | 1      | 0.6%    |
| Gigabyte Technology | 1         | 1      | 0.6%    |
| GeIL                | 1         | 1      | 0.6%    |
| CT500MX5            | 1         | 1      | 0.6%    |
| CT1000P3            | 1         | 1      | 0.6%    |
| CT1000MX            | 1         | 1      | 0.6%    |
| Corsair             | 1         | 1      | 0.6%    |
| Avant               | 1         | 1      | 0.6%    |
| Acer                | 1         | 1      | 0.6%    |
| Unknown             | 1         | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 140       | 198    | 38.36%  |
| HDD     | 110       | 149    | 30.14%  |
| NVMe    | 95        | 123    | 26.03%  |
| MMC     | 16        | 19     | 4.38%   |
| Unknown | 4         | 6      | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 191       | 332    | 60.63%  |
| NVMe | 94        | 122    | 29.84%  |
| MMC  | 16        | 19     | 5.08%   |
| SAS  | 14        | 22     | 4.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 158       | 222    | 63.2%   |
| 0.51-1.0   | 62        | 82     | 24.8%   |
| 1.01-2.0   | 19        | 25     | 7.6%    |
| 3.01-4.0   | 4         | 4      | 1.6%    |
| 2.01-3.0   | 3         | 3      | 1.2%    |
| 4.01-10.0  | 3         | 10     | 1.2%    |
| 10.01-20.0 | 1         | 1      | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 74        | 27.61%  |
| 251-500        | 57        | 21.27%  |
| 501-1000       | 35        | 13.06%  |
| 21-50          | 23        | 8.58%   |
| 51-100         | 23        | 8.58%   |
| 1001-2000      | 21        | 7.84%   |
| 1-20           | 15        | 5.6%    |
| More than 3000 | 11        | 4.1%    |
| 2001-3000      | 9         | 3.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 101       | 36.86%  |
| 21-50          | 49        | 17.88%  |
| 101-250        | 38        | 13.87%  |
| 51-100         | 35        | 12.77%  |
| 251-500        | 19        | 6.93%   |
| 501-1000       | 13        | 4.74%   |
| 1001-2000      | 12        | 4.38%   |
| More than 3000 | 4         | 1.46%   |
| 2001-3000      | 3         | 1.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB              | 2         | 2      | 4.08%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1      | 2.04%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 2.04%   |
| WDC WD5000AAKS-40V6A0 500GB                  | 1         | 1      | 2.04%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 2.04%   |
| WDC WD3200AAKS-00UU3A0 320GB                 | 1         | 1      | 2.04%   |
| WDC WD2500AAJS-00B4A0 250GB                  | 1         | 1      | 2.04%   |
| WDC WD10EADS-98M2B0 1TB                      | 1         | 1      | 2.04%   |
| WDC WD10EADS-00M2B0 1TB                      | 1         | 1      | 2.04%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD         | 1         | 1      | 2.04%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 2.04%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD        | 1         | 1      | 2.04%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 2.04%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 2.04%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 2.04%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 2.04%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 2.04%   |
| Seagate ST380815AS 80GB                      | 1         | 1      | 2.04%   |
| Seagate ST3500413AS 500GB                    | 1         | 1      | 2.04%   |
| Seagate ST3360320AS 360GB                    | 1         | 1      | 2.04%   |
| Seagate ST320LT020-9YG142 320GB              | 1         | 1      | 2.04%   |
| Seagate ST320LT012-1DG14C 320GB              | 1         | 2      | 2.04%   |
| Seagate ST320LT007-9ZV142 320GB              | 1         | 1      | 2.04%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 2.04%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 2.04%   |
| Seagate ST1000VM002-1CT162 1TB               | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 850 EVO 500GB        | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 2      | 2.04%   |
| Samsung Electronics SSD 840 Series 120GB     | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 1      | 2.04%   |
| RENICE X2 64GB SSD                           | 1         | 1      | 2.04%   |
| Maxtor 4K040H2 40GB                          | 1         | 1      | 2.04%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 1      | 2.04%   |
| Intel SSDPEKKF512G8L 512GB                   | 1         | 2      | 2.04%   |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 1      | 2.04%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 2.04%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 2.04%   |
| Hitachi HTS543216L9SA00 160GB                | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 17     | 33.33%  |
| WDC                 | 8         | 8      | 16.67%  |
| Samsung Electronics | 6         | 7      | 12.5%   |
| Hitachi             | 4         | 5      | 8.33%   |
| HGST                | 3         | 3      | 6.25%   |
| Toshiba             | 2         | 2      | 4.17%   |
| SK hynix            | 1         | 1      | 2.08%   |
| RENICE              | 1         | 1      | 2.08%   |
| Maxtor              | 1         | 1      | 2.08%   |
| Kingston            | 1         | 1      | 2.08%   |
| Intel               | 1         | 2      | 2.08%   |
| Indilinx            | 1         | 1      | 2.08%   |
| GOODRAM             | 1         | 1      | 2.08%   |
| Crucial             | 1         | 4      | 2.08%   |
| China               | 1         | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 17     | 50%     |
| WDC     | 7         | 7      | 21.88%  |
| Hitachi | 4         | 5      | 12.5%   |
| HGST    | 3         | 3      | 9.38%   |
| Toshiba | 1         | 1      | 3.13%   |
| Maxtor  | 1         | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 34     | 65.96%  |
| SSD  | 15        | 19     | 31.91%  |
| NVMe | 1         | 2      | 2.13%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 224       | 393    | 72.96%  |
| Malfunc  | 47        | 55     | 15.31%  |
| Detected | 36        | 47     | 11.73%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 177       | 53.15%  |
| AMD                          | 40        | 12.01%  |
| Samsung Electronics          | 34        | 10.21%  |
| SanDisk                      | 13        | 3.9%    |
| SK hynix                     | 10        | 3%      |
| Phison Electronics           | 10        | 3%      |
| Kingston Technology Company  | 9         | 2.7%    |
| KIOXIA                       | 6         | 1.8%    |
| ASMedia Technology           | 6         | 1.8%    |
| Nvidia                       | 5         | 1.5%    |
| Micron/Crucial Technology    | 5         | 1.5%    |
| Micron Technology            | 3         | 0.9%    |
| Toshiba America Info Systems | 2         | 0.6%    |
| Silicon Motion               | 2         | 0.6%    |
| Marvell Technology Group     | 2         | 0.6%    |
| Broadcom / LSI               | 2         | 0.6%    |
| Apple                        | 2         | 0.6%    |
| VIA Technologies             | 1         | 0.3%    |
| ULi Electronics              | 1         | 0.3%    |
| Silicon Image                | 1         | 0.3%    |
| LSI Logic / Symbios Logic    | 1         | 0.3%    |
| Lite-On Technology           | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 23        | 6.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 5.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 4.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 3.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 2.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 2.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 2.14%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 1.6%    |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 1.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.6%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 6         | 1.6%    |
| AMD 500 Series Chipset SATA Controller                                         | 6         | 1.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.34%   |
| Phison E12 NVMe Controller                                                     | 5         | 1.34%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 5         | 1.34%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 1.34%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 1.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.34%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.34%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 1.07%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.07%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 1.07%   |
| SK hynix BC511                                                                 | 3         | 0.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 0.8%    |
| SanDisk NVMe Controller                                                        | 3         | 0.8%    |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 0.8%    |
| Micron NVMe Storage Controller                                                 | 3         | 0.8%    |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 0.8%    |
| Kingston Company OM3PDP3 NVMe SSD                                              | 3         | 0.8%    |
| Intel Non-Volatile memory controller                                           | 3         | 0.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 195       | 58.21%  |
| NVMe | 93        | 27.76%  |
| IDE  | 32        | 9.55%   |
| RAID | 13        | 3.88%   |
| SCSI | 2         | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 206       | 78.93%  |
| AMD    | 55        | 21.07%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 2.3%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.92%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 4         | 1.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.15%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.15%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 1.15%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 3         | 1.15%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 1.15%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 1.15%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.15%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.15%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.15%   |
| Intel Core i7-8700B CPU @ 3.20GHz             | 2         | 0.77%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 0.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.77%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 2         | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.77%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 2         | 0.77%   |
| Intel Core i5-3350P CPU @ 3.10GHz             | 2         | 0.77%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.77%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.77%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.77%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.77%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.77%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 0.77%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 0.77%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 0.77%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.77%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 0.77%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 0.77%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 0.77%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 2         | 0.77%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.77%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 0.77%   |
| AMD Athlon II X4 630 Processor                | 2         | 0.77%   |
| Intel Xeon W-2123 CPU @ 3.60GHz               | 1         | 0.38%   |
| Intel Xeon CPU X5675 @ 3.07GHz                | 1         | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 48        | 18.39%  |
| Intel Core i5           | 48        | 18.39%  |
| Intel Core i3           | 28        | 10.73%  |
| Other                   | 25        | 9.58%   |
| Intel Celeron           | 17        | 6.51%   |
| AMD Ryzen 7             | 15        | 5.75%   |
| AMD Ryzen 5             | 15        | 5.75%   |
| Intel Core 2 Duo        | 13        | 4.98%   |
| Intel Atom              | 6         | 2.3%    |
| Intel Xeon              | 5         | 1.92%   |
| AMD Ryzen 3             | 4         | 1.53%   |
| Intel Pentium Dual-Core | 3         | 1.15%   |
| Intel Pentium           | 3         | 1.15%   |
| AMD Ryzen 9             | 3         | 1.15%   |
| AMD Athlon II X4        | 3         | 1.15%   |
| Intel Pentium Silver    | 2         | 0.77%   |
| Intel Pentium M         | 2         | 0.77%   |
| Intel Core i9           | 2         | 0.77%   |
| AMD Phenom              | 2         | 0.77%   |
| Intel Pentium Dual      | 1         | 0.38%   |
| Intel Pentium 4         | 1         | 0.38%   |
| Intel Genuine           | 1         | 0.38%   |
| Intel Core M            | 1         | 0.38%   |
| Intel Core 2            | 1         | 0.38%   |
| AMD Turion 64 X2 Mobile | 1         | 0.38%   |
| AMD Sempron             | 1         | 0.38%   |
| AMD Ryzen Threadripper  | 1         | 0.38%   |
| AMD Ryzen 5 PRO         | 1         | 0.38%   |
| AMD Phenom II X4        | 1         | 0.38%   |
| AMD E2                  | 1         | 0.38%   |
| AMD E1                  | 1         | 0.38%   |
| AMD E                   | 1         | 0.38%   |
| AMD Athlon              | 1         | 0.38%   |
| AMD A8                  | 1         | 0.38%   |
| AMD A6                  | 1         | 0.38%   |
| AMD A10                 | 1         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 100       | 38.31%  |
| 4      | 93        | 35.63%  |
| 6      | 27        | 10.34%  |
| 8      | 23        | 8.81%   |
| 12     | 6         | 2.3%    |
| 1      | 6         | 2.3%    |
| 14     | 3         | 1.15%   |
| 10     | 3         | 1.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 258       | 98.85%  |
| 2      | 3         | 1.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 173       | 66.28%  |
| 1      | 88        | 33.72%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 257       | 98.47%  |
| 32-bit         | 4         | 1.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 9.81%   |
| 0x306a9    | 19        | 7.17%   |
| 0x206a7    | 19        | 7.17%   |
| 0x806c1    | 11        | 4.15%   |
| 0x306c3    | 10        | 3.77%   |
| 0x506e3    | 9         | 3.4%    |
| 0x1067a    | 9         | 3.4%    |
| 0x406e3    | 8         | 3.02%   |
| 0x0a50000c | 8         | 3.02%   |
| 0x906ea    | 7         | 2.64%   |
| 0x20655    | 7         | 2.64%   |
| 0x806ec    | 5         | 1.89%   |
| 0x806ea    | 5         | 1.89%   |
| 0x706a8    | 5         | 1.89%   |
| 0xa0652    | 4         | 1.51%   |
| 0x906ed    | 4         | 1.51%   |
| 0x906a3    | 4         | 1.51%   |
| 0x806e9    | 4         | 1.51%   |
| 0x6fd      | 4         | 1.51%   |
| 0x306d4    | 4         | 1.51%   |
| 0x30678    | 4         | 1.51%   |
| 0x08608103 | 4         | 1.51%   |
| 0x08108109 | 4         | 1.51%   |
| 0x706a1    | 3         | 1.13%   |
| 0x406c4    | 3         | 1.13%   |
| 0x40651    | 3         | 1.13%   |
| 0x106e5    | 3         | 1.13%   |
| 0x08701021 | 3         | 1.13%   |
| 0x08600106 | 3         | 1.13%   |
| 0x0800820d | 3         | 1.13%   |
| 0x010000db | 3         | 1.13%   |
| 0xa0671    | 2         | 0.75%   |
| 0xa0653    | 2         | 0.75%   |
| 0x906e9    | 2         | 0.75%   |
| 0x906c0    | 2         | 0.75%   |
| 0x906a4    | 2         | 0.75%   |
| 0x806d1    | 2         | 0.75%   |
| 0x506c9    | 2         | 0.75%   |
| 0x306f2    | 2         | 0.75%   |
| 0x10676    | 2         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 11.45%  |
| SandyBridge      | 20        | 7.63%   |
| IvyBridge        | 20        | 7.63%   |
| Skylake          | 19        | 7.25%   |
| Haswell          | 19        | 7.25%   |
| Zen 3            | 15        | 5.73%   |
| TigerLake        | 12        | 4.58%   |
| Penryn           | 12        | 4.58%   |
| Zen+             | 10        | 3.82%   |
| Westmere         | 10        | 3.82%   |
| Unknown          | 10        | 3.82%   |
| Silvermont       | 8         | 3.05%   |
| Goldmont plus    | 8         | 3.05%   |
| Zen 2            | 7         | 2.67%   |
| CometLake        | 7         | 2.67%   |
| K10              | 6         | 2.29%   |
| IceLake          | 6         | 2.29%   |
| Core             | 6         | 2.29%   |
| Nehalem          | 5         | 1.91%   |
| Broadwell        | 5         | 1.91%   |
| Alderlake Hybrid | 4         | 1.53%   |
| Zen              | 3         | 1.15%   |
| P6               | 3         | 1.15%   |
| Goldmont         | 3         | 1.15%   |
| Tremont          | 2         | 0.76%   |
| Puma             | 2         | 0.76%   |
| K8 Hammer        | 2         | 0.76%   |
| Excavator        | 2         | 0.76%   |
| Bonnell          | 2         | 0.76%   |
| Piledriver       | 1         | 0.38%   |
| NetBurst         | 1         | 0.38%   |
| K8 & K10 hybrid  | 1         | 0.38%   |
| Bobcat           | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 167       | 53.7%   |
| Nvidia                     | 76        | 24.44%  |
| AMD                        | 67        | 21.54%  |
| Matrox Electronics Systems | 1         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 5.31%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 4.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 3.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 2.81%   |
| Intel HD Graphics 530                                                                    | 7         | 2.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.88%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.56%   |
| AMD Lucienne                                                                             | 5         | 1.56%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.25%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.25%   |
| Intel HD Graphics 620                                                                    | 4         | 1.25%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.25%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.25%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.94%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3         | 0.94%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.94%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.94%   |
| Intel HD Graphics 500                                                                    | 3         | 0.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.94%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 0.94%   |
| AMD Renoir                                                                               | 3         | 0.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 0.94%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 2         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.63%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 121       | 46.36%  |
| 1 x AMD        | 51        | 19.54%  |
| 1 x Nvidia     | 42        | 16.09%  |
| Intel + Nvidia | 29        | 11.11%  |
| Intel + AMD    | 9         | 3.45%   |
| AMD + Nvidia   | 4         | 1.53%   |
| 2 x AMD        | 3         | 1.15%   |
| 2 x Intel      | 1         | 0.38%   |
| 1 x Matrox     | 1         | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 216       | 81.2%   |
| Proprietary | 36        | 13.53%  |
| Unknown     | 14        | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 170       | 64.15%  |
| 0.01-0.5   | 25        | 9.43%   |
| 1.01-2.0   | 18        | 6.79%   |
| 3.01-4.0   | 17        | 6.42%   |
| 0.51-1.0   | 17        | 6.42%   |
| 7.01-8.0   | 13        | 4.91%   |
| 8.01-16.0  | 3         | 1.13%   |
| 2.01-3.0   | 2         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 34        | 12.01%  |
| Chimei Innolux          | 33        | 11.66%  |
| AU Optronics            | 31        | 10.95%  |
| LG Display              | 19        | 6.71%   |
| BOE                     | 17        | 6.01%   |
| Hewlett-Packard         | 15        | 5.3%    |
| Dell                    | 15        | 5.3%    |
| Apple                   | 10        | 3.53%   |
| Lenovo                  | 9         | 3.18%   |
| Goldstar                | 9         | 3.18%   |
| Sony                    | 8         | 2.83%   |
| Chi Mei Optoelectronics | 7         | 2.47%   |
| Acer                    | 7         | 2.47%   |
| PANDA                   | 6         | 2.12%   |
| Ancor Communications    | 6         | 2.12%   |
| AOC                     | 5         | 1.77%   |
| Sharp                   | 4         | 1.41%   |
| Philips                 | 4         | 1.41%   |
| Fujitsu Siemens         | 4         | 1.41%   |
| Eizo                    | 4         | 1.41%   |
| Iiyama                  | 3         | 1.06%   |
| BenQ                    | 3         | 1.06%   |
| Panasonic               | 2         | 0.71%   |
| NEC Computers           | 2         | 0.71%   |
| MiTAC                   | 2         | 0.71%   |
| Medion                  | 2         | 0.71%   |
| CPT                     | 2         | 0.71%   |
| Xiaomi                  | 1         | 0.35%   |
| Vizio                   | 1         | 0.35%   |
| Vestel Elektronik       | 1         | 0.35%   |
| Sunplus                 | 1         | 0.35%   |
| STA                     | 1         | 0.35%   |
| SAC                     | 1         | 0.35%   |
| RTK                     | 1         | 0.35%   |
| PRI                     | 1         | 0.35%   |
| Packard Bell            | 1         | 0.35%   |
| ONN                     | 1         | 0.35%   |
| MSI                     | 1         | 0.35%   |
| LTM                     | 1         | 0.35%   |
| LG Philips              | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 1.38%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 1.04%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                       | 2         | 0.69%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch        | 2         | 0.69%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.69%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 0.69%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.69%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 2         | 0.69%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.69%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.69%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.69%   |
| AOC 27B2G5 AOC2702 1920x1080 598x336mm 27.0-inch                         | 2         | 0.69%   |
| Xiaomi Mi TV XMD004A 1360x768 708x398mm 32.0-inch                        | 1         | 0.35%   |
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                       | 1         | 0.35%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 1         | 0.35%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.35%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.35%   |
| Sony TV SNY3001 1920x1080                                                | 1         | 0.35%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                     | 1         | 0.35%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                       | 1         | 0.35%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.35%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.35%   |
| Sony CPD-200SX SNY0570 1920x1080 698x392mm 31.5-inch                     | 1         | 0.35%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP1445 3840x2160 346x194mm 15.6-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.35%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch        | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch     | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0458 1360x768                          | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM03EE 1680x1050                         | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch     | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch      | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 117       | 43.17%  |
| 1366x768 (WXGA)    | 46        | 16.97%  |
| 3840x2160 (4K)     | 22        | 8.12%   |
| 1680x1050 (WSXGA+) | 13        | 4.8%    |
| 2560x1440 (QHD)    | 11        | 4.06%   |
| 1280x1024 (SXGA)   | 11        | 4.06%   |
| 1600x900 (HD+)     | 7         | 2.58%   |
| 1920x1200 (WUXGA)  | 6         | 2.21%   |
| 1280x800 (WXGA)    | 5         | 1.85%   |
| 1440x900 (WXGA+)   | 4         | 1.48%   |
| 2880x1800          | 3         | 1.11%   |
| 2560x1600          | 3         | 1.11%   |
| 2560x1080          | 3         | 1.11%   |
| 2160x1440          | 3         | 1.11%   |
| 1360x768           | 3         | 1.11%   |
| 3440x1440          | 2         | 0.74%   |
| 1280x720 (HD)      | 2         | 0.74%   |
| 1024x768 (XGA)     | 2         | 0.74%   |
| Unknown            | 2         | 0.74%   |
| 3840x2400          | 1         | 0.37%   |
| 3840x1080          | 1         | 0.37%   |
| 2736x1824          | 1         | 0.37%   |
| 2256x1504          | 1         | 0.37%   |
| 1400x1050          | 1         | 0.37%   |
| 1024x600           | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 77        | 27.5%   |
| 23      | 22        | 7.86%   |
| 13      | 22        | 7.86%   |
| 17      | 20        | 7.14%   |
| 27      | 19        | 6.79%   |
| 24      | 19        | 6.79%   |
| 14      | 15        | 5.36%   |
| 21      | 11        | 3.93%   |
| 31      | 9         | 3.21%   |
| 22      | 9         | 3.21%   |
| 11      | 8         | 2.86%   |
| 19      | 6         | 2.14%   |
| Unknown | 6         | 2.14%   |
| 34      | 5         | 1.79%   |
| 18      | 4         | 1.43%   |
| 84      | 3         | 1.07%   |
| 40      | 3         | 1.07%   |
| 16      | 3         | 1.07%   |
| 12      | 3         | 1.07%   |
| 26      | 2         | 0.71%   |
| 20      | 2         | 0.71%   |
| 10      | 2         | 0.71%   |
| 65      | 1         | 0.36%   |
| 61      | 1         | 0.36%   |
| 54      | 1         | 0.36%   |
| 47      | 1         | 0.36%   |
| 46      | 1         | 0.36%   |
| 43      | 1         | 0.36%   |
| 42      | 1         | 0.36%   |
| 36      | 1         | 0.36%   |
| 32      | 1         | 0.36%   |
| 25      | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 106       | 38.27%  |
| 501-600     | 59        | 21.3%   |
| 401-500     | 26        | 9.39%   |
| 351-400     | 26        | 9.39%   |
| 201-300     | 25        | 9.03%   |
| 601-700     | 9         | 3.25%   |
| 701-800     | 7         | 2.53%   |
| Unknown     | 6         | 2.17%   |
| 1001-1500   | 5         | 1.81%   |
| 801-900     | 3         | 1.08%   |
| 1501-2000   | 3         | 1.08%   |
| 901-1000    | 2         | 0.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 195       | 75.29%  |
| 16/10   | 37        | 14.29%  |
| 5/4     | 11        | 4.25%   |
| 3/2     | 5         | 1.93%   |
| 21/9    | 5         | 1.93%   |
| 4/3     | 4         | 1.54%   |
| Unknown | 2         | 0.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 77        | 27.6%   |
| 201-250        | 50        | 17.92%  |
| 81-90          | 29        | 10.39%  |
| 301-350        | 20        | 7.17%   |
| 121-130        | 17        | 6.09%   |
| 351-500        | 15        | 5.38%   |
| 151-200        | 14        | 5.02%   |
| 251-300        | 9         | 3.23%   |
| 71-80          | 8         | 2.87%   |
| 51-60          | 8         | 2.87%   |
| 501-1000       | 8         | 2.87%   |
| More than 1000 | 6         | 2.15%   |
| Unknown        | 6         | 2.15%   |
| 141-150        | 5         | 1.79%   |
| 61-70          | 2         | 0.72%   |
| 41-50          | 2         | 0.72%   |
| 91-100         | 2         | 0.72%   |
| 111-120        | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 104       | 38.24%  |
| 121-160       | 77        | 28.31%  |
| 101-120       | 54        | 19.85%  |
| 161-240       | 16        | 5.88%   |
| 1-50          | 8         | 2.94%   |
| More than 240 | 7         | 2.57%   |
| Unknown       | 6         | 2.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 207       | 77.82%  |
| 2     | 41        | 15.41%  |
| 0     | 13        | 4.89%   |
| 3     | 5         | 1.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 136       | 32.61%  |
| Intel                             | 131       | 31.41%  |
| Qualcomm Atheros                  | 46        | 11.03%  |
| Broadcom                          | 23        | 5.52%   |
| MediaTek                          | 11        | 2.64%   |
| TP-Link                           | 10        | 2.4%    |
| Broadcom Limited                  | 8         | 1.92%   |
| Ralink Technology                 | 7         | 1.68%   |
| Marvell Technology Group          | 7         | 1.68%   |
| Ralink                            | 5         | 1.2%    |
| Nvidia                            | 4         | 0.96%   |
| Microsoft                         | 3         | 0.72%   |
| AVM                               | 3         | 0.72%   |
| Sierra Wireless                   | 2         | 0.48%   |
| Motorola PCS                      | 2         | 0.48%   |
| Xiaomi                            | 1         | 0.24%   |
| VIA Technologies                  | 1         | 0.24%   |
| Sweex                             | 1         | 0.24%   |
| Samsung Electronics               | 1         | 0.24%   |
| Qualcomm Atheros Communications   | 1         | 0.24%   |
| OPPO Electronics                  | 1         | 0.24%   |
| NetGear                           | 1         | 0.24%   |
| Mercucys                          | 1         | 0.24%   |
| Linksys                           | 1         | 0.24%   |
| Lenovo                            | 1         | 0.24%   |
| JMicron Technology                | 1         | 0.24%   |
| Ericsson Business Mobile Networks | 1         | 0.24%   |
| Edimax Technology                 | 1         | 0.24%   |
| Dell                              | 1         | 0.24%   |
| D-Link                            | 1         | 0.24%   |
| ASUSTek Computer                  | 1         | 0.24%   |
| ASIX Electronics                  | 1         | 0.24%   |
| Aquantia                          | 1         | 0.24%   |
| Apple                             | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 92        | 18.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 2.68%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 2.06%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 2.06%   |
| Intel Wireless 8260                                               | 9         | 1.86%   |
| Intel Ethernet Controller I225-V                                  | 8         | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 1.24%   |
| Intel Wireless 3165                                               | 6         | 1.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.24%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 5         | 1.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.03%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.03%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.82%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.82%   |
| Intel Wireless 7265                                               | 4         | 0.82%   |
| Intel Wireless 7260                                               | 4         | 0.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.82%   |
| Intel I211 Gigabit Network Connection                             | 4         | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 0.82%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 4         | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.62%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 0.62%   |
| Intel Wireless 3160                                               | 3         | 0.62%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 3         | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.62%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 101       | 42.62%  |
| Realtek Semiconductor           | 38        | 16.03%  |
| Qualcomm Atheros                | 30        | 12.66%  |
| Broadcom                        | 15        | 6.33%   |
| MediaTek                        | 11        | 4.64%   |
| TP-Link                         | 9         | 3.8%    |
| Ralink Technology               | 7         | 2.95%   |
| Broadcom Limited                | 6         | 2.53%   |
| Ralink                          | 5         | 2.11%   |
| AVM                             | 3         | 1.27%   |
| Sierra Wireless                 | 2         | 0.84%   |
| Sweex                           | 1         | 0.42%   |
| Qualcomm Atheros Communications | 1         | 0.42%   |
| NetGear                         | 1         | 0.42%   |
| Microsoft                       | 1         | 0.42%   |
| Mercucys                        | 1         | 0.42%   |
| Marvell Technology Group        | 1         | 0.42%   |
| Linksys                         | 1         | 0.42%   |
| Edimax Technology               | 1         | 0.42%   |
| D-Link                          | 1         | 0.42%   |
| ASUSTek Computer                | 1         | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 13        | 5.49%   |
| Intel Wi-Fi 6 AX201                                            | 10        | 4.22%   |
| Intel Wireless 8260                                            | 9         | 3.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 2.53%   |
| Intel Wireless 3165                                            | 6         | 2.53%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 5         | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.11%   |
| Intel Wireless 8265 / 8275                                     | 5         | 2.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.69%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.69%   |
| Intel Wireless 7265                                            | 4         | 1.69%   |
| Intel Wireless 7260                                            | 4         | 1.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 1.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 1.69%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 1.27%   |
| Intel Wireless 3160                                            | 3         | 1.27%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.27%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                     | 2         | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.84%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 2         | 0.84%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2         | 0.84%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.84%   |
| Realtek 802.11ac NIC                                           | 2         | 0.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 118       | 50%     |
| Intel                    | 59        | 25%     |
| Qualcomm Atheros         | 20        | 8.47%   |
| Broadcom                 | 14        | 5.93%   |
| Marvell Technology Group | 6         | 2.54%   |
| Nvidia                   | 4         | 1.69%   |
| Microsoft                | 2         | 0.85%   |
| Broadcom Limited         | 2         | 0.85%   |
| Xiaomi                   | 1         | 0.42%   |
| VIA Technologies         | 1         | 0.42%   |
| TP-Link                  | 1         | 0.42%   |
| Samsung Electronics      | 1         | 0.42%   |
| OPPO Electronics         | 1         | 0.42%   |
| Motorola PCS             | 1         | 0.42%   |
| Lenovo                   | 1         | 0.42%   |
| JMicron Technology       | 1         | 0.42%   |
| ASIX Electronics         | 1         | 0.42%   |
| Aquantia                 | 1         | 0.42%   |
| Apple                    | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 92        | 37.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 5.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 4.1%    |
| Intel Ethernet Controller I225-V                                  | 8         | 3.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.05%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 2.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.64%   |
| Intel I211 Gigabit Network Connection                             | 4         | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.23%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 1.23%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 1.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 1.23%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.82%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2         | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.82%   |
| Microsoft RTL8153 GigE [Surface Dock Ethernet]                    | 2         | 0.82%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.82%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.82%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.82%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.82%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.82%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.82%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.82%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.82%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.41%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 223       | 50.68%  |
| WiFi     | 213       | 48.41%  |
| Modem    | 3         | 0.68%   |
| Unknown  | 1         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 171       | 63.81%  |
| Ethernet | 97        | 36.19%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 150       | 57.25%  |
| 1     | 100       | 38.17%  |
| 3     | 7         | 2.67%   |
| 0     | 4         | 1.53%   |
| 4     | 1         | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 188       | 71.48%  |
| Yes  | 75        | 28.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 46.11%  |
| Qualcomm Atheros Communications | 15        | 8.98%   |
| Apple                           | 14        | 8.38%   |
| Realtek Semiconductor           | 12        | 7.19%   |
| Cambridge Silicon Radio         | 10        | 5.99%   |
| Foxconn / Hon Hai               | 9         | 5.39%   |
| Broadcom                        | 8         | 4.79%   |
| Lite-On Technology              | 4         | 2.4%    |
| IMC Networks                    | 4         | 2.4%    |
| MediaTek                        | 3         | 1.8%    |
| ASUSTek Computer                | 3         | 1.8%    |
| Ralink                          | 2         | 1.2%    |
| Hewlett-Packard                 | 2         | 1.2%    |
| TP-Link                         | 1         | 0.6%    |
| Marvell Semiconductor           | 1         | 0.6%    |
| Dell                            | 1         | 0.6%    |
| Alps Electric                   | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 28        | 16.77%  |
| Intel AX201 Bluetooth                                                               | 15        | 8.98%   |
| Intel AX200 Bluetooth                                                               | 13        | 7.78%   |
| Realtek Bluetooth Radio                                                             | 10        | 5.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 5.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 5.99%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 4.79%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 2.99%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.99%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 2.4%    |
| MediaTek Wireless_Device                                                            | 3         | 1.8%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.8%    |
| Intel Bluetooth Device                                                              | 3         | 1.8%    |
| IMC Networks Wireless_Device                                                        | 3         | 1.8%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.2%    |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.2%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.2%    |
| Lite-On Wireless_Device                                                             | 2         | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.2%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.2%    |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.2%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.2%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.2%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 1.2%    |
| Apple Bluetooth HCI                                                                 | 2         | 1.2%    |
| TP-Link UB500 Adapter                                                               | 1         | 0.6%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.6%    |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.6%    |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.6%    |
| Lite-On Bluetooth Radio                                                             | 1         | 0.6%    |
| Intel AX210 Bluetooth                                                               | 1         | 0.6%    |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.6%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.6%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.6%    |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.6%    |
| Broadcom HP Portable Valentine                                                      | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 195       | 52.85%  |
| AMD                        | 65        | 17.62%  |
| Nvidia                     | 61        | 16.53%  |
| C-Media Electronics        | 7         | 1.9%    |
| Creative Labs              | 5         | 1.36%   |
| VIA Technologies           | 3         | 0.81%   |
| Texas Instruments          | 2         | 0.54%   |
| ROCCAT                     | 2         | 0.54%   |
| Realtek Semiconductor      | 2         | 0.54%   |
| Generalplus Technology     | 2         | 0.54%   |
| BEHRINGER International    | 2         | 0.54%   |
| Apple                      | 2         | 0.54%   |
| TerraTec Electronic        | 1         | 0.27%   |
| Shenzhen Riitek Technology | 1         | 0.27%   |
| Setek Elektronik           | 1         | 0.27%   |
| Schiit Audio               | 1         | 0.27%   |
| Razer USA                  | 1         | 0.27%   |
| Plantronics                | 1         | 0.27%   |
| Microsoft                  | 1         | 0.27%   |
| Logitech                   | 1         | 0.27%   |
| LG Electronics             | 1         | 0.27%   |
| Lenovo                     | 1         | 0.27%   |
| JMTek                      | 1         | 0.27%   |
| GYROCOM C&C                | 1         | 0.27%   |
| Guillemot                  | 1         | 0.27%   |
| GN Netcom                  | 1         | 0.27%   |
| Focusrite-Novation         | 1         | 0.27%   |
| FIFINE 683 Microphone      | 1         | 0.27%   |
| Ensoniq                    | 1         | 0.27%   |
| Dell                       | 1         | 0.27%   |
| Creative Technology        | 1         | 0.27%   |
| Conexant Systems           | 1         | 0.27%   |
| CMX Systems                | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 28        | 6.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23        | 5.35%   |
| Intel Sunrise Point-LP HD Audio                                            | 19        | 4.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 19        | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 3.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 2.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 2.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 2.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 2.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 1.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 1.4%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 1.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 1.4%    |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 1.4%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 1.4%    |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.16%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 1.16%   |
| Nvidia Audio device                                                        | 5         | 1.16%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.93%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 0.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 0.93%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.93%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 0.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.7%    |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 0.7%    |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 3         | 0.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 63        | 20.52%  |
| SK hynix            | 53        | 17.26%  |
| Unknown             | 35        | 11.4%   |
| Kingston            | 33        | 10.75%  |
| Micron Technology   | 26        | 8.47%   |
| Crucial             | 19        | 6.19%   |
| Corsair             | 14        | 4.56%   |
| Ramaxel Technology  | 9         | 2.93%   |
| A-DATA Technology   | 9         | 2.93%   |
| G.Skill             | 7         | 2.28%   |
| Elpida              | 7         | 2.28%   |
| Unknown (ABCD)      | 6         | 1.95%   |
| Transcend           | 4         | 1.3%    |
| Nanya Technology    | 4         | 1.3%    |
| Unknown             | 4         | 1.3%    |
| Smart               | 2         | 0.65%   |
| Avant               | 2         | 0.65%   |
| Unknown (AB)        | 1         | 0.33%   |
| Team                | 1         | 0.33%   |
| PNY                 | 1         | 0.33%   |
| Patriot             | 1         | 0.33%   |
| Innodisk            | 1         | 0.33%   |
| Hewlett-Packard     | 1         | 0.33%   |
| Golden Empire       | 1         | 0.33%   |
| ASint Technology    | 1         | 0.33%   |
| Apacer              | 1         | 0.33%   |
| 48spaces            | 1         | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 1.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.53%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.22%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.22%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4         | 1.22%   |
| Unknown                                                          | 4         | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.92%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.92%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 2         | 0.61%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 2         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 2         | 0.61%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.61%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.61%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.61%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.61%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.61%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.61%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.61%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s              | 2         | 0.61%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.61%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.61%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s            | 2         | 0.61%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.61%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 0.61%   |
| Crucial RAM CT16G4SFRA32A.C16FR 16GB SODIMM DDR4 3200MT/s        | 2         | 0.61%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16GB SODIMM DDR4 2667MT/s       | 2         | 0.61%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.61%   |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8GB DIMM DDR4 3600MT/s          | 2         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 116       | 43.61%  |
| DDR3    | 100       | 37.59%  |
| DDR2    | 14        | 5.26%   |
| LPDDR4  | 13        | 4.89%   |
| SDRAM   | 8         | 3.01%   |
| Unknown | 6         | 2.26%   |
| DDR     | 4         | 1.5%    |
| LPDDR3  | 3         | 1.13%   |
| DRAM    | 1         | 0.38%   |
| DDR5    | 1         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 173       | 65.78%  |
| DIMM         | 77        | 29.28%  |
| Row Of Chips | 13        | 4.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 94        | 32.87%  |
| 4096  | 86        | 30.07%  |
| 2048  | 46        | 16.08%  |
| 16384 | 37        | 12.94%  |
| 1024  | 12        | 4.2%    |
| 32768 | 10        | 3.5%    |
| 512   | 1         | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 58        | 20.64%  |
| 3200    | 47        | 16.73%  |
| 2667    | 28        | 9.96%   |
| 1333    | 26        | 9.25%   |
| 2400    | 21        | 7.47%   |
| Unknown | 13        | 4.63%   |
| 2133    | 12        | 4.27%   |
| 1334    | 10        | 3.56%   |
| 667     | 10        | 3.56%   |
| 3600    | 9         | 3.2%    |
| 1067    | 5         | 1.78%   |
| 800     | 5         | 1.78%   |
| 4267    | 3         | 1.07%   |
| 4199    | 3         | 1.07%   |
| 3400    | 3         | 1.07%   |
| 2666    | 3         | 1.07%   |
| 3733    | 2         | 0.71%   |
| 2933    | 2         | 0.71%   |
| 2048    | 2         | 0.71%   |
| 1867    | 2         | 0.71%   |
| 1066    | 2         | 0.71%   |
| 333     | 2         | 0.71%   |
| 8400    | 1         | 0.36%   |
| 4800    | 1         | 0.36%   |
| 4266    | 1         | 0.36%   |
| 3866    | 1         | 0.36%   |
| 3466    | 1         | 0.36%   |
| 3266    | 1         | 0.36%   |
| 3000    | 1         | 0.36%   |
| 2000    | 1         | 0.36%   |
| 1866    | 1         | 0.36%   |
| 1800    | 1         | 0.36%   |
| 1639    | 1         | 0.36%   |
| 533     | 1         | 0.36%   |
| 166     | 1         | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 4         | 44.44%  |
| Brother Industries | 3         | 33.33%  |
| Hewlett-Packard    | 2         | 22.22%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |
| Canon CanoScan LiDE 210       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 36        | 22.78%  |
| Microdia                               | 14        | 8.86%   |
| Realtek Semiconductor                  | 12        | 7.59%   |
| Acer                                   | 12        | 7.59%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 6.33%   |
| IMC Networks                           | 9         | 5.7%    |
| Apple                                  | 8         | 5.06%   |
| Logitech                               | 7         | 4.43%   |
| Sunplus Innovation Technology          | 6         | 3.8%    |
| Quanta                                 | 6         | 3.8%    |
| Lite-On Technology                     | 5         | 3.16%   |
| Suyin                                  | 4         | 2.53%   |
| Ricoh                                  | 4         | 2.53%   |
| Microsoft                              | 3         | 1.9%    |
| Lenovo                                 | 3         | 1.9%    |
| Silicon Motion                         | 2         | 1.27%   |
| Luxvisions Innotech Limited            | 2         | 1.27%   |
| Bison Electronics                      | 2         | 1.27%   |
| Alcor Micro                            | 2         | 1.27%   |
| Z-Star Microelectronics                | 1         | 0.63%   |
| Y Media                                | 1         | 0.63%   |
| Sonix Technology                       | 1         | 0.63%   |
| Primax Electronics                     | 1         | 0.63%   |
| Novatek Microelectronics               | 1         | 0.63%   |
| LG Electronics                         | 1         | 0.63%   |
| Hewlett-Packard                        | 1         | 0.63%   |
| Goodong Industry                       | 1         | 0.63%   |
| Generalplus Technology                 | 1         | 0.63%   |
| GEMBIRD                                | 1         | 0.63%   |
| Arkmicro Technologies                  | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 6         | 3.75%   |
| Microdia Integrated_Webcam_HD                       | 5         | 3.13%   |
| Realtek Integrated_Webcam_HD                        | 4         | 2.5%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.5%    |
| Acer Integrated Camera                              | 4         | 2.5%    |
| Realtek USB Camera                                  | 3         | 1.88%   |
| Quanta HD User Facing                               | 3         | 1.88%   |
| IMC Networks Integrated Camera                      | 3         | 1.88%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.88%   |
| Chicony HD User Facing                              | 3         | 1.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 1.88%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 1.88%   |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 1.88%   |
| Apple Built-in iSight                               | 3         | 1.88%   |
| Acer BisonCam,NB Pro                                | 3         | 1.88%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.25%   |
| Sunplus HD 720P webcam                              | 2         | 1.25%   |
| Ricoh USB2.0 Camera                                 | 2         | 1.25%   |
| Microsoft LifeCam HD-3000                           | 2         | 1.25%   |
| Microdia Webcam Vitade AF                           | 2         | 1.25%   |
| Logitech Webcam C930e                               | 2         | 1.25%   |
| Logitech Webcam C270                                | 2         | 1.25%   |
| Lite-On HP HD Camera                                | 2         | 1.25%   |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 1.25%   |
| Chicony HD WebCam                                   | 2         | 1.25%   |
| Acer HD Webcam                                      | 2         | 1.25%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 0.63%   |
| Y Media USB Camera                                  | 1         | 0.63%   |
| Suyin Sony Visual Communication Camera              | 1         | 0.63%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.63%   |
| Suyin HP Webcam                                     | 1         | 0.63%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.63%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 0.63%   |
| Sunplus ASUS Webcam                                 | 1         | 0.63%   |
| Sonix USB Camera                                    | 1         | 0.63%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.63%   |
| Silicon Motion Web Camera                           | 1         | 0.63%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 0.63%   |
| Ricoh Integrated Webcam                             | 1         | 0.63%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 25%     |
| Synaptics                  | 7         | 25%     |
| Shenzhen Goodix Technology | 6         | 21.43%  |
| AuthenTec                  | 4         | 14.29%  |
| Upek                       | 2         | 7.14%   |
| Microsoft                  | 1         | 3.57%   |
| Elan Microelectronics      | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                      | 5         | 17.86%  |
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 10.71%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 3         | 10.71%  |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 2         | 7.14%   |
| AuthenTec AES2810                                        | 2         | 7.14%   |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 3.57%   |
| Upek TCS5B Fingerprint sensor                            | 1         | 3.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 1         | 3.57%   |
| Synaptics WBDI Fingerprint Reader USB 102                | 1         | 3.57%   |
| Synaptics UWP WBDI Device                                | 1         | 3.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 3.57%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 3.57%   |
| Microsoft Fingerprint Reader                             | 1         | 3.57%   |
| Elan ELAN:Fingerprint                                    | 1         | 3.57%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 3.57%   |
| AuthenTec AES1660 Fingerprint Sensor                     | 1         | 3.57%   |
| Unknown                                                  | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 41.67%  |
| Alcor Micro           | 5         | 41.67%  |
| Advanced Card Systems | 2         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 187       | 69.78%  |
| 1     | 56        | 20.9%   |
| 2     | 21        | 7.84%   |
| 3     | 4         | 1.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 41        | 39.81%  |
| Fingerprint reader       | 28        | 27.18%  |
| Chipcard                 | 10        | 9.71%   |
| Net/wireless             | 5         | 4.85%   |
| Multimedia controller    | 5         | 4.85%   |
| Communication controller | 4         | 3.88%   |
| Unassigned class         | 3         | 2.91%   |
| Net/ethernet             | 2         | 1.94%   |
| Camera                   | 2         | 1.94%   |
| Sound                    | 1         | 0.97%   |
| Dvb card                 | 1         | 0.97%   |
| Bluetooth                | 1         | 0.97%   |

