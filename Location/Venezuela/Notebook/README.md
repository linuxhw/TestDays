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

Total: 133

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 8         | 8.42%   |
| Debian 11                    | 7         | 7.37%   |
| Debian 10                    | 6         | 6.32%   |
| Ubuntu 18.04                 | 5         | 5.26%   |
| OpenMandriva 4.3             | 5         | 5.26%   |
| Xubuntu 18.04                | 3         | 3.16%   |
| ROSA R9                      | 3         | 3.16%   |
| OpenMandriva 4.2             | 3         | 3.16%   |
| Kubuntu 20.04                | 3         | 3.16%   |
| KDE neon 20.04               | 3         | 3.16%   |
| Zorin 15                     | 2         | 2.11%   |
| Ubuntu 21.10                 | 2         | 2.11%   |
| Ubuntu 19.10                 | 2         | 2.11%   |
| Ubuntu 16.04                 | 2         | 2.11%   |
| Pop!_OS 21.04                | 2         | 2.11%   |
| Manjaro                      | 2         | 2.11%   |
| Linux Mint 20.3              | 2         | 2.11%   |
| Linux Mint 20                | 2         | 2.11%   |
| Fedora 35                    | 2         | 2.11%   |
| Zorin 16                     | 1         | 1.05%   |
| Xubuntu 21.10                | 1         | 1.05%   |
| Xubuntu 20.04                | 1         | 1.05%   |
| Ubuntu MATE 20.04            | 1         | 1.05%   |
| Ubuntu MATE 19.10            | 1         | 1.05%   |
| Ubuntu 22.04                 | 1         | 1.05%   |
| Solus 4.1                    | 1         | 1.05%   |
| ROSA R11                     | 1         | 1.05%   |
| Q4OS 4                       | 1         | 1.05%   |
| Pop!_OS 22.04                | 1         | 1.05%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 1.05%   |
| OpenMandriva 4.50            | 1         | 1.05%   |
| MX 20                        | 1         | 1.05%   |
| Manjaro 21.2.0               | 1         | 1.05%   |
| Manjaro 21.1.0               | 1         | 1.05%   |
| Manjaro 21.0                 | 1         | 1.05%   |
| Manjaro 20.1                 | 1         | 1.05%   |
| Lubuntu 18.04                | 1         | 1.05%   |
| LMDE 4                       | 1         | 1.05%   |
| Linux Mint 19.3              | 1         | 1.05%   |
| KDE neon 18.04               | 1         | 1.05%   |
| Garuda Linux Soaring         | 1         | 1.05%   |
| Feren OS 18.04               | 1         | 1.05%   |
| Fedora 36                    | 1         | 1.05%   |
| Fedora 34                    | 1         | 1.05%   |
| Fedora 33                    | 1         | 1.05%   |
| Deepin                       | 1         | 1.05%   |
| ArcoLinux Rolling            | 1         | 1.05%   |
| Arch                         | 1         | 1.05%   |
| Alpine 3.13.0_alpha20200917  | 1         | 1.05%   |
| AlmaLinux 8.5                | 1         | 1.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 20        | 21.51%  |
| Debian       | 12        | 12.9%   |
| OpenMandriva | 9         | 9.68%   |
| Manjaro      | 6         | 6.45%   |
| Xubuntu      | 5         | 5.38%   |
| Linux Mint   | 5         | 5.38%   |
| ROSA         | 4         | 4.3%    |
| KDE neon     | 4         | 4.3%    |
| Fedora       | 4         | 4.3%    |
| Zorin        | 3         | 3.23%   |
| Pop!_OS      | 3         | 3.23%   |
| Kubuntu      | 3         | 3.23%   |
| Ubuntu MATE  | 2         | 2.15%   |
| Solus        | 1         | 1.08%   |
| Q4OS         | 1         | 1.08%   |
| openSUSE     | 1         | 1.08%   |
| MX           | 1         | 1.08%   |
| Lubuntu      | 1         | 1.08%   |
| LMDE         | 1         | 1.08%   |
| Garuda Linux | 1         | 1.08%   |
| Feren OS     | 1         | 1.08%   |
| Deepin       | 1         | 1.08%   |
| ArcoLinux    | 1         | 1.08%   |
| Arch         | 1         | 1.08%   |
| Alpine       | 1         | 1.08%   |
| AlmaLinux    | 1         | 1.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                  | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003                  | 5         | 4.76%   |
| 5.4.0-42-generic                         | 4         | 3.81%   |
| 5.4.0-73-generic                         | 3         | 2.86%   |
| 5.4.0-52-generic                         | 3         | 2.86%   |
| 5.3.0-40-generic                         | 3         | 2.86%   |
| 5.13.0-39-generic                        | 3         | 2.86%   |
| 5.10.14-desktop-1omv4002                 | 3         | 2.86%   |
| 5.10.0-13-amd64                          | 3         | 2.86%   |
| 4.9.20-nrj-desktop-1rosa-x86_64          | 3         | 2.86%   |
| 4.19.0-17-amd64                          | 3         | 2.86%   |
| 5.4.0-89-generic                         | 2         | 1.9%    |
| 5.4.0-77-generic                         | 2         | 1.9%    |
| 5.4.0-48-generic                         | 2         | 1.9%    |
| 5.11.0-37-generic                        | 2         | 1.9%    |
| 5.10.0-11-amd64                          | 2         | 1.9%    |
| 5.0.0-37-generic                         | 2         | 1.9%    |
| 5.9.0-5-amd64                            | 1         | 0.95%   |
| 5.8.6-1-MANJARO                          | 1         | 0.95%   |
| 5.8.0-53-generic                         | 1         | 0.95%   |
| 5.8.0-45-generic                         | 1         | 0.95%   |
| 5.8.0-44-generic                         | 1         | 0.95%   |
| 5.8.0-41-generic                         | 1         | 0.95%   |
| 5.6.6-1-default                          | 1         | 0.95%   |
| 5.6.18-155.current                       | 1         | 0.95%   |
| 5.5.4-linux-xanmod-1-rosa-x86_64-xanmod3 | 1         | 0.95%   |
| 5.4.83-0-lts                             | 1         | 0.95%   |
| 5.4.105-1-MANJARO                        | 1         | 0.95%   |
| 5.4.0-91-generic                         | 1         | 0.95%   |
| 5.4.0-86-generic                         | 1         | 0.95%   |
| 5.4.0-70-generic                         | 1         | 0.95%   |
| 5.4.0-31-generic                         | 1         | 0.95%   |
| 5.4.0-107-generic                        | 1         | 0.95%   |
| 5.3.0-42-generic                         | 1         | 0.95%   |
| 5.3.0-29-generic                         | 1         | 0.95%   |
| 5.17.2-xanmod1                           | 1         | 0.95%   |
| 5.17.11-300.fc36.x86_64                  | 1         | 0.95%   |
| 5.15.8-200.fc35.x86_64                   | 1         | 0.95%   |
| 5.15.6-2-MANJARO                         | 1         | 0.95%   |
| 5.15.28-1-MANJARO                        | 1         | 0.95%   |
| 5.15.2-2-MANJARO                         | 1         | 0.95%   |
| 5.15.19-1-MANJARO                        | 1         | 0.95%   |
| 5.15.13-xanmod1                          | 1         | 0.95%   |
| 5.15.10-zen1-1-zen                       | 1         | 0.95%   |
| 5.15.0-33-generic                        | 1         | 0.95%   |
| 5.14.10-300.fc35.x86_64                  | 1         | 0.95%   |
| 5.14.10-200.fc34.x86_64                  | 1         | 0.95%   |
| 5.13.13-arch1-1                          | 1         | 0.95%   |
| 5.13.0-41-generic                        | 1         | 0.95%   |
| 5.13.0-37-generic                        | 1         | 0.95%   |
| 5.13.0-28-generic                        | 1         | 0.95%   |
| 5.13.0-19-generic                        | 1         | 0.95%   |
| 5.12.4-desktop-1omv4050                  | 1         | 0.95%   |
| 5.12.19-1-MANJARO                        | 1         | 0.95%   |
| 5.11.0-7633-generic                      | 1         | 0.95%   |
| 5.11.0-7620-generic                      | 1         | 0.95%   |
| 5.11.0-38-generic                        | 1         | 0.95%   |
| 5.11.0-25-generic                        | 1         | 0.95%   |
| 5.10.5-amd64-desktop+                    | 1         | 0.95%   |
| 5.10.11-200.fc33.x86_64                  | 1         | 0.95%   |
| 5.10.10-arch1-1                          | 1         | 0.95%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 19.39%  |
| 4.19.0  | 8         | 8.16%   |
| 5.13.0  | 7         | 7.14%   |
| 5.10.0  | 7         | 7.14%   |
| 5.11.0  | 6         | 6.12%   |
| 5.3.0   | 5         | 5.1%    |
| 5.16.7  | 5         | 5.1%    |
| 4.15.0  | 4         | 4.08%   |
| 5.8.0   | 3         | 3.06%   |
| 5.10.14 | 3         | 3.06%   |
| 4.9.20  | 3         | 3.06%   |
| 5.14.10 | 2         | 2.04%   |
| 5.0.0   | 2         | 2.04%   |
| 5.9.0   | 1         | 1.02%   |
| 5.8.6   | 1         | 1.02%   |
| 5.6.6   | 1         | 1.02%   |
| 5.6.18  | 1         | 1.02%   |
| 5.5.4   | 1         | 1.02%   |
| 5.4.83  | 1         | 1.02%   |
| 5.4.105 | 1         | 1.02%   |
| 5.17.2  | 1         | 1.02%   |
| 5.17.11 | 1         | 1.02%   |
| 5.15.8  | 1         | 1.02%   |
| 5.15.6  | 1         | 1.02%   |
| 5.15.28 | 1         | 1.02%   |
| 5.15.2  | 1         | 1.02%   |
| 5.15.19 | 1         | 1.02%   |
| 5.15.13 | 1         | 1.02%   |
| 5.15.10 | 1         | 1.02%   |
| 5.15.0  | 1         | 1.02%   |
| 5.13.13 | 1         | 1.02%   |
| 5.12.4  | 1         | 1.02%   |
| 5.12.19 | 1         | 1.02%   |
| 5.10.5  | 1         | 1.02%   |
| 5.10.11 | 1         | 1.02%   |
| 5.10.10 | 1         | 1.02%   |
| 4.18.0  | 1         | 1.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 21        | 21.65%  |
| 5.10    | 13        | 13.4%   |
| 5.13    | 8         | 8.25%   |
| 4.19    | 8         | 8.25%   |
| 5.15    | 7         | 7.22%   |
| 5.11    | 6         | 6.19%   |
| 5.3     | 5         | 5.15%   |
| 5.16    | 5         | 5.15%   |
| 5.8     | 4         | 4.12%   |
| 4.15    | 4         | 4.12%   |
| 4.9     | 3         | 3.09%   |
| 5.6     | 2         | 2.06%   |
| 5.17    | 2         | 2.06%   |
| 5.14    | 2         | 2.06%   |
| 5.12    | 2         | 2.06%   |
| 5.0     | 2         | 2.06%   |
| 5.9     | 1         | 1.03%   |
| 5.5     | 1         | 1.03%   |
| 4.18    | 1         | 1.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 80        | 88.89%  |
| i686   | 10        | 11.11%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 31        | 32.29%  |
| KDE5          | 19        | 19.79%  |
| XFCE          | 17        | 17.71%  |
| KDE           | 6         | 6.25%   |
| Unknown       | 6         | 6.25%   |
| MATE          | 4         | 4.17%   |
| KDE4          | 3         | 3.13%   |
| X-Cinnamon    | 2         | 2.08%   |
| Unity         | 2         | 2.08%   |
| Cinnamon      | 2         | 2.08%   |
| LXQt          | 1         | 1.04%   |
| GNOME Classic | 1         | 1.04%   |
| Deepin        | 1         | 1.04%   |
| Budgie        | 1         | 1.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 81        | 90%     |
| Wayland | 9         | 10%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 39        | 41.05%  |
| SDDM    | 17        | 17.89%  |
| GDM     | 14        | 14.74%  |
| LightDM | 12        | 12.63%  |
| GDM3    | 7         | 7.37%   |
| TDM     | 3         | 3.16%   |
| KDM     | 3         | 3.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_VE   | 51        | 54.26%  |
| en_US   | 29        | 30.85%  |
| es_ES   | 7         | 7.45%   |
| Unknown | 6         | 6.38%   |
| en_CA   | 1         | 1.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 65        | 71.43%  |
| EFI  | 26        | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 71        | 78.02%  |
| Overlay | 8         | 8.79%   |
| Btrfs   | 6         | 6.59%   |
| Xfs     | 3         | 3.3%    |
| Unknown | 3         | 3.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 51        | 54.26%  |
| MBR     | 22        | 23.4%   |
| GPT     | 21        | 22.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 81        | 87.1%   |
| Yes       | 12        | 12.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 64.84%  |
| Yes       | 32        | 35.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 17        | 18.89%  |
| Dell                | 17        | 18.89%  |
| VIT                 | 15        | 16.67%  |
| Hewlett-Packard     | 12        | 13.33%  |
| Intel               | 5         | 5.56%   |
| ASUSTek Computer    | 5         | 5.56%   |
| Unknown             | 4         | 4.44%   |
| Acer                | 3         | 3.33%   |
| UNIQCELL            | 1         | 1.11%   |
| Toshiba             | 1         | 1.11%   |
| Sony                | 1         | 1.11%   |
| Samsung Electronics | 1         | 1.11%   |
| Pegatron            | 1         | 1.11%   |
| MSI                 | 1         | 1.11%   |
| GPU Company         | 1         | 1.11%   |
| Gateway             | 1         | 1.11%   |
| Exo                 | 1         | 1.11%   |
| Clevo               | 1         | 1.11%   |
| AVITA               | 1         | 1.11%   |
| Alienware           | 1         | 1.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| VIT P2400                           | 5         | 5.56%   |
| Intel powered classmate PC          | 5         | 5.56%   |
| Unknown                             | 4         | 4.44%   |
| VIT P3400                           | 3         | 3.33%   |
| VIT P2402                           | 2         | 2.22%   |
| VIT M2421                           | 2         | 2.22%   |
| VIT M2420                           | 2         | 2.22%   |
| Lenovo IdeaPad S100c 20194          | 2         | 2.22%   |
| Lenovo 3000 N200 0769ARS            | 2         | 2.22%   |
| Dell Inspiron 1545                  | 2         | 2.22%   |
| VIT P1400                           | 1         | 1.11%   |
| UNIQCELL Q15.6                      | 1         | 1.11%   |
| Toshiba Satellite E55t-A            | 1         | 1.11%   |
| Sony VGN-FW510F                     | 1         | 1.11%   |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 1.11%   |
| Pegatron T14AF                      | 1         | 1.11%   |
| MSI MS-1454                         | 1         | 1.11%   |
| Lenovo Z50-75 80EC                  | 1         | 1.11%   |
| Lenovo ThinkPad X201 3680AE2        | 1         | 1.11%   |
| Lenovo ThinkPad SL400 2743A48       | 1         | 1.11%   |
| Lenovo ThinkPad Edge 01962AS        | 1         | 1.11%   |
| Lenovo ThinkPad E560 20EV002FUS     | 1         | 1.11%   |
| Lenovo IdeaPad S110 20126           | 1         | 1.11%   |
| Lenovo IdeaPad 5 14ALC05 82LM       | 1         | 1.11%   |
| Lenovo IdeaPad 330-15ARR 81D2       | 1         | 1.11%   |
| Lenovo IdeaPad 3 15IIL05 81WE       | 1         | 1.11%   |
| Lenovo G570 4334                    | 1         | 1.11%   |
| Lenovo G480 20150                   | 1         | 1.11%   |
| Lenovo G460 20041                   | 1         | 1.11%   |
| Lenovo B40-70 20392                 | 1         | 1.11%   |
| HP Presario V2000 (EW997LA#ABM)     | 1         | 1.11%   |
| HP Presario C700                    | 1         | 1.11%   |
| HP Pavilion dv6700                  | 1         | 1.11%   |
| HP Pavilion dv6500                  | 1         | 1.11%   |
| HP Pavilion dv6000 (RV216UA#ABA)    | 1         | 1.11%   |
| HP Pavilion dv6                     | 1         | 1.11%   |
| HP Pavilion dv5                     | 1         | 1.11%   |
| HP Pavilion dv4                     | 1         | 1.11%   |
| HP Laptop 15-ef2xxx                 | 1         | 1.11%   |
| HP EliteBook 840 G3                 | 1         | 1.11%   |
| HP Compaq Presario C700             | 1         | 1.11%   |
| HP 2000                             | 1         | 1.11%   |
| GPU Company GWTN156-11              | 1         | 1.11%   |
| Gateway NV57H                       | 1         | 1.11%   |
| Exo AIO A210                        | 1         | 1.11%   |
| Dell XPS 15 7590                    | 1         | 1.11%   |
| Dell Vostro 5402                    | 1         | 1.11%   |
| Dell Vostro 1500                    | 1         | 1.11%   |
| Dell Precision 7710                 | 1         | 1.11%   |
| Dell Latitude E7450                 | 1         | 1.11%   |
| Dell Latitude E6420                 | 1         | 1.11%   |
| Dell Latitude 5590                  | 1         | 1.11%   |
| Dell Inspiron 5570                  | 1         | 1.11%   |
| Dell Inspiron 5520                  | 1         | 1.11%   |
| Dell Inspiron 5502                  | 1         | 1.11%   |
| Dell Inspiron 5437                  | 1         | 1.11%   |
| Dell Inspiron 3421                  | 1         | 1.11%   |
| Dell Inspiron 3180                  | 1         | 1.11%   |
| Dell Inspiron 14-3467               | 1         | 1.11%   |
| Dell Inspiron 1018                  | 1         | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 10        | 11.11%  |
| Lenovo IdeaPad         | 6         | 6.67%   |
| HP Pavilion            | 6         | 6.67%   |
| VIT P2400              | 5         | 5.56%   |
| Intel powered          | 5         | 5.56%   |
| Lenovo ThinkPad        | 4         | 4.44%   |
| Unknown                | 4         | 4.44%   |
| VIT P3400              | 3         | 3.33%   |
| Dell Latitude          | 3         | 3.33%   |
| VIT P2402              | 2         | 2.22%   |
| VIT M2421              | 2         | 2.22%   |
| VIT M2420              | 2         | 2.22%   |
| Lenovo 3000            | 2         | 2.22%   |
| HP Presario            | 2         | 2.22%   |
| Dell Vostro            | 2         | 2.22%   |
| Acer Aspire            | 2         | 2.22%   |
| VIT P1400              | 1         | 1.11%   |
| UNIQCELL Q15.6         | 1         | 1.11%   |
| Toshiba Satellite      | 1         | 1.11%   |
| Sony VGN-FW510F        | 1         | 1.11%   |
| Samsung 355V4C         | 1         | 1.11%   |
| Pegatron T14AF         | 1         | 1.11%   |
| MSI MS-1454            | 1         | 1.11%   |
| Lenovo Z50-75          | 1         | 1.11%   |
| Lenovo G570            | 1         | 1.11%   |
| Lenovo G480            | 1         | 1.11%   |
| Lenovo G460            | 1         | 1.11%   |
| Lenovo B40-70          | 1         | 1.11%   |
| HP Laptop              | 1         | 1.11%   |
| HP EliteBook           | 1         | 1.11%   |
| HP Compaq              | 1         | 1.11%   |
| HP 2000                | 1         | 1.11%   |
| GPU Company GWTN156-11 | 1         | 1.11%   |
| Gateway NV57H          | 1         | 1.11%   |
| Exo AIO                | 1         | 1.11%   |
| Dell XPS               | 1         | 1.11%   |
| Dell Precision         | 1         | 1.11%   |
| Clevo W54xEU           | 1         | 1.11%   |
| AVITA NS14A1US         | 1         | 1.11%   |
| ASUS X555DA            | 1         | 1.11%   |
| ASUS X553MA            | 1         | 1.11%   |
| ASUS VivoBook          | 1         | 1.11%   |
| ASUS TUF               | 1         | 1.11%   |
| ASUS ASUS              | 1         | 1.11%   |
| Alienware 17           | 1         | 1.11%   |
| Acer TravelMate        | 1         | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 12        | 13.33%  |
| 2012    | 11        | 12.22%  |
| 2011    | 11        | 12.22%  |
| 2010    | 8         | 8.89%   |
| 2007    | 8         | 8.89%   |
| 2008    | 6         | 6.67%   |
| 2021    | 5         | 5.56%   |
| 2018    | 5         | 5.56%   |
| 2014    | 5         | 5.56%   |
| 2020    | 4         | 4.44%   |
| 2017    | 4         | 4.44%   |
| 2015    | 3         | 3.33%   |
| 2009    | 3         | 3.33%   |
| 2019    | 2         | 2.22%   |
| 2016    | 1         | 1.11%   |
| 2006    | 1         | 1.11%   |
| Unknown | 1         | 1.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 90        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 86        | 95.56%  |
| Enabled  | 4         | 4.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 90        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 23        | 25.27%  |
| 4.01-8.0   | 22        | 24.18%  |
| 1.01-2.0   | 22        | 24.18%  |
| 8.01-16.0  | 12        | 13.19%  |
| 16.01-24.0 | 5         | 5.49%   |
| 2.01-3.0   | 4         | 4.4%    |
| 32.01-64.0 | 2         | 2.2%    |
| 0.51-1.0   | 1         | 1.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 40        | 41.24%  |
| 2.01-3.0   | 23        | 23.71%  |
| 0.51-1.0   | 16        | 16.49%  |
| 4.01-8.0   | 10        | 10.31%  |
| 3.01-4.0   | 7         | 7.22%   |
| 16.01-24.0 | 1         | 1.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 64        | 70.33%  |
| 2      | 23        | 25.27%  |
| 3      | 4         | 4.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 57.78%  |
| No        | 38        | 42.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 91.21%  |
| No        | 8         | 8.79%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 97.78%  |
| No        | 2         | 2.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 52.75%  |
| Yes       | 43        | 47.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Venezuela | 90        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 39        | 40.63%  |
| Maracaibo                  | 12        | 12.5%   |
| Mérida                    | 6         | 6.25%   |
| Maracay                    | 6         | 6.25%   |
| Barcelona                  | 4         | 4.17%   |
| Barquisimeto               | 3         | 3.13%   |
| Maturín                   | 2         | 2.08%   |
| Lecherias                  | 2         | 2.08%   |
| Valencia                   | 1         | 1.04%   |
| San Juan Bautista          | 1         | 1.04%   |
| San Diego                  | 1         | 1.04%   |
| San Cristóbal             | 1         | 1.04%   |
| San Carlos del Zulia       | 1         | 1.04%   |
| Puerto Ordaz and San Felix | 1         | 1.04%   |
| Puerto Cumarebo            | 1         | 1.04%   |
| Puerto Cruz                | 1         | 1.04%   |
| Porlamar                   | 1         | 1.04%   |
| Parroquia El Recreo        | 1         | 1.04%   |
| Mariara                    | 1         | 1.04%   |
| Los Palos Grandes          | 1         | 1.04%   |
| Las Vegas                  | 1         | 1.04%   |
| Guatire                    | 1         | 1.04%   |
| Guarenas                   | 1         | 1.04%   |
| Guanare                    | 1         | 1.04%   |
| El Hatillo Municipality    | 1         | 1.04%   |
| Ciudad Guayana             | 1         | 1.04%   |
| Ciudad Bolívar            | 1         | 1.04%   |
| Charallave                 | 1         | 1.04%   |
| Cagua                      | 1         | 1.04%   |
| Barinas                    | 1         | 1.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 26     | 23.76%  |
| WDC                 | 22        | 29     | 21.78%  |
| Toshiba             | 10        | 10     | 9.9%    |
| Samsung Electronics | 7         | 7      | 6.93%   |
| Hitachi             | 5         | 5      | 4.95%   |
| LITEONIT            | 4         | 6      | 3.96%   |
| SanDisk             | 3         | 3      | 2.97%   |
| Kingston            | 3         | 4      | 2.97%   |
| Intel               | 3         | 4      | 2.97%   |
| Crucial             | 3         | 4      | 2.97%   |
| Unknown             | 2         | 2      | 1.98%   |
| SPCC                | 2         | 3      | 1.98%   |
| HGST                | 2         | 2      | 1.98%   |
| Fujitsu             | 2         | 2      | 1.98%   |
| Vaseky              | 1         | 1      | 0.99%   |
| Silicon Motion      | 1         | 1      | 0.99%   |
| PNY                 | 1         | 1      | 0.99%   |
| Micron Technology   | 1         | 3      | 0.99%   |
| KingFast            | 1         | 1      | 0.99%   |
| Intenso             | 1         | 1      | 0.99%   |
| Dell                | 1         | 1      | 0.99%   |
| BIWIN               | 1         | 2      | 0.99%   |
| Apacer              | 1         | 1      | 0.99%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB      | 4         | 3.92%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 3         | 2.94%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 2.94%   |
| Seagate ST250LM004 HN-M250MBB 250GB  | 3         | 2.94%   |
| LITEONIT LMS-32L6M 32GB SSD          | 3         | 2.94%   |
| WDC WD5000LPVT-08G33T1 500GB         | 2         | 1.96%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 1.96%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.96%   |
| Toshiba MQ01ABF032 320GB             | 2         | 1.96%   |
| Seagate ST320LM000 HM321HI 320GB     | 2         | 1.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.96%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.96%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.98%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.98%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.98%   |
| WDC WD3200LPVX-22V0TT0 320GB         | 1         | 0.98%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 0.98%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.98%   |
| WDC WD3200BEVT-00A0RT0 320GB         | 1         | 0.98%   |
| WDC WD3200BEKT-60F3T1 320GB          | 1         | 0.98%   |
| WDC WD1600BEVT-88ZCT0 160GB          | 1         | 0.98%   |
| WDC WD1600BEVS-22RST0 160GB          | 1         | 0.98%   |
| WDC WD1200BEVS-60UST0 120GB          | 1         | 0.98%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.98%   |
| Vaseky V800/128G 128GB               | 1         | 0.98%   |
| Unknown USDU1  32GB                  | 1         | 0.98%   |
| Unknown MMC128  128GB                | 1         | 0.98%   |
| Toshiba THNSNH256GBST SSD            | 1         | 0.98%   |
| Toshiba MQ01ACF050 500GB             | 1         | 0.98%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.98%   |
| Toshiba MQ01ABD050 500GB             | 1         | 0.98%   |
| Toshiba MK3275GSX 320GB              | 1         | 0.98%   |
| Toshiba MK1652GSX 160GB              | 1         | 0.98%   |
| SPCC Solid State Disk 512GB          | 1         | 0.98%   |
| SPCC Solid State Disk 128GB          | 1         | 0.98%   |
| Silicon Motion NVME SSD 512GB        | 1         | 0.98%   |
| Seagate ST9500325AS 500GB            | 1         | 0.98%   |
| Seagate ST9320423AS 320GB            | 1         | 0.98%   |
| Seagate ST9160314AS 160GB            | 1         | 0.98%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 0.98%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 0.98%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 0.98%   |
| Seagate ST320LT012-9WS14C 320GB      | 1         | 0.98%   |
| Seagate ST320LT012-1DG14C 320GB      | 1         | 0.98%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 1         | 0.98%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 0.98%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 0.98%   |
| Seagate Backup+ SL 1TB               | 1         | 0.98%   |
| Seagate BACKUP+ Mac 500GB            | 1         | 0.98%   |
| SanDisk SSD PLUS 480GB               | 1         | 0.98%   |
| SanDisk SSD PLUS 240GB               | 1         | 0.98%   |
| Sandisk NVMe SSD Drive 1TB           | 1         | 0.98%   |
| Samsung SSD PM871b M.2 2280 128GB    | 1         | 0.98%   |
| Samsung SSD 830 Series 128GB         | 1         | 0.98%   |
| Samsung MZNTE128HMGR-00000 128GB SSD | 1         | 0.98%   |
| Samsung MZALQ512HBLU-00BL2 512GB     | 1         | 0.98%   |
| Samsung MZALQ256HAJD-000L2 256GB     | 1         | 0.98%   |
| Samsung HN-M320MBB 320GB             | 1         | 0.98%   |
| Samsung HM250HI 250GB                | 1         | 0.98%   |
| PNY CS900 480GB SSD                  | 1         | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 24     | 34.92%  |
| WDC                 | 21        | 28     | 33.33%  |
| Toshiba             | 9         | 9      | 14.29%  |
| Hitachi             | 5         | 5      | 7.94%   |
| Samsung Electronics | 2         | 2      | 3.17%   |
| HGST                | 2         | 2      | 3.17%   |
| Fujitsu             | 2         | 2      | 3.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| LITEONIT            | 4         | 6      | 16.67%  |
| Samsung Electronics | 3         | 3      | 12.5%   |
| Crucial             | 3         | 4      | 12.5%   |
| SPCC                | 2         | 3      | 8.33%   |
| SanDisk             | 2         | 2      | 8.33%   |
| Kingston            | 2         | 3      | 8.33%   |
| Vaseky              | 1         | 1      | 4.17%   |
| Toshiba             | 1         | 1      | 4.17%   |
| PNY                 | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 3      | 4.17%   |
| KingFast            | 1         | 1      | 4.17%   |
| Intenso             | 1         | 1      | 4.17%   |
| Dell                | 1         | 1      | 4.17%   |
| BIWIN               | 1         | 2      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 62        | 72     | 62.63%  |
| SSD     | 23        | 32     | 23.23%  |
| NVMe    | 10        | 11     | 10.1%   |
| MMC     | 2         | 2      | 2.02%   |
| Unknown | 2         | 2      | 2.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 80        | 104    | 85.11%  |
| NVMe | 10        | 11     | 10.64%  |
| SAS  | 2         | 2      | 2.13%   |
| MMC  | 2         | 2      | 2.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 71        | 83     | 83.53%  |
| 0.51-1.0   | 13        | 20     | 15.29%  |
| 1.01-2.0   | 1         | 1      | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 29        | 30.85%  |
| 101-250    | 26        | 27.66%  |
| 501-1000   | 14        | 14.89%  |
| 21-50      | 9         | 9.57%   |
| 1-20       | 7         | 7.45%   |
| 51-100     | 5         | 5.32%   |
| 1001-2000  | 3         | 3.19%   |
| 2001-3000  | 1         | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 36        | 37.5%   |
| 21-50    | 20        | 20.83%  |
| 51-100   | 14        | 14.58%  |
| 101-250  | 13        | 13.54%  |
| 251-500  | 8         | 8.33%   |
| 501-1000 | 5         | 5.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 1      | 6.25%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 6.25%   |
| WDC WD1200BEVS-60UST0 120GB          | 1         | 1      | 6.25%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2      | 6.25%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 6.25%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 6.25%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 6.25%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 6.25%   |
| Samsung Electronics HN-M320MBB 320GB | 1         | 1      | 6.25%   |
| Samsung Electronics HM250HI 250GB    | 1         | 1      | 6.25%   |
| Intel SSDPEKKW256G7 256GB            | 1         | 1      | 6.25%   |
| Hitachi HTS543232L9A300 320GB        | 1         | 1      | 6.25%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1      | 6.25%   |
| Hitachi HTS542525K9SA00 250GB        | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 25%     |
| Seagate             | 4         | 4      | 25%     |
| Hitachi             | 3         | 3      | 18.75%  |
| Toshiba             | 2         | 2      | 12.5%   |
| Samsung Electronics | 2         | 2      | 12.5%   |
| Intel               | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 26.67%  |
| Seagate             | 4         | 4      | 26.67%  |
| Hitachi             | 3         | 3      | 20%     |
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 16     | 93.75%  |
| NVMe | 1         | 1      | 6.25%   |

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
| Detected | 52        | 70     | 54.17%  |
| Works    | 28        | 32     | 29.17%  |
| Malfunc  | 16        | 17     | 16.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 77        | 81.05%  |
| AMD                         | 11        | 11.58%  |
| Sandisk                     | 2         | 2.11%   |
| Samsung Electronics         | 2         | 2.11%   |
| Silicon Motion              | 1         | 1.05%   |
| Phison Electronics          | 1         | 1.05%   |
| Kingston Technology Company | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 14.02%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 8.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 7.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 6.54%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 6         | 5.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 5.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 4.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 4.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 3.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 3.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 2.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.8%    |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.87%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.87%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.87%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.93%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.93%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 0.93%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.93%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.93%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.93%   |
| Intel SSD 600P Series                                                          | 1         | 0.93%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.93%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 0.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 0.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 0.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 0.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 0.93%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 0.93%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 0.93%   |
| AMD IXP SB4x0 IDE Controller                                                   | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 71        | 68.93%  |
| IDE  | 13        | 12.62%  |
| NVMe | 10        | 9.71%   |
| RAID | 9         | 8.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 78        | 86.67%  |
| AMD    | 12        | 13.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz             | 4         | 4.44%   |
| Intel Atom CPU N455 @ 1.66GHz               | 4         | 4.44%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 3         | 3.33%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 3         | 3.33%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz        | 3         | 3.33%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 2         | 2.22%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 2.22%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 2.22%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 2.22%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 2.22%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 2         | 2.22%   |
| Intel Atom CPU N570 @ 1.66GHz               | 2         | 2.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 2.22%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.11%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 1.11%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 1.11%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1         | 1.11%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 1.11%   |
| Intel Genuine CPU T2080 @ 1.73GHz           | 1         | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.11%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.11%   |
| Intel Core i7-7820HK CPU @ 2.90GHz          | 1         | 1.11%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.11%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.11%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 1.11%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 1.11%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 1.11%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.11%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz            | 1         | 1.11%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.11%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.11%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.11%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.11%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.11%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.11%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.11%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.11%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 1.11%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.11%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 1.11%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.11%   |
| Intel Core i3-4000M CPU @ 2.40GHz           | 1         | 1.11%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.11%   |
| Intel Core i3-2375M CPU @ 1.50GHz           | 1         | 1.11%   |
| Intel Core i3-2370M CPU @ 2.40GHz           | 1         | 1.11%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.11%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 1.11%   |
| Intel Core i3 CPU M 390 @ 2.67GHz           | 1         | 1.11%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.11%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz        | 1         | 1.11%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.11%   |
| Intel Core 2 Duo CPU T5270 @ 1.40GHz        | 1         | 1.11%   |
| Intel Celeron CPU N2930 @ 1.83GHz           | 1         | 1.11%   |
| Intel Celeron CPU N2805 @ 1.46GHz           | 1         | 1.11%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 1         | 1.11%   |
| Intel Celeron CPU 1000M @ 1.80GHz           | 1         | 1.11%   |
| Intel Atom CPU N2800 @ 1.86GHz              | 1         | 1.11%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz     | 1         | 1.11%   |
| AMD Turion X2 Dual-Core Mobile RM-70        | 1         | 1.11%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 1         | 1.11%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 16        | 17.78%  |
| Intel Core i3                  | 16        | 17.78%  |
| Intel Core 2 Duo               | 11        | 12.22%  |
| Intel Core i7                  | 9         | 10%     |
| Intel Celeron                  | 8         | 8.89%   |
| Intel Atom                     | 7         | 7.78%   |
| Other                          | 3         | 3.33%   |
| AMD Ryzen 5                    | 3         | 3.33%   |
| Intel Pentium Dual-Core        | 2         | 2.22%   |
| Intel Pentium                  | 2         | 2.22%   |
| Intel Genuine                  | 2         | 2.22%   |
| AMD A10                        | 2         | 2.22%   |
| Intel Pentium Silver           | 1         | 1.11%   |
| Intel Pentium Dual             | 1         | 1.11%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 1.11%   |
| AMD Ryzen 7                    | 1         | 1.11%   |
| AMD Ryzen 3                    | 1         | 1.11%   |
| AMD Mobile Sempron             | 1         | 1.11%   |
| AMD E1                         | 1         | 1.11%   |
| AMD E                          | 1         | 1.11%   |
| AMD A6                         | 1         | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 66        | 73.33%  |
| 4       | 13        | 14.44%  |
| 1       | 5         | 5.56%   |
| 6       | 3         | 3.33%   |
| Unknown | 2         | 2.22%   |
| 8       | 1         | 1.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 90        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 57        | 63.33%  |
| 1       | 31        | 34.44%  |
| Unknown | 2         | 2.22%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 85        | 94.44%  |
| 64-bit         | 3         | 3.33%   |
| 32-bit         | 2         | 2.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 18.28%  |
| 0x306a9    | 11        | 11.83%  |
| 0x206a7    | 10        | 10.75%  |
| 0x1067a    | 9         | 9.68%   |
| 0x6fd      | 5         | 5.38%   |
| 0x106ca    | 5         | 5.38%   |
| 0x806e9    | 3         | 3.23%   |
| 0x806c1    | 3         | 3.23%   |
| 0x40651    | 3         | 3.23%   |
| 0x20655    | 3         | 3.23%   |
| 0x406e3    | 2         | 2.15%   |
| 0x08608103 | 2         | 2.15%   |
| 0x05000119 | 2         | 2.15%   |
| 0x906e9    | 1         | 1.08%   |
| 0x806ea    | 1         | 1.08%   |
| 0x706e5    | 1         | 1.08%   |
| 0x6ec      | 1         | 1.08%   |
| 0x506e3    | 1         | 1.08%   |
| 0x306d4    | 1         | 1.08%   |
| 0x306c3    | 1         | 1.08%   |
| 0x30678    | 1         | 1.08%   |
| 0x30673    | 1         | 1.08%   |
| 0x30661    | 1         | 1.08%   |
| 0x20652    | 1         | 1.08%   |
| 0x08600102 | 1         | 1.08%   |
| 0x0810100b | 1         | 1.08%   |
| 0x08101007 | 1         | 1.08%   |
| 0x06006704 | 1         | 1.08%   |
| 0x06006118 | 1         | 1.08%   |
| 0x06003106 | 1         | 1.08%   |
| 0x02000057 | 1         | 1.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 14        | 15.56%  |
| IvyBridge       | 12        | 13.33%  |
| Penryn          | 8         | 8.89%   |
| KabyLake        | 7         | 7.78%   |
| Core            | 7         | 7.78%   |
| Bonnell         | 7         | 7.78%   |
| Westmere        | 6         | 6.67%   |
| Haswell         | 4         | 4.44%   |
| TigerLake       | 3         | 3.33%   |
| Skylake         | 3         | 3.33%   |
| Zen             | 2         | 2.22%   |
| Silvermont      | 2         | 2.22%   |
| Excavator       | 2         | 2.22%   |
| Bobcat          | 2         | 2.22%   |
| Unknown         | 2         | 2.22%   |
| Zen 2           | 1         | 1.11%   |
| Steamroller     | 1         | 1.11%   |
| P6              | 1         | 1.11%   |
| K8 Hammer       | 1         | 1.11%   |
| K8 & K10 hybrid | 1         | 1.11%   |
| IceLake         | 1         | 1.11%   |
| Goldmont plus   | 1         | 1.11%   |
| Goldmont        | 1         | 1.11%   |
| Broadwell       | 1         | 1.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 77        | 79.38%  |
| AMD    | 14        | 14.43%  |
| Nvidia | 6         | 6.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 14        | 13.33%  |
| Intel 3rd Gen Core processor Graphics Controller                              | 12        | 11.43%  |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 7         | 6.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 7         | 6.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 7         | 6.67%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 5.71%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 6         | 5.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 2.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 2.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 1.9%    |
| Intel HD Graphics 630                                                         | 2         | 1.9%    |
| Intel HD Graphics 620                                                         | 2         | 1.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 1.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.9%    |
| AMD Lucienne                                                                  | 2         | 1.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.95%   |
| Nvidia TU117M                                                                 | 1         | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.95%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                      | 1         | 0.95%   |
| Nvidia GM204GLM [Quadro M3000M]                                               | 1         | 0.95%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 1         | 0.95%   |
| Intel UHD Graphics 620                                                        | 1         | 0.95%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.95%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 0.95%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 0.95%   |
| Intel HD Graphics 615                                                         | 1         | 0.95%   |
| Intel HD Graphics 5500                                                        | 1         | 0.95%   |
| Intel HD Graphics 530                                                         | 1         | 0.95%   |
| Intel HD Graphics 500                                                         | 1         | 0.95%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 0.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 0.95%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 0.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 0.95%   |
| AMD Wrestler [Radeon HD 7310]                                                 | 1         | 0.95%   |
| AMD Wrestler [Radeon HD 6310]                                                 | 1         | 0.95%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                 | 1         | 0.95%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 1         | 0.95%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 0.95%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                  | 1         | 0.95%   |
| AMD RS780M [Mobility Radeon HD 3200]                                          | 1         | 0.95%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                       | 1         | 0.95%   |
| AMD Renoir                                                                    | 1         | 0.95%   |
| AMD Kaveri [Radeon R6 Graphics]                                               | 1         | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 71        | 78.89%  |
| 1 x AMD        | 12        | 13.33%  |
| Intel + Nvidia | 4         | 4.44%   |
| 1 x Nvidia     | 1         | 1.11%   |
| Intel + AMD    | 1         | 1.11%   |
| AMD + Nvidia   | 1         | 1.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 84        | 93.33%  |
| Proprietary | 4         | 4.44%   |
| Unknown     | 2         | 2.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 76.09%  |
| 0.01-0.5   | 13        | 14.13%  |
| 1.01-2.0   | 4         | 4.35%   |
| 3.01-4.0   | 3         | 3.26%   |
| 0.51-1.0   | 2         | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 17.53%  |
| BOE                     | 14        | 14.43%  |
| LG Display              | 12        | 12.37%  |
| AU Optronics            | 11        | 11.34%  |
| Chimei Innolux          | 8         | 8.25%   |
| Chi Mei Optoelectronics | 6         | 6.19%   |
| LG Philips              | 5         | 5.15%   |
| Lenovo                  | 4         | 4.12%   |
| InfoVision              | 4         | 4.12%   |
| Hewlett-Packard         | 3         | 3.09%   |
| HannStar                | 3         | 3.09%   |
| PANDA                   | 2         | 2.06%   |
| Vizio                   | 1         | 1.03%   |
| Sharp                   | 1         | 1.03%   |
| MStar                   | 1         | 1.03%   |
| KTC                     | 1         | 1.03%   |
| InnoLux Display         | 1         | 1.03%   |
| Goldstar                | 1         | 1.03%   |
| Dell                    | 1         | 1.03%   |
| Acer                    | 1         | 1.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 4         | 4.12%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                     | 3         | 3.09%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch            | 3         | 3.09%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 2.06%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 2.06%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch              | 2         | 2.06%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch              | 2         | 2.06%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 2.06%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch          | 2         | 2.06%   |
| Vizio E322AR VIZ0079 1360x768 700x400mm 31.7-inch                        | 1         | 1.03%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                  | 1         | 1.03%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch        | 1         | 1.03%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch      | 1         | 1.03%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch        | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC8151 1920x1080 382x214mm 17.2-inch    | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch     | 1         | 1.03%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                         | 1         | 1.03%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch            | 1         | 1.03%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 1         | 1.03%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 1         | 1.03%   |
| LG Philips LCD Monitor LPL0701 1280x800 331x207mm 15.4-inch              | 1         | 1.03%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch              | 1         | 1.03%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch            | 1         | 1.03%   |
| LG Display LCD Monitor LGD0550 1920x1080 344x194mm 15.5-inch             | 1         | 1.03%   |
| LG Display LCD Monitor LGD04B7 1366x768 344x194mm 15.5-inch              | 1         | 1.03%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 1.03%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch              | 1         | 1.03%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 1         | 1.03%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 1         | 1.03%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch              | 1         | 1.03%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 1.03%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 1         | 1.03%   |
| Lenovo LCD Monitor LEN4090 1366x768 293x164mm 13.2-inch                  | 1         | 1.03%   |
| Lenovo LCD Monitor LEN4055 1920x1200 330x210mm 15.4-inch                 | 1         | 1.03%   |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch                  | 1         | 1.03%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.03%   |
| KTC 32L22-H-CS KTC3202 1360x768 708x398mm 32.0-inch                      | 1         | 1.03%   |
| InnoLux Display LCD Monitor CMI001B 1366x768 309x174mm 14.0-inch         | 1         | 1.03%   |
| InfoVision LCD Monitor IVO057E 1366x768 309x174mm 14.0-inch              | 1         | 1.03%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch              | 1         | 1.03%   |
| Hewlett-Packard L1755 HWP264A 1280x1024 376x301mm 19.0-inch              | 1         | 1.03%   |
| Hewlett-Packard 25f HPN3547 1920x1080 553x309mm 24.9-inch                | 1         | 1.03%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 476x268mm 21.5-inch               | 1         | 1.03%   |
| HannStar HSD140PHW1 HSD0583 1366x768 309x174mm 14.0-inch                 | 1         | 1.03%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 1         | 1.03%   |
| Dell U2720Q DEL41B5 3840x2160 597x336mm 27.0-inch                        | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch         | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15AA 1366x768 344x194mm 15.5-inch          | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN1040 1366x768 222x125mm 10.0-inch          | 1         | 1.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 1         | 1.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 51        | 54.84%  |
| 1920x1080 (FHD)   | 17        | 18.28%  |
| 1280x800 (WXGA)   | 11        | 11.83%  |
| 3840x2160 (4K)    | 3         | 3.23%   |
| 1360x768          | 3         | 3.23%   |
| 1280x1024 (SXGA)  | 2         | 2.15%   |
| 1024x600          | 2         | 2.15%   |
| 2560x1440 (QHD)   | 1         | 1.08%   |
| 1920x1200 (WUXGA) | 1         | 1.08%   |
| 1600x900 (HD+)    | 1         | 1.08%   |
| 1440x900 (WXGA+)  | 1         | 1.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 38        | 39.18%  |
| 14     | 21        | 21.65%  |
| 13     | 16        | 16.49%  |
| 10     | 4         | 4.12%   |
| 21     | 3         | 3.09%   |
| 17     | 3         | 3.09%   |
| 18     | 2         | 2.06%   |
| 11     | 2         | 2.06%   |
| 54     | 1         | 1.03%   |
| 52     | 1         | 1.03%   |
| 32     | 1         | 1.03%   |
| 31     | 1         | 1.03%   |
| 27     | 1         | 1.03%   |
| 24     | 1         | 1.03%   |
| 19     | 1         | 1.03%   |
| 12     | 1         | 1.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 73        | 76.04%  |
| 201-300     | 8         | 8.33%   |
| 401-500     | 5         | 5.21%   |
| 351-400     | 4         | 4.17%   |
| 501-600     | 2         | 2.08%   |
| 1001-1500   | 2         | 2.08%   |
| 701-800     | 1         | 1.04%   |
| 601-700     | 1         | 1.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 72        | 82.76%  |
| 16/10 | 12        | 13.79%  |
| 5/4   | 2         | 2.3%    |
| 3/2   | 1         | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 39.18%  |
| 81-90          | 36        | 37.11%  |
| 41-50          | 4         | 4.12%   |
| 141-150        | 3         | 3.09%   |
| More than 1000 | 2         | 2.06%   |
| 51-60          | 2         | 2.06%   |
| 351-500        | 2         | 2.06%   |
| 201-250        | 2         | 2.06%   |
| 151-200        | 2         | 2.06%   |
| 121-130        | 2         | 2.06%   |
| 71-80          | 1         | 1.03%   |
| 61-70          | 1         | 1.03%   |
| 301-350        | 1         | 1.03%   |
| 251-300        | 1         | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 46        | 48.42%  |
| 121-160       | 22        | 23.16%  |
| 51-100        | 20        | 21.05%  |
| 1-50          | 4         | 4.21%   |
| 161-240       | 2         | 2.11%   |
| More than 240 | 1         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 79        | 85.87%  |
| 2     | 11        | 11.96%  |
| 3     | 1         | 1.09%   |
| 0     | 1         | 1.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 63        | 41.45%  |
| Qualcomm Atheros                | 32        | 21.05%  |
| Intel                           | 29        | 19.08%  |
| Broadcom                        | 12        | 7.89%   |
| Broadcom Limited                | 4         | 2.63%   |
| Marvell Technology Group        | 3         | 1.97%   |
| Samsung Electronics             | 2         | 1.32%   |
| JMicron Technology              | 2         | 1.32%   |
| Xiaomi                          | 1         | 0.66%   |
| Trendchip Technologies          | 1         | 0.66%   |
| Ralink Technology               | 1         | 0.66%   |
| Qualcomm Atheros Communications | 1         | 0.66%   |
| AMD                             | 1         | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 31        | 17.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 17        | 9.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 6.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 3.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.41%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 4         | 2.27%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 2.27%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 2.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 1.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.7%    |
| Intel Centrino Wireless-N 105                                           | 3         | 1.7%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 1.14%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 1.14%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.14%   |
| Intel Wireless 8260                                                     | 2         | 1.14%   |
| Intel Wireless 7265                                                     | 2         | 1.14%   |
| Intel Wireless 7260                                                     | 2         | 1.14%   |
| Intel Wireless 3165                                                     | 2         | 1.14%   |
| Intel WiFi Link 5100                                                    | 2         | 1.14%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.14%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.14%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.14%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express             | 2         | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.14%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.57%   |
| Trendchip Ethernet controller                                           | 1         | 0.57%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.57%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.57%   |
| Realtek Realtek Ethernet controller                                     | 1         | 0.57%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.57%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1         | 0.57%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 0.57%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                     | 1         | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 0.57%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 0.57%   |
| Intel PRO/100 VE Network Connection                                     | 1         | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.57%   |
| Intel Ethernet Connection I219-V                                        | 1         | 0.57%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 0.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.57%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.57%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.57%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 30.77%  |
| Qualcomm Atheros                | 26        | 28.57%  |
| Realtek Semiconductor           | 24        | 26.37%  |
| Broadcom                        | 10        | 10.99%  |
| Ralink Technology               | 1         | 1.1%    |
| Qualcomm Atheros Communications | 1         | 1.1%    |
| Broadcom Limited                | 1         | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 13.19%  |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 7.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 6.59%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 4         | 4.4%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 4.4%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 4.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 3.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 3.3%    |
| Intel Centrino Wireless-N 105                                           | 3         | 3.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 2.2%    |
| Intel Wireless 8265 / 8275                                              | 2         | 2.2%    |
| Intel Wireless 8260                                                     | 2         | 2.2%    |
| Intel Wireless 7265                                                     | 2         | 2.2%    |
| Intel Wireless 7260                                                     | 2         | 2.2%    |
| Intel Wireless 3165                                                     | 2         | 2.2%    |
| Intel WiFi Link 5100                                                    | 2         | 2.2%    |
| Intel Wi-Fi 6 AX201                                                     | 2         | 2.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 2.2%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 2.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.2%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 2.2%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 1.1%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 1.1%    |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.1%    |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.1%    |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.1%    |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.1%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.1%    |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.1%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.1%    |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.1%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.1%    |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 1         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 53        | 63.1%   |
| Qualcomm Atheros         | 9         | 10.71%  |
| Intel                    | 8         | 9.52%   |
| Marvell Technology Group | 3         | 3.57%   |
| Broadcom Limited         | 3         | 3.57%   |
| Samsung Electronics      | 2         | 2.38%   |
| JMicron Technology       | 2         | 2.38%   |
| Broadcom                 | 2         | 2.38%   |
| Xiaomi                   | 1         | 1.19%   |
| Trendchip Technologies   | 1         | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 36.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 20.24%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 3.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 3.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 2.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.38%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 2.38%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 2         | 2.38%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.19%   |
| Trendchip Ethernet controller                                     | 1         | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.19%   |
| Realtek Realtek Ethernet controller                               | 1         | 1.19%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.19%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.19%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.19%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.19%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 1.19%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.19%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.19%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.19%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.19%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.19%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.19%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.19%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.19%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.19%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 1.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 51.46%  |
| Ethernet | 82        | 47.95%  |
| Modem    | 1         | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 73.4%   |
| Ethernet | 25        | 26.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 76        | 84.44%  |
| 1     | 13        | 14.44%  |
| 0     | 1         | 1.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 90        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 37.21%  |
| Qualcomm Atheros Communications | 8         | 18.6%   |
| IMC Networks                    | 6         | 13.95%  |
| Realtek Semiconductor           | 5         | 11.63%  |
| Broadcom                        | 4         | 9.3%    |
| Cambridge Silicon Radio         | 3         | 6.98%   |
| ASUSTek Computer                | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 23.26%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 9.3%    |
| Realtek Bluetooth Radio                             | 3         | 6.98%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 6.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 6.98%   |
| Realtek RTL8723B Bluetooth                          | 2         | 4.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 4.65%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 4.65%   |
| Intel AX201 Bluetooth                               | 2         | 4.65%   |
| IMC Networks Bluetooth                              | 2         | 4.65%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 4.65%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.33%   |
| Intel AX200 Bluetooth                               | 1         | 2.33%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.33%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 2.33%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 2.33%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 79        | 81.44%  |
| AMD                   | 13        | 13.4%   |
| Nvidia                | 3         | 3.09%   |
| Realtek Semiconductor | 1         | 1.03%   |
| Microsoft             | 1         | 1.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 15.93%  |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 7.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 7.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 7.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 6.19%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 5.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 5.31%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 4.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.65%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.65%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 2.65%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.65%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.77%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.77%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.77%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.88%   |
| Nvidia Audio device                                                        | 1         | 0.88%   |
| Microsoft LifeChat LX-4000                                                 | 1         | 0.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.88%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 0.88%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.88%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 0.88%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1         | 0.88%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 0.88%   |
| AMD IXP SB400 AC'97 Audio Controller                                       | 1         | 0.88%   |
| AMD High Definition Audio Controller                                       | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 15        | 20.83%  |
| Samsung Electronics | 13        | 18.06%  |
| Ramaxel Technology  | 10        | 13.89%  |
| Unknown             | 9         | 12.5%   |
| Micron Technology   | 7         | 9.72%   |
| Kingston            | 5         | 6.94%   |
| Crucial             | 4         | 5.56%   |
| Unknown (ABCD)      | 2         | 2.78%   |
| Unknown (081A)      | 1         | 1.39%   |
| Qimonda             | 1         | 1.39%   |
| Memox               | 1         | 1.39%   |
| ELPIDA              | 1         | 1.39%   |
| Corsair             | 1         | 1.39%   |
| A-DATA Technology   | 1         | 1.39%   |
| Unknown             | 1         | 1.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s                   | 3         | 4%      |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s                   | 3         | 4%      |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 2.67%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 2.67%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s                     | 2         | 2.67%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s                   | 2         | 2.67%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s                   | 2         | 2.67%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s                   | 2         | 2.67%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 1.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                            | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                                 | 1         | 1.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 1         | 1.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 1         | 1.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 1.33%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2667MT/s                           | 1         | 1.33%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                             | 1         | 1.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s            | 1         | 1.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s            | 1         | 1.33%   |
| Unknown (081A) RAM HXMSH2GS03A2F1CL16 2GB SODIMM DDR3 1600MT/s            | 1         | 1.33%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                      | 1         | 1.33%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.33%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.33%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.33%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s                 | 1         | 1.33%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s                    | 1         | 1.33%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                    | 1         | 1.33%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 1.33%   |
| SK Hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 1         | 1.33%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.33%   |
| SK Hynix RAM 999999999999999999999999999999999999 1GB SODIMM DDR2 667MT/s | 1         | 1.33%   |
| SK Hynix RAM 121212121212121212121212121212121212 2GB SODIMM DDR2 667MT/s | 1         | 1.33%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                               | 1         | 1.33%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s                     | 1         | 1.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 1.33%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                     | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s               | 1         | 1.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.33%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s                    | 1         | 1.33%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s                     | 1         | 1.33%   |
| Samsung RAM M4 70T2864DZ3-CE6 1GB SODIMM DDR 667MT/s                      | 1         | 1.33%   |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s                       | 1         | 1.33%   |
| Ramaxel RAM RMT3170MK58F8F1600 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.33%   |
| Qimonda RAM Module 1024MB SODIMM DDR2 533MT/s                             | 1         | 1.33%   |
| Micron RAM Module 8GB SODIMM DDR4 2133MT/s                                | 1         | 1.33%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.33%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8192MB SODIMM DDR4 2400MT/s                   | 1         | 1.33%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8192MB SODIMM DDR4 2400MT/s                   | 1         | 1.33%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s                     | 1         | 1.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s             | 1         | 1.33%   |
| Micron RAM 16JSF25664HZ-1G1F1 2048MB SODIMM 800MT/s                       | 1         | 1.33%   |
| Memox RAM LN-SD302160011SA8R 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.33%   |
| Kingston RAM Module 4GB SODIMM DDR3 1333MT/s                              | 1         | 1.33%   |
| Kingston RAM KN2M64-ETB 8192MB SODIMM DDR3 1600MT/s                       | 1         | 1.33%   |
| Kingston RAM 99U5624-003.A00G 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.33%   |
| Kingston RAM 99U5469-070.A00LF 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.33%   |
| Kingston RAM 9905428-071.A00LF 4GB SODIMM DDR3 1333MT/s                   | 1         | 1.33%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s                  | 1         | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 22        | 40.74%  |
| DDR4   | 15        | 27.78%  |
| DDR2   | 10        | 18.52%  |
| SDRAM  | 4         | 7.41%   |
| LPDDR4 | 2         | 3.7%    |
| DDR    | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 49        | 94.23%  |
| Row Of Chips | 2         | 3.85%   |
| DIMM         | 1         | 1.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 21        | 34.43%  |
| 2048  | 21        | 34.43%  |
| 8192  | 13        | 21.31%  |
| 1024  | 4         | 6.56%   |
| 16384 | 2         | 3.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 20        | 32.26%  |
| 2400    | 7         | 11.29%  |
| 3200    | 5         | 8.06%   |
| 2667    | 5         | 8.06%   |
| 667     | 5         | 8.06%   |
| 1333    | 4         | 6.45%   |
| 1334    | 3         | 4.84%   |
| 4199    | 2         | 3.23%   |
| 2048    | 2         | 3.23%   |
| 533     | 2         | 3.23%   |
| Unknown | 2         | 3.23%   |
| 3266    | 1         | 1.61%   |
| 2133    | 1         | 1.61%   |
| 1067    | 1         | 1.61%   |
| 975     | 1         | 1.61%   |
| 800     | 1         | 1.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Hewlett-Packard     | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Samsung ML-1865  | 1         | 50%     |
| HP LaserJet 1018 | 1         | 50%     |

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
| Chicony Electronics                    | 14        | 20.9%   |
| Acer                                   | 11        | 16.42%  |
| Microdia                               | 10        | 14.93%  |
| Realtek Semiconductor                  | 8         | 11.94%  |
| IMC Networks                           | 5         | 7.46%   |
| Suyin                                  | 4         | 5.97%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.48%   |
| Syntek                                 | 2         | 2.99%   |
| Ricoh                                  | 2         | 2.99%   |
| Tobii Technology AB                    | 1         | 1.49%   |
| Sunplus Innovation Technology          | 1         | 1.49%   |
| Quanta                                 | 1         | 1.49%   |
| Luxvisions Innotech Limited            | 1         | 1.49%   |
| Lite-On Technology                     | 1         | 1.49%   |
| Lenovo                                 | 1         | 1.49%   |
| Apple                                  | 1         | 1.49%   |
| ALi                                    | 1         | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                  | 4         | 5.97%   |
| Chicony USB 2.0 Camera                                        | 4         | 5.97%   |
| Chicony Lenovo EasyCamera                                     | 3         | 4.48%   |
| Microdia USB 2.0 Camera                                       | 2         | 2.99%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 2.99%   |
| IMC Networks USB 2.0 UVC VGA WebCam                           | 2         | 2.99%   |
| Chicony Integrated Camera                                     | 2         | 2.99%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 2         | 2.99%   |
| Acer USB HD Webcam                                            | 2         | 2.99%   |
| Acer USB Camera                                               | 2         | 2.99%   |
| Acer Lenovo EasyCamera                                        | 2         | 2.99%   |
| Acer HD Webcam                                                | 2         | 2.99%   |
| Tobii AB EyeChip                                              | 1         | 1.49%   |
| Syntek USB Camera Device                                      | 1         | 1.49%   |
| Syntek Integrated Webcam                                      | 1         | 1.49%   |
| Suyin USB2.0 UVC 1.3M WebCam                                  | 1         | 1.49%   |
| Suyin HP Webcam 101                                           | 1         | 1.49%   |
| Suyin HD Video WebCam                                         | 1         | 1.49%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 1.49%   |
| Sunplus MTD Camera                                            | 1         | 1.49%   |
| Ricoh Sony Vaio Integrated Webcam                             | 1         | 1.49%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 1         | 1.49%   |
| Realtek USB Camera                                            | 1         | 1.49%   |
| Realtek MTD camera                                            | 1         | 1.49%   |
| Realtek Integrated Webcam HD                                  | 1         | 1.49%   |
| Realtek Integrated Webcam                                     | 1         | 1.49%   |
| Quanta HP Webcam                                              | 1         | 1.49%   |
| Microdia WebCam SC-13HDL12639P                                | 1         | 1.49%   |
| Microdia USB camera                                           | 1         | 1.49%   |
| Microdia Sonix USB 2.0 Camera                                 | 1         | 1.49%   |
| Microdia Laptop_Integrated_Webcam_HD                          | 1         | 1.49%   |
| Microdia Integrated_Webcam_HD                                 | 1         | 1.49%   |
| Microdia Integrated_Webcam_FHD                                | 1         | 1.49%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera           | 1         | 1.49%   |
| Lite-On TOSHIBA Web Camera - HD                               | 1         | 1.49%   |
| Lenovo CNF7237&CNF7238                                        | 1         | 1.49%   |
| IMC Networks USB2.0 VGA UVC WebCam                            | 1         | 1.49%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 1         | 1.49%   |
| IMC Networks EasyCamera                                       | 1         | 1.49%   |
| Chicony USB2.0 HD UVC WebCam                                  | 1         | 1.49%   |
| Chicony Lenovo Integrated Camera                              | 1         | 1.49%   |
| Chicony HP HD Camera                                          | 1         | 1.49%   |
| Chicony HD WebCam                                             | 1         | 1.49%   |
| Chicony 1.3M HD WebCam                                        | 1         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD       | 1         | 1.49%   |
| Apple iPhone 5/5C/5S/6/SE                                     | 1         | 1.49%   |
| ALi Gateway Webcam                                            | 1         | 1.49%   |
| Acer Integrated Camera                                        | 1         | 1.49%   |
| Acer HP TrueVision HD Webcam                                  | 1         | 1.49%   |
| Acer BisonCam, NB Pro                                         | 1         | 1.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Validity Sensors    | 4         | 57.14%  |
| AuthenTec           | 2         | 28.57%  |
| Futronic Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 2         | 28.57%  |
| AuthenTec AES2501 Fingerprint Sensor        | 2         | 28.57%  |
| Validity Sensors VFS495 Fingerprint Reader  | 1         | 14.29%  |
| Validity Sensors Fingerprint scanner        | 1         | 14.29%  |
| Futronic Fingerprint Scanner Model FS88     | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 66.67%  |
| Broadcom 5880                                  | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 72        | 79.12%  |
| 1     | 16        | 17.58%  |
| 2     | 2         | 2.2%    |
| 4     | 1         | 1.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7         | 29.17%  |
| Graphics card            | 6         | 25%     |
| Net/wireless             | 3         | 12.5%   |
| Chipcard                 | 3         | 12.5%   |
| Camera                   | 2         | 8.33%   |
| Storage                  | 1         | 4.17%   |
| Sound                    | 1         | 4.17%   |
| Communication controller | 1         | 4.17%   |

