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

Total: 215

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Debian 11                    | 12        | 7.84%   |
| Ubuntu 20.04                 | 11        | 7.19%   |
| Ubuntu 22.04                 | 10        | 6.54%   |
| OpenMandriva 4.3             | 8         | 5.23%   |
| Debian 10                    | 6         | 3.92%   |
| Ubuntu 18.04                 | 5         | 3.27%   |
| KDE neon 20.04               | 5         | 3.27%   |
| Zorin 16                     | 4         | 2.61%   |
| Kubuntu 20.04                | 4         | 2.61%   |
| Xubuntu 18.04                | 3         | 1.96%   |
| ROSA R9                      | 3         | 1.96%   |
| OpenMandriva 4.2             | 3         | 1.96%   |
| OpenMandriva 23.03           | 3         | 1.96%   |
| Linux Mint 21.1              | 3         | 1.96%   |
| Linux Mint 20.3              | 3         | 1.96%   |
| KDE neon 22.04               | 3         | 1.96%   |
| Zorin 15                     | 2         | 1.31%   |
| Xubuntu 22.04                | 2         | 1.31%   |
| Ubuntu Unity 16.04           | 2         | 1.31%   |
| Ubuntu 21.10                 | 2         | 1.31%   |
| Ubuntu 19.10                 | 2         | 1.31%   |
| Pop!_OS 22.04                | 2         | 1.31%   |
| Pop!_OS 21.04                | 2         | 1.31%   |
| OpenMandriva 23.01           | 2         | 1.31%   |
| Manjaro                      | 2         | 1.31%   |
| Linux Mint 20                | 2         | 1.31%   |
| Fedora 37                    | 2         | 1.31%   |
| Fedora 36                    | 2         | 1.31%   |
| Fedora 35                    | 2         | 1.31%   |
| ArcoLinux Rolling            | 2         | 1.31%   |
| Xubuntu 21.10                | 1         | 0.65%   |
| Xubuntu 20.04                | 1         | 0.65%   |
| Ubuntu MATE 20.04            | 1         | 0.65%   |
| Ubuntu MATE 19.10            | 1         | 0.65%   |
| Ubuntu 16.04                 | 1         | 0.65%   |
| Solus 4.1                    | 1         | 0.65%   |
| ROSA R11                     | 1         | 0.65%   |
| Q4OS 4                       | 1         | 0.65%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.65%   |
| OpenMandriva 4.50            | 1         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 29        | 19.86%  |
| Debian       | 18        | 12.33%  |
| OpenMandriva | 16        | 10.96%  |
| Linux Mint   | 10        | 6.85%   |
| KDE neon     | 9         | 6.16%   |
| Xubuntu      | 7         | 4.79%   |
| Fedora       | 7         | 4.79%   |
| Zorin        | 6         | 4.11%   |
| Manjaro      | 6         | 4.11%   |
| Kubuntu      | 6         | 4.11%   |
| ROSA         | 4         | 2.74%   |
| Pop!_OS      | 4         | 2.74%   |
| Ubuntu Unity | 2         | 1.37%   |
| Ubuntu MATE  | 2         | 1.37%   |
| LMDE         | 2         | 1.37%   |
| ArcoLinux    | 2         | 1.37%   |
| Solus        | 1         | 0.68%   |
| Q4OS         | 1         | 0.68%   |
| openSUSE     | 1         | 0.68%   |
| Nobara       | 1         | 0.68%   |
| MX           | 1         | 0.68%   |
| Lubuntu      | 1         | 0.68%   |
| Linux Lite   | 1         | 0.68%   |
| Kali         | 1         | 0.68%   |
| Garuda Linux | 1         | 0.68%   |
| Feren OS     | 1         | 0.68%   |
| Elementary   | 1         | 0.68%   |
| Deepin       | 1         | 0.68%   |
| BunsenLabs   | 1         | 0.68%   |
| Arch         | 1         | 0.68%   |
| Alpine       | 1         | 0.68%   |
| AlmaLinux    | 1         | 0.68%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 8         | 4.71%   |
| 5.4.0-42-generic                | 4         | 2.35%   |
| 5.15.0-56-generic               | 4         | 2.35%   |
| 5.15.0-46-generic               | 4         | 2.35%   |
| 6.2.6-desktop-1omv2390          | 3         | 1.76%   |
| 5.4.0-73-generic                | 3         | 1.76%   |
| 5.4.0-52-generic                | 3         | 1.76%   |
| 5.3.0-40-generic                | 3         | 1.76%   |
| 5.13.0-39-generic               | 3         | 1.76%   |
| 5.10.14-desktop-1omv4002        | 3         | 1.76%   |
| 5.10.0-13-amd64                 | 3         | 1.76%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 3         | 1.76%   |
| 4.19.0-17-amd64                 | 3         | 1.76%   |
| 6.1.1-desktop-1omv2290          | 2         | 1.18%   |
| 5.4.0-89-generic                | 2         | 1.18%   |
| 5.4.0-77-generic                | 2         | 1.18%   |
| 5.4.0-48-generic                | 2         | 1.18%   |
| 5.4.0-107-generic               | 2         | 1.18%   |
| 5.19.0-40-generic               | 2         | 1.18%   |
| 5.19.0-2-amd64                  | 2         | 1.18%   |
| 5.15.0-67-generic               | 2         | 1.18%   |
| 5.15.0-60-generic               | 2         | 1.18%   |
| 5.15.0-48-generic               | 2         | 1.18%   |
| 5.15.0-43-generic               | 2         | 1.18%   |
| 5.11.0-37-generic               | 2         | 1.18%   |
| 5.10.0-21-amd64                 | 2         | 1.18%   |
| 5.10.0-18-amd64                 | 2         | 1.18%   |
| 5.10.0-11-amd64                 | 2         | 1.18%   |
| 5.10.0-10-amd64                 | 2         | 1.18%   |
| 5.0.0-37-generic                | 2         | 1.18%   |
| 6.2.12-300.fc38.x86_64          | 1         | 0.59%   |
| 6.2.0-060200-generic            | 1         | 0.59%   |
| 6.1.8-200.fc37.x86_64           | 1         | 0.59%   |
| 6.1.14-201.fsync.fc37.x86_64    | 1         | 0.59%   |
| 6.1.10-100.fc36.x86_64          | 1         | 0.59%   |
| 6.1.0-3-amd64                   | 1         | 0.59%   |
| 6.0.8-arch1-1                   | 1         | 0.59%   |
| 6.0.2-76060002-generic          | 1         | 0.59%   |
| 5.9.0-5-amd64                   | 1         | 0.59%   |
| 5.8.6-1-MANJARO                 | 1         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 23        | 14.56%  |
| 5.4.0   | 20        | 12.66%  |
| 5.10.0  | 13        | 8.23%   |
| 5.13.0  | 10        | 6.33%   |
| 5.16.7  | 8         | 5.06%   |
| 4.19.0  | 8         | 5.06%   |
| 5.11.0  | 6         | 3.8%    |
| 5.3.0   | 5         | 3.16%   |
| 5.19.0  | 5         | 3.16%   |
| 5.8.0   | 4         | 2.53%   |
| 4.15.0  | 4         | 2.53%   |
| 6.2.6   | 3         | 1.9%    |
| 5.10.14 | 3         | 1.9%    |
| 4.9.20  | 3         | 1.9%    |
| 6.1.1   | 2         | 1.27%   |
| 5.15.2  | 2         | 1.27%   |
| 5.14.10 | 2         | 1.27%   |
| 5.0.0   | 2         | 1.27%   |
| 6.2.12  | 1         | 0.63%   |
| 6.2.0   | 1         | 0.63%   |
| 6.1.8   | 1         | 0.63%   |
| 6.1.14  | 1         | 0.63%   |
| 6.1.10  | 1         | 0.63%   |
| 6.1.0   | 1         | 0.63%   |
| 6.0.8   | 1         | 0.63%   |
| 6.0.2   | 1         | 0.63%   |
| 5.9.0   | 1         | 0.63%   |
| 5.8.6   | 1         | 0.63%   |
| 5.6.6   | 1         | 0.63%   |
| 5.6.18  | 1         | 0.63%   |
| 5.5.4   | 1         | 0.63%   |
| 5.4.83  | 1         | 0.63%   |
| 5.4.105 | 1         | 0.63%   |
| 5.18.0  | 1         | 0.63%   |
| 5.17.2  | 1         | 0.63%   |
| 5.17.15 | 1         | 0.63%   |
| 5.17.12 | 1         | 0.63%   |
| 5.17.11 | 1         | 0.63%   |
| 5.15.8  | 1         | 0.63%   |
| 5.15.65 | 1         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 31        | 19.87%  |
| 5.4     | 22        | 14.1%   |
| 5.10    | 19        | 12.18%  |
| 5.13    | 11        | 7.05%   |
| 5.16    | 8         | 5.13%   |
| 4.19    | 8         | 5.13%   |
| 6.1     | 6         | 3.85%   |
| 5.11    | 6         | 3.85%   |
| 6.2     | 5         | 3.21%   |
| 5.8     | 5         | 3.21%   |
| 5.3     | 5         | 3.21%   |
| 5.19    | 5         | 3.21%   |
| 5.17    | 4         | 2.56%   |
| 4.15    | 4         | 2.56%   |
| 4.9     | 3         | 1.92%   |
| 6.0     | 2         | 1.28%   |
| 5.6     | 2         | 1.28%   |
| 5.14    | 2         | 1.28%   |
| 5.12    | 2         | 1.28%   |
| 5.0     | 2         | 1.28%   |
| 5.9     | 1         | 0.64%   |
| 5.5     | 1         | 0.64%   |
| 5.18    | 1         | 0.64%   |
| 4.18    | 1         | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 129       | 92.14%  |
| i686   | 11        | 7.86%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 50        | 33.11%  |
| KDE5          | 36        | 23.84%  |
| XFCE          | 23        | 15.23%  |
| X-Cinnamon    | 9         | 5.96%   |
| Unknown       | 9         | 5.96%   |
| KDE           | 6         | 3.97%   |
| MATE          | 4         | 2.65%   |
| LXQt          | 3         | 1.99%   |
| KDE4          | 3         | 1.99%   |
| Unity         | 2         | 1.32%   |
| Cinnamon      | 2         | 1.32%   |
| Pantheon      | 1         | 0.66%   |
| GNOME Classic | 1         | 0.66%   |
| Deepin        | 1         | 0.66%   |
| Budgie        | 1         | 0.66%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 124       | 87.32%  |
| Wayland | 17        | 11.97%  |
| Tty     | 1         | 0.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 55        | 36.91%  |
| SDDM    | 27        | 18.12%  |
| LightDM | 23        | 15.44%  |
| GDM     | 22        | 14.77%  |
| GDM3    | 16        | 10.74%  |
| TDM     | 3         | 2.01%   |
| KDM     | 3         | 2.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_VE   | 80        | 54.79%  |
| en_US   | 44        | 30.14%  |
| es_ES   | 10        | 6.85%   |
| Unknown | 7         | 4.79%   |
| es_US   | 2         | 1.37%   |
| es_MX   | 2         | 1.37%   |
| en_CA   | 1         | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 93        | 64.58%  |
| EFI  | 51        | 35.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 111       | 77.62%  |
| Overlay | 16        | 11.19%  |
| Btrfs   | 10        | 6.99%   |
| Xfs     | 3         | 2.1%    |
| Unknown | 3         | 2.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 64        | 44.14%  |
| GPT     | 48        | 33.1%   |
| MBR     | 33        | 22.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 82.88%  |
| Yes       | 25        | 17.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 88        | 62.41%  |
| Yes       | 53        | 37.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 27        | 19.29%  |
| Dell                           | 23        | 16.43%  |
| VIT                            | 19        | 13.57%  |
| Hewlett-Packard                | 18        | 12.86%  |
| ASUSTek Computer               | 8         | 5.71%   |
| Acer                           | 8         | 5.71%   |
| Intel                          | 7         | 5%      |
| Unknown                        | 5         | 3.57%   |
| Shanghai Zhaoxin Semiconductor | 3         | 2.14%   |
| Pegatron                       | 3         | 2.14%   |
| Google                         | 3         | 2.14%   |
| Toshiba                        | 2         | 1.43%   |
| Samsung Electronics            | 2         | 1.43%   |
| Notebook                       | 2         | 1.43%   |
| MSI                            | 2         | 1.43%   |
| UNIQCELL                       | 1         | 0.71%   |
| Sony                           | 1         | 0.71%   |
| GPU Company                    | 1         | 0.71%   |
| Gateway                        | 1         | 0.71%   |
| Exo                            | 1         | 0.71%   |
| Clevo                          | 1         | 0.71%   |
| AVITA                          | 1         | 0.71%   |
| Alienware                      | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Intel powered classmate PC                | 7         | 5%      |
| VIT P2400                                 | 5         | 3.57%   |
| Unknown                                   | 5         | 3.57%   |
| VIT P2402                                 | 4         | 2.86%   |
| VIT P3400                                 | 3         | 2.14%   |
| VIT M2420                                 | 3         | 2.14%   |
| Shanghai Zhaoxin ZXE CRB                  | 3         | 2.14%   |
| VIT P1400                                 | 2         | 1.43%   |
| VIT M2421                                 | 2         | 1.43%   |
| Lenovo IdeaPad S100c 20194                | 2         | 1.43%   |
| Lenovo 3000 N200 0769ARS                  | 2         | 1.43%   |
| HP Compaq Presario C700                   | 2         | 1.43%   |
| Google Candy                              | 2         | 1.43%   |
| Dell Inspiron 1545                        | 2         | 1.43%   |
| ASUS ASUS TUF Gaming F17 FX706HM_TUF706HM | 2         | 1.43%   |
| Acer Aspire 4739Z                         | 2         | 1.43%   |
| UNIQCELL Q15.6                            | 1         | 0.71%   |
| Toshiba Satellite E55t-A                  | 1         | 0.71%   |
| Toshiba ENCORE 2 WT8-B                    | 1         | 0.71%   |
| Sony VGN-FW510F                           | 1         | 0.71%   |
| Samsung 905S3G/906S3G/915S3G              | 1         | 0.71%   |
| Samsung 355V4C/356V4C/3445VC/3545VC       | 1         | 0.71%   |
| Pegatron T14AF                            | 1         | 0.71%   |
| Pegatron H36Y                             | 1         | 0.71%   |
| Pegatron B74                              | 1         | 0.71%   |
| Notebook W54BL                            | 1         | 0.71%   |
| Notebook NL40_50CU                        | 1         | 0.71%   |
| MSI MS-1454                               | 1         | 0.71%   |
| MSI GL73 9SD                              | 1         | 0.71%   |
| Lenovo Z50-75 80EC                        | 1         | 0.71%   |
| Lenovo ThinkPad X201 3680AE2              | 1         | 0.71%   |
| Lenovo ThinkPad T14 Gen 1 20S1S2FB00      | 1         | 0.71%   |
| Lenovo ThinkPad SL400 2743A48             | 1         | 0.71%   |
| Lenovo ThinkPad SL 2743A65                | 1         | 0.71%   |
| Lenovo ThinkPad Edge 01962AS              | 1         | 0.71%   |
| Lenovo ThinkPad E560 20EV002FUS           | 1         | 0.71%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 0.71%   |
| Lenovo Legion 5 15ARH05H 82B1             | 1         | 0.71%   |
| Lenovo IdeaPad Z580                       | 1         | 0.71%   |
| Lenovo IdeaPad S110 20126                 | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 11        | 7.86%   |
| Lenovo IdeaPad       | 10        | 7.14%   |
| Intel powered        | 7         | 5%      |
| HP Pavilion          | 7         | 5%      |
| Acer Aspire          | 7         | 5%      |
| Lenovo ThinkPad      | 6         | 4.29%   |
| Dell Latitude        | 6         | 4.29%   |
| VIT P2400            | 5         | 3.57%   |
| Unknown              | 5         | 3.57%   |
| VIT P2402            | 4         | 2.86%   |
| Lenovo 3000          | 4         | 2.86%   |
| Dell Vostro          | 4         | 2.86%   |
| VIT P3400            | 3         | 2.14%   |
| VIT M2420            | 3         | 2.14%   |
| Shanghai Zhaoxin ZXE | 3         | 2.14%   |
| ASUS ASUS            | 3         | 2.14%   |
| VIT P1400            | 2         | 1.43%   |
| VIT M2421            | 2         | 1.43%   |
| Lenovo Legion        | 2         | 1.43%   |
| HP Presario          | 2         | 1.43%   |
| HP Laptop            | 2         | 1.43%   |
| HP EliteBook         | 2         | 1.43%   |
| HP Compaq            | 2         | 1.43%   |
| Google Candy         | 2         | 1.43%   |
| ASUS VivoBook        | 2         | 1.43%   |
| UNIQCELL Q15.6       | 1         | 0.71%   |
| Toshiba Satellite    | 1         | 0.71%   |
| Toshiba ENCORE       | 1         | 0.71%   |
| Sony VGN-FW510F      | 1         | 0.71%   |
| Samsung 905S3G       | 1         | 0.71%   |
| Samsung 355V4C       | 1         | 0.71%   |
| Pegatron T14AF       | 1         | 0.71%   |
| Pegatron H36Y        | 1         | 0.71%   |
| Pegatron B74         | 1         | 0.71%   |
| Notebook W54BL       | 1         | 0.71%   |
| Notebook NL40        | 1         | 0.71%   |
| MSI MS-1454          | 1         | 0.71%   |
| MSI GL73             | 1         | 0.71%   |
| Lenovo Z50-75        | 1         | 0.71%   |
| Lenovo G570          | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 17        | 12.14%  |
| 2011    | 16        | 11.43%  |
| 2012    | 14        | 10%     |
| 2020    | 10        | 7.14%   |
| 2007    | 10        | 7.14%   |
| 2022    | 9         | 6.43%   |
| 2010    | 9         | 6.43%   |
| 2018    | 8         | 5.71%   |
| 2014    | 8         | 5.71%   |
| 2019    | 7         | 5%      |
| 2008    | 7         | 5%      |
| 2021    | 6         | 4.29%   |
| 2009    | 6         | 4.29%   |
| 2017    | 4         | 2.86%   |
| 2015    | 4         | 2.86%   |
| Unknown | 2         | 1.43%   |
| 2023    | 1         | 0.71%   |
| 2016    | 1         | 0.71%   |
| 2006    | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 140       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 136       | 97.14%  |
| Enabled  | 4         | 2.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 137       | 97.86%  |
| Yes  | 3         | 2.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 41        | 29.08%  |
| 4.01-8.0   | 33        | 23.4%   |
| 1.01-2.0   | 26        | 18.44%  |
| 8.01-16.0  | 19        | 13.48%  |
| 16.01-24.0 | 10        | 7.09%   |
| 2.01-3.0   | 6         | 4.26%   |
| 32.01-64.0 | 4         | 2.84%   |
| 24.01-32.0 | 1         | 0.71%   |
| 0.51-1.0   | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 58        | 37.18%  |
| 2.01-3.0   | 37        | 23.72%  |
| 0.51-1.0   | 21        | 13.46%  |
| 4.01-8.0   | 20        | 12.82%  |
| 3.01-4.0   | 15        | 9.62%   |
| 8.01-16.0  | 4         | 2.56%   |
| 16.01-24.0 | 1         | 0.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 94        | 65.73%  |
| 2      | 44        | 30.77%  |
| 3      | 4         | 2.8%    |
| 0      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 71        | 50.71%  |
| Yes       | 69        | 49.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 84.51%  |
| No        | 22        | 15.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 97.14%  |
| No        | 4         | 2.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 58.87%  |
| No        | 58        | 41.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Venezuela | 140       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 65        | 42.76%  |
| Maracaibo                  | 16        | 10.53%  |
| Maracay                    | 8         | 5.26%   |
| Mérida                    | 7         | 4.61%   |
| Barquisimeto               | 7         | 4.61%   |
| Valencia                   | 4         | 2.63%   |
| Barcelona                  | 4         | 2.63%   |
| Maturín                   | 3         | 1.97%   |
| San Cristóbal             | 2         | 1.32%   |
| San Carlos del Zulia       | 2         | 1.32%   |
| Porlamar                   | 2         | 1.32%   |
| Lecherias                  | 2         | 1.32%   |
| Ciudad Guayana             | 2         | 1.32%   |
| Anaco                      | 2         | 1.32%   |
| Tucape                     | 1         | 0.66%   |
| San Juan Bautista          | 1         | 0.66%   |
| San Felipe                 | 1         | 0.66%   |
| San Diego                  | 1         | 0.66%   |
| San Antonio de Los Altos   | 1         | 0.66%   |
| Punto Fijo                 | 1         | 0.66%   |
| Puerto Ordaz and San Felix | 1         | 0.66%   |
| Puerto Cumarebo            | 1         | 0.66%   |
| Puerto Cruz                | 1         | 0.66%   |
| Parroquia El Recreo        | 1         | 0.66%   |
| Naguanagua                 | 1         | 0.66%   |
| Mariara                    | 1         | 0.66%   |
| Los Teques                 | 1         | 0.66%   |
| Los Palos Grandes          | 1         | 0.66%   |
| Las Vegas                  | 1         | 0.66%   |
| Guatire                    | 1         | 0.66%   |
| Guarenas                   | 1         | 0.66%   |
| Guanare                    | 1         | 0.66%   |
| El Hatillo Municipality    | 1         | 0.66%   |
| Ejido                      | 1         | 0.66%   |
| Ciudad Bolívar            | 1         | 0.66%   |
| Charallave                 | 1         | 0.66%   |
| Cagua                      | 1         | 0.66%   |
| Cabudare                   | 1         | 0.66%   |
| Barinas                    | 1         | 0.66%   |
| Acarigua                   | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 34     | 19.05%  |
| WDC                 | 28        | 38     | 16.67%  |
| Toshiba             | 16        | 17     | 9.52%   |
| Unknown             | 11        | 15     | 6.55%   |
| Samsung Electronics | 11        | 11     | 6.55%   |
| Hitachi             | 9         | 9      | 5.36%   |
| SanDisk             | 6         | 9      | 3.57%   |
| Intel               | 6         | 9      | 3.57%   |
| Crucial             | 5         | 7      | 2.98%   |
| SK hynix            | 4         | 5      | 2.38%   |
| LITEONIT            | 4         | 8      | 2.38%   |
| Kingston            | 4         | 6      | 2.38%   |
| HGST                | 4         | 4      | 2.38%   |
| SPCC                | 3         | 5      | 1.79%   |
| PNY                 | 3         | 3      | 1.79%   |
| Team                | 2         | 2      | 1.19%   |
| Silicon Motion      | 2         | 2      | 1.19%   |
| Micron Technology   | 2         | 5      | 1.19%   |
| HUAWEI              | 2         | 2      | 1.19%   |
| Fujitsu             | 2         | 2      | 1.19%   |
| BIWIN               | 2         | 3      | 1.19%   |
| addlink             | 2         | 2      | 1.19%   |
| Vaseky              | 1         | 1      | 0.6%    |
| PUSKILL             | 1         | 1      | 0.6%    |
| Phison              | 1         | 1      | 0.6%    |
| Lexar               | 1         | 1      | 0.6%    |
| KingFast            | 1         | 3      | 0.6%    |
| Intenso             | 1         | 1      | 0.6%    |
| Dell                | 1         | 2      | 0.6%    |
| Apacer              | 1         | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB     | 4         | 2.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 1.74%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 1.74%   |
| Unknown NVMe SSD Drive 512GB        | 3         | 1.74%   |
| Seagate ST320LT012-9WS14C 320GB     | 3         | 1.74%   |
| Seagate ST320LT012-1DG14C 320GB     | 3         | 1.74%   |
| Seagate ST250LM004 HN-M250MBB 250GB | 3         | 1.74%   |
| LITEONIT LMS-32L6M 32GB SSD         | 3         | 1.74%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 1.16%   |
| WDC WD5000LPVT-08G33T1 500GB        | 2         | 1.16%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2         | 1.16%   |
| WDC WD1200BEVS-60UST0 120GB         | 2         | 1.16%   |
| Unknown MMC Card  16GB              | 2         | 1.16%   |
| Toshiba MQ04ABF100 1TB              | 2         | 1.16%   |
| Toshiba MQ01ABF050 500GB            | 2         | 1.16%   |
| Toshiba MQ01ABF032 320GB            | 2         | 1.16%   |
| Toshiba MQ01ABD050 500GB            | 2         | 1.16%   |
| Toshiba MK3275GSX 320GB             | 2         | 1.16%   |
| SK hynix HFM001TD3JX013N 1024GB     | 2         | 1.16%   |
| Seagate ST9320325AS 320GB           | 2         | 1.16%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 2         | 1.16%   |
| Seagate ST320LM000 HM321HI 320GB    | 2         | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 1.16%   |
| SanDisk NVMe SSD Drive 1TB          | 2         | 1.16%   |
| PNY CS900 1TB SSD                   | 2         | 1.16%   |
| HUAWEI SD Storage 128GB             | 2         | 1.16%   |
| Hitachi HTS725050A9A364 500GB       | 2         | 1.16%   |
| HGST HTS721010A9E630 1TB            | 2         | 1.16%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 1.16%   |
| WDC WDS500G2B0C-00PXH0 500GB        | 1         | 0.58%   |
| WDC WD5000BPVT-24HXZT3 500GB        | 1         | 0.58%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 0.58%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 1         | 0.58%   |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 0.58%   |
| WDC WD3200BEVT-08A23T1 320GB        | 1         | 0.58%   |
| WDC WD3200BEVT-00A0RT0 320GB        | 1         | 0.58%   |
| WDC WD3200BEKT-60F3T1 320GB         | 1         | 0.58%   |
| WDC WD1600BEVT-88ZCT0 160GB         | 1         | 0.58%   |
| WDC WD1600BEVT-60ZCT1 160GB         | 1         | 0.58%   |
| WDC WD1600BEVS-22RST0 160GB         | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 31     | 32.58%  |
| WDC                 | 26        | 33     | 29.21%  |
| Toshiba             | 15        | 16     | 16.85%  |
| Hitachi             | 9         | 9      | 10.11%  |
| HGST                | 4         | 4      | 4.49%   |
| Unknown             | 2         | 2      | 2.25%   |
| Samsung Electronics | 2         | 2      | 2.25%   |
| Fujitsu             | 2         | 2      | 2.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 13.89%  |
| Crucial             | 5         | 7      | 13.89%  |
| LITEONIT            | 4         | 8      | 11.11%  |
| PNY                 | 3         | 3      | 8.33%   |
| Kingston            | 3         | 5      | 8.33%   |
| SPCC                | 2         | 3      | 5.56%   |
| SanDisk             | 2         | 3      | 5.56%   |
| Vaseky              | 1         | 1      | 2.78%   |
| Toshiba             | 1         | 1      | 2.78%   |
| Team                | 1         | 1      | 2.78%   |
| PUSKILL             | 1         | 1      | 2.78%   |
| Micron Technology   | 1         | 3      | 2.78%   |
| Lexar               | 1         | 1      | 2.78%   |
| KingFast            | 1         | 3      | 2.78%   |
| Intenso             | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| Dell                | 1         | 2      | 2.78%   |
| BIWIN               | 1         | 2      | 2.78%   |
| addlink             | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 87        | 99     | 53.7%   |
| SSD     | 35        | 52     | 21.6%   |
| NVMe    | 28        | 43     | 17.28%  |
| MMC     | 7         | 10     | 4.32%   |
| Unknown | 5         | 5      | 3.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 112       | 149    | 72.73%  |
| NVMe | 28        | 43     | 18.18%  |
| SAS  | 7         | 7      | 4.55%   |
| MMC  | 7         | 10     | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 96        | 121    | 80.67%  |
| 0.51-1.0   | 22        | 29     | 18.49%  |
| 1.01-2.0   | 1         | 1      | 0.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 44        | 29.53%  |
| 101-250        | 37        | 24.83%  |
| 501-1000       | 24        | 16.11%  |
| 1-20           | 16        | 10.74%  |
| 21-50          | 10        | 6.71%   |
| 51-100         | 10        | 6.71%   |
| 1001-2000      | 4         | 2.68%   |
| 2001-3000      | 2         | 1.34%   |
| More than 3000 | 1         | 0.67%   |
| Unknown        | 1         | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 56        | 36.13%  |
| 21-50     | 31        | 20%     |
| 101-250   | 26        | 16.77%  |
| 51-100    | 20        | 12.9%   |
| 251-500   | 13        | 8.39%   |
| 501-1000  | 7         | 4.52%   |
| 2001-3000 | 1         | 0.65%   |
| Unknown   | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD1200BEVS-60UST0 120GB          | 2         | 2      | 8.33%   |
| Hitachi HTS725050A9A364 500GB        | 2         | 2      | 8.33%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 1      | 4.17%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 4.17%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2      | 4.17%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 4.17%   |
| Toshiba MK3275GSX 320GB              | 1         | 1      | 4.17%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 4.17%   |
| Seagate ST9320325AS 320GB            | 1         | 1      | 4.17%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 4.17%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 4.17%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 4.17%   |
| Samsung Electronics HN-M320MBB 320GB | 1         | 1      | 4.17%   |
| Samsung Electronics HM250HI 250GB    | 1         | 1      | 4.17%   |
| Intel SSDPEKKW256G7 256GB            | 1         | 1      | 4.17%   |
| Intel SSDPEKKF512G7L 512GB           | 1         | 1      | 4.17%   |
| Hitachi HTS543232L9A300 320GB        | 1         | 1      | 4.17%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1      | 4.17%   |
| Hitachi HTS542525K9SA00 250GB        | 1         | 1      | 4.17%   |
| HGST HTS545050A7E380 500GB           | 1         | 1      | 4.17%   |
| HGST HTS541010A7E630 1TB             | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 6      | 20.83%  |
| Seagate             | 5         | 5      | 20.83%  |
| Hitachi             | 5         | 5      | 20.83%  |
| Toshiba             | 3         | 3      | 12.5%   |
| Samsung Electronics | 2         | 2      | 8.33%   |
| Intel               | 2         | 2      | 8.33%   |
| HGST                | 2         | 2      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 6      | 22.73%  |
| Seagate             | 5         | 5      | 22.73%  |
| Hitachi             | 5         | 5      | 22.73%  |
| Toshiba             | 3         | 3      | 13.64%  |
| Samsung Electronics | 2         | 2      | 9.09%   |
| HGST                | 2         | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 23     | 91.67%  |
| NVMe | 2         | 2      | 8.33%   |

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
| Detected | 79        | 116    | 52.67%  |
| Works    | 47        | 68     | 31.33%  |
| Malfunc  | 24        | 25     | 16%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 110       | 71.43%  |
| AMD                         | 20        | 12.99%  |
| SanDisk                     | 5         | 3.25%   |
| SK hynix                    | 4         | 2.6%    |
| Samsung Electronics         | 4         | 2.6%    |
| Silicon Motion              | 3         | 1.95%   |
| Phison Electronics          | 3         | 1.95%   |
| Jiangsu Huacun Elec.        | 3         | 1.95%   |
| Micron Technology           | 1         | 0.65%   |
| Kingston Technology Company | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 12.35%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 10%     |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 6.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 5.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 8         | 4.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 4.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 4.71%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 6         | 3.53%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 2.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 2.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 1.76%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.76%   |
| Jiangsu Huacun Elec. Non-Volatile memory controller                            | 3         | 1.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.76%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 1.18%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 1.18%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 1.18%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.18%   |
| Intel SSD 600P Series                                                          | 2         | 1.18%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.18%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.18%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 2         | 1.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 1.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.18%   |
| SK hynix BC511                                                                 | 1         | 0.59%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.59%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 0.59%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 0.59%   |
| Phison Electronics Non-Volatile memory controller                              | 1         | 0.59%   |
| Micron NVMe Storage Controller                                                 | 1         | 0.59%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.59%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.59%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 104       | 63.41%  |
| NVMe | 28        | 17.07%  |
| IDE  | 17        | 10.37%  |
| RAID | 15        | 9.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 115       | 82.14%  |
| AMD          | 22        | 15.71%  |
| CentaurHauls | 3         | 2.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz                | 6         | 4.29%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 4         | 2.86%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 4         | 2.86%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 3         | 2.14%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 3         | 2.14%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 3         | 2.14%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 3         | 2.14%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 3         | 2.14%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 1.43%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 2         | 1.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 2         | 1.43%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 2         | 1.43%   |
| Intel Core i5-3337U CPU @ 1.80GHz              | 2         | 1.43%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 1.43%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 2         | 1.43%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 2         | 1.43%   |
| Intel Core i3-4000M CPU @ 2.40GHz              | 2         | 1.43%   |
| Intel Core i3-2350M CPU @ 2.30GHz              | 2         | 1.43%   |
| Intel Core i3 CPU M 330 @ 2.13GHz              | 2         | 1.43%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz           | 2         | 1.43%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz           | 2         | 1.43%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 2         | 1.43%   |
| Intel Celeron CPU N2805 @ 1.46GHz              | 2         | 1.43%   |
| Intel Atom CPU N570 @ 1.66GHz                  | 2         | 1.43%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 2         | 1.43%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 1.43%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 2         | 1.43%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 2         | 1.43%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 2         | 1.43%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 0.71%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz         | 1         | 0.71%   |
| Intel Pentium CPU 6405U @ 2.40GHz              | 1         | 0.71%   |
| Intel Pentium CPU 2030M @ 2.50GHz              | 1         | 0.71%   |
| Intel Genuine CPU U7300 @ 1.30GHz              | 1         | 0.71%   |
| Intel Genuine CPU T2080 @ 1.73GHz              | 1         | 0.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 1         | 0.71%   |
| Intel Core i7-7820HK CPU @ 2.90GHz             | 1         | 0.71%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz             | 1         | 0.71%   |
| Intel Core i7-5600U CPU @ 2.60GHz              | 1         | 0.71%   |
| Intel Core i7-4500U CPU @ 1.80GHz              | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 23        | 16.43%  |
| Intel Core i3                  | 22        | 15.71%  |
| Intel Celeron                  | 15        | 10.71%  |
| Intel Core 2 Duo               | 14        | 10%     |
| Intel Core i7                  | 13        | 9.29%   |
| Other                          | 10        | 7.14%   |
| Intel Atom                     | 9         | 6.43%   |
| AMD Ryzen 5                    | 7         | 5%      |
| Intel Pentium                  | 5         | 3.57%   |
| AMD Ryzen 7                    | 4         | 2.86%   |
| Intel Pentium Dual             | 3         | 2.14%   |
| Intel Pentium Dual-Core        | 2         | 1.43%   |
| Intel Genuine                  | 2         | 1.43%   |
| AMD A10                        | 2         | 1.43%   |
| Intel Pentium Silver           | 1         | 0.71%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.71%   |
| AMD Ryzen 3                    | 1         | 0.71%   |
| AMD Quad-Core                  | 1         | 0.71%   |
| AMD Mobile Sempron             | 1         | 0.71%   |
| AMD E1                         | 1         | 0.71%   |
| AMD E                          | 1         | 0.71%   |
| AMD C-70                       | 1         | 0.71%   |
| AMD A6                         | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 96        | 68.57%  |
| 4       | 22        | 15.71%  |
| 6       | 7         | 5%      |
| 1       | 7         | 5%      |
| 8       | 5         | 3.57%   |
| Unknown | 2         | 1.43%   |
| 14      | 1         | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 140       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 85        | 60.71%  |
| 1       | 53        | 37.86%  |
| Unknown | 2         | 1.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 134       | 95.71%  |
| 64-bit         | 3         | 2.14%   |
| 32-bit         | 3         | 2.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 23.81%  |
| 0x306a9    | 15        | 10.2%   |
| 0x206a7    | 15        | 10.2%   |
| 0x1067a    | 11        | 7.48%   |
| 0x6fd      | 7         | 4.76%   |
| 0x806e9    | 5         | 3.4%    |
| 0x106ca    | 5         | 3.4%    |
| 0x30678    | 4         | 2.72%   |
| 0x20655    | 4         | 2.72%   |
| 0x806c1    | 3         | 2.04%   |
| 0x40651    | 3         | 2.04%   |
| 0x806ec    | 2         | 1.36%   |
| 0x806d1    | 2         | 1.36%   |
| 0x406e3    | 2         | 1.36%   |
| 0x306d4    | 2         | 1.36%   |
| 0x306c3    | 2         | 1.36%   |
| 0x30673    | 2         | 1.36%   |
| 0x08608103 | 2         | 1.36%   |
| 0x08108102 | 2         | 1.36%   |
| 0x05000119 | 2         | 1.36%   |
| 0x906ea    | 1         | 0.68%   |
| 0x906e9    | 1         | 0.68%   |
| 0x806ea    | 1         | 0.68%   |
| 0x706e5    | 1         | 0.68%   |
| 0x706a8    | 1         | 0.68%   |
| 0x6ec      | 1         | 0.68%   |
| 0x506e3    | 1         | 0.68%   |
| 0x406c4    | 1         | 0.68%   |
| 0x30661    | 1         | 0.68%   |
| 0x20652    | 1         | 0.68%   |
| 0x106c2    | 1         | 0.68%   |
| 0x08600104 | 1         | 0.68%   |
| 0x08600103 | 1         | 0.68%   |
| 0x08600102 | 1         | 0.68%   |
| 0x0810100b | 1         | 0.68%   |
| 0x08101007 | 1         | 0.68%   |
| 0x06006705 | 1         | 0.68%   |
| 0x06006704 | 1         | 0.68%   |
| 0x06006118 | 1         | 0.68%   |
| 0x06003106 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 19        | 13.57%  |
| IvyBridge        | 17        | 12.14%  |
| KabyLake         | 12        | 8.57%   |
| Penryn           | 10        | 7.14%   |
| Core             | 10        | 7.14%   |
| Westmere         | 9         | 6.43%   |
| Bonnell          | 8         | 5.71%   |
| Silvermont       | 7         | 5%      |
| Unknown          | 7         | 5%      |
| Haswell          | 5         | 3.57%   |
| Zen+             | 3         | 2.14%   |
| Zen 2            | 3         | 2.14%   |
| TigerLake        | 3         | 2.14%   |
| Skylake          | 3         | 2.14%   |
| Icelake          | 3         | 2.14%   |
| Excavator        | 3         | 2.14%   |
| Broadwell        | 3         | 2.14%   |
| Bobcat           | 3         | 2.14%   |
| Zen              | 2         | 1.43%   |
| Goldmont plus    | 2         | 1.43%   |
| Steamroller      | 1         | 0.71%   |
| P6               | 1         | 0.71%   |
| K8 Hammer        | 1         | 0.71%   |
| K8 & K10 hybrid  | 1         | 0.71%   |
| Jaguar           | 1         | 0.71%   |
| Goldmont         | 1         | 0.71%   |
| CometLake        | 1         | 0.71%   |
| Alderlake Hybrid | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 111       | 74%     |
| AMD     | 23        | 15.33%  |
| Nvidia  | 13        | 8.67%   |
| Zhaoxin | 3         | 2%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 18        | 11.18%  |
| Intel 3rd Gen Core processor Graphics Controller                              | 16        | 9.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 10        | 6.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 9         | 5.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 9         | 5.59%   |
| Intel Core Processor Integrated Graphics Controller                           | 9         | 5.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 6         | 3.73%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 6         | 3.73%   |
| Intel HD Graphics 620                                                         | 4         | 2.48%   |
| AMD Lucienne                                                                  | 4         | 2.48%   |
| Zhaoxin ZX-E C-960 GPU                                                        | 3         | 1.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 1.86%   |
| Intel HD Graphics 5500                                                        | 3         | 1.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 1.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.86%   |
| Nvidia TU117M                                                                 | 2         | 1.24%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 1.24%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 1.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 1.24%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 1.24%   |
| Intel HD Graphics 630                                                         | 2         | 1.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 1.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 1.24%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 2         | 1.24%   |
| AMD Renoir                                                                    | 2         | 1.24%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.62%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 0.62%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.62%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                      | 1         | 0.62%   |
| Nvidia GM204GLM [Quadro M3000M]                                               | 1         | 0.62%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 0.62%   |
| Nvidia GF104GLM [Quadro 3000M]                                                | 1         | 0.62%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 1         | 0.62%   |
| Intel UHD Graphics 620                                                        | 1         | 0.62%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.62%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 0.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 0.62%   |
| Intel HD Graphics 615                                                         | 1         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 100       | 71.43%  |
| 1 x AMD        | 21        | 15%     |
| Intel + Nvidia | 7         | 5%      |
| 1 x Nvidia     | 5         | 3.57%   |
| 1 x Zhaoxin    | 3         | 2.14%   |
| 2 x Intel      | 2         | 1.43%   |
| Intel + AMD    | 1         | 0.71%   |
| AMD + Nvidia   | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 127       | 90.07%  |
| Proprietary | 8         | 5.67%   |
| Unknown     | 6         | 4.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 79.58%  |
| 0.01-0.5   | 15        | 10.56%  |
| 1.01-2.0   | 6         | 4.23%   |
| 3.01-4.0   | 3         | 2.11%   |
| 0.51-1.0   | 3         | 2.11%   |
| 5.01-6.0   | 2         | 1.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 24        | 15.79%  |
| Samsung Electronics     | 23        | 15.13%  |
| AU Optronics            | 23        | 15.13%  |
| LG Display              | 20        | 13.16%  |
| Chimei Innolux          | 15        | 9.87%   |
| Chi Mei Optoelectronics | 7         | 4.61%   |
| Lenovo                  | 6         | 3.95%   |
| LG Philips              | 5         | 3.29%   |
| InfoVision              | 5         | 3.29%   |
| Hewlett-Packard         | 4         | 2.63%   |
| HannStar                | 4         | 2.63%   |
| Goldstar                | 3         | 1.97%   |
| PANDA                   | 2         | 1.32%   |
| Dell                    | 2         | 1.32%   |
| Vizio                   | 1         | 0.66%   |
| ViewSonic               | 1         | 0.66%   |
| Sharp                   | 1         | 0.66%   |
| Sceptre Tech            | 1         | 0.66%   |
| MStar                   | 1         | 0.66%   |
| KTC                     | 1         | 0.66%   |
| InnoLux Display         | 1         | 0.66%   |
| ASUSTek Computer        | 1         | 0.66%   |
| Acer                    | 1         | 0.66%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 5         | 3.29%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch       | 5         | 3.29%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 3         | 1.97%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                  | 3         | 1.97%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch         | 3         | 1.97%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2         | 1.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 1.32%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.32%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 2         | 1.32%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 2         | 1.32%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 2         | 1.32%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch           | 2         | 1.32%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch           | 2         | 1.32%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                  | 2         | 1.32%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                  | 2         | 1.32%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                  | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO8294 1920x1080 382x215mm 17.3-inch        | 2         | 1.32%   |
| Vizio E3D320VX VIZ0079 1920x1080 698x393mm 31.5-inch                  | 1         | 0.66%   |
| ViewSonic VA2252 SERIES VSC7731 1920x1080 476x268mm 21.5-inch         | 1         | 0.66%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.66%   |
| Sceptre Tech Sceptre T24 SPT09AB 1920x1080 520x320mm 24.0-inch        | 1         | 0.66%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch     | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC4241 1280x800 261x163mm 12.1-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC8151 1920x1080 382x214mm 17.2-inch | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch  | 1         | 0.66%   |
| MStar Demo MST0030 1366x768 708x398mm 32.0-inch                       | 1         | 0.66%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch         | 1         | 0.66%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch         | 1         | 0.66%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 0.66%   |
| LG Philips LCD Monitor LPL0701 1280x800 331x207mm 15.4-inch           | 1         | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 76        | 53.9%   |
| 1920x1080 (FHD)   | 32        | 22.7%   |
| 1280x800 (WXGA)   | 14        | 9.93%   |
| 3840x2160 (4K)    | 3         | 2.13%   |
| 1600x900 (HD+)    | 3         | 2.13%   |
| 1360x768          | 3         | 2.13%   |
| 1024x600          | 3         | 2.13%   |
| 1920x1200 (WUXGA) | 2         | 1.42%   |
| 1440x900 (WXGA+)  | 2         | 1.42%   |
| 1280x1024 (SXGA)  | 2         | 1.42%   |
| 2560x1440 (QHD)   | 1         | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 54        | 35.76%  |
| 14      | 31        | 20.53%  |
| 13      | 24        | 15.89%  |
| 17      | 8         | 5.3%    |
| 21      | 6         | 3.97%   |
| 10      | 6         | 3.97%   |
| 11      | 5         | 3.31%   |
| 18      | 3         | 1.99%   |
| 32      | 2         | 1.32%   |
| 27      | 2         | 1.32%   |
| 23      | 2         | 1.32%   |
| 12      | 2         | 1.32%   |
| 54      | 1         | 0.66%   |
| 52      | 1         | 0.66%   |
| 31      | 1         | 0.66%   |
| 24      | 1         | 0.66%   |
| 19      | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 106       | 70.67%  |
| 201-300     | 15        | 10%     |
| 401-500     | 9         | 6%      |
| 351-400     | 9         | 6%      |
| 501-600     | 5         | 3.33%   |
| 701-800     | 2         | 1.33%   |
| 1001-1500   | 2         | 1.33%   |
| 601-700     | 1         | 0.67%   |
| Unknown     | 1         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 113       | 84.33%  |
| 16/10 | 18        | 13.43%  |
| 5/4   | 2         | 1.49%   |
| 3/2   | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 54        | 35.76%  |
| 81-90          | 53        | 35.1%   |
| 201-250        | 7         | 4.64%   |
| 121-130        | 7         | 4.64%   |
| 41-50          | 6         | 3.97%   |
| 51-60          | 5         | 3.31%   |
| 141-150        | 4         | 2.65%   |
| 351-500        | 3         | 1.99%   |
| More than 1000 | 2         | 1.32%   |
| 71-80          | 2         | 1.32%   |
| 61-70          | 2         | 1.32%   |
| 301-350        | 2         | 1.32%   |
| 151-200        | 2         | 1.32%   |
| 251-300        | 1         | 0.66%   |
| Unknown        | 1         | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 71        | 47.97%  |
| 121-160       | 42        | 28.38%  |
| 51-100        | 27        | 18.24%  |
| 1-50          | 4         | 2.7%    |
| 161-240       | 2         | 1.35%   |
| More than 240 | 1         | 0.68%   |
| Unknown       | 1         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 116       | 81.12%  |
| 2     | 20        | 13.99%  |
| 0     | 5         | 3.5%    |
| 3     | 2         | 1.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 94        | 40.34%  |
| Intel                           | 49        | 21.03%  |
| Qualcomm Atheros                | 46        | 19.74%  |
| Broadcom                        | 15        | 6.44%   |
| Broadcom Limited                | 5         | 2.15%   |
| Xiaomi                          | 3         | 1.29%   |
| TP-Link                         | 3         | 1.29%   |
| MediaTek                        | 3         | 1.29%   |
| Marvell Technology Group        | 3         | 1.29%   |
| Samsung Electronics             | 2         | 0.86%   |
| Qualcomm Atheros Communications | 2         | 0.86%   |
| JMicron Technology              | 2         | 0.86%   |
| ZyXEL Communications            | 1         | 0.43%   |
| Trendchip Technologies          | 1         | 0.43%   |
| Ralink Technology               | 1         | 0.43%   |
| Huawei Technologies             | 1         | 0.43%   |
| ASIX Electronics                | 1         | 0.43%   |
| AMD                             | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 49        | 18.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 21        | 7.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 4.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 3.69%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 2.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.58%   |
| Intel Wireless 7265                                                     | 7         | 2.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.21%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 6         | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.85%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 1.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.48%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.48%   |
| Intel Wireless 7260                                                     | 4         | 1.48%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 1.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.11%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.11%   |
| Intel WiFi Link 5100                                                    | 3         | 1.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.11%   |
| Intel Centrino Wireless-N 105                                           | 3         | 1.11%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.11%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1.11%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.74%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.74%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 0.74%   |
| Intel Wireless 8260                                                     | 2         | 0.74%   |
| Intel Wireless 3165                                                     | 2         | 0.74%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.74%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.74%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 33.57%  |
| Realtek Semiconductor           | 38        | 26.57%  |
| Qualcomm Atheros                | 34        | 23.78%  |
| Broadcom                        | 12        | 8.39%   |
| MediaTek                        | 3         | 2.1%    |
| TP-Link                         | 2         | 1.4%    |
| Qualcomm Atheros Communications | 2         | 1.4%    |
| Broadcom Limited                | 2         | 1.4%    |
| Xiaomi                          | 1         | 0.7%    |
| Ralink Technology               | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Notebooks | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 13        | 9.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 10        | 6.99%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                      | 8         | 5.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 7         | 4.9%    |
| Intel Wireless 7265                                                                  | 7         | 4.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 6         | 4.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 5         | 3.5%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                          | 4         | 2.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 4         | 2.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)              | 4         | 2.8%    |
| Intel Wireless 7260                                                                  | 4         | 2.8%    |
| Broadcom BCM4311 802.11b/g WLAN                                                      | 4         | 2.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 3         | 2.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 3         | 2.1%    |
| Intel Wireless 8265 / 8275                                                           | 3         | 2.1%    |
| Intel WiFi Link 5100                                                                 | 3         | 2.1%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                        | 3         | 2.1%    |
| Intel Centrino Wireless-N 105                                                        | 3         | 2.1%    |
| Intel Centrino Ultimate-N 6300                                                       | 3         | 2.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                  | 3         | 2.1%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                                    | 3         | 2.1%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 2         | 1.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 2         | 1.4%    |
| Intel Wireless 8260                                                                  | 2         | 1.4%    |
| Intel Wireless 3165                                                                  | 2         | 1.4%    |
| Intel Wi-Fi 6 AX201                                                                  | 2         | 1.4%    |
| Intel Wi-Fi 6 AX200                                                                  | 2         | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                    | 2         | 1.4%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                        | 2         | 1.4%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                         | 2         | 1.4%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                            | 2         | 1.4%    |
| Xiaomi MediaTek MT7601U [MI WiFi]                                                    | 1         | 0.7%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                          | 1         | 0.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                           | 1         | 0.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 1         | 0.7%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1         | 0.7%    |
| Realtek 802.11n WLAN Adapter                                                         | 1         | 0.7%    |
| Ralink MT7601U Wireless Adapter                                                      | 1         | 0.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1         | 0.7%    |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 76        | 61.79%  |
| Qualcomm Atheros         | 16        | 13.01%  |
| Intel                    | 13        | 10.57%  |
| Broadcom                 | 4         | 3.25%   |
| Marvell Technology Group | 3         | 2.44%   |
| Broadcom Limited         | 3         | 2.44%   |
| Xiaomi                   | 2         | 1.63%   |
| JMicron Technology       | 2         | 1.63%   |
| ZyXEL Communications     | 1         | 0.81%   |
| Trendchip Technologies   | 1         | 0.81%   |
| TP-Link                  | 1         | 0.81%   |
| ASIX Electronics         | 1         | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49        | 39.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 16.94%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 4.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 3.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.61%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 1.61%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 2         | 1.61%   |
| ZyXEL ADSL Modem Prestige 600 series                              | 1         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.81%   |
| Trendchip Ethernet controller                                     | 1         | 0.81%   |
| TP-Link M7200                                                     | 1         | 0.81%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.81%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.81%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.81%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.81%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.81%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.81%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.81%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 136       | 52.51%  |
| Ethernet | 119       | 45.95%  |
| Modem    | 4         | 1.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 109       | 74.15%  |
| Ethernet | 38        | 25.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 111       | 79.29%  |
| 1     | 27        | 19.29%  |
| 0     | 2         | 1.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 139       | 98.58%  |
| Yes  | 2         | 1.42%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 37.35%  |
| Qualcomm Atheros Communications | 13        | 15.66%  |
| Realtek Semiconductor           | 11        | 13.25%  |
| IMC Networks                    | 11        | 13.25%  |
| Broadcom                        | 6         | 7.23%   |
| Lite-On Technology              | 4         | 4.82%   |
| Cambridge Silicon Radio         | 3         | 3.61%   |
| Hewlett-Packard                 | 2         | 2.41%   |
| Dell                            | 1         | 1.2%    |
| ASUSTek Computer                | 1         | 1.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 18        | 21.69%  |
| Realtek Bluetooth Radio                                     | 6         | 7.23%   |
| Qualcomm Atheros  Bluetooth Device                          | 5         | 6.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 4.82%   |
| Intel AX201 Bluetooth                                       | 4         | 4.82%   |
| IMC Networks Bluetooth                                      | 4         | 4.82%   |
| Realtek RTL8723B Bluetooth                                  | 3         | 3.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 3.61%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 3         | 3.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 3         | 3.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 3.61%   |
| Broadcom BCM2045 Bluetooth                                  | 3         | 3.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 2.41%   |
| Intel AX200 Bluetooth                                       | 2         | 2.41%   |
| IMC Networks Wireless_Device                                | 2         | 2.41%   |
| IMC Networks Bluetooth Radio                                | 2         | 2.41%   |
| Realtek RTL8723A Bluetooth                                  | 1         | 1.2%    |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.2%    |
| Qualcomm Atheros Bluetooth (AR3011)                         | 1         | 1.2%    |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 1.2%    |
| Lite-On Wireless_Device                                     | 1         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.2%    |
| Lite-On Bluetooth Device                                    | 1         | 1.2%    |
| Lite-On BCM20702A0                                          | 1         | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.2%    |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 1.2%    |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.2%    |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 1.2%    |
| Broadcom HP Portable Valentine                              | 1         | 1.2%    |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.2%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.2%    |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 115       | 74.68%  |
| AMD                   | 23        | 14.94%  |
| Nvidia                | 10        | 6.49%   |
| Zhaoxin               | 3         | 1.95%   |
| Realtek Semiconductor | 1         | 0.65%   |
| Microsoft             | 1         | 0.65%   |
| Logitech              | 1         | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25        | 13.51%  |
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 6.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 5.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 5.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9         | 4.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 9         | 4.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 4.86%   |
| Intel Sunrise Point-LP HD Audio                                            | 8         | 4.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 3.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.7%    |
| AMD FCH Azalia Controller                                                  | 5         | 2.7%    |
| Zhaoxin ZX-E High Definition Audio Controller                              | 3         | 1.62%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller   | 3         | 1.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.62%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.62%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.62%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.62%   |
| AMD Wrestler HDMI Audio                                                    | 3         | 1.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.08%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.08%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.08%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.08%   |
| AMD High Definition Audio Controller                                       | 2         | 1.08%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.54%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.54%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.54%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.54%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.54%   |
| Nvidia GF104 High Definition Audio Controller                              | 1         | 0.54%   |
| Nvidia Audio device                                                        | 1         | 0.54%   |
| Microsoft LifeChat LX-4000                                                 | 1         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 25        | 21.93%  |
| Samsung Electronics | 19        | 16.67%  |
| Unknown             | 16        | 14.04%  |
| Ramaxel Technology  | 12        | 10.53%  |
| Micron Technology   | 11        | 9.65%   |
| Kingston            | 6         | 5.26%   |
| Crucial             | 5         | 4.39%   |
| Elpida              | 4         | 3.51%   |
| Unknown (ABCD)      | 2         | 1.75%   |
| Shenzhen WODPOSIT   | 2         | 1.75%   |
| Qimonda             | 2         | 1.75%   |
| Unknown             | 2         | 1.75%   |
| Unknown (081A)      | 1         | 0.88%   |
| Unknown (07F7)      | 1         | 0.88%   |
| Team                | 1         | 0.88%   |
| Memox               | 1         | 0.88%   |
| Gold Key            | 1         | 0.88%   |
| Corsair             | 1         | 0.88%   |
| A-DATA Technology   | 1         | 0.88%   |
| <Invalid>           | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 4         | 3.31%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 3         | 2.48%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s           | 3         | 2.48%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s           | 3         | 2.48%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s           | 3         | 2.48%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                        | 2         | 1.65%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s              | 2         | 1.65%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s            | 2         | 1.65%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s            | 2         | 1.65%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 2         | 1.65%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s           | 2         | 1.65%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s             | 2         | 1.65%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s             | 2         | 1.65%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s           | 2         | 1.65%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s              | 2         | 1.65%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s            | 2         | 1.65%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM 1334MT/s                  | 2         | 1.65%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s           | 2         | 1.65%   |
| Unknown                                                           | 2         | 1.65%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                    | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                    | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM SDRAM                               | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR2                                | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                         | 1         | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                    | 1         | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 1         | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR2                             | 1         | 0.83%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2667MT/s                   | 1         | 0.83%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                     | 1         | 0.83%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s  | 1         | 0.83%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s    | 1         | 0.83%   |
| Unknown (081A) RAM HXMSH2GS03A2F1CL16 2GB SODIMM DDR3 1600MT/s    | 1         | 0.83%   |
| Unknown (07F7) RAM CMB6-5FAA1BAR01B00 4096MB SODIMM DDR4 2667MT/s | 1         | 0.83%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s             | 1         | 0.83%   |
| SK hynix RAM HMT451S6BFR8A-RD 4GB SODIMM DDR3 1867MT/s            | 1         | 0.83%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.83%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s            | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 33        | 37.08%  |
| DDR3   | 32        | 35.96%  |
| DDR2   | 15        | 16.85%  |
| SDRAM  | 5         | 5.62%   |
| LPDDR4 | 3         | 3.37%   |
| DDR    | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 83        | 95.4%   |
| Row Of Chips | 3         | 3.45%   |
| DIMM         | 1         | 1.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 32        | 31.37%  |
| 2048  | 32        | 31.37%  |
| 4096  | 26        | 25.49%  |
| 1024  | 6         | 5.88%   |
| 16384 | 5         | 4.9%    |
| 32768 | 1         | 0.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 26%     |
| 2667    | 14        | 14%     |
| 3200    | 13        | 13%     |
| 667     | 8         | 8%      |
| 2400    | 7         | 7%      |
| 1333    | 5         | 5%      |
| 1334    | 4         | 4%      |
| 2666    | 3         | 3%      |
| 533     | 3         | 3%      |
| Unknown | 3         | 3%      |
| 4199    | 2         | 2%      |
| 2048    | 2         | 2%      |
| 1067    | 2         | 2%      |
| 975     | 2         | 2%      |
| 800     | 2         | 2%      |
| 3266    | 1         | 1%      |
| 2133    | 1         | 1%      |
| 1867    | 1         | 1%      |
| 1066    | 1         | 1%      |

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
| Chicony Electronics                    | 24        | 21.62%  |
| Microdia                               | 15        | 13.51%  |
| Realtek Semiconductor                  | 9         | 8.11%   |
| IMC Networks                           | 9         | 8.11%   |
| Bison Electronics                      | 9         | 8.11%   |
| Suyin                                  | 7         | 6.31%   |
| Acer                                   | 5         | 4.5%    |
| Syntek                                 | 4         | 3.6%    |
| Sunplus Innovation Technology          | 4         | 3.6%    |
| Quanta                                 | 4         | 3.6%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.6%    |
| Ricoh                                  | 3         | 2.7%    |
| ALi                                    | 3         | 2.7%    |
| Sonix Technology                       | 2         | 1.8%    |
| Lite-On Technology                     | 2         | 1.8%    |
| Tobii Technology AB                    | 1         | 0.9%    |
| Silicon Motion                         | 1         | 0.9%    |
| Luxvisions Innotech Limited            | 1         | 0.9%    |
| Lenovo                                 | 1         | 0.9%    |
| Importek                               | 1         | 0.9%    |
| icSpring                               | 1         | 0.9%    |
| Apple                                  | 1         | 0.9%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                        | 6         | 5.41%   |
| Microdia USB 2.0 Camera                                       | 5         | 4.5%    |
| Bison HD Webcam                                               | 5         | 4.5%    |
| Realtek Integrated_Webcam_HD                                  | 4         | 3.6%    |
| Chicony Lenovo EasyCamera                                     | 4         | 3.6%    |
| Chicony Integrated Camera                                     | 4         | 3.6%    |
| IMC Networks XHC Camera                                       | 3         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 3         | 2.7%    |
| Suyin Integrated_Webcam_HD                                    | 2         | 1.8%    |
| Suyin HP Webcam 101                                           | 2         | 1.8%    |
| Sunplus Integrated_Webcam_HD                                  | 2         | 1.8%    |
| Sonix USB2.0 HD UVC WebCam                                    | 2         | 1.8%    |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 2         | 1.8%    |
| Microdia Integrated_Webcam_HD                                 | 2         | 1.8%    |
| Microdia Integrated_Webcam_1.3M                               | 2         | 1.8%    |
| IMC Networks Lenovo EasyCamera                                | 2         | 1.8%    |
| Chicony HD WebCam                                             | 2         | 1.8%    |
| ALi WebCam                                                    | 2         | 1.8%    |
| Acer USB Camera                                               | 2         | 1.8%    |
| Tobii AB EyeChip                                              | 1         | 0.9%    |
| Syntek USB Camera Device                                      | 1         | 0.9%    |
| Syntek Integrated Webcam                                      | 1         | 0.9%    |
| Syntek Integrated Camera                                      | 1         | 0.9%    |
| Syntek EasyCamera                                             | 1         | 0.9%    |
| Suyin USB2.0 UVC 1.3M WebCam                                  | 1         | 0.9%    |
| Suyin HD Video WebCam                                         | 1         | 0.9%    |
| Suyin Acer CrystalEye Webcam                                  | 1         | 0.9%    |
| Sunplus MTD Camera                                            | 1         | 0.9%    |
| Sunplus Lenovo EasyCamera                                     | 1         | 0.9%    |
| Silicon Motion WebCam SC-10HDD13335N                          | 1         | 0.9%    |
| Ricoh Sony Vaio Integrated Webcam                             | 1         | 0.9%    |
| Realtek USB2.0 camera                                         | 1         | 0.9%    |
| Realtek USB Camera                                            | 1         | 0.9%    |
| Realtek Integrated Webcam HD                                  | 1         | 0.9%    |
| Realtek Integrated Webcam                                     | 1         | 0.9%    |
| Realtek EasyCamera                                            | 1         | 0.9%    |
| Quanta VGA WebCam                                             | 1         | 0.9%    |
| Quanta HP Webcam                                              | 1         | 0.9%    |
| Quanta HD User Facing                                         | 1         | 0.9%    |
| Quanta ACER HD User Facing                                    | 1         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 46.67%  |
| AuthenTec                  | 3         | 20%     |
| Upek                       | 1         | 6.67%   |
| Synaptics                  | 1         | 6.67%   |
| Shenzhen Goodix Technology | 1         | 6.67%   |
| Futronic Technology        | 1         | 6.67%   |
| Elan Microelectronics      | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 13.33%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 13.33%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                   | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 6.67%   |
| Futronic Fingerprint Scanner Model FS88                | 1         | 6.67%   |
| Elan ELAN:ARM-M4                                       | 1         | 6.67%   |
| AuthenTec AES1600                                      | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 80%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 40%     |
| Broadcom 5880                                  | 2         | 40%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 103       | 72.54%  |
| 1     | 29        | 20.42%  |
| 2     | 9         | 6.34%   |
| 4     | 1         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 17        | 33.33%  |
| Fingerprint reader       | 15        | 29.41%  |
| Net/wireless             | 5         | 9.8%    |
| Chipcard                 | 5         | 9.8%    |
| Sound                    | 4         | 7.84%   |
| Camera                   | 3         | 5.88%   |
| Storage                  | 1         | 1.96%   |
| Communication controller | 1         | 1.96%   |

