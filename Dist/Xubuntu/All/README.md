Xubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Xubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu/Desktop/README.md) and [notebooks](/Dist/Xubuntu/Notebook/README.md).

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

Total: 6426

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Medion        | Akoya P2213T                | Notebook    | [2464869ce2](https://linux-hardware.org/?probe=2464869ce2) | Sep 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [af67c49814](https://linux-hardware.org/?probe=af67c49814) | Sep 06, 2023 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [1056a6ebb4](https://linux-hardware.org/?probe=1056a6ebb4) | Sep 06, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [b9dddc1ef8](https://linux-hardware.org/?probe=b9dddc1ef8) | Sep 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c404211007](https://linux-hardware.org/?probe=c404211007) | Sep 05, 2023 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [da9dc1f5d9](https://linux-hardware.org/?probe=da9dc1f5d9) | Sep 05, 2023 |
| Unknown       | SEI Robotics SEI610         | Soc         | [9b43cf14a3](https://linux-hardware.org/?probe=9b43cf14a3) | Sep 04, 2023 |
| HP            | 198E                        | Desktop     | [7f57cfbacc](https://linux-hardware.org/?probe=7f57cfbacc) | Sep 04, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e9234028f1](https://linux-hardware.org/?probe=e9234028f1) | Sep 03, 2023 |
| AMD           | A88K                        | Desktop     | [d58c29d4ad](https://linux-hardware.org/?probe=d58c29d4ad) | Sep 03, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [62f941ff29](https://linux-hardware.org/?probe=62f941ff29) | Sep 03, 2023 |
| HP            | 2B2C                        | Desktop     | [a24d61a0f4](https://linux-hardware.org/?probe=a24d61a0f4) | Sep 02, 2023 |
| HP            | 198E                        | Desktop     | [3f3cb2e64c](https://linux-hardware.org/?probe=3f3cb2e64c) | Sep 02, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [6decc4abdd](https://linux-hardware.org/?probe=6decc4abdd) | Sep 01, 2023 |
| AMD           | A88K                        | Desktop     | [08a455504f](https://linux-hardware.org/?probe=08a455504f) | Sep 01, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [281e7176d8](https://linux-hardware.org/?probe=281e7176d8) | Aug 31, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [43c2d13a44](https://linux-hardware.org/?probe=43c2d13a44) | Aug 31, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [5ef4c889a4](https://linux-hardware.org/?probe=5ef4c889a4) | Aug 31, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [32a123fc5d](https://linux-hardware.org/?probe=32a123fc5d) | Aug 31, 2023 |
| OrangePi      | Zero3                       | Soc         | [34919a3af1](https://linux-hardware.org/?probe=34919a3af1) | Aug 31, 2023 |
| Dell          | Latitude E5510              | Notebook    | [61f6df7426](https://linux-hardware.org/?probe=61f6df7426) | Aug 29, 2023 |
| HP            | Pavilion 17                 | Notebook    | [ba077d7ea1](https://linux-hardware.org/?probe=ba077d7ea1) | Aug 29, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [74ad31c9de](https://linux-hardware.org/?probe=74ad31c9de) | Aug 29, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [f94a46ad17](https://linux-hardware.org/?probe=f94a46ad17) | Aug 28, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [f520b2dd72](https://linux-hardware.org/?probe=f520b2dd72) | Aug 28, 2023 |
| Unknown       | SEI Robotics SEI610         | Soc         | [9ee073735e](https://linux-hardware.org/?probe=9ee073735e) | Aug 28, 2023 |
| ASUSTek       | ROG Strix G733PY_G733PY     | Notebook    | [b886de0613](https://linux-hardware.org/?probe=b886de0613) | Aug 28, 2023 |
| Google        | Banjo                       | Notebook    | [fcac9f460e](https://linux-hardware.org/?probe=fcac9f460e) | Aug 28, 2023 |
| HP            | Pavilion 17                 | Notebook    | [1d04c114d6](https://linux-hardware.org/?probe=1d04c114d6) | Aug 26, 2023 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [6edcb45992](https://linux-hardware.org/?probe=6edcb45992) | Aug 26, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [26c7035d28](https://linux-hardware.org/?probe=26c7035d28) | Aug 25, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [b7dce1f6e0](https://linux-hardware.org/?probe=b7dce1f6e0) | Aug 25, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [e5317c3887](https://linux-hardware.org/?probe=e5317c3887) | Aug 25, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [082e1c2cc1](https://linux-hardware.org/?probe=082e1c2cc1) | Aug 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [add8b61fa2](https://linux-hardware.org/?probe=add8b61fa2) | Aug 24, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [4d01543131](https://linux-hardware.org/?probe=4d01543131) | Aug 24, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [a7fbf7edf2](https://linux-hardware.org/?probe=a7fbf7edf2) | Aug 24, 2023 |
| Lenovo        | ThinkPad T460s 20F9003VM... | Notebook    | [e6e076d380](https://linux-hardware.org/?probe=e6e076d380) | Aug 23, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [c5484868fd](https://linux-hardware.org/?probe=c5484868fd) | Aug 23, 2023 |
| Acer          | AOD255                      | Notebook    | [06c6346db1](https://linux-hardware.org/?probe=06c6346db1) | Aug 23, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [b40144bd93](https://linux-hardware.org/?probe=b40144bd93) | Aug 22, 2023 |
| Acer          | TMP255-M                    | Notebook    | [4d5632e2d0](https://linux-hardware.org/?probe=4d5632e2d0) | Aug 22, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [d8a6683747](https://linux-hardware.org/?probe=d8a6683747) | Aug 21, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [aad70f30d7](https://linux-hardware.org/?probe=aad70f30d7) | Aug 21, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [22efc40cfd](https://linux-hardware.org/?probe=22efc40cfd) | Aug 21, 2023 |
| HP            | Presario CQ42               | Notebook    | [183f035603](https://linux-hardware.org/?probe=183f035603) | Aug 20, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [a8a0c22567](https://linux-hardware.org/?probe=a8a0c22567) | Aug 20, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [277050ce29](https://linux-hardware.org/?probe=277050ce29) | Aug 20, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [3c24c755d6](https://linux-hardware.org/?probe=3c24c755d6) | Aug 20, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [ea6fdc81ab](https://linux-hardware.org/?probe=ea6fdc81ab) | Aug 18, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [6aec4cb61e](https://linux-hardware.org/?probe=6aec4cb61e) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f626ffa833](https://linux-hardware.org/?probe=f626ffa833) | Aug 17, 2023 |
| Sony          | VGN-SR19VN                  | Notebook    | [013756c475](https://linux-hardware.org/?probe=013756c475) | Aug 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [48af3e541c](https://linux-hardware.org/?probe=48af3e541c) | Aug 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [5b482b674c](https://linux-hardware.org/?probe=5b482b674c) | Aug 16, 2023 |
| Supermicro    | H12DSG-O-CPUA               | Server      | [b4efbfe41e](https://linux-hardware.org/?probe=b4efbfe41e) | Aug 16, 2023 |
| MSI           | U90/U100                    | Notebook    | [e8ae0fbcfb](https://linux-hardware.org/?probe=e8ae0fbcfb) | Aug 14, 2023 |
| Lenovo        | ThinkPad X250 20CM001RMC    | Notebook    | [618a7e3e29](https://linux-hardware.org/?probe=618a7e3e29) | Aug 14, 2023 |
| Lenovo        | B50-50 80S2                 | Notebook    | [6c897e0c63](https://linux-hardware.org/?probe=6c897e0c63) | Aug 14, 2023 |
| Daten Tecn... | DT02-M4                     | Notebook    | [39acd7fbd5](https://linux-hardware.org/?probe=39acd7fbd5) | Aug 13, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [10d9228c2d](https://linux-hardware.org/?probe=10d9228c2d) | Aug 12, 2023 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [0ea140ff49](https://linux-hardware.org/?probe=0ea140ff49) | Aug 12, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [b2acf53271](https://linux-hardware.org/?probe=b2acf53271) | Aug 12, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [cb455d1334](https://linux-hardware.org/?probe=cb455d1334) | Aug 12, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [f8fa12cc07](https://linux-hardware.org/?probe=f8fa12cc07) | Aug 11, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [60de8d6d38](https://linux-hardware.org/?probe=60de8d6d38) | Aug 11, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [3ab135e657](https://linux-hardware.org/?probe=3ab135e657) | Aug 11, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [09000d6461](https://linux-hardware.org/?probe=09000d6461) | Aug 10, 2023 |
| Dell          | Latitude 3540               | Notebook    | [496e3ab340](https://linux-hardware.org/?probe=496e3ab340) | Aug 10, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [c05973af65](https://linux-hardware.org/?probe=c05973af65) | Aug 10, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [c5a255abcb](https://linux-hardware.org/?probe=c5a255abcb) | Aug 10, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [63f0153cfe](https://linux-hardware.org/?probe=63f0153cfe) | Aug 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [5f186cbc4d](https://linux-hardware.org/?probe=5f186cbc4d) | Aug 09, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [77ec1f7364](https://linux-hardware.org/?probe=77ec1f7364) | Aug 09, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [cc5ec06f60](https://linux-hardware.org/?probe=cc5ec06f60) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [14e4cbffd4](https://linux-hardware.org/?probe=14e4cbffd4) | Aug 08, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [150d68269d](https://linux-hardware.org/?probe=150d68269d) | Aug 08, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [047ae922f7](https://linux-hardware.org/?probe=047ae922f7) | Aug 07, 2023 |
| Dell          | Latitude 5411               | Notebook    | [2d69739196](https://linux-hardware.org/?probe=2d69739196) | Aug 07, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [341fecf811](https://linux-hardware.org/?probe=341fecf811) | Aug 06, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [7a15d18c93](https://linux-hardware.org/?probe=7a15d18c93) | Aug 06, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | Desktop     | [13f47a5399](https://linux-hardware.org/?probe=13f47a5399) | Aug 06, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [5796ca55ef](https://linux-hardware.org/?probe=5796ca55ef) | Aug 06, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0ffd23b534](https://linux-hardware.org/?probe=0ffd23b534) | Aug 04, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [cc7ae6c4e9](https://linux-hardware.org/?probe=cc7ae6c4e9) | Aug 04, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [0068fdf226](https://linux-hardware.org/?probe=0068fdf226) | Aug 04, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [122ba504c1](https://linux-hardware.org/?probe=122ba504c1) | Aug 04, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [88a569c8ee](https://linux-hardware.org/?probe=88a569c8ee) | Aug 03, 2023 |
| Pegatron      | Eureka3                     | Desktop     | [a999a00c0a](https://linux-hardware.org/?probe=a999a00c0a) | Aug 03, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [a61b8168b7](https://linux-hardware.org/?probe=a61b8168b7) | Aug 02, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [60cb0baf9d](https://linux-hardware.org/?probe=60cb0baf9d) | Aug 02, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [485793f801](https://linux-hardware.org/?probe=485793f801) | Aug 02, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [80558a1dcd](https://linux-hardware.org/?probe=80558a1dcd) | Aug 02, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [aa9fd10def](https://linux-hardware.org/?probe=aa9fd10def) | Aug 01, 2023 |
| Unknown       | Unknown                     | Soc         | [b89f7f59c6](https://linux-hardware.org/?probe=b89f7f59c6) | Aug 01, 2023 |
| Acer          | AOD255                      | Notebook    | [bdaffcb2ef](https://linux-hardware.org/?probe=bdaffcb2ef) | Jul 31, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [67fbb84480](https://linux-hardware.org/?probe=67fbb84480) | Jul 31, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [edbd410baa](https://linux-hardware.org/?probe=edbd410baa) | Jul 30, 2023 |
| SiComputer    | NL40_50CU                   | Notebook    | [95afbe5674](https://linux-hardware.org/?probe=95afbe5674) | Jul 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [1df8f3a3ed](https://linux-hardware.org/?probe=1df8f3a3ed) | Jul 29, 2023 |
| Medion        | Akoya P2213T                | Notebook    | [740da3bf14](https://linux-hardware.org/?probe=740da3bf14) | Jul 29, 2023 |
| Acer          | AOD255                      | Notebook    | [53c73b6ad3](https://linux-hardware.org/?probe=53c73b6ad3) | Jul 29, 2023 |
| HP            | ProBook 4525s               | Notebook    | [f1f6309860](https://linux-hardware.org/?probe=f1f6309860) | Jul 29, 2023 |
| Gateway       | NV57H                       | Notebook    | [efc311477f](https://linux-hardware.org/?probe=efc311477f) | Jul 28, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [136cb11fa2](https://linux-hardware.org/?probe=136cb11fa2) | Jul 28, 2023 |
| Samsung       | N250P/N145P                 | Notebook    | [6b6e675a4c](https://linux-hardware.org/?probe=6b6e675a4c) | Jul 28, 2023 |
| Acer          | Extensa 2510                | Notebook    | [b276a715eb](https://linux-hardware.org/?probe=b276a715eb) | Jul 27, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | Desktop     | [23633cafce](https://linux-hardware.org/?probe=23633cafce) | Jul 27, 2023 |
| Toshiba       | STI 005492G                 | Desktop     | [6e73cad7e4](https://linux-hardware.org/?probe=6e73cad7e4) | Jul 27, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [14b58ac305](https://linux-hardware.org/?probe=14b58ac305) | Jul 27, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [6a1aa5fbc8](https://linux-hardware.org/?probe=6a1aa5fbc8) | Jul 26, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [08fd0fea6a](https://linux-hardware.org/?probe=08fd0fea6a) | Jul 26, 2023 |
| Acer          | AOD255                      | Notebook    | [4f96dbf750](https://linux-hardware.org/?probe=4f96dbf750) | Jul 25, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [2ae4820944](https://linux-hardware.org/?probe=2ae4820944) | Jul 25, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [e1db241198](https://linux-hardware.org/?probe=e1db241198) | Jul 24, 2023 |
| Acer          | AOD255                      | Notebook    | [3543f0800e](https://linux-hardware.org/?probe=3543f0800e) | Jul 24, 2023 |
| MSI           | MEGA BOOK GX620             | Notebook    | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [ff6179199d](https://linux-hardware.org/?probe=ff6179199d) | Jul 22, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [f4e52f14b5](https://linux-hardware.org/?probe=f4e52f14b5) | Jul 22, 2023 |
| HP            | 158A                        | Desktop     | [a2a4176353](https://linux-hardware.org/?probe=a2a4176353) | Jul 22, 2023 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [1c28b8d159](https://linux-hardware.org/?probe=1c28b8d159) | Jul 22, 2023 |
| MSI           | PR601/VR603                 | Notebook    | [b982476d84](https://linux-hardware.org/?probe=b982476d84) | Jul 21, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [5bf3142c39](https://linux-hardware.org/?probe=5bf3142c39) | Jul 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [38856f8131](https://linux-hardware.org/?probe=38856f8131) | Jul 21, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [977443386e](https://linux-hardware.org/?probe=977443386e) | Jul 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [187cbf1010](https://linux-hardware.org/?probe=187cbf1010) | Jul 21, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [287298e199](https://linux-hardware.org/?probe=287298e199) | Jul 21, 2023 |
| Itautec       | Infoway w7535               | Notebook    | [bde95c0c99](https://linux-hardware.org/?probe=bde95c0c99) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [e4cc108748](https://linux-hardware.org/?probe=e4cc108748) | Jul 20, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [59cf8541b4](https://linux-hardware.org/?probe=59cf8541b4) | Jul 20, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [014e4a907f](https://linux-hardware.org/?probe=014e4a907f) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [39742015a1](https://linux-hardware.org/?probe=39742015a1) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [e69885810c](https://linux-hardware.org/?probe=e69885810c) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [02958438e7](https://linux-hardware.org/?probe=02958438e7) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [28850b9e94](https://linux-hardware.org/?probe=28850b9e94) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [35c4f96184](https://linux-hardware.org/?probe=35c4f96184) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [3b0be53d2b](https://linux-hardware.org/?probe=3b0be53d2b) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f35f948278](https://linux-hardware.org/?probe=f35f948278) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [cb12281aa1](https://linux-hardware.org/?probe=cb12281aa1) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [3bfca8e034](https://linux-hardware.org/?probe=3bfca8e034) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [667a30309b](https://linux-hardware.org/?probe=667a30309b) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [08cca00ba4](https://linux-hardware.org/?probe=08cca00ba4) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [646ef2c43e](https://linux-hardware.org/?probe=646ef2c43e) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [d1f453b1cf](https://linux-hardware.org/?probe=d1f453b1cf) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [0525e36038](https://linux-hardware.org/?probe=0525e36038) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [56571f9682](https://linux-hardware.org/?probe=56571f9682) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [b4516f6d51](https://linux-hardware.org/?probe=b4516f6d51) | Jul 19, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [94c330e355](https://linux-hardware.org/?probe=94c330e355) | Jul 19, 2023 |
| Thomson       | N15C8BK2T                   | Notebook    | [2e04333da5](https://linux-hardware.org/?probe=2e04333da5) | Jul 19, 2023 |
| Dell          | Latitude 5590               | Notebook    | [93857a3b66](https://linux-hardware.org/?probe=93857a3b66) | Jul 18, 2023 |
| Pegatron      | IPM41G                      | Desktop     | [9d29cf9820](https://linux-hardware.org/?probe=9d29cf9820) | Jul 18, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [e790be3f6e](https://linux-hardware.org/?probe=e790be3f6e) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [f0f2c5a6a7](https://linux-hardware.org/?probe=f0f2c5a6a7) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [6070a533c5](https://linux-hardware.org/?probe=6070a533c5) | Jul 17, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [08fc7fff38](https://linux-hardware.org/?probe=08fc7fff38) | Jul 17, 2023 |
| MSI           | GF65 Thin 10SER             | Notebook    | [27966135e2](https://linux-hardware.org/?probe=27966135e2) | Jul 16, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [a79d62db7c](https://linux-hardware.org/?probe=a79d62db7c) | Jul 16, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [c9a443767b](https://linux-hardware.org/?probe=c9a443767b) | Jul 16, 2023 |
| MSI           | Modern 15 A10RBS            | Notebook    | [fde24c2a13](https://linux-hardware.org/?probe=fde24c2a13) | Jul 15, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [0bd37865ac](https://linux-hardware.org/?probe=0bd37865ac) | Jul 15, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [d18c64af74](https://linux-hardware.org/?probe=d18c64af74) | Jul 14, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [e3e2452c10](https://linux-hardware.org/?probe=e3e2452c10) | Jul 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | Notebook    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| HP            | ProBook 4525s               | Notebook    | [6bae89bb98](https://linux-hardware.org/?probe=6bae89bb98) | Jul 13, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [5aacfb69aa](https://linux-hardware.org/?probe=5aacfb69aa) | Jul 12, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8807f705d0](https://linux-hardware.org/?probe=8807f705d0) | Jul 12, 2023 |
| MSI           | H81M-P32                    | Desktop     | [2bf59485a6](https://linux-hardware.org/?probe=2bf59485a6) | Jul 12, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [d4bc86a90a](https://linux-hardware.org/?probe=d4bc86a90a) | Jul 12, 2023 |
| Lenovo        | ThinkPad T460s 20FAS42W0... | Notebook    | [add1dac3cb](https://linux-hardware.org/?probe=add1dac3cb) | Jul 11, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [5477254db4](https://linux-hardware.org/?probe=5477254db4) | Jul 10, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [cc05c0d021](https://linux-hardware.org/?probe=cc05c0d021) | Jul 09, 2023 |
| Pegatron      | IPM41G                      | Desktop     | [be1f42c658](https://linux-hardware.org/?probe=be1f42c658) | Jul 09, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [db2ec8adc8](https://linux-hardware.org/?probe=db2ec8adc8) | Jul 08, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [4aba66ddfb](https://linux-hardware.org/?probe=4aba66ddfb) | Jul 07, 2023 |
| Olidata       | Stainer 8050                | Notebook    | [beb3c029a6](https://linux-hardware.org/?probe=beb3c029a6) | Jul 07, 2023 |
| Dell          | Latitude 3540               | Notebook    | [4ebbd2913f](https://linux-hardware.org/?probe=4ebbd2913f) | Jul 06, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [abc4554a51](https://linux-hardware.org/?probe=abc4554a51) | Jul 04, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [4fbf0f4e5d](https://linux-hardware.org/?probe=4fbf0f4e5d) | Jul 04, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [a9b28705a3](https://linux-hardware.org/?probe=a9b28705a3) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [983745a0d2](https://linux-hardware.org/?probe=983745a0d2) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [a5bd493e91](https://linux-hardware.org/?probe=a5bd493e91) | Jul 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [349ff94e9f](https://linux-hardware.org/?probe=349ff94e9f) | Jul 02, 2023 |
| Google        | Snappy                      | Notebook    | [683d8bf80a](https://linux-hardware.org/?probe=683d8bf80a) | Jul 02, 2023 |
| Google        | Snappy                      | Notebook    | [d3502a53cc](https://linux-hardware.org/?probe=d3502a53cc) | Jul 02, 2023 |
| HP            | Pavilion 17                 | Notebook    | [e6daccb5b9](https://linux-hardware.org/?probe=e6daccb5b9) | Jul 02, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [7c14851b62](https://linux-hardware.org/?probe=7c14851b62) | Jul 02, 2023 |
| Chuwi         | CoreBox                     | Mini pc     | [7a2a217b46](https://linux-hardware.org/?probe=7a2a217b46) | Jul 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [f252a559f2](https://linux-hardware.org/?probe=f252a559f2) | Jul 02, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [b9d71582c0](https://linux-hardware.org/?probe=b9d71582c0) | Jul 01, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [5270a5ddc7](https://linux-hardware.org/?probe=5270a5ddc7) | Jul 01, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [72d0376041](https://linux-hardware.org/?probe=72d0376041) | Jul 01, 2023 |
| Dynabook      | B65/ER                      | Notebook    | [8f6f243e98](https://linux-hardware.org/?probe=8f6f243e98) | Jul 01, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [196daaa768](https://linux-hardware.org/?probe=196daaa768) | Jun 30, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [8e7db66929](https://linux-hardware.org/?probe=8e7db66929) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [79f2cae4d6](https://linux-hardware.org/?probe=79f2cae4d6) | Jun 30, 2023 |
| Google        | Fleex                       | Notebook    | [7e3eb2d4f9](https://linux-hardware.org/?probe=7e3eb2d4f9) | Jun 30, 2023 |
| HP            | Unknown                     | Notebook    | [0f4ae63ce0](https://linux-hardware.org/?probe=0f4ae63ce0) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [06d27800c2](https://linux-hardware.org/?probe=06d27800c2) | Jun 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [e46c7340d7](https://linux-hardware.org/?probe=e46c7340d7) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| ASUSTek       | H61M-CS                     | Desktop     | [2878c06857](https://linux-hardware.org/?probe=2878c06857) | Jun 26, 2023 |
| HP            | Unknown                     | Notebook    | [d681765bb7](https://linux-hardware.org/?probe=d681765bb7) | Jun 26, 2023 |
| HP            | 339A                        | Desktop     | [ff38f43250](https://linux-hardware.org/?probe=ff38f43250) | Jun 25, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [8152698df7](https://linux-hardware.org/?probe=8152698df7) | Jun 25, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [338b2e7db3](https://linux-hardware.org/?probe=338b2e7db3) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [7d1989fd84](https://linux-hardware.org/?probe=7d1989fd84) | Jun 24, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [a39abe1278](https://linux-hardware.org/?probe=a39abe1278) | Jun 24, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [89116ab6be](https://linux-hardware.org/?probe=89116ab6be) | Jun 24, 2023 |
| Alienware     | 18                          | Notebook    | [047bc74541](https://linux-hardware.org/?probe=047bc74541) | Jun 24, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [0908f99494](https://linux-hardware.org/?probe=0908f99494) | Jun 23, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [1999834725](https://linux-hardware.org/?probe=1999834725) | Jun 23, 2023 |
| Google        | Link                        | Notebook    | [b8284753ca](https://linux-hardware.org/?probe=b8284753ca) | Jun 22, 2023 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [2e4e948549](https://linux-hardware.org/?probe=2e4e948549) | Jun 22, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [8f879f5566](https://linux-hardware.org/?probe=8f879f5566) | Jun 21, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [66736b8fbb](https://linux-hardware.org/?probe=66736b8fbb) | Jun 21, 2023 |
| HP            | Unknown                     | Notebook    | [4f27a83f9e](https://linux-hardware.org/?probe=4f27a83f9e) | Jun 21, 2023 |
| HP            | 18E7                        | Desktop     | [3b872d2a88](https://linux-hardware.org/?probe=3b872d2a88) | Jun 20, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [c2313cf371](https://linux-hardware.org/?probe=c2313cf371) | Jun 20, 2023 |
| Lenovo        | 1057 SDK0T76530 WIN 3556... | Desktop     | [0502b8f756](https://linux-hardware.org/?probe=0502b8f756) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [a7238c71a7](https://linux-hardware.org/?probe=a7238c71a7) | Jun 20, 2023 |
| TUXEDO        | P65xRP                      | Notebook    | [cfefc9c13a](https://linux-hardware.org/?probe=cfefc9c13a) | Jun 20, 2023 |
| Intel         | H61                         | Desktop     | [d8de2bb1a7](https://linux-hardware.org/?probe=d8de2bb1a7) | Jun 20, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [ade4d4c90c](https://linux-hardware.org/?probe=ade4d4c90c) | Jun 19, 2023 |
| Standard      | Unknown                     | Desktop     | [4956d7fc21](https://linux-hardware.org/?probe=4956d7fc21) | Jun 18, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [154f9809e6](https://linux-hardware.org/?probe=154f9809e6) | Jun 18, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [66ce1a98a8](https://linux-hardware.org/?probe=66ce1a98a8) | Jun 18, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [10b3b517f3](https://linux-hardware.org/?probe=10b3b517f3) | Jun 18, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [4f0ec49165](https://linux-hardware.org/?probe=4f0ec49165) | Jun 17, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [601d7611be](https://linux-hardware.org/?probe=601d7611be) | Jun 17, 2023 |
| Unknown       | Minix Neo U9-H              | Soc         | [7b845b4b0b](https://linux-hardware.org/?probe=7b845b4b0b) | Jun 16, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | Desktop     | [53a0b2f173](https://linux-hardware.org/?probe=53a0b2f173) | Jun 15, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [5a31ac8b21](https://linux-hardware.org/?probe=5a31ac8b21) | Jun 15, 2023 |
| HP            | Unknown                     | Notebook    | [00c49ad567](https://linux-hardware.org/?probe=00c49ad567) | Jun 14, 2023 |
| Samsung       | 760XDA                      | Notebook    | [f0decf4dbe](https://linux-hardware.org/?probe=f0decf4dbe) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [04f1fdc3c9](https://linux-hardware.org/?probe=04f1fdc3c9) | Jun 14, 2023 |
| Dell          | Latitude E5270              | Notebook    | [49f184b9e9](https://linux-hardware.org/?probe=49f184b9e9) | Jun 13, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [b0afd2fa7b](https://linux-hardware.org/?probe=b0afd2fa7b) | Jun 13, 2023 |
| Dell          | Latitude 5411               | Notebook    | [c0292655dd](https://linux-hardware.org/?probe=c0292655dd) | Jun 13, 2023 |
| Xunlong       | Orange Pi PC                | Soc         | [2a93adb1f0](https://linux-hardware.org/?probe=2a93adb1f0) | Jun 12, 2023 |
| Unknown       | Unknown                     | Other       | [00ad49fe2f](https://linux-hardware.org/?probe=00ad49fe2f) | Jun 12, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [69f20a331c](https://linux-hardware.org/?probe=69f20a331c) | Jun 12, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [61e759f7db](https://linux-hardware.org/?probe=61e759f7db) | Jun 11, 2023 |
| Biostar       | TPower I45                  | Desktop     | [b88767bce0](https://linux-hardware.org/?probe=b88767bce0) | Jun 11, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [1cfac1228c](https://linux-hardware.org/?probe=1cfac1228c) | Jun 10, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [427db0e78b](https://linux-hardware.org/?probe=427db0e78b) | Jun 10, 2023 |
| TYAN Compu... | S7010                       | Server      | [a8b96e89f2](https://linux-hardware.org/?probe=a8b96e89f2) | Jun 10, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [2c8c27897b](https://linux-hardware.org/?probe=2c8c27897b) | Jun 09, 2023 |
| MSI           | A55M-E35                    | Desktop     | [7800efb785](https://linux-hardware.org/?probe=7800efb785) | Jun 08, 2023 |
| Acer          | AO722                       | Notebook    | [a57b6cf2ff](https://linux-hardware.org/?probe=a57b6cf2ff) | Jun 08, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [2f5adf59a3](https://linux-hardware.org/?probe=2f5adf59a3) | Jun 07, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [b661a14644](https://linux-hardware.org/?probe=b661a14644) | Jun 07, 2023 |
| Acer          | AO722                       | Notebook    | [8840b1284b](https://linux-hardware.org/?probe=8840b1284b) | Jun 06, 2023 |
| Dell          | Precision 5510              | Notebook    | [9888f3aedd](https://linux-hardware.org/?probe=9888f3aedd) | Jun 06, 2023 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [83988ad739](https://linux-hardware.org/?probe=83988ad739) | Jun 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [46751741ef](https://linux-hardware.org/?probe=46751741ef) | Jun 05, 2023 |
| LORD ELECT... | I915 Series V1.0            | Desktop     | [d693b7baec](https://linux-hardware.org/?probe=d693b7baec) | Jun 05, 2023 |
| HP            | 8768 A                      | Desktop     | [17d0560a85](https://linux-hardware.org/?probe=17d0560a85) | Jun 05, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [741e39b142](https://linux-hardware.org/?probe=741e39b142) | Jun 05, 2023 |
| HP            | 21B4 A01                    | Desktop     | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| Lenovo        | V560                        | Notebook    | [b2564e07cc](https://linux-hardware.org/?probe=b2564e07cc) | Jun 03, 2023 |
| SK hynix      | HyBook                      | Notebook    | [c25f19e040](https://linux-hardware.org/?probe=c25f19e040) | Jun 03, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [c716b12ee2](https://linux-hardware.org/?probe=c716b12ee2) | Jun 02, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [1d9f5bc60f](https://linux-hardware.org/?probe=1d9f5bc60f) | Jun 02, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1383313bbb](https://linux-hardware.org/?probe=1383313bbb) | May 31, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [d2912dfb69](https://linux-hardware.org/?probe=d2912dfb69) | May 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [caa2968187](https://linux-hardware.org/?probe=caa2968187) | May 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [9390923473](https://linux-hardware.org/?probe=9390923473) | May 30, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [f9a2c23bfa](https://linux-hardware.org/?probe=f9a2c23bfa) | May 30, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [88f3c7f5e5](https://linux-hardware.org/?probe=88f3c7f5e5) | May 29, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [ae0b46c29f](https://linux-hardware.org/?probe=ae0b46c29f) | May 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [9051961e40](https://linux-hardware.org/?probe=9051961e40) | May 28, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [33eb5df96b](https://linux-hardware.org/?probe=33eb5df96b) | May 26, 2023 |
| Acer          | Veriton N4620G              | Desktop     | [4f2cc019b8](https://linux-hardware.org/?probe=4f2cc019b8) | May 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [df5ea78282](https://linux-hardware.org/?probe=df5ea78282) | May 25, 2023 |
| Dell          | Latitude 7390               | Notebook    | [21653cfe83](https://linux-hardware.org/?probe=21653cfe83) | May 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [10adda3362](https://linux-hardware.org/?probe=10adda3362) | May 25, 2023 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [7788147663](https://linux-hardware.org/?probe=7788147663) | May 24, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [2dfed39533](https://linux-hardware.org/?probe=2dfed39533) | May 24, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [b2ade78a38](https://linux-hardware.org/?probe=b2ade78a38) | May 24, 2023 |
| Lenovo        | ThinkPad W500 40626NG       | Notebook    | [9466f83af8](https://linux-hardware.org/?probe=9466f83af8) | May 22, 2023 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [91bb4c8e5d](https://linux-hardware.org/?probe=91bb4c8e5d) | May 22, 2023 |
| ASRock        | A520M Phantom Gaming 4      | Desktop     | [50b46e4d8c](https://linux-hardware.org/?probe=50b46e4d8c) | May 22, 2023 |
| Dell          | Latitude E4200              | Notebook    | [f352cc3ee4](https://linux-hardware.org/?probe=f352cc3ee4) | May 22, 2023 |
| Unknown       | 1.0                         | Desktop     | [54d3a069a4](https://linux-hardware.org/?probe=54d3a069a4) | May 22, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [bfaa8e099f](https://linux-hardware.org/?probe=bfaa8e099f) | May 21, 2023 |
| HP            | 0A08h                       | Desktop     | [9d159d2637](https://linux-hardware.org/?probe=9d159d2637) | May 21, 2023 |
| Dell          | G3 3500                     | Notebook    | [cbe9c2f010](https://linux-hardware.org/?probe=cbe9c2f010) | May 21, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [9419d4d25c](https://linux-hardware.org/?probe=9419d4d25c) | May 19, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [584948af65](https://linux-hardware.org/?probe=584948af65) | May 19, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0b802ad297](https://linux-hardware.org/?probe=0b802ad297) | May 19, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bd7e95bf66](https://linux-hardware.org/?probe=bd7e95bf66) | May 18, 2023 |
| Pegatron      | Benicia                     | Desktop     | [8d49889e39](https://linux-hardware.org/?probe=8d49889e39) | May 18, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [84bd50bc27](https://linux-hardware.org/?probe=84bd50bc27) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3a7b647f0b](https://linux-hardware.org/?probe=3a7b647f0b) | May 17, 2023 |
| HP            | 09F8h                       | Desktop     | [380bbcda71](https://linux-hardware.org/?probe=380bbcda71) | May 17, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [f48dba1e04](https://linux-hardware.org/?probe=f48dba1e04) | May 16, 2023 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [84d5e196da](https://linux-hardware.org/?probe=84d5e196da) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7661V3L        | Notebook    | [5714171d2a](https://linux-hardware.org/?probe=5714171d2a) | May 14, 2023 |
| Acer          | Aspire V5-552G              | Notebook    | [4384294484](https://linux-hardware.org/?probe=4384294484) | May 14, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | Notebook    | [7e178a2a32](https://linux-hardware.org/?probe=7e178a2a32) | May 13, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [0b0b5e02cc](https://linux-hardware.org/?probe=0b0b5e02cc) | May 13, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [87edc3a632](https://linux-hardware.org/?probe=87edc3a632) | May 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d5bd5c8930](https://linux-hardware.org/?probe=d5bd5c8930) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [3191d9fca4](https://linux-hardware.org/?probe=3191d9fca4) | May 11, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2d3692d380](https://linux-hardware.org/?probe=2d3692d380) | May 11, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [3c43bfe7bc](https://linux-hardware.org/?probe=3c43bfe7bc) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7b53d1c3dc](https://linux-hardware.org/?probe=7b53d1c3dc) | May 11, 2023 |
| Dell          | Latitude E4310              | Notebook    | [84d1a3fda9](https://linux-hardware.org/?probe=84d1a3fda9) | May 11, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d6a837c94d](https://linux-hardware.org/?probe=d6a837c94d) | May 11, 2023 |
| Unknown       | Kontron BL i.MX8MM OSM-S... | Soc         | [958fed11ae](https://linux-hardware.org/?probe=958fed11ae) | May 10, 2023 |
| Google        | Edgar                       | Notebook    | [372d5c177f](https://linux-hardware.org/?probe=372d5c177f) | May 10, 2023 |
| Gigabyte      | A7 K1                       | Notebook    | [1c37df2d10](https://linux-hardware.org/?probe=1c37df2d10) | May 09, 2023 |
| Google        | Snappy                      | Notebook    | [52836871bb](https://linux-hardware.org/?probe=52836871bb) | May 09, 2023 |
| Google        | Snappy                      | Notebook    | [a026aff306](https://linux-hardware.org/?probe=a026aff306) | May 09, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [9726453f00](https://linux-hardware.org/?probe=9726453f00) | May 09, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [0f322b6e3f](https://linux-hardware.org/?probe=0f322b6e3f) | May 08, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [7ac436d763](https://linux-hardware.org/?probe=7ac436d763) | May 08, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [a915e84a9a](https://linux-hardware.org/?probe=a915e84a9a) | May 08, 2023 |
| Google        | Auron_Yuna                  | Notebook    | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [c7d1eac585](https://linux-hardware.org/?probe=c7d1eac585) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [ebafddb3f1](https://linux-hardware.org/?probe=ebafddb3f1) | May 06, 2023 |
| MSI           | MEG Z590 ACE GOLD EDITIO... | Desktop     | [e34348c1b5](https://linux-hardware.org/?probe=e34348c1b5) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [2d41ef08f2](https://linux-hardware.org/?probe=2d41ef08f2) | May 05, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f5f0edbac8](https://linux-hardware.org/?probe=f5f0edbac8) | May 05, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [307dfb1c46](https://linux-hardware.org/?probe=307dfb1c46) | May 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [c693555567](https://linux-hardware.org/?probe=c693555567) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [bbac197d5d](https://linux-hardware.org/?probe=bbac197d5d) | May 04, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [11e132041b](https://linux-hardware.org/?probe=11e132041b) | May 04, 2023 |
| HP            | ENVY 4                      | Notebook    | [20395a1739](https://linux-hardware.org/?probe=20395a1739) | May 04, 2023 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [b735e1019b](https://linux-hardware.org/?probe=b735e1019b) | May 03, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [d8b2bfb82c](https://linux-hardware.org/?probe=d8b2bfb82c) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [2f6fd9e5b0](https://linux-hardware.org/?probe=2f6fd9e5b0) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [6cbfaabd66](https://linux-hardware.org/?probe=6cbfaabd66) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [4762d9bb4e](https://linux-hardware.org/?probe=4762d9bb4e) | May 03, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| HP            | 15                          | Notebook    | [17817f5320](https://linux-hardware.org/?probe=17817f5320) | May 02, 2023 |
| Dell          | Latitude E7270              | Notebook    | [62c1cdc600](https://linux-hardware.org/?probe=62c1cdc600) | May 02, 2023 |
| Dell          | Latitude E7270              | Notebook    | [96e1a00bae](https://linux-hardware.org/?probe=96e1a00bae) | May 02, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [36f4134c6b](https://linux-hardware.org/?probe=36f4134c6b) | May 01, 2023 |
| Toshiba       | EQUIUM P200                 | Notebook    | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Acer          | Peppy                       | Notebook    | [dcac703c46](https://linux-hardware.org/?probe=dcac703c46) | Apr 30, 2023 |
| Acer          | Extensa 5620                | Notebook    | [415396fa78](https://linux-hardware.org/?probe=415396fa78) | Apr 30, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| HP            | 158A                        | Desktop     | [fb7aef7883](https://linux-hardware.org/?probe=fb7aef7883) | Apr 28, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [95d59e1bc3](https://linux-hardware.org/?probe=95d59e1bc3) | Apr 28, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [6daa7002c8](https://linux-hardware.org/?probe=6daa7002c8) | Apr 27, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dfd3d8a5c5](https://linux-hardware.org/?probe=dfd3d8a5c5) | Apr 27, 2023 |
| MSI           | GP65 Leopard 10SDK          | Notebook    | [fc66ccccde](https://linux-hardware.org/?probe=fc66ccccde) | Apr 27, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [09f98983fd](https://linux-hardware.org/?probe=09f98983fd) | Apr 27, 2023 |
| SGIN          | M15                         | Notebook    | [ac5d947f22](https://linux-hardware.org/?probe=ac5d947f22) | Apr 27, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [4382f0cce7](https://linux-hardware.org/?probe=4382f0cce7) | Apr 27, 2023 |
| HP            | 1632                        | Desktop     | [b818834691](https://linux-hardware.org/?probe=b818834691) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [caae9b5992](https://linux-hardware.org/?probe=caae9b5992) | Apr 26, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| HP            | 158A                        | Desktop     | [c3189bccb1](https://linux-hardware.org/?probe=c3189bccb1) | Apr 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [98ed5e9a2e](https://linux-hardware.org/?probe=98ed5e9a2e) | Apr 25, 2023 |
| HP            | 470 17 inch G9 Notebook ... | Notebook    | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | Notebook    | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [43f6a6180a](https://linux-hardware.org/?probe=43f6a6180a) | Apr 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [76c4edb7f3](https://linux-hardware.org/?probe=76c4edb7f3) | Apr 23, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [4611a1d998](https://linux-hardware.org/?probe=4611a1d998) | Apr 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C50... | Notebook    | [77cfc9d5b2](https://linux-hardware.org/?probe=77cfc9d5b2) | Apr 22, 2023 |
| HP            | 0AECh D                     | Desktop     | [827246f901](https://linux-hardware.org/?probe=827246f901) | Apr 22, 2023 |
| OrangePi      | 4 (DT)                      | Soc         | [a1c0a82172](https://linux-hardware.org/?probe=a1c0a82172) | Apr 20, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [3e1880b375](https://linux-hardware.org/?probe=3e1880b375) | Apr 20, 2023 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [9ff4edba5b](https://linux-hardware.org/?probe=9ff4edba5b) | Apr 20, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [e062ca363c](https://linux-hardware.org/?probe=e062ca363c) | Apr 20, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [704778a577](https://linux-hardware.org/?probe=704778a577) | Apr 19, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [9f2a1a2c93](https://linux-hardware.org/?probe=9f2a1a2c93) | Apr 19, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [222f45e8c6](https://linux-hardware.org/?probe=222f45e8c6) | Apr 18, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [9539ccfd4d](https://linux-hardware.org/?probe=9539ccfd4d) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4c6934e946](https://linux-hardware.org/?probe=4c6934e946) | Apr 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5fc4a56d59](https://linux-hardware.org/?probe=5fc4a56d59) | Apr 17, 2023 |
| ASRock        | N3700-ITX                   | Desktop     | [849679b442](https://linux-hardware.org/?probe=849679b442) | Apr 17, 2023 |
| ASRock        | X370 Killer SLI             | Desktop     | [912a7f830b](https://linux-hardware.org/?probe=912a7f830b) | Apr 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7b5363bc3e](https://linux-hardware.org/?probe=7b5363bc3e) | Apr 16, 2023 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [4cb39d1136](https://linux-hardware.org/?probe=4cb39d1136) | Apr 15, 2023 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [b901ff7e98](https://linux-hardware.org/?probe=b901ff7e98) | Apr 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [7f4ed3cfde](https://linux-hardware.org/?probe=7f4ed3cfde) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [93fae77e6c](https://linux-hardware.org/?probe=93fae77e6c) | Apr 13, 2023 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [ae144ff4c8](https://linux-hardware.org/?probe=ae144ff4c8) | Apr 12, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Dell          | 060K5C A04                  | Server      | [962b265260](https://linux-hardware.org/?probe=962b265260) | Apr 11, 2023 |
| ASRock        | Z77 Pro4                    | Desktop     | [7f718ab68f](https://linux-hardware.org/?probe=7f718ab68f) | Apr 10, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e99e4b1fac](https://linux-hardware.org/?probe=e99e4b1fac) | Apr 10, 2023 |
| Medion        | MS-7848                     | Desktop     | [40e46961a4](https://linux-hardware.org/?probe=40e46961a4) | Apr 08, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [71ee0575d4](https://linux-hardware.org/?probe=71ee0575d4) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e9dde876e9](https://linux-hardware.org/?probe=e9dde876e9) | Apr 08, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [c7444ac7f0](https://linux-hardware.org/?probe=c7444ac7f0) | Apr 07, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [fc1b119dca](https://linux-hardware.org/?probe=fc1b119dca) | Apr 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [08e8eb7cea](https://linux-hardware.org/?probe=08e8eb7cea) | Apr 05, 2023 |
| ASUSTek       | X58C                        | Notebook    | [ff580ffa57](https://linux-hardware.org/?probe=ff580ffa57) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [2ac5f02bb5](https://linux-hardware.org/?probe=2ac5f02bb5) | Apr 05, 2023 |
| ASUSTek       | X58C                        | Notebook    | [ae9888c407](https://linux-hardware.org/?probe=ae9888c407) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Dell          | Latitude E6400              | Notebook    | [5aa68e620c](https://linux-hardware.org/?probe=5aa68e620c) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | Notebook    | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [86de0a83c3](https://linux-hardware.org/?probe=86de0a83c3) | Apr 04, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [9f0d854259](https://linux-hardware.org/?probe=9f0d854259) | Apr 03, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [1b8983e24d](https://linux-hardware.org/?probe=1b8983e24d) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Nvidia        | Tegra                       | Soc         | [d57318f254](https://linux-hardware.org/?probe=d57318f254) | Apr 02, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [25c3fdc9f7](https://linux-hardware.org/?probe=25c3fdc9f7) | Apr 02, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [8b4f79808a](https://linux-hardware.org/?probe=8b4f79808a) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [f7cdc4223d](https://linux-hardware.org/?probe=f7cdc4223d) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [8bc61e0fcd](https://linux-hardware.org/?probe=8bc61e0fcd) | Mar 31, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [deedee079c](https://linux-hardware.org/?probe=deedee079c) | Mar 31, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [81c43aeb0d](https://linux-hardware.org/?probe=81c43aeb0d) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [0f26b74917](https://linux-hardware.org/?probe=0f26b74917) | Mar 30, 2023 |
| Medion        | S321X                       | Notebook    | [4c02136dda](https://linux-hardware.org/?probe=4c02136dda) | Mar 30, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [a46eb24b2a](https://linux-hardware.org/?probe=a46eb24b2a) | Mar 29, 2023 |
| Gateway       | LT27                        | Notebook    | [4697cead5f](https://linux-hardware.org/?probe=4697cead5f) | Mar 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [94cd15664b](https://linux-hardware.org/?probe=94cd15664b) | Mar 27, 2023 |
| MSI           | MS-AA8B 100                 | All in one  | [8f698075ee](https://linux-hardware.org/?probe=8f698075ee) | Mar 27, 2023 |
| MSI           | MEG B550 UNIFY              | Desktop     | [492a70f1c3](https://linux-hardware.org/?probe=492a70f1c3) | Mar 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a7ff24abc4](https://linux-hardware.org/?probe=a7ff24abc4) | Mar 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [8d5a135264](https://linux-hardware.org/?probe=8d5a135264) | Mar 26, 2023 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [0fc1609d81](https://linux-hardware.org/?probe=0fc1609d81) | Mar 26, 2023 |
| Samsung       | RV408/RV508                 | Notebook    | [5f5efa7edc](https://linux-hardware.org/?probe=5f5efa7edc) | Mar 25, 2023 |
| Samsung       | RV408/RV508                 | Notebook    | [cce3fdd054](https://linux-hardware.org/?probe=cce3fdd054) | Mar 25, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [426c7d7939](https://linux-hardware.org/?probe=426c7d7939) | Mar 25, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [a822425dcf](https://linux-hardware.org/?probe=a822425dcf) | Mar 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [3d8b7a6d89](https://linux-hardware.org/?probe=3d8b7a6d89) | Mar 25, 2023 |
| MSI           | H81M-E33                    | Desktop     | [47f031e68c](https://linux-hardware.org/?probe=47f031e68c) | Mar 25, 2023 |
| HP            | 158A                        | Desktop     | [9ed0f8f65f](https://linux-hardware.org/?probe=9ed0f8f65f) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [34d3fc12b2](https://linux-hardware.org/?probe=34d3fc12b2) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f7aaf1dcd0](https://linux-hardware.org/?probe=f7aaf1dcd0) | Mar 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Gigabyte      | AERO 15WV8                  | Notebook    | [379c88860a](https://linux-hardware.org/?probe=379c88860a) | Mar 23, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [204b7c3324](https://linux-hardware.org/?probe=204b7c3324) | Mar 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [bbd16627c2](https://linux-hardware.org/?probe=bbd16627c2) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [f97f90f7ce](https://linux-hardware.org/?probe=f97f90f7ce) | Mar 22, 2023 |
| TrekStor      | Notebook Slim S130          | Notebook    | [6c3a6e7e53](https://linux-hardware.org/?probe=6c3a6e7e53) | Mar 22, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [fdeb2e4e3b](https://linux-hardware.org/?probe=fdeb2e4e3b) | Mar 22, 2023 |
| Getac         | F110G3                      | Notebook    | [792ac98040](https://linux-hardware.org/?probe=792ac98040) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [5c07e530e9](https://linux-hardware.org/?probe=5c07e530e9) | Mar 21, 2023 |
| Biostar       | TZ77A                       | Desktop     | [9484c73494](https://linux-hardware.org/?probe=9484c73494) | Mar 21, 2023 |
| HP            | 158A                        | Desktop     | [033f7a5abd](https://linux-hardware.org/?probe=033f7a5abd) | Mar 21, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [62d90f07ba](https://linux-hardware.org/?probe=62d90f07ba) | Mar 20, 2023 |
| Lenovo        | ThinkPad T530 2429LT7       | Notebook    | [ebb127610b](https://linux-hardware.org/?probe=ebb127610b) | Mar 20, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [653b1820fe](https://linux-hardware.org/?probe=653b1820fe) | Mar 20, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [fd4d05d961](https://linux-hardware.org/?probe=fd4d05d961) | Mar 20, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [00b550c606](https://linux-hardware.org/?probe=00b550c606) | Mar 18, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [c6ea9d7f10](https://linux-hardware.org/?probe=c6ea9d7f10) | Mar 18, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [a174d9ea53](https://linux-hardware.org/?probe=a174d9ea53) | Mar 17, 2023 |
| Amlogic       | Meson8B                     | Soc         | [c564829ae4](https://linux-hardware.org/?probe=c564829ae4) | Mar 17, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [4efa1b8600](https://linux-hardware.org/?probe=4efa1b8600) | Mar 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [182bd8cca1](https://linux-hardware.org/?probe=182bd8cca1) | Mar 16, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4cad3cfe12](https://linux-hardware.org/?probe=4cad3cfe12) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 20RES05U00     | Notebook    | [7047c529ef](https://linux-hardware.org/?probe=7047c529ef) | Mar 13, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [406ea57f9c](https://linux-hardware.org/?probe=406ea57f9c) | Mar 13, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [a6af61dfb4](https://linux-hardware.org/?probe=a6af61dfb4) | Mar 13, 2023 |
| Gigabyte      | 8IR533                      | Desktop     | [ee9bb6485a](https://linux-hardware.org/?probe=ee9bb6485a) | Mar 12, 2023 |
| Gigabyte      | 8IR533                      | Desktop     | [9e5837ddaf](https://linux-hardware.org/?probe=9e5837ddaf) | Mar 12, 2023 |
| Google        | Kefka                       | Notebook    | [58abcf00e9](https://linux-hardware.org/?probe=58abcf00e9) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [d5b197e7f2](https://linux-hardware.org/?probe=d5b197e7f2) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [14de22ae05](https://linux-hardware.org/?probe=14de22ae05) | Mar 11, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [b7de8d093d](https://linux-hardware.org/?probe=b7de8d093d) | Mar 11, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [728697bff3](https://linux-hardware.org/?probe=728697bff3) | Mar 11, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ac565d5d7d](https://linux-hardware.org/?probe=ac565d5d7d) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | Notebook    | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| Apple         | MacBookPro1,1               | Notebook    | [105d39532f](https://linux-hardware.org/?probe=105d39532f) | Mar 10, 2023 |
| Foxconn       | ETON                        | Desktop     | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ad41e0e370](https://linux-hardware.org/?probe=ad41e0e370) | Mar 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [82551d929c](https://linux-hardware.org/?probe=82551d929c) | Mar 09, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [a35bb278ba](https://linux-hardware.org/?probe=a35bb278ba) | Mar 09, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [13418c9605](https://linux-hardware.org/?probe=13418c9605) | Mar 08, 2023 |
| Foxconn       | ETON                        | Desktop     | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [44509323b0](https://linux-hardware.org/?probe=44509323b0) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [2d093cc3ef](https://linux-hardware.org/?probe=2d093cc3ef) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [57d690358f](https://linux-hardware.org/?probe=57d690358f) | Mar 08, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [04ef76ee4a](https://linux-hardware.org/?probe=04ef76ee4a) | Mar 07, 2023 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [66f6a0491e](https://linux-hardware.org/?probe=66f6a0491e) | Mar 07, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [c0f8008427](https://linux-hardware.org/?probe=c0f8008427) | Mar 07, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [32dedf99a8](https://linux-hardware.org/?probe=32dedf99a8) | Mar 07, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [5bd9a1c0d2](https://linux-hardware.org/?probe=5bd9a1c0d2) | Mar 07, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [963b41587c](https://linux-hardware.org/?probe=963b41587c) | Mar 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [a3dbc9b45e](https://linux-hardware.org/?probe=a3dbc9b45e) | Mar 07, 2023 |
| Toshiba       | Satellite L775              | Notebook    | [75a1948a64](https://linux-hardware.org/?probe=75a1948a64) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [9404cddcdf](https://linux-hardware.org/?probe=9404cddcdf) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| Microtech     | ebookPro                    | Notebook    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [64c40ef1a4](https://linux-hardware.org/?probe=64c40ef1a4) | Mar 06, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [439ec46914](https://linux-hardware.org/?probe=439ec46914) | Mar 05, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ec9c2f21a5](https://linux-hardware.org/?probe=ec9c2f21a5) | Mar 05, 2023 |
| Radxa         | ROCK Pi 4C+                 | Soc         | [e513434675](https://linux-hardware.org/?probe=e513434675) | Mar 04, 2023 |
| Radxa         | ROCK Pi 4C+                 | Soc         | [5c3d9047bd](https://linux-hardware.org/?probe=5c3d9047bd) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| OEM           | Unknown                     | Desktop     | [d0f1ae246c](https://linux-hardware.org/?probe=d0f1ae246c) | Mar 03, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [e367c45f3b](https://linux-hardware.org/?probe=e367c45f3b) | Mar 03, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [c803be2765](https://linux-hardware.org/?probe=c803be2765) | Mar 02, 2023 |
| Google        | Nautilus                    | Convertible | [5aff7271ac](https://linux-hardware.org/?probe=5aff7271ac) | Mar 02, 2023 |
| AZW           | GTR V01                     | Mini pc     | [09e66839c3](https://linux-hardware.org/?probe=09e66839c3) | Mar 01, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [aeb7d7a9f4](https://linux-hardware.org/?probe=aeb7d7a9f4) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [83e6da010b](https://linux-hardware.org/?probe=83e6da010b) | Feb 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [1a407f82b9](https://linux-hardware.org/?probe=1a407f82b9) | Feb 27, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [e538527e6c](https://linux-hardware.org/?probe=e538527e6c) | Feb 26, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [525ac20362](https://linux-hardware.org/?probe=525ac20362) | Feb 26, 2023 |
| Alienware     | 17 R4                       | Notebook    | [bfeccbf9f3](https://linux-hardware.org/?probe=bfeccbf9f3) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| AZW           | U59                         | Desktop     | [b574c32b53](https://linux-hardware.org/?probe=b574c32b53) | Feb 24, 2023 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [2645328f34](https://linux-hardware.org/?probe=2645328f34) | Feb 23, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [43b2cca281](https://linux-hardware.org/?probe=43b2cca281) | Feb 23, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| Dell          | Studio 1450                 | Notebook    | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | Notebook    | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| Acer          | Aspire 7736                 | Notebook    | [479496a645](https://linux-hardware.org/?probe=479496a645) | Feb 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [751f76b561](https://linux-hardware.org/?probe=751f76b561) | Feb 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [c9adb74693](https://linux-hardware.org/?probe=c9adb74693) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [656629ffba](https://linux-hardware.org/?probe=656629ffba) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [4a9dcac308](https://linux-hardware.org/?probe=4a9dcac308) | Feb 19, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [d808827823](https://linux-hardware.org/?probe=d808827823) | Feb 19, 2023 |
| HP            | 158A                        | Desktop     | [ce217224ba](https://linux-hardware.org/?probe=ce217224ba) | Feb 19, 2023 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [e85ff6e5c3](https://linux-hardware.org/?probe=e85ff6e5c3) | Feb 18, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [51cf60bd9b](https://linux-hardware.org/?probe=51cf60bd9b) | Feb 18, 2023 |
| Sony          | VPCEA3S1E                   | Notebook    | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [0dbeeea38c](https://linux-hardware.org/?probe=0dbeeea38c) | Feb 16, 2023 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [8cd6645d36](https://linux-hardware.org/?probe=8cd6645d36) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [40c415883e](https://linux-hardware.org/?probe=40c415883e) | Feb 16, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [0b622220d7](https://linux-hardware.org/?probe=0b622220d7) | Feb 15, 2023 |
| Pegatron      | EVE                         | Desktop     | [0bde64bb64](https://linux-hardware.org/?probe=0bde64bb64) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [2334fc688f](https://linux-hardware.org/?probe=2334fc688f) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [21ad600245](https://linux-hardware.org/?probe=21ad600245) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [e2f49b2fe4](https://linux-hardware.org/?probe=e2f49b2fe4) | Feb 14, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [6e1d13cecb](https://linux-hardware.org/?probe=6e1d13cecb) | Feb 14, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [33e3d93b19](https://linux-hardware.org/?probe=33e3d93b19) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| ASRock        | AOD790GX/128M               | Desktop     | [693f4f40f8](https://linux-hardware.org/?probe=693f4f40f8) | Feb 13, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [bb037d75a7](https://linux-hardware.org/?probe=bb037d75a7) | Feb 13, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [dd2d87798a](https://linux-hardware.org/?probe=dd2d87798a) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Sony          | VPCX11Z6R                   | Notebook    | [ad87a45a26](https://linux-hardware.org/?probe=ad87a45a26) | Feb 12, 2023 |
| Packard Be... | DOT S                       | Notebook    | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| ASUSTek       | P8H77-I                     | Desktop     | [74013e0688](https://linux-hardware.org/?probe=74013e0688) | Feb 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [59a015c31d](https://linux-hardware.org/?probe=59a015c31d) | Feb 11, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| HP            | Compaq Presario A900        | Notebook    | [d3c4a9e1e6](https://linux-hardware.org/?probe=d3c4a9e1e6) | Feb 09, 2023 |
| Lenovo        | ThinkPad T430s 23562Z3      | Notebook    | [7338d8375a](https://linux-hardware.org/?probe=7338d8375a) | Feb 09, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [e3bd76eeaf](https://linux-hardware.org/?probe=e3bd76eeaf) | Feb 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [feeed093c0](https://linux-hardware.org/?probe=feeed093c0) | Feb 07, 2023 |
| Dell          | Latitude D430               | Notebook    | [0c1ad39f32](https://linux-hardware.org/?probe=0c1ad39f32) | Feb 06, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [cb02cfc77c](https://linux-hardware.org/?probe=cb02cfc77c) | Feb 05, 2023 |
| MSI           | MS-7309                     | Desktop     | [46995d58eb](https://linux-hardware.org/?probe=46995d58eb) | Feb 05, 2023 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [99dc5ad30d](https://linux-hardware.org/?probe=99dc5ad30d) | Feb 05, 2023 |
| ASUSTek       | P5V-VM DH                   | Desktop     | [9d090675b1](https://linux-hardware.org/?probe=9d090675b1) | Feb 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| Intel         | Unknown                     | Notebook    | [f12482330f](https://linux-hardware.org/?probe=f12482330f) | Feb 05, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | Notebook    | [a645368e82](https://linux-hardware.org/?probe=a645368e82) | Feb 04, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [163991dfae](https://linux-hardware.org/?probe=163991dfae) | Feb 03, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [7cd66ad148](https://linux-hardware.org/?probe=7cd66ad148) | Feb 03, 2023 |
| HP            | 240 G3                      | Notebook    | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [a08e60bb31](https://linux-hardware.org/?probe=a08e60bb31) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [d6829621d7](https://linux-hardware.org/?probe=d6829621d7) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | Notebook    | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Dell          | 0HFG24 A02                  | Server      | [a05562bc52](https://linux-hardware.org/?probe=a05562bc52) | Feb 02, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [894f632950](https://linux-hardware.org/?probe=894f632950) | Feb 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0d500d9d33](https://linux-hardware.org/?probe=0d500d9d33) | Jan 31, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [8641149603](https://linux-hardware.org/?probe=8641149603) | Jan 31, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ac695aa3](https://linux-hardware.org/?probe=d8ac695aa3) | Jan 31, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3fac03d01d](https://linux-hardware.org/?probe=3fac03d01d) | Jan 30, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [0f2037dcd8](https://linux-hardware.org/?probe=0f2037dcd8) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [0e28b954b4](https://linux-hardware.org/?probe=0e28b954b4) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [10421fe598](https://linux-hardware.org/?probe=10421fe598) | Jan 30, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [00a3607d18](https://linux-hardware.org/?probe=00a3607d18) | Jan 30, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| HP            | 0A08h                       | Desktop     | [f9b0168de1](https://linux-hardware.org/?probe=f9b0168de1) | Jan 28, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [c93d5da3f1](https://linux-hardware.org/?probe=c93d5da3f1) | Jan 28, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [e9d671848c](https://linux-hardware.org/?probe=e9d671848c) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [f409b1df0b](https://linux-hardware.org/?probe=f409b1df0b) | Jan 27, 2023 |
| Philco        | 14E                         | Notebook    | [1c069ed627](https://linux-hardware.org/?probe=1c069ed627) | Jan 27, 2023 |
| Philco        | 14E                         | Notebook    | [cfb283e599](https://linux-hardware.org/?probe=cfb283e599) | Jan 27, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [6aa78b855a](https://linux-hardware.org/?probe=6aa78b855a) | Jan 27, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [cf42b2f763](https://linux-hardware.org/?probe=cf42b2f763) | Jan 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [34e69693d1](https://linux-hardware.org/?probe=34e69693d1) | Jan 25, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [28effc69e6](https://linux-hardware.org/?probe=28effc69e6) | Jan 25, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [4867533043](https://linux-hardware.org/?probe=4867533043) | Jan 25, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [12d8081c29](https://linux-hardware.org/?probe=12d8081c29) | Jan 23, 2023 |
| Notebook      | W65_67SZ                    | Notebook    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7e91e49912](https://linux-hardware.org/?probe=7e91e49912) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3324fafe5a](https://linux-hardware.org/?probe=3324fafe5a) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [8d876754f3](https://linux-hardware.org/?probe=8d876754f3) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [f1f61785e5](https://linux-hardware.org/?probe=f1f61785e5) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [ec7d450cb0](https://linux-hardware.org/?probe=ec7d450cb0) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [d55b2b9507](https://linux-hardware.org/?probe=d55b2b9507) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [8716ca07da](https://linux-hardware.org/?probe=8716ca07da) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [21e1d557cc](https://linux-hardware.org/?probe=21e1d557cc) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [33c845f3a4](https://linux-hardware.org/?probe=33c845f3a4) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [24d2721a00](https://linux-hardware.org/?probe=24d2721a00) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [1e1066bd8b](https://linux-hardware.org/?probe=1e1066bd8b) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [7e636906b9](https://linux-hardware.org/?probe=7e636906b9) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [5aa076d0a5](https://linux-hardware.org/?probe=5aa076d0a5) | Jan 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b5e6a74fcb](https://linux-hardware.org/?probe=b5e6a74fcb) | Jan 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4c4a17a3cf](https://linux-hardware.org/?probe=4c4a17a3cf) | Jan 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [873bf3c874](https://linux-hardware.org/?probe=873bf3c874) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Gigabyte      | 8I945GMF                    | Desktop     | [2971006e43](https://linux-hardware.org/?probe=2971006e43) | Jan 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | Notebook    | [fb70812654](https://linux-hardware.org/?probe=fb70812654) | Jan 21, 2023 |
| ASUSTek       | N53SN                       | Notebook    | [bc8c82ca9a](https://linux-hardware.org/?probe=bc8c82ca9a) | Jan 21, 2023 |
| Dell          | Inspiron 5391               | Notebook    | [050e28c342](https://linux-hardware.org/?probe=050e28c342) | Jan 20, 2023 |
| Dell          | Venue 11 Pro 7139           | Notebook    | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [76ab21d17b](https://linux-hardware.org/?probe=76ab21d17b) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d5ad4c9486](https://linux-hardware.org/?probe=d5ad4c9486) | Jan 17, 2023 |
| Dell          | Latitude E6440              | Notebook    | [f2b34c7c46](https://linux-hardware.org/?probe=f2b34c7c46) | Jan 17, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [c32c7f2d35](https://linux-hardware.org/?probe=c32c7f2d35) | Jan 17, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [a49a3ddeaa](https://linux-hardware.org/?probe=a49a3ddeaa) | Jan 17, 2023 |
| ASUSTek       | P5K-E                       | Desktop     | [2b7ce8a40b](https://linux-hardware.org/?probe=2b7ce8a40b) | Jan 17, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [5f3e7922cd](https://linux-hardware.org/?probe=5f3e7922cd) | Jan 16, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [7d03111ac0](https://linux-hardware.org/?probe=7d03111ac0) | Jan 16, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [b4bc427969](https://linux-hardware.org/?probe=b4bc427969) | Jan 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [22c3999607](https://linux-hardware.org/?probe=22c3999607) | Jan 14, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [558f3d0d93](https://linux-hardware.org/?probe=558f3d0d93) | Jan 14, 2023 |
| ASUSTek       | A7K                         | Notebook    | [1303f158ab](https://linux-hardware.org/?probe=1303f158ab) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| HP            | 873A A01                    | Mini pc     | [5c3be4e9aa](https://linux-hardware.org/?probe=5c3be4e9aa) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f2d7914ecc](https://linux-hardware.org/?probe=f2d7914ecc) | Jan 11, 2023 |
| Sony          | VPCEB3L9E                   | Notebook    | [5a7ea474fd](https://linux-hardware.org/?probe=5a7ea474fd) | Jan 11, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Acer          | Aspire E5-771               | Notebook    | [dc397ff7f7](https://linux-hardware.org/?probe=dc397ff7f7) | Jan 09, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | Notebook    | [2f9ff5256a](https://linux-hardware.org/?probe=2f9ff5256a) | Jan 08, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | Notebook    | [b952438f2c](https://linux-hardware.org/?probe=b952438f2c) | Jan 08, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Toshiba       | NB205                       | Notebook    | [3d6ba0d0b3](https://linux-hardware.org/?probe=3d6ba0d0b3) | Jan 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b11276e9d3](https://linux-hardware.org/?probe=b11276e9d3) | Jan 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [51bbf252db](https://linux-hardware.org/?probe=51bbf252db) | Jan 06, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Dell          | Latitude 5590               | Notebook    | [f32e1efdef](https://linux-hardware.org/?probe=f32e1efdef) | Jan 05, 2023 |
| Samsung       | R530/R730                   | Notebook    | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [ef5e737fd6](https://linux-hardware.org/?probe=ef5e737fd6) | Jan 04, 2023 |
| MiPi PC       | Mini PC                     | Mini pc     | [776c827bdb](https://linux-hardware.org/?probe=776c827bdb) | Jan 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [0ac727d853](https://linux-hardware.org/?probe=0ac727d853) | Jan 03, 2023 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| HP            | 339A                        | Desktop     | [c35711cb53](https://linux-hardware.org/?probe=c35711cb53) | Jan 03, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [14aa07b144](https://linux-hardware.org/?probe=14aa07b144) | Jan 02, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [0c30f220cb](https://linux-hardware.org/?probe=0c30f220cb) | Jan 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [da1db1e278](https://linux-hardware.org/?probe=da1db1e278) | Jan 02, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| MSI           | MS-7142                     | Desktop     | [b267479470](https://linux-hardware.org/?probe=b267479470) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| MSI           | MS-7142                     | Desktop     | [ad19259a27](https://linux-hardware.org/?probe=ad19259a27) | Jan 01, 2023 |
| ASUSTek       | P5GD2-VM                    | Desktop     | [13ccd15493](https://linux-hardware.org/?probe=13ccd15493) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| TrekStor      | Primebook C11B              | Convertible | [e96819bd00](https://linux-hardware.org/?probe=e96819bd00) | Dec 31, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [f0b4df8849](https://linux-hardware.org/?probe=f0b4df8849) | Dec 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [0ee8e9bb5b](https://linux-hardware.org/?probe=0ee8e9bb5b) | Dec 28, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [23dc9112a8](https://linux-hardware.org/?probe=23dc9112a8) | Dec 27, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [2041ed5cba](https://linux-hardware.org/?probe=2041ed5cba) | Dec 27, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [01466a6701](https://linux-hardware.org/?probe=01466a6701) | Dec 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Unknown       | OA Q-ONE BRAND_V2.0         | Notebook    | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Khadas        | VIM2                        | Soc         | [2ead7fb94b](https://linux-hardware.org/?probe=2ead7fb94b) | Dec 23, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | Notebook    | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [360e473cf9](https://linux-hardware.org/?probe=360e473cf9) | Dec 22, 2022 |
| Clevo         | P170EM                      | Notebook    | [3c8b8bd784](https://linux-hardware.org/?probe=3c8b8bd784) | Dec 22, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [f78b9b1a90](https://linux-hardware.org/?probe=f78b9b1a90) | Dec 22, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| HP            | 81C9                        | Desktop     | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| ASUSTek       | 1215P                       | Notebook    | [a39ca1c22f](https://linux-hardware.org/?probe=a39ca1c22f) | Dec 21, 2022 |
| ASUSTek       | 1215P                       | Notebook    | [ed3dc80f1b](https://linux-hardware.org/?probe=ed3dc80f1b) | Dec 21, 2022 |
| Dell          | Latitude E5450              | Notebook    | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| HP            | Pavilion dv7                | Notebook    | [075b40bb9e](https://linux-hardware.org/?probe=075b40bb9e) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| HP            | 8594                        | Desktop     | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [643c90d5e1](https://linux-hardware.org/?probe=643c90d5e1) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [82687103ac](https://linux-hardware.org/?probe=82687103ac) | Dec 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [ba280c7787](https://linux-hardware.org/?probe=ba280c7787) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [7f18d05353](https://linux-hardware.org/?probe=7f18d05353) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8862992776](https://linux-hardware.org/?probe=8862992776) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Sony          | VPCS12V9E                   | Notebook    | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [6ea891850f](https://linux-hardware.org/?probe=6ea891850f) | Dec 18, 2022 |
| Lenovo        | FLEX-14IWL Laptop 81SQ      | Convertible | [f64e5ab064](https://linux-hardware.org/?probe=f64e5ab064) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | Notebook    | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [9415a97254](https://linux-hardware.org/?probe=9415a97254) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [79506873c1](https://linux-hardware.org/?probe=79506873c1) | Dec 15, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [0679db84af](https://linux-hardware.org/?probe=0679db84af) | Dec 14, 2022 |
| ECS           | CMPC                        | Notebook    | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [282ef194e5](https://linux-hardware.org/?probe=282ef194e5) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [51acd303f0](https://linux-hardware.org/?probe=51acd303f0) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [a9505fa3e4](https://linux-hardware.org/?probe=a9505fa3e4) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| HP            | 350 G1                      | Notebook    | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [d65a8640af](https://linux-hardware.org/?probe=d65a8640af) | Dec 11, 2022 |
| HP            | 1497                        | Desktop     | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Fusion5       | Lapbook T90B                | Notebook    | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [7968282240](https://linux-hardware.org/?probe=7968282240) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [01da97dae6](https://linux-hardware.org/?probe=01da97dae6) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [44895b82f9](https://linux-hardware.org/?probe=44895b82f9) | Dec 05, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| HP            | 2B34                        | Desktop     | [18ec4a2e66](https://linux-hardware.org/?probe=18ec4a2e66) | Dec 04, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f6bb91c588](https://linux-hardware.org/?probe=f6bb91c588) | Dec 03, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [db5a886817](https://linux-hardware.org/?probe=db5a886817) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [762b81c49e](https://linux-hardware.org/?probe=762b81c49e) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [01543655e9](https://linux-hardware.org/?probe=01543655e9) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | Notebook    | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | Notebook    | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| Dell          | Latitude D610               | Notebook    | [437f7630fd](https://linux-hardware.org/?probe=437f7630fd) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| Positivo      | Mobile                      | Notebook    | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | Notebook    | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7399298a0f](https://linux-hardware.org/?probe=7399298a0f) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [8eb4e40bf5](https://linux-hardware.org/?probe=8eb4e40bf5) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| Intel         | AB2L .A004                  | Mini pc     | [6124722e1f](https://linux-hardware.org/?probe=6124722e1f) | Nov 22, 2022 |
| HP            | 8540w                       | Notebook    | [3712bfe3cb](https://linux-hardware.org/?probe=3712bfe3cb) | Nov 21, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | Notebook    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEH25EN                   | Notebook    | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a5cfd24a43](https://linux-hardware.org/?probe=a5cfd24a43) | Nov 18, 2022 |
| Dell          | Latitude 5490               | Notebook    | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | Desktop     | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| ASUSTek       | K53U                        | Notebook    | [e947ac0aab](https://linux-hardware.org/?probe=e947ac0aab) | Nov 14, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [8a2f5e3f03](https://linux-hardware.org/?probe=8a2f5e3f03) | Nov 14, 2022 |
| HP            | ProBook 6450b               | Notebook    | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [c120112085](https://linux-hardware.org/?probe=c120112085) | Nov 13, 2022 |
| MSI           | MS-7309                     | Desktop     | [bd4d6c72e3](https://linux-hardware.org/?probe=bd4d6c72e3) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [a5575e0c9d](https://linux-hardware.org/?probe=a5575e0c9d) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [2e6b12e93d](https://linux-hardware.org/?probe=2e6b12e93d) | Nov 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS33U0... | Notebook    | [ce3e5599ad](https://linux-hardware.org/?probe=ce3e5599ad) | Nov 10, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [27af8e61c5](https://linux-hardware.org/?probe=27af8e61c5) | Nov 10, 2022 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [01cb4ff120](https://linux-hardware.org/?probe=01cb4ff120) | Nov 10, 2022 |
| Lenovo        | ThinkCentre M70e 0830AC4    | Desktop     | [8eb9b40274](https://linux-hardware.org/?probe=8eb9b40274) | Nov 10, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [d2dd725b2e](https://linux-hardware.org/?probe=d2dd725b2e) | Nov 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Dell          | 06FW8M A03                  | Server      | [2d4eead63b](https://linux-hardware.org/?probe=2d4eead63b) | Nov 08, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| ASUSTek       | VM40B                       | Desktop     | [5736f2e2ae](https://linux-hardware.org/?probe=5736f2e2ae) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [640298162b](https://linux-hardware.org/?probe=640298162b) | Nov 07, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [a39cc50a9a](https://linux-hardware.org/?probe=a39cc50a9a) | Nov 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | Notebook    | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| MSI           | CSM-H87M-G43                | Desktop     | [43ffdafb80](https://linux-hardware.org/?probe=43ffdafb80) | Nov 06, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [98a3c2457d](https://linux-hardware.org/?probe=98a3c2457d) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [1cf71a1b5c](https://linux-hardware.org/?probe=1cf71a1b5c) | Nov 05, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2bf5248261](https://linux-hardware.org/?probe=2bf5248261) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | Notebook    | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| HP            | 8054                        | Desktop     | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| eMachines     | EL1358G                     | Desktop     | [48d6ba4c24](https://linux-hardware.org/?probe=48d6ba4c24) | Nov 03, 2022 |
| eMachines     | EL1358G                     | Desktop     | [1acbe713b6](https://linux-hardware.org/?probe=1acbe713b6) | Nov 03, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [fa6ec2e89c](https://linux-hardware.org/?probe=fa6ec2e89c) | Nov 03, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [3eae1f74ca](https://linux-hardware.org/?probe=3eae1f74ca) | Nov 03, 2022 |
| Dell          | Precision M6400             | Notebook    | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [034414a73e](https://linux-hardware.org/?probe=034414a73e) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6f635f46c6](https://linux-hardware.org/?probe=6f635f46c6) | Nov 01, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [428b353c2c](https://linux-hardware.org/?probe=428b353c2c) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7a29190887](https://linux-hardware.org/?probe=7a29190887) | Nov 01, 2022 |
| BCM           | MX110HD                     | Desktop     | [60c3eb0c5c](https://linux-hardware.org/?probe=60c3eb0c5c) | Nov 01, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [37f3d75177](https://linux-hardware.org/?probe=37f3d75177) | Oct 31, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [3af3091881](https://linux-hardware.org/?probe=3af3091881) | Oct 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [32b9b29220](https://linux-hardware.org/?probe=32b9b29220) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [a4e0449df5](https://linux-hardware.org/?probe=a4e0449df5) | Oct 30, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ad558f1150](https://linux-hardware.org/?probe=ad558f1150) | Oct 30, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [caefae88bf](https://linux-hardware.org/?probe=caefae88bf) | Oct 30, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1c95e9ba40](https://linux-hardware.org/?probe=1c95e9ba40) | Oct 28, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | Desktop     | [5831a0d715](https://linux-hardware.org/?probe=5831a0d715) | Oct 28, 2022 |
| Lenovo        | ThinkPad W530 2438CTO       | Notebook    | [1915c9d3b0](https://linux-hardware.org/?probe=1915c9d3b0) | Oct 28, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8fad928e72](https://linux-hardware.org/?probe=8fad928e72) | Oct 28, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [fef5f08978](https://linux-hardware.org/?probe=fef5f08978) | Oct 27, 2022 |
| Dell          | Latitude E6510              | Notebook    | [2cb824b444](https://linux-hardware.org/?probe=2cb824b444) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [275bc51aaf](https://linux-hardware.org/?probe=275bc51aaf) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ddb0a31443](https://linux-hardware.org/?probe=ddb0a31443) | Oct 26, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [46d64e9947](https://linux-hardware.org/?probe=46d64e9947) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [4ef2a348fc](https://linux-hardware.org/?probe=4ef2a348fc) | Oct 25, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [dbc717a299](https://linux-hardware.org/?probe=dbc717a299) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | Desktop     | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [23a298a9a5](https://linux-hardware.org/?probe=23a298a9a5) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [3e39042f59](https://linux-hardware.org/?probe=3e39042f59) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [b7412d4350](https://linux-hardware.org/?probe=b7412d4350) | Oct 23, 2022 |
| HP            | 15                          | Notebook    | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [d575515de3](https://linux-hardware.org/?probe=d575515de3) | Oct 20, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [4de39d4a1c](https://linux-hardware.org/?probe=4de39d4a1c) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | Desktop     | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| Dell          | 500                         | Notebook    | [91b78b800a](https://linux-hardware.org/?probe=91b78b800a) | Oct 17, 2022 |
| Dell          | Latitude E5270              | Notebook    | [6f07cdee36](https://linux-hardware.org/?probe=6f07cdee36) | Oct 17, 2022 |
| MSI           | MS-7309                     | Desktop     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| Samsung       | NC10                        | Notebook    | [1ea93f5095](https://linux-hardware.org/?probe=1ea93f5095) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | Desktop     | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [d00f5feebf](https://linux-hardware.org/?probe=d00f5feebf) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Dell          | 0N36HY A09                  | Server      | [464fda30a8](https://linux-hardware.org/?probe=464fda30a8) | Oct 14, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | Notebook    | [a698e6de4d](https://linux-hardware.org/?probe=a698e6de4d) | Oct 13, 2022 |
| eMachines     | eME528                      | Notebook    | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [16f5eb4d25](https://linux-hardware.org/?probe=16f5eb4d25) | Oct 12, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6580d55237](https://linux-hardware.org/?probe=6580d55237) | Oct 09, 2022 |
| HP            | 255 G1                      | Notebook    | [fc9f63bfb6](https://linux-hardware.org/?probe=fc9f63bfb6) | Oct 08, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [05e82f0dd5](https://linux-hardware.org/?probe=05e82f0dd5) | Oct 08, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [9a380f66ea](https://linux-hardware.org/?probe=9a380f66ea) | Oct 08, 2022 |
| HP            | 1589                        | Desktop     | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | Notebook    | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | Notebook    | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| Acer          | EQ35M                       | Desktop     | [6a765c4673](https://linux-hardware.org/?probe=6a765c4673) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [4ad6d2e719](https://linux-hardware.org/?probe=4ad6d2e719) | Oct 05, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Xubuntu 20.04        | 1983      | 45.91%  |
| Xubuntu 18.04        | 1042      | 24.13%  |
| Xubuntu 22.04        | 562       | 13.01%  |
| Xubuntu 19.10        | 199       | 4.61%   |
| Xubuntu 16.04        | 97        | 2.25%   |
| Xubuntu 21.10        | 96        | 2.22%   |
| Xubuntu 20.10        | 93        | 2.15%   |
| Xubuntu 21.04        | 81        | 1.88%   |
| Xubuntu 22.10        | 56        | 1.3%    |
| Xubuntu 23.04        | 54        | 1.25%   |
| Xubuntu 19.04        | 26        | 0.6%    |
| Xubuntu 18.10        | 11        | 0.25%   |
| Xubuntu 17.10        | 6         | 0.14%   |
| Xubuntu              | 6         | 0.14%   |
| Xubuntu 14.04        | 3         | 0.07%   |
| Xubuntu 17.04        | 2         | 0.05%   |
| Xubuntu 23.10        | 1         | 0.02%   |
| Xubuntu 2023.1-beta5 | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Xubuntu | 4160      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 156       | 3.16%   |
| 5.4.0-48-generic    | 65        | 1.31%   |
| 5.4.0-58-generic    | 60        | 1.21%   |
| 5.4.0-52-generic    | 59        | 1.19%   |
| 5.3.0-46-generic    | 59        | 1.19%   |
| 5.15.0-56-generic   | 51        | 1.03%   |
| 5.11.0-27-generic   | 50        | 1.01%   |
| 5.4.0-65-generic    | 48        | 0.97%   |
| 5.3.0-40-generic    | 48        | 0.97%   |
| 5.4.0-29-generic    | 46        | 0.93%   |
| 5.4.0-54-generic    | 45        | 0.91%   |
| 5.15.0-52-generic   | 44        | 0.89%   |
| 5.4.0-47-generic    | 42        | 0.85%   |
| 5.4.0-42-lowlatency | 40        | 0.81%   |
| 5.4.0-26-generic    | 38        | 0.77%   |
| 5.3.0-42-generic    | 38        | 0.77%   |
| 5.3.0-28-generic    | 36        | 0.73%   |
| 5.4.0-40-generic    | 35        | 0.71%   |
| 5.0.0-37-generic    | 35        | 0.71%   |
| 5.3.0-51-generic    | 34        | 0.69%   |
| 5.4.0-37-generic    | 33        | 0.67%   |
| 5.4.0-66-generic    | 31        | 0.63%   |
| 5.15.0-47-generic   | 31        | 0.63%   |
| 4.15.0-99-generic   | 31        | 0.63%   |
| 5.4.0-89-generic    | 30        | 0.61%   |
| 5.4.0-31-generic    | 30        | 0.61%   |
| 5.15.0-58-generic   | 30        | 0.61%   |
| 5.15.0-48-generic   | 30        | 0.61%   |
| 5.15.0-46-generic   | 29        | 0.59%   |
| 5.4.0-72-generic    | 28        | 0.57%   |
| 5.3.0-53-generic    | 28        | 0.57%   |
| 5.4.0-29-lowlatency | 27        | 0.55%   |
| 6.2.0-26-generic    | 26        | 0.53%   |
| 5.4.0-91-generic    | 26        | 0.53%   |
| 5.4.0-81-generic    | 26        | 0.53%   |
| 5.13.0-39-generic   | 26        | 0.53%   |
| 5.8.0-53-generic    | 25        | 0.51%   |
| 5.4.0-33-generic    | 25        | 0.51%   |
| 5.15.0-60-generic   | 25        | 0.51%   |
| 5.13.0-30-generic   | 25        | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1613      | 36.63%  |
| 5.15.0  | 489       | 11.1%   |
| 4.15.0  | 484       | 10.99%  |
| 5.3.0   | 438       | 9.95%   |
| 5.11.0  | 276       | 6.27%   |
| 5.8.0   | 255       | 5.79%   |
| 5.13.0  | 224       | 5.09%   |
| 5.19.0  | 140       | 3.18%   |
| 5.0.0   | 107       | 2.43%   |
| 6.2.0   | 76        | 1.73%   |
| 4.4.0   | 47        | 1.07%   |
| 4.18.0  | 26        | 0.59%   |
| 5.17.0  | 12        | 0.27%   |
| 4.13.0  | 9         | 0.2%    |
| 6.1.0   | 6         | 0.14%   |
| 4.10.0  | 6         | 0.14%   |
| 5.6.0   | 5         | 0.11%   |
| 5.14.0  | 5         | 0.11%   |
| 5.10.0  | 5         | 0.11%   |
| 6.0.0   | 4         | 0.09%   |
| 5.18.0  | 4         | 0.09%   |
| 6.1.30  | 3         | 0.07%   |
| 5.9.8   | 3         | 0.07%   |
| 5.9.16  | 3         | 0.07%   |
| 5.9.0   | 3         | 0.07%   |
| 5.4.217 | 3         | 0.07%   |
| 5.15.1  | 3         | 0.07%   |
| 5.11.16 | 3         | 0.07%   |
| 4.8.0   | 3         | 0.07%   |
| 6.2.7   | 2         | 0.05%   |
| 6.2.2   | 2         | 0.05%   |
| 6.0.9   | 2         | 0.05%   |
| 5.7.7   | 2         | 0.05%   |
| 5.7.6   | 2         | 0.05%   |
| 5.7.1   | 2         | 0.05%   |
| 5.7.0   | 2         | 0.05%   |
| 5.6.19  | 2         | 0.05%   |
| 5.5.19  | 2         | 0.05%   |
| 5.16.9  | 2         | 0.05%   |
| 5.16.0  | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1623      | 36.89%  |
| 5.15    | 504       | 11.46%  |
| 4.15    | 484       | 11%     |
| 5.3     | 440       | 10%     |
| 5.11    | 283       | 6.43%   |
| 5.8     | 260       | 5.91%   |
| 5.13    | 228       | 5.18%   |
| 5.19    | 143       | 3.25%   |
| 5.0     | 109       | 2.48%   |
| 6.2     | 82        | 1.86%   |
| 4.4     | 52        | 1.18%   |
| 4.18    | 26        | 0.59%   |
| 5.10    | 16        | 0.36%   |
| 6.1     | 13        | 0.3%    |
| 5.17    | 13        | 0.3%    |
| 5.9     | 12        | 0.27%   |
| 5.7     | 10        | 0.23%   |
| 5.6     | 10        | 0.23%   |
| 5.14    | 10        | 0.23%   |
| 4.13    | 9         | 0.2%    |
| 5.12    | 8         | 0.18%   |
| 6.0     | 7         | 0.16%   |
| 4.19    | 7         | 0.16%   |
| 5.18    | 6         | 0.14%   |
| 4.9     | 6         | 0.14%   |
| 4.10    | 6         | 0.14%   |
| 6.4     | 5         | 0.11%   |
| 6.3     | 5         | 0.11%   |
| 5.16    | 5         | 0.11%   |
| 5.5     | 3         | 0.07%   |
| 4.8     | 3         | 0.07%   |
| 5.2     | 2         | 0.05%   |
| 4.14    | 2         | 0.05%   |
| 4.11    | 2         | 0.05%   |
| 6.5     | 1         | 0.02%   |
| 4.20    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 3.13    | 1         | 0.02%   |
| 3.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3606      | 86.54%  |
| i686    | 509       | 12.22%  |
| aarch64 | 40        | 0.96%   |
| armv7l  | 12        | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 4012      | 96.26%  |
| GNOME           | 108       | 2.59%   |
| KDE5            | 10        | 0.24%   |
| i3              | 9         | 0.22%   |
| Cinnamon        | 8         | 0.19%   |
| Unity           | 4         | 0.1%    |
| GNOME Flashback | 4         | 0.1%    |
| X-Cinnamon      | 3         | 0.07%   |
| MATE            | 2         | 0.05%   |
| LXQt            | 2         | 0.05%   |
| GNUstep         | 2         | 0.05%   |
| xmonad          | 1         | 0.02%   |
| ICEWM           | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |
| Unknown         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4083      | 97.98%  |
| Tty     | 59        | 1.42%   |
| Wayland | 20        | 0.48%   |
| Web     | 3         | 0.07%   |
| Unknown | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2118      | 49.27%  |
| LightDM | 1539      | 35.8%   |
| TDM     | 508       | 11.82%  |
| GDM3    | 62        | 1.44%   |
| GDM     | 48        | 1.12%   |
| SDDM    | 16        | 0.37%   |
| XDM     | 4         | 0.09%   |
| SLiM    | 2         | 0.05%   |
| NODM    | 1         | 0.02%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1367      | 32.69%  |
| de_DE   | 430       | 10.28%  |
| fr_FR   | 370       | 8.85%   |
| it_IT   | 275       | 6.58%   |
| ru_RU   | 212       | 5.07%   |
| pt_BR   | 209       | 5%      |
| en_GB   | 157       | 3.75%   |
| C       | 138       | 3.3%    |
| es_ES   | 110       | 2.63%   |
| en_CA   | 100       | 2.39%   |
| Unknown | 82        | 1.96%   |
| en_AU   | 74        | 1.77%   |
| pl_PL   | 64        | 1.53%   |
| es_AR   | 42        | 1%      |
| nl_NL   | 38        | 0.91%   |
| hu_HU   | 38        | 0.91%   |
| ja_JP   | 37        | 0.88%   |
| cs_CZ   | 34        | 0.81%   |
| en_IN   | 26        | 0.62%   |
| es_MX   | 24        | 0.57%   |
| fr_BE   | 18        | 0.43%   |
| pt_PT   | 17        | 0.41%   |
| fi_FI   | 17        | 0.41%   |
| ru_UA   | 16        | 0.38%   |
| sv_SE   | 15        | 0.36%   |
| en_ZA   | 15        | 0.36%   |
| tr_TR   | 14        | 0.33%   |
| sk_SK   | 14        | 0.33%   |
| es_CO   | 14        | 0.33%   |
| de_CH   | 14        | 0.33%   |
| de_AT   | 14        | 0.33%   |
| el_GR   | 13        | 0.31%   |
| zh_TW   | 12        | 0.29%   |
| fr_CA   | 11        | 0.26%   |
| es_VE   | 11        | 0.26%   |
| zh_CN   | 10        | 0.24%   |
| nl_BE   | 10        | 0.24%   |
| en_NZ   | 7         | 0.17%   |
| en_IL   | 7         | 0.17%   |
| ca_ES   | 7         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2730      | 64.83%  |
| EFI  | 1481      | 35.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3788      | 90.21%  |
| Overlay | 156       | 3.72%   |
| Tmpfs   | 81        | 1.93%   |
| Btrfs   | 73        | 1.74%   |
| Zfs     | 40        | 0.95%   |
| Unknown | 24        | 0.57%   |
| Xfs     | 17        | 0.4%    |
| Ext2    | 11        | 0.26%   |
| Ext3    | 7         | 0.17%   |
| Ufs     | 1         | 0.02%   |
| Aufs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2514      | 59.47%  |
| GPT     | 1133      | 26.8%   |
| MBR     | 580       | 13.72%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3554      | 83.62%  |
| Yes       | 696       | 16.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2821      | 66.61%  |
| Yes       | 1414      | 33.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 637       | 15.31%  |
| ASUSTek Computer        | 620       | 14.9%   |
| Dell                    | 501       | 12.04%  |
| Lenovo                  | 491       | 11.8%   |
| Acer                    | 276       | 6.63%   |
| Gigabyte Technology     | 243       | 5.84%   |
| MSI                     | 198       | 4.76%   |
| ASRock                  | 156       | 3.75%   |
| Toshiba                 | 101       | 2.43%   |
| Apple                   | 76        | 1.83%   |
| Intel                   | 69        | 1.66%   |
| Samsung Electronics     | 62        | 1.49%   |
| Sony                    | 51        | 1.23%   |
| Unknown                 | 49        | 1.18%   |
| Medion                  | 46        | 1.11%   |
| Fujitsu Siemens         | 33        | 0.79%   |
| Fujitsu                 | 33        | 0.79%   |
| ECS                     | 29        | 0.7%    |
| Packard Bell            | 28        | 0.67%   |
| Google                  | 25        | 0.6%    |
| Foxconn                 | 23        | 0.55%   |
| Pegatron                | 18        | 0.43%   |
| Notebook                | 17        | 0.41%   |
| Positivo                | 16        | 0.38%   |
| Raspberry Pi Foundation | 15        | 0.36%   |
| Clevo                   | 15        | 0.36%   |
| eMachines               | 14        | 0.34%   |
| IBM                     | 12        | 0.29%   |
| Supermicro              | 11        | 0.26%   |
| HUAWEI                  | 11        | 0.26%   |
| Gateway                 | 11        | 0.26%   |
| Biostar                 | 10        | 0.24%   |
| AMI                     | 10        | 0.24%   |
| GPU Company             | 9         | 0.22%   |
| ZOTAC                   | 8         | 0.19%   |
| LG Electronics          | 8         | 0.19%   |
| Alienware               | 7         | 0.17%   |
| TUXEDO                  | 6         | 0.14%   |
| Semp Toshiba            | 6         | 0.14%   |
| OEM                     | 6         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 73        | 1.75%   |
| ASUS All Series                        | 36        | 0.87%   |
| HP Pavilion dv6                        | 18        | 0.43%   |
| HP Notebook                            | 17        | 0.41%   |
| Gigabyte H410M S2H                     | 15        | 0.36%   |
| Dell OptiPlex 7010                     | 15        | 0.36%   |
| Dell OptiPlex 755                      | 11        | 0.26%   |
| Dell Latitude D630                     | 11        | 0.26%   |
| HP Pavilion 15                         | 10        | 0.24%   |
| HP 15                                  | 10        | 0.24%   |
| Gigabyte H81M-S2V                      | 9         | 0.22%   |
| ECS G31T-M9                            | 9         | 0.22%   |
| Dell Latitude E6430                    | 9         | 0.22%   |
| ASRock N68C-S UCC                      | 9         | 0.22%   |
| Dell OptiPlex 780                      | 8         | 0.19%   |
| Dell OptiPlex 760                      | 8         | 0.19%   |
| Dell OptiPlex 390                      | 8         | 0.19%   |
| MSI MS-7721                            | 7         | 0.17%   |
| HP Pavilion g6                         | 7         | 0.17%   |
| HP Pavilion dv7                        | 7         | 0.17%   |
| HP Pavilion dv6500                     | 7         | 0.17%   |
| Dell OptiPlex 3020                     | 7         | 0.17%   |
| ASUS TUF Gaming X570-PLUS              | 7         | 0.17%   |
| MSI MS-7C37                            | 6         | 0.14%   |
| MSI MS-7817                            | 6         | 0.14%   |
| HP EliteDesk 800 G1 SFF                | 6         | 0.14%   |
| Dell OptiPlex 9020                     | 6         | 0.14%   |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.14%   |
| MSI MS-7C02                            | 5         | 0.12%   |
| MSI MS-7B89                            | 5         | 0.12%   |
| MSI MS-7B79                            | 5         | 0.12%   |
| MSI MS-7A38                            | 5         | 0.12%   |
| Intel H61                              | 5         | 0.12%   |
| HP Pavilion 17                         | 5         | 0.12%   |
| HP EliteBook 840 G3                    | 5         | 0.12%   |
| HP Compaq Pro 6300 SFF                 | 5         | 0.12%   |
| HP Compaq Elite 8300 SFF               | 5         | 0.12%   |
| HP Compaq dc7600 Small Form Factor     | 5         | 0.12%   |
| Gigabyte 945GZM-S2                     | 5         | 0.12%   |
| Dell OptiPlex GX620                    | 5         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 246       | 5.91%   |
| Acer Aspire           | 173       | 4.16%   |
| Dell Inspiron         | 132       | 3.17%   |
| Dell Latitude         | 127       | 3.05%   |
| HP Pavilion           | 117       | 2.81%   |
| HP Compaq             | 113       | 2.72%   |
| Dell OptiPlex         | 105       | 2.52%   |
| Toshiba Satellite     | 85        | 2.04%   |
| Lenovo IdeaPad        | 74        | 1.78%   |
| Unknown               | 73        | 1.75%   |
| HP EliteBook          | 60        | 1.44%   |
| ASUS PRIME            | 53        | 1.27%   |
| HP ProBook            | 46        | 1.11%   |
| HP Laptop             | 43        | 1.03%   |
| Lenovo ThinkCentre    | 42        | 1.01%   |
| Dell Precision        | 38        | 0.91%   |
| ASUS VivoBook         | 38        | 0.91%   |
| ASUS All              | 36        | 0.87%   |
| Dell XPS              | 23        | 0.55%   |
| Dell Vostro           | 22        | 0.53%   |
| ASUS TUF              | 22        | 0.53%   |
| HP ProDesk            | 19        | 0.46%   |
| Acer Extensa          | 19        | 0.46%   |
| HP Notebook           | 18        | 0.43%   |
| ASUS ROG              | 18        | 0.43%   |
| Acer Veriton          | 18        | 0.43%   |
| Gigabyte H410M        | 16        | 0.38%   |
| RPi Raspberry         | 15        | 0.36%   |
| Fujitsu Siemens AMILO | 15        | 0.36%   |
| Dell PowerEdge        | 15        | 0.36%   |
| Packard Bell EasyNote | 14        | 0.34%   |
| HP ENVY               | 14        | 0.34%   |
| HP EliteDesk          | 14        | 0.34%   |
| Fujitsu LIFEBOOK      | 14        | 0.34%   |
| HP Presario           | 12        | 0.29%   |
| Fujitsu ESPRIMO       | 12        | 0.29%   |
| Dell Studio           | 12        | 0.29%   |
| Lenovo IdeaCentre     | 11        | 0.26%   |
| HP Mini               | 11        | 0.26%   |
| HP 255                | 11        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 345       | 8.29%   |
| 2011    | 345       | 8.29%   |
| 2010    | 309       | 7.43%   |
| 2013    | 304       | 7.31%   |
| 2008    | 298       | 7.16%   |
| 2009    | 284       | 6.83%   |
| 2007    | 269       | 6.47%   |
| 2019    | 244       | 5.87%   |
| 2014    | 244       | 5.87%   |
| 2018    | 232       | 5.58%   |
| 2020    | 220       | 5.29%   |
| 2017    | 211       | 5.07%   |
| 2015    | 170       | 4.09%   |
| 2016    | 162       | 3.89%   |
| 2021    | 153       | 3.68%   |
| 2006    | 146       | 3.51%   |
| 2005    | 71        | 1.71%   |
| 2022    | 56        | 1.35%   |
| Unknown | 48        | 1.15%   |
| 2004    | 16        | 0.38%   |
| 2003    | 16        | 0.38%   |
| 2023    | 9         | 0.22%   |
| 2002    | 4         | 0.1%    |
| 2001    | 4         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2258      | 54.28%  |
| Desktop        | 1651      | 39.69%  |
| Mini pc        | 59        | 1.42%   |
| System on chip | 49        | 1.18%   |
| All in one     | 46        | 1.11%   |
| Convertible    | 43        | 1.03%   |
| Server         | 35        | 0.84%   |
| Tablet         | 17        | 0.41%   |
| Other          | 1         | 0.02%   |
| Firewall       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3951      | 94.5%   |
| Enabled  | 230       | 5.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4133      | 99.35%  |
| Yes  | 27        | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1126      | 26.66%  |
| 4.01-8.0        | 805       | 19.06%  |
| 8.01-16.0       | 567       | 13.43%  |
| 16.01-24.0      | 545       | 12.91%  |
| 1.01-2.0        | 476       | 11.27%  |
| 32.01-64.0      | 231       | 5.47%   |
| 2.01-3.0        | 156       | 3.69%   |
| 0.51-1.0        | 155       | 3.67%   |
| 64.01-256.0     | 95        | 2.25%   |
| 24.01-32.0      | 52        | 1.23%   |
| 0.01-0.5        | 12        | 0.28%   |
| More than 256.0 | 3         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1900      | 41.23%  |
| 0.51-1.0   | 891       | 19.34%  |
| 2.01-3.0   | 848       | 18.4%   |
| 4.01-8.0   | 384       | 8.33%   |
| 3.01-4.0   | 323       | 7.01%   |
| 0.01-0.5   | 124       | 2.69%   |
| 8.01-16.0  | 108       | 2.34%   |
| 16.01-24.0 | 18        | 0.39%   |
| 24.01-32.0 | 8         | 0.17%   |
| 32.01-64.0 | 2         | 0.04%   |
| Unknown    | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2666      | 62.3%   |
| 2      | 1016      | 23.74%  |
| 3      | 320       | 7.48%   |
| 4      | 122       | 2.85%   |
| 5      | 58        | 1.36%   |
| 0      | 48        | 1.12%   |
| 6      | 23        | 0.54%   |
| 7      | 15        | 0.35%   |
| 10     | 4         | 0.09%   |
| 9      | 3         | 0.07%   |
| 8      | 3         | 0.07%   |
| 11     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2134      | 50.94%  |
| No        | 2055      | 49.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3758      | 90.25%  |
| No        | 406       | 9.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3009      | 71.81%  |
| No        | 1181      | 28.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2347      | 55.71%  |
| Yes       | 1866      | 44.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 657       | 15.71%  |
| Germany      | 521       | 12.46%  |
| France       | 392       | 9.37%   |
| Italy        | 309       | 7.39%   |
| Russia       | 268       | 6.41%   |
| Brazil       | 242       | 5.79%   |
| Canada       | 158       | 3.78%   |
| UK           | 154       | 3.68%   |
| Spain        | 132       | 3.16%   |
| Netherlands  | 99        | 2.37%   |
| Australia    | 86        | 2.06%   |
| Poland       | 80        | 1.91%   |
| Argentina    | 58        | 1.39%   |
| Ukraine      | 55        | 1.31%   |
| Belgium      | 53        | 1.27%   |
| Mexico       | 47        | 1.12%   |
| Czechia      | 47        | 1.12%   |
| Sweden       | 44        | 1.05%   |
| Japan        | 44        | 1.05%   |
| Hungary      | 44        | 1.05%   |
| Finland      | 40        | 0.96%   |
| India        | 36        | 0.86%   |
| Portugal     | 35        | 0.84%   |
| Greece       | 34        | 0.81%   |
| Austria      | 30        | 0.72%   |
| Indonesia    | 27        | 0.65%   |
| Bulgaria     | 27        | 0.65%   |
| Switzerland  | 24        | 0.57%   |
| Turkey       | 23        | 0.55%   |
| Romania      | 23        | 0.55%   |
| Slovakia     | 19        | 0.45%   |
| Iran         | 18        | 0.43%   |
| Colombia     | 18        | 0.43%   |
| Norway       | 17        | 0.41%   |
| Taiwan       | 15        | 0.36%   |
| South Africa | 15        | 0.36%   |
| Venezuela    | 14        | 0.33%   |
| Denmark      | 14        | 0.33%   |
| Israel       | 13        | 0.31%   |
| China        | 12        | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 54        | 1.22%   |
| Berlin            | 48        | 1.09%   |
| Voronezh          | 46        | 1.04%   |
| Moscow            | 45        | 1.02%   |
| Rome              | 37        | 0.84%   |
| Milan             | 37        | 0.84%   |
| Sydney            | 28        | 0.63%   |
| Sao Paulo         | 26        | 0.59%   |
| Warsaw            | 25        | 0.57%   |
| Amsterdam         | 25        | 0.57%   |
| Munich            | 24        | 0.54%   |
| Athens            | 24        | 0.54%   |
| Madrid            | 23        | 0.52%   |
| St Petersburg     | 22        | 0.5%    |
| Hamburg           | 22        | 0.5%    |
| Budapest          | 20        | 0.45%   |
| Rio de Janeiro    | 19        | 0.43%   |
| Québec           | 19        | 0.43%   |
| Helsinki          | 18        | 0.41%   |
| Melbourne         | 17        | 0.38%   |
| Barcelona         | 17        | 0.38%   |
| Genoa             | 16        | 0.36%   |
| Oryol             | 15        | 0.34%   |
| Montreal          | 15        | 0.34%   |
| Kyiv              | 15        | 0.34%   |
| Buenos Aires      | 15        | 0.34%   |
| Turin             | 14        | 0.32%   |
| Toronto           | 14        | 0.32%   |
| Prague            | 14        | 0.32%   |
| Vancouver         | 13        | 0.29%   |
| Tehran            | 13        | 0.29%   |
| Stuttgart         | 13        | 0.29%   |
| Sofia             | 13        | 0.29%   |
| Frankfurt am Main | 13        | 0.29%   |
| Vienna            | 12        | 0.27%   |
| Leipzig           | 12        | 0.27%   |
| Seattle           | 11        | 0.25%   |
| Cologne           | 11        | 0.25%   |
| Chicago           | 11        | 0.25%   |
| Belo Horizonte    | 11        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1028      | 1506   | 17.88%  |
| WDC                         | 971       | 1425   | 16.89%  |
| Samsung Electronics         | 777       | 1097   | 13.51%  |
| Toshiba                     | 389       | 490    | 6.77%   |
| Hitachi                     | 330       | 437    | 5.74%   |
| Unknown                     | 295       | 381    | 5.13%   |
| Kingston                    | 262       | 334    | 4.56%   |
| SanDisk                     | 207       | 263    | 3.6%    |
| Crucial                     | 159       | 210    | 2.77%   |
| HGST                        | 112       | 136    | 1.95%   |
| Intel                       | 108       | 153    | 1.88%   |
| SK hynix                    | 89        | 107    | 1.55%   |
| A-DATA Technology           | 77        | 100    | 1.34%   |
| Fujitsu                     | 71        | 88     | 1.23%   |
| China                       | 63        | 73     | 1.1%    |
| Maxtor                      | 61        | 86     | 1.06%   |
| Micron Technology           | 47        | 54     | 0.82%   |
| PNY                         | 39        | 52     | 0.68%   |
| Patriot                     | 32        | 37     | 0.56%   |
| OCZ                         | 28        | 36     | 0.49%   |
| Intenso                     | 28        | 35     | 0.49%   |
| Transcend                   | 27        | 30     | 0.47%   |
| Phison                      | 27        | 47     | 0.47%   |
| SPCC                        | 24        | 36     | 0.42%   |
| KIOXIA                      | 23        | 29     | 0.4%    |
| Apple                       | 20        | 28     | 0.35%   |
| Unknown                     | 19        | 20     | 0.33%   |
| LITEON                      | 17        | 19     | 0.3%    |
| LITEONIT                    | 16        | 19     | 0.28%   |
| Apacer                      | 16        | 22     | 0.28%   |
| Silicon Motion              | 15        | 16     | 0.26%   |
| ASMT                        | 15        | 24     | 0.26%   |
| JMicron Technology          | 14        | 14     | 0.24%   |
| KingDian                    | 13        | 19     | 0.23%   |
| Hewlett-Packard             | 12        | 21     | 0.21%   |
| Lexar                       | 10        | 10     | 0.17%   |
| KingSpec                    | 9         | 11     | 0.16%   |
| Kingston Technology Company | 8         | 11     | 0.14%   |
| XPG                         | 7         | 13     | 0.12%   |
| USB3.0                      | 7         | 10     | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 69        | 1.1%    |
| Unknown MMC Card  32GB              | 57        | 0.91%   |
| Seagate ST500DM002-1BD142 500GB     | 54        | 0.86%   |
| Samsung SSD 860 EVO 500GB           | 47        | 0.75%   |
| Kingston SA400S37480G 480GB SSD     | 41        | 0.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 35        | 0.56%   |
| Samsung SSD 850 EVO 250GB           | 35        | 0.56%   |
| Unknown MMC Card  64GB              | 34        | 0.54%   |
| Seagate ST500LT012-1DG142 500GB     | 32        | 0.51%   |
| Seagate ST1000DM010-2EP102 1TB      | 32        | 0.51%   |
| Samsung SSD 850 EVO 500GB           | 31        | 0.49%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 30        | 0.48%   |
| Unknown SD/MMC/MS PRO 1GB           | 28        | 0.45%   |
| Toshiba MQ01ABF050 500GB            | 27        | 0.43%   |
| Toshiba MQ01ABD100 1TB              | 27        | 0.43%   |
| Seagate Expansion 2TB               | 27        | 0.43%   |
| Kingston SA400S37120G 120GB SSD     | 26        | 0.41%   |
| Seagate ST3500418AS 500GB           | 25        | 0.4%    |
| Seagate ST1000LM035-1RK172 1TB      | 25        | 0.4%    |
| Toshiba DT01ACA100 1TB              | 24        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD    | 23        | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB      | 22        | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB      | 22        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB      | 22        | 0.35%   |
| Unknown MMC Card  128GB             | 21        | 0.33%   |
| HGST HTS721010A9E630 1TB            | 21        | 0.33%   |
| HGST HTS541010A9E680 1TB            | 21        | 0.33%   |
| Unknown MMC Card  16GB              | 20        | 0.32%   |
| Seagate ST9500325AS 500GB           | 20        | 0.32%   |
| Seagate ST2000DM001-1CH164 2TB      | 20        | 0.32%   |
| Seagate ST9320325AS 320GB           | 19        | 0.3%    |
| Seagate ST31000528AS 1TB            | 19        | 0.3%    |
| Samsung SSD 860 EVO 250GB           | 19        | 0.3%    |
| Samsung SSD 860 EVO 1TB             | 19        | 0.3%    |
| Crucial CT500MX500SSD1 500GB        | 19        | 0.3%    |
| Unknown                             | 19        | 0.3%    |
| Seagate ST4000DM004-2CV104 4TB      | 18        | 0.29%   |
| Crucial CT240BX500SSD1 240GB        | 18        | 0.29%   |
| Seagate ST500LT012-9WS142 500GB     | 17        | 0.27%   |
| Hitachi HDS721010CLA332 1TB         | 17        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1010      | 1472   | 33.08%  |
| WDC                 | 849       | 1248   | 27.81%  |
| Toshiba             | 331       | 422    | 10.84%  |
| Hitachi             | 330       | 437    | 10.81%  |
| Samsung Electronics | 193       | 270    | 6.32%   |
| HGST                | 112       | 136    | 3.67%   |
| Fujitsu             | 69        | 86     | 2.26%   |
| Maxtor              | 59        | 84     | 1.93%   |
| Unknown             | 29        | 34     | 0.95%   |
| USB3.0              | 7         | 10     | 0.23%   |
| IBM/Hitachi         | 7         | 7      | 0.23%   |
| ASMT                | 7         | 13     | 0.23%   |
| Intenso             | 5         | 6      | 0.16%   |
| SSK                 | 4         | 4      | 0.13%   |
| SABRENT             | 4         | 4      | 0.13%   |
| Hewlett-Packard     | 4         | 9      | 0.13%   |
| Pioneer             | 3         | 3      | 0.1%    |
| PHD 3.0             | 3         | 3      | 0.1%    |
| External            | 3         | 3      | 0.1%    |
| Apple               | 3         | 4      | 0.1%    |
| WD MediaMax         | 2         | 2      | 0.07%   |
| Inateck             | 2         | 2      | 0.07%   |
| HPE                 | 2         | 5      | 0.07%   |
| HGST HTS            | 2         | 2      | 0.07%   |
| ExcelStor           | 2         | 2      | 0.07%   |
| ASMedia             | 2         | 2      | 0.07%   |
| Apricorn            | 2         | 3      | 0.07%   |
| SAGE                | 1         | 1      | 0.03%   |
| LaCie               | 1         | 5      | 0.03%   |
| ICY BOX             | 1         | 2      | 0.03%   |
| Ext Hard            | 1         | 1      | 0.03%   |
| CLOVER              | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 401       | 548    | 23.22%  |
| Kingston            | 233       | 294    | 13.49%  |
| SanDisk             | 156       | 206    | 9.03%   |
| Crucial             | 145       | 196    | 8.4%    |
| WDC                 | 83        | 106    | 4.81%   |
| A-DATA Technology   | 65        | 87     | 3.76%   |
| China               | 63        | 73     | 3.65%   |
| Intel               | 54        | 78     | 3.13%   |
| PNY                 | 38        | 50     | 2.2%    |
| Patriot             | 32        | 37     | 1.85%   |
| Toshiba             | 30        | 37     | 1.74%   |
| Micron Technology   | 30        | 34     | 1.74%   |
| OCZ                 | 27        | 34     | 1.56%   |
| Transcend           | 25        | 26     | 1.45%   |
| SPCC                | 24        | 36     | 1.39%   |
| SK hynix            | 24        | 25     | 1.39%   |
| Intenso             | 21        | 23     | 1.22%   |
| LITEON              | 17        | 19     | 0.98%   |
| LITEONIT            | 16        | 19     | 0.93%   |
| Apacer              | 15        | 21     | 0.87%   |
| KingDian            | 13        | 19     | 0.75%   |
| Apple               | 10        | 14     | 0.58%   |
| Lexar               | 9         | 9      | 0.52%   |
| Unknown             | 8         | 9      | 0.46%   |
| KingSpec            | 8         | 10     | 0.46%   |
| ASMT                | 8         | 11     | 0.46%   |
| Smartbuy            | 7         | 7      | 0.41%   |
| Plextor             | 7         | 13     | 0.41%   |
| JMicron Technology  | 7         | 7      | 0.41%   |
| GOODRAM             | 7         | 9      | 0.41%   |
| TO Exter            | 6         | 8      | 0.35%   |
| Team                | 6         | 13     | 0.35%   |
| Netac               | 6         | 10     | 0.35%   |
| Hewlett-Packard     | 6         | 9      | 0.35%   |
| Dogfish             | 6         | 9      | 0.35%   |
| Corsair             | 6         | 7      | 0.35%   |
| Mushkin             | 5         | 5      | 0.29%   |
| FORESEE             | 5         | 9      | 0.29%   |
| Seagate             | 4         | 7      | 0.23%   |
| Gigabyte Technology | 4         | 6      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2573      | 4285   | 50.2%   |
| SSD     | 1551      | 2242   | 30.26%  |
| NVMe    | 647       | 858    | 12.62%  |
| MMC     | 273       | 357    | 5.33%   |
| Unknown | 82        | 103    | 1.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3517      | 6298   | 75.15%  |
| NVMe | 646       | 856    | 13.8%   |
| MMC  | 273       | 357    | 5.83%   |
| SAS  | 244       | 334    | 5.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 2876      | 4349   | 66.5%   |
| 0.51-1.0        | 969       | 1396   | 22.4%   |
| 1.01-2.0        | 281       | 443    | 6.5%    |
| 3.01-4.0        | 83        | 146    | 1.92%   |
| 2.01-3.0        | 59        | 104    | 1.36%   |
| 4.01-10.0       | 51        | 81     | 1.18%   |
| 10.01-20.0      | 4         | 6      | 0.09%   |
| More than 100.0 | 1         | 1      | 0.02%   |
| 0               | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1336      | 30.8%   |
| 251-500        | 982       | 22.64%  |
| 501-1000       | 564       | 13%     |
| 51-100         | 391       | 9.02%   |
| 1001-2000      | 284       | 6.55%   |
| 21-50          | 282       | 6.5%    |
| 1-20           | 203       | 4.68%   |
| More than 3000 | 164       | 3.78%   |
| 2001-3000      | 104       | 2.4%    |
| Unknown        | 27        | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1823      | 40.43%  |
| 21-50          | 781       | 17.32%  |
| 101-250        | 567       | 12.57%  |
| 51-100         | 532       | 11.8%   |
| 251-500        | 308       | 6.83%   |
| 501-1000       | 235       | 5.21%   |
| 1001-2000      | 119       | 2.64%   |
| More than 3000 | 70        | 1.55%   |
| 2001-3000      | 47        | 1.04%   |
| Unknown        | 27        | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 9         | 9      | 2.6%    |
| Seagate ST500DM002-1BD142 500GB     | 8         | 8      | 2.31%   |
| Seagate ST9500325AS 500GB           | 6         | 8      | 1.73%   |
| Toshiba MQ01ABD100 1TB              | 5         | 6      | 1.45%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 1.45%   |
| Seagate ST2000DM001-1CH164 2TB      | 4         | 6      | 1.16%   |
| Samsung Electronics HM321HI 320GB   | 4         | 5      | 1.16%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 3      | 0.87%   |
| Seagate ST3500418AS 500GB           | 3         | 4      | 0.87%   |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 3      | 0.87%   |
| Maxtor STM3160215AS 160GB           | 3         | 3      | 0.87%   |
| Hitachi HDS721050CLA362 500GB       | 3         | 3      | 0.87%   |
| HGST HTS545050A7E680 500GB          | 3         | 3      | 0.87%   |
| HGST HTS541010A9E680 1TB            | 3         | 3      | 0.87%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 2         | 2      | 0.58%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 2         | 2      | 0.58%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.58%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 2         | 2      | 0.58%   |
| WDC WD4000FYYZ-01UL1B1 4TB          | 2         | 3      | 0.58%   |
| WDC WD3200AAKS-00L9A0 320GB         | 2         | 2      | 0.58%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 2         | 2      | 0.58%   |
| Toshiba MQ01ABD050 500GB            | 2         | 2      | 0.58%   |
| Toshiba MK2552GSX 250GB             | 2         | 2      | 0.58%   |
| Toshiba DT01ACA100 1TB              | 2         | 2      | 0.58%   |
| Seagate ST9500423AS 500GB           | 2         | 2      | 0.58%   |
| Seagate ST9320423AS 320GB           | 2         | 2      | 0.58%   |
| Seagate ST9320325AS 320GB           | 2         | 2      | 0.58%   |
| Seagate ST9250410AS 250GB           | 2         | 2      | 0.58%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 0.58%   |
| Seagate ST3250318AS 250GB           | 2         | 4      | 0.58%   |
| Seagate ST3250310AS 250GB           | 2         | 2      | 0.58%   |
| Seagate ST320LT007-9ZV142 320GB     | 2         | 2      | 0.58%   |
| Seagate ST31000528AS 1TB            | 2         | 2      | 0.58%   |
| Seagate ST1000DM003-1ER162 1TB      | 2         | 2      | 0.58%   |
| Seagate ST1000DL002-9TT153 1TB      | 2         | 2      | 0.58%   |
| Samsung Electronics HD753LJ 752GB   | 2         | 3      | 0.58%   |
| Samsung Electronics HD103SJ 1TB     | 2         | 3      | 0.58%   |
| Samsung Electronics HD103SI 1TB     | 2         | 2      | 0.58%   |
| Samsung Electronics HD081GJ 80GB    | 2         | 2      | 0.58%   |
| Kingston SV300S37A120G 120GB SSD    | 2         | 2      | 0.58%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 99        | 113    | 29.29%  |
| WDC                 | 66        | 77     | 19.53%  |
| Toshiba             | 32        | 38     | 9.47%   |
| Hitachi             | 31        | 38     | 9.17%   |
| Samsung Electronics | 26        | 33     | 7.69%   |
| HGST                | 10        | 13     | 2.96%   |
| Maxtor              | 8         | 8      | 2.37%   |
| Kingston            | 8         | 10     | 2.37%   |
| Fujitsu             | 8         | 9      | 2.37%   |
| Intel               | 6         | 7      | 1.78%   |
| SK hynix            | 5         | 6      | 1.48%   |
| SanDisk             | 4         | 4      | 1.18%   |
| Crucial             | 3         | 3      | 0.89%   |
| A-DATA Technology   | 3         | 4      | 0.89%   |
| OCZ                 | 2         | 2      | 0.59%   |
| Micron Technology   | 2         | 2      | 0.59%   |
| KingDian            | 2         | 4      | 0.59%   |
| China               | 2         | 2      | 0.59%   |
| Unknown             | 1         | 1      | 0.3%    |
| SSSTC               | 1         | 1      | 0.3%    |
| SPCC                | 1         | 1      | 0.3%    |
| PNY                 | 1         | 1      | 0.3%    |
| Netac               | 1         | 1      | 0.3%    |
| Neo Forza           | 1         | 1      | 0.3%    |
| Mushkin             | 1         | 1      | 0.3%    |
| LITEON              | 1         | 1      | 0.3%    |
| LDLC                | 1         | 1      | 0.3%    |
| KEEPDATA            | 1         | 1      | 0.3%    |
| JMicron Technology  | 1         | 1      | 0.3%    |
| ICY BOX             | 1         | 2      | 0.3%    |
| Hewlett-Packard     | 1         | 1      | 0.3%    |
| FORESEE             | 1         | 1      | 0.3%    |
| Drevo               | 1         | 1      | 0.3%    |
| Corsair             | 1         | 1      | 0.3%    |
| Avant               | 1         | 1      | 0.3%    |
| ASMT                | 1         | 4      | 0.3%    |
| Apple               | 1         | 1      | 0.3%    |
| Apacer              | 1         | 1      | 0.3%    |
| Unknown             | 1         | 1      | 0.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 99        | 113    | 36.26%  |
| WDC                 | 63        | 74     | 23.08%  |
| Toshiba             | 31        | 37     | 11.36%  |
| Hitachi             | 31        | 38     | 11.36%  |
| Samsung Electronics | 20        | 26     | 7.33%   |
| HGST                | 10        | 13     | 3.66%   |
| Maxtor              | 8         | 8      | 2.93%   |
| Fujitsu             | 8         | 9      | 2.93%   |
| ICY BOX             | 1         | 2      | 0.37%   |
| Hewlett-Packard     | 1         | 1      | 0.37%   |
| ASMT                | 1         | 4      | 0.37%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 257       | 325    | 80.31%  |
| SSD  | 61        | 71     | 19.06%  |
| NVMe | 2         | 2      | 0.63%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00J99B0 2TB         | 1         | 2      | 25%     |
| Toshiba DT01ACA200 2TB           | 1         | 1      | 25%     |
| Seagate ST500DM002-1BC142 500GB  | 1         | 1      | 25%     |
| A-DATA Technology SP800 32GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 1         | 2      | 25%     |
| Toshiba           | 1         | 1      | 25%     |
| Seagate           | 1         | 1      | 25%     |
| A-DATA Technology | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2831      | 5351   | 64.4%   |
| Works    | 1248      | 2091   | 28.39%  |
| Malfunc  | 313       | 398    | 7.12%   |
| Failed   | 4         | 5      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2882      | 61.18%  |
| AMD                              | 709       | 15.05%  |
| Samsung Electronics              | 230       | 4.88%   |
| Nvidia                           | 145       | 3.08%   |
| SanDisk                          | 96        | 2.04%   |
| JMicron Technology               | 68        | 1.44%   |
| ASMedia Technology               | 68        | 1.44%   |
| SK hynix                         | 57        | 1.21%   |
| VIA Technologies                 | 55        | 1.17%   |
| Marvell Technology Group         | 51        | 1.08%   |
| Kingston Technology Company      | 41        | 0.87%   |
| Silicon Integrated Systems [SiS] | 40        | 0.85%   |
| Phison Electronics               | 36        | 0.76%   |
| Toshiba America Info Systems     | 27        | 0.57%   |
| KIOXIA                           | 24        | 0.51%   |
| Silicon Motion                   | 21        | 0.45%   |
| Micron Technology                | 18        | 0.38%   |
| Micron/Crucial Technology        | 17        | 0.36%   |
| ADATA Technology                 | 17        | 0.36%   |
| LSI Logic / Symbios Logic        | 15        | 0.32%   |
| Realtek Semiconductor            | 12        | 0.25%   |
| Silicon Image                    | 11        | 0.23%   |
| Broadcom / LSI                   | 11        | 0.23%   |
| Adaptec                          | 7         | 0.15%   |
| ULi Electronics                  | 6         | 0.13%   |
| Hewlett-Packard                  | 6         | 0.13%   |
| Apple                            | 6         | 0.13%   |
| Union Memory (Shenzhen)          | 5         | 0.11%   |
| Integrated Technology Express    | 5         | 0.11%   |
| Seagate Technology               | 4         | 0.08%   |
| Promise Technology               | 4         | 0.08%   |
| Lenovo                           | 4         | 0.08%   |
| Lite-On Technology               | 3         | 0.06%   |
| Shenzhen Longsys Electronics     | 2         | 0.04%   |
| INNOGRIT                         | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Solid State Storage Technology   | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 421       | 7.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 182       | 3.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 178       | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 168       | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 159       | 2.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 140       | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 136       | 2.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 128       | 2.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 124       | 2.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 121       | 2.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 113       | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 111       | 1.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 104       | 1.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 100       | 1.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 97        | 1.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 81        | 1.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 77        | 1.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 75        | 1.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 67        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 66        | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 66        | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 64        | 1.09%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 64        | 1.09%   |
| AMD 400 Series Chipset SATA Controller                                                  | 63        | 1.07%   |
| Nvidia MCP61 SATA Controller                                                            | 62        | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 62        | 1.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 61        | 1.04%   |
| Intel SATA Controller [RAID mode]                                                       | 60        | 1.02%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 54        | 0.92%   |
| Nvidia MCP61 IDE                                                                        | 49        | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 49        | 0.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 48        | 0.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 47        | 0.8%    |
| Samsung NVMe SSD Controller 980                                                         | 46        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 45        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 44        | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 44        | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 43        | 0.73%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 40        | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 40        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2819      | 56.4%   |
| IDE  | 1229      | 24.59%  |
| NVMe | 641       | 12.83%  |
| RAID | 282       | 5.64%   |
| SAS  | 14        | 0.28%   |
| SCSI | 13        | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3215      | 77.28%  |
| AMD          | 889       | 21.37%  |
| ARM          | 51        | 1.23%   |
| CentaurHauls | 4         | 0.1%    |
| Unknown      | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ARM Processor                           | 40        | 0.96%   |
| Intel Atom CPU N270 @ 1.60GHz           | 32        | 0.77%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 27        | 0.65%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 26        | 0.62%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 26        | 0.62%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 24        | 0.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 24        | 0.57%   |
| Intel Pentium 4 CPU 3.00GHz             | 23        | 0.55%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 23        | 0.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 22        | 0.53%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 22        | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 22        | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 22        | 0.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 22        | 0.53%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 22        | 0.53%   |
| Intel Atom CPU N450 @ 1.66GHz           | 22        | 0.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 21        | 0.5%    |
| Intel Core i5-3470 CPU @ 3.20GHz        | 21        | 0.5%    |
| Intel Core i3-4130 CPU @ 3.40GHz        | 21        | 0.5%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 20        | 0.48%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 20        | 0.48%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 19        | 0.45%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 18        | 0.43%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 18        | 0.43%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 18        | 0.43%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 18        | 0.43%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 17        | 0.41%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 17        | 0.41%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 17        | 0.41%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz    | 17        | 0.41%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 16        | 0.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 16        | 0.38%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 16        | 0.38%   |
| AMD Ryzen 5 3600 6-Core Processor       | 16        | 0.38%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 15        | 0.36%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 15        | 0.36%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 15        | 0.36%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 15        | 0.36%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 15        | 0.36%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 15        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 706       | 16.91%  |
| Intel Core i7           | 522       | 12.51%  |
| Intel Core 2 Duo        | 326       | 7.81%   |
| Intel Core i3           | 325       | 7.79%   |
| Intel Celeron           | 299       | 7.16%   |
| Intel Atom              | 183       | 4.38%   |
| Other                   | 161       | 3.86%   |
| AMD Ryzen 5             | 131       | 3.14%   |
| Intel Pentium           | 125       | 2.99%   |
| Intel Xeon              | 102       | 2.44%   |
| AMD Ryzen 7             | 93        | 2.23%   |
| Intel Pentium Dual-Core | 92        | 2.2%    |
| Intel Pentium Dual      | 67        | 1.61%   |
| Intel Pentium 4         | 65        | 1.56%   |
| Intel Genuine           | 59        | 1.41%   |
| Intel Core 2            | 58        | 1.39%   |
| Intel Core 2 Quad       | 55        | 1.32%   |
| AMD FX                  | 53        | 1.27%   |
| AMD A8                  | 51        | 1.22%   |
| AMD Athlon 64 X2        | 42        | 1.01%   |
| AMD A6                  | 34        | 0.81%   |
| AMD Ryzen 9             | 32        | 0.77%   |
| AMD E1                  | 32        | 0.77%   |
| AMD Ryzen 3             | 30        | 0.72%   |
| AMD Phenom II X4        | 30        | 0.72%   |
| Intel Pentium M         | 28        | 0.67%   |
| AMD Athlon II X2        | 28        | 0.67%   |
| AMD A4                  | 25        | 0.6%    |
| Intel Celeron M         | 24        | 0.57%   |
| AMD A10                 | 22        | 0.53%   |
| AMD Turion 64 X2 Mobile | 20        | 0.48%   |
| AMD Sempron             | 20        | 0.48%   |
| AMD E                   | 20        | 0.48%   |
| AMD Athlon              | 20        | 0.48%   |
| Intel Pentium D         | 17        | 0.41%   |
| AMD Ryzen 7 PRO         | 17        | 0.41%   |
| Intel Core i9           | 16        | 0.38%   |
| AMD E2                  | 16        | 0.38%   |
| AMD Athlon 64           | 16        | 0.38%   |
| Intel Pentium Silver    | 13        | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2028      | 48.61%  |
| 4       | 1283      | 30.75%  |
| 1       | 356       | 8.53%   |
| 6       | 222       | 5.32%   |
| 8       | 170       | 4.07%   |
| 12      | 39        | 0.93%   |
| 16      | 22        | 0.53%   |
| 3       | 18        | 0.43%   |
| 10      | 11        | 0.26%   |
| Unknown | 9         | 0.22%   |
| 24      | 4         | 0.1%    |
| 14      | 4         | 0.1%    |
| 64      | 3         | 0.07%   |
| 20      | 3         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4105      | 98.68%  |
| 2       | 47        | 1.13%   |
| Unknown | 8         | 0.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2084      | 50.04%  |
| 1       | 2071      | 49.72%  |
| Unknown | 9         | 0.22%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3931      | 94.47%  |
| 32-bit         | 195       | 4.69%   |
| Unknown        | 31        | 0.75%   |
| 64-bit         | 4         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 834       | 19.47%  |
| 0x206a7    | 270       | 6.3%    |
| 0x306a9    | 249       | 5.81%   |
| 0x1067a    | 243       | 5.67%   |
| 0x306c3    | 170       | 3.97%   |
| 0x6fd      | 145       | 3.38%   |
| 0x20655    | 91        | 2.12%   |
| 0x10676    | 85        | 1.98%   |
| 0x40651    | 69        | 1.61%   |
| 0x506e3    | 67        | 1.56%   |
| 0x906ea    | 62        | 1.45%   |
| 0x30678    | 62        | 1.45%   |
| 0x406c4    | 60        | 1.4%    |
| 0x406e3    | 57        | 1.33%   |
| 0x106ca    | 55        | 1.28%   |
| 0x6fb      | 54        | 1.26%   |
| 0x010000c8 | 54        | 1.26%   |
| 0x6f6      | 52        | 1.21%   |
| 0x806ea    | 51        | 1.19%   |
| 0x106c2    | 48        | 1.12%   |
| 0x806ec    | 47        | 1.1%    |
| 0x806c1    | 47        | 1.1%    |
| 0x20652    | 46        | 1.07%   |
| 0x806e9    | 43        | 1%      |
| 0x306d4    | 43        | 1%      |
| 0x906e9    | 42        | 0.98%   |
| 0x06000852 | 39        | 0.91%   |
| 0x08108109 | 36        | 0.84%   |
| 0x6e8      | 35        | 0.82%   |
| 0x6d8      | 34        | 0.79%   |
| 0x406c3    | 34        | 0.79%   |
| 0x106e5    | 33        | 0.77%   |
| 0x05000119 | 33        | 0.77%   |
| 0x08701021 | 31        | 0.72%   |
| 0x0800820d | 31        | 0.72%   |
| 0x07030105 | 31        | 0.72%   |
| 0x506c9    | 27        | 0.63%   |
| 0x706a1    | 26        | 0.61%   |
| 0x0700010f | 26        | 0.61%   |
| 0x06001119 | 26        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 377       | 9.04%   |
| KabyLake         | 357       | 8.56%   |
| SandyBridge      | 328       | 7.86%   |
| Core             | 308       | 7.38%   |
| Haswell          | 300       | 7.19%   |
| IvyBridge        | 298       | 7.14%   |
| Silvermont       | 195       | 4.68%   |
| Westmere         | 176       | 4.22%   |
| Skylake          | 159       | 3.81%   |
| Bonnell          | 130       | 3.12%   |
| K8 Hammer        | 127       | 3.04%   |
| K10              | 118       | 2.83%   |
| Zen 2            | 105       | 2.52%   |
| Unknown          | 105       | 2.52%   |
| P6               | 100       | 2.4%    |
| Zen+             | 94        | 2.25%   |
| NetBurst         | 92        | 2.21%   |
| Piledriver       | 76        | 1.82%   |
| CometLake        | 66        | 1.58%   |
| TigerLake        | 61        | 1.46%   |
| Broadwell        | 58        | 1.39%   |
| Zen              | 55        | 1.32%   |
| Zen 3            | 52        | 1.25%   |
| Goldmont plus    | 52        | 1.25%   |
| Nehalem          | 51        | 1.22%   |
| Bobcat           | 49        | 1.17%   |
| Excavator        | 43        | 1.03%   |
| Goldmont         | 41        | 0.98%   |
| Puma             | 40        | 0.96%   |
| IceLake          | 35        | 0.84%   |
| Jaguar           | 31        | 0.74%   |
| K10 Llano        | 29        | 0.7%    |
| Alderlake Hybrid | 18        | 0.43%   |
| Steamroller      | 14        | 0.34%   |
| K8 & K10 hybrid  | 12        | 0.29%   |
| Bulldozer        | 10        | 0.24%   |
| K6               | 6         | 0.14%   |
| Tremont          | 3         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2355      | 51%     |
| Nvidia                           | 1163      | 25.18%  |
| AMD                              | 1022      | 22.13%  |
| Silicon Integrated Systems [SiS] | 26        | 0.56%   |
| Matrox Electronics Systems       | 22        | 0.48%   |
| VIA Technologies                 | 19        | 0.41%   |
| ASPEED Technology                | 9         | 0.19%   |
| S3 Graphics                      | 1         | 0.02%   |
| Alliance Semiconductor           | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 243       | 4.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 157       | 3.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 126       | 2.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 108       | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 106       | 2.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 91        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 88        | 1.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 86        | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 86        | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 85        | 1.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 78        | 1.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 66        | 1.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 63        | 1.28%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 61        | 1.24%   |
| Intel UHD Graphics 620                                                                   | 58        | 1.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 58        | 1.18%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 56        | 1.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 55        | 1.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 54        | 1.1%    |
| Intel HD Graphics 620                                                                    | 52        | 1.06%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 50        | 1.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 50        | 1.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 46        | 0.94%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 44        | 0.9%    |
| Intel HD Graphics 530                                                                    | 43        | 0.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 43        | 0.88%   |
| Intel HD Graphics 5500                                                                   | 41        | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 41        | 0.84%   |
| AMD Renoir                                                                               | 40        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 35        | 0.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 34        | 0.69%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 34        | 0.69%   |
| Intel HD Graphics 500                                                                    | 34        | 0.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 34        | 0.69%   |
| Nvidia GT218 [GeForce 210]                                                               | 33        | 0.67%   |
| Intel HD Graphics 630                                                                    | 30        | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 30        | 0.61%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 28        | 0.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 26        | 0.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 25        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 1909      | 45.62%  |
| 1 x AMD                              | 819       | 19.57%  |
| 1 x Nvidia                           | 806       | 19.26%  |
| Intel + Nvidia                       | 306       | 7.31%   |
| Intel + AMD                          | 92        | 2.2%    |
| 2 x AMD                              | 70        | 1.67%   |
| Other                                | 62        | 1.48%   |
| AMD + Nvidia                         | 32        | 0.76%   |
| 1 x SiS                              | 26        | 0.62%   |
| 1 x VIA                              | 19        | 0.45%   |
| 1 x Matrox                           | 16        | 0.38%   |
| Nvidia + ASPEED                      | 6         | 0.14%   |
| 2 x Nvidia                           | 5         | 0.12%   |
| Nvidia + Matrox                      | 3         | 0.07%   |
| 2 x Intel                            | 2         | 0.05%   |
| 1 x ASPEED                           | 2         | 0.05%   |
| AMD + Matrox                         | 2         | 0.05%   |
| 3 x AMD                              | 1         | 0.02%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia                 | 1         | 0.02%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.02%   |
| 1 x S3 Graphics                      | 1         | 0.02%   |
| Intel + 2 x AMD                      | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia             | 1         | 0.02%   |
| AMD + ASPEED                         | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3356      | 80%     |
| Proprietary | 630       | 15.02%  |
| Unknown     | 209       | 4.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2196      | 51.66%  |
| 0.01-0.5   | 817       | 19.22%  |
| 1.01-2.0   | 483       | 11.36%  |
| 0.51-1.0   | 374       | 8.8%    |
| 3.01-4.0   | 204       | 4.8%    |
| 7.01-8.0   | 80        | 1.88%   |
| 5.01-6.0   | 50        | 1.18%   |
| 8.01-16.0  | 24        | 0.56%   |
| 2.01-3.0   | 18        | 0.42%   |
| 4.01-5.0   | 2         | 0.05%   |
| 16.01-24.0 | 2         | 0.05%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 617       | 14.42%  |
| AU Optronics            | 469       | 10.96%  |
| LG Display              | 367       | 8.58%   |
| Chimei Innolux          | 248       | 5.8%    |
| Dell                    | 237       | 5.54%   |
| BOE                     | 237       | 5.54%   |
| Goldstar                | 199       | 4.65%   |
| Hewlett-Packard         | 158       | 3.69%   |
| Acer                    | 154       | 3.6%    |
| AOC                     | 113       | 2.64%   |
| Philips                 | 106       | 2.48%   |
| Chi Mei Optoelectronics | 102       | 2.38%   |
| Lenovo                  | 100       | 2.34%   |
| Ancor Communications    | 89        | 2.08%   |
| BenQ                    | 77        | 1.8%    |
| LG Philips              | 73        | 1.71%   |
| Apple                   | 61        | 1.43%   |
| ViewSonic               | 54        | 1.26%   |
| HannStar                | 52        | 1.22%   |
| Iiyama                  | 44        | 1.03%   |
| Unknown                 | 39        | 0.91%   |
| Sony                    | 39        | 0.91%   |
| LG Electronics          | 36        | 0.84%   |
| Sharp                   | 34        | 0.79%   |
| InfoVision              | 34        | 0.79%   |
| Fujitsu Siemens         | 28        | 0.65%   |
| CPT                     | 24        | 0.56%   |
| NEC Computers           | 23        | 0.54%   |
| Panasonic               | 22        | 0.51%   |
| PANDA                   | 20        | 0.47%   |
| Eizo                    | 19        | 0.44%   |
| Toshiba                 | 17        | 0.4%    |
| ASUSTek Computer        | 17        | 0.4%    |
| Vizio                   | 14        | 0.33%   |
| Medion                  | 14        | 0.33%   |
| Quanta Display          | 11        | 0.26%   |
| PKB                     | 11        | 0.26%   |
| Packard Bell            | 11        | 0.26%   |
| RTK                     | 10        | 0.23%   |
| Vestel Elektronik       | 9         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 25        | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 21        | 0.48%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 20        | 0.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.38%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                       | 16        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.29%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 13        | 0.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.27%   |
| Panasonic TV MEIA296 3840x2160 1280x720mm 57.8-inch                      | 10        | 0.23%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 10        | 0.23%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 10        | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 10        | 0.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.23%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 10        | 0.23%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 10        | 0.23%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                            | 9         | 0.2%    |
| PKB LCD Monitor Viseo223DX 1920x1080                                     | 9         | 0.2%    |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 9         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 9         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 9         | 0.2%    |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 9         | 0.2%    |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 8         | 0.18%   |
| Packard Bell Viseo223DX PKB0385 1920x1080 477x268mm 21.5-inch            | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.18%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 8         | 0.18%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.18%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 8         | 0.18%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 8         | 0.18%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch     | 8         | 0.18%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 7         | 0.16%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 7         | 0.16%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 7         | 0.16%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 7         | 0.16%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 7         | 0.16%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 7         | 0.16%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 7         | 0.16%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1417      | 33.96%  |
| 1366x768 (WXGA)    | 916       | 21.96%  |
| 1280x800 (WXGA)    | 260       | 6.23%   |
| 1280x1024 (SXGA)   | 236       | 5.66%   |
| 1600x900 (HD+)     | 209       | 5.01%   |
| 1440x900 (WXGA+)   | 184       | 4.41%   |
| 3840x2160 (4K)     | 157       | 3.76%   |
| 1680x1050 (WSXGA+) | 154       | 3.69%   |
| 2560x1440 (QHD)    | 114       | 2.73%   |
| 1920x1200 (WUXGA)  | 98        | 2.35%   |
| 1024x600           | 71        | 1.7%    |
| Unknown            | 61        | 1.46%   |
| 1024x768 (XGA)     | 46        | 1.1%    |
| 1360x768           | 43        | 1.03%   |
| 3840x1080          | 24        | 0.58%   |
| 1920x540           | 17        | 0.41%   |
| 1600x1200          | 17        | 0.41%   |
| 3440x1440          | 14        | 0.34%   |
| 2560x1080          | 14        | 0.34%   |
| 2560x1600          | 13        | 0.31%   |
| 1280x720 (HD)      | 10        | 0.24%   |
| 2288x1287          | 8         | 0.19%   |
| 3200x1080          | 6         | 0.14%   |
| 2160x1440          | 5         | 0.12%   |
| 2048x1152          | 5         | 0.12%   |
| 1400x1050          | 5         | 0.12%   |
| 5120x1440          | 4         | 0.1%    |
| 3840x1200          | 4         | 0.1%    |
| 3200x1800 (QHD+)   | 4         | 0.1%    |
| 2880x1800          | 4         | 0.1%    |
| 3840x2400          | 3         | 0.07%   |
| 4480x1440          | 2         | 0.05%   |
| 3840x1600          | 2         | 0.05%   |
| 3600x1080          | 2         | 0.05%   |
| 3286x1080          | 2         | 0.05%   |
| 3200x900           | 2         | 0.05%   |
| 2960x1050          | 2         | 0.05%   |
| 2048x1536          | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 800x600            | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1024      | 24%     |
| 14      | 323       | 7.57%   |
| 17      | 317       | 7.43%   |
| Unknown | 308       | 7.22%   |
| 13      | 283       | 6.63%   |
| 23      | 256       | 6%      |
| 21      | 239       | 5.6%    |
| 24      | 235       | 5.51%   |
| 19      | 198       | 4.64%   |
| 27      | 182       | 4.27%   |
| 18      | 139       | 3.26%   |
| 20      | 102       | 2.39%   |
| 12      | 86        | 2.02%   |
| 22      | 83        | 1.95%   |
| 10      | 78        | 1.83%   |
| 31      | 76        | 1.78%   |
| 11      | 75        | 1.76%   |
| 84      | 31        | 0.73%   |
| 54      | 23        | 0.54%   |
| 72      | 22        | 0.52%   |
| 34      | 20        | 0.47%   |
| 16      | 20        | 0.47%   |
| 40      | 19        | 0.45%   |
| 32      | 19        | 0.45%   |
| 26      | 18        | 0.42%   |
| 25      | 14        | 0.33%   |
| 52      | 10        | 0.23%   |
| 28      | 8         | 0.19%   |
| 48      | 7         | 0.16%   |
| 37      | 7         | 0.16%   |
| 46      | 6         | 0.14%   |
| 49      | 4         | 0.09%   |
| 8       | 4         | 0.09%   |
| 142     | 3         | 0.07%   |
| 65      | 3         | 0.07%   |
| 29      | 3         | 0.07%   |
| 74      | 2         | 0.05%   |
| 63      | 2         | 0.05%   |
| 60      | 2         | 0.05%   |
| 57      | 2         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1584      | 37.59%  |
| 501-600        | 646       | 15.33%  |
| 401-500        | 632       | 15%     |
| 201-300        | 381       | 9.04%   |
| 351-400        | 353       | 8.38%   |
| Unknown        | 308       | 7.31%   |
| 601-700        | 113       | 2.68%   |
| 1001-1500      | 59        | 1.4%    |
| 1501-2000      | 56        | 1.33%   |
| 701-800        | 41        | 0.97%   |
| 801-900        | 30        | 0.71%   |
| 101-200        | 5         | 0.12%   |
| More than 2000 | 3         | 0.07%   |
| 901-1000       | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2642      | 66.58%  |
| 16/10   | 665       | 16.76%  |
| Unknown | 280       | 7.06%   |
| 5/4     | 220       | 5.54%   |
| 4/3     | 83        | 2.09%   |
| 3/2     | 28        | 0.71%   |
| 21/9    | 25        | 0.63%   |
| 6/5     | 12        | 0.3%    |
| 1.00    | 5         | 0.13%   |
| 32/9    | 4         | 0.1%    |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1022      | 24.12%  |
| 201-250        | 650       | 15.34%  |
| 81-90          | 489       | 11.54%  |
| 151-200        | 399       | 9.41%   |
| Unknown        | 308       | 7.27%   |
| 141-150        | 223       | 5.26%   |
| 301-350        | 192       | 4.53%   |
| 121-130        | 152       | 3.59%   |
| 351-500        | 123       | 2.9%    |
| More than 1000 | 108       | 2.55%   |
| 71-80          | 102       | 2.41%   |
| 251-300        | 99        | 2.34%   |
| 61-70          | 79        | 1.86%   |
| 41-50          | 77        | 1.82%   |
| 51-60          | 76        | 1.79%   |
| 131-140        | 52        | 1.23%   |
| 501-1000       | 44        | 1.04%   |
| 91-100         | 24        | 0.57%   |
| 111-120        | 14        | 0.33%   |
| 1-40           | 5         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1586      | 38.64%  |
| 101-120       | 1186      | 28.89%  |
| 121-160       | 787       | 19.17%  |
| Unknown       | 308       | 7.5%    |
| 161-240       | 110       | 2.68%   |
| 1-50          | 97        | 2.36%   |
| More than 240 | 31        | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3495      | 82.45%  |
| 2     | 513       | 12.1%   |
| 0     | 188       | 4.44%   |
| 3     | 39        | 0.92%   |
| 4     | 4         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2171      | 34.1%   |
| Intel                             | 1707      | 26.81%  |
| Qualcomm Atheros                  | 794       | 12.47%  |
| Broadcom                          | 451       | 7.08%   |
| Marvell Technology Group          | 151       | 2.37%   |
| Broadcom Limited                  | 122       | 1.92%   |
| Nvidia                            | 117       | 1.84%   |
| Ralink Technology                 | 97        | 1.52%   |
| Ralink                            | 87        | 1.37%   |
| TP-Link                           | 73        | 1.15%   |
| VIA Technologies                  | 42        | 0.66%   |
| MediaTek                          | 39        | 0.61%   |
| Qualcomm Atheros Communications   | 37        | 0.58%   |
| Samsung Electronics               | 34        | 0.53%   |
| Silicon Integrated Systems [SiS]  | 33        | 0.52%   |
| Huawei Technologies               | 29        | 0.46%   |
| D-Link System                     | 26        | 0.41%   |
| JMicron Technology                | 24        | 0.38%   |
| NetGear                           | 23        | 0.36%   |
| Sierra Wireless                   | 19        | 0.3%    |
| D-Link                            | 18        | 0.28%   |
| ASIX Electronics                  | 16        | 0.25%   |
| Ericsson Business Mobile Networks | 15        | 0.24%   |
| Attansic Technology               | 15        | 0.24%   |
| Xiaomi                            | 12        | 0.19%   |
| Dell                              | 12        | 0.19%   |
| ASUSTek Computer                  | 12        | 0.19%   |
| Qualcomm                          | 10        | 0.16%   |
| Edimax Technology                 | 10        | 0.16%   |
| DisplayLink                       | 10        | 0.16%   |
| Aquantia                          | 10        | 0.16%   |
| Lenovo                            | 9         | 0.14%   |
| Belkin Components                 | 9         | 0.14%   |
| AMD                               | 8         | 0.13%   |
| Fibocom                           | 7         | 0.11%   |
| Microsoft                         | 6         | 0.09%   |
| Linksys                           | 6         | 0.09%   |
| ZyDAS                             | 5         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 5         | 0.08%   |
| ULi Electronics                   | 5         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1375      | 18.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 340       | 4.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 181       | 2.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 122       | 1.65%   |
| Intel Wi-Fi 6 AX200                                                     | 98        | 1.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 98        | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 97        | 1.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 93        | 1.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 93        | 1.26%   |
| Intel Wireless 7260                                                     | 81        | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 75        | 1.01%   |
| Intel Wireless 7265                                                     | 68        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 67        | 0.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 64        | 0.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 64        | 0.87%   |
| Intel Wireless 8265 / 8275                                              | 63        | 0.85%   |
| Intel Ethernet Connection I217-LM                                       | 63        | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 60        | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 55        | 0.74%   |
| Nvidia MCP61 Ethernet                                                   | 55        | 0.74%   |
| Intel Wireless 8260                                                     | 55        | 0.74%   |
| Intel Wireless 3165                                                     | 52        | 0.7%    |
| Intel I211 Gigabit Network Connection                                   | 50        | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 48        | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                       | 45        | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 44        | 0.6%    |
| Intel Wi-Fi 6 AX201                                                     | 44        | 0.6%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 42        | 0.57%   |
| Intel 82579V Gigabit Network Connection                                 | 41        | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 40        | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                    | 40        | 0.54%   |
| Ralink MT7601U Wireless Adapter                                         | 39        | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 38        | 0.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 37        | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 37        | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                            | 34        | 0.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 34        | 0.46%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 34        | 0.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 33        | 0.45%   |
| Qualcomm Atheros AR9271 802.11n                                         | 32        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1182      | 36.83%  |
| Qualcomm Atheros                      | 645       | 20.1%   |
| Realtek Semiconductor                 | 553       | 17.23%  |
| Broadcom                              | 271       | 8.44%   |
| Ralink Technology                     | 97        | 3.02%   |
| Ralink                                | 87        | 2.71%   |
| TP-Link                               | 68        | 2.12%   |
| Broadcom Limited                      | 57        | 1.78%   |
| Qualcomm Atheros Communications       | 37        | 1.15%   |
| MediaTek                              | 29        | 0.9%    |
| NetGear                               | 23        | 0.72%   |
| Sierra Wireless                       | 19        | 0.59%   |
| D-Link System                         | 18        | 0.56%   |
| D-Link                                | 17        | 0.53%   |
| ASUSTek Computer                      | 11        | 0.34%   |
| Edimax Technology                     | 10        | 0.31%   |
| Belkin Components                     | 9         | 0.28%   |
| Qualcomm                              | 7         | 0.22%   |
| Fibocom                               | 7         | 0.22%   |
| Dell                                  | 7         | 0.22%   |
| Microsoft                             | 6         | 0.19%   |
| Linksys                               | 6         | 0.19%   |
| ZyDAS                                 | 5         | 0.16%   |
| Sitecom Europe                        | 5         | 0.16%   |
| Marvell Technology Group              | 4         | 0.12%   |
| IMC Networks                          | 4         | 0.12%   |
| AVM                                   | 4         | 0.12%   |
| TRENDnet                              | 3         | 0.09%   |
| Ericsson Business Mobile Networks     | 3         | 0.09%   |
| Hewlett-Packard                       | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Xiaomi                                | 1         | 0.03%   |
| Winbond Electronics                   | 1         | 0.03%   |
| Toshiba                               | 1         | 0.03%   |
| Texas Instruments                     | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 122       | 3.76%   |
| Intel Wi-Fi 6 AX200                                                     | 98        | 3.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 98        | 3.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 97        | 2.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 93        | 2.87%   |
| Intel Wireless 7260                                                     | 81        | 2.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 75        | 2.31%   |
| Intel Wireless 7265                                                     | 68        | 2.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 67        | 2.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 64        | 1.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 64        | 1.97%   |
| Intel Wireless 8265 / 8275                                              | 63        | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 60        | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 55        | 1.69%   |
| Intel Wireless 8260                                                     | 55        | 1.69%   |
| Intel Wireless 3165                                                     | 52        | 1.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 44        | 1.36%   |
| Intel Wi-Fi 6 AX201                                                     | 44        | 1.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 42        | 1.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 40        | 1.23%   |
| Ralink MT7601U Wireless Adapter                                         | 39        | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 37        | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 37        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 34        | 1.05%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 34        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 33        | 1.02%   |
| Qualcomm Atheros AR9271 802.11n                                         | 32        | 0.99%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 31        | 0.96%   |
| Intel Centrino Advanced-N 6200                                          | 31        | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 30        | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                           | 30        | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 29        | 0.89%   |
| Intel Wireless 3160                                                     | 29        | 0.89%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 29        | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 29        | 0.89%   |
| Intel Wireless-AC 9260                                                  | 26        | 0.8%    |
| Intel Centrino Ultimate-N 6300                                          | 26        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 26        | 0.8%    |
| Realtek 802.11ac NIC                                                    | 25        | 0.77%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 24        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1920      | 48.25%  |
| Intel                            | 965       | 24.25%  |
| Qualcomm Atheros                 | 245       | 6.16%   |
| Broadcom                         | 226       | 5.68%   |
| Marvell Technology Group         | 147       | 3.69%   |
| Nvidia                           | 116       | 2.92%   |
| Broadcom Limited                 | 66        | 1.66%   |
| VIA Technologies                 | 42        | 1.06%   |
| Samsung Electronics              | 33        | 0.83%   |
| Silicon Integrated Systems [SiS] | 31        | 0.78%   |
| JMicron Technology               | 24        | 0.6%    |
| Huawei Technologies              | 18        | 0.45%   |
| ASIX Electronics                 | 16        | 0.4%    |
| Attansic Technology              | 15        | 0.38%   |
| Xiaomi                           | 11        | 0.28%   |
| MediaTek                         | 11        | 0.28%   |
| DisplayLink                      | 10        | 0.25%   |
| Aquantia                         | 10        | 0.25%   |
| Lenovo                           | 9         | 0.23%   |
| D-Link System                    | 8         | 0.2%    |
| TP-Link                          | 5         | 0.13%   |
| HTC (High Tech Computer)         | 5         | 0.13%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.1%    |
| LG Electronics                   | 4         | 0.1%    |
| Qualcomm                         | 3         | 0.08%   |
| Insyde Software                  | 3         | 0.08%   |
| IBM                              | 3         | 0.08%   |
| Apple                            | 3         | 0.08%   |
| Spreadtrum Communications        | 2         | 0.05%   |
| OPPO Electronics                 | 2         | 0.05%   |
| National Semiconductor           | 2         | 0.05%   |
| Motorola PCS                     | 2         | 0.05%   |
| Microchip Technology             | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| Accton Technology                | 2         | 0.05%   |
| 3Com                             | 2         | 0.05%   |
| ULi Electronics                  | 1         | 0.03%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| Mellanox Technologies            | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1375      | 34.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 340       | 8.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 181       | 4.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 93        | 2.3%    |
| Intel Ethernet Connection I217-LM                                 | 63        | 1.56%   |
| Nvidia MCP61 Ethernet                                             | 55        | 1.36%   |
| Intel I211 Gigabit Network Connection                             | 50        | 1.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 48        | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 45        | 1.11%   |
| Intel 82579V Gigabit Network Connection                           | 41        | 1.01%   |
| Intel Ethernet Connection (2) I219-V                              | 40        | 0.99%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 38        | 0.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 34        | 0.84%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 31        | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 31        | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 30        | 0.74%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 29        | 0.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 29        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 28        | 0.69%   |
| Intel 82567LM Gigabit Network Connection                          | 28        | 0.69%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 27        | 0.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 27        | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 22        | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 22        | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 22        | 0.54%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 22        | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 21        | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 20        | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 19        | 0.47%   |
| Intel 82566MM Gigabit Network Connection                          | 19        | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 18        | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 0.45%   |
| Intel 82574L Gigabit Network Connection                           | 18        | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 17        | 0.42%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 17        | 0.42%   |
| Intel PRO/100 VE Network Connection                               | 17        | 0.42%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.42%   |
| Intel 82573L Gigabit Ethernet Controller                          | 17        | 0.42%   |
| Nvidia MCP79 Ethernet                                             | 16        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3752      | 54.68%  |
| WiFi     | 3003      | 43.76%  |
| Modem    | 100       | 1.46%   |
| Unknown  | 7         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2383      | 55.43%  |
| Ethernet | 1916      | 44.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2305      | 55.18%  |
| 1     | 1651      | 39.53%  |
| 0     | 127       | 3.04%   |
| 3     | 66        | 1.58%   |
| 4     | 21        | 0.5%    |
| 5     | 4         | 0.1%    |
| 10    | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3545      | 83.93%  |
| Yes  | 679       | 16.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 734       | 38.75%  |
| Realtek Semiconductor           | 178       | 9.4%    |
| Broadcom                        | 177       | 9.35%   |
| Qualcomm Atheros Communications | 162       | 8.55%   |
| Cambridge Silicon Radio         | 128       | 6.76%   |
| Apple                           | 67        | 3.54%   |
| Lite-On Technology              | 65        | 3.43%   |
| IMC Networks                    | 64        | 3.38%   |
| Foxconn / Hon Hai               | 62        | 3.27%   |
| Dell                            | 56        | 2.96%   |
| Hewlett-Packard                 | 52        | 2.75%   |
| ASUSTek Computer                | 30        | 1.58%   |
| Toshiba                         | 20        | 1.06%   |
| Ralink                          | 17        | 0.9%    |
| Alps Electric                   | 15        | 0.79%   |
| MediaTek                        | 9         | 0.48%   |
| Integrated System Solution      | 8         | 0.42%   |
| Realtek                         | 7         | 0.37%   |
| Ralink Technology               | 6         | 0.32%   |
| Foxconn International           | 6         | 0.32%   |
| TP-Link                         | 5         | 0.26%   |
| Chicony Electronics             | 4         | 0.21%   |
| Taiyo Yuden                     | 3         | 0.16%   |
| Edimax Technology               | 3         | 0.16%   |
| Qcom                            | 2         | 0.11%   |
| Micro Star International        | 2         | 0.11%   |
| Fujitsu                         | 2         | 0.11%   |
| USI                             | 1         | 0.05%   |
| Syntek                          | 1         | 0.05%   |
| Sitecom Europe                  | 1         | 0.05%   |
| Marvell Semiconductor           | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| ISSC                            | 1         | 0.05%   |
| Conwise Technology              | 1         | 0.05%   |
| Askey Computer                  | 1         | 0.05%   |
| Actions                         | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 329       | 17.35%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 128       | 6.75%   |
| Realtek Bluetooth Radio                                                             | 122       | 6.43%   |
| Intel AX201 Bluetooth                                                               | 100       | 5.27%   |
| Intel AX200 Bluetooth                                                               | 97        | 5.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 78        | 4.11%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 64        | 3.38%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 45        | 2.37%   |
| Intel Bluetooth Device                                                              | 43        | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 34        | 1.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 33        | 1.74%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 32        | 1.69%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 27        | 1.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 25        | 1.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 23        | 1.21%   |
| Apple Bluetooth HCI                                                                 | 22        | 1.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 20        | 1.05%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 20        | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 20        | 1.05%   |
| Lite-On Bluetooth Device                                                            | 19        | 1%      |
| Intel AX210 Bluetooth                                                               | 19        | 1%      |
| Foxconn / Hon Hai Bluetooth Device                                                  | 19        | 1%      |
| Apple Bluetooth Host Controller                                                     | 19        | 1%      |
| IMC Networks Bluetooth Device                                                       | 18        | 0.95%   |
| Ralink RT3290 Bluetooth                                                             | 17        | 0.9%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 17        | 0.9%    |
| IMC Networks Bluetooth Radio                                                        | 17        | 0.9%    |
| Broadcom BCM2045 Bluetooth                                                          | 17        | 0.9%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 16        | 0.84%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 15        | 0.79%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 15        | 0.79%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 15        | 0.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 13        | 0.69%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 13        | 0.69%   |
| Dell DW375 Bluetooth Module                                                         | 13        | 0.69%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 12        | 0.63%   |
| Toshiba Integrated Bluetooth HCI                                                    | 11        | 0.58%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 11        | 0.58%   |
| Apple Bluetooth USB Host Controller                                                 | 11        | 0.58%   |
| Dell Wireless 360 Bluetooth                                                         | 10        | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2989      | 55.4%   |
| AMD                              | 981       | 18.18%  |
| Nvidia                           | 843       | 15.63%  |
| C-Media Electronics              | 77        | 1.43%   |
| Creative Labs                    | 58        | 1.08%   |
| VIA Technologies                 | 51        | 0.95%   |
| Silicon Integrated Systems [SiS] | 40        | 0.74%   |
| Texas Instruments                | 31        | 0.57%   |
| Logitech                         | 29        | 0.54%   |
| GN Netcom                        | 18        | 0.33%   |
| Focusrite-Novation               | 15        | 0.28%   |
| M-Audio                          | 14        | 0.26%   |
| JMTek                            | 13        | 0.24%   |
| Creative Technology              | 13        | 0.24%   |
| Generalplus Technology           | 12        | 0.22%   |
| Plantronics                      | 11        | 0.2%    |
| Yamaha                           | 10        | 0.19%   |
| Lenovo                           | 9         | 0.17%   |
| BEHRINGER International          | 9         | 0.17%   |
| Realtek Semiconductor            | 8         | 0.15%   |
| ULi Electronics                  | 6         | 0.11%   |
| Sennheiser Communications        | 6         | 0.11%   |
| ASUSTek Computer                 | 6         | 0.11%   |
| SAVITECH                         | 4         | 0.07%   |
| Roland                           | 4         | 0.07%   |
| Micro Star International         | 4         | 0.07%   |
| Ensoniq                          | 4         | 0.07%   |
| DigiTech                         | 4         | 0.07%   |
| Corsair                          | 4         | 0.07%   |
| AKAI Professional M.I.           | 4         | 0.07%   |
| XMOS                             | 3         | 0.06%   |
| Xilinx                           | 3         | 0.06%   |
| Textech International            | 3         | 0.06%   |
| Tenx Technology                  | 3         | 0.06%   |
| TEAC                             | 3         | 0.06%   |
| Razer USA                        | 3         | 0.06%   |
| PreSonus Audio Electronics       | 3         | 0.06%   |
| Kingston Technology              | 3         | 0.06%   |
| Elite Silicon                    | 3         | 0.06%   |
| EGO SYStems                      | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 343       | 5.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 298       | 4.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 286       | 4.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 221       | 3.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 193       | 3.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 192       | 3.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 191       | 3.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 190       | 3.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 178       | 2.86%   |
| AMD FCH Azalia Controller                                                                         | 171       | 2.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 157       | 2.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 143       | 2.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 90        | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 85        | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 85        | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 84        | 1.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 83        | 1.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 82        | 1.32%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 80        | 1.28%   |
| Intel 8 Series HD Audio Controller                                                                | 80        | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 79        | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 75        | 1.2%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 74        | 1.19%   |
| Nvidia High Definition Audio Controller                                                           | 72        | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 69        | 1.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 61        | 0.98%   |
| Nvidia MCP61 High Definition Audio                                                                | 58        | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 54        | 0.87%   |
| Intel Broadwell-U Audio Controller                                                                | 53        | 0.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 52        | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 52        | 0.83%   |
| Intel 200 Series PCH HD Audio                                                                     | 52        | 0.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 52        | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 51        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 46        | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 44        | 0.71%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 42        | 0.67%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 41        | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 40        | 0.64%   |
| AMD Wrestler HDMI Audio                                                                           | 39        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 455       | 20.77%  |
| SK hynix                     | 367       | 16.75%  |
| Unknown                      | 341       | 15.56%  |
| Kingston                     | 252       | 11.5%   |
| Micron Technology            | 167       | 7.62%   |
| Crucial                      | 131       | 5.98%   |
| Corsair                      | 85        | 3.88%   |
| G.Skill                      | 60        | 2.74%   |
| Elpida                       | 47        | 2.15%   |
| Ramaxel Technology           | 39        | 1.78%   |
| Nanya Technology             | 34        | 1.55%   |
| Unknown (ABCD)               | 32        | 1.46%   |
| A-DATA Technology            | 31        | 1.41%   |
| Smart                        | 16        | 0.73%   |
| Transcend                    | 13        | 0.59%   |
| Team                         | 10        | 0.46%   |
| Goodram                      | 9         | 0.41%   |
| Patriot                      | 8         | 0.37%   |
| Unknown                      | 7         | 0.32%   |
| Qimonda                      | 5         | 0.23%   |
| Avant                        | 5         | 0.23%   |
| Apacer                       | 5         | 0.23%   |
| Unifosa                      | 4         | 0.18%   |
| 48spaces                     | 4         | 0.18%   |
| Timetec                      | 3         | 0.14%   |
| GeIL                         | 3         | 0.14%   |
| fef5                         | 3         | 0.14%   |
| V-Color                      | 2         | 0.09%   |
| Teikon                       | 2         | 0.09%   |
| Super Talent                 | 2         | 0.09%   |
| PNY                          | 2         | 0.09%   |
| Neo Forza                    | 2         | 0.09%   |
| High Bridge                  | 2         | 0.09%   |
| CSX                          | 2         | 0.09%   |
| ASint Technology             | 2         | 0.09%   |
| Walton Chaintech             | 1         | 0.05%   |
| V-GeN                        | 1         | 0.05%   |
| Unknown (AB)                 | 1         | 0.05%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.05%   |
| Unknown (0x7FA8000000000000) | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 26        | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.76%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 0.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 0.64%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s            | 15        | 0.64%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 0.59%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 13        | 0.55%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 12        | 0.51%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.51%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 11        | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.42%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 10        | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 10        | 0.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.42%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.42%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.38%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 9         | 0.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.38%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.38%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 9         | 0.38%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 8         | 0.34%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 8         | 0.34%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 8         | 0.34%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.34%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 7         | 0.3%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 7         | 0.3%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.3%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 7         | 0.3%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.3%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 7         | 0.3%    |
| Unknown                                                          | 7         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 750       | 39.1%   |
| DDR4    | 667       | 34.78%  |
| DDR2    | 191       | 9.96%   |
| SDRAM   | 91        | 4.74%   |
| LPDDR4  | 71        | 3.7%    |
| Unknown | 65        | 3.39%   |
| LPDDR3  | 36        | 1.88%   |
| DDR     | 24        | 1.25%   |
| DDR5    | 9         | 0.47%   |
| DRAM    | 8         | 0.42%   |
| LPDDR5  | 5         | 0.26%   |
| EEPROM  | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1097      | 58.26%  |
| DIMM         | 688       | 36.54%  |
| Row Of Chips | 71        | 3.77%   |
| Chip         | 13        | 0.69%   |
| Unknown      | 10        | 0.53%   |
| FB-DIMM      | 4         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 610       | 29.43%  |
| 8192    | 603       | 29.09%  |
| 2048    | 426       | 20.55%  |
| 16384   | 240       | 11.58%  |
| 1024    | 127       | 6.13%   |
| 32768   | 46        | 2.22%   |
| 512     | 15        | 0.72%   |
| 1536    | 2         | 0.1%    |
| 65536   | 1         | 0.05%   |
| 256     | 1         | 0.05%   |
| 1       | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 461       | 22.58%  |
| 2667    | 260       | 12.73%  |
| 3200    | 197       | 9.65%   |
| 1333    | 162       | 7.93%   |
| 2400    | 137       | 6.71%   |
| 667     | 100       | 4.9%    |
| 800     | 82        | 4.02%   |
| Unknown | 81        | 3.97%   |
| 2133    | 75        | 3.67%   |
| 1334    | 69        | 3.38%   |
| 3600    | 36        | 1.76%   |
| 1066    | 32        | 1.57%   |
| 1867    | 31        | 1.52%   |
| 1067    | 29        | 1.42%   |
| 1866    | 25        | 1.22%   |
| 4199    | 21        | 1.03%   |
| 3266    | 21        | 1.03%   |
| 1800    | 20        | 0.98%   |
| 533     | 20        | 0.98%   |
| 4267    | 15        | 0.73%   |
| 3000    | 15        | 0.73%   |
| 2048    | 15        | 0.73%   |
| 2666    | 13        | 0.64%   |
| 975     | 10        | 0.49%   |
| 4800    | 8         | 0.39%   |
| 400     | 8         | 0.39%   |
| 3800    | 6         | 0.29%   |
| 3733    | 5         | 0.24%   |
| 2733    | 5         | 0.24%   |
| 2000    | 5         | 0.24%   |
| 333     | 5         | 0.24%   |
| 49926   | 4         | 0.2%    |
| 6400    | 4         | 0.2%    |
| 4266    | 4         | 0.2%    |
| 3400    | 4         | 0.2%    |
| 2800    | 4         | 0.2%    |
| 2200    | 4         | 0.2%    |
| 3466    | 3         | 0.15%   |
| 2448    | 3         | 0.15%   |
| 1639    | 3         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 56        | 40.58%  |
| Brother Industries    | 27        | 19.57%  |
| Canon                 | 24        | 17.39%  |
| Samsung Electronics   | 11        | 7.97%   |
| Seiko Epson           | 5         | 3.62%   |
| Zebra                 | 4         | 2.9%    |
| QinHeng Electronics   | 2         | 1.45%   |
| Prolific Technology   | 2         | 1.45%   |
| Kyocera               | 2         | 1.45%   |
| STMicroelectronics    | 1         | 0.72%   |
| Pantum                | 1         | 0.72%   |
| Minolta               | 1         | 0.72%   |
| Lexmark International | 1         | 0.72%   |
| Dymo-CoStar           | 1         | 0.72%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet P1005                                                     | 4         | 2.88%   |
| HP LaserJet 400 M401a                                                 | 4         | 2.88%   |
| Zebra ZP 450 Printer                                                  | 3         | 2.16%   |
| HP ENVY 4520 series                                                   | 3         | 2.16%   |
| HP DeskJet 3700 series                                                | 3         | 2.16%   |
| Brother HL-5370DW series                                              | 3         | 2.16%   |
| Seiko Epson L360 Series                                               | 2         | 1.44%   |
| QinHeng CH340S                                                        | 2         | 1.44%   |
| Prolific PL2305 Parallel Port                                         | 2         | 1.44%   |
| HP OfficeJet Pro 7730 series                                          | 2         | 1.44%   |
| HP LaserJet P1006                                                     | 2         | 1.44%   |
| HP LaserJet 1320                                                      | 2         | 1.44%   |
| HP LaserJet 1020                                                      | 2         | 1.44%   |
| HP LaserJet 1018                                                      | 2         | 1.44%   |
| HP LaserJet 1015                                                      | 2         | 1.44%   |
| HP Deskjet 3050A                                                      | 2         | 1.44%   |
| Canon TS3100 series                                                   | 2         | 1.44%   |
| Canon PIXMA MX530 Series                                              | 2         | 1.44%   |
| Canon LBP6000                                                         | 2         | 1.44%   |
| Brother HL-L2320D series                                              | 2         | 1.44%   |
| Brother HL-5340 series                                                | 2         | 1.44%   |
| Brother HL-2270DW Laser Printer                                       | 2         | 1.44%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.72%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 0.72%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.72%   |
| Seiko Epson L396 Series                                               | 1         | 0.72%   |
| Seiko Epson ET-2720 Series                                            | 1         | 0.72%   |
| Samsung Xerox Phaser 3117 Laser Printer                               | 1         | 0.72%   |
| Samsung SF-760 Series                                                 | 1         | 0.72%   |
| Samsung SCX-4200 series                                               | 1         | 0.72%   |
| Samsung SCX-4100 Scanner                                              | 1         | 0.72%   |
| Samsung SCX-3400 Series                                               | 1         | 0.72%   |
| Samsung ML-2525W Series                                               | 1         | 0.72%   |
| Samsung ML-1865                                                       | 1         | 0.72%   |
| Samsung ML-1740 Printer                                               | 1         | 0.72%   |
| Samsung M2070 Series                                                  | 1         | 0.72%   |
| Samsung M2020 Series                                                  | 1         | 0.72%   |
| Samsung C48x Series Color Laser Multifunction Printer                 | 1         | 0.72%   |
| Pantum P2000                                                          | 1         | 0.72%   |
| Minolta PagePro 1300W                                                 | 1         | 0.72%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 28        | 71.79%  |
| Hewlett-Packard | 6         | 15.38%  |
| Seiko Epson     | 5         | 12.82%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                     | 5         | 12.82%  |
| Canon CanoScan LIDE 25                                      | 4         | 10.26%  |
| Canon CanoScan LiDE 100                                     | 4         | 10.26%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 3         | 7.69%   |
| Canon CanoScan N650U/N656U                                  | 2         | 5.13%   |
| Canon CanoScan LiDE 220                                     | 2         | 5.13%   |
| Canon CanoScan LiDE 210                                     | 2         | 5.13%   |
| Canon CanoScan LiDE 120                                     | 2         | 5.13%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 2.56%   |
| Seiko Epson GT-X770 [Perfection V500]                       | 1         | 2.56%   |
| Seiko Epson GT-9800F [Perfection 3200]                      | 1         | 2.56%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 2.56%   |
| Seiko Epson GT-7700U [Perfection 1240U]                     | 1         | 2.56%   |
| HP ScanJet 82x0C                                            | 1         | 2.56%   |
| HP ScanJet 7400c                                            | 1         | 2.56%   |
| HP ScanJet 5590                                             | 1         | 2.56%   |
| HP ScanJet 3570c                                            | 1         | 2.56%   |
| HP Scanjet 200                                              | 1         | 2.56%   |
| HP PSC 1200                                                 | 1         | 2.56%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1         | 2.56%   |
| Canon CanoScan LiDE 90                                      | 1         | 2.56%   |
| Canon CanoScan LiDE 200                                     | 1         | 2.56%   |
| Canon CanoScan 4400F                                        | 1         | 2.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 539       | 24.69%  |
| Microdia                               | 172       | 7.88%   |
| Realtek Semiconductor                  | 139       | 6.37%   |
| IMC Networks                           | 137       | 6.28%   |
| Suyin                                  | 121       | 5.54%   |
| Logitech                               | 115       | 5.27%   |
| Bison Electronics                      | 114       | 5.22%   |
| Sunplus Innovation Technology          | 104       | 4.76%   |
| Quanta                                 | 77        | 3.53%   |
| Cheng Uei Precision Industry (Foxlink) | 71        | 3.25%   |
| Apple                                  | 55        | 2.52%   |
| Silicon Motion                         | 48        | 2.2%    |
| Alcor Micro                            | 47        | 2.15%   |
| Syntek                                 | 45        | 2.06%   |
| Ricoh                                  | 42        | 1.92%   |
| Lite-On Technology                     | 36        | 1.65%   |
| Acer                                   | 28        | 1.28%   |
| Samsung Electronics                    | 26        | 1.19%   |
| Z-Star Microelectronics                | 24        | 1.1%    |
| Microsoft                              | 22        | 1.01%   |
| Luxvisions Innotech Limited            | 19        | 0.87%   |
| Lenovo                                 | 17        | 0.78%   |
| ALi                                    | 17        | 0.78%   |
| Primax Electronics                     | 10        | 0.46%   |
| Importek                               | 10        | 0.46%   |
| icSpring                               | 8         | 0.37%   |
| Generalplus Technology                 | 8         | 0.37%   |
| GEMBIRD                                | 8         | 0.37%   |
| OmniVision Technologies                | 7         | 0.32%   |
| MacroSilicon                           | 7         | 0.32%   |
| DigiTech                               | 7         | 0.32%   |
| KYE Systems (Mouse Systems)            | 6         | 0.27%   |
| Jieli Technology                       | 6         | 0.27%   |
| Cubeternet                             | 6         | 0.27%   |
| ARC International                      | 6         | 0.27%   |
| Sonix Technology                       | 5         | 0.23%   |
| Creative Technology                    | 5         | 0.23%   |
| Sunplus Technology                     | 4         | 0.18%   |
| USB Camera CS                          | 3         | 0.14%   |
| Trust                                  | 3         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 85        | 3.88%   |
| Microdia Integrated_Webcam_HD                    | 36        | 1.64%   |
| Realtek Integrated_Webcam_HD                     | 34        | 1.55%   |
| Chicony HD WebCam                                | 33        | 1.51%   |
| Chicony USB 2.0 Camera                           | 28        | 1.28%   |
| IMC Networks USB2.0 HD UVC WebCam                | 27        | 1.23%   |
| Logitech Webcam C270                             | 26        | 1.19%   |
| Sunplus Integrated_Webcam_HD                     | 25        | 1.14%   |
| Samsung Galaxy series, misc. (MTP mode)          | 25        | 1.14%   |
| Bison Integrated Camera                          | 24        | 1.1%    |
| IMC Networks Integrated Camera                   | 22        | 1%      |
| Logitech HD Pro Webcam C920                      | 21        | 0.96%   |
| Chicony TOSHIBA Web Camera - HD                  | 21        | 0.96%   |
| Microdia Sonix USB 2.0 Camera                    | 20        | 0.91%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 20        | 0.91%   |
| Apple Built-in iSight                            | 20        | 0.91%   |
| Chicony HP Truevision HD                         | 19        | 0.87%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 19        | 0.87%   |
| Alcor Micro USB 2.0 PC cam                       | 19        | 0.87%   |
| Chicony Lenovo EasyCamera                        | 18        | 0.82%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 18        | 0.82%   |
| Suyin HP TrueVision HD                           | 17        | 0.78%   |
| Microdia Integrated Webcam                       | 16        | 0.73%   |
| Bison HD Webcam                                  | 16        | 0.73%   |
| Syntek Integrated Camera                         | 15        | 0.68%   |
| Sunplus HD WebCam                                | 15        | 0.68%   |
| Lite-On Integrated Camera                        | 15        | 0.68%   |
| Chicony USB2.0 VGA UVC WebCam                    | 15        | 0.68%   |
| Suyin Acer CrystalEye Webcam                     | 14        | 0.64%   |
| Bison SunplusIT Integrated Camera                | 14        | 0.64%   |
| Quanta HP Webcam                                 | 13        | 0.59%   |
| Logitech C922 Pro Stream Webcam                  | 13        | 0.59%   |
| IMC Networks UVC VGA Webcam                      | 13        | 0.59%   |
| Chicony HP Truevision HD camera                  | 13        | 0.59%   |
| Chicony HP HD Camera                             | 13        | 0.59%   |
| Bison BisonCam, NB Pro                           | 13        | 0.59%   |
| Syntek Lenovo EasyCamera                         | 12        | 0.55%   |
| Realtek USB Camera                               | 12        | 0.55%   |
| Chicony USB2.0 Camera                            | 12        | 0.55%   |
| Quanta HP TrueVision HD Camera                   | 11        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 132       | 35.97%  |
| Synaptics                          | 68        | 18.53%  |
| AuthenTec                          | 55        | 14.99%  |
| Upek                               | 33        | 8.99%   |
| Shenzhen Goodix Technology         | 27        | 7.36%   |
| STMicroelectronics                 | 20        | 5.45%   |
| LighTuning Technology              | 14        | 3.81%   |
| Elan Microelectronics              | 11        | 3%      |
| Samsung Electronics                | 3         | 0.82%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.27%   |
| Gingytech                          | 1         | 0.27%   |
| Focal-systems.Corp                 | 1         | 0.27%   |
| DigitalPersona                     | 1         | 0.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 30        | 8.17%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 29        | 7.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 29        | 7.9%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 23        | 6.27%   |
| STMicroelectronics Fingerprint Reader                                      | 20        | 5.45%   |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 4.63%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 4.36%   |
| AuthenTec AES2810                                                          | 15        | 4.09%   |
| Validity Sensors Fingerprint scanner                                       | 13        | 3.54%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 3%      |
| Validity Sensors VFS491                                                    | 11        | 3%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 3%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 2.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 2.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 2.45%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 2.18%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 2.18%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 2.18%   |
| AuthenTec AES1600                                                          | 7         | 1.91%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.36%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.36%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.09%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.09%   |
| Synaptics UWP WBDI                                                         | 4         | 1.09%   |
| Synaptics  WBDI                                                            | 4         | 1.09%   |
| LighTuning Fingerprint Reader                                              | 4         | 1.09%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.09%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.09%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.82%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 0.82%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.82%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.54%   |
| Synaptics WBDI Device                                                      | 2         | 0.54%   |
| Synaptics WBDI                                                             | 2         | 0.54%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.54%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 0.54%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 0.54%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 72        | 34.62%  |
| Alcor Micro                       | 55        | 26.44%  |
| O2 Micro                          | 29        | 13.94%  |
| Upek                              | 17        | 8.17%   |
| Lenovo                            | 17        | 8.17%   |
| OmniKey                           | 3         | 1.44%   |
| Gemalto (was Gemplus)             | 3         | 1.44%   |
| Reiner SCT Kartensysteme          | 2         | 0.96%   |
| Yubico.com                        | 1         | 0.48%   |
| VASCO Data Security International | 1         | 0.48%   |
| In Focus Systems                  | 1         | 0.48%   |
| Fujitsu Siemens Computers         | 1         | 0.48%   |
| Clay Logic                        | 1         | 0.48%   |
| Chicony Electronics               | 1         | 0.48%   |
| Cherry                            | 1         | 0.48%   |
| C3PO                              | 1         | 0.48%   |
| Aktiv                             | 1         | 0.48%   |
| Advanced Card Systems             | 1         | 0.48%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 55        | 26.44%  |
| Broadcom BCM5880 Secure Applications Processor                               | 33        | 15.87%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 11.06%  |
| Broadcom 5880                                                                | 18        | 8.65%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 8.17%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 5.29%   |
| Broadcom 58200                                                               | 9         | 4.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 6         | 2.88%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.96%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.96%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.48%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.48%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.48%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 0.48%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.48%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.48%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.48%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.48%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.48%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.48%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.48%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.48%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.48%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.48%   |
| Aktiv Rutoken lite                                                           | 1         | 0.48%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.48%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3067      | 72.57%  |
| 1     | 894       | 21.15%  |
| 2     | 212       | 5.02%   |
| 3     | 35        | 0.83%   |
| 4     | 11        | 0.26%   |
| 5     | 4         | 0.09%   |
| 10    | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 365       | 25.7%   |
| Graphics card            | 351       | 24.72%  |
| Chipcard                 | 196       | 13.8%   |
| Net/wireless             | 146       | 10.28%  |
| Communication controller | 60        | 4.23%   |
| Modem                    | 47        | 3.31%   |
| Camera                   | 47        | 3.31%   |
| Multimedia controller    | 37        | 2.61%   |
| Unassigned class         | 28        | 1.97%   |
| Bluetooth                | 28        | 1.97%   |
| Storage                  | 25        | 1.76%   |
| Sound                    | 24        | 1.69%   |
| Card reader              | 22        | 1.55%   |
| Flash memory             | 16        | 1.13%   |
| Network                  | 10        | 0.7%    |
| Net/ethernet             | 8         | 0.56%   |
| Dvb card                 | 4         | 0.28%   |
| Storage/raid             | 2         | 0.14%   |
| Storage/ide              | 2         | 0.14%   |
| Video                    | 1         | 0.07%   |
| Firewire controller      | 1         | 0.07%   |

