Linux in Venezuela - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Venezuela.

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

Total: 288

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | W54BL                       | [adb804fa7f](https://linux-hardware.org/?probe=adb804fa7f) | Apr 27, 2024 |
| Unknown       | Unknown                     | [5fda06b27d](https://linux-hardware.org/?probe=5fda06b27d) | Apr 26, 2024 |
| HP            | Pavilion m6                 | [7573d33d4f](https://linux-hardware.org/?probe=7573d33d4f) | Apr 04, 2024 |
| Toshiba       | Satellite A205              | [4fcbf3184c](https://linux-hardware.org/?probe=4fcbf3184c) | Apr 02, 2024 |
| VENEZOLANA... | VIT P2460-02                | [c6fc091713](https://linux-hardware.org/?probe=c6fc091713) | Mar 24, 2024 |
| Dell          | Precision M4800             | [9a66a454e2](https://linux-hardware.org/?probe=9a66a454e2) | Mar 17, 2024 |
| Dell          | Precision M4800             | [c38442b3dc](https://linux-hardware.org/?probe=c38442b3dc) | Mar 17, 2024 |
| Unknown       | Unknown                     | [d00c774230](https://linux-hardware.org/?probe=d00c774230) | Mar 16, 2024 |
| Google        | Kip                         | [3da64ae4ad](https://linux-hardware.org/?probe=3da64ae4ad) | Mar 11, 2024 |
| Google        | Kip                         | [a08197fa56](https://linux-hardware.org/?probe=a08197fa56) | Mar 11, 2024 |
| Acer          | Aspire A515-43              | [054ae2a4a5](https://linux-hardware.org/?probe=054ae2a4a5) | Mar 09, 2024 |
| Dell          | Inspiron N4010              | [0d25733cfa](https://linux-hardware.org/?probe=0d25733cfa) | Feb 27, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [46990d3920](https://linux-hardware.org/?probe=46990d3920) | Feb 17, 2024 |
| HP            | ProBook 650 G1              | [9b6886b2f0](https://linux-hardware.org/?probe=9b6886b2f0) | Feb 16, 2024 |
| HP            | ProBook 650 G1              | [d3d2fd6bda](https://linux-hardware.org/?probe=d3d2fd6bda) | Feb 16, 2024 |
| Lenovo        | 3000 N500 42336DS           | [7c23ebf66b](https://linux-hardware.org/?probe=7c23ebf66b) | Feb 13, 2024 |
| VIT           | P1400                       | [8cb8362e24](https://linux-hardware.org/?probe=8cb8362e24) | Feb 10, 2024 |
| VIT           | P3400                       | [036ee57838](https://linux-hardware.org/?probe=036ee57838) | Feb 02, 2024 |
| VIT           | P3400                       | [6b03e6574f](https://linux-hardware.org/?probe=6b03e6574f) | Feb 01, 2024 |
| Dell          | Inspiron MXC061             | [a134206781](https://linux-hardware.org/?probe=a134206781) | Jan 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [1ebab4d906](https://linux-hardware.org/?probe=1ebab4d906) | Jan 30, 2024 |
| Dell          | Inspiron 3531               | [afc0f1a968](https://linux-hardware.org/?probe=afc0f1a968) | Jan 20, 2024 |
| Google        | Fleex                       | [100ab93f52](https://linux-hardware.org/?probe=100ab93f52) | Jan 09, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [45b99e2412](https://linux-hardware.org/?probe=45b99e2412) | Jan 08, 2024 |
| Dell          | G16 7630                    | [71f36f8ed0](https://linux-hardware.org/?probe=71f36f8ed0) | Dec 24, 2023 |
| HP            | Pavilion dv5                | [cf88cdfeb2](https://linux-hardware.org/?probe=cf88cdfeb2) | Dec 18, 2023 |
| Google        | Candy                       | [be56752bfd](https://linux-hardware.org/?probe=be56752bfd) | Dec 17, 2023 |
| VIT           | P3400                       | [0564cdc52e](https://linux-hardware.org/?probe=0564cdc52e) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [55a44e9a14](https://linux-hardware.org/?probe=55a44e9a14) | Dec 05, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [88fba30cec](https://linux-hardware.org/?probe=88fba30cec) | Nov 21, 2023 |
| Notebook      | NL40_50CU                   | [94885b9878](https://linux-hardware.org/?probe=94885b9878) | Nov 21, 2023 |
| Dell          | Inspiron 15 3511            | [79b891b4df](https://linux-hardware.org/?probe=79b891b4df) | Nov 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9c9733a5c4](https://linux-hardware.org/?probe=9c9733a5c4) | Nov 07, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e4d524b5b8](https://linux-hardware.org/?probe=e4d524b5b8) | Nov 07, 2023 |
| Lenovo        | ThinkPad T490 20N2000LSP    | [55e3cdf0cc](https://linux-hardware.org/?probe=55e3cdf0cc) | Nov 05, 2023 |
| Intel         | powered classmate PC        | [122f9662f5](https://linux-hardware.org/?probe=122f9662f5) | Nov 02, 2023 |
| VIT           | P1400                       | [235c6e8c49](https://linux-hardware.org/?probe=235c6e8c49) | Oct 28, 2023 |
| Gateway       | NV57H                       | [141355e1e3](https://linux-hardware.org/?probe=141355e1e3) | Oct 09, 2023 |
| HP            | Compaq Presario C768        | [7b364bd566](https://linux-hardware.org/?probe=7b364bd566) | Oct 07, 2023 |
| VIT           | P2400                       | [1896f1962a](https://linux-hardware.org/?probe=1896f1962a) | Oct 06, 2023 |
| HP            | Pavilion m6                 | [2fb7dbd455](https://linux-hardware.org/?probe=2fb7dbd455) | Sep 09, 2023 |
| Acer          | Aspire A315-42              | [a0abff6d5f](https://linux-hardware.org/?probe=a0abff6d5f) | Sep 08, 2023 |
| VIT           | P2400                       | [d8ea46cf44](https://linux-hardware.org/?probe=d8ea46cf44) | Sep 04, 2023 |
| VENEZOLANA... | VIT P2460-02                | [9c1d875ec4](https://linux-hardware.org/?probe=9c1d875ec4) | Sep 03, 2023 |
| ASUSTek       | X540SA                      | [71b31f4a43](https://linux-hardware.org/?probe=71b31f4a43) | Aug 31, 2023 |
| Panasonic     | CF-31RECAXDR                | [2c021f93de](https://linux-hardware.org/?probe=2c021f93de) | Aug 30, 2023 |
| ASUSTek       | X540SA                      | [dd6f1d7cac](https://linux-hardware.org/?probe=dd6f1d7cac) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [fc59d4358f](https://linux-hardware.org/?probe=fc59d4358f) | Aug 26, 2023 |
| HP            | Pavilion dv5                | [8e621682ec](https://linux-hardware.org/?probe=8e621682ec) | Aug 25, 2023 |
| VIT           | P2402                       | [fa87ae71d4](https://linux-hardware.org/?probe=fa87ae71d4) | Aug 22, 2023 |
| VIT           | P2402                       | [7b83628f3c](https://linux-hardware.org/?probe=7b83628f3c) | Aug 22, 2023 |
| HP            | Laptop 15-fc0xxx            | [52c59bb799](https://linux-hardware.org/?probe=52c59bb799) | Aug 16, 2023 |
| Siragon       | MN-50                       | [8eafa43cb5](https://linux-hardware.org/?probe=8eafa43cb5) | Aug 09, 2023 |
| Dell          | Inspiron 3531               | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Shanghai Z... | ZXE CRB                     | [da6bb4265c](https://linux-hardware.org/?probe=da6bb4265c) | Jul 20, 2023 |
| Acer          | Aspire 4750                 | [d1ef43e488](https://linux-hardware.org/?probe=d1ef43e488) | Jul 16, 2023 |
| SIRAGON       | LM-C100                     | [daef084233](https://linux-hardware.org/?probe=daef084233) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2f2887fc32](https://linux-hardware.org/?probe=2f2887fc32) | Jul 15, 2023 |
| Lenovo        | G570 4334                   | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [c1da8fb79e](https://linux-hardware.org/?probe=c1da8fb79e) | Jul 08, 2023 |
| Dell          | Inspiron N4050              | [d5fa70cfda](https://linux-hardware.org/?probe=d5fa70cfda) | Jul 08, 2023 |
| Dell          | Latitude 7490               | [3734a0a9bf](https://linux-hardware.org/?probe=3734a0a9bf) | Jul 07, 2023 |
| Acer          | Aspire 6930                 | [772d3d7f4a](https://linux-hardware.org/?probe=772d3d7f4a) | Jul 04, 2023 |
| VIT           | P2423                       | [19242b2ddb](https://linux-hardware.org/?probe=19242b2ddb) | Jun 23, 2023 |
| Intel         | powered classmate PC        | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| VIT           | P2402                       | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| VIT           | P2400                       | [dca6cca8a2](https://linux-hardware.org/?probe=dca6cca8a2) | May 26, 2023 |
| Acer          | Aspire A514-55              | [17996395f4](https://linux-hardware.org/?probe=17996395f4) | May 25, 2023 |
| HP            | Laptop 14-dq1xxx            | [dddde1dc45](https://linux-hardware.org/?probe=dddde1dc45) | May 25, 2023 |
| HP            | Laptop 14-dq1xxx            | [d8261039f8](https://linux-hardware.org/?probe=d8261039f8) | May 24, 2023 |
| HP            | Laptop 17-cp0xxx            | [7f1bc5a99c](https://linux-hardware.org/?probe=7f1bc5a99c) | May 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [701fb0df1b](https://linux-hardware.org/?probe=701fb0df1b) | Apr 26, 2023 |
| HP            | Laptop 17-cp0xxx            | [7ba77e1842](https://linux-hardware.org/?probe=7ba77e1842) | Apr 23, 2023 |
| Dell          | Latitude E6430              | [e844bce31c](https://linux-hardware.org/?probe=e844bce31c) | Apr 23, 2023 |
| Notebook      | NL40_50CU                   | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| Samsung       | 905S3G/906S3G/915S3G        | [54af26ce93](https://linux-hardware.org/?probe=54af26ce93) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [98121ef614](https://linux-hardware.org/?probe=98121ef614) | Apr 14, 2023 |
| Lenovo        | 3000 V200 07642XU           | [365e3a50d2](https://linux-hardware.org/?probe=365e3a50d2) | Apr 10, 2023 |
| VIT           | P2402                       | [1c25795c2f](https://linux-hardware.org/?probe=1c25795c2f) | Apr 07, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | EliteBook 840 G3            | [36f4574fd4](https://linux-hardware.org/?probe=36f4574fd4) | Apr 03, 2023 |
| Notebook      | W54BL                       | [5e3ba9b128](https://linux-hardware.org/?probe=5e3ba9b128) | Apr 01, 2023 |
| Intel         | powered classmate PC        | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| Pegatron      | H36Y                        | [1757156f40](https://linux-hardware.org/?probe=1757156f40) | Mar 11, 2023 |
| Acer          | Aspire A715-76              | [c0c0d5447d](https://linux-hardware.org/?probe=c0c0d5447d) | Mar 09, 2023 |
| Pegatron      | H36Y                        | [8d9c3ebbc8](https://linux-hardware.org/?probe=8d9c3ebbc8) | Mar 09, 2023 |
| MSI           | GL73 9SD                    | [0913746f16](https://linux-hardware.org/?probe=0913746f16) | Mar 07, 2023 |
| VIT           | P1400                       | [3d31270e0d](https://linux-hardware.org/?probe=3d31270e0d) | Mar 07, 2023 |
| VIT           | P1400                       | [bed6aed6fa](https://linux-hardware.org/?probe=bed6aed6fa) | Mar 07, 2023 |
| Acer          | Aspire A715-76              | [b9f52dc0f3](https://linux-hardware.org/?probe=b9f52dc0f3) | Feb 27, 2023 |
| Shanghai Z... | ZXE CRB                     | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
| Dell          | Latitude E6430              | [23c0ff9281](https://linux-hardware.org/?probe=23c0ff9281) | Feb 19, 2023 |
| Dell          | Latitude E6430              | [d97087b55f](https://linux-hardware.org/?probe=d97087b55f) | Feb 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7fd55795a0](https://linux-hardware.org/?probe=7fd55795a0) | Feb 15, 2023 |
| Google        | Candy                       | [b2f2862759](https://linux-hardware.org/?probe=b2f2862759) | Feb 13, 2023 |
| Dell          | Latitude E5450              | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Acer          | Aspire 4739Z                | [cc795627da](https://linux-hardware.org/?probe=cc795627da) | Feb 10, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [c20b6ee7d2](https://linux-hardware.org/?probe=c20b6ee7d2) | Feb 04, 2023 |
| Dell          | Latitude E6430              | [10b3b0cfbb](https://linux-hardware.org/?probe=10b3b0cfbb) | Feb 03, 2023 |
| Dell          | Latitude E6430              | [55c398146b](https://linux-hardware.org/?probe=55c398146b) | Feb 01, 2023 |
| Lenovo        | ThinkPad SL 2743A65         | [89f744ff83](https://linux-hardware.org/?probe=89f744ff83) | Jan 22, 2023 |
| Dell          | Vostro 1220                 | [6cd42b6be3](https://linux-hardware.org/?probe=6cd42b6be3) | Jan 19, 2023 |
| Dell          | Inspiron 5502               | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| Pegatron      | B74                         | [3e721dbe13](https://linux-hardware.org/?probe=3e721dbe13) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z580                | [6cb922bbdf](https://linux-hardware.org/?probe=6cb922bbdf) | Jan 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [8e885883c6](https://linux-hardware.org/?probe=8e885883c6) | Jan 03, 2023 |
| HP            | Compaq Presario C700        | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [e0584a11c0](https://linux-hardware.org/?probe=e0584a11c0) | Dec 10, 2022 |
| Acer          | Aspire A315-42              | [68f683d29e](https://linux-hardware.org/?probe=68f683d29e) | Dec 06, 2022 |
| HP            | Mini 110-1100               | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| Lenovo        | 3000 N500 42336DS           | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| Intel         | powered classmate PC        | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Dell          | Vostro 3550                 | [a195c7598f](https://linux-hardware.org/?probe=a195c7598f) | Nov 14, 2022 |
| Dell          | Vostro 3550                 | [2176ff6bc0](https://linux-hardware.org/?probe=2176ff6bc0) | Nov 14, 2022 |
| Acer          | Aspire 4739Z                | [d3ef4a43db](https://linux-hardware.org/?probe=d3ef4a43db) | Nov 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| Google        | Candy                       | [af2c0be6ca](https://linux-hardware.org/?probe=af2c0be6ca) | Oct 17, 2022 |
| Google        | Candy                       | [ec740507fd](https://linux-hardware.org/?probe=ec740507fd) | Oct 17, 2022 |
| Dell          | Inspiron 5502               | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| Shanghai Z... | ZXE CRB                     | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Unknown       | NB-7000                     | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| VIT           | P2402                       | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| Toshiba       | ENCORE 2 WT8-B              | [b9cd7b49d3](https://linux-hardware.org/?probe=b9cd7b49d3) | Sep 23, 2022 |
| HP            | EliteBook 8760w             | [858fd4f09e](https://linux-hardware.org/?probe=858fd4f09e) | Sep 20, 2022 |
| Gateway       | NV57H                       | [8fb75d738c](https://linux-hardware.org/?probe=8fb75d738c) | Sep 20, 2022 |
| Clevo         | W54xEU                      | [bd0c5962bd](https://linux-hardware.org/?probe=bd0c5962bd) | Sep 15, 2022 |
| Acer          | Aspire A515-44              | [ac687f4dcd](https://linux-hardware.org/?probe=ac687f4dcd) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| Dell          | Latitude E6420              | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| Dell          | Inspiron 3180               | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [63a6df97b9](https://linux-hardware.org/?probe=63a6df97b9) | Aug 09, 2022 |
| VIT           | P2402                       | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| HP            | ProBook 440 G1              | [fc4f66c2de](https://linux-hardware.org/?probe=fc4f66c2de) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [743422e837](https://linux-hardware.org/?probe=743422e837) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [78bde5c7cc](https://linux-hardware.org/?probe=78bde5c7cc) | Aug 02, 2022 |
| VIT           | P2402                       | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| HP            | ProBook 440 G1              | [a0ebe8cf5a](https://linux-hardware.org/?probe=a0ebe8cf5a) | Jul 20, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [dee20b535f](https://linux-hardware.org/?probe=dee20b535f) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| HP            | EliteBook 840 G3            | [d7282a0f61](https://linux-hardware.org/?probe=d7282a0f61) | Jun 29, 2022 |
| Dell          | Inspiron 5502               | [c3e90d4ebd](https://linux-hardware.org/?probe=c3e90d4ebd) | Jun 26, 2022 |
| Google        | Cyan                        | [7b82520717](https://linux-hardware.org/?probe=7b82520717) | Jun 13, 2022 |
| VIT           | M2420                       | [8152d4c61b](https://linux-hardware.org/?probe=8152d4c61b) | Jun 08, 2022 |
| VIT           | M2420                       | [d09de8cbd7](https://linux-hardware.org/?probe=d09de8cbd7) | Jun 07, 2022 |
| VIT           | M2420                       | [c2ea650175](https://linux-hardware.org/?probe=c2ea650175) | Jun 01, 2022 |
| Dell          | Precision 7710              | [befe390051](https://linux-hardware.org/?probe=befe390051) | May 28, 2022 |
| Acer          | TravelMate 5742Z            | [fd6407ece1](https://linux-hardware.org/?probe=fd6407ece1) | May 26, 2022 |
| Dell          | Inspiron 5520               | [0e7bf88677](https://linux-hardware.org/?probe=0e7bf88677) | May 19, 2022 |
| Dell          | XPS 15 7590                 | [8dc1b9cd87](https://linux-hardware.org/?probe=8dc1b9cd87) | May 14, 2022 |
| Unknown       | Unknown                     | [ff32f84c4e](https://linux-hardware.org/?probe=ff32f84c4e) | Apr 23, 2022 |
| Dell          | Inspiron 1545               | [8869defd9c](https://linux-hardware.org/?probe=8869defd9c) | Apr 22, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [8510a8836c](https://linux-hardware.org/?probe=8510a8836c) | Apr 18, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [6c3ed980a1](https://linux-hardware.org/?probe=6c3ed980a1) | Apr 18, 2022 |
| Clevo         | W54xEU                      | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Dell          | Latitude 5590               | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| HP            | Pavilion dv5                | [22aa828b2f](https://linux-hardware.org/?probe=22aa828b2f) | Apr 16, 2022 |
| HP            | Compaq Presario C700        | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Clevo         | W54xEU                      | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3f66b1cb5c](https://linux-hardware.org/?probe=3f66b1cb5c) | Apr 13, 2022 |
| Dell          | Latitude 5590               | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| HP            | EliteBook 840 G3            | [659999d04a](https://linux-hardware.org/?probe=659999d04a) | Apr 11, 2022 |
| HP            | EliteBook 840 G3            | [227c3936b8](https://linux-hardware.org/?probe=227c3936b8) | Apr 09, 2022 |
| Dell          | Vostro 5402                 | [6cb82accd9](https://linux-hardware.org/?probe=6cb82accd9) | Apr 07, 2022 |
| Gateway       | NV57H                       | [ce2e78a407](https://linux-hardware.org/?probe=ce2e78a407) | Mar 31, 2022 |
| HP            | Laptop 15-ef2xxx            | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| VIT           | P2402                       | [5d9e3733ea](https://linux-hardware.org/?probe=5d9e3733ea) | Mar 21, 2022 |
| Dell          | Inspiron 5502               | [3dcc73772f](https://linux-hardware.org/?probe=3dcc73772f) | Mar 12, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [5fa0d18666](https://linux-hardware.org/?probe=5fa0d18666) | Mar 04, 2022 |
| VIT           | P3400                       | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| VIT           | P3400                       | [b90c32748d](https://linux-hardware.org/?probe=b90c32748d) | Feb 18, 2022 |
| Lenovo        | ThinkPad X201 3680AE2       | [cb777c91bc](https://linux-hardware.org/?probe=cb777c91bc) | Feb 13, 2022 |
| HP            | Pavilion dv6500             | [16dbcf63f1](https://linux-hardware.org/?probe=16dbcf63f1) | Feb 12, 2022 |
| Gateway       | NV57H                       | [9d59228f90](https://linux-hardware.org/?probe=9d59228f90) | Feb 09, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [ac9ed3224d](https://linux-hardware.org/?probe=ac9ed3224d) | Feb 01, 2022 |
| MSI           | MS-1454                     | [1cb9a056e7](https://linux-hardware.org/?probe=1cb9a056e7) | Jan 14, 2022 |
| VIT           | M2421                       | [c6cc8a474d](https://linux-hardware.org/?probe=c6cc8a474d) | Jan 10, 2022 |
| UNIQCELL      | Q15.6                       | [d21e7048e1](https://linux-hardware.org/?probe=d21e7048e1) | Dec 20, 2021 |
| GPU Compan... | GWTN156-11                  | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| AVITA         | NS14A1US                    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| Intel         | powered classmate PC        | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Lenovo        | B40-70 20392                | [4f4458d61a](https://linux-hardware.org/?probe=4f4458d61a) | Nov 23, 2021 |
| HP            | Pavilion dv6                | [2f83ccbc4f](https://linux-hardware.org/?probe=2f83ccbc4f) | Nov 21, 2021 |
| HP            | Pavilion dv6                | [a492e3e1ff](https://linux-hardware.org/?probe=a492e3e1ff) | Nov 21, 2021 |
| Unknown       | Unknown                     | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| Dell          | Inspiron 14-3467            | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b37e3324e3](https://linux-hardware.org/?probe=b37e3324e3) | Nov 05, 2021 |
| VIT           | P3400                       | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Lenovo        | G570 4334                   | [d1d57448c4](https://linux-hardware.org/?probe=d1d57448c4) | Oct 29, 2021 |
| Lenovo        | G570 4334                   | [f5112dbf47](https://linux-hardware.org/?probe=f5112dbf47) | Oct 29, 2021 |
| Dell          | Latitude E7450              | [9cbd7f01e8](https://linux-hardware.org/?probe=9cbd7f01e8) | Oct 18, 2021 |
| Dell          | Latitude E6420              | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [e5391d41e0](https://linux-hardware.org/?probe=e5391d41e0) | Oct 14, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [3f6e406107](https://linux-hardware.org/?probe=3f6e406107) | Oct 14, 2021 |
| ASUSTek       | X555DA                      | [903dc4ef05](https://linux-hardware.org/?probe=903dc4ef05) | Oct 13, 2021 |
| Clevo         | W54xEU                      | [a6732ab721](https://linux-hardware.org/?probe=a6732ab721) | Sep 30, 2021 |
| VIT           | P3400                       | [22260810d1](https://linux-hardware.org/?probe=22260810d1) | Sep 27, 2021 |
| ASUSTek       | TUF Gaming FA506IH_FA506... | [5854fbcaed](https://linux-hardware.org/?probe=5854fbcaed) | Sep 17, 2021 |
| Pegatron      | T14AF                       | [46067ec02a](https://linux-hardware.org/?probe=46067ec02a) | Sep 07, 2021 |
| Lenovo        | ThinkPad Edge 01962AS       | [8ccb24d0d8](https://linux-hardware.org/?probe=8ccb24d0d8) | Aug 24, 2021 |
| VIT           | P2400                       | [f844ffff09](https://linux-hardware.org/?probe=f844ffff09) | Aug 11, 2021 |
| Acer          | Aspire VX5-591G             | [c726cd767b](https://linux-hardware.org/?probe=c726cd767b) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c468ca84d3](https://linux-hardware.org/?probe=c468ca84d3) | Jun 30, 2021 |
| HP            | Pavilion dv6700             | [93c6a703a7](https://linux-hardware.org/?probe=93c6a703a7) | Jun 27, 2021 |
| HP            | Pavilion dv6700             | [f7e407b14c](https://linux-hardware.org/?probe=f7e407b14c) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [fc58981ecd](https://linux-hardware.org/?probe=fc58981ecd) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [bce9c74edb](https://linux-hardware.org/?probe=bce9c74edb) | Jun 27, 2021 |
| VIT           | P2400                       | [295d4d5a47](https://linux-hardware.org/?probe=295d4d5a47) | Jun 17, 2021 |
| VIT           | P1400                       | [129d543695](https://linux-hardware.org/?probe=129d543695) | Jun 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [423b514d2b](https://linux-hardware.org/?probe=423b514d2b) | May 30, 2021 |
| VIT           | P2400                       | [f39537fca1](https://linux-hardware.org/?probe=f39537fca1) | May 28, 2021 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [0f12ef1983](https://linux-hardware.org/?probe=0f12ef1983) | May 25, 2021 |
| VIT           | P2400                       | [4fa6d109de](https://linux-hardware.org/?probe=4fa6d109de) | May 25, 2021 |
| Sony          | VGN-FW510F                  | [1a9761824e](https://linux-hardware.org/?probe=1a9761824e) | May 20, 2021 |
| Intel         | powered classmate PC        | [a3b0d4e33e](https://linux-hardware.org/?probe=a3b0d4e33e) | May 12, 2021 |
| Lenovo        | G570 4334                   | [f16304ca03](https://linux-hardware.org/?probe=f16304ca03) | May 04, 2021 |
| Lenovo        | G570 4334                   | [8eca6b6f79](https://linux-hardware.org/?probe=8eca6b6f79) | May 04, 2021 |
| Lenovo        | G570 4334                   | [bef0f33897](https://linux-hardware.org/?probe=bef0f33897) | May 02, 2021 |
| Acer          | Aspire 4935                 | [cbe6a288f1](https://linux-hardware.org/?probe=cbe6a288f1) | Apr 06, 2021 |
| Toshiba       | Satellite E55t-A            | [e1a3602d7b](https://linux-hardware.org/?probe=e1a3602d7b) | Mar 28, 2021 |
| Dell          | Vostro 1500                 | [76ade477e8](https://linux-hardware.org/?probe=76ade477e8) | Mar 28, 2021 |
| ASUSTek       | X555DA                      | [28996604f4](https://linux-hardware.org/?probe=28996604f4) | Mar 27, 2021 |
| ASUSTek       | X555DA                      | [e90c94fd9d](https://linux-hardware.org/?probe=e90c94fd9d) | Mar 27, 2021 |
| Dell          | Inspiron 5437               | [918f841c61](https://linux-hardware.org/?probe=918f841c61) | Mar 12, 2021 |
| HP            | 2000                        | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| Dell          | Inspiron 5437               | [4883c81a02](https://linux-hardware.org/?probe=4883c81a02) | Feb 07, 2021 |
| AVITA         | NS14A1US                    | [63ab85aac6](https://linux-hardware.org/?probe=63ab85aac6) | Feb 05, 2021 |
| Dell          | Inspiron 1018               | [570fb5f20b](https://linux-hardware.org/?probe=570fb5f20b) | Jan 27, 2021 |
| Dell          | Inspiron 1018               | [b481e5f8d2](https://linux-hardware.org/?probe=b481e5f8d2) | Jan 27, 2021 |
| Dell          | Inspiron 3180               | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | [1d1e7e6236](https://linux-hardware.org/?probe=1d1e7e6236) | Nov 07, 2020 |
| Dell          | Inspiron 1545               | [31fa456854](https://linux-hardware.org/?probe=31fa456854) | Nov 07, 2020 |
| Exo           | AIO A210                    | [2082cc5386](https://linux-hardware.org/?probe=2082cc5386) | Nov 02, 2020 |
| Lenovo        | IdeaPad S110 20126          | [c172177266](https://linux-hardware.org/?probe=c172177266) | Oct 31, 2020 |
| ASUSTek       | X553MA                      | [8de08ff7ac](https://linux-hardware.org/?probe=8de08ff7ac) | Oct 24, 2020 |
| ASUSTek       | X553MA                      | [46849fa419](https://linux-hardware.org/?probe=46849fa419) | Oct 24, 2020 |
| Dell          | Inspiron 5437               | [0fa1b76517](https://linux-hardware.org/?probe=0fa1b76517) | Oct 15, 2020 |
| Lenovo        | G460 20041                  | [6944572eca](https://linux-hardware.org/?probe=6944572eca) | Oct 02, 2020 |
| Lenovo        | G460 20041                  | [1f4ffcafa7](https://linux-hardware.org/?probe=1f4ffcafa7) | Oct 02, 2020 |
| Dell          | Inspiron 5570               | [0d9041893c](https://linux-hardware.org/?probe=0d9041893c) | Sep 15, 2020 |
| Unknown       | Unknown                     | [922d1c2533](https://linux-hardware.org/?probe=922d1c2533) | Sep 11, 2020 |
| Unknown       | Unknown                     | [f56d6dcffd](https://linux-hardware.org/?probe=f56d6dcffd) | Sep 11, 2020 |
| HP            | Presario V2000 (EW997LA#... | [77a2a0c00f](https://linux-hardware.org/?probe=77a2a0c00f) | Aug 15, 2020 |
| Alienware     | 17 R4                       | [c1a871b29b](https://linux-hardware.org/?probe=c1a871b29b) | Aug 14, 2020 |
| VIT           | M2421                       | [451969e0fc](https://linux-hardware.org/?probe=451969e0fc) | Jul 27, 2020 |
| Intel         | powered classmate PC        | [1ffa275c8b](https://linux-hardware.org/?probe=1ffa275c8b) | Jul 12, 2020 |
| Intel         | powered classmate PC        | [49442bdbca](https://linux-hardware.org/?probe=49442bdbca) | Jul 11, 2020 |
| HP            | Presario C700               | [6b50a4fad1](https://linux-hardware.org/?probe=6b50a4fad1) | Jun 26, 2020 |
| Unknown       | Unknown                     | [e8a608f296](https://linux-hardware.org/?probe=e8a608f296) | May 23, 2020 |
| VIT           | P3400                       | [48c981187d](https://linux-hardware.org/?probe=48c981187d) | May 18, 2020 |
| VIT           | P3400                       | [f9be2de38c](https://linux-hardware.org/?probe=f9be2de38c) | May 14, 2020 |
| HP            | Pavilion dv4                | [2efd349a3f](https://linux-hardware.org/?probe=2efd349a3f) | May 13, 2020 |
| VIT           | P2402                       | [bacbeb66bd](https://linux-hardware.org/?probe=bacbeb66bd) | May 07, 2020 |
| VIT           | P3400                       | [cd75b7e2c3](https://linux-hardware.org/?probe=cd75b7e2c3) | Apr 24, 2020 |
| VIT           | P2400                       | [4acb382140](https://linux-hardware.org/?probe=4acb382140) | Apr 23, 2020 |
| VIT           | M2420                       | [a7535d12dc](https://linux-hardware.org/?probe=a7535d12dc) | Apr 13, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | [ebbf8f7b4e](https://linux-hardware.org/?probe=ebbf8f7b4e) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | [e39e92a6f9](https://linux-hardware.org/?probe=e39e92a6f9) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | [b9d2e7e174](https://linux-hardware.org/?probe=b9d2e7e174) | Mar 20, 2020 |
| VIT           | P2402                       | [9f90b82033](https://linux-hardware.org/?probe=9f90b82033) | Mar 10, 2020 |
| VIT           | P2402                       | [ea6b959930](https://linux-hardware.org/?probe=ea6b959930) | Mar 03, 2020 |
| Lenovo        | Z50-75 80EC                 | [79f0a68dd3](https://linux-hardware.org/?probe=79f0a68dd3) | Feb 26, 2020 |
| Lenovo        | IdeaPad S100c 20194         | [d1a4bff183](https://linux-hardware.org/?probe=d1a4bff183) | Feb 15, 2020 |
| Dell          | Inspiron 3421               | [17f334232d](https://linux-hardware.org/?probe=17f334232d) | Jan 01, 2020 |
| Intel         | powered classmate PC        | [b772cf9349](https://linux-hardware.org/?probe=b772cf9349) | Dec 11, 2019 |
| Intel         | powered classmate PC        | [b66f15db35](https://linux-hardware.org/?probe=b66f15db35) | Dec 11, 2019 |
| Lenovo        | IdeaPad S100c 20194         | [7c2893dba4](https://linux-hardware.org/?probe=7c2893dba4) | Nov 15, 2019 |
| Lenovo        | IdeaPad S100c 20194         | [530c41513b](https://linux-hardware.org/?probe=530c41513b) | Sep 20, 2019 |
| Lenovo        | G480 20150                  | [1b7e674c82](https://linux-hardware.org/?probe=1b7e674c82) | May 08, 2019 |
| Lenovo        | G480 20150                  | [99198fbcfa](https://linux-hardware.org/?probe=99198fbcfa) | May 08, 2019 |
| HP            | Pavilion dv4                | [e59414c439](https://linux-hardware.org/?probe=e59414c439) | Apr 11, 2019 |
| Intel         | powered classmate PC        | [405f76133d](https://linux-hardware.org/?probe=405f76133d) | Oct 11, 2017 |
| Intel         | powered classmate PC        | [e79ec0466f](https://linux-hardware.org/?probe=e79ec0466f) | Oct 01, 2017 |
| Lenovo        | 3000 N200 0769ARS           | [1ada6660c3](https://linux-hardware.org/?probe=1ada6660c3) | Aug 15, 2017 |
| Lenovo        | 3000 N200 0769ARS           | [5548cd964f](https://linux-hardware.org/?probe=5548cd964f) | Jul 28, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Debian 11          | 16        | 7.66%   |
| Ubuntu 22.04       | 15        | 7.18%   |
| Ubuntu 20.04       | 13        | 6.22%   |
| OpenMandriva 4.3   | 8         | 3.83%   |
| KDE neon 22.04     | 6         | 2.87%   |
| Debian 12          | 6         | 2.87%   |
| Debian 10          | 6         | 2.87%   |
| Zorin 16           | 5         | 2.39%   |
| Ubuntu 18.04       | 5         | 2.39%   |
| OpenMandriva 23.08 | 5         | 2.39%   |
| KDE neon 20.04     | 5         | 2.39%   |
| OpenMandriva 4.2   | 4         | 1.91%   |
| Linux Mint 21.1    | 4         | 1.91%   |
| Kubuntu 20.04      | 4         | 1.91%   |
| Xubuntu 18.04      | 3         | 1.44%   |
| ROSA R9            | 3         | 1.44%   |
| OpenMandriva 23.03 | 3         | 1.44%   |
| Linux Mint 20.3    | 3         | 1.44%   |
| Fedora 39          | 3         | 1.44%   |
| Arch Rolling       | 3         | 1.44%   |
| Zorin 15           | 2         | 0.96%   |
| Xubuntu 22.04      | 2         | 0.96%   |
| Ubuntu Unity 16.04 | 2         | 0.96%   |
| Ubuntu 23.10       | 2         | 0.96%   |
| Ubuntu 21.10       | 2         | 0.96%   |
| Ubuntu 19.10       | 2         | 0.96%   |
| Pop!_OS 22.04      | 2         | 0.96%   |
| Pop!_OS 21.04      | 2         | 0.96%   |
| OpenMandriva 24.01 | 2         | 0.96%   |
| OpenMandriva 23.01 | 2         | 0.96%   |
| Manjaro            | 2         | 0.96%   |
| Linux Mint 21.2    | 2         | 0.96%   |
| Linux Mint 20      | 2         | 0.96%   |
| Fedora 37          | 2         | 0.96%   |
| Fedora 36          | 2         | 0.96%   |
| Fedora 35          | 2         | 0.96%   |
| ArcoLinux Rolling  | 2         | 0.96%   |
| Xubuntu 23.10      | 1         | 0.48%   |
| Xubuntu 21.10      | 1         | 0.48%   |
| Xubuntu 20.04      | 1         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 38        | 19.19%  |
| Debian       | 26        | 13.13%  |
| OpenMandriva | 24        | 12.12%  |
| Linux Mint   | 14        | 7.07%   |
| KDE neon     | 12        | 6.06%   |
| Fedora       | 10        | 5.05%   |
| Xubuntu      | 8         | 4.04%   |
| Zorin        | 7         | 3.54%   |
| ROSA         | 6         | 3.03%   |
| Manjaro      | 6         | 3.03%   |
| Kubuntu      | 6         | 3.03%   |
| Pop!_OS      | 4         | 2.02%   |
| Arch         | 4         | 2.02%   |
| Ubuntu MATE  | 3         | 1.52%   |
| MX           | 3         | 1.52%   |
| Kali         | 3         | 1.52%   |
| Ubuntu Unity | 2         | 1.01%   |
| openSUSE     | 2         | 1.01%   |
| Nobara       | 2         | 1.01%   |
| Lubuntu      | 2         | 1.01%   |
| LMDE         | 2         | 1.01%   |
| ArcoLinux    | 2         | 1.01%   |
| Xero         | 1         | 0.51%   |
| Solus        | 1         | 0.51%   |
| Q4OS         | 1         | 0.51%   |
| Linux Lite   | 1         | 0.51%   |
| Garuda Linux | 1         | 0.51%   |
| Feren OS     | 1         | 0.51%   |
| EndeavourOS  | 1         | 0.51%   |
| Elementary   | 1         | 0.51%   |
| Deepin       | 1         | 0.51%   |
| BunsenLabs   | 1         | 0.51%   |
| Alpine       | 1         | 0.51%   |
| AlmaLinux    | 1         | 0.51%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 8         | 3.43%   |
| 5.4.0-42-generic                | 4         | 1.72%   |
| 5.15.0-46-generic               | 4         | 1.72%   |
| 5.10.14-desktop-1omv4002        | 4         | 1.72%   |
| 5.10.0-23-amd64                 | 4         | 1.72%   |
| 6.4.8-desktop-2omv2390          | 3         | 1.29%   |
| 6.4.11-desktop-1omv2390         | 3         | 1.29%   |
| 6.2.6-desktop-1omv2390          | 3         | 1.29%   |
| 5.4.0-73-generic                | 3         | 1.29%   |
| 5.4.0-52-generic                | 3         | 1.29%   |
| 5.3.0-40-generic                | 3         | 1.29%   |
| 5.15.0-67-generic               | 3         | 1.29%   |
| 5.15.0-56-generic               | 3         | 1.29%   |
| 5.13.0-39-generic               | 3         | 1.29%   |
| 5.10.0-13-amd64                 | 3         | 1.29%   |
| 4.19.0-17-amd64                 | 3         | 1.29%   |
| 6.4.11-arch2-1                  | 2         | 0.86%   |
| 6.2.0-26-generic                | 2         | 0.86%   |
| 6.1.1-desktop-1omv2290          | 2         | 0.86%   |
| 6.1.0-17-amd64                  | 2         | 0.86%   |
| 5.4.0-89-generic                | 2         | 0.86%   |
| 5.4.0-77-generic                | 2         | 0.86%   |
| 5.4.0-48-generic                | 2         | 0.86%   |
| 5.4.0-107-generic               | 2         | 0.86%   |
| 5.19.0-41-generic               | 2         | 0.86%   |
| 5.19.0-40-generic               | 2         | 0.86%   |
| 5.19.0-2-amd64                  | 2         | 0.86%   |
| 5.15.0-91-generic               | 2         | 0.86%   |
| 5.15.0-76-generic               | 2         | 0.86%   |
| 5.15.0-60-generic               | 2         | 0.86%   |
| 5.15.0-48-generic               | 2         | 0.86%   |
| 5.15.0-43-generic               | 2         | 0.86%   |
| 5.15.0-100-generic              | 2         | 0.86%   |
| 5.11.0-37-generic               | 2         | 0.86%   |
| 5.10.0-21-amd64                 | 2         | 0.86%   |
| 5.10.0-18-amd64                 | 2         | 0.86%   |
| 5.10.0-11-amd64                 | 2         | 0.86%   |
| 5.10.0-10-amd64                 | 2         | 0.86%   |
| 5.0.0-37-generic                | 2         | 0.86%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2         | 0.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 29        | 13.36%  |
| 5.4.0   | 20        | 9.22%   |
| 5.10.0  | 17        | 7.83%   |
| 6.2.0   | 10        | 4.61%   |
| 5.13.0  | 10        | 4.61%   |
| 5.16.7  | 8         | 3.69%   |
| 4.19.0  | 8         | 3.69%   |
| 5.19.0  | 7         | 3.23%   |
| 6.5.0   | 6         | 2.76%   |
| 6.1.0   | 6         | 2.76%   |
| 5.11.0  | 6         | 2.76%   |
| 6.4.11  | 5         | 2.3%    |
| 5.3.0   | 5         | 2.3%    |
| 5.8.0   | 4         | 1.84%   |
| 5.10.14 | 4         | 1.84%   |
| 4.15.0  | 4         | 1.84%   |
| 6.4.8   | 3         | 1.38%   |
| 6.2.6   | 3         | 1.38%   |
| 6.6.2   | 2         | 0.92%   |
| 6.4.2   | 2         | 0.92%   |
| 6.1.1   | 2         | 0.92%   |
| 5.18.0  | 2         | 0.92%   |
| 5.15.2  | 2         | 0.92%   |
| 5.14.10 | 2         | 0.92%   |
| 5.0.0   | 2         | 0.92%   |
| 4.9.20  | 2         | 0.92%   |
| 6.8.7   | 1         | 0.46%   |
| 6.7.7   | 1         | 0.46%   |
| 6.6.7   | 1         | 0.46%   |
| 6.6.21  | 1         | 0.46%   |
| 6.5.6   | 1         | 0.46%   |
| 6.5.1   | 1         | 0.46%   |
| 6.4.12  | 1         | 0.46%   |
| 6.3.6   | 1         | 0.46%   |
| 6.3.5   | 1         | 0.46%   |
| 6.3.0   | 1         | 0.46%   |
| 6.2.12  | 1         | 0.46%   |
| 6.1.8   | 1         | 0.46%   |
| 6.1.55  | 1         | 0.46%   |
| 6.1.14  | 1         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 37        | 17.21%  |
| 5.10    | 24        | 11.16%  |
| 5.4     | 22        | 10.23%  |
| 6.2     | 14        | 6.51%   |
| 6.1     | 12        | 5.58%   |
| 6.4     | 11        | 5.12%   |
| 5.13    | 11        | 5.12%   |
| 6.5     | 8         | 3.72%   |
| 5.16    | 8         | 3.72%   |
| 4.19    | 8         | 3.72%   |
| 5.19    | 7         | 3.26%   |
| 5.11    | 6         | 2.79%   |
| 5.8     | 5         | 2.33%   |
| 5.3     | 5         | 2.33%   |
| 6.6     | 4         | 1.86%   |
| 5.17    | 4         | 1.86%   |
| 4.9     | 4         | 1.86%   |
| 4.15    | 4         | 1.86%   |
| 6.3     | 3         | 1.4%    |
| 5.14    | 3         | 1.4%    |
| 6.0     | 2         | 0.93%   |
| 5.6     | 2         | 0.93%   |
| 5.18    | 2         | 0.93%   |
| 5.12    | 2         | 0.93%   |
| 5.0     | 2         | 0.93%   |
| 6.8     | 1         | 0.47%   |
| 6.7     | 1         | 0.47%   |
| 5.9     | 1         | 0.47%   |
| 5.5     | 1         | 0.47%   |
| 4.18    | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 177       | 93.16%  |
| i686   | 13        | 6.84%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 66        | 32.84%  |
| KDE5          | 51        | 25.37%  |
| XFCE          | 29        | 14.43%  |
| X-Cinnamon    | 12        | 5.97%   |
| Unknown       | 10        | 4.98%   |
| KDE           | 6         | 2.99%   |
| MATE          | 5         | 2.49%   |
| LXQt          | 5         | 2.49%   |
| KDE4          | 4         | 1.99%   |
| Cinnamon      | 3         | 1.49%   |
| Unity         | 2         | 1%      |
| Budgie        | 2         | 1%      |
| Pantheon      | 1         | 0.5%    |
| Openbox       | 1         | 0.5%    |
| KDE6          | 1         | 0.5%    |
| GNOME Classic | 1         | 0.5%    |
| Deepin        | 1         | 0.5%    |
| awesome       | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 156       | 79.59%  |
| Wayland | 37        | 18.88%  |
| Tty     | 2         | 1.02%   |
| Unknown | 1         | 0.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 63        | 31.66%  |
| SDDM    | 42        | 21.11%  |
| LightDM | 34        | 17.09%  |
| GDM3    | 27        | 13.57%  |
| GDM     | 26        | 13.07%  |
| KDM     | 4         | 2.01%   |
| TDM     | 3         | 1.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_VE   | 107       | 53.5%   |
| en_US   | 58        | 29%     |
| es_ES   | 16        | 8%      |
| Unknown | 8         | 4%      |
| es_MX   | 7         | 3.5%    |
| es_US   | 2         | 1%      |
| en_CA   | 1         | 0.5%    |
| C       | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 119       | 61.03%  |
| EFI  | 76        | 38.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 148       | 75.13%  |
| Overlay | 20        | 10.15%  |
| Btrfs   | 15        | 7.61%   |
| Tmpfs   | 7         | 3.55%   |
| Xfs     | 4         | 2.03%   |
| Unknown | 3         | 1.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 84        | 42%     |
| Unknown | 71        | 35.5%   |
| MBR     | 45        | 22.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 163       | 82.74%  |
| Yes       | 34        | 17.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 124       | 64.92%  |
| Yes       | 67        | 35.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo                                   | 31        | 16.32%  |
| Dell                                     | 31        | 16.32%  |
| VIT                                      | 27        | 14.21%  |
| Hewlett-Packard                          | 26        | 13.68%  |
| ASUSTek Computer                         | 13        | 6.84%   |
| Acer                                     | 12        | 6.32%   |
| Intel                                    | 9         | 4.74%   |
| Unknown                                  | 7         | 3.68%   |
| Google                                   | 6         | 3.16%   |
| Toshiba                                  | 3         | 1.58%   |
| Shanghai Zhaoxin Semiconductor           | 3         | 1.58%   |
| Pegatron                                 | 3         | 1.58%   |
| Notebook                                 | 3         | 1.58%   |
| Siragon                                  | 2         | 1.05%   |
| Samsung Electronics                      | 2         | 1.05%   |
| MSI                                      | 2         | 1.05%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. | 1         | 0.53%   |
| UNIQCELL                                 | 1         | 0.53%   |
| Sony                                     | 1         | 0.53%   |
| Panasonic                                | 1         | 0.53%   |
| GPU Company                              | 1         | 0.53%   |
| Gateway                                  | 1         | 0.53%   |
| Exo                                      | 1         | 0.53%   |
| Clevo                                    | 1         | 0.53%   |
| AVITA                                    | 1         | 0.53%   |
| Alienware                                | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel powered classmate PC                            | 9         | 4.74%   |
| VIT P2400                                             | 8         | 4.21%   |
| Unknown                                               | 7         | 3.68%   |
| VIT P3400                                             | 5         | 2.63%   |
| VIT P2402                                             | 5         | 2.63%   |
| VIT P1400                                             | 3         | 1.58%   |
| VIT M2420                                             | 3         | 1.58%   |
| Shanghai Zhaoxin ZXE CRB                              | 3         | 1.58%   |
| HP Pavilion dv5                                       | 3         | 1.58%   |
| Google Candy                                          | 3         | 1.58%   |
| VIT M2421                                             | 2         | 1.05%   |
| Notebook W54BL                                        | 2         | 1.05%   |
| Lenovo IdeaPad S100c 20194                            | 2         | 1.05%   |
| Lenovo 3000 N200 0769ARS                              | 2         | 1.05%   |
| HP Compaq Presario C700                               | 2         | 1.05%   |
| Dell Inspiron 1545                                    | 2         | 1.05%   |
| ASUS VivoBook_ASUSLaptop K3605VC_K3605VC              | 2         | 1.05%   |
| ASUS ASUS TUF Gaming F17 FX706HM_TUF706HM             | 2         | 1.05%   |
| Acer Aspire 4739Z                                     | 2         | 1.05%   |
| VIT P2423                                             | 1         | 0.53%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. VIT P2460-02 | 1         | 0.53%   |
| UNIQCELL Q15.6                                        | 1         | 0.53%   |
| Toshiba Satellite E55t-A                              | 1         | 0.53%   |
| Toshiba Satellite A205                                | 1         | 0.53%   |
| Toshiba ENCORE 2 WT8-B                                | 1         | 0.53%   |
| Sony VGN-FW510F                                       | 1         | 0.53%   |
| Siragon MN-50                                         | 1         | 0.53%   |
| SIRAGON LM-C100                                       | 1         | 0.53%   |
| Samsung 905S3G/906S3G/915S3G                          | 1         | 0.53%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.53%   |
| Pegatron T14AF                                        | 1         | 0.53%   |
| Pegatron H36Y                                         | 1         | 0.53%   |
| Pegatron B74                                          | 1         | 0.53%   |
| Panasonic CF-31RECAXDR                                | 1         | 0.53%   |
| Notebook NL40_50CU                                    | 1         | 0.53%   |
| MSI MS-1454                                           | 1         | 0.53%   |
| MSI GL73 9SD                                          | 1         | 0.53%   |
| Lenovo Z50-75 80EC                                    | 1         | 0.53%   |
| Lenovo ThinkPad X201 3680AE2                          | 1         | 0.53%   |
| Lenovo ThinkPad T490 20N2000LSP                       | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Dell Inspiron                                | 16        | 8.42%   |
| Lenovo IdeaPad                               | 13        | 6.84%   |
| HP Pavilion                                  | 11        | 5.79%   |
| Acer Aspire                                  | 11        | 5.79%   |
| Intel powered                                | 9         | 4.74%   |
| VIT P2400                                    | 8         | 4.21%   |
| Lenovo ThinkPad                              | 7         | 3.68%   |
| Dell Latitude                                | 7         | 3.68%   |
| Unknown                                      | 7         | 3.68%   |
| VIT P3400                                    | 5         | 2.63%   |
| VIT P2402                                    | 5         | 2.63%   |
| ASUS ASUS                                    | 5         | 2.63%   |
| Lenovo 3000                                  | 4         | 2.11%   |
| HP Laptop                                    | 4         | 2.11%   |
| Dell Vostro                                  | 4         | 2.11%   |
| ASUS VivoBook                                | 4         | 2.11%   |
| VIT P1400                                    | 3         | 1.58%   |
| VIT M2420                                    | 3         | 1.58%   |
| Shanghai Zhaoxin ZXE                         | 3         | 1.58%   |
| HP Compaq                                    | 3         | 1.58%   |
| Google Candy                                 | 3         | 1.58%   |
| VIT M2421                                    | 2         | 1.05%   |
| Toshiba Satellite                            | 2         | 1.05%   |
| Notebook W54BL                               | 2         | 1.05%   |
| Lenovo Legion                                | 2         | 1.05%   |
| HP ProBook                                   | 2         | 1.05%   |
| HP Presario                                  | 2         | 1.05%   |
| HP EliteBook                                 | 2         | 1.05%   |
| Dell Precision                               | 2         | 1.05%   |
| VIT P2423                                    | 1         | 0.53%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. VIT | 1         | 0.53%   |
| UNIQCELL Q15.6                               | 1         | 0.53%   |
| Toshiba ENCORE                               | 1         | 0.53%   |
| Sony VGN-FW510F                              | 1         | 0.53%   |
| Siragon MN-50                                | 1         | 0.53%   |
| SIRAGON LM-C100                              | 1         | 0.53%   |
| Samsung 905S3G                               | 1         | 0.53%   |
| Samsung 355V4C                               | 1         | 0.53%   |
| Pegatron T14AF                               | 1         | 0.53%   |
| Pegatron H36Y                                | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 24        | 12.63%  |
| 2012    | 20        | 10.53%  |
| 2011    | 20        | 10.53%  |
| 2022    | 13        | 6.84%   |
| 2020    | 11        | 5.79%   |
| 2019    | 11        | 5.79%   |
| 2008    | 11        | 5.79%   |
| 2007    | 11        | 5.79%   |
| 2010    | 10        | 5.26%   |
| 2023    | 9         | 4.74%   |
| 2021    | 9         | 4.74%   |
| 2018    | 9         | 4.74%   |
| 2014    | 9         | 4.74%   |
| 2009    | 6         | 3.16%   |
| 2015    | 5         | 2.63%   |
| 2017    | 4         | 2.11%   |
| Unknown | 3         | 1.58%   |
| 2016    | 2         | 1.05%   |
| 2006    | 2         | 1.05%   |
| 2024    | 1         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 190       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 182       | 95.79%  |
| Enabled  | 8         | 4.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 184       | 96.84%  |
| Yes  | 6         | 3.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 53        | 27.46%  |
| 4.01-8.0   | 44        | 22.8%   |
| 1.01-2.0   | 32        | 16.58%  |
| 8.01-16.0  | 30        | 15.54%  |
| 16.01-24.0 | 16        | 8.29%   |
| 2.01-3.0   | 9         | 4.66%   |
| 32.01-64.0 | 6         | 3.11%   |
| 24.01-32.0 | 2         | 1.04%   |
| 0.51-1.0   | 1         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 75        | 34.4%   |
| 2.01-3.0   | 56        | 25.69%  |
| 4.01-8.0   | 28        | 12.84%  |
| 0.51-1.0   | 27        | 12.39%  |
| 3.01-4.0   | 23        | 10.55%  |
| 8.01-16.0  | 6         | 2.75%   |
| 0.01-0.5   | 2         | 0.92%   |
| 16.01-24.0 | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 130       | 66.67%  |
| 2      | 58        | 29.74%  |
| 3      | 6         | 3.08%   |
| 0      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 101       | 52.88%  |
| Yes       | 90        | 47.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 82.81%  |
| No        | 33        | 17.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 185       | 97.37%  |
| No        | 5         | 2.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 60.94%  |
| No        | 75        | 39.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Venezuela | 190       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 79        | 38.16%  |
| Maracaibo                  | 21        | 10.14%  |
| Maracay                    | 10        | 4.83%   |
| Barquisimeto               | 8         | 3.86%   |
| Valencia                   | 7         | 3.38%   |
| Mérida                    | 7         | 3.38%   |
| Barcelona                  | 6         | 2.9%    |
| Ciudad Guayana             | 4         | 1.93%   |
| San Cristóbal             | 3         | 1.45%   |
| San Carlos del Zulia       | 3         | 1.45%   |
| Maturín                   | 3         | 1.45%   |
| Lecherias                  | 3         | 1.45%   |
| San Juan de los Morros     | 2         | 0.97%   |
| Punto Fijo                 | 2         | 0.97%   |
| Puerto Ordaz and San Felix | 2         | 0.97%   |
| Porlamar                   | 2         | 0.97%   |
| La Guaira                  | 2         | 0.97%   |
| Guatire                    | 2         | 0.97%   |
| Cagua                      | 2         | 0.97%   |
| Araure                     | 2         | 0.97%   |
| Anaco                      | 2         | 0.97%   |
| Acarigua                   | 2         | 0.97%   |
| Villa de Cura              | 1         | 0.48%   |
| Vigia                      | 1         | 0.48%   |
| Tucape                     | 1         | 0.48%   |
| San Juan Bautista          | 1         | 0.48%   |
| San Jose de Guanipa        | 1         | 0.48%   |
| San Felipe                 | 1         | 0.48%   |
| San Diego                  | 1         | 0.48%   |
| San Antonio de Los Altos   | 1         | 0.48%   |
| Puerto Cumarebo            | 1         | 0.48%   |
| Puerto Cruz                | 1         | 0.48%   |
| Petare                     | 1         | 0.48%   |
| Parroquia El Recreo        | 1         | 0.48%   |
| Naguanagua                 | 1         | 0.48%   |
| Miranda                    | 1         | 0.48%   |
| Mariara                    | 1         | 0.48%   |
| Maiquetia                  | 1         | 0.48%   |
| Macuto                     | 1         | 0.48%   |
| Los Palos Grandes          | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 36        | 39     | 15.86%  |
| WDC                       | 32        | 45     | 14.1%   |
| Toshiba                   | 22        | 24     | 9.69%   |
| Unknown                   | 17        | 23     | 7.49%   |
| Samsung Electronics       | 17        | 17     | 7.49%   |
| SanDisk                   | 10        | 15     | 4.41%   |
| Intel                     | 10        | 15     | 4.41%   |
| Hitachi                   | 9         | 10     | 3.96%   |
| Micron Technology         | 7         | 10     | 3.08%   |
| LITEONIT                  | 6         | 10     | 2.64%   |
| Crucial                   | 6         | 9      | 2.64%   |
| SK hynix                  | 5         | 7      | 2.2%    |
| HGST                      | 5         | 5      | 2.2%    |
| PNY                       | 4         | 4      | 1.76%   |
| Kingston                  | 4         | 6      | 1.76%   |
| SPCC                      | 3         | 6      | 1.32%   |
| addlink                   | 3         | 3      | 1.32%   |
| Team                      | 2         | 2      | 0.88%   |
| Silicon Motion            | 2         | 3      | 0.88%   |
| Patriot                   | 2         | 2      | 0.88%   |
| HUAWEI                    | 2         | 2      | 0.88%   |
| Fujitsu                   | 2         | 2      | 0.88%   |
| China                     | 2         | 2      | 0.88%   |
| BIWIN                     | 2         | 3      | 0.88%   |
| A-DATA Technology         | 2         | 2      | 0.88%   |
| WALRAM                    | 1         | 1      | 0.44%   |
| Vaseky                    | 1         | 1      | 0.44%   |
| UMIS                      | 1         | 1      | 0.44%   |
| Saichi                    | 1         | 1      | 0.44%   |
| PUSKILL                   | 1         | 1      | 0.44%   |
| Phison                    | 1         | 1      | 0.44%   |
| Micron/Crucial Technology | 1         | 1      | 0.44%   |
| Lexar                     | 1         | 1      | 0.44%   |
| KingFast                  | 1         | 3      | 0.44%   |
| Intenso                   | 1         | 1      | 0.44%   |
| Emtec                     | 1         | 2      | 0.44%   |
| Dell                      | 1         | 2      | 0.44%   |
| Dahua                     | 1         | 1      | 0.44%   |
| Apacer                    | 1         | 1      | 0.44%   |
| Unknown                   | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| LITEONIT LMS-32L6M 32GB SSD                     | 5         | 2.14%   |
| WDC WD3200BPVT-22JJ5T0 320GB                    | 4         | 1.71%   |
| Seagate ST500LT012-9WS142 500GB                 | 4         | 1.71%   |
| WDC WD10JPVX-22JC3T0 1TB                        | 3         | 1.28%   |
| Unknown NVMe SSD Drive 512GB                    | 3         | 1.28%   |
| Toshiba MQ04ABF100 1TB                          | 3         | 1.28%   |
| Seagate ST320LT012-9WS14C 320GB                 | 3         | 1.28%   |
| Seagate ST320LT012-1DG14C 320GB                 | 3         | 1.28%   |
| Seagate ST250LM004 HN-M250MBB 250GB             | 3         | 1.28%   |
| WDC WD5000LPVX-22V0TT0 500GB                    | 2         | 0.85%   |
| WDC WD5000LPVT-08G33T1 500GB                    | 2         | 0.85%   |
| WDC WD3200BEVT-00A0RT0 320GB                    | 2         | 0.85%   |
| WDC WD1600BEVT-22ZCT0 160GB                     | 2         | 0.85%   |
| WDC WD1200BEVS-60UST0 120GB                     | 2         | 0.85%   |
| Unknown MMC Card  64GB                          | 2         | 0.85%   |
| Unknown MMC Card  16GB                          | 2         | 0.85%   |
| Unknown HAG2e  16GB                             | 2         | 0.85%   |
| Toshiba MQ01ABF050 500GB                        | 2         | 0.85%   |
| Toshiba MQ01ABF032 320GB                        | 2         | 0.85%   |
| Toshiba MQ01ABD050 500GB                        | 2         | 0.85%   |
| Toshiba MK3276GSX 320GB                         | 2         | 0.85%   |
| Toshiba MK3275GSX 320GB                         | 2         | 0.85%   |
| SK hynix HFM001TD3JX013N 1024GB                 | 2         | 0.85%   |
| Seagate ST9500325AS 500GB                       | 2         | 0.85%   |
| Seagate ST9320325AS 320GB                       | 2         | 0.85%   |
| Seagate ST500LT012-1DG142 500GB                 | 2         | 0.85%   |
| Seagate ST500LM021-1KJ152 500GB                 | 2         | 0.85%   |
| Seagate ST320LM001 HN-M320MBB 320GB             | 2         | 0.85%   |
| Seagate ST320LM000 HM321HI 320GB                | 2         | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 2         | 0.85%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB | 2         | 0.85%   |
| SanDisk NVMe SSD Drive 1TB                      | 2         | 0.85%   |
| Samsung MZALQ512HBLU-00BL2 512GB                | 2         | 0.85%   |
| Samsung HN-M320MBB 320GB                        | 2         | 0.85%   |
| Samsung HM250HI 250GB                           | 2         | 0.85%   |
| PNY CS900 480GB SSD                             | 2         | 0.85%   |
| PNY CS900 1TB SSD                               | 2         | 0.85%   |
| Micron 2450_MTFDKBA512TFK 512GB                 | 2         | 0.85%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                   | 2         | 0.85%   |
| Intel SSDPEKNU512GZ 512GB                       | 2         | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 35     | 30.56%  |
| WDC                 | 30        | 40     | 27.78%  |
| Toshiba             | 21        | 23     | 19.44%  |
| Hitachi             | 9         | 10     | 8.33%   |
| Samsung Electronics | 6         | 6      | 5.56%   |
| HGST                | 5         | 5      | 4.63%   |
| Unknown             | 2         | 2      | 1.85%   |
| Fujitsu             | 2         | 2      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 11.76%  |
| LITEONIT            | 6         | 10     | 11.76%  |
| Crucial             | 6         | 9      | 11.76%  |
| PNY                 | 4         | 4      | 7.84%   |
| Kingston            | 3         | 5      | 5.88%   |
| SPCC                | 2         | 4      | 3.92%   |
| SanDisk             | 2         | 3      | 3.92%   |
| Patriot             | 2         | 2      | 3.92%   |
| China               | 2         | 2      | 3.92%   |
| A-DATA Technology   | 2         | 2      | 3.92%   |
| WALRAM              | 1         | 1      | 1.96%   |
| Vaseky              | 1         | 1      | 1.96%   |
| Toshiba             | 1         | 1      | 1.96%   |
| Team                | 1         | 1      | 1.96%   |
| Saichi              | 1         | 1      | 1.96%   |
| PUSKILL             | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 3      | 1.96%   |
| Lexar               | 1         | 1      | 1.96%   |
| KingFast            | 1         | 3      | 1.96%   |
| Intenso             | 1         | 1      | 1.96%   |
| Intel               | 1         | 1      | 1.96%   |
| Emtec               | 1         | 2      | 1.96%   |
| Dell                | 1         | 2      | 1.96%   |
| Dahua               | 1         | 1      | 1.96%   |
| BIWIN               | 1         | 2      | 1.96%   |
| addlink             | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 106       | 123    | 48.62%  |
| SSD     | 49        | 70     | 22.48%  |
| NVMe    | 45        | 68     | 20.64%  |
| MMC     | 13        | 18     | 5.96%   |
| Unknown | 5         | 6      | 2.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 141       | 190    | 68.12%  |
| NVMe | 45        | 68     | 21.74%  |
| MMC  | 13        | 18     | 6.28%   |
| SAS  | 8         | 9      | 3.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 125       | 159    | 82.78%  |
| 0.51-1.0   | 25        | 33     | 16.56%  |
| 1.01-2.0   | 1         | 1      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 63        | 31.19%  |
| 101-250        | 54        | 26.73%  |
| 501-1000       | 28        | 13.86%  |
| 1-20           | 21        | 10.4%   |
| 51-100         | 13        | 6.44%   |
| 21-50          | 11        | 5.45%   |
| 1001-2000      | 6         | 2.97%   |
| More than 3000 | 2         | 0.99%   |
| 2001-3000      | 2         | 0.99%   |
| Unknown        | 2         | 0.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 79        | 37.26%  |
| 21-50     | 41        | 19.34%  |
| 101-250   | 33        | 15.57%  |
| 51-100    | 30        | 14.15%  |
| 251-500   | 18        | 8.49%   |
| 501-1000  | 8         | 3.77%   |
| Unknown   | 2         | 0.94%   |
| 2001-3000 | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD1200BEVS-60UST0 120GB          | 2         | 2      | 5.71%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 5.71%   |
| Samsung Electronics HM250HI 250GB    | 2         | 2      | 5.71%   |
| Hitachi HTS725050A9A364 500GB        | 2         | 2      | 5.71%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 1      | 2.86%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 2.86%   |
| WDC WD3200BEVT-00A0RT0 320GB         | 1         | 1      | 2.86%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2      | 2.86%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 2.86%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 2.86%   |
| Toshiba MK3276GSX 320GB              | 1         | 1      | 2.86%   |
| Toshiba MK3275GSX 320GB              | 1         | 2      | 2.86%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 2.86%   |
| Toshiba MK2565GSX 250GB              | 1         | 1      | 2.86%   |
| Toshiba MK1032GSX 100GB              | 1         | 1      | 2.86%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 2.86%   |
| Seagate ST9320325AS 320GB            | 1         | 1      | 2.86%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 2.86%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 2.86%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 2.86%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 2.86%   |
| Samsung Electronics HN-M320MBB 320GB | 1         | 1      | 2.86%   |
| Samsung Electronics HM321HI 320GB    | 1         | 1      | 2.86%   |
| Samsung Electronics HM121HI 120GB    | 1         | 1      | 2.86%   |
| Intel SSDPEKKW256G7 256GB            | 1         | 1      | 2.86%   |
| Intel SSDPEKKF512G7L 512GB           | 1         | 1      | 2.86%   |
| Hitachi HTS543232L9A300 320GB        | 1         | 1      | 2.86%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1      | 2.86%   |
| Hitachi HTS542525K9SA00 250GB        | 1         | 1      | 2.86%   |
| HGST HTS545050A7E380 500GB           | 1         | 1      | 2.86%   |
| HGST HTS541010A7E630 1TB             | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 8      | 20%     |
| Seagate             | 7         | 7      | 20%     |
| WDC                 | 6         | 7      | 17.14%  |
| Samsung Electronics | 5         | 5      | 14.29%  |
| Hitachi             | 5         | 5      | 14.29%  |
| Intel               | 2         | 2      | 5.71%   |
| HGST                | 2         | 2      | 5.71%   |
| SK hynix            | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 8      | 21.88%  |
| Seagate             | 7         | 7      | 21.88%  |
| WDC                 | 6         | 7      | 18.75%  |
| Samsung Electronics | 5         | 5      | 15.63%  |
| Hitachi             | 5         | 5      | 15.63%  |
| HGST                | 2         | 2      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 34     | 91.43%  |
| NVMe | 3         | 3      | 8.57%   |

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
| Detected | 97        | 148    | 47.55%  |
| Works    | 72        | 100    | 35.29%  |
| Malfunc  | 35        | 37     | 17.16%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 150       | 70.75%  |
| AMD                         | 24        | 11.32%  |
| SanDisk                     | 9         | 4.25%   |
| Micron Technology           | 6         | 2.83%   |
| SK hynix                    | 5         | 2.36%   |
| Samsung Electronics         | 5         | 2.36%   |
| Silicon Motion              | 3         | 1.42%   |
| Phison Electronics          | 3         | 1.42%   |
| Jiangsu Huacun Elec.        | 3         | 1.42%   |
| Union Memory (Shenzhen)     | 1         | 0.47%   |
| Micron/Crucial Technology   | 1         | 0.47%   |
| MAXIO Technology (Hangzhou) | 1         | 0.47%   |
| Kingston Technology Company | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 26        | 10.88%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 7.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 6.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 13        | 5.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 4.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 10        | 4.18%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 3.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 3.35%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 7         | 2.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 7         | 2.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 2.51%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 5         | 2.09%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 1.67%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 4         | 1.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 1.67%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.26%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 1.26%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 3         | 1.26%   |
| Jiangsu Huacun Elec. MMY MMSP350 PCIe 3 NVMe SSD (DRAM-less)                   | 3         | 1.26%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 3         | 1.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.26%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.26%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2         | 0.84%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2         | 0.84%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.84%   |
| Intel SSD 600P Series                                                          | 2         | 0.84%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.84%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.84%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.84%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 0.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 2         | 0.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 0.84%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 0.84%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 134       | 58.26%  |
| NVMe | 45        | 19.57%  |
| RAID | 26        | 11.3%   |
| IDE  | 25        | 10.87%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 159       | 83.68%  |
| AMD          | 28        | 14.74%  |
| CentaurHauls | 3         | 1.58%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz                | 8         | 4.21%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 6         | 3.16%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 5         | 2.63%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 4         | 2.11%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 4         | 2.11%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 4         | 2.11%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 3         | 1.58%   |
| Intel Core i7-3537U CPU @ 2.00GHz              | 3         | 1.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 3         | 1.58%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 3         | 1.58%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 3         | 1.58%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 3         | 1.58%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 3         | 1.58%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 3         | 1.58%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 3         | 1.58%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 3         | 1.58%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 1.05%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 2         | 1.05%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 2         | 1.05%   |
| Intel Core i5-3337U CPU @ 1.80GHz              | 2         | 1.05%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 1.05%   |
| Intel Core i3-4000M CPU @ 2.40GHz              | 2         | 1.05%   |
| Intel Core i3-2350M CPU @ 2.30GHz              | 2         | 1.05%   |
| Intel Core i3 CPU M 330 @ 2.13GHz              | 2         | 1.05%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz           | 2         | 1.05%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz           | 2         | 1.05%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 2         | 1.05%   |
| Intel Celeron CPU N2805 @ 1.46GHz              | 2         | 1.05%   |
| Intel Atom CPU N570 @ 1.66GHz                  | 2         | 1.05%   |
| Intel 13th Gen Core i9-13900H                  | 2         | 1.05%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 2         | 1.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 2         | 1.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 1.05%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 2         | 1.05%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 2         | 1.05%   |
| AMD C-70 APU with Radeon HD Graphics           | 2         | 1.05%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 0.53%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz         | 1         | 0.53%   |
| Intel Pentium CPU N3710 @ 1.60GHz              | 1         | 0.53%   |
| Intel Pentium CPU B940 @ 2.00GHz               | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 32        | 16.84%  |
| Intel Core i3                        | 28        | 14.74%  |
| Intel Celeron                        | 22        | 11.58%  |
| Other                                | 18        | 9.47%   |
| Intel Core i7                        | 18        | 9.47%   |
| Intel Core 2 Duo                     | 15        | 7.89%   |
| Intel Atom                           | 11        | 5.79%   |
| Intel Pentium                        | 7         | 3.68%   |
| AMD Ryzen 5                          | 7         | 3.68%   |
| AMD Ryzen 7                          | 6         | 3.16%   |
| Intel Pentium Dual                   | 5         | 2.63%   |
| Intel Pentium Dual-Core              | 2         | 1.05%   |
| Intel Genuine                        | 2         | 1.05%   |
| AMD Ryzen 3                          | 2         | 1.05%   |
| AMD C-70                             | 2         | 1.05%   |
| AMD A10                              | 2         | 1.05%   |
| Intel Pentium Silver                 | 1         | 0.53%   |
| Intel Core i9                        | 1         | 0.53%   |
| Intel Core 2                         | 1         | 0.53%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.53%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.53%   |
| AMD Quad-Core                        | 1         | 0.53%   |
| AMD Phenom II                        | 1         | 0.53%   |
| AMD Mobile Sempron                   | 1         | 0.53%   |
| AMD E1                               | 1         | 0.53%   |
| AMD E                                | 1         | 0.53%   |
| AMD A6                               | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 125       | 65.79%  |
| 4       | 32        | 16.84%  |
| 8       | 9         | 4.74%   |
| 1       | 9         | 4.74%   |
| 6       | 7         | 3.68%   |
| 14      | 3         | 1.58%   |
| Unknown | 2         | 1.05%   |
| 24      | 1         | 0.53%   |
| 12      | 1         | 0.53%   |
| 10      | 1         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 190       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 118       | 62.11%  |
| 1       | 70        | 36.84%  |
| Unknown | 2         | 1.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 184       | 96.84%  |
| 64-bit         | 3         | 1.58%   |
| 32-bit         | 3         | 1.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 33%     |
| 0x306a9    | 17        | 8.5%    |
| 0x206a7    | 17        | 8.5%    |
| 0x1067a    | 11        | 5.5%    |
| 0x6fd      | 8         | 4%      |
| 0x30678    | 7         | 3.5%    |
| 0x106ca    | 6         | 3%      |
| 0x806e9    | 5         | 2.5%    |
| 0x806c1    | 4         | 2%      |
| 0x20655    | 4         | 2%      |
| 0x806ec    | 3         | 1.5%    |
| 0x406e3    | 3         | 1.5%    |
| 0x40651    | 3         | 1.5%    |
| 0x306c3    | 3         | 1.5%    |
| 0x806ea    | 2         | 1%      |
| 0x806d1    | 2         | 1%      |
| 0x306d4    | 2         | 1%      |
| 0x30673    | 2         | 1%      |
| 0x08608103 | 2         | 1%      |
| 0x08108102 | 2         | 1%      |
| 0x05000119 | 2         | 1%      |
| 0x0500010d | 2         | 1%      |
| 0x02000057 | 2         | 1%      |
| 0x906ea    | 1         | 0.5%    |
| 0x906e9    | 1         | 0.5%    |
| 0x906a4    | 1         | 0.5%    |
| 0x806eb    | 1         | 0.5%    |
| 0x706e5    | 1         | 0.5%    |
| 0x706a8    | 1         | 0.5%    |
| 0x6f6      | 1         | 0.5%    |
| 0x6ec      | 1         | 0.5%    |
| 0x506e3    | 1         | 0.5%    |
| 0x406c4    | 1         | 0.5%    |
| 0x30661    | 1         | 0.5%    |
| 0x20652    | 1         | 0.5%    |
| 0x106c2    | 1         | 0.5%    |
| 0x0a50000d | 1         | 0.5%    |
| 0x08608104 | 1         | 0.5%    |
| 0x08600104 | 1         | 0.5%    |
| 0x08600103 | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 25        | 13.16%  |
| IvyBridge        | 24        | 12.63%  |
| KabyLake         | 15        | 7.89%   |
| Core             | 14        | 7.37%   |
| Silvermont       | 11        | 5.79%   |
| Westmere         | 10        | 5.26%   |
| Penryn           | 10        | 5.26%   |
| Bonnell          | 10        | 5.26%   |
| Unknown          | 8         | 4.21%   |
| Haswell          | 7         | 3.68%   |
| Alderlake Hybrid | 7         | 3.68%   |
| TigerLake        | 5         | 2.63%   |
| Icelake          | 5         | 2.63%   |
| Zen+             | 4         | 2.11%   |
| Skylake          | 4         | 2.11%   |
| Goldmont plus    | 4         | 2.11%   |
| Bobcat           | 4         | 2.11%   |
| Zen 2            | 3         | 1.58%   |
| Excavator        | 3         | 1.58%   |
| CometLake        | 3         | 1.58%   |
| Broadwell        | 3         | 1.58%   |
| Zen              | 2         | 1.05%   |
| K8 & K10 hybrid  | 2         | 1.05%   |
| Zen 3            | 1         | 0.53%   |
| Steamroller      | 1         | 0.53%   |
| P6               | 1         | 0.53%   |
| K8 Hammer        | 1         | 0.53%   |
| K10              | 1         | 0.53%   |
| Jaguar           | 1         | 0.53%   |
| Goldmont         | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 155       | 75.24%  |
| AMD     | 30        | 14.56%  |
| Nvidia  | 18        | 8.74%   |
| Zhaoxin | 3         | 1.46%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 10.91%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 10.45%  |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 11        | 5%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 11        | 5%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 5%      |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 4.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 4.09%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 8         | 3.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.27%   |
| AMD Lucienne                                                                             | 5         | 2.27%   |
| Intel HD Graphics 620                                                                    | 4         | 1.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.82%   |
| Zhaoxin KX-6000 C-960 GPU                                                                | 3         | 1.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.36%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.36%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.36%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.36%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.36%   |
| Nvidia GA107M [GeForce RTX 3050 4GB Laptop GPU]                                          | 2         | 0.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.91%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.91%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.91%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 0.91%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.91%   |
| Intel HD Graphics 630                                                                    | 2         | 0.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.91%   |
| AMD Wrestler [Radeon HD 7290]                                                            | 2         | 0.91%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.91%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 2         | 0.91%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.91%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.45%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 134       | 70.16%  |
| 1 x AMD        | 27        | 14.14%  |
| Intel + Nvidia | 12        | 6.28%   |
| 2 x Intel      | 6         | 3.14%   |
| 1 x Nvidia     | 5         | 2.62%   |
| 1 x Zhaoxin    | 3         | 1.57%   |
| Intel + AMD    | 2         | 1.05%   |
| Other          | 1         | 0.52%   |
| AMD + Nvidia   | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 171       | 89.53%  |
| Proprietary | 13        | 6.81%   |
| Unknown     | 7         | 3.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 157       | 81.35%  |
| 0.01-0.5   | 20        | 10.36%  |
| 1.01-2.0   | 6         | 3.11%   |
| 3.01-4.0   | 4         | 2.07%   |
| 0.51-1.0   | 4         | 2.07%   |
| 5.01-6.0   | 2         | 1.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 34        | 16.04%  |
| AU Optronics            | 34        | 16.04%  |
| BOE                     | 33        | 15.57%  |
| LG Display              | 27        | 12.74%  |
| Chimei Innolux          | 24        | 11.32%  |
| InfoVision              | 9         | 4.25%   |
| LG Philips              | 7         | 3.3%    |
| Lenovo                  | 7         | 3.3%    |
| Chi Mei Optoelectronics | 7         | 3.3%    |
| Hewlett-Packard         | 6         | 2.83%   |
| HannStar                | 4         | 1.89%   |
| Goldstar                | 4         | 1.89%   |
| Dell                    | 3         | 1.42%   |
| PANDA                   | 2         | 0.94%   |
| Vizio                   | 1         | 0.47%   |
| ViewSonic               | 1         | 0.47%   |
| Toshiba                 | 1         | 0.47%   |
| Sharp                   | 1         | 0.47%   |
| Sceptre Tech            | 1         | 0.47%   |
| MStar                   | 1         | 0.47%   |
| KTC                     | 1         | 0.47%   |
| InnoLux Display         | 1         | 0.47%   |
| HKC                     | 1         | 0.47%   |
| ASUSTek Computer        | 1         | 0.47%   |
| Acer                    | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch | 7         | 3.29%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch      | 6         | 2.82%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch        | 5         | 2.35%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 3         | 1.41%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 3         | 1.41%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch          | 3         | 1.41%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 3         | 1.41%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                 | 3         | 1.41%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 3         | 1.41%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                 | 3         | 1.41%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 2         | 0.94%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.94%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch        | 2         | 0.94%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 2         | 0.94%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 2         | 0.94%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.94%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch          | 2         | 0.94%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 2         | 0.94%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 2         | 0.94%   |
| Chimei Innolux N160JME-GL2 CMN1627 1920x1200 344x215mm 16.0-inch     | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 340x190mm 15.3-inch      | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 2         | 0.94%   |
| BOE LCD Monitor BOE08C2 1920x1080 344x194mm 15.5-inch                | 2         | 0.94%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                 | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO8294 1920x1080 382x215mm 17.3-inch       | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch       | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO115C 1366x768 256x144mm 11.6-inch        | 2         | 0.94%   |
| Vizio E3D320VX VIZ0079 1920x1080 698x393mm 31.5-inch                 | 1         | 0.47%   |
| ViewSonic VA2252 Series VSC7731 1920x1080 476x268mm 21.5-inch        | 1         | 0.47%   |
| Toshiba LCD-MONITOR LCDE981 1280x720 400x250mm 18.6-inch             | 1         | 0.47%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch              | 1         | 0.47%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch       | 1         | 0.47%   |
| Samsung Electronics T27B550 SAM095C 1920x1080 598x336mm 27.0-inch    | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch  | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                     | 1         | 0.47%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 102       | 51.52%  |
| 1920x1080 (FHD)    | 50        | 25.25%  |
| 1280x800 (WXGA)    | 17        | 8.59%   |
| 1920x1200 (WUXGA)  | 4         | 2.02%   |
| 1600x900 (HD+)     | 4         | 2.02%   |
| 3840x2160 (4K)     | 3         | 1.52%   |
| 1440x900 (WXGA+)   | 3         | 1.52%   |
| 1280x1024 (SXGA)   | 3         | 1.52%   |
| 1024x600           | 3         | 1.52%   |
| 2560x1440 (QHD)    | 2         | 1.01%   |
| 1680x1050 (WSXGA+) | 2         | 1.01%   |
| 1360x768           | 2         | 1.01%   |
| 2560x1600          | 1         | 0.51%   |
| 2240x1400          | 1         | 0.51%   |
| 1280x720 (HD)      | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 74        | 35.24%  |
| 14      | 43        | 20.48%  |
| 13      | 34        | 16.19%  |
| 21      | 10        | 4.76%   |
| 17      | 8         | 3.81%   |
| 11      | 7         | 3.33%   |
| 10      | 6         | 2.86%   |
| 18      | 4         | 1.9%    |
| 27      | 3         | 1.43%   |
| 23      | 3         | 1.43%   |
| 16      | 3         | 1.43%   |
| 32      | 2         | 0.95%   |
| 24      | 2         | 0.95%   |
| 19      | 2         | 0.95%   |
| 12      | 2         | 0.95%   |
| Unknown | 2         | 0.95%   |
| 54      | 1         | 0.48%   |
| 52      | 1         | 0.48%   |
| 31      | 1         | 0.48%   |
| 22      | 1         | 0.48%   |
| 20      | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 150       | 71.77%  |
| 401-500     | 17        | 8.13%   |
| 201-300     | 17        | 8.13%   |
| 351-400     | 11        | 5.26%   |
| 501-600     | 7         | 3.35%   |
| 701-800     | 2         | 0.96%   |
| 1001-1500   | 2         | 0.96%   |
| Unknown     | 2         | 0.96%   |
| 601-700     | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 155       | 83.33%  |
| 16/10 | 28        | 15.05%  |
| 5/4   | 2         | 1.08%   |
| 3/2   | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 75        | 35.71%  |
| 101-110        | 74        | 35.24%  |
| 201-250        | 11        | 5.24%   |
| 51-60          | 7         | 3.33%   |
| 151-200        | 7         | 3.33%   |
| 121-130        | 7         | 3.33%   |
| 41-50          | 6         | 2.86%   |
| 141-150        | 4         | 1.9%    |
| 351-500        | 3         | 1.43%   |
| 301-350        | 3         | 1.43%   |
| 111-120        | 3         | 1.43%   |
| More than 1000 | 2         | 0.95%   |
| 71-80          | 2         | 0.95%   |
| 61-70          | 2         | 0.95%   |
| 251-300        | 2         | 0.95%   |
| Unknown        | 2         | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 99        | 47.83%  |
| 121-160       | 60        | 28.99%  |
| 51-100        | 37        | 17.87%  |
| 1-50          | 4         | 1.93%   |
| 161-240       | 4         | 1.93%   |
| Unknown       | 2         | 0.97%   |
| More than 240 | 1         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 156       | 79.19%  |
| 2     | 31        | 15.74%  |
| 0     | 7         | 3.55%   |
| 3     | 3         | 1.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 123       | 39.05%  |
| Intel                           | 69        | 21.9%   |
| Qualcomm Atheros                | 66        | 20.95%  |
| Broadcom                        | 19        | 6.03%   |
| MediaTek                        | 8         | 2.54%   |
| Broadcom Limited                | 6         | 1.9%    |
| TP-Link                         | 5         | 1.59%   |
| Xiaomi                          | 3         | 0.95%   |
| Marvell Technology Group        | 3         | 0.95%   |
| Samsung Electronics             | 2         | 0.63%   |
| Qualcomm Atheros Communications | 2         | 0.63%   |
| JMicron Technology              | 2         | 0.63%   |
| ASIX Electronics                | 2         | 0.63%   |
| ZyXEL Communications            | 1         | 0.32%   |
| Trendchip Technologies          | 1         | 0.32%   |
| Ralink Technology               | 1         | 0.32%   |
| Huawei Technologies             | 1         | 0.32%   |
| AMD                             | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 63        | 17.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 28        | 7.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 23        | 6.34%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 2.75%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 9         | 2.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 2.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.2%    |
| Intel Wireless 7265                                                     | 8         | 2.2%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 7         | 1.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.93%   |
| Intel Wireless 7260                                                     | 6         | 1.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 5         | 1.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.38%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 4         | 1.1%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 1.1%    |
| Intel Wireless 8265 / 8275                                              | 4         | 1.1%    |
| Intel WiFi Link 5100                                                    | 4         | 1.1%    |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 1.1%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.83%   |
| Intel Wireless 3165                                                     | 3         | 0.83%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.83%   |
| Intel Centrino Wireless-N 105                                           | 3         | 0.83%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.83%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.83%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.55%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 2         | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 0.55%   |
| Intel Wireless 8260                                                     | 2         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 33.67%  |
| Qualcomm Atheros                | 51        | 26.02%  |
| Realtek Semiconductor           | 46        | 23.47%  |
| Broadcom                        | 14        | 7.14%   |
| MediaTek                        | 8         | 4.08%   |
| TP-Link                         | 4         | 2.04%   |
| Broadcom Limited                | 3         | 1.53%   |
| Qualcomm Atheros Communications | 2         | 1.02%   |
| Xiaomi                          | 1         | 0.51%   |
| Ralink Technology               | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 23        | 11.73%  |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 5.1%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 9         | 4.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 4.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.08%   |
| Intel Wireless 7265                                                     | 8         | 4.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 3.57%   |
| Intel Wireless 7260                                                     | 6         | 3.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 4         | 2.04%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.04%   |
| Intel Wireless 8265 / 8275                                              | 4         | 2.04%   |
| Intel WiFi Link 5100                                                    | 4         | 2.04%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.04%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.53%   |
| Intel Wireless 3165                                                     | 3         | 1.53%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.53%   |
| Intel Centrino Wireless-N 105                                           | 3         | 1.53%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.53%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1.53%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.02%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 2         | 1.02%   |
| Intel Wireless 8260                                                     | 2         | 1.02%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.02%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.02%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.02%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.02%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.02%   |
| Intel Centrino Wireless-N 100                                           | 2         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.02%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 1.02%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                       | 1         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 99        | 60.74%  |
| Qualcomm Atheros         | 21        | 12.88%  |
| Intel                    | 20        | 12.27%  |
| Broadcom                 | 6         | 3.68%   |
| Marvell Technology Group | 3         | 1.84%   |
| Broadcom Limited         | 3         | 1.84%   |
| Xiaomi                   | 2         | 1.23%   |
| Samsung Electronics      | 2         | 1.23%   |
| JMicron Technology       | 2         | 1.23%   |
| ASIX Electronics         | 2         | 1.23%   |
| ZyXEL Communications     | 1         | 0.61%   |
| Trendchip Technologies   | 1         | 0.61%   |
| TP-Link                  | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 63        | 38.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 28        | 16.97%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 7         | 4.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5         | 3.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 2.42%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 1.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 1.21%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 1.21%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 1.21%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.21%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 1.21%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.21%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express            | 2         | 1.21%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.21%   |
| ZyXEL ADSL Modem Prestige 600 series                                   | 1         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.61%   |
| Trendchip Ethernet controller                                          | 1         | 0.61%   |
| TP-Link M7010                                                          | 1         | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.61%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.61%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.61%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.61%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.61%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 1         | 0.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.61%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 0.61%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.61%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.61%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.61%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 185       | 53.62%  |
| Ethernet | 158       | 45.8%   |
| Modem    | 2         | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 148       | 74.37%  |
| Ethernet | 51        | 25.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 147       | 77.37%  |
| 1     | 41        | 21.58%  |
| 0     | 2         | 1.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 189       | 98.44%  |
| Yes  | 3         | 1.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 36.44%  |
| Realtek Semiconductor           | 17        | 14.41%  |
| Qualcomm Atheros Communications | 17        | 14.41%  |
| IMC Networks                    | 17        | 14.41%  |
| Broadcom                        | 7         | 5.93%   |
| Lite-On Technology              | 5         | 4.24%   |
| Cambridge Silicon Radio         | 4         | 3.39%   |
| Hewlett-Packard                 | 2         | 1.69%   |
| Dell                            | 2         | 1.69%   |
| SiW                             | 1         | 0.85%   |
| Foxconn / Hon Hai               | 1         | 0.85%   |
| ASUSTek Computer                | 1         | 0.85%   |
| Alps Electric                   | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 18        | 15.25%  |
| Realtek Bluetooth Radio                                     | 10        | 8.47%   |
| Intel AX201 Bluetooth                                       | 8         | 6.78%   |
| Qualcomm Atheros  Bluetooth Device                          | 6         | 5.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 6         | 5.08%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 6         | 5.08%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 5         | 4.24%   |
| Intel Bluetooth Device                                      | 5         | 4.24%   |
| IMC Networks Wireless_Device                                | 5         | 4.24%   |
| IMC Networks Bluetooth                                      | 4         | 3.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 3.39%   |
| Realtek RTL8723B Bluetooth                                  | 3         | 2.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 2.54%   |
| Broadcom BCM2045 Bluetooth                                  | 3         | 2.54%   |
| Realtek RTL8723A Bluetooth                                  | 2         | 1.69%   |
| Qualcomm Atheros Bluetooth (AR3011)                         | 2         | 1.69%   |
| Lite-On Wireless_Device                                     | 2         | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.69%   |
| Intel AX200 Bluetooth                                       | 2         | 1.69%   |
| IMC Networks Bluetooth Radio                                | 2         | 1.69%   |
| SiW SiW                                                     | 1         | 0.85%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.85%   |
| Realtek 802.11ac WLAN Adapter                               | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.85%   |
| Lite-On Bluetooth Device                                    | 1         | 0.85%   |
| Lite-On BCM20702A0                                          | 1         | 0.85%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.85%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 0.85%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.85%   |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.85%   |
| Broadcom HP Portable Valentine                              | 1         | 0.85%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.85%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 0.85%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 0.85%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 0.85%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 159       | 75.36%  |
| AMD                   | 30        | 14.22%  |
| Nvidia                | 13        | 6.16%   |
| Zhaoxin               | 3         | 1.42%   |
| Texas Instruments     | 1         | 0.47%   |
| Realtek Semiconductor | 1         | 0.47%   |
| Microsoft             | 1         | 0.47%   |
| Logitech              | 1         | 0.47%   |
| Corsair               | 1         | 0.47%   |
| ASUSTek Computer      | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 34        | 13.6%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 6%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 6%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 4.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 4.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 4.4%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 4%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 4%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 3.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 3.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.4%    |
| AMD FCH Azalia Controller                                                                         | 6         | 2.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.6%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.6%    |
| AMD Wrestler HDMI Audio                                                                           | 4         | 1.6%    |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 3         | 1.2%    |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000/KX-7000 High Definition Audio Controller         | 3         | 1.2%    |
| Nvidia Audio device                                                                               | 3         | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.2%    |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.2%    |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.2%    |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.2%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.8%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.8%    |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 0.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.8%    |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.8%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2         | 0.8%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 20.12%  |
| SK hynix            | 33        | 19.53%  |
| Ramaxel Technology  | 20        | 11.83%  |
| Unknown             | 18        | 10.65%  |
| Micron Technology   | 18        | 10.65%  |
| Crucial             | 9         | 5.33%   |
| Kingston            | 8         | 4.73%   |
| Elpida              | 5         | 2.96%   |
| Unknown (ABCD)      | 2         | 1.18%   |
| Shenzhen WODPOSIT   | 2         | 1.18%   |
| Qimonda             | 2         | 1.18%   |
| Memox               | 2         | 1.18%   |
| Unknown             | 2         | 1.18%   |
| Unknown (081A)      | 1         | 0.59%   |
| Unknown (07F7)      | 1         | 0.59%   |
| Transcend           | 1         | 0.59%   |
| Timetec             | 1         | 0.59%   |
| Team                | 1         | 0.59%   |
| PNY                 | 1         | 0.59%   |
| Hikvision           | 1         | 0.59%   |
| Gold Key            | 1         | 0.59%   |
| ff                  | 1         | 0.59%   |
| Corsair             | 1         | 0.59%   |
| A-DATA Technology   | 1         | 0.59%   |
| <Invalid>           | 1         | 0.59%   |
| 4ea5                | 1         | 0.59%   |
| 48spaces            | 1         | 0.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s | 6         | 3.37%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s | 5         | 2.81%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 4         | 2.25%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s   | 4         | 2.25%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s | 4         | 2.25%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s  | 3         | 1.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 3         | 1.69%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s  | 3         | 1.69%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s   | 3         | 1.69%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s | 3         | 1.69%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 2         | 1.12%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s              | 2         | 1.12%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s   | 2         | 1.12%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 2         | 1.12%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s  | 2         | 1.12%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s  | 2         | 1.12%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s  | 2         | 1.12%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s | 2         | 1.12%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s  | 2         | 1.12%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s   | 2         | 1.12%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s   | 2         | 1.12%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s   | 2         | 1.12%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s   | 2         | 1.12%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s  | 2         | 1.12%   |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s     | 2         | 1.12%   |
| Micron RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 800MT/s   | 2         | 1.12%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s    | 2         | 1.12%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s    | 2         | 1.12%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s  | 2         | 1.12%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s   | 2         | 1.12%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s   | 2         | 1.12%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s | 2         | 1.12%   |
| Unknown                                                 | 2         | 1.12%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s             | 1         | 0.56%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s          | 1         | 0.56%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s          | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM SDRAM                     | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s             | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2                      | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s               | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 49        | 38.89%  |
| DDR4   | 47        | 37.3%   |
| DDR2   | 17        | 13.49%  |
| SDRAM  | 6         | 4.76%   |
| LPDDR4 | 4         | 3.17%   |
| DDR    | 2         | 1.59%   |
| DDR5   | 1         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 117       | 94.35%  |
| Row Of Chips | 5         | 4.03%   |
| DIMM         | 1         | 0.81%   |
| Unknown      | 1         | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 46        | 31.51%  |
| 2048  | 43        | 29.45%  |
| 4096  | 36        | 24.66%  |
| 16384 | 10        | 6.85%   |
| 1024  | 10        | 6.85%   |
| 32768 | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 35        | 24.31%  |
| 3200    | 27        | 18.75%  |
| 2667    | 19        | 13.19%  |
| 2400    | 10        | 6.94%   |
| 667     | 10        | 6.94%   |
| 1333    | 8         | 5.56%   |
| 533     | 6         | 4.17%   |
| 1334    | 5         | 3.47%   |
| 2666    | 3         | 2.08%   |
| 2048    | 3         | 2.08%   |
| 800     | 3         | 2.08%   |
| Unknown | 3         | 2.08%   |
| 4199    | 2         | 1.39%   |
| 3266    | 2         | 1.39%   |
| 1067    | 2         | 1.39%   |
| 975     | 2         | 1.39%   |
| 4800    | 1         | 0.69%   |
| 2133    | 1         | 0.69%   |
| 1867    | 1         | 0.69%   |
| 1066    | 1         | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 66.67%  |
| Samsung Electronics | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung ML-1865        | 1         | 33.33%  |
| HP LaserJet 1018       | 1         | 33.33%  |
| HP DeskJet 2300 series | 1         | 33.33%  |

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
| Chicony Electronics                    | 26        | 17.45%  |
| Microdia                               | 20        | 13.42%  |
| Bison Electronics                      | 15        | 10.07%  |
| Realtek Semiconductor                  | 13        | 8.72%   |
| IMC Networks                           | 13        | 8.72%   |
| Suyin                                  | 9         | 6.04%   |
| Sunplus Innovation Technology          | 7         | 4.7%    |
| Quanta                                 | 7         | 4.7%    |
| Syntek                                 | 5         | 3.36%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.36%   |
| Sonix Technology                       | 4         | 2.68%   |
| Acer                                   | 4         | 2.68%   |
| Ricoh                                  | 3         | 2.01%   |
| Luxvisions Innotech Limited            | 3         | 2.01%   |
| ALi                                    | 3         | 2.01%   |
| Lite-On Technology                     | 2         | 1.34%   |
| Importek                               | 2         | 1.34%   |
| Tobii Technology AB                    | 1         | 0.67%   |
| Silicon Motion                         | 1         | 0.67%   |
| OmniVision Technologies                | 1         | 0.67%   |
| Logitech                               | 1         | 0.67%   |
| Lenovo                                 | 1         | 0.67%   |
| icSpring                               | 1         | 0.67%   |
| Apple                                  | 1         | 0.67%   |
| Alcor Micro                            | 1         | 0.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                        | 7         | 4.7%    |
| Realtek Integrated_Webcam_HD                                  | 6         | 4.03%   |
| Microdia USB 2.0 Camera                                       | 6         | 4.03%   |
| Sunplus Integrated_Webcam_HD                                  | 4         | 2.68%   |
| Sonix USB2.0 HD UVC WebCam                                    | 4         | 2.68%   |
| Microdia Integrated_Webcam_HD                                 | 4         | 2.68%   |
| Chicony Lenovo EasyCamera                                     | 4         | 2.68%   |
| Chicony Integrated Camera                                     | 4         | 2.68%   |
| Bison USB HD Webcam                                           | 4         | 2.68%   |
| IMC Networks XHC Camera                                       | 3         | 2.01%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 3         | 2.01%   |
| IMC Networks Integrated Camera                                | 3         | 2.01%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 3         | 2.01%   |
| Bison USB Camera                                              | 3         | 2.01%   |
| Bison HD Webcam                                               | 3         | 2.01%   |
| Suyin Integrated_Webcam_HD                                    | 2         | 1.34%   |
| Suyin HP Webcam 101                                           | 2         | 1.34%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 2         | 1.34%   |
| Realtek USB Camera                                            | 2         | 1.34%   |
| Realtek Integrated Webcam HD                                  | 2         | 1.34%   |
| Quanta ACER HD User Facing                                    | 2         | 1.34%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 1.34%   |
| IMC Networks Lenovo EasyCamera                                | 2         | 1.34%   |
| Chicony HD WebCam                                             | 2         | 1.34%   |
| Bison BisonCam, NB Pro                                        | 2         | 1.34%   |
| ALi WebCam                                                    | 2         | 1.34%   |
| Tobii AB EyeChip                                              | 1         | 0.67%   |
| Syntek USB Camera Device                                      | 1         | 0.67%   |
| Syntek USB 2.0 UVC PC Camera                                  | 1         | 0.67%   |
| Syntek Integrated Webcam                                      | 1         | 0.67%   |
| Syntek Integrated Camera                                      | 1         | 0.67%   |
| Syntek EasyCamera                                             | 1         | 0.67%   |
| Suyin USB2.0 UVC 1.3M WebCam                                  | 1         | 0.67%   |
| Suyin Integrated Webcam                                       | 1         | 0.67%   |
| Suyin HP Truevision HD                                        | 1         | 0.67%   |
| Suyin HD Video WebCam                                         | 1         | 0.67%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 0.67%   |
| Sunplus Lenovo EasyCamera                                     | 1         | 0.67%   |
| Sunplus Integrated Camera                                     | 1         | 0.67%   |
| Sunplus HesTongCamera                                         | 1         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 44.44%  |
| AuthenTec                  | 3         | 16.67%  |
| Synaptics                  | 2         | 11.11%  |
| Shenzhen Goodix Technology | 2         | 11.11%  |
| Upek                       | 1         | 5.56%   |
| Futronic Technology        | 1         | 5.56%   |
| Elan Microelectronics      | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 11.11%  |
| Validity Sensors Fingerprint scanner                   | 2         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 11.11%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 11.11%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.56%   |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5.56%   |
| Futronic Fingerprint Scanner Model FS88                | 1         | 5.56%   |
| Elan ELAN:ARM-M4                                       | 1         | 5.56%   |
| AuthenTec AES1600                                      | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 75%     |
| Alcor Micro | 2         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 37.5%   |
| Broadcom 5880                                  | 3         | 37.5%   |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 140       | 72.54%  |
| 1     | 43        | 22.28%  |
| 2     | 8         | 4.15%   |
| 5     | 1         | 0.52%   |
| 4     | 1         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 19        | 28.79%  |
| Fingerprint reader       | 18        | 27.27%  |
| Net/wireless             | 8         | 12.12%  |
| Chipcard                 | 8         | 12.12%  |
| Sound                    | 5         | 7.58%   |
| Camera                   | 4         | 6.06%   |
| Storage                  | 1         | 1.52%   |
| Multimedia controller    | 1         | 1.52%   |
| Communication controller | 1         | 1.52%   |
| Bluetooth                | 1         | 1.52%   |

