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

Total: 271

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Debian 11          | 16        | 8.21%   |
| Ubuntu 22.04       | 14        | 7.18%   |
| Ubuntu 20.04       | 11        | 5.64%   |
| OpenMandriva 4.3   | 8         | 4.1%    |
| Debian 10          | 6         | 3.08%   |
| Zorin 16           | 5         | 2.56%   |
| Ubuntu 18.04       | 5         | 2.56%   |
| KDE neon 22.04     | 5         | 2.56%   |
| KDE neon 20.04     | 5         | 2.56%   |
| Debian 12          | 5         | 2.56%   |
| OpenMandriva 4.2   | 4         | 2.05%   |
| Linux Mint 21.1    | 4         | 2.05%   |
| Kubuntu 20.04      | 4         | 2.05%   |
| Xubuntu 18.04      | 3         | 1.54%   |
| ROSA R9            | 3         | 1.54%   |
| OpenMandriva 23.03 | 3         | 1.54%   |
| Linux Mint 20.3    | 3         | 1.54%   |
| Zorin 15           | 2         | 1.03%   |
| Xubuntu 22.04      | 2         | 1.03%   |
| Ubuntu Unity 16.04 | 2         | 1.03%   |
| Ubuntu 23.10       | 2         | 1.03%   |
| Ubuntu 21.10       | 2         | 1.03%   |
| Ubuntu 19.10       | 2         | 1.03%   |
| Pop!_OS 22.04      | 2         | 1.03%   |
| Pop!_OS 21.04      | 2         | 1.03%   |
| OpenMandriva 23.08 | 2         | 1.03%   |
| OpenMandriva 23.01 | 2         | 1.03%   |
| Manjaro            | 2         | 1.03%   |
| Linux Mint 21.2    | 2         | 1.03%   |
| Linux Mint 20      | 2         | 1.03%   |
| Fedora 39          | 2         | 1.03%   |
| Fedora 37          | 2         | 1.03%   |
| Fedora 36          | 2         | 1.03%   |
| Fedora 35          | 2         | 1.03%   |
| ArcoLinux Rolling  | 2         | 1.03%   |
| Arch Rolling       | 2         | 1.03%   |
| Xubuntu 23.10      | 1         | 0.51%   |
| Xubuntu 21.10      | 1         | 0.51%   |
| Xubuntu 20.04      | 1         | 0.51%   |
| Xero Rolling       | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 36        | 19.25%  |
| Debian       | 25        | 13.37%  |
| OpenMandriva | 21        | 11.23%  |
| Linux Mint   | 13        | 6.95%   |
| KDE neon     | 11        | 5.88%   |
| Fedora       | 9         | 4.81%   |
| Xubuntu      | 8         | 4.28%   |
| Zorin        | 7         | 3.74%   |
| Manjaro      | 6         | 3.21%   |
| Kubuntu      | 6         | 3.21%   |
| ROSA         | 5         | 2.67%   |
| Pop!_OS      | 4         | 2.14%   |
| Ubuntu MATE  | 3         | 1.6%    |
| MX           | 3         | 1.6%    |
| Kali         | 3         | 1.6%    |
| Arch         | 3         | 1.6%    |
| Ubuntu Unity | 2         | 1.07%   |
| openSUSE     | 2         | 1.07%   |
| Nobara       | 2         | 1.07%   |
| Lubuntu      | 2         | 1.07%   |
| LMDE         | 2         | 1.07%   |
| ArcoLinux    | 2         | 1.07%   |
| Xero         | 1         | 0.53%   |
| Solus        | 1         | 0.53%   |
| Q4OS         | 1         | 0.53%   |
| Linux Lite   | 1         | 0.53%   |
| Garuda Linux | 1         | 0.53%   |
| Feren OS     | 1         | 0.53%   |
| EndeavourOS  | 1         | 0.53%   |
| Elementary   | 1         | 0.53%   |
| Deepin       | 1         | 0.53%   |
| BunsenLabs   | 1         | 0.53%   |
| Alpine       | 1         | 0.53%   |
| AlmaLinux    | 1         | 0.53%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 8         | 3.65%   |
| 5.4.0-42-generic                | 4         | 1.83%   |
| 5.15.0-56-generic               | 4         | 1.83%   |
| 5.15.0-46-generic               | 4         | 1.83%   |
| 5.10.14-desktop-1omv4002        | 4         | 1.83%   |
| 5.10.0-23-amd64                 | 4         | 1.83%   |
| 6.2.6-desktop-1omv2390          | 3         | 1.37%   |
| 5.4.0-73-generic                | 3         | 1.37%   |
| 5.4.0-52-generic                | 3         | 1.37%   |
| 5.3.0-40-generic                | 3         | 1.37%   |
| 5.13.0-39-generic               | 3         | 1.37%   |
| 5.10.0-13-amd64                 | 3         | 1.37%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 3         | 1.37%   |
| 4.19.0-17-amd64                 | 3         | 1.37%   |
| 6.4.11-arch2-1                  | 2         | 0.91%   |
| 6.2.0-26-generic                | 2         | 0.91%   |
| 6.1.1-desktop-1omv2290          | 2         | 0.91%   |
| 6.1.0-17-amd64                  | 2         | 0.91%   |
| 5.4.0-89-generic                | 2         | 0.91%   |
| 5.4.0-77-generic                | 2         | 0.91%   |
| 5.4.0-48-generic                | 2         | 0.91%   |
| 5.4.0-107-generic               | 2         | 0.91%   |
| 5.19.0-41-generic               | 2         | 0.91%   |
| 5.19.0-40-generic               | 2         | 0.91%   |
| 5.19.0-2-amd64                  | 2         | 0.91%   |
| 5.15.0-91-generic               | 2         | 0.91%   |
| 5.15.0-76-generic               | 2         | 0.91%   |
| 5.15.0-67-generic               | 2         | 0.91%   |
| 5.15.0-60-generic               | 2         | 0.91%   |
| 5.15.0-48-generic               | 2         | 0.91%   |
| 5.15.0-43-generic               | 2         | 0.91%   |
| 5.11.0-37-generic               | 2         | 0.91%   |
| 5.10.0-21-amd64                 | 2         | 0.91%   |
| 5.10.0-18-amd64                 | 2         | 0.91%   |
| 5.10.0-11-amd64                 | 2         | 0.91%   |
| 5.10.0-10-amd64                 | 2         | 0.91%   |
| 5.0.0-37-generic                | 2         | 0.91%   |
| 6.6.7-200.fc39.x86_64           | 1         | 0.46%   |
| 6.6.2-201.fsync.fc38.x86_64     | 1         | 0.46%   |
| 6.5.6-300.fc39.x86_64           | 1         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 27        | 13.3%   |
| 5.4.0   | 20        | 9.85%   |
| 5.10.0  | 17        | 8.37%   |
| 6.2.0   | 10        | 4.93%   |
| 5.13.0  | 10        | 4.93%   |
| 5.16.7  | 8         | 3.94%   |
| 4.19.0  | 8         | 3.94%   |
| 5.19.0  | 7         | 3.45%   |
| 5.11.0  | 6         | 2.96%   |
| 6.1.0   | 5         | 2.46%   |
| 5.3.0   | 5         | 2.46%   |
| 5.8.0   | 4         | 1.97%   |
| 5.10.14 | 4         | 1.97%   |
| 4.15.0  | 4         | 1.97%   |
| 6.5.0   | 3         | 1.48%   |
| 6.4.11  | 3         | 1.48%   |
| 6.2.6   | 3         | 1.48%   |
| 4.9.20  | 3         | 1.48%   |
| 6.4.2   | 2         | 0.99%   |
| 6.1.1   | 2         | 0.99%   |
| 5.18.0  | 2         | 0.99%   |
| 5.15.2  | 2         | 0.99%   |
| 5.14.10 | 2         | 0.99%   |
| 5.0.0   | 2         | 0.99%   |
| 6.6.7   | 1         | 0.49%   |
| 6.6.2   | 1         | 0.49%   |
| 6.5.6   | 1         | 0.49%   |
| 6.5.1   | 1         | 0.49%   |
| 6.4.8   | 1         | 0.49%   |
| 6.4.12  | 1         | 0.49%   |
| 6.3.6   | 1         | 0.49%   |
| 6.3.5   | 1         | 0.49%   |
| 6.3.0   | 1         | 0.49%   |
| 6.2.12  | 1         | 0.49%   |
| 6.1.8   | 1         | 0.49%   |
| 6.1.55  | 1         | 0.49%   |
| 6.1.14  | 1         | 0.49%   |
| 6.1.10  | 1         | 0.49%   |
| 6.0.8   | 1         | 0.49%   |
| 6.0.2   | 1         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 35        | 17.41%  |
| 5.10    | 24        | 11.94%  |
| 5.4     | 22        | 10.95%  |
| 6.2     | 14        | 6.97%   |
| 6.1     | 11        | 5.47%   |
| 5.13    | 11        | 5.47%   |
| 5.16    | 8         | 3.98%   |
| 4.19    | 8         | 3.98%   |
| 6.4     | 7         | 3.48%   |
| 5.19    | 7         | 3.48%   |
| 5.11    | 6         | 2.99%   |
| 6.5     | 5         | 2.49%   |
| 5.8     | 5         | 2.49%   |
| 5.3     | 5         | 2.49%   |
| 5.17    | 4         | 1.99%   |
| 4.9     | 4         | 1.99%   |
| 4.15    | 4         | 1.99%   |
| 6.3     | 3         | 1.49%   |
| 5.14    | 3         | 1.49%   |
| 6.6     | 2         | 1%      |
| 6.0     | 2         | 1%      |
| 5.6     | 2         | 1%      |
| 5.18    | 2         | 1%      |
| 5.12    | 2         | 1%      |
| 5.0     | 2         | 1%      |
| 5.9     | 1         | 0.5%    |
| 5.5     | 1         | 0.5%    |
| 4.18    | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 167       | 92.78%  |
| i686   | 13        | 7.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 63        | 32.98%  |
| KDE5          | 46        | 24.08%  |
| XFCE          | 29        | 15.18%  |
| X-Cinnamon    | 12        | 6.28%   |
| Unknown       | 10        | 5.24%   |
| KDE           | 6         | 3.14%   |
| MATE          | 5         | 2.62%   |
| LXQt          | 5         | 2.62%   |
| KDE4          | 4         | 2.09%   |
| Unity         | 2         | 1.05%   |
| Cinnamon      | 2         | 1.05%   |
| Budgie        | 2         | 1.05%   |
| Pantheon      | 1         | 0.52%   |
| Openbox       | 1         | 0.52%   |
| GNOME Classic | 1         | 0.52%   |
| Deepin        | 1         | 0.52%   |
| awesome       | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 150       | 81.97%  |
| Wayland | 30        | 16.39%  |
| Tty     | 2         | 1.09%   |
| Unknown | 1         | 0.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 61        | 32.28%  |
| SDDM    | 38        | 20.11%  |
| LightDM | 33        | 17.46%  |
| GDM3    | 26        | 13.76%  |
| GDM     | 24        | 12.7%   |
| KDM     | 4         | 2.12%   |
| TDM     | 3         | 1.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_VE   | 101       | 54.01%  |
| en_US   | 54        | 28.88%  |
| es_ES   | 15        | 8.02%   |
| Unknown | 8         | 4.28%   |
| es_MX   | 5         | 2.67%   |
| es_US   | 2         | 1.07%   |
| en_CA   | 1         | 0.53%   |
| C       | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 114       | 61.62%  |
| EFI  | 71        | 38.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 139       | 75.14%  |
| Overlay | 19        | 10.27%  |
| Btrfs   | 14        | 7.57%   |
| Tmpfs   | 7         | 3.78%   |
| Xfs     | 3         | 1.62%   |
| Unknown | 3         | 1.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 75        | 40.11%  |
| Unknown | 69        | 36.9%   |
| MBR     | 43        | 22.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 155       | 82.89%  |
| Yes       | 32        | 17.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 114       | 62.98%  |
| Yes       | 67        | 37.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo                                   | 31        | 17.22%  |
| Dell                                     | 29        | 16.11%  |
| VIT                                      | 27        | 15%     |
| Hewlett-Packard                          | 24        | 13.33%  |
| ASUSTek Computer                         | 13        | 7.22%   |
| Acer                                     | 11        | 6.11%   |
| Intel                                    | 9         | 5%      |
| Google                                   | 5         | 2.78%   |
| Unknown                                  | 5         | 2.78%   |
| Shanghai Zhaoxin Semiconductor           | 3         | 1.67%   |
| Pegatron                                 | 3         | 1.67%   |
| Toshiba                                  | 2         | 1.11%   |
| Siragon                                  | 2         | 1.11%   |
| Samsung Electronics                      | 2         | 1.11%   |
| Notebook                                 | 2         | 1.11%   |
| MSI                                      | 2         | 1.11%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. | 1         | 0.56%   |
| UNIQCELL                                 | 1         | 0.56%   |
| Sony                                     | 1         | 0.56%   |
| Panasonic                                | 1         | 0.56%   |
| GPU Company                              | 1         | 0.56%   |
| Gateway                                  | 1         | 0.56%   |
| Exo                                      | 1         | 0.56%   |
| Clevo                                    | 1         | 0.56%   |
| AVITA                                    | 1         | 0.56%   |
| Alienware                                | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel powered classmate PC                            | 9         | 5%      |
| VIT P2400                                             | 8         | 4.44%   |
| VIT P3400                                             | 5         | 2.78%   |
| VIT P2402                                             | 5         | 2.78%   |
| Unknown                                               | 5         | 2.78%   |
| VIT P1400                                             | 3         | 1.67%   |
| VIT M2420                                             | 3         | 1.67%   |
| Shanghai Zhaoxin ZXE CRB                              | 3         | 1.67%   |
| HP Pavilion dv5                                       | 3         | 1.67%   |
| Google Candy                                          | 3         | 1.67%   |
| VIT M2421                                             | 2         | 1.11%   |
| Lenovo IdeaPad S100c 20194                            | 2         | 1.11%   |
| Lenovo 3000 N200 0769ARS                              | 2         | 1.11%   |
| HP Compaq Presario C700                               | 2         | 1.11%   |
| Dell Inspiron 1545                                    | 2         | 1.11%   |
| ASUS VivoBook_ASUSLaptop K3605VC_K3605VC              | 2         | 1.11%   |
| ASUS ASUS TUF Gaming F17 FX706HM_TUF706HM             | 2         | 1.11%   |
| Acer Aspire 4739Z                                     | 2         | 1.11%   |
| VIT P2423                                             | 1         | 0.56%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. VIT P2460-02 | 1         | 0.56%   |
| UNIQCELL Q15.6                                        | 1         | 0.56%   |
| Toshiba Satellite E55t-A                              | 1         | 0.56%   |
| Toshiba ENCORE 2 WT8-B                                | 1         | 0.56%   |
| Sony VGN-FW510F                                       | 1         | 0.56%   |
| Siragon MN-50                                         | 1         | 0.56%   |
| SIRAGON LM-C100                                       | 1         | 0.56%   |
| Samsung 905S3G/906S3G/915S3G                          | 1         | 0.56%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.56%   |
| Pegatron T14AF                                        | 1         | 0.56%   |
| Pegatron H36Y                                         | 1         | 0.56%   |
| Pegatron B74                                          | 1         | 0.56%   |
| Panasonic CF-31RECAXDR                                | 1         | 0.56%   |
| Notebook W54BL                                        | 1         | 0.56%   |
| Notebook NL40_50CU                                    | 1         | 0.56%   |
| MSI MS-1454                                           | 1         | 0.56%   |
| MSI GL73 9SD                                          | 1         | 0.56%   |
| Lenovo Z50-75 80EC                                    | 1         | 0.56%   |
| Lenovo ThinkPad X201 3680AE2                          | 1         | 0.56%   |
| Lenovo ThinkPad T490 20N2000LSP                       | 1         | 0.56%   |
| Lenovo ThinkPad T14 Gen 1 20S1S2FB00                  | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Dell Inspiron                                | 15        | 8.33%   |
| Lenovo IdeaPad                               | 13        | 7.22%   |
| HP Pavilion                                  | 10        | 5.56%   |
| Acer Aspire                                  | 10        | 5.56%   |
| Intel powered                                | 9         | 5%      |
| VIT P2400                                    | 8         | 4.44%   |
| Lenovo ThinkPad                              | 7         | 3.89%   |
| Dell Latitude                                | 7         | 3.89%   |
| VIT P3400                                    | 5         | 2.78%   |
| VIT P2402                                    | 5         | 2.78%   |
| ASUS ASUS                                    | 5         | 2.78%   |
| Unknown                                      | 5         | 2.78%   |
| Lenovo 3000                                  | 4         | 2.22%   |
| HP Laptop                                    | 4         | 2.22%   |
| Dell Vostro                                  | 4         | 2.22%   |
| ASUS VivoBook                                | 4         | 2.22%   |
| VIT P1400                                    | 3         | 1.67%   |
| VIT M2420                                    | 3         | 1.67%   |
| Shanghai Zhaoxin ZXE                         | 3         | 1.67%   |
| HP Compaq                                    | 3         | 1.67%   |
| Google Candy                                 | 3         | 1.67%   |
| VIT M2421                                    | 2         | 1.11%   |
| Lenovo Legion                                | 2         | 1.11%   |
| HP Presario                                  | 2         | 1.11%   |
| HP EliteBook                                 | 2         | 1.11%   |
| VIT P2423                                    | 1         | 0.56%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. VIT | 1         | 0.56%   |
| UNIQCELL Q15.6                               | 1         | 0.56%   |
| Toshiba Satellite                            | 1         | 0.56%   |
| Toshiba ENCORE                               | 1         | 0.56%   |
| Sony VGN-FW510F                              | 1         | 0.56%   |
| Siragon MN-50                                | 1         | 0.56%   |
| SIRAGON LM-C100                              | 1         | 0.56%   |
| Samsung 905S3G                               | 1         | 0.56%   |
| Samsung 355V4C                               | 1         | 0.56%   |
| Pegatron T14AF                               | 1         | 0.56%   |
| Pegatron H36Y                                | 1         | 0.56%   |
| Pegatron B74                                 | 1         | 0.56%   |
| Panasonic CF-31RECAXDR                       | 1         | 0.56%   |
| Notebook W54BL                               | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 21        | 11.67%  |
| 2012    | 20        | 11.11%  |
| 2011    | 20        | 11.11%  |
| 2022    | 13        | 7.22%   |
| 2020    | 11        | 6.11%   |
| 2008    | 11        | 6.11%   |
| 2019    | 10        | 5.56%   |
| 2007    | 10        | 5.56%   |
| 2018    | 9         | 5%      |
| 2014    | 9         | 5%      |
| 2010    | 9         | 5%      |
| 2021    | 8         | 4.44%   |
| 2023    | 7         | 3.89%   |
| 2009    | 6         | 3.33%   |
| 2015    | 5         | 2.78%   |
| 2017    | 4         | 2.22%   |
| Unknown | 3         | 1.67%   |
| 2016    | 2         | 1.11%   |
| 2006    | 2         | 1.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 180       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 173       | 96.11%  |
| Enabled  | 7         | 3.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 175       | 97.22%  |
| Yes  | 5         | 2.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 50        | 27.32%  |
| 4.01-8.0   | 42        | 22.95%  |
| 1.01-2.0   | 31        | 16.94%  |
| 8.01-16.0  | 30        | 16.39%  |
| 16.01-24.0 | 13        | 7.1%    |
| 2.01-3.0   | 9         | 4.92%   |
| 32.01-64.0 | 5         | 2.73%   |
| 24.01-32.0 | 2         | 1.09%   |
| 0.51-1.0   | 1         | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 69        | 33.66%  |
| 2.01-3.0   | 54        | 26.34%  |
| 4.01-8.0   | 27        | 13.17%  |
| 0.51-1.0   | 25        | 12.2%   |
| 3.01-4.0   | 21        | 10.24%  |
| 8.01-16.0  | 6         | 2.93%   |
| 0.01-0.5   | 2         | 0.98%   |
| 16.01-24.0 | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 122       | 65.95%  |
| 2      | 56        | 30.27%  |
| 3      | 6         | 3.24%   |
| 0      | 1         | 0.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 96        | 53.33%  |
| Yes       | 84        | 46.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 82.97%  |
| No        | 31        | 17.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 97.22%  |
| No        | 5         | 2.78%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 60.99%  |
| No        | 71        | 39.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Venezuela | 180       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 77        | 39.49%  |
| Maracaibo                  | 20        | 10.26%  |
| Maracay                    | 10        | 5.13%   |
| Barquisimeto               | 7         | 3.59%   |
| Valencia                   | 6         | 3.08%   |
| Mérida                    | 6         | 3.08%   |
| Barcelona                  | 5         | 2.56%   |
| Ciudad Guayana             | 4         | 2.05%   |
| San Cristóbal             | 3         | 1.54%   |
| San Carlos del Zulia       | 3         | 1.54%   |
| Maturín                   | 3         | 1.54%   |
| Lecherias                  | 3         | 1.54%   |
| San Juan de los Morros     | 2         | 1.03%   |
| Punto Fijo                 | 2         | 1.03%   |
| Puerto Ordaz and San Felix | 2         | 1.03%   |
| Porlamar                   | 2         | 1.03%   |
| La Guaira                  | 2         | 1.03%   |
| Guatire                    | 2         | 1.03%   |
| Cagua                      | 2         | 1.03%   |
| Anaco                      | 2         | 1.03%   |
| Acarigua                   | 2         | 1.03%   |
| Villa de Cura              | 1         | 0.51%   |
| Vigia                      | 1         | 0.51%   |
| Tucape                     | 1         | 0.51%   |
| San Juan Bautista          | 1         | 0.51%   |
| San Felipe                 | 1         | 0.51%   |
| San Diego                  | 1         | 0.51%   |
| San Antonio de Los Altos   | 1         | 0.51%   |
| Puerto Cumarebo            | 1         | 0.51%   |
| Puerto Cruz                | 1         | 0.51%   |
| Petare                     | 1         | 0.51%   |
| Parroquia El Recreo        | 1         | 0.51%   |
| Naguanagua                 | 1         | 0.51%   |
| Mariara                    | 1         | 0.51%   |
| Maiquetia                  | 1         | 0.51%   |
| Los Palos Grandes          | 1         | 0.51%   |
| Las Vegas                  | 1         | 0.51%   |
| Las Tienditas              | 1         | 0.51%   |
| Las Mercedes               | 1         | 0.51%   |
| Guarenas                   | 1         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 36        | 39     | 16.67%  |
| WDC                       | 32        | 44     | 14.81%  |
| Toshiba                   | 22        | 23     | 10.19%  |
| Unknown                   | 15        | 20     | 6.94%   |
| Samsung Electronics       | 14        | 14     | 6.48%   |
| Intel                     | 10        | 14     | 4.63%   |
| Hitachi                   | 9         | 10     | 4.17%   |
| SanDisk                   | 8         | 13     | 3.7%    |
| Micron Technology         | 7         | 10     | 3.24%   |
| LITEONIT                  | 6         | 10     | 2.78%   |
| Crucial                   | 6         | 9      | 2.78%   |
| HGST                      | 5         | 5      | 2.31%   |
| SK hynix                  | 4         | 6      | 1.85%   |
| PNY                       | 4         | 4      | 1.85%   |
| Kingston                  | 4         | 6      | 1.85%   |
| SPCC                      | 3         | 6      | 1.39%   |
| addlink                   | 3         | 3      | 1.39%   |
| Team                      | 2         | 2      | 0.93%   |
| Silicon Motion            | 2         | 3      | 0.93%   |
| Patriot                   | 2         | 2      | 0.93%   |
| HUAWEI                    | 2         | 2      | 0.93%   |
| Fujitsu                   | 2         | 2      | 0.93%   |
| China                     | 2         | 2      | 0.93%   |
| BIWIN                     | 2         | 3      | 0.93%   |
| A-DATA Technology         | 2         | 2      | 0.93%   |
| Vaseky                    | 1         | 1      | 0.46%   |
| UMIS                      | 1         | 1      | 0.46%   |
| PUSKILL                   | 1         | 1      | 0.46%   |
| Phison                    | 1         | 1      | 0.46%   |
| Micron/Crucial Technology | 1         | 1      | 0.46%   |
| Lexar                     | 1         | 1      | 0.46%   |
| KingFast                  | 1         | 3      | 0.46%   |
| Intenso                   | 1         | 1      | 0.46%   |
| Emtec                     | 1         | 1      | 0.46%   |
| Dell                      | 1         | 2      | 0.46%   |
| Apacer                    | 1         | 1      | 0.46%   |
| Unknown                   | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| LITEONIT LMS-32L6M 32GB SSD         | 5         | 2.25%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 4         | 1.8%    |
| Seagate ST500LT012-9WS142 500GB     | 4         | 1.8%    |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 1.35%   |
| Unknown NVMe SSD Drive 512GB        | 3         | 1.35%   |
| Toshiba MQ04ABF100 1TB              | 3         | 1.35%   |
| Seagate ST320LT012-9WS14C 320GB     | 3         | 1.35%   |
| Seagate ST320LT012-1DG14C 320GB     | 3         | 1.35%   |
| Seagate ST250LM004 HN-M250MBB 250GB | 3         | 1.35%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.9%    |
| WDC WD5000LPVT-08G33T1 500GB        | 2         | 0.9%    |
| WDC WD3200BEVT-00A0RT0 320GB        | 2         | 0.9%    |
| WDC WD1600BEVT-22ZCT0 160GB         | 2         | 0.9%    |
| WDC WD1200BEVS-60UST0 120GB         | 2         | 0.9%    |
| Unknown MMC Card  64GB              | 2         | 0.9%    |
| Unknown MMC Card  16GB              | 2         | 0.9%    |
| Unknown HAG2e  16GB                 | 2         | 0.9%    |
| Toshiba MQ01ABF050 500GB            | 2         | 0.9%    |
| Toshiba MQ01ABF032 320GB            | 2         | 0.9%    |
| Toshiba MQ01ABD050 500GB            | 2         | 0.9%    |
| Toshiba MK3276GSX 320GB             | 2         | 0.9%    |
| Toshiba MK3275GSX 320GB             | 2         | 0.9%    |
| SK hynix HFM001TD3JX013N 1024GB     | 2         | 0.9%    |
| Seagate ST9500325AS 500GB           | 2         | 0.9%    |
| Seagate ST9320325AS 320GB           | 2         | 0.9%    |
| Seagate ST500LT012-1DG142 500GB     | 2         | 0.9%    |
| Seagate ST500LM021-1KJ152 500GB     | 2         | 0.9%    |
| Seagate ST320LM001 HN-M320MBB 320GB | 2         | 0.9%    |
| Seagate ST320LM000 HM321HI 320GB    | 2         | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.9%    |
| SanDisk NVMe SSD Drive 1TB          | 2         | 0.9%    |
| Samsung MZALQ512HBLU-00BL2 512GB    | 2         | 0.9%    |
| Samsung HN-M320MBB 320GB            | 2         | 0.9%    |
| Samsung HM250HI 250GB               | 2         | 0.9%    |
| PNY CS900 480GB SSD                 | 2         | 0.9%    |
| PNY CS900 1TB SSD                   | 2         | 0.9%    |
| Micron 2450_MTFDKBA512TFK 512GB     | 2         | 0.9%    |
| Micron 2450_MTFDKBA1T0TFK 1TB       | 2         | 0.9%    |
| Intel SSDPEKNU512GZ 512GB           | 2         | 0.9%    |
| HUAWEI SD Storage 33GB              | 2         | 0.9%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 35     | 31.13%  |
| WDC                 | 30        | 39     | 28.3%   |
| Toshiba             | 21        | 22     | 19.81%  |
| Hitachi             | 9         | 10     | 8.49%   |
| HGST                | 5         | 5      | 4.72%   |
| Samsung Electronics | 4         | 4      | 3.77%   |
| Unknown             | 2         | 2      | 1.89%   |
| Fujitsu             | 2         | 2      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| LITEONIT            | 6         | 10     | 12.77%  |
| Crucial             | 6         | 9      | 12.77%  |
| Samsung Electronics | 5         | 5      | 10.64%  |
| PNY                 | 4         | 4      | 8.51%   |
| Kingston            | 3         | 5      | 6.38%   |
| SPCC                | 2         | 4      | 4.26%   |
| SanDisk             | 2         | 3      | 4.26%   |
| Patriot             | 2         | 2      | 4.26%   |
| China               | 2         | 2      | 4.26%   |
| A-DATA Technology   | 2         | 2      | 4.26%   |
| Vaseky              | 1         | 1      | 2.13%   |
| Toshiba             | 1         | 1      | 2.13%   |
| Team                | 1         | 1      | 2.13%   |
| PUSKILL             | 1         | 1      | 2.13%   |
| Micron Technology   | 1         | 3      | 2.13%   |
| Lexar               | 1         | 1      | 2.13%   |
| KingFast            | 1         | 3      | 2.13%   |
| Intenso             | 1         | 1      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| Emtec               | 1         | 1      | 2.13%   |
| Dell                | 1         | 2      | 2.13%   |
| BIWIN               | 1         | 2      | 2.13%   |
| addlink             | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 104       | 119    | 50.24%  |
| SSD     | 45        | 65     | 21.74%  |
| NVMe    | 42        | 64     | 20.29%  |
| MMC     | 11        | 15     | 5.31%   |
| Unknown | 5         | 6      | 2.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 135       | 181    | 68.88%  |
| NVMe | 42        | 64     | 21.43%  |
| MMC  | 11        | 15     | 5.61%   |
| SAS  | 8         | 9      | 4.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 120       | 150    | 82.19%  |
| 0.51-1.0   | 25        | 33     | 17.12%  |
| 1.01-2.0   | 1         | 1      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 61        | 32.11%  |
| 101-250        | 48        | 25.26%  |
| 501-1000       | 28        | 14.74%  |
| 1-20           | 20        | 10.53%  |
| 21-50          | 11        | 5.79%   |
| 51-100         | 11        | 5.79%   |
| 1001-2000      | 5         | 2.63%   |
| More than 3000 | 2         | 1.05%   |
| 2001-3000      | 2         | 1.05%   |
| Unknown        | 2         | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 76        | 37.81%  |
| 21-50     | 36        | 17.91%  |
| 101-250   | 33        | 16.42%  |
| 51-100    | 29        | 14.43%  |
| 251-500   | 16        | 7.96%   |
| 501-1000  | 8         | 3.98%   |
| Unknown   | 2         | 1%      |
| 2001-3000 | 1         | 0.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD1200BEVS-60UST0 120GB          | 2         | 2      | 6.25%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 6.25%   |
| Samsung Electronics HM250HI 250GB    | 2         | 2      | 6.25%   |
| Hitachi HTS725050A9A364 500GB        | 2         | 2      | 6.25%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 1      | 3.13%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 3.13%   |
| WDC WD3200BEVT-00A0RT0 320GB         | 1         | 1      | 3.13%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2      | 3.13%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 3.13%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 3.13%   |
| Toshiba MK3276GSX 320GB              | 1         | 1      | 3.13%   |
| Toshiba MK3275GSX 320GB              | 1         | 1      | 3.13%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 3.13%   |
| Toshiba MK2565GSX 250GB              | 1         | 1      | 3.13%   |
| Toshiba MK1032GSX 100GB              | 1         | 1      | 3.13%   |
| Seagate ST9320325AS 320GB            | 1         | 1      | 3.13%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 3.13%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 3.13%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 3.13%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 3.13%   |
| Samsung Electronics HN-M320MBB 320GB | 1         | 1      | 3.13%   |
| Intel SSDPEKKW256G7 256GB            | 1         | 1      | 3.13%   |
| Intel SSDPEKKF512G7L 512GB           | 1         | 1      | 3.13%   |
| Hitachi HTS543232L9A300 320GB        | 1         | 1      | 3.13%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1      | 3.13%   |
| Hitachi HTS542525K9SA00 250GB        | 1         | 1      | 3.13%   |
| HGST HTS545050A7E380 500GB           | 1         | 1      | 3.13%   |
| HGST HTS541010A7E630 1TB             | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 7      | 21.88%  |
| Seagate             | 7         | 7      | 21.88%  |
| WDC                 | 6         | 7      | 18.75%  |
| Hitachi             | 5         | 5      | 15.63%  |
| Samsung Electronics | 3         | 3      | 9.38%   |
| Intel               | 2         | 2      | 6.25%   |
| HGST                | 2         | 2      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 7      | 23.33%  |
| Seagate             | 7         | 7      | 23.33%  |
| WDC                 | 6         | 7      | 20%     |
| Hitachi             | 5         | 5      | 16.67%  |
| Samsung Electronics | 3         | 3      | 10%     |
| HGST                | 2         | 2      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 31     | 93.75%  |
| NVMe | 2         | 2      | 6.25%   |

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
| Detected | 92        | 142    | 47.67%  |
| Works    | 69        | 94     | 35.75%  |
| Malfunc  | 32        | 33     | 16.58%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 144       | 71.64%  |
| AMD                         | 22        | 10.95%  |
| SanDisk                     | 7         | 3.48%   |
| Micron Technology           | 6         | 2.99%   |
| Samsung Electronics         | 5         | 2.49%   |
| SK hynix                    | 4         | 1.99%   |
| Silicon Motion              | 3         | 1.49%   |
| Phison Electronics          | 3         | 1.49%   |
| Jiangsu Huacun Elec.        | 3         | 1.49%   |
| Union Memory (Shenzhen)     | 1         | 0.5%    |
| Micron/Crucial Technology   | 1         | 0.5%    |
| MAXIO Technology (Hangzhou) | 1         | 0.5%    |
| Kingston Technology Company | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 26        | 11.5%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 7.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 6.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 5.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 4.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 9         | 3.98%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 3.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 3.54%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 7         | 3.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 2.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 2.65%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 5         | 2.21%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 1.77%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 4         | 1.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 1.77%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 1.33%   |
| Jiangsu Huacun Elec. MMY MMSP350 PCIe 3 NVMe SSD (DRAM-less)                   | 3         | 1.33%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 3         | 1.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.33%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.88%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2         | 0.88%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 0.88%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.88%   |
| Intel SSD 600P Series                                                          | 2         | 0.88%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.88%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 2         | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 0.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.88%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 0.88%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 0.88%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                | 1         | 0.44%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 127       | 58.53%  |
| NVMe | 42        | 19.35%  |
| RAID | 25        | 11.52%  |
| IDE  | 23        | 10.6%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 152       | 84.44%  |
| AMD          | 25        | 13.89%  |
| CentaurHauls | 3         | 1.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz                | 8         | 4.44%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 6         | 3.33%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 5         | 2.78%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 4         | 2.22%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 4         | 2.22%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 3         | 1.67%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 3         | 1.67%   |
| Intel Core i7-3537U CPU @ 2.00GHz              | 3         | 1.67%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 3         | 1.67%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 3         | 1.67%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 3         | 1.67%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 3         | 1.67%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 3         | 1.67%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 3         | 1.67%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 3         | 1.67%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 2         | 1.11%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 2         | 1.11%   |
| Intel Core i5-3337U CPU @ 1.80GHz              | 2         | 1.11%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 1.11%   |
| Intel Core i3-4000M CPU @ 2.40GHz              | 2         | 1.11%   |
| Intel Core i3-2350M CPU @ 2.30GHz              | 2         | 1.11%   |
| Intel Core i3 CPU M 330 @ 2.13GHz              | 2         | 1.11%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz           | 2         | 1.11%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz           | 2         | 1.11%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 2         | 1.11%   |
| Intel Celeron CPU N2805 @ 1.46GHz              | 2         | 1.11%   |
| Intel Atom CPU N570 @ 1.66GHz                  | 2         | 1.11%   |
| Intel 13th Gen Core i9-13900H                  | 2         | 1.11%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 2         | 1.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 2         | 1.11%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 1.11%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 2         | 1.11%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 2         | 1.11%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 2         | 1.11%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 0.56%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz         | 1         | 0.56%   |
| Intel Pentium CPU N3710 @ 1.60GHz              | 1         | 0.56%   |
| Intel Pentium CPU B940 @ 2.00GHz               | 1         | 0.56%   |
| Intel Pentium CPU 6405U @ 2.40GHz              | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 32        | 17.78%  |
| Intel Core i3                        | 27        | 15%     |
| Intel Celeron                        | 21        | 11.67%  |
| Other                                | 17        | 9.44%   |
| Intel Core i7                        | 16        | 8.89%   |
| Intel Core 2 Duo                     | 15        | 8.33%   |
| Intel Atom                           | 11        | 6.11%   |
| Intel Pentium                        | 7         | 3.89%   |
| AMD Ryzen 5                          | 7         | 3.89%   |
| AMD Ryzen 7                          | 5         | 2.78%   |
| Intel Pentium Dual                   | 4         | 2.22%   |
| Intel Pentium Dual-Core              | 2         | 1.11%   |
| Intel Genuine                        | 2         | 1.11%   |
| AMD A10                              | 2         | 1.11%   |
| Intel Pentium Silver                 | 1         | 0.56%   |
| Intel Core 2                         | 1         | 0.56%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.56%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.56%   |
| AMD Ryzen 3                          | 1         | 0.56%   |
| AMD Quad-Core                        | 1         | 0.56%   |
| AMD Phenom II                        | 1         | 0.56%   |
| AMD Mobile Sempron                   | 1         | 0.56%   |
| AMD E1                               | 1         | 0.56%   |
| AMD E                                | 1         | 0.56%   |
| AMD C-70                             | 1         | 0.56%   |
| AMD A6                               | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 120       | 66.67%  |
| 4       | 30        | 16.67%  |
| 1       | 9         | 5%      |
| 8       | 7         | 3.89%   |
| 6       | 7         | 3.89%   |
| 14      | 3         | 1.67%   |
| Unknown | 2         | 1.11%   |
| 24      | 1         | 0.56%   |
| 10      | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 180       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 112       | 62.22%  |
| 1       | 66        | 36.67%  |
| Unknown | 2         | 1.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 174       | 96.67%  |
| 64-bit         | 3         | 1.67%   |
| 32-bit         | 3         | 1.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 30.85%  |
| 0x306a9    | 17        | 9.04%   |
| 0x206a7    | 17        | 9.04%   |
| 0x1067a    | 11        | 5.85%   |
| 0x6fd      | 8         | 4.26%   |
| 0x30678    | 6         | 3.19%   |
| 0x106ca    | 6         | 3.19%   |
| 0x806e9    | 5         | 2.66%   |
| 0x806c1    | 4         | 2.13%   |
| 0x20655    | 4         | 2.13%   |
| 0x806ec    | 3         | 1.6%    |
| 0x406e3    | 3         | 1.6%    |
| 0x40651    | 3         | 1.6%    |
| 0x806ea    | 2         | 1.06%   |
| 0x806d1    | 2         | 1.06%   |
| 0x306d4    | 2         | 1.06%   |
| 0x306c3    | 2         | 1.06%   |
| 0x30673    | 2         | 1.06%   |
| 0x08608103 | 2         | 1.06%   |
| 0x08108102 | 2         | 1.06%   |
| 0x05000119 | 2         | 1.06%   |
| 0x02000057 | 2         | 1.06%   |
| 0x906ea    | 1         | 0.53%   |
| 0x906e9    | 1         | 0.53%   |
| 0x906a4    | 1         | 0.53%   |
| 0x806eb    | 1         | 0.53%   |
| 0x706e5    | 1         | 0.53%   |
| 0x706a8    | 1         | 0.53%   |
| 0x6f6      | 1         | 0.53%   |
| 0x6ec      | 1         | 0.53%   |
| 0x506e3    | 1         | 0.53%   |
| 0x406c4    | 1         | 0.53%   |
| 0x30661    | 1         | 0.53%   |
| 0x20652    | 1         | 0.53%   |
| 0x106c2    | 1         | 0.53%   |
| 0x0a50000d | 1         | 0.53%   |
| 0x08600104 | 1         | 0.53%   |
| 0x08600103 | 1         | 0.53%   |
| 0x08600102 | 1         | 0.53%   |
| 0x0810100b | 1         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 25        | 13.89%  |
| IvyBridge        | 24        | 13.33%  |
| KabyLake         | 15        | 8.33%   |
| Core             | 13        | 7.22%   |
| Silvermont       | 10        | 5.56%   |
| Penryn           | 10        | 5.56%   |
| Bonnell          | 10        | 5.56%   |
| Westmere         | 9         | 5%      |
| Unknown          | 7         | 3.89%   |
| Alderlake Hybrid | 6         | 3.33%   |
| TigerLake        | 5         | 2.78%   |
| Icelake          | 5         | 2.78%   |
| Haswell          | 5         | 2.78%   |
| Skylake          | 4         | 2.22%   |
| Goldmont plus    | 4         | 2.22%   |
| Zen+             | 3         | 1.67%   |
| Zen 2            | 3         | 1.67%   |
| Excavator        | 3         | 1.67%   |
| Broadwell        | 3         | 1.67%   |
| Bobcat           | 3         | 1.67%   |
| Zen              | 2         | 1.11%   |
| K8 & K10 hybrid  | 2         | 1.11%   |
| CometLake        | 2         | 1.11%   |
| Zen 3            | 1         | 0.56%   |
| Steamroller      | 1         | 0.56%   |
| P6               | 1         | 0.56%   |
| K8 Hammer        | 1         | 0.56%   |
| K10              | 1         | 0.56%   |
| Jaguar           | 1         | 0.56%   |
| Goldmont         | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 148       | 76.29%  |
| AMD     | 26        | 13.4%   |
| Nvidia  | 17        | 8.76%   |
| Zhaoxin | 3         | 1.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 11.59%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 11.11%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 5.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 4.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 4.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 4.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 3.86%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 8         | 3.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.42%   |
| Intel HD Graphics 620                                                                    | 4         | 1.93%   |
| AMD Lucienne                                                                             | 4         | 1.93%   |
| Zhaoxin KX-6000 C-960 GPU                                                                | 3         | 1.45%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.45%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.45%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.45%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.45%   |
| Nvidia GA107M [GeForce RTX 3050 4GB Laptop GPU]                                          | 2         | 0.97%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.97%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.97%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.97%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 0.97%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.97%   |
| Intel HD Graphics 630                                                                    | 2         | 0.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.97%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 2         | 0.97%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.97%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.48%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.48%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.48%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.48%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 130       | 72.22%  |
| 1 x AMD        | 24        | 13.33%  |
| Intel + Nvidia | 11        | 6.11%   |
| 1 x Nvidia     | 5         | 2.78%   |
| 2 x Intel      | 4         | 2.22%   |
| 1 x Zhaoxin    | 3         | 1.67%   |
| Other          | 1         | 0.56%   |
| Intel + AMD    | 1         | 0.56%   |
| AMD + Nvidia   | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 162       | 89.5%   |
| Proprietary | 12        | 6.63%   |
| Unknown     | 7         | 3.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 149       | 81.87%  |
| 0.01-0.5   | 18        | 9.89%   |
| 1.01-2.0   | 6         | 3.3%    |
| 3.01-4.0   | 4         | 2.2%    |
| 0.51-1.0   | 3         | 1.65%   |
| 5.01-6.0   | 2         | 1.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 34        | 16.92%  |
| Samsung Electronics     | 33        | 16.42%  |
| BOE                     | 31        | 15.42%  |
| Chimei Innolux          | 23        | 11.44%  |
| LG Display              | 22        | 10.95%  |
| InfoVision              | 9         | 4.48%   |
| Lenovo                  | 7         | 3.48%   |
| Chi Mei Optoelectronics | 7         | 3.48%   |
| LG Philips              | 6         | 2.99%   |
| Hewlett-Packard         | 6         | 2.99%   |
| HannStar                | 4         | 1.99%   |
| Goldstar                | 4         | 1.99%   |
| Dell                    | 3         | 1.49%   |
| PANDA                   | 2         | 1%      |
| Vizio                   | 1         | 0.5%    |
| ViewSonic               | 1         | 0.5%    |
| Toshiba                 | 1         | 0.5%    |
| Sharp                   | 1         | 0.5%    |
| Sceptre Tech            | 1         | 0.5%    |
| MStar                   | 1         | 0.5%    |
| KTC                     | 1         | 0.5%    |
| InnoLux Display         | 1         | 0.5%    |
| ASUSTek Computer        | 1         | 0.5%    |
| Acer                    | 1         | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch | 7         | 3.47%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch      | 6         | 2.97%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch        | 5         | 2.48%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 3         | 1.49%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 3         | 1.49%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch          | 3         | 1.49%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 3         | 1.49%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                 | 3         | 1.49%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 3         | 1.49%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                 | 3         | 1.49%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 2         | 0.99%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 2         | 0.99%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.99%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 2         | 0.99%   |
| LG Display LCD Monitor LGD02F8 1366x768 310x170mm 13.9-inch          | 2         | 0.99%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch          | 2         | 0.99%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 2         | 0.99%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 2         | 0.99%   |
| Chimei Innolux N160JME-GL2 CMN1627 1920x1200 344x215mm 16.0-inch     | 2         | 0.99%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 2         | 0.99%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                 | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO8294 1920x1080 382x215mm 17.3-inch       | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch       | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO115C 1366x768 256x144mm 11.6-inch        | 2         | 0.99%   |
| Vizio E3D320VX VIZ0079 1920x1080 698x393mm 31.5-inch                 | 1         | 0.5%    |
| ViewSonic VA2252 Series VSC7731 1920x1080 476x268mm 21.5-inch        | 1         | 0.5%    |
| Toshiba LCD-MONITOR LCDE981 1280x720 400x250mm 18.6-inch             | 1         | 0.5%    |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch              | 1         | 0.5%    |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch       | 1         | 0.5%    |
| Samsung Electronics T27B550 SAM095C 1920x1080 598x336mm 27.0-inch    | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch  | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0426 1920x1200                     | 1         | 0.5%    |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4457 1440x900 303x190mm 14.1-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4241 1280x800 261x163mm 12.1-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 98        | 52.13%  |
| 1920x1080 (FHD)    | 45        | 23.94%  |
| 1280x800 (WXGA)    | 16        | 8.51%   |
| 1920x1200 (WUXGA)  | 4         | 2.13%   |
| 1600x900 (HD+)     | 4         | 2.13%   |
| 3840x2160 (4K)     | 3         | 1.6%    |
| 1440x900 (WXGA+)   | 3         | 1.6%    |
| 1280x1024 (SXGA)   | 3         | 1.6%    |
| 1024x600           | 3         | 1.6%    |
| 2560x1440 (QHD)    | 2         | 1.06%   |
| 1680x1050 (WSXGA+) | 2         | 1.06%   |
| 1360x768           | 2         | 1.06%   |
| 2560x1600          | 1         | 0.53%   |
| 2240x1400          | 1         | 0.53%   |
| 1280x720 (HD)      | 1         | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 68        | 34%     |
| 14      | 41        | 20.5%   |
| 13      | 33        | 16.5%   |
| 21      | 10        | 5%      |
| 17      | 8         | 4%      |
| 11      | 7         | 3.5%    |
| 10      | 6         | 3%      |
| 18      | 4         | 2%      |
| 27      | 3         | 1.5%    |
| 23      | 3         | 1.5%    |
| 16      | 3         | 1.5%    |
| 32      | 2         | 1%      |
| 19      | 2         | 1%      |
| 12      | 2         | 1%      |
| Unknown | 2         | 1%      |
| 54      | 1         | 0.5%    |
| 52      | 1         | 0.5%    |
| 31      | 1         | 0.5%    |
| 24      | 1         | 0.5%    |
| 22      | 1         | 0.5%    |
| 20      | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 141       | 70.85%  |
| 401-500     | 17        | 8.54%   |
| 201-300     | 17        | 8.54%   |
| 351-400     | 11        | 5.53%   |
| 501-600     | 6         | 3.02%   |
| 701-800     | 2         | 1.01%   |
| 1001-1500   | 2         | 1.01%   |
| Unknown     | 2         | 1.01%   |
| 601-700     | 1         | 0.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 147       | 83.05%  |
| 16/10 | 27        | 15.25%  |
| 5/4   | 2         | 1.13%   |
| 3/2   | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 72        | 36%     |
| 101-110        | 68        | 34%     |
| 201-250        | 11        | 5.5%    |
| 51-60          | 7         | 3.5%    |
| 151-200        | 7         | 3.5%    |
| 121-130        | 7         | 3.5%    |
| 41-50          | 6         | 3%      |
| 141-150        | 4         | 2%      |
| 351-500        | 3         | 1.5%    |
| 301-350        | 3         | 1.5%    |
| 111-120        | 3         | 1.5%    |
| More than 1000 | 2         | 1%      |
| 71-80          | 2         | 1%      |
| 61-70          | 2         | 1%      |
| Unknown        | 2         | 1%      |
| 251-300        | 1         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 95        | 48.47%  |
| 121-160       | 55        | 28.06%  |
| 51-100        | 35        | 17.86%  |
| 1-50          | 4         | 2.04%   |
| 161-240       | 4         | 2.04%   |
| Unknown       | 2         | 1.02%   |
| More than 240 | 1         | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 149       | 79.68%  |
| 2     | 29        | 15.51%  |
| 0     | 6         | 3.21%   |
| 3     | 3         | 1.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 116       | 38.93%  |
| Intel                           | 64        | 21.48%  |
| Qualcomm Atheros                | 63        | 21.14%  |
| Broadcom                        | 18        | 6.04%   |
| MediaTek                        | 8         | 2.68%   |
| TP-Link                         | 5         | 1.68%   |
| Broadcom Limited                | 5         | 1.68%   |
| Xiaomi                          | 3         | 1.01%   |
| Marvell Technology Group        | 3         | 1.01%   |
| Samsung Electronics             | 2         | 0.67%   |
| Qualcomm Atheros Communications | 2         | 0.67%   |
| JMicron Technology              | 2         | 0.67%   |
| ASIX Electronics                | 2         | 0.67%   |
| ZyXEL Communications            | 1         | 0.34%   |
| Trendchip Technologies          | 1         | 0.34%   |
| Ralink Technology               | 1         | 0.34%   |
| Huawei Technologies             | 1         | 0.34%   |
| AMD                             | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 60        | 17.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 26        | 7.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 22        | 6.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 2.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 2.62%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.03%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 7         | 2.03%   |
| Intel Wireless 7265                                                     | 7         | 2.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 5         | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.45%   |
| Intel Wireless 7260                                                     | 5         | 1.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 4         | 1.16%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 1.16%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.16%   |
| Intel WiFi Link 5100                                                    | 4         | 1.16%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.16%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.87%   |
| Intel Wireless 3165                                                     | 3         | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.87%   |
| Intel Centrino Wireless-N 105                                           | 3         | 0.87%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.87%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.58%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 2         | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 0.58%   |
| Intel Wireless 8260                                                     | 2         | 0.58%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 34.05%  |
| Qualcomm Atheros                | 49        | 26.49%  |
| Realtek Semiconductor           | 42        | 22.7%   |
| Broadcom                        | 13        | 7.03%   |
| MediaTek                        | 8         | 4.32%   |
| TP-Link                         | 4         | 2.16%   |
| Qualcomm Atheros Communications | 2         | 1.08%   |
| Broadcom Limited                | 2         | 1.08%   |
| Xiaomi                          | 1         | 0.54%   |
| Ralink Technology               | 1         | 0.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 22        | 11.89%  |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 5.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 4.86%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 4.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.78%   |
| Intel Wireless 7265                                                     | 7         | 3.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 3.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.7%    |
| Intel Wireless 7260                                                     | 5         | 2.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 4         | 2.16%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 2.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.16%   |
| Intel Wireless 8265 / 8275                                              | 4         | 2.16%   |
| Intel WiFi Link 5100                                                    | 4         | 2.16%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.16%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 2.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.62%   |
| Intel Wireless 3165                                                     | 3         | 1.62%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.62%   |
| Intel Centrino Wireless-N 105                                           | 3         | 1.62%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.62%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.08%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 2         | 1.08%   |
| Intel Wireless 8260                                                     | 2         | 1.08%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.08%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.08%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.08%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.08%   |
| Intel Centrino Wireless-N 100                                           | 2         | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.08%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 1.08%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                       | 1         | 0.54%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]      | 1         | 0.54%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 94        | 60.65%  |
| Qualcomm Atheros         | 20        | 12.9%   |
| Intel                    | 18        | 11.61%  |
| Broadcom                 | 6         | 3.87%   |
| Marvell Technology Group | 3         | 1.94%   |
| Broadcom Limited         | 3         | 1.94%   |
| Xiaomi                   | 2         | 1.29%   |
| Samsung Electronics      | 2         | 1.29%   |
| JMicron Technology       | 2         | 1.29%   |
| ASIX Electronics         | 2         | 1.29%   |
| ZyXEL Communications     | 1         | 0.65%   |
| Trendchip Technologies   | 1         | 0.65%   |
| TP-Link                  | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 60        | 38.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 26        | 16.56%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 7         | 4.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5         | 3.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 2.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 2.55%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.91%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 1.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 1.27%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.27%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 1.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.27%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express            | 2         | 1.27%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.27%   |
| ZyXEL ADSL Modem Prestige 600 series                                   | 1         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.64%   |
| Trendchip Ethernet controller                                          | 1         | 0.64%   |
| TP-Link M7200                                                          | 1         | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.64%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.64%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.64%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.64%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.64%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 1         | 0.64%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.64%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 0.64%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.64%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.64%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.64%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 175       | 53.52%  |
| Ethernet | 150       | 45.87%  |
| Modem    | 2         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 138       | 73.4%   |
| Ethernet | 50        | 26.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 139       | 77.22%  |
| 1     | 39        | 21.67%  |
| 0     | 2         | 1.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 179       | 98.35%  |
| Yes  | 3         | 1.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 35.71%  |
| Qualcomm Atheros Communications | 17        | 15.18%  |
| IMC Networks                    | 17        | 15.18%  |
| Realtek Semiconductor           | 14        | 12.5%   |
| Broadcom                        | 8         | 7.14%   |
| Lite-On Technology              | 5         | 4.46%   |
| Cambridge Silicon Radio         | 4         | 3.57%   |
| Hewlett-Packard                 | 2         | 1.79%   |
| Dell                            | 2         | 1.79%   |
| Foxconn / Hon Hai               | 1         | 0.89%   |
| ASUSTek Computer                | 1         | 0.89%   |
| Alps Electric                   | 1         | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 21        | 18.75%  |
| Realtek Bluetooth Radio                                     | 9         | 8.04%   |
| Intel AX201 Bluetooth                                       | 8         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                          | 6         | 5.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 6         | 5.36%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 5         | 4.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 4.46%   |
| IMC Networks Wireless_Device                                | 5         | 4.46%   |
| IMC Networks Bluetooth                                      | 4         | 3.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 3.57%   |
| Realtek RTL8723B Bluetooth                                  | 3         | 2.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 2.68%   |
| Broadcom BCM2045 Bluetooth                                  | 3         | 2.68%   |
| Qualcomm Atheros Bluetooth (AR3011)                         | 2         | 1.79%   |
| Lite-On Wireless_Device                                     | 2         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.79%   |
| Intel Bluetooth Device                                      | 2         | 1.79%   |
| Intel AX200 Bluetooth                                       | 2         | 1.79%   |
| IMC Networks Bluetooth Radio                                | 2         | 1.79%   |
| Realtek RTL8723A Bluetooth                                  | 1         | 0.89%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.89%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.89%   |
| Lite-On Bluetooth Device                                    | 1         | 0.89%   |
| Lite-On BCM20702A0                                          | 1         | 0.89%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.89%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.89%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 0.89%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.89%   |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.89%   |
| Broadcom HP Portable Valentine                              | 1         | 0.89%   |
| Broadcom BCM92045B3 ROM                                     | 1         | 0.89%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.89%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 0.89%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 0.89%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 0.89%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 152       | 76.38%  |
| AMD                   | 26        | 13.07%  |
| Nvidia                | 12        | 6.03%   |
| Zhaoxin               | 3         | 1.51%   |
| Texas Instruments     | 1         | 0.5%    |
| Realtek Semiconductor | 1         | 0.5%    |
| Microsoft             | 1         | 0.5%    |
| Logitech              | 1         | 0.5%    |
| Corsair               | 1         | 0.5%    |
| ASUSTek Computer      | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 34        | 14.59%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 6.44%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 5.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 5.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 5.15%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 4.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 4.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 3.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 3%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 3%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 2.15%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.72%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 3         | 1.29%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000/KX-7000 High Definition Audio Controller         | 3         | 1.29%   |
| Nvidia Audio device                                                                               | 3         | 1.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.29%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.29%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.29%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.29%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.29%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.29%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.86%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.86%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 0.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.86%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 0.86%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2         | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 20%     |
| SK hynix            | 30        | 18.75%  |
| Ramaxel Technology  | 20        | 12.5%   |
| Unknown             | 17        | 10.63%  |
| Micron Technology   | 15        | 9.38%   |
| Crucial             | 9         | 5.63%   |
| Kingston            | 8         | 5%      |
| Elpida              | 5         | 3.13%   |
| Unknown (ABCD)      | 2         | 1.25%   |
| Shenzhen WODPOSIT   | 2         | 1.25%   |
| Qimonda             | 2         | 1.25%   |
| Memox               | 2         | 1.25%   |
| Unknown             | 2         | 1.25%   |
| Unknown (081A)      | 1         | 0.63%   |
| Unknown (07F7)      | 1         | 0.63%   |
| Transcend           | 1         | 0.63%   |
| Timetec             | 1         | 0.63%   |
| Team                | 1         | 0.63%   |
| PNY                 | 1         | 0.63%   |
| Hikvision           | 1         | 0.63%   |
| Gold Key            | 1         | 0.63%   |
| ff                  | 1         | 0.63%   |
| Corsair             | 1         | 0.63%   |
| A-DATA Technology   | 1         | 0.63%   |
| <Invalid>           | 1         | 0.63%   |
| 4ea5                | 1         | 0.63%   |
| 48spaces            | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s    | 6         | 3.57%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s    | 5         | 2.98%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 4         | 2.38%   |
| Ramaxel RAM RMT3160ED58E9W1600 4096MB SODIMM DDR3 1600MT/s | 4         | 2.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 3         | 1.79%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s      | 3         | 1.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s      | 3         | 1.79%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s    | 3         | 1.79%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                | 2         | 1.19%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                 | 2         | 1.19%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s    | 2         | 1.19%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s     | 2         | 1.19%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s     | 2         | 1.19%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s     | 2         | 1.19%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 2         | 1.19%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s     | 2         | 1.19%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 2         | 1.19%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 2         | 1.19%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s      | 2         | 1.19%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s   | 2         | 1.19%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s      | 2         | 1.19%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s      | 2         | 1.19%   |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s        | 2         | 1.19%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s       | 2         | 1.19%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s       | 2         | 1.19%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM 1067MT/s          | 2         | 1.19%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s      | 2         | 1.19%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s      | 2         | 1.19%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s    | 2         | 1.19%   |
| Unknown                                                    | 2         | 1.19%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 0.6%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s             | 1         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s             | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM SDRAM                        | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR2                         | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                  | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s             | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s              | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR2                      | 1         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 45        | 38.14%  |
| DDR4   | 44        | 37.29%  |
| DDR2   | 16        | 13.56%  |
| SDRAM  | 6         | 5.08%   |
| LPDDR4 | 4         | 3.39%   |
| DDR    | 2         | 1.69%   |
| DDR5   | 1         | 0.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 109       | 93.97%  |
| Row Of Chips | 5         | 4.31%   |
| DIMM         | 1         | 0.86%   |
| Unknown      | 1         | 0.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 45        | 32.85%  |
| 2048  | 40        | 29.2%   |
| 4096  | 35        | 25.55%  |
| 1024  | 9         | 6.57%   |
| 16384 | 7         | 5.11%   |
| 32768 | 1         | 0.73%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 33        | 24.63%  |
| 3200    | 24        | 17.91%  |
| 2667    | 17        | 12.69%  |
| 2400    | 10        | 7.46%   |
| 667     | 10        | 7.46%   |
| 1333    | 8         | 5.97%   |
| 1334    | 5         | 3.73%   |
| 533     | 4         | 2.99%   |
| 2666    | 3         | 2.24%   |
| 2048    | 3         | 2.24%   |
| Unknown | 3         | 2.24%   |
| 4199    | 2         | 1.49%   |
| 3266    | 2         | 1.49%   |
| 1067    | 2         | 1.49%   |
| 975     | 2         | 1.49%   |
| 800     | 2         | 1.49%   |
| 4800    | 1         | 0.75%   |
| 2133    | 1         | 0.75%   |
| 1867    | 1         | 0.75%   |
| 1066    | 1         | 0.75%   |

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
| Chicony Electronics                    | 25        | 17.61%  |
| Microdia                               | 18        | 12.68%  |
| Bison Electronics                      | 17        | 11.97%  |
| Realtek Semiconductor                  | 13        | 9.15%   |
| IMC Networks                           | 13        | 9.15%   |
| Suyin                                  | 9         | 6.34%   |
| Quanta                                 | 6         | 4.23%   |
| Syntek                                 | 5         | 3.52%   |
| Sunplus Innovation Technology          | 5         | 3.52%   |
| Sonix Technology                       | 4         | 2.82%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.82%   |
| Ricoh                                  | 3         | 2.11%   |
| Luxvisions Innotech Limited            | 3         | 2.11%   |
| ALi                                    | 3         | 2.11%   |
| Lite-On Technology                     | 2         | 1.41%   |
| Importek                               | 2         | 1.41%   |
| Acer                                   | 2         | 1.41%   |
| USB Camera                             | 1         | 0.7%    |
| Tobii Technology AB                    | 1         | 0.7%    |
| Silicon Motion                         | 1         | 0.7%    |
| OmniVision Technologies                | 1         | 0.7%    |
| Logitech                               | 1         | 0.7%    |
| Lenovo                                 | 1         | 0.7%    |
| Apple                                  | 1         | 0.7%    |
| Alcor Micro                            | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                  | 7         | 4.93%   |
| Chicony USB 2.0 Camera                                        | 7         | 4.93%   |
| Microdia USB 2.0 Camera                                       | 6         | 4.23%   |
| Sonix USB2.0 HD UVC WebCam                                    | 4         | 2.82%   |
| Microdia Integrated_Webcam_HD                                 | 4         | 2.82%   |
| Chicony Lenovo EasyCamera                                     | 4         | 2.82%   |
| Chicony Integrated Camera                                     | 4         | 2.82%   |
| Bison USB HD Webcam                                           | 4         | 2.82%   |
| Sunplus Integrated_Webcam_HD                                  | 3         | 2.11%   |
| IMC Networks XHC Camera                                       | 3         | 2.11%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 3         | 2.11%   |
| IMC Networks Integrated Camera                                | 3         | 2.11%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 3         | 2.11%   |
| Bison USB Camera                                              | 3         | 2.11%   |
| Bison HD Webcam                                               | 3         | 2.11%   |
| Suyin Integrated_Webcam_HD                                    | 2         | 1.41%   |
| Suyin HP Webcam 101                                           | 2         | 1.41%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 2         | 1.41%   |
| Realtek USB Camera                                            | 2         | 1.41%   |
| Quanta ACER HD User Facing                                    | 2         | 1.41%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 1.41%   |
| IMC Networks Lenovo EasyCamera                                | 2         | 1.41%   |
| Chicony HD WebCam                                             | 2         | 1.41%   |
| Bison Lenovo EasyCamera                                       | 2         | 1.41%   |
| ALi WebCam                                                    | 2         | 1.41%   |
| USB Camera USB Camera                                         | 1         | 0.7%    |
| Tobii AB EyeChip                                              | 1         | 0.7%    |
| Syntek USB Camera Device                                      | 1         | 0.7%    |
| Syntek USB 2.0 UVC PC Camera                                  | 1         | 0.7%    |
| Syntek Integrated Webcam                                      | 1         | 0.7%    |
| Syntek Integrated Camera                                      | 1         | 0.7%    |
| Syntek EasyCamera                                             | 1         | 0.7%    |
| Suyin USB 2.0 Camera                                          | 1         | 0.7%    |
| Suyin Integrated Webcam                                       | 1         | 0.7%    |
| Suyin HP TrueVision HD                                        | 1         | 0.7%    |
| Suyin HD Video WebCam                                         | 1         | 0.7%    |
| Suyin Acer CrystalEye Webcam                                  | 1         | 0.7%    |
| Sunplus MTD Camera                                            | 1         | 0.7%    |
| Sunplus Lenovo EasyCamera                                     | 1         | 0.7%    |
| Silicon Motion WebCam SC-10HDD13335N                          | 1         | 0.7%    |

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
| Broadcom    | 5         | 71.43%  |
| Alcor Micro | 2         | 28.57%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 42.86%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 28.57%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 28.57%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 129       | 70.49%  |
| 1     | 44        | 24.04%  |
| 2     | 8         | 4.37%   |
| 5     | 1         | 0.55%   |
| 4     | 1         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 21        | 31.34%  |
| Fingerprint reader       | 18        | 26.87%  |
| Net/wireless             | 8         | 11.94%  |
| Chipcard                 | 7         | 10.45%  |
| Sound                    | 5         | 7.46%   |
| Camera                   | 4         | 5.97%   |
| Storage                  | 1         | 1.49%   |
| Multimedia controller    | 1         | 1.49%   |
| Communication controller | 1         | 1.49%   |
| Bluetooth                | 1         | 1.49%   |

