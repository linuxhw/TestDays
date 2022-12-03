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

Total: 174

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Debian 11                    | 12        | 9.76%   |
| Ubuntu 20.04                 | 10        | 8.13%   |
| OpenMandriva 4.3             | 7         | 5.69%   |
| Debian 10                    | 6         | 4.88%   |
| Ubuntu 22.04                 | 5         | 4.07%   |
| Ubuntu 18.04                 | 5         | 4.07%   |
| KDE neon 20.04               | 5         | 4.07%   |
| Kubuntu 20.04                | 4         | 3.25%   |
| Zorin 16                     | 3         | 2.44%   |
| Xubuntu 18.04                | 3         | 2.44%   |
| ROSA R9                      | 3         | 2.44%   |
| OpenMandriva 4.2             | 3         | 2.44%   |
| Linux Mint 20.3              | 3         | 2.44%   |
| Zorin 15                     | 2         | 1.63%   |
| Ubuntu Unity 16.04           | 2         | 1.63%   |
| Ubuntu 21.10                 | 2         | 1.63%   |
| Ubuntu 19.10                 | 2         | 1.63%   |
| Pop!_OS 22.04                | 2         | 1.63%   |
| Pop!_OS 21.04                | 2         | 1.63%   |
| Manjaro                      | 2         | 1.63%   |
| Linux Mint 20                | 2         | 1.63%   |
| Fedora 36                    | 2         | 1.63%   |
| Fedora 35                    | 2         | 1.63%   |
| ArcoLinux Rolling            | 2         | 1.63%   |
| Xubuntu 21.10                | 1         | 0.81%   |
| Xubuntu 20.04                | 1         | 0.81%   |
| Ubuntu MATE 20.04            | 1         | 0.81%   |
| Ubuntu MATE 19.10            | 1         | 0.81%   |
| Ubuntu 16.04                 | 1         | 0.81%   |
| Solus 4.1                    | 1         | 0.81%   |
| ROSA R11                     | 1         | 0.81%   |
| Q4OS 4                       | 1         | 0.81%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.81%   |
| OpenMandriva 4.50            | 1         | 0.81%   |
| MX 20                        | 1         | 0.81%   |
| Manjaro 21.2.0               | 1         | 0.81%   |
| Manjaro 21.1.0               | 1         | 0.81%   |
| Manjaro 21.0                 | 1         | 0.81%   |
| Manjaro 20.1                 | 1         | 0.81%   |
| Lubuntu 18.04                | 1         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 23        | 19.49%  |
| Debian       | 17        | 14.41%  |
| OpenMandriva | 11        | 9.32%   |
| Manjaro      | 6         | 5.08%   |
| Linux Mint   | 6         | 5.08%   |
| KDE neon     | 6         | 5.08%   |
| Zorin        | 5         | 4.24%   |
| Xubuntu      | 5         | 4.24%   |
| Kubuntu      | 5         | 4.24%   |
| Fedora       | 5         | 4.24%   |
| ROSA         | 4         | 3.39%   |
| Pop!_OS      | 4         | 3.39%   |
| Ubuntu Unity | 2         | 1.69%   |
| Ubuntu MATE  | 2         | 1.69%   |
| LMDE         | 2         | 1.69%   |
| ArcoLinux    | 2         | 1.69%   |
| Solus        | 1         | 0.85%   |
| Q4OS         | 1         | 0.85%   |
| openSUSE     | 1         | 0.85%   |
| MX           | 1         | 0.85%   |
| Lubuntu      | 1         | 0.85%   |
| Linux Lite   | 1         | 0.85%   |
| Garuda Linux | 1         | 0.85%   |
| Feren OS     | 1         | 0.85%   |
| Elementary   | 1         | 0.85%   |
| Deepin       | 1         | 0.85%   |
| Arch         | 1         | 0.85%   |
| Alpine       | 1         | 0.85%   |
| AlmaLinux    | 1         | 0.85%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                  | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003                  | 7         | 5.07%   |
| 5.4.0-42-generic                         | 4         | 2.9%    |
| 5.15.0-46-generic                        | 4         | 2.9%    |
| 5.4.0-73-generic                         | 3         | 2.17%   |
| 5.4.0-52-generic                         | 3         | 2.17%   |
| 5.3.0-40-generic                         | 3         | 2.17%   |
| 5.13.0-39-generic                        | 3         | 2.17%   |
| 5.10.14-desktop-1omv4002                 | 3         | 2.17%   |
| 5.10.0-13-amd64                          | 3         | 2.17%   |
| 4.9.20-nrj-desktop-1rosa-x86_64          | 3         | 2.17%   |
| 4.19.0-17-amd64                          | 3         | 2.17%   |
| 5.4.0-89-generic                         | 2         | 1.45%   |
| 5.4.0-77-generic                         | 2         | 1.45%   |
| 5.4.0-48-generic                         | 2         | 1.45%   |
| 5.4.0-107-generic                        | 2         | 1.45%   |
| 5.19.0-2-amd64                           | 2         | 1.45%   |
| 5.15.0-48-generic                        | 2         | 1.45%   |
| 5.15.0-43-generic                        | 2         | 1.45%   |
| 5.11.0-37-generic                        | 2         | 1.45%   |
| 5.10.0-18-amd64                          | 2         | 1.45%   |
| 5.10.0-11-amd64                          | 2         | 1.45%   |
| 5.0.0-37-generic                         | 2         | 1.45%   |
| 6.0.8-arch1-1                            | 1         | 0.72%   |
| 6.0.2-76060002-generic                   | 1         | 0.72%   |
| 5.9.0-5-amd64                            | 1         | 0.72%   |
| 5.8.6-1-MANJARO                          | 1         | 0.72%   |
| 5.8.0-63-generic                         | 1         | 0.72%   |
| 5.8.0-53-generic                         | 1         | 0.72%   |
| 5.8.0-45-generic                         | 1         | 0.72%   |
| 5.8.0-44-generic                         | 1         | 0.72%   |
| 5.8.0-41-generic                         | 1         | 0.72%   |
| 5.6.6-1-default                          | 1         | 0.72%   |
| 5.6.18-155.current                       | 1         | 0.72%   |
| 5.5.4-linux-xanmod-1-rosa-x86_64-xanmod3 | 1         | 0.72%   |
| 5.4.83-0-lts                             | 1         | 0.72%   |
| 5.4.105-1-MANJARO                        | 1         | 0.72%   |
| 5.4.0-91-generic                         | 1         | 0.72%   |
| 5.4.0-86-generic                         | 1         | 0.72%   |
| 5.4.0-70-generic                         | 1         | 0.72%   |
| 5.4.0-31-generic                         | 1         | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 20        | 15.63%  |
| 5.15.0  | 11        | 8.59%   |
| 5.10.0  | 11        | 8.59%   |
| 5.13.0  | 10        | 7.81%   |
| 4.19.0  | 8         | 6.25%   |
| 5.16.7  | 7         | 5.47%   |
| 5.11.0  | 6         | 4.69%   |
| 5.3.0   | 5         | 3.91%   |
| 5.8.0   | 4         | 3.13%   |
| 4.15.0  | 4         | 3.13%   |
| 5.10.14 | 3         | 2.34%   |
| 4.9.20  | 3         | 2.34%   |
| 5.19.0  | 2         | 1.56%   |
| 5.14.10 | 2         | 1.56%   |
| 5.0.0   | 2         | 1.56%   |
| 6.0.8   | 1         | 0.78%   |
| 6.0.2   | 1         | 0.78%   |
| 5.9.0   | 1         | 0.78%   |
| 5.8.6   | 1         | 0.78%   |
| 5.6.6   | 1         | 0.78%   |
| 5.6.18  | 1         | 0.78%   |
| 5.5.4   | 1         | 0.78%   |
| 5.4.83  | 1         | 0.78%   |
| 5.4.105 | 1         | 0.78%   |
| 5.18.0  | 1         | 0.78%   |
| 5.17.2  | 1         | 0.78%   |
| 5.17.15 | 1         | 0.78%   |
| 5.17.12 | 1         | 0.78%   |
| 5.17.11 | 1         | 0.78%   |
| 5.15.8  | 1         | 0.78%   |
| 5.15.65 | 1         | 0.78%   |
| 5.15.6  | 1         | 0.78%   |
| 5.15.46 | 1         | 0.78%   |
| 5.15.28 | 1         | 0.78%   |
| 5.15.2  | 1         | 0.78%   |
| 5.15.19 | 1         | 0.78%   |
| 5.15.13 | 1         | 0.78%   |
| 5.15.10 | 1         | 0.78%   |
| 5.13.13 | 1         | 0.78%   |
| 5.12.4  | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 22        | 17.46%  |
| 5.15    | 18        | 14.29%  |
| 5.10    | 17        | 13.49%  |
| 5.13    | 11        | 8.73%   |
| 4.19    | 8         | 6.35%   |
| 5.16    | 7         | 5.56%   |
| 5.11    | 6         | 4.76%   |
| 5.8     | 5         | 3.97%   |
| 5.3     | 5         | 3.97%   |
| 5.17    | 4         | 3.17%   |
| 4.15    | 4         | 3.17%   |
| 4.9     | 3         | 2.38%   |
| 6.0     | 2         | 1.59%   |
| 5.6     | 2         | 1.59%   |
| 5.19    | 2         | 1.59%   |
| 5.14    | 2         | 1.59%   |
| 5.12    | 2         | 1.59%   |
| 5.0     | 2         | 1.59%   |
| 5.9     | 1         | 0.79%   |
| 5.5     | 1         | 0.79%   |
| 5.18    | 1         | 0.79%   |
| 4.18    | 1         | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 101       | 90.18%  |
| i686   | 11        | 9.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 41        | 33.88%  |
| KDE5          | 26        | 21.49%  |
| XFCE          | 20        | 16.53%  |
| Unknown       | 8         | 6.61%   |
| KDE           | 6         | 4.96%   |
| X-Cinnamon    | 4         | 3.31%   |
| MATE          | 4         | 3.31%   |
| KDE4          | 3         | 2.48%   |
| Unity         | 2         | 1.65%   |
| Cinnamon      | 2         | 1.65%   |
| Pantheon      | 1         | 0.83%   |
| LXQt          | 1         | 0.83%   |
| GNOME Classic | 1         | 0.83%   |
| Deepin        | 1         | 0.83%   |
| Budgie        | 1         | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 100       | 87.72%  |
| Wayland | 13        | 11.4%   |
| Tty     | 1         | 0.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 47        | 39.17%  |
| SDDM    | 20        | 16.67%  |
| GDM     | 20        | 16.67%  |
| LightDM | 15        | 12.5%   |
| GDM3    | 12        | 10%     |
| TDM     | 3         | 2.5%    |
| KDM     | 3         | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_VE   | 68        | 57.63%  |
| en_US   | 33        | 27.97%  |
| es_ES   | 9         | 7.63%   |
| Unknown | 7         | 5.93%   |
| en_CA   | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 75        | 65.22%  |
| EFI  | 40        | 34.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 91        | 79.82%  |
| Overlay | 11        | 9.65%   |
| Btrfs   | 6         | 5.26%   |
| Xfs     | 3         | 2.63%   |
| Unknown | 3         | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 56        | 47.86%  |
| GPT     | 33        | 28.21%  |
| MBR     | 28        | 23.93%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 82.91%  |
| Yes       | 20        | 17.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 66.37%  |
| Yes       | 38        | 33.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Dell                           | 20        | 17.86%  |
| Lenovo                         | 19        | 16.96%  |
| VIT                            | 18        | 16.07%  |
| Hewlett-Packard                | 15        | 13.39%  |
| ASUSTek Computer               | 7         | 6.25%   |
| Intel                          | 6         | 5.36%   |
| Acer                           | 5         | 4.46%   |
| Unknown                        | 5         | 4.46%   |
| Toshiba                        | 2         | 1.79%   |
| Shanghai Zhaoxin Semiconductor | 2         | 1.79%   |
| Google                         | 2         | 1.79%   |
| UNIQCELL                       | 1         | 0.89%   |
| Sony                           | 1         | 0.89%   |
| Samsung Electronics            | 1         | 0.89%   |
| Pegatron                       | 1         | 0.89%   |
| MSI                            | 1         | 0.89%   |
| GPU Company                    | 1         | 0.89%   |
| Gateway                        | 1         | 0.89%   |
| Exo                            | 1         | 0.89%   |
| Clevo                          | 1         | 0.89%   |
| AVITA                          | 1         | 0.89%   |
| Alienware                      | 1         | 0.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Intel powered classmate PC          | 6         | 5.36%   |
| VIT P2400                           | 5         | 4.46%   |
| Unknown                             | 5         | 4.46%   |
| VIT P2402                           | 4         | 3.57%   |
| VIT P3400                           | 3         | 2.68%   |
| VIT M2420                           | 3         | 2.68%   |
| VIT M2421                           | 2         | 1.79%   |
| Shanghai Zhaoxin ZXE CRB            | 2         | 1.79%   |
| Lenovo IdeaPad S100c 20194          | 2         | 1.79%   |
| Lenovo 3000 N200 0769ARS            | 2         | 1.79%   |
| Dell Inspiron 1545                  | 2         | 1.79%   |
| VIT P1400                           | 1         | 0.89%   |
| UNIQCELL Q15.6                      | 1         | 0.89%   |
| Toshiba Satellite E55t-A            | 1         | 0.89%   |
| Toshiba ENCORE 2 WT8-B              | 1         | 0.89%   |
| Sony VGN-FW510F                     | 1         | 0.89%   |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 0.89%   |
| Pegatron T14AF                      | 1         | 0.89%   |
| MSI MS-1454                         | 1         | 0.89%   |
| Lenovo Z50-75 80EC                  | 1         | 0.89%   |
| Lenovo ThinkPad X201 3680AE2        | 1         | 0.89%   |
| Lenovo ThinkPad SL400 2743A48       | 1         | 0.89%   |
| Lenovo ThinkPad Edge 01962AS        | 1         | 0.89%   |
| Lenovo ThinkPad E560 20EV002FUS     | 1         | 0.89%   |
| Lenovo IdeaPad S110 20126           | 1         | 0.89%   |
| Lenovo IdeaPad 5 14ALC05 82LM       | 1         | 0.89%   |
| Lenovo IdeaPad 330-15ARR 81D2       | 1         | 0.89%   |
| Lenovo IdeaPad 3 15IIL05 81WE       | 1         | 0.89%   |
| Lenovo IdeaPad 1 14IGL05 81VU       | 1         | 0.89%   |
| Lenovo G570 4334                    | 1         | 0.89%   |
| Lenovo G480 20150                   | 1         | 0.89%   |
| Lenovo G460 20041                   | 1         | 0.89%   |
| Lenovo B40-70 20392                 | 1         | 0.89%   |
| Lenovo 3000 N500 42336DS            | 1         | 0.89%   |
| HP ProBook 440 G1                   | 1         | 0.89%   |
| HP Presario V2000 (EW997LA#ABM)     | 1         | 0.89%   |
| HP Presario C700                    | 1         | 0.89%   |
| HP Pavilion dv6700                  | 1         | 0.89%   |
| HP Pavilion dv6500                  | 1         | 0.89%   |
| HP Pavilion dv6000 (RV216UA#ABA)    | 1         | 0.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 11        | 9.82%   |
| Lenovo IdeaPad         | 7         | 6.25%   |
| Intel powered          | 6         | 5.36%   |
| HP Pavilion            | 6         | 5.36%   |
| VIT P2400              | 5         | 4.46%   |
| Unknown                | 5         | 4.46%   |
| VIT P2402              | 4         | 3.57%   |
| Lenovo ThinkPad        | 4         | 3.57%   |
| Dell Latitude          | 4         | 3.57%   |
| Acer Aspire            | 4         | 3.57%   |
| VIT P3400              | 3         | 2.68%   |
| VIT M2420              | 3         | 2.68%   |
| Lenovo 3000            | 3         | 2.68%   |
| Dell Vostro            | 3         | 2.68%   |
| VIT M2421              | 2         | 1.79%   |
| Shanghai Zhaoxin ZXE   | 2         | 1.79%   |
| HP Presario            | 2         | 1.79%   |
| HP EliteBook           | 2         | 1.79%   |
| ASUS VivoBook          | 2         | 1.79%   |
| ASUS ASUS              | 2         | 1.79%   |
| VIT P1400              | 1         | 0.89%   |
| UNIQCELL Q15.6         | 1         | 0.89%   |
| Toshiba Satellite      | 1         | 0.89%   |
| Toshiba ENCORE         | 1         | 0.89%   |
| Sony VGN-FW510F        | 1         | 0.89%   |
| Samsung 355V4C         | 1         | 0.89%   |
| Pegatron T14AF         | 1         | 0.89%   |
| MSI MS-1454            | 1         | 0.89%   |
| Lenovo Z50-75          | 1         | 0.89%   |
| Lenovo G570            | 1         | 0.89%   |
| Lenovo G480            | 1         | 0.89%   |
| Lenovo G460            | 1         | 0.89%   |
| Lenovo B40-70          | 1         | 0.89%   |
| HP ProBook             | 1         | 0.89%   |
| HP Mini                | 1         | 0.89%   |
| HP Laptop              | 1         | 0.89%   |
| HP Compaq              | 1         | 0.89%   |
| HP 2000                | 1         | 0.89%   |
| GPU Company GWTN156-11 | 1         | 0.89%   |
| Google Cyan            | 1         | 0.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 15        | 13.39%  |
| 2013    | 14        | 12.5%   |
| 2012    | 11        | 9.82%   |
| 2010    | 8         | 7.14%   |
| 2007    | 8         | 7.14%   |
| 2020    | 7         | 6.25%   |
| 2018    | 7         | 6.25%   |
| 2014    | 7         | 6.25%   |
| 2008    | 6         | 5.36%   |
| 2022    | 5         | 4.46%   |
| 2021    | 5         | 4.46%   |
| 2009    | 5         | 4.46%   |
| 2017    | 4         | 3.57%   |
| 2015    | 4         | 3.57%   |
| 2019    | 3         | 2.68%   |
| 2016    | 1         | 0.89%   |
| 2006    | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 112       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 108       | 96.43%  |
| Enabled  | 4         | 3.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 98.21%  |
| Yes  | 2         | 1.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 31        | 27.43%  |
| 4.01-8.0   | 25        | 22.12%  |
| 1.01-2.0   | 24        | 21.24%  |
| 8.01-16.0  | 15        | 13.27%  |
| 16.01-24.0 | 8         | 7.08%   |
| 2.01-3.0   | 6         | 5.31%   |
| 32.01-64.0 | 2         | 1.77%   |
| 24.01-32.0 | 1         | 0.88%   |
| 0.51-1.0   | 1         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 49        | 39.2%   |
| 2.01-3.0   | 29        | 23.2%   |
| 0.51-1.0   | 20        | 16%     |
| 4.01-8.0   | 14        | 11.2%   |
| 3.01-4.0   | 10        | 8%      |
| 8.01-16.0  | 2         | 1.6%    |
| 16.01-24.0 | 1         | 0.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 79        | 68.7%   |
| 2      | 32        | 27.83%  |
| 3      | 4         | 3.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 52.68%  |
| No        | 53        | 47.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 85.84%  |
| No        | 16        | 14.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 97.32%  |
| No        | 3         | 2.68%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 53.98%  |
| No        | 52        | 46.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Venezuela | 112       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 50        | 41.32%  |
| Maracaibo                  | 14        | 11.57%  |
| Maracay                    | 7         | 5.79%   |
| Mérida                    | 6         | 4.96%   |
| Barquisimeto               | 4         | 3.31%   |
| Barcelona                  | 4         | 3.31%   |
| Valencia                   | 3         | 2.48%   |
| San Carlos del Zulia       | 2         | 1.65%   |
| Maturín                   | 2         | 1.65%   |
| Lecherias                  | 2         | 1.65%   |
| Anaco                      | 2         | 1.65%   |
| Tucape                     | 1         | 0.83%   |
| San Juan Bautista          | 1         | 0.83%   |
| San Felipe                 | 1         | 0.83%   |
| San Diego                  | 1         | 0.83%   |
| San Cristóbal             | 1         | 0.83%   |
| Puerto Ordaz and San Felix | 1         | 0.83%   |
| Puerto Cumarebo            | 1         | 0.83%   |
| Puerto Cruz                | 1         | 0.83%   |
| Porlamar                   | 1         | 0.83%   |
| Parroquia El Recreo        | 1         | 0.83%   |
| Naguanagua                 | 1         | 0.83%   |
| Mariara                    | 1         | 0.83%   |
| Los Palos Grandes          | 1         | 0.83%   |
| Las Vegas                  | 1         | 0.83%   |
| Guatire                    | 1         | 0.83%   |
| Guarenas                   | 1         | 0.83%   |
| Guanare                    | 1         | 0.83%   |
| El Hatillo Municipality    | 1         | 0.83%   |
| Ejido                      | 1         | 0.83%   |
| Ciudad Guayana             | 1         | 0.83%   |
| Ciudad Bolívar            | 1         | 0.83%   |
| Charallave                 | 1         | 0.83%   |
| Cagua                      | 1         | 0.83%   |
| Barinas                    | 1         | 0.83%   |
| Acarigua                   | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 30     | 21.37%  |
| WDC                 | 24        | 33     | 18.32%  |
| Toshiba             | 13        | 13     | 9.92%   |
| Unknown             | 9         | 13     | 6.87%   |
| Samsung Electronics | 7         | 7      | 5.34%   |
| Hitachi             | 7         | 7      | 5.34%   |
| Crucial             | 5         | 7      | 3.82%   |
| SanDisk             | 4         | 6      | 3.05%   |
| LITEONIT            | 4         | 7      | 3.05%   |
| Intel               | 4         | 7      | 3.05%   |
| Kingston            | 3         | 5      | 2.29%   |
| HGST                | 3         | 3      | 2.29%   |
| SPCC                | 2         | 3      | 1.53%   |
| SK hynix            | 2         | 3      | 1.53%   |
| PNY                 | 2         | 2      | 1.53%   |
| Fujitsu             | 2         | 2      | 1.53%   |
| Vaseky              | 1         | 1      | 0.76%   |
| Silicon Motion      | 1         | 1      | 0.76%   |
| PUSKILL             | 1         | 1      | 0.76%   |
| Phison              | 1         | 1      | 0.76%   |
| Micron Technology   | 1         | 3      | 0.76%   |
| Lexar               | 1         | 1      | 0.76%   |
| KingFast            | 1         | 2      | 0.76%   |
| Intenso             | 1         | 1      | 0.76%   |
| Dell                | 1         | 2      | 0.76%   |
| BIWIN               | 1         | 2      | 0.76%   |
| Apacer              | 1         | 1      | 0.76%   |
| addlink             | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB      | 4         | 2.96%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 3         | 2.22%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 2.22%   |
| Seagate ST250LM004 HN-M250MBB 250GB  | 3         | 2.22%   |
| LITEONIT LMS-32L6M 32GB SSD          | 3         | 2.22%   |
| WDC WD5000LPVT-08G33T1 500GB         | 2         | 1.48%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 1.48%   |
| Unknown NVMe SSD Drive 512GB         | 2         | 1.48%   |
| Unknown MMC Card  16GB               | 2         | 1.48%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.48%   |
| Toshiba MQ01ABF032 320GB             | 2         | 1.48%   |
| Toshiba MQ01ABD050 500GB             | 2         | 1.48%   |
| Toshiba MK3275GSX 320GB              | 2         | 1.48%   |
| Seagate ST320LT012-9WS14C 320GB      | 2         | 1.48%   |
| Seagate ST320LT012-1DG14C 320GB      | 2         | 1.48%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 2         | 1.48%   |
| Seagate ST320LM000 HM321HI 320GB     | 2         | 1.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.48%   |
| SanDisk NVMe SSD Drive 1TB           | 2         | 1.48%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.48%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 1.48%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.74%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.74%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.74%   |
| WDC WD3200LPVX-22V0TT0 320GB         | 1         | 0.74%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 0.74%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.74%   |
| WDC WD3200BEVT-00A0RT0 320GB         | 1         | 0.74%   |
| WDC WD3200BEKT-60F3T1 320GB          | 1         | 0.74%   |
| WDC WD1600BEVT-88ZCT0 160GB          | 1         | 0.74%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 0.74%   |
| WDC WD1600BEVS-22RST0 160GB          | 1         | 0.74%   |
| WDC WD1200BEVS-60UST0 120GB          | 1         | 0.74%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.74%   |
| WDC PC SN520 SDAPNUW-256G-1014 256GB | 1         | 0.74%   |
| Vaseky V800/128G 128GB SSD           | 1         | 0.74%   |
| Unknown USDU1  32GB                  | 1         | 0.74%   |
| Unknown SD/MMC/MS PRO 8GB            | 1         | 0.74%   |
| Unknown SC64G  64GB                  | 1         | 0.74%   |
| Unknown MMC128  128GB                | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 28     | 34.21%  |
| WDC                 | 22        | 29     | 28.95%  |
| Toshiba             | 12        | 12     | 15.79%  |
| Hitachi             | 7         | 7      | 9.21%   |
| HGST                | 3         | 3      | 3.95%   |
| Unknown             | 2         | 2      | 2.63%   |
| Samsung Electronics | 2         | 2      | 2.63%   |
| Fujitsu             | 2         | 2      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 5         | 7      | 16.67%  |
| LITEONIT            | 4         | 7      | 13.33%  |
| Samsung Electronics | 3         | 3      | 10%     |
| SPCC                | 2         | 3      | 6.67%   |
| SanDisk             | 2         | 3      | 6.67%   |
| PNY                 | 2         | 2      | 6.67%   |
| Kingston            | 2         | 4      | 6.67%   |
| Vaseky              | 1         | 1      | 3.33%   |
| Toshiba             | 1         | 1      | 3.33%   |
| PUSKILL             | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 3      | 3.33%   |
| Lexar               | 1         | 1      | 3.33%   |
| KingFast            | 1         | 2      | 3.33%   |
| Intenso             | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| Dell                | 1         | 2      | 3.33%   |
| BIWIN               | 1         | 2      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 74        | 85     | 58.27%  |
| SSD     | 29        | 44     | 22.83%  |
| NVMe    | 16        | 25     | 12.6%   |
| MMC     | 6         | 9      | 4.72%   |
| Unknown | 2         | 2      | 1.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 94        | 127    | 78.33%  |
| NVMe | 16        | 25     | 13.33%  |
| MMC  | 6         | 9      | 5%      |
| SAS  | 4         | 4      | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 82        | 103    | 81.19%  |
| 0.51-1.0   | 18        | 25     | 17.82%  |
| 1.01-2.0   | 1         | 1      | 0.99%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 35        | 29.17%  |
| 101-250    | 29        | 24.17%  |
| 501-1000   | 20        | 16.67%  |
| 1-20       | 12        | 10%     |
| 21-50      | 10        | 8.33%   |
| 51-100     | 8         | 6.67%   |
| 1001-2000  | 4         | 3.33%   |
| 2001-3000  | 1         | 0.83%   |
| Unknown    | 1         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 48        | 38.1%   |
| 21-50    | 26        | 20.63%  |
| 101-250  | 19        | 15.08%  |
| 51-100   | 15        | 11.9%   |
| 251-500  | 10        | 7.94%   |
| 501-1000 | 7         | 5.56%   |
| Unknown  | 1         | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 1      | 5%      |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 5%      |
| WDC WD1200BEVS-60UST0 120GB          | 1         | 1      | 5%      |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2      | 5%      |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 5%      |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 5%      |
| Toshiba MK3275GSX 320GB              | 1         | 1      | 5%      |
| Seagate ST9500325AS 500GB            | 1         | 1      | 5%      |
| Seagate ST9320325AS 320GB            | 1         | 1      | 5%      |
| Seagate ST9160314AS 160GB            | 1         | 1      | 5%      |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 5%      |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 5%      |
| Samsung Electronics HN-M320MBB 320GB | 1         | 1      | 5%      |
| Samsung Electronics HM250HI 250GB    | 1         | 1      | 5%      |
| Intel SSDPEKKW256G7 256GB            | 1         | 1      | 5%      |
| Hitachi HTS725050A9A364 500GB        | 1         | 1      | 5%      |
| Hitachi HTS543232L9A300 320GB        | 1         | 1      | 5%      |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1      | 5%      |
| Hitachi HTS542525K9SA00 250GB        | 1         | 1      | 5%      |
| HGST HTS541010A7E630 1TB             | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 25%     |
| WDC                 | 4         | 5      | 20%     |
| Hitachi             | 4         | 4      | 20%     |
| Toshiba             | 3         | 3      | 15%     |
| Samsung Electronics | 2         | 2      | 10%     |
| Intel               | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 26.32%  |
| WDC                 | 4         | 5      | 21.05%  |
| Hitachi             | 4         | 4      | 21.05%  |
| Toshiba             | 3         | 3      | 15.79%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| HGST                | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 20     | 95%     |
| NVMe | 1         | 1      | 5%      |

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
| Detected | 64        | 94     | 52.46%  |
| Works    | 38        | 50     | 31.15%  |
| Malfunc  | 20        | 21     | 16.39%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 91        | 77.78%  |
| AMD                         | 13        | 11.11%  |
| SanDisk                     | 3         | 2.56%   |
| SK hynix                    | 2         | 1.71%   |
| Samsung Electronics         | 2         | 1.71%   |
| Phison Electronics          | 2         | 1.71%   |
| Unknown                     | 2         | 1.71%   |
| Silicon Motion              | 1         | 0.85%   |
| Kingston Technology Company | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 17        | 13.08%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 8.46%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 8.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 6.15%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 6         | 4.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 4.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 4.62%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 4.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 3.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 3.08%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.31%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 2.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 2.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.31%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.54%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.54%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.54%   |
| Unknown                                                                        | 2         | 1.54%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 0.77%   |
| SK hynix BC511                                                                 | 1         | 0.77%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.77%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.77%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.77%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.77%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.77%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.77%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.77%   |
| Intel SSD 600P Series                                                          | 1         | 0.77%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.77%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 0.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 0.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 85        | 68%     |
| NVMe | 16        | 12.8%   |
| IDE  | 13        | 10.4%   |
| RAID | 11        | 8.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 96        | 85.71%  |
| AMD          | 14        | 12.5%   |
| CentaurHauls | 2         | 1.79%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz                | 4         | 3.57%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 4         | 3.57%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 3         | 2.68%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 3         | 2.68%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 3         | 2.68%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 1.79%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 2         | 1.79%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 2         | 1.79%   |
| Intel Core i5-3337U CPU @ 1.80GHz              | 2         | 1.79%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 1.79%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 2         | 1.79%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 2         | 1.79%   |
| Intel Core i3-4000M CPU @ 2.40GHz              | 2         | 1.79%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 2         | 1.79%   |
| Intel Core i3-2350M CPU @ 2.30GHz              | 2         | 1.79%   |
| Intel Core i3 CPU M 330 @ 2.13GHz              | 2         | 1.79%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz           | 2         | 1.79%   |
| Intel Celeron CPU N2805 @ 1.46GHz              | 2         | 1.79%   |
| Intel Atom CPU N570 @ 1.66GHz                  | 2         | 1.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 1.79%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 2         | 1.79%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 0.89%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz         | 1         | 0.89%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 1         | 0.89%   |
| Intel Pentium CPU 2030M @ 2.50GHz              | 1         | 0.89%   |
| Intel Genuine CPU U7300 @ 1.30GHz              | 1         | 0.89%   |
| Intel Genuine CPU T2080 @ 1.73GHz              | 1         | 0.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 1         | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 1         | 0.89%   |
| Intel Core i7-7820HK CPU @ 2.90GHz             | 1         | 0.89%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz             | 1         | 0.89%   |
| Intel Core i7-5600U CPU @ 2.60GHz              | 1         | 0.89%   |
| Intel Core i7-4500U CPU @ 1.80GHz              | 1         | 0.89%   |
| Intel Core i7-3632QM CPU @ 2.20GHz             | 1         | 0.89%   |
| Intel Core i7-3537U CPU @ 2.00GHz              | 1         | 0.89%   |
| Intel Core i7-2640M CPU @ 2.80GHz              | 1         | 0.89%   |
| Intel Core i7-2620M CPU @ 2.70GHz              | 1         | 0.89%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz               | 1         | 0.89%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz             | 1         | 0.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 1         | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 20        | 17.86%  |
| Intel Core i3                  | 20        | 17.86%  |
| Intel Celeron                  | 12        | 10.71%  |
| Intel Core 2 Duo               | 11        | 9.82%   |
| Intel Core i7                  | 10        | 8.93%   |
| Intel Atom                     | 9         | 8.04%   |
| Other                          | 6         | 5.36%   |
| AMD Ryzen 5                    | 5         | 4.46%   |
| Intel Pentium                  | 3         | 2.68%   |
| Intel Pentium Dual-Core        | 2         | 1.79%   |
| Intel Pentium Dual             | 2         | 1.79%   |
| Intel Genuine                  | 2         | 1.79%   |
| AMD A10                        | 2         | 1.79%   |
| Intel Pentium Silver           | 1         | 0.89%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.89%   |
| AMD Ryzen 7                    | 1         | 0.89%   |
| AMD Ryzen 3                    | 1         | 0.89%   |
| AMD Mobile Sempron             | 1         | 0.89%   |
| AMD E1                         | 1         | 0.89%   |
| AMD E                          | 1         | 0.89%   |
| AMD A6                         | 1         | 0.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 81        | 72.32%  |
| 4       | 17        | 15.18%  |
| 1       | 6         | 5.36%   |
| 6       | 4         | 3.57%   |
| 8       | 2         | 1.79%   |
| Unknown | 2         | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 112       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 69        | 61.61%  |
| 1       | 41        | 36.61%  |
| Unknown | 2         | 1.79%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 106       | 94.64%  |
| 64-bit         | 3         | 2.68%   |
| 32-bit         | 3         | 2.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 18.8%   |
| 0x306a9    | 13        | 11.11%  |
| 0x206a7    | 13        | 11.11%  |
| 0x1067a    | 9         | 7.69%   |
| 0x6fd      | 6         | 5.13%   |
| 0x806e9    | 5         | 4.27%   |
| 0x106ca    | 5         | 4.27%   |
| 0x806c1    | 3         | 2.56%   |
| 0x40651    | 3         | 2.56%   |
| 0x30678    | 3         | 2.56%   |
| 0x20655    | 3         | 2.56%   |
| 0x406e3    | 2         | 1.71%   |
| 0x306d4    | 2         | 1.71%   |
| 0x306c3    | 2         | 1.71%   |
| 0x30673    | 2         | 1.71%   |
| 0x08608103 | 2         | 1.71%   |
| 0x05000119 | 2         | 1.71%   |
| 0x906e9    | 1         | 0.85%   |
| 0x806ea    | 1         | 0.85%   |
| 0x806d1    | 1         | 0.85%   |
| 0x706e5    | 1         | 0.85%   |
| 0x706a8    | 1         | 0.85%   |
| 0x6ec      | 1         | 0.85%   |
| 0x506e3    | 1         | 0.85%   |
| 0x406c4    | 1         | 0.85%   |
| 0x30661    | 1         | 0.85%   |
| 0x20652    | 1         | 0.85%   |
| 0x106c2    | 1         | 0.85%   |
| 0x08600103 | 1         | 0.85%   |
| 0x08600102 | 1         | 0.85%   |
| 0x08108102 | 1         | 0.85%   |
| 0x0810100b | 1         | 0.85%   |
| 0x08101007 | 1         | 0.85%   |
| 0x06006704 | 1         | 0.85%   |
| 0x06006118 | 1         | 0.85%   |
| 0x06003106 | 1         | 0.85%   |
| 0x02000057 | 1         | 0.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 17        | 15.18%  |
| IvyBridge       | 14        | 12.5%   |
| KabyLake        | 9         | 8.04%   |
| Penryn          | 8         | 7.14%   |
| Core            | 8         | 7.14%   |
| Bonnell         | 8         | 7.14%   |
| Westmere        | 7         | 6.25%   |
| Silvermont      | 6         | 5.36%   |
| Haswell         | 5         | 4.46%   |
| Unknown         | 4         | 3.57%   |
| TigerLake       | 3         | 2.68%   |
| Skylake         | 3         | 2.68%   |
| Zen 2           | 2         | 1.79%   |
| Zen             | 2         | 1.79%   |
| Icelake         | 2         | 1.79%   |
| Goldmont plus   | 2         | 1.79%   |
| Excavator       | 2         | 1.79%   |
| Broadwell       | 2         | 1.79%   |
| Bobcat          | 2         | 1.79%   |
| Zen+            | 1         | 0.89%   |
| Steamroller     | 1         | 0.89%   |
| P6              | 1         | 0.89%   |
| K8 Hammer       | 1         | 0.89%   |
| K8 & K10 hybrid | 1         | 0.89%   |
| Goldmont        | 1         | 0.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 94        | 78.33%  |
| AMD     | 16        | 13.33%  |
| Nvidia  | 8         | 6.67%   |
| Zhaoxin | 2         | 1.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 12.4%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 10.85%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 6.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 5.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 5.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 5.43%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 4.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 3.88%   |
| Intel HD Graphics 620                                                                    | 4         | 3.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.33%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 2         | 1.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.55%   |
| Intel HD Graphics 630                                                                    | 2         | 1.55%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.55%   |
| AMD Renoir                                                                               | 2         | 1.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.55%   |
| AMD Lucienne                                                                             | 2         | 1.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.78%   |
| Nvidia TU117M                                                                            | 1         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.78%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.78%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 0.78%   |
| Nvidia GF104GLM [Quadro 3000M]                                                           | 1         | 0.78%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.78%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.78%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.78%   |
| Intel HD Graphics 615                                                                    | 1         | 0.78%   |
| Intel HD Graphics 530                                                                    | 1         | 0.78%   |
| Intel HD Graphics 500                                                                    | 1         | 0.78%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 87        | 77.68%  |
| 1 x AMD        | 14        | 12.5%   |
| Intel + Nvidia | 5         | 4.46%   |
| 1 x Zhaoxin    | 2         | 1.79%   |
| 1 x Nvidia     | 2         | 1.79%   |
| Intel + AMD    | 1         | 0.89%   |
| AMD + Nvidia   | 1         | 0.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 102       | 91.07%  |
| Proprietary | 6         | 5.36%   |
| Unknown     | 4         | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 78.95%  |
| 0.01-0.5   | 14        | 12.28%  |
| 1.01-2.0   | 5         | 4.39%   |
| 3.01-4.0   | 3         | 2.63%   |
| 0.51-1.0   | 2         | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 18        | 14.88%  |
| BOE                     | 17        | 14.05%  |
| LG Display              | 16        | 13.22%  |
| AU Optronics            | 15        | 12.4%   |
| Chimei Innolux          | 11        | 9.09%   |
| Chi Mei Optoelectronics | 7         | 5.79%   |
| LG Philips              | 5         | 4.13%   |
| Lenovo                  | 5         | 4.13%   |
| InfoVision              | 5         | 4.13%   |
| HannStar                | 4         | 3.31%   |
| Hewlett-Packard         | 3         | 2.48%   |
| Goldstar                | 3         | 2.48%   |
| PANDA                   | 2         | 1.65%   |
| Dell                    | 2         | 1.65%   |
| Vizio                   | 1         | 0.83%   |
| ViewSonic               | 1         | 0.83%   |
| Sharp                   | 1         | 0.83%   |
| MStar                   | 1         | 0.83%   |
| KTC                     | 1         | 0.83%   |
| InnoLux Display         | 1         | 0.83%   |
| ASUSTek Computer        | 1         | 0.83%   |
| Acer                    | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 4         | 3.31%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch       | 4         | 3.31%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch              | 3         | 2.48%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                  | 3         | 2.48%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch         | 3         | 2.48%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 1.65%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.65%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 2         | 1.65%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch           | 2         | 1.65%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch           | 2         | 1.65%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                  | 2         | 1.65%   |
| Vizio E322AR VIZ0079 1360x768 700x400mm 31.7-inch                     | 1         | 0.83%   |
| ViewSonic VA2252 SERIES VSC7731 1920x1080 476x268mm 21.5-inch         | 1         | 0.83%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.83%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch     | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.83%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC8151 1920x1080 382x214mm 17.2-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch  | 1         | 0.83%   |
| MStar Demo MST0030 1920x1080 1150x650mm 52.0-inch                     | 1         | 0.83%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch         | 1         | 0.83%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 0.83%   |
| LG Philips LCD Monitor LPL3101 1280x800 330x210mm 15.4-inch           | 1         | 0.83%   |
| LG Philips LCD Monitor LPL0701 1280x800 331x207mm 15.4-inch           | 1         | 0.83%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.83%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch         | 1         | 0.83%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0550 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD04B7 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0383 1600x900 380x210mm 17.1-inch           | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 64        | 56.64%  |
| 1920x1080 (FHD)   | 22        | 19.47%  |
| 1280x800 (WXGA)   | 11        | 9.73%   |
| 3840x2160 (4K)    | 3         | 2.65%   |
| 1360x768          | 3         | 2.65%   |
| 1024x600          | 3         | 2.65%   |
| 1600x900 (HD+)    | 2         | 1.77%   |
| 1280x1024 (SXGA)  | 2         | 1.77%   |
| 2560x1440 (QHD)   | 1         | 0.88%   |
| 1920x1200 (WUXGA) | 1         | 0.88%   |
| 1440x900 (WXGA+)  | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 43        | 35.83%  |
| 14     | 24        | 20%     |
| 13     | 20        | 16.67%  |
| 10     | 6         | 5%      |
| 21     | 5         | 4.17%   |
| 17     | 5         | 4.17%   |
| 11     | 4         | 3.33%   |
| 18     | 3         | 2.5%    |
| 27     | 2         | 1.67%   |
| 54     | 1         | 0.83%   |
| 52     | 1         | 0.83%   |
| 32     | 1         | 0.83%   |
| 31     | 1         | 0.83%   |
| 24     | 1         | 0.83%   |
| 23     | 1         | 0.83%   |
| 19     | 1         | 0.83%   |
| 12     | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 85        | 71.43%  |
| 201-300     | 12        | 10.08%  |
| 401-500     | 8         | 6.72%   |
| 351-400     | 6         | 5.04%   |
| 501-600     | 4         | 3.36%   |
| 1001-1500   | 2         | 1.68%   |
| 701-800     | 1         | 0.84%   |
| 601-700     | 1         | 0.84%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 90        | 84.91%  |
| 16/10 | 13        | 12.26%  |
| 5/4   | 2         | 1.89%   |
| 3/2   | 1         | 0.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 43        | 35.83%  |
| 101-110        | 43        | 35.83%  |
| 41-50          | 6         | 5%      |
| 201-250        | 5         | 4.17%   |
| 51-60          | 4         | 3.33%   |
| 141-150        | 4         | 3.33%   |
| 121-130        | 4         | 3.33%   |
| More than 1000 | 2         | 1.67%   |
| 351-500        | 2         | 1.67%   |
| 301-350        | 2         | 1.67%   |
| 151-200        | 2         | 1.67%   |
| 71-80          | 1         | 0.83%   |
| 61-70          | 1         | 0.83%   |
| 251-300        | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 57        | 48.31%  |
| 121-160       | 29        | 24.58%  |
| 51-100        | 25        | 21.19%  |
| 1-50          | 4         | 3.39%   |
| 161-240       | 2         | 1.69%   |
| More than 240 | 1         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 95        | 83.33%  |
| 2     | 14        | 12.28%  |
| 0     | 3         | 2.63%   |
| 3     | 2         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 74        | 40.66%  |
| Qualcomm Atheros                | 39        | 21.43%  |
| Intel                           | 37        | 20.33%  |
| Broadcom                        | 13        | 7.14%   |
| Broadcom Limited                | 5         | 2.75%   |
| Marvell Technology Group        | 3         | 1.65%   |
| Xiaomi                          | 2         | 1.1%    |
| Samsung Electronics             | 2         | 1.1%    |
| JMicron Technology              | 2         | 1.1%    |
| Trendchip Technologies          | 1         | 0.55%   |
| Ralink Technology               | 1         | 0.55%   |
| Qualcomm Atheros Communications | 1         | 0.55%   |
| MediaTek                        | 1         | 0.55%   |
| AMD                             | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 37        | 17.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 18        | 8.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 5.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 3.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.29%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 6         | 2.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 5         | 2.35%   |
| Intel Wireless 7265                                                     | 5         | 2.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.88%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 1.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.41%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.41%   |
| Intel Wireless 7260                                                     | 3         | 1.41%   |
| Intel Centrino Wireless-N 105                                           | 3         | 1.41%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.94%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 0.94%   |
| Intel Wireless 8260                                                     | 2         | 0.94%   |
| Intel Wireless 3165                                                     | 2         | 0.94%   |
| Intel WiFi Link 5100                                                    | 2         | 0.94%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.94%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.94%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.94%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 0.94%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express             | 2         | 0.94%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.47%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                       | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 31.86%  |
| Realtek Semiconductor           | 30        | 26.55%  |
| Qualcomm Atheros                | 30        | 26.55%  |
| Broadcom                        | 11        | 9.73%   |
| Broadcom Limited                | 2         | 1.77%   |
| Xiaomi                          | 1         | 0.88%   |
| Ralink Technology               | 1         | 0.88%   |
| Qualcomm Atheros Communications | 1         | 0.88%   |
| MediaTek                        | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 10.62%  |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 7.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 6.19%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 6         | 5.31%   |
| Intel Wireless 7265                                                     | 5         | 4.42%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 3.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 3.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 3.54%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 3.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 2.65%   |
| Intel Wireless 8265 / 8275                                              | 3         | 2.65%   |
| Intel Wireless 7260                                                     | 3         | 2.65%   |
| Intel Centrino Wireless-N 105                                           | 3         | 2.65%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 2.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.77%   |
| Intel Wireless 8260                                                     | 2         | 1.77%   |
| Intel Wireless 3165                                                     | 2         | 1.77%   |
| Intel WiFi Link 5100                                                    | 2         | 1.77%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.77%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.77%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.77%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.77%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.77%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 1.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.77%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                       | 1         | 0.88%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.88%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.88%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 0.88%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.88%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.88%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.88%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 60        | 61.22%  |
| Qualcomm Atheros         | 13        | 13.27%  |
| Intel                    | 10        | 10.2%   |
| Marvell Technology Group | 3         | 3.06%   |
| Broadcom Limited         | 3         | 3.06%   |
| Broadcom                 | 3         | 3.06%   |
| Samsung Electronics      | 2         | 2.04%   |
| JMicron Technology       | 2         | 2.04%   |
| Xiaomi                   | 1         | 1.02%   |
| Trendchip Technologies   | 1         | 1.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 37.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 18.18%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 5.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 3.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 3.03%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.02%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 2.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.02%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 2         | 2.02%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.01%   |
| Trendchip Ethernet controller                                     | 1         | 1.01%   |
| Realtek Realtek Ethernet controller                               | 1         | 1.01%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.01%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.01%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.01%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.01%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.01%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.01%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 1.01%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.01%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.01%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.01%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.01%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.01%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.01%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.01%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 109       | 52.91%  |
| Ethernet | 96        | 46.6%   |
| Modem    | 1         | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 84        | 71.19%  |
| Ethernet | 34        | 28.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 89        | 79.46%  |
| 1     | 21        | 18.75%  |
| 0     | 2         | 1.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 112       | 99.12%  |
| Yes  | 1         | 0.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 37.7%   |
| Qualcomm Atheros Communications | 11        | 18.03%  |
| IMC Networks                    | 10        | 16.39%  |
| Realtek Semiconductor           | 6         | 9.84%   |
| Broadcom                        | 4         | 6.56%   |
| Cambridge Silicon Radio         | 3         | 4.92%   |
| Hewlett-Packard                 | 2         | 3.28%   |
| Lite-On Technology              | 1         | 1.64%   |
| ASUSTek Computer                | 1         | 1.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 15        | 24.59%  |
| Qualcomm Atheros  Bluetooth Device                          | 5         | 8.2%    |
| IMC Networks Bluetooth                                      | 4         | 6.56%   |
| Realtek RTL8723B Bluetooth                                  | 3         | 4.92%   |
| Realtek Bluetooth Radio                                     | 3         | 4.92%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 3         | 4.92%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 3         | 4.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 4.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 3.28%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 3.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 3.28%   |
| Intel AX201 Bluetooth                                       | 2         | 3.28%   |
| IMC Networks Bluetooth Radio                                | 2         | 3.28%   |
| Broadcom BCM2045 Bluetooth                                  | 2         | 3.28%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 1.64%   |
| Lite-On Bluetooth Device                                    | 1         | 1.64%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.64%   |
| Intel AX200 Bluetooth                                       | 1         | 1.64%   |
| IMC Networks Wireless_Device                                | 1         | 1.64%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 1.64%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.64%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.64%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.64%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 96        | 79.34%  |
| AMD                   | 15        | 12.4%   |
| Nvidia                | 5         | 4.13%   |
| Zhaoxin               | 2         | 1.65%   |
| Realtek Semiconductor | 1         | 0.83%   |
| Microsoft             | 1         | 0.83%   |
| Logitech              | 1         | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 13.99%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 7.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 6.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 6.29%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 5.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 4.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 4.9%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 4.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.1%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.1%    |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.1%    |
| AMD FCH Azalia Controller                                                                         | 3         | 2.1%    |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 2         | 1.4%    |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                                         | 2         | 1.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.4%    |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.4%    |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.4%    |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.4%    |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.7%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.7%    |
| Nvidia GF104 High Definition Audio Controller                                                     | 1         | 0.7%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.7%    |
| Nvidia Audio device                                                                               | 1         | 0.7%    |
| Microsoft LifeChat LX-4000                                                                        | 1         | 0.7%    |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.7%    |
| Intel USB PnP Sound Device                                                                        | 1         | 0.7%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 20        | 21.28%  |
| Samsung Electronics | 15        | 15.96%  |
| Unknown             | 14        | 14.89%  |
| Ramaxel Technology  | 11        | 11.7%   |
| Micron Technology   | 9         | 9.57%   |
| Kingston            | 5         | 5.32%   |
| Crucial             | 5         | 5.32%   |
| Elpida              | 4         | 4.26%   |
| Unknown (ABCD)      | 2         | 2.13%   |
| Shenzhen WODPOSIT   | 2         | 2.13%   |
| Unknown             | 2         | 2.13%   |
| Unknown (081A)      | 1         | 1.06%   |
| Qimonda             | 1         | 1.06%   |
| Memox               | 1         | 1.06%   |
| Corsair             | 1         | 1.06%   |
| A-DATA Technology   | 1         | 1.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 3         | 3%      |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s          | 3         | 3%      |
| Ramaxel RAM RMT3010EC58E8F1333 2048MB SODIMM DDR3 1600MT/s       | 3         | 3%      |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 2%      |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 2%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2%      |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 2         | 2%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2%      |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s            | 2         | 2%      |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 2         | 2%      |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 2%      |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 2%      |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s         | 2         | 2%      |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s          | 2         | 2%      |
| Unknown                                                          | 2         | 2%      |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1%      |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 1%      |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1%      |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1%      |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 1%      |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1%      |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1%      |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                        | 1         | 1%      |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 1%      |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1%      |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 1%      |
| Unknown RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 1         | 1%      |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 1%      |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 1%      |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1%      |
| Unknown (081A) RAM HXMSH2GS03A2F1CL16 2GB SODIMM DDR3 1600MT/s   | 1         | 1%      |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 800MT/s          | 1         | 1%      |
| SK hynix RAM HMT451S6BFR8A-RD 4GB SODIMM DDR3 1867MT/s           | 1         | 1%      |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1%      |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1%      |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 1%      |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1%      |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1%      |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 29        | 40.85%  |
| DDR4   | 22        | 30.99%  |
| DDR2   | 11        | 15.49%  |
| SDRAM  | 5         | 7.04%   |
| LPDDR4 | 3         | 4.23%   |
| DDR    | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 65        | 95.59%  |
| Row Of Chips | 2         | 2.94%   |
| DIMM         | 1         | 1.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 27        | 32.93%  |
| 8192  | 24        | 29.27%  |
| 4096  | 22        | 26.83%  |
| 1024  | 5         | 6.1%    |
| 16384 | 4         | 4.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 25        | 30.86%  |
| 2667    | 9         | 11.11%  |
| 2400    | 7         | 8.64%   |
| 3200    | 6         | 7.41%   |
| 667     | 6         | 7.41%   |
| 1333    | 5         | 6.17%   |
| 1334    | 4         | 4.94%   |
| Unknown | 3         | 3.7%    |
| 4199    | 2         | 2.47%   |
| 2666    | 2         | 2.47%   |
| 2048    | 2         | 2.47%   |
| 1067    | 2         | 2.47%   |
| 533     | 2         | 2.47%   |
| 3266    | 1         | 1.23%   |
| 2133    | 1         | 1.23%   |
| 1867    | 1         | 1.23%   |
| 1066    | 1         | 1.23%   |
| 975     | 1         | 1.23%   |
| 800     | 1         | 1.23%   |

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
| Chicony Electronics                    | 19        | 21.84%  |
| Microdia                               | 13        | 14.94%  |
| Acer                                   | 11        | 12.64%  |
| Realtek Semiconductor                  | 9         | 10.34%  |
| IMC Networks                           | 7         | 8.05%   |
| Suyin                                  | 5         | 5.75%   |
| Ricoh                                  | 3         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.45%   |
| Syntek                                 | 2         | 2.3%    |
| Sunplus Innovation Technology          | 2         | 2.3%    |
| Quanta                                 | 2         | 2.3%    |
| Lite-On Technology                     | 2         | 2.3%    |
| ALi                                    | 2         | 2.3%    |
| USB Camera                             | 1         | 1.15%   |
| Tobii Technology AB                    | 1         | 1.15%   |
| Sonix Technology                       | 1         | 1.15%   |
| Luxvisions Innotech Limited            | 1         | 1.15%   |
| Lenovo                                 | 1         | 1.15%   |
| Importek                               | 1         | 1.15%   |
| Apple                                  | 1         | 1.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                        | 5         | 5.75%   |
| Realtek Integrated_Webcam_HD                                  | 4         | 4.6%    |
| Microdia USB 2.0 Camera                                       | 4         | 4.6%    |
| Chicony Lenovo EasyCamera                                     | 4         | 4.6%    |
| Acer USB Camera                                               | 4         | 4.6%    |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 2         | 2.3%    |
| Realtek USB Camera                                            | 2         | 2.3%    |
| Microdia Integrated_Webcam_HD                                 | 2         | 2.3%    |
| Microdia Integrated_Webcam_1.3M                               | 2         | 2.3%    |
| IMC Networks XHC Camera                                       | 2         | 2.3%    |
| IMC Networks Lenovo EasyCamera                                | 2         | 2.3%    |
| Chicony Integrated Camera                                     | 2         | 2.3%    |
| Chicony HD WebCam                                             | 2         | 2.3%    |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 2         | 2.3%    |
| Acer Lenovo EasyCamera                                        | 2         | 2.3%    |
| Acer HD Webcam                                                | 2         | 2.3%    |
| USB Camera USB Camera                                         | 1         | 1.15%   |
| Tobii AB EyeChip                                              | 1         | 1.15%   |
| Syntek USB Camera Device                                      | 1         | 1.15%   |
| Syntek Integrated Webcam                                      | 1         | 1.15%   |
| Suyin Lenovo EasyCamera                                       | 1         | 1.15%   |
| Suyin Integrated_Webcam_HD                                    | 1         | 1.15%   |
| Suyin HP Webcam 101                                           | 1         | 1.15%   |
| Suyin HD Video WebCam                                         | 1         | 1.15%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 1.15%   |
| Sunplus Integrated_Webcam_HD                                  | 1         | 1.15%   |
| Sunplus HD WebCam                                             | 1         | 1.15%   |
| Sonix USB2.0 HD UVC WebCam                                    | 1         | 1.15%   |
| Ricoh Sony Vaio Integrated Webcam                             | 1         | 1.15%   |
| Realtek Integrated Webcam HD                                  | 1         | 1.15%   |
| Realtek Integrated Webcam                                     | 1         | 1.15%   |
| Realtek EasyCamera                                            | 1         | 1.15%   |
| Quanta HP Webcam                                              | 1         | 1.15%   |
| Quanta HD User Facing                                         | 1         | 1.15%   |
| Microdia WebCam SC-13HDL12639P                                | 1         | 1.15%   |
| Microdia USB camera                                           | 1         | 1.15%   |
| Microdia Sonix USB 2.0 Camera                                 | 1         | 1.15%   |
| Microdia Laptop_Integrated_Webcam_HD                          | 1         | 1.15%   |
| Microdia Integrated_Webcam_FHD                                | 1         | 1.15%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera           | 1         | 1.15%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 63.64%  |
| AuthenTec                  | 2         | 18.18%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| Futronic Technology        | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 3         | 27.27%  |
| Validity Sensors VFS495 Fingerprint Reader  | 2         | 18.18%  |
| AuthenTec AES2501 Fingerprint Sensor        | 2         | 18.18%  |
| Validity Sensors VFS471 Fingerprint Reader  | 1         | 9.09%   |
| Validity Sensors Fingerprint scanner        | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader          | 1         | 9.09%   |
| Futronic Fingerprint Scanner Model FS88     | 1         | 9.09%   |

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
| 0     | 89        | 78.07%  |
| 1     | 19        | 16.67%  |
| 2     | 5         | 4.39%   |
| 5     | 1         | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 33.33%  |
| Graphics card            | 7         | 21.21%  |
| Chipcard                 | 5         | 15.15%  |
| Sound                    | 3         | 9.09%   |
| Net/wireless             | 3         | 9.09%   |
| Camera                   | 2         | 6.06%   |
| Storage                  | 1         | 3.03%   |
| Communication controller | 1         | 3.03%   |

