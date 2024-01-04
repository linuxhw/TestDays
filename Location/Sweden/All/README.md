Linux in Sweden - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Sweden.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Sweden/Desktop/README.md) and [notebooks](/Location/Sweden/Notebook/README.md).

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

Total: 3444

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-db0xxx            | Notebook    | [dc302f3b3e](https://linux-hardware.org/?probe=dc302f3b3e) | Jan 02, 2024 |
| ASUSTek       | P6T                         | Desktop     | [7b5a14566d](https://linux-hardware.org/?probe=7b5a14566d) | Jan 01, 2024 |
| Dell          | Latitude 7490               | Notebook    | [efab03db5f](https://linux-hardware.org/?probe=efab03db5f) | Jan 01, 2024 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [d47bc3897f](https://linux-hardware.org/?probe=d47bc3897f) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | Notebook    | [65fb7df562](https://linux-hardware.org/?probe=65fb7df562) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | Notebook    | [e270ce7266](https://linux-hardware.org/?probe=e270ce7266) | Jan 01, 2024 |
| ASUSTek       | UX550VE                     | Notebook    | [90014cac84](https://linux-hardware.org/?probe=90014cac84) | Dec 31, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [763233abcb](https://linux-hardware.org/?probe=763233abcb) | Dec 30, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [bf4f14e416](https://linux-hardware.org/?probe=bf4f14e416) | Dec 30, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3f7e7324a4](https://linux-hardware.org/?probe=3f7e7324a4) | Dec 29, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [2a7878eaed](https://linux-hardware.org/?probe=2a7878eaed) | Dec 28, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [424a79de6b](https://linux-hardware.org/?probe=424a79de6b) | Dec 28, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [42460d0cd3](https://linux-hardware.org/?probe=42460d0cd3) | Dec 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [61116b6285](https://linux-hardware.org/?probe=61116b6285) | Dec 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [769ba1b68c](https://linux-hardware.org/?probe=769ba1b68c) | Dec 27, 2023 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [68c1102e98](https://linux-hardware.org/?probe=68c1102e98) | Dec 25, 2023 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [f22547b26f](https://linux-hardware.org/?probe=f22547b26f) | Dec 25, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0972c678d9](https://linux-hardware.org/?probe=0972c678d9) | Dec 25, 2023 |
| ASUSTek       | ET2010AG                    | All in one  | [34f80ef918](https://linux-hardware.org/?probe=34f80ef918) | Dec 25, 2023 |
| ASUSTek       | ET2010AG                    | All in one  | [bf542378eb](https://linux-hardware.org/?probe=bf542378eb) | Dec 25, 2023 |
| PC Special... | N150CU                      | Notebook    | [5697f18262](https://linux-hardware.org/?probe=5697f18262) | Dec 24, 2023 |
| Biostar       | A320MH                      | Desktop     | [0898691249](https://linux-hardware.org/?probe=0898691249) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1RS0... | Notebook    | [5c4efd5165](https://linux-hardware.org/?probe=5c4efd5165) | Dec 24, 2023 |
| pine64,pin... | Pinebook Pro                | Soc         | [8e5ebecea9](https://linux-hardware.org/?probe=8e5ebecea9) | Dec 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [6484f4217b](https://linux-hardware.org/?probe=6484f4217b) | Dec 24, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [a7194ce97c](https://linux-hardware.org/?probe=a7194ce97c) | Dec 23, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [18ef14b687](https://linux-hardware.org/?probe=18ef14b687) | Dec 23, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [ff8ded7ff8](https://linux-hardware.org/?probe=ff8ded7ff8) | Dec 22, 2023 |
| HP            | 83E0                        | Desktop     | [07e6f563f9](https://linux-hardware.org/?probe=07e6f563f9) | Dec 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9515cb0c90](https://linux-hardware.org/?probe=9515cb0c90) | Dec 22, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [8bce457975](https://linux-hardware.org/?probe=8bce457975) | Dec 21, 2023 |
| Supermicro    | H13DSG-O-CPU                | Desktop     | [1ba9d3bc0c](https://linux-hardware.org/?probe=1ba9d3bc0c) | Dec 21, 2023 |
| Supermicro    | H13DSG-O-CPU                | Desktop     | [066ebdde5b](https://linux-hardware.org/?probe=066ebdde5b) | Dec 21, 2023 |
| Neousys Te... | NVS-10000 Rev. A2           | Server      | [cde616cde3](https://linux-hardware.org/?probe=cde616cde3) | Dec 21, 2023 |
| MSI           | B85M-G43                    | Desktop     | [f2b41e4ce3](https://linux-hardware.org/?probe=f2b41e4ce3) | Dec 21, 2023 |
| HP            | ProBook 445 14 inch G10 ... | Notebook    | [5b3a77bd87](https://linux-hardware.org/?probe=5b3a77bd87) | Dec 20, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [95ab984d32](https://linux-hardware.org/?probe=95ab984d32) | Dec 19, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [83ef4dd286](https://linux-hardware.org/?probe=83ef4dd286) | Dec 18, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [2e837d2a52](https://linux-hardware.org/?probe=2e837d2a52) | Dec 18, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [0cf5577833](https://linux-hardware.org/?probe=0cf5577833) | Dec 18, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [2bee7533b2](https://linux-hardware.org/?probe=2bee7533b2) | Dec 18, 2023 |
| Lenovo        | ThinkPad X270 20HMS0B60H    | Notebook    | [059545a4ad](https://linux-hardware.org/?probe=059545a4ad) | Dec 17, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [4a6ea199e2](https://linux-hardware.org/?probe=4a6ea199e2) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [b9029b0475](https://linux-hardware.org/?probe=b9029b0475) | Dec 17, 2023 |
| Shenzhen D... | MP80                        | Mini pc     | [adced59500](https://linux-hardware.org/?probe=adced59500) | Dec 17, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [171e1a6bbb](https://linux-hardware.org/?probe=171e1a6bbb) | Dec 17, 2023 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [c95903375b](https://linux-hardware.org/?probe=c95903375b) | Dec 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3324746751](https://linux-hardware.org/?probe=3324746751) | Dec 16, 2023 |
| HP            | 2B05                        | Desktop     | [81e68a1fb8](https://linux-hardware.org/?probe=81e68a1fb8) | Dec 16, 2023 |
| HP            | 2B05                        | Desktop     | [2063743d90](https://linux-hardware.org/?probe=2063743d90) | Dec 16, 2023 |
| PC Special... | N150CU                      | Notebook    | [92a4f7a5a4](https://linux-hardware.org/?probe=92a4f7a5a4) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [984c55c6a2](https://linux-hardware.org/?probe=984c55c6a2) | Dec 16, 2023 |
| PC Special... | N150CU                      | Notebook    | [07686d110e](https://linux-hardware.org/?probe=07686d110e) | Dec 16, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [78ef6792a1](https://linux-hardware.org/?probe=78ef6792a1) | Dec 16, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [92b42d7c3e](https://linux-hardware.org/?probe=92b42d7c3e) | Dec 15, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [059715d1bf](https://linux-hardware.org/?probe=059715d1bf) | Dec 15, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [49278a194a](https://linux-hardware.org/?probe=49278a194a) | Dec 14, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [d4d42016ea](https://linux-hardware.org/?probe=d4d42016ea) | Dec 14, 2023 |
| HP            | Unknown                     | Notebook    | [6a46b87d41](https://linux-hardware.org/?probe=6a46b87d41) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [05c8fb1ded](https://linux-hardware.org/?probe=05c8fb1ded) | Dec 13, 2023 |
| Lenovo        | 1031 SDK0J40697 WIN 3305... | Desktop     | [f04b854d78](https://linux-hardware.org/?probe=f04b854d78) | Dec 13, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [5a796a43bd](https://linux-hardware.org/?probe=5a796a43bd) | Dec 12, 2023 |
| Lenovo        | 3111 SDK0J40700 WIN 3258... | Mini pc     | [52be4d3e15](https://linux-hardware.org/?probe=52be4d3e15) | Dec 12, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [bdfc16eb98](https://linux-hardware.org/?probe=bdfc16eb98) | Dec 11, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [6a4ff9d940](https://linux-hardware.org/?probe=6a4ff9d940) | Dec 11, 2023 |
| Acer          | Extensa 2509                | Notebook    | [ee00581b3a](https://linux-hardware.org/?probe=ee00581b3a) | Dec 11, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [41f57147de](https://linux-hardware.org/?probe=41f57147de) | Dec 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b87d7c1c10](https://linux-hardware.org/?probe=b87d7c1c10) | Dec 10, 2023 |
| Dell          | XPS 9320                    | Notebook    | [91f9b06d7f](https://linux-hardware.org/?probe=91f9b06d7f) | Dec 10, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [bb7ea992e6](https://linux-hardware.org/?probe=bb7ea992e6) | Dec 09, 2023 |
| MSI           | MS-B120                     | Mini pc     | [51a1cc9143](https://linux-hardware.org/?probe=51a1cc9143) | Dec 07, 2023 |
| MSI           | MS-B120                     | Mini pc     | [9c55ae59fe](https://linux-hardware.org/?probe=9c55ae59fe) | Dec 07, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [8446d618a7](https://linux-hardware.org/?probe=8446d618a7) | Dec 06, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [3f2a30851e](https://linux-hardware.org/?probe=3f2a30851e) | Dec 05, 2023 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [8c397afeca](https://linux-hardware.org/?probe=8c397afeca) | Dec 05, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [3792e939db](https://linux-hardware.org/?probe=3792e939db) | Dec 05, 2023 |
| Acer          | Swift SFE16-43              | Notebook    | [e31c4454c6](https://linux-hardware.org/?probe=e31c4454c6) | Dec 04, 2023 |
| HP            | 1998                        | Desktop     | [14cb2b69d2](https://linux-hardware.org/?probe=14cb2b69d2) | Dec 03, 2023 |
| Shenzhen D... | MP80                        | Mini pc     | [af649a6096](https://linux-hardware.org/?probe=af649a6096) | Dec 03, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [90e07856e4](https://linux-hardware.org/?probe=90e07856e4) | Dec 01, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [f9175866ae](https://linux-hardware.org/?probe=f9175866ae) | Nov 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [6357a41a39](https://linux-hardware.org/?probe=6357a41a39) | Nov 30, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [dd49d338b4](https://linux-hardware.org/?probe=dd49d338b4) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FBA... | Convertible | [720eead0a5](https://linux-hardware.org/?probe=720eead0a5) | Nov 29, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9af25bdb99](https://linux-hardware.org/?probe=9af25bdb99) | Nov 28, 2023 |
| HP            | 304Bh                       | Desktop     | [3cb20d232f](https://linux-hardware.org/?probe=3cb20d232f) | Nov 28, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [9530bb80db](https://linux-hardware.org/?probe=9530bb80db) | Nov 28, 2023 |
| ASUSTek       | PN41-S1                     | Mini pc     | [d254031e43](https://linux-hardware.org/?probe=d254031e43) | Nov 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [535c1fe9e0](https://linux-hardware.org/?probe=535c1fe9e0) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3397e49e8a](https://linux-hardware.org/?probe=3397e49e8a) | Nov 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [38e71449be](https://linux-hardware.org/?probe=38e71449be) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [24e86fc568](https://linux-hardware.org/?probe=24e86fc568) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [288151e67d](https://linux-hardware.org/?probe=288151e67d) | Nov 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [2715c8329f](https://linux-hardware.org/?probe=2715c8329f) | Nov 27, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [8139afea1a](https://linux-hardware.org/?probe=8139afea1a) | Nov 26, 2023 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [dc0fce7e4a](https://linux-hardware.org/?probe=dc0fce7e4a) | Nov 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [94927ee986](https://linux-hardware.org/?probe=94927ee986) | Nov 25, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0c52ef42c9](https://linux-hardware.org/?probe=0c52ef42c9) | Nov 24, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [8ff45d7c99](https://linux-hardware.org/?probe=8ff45d7c99) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8cb9c3b0a7](https://linux-hardware.org/?probe=8cb9c3b0a7) | Nov 24, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7aa3c32e86](https://linux-hardware.org/?probe=7aa3c32e86) | Nov 24, 2023 |
| HP            | Presario CQ61               | Notebook    | [5c7a775c76](https://linux-hardware.org/?probe=5c7a775c76) | Nov 24, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [4a18f0945f](https://linux-hardware.org/?probe=4a18f0945f) | Nov 23, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [6bc9169e34](https://linux-hardware.org/?probe=6bc9169e34) | Nov 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [0ea9603f31](https://linux-hardware.org/?probe=0ea9603f31) | Nov 23, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b6e4999e4f](https://linux-hardware.org/?probe=b6e4999e4f) | Nov 22, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [bc7df67b84](https://linux-hardware.org/?probe=bc7df67b84) | Nov 22, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [8ea017cbfe](https://linux-hardware.org/?probe=8ea017cbfe) | Nov 21, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [b95977fce2](https://linux-hardware.org/?probe=b95977fce2) | Nov 20, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [72b1a867da](https://linux-hardware.org/?probe=72b1a867da) | Nov 20, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [03c5ac12be](https://linux-hardware.org/?probe=03c5ac12be) | Nov 20, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [e0d3e7cba3](https://linux-hardware.org/?probe=e0d3e7cba3) | Nov 19, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [88e978f447](https://linux-hardware.org/?probe=88e978f447) | Nov 18, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [4230260e34](https://linux-hardware.org/?probe=4230260e34) | Nov 18, 2023 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [e9e9d46316](https://linux-hardware.org/?probe=e9e9d46316) | Nov 17, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [63c8984ac3](https://linux-hardware.org/?probe=63c8984ac3) | Nov 16, 2023 |
| Lenovo        | 1064 SDK0T76530 WIN 3556... | Desktop     | [0c6d21ae8f](https://linux-hardware.org/?probe=0c6d21ae8f) | Nov 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [e42bab7bfa](https://linux-hardware.org/?probe=e42bab7bfa) | Nov 15, 2023 |
| Lenovo        | 1064 SDK0T76530 WIN 3556... | Desktop     | [58692dde45](https://linux-hardware.org/?probe=58692dde45) | Nov 15, 2023 |
| System76      | Adder WS                    | Notebook    | [7135955eda](https://linux-hardware.org/?probe=7135955eda) | Nov 13, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [5ef7be7906](https://linux-hardware.org/?probe=5ef7be7906) | Nov 12, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [bee917829a](https://linux-hardware.org/?probe=bee917829a) | Nov 12, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [503d3690b0](https://linux-hardware.org/?probe=503d3690b0) | Nov 11, 2023 |
| ASUSTek       | TS10                        | Desktop     | [c35ca1dadb](https://linux-hardware.org/?probe=c35ca1dadb) | Nov 11, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [36d24b7c8b](https://linux-hardware.org/?probe=36d24b7c8b) | Nov 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [040bcdd741](https://linux-hardware.org/?probe=040bcdd741) | Nov 10, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [cb1e3547f7](https://linux-hardware.org/?probe=cb1e3547f7) | Nov 10, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [d9873e127d](https://linux-hardware.org/?probe=d9873e127d) | Nov 10, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [224a0992ae](https://linux-hardware.org/?probe=224a0992ae) | Nov 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [9a3d616dad](https://linux-hardware.org/?probe=9a3d616dad) | Nov 08, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [de38771bec](https://linux-hardware.org/?probe=de38771bec) | Nov 08, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [c035e0367f](https://linux-hardware.org/?probe=c035e0367f) | Nov 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [da7463eff8](https://linux-hardware.org/?probe=da7463eff8) | Nov 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [5191c2b469](https://linux-hardware.org/?probe=5191c2b469) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [4caad7b0d1](https://linux-hardware.org/?probe=4caad7b0d1) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [1d0638865e](https://linux-hardware.org/?probe=1d0638865e) | Nov 07, 2023 |
| Dell          | Latitude 3190               | Notebook    | [309f968d10](https://linux-hardware.org/?probe=309f968d10) | Nov 07, 2023 |
| HP            | 8431                        | All in one  | [00262f7c56](https://linux-hardware.org/?probe=00262f7c56) | Nov 06, 2023 |
| HP            | 8431                        | All in one  | [1d1dbab0f0](https://linux-hardware.org/?probe=1d1dbab0f0) | Nov 06, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [8cd8d5ade1](https://linux-hardware.org/?probe=8cd8d5ade1) | Nov 06, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [a6fbe4af41](https://linux-hardware.org/?probe=a6fbe4af41) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4f690a4297](https://linux-hardware.org/?probe=4f690a4297) | Nov 05, 2023 |
| HP            | Unknown                     | Notebook    | [c8cff9e339](https://linux-hardware.org/?probe=c8cff9e339) | Nov 05, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [5ff7f9b284](https://linux-hardware.org/?probe=5ff7f9b284) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d0f3cf43b7](https://linux-hardware.org/?probe=d0f3cf43b7) | Nov 04, 2023 |
| Lenovo        | ThinkPad X220 4293A25       | Notebook    | [95a5125a73](https://linux-hardware.org/?probe=95a5125a73) | Nov 03, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [62a859fb72](https://linux-hardware.org/?probe=62a859fb72) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [7b64212148](https://linux-hardware.org/?probe=7b64212148) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [0e71b912ec](https://linux-hardware.org/?probe=0e71b912ec) | Nov 03, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [e95902544f](https://linux-hardware.org/?probe=e95902544f) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [b596813aeb](https://linux-hardware.org/?probe=b596813aeb) | Nov 02, 2023 |
| Panasonic     | CF-54-1                     | Notebook    | [b7d7cde99a](https://linux-hardware.org/?probe=b7d7cde99a) | Nov 01, 2023 |
| ONDA          | Tablet                      | Tablet      | [1f8b5d6c72](https://linux-hardware.org/?probe=1f8b5d6c72) | Nov 01, 2023 |
| HP            | 2B01                        | Desktop     | [a345333330](https://linux-hardware.org/?probe=a345333330) | Oct 31, 2023 |
| HP            | 2B01                        | Desktop     | [b3a75824f5](https://linux-hardware.org/?probe=b3a75824f5) | Oct 31, 2023 |
| Dell          | Precision 5570              | Notebook    | [fb83199260](https://linux-hardware.org/?probe=fb83199260) | Oct 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [9dd62a1bb2](https://linux-hardware.org/?probe=9dd62a1bb2) | Oct 31, 2023 |
| Dell          | Latitude 7370               | Notebook    | [f47b42c0b0](https://linux-hardware.org/?probe=f47b42c0b0) | Oct 30, 2023 |
| HP            | Unknown                     | Notebook    | [3aadbc5c33](https://linux-hardware.org/?probe=3aadbc5c33) | Oct 30, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b61ad8059a](https://linux-hardware.org/?probe=b61ad8059a) | Oct 30, 2023 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [261e5240fe](https://linux-hardware.org/?probe=261e5240fe) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [65f24e332a](https://linux-hardware.org/?probe=65f24e332a) | Oct 30, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [e41780f56a](https://linux-hardware.org/?probe=e41780f56a) | Oct 29, 2023 |
| HP            | G62                         | Notebook    | [bd714e9671](https://linux-hardware.org/?probe=bd714e9671) | Oct 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [4aceca5660](https://linux-hardware.org/?probe=4aceca5660) | Oct 28, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [e3bde6ede0](https://linux-hardware.org/?probe=e3bde6ede0) | Oct 28, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [68da315076](https://linux-hardware.org/?probe=68da315076) | Oct 28, 2023 |
| Lenovo        | ThinkPad X230 2325SDE       | Notebook    | [cbdbd4a156](https://linux-hardware.org/?probe=cbdbd4a156) | Oct 27, 2023 |
| HP            | 8433 11                     | Desktop     | [f4b0e9190f](https://linux-hardware.org/?probe=f4b0e9190f) | Oct 27, 2023 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [a20c6e2c77](https://linux-hardware.org/?probe=a20c6e2c77) | Oct 26, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [c1078c11fb](https://linux-hardware.org/?probe=c1078c11fb) | Oct 26, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b05283573c](https://linux-hardware.org/?probe=b05283573c) | Oct 26, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [101037a3e1](https://linux-hardware.org/?probe=101037a3e1) | Oct 25, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [b98bc11e71](https://linux-hardware.org/?probe=b98bc11e71) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [b7447f21b5](https://linux-hardware.org/?probe=b7447f21b5) | Oct 25, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [c505d21099](https://linux-hardware.org/?probe=c505d21099) | Oct 25, 2023 |
| Notebook      | NS5x_NS7xAU                 | Notebook    | [ad7033d138](https://linux-hardware.org/?probe=ad7033d138) | Oct 24, 2023 |
| Lenovo        | ThinkCentre M90 5485W2L     | Desktop     | [0fcc4fe794](https://linux-hardware.org/?probe=0fcc4fe794) | Oct 24, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [51f3725a80](https://linux-hardware.org/?probe=51f3725a80) | Oct 24, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a26f69cb33](https://linux-hardware.org/?probe=a26f69cb33) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [88e833ab8a](https://linux-hardware.org/?probe=88e833ab8a) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [62ca050eaf](https://linux-hardware.org/?probe=62ca050eaf) | Oct 24, 2023 |
| Dixonsxp      | Unknown                     | Notebook    | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| ONDA          | Tablet                      | Tablet      | [2ef7c07bdf](https://linux-hardware.org/?probe=2ef7c07bdf) | Oct 22, 2023 |
| Dell          | 06FW8P A01                  | Desktop     | [356c2f38aa](https://linux-hardware.org/?probe=356c2f38aa) | Oct 21, 2023 |
| HP            | ML150 G3                    | Desktop     | [eb5a4bfed8](https://linux-hardware.org/?probe=eb5a4bfed8) | Oct 21, 2023 |
| ONDA          | Tablet                      | Tablet      | [835a5e9d6d](https://linux-hardware.org/?probe=835a5e9d6d) | Oct 21, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [cceff4e3b1](https://linux-hardware.org/?probe=cceff4e3b1) | Oct 20, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [a7f26cedd6](https://linux-hardware.org/?probe=a7f26cedd6) | Oct 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0feec3b3ab](https://linux-hardware.org/?probe=0feec3b3ab) | Oct 19, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [77cf0c3af6](https://linux-hardware.org/?probe=77cf0c3af6) | Oct 18, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [0815767d1d](https://linux-hardware.org/?probe=0815767d1d) | Oct 18, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [0944131c12](https://linux-hardware.org/?probe=0944131c12) | Oct 18, 2023 |
| ONDA          | Tablet                      | Tablet      | [6a43a8d57d](https://linux-hardware.org/?probe=6a43a8d57d) | Oct 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0b4065c185](https://linux-hardware.org/?probe=0b4065c185) | Oct 17, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [d5febd2212](https://linux-hardware.org/?probe=d5febd2212) | Oct 17, 2023 |
| HP            | 8433 11                     | Desktop     | [24fdb6f03a](https://linux-hardware.org/?probe=24fdb6f03a) | Oct 16, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Notebook      | NS5x_NS7xAU                 | Notebook    | [1568dbcf9b](https://linux-hardware.org/?probe=1568dbcf9b) | Oct 15, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [80bd4e2684](https://linux-hardware.org/?probe=80bd4e2684) | Oct 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [6082a5c0de](https://linux-hardware.org/?probe=6082a5c0de) | Oct 15, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [1df7e29365](https://linux-hardware.org/?probe=1df7e29365) | Oct 15, 2023 |
| Shenzhen D... | MP80                        | Mini pc     | [c6c5b8dc5c](https://linux-hardware.org/?probe=c6c5b8dc5c) | Oct 15, 2023 |
| Shenzhen D... | MP80                        | Mini pc     | [02141519f7](https://linux-hardware.org/?probe=02141519f7) | Oct 15, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [10b572c94a](https://linux-hardware.org/?probe=10b572c94a) | Oct 14, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [7901d1df27](https://linux-hardware.org/?probe=7901d1df27) | Oct 12, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [c815acfae8](https://linux-hardware.org/?probe=c815acfae8) | Oct 11, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [f6fbcbf614](https://linux-hardware.org/?probe=f6fbcbf614) | Oct 11, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [a646cc1cc1](https://linux-hardware.org/?probe=a646cc1cc1) | Oct 10, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [d731fb0868](https://linux-hardware.org/?probe=d731fb0868) | Oct 10, 2023 |
| Dell          | Latitude 7420               | Notebook    | [4071bd53ce](https://linux-hardware.org/?probe=4071bd53ce) | Oct 10, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [f010d626da](https://linux-hardware.org/?probe=f010d626da) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [a07ec0ee55](https://linux-hardware.org/?probe=a07ec0ee55) | Oct 08, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [c360c7552a](https://linux-hardware.org/?probe=c360c7552a) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [7b6ad19193](https://linux-hardware.org/?probe=7b6ad19193) | Oct 07, 2023 |
| Dell          | 0PU052                      | Desktop     | [c32b862792](https://linux-hardware.org/?probe=c32b862792) | Oct 07, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [dcc7e8da51](https://linux-hardware.org/?probe=dcc7e8da51) | Oct 06, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [e5b3d089e8](https://linux-hardware.org/?probe=e5b3d089e8) | Oct 06, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [11497e61f8](https://linux-hardware.org/?probe=11497e61f8) | Oct 06, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8bc96db254](https://linux-hardware.org/?probe=8bc96db254) | Oct 06, 2023 |
| HP            | ZBook 14u G4                | Notebook    | [1d14da7190](https://linux-hardware.org/?probe=1d14da7190) | Oct 05, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [071eee1057](https://linux-hardware.org/?probe=071eee1057) | Oct 03, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [8076ad493d](https://linux-hardware.org/?probe=8076ad493d) | Oct 03, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [6a2fa93249](https://linux-hardware.org/?probe=6a2fa93249) | Oct 03, 2023 |
| Lenovo        | ThinkPad T420s 4170CTO      | Notebook    | [f141fc2bd7](https://linux-hardware.org/?probe=f141fc2bd7) | Oct 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [d88817f79c](https://linux-hardware.org/?probe=d88817f79c) | Oct 02, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f80a538f2a](https://linux-hardware.org/?probe=f80a538f2a) | Oct 02, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [76f023476d](https://linux-hardware.org/?probe=76f023476d) | Oct 02, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [8487059659](https://linux-hardware.org/?probe=8487059659) | Sep 30, 2023 |
| HP            | ZBook Studio G5             | Notebook    | [3f96bd2883](https://linux-hardware.org/?probe=3f96bd2883) | Sep 30, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [545098d0d2](https://linux-hardware.org/?probe=545098d0d2) | Sep 29, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [51f3cd7354](https://linux-hardware.org/?probe=51f3cd7354) | Sep 29, 2023 |
| HP            | ZBook Studio G5             | Notebook    | [239b5a3fd5](https://linux-hardware.org/?probe=239b5a3fd5) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [5c38fe5e79](https://linux-hardware.org/?probe=5c38fe5e79) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [c61d70bcfa](https://linux-hardware.org/?probe=c61d70bcfa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [be49c167d0](https://linux-hardware.org/?probe=be49c167d0) | Sep 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8c585051a3](https://linux-hardware.org/?probe=8c585051a3) | Sep 27, 2023 |
| MSI           | Z77A-S01                    | Desktop     | [277586f152](https://linux-hardware.org/?probe=277586f152) | Sep 27, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | Latitude E7270              | Notebook    | [98dd5eefb6](https://linux-hardware.org/?probe=98dd5eefb6) | Sep 25, 2023 |
| Dell          | Latitude E5270              | Notebook    | [d091c4fa0e](https://linux-hardware.org/?probe=d091c4fa0e) | Sep 24, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [de5a55aa7b](https://linux-hardware.org/?probe=de5a55aa7b) | Sep 23, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [da796376e1](https://linux-hardware.org/?probe=da796376e1) | Sep 23, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [9b6bbb4b56](https://linux-hardware.org/?probe=9b6bbb4b56) | Sep 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [3889f9ca9d](https://linux-hardware.org/?probe=3889f9ca9d) | Sep 23, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [22ce921c1e](https://linux-hardware.org/?probe=22ce921c1e) | Sep 22, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4679088d4e](https://linux-hardware.org/?probe=4679088d4e) | Sep 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [1893bb3992](https://linux-hardware.org/?probe=1893bb3992) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [4d1743c405](https://linux-hardware.org/?probe=4d1743c405) | Sep 20, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [9e6874d35c](https://linux-hardware.org/?probe=9e6874d35c) | Sep 20, 2023 |
| ASUSTek       | P8H61-M EVO                 | Desktop     | [51c58cd13a](https://linux-hardware.org/?probe=51c58cd13a) | Sep 19, 2023 |
| ASUSTek       | P8H61-M EVO                 | Desktop     | [64618297ff](https://linux-hardware.org/?probe=64618297ff) | Sep 19, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [79142d7f53](https://linux-hardware.org/?probe=79142d7f53) | Sep 17, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [10d32d6284](https://linux-hardware.org/?probe=10d32d6284) | Sep 17, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [293bc3eab9](https://linux-hardware.org/?probe=293bc3eab9) | Sep 16, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [f3b7f92416](https://linux-hardware.org/?probe=f3b7f92416) | Sep 16, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2fa5c8bb34](https://linux-hardware.org/?probe=2fa5c8bb34) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [efda5ec51a](https://linux-hardware.org/?probe=efda5ec51a) | Sep 15, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [43f6a3bfc1](https://linux-hardware.org/?probe=43f6a3bfc1) | Sep 14, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [dcd2b90824](https://linux-hardware.org/?probe=dcd2b90824) | Sep 14, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [bd161c3850](https://linux-hardware.org/?probe=bd161c3850) | Sep 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [0cdeaab8be](https://linux-hardware.org/?probe=0cdeaab8be) | Sep 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [118c76cef1](https://linux-hardware.org/?probe=118c76cef1) | Sep 12, 2023 |
| Samsung       | R530/R730/P590              | Notebook    | [d9bd973c79](https://linux-hardware.org/?probe=d9bd973c79) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [58b852c7cb](https://linux-hardware.org/?probe=58b852c7cb) | Sep 12, 2023 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [e1eea73611](https://linux-hardware.org/?probe=e1eea73611) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [10ff64dcf5](https://linux-hardware.org/?probe=10ff64dcf5) | Sep 12, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d3b821a061](https://linux-hardware.org/?probe=d3b821a061) | Sep 10, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [4d658a922b](https://linux-hardware.org/?probe=4d658a922b) | Sep 10, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [03b8175690](https://linux-hardware.org/?probe=03b8175690) | Sep 10, 2023 |
| ASUSTek       | TS10                        | Desktop     | [ad867c5e25](https://linux-hardware.org/?probe=ad867c5e25) | Sep 10, 2023 |
| Dell          | Precision M4800             | Notebook    | [ea570fedac](https://linux-hardware.org/?probe=ea570fedac) | Sep 09, 2023 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [03ce2f9b74](https://linux-hardware.org/?probe=03ce2f9b74) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3857377d7a](https://linux-hardware.org/?probe=3857377d7a) | Sep 09, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [98ba75a25b](https://linux-hardware.org/?probe=98ba75a25b) | Sep 09, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [0c2dda2476](https://linux-hardware.org/?probe=0c2dda2476) | Sep 09, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [b73ef6339a](https://linux-hardware.org/?probe=b73ef6339a) | Sep 08, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [e71f333094](https://linux-hardware.org/?probe=e71f333094) | Sep 07, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [72516e7752](https://linux-hardware.org/?probe=72516e7752) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [26448cf759](https://linux-hardware.org/?probe=26448cf759) | Sep 07, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [7cbd11709c](https://linux-hardware.org/?probe=7cbd11709c) | Sep 07, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [c48759c297](https://linux-hardware.org/?probe=c48759c297) | Sep 07, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [26a5d8b449](https://linux-hardware.org/?probe=26a5d8b449) | Sep 06, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [6521407977](https://linux-hardware.org/?probe=6521407977) | Sep 06, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [5dca7c7315](https://linux-hardware.org/?probe=5dca7c7315) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [07429e910f](https://linux-hardware.org/?probe=07429e910f) | Sep 05, 2023 |
| Dell          | Latitude 7440               | Notebook    | [47f28d7b00](https://linux-hardware.org/?probe=47f28d7b00) | Sep 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [27b2ae9d5b](https://linux-hardware.org/?probe=27b2ae9d5b) | Sep 04, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [c8978cf811](https://linux-hardware.org/?probe=c8978cf811) | Sep 03, 2023 |
| Lenovo        | ThinkPad T440 20B7S0RD00    | Notebook    | [af57fd1655](https://linux-hardware.org/?probe=af57fd1655) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [62ac121b13](https://linux-hardware.org/?probe=62ac121b13) | Sep 03, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [806eed53dc](https://linux-hardware.org/?probe=806eed53dc) | Sep 02, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [377d5352d8](https://linux-hardware.org/?probe=377d5352d8) | Sep 02, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [b6f6192ef9](https://linux-hardware.org/?probe=b6f6192ef9) | Sep 02, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [e4a45bf853](https://linux-hardware.org/?probe=e4a45bf853) | Sep 02, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [19bf85f553](https://linux-hardware.org/?probe=19bf85f553) | Sep 01, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [b938dc8500](https://linux-hardware.org/?probe=b938dc8500) | Aug 31, 2023 |
| HP            | ProBook 6360b               | Notebook    | [0dbff9ebb3](https://linux-hardware.org/?probe=0dbff9ebb3) | Aug 30, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [a21f3ba335](https://linux-hardware.org/?probe=a21f3ba335) | Aug 30, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [3740c90267](https://linux-hardware.org/?probe=3740c90267) | Aug 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [44e7ba057b](https://linux-hardware.org/?probe=44e7ba057b) | Aug 30, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [7c208705e5](https://linux-hardware.org/?probe=7c208705e5) | Aug 29, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [6f5a767b7e](https://linux-hardware.org/?probe=6f5a767b7e) | Aug 29, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [577d9d5dc1](https://linux-hardware.org/?probe=577d9d5dc1) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [0be67de1c9](https://linux-hardware.org/?probe=0be67de1c9) | Aug 29, 2023 |
| Lenovo        | B50-30 80ES                 | Notebook    | [96aa7b5683](https://linux-hardware.org/?probe=96aa7b5683) | Aug 29, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [6736188e61](https://linux-hardware.org/?probe=6736188e61) | Aug 26, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [6a55471f69](https://linux-hardware.org/?probe=6a55471f69) | Aug 26, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [f0a3b05a99](https://linux-hardware.org/?probe=f0a3b05a99) | Aug 25, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [f8f097e135](https://linux-hardware.org/?probe=f8f097e135) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [aa3157f519](https://linux-hardware.org/?probe=aa3157f519) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [8d3738c790](https://linux-hardware.org/?probe=8d3738c790) | Aug 24, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [e11053f833](https://linux-hardware.org/?probe=e11053f833) | Aug 23, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [799390e547](https://linux-hardware.org/?probe=799390e547) | Aug 23, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [3231dcefb4](https://linux-hardware.org/?probe=3231dcefb4) | Aug 22, 2023 |
| HP            | 845A                        | Desktop     | [4a8699daad](https://linux-hardware.org/?probe=4a8699daad) | Aug 22, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b4133748fc](https://linux-hardware.org/?probe=b4133748fc) | Aug 21, 2023 |
| HP            | 212B                        | Desktop     | [ee20bd40d8](https://linux-hardware.org/?probe=ee20bd40d8) | Aug 21, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [83b6cab3cd](https://linux-hardware.org/?probe=83b6cab3cd) | Aug 20, 2023 |
| Dell          | Latitude 3350               | Notebook    | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [d989b68c65](https://linux-hardware.org/?probe=d989b68c65) | Aug 19, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [aa6781c002](https://linux-hardware.org/?probe=aa6781c002) | Aug 18, 2023 |
| ASUSTek       | M3N                         | Notebook    | [7c4b9386db](https://linux-hardware.org/?probe=7c4b9386db) | Aug 18, 2023 |
| ASUSTek       | U38N                        | Notebook    | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [eb44f4dfc1](https://linux-hardware.org/?probe=eb44f4dfc1) | Aug 17, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [91b8c2a5eb](https://linux-hardware.org/?probe=91b8c2a5eb) | Aug 17, 2023 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [3135a88431](https://linux-hardware.org/?probe=3135a88431) | Aug 17, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [2f82c5eb18](https://linux-hardware.org/?probe=2f82c5eb18) | Aug 14, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [369b0195cc](https://linux-hardware.org/?probe=369b0195cc) | Aug 14, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [f3e1bb3812](https://linux-hardware.org/?probe=f3e1bb3812) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [483fc71762](https://linux-hardware.org/?probe=483fc71762) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [0a1e2a7f23](https://linux-hardware.org/?probe=0a1e2a7f23) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [742b085257](https://linux-hardware.org/?probe=742b085257) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [836fcda626](https://linux-hardware.org/?probe=836fcda626) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [3e208faa6e](https://linux-hardware.org/?probe=3e208faa6e) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [df9e6a8d98](https://linux-hardware.org/?probe=df9e6a8d98) | Aug 10, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f20a32551b](https://linux-hardware.org/?probe=f20a32551b) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [bd9c532bbc](https://linux-hardware.org/?probe=bd9c532bbc) | Aug 10, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [e323e9cd7e](https://linux-hardware.org/?probe=e323e9cd7e) | Aug 10, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [a3b9be2f56](https://linux-hardware.org/?probe=a3b9be2f56) | Aug 10, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [4d7fbea818](https://linux-hardware.org/?probe=4d7fbea818) | Aug 09, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [bdc11616d7](https://linux-hardware.org/?probe=bdc11616d7) | Aug 08, 2023 |
| HP            | Unknown                     | Notebook    | [567a10ceb2](https://linux-hardware.org/?probe=567a10ceb2) | Aug 08, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | Notebook    | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [3d49205e68](https://linux-hardware.org/?probe=3d49205e68) | Aug 06, 2023 |
| Toshiba       | Satellite C670D-11P         | Notebook    | [a5c49672d6](https://linux-hardware.org/?probe=a5c49672d6) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [e3fd0f4808](https://linux-hardware.org/?probe=e3fd0f4808) | Aug 04, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [f420f3e1e6](https://linux-hardware.org/?probe=f420f3e1e6) | Aug 04, 2023 |
| Dell          | 0K095G A01                  | Desktop     | [ee2fb87d2f](https://linux-hardware.org/?probe=ee2fb87d2f) | Aug 04, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [bd2d5f588f](https://linux-hardware.org/?probe=bd2d5f588f) | Aug 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNP           | Notebook    | [508c18e563](https://linux-hardware.org/?probe=508c18e563) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [53c9161fc5](https://linux-hardware.org/?probe=53c9161fc5) | Aug 03, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [a449d60316](https://linux-hardware.org/?probe=a449d60316) | Aug 03, 2023 |
| Dell          | Latitude E7240              | Notebook    | [87a0310cf0](https://linux-hardware.org/?probe=87a0310cf0) | Aug 02, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [e0c07e2d0c](https://linux-hardware.org/?probe=e0c07e2d0c) | Aug 02, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [a06a335d70](https://linux-hardware.org/?probe=a06a335d70) | Aug 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c88a2ad597](https://linux-hardware.org/?probe=c88a2ad597) | Aug 01, 2023 |
| HP            | Unknown                     | Notebook    | [a4d8377dfa](https://linux-hardware.org/?probe=a4d8377dfa) | Aug 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [d8272e8eeb](https://linux-hardware.org/?probe=d8272e8eeb) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [436e1e4e01](https://linux-hardware.org/?probe=436e1e4e01) | Jul 29, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [7d5b443b84](https://linux-hardware.org/?probe=7d5b443b84) | Jul 29, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [1b9bb7c266](https://linux-hardware.org/?probe=1b9bb7c266) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a8e51655da](https://linux-hardware.org/?probe=a8e51655da) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [1950bcc818](https://linux-hardware.org/?probe=1950bcc818) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [80a34d344b](https://linux-hardware.org/?probe=80a34d344b) | Jul 28, 2023 |
| Acer          | Spin SP111-31               | Convertible | [003fa350a2](https://linux-hardware.org/?probe=003fa350a2) | Jul 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S55L00    | Notebook    | [5b3742984b](https://linux-hardware.org/?probe=5b3742984b) | Jul 27, 2023 |
| Lenovo        | 3743 SDK0J40700 WIN 3258... | Desktop     | [546f011b1a](https://linux-hardware.org/?probe=546f011b1a) | Jul 27, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [47e831a79a](https://linux-hardware.org/?probe=47e831a79a) | Jul 26, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [4fc2e4c331](https://linux-hardware.org/?probe=4fc2e4c331) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [a060c0999b](https://linux-hardware.org/?probe=a060c0999b) | Jul 26, 2023 |
| Lenovo        | ThinkPad E480 20KN001QMX    | Notebook    | [1ff9753d17](https://linux-hardware.org/?probe=1ff9753d17) | Jul 25, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [ac63d4a30c](https://linux-hardware.org/?probe=ac63d4a30c) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [9fa1cd70a3](https://linux-hardware.org/?probe=9fa1cd70a3) | Jul 24, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1e169f0ba8](https://linux-hardware.org/?probe=1e169f0ba8) | Jul 23, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [52541ec1ed](https://linux-hardware.org/?probe=52541ec1ed) | Jul 23, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [f291f72d81](https://linux-hardware.org/?probe=f291f72d81) | Jul 23, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [bbd3181f1f](https://linux-hardware.org/?probe=bbd3181f1f) | Jul 22, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [9ab47777ca](https://linux-hardware.org/?probe=9ab47777ca) | Jul 21, 2023 |
| HP            | ProBook 4530s               | Notebook    | [450e93a8de](https://linux-hardware.org/?probe=450e93a8de) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS        | Desktop     | [c3994db136](https://linux-hardware.org/?probe=c3994db136) | Jul 21, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [b1a5c8b10d](https://linux-hardware.org/?probe=b1a5c8b10d) | Jul 20, 2023 |
| HP            | 15                          | Notebook    | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| ASUSTek       | A_F_K20BF                   | Desktop     | [f2ae40130e](https://linux-hardware.org/?probe=f2ae40130e) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [805d981913](https://linux-hardware.org/?probe=805d981913) | Jul 19, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [db2a22c2eb](https://linux-hardware.org/?probe=db2a22c2eb) | Jul 19, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [b12aa2eb63](https://linux-hardware.org/?probe=b12aa2eb63) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | Notebook    | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Dell          | 0MN1TX A01                  | Desktop     | [696072cf7c](https://linux-hardware.org/?probe=696072cf7c) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [d2c6c9bcba](https://linux-hardware.org/?probe=d2c6c9bcba) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f4bc253638](https://linux-hardware.org/?probe=f4bc253638) | Jul 17, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [e707b1595f](https://linux-hardware.org/?probe=e707b1595f) | Jul 17, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [65a6e11166](https://linux-hardware.org/?probe=65a6e11166) | Jul 17, 2023 |
| MSI           | GF65 Thin 10SER             | Notebook    | [27966135e2](https://linux-hardware.org/?probe=27966135e2) | Jul 16, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [21950296b4](https://linux-hardware.org/?probe=21950296b4) | Jul 16, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [0063ae1936](https://linux-hardware.org/?probe=0063ae1936) | Jul 16, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [6758dfb731](https://linux-hardware.org/?probe=6758dfb731) | Jul 15, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [801eb1eb3c](https://linux-hardware.org/?probe=801eb1eb3c) | Jul 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Alienware     | x15 R1                      | Notebook    | [a72051a57e](https://linux-hardware.org/?probe=a72051a57e) | Jul 13, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | Notebook    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ab0a96405e](https://linux-hardware.org/?probe=ab0a96405e) | Jul 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [30403bcd32](https://linux-hardware.org/?probe=30403bcd32) | Jul 12, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [c3b936e87a](https://linux-hardware.org/?probe=c3b936e87a) | Jul 12, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [161a78ce7d](https://linux-hardware.org/?probe=161a78ce7d) | Jul 11, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [cfc5e42de6](https://linux-hardware.org/?probe=cfc5e42de6) | Jul 11, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d0035bb703](https://linux-hardware.org/?probe=d0035bb703) | Jul 10, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [2992a0aea9](https://linux-hardware.org/?probe=2992a0aea9) | Jul 10, 2023 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [57cc83ff44](https://linux-hardware.org/?probe=57cc83ff44) | Jul 10, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [4b33cf2e09](https://linux-hardware.org/?probe=4b33cf2e09) | Jul 09, 2023 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [c7d3e6a151](https://linux-hardware.org/?probe=c7d3e6a151) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [ecd8f6cdd2](https://linux-hardware.org/?probe=ecd8f6cdd2) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [0ea27ea171](https://linux-hardware.org/?probe=0ea27ea171) | Jul 09, 2023 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [bdf5ce2163](https://linux-hardware.org/?probe=bdf5ce2163) | Jul 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [5f28888f0d](https://linux-hardware.org/?probe=5f28888f0d) | Jul 06, 2023 |
| Medion        | ML-210007                   | Notebook    | [192b83694f](https://linux-hardware.org/?probe=192b83694f) | Jul 06, 2023 |
| Medion        | ML-210007                   | Notebook    | [8bc97d58d2](https://linux-hardware.org/?probe=8bc97d58d2) | Jul 06, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [9c0f0d40b9](https://linux-hardware.org/?probe=9c0f0d40b9) | Jul 05, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [348b9a4a73](https://linux-hardware.org/?probe=348b9a4a73) | Jul 05, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [fceaf9bea9](https://linux-hardware.org/?probe=fceaf9bea9) | Jul 04, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [b6d0f85342](https://linux-hardware.org/?probe=b6d0f85342) | Jul 04, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [e2c9e04a7c](https://linux-hardware.org/?probe=e2c9e04a7c) | Jul 04, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [50b65edbc0](https://linux-hardware.org/?probe=50b65edbc0) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [e0fc7e357f](https://linux-hardware.org/?probe=e0fc7e357f) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [0ca36f92b8](https://linux-hardware.org/?probe=0ca36f92b8) | Jul 03, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [066d1a2fa8](https://linux-hardware.org/?probe=066d1a2fa8) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [80810e133e](https://linux-hardware.org/?probe=80810e133e) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [48df5942cf](https://linux-hardware.org/?probe=48df5942cf) | Jul 02, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f91dbee23b](https://linux-hardware.org/?probe=f91dbee23b) | Jul 02, 2023 |
| Acer          | Predator G9-593             | Notebook    | [127df9999f](https://linux-hardware.org/?probe=127df9999f) | Jul 01, 2023 |
| TrekStor      | YOURBOOK C11B               | Convertible | [8c2340f01f](https://linux-hardware.org/?probe=8c2340f01f) | Jul 01, 2023 |
| Acer          | Predator G9-593             | Notebook    | [d4dca39223](https://linux-hardware.org/?probe=d4dca39223) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [7f9164d1e0](https://linux-hardware.org/?probe=7f9164d1e0) | Jun 29, 2023 |
| Acer          | Aspire XC-840               | Desktop     | [76c750aae4](https://linux-hardware.org/?probe=76c750aae4) | Jun 29, 2023 |
| Lenovo        | ThinkPad X240 20AL00C7MD    | Notebook    | [5c5334f633](https://linux-hardware.org/?probe=5c5334f633) | Jun 28, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [a91acc04b6](https://linux-hardware.org/?probe=a91acc04b6) | Jun 28, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [cc161cc65b](https://linux-hardware.org/?probe=cc161cc65b) | Jun 28, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [32e4f74711](https://linux-hardware.org/?probe=32e4f74711) | Jun 28, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [9450fc030e](https://linux-hardware.org/?probe=9450fc030e) | Jun 27, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [566e7a4396](https://linux-hardware.org/?probe=566e7a4396) | Jun 26, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [165584477b](https://linux-hardware.org/?probe=165584477b) | Jun 25, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [3c8a1b23bb](https://linux-hardware.org/?probe=3c8a1b23bb) | Jun 24, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [e10aa58dda](https://linux-hardware.org/?probe=e10aa58dda) | Jun 24, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [510d2844bd](https://linux-hardware.org/?probe=510d2844bd) | Jun 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [56208916c9](https://linux-hardware.org/?probe=56208916c9) | Jun 23, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [3d506cafad](https://linux-hardware.org/?probe=3d506cafad) | Jun 22, 2023 |
| MSI           | GX60 1AC                    | Notebook    | [8e15fea8cd](https://linux-hardware.org/?probe=8e15fea8cd) | Jun 22, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7ac67acfed](https://linux-hardware.org/?probe=7ac67acfed) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [a7b7b2c413](https://linux-hardware.org/?probe=a7b7b2c413) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [d4bd011ff9](https://linux-hardware.org/?probe=d4bd011ff9) | Jun 21, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [30f85c0f2e](https://linux-hardware.org/?probe=30f85c0f2e) | Jun 21, 2023 |
| MSI           | Katana GF76 12UD            | Notebook    | [1897f5f0cb](https://linux-hardware.org/?probe=1897f5f0cb) | Jun 20, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9e30c629f3](https://linux-hardware.org/?probe=9e30c629f3) | Jun 19, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [6579287940](https://linux-hardware.org/?probe=6579287940) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0c5693c658](https://linux-hardware.org/?probe=0c5693c658) | Jun 18, 2023 |
| OEM           | ALDER LAKE JHS64S           | Desktop     | [0eb1dc0b8e](https://linux-hardware.org/?probe=0eb1dc0b8e) | Jun 16, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [b0361fedbc](https://linux-hardware.org/?probe=b0361fedbc) | Jun 16, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [da6bfc34aa](https://linux-hardware.org/?probe=da6bfc34aa) | Jun 15, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [74a69e5cca](https://linux-hardware.org/?probe=74a69e5cca) | Jun 15, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [a0e0ea6aa1](https://linux-hardware.org/?probe=a0e0ea6aa1) | Jun 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [91af63490c](https://linux-hardware.org/?probe=91af63490c) | Jun 15, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [294cbcd9cd](https://linux-hardware.org/?probe=294cbcd9cd) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [11fa244fa5](https://linux-hardware.org/?probe=11fa244fa5) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [e9aeb26aeb](https://linux-hardware.org/?probe=e9aeb26aeb) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [f675b70f23](https://linux-hardware.org/?probe=f675b70f23) | Jun 14, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [bbcb31d079](https://linux-hardware.org/?probe=bbcb31d079) | Jun 14, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [ff01549321](https://linux-hardware.org/?probe=ff01549321) | Jun 14, 2023 |
| Dell          | Latitude 7480               | Notebook    | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [3a8338d906](https://linux-hardware.org/?probe=3a8338d906) | Jun 13, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [cda9f3da9c](https://linux-hardware.org/?probe=cda9f3da9c) | Jun 13, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [93cd1fd89c](https://linux-hardware.org/?probe=93cd1fd89c) | Jun 13, 2023 |
| Dell          | Latitude 3320               | Notebook    | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | Notebook    | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [88fc978934](https://linux-hardware.org/?probe=88fc978934) | Jun 12, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [0b737be0c6](https://linux-hardware.org/?probe=0b737be0c6) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5f4978fc61](https://linux-hardware.org/?probe=5f4978fc61) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8a3bd0a576](https://linux-hardware.org/?probe=8a3bd0a576) | Jun 11, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [2838a84809](https://linux-hardware.org/?probe=2838a84809) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [d58405f7c1](https://linux-hardware.org/?probe=d58405f7c1) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [86b377710d](https://linux-hardware.org/?probe=86b377710d) | Jun 10, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [2c8c27897b](https://linux-hardware.org/?probe=2c8c27897b) | Jun 09, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [8fa2e2acc9](https://linux-hardware.org/?probe=8fa2e2acc9) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6a98d856ee](https://linux-hardware.org/?probe=6a98d856ee) | Jun 07, 2023 |
| Dell          | Latitude 3340               | Notebook    | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [4d71226d7c](https://linux-hardware.org/?probe=4d71226d7c) | Jun 04, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [f92e294ba0](https://linux-hardware.org/?probe=f92e294ba0) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [48eb50cc43](https://linux-hardware.org/?probe=48eb50cc43) | Jun 03, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ded9a8f554](https://linux-hardware.org/?probe=ded9a8f554) | Jun 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [79de4bed98](https://linux-hardware.org/?probe=79de4bed98) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eda1870d76](https://linux-hardware.org/?probe=eda1870d76) | May 31, 2023 |
| Gigabyte      | X99-UD7 WIFI-CF             | Desktop     | [955e65b76f](https://linux-hardware.org/?probe=955e65b76f) | May 31, 2023 |
| Timi          | RedmiBook 14 II             | Notebook    | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [5271bd0b88](https://linux-hardware.org/?probe=5271bd0b88) | May 30, 2023 |
| MSI           | Katana GF76 12UD            | Notebook    | [b1b1816b59](https://linux-hardware.org/?probe=b1b1816b59) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | Notebook    | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [2f1017a58e](https://linux-hardware.org/?probe=2f1017a58e) | May 28, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [32fee60a54](https://linux-hardware.org/?probe=32fee60a54) | May 28, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ec91d28c95](https://linux-hardware.org/?probe=ec91d28c95) | May 28, 2023 |
| HP            | Compaq 6730s                | Notebook    | [fe2b8b63ac](https://linux-hardware.org/?probe=fe2b8b63ac) | May 28, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [f4411b6232](https://linux-hardware.org/?probe=f4411b6232) | May 27, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [07ecf79e17](https://linux-hardware.org/?probe=07ecf79e17) | May 26, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c4af5a7969](https://linux-hardware.org/?probe=c4af5a7969) | May 26, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [aa99fb811d](https://linux-hardware.org/?probe=aa99fb811d) | May 26, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [dbfc9be02f](https://linux-hardware.org/?probe=dbfc9be02f) | May 26, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25f6dcaefc](https://linux-hardware.org/?probe=25f6dcaefc) | May 25, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [486d6ac497](https://linux-hardware.org/?probe=486d6ac497) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| congatec      | conga-TA7 A.4               | Mini pc     | [686699557a](https://linux-hardware.org/?probe=686699557a) | May 24, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f2477906c7](https://linux-hardware.org/?probe=f2477906c7) | May 23, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [266235dc3b](https://linux-hardware.org/?probe=266235dc3b) | May 23, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [73d0ff64b6](https://linux-hardware.org/?probe=73d0ff64b6) | May 23, 2023 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [0cba90ce8e](https://linux-hardware.org/?probe=0cba90ce8e) | May 23, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [df04cb5fb1](https://linux-hardware.org/?probe=df04cb5fb1) | May 22, 2023 |
| Lenovo        | ThinkPad T550 20CJS1V900    | Notebook    | [9bc275ef54](https://linux-hardware.org/?probe=9bc275ef54) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [117bc29848](https://linux-hardware.org/?probe=117bc29848) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [e3af81180a](https://linux-hardware.org/?probe=e3af81180a) | May 22, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [11c329d15a](https://linux-hardware.org/?probe=11c329d15a) | May 22, 2023 |
| MSI           | Z87-G43                     | Desktop     | [2fa7c1d81d](https://linux-hardware.org/?probe=2fa7c1d81d) | May 21, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [b3564ca1cf](https://linux-hardware.org/?probe=b3564ca1cf) | May 20, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [cce6eaa028](https://linux-hardware.org/?probe=cce6eaa028) | May 20, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [15d9163f08](https://linux-hardware.org/?probe=15d9163f08) | May 20, 2023 |
| HP            | Compaq 6730s                | Notebook    | [632961079b](https://linux-hardware.org/?probe=632961079b) | May 20, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | Desktop     | [693c7b6d9b](https://linux-hardware.org/?probe=693c7b6d9b) | May 18, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [7a2e636353](https://linux-hardware.org/?probe=7a2e636353) | May 18, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [ca0ae58640](https://linux-hardware.org/?probe=ca0ae58640) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | Notebook    | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| Acer          | Revo 70                     | Desktop     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [0829603c60](https://linux-hardware.org/?probe=0829603c60) | May 17, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [7d818512b8](https://linux-hardware.org/?probe=7d818512b8) | May 17, 2023 |
| Packard Be... | EasyNote TV43CM             | Notebook    | [66dbc844c7](https://linux-hardware.org/?probe=66dbc844c7) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [8c10a0ad96](https://linux-hardware.org/?probe=8c10a0ad96) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [be5ad76a6e](https://linux-hardware.org/?probe=be5ad76a6e) | May 16, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7d44c65f86](https://linux-hardware.org/?probe=7d44c65f86) | May 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [36df0e0f57](https://linux-hardware.org/?probe=36df0e0f57) | May 14, 2023 |
| MSI           | H110I PRO                   | Desktop     | [1224d45c07](https://linux-hardware.org/?probe=1224d45c07) | May 14, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [df19e8413c](https://linux-hardware.org/?probe=df19e8413c) | May 14, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [beb403e4e0](https://linux-hardware.org/?probe=beb403e4e0) | May 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [5ab21854e6](https://linux-hardware.org/?probe=5ab21854e6) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [c5c05f7e4c](https://linux-hardware.org/?probe=c5c05f7e4c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | Notebook    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [d835755922](https://linux-hardware.org/?probe=d835755922) | May 12, 2023 |
| HP            | ProBook 6470b               | Notebook    | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | Notebook    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [cbc84d049a](https://linux-hardware.org/?probe=cbc84d049a) | May 12, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [c458dad4b3](https://linux-hardware.org/?probe=c458dad4b3) | May 12, 2023 |
| ASUSTek       | Rampage IV FORMULA          | Desktop     | [b44dd1286b](https://linux-hardware.org/?probe=b44dd1286b) | May 12, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [c51d42778d](https://linux-hardware.org/?probe=c51d42778d) | May 12, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [e65b0be462](https://linux-hardware.org/?probe=e65b0be462) | May 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d5bd5c8930](https://linux-hardware.org/?probe=d5bd5c8930) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [e661dd9daf](https://linux-hardware.org/?probe=e661dd9daf) | May 11, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [721f9583d7](https://linux-hardware.org/?probe=721f9583d7) | May 11, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [bd7c97ad54](https://linux-hardware.org/?probe=bd7c97ad54) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9cbcc36a48](https://linux-hardware.org/?probe=9cbcc36a48) | May 11, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [483f4bbb5d](https://linux-hardware.org/?probe=483f4bbb5d) | May 10, 2023 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [535cc48341](https://linux-hardware.org/?probe=535cc48341) | May 08, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4c3e0a0ac6](https://linux-hardware.org/?probe=4c3e0a0ac6) | May 08, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [08df3c35ee](https://linux-hardware.org/?probe=08df3c35ee) | May 08, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [3ac194e77a](https://linux-hardware.org/?probe=3ac194e77a) | May 07, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [1c84c61678](https://linux-hardware.org/?probe=1c84c61678) | May 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [893f259653](https://linux-hardware.org/?probe=893f259653) | May 07, 2023 |
| MSI           | MS-B120                     | Mini pc     | [836697d300](https://linux-hardware.org/?probe=836697d300) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c88845ae9b](https://linux-hardware.org/?probe=c88845ae9b) | May 06, 2023 |
| Dell          | Vostro 3360                 | Notebook    | [13a1e30b53](https://linux-hardware.org/?probe=13a1e30b53) | May 06, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [14c71828ca](https://linux-hardware.org/?probe=14c71828ca) | May 05, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [3f515702d2](https://linux-hardware.org/?probe=3f515702d2) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [a15c5113a0](https://linux-hardware.org/?probe=a15c5113a0) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [5b24260cc3](https://linux-hardware.org/?probe=5b24260cc3) | May 05, 2023 |
| Dell          | 02N3WF A02                  | Desktop     | [3f10b3ca43](https://linux-hardware.org/?probe=3f10b3ca43) | May 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [0b217b3ccc](https://linux-hardware.org/?probe=0b217b3ccc) | May 04, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [2f6fd9e5b0](https://linux-hardware.org/?probe=2f6fd9e5b0) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [6cbfaabd66](https://linux-hardware.org/?probe=6cbfaabd66) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [4762d9bb4e](https://linux-hardware.org/?probe=4762d9bb4e) | May 03, 2023 |
| Dynabook      | Satellite Pro C50-G-10M     | Notebook    | [d64568ca9c](https://linux-hardware.org/?probe=d64568ca9c) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e8721751c6](https://linux-hardware.org/?probe=e8721751c6) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e426e8e40b](https://linux-hardware.org/?probe=e426e8e40b) | May 03, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [973f9c6467](https://linux-hardware.org/?probe=973f9c6467) | May 01, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [92f7217eb7](https://linux-hardware.org/?probe=92f7217eb7) | May 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [22cf2ddf02](https://linux-hardware.org/?probe=22cf2ddf02) | May 01, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [56db7fc27f](https://linux-hardware.org/?probe=56db7fc27f) | May 01, 2023 |
| Shuttle       | FS35V4                      | Desktop     | [137fda9bc6](https://linux-hardware.org/?probe=137fda9bc6) | May 01, 2023 |
| MSI           | MS-B120                     | Mini pc     | [8019bfa6d4](https://linux-hardware.org/?probe=8019bfa6d4) | Apr 30, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4f10159e93](https://linux-hardware.org/?probe=4f10159e93) | Apr 30, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [4b47a4606b](https://linux-hardware.org/?probe=4b47a4606b) | Apr 29, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [d97d6d6dff](https://linux-hardware.org/?probe=d97d6d6dff) | Apr 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [1a73639c02](https://linux-hardware.org/?probe=1a73639c02) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [a6eba14ab4](https://linux-hardware.org/?probe=a6eba14ab4) | Apr 28, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [6f56840307](https://linux-hardware.org/?probe=6f56840307) | Apr 28, 2023 |
| Dell          | Latitude 5430               | Notebook    | [644e44f95a](https://linux-hardware.org/?probe=644e44f95a) | Apr 28, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [c53a69bd72](https://linux-hardware.org/?probe=c53a69bd72) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [07572e6599](https://linux-hardware.org/?probe=07572e6599) | Apr 27, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ff439c208a](https://linux-hardware.org/?probe=ff439c208a) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [69f1753783](https://linux-hardware.org/?probe=69f1753783) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [067bc49888](https://linux-hardware.org/?probe=067bc49888) | Apr 26, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [c6a1179816](https://linux-hardware.org/?probe=c6a1179816) | Apr 25, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [4fcb9881b2](https://linux-hardware.org/?probe=4fcb9881b2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [21c872ac1c](https://linux-hardware.org/?probe=21c872ac1c) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [99e0054492](https://linux-hardware.org/?probe=99e0054492) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [86b56d3e69](https://linux-hardware.org/?probe=86b56d3e69) | Apr 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [adab9d9f6b](https://linux-hardware.org/?probe=adab9d9f6b) | Apr 22, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [17c955a974](https://linux-hardware.org/?probe=17c955a974) | Apr 21, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [cb9c80dbba](https://linux-hardware.org/?probe=cb9c80dbba) | Apr 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [68d07ba405](https://linux-hardware.org/?probe=68d07ba405) | Apr 20, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [3f12350d47](https://linux-hardware.org/?probe=3f12350d47) | Apr 20, 2023 |
| Dell          | Latitude 7490               | Notebook    | [57a719ce62](https://linux-hardware.org/?probe=57a719ce62) | Apr 20, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [69c613b55f](https://linux-hardware.org/?probe=69c613b55f) | Apr 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [83c6b6137d](https://linux-hardware.org/?probe=83c6b6137d) | Apr 20, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [b45a30f071](https://linux-hardware.org/?probe=b45a30f071) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6SV0... | Notebook    | [8f05b53b93](https://linux-hardware.org/?probe=8f05b53b93) | Apr 17, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [4278a9f497](https://linux-hardware.org/?probe=4278a9f497) | Apr 17, 2023 |
| Toshiba       | Satellite C855D-162         | Notebook    | [d8e8774e0b](https://linux-hardware.org/?probe=d8e8774e0b) | Apr 17, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [39106da598](https://linux-hardware.org/?probe=39106da598) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a9f8183365](https://linux-hardware.org/?probe=a9f8183365) | Apr 16, 2023 |
| Unknown       | Unknown                     | Phone       | [3d8d71ba51](https://linux-hardware.org/?probe=3d8d71ba51) | Apr 16, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [a51c500b65](https://linux-hardware.org/?probe=a51c500b65) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [53c9fe0b8d](https://linux-hardware.org/?probe=53c9fe0b8d) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [99f95937d4](https://linux-hardware.org/?probe=99f95937d4) | Apr 15, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [b259f47200](https://linux-hardware.org/?probe=b259f47200) | Apr 15, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [40894d0141](https://linux-hardware.org/?probe=40894d0141) | Apr 14, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [d2c04327fb](https://linux-hardware.org/?probe=d2c04327fb) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [b7786541c0](https://linux-hardware.org/?probe=b7786541c0) | Apr 13, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [ec6dc0883b](https://linux-hardware.org/?probe=ec6dc0883b) | Apr 13, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [66924704d2](https://linux-hardware.org/?probe=66924704d2) | Apr 12, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [87d43c1f1d](https://linux-hardware.org/?probe=87d43c1f1d) | Apr 12, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [a291f82fe3](https://linux-hardware.org/?probe=a291f82fe3) | Apr 12, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [810aed46d0](https://linux-hardware.org/?probe=810aed46d0) | Apr 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [5db9e8f875](https://linux-hardware.org/?probe=5db9e8f875) | Apr 11, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [7ddf3af042](https://linux-hardware.org/?probe=7ddf3af042) | Apr 11, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [e3eee10ad1](https://linux-hardware.org/?probe=e3eee10ad1) | Apr 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [885fff9ddb](https://linux-hardware.org/?probe=885fff9ddb) | Apr 10, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [d5fb19d97c](https://linux-hardware.org/?probe=d5fb19d97c) | Apr 08, 2023 |
| HP            | ProBook 4530s               | Notebook    | [efd084d9d5](https://linux-hardware.org/?probe=efd084d9d5) | Apr 07, 2023 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [0ddbf6cc2e](https://linux-hardware.org/?probe=0ddbf6cc2e) | Apr 07, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [a0c75732ae](https://linux-hardware.org/?probe=a0c75732ae) | Apr 06, 2023 |
| LG Electro... | Kabylake Platform           | Notebook    | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [0f4a907d19](https://linux-hardware.org/?probe=0f4a907d19) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [d337edfd9a](https://linux-hardware.org/?probe=d337edfd9a) | Apr 05, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6ddafae4d0](https://linux-hardware.org/?probe=6ddafae4d0) | Apr 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [01f2e4a69f](https://linux-hardware.org/?probe=01f2e4a69f) | Apr 05, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [f49ec499ed](https://linux-hardware.org/?probe=f49ec499ed) | Apr 04, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [68322a0698](https://linux-hardware.org/?probe=68322a0698) | Apr 04, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [9d90029e27](https://linux-hardware.org/?probe=9d90029e27) | Apr 04, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [53fc9d8c25](https://linux-hardware.org/?probe=53fc9d8c25) | Apr 04, 2023 |
| Dell          | Precision 5530              | Notebook    | [bf568860cb](https://linux-hardware.org/?probe=bf568860cb) | Apr 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [550f1d522d](https://linux-hardware.org/?probe=550f1d522d) | Apr 04, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [56a619b537](https://linux-hardware.org/?probe=56a619b537) | Apr 04, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [08074927ff](https://linux-hardware.org/?probe=08074927ff) | Apr 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d57f6cb4c6](https://linux-hardware.org/?probe=d57f6cb4c6) | Apr 03, 2023 |
| Intel         | NUC12WSBi5 M63398-302       | Mini pc     | [785a41f4e9](https://linux-hardware.org/?probe=785a41f4e9) | Apr 02, 2023 |
| Acer          | Predator G3-605             | Desktop     | [f7ca1573d0](https://linux-hardware.org/?probe=f7ca1573d0) | Apr 02, 2023 |
| Acer          | Predator G3-605             | Desktop     | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [06275c19f3](https://linux-hardware.org/?probe=06275c19f3) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [36e57fb4cf](https://linux-hardware.org/?probe=36e57fb4cf) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a89c429c84](https://linux-hardware.org/?probe=a89c429c84) | Mar 31, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [fc0539603c](https://linux-hardware.org/?probe=fc0539603c) | Mar 31, 2023 |
| HP            | 82B4                        | Desktop     | [9712d04ab5](https://linux-hardware.org/?probe=9712d04ab5) | Mar 30, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [f897573506](https://linux-hardware.org/?probe=f897573506) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [50affe59d1](https://linux-hardware.org/?probe=50affe59d1) | Mar 28, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [b74b7f7d31](https://linux-hardware.org/?probe=b74b7f7d31) | Mar 28, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [f0e6089a6e](https://linux-hardware.org/?probe=f0e6089a6e) | Mar 28, 2023 |
| Acer          | Nitro N50-640               | Desktop     | [2219ec0fad](https://linux-hardware.org/?probe=2219ec0fad) | Mar 27, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [011d1b8bf7](https://linux-hardware.org/?probe=011d1b8bf7) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [c5a3b374a7](https://linux-hardware.org/?probe=c5a3b374a7) | Mar 27, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [8a1c592e98](https://linux-hardware.org/?probe=8a1c592e98) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [f403538019](https://linux-hardware.org/?probe=f403538019) | Mar 26, 2023 |
| HP            | 1998                        | Desktop     | [346f37956b](https://linux-hardware.org/?probe=346f37956b) | Mar 26, 2023 |
| Gigabyte      | AORUS 15G KC                | Notebook    | [d87e89d84f](https://linux-hardware.org/?probe=d87e89d84f) | Mar 26, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [6f9300474f](https://linux-hardware.org/?probe=6f9300474f) | Mar 26, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [d1baffa910](https://linux-hardware.org/?probe=d1baffa910) | Mar 25, 2023 |
| HP            | 2B05                        | Desktop     | [b34e6d230c](https://linux-hardware.org/?probe=b34e6d230c) | Mar 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b2cdf1deb7](https://linux-hardware.org/?probe=b2cdf1deb7) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [1e549ae67e](https://linux-hardware.org/?probe=1e549ae67e) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [09fec047e4](https://linux-hardware.org/?probe=09fec047e4) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bf24fe6112](https://linux-hardware.org/?probe=bf24fe6112) | Mar 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [883d4de906](https://linux-hardware.org/?probe=883d4de906) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [b4c65fead7](https://linux-hardware.org/?probe=b4c65fead7) | Mar 21, 2023 |
| Shuttle       | SH570                       | Desktop     | [3ef2bf52b7](https://linux-hardware.org/?probe=3ef2bf52b7) | Mar 21, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [240444cad9](https://linux-hardware.org/?probe=240444cad9) | Mar 21, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [a9a586ef2d](https://linux-hardware.org/?probe=a9a586ef2d) | Mar 20, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [51e5415bb0](https://linux-hardware.org/?probe=51e5415bb0) | Mar 19, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [c88d5f831a](https://linux-hardware.org/?probe=c88d5f831a) | Mar 19, 2023 |
| Intel         | NUC5CPYB H61145-412         | Mini pc     | [a87d0fe300](https://linux-hardware.org/?probe=a87d0fe300) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bd119c8898](https://linux-hardware.org/?probe=bd119c8898) | Mar 17, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [87ba801b00](https://linux-hardware.org/?probe=87ba801b00) | Mar 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [d95b09eda0](https://linux-hardware.org/?probe=d95b09eda0) | Mar 17, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [dfb8518fa9](https://linux-hardware.org/?probe=dfb8518fa9) | Mar 16, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [bb4f0202b7](https://linux-hardware.org/?probe=bb4f0202b7) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Google        | Rabbid                      | Notebook    | [621762ceec](https://linux-hardware.org/?probe=621762ceec) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | Notebook    | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [016f5cd3be](https://linux-hardware.org/?probe=016f5cd3be) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | Desktop     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [070c7d809a](https://linux-hardware.org/?probe=070c7d809a) | Mar 13, 2023 |
| GPD           | P2 MAX                      | Notebook    | [dd958bf28e](https://linux-hardware.org/?probe=dd958bf28e) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [ff9cb78f74](https://linux-hardware.org/?probe=ff9cb78f74) | Mar 13, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [12120178de](https://linux-hardware.org/?probe=12120178de) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| HP            | 1825                        | Desktop     | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [1169593829](https://linux-hardware.org/?probe=1169593829) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [76e4cc71f5](https://linux-hardware.org/?probe=76e4cc71f5) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [75fc2c0a15](https://linux-hardware.org/?probe=75fc2c0a15) | Mar 12, 2023 |
| HP            | 1998                        | Desktop     | [68d7c4350d](https://linux-hardware.org/?probe=68d7c4350d) | Mar 12, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c22a046fc6](https://linux-hardware.org/?probe=c22a046fc6) | Mar 11, 2023 |
| SiYW          | V200 Series                 | Desktop     | [7c3751c888](https://linux-hardware.org/?probe=7c3751c888) | Mar 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [0555c85a89](https://linux-hardware.org/?probe=0555c85a89) | Mar 11, 2023 |
| HP            | 18E5                        | Desktop     | [82e5831486](https://linux-hardware.org/?probe=82e5831486) | Mar 10, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [03f44a913e](https://linux-hardware.org/?probe=03f44a913e) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4d15122995](https://linux-hardware.org/?probe=4d15122995) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc6e719e99](https://linux-hardware.org/?probe=cc6e719e99) | Mar 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d1768ecbaa](https://linux-hardware.org/?probe=d1768ecbaa) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [081ecd2050](https://linux-hardware.org/?probe=081ecd2050) | Mar 07, 2023 |
| HP            | Presario CQ57               | Notebook    | [33b1812664](https://linux-hardware.org/?probe=33b1812664) | Mar 06, 2023 |
| HP            | Presario CQ57               | Notebook    | [26ec55c2cb](https://linux-hardware.org/?probe=26ec55c2cb) | Mar 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0d202dc031](https://linux-hardware.org/?probe=0d202dc031) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8814af9b71](https://linux-hardware.org/?probe=8814af9b71) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [deb075440f](https://linux-hardware.org/?probe=deb075440f) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [f21bd9cc58](https://linux-hardware.org/?probe=f21bd9cc58) | Mar 05, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [19bd4c1e4e](https://linux-hardware.org/?probe=19bd4c1e4e) | Mar 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f9a2075d54](https://linux-hardware.org/?probe=f9a2075d54) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Dell          | Precision 3551              | Notebook    | [7c1bc8355a](https://linux-hardware.org/?probe=7c1bc8355a) | Mar 03, 2023 |
| Clevo         | W25xHNx                     | Notebook    | [5227127f81](https://linux-hardware.org/?probe=5227127f81) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [f3defb812b](https://linux-hardware.org/?probe=f3defb812b) | Mar 03, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [41d9c3d9ed](https://linux-hardware.org/?probe=41d9c3d9ed) | Mar 02, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a279108842](https://linux-hardware.org/?probe=a279108842) | Mar 02, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | Desktop     | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [3cd0e65d1f](https://linux-hardware.org/?probe=3cd0e65d1f) | Feb 27, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [2fe31a709a](https://linux-hardware.org/?probe=2fe31a709a) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [5ef01d46d4](https://linux-hardware.org/?probe=5ef01d46d4) | Feb 25, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0AE0... | Notebook    | [7f8c9de1aa](https://linux-hardware.org/?probe=7f8c9de1aa) | Feb 24, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [fc86b476d7](https://linux-hardware.org/?probe=fc86b476d7) | Feb 22, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [de328ac1ad](https://linux-hardware.org/?probe=de328ac1ad) | Feb 22, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | Notebook    | [da461191e8](https://linux-hardware.org/?probe=da461191e8) | Feb 21, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [54b9c4c95c](https://linux-hardware.org/?probe=54b9c4c95c) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ecc97fee86](https://linux-hardware.org/?probe=ecc97fee86) | Feb 21, 2023 |
| Dell          | Precision M4800             | Notebook    | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd6a746c89](https://linux-hardware.org/?probe=bd6a746c89) | Feb 20, 2023 |
| ASUSTek       | G501VW                      | Notebook    | [6e014311b2](https://linux-hardware.org/?probe=6e014311b2) | Feb 20, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [5aa73f71fd](https://linux-hardware.org/?probe=5aa73f71fd) | Feb 20, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [7427fa6886](https://linux-hardware.org/?probe=7427fa6886) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [2b56edae65](https://linux-hardware.org/?probe=2b56edae65) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [dde311dcb2](https://linux-hardware.org/?probe=dde311dcb2) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [96b350db9f](https://linux-hardware.org/?probe=96b350db9f) | Feb 18, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f594570a77](https://linux-hardware.org/?probe=f594570a77) | Feb 16, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [8e521a2efc](https://linux-hardware.org/?probe=8e521a2efc) | Feb 16, 2023 |
| GPD           | P2 MAX                      | Notebook    | [9a623b2196](https://linux-hardware.org/?probe=9a623b2196) | Feb 16, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [eac9c046ac](https://linux-hardware.org/?probe=eac9c046ac) | Feb 15, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [3717c2476f](https://linux-hardware.org/?probe=3717c2476f) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4e3ff30332](https://linux-hardware.org/?probe=4e3ff30332) | Feb 15, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [eb40144624](https://linux-hardware.org/?probe=eb40144624) | Feb 13, 2023 |
| HP            | 8455                        | Desktop     | [f75db6c5d5](https://linux-hardware.org/?probe=f75db6c5d5) | Feb 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [3a18e2226c](https://linux-hardware.org/?probe=3a18e2226c) | Feb 12, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [004535fd1c](https://linux-hardware.org/?probe=004535fd1c) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c1ac37fee3](https://linux-hardware.org/?probe=c1ac37fee3) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| MSI           | MS-B120                     | Mini pc     | [1d365cbddd](https://linux-hardware.org/?probe=1d365cbddd) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [a60a4191b8](https://linux-hardware.org/?probe=a60a4191b8) | Feb 10, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| AZW           | GTR V01                     | Mini pc     | [2898aebf10](https://linux-hardware.org/?probe=2898aebf10) | Feb 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| Dell          | Latitude E7250              | Notebook    | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [3797cf0990](https://linux-hardware.org/?probe=3797cf0990) | Feb 07, 2023 |
| ASUSTek       | EB1501P                     | Desktop     | [687e52dcb1](https://linux-hardware.org/?probe=687e52dcb1) | Feb 06, 2023 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [e553ba2549](https://linux-hardware.org/?probe=e553ba2549) | Feb 06, 2023 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [d888ff5291](https://linux-hardware.org/?probe=d888ff5291) | Feb 06, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [0c6df9267b](https://linux-hardware.org/?probe=0c6df9267b) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [452216b5ed](https://linux-hardware.org/?probe=452216b5ed) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | Notebook    | [bbe182e4c2](https://linux-hardware.org/?probe=bbe182e4c2) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [f265a0e81e](https://linux-hardware.org/?probe=f265a0e81e) | Feb 04, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [9e2380e15d](https://linux-hardware.org/?probe=9e2380e15d) | Feb 03, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [fac45201b3](https://linux-hardware.org/?probe=fac45201b3) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [1752779e0c](https://linux-hardware.org/?probe=1752779e0c) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [ef707954b8](https://linux-hardware.org/?probe=ef707954b8) | Feb 02, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [6e089e22b1](https://linux-hardware.org/?probe=6e089e22b1) | Feb 01, 2023 |
| Dell          | Latitude 7420               | Notebook    | [f0b8816283](https://linux-hardware.org/?probe=f0b8816283) | Feb 01, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [431a6c7a3a](https://linux-hardware.org/?probe=431a6c7a3a) | Feb 01, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [f1a9c37047](https://linux-hardware.org/?probe=f1a9c37047) | Jan 31, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [fe2a413caa](https://linux-hardware.org/?probe=fe2a413caa) | Jan 31, 2023 |
| Dell          | Latitude 7420               | Notebook    | [55f81648a1](https://linux-hardware.org/?probe=55f81648a1) | Jan 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| Dell          | Latitude D630C              | Notebook    | [401357bc99](https://linux-hardware.org/?probe=401357bc99) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | Notebook    | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [f01366b131](https://linux-hardware.org/?probe=f01366b131) | Jan 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [54ba66711b](https://linux-hardware.org/?probe=54ba66711b) | Jan 26, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [756bf12bd7](https://linux-hardware.org/?probe=756bf12bd7) | Jan 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [c4a13a66ed](https://linux-hardware.org/?probe=c4a13a66ed) | Jan 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [cb00a3e89d](https://linux-hardware.org/?probe=cb00a3e89d) | Jan 24, 2023 |
| Google        | Link                        | Notebook    | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [1a9bed0cf3](https://linux-hardware.org/?probe=1a9bed0cf3) | Jan 23, 2023 |
| Dell          | 0Y56T3 A00                  | Desktop     | [7078ea91e9](https://linux-hardware.org/?probe=7078ea91e9) | Jan 22, 2023 |
| AZW           | GTR V01                     | Mini pc     | [1d4c2002d5](https://linux-hardware.org/?probe=1d4c2002d5) | Jan 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [9792de46ad](https://linux-hardware.org/?probe=9792de46ad) | Jan 22, 2023 |
| AMI           | Intel                       | Notebook    | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fa1f3d8e3b](https://linux-hardware.org/?probe=fa1f3d8e3b) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [1d10977303](https://linux-hardware.org/?probe=1d10977303) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [fdbbb4a832](https://linux-hardware.org/?probe=fdbbb4a832) | Jan 21, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [80e51b3319](https://linux-hardware.org/?probe=80e51b3319) | Jan 20, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [d7e7799006](https://linux-hardware.org/?probe=d7e7799006) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [e221c08388](https://linux-hardware.org/?probe=e221c08388) | Jan 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [d2bb65ed09](https://linux-hardware.org/?probe=d2bb65ed09) | Jan 18, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [6d6698b316](https://linux-hardware.org/?probe=6d6698b316) | Jan 18, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [8bfae8a964](https://linux-hardware.org/?probe=8bfae8a964) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0e57f4ecbe](https://linux-hardware.org/?probe=0e57f4ecbe) | Jan 15, 2023 |
| Star Labs     | StarBook                    | Notebook    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [5b26575c52](https://linux-hardware.org/?probe=5b26575c52) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [0533348a3f](https://linux-hardware.org/?probe=0533348a3f) | Jan 14, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [b0308f4270](https://linux-hardware.org/?probe=b0308f4270) | Jan 13, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [bb85f0bdc7](https://linux-hardware.org/?probe=bb85f0bdc7) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [262fe40796](https://linux-hardware.org/?probe=262fe40796) | Jan 12, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [18bdf2650e](https://linux-hardware.org/?probe=18bdf2650e) | Jan 12, 2023 |
| ASUSTek       | GA15DH                      | Desktop     | [e480a3bfa3](https://linux-hardware.org/?probe=e480a3bfa3) | Jan 11, 2023 |
| Dell          | Studio 1749                 | Notebook    | [28a19b2c03](https://linux-hardware.org/?probe=28a19b2c03) | Jan 11, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [7697ff8cb4](https://linux-hardware.org/?probe=7697ff8cb4) | Jan 11, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | Desktop     | [994306b125](https://linux-hardware.org/?probe=994306b125) | Jan 11, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [72bf3e7a8b](https://linux-hardware.org/?probe=72bf3e7a8b) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [aacfe1b351](https://linux-hardware.org/?probe=aacfe1b351) | Jan 11, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [5cfaf7d715](https://linux-hardware.org/?probe=5cfaf7d715) | Jan 10, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [59155b3092](https://linux-hardware.org/?probe=59155b3092) | Jan 10, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [ac85316fc2](https://linux-hardware.org/?probe=ac85316fc2) | Jan 09, 2023 |
| MSI           | GP60 2PE                    | Notebook    | [e1506ca6f6](https://linux-hardware.org/?probe=e1506ca6f6) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [980ee9f42c](https://linux-hardware.org/?probe=980ee9f42c) | Jan 07, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [be1be100c9](https://linux-hardware.org/?probe=be1be100c9) | Jan 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [e64152748d](https://linux-hardware.org/?probe=e64152748d) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Samsung       | R530/R730                   | Notebook    | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Dell          | Precision M90               | Notebook    | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a24229bc3b](https://linux-hardware.org/?probe=a24229bc3b) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2849ffe456](https://linux-hardware.org/?probe=2849ffe456) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [77cc17c28c](https://linux-hardware.org/?probe=77cc17c28c) | Jan 02, 2023 |
| Foxconn       | 2AAF                        | Desktop     | [813a45dc50](https://linux-hardware.org/?probe=813a45dc50) | Jan 01, 2023 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [de65990b87](https://linux-hardware.org/?probe=de65990b87) | Jan 01, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [273f6722e0](https://linux-hardware.org/?probe=273f6722e0) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [34cd286c5f](https://linux-hardware.org/?probe=34cd286c5f) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [15c60654b3](https://linux-hardware.org/?probe=15c60654b3) | Dec 30, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [87d0f67d84](https://linux-hardware.org/?probe=87d0f67d84) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [b89e7eb1c9](https://linux-hardware.org/?probe=b89e7eb1c9) | Dec 28, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [f37619077b](https://linux-hardware.org/?probe=f37619077b) | Dec 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e979df032a](https://linux-hardware.org/?probe=e979df032a) | Dec 26, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [82a5aa7ead](https://linux-hardware.org/?probe=82a5aa7ead) | Dec 26, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [2ef0101186](https://linux-hardware.org/?probe=2ef0101186) | Dec 25, 2022 |
| GMKtec        | NucBox8                     | Server      | [abc999a1a4](https://linux-hardware.org/?probe=abc999a1a4) | Dec 24, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| Dell          | Latitude 3380               | Notebook    | [e4847d5b1f](https://linux-hardware.org/?probe=e4847d5b1f) | Dec 24, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [92f12e3ec7](https://linux-hardware.org/?probe=92f12e3ec7) | Dec 24, 2022 |
| GMKtec        | NucBox8                     | Server      | [66b0fbce86](https://linux-hardware.org/?probe=66b0fbce86) | Dec 24, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [3237ff6784](https://linux-hardware.org/?probe=3237ff6784) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [ba82bee4c7](https://linux-hardware.org/?probe=ba82bee4c7) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [a2a2f20ef4](https://linux-hardware.org/?probe=a2a2f20ef4) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92515d8a95](https://linux-hardware.org/?probe=92515d8a95) | Dec 21, 2022 |
| Schenker      | XMG APEX 15 MAX (E22)       | Notebook    | [6b46538fea](https://linux-hardware.org/?probe=6b46538fea) | Dec 21, 2022 |
| Dell          | 0020HJ A01                  | Server      | [e266254c60](https://linux-hardware.org/?probe=e266254c60) | Dec 21, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [5477e8f714](https://linux-hardware.org/?probe=5477e8f714) | Dec 21, 2022 |
| Dell          | Latitude 3380               | Notebook    | [808c693271](https://linux-hardware.org/?probe=808c693271) | Dec 20, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [8a09a51987](https://linux-hardware.org/?probe=8a09a51987) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4fbc0ddbd5](https://linux-hardware.org/?probe=4fbc0ddbd5) | Dec 20, 2022 |
| HP            | 18E7                        | Desktop     | [31011a35a4](https://linux-hardware.org/?probe=31011a35a4) | Dec 17, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [3b48a01ef2](https://linux-hardware.org/?probe=3b48a01ef2) | Dec 16, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ffa7e28596](https://linux-hardware.org/?probe=ffa7e28596) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [143d2059a6](https://linux-hardware.org/?probe=143d2059a6) | Dec 16, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [bc3635620b](https://linux-hardware.org/?probe=bc3635620b) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [888e6092a6](https://linux-hardware.org/?probe=888e6092a6) | Dec 15, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [5248ee7dbe](https://linux-hardware.org/?probe=5248ee7dbe) | Dec 15, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [3403282c8c](https://linux-hardware.org/?probe=3403282c8c) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | Desktop     | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a0d408fecd](https://linux-hardware.org/?probe=a0d408fecd) | Dec 15, 2022 |
| Dell          | Latitude E7240              | Notebook    | [c47fc4fadf](https://linux-hardware.org/?probe=c47fc4fadf) | Dec 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6b47a036ab](https://linux-hardware.org/?probe=6b47a036ab) | Dec 14, 2022 |
| Insyde        | G0975                       | Notebook    | [1f4823542d](https://linux-hardware.org/?probe=1f4823542d) | Dec 14, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [39a9464c10](https://linux-hardware.org/?probe=39a9464c10) | Dec 14, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5a9654c743](https://linux-hardware.org/?probe=5a9654c743) | Dec 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4a3ac966fc](https://linux-hardware.org/?probe=4a3ac966fc) | Dec 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [05ffc0ef7a](https://linux-hardware.org/?probe=05ffc0ef7a) | Dec 13, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [502792fe8a](https://linux-hardware.org/?probe=502792fe8a) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [7b8b3c2a86](https://linux-hardware.org/?probe=7b8b3c2a86) | Dec 12, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [65c6c18ffe](https://linux-hardware.org/?probe=65c6c18ffe) | Dec 12, 2022 |
| Dell          | Latitude 5430               | Notebook    | [b439d1e1a4](https://linux-hardware.org/?probe=b439d1e1a4) | Dec 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| Google        | Orco                        | Notebook    | [40acd3207e](https://linux-hardware.org/?probe=40acd3207e) | Dec 10, 2022 |
| Google        | Orco                        | Notebook    | [9c369b40b3](https://linux-hardware.org/?probe=9c369b40b3) | Dec 10, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3a91c2e245](https://linux-hardware.org/?probe=3a91c2e245) | Dec 07, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | Notebook    | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [310ff494e7](https://linux-hardware.org/?probe=310ff494e7) | Dec 06, 2022 |
| HP            | 18E5                        | Desktop     | [9158a7ab6b](https://linux-hardware.org/?probe=9158a7ab6b) | Dec 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | Notebook    | [d01d1e9652](https://linux-hardware.org/?probe=d01d1e9652) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [ff90421b87](https://linux-hardware.org/?probe=ff90421b87) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [3bc6ea9cfa](https://linux-hardware.org/?probe=3bc6ea9cfa) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [aaed16d626](https://linux-hardware.org/?probe=aaed16d626) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [cd63efdbd4](https://linux-hardware.org/?probe=cd63efdbd4) | Dec 05, 2022 |
| SiYW          | V200 Series                 | Desktop     | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| Sony          | VPCEB1M1E                   | Notebook    | [7ea8161a05](https://linux-hardware.org/?probe=7ea8161a05) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [d8d5459ad6](https://linux-hardware.org/?probe=d8d5459ad6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [1dddd99280](https://linux-hardware.org/?probe=1dddd99280) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F10034MX    | Notebook    | [34842eb8d9](https://linux-hardware.org/?probe=34842eb8d9) | Dec 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | Notebook    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [258c074e40](https://linux-hardware.org/?probe=258c074e40) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [29ec19d38e](https://linux-hardware.org/?probe=29ec19d38e) | Nov 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [997ffc40f0](https://linux-hardware.org/?probe=997ffc40f0) | Nov 29, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [efacbf6215](https://linux-hardware.org/?probe=efacbf6215) | Nov 29, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [85ac938c0c](https://linux-hardware.org/?probe=85ac938c0c) | Nov 29, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [96b383097b](https://linux-hardware.org/?probe=96b383097b) | Nov 29, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Sweden/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 273       | 11.03%  |
| Ubuntu 22.04                 | 167       | 6.75%   |
| Ubuntu 18.04                 | 131       | 5.29%   |
| Arch Rolling                 | 68        | 2.75%   |
| Pop!_OS 22.04                | 61        | 2.46%   |
| Debian 11                    | 56        | 2.26%   |
| Manjaro                      | 51        | 2.06%   |
| Pop!_OS 21.04                | 49        | 1.98%   |
| Zorin 16                     | 45        | 1.82%   |
| Debian 12                    | 44        | 1.78%   |
| OpenMandriva 4.3             | 41        | 1.66%   |
| Arch                         | 40        | 1.62%   |
| OpenMandriva 4.2             | 39        | 1.58%   |
| ArcoLinux Rolling            | 39        | 1.58%   |
| KDE neon 20.04               | 38        | 1.54%   |
| Linux Mint 21.1              | 33        | 1.33%   |
| openSUSE Tumbleweed-XXXXXXXX | 32        | 1.29%   |
| Linux Mint 20.3              | 32        | 1.29%   |
| Pop!_OS 20.04                | 31        | 1.25%   |
| Fedora 38                    | 30        | 1.21%   |
| Ubuntu 21.10                 | 29        | 1.17%   |
| Ubuntu 21.04                 | 29        | 1.17%   |
| Pop!_OS 20.10                | 29        | 1.17%   |
| Fedora 37                    | 29        | 1.17%   |
| Fedora 35                    | 29        | 1.17%   |
| Ubuntu 19.04                 | 27        | 1.09%   |
| Fedora 34                    | 25        | 1.01%   |
| Ubuntu 19.10                 | 24        | 0.97%   |
| Fedora 36                    | 23        | 0.93%   |
| Fedora 32                    | 23        | 0.93%   |
| Zorin 15                     | 22        | 0.89%   |
| Ubuntu 23.04                 | 21        | 0.85%   |
| EndeavourOS Rolling          | 21        | 0.85%   |
| Xubuntu 20.04                | 20        | 0.81%   |
| Linux Mint 21.2              | 20        | 0.81%   |
| Linux Mint 20.2              | 20        | 0.81%   |
| Linux Mint 20                | 20        | 0.81%   |
| Ubuntu 20.10                 | 19        | 0.77%   |
| Fedora 33                    | 19        | 0.77%   |
| Ubuntu 22.10                 | 17        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 728       | 30.89%  |
| Fedora        | 194       | 8.23%   |
| Linux Mint    | 179       | 7.59%   |
| Pop!_OS       | 175       | 7.42%   |
| Debian        | 133       | 5.64%   |
| OpenMandriva  | 123       | 5.22%   |
| Arch          | 107       | 4.54%   |
| Manjaro       | 103       | 4.37%   |
| Zorin         | 68        | 2.89%   |
| KDE neon      | 51        | 2.16%   |
| Xubuntu       | 45        | 1.91%   |
| ArcoLinux     | 44        | 1.87%   |
| openSUSE      | 39        | 1.65%   |
| Kubuntu       | 35        | 1.48%   |
| Gentoo        | 35        | 1.48%   |
| Kali          | 25        | 1.06%   |
| EndeavourOS   | 25        | 1.06%   |
| ROSA          | 20        | 0.85%   |
| Elementary    | 18        | 0.76%   |
| Ubuntu MATE   | 16        | 0.68%   |
| CentOS        | 14        | 0.59%   |
| Nobara        | 12        | 0.51%   |
| Clear Linux   | 12        | 0.51%   |
| SteamOS       | 10        | 0.42%   |
| Endless       | 10        | 0.42%   |
| MX            | 9         | 0.38%   |
| Lubuntu       | 9         | 0.38%   |
| LMDE          | 9         | 0.38%   |
| Garuda Linux  | 9         | 0.38%   |
| Ubuntu Unity  | 8         | 0.34%   |
| Ubuntu Budgie | 6         | 0.25%   |
| Peppermint    | 6         | 0.25%   |
| Parrot        | 6         | 0.25%   |
| BunsenLabs    | 6         | 0.25%   |
| Solus         | 5         | 0.21%   |
| Alpine        | 5         | 0.21%   |
| Slackware     | 4         | 0.17%   |
| Raspbian      | 4         | 0.17%   |
| NixOS         | 4         | 0.17%   |
| BlackPanther  | 4         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 39        | 1.43%   |
| 5.10.14-desktop-1omv4002 | 39        | 1.43%   |
| 5.4.0-42-generic         | 33        | 1.21%   |
| 5.15.0-56-generic        | 29        | 1.07%   |
| 5.4.0-58-generic         | 21        | 0.77%   |
| 5.4.0-48-generic         | 20        | 0.73%   |
| 5.15.0-52-generic        | 19        | 0.7%    |
| 5.11.0-7620-generic      | 19        | 0.7%    |
| 5.3.0-40-generic         | 17        | 0.62%   |
| 5.13.0-7614-generic      | 17        | 0.62%   |
| 5.4.0-52-generic         | 16        | 0.59%   |
| 5.15.0-46-generic        | 15        | 0.55%   |
| 5.13.0-30-generic        | 15        | 0.55%   |
| 5.4.0-40-generic         | 14        | 0.51%   |
| 5.15.0-58-generic        | 14        | 0.51%   |
| 5.13.0-39-generic        | 14        | 0.51%   |
| 6.2.6-76060206-generic   | 13        | 0.48%   |
| 5.4.0-7634-generic       | 13        | 0.48%   |
| 5.15.0-48-generic        | 13        | 0.48%   |
| 6.2.6-desktop-1omv2390   | 12        | 0.44%   |
| 5.4.0-54-generic         | 12        | 0.44%   |
| 5.4.0-33-generic         | 12        | 0.44%   |
| 5.15.0-78-generic        | 12        | 0.44%   |
| 5.15.0-53-generic        | 12        | 0.44%   |
| 5.11.0-37-generic        | 12        | 0.44%   |
| 6.1.0-7-amd64            | 11        | 0.4%    |
| 5.8.0-48-generic         | 11        | 0.4%    |
| 5.4.0-70-generic         | 11        | 0.4%    |
| 5.19.0-35-generic        | 11        | 0.4%    |
| 5.15.0-76-generic        | 11        | 0.4%    |
| 5.15.0-60-generic        | 11        | 0.4%    |
| 5.15.0-50-generic        | 11        | 0.4%    |
| 5.11.0-7614-generic      | 11        | 0.4%    |
| 5.10.0-8-amd64           | 11        | 0.4%    |
| 6.2.0-20-generic         | 10        | 0.37%   |
| 6.1.0-9-amd64            | 10        | 0.37%   |
| 5.8.0-43-generic         | 10        | 0.37%   |
| 5.4.0-65-generic         | 10        | 0.37%   |
| 5.4.0-29-generic         | 10        | 0.37%   |
| 5.19.0-38-generic        | 10        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 342       | 13.18%  |
| 5.15.0  | 239       | 9.21%   |
| 5.11.0  | 129       | 4.97%   |
| 5.13.0  | 121       | 4.66%   |
| 5.8.0   | 98        | 3.78%   |
| 4.15.0  | 82        | 3.16%   |
| 5.3.0   | 76        | 2.93%   |
| 5.10.0  | 76        | 2.93%   |
| 5.19.0  | 74        | 2.85%   |
| 6.2.0   | 66        | 2.54%   |
| 6.1.0   | 62        | 2.39%   |
| 5.0.0   | 59        | 2.27%   |
| 4.18.0  | 47        | 1.81%   |
| 5.16.7  | 40        | 1.54%   |
| 5.10.14 | 40        | 1.54%   |
| 6.2.6   | 26        | 1%      |
| 6.5.0   | 17        | 0.66%   |
| 6.5.6   | 15        | 0.58%   |
| 5.14.0  | 14        | 0.54%   |
| 5.17.5  | 13        | 0.5%    |
| 6.1.1   | 12        | 0.46%   |
| 6.6.7   | 11        | 0.42%   |
| 6.4.11  | 11        | 0.42%   |
| 4.19.0  | 11        | 0.42%   |
| 6.2.9   | 10        | 0.39%   |
| 6.0.12  | 10        | 0.39%   |
| 5.18.0  | 10        | 0.39%   |
| 5.12.4  | 10        | 0.39%   |
| 5.17.1  | 9         | 0.35%   |
| 6.6.2   | 8         | 0.31%   |
| 6.4.0   | 8         | 0.31%   |
| 5.16.0  | 8         | 0.31%   |
| 6.5.7   | 7         | 0.27%   |
| 6.3.1   | 7         | 0.27%   |
| 6.1.12  | 7         | 0.27%   |
| 6.1.11  | 7         | 0.27%   |
| 5.7.0   | 7         | 0.27%   |
| 5.19.16 | 7         | 0.27%   |
| 5.15.7  | 7         | 0.27%   |
| 6.5.5   | 6         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 372       | 14.61%  |
| 5.15    | 305       | 11.97%  |
| 5.10    | 163       | 6.4%    |
| 5.11    | 158       | 6.2%    |
| 5.13    | 141       | 5.54%   |
| 5.8     | 135       | 5.3%    |
| 6.1     | 124       | 4.87%   |
| 6.2     | 123       | 4.83%   |
| 5.19    | 92        | 3.61%   |
| 5.3     | 88        | 3.46%   |
| 4.15    | 82        | 3.22%   |
| 5.16    | 81        | 3.18%   |
| 5.0     | 62        | 2.43%   |
| 6.5     | 61        | 2.39%   |
| 4.18    | 54        | 2.12%   |
| 6.4     | 52        | 2.04%   |
| 5.17    | 48        | 1.88%   |
| 6.0     | 46        | 1.81%   |
| 6.3     | 41        | 1.61%   |
| 5.18    | 37        | 1.45%   |
| 5.14    | 36        | 1.41%   |
| 5.12    | 36        | 1.41%   |
| 6.6     | 35        | 1.37%   |
| 5.9     | 33        | 1.3%    |
| 5.6     | 28        | 1.1%    |
| 5.7     | 24        | 0.94%   |
| 4.19    | 23        | 0.9%    |
| 4.9     | 16        | 0.63%   |
| 5.5     | 15        | 0.59%   |
| 5.1     | 7         | 0.27%   |
| 5.2     | 6         | 0.24%   |
| 4.4     | 6         | 0.24%   |
| 4.14    | 3         | 0.12%   |
| 4.1     | 3         | 0.12%   |
| 4.20    | 2         | 0.08%   |
| 4.12    | 2         | 0.08%   |
| 3.10    | 2         | 0.08%   |
| 6.7     | 1         | 0.04%   |
| 5       | 1         | 0.04%   |
| 4.16    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2211      | 97.83%  |
| i686    | 25        | 1.11%   |
| aarch64 | 16        | 0.71%   |
| armv7l  | 6         | 0.27%   |
| i586    | 1         | 0.04%   |
| armv8l  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1112      | 46.78%  |
| KDE5            | 348       | 14.64%  |
| Unknown         | 290       | 12.2%   |
| XFCE            | 184       | 7.74%   |
| X-Cinnamon      | 152       | 6.39%   |
| KDE             | 71        | 2.99%   |
| MATE            | 47        | 1.98%   |
| i3              | 20        | 0.84%   |
| Cinnamon        | 20        | 0.84%   |
| LXQt            | 18        | 0.76%   |
| Pantheon        | 17        | 0.72%   |
| LXDE            | 14        | 0.59%   |
| KDE4            | 11        | 0.46%   |
| Budgie          | 10        | 0.42%   |
| Unity           | 9         | 0.38%   |
| Deepin          | 7         | 0.29%   |
| sway            | 6         | 0.25%   |
| awesome         | 6         | 0.25%   |
| GNOME Flashback | 5         | 0.21%   |
| GNOME Classic   | 5         | 0.21%   |
| openbox         | 4         | 0.17%   |
| Hyprland        | 3         | 0.13%   |
| DWM             | 3         | 0.13%   |
| BunsenLabs      | 3         | 0.13%   |
| qtile           | 2         | 0.08%   |
| LeftWM          | 2         | 0.08%   |
| xmonad          | 1         | 0.04%   |
| Trinity         | 1         | 0.04%   |
| spectrwm        | 1         | 0.04%   |
| none+awesome    | 1         | 0.04%   |
| GNOME-Flashback | 1         | 0.04%   |
| Enlightenment   | 1         | 0.04%   |
| DDE             | 1         | 0.04%   |
| bspwm           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1644      | 70.56%  |
| Wayland     | 462       | 19.83%  |
| Unknown     | 140       | 6.01%   |
| Tty         | 83        | 3.56%   |
| Unspecified | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1175      | 49.68%  |
| SDDM    | 313       | 13.23%  |
| GDM3    | 305       | 12.9%   |
| GDM     | 251       | 10.61%  |
| LightDM | 226       | 9.56%   |
| TDM     | 63        | 2.66%   |
| KDM     | 11        | 0.47%   |
| XDM     | 7         | 0.3%    |
| LXDM    | 7         | 0.3%    |
| Ly      | 6         | 0.25%   |
| GREETD  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1128      | 48.43%  |
| sv_SE       | 640       | 27.48%  |
| Unknown     | 233       | 10%     |
| en_GB       | 151       | 6.48%   |
| C           | 58        | 2.49%   |
| de_DE       | 18        | 0.77%   |
| ru_RU       | 17        | 0.73%   |
| en_SE       | 8         | 0.34%   |
| pl_PL       | 7         | 0.3%    |
| en_DK       | 7         | 0.3%    |
| uk_UA       | 4         | 0.17%   |
| nb_NO       | 4         | 0.17%   |
| fr_FR       | 4         | 0.17%   |
| en_IE       | 4         | 0.17%   |
| en_CA       | 4         | 0.17%   |
| POSIX       | 3         | 0.13%   |
| fi_FI       | 3         | 0.13%   |
| en_AG       | 3         | 0.13%   |
| el_GR       | 3         | 0.13%   |
| C.UTF8      | 3         | 0.13%   |
| bg_BG       | 3         | 0.13%   |
| zh_CN       | 2         | 0.09%   |
| lt_LT       | 2         | 0.09%   |
| it_IT       | 2         | 0.09%   |
| en_US.utf-8 | 2         | 0.09%   |
| UTF-8       | 1         | 0.04%   |
| tr_TR       | 1         | 0.04%   |
| sv_SE.UTF8  | 1         | 0.04%   |
| sv_FI       | 1         | 0.04%   |
| sma_SE      | 1         | 0.04%   |
| nn_NO       | 1         | 0.04%   |
| hu_HU       | 1         | 0.04%   |
| hr_HR       | 1         | 0.04%   |
| gl_ES       | 1         | 0.04%   |
| es_VE       | 1         | 0.04%   |
| es_ES       | 1         | 0.04%   |
| en_IN       | 1         | 0.04%   |
| en_GB.UTF8  | 1         | 0.04%   |
| en_GB.utf-8 | 1         | 0.04%   |
| en_AU       | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1213      | 52.24%  |
| BIOS | 1109      | 47.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1684      | 72.09%  |
| Btrfs    | 283       | 12.11%  |
| Overlay  | 147       | 6.29%   |
| Tmpfs    | 89        | 3.81%   |
| Unknown  | 59        | 2.53%   |
| Xfs      | 37        | 1.58%   |
| Zfs      | 20        | 0.86%   |
| Ext2     | 7         | 0.3%    |
| F2fs     | 6         | 0.26%   |
| Ext3     | 2         | 0.09%   |
| XXXXXXX  | 1         | 0.04%   |
| Reiserfs | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1170      | 50.02%  |
| GPT     | 970       | 41.47%  |
| MBR     | 199       | 8.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2014      | 87.34%  |
| Yes       | 292       | 12.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1752      | 76.11%  |
| Yes       | 550       | 23.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 501       | 22.17%  |
| Lenovo                  | 347       | 15.35%  |
| Hewlett-Packard         | 332       | 14.69%  |
| Dell                    | 238       | 10.53%  |
| MSI                     | 157       | 6.95%   |
| Gigabyte Technology     | 141       | 6.24%   |
| Acer                    | 112       | 4.96%   |
| Apple                   | 76        | 3.36%   |
| ASRock                  | 51        | 2.26%   |
| Intel                   | 29        | 1.28%   |
| Fujitsu                 | 21        | 0.93%   |
| Toshiba                 | 17        | 0.75%   |
| Raspberry Pi Foundation | 17        | 0.75%   |
| Sony                    | 15        | 0.66%   |
| Packard Bell            | 13        | 0.58%   |
| Unknown                 | 12        | 0.53%   |
| Samsung Electronics     | 11        | 0.49%   |
| Notebook                | 10        | 0.44%   |
| Supermicro              | 9         | 0.4%    |
| Google                  | 9         | 0.4%    |
| Valve                   | 8         | 0.35%   |
| Fujitsu Siemens         | 8         | 0.35%   |
| Microsoft               | 7         | 0.31%   |
| Foxconn                 | 7         | 0.31%   |
| Pegatron                | 6         | 0.27%   |
| HUAWEI                  | 5         | 0.22%   |
| AAEON                   | 5         | 0.22%   |
| Maxtang                 | 4         | 0.18%   |
| Alienware               | 4         | 0.18%   |
| TUXEDO                  | 3         | 0.13%   |
| Star Labs               | 3         | 0.13%   |
| Clevo                   | 3         | 0.13%   |
| Timi                    | 2         | 0.09%   |
| System76                | 2         | 0.09%   |
| Shuttle                 | 2         | 0.09%   |
| Schenker                | 2         | 0.09%   |
| Razer                   | 2         | 0.09%   |
| PC Specialist           | 2         | 0.09%   |
| OEM                     | 2         | 0.09%   |
| Linx                    | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 22        | 0.97%   |
| Unknown                            | 17        | 0.75%   |
| ASUS ROG STRIX B450-F GAMING       | 12        | 0.53%   |
| ASUS ROG STRIX X570-F GAMING       | 10        | 0.44%   |
| ASUS ROG STRIX B550-F GAMING       | 10        | 0.44%   |
| Valve Jupiter                      | 8         | 0.35%   |
| MSI MS-7C37                        | 8         | 0.35%   |
| ASUS PRIME X470-PRO                | 8         | 0.35%   |
| Dell XPS 13 9370                   | 7         | 0.31%   |
| Dell XPS 13 9310                   | 7         | 0.31%   |
| ASUS Z170 PRO GAMING               | 7         | 0.31%   |
| MSI MS-7C02                        | 6         | 0.27%   |
| HP EliteBook Folio 9470m           | 6         | 0.27%   |
| Dell Precision 5540                | 6         | 0.27%   |
| Apple MacBookPro9,2                | 6         | 0.27%   |
| Apple MacBookAir7,2                | 6         | 0.27%   |
| Acer Aspire V3-571                 | 6         | 0.27%   |
| MSI MS-7C52                        | 5         | 0.22%   |
| MSI MS-7817                        | 5         | 0.22%   |
| Lenovo Yoga C740-14IML 81TC        | 5         | 0.22%   |
| Lenovo MIIX 310-10ICR 80SG         | 5         | 0.22%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5   | 5         | 0.22%   |
| HP ProBook 640 G1                  | 5         | 0.22%   |
| HP Pavilion dv7                    | 5         | 0.22%   |
| HP Pavilion 15                     | 5         | 0.22%   |
| HP EliteBook 840 G3                | 5         | 0.22%   |
| HP EliteBook 840 G2                | 5         | 0.22%   |
| Gigabyte B550 AORUS ELITE V2       | 5         | 0.22%   |
| Gigabyte B450M DS3H                | 5         | 0.22%   |
| Dell XPS 15 9570                   | 5         | 0.22%   |
| Dell OptiPlex 7010                 | 5         | 0.22%   |
| ASUS TUF Gaming X570-PLUS          | 5         | 0.22%   |
| ASUS ROG STRIX Z390-F GAMING       | 5         | 0.22%   |
| ASUS ROG STRIX B550-I GAMING       | 5         | 0.22%   |
| ASUS ROG STRIX B350-F GAMING       | 5         | 0.22%   |
| ASUS PRIME X370-PRO                | 5         | 0.22%   |
| ASUS M5A97 R2.0                    | 5         | 0.22%   |
| Apple MacBookPro8,1                | 5         | 0.22%   |
| Apple MacBookPro11,3               | 5         | 0.22%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 4         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 190       | 8.41%   |
| ASUS ROG              | 117       | 5.18%   |
| HP EliteBook          | 92        | 4.07%   |
| Dell Latitude         | 70        | 3.1%    |
| Acer Aspire           | 69        | 3.05%   |
| ASUS PRIME            | 59        | 2.61%   |
| Dell Precision        | 54        | 2.39%   |
| Dell XPS              | 50        | 2.21%   |
| HP Pavilion           | 45        | 1.99%   |
| Lenovo IdeaPad        | 43        | 1.9%    |
| HP ProBook            | 43        | 1.9%    |
| Dell OptiPlex         | 33        | 1.46%   |
| Lenovo Yoga           | 29        | 1.28%   |
| HP Compaq             | 28        | 1.24%   |
| ASUS TUF              | 25        | 1.11%   |
| ASUS VivoBook         | 23        | 1.02%   |
| ASUS All              | 22        | 0.97%   |
| HP ZBook              | 21        | 0.93%   |
| HP Laptop             | 19        | 0.84%   |
| HP ENVY               | 18        | 0.8%    |
| RPi Raspberry         | 17        | 0.75%   |
| Unknown               | 17        | 0.75%   |
| Toshiba Satellite     | 14        | 0.62%   |
| HP EliteDesk          | 13        | 0.58%   |
| Dell Inspiron         | 13        | 0.58%   |
| ASUS ZenBook          | 13        | 0.58%   |
| Acer Swift            | 13        | 0.58%   |
| Lenovo Legion         | 12        | 0.53%   |
| Lenovo ThinkCentre    | 11        | 0.49%   |
| Gigabyte X570         | 11        | 0.49%   |
| Dell Vostro           | 11        | 0.49%   |
| ASUS P8Z77-V          | 10        | 0.44%   |
| Acer Predator         | 10        | 0.44%   |
| Packard Bell EasyNote | 9         | 0.4%    |
| Lenovo IdeaCentre     | 9         | 0.4%    |
| Fujitsu LIFEBOOK      | 9         | 0.4%    |
| ASUS STRIX            | 9         | 0.4%    |
| ASUS SABERTOOTH       | 9         | 0.4%    |
| ASUS ASUS             | 9         | 0.4%    |
| Valve Jupiter         | 8         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 229       | 10.13%  |
| 2019    | 217       | 9.6%    |
| 2020    | 200       | 8.85%   |
| 2021    | 169       | 7.48%   |
| 2013    | 164       | 7.26%   |
| 2012    | 163       | 7.21%   |
| 2017    | 158       | 6.99%   |
| 2011    | 157       | 6.95%   |
| 2015    | 130       | 5.75%   |
| 2014    | 126       | 5.58%   |
| 2016    | 120       | 5.31%   |
| 2022    | 98        | 4.34%   |
| 2010    | 97        | 4.29%   |
| 2008    | 60        | 2.65%   |
| 2009    | 57        | 2.52%   |
| 2007    | 47        | 2.08%   |
| 2023    | 30        | 1.33%   |
| Unknown | 16        | 0.71%   |
| 2006    | 11        | 0.49%   |
| 2005    | 8         | 0.35%   |
| 2004    | 2         | 0.09%   |
| 2002    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1170      | 51.77%  |
| Desktop        | 899       | 39.78%  |
| Convertible    | 66        | 2.92%   |
| Mini pc        | 46        | 2.04%   |
| All in one     | 21        | 0.93%   |
| System on chip | 20        | 0.88%   |
| Tablet         | 19        | 0.84%   |
| Server         | 16        | 0.71%   |
| Phone          | 3         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2071      | 91.11%  |
| Enabled  | 202       | 8.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2246      | 99.38%  |
| Yes  | 14        | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 539       | 23.51%  |
| 4.01-8.0        | 492       | 21.46%  |
| 8.01-16.0       | 388       | 16.92%  |
| 32.01-64.0      | 362       | 15.79%  |
| 3.01-4.0        | 284       | 12.39%  |
| 64.01-256.0     | 84        | 3.66%   |
| 1.01-2.0        | 61        | 2.66%   |
| 24.01-32.0      | 46        | 2.01%   |
| 0.51-1.0        | 17        | 0.74%   |
| 2.01-3.0        | 16        | 0.7%    |
| More than 256.0 | 3         | 0.13%   |
| 0.01-0.5        | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 764       | 30.49%  |
| 2.01-3.0    | 608       | 24.26%  |
| 4.01-8.0    | 476       | 18.99%  |
| 3.01-4.0    | 353       | 14.09%  |
| 8.01-16.0   | 136       | 5.43%   |
| 0.51-1.0    | 105       | 4.19%   |
| 16.01-24.0  | 30        | 1.2%    |
| 0.01-0.5    | 24        | 0.96%   |
| 24.01-32.0  | 6         | 0.24%   |
| 32.01-64.0  | 2         | 0.08%   |
| 64.01-256.0 | 1         | 0.04%   |
| Unknown     | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1389      | 59.51%  |
| 2      | 499       | 21.38%  |
| 3      | 198       | 8.48%   |
| 4      | 113       | 4.84%   |
| 5      | 49        | 2.1%    |
| 6      | 35        | 1.5%    |
| 0      | 22        | 0.94%   |
| 7      | 18        | 0.77%   |
| 8      | 6         | 0.26%   |
| 10     | 2         | 0.09%   |
| 26     | 1         | 0.04%   |
| 11     | 1         | 0.04%   |
| 9      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1567      | 68.97%  |
| Yes       | 705       | 31.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1945      | 85.83%  |
| No        | 321       | 14.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1662      | 72.93%  |
| No        | 617       | 27.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1428      | 62.28%  |
| No        | 865       | 37.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 2260      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Stockholm               | 448       | 18.31%  |
| Gothenburg              | 244       | 9.97%   |
| Malmo                   | 119       | 4.86%   |
| Uppsala                 | 67        | 2.74%   |
| Lund                    | 50        | 2.04%   |
| Linköping              | 44        | 1.8%    |
| Västerås              | 42        | 1.72%   |
| Umeå                   | 32        | 1.31%   |
| Bromma                  | 32        | 1.31%   |
| Solna                   | 30        | 1.23%   |
| Sollentuna              | 30        | 1.23%   |
| Norrköping             | 27        | 1.1%    |
| Örebro                 | 26        | 1.06%   |
| Vaxjo                   | 25        | 1.02%   |
| Sundsvall               | 25        | 1.02%   |
| Saltsjoe-Boo            | 25        | 1.02%   |
| Karlstad                | 22        | 0.9%    |
| Sundbyberg              | 21        | 0.86%   |
| Karlskrona              | 20        | 0.82%   |
| Vaestra Froelunda       | 19        | 0.78%   |
| Helsingborg             | 19        | 0.78%   |
| Haegersten              | 19        | 0.78%   |
| Huddinge                | 18        | 0.74%   |
| Taby                    | 17        | 0.69%   |
| Bandhagen               | 17        | 0.69%   |
| Södertälje            | 15        | 0.61%   |
| Nyköping               | 15        | 0.61%   |
| Gävle                  | 15        | 0.61%   |
| Norsborg                | 14        | 0.57%   |
| Kista                   | 14        | 0.57%   |
| Halmstad                | 14        | 0.57%   |
| Spanga                  | 13        | 0.53%   |
| Moelndal                | 13        | 0.53%   |
| Staffanstorp            | 12        | 0.49%   |
| Järfälla Municipality | 12        | 0.49%   |
| Skövde                 | 11        | 0.45%   |
| Landskrona              | 11        | 0.45%   |
| Katrineholm             | 11        | 0.45%   |
| Jönköping             | 11        | 0.45%   |
| Upplands Vasby          | 10        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 755       | 1232   | 22.36%  |
| WDC                         | 439       | 712    | 13%     |
| Seagate                     | 400       | 649    | 11.84%  |
| Kingston                    | 267       | 384    | 7.91%   |
| Intel                       | 183       | 237    | 5.42%   |
| SanDisk                     | 168       | 214    | 4.97%   |
| Toshiba                     | 163       | 216    | 4.83%   |
| Unknown                     | 118       | 151    | 3.49%   |
| SK hynix                    | 98        | 112    | 2.9%    |
| Hitachi                     | 92        | 128    | 2.72%   |
| Crucial                     | 84        | 121    | 2.49%   |
| Micron Technology           | 76        | 90     | 2.25%   |
| HGST                        | 54        | 64     | 1.6%    |
| Apple                       | 41        | 49     | 1.21%   |
| Kingston Technology Company | 32        | 41     | 0.95%   |
| Corsair                     | 28        | 38     | 0.83%   |
| Phison                      | 23        | 28     | 0.68%   |
| OCZ                         | 23        | 29     | 0.68%   |
| KIOXIA                      | 23        | 24     | 0.68%   |
| A-DATA Technology           | 23        | 24     | 0.68%   |
| LITEON                      | 20        | 27     | 0.59%   |
| Phison Electronics          | 16        | 21     | 0.47%   |
| Transcend                   | 13        | 14     | 0.38%   |
| Intenso                     | 13        | 17     | 0.38%   |
| LITEONIT                    | 12        | 20     | 0.36%   |
| Fujitsu                     | 12        | 18     | 0.36%   |
| Silicon Motion              | 11        | 29     | 0.33%   |
| Micron/Crucial Technology   | 11        | 15     | 0.33%   |
| China                       | 11        | 12     | 0.33%   |
| PNY                         | 9         | 12     | 0.27%   |
| Unknown                     | 8         | 8      | 0.24%   |
| Maxtor                      | 7         | 7      | 0.21%   |
| JMicron Technology          | 7         | 8      | 0.21%   |
| SPCC                        | 6         | 20     | 0.18%   |
| LaCie                       | 6         | 7      | 0.18%   |
| ASMT                        | 6         | 6      | 0.18%   |
| Verbatim                    | 5         | 9      | 0.15%   |
| Lenovo                      | 5         | 5      | 0.15%   |
| Patriot                     | 4         | 5      | 0.12%   |
| Hewlett-Packard             | 4         | 6      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 58        | 1.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 50        | 1.3%    |
| Samsung SSD 850 EVO 500GB                           | 46        | 1.19%   |
| Kingston SA400S37120G 120GB SSD                     | 40        | 1.04%   |
| Kingston SV300S37A120G 120GB SSD                    | 34        | 0.88%   |
| Kingston SA400S37480G 480GB SSD                     | 33        | 0.85%   |
| Kingston SA400S37240G 240GB SSD                     | 32        | 0.83%   |
| Samsung SSD 860 EVO 250GB                           | 26        | 0.67%   |
| Samsung SSD 840 EVO 250GB                           | 26        | 0.67%   |
| Samsung SSD 860 EVO 500GB                           | 25        | 0.65%   |
| Samsung NVMe SSD Drive 500GB                        | 25        | 0.65%   |
| Seagate ST4000DM004-2CV104 4TB                      | 23        | 0.6%    |
| Samsung NVMe SSD Drive 512GB                        | 20        | 0.52%   |
| Unknown MMC Card  32GB                              | 19        | 0.49%   |
| Seagate ST1000DM010-2EP102 1TB                      | 19        | 0.49%   |
| Samsung SSD 860 EVO 1TB                             | 19        | 0.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 19        | 0.49%   |
| SanDisk NVMe SSD Drive 1TB                          | 18        | 0.47%   |
| Samsung SSD 970 EVO Plus 500GB                      | 18        | 0.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB | 18        | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB                      | 17        | 0.44%   |
| Samsung NVMe SSD Drive 1TB                          | 16        | 0.41%   |
| Seagate ST1000DM003-1CH162 1TB                      | 15        | 0.39%   |
| SanDisk NVMe SSD Drive 512GB                        | 15        | 0.39%   |
| Samsung SSD 840 EVO 500GB                           | 15        | 0.39%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 15        | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 14        | 0.36%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 14        | 0.36%   |
| Seagate ST500DM002-1BD142 500GB                     | 14        | 0.36%   |
| Seagate ST2000DM006-2DM164 2TB                      | 14        | 0.36%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 14        | 0.36%   |
| Samsung SSD 970 EVO Plus 1TB                        | 14        | 0.36%   |
| HGST HTS721010A9E630 1TB                            | 14        | 0.36%   |
| Unknown SD/MMC/MS PRO 512GB                         | 13        | 0.34%   |
| Seagate ST4000VN008-2DR166 4TB                      | 13        | 0.34%   |
| Samsung SSD 840 EVO 120GB                           | 13        | 0.34%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 13        | 0.34%   |
| Toshiba NVMe SSD Drive 512GB                        | 12        | 0.31%   |
| Seagate ST9500325AS 500GB                           | 12        | 0.31%   |
| Seagate Expansion Desk 8TB                          | 12        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 394       | 634    | 36.08%  |
| WDC                 | 339       | 569    | 31.04%  |
| Hitachi             | 92        | 128    | 8.42%   |
| Toshiba             | 88        | 121    | 8.06%   |
| Samsung Electronics | 61        | 98     | 5.59%   |
| HGST                | 54        | 64     | 4.95%   |
| Unknown             | 14        | 16     | 1.28%   |
| Fujitsu             | 12        | 18     | 1.1%    |
| Apple               | 11        | 11     | 1.01%   |
| Maxtor              | 6         | 6      | 0.55%   |
| Intenso             | 3         | 3      | 0.27%   |
| ASMedia             | 3         | 3      | 0.27%   |
| Hewlett-Packard     | 2         | 4      | 0.18%   |
| ASMT                | 2         | 2      | 0.18%   |
| Unknown             | 2         | 2      | 0.18%   |
| USB3.0              | 1         | 1      | 0.09%   |
| TO Exter            | 1         | 1      | 0.09%   |
| StoreJet            | 1         | 1      | 0.09%   |
| SABRENT             | 1         | 1      | 0.09%   |
| MARVELL             | 1         | 1      | 0.09%   |
| LaCie               | 1         | 1      | 0.09%   |
| JMicron Technology  | 1         | 2      | 0.09%   |
| IB                  | 1         | 2      | 0.09%   |
| HGST HTS            | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 418       | 643    | 33.04%  |
| Kingston            | 204       | 290    | 16.13%  |
| Intel               | 105       | 135    | 8.3%    |
| Crucial             | 79        | 113    | 6.25%   |
| SanDisk             | 78        | 98     | 6.17%   |
| WDC                 | 65        | 86     | 5.14%   |
| Micron Technology   | 44        | 56     | 3.48%   |
| Apple               | 28        | 34     | 2.21%   |
| SK hynix            | 26        | 30     | 2.06%   |
| OCZ                 | 23        | 29     | 1.82%   |
| Toshiba             | 21        | 29     | 1.66%   |
| LITEON              | 19        | 26     | 1.5%    |
| Corsair             | 16        | 19     | 1.26%   |
| A-DATA Technology   | 14        | 15     | 1.11%   |
| Transcend           | 12        | 13     | 0.95%   |
| LITEONIT            | 12        | 20     | 0.95%   |
| China               | 11        | 12     | 0.87%   |
| Intenso             | 8         | 8      | 0.63%   |
| SPCC                | 6         | 20     | 0.47%   |
| PNY                 | 6         | 9      | 0.47%   |
| Verbatim            | 5         | 9      | 0.4%    |
| Patriot             | 4         | 5      | 0.32%   |
| JMicron Technology  | 4         | 4      | 0.32%   |
| ASMT                | 4         | 4      | 0.32%   |
| M4-CT128            | 3         | 3      | 0.24%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.24%   |
| Emtec               | 3         | 3      | 0.24%   |
| Seagate             | 2         | 4      | 0.16%   |
| OCZ-VERTEX3         | 2         | 2      | 0.16%   |
| KingSpec            | 2         | 2      | 0.16%   |
| INTEL SS            | 2         | 3      | 0.16%   |
| GOODRAM             | 2         | 3      | 0.16%   |
| Apacer              | 2         | 2      | 0.16%   |
| XSTAR               | 1         | 2      | 0.08%   |
| WDC WDS2            | 1         | 1      | 0.08%   |
| WDC WDS1            | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |
| tigo                | 1         | 1      | 0.08%   |
| Team                | 1         | 1      | 0.08%   |
| Star                | 1         | 1      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1075      | 1769   | 35.57%  |
| NVMe    | 909       | 1285   | 30.08%  |
| HDD     | 892       | 1690   | 29.52%  |
| MMC     | 111       | 134    | 3.67%   |
| Unknown | 35        | 45     | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1558      | 3300   | 57.49%  |
| NVMe | 908       | 1281   | 33.51%  |
| SAS  | 133       | 208    | 4.91%   |
| MMC  | 111       | 134    | 4.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1260      | 2079   | 58.93%  |
| 0.51-1.0   | 471       | 730    | 22.03%  |
| 1.01-2.0   | 202       | 307    | 9.45%   |
| 3.01-4.0   | 83        | 138    | 3.88%   |
| 2.01-3.0   | 62        | 99     | 2.9%    |
| 4.01-10.0  | 51        | 93     | 2.39%   |
| 10.01-20.0 | 9         | 13     | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 639       | 26.58%  |
| 251-500        | 523       | 21.76%  |
| 501-1000       | 320       | 13.31%  |
| 1-20           | 194       | 8.07%   |
| 1001-2000      | 192       | 7.99%   |
| More than 3000 | 179       | 7.45%   |
| 51-100         | 122       | 5.07%   |
| Unknown        | 96        | 3.99%   |
| 2001-3000      | 74        | 3.08%   |
| 21-50          | 65        | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 898       | 36.4%   |
| 21-50          | 378       | 15.32%  |
| 101-250        | 324       | 13.13%  |
| 51-100         | 265       | 10.74%  |
| 251-500        | 172       | 6.97%   |
| 501-1000       | 138       | 5.59%   |
| Unknown        | 96        | 3.89%   |
| 1001-2000      | 79        | 3.2%    |
| More than 3000 | 67        | 2.72%   |
| 2001-3000      | 48        | 1.95%   |
| 0              | 2         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 5         | 5      | 2.59%   |
| Seagate ST9250410AS 250GB                      | 3         | 4      | 1.55%   |
| Samsung Electronics SSD 870 EVO 1TB            | 3         | 3      | 1.55%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 3         | 4      | 1.55%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 1.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 2         | 2      | 1.04%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 2         | 2      | 1.04%   |
| WDC WD5000AAKX-75U6AA0 500GB                   | 2         | 2      | 1.04%   |
| WDC WD5000AAKX-22ERMA0 500GB                   | 2         | 2      | 1.04%   |
| WDC WD10EZEX-21M2NA0 1TB                       | 2         | 3      | 1.04%   |
| Seagate ST9500420AS 500GB                      | 2         | 2      | 1.04%   |
| Seagate ST4000DM004-2CV104 4TB                 | 2         | 2      | 1.04%   |
| Seagate ST3500418AS 500GB                      | 2         | 2      | 1.04%   |
| Seagate ST2000DX001-1CM164 2TB                 | 2         | 2      | 1.04%   |
| Seagate ST2000DM001-1CH164 2TB                 | 2         | 3      | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2         | 2      | 1.04%   |
| Samsung Electronics SP2504C 250GB              | 2         | 2      | 1.04%   |
| Samsung Electronics HD501LJ 500GB              | 2         | 2      | 1.04%   |
| Samsung Electronics HD300LJ 304GB              | 2         | 2      | 1.04%   |
| Kingston SV300S37A120G 120GB SSD               | 2         | 2      | 1.04%   |
| Intel SSDSC2CW120A3 120GB                      | 2         | 2      | 1.04%   |
| Intel SSDSC2BW480A4 480GB                      | 2         | 3      | 1.04%   |
| Intel SSDSC2BW240A4 240GB                      | 2         | 3      | 1.04%   |
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 1.04%   |
| Hitachi HTS543216L9A300 160GB                  | 2         | 2      | 1.04%   |
| HGST HTS725032A7E630 320GB                     | 2         | 2      | 1.04%   |
| Crucial CT525MX300SSD1 528GB                   | 2         | 2      | 1.04%   |
| WDC WD7500AACS-00ZJB0 752GB                    | 1         | 1      | 0.52%   |
| WDC WD740GD-00FLA1 74GB                        | 1         | 1      | 0.52%   |
| WDC WD6400AAKS-22A7B2 640GB                    | 1         | 1      | 0.52%   |
| WDC WD6400AAKS-00A7B2 640GB                    | 1         | 1      | 0.52%   |
| WDC WD60EFRX-68L0BN1 6TB                       | 1         | 6      | 0.52%   |
| WDC WD5000BPKT-60PK4T0 500GB                   | 1         | 1      | 0.52%   |
| WDC WD5000AZRX-00A8LB0 500GB                   | 1         | 2      | 0.52%   |
| WDC WD5000AAKS-00A7B2 500GB                    | 1         | 1      | 0.52%   |
| WDC WD40EFRX-68N32N0 4TB                       | 1         | 2      | 0.52%   |
| WDC WD4003FZEX-00Z4SA0 4TB                     | 1         | 2      | 0.52%   |
| WDC WD3200AAKS-75L9A0 320GB                    | 1         | 1      | 0.52%   |
| WDC WD3200AAKS-00B3A0 320GB                    | 1         | 4      | 0.52%   |
| WDC WD30EFRX-68AX9N0 3TB                       | 1         | 3      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 43        | 54     | 23.12%  |
| WDC                 | 32        | 57     | 17.2%   |
| Samsung Electronics | 20        | 20     | 10.75%  |
| Hitachi             | 19        | 22     | 10.22%  |
| Intel               | 15        | 18     | 8.06%   |
| HGST                | 8         | 9      | 4.3%    |
| Kingston            | 7         | 7      | 3.76%   |
| Micron Technology   | 6         | 7      | 3.23%   |
| Crucial             | 6         | 8      | 3.23%   |
| Toshiba             | 5         | 6      | 2.69%   |
| OCZ                 | 3         | 5      | 1.61%   |
| Corsair             | 3         | 3      | 1.61%   |
| SK hynix            | 2         | 2      | 1.08%   |
| SanDisk             | 2         | 2      | 1.08%   |
| LITEONIT            | 2         | 2      | 1.08%   |
| Fujitsu             | 2         | 2      | 1.08%   |
| Apple               | 2         | 2      | 1.08%   |
| Union Memory        | 1         | 1      | 0.54%   |
| Transcend           | 1         | 1      | 0.54%   |
| Team                | 1         | 1      | 0.54%   |
| Silicon Motion      | 1         | 1      | 0.54%   |
| PNY                 | 1         | 2      | 0.54%   |
| Hewlett-Packard     | 1         | 1      | 0.54%   |
| China               | 1         | 1      | 0.54%   |
| A-DATA Technology   | 1         | 1      | 0.54%   |
| Unknown             | 1         | 1      | 0.54%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 43        | 54     | 35.25%  |
| WDC                 | 30        | 55     | 24.59%  |
| Hitachi             | 19        | 22     | 15.57%  |
| Samsung Electronics | 12        | 12     | 9.84%   |
| HGST                | 8         | 9      | 6.56%   |
| Toshiba             | 4         | 5      | 3.28%   |
| Fujitsu             | 2         | 2      | 1.64%   |
| Apple               | 2         | 2      | 1.64%   |
| Hewlett-Packard     | 1         | 1      | 0.82%   |
| Unknown             | 1         | 1      | 0.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 117       | 163    | 65.73%  |
| SSD  | 53        | 65     | 29.78%  |
| NVMe | 8         | 8      | 4.49%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB                                 | 1         | 1      | 50%     |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1411      | 3020   | 56.8%   |
| Works    | 899       | 1665   | 36.19%  |
| Malfunc  | 172       | 236    | 6.92%   |
| Failed   | 2         | 2      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1375      | 46.42%  |
| AMD                              | 487       | 16.44%  |
| Samsung Electronics              | 390       | 13.17%  |
| SanDisk                          | 130       | 4.39%   |
| Kingston Technology Company      | 96        | 3.24%   |
| SK hynix                         | 70        | 2.36%   |
| Toshiba America Info Systems     | 58        | 1.96%   |
| Phison Electronics               | 52        | 1.76%   |
| ASMedia Technology               | 49        | 1.65%   |
| JMicron Technology               | 40        | 1.35%   |
| Marvell Technology Group         | 36        | 1.22%   |
| Micron Technology                | 33        | 1.11%   |
| Nvidia                           | 23        | 0.78%   |
| KIOXIA                           | 22        | 0.74%   |
| Micron/Crucial Technology        | 15        | 0.51%   |
| Silicon Motion                   | 13        | 0.44%   |
| ADATA Technology                 | 12        | 0.41%   |
| Silicon Image                    | 6         | 0.2%    |
| VIA Technologies                 | 5         | 0.17%   |
| Union Memory (Shenzhen)          | 5         | 0.17%   |
| Lite-On Technology               | 5         | 0.17%   |
| Lenovo                           | 5         | 0.17%   |
| Broadcom / LSI                   | 5         | 0.17%   |
| Solid State Storage Technology   | 4         | 0.14%   |
| Realtek Semiconductor            | 4         | 0.14%   |
| LSI Logic / Symbios Logic        | 4         | 0.14%   |
| Apple                            | 4         | 0.14%   |
| Silicon Integrated Systems [SiS] | 3         | 0.1%    |
| Seagate Technology               | 3         | 0.1%    |
| Hewlett-Packard                  | 3         | 0.1%    |
| Transcend                        | 1         | 0.03%   |
| O2 Micro                         | 1         | 0.03%   |
| Integrated Technology Express    | 1         | 0.03%   |
| HighPoint Technologies           | 1         | 0.03%   |
| Adaptec                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 324       | 9.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 205       | 6.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 99        | 2.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 99        | 2.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 84        | 2.49%   |
| AMD 400 Series Chipset SATA Controller                                         | 81        | 2.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 66        | 1.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 63        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 61        | 1.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 59        | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 55        | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 55        | 1.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 53        | 1.57%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 51        | 1.51%   |
| Intel Volume Management Device NVMe RAID Controller                            | 49        | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 49        | 1.45%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 48        | 1.42%   |
| AMD 500 Series Chipset SATA Controller                                         | 47        | 1.39%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 43        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 43        | 1.27%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 41        | 1.21%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 41        | 1.21%   |
| Intel SSD 660P Series                                                          | 40        | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 38        | 1.12%   |
| Intel SATA Controller [RAID mode]                                              | 37        | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 37        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 37        | 1.1%    |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 36        | 1.07%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 32        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 30        | 0.89%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 28        | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 26        | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 25        | 0.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 24        | 0.71%   |
| Phison E12 NVMe Controller                                                     | 24        | 0.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 24        | 0.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 24        | 0.71%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 0.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 21        | 0.62%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 20        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1598      | 54.19%  |
| NVMe | 916       | 31.06%  |
| IDE  | 253       | 8.58%   |
| RAID | 170       | 5.76%   |
| SAS  | 8         | 0.27%   |
| SCSI | 4         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1633      | 72.26%  |
| AMD      | 604       | 26.73%  |
| ARM      | 22        | 0.97%   |
| QUALCOMM | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 33        | 1.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 30        | 1.32%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 27        | 1.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 25        | 1.1%    |
| AMD Ryzen 5 3600 6-Core Processor           | 25        | 1.1%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 21        | 0.93%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 19        | 0.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 18        | 0.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 17        | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 16        | 0.71%   |
| ARM Processor                               | 16        | 0.71%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 16        | 0.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 15        | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 15        | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 14        | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 14        | 0.62%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 13        | 0.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 13        | 0.57%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 13        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 12        | 0.53%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 12        | 0.53%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 12        | 0.53%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 12        | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 11        | 0.49%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 11        | 0.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 11        | 0.49%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 11        | 0.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 11        | 0.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 11        | 0.49%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 11        | 0.49%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 11        | 0.49%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 11        | 0.49%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 10        | 0.44%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 10        | 0.44%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 10        | 0.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 10        | 0.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 9         | 0.4%    |
| Intel Core i7-5500U CPU @ 2.40GHz           | 9         | 0.4%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9         | 0.4%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 9         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 536       | 23.7%   |
| Intel Core i7           | 485       | 21.44%  |
| Other                   | 196       | 8.66%   |
| AMD Ryzen 5             | 154       | 6.81%   |
| AMD Ryzen 7             | 134       | 5.92%   |
| Intel Core i3           | 92        | 4.07%   |
| Intel Celeron           | 82        | 3.63%   |
| AMD Ryzen 9             | 67        | 2.96%   |
| Intel Core 2 Duo        | 64        | 2.83%   |
| Intel Xeon              | 53        | 2.34%   |
| Intel Pentium           | 36        | 1.59%   |
| AMD FX                  | 34        | 1.5%    |
| Intel Atom              | 29        | 1.28%   |
| AMD Ryzen 3             | 21        | 0.93%   |
| Intel Core i9           | 17        | 0.75%   |
| Intel Core 2 Quad       | 17        | 0.75%   |
| AMD A8                  | 17        | 0.75%   |
| Intel Core 2            | 14        | 0.62%   |
| AMD A6                  | 13        | 0.57%   |
| AMD Ryzen Threadripper  | 11        | 0.49%   |
| AMD Ryzen 7 PRO         | 11        | 0.49%   |
| AMD Phenom II X4        | 11        | 0.49%   |
| Intel Genuine           | 10        | 0.44%   |
| AMD E1                  | 10        | 0.44%   |
| AMD A4                  | 10        | 0.44%   |
| Intel Pentium Dual-Core | 9         | 0.4%    |
| AMD A10                 | 9         | 0.4%    |
| AMD E                   | 8         | 0.35%   |
| Intel Pentium Silver    | 7         | 0.31%   |
| AMD Ryzen 5 PRO         | 7         | 0.31%   |
| AMD Phenom II X6        | 7         | 0.31%   |
| AMD Athlon II X2        | 7         | 0.31%   |
| AMD Athlon 64 X2        | 7         | 0.31%   |
| Intel Pentium Dual      | 6         | 0.27%   |
| ARM BCM                 | 6         | 0.27%   |
| AMD Ryzen Embedded      | 5         | 0.22%   |
| Intel Pentium M         | 4         | 0.18%   |
| Intel Core m3           | 3         | 0.13%   |
| Intel Celeron Dual-Core | 3         | 0.13%   |
| AMD Turion 64 X2 Mobile | 3         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 850       | 37.53%  |
| 2       | 731       | 32.27%  |
| 6       | 275       | 12.14%  |
| 8       | 209       | 9.23%   |
| 12      | 61        | 2.69%   |
| 16      | 34        | 1.5%    |
| 1       | 32        | 1.41%   |
| 10      | 19        | 0.84%   |
| 3       | 19        | 0.84%   |
| 14      | 17        | 0.75%   |
| Unknown | 5         | 0.22%   |
| 18      | 4         | 0.18%   |
| 32      | 3         | 0.13%   |
| 24      | 3         | 0.13%   |
| 64      | 1         | 0.04%   |
| 28      | 1         | 0.04%   |
| 20      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2230      | 98.67%  |
| 2       | 25        | 1.11%   |
| Unknown | 4         | 0.18%   |
| 3       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1573      | 69.48%  |
| 1       | 686       | 30.3%   |
| Unknown | 5         | 0.22%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2209      | 97.57%  |
| Unknown        | 42        | 1.86%   |
| 32-bit         | 12        | 0.53%   |
| 64-bit         | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 723       | 30.52%  |
| 0x306c3    | 105       | 4.43%   |
| 0x206a7    | 96        | 4.05%   |
| 0x306a9    | 92        | 3.88%   |
| 0x906ea    | 52        | 2.2%    |
| 0x806c1    | 52        | 2.2%    |
| 0x806ea    | 50        | 2.11%   |
| 0x40651    | 50        | 2.11%   |
| 0x1067a    | 49        | 2.07%   |
| 0x806ec    | 48        | 2.03%   |
| 0x406e3    | 46        | 1.94%   |
| 0x306d4    | 46        | 1.94%   |
| 0x506e3    | 45        | 1.9%    |
| 0x906e9    | 44        | 1.86%   |
| 0x08701021 | 43        | 1.82%   |
| 0x806e9    | 42        | 1.77%   |
| 0x20655    | 28        | 1.18%   |
| 0x0a50000c | 25        | 1.06%   |
| 0x08108109 | 23        | 0.97%   |
| 0x08701013 | 22        | 0.93%   |
| 0x0800820d | 22        | 0.93%   |
| 0x406c4    | 19        | 0.8%    |
| 0x08600106 | 18        | 0.76%   |
| 0x906ed    | 16        | 0.68%   |
| 0x06000852 | 15        | 0.63%   |
| 0x010000c8 | 15        | 0.63%   |
| 0x806eb    | 14        | 0.59%   |
| 0x6fd      | 14        | 0.59%   |
| 0x306f2    | 14        | 0.59%   |
| 0x30678    | 14        | 0.59%   |
| 0x0a201009 | 14        | 0.59%   |
| 0x0810100b | 14        | 0.59%   |
| 0xa0652    | 13        | 0.55%   |
| 0x906a3    | 13        | 0.55%   |
| 0x106e5    | 13        | 0.55%   |
| 0x08001138 | 13        | 0.55%   |
| 0x06001119 | 13        | 0.55%   |
| 0x6f6      | 12        | 0.51%   |
| 0x08608103 | 12        | 0.51%   |
| 0x0700010f | 12        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 381       | 16.83%  |
| Haswell          | 230       | 10.16%  |
| SandyBridge      | 149       | 6.58%   |
| IvyBridge        | 138       | 6.1%    |
| Skylake          | 133       | 5.87%   |
| Zen 2            | 126       | 5.57%   |
| Unknown          | 125       | 5.52%   |
| Zen 3            | 103       | 4.55%   |
| Penryn           | 77        | 3.4%    |
| Zen+             | 72        | 3.18%   |
| TigerLake        | 71        | 3.14%   |
| Broadwell        | 61        | 2.69%   |
| Silvermont       | 60        | 2.65%   |
| Zen              | 56        | 2.47%   |
| Westmere         | 55        | 2.43%   |
| Core             | 53        | 2.34%   |
| K10              | 44        | 1.94%   |
| Alderlake Hybrid | 44        | 1.94%   |
| Piledriver       | 41        | 1.81%   |
| CometLake        | 39        | 1.72%   |
| IceLake          | 27        | 1.19%   |
| Nehalem          | 24        | 1.06%   |
| Goldmont plus    | 24        | 1.06%   |
| Excavator        | 19        | 0.84%   |
| K8 Hammer        | 14        | 0.62%   |
| K10 Llano        | 12        | 0.53%   |
| Jaguar           | 12        | 0.53%   |
| Goldmont         | 12        | 0.53%   |
| Bobcat           | 12        | 0.53%   |
| Puma             | 10        | 0.44%   |
| Bulldozer        | 10        | 0.44%   |
| Bonnell          | 8         | 0.35%   |
| P6               | 6         | 0.27%   |
| Tremont          | 5         | 0.22%   |
| Steamroller      | 3         | 0.13%   |
| NetBurst         | 3         | 0.13%   |
| K8 & K10 hybrid  | 3         | 0.13%   |
| K6               | 1         | 0.04%   |
| Geode            | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1179      | 45%     |
| Nvidia                           | 820       | 31.3%   |
| AMD                              | 599       | 22.86%  |
| Matrox Electronics Systems       | 11        | 0.42%   |
| ASPEED Technology                | 8         | 0.31%   |
| Silicon Integrated Systems [SiS] | 3         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 99        | 3.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 76        | 2.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 68        | 2.51%   |
| Intel UHD Graphics 620                                                                   | 64        | 2.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 62        | 2.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 53        | 1.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 50        | 1.84%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 48        | 1.77%   |
| Intel HD Graphics 620                                                                    | 47        | 1.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 47        | 1.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 45        | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 40        | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 40        | 1.47%   |
| Intel HD Graphics 5500                                                                   | 39        | 1.44%   |
| Intel HD Graphics 630                                                                    | 35        | 1.29%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 35        | 1.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 32        | 1.18%   |
| Intel Core Processor Integrated Graphics Controller                                      | 29        | 1.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 27        | 0.99%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 26        | 0.96%   |
| Intel HD Graphics 530                                                                    | 24        | 0.88%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 24        | 0.88%   |
| AMD Lucienne                                                                             | 23        | 0.85%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 21        | 0.77%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 21        | 0.77%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 21        | 0.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 20        | 0.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 20        | 0.74%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 20        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 18        | 0.66%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 18        | 0.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 18        | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 17        | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 16        | 0.59%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 16        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 856       | 37.58%  |
| 1 x Nvidia               | 518       | 22.74%  |
| 1 x AMD                  | 472       | 20.72%  |
| Intel + Nvidia           | 247       | 10.84%  |
| 2 x AMD                  | 46        | 2.02%   |
| AMD + Nvidia             | 43        | 1.89%   |
| Intel + AMD              | 38        | 1.67%   |
| Other                    | 24        | 1.05%   |
| 1 x Matrox               | 9         | 0.4%    |
| 1 x ASPEED               | 7         | 0.31%   |
| 2 x Nvidia               | 5         | 0.22%   |
| 2 x Intel                | 3         | 0.13%   |
| 1 x SiS                  | 3         | 0.13%   |
| Intel + 2 x Nvidia       | 2         | 0.09%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.09%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.04%   |
| Nvidia + Matrox          | 1         | 0.04%   |
| Nvidia + ASPEED          | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1688      | 73.52%  |
| Proprietary | 505       | 21.99%  |
| Unknown     | 103       | 4.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1298      | 55.64%  |
| 1.01-2.0   | 247       | 10.59%  |
| 0.01-0.5   | 228       | 9.77%   |
| 7.01-8.0   | 140       | 6%      |
| 3.01-4.0   | 138       | 5.92%   |
| 0.51-1.0   | 136       | 5.83%   |
| 5.01-6.0   | 65        | 2.79%   |
| 8.01-16.0  | 47        | 2.01%   |
| 2.01-3.0   | 25        | 1.07%   |
| 16.01-24.0 | 9         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 320       | 12.43%  |
| Samsung Electronics     | 309       | 12%     |
| LG Display              | 189       | 7.34%   |
| Chimei Innolux          | 181       | 7.03%   |
| Dell                    | 151       | 5.86%   |
| BenQ                    | 132       | 5.13%   |
| BOE                     | 116       | 4.5%    |
| Philips                 | 110       | 4.27%   |
| Ancor Communications    | 109       | 4.23%   |
| Hewlett-Packard         | 105       | 4.08%   |
| AOC                     | 94        | 3.65%   |
| Acer                    | 91        | 3.53%   |
| Sharp                   | 68        | 2.64%   |
| Goldstar                | 66        | 2.56%   |
| Apple                   | 63        | 2.45%   |
| Lenovo                  | 57        | 2.21%   |
| ASUSTek Computer        | 36        | 1.4%    |
| MSI                     | 27        | 1.05%   |
| InfoVision              | 26        | 1.01%   |
| Chi Mei Optoelectronics | 25        | 0.97%   |
| Eizo                    | 23        | 0.89%   |
| CSO                     | 19        | 0.74%   |
| LG Philips              | 17        | 0.66%   |
| Unknown                 | 16        | 0.62%   |
| Vestel Elektronik       | 15        | 0.58%   |
| Sony                    | 15        | 0.58%   |
| Panasonic               | 13        | 0.5%    |
| Fujitsu Siemens         | 12        | 0.47%   |
| PANDA                   | 11        | 0.43%   |
| LG Electronics          | 11        | 0.43%   |
| ViewSonic               | 10        | 0.39%   |
| Gigabyte Technology     | 8         | 0.31%   |
| Toshiba                 | 6         | 0.23%   |
| VOXICON                 | 5         | 0.19%   |
| Valve                   | 5         | 0.19%   |
| Microstep               | 5         | 0.19%   |
| LGD                     | 5         | 0.19%   |
| BOE Technology Group    | 5         | 0.19%   |
| Quanta Display          | 4         | 0.16%   |
| Positivo                | 4         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 16        | 0.6%    |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 15        | 0.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 13        | 0.49%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 11        | 0.41%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 11        | 0.41%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 10        | 0.37%   |
| BenQ G2420HDBL BNQ785F 1920x1080 477x268mm 21.5-inch                   | 9         | 0.34%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 9         | 0.34%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 8         | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 8         | 0.3%    |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 8         | 0.3%    |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 8         | 0.3%    |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 8         | 0.3%    |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch  | 8         | 0.3%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 7         | 0.26%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 797x333mm 34.0-inch                   | 7         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 7         | 0.26%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                     | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 7         | 0.26%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch       | 7         | 0.26%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 7         | 0.26%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 6         | 0.22%   |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                   | 6         | 0.22%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 6         | 0.22%   |
| Hewlett-Packard E241i HWP3122 1920x1200 520x320mm 24.0-inch            | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch       | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch       | 6         | 0.22%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 6         | 0.22%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 6         | 0.22%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                | 5         | 0.19%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 5         | 0.19%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch              | 5         | 0.19%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch             | 5         | 0.19%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 5         | 0.19%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 5         | 0.19%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 5         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1074      | 43.59%  |
| 1366x768 (WXGA)    | 288       | 11.69%  |
| 3840x2160 (4K)     | 212       | 8.6%    |
| 2560x1440 (QHD)    | 202       | 8.2%    |
| 1920x1200 (WUXGA)  | 90        | 3.65%   |
| 1680x1050 (WSXGA+) | 85        | 3.45%   |
| 3440x1440          | 65        | 2.64%   |
| 1600x900 (HD+)     | 55        | 2.23%   |
| 1280x1024 (SXGA)   | 50        | 2.03%   |
| 1280x800 (WXGA)    | 49        | 1.99%   |
| Unknown            | 40        | 1.62%   |
| 2560x1600          | 35        | 1.42%   |
| 1440x900 (WXGA+)   | 34        | 1.38%   |
| 3840x2400          | 21        | 0.85%   |
| 2880x1800          | 21        | 0.85%   |
| 3840x1080          | 18        | 0.73%   |
| 1024x768 (XGA)     | 13        | 0.53%   |
| 1360x768           | 11        | 0.45%   |
| 1920x540           | 10        | 0.41%   |
| 3200x1800 (QHD+)   | 8         | 0.32%   |
| 1280x720 (HD)      | 8         | 0.32%   |
| 800x1280           | 7         | 0.28%   |
| 2736x1824          | 7         | 0.28%   |
| 2560x1080          | 6         | 0.24%   |
| 2288x1287          | 5         | 0.2%    |
| 1024x600           | 5         | 0.2%    |
| 3840x1600          | 4         | 0.16%   |
| 2160x1440          | 4         | 0.16%   |
| 6400x2160          | 3         | 0.12%   |
| 5760x2160          | 3         | 0.12%   |
| 5760x1080          | 3         | 0.12%   |
| 4480x1440          | 2         | 0.08%   |
| 3840x1200          | 2         | 0.08%   |
| 3200x1200          | 2         | 0.08%   |
| 1280x768           | 2         | 0.08%   |
| 7280x2160          | 1         | 0.04%   |
| 5520x2160          | 1         | 0.04%   |
| 5360x1440          | 1         | 0.04%   |
| 4920x1920          | 1         | 0.04%   |
| 4864x1080          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 452       | 17.75%  |
| 13      | 298       | 11.7%   |
| 27      | 276       | 10.84%  |
| 24      | 269       | 10.56%  |
| 14      | 202       | 7.93%   |
| 23      | 153       | 6.01%   |
| Unknown | 149       | 5.85%   |
| 17      | 90        | 3.53%   |
| 21      | 73        | 2.87%   |
| 12      | 73        | 2.87%   |
| 31      | 62        | 2.43%   |
| 34      | 60        | 2.36%   |
| 22      | 60        | 2.36%   |
| 19      | 50        | 1.96%   |
| 84      | 38        | 1.49%   |
| 11      | 28        | 1.1%    |
| 16      | 25        | 0.98%   |
| 32      | 19        | 0.75%   |
| 20      | 16        | 0.63%   |
| 72      | 14        | 0.55%   |
| 25      | 13        | 0.51%   |
| 40      | 12        | 0.47%   |
| 65      | 11        | 0.43%   |
| 54      | 10        | 0.39%   |
| 42      | 9         | 0.35%   |
| 18      | 8         | 0.31%   |
| 39      | 7         | 0.27%   |
| 35      | 7         | 0.27%   |
| 48      | 6         | 0.24%   |
| 37      | 5         | 0.2%    |
| 29      | 5         | 0.2%    |
| 10      | 5         | 0.2%    |
| 50      | 4         | 0.16%   |
| 49      | 4         | 0.16%   |
| 7       | 4         | 0.16%   |
| 142     | 3         | 0.12%   |
| 46      | 3         | 0.12%   |
| 33      | 3         | 0.12%   |
| 3       | 3         | 0.12%   |
| 55      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 805       | 32.3%   |
| 501-600        | 636       | 25.52%  |
| 201-300        | 277       | 11.12%  |
| 401-500        | 169       | 6.78%   |
| Unknown        | 149       | 5.98%   |
| 351-400        | 125       | 5.02%   |
| 601-700        | 96        | 3.85%   |
| 701-800        | 82        | 3.29%   |
| 1501-2000      | 54        | 2.17%   |
| 1001-1500      | 44        | 1.77%   |
| 801-900        | 30        | 1.2%    |
| 901-1000       | 14        | 0.56%   |
| 1-100          | 7         | 0.28%   |
| More than 2000 | 3         | 0.12%   |
| 101-200        | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1616      | 70.57%  |
| 16/10   | 356       | 15.55%  |
| Unknown | 136       | 5.94%   |
| 21/9    | 73        | 3.19%   |
| 5/4     | 53        | 2.31%   |
| 3/2     | 21        | 0.92%   |
| 4/3     | 14        | 0.61%   |
| 32/9    | 6         | 0.26%   |
| 6/5     | 5         | 0.22%   |
| 0.67    | 4         | 0.17%   |
| 1.00    | 3         | 0.13%   |
| 3.40    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |
| 0.45    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 445       | 17.74%  |
| 201-250        | 417       | 16.62%  |
| 81-90          | 359       | 14.31%  |
| 301-350        | 277       | 11.04%  |
| 351-500        | 151       | 6.02%   |
| Unknown        | 149       | 5.94%   |
| 71-80          | 141       | 5.62%   |
| 251-300        | 109       | 4.34%   |
| More than 1000 | 92        | 3.67%   |
| 151-200        | 79        | 3.15%   |
| 121-130        | 69        | 2.75%   |
| 61-70          | 67        | 2.67%   |
| 501-1000       | 47        | 1.87%   |
| 51-60          | 29        | 1.16%   |
| 111-120        | 26        | 1.04%   |
| 141-150        | 18        | 0.72%   |
| 131-140        | 14        | 0.56%   |
| 1-40           | 7         | 0.28%   |
| 91-100         | 7         | 0.28%   |
| 41-50          | 6         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 776       | 31.97%  |
| 121-160       | 635       | 26.16%  |
| 101-120       | 517       | 21.3%   |
| 161-240       | 197       | 8.12%   |
| Unknown       | 149       | 6.14%   |
| More than 240 | 92        | 3.79%   |
| 1-50          | 61        | 2.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1728      | 74.48%  |
| 2     | 427       | 18.41%  |
| 0     | 110       | 4.74%   |
| 3     | 47        | 2.03%   |
| 4     | 7         | 0.3%    |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1276      | 39.03%  |
| Realtek Semiconductor             | 987       | 30.19%  |
| Qualcomm Atheros                  | 298       | 9.12%   |
| Broadcom                          | 195       | 5.97%   |
| MediaTek                          | 61        | 1.87%   |
| Broadcom Limited                  | 50        | 1.53%   |
| Marvell Technology Group          | 33        | 1.01%   |
| Ralink                            | 23        | 0.7%    |
| ASIX Electronics                  | 23        | 0.7%    |
| Hewlett-Packard                   | 19        | 0.58%   |
| TP-Link                           | 18        | 0.55%   |
| Nvidia                            | 18        | 0.55%   |
| Sierra Wireless                   | 17        | 0.52%   |
| ASUSTek Computer                  | 17        | 0.52%   |
| Lenovo                            | 16        | 0.49%   |
| Ralink Technology                 | 15        | 0.46%   |
| Microsoft                         | 15        | 0.46%   |
| Dell                              | 14        | 0.43%   |
| D-Link System                     | 14        | 0.43%   |
| NetGear                           | 13        | 0.4%    |
| DisplayLink                       | 11        | 0.34%   |
| D-Link                            | 11        | 0.34%   |
| Qualcomm                          | 9         | 0.28%   |
| Huawei Technologies               | 9         | 0.28%   |
| Ericsson Business Mobile Networks | 9         | 0.28%   |
| Qualcomm Atheros Communications   | 7         | 0.21%   |
| Aquantia                          | 7         | 0.21%   |
| Samsung Electronics               | 6         | 0.18%   |
| Fibocom                           | 5         | 0.15%   |
| Xiaomi                            | 4         | 0.12%   |
| Microchip Technology              | 4         | 0.12%   |
| STMicroelectronics                | 3         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.09%   |
| Mellanox Technologies             | 3         | 0.09%   |
| Linksys                           | 3         | 0.09%   |
| JMicron Technology                | 3         | 0.09%   |
| Belkin Components                 | 3         | 0.09%   |
| Arduino SA                        | 3         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.06%   |
| Wacom                             | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 679       | 17.26%  |
| Intel I211 Gigabit Network Connection                             | 112       | 2.85%   |
| Intel Wi-Fi 6 AX200                                               | 106       | 2.69%   |
| Intel Wireless 8265 / 8275                                        | 104       | 2.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 83        | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 76        | 1.93%   |
| Intel Wireless 7260                                               | 73        | 1.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 62        | 1.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 62        | 1.58%   |
| Intel Ethernet Connection (2) I219-V                              | 58        | 1.47%   |
| Intel Wireless 8260                                               | 57        | 1.45%   |
| Intel Wi-Fi 6 AX201                                               | 57        | 1.45%   |
| Intel Wireless 7265                                               | 52        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 42        | 1.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 0.99%   |
| Intel Ethernet Controller I225-V                                  | 37        | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 37        | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 36        | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 35        | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 35        | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 33        | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 33        | 0.84%   |
| Intel 82579V Gigabit Network Connection                           | 33        | 0.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 30        | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 30        | 0.76%   |
| Intel Ethernet Connection (7) I219-V                              | 29        | 0.74%   |
| Intel Wireless-AC 9260                                            | 27        | 0.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 27        | 0.69%   |
| Intel Ethernet Connection (4) I219-V                              | 27        | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 0.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 26        | 0.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25        | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 25        | 0.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 25        | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 24        | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 23        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 22        | 0.56%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 22        | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 21        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 905       | 51.39%  |
| Qualcomm Atheros                  | 232       | 13.17%  |
| Realtek Semiconductor             | 217       | 12.32%  |
| Broadcom                          | 129       | 7.33%   |
| MediaTek                          | 60        | 3.41%   |
| Broadcom Limited                  | 32        | 1.82%   |
| Ralink                            | 23        | 1.31%   |
| Sierra Wireless                   | 17        | 0.97%   |
| ASUSTek Computer                  | 17        | 0.97%   |
| TP-Link                           | 15        | 0.85%   |
| Ralink Technology                 | 15        | 0.85%   |
| NetGear                           | 13        | 0.74%   |
| Microsoft                         | 10        | 0.57%   |
| D-Link System                     | 10        | 0.57%   |
| D-Link                            | 10        | 0.57%   |
| Dell                              | 9         | 0.51%   |
| Qualcomm Atheros Communications   | 7         | 0.4%    |
| Qualcomm                          | 7         | 0.4%    |
| Marvell Technology Group          | 5         | 0.28%   |
| Fibocom                           | 5         | 0.28%   |
| Hewlett-Packard                   | 4         | 0.23%   |
| Belkin Components                 | 3         | 0.17%   |
| Wacom                             | 2         | 0.11%   |
| Micro Star International          | 2         | 0.11%   |
| Linksys                           | 2         | 0.11%   |
| Ericsson Business Mobile Networks | 2         | 0.11%   |
| Edimax Technology                 | 2         | 0.11%   |
| ZyXEL Communications              | 1         | 0.06%   |
| Wilocity                          | 1         | 0.06%   |
| Sitecom Europe                    | 1         | 0.06%   |
| IMC Networks                      | 1         | 0.06%   |
| Fujitsu Siemens Computers         | 1         | 0.06%   |
| Chu Yuen Enterprise               | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 106       | 5.98%   |
| Intel Wireless 8265 / 8275                                           | 104       | 5.87%   |
| Intel Wireless 7260                                                  | 73        | 4.12%   |
| Intel Wireless 8260                                                  | 57        | 3.22%   |
| Intel Wi-Fi 6 AX201                                                  | 57        | 3.22%   |
| Intel Wireless 7265                                                  | 52        | 2.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 42        | 2.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 39        | 2.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 36        | 2.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 35        | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 35        | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 33        | 1.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 33        | 1.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 30        | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 30        | 1.69%   |
| Intel Wireless-AC 9260                                               | 27        | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 27        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 26        | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 25        | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 25        | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 24        | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 23        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                       | 22        | 1.24%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 21        | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 20        | 1.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 20        | 1.13%   |
| Intel Wireless 3160                                                  | 20        | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 19        | 1.07%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 18        | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 17        | 0.96%   |
| Intel Wireless 3165                                                  | 17        | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 17        | 0.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 17        | 0.96%   |
| Intel Centrino Advanced-N 6200                                       | 15        | 0.85%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter         | 15        | 0.85%   |
| Intel Centrino Advanced-N 6235                                       | 14        | 0.79%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 14        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 13        | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 12        | 0.68%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 12        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 896       | 43.64%  |
| Intel                                  | 776       | 37.8%   |
| Qualcomm Atheros                       | 99        | 4.82%   |
| Broadcom                               | 95        | 4.63%   |
| Marvell Technology Group               | 28        | 1.36%   |
| ASIX Electronics                       | 23        | 1.12%   |
| Broadcom Limited                       | 19        | 0.93%   |
| Nvidia                                 | 18        | 0.88%   |
| Lenovo                                 | 15        | 0.73%   |
| DisplayLink                            | 11        | 0.54%   |
| Huawei Technologies                    | 7         | 0.34%   |
| Aquantia                               | 7         | 0.34%   |
| Hewlett-Packard                        | 6         | 0.29%   |
| Samsung Electronics                    | 5         | 0.24%   |
| Microsoft                              | 5         | 0.24%   |
| Xiaomi                                 | 4         | 0.19%   |
| Microchip Technology                   | 4         | 0.19%   |
| D-Link System                          | 4         | 0.19%   |
| TP-Link                                | 3         | 0.15%   |
| JMicron Technology                     | 3         | 0.15%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.1%    |
| Standard Microsystems                  | 2         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 2         | 0.1%    |
| Silicon Integrated Systems [SiS]       | 2         | 0.1%    |
| Qualcomm                               | 2         | 0.1%    |
| ICS Advent                             | 2         | 0.1%    |
| VIA Technologies                       | 1         | 0.05%   |
| Unknown                                | 1         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| Netchip Technology                     | 1         | 0.05%   |
| Mellanox Technologies                  | 1         | 0.05%   |
| MediaTek                               | 1         | 0.05%   |
| Linksys                                | 1         | 0.05%   |
| Google                                 | 1         | 0.05%   |
| Gemtek                                 | 1         | 0.05%   |
| D-Link                                 | 1         | 0.05%   |
| Apple                                  | 1         | 0.05%   |
| 3Com                                   | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 679       | 32.21%  |
| Intel I211 Gigabit Network Connection                             | 112       | 5.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 83        | 3.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 76        | 3.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 62        | 2.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 62        | 2.94%   |
| Intel Ethernet Connection (2) I219-V                              | 58        | 2.75%   |
| Intel Ethernet Controller I225-V                                  | 37        | 1.76%   |
| Intel Ethernet Connection I217-LM                                 | 37        | 1.76%   |
| Intel 82579V Gigabit Network Connection                           | 33        | 1.57%   |
| Intel Ethernet Connection (7) I219-V                              | 29        | 1.38%   |
| Intel Ethernet Connection (4) I219-V                              | 27        | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 25        | 1.19%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                             | 22        | 1.04%   |
| Intel Ethernet Connection (6) I219-V                              | 21        | 1%      |
| Intel Ethernet Connection I217-V                                  | 20        | 0.95%   |
| Intel Ethernet Connection (2) I218-V                              | 20        | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 18        | 0.85%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 17        | 0.81%   |
| Intel I210 Gigabit Network Connection                             | 16        | 0.76%   |
| Intel Ethernet Connection I219-V                                  | 16        | 0.76%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 16        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 16        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.66%   |
| Intel Ethernet Connection (13) I219-V                             | 14        | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.52%   |
| Intel Ethernet Connection (6) I219-LM                             | 10        | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.38%   |
| Intel Ethernet Connection (5) I219-LM                             | 8         | 0.38%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.38%   |
| Intel 82566MM Gigabit Network Connection                          | 8         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1939      | 53.07%  |
| WiFi     | 1660      | 45.43%  |
| Modem    | 44        | 1.2%    |
| Unknown  | 11        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1232      | 52.34%  |
| Ethernet | 1120      | 47.58%  |
| Unknown  | 2         | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1173      | 51.7%   |
| 1     | 969       | 42.71%  |
| 3     | 62        | 2.73%   |
| 0     | 44        | 1.94%   |
| 4     | 13        | 0.57%   |
| 5     | 5         | 0.22%   |
| 11    | 1         | 0.04%   |
| 9     | 1         | 0.04%   |
| 6     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2137      | 93.93%  |
| Yes  | 138       | 6.07%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 746       | 51.84%  |
| Realtek Semiconductor           | 106       | 7.37%   |
| Qualcomm Atheros Communications | 75        | 5.21%   |
| IMC Networks                    | 71        | 4.93%   |
| Apple                           | 70        | 4.86%   |
| Cambridge Silicon Radio         | 67        | 4.66%   |
| Broadcom                        | 62        | 4.31%   |
| ASUSTek Computer                | 61        | 4.24%   |
| Foxconn / Hon Hai               | 58        | 4.03%   |
| Lite-On Technology              | 38        | 2.64%   |
| Hewlett-Packard                 | 20        | 1.39%   |
| Dell                            | 16        | 1.11%   |
| MediaTek                        | 10        | 0.69%   |
| Ralink                          | 7         | 0.49%   |
| Toshiba                         | 5         | 0.35%   |
| Marvell Semiconductor           | 5         | 0.35%   |
| USI                             | 3         | 0.21%   |
| Realtek                         | 3         | 0.21%   |
| Ralink Technology               | 2         | 0.14%   |
| Micro Star International        | 2         | 0.14%   |
| HTC (High Tech Computer)        | 2         | 0.14%   |
| Chicony Electronics             | 2         | 0.14%   |
| Belkin Components               | 2         | 0.14%   |
| Taiyo Yuden                     | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |
| Creative Technology             | 1         | 0.07%   |
| Alps Electric                   | 1         | 0.07%   |
| Actions                         | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 305       | 21.11%  |
| Intel Bluetooth Device                              | 156       | 10.8%   |
| Intel AX200 Bluetooth                               | 103       | 7.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 81        | 5.61%   |
| Realtek Bluetooth Radio                             | 73        | 5.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 67        | 4.64%   |
| Apple Bluetooth Host Controller                     | 30        | 2.08%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 28        | 1.94%   |
| Intel AX210 Bluetooth                               | 26        | 1.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 25        | 1.73%   |
| Intel Wireless-AC 3168 Bluetooth                    | 23        | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 1.59%   |
| IMC Networks Bluetooth Radio                        | 23        | 1.59%   |
| Apple Bluetooth USB Host Controller                 | 23        | 1.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 22        | 1.52%   |
| Foxconn / Hon Hai Bluetooth Device                  | 21        | 1.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 1.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 17        | 1.18%   |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 1.18%   |
| IMC Networks Wireless_Device                        | 17        | 1.18%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 1.04%   |
| ASUS Bluetooth Device                               | 13        | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 12        | 0.83%   |
| IMC Networks Bluetooth Device                       | 12        | 0.83%   |
| Lite-On Bluetooth Device                            | 11        | 0.76%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.76%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 11        | 0.76%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.69%   |
| Foxconn / Hon Hai Wireless_Device                   | 10        | 0.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 0.62%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 0.62%   |
| Broadcom HP Portable SoftSailing                    | 9         | 0.62%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.55%   |
| IMC Networks 802.11ac WLAN Adapter                  | 8         | 0.55%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 8         | 0.55%   |
| Broadcom BCM20702A0                                 | 8         | 0.55%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.48%   |
| MediaTek Wireless_Device                            | 7         | 0.48%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 0.48%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1554      | 46.07%  |
| AMD                              | 697       | 20.66%  |
| Nvidia                           | 627       | 18.59%  |
| C-Media Electronics              | 64        | 1.9%    |
| Logitech                         | 41        | 1.22%   |
| SteelSeries ApS                  | 24        | 0.71%   |
| Creative Labs                    | 23        | 0.68%   |
| Kingston Technology              | 20        | 0.59%   |
| GN Netcom                        | 18        | 0.53%   |
| Realtek Semiconductor            | 16        | 0.47%   |
| Creative Technology              | 16        | 0.47%   |
| ASUSTek Computer                 | 16        | 0.47%   |
| Plantronics                      | 15        | 0.44%   |
| Focusrite-Novation               | 14        | 0.42%   |
| Texas Instruments                | 13        | 0.39%   |
| Lenovo                           | 12        | 0.36%   |
| Corsair                          | 11        | 0.33%   |
| Razer USA                        | 10        | 0.3%    |
| SAVITECH                         | 8         | 0.24%   |
| Micro Star International         | 8         | 0.24%   |
| RODE Microphones                 | 7         | 0.21%   |
| GYROCOM C&C                      | 6         | 0.18%   |
| Blue Microphones                 | 6         | 0.18%   |
| Yamaha                           | 5         | 0.15%   |
| Sony                             | 5         | 0.15%   |
| JMTek                            | 5         | 0.15%   |
| Hewlett-Packard                  | 5         | 0.15%   |
| DSEA A/S                         | 5         | 0.15%   |
| Apple                            | 5         | 0.15%   |
| Antlion Audio                    | 4         | 0.12%   |
| XMOS                             | 3         | 0.09%   |
| VIA Technologies                 | 3         | 0.09%   |
| Trust                            | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.09%   |
| Samsung Electronics              | 3         | 0.09%   |
| Samson Technologies              | 3         | 0.09%   |
| PreSonus Audio Electronics       | 3         | 0.09%   |
| Harman International             | 3         | 0.09%   |
| Generalplus Technology           | 3         | 0.09%   |
| BEHRINGER International          | 3         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 202       | 5.06%   |
| Intel Sunrise Point-LP HD Audio                                            | 177       | 4.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 139       | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 132       | 3.31%   |
| AMD Starship/Matisse HD Audio Controller                                   | 131       | 3.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 113       | 2.83%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 104       | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 91        | 2.28%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 84        | 2.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 76        | 1.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 71        | 1.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 68        | 1.7%    |
| Intel 8 Series HD Audio Controller                                         | 68        | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 64        | 1.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 62        | 1.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 62        | 1.55%   |
| AMD FCH Azalia Controller                                                  | 57        | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 55        | 1.38%   |
| Intel 200 Series PCH HD Audio                                              | 55        | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 53        | 1.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 52        | 1.3%    |
| Intel Broadwell-U Audio Controller                                         | 52        | 1.3%    |
| Nvidia GP106 High Definition Audio Controller                              | 50        | 1.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 47        | 1.18%   |
| Nvidia GP104 High Definition Audio Controller                              | 46        | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 43        | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 40        | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 40        | 1%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 38        | 0.95%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 37        | 0.93%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 35        | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                              | 31        | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                               | 31        | 0.78%   |
| Intel CM238 HD Audio Controller                                            | 31        | 0.78%   |
| AMD Kabini HDMI/DP Audio                                                   | 30        | 0.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 29        | 0.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 29        | 0.73%   |
| AMD Navi 10 HDMI Audio                                                     | 29        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 28        | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 28        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 302       | 22.22%  |
| SK hynix                     | 229       | 16.85%  |
| Corsair                      | 180       | 13.25%  |
| Kingston                     | 163       | 11.99%  |
| Micron Technology            | 155       | 11.41%  |
| Unknown                      | 105       | 7.73%   |
| Crucial                      | 68        | 5%      |
| G.Skill                      | 41        | 3.02%   |
| Ramaxel Technology           | 19        | 1.4%    |
| Elpida                       | 18        | 1.32%   |
| A-DATA Technology            | 14        | 1.03%   |
| Unknown (ABCD)               | 10        | 0.74%   |
| Nanya Technology             | 9         | 0.66%   |
| Unknown                      | 9         | 0.66%   |
| Patriot                      | 5         | 0.37%   |
| Team                         | 3         | 0.22%   |
| Transcend                    | 2         | 0.15%   |
| Qimonda                      | 2         | 0.15%   |
| GSkill                       | 2         | 0.15%   |
| GOODRAM                      | 2         | 0.15%   |
| G-Alantic                    | 2         | 0.15%   |
| Avant                        | 2         | 0.15%   |
| Apacer                       | 2         | 0.15%   |
| Unknown (AB)                 | 1         | 0.07%   |
| Unknown (836D)               | 1         | 0.07%   |
| Unifosa                      | 1         | 0.07%   |
| TEXTORM                      | 1         | 0.07%   |
| SHARETRONIC                  | 1         | 0.07%   |
| Patriot Memory (PDP Systems) | 1         | 0.07%   |
| Netlist                      | 1         | 0.07%   |
| Neo Forza                    | 1         | 0.07%   |
| KingSpec                     | 1         | 0.07%   |
| Innodisk                     | 1         | 0.07%   |
| Hyundai lnc                  | 1         | 0.07%   |
| Hewlett-Packard              | 1         | 0.07%   |
| fef5                         | 1         | 0.07%   |
| ASint Technology             | 1         | 0.07%   |
| Ankowall                     | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 24        | 1.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 13        | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.83%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.76%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 11        | 0.76%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.62%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.62%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 9         | 0.62%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.62%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s           | 9         | 0.62%   |
| Unknown                                                          | 9         | 0.62%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 8         | 0.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 0.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 0.55%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.48%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.41%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 6         | 0.41%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.41%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.41%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 6         | 0.41%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 5         | 0.34%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.34%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 5         | 0.34%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.34%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 5         | 0.34%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.34%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.34%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.34%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 5         | 0.34%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 5         | 0.34%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 5         | 0.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.34%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 5         | 0.34%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 5         | 0.34%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 5         | 0.34%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 593       | 48.85%  |
| DDR3    | 368       | 30.31%  |
| LPDDR4  | 59        | 4.86%   |
| DDR2    | 41        | 3.38%   |
| LPDDR3  | 38        | 3.13%   |
| DDR5    | 35        | 2.88%   |
| SDRAM   | 27        | 2.22%   |
| Unknown | 21        | 1.73%   |
| LPDDR5  | 18        | 1.48%   |
| DDR     | 9         | 0.74%   |
| DRAM    | 5         | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 641       | 52.89%  |
| DIMM         | 447       | 36.88%  |
| Row Of Chips | 104       | 8.58%   |
| Chip         | 12        | 0.99%   |
| Unknown      | 4         | 0.33%   |
| RIMM         | 3         | 0.25%   |
| FB-DIMM      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 524       | 40.18%  |
| 4096    | 301       | 23.08%  |
| 16384   | 257       | 19.71%  |
| 2048    | 143       | 10.97%  |
| 32768   | 38        | 2.91%   |
| 1024    | 34        | 2.61%   |
| 512     | 6         | 0.46%   |
| Unknown | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 243       | 18.65%  |
| 3200    | 180       | 13.81%  |
| 2667    | 146       | 11.2%   |
| 2400    | 95        | 7.29%   |
| 2133    | 84        | 6.45%   |
| 3600    | 65        | 4.99%   |
| 1333    | 63        | 4.83%   |
| 4267    | 32        | 2.46%   |
| 1334    | 32        | 2.46%   |
| 1867    | 28        | 2.15%   |
| 667     | 26        | 2%      |
| 4800    | 23        | 1.77%   |
| Unknown | 22        | 1.69%   |
| 800     | 20        | 1.53%   |
| 6400    | 18        | 1.38%   |
| 1067    | 16        | 1.23%   |
| 3000    | 14        | 1.07%   |
| 3733    | 13        | 1%      |
| 3400    | 13        | 1%      |
| 1800    | 13        | 1%      |
| 3533    | 11        | 0.84%   |
| 4266    | 10        | 0.77%   |
| 3800    | 10        | 0.77%   |
| 1066    | 10        | 0.77%   |
| 3266    | 9         | 0.69%   |
| 2666    | 9         | 0.69%   |
| 2933    | 7         | 0.54%   |
| 1866    | 7         | 0.54%   |
| 4199    | 6         | 0.46%   |
| 6000    | 5         | 0.38%   |
| 5600    | 5         | 0.38%   |
| 3466    | 5         | 0.38%   |
| 2747    | 5         | 0.38%   |
| 3866    | 4         | 0.31%   |
| 3534    | 4         | 0.31%   |
| 2000    | 4         | 0.31%   |
| 8400    | 3         | 0.23%   |
| 49926   | 2         | 0.15%   |
| 3933    | 2         | 0.15%   |
| 3666    | 2         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 41.94%  |
| Brother Industries    | 6         | 19.35%  |
| Samsung Electronics   | 5         | 16.13%  |
| Canon                 | 3         | 9.68%   |
| Seiko Epson           | 2         | 6.45%   |
| Oki Data              | 1         | 3.23%   |
| Lexmark International | 1         | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 2         | 6.45%   |
| HP LaserJet 1020                     | 2         | 6.45%   |
| Seiko Epson XP-4100 Series           | 1         | 3.23%   |
| Seiko Epson Printer                  | 1         | 3.23%   |
| Samsung SCX-3200 Series              | 1         | 3.23%   |
| Samsung M2070 Series                 | 1         | 3.23%   |
| Samsung Color Laser Printer          | 1         | 3.23%   |
| Oki Data USB Device                  | 1         | 3.23%   |
| Lexmark International MX317dn        | 1         | 3.23%   |
| HP OfficeJet Pro 8730                | 1         | 3.23%   |
| HP OfficeJet G55                     | 1         | 3.23%   |
| HP LaserJet Professional P 1102w     | 1         | 3.23%   |
| HP LaserJet P2035                    | 1         | 3.23%   |
| HP LaserJet 1320                     | 1         | 3.23%   |
| HP ENVY 4520 series                  | 1         | 3.23%   |
| HP DeskJet 5650c                     | 1         | 3.23%   |
| HP Deskjet 3050 J610 series          | 1         | 3.23%   |
| HP DeskJet 2700 series               | 1         | 3.23%   |
| HP DeskJet 2130 series               | 1         | 3.23%   |
| HP Color LaserJet CP1215             | 1         | 3.23%   |
| Canon LBP7010C/7018C                 | 1         | 3.23%   |
| Canon LBP6200                        | 1         | 3.23%   |
| Canon CanoScan LiDE 300              | 1         | 3.23%   |
| Brother QL-500 label printer         | 1         | 3.23%   |
| Brother HL-5150D series              | 1         | 3.23%   |
| Brother HL-2270DW Laser Printer      | 1         | 3.23%   |
| Brother HL-2130 series               | 1         | 3.23%   |
| Brother DCP-7055W                    | 1         | 3.23%   |
| Brother DCP-7040                     | 1         | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 8         | 80%     |
| Seiko Epson     | 1         | 10%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                     | 2         | 20%     |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 10%     |
| HP ScanJet 2200c                            | 1         | 10%     |
| Canon CanoScan LiDE 700F                    | 1         | 10%     |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 1         | 10%     |
| Canon CanoScan LiDE 210                     | 1         | 10%     |
| Canon CanoScan LiDE 120                     | 1         | 10%     |
| Canon CanoScan LiDE 110                     | 1         | 10%     |
| Canon CanoScan 4400F                        | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 295       | 23.06%  |
| Microdia                               | 113       | 8.84%   |
| IMC Networks                           | 108       | 8.44%   |
| Logitech                               | 102       | 7.97%   |
| Bison Electronics                      | 83        | 6.49%   |
| Realtek Semiconductor                  | 80        | 6.25%   |
| Sunplus Innovation Technology          | 59        | 4.61%   |
| Apple                                  | 53        | 4.14%   |
| Cheng Uei Precision Industry (Foxlink) | 49        | 3.83%   |
| Quanta                                 | 46        | 3.6%    |
| Lite-On Technology                     | 41        | 3.21%   |
| Syntek                                 | 33        | 2.58%   |
| Suyin                                  | 30        | 2.35%   |
| Luxvisions Innotech Limited            | 21        | 1.64%   |
| Acer                                   | 21        | 1.64%   |
| Samsung Electronics                    | 17        | 1.33%   |
| Microsoft                              | 14        | 1.09%   |
| Ricoh                                  | 10        | 0.78%   |
| Lenovo                                 | 10        | 0.78%   |
| Alcor Micro                            | 9         | 0.7%    |
| Z-Star Microelectronics                | 7         | 0.55%   |
| Silicon Motion                         | 7         | 0.55%   |
| ALi                                    | 6         | 0.47%   |
| Sonix Technology                       | 5         | 0.39%   |
| Creative Technology                    | 5         | 0.39%   |
| Trust                                  | 4         | 0.31%   |
| Primax Electronics                     | 4         | 0.31%   |
| DigiTech                               | 4         | 0.31%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.23%   |
| Generalplus Technology                 | 3         | 0.23%   |
| ARC International                      | 3         | 0.23%   |
| SunplusIT                              | 2         | 0.16%   |
| Sunplus Technology                     | 2         | 0.16%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.16%   |
| LG Electronics                         | 2         | 0.16%   |
| Importek                               | 2         | 0.16%   |
| Valve Software                         | 1         | 0.08%   |
| Tobii Technology AB                    | 1         | 0.08%   |
| Sony                                   | 1         | 0.08%   |
| ShineTech                              | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 74        | 5.72%   |
| Microdia Integrated_Webcam_HD                                            | 49        | 3.79%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 43        | 3.33%   |
| IMC Networks Integrated Camera                                           | 34        | 2.63%   |
| Realtek Integrated_Webcam_HD                                             | 28        | 2.17%   |
| Bison Integrated Camera                                                  | 26        | 2.01%   |
| Syntek Integrated Camera                                                 | 25        | 1.93%   |
| Chicony HD WebCam                                                        | 25        | 1.93%   |
| Chicony HP HD Camera                                                     | 22        | 1.7%    |
| Lite-On HP HD Camera                                                     | 18        | 1.39%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 17        | 1.31%   |
| Logitech Webcam C270                                                     | 17        | 1.31%   |
| Logitech HD Pro Webcam C920                                              | 17        | 1.31%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 15        | 1.16%   |
| Sunplus Integrated_Webcam_HD                                             | 14        | 1.08%   |
| Logitech C922 Pro Stream Webcam                                          | 14        | 1.08%   |
| Sunplus HD WebCam                                                        | 13        | 1.01%   |
| Apple Built-in iSight                                                    | 13        | 1.01%   |
| Quanta HP HD Camera                                                      | 12        | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 12        | 0.93%   |
| Bison SunplusIT Integrated Camera                                        | 12        | 0.93%   |
| Realtek USB Camera                                                       | 11        | 0.85%   |
| Lite-On Integrated Camera                                                | 11        | 0.85%   |
| Bison Lenovo EasyCamera                                                  | 11        | 0.85%   |
| Apple FaceTime HD Camera (Built-in)                                      | 11        | 0.85%   |
| Chicony HP HD Webcam [Fixed]                                             | 10        | 0.77%   |
| Apple FaceTime HD Camera                                                 | 10        | 0.77%   |
| Quanta HD User Facing                                                    | 9         | 0.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 9         | 0.7%    |
| Chicony USB2.0 Camera                                                    | 9         | 0.7%    |
| Chicony HP Wide Vision HD Camera                                         | 9         | 0.7%    |
| Chicony HP HD Webcam                                                     | 9         | 0.7%    |
| Quanta HP TrueVision HD Camera                                           | 8         | 0.62%   |
| Luxvisions Innotech Limited HP HD Camera                                 | 8         | 0.62%   |
| Chicony USB2.0 HD UVC WebCam                                             | 8         | 0.62%   |
| Chicony Integrated HP HD Webcam                                          | 8         | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 8         | 0.62%   |
| Bison EasyCamera                                                         | 8         | 0.62%   |
| Syntek Lenovo EasyCamera                                                 | 7         | 0.54%   |
| Suyin HP TrueVision HD                                                   | 7         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 134       | 42.95%  |
| Synaptics                  | 95        | 30.45%  |
| Shenzhen Goodix Technology | 29        | 9.29%   |
| Elan Microelectronics      | 15        | 4.81%   |
| Upek                       | 13        | 4.17%   |
| AuthenTec                  | 11        | 3.53%   |
| LighTuning Technology      | 9         | 2.88%   |
| STMicroelectronics         | 6         | 1.92%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 45        | 14.42%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 19        | 6.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 5.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 16        | 5.13%   |
| Shenzhen Goodix FingerPrint                                                | 14        | 4.49%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 4.17%   |
| Validity Sensors VFS491                                                    | 12        | 3.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 3.85%   |
| Synaptics WBDI                                                             | 10        | 3.21%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 3.21%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 2.88%   |
| Elan ELAN:Fingerprint                                                      | 9         | 2.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 2.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.24%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.92%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.92%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.92%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 1.92%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.6%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.6%    |
| Synaptics  WBDI                                                            | 5         | 1.6%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.6%    |
| Elan ELAN:ARM-M4                                                           | 5         | 1.6%    |
| AuthenTec AES2810                                                          | 5         | 1.6%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.6%    |
| Synaptics UWP WBDI                                                         | 4         | 1.28%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.96%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.96%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 0.96%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 3         | 0.96%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.96%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.96%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.64%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.64%   |
| Unknown                                                                    | 2         | 0.64%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.32%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 73        | 43.2%   |
| Broadcom                          | 64        | 37.87%  |
| O2 Micro                          | 12        | 7.1%    |
| Lenovo                            | 7         | 4.14%   |
| Upek                              | 5         | 2.96%   |
| Gemalto (was Gemplus)             | 3         | 1.78%   |
| Yubico.com                        | 1         | 0.59%   |
| VASCO Data Security International | 1         | 0.59%   |
| Hewlett-Packard                   | 1         | 0.59%   |
| Chicony Electronics               | 1         | 0.59%   |
| Cherry                            | 1         | 0.59%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 70        | 41.42%  |
| Broadcom 58200                                                               | 19        | 11.24%  |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 10.65%  |
| Broadcom 5880                                                                | 14        | 8.28%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 7.1%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 5.92%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 4.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 2.96%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.78%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.78%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.18%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.59%   |
| VASCO Data Security International DIGIPASS 920                               | 1         | 0.59%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.59%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.59%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.59%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1518      | 65.49%  |
| 1     | 612       | 26.4%   |
| 2     | 162       | 6.99%   |
| 3     | 18        | 0.78%   |
| 4     | 6         | 0.26%   |
| 7     | 1         | 0.04%   |
| 5     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 310       | 31.34%  |
| Graphics card            | 181       | 18.3%   |
| Chipcard                 | 152       | 15.37%  |
| Net/wireless             | 90        | 9.1%    |
| Multimedia controller    | 68        | 6.88%   |
| Communication controller | 45        | 4.55%   |
| Camera                   | 32        | 3.24%   |
| Unassigned class         | 29        | 2.93%   |
| Bluetooth                | 24        | 2.43%   |
| Sound                    | 17        | 1.72%   |
| Card reader              | 13        | 1.31%   |
| Net/ethernet             | 9         | 0.91%   |
| Storage                  | 5         | 0.51%   |
| Storage/ata              | 2         | 0.2%    |
| Network                  | 2         | 0.2%    |
| Modem                    | 2         | 0.2%    |
| Flash memory             | 2         | 0.2%    |
| Firewire controller      | 2         | 0.2%    |
| Storage/raid             | 1         | 0.1%    |
| Storage/nvme             | 1         | 0.1%    |
| Storage/ide              | 1         | 0.1%    |
| Dvb card                 | 1         | 0.1%    |

