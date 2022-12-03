Debian - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 5644

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T440p 20AN0079M... | [79261239c1](https://linux-hardware.org/?probe=79261239c1) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [674157de54](https://linux-hardware.org/?probe=674157de54) | Dec 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | [becc2328fd](https://linux-hardware.org/?probe=becc2328fd) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [73c388fb61](https://linux-hardware.org/?probe=73c388fb61) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [6d44ef56c9](https://linux-hardware.org/?probe=6d44ef56c9) | Dec 01, 2022 |
| HP            | Pavilion dv5                | [0fc7017b0c](https://linux-hardware.org/?probe=0fc7017b0c) | Nov 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [183243daeb](https://linux-hardware.org/?probe=183243daeb) | Nov 30, 2022 |
| Notebook      | RIM2520                     | [5f66abbb8b](https://linux-hardware.org/?probe=5f66abbb8b) | Nov 30, 2022 |
| HP            | Elite x2 1011 G1 Tablet     | [1a00258de3](https://linux-hardware.org/?probe=1a00258de3) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| Dell          | Latitude 7490               | [8934413cf0](https://linux-hardware.org/?probe=8934413cf0) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| Dell          | XPS 15 9500                 | [9c87ab493e](https://linux-hardware.org/?probe=9c87ab493e) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [1e52ea39e4](https://linux-hardware.org/?probe=1e52ea39e4) | Nov 28, 2022 |
| Lenovo        | ThinkPad X301 2776LEG       | [ebaea0c805](https://linux-hardware.org/?probe=ebaea0c805) | Nov 28, 2022 |
| Dell          | Precision M6400             | [05f69c6917](https://linux-hardware.org/?probe=05f69c6917) | Nov 28, 2022 |
| HP            | ProBook 450 G5              | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| ASUSTek       | GL752VW                     | [edc0678b85](https://linux-hardware.org/?probe=edc0678b85) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS03J00    | [8423f90db0](https://linux-hardware.org/?probe=8423f90db0) | Nov 27, 2022 |
| Lenovo        | ThinkPad T520 4243F53       | [8f9e96442a](https://linux-hardware.org/?probe=8f9e96442a) | Nov 27, 2022 |
| Tactus        | GeoBook 140                 | [e3f4d734da](https://linux-hardware.org/?probe=e3f4d734da) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| HP            | Compaq nx9110 (DU432EA#A... | [1b54092e14](https://linux-hardware.org/?probe=1b54092e14) | Nov 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [32bfa52fc1](https://linux-hardware.org/?probe=32bfa52fc1) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [3d1b8f282a](https://linux-hardware.org/?probe=3d1b8f282a) | Nov 27, 2022 |
| HP            | Laptop 15s-fq5xxx           | [f1ef96a2e6](https://linux-hardware.org/?probe=f1ef96a2e6) | Nov 26, 2022 |
| MSI           | Creator 15M A9SD            | [8b47bbf475](https://linux-hardware.org/?probe=8b47bbf475) | Nov 26, 2022 |
| HP            | Laptop 15-da3xxx            | [335fce26dd](https://linux-hardware.org/?probe=335fce26dd) | Nov 26, 2022 |
| HP            | 255 G7 Notebook PC          | [8c389cf5d6](https://linux-hardware.org/?probe=8c389cf5d6) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [2902b75068](https://linux-hardware.org/?probe=2902b75068) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [973662f8d5](https://linux-hardware.org/?probe=973662f8d5) | Nov 26, 2022 |
| Lenovo        | ThinkPad T495 20NJS0L100    | [1e9e7f34df](https://linux-hardware.org/?probe=1e9e7f34df) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bede773ce4](https://linux-hardware.org/?probe=bede773ce4) | Nov 26, 2022 |
| ASUSTek       | A6R                         | [68f38deab1](https://linux-hardware.org/?probe=68f38deab1) | Nov 26, 2022 |
| Dell          | Latitude E7240              | [634ebb2a88](https://linux-hardware.org/?probe=634ebb2a88) | Nov 25, 2022 |
| HP            | Pavilion TS Sleekbook 14    | [26440cddbb](https://linux-hardware.org/?probe=26440cddbb) | Nov 25, 2022 |
| MSI           | Creator 15M A9SD            | [a15ef33296](https://linux-hardware.org/?probe=a15ef33296) | Nov 25, 2022 |
| Lenovo        | ThinkPad E14 20RBS3LE00     | [83203a04f2](https://linux-hardware.org/?probe=83203a04f2) | Nov 25, 2022 |
| ASUSTek       | GL752VW                     | [2dfd7f3926](https://linux-hardware.org/?probe=2dfd7f3926) | Nov 25, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | [f82ee02c50](https://linux-hardware.org/?probe=f82ee02c50) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| HP            | 255 G7 Notebook PC          | [f5a6bcf0fb](https://linux-hardware.org/?probe=f5a6bcf0fb) | Nov 24, 2022 |
| ASUSTek       | X551CAP                     | [f40e3110d0](https://linux-hardware.org/?probe=f40e3110d0) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [8b4ad51670](https://linux-hardware.org/?probe=8b4ad51670) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [a5265c8a0e](https://linux-hardware.org/?probe=a5265c8a0e) | Nov 24, 2022 |
| Dell          | Latitude E6500              | [73d607f9e1](https://linux-hardware.org/?probe=73d607f9e1) | Nov 24, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [299634697d](https://linux-hardware.org/?probe=299634697d) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ef378a135b](https://linux-hardware.org/?probe=ef378a135b) | Nov 24, 2022 |
| Aquarius      | NS585                       | [d54530cbcb](https://linux-hardware.org/?probe=d54530cbcb) | Nov 24, 2022 |
| Aquarius      | NS585                       | [64d9bcbcde](https://linux-hardware.org/?probe=64d9bcbcde) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| MSI           | Modern 14 A10M              | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| Lenovo        | ThinkPad T495 20NK000UUS    | [0e8c0e6f07](https://linux-hardware.org/?probe=0e8c0e6f07) | Nov 23, 2022 |
| Lenovo        | ThinkPad T490 20N3S8T211    | [97ea649145](https://linux-hardware.org/?probe=97ea649145) | Nov 23, 2022 |
| HP            | ProBook 450 G7              | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| Dell          | Latitude E6530              | [71623eedf3](https://linux-hardware.org/?probe=71623eedf3) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| MPMAN         | CONVERTER 102               | [cab847edc0](https://linux-hardware.org/?probe=cab847edc0) | Nov 23, 2022 |
| HP            | Compaq 6720s                | [63a0e0161c](https://linux-hardware.org/?probe=63a0e0161c) | Nov 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [363e0b0149](https://linux-hardware.org/?probe=363e0b0149) | Nov 22, 2022 |
| Unknown       | Unknown                     | [1de34b67e2](https://linux-hardware.org/?probe=1de34b67e2) | Nov 22, 2022 |
| Dell          | Latitude 3420               | [30434de3e9](https://linux-hardware.org/?probe=30434de3e9) | Nov 22, 2022 |
| Unknown       | Wiren Board rev. 7.3.1 (... | [1f9ccab914](https://linux-hardware.org/?probe=1f9ccab914) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [71c464a407](https://linux-hardware.org/?probe=71c464a407) | Nov 22, 2022 |
| HP            | Pavilion Sleekbook 15       | [add4f71bc0](https://linux-hardware.org/?probe=add4f71bc0) | Nov 22, 2022 |
| HP            | ENVY 6                      | [feb348843e](https://linux-hardware.org/?probe=feb348843e) | Nov 22, 2022 |
| Lenovo        | Y520-15IKBA 80WY            | [c1cccb2b2a](https://linux-hardware.org/?probe=c1cccb2b2a) | Nov 22, 2022 |
| HP            | 255 G6 Notebook PC          | [149cee1720](https://linux-hardware.org/?probe=149cee1720) | Nov 22, 2022 |
| ASUSTek       | K53SD                       | [c127a0db71](https://linux-hardware.org/?probe=c127a0db71) | Nov 21, 2022 |
| Lenovo        | ThinkPad E14 20RAS04700     | [63d93d05db](https://linux-hardware.org/?probe=63d93d05db) | Nov 21, 2022 |
| MSI           | Creator 15M A9SD            | [e6d5440b09](https://linux-hardware.org/?probe=e6d5440b09) | Nov 21, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [b58bad1779](https://linux-hardware.org/?probe=b58bad1779) | Nov 21, 2022 |
| Dell          | Latitude 5310               | [9c19a3de68](https://linux-hardware.org/?probe=9c19a3de68) | Nov 21, 2022 |
| Micro Elec... | MG-VCTR002-2060             | [3ba115909e](https://linux-hardware.org/?probe=3ba115909e) | Nov 21, 2022 |
| HP            | Laptop 15-db0xxx            | [f634446cde](https://linux-hardware.org/?probe=f634446cde) | Nov 21, 2022 |
| Acer          | Popcorn                     | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [466592b744](https://linux-hardware.org/?probe=466592b744) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [3ca5ee2f7a](https://linux-hardware.org/?probe=3ca5ee2f7a) | Nov 20, 2022 |
| Chuwi         | LarkBook                    | [bef3087526](https://linux-hardware.org/?probe=bef3087526) | Nov 20, 2022 |
| MPMAN         | CONVERTER 102               | [845925720b](https://linux-hardware.org/?probe=845925720b) | Nov 20, 2022 |
| HP            | Laptop 15s-du3xxx           | [a90cea62ff](https://linux-hardware.org/?probe=a90cea62ff) | Nov 19, 2022 |
| Dell          | XPS 13 9380                 | [d42bddbd11](https://linux-hardware.org/?probe=d42bddbd11) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1af7bd26fd](https://linux-hardware.org/?probe=1af7bd26fd) | Nov 19, 2022 |
| Dell          | Inspiron 15-3567            | [5d6f9e57c5](https://linux-hardware.org/?probe=5d6f9e57c5) | Nov 19, 2022 |
| Tactus        | GeoBook 140                 | [127ec68044](https://linux-hardware.org/?probe=127ec68044) | Nov 19, 2022 |
| Aquarius      | NS585                       | [a0bc8d3f44](https://linux-hardware.org/?probe=a0bc8d3f44) | Nov 19, 2022 |
| Acer          | Aspire ES1-533              | [8c080caac2](https://linux-hardware.org/?probe=8c080caac2) | Nov 19, 2022 |
| Fujitsu       | FMVNQL7PM                   | [28ee68da79](https://linux-hardware.org/?probe=28ee68da79) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ad7abfb8cb](https://linux-hardware.org/?probe=ad7abfb8cb) | Nov 19, 2022 |
| Dell          | Latitude 7410               | [ce222880fe](https://linux-hardware.org/?probe=ce222880fe) | Nov 18, 2022 |
| Dynabook      | TECRA A50-J                 | [c0ae8746e0](https://linux-hardware.org/?probe=c0ae8746e0) | Nov 18, 2022 |
| HP            | 650                         | [43998a620b](https://linux-hardware.org/?probe=43998a620b) | Nov 18, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [0278a1f18d](https://linux-hardware.org/?probe=0278a1f18d) | Nov 18, 2022 |
| Apple         | MacBookAir7,2               | [f0fa194e20](https://linux-hardware.org/?probe=f0fa194e20) | Nov 18, 2022 |
| Google        | Terra                       | [9fcc3fb18a](https://linux-hardware.org/?probe=9fcc3fb18a) | Nov 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [3b33d1989a](https://linux-hardware.org/?probe=3b33d1989a) | Nov 18, 2022 |
| ASUSTek       | T100TA                      | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| Dell          | Latitude 5310               | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| Lenovo        | B475 Sabine                 | [5be5a7cd5f](https://linux-hardware.org/?probe=5be5a7cd5f) | Nov 17, 2022 |
| HP            | EliteBook 745 G5            | [9d7fefd253](https://linux-hardware.org/?probe=9d7fefd253) | Nov 17, 2022 |
| MSI           | Creator 15M A9SD            | [f1fdc384f9](https://linux-hardware.org/?probe=f1fdc384f9) | Nov 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [814b5d3d2e](https://linux-hardware.org/?probe=814b5d3d2e) | Nov 17, 2022 |
| HP            | Laptop 15-db0xxx            | [5aa50e7f6c](https://linux-hardware.org/?probe=5aa50e7f6c) | Nov 17, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | [523e8a1c6b](https://linux-hardware.org/?probe=523e8a1c6b) | Nov 17, 2022 |
| Dell          | Latitude 3320               | [fbaf8e5ab9](https://linux-hardware.org/?probe=fbaf8e5ab9) | Nov 16, 2022 |
| Dell          | Latitude 3320               | [377fbd3b41](https://linux-hardware.org/?probe=377fbd3b41) | Nov 16, 2022 |
| Dell          | Inspiron 13 5310            | [3c9865d86e](https://linux-hardware.org/?probe=3c9865d86e) | Nov 16, 2022 |
| HP            | Laptop 15-db0xxx            | [f6202bb6fa](https://linux-hardware.org/?probe=f6202bb6fa) | Nov 16, 2022 |
| MSI           | Prestige 14Evo A11M         | [78601d078c](https://linux-hardware.org/?probe=78601d078c) | Nov 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8fe0bcfe69](https://linux-hardware.org/?probe=8fe0bcfe69) | Nov 16, 2022 |
| Lenovo        | IdeaPad Z470                | [bc0980a6df](https://linux-hardware.org/?probe=bc0980a6df) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c38c6ddff6](https://linux-hardware.org/?probe=c38c6ddff6) | Nov 16, 2022 |
| Lenovo        | G470 20078                  | [55f47f2c19](https://linux-hardware.org/?probe=55f47f2c19) | Nov 16, 2022 |
| Unknown       | Unknown                     | [a86465b0f3](https://linux-hardware.org/?probe=a86465b0f3) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b5eb364ac6](https://linux-hardware.org/?probe=b5eb364ac6) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [f29e7d7659](https://linux-hardware.org/?probe=f29e7d7659) | Nov 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [2cc4a2cf6d](https://linux-hardware.org/?probe=2cc4a2cf6d) | Nov 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [867825d906](https://linux-hardware.org/?probe=867825d906) | Nov 15, 2022 |
| Dell          | Inspiron 5558               | [0674cb5916](https://linux-hardware.org/?probe=0674cb5916) | Nov 15, 2022 |
| GPU Compan... | GWTN116-3                   | [f8d8191f69](https://linux-hardware.org/?probe=f8d8191f69) | Nov 15, 2022 |
| ASUSTek       | X550VX                      | [8e55592803](https://linux-hardware.org/?probe=8e55592803) | Nov 15, 2022 |
| Dell          | G7 7700                     | [2440bebe2c](https://linux-hardware.org/?probe=2440bebe2c) | Nov 15, 2022 |
| IBM           | ThinkPad X31 2672JBU        | [ea0c82f4eb](https://linux-hardware.org/?probe=ea0c82f4eb) | Nov 15, 2022 |
| HP            | EliteBook 820 G3            | [fe84036164](https://linux-hardware.org/?probe=fe84036164) | Nov 15, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [862e9a2c25](https://linux-hardware.org/?probe=862e9a2c25) | Nov 15, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [a94cf56482](https://linux-hardware.org/?probe=a94cf56482) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| Acer          | Aspire A315-23G             | [16e5672a66](https://linux-hardware.org/?probe=16e5672a66) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [100714ed23](https://linux-hardware.org/?probe=100714ed23) | Nov 14, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [8267ec6686](https://linux-hardware.org/?probe=8267ec6686) | Nov 14, 2022 |
| Lenovo        | V14-ADA 82C6                | [7971c5cda7](https://linux-hardware.org/?probe=7971c5cda7) | Nov 14, 2022 |
| Toshiba       | Satellite P50-B-10Q         | [f28064cdad](https://linux-hardware.org/?probe=f28064cdad) | Nov 14, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [233791ab06](https://linux-hardware.org/?probe=233791ab06) | Nov 14, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [c6e254c4ed](https://linux-hardware.org/?probe=c6e254c4ed) | Nov 14, 2022 |
| HP            | 530 Notebook PC(KD092AA#... | [b6c682238c](https://linux-hardware.org/?probe=b6c682238c) | Nov 13, 2022 |
| Chuwi         | LarkBook                    | [8c33c61e14](https://linux-hardware.org/?probe=8c33c61e14) | Nov 13, 2022 |
| HP            | Laptop 15s-eq2xxx           | [36df61fb32](https://linux-hardware.org/?probe=36df61fb32) | Nov 13, 2022 |
| Unknown       | Unknown                     | [344e5842d1](https://linux-hardware.org/?probe=344e5842d1) | Nov 13, 2022 |
| Dell          | Inspiron 3521               | [c644f80930](https://linux-hardware.org/?probe=c644f80930) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [ff0881b6e4](https://linux-hardware.org/?probe=ff0881b6e4) | Nov 13, 2022 |
| HP            | 250 G8 Notebook PC          | [7e9c7562d6](https://linux-hardware.org/?probe=7e9c7562d6) | Nov 13, 2022 |
| HP            | EliteBook 8460p             | [8cb389e68e](https://linux-hardware.org/?probe=8cb389e68e) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1067cba3cc](https://linux-hardware.org/?probe=1067cba3cc) | Nov 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6677ca6be8](https://linux-hardware.org/?probe=6677ca6be8) | Nov 12, 2022 |
| GPU Compan... | GWTC116-2                   | [978facebde](https://linux-hardware.org/?probe=978facebde) | Nov 12, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [904b7c0e89](https://linux-hardware.org/?probe=904b7c0e89) | Nov 12, 2022 |
| HP            | Notebook                    | [2419e7d149](https://linux-hardware.org/?probe=2419e7d149) | Nov 12, 2022 |
| HP            | Notebook                    | [97c6c3c412](https://linux-hardware.org/?probe=97c6c3c412) | Nov 12, 2022 |
| GPU Compan... | GWTC116-2                   | [9e0c2df66d](https://linux-hardware.org/?probe=9e0c2df66d) | Nov 12, 2022 |
| IBM           | ThinkPad X31 2672JBU        | [9f627ba3f8](https://linux-hardware.org/?probe=9f627ba3f8) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [59aa7d31d8](https://linux-hardware.org/?probe=59aa7d31d8) | Nov 11, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [22ab694d81](https://linux-hardware.org/?probe=22ab694d81) | Nov 11, 2022 |
| Lenovo        | ThinkPad W700 275236U       | [c79bbe36c5](https://linux-hardware.org/?probe=c79bbe36c5) | Nov 11, 2022 |
| NCA Group     | iRU_Notebook                | [6d22b3942e](https://linux-hardware.org/?probe=6d22b3942e) | Nov 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [1681f97433](https://linux-hardware.org/?probe=1681f97433) | Nov 11, 2022 |
| HP            | Spectre x2 Detachable       | [0c480bd74d](https://linux-hardware.org/?probe=0c480bd74d) | Nov 11, 2022 |
| ASUSTek       | K50IE                       | [4bd91fccfa](https://linux-hardware.org/?probe=4bd91fccfa) | Nov 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [139c944b07](https://linux-hardware.org/?probe=139c944b07) | Nov 11, 2022 |
| Positivo B... | VJFE53F11X-XXXXXX           | [7e81c7cf85](https://linux-hardware.org/?probe=7e81c7cf85) | Nov 10, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [ae40e6e5b3](https://linux-hardware.org/?probe=ae40e6e5b3) | Nov 10, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f8cd836199](https://linux-hardware.org/?probe=f8cd836199) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [8bb3389cc1](https://linux-hardware.org/?probe=8bb3389cc1) | Nov 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [24c5edc9f9](https://linux-hardware.org/?probe=24c5edc9f9) | Nov 10, 2022 |
| Lenovo        | G50-30 80G0                 | [1e0c308a85](https://linux-hardware.org/?probe=1e0c308a85) | Nov 10, 2022 |
| ASUSTek       | X550VXK                     | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| ASUSTek       | K50IE                       | [5176f404f1](https://linux-hardware.org/?probe=5176f404f1) | Nov 10, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [9a69ea4724](https://linux-hardware.org/?probe=9a69ea4724) | Nov 10, 2022 |
| Dell          | Latitude E6530              | [f71e1a930c](https://linux-hardware.org/?probe=f71e1a930c) | Nov 10, 2022 |
| HP            | Pavilion g7                 | [ae04263783](https://linux-hardware.org/?probe=ae04263783) | Nov 09, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9d27997bce](https://linux-hardware.org/?probe=9d27997bce) | Nov 09, 2022 |
| ASUSTek       | UX31A                       | [e9bc780ce8](https://linux-hardware.org/?probe=e9bc780ce8) | Nov 09, 2022 |
| Gigabyte      | Sabre 15                    | [1edede0895](https://linux-hardware.org/?probe=1edede0895) | Nov 09, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [098d4ab9ec](https://linux-hardware.org/?probe=098d4ab9ec) | Nov 09, 2022 |
| Lenovo        | ThinkPad T420 4180PEM       | [ad4d7f338d](https://linux-hardware.org/?probe=ad4d7f338d) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [52080bf6ef](https://linux-hardware.org/?probe=52080bf6ef) | Nov 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [6b1f5f2c2a](https://linux-hardware.org/?probe=6b1f5f2c2a) | Nov 08, 2022 |
| HP            | Pavilion g7                 | [47c2e96181](https://linux-hardware.org/?probe=47c2e96181) | Nov 08, 2022 |
| Aquarius      | NS585                       | [9b20fcc4b8](https://linux-hardware.org/?probe=9b20fcc4b8) | Nov 08, 2022 |
| Razer         | Blade 15 Advanced Model ... | [0596fa3f71](https://linux-hardware.org/?probe=0596fa3f71) | Nov 08, 2022 |
| Dell          | Latitude E7470              | [3938dbeadd](https://linux-hardware.org/?probe=3938dbeadd) | Nov 08, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [da41b87b7c](https://linux-hardware.org/?probe=da41b87b7c) | Nov 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [f3c625be2d](https://linux-hardware.org/?probe=f3c625be2d) | Nov 07, 2022 |
| Unknown       | Unknown                     | [6af513692f](https://linux-hardware.org/?probe=6af513692f) | Nov 07, 2022 |
| Unknown       | Unknown                     | [b4859caaba](https://linux-hardware.org/?probe=b4859caaba) | Nov 07, 2022 |
| Lenovo        | G50-70 20351                | [0d4536a010](https://linux-hardware.org/?probe=0d4536a010) | Nov 07, 2022 |
| Lenovo        | ThinkPad W700 275236U       | [d3580b26c6](https://linux-hardware.org/?probe=d3580b26c6) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | [32b59c7a7d](https://linux-hardware.org/?probe=32b59c7a7d) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | [f0c8aff40f](https://linux-hardware.org/?probe=f0c8aff40f) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [9593951427](https://linux-hardware.org/?probe=9593951427) | Nov 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [e872e8551e](https://linux-hardware.org/?probe=e872e8551e) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [53eedbde1f](https://linux-hardware.org/?probe=53eedbde1f) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [55d115647e](https://linux-hardware.org/?probe=55d115647e) | Nov 06, 2022 |
| ASUSTek       | GL752VW                     | [cc373f85e7](https://linux-hardware.org/?probe=cc373f85e7) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3ec96d66bb](https://linux-hardware.org/?probe=3ec96d66bb) | Nov 05, 2022 |
| Acer          | Aspire 5741G                | [10c1cb72e2](https://linux-hardware.org/?probe=10c1cb72e2) | Nov 05, 2022 |
| Acer          | Aspire V3-572G              | [77f939bab4](https://linux-hardware.org/?probe=77f939bab4) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [2d165dd7b0](https://linux-hardware.org/?probe=2d165dd7b0) | Nov 05, 2022 |
| Lenovo        | ThinkPad L380 20M50013MH    | [80ac51627a](https://linux-hardware.org/?probe=80ac51627a) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [b89c7882f3](https://linux-hardware.org/?probe=b89c7882f3) | Nov 05, 2022 |
| Dell          | Inspiron 7570               | [158f7b0bcd](https://linux-hardware.org/?probe=158f7b0bcd) | Nov 05, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [605e06c6ad](https://linux-hardware.org/?probe=605e06c6ad) | Nov 04, 2022 |
| ASUSTek       | K53SD                       | [809577d2bb](https://linux-hardware.org/?probe=809577d2bb) | Nov 04, 2022 |
| Google        | Terra                       | [90518f31df](https://linux-hardware.org/?probe=90518f31df) | Nov 04, 2022 |
| Google        | Terra                       | [46ffa8092b](https://linux-hardware.org/?probe=46ffa8092b) | Nov 04, 2022 |
| Google        | Terra                       | [fc3f4b0ba5](https://linux-hardware.org/?probe=fc3f4b0ba5) | Nov 04, 2022 |
| Google        | Terra                       | [41017e02e4](https://linux-hardware.org/?probe=41017e02e4) | Nov 04, 2022 |
| Google        | Terra                       | [7429a311e4](https://linux-hardware.org/?probe=7429a311e4) | Nov 04, 2022 |
| SK hynix      | HyBook                      | [e758cde5ed](https://linux-hardware.org/?probe=e758cde5ed) | Nov 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [f0be03da28](https://linux-hardware.org/?probe=f0be03da28) | Nov 04, 2022 |
| Juana Mans... | SF20GM7                     | [8e8c4f52f4](https://linux-hardware.org/?probe=8e8c4f52f4) | Nov 04, 2022 |
| HP            | ProBook 6450b               | [7e595214cb](https://linux-hardware.org/?probe=7e595214cb) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | [a1cef4e43d](https://linux-hardware.org/?probe=a1cef4e43d) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | [b58a40d876](https://linux-hardware.org/?probe=b58a40d876) | Nov 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [391881cdd5](https://linux-hardware.org/?probe=391881cdd5) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [67e9f8d2f4](https://linux-hardware.org/?probe=67e9f8d2f4) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [ecf54fa708](https://linux-hardware.org/?probe=ecf54fa708) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8681693f03](https://linux-hardware.org/?probe=8681693f03) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | [d4d0f735d4](https://linux-hardware.org/?probe=d4d0f735d4) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | [04e15fb2d7](https://linux-hardware.org/?probe=04e15fb2d7) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [c80c7a9048](https://linux-hardware.org/?probe=c80c7a9048) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [455bdc6c45](https://linux-hardware.org/?probe=455bdc6c45) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [e507b9a974](https://linux-hardware.org/?probe=e507b9a974) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [7a5f1eaf6c](https://linux-hardware.org/?probe=7a5f1eaf6c) | Nov 03, 2022 |
| SAGER         | D900F                       | [7e0d0de36a](https://linux-hardware.org/?probe=7e0d0de36a) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [cecc0cca9d](https://linux-hardware.org/?probe=cecc0cca9d) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [464cc2acc3](https://linux-hardware.org/?probe=464cc2acc3) | Nov 03, 2022 |
| Lenovo        | ThinkPad T430 23501B6       | [f059837f31](https://linux-hardware.org/?probe=f059837f31) | Nov 03, 2022 |
| Dell          | Latitude 5420               | [717e0e6d40](https://linux-hardware.org/?probe=717e0e6d40) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [d59bd1e8f1](https://linux-hardware.org/?probe=d59bd1e8f1) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [4342ecb0f9](https://linux-hardware.org/?probe=4342ecb0f9) | Nov 02, 2022 |
| Google        | Terra                       | [46299bf228](https://linux-hardware.org/?probe=46299bf228) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [fd32769391](https://linux-hardware.org/?probe=fd32769391) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [d3c1c92563](https://linux-hardware.org/?probe=d3c1c92563) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [0ffaee423b](https://linux-hardware.org/?probe=0ffaee423b) | Nov 02, 2022 |
| ASUSTek       | 1005HA                      | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | G42                         | [18c487d99d](https://linux-hardware.org/?probe=18c487d99d) | Nov 02, 2022 |
| Digma         | EVE 11 C422 ES1068EW        | [f5177de131](https://linux-hardware.org/?probe=f5177de131) | Nov 02, 2022 |
| Toshiba       | Satellite L755              | [dc3d60731e](https://linux-hardware.org/?probe=dc3d60731e) | Nov 01, 2022 |
| Acer          | Aspire one                  | [bfb9f97d74](https://linux-hardware.org/?probe=bfb9f97d74) | Oct 31, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c9e0b81f80](https://linux-hardware.org/?probe=c9e0b81f80) | Oct 31, 2022 |
| HP            | Compaq nc6320 (EV073AV)     | [b73f359ded](https://linux-hardware.org/?probe=b73f359ded) | Oct 31, 2022 |
| ASUSTek       | G75VW                       | [6f1d41a85c](https://linux-hardware.org/?probe=6f1d41a85c) | Oct 31, 2022 |
| Acer          | Aspire one                  | [82b34552f6](https://linux-hardware.org/?probe=82b34552f6) | Oct 31, 2022 |
| MSI           | Pulse GL76 12UEK            | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| ASUSTek       | ZenBook UX431FAC_UX431FA    | [95554a578b](https://linux-hardware.org/?probe=95554a578b) | Oct 31, 2022 |
| Aquarius      | NS585                       | [e4b4e0456d](https://linux-hardware.org/?probe=e4b4e0456d) | Oct 31, 2022 |
| Apple         | MacBookPro5,5               | [00e1f1f754](https://linux-hardware.org/?probe=00e1f1f754) | Oct 31, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a872c9888a](https://linux-hardware.org/?probe=a872c9888a) | Oct 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [45f670d99f](https://linux-hardware.org/?probe=45f670d99f) | Oct 30, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [209fa66bb9](https://linux-hardware.org/?probe=209fa66bb9) | Oct 30, 2022 |
| Acer          | Aspire A515-51G             | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| HP            | x2 210                      | [8ed0a97ee9](https://linux-hardware.org/?probe=8ed0a97ee9) | Oct 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [e8a1f8f6bf](https://linux-hardware.org/?probe=e8a1f8f6bf) | Oct 30, 2022 |
| Dell          | XPS L322X                   | [cacebfe41e](https://linux-hardware.org/?probe=cacebfe41e) | Oct 30, 2022 |
| ASUSTek       | N751JK                      | [eea92055f3](https://linux-hardware.org/?probe=eea92055f3) | Oct 30, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [89595b2fa9](https://linux-hardware.org/?probe=89595b2fa9) | Oct 30, 2022 |
| Chuwi         | LarkBook                    | [3ff2ff69ce](https://linux-hardware.org/?probe=3ff2ff69ce) | Oct 30, 2022 |
| Dell          | Latitude 5501               | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| Notebook      | W230SD                      | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Dell          | Precision 7520              | [f54f6d6354](https://linux-hardware.org/?probe=f54f6d6354) | Oct 29, 2022 |
| Dell          | Latitude 5590               | [c7fa986fbd](https://linux-hardware.org/?probe=c7fa986fbd) | Oct 29, 2022 |
| ASUSTek       | X75VC                       | [9c1ab509ec](https://linux-hardware.org/?probe=9c1ab509ec) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [8cc0e0d828](https://linux-hardware.org/?probe=8cc0e0d828) | Oct 29, 2022 |
| Dell          | Latitude E4310              | [fe6c65dd77](https://linux-hardware.org/?probe=fe6c65dd77) | Oct 29, 2022 |
| Insyde        | Braswell                    | [d98b2d9661](https://linux-hardware.org/?probe=d98b2d9661) | Oct 29, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | [4acb2d0863](https://linux-hardware.org/?probe=4acb2d0863) | Oct 29, 2022 |
| Dell          | Latitude E4310              | [7a610ca46d](https://linux-hardware.org/?probe=7a610ca46d) | Oct 29, 2022 |
| Dell          | XPS 17 9720                 | [270b988521](https://linux-hardware.org/?probe=270b988521) | Oct 29, 2022 |
| Dell          | Precision 7520              | [30f6ad7a26](https://linux-hardware.org/?probe=30f6ad7a26) | Oct 29, 2022 |
| Dell          | Precision 7520              | [b81923dbd2](https://linux-hardware.org/?probe=b81923dbd2) | Oct 29, 2022 |
| MSI           | Modern 15 A10RBS            | [ddc3eded89](https://linux-hardware.org/?probe=ddc3eded89) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [60d1db050b](https://linux-hardware.org/?probe=60d1db050b) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [2a9f06c2b4](https://linux-hardware.org/?probe=2a9f06c2b4) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [787904d265](https://linux-hardware.org/?probe=787904d265) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [0971db18ed](https://linux-hardware.org/?probe=0971db18ed) | Oct 28, 2022 |
| Toshiba       | Satellite L755              | [0fa70f29d4](https://linux-hardware.org/?probe=0fa70f29d4) | Oct 28, 2022 |
| Lenovo        | ThinkPad T530 239242U       | [dbf70338e9](https://linux-hardware.org/?probe=dbf70338e9) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| Dell          | Latitude 5280               | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Dell          | XPS 17 9700                 | [81121b7762](https://linux-hardware.org/?probe=81121b7762) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | [0696abd43c](https://linux-hardware.org/?probe=0696abd43c) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | [d42867d201](https://linux-hardware.org/?probe=d42867d201) | Oct 28, 2022 |
| ASUSTek       | X555QG                      | [bace747804](https://linux-hardware.org/?probe=bace747804) | Oct 28, 2022 |
| Acer          | Aspire A715-75G             | [78b0c55e62](https://linux-hardware.org/?probe=78b0c55e62) | Oct 28, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [02c6d1fe1a](https://linux-hardware.org/?probe=02c6d1fe1a) | Oct 28, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | [768c6c8357](https://linux-hardware.org/?probe=768c6c8357) | Oct 28, 2022 |
| SANTECH       | NHx0DB,DE                   | [db8c0489f4](https://linux-hardware.org/?probe=db8c0489f4) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [63565608d1](https://linux-hardware.org/?probe=63565608d1) | Oct 28, 2022 |
| Google        | Boten                       | [2ed6baabf0](https://linux-hardware.org/?probe=2ed6baabf0) | Oct 27, 2022 |
| ASUSTek       | N501VW                      | [07f7d43f09](https://linux-hardware.org/?probe=07f7d43f09) | Oct 27, 2022 |
| HP            | ZBook 15 G3                 | [2b886c255e](https://linux-hardware.org/?probe=2b886c255e) | Oct 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [24da197a3a](https://linux-hardware.org/?probe=24da197a3a) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [3ab1fbc8e8](https://linux-hardware.org/?probe=3ab1fbc8e8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [faafe16cfb](https://linux-hardware.org/?probe=faafe16cfb) | Oct 27, 2022 |
| Acer          | Aspire A515-45              | [3a09f9ee6b](https://linux-hardware.org/?probe=3a09f9ee6b) | Oct 27, 2022 |
| THTF          | CR F860-T1                  | [0e20f4f61a](https://linux-hardware.org/?probe=0e20f4f61a) | Oct 27, 2022 |
| Acer          | Aspire ES1-131              | [f0edf4897a](https://linux-hardware.org/?probe=f0edf4897a) | Oct 26, 2022 |
| ASUSTek       | X541UAK                     | [87ee863ba2](https://linux-hardware.org/?probe=87ee863ba2) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [bfd570bbef](https://linux-hardware.org/?probe=bfd570bbef) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [58820ca517](https://linux-hardware.org/?probe=58820ca517) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [6b9a3ab27e](https://linux-hardware.org/?probe=6b9a3ab27e) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [a5bd8bebc7](https://linux-hardware.org/?probe=a5bd8bebc7) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [bce3a8b1b3](https://linux-hardware.org/?probe=bce3a8b1b3) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [65a1d5242f](https://linux-hardware.org/?probe=65a1d5242f) | Oct 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| ASUSTek       | 1005HA                      | [118fed891f](https://linux-hardware.org/?probe=118fed891f) | Oct 26, 2022 |
| HP            | Pavilion g6                 | [353259fad4](https://linux-hardware.org/?probe=353259fad4) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [93b8dd8c3e](https://linux-hardware.org/?probe=93b8dd8c3e) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [5e08852d18](https://linux-hardware.org/?probe=5e08852d18) | Oct 25, 2022 |
| Lenovo        | Z50-70 20354                | [08b673e57b](https://linux-hardware.org/?probe=08b673e57b) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [438afb4185](https://linux-hardware.org/?probe=438afb4185) | Oct 25, 2022 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [0c13fbf129](https://linux-hardware.org/?probe=0c13fbf129) | Oct 25, 2022 |
| Toshiba       | dynabook MX/33KBL           | [7ee9057da2](https://linux-hardware.org/?probe=7ee9057da2) | Oct 25, 2022 |
| Dell          | Vostro 5490                 | [6b4c7d3c8b](https://linux-hardware.org/?probe=6b4c7d3c8b) | Oct 24, 2022 |
| Dell          | Latitude E6430              | [3fbd9c277d](https://linux-hardware.org/?probe=3fbd9c277d) | Oct 24, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [eae727e6a0](https://linux-hardware.org/?probe=eae727e6a0) | Oct 24, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [52701ec9f4](https://linux-hardware.org/?probe=52701ec9f4) | Oct 24, 2022 |
| Packard Be... | DOT S                       | [f280a6ccbc](https://linux-hardware.org/?probe=f280a6ccbc) | Oct 24, 2022 |
| Lenovo        | ThinkPad T470 20HES4VB00    | [f7b39d371a](https://linux-hardware.org/?probe=f7b39d371a) | Oct 24, 2022 |
| Packard Be... | H17HV                       | [2e94cfdd84](https://linux-hardware.org/?probe=2e94cfdd84) | Oct 24, 2022 |
| Alienware     | M11xR3                      | [62bf8b7b02](https://linux-hardware.org/?probe=62bf8b7b02) | Oct 24, 2022 |
| HP            | Pavilion g4                 | [3b6666b5ba](https://linux-hardware.org/?probe=3b6666b5ba) | Oct 24, 2022 |
| Lenovo        | V310-14IKB 80T2             | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| Dell          | Precision 7750              | [dd51bb7ccd](https://linux-hardware.org/?probe=dd51bb7ccd) | Oct 23, 2022 |
| HP            | Pavilion g4                 | [487a972bda](https://linux-hardware.org/?probe=487a972bda) | Oct 23, 2022 |
| Panasonic     | CF-LX3J-50M3                | [949acb4c3a](https://linux-hardware.org/?probe=949acb4c3a) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | [6437fb22e1](https://linux-hardware.org/?probe=6437fb22e1) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | [a19b5987c6](https://linux-hardware.org/?probe=a19b5987c6) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [88af6c857c](https://linux-hardware.org/?probe=88af6c857c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [246517ceab](https://linux-hardware.org/?probe=246517ceab) | Oct 22, 2022 |
| ASUSTek       | X756UQK                     | [2570a4e51f](https://linux-hardware.org/?probe=2570a4e51f) | Oct 22, 2022 |
| Toshiba       | Satellite P50-B-103         | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [45d7e6a1aa](https://linux-hardware.org/?probe=45d7e6a1aa) | Oct 21, 2022 |
| Apple         | MacBook5,2                  | [165ce75570](https://linux-hardware.org/?probe=165ce75570) | Oct 21, 2022 |
| MSI           | Prestige 14Evo A11M         | [c63a7ccdeb](https://linux-hardware.org/?probe=c63a7ccdeb) | Oct 21, 2022 |
| Acer          | Swift SF314-42              | [2449f6a1b7](https://linux-hardware.org/?probe=2449f6a1b7) | Oct 21, 2022 |
| Aquarius      | NS585                       | [c953c5090c](https://linux-hardware.org/?probe=c953c5090c) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1dc7719a4d](https://linux-hardware.org/?probe=1dc7719a4d) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7acb5493d7](https://linux-hardware.org/?probe=7acb5493d7) | Oct 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b13dc58884](https://linux-hardware.org/?probe=b13dc58884) | Oct 20, 2022 |
| ASUSTek       | G75VW                       | [194959e65e](https://linux-hardware.org/?probe=194959e65e) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [914bab2302](https://linux-hardware.org/?probe=914bab2302) | Oct 20, 2022 |
| HP            | EliteBook 745 G3            | [3bfbc8dcac](https://linux-hardware.org/?probe=3bfbc8dcac) | Oct 20, 2022 |
| HP            | Laptop 15-ef2xxx            | [823d998220](https://linux-hardware.org/?probe=823d998220) | Oct 20, 2022 |
| HP            | EliteBook 840 Aero G8 No... | [80738ede80](https://linux-hardware.org/?probe=80738ede80) | Oct 20, 2022 |
| Apple         | MacBook5,2                  | [1e76467975](https://linux-hardware.org/?probe=1e76467975) | Oct 20, 2022 |
| Aquarius      | NS585                       | [a134ed693c](https://linux-hardware.org/?probe=a134ed693c) | Oct 20, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [162e7a20b2](https://linux-hardware.org/?probe=162e7a20b2) | Oct 20, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| HP            | 245 G7                      | [9ec088c343](https://linux-hardware.org/?probe=9ec088c343) | Oct 19, 2022 |
| ASUSTek       | X541NA                      | [5b61fd3a38](https://linux-hardware.org/?probe=5b61fd3a38) | Oct 19, 2022 |
| Dell          | Inspiron 7590               | [43ec5b2df8](https://linux-hardware.org/?probe=43ec5b2df8) | Oct 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [67ebd92594](https://linux-hardware.org/?probe=67ebd92594) | Oct 19, 2022 |
| Acer          | Aspire A315-23G             | [93584b3b67](https://linux-hardware.org/?probe=93584b3b67) | Oct 19, 2022 |
| Fujitsu       | LIFEBOOK E753               | [1fbb05ae6b](https://linux-hardware.org/?probe=1fbb05ae6b) | Oct 18, 2022 |
| HP            | EliteBook 745 G3            | [e800d683ef](https://linux-hardware.org/?probe=e800d683ef) | Oct 18, 2022 |
| ASUSTek       | G75VW                       | [5ee12be257](https://linux-hardware.org/?probe=5ee12be257) | Oct 18, 2022 |
| UNOWHY        | Y13G010S4EI                 | [f7f13866aa](https://linux-hardware.org/?probe=f7f13866aa) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | [aff8f19a59](https://linux-hardware.org/?probe=aff8f19a59) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | [c33d20c223](https://linux-hardware.org/?probe=c33d20c223) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IAH7 82S... | [dfa3140411](https://linux-hardware.org/?probe=dfa3140411) | Oct 17, 2022 |
| Dell          | XPS 17 9700                 | [5368bd3ad6](https://linux-hardware.org/?probe=5368bd3ad6) | Oct 17, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e076f9208c](https://linux-hardware.org/?probe=e076f9208c) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | [10bcc184e7](https://linux-hardware.org/?probe=10bcc184e7) | Oct 17, 2022 |
| SLIMBOOK      | TITAN                       | [87177b2371](https://linux-hardware.org/?probe=87177b2371) | Oct 17, 2022 |
| ASUSTek       | UX21A                       | [1d7d76b463](https://linux-hardware.org/?probe=1d7d76b463) | Oct 16, 2022 |
| ASUSTek       | G75VW                       | [a88a291921](https://linux-hardware.org/?probe=a88a291921) | Oct 16, 2022 |
| Lenovo        | Legion Y545 81Q6            | [b6162e2c5e](https://linux-hardware.org/?probe=b6162e2c5e) | Oct 16, 2022 |
| Dell          | Inspiron 1545               | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| Dell          | Latitude 3320               | [300f16471f](https://linux-hardware.org/?probe=300f16471f) | Oct 16, 2022 |
| Dell          | Latitude 3320               | [e4645890b8](https://linux-hardware.org/?probe=e4645890b8) | Oct 16, 2022 |
| Dell          | Inspiron N5110              | [ae7d737ee5](https://linux-hardware.org/?probe=ae7d737ee5) | Oct 16, 2022 |
| Dell          | Inspiron N5110              | [5cbc449f36](https://linux-hardware.org/?probe=5cbc449f36) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | [fb37bc6617](https://linux-hardware.org/?probe=fb37bc6617) | Oct 15, 2022 |
| HP            | EliteBook Folio 1040 G1     | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Panasonic     | CF-LX3J-50M3                | [95386977de](https://linux-hardware.org/?probe=95386977de) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [766f4b2d1f](https://linux-hardware.org/?probe=766f4b2d1f) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [bf46cd0c9e](https://linux-hardware.org/?probe=bf46cd0c9e) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [8cf96a6d0b](https://linux-hardware.org/?probe=8cf96a6d0b) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [a68e7df338](https://linux-hardware.org/?probe=a68e7df338) | Oct 14, 2022 |
| Dell          | Latitude E6330              | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| Dell          | Inspiron 5502               | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| MSI           | MS-N014                     | [87e6e540be](https://linux-hardware.org/?probe=87e6e540be) | Oct 14, 2022 |
| Google        | Robo                        | [d070697e72](https://linux-hardware.org/?probe=d070697e72) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [a1b02901a1](https://linux-hardware.org/?probe=a1b02901a1) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [a0f4cd454d](https://linux-hardware.org/?probe=a0f4cd454d) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dfc5a5f754](https://linux-hardware.org/?probe=dfc5a5f754) | Oct 13, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | [e560a29570](https://linux-hardware.org/?probe=e560a29570) | Oct 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [00d174fcf4](https://linux-hardware.org/?probe=00d174fcf4) | Oct 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ccee0b66d9](https://linux-hardware.org/?probe=ccee0b66d9) | Oct 12, 2022 |
| MSI           | GE72 2QF                    | [22904f1270](https://linux-hardware.org/?probe=22904f1270) | Oct 12, 2022 |
| MSI           | GE72 2QF                    | [ecd8555f97](https://linux-hardware.org/?probe=ecd8555f97) | Oct 12, 2022 |
| Thomson       | N14C4WH64                   | [bfc16b9ded](https://linux-hardware.org/?probe=bfc16b9ded) | Oct 12, 2022 |
| ASUSTek       | E402MA                      | [807cf84523](https://linux-hardware.org/?probe=807cf84523) | Oct 11, 2022 |
| ASUSTek       | N53Jg                       | [0b4302ed6c](https://linux-hardware.org/?probe=0b4302ed6c) | Oct 11, 2022 |
| Apple         | MacBookAir7,2               | [8b4c66e10a](https://linux-hardware.org/?probe=8b4c66e10a) | Oct 11, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [04cb107be2](https://linux-hardware.org/?probe=04cb107be2) | Oct 11, 2022 |
| Dell          | Precision 7720              | [2252c7bd79](https://linux-hardware.org/?probe=2252c7bd79) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| Apple         | MacBook5,2                  | [4687cf8900](https://linux-hardware.org/?probe=4687cf8900) | Oct 10, 2022 |
| Toshiba       | Satellite A100              | [f280857c1c](https://linux-hardware.org/?probe=f280857c1c) | Oct 09, 2022 |
| Dell          | Inspiron 14 5420            | [d9f937a8c4](https://linux-hardware.org/?probe=d9f937a8c4) | Oct 09, 2022 |
| HP            | Pavilion TS 11              | [1a6ea38863](https://linux-hardware.org/?probe=1a6ea38863) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [7785f0ebfb](https://linux-hardware.org/?probe=7785f0ebfb) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f15acdf9d4](https://linux-hardware.org/?probe=f15acdf9d4) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [487fd1959f](https://linux-hardware.org/?probe=487fd1959f) | Oct 08, 2022 |
| MSI           | Prestige 14Evo A11M         | [68137e0e8d](https://linux-hardware.org/?probe=68137e0e8d) | Oct 07, 2022 |
| HP            | Pavilion dv7                | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [e6eac5c882](https://linux-hardware.org/?probe=e6eac5c882) | Oct 07, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [b27c3b70a7](https://linux-hardware.org/?probe=b27c3b70a7) | Oct 07, 2022 |
| Google        | Setzer                      | [cdb57d7ddf](https://linux-hardware.org/?probe=cdb57d7ddf) | Oct 07, 2022 |
| Shanghai Z... | ZXE CRB                     | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| HP            | EliteBook 8470p             | [1b09c0a820](https://linux-hardware.org/?probe=1b09c0a820) | Oct 06, 2022 |
| HP            | EliteBook 8470p             | [0fa7893206](https://linux-hardware.org/?probe=0fa7893206) | Oct 06, 2022 |
| Acer          | Predator PH315-53           | [0f3387ce35](https://linux-hardware.org/?probe=0f3387ce35) | Oct 06, 2022 |
| Toshiba       | Satellite L40               | [0f3e9273a6](https://linux-hardware.org/?probe=0f3e9273a6) | Oct 06, 2022 |
| Google        | Akemi                       | [5a165f46bc](https://linux-hardware.org/?probe=5a165f46bc) | Oct 05, 2022 |
| Dell          | Precision 3541              | [bfef2cb8a3](https://linux-hardware.org/?probe=bfef2cb8a3) | Oct 05, 2022 |
| HP            | EliteBook 8570p             | [3079a45a56](https://linux-hardware.org/?probe=3079a45a56) | Oct 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [96b4cda722](https://linux-hardware.org/?probe=96b4cda722) | Oct 05, 2022 |
| HP            | EliteBook 8460p             | [02d4090cce](https://linux-hardware.org/?probe=02d4090cce) | Oct 05, 2022 |
| HP            | EliteBook 8460p             | [4f037d4c3d](https://linux-hardware.org/?probe=4f037d4c3d) | Oct 05, 2022 |
| Toshiba       | NB505                       | [9de39780b5](https://linux-hardware.org/?probe=9de39780b5) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [dea0d04059](https://linux-hardware.org/?probe=dea0d04059) | Oct 05, 2022 |
| Acer          | Aspire A315-23G             | [ab3508b938](https://linux-hardware.org/?probe=ab3508b938) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | EliteBook 8460p             | [8b9d1152e4](https://linux-hardware.org/?probe=8b9d1152e4) | Oct 04, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8631c6f717](https://linux-hardware.org/?probe=8631c6f717) | Oct 04, 2022 |
| MSI           | GF65 Thin 10SDR             | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| HP            | EliteBook 735 G6            | [c3f86b0e1a](https://linux-hardware.org/?probe=c3f86b0e1a) | Oct 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [33b42f3ed1](https://linux-hardware.org/?probe=33b42f3ed1) | Oct 04, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [5b2fac59ea](https://linux-hardware.org/?probe=5b2fac59ea) | Oct 04, 2022 |
| Shanghai Z... | ZXE CRB                     | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Lenovo        | ThinkPad Twist 20C41A3      | [3da96ac399](https://linux-hardware.org/?probe=3da96ac399) | Oct 04, 2022 |
| Acer          | Aspire A315-56              | [e799907aba](https://linux-hardware.org/?probe=e799907aba) | Oct 04, 2022 |
| Dell          | Precision M4800             | [1099761dca](https://linux-hardware.org/?probe=1099761dca) | Oct 04, 2022 |
| ASUSTek       | PU403UA                     | [8bf4879487](https://linux-hardware.org/?probe=8bf4879487) | Oct 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [31fa8b62ff](https://linux-hardware.org/?probe=31fa8b62ff) | Oct 04, 2022 |
| UNOWHY        | Y13G010S4EI                 | [38f5b56e5d](https://linux-hardware.org/?probe=38f5b56e5d) | Oct 04, 2022 |
| Dell          | Inspiron 5590               | [ed3bf1e99b](https://linux-hardware.org/?probe=ed3bf1e99b) | Oct 04, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [e42a5888c7](https://linux-hardware.org/?probe=e42a5888c7) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [84ce32d994](https://linux-hardware.org/?probe=84ce32d994) | Oct 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | [81ac41d8b9](https://linux-hardware.org/?probe=81ac41d8b9) | Oct 03, 2022 |
| Dell          | Latitude 2110               | [3fbbac2c8a](https://linux-hardware.org/?probe=3fbbac2c8a) | Oct 03, 2022 |
| ASUSTek       | 1225B                       | [9bb2d54ca7](https://linux-hardware.org/?probe=9bb2d54ca7) | Oct 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [1427143cf0](https://linux-hardware.org/?probe=1427143cf0) | Oct 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [64f2393fde](https://linux-hardware.org/?probe=64f2393fde) | Oct 03, 2022 |
| Toshiba       | Satellite L855              | [66e22581f7](https://linux-hardware.org/?probe=66e22581f7) | Oct 03, 2022 |
| Dell          | Precision 3570              | [f4f047eecf](https://linux-hardware.org/?probe=f4f047eecf) | Oct 03, 2022 |
| Apple         | MacBookAir7,2               | [ae39aea3e9](https://linux-hardware.org/?probe=ae39aea3e9) | Oct 02, 2022 |
| Lenovo        | ThinkPad T460s 20F90060G... | [8d17d38142](https://linux-hardware.org/?probe=8d17d38142) | Oct 02, 2022 |
| ASUSTek       | X71Q                        | [830c8ab6d2](https://linux-hardware.org/?probe=830c8ab6d2) | Oct 02, 2022 |
| Dell          | Vostro 5320                 | [93a0c7d88f](https://linux-hardware.org/?probe=93a0c7d88f) | Oct 02, 2022 |
| Toshiba       | Satellite L45               | [79ff097329](https://linux-hardware.org/?probe=79ff097329) | Oct 02, 2022 |
| Acer          | Aspire A715-41G             | [1a473e9809](https://linux-hardware.org/?probe=1a473e9809) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [5bc67115db](https://linux-hardware.org/?probe=5bc67115db) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [4758af490a](https://linux-hardware.org/?probe=4758af490a) | Oct 01, 2022 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | [fbe1e53387](https://linux-hardware.org/?probe=fbe1e53387) | Oct 01, 2022 |
| Lenovo        | ThinkPad L380 20M5SSIN11    | [0cad79b1f7](https://linux-hardware.org/?probe=0cad79b1f7) | Sep 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [786e0c1f5d](https://linux-hardware.org/?probe=786e0c1f5d) | Sep 30, 2022 |
| HP            | Pavilion Notebook           | [ee72cbd627](https://linux-hardware.org/?probe=ee72cbd627) | Sep 29, 2022 |
| HP            | Compaq nx6325 (EY344EA#A... | [8808f98c62](https://linux-hardware.org/?probe=8808f98c62) | Sep 29, 2022 |
| ASUSTek       | N53SV                       | [6652e85ddd](https://linux-hardware.org/?probe=6652e85ddd) | Sep 29, 2022 |
| HUAWEI        | KLVL-WXXW                   | [fd8b95bb3b](https://linux-hardware.org/?probe=fd8b95bb3b) | Sep 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | [0453cd781f](https://linux-hardware.org/?probe=0453cd781f) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | [973307d03b](https://linux-hardware.org/?probe=973307d03b) | Sep 28, 2022 |
| Acer          | Aspire A315-23G             | [3eaaf54d1b](https://linux-hardware.org/?probe=3eaaf54d1b) | Sep 28, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [ca9c7bf57b](https://linux-hardware.org/?probe=ca9c7bf57b) | Sep 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fb2de59c3f](https://linux-hardware.org/?probe=fb2de59c3f) | Sep 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [70f86aa587](https://linux-hardware.org/?probe=70f86aa587) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E752               | [f4e2b14498](https://linux-hardware.org/?probe=f4e2b14498) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [4f58ff1174](https://linux-hardware.org/?probe=4f58ff1174) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [56e06deea2](https://linux-hardware.org/?probe=56e06deea2) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [2d7ce63bce](https://linux-hardware.org/?probe=2d7ce63bce) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Dell          | Inspiron 15-3567            | [9ae6efbc0f](https://linux-hardware.org/?probe=9ae6efbc0f) | Sep 25, 2022 |
| HUAWEI        | RLEF-XX                     | [7bab2cbc57](https://linux-hardware.org/?probe=7bab2cbc57) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [23f425e425](https://linux-hardware.org/?probe=23f425e425) | Sep 24, 2022 |
| Dell          | Inspiron 14 5425            | [209be443ac](https://linux-hardware.org/?probe=209be443ac) | Sep 24, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [f3527878e5](https://linux-hardware.org/?probe=f3527878e5) | Sep 24, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | [89a019875a](https://linux-hardware.org/?probe=89a019875a) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| Dell          | Latitude 3320               | [3296a12784](https://linux-hardware.org/?probe=3296a12784) | Sep 24, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | [0adb7bc0b1](https://linux-hardware.org/?probe=0adb7bc0b1) | Sep 24, 2022 |
| VIT           | P2402                       | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| Samsung       | 550XBE/350XBE               | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Google        | Robo                        | [4772493ae3](https://linux-hardware.org/?probe=4772493ae3) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | [e17fb419bd](https://linux-hardware.org/?probe=e17fb419bd) | Sep 23, 2022 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | [077c05c78d](https://linux-hardware.org/?probe=077c05c78d) | Sep 23, 2022 |
| Acer          | Aspire ES1-732              | [d6ccc5301b](https://linux-hardware.org/?probe=d6ccc5301b) | Sep 23, 2022 |
| Dell          | XPS 15 9520                 | [1a7e610c32](https://linux-hardware.org/?probe=1a7e610c32) | Sep 23, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [f77dda559d](https://linux-hardware.org/?probe=f77dda559d) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [c9457ee571](https://linux-hardware.org/?probe=c9457ee571) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [412296c83f](https://linux-hardware.org/?probe=412296c83f) | Sep 22, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [db6f733994](https://linux-hardware.org/?probe=db6f733994) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [21ba0d8f46](https://linux-hardware.org/?probe=21ba0d8f46) | Sep 22, 2022 |
| Lenovo        | ThinkPad X220 4291G26       | [33654dfbfa](https://linux-hardware.org/?probe=33654dfbfa) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [0c4627555a](https://linux-hardware.org/?probe=0c4627555a) | Sep 22, 2022 |
| Dell          | Inspiron 5537               | [7e3170527c](https://linux-hardware.org/?probe=7e3170527c) | Sep 22, 2022 |
| HP            | Notebook                    | [18b9221add](https://linux-hardware.org/?probe=18b9221add) | Sep 22, 2022 |
| Toshiba       | Satellite P745              | [963d04c729](https://linux-hardware.org/?probe=963d04c729) | Sep 22, 2022 |
| Dell          | Vostro 15 5510              | [630b3877c4](https://linux-hardware.org/?probe=630b3877c4) | Sep 22, 2022 |
| MSI           | GS60 2PE                    | [1aaaa99706](https://linux-hardware.org/?probe=1aaaa99706) | Sep 22, 2022 |
| HP            | Presario CQ57               | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Avell High... | B.ON                        | [95c7e35ef3](https://linux-hardware.org/?probe=95c7e35ef3) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | [41af175db4](https://linux-hardware.org/?probe=41af175db4) | Sep 21, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [69d5dcb9b7](https://linux-hardware.org/?probe=69d5dcb9b7) | Sep 21, 2022 |
| Avell High... | B.ON                        | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| Dell          | Latitude 7530               | [39b655888c](https://linux-hardware.org/?probe=39b655888c) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| Dell          | Precision 7540              | [fb7472fe87](https://linux-hardware.org/?probe=fb7472fe87) | Sep 21, 2022 |
| Dell          | Inspiron MP061              | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [0ada4a5b83](https://linux-hardware.org/?probe=0ada4a5b83) | Sep 20, 2022 |
| HP            | Folio 13                    | [eafa8204e9](https://linux-hardware.org/?probe=eafa8204e9) | Sep 20, 2022 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [5861c90514](https://linux-hardware.org/?probe=5861c90514) | Sep 20, 2022 |
| HP            | EliteBook 840 14 inch G9... | [450a86c900](https://linux-hardware.org/?probe=450a86c900) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad X260 20F5003EMB    | [302eacc4ff](https://linux-hardware.org/?probe=302eacc4ff) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad SL400 2743AQC      | [beb74c65cc](https://linux-hardware.org/?probe=beb74c65cc) | Sep 19, 2022 |
| MSI           | Prestige 14Evo A11M         | [4b412dd569](https://linux-hardware.org/?probe=4b412dd569) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HP            | 15                          | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [0f049ae5d6](https://linux-hardware.org/?probe=0f049ae5d6) | Sep 19, 2022 |
| HP            | 15                          | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| HP            | G42                         | [3f584eb1af](https://linux-hardware.org/?probe=3f584eb1af) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Panasonic     | CF-53JAWZYDE                | [f8b1ca10d1](https://linux-hardware.org/?probe=f8b1ca10d1) | Sep 19, 2022 |
| Acer          | Aspire A315-23G             | [9e3edc5b61](https://linux-hardware.org/?probe=9e3edc5b61) | Sep 18, 2022 |
| Lenovo        | IdeaPad 720s-13ARR 81BR     | [fa45602fc5](https://linux-hardware.org/?probe=fa45602fc5) | Sep 18, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [b94564300a](https://linux-hardware.org/?probe=b94564300a) | Sep 18, 2022 |
| Dell          | Latitude E6330              | [bbb0a5f1a1](https://linux-hardware.org/?probe=bbb0a5f1a1) | Sep 18, 2022 |
| Dell          | Latitude 3310               | [4de8502362](https://linux-hardware.org/?probe=4de8502362) | Sep 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [87c3b99589](https://linux-hardware.org/?probe=87c3b99589) | Sep 18, 2022 |
| Acer          | Aspire A315-23G             | [3de0a6e725](https://linux-hardware.org/?probe=3de0a6e725) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| MSI           | Prestige 14Evo A11M         | [f474823b5a](https://linux-hardware.org/?probe=f474823b5a) | Sep 17, 2022 |
| Dell          | Latitude E7440              | [5194c92c15](https://linux-hardware.org/?probe=5194c92c15) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [6c5b0c0659](https://linux-hardware.org/?probe=6c5b0c0659) | Sep 17, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [1fa176a244](https://linux-hardware.org/?probe=1fa176a244) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [8c355ea88e](https://linux-hardware.org/?probe=8c355ea88e) | Sep 17, 2022 |
| HP            | Notebook                    | [9fcfcab16e](https://linux-hardware.org/?probe=9fcfcab16e) | Sep 17, 2022 |
| HP            | Unknown                     | [e87c925eb0](https://linux-hardware.org/?probe=e87c925eb0) | Sep 16, 2022 |
| Dell          | Latitude E5540              | [8e44a11e6c](https://linux-hardware.org/?probe=8e44a11e6c) | Sep 16, 2022 |
| Dell          | Latitude E5540              | [c2d57deba4](https://linux-hardware.org/?probe=c2d57deba4) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7e865e8b3f](https://linux-hardware.org/?probe=7e865e8b3f) | Sep 16, 2022 |
| Aquarius      | NS585                       | [84054aaa40](https://linux-hardware.org/?probe=84054aaa40) | Sep 16, 2022 |
| HP            | Stream Laptop 11-y0XX       | [b030fff6bb](https://linux-hardware.org/?probe=b030fff6bb) | Sep 16, 2022 |
| Aquarius      | NS585                       | [c4ad74720a](https://linux-hardware.org/?probe=c4ad74720a) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Aquarius      | NS585                       | [400485718e](https://linux-hardware.org/?probe=400485718e) | Sep 16, 2022 |
| Lenovo        | G50-45 80E3                 | [59c06bcd6f](https://linux-hardware.org/?probe=59c06bcd6f) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [382325db11](https://linux-hardware.org/?probe=382325db11) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4c33a54701](https://linux-hardware.org/?probe=4c33a54701) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [a1f16914f7](https://linux-hardware.org/?probe=a1f16914f7) | Sep 16, 2022 |
| Aquarius      | NS585                       | [249e3f9a7c](https://linux-hardware.org/?probe=249e3f9a7c) | Sep 16, 2022 |
| Acer          | Aspire A315-23G             | [283a38bb80](https://linux-hardware.org/?probe=283a38bb80) | Sep 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [14cbf91f0c](https://linux-hardware.org/?probe=14cbf91f0c) | Sep 15, 2022 |
| Google        | Stout                       | [82b966b9ad](https://linux-hardware.org/?probe=82b966b9ad) | Sep 15, 2022 |
| Dell          | Precision 3571              | [01f5d7f7f8](https://linux-hardware.org/?probe=01f5d7f7f8) | Sep 15, 2022 |
| Aquarius      | NS585                       | [e86929e9a3](https://linux-hardware.org/?probe=e86929e9a3) | Sep 15, 2022 |
| Aquarius      | NS585                       | [a1568949cd](https://linux-hardware.org/?probe=a1568949cd) | Sep 15, 2022 |
| Aquarius      | NS585                       | [feedc8a0ba](https://linux-hardware.org/?probe=feedc8a0ba) | Sep 15, 2022 |
| Aquarius      | NS585                       | [eb2906fdc5](https://linux-hardware.org/?probe=eb2906fdc5) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3bf32bc004](https://linux-hardware.org/?probe=3bf32bc004) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | [aa5d8a2fc6](https://linux-hardware.org/?probe=aa5d8a2fc6) | Sep 15, 2022 |
| Positivo      | Mobile                      | [f0f7335929](https://linux-hardware.org/?probe=f0f7335929) | Sep 15, 2022 |
| INFINITY      | Unknown                     | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [5bdc2b7041](https://linux-hardware.org/?probe=5bdc2b7041) | Sep 14, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| Google        | Terra                       | [9dae30736d](https://linux-hardware.org/?probe=9dae30736d) | Sep 14, 2022 |
| Aquarius      | NS585                       | [8fb883495e](https://linux-hardware.org/?probe=8fb883495e) | Sep 14, 2022 |
| Aquarius      | NS585                       | [2c51e9e9c2](https://linux-hardware.org/?probe=2c51e9e9c2) | Sep 14, 2022 |
| Aquarius      | NS585                       | [54a3f9eec9](https://linux-hardware.org/?probe=54a3f9eec9) | Sep 14, 2022 |
| Aquarius      | NS585                       | [3760a35f01](https://linux-hardware.org/?probe=3760a35f01) | Sep 14, 2022 |
| Dell          | Precision 3571              | [72e1a27ea7](https://linux-hardware.org/?probe=72e1a27ea7) | Sep 14, 2022 |
| Aquarius      | NS585                       | [7927c44ef0](https://linux-hardware.org/?probe=7927c44ef0) | Sep 14, 2022 |
| Aquarius      | NS585                       | [eaa0e46c9f](https://linux-hardware.org/?probe=eaa0e46c9f) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8935b3f204](https://linux-hardware.org/?probe=8935b3f204) | Sep 14, 2022 |
| Valve         | Jupiter                     | [28bed644da](https://linux-hardware.org/?probe=28bed644da) | Sep 14, 2022 |
| Aquarius      | NS585                       | [a904acc9e9](https://linux-hardware.org/?probe=a904acc9e9) | Sep 14, 2022 |
| Aquarius      | NS585                       | [7f883700cf](https://linux-hardware.org/?probe=7f883700cf) | Sep 14, 2022 |
| Aquarius      | NS585                       | [8ef03a6208](https://linux-hardware.org/?probe=8ef03a6208) | Sep 14, 2022 |
| Aquarius      | NS585                       | [c3f844b853](https://linux-hardware.org/?probe=c3f844b853) | Sep 14, 2022 |
| Aquarius      | NS585                       | [0a77a87395](https://linux-hardware.org/?probe=0a77a87395) | Sep 14, 2022 |
| Aquarius      | NS585                       | [344bf802ef](https://linux-hardware.org/?probe=344bf802ef) | Sep 14, 2022 |
| ASUSTek       | K54HR                       | [6be4965b4d](https://linux-hardware.org/?probe=6be4965b4d) | Sep 14, 2022 |
| Aquarius      | NS585                       | [f627c1d051](https://linux-hardware.org/?probe=f627c1d051) | Sep 14, 2022 |
| Aquarius      | NS585                       | [67eca2e394](https://linux-hardware.org/?probe=67eca2e394) | Sep 14, 2022 |
| Aquarius      | NS585                       | [8c8644f284](https://linux-hardware.org/?probe=8c8644f284) | Sep 14, 2022 |
| Aquarius      | NS585                       | [09ca233ab5](https://linux-hardware.org/?probe=09ca233ab5) | Sep 14, 2022 |
| Dell          | Latitude E7250              | [80a2e50cfc](https://linux-hardware.org/?probe=80a2e50cfc) | Sep 14, 2022 |
| Aquarius      | NS585                       | [df1a5c5ca1](https://linux-hardware.org/?probe=df1a5c5ca1) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [5784c0a7e3](https://linux-hardware.org/?probe=5784c0a7e3) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | [b8665b7aed](https://linux-hardware.org/?probe=b8665b7aed) | Sep 14, 2022 |
| ASUSTek       | K54HR                       | [e65b9d439e](https://linux-hardware.org/?probe=e65b9d439e) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | [22c2adf69b](https://linux-hardware.org/?probe=22c2adf69b) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [c8994c7912](https://linux-hardware.org/?probe=c8994c7912) | Sep 14, 2022 |
| Dell          | Inspiron 15-7568            | [c3b834caec](https://linux-hardware.org/?probe=c3b834caec) | Sep 14, 2022 |
| IPASON        | MaxBook P1X                 | [18d0740712](https://linux-hardware.org/?probe=18d0740712) | Sep 13, 2022 |
| Acer          | Aspire 5742                 | [9c37d390a7](https://linux-hardware.org/?probe=9c37d390a7) | Sep 13, 2022 |
| Google        | Terra                       | [a7150f06c7](https://linux-hardware.org/?probe=a7150f06c7) | Sep 13, 2022 |
| MSI           | Prestige 14Evo A11M         | [5a69611620](https://linux-hardware.org/?probe=5a69611620) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [89339e48f1](https://linux-hardware.org/?probe=89339e48f1) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d39dcbc8ed](https://linux-hardware.org/?probe=d39dcbc8ed) | Sep 13, 2022 |
| MSI           | Prestige 14Evo A11M         | [4c5dc2ec7d](https://linux-hardware.org/?probe=4c5dc2ec7d) | Sep 13, 2022 |
| Aquarius      | NS585                       | [f76497447f](https://linux-hardware.org/?probe=f76497447f) | Sep 13, 2022 |
| Aquarius      | NS585                       | [042a81998b](https://linux-hardware.org/?probe=042a81998b) | Sep 13, 2022 |
| Aquarius      | NS585                       | [e5078cd5f4](https://linux-hardware.org/?probe=e5078cd5f4) | Sep 13, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7acd0e62aa](https://linux-hardware.org/?probe=7acd0e62aa) | Sep 12, 2022 |
| Google        | Terra                       | [6b591d8c39](https://linux-hardware.org/?probe=6b591d8c39) | Sep 12, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [1d95c5b6ef](https://linux-hardware.org/?probe=1d95c5b6ef) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| Google        | Reks                        | [28f0932e1a](https://linux-hardware.org/?probe=28f0932e1a) | Sep 12, 2022 |
| Lenovo        | ThinkPad X240 20AL00ETGE    | [95a3df06c9](https://linux-hardware.org/?probe=95a3df06c9) | Sep 12, 2022 |
| Unknown       | Unknown                     | [b686d4f2b7](https://linux-hardware.org/?probe=b686d4f2b7) | Sep 12, 2022 |
| MSI           | Modern 15 A11M              | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| MSI           | GS60 2PE                    | [0164cbee91](https://linux-hardware.org/?probe=0164cbee91) | Sep 12, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [3a6e62d846](https://linux-hardware.org/?probe=3a6e62d846) | Sep 12, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [c18f89b2bb](https://linux-hardware.org/?probe=c18f89b2bb) | Sep 11, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| Dell          | Vostro 3400                 | [06c0b65315](https://linux-hardware.org/?probe=06c0b65315) | Sep 11, 2022 |
| Dell          | Vostro 3400                 | [59d8ed6557](https://linux-hardware.org/?probe=59d8ed6557) | Sep 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [cd49377ddf](https://linux-hardware.org/?probe=cd49377ddf) | Sep 11, 2022 |
| HP            | G42                         | [092b9e2c38](https://linux-hardware.org/?probe=092b9e2c38) | Sep 11, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | [c55fef18c3](https://linux-hardware.org/?probe=c55fef18c3) | Sep 11, 2022 |
| HP            | 255 G8 Notebook PC          | [cca78f4488](https://linux-hardware.org/?probe=cca78f4488) | Sep 11, 2022 |
| Lenovo        | ThinkPad L460 20FVS1BC0S    | [e668edf31d](https://linux-hardware.org/?probe=e668edf31d) | Sep 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5a7c8dfacf](https://linux-hardware.org/?probe=5a7c8dfacf) | Sep 10, 2022 |
| Google        | Treeya                      | [d7a00caa63](https://linux-hardware.org/?probe=d7a00caa63) | Sep 10, 2022 |
| Lenovo        | G50-45 80E3                 | [2f4b4e4203](https://linux-hardware.org/?probe=2f4b4e4203) | Sep 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [823dbe2390](https://linux-hardware.org/?probe=823dbe2390) | Sep 10, 2022 |
| ASUSTek       | X200CA                      | [70c2613095](https://linux-hardware.org/?probe=70c2613095) | Sep 09, 2022 |
| Acer          | AO532h                      | [3ea8a4ba38](https://linux-hardware.org/?probe=3ea8a4ba38) | Sep 09, 2022 |
| Toshiba       | Satellite L40               | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Dell          | Latitude E6330              | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| Dell          | Latitude 3320               | [1ab9888966](https://linux-hardware.org/?probe=1ab9888966) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [92ae6811fa](https://linux-hardware.org/?probe=92ae6811fa) | Sep 09, 2022 |
| HP            | Compaq 8510w                | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [d37b0f4483](https://linux-hardware.org/?probe=d37b0f4483) | Sep 08, 2022 |
| ASUSTek       | K46CB                       | [9449630b6a](https://linux-hardware.org/?probe=9449630b6a) | Sep 08, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [c8f2e1da45](https://linux-hardware.org/?probe=c8f2e1da45) | Sep 08, 2022 |
| Google        | Reks                        | [a171b11595](https://linux-hardware.org/?probe=a171b11595) | Sep 08, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [32ab96441e](https://linux-hardware.org/?probe=32ab96441e) | Sep 08, 2022 |
| ASUSTek       | UX430UAR                    | [478d0564a6](https://linux-hardware.org/?probe=478d0564a6) | Sep 08, 2022 |
| HP            | ProBook 440 G7              | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| ASUSTek       | X441NA                      | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| Acer          | Aspire 5738                 | [141712c674](https://linux-hardware.org/?probe=141712c674) | Sep 07, 2022 |
| Lenovo        | B570e 521524G               | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| HP            | Laptop 17-ca0xxx            | [c65eb0b5c8](https://linux-hardware.org/?probe=c65eb0b5c8) | Sep 07, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [044bee5e0c](https://linux-hardware.org/?probe=044bee5e0c) | Sep 07, 2022 |
| Dell          | XPS 17 9720                 | [b85068c001](https://linux-hardware.org/?probe=b85068c001) | Sep 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [c0e98bf9e5](https://linux-hardware.org/?probe=c0e98bf9e5) | Sep 06, 2022 |
| Aquarius      | NS585                       | [74e50c07d8](https://linux-hardware.org/?probe=74e50c07d8) | Sep 06, 2022 |
| HP            | ENVY 17                     | [63411dc061](https://linux-hardware.org/?probe=63411dc061) | Sep 06, 2022 |
| Lenovo        | ThinkPad P51s 20HB000URT    | [8214e1ba30](https://linux-hardware.org/?probe=8214e1ba30) | Sep 06, 2022 |
| HP            | ZBook Power 15.6 inch G9... | [f4a0990d22](https://linux-hardware.org/?probe=f4a0990d22) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | [fefa3f4935](https://linux-hardware.org/?probe=fefa3f4935) | Sep 06, 2022 |
| HP            | ProBook 640 G4              | [b76e5a62e8](https://linux-hardware.org/?probe=b76e5a62e8) | Sep 06, 2022 |
| Dell          | XPS 9320                    | [54c8e046a1](https://linux-hardware.org/?probe=54c8e046a1) | Sep 06, 2022 |
| Dell          | Latitude 5530               | [4a2fb0c4c2](https://linux-hardware.org/?probe=4a2fb0c4c2) | Sep 06, 2022 |
| Dell          | Latitude 5530               | [a0896a063c](https://linux-hardware.org/?probe=a0896a063c) | Sep 06, 2022 |
| ASUSTek       | X555LAB                     | [b10937286d](https://linux-hardware.org/?probe=b10937286d) | Sep 06, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [6bd37547d3](https://linux-hardware.org/?probe=6bd37547d3) | Sep 05, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [4c68e17f1a](https://linux-hardware.org/?probe=4c68e17f1a) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e6117fb016](https://linux-hardware.org/?probe=e6117fb016) | Sep 05, 2022 |
| Dell          | Vostro 15 5510              | [beb1aeb4ad](https://linux-hardware.org/?probe=beb1aeb4ad) | Sep 05, 2022 |
| Acer          | Aspire A517-52G             | [c1709e40b7](https://linux-hardware.org/?probe=c1709e40b7) | Sep 05, 2022 |
| Unknown       | Unknown                     | [efb1e9883d](https://linux-hardware.org/?probe=efb1e9883d) | Sep 05, 2022 |
| Unknown       | Unknown                     | [20178af23f](https://linux-hardware.org/?probe=20178af23f) | Sep 05, 2022 |
| Dell          | Latitude E6330              | [e4dcf51a84](https://linux-hardware.org/?probe=e4dcf51a84) | Sep 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c2cd1091cd](https://linux-hardware.org/?probe=c2cd1091cd) | Sep 04, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [ea93dfd855](https://linux-hardware.org/?probe=ea93dfd855) | Sep 04, 2022 |
| Lenovo        | ThinkPad X230 232438J       | [dca0e2fa77](https://linux-hardware.org/?probe=dca0e2fa77) | Sep 04, 2022 |
| Lenovo        | ThinkPad E450 20DCA087CD    | [26928f83da](https://linux-hardware.org/?probe=26928f83da) | Sep 04, 2022 |
| Dell          | XPS 15 9520                 | [9736522a27](https://linux-hardware.org/?probe=9736522a27) | Sep 03, 2022 |
| HP            | Compaq 8510w                | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| PC Special... | 14 Fusion IV                | [dd9ed93b55](https://linux-hardware.org/?probe=dd9ed93b55) | Sep 03, 2022 |
| HP            | Compaq 6910p                | [0165c7d3c6](https://linux-hardware.org/?probe=0165c7d3c6) | Sep 03, 2022 |
| Chuwi         | LarkBook                    | [351478ee65](https://linux-hardware.org/?probe=351478ee65) | Sep 03, 2022 |
| Aquarius      | NS585                       | [b11a34556d](https://linux-hardware.org/?probe=b11a34556d) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Acer          | Aspire A315-23G             | [9a2200f8f8](https://linux-hardware.org/?probe=9a2200f8f8) | Sep 03, 2022 |
| Valve         | Jupiter                     | [b5c7b2be02](https://linux-hardware.org/?probe=b5c7b2be02) | Sep 03, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [1822ab5853](https://linux-hardware.org/?probe=1822ab5853) | Sep 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [2c5c9d2233](https://linux-hardware.org/?probe=2c5c9d2233) | Sep 02, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [c8bf09dd8d](https://linux-hardware.org/?probe=c8bf09dd8d) | Sep 02, 2022 |
| Aquarius      | NS585                       | [86de3c4954](https://linux-hardware.org/?probe=86de3c4954) | Sep 02, 2022 |
| Dell          | XPS 13 9350                 | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Google        | Enguarde                    | [50369de0be](https://linux-hardware.org/?probe=50369de0be) | Sep 01, 2022 |
| Dell          | Latitude E6330              | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| MSI           | Katana GF66 12UC            | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| Google        | Enguarde                    | [b59a9615cd](https://linux-hardware.org/?probe=b59a9615cd) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [f25f0f5499](https://linux-hardware.org/?probe=f25f0f5499) | Sep 01, 2022 |
| Google        | Enguarde                    | [7acc7436b0](https://linux-hardware.org/?probe=7acc7436b0) | Sep 01, 2022 |
| Google        | Enguarde                    | [671a062f6e](https://linux-hardware.org/?probe=671a062f6e) | Sep 01, 2022 |
| Google        | Enguarde                    | [baabafd42b](https://linux-hardware.org/?probe=baabafd42b) | Sep 01, 2022 |
| Google        | Enguarde                    | [4c1595c83e](https://linux-hardware.org/?probe=4c1595c83e) | Sep 01, 2022 |
| Google        | Enguarde                    | [bb6b28b279](https://linux-hardware.org/?probe=bb6b28b279) | Sep 01, 2022 |
| Google        | Terra                       | [b7940ab738](https://linux-hardware.org/?probe=b7940ab738) | Sep 01, 2022 |
| Google        | Enguarde                    | [0cbe57b975](https://linux-hardware.org/?probe=0cbe57b975) | Sep 01, 2022 |
| Google        | Enguarde                    | [9f20842cc5](https://linux-hardware.org/?probe=9f20842cc5) | Sep 01, 2022 |
| Google        | Enguarde                    | [06969489cc](https://linux-hardware.org/?probe=06969489cc) | Sep 01, 2022 |
| Google        | Enguarde                    | [2b4231258e](https://linux-hardware.org/?probe=2b4231258e) | Sep 01, 2022 |
| Google        | Enguarde                    | [1a0596c60d](https://linux-hardware.org/?probe=1a0596c60d) | Sep 01, 2022 |
| Google        | Enguarde                    | [4dfdb5e364](https://linux-hardware.org/?probe=4dfdb5e364) | Sep 01, 2022 |
| Google        | Enguarde                    | [c6db81251c](https://linux-hardware.org/?probe=c6db81251c) | Sep 01, 2022 |
| Google        | Enguarde                    | [05f112ddb7](https://linux-hardware.org/?probe=05f112ddb7) | Sep 01, 2022 |
| Dell          | Vostro 15 5510              | [e14cc69370](https://linux-hardware.org/?probe=e14cc69370) | Sep 01, 2022 |
| ASUSTek       | K50IJ                       | [10dd5d1e15](https://linux-hardware.org/?probe=10dd5d1e15) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| ASUSTek       | UX550VD                     | [a43d53b3b7](https://linux-hardware.org/?probe=a43d53b3b7) | Sep 01, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [7277e72eb4](https://linux-hardware.org/?probe=7277e72eb4) | Aug 31, 2022 |
| Dell          | Latitude E6330              | [b5766d41fa](https://linux-hardware.org/?probe=b5766d41fa) | Aug 31, 2022 |
| HP            | 250 G8 Notebook PC          | [c0a39342c3](https://linux-hardware.org/?probe=c0a39342c3) | Aug 31, 2022 |
| HP            | Compaq 8510w                | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| HP            | Compaq nc6400 (RU626ET#A... | [e94cb8e943](https://linux-hardware.org/?probe=e94cb8e943) | Aug 30, 2022 |
| Google        | Reks                        | [71f6228c3d](https://linux-hardware.org/?probe=71f6228c3d) | Aug 30, 2022 |
| Google        | Reks                        | [48174b01b3](https://linux-hardware.org/?probe=48174b01b3) | Aug 30, 2022 |
| ASUSTek       | X550CC                      | [f9a9be3a35](https://linux-hardware.org/?probe=f9a9be3a35) | Aug 30, 2022 |
| Google        | Terra                       | [25f50ae6d9](https://linux-hardware.org/?probe=25f50ae6d9) | Aug 30, 2022 |
| Google        | Reks                        | [e768a1940e](https://linux-hardware.org/?probe=e768a1940e) | Aug 30, 2022 |
| Lenovo        | ThinkPad L490 20Q5001YPB    | [daae538154](https://linux-hardware.org/?probe=daae538154) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [30b240a3fe](https://linux-hardware.org/?probe=30b240a3fe) | Aug 29, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [ddc175428b](https://linux-hardware.org/?probe=ddc175428b) | Aug 29, 2022 |
| Dell          | Latitude 5590               | [e06f40dae9](https://linux-hardware.org/?probe=e06f40dae9) | Aug 29, 2022 |
| Acer          | TravelMate P215-53          | [4ba2e9fbba](https://linux-hardware.org/?probe=4ba2e9fbba) | Aug 29, 2022 |
| ASUSTek       | K55VM                       | [ec5806d544](https://linux-hardware.org/?probe=ec5806d544) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [7ed4b144d7](https://linux-hardware.org/?probe=7ed4b144d7) | Aug 28, 2022 |
| Apple         | MacBookPro14,1              | [31d4a8fc43](https://linux-hardware.org/?probe=31d4a8fc43) | Aug 28, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| Dell          | XPS 15 7590                 | [9158baf2c0](https://linux-hardware.org/?probe=9158baf2c0) | Aug 28, 2022 |
| Dell          | Latitude 5420               | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| BANGHO        | AERO X2 I1002               | [f24ddb9619](https://linux-hardware.org/?probe=f24ddb9619) | Aug 28, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [a10cbdb73b](https://linux-hardware.org/?probe=a10cbdb73b) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [562d827323](https://linux-hardware.org/?probe=562d827323) | Aug 27, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | [3d1138a71c](https://linux-hardware.org/?probe=3d1138a71c) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c155c4b324](https://linux-hardware.org/?probe=c155c4b324) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | [e4cd019582](https://linux-hardware.org/?probe=e4cd019582) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8231da35ed](https://linux-hardware.org/?probe=8231da35ed) | Aug 27, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2KU0... | [6500c142f5](https://linux-hardware.org/?probe=6500c142f5) | Aug 27, 2022 |
| Lenovo        | ThinkPad X260 20F5A050IG    | [33b5154a7a](https://linux-hardware.org/?probe=33b5154a7a) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | [634c973e53](https://linux-hardware.org/?probe=634c973e53) | Aug 27, 2022 |
| Medion        | Akoya P2213T                | [c8d10c3b3f](https://linux-hardware.org/?probe=c8d10c3b3f) | Aug 27, 2022 |
| Google        | Terra                       | [717b3cc17f](https://linux-hardware.org/?probe=717b3cc17f) | Aug 26, 2022 |
| Google        | Terra                       | [f9856d813e](https://linux-hardware.org/?probe=f9856d813e) | Aug 26, 2022 |
| ASUSTek       | X455LD                      | [5351e31366](https://linux-hardware.org/?probe=5351e31366) | Aug 26, 2022 |
| MSI           | Creator 15 A11UH            | [fdd5e2b26a](https://linux-hardware.org/?probe=fdd5e2b26a) | Aug 26, 2022 |
| Lenovo        | ThinkPad T590 20N4001NUS    | [479ef1a89c](https://linux-hardware.org/?probe=479ef1a89c) | Aug 26, 2022 |
| ASUSTek       | M70Vn                       | [2e84d460f5](https://linux-hardware.org/?probe=2e84d460f5) | Aug 26, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [73c598ebe7](https://linux-hardware.org/?probe=73c598ebe7) | Aug 26, 2022 |
| Lenovo        | ThinkPad T400 2768BM2       | [f2d91055c9](https://linux-hardware.org/?probe=f2d91055c9) | Aug 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [a624a45cda](https://linux-hardware.org/?probe=a624a45cda) | Aug 26, 2022 |
| HP            | ProBook 450 G6              | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [843ee79f1b](https://linux-hardware.org/?probe=843ee79f1b) | Aug 25, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [783495e971](https://linux-hardware.org/?probe=783495e971) | Aug 25, 2022 |
| Google        | Terra                       | [72965945d5](https://linux-hardware.org/?probe=72965945d5) | Aug 25, 2022 |
| Google        | Terra                       | [78436fd3bf](https://linux-hardware.org/?probe=78436fd3bf) | Aug 25, 2022 |
| Apple         | MacBookAir7,2               | [b2dc63405c](https://linux-hardware.org/?probe=b2dc63405c) | Aug 25, 2022 |
| Dell          | Inspiron 600m               | [6acc515c79](https://linux-hardware.org/?probe=6acc515c79) | Aug 25, 2022 |
| Dell          | Latitude 3570               | [287cfa2ce8](https://linux-hardware.org/?probe=287cfa2ce8) | Aug 25, 2022 |
| MSI           | GF63 Thin 10SCSR            | [f3facd36da](https://linux-hardware.org/?probe=f3facd36da) | Aug 24, 2022 |
| Lenovo        | ThinkPad E490 20N8001EUS    | [1620f0e5ff](https://linux-hardware.org/?probe=1620f0e5ff) | Aug 24, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| Dell          | XPS 15 9500                 | [b3a7cd094e](https://linux-hardware.org/?probe=b3a7cd094e) | Aug 24, 2022 |
| HP            | Laptop 14-dq2xxx            | [bc4f5f8811](https://linux-hardware.org/?probe=bc4f5f8811) | Aug 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [8b346ab142](https://linux-hardware.org/?probe=8b346ab142) | Aug 24, 2022 |
| Google        | Reks                        | [043b648dc5](https://linux-hardware.org/?probe=043b648dc5) | Aug 23, 2022 |
| Google        | Terra                       | [b720f3ca23](https://linux-hardware.org/?probe=b720f3ca23) | Aug 23, 2022 |
| Google        | Terra                       | [0fd5baced8](https://linux-hardware.org/?probe=0fd5baced8) | Aug 23, 2022 |
| Dell          | Inspiron 3583               | [dfbced302f](https://linux-hardware.org/?probe=dfbced302f) | Aug 23, 2022 |
| Google        | Terra                       | [92efdef775](https://linux-hardware.org/?probe=92efdef775) | Aug 23, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [e5d3453caa](https://linux-hardware.org/?probe=e5d3453caa) | Aug 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | [91f1311a5f](https://linux-hardware.org/?probe=91f1311a5f) | Aug 23, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [801a4be04d](https://linux-hardware.org/?probe=801a4be04d) | Aug 23, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | [2ac415ca87](https://linux-hardware.org/?probe=2ac415ca87) | Aug 23, 2022 |
| HP            | EliteBook 820 G1            | [1231c2fabe](https://linux-hardware.org/?probe=1231c2fabe) | Aug 23, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [d0b18cffdb](https://linux-hardware.org/?probe=d0b18cffdb) | Aug 23, 2022 |
| Dell          | Vostro 15 5510              | [3224d8bdcc](https://linux-hardware.org/?probe=3224d8bdcc) | Aug 23, 2022 |
| VANT          | MOOVE3-15                   | [854b7f42d4](https://linux-hardware.org/?probe=854b7f42d4) | Aug 22, 2022 |
| Acer          | Aspire 5742                 | [6692313edb](https://linux-hardware.org/?probe=6692313edb) | Aug 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [936ce5ca55](https://linux-hardware.org/?probe=936ce5ca55) | Aug 22, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [aacdd42304](https://linux-hardware.org/?probe=aacdd42304) | Aug 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [2431fa78d1](https://linux-hardware.org/?probe=2431fa78d1) | Aug 21, 2022 |
| HP            | Laptop 15-dy2xxx            | [532e1358b6](https://linux-hardware.org/?probe=532e1358b6) | Aug 21, 2022 |
| Dell          | XPS 15 9550                 | [8ab7fcb6ff](https://linux-hardware.org/?probe=8ab7fcb6ff) | Aug 21, 2022 |
| Dell          | Precision 7720              | [60ad0b7b3d](https://linux-hardware.org/?probe=60ad0b7b3d) | Aug 21, 2022 |
| Positivo      | Mobile                      | [8678ddf7ac](https://linux-hardware.org/?probe=8678ddf7ac) | Aug 20, 2022 |
| Positivo      | Mobile                      | [d1cf6b8c9e](https://linux-hardware.org/?probe=d1cf6b8c9e) | Aug 20, 2022 |
| VANT          | MOOVE3-15                   | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| Dell          | Vostro 15 5510              | [9f5e59e0b9](https://linux-hardware.org/?probe=9f5e59e0b9) | Aug 20, 2022 |
| MSI           | GF75 Thin 10SCSXR           | [095c130069](https://linux-hardware.org/?probe=095c130069) | Aug 20, 2022 |
| HP            | 620                         | [d3b1eb8b4e](https://linux-hardware.org/?probe=d3b1eb8b4e) | Aug 20, 2022 |
| HP            | Laptop 17-cp0xxx            | [6ba8616656](https://linux-hardware.org/?probe=6ba8616656) | Aug 20, 2022 |
| Samsung       | 935XDB                      | [a8d4f5e6a0](https://linux-hardware.org/?probe=a8d4f5e6a0) | Aug 20, 2022 |
| Google        | Reks                        | [e5cde69ff7](https://linux-hardware.org/?probe=e5cde69ff7) | Aug 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [9e72f598eb](https://linux-hardware.org/?probe=9e72f598eb) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [45bfdfa985](https://linux-hardware.org/?probe=45bfdfa985) | Aug 19, 2022 |
| HP            | 620                         | [259635c419](https://linux-hardware.org/?probe=259635c419) | Aug 19, 2022 |
| ICL           | N7x0WU                      | [7b9c4ad6b1](https://linux-hardware.org/?probe=7b9c4ad6b1) | Aug 19, 2022 |
| HP            | Compaq nx7300 (RH678EA#A... | [6fc01cef23](https://linux-hardware.org/?probe=6fc01cef23) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [e6003f393e](https://linux-hardware.org/?probe=e6003f393e) | Aug 19, 2022 |
| Dell          | Latitude 5500               | [1c7c8639aa](https://linux-hardware.org/?probe=1c7c8639aa) | Aug 19, 2022 |
| Google        | Reks                        | [d09d250717](https://linux-hardware.org/?probe=d09d250717) | Aug 18, 2022 |
| Google        | Terra                       | [4eca7693ab](https://linux-hardware.org/?probe=4eca7693ab) | Aug 18, 2022 |
| Google        | Reks                        | [9fc034e8a0](https://linux-hardware.org/?probe=9fc034e8a0) | Aug 18, 2022 |
| Google        | Terra                       | [aabdca917b](https://linux-hardware.org/?probe=aabdca917b) | Aug 18, 2022 |
| Acer          | TravelMate 5620             | [5b1df1054c](https://linux-hardware.org/?probe=5b1df1054c) | Aug 18, 2022 |
| Lenovo        | ThinkPad Edge E431 62774... | [b7d37d0c4c](https://linux-hardware.org/?probe=b7d37d0c4c) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Dell          | Vostro 3405                 | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Acer          | TravelMate 5620             | [cdb6e6d5d6](https://linux-hardware.org/?probe=cdb6e6d5d6) | Aug 17, 2022 |
| ASUSTek       | K70IJ                       | [99bb1459e7](https://linux-hardware.org/?probe=99bb1459e7) | Aug 17, 2022 |
| Shuttle       | DS437                       | [21e0ca6a77](https://linux-hardware.org/?probe=21e0ca6a77) | Aug 17, 2022 |
| Acer          | Nitro AN515-56              | [c62f8ea53b](https://linux-hardware.org/?probe=c62f8ea53b) | Aug 17, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [57732104cd](https://linux-hardware.org/?probe=57732104cd) | Aug 17, 2022 |
| Dell          | Precision M6600             | [2e1eaedbc4](https://linux-hardware.org/?probe=2e1eaedbc4) | Aug 17, 2022 |
| HP            | Laptop 14-dq2xxx            | [9cefc23bb3](https://linux-hardware.org/?probe=9cefc23bb3) | Aug 17, 2022 |
| HP            | 255 G5 Notebook PC          | [fdeea5b020](https://linux-hardware.org/?probe=fdeea5b020) | Aug 16, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [74e8d1be5b](https://linux-hardware.org/?probe=74e8d1be5b) | Aug 16, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [d04d18b241](https://linux-hardware.org/?probe=d04d18b241) | Aug 16, 2022 |
| Dell          | Inspiron 5547               | [84a3ba511d](https://linux-hardware.org/?probe=84a3ba511d) | Aug 16, 2022 |
| PCBOX         | Kant                        | [1b5c160d93](https://linux-hardware.org/?probe=1b5c160d93) | Aug 16, 2022 |
| Google        | Terra                       | [8c5b7a9814](https://linux-hardware.org/?probe=8c5b7a9814) | Aug 15, 2022 |
| Google        | Terra                       | [43c28dadff](https://linux-hardware.org/?probe=43c28dadff) | Aug 15, 2022 |
| Google        | Terra                       | [98b7a9a377](https://linux-hardware.org/?probe=98b7a9a377) | Aug 15, 2022 |
| Google        | Terra                       | [3bfcb2b1b4](https://linux-hardware.org/?probe=3bfcb2b1b4) | Aug 15, 2022 |
| Dell          | Latitude 5420               | [0dec3e9676](https://linux-hardware.org/?probe=0dec3e9676) | Aug 15, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Toshiba       | Satellite P50-B-103         | [39da8f51fe](https://linux-hardware.org/?probe=39da8f51fe) | Aug 14, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [49e3ff7af1](https://linux-hardware.org/?probe=49e3ff7af1) | Aug 14, 2022 |
| Dell          | Latitude 3320               | [b8e1190875](https://linux-hardware.org/?probe=b8e1190875) | Aug 14, 2022 |
| Dell          | Latitude 3320               | [f489cd4f21](https://linux-hardware.org/?probe=f489cd4f21) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | [eeed6b3d08](https://linux-hardware.org/?probe=eeed6b3d08) | Aug 14, 2022 |
| Dell          | Latitude E5430 vPro         | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| Acer          | Aspire A315-23G             | [cdba281a27](https://linux-hardware.org/?probe=cdba281a27) | Aug 13, 2022 |
| HP            | Pavilion g7                 | [34a327329a](https://linux-hardware.org/?probe=34a327329a) | Aug 13, 2022 |
| Apple         | MacBookPro12,1              | [8b417889e1](https://linux-hardware.org/?probe=8b417889e1) | Aug 13, 2022 |
| HP            | Presario CQ56               | [48dfc2da91](https://linux-hardware.org/?probe=48dfc2da91) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | [188bfa465d](https://linux-hardware.org/?probe=188bfa465d) | Aug 13, 2022 |
| Dell          | Latitude E6330              | [b48c021700](https://linux-hardware.org/?probe=b48c021700) | Aug 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [94eb72e4ac](https://linux-hardware.org/?probe=94eb72e4ac) | Aug 13, 2022 |
| HP            | Pavilion Notebook           | [3dd4d44be4](https://linux-hardware.org/?probe=3dd4d44be4) | Aug 12, 2022 |
| Acer          | Aspire A114-33              | [471a1ec71e](https://linux-hardware.org/?probe=471a1ec71e) | Aug 12, 2022 |
| Unknown       | Unknown                     | [84771d9750](https://linux-hardware.org/?probe=84771d9750) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | [ed37ad46b6](https://linux-hardware.org/?probe=ed37ad46b6) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | [2fab557514](https://linux-hardware.org/?probe=2fab557514) | Aug 12, 2022 |
| Dell          | XPS 13 9350                 | [6f828c5743](https://linux-hardware.org/?probe=6f828c5743) | Aug 12, 2022 |
| System76      | Oryx Pro                    | [87b38f5a99](https://linux-hardware.org/?probe=87b38f5a99) | Aug 12, 2022 |
| Apple         | MacBookAir7,2               | [c38e80ade4](https://linux-hardware.org/?probe=c38e80ade4) | Aug 11, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [efd4ec3ee7](https://linux-hardware.org/?probe=efd4ec3ee7) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | [4d052b34a7](https://linux-hardware.org/?probe=4d052b34a7) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [d64d35a05d](https://linux-hardware.org/?probe=d64d35a05d) | Aug 11, 2022 |
| Dell          | Latitude 6430U              | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [23b946fc6d](https://linux-hardware.org/?probe=23b946fc6d) | Aug 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3d7e2cfbcb](https://linux-hardware.org/?probe=3d7e2cfbcb) | Aug 11, 2022 |
| Toshiba       | Satellite M645              | [9fa1e00c24](https://linux-hardware.org/?probe=9fa1e00c24) | Aug 10, 2022 |
| Toshiba       | TECRA R950                  | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| HUAWEI        | BDZ-WXX9                    | [d3d3023a41](https://linux-hardware.org/?probe=d3d3023a41) | Aug 10, 2022 |
| ASUSTek       | X751LJ                      | [5c3767ccc2](https://linux-hardware.org/?probe=5c3767ccc2) | Aug 10, 2022 |
| Dell          | Latitude E6420              | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| HP            | Pavilion g6                 | [5b3f1dcc95](https://linux-hardware.org/?probe=5b3f1dcc95) | Aug 10, 2022 |
| GPU Compan... | GWTC116-2                   | [b92ffbefad](https://linux-hardware.org/?probe=b92ffbefad) | Aug 09, 2022 |
| ASUSTek       | X751LJ                      | [e35689c8f1](https://linux-hardware.org/?probe=e35689c8f1) | Aug 09, 2022 |
| Acer          | Aspire A515-56              | [21fdf57c32](https://linux-hardware.org/?probe=21fdf57c32) | Aug 09, 2022 |
| HP            | EliteBook 725 G3            | [7e36a68724](https://linux-hardware.org/?probe=7e36a68724) | Aug 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [66235597aa](https://linux-hardware.org/?probe=66235597aa) | Aug 09, 2022 |
| NVN-ED01      | Unknown                     | [0a677cad6c](https://linux-hardware.org/?probe=0a677cad6c) | Aug 09, 2022 |
| Dell          | Latitude 3320               | [b99f237d17](https://linux-hardware.org/?probe=b99f237d17) | Aug 09, 2022 |
| Alienware     | m15 R6                      | [675208eaec](https://linux-hardware.org/?probe=675208eaec) | Aug 09, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [b8ae818291](https://linux-hardware.org/?probe=b8ae818291) | Aug 08, 2022 |
| Alienware     | m15 R4                      | [d134cf97e4](https://linux-hardware.org/?probe=d134cf97e4) | Aug 08, 2022 |
| Dell          | Latitude E7450              | [f2d8a030f4](https://linux-hardware.org/?probe=f2d8a030f4) | Aug 08, 2022 |
| HP            | EliteBook 725 G3            | [e48eff307c](https://linux-hardware.org/?probe=e48eff307c) | Aug 08, 2022 |
| Acer          | Aspire A315-23G             | [46b74e61f0](https://linux-hardware.org/?probe=46b74e61f0) | Aug 08, 2022 |
| Samsung       | 935XDB                      | [fcfe8368c6](https://linux-hardware.org/?probe=fcfe8368c6) | Aug 08, 2022 |
| Dell          | Latitude E6430              | [17d0fce9e5](https://linux-hardware.org/?probe=17d0fce9e5) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | [b1420b630f](https://linux-hardware.org/?probe=b1420b630f) | Aug 07, 2022 |
| Acer          | Aspire 5738                 | [31d08ab231](https://linux-hardware.org/?probe=31d08ab231) | Aug 07, 2022 |
| Toshiba       | Satellite M645              | [a7225934dc](https://linux-hardware.org/?probe=a7225934dc) | Aug 07, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [19b3f7fe4b](https://linux-hardware.org/?probe=19b3f7fe4b) | Aug 07, 2022 |
| Dell          | Precision 7720              | [db2f868372](https://linux-hardware.org/?probe=db2f868372) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0564acfb6c](https://linux-hardware.org/?probe=0564acfb6c) | Aug 07, 2022 |
| SANTECH       | NHx0DB,DE                   | [1eba623e90](https://linux-hardware.org/?probe=1eba623e90) | Aug 06, 2022 |
| Dell          | XPS 9320                    | [358ffe39cd](https://linux-hardware.org/?probe=358ffe39cd) | Aug 06, 2022 |
| Dell          | XPS 13 9300                 | [b139d0b71f](https://linux-hardware.org/?probe=b139d0b71f) | Aug 06, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [53c997fe1f](https://linux-hardware.org/?probe=53c997fe1f) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d5786b75a3](https://linux-hardware.org/?probe=d5786b75a3) | Aug 05, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [24d8a6228c](https://linux-hardware.org/?probe=24d8a6228c) | Aug 05, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [83c6e58e51](https://linux-hardware.org/?probe=83c6e58e51) | Aug 05, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d12e654f35](https://linux-hardware.org/?probe=d12e654f35) | Aug 05, 2022 |
| HP            | ProBook 430 G5              | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| ASUSTek       | X550CC                      | [9d032c38b4](https://linux-hardware.org/?probe=9d032c38b4) | Aug 05, 2022 |
| ASUSTek       | X550CC                      | [433126127b](https://linux-hardware.org/?probe=433126127b) | Aug 05, 2022 |
| Dell          | XPS 9320                    | [ebc62403a7](https://linux-hardware.org/?probe=ebc62403a7) | Aug 05, 2022 |
| Acer          | Aspire 5315                 | [7be46d4930](https://linux-hardware.org/?probe=7be46d4930) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | [87d90381e1](https://linux-hardware.org/?probe=87d90381e1) | Aug 04, 2022 |
| HP            | EliteBook 8460p             | [7948505598](https://linux-hardware.org/?probe=7948505598) | Aug 04, 2022 |
| ASUSTek       | X75VC                       | [f293c53dec](https://linux-hardware.org/?probe=f293c53dec) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e74155922c](https://linux-hardware.org/?probe=e74155922c) | Aug 04, 2022 |
| Acer          | AO532h                      | [9a35f25fba](https://linux-hardware.org/?probe=9a35f25fba) | Aug 04, 2022 |
| Acer          | Aspire A315-23G             | [52e4d5e94f](https://linux-hardware.org/?probe=52e4d5e94f) | Aug 03, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [7fbe005ec3](https://linux-hardware.org/?probe=7fbe005ec3) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | [5ab3e7f74f](https://linux-hardware.org/?probe=5ab3e7f74f) | Aug 03, 2022 |
| Google        | Droid                       | [15d4518ba0](https://linux-hardware.org/?probe=15d4518ba0) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | [02d4876457](https://linux-hardware.org/?probe=02d4876457) | Aug 03, 2022 |
| ASUSTek       | X756UQK                     | [97b2316a06](https://linux-hardware.org/?probe=97b2316a06) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [8754f8caa3](https://linux-hardware.org/?probe=8754f8caa3) | Aug 03, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [94ccc2e14f](https://linux-hardware.org/?probe=94ccc2e14f) | Aug 03, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [eb77f8f852](https://linux-hardware.org/?probe=eb77f8f852) | Aug 03, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [0bf365f767](https://linux-hardware.org/?probe=0bf365f767) | Aug 02, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [e586e6ee53](https://linux-hardware.org/?probe=e586e6ee53) | Aug 02, 2022 |
| HP            | 255 G3                      | [46ad188006](https://linux-hardware.org/?probe=46ad188006) | Aug 02, 2022 |
| HUAWEI        | CREM-WXX9                   | [9e48213e39](https://linux-hardware.org/?probe=9e48213e39) | Aug 02, 2022 |
| HUAWEI        | CREM-WXX9                   | [2efb41280c](https://linux-hardware.org/?probe=2efb41280c) | Aug 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5d4fdde00](https://linux-hardware.org/?probe=f5d4fdde00) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [743422e837](https://linux-hardware.org/?probe=743422e837) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [78bde5c7cc](https://linux-hardware.org/?probe=78bde5c7cc) | Aug 02, 2022 |
| Dell          | Inspiron 13-7378            | [c08447d945](https://linux-hardware.org/?probe=c08447d945) | Aug 01, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [ae2fa8b811](https://linux-hardware.org/?probe=ae2fa8b811) | Aug 01, 2022 |
| Dell          | Latitude 7420               | [d498af2db5](https://linux-hardware.org/?probe=d498af2db5) | Aug 01, 2022 |
| Toshiba       | TECRA Z40-C                 | [9612659f60](https://linux-hardware.org/?probe=9612659f60) | Aug 01, 2022 |
| Apple         | MacBookPro11,5              | [24ccaddbf8](https://linux-hardware.org/?probe=24ccaddbf8) | Jul 31, 2022 |
| HP            | ProBook 4310s               | [d15b493637](https://linux-hardware.org/?probe=d15b493637) | Jul 31, 2022 |
| Dell          | Latitude 3320               | [183ae38016](https://linux-hardware.org/?probe=183ae38016) | Jul 31, 2022 |
| Dell          | Latitude 3320               | [a849c0d90a](https://linux-hardware.org/?probe=a849c0d90a) | Jul 30, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [9b362907fc](https://linux-hardware.org/?probe=9b362907fc) | Jul 30, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [61aed5ab55](https://linux-hardware.org/?probe=61aed5ab55) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | [1b94bd5797](https://linux-hardware.org/?probe=1b94bd5797) | Jul 29, 2022 |
| Acer          | AO756                       | [8203ac54d7](https://linux-hardware.org/?probe=8203ac54d7) | Jul 29, 2022 |
| ASUSTek       | GL553VE                     | [0bbcd152c5](https://linux-hardware.org/?probe=0bbcd152c5) | Jul 29, 2022 |
| Samsung       | R505                        | [4f92cf3c93](https://linux-hardware.org/?probe=4f92cf3c93) | Jul 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [0121efa569](https://linux-hardware.org/?probe=0121efa569) | Jul 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [bc5b132a8d](https://linux-hardware.org/?probe=bc5b132a8d) | Jul 29, 2022 |
| Lenovo        | ThinkPad L480 20LS002CPB    | [35764371d6](https://linux-hardware.org/?probe=35764371d6) | Jul 29, 2022 |
| HP            | EliteBook 820 G2            | [0735a357ee](https://linux-hardware.org/?probe=0735a357ee) | Jul 28, 2022 |
| Dell          | Latitude E5500              | [ba214335da](https://linux-hardware.org/?probe=ba214335da) | Jul 28, 2022 |
| HP            | Compaq 8510p                | [2a005b06da](https://linux-hardware.org/?probe=2a005b06da) | Jul 28, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [a05f5dc510](https://linux-hardware.org/?probe=a05f5dc510) | Jul 28, 2022 |
| Lenovo        | S21e-20 80M4                | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f062c9d4c7](https://linux-hardware.org/?probe=f062c9d4c7) | Jul 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [87f0eb95eb](https://linux-hardware.org/?probe=87f0eb95eb) | Jul 27, 2022 |
| HP            | Stream Notebook PC 11       | [e3c8a52e5b](https://linux-hardware.org/?probe=e3c8a52e5b) | Jul 27, 2022 |
| Acer          | Aspire A515-43              | [d378021961](https://linux-hardware.org/?probe=d378021961) | Jul 26, 2022 |
| HP            | Notebook                    | [9a4fc65b6a](https://linux-hardware.org/?probe=9a4fc65b6a) | Jul 26, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 2548      | 62.03%  |
| Debian 10                       | 844       | 20.55%  |
| Debian Testing                  | 357       | 8.69%   |
| Debian 9                        | 146       | 3.55%   |
| Debian Unstable                 | 128       | 3.12%   |
| Debian                          | 45        | 1.1%    |
| Debian 11-updates               | 23        | 0.56%   |
| Debian 8                        | 10        | 0.24%   |
| Debian Sid                      | 3         | 0.07%   |
| Debian Testing/unstable         | 2         | 0.05%   |
| Debian Testing-proposed-updates | 1         | 0.02%   |
| Debian 99                       | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Debian | 3999      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.10.0-8-amd64    | 583       | 12.95%  |
| 5.10.0-10-amd64   | 490       | 10.88%  |
| 5.10.0-9-amd64    | 170       | 3.78%   |
| 5.10.0-7-amd64    | 170       | 3.78%   |
| 5.10.0-16-amd64   | 165       | 3.66%   |
| 5.10.0-18-amd64   | 154       | 3.42%   |
| 5.10.0-13-amd64   | 149       | 3.31%   |
| 5.10.0-19-amd64   | 110       | 2.44%   |
| 5.10.0-11-amd64   | 102       | 2.27%   |
| 4.19.0-9-amd64    | 85        | 1.89%   |
| 4.19.0-6-amd64    | 82        | 1.82%   |
| 5.10.0-14-amd64   | 79        | 1.75%   |
| 5.10.0-17-amd64   | 72        | 1.6%    |
| 4.19.0-8-amd64    | 68        | 1.51%   |
| 4.19.0-13-amd64   | 68        | 1.51%   |
| 4.19.0-16-amd64   | 52        | 1.15%   |
| 4.19.0-10-amd64   | 52        | 1.15%   |
| 5.15.0-2-amd64    | 51        | 1.13%   |
| 4.19.0-12-amd64   | 47        | 1.04%   |
| 5.10.0-15-amd64   | 45        | 1%      |
| 4.19.0-14-amd64   | 42        | 0.93%   |
| 5.10.0-6-amd64    | 41        | 0.91%   |
| 5.10.0-12-amd64   | 40        | 0.89%   |
| 4.19.0-17-amd64   | 40        | 0.89%   |
| 4.9.0-8-amd64     | 39        | 0.87%   |
| 5.10.0-2-amd64    | 35        | 0.78%   |
| 5.18.0-2-amd64    | 31        | 0.69%   |
| 5.10.0-3-amd64    | 31        | 0.69%   |
| 5.19.0-1-amd64    | 26        | 0.58%   |
| 5.10.0-13-686-pae | 26        | 0.58%   |
| 5.4.0-4-amd64     | 25        | 0.56%   |
| 5.17.0-1-amd64    | 24        | 0.53%   |
| 5.18.0-4-amd64    | 23        | 0.51%   |
| 5.19.0-2-amd64    | 22        | 0.49%   |
| 5.16.0-6-amd64    | 22        | 0.49%   |
| 4.19.0-11-amd64   | 22        | 0.49%   |
| 5.7.0-1-amd64     | 21        | 0.47%   |
| 4.19.0-5-amd64    | 21        | 0.47%   |
| 5.6.0-2-amd64     | 20        | 0.44%   |
| 6.0.0-2-amd64     | 19        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 2452      | 58.08%  |
| 4.19.0  | 647       | 15.32%  |
| 4.9.0   | 120       | 2.84%   |
| 5.18.0  | 103       | 2.44%   |
| 5.15.0  | 91        | 2.16%   |
| 5.9.0   | 74        | 1.75%   |
| 5.16.0  | 65        | 1.54%   |
| 5.4.0   | 64        | 1.52%   |
| 5.19.0  | 61        | 1.44%   |
| 5.7.0   | 59        | 1.4%    |
| 5.8.0   | 56        | 1.33%   |
| 5.14.0  | 53        | 1.26%   |
| 6.0.0   | 48        | 1.14%   |
| 5.6.0   | 45        | 1.07%   |
| 5.17.0  | 39        | 0.92%   |
| 5.3.0   | 19        | 0.45%   |
| 5.5.0   | 16        | 0.38%   |
| 5.2.0   | 12        | 0.28%   |
| 4.18.0  | 12        | 0.28%   |
| 3.16.0  | 8         | 0.19%   |
| 5.12.0  | 6         | 0.14%   |
| 5.17.5  | 3         | 0.07%   |
| 5.13.19 | 3         | 0.07%   |
| 5.13.0  | 3         | 0.07%   |
| 5.11.0  | 3         | 0.07%   |
| 5.10.60 | 3         | 0.07%   |
| 5.10.10 | 3         | 0.07%   |
| 5.0.0   | 3         | 0.07%   |
| 6.0.2   | 2         | 0.05%   |
| 5.8.2   | 2         | 0.05%   |
| 5.8.16  | 2         | 0.05%   |
| 5.4.21  | 2         | 0.05%   |
| 5.3.5   | 2         | 0.05%   |
| 5.18.15 | 2         | 0.05%   |
| 5.17.11 | 2         | 0.05%   |
| 5.15.5  | 2         | 0.05%   |
| 5.15.35 | 2         | 0.05%   |
| 5.15.32 | 2         | 0.05%   |
| 5.13.8  | 2         | 0.05%   |
| 5.10.88 | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2472      | 58.66%  |
| 4.19    | 651       | 15.45%  |
| 4.9     | 123       | 2.92%   |
| 5.18    | 108       | 2.56%   |
| 5.15    | 107       | 2.54%   |
| 5.9     | 80        | 1.9%    |
| 5.4     | 76        | 1.8%    |
| 5.16    | 67        | 1.59%   |
| 5.19    | 65        | 1.54%   |
| 5.7     | 62        | 1.47%   |
| 5.8     | 61        | 1.45%   |
| 5.14    | 58        | 1.38%   |
| 6.0     | 53        | 1.26%   |
| 5.6     | 49        | 1.16%   |
| 5.17    | 48        | 1.14%   |
| 5.3     | 23        | 0.55%   |
| 5.5     | 19        | 0.45%   |
| 5.2     | 17        | 0.4%    |
| 5.13    | 12        | 0.28%   |
| 4.18    | 12        | 0.28%   |
| 5.12    | 9         | 0.21%   |
| 5.11    | 9         | 0.21%   |
| 3.16    | 8         | 0.19%   |
| 3.10    | 4         | 0.09%   |
| 5.1     | 3         | 0.07%   |
| 5.0     | 3         | 0.07%   |
| 4.17    | 2         | 0.05%   |
| 4.15    | 2         | 0.05%   |
| 6.1     | 1         | 0.02%   |
| 5.4.104 | 1         | 0.02%   |
| 5.15.6  | 1         | 0.02%   |
| 4.4     | 1         | 0.02%   |
| 4.20    | 1         | 0.02%   |
| 4.14    | 1         | 0.02%   |
| 4.13    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |
| 3.8     | 1         | 0.02%   |
| 3.0     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3803      | 95.08%  |
| i686    | 185       | 4.63%   |
| armv7l  | 9         | 0.23%   |
| aarch64 | 2         | 0.05%   |
| i586    | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 1123      | 27.44%  |
| GNOME            | 1050      | 25.65%  |
| XFCE             | 523       | 12.78%  |
| KDE5             | 485       | 11.85%  |
| MATE             | 170       | 4.15%   |
| X-Cinnamon       | 126       | 3.08%   |
| LXDE             | 119       | 2.91%   |
| Cinnamon         | 115       | 2.81%   |
| KDE              | 106       | 2.59%   |
| i3               | 83        | 2.03%   |
| LXQt             | 55        | 1.34%   |
| GNOME Flashback  | 30        | 0.73%   |
| lightdm-xsession | 23        | 0.56%   |
| openbox          | 13        | 0.32%   |
| Budgie           | 12        | 0.29%   |
| trinity          | 11        | 0.27%   |
| GNOME Classic    | 8         | 0.2%    |
| sway             | 4         | 0.1%    |
| ICEWM            | 4         | 0.1%    |
| bspwm            | 4         | 0.1%    |
| awesome          | 4         | 0.1%    |
| fluxbox          | 3         | 0.07%   |
| Enlightenment    | 3         | 0.07%   |
| DWM              | 3         | 0.07%   |
| Cutefish         | 3         | 0.07%   |
| Unity            | 2         | 0.05%   |
| KDE4             | 2         | 0.05%   |
| default          | 2         | 0.05%   |
| xmonad           | 1         | 0.02%   |
| wmaker-common    | 1         | 0.02%   |
| matchbox         | 1         | 0.02%   |
| jwm              | 1         | 0.02%   |
| i3-gaps          | 1         | 0.02%   |
| GNUstep          | 1         | 0.02%   |
| Deepin           | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2264      | 55.56%  |
| Unknown | 907       | 22.26%  |
| Wayland | 752       | 18.45%  |
| Tty     | 152       | 3.73%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1733      | 42.29%  |
| GDM     | 790       | 19.28%  |
| LightDM | 571       | 13.93%  |
| SDDM    | 481       | 11.74%  |
| TDM     | 310       | 7.56%   |
| GDM3    | 170       | 4.15%   |
| XDM     | 16        | 0.39%   |
| SLiM    | 13        | 0.32%   |
| NODM    | 7         | 0.17%   |
| KDM     | 6         | 0.15%   |
| WDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1172      | 28.85%  |
| Unknown | 932       | 22.94%  |
| ru_RU   | 275       | 6.77%   |
| de_DE   | 236       | 5.81%   |
| fr_FR   | 207       | 5.09%   |
| en_GB   | 161       | 3.96%   |
| pt_BR   | 138       | 3.4%    |
| es_ES   | 123       | 3.03%   |
| it_IT   | 109       | 2.68%   |
| pl_PL   | 78        | 1.92%   |
| en_CA   | 47        | 1.16%   |
| C       | 40        | 0.98%   |
| es_MX   | 38        | 0.94%   |
| en_AU   | 37        | 0.91%   |
| en_IN   | 35        | 0.86%   |
| zh_CN   | 30        | 0.74%   |
| es_CL   | 27        | 0.66%   |
| es_AR   | 24        | 0.59%   |
| en_IE   | 23        | 0.57%   |
| hu_HU   | 22        | 0.54%   |
| pt_PT   | 16        | 0.39%   |
| es_VE   | 14        | 0.34%   |
| de_CH   | 14        | 0.34%   |
| nl_NL   | 12        | 0.3%    |
| fi_FI   | 12        | 0.3%    |
| en_NZ   | 12        | 0.3%    |
| de_AT   | 12        | 0.3%    |
| cs_CZ   | 12        | 0.3%    |
| sv_SE   | 11        | 0.27%   |
| es_CO   | 11        | 0.27%   |
| en_ZA   | 11        | 0.27%   |
| tr_TR   | 10        | 0.25%   |
| ja_JP   | 10        | 0.25%   |
| en_SG   | 9         | 0.22%   |
| ru_UA   | 8         | 0.2%    |
| uk_UA   | 6         | 0.15%   |
| fr_CH   | 6         | 0.15%   |
| fr_BE   | 6         | 0.15%   |
| es_PE   | 6         | 0.15%   |
| da_DK   | 6         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2456      | 60.78%  |
| BIOS | 1585      | 39.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2792      | 69.45%  |
| Overlay | 945       | 23.51%  |
| Btrfs   | 123       | 3.06%   |
| Unknown | 78        | 1.94%   |
| Xfs     | 37        | 0.92%   |
| Ext2    | 13        | 0.32%   |
| Zfs     | 12        | 0.3%    |
| Rootfs  | 6         | 0.15%   |
| Tmpfs   | 5         | 0.12%   |
| Ext3    | 5         | 0.12%   |
| Aufs    | 3         | 0.07%   |
| F2fs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2465      | 60.62%  |
| Unknown | 844       | 20.76%  |
| MBR     | 757       | 18.62%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3276      | 80.97%  |
| Yes       | 770       | 19.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3016      | 74.52%  |
| Yes       | 1031      | 25.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 871       | 21.78%  |
| Hewlett-Packard        | 586       | 14.65%  |
| Apple                  | 581       | 14.53%  |
| Dell                   | 565       | 14.13%  |
| ASUSTek Computer       | 372       | 9.3%    |
| Acer                   | 245       | 6.13%   |
| Google                 | 128       | 3.2%    |
| MSI                    | 64        | 1.6%    |
| Toshiba                | 63        | 1.58%   |
| Samsung Electronics    | 60        | 1.5%    |
| Aquarius               | 44        | 1.1%    |
| Sony                   | 37        | 0.93%   |
| HUAWEI                 | 34        | 0.85%   |
| Unknown                | 28        | 0.7%    |
| Notebook               | 23        | 0.58%   |
| Fujitsu                | 17        | 0.43%   |
| Alienware              | 13        | 0.33%   |
| Medion                 | 12        | 0.3%    |
| IBM                    | 11        | 0.28%   |
| Timi                   | 10        | 0.25%   |
| Positivo               | 10        | 0.25%   |
| Intel                  | 10        | 0.25%   |
| Panasonic              | 9         | 0.23%   |
| Packard Bell           | 9         | 0.23%   |
| TUXEDO                 | 8         | 0.2%    |
| LG Electronics         | 8         | 0.2%    |
| Fujitsu Siemens        | 8         | 0.2%    |
| Clevo                  | 8         | 0.2%    |
| Razer                  | 7         | 0.18%   |
| PC Specialist          | 6         | 0.15%   |
| GPU Company            | 6         | 0.15%   |
| SLIMBOOK               | 5         | 0.13%   |
| Gigabyte Technology    | 5         | 0.13%   |
| Chuwi                  | 5         | 0.13%   |
| Avell High Performance | 5         | 0.13%   |
| System76               | 4         | 0.1%    |
| Insyde                 | 4         | 0.1%    |
| HONOR                  | 4         | 0.1%    |
| eMachines              | 4         | 0.1%    |
| Compal                 | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 306       | 7.65%   |
| Apple MacBookAir7,2                   | 75        | 1.88%   |
| Apple MacBookAir7,1                   | 75        | 1.88%   |
| Google Enguarde                       | 74        | 1.85%   |
| Apple MacBook2,1                      | 56        | 1.4%    |
| Aquarius NS585                        | 44        | 1.1%    |
| Unknown                               | 40        | 1%      |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.6%    |
| Google Terra                          | 23        | 0.58%   |
| Apple MacBook4,1                      | 23        | 0.58%   |
| HP Notebook                           | 20        | 0.5%    |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.4%    |
| Acer Aspire A315-23                   | 16        | 0.4%    |
| HP Pavilion g6                        | 15        | 0.38%   |
| ASUS 1005HA                           | 15        | 0.38%   |
| HP EliteBook 8460p                    | 11        | 0.28%   |
| HP Laptop 15-db0xxx                   | 10        | 0.25%   |
| HP 250 G7 Notebook PC                 | 9         | 0.23%   |
| Google Reks                           | 9         | 0.23%   |
| Dell XPS 13 9310                      | 8         | 0.2%    |
| Dell Latitude E7450                   | 8         | 0.2%    |
| Dell Latitude E6420                   | 8         | 0.2%    |
| Dell Inspiron 5570                    | 8         | 0.2%    |
| Lenovo IdeaPad S145-15API 81V7        | 7         | 0.18%   |
| HP Pavilion Notebook                  | 7         | 0.18%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 7         | 0.18%   |
| HP Pavilion dv6                       | 7         | 0.18%   |
| Dell Latitude E7470                   | 7         | 0.18%   |
| Dell Latitude E6430                   | 7         | 0.18%   |
| Dell Latitude E6330                   | 7         | 0.18%   |
| Dell Latitude 7490                    | 7         | 0.18%   |
| Dell Latitude 7480                    | 7         | 0.18%   |
| Apple MacBook7,1                      | 7         | 0.18%   |
| Samsung 300E4C/300E5C/300E7C          | 6         | 0.15%   |
| HP Stream Notebook PC 13              | 6         | 0.15%   |
| HP Pavilion g4                        | 6         | 0.15%   |
| HP Laptop 15s-fq2xxx                  | 6         | 0.15%   |
| HP Laptop 15-db1xxx                   | 6         | 0.15%   |
| HP Laptop 15-bw0xx                    | 6         | 0.15%   |
| HP EliteBook 8470p                    | 6         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 580       | 14.5%   |
| Apple MacBook5    | 307       | 7.68%   |
| Dell Latitude     | 208       | 5.2%    |
| Dell Inspiron     | 177       | 4.43%   |
| Acer Aspire       | 160       | 4%      |
| Lenovo IdeaPad    | 154       | 3.85%   |
| Apple MacBookAir7 | 150       | 3.75%   |
| HP EliteBook      | 114       | 2.85%   |
| HP Pavilion       | 94        | 2.35%   |
| HP Laptop         | 80        | 2%      |
| HP ProBook        | 77        | 1.93%   |
| Google Enguarde   | 74        | 1.85%   |
| Dell XPS          | 64        | 1.6%    |
| Apple MacBook2    | 56        | 1.4%    |
| Dell Vostro       | 50        | 1.25%   |
| Toshiba Satellite | 48        | 1.2%    |
| ASUS VivoBook     | 46        | 1.15%   |
| Aquarius NS585    | 44        | 1.1%    |
| Dell Precision    | 43        | 1.08%   |
| Unknown           | 40        | 1%      |
| HP Compaq         | 35        | 0.88%   |
| HP 250            | 28        | 0.7%    |
| ASUS ZenBook      | 25        | 0.63%   |
| Google Terra      | 23        | 0.58%   |
| Apple MacBook4    | 23        | 0.58%   |
| HP ZBook          | 22        | 0.55%   |
| Lenovo Legion     | 21        | 0.53%   |
| HP Notebook       | 20        | 0.5%    |
| ASUS ASUS         | 20        | 0.5%    |
| Lenovo ThinkBook  | 19        | 0.48%   |
| Acer Swift        | 19        | 0.48%   |
| Acer TravelMate   | 17        | 0.43%   |
| Acer Nitro        | 17        | 0.43%   |
| HP ENVY           | 15        | 0.38%   |
| HP 255            | 15        | 0.38%   |
| ASUS ROG          | 15        | 0.38%   |
| ASUS 1005HA       | 15        | 0.38%   |
| HP OMEN           | 14        | 0.35%   |
| Fujitsu LIFEBOOK  | 14        | 0.35%   |
| ASUS TUF          | 12        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 426       | 10.65%  |
| 2019    | 406       | 10.15%  |
| 2020    | 369       | 9.23%   |
| 2021    | 315       | 7.88%   |
| 2016    | 267       | 6.68%   |
| 2018    | 260       | 6.5%    |
| 2011    | 258       | 6.45%   |
| 2015    | 250       | 6.25%   |
| 2012    | 245       | 6.13%   |
| 2017    | 243       | 6.08%   |
| 2013    | 185       | 4.63%   |
| 2014    | 175       | 4.38%   |
| 2010    | 152       | 3.8%    |
| 2008    | 129       | 3.23%   |
| 2007    | 119       | 2.98%   |
| 2022    | 118       | 2.95%   |
| 2006    | 23        | 0.58%   |
| 2005    | 22        | 0.55%   |
| Unknown | 14        | 0.35%   |
| 2004    | 11        | 0.28%   |
| 2003    | 10        | 0.25%   |
| 2002    | 2         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3999      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3712      | 92.38%  |
| Enabled  | 306       | 7.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3860      | 96.5%   |
| Yes  | 140       | 3.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1039      | 25.74%  |
| 3.01-4.0    | 775       | 19.2%   |
| 16.01-24.0  | 636       | 15.76%  |
| 8.01-16.0   | 601       | 14.89%  |
| 1.01-2.0    | 512       | 12.69%  |
| 32.01-64.0  | 218       | 5.4%    |
| 2.01-3.0    | 85        | 2.11%   |
| 0.51-1.0    | 73        | 1.81%   |
| 64.01-256.0 | 39        | 0.97%   |
| 24.01-32.0  | 35        | 0.87%   |
| 0.01-0.5    | 21        | 0.52%   |
| Unknown     | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1722      | 40.3%   |
| 2.01-3.0   | 845       | 19.78%  |
| 4.01-8.0   | 546       | 12.78%  |
| 0.51-1.0   | 444       | 10.39%  |
| 3.01-4.0   | 430       | 10.06%  |
| 8.01-16.0  | 148       | 3.46%   |
| 0.01-0.5   | 111       | 2.6%    |
| 16.01-24.0 | 13        | 0.3%    |
| Unknown    | 7         | 0.16%   |
| 32.01-64.0 | 3         | 0.07%   |
| 24.01-32.0 | 3         | 0.07%   |
| 0          | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3194      | 78.77%  |
| 2      | 738       | 18.2%   |
| 3      | 82        | 2.02%   |
| 0      | 23        | 0.57%   |
| 4      | 12        | 0.3%    |
| 5      | 4         | 0.1%    |
| 7      | 2         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2577      | 64.2%   |
| Yes       | 1437      | 35.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3260      | 81.28%  |
| No        | 751       | 18.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3923      | 98.03%  |
| No        | 79        | 1.97%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3212      | 79.78%  |
| No        | 814       | 20.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1125      | 27.93%  |
| Germany      | 351       | 8.71%   |
| Russia       | 322       | 7.99%   |
| France       | 265       | 6.58%   |
| Brazil       | 203       | 5.04%   |
| Spain        | 172       | 4.27%   |
| Italy        | 148       | 3.67%   |
| Poland       | 110       | 2.73%   |
| UK           | 88        | 2.18%   |
| Netherlands  | 65        | 1.61%   |
| Canada       | 65        | 1.61%   |
| Mexico       | 55        | 1.37%   |
| Switzerland  | 54        | 1.34%   |
| India        | 52        | 1.29%   |
| Ukraine      | 49        | 1.22%   |
| China        | 47        | 1.17%   |
| Argentina    | 44        | 1.09%   |
| Australia    | 41        | 1.02%   |
| Sweden       | 36        | 0.89%   |
| Portugal     | 36        | 0.89%   |
| Turkey       | 34        | 0.84%   |
| Chile        | 33        | 0.82%   |
| Hungary      | 32        | 0.79%   |
| Austria      | 30        | 0.74%   |
| Belgium      | 29        | 0.72%   |
| Czechia      | 28        | 0.7%    |
| Greece       | 27        | 0.67%   |
| Norway       | 25        | 0.62%   |
| Finland      | 22        | 0.55%   |
| Romania      | 20        | 0.5%    |
| Ireland      | 20        | 0.5%    |
| Colombia     | 20        | 0.5%    |
| Indonesia    | 19        | 0.47%   |
| Venezuela    | 17        | 0.42%   |
| Japan        | 17        | 0.42%   |
| New Zealand  | 16        | 0.4%    |
| Thailand     | 15        | 0.37%   |
| Denmark      | 15        | 0.37%   |
| Bulgaria     | 13        | 0.32%   |
| South Africa | 12        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 541       | 12.79%  |
| Dover-Foxcroft    | 229       | 5.41%   |
| Voronezh          | 134       | 3.17%   |
| Moscow            | 46        | 1.09%   |
| Paris             | 45        | 1.06%   |
| St Petersburg     | 43        | 1.02%   |
| Berlin            | 38        | 0.9%    |
| Seville           | 34        | 0.8%    |
| Madrid            | 32        | 0.76%   |
| Sao Paulo         | 31        | 0.73%   |
| Warsaw            | 27        | 0.64%   |
| Munich            | 25        | 0.59%   |
| Vienna            | 22        | 0.52%   |
| Amsterdam         | 22        | 0.52%   |
| Milan             | 19        | 0.45%   |
| Hamburg           | 18        | 0.43%   |
| Zurich            | 17        | 0.4%    |
| London            | 17        | 0.4%    |
| Barcelona         | 16        | 0.38%   |
| Prague            | 15        | 0.35%   |
| Budapest          | 15        | 0.35%   |
| Athens            | 15        | 0.35%   |
| Sydney            | 14        | 0.33%   |
| Frankfurt am Main | 14        | 0.33%   |
| Perm              | 13        | 0.31%   |
| Dublin            | 13        | 0.31%   |
| Mexico City       | 12        | 0.28%   |
| Istanbul          | 12        | 0.28%   |
| Brasília         | 12        | 0.28%   |
| Toronto           | 11        | 0.26%   |
| Singapore         | 11        | 0.26%   |
| Lisbon            | 11        | 0.26%   |
| Helsinki          | 11        | 0.26%   |
| Blizniew          | 11        | 0.26%   |
| Bangkok           | 11        | 0.26%   |
| Zagreb            | 10        | 0.24%   |
| Turin             | 10        | 0.24%   |
| New York          | 10        | 0.24%   |
| Kyiv              | 10        | 0.24%   |
| Belo Horizonte    | 10        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 672       | 855    | 14.06%  |
| WDC                       | 545       | 658    | 11.4%   |
| Seagate                   | 465       | 553    | 9.73%   |
| Toshiba                   | 381       | 426    | 7.97%   |
| Unknown                   | 323       | 412    | 6.76%   |
| Kingston                  | 254       | 311    | 5.31%   |
| Fujitsu                   | 252       | 257    | 5.27%   |
| SanDisk                   | 226       | 274    | 4.73%   |
| SK hynix                  | 181       | 221    | 3.79%   |
| Crucial                   | 179       | 220    | 3.74%   |
| Apple                     | 172       | 201    | 3.6%    |
| Hitachi                   | 140       | 161    | 2.93%   |
| A-DATA Technology         | 114       | 195    | 2.38%   |
| Intel                     | 106       | 127    | 2.22%   |
| Micron Technology         | 103       | 108    | 2.15%   |
| HGST                      | 100       | 114    | 2.09%   |
| KIOXIA                    | 42        | 53     | 0.88%   |
| LITEON                    | 28        | 32     | 0.59%   |
| Transcend                 | 26        | 32     | 0.54%   |
| China                     | 26        | 28     | 0.54%   |
| Silicon Motion            | 20        | 21     | 0.42%   |
| Unknown                   | 20        | 21     | 0.42%   |
| PNY                       | 19        | 21     | 0.4%    |
| Phison                    | 19        | 26     | 0.4%    |
| Intenso                   | 19        | 25     | 0.4%    |
| SABRENT                   | 16        | 17     | 0.33%   |
| SPCC                      | 15        | 19     | 0.31%   |
| Patriot                   | 14        | 16     | 0.29%   |
| LITEONIT                  | 13        | 15     | 0.27%   |
| GOODRAM                   | 11        | 13     | 0.23%   |
| Team                      | 10        | 12     | 0.21%   |
| OCZ                       | 10        | 12     | 0.21%   |
| Micron/Crucial Technology | 10        | 10     | 0.21%   |
| SSSTC                     | 9         | 9      | 0.19%   |
| Lenovo                    | 8         | 10     | 0.17%   |
| LDLC                      | 8         | 8      | 0.17%   |
| Hewlett-Packard           | 8         | 7      | 0.17%   |
| Union Memory              | 7         | 8      | 0.15%   |
| Plextor                   | 7         | 7      | 0.15%   |
| KingSpec                  | 7         | 7      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 201       | 4.11%   |
| Apple SSD AP0128H 121GB              | 75        | 1.53%   |
| Apple SSD SM0128G 121GB              | 71        | 1.45%   |
| Seagate ST1000LM035-1RK172 1TB       | 61        | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 52        | 1.06%   |
| Kingston SA400S37240G 240GB SSD      | 51        | 1.04%   |
| Kingston SA400S37120G 120GB SSD      | 48        | 0.98%   |
| Toshiba MK1655GSXF 160GB             | 46        | 0.94%   |
| A-DATA SU800 512GB SSD               | 46        | 0.94%   |
| Toshiba MK1653GSX 160GB              | 43        | 0.88%   |
| Unknown AGND3R  16GB                 | 39        | 0.8%    |
| HGST HTS721010A9E630 1TB             | 37        | 0.76%   |
| Toshiba MQ01ABD100 1TB               | 35        | 0.72%   |
| Toshiba MQ01ABF050 500GB             | 32        | 0.65%   |
| Unknown HAG2e  16GB                  | 31        | 0.63%   |
| Toshiba MQ04ABF100 1TB               | 30        | 0.61%   |
| Unknown MMC Card  32GB               | 28        | 0.57%   |
| Crucial CT500MX500SSD1 500GB         | 28        | 0.57%   |
| Unknown SDW16G  16GB                 | 25        | 0.51%   |
| Seagate ST1000LM048-2E7172 1TB       | 23        | 0.47%   |
| Samsung SSD 860 EVO 500GB            | 23        | 0.47%   |
| Samsung SSD 850 EVO 250GB            | 23        | 0.47%   |
| Kingston SA400S37480G 480GB SSD      | 22        | 0.45%   |
| Seagate ST500LT012-1DG142 500GB      | 21        | 0.43%   |
| Unknown                              | 20        | 0.41%   |
| Unknown MMC Card  64GB               | 19        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB         | 19        | 0.39%   |
| Samsung SSD 860 EVO 1TB              | 19        | 0.39%   |
| Crucial CT1000MX500SSD1 1TB          | 19        | 0.39%   |
| WDC WD10SPZX-24Z10 1TB               | 18        | 0.37%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 18        | 0.37%   |
| Samsung SSD 860 EVO 250GB            | 18        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD     | 18        | 0.37%   |
| Seagate ST9500325AS 500GB            | 17        | 0.35%   |
| HGST HTS725050A7E630 500GB           | 17        | 0.35%   |
| Crucial CT240BX500SSD1 240GB         | 17        | 0.35%   |
| WDC WD1600BUDT-63DPZY0 160GB         | 16        | 0.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 16        | 0.33%   |
| Seagate ST1000LM049-2GH172 1TB       | 16        | 0.33%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 16        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 450       | 536    | 28%     |
| WDC                 | 318       | 358    | 19.79%  |
| Toshiba             | 286       | 314    | 17.8%   |
| Fujitsu             | 252       | 257    | 15.68%  |
| Hitachi             | 140       | 161    | 8.71%   |
| HGST                | 100       | 114    | 6.22%   |
| Samsung Electronics | 30        | 32     | 1.87%   |
| Unknown             | 8         | 11     | 0.5%    |
| IBM/Hitachi         | 5         | 6      | 0.31%   |
| ASMT                | 4         | 9      | 0.25%   |
| Intenso             | 3         | 4      | 0.19%   |
| SILICONMOTION       | 2         | 2      | 0.12%   |
| Unknown (CF)        | 1         | 1      | 0.06%   |
| SAGE                | 1         | 1      | 0.06%   |
| QNAP                | 1         | 2      | 0.06%   |
| PHD 3.0             | 1         | 1      | 0.06%   |
| Maxone              | 1         | 1      | 0.06%   |
| IBM                 | 1         | 1      | 0.06%   |
| Hewlett-Packard     | 1         | 1      | 0.06%   |
| ASMT109x            | 1         | 1      | 0.06%   |
| Apple               | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 322       | 406    | 20.68%  |
| Kingston            | 203       | 257    | 13.04%  |
| SanDisk             | 176       | 217    | 11.3%   |
| Crucial             | 163       | 202    | 10.47%  |
| Apple               | 88        | 92     | 5.65%   |
| A-DATA Technology   | 85        | 155    | 5.46%   |
| WDC                 | 60        | 78     | 3.85%   |
| Micron Technology   | 48        | 50     | 3.08%   |
| SK hynix            | 38        | 45     | 2.44%   |
| Intel               | 32        | 36     | 2.06%   |
| Toshiba             | 27        | 29     | 1.73%   |
| China               | 26        | 28     | 1.67%   |
| Transcend           | 24        | 30     | 1.54%   |
| LITEON              | 23        | 27     | 1.48%   |
| PNY                 | 15        | 17     | 0.96%   |
| Intenso             | 15        | 19     | 0.96%   |
| Patriot             | 13        | 15     | 0.83%   |
| LITEONIT            | 13        | 15     | 0.83%   |
| SPCC                | 12        | 15     | 0.77%   |
| Team                | 10        | 12     | 0.64%   |
| OCZ                 | 10        | 12     | 0.64%   |
| GOODRAM             | 8         | 10     | 0.51%   |
| Plextor             | 7         | 7      | 0.45%   |
| LDLC                | 7         | 7      | 0.45%   |
| KingSpec            | 7         | 7      | 0.45%   |
| Netac               | 6         | 10     | 0.39%   |
| Seagate             | 5         | 5      | 0.32%   |
| Lexar               | 5         | 6      | 0.32%   |
| KingDian            | 5         | 5      | 0.32%   |
| JMicron Technology  | 5         | 5      | 0.32%   |
| Corsair             | 5         | 5      | 0.32%   |
| Unknown             | 5         | 5      | 0.32%   |
| Hewlett-Packard     | 4         | 4      | 0.26%   |
| Dogfish             | 4         | 5      | 0.26%   |
| BIWIN               | 4         | 4      | 0.26%   |
| ASUS-PHISON         | 4         | 5      | 0.26%   |
| Apacer              | 4         | 4      | 0.26%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.19%   |
| Kingchuxing         | 3         | 3      | 0.19%   |
| Gigabyte Technology | 3         | 3      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1570      | 1814   | 34.19%  |
| SSD     | 1455      | 1942   | 31.69%  |
| NVMe    | 1189      | 1535   | 25.89%  |
| MMC     | 338       | 429    | 7.36%   |
| Unknown | 40        | 45     | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2747      | 3645   | 62.56%  |
| NVMe | 1177      | 1514   | 26.8%   |
| MMC  | 338       | 429    | 7.7%    |
| SAS  | 129       | 177    | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2132      | 2642   | 71.4%   |
| 0.51-1.0   | 774       | 1008   | 25.92%  |
| 1.01-2.0   | 59        | 72     | 1.98%   |
| 4.01-10.0  | 12        | 15     | 0.4%    |
| 3.01-4.0   | 5         | 13     | 0.17%   |
| 2.01-3.0   | 3         | 4      | 0.1%    |
| 20.01-50.0 | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1174      | 28.42%  |
| 251-500        | 835       | 20.21%  |
| Unknown        | 694       | 16.8%   |
| 501-1000       | 516       | 12.49%  |
| 51-100         | 263       | 6.37%   |
| 1-20           | 210       | 5.08%   |
| 1001-2000      | 206       | 4.99%   |
| 21-50          | 142       | 3.44%   |
| 2001-3000      | 51        | 1.23%   |
| More than 3000 | 40        | 0.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1468      | 34.48%  |
| Unknown        | 694       | 16.3%   |
| 21-50          | 546       | 12.83%  |
| 101-250        | 536       | 12.59%  |
| 51-100         | 442       | 10.38%  |
| 251-500        | 300       | 7.05%   |
| 501-1000       | 171       | 4.02%   |
| 1001-2000      | 62        | 1.46%   |
| More than 3000 | 15        | 0.35%   |
| 2001-3000      | 12        | 0.28%   |
| 0              | 11        | 0.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB        | 20        | 20     | 5.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 10        | 12     | 2.51%   |
| Toshiba MK1653GSX 160GB               | 9         | 9      | 2.26%   |
| Seagate ST9500325AS 500GB             | 8         | 8      | 2.01%   |
| Toshiba MK1655GSXF 160GB              | 7         | 7      | 1.75%   |
| Seagate ST9500420AS 500GB             | 6         | 6      | 1.5%    |
| Hitachi HTS545050B9A300 500GB         | 6         | 6      | 1.5%    |
| Hitachi HTS543216L9SA02 160GB         | 6         | 6      | 1.5%    |
| Toshiba MQ01ABD100 1TB                | 5         | 5      | 1.25%   |
| Seagate ST1000LM035-1RK172 1TB        | 5         | 5      | 1.25%   |
| Hitachi HTS542512K9SA00 120GB         | 5         | 6      | 1.25%   |
| HGST HTS725050A7E630 500GB            | 5         | 5      | 1.25%   |
| WDC WD1600BUDT-63DPZY0 160GB          | 4         | 4      | 1%      |
| Toshiba MQ01ABF050 500GB              | 4         | 4      | 1%      |
| Seagate ST500LT012-9WS142 500GB       | 4         | 5      | 1%      |
| Seagate ST500LM021-1KJ152 500GB       | 4         | 4      | 1%      |
| Seagate ST500LM000-SSHD-8GB           | 4         | 4      | 1%      |
| Seagate ST320LT007-9ZV142 320GB       | 4         | 6      | 1%      |
| Hitachi HTS547575A9E384 752GB         | 4         | 4      | 1%      |
| Toshiba MQ04ABF100 1TB                | 3         | 3      | 0.75%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 3         | 3      | 0.75%   |
| SK hynix HFS256G39MND-2300A 256GB SSD | 3         | 4      | 0.75%   |
| Seagate ST9320325AS 320GB             | 3         | 3      | 0.75%   |
| Seagate ST9250315AS 250GB             | 3         | 4      | 0.75%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 0.75%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 3      | 0.75%   |
| Hitachi HTS547550A9E384 500GB         | 3         | 3      | 0.75%   |
| Hitachi HTS542516K9SA00 160GB         | 3         | 3      | 0.75%   |
| HGST HTS721010A9E630 1TB              | 3         | 4      | 0.75%   |
| HGST HTS541010A9E680 1TB              | 3         | 3      | 0.75%   |
| Crucial CT275MX300SSD1 275GB          | 3         | 3      | 0.75%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 2         | 2      | 0.5%    |
| WDC WD7500BPKT-75PK4T0 752GB          | 2         | 2      | 0.5%    |
| WDC WD10SPZX-60Z10T0 1TB              | 2         | 3      | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 2      | 0.5%    |
| WDC WD10JPCX-24UE4T0 1TB              | 2         | 3      | 0.5%    |
| Toshiba MQ01ACF050 500GB              | 2         | 2      | 0.5%    |
| Toshiba MQ01ABD050 500GB              | 2         | 2      | 0.5%    |
| SK hynix HFS256G39TND-N210A 256GB SSD | 2         | 2      | 0.5%    |
| Seagate ST980811AS 80GB               | 2         | 2      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 93     | 21.36%  |
| Hitachi             | 61        | 66     | 15.33%  |
| Toshiba             | 48        | 49     | 12.06%  |
| WDC                 | 40        | 42     | 10.05%  |
| Fujitsu             | 34        | 34     | 8.54%   |
| Samsung Electronics | 21        | 23     | 5.28%   |
| HGST                | 21        | 22     | 5.28%   |
| SK hynix            | 15        | 16     | 3.77%   |
| Micron Technology   | 10        | 10     | 2.51%   |
| Kingston            | 10        | 11     | 2.51%   |
| SanDisk             | 9         | 11     | 2.26%   |
| Intel               | 9         | 10     | 2.26%   |
| Crucial             | 7         | 8      | 1.76%   |
| A-DATA Technology   | 7         | 8      | 1.76%   |
| LITEONIT            | 3         | 4      | 0.75%   |
| LITEON              | 3         | 3      | 0.75%   |
| IBM/Hitachi         | 2         | 2      | 0.5%    |
| Corsair             | 2         | 2      | 0.5%    |
| Team                | 1         | 1      | 0.25%   |
| ShiJi               | 1         | 1      | 0.25%   |
| Lenovo              | 1         | 1      | 0.25%   |
| KingSpec            | 1         | 1      | 0.25%   |
| KingDian            | 1         | 1      | 0.25%   |
| IBM                 | 1         | 1      | 0.25%   |
| GOODRAM             | 1         | 1      | 0.25%   |
| DGM                 | 1         | 1      | 0.25%   |
| China               | 1         | 1      | 0.25%   |
| Apple               | 1         | 1      | 0.25%   |
| Unknown             | 1         | 1      | 0.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 93     | 28.24%  |
| Hitachi             | 61        | 66     | 20.27%  |
| Toshiba             | 47        | 48     | 15.61%  |
| WDC                 | 39        | 41     | 12.96%  |
| Fujitsu             | 34        | 34     | 11.3%   |
| HGST                | 21        | 22     | 6.98%   |
| Samsung Electronics | 11        | 11     | 3.65%   |
| IBM/Hitachi         | 2         | 2      | 0.66%   |
| IBM                 | 1         | 1      | 0.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 298       | 318    | 75.44%  |
| SSD  | 85        | 95     | 21.52%  |
| NVMe | 12        | 12     | 3.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 14.29%  |
| Toshiba MK6465GSX 640GB                         | 1         | 1      | 14.29%  |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 14.29%  |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 14.29%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 14.29%  |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 14.29%  |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 28.57%  |
| Samsung Electronics | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 2      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2696      | 3565   | 62.83%  |
| Detected | 1195      | 1766   | 27.85%  |
| Malfunc  | 392       | 425    | 9.14%   |
| Failed   | 7         | 8      | 0.16%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2423      | 55.16%  |
| Samsung Electronics              | 417       | 9.49%   |
| AMD                              | 378       | 8.6%    |
| Nvidia                           | 326       | 7.42%   |
| SanDisk                          | 204       | 4.64%   |
| SK hynix                         | 134       | 3.05%   |
| Apple                            | 82        | 1.87%   |
| Toshiba America Info Systems     | 75        | 1.71%   |
| Micron Technology                | 55        | 1.25%   |
| Kingston Technology Company      | 51        | 1.16%   |
| KIOXIA                           | 41        | 0.93%   |
| Phison Electronics               | 36        | 0.82%   |
| ADATA Technology                 | 35        | 0.8%    |
| Silicon Motion                   | 31        | 0.71%   |
| Micron/Crucial Technology        | 26        | 0.59%   |
| Solid State Storage Technology   | 14        | 0.32%   |
| Union Memory (Shenzhen)          | 11        | 0.25%   |
| Silicon Integrated Systems [SiS] | 11        | 0.25%   |
| Lite-On Technology               | 6         | 0.14%   |
| Shenzhen Longsys Electronics     | 5         | 0.11%   |
| Realtek Semiconductor            | 5         | 0.11%   |
| Lenovo                           | 5         | 0.11%   |
| Silicon Image                    | 3         | 0.07%   |
| Seagate Technology               | 3         | 0.07%   |
| Unknown                          | 3         | 0.07%   |
| VIA Technologies                 | 2         | 0.05%   |
| ULi Electronics                  | 2         | 0.05%   |
| Marvell Technology Group         | 2         | 0.05%   |
| ASMedia Technology               | 2         | 0.05%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| JMicron Technology               | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |
| Adaptec                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 331       | 7.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 321       | 6.81%   |
| Nvidia MCP79 AHCI Controller                                                   | 312       | 6.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 263       | 5.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 186       | 3.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 181       | 3.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 175       | 3.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 123       | 2.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 104       | 2.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 100       | 2.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 98        | 2.08%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 93        | 1.97%   |
| Samsung NVMe SSD Controller 980                                                | 86        | 1.82%   |
| Samsung Electronics SATA controller                                            | 79        | 1.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 79        | 1.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 78        | 1.65%   |
| Apple S1X NVMe Controller                                                      | 76        | 1.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 74        | 1.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 71        | 1.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 71        | 1.51%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 68        | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 66        | 1.4%    |
| Micron Non-Volatile memory controller                                          | 55        | 1.17%   |
| Intel Comet Lake SATA AHCI Controller                                          | 55        | 1.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 53        | 1.12%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 51        | 1.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 46        | 0.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 46        | 0.98%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 46        | 0.98%   |
| Intel Tiger Lake-LP SATA Controller                                            | 45        | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 44        | 0.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 43        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 43        | 0.91%   |
| Intel SSD 660P Series                                                          | 40        | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 37        | 0.79%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 34        | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 31        | 0.66%   |
| SanDisk Non-Volatile memory controller                                         | 30        | 0.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 30        | 0.64%   |
| SK hynix BC511                                                                 | 29        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2776      | 60.43%  |
| NVMe | 1185      | 25.79%  |
| IDE  | 341       | 7.42%   |
| RAID | 291       | 6.33%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3446      | 86.15%  |
| AMD          | 539       | 13.48%  |
| ARM          | 10        | 0.25%   |
| CentaurHauls | 3         | 0.08%   |
| Unknown      | 2         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 308       | 7.69%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 143       | 3.57%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 89        | 2.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 68        | 1.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 67        | 1.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 66        | 1.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 60        | 1.5%    |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 60        | 1.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 59        | 1.47%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 58        | 1.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 56        | 1.4%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 50        | 1.25%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 47        | 1.17%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 47        | 1.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 45        | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 44        | 1.1%    |
| Intel Core i3-9100 CPU @ 3.60GHz              | 44        | 1.1%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 43        | 1.07%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 37        | 0.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 37        | 0.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 34        | 0.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 34        | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 30        | 0.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 28        | 0.7%    |
| Intel Atom CPU N270 @ 1.60GHz                 | 28        | 0.7%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 28        | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 27        | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 27        | 0.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 26        | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 25        | 0.62%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 24        | 0.6%    |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.6%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 23        | 0.57%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 23        | 0.57%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.55%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 22        | 0.55%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 21        | 0.52%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 20        | 0.5%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 20        | 0.5%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 20        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 993       | 24.82%  |
| Intel Core i7           | 773       | 19.32%  |
| Intel Core 2 Duo        | 473       | 11.82%  |
| Intel Celeron           | 295       | 7.37%   |
| Other                   | 276       | 6.9%    |
| Intel Core i3           | 258       | 6.45%   |
| AMD Ryzen 5             | 155       | 3.87%   |
| Intel Atom              | 119       | 2.97%   |
| AMD Ryzen 7             | 85        | 2.12%   |
| Intel Pentium           | 76        | 1.9%    |
| Intel Core 2            | 68        | 1.7%    |
| AMD Ryzen 7 PRO         | 40        | 1%      |
| Intel Pentium M         | 30        | 0.75%   |
| AMD A6                  | 28        | 0.7%    |
| Intel Pentium Dual-Core | 22        | 0.55%   |
| AMD A4                  | 22        | 0.55%   |
| Intel Genuine           | 20        | 0.5%    |
| AMD Ryzen 3             | 20        | 0.5%    |
| Intel Pentium Dual      | 19        | 0.47%   |
| AMD A8                  | 18        | 0.45%   |
| AMD E1                  | 16        | 0.4%    |
| AMD Ryzen 5 PRO         | 14        | 0.35%   |
| AMD Ryzen 9             | 13        | 0.32%   |
| Intel Celeron M         | 12        | 0.3%    |
| AMD A10                 | 11        | 0.27%   |
| AMD E2                  | 10        | 0.25%   |
| AMD E                   | 10        | 0.25%   |
| Intel Pentium 4         | 9         | 0.22%   |
| Intel Pentium Silver    | 8         | 0.2%    |
| Intel Core i9           | 8         | 0.2%    |
| Intel Core m3           | 7         | 0.17%   |
| AMD A12                 | 7         | 0.17%   |
| AMD Athlon              | 6         | 0.15%   |
| Intel Xeon              | 5         | 0.12%   |
| Intel Celeron Dual-Core | 5         | 0.12%   |
| ARM ARMv7               | 5         | 0.12%   |
| AMD Turion 64 X2 Mobile | 5         | 0.12%   |
| AMD C-60                | 5         | 0.12%   |
| Intel Mobile Pentium 4  | 4         | 0.1%    |
| Intel Pentium III       | 3         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2260      | 56.47%  |
| 4      | 1166      | 29.14%  |
| 6      | 203       | 5.07%   |
| 1      | 183       | 4.57%   |
| 8      | 151       | 3.77%   |
| 14     | 17        | 0.42%   |
| 12     | 12        | 0.3%    |
| 10     | 9         | 0.22%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3998      | 99.97%  |
| 2      | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2625      | 65.63%  |
| 1      | 1374      | 34.35%  |
| 4      | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3820      | 95.48%  |
| 32-bit         | 108       | 2.7%    |
| Unknown        | 71        | 1.77%   |
| 64-bit         | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 864       | 21.12%  |
| 0x1067a    | 389       | 9.51%   |
| 0x306d4    | 234       | 5.72%   |
| 0x306a9    | 184       | 4.5%    |
| 0x206a7    | 178       | 4.35%   |
| 0x806ec    | 161       | 3.94%   |
| 0x806c1    | 138       | 3.37%   |
| 0x806e9    | 113       | 2.76%   |
| 0x30678    | 112       | 2.74%   |
| 0x806ea    | 108       | 2.64%   |
| 0x40651    | 98        | 2.4%    |
| 0x406e3    | 92        | 2.25%   |
| 0x906ea    | 67        | 1.64%   |
| 0x6f6      | 64        | 1.56%   |
| 0x306c3    | 62        | 1.52%   |
| 0xa0652    | 58        | 1.42%   |
| 0x406c4    | 58        | 1.42%   |
| 0x20655    | 56        | 1.37%   |
| 0x08600106 | 47        | 1.15%   |
| 0x08108109 | 46        | 1.12%   |
| 0x0a50000c | 45        | 1.1%    |
| 0x906eb    | 44        | 1.08%   |
| 0x10676    | 43        | 1.05%   |
| 0x706e5    | 41        | 1%      |
| 0x08108102 | 39        | 0.95%   |
| 0x08608103 | 35        | 0.86%   |
| 0x6fd      | 34        | 0.83%   |
| 0x806eb    | 32        | 0.78%   |
| 0x106ca    | 32        | 0.78%   |
| 0x106c2    | 31        | 0.76%   |
| 0x0600611a | 30        | 0.73%   |
| 0x906e9    | 29        | 0.71%   |
| 0x506e3    | 29        | 0.71%   |
| 0x906a3    | 28        | 0.68%   |
| 0x706a8    | 27        | 0.66%   |
| 0x6d8      | 25        | 0.61%   |
| 0x506c9    | 24        | 0.59%   |
| 0x06006705 | 24        | 0.59%   |
| 0x20652    | 22        | 0.54%   |
| 0x406c3    | 19        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 750       | 18.74%  |
| Penryn           | 466       | 11.64%  |
| Broadwell        | 262       | 6.55%   |
| IvyBridge        | 257       | 6.42%   |
| SandyBridge      | 245       | 6.12%   |
| Haswell          | 223       | 5.57%   |
| Silvermont       | 215       | 5.37%   |
| Skylake          | 176       | 4.4%    |
| TigerLake        | 171       | 4.27%   |
| Core             | 138       | 3.45%   |
| Zen+             | 108       | 2.7%    |
| Westmere         | 107       | 2.67%   |
| Zen 2            | 93        | 2.32%   |
| CometLake        | 79        | 1.97%   |
| Bonnell          | 79        | 1.97%   |
| Unknown          | 76        | 1.9%    |
| Excavator        | 75        | 1.87%   |
| Icelake          | 60        | 1.5%    |
| P6               | 59        | 1.47%   |
| Zen 3            | 55        | 1.37%   |
| Goldmont plus    | 49        | 1.22%   |
| Zen              | 34        | 0.85%   |
| Goldmont         | 33        | 0.82%   |
| Bobcat           | 29        | 0.72%   |
| Alderlake Hybrid | 29        | 0.72%   |
| Puma             | 23        | 0.57%   |
| K8 Hammer        | 16        | 0.4%    |
| K10 Llano        | 16        | 0.4%    |
| Jaguar           | 16        | 0.4%    |
| NetBurst         | 14        | 0.35%   |
| Nehalem          | 12        | 0.3%    |
| Piledriver       | 11        | 0.27%   |
| Tremont          | 8         | 0.2%    |
| K10              | 8         | 0.2%    |
| Steamroller      | 6         | 0.15%   |
| K8 & K10 hybrid  | 5         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2902      | 60.45%  |
| Nvidia                           | 1125      | 23.43%  |
| AMD                              | 760       | 15.83%  |
| Silicon Integrated Systems [SiS] | 7         | 0.15%   |
| Zhaoxin                          | 2         | 0.04%   |
| VIA Technologies                 | 2         | 0.04%   |
| S3 Graphics                      | 2         | 0.04%   |
| Neomagic                         | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 306       | 6.09%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 237       | 4.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 218       | 4.34%   |
| Intel UHD Graphics 620                                                                   | 166       | 3.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 156       | 3.1%    |
| Intel HD Graphics 6000                                                                   | 150       | 2.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 130       | 2.59%   |
| Intel HD Graphics 620                                                                    | 128       | 2.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 128       | 2.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 126       | 2.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 123       | 2.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 111       | 2.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 111       | 2.21%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 106       | 2.11%   |
| Intel HD Graphics 5500                                                                   | 102       | 2.03%   |
| AMD Renoir                                                                               | 92        | 1.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 88        | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 86        | 1.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 82        | 1.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 81        | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 78        | 1.55%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 74        | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 70        | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 70        | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 63        | 1.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 50        | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 45        | 0.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 0.88%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 42        | 0.84%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 41        | 0.82%   |
| AMD Lucienne                                                                             | 41        | 0.82%   |
| Intel HD Graphics 630                                                                    | 40        | 0.8%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 39        | 0.78%   |
| Intel HD Graphics 530                                                                    | 37        | 0.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 33        | 0.66%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 33        | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 32        | 0.64%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 32        | 0.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 31        | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 29        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2141      | 53.43%  |
| Intel + Nvidia     | 622       | 15.52%  |
| 1 x AMD            | 529       | 13.2%   |
| 1 x Nvidia         | 449       | 11.21%  |
| Intel + AMD        | 132       | 3.29%   |
| AMD + Nvidia       | 54        | 1.35%   |
| 2 x AMD            | 45        | 1.12%   |
| Other              | 18        | 0.45%   |
| 1 x SiS            | 7         | 0.17%   |
| 1 x Zhaoxin        | 2         | 0.05%   |
| 1 x VIA            | 2         | 0.05%   |
| 1 x S3 Graphics    | 2         | 0.05%   |
| Intel + 2 x Nvidia | 2         | 0.05%   |
| 2 x Nvidia         | 1         | 0.02%   |
| 1 x Neomagic       | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3486      | 86.48%  |
| Proprietary | 290       | 7.19%   |
| Unknown     | 255       | 6.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 2932      | 72.38%  |
| 0.01-0.5       | 621       | 15.33%  |
| 1.01-2.0       | 219       | 5.41%   |
| 3.01-4.0       | 113       | 2.79%   |
| 0.51-1.0       | 113       | 2.79%   |
| 5.01-6.0       | 25        | 0.62%   |
| 7.01-8.0       | 20        | 0.49%   |
| 2.01-3.0       | 6         | 0.15%   |
| More than 64.0 | 1         | 0.02%   |
| 8.01-16.0      | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 775       | 17.81%  |
| Apple                   | 579       | 13.3%   |
| BOE                     | 557       | 12.8%   |
| LG Display              | 522       | 11.99%  |
| Chimei Innolux          | 469       | 10.78%  |
| Samsung Electronics     | 350       | 8.04%   |
| Dell                    | 118       | 2.71%   |
| Lenovo                  | 105       | 2.41%   |
| Sharp                   | 90        | 2.07%   |
| Goldstar                | 90        | 2.07%   |
| Chi Mei Optoelectronics | 69        | 1.59%   |
| Hewlett-Packard         | 53        | 1.22%   |
| InfoVision              | 51        | 1.17%   |
| BenQ                    | 42        | 0.97%   |
| PANDA                   | 41        | 0.94%   |
| Philips                 | 36        | 0.83%   |
| AOC                     | 32        | 0.74%   |
| HannStar                | 31        | 0.71%   |
| Iiyama                  | 29        | 0.67%   |
| Ancor Communications    | 28        | 0.64%   |
| LG Philips              | 27        | 0.62%   |
| Acer                    | 27        | 0.62%   |
| CSO                     | 22        | 0.51%   |
| Unknown                 | 19        | 0.44%   |
| ViewSonic               | 16        | 0.37%   |
| Sony                    | 16        | 0.37%   |
| CPT                     | 15        | 0.34%   |
| Eizo                    | 13        | 0.3%    |
| Quanta Display          | 8         | 0.18%   |
| NEC Computers           | 7         | 0.16%   |
| ASUSTek Computer        | 7         | 0.16%   |
| Panasonic               | 6         | 0.14%   |
| Pixio                   | 4         | 0.09%   |
| MSI                     | 4         | 0.09%   |
| InnoLux Display         | 4         | 0.09%   |
| AGO                     | 4         | 0.09%   |
| Toshiba                 | 3         | 0.07%   |
| TMX                     | 3         | 0.07%   |
| SLD                     | 3         | 0.07%   |
| RTK                     | 3         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 200       | 4.54%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 152       | 3.45%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 52        | 1.18%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 43        | 0.98%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 43        | 0.98%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 40        | 0.91%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 39        | 0.89%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 35        | 0.79%   |
| BOE LCD Monitor BOE06B3 1920x1080 310x170mm 13.9-inch                | 29        | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 27        | 0.61%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 26        | 0.59%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 25        | 0.57%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 23        | 0.52%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 23        | 0.52%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 22        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 22        | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 21        | 0.48%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 21        | 0.48%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 17        | 0.39%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 16        | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 16        | 0.36%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.34%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 15        | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 14        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 14        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 14        | 0.32%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 14        | 0.32%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 14        | 0.32%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 14        | 0.32%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 12        | 0.27%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 11        | 0.25%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                 | 11        | 0.25%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 10        | 0.23%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 10        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 10        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1517      | 36.91%  |
| 1366x768 (WXGA)    | 1152      | 28.03%  |
| 1280x800 (WXGA)    | 505       | 12.29%  |
| 1600x900 (HD+)     | 175       | 4.26%   |
| 1440x900 (WXGA+)   | 128       | 3.11%   |
| 3840x2160 (4K)     | 120       | 2.92%   |
| 2560x1440 (QHD)    | 92        | 2.24%   |
| 1920x1200 (WUXGA)  | 83        | 2.02%   |
| 1024x600           | 61        | 1.48%   |
| 1280x1024 (SXGA)   | 33        | 0.8%    |
| 2560x1600          | 28        | 0.68%   |
| 1680x1050 (WSXGA+) | 28        | 0.68%   |
| 2560x1080          | 22        | 0.54%   |
| 1360x768           | 21        | 0.51%   |
| 1024x768 (XGA)     | 17        | 0.41%   |
| 2288x1287          | 16        | 0.39%   |
| 3840x2400          | 15        | 0.36%   |
| 2880x1800          | 14        | 0.34%   |
| 3440x1440          | 13        | 0.32%   |
| 3200x1800 (QHD+)   | 9         | 0.22%   |
| 2160x1440          | 8         | 0.19%   |
| 1600x1200          | 6         | 0.15%   |
| 3840x1080          | 5         | 0.12%   |
| Unknown            | 5         | 0.12%   |
| 1400x1050          | 4         | 0.1%    |
| 3840x1100          | 3         | 0.07%   |
| 2256x1504          | 3         | 0.07%   |
| 2240x1400          | 3         | 0.07%   |
| 1280x720 (HD)      | 3         | 0.07%   |
| 3840x1200          | 2         | 0.05%   |
| 2880x1920          | 2         | 0.05%   |
| 2304x1440          | 2         | 0.05%   |
| 1920x1280          | 2         | 0.05%   |
| 800x1280           | 1         | 0.02%   |
| 7680x2160          | 1         | 0.02%   |
| 640x480            | 1         | 0.02%   |
| 3840x1600          | 1         | 0.02%   |
| 2520x1680          | 1         | 0.02%   |
| 2048x1152          | 1         | 0.02%   |
| 1920x540           | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1320      | 30.32%  |
| 13      | 1011      | 23.23%  |
| 14      | 537       | 12.34%  |
| 11      | 261       | 6%      |
| 17      | 235       | 5.4%    |
| 12      | 162       | 3.72%   |
| 24      | 146       | 3.35%   |
| 27      | 118       | 2.71%   |
| 23      | 107       | 2.46%   |
| 21      | 90        | 2.07%   |
| 10      | 60        | 1.38%   |
| 18      | 38        | 0.87%   |
| Unknown | 36        | 0.83%   |
| 34      | 29        | 0.67%   |
| 19      | 29        | 0.67%   |
| 31      | 20        | 0.46%   |
| 16      | 20        | 0.46%   |
| 22      | 17        | 0.39%   |
| 142     | 16        | 0.37%   |
| 25      | 15        | 0.34%   |
| 20      | 12        | 0.28%   |
| 72      | 9         | 0.21%   |
| 32      | 9         | 0.21%   |
| 54      | 6         | 0.14%   |
| 29      | 6         | 0.14%   |
| 8       | 6         | 0.14%   |
| 40      | 5         | 0.11%   |
| 84      | 4         | 0.09%   |
| 46      | 4         | 0.09%   |
| 28      | 4         | 0.09%   |
| 52      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |
| 43      | 3         | 0.07%   |
| 49      | 2         | 0.05%   |
| 33      | 2         | 0.05%   |
| 26      | 2         | 0.05%   |
| 58      | 1         | 0.02%   |
| 55      | 1         | 0.02%   |
| 47      | 1         | 0.02%   |
| 39      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2150      | 49.85%  |
| 201-300        | 1178      | 27.31%  |
| 501-600        | 353       | 8.18%   |
| 351-400        | 276       | 6.4%    |
| 401-500        | 168       | 3.9%    |
| 601-700        | 46        | 1.07%   |
| 701-800        | 39        | 0.9%    |
| Unknown        | 36        | 0.83%   |
| 1001-1500      | 23        | 0.53%   |
| More than 2000 | 16        | 0.37%   |
| 1501-2000      | 13        | 0.3%    |
| 801-900        | 7         | 0.16%   |
| 101-200        | 7         | 0.16%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2904      | 74.81%  |
| 16/10   | 805       | 20.74%  |
| 4/3     | 33        | 0.85%   |
| 5/4     | 32        | 0.82%   |
| 21/9    | 32        | 0.82%   |
| 3/2     | 25        | 0.64%   |
| Unknown | 19        | 0.49%   |
| 1.00    | 16        | 0.41%   |
| 32/9    | 5         | 0.13%   |
| 2.65    | 4         | 0.1%    |
| 3.40    | 3         | 0.08%   |
| 3.20    | 2         | 0.05%   |
| 3.73    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1319      | 30.4%   |
| 81-90          | 1280      | 29.5%   |
| 201-250        | 278       | 6.41%   |
| 71-80          | 265       | 6.11%   |
| 51-60          | 264       | 6.08%   |
| 121-130        | 188       | 4.33%   |
| 61-70          | 156       | 3.6%    |
| 301-350        | 119       | 2.74%   |
| 251-300        | 69        | 1.59%   |
| 351-500        | 65        | 1.5%    |
| 151-200        | 63        | 1.45%   |
| 41-50          | 60        | 1.38%   |
| 141-150        | 54        | 1.24%   |
| More than 1000 | 41        | 0.94%   |
| Unknown        | 36        | 0.83%   |
| 131-140        | 28        | 0.65%   |
| 501-1000       | 18        | 0.41%   |
| 91-100         | 16        | 0.37%   |
| 111-120        | 13        | 0.3%    |
| 1-40           | 7         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1771      | 41.63%  |
| 101-120       | 1456      | 34.23%  |
| 51-100        | 607       | 14.27%  |
| 161-240       | 253       | 5.95%   |
| More than 240 | 81        | 1.9%    |
| 1-50          | 50        | 1.18%   |
| Unknown       | 36        | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3179      | 77.84%  |
| 2     | 594       | 14.54%  |
| 0     | 241       | 5.9%    |
| 3     | 68        | 1.67%   |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1981      | 30.73%  |
| Realtek Semiconductor             | 1733      | 26.88%  |
| Qualcomm Atheros                  | 863       | 13.39%  |
| Broadcom                          | 623       | 9.66%   |
| Nvidia                            | 322       | 4.99%   |
| Broadcom Limited                  | 235       | 3.65%   |
| Marvell Technology Group          | 139       | 2.16%   |
| Ralink                            | 55        | 0.85%   |
| MediaTek                          | 47        | 0.73%   |
| ASIX Electronics                  | 39        | 0.6%    |
| TP-Link                           | 35        | 0.54%   |
| Dell                              | 31        | 0.48%   |
| Lenovo                            | 27        | 0.42%   |
| Samsung Electronics               | 25        | 0.39%   |
| JMicron Technology                | 25        | 0.39%   |
| Sierra Wireless                   | 24        | 0.37%   |
| Ralink Technology                 | 19        | 0.29%   |
| Ericsson Business Mobile Networks | 19        | 0.29%   |
| Qualcomm                          | 16        | 0.25%   |
| Huawei Technologies               | 15        | 0.23%   |
| DisplayLink                       | 15        | 0.23%   |
| Xiaomi                            | 14        | 0.22%   |
| Fibocom                           | 13        | 0.2%    |
| Hewlett-Packard                   | 11        | 0.17%   |
| Silicon Integrated Systems [SiS]  | 10        | 0.16%   |
| Qualcomm Atheros Communications   | 8         | 0.12%   |
| Cypress Semiconductor             | 8         | 0.12%   |
| NetGear                           | 6         | 0.09%   |
| ICS Advent                        | 6         | 0.09%   |
| Attansic Technology               | 6         | 0.09%   |
| ASUSTek Computer                  | 6         | 0.09%   |
| Apple                             | 5         | 0.08%   |
| AMD                               | 5         | 0.08%   |
| OPPO Electronics                  | 4         | 0.06%   |
| Motorola PCS                      | 4         | 0.06%   |
| Microchip Technology              | 4         | 0.06%   |
| U-Blox                            | 3         | 0.05%   |
| Edimax Technology                 | 3         | 0.05%   |
| 3Com                              | 3         | 0.05%   |
| Wilocity                          | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1065      | 13.94%  |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 313       | 4.1%    |
| Nvidia MCP79 Ethernet                                                                 | 312       | 4.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 310       | 4.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 180       | 2.36%   |
| Intel Wireless 7260                                                                   | 178       | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 158       | 2.07%   |
| Intel Wireless 8265 / 8275                                                            | 156       | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 155       | 2.03%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 155       | 2.03%   |
| Intel Wi-Fi 6 AX200                                                                   | 151       | 1.98%   |
| Intel Wireless 7265                                                                   | 149       | 1.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 135       | 1.77%   |
| Intel Wi-Fi 6 AX201                                                                   | 119       | 1.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 109       | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 104       | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 101       | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 99        | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 93        | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 87        | 1.14%   |
| Intel Wireless 8260                                                                   | 85        | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 83        | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 81        | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 68        | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 65        | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 59        | 0.77%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 58        | 0.76%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 0.75%   |
| Intel Ethernet Connection (4) I219-V                                                  | 53        | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 53        | 0.69%   |
| Intel Wireless 3165                                                                   | 52        | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 48        | 0.63%   |
| Intel Ethernet Connection I219-LM                                                     | 47        | 0.62%   |
| Intel Ethernet Connection I218-LM                                                     | 45        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 45        | 0.59%   |
| Intel Wireless-AC 9260                                                                | 39        | 0.51%   |
| Intel 82577LM Gigabit Network Connection                                              | 39        | 0.51%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 39        | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 38        | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 38        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1873      | 45.95%  |
| Qualcomm Atheros                | 773       | 18.96%  |
| Broadcom                        | 530       | 13%     |
| Realtek Semiconductor           | 460       | 11.29%  |
| Broadcom Limited                | 203       | 4.98%   |
| Ralink                          | 55        | 1.35%   |
| MediaTek                        | 45        | 1.1%    |
| Sierra Wireless                 | 24        | 0.59%   |
| TP-Link                         | 19        | 0.47%   |
| Ralink Technology               | 19        | 0.47%   |
| Dell                            | 17        | 0.42%   |
| Fibocom                         | 12        | 0.29%   |
| Qualcomm Atheros Communications | 8         | 0.2%    |
| Qualcomm                        | 6         | 0.15%   |
| NetGear                         | 6         | 0.15%   |
| ASUSTek Computer                | 6         | 0.15%   |
| Hewlett-Packard                 | 4         | 0.1%    |
| Edimax Technology               | 3         | 0.07%   |
| Wilocity                        | 2         | 0.05%   |
| D-Link System                   | 2         | 0.05%   |
| Belkin Components               | 2         | 0.05%   |
| 3Com                            | 2         | 0.05%   |
| ZyXEL Communications            | 1         | 0.02%   |
| Z-Com                           | 1         | 0.02%   |
| Quectel Wireless Solutions      | 1         | 0.02%   |
| Microsoft                       | 1         | 0.02%   |
| Cinterion                       | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 313       | 7.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 180       | 4.39%   |
| Intel Wireless 7260                                                                   | 178       | 4.35%   |
| Intel Wireless 8265 / 8275                                                            | 156       | 3.81%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 155       | 3.78%   |
| Intel Wi-Fi 6 AX200                                                                   | 151       | 3.69%   |
| Intel Wireless 7265                                                                   | 149       | 3.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 135       | 3.3%    |
| Intel Wi-Fi 6 AX201                                                                   | 119       | 2.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 109       | 2.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 104       | 2.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 101       | 2.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 99        | 2.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 93        | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 87        | 2.12%   |
| Intel Wireless 8260                                                                   | 85        | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 83        | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 81        | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 68        | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 65        | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 59        | 1.44%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 53        | 1.29%   |
| Intel Wireless 3165                                                                   | 52        | 1.27%   |
| Intel Wireless-AC 9260                                                                | 39        | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 39        | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 38        | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 38        | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 38        | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 37        | 0.9%    |
| Intel Wireless 3160                                                                   | 35        | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 35        | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 33        | 0.81%   |
| Intel Centrino Ultimate-N 6300                                                        | 33        | 0.81%   |
| Intel Centrino Advanced-N 6200                                                        | 30        | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 28        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 28        | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 28        | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 26        | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 25        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1568      | 46.17%  |
| Intel                            | 779       | 22.94%  |
| Nvidia                           | 322       | 9.48%   |
| Qualcomm Atheros                 | 187       | 5.51%   |
| Marvell Technology Group         | 139       | 4.09%   |
| Broadcom                         | 121       | 3.56%   |
| ASIX Electronics                 | 39        | 1.15%   |
| Broadcom Limited                 | 35        | 1.03%   |
| Lenovo                           | 27        | 0.8%    |
| Samsung Electronics              | 25        | 0.74%   |
| JMicron Technology               | 25        | 0.74%   |
| TP-Link                          | 16        | 0.47%   |
| DisplayLink                      | 15        | 0.44%   |
| Xiaomi                           | 14        | 0.41%   |
| Silicon Integrated Systems [SiS] | 10        | 0.29%   |
| Huawei Technologies              | 10        | 0.29%   |
| Qualcomm                         | 9         | 0.27%   |
| Cypress Semiconductor            | 8         | 0.24%   |
| ICS Advent                       | 6         | 0.18%   |
| Attansic Technology              | 6         | 0.18%   |
| Apple                            | 5         | 0.15%   |
| OPPO Electronics                 | 4         | 0.12%   |
| Microchip Technology             | 4         | 0.12%   |
| Motorola PCS                     | 3         | 0.09%   |
| Spreadtrum Communications        | 2         | 0.06%   |
| National Semiconductor           | 2         | 0.06%   |
| MediaTek                         | 2         | 0.06%   |
| LG Electronics                   | 2         | 0.06%   |
| Hewlett-Packard                  | 2         | 0.06%   |
| D-Link                           | 2         | 0.06%   |
| VIA Technologies                 | 1         | 0.03%   |
| MosChip Semiconductor            | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| Google                           | 1         | 0.03%   |
| Foxconn / Hon Hai                | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |
| 3Com                             | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1065      | 31.04%  |
| Nvidia MCP79 Ethernet                                             | 312       | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 310       | 9.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 158       | 4.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 155       | 4.52%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 58        | 1.69%   |
| Intel Ethernet Connection (4) I219-V                              | 53        | 1.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 48        | 1.4%    |
| Intel Ethernet Connection I219-LM                                 | 47        | 1.37%   |
| Intel Ethernet Connection I218-LM                                 | 45        | 1.31%   |
| Intel Ethernet Connection (4) I219-LM                             | 45        | 1.31%   |
| Intel 82577LM Gigabit Network Connection                          | 39        | 1.14%   |
| Intel Ethernet Connection (6) I219-V                              | 37        | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 0.99%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 33        | 0.96%   |
| Intel 82567LM Gigabit Network Connection                          | 32        | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                     | 31        | 0.9%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.73%   |
| Intel Ethernet Connection I219-V                                  | 25        | 0.73%   |
| Intel Ethernet Connection (10) I219-V                             | 24        | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 22        | 0.64%   |
| Intel Ethernet Connection I217-LM                                 | 22        | 0.64%   |
| Intel Ethernet Connection (13) I219-V                             | 22        | 0.64%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 22        | 0.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 20        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 18        | 0.52%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 18        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 16        | 0.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 15        | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 15        | 0.44%   |
| Intel 82579V Gigabit Network Connection                           | 15        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 13        | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 13        | 0.38%   |
| Intel 82566MM Gigabit Network Connection                          | 13        | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 12        | 0.35%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 12        | 0.35%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 12        | 0.35%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 12        | 0.35%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3925      | 53.82%  |
| Ethernet | 3256      | 44.65%  |
| Modem    | 104       | 1.43%   |
| Unknown  | 8         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3075      | 72.97%  |
| Ethernet | 1138      | 27.01%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2950      | 73.64%  |
| 1     | 956       | 23.86%  |
| 0     | 60        | 1.5%    |
| 3     | 38        | 0.95%   |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3463      | 85.53%  |
| Yes  | 586       | 14.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1404      | 43.36%  |
| Apple                           | 569       | 17.57%  |
| Qualcomm Atheros Communications | 293       | 9.05%   |
| Realtek Semiconductor           | 265       | 8.18%   |
| Broadcom                        | 159       | 4.91%   |
| Lite-On Technology              | 115       | 3.55%   |
| IMC Networks                    | 115       | 3.55%   |
| Foxconn / Hon Hai               | 73        | 2.25%   |
| Dell                            | 56        | 1.73%   |
| Hewlett-Packard                 | 39        | 1.2%    |
| Cambridge Silicon Radio         | 36        | 1.11%   |
| ASUSTek Computer                | 24        | 0.74%   |
| Toshiba                         | 20        | 0.62%   |
| Realtek                         | 19        | 0.59%   |
| Ralink                          | 19        | 0.59%   |
| Foxconn International           | 8         | 0.25%   |
| Ralink Technology               | 5         | 0.15%   |
| Alps Electric                   | 5         | 0.15%   |
| Taiyo Yuden                     | 3         | 0.09%   |
| Unknown                         | 2         | 0.06%   |
| MediaTek                        | 2         | 0.06%   |
| Fujitsu                         | 2         | 0.06%   |
| Qcom                            | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 613       | 18.91%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 302       | 9.32%   |
| Intel AX201 Bluetooth                               | 253       | 7.81%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 225       | 6.94%   |
| Realtek Bluetooth Radio                             | 170       | 5.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 169       | 5.21%   |
| Apple Bluetooth USB Host Controller                 | 154       | 4.75%   |
| Intel AX200 Bluetooth                               | 143       | 4.41%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.34%   |
| Realtek  Bluetooth 4.2 Adapter                      | 71        | 2.19%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 46        | 1.42%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 42        | 1.3%    |
| Broadcom BCM2045B (BDC-2.1)                         | 37        | 1.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 36        | 1.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 36        | 1.11%   |
| IMC Networks Bluetooth Radio                        | 35        | 1.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 34        | 1.05%   |
| IMC Networks Bluetooth Device                       | 32        | 0.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 30        | 0.93%   |
| Apple Bluetooth Host Controller                     | 30        | 0.93%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 28        | 0.86%   |
| Lite-On Bluetooth Device                            | 28        | 0.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 28        | 0.86%   |
| Foxconn / Hon Hai Bluetooth Device                  | 28        | 0.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 27        | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 27        | 0.83%   |
| Intel Bluetooth Device                              | 24        | 0.74%   |
| Dell DW375 Bluetooth Module                         | 20        | 0.62%   |
| Realtek Bluetooth Radio                             | 19        | 0.59%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.59%   |
| Intel AX210 Bluetooth                               | 18        | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 18        | 0.56%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.49%   |
| Foxconn / Hon Hai Wireless_Device                   | 16        | 0.49%   |
| IMC Networks Wireless_Device                        | 15        | 0.46%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 15        | 0.46%   |
| Dell BCM20702A0 Bluetooth Module                    | 15        | 0.46%   |
| Realtek RTL8723B Bluetooth                          | 14        | 0.43%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 13        | 0.4%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 11        | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3067      | 66.21%  |
| Nvidia                               | 688       | 14.85%  |
| AMD                                  | 603       | 13.02%  |
| C-Media Electronics                  | 32        | 0.69%   |
| Logitech                             | 27        | 0.58%   |
| Lenovo                               | 23        | 0.5%    |
| Realtek Semiconductor                | 22        | 0.47%   |
| Texas Instruments                    | 17        | 0.37%   |
| Plantronics                          | 15        | 0.32%   |
| GN Netcom                            | 14        | 0.3%    |
| Silicon Integrated Systems [SiS]     | 11        | 0.24%   |
| Hewlett-Packard                      | 10        | 0.22%   |
| Generalplus Technology               | 9         | 0.19%   |
| Creative Technology                  | 6         | 0.13%   |
| ASUSTek Computer                     | 5         | 0.11%   |
| RODE Microphones                     | 4         | 0.09%   |
| Kingston Technology                  | 4         | 0.09%   |
| JMTek                                | 4         | 0.09%   |
| Focusrite-Novation                   | 4         | 0.09%   |
| Sennheiser Communications            | 3         | 0.06%   |
| Razer USA                            | 3         | 0.06%   |
| Microsoft                            | 3         | 0.06%   |
| Dell                                 | 3         | 0.06%   |
| Zhaoxin                              | 2         | 0.04%   |
| VIA Technologies                     | 2         | 0.04%   |
| ULi Electronics                      | 2         | 0.04%   |
| SAVITECH                             | 2         | 0.04%   |
| M-Audio                              | 2         | 0.04%   |
| ESS Technology                       | 2         | 0.04%   |
| CMX Systems                          | 2         | 0.04%   |
| Blue Microphones                     | 2         | 0.04%   |
| BEHRINGER International              | 2         | 0.04%   |
| Apple                                | 2         | 0.04%   |
| Yamaha                               | 1         | 0.02%   |
| XMOS                                 | 1         | 0.02%   |
| Veho                                 | 1         | 0.02%   |
| Trust                                | 1         | 0.02%   |
| Toshiba                              | 1         | 0.02%   |
| Thomann                              | 1         | 0.02%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 458       | 8.2%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 325       | 5.82%   |
| Nvidia MCP79 High Definition Audio                                                                | 314       | 5.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 302       | 5.41%   |
| Intel Broadwell-U Audio Controller                                                                | 262       | 4.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 258       | 4.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 199       | 3.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 169       | 3.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 158       | 2.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 157       | 2.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 142       | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 139       | 2.49%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 132       | 2.36%   |
| Intel 8 Series HD Audio Controller                                                                | 132       | 2.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 128       | 2.29%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 119       | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 118       | 2.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 117       | 2.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 107       | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 90        | 1.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 87        | 1.56%   |
| AMD FCH Azalia Controller                                                                         | 84        | 1.5%    |
| AMD Kabini HDMI/DP Audio                                                                          | 81        | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 79        | 1.41%   |
| Intel Comet Lake PCH cAVS                                                                         | 73        | 1.31%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 73        | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 71        | 1.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 53        | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 49        | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 46        | 0.82%   |
| Intel CM238 HD Audio Controller                                                                   | 44        | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 42        | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 38        | 0.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 38        | 0.68%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 37        | 0.66%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 35        | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 33        | 0.59%   |
| AMD High Definition Audio Controller                                                              | 33        | 0.59%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 29        | 0.52%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 26        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 1098      | 28.93%  |
| Samsung Electronics | 999       | 26.32%  |
| Micron Technology   | 388       | 10.22%  |
| Kingston            | 262       | 6.9%    |
| Unknown             | 251       | 6.61%   |
| Crucial             | 193       | 5.09%   |
| Elpida              | 116       | 3.06%   |
| A-DATA Technology   | 78        | 2.06%   |
| Ramaxel Technology  | 68        | 1.79%   |
| Nanya Technology    | 43        | 1.13%   |
| Corsair             | 37        | 0.97%   |
| Unknown             | 35        | 0.92%   |
| Unknown (ABCD)      | 28        | 0.74%   |
| Smart               | 28        | 0.74%   |
| GOODRAM             | 20        | 0.53%   |
| G.Skill             | 17        | 0.45%   |
| Transcend           | 15        | 0.4%    |
| Team                | 15        | 0.4%    |
| Teikon              | 10        | 0.26%   |
| Apacer              | 7         | 0.18%   |
| 48spaces            | 7         | 0.18%   |
| Smart Brazil        | 6         | 0.16%   |
| Silicon Power       | 6         | 0.16%   |
| Patriot             | 6         | 0.16%   |
| ASint Technology    | 5         | 0.13%   |
| Qimonda             | 4         | 0.11%   |
| AMD                 | 4         | 0.11%   |
| Wilk                | 3         | 0.08%   |
| PNY                 | 3         | 0.08%   |
| Neo Forza           | 3         | 0.08%   |
| Goldkey             | 3         | 0.08%   |
| Avant               | 3         | 0.08%   |
| Unknown (89F7)      | 2         | 0.05%   |
| Unifosa             | 2         | 0.05%   |
| TEXTORM             | 2         | 0.05%   |
| Shenzhen WODPOSIT   | 2         | 0.05%   |
| Infineon            | 2         | 0.05%   |
| High Bridge         | 2         | 0.05%   |
| Essencore           | 2         | 0.05%   |
| CSX                 | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 257       | 6.44%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.7%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 66        | 1.65%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 61        | 1.53%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 1.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 41        | 1.03%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 38        | 0.95%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 37        | 0.93%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 35        | 0.88%   |
| Unknown                                                          | 35        | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 33        | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 33        | 0.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 32        | 0.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 30        | 0.75%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 30        | 0.75%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 29        | 0.73%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 26        | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 25        | 0.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 25        | 0.63%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.63%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 24        | 0.6%    |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 24        | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 24        | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.6%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 24        | 0.6%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.58%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.55%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 21        | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 21        | 0.53%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 18        | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 0.45%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.43%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 17        | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 16        | 0.4%    |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 16        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1267      | 38.38%  |
| DDR3    | 1125      | 34.08%  |
| DDR2    | 522       | 15.81%  |
| LPDDR3  | 116       | 3.51%   |
| LPDDR4  | 112       | 3.39%   |
| SDRAM   | 71        | 2.15%   |
| DDR     | 38        | 1.15%   |
| Unknown | 18        | 0.55%   |
| DDR5    | 12        | 0.36%   |
| LPDDR5  | 10        | 0.3%    |
| DRAM    | 9         | 0.27%   |
| RAM     | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3016      | 91.17%  |
| Row Of Chips | 207       | 6.26%   |
| Unknown      | 48        | 1.45%   |
| Chip         | 29        | 0.88%   |
| DIMM         | 8         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1046      | 29.23%  |
| 4096  | 971       | 27.13%  |
| 2048  | 557       | 15.56%  |
| 1024  | 509       | 14.22%  |
| 16384 | 365       | 10.2%   |
| 32768 | 73        | 2.04%   |
| 512   | 40        | 1.12%   |
| 256   | 16        | 0.45%   |
| 128   | 2         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 854       | 24.17%  |
| 2667    | 626       | 17.71%  |
| 3200    | 471       | 13.33%  |
| 800     | 330       | 9.34%   |
| 2400    | 217       | 6.14%   |
| 667     | 165       | 4.67%   |
| 2133    | 148       | 4.19%   |
| 1334    | 148       | 4.19%   |
| 1333    | 122       | 3.45%   |
| Unknown | 92        | 2.6%    |
| 4267    | 48        | 1.36%   |
| 1067    | 47        | 1.33%   |
| 1867    | 41        | 1.16%   |
| 3266    | 32        | 0.91%   |
| 4199    | 25        | 0.71%   |
| 533     | 21        | 0.59%   |
| 975     | 18        | 0.51%   |
| 2048    | 16        | 0.45%   |
| 1066    | 15        | 0.42%   |
| 8400    | 14        | 0.4%    |
| 4800    | 14        | 0.4%    |
| 6400    | 10        | 0.28%   |
| 400     | 10        | 0.28%   |
| 4266    | 9         | 0.25%   |
| 333     | 9         | 0.25%   |
| 266     | 8         | 0.23%   |
| 1866    | 6         | 0.17%   |
| 3733    | 3         | 0.08%   |
| 2933    | 3         | 0.08%   |
| 2666    | 2         | 0.06%   |
| 1776    | 2         | 0.06%   |
| 933     | 2         | 0.06%   |
| 3000    | 1         | 0.03%   |
| 2134    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1596    | 1         | 0.03%   |
| 200     | 1         | 0.03%   |
| 133     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 38.46%  |
| Xerox               | 4         | 15.38%  |
| Canon               | 3         | 11.54%  |
| Brother Industries  | 3         | 11.54%  |
| Samsung Electronics | 2         | 7.69%   |
| Xiaomi              | 1         | 3.85%   |
| STMicroelectronics  | 1         | 3.85%   |
| Pantum              | 1         | 3.85%   |
| Kyocera             | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 4         | 14.81%  |
| Xiaomi MiMouse 2                                          | 1         | 3.7%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.7%    |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 3.7%    |
| Samsung CLX-3300 Series                                   | 1         | 3.7%    |
| Pantum P2500W series                                      | 1         | 3.7%    |
| Kyocera ECOSYS P2335d                                     | 1         | 3.7%    |
| HP OfficeJet 3830 series                                  | 1         | 3.7%    |
| HP LaserJet P1102                                         | 1         | 3.7%    |
| HP LaserJet 1200                                          | 1         | 3.7%    |
| HP LaserJet 1160 series                                   | 1         | 3.7%    |
| HP LaserJet 1022                                          | 1         | 3.7%    |
| HP LaserJet 1020                                          | 1         | 3.7%    |
| HP Ink Tank 110 series                                    | 1         | 3.7%    |
| HP EWS UPD                                                | 1         | 3.7%    |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 3.7%    |
| HP Deskjet 2540 series                                    | 1         | 3.7%    |
| HP DeskJet 2130 series                                    | 1         | 3.7%    |
| Canon PIXMA MX920 Series                                  | 1         | 3.7%    |
| Canon LBP3010/LBP3018/LBP3050                             | 1         | 3.7%    |
| Canon G3010 series                                        | 1         | 3.7%    |
| Brother PT-9500PC                                         | 1         | 3.7%    |
| Brother MFC-L2707DW                                       | 1         | 3.7%    |
| Brother HL-L2340D series                                  | 1         | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 45.45%  |
| Seiko Epson     | 4         | 36.36%  |
| Mustek Systems  | 1         | 9.09%   |
| Hewlett-Packard | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                           | 2         | 18.18%  |
| Seiko Epson GT-9800F [Perfection 3200]            | 1         | 9.09%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]     | 1         | 9.09%   |
| Seiko Epson GT-7700U [Perfection 1240U]           | 1         | 9.09%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 9.09%   |
| Mustek Systems SNAPSCAN e22                       | 1         | 9.09%   |
| HP Scanjet 200                                    | 1         | 9.09%   |
| Canon CanoScan LIDE 25                            | 1         | 9.09%   |
| Canon CanoScan LiDE 220                           | 1         | 9.09%   |
| Canon CanoScan LiDE 110                           | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 739       | 24.14%  |
| IMC Networks                           | 352       | 11.5%   |
| Acer                                   | 289       | 9.44%   |
| Realtek Semiconductor                  | 261       | 8.53%   |
| Microdia                               | 261       | 8.53%   |
| Quanta                                 | 228       | 7.45%   |
| Sunplus Innovation Technology          | 163       | 5.33%   |
| Suyin                                  | 101       | 3.3%    |
| Cheng Uei Precision Industry (Foxlink) | 93        | 3.04%   |
| Lite-On Technology                     | 76        | 2.48%   |
| Syntek                                 | 65        | 2.12%   |
| Luxvisions Innotech Limited            | 46        | 1.5%    |
| Apple                                  | 46        | 1.5%    |
| Logitech                               | 45        | 1.47%   |
| Silicon Motion                         | 44        | 1.44%   |
| Alcor Micro                            | 34        | 1.11%   |
| Ricoh                                  | 29        | 0.95%   |
| Lenovo                                 | 28        | 0.91%   |
| Z-Star Microelectronics                | 17        | 0.56%   |
| Primax Electronics                     | 15        | 0.49%   |
| Samsung Electronics                    | 13        | 0.42%   |
| Sonix Technology                       | 11        | 0.36%   |
| ALi                                    | 10        | 0.33%   |
| Importek                               | 7         | 0.23%   |
| SunplusIT                              | 6         | 0.2%    |
| Genesys Logic                          | 6         | 0.2%    |
| USB Camera                             | 5         | 0.16%   |
| OmniVision Technologies                | 4         | 0.13%   |
| Intel                                  | 4         | 0.13%   |
| DJKANA19IDX53W                         | 4         | 0.13%   |
| Y Media                                | 3         | 0.1%    |
| Sunplus Technology                     | 3         | 0.1%    |
| Microsoft                              | 3         | 0.1%    |
| MacroSilicon                           | 3         | 0.1%    |
| GEMBIRD                                | 3         | 0.1%    |
| Unknown                                | 2         | 0.07%   |
| Tobii Technology AB                    | 2         | 0.07%   |
| Pixart Imaging                         | 2         | 0.07%   |
| Mimaki Engineering                     | 2         | 0.07%   |
| Generalplus Technology                 | 2         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 206       | 6.69%   |
| IMC Networks Integrated Camera                      | 120       | 3.89%   |
| Microdia Integrated_Webcam_HD                       | 116       | 3.77%   |
| Realtek Integrated_Webcam_HD                        | 96        | 3.12%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 74        | 2.4%    |
| Acer Integrated Camera                              | 73        | 2.37%   |
| Quanta Chromebook HD Camera                         | 68        | 2.21%   |
| Chicony HD Webcam                                   | 68        | 2.21%   |
| Acer BisonCam, NB Pro                               | 57        | 1.85%   |
| Sunplus Integrated_Webcam_HD                        | 56        | 1.82%   |
| Chicony HP HD Camera                                | 40        | 1.3%    |
| Chicony USB2.0 HD UVC WebCam                        | 37        | 1.2%    |
| Syntek Integrated Camera                            | 34        | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 33        | 1.07%   |
| Lite-On Integrated Camera                           | 32        | 1.04%   |
| Quanta HP TrueVision HD Camera                      | 31        | 1.01%   |
| Acer SunplusIT Integrated Camera                    | 28        | 0.91%   |
| Microdia Integrated Webcam                          | 26        | 0.84%   |
| Acer Lenovo EasyCamera                              | 25        | 0.81%   |
| Realtek USB Camera                                  | 24        | 0.78%   |
| Quanta VGA WebCam                                   | 23        | 0.75%   |
| Quanta HD User Facing                               | 23        | 0.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 23        | 0.75%   |
| Chicony Integrated Camera (1280x720@30)             | 22        | 0.71%   |
| Sunplus HD WebCam                                   | 21        | 0.68%   |
| Quanta HP HD Camera                                 | 20        | 0.65%   |
| Chicony HP TrueVision HD Camera                     | 20        | 0.65%   |
| Realtek USB2.0 HD UVC WebCam                        | 19        | 0.62%   |
| Microdia Laptop_Integrated_Webcam_HD                | 18        | 0.58%   |
| Chicony HP Truevision HD                            | 18        | 0.58%   |
| Chicony HD User Facing                              | 18        | 0.58%   |
| Acer Lenovo Integrated Webcam                       | 18        | 0.58%   |
| Suyin HP TrueVision HD                              | 17        | 0.55%   |
| Realtek Integrated Webcam                           | 17        | 0.55%   |
| Lite-On HP HD Camera                                | 17        | 0.55%   |
| Chicony USB2.0 Camera                               | 17        | 0.55%   |
| Apple iPhone 5/5C/5S/6/SE                           | 17        | 0.55%   |
| Chicony Lenovo EasyCamera                           | 16        | 0.52%   |
| Chicony HP Webcam                                   | 16        | 0.52%   |
| Chicony EasyCamera                                  | 16        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 220       | 33.49%  |
| Synaptics                          | 198       | 30.14%  |
| Shenzhen Goodix Technology         | 89        | 13.55%  |
| AuthenTec                          | 43        | 6.54%   |
| Upek                               | 37        | 5.63%   |
| Elan Microelectronics              | 33        | 5.02%   |
| LighTuning Technology              | 21        | 3.2%    |
| STMicroelectronics                 | 13        | 1.98%   |
| Samsung Electronics                | 1         | 0.15%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.15%   |
| Microsoft                          | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 94        | 14.31%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 53        | 8.07%   |
| Shenzhen Goodix  Fingerprint Device                                        | 51        | 7.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 44        | 6.7%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 39        | 5.94%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 33        | 5.02%   |
| Unknown                                                                    | 27        | 4.11%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 25        | 3.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 21        | 3.2%    |
| Elan ELAN:Fingerprint                                                      | 21        | 3.2%    |
| AuthenTec AES2810                                                          | 18        | 2.74%   |
| Shenzhen Goodix FingerPrint                                                | 17        | 2.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 15        | 2.28%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 15        | 2.28%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 1.98%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 1.83%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.83%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 12        | 1.83%   |
| Elan ELAN:ARM-M4                                                           | 12        | 1.83%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 1.67%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.52%   |
| Validity Sensors VFS Fingerprint sensor                                    | 9         | 1.37%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 1.37%   |
| Synaptics  WBDI                                                            | 9         | 1.37%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.22%   |
| Validity Sensors VFS491                                                    | 7         | 1.07%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.91%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 0.76%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 0.76%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.61%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.61%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.46%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.46%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.3%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.3%    |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.3%    |
| LighTuning Fingerprint Reader                                              | 2         | 0.3%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.15%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 126       | 37.61%  |
| Alcor Micro               | 122       | 36.42%  |
| Upek                      | 26        | 7.76%   |
| Lenovo                    | 24        | 7.16%   |
| O2 Micro                  | 22        | 6.57%   |
| Gemalto (was Gemplus)     | 3         | 0.9%    |
| Clay Logic                | 3         | 0.9%    |
| Yubico.com                | 2         | 0.6%    |
| Aladdin Knowledge Systems | 2         | 0.6%    |
| SCM Microsystems          | 1         | 0.3%    |
| OmniKey                   | 1         | 0.3%    |
| Cherry                    | 1         | 0.3%    |
| C3PO                      | 1         | 0.3%    |
| Advanced Card Systems     | 1         | 0.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 120       | 35.82%  |
| Broadcom BCM5880 Secure Applications Processor                               | 42        | 12.54%  |
| Broadcom 5880                                                                | 34        | 10.15%  |
| Broadcom 58200                                                               | 30        | 8.96%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 7.76%   |
| Lenovo Integrated Smart Card Reader                                          | 24        | 7.16%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 19        | 5.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 19        | 5.67%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.9%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.6%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.6%    |
| Clay Logic Nitrokey Start                                                    | 2         | 0.6%    |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.6%    |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.6%    |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.3%    |
| OmniKey CardMan 4321                                                         | 1         | 0.3%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.3%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.3%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.3%    |
| C3PO LTC31v2                                                                 | 1         | 0.3%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.3%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2381      | 58.37%  |
| 1     | 1279      | 31.36%  |
| 2     | 328       | 8.04%   |
| 3     | 77        | 1.89%   |
| 4     | 8         | 0.2%    |
| 5     | 5         | 0.12%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 653       | 30.9%   |
| Graphics card            | 497       | 23.52%  |
| Chipcard                 | 305       | 14.43%  |
| Multimedia controller    | 227       | 10.74%  |
| Net/wireless             | 184       | 8.71%   |
| Bluetooth                | 57        | 2.7%    |
| Camera                   | 40        | 1.89%   |
| Card reader              | 36        | 1.7%    |
| Storage                  | 33        | 1.56%   |
| Communication controller | 29        | 1.37%   |
| Sound                    | 14        | 0.66%   |
| Net/ethernet             | 13        | 0.62%   |
| Network                  | 8         | 0.38%   |
| Modem                    | 6         | 0.28%   |
| Flash memory             | 4         | 0.19%   |
| Unassigned class         | 2         | 0.09%   |
| Firewire controller      | 2         | 0.09%   |
| Wireless                 | 1         | 0.05%   |
| Tv card                  | 1         | 0.05%   |
| Storage/ide              | 1         | 0.05%   |

