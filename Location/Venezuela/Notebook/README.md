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

Total: 195

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Debian 11                    | 12        | 8.63%   |
| Ubuntu 20.04                 | 10        | 7.19%   |
| Ubuntu 22.04                 | 8         | 5.76%   |
| OpenMandriva 4.3             | 8         | 5.76%   |
| Debian 10                    | 6         | 4.32%   |
| Ubuntu 18.04                 | 5         | 3.6%    |
| KDE neon 20.04               | 5         | 3.6%    |
| Kubuntu 20.04                | 4         | 2.88%   |
| Zorin 16                     | 3         | 2.16%   |
| Xubuntu 18.04                | 3         | 2.16%   |
| ROSA R9                      | 3         | 2.16%   |
| OpenMandriva 4.2             | 3         | 2.16%   |
| Linux Mint 20.3              | 3         | 2.16%   |
| Zorin 15                     | 2         | 1.44%   |
| Xubuntu 22.04                | 2         | 1.44%   |
| Ubuntu Unity 16.04           | 2         | 1.44%   |
| Ubuntu 21.10                 | 2         | 1.44%   |
| Ubuntu 19.10                 | 2         | 1.44%   |
| Pop!_OS 22.04                | 2         | 1.44%   |
| Pop!_OS 21.04                | 2         | 1.44%   |
| OpenMandriva 23.01           | 2         | 1.44%   |
| Manjaro                      | 2         | 1.44%   |
| Linux Mint 20                | 2         | 1.44%   |
| Fedora 37                    | 2         | 1.44%   |
| Fedora 36                    | 2         | 1.44%   |
| Fedora 35                    | 2         | 1.44%   |
| ArcoLinux Rolling            | 2         | 1.44%   |
| Xubuntu 21.10                | 1         | 0.72%   |
| Xubuntu 20.04                | 1         | 0.72%   |
| Ubuntu MATE 20.04            | 1         | 0.72%   |
| Ubuntu MATE 19.10            | 1         | 0.72%   |
| Ubuntu 16.04                 | 1         | 0.72%   |
| Solus 4.1                    | 1         | 0.72%   |
| ROSA R11                     | 1         | 0.72%   |
| Q4OS 4                       | 1         | 0.72%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.72%   |
| OpenMandriva 4.50            | 1         | 0.72%   |
| MX 20                        | 1         | 0.72%   |
| Manjaro 21.2.0               | 1         | 0.72%   |
| Manjaro 21.1.0               | 1         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 26        | 19.4%   |
| Debian       | 18        | 13.43%  |
| OpenMandriva | 14        | 10.45%  |
| Linux Mint   | 8         | 5.97%   |
| Xubuntu      | 7         | 5.22%   |
| KDE neon     | 7         | 5.22%   |
| Fedora       | 7         | 5.22%   |
| Manjaro      | 6         | 4.48%   |
| Zorin        | 5         | 3.73%   |
| Kubuntu      | 5         | 3.73%   |
| ROSA         | 4         | 2.99%   |
| Pop!_OS      | 4         | 2.99%   |
| Ubuntu Unity | 2         | 1.49%   |
| Ubuntu MATE  | 2         | 1.49%   |
| LMDE         | 2         | 1.49%   |
| ArcoLinux    | 2         | 1.49%   |
| Solus        | 1         | 0.75%   |
| Q4OS         | 1         | 0.75%   |
| openSUSE     | 1         | 0.75%   |
| MX           | 1         | 0.75%   |
| Lubuntu      | 1         | 0.75%   |
| Linux Lite   | 1         | 0.75%   |
| Kali         | 1         | 0.75%   |
| Garuda Linux | 1         | 0.75%   |
| Feren OS     | 1         | 0.75%   |
| Elementary   | 1         | 0.75%   |
| Deepin       | 1         | 0.75%   |
| BunsenLabs   | 1         | 0.75%   |
| Arch         | 1         | 0.75%   |
| Alpine       | 1         | 0.75%   |
| AlmaLinux    | 1         | 0.75%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 8         | 5.16%   |
| 5.4.0-42-generic                | 4         | 2.58%   |
| 5.15.0-46-generic               | 4         | 2.58%   |
| 5.4.0-73-generic                | 3         | 1.94%   |
| 5.4.0-52-generic                | 3         | 1.94%   |
| 5.3.0-40-generic                | 3         | 1.94%   |
| 5.15.0-56-generic               | 3         | 1.94%   |
| 5.13.0-39-generic               | 3         | 1.94%   |
| 5.10.14-desktop-1omv4002        | 3         | 1.94%   |
| 5.10.0-13-amd64                 | 3         | 1.94%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 3         | 1.94%   |
| 4.19.0-17-amd64                 | 3         | 1.94%   |
| 6.1.1-desktop-1omv2290          | 2         | 1.29%   |
| 5.4.0-89-generic                | 2         | 1.29%   |
| 5.4.0-77-generic                | 2         | 1.29%   |
| 5.4.0-48-generic                | 2         | 1.29%   |
| 5.4.0-107-generic               | 2         | 1.29%   |
| 5.19.0-2-amd64                  | 2         | 1.29%   |
| 5.15.0-60-generic               | 2         | 1.29%   |
| 5.15.0-48-generic               | 2         | 1.29%   |
| 5.15.0-43-generic               | 2         | 1.29%   |
| 5.11.0-37-generic               | 2         | 1.29%   |
| 5.10.0-18-amd64                 | 2         | 1.29%   |
| 5.10.0-11-amd64                 | 2         | 1.29%   |
| 5.10.0-10-amd64                 | 2         | 1.29%   |
| 5.0.0-37-generic                | 2         | 1.29%   |
| 6.2.0-060200-generic            | 1         | 0.65%   |
| 6.1.8-200.fc37.x86_64           | 1         | 0.65%   |
| 6.1.10-100.fc36.x86_64          | 1         | 0.65%   |
| 6.1.0-3-amd64                   | 1         | 0.65%   |
| 6.0.8-arch1-1                   | 1         | 0.65%   |
| 6.0.2-76060002-generic          | 1         | 0.65%   |
| 5.9.0-5-amd64                   | 1         | 0.65%   |
| 5.8.6-1-MANJARO                 | 1         | 0.65%   |
| 5.8.0-63-generic                | 1         | 0.65%   |
| 5.8.0-53-generic                | 1         | 0.65%   |
| 5.8.0-45-generic                | 1         | 0.65%   |
| 5.8.0-44-generic                | 1         | 0.65%   |
| 5.8.0-41-generic                | 1         | 0.65%   |
| 5.6.6-1-default                 | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 20        | 13.89%  |
| 5.15.0  | 18        | 12.5%   |
| 5.10.0  | 13        | 9.03%   |
| 5.13.0  | 10        | 6.94%   |
| 5.16.7  | 8         | 5.56%   |
| 4.19.0  | 8         | 5.56%   |
| 5.11.0  | 6         | 4.17%   |
| 5.3.0   | 5         | 3.47%   |
| 5.8.0   | 4         | 2.78%   |
| 4.15.0  | 4         | 2.78%   |
| 5.10.14 | 3         | 2.08%   |
| 4.9.20  | 3         | 2.08%   |
| 6.1.1   | 2         | 1.39%   |
| 5.19.0  | 2         | 1.39%   |
| 5.14.10 | 2         | 1.39%   |
| 5.0.0   | 2         | 1.39%   |
| 6.2.0   | 1         | 0.69%   |
| 6.1.8   | 1         | 0.69%   |
| 6.1.10  | 1         | 0.69%   |
| 6.1.0   | 1         | 0.69%   |
| 6.0.8   | 1         | 0.69%   |
| 6.0.2   | 1         | 0.69%   |
| 5.9.0   | 1         | 0.69%   |
| 5.8.6   | 1         | 0.69%   |
| 5.6.6   | 1         | 0.69%   |
| 5.6.18  | 1         | 0.69%   |
| 5.5.4   | 1         | 0.69%   |
| 5.4.83  | 1         | 0.69%   |
| 5.4.105 | 1         | 0.69%   |
| 5.18.0  | 1         | 0.69%   |
| 5.17.2  | 1         | 0.69%   |
| 5.17.15 | 1         | 0.69%   |
| 5.17.12 | 1         | 0.69%   |
| 5.17.11 | 1         | 0.69%   |
| 5.15.8  | 1         | 0.69%   |
| 5.15.65 | 1         | 0.69%   |
| 5.15.6  | 1         | 0.69%   |
| 5.15.46 | 1         | 0.69%   |
| 5.15.28 | 1         | 0.69%   |
| 5.15.2  | 1         | 0.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 25        | 17.61%  |
| 5.4     | 22        | 15.49%  |
| 5.10    | 19        | 13.38%  |
| 5.13    | 11        | 7.75%   |
| 5.16    | 8         | 5.63%   |
| 4.19    | 8         | 5.63%   |
| 5.11    | 6         | 4.23%   |
| 6.1     | 5         | 3.52%   |
| 5.8     | 5         | 3.52%   |
| 5.3     | 5         | 3.52%   |
| 5.17    | 4         | 2.82%   |
| 4.15    | 4         | 2.82%   |
| 4.9     | 3         | 2.11%   |
| 6.0     | 2         | 1.41%   |
| 5.6     | 2         | 1.41%   |
| 5.19    | 2         | 1.41%   |
| 5.14    | 2         | 1.41%   |
| 5.12    | 2         | 1.41%   |
| 5.0     | 2         | 1.41%   |
| 6.2     | 1         | 0.7%    |
| 5.9     | 1         | 0.7%    |
| 5.5     | 1         | 0.7%    |
| 5.18    | 1         | 0.7%    |
| 4.18    | 1         | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 117       | 91.41%  |
| i686   | 11        | 8.59%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 47        | 34.31%  |
| KDE5          | 30        | 21.9%   |
| XFCE          | 23        | 16.79%  |
| Unknown       | 9         | 6.57%   |
| X-Cinnamon    | 6         | 4.38%   |
| KDE           | 6         | 4.38%   |
| MATE          | 4         | 2.92%   |
| KDE4          | 3         | 2.19%   |
| Unity         | 2         | 1.46%   |
| Cinnamon      | 2         | 1.46%   |
| Pantheon      | 1         | 0.73%   |
| LXQt          | 1         | 0.73%   |
| GNOME Classic | 1         | 0.73%   |
| Deepin        | 1         | 0.73%   |
| Budgie        | 1         | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 114       | 87.69%  |
| Wayland | 15        | 11.54%  |
| Tty     | 1         | 0.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 49        | 36.03%  |
| SDDM    | 23        | 16.91%  |
| LightDM | 22        | 16.18%  |
| GDM     | 21        | 15.44%  |
| GDM3    | 15        | 11.03%  |
| TDM     | 3         | 2.21%   |
| KDM     | 3         | 2.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_VE   | 76        | 56.72%  |
| en_US   | 39        | 29.1%   |
| es_ES   | 9         | 6.72%   |
| Unknown | 7         | 5.22%   |
| es_US   | 1         | 0.75%   |
| es_MX   | 1         | 0.75%   |
| en_CA   | 1         | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 84        | 64.12%  |
| EFI  | 47        | 35.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 101       | 77.69%  |
| Overlay | 15        | 11.54%  |
| Btrfs   | 8         | 6.15%   |
| Xfs     | 3         | 2.31%   |
| Unknown | 3         | 2.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 58        | 43.61%  |
| GPT     | 44        | 33.08%  |
| MBR     | 31        | 23.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 109       | 81.95%  |
| Yes       | 24        | 18.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 63.57%  |
| Yes       | 47        | 36.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 24        | 18.75%  |
| Dell                           | 23        | 17.97%  |
| VIT                            | 18        | 14.06%  |
| Hewlett-Packard                | 17        | 13.28%  |
| Acer                           | 8         | 6.25%   |
| ASUSTek Computer               | 7         | 5.47%   |
| Intel                          | 6         | 4.69%   |
| Unknown                        | 5         | 3.91%   |
| Shanghai Zhaoxin Semiconductor | 3         | 2.34%   |
| Google                         | 3         | 2.34%   |
| Toshiba                        | 2         | 1.56%   |
| Pegatron                       | 2         | 1.56%   |
| UNIQCELL                       | 1         | 0.78%   |
| Sony                           | 1         | 0.78%   |
| Samsung Electronics            | 1         | 0.78%   |
| MSI                            | 1         | 0.78%   |
| GPU Company                    | 1         | 0.78%   |
| Gateway                        | 1         | 0.78%   |
| Exo                            | 1         | 0.78%   |
| Clevo                          | 1         | 0.78%   |
| AVITA                          | 1         | 0.78%   |
| Alienware                      | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel powered classmate PC           | 6         | 4.69%   |
| VIT P2400                            | 5         | 3.91%   |
| Unknown                              | 5         | 3.91%   |
| VIT P2402                            | 4         | 3.13%   |
| VIT P3400                            | 3         | 2.34%   |
| VIT M2420                            | 3         | 2.34%   |
| Shanghai Zhaoxin ZXE CRB             | 3         | 2.34%   |
| VIT M2421                            | 2         | 1.56%   |
| Lenovo IdeaPad S100c 20194           | 2         | 1.56%   |
| Lenovo 3000 N200 0769ARS             | 2         | 1.56%   |
| HP Compaq Presario C700              | 2         | 1.56%   |
| Google Candy                         | 2         | 1.56%   |
| Dell Inspiron 1545                   | 2         | 1.56%   |
| Acer Aspire 4739Z                    | 2         | 1.56%   |
| VIT P1400                            | 1         | 0.78%   |
| UNIQCELL Q15.6                       | 1         | 0.78%   |
| Toshiba Satellite E55t-A             | 1         | 0.78%   |
| Toshiba ENCORE 2 WT8-B               | 1         | 0.78%   |
| Sony VGN-FW510F                      | 1         | 0.78%   |
| Samsung 355V4C/356V4C/3445VC/3545VC  | 1         | 0.78%   |
| Pegatron T14AF                       | 1         | 0.78%   |
| Pegatron B74                         | 1         | 0.78%   |
| MSI MS-1454                          | 1         | 0.78%   |
| Lenovo Z50-75 80EC                   | 1         | 0.78%   |
| Lenovo ThinkPad X201 3680AE2         | 1         | 0.78%   |
| Lenovo ThinkPad T14 Gen 1 20S1S2FB00 | 1         | 0.78%   |
| Lenovo ThinkPad SL400 2743A48        | 1         | 0.78%   |
| Lenovo ThinkPad SL 2743A65           | 1         | 0.78%   |
| Lenovo ThinkPad Edge 01962AS         | 1         | 0.78%   |
| Lenovo ThinkPad E560 20EV002FUS      | 1         | 0.78%   |
| Lenovo Legion 5 15IMH05 82AU         | 1         | 0.78%   |
| Lenovo Legion 5 15ARH05H 82B1        | 1         | 0.78%   |
| Lenovo IdeaPad Z580                  | 1         | 0.78%   |
| Lenovo IdeaPad S110 20126            | 1         | 0.78%   |
| Lenovo IdeaPad 5 14ALC05 82LM        | 1         | 0.78%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 0.78%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 1         | 0.78%   |
| Lenovo IdeaPad 1 14IGL05 81VU        | 1         | 0.78%   |
| Lenovo G570 4334                     | 1         | 0.78%   |
| Lenovo G480 20150                    | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 11        | 8.59%   |
| Lenovo IdeaPad       | 8         | 6.25%   |
| HP Pavilion          | 7         | 5.47%   |
| Acer Aspire          | 7         | 5.47%   |
| Lenovo ThinkPad      | 6         | 4.69%   |
| Intel powered        | 6         | 4.69%   |
| Dell Latitude        | 6         | 4.69%   |
| VIT P2400            | 5         | 3.91%   |
| Unknown              | 5         | 3.91%   |
| VIT P2402            | 4         | 3.13%   |
| Dell Vostro          | 4         | 3.13%   |
| VIT P3400            | 3         | 2.34%   |
| VIT M2420            | 3         | 2.34%   |
| Shanghai Zhaoxin ZXE | 3         | 2.34%   |
| Lenovo 3000          | 3         | 2.34%   |
| VIT M2421            | 2         | 1.56%   |
| Lenovo Legion        | 2         | 1.56%   |
| HP Presario          | 2         | 1.56%   |
| HP EliteBook         | 2         | 1.56%   |
| HP Compaq            | 2         | 1.56%   |
| Google Candy         | 2         | 1.56%   |
| ASUS VivoBook        | 2         | 1.56%   |
| ASUS ASUS            | 2         | 1.56%   |
| VIT P1400            | 1         | 0.78%   |
| UNIQCELL Q15.6       | 1         | 0.78%   |
| Toshiba Satellite    | 1         | 0.78%   |
| Toshiba ENCORE       | 1         | 0.78%   |
| Sony VGN-FW510F      | 1         | 0.78%   |
| Samsung 355V4C       | 1         | 0.78%   |
| Pegatron T14AF       | 1         | 0.78%   |
| Pegatron B74         | 1         | 0.78%   |
| MSI MS-1454          | 1         | 0.78%   |
| Lenovo Z50-75        | 1         | 0.78%   |
| Lenovo G570          | 1         | 0.78%   |
| Lenovo G480          | 1         | 0.78%   |
| Lenovo G460          | 1         | 0.78%   |
| Lenovo B40-70        | 1         | 0.78%   |
| HP ProBook           | 1         | 0.78%   |
| HP Mini              | 1         | 0.78%   |
| HP Laptop            | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 16        | 12.5%   |
| 2013    | 14        | 10.94%  |
| 2012    | 14        | 10.94%  |
| 2020    | 10        | 7.81%   |
| 2007    | 9         | 7.03%   |
| 2014    | 8         | 6.25%   |
| 2010    | 8         | 6.25%   |
| 2022    | 7         | 5.47%   |
| 2018    | 7         | 5.47%   |
| 2008    | 7         | 5.47%   |
| 2009    | 6         | 4.69%   |
| 2021    | 5         | 3.91%   |
| 2019    | 5         | 3.91%   |
| 2017    | 4         | 3.13%   |
| 2015    | 4         | 3.13%   |
| 2023    | 1         | 0.78%   |
| 2016    | 1         | 0.78%   |
| 2006    | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 128       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 124       | 96.88%  |
| Enabled  | 4         | 3.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 125       | 97.66%  |
| Yes  | 3         | 2.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 36        | 27.91%  |
| 4.01-8.0   | 30        | 23.26%  |
| 1.01-2.0   | 25        | 19.38%  |
| 8.01-16.0  | 18        | 13.95%  |
| 16.01-24.0 | 9         | 6.98%   |
| 2.01-3.0   | 6         | 4.65%   |
| 32.01-64.0 | 3         | 2.33%   |
| 24.01-32.0 | 1         | 0.78%   |
| 0.51-1.0   | 1         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 54        | 38.3%   |
| 2.01-3.0   | 35        | 24.82%  |
| 0.51-1.0   | 20        | 14.18%  |
| 4.01-8.0   | 15        | 10.64%  |
| 3.01-4.0   | 12        | 8.51%   |
| 8.01-16.0  | 4         | 2.84%   |
| 16.01-24.0 | 1         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 86        | 65.65%  |
| 2      | 40        | 30.53%  |
| 3      | 4         | 3.05%   |
| 0      | 1         | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 51.56%  |
| No        | 62        | 48.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 85.38%  |
| No        | 19        | 14.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 96.88%  |
| No        | 4         | 3.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 55.81%  |
| No        | 57        | 44.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Venezuela | 128       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 59        | 42.75%  |
| Maracaibo                  | 14        | 10.14%  |
| Maracay                    | 8         | 5.8%    |
| Barquisimeto               | 7         | 5.07%   |
| Mérida                    | 6         | 4.35%   |
| Barcelona                  | 4         | 2.9%    |
| Valencia                   | 3         | 2.17%   |
| San Cristóbal             | 2         | 1.45%   |
| San Carlos del Zulia       | 2         | 1.45%   |
| Maturín                   | 2         | 1.45%   |
| Lecherias                  | 2         | 1.45%   |
| Ciudad Guayana             | 2         | 1.45%   |
| Anaco                      | 2         | 1.45%   |
| Tucape                     | 1         | 0.72%   |
| San Juan Bautista          | 1         | 0.72%   |
| San Felipe                 | 1         | 0.72%   |
| San Diego                  | 1         | 0.72%   |
| San Antonio de Los Altos   | 1         | 0.72%   |
| Puerto Ordaz and San Felix | 1         | 0.72%   |
| Puerto Cumarebo            | 1         | 0.72%   |
| Puerto Cruz                | 1         | 0.72%   |
| Porlamar                   | 1         | 0.72%   |
| Parroquia El Recreo        | 1         | 0.72%   |
| Naguanagua                 | 1         | 0.72%   |
| Mariara                    | 1         | 0.72%   |
| Los Palos Grandes          | 1         | 0.72%   |
| Las Vegas                  | 1         | 0.72%   |
| Guatire                    | 1         | 0.72%   |
| Guarenas                   | 1         | 0.72%   |
| Guanare                    | 1         | 0.72%   |
| El Hatillo Municipality    | 1         | 0.72%   |
| Ejido                      | 1         | 0.72%   |
| Ciudad Bolívar            | 1         | 0.72%   |
| Charallave                 | 1         | 0.72%   |
| Cagua                      | 1         | 0.72%   |
| Cabudare                   | 1         | 0.72%   |
| Barinas                    | 1         | 0.72%   |
| Acarigua                   | 1         | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 32     | 19.74%  |
| WDC                 | 26        | 36     | 17.11%  |
| Toshiba             | 15        | 15     | 9.87%   |
| Unknown             | 11        | 15     | 7.24%   |
| Samsung Electronics | 9         | 9      | 5.92%   |
| Hitachi             | 8         | 8      | 5.26%   |
| Intel               | 5         | 8      | 3.29%   |
| Crucial             | 5         | 7      | 3.29%   |
| SanDisk             | 4         | 7      | 2.63%   |
| LITEONIT            | 4         | 7      | 2.63%   |
| Kingston            | 4         | 6      | 2.63%   |
| SPCC                | 3         | 4      | 1.97%   |
| SK hynix            | 3         | 4      | 1.97%   |
| PNY                 | 3         | 3      | 1.97%   |
| HGST                | 3         | 3      | 1.97%   |
| Micron Technology   | 2         | 4      | 1.32%   |
| HUAWEI              | 2         | 2      | 1.32%   |
| Fujitsu             | 2         | 2      | 1.32%   |
| addlink             | 2         | 2      | 1.32%   |
| Vaseky              | 1         | 1      | 0.66%   |
| Team                | 1         | 1      | 0.66%   |
| Silicon Motion      | 1         | 1      | 0.66%   |
| PUSKILL             | 1         | 1      | 0.66%   |
| Phison              | 1         | 1      | 0.66%   |
| Lexar               | 1         | 1      | 0.66%   |
| KingFast            | 1         | 2      | 0.66%   |
| Intenso             | 1         | 1      | 0.66%   |
| Dell                | 1         | 2      | 0.66%   |
| BIWIN               | 1         | 2      | 0.66%   |
| Apacer              | 1         | 1      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB      | 4         | 2.56%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 3         | 1.92%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 1.92%   |
| Unknown NVMe SSD Drive 512GB         | 3         | 1.92%   |
| Seagate ST320LT012-9WS14C 320GB      | 3         | 1.92%   |
| Seagate ST250LM004 HN-M250MBB 250GB  | 3         | 1.92%   |
| LITEONIT LMS-32L6M 32GB SSD          | 3         | 1.92%   |
| WDC WD5000LPVT-08G33T1 500GB         | 2         | 1.28%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 1.28%   |
| WDC WD1200BEVS-60UST0 120GB          | 2         | 1.28%   |
| Unknown MMC Card  16GB               | 2         | 1.28%   |
| Toshiba MQ04ABF100 1TB               | 2         | 1.28%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.28%   |
| Toshiba MQ01ABF032 320GB             | 2         | 1.28%   |
| Toshiba MQ01ABD050 500GB             | 2         | 1.28%   |
| Toshiba MK3275GSX 320GB              | 2         | 1.28%   |
| Seagate ST9320325AS 320GB            | 2         | 1.28%   |
| Seagate ST320LT012-1DG14C 320GB      | 2         | 1.28%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 2         | 1.28%   |
| Seagate ST320LM000 HM321HI 320GB     | 2         | 1.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.28%   |
| SanDisk NVMe SSD Drive 1TB           | 2         | 1.28%   |
| PNY CS900 1TB SSD                    | 2         | 1.28%   |
| HUAWEI SD Storage 128GB              | 2         | 1.28%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.28%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 1.28%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.64%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.64%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.64%   |
| WDC WD3200LPVX-22V0TT0 320GB         | 1         | 0.64%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 0.64%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.64%   |
| WDC WD3200BEVT-00A0RT0 320GB         | 1         | 0.64%   |
| WDC WD3200BEKT-60F3T1 320GB          | 1         | 0.64%   |
| WDC WD1600BEVT-88ZCT0 160GB          | 1         | 0.64%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 0.64%   |
| WDC WD1600BEVS-22RST0 160GB          | 1         | 0.64%   |
| WDC WD10SPCX-75KHST0 1TB             | 1         | 0.64%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.64%   |
| WDC PC SN520 SDAPNUW-256G-1014 256GB | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 30     | 33.73%  |
| WDC                 | 24        | 31     | 28.92%  |
| Toshiba             | 14        | 14     | 16.87%  |
| Hitachi             | 8         | 8      | 9.64%   |
| HGST                | 3         | 3      | 3.61%   |
| Unknown             | 2         | 2      | 2.41%   |
| Samsung Electronics | 2         | 2      | 2.41%   |
| Fujitsu             | 2         | 2      | 2.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 5         | 7      | 15.15%  |
| LITEONIT            | 4         | 7      | 12.12%  |
| Samsung Electronics | 3         | 3      | 9.09%   |
| PNY                 | 3         | 3      | 9.09%   |
| Kingston            | 3         | 5      | 9.09%   |
| SPCC                | 2         | 3      | 6.06%   |
| SanDisk             | 2         | 3      | 6.06%   |
| Vaseky              | 1         | 1      | 3.03%   |
| Toshiba             | 1         | 1      | 3.03%   |
| PUSKILL             | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 3      | 3.03%   |
| Lexar               | 1         | 1      | 3.03%   |
| KingFast            | 1         | 2      | 3.03%   |
| Intenso             | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| Dell                | 1         | 2      | 3.03%   |
| BIWIN               | 1         | 2      | 3.03%   |
| addlink             | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 81        | 92     | 55.1%   |
| SSD     | 32        | 47     | 21.77%  |
| NVMe    | 23        | 35     | 15.65%  |
| MMC     | 7         | 10     | 4.76%   |
| Unknown | 4         | 4      | 2.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 104       | 137    | 74.29%  |
| NVMe | 23        | 35     | 16.43%  |
| MMC  | 7         | 10     | 5%      |
| SAS  | 6         | 6      | 4.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 89        | 110    | 80.18%  |
| 0.51-1.0   | 21        | 28     | 18.92%  |
| 1.01-2.0   | 1         | 1      | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 40        | 29.41%  |
| 101-250    | 33        | 24.26%  |
| 501-1000   | 22        | 16.18%  |
| 1-20       | 16        | 11.76%  |
| 21-50      | 10        | 7.35%   |
| 51-100     | 8         | 5.88%   |
| 1001-2000  | 4         | 2.94%   |
| 2001-3000  | 2         | 1.47%   |
| Unknown    | 1         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 54        | 37.76%  |
| 21-50    | 29        | 20.28%  |
| 101-250  | 23        | 16.08%  |
| 51-100   | 17        | 11.89%  |
| 251-500  | 12        | 8.39%   |
| 501-1000 | 7         | 4.9%    |
| Unknown  | 1         | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD1200BEVS-60UST0 120GB          | 2         | 2      | 9.09%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 1      | 4.55%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 4.55%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2      | 4.55%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 4.55%   |
| Toshiba MK3275GSX 320GB              | 1         | 1      | 4.55%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 4.55%   |
| Seagate ST9320325AS 320GB            | 1         | 1      | 4.55%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 4.55%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 4.55%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 4.55%   |
| Samsung Electronics HN-M320MBB 320GB | 1         | 1      | 4.55%   |
| Samsung Electronics HM250HI 250GB    | 1         | 1      | 4.55%   |
| Intel SSDPEKKW256G7 256GB            | 1         | 1      | 4.55%   |
| Intel SSDPEKKF512G7L 512GB           | 1         | 1      | 4.55%   |
| Hitachi HTS725050A9A364 500GB        | 1         | 1      | 4.55%   |
| Hitachi HTS543232L9A300 320GB        | 1         | 1      | 4.55%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1      | 4.55%   |
| Hitachi HTS542525K9SA00 250GB        | 1         | 1      | 4.55%   |
| HGST HTS541010A7E630 1TB             | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 6      | 22.73%  |
| Seagate             | 5         | 5      | 22.73%  |
| Hitachi             | 4         | 4      | 18.18%  |
| Toshiba             | 3         | 3      | 13.64%  |
| Samsung Electronics | 2         | 2      | 9.09%   |
| Intel               | 2         | 2      | 9.09%   |
| HGST                | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 6      | 25%     |
| Seagate             | 5         | 5      | 25%     |
| Hitachi             | 4         | 4      | 20%     |
| Toshiba             | 3         | 3      | 15%     |
| Samsung Electronics | 2         | 2      | 10%     |
| HGST                | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 21     | 90.91%  |
| NVMe | 2         | 2      | 9.09%   |

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
| Detected | 72        | 106    | 52.55%  |
| Works    | 43        | 59     | 31.39%  |
| Malfunc  | 22        | 23     | 16.06%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 102       | 73.91%  |
| AMD                         | 16        | 11.59%  |
| Samsung Electronics         | 4         | 2.9%    |
| SK hynix                    | 3         | 2.17%   |
| SanDisk                     | 3         | 2.17%   |
| Phison Electronics          | 3         | 2.17%   |
| Jiangsu Huacun Elec.        | 3         | 2.17%   |
| Silicon Motion              | 2         | 1.45%   |
| Micron Technology           | 1         | 0.72%   |
| Kingston Technology Company | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 12.5%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 9.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 7.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 5.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 5.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 4.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 4.61%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 6         | 3.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 3.29%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 2.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 2.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 2.63%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.97%   |
| Jiangsu Huacun Elec. Non-Volatile memory controller                            | 3         | 1.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.97%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 1.32%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.32%   |
| Intel SSD 600P Series                                                          | 2         | 1.32%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 2         | 1.32%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 1.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.32%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 0.66%   |
| SK hynix BC511                                                                 | 1         | 0.66%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.66%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.66%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.66%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 0.66%   |
| Phison Electronics Non-Volatile memory controller                              | 1         | 0.66%   |
| Micron Non-Volatile memory controller                                          | 1         | 0.66%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.66%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.66%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.66%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.66%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 94        | 64.38%  |
| NVMe | 23        | 15.75%  |
| IDE  | 15        | 10.27%  |
| RAID | 14        | 9.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 108       | 84.38%  |
| AMD          | 17        | 13.28%  |
| CentaurHauls | 3         | 2.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 4         | 3.13%   |
| Intel Celeron CPU 847 @ 1.10GHz                | 4         | 3.13%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 4         | 3.13%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 3         | 2.34%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 3         | 2.34%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 3         | 2.34%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 3         | 2.34%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 3         | 2.34%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 1.56%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 2         | 1.56%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 2         | 1.56%   |
| Intel Core i5-3337U CPU @ 1.80GHz              | 2         | 1.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 1.56%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 2         | 1.56%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 2         | 1.56%   |
| Intel Core i3-4000M CPU @ 2.40GHz              | 2         | 1.56%   |
| Intel Core i3-2350M CPU @ 2.30GHz              | 2         | 1.56%   |
| Intel Core i3 CPU M 330 @ 2.13GHz              | 2         | 1.56%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz           | 2         | 1.56%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 2         | 1.56%   |
| Intel Celeron CPU N2805 @ 1.46GHz              | 2         | 1.56%   |
| Intel Atom CPU N570 @ 1.66GHz                  | 2         | 1.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 1.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 2         | 1.56%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 0.78%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz         | 1         | 0.78%   |
| Intel Pentium CPU 2030M @ 2.50GHz              | 1         | 0.78%   |
| Intel Genuine CPU U7300 @ 1.30GHz              | 1         | 0.78%   |
| Intel Genuine CPU T2080 @ 1.73GHz              | 1         | 0.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 1         | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 1         | 0.78%   |
| Intel Core i7-7820HK CPU @ 2.90GHz             | 1         | 0.78%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz             | 1         | 0.78%   |
| Intel Core i7-5600U CPU @ 2.60GHz              | 1         | 0.78%   |
| Intel Core i7-4500U CPU @ 1.80GHz              | 1         | 0.78%   |
| Intel Core i7-3632QM CPU @ 2.20GHz             | 1         | 0.78%   |
| Intel Core i7-3537U CPU @ 2.00GHz              | 1         | 0.78%   |
| Intel Core i7-3520M CPU @ 2.90GHz              | 1         | 0.78%   |
| Intel Core i7-2640M CPU @ 2.80GHz              | 1         | 0.78%   |
| Intel Core i7-2620M CPU @ 2.70GHz              | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 22        | 17.19%  |
| Intel Core i3                  | 22        | 17.19%  |
| Intel Core 2 Duo               | 13        | 10.16%  |
| Intel Celeron                  | 13        | 10.16%  |
| Intel Core i7                  | 12        | 9.38%   |
| Intel Atom                     | 9         | 7.03%   |
| Other                          | 8         | 6.25%   |
| AMD Ryzen 5                    | 6         | 4.69%   |
| Intel Pentium                  | 4         | 3.13%   |
| Intel Pentium Dual             | 3         | 2.34%   |
| AMD Ryzen 7                    | 3         | 2.34%   |
| Intel Pentium Dual-Core        | 2         | 1.56%   |
| Intel Genuine                  | 2         | 1.56%   |
| AMD A10                        | 2         | 1.56%   |
| Intel Pentium Silver           | 1         | 0.78%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.78%   |
| AMD Ryzen 3                    | 1         | 0.78%   |
| AMD Mobile Sempron             | 1         | 0.78%   |
| AMD E1                         | 1         | 0.78%   |
| AMD E                          | 1         | 0.78%   |
| AMD A6                         | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 89        | 69.53%  |
| 4       | 21        | 16.41%  |
| 1       | 7         | 5.47%   |
| 6       | 5         | 3.91%   |
| 8       | 3         | 2.34%   |
| Unknown | 2         | 1.56%   |
| 14      | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 128       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 79        | 61.72%  |
| 1       | 47        | 36.72%  |
| Unknown | 2         | 1.56%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 122       | 95.31%  |
| 64-bit         | 3         | 2.34%   |
| 32-bit         | 3         | 2.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 21.8%   |
| 0x306a9    | 15        | 11.28%  |
| 0x206a7    | 13        | 9.77%   |
| 0x1067a    | 11        | 8.27%   |
| 0x6fd      | 7         | 5.26%   |
| 0x806e9    | 5         | 3.76%   |
| 0x106ca    | 5         | 3.76%   |
| 0x30678    | 4         | 3.01%   |
| 0x806c1    | 3         | 2.26%   |
| 0x40651    | 3         | 2.26%   |
| 0x20655    | 3         | 2.26%   |
| 0x406e3    | 2         | 1.5%    |
| 0x306d4    | 2         | 1.5%    |
| 0x306c3    | 2         | 1.5%    |
| 0x30673    | 2         | 1.5%    |
| 0x08608103 | 2         | 1.5%    |
| 0x08108102 | 2         | 1.5%    |
| 0x05000119 | 2         | 1.5%    |
| 0x906e9    | 1         | 0.75%   |
| 0x806ec    | 1         | 0.75%   |
| 0x806ea    | 1         | 0.75%   |
| 0x806d1    | 1         | 0.75%   |
| 0x706e5    | 1         | 0.75%   |
| 0x706a8    | 1         | 0.75%   |
| 0x6ec      | 1         | 0.75%   |
| 0x506e3    | 1         | 0.75%   |
| 0x406c4    | 1         | 0.75%   |
| 0x30661    | 1         | 0.75%   |
| 0x20652    | 1         | 0.75%   |
| 0x106c2    | 1         | 0.75%   |
| 0x08600104 | 1         | 0.75%   |
| 0x08600103 | 1         | 0.75%   |
| 0x08600102 | 1         | 0.75%   |
| 0x0810100b | 1         | 0.75%   |
| 0x08101007 | 1         | 0.75%   |
| 0x06006704 | 1         | 0.75%   |
| 0x06006118 | 1         | 0.75%   |
| 0x06003106 | 1         | 0.75%   |
| 0x02000057 | 1         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 17        | 13.28%  |
| IvyBridge        | 17        | 13.28%  |
| Penryn           | 10        | 7.81%   |
| KabyLake         | 10        | 7.81%   |
| Core             | 9         | 7.03%   |
| Westmere         | 8         | 6.25%   |
| Bonnell          | 8         | 6.25%   |
| Silvermont       | 7         | 5.47%   |
| Haswell          | 5         | 3.91%   |
| Unknown          | 5         | 3.91%   |
| Zen+             | 3         | 2.34%   |
| Zen 2            | 3         | 2.34%   |
| TigerLake        | 3         | 2.34%   |
| Skylake          | 3         | 2.34%   |
| Broadwell        | 3         | 2.34%   |
| Zen              | 2         | 1.56%   |
| Icelake          | 2         | 1.56%   |
| Goldmont plus    | 2         | 1.56%   |
| Excavator        | 2         | 1.56%   |
| Bobcat           | 2         | 1.56%   |
| Steamroller      | 1         | 0.78%   |
| P6               | 1         | 0.78%   |
| K8 Hammer        | 1         | 0.78%   |
| K8 & K10 hybrid  | 1         | 0.78%   |
| Goldmont         | 1         | 0.78%   |
| CometLake        | 1         | 0.78%   |
| Alderlake Hybrid | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 104       | 76.47%  |
| AMD     | 18        | 13.24%  |
| Nvidia  | 11        | 8.09%   |
| Zhaoxin | 3         | 2.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 16        | 10.96%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 16        | 10.96%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 10        | 6.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 8         | 5.48%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 8         | 5.48%   |
| Intel Core Processor Integrated Graphics Controller                           | 8         | 5.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 6         | 4.11%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 6         | 4.11%   |
| Intel HD Graphics 620                                                         | 4         | 2.74%   |
| Zhaoxin ZX-E C-960 GPU                                                        | 3         | 2.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 2.05%   |
| Intel HD Graphics 5500                                                        | 3         | 2.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 2.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 2.05%   |
| Nvidia TU117M                                                                 | 2         | 1.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 1.37%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 1.37%   |
| Intel HD Graphics 630                                                         | 2         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 1.37%   |
| AMD Renoir                                                                    | 2         | 1.37%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.37%   |
| AMD Lucienne                                                                  | 2         | 1.37%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.68%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.68%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                      | 1         | 0.68%   |
| Nvidia GM204GLM [Quadro M3000M]                                               | 1         | 0.68%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 0.68%   |
| Nvidia GF104GLM [Quadro 3000M]                                                | 1         | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 1         | 0.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 0.68%   |
| Intel UHD Graphics 620                                                        | 1         | 0.68%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 0.68%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.68%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 0.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 0.68%   |
| Intel HD Graphics 615                                                         | 1         | 0.68%   |
| Intel HD Graphics 530                                                         | 1         | 0.68%   |
| Intel HD Graphics 500                                                         | 1         | 0.68%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 96        | 75%     |
| 1 x AMD        | 16        | 12.5%   |
| 1 x Nvidia     | 5         | 3.91%   |
| Intel + Nvidia | 5         | 3.91%   |
| 1 x Zhaoxin    | 3         | 2.34%   |
| 2 x Intel      | 1         | 0.78%   |
| Intel + AMD    | 1         | 0.78%   |
| AMD + Nvidia   | 1         | 0.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 116       | 90.63%  |
| Proprietary | 7         | 5.47%   |
| Unknown     | 5         | 3.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 105       | 80.77%  |
| 0.01-0.5   | 14        | 10.77%  |
| 1.01-2.0   | 6         | 4.62%   |
| 3.01-4.0   | 3         | 2.31%   |
| 0.51-1.0   | 2         | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 21        | 15.22%  |
| Samsung Electronics     | 20        | 14.49%  |
| LG Display              | 19        | 13.77%  |
| AU Optronics            | 19        | 13.77%  |
| Chimei Innolux          | 13        | 9.42%   |
| Chi Mei Optoelectronics | 7         | 5.07%   |
| Lenovo                  | 6         | 4.35%   |
| LG Philips              | 5         | 3.62%   |
| InfoVision              | 5         | 3.62%   |
| Hewlett-Packard         | 4         | 2.9%    |
| HannStar                | 4         | 2.9%    |
| Goldstar                | 3         | 2.17%   |
| PANDA                   | 2         | 1.45%   |
| Dell                    | 2         | 1.45%   |
| Vizio                   | 1         | 0.72%   |
| ViewSonic               | 1         | 0.72%   |
| Sharp                   | 1         | 0.72%   |
| MStar                   | 1         | 0.72%   |
| KTC                     | 1         | 0.72%   |
| InnoLux Display         | 1         | 0.72%   |
| ASUSTek Computer        | 1         | 0.72%   |
| Acer                    | 1         | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch       | 5         | 3.62%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 4         | 2.9%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 3         | 2.17%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                  | 3         | 2.17%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch         | 3         | 2.17%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2         | 1.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 2         | 1.45%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.45%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 2         | 1.45%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 2         | 1.45%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 2         | 1.45%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch           | 2         | 1.45%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch           | 2         | 1.45%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                  | 2         | 1.45%   |
| Vizio E3D320VX VIZ0079 1920x1080 698x393mm 31.5-inch                  | 1         | 0.72%   |
| ViewSonic VA2252 SERIES VSC7731 1920x1080 476x268mm 21.5-inch         | 1         | 0.72%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.72%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch     | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC8151 1920x1080 382x214mm 17.2-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4147 3840x2160 294x165mm 13.3-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch  | 1         | 0.72%   |
| MStar Demo MST0030 1920x540 708x398mm 32.0-inch                       | 1         | 0.72%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch         | 1         | 0.72%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch         | 1         | 0.72%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 0.72%   |
| LG Philips LCD Monitor LPL0701 1280x800 331x207mm 15.4-inch           | 1         | 0.72%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.72%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch         | 1         | 0.72%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD0550 1920x1080 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD04B7 1366x768 344x194mm 15.5-inch           | 1         | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 70        | 54.69%  |
| 1920x1080 (FHD)   | 27        | 21.09%  |
| 1280x800 (WXGA)   | 13        | 10.16%  |
| 3840x2160 (4K)    | 3         | 2.34%   |
| 1600x900 (HD+)    | 3         | 2.34%   |
| 1360x768          | 3         | 2.34%   |
| 1024x600          | 3         | 2.34%   |
| 1440x900 (WXGA+)  | 2         | 1.56%   |
| 1280x1024 (SXGA)  | 2         | 1.56%   |
| 2560x1440 (QHD)   | 1         | 0.78%   |
| 1920x1200 (WUXGA) | 1         | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 50        | 36.5%   |
| 14     | 30        | 21.9%   |
| 13     | 21        | 15.33%  |
| 21     | 6         | 4.38%   |
| 10     | 6         | 4.38%   |
| 17     | 5         | 3.65%   |
| 11     | 5         | 3.65%   |
| 18     | 3         | 2.19%   |
| 27     | 2         | 1.46%   |
| 23     | 2         | 1.46%   |
| 54     | 1         | 0.73%   |
| 52     | 1         | 0.73%   |
| 32     | 1         | 0.73%   |
| 31     | 1         | 0.73%   |
| 24     | 1         | 0.73%   |
| 19     | 1         | 0.73%   |
| 12     | 1         | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 99        | 72.79%  |
| 201-300     | 13        | 9.56%   |
| 401-500     | 9         | 6.62%   |
| 351-400     | 6         | 4.41%   |
| 501-600     | 5         | 3.68%   |
| 1001-1500   | 2         | 1.47%   |
| 701-800     | 1         | 0.74%   |
| 601-700     | 1         | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 102       | 84.3%   |
| 16/10 | 16        | 13.22%  |
| 5/4   | 2         | 1.65%   |
| 3/2   | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 50        | 36.5%   |
| 101-110        | 50        | 36.5%   |
| 201-250        | 7         | 5.11%   |
| 41-50          | 6         | 4.38%   |
| 51-60          | 5         | 3.65%   |
| 141-150        | 4         | 2.92%   |
| 121-130        | 4         | 2.92%   |
| More than 1000 | 2         | 1.46%   |
| 351-500        | 2         | 1.46%   |
| 301-350        | 2         | 1.46%   |
| 151-200        | 2         | 1.46%   |
| 71-80          | 1         | 0.73%   |
| 61-70          | 1         | 0.73%   |
| 251-300        | 1         | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 65        | 48.15%  |
| 121-160       | 36        | 26.67%  |
| 51-100        | 27        | 20%     |
| 1-50          | 4         | 2.96%   |
| 161-240       | 2         | 1.48%   |
| More than 240 | 1         | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 108       | 83.08%  |
| 2     | 16        | 12.31%  |
| 0     | 4         | 3.08%   |
| 3     | 2         | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 85        | 40.28%  |
| Intel                           | 46        | 21.8%   |
| Qualcomm Atheros                | 42        | 19.91%  |
| Broadcom                        | 13        | 6.16%   |
| Broadcom Limited                | 5         | 2.37%   |
| Marvell Technology Group        | 3         | 1.42%   |
| Xiaomi                          | 2         | 0.95%   |
| Samsung Electronics             | 2         | 0.95%   |
| Qualcomm Atheros Communications | 2         | 0.95%   |
| MediaTek                        | 2         | 0.95%   |
| JMicron Technology              | 2         | 0.95%   |
| ZyXEL Communications            | 1         | 0.47%   |
| Trendchip Technologies          | 1         | 0.47%   |
| TP-Link                         | 1         | 0.47%   |
| Ralink Technology               | 1         | 0.47%   |
| Huawei Technologies             | 1         | 0.47%   |
| ASIX Electronics                | 1         | 0.47%   |
| AMD                             | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 44        | 17.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 19        | 7.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 4.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 9         | 3.66%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 7         | 2.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.85%   |
| Intel Wireless 7265                                                     | 7         | 2.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 6         | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 1.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 1.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.63%   |
| Intel Wireless 7260                                                     | 4         | 1.63%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 1.22%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.22%   |
| Intel WiFi Link 5100                                                    | 3         | 1.22%   |
| Intel Centrino Wireless-N 105                                           | 3         | 1.22%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1.22%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.81%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 0.81%   |
| Intel Wireless 8260                                                     | 2         | 0.81%   |
| Intel Wireless 3165                                                     | 2         | 0.81%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.81%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 0.81%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.81%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.81%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.81%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express             | 2         | 0.81%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 34.88%  |
| Realtek Semiconductor           | 33        | 25.58%  |
| Qualcomm Atheros                | 32        | 24.81%  |
| Broadcom                        | 11        | 8.53%   |
| Qualcomm Atheros Communications | 2         | 1.55%   |
| MediaTek                        | 2         | 1.55%   |
| Broadcom Limited                | 2         | 1.55%   |
| Xiaomi                          | 1         | 0.78%   |
| Ralink Technology               | 1         | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Notebooks | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 12        | 9.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 9         | 6.98%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                      | 7         | 5.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 7         | 5.43%   |
| Intel Wireless 7265                                                                  | 7         | 5.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 4         | 3.1%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                          | 4         | 3.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 4         | 3.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 4         | 3.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)              | 4         | 3.1%    |
| Intel Wireless 7260                                                                  | 4         | 3.1%    |
| Broadcom BCM4311 802.11b/g WLAN                                                      | 4         | 3.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 3         | 2.33%   |
| Intel Wireless 8265 / 8275                                                           | 3         | 2.33%   |
| Intel WiFi Link 5100                                                                 | 3         | 2.33%   |
| Intel Centrino Wireless-N 105                                                        | 3         | 2.33%   |
| Intel Centrino Ultimate-N 6300                                                       | 3         | 2.33%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                    | 3         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 2         | 1.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 2         | 1.55%   |
| Intel Wireless 8260                                                                  | 2         | 1.55%   |
| Intel Wireless 3165                                                                  | 2         | 1.55%   |
| Intel Wi-Fi 6 AX201                                                                  | 2         | 1.55%   |
| Intel Wi-Fi 6 AX200                                                                  | 2         | 1.55%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                        | 2         | 1.55%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                        | 2         | 1.55%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                         | 2         | 1.55%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                            | 2         | 1.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                  | 2         | 1.55%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                                    | 1         | 0.78%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                           | 1         | 0.78%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 1         | 0.78%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1         | 0.78%   |
| Realtek 802.11n WLAN Adapter                                                         | 1         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                                      | 1         | 0.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1         | 0.78%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 1         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 0.78%   |
| Intel Gemini Lake PCH CNVi WiFi                                                      | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 69        | 60.53%  |
| Qualcomm Atheros         | 14        | 12.28%  |
| Intel                    | 13        | 11.4%   |
| Marvell Technology Group | 3         | 2.63%   |
| Broadcom Limited         | 3         | 2.63%   |
| Broadcom                 | 3         | 2.63%   |
| Samsung Electronics      | 2         | 1.75%   |
| JMicron Technology       | 2         | 1.75%   |
| ZyXEL Communications     | 1         | 0.88%   |
| Xiaomi                   | 1         | 0.88%   |
| Trendchip Technologies   | 1         | 0.88%   |
| TP-Link                  | 1         | 0.88%   |
| ASIX Electronics         | 1         | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 38.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 16.52%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 5.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 3.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.74%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.74%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 2         | 1.74%   |
| ZyXEL ADSL Modem Prestige 600 series                              | 1         | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.87%   |
| Trendchip Ethernet controller                                     | 1         | 0.87%   |
| TP-Link M7200                                                     | 1         | 0.87%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.87%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.87%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.87%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.87%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.87%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.87%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.87%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.87%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.87%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.87%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.87%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.87%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.87%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.87%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.87%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 124       | 52.54%  |
| Ethernet | 110       | 46.61%  |
| Modem    | 2         | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 72.59%  |
| Ethernet | 37        | 27.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 101       | 78.91%  |
| 1     | 25        | 19.53%  |
| 0     | 2         | 1.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 128       | 99.22%  |
| Yes  | 1         | 0.78%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 40.28%  |
| Qualcomm Atheros Communications | 11        | 15.28%  |
| IMC Networks                    | 10        | 13.89%  |
| Realtek Semiconductor           | 7         | 9.72%   |
| Lite-On Technology              | 4         | 5.56%   |
| Broadcom                        | 4         | 5.56%   |
| Cambridge Silicon Radio         | 3         | 4.17%   |
| Hewlett-Packard                 | 2         | 2.78%   |
| Dell                            | 1         | 1.39%   |
| ASUSTek Computer                | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 18        | 25%     |
| Qualcomm Atheros  Bluetooth Device                          | 5         | 6.94%   |
| Intel AX201 Bluetooth                                       | 4         | 5.56%   |
| IMC Networks Bluetooth                                      | 4         | 5.56%   |
| Realtek RTL8723B Bluetooth                                  | 3         | 4.17%   |
| Realtek Bluetooth Radio                                     | 3         | 4.17%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 3         | 4.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 3         | 4.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 4.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 2.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 2.78%   |
| Intel AX200 Bluetooth                                       | 2         | 2.78%   |
| IMC Networks Bluetooth Radio                                | 2         | 2.78%   |
| Broadcom BCM2045 Bluetooth                                  | 2         | 2.78%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.39%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 1.39%   |
| Lite-On Wireless_Device                                     | 1         | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.39%   |
| Lite-On Bluetooth Device                                    | 1         | 1.39%   |
| Lite-On BCM20702A0                                          | 1         | 1.39%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.39%   |
| IMC Networks Wireless_Device                                | 1         | 1.39%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 1.39%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.39%   |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 1.39%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.39%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.39%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 108       | 77.14%  |
| AMD                   | 18        | 12.86%  |
| Nvidia                | 8         | 5.71%   |
| Zhaoxin               | 3         | 2.14%   |
| Realtek Semiconductor | 1         | 0.71%   |
| Microsoft             | 1         | 0.71%   |
| Logitech              | 1         | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23        | 13.86%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 6.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 6.63%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 6.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9         | 5.42%   |
| Intel Sunrise Point-LP HD Audio                                            | 8         | 4.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 8         | 4.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 4.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 3.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 3.01%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 2.41%   |
| Zhaoxin ZX-E High Definition Audio Controller                              | 3         | 1.81%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller   | 3         | 1.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.81%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.81%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.81%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.2%    |
| Intel CM238 HD Audio Controller                                            | 2         | 1.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.2%    |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.2%    |
| Realtek Semiconductor USB Audio                                            | 1         | 0.6%    |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.6%    |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.6%    |
| Nvidia GF104 High Definition Audio Controller                              | 1         | 0.6%    |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.6%    |
| Nvidia Audio device                                                        | 1         | 0.6%    |
| Microsoft LifeChat LX-4000                                                 | 1         | 0.6%    |
| Logitech G635 Gaming Headset                                               | 1         | 0.6%    |
| Intel USB PnP Sound Device                                                 | 1         | 0.6%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.6%    |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.6%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 24        | 22.64%  |
| Samsung Electronics | 18        | 16.98%  |
| Unknown             | 15        | 14.15%  |
| Ramaxel Technology  | 11        | 10.38%  |
| Micron Technology   | 9         | 8.49%   |
| Kingston            | 6         | 5.66%   |
| Crucial             | 5         | 4.72%   |
| Elpida              | 4         | 3.77%   |
| Unknown (ABCD)      | 2         | 1.89%   |
| Shenzhen WODPOSIT   | 2         | 1.89%   |
| Qimonda             | 2         | 1.89%   |
| Unknown             | 2         | 1.89%   |
| Unknown (081A)      | 1         | 0.94%   |
| Memox               | 1         | 0.94%   |
| Gold Key            | 1         | 0.94%   |
| Corsair             | 1         | 0.94%   |
| A-DATA Technology   | 1         | 0.94%   |
| <Invalid>           | 1         | 0.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 2.65%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.65%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 3         | 2.65%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s          | 3         | 2.65%   |
| Ramaxel RAM RMT3010EC58E8F1333 2048MB SODIMM DDR3 1600MT/s       | 3         | 2.65%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.77%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 2         | 1.77%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM 1600MT/s                | 2         | 1.77%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 1.77%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.77%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s            | 2         | 1.77%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 2         | 1.77%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 1.77%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 1.77%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 1.77%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s          | 2         | 1.77%   |
| Unknown                                                          | 2         | 1.77%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.88%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.88%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.88%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                        | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.88%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 1         | 0.88%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.88%   |
| Unknown (081A) RAM HXMSH2GS03A2F1CL16 2GB SODIMM DDR3 1600MT/s   | 1         | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-RD 4GB SODIMM DDR3 1867MT/s           | 1         | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 31        | 37.8%   |
| DDR4   | 28        | 34.15%  |
| DDR2   | 14        | 17.07%  |
| SDRAM  | 5         | 6.1%    |
| LPDDR4 | 3         | 3.66%   |
| DDR    | 1         | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 76        | 96.2%   |
| Row Of Chips | 2         | 2.53%   |
| DIMM         | 1         | 1.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 31        | 32.98%  |
| 8192  | 29        | 30.85%  |
| 4096  | 23        | 24.47%  |
| 1024  | 6         | 6.38%   |
| 16384 | 5         | 5.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 27.96%  |
| 3200    | 11        | 11.83%  |
| 2667    | 11        | 11.83%  |
| 2400    | 7         | 7.53%   |
| 667     | 7         | 7.53%   |
| 1333    | 5         | 5.38%   |
| 1334    | 4         | 4.3%    |
| 2666    | 3         | 3.23%   |
| 533     | 3         | 3.23%   |
| Unknown | 3         | 3.23%   |
| 4199    | 2         | 2.15%   |
| 2048    | 2         | 2.15%   |
| 1067    | 2         | 2.15%   |
| 975     | 2         | 2.15%   |
| 3266    | 1         | 1.08%   |
| 2133    | 1         | 1.08%   |
| 1867    | 1         | 1.08%   |
| 1066    | 1         | 1.08%   |
| 800     | 1         | 1.08%   |

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
| Chicony Electronics                    | 22        | 21.78%  |
| Microdia                               | 15        | 14.85%  |
| Acer                                   | 11        | 10.89%  |
| Realtek Semiconductor                  | 9         | 8.91%   |
| IMC Networks                           | 9         | 8.91%   |
| Suyin                                  | 7         | 6.93%   |
| Sunplus Innovation Technology          | 4         | 3.96%   |
| Quanta                                 | 4         | 3.96%   |
| Ricoh                                  | 3         | 2.97%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.97%   |
| ALi                                    | 3         | 2.97%   |
| Syntek                                 | 2         | 1.98%   |
| Lite-On Technology                     | 2         | 1.98%   |
| Tobii Technology AB                    | 1         | 0.99%   |
| Sonix Technology                       | 1         | 0.99%   |
| Luxvisions Innotech Limited            | 1         | 0.99%   |
| Lenovo                                 | 1         | 0.99%   |
| Importek                               | 1         | 0.99%   |
| icSpring                               | 1         | 0.99%   |
| Apple                                  | 1         | 0.99%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Microdia USB 2.0 Camera                                       | 5         | 4.95%   |
| Chicony USB 2.0 Camera                                        | 5         | 4.95%   |
| Realtek Integrated_Webcam_HD                                  | 4         | 3.96%   |
| Chicony Lenovo EasyCamera                                     | 4         | 3.96%   |
| Chicony Integrated Camera                                     | 4         | 3.96%   |
| Acer HD Webcam                                                | 4         | 3.96%   |
| IMC Networks XHC Camera                                       | 3         | 2.97%   |
| Suyin Webcam-101                                              | 2         | 1.98%   |
| Suyin Integrated_Webcam_HD                                    | 2         | 1.98%   |
| Sunplus Integrated_Webcam_HD                                  | 2         | 1.98%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 2         | 1.98%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 1.98%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 1.98%   |
| IMC Networks Lenovo EasyCamera                                | 2         | 1.98%   |
| Chicony HD WebCam                                             | 2         | 1.98%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 2         | 1.98%   |
| ALi WebCam                                                    | 2         | 1.98%   |
| Acer USB Camera                                               | 2         | 1.98%   |
| Acer Lenovo EasyCamera                                        | 2         | 1.98%   |
| Tobii AB EyeChip                                              | 1         | 0.99%   |
| Syntek USB Camera Device                                      | 1         | 0.99%   |
| Syntek Integrated Webcam                                      | 1         | 0.99%   |
| Suyin Lenovo EasyCamera                                       | 1         | 0.99%   |
| Suyin Acer HD Crystal Eye webcam                              | 1         | 0.99%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 0.99%   |
| Sunplus USB Camera                                            | 1         | 0.99%   |
| Sunplus Lenovo EasyCamera                                     | 1         | 0.99%   |
| Sonix USB2.0 HD UVC WebCam                                    | 1         | 0.99%   |
| Ricoh Sony Vaio Integrated Webcam                             | 1         | 0.99%   |
| Realtek USB Camera                                            | 1         | 0.99%   |
| Realtek MTD camera                                            | 1         | 0.99%   |
| Realtek Integrated Webcam HD                                  | 1         | 0.99%   |
| Realtek Integrated Webcam                                     | 1         | 0.99%   |
| Realtek EasyCamera                                            | 1         | 0.99%   |
| Quanta VGA WebCam                                             | 1         | 0.99%   |
| Quanta HP Webcam                                              | 1         | 0.99%   |
| Quanta HD User Facing                                         | 1         | 0.99%   |
| Quanta ACER HD User Facing                                    | 1         | 0.99%   |
| Microdia WebCam SC-13HDL12639P                                | 1         | 0.99%   |
| Microdia USB camera                                           | 1         | 0.99%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 53.85%  |
| AuthenTec                  | 2         | 15.38%  |
| Upek                       | 1         | 7.69%   |
| Synaptics                  | 1         | 7.69%   |
| Shenzhen Goodix Technology | 1         | 7.69%   |
| Futronic Technology        | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 23.08%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 15.38%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 15.38%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 7.69%   |
| Validity Sensors Fingerprint scanner                   | 1         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.69%   |
| Futronic Fingerprint Scanner Model FS88                | 1         | 7.69%   |

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
| 0     | 96        | 73.85%  |
| 1     | 27        | 20.77%  |
| 2     | 6         | 4.62%   |
| 5     | 1         | 0.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 13        | 30.23%  |
| Fingerprint reader       | 13        | 30.23%  |
| Chipcard                 | 5         | 11.63%  |
| Sound                    | 4         | 9.3%    |
| Net/wireless             | 3         | 6.98%   |
| Camera                   | 3         | 6.98%   |
| Storage                  | 1         | 2.33%   |
| Communication controller | 1         | 2.33%   |

