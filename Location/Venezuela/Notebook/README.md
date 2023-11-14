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

Total: 254

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Debian 11          | 16        | 8.74%   |
| Ubuntu 22.04       | 14        | 7.65%   |
| Ubuntu 20.04       | 11        | 6.01%   |
| OpenMandriva 4.3   | 8         | 4.37%   |
| Debian 10          | 6         | 3.28%   |
| Zorin 16           | 5         | 2.73%   |
| Ubuntu 18.04       | 5         | 2.73%   |
| KDE neon 20.04     | 5         | 2.73%   |
| OpenMandriva 4.2   | 4         | 2.19%   |
| Linux Mint 21.1    | 4         | 2.19%   |
| Kubuntu 20.04      | 4         | 2.19%   |
| KDE neon 22.04     | 4         | 2.19%   |
| Debian 12          | 4         | 2.19%   |
| Xubuntu 18.04      | 3         | 1.64%   |
| ROSA R9            | 3         | 1.64%   |
| OpenMandriva 23.03 | 3         | 1.64%   |
| Linux Mint 20.3    | 3         | 1.64%   |
| Zorin 15           | 2         | 1.09%   |
| Xubuntu 22.04      | 2         | 1.09%   |
| Ubuntu Unity 16.04 | 2         | 1.09%   |
| Ubuntu 21.10       | 2         | 1.09%   |
| Ubuntu 19.10       | 2         | 1.09%   |
| Pop!_OS 22.04      | 2         | 1.09%   |
| Pop!_OS 21.04      | 2         | 1.09%   |
| OpenMandriva 23.08 | 2         | 1.09%   |
| OpenMandriva 23.01 | 2         | 1.09%   |
| Manjaro            | 2         | 1.09%   |
| Linux Mint 20      | 2         | 1.09%   |
| Fedora 37          | 2         | 1.09%   |
| Fedora 36          | 2         | 1.09%   |
| Fedora 35          | 2         | 1.09%   |
| ArcoLinux Rolling  | 2         | 1.09%   |
| Arch Rolling       | 2         | 1.09%   |
| Xubuntu 21.10      | 1         | 0.55%   |
| Xubuntu 20.04      | 1         | 0.55%   |
| Xero Rolling       | 1         | 0.55%   |
| Ubuntu MATE 22.04  | 1         | 0.55%   |
| Ubuntu MATE 20.04  | 1         | 0.55%   |
| Ubuntu MATE 19.10  | 1         | 0.55%   |
| Ubuntu 23.04       | 1         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 34        | 19.43%  |
| Debian       | 24        | 13.71%  |
| OpenMandriva | 21        | 12%     |
| Linux Mint   | 12        | 6.86%   |
| KDE neon     | 10        | 5.71%   |
| Zorin        | 7         | 4%      |
| Xubuntu      | 7         | 4%      |
| Fedora       | 7         | 4%      |
| Manjaro      | 6         | 3.43%   |
| Kubuntu      | 6         | 3.43%   |
| ROSA         | 4         | 2.29%   |
| Pop!_OS      | 4         | 2.29%   |
| Ubuntu MATE  | 3         | 1.71%   |
| Kali         | 3         | 1.71%   |
| Arch         | 3         | 1.71%   |
| Ubuntu Unity | 2         | 1.14%   |
| openSUSE     | 2         | 1.14%   |
| MX           | 2         | 1.14%   |
| LMDE         | 2         | 1.14%   |
| ArcoLinux    | 2         | 1.14%   |
| Xero         | 1         | 0.57%   |
| Solus        | 1         | 0.57%   |
| Q4OS         | 1         | 0.57%   |
| Nobara       | 1         | 0.57%   |
| Lubuntu      | 1         | 0.57%   |
| Linux Lite   | 1         | 0.57%   |
| Garuda Linux | 1         | 0.57%   |
| Feren OS     | 1         | 0.57%   |
| EndeavourOS  | 1         | 0.57%   |
| Elementary   | 1         | 0.57%   |
| Deepin       | 1         | 0.57%   |
| BunsenLabs   | 1         | 0.57%   |
| Alpine       | 1         | 0.57%   |
| AlmaLinux    | 1         | 0.57%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 8         | 3.92%   |
| 5.4.0-42-generic                | 4         | 1.96%   |
| 5.15.0-56-generic               | 4         | 1.96%   |
| 5.15.0-46-generic               | 4         | 1.96%   |
| 5.10.14-desktop-1omv4002        | 4         | 1.96%   |
| 5.10.0-23-amd64                 | 4         | 1.96%   |
| 6.2.6-desktop-1omv2390          | 3         | 1.47%   |
| 5.4.0-73-generic                | 3         | 1.47%   |
| 5.4.0-52-generic                | 3         | 1.47%   |
| 5.3.0-40-generic                | 3         | 1.47%   |
| 5.13.0-39-generic               | 3         | 1.47%   |
| 5.10.0-13-amd64                 | 3         | 1.47%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 3         | 1.47%   |
| 4.19.0-17-amd64                 | 3         | 1.47%   |
| 6.4.11-arch2-1                  | 2         | 0.98%   |
| 6.2.0-26-generic                | 2         | 0.98%   |
| 6.1.1-desktop-1omv2290          | 2         | 0.98%   |
| 5.4.0-89-generic                | 2         | 0.98%   |
| 5.4.0-77-generic                | 2         | 0.98%   |
| 5.4.0-48-generic                | 2         | 0.98%   |
| 5.4.0-107-generic               | 2         | 0.98%   |
| 5.19.0-41-generic               | 2         | 0.98%   |
| 5.19.0-40-generic               | 2         | 0.98%   |
| 5.19.0-2-amd64                  | 2         | 0.98%   |
| 5.15.0-76-generic               | 2         | 0.98%   |
| 5.15.0-67-generic               | 2         | 0.98%   |
| 5.15.0-60-generic               | 2         | 0.98%   |
| 5.15.0-48-generic               | 2         | 0.98%   |
| 5.15.0-43-generic               | 2         | 0.98%   |
| 5.11.0-37-generic               | 2         | 0.98%   |
| 5.10.0-21-amd64                 | 2         | 0.98%   |
| 5.10.0-18-amd64                 | 2         | 0.98%   |
| 5.10.0-11-amd64                 | 2         | 0.98%   |
| 5.10.0-10-amd64                 | 2         | 0.98%   |
| 5.0.0-37-generic                | 2         | 0.98%   |
| 6.5.1-desktop-1omv2390          | 1         | 0.49%   |
| 6.4.8-desktop-2omv2390          | 1         | 0.49%   |
| 6.4.2-edwardron-amd64           | 1         | 0.49%   |
| 6.4.2-arch1-1                   | 1         | 0.49%   |
| 6.4.12-1-liquorix-amd64         | 1         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 25        | 13.16%  |
| 5.4.0   | 20        | 10.53%  |
| 5.10.0  | 17        | 8.95%   |
| 5.13.0  | 10        | 5.26%   |
| 6.2.0   | 8         | 4.21%   |
| 5.16.7  | 8         | 4.21%   |
| 4.19.0  | 8         | 4.21%   |
| 5.19.0  | 7         | 3.68%   |
| 5.11.0  | 6         | 3.16%   |
| 5.3.0   | 5         | 2.63%   |
| 5.8.0   | 4         | 2.11%   |
| 5.10.14 | 4         | 2.11%   |
| 4.15.0  | 4         | 2.11%   |
| 6.4.11  | 3         | 1.58%   |
| 6.2.6   | 3         | 1.58%   |
| 6.1.0   | 3         | 1.58%   |
| 4.9.20  | 3         | 1.58%   |
| 6.4.2   | 2         | 1.05%   |
| 6.1.1   | 2         | 1.05%   |
| 5.18.0  | 2         | 1.05%   |
| 5.15.2  | 2         | 1.05%   |
| 5.14.10 | 2         | 1.05%   |
| 5.0.0   | 2         | 1.05%   |
| 6.5.1   | 1         | 0.53%   |
| 6.4.8   | 1         | 0.53%   |
| 6.4.12  | 1         | 0.53%   |
| 6.3.6   | 1         | 0.53%   |
| 6.3.5   | 1         | 0.53%   |
| 6.3.0   | 1         | 0.53%   |
| 6.2.12  | 1         | 0.53%   |
| 6.1.8   | 1         | 0.53%   |
| 6.1.55  | 1         | 0.53%   |
| 6.1.14  | 1         | 0.53%   |
| 6.1.10  | 1         | 0.53%   |
| 6.0.8   | 1         | 0.53%   |
| 6.0.2   | 1         | 0.53%   |
| 5.9.0   | 1         | 0.53%   |
| 5.8.6   | 1         | 0.53%   |
| 5.6.6   | 1         | 0.53%   |
| 5.6.18  | 1         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 33        | 17.55%  |
| 5.10    | 24        | 12.77%  |
| 5.4     | 22        | 11.7%   |
| 6.2     | 12        | 6.38%   |
| 5.13    | 11        | 5.85%   |
| 6.1     | 9         | 4.79%   |
| 5.16    | 8         | 4.26%   |
| 4.19    | 8         | 4.26%   |
| 6.4     | 7         | 3.72%   |
| 5.19    | 7         | 3.72%   |
| 5.11    | 6         | 3.19%   |
| 5.8     | 5         | 2.66%   |
| 5.3     | 5         | 2.66%   |
| 5.17    | 4         | 2.13%   |
| 4.15    | 4         | 2.13%   |
| 6.3     | 3         | 1.6%    |
| 5.14    | 3         | 1.6%    |
| 4.9     | 3         | 1.6%    |
| 6.0     | 2         | 1.06%   |
| 5.6     | 2         | 1.06%   |
| 5.18    | 2         | 1.06%   |
| 5.12    | 2         | 1.06%   |
| 5.0     | 2         | 1.06%   |
| 6.5     | 1         | 0.53%   |
| 5.9     | 1         | 0.53%   |
| 5.5     | 1         | 0.53%   |
| 4.18    | 1         | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 156       | 92.86%  |
| i686   | 12        | 7.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 60        | 33.52%  |
| KDE5          | 45        | 25.14%  |
| XFCE          | 27        | 15.08%  |
| X-Cinnamon    | 11        | 6.15%   |
| Unknown       | 10        | 5.59%   |
| KDE           | 6         | 3.35%   |
| MATE          | 5         | 2.79%   |
| LXQt          | 3         | 1.68%   |
| KDE4          | 3         | 1.68%   |
| Unity         | 2         | 1.12%   |
| Cinnamon      | 2         | 1.12%   |
| Pantheon      | 1         | 0.56%   |
| Openbox       | 1         | 0.56%   |
| GNOME Classic | 1         | 0.56%   |
| Deepin        | 1         | 0.56%   |
| Budgie        | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 141       | 82.46%  |
| Wayland | 27        | 15.79%  |
| Tty     | 2         | 1.17%   |
| Unknown | 1         | 0.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 58        | 32.77%  |
| SDDM    | 35        | 19.77%  |
| LightDM | 30        | 16.95%  |
| GDM3    | 24        | 13.56%  |
| GDM     | 24        | 13.56%  |
| TDM     | 3         | 1.69%   |
| KDM     | 3         | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_VE   | 96        | 54.86%  |
| en_US   | 51        | 29.14%  |
| es_ES   | 12        | 6.86%   |
| Unknown | 8         | 4.57%   |
| es_MX   | 4         | 2.29%   |
| es_US   | 2         | 1.14%   |
| en_CA   | 1         | 0.57%   |
| C       | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 110       | 63.95%  |
| EFI  | 62        | 36.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 131       | 76.16%  |
| Overlay | 19        | 11.05%  |
| Btrfs   | 11        | 6.4%    |
| Tmpfs   | 5         | 2.91%   |
| Xfs     | 3         | 1.74%   |
| Unknown | 3         | 1.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 66        | 37.93%  |
| Unknown | 66        | 37.93%  |
| MBR     | 42        | 24.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 82.29%  |
| Yes       | 31        | 17.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 61.54%  |
| Yes       | 65        | 38.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo                                   | 29        | 17.26%  |
| Dell                                     | 26        | 15.48%  |
| VIT                                      | 25        | 14.88%  |
| Hewlett-Packard                          | 23        | 13.69%  |
| ASUSTek Computer                         | 11        | 6.55%   |
| Acer                                     | 11        | 6.55%   |
| Intel                                    | 9         | 5.36%   |
| Unknown                                  | 5         | 2.98%   |
| Shanghai Zhaoxin Semiconductor           | 3         | 1.79%   |
| Pegatron                                 | 3         | 1.79%   |
| Google                                   | 3         | 1.79%   |
| Toshiba                                  | 2         | 1.19%   |
| Siragon                                  | 2         | 1.19%   |
| Samsung Electronics                      | 2         | 1.19%   |
| Notebook                                 | 2         | 1.19%   |
| MSI                                      | 2         | 1.19%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. | 1         | 0.6%    |
| UNIQCELL                                 | 1         | 0.6%    |
| Sony                                     | 1         | 0.6%    |
| Panasonic                                | 1         | 0.6%    |
| GPU Company                              | 1         | 0.6%    |
| Gateway                                  | 1         | 0.6%    |
| Exo                                      | 1         | 0.6%    |
| Clevo                                    | 1         | 0.6%    |
| AVITA                                    | 1         | 0.6%    |
| Alienware                                | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel powered classmate PC                            | 9         | 5.36%   |
| VIT P2400                                             | 8         | 4.76%   |
| VIT P2402                                             | 5         | 2.98%   |
| Unknown                                               | 5         | 2.98%   |
| VIT P3400                                             | 3         | 1.79%   |
| VIT P1400                                             | 3         | 1.79%   |
| VIT M2420                                             | 3         | 1.79%   |
| Shanghai Zhaoxin ZXE CRB                              | 3         | 1.79%   |
| VIT M2421                                             | 2         | 1.19%   |
| Lenovo IdeaPad S100c 20194                            | 2         | 1.19%   |
| Lenovo 3000 N200 0769ARS                              | 2         | 1.19%   |
| HP Pavilion dv5                                       | 2         | 1.19%   |
| HP Compaq Presario C700                               | 2         | 1.19%   |
| Google Candy                                          | 2         | 1.19%   |
| Dell Inspiron 1545                                    | 2         | 1.19%   |
| ASUS ASUS TUF Gaming F17 FX706HM_TUF706HM             | 2         | 1.19%   |
| Acer Aspire 4739Z                                     | 2         | 1.19%   |
| VIT P2423                                             | 1         | 0.6%    |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. VIT P2460-02 | 1         | 0.6%    |
| UNIQCELL Q15.6                                        | 1         | 0.6%    |
| Toshiba Satellite E55t-A                              | 1         | 0.6%    |
| Toshiba ENCORE 2 WT8-B                                | 1         | 0.6%    |
| Sony VGN-FW510F                                       | 1         | 0.6%    |
| Siragon MN-50                                         | 1         | 0.6%    |
| SIRAGON LM-C100                                       | 1         | 0.6%    |
| Samsung 905S3G/906S3G/915S3G                          | 1         | 0.6%    |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.6%    |
| Pegatron T14AF                                        | 1         | 0.6%    |
| Pegatron H36Y                                         | 1         | 0.6%    |
| Pegatron B74                                          | 1         | 0.6%    |
| Panasonic CF-31RECAXDR                                | 1         | 0.6%    |
| Notebook W54BL                                        | 1         | 0.6%    |
| Notebook NL40_50CU                                    | 1         | 0.6%    |
| MSI MS-1454                                           | 1         | 0.6%    |
| MSI GL73 9SD                                          | 1         | 0.6%    |
| Lenovo Z50-75 80EC                                    | 1         | 0.6%    |
| Lenovo ThinkPad X201 3680AE2                          | 1         | 0.6%    |
| Lenovo ThinkPad T490 20N2000LSP                       | 1         | 0.6%    |
| Lenovo ThinkPad T14 Gen 1 20S1S2FB00                  | 1         | 0.6%    |
| Lenovo ThinkPad SL400 2743A48                         | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Dell Inspiron                                | 13        | 7.74%   |
| Lenovo IdeaPad                               | 11        | 6.55%   |
| Acer Aspire                                  | 10        | 5.95%   |
| Intel powered                                | 9         | 5.36%   |
| HP Pavilion                                  | 9         | 5.36%   |
| VIT P2400                                    | 8         | 4.76%   |
| Lenovo ThinkPad                              | 7         | 4.17%   |
| Dell Latitude                                | 7         | 4.17%   |
| VIT P2402                                    | 5         | 2.98%   |
| ASUS ASUS                                    | 5         | 2.98%   |
| Unknown                                      | 5         | 2.98%   |
| Lenovo 3000                                  | 4         | 2.38%   |
| HP Laptop                                    | 4         | 2.38%   |
| Dell Vostro                                  | 4         | 2.38%   |
| VIT P3400                                    | 3         | 1.79%   |
| VIT P1400                                    | 3         | 1.79%   |
| VIT M2420                                    | 3         | 1.79%   |
| Shanghai Zhaoxin ZXE                         | 3         | 1.79%   |
| HP Compaq                                    | 3         | 1.79%   |
| VIT M2421                                    | 2         | 1.19%   |
| Lenovo Legion                                | 2         | 1.19%   |
| HP Presario                                  | 2         | 1.19%   |
| HP EliteBook                                 | 2         | 1.19%   |
| Google Candy                                 | 2         | 1.19%   |
| ASUS VivoBook                                | 2         | 1.19%   |
| VIT P2423                                    | 1         | 0.6%    |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. VIT | 1         | 0.6%    |
| UNIQCELL Q15.6                               | 1         | 0.6%    |
| Toshiba Satellite                            | 1         | 0.6%    |
| Toshiba ENCORE                               | 1         | 0.6%    |
| Sony VGN-FW510F                              | 1         | 0.6%    |
| Siragon MN-50                                | 1         | 0.6%    |
| SIRAGON LM-C100                              | 1         | 0.6%    |
| Samsung 905S3G                               | 1         | 0.6%    |
| Samsung 355V4C                               | 1         | 0.6%    |
| Pegatron T14AF                               | 1         | 0.6%    |
| Pegatron H36Y                                | 1         | 0.6%    |
| Pegatron B74                                 | 1         | 0.6%    |
| Panasonic CF-31RECAXDR                       | 1         | 0.6%    |
| Notebook W54BL                               | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 20        | 11.9%   |
| 2011    | 20        | 11.9%   |
| 2013    | 19        | 11.31%  |
| 2022    | 13        | 7.74%   |
| 2020    | 10        | 5.95%   |
| 2008    | 10        | 5.95%   |
| 2007    | 10        | 5.95%   |
| 2019    | 9         | 5.36%   |
| 2018    | 9         | 5.36%   |
| 2014    | 9         | 5.36%   |
| 2010    | 9         | 5.36%   |
| 2021    | 7         | 4.17%   |
| 2009    | 6         | 3.57%   |
| 2015    | 5         | 2.98%   |
| 2017    | 4         | 2.38%   |
| Unknown | 3         | 1.79%   |
| 2023    | 2         | 1.19%   |
| 2016    | 2         | 1.19%   |
| 2006    | 1         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 168       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 163       | 97.02%  |
| Enabled  | 5         | 2.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 165       | 98.21%  |
| Yes  | 3         | 1.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 48        | 28.24%  |
| 4.01-8.0   | 39        | 22.94%  |
| 1.01-2.0   | 31        | 18.24%  |
| 8.01-16.0  | 26        | 15.29%  |
| 16.01-24.0 | 13        | 7.65%   |
| 2.01-3.0   | 7         | 4.12%   |
| 32.01-64.0 | 4         | 2.35%   |
| 24.01-32.0 | 1         | 0.59%   |
| 0.51-1.0   | 1         | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 67        | 35.26%  |
| 2.01-3.0   | 47        | 24.74%  |
| 4.01-8.0   | 26        | 13.68%  |
| 0.51-1.0   | 23        | 12.11%  |
| 3.01-4.0   | 19        | 10%     |
| 8.01-16.0  | 5         | 2.63%   |
| 0.01-0.5   | 2         | 1.05%   |
| 16.01-24.0 | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 114       | 66.28%  |
| 2      | 53        | 30.81%  |
| 3      | 4         | 2.33%   |
| 0      | 1         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 51.79%  |
| Yes       | 81        | 48.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 85.29%  |
| No        | 25        | 14.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 163       | 97.02%  |
| No        | 5         | 2.98%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 58.24%  |
| No        | 71        | 41.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Venezuela | 168       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 75        | 40.98%  |
| Maracaibo                  | 20        | 10.93%  |
| Maracay                    | 9         | 4.92%   |
| Valencia                   | 6         | 3.28%   |
| Mérida                    | 6         | 3.28%   |
| Barquisimeto               | 6         | 3.28%   |
| Barcelona                  | 5         | 2.73%   |
| Ciudad Guayana             | 4         | 2.19%   |
| San Cristóbal             | 3         | 1.64%   |
| Maturín                   | 3         | 1.64%   |
| San Carlos del Zulia       | 2         | 1.09%   |
| Punto Fijo                 | 2         | 1.09%   |
| Porlamar                   | 2         | 1.09%   |
| Lecherias                  | 2         | 1.09%   |
| La Guaira                  | 2         | 1.09%   |
| Guatire                    | 2         | 1.09%   |
| Cagua                      | 2         | 1.09%   |
| Anaco                      | 2         | 1.09%   |
| Villa de Cura              | 1         | 0.55%   |
| Tucape                     | 1         | 0.55%   |
| San Juan Bautista          | 1         | 0.55%   |
| San Felipe                 | 1         | 0.55%   |
| San Diego                  | 1         | 0.55%   |
| San Antonio de Los Altos   | 1         | 0.55%   |
| Puerto Ordaz and San Felix | 1         | 0.55%   |
| Puerto Cumarebo            | 1         | 0.55%   |
| Puerto Cruz                | 1         | 0.55%   |
| Petare                     | 1         | 0.55%   |
| Parroquia El Recreo        | 1         | 0.55%   |
| Naguanagua                 | 1         | 0.55%   |
| Mariara                    | 1         | 0.55%   |
| Maiquetia                  | 1         | 0.55%   |
| Los Palos Grandes          | 1         | 0.55%   |
| Las Vegas                  | 1         | 0.55%   |
| Las Tienditas              | 1         | 0.55%   |
| Las Mercedes               | 1         | 0.55%   |
| Guarenas                   | 1         | 0.55%   |
| Guanare                    | 1         | 0.55%   |
| El Hatillo Municipality    | 1         | 0.55%   |
| Ejido                      | 1         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 35        | 37     | 17.5%   |
| WDC                       | 32        | 43     | 16%     |
| Toshiba                   | 21        | 22     | 10.5%   |
| Unknown                   | 13        | 18     | 6.5%    |
| Samsung Electronics       | 12        | 12     | 6%      |
| Intel                     | 9         | 12     | 4.5%    |
| Hitachi                   | 9         | 10     | 4.5%    |
| Sandisk                   | 7         | 11     | 3.5%    |
| Crucial                   | 6         | 9      | 3%      |
| Micron Technology         | 5         | 8      | 2.5%    |
| HGST                      | 5         | 5      | 2.5%    |
| SK hynix                  | 4         | 6      | 2%      |
| PNY                       | 4         | 4      | 2%      |
| LITEONIT                  | 4         | 8      | 2%      |
| Kingston                  | 4         | 6      | 2%      |
| SPCC                      | 3         | 6      | 1.5%    |
| addlink                   | 3         | 3      | 1.5%    |
| Team                      | 2         | 2      | 1%      |
| Silicon Motion            | 2         | 2      | 1%      |
| Patriot                   | 2         | 2      | 1%      |
| HUAWEI                    | 2         | 2      | 1%      |
| Fujitsu                   | 2         | 2      | 1%      |
| BIWIN                     | 2         | 3      | 1%      |
| Vaseky                    | 1         | 1      | 0.5%    |
| PUSKILL                   | 1         | 1      | 0.5%    |
| Phison                    | 1         | 1      | 0.5%    |
| Micron/Crucial Technology | 1         | 1      | 0.5%    |
| Lexar                     | 1         | 1      | 0.5%    |
| KingFast                  | 1         | 3      | 0.5%    |
| Intenso                   | 1         | 1      | 0.5%    |
| Emtec                     | 1         | 1      | 0.5%    |
| Dell                      | 1         | 2      | 0.5%    |
| China                     | 1         | 1      | 0.5%    |
| Apacer                    | 1         | 1      | 0.5%    |
| A-DATA Technology         | 1         | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD3200BPVT-22JJ5T0 320GB        | 4         | 1.95%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 1.95%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 1.46%   |
| Unknown NVMe SSD Drive 512GB        | 3         | 1.46%   |
| Seagate ST320LT012-9WS14C 320GB     | 3         | 1.46%   |
| Seagate ST320LT012-1DG14C 320GB     | 3         | 1.46%   |
| Seagate ST250LM004 HN-M250MBB 250GB | 3         | 1.46%   |
| LITEONIT LMS-32L6M 32GB SSD         | 3         | 1.46%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.98%   |
| WDC WD5000LPVT-08G33T1 500GB        | 2         | 0.98%   |
| WDC WD3200BEVT-00A0RT0 320GB        | 2         | 0.98%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2         | 0.98%   |
| WDC WD1200BEVS-60UST0 120GB         | 2         | 0.98%   |
| Unknown MMC Card  64GB              | 2         | 0.98%   |
| Unknown MMC Card  16GB              | 2         | 0.98%   |
| Toshiba MQ04ABF100 1TB              | 2         | 0.98%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.98%   |
| Toshiba MQ01ABF032 320GB            | 2         | 0.98%   |
| Toshiba MQ01ABD050 500GB            | 2         | 0.98%   |
| Toshiba MK3276GSX 320GB             | 2         | 0.98%   |
| Toshiba MK3275GSX 320GB             | 2         | 0.98%   |
| SK hynix HFM001TD3JX013N 1024GB     | 2         | 0.98%   |
| Seagate ST9500325AS 500GB           | 2         | 0.98%   |
| Seagate ST9320325AS 320GB           | 2         | 0.98%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 0.98%   |
| Seagate ST500LM021-1KJ152 500GB     | 2         | 0.98%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 2         | 0.98%   |
| Seagate ST320LM000 HM321HI 320GB    | 2         | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.98%   |
| SanDisk NVMe SSD Drive 1TB          | 2         | 0.98%   |
| Samsung HN-M320MBB 320GB            | 2         | 0.98%   |
| PNY CS900 480GB SSD                 | 2         | 0.98%   |
| PNY CS900 1TB SSD                   | 2         | 0.98%   |
| Micron 2450_MTFDKBA512TFK 512GB     | 2         | 0.98%   |
| Intel SSDPEKNU512GZ 512GB           | 2         | 0.98%   |
| HUAWEI SD Storage 33GB              | 2         | 0.98%   |
| Hitachi HTS725050A9A364 500GB       | 2         | 0.98%   |
| HGST HTS721010A9E630 1TB            | 2         | 0.98%   |
| HGST HTS545050A7E380 500GB          | 2         | 0.98%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 34     | 31.07%  |
| WDC                 | 30        | 38     | 29.13%  |
| Toshiba             | 20        | 21     | 19.42%  |
| Hitachi             | 9         | 10     | 8.74%   |
| HGST                | 5         | 5      | 4.85%   |
| Samsung Electronics | 3         | 3      | 2.91%   |
| Unknown             | 2         | 2      | 1.94%   |
| Fujitsu             | 2         | 2      | 1.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 6         | 9      | 13.95%  |
| Samsung Electronics | 5         | 5      | 11.63%  |
| PNY                 | 4         | 4      | 9.3%    |
| LITEONIT            | 4         | 8      | 9.3%    |
| Kingston            | 3         | 5      | 6.98%   |
| SPCC                | 2         | 4      | 4.65%   |
| SanDisk             | 2         | 3      | 4.65%   |
| Patriot             | 2         | 2      | 4.65%   |
| Vaseky              | 1         | 1      | 2.33%   |
| Toshiba             | 1         | 1      | 2.33%   |
| Team                | 1         | 1      | 2.33%   |
| PUSKILL             | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 3      | 2.33%   |
| Lexar               | 1         | 1      | 2.33%   |
| KingFast            | 1         | 3      | 2.33%   |
| Intenso             | 1         | 1      | 2.33%   |
| Intel               | 1         | 1      | 2.33%   |
| Emtec               | 1         | 1      | 2.33%   |
| Dell                | 1         | 2      | 2.33%   |
| China               | 1         | 1      | 2.33%   |
| BIWIN               | 1         | 2      | 2.33%   |
| addlink             | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 101       | 115    | 52.33%  |
| SSD     | 42        | 61     | 21.76%  |
| NVMe    | 36        | 55     | 18.65%  |
| MMC     | 9         | 12     | 4.66%   |
| Unknown | 5         | 5      | 2.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 131       | 174    | 71.58%  |
| NVMe | 36        | 55     | 19.67%  |
| MMC  | 9         | 12     | 4.92%   |
| SAS  | 7         | 7      | 3.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 115       | 145    | 83.33%  |
| 0.51-1.0   | 22        | 30     | 15.94%  |
| 1.01-2.0   | 1         | 1      | 0.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 59        | 33.15%  |
| 101-250        | 45        | 25.28%  |
| 501-1000       | 25        | 14.04%  |
| 1-20           | 19        | 10.67%  |
| 51-100         | 11        | 6.18%   |
| 21-50          | 10        | 5.62%   |
| 1001-2000      | 4         | 2.25%   |
| 2001-3000      | 2         | 1.12%   |
| Unknown        | 2         | 1.12%   |
| More than 3000 | 1         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 69        | 36.7%   |
| 21-50     | 34        | 18.09%  |
| 101-250   | 31        | 16.49%  |
| 51-100    | 29        | 15.43%  |
| 251-500   | 14        | 7.45%   |
| 501-1000  | 8         | 4.26%   |
| Unknown   | 2         | 1.06%   |
| 2001-3000 | 1         | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD1200BEVS-60UST0 120GB          | 2         | 2      | 6.45%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 6.45%   |
| Hitachi HTS725050A9A364 500GB        | 2         | 2      | 6.45%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 1      | 3.23%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 3.23%   |
| WDC WD3200BEVT-00A0RT0 320GB         | 1         | 1      | 3.23%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2      | 3.23%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 3.23%   |
| Toshiba MK3276GSX 320GB              | 1         | 1      | 3.23%   |
| Toshiba MK3275GSX 320GB              | 1         | 1      | 3.23%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 3.23%   |
| Toshiba MK2565GSX 250GB              | 1         | 1      | 3.23%   |
| Toshiba MK1032GSX 100GB              | 1         | 1      | 3.23%   |
| Seagate ST9320325AS 320GB            | 1         | 1      | 3.23%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 3.23%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 3.23%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 3.23%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 3.23%   |
| Samsung Electronics HN-M320MBB 320GB | 1         | 1      | 3.23%   |
| Samsung Electronics HM250HI 250GB    | 1         | 1      | 3.23%   |
| Intel SSDPEKKW256G7 256GB            | 1         | 1      | 3.23%   |
| Intel SSDPEKKF512G7L 512GB           | 1         | 1      | 3.23%   |
| Hitachi HTS543232L9A300 320GB        | 1         | 1      | 3.23%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1      | 3.23%   |
| Hitachi HTS542525K9SA00 250GB        | 1         | 1      | 3.23%   |
| HGST HTS545050A7E380 500GB           | 1         | 1      | 3.23%   |
| HGST HTS541010A7E630 1TB             | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 7      | 22.58%  |
| Seagate             | 7         | 7      | 22.58%  |
| WDC                 | 6         | 7      | 19.35%  |
| Hitachi             | 5         | 5      | 16.13%  |
| Samsung Electronics | 2         | 2      | 6.45%   |
| Intel               | 2         | 2      | 6.45%   |
| HGST                | 2         | 2      | 6.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 7      | 24.14%  |
| Seagate             | 7         | 7      | 24.14%  |
| WDC                 | 6         | 7      | 20.69%  |
| Hitachi             | 5         | 5      | 17.24%  |
| Samsung Electronics | 2         | 2      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 30     | 93.55%  |
| NVMe | 2         | 2      | 6.45%   |

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
| Detected | 86        | 128    | 47.51%  |
| Works    | 64        | 88     | 35.36%  |
| Malfunc  | 31        | 32     | 17.13%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 135       | 72.58%  |
| AMD                         | 21        | 11.29%  |
| SanDisk                     | 6         | 3.23%   |
| SK hynix                    | 4         | 2.15%   |
| Samsung Electronics         | 4         | 2.15%   |
| Micron Technology           | 4         | 2.15%   |
| Silicon Motion              | 3         | 1.61%   |
| Phison Electronics          | 3         | 1.61%   |
| Jiangsu Huacun Elec.        | 3         | 1.61%   |
| Micron/Crucial Technology   | 1         | 0.54%   |
| MAXIO Technology (Hangzhou) | 1         | 0.54%   |
| Kingston Technology Company | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 26        | 12.56%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 8.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 7.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 4.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 4.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 9         | 4.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 3.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 3.38%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 7         | 3.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 2.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 2.9%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 1.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 1.93%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 1.45%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 1.45%   |
| Jiangsu Huacun Elec. MMY MMSP350 PCIe 3 NVMe SSD (DRAM-less)                   | 3         | 1.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.45%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.97%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2         | 0.97%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 0.97%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.97%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.97%   |
| Intel SSD 600P Series                                                          | 2         | 0.97%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 2         | 0.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 0.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.97%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 0.97%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 0.97%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 0.97%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 0.48%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.48%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 0.48%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 123       | 61.81%  |
| NVMe | 36        | 18.09%  |
| IDE  | 21        | 10.55%  |
| RAID | 19        | 9.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 141       | 83.93%  |
| AMD          | 24        | 14.29%  |
| CentaurHauls | 3         | 1.79%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz                | 8         | 4.76%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 6         | 3.57%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 5         | 2.98%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 4         | 2.38%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 4         | 2.38%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 3         | 1.79%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 3         | 1.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 3         | 1.79%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 3         | 1.79%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 3         | 1.79%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 3         | 1.79%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 3         | 1.79%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 1.19%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 2         | 1.19%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 2         | 1.19%   |
| Intel Core i5-3337U CPU @ 1.80GHz              | 2         | 1.19%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 1.19%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 2         | 1.19%   |
| Intel Core i3-4000M CPU @ 2.40GHz              | 2         | 1.19%   |
| Intel Core i3-2350M CPU @ 2.30GHz              | 2         | 1.19%   |
| Intel Core i3 CPU M 330 @ 2.13GHz              | 2         | 1.19%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz           | 2         | 1.19%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz           | 2         | 1.19%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 2         | 1.19%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 2         | 1.19%   |
| Intel Celeron CPU N2805 @ 1.46GHz              | 2         | 1.19%   |
| Intel Atom CPU N570 @ 1.66GHz                  | 2         | 1.19%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 2         | 1.19%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 1.19%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 2         | 1.19%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 2         | 1.19%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 2         | 1.19%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 0.6%    |
| Intel Pentium Dual CPU T3400 @ 2.16GHz         | 1         | 0.6%    |
| Intel Pentium CPU N3710 @ 1.60GHz              | 1         | 0.6%    |
| Intel Pentium CPU B940 @ 2.00GHz               | 1         | 0.6%    |
| Intel Pentium CPU 6405U @ 2.40GHz              | 1         | 0.6%    |
| Intel Pentium CPU 2030M @ 2.50GHz              | 1         | 0.6%    |
| Intel Genuine CPU U7300 @ 1.30GHz              | 1         | 0.6%    |
| Intel Genuine CPU T2080 @ 1.73GHz              | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 31        | 18.45%  |
| Intel Core i3                        | 26        | 15.48%  |
| Intel Celeron                        | 19        | 11.31%  |
| Intel Core 2 Duo                     | 15        | 8.93%   |
| Intel Core i7                        | 14        | 8.33%   |
| Other                                | 13        | 7.74%   |
| Intel Atom                           | 11        | 6.55%   |
| Intel Pentium                        | 7         | 4.17%   |
| AMD Ryzen 5                          | 7         | 4.17%   |
| AMD Ryzen 7                          | 5         | 2.98%   |
| Intel Pentium Dual                   | 4         | 2.38%   |
| Intel Pentium Dual-Core              | 2         | 1.19%   |
| Intel Genuine                        | 2         | 1.19%   |
| AMD A10                              | 2         | 1.19%   |
| Intel Pentium Silver                 | 1         | 0.6%    |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.6%    |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.6%    |
| AMD Ryzen 3                          | 1         | 0.6%    |
| AMD Quad-Core                        | 1         | 0.6%    |
| AMD Mobile Sempron                   | 1         | 0.6%    |
| AMD E1                               | 1         | 0.6%    |
| AMD E                                | 1         | 0.6%    |
| AMD C-70                             | 1         | 0.6%    |
| AMD A6                               | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 113       | 67.26%  |
| 4       | 28        | 16.67%  |
| 1       | 9         | 5.36%   |
| 8       | 7         | 4.17%   |
| 6       | 7         | 4.17%   |
| Unknown | 2         | 1.19%   |
| 14      | 1         | 0.6%    |
| 10      | 1         | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 168       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 104       | 61.9%   |
| 1       | 62        | 36.9%   |
| Unknown | 2         | 1.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 162       | 96.43%  |
| 64-bit         | 3         | 1.79%   |
| 32-bit         | 3         | 1.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 29.55%  |
| 0x206a7    | 17        | 9.66%   |
| 0x306a9    | 16        | 9.09%   |
| 0x1067a    | 11        | 6.25%   |
| 0x6fd      | 8         | 4.55%   |
| 0x106ca    | 6         | 3.41%   |
| 0x806e9    | 5         | 2.84%   |
| 0x30678    | 5         | 2.84%   |
| 0x20655    | 4         | 2.27%   |
| 0x806ec    | 3         | 1.7%    |
| 0x806c1    | 3         | 1.7%    |
| 0x406e3    | 3         | 1.7%    |
| 0x40651    | 3         | 1.7%    |
| 0x806ea    | 2         | 1.14%   |
| 0x806d1    | 2         | 1.14%   |
| 0x306d4    | 2         | 1.14%   |
| 0x306c3    | 2         | 1.14%   |
| 0x30673    | 2         | 1.14%   |
| 0x08608103 | 2         | 1.14%   |
| 0x08108102 | 2         | 1.14%   |
| 0x05000119 | 2         | 1.14%   |
| 0x02000057 | 2         | 1.14%   |
| 0x906ea    | 1         | 0.57%   |
| 0x906e9    | 1         | 0.57%   |
| 0x906a4    | 1         | 0.57%   |
| 0x706e5    | 1         | 0.57%   |
| 0x706a8    | 1         | 0.57%   |
| 0x6ec      | 1         | 0.57%   |
| 0x506e3    | 1         | 0.57%   |
| 0x406c4    | 1         | 0.57%   |
| 0x30661    | 1         | 0.57%   |
| 0x20652    | 1         | 0.57%   |
| 0x106c2    | 1         | 0.57%   |
| 0x0a50000d | 1         | 0.57%   |
| 0x08600104 | 1         | 0.57%   |
| 0x08600103 | 1         | 0.57%   |
| 0x08600102 | 1         | 0.57%   |
| 0x0810100b | 1         | 0.57%   |
| 0x08101007 | 1         | 0.57%   |
| 0x06006705 | 1         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 25        | 14.88%  |
| IvyBridge        | 22        | 13.1%   |
| KabyLake         | 14        | 8.33%   |
| Core             | 12        | 7.14%   |
| Penryn           | 10        | 5.95%   |
| Bonnell          | 10        | 5.95%   |
| Westmere         | 9         | 5.36%   |
| Silvermont       | 9         | 5.36%   |
| Unknown          | 7         | 4.17%   |
| Haswell          | 5         | 2.98%   |
| TigerLake        | 4         | 2.38%   |
| Skylake          | 4         | 2.38%   |
| Icelake          | 4         | 2.38%   |
| Zen+             | 3         | 1.79%   |
| Zen 2            | 3         | 1.79%   |
| Goldmont plus    | 3         | 1.79%   |
| Excavator        | 3         | 1.79%   |
| Broadwell        | 3         | 1.79%   |
| Bobcat           | 3         | 1.79%   |
| Alderlake Hybrid | 3         | 1.79%   |
| Zen              | 2         | 1.19%   |
| K8 & K10 hybrid  | 2         | 1.19%   |
| CometLake        | 2         | 1.19%   |
| Zen 3            | 1         | 0.6%    |
| Steamroller      | 1         | 0.6%    |
| P6               | 1         | 0.6%    |
| K8 Hammer        | 1         | 0.6%    |
| Jaguar           | 1         | 0.6%    |
| Goldmont         | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 137       | 76.54%  |
| AMD     | 25        | 13.97%  |
| Nvidia  | 14        | 7.82%   |
| Zhaoxin | 3         | 1.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 12.57%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 10.99%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 5.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 5.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 5.24%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 4.71%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 8         | 4.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 3.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.09%   |
| Intel HD Graphics 620                                                                    | 4         | 2.09%   |
| AMD Lucienne                                                                             | 4         | 2.09%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 3         | 1.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.57%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.05%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.05%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.05%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.05%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.05%   |
| Intel HD Graphics 630                                                                    | 2         | 1.05%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.05%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.05%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 2         | 1.05%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 1.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.05%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.52%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.52%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.52%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 0.52%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.52%   |
| Nvidia GF104GLM [Quadro 3000M]                                                           | 1         | 0.52%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.52%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 123       | 73.21%  |
| 1 x AMD        | 23        | 13.69%  |
| Intel + Nvidia | 8         | 4.76%   |
| 1 x Nvidia     | 5         | 2.98%   |
| 2 x Intel      | 4         | 2.38%   |
| 1 x Zhaoxin    | 3         | 1.79%   |
| Intel + AMD    | 1         | 0.6%    |
| AMD + Nvidia   | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 154       | 91.12%  |
| Proprietary | 9         | 5.33%   |
| Unknown     | 6         | 3.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 138       | 81.18%  |
| 0.01-0.5   | 17        | 10%     |
| 1.01-2.0   | 6         | 3.53%   |
| 3.01-4.0   | 4         | 2.35%   |
| 0.51-1.0   | 3         | 1.76%   |
| 5.01-6.0   | 2         | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 31        | 16.85%  |
| Samsung Electronics     | 29        | 15.76%  |
| BOE                     | 29        | 15.76%  |
| LG Display              | 22        | 11.96%  |
| Chimei Innolux          | 20        | 10.87%  |
| Chi Mei Optoelectronics | 7         | 3.8%    |
| LG Philips              | 6         | 3.26%   |
| Lenovo                  | 6         | 3.26%   |
| InfoVision              | 6         | 3.26%   |
| Hewlett-Packard         | 6         | 3.26%   |
| HannStar                | 4         | 2.17%   |
| Goldstar                | 4         | 2.17%   |
| Dell                    | 3         | 1.63%   |
| PANDA                   | 2         | 1.09%   |
| Vizio                   | 1         | 0.54%   |
| ViewSonic               | 1         | 0.54%   |
| Sharp                   | 1         | 0.54%   |
| Sceptre Tech            | 1         | 0.54%   |
| MStar                   | 1         | 0.54%   |
| KTC                     | 1         | 0.54%   |
| InnoLux Display         | 1         | 0.54%   |
| ASUSTek Computer        | 1         | 0.54%   |
| Acer                    | 1         | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 7         | 3.78%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch       | 6         | 3.24%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch         | 5         | 2.7%    |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 3         | 1.62%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 3         | 1.62%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                  | 3         | 1.62%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                  | 3         | 1.62%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2         | 1.08%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 1.08%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.08%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch           | 2         | 1.08%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 2         | 1.08%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 2         | 1.08%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch           | 2         | 1.08%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch           | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 2         | 1.08%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                  | 2         | 1.08%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                  | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO8294 1920x1080 382x215mm 17.3-inch        | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch        | 2         | 1.08%   |
| Vizio E3D320VX VIZ0079 1920x1080 698x393mm 31.5-inch                  | 1         | 0.54%   |
| ViewSonic VA2252 SERIES VSC7731 1920x1080 476x268mm 21.5-inch         | 1         | 0.54%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.54%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 1         | 0.54%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch     | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 0.54%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4241 1280x800 261x163mm 12.1-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDC8151 1920x1080 382x214mm 17.2-inch | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 92        | 53.8%   |
| 1920x1080 (FHD)    | 40        | 23.39%  |
| 1280x800 (WXGA)    | 16        | 9.36%   |
| 3840x2160 (4K)     | 3         | 1.75%   |
| 1600x900 (HD+)     | 3         | 1.75%   |
| 1024x600           | 3         | 1.75%   |
| 2560x1440 (QHD)    | 2         | 1.17%   |
| 1920x1200 (WUXGA)  | 2         | 1.17%   |
| 1680x1050 (WSXGA+) | 2         | 1.17%   |
| 1440x900 (WXGA+)   | 2         | 1.17%   |
| 1360x768           | 2         | 1.17%   |
| 1280x1024 (SXGA)   | 2         | 1.17%   |
| 2240x1400          | 1         | 0.58%   |
| 1280x720 (HD)      | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 65        | 35.52%  |
| 14      | 38        | 20.77%  |
| 13      | 32        | 17.49%  |
| 21      | 8         | 4.37%   |
| 17      | 8         | 4.37%   |
| 10      | 6         | 3.28%   |
| 11      | 5         | 2.73%   |
| 23      | 3         | 1.64%   |
| 18      | 3         | 1.64%   |
| 32      | 2         | 1.09%   |
| 27      | 2         | 1.09%   |
| 12      | 2         | 1.09%   |
| Unknown | 2         | 1.09%   |
| 54      | 1         | 0.55%   |
| 52      | 1         | 0.55%   |
| 31      | 1         | 0.55%   |
| 24      | 1         | 0.55%   |
| 22      | 1         | 0.55%   |
| 20      | 1         | 0.55%   |
| 19      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 131       | 71.98%  |
| 201-300     | 15        | 8.24%   |
| 401-500     | 14        | 7.69%   |
| 351-400     | 10        | 5.49%   |
| 501-600     | 5         | 2.75%   |
| 701-800     | 2         | 1.1%    |
| 1001-1500   | 2         | 1.1%    |
| Unknown     | 2         | 1.1%    |
| 601-700     | 1         | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 136       | 84.47%  |
| 16/10 | 22        | 13.66%  |
| 5/4   | 2         | 1.24%   |
| 3/2   | 1         | 0.62%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 68        | 37.16%  |
| 101-110        | 65        | 35.52%  |
| 201-250        | 11        | 6.01%   |
| 121-130        | 7         | 3.83%   |
| 41-50          | 6         | 3.28%   |
| 51-60          | 5         | 2.73%   |
| 141-150        | 4         | 2.19%   |
| 351-500        | 3         | 1.64%   |
| 151-200        | 3         | 1.64%   |
| More than 1000 | 2         | 1.09%   |
| 71-80          | 2         | 1.09%   |
| 61-70          | 2         | 1.09%   |
| 301-350        | 2         | 1.09%   |
| Unknown        | 2         | 1.09%   |
| 251-300        | 1         | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 89        | 49.44%  |
| 121-160       | 48        | 26.67%  |
| 51-100        | 33        | 18.33%  |
| 1-50          | 4         | 2.22%   |
| 161-240       | 3         | 1.67%   |
| Unknown       | 2         | 1.11%   |
| More than 240 | 1         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 141       | 80.57%  |
| 2     | 26        | 14.86%  |
| 0     | 6         | 3.43%   |
| 3     | 2         | 1.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 110       | 39.57%  |
| Qualcomm Atheros                | 60        | 21.58%  |
| Intel                           | 59        | 21.22%  |
| Broadcom                        | 16        | 5.76%   |
| MediaTek                        | 6         | 2.16%   |
| Broadcom Limited                | 5         | 1.8%    |
| TP-Link                         | 4         | 1.44%   |
| Xiaomi                          | 3         | 1.08%   |
| Marvell Technology Group        | 3         | 1.08%   |
| Samsung Electronics             | 2         | 0.72%   |
| Qualcomm Atheros Communications | 2         | 0.72%   |
| JMicron Technology              | 2         | 0.72%   |
| ZyXEL Communications            | 1         | 0.36%   |
| Trendchip Technologies          | 1         | 0.36%   |
| Ralink Technology               | 1         | 0.36%   |
| Huawei Technologies             | 1         | 0.36%   |
| ASIX Electronics                | 1         | 0.36%   |
| AMD                             | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 57        | 17.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 26        | 8.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 20        | 6.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 3.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 2.79%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 2.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 7         | 2.17%   |
| Intel Wireless 7265                                                     | 7         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 5         | 1.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.55%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 1.24%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.24%   |
| Intel Wireless 7260                                                     | 4         | 1.24%   |
| Intel WiFi Link 5100                                                    | 4         | 1.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 1.24%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.24%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.93%   |
| Intel Wireless 3165                                                     | 3         | 0.93%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.93%   |
| Intel Centrino Wireless-N 105                                           | 3         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.93%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.93%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 0.62%   |
| Intel Wireless 8260                                                     | 2         | 0.62%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 33.92%  |
| Qualcomm Atheros                | 46        | 26.9%   |
| Realtek Semiconductor           | 40        | 23.39%  |
| Broadcom                        | 12        | 7.02%   |
| MediaTek                        | 6         | 3.51%   |
| TP-Link                         | 3         | 1.75%   |
| Qualcomm Atheros Communications | 2         | 1.17%   |
| Broadcom Limited                | 2         | 1.17%   |
| Xiaomi                          | 1         | 0.58%   |
| Ralink Technology               | 1         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 20        | 11.7%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 5.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 5.26%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 4.68%   |
| Intel Wireless 7265                                                     | 7         | 4.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 3.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 2.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.34%   |
| Intel Wireless 8265 / 8275                                              | 4         | 2.34%   |
| Intel Wireless 7260                                                     | 4         | 2.34%   |
| Intel WiFi Link 5100                                                    | 4         | 2.34%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 2.34%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.75%   |
| Intel Wireless 3165                                                     | 3         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.75%   |
| Intel Centrino Wireless-N 105                                           | 3         | 1.75%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.75%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1.75%   |
| Intel Wireless 8260                                                     | 2         | 1.17%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.17%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.17%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.17%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.17%   |
| Intel Centrino Wireless-N 100                                           | 2         | 1.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.17%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 1.17%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                       | 1         | 0.58%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]      | 1         | 0.58%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 0.58%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.58%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.58%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 90        | 60.4%   |
| Qualcomm Atheros         | 20        | 13.42%  |
| Intel                    | 18        | 12.08%  |
| Broadcom                 | 5         | 3.36%   |
| Marvell Technology Group | 3         | 2.01%   |
| Broadcom Limited         | 3         | 2.01%   |
| Xiaomi                   | 2         | 1.34%   |
| Samsung Electronics      | 2         | 1.34%   |
| JMicron Technology       | 2         | 1.34%   |
| ZyXEL Communications     | 1         | 0.67%   |
| Trendchip Technologies   | 1         | 0.67%   |
| TP-Link                  | 1         | 0.67%   |
| ASIX Electronics         | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 57        | 38%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 17.33%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 4.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 3.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2%      |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.33%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 1.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.33%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 2         | 1.33%   |
| ZyXEL ADSL Modem Prestige 600 series                              | 1         | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.67%   |
| Trendchip Ethernet controller                                     | 1         | 0.67%   |
| TP-Link M7200                                                     | 1         | 0.67%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.67%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.67%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.67%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.67%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.67%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.67%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.67%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.67%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.67%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.67%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.67%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 163       | 52.75%  |
| Ethernet | 144       | 46.6%   |
| Modem    | 2         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 127       | 72.57%  |
| Ethernet | 48        | 27.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 134       | 79.76%  |
| 1     | 32        | 19.05%  |
| 0     | 2         | 1.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 167       | 98.82%  |
| Yes  | 2         | 1.18%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 36%     |
| Qualcomm Atheros Communications | 16        | 16%     |
| Realtek Semiconductor           | 13        | 13%     |
| IMC Networks                    | 13        | 13%     |
| Broadcom                        | 6         | 6%      |
| Lite-On Technology              | 5         | 5%      |
| Cambridge Silicon Radio         | 4         | 4%      |
| Hewlett-Packard                 | 2         | 2%      |
| ISSC                            | 1         | 1%      |
| Foxconn / Hon Hai               | 1         | 1%      |
| Dell                            | 1         | 1%      |
| ASUSTek Computer                | 1         | 1%      |
| Alps Electric                   | 1         | 1%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 20        | 20%     |
| Realtek Bluetooth Radio                                     | 8         | 8%      |
| Intel AX201 Bluetooth                                       | 6         | 6%      |
| Qualcomm Atheros  Bluetooth Device                          | 5         | 5%      |
| Qualcomm Atheros AR3011 Bluetooth                           | 5         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 4%      |
| IMC Networks Bluetooth                                      | 4         | 4%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 4         | 4%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 4%      |
| Realtek RTL8723B Bluetooth                                  | 3         | 3%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 3%      |
| IMC Networks Wireless_Device                                | 3         | 3%      |
| Broadcom BCM2045 Bluetooth                                  | 3         | 3%      |
| Qualcomm Atheros Bluetooth (AR3011)                         | 2         | 2%      |
| Lite-On Wireless_Device                                     | 2         | 2%      |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2%      |
| Intel Bluetooth Device                                      | 2         | 2%      |
| Intel AX200 Bluetooth                                       | 2         | 2%      |
| IMC Networks Bluetooth Radio                                | 2         | 2%      |
| Realtek RTL8723A Bluetooth                                  | 1         | 1%      |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1%      |
| Lite-On Bluetooth Device                                    | 1         | 1%      |
| Lite-On BCM20702A0                                          | 1         | 1%      |
| ISSC Bluetooth Device                                       | 1         | 1%      |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 1%      |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1%      |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 1%      |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 1%      |
| Broadcom HP Portable Valentine                              | 1         | 1%      |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1%      |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1%      |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 141       | 76.22%  |
| AMD                   | 25        | 13.51%  |
| Nvidia                | 11        | 5.95%   |
| Zhaoxin               | 3         | 1.62%   |
| Realtek Semiconductor | 1         | 0.54%   |
| Microsoft             | 1         | 0.54%   |
| Logitech              | 1         | 0.54%   |
| Corsair               | 1         | 0.54%   |
| ASUSTek Computer      | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32        | 14.68%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 6.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 5.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 5.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 5.05%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 4.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 4.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 4.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 3.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 2.29%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.83%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 3         | 1.38%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000 High Definition Audio Controller                 | 3         | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.38%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.38%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.38%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.38%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.92%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.92%   |
| Nvidia Audio device                                                                               | 2         | 0.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.92%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.92%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.92%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.92%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 0.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.92%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2         | 0.92%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.92%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.92%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 28        | 19.18%  |
| Samsung Electronics | 28        | 19.18%  |
| Ramaxel Technology  | 18        | 12.33%  |
| Unknown             | 17        | 11.64%  |
| Micron Technology   | 13        | 8.9%    |
| Crucial             | 9         | 6.16%   |
| Kingston            | 7         | 4.79%   |
| Elpida              | 5         | 3.42%   |
| Unknown (ABCD)      | 2         | 1.37%   |
| Shenzhen WODPOSIT   | 2         | 1.37%   |
| Qimonda             | 2         | 1.37%   |
| Memox               | 2         | 1.37%   |
| Unknown             | 2         | 1.37%   |
| Unknown (081A)      | 1         | 0.68%   |
| Unknown (07F7)      | 1         | 0.68%   |
| Transcend           | 1         | 0.68%   |
| Team                | 1         | 0.68%   |
| PNY                 | 1         | 0.68%   |
| Hikvision           | 1         | 0.68%   |
| Gold Key            | 1         | 0.68%   |
| Corsair             | 1         | 0.68%   |
| A-DATA Technology   | 1         | 0.68%   |
| <Invalid>           | 1         | 0.68%   |
| 48spaces            | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s          | 6         | 3.9%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 2.6%    |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s       | 4         | 2.6%    |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 4         | 2.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.95%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 3         | 1.95%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s          | 3         | 1.95%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 1.3%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.3%    |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s          | 2         | 1.3%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 2         | 1.3%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.3%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.3%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.3%    |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.3%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.3%    |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s            | 2         | 1.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.3%    |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 1.3%    |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s              | 2         | 1.3%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.3%    |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 1.3%    |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 1.3%    |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 1.3%    |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s          | 2         | 1.3%    |
| Unknown                                                          | 2         | 1.3%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.65%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.65%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 1         | 0.65%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 43        | 39.09%  |
| DDR4   | 40        | 36.36%  |
| DDR2   | 16        | 14.55%  |
| SDRAM  | 6         | 5.45%   |
| LPDDR4 | 3         | 2.73%   |
| DDR5   | 1         | 0.91%   |
| DDR    | 1         | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 103       | 95.37%  |
| Row Of Chips | 4         | 3.7%    |
| DIMM         | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 42        | 32.81%  |
| 2048  | 39        | 30.47%  |
| 4096  | 32        | 25%     |
| 16384 | 7         | 5.47%   |
| 1024  | 7         | 5.47%   |
| 32768 | 1         | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 32        | 25.6%   |
| 3200    | 20        | 16%     |
| 2667    | 17        | 13.6%   |
| 667     | 9         | 7.2%    |
| 2400    | 8         | 6.4%    |
| 1333    | 8         | 6.4%    |
| 1334    | 5         | 4%      |
| 533     | 4         | 3.2%    |
| 2666    | 3         | 2.4%    |
| 2048    | 3         | 2.4%    |
| Unknown | 3         | 2.4%    |
| 4199    | 2         | 1.6%    |
| 1067    | 2         | 1.6%    |
| 975     | 2         | 1.6%    |
| 800     | 2         | 1.6%    |
| 4800    | 1         | 0.8%    |
| 3266    | 1         | 0.8%    |
| 2133    | 1         | 0.8%    |
| 1867    | 1         | 0.8%    |
| 1066    | 1         | 0.8%    |

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
| Chicony Electronics                    | 25        | 18.8%   |
| Microdia                               | 16        | 12.03%  |
| Bison Electronics                      | 15        | 11.28%  |
| Realtek Semiconductor                  | 11        | 8.27%   |
| IMC Networks                           | 11        | 8.27%   |
| Suyin                                  | 9         | 6.77%   |
| Quanta                                 | 6         | 4.51%   |
| Syntek                                 | 5         | 3.76%   |
| Sunplus Innovation Technology          | 5         | 3.76%   |
| Sonix Technology                       | 4         | 3.01%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.01%   |
| Ricoh                                  | 3         | 2.26%   |
| Luxvisions Innotech Limited            | 3         | 2.26%   |
| ALi                                    | 3         | 2.26%   |
| Lite-On Technology                     | 2         | 1.5%    |
| Importek                               | 2         | 1.5%    |
| Tobii Technology AB                    | 1         | 0.75%   |
| Silicon Motion                         | 1         | 0.75%   |
| OmniVision Technologies                | 1         | 0.75%   |
| Logitech                               | 1         | 0.75%   |
| Lenovo                                 | 1         | 0.75%   |
| icSpring                               | 1         | 0.75%   |
| Apple                                  | 1         | 0.75%   |
| Alcor Micro                            | 1         | 0.75%   |
| Acer                                   | 1         | 0.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                        | 7         | 5.26%   |
| Microdia USB 2.0 Camera                                       | 6         | 4.51%   |
| Bison HD Webcam                                               | 5         | 3.76%   |
| Sonix USB2.0 HD UVC WebCam                                    | 4         | 3.01%   |
| Realtek Integrated_Webcam_HD                                  | 4         | 3.01%   |
| Chicony Lenovo EasyCamera                                     | 4         | 3.01%   |
| Chicony Integrated Camera                                     | 4         | 3.01%   |
| Sunplus Integrated_Webcam_HD                                  | 3         | 2.26%   |
| IMC Networks XHC Camera                                       | 3         | 2.26%   |
| IMC Networks Integrated Camera                                | 3         | 2.26%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 3         | 2.26%   |
| Bison USB Camera                                              | 3         | 2.26%   |
| Suyin Integrated_Webcam_HD                                    | 2         | 1.5%    |
| Suyin HP Webcam 101                                           | 2         | 1.5%    |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 2         | 1.5%    |
| Realtek Integrated Webcam HD                                  | 2         | 1.5%    |
| Quanta ACER HD User Facing                                    | 2         | 1.5%    |
| Microdia Integrated_Webcam_HD                                 | 2         | 1.5%    |
| Microdia Integrated_Webcam_1.3M                               | 2         | 1.5%    |
| IMC Networks Lenovo EasyCamera                                | 2         | 1.5%    |
| Chicony HD WebCam                                             | 2         | 1.5%    |
| Bison Lenovo EasyCamera                                       | 2         | 1.5%    |
| ALi WebCam                                                    | 2         | 1.5%    |
| Tobii AB EyeChip                                              | 1         | 0.75%   |
| Syntek USB Camera Device                                      | 1         | 0.75%   |
| Syntek USB 2.0 UVC PC Camera                                  | 1         | 0.75%   |
| Syntek Integrated Webcam                                      | 1         | 0.75%   |
| Syntek Integrated Camera                                      | 1         | 0.75%   |
| Syntek EasyCamera                                             | 1         | 0.75%   |
| Suyin USB 2.0 Camera                                          | 1         | 0.75%   |
| Suyin Integrated Webcam                                       | 1         | 0.75%   |
| Suyin HP TrueVision HD                                        | 1         | 0.75%   |
| Suyin Acer HD Crystal Eye webcam                              | 1         | 0.75%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 0.75%   |
| Sunplus Lenovo EasyCamera                                     | 1         | 0.75%   |
| Sunplus Camera                                                | 1         | 0.75%   |
| Silicon Motion WebCam SC-10HDD13335N                          | 1         | 0.75%   |
| Ricoh Sony Vaio Integrated Webcam                             | 1         | 0.75%   |
| Realtek USB2.0 VGA UVC WebCam                                 | 1         | 0.75%   |
| Realtek USB2.0 camera                                         | 1         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 47.06%  |
| AuthenTec                  | 3         | 17.65%  |
| Synaptics                  | 2         | 11.76%  |
| Upek                       | 1         | 5.88%   |
| Shenzhen Goodix Technology | 1         | 5.88%   |
| Futronic Technology        | 1         | 5.88%   |
| Elan Microelectronics      | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 17.65%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 11.76%  |
| Validity Sensors Fingerprint scanner                   | 2         | 11.76%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 11.76%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 11.76%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5.88%   |
| Futronic Fingerprint Scanner Model FS88                | 1         | 5.88%   |
| Elan ELAN:ARM-M4                                       | 1         | 5.88%   |
| AuthenTec AES1600                                      | 1         | 5.88%   |

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
| 0     | 124       | 72.51%  |
| 1     | 35        | 20.47%  |
| 2     | 10        | 5.85%   |
| 4     | 2         | 1.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 19        | 30.65%  |
| Fingerprint reader       | 17        | 27.42%  |
| Chipcard                 | 7         | 11.29%  |
| Net/wireless             | 6         | 9.68%   |
| Sound                    | 5         | 8.06%   |
| Camera                   | 4         | 6.45%   |
| Storage                  | 1         | 1.61%   |
| Multimedia controller    | 1         | 1.61%   |
| Communication controller | 1         | 1.61%   |
| Bluetooth                | 1         | 1.61%   |

