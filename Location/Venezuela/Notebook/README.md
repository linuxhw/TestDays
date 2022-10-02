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

Total: 162

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 10        | 8.7%    |
| Debian 11                    | 10        | 8.7%    |
| Debian 10                    | 6         | 5.22%   |
| Ubuntu 18.04                 | 5         | 4.35%   |
| OpenMandriva 4.3             | 5         | 4.35%   |
| Ubuntu 22.04                 | 4         | 3.48%   |
| Kubuntu 20.04                | 4         | 3.48%   |
| KDE neon 20.04               | 4         | 3.48%   |
| Zorin 16                     | 3         | 2.61%   |
| Xubuntu 18.04                | 3         | 2.61%   |
| ROSA R9                      | 3         | 2.61%   |
| OpenMandriva 4.2             | 3         | 2.61%   |
| Linux Mint 20.3              | 3         | 2.61%   |
| Zorin 15                     | 2         | 1.74%   |
| Ubuntu Unity 16.04           | 2         | 1.74%   |
| Ubuntu 21.10                 | 2         | 1.74%   |
| Ubuntu 19.10                 | 2         | 1.74%   |
| Pop!_OS 22.04                | 2         | 1.74%   |
| Pop!_OS 21.04                | 2         | 1.74%   |
| Manjaro                      | 2         | 1.74%   |
| Linux Mint 20                | 2         | 1.74%   |
| Fedora 36                    | 2         | 1.74%   |
| Fedora 35                    | 2         | 1.74%   |
| Xubuntu 21.10                | 1         | 0.87%   |
| Xubuntu 20.04                | 1         | 0.87%   |
| Ubuntu MATE 20.04            | 1         | 0.87%   |
| Ubuntu MATE 19.10            | 1         | 0.87%   |
| Ubuntu 16.04                 | 1         | 0.87%   |
| Solus 4.1                    | 1         | 0.87%   |
| ROSA R11                     | 1         | 0.87%   |
| Q4OS 4                       | 1         | 0.87%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.87%   |
| OpenMandriva 4.50            | 1         | 0.87%   |
| MX 20                        | 1         | 0.87%   |
| Manjaro 21.2.0               | 1         | 0.87%   |
| Manjaro 21.1.0               | 1         | 0.87%   |
| Manjaro 21.0                 | 1         | 0.87%   |
| Manjaro 20.1                 | 1         | 0.87%   |
| Lubuntu 18.04                | 1         | 0.87%   |
| LMDE 4                       | 1         | 0.87%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 22        | 20%     |
| Debian       | 15        | 13.64%  |
| OpenMandriva | 9         | 8.18%   |
| Manjaro      | 6         | 5.45%   |
| Linux Mint   | 6         | 5.45%   |
| Zorin        | 5         | 4.55%   |
| Xubuntu      | 5         | 4.55%   |
| Kubuntu      | 5         | 4.55%   |
| KDE neon     | 5         | 4.55%   |
| Fedora       | 5         | 4.55%   |
| ROSA         | 4         | 3.64%   |
| Pop!_OS      | 4         | 3.64%   |
| Ubuntu Unity | 2         | 1.82%   |
| Ubuntu MATE  | 2         | 1.82%   |
| Solus        | 1         | 0.91%   |
| Q4OS         | 1         | 0.91%   |
| openSUSE     | 1         | 0.91%   |
| MX           | 1         | 0.91%   |
| Lubuntu      | 1         | 0.91%   |
| LMDE         | 1         | 0.91%   |
| Linux Lite   | 1         | 0.91%   |
| Garuda Linux | 1         | 0.91%   |
| Feren OS     | 1         | 0.91%   |
| Elementary   | 1         | 0.91%   |
| Deepin       | 1         | 0.91%   |
| ArcoLinux    | 1         | 0.91%   |
| Arch         | 1         | 0.91%   |
| Alpine       | 1         | 0.91%   |
| AlmaLinux    | 1         | 0.91%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                  | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003                  | 5         | 3.88%   |
| 5.4.0-42-generic                         | 4         | 3.1%    |
| 5.15.0-46-generic                        | 4         | 3.1%    |
| 5.4.0-73-generic                         | 3         | 2.33%   |
| 5.4.0-52-generic                         | 3         | 2.33%   |
| 5.3.0-40-generic                         | 3         | 2.33%   |
| 5.13.0-39-generic                        | 3         | 2.33%   |
| 5.10.14-desktop-1omv4002                 | 3         | 2.33%   |
| 5.10.0-13-amd64                          | 3         | 2.33%   |
| 4.9.20-nrj-desktop-1rosa-x86_64          | 3         | 2.33%   |
| 4.19.0-17-amd64                          | 3         | 2.33%   |
| 5.4.0-89-generic                         | 2         | 1.55%   |
| 5.4.0-77-generic                         | 2         | 1.55%   |
| 5.4.0-48-generic                         | 2         | 1.55%   |
| 5.4.0-107-generic                        | 2         | 1.55%   |
| 5.15.0-48-generic                        | 2         | 1.55%   |
| 5.15.0-43-generic                        | 2         | 1.55%   |
| 5.11.0-37-generic                        | 2         | 1.55%   |
| 5.10.0-15-amd64                          | 2         | 1.55%   |
| 5.10.0-11-amd64                          | 2         | 1.55%   |
| 5.0.0-37-generic                         | 2         | 1.55%   |
| 5.9.0-5-amd64                            | 1         | 0.78%   |
| 5.8.6-1-MANJARO                          | 1         | 0.78%   |
| 5.8.0-63-generic                         | 1         | 0.78%   |
| 5.8.0-53-generic                         | 1         | 0.78%   |
| 5.8.0-45-generic                         | 1         | 0.78%   |
| 5.8.0-44-generic                         | 1         | 0.78%   |
| 5.8.0-41-generic                         | 1         | 0.78%   |
| 5.6.6-1-default                          | 1         | 0.78%   |
| 5.6.18-155.current                       | 1         | 0.78%   |
| 5.5.4-linux-xanmod-1-rosa-x86_64-xanmod3 | 1         | 0.78%   |
| 5.4.83-0-lts                             | 1         | 0.78%   |
| 5.4.105-1-MANJARO                        | 1         | 0.78%   |
| 5.4.0-91-generic                         | 1         | 0.78%   |
| 5.4.0-86-generic                         | 1         | 0.78%   |
| 5.4.0-70-generic                         | 1         | 0.78%   |
| 5.4.0-31-generic                         | 1         | 0.78%   |
| 5.3.0-42-generic                         | 1         | 0.78%   |
| 5.3.0-29-generic                         | 1         | 0.78%   |
| 5.18.0-0.bpo.1-amd64                     | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 20        | 16.95%  |
| 5.13.0  | 10        | 8.47%   |
| 5.15.0  | 9         | 7.63%   |
| 5.10.0  | 9         | 7.63%   |
| 4.19.0  | 8         | 6.78%   |
| 5.11.0  | 6         | 5.08%   |
| 5.3.0   | 5         | 4.24%   |
| 5.16.7  | 5         | 4.24%   |
| 5.8.0   | 4         | 3.39%   |
| 4.15.0  | 4         | 3.39%   |
| 5.10.14 | 3         | 2.54%   |
| 4.9.20  | 3         | 2.54%   |
| 5.14.10 | 2         | 1.69%   |
| 5.0.0   | 2         | 1.69%   |
| 5.9.0   | 1         | 0.85%   |
| 5.8.6   | 1         | 0.85%   |
| 5.6.6   | 1         | 0.85%   |
| 5.6.18  | 1         | 0.85%   |
| 5.5.4   | 1         | 0.85%   |
| 5.4.83  | 1         | 0.85%   |
| 5.4.105 | 1         | 0.85%   |
| 5.18.0  | 1         | 0.85%   |
| 5.17.2  | 1         | 0.85%   |
| 5.17.15 | 1         | 0.85%   |
| 5.17.12 | 1         | 0.85%   |
| 5.17.11 | 1         | 0.85%   |
| 5.15.8  | 1         | 0.85%   |
| 5.15.65 | 1         | 0.85%   |
| 5.15.6  | 1         | 0.85%   |
| 5.15.46 | 1         | 0.85%   |
| 5.15.28 | 1         | 0.85%   |
| 5.15.2  | 1         | 0.85%   |
| 5.15.19 | 1         | 0.85%   |
| 5.15.13 | 1         | 0.85%   |
| 5.15.10 | 1         | 0.85%   |
| 5.13.13 | 1         | 0.85%   |
| 5.12.4  | 1         | 0.85%   |
| 5.12.19 | 1         | 0.85%   |
| 5.10.5  | 1         | 0.85%   |
| 5.10.11 | 1         | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 22        | 18.97%  |
| 5.15    | 16        | 13.79%  |
| 5.10    | 15        | 12.93%  |
| 5.13    | 11        | 9.48%   |
| 4.19    | 8         | 6.9%    |
| 5.11    | 6         | 5.17%   |
| 5.8     | 5         | 4.31%   |
| 5.3     | 5         | 4.31%   |
| 5.16    | 5         | 4.31%   |
| 5.17    | 4         | 3.45%   |
| 4.15    | 4         | 3.45%   |
| 4.9     | 3         | 2.59%   |
| 5.6     | 2         | 1.72%   |
| 5.14    | 2         | 1.72%   |
| 5.12    | 2         | 1.72%   |
| 5.0     | 2         | 1.72%   |
| 5.9     | 1         | 0.86%   |
| 5.5     | 1         | 0.86%   |
| 5.18    | 1         | 0.86%   |
| 4.18    | 1         | 0.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 94        | 90.38%  |
| i686   | 10        | 9.62%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 37        | 33.04%  |
| KDE5          | 23        | 20.54%  |
| XFCE          | 20        | 17.86%  |
| Unknown       | 7         | 6.25%   |
| KDE           | 6         | 5.36%   |
| MATE          | 4         | 3.57%   |
| X-Cinnamon    | 3         | 2.68%   |
| KDE4          | 3         | 2.68%   |
| Unity         | 2         | 1.79%   |
| Cinnamon      | 2         | 1.79%   |
| Pantheon      | 1         | 0.89%   |
| LXQt          | 1         | 0.89%   |
| GNOME Classic | 1         | 0.89%   |
| Deepin        | 1         | 0.89%   |
| Budgie        | 1         | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 93        | 88.57%  |
| Wayland | 11        | 10.48%  |
| Tty     | 1         | 0.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 45        | 40.54%  |
| SDDM    | 18        | 16.22%  |
| GDM     | 18        | 16.22%  |
| LightDM | 14        | 12.61%  |
| GDM3    | 10        | 9.01%   |
| TDM     | 3         | 2.7%    |
| KDM     | 3         | 2.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_VE   | 61        | 55.96%  |
| en_US   | 32        | 29.36%  |
| es_ES   | 8         | 7.34%   |
| Unknown | 7         | 6.42%   |
| en_CA   | 1         | 0.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 71        | 66.36%  |
| EFI  | 36        | 33.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 85        | 80.95%  |
| Overlay | 8         | 7.62%   |
| Btrfs   | 6         | 5.71%   |
| Xfs     | 3         | 2.86%   |
| Unknown | 3         | 2.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 55        | 50.46%  |
| GPT     | 28        | 25.69%  |
| MBR     | 26        | 23.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 84.26%  |
| Yes       | 17        | 15.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 67        | 63.81%  |
| Yes       | 38        | 36.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 19        | 18.27%  |
| VIT                 | 18        | 17.31%  |
| Lenovo              | 18        | 17.31%  |
| Hewlett-Packard     | 14        | 13.46%  |
| ASUSTek Computer    | 7         | 6.73%   |
| Intel               | 5         | 4.81%   |
| Unknown             | 5         | 4.81%   |
| Acer                | 4         | 3.85%   |
| Toshiba             | 2         | 1.92%   |
| UNIQCELL            | 1         | 0.96%   |
| Sony                | 1         | 0.96%   |
| Samsung Electronics | 1         | 0.96%   |
| Pegatron            | 1         | 0.96%   |
| MSI                 | 1         | 0.96%   |
| GPU Company         | 1         | 0.96%   |
| Google              | 1         | 0.96%   |
| Gateway             | 1         | 0.96%   |
| Exo                 | 1         | 0.96%   |
| Clevo               | 1         | 0.96%   |
| AVITA               | 1         | 0.96%   |
| Alienware           | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| VIT P2400                           | 5         | 4.81%   |
| Intel powered classmate PC          | 5         | 4.81%   |
| Unknown                             | 5         | 4.81%   |
| VIT P2402                           | 4         | 3.85%   |
| VIT P3400                           | 3         | 2.88%   |
| VIT M2420                           | 3         | 2.88%   |
| VIT M2421                           | 2         | 1.92%   |
| Lenovo IdeaPad S100c 20194          | 2         | 1.92%   |
| Lenovo 3000 N200 0769ARS            | 2         | 1.92%   |
| Dell Inspiron 1545                  | 2         | 1.92%   |
| VIT P1400                           | 1         | 0.96%   |
| UNIQCELL Q15.6                      | 1         | 0.96%   |
| Toshiba Satellite E55t-A            | 1         | 0.96%   |
| Toshiba ENCORE 2 WT8-B              | 1         | 0.96%   |
| Sony VGN-FW510F                     | 1         | 0.96%   |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 0.96%   |
| Pegatron T14AF                      | 1         | 0.96%   |
| MSI MS-1454                         | 1         | 0.96%   |
| Lenovo Z50-75 80EC                  | 1         | 0.96%   |
| Lenovo ThinkPad X201 3680AE2        | 1         | 0.96%   |
| Lenovo ThinkPad SL400 2743A48       | 1         | 0.96%   |
| Lenovo ThinkPad Edge 01962AS        | 1         | 0.96%   |
| Lenovo ThinkPad E560 20EV002FUS     | 1         | 0.96%   |
| Lenovo IdeaPad S110 20126           | 1         | 0.96%   |
| Lenovo IdeaPad 5 14ALC05 82LM       | 1         | 0.96%   |
| Lenovo IdeaPad 330-15ARR 81D2       | 1         | 0.96%   |
| Lenovo IdeaPad 3 15IIL05 81WE       | 1         | 0.96%   |
| Lenovo IdeaPad 1 14IGL05 81VU       | 1         | 0.96%   |
| Lenovo G570 4334                    | 1         | 0.96%   |
| Lenovo G480 20150                   | 1         | 0.96%   |
| Lenovo G460 20041                   | 1         | 0.96%   |
| Lenovo B40-70 20392                 | 1         | 0.96%   |
| HP ProBook 440 G1                   | 1         | 0.96%   |
| HP Presario V2000 (EW997LA#ABM)     | 1         | 0.96%   |
| HP Presario C700                    | 1         | 0.96%   |
| HP Pavilion dv6700                  | 1         | 0.96%   |
| HP Pavilion dv6500                  | 1         | 0.96%   |
| HP Pavilion dv6000 (RV216UA#ABA)    | 1         | 0.96%   |
| HP Pavilion dv6                     | 1         | 0.96%   |
| HP Pavilion dv5                     | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 11        | 10.58%  |
| Lenovo IdeaPad         | 7         | 6.73%   |
| HP Pavilion            | 6         | 5.77%   |
| VIT P2400              | 5         | 4.81%   |
| Intel powered          | 5         | 4.81%   |
| Unknown                | 5         | 4.81%   |
| VIT P2402              | 4         | 3.85%   |
| Lenovo ThinkPad        | 4         | 3.85%   |
| Dell Latitude          | 4         | 3.85%   |
| VIT P3400              | 3         | 2.88%   |
| VIT M2420              | 3         | 2.88%   |
| Acer Aspire            | 3         | 2.88%   |
| VIT M2421              | 2         | 1.92%   |
| Lenovo 3000            | 2         | 1.92%   |
| HP Presario            | 2         | 1.92%   |
| HP EliteBook           | 2         | 1.92%   |
| Dell Vostro            | 2         | 1.92%   |
| ASUS VivoBook          | 2         | 1.92%   |
| ASUS ASUS              | 2         | 1.92%   |
| VIT P1400              | 1         | 0.96%   |
| UNIQCELL Q15.6         | 1         | 0.96%   |
| Toshiba Satellite      | 1         | 0.96%   |
| Toshiba ENCORE         | 1         | 0.96%   |
| Sony VGN-FW510F        | 1         | 0.96%   |
| Samsung 355V4C         | 1         | 0.96%   |
| Pegatron T14AF         | 1         | 0.96%   |
| MSI MS-1454            | 1         | 0.96%   |
| Lenovo Z50-75          | 1         | 0.96%   |
| Lenovo G570            | 1         | 0.96%   |
| Lenovo G480            | 1         | 0.96%   |
| Lenovo G460            | 1         | 0.96%   |
| Lenovo B40-70          | 1         | 0.96%   |
| HP ProBook             | 1         | 0.96%   |
| HP Laptop              | 1         | 0.96%   |
| HP Compaq              | 1         | 0.96%   |
| HP 2000                | 1         | 0.96%   |
| GPU Company GWTN156-11 | 1         | 0.96%   |
| Google Cyan            | 1         | 0.96%   |
| Gateway NV57H          | 1         | 0.96%   |
| Exo AIO                | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 14        | 13.46%  |
| 2011    | 13        | 12.5%   |
| 2012    | 11        | 10.58%  |
| 2010    | 8         | 7.69%   |
| 2007    | 8         | 7.69%   |
| 2020    | 7         | 6.73%   |
| 2018    | 7         | 6.73%   |
| 2014    | 7         | 6.73%   |
| 2008    | 6         | 5.77%   |
| 2021    | 5         | 4.81%   |
| 2017    | 4         | 3.85%   |
| 2019    | 3         | 2.88%   |
| 2015    | 3         | 2.88%   |
| 2009    | 3         | 2.88%   |
| 2022    | 2         | 1.92%   |
| 2016    | 1         | 0.96%   |
| 2006    | 1         | 0.96%   |
| Unknown | 1         | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 104       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 100       | 96.15%  |
| Enabled  | 4         | 3.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 103       | 99.04%  |
| Yes  | 1         | 0.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 28        | 26.67%  |
| 4.01-8.0   | 23        | 21.9%   |
| 1.01-2.0   | 23        | 21.9%   |
| 8.01-16.0  | 15        | 14.29%  |
| 16.01-24.0 | 8         | 7.62%   |
| 2.01-3.0   | 4         | 3.81%   |
| 32.01-64.0 | 2         | 1.9%    |
| 24.01-32.0 | 1         | 0.95%   |
| 0.51-1.0   | 1         | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 46        | 40.35%  |
| 2.01-3.0   | 26        | 22.81%  |
| 0.51-1.0   | 17        | 14.91%  |
| 4.01-8.0   | 12        | 10.53%  |
| 3.01-4.0   | 10        | 8.77%   |
| 8.01-16.0  | 2         | 1.75%   |
| 16.01-24.0 | 1         | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 72        | 67.29%  |
| 2      | 31        | 28.97%  |
| 3      | 4         | 3.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 54.81%  |
| No        | 47        | 45.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 88.57%  |
| No        | 12        | 11.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 97.12%  |
| No        | 3         | 2.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 52.38%  |
| No        | 50        | 47.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Venezuela | 104       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 47        | 41.59%  |
| Maracaibo                  | 13        | 11.5%   |
| Mérida                    | 6         | 5.31%   |
| Maracay                    | 6         | 5.31%   |
| Barquisimeto               | 4         | 3.54%   |
| Barcelona                  | 4         | 3.54%   |
| Valencia                   | 3         | 2.65%   |
| Maturín                   | 2         | 1.77%   |
| Lecherias                  | 2         | 1.77%   |
| Anaco                      | 2         | 1.77%   |
| Tucape                     | 1         | 0.88%   |
| San Juan Bautista          | 1         | 0.88%   |
| San Diego                  | 1         | 0.88%   |
| San Cristóbal             | 1         | 0.88%   |
| San Carlos del Zulia       | 1         | 0.88%   |
| Puerto Ordaz and San Felix | 1         | 0.88%   |
| Puerto Cumarebo            | 1         | 0.88%   |
| Puerto Cruz                | 1         | 0.88%   |
| Porlamar                   | 1         | 0.88%   |
| Parroquia El Recreo        | 1         | 0.88%   |
| Mariara                    | 1         | 0.88%   |
| Los Palos Grandes          | 1         | 0.88%   |
| Las Vegas                  | 1         | 0.88%   |
| Guatire                    | 1         | 0.88%   |
| Guarenas                   | 1         | 0.88%   |
| Guanare                    | 1         | 0.88%   |
| El Hatillo Municipality    | 1         | 0.88%   |
| Ejido                      | 1         | 0.88%   |
| Ciudad Guayana             | 1         | 0.88%   |
| Ciudad Bolívar            | 1         | 0.88%   |
| Charallave                 | 1         | 0.88%   |
| Cagua                      | 1         | 0.88%   |
| Barinas                    | 1         | 0.88%   |
| Acarigua                   | 1         | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 28     | 21.14%  |
| WDC                 | 23        | 31     | 18.7%   |
| Toshiba             | 12        | 12     | 9.76%   |
| Samsung Electronics | 7         | 7      | 5.69%   |
| Unknown             | 6         | 10     | 4.88%   |
| Hitachi             | 6         | 6      | 4.88%   |
| Crucial             | 5         | 7      | 4.07%   |
| SanDisk             | 4         | 5      | 3.25%   |
| LITEONIT            | 4         | 7      | 3.25%   |
| Intel               | 4         | 7      | 3.25%   |
| Kingston            | 3         | 5      | 2.44%   |
| HGST                | 3         | 3      | 2.44%   |
| SPCC                | 2         | 3      | 1.63%   |
| SK hynix            | 2         | 2      | 1.63%   |
| PNY                 | 2         | 2      | 1.63%   |
| Fujitsu             | 2         | 2      | 1.63%   |
| Vaseky              | 1         | 1      | 0.81%   |
| Silicon Motion      | 1         | 1      | 0.81%   |
| PUSKILL             | 1         | 1      | 0.81%   |
| Phison              | 1         | 1      | 0.81%   |
| Micron Technology   | 1         | 3      | 0.81%   |
| Lexar               | 1         | 1      | 0.81%   |
| KingFast            | 1         | 2      | 0.81%   |
| Intenso             | 1         | 1      | 0.81%   |
| Dell                | 1         | 2      | 0.81%   |
| BIWIN               | 1         | 2      | 0.81%   |
| Apacer              | 1         | 1      | 0.81%   |
| addlink             | 1         | 1      | 0.81%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB      | 4         | 3.15%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 3         | 2.36%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 2.36%   |
| Seagate ST250LM004 HN-M250MBB 250GB  | 3         | 2.36%   |
| LITEONIT LMS-32L6M 32GB SSD          | 3         | 2.36%   |
| WDC WD5000LPVT-08G33T1 500GB         | 2         | 1.57%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 1.57%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.57%   |
| Toshiba MQ01ABF032 320GB             | 2         | 1.57%   |
| Toshiba MQ01ABD050 500GB             | 2         | 1.57%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 2         | 1.57%   |
| Seagate ST320LM000 HM321HI 320GB     | 2         | 1.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.57%   |
| SanDisk NVMe SSD Drive 1TB           | 2         | 1.57%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.57%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 1.57%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.79%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.79%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.79%   |
| WDC WD3200LPVX-22V0TT0 320GB         | 1         | 0.79%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 0.79%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.79%   |
| WDC WD3200BEVT-00A0RT0 320GB         | 1         | 0.79%   |
| WDC WD3200BEKT-60F3T1 320GB          | 1         | 0.79%   |
| WDC WD1600BEVT-88ZCT0 160GB          | 1         | 0.79%   |
| WDC WD1600BEVS-22RST0 160GB          | 1         | 0.79%   |
| WDC WD1200BEVS-60UST0 120GB          | 1         | 0.79%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.79%   |
| WDC PC SN520 SDAPNUW-256G-1014 256GB | 1         | 0.79%   |
| Vaseky V800/128G 128GB               | 1         | 0.79%   |
| Unknown USDU1  32GB                  | 1         | 0.79%   |
| Unknown SD/MMC/MS PRO 2GB            | 1         | 0.79%   |
| Unknown SC64G  64GB                  | 1         | 0.79%   |
| Unknown MMC128  128GB                | 1         | 0.79%   |
| Unknown MMC Card  64GB               | 1         | 0.79%   |
| Unknown MMC Card  16GB               | 1         | 0.79%   |
| Unknown External 120GB               | 1         | 0.79%   |
| Unknown DA4064  64GB                 | 1         | 0.79%   |
| Unknown 032GE4  32GB                 | 1         | 0.79%   |
| Toshiba THNSNH256GBST SSD            | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 26     | 33.8%   |
| WDC                 | 21        | 28     | 29.58%  |
| Toshiba             | 11        | 11     | 15.49%  |
| Hitachi             | 6         | 6      | 8.45%   |
| HGST                | 3         | 3      | 4.23%   |
| Unknown             | 2         | 2      | 2.82%   |
| Samsung Electronics | 2         | 2      | 2.82%   |
| Fujitsu             | 2         | 2      | 2.82%   |

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
| HDD     | 69        | 80     | 57.98%  |
| SSD     | 29        | 44     | 24.37%  |
| NVMe    | 14        | 20     | 11.76%  |
| MMC     | 5         | 8      | 4.2%    |
| Unknown | 2         | 2      | 1.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 89        | 122    | 79.46%  |
| NVMe | 14        | 20     | 12.5%   |
| MMC  | 5         | 8      | 4.46%   |
| SAS  | 4         | 4      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 98     | 80.21%  |
| 0.51-1.0   | 18        | 25     | 18.75%  |
| 1.01-2.0   | 1         | 1      | 1.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 31        | 27.93%  |
| 101-250    | 28        | 25.23%  |
| 501-1000   | 20        | 18.02%  |
| 21-50      | 10        | 9.01%   |
| 1-20       | 8         | 7.21%   |
| 51-100     | 8         | 7.21%   |
| 1001-2000  | 4         | 3.6%    |
| 2001-3000  | 1         | 0.9%    |
| Unknown    | 1         | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 40        | 34.48%  |
| 21-50    | 26        | 22.41%  |
| 101-250  | 18        | 15.52%  |
| 51-100   | 14        | 12.07%  |
| 251-500  | 10        | 8.62%   |
| 501-1000 | 7         | 6.03%   |
| Unknown  | 1         | 0.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 1      | 5.26%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 5.26%   |
| WDC WD1200BEVS-60UST0 120GB          | 1         | 1      | 5.26%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2      | 5.26%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 5.26%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 5.26%   |
| Seagate ST9320325AS 320GB            | 1         | 1      | 5.26%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 5.26%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 5.26%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 5.26%   |
| Samsung Electronics HN-M320MBB 320GB | 1         | 1      | 5.26%   |
| Samsung Electronics HM250HI 250GB    | 1         | 1      | 5.26%   |
| Intel SSDPEKKW256G7 256GB            | 1         | 1      | 5.26%   |
| Hitachi HTS725050A9A364 500GB        | 1         | 1      | 5.26%   |
| Hitachi HTS543232L9A300 320GB        | 1         | 1      | 5.26%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1      | 5.26%   |
| Hitachi HTS542525K9SA00 250GB        | 1         | 1      | 5.26%   |
| HGST HTS541010A7E630 1TB             | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 26.32%  |
| WDC                 | 4         | 5      | 21.05%  |
| Hitachi             | 4         | 4      | 21.05%  |
| Toshiba             | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Intel               | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 27.78%  |
| WDC                 | 4         | 5      | 22.22%  |
| Hitachi             | 4         | 4      | 22.22%  |
| Toshiba             | 2         | 2      | 11.11%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| HGST                | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 19     | 94.74%  |
| NVMe | 1         | 1      | 5.26%   |

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
| Detected | 59        | 88     | 51.75%  |
| Works    | 36        | 46     | 31.58%  |
| Malfunc  | 19        | 20     | 16.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 86        | 78.18%  |
| AMD                         | 13        | 11.82%  |
| SanDisk                     | 3         | 2.73%   |
| SK hynix                    | 2         | 1.82%   |
| Samsung Electronics         | 2         | 1.82%   |
| Phison Electronics          | 2         | 1.82%   |
| Silicon Motion              | 1         | 0.91%   |
| Kingston Technology Company | 1         | 0.91%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 17        | 13.82%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 8.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 8.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 5.69%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 6         | 4.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 4.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 4.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 4.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 4.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 3.25%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.44%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.63%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.63%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.63%   |
| SK hynix Gold P31 SSD                                                          | 1         | 0.81%   |
| SK hynix BC511                                                                 | 1         | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.81%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.81%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.81%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.81%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.81%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.81%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.81%   |
| Intel SSD 600P Series                                                          | 1         | 0.81%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.81%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.81%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 0.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 0.81%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 0.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 0.81%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 80        | 67.8%   |
| NVMe | 14        | 11.86%  |
| IDE  | 13        | 11.02%  |
| RAID | 11        | 9.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 90        | 86.54%  |
| AMD    | 14        | 13.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz             | 4         | 3.85%   |
| Intel Atom CPU N455 @ 1.66GHz               | 4         | 3.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 3         | 2.88%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 3         | 2.88%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz        | 3         | 2.88%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 2         | 1.92%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 1.92%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 1.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.92%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.92%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 1.92%   |
| Intel Core i3-4000M CPU @ 2.40GHz           | 2         | 1.92%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.92%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 1.92%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.92%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 2         | 1.92%   |
| Intel Atom CPU N570 @ 1.66GHz               | 2         | 1.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.92%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.96%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 0.96%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.96%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1         | 0.96%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 0.96%   |
| Intel Genuine CPU T2080 @ 1.73GHz           | 1         | 0.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.96%   |
| Intel Core i7-7820HK CPU @ 2.90GHz          | 1         | 0.96%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.96%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.96%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 0.96%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.96%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 0.96%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.96%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 0.96%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz            | 1         | 0.96%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 0.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 0.96%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i3                  | 20        | 19.23%  |
| Intel Core i5                  | 19        | 18.27%  |
| Intel Core 2 Duo               | 11        | 10.58%  |
| Intel Core i7                  | 10        | 9.62%   |
| Intel Celeron                  | 10        | 9.62%   |
| Intel Atom                     | 8         | 7.69%   |
| AMD Ryzen 5                    | 5         | 4.81%   |
| Other                          | 4         | 3.85%   |
| Intel Pentium Dual-Core        | 2         | 1.92%   |
| Intel Pentium                  | 2         | 1.92%   |
| Intel Genuine                  | 2         | 1.92%   |
| AMD A10                        | 2         | 1.92%   |
| Intel Pentium Silver           | 1         | 0.96%   |
| Intel Pentium Dual             | 1         | 0.96%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.96%   |
| AMD Ryzen 7                    | 1         | 0.96%   |
| AMD Ryzen 3                    | 1         | 0.96%   |
| AMD Mobile Sempron             | 1         | 0.96%   |
| AMD E1                         | 1         | 0.96%   |
| AMD E                          | 1         | 0.96%   |
| AMD A6                         | 1         | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 76        | 73.08%  |
| 4       | 15        | 14.42%  |
| 1       | 5         | 4.81%   |
| 6       | 4         | 3.85%   |
| 8       | 2         | 1.92%   |
| Unknown | 2         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 104       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 67        | 64.42%  |
| 1       | 35        | 33.65%  |
| Unknown | 2         | 1.92%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 99        | 95.19%  |
| 64-bit         | 3         | 2.88%   |
| 32-bit         | 2         | 1.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 17.43%  |
| 0x306a9    | 13        | 11.93%  |
| 0x206a7    | 12        | 11.01%  |
| 0x1067a    | 9         | 8.26%   |
| 0x806e9    | 5         | 4.59%   |
| 0x6fd      | 5         | 4.59%   |
| 0x106ca    | 5         | 4.59%   |
| 0x806c1    | 3         | 2.75%   |
| 0x40651    | 3         | 2.75%   |
| 0x20655    | 3         | 2.75%   |
| 0x406e3    | 2         | 1.83%   |
| 0x306d4    | 2         | 1.83%   |
| 0x306c3    | 2         | 1.83%   |
| 0x30678    | 2         | 1.83%   |
| 0x08608103 | 2         | 1.83%   |
| 0x05000119 | 2         | 1.83%   |
| 0x906e9    | 1         | 0.92%   |
| 0x806ea    | 1         | 0.92%   |
| 0x806d1    | 1         | 0.92%   |
| 0x706e5    | 1         | 0.92%   |
| 0x706a8    | 1         | 0.92%   |
| 0x6ec      | 1         | 0.92%   |
| 0x506e3    | 1         | 0.92%   |
| 0x406c4    | 1         | 0.92%   |
| 0x30673    | 1         | 0.92%   |
| 0x30661    | 1         | 0.92%   |
| 0x20652    | 1         | 0.92%   |
| 0x08600103 | 1         | 0.92%   |
| 0x08600102 | 1         | 0.92%   |
| 0x08108102 | 1         | 0.92%   |
| 0x0810100b | 1         | 0.92%   |
| 0x08101007 | 1         | 0.92%   |
| 0x06006704 | 1         | 0.92%   |
| 0x06006118 | 1         | 0.92%   |
| 0x06003106 | 1         | 0.92%   |
| 0x02000057 | 1         | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 16        | 15.38%  |
| IvyBridge       | 14        | 13.46%  |
| KabyLake        | 9         | 8.65%   |
| Penryn          | 8         | 7.69%   |
| Core            | 7         | 6.73%   |
| Bonnell         | 7         | 6.73%   |
| Westmere        | 6         | 5.77%   |
| Haswell         | 5         | 4.81%   |
| Silvermont      | 4         | 3.85%   |
| TigerLake       | 3         | 2.88%   |
| Skylake         | 3         | 2.88%   |
| Zen 2           | 2         | 1.92%   |
| Zen             | 2         | 1.92%   |
| Icelake         | 2         | 1.92%   |
| Goldmont plus   | 2         | 1.92%   |
| Excavator       | 2         | 1.92%   |
| Broadwell       | 2         | 1.92%   |
| Bobcat          | 2         | 1.92%   |
| Unknown         | 2         | 1.92%   |
| Zen+            | 1         | 0.96%   |
| Steamroller     | 1         | 0.96%   |
| P6              | 1         | 0.96%   |
| K8 Hammer       | 1         | 0.96%   |
| K8 & K10 hybrid | 1         | 0.96%   |
| Goldmont        | 1         | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 88        | 78.57%  |
| AMD    | 16        | 14.29%  |
| Nvidia | 8         | 7.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 12.5%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 11.67%  |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 5.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 5.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 5.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 5%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 5%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.5%    |
| Intel HD Graphics 620                                                                    | 3         | 2.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.67%   |
| Intel HD Graphics 630                                                                    | 2         | 1.67%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.67%   |
| AMD Renoir                                                                               | 2         | 1.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.67%   |
| AMD Lucienne                                                                             | 2         | 1.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.83%   |
| Nvidia TU117M                                                                            | 1         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.83%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.83%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 0.83%   |
| Nvidia GF104GLM [Quadro 3000M]                                                           | 1         | 0.83%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.83%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.83%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.83%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.83%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.83%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.83%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 1         | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.83%   |
| Intel HD Graphics 615                                                                    | 1         | 0.83%   |
| Intel HD Graphics 530                                                                    | 1         | 0.83%   |
| Intel HD Graphics 500                                                                    | 1         | 0.83%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.83%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 81        | 77.88%  |
| 1 x AMD        | 14        | 13.46%  |
| Intel + Nvidia | 5         | 4.81%   |
| 1 x Nvidia     | 2         | 1.92%   |
| Intel + AMD    | 1         | 0.96%   |
| AMD + Nvidia   | 1         | 0.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 96        | 92.31%  |
| Proprietary | 6         | 5.77%   |
| Unknown     | 2         | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 77.36%  |
| 0.01-0.5   | 14        | 13.21%  |
| 1.01-2.0   | 5         | 4.72%   |
| 3.01-4.0   | 3         | 2.83%   |
| 0.51-1.0   | 2         | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 14.78%  |
| BOE                     | 17        | 14.78%  |
| LG Display              | 15        | 13.04%  |
| AU Optronics            | 14        | 12.17%  |
| Chimei Innolux          | 11        | 9.57%   |
| Chi Mei Optoelectronics | 6         | 5.22%   |
| LG Philips              | 5         | 4.35%   |
| Lenovo                  | 5         | 4.35%   |
| InfoVision              | 4         | 3.48%   |
| Hewlett-Packard         | 3         | 2.61%   |
| HannStar                | 3         | 2.61%   |
| Goldstar                | 3         | 2.61%   |
| PANDA                   | 2         | 1.74%   |
| Dell                    | 2         | 1.74%   |
| Vizio                   | 1         | 0.87%   |
| ViewSonic               | 1         | 0.87%   |
| Sharp                   | 1         | 0.87%   |
| MStar                   | 1         | 0.87%   |
| KTC                     | 1         | 0.87%   |
| InnoLux Display         | 1         | 0.87%   |
| ASUSTek Computer        | 1         | 0.87%   |
| Acer                    | 1         | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 4         | 3.48%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch       | 4         | 3.48%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                  | 3         | 2.61%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch         | 3         | 2.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 2         | 1.74%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.74%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 2         | 1.74%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch           | 2         | 1.74%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.74%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                  | 2         | 1.74%   |
| Vizio E322AR VIZ0079 1360x768 700x400mm 31.7-inch                     | 1         | 0.87%   |
| ViewSonic VA2252 SERIES VSC7731 1920x1080 476x268mm 21.5-inch         | 1         | 0.87%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.87%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch     | 1         | 0.87%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.87%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC8151 1920x1080 382x214mm 17.2-inch | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch  | 1         | 0.87%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.87%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch         | 1         | 0.87%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch         | 1         | 0.87%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 0.87%   |
| LG Philips LCD Monitor LPL0701 1280x800 331x207mm 15.4-inch           | 1         | 0.87%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.87%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch         | 1         | 0.87%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD0550 1920x1080 344x194mm 15.5-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD04B7 1366x768 344x194mm 15.5-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD0383 1600x900 380x210mm 17.1-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 1         | 0.87%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 59        | 55.14%  |
| 1920x1080 (FHD)   | 22        | 20.56%  |
| 1280x800 (WXGA)   | 11        | 10.28%  |
| 3840x2160 (4K)    | 3         | 2.8%    |
| 1360x768          | 3         | 2.8%    |
| 1600x900 (HD+)    | 2         | 1.87%   |
| 1280x1024 (SXGA)  | 2         | 1.87%   |
| 1024x600          | 2         | 1.87%   |
| 2560x1440 (QHD)   | 1         | 0.93%   |
| 1920x1200 (WUXGA) | 1         | 0.93%   |
| 1440x900 (WXGA+)  | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 41        | 35.96%  |
| 14     | 23        | 20.18%  |
| 13     | 20        | 17.54%  |
| 21     | 5         | 4.39%   |
| 17     | 5         | 4.39%   |
| 10     | 4         | 3.51%   |
| 18     | 3         | 2.63%   |
| 11     | 3         | 2.63%   |
| 27     | 2         | 1.75%   |
| 54     | 1         | 0.88%   |
| 52     | 1         | 0.88%   |
| 32     | 1         | 0.88%   |
| 31     | 1         | 0.88%   |
| 24     | 1         | 0.88%   |
| 23     | 1         | 0.88%   |
| 19     | 1         | 0.88%   |
| 12     | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 82        | 72.57%  |
| 201-300     | 9         | 7.96%   |
| 401-500     | 8         | 7.08%   |
| 351-400     | 6         | 5.31%   |
| 501-600     | 4         | 3.54%   |
| 1001-1500   | 2         | 1.77%   |
| 701-800     | 1         | 0.88%   |
| 601-700     | 1         | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 85        | 85%     |
| 16/10 | 12        | 12%     |
| 5/4   | 2         | 2%      |
| 3/2   | 1         | 1%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 42        | 36.84%  |
| 101-110        | 41        | 35.96%  |
| 201-250        | 5         | 4.39%   |
| 41-50          | 4         | 3.51%   |
| 141-150        | 4         | 3.51%   |
| 121-130        | 4         | 3.51%   |
| 51-60          | 3         | 2.63%   |
| More than 1000 | 2         | 1.75%   |
| 351-500        | 2         | 1.75%   |
| 301-350        | 2         | 1.75%   |
| 151-200        | 2         | 1.75%   |
| 71-80          | 1         | 0.88%   |
| 61-70          | 1         | 0.88%   |
| 251-300        | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 55        | 49.11%  |
| 121-160       | 27        | 24.11%  |
| 51-100        | 23        | 20.54%  |
| 1-50          | 4         | 3.57%   |
| 161-240       | 2         | 1.79%   |
| More than 240 | 1         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 89        | 83.96%  |
| 2     | 14        | 13.21%  |
| 3     | 2         | 1.89%   |
| 0     | 1         | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 71        | 41.52%  |
| Qualcomm Atheros                | 38        | 22.22%  |
| Intel                           | 33        | 19.3%   |
| Broadcom                        | 12        | 7.02%   |
| Broadcom Limited                | 4         | 2.34%   |
| Marvell Technology Group        | 3         | 1.75%   |
| Samsung Electronics             | 2         | 1.17%   |
| JMicron Technology              | 2         | 1.17%   |
| Xiaomi                          | 1         | 0.58%   |
| Trendchip Technologies          | 1         | 0.58%   |
| Ralink Technology               | 1         | 0.58%   |
| Qualcomm Atheros Communications | 1         | 0.58%   |
| MediaTek                        | 1         | 0.58%   |
| AMD                             | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 35        | 17.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 18        | 9%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 6%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 3.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.5%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 6         | 3%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 5         | 2.5%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2%      |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 1.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 1.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.5%    |
| Intel Wireless 8265 / 8275                                              | 3         | 1.5%    |
| Intel Wireless 7265                                                     | 3         | 1.5%    |
| Intel Centrino Wireless-N 105                                           | 3         | 1.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1%      |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 1%      |
| Intel Wireless 8260                                                     | 2         | 1%      |
| Intel Wireless 7260                                                     | 2         | 1%      |
| Intel Wireless 3165                                                     | 2         | 1%      |
| Intel WiFi Link 5100                                                    | 2         | 1%      |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1%      |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1%      |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1%      |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1%      |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express             | 2         | 1%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1%      |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.5%    |
| Trendchip Ethernet controller                                           | 1         | 0.5%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.5%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 30.77%  |
| Qualcomm Atheros                | 30        | 28.85%  |
| Realtek Semiconductor           | 28        | 26.92%  |
| Broadcom                        | 10        | 9.62%   |
| Ralink Technology               | 1         | 0.96%   |
| Qualcomm Atheros Communications | 1         | 0.96%   |
| MediaTek                        | 1         | 0.96%   |
| Broadcom Limited                | 1         | 0.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 11.54%  |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 6.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 6.73%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 6         | 5.77%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 3.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 3.85%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 2.88%   |
| Intel Wireless 8265 / 8275                                              | 3         | 2.88%   |
| Intel Wireless 7265                                                     | 3         | 2.88%   |
| Intel Centrino Wireless-N 105                                           | 3         | 2.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.92%   |
| Intel Wireless 8260                                                     | 2         | 1.92%   |
| Intel Wireless 7260                                                     | 2         | 1.92%   |
| Intel Wireless 3165                                                     | 2         | 1.92%   |
| Intel WiFi Link 5100                                                    | 2         | 1.92%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.92%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.92%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.92%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.96%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.96%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 0.96%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.96%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.96%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.96%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.96%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.96%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.96%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 58        | 61.7%   |
| Qualcomm Atheros         | 12        | 12.77%  |
| Intel                    | 10        | 10.64%  |
| Marvell Technology Group | 3         | 3.19%   |
| Broadcom Limited         | 3         | 3.19%   |
| Samsung Electronics      | 2         | 2.13%   |
| JMicron Technology       | 2         | 2.13%   |
| Broadcom                 | 2         | 2.13%   |
| Xiaomi                   | 1         | 1.06%   |
| Trendchip Technologies   | 1         | 1.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 36.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 18.95%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 5.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 3.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 3.16%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 2.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.11%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 2.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.11%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 2         | 2.11%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.05%   |
| Trendchip Ethernet controller                                     | 1         | 1.05%   |
| Realtek Realtek Ethernet controller                               | 1         | 1.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.05%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.05%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.05%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.05%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 1.05%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.05%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.05%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.05%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.05%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.05%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.05%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 1.05%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 52.06%  |
| Ethernet | 92        | 47.42%  |
| Modem    | 1         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 70.37%  |
| Ethernet | 32        | 29.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 85        | 81.73%  |
| 1     | 17        | 16.35%  |
| 0     | 2         | 1.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 104       | 99.05%  |
| Yes  | 1         | 0.95%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 34.55%  |
| Qualcomm Atheros Communications | 11        | 20%     |
| IMC Networks                    | 10        | 18.18%  |
| Realtek Semiconductor           | 5         | 9.09%   |
| Broadcom                        | 4         | 7.27%   |
| Cambridge Silicon Radio         | 3         | 5.45%   |
| Lite-On Technology              | 1         | 1.82%   |
| Hewlett-Packard                 | 1         | 1.82%   |
| ASUSTek Computer                | 1         | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 21.82%  |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 9.09%   |
| IMC Networks Bluetooth                              | 4         | 7.27%   |
| Realtek Bluetooth Radio                             | 3         | 5.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 5.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 5.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 5.45%   |
| Realtek RTL8723B Bluetooth                          | 2         | 3.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 3.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 3.64%   |
| Intel AX201 Bluetooth                               | 2         | 3.64%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.64%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 3.64%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.82%   |
| Lite-On Bluetooth Device                            | 1         | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.82%   |
| Intel AX200 Bluetooth                               | 1         | 1.82%   |
| IMC Networks Wireless_Device                        | 1         | 1.82%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.82%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.82%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.82%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 90        | 79.65%  |
| AMD                   | 15        | 13.27%  |
| Nvidia                | 5         | 4.42%   |
| Realtek Semiconductor | 1         | 0.88%   |
| Microsoft             | 1         | 0.88%   |
| Logitech              | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 15.04%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 7.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 6.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 6.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 6.02%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 5.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 5.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 4.51%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.26%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.26%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.5%    |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.5%    |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.5%    |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.5%    |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.75%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Nvidia Audio device                                                                               | 1         | 0.75%   |
| Microsoft LifeChat LX-4000                                                                        | 1         | 0.75%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.75%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 19        | 21.84%  |
| Samsung Electronics | 15        | 17.24%  |
| Unknown             | 11        | 12.64%  |
| Ramaxel Technology  | 11        | 12.64%  |
| Micron Technology   | 9         | 10.34%  |
| Kingston            | 5         | 5.75%   |
| Crucial             | 5         | 5.75%   |
| Elpida              | 3         | 3.45%   |
| Unknown (ABCD)      | 2         | 2.3%    |
| Unknown             | 2         | 2.3%    |
| Unknown (081A)      | 1         | 1.15%   |
| Qimonda             | 1         | 1.15%   |
| Memox               | 1         | 1.15%   |
| Corsair             | 1         | 1.15%   |
| A-DATA Technology   | 1         | 1.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 3         | 3.26%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s          | 3         | 3.26%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s          | 3         | 3.26%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.17%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.17%   |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s         | 2         | 2.17%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 2.17%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 2.17%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s          | 2         | 2.17%   |
| Unknown                                                          | 2         | 2.17%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.09%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 1.09%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.09%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.09%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.09%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.09%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                        | 1         | 1.09%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 1.09%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.09%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 1.09%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.09%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 1         | 1.09%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 1.09%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s  | 1         | 1.09%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 1.09%   |
| Unknown (081A) RAM HXMSH2GS03A2F1CL16 2GB SODIMM DDR3 1600MT/s   | 1         | 1.09%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.09%   |
| SK hynix RAM HMT451S6BFR8A-RD 4GB SODIMM DDR3 1867MT/s           | 1         | 1.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.09%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.09%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.09%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.09%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.09%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.09%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.09%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.09%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.09%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.09%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 1         | 1.09%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8192MB SODIMM DDR4 2400MT/s        | 1         | 1.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 27        | 41.54%  |
| DDR4   | 20        | 30.77%  |
| DDR2   | 10        | 15.38%  |
| SDRAM  | 4         | 6.15%   |
| LPDDR4 | 3         | 4.62%   |
| DDR    | 1         | 1.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 59        | 95.16%  |
| Row Of Chips | 2         | 3.23%   |
| DIMM         | 1         | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 23        | 31.08%  |
| 2048  | 23        | 31.08%  |
| 8192  | 20        | 27.03%  |
| 16384 | 4         | 5.41%   |
| 1024  | 4         | 5.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 24        | 32.43%  |
| 2667    | 9         | 12.16%  |
| 2400    | 7         | 9.46%   |
| 3200    | 6         | 8.11%   |
| 1333    | 5         | 6.76%   |
| 667     | 5         | 6.76%   |
| 1334    | 3         | 4.05%   |
| 4199    | 2         | 2.7%    |
| 2048    | 2         | 2.7%    |
| 1067    | 2         | 2.7%    |
| 533     | 2         | 2.7%    |
| Unknown | 2         | 2.7%    |
| 3266    | 1         | 1.35%   |
| 2133    | 1         | 1.35%   |
| 1867    | 1         | 1.35%   |
| 975     | 1         | 1.35%   |
| 800     | 1         | 1.35%   |

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
| Chicony Electronics                    | 17        | 21.52%  |
| Microdia                               | 13        | 16.46%  |
| Acer                                   | 11        | 13.92%  |
| Realtek Semiconductor                  | 9         | 11.39%  |
| IMC Networks                           | 5         | 6.33%   |
| Suyin                                  | 4         | 5.06%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.8%    |
| Syntek                                 | 2         | 2.53%   |
| Sunplus Innovation Technology          | 2         | 2.53%   |
| Ricoh                                  | 2         | 2.53%   |
| Quanta                                 | 2         | 2.53%   |
| Lite-On Technology                     | 2         | 2.53%   |
| Tobii Technology AB                    | 1         | 1.27%   |
| Sonix Technology                       | 1         | 1.27%   |
| Luxvisions Innotech Limited            | 1         | 1.27%   |
| Lenovo                                 | 1         | 1.27%   |
| icSpring                               | 1         | 1.27%   |
| Apple                                  | 1         | 1.27%   |
| ALi                                    | 1         | 1.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                  | 4         | 5.06%   |
| Microdia USB 2.0 Camera                                       | 4         | 5.06%   |
| Chicony USB 2.0 Camera                                        | 4         | 5.06%   |
| Acer HD Webcam                                                | 4         | 5.06%   |
| Chicony Lenovo EasyCamera                                     | 3         | 3.8%    |
| Microdia Integrated_Webcam_HD                                 | 2         | 2.53%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 2.53%   |
| IMC Networks Lenovo EasyCamera                                | 2         | 2.53%   |
| Chicony Integrated Camera                                     | 2         | 2.53%   |
| Chicony HD WebCam                                             | 2         | 2.53%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 2         | 2.53%   |
| Acer USB Camera                                               | 2         | 2.53%   |
| Acer Lenovo EasyCamera                                        | 2         | 2.53%   |
| Tobii AB EyeChip                                              | 1         | 1.27%   |
| Syntek USB Camera Device                                      | 1         | 1.27%   |
| Syntek Integrated Webcam                                      | 1         | 1.27%   |
| Suyin USB2.0 UVC 1.3M WebCam                                  | 1         | 1.27%   |
| Suyin HP Webcam 101                                           | 1         | 1.27%   |
| Suyin Acer HD Crystal Eye webcam                              | 1         | 1.27%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 1.27%   |
| Sunplus MTD Camera                                            | 1         | 1.27%   |
| Sunplus Integrated_Webcam_HD                                  | 1         | 1.27%   |
| Sonix USB2.0 HD UVC WebCam                                    | 1         | 1.27%   |
| Ricoh Sony Vaio Integrated Webcam                             | 1         | 1.27%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 1         | 1.27%   |
| Realtek USB2.0 camera                                         | 1         | 1.27%   |
| Realtek USB Camera                                            | 1         | 1.27%   |
| Realtek Integrated Webcam HD                                  | 1         | 1.27%   |
| Realtek Integrated Webcam                                     | 1         | 1.27%   |
| Realtek EasyCamera                                            | 1         | 1.27%   |
| Quanta HP Webcam                                              | 1         | 1.27%   |
| Quanta HD User Facing                                         | 1         | 1.27%   |
| Microdia WebCam SC-13HDL12639P                                | 1         | 1.27%   |
| Microdia USB camera                                           | 1         | 1.27%   |
| Microdia Sonix USB 2.0 Camera                                 | 1         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_HD                          | 1         | 1.27%   |
| Microdia Integrated_Webcam_FHD                                | 1         | 1.27%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera           | 1         | 1.27%   |
| Lite-On TOSHIBA Web Camera - HD                               | 1         | 1.27%   |
| Lite-On HP HD Webcam                                          | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 60%     |
| AuthenTec                  | 2         | 20%     |
| Shenzhen Goodix Technology | 1         | 10%     |
| Futronic Technology        | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader  | 2         | 20%     |
| AuthenTec AES2501 Fingerprint Sensor        | 2         | 20%     |
| Validity Sensors VFS471 Fingerprint Reader  | 1         | 10%     |
| Validity Sensors Fingerprint scanner        | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader          | 1         | 10%     |
| Futronic Fingerprint Scanner Model FS88     | 1         | 10%     |

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
| 0     | 85        | 80.19%  |
| 1     | 17        | 16.04%  |
| 2     | 3         | 2.83%   |
| 4     | 1         | 0.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 37.04%  |
| Chipcard                 | 5         | 18.52%  |
| Graphics card            | 4         | 14.81%  |
| Net/wireless             | 3         | 11.11%  |
| Camera                   | 2         | 7.41%   |
| Storage                  | 1         | 3.7%    |
| Sound                    | 1         | 3.7%    |
| Communication controller | 1         | 3.7%    |

