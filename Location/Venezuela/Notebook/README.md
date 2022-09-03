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

Total: 153

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| HP            | EliteBook 840 G3            | [e4dd9b130e](https://linux-hardware.org/?probe=e4dd9b130e) | Jun 29, 2022 |
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
| Ubuntu 20.04                 | 9         | 8.49%   |
| Debian 11                    | 8         | 7.55%   |
| Debian 10                    | 6         | 5.66%   |
| Ubuntu 18.04                 | 5         | 4.72%   |
| OpenMandriva 4.3             | 5         | 4.72%   |
| Kubuntu 20.04                | 4         | 3.77%   |
| KDE neon 20.04               | 4         | 3.77%   |
| Xubuntu 18.04                | 3         | 2.83%   |
| Ubuntu 22.04                 | 3         | 2.83%   |
| ROSA R9                      | 3         | 2.83%   |
| OpenMandriva 4.2             | 3         | 2.83%   |
| Zorin 16                     | 2         | 1.89%   |
| Zorin 15                     | 2         | 1.89%   |
| Ubuntu 21.10                 | 2         | 1.89%   |
| Ubuntu 19.10                 | 2         | 1.89%   |
| Ubuntu 16.04                 | 2         | 1.89%   |
| Pop!_OS 22.04                | 2         | 1.89%   |
| Pop!_OS 21.04                | 2         | 1.89%   |
| Manjaro                      | 2         | 1.89%   |
| Linux Mint 20.3              | 2         | 1.89%   |
| Linux Mint 20                | 2         | 1.89%   |
| Fedora 36                    | 2         | 1.89%   |
| Fedora 35                    | 2         | 1.89%   |
| Xubuntu 21.10                | 1         | 0.94%   |
| Xubuntu 20.04                | 1         | 0.94%   |
| Ubuntu MATE 20.04            | 1         | 0.94%   |
| Ubuntu MATE 19.10            | 1         | 0.94%   |
| Solus 4.1                    | 1         | 0.94%   |
| ROSA R11                     | 1         | 0.94%   |
| Q4OS 4                       | 1         | 0.94%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.94%   |
| OpenMandriva 4.50            | 1         | 0.94%   |
| MX 20                        | 1         | 0.94%   |
| Manjaro 21.2.0               | 1         | 0.94%   |
| Manjaro 21.1.0               | 1         | 0.94%   |
| Manjaro 21.0                 | 1         | 0.94%   |
| Manjaro 20.1                 | 1         | 0.94%   |
| Lubuntu 18.04                | 1         | 0.94%   |
| LMDE 4                       | 1         | 0.94%   |
| Linux Mint 19.3              | 1         | 0.94%   |
| Linux Lite 5.6               | 1         | 0.94%   |
| KDE neon 18.04               | 1         | 0.94%   |
| Garuda Linux Soaring         | 1         | 0.94%   |
| Feren OS 18.04               | 1         | 0.94%   |
| Fedora 34                    | 1         | 0.94%   |
| Fedora 33                    | 1         | 0.94%   |
| Deepin                       | 1         | 0.94%   |
| ArcoLinux Rolling            | 1         | 0.94%   |
| Arch                         | 1         | 0.94%   |
| Alpine 3.16.0                | 1         | 0.94%   |
| Alpine 3.13.0_alpha20200917  | 1         | 0.94%   |
| AlmaLinux 8.5                | 1         | 0.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 21        | 20.79%  |
| Debian       | 13        | 12.87%  |
| OpenMandriva | 9         | 8.91%   |
| Manjaro      | 6         | 5.94%   |
| Xubuntu      | 5         | 4.95%   |
| Linux Mint   | 5         | 4.95%   |
| KDE neon     | 5         | 4.95%   |
| Fedora       | 5         | 4.95%   |
| Zorin        | 4         | 3.96%   |
| ROSA         | 4         | 3.96%   |
| Pop!_OS      | 4         | 3.96%   |
| Kubuntu      | 4         | 3.96%   |
| Ubuntu MATE  | 2         | 1.98%   |
| Solus        | 1         | 0.99%   |
| Q4OS         | 1         | 0.99%   |
| openSUSE     | 1         | 0.99%   |
| MX           | 1         | 0.99%   |
| Lubuntu      | 1         | 0.99%   |
| LMDE         | 1         | 0.99%   |
| Linux Lite   | 1         | 0.99%   |
| Garuda Linux | 1         | 0.99%   |
| Feren OS     | 1         | 0.99%   |
| Deepin       | 1         | 0.99%   |
| ArcoLinux    | 1         | 0.99%   |
| Arch         | 1         | 0.99%   |
| Alpine       | 1         | 0.99%   |
| AlmaLinux    | 1         | 0.99%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                  | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003                  | 5         | 4.17%   |
| 5.4.0-42-generic                         | 4         | 3.33%   |
| 5.4.0-73-generic                         | 3         | 2.5%    |
| 5.4.0-52-generic                         | 3         | 2.5%    |
| 5.3.0-40-generic                         | 3         | 2.5%    |
| 5.13.0-39-generic                        | 3         | 2.5%    |
| 5.10.14-desktop-1omv4002                 | 3         | 2.5%    |
| 5.10.0-13-amd64                          | 3         | 2.5%    |
| 4.9.20-nrj-desktop-1rosa-x86_64          | 3         | 2.5%    |
| 4.19.0-17-amd64                          | 3         | 2.5%    |
| 5.4.0-89-generic                         | 2         | 1.67%   |
| 5.4.0-77-generic                         | 2         | 1.67%   |
| 5.4.0-48-generic                         | 2         | 1.67%   |
| 5.4.0-107-generic                        | 2         | 1.67%   |
| 5.15.0-43-generic                        | 2         | 1.67%   |
| 5.11.0-37-generic                        | 2         | 1.67%   |
| 5.10.0-15-amd64                          | 2         | 1.67%   |
| 5.10.0-11-amd64                          | 2         | 1.67%   |
| 5.0.0-37-generic                         | 2         | 1.67%   |
| 5.9.0-5-amd64                            | 1         | 0.83%   |
| 5.8.6-1-MANJARO                          | 1         | 0.83%   |
| 5.8.0-53-generic                         | 1         | 0.83%   |
| 5.8.0-45-generic                         | 1         | 0.83%   |
| 5.8.0-44-generic                         | 1         | 0.83%   |
| 5.8.0-41-generic                         | 1         | 0.83%   |
| 5.6.6-1-default                          | 1         | 0.83%   |
| 5.6.18-155.current                       | 1         | 0.83%   |
| 5.5.4-linux-xanmod-1-rosa-x86_64-xanmod3 | 1         | 0.83%   |
| 5.4.83-0-lts                             | 1         | 0.83%   |
| 5.4.105-1-MANJARO                        | 1         | 0.83%   |
| 5.4.0-91-generic                         | 1         | 0.83%   |
| 5.4.0-86-generic                         | 1         | 0.83%   |
| 5.4.0-70-generic                         | 1         | 0.83%   |
| 5.4.0-31-generic                         | 1         | 0.83%   |
| 5.3.0-42-generic                         | 1         | 0.83%   |
| 5.3.0-29-generic                         | 1         | 0.83%   |
| 5.17.2-xanmod1                           | 1         | 0.83%   |
| 5.17.15-76051715-generic                 | 1         | 0.83%   |
| 5.17.12-300.fc36.x86_64                  | 1         | 0.83%   |
| 5.17.11-300.fc36.x86_64                  | 1         | 0.83%   |
| 5.15.8-200.fc35.x86_64                   | 1         | 0.83%   |
| 5.15.6-2-MANJARO                         | 1         | 0.83%   |
| 5.15.46-1-lts                            | 1         | 0.83%   |
| 5.15.28-1-MANJARO                        | 1         | 0.83%   |
| 5.15.2-2-MANJARO                         | 1         | 0.83%   |
| 5.15.19-1-MANJARO                        | 1         | 0.83%   |
| 5.15.13-xanmod1                          | 1         | 0.83%   |
| 5.15.10-zen1-1-zen                       | 1         | 0.83%   |
| 5.15.0-46-generic                        | 1         | 0.83%   |
| 5.15.0-41-generic                        | 1         | 0.83%   |
| 5.15.0-40-generic                        | 1         | 0.83%   |
| 5.15.0-33-generic                        | 1         | 0.83%   |
| 5.14.10-300.fc35.x86_64                  | 1         | 0.83%   |
| 5.14.10-200.fc34.x86_64                  | 1         | 0.83%   |
| 5.13.13-arch1-1                          | 1         | 0.83%   |
| 5.13.0-51-generic                        | 1         | 0.83%   |
| 5.13.0-48-generic                        | 1         | 0.83%   |
| 5.13.0-41-generic                        | 1         | 0.83%   |
| 5.13.0-37-generic                        | 1         | 0.83%   |
| 5.13.0-30-generic                        | 1         | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 20        | 18.35%  |
| 5.13.0  | 10        | 9.17%   |
| 5.10.0  | 8         | 7.34%   |
| 4.19.0  | 8         | 7.34%   |
| 5.11.0  | 6         | 5.5%    |
| 5.3.0   | 5         | 4.59%   |
| 5.16.7  | 5         | 4.59%   |
| 5.15.0  | 4         | 3.67%   |
| 4.15.0  | 4         | 3.67%   |
| 5.8.0   | 3         | 2.75%   |
| 5.10.14 | 3         | 2.75%   |
| 4.9.20  | 3         | 2.75%   |
| 5.14.10 | 2         | 1.83%   |
| 5.0.0   | 2         | 1.83%   |
| 5.9.0   | 1         | 0.92%   |
| 5.8.6   | 1         | 0.92%   |
| 5.6.6   | 1         | 0.92%   |
| 5.6.18  | 1         | 0.92%   |
| 5.5.4   | 1         | 0.92%   |
| 5.4.83  | 1         | 0.92%   |
| 5.4.105 | 1         | 0.92%   |
| 5.17.2  | 1         | 0.92%   |
| 5.17.15 | 1         | 0.92%   |
| 5.17.12 | 1         | 0.92%   |
| 5.17.11 | 1         | 0.92%   |
| 5.15.8  | 1         | 0.92%   |
| 5.15.6  | 1         | 0.92%   |
| 5.15.46 | 1         | 0.92%   |
| 5.15.28 | 1         | 0.92%   |
| 5.15.2  | 1         | 0.92%   |
| 5.15.19 | 1         | 0.92%   |
| 5.15.13 | 1         | 0.92%   |
| 5.15.10 | 1         | 0.92%   |
| 5.13.13 | 1         | 0.92%   |
| 5.12.4  | 1         | 0.92%   |
| 5.12.19 | 1         | 0.92%   |
| 5.10.5  | 1         | 0.92%   |
| 5.10.11 | 1         | 0.92%   |
| 5.10.10 | 1         | 0.92%   |
| 4.18.0  | 1         | 0.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 22        | 20.37%  |
| 5.10    | 14        | 12.96%  |
| 5.15    | 11        | 10.19%  |
| 5.13    | 11        | 10.19%  |
| 4.19    | 8         | 7.41%   |
| 5.11    | 6         | 5.56%   |
| 5.3     | 5         | 4.63%   |
| 5.16    | 5         | 4.63%   |
| 5.8     | 4         | 3.7%    |
| 5.17    | 4         | 3.7%    |
| 4.15    | 4         | 3.7%    |
| 4.9     | 3         | 2.78%   |
| 5.6     | 2         | 1.85%   |
| 5.14    | 2         | 1.85%   |
| 5.12    | 2         | 1.85%   |
| 5.0     | 2         | 1.85%   |
| 5.9     | 1         | 0.93%   |
| 5.5     | 1         | 0.93%   |
| 4.18    | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 88        | 89.8%   |
| i686   | 10        | 10.2%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 34        | 32.69%  |
| KDE5          | 21        | 20.19%  |
| XFCE          | 19        | 18.27%  |
| Unknown       | 7         | 6.73%   |
| KDE           | 6         | 5.77%   |
| MATE          | 4         | 3.85%   |
| KDE4          | 3         | 2.88%   |
| X-Cinnamon    | 2         | 1.92%   |
| Unity         | 2         | 1.92%   |
| Cinnamon      | 2         | 1.92%   |
| LXQt          | 1         | 0.96%   |
| GNOME Classic | 1         | 0.96%   |
| Deepin        | 1         | 0.96%   |
| Budgie        | 1         | 0.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 87        | 87.88%  |
| Wayland | 11        | 11.11%  |
| Tty     | 1         | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 43        | 41.35%  |
| SDDM    | 17        | 16.35%  |
| GDM     | 16        | 15.38%  |
| LightDM | 13        | 12.5%   |
| GDM3    | 9         | 8.65%   |
| TDM     | 3         | 2.88%   |
| KDM     | 3         | 2.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_VE   | 55        | 53.4%   |
| en_US   | 32        | 31.07%  |
| es_ES   | 8         | 7.77%   |
| Unknown | 7         | 6.8%    |
| en_CA   | 1         | 0.97%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 69        | 68.32%  |
| EFI  | 32        | 31.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 79        | 79.8%   |
| Overlay | 8         | 8.08%   |
| Btrfs   | 6         | 6.06%   |
| Xfs     | 3         | 3.03%   |
| Unknown | 3         | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 54        | 52.43%  |
| GPT     | 25        | 24.27%  |
| MBR     | 24        | 23.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 85.29%  |
| Yes       | 15        | 14.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 63.64%  |
| Yes       | 36        | 36.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 18        | 18.37%  |
| Dell                | 18        | 18.37%  |
| VIT                 | 17        | 17.35%  |
| Hewlett-Packard     | 13        | 13.27%  |
| ASUSTek Computer    | 7         | 7.14%   |
| Intel               | 5         | 5.1%    |
| Unknown             | 4         | 4.08%   |
| Acer                | 3         | 3.06%   |
| UNIQCELL            | 1         | 1.02%   |
| Toshiba             | 1         | 1.02%   |
| Sony                | 1         | 1.02%   |
| Samsung Electronics | 1         | 1.02%   |
| Pegatron            | 1         | 1.02%   |
| MSI                 | 1         | 1.02%   |
| GPU Company         | 1         | 1.02%   |
| Google              | 1         | 1.02%   |
| Gateway             | 1         | 1.02%   |
| Exo                 | 1         | 1.02%   |
| Clevo               | 1         | 1.02%   |
| AVITA               | 1         | 1.02%   |
| Alienware           | 1         | 1.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| VIT P2400                           | 5         | 5.1%    |
| Intel powered classmate PC          | 5         | 5.1%    |
| Unknown                             | 4         | 4.08%   |
| VIT P3400                           | 3         | 3.06%   |
| VIT P2402                           | 3         | 3.06%   |
| VIT M2420                           | 3         | 3.06%   |
| VIT M2421                           | 2         | 2.04%   |
| Lenovo IdeaPad S100c 20194          | 2         | 2.04%   |
| Lenovo 3000 N200 0769ARS            | 2         | 2.04%   |
| Dell Inspiron 1545                  | 2         | 2.04%   |
| VIT P1400                           | 1         | 1.02%   |
| UNIQCELL Q15.6                      | 1         | 1.02%   |
| Toshiba Satellite E55t-A            | 1         | 1.02%   |
| Sony VGN-FW510F                     | 1         | 1.02%   |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 1.02%   |
| Pegatron T14AF                      | 1         | 1.02%   |
| MSI MS-1454                         | 1         | 1.02%   |
| Lenovo Z50-75 80EC                  | 1         | 1.02%   |
| Lenovo ThinkPad X201 3680AE2        | 1         | 1.02%   |
| Lenovo ThinkPad SL400 2743A48       | 1         | 1.02%   |
| Lenovo ThinkPad Edge 01962AS        | 1         | 1.02%   |
| Lenovo ThinkPad E560 20EV002FUS     | 1         | 1.02%   |
| Lenovo IdeaPad S110 20126           | 1         | 1.02%   |
| Lenovo IdeaPad 5 14ALC05 82LM       | 1         | 1.02%   |
| Lenovo IdeaPad 330-15ARR 81D2       | 1         | 1.02%   |
| Lenovo IdeaPad 3 15IIL05 81WE       | 1         | 1.02%   |
| Lenovo IdeaPad 1 14IGL05 81VU       | 1         | 1.02%   |
| Lenovo G570 4334                    | 1         | 1.02%   |
| Lenovo G480 20150                   | 1         | 1.02%   |
| Lenovo G460 20041                   | 1         | 1.02%   |
| Lenovo B40-70 20392                 | 1         | 1.02%   |
| HP ProBook 440 G1                   | 1         | 1.02%   |
| HP Presario V2000 (EW997LA#ABM)     | 1         | 1.02%   |
| HP Presario C700                    | 1         | 1.02%   |
| HP Pavilion dv6700                  | 1         | 1.02%   |
| HP Pavilion dv6500                  | 1         | 1.02%   |
| HP Pavilion dv6000 (RV216UA#ABA)    | 1         | 1.02%   |
| HP Pavilion dv6                     | 1         | 1.02%   |
| HP Pavilion dv5                     | 1         | 1.02%   |
| HP Pavilion dv4                     | 1         | 1.02%   |
| HP Laptop 15-ef2xxx                 | 1         | 1.02%   |
| HP EliteBook 840 G3                 | 1         | 1.02%   |
| HP Compaq Presario C700             | 1         | 1.02%   |
| HP 2000                             | 1         | 1.02%   |
| GPU Company GWTN156-11              | 1         | 1.02%   |
| Google Cyan                         | 1         | 1.02%   |
| Gateway NV57H                       | 1         | 1.02%   |
| Exo AIO A210                        | 1         | 1.02%   |
| Dell XPS 15 7590                    | 1         | 1.02%   |
| Dell Vostro 5402                    | 1         | 1.02%   |
| Dell Vostro 1500                    | 1         | 1.02%   |
| Dell Precision 7710                 | 1         | 1.02%   |
| Dell Latitude E7450                 | 1         | 1.02%   |
| Dell Latitude E6420                 | 1         | 1.02%   |
| Dell Latitude 5590                  | 1         | 1.02%   |
| Dell Latitude 5490                  | 1         | 1.02%   |
| Dell Inspiron 5570                  | 1         | 1.02%   |
| Dell Inspiron 5520                  | 1         | 1.02%   |
| Dell Inspiron 5502                  | 1         | 1.02%   |
| Dell Inspiron 5437                  | 1         | 1.02%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 10        | 10.2%   |
| Lenovo IdeaPad         | 7         | 7.14%   |
| HP Pavilion            | 6         | 6.12%   |
| VIT P2400              | 5         | 5.1%    |
| Intel powered          | 5         | 5.1%    |
| Lenovo ThinkPad        | 4         | 4.08%   |
| Dell Latitude          | 4         | 4.08%   |
| Unknown                | 4         | 4.08%   |
| VIT P3400              | 3         | 3.06%   |
| VIT P2402              | 3         | 3.06%   |
| VIT M2420              | 3         | 3.06%   |
| VIT M2421              | 2         | 2.04%   |
| Lenovo 3000            | 2         | 2.04%   |
| HP Presario            | 2         | 2.04%   |
| Dell Vostro            | 2         | 2.04%   |
| ASUS VivoBook          | 2         | 2.04%   |
| ASUS ASUS              | 2         | 2.04%   |
| Acer Aspire            | 2         | 2.04%   |
| VIT P1400              | 1         | 1.02%   |
| UNIQCELL Q15.6         | 1         | 1.02%   |
| Toshiba Satellite      | 1         | 1.02%   |
| Sony VGN-FW510F        | 1         | 1.02%   |
| Samsung 355V4C         | 1         | 1.02%   |
| Pegatron T14AF         | 1         | 1.02%   |
| MSI MS-1454            | 1         | 1.02%   |
| Lenovo Z50-75          | 1         | 1.02%   |
| Lenovo G570            | 1         | 1.02%   |
| Lenovo G480            | 1         | 1.02%   |
| Lenovo G460            | 1         | 1.02%   |
| Lenovo B40-70          | 1         | 1.02%   |
| HP ProBook             | 1         | 1.02%   |
| HP Laptop              | 1         | 1.02%   |
| HP EliteBook           | 1         | 1.02%   |
| HP Compaq              | 1         | 1.02%   |
| HP 2000                | 1         | 1.02%   |
| GPU Company GWTN156-11 | 1         | 1.02%   |
| Google Cyan            | 1         | 1.02%   |
| Gateway NV57H          | 1         | 1.02%   |
| Exo AIO                | 1         | 1.02%   |
| Dell XPS               | 1         | 1.02%   |
| Dell Precision         | 1         | 1.02%   |
| Clevo W54xEU           | 1         | 1.02%   |
| AVITA NS14A1US         | 1         | 1.02%   |
| ASUS X555DA            | 1         | 1.02%   |
| ASUS X553MA            | 1         | 1.02%   |
| ASUS TUF               | 1         | 1.02%   |
| Alienware 17           | 1         | 1.02%   |
| Acer TravelMate        | 1         | 1.02%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 13        | 13.27%  |
| 2011    | 12        | 12.24%  |
| 2012    | 11        | 11.22%  |
| 2010    | 8         | 8.16%   |
| 2007    | 8         | 8.16%   |
| 2018    | 7         | 7.14%   |
| 2014    | 6         | 6.12%   |
| 2008    | 6         | 6.12%   |
| 2021    | 5         | 5.1%    |
| 2020    | 5         | 5.1%    |
| 2017    | 4         | 4.08%   |
| 2015    | 3         | 3.06%   |
| 2009    | 3         | 3.06%   |
| 2022    | 2         | 2.04%   |
| 2019    | 2         | 2.04%   |
| 2016    | 1         | 1.02%   |
| 2006    | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 98        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 94        | 95.92%  |
| Enabled  | 4         | 4.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 97        | 98.98%  |
| Yes  | 1         | 1.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 27        | 27.27%  |
| 4.01-8.0   | 23        | 23.23%  |
| 1.01-2.0   | 22        | 22.22%  |
| 8.01-16.0  | 14        | 14.14%  |
| 16.01-24.0 | 6         | 6.06%   |
| 2.01-3.0   | 4         | 4.04%   |
| 32.01-64.0 | 2         | 2.02%   |
| 0.51-1.0   | 1         | 1.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 45        | 42.06%  |
| 2.01-3.0   | 25        | 23.36%  |
| 0.51-1.0   | 16        | 14.95%  |
| 4.01-8.0   | 10        | 9.35%   |
| 3.01-4.0   | 9         | 8.41%   |
| 16.01-24.0 | 1         | 0.93%   |
| 8.01-16.0  | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 70        | 70%     |
| 2      | 26        | 26%     |
| 3      | 4         | 4%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 56.12%  |
| No        | 43        | 43.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 88.89%  |
| No        | 11        | 11.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 97.96%  |
| No        | 2         | 2.04%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 51.52%  |
| No        | 48        | 48.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Venezuela | 98        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 44        | 41.12%  |
| Maracaibo                  | 13        | 12.15%  |
| Mérida                    | 6         | 5.61%   |
| Maracay                    | 6         | 5.61%   |
| Barquisimeto               | 4         | 3.74%   |
| Barcelona                  | 4         | 3.74%   |
| Valencia                   | 2         | 1.87%   |
| Maturín                   | 2         | 1.87%   |
| Lecherias                  | 2         | 1.87%   |
| Tucape                     | 1         | 0.93%   |
| San Juan Bautista          | 1         | 0.93%   |
| San Diego                  | 1         | 0.93%   |
| San Cristóbal             | 1         | 0.93%   |
| San Carlos del Zulia       | 1         | 0.93%   |
| Puerto Ordaz and San Felix | 1         | 0.93%   |
| Puerto Cumarebo            | 1         | 0.93%   |
| Puerto Cruz                | 1         | 0.93%   |
| Porlamar                   | 1         | 0.93%   |
| Parroquia El Recreo        | 1         | 0.93%   |
| Mariara                    | 1         | 0.93%   |
| Los Palos Grandes          | 1         | 0.93%   |
| Las Vegas                  | 1         | 0.93%   |
| Guatire                    | 1         | 0.93%   |
| Guarenas                   | 1         | 0.93%   |
| Guanare                    | 1         | 0.93%   |
| El Hatillo Municipality    | 1         | 0.93%   |
| Ejido                      | 1         | 0.93%   |
| Ciudad Guayana             | 1         | 0.93%   |
| Ciudad Bolívar            | 1         | 0.93%   |
| Charallave                 | 1         | 0.93%   |
| Cagua                      | 1         | 0.93%   |
| Barinas                    | 1         | 0.93%   |
| Anaco                      | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 28     | 23.01%  |
| WDC                 | 22        | 30     | 19.47%  |
| Toshiba             | 11        | 11     | 9.73%   |
| Samsung Electronics | 7         | 7      | 6.19%   |
| Unknown             | 5         | 7      | 4.42%   |
| Hitachi             | 5         | 5      | 4.42%   |
| Crucial             | 5         | 6      | 4.42%   |
| SanDisk             | 4         | 5      | 3.54%   |
| LITEONIT            | 4         | 7      | 3.54%   |
| Kingston            | 3         | 4      | 2.65%   |
| Intel               | 3         | 6      | 2.65%   |
| SPCC                | 2         | 3      | 1.77%   |
| HGST                | 2         | 2      | 1.77%   |
| Fujitsu             | 2         | 2      | 1.77%   |
| Vaseky              | 1         | 1      | 0.88%   |
| SK hynix            | 1         | 1      | 0.88%   |
| Silicon Motion      | 1         | 1      | 0.88%   |
| PNY                 | 1         | 1      | 0.88%   |
| Phison              | 1         | 1      | 0.88%   |
| Micron Technology   | 1         | 3      | 0.88%   |
| KingFast            | 1         | 2      | 0.88%   |
| Intenso             | 1         | 1      | 0.88%   |
| Dell                | 1         | 2      | 0.88%   |
| BIWIN               | 1         | 2      | 0.88%   |
| Apacer              | 1         | 1      | 0.88%   |
| addlink             | 1         | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB     | 4         | 3.45%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 2.59%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 2.59%   |
| Seagate ST250LM004 HN-M250MBB 250GB | 3         | 2.59%   |
| LITEONIT LMS-32L6M 32GB SSD         | 3         | 2.59%   |
| WDC WD5000LPVT-08G33T1 500GB        | 2         | 1.72%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2         | 1.72%   |
| Toshiba MQ01ABF050 500GB            | 2         | 1.72%   |
| Toshiba MQ01ABF032 320GB            | 2         | 1.72%   |
| Toshiba MQ01ABD050 500GB            | 2         | 1.72%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 2         | 1.72%   |
| Seagate ST320LM000 HM321HI 320GB    | 2         | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 1.72%   |
| SanDisk NVMe SSD Drive 1TB          | 2         | 1.72%   |
| HGST HTS721010A9E630 1TB            | 2         | 1.72%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 1.72%   |
| WDC WDS500G2B0C-00PXH0 500GB        | 1         | 0.86%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 0.86%   |
| WDC WD5000BPVT-24HXZT3 500GB        | 1         | 0.86%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 0.86%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 1         | 0.86%   |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 0.86%   |
| WDC WD3200BEVT-00A0RT0 320GB        | 1         | 0.86%   |
| WDC WD3200BEKT-60F3T1 320GB         | 1         | 0.86%   |
| WDC WD1600BEVT-88ZCT0 160GB         | 1         | 0.86%   |
| WDC WD1600BEVS-22RST0 160GB         | 1         | 0.86%   |
| WDC WD1200BEVS-60UST0 120GB         | 1         | 0.86%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 0.86%   |
| Vaseky V800/128G 128GB              | 1         | 0.86%   |
| Unknown USDU1  32GB                 | 1         | 0.86%   |
| Unknown SD/MMC/MS PRO 128GB         | 1         | 0.86%   |
| Unknown MMC128  128GB               | 1         | 0.86%   |
| Unknown MMC Card  64GB              | 1         | 0.86%   |
| Unknown MMC Card  16GB              | 1         | 0.86%   |
| Unknown External 120GB              | 1         | 0.86%   |
| Unknown DA4064  64GB                | 1         | 0.86%   |
| Toshiba THNSNH256GBST SSD           | 1         | 0.86%   |
| Toshiba MQ01ACF050 500GB            | 1         | 0.86%   |
| Toshiba MQ01ABD075 752GB            | 1         | 0.86%   |
| Toshiba MK3275GSX 320GB             | 1         | 0.86%   |
| Toshiba MK1652GSX 160GB             | 1         | 0.86%   |
| SPCC Solid State Disk 512GB         | 1         | 0.86%   |
| SPCC Solid State Disk 128GB         | 1         | 0.86%   |
| SK hynix HFM001TD3JX013N 1TB        | 1         | 0.86%   |
| Silicon Motion NVME SSD 512GB       | 1         | 0.86%   |
| Seagate ST9500325AS 500GB           | 1         | 0.86%   |
| Seagate ST9320423AS 320GB           | 1         | 0.86%   |
| Seagate ST9320325AS 320GB           | 1         | 0.86%   |
| Seagate ST9160314AS 160GB           | 1         | 0.86%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 0.86%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 0.86%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 0.86%   |
| Seagate ST320LT012-9WS14C 320GB     | 1         | 0.86%   |
| Seagate ST320LT012-1DG14C 320GB     | 1         | 0.86%   |
| Seagate ST2000LM007-1R8174 2TB      | 1         | 0.86%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 0.86%   |
| Seagate Backup+ SL 1TB              | 1         | 0.86%   |
| Seagate BACKUP+ Mac 500GB           | 1         | 0.86%   |
| SanDisk SSD PLUS 480GB              | 1         | 0.86%   |
| SanDisk SSD PLUS 240GB              | 1         | 0.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 26     | 35.29%  |
| WDC                 | 21        | 28     | 30.88%  |
| Toshiba             | 10        | 10     | 14.71%  |
| Hitachi             | 5         | 5      | 7.35%   |
| Unknown             | 2         | 2      | 2.94%   |
| Samsung Electronics | 2         | 2      | 2.94%   |
| HGST                | 2         | 2      | 2.94%   |
| Fujitsu             | 2         | 2      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 5         | 6      | 19.23%  |
| LITEONIT            | 4         | 7      | 15.38%  |
| Samsung Electronics | 3         | 3      | 11.54%  |
| SPCC                | 2         | 3      | 7.69%   |
| SanDisk             | 2         | 3      | 7.69%   |
| Kingston            | 2         | 3      | 7.69%   |
| Vaseky              | 1         | 1      | 3.85%   |
| Toshiba             | 1         | 1      | 3.85%   |
| PNY                 | 1         | 1      | 3.85%   |
| Micron Technology   | 1         | 3      | 3.85%   |
| KingFast            | 1         | 2      | 3.85%   |
| Intenso             | 1         | 1      | 3.85%   |
| Dell                | 1         | 2      | 3.85%   |
| BIWIN               | 1         | 2      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 66        | 77     | 60.55%  |
| SSD     | 25        | 38     | 22.94%  |
| NVMe    | 12        | 18     | 11.01%  |
| MMC     | 4         | 5      | 3.67%   |
| Unknown | 2         | 2      | 1.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 84        | 113    | 80.77%  |
| NVMe | 12        | 18     | 11.54%  |
| SAS  | 4         | 4      | 3.85%   |
| MMC  | 4         | 5      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 93     | 83.33%  |
| 0.51-1.0   | 14        | 21     | 15.56%  |
| 1.01-2.0   | 1         | 1      | 1.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 30        | 28.57%  |
| 101-250    | 27        | 25.71%  |
| 501-1000   | 18        | 17.14%  |
| 21-50      | 10        | 9.52%   |
| 1-20       | 8         | 7.62%   |
| 51-100     | 7         | 6.67%   |
| 1001-2000  | 3         | 2.86%   |
| 2001-3000  | 1         | 0.95%   |
| Unknown    | 1         | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 40        | 37.38%  |
| 21-50    | 22        | 20.56%  |
| 101-250  | 15        | 14.02%  |
| 51-100   | 14        | 13.08%  |
| 251-500  | 9         | 8.41%   |
| 501-1000 | 6         | 5.61%   |
| Unknown  | 1         | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 1      | 5.88%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 5.88%   |
| WDC WD1200BEVS-60UST0 120GB          | 1         | 1      | 5.88%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2      | 5.88%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 5.88%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 5.88%   |
| Seagate ST9320325AS 320GB            | 1         | 1      | 5.88%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 5.88%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 5.88%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 5.88%   |
| Samsung Electronics HN-M320MBB 320GB | 1         | 1      | 5.88%   |
| Samsung Electronics HM250HI 250GB    | 1         | 1      | 5.88%   |
| Intel SSDPEKKW256G7 256GB            | 1         | 1      | 5.88%   |
| Hitachi HTS543232L9A300 320GB        | 1         | 1      | 5.88%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1      | 5.88%   |
| Hitachi HTS542525K9SA00 250GB        | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 29.41%  |
| WDC                 | 4         | 5      | 23.53%  |
| Hitachi             | 3         | 3      | 17.65%  |
| Toshiba             | 2         | 2      | 11.76%  |
| Samsung Electronics | 2         | 2      | 11.76%  |
| Intel               | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 31.25%  |
| WDC                 | 4         | 5      | 25%     |
| Hitachi             | 3         | 3      | 18.75%  |
| Toshiba             | 2         | 2      | 12.5%   |
| Samsung Electronics | 2         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 17     | 94.12%  |
| NVMe | 1         | 1      | 5.88%   |

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
| Detected | 57        | 81     | 53.77%  |
| Works    | 32        | 41     | 30.19%  |
| Malfunc  | 17        | 18     | 16.04%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 83        | 80.58%  |
| AMD                         | 11        | 10.68%  |
| SanDisk                     | 2         | 1.94%   |
| Samsung Electronics         | 2         | 1.94%   |
| Phison Electronics          | 2         | 1.94%   |
| SK hynix                    | 1         | 0.97%   |
| Silicon Motion              | 1         | 0.97%   |
| Kingston Technology Company | 1         | 0.97%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 13.79%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 7.76%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 7.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 6.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 6         | 5.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 5.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 5.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 4.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 4.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 3.45%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 2.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.59%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.72%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.72%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.72%   |
| SK hynix Gold P31 SSD                                                          | 1         | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.86%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.86%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.86%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.86%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.86%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.86%   |
| Intel SSD 600P Series                                                          | 1         | 0.86%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.86%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 0.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 0.86%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 0.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 0.86%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 0.86%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 0.86%   |
| AMD IXP SB4x0 IDE Controller                                                   | 1         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 75        | 67.57%  |
| IDE  | 13        | 11.71%  |
| NVMe | 12        | 10.81%  |
| RAID | 11        | 9.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 86        | 87.76%  |
| AMD    | 12        | 12.24%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz             | 4         | 4.08%   |
| Intel Atom CPU N455 @ 1.66GHz               | 4         | 4.08%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 3         | 3.06%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 3         | 3.06%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz        | 3         | 3.06%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 2         | 2.04%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 2.04%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 2.04%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 2.04%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 2.04%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 2.04%   |
| Intel Core i3-4000M CPU @ 2.40GHz           | 2         | 2.04%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 2.04%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 2.04%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 2         | 2.04%   |
| Intel Atom CPU N570 @ 1.66GHz               | 2         | 2.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 2.04%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.02%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 1.02%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 1.02%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1         | 1.02%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 1.02%   |
| Intel Genuine CPU T2080 @ 1.73GHz           | 1         | 1.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.02%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.02%   |
| Intel Core i7-7820HK CPU @ 2.90GHz          | 1         | 1.02%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.02%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.02%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 1.02%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 1.02%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 1.02%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.02%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz            | 1         | 1.02%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.02%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.02%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.02%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.02%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.02%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 1.02%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.02%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.02%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.02%   |
| Intel Core i3-2375M CPU @ 1.50GHz           | 1         | 1.02%   |
| Intel Core i3-2370M CPU @ 2.40GHz           | 1         | 1.02%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.02%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 1.02%   |
| Intel Core i3 CPU M 390 @ 2.67GHz           | 1         | 1.02%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.02%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU T5270 @ 1.40GHz        | 1         | 1.02%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.02%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 1         | 1.02%   |
| Intel Celeron CPU N2930 @ 1.83GHz           | 1         | 1.02%   |
| Intel Celeron CPU N2805 @ 1.46GHz           | 1         | 1.02%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 1         | 1.02%   |
| Intel Celeron CPU 1000M @ 1.80GHz           | 1         | 1.02%   |
| Intel Atom CPU N2800 @ 1.86GHz              | 1         | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 19        | 19.39%  |
| Intel Core i3                  | 18        | 18.37%  |
| Intel Core 2 Duo               | 11        | 11.22%  |
| Intel Celeron                  | 10        | 10.2%   |
| Intel Core i7                  | 9         | 9.18%   |
| Intel Atom                     | 7         | 7.14%   |
| Other                          | 4         | 4.08%   |
| AMD Ryzen 5                    | 3         | 3.06%   |
| Intel Pentium Dual-Core        | 2         | 2.04%   |
| Intel Pentium                  | 2         | 2.04%   |
| Intel Genuine                  | 2         | 2.04%   |
| AMD A10                        | 2         | 2.04%   |
| Intel Pentium Silver           | 1         | 1.02%   |
| Intel Pentium Dual             | 1         | 1.02%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 1.02%   |
| AMD Ryzen 7                    | 1         | 1.02%   |
| AMD Ryzen 3                    | 1         | 1.02%   |
| AMD Mobile Sempron             | 1         | 1.02%   |
| AMD E1                         | 1         | 1.02%   |
| AMD E                          | 1         | 1.02%   |
| AMD A6                         | 1         | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 73        | 74.49%  |
| 4       | 13        | 13.27%  |
| 1       | 5         | 5.1%    |
| 6       | 3         | 3.06%   |
| 8       | 2         | 2.04%   |
| Unknown | 2         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 98        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 63        | 64.29%  |
| 1       | 33        | 33.67%  |
| Unknown | 2         | 2.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 93        | 94.9%   |
| 64-bit         | 3         | 3.06%   |
| 32-bit         | 2         | 2.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 18.45%  |
| 0x306a9    | 12        | 11.65%  |
| 0x206a7    | 11        | 10.68%  |
| 0x1067a    | 9         | 8.74%   |
| 0x806e9    | 5         | 4.85%   |
| 0x6fd      | 5         | 4.85%   |
| 0x106ca    | 5         | 4.85%   |
| 0x806c1    | 3         | 2.91%   |
| 0x40651    | 3         | 2.91%   |
| 0x20655    | 3         | 2.91%   |
| 0x406e3    | 2         | 1.94%   |
| 0x306c3    | 2         | 1.94%   |
| 0x08608103 | 2         | 1.94%   |
| 0x05000119 | 2         | 1.94%   |
| 0x906e9    | 1         | 0.97%   |
| 0x806ea    | 1         | 0.97%   |
| 0x806d1    | 1         | 0.97%   |
| 0x706e5    | 1         | 0.97%   |
| 0x706a8    | 1         | 0.97%   |
| 0x6ec      | 1         | 0.97%   |
| 0x506e3    | 1         | 0.97%   |
| 0x406c4    | 1         | 0.97%   |
| 0x306d4    | 1         | 0.97%   |
| 0x30678    | 1         | 0.97%   |
| 0x30673    | 1         | 0.97%   |
| 0x30661    | 1         | 0.97%   |
| 0x20652    | 1         | 0.97%   |
| 0x08600102 | 1         | 0.97%   |
| 0x0810100b | 1         | 0.97%   |
| 0x08101007 | 1         | 0.97%   |
| 0x06006704 | 1         | 0.97%   |
| 0x06006118 | 1         | 0.97%   |
| 0x06003106 | 1         | 0.97%   |
| 0x02000057 | 1         | 0.97%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 15        | 15.31%  |
| IvyBridge       | 13        | 13.27%  |
| KabyLake        | 9         | 9.18%   |
| Penryn          | 8         | 8.16%   |
| Core            | 7         | 7.14%   |
| Bonnell         | 7         | 7.14%   |
| Westmere        | 6         | 6.12%   |
| Haswell         | 5         | 5.1%    |
| TigerLake       | 3         | 3.06%   |
| Skylake         | 3         | 3.06%   |
| Silvermont      | 3         | 3.06%   |
| Zen             | 2         | 2.04%   |
| Icelake         | 2         | 2.04%   |
| Goldmont plus   | 2         | 2.04%   |
| Excavator       | 2         | 2.04%   |
| Bobcat          | 2         | 2.04%   |
| Unknown         | 2         | 2.04%   |
| Zen 2           | 1         | 1.02%   |
| Steamroller     | 1         | 1.02%   |
| P6              | 1         | 1.02%   |
| K8 Hammer       | 1         | 1.02%   |
| K8 & K10 hybrid | 1         | 1.02%   |
| Goldmont        | 1         | 1.02%   |
| Broadwell       | 1         | 1.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 85        | 80.19%  |
| AMD    | 14        | 13.21%  |
| Nvidia | 7         | 6.6%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 13.16%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 11.4%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 6.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 6.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 6.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 5.26%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 5.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.63%   |
| Intel HD Graphics 620                                                                    | 3         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.75%   |
| Intel HD Graphics 630                                                                    | 2         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.75%   |
| AMD Lucienne                                                                             | 2         | 1.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.88%   |
| Nvidia TU117M                                                                            | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.88%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.88%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 0.88%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.88%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.88%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.88%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 1         | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.88%   |
| Intel HD Graphics 615                                                                    | 1         | 0.88%   |
| Intel HD Graphics 5500                                                                   | 1         | 0.88%   |
| Intel HD Graphics 530                                                                    | 1         | 0.88%   |
| Intel HD Graphics 500                                                                    | 1         | 0.88%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.88%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.88%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 0.88%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.88%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.88%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.88%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 0.88%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 1         | 0.88%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 1         | 0.88%   |
| AMD Renoir                                                                               | 1         | 0.88%   |
| AMD Kaveri [Radeon R6 Graphics]                                                          | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 78        | 79.59%  |
| 1 x AMD        | 12        | 12.24%  |
| Intel + Nvidia | 5         | 5.1%    |
| 1 x Nvidia     | 1         | 1.02%   |
| Intel + AMD    | 1         | 1.02%   |
| AMD + Nvidia   | 1         | 1.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 91        | 92.86%  |
| Proprietary | 5         | 5.1%    |
| Unknown     | 2         | 2.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 78%     |
| 0.01-0.5   | 13        | 13%     |
| 1.01-2.0   | 4         | 4%      |
| 3.01-4.0   | 3         | 3%      |
| 0.51-1.0   | 2         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 16.04%  |
| BOE                     | 16        | 15.09%  |
| AU Optronics            | 14        | 13.21%  |
| LG Display              | 12        | 11.32%  |
| Chimei Innolux          | 10        | 9.43%   |
| Chi Mei Optoelectronics | 6         | 5.66%   |
| LG Philips              | 5         | 4.72%   |
| Lenovo                  | 5         | 4.72%   |
| InfoVision              | 4         | 3.77%   |
| Hewlett-Packard         | 3         | 2.83%   |
| HannStar                | 3         | 2.83%   |
| PANDA                   | 2         | 1.89%   |
| Goldstar                | 2         | 1.89%   |
| Vizio                   | 1         | 0.94%   |
| Sharp                   | 1         | 0.94%   |
| MStar                   | 1         | 0.94%   |
| KTC                     | 1         | 0.94%   |
| InnoLux Display         | 1         | 0.94%   |
| Dell                    | 1         | 0.94%   |
| Acer                    | 1         | 0.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 4         | 3.77%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch       | 3         | 2.83%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                  | 3         | 2.83%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch         | 3         | 2.83%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 1.89%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.89%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 2         | 1.89%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch           | 2         | 1.89%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.89%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                  | 2         | 1.89%   |
| Vizio E322AR VIZ0079 1360x768 700x400mm 31.7-inch                     | 1         | 0.94%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.94%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch     | 1         | 0.94%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.94%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC8151 1920x1080 382x214mm 17.2-inch | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch  | 1         | 0.94%   |
| MStar Demo MST0030 1920x540 708x398mm 32.0-inch                       | 1         | 0.94%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch         | 1         | 0.94%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch         | 1         | 0.94%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 0.94%   |
| LG Philips LCD Monitor LPL0701 1280x800 331x207mm 15.4-inch           | 1         | 0.94%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.94%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch         | 1         | 0.94%   |
| LG Display LCD Monitor LGD0550 1920x1080 344x194mm 15.5-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD04B7 1366x768 344x194mm 15.5-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 1         | 0.94%   |
| Lenovo LCD Monitor LEN4090 1366x768 293x164mm 13.2-inch               | 1         | 0.94%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 0.94%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch               | 1         | 0.94%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 0.94%   |
| Lenovo D185wA LEN183F 1366x768 410x230mm 18.5-inch                    | 1         | 0.94%   |
| KTC 32L22-H-CS KTC3202 1360x768 708x398mm 32.0-inch                   | 1         | 0.94%   |
| InnoLux Display LCD Monitor CMI001B 1366x768 309x174mm 14.0-inch      | 1         | 0.94%   |
| InfoVision LCD Monitor IVO057E 1366x768 309x174mm 14.0-inch           | 1         | 0.94%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch           | 1         | 0.94%   |
| Hewlett-Packard L1755 HWP264A 1280x1024 376x301mm 19.0-inch           | 1         | 0.94%   |
| Hewlett-Packard 25f HPN3547 1920x1080 553x309mm 24.9-inch             | 1         | 0.94%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 1         | 0.94%   |
| HannStar HSD140PHW1 HSD0583 1366x768 309x174mm 14.0-inch              | 1         | 0.94%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 1         | 0.94%   |
| Goldstar FHD GSM5BC9 1920x1080 480x270mm 21.7-inch                    | 1         | 0.94%   |
| Dell U2720Q DEL41B5 3840x2160 597x336mm 27.0-inch                     | 1         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 1         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch      | 1         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 1         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15AA 1366x768 344x194mm 15.5-inch       | 1         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 1         | 0.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 58        | 57.43%  |
| 1920x1080 (FHD)   | 18        | 17.82%  |
| 1280x800 (WXGA)   | 11        | 10.89%  |
| 3840x2160 (4K)    | 3         | 2.97%   |
| 1360x768          | 3         | 2.97%   |
| 1280x1024 (SXGA)  | 2         | 1.98%   |
| 1024x600          | 2         | 1.98%   |
| 2560x1440 (QHD)   | 1         | 0.99%   |
| 1920x1200 (WUXGA) | 1         | 0.99%   |
| 1600x900 (HD+)    | 1         | 0.99%   |
| 1440x900 (WXGA+)  | 1         | 0.99%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 38        | 35.85%  |
| 14     | 22        | 20.75%  |
| 13     | 20        | 18.87%  |
| 21     | 4         | 3.77%   |
| 17     | 4         | 3.77%   |
| 10     | 4         | 3.77%   |
| 18     | 3         | 2.83%   |
| 11     | 3         | 2.83%   |
| 54     | 1         | 0.94%   |
| 52     | 1         | 0.94%   |
| 32     | 1         | 0.94%   |
| 31     | 1         | 0.94%   |
| 27     | 1         | 0.94%   |
| 24     | 1         | 0.94%   |
| 19     | 1         | 0.94%   |
| 12     | 1         | 0.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 78        | 74.29%  |
| 201-300     | 9         | 8.57%   |
| 401-500     | 7         | 6.67%   |
| 351-400     | 5         | 4.76%   |
| 501-600     | 2         | 1.9%    |
| 1001-1500   | 2         | 1.9%    |
| 701-800     | 1         | 0.95%   |
| 601-700     | 1         | 0.95%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 80        | 84.21%  |
| 16/10 | 12        | 12.63%  |
| 5/4   | 2         | 2.11%   |
| 3/2   | 1         | 1.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 41        | 38.68%  |
| 101-110        | 38        | 35.85%  |
| 41-50          | 4         | 3.77%   |
| 141-150        | 4         | 3.77%   |
| 51-60          | 3         | 2.83%   |
| 201-250        | 3         | 2.83%   |
| 121-130        | 3         | 2.83%   |
| More than 1000 | 2         | 1.89%   |
| 351-500        | 2         | 1.89%   |
| 151-200        | 2         | 1.89%   |
| 71-80          | 1         | 0.94%   |
| 61-70          | 1         | 0.94%   |
| 301-350        | 1         | 0.94%   |
| 251-300        | 1         | 0.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 52        | 50%     |
| 121-160       | 24        | 23.08%  |
| 51-100        | 21        | 20.19%  |
| 1-50          | 4         | 3.85%   |
| 161-240       | 2         | 1.92%   |
| More than 240 | 1         | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 86        | 86%     |
| 2     | 12        | 12%     |
| 3     | 1         | 1%      |
| 0     | 1         | 1%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 67        | 41.1%   |
| Qualcomm Atheros                | 35        | 21.47%  |
| Intel                           | 32        | 19.63%  |
| Broadcom                        | 12        | 7.36%   |
| Broadcom Limited                | 4         | 2.45%   |
| Marvell Technology Group        | 3         | 1.84%   |
| Samsung Electronics             | 2         | 1.23%   |
| JMicron Technology              | 2         | 1.23%   |
| Xiaomi                          | 1         | 0.61%   |
| Trendchip Technologies          | 1         | 0.61%   |
| Ralink Technology               | 1         | 0.61%   |
| Qualcomm Atheros Communications | 1         | 0.61%   |
| MediaTek                        | 1         | 0.61%   |
| AMD                             | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 33        | 17.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 17        | 8.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 6.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 3.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.68%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 5         | 2.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 4         | 2.11%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 1.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 1.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.58%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.58%   |
| Intel Wireless 7265                                                     | 3         | 1.58%   |
| Intel Centrino Wireless-N 105                                           | 3         | 1.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.05%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 1.05%   |
| Intel Wireless 8260                                                     | 2         | 1.05%   |
| Intel Wireless 7260                                                     | 2         | 1.05%   |
| Intel Wireless 3165                                                     | 2         | 1.05%   |
| Intel WiFi Link 5100                                                    | 2         | 1.05%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.05%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.05%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express             | 2         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.05%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.53%   |
| Trendchip Ethernet controller                                           | 1         | 0.53%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.53%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 0.53%   |
| Realtek Realtek Ethernet controller                                     | 1         | 0.53%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.53%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1         | 0.53%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.53%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 0.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 0.53%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                     | 1         | 0.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 0.53%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 0.53%   |
| Intel PRO/100 VE Network Connection                                     | 1         | 0.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.53%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.53%   |
| Intel Ethernet Connection I219-V                                        | 1         | 0.53%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 0.53%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.53%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 31.31%  |
| Qualcomm Atheros                | 28        | 28.28%  |
| Realtek Semiconductor           | 26        | 26.26%  |
| Broadcom                        | 10        | 10.1%   |
| Ralink Technology               | 1         | 1.01%   |
| Qualcomm Atheros Communications | 1         | 1.01%   |
| MediaTek                        | 1         | 1.01%   |
| Broadcom Limited                | 1         | 1.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 12.12%  |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 7.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 7.07%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 5         | 5.05%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 4.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 4.04%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 4.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 3.03%   |
| Intel Wireless 8265 / 8275                                              | 3         | 3.03%   |
| Intel Wireless 7265                                                     | 3         | 3.03%   |
| Intel Centrino Wireless-N 105                                           | 3         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 2.02%   |
| Intel Wireless 8260                                                     | 2         | 2.02%   |
| Intel Wireless 7260                                                     | 2         | 2.02%   |
| Intel Wireless 3165                                                     | 2         | 2.02%   |
| Intel WiFi Link 5100                                                    | 2         | 2.02%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 2.02%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 2.02%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.02%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 2.02%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 1.01%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 1.01%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.01%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.01%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.01%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.01%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.01%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.01%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.01%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.01%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.01%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 1         | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.01%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 55        | 61.8%   |
| Qualcomm Atheros         | 11        | 12.36%  |
| Intel                    | 9         | 10.11%  |
| Marvell Technology Group | 3         | 3.37%   |
| Broadcom Limited         | 3         | 3.37%   |
| Samsung Electronics      | 2         | 2.25%   |
| JMicron Technology       | 2         | 2.25%   |
| Broadcom                 | 2         | 2.25%   |
| Xiaomi                   | 1         | 1.12%   |
| Trendchip Technologies   | 1         | 1.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 36.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 18.89%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 4.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 3.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 3.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.22%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 2.22%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.22%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 2         | 2.22%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.11%   |
| Trendchip Ethernet controller                                     | 1         | 1.11%   |
| Realtek Realtek Ethernet controller                               | 1         | 1.11%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.11%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.11%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.11%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.11%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.11%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 1.11%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.11%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.11%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.11%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.11%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.11%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.11%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.11%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.11%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 1.11%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 96        | 52.17%  |
| Ethernet | 87        | 47.28%  |
| Modem    | 1         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 73        | 70.87%  |
| Ethernet | 30        | 29.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 81        | 82.65%  |
| 1     | 16        | 16.33%  |
| 0     | 1         | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 98        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 37.25%  |
| Qualcomm Atheros Communications | 10        | 19.61%  |
| IMC Networks                    | 9         | 17.65%  |
| Realtek Semiconductor           | 5         | 9.8%    |
| Broadcom                        | 4         | 7.84%   |
| Cambridge Silicon Radio         | 3         | 5.88%   |
| ASUSTek Computer                | 1         | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 23.53%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 7.84%   |
| Realtek Bluetooth Radio                             | 3         | 5.88%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 5.88%   |
| IMC Networks Bluetooth                              | 3         | 5.88%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 5.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 5.88%   |
| Realtek RTL8723B Bluetooth                          | 2         | 3.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 3.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 3.92%   |
| Intel AX201 Bluetooth                               | 2         | 3.92%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.92%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 3.92%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.96%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.96%   |
| Intel AX200 Bluetooth                               | 1         | 1.96%   |
| IMC Networks Wireless_Device                        | 1         | 1.96%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.96%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.96%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 87        | 81.31%  |
| AMD                   | 13        | 12.15%  |
| Nvidia                | 4         | 3.74%   |
| Realtek Semiconductor | 1         | 0.93%   |
| Microsoft             | 1         | 0.93%   |
| Logitech              | 1         | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 15.32%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 7.26%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 6.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 6.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 6.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 5.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 4.84%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 4.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.42%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.42%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.61%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.61%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.61%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.81%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Nvidia Audio device                                                                               | 1         | 0.81%   |
| Microsoft LifeChat LX-4000                                                                        | 1         | 0.81%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.81%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.81%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.81%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 1         | 0.81%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.81%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 1         | 0.81%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 17        | 20.99%  |
| Samsung Electronics | 13        | 16.05%  |
| Ramaxel Technology  | 11        | 13.58%  |
| Unknown             | 10        | 12.35%  |
| Micron Technology   | 9         | 11.11%  |
| Kingston            | 5         | 6.17%   |
| Crucial             | 5         | 6.17%   |
| Unknown (ABCD)      | 2         | 2.47%   |
| Elpida              | 2         | 2.47%   |
| Unknown             | 2         | 2.47%   |
| Unknown (081A)      | 1         | 1.23%   |
| Qimonda             | 1         | 1.23%   |
| Memox               | 1         | 1.23%   |
| Corsair             | 1         | 1.23%   |
| A-DATA Technology   | 1         | 1.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s                | 3         | 3.53%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s                   | 3         | 3.53%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s                   | 3         | 3.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 2.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 2.35%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s                     | 2         | 2.35%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s                   | 2         | 2.35%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s                    | 2         | 2.35%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s                   | 2         | 2.35%   |
| Unknown                                                                   | 2         | 2.35%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 1.18%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                            | 1         | 1.18%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 1.18%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                            | 1         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 1         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                                 | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 1         | 1.18%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 1.18%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2667MT/s                           | 1         | 1.18%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                             | 1         | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s       | 1         | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s              | 1         | 1.18%   |
| Unknown (081A) RAM HXMSH2GS03A2F1CL16 2GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s                     | 1         | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-RD 4GB SODIMM DDR3 1867MT/s                    | 1         | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.18%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.18%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.18%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s                    | 1         | 1.18%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s                    | 1         | 1.18%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                    | 1         | 1.18%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                    | 1         | 1.18%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 1.18%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8192MB SODIMM DDR4 2400MT/s                 | 1         | 1.18%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.18%   |
| SK hynix RAM 999999999999999999999999999999999999 1GB SODIMM DDR2 667MT/s | 1         | 1.18%   |
| SK hynix RAM 121212121212121212121212121212121212 2GB SODIMM DDR2 667MT/s | 1         | 1.18%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                               | 1         | 1.18%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s                     | 1         | 1.18%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s                  | 1         | 1.18%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s                  | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s            | 1         | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.18%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s                 | 1         | 1.18%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s                     | 1         | 1.18%   |
| Samsung RAM M4 70T2864DZ3-CE6 1GB SODIMM DDR 667MT/s                      | 1         | 1.18%   |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s                       | 1         | 1.18%   |
| Ramaxel RAM RMT3170MK58F8F1600 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.18%   |
| Qimonda RAM Module 1024MB SODIMM DDR2 533MT/s                             | 1         | 1.18%   |
| Micron RAM Module 8GB SODIMM DDR4 2133MT/s                                | 1         | 1.18%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.18%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.18%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s                     | 1         | 1.18%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.18%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s                | 1         | 1.18%   |
| Memox RAM LN-SD302160011SA8R 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 24        | 40%     |
| DDR4   | 18        | 30%     |
| DDR2   | 10        | 16.67%  |
| SDRAM  | 4         | 6.67%   |
| LPDDR4 | 3         | 5%      |
| DDR    | 1         | 1.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 54        | 94.74%  |
| Row Of Chips | 2         | 3.51%   |
| DIMM         | 1         | 1.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 23        | 33.82%  |
| 2048  | 22        | 32.35%  |
| 8192  | 17        | 25%     |
| 1024  | 4         | 5.88%   |
| 16384 | 2         | 2.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 22        | 31.88%  |
| 2667    | 7         | 10.14%  |
| 2400    | 7         | 10.14%  |
| 3200    | 6         | 8.7%    |
| 667     | 5         | 7.25%   |
| 1333    | 4         | 5.8%    |
| 1334    | 3         | 4.35%   |
| 4199    | 2         | 2.9%    |
| 2048    | 2         | 2.9%    |
| 1067    | 2         | 2.9%    |
| 533     | 2         | 2.9%    |
| Unknown | 2         | 2.9%    |
| 3266    | 1         | 1.45%   |
| 2133    | 1         | 1.45%   |
| 1867    | 1         | 1.45%   |
| 975     | 1         | 1.45%   |
| 800     | 1         | 1.45%   |

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
| Chicony Electronics                    | 16        | 21.62%  |
| Microdia                               | 11        | 14.86%  |
| Acer                                   | 11        | 14.86%  |
| Realtek Semiconductor                  | 9         | 12.16%  |
| IMC Networks                           | 5         | 6.76%   |
| Suyin                                  | 4         | 5.41%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.05%   |
| Syntek                                 | 2         | 2.7%    |
| Sunplus Innovation Technology          | 2         | 2.7%    |
| Ricoh                                  | 2         | 2.7%    |
| Lite-On Technology                     | 2         | 2.7%    |
| Tobii Technology AB                    | 1         | 1.35%   |
| Sonix Technology                       | 1         | 1.35%   |
| Quanta                                 | 1         | 1.35%   |
| Luxvisions Innotech Limited            | 1         | 1.35%   |
| Lenovo                                 | 1         | 1.35%   |
| Apple                                  | 1         | 1.35%   |
| ALi                                    | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                  | 4         | 5.41%   |
| Chicony USB 2.0 Camera                                        | 4         | 5.41%   |
| Acer HD Webcam                                                | 4         | 5.41%   |
| Microdia USB 2.0 Camera                                       | 3         | 4.05%   |
| Chicony Lenovo EasyCamera                                     | 3         | 4.05%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 2.7%    |
| IMC Networks USB 2.0 UVC VGA WebCam                           | 2         | 2.7%    |
| Chicony Integrated Camera                                     | 2         | 2.7%    |
| Chicony HD WebCam                                             | 2         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 2         | 2.7%    |
| Acer USB Camera                                               | 2         | 2.7%    |
| Acer Lenovo EasyCamera                                        | 2         | 2.7%    |
| Tobii AB EyeChip                                              | 1         | 1.35%   |
| Syntek USB Camera Device                                      | 1         | 1.35%   |
| Syntek Integrated Webcam                                      | 1         | 1.35%   |
| Suyin USB2.0 UVC 1.3M WebCam                                  | 1         | 1.35%   |
| Suyin HP Webcam 101                                           | 1         | 1.35%   |
| Suyin HD Video WebCam                                         | 1         | 1.35%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 1.35%   |
| Sunplus MTD Camera                                            | 1         | 1.35%   |
| Sunplus Integrated_Webcam_HD                                  | 1         | 1.35%   |
| Sonix USB2.0 HD UVC WebCam                                    | 1         | 1.35%   |
| Ricoh Sony Vaio Integrated Webcam                             | 1         | 1.35%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 1         | 1.35%   |
| Realtek USB2.0 camera                                         | 1         | 1.35%   |
| Realtek USB Camera                                            | 1         | 1.35%   |
| Realtek Integrated Webcam HD                                  | 1         | 1.35%   |
| Realtek Integrated Webcam                                     | 1         | 1.35%   |
| Realtek EasyCamera                                            | 1         | 1.35%   |
| Quanta HP Webcam                                              | 1         | 1.35%   |
| Microdia WebCam SC-13HDL12639P                                | 1         | 1.35%   |
| Microdia USB camera                                           | 1         | 1.35%   |
| Microdia Sonix USB 2.0 Camera                                 | 1         | 1.35%   |
| Microdia Laptop_Integrated_Webcam_HD                          | 1         | 1.35%   |
| Microdia Integrated_Webcam_HD                                 | 1         | 1.35%   |
| Microdia Integrated_Webcam_FHD                                | 1         | 1.35%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera           | 1         | 1.35%   |
| Lite-On TOSHIBA Web Camera - HD                               | 1         | 1.35%   |
| Lite-On HP HD Webcam                                          | 1         | 1.35%   |
| Lenovo CNF7237&CNF7238                                        | 1         | 1.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                            | 1         | 1.35%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 1         | 1.35%   |
| IMC Networks EasyCamera                                       | 1         | 1.35%   |
| Chicony USB2.0 VGA UVC WebCam                                 | 1         | 1.35%   |
| Chicony USB2.0 HD UVC WebCam                                  | 1         | 1.35%   |
| Chicony Lenovo Integrated Camera                              | 1         | 1.35%   |
| Chicony HP HD Camera                                          | 1         | 1.35%   |
| Chicony 1.3M HD WebCam                                        | 1         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD       | 1         | 1.35%   |
| Apple iPhone 5/5C/5S/6/SE                                     | 1         | 1.35%   |
| ALi Gateway Webcam                                            | 1         | 1.35%   |
| Acer Integrated Camera                                        | 1         | 1.35%   |
| Acer HP TrueVision HD                                         | 1         | 1.35%   |
| Acer BisonCam, NB Pro                                         | 1         | 1.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Validity Sensors    | 5         | 62.5%   |
| AuthenTec           | 2         | 25%     |
| Futronic Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 2         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader  | 2         | 25%     |
| AuthenTec AES2501 Fingerprint Sensor        | 2         | 25%     |
| Validity Sensors Fingerprint scanner        | 1         | 12.5%   |
| Futronic Fingerprint Scanner Model FS88     | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 4         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 50%     |
| Broadcom 5880                                  | 2         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 81        | 81%     |
| 1     | 16        | 16%     |
| 2     | 2         | 2%      |
| 4     | 1         | 1%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 33.33%  |
| Graphics card            | 4         | 16.67%  |
| Chipcard                 | 4         | 16.67%  |
| Net/wireless             | 3         | 12.5%   |
| Camera                   | 2         | 8.33%   |
| Storage                  | 1         | 4.17%   |
| Sound                    | 1         | 4.17%   |
| Communication controller | 1         | 4.17%   |

