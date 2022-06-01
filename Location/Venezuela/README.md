Linux in Venezuela - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Venezuela.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Venezuela/Desktop/README.md) and [notebooks](/Location/Venezuela/Notebook/README.md).

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

Total: 290

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| VIT           | M2420                       | Notebook    | [c2ea650175](https://linux-hardware.org/?probe=c2ea650175) | Jun 01, 2022 |
| Dell          | Precision 7710              | Notebook    | [befe390051](https://linux-hardware.org/?probe=befe390051) | May 28, 2022 |
| Lenovo        | 11051CS ThinkServer TS13... | Desktop     | [48e6a5501d](https://linux-hardware.org/?probe=48e6a5501d) | May 26, 2022 |
| Acer          | TravelMate 5742Z            | Notebook    | [fd6407ece1](https://linux-hardware.org/?probe=fd6407ece1) | May 26, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [13918cd2b7](https://linux-hardware.org/?probe=13918cd2b7) | May 23, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [0e7bf88677](https://linux-hardware.org/?probe=0e7bf88677) | May 19, 2022 |
| IP3 Tech      | TB20                        | Desktop     | [1cf2be0840](https://linux-hardware.org/?probe=1cf2be0840) | May 16, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [8dc1b9cd87](https://linux-hardware.org/?probe=8dc1b9cd87) | May 14, 2022 |
| Intel         | H61                         | Desktop     | [28277b5d5a](https://linux-hardware.org/?probe=28277b5d5a) | May 10, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [00620504c7](https://linux-hardware.org/?probe=00620504c7) | Apr 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ff32f84c4e](https://linux-hardware.org/?probe=ff32f84c4e) | Apr 23, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [8869defd9c](https://linux-hardware.org/?probe=8869defd9c) | Apr 22, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [8510a8836c](https://linux-hardware.org/?probe=8510a8836c) | Apr 18, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [6c3ed980a1](https://linux-hardware.org/?probe=6c3ed980a1) | Apr 18, 2022 |
| Clevo         | W54xEU                      | Notebook    | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Dell          | Latitude 5590               | Notebook    | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| HP            | Pavilion dv5                | Notebook    | [22aa828b2f](https://linux-hardware.org/?probe=22aa828b2f) | Apr 16, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Clevo         | W54xEU                      | Notebook    | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3f66b1cb5c](https://linux-hardware.org/?probe=3f66b1cb5c) | Apr 13, 2022 |
| Dell          | Latitude 5590               | Notebook    | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [659999d04a](https://linux-hardware.org/?probe=659999d04a) | Apr 11, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [227c3936b8](https://linux-hardware.org/?probe=227c3936b8) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [6cb82accd9](https://linux-hardware.org/?probe=6cb82accd9) | Apr 07, 2022 |
| ASRock        | G31M-S                      | Desktop     | [33737ec5ba](https://linux-hardware.org/?probe=33737ec5ba) | Apr 01, 2022 |
| Gateway       | NV57H                       | Notebook    | [ce2e78a407](https://linux-hardware.org/?probe=ce2e78a407) | Mar 31, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| Intel         | D945GCCR AAD78647-300       | Desktop     | [c3d1b55376](https://linux-hardware.org/?probe=c3d1b55376) | Mar 27, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [552956f271](https://linux-hardware.org/?probe=552956f271) | Mar 24, 2022 |
| VIT           | P2402                       | Notebook    | [5d9e3733ea](https://linux-hardware.org/?probe=5d9e3733ea) | Mar 21, 2022 |
| ASRock        | H370M-HDV                   | Desktop     | [9945efc3fa](https://linux-hardware.org/?probe=9945efc3fa) | Mar 20, 2022 |
| Inspur        | Computer All in one PC V... | Desktop     | [5c419895c5](https://linux-hardware.org/?probe=5c419895c5) | Mar 18, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [3dcc73772f](https://linux-hardware.org/?probe=3dcc73772f) | Mar 12, 2022 |
| MSI           | 3664h                       | Desktop     | [e5eaec6553](https://linux-hardware.org/?probe=e5eaec6553) | Mar 08, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [5fa0d18666](https://linux-hardware.org/?probe=5fa0d18666) | Mar 04, 2022 |
| VIT           | NP3020M3                    | Server      | [9fbb87a829](https://linux-hardware.org/?probe=9fbb87a829) | Mar 03, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [0e8fbc26f1](https://linux-hardware.org/?probe=0e8fbc26f1) | Mar 01, 2022 |
| Pegatron      | 2ACC                        | Desktop     | [c1127626c5](https://linux-hardware.org/?probe=c1127626c5) | Mar 01, 2022 |
| VIT           | P3400                       | Notebook    | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Intel         | powered classmate PC        | Tablet      | [a2b7a04dfa](https://linux-hardware.org/?probe=a2b7a04dfa) | Feb 18, 2022 |
| VIT           | P3400                       | Notebook    | [b90c32748d](https://linux-hardware.org/?probe=b90c32748d) | Feb 18, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [89cecb62bc](https://linux-hardware.org/?probe=89cecb62bc) | Feb 17, 2022 |
| Lenovo        | ThinkPad X201 3680AE2       | Notebook    | [cb777c91bc](https://linux-hardware.org/?probe=cb777c91bc) | Feb 13, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [16dbcf63f1](https://linux-hardware.org/?probe=16dbcf63f1) | Feb 12, 2022 |
| ECS           | KAM1-I                      | Desktop     | [be38f855ff](https://linux-hardware.org/?probe=be38f855ff) | Feb 10, 2022 |
| Gateway       | NV57H                       | Notebook    | [9d59228f90](https://linux-hardware.org/?probe=9d59228f90) | Feb 09, 2022 |
| ASRock        | A55M-HVS                    | Desktop     | [c4c68e7dd1](https://linux-hardware.org/?probe=c4c68e7dd1) | Feb 08, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [ac9ed3224d](https://linux-hardware.org/?probe=ac9ed3224d) | Feb 01, 2022 |
| ASUSTek       | P6X58-E PRO                 | Desktop     | [9ee8e1ecdf](https://linux-hardware.org/?probe=9ee8e1ecdf) | Jan 30, 2022 |
| Intel         | DG41TY AAE47335-203         | Desktop     | [01ec1ff569](https://linux-hardware.org/?probe=01ec1ff569) | Jan 26, 2022 |
| MSI           | MS-1454                     | Notebook    | [1cb9a056e7](https://linux-hardware.org/?probe=1cb9a056e7) | Jan 14, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8700fd1193](https://linux-hardware.org/?probe=8700fd1193) | Jan 11, 2022 |
| VIT           | M2421                       | Notebook    | [c6cc8a474d](https://linux-hardware.org/?probe=c6cc8a474d) | Jan 10, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b6cffe86a0](https://linux-hardware.org/?probe=b6cffe86a0) | Dec 23, 2021 |
| UNIQCELL      | Q15.6                       | Notebook    | [d21e7048e1](https://linux-hardware.org/?probe=d21e7048e1) | Dec 20, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| AVITA         | NS14A1US                    | Notebook    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| Intel         | powered classmate PC        | Notebook    | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | Notebook    | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [8d19cd079a](https://linux-hardware.org/?probe=8d19cd079a) | Dec 09, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [ecd0add9b3](https://linux-hardware.org/?probe=ecd0add9b3) | Dec 09, 2021 |
| HP            | 3398                        | Desktop     | [5ae73e1468](https://linux-hardware.org/?probe=5ae73e1468) | Dec 07, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Lenovo        | B40-70 20392                | Notebook    | [4f4458d61a](https://linux-hardware.org/?probe=4f4458d61a) | Nov 23, 2021 |
| Intel         | powered classmate PC        | Tablet      | [aea7e0243a](https://linux-hardware.org/?probe=aea7e0243a) | Nov 21, 2021 |
| Intel         | powered classmate PC        | Tablet      | [444812feb3](https://linux-hardware.org/?probe=444812feb3) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [2f83ccbc4f](https://linux-hardware.org/?probe=2f83ccbc4f) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a492e3e1ff](https://linux-hardware.org/?probe=a492e3e1ff) | Nov 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b37e3324e3](https://linux-hardware.org/?probe=b37e3324e3) | Nov 05, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| VIT           | P3400                       | Notebook    | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [d1d57448c4](https://linux-hardware.org/?probe=d1d57448c4) | Oct 29, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [f5112dbf47](https://linux-hardware.org/?probe=f5112dbf47) | Oct 29, 2021 |
| Dell          | Latitude E7450              | Notebook    | [9cbd7f01e8](https://linux-hardware.org/?probe=9cbd7f01e8) | Oct 18, 2021 |
| Dell          | Latitude E6420              | Notebook    | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| Biostar       | P4M90-M7A Ver:1.0           | Desktop     | [d8875918ac](https://linux-hardware.org/?probe=d8875918ac) | Oct 16, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [e5391d41e0](https://linux-hardware.org/?probe=e5391d41e0) | Oct 14, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [3f6e406107](https://linux-hardware.org/?probe=3f6e406107) | Oct 14, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [903dc4ef05](https://linux-hardware.org/?probe=903dc4ef05) | Oct 13, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [1ec421714e](https://linux-hardware.org/?probe=1ec421714e) | Oct 02, 2021 |
| HP            | 1495                        | Desktop     | [64cbb112e2](https://linux-hardware.org/?probe=64cbb112e2) | Oct 01, 2021 |
| Clevo         | W54xEU                      | Notebook    | [a6732ab721](https://linux-hardware.org/?probe=a6732ab721) | Sep 30, 2021 |
| VIT           | P3400                       | Notebook    | [22260810d1](https://linux-hardware.org/?probe=22260810d1) | Sep 27, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [4571e36b80](https://linux-hardware.org/?probe=4571e36b80) | Sep 26, 2021 |
| ASUSTek       | TUF Gaming FA506IH_FA506... | Notebook    | [5854fbcaed](https://linux-hardware.org/?probe=5854fbcaed) | Sep 17, 2021 |
| Foxconn       | M61PMV FAB                  | Desktop     | [290d3e0fd5](https://linux-hardware.org/?probe=290d3e0fd5) | Sep 14, 2021 |
| Pegatron      | T14AF                       | Notebook    | [46067ec02a](https://linux-hardware.org/?probe=46067ec02a) | Sep 07, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [202fe67100](https://linux-hardware.org/?probe=202fe67100) | Aug 27, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [321f53f711](https://linux-hardware.org/?probe=321f53f711) | Aug 27, 2021 |
| Lenovo        | ThinkPad Edge 01962AS       | Notebook    | [8ccb24d0d8](https://linux-hardware.org/?probe=8ccb24d0d8) | Aug 24, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [ec9367ff70](https://linux-hardware.org/?probe=ec9367ff70) | Aug 16, 2021 |
| VIT           | P2400                       | Notebook    | [f844ffff09](https://linux-hardware.org/?probe=f844ffff09) | Aug 11, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Foxconn       | ELA01                       | Desktop     | [13bcd06d5f](https://linux-hardware.org/?probe=13bcd06d5f) | Jul 23, 2021 |
| Foxconn       | ELA01                       | Desktop     | [a73982649a](https://linux-hardware.org/?probe=a73982649a) | Jul 22, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c726cd767b](https://linux-hardware.org/?probe=c726cd767b) | Jul 19, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [ab44db5647](https://linux-hardware.org/?probe=ab44db5647) | Jul 18, 2021 |
| Lenovo        | ThinkCentre M71e 3157G6S    | Desktop     | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [60c62c33f8](https://linux-hardware.org/?probe=60c62c33f8) | Jul 14, 2021 |
| Biostar       | G41D3                       | Desktop     | [673d4faa98](https://linux-hardware.org/?probe=673d4faa98) | Jul 12, 2021 |
| HP            | 3397                        | Desktop     | [f1a6d10d78](https://linux-hardware.org/?probe=f1a6d10d78) | Jul 08, 2021 |
| HP            | 3397                        | Desktop     | [e087e03e0b](https://linux-hardware.org/?probe=e087e03e0b) | Jul 08, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [a57f28921c](https://linux-hardware.org/?probe=a57f28921c) | Jul 05, 2021 |
| ECS           | Livermore                   | Desktop     | [b471a4666c](https://linux-hardware.org/?probe=b471a4666c) | Jun 30, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [c468ca84d3](https://linux-hardware.org/?probe=c468ca84d3) | Jun 30, 2021 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [a82bafec08](https://linux-hardware.org/?probe=a82bafec08) | Jun 29, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [93c6a703a7](https://linux-hardware.org/?probe=93c6a703a7) | Jun 27, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [f7e407b14c](https://linux-hardware.org/?probe=f7e407b14c) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [fc58981ecd](https://linux-hardware.org/?probe=fc58981ecd) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [bce9c74edb](https://linux-hardware.org/?probe=bce9c74edb) | Jun 27, 2021 |
| ECS           | Livermore                   | Desktop     | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [cb1c07fa68](https://linux-hardware.org/?probe=cb1c07fa68) | Jun 17, 2021 |
| VIT           | P2400                       | Notebook    | [295d4d5a47](https://linux-hardware.org/?probe=295d4d5a47) | Jun 17, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [512537c402](https://linux-hardware.org/?probe=512537c402) | Jun 17, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [9773736b0f](https://linux-hardware.org/?probe=9773736b0f) | Jun 17, 2021 |
| ECS           | G31T-M7                     | Desktop     | [01ed8410e9](https://linux-hardware.org/?probe=01ed8410e9) | Jun 15, 2021 |
| Lenovo        | ThinkCentre M55E 9645BN2    | Desktop     | [ef91279611](https://linux-hardware.org/?probe=ef91279611) | Jun 15, 2021 |
| VIT           | P1400                       | Notebook    | [129d543695](https://linux-hardware.org/?probe=129d543695) | Jun 13, 2021 |
| Biostar       | G41D3C                      | Desktop     | [263491c02a](https://linux-hardware.org/?probe=263491c02a) | Jun 07, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [423b514d2b](https://linux-hardware.org/?probe=423b514d2b) | May 30, 2021 |
| VIT           | P2400                       | Notebook    | [f39537fca1](https://linux-hardware.org/?probe=f39537fca1) | May 28, 2021 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [0f12ef1983](https://linux-hardware.org/?probe=0f12ef1983) | May 25, 2021 |
| VIT           | P2400                       | Notebook    | [4fa6d109de](https://linux-hardware.org/?probe=4fa6d109de) | May 25, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [42960896cb](https://linux-hardware.org/?probe=42960896cb) | May 20, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [4856303cbe](https://linux-hardware.org/?probe=4856303cbe) | May 20, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [1a9761824e](https://linux-hardware.org/?probe=1a9761824e) | May 20, 2021 |
| Intel         | powered classmate PC        | Notebook    | [a3b0d4e33e](https://linux-hardware.org/?probe=a3b0d4e33e) | May 12, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [9e701873b1](https://linux-hardware.org/?probe=9e701873b1) | May 09, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [59a6774cd5](https://linux-hardware.org/?probe=59a6774cd5) | May 09, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [f16304ca03](https://linux-hardware.org/?probe=f16304ca03) | May 04, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [8eca6b6f79](https://linux-hardware.org/?probe=8eca6b6f79) | May 04, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [bef0f33897](https://linux-hardware.org/?probe=bef0f33897) | May 02, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [8d84f6dc9e](https://linux-hardware.org/?probe=8d84f6dc9e) | Apr 25, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [db04624ac3](https://linux-hardware.org/?probe=db04624ac3) | Apr 20, 2021 |
| Acer          | Aspire 4935                 | Notebook    | [cbe6a288f1](https://linux-hardware.org/?probe=cbe6a288f1) | Apr 06, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [330f034c61](https://linux-hardware.org/?probe=330f034c61) | Apr 04, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [4cf71fac35](https://linux-hardware.org/?probe=4cf71fac35) | Apr 04, 2021 |
| Toshiba       | Satellite E55t-A            | Notebook    | [e1a3602d7b](https://linux-hardware.org/?probe=e1a3602d7b) | Mar 28, 2021 |
| Dell          | Vostro 1500                 | Notebook    | [76ade477e8](https://linux-hardware.org/?probe=76ade477e8) | Mar 28, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [28996604f4](https://linux-hardware.org/?probe=28996604f4) | Mar 27, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [e90c94fd9d](https://linux-hardware.org/?probe=e90c94fd9d) | Mar 27, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [7f2618efb7](https://linux-hardware.org/?probe=7f2618efb7) | Mar 12, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [918f841c61](https://linux-hardware.org/?probe=918f841c61) | Mar 12, 2021 |
| HP            | 1495                        | Desktop     | [248af9611e](https://linux-hardware.org/?probe=248af9611e) | Mar 11, 2021 |
| Dell          | 0GX297                      | Desktop     | [6ac3da669a](https://linux-hardware.org/?probe=6ac3da669a) | Mar 09, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [543e8d3501](https://linux-hardware.org/?probe=543e8d3501) | Mar 07, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [892f3e6658](https://linux-hardware.org/?probe=892f3e6658) | Mar 07, 2021 |
| HP            | 2000                        | Notebook    | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| Intel         | S5500BC E25124-407          | Server      | [fe3d758c20](https://linux-hardware.org/?probe=fe3d758c20) | Mar 06, 2021 |
| Pegatron      | NARRA5                      | Desktop     | [e7550259a4](https://linux-hardware.org/?probe=e7550259a4) | Mar 06, 2021 |
| Pegatron      | NARRA5                      | Desktop     | [294b1c19fb](https://linux-hardware.org/?probe=294b1c19fb) | Feb 20, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [9e6a12d9e1](https://linux-hardware.org/?probe=9e6a12d9e1) | Feb 15, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [4883c81a02](https://linux-hardware.org/?probe=4883c81a02) | Feb 07, 2021 |
| AVITA         | NS14A1US                    | Notebook    | [63ab85aac6](https://linux-hardware.org/?probe=63ab85aac6) | Feb 05, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [570fb5f20b](https://linux-hardware.org/?probe=570fb5f20b) | Jan 27, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [b481e5f8d2](https://linux-hardware.org/?probe=b481e5f8d2) | Jan 27, 2021 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e4d1cc65bc](https://linux-hardware.org/?probe=e4d1cc65bc) | Jan 27, 2021 |
| HP            | 1493                        | Desktop     | [febb5aee31](https://linux-hardware.org/?probe=febb5aee31) | Jan 15, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| Dell          | Inspiron 3180               | Notebook    | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| Pegatron      | IPM41-D3                    | Desktop     | [4e0489bdb0](https://linux-hardware.org/?probe=4e0489bdb0) | Dec 05, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [5751926628](https://linux-hardware.org/?probe=5751926628) | Nov 23, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [812b2188d4](https://linux-hardware.org/?probe=812b2188d4) | Nov 23, 2020 |
| Biostar       | A55MLC2                     | Desktop     | [e195f622e4](https://linux-hardware.org/?probe=e195f622e4) | Nov 22, 2020 |
| Biostar       | A55MLC2                     | Desktop     | [a0456b9ad3](https://linux-hardware.org/?probe=a0456b9ad3) | Nov 22, 2020 |
| HP            | 1495                        | Desktop     | [72bdee2784](https://linux-hardware.org/?probe=72bdee2784) | Nov 19, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [1d1e7e6236](https://linux-hardware.org/?probe=1d1e7e6236) | Nov 07, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [31fa456854](https://linux-hardware.org/?probe=31fa456854) | Nov 07, 2020 |
| Exo           | AIO A210                    | Notebook    | [2082cc5386](https://linux-hardware.org/?probe=2082cc5386) | Nov 02, 2020 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [c172177266](https://linux-hardware.org/?probe=c172177266) | Oct 31, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [8de08ff7ac](https://linux-hardware.org/?probe=8de08ff7ac) | Oct 24, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [46849fa419](https://linux-hardware.org/?probe=46849fa419) | Oct 24, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [0fa1b76517](https://linux-hardware.org/?probe=0fa1b76517) | Oct 15, 2020 |
| Foxconn       | M61PMV FAB A1               | Desktop     | [cb7568786f](https://linux-hardware.org/?probe=cb7568786f) | Oct 05, 2020 |
| Lenovo        | G460 20041                  | Notebook    | [6944572eca](https://linux-hardware.org/?probe=6944572eca) | Oct 02, 2020 |
| Lenovo        | G460 20041                  | Notebook    | [1f4ffcafa7](https://linux-hardware.org/?probe=1f4ffcafa7) | Oct 02, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [db328c3c01](https://linux-hardware.org/?probe=db328c3c01) | Sep 29, 2020 |
| ECS           | H61H2-CM                    | Desktop     | [8ae7ffac0b](https://linux-hardware.org/?probe=8ae7ffac0b) | Sep 28, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [0d9041893c](https://linux-hardware.org/?probe=0d9041893c) | Sep 15, 2020 |
| Unknown       | Unknown                     | Notebook    | [922d1c2533](https://linux-hardware.org/?probe=922d1c2533) | Sep 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [f56d6dcffd](https://linux-hardware.org/?probe=f56d6dcffd) | Sep 11, 2020 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Intel         | powered classmate PC        | Tablet      | [4f4efbc5c6](https://linux-hardware.org/?probe=4f4efbc5c6) | Sep 06, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [5f5f0bd2cf](https://linux-hardware.org/?probe=5f5f0bd2cf) | Aug 29, 2020 |
| Biostar       | N68S3B                      | Desktop     | [1e4d89cafe](https://linux-hardware.org/?probe=1e4d89cafe) | Aug 27, 2020 |
| MSI           | FM2-A75MA-E35               | Desktop     | [7f40a96159](https://linux-hardware.org/?probe=7f40a96159) | Aug 20, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8445b18759](https://linux-hardware.org/?probe=8445b18759) | Aug 20, 2020 |
| HP            | Presario V2000 (EW997LA#... | Notebook    | [77a2a0c00f](https://linux-hardware.org/?probe=77a2a0c00f) | Aug 15, 2020 |
| Alienware     | 17 R4                       | Notebook    | [c1a871b29b](https://linux-hardware.org/?probe=c1a871b29b) | Aug 14, 2020 |
| ECS           | H61H2-CM                    | Desktop     | [43d0144f0a](https://linux-hardware.org/?probe=43d0144f0a) | Aug 06, 2020 |
| MSI           | K9N2 Diamond                | Desktop     | [07a001660f](https://linux-hardware.org/?probe=07a001660f) | Aug 04, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [56ad5a6a22](https://linux-hardware.org/?probe=56ad5a6a22) | Jul 29, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [f2fdb4f618](https://linux-hardware.org/?probe=f2fdb4f618) | Jul 27, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [a2e742ec36](https://linux-hardware.org/?probe=a2e742ec36) | Jul 27, 2020 |
| VIT           | M2421                       | Notebook    | [451969e0fc](https://linux-hardware.org/?probe=451969e0fc) | Jul 27, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [6786c103d7](https://linux-hardware.org/?probe=6786c103d7) | Jul 27, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [8081f20c91](https://linux-hardware.org/?probe=8081f20c91) | Jul 25, 2020 |
| Intel         | powered classmate PC        | Notebook    | [1ffa275c8b](https://linux-hardware.org/?probe=1ffa275c8b) | Jul 12, 2020 |
| Intel         | powered classmate PC        | Notebook    | [49442bdbca](https://linux-hardware.org/?probe=49442bdbca) | Jul 11, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [39510acc74](https://linux-hardware.org/?probe=39510acc74) | Jul 06, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [eff9ad2c7d](https://linux-hardware.org/?probe=eff9ad2c7d) | Jul 05, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [a1e610807e](https://linux-hardware.org/?probe=a1e610807e) | Jun 30, 2020 |
| HP            | Presario C700               | Notebook    | [6b50a4fad1](https://linux-hardware.org/?probe=6b50a4fad1) | Jun 26, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [e8c521f7e8](https://linux-hardware.org/?probe=e8c521f7e8) | Jun 25, 2020 |
| Standard      | AHV                         | All in one  | [989175dbdc](https://linux-hardware.org/?probe=989175dbdc) | Jun 08, 2020 |
| Standard      | AHV                         | All in one  | [f0bd9ac2e1](https://linux-hardware.org/?probe=f0bd9ac2e1) | Jun 07, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [cd52689b0a](https://linux-hardware.org/?probe=cd52689b0a) | May 25, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [d48d360c14](https://linux-hardware.org/?probe=d48d360c14) | May 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [e8a608f296](https://linux-hardware.org/?probe=e8a608f296) | May 23, 2020 |
| Lenovo        | ThinkCentre A55 8705AV4     | Desktop     | [18c81b7e8b](https://linux-hardware.org/?probe=18c81b7e8b) | May 19, 2020 |
| Lenovo        | ThinkCentre A55 8705AV4     | Desktop     | [cce631f67b](https://linux-hardware.org/?probe=cce631f67b) | May 19, 2020 |
| VIT           | P3400                       | Notebook    | [48c981187d](https://linux-hardware.org/?probe=48c981187d) | May 18, 2020 |
| Intel         | DG41TX AAE78178-303         | Desktop     | [084641dbc1](https://linux-hardware.org/?probe=084641dbc1) | May 17, 2020 |
| VIT           | P3400                       | Notebook    | [f9be2de38c](https://linux-hardware.org/?probe=f9be2de38c) | May 14, 2020 |
| HP            | Pavilion dv4                | Notebook    | [2efd349a3f](https://linux-hardware.org/?probe=2efd349a3f) | May 13, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [b55d1daea5](https://linux-hardware.org/?probe=b55d1daea5) | May 11, 2020 |
| VIT           | P2402                       | Notebook    | [bacbeb66bd](https://linux-hardware.org/?probe=bacbeb66bd) | May 07, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [97e5a8c8da](https://linux-hardware.org/?probe=97e5a8c8da) | Apr 26, 2020 |
| VIT           | P3400                       | Notebook    | [cd75b7e2c3](https://linux-hardware.org/?probe=cd75b7e2c3) | Apr 24, 2020 |
| VIT           | P2400                       | Notebook    | [4acb382140](https://linux-hardware.org/?probe=4acb382140) | Apr 23, 2020 |
| VIT           | M2420                       | Notebook    | [a7535d12dc](https://linux-hardware.org/?probe=a7535d12dc) | Apr 13, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [b3436f0ec6](https://linux-hardware.org/?probe=b3436f0ec6) | Apr 11, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [841ded939f](https://linux-hardware.org/?probe=841ded939f) | Mar 31, 2020 |
| Lenovo        | ThinkCentre A58 7515A33     | Desktop     | [75be0ab7ac](https://linux-hardware.org/?probe=75be0ab7ac) | Mar 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [ebbf8f7b4e](https://linux-hardware.org/?probe=ebbf8f7b4e) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [e39e92a6f9](https://linux-hardware.org/?probe=e39e92a6f9) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [b9d2e7e174](https://linux-hardware.org/?probe=b9d2e7e174) | Mar 20, 2020 |
| VIT           | P2402                       | Notebook    | [9f90b82033](https://linux-hardware.org/?probe=9f90b82033) | Mar 10, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [1d140aa76c](https://linux-hardware.org/?probe=1d140aa76c) | Mar 07, 2020 |
| Acer          | Aspire Z3730                | All in one  | [24d42a520e](https://linux-hardware.org/?probe=24d42a520e) | Mar 03, 2020 |
| VIT           | P2402                       | Notebook    | [ea6b959930](https://linux-hardware.org/?probe=ea6b959930) | Mar 03, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [2859756e56](https://linux-hardware.org/?probe=2859756e56) | Feb 29, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [79f0a68dd3](https://linux-hardware.org/?probe=79f0a68dd3) | Feb 26, 2020 |
| Lenovo        | ThinkCentre XXXX 8705A84    | Desktop     | [b824441963](https://linux-hardware.org/?probe=b824441963) | Feb 23, 2020 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [d1a4bff183](https://linux-hardware.org/?probe=d1a4bff183) | Feb 15, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [33fc6022df](https://linux-hardware.org/?probe=33fc6022df) | Feb 06, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [e79318e87d](https://linux-hardware.org/?probe=e79318e87d) | Feb 06, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [3e6bc93a39](https://linux-hardware.org/?probe=3e6bc93a39) | Jan 31, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [b6ba4394f7](https://linux-hardware.org/?probe=b6ba4394f7) | Jan 29, 2020 |
| ASUSTek       | Leonite2                    | Desktop     | [d0d56d5609](https://linux-hardware.org/?probe=d0d56d5609) | Jan 23, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [17f334232d](https://linux-hardware.org/?probe=17f334232d) | Jan 01, 2020 |
| VIT           | Aptio CRB                   | Mini pc     | [d999c674f1](https://linux-hardware.org/?probe=d999c674f1) | Dec 23, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [41131b1d8e](https://linux-hardware.org/?probe=41131b1d8e) | Dec 23, 2019 |
| Intel         | powered classmate PC        | Notebook    | [b772cf9349](https://linux-hardware.org/?probe=b772cf9349) | Dec 11, 2019 |
| Intel         | powered classmate PC        | Notebook    | [b66f15db35](https://linux-hardware.org/?probe=b66f15db35) | Dec 11, 2019 |
| Lenovo        | ThinkCentre M55E 9632BU8    | Desktop     | [209a9171b1](https://linux-hardware.org/?probe=209a9171b1) | Dec 04, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [2d4b473d59](https://linux-hardware.org/?probe=2d4b473d59) | Dec 01, 2019 |
| Pegatron      | 2A73h                       | Desktop     | [2371d130d0](https://linux-hardware.org/?probe=2371d130d0) | Nov 30, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [aba5fa885d](https://linux-hardware.org/?probe=aba5fa885d) | Nov 25, 2019 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [7c2893dba4](https://linux-hardware.org/?probe=7c2893dba4) | Nov 15, 2019 |
| IBM           | 8188LS4                     | Desktop     | [3d775f418d](https://linux-hardware.org/?probe=3d775f418d) | Oct 08, 2019 |
| Foxconn       | 8657MF-series               | Desktop     | [8ce7f69a15](https://linux-hardware.org/?probe=8ce7f69a15) | Oct 05, 2019 |
| IBM           | 8188LS4                     | Desktop     | [3fc14db446](https://linux-hardware.org/?probe=3fc14db446) | Oct 05, 2019 |
| IBM           | 8188LS4                     | Desktop     | [af840eb366](https://linux-hardware.org/?probe=af840eb366) | Oct 04, 2019 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [530c41513b](https://linux-hardware.org/?probe=530c41513b) | Sep 20, 2019 |
| Intel         | powered classmate PC        | Tablet      | [05f47d610a](https://linux-hardware.org/?probe=05f47d610a) | Aug 22, 2019 |
| Pegatron      | 2AAE                        | Desktop     | [f80cb4a7f2](https://linux-hardware.org/?probe=f80cb4a7f2) | Aug 17, 2019 |
| Dell          | 0RK936                      | Desktop     | [060c60558b](https://linux-hardware.org/?probe=060c60558b) | Aug 08, 2019 |
| ASUSTek       | P8H61-M PRO                 | Desktop     | [e107cafe33](https://linux-hardware.org/?probe=e107cafe33) | Jun 07, 2019 |
| ASRock        | H67M-GE                     | Desktop     | [65dd091a6f](https://linux-hardware.org/?probe=65dd091a6f) | May 13, 2019 |
| Lenovo        | G480 20150                  | Notebook    | [1b7e674c82](https://linux-hardware.org/?probe=1b7e674c82) | May 08, 2019 |
| Lenovo        | G480 20150                  | Notebook    | [99198fbcfa](https://linux-hardware.org/?probe=99198fbcfa) | May 08, 2019 |
| Pegatron      | 2AF0                        | Desktop     | [bebc187dbd](https://linux-hardware.org/?probe=bebc187dbd) | May 05, 2019 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [1ddb0e459f](https://linux-hardware.org/?probe=1ddb0e459f) | Apr 26, 2019 |
| Pegatron      | IPPEL-DB                    | Desktop     | [c73b25ed21](https://linux-hardware.org/?probe=c73b25ed21) | Apr 24, 2019 |
| Pegatron      | IPPEL-DB                    | Desktop     | [d1941d4619](https://linux-hardware.org/?probe=d1941d4619) | Apr 24, 2019 |
| Lenovo        | H220 10028                  | Desktop     | [9b6593e8c6](https://linux-hardware.org/?probe=9b6593e8c6) | Apr 21, 2019 |
| ASRock        | N68C-S UCC                  | Desktop     | [ac39e69311](https://linux-hardware.org/?probe=ac39e69311) | Apr 21, 2019 |
| ASRock        | H67M-GE                     | Desktop     | [282ee52768](https://linux-hardware.org/?probe=282ee52768) | Apr 19, 2019 |
| HP            | Pavilion dv4                | Notebook    | [e59414c439](https://linux-hardware.org/?probe=e59414c439) | Apr 11, 2019 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [e054fab57c](https://linux-hardware.org/?probe=e054fab57c) | Nov 24, 2018 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [d3d5ff2e54](https://linux-hardware.org/?probe=d3d5ff2e54) | Nov 24, 2018 |
| Intel         | powered classmate PC        | Notebook    | [405f76133d](https://linux-hardware.org/?probe=405f76133d) | Oct 11, 2017 |
| Intel         | powered classmate PC        | Notebook    | [e79ec0466f](https://linux-hardware.org/?probe=e79ec0466f) | Oct 01, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [8d884b92fa](https://linux-hardware.org/?probe=8d884b92fa) | Sep 16, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [17af4fce47](https://linux-hardware.org/?probe=17af4fce47) | Sep 03, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [c501aaa553](https://linux-hardware.org/?probe=c501aaa553) | Sep 01, 2017 |
| Lenovo        | 3000 N200 0769ARS           | Notebook    | [1ada6660c3](https://linux-hardware.org/?probe=1ada6660c3) | Aug 15, 2017 |
| Lenovo        | 3000 N200 0769ARS           | Notebook    | [5548cd964f](https://linux-hardware.org/?probe=5548cd964f) | Jul 28, 2017 |
| ASRock        | 945GCM-S                    | Desktop     | [009791bef2](https://linux-hardware.org/?probe=009791bef2) | Jun 25, 2017 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [270499b92c](https://linux-hardware.org/?probe=270499b92c) | Dec 29, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 19        | 8.96%   |
| Ubuntu 18.04                 | 17        | 8.02%   |
| Debian 11                    | 17        | 8.02%   |
| OpenMandriva 4.3             | 10        | 4.72%   |
| Debian 10                    | 10        | 4.72%   |
| OpenMandriva 4.2             | 9         | 4.25%   |
| KDE neon 20.04               | 7         | 3.3%    |
| Xubuntu 18.04                | 6         | 2.83%   |
| ROSA R9                      | 5         | 2.36%   |
| ROSA R11                     | 5         | 2.36%   |
| Linux Mint 20                | 5         | 2.36%   |
| Linux Mint 19.3              | 5         | 2.36%   |
| Kubuntu 20.04                | 5         | 2.36%   |
| Ubuntu MATE 19.10            | 4         | 1.89%   |
| Ubuntu 19.10                 | 4         | 1.89%   |
| Linux Mint 20.3              | 4         | 1.89%   |
| Fedora 35                    | 4         | 1.89%   |
| Zorin 15                     | 3         | 1.42%   |
| KDE neon 18.04               | 3         | 1.42%   |
| Arch Rolling                 | 3         | 1.42%   |
| Xubuntu 20.04                | 2         | 0.94%   |
| Xubuntu 16.04                | 2         | 0.94%   |
| Ubuntu 21.10                 | 2         | 0.94%   |
| Ubuntu 20.10                 | 2         | 0.94%   |
| Ubuntu 16.04                 | 2         | 0.94%   |
| Pop!_OS 21.04                | 2         | 0.94%   |
| OpenMandriva 4.50            | 2         | 0.94%   |
| Manjaro                      | 2         | 0.94%   |
| Linux Mint 20.1              | 2         | 0.94%   |
| Fedora 34                    | 2         | 0.94%   |
| Arch                         | 2         | 0.94%   |
| Zorin 16                     | 1         | 0.47%   |
| Xubuntu 21.10                | 1         | 0.47%   |
| Ubuntu MATE 20.04            | 1         | 0.47%   |
| Ubuntu 22.04                 | 1         | 0.47%   |
| Ubuntu 19.04                 | 1         | 0.47%   |
| Sparky 5.12                  | 1         | 0.47%   |
| Solus 4.3                    | 1         | 0.47%   |
| Solus 4.1                    | 1         | 0.47%   |
| ROSA R8                      | 1         | 0.47%   |
| ROSA R11.1                   | 1         | 0.47%   |
| ROSA 12.1                    | 1         | 0.47%   |
| Q4OS 4                       | 1         | 0.47%   |
| Pop!_OS 22.04                | 1         | 0.47%   |
| Pop!_OS 20.04                | 1         | 0.47%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.47%   |
| MX 20                        | 1         | 0.47%   |
| Manjaro 21.2.0               | 1         | 0.47%   |
| Manjaro 21.1.0               | 1         | 0.47%   |
| Manjaro 21.0                 | 1         | 0.47%   |
| Manjaro 20.2.1               | 1         | 0.47%   |
| Manjaro 20.1                 | 1         | 0.47%   |
| Lubuntu 18.04                | 1         | 0.47%   |
| LMDE 5                       | 1         | 0.47%   |
| LMDE 4                       | 1         | 0.47%   |
| Linux Mint 20.2              | 1         | 0.47%   |
| Linux Mint 19.2              | 1         | 0.47%   |
| Linux Mint 19                | 1         | 0.47%   |
| Kali 2021.4                  | 1         | 0.47%   |
| Garuda Linux Soaring         | 1         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 47        | 22.93%  |
| Debian       | 28        | 13.66%  |
| OpenMandriva | 21        | 10.24%  |
| Linux Mint   | 18        | 8.78%   |
| ROSA         | 13        | 6.34%   |
| Xubuntu      | 10        | 4.88%   |
| KDE neon     | 9         | 4.39%   |
| Fedora       | 8         | 3.9%    |
| Manjaro      | 7         | 3.41%   |
| Ubuntu MATE  | 5         | 2.44%   |
| Kubuntu      | 5         | 2.44%   |
| Arch         | 5         | 2.44%   |
| Zorin        | 4         | 1.95%   |
| Pop!_OS      | 4         | 1.95%   |
| Solus        | 2         | 0.98%   |
| LMDE         | 2         | 0.98%   |
| Garuda Linux | 2         | 0.98%   |
| Feren OS     | 2         | 0.98%   |
| Elementary   | 2         | 0.98%   |
| Sparky       | 1         | 0.49%   |
| Q4OS         | 1         | 0.49%   |
| openSUSE     | 1         | 0.49%   |
| MX           | 1         | 0.49%   |
| Lubuntu      | 1         | 0.49%   |
| Kali         | 1         | 0.49%   |
| Endless      | 1         | 0.49%   |
| Deepin       | 1         | 0.49%   |
| ArcoLinux    | 1         | 0.49%   |
| Alpine       | 1         | 0.49%   |
| AlmaLinux    | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                  | Computers | Percent |
|------------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003                  | 10        | 4.39%   |
| 5.10.14-desktop-1omv4002                 | 9         | 3.95%   |
| 5.4.0-42-generic                         | 8         | 3.51%   |
| 5.3.0-40-generic                         | 6         | 2.63%   |
| 5.4.0-77-generic                         | 4         | 1.75%   |
| 5.13.0-39-generic                        | 4         | 1.75%   |
| 5.10.0-13-amd64                          | 4         | 1.75%   |
| 5.10.0-11-amd64                          | 4         | 1.75%   |
| 5.0.0-37-generic                         | 4         | 1.75%   |
| 4.9.20-nrj-desktop-1rosa-x86_64          | 4         | 1.75%   |
| 4.19.0-17-amd64                          | 4         | 1.75%   |
| 5.4.0-73-generic                         | 3         | 1.32%   |
| 5.4.0-52-generic                         | 3         | 1.32%   |
| 5.3.0-29-generic                         | 3         | 1.32%   |
| 5.11.0-37-generic                        | 3         | 1.32%   |
| 4.15.0-48-generic                        | 3         | 1.32%   |
| 5.8.0-55-generic                         | 2         | 0.88%   |
| 5.8.0-44-generic                         | 2         | 0.88%   |
| 5.4.0-89-generic                         | 2         | 0.88%   |
| 5.4.0-74-generic                         | 2         | 0.88%   |
| 5.4.0-66-generic                         | 2         | 0.88%   |
| 5.4.0-54-generic                         | 2         | 0.88%   |
| 5.4.0-48-generic                         | 2         | 0.88%   |
| 5.4.0-31-generic                         | 2         | 0.88%   |
| 5.4.0-26-generic                         | 2         | 0.88%   |
| 5.3.0-42-generic                         | 2         | 0.88%   |
| 5.14.10-300.fc35.x86_64                  | 2         | 0.88%   |
| 5.13.0-27-generic                        | 2         | 0.88%   |
| 5.12.4-desktop-1omv4050                  | 2         | 0.88%   |
| 5.10.0-8-amd64                           | 2         | 0.88%   |
| 5.10.0-14-amd64                          | 2         | 0.88%   |
| 5.10.0-12-amd64                          | 2         | 0.88%   |
| 4.15.0-desktop-45.1rosa-x86_64           | 2         | 0.88%   |
| 4.15.0-96-generic                        | 2         | 0.88%   |
| 4.15.0-112-generic                       | 2         | 0.88%   |
| 5.9.16-1-MANJARO                         | 1         | 0.44%   |
| 5.9.0-5-amd64                            | 1         | 0.44%   |
| 5.8.6-1-MANJARO                          | 1         | 0.44%   |
| 5.8.11-arch1-1                           | 1         | 0.44%   |
| 5.8.10-17-tkg-bmq                        | 1         | 0.44%   |
| 5.8.0-63-generic                         | 1         | 0.44%   |
| 5.8.0-59-generic                         | 1         | 0.44%   |
| 5.8.0-53-generic                         | 1         | 0.44%   |
| 5.8.0-45-generic                         | 1         | 0.44%   |
| 5.8.0-41-generic                         | 1         | 0.44%   |
| 5.8.0-40-generic                         | 1         | 0.44%   |
| 5.7.0-1.vanilla.1.fc31.x86_64            | 1         | 0.44%   |
| 5.6.6-1-default                          | 1         | 0.44%   |
| 5.6.18-155.current                       | 1         | 0.44%   |
| 5.6.0-1-amd64                            | 1         | 0.44%   |
| 5.5.4-linux-xanmod-1-rosa-x86_64-xanmod3 | 1         | 0.44%   |
| 5.4.83-0-lts                             | 1         | 0.44%   |
| 5.4.105-1-MANJARO                        | 1         | 0.44%   |
| 5.4.0-96-generic                         | 1         | 0.44%   |
| 5.4.0-91-generic                         | 1         | 0.44%   |
| 5.4.0-88-generic                         | 1         | 0.44%   |
| 5.4.0-86-generic                         | 1         | 0.44%   |
| 5.4.0-7634-generic                       | 1         | 0.44%   |
| 5.4.0-72-generic                         | 1         | 0.44%   |
| 5.4.0-70-generic                         | 1         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 43        | 20.19%  |
| 4.15.0  | 23        | 10.8%   |
| 5.10.0  | 16        | 7.51%   |
| 5.3.0   | 12        | 5.63%   |
| 5.13.0  | 12        | 5.63%   |
| 4.19.0  | 12        | 5.63%   |
| 5.16.7  | 10        | 4.69%   |
| 5.8.0   | 9         | 4.23%   |
| 5.10.14 | 9         | 4.23%   |
| 5.11.0  | 8         | 3.76%   |
| 5.0.0   | 7         | 3.29%   |
| 4.9.20  | 5         | 2.35%   |
| 5.14.10 | 3         | 1.41%   |
| 5.15.6  | 2         | 0.94%   |
| 5.15.0  | 2         | 0.94%   |
| 5.12.4  | 2         | 0.94%   |
| 4.9.0   | 2         | 0.94%   |
| 4.18.0  | 2         | 0.94%   |
| 5.9.16  | 1         | 0.47%   |
| 5.9.0   | 1         | 0.47%   |
| 5.8.6   | 1         | 0.47%   |
| 5.8.11  | 1         | 0.47%   |
| 5.8.10  | 1         | 0.47%   |
| 5.7.0   | 1         | 0.47%   |
| 5.6.6   | 1         | 0.47%   |
| 5.6.18  | 1         | 0.47%   |
| 5.6.0   | 1         | 0.47%   |
| 5.5.4   | 1         | 0.47%   |
| 5.4.83  | 1         | 0.47%   |
| 5.4.105 | 1         | 0.47%   |
| 5.17.2  | 1         | 0.47%   |
| 5.17.11 | 1         | 0.47%   |
| 5.16.16 | 1         | 0.47%   |
| 5.16.14 | 1         | 0.47%   |
| 5.15.8  | 1         | 0.47%   |
| 5.15.28 | 1         | 0.47%   |
| 5.15.2  | 1         | 0.47%   |
| 5.15.19 | 1         | 0.47%   |
| 5.15.13 | 1         | 0.47%   |
| 5.15.10 | 1         | 0.47%   |
| 5.13.16 | 1         | 0.47%   |
| 5.13.13 | 1         | 0.47%   |
| 5.13.1  | 1         | 0.47%   |
| 5.12.19 | 1         | 0.47%   |
| 5.10.74 | 1         | 0.47%   |
| 5.10.5  | 1         | 0.47%   |
| 5.10.3  | 1         | 0.47%   |
| 5.10.11 | 1         | 0.47%   |
| 5.10.10 | 1         | 0.47%   |
| 4.4.0   | 1         | 0.47%   |
| 4.13.0  | 1         | 0.47%   |
| 4.1.15  | 1         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 45        | 21.23%  |
| 5.10    | 30        | 14.15%  |
| 4.15    | 23        | 10.85%  |
| 5.13    | 15        | 7.08%   |
| 5.8     | 12        | 5.66%   |
| 5.3     | 12        | 5.66%   |
| 5.16    | 12        | 5.66%   |
| 4.19    | 12        | 5.66%   |
| 5.15    | 9         | 4.25%   |
| 5.11    | 8         | 3.77%   |
| 5.0     | 7         | 3.3%    |
| 4.9     | 7         | 3.3%    |
| 5.6     | 3         | 1.42%   |
| 5.14    | 3         | 1.42%   |
| 5.12    | 3         | 1.42%   |
| 5.9     | 2         | 0.94%   |
| 5.17    | 2         | 0.94%   |
| 4.18    | 2         | 0.94%   |
| 5.7     | 1         | 0.47%   |
| 5.5     | 1         | 0.47%   |
| 4.4     | 1         | 0.47%   |
| 4.13    | 1         | 0.47%   |
| 4.1     | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 176       | 88%     |
| i686   | 24        | 12%     |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 56        | 26.54%  |
| KDE5            | 46        | 21.8%   |
| XFCE            | 29        | 13.74%  |
| Unknown         | 22        | 10.43%  |
| KDE             | 12        | 5.69%   |
| MATE            | 11        | 5.21%   |
| X-Cinnamon      | 8         | 3.79%   |
| KDE4            | 7         | 3.32%   |
| Cinnamon        | 4         | 1.9%    |
| Unity           | 3         | 1.42%   |
| LXDE            | 3         | 1.42%   |
| LXQt            | 2         | 0.95%   |
| GNOME Classic   | 2         | 0.95%   |
| Budgie          | 2         | 0.95%   |
| xmonad          | 1         | 0.47%   |
| Pantheon        | 1         | 0.47%   |
| GNOME Flashback | 1         | 0.47%   |
| Deepin          | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 176       | 88.44%  |
| Wayland | 17        | 8.54%   |
| Unknown | 5         | 2.51%   |
| Tty     | 1         | 0.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 92        | 44.66%  |
| SDDM    | 43        | 20.87%  |
| GDM     | 24        | 11.65%  |
| LightDM | 22        | 10.68%  |
| TDM     | 10        | 4.85%   |
| KDM     | 7         | 3.4%    |
| GDM3    | 7         | 3.4%    |
| SLiM    | 1         | 0.49%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_VE   | 117       | 57.35%  |
| en_US   | 48        | 23.53%  |
| Unknown | 24        | 11.76%  |
| es_ES   | 10        | 4.9%    |
| es_US   | 2         | 0.98%   |
| C       | 2         | 0.98%   |
| en_CA   | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 156       | 78%     |
| EFI  | 44        | 22%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 156       | 77.61%  |
| Overlay | 20        | 9.95%   |
| Btrfs   | 11        | 5.47%   |
| Unknown | 8         | 3.98%   |
| Xfs     | 4         | 1.99%   |
| Ext2    | 2         | 1%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 108       | 53.2%   |
| MBR     | 56        | 27.59%  |
| GPT     | 39        | 19.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 171       | 84.65%  |
| Yes       | 31        | 15.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 122       | 61%     |
| Yes       | 78        | 39%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 26        | 13.13%  |
| Dell                | 21        | 10.61%  |
| Intel               | 20        | 10.1%   |
| VIT                 | 17        | 8.59%   |
| ASRock              | 17        | 8.59%   |
| Hewlett-Packard     | 16        | 8.08%   |
| ASUSTek Computer    | 12        | 6.06%   |
| ECS                 | 11        | 5.56%   |
| Pegatron            | 10        | 5.05%   |
| Biostar             | 6         | 3.03%   |
| Gigabyte Technology | 5         | 2.53%   |
| Unknown             | 5         | 2.53%   |
| MSI                 | 4         | 2.02%   |
| Foxconn             | 4         | 2.02%   |
| Acer                | 4         | 2.02%   |
| langchao            | 3         | 1.52%   |
| Apple               | 3         | 1.52%   |
| UNIQCELL            | 1         | 0.51%   |
| Toshiba             | 1         | 0.51%   |
| Standard            | 1         | 0.51%   |
| Sony                | 1         | 0.51%   |
| Samsung Electronics | 1         | 0.51%   |
| IP3 Tech            | 1         | 0.51%   |
| Inspur              | 1         | 0.51%   |
| IBM                 | 1         | 0.51%   |
| GPU Company         | 1         | 0.51%   |
| Gateway             | 1         | 0.51%   |
| Exo                 | 1         | 0.51%   |
| Clevo               | 1         | 0.51%   |
| AVITA               | 1         | 0.51%   |
| Alienware           | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel powered classmate PC           | 9         | 4.55%   |
| ECS H61H2-CM                         | 6         | 3.03%   |
| VIT P2400                            | 5         | 2.53%   |
| Unknown                              | 5         | 2.53%   |
| ASRock G41M-VS3                      | 4         | 2.02%   |
| VIT P3400                            | 3         | 1.52%   |
| langchao 12345                       | 3         | 1.52%   |
| VIT P2402                            | 2         | 1.01%   |
| VIT M2421                            | 2         | 1.01%   |
| VIT M2420                            | 2         | 1.01%   |
| Pegatron Compaq dx2400 Microtower    | 2         | 1.01%   |
| Lenovo IdeaPad S100c 20194           | 2         | 1.01%   |
| Lenovo 3000 N200 0769ARS             | 2         | 1.01%   |
| Dell Inspiron 1545                   | 2         | 1.01%   |
| ASRock N68C-S UCC                    | 2         | 1.01%   |
| Apple iMac11,2                       | 2         | 1.01%   |
| VIT P1400                            | 1         | 0.51%   |
| VIT NP3020M3                         | 1         | 0.51%   |
| VIT Aptio CRB                        | 1         | 0.51%   |
| UNIQCELL Q15.6                       | 1         | 0.51%   |
| Toshiba Satellite E55t-A             | 1         | 0.51%   |
| Standard AIO                         | 1         | 0.51%   |
| Sony VGN-FW510F                      | 1         | 0.51%   |
| Samsung 355V4C/356V4C/3445VC/3545VC  | 1         | 0.51%   |
| Pegatron T14AF                       | 1         | 0.51%   |
| Pegatron IPPEL-DB                    | 1         | 0.51%   |
| Pegatron IPM41-D3                    | 1         | 0.51%   |
| Pegatron CQ1507LA                    | 1         | 0.51%   |
| Pegatron Compaq dx2400 Microtower PC | 1         | 0.51%   |
| Pegatron BM411AA-ABA CQ5600F         | 1         | 0.51%   |
| Pegatron 20-b010                     | 1         | 0.51%   |
| Pegatron 100-5010la                  | 1         | 0.51%   |
| MSI Pro 3000 Microtower PC           | 1         | 0.51%   |
| MSI MS-7721                          | 1         | 0.51%   |
| MSI MS-7375                          | 1         | 0.51%   |
| MSI MS-1454                          | 1         | 0.51%   |
| Lenovo Z50-75 80EC                   | 1         | 0.51%   |
| Lenovo ThinkPad X201 3680AE2         | 1         | 0.51%   |
| Lenovo ThinkPad SL400 2743A48        | 1         | 0.51%   |
| Lenovo ThinkPad Edge 01962AS         | 1         | 0.51%   |
| Lenovo ThinkPad E560 20EV002FUS      | 1         | 0.51%   |
| Lenovo ThinkCentre XXXX 8705A84      | 1         | 0.51%   |
| Lenovo ThinkCentre M71e 3157G6S      | 1         | 0.51%   |
| Lenovo ThinkCentre M55E 9645BN2      | 1         | 0.51%   |
| Lenovo ThinkCentre M55E 9632BU8      | 1         | 0.51%   |
| Lenovo ThinkCentre A58 7515A33       | 1         | 0.51%   |
| Lenovo ThinkCentre A55 8705AV4       | 1         | 0.51%   |
| Lenovo IdeaPad S110 20126            | 1         | 0.51%   |
| Lenovo IdeaPad 5 14ALC05 82LM        | 1         | 0.51%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 0.51%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 1         | 0.51%   |
| Lenovo H220 10028                    | 1         | 0.51%   |
| Lenovo G570 4334                     | 1         | 0.51%   |
| Lenovo G480 20150                    | 1         | 0.51%   |
| Lenovo G460 20041                    | 1         | 0.51%   |
| Lenovo B40-70 20392                  | 1         | 0.51%   |
| Lenovo 70A4000HUX ThinkServer TS140  | 1         | 0.51%   |
| Lenovo 11051CS ThinkServer TS130     | 1         | 0.51%   |
| IP3 Tech TB20                        | 1         | 0.51%   |
| Intel S5500BC                        | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 10        | 5.05%   |
| Intel powered        | 9         | 4.55%   |
| Lenovo ThinkCentre   | 6         | 3.03%   |
| Lenovo IdeaPad       | 6         | 3.03%   |
| HP Pavilion          | 6         | 3.03%   |
| ECS H61H2-CM         | 6         | 3.03%   |
| VIT P2400            | 5         | 2.53%   |
| HP Compaq            | 5         | 2.53%   |
| Unknown              | 5         | 2.53%   |
| Lenovo ThinkPad      | 4         | 2.02%   |
| Dell Vostro          | 4         | 2.02%   |
| ASRock G41M-VS3      | 4         | 2.02%   |
| VIT P3400            | 3         | 1.52%   |
| Pegatron Compaq      | 3         | 1.52%   |
| langchao 12345       | 3         | 1.52%   |
| Dell Latitude        | 3         | 1.52%   |
| Acer Aspire          | 3         | 1.52%   |
| VIT P2402            | 2         | 1.01%   |
| VIT M2421            | 2         | 1.01%   |
| VIT M2420            | 2         | 1.01%   |
| Lenovo 3000          | 2         | 1.01%   |
| HP Presario          | 2         | 1.01%   |
| Dell Precision       | 2         | 1.01%   |
| ASRock N68C-S        | 2         | 1.01%   |
| Apple iMac11         | 2         | 1.01%   |
| VIT P1400            | 1         | 0.51%   |
| VIT NP3020M3         | 1         | 0.51%   |
| VIT Aptio            | 1         | 0.51%   |
| UNIQCELL Q15.6       | 1         | 0.51%   |
| Toshiba Satellite    | 1         | 0.51%   |
| Standard AIO         | 1         | 0.51%   |
| Sony VGN-FW510F      | 1         | 0.51%   |
| Samsung 355V4C       | 1         | 0.51%   |
| Pegatron T14AF       | 1         | 0.51%   |
| Pegatron IPPEL-DB    | 1         | 0.51%   |
| Pegatron IPM41-D3    | 1         | 0.51%   |
| Pegatron CQ1507LA    | 1         | 0.51%   |
| Pegatron BM411AA-ABA | 1         | 0.51%   |
| Pegatron 20-b010     | 1         | 0.51%   |
| Pegatron 100-5010la  | 1         | 0.51%   |
| MSI Pro              | 1         | 0.51%   |
| MSI MS-7721          | 1         | 0.51%   |
| MSI MS-7375          | 1         | 0.51%   |
| MSI MS-1454          | 1         | 0.51%   |
| Lenovo Z50-75        | 1         | 0.51%   |
| Lenovo H220          | 1         | 0.51%   |
| Lenovo G570          | 1         | 0.51%   |
| Lenovo G480          | 1         | 0.51%   |
| Lenovo G460          | 1         | 0.51%   |
| Lenovo B40-70        | 1         | 0.51%   |
| Lenovo 70A4000HUX    | 1         | 0.51%   |
| Lenovo 11051CS       | 1         | 0.51%   |
| IP3 Tech TB20        | 1         | 0.51%   |
| Intel S5500BC        | 1         | 0.51%   |
| Intel MAHOBAY        | 1         | 0.51%   |
| Intel H61            | 1         | 0.51%   |
| Intel DH77EB         | 1         | 0.51%   |
| Intel DG41TY         | 1         | 0.51%   |
| Intel DG41TX         | 1         | 0.51%   |
| Intel DG35EC         | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 34        | 17.17%  |
| 2011    | 33        | 16.67%  |
| 2012    | 21        | 10.61%  |
| 2008    | 19        | 9.6%    |
| 2007    | 18        | 9.09%   |
| 2013    | 14        | 7.07%   |
| 2014    | 12        | 6.06%   |
| 2006    | 7         | 3.54%   |
| 2021    | 6         | 3.03%   |
| 2017    | 6         | 3.03%   |
| 2020    | 5         | 2.53%   |
| 2018    | 5         | 2.53%   |
| 2015    | 5         | 2.53%   |
| 2009    | 5         | 2.53%   |
| 2019    | 3         | 1.52%   |
| 2016    | 3         | 1.52%   |
| 2005    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 96        | 48.48%  |
| Notebook   | 90        | 45.45%  |
| All in one | 5         | 2.53%   |
| Tablet     | 4         | 2.02%   |
| Server     | 2         | 1.01%   |
| Mini pc    | 1         | 0.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 194       | 97.98%  |
| Enabled  | 4         | 2.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 198       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 52        | 25.74%  |
| 4.01-8.0   | 45        | 22.28%  |
| 1.01-2.0   | 44        | 21.78%  |
| 8.01-16.0  | 28        | 13.86%  |
| 16.01-24.0 | 16        | 7.92%   |
| 2.01-3.0   | 9         | 4.46%   |
| 24.01-32.0 | 3         | 1.49%   |
| 0.51-1.0   | 3         | 1.49%   |
| 32.01-64.0 | 2         | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 90        | 41.28%  |
| 2.01-3.0   | 50        | 22.94%  |
| 0.51-1.0   | 35        | 16.06%  |
| 4.01-8.0   | 23        | 10.55%  |
| 3.01-4.0   | 15        | 6.88%   |
| 0.01-0.5   | 3         | 1.38%   |
| 16.01-24.0 | 1         | 0.46%   |
| 8.01-16.0  | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 129       | 63.86%  |
| 2      | 58        | 28.71%  |
| 3      | 13        | 6.44%   |
| 6      | 1         | 0.5%    |
| 4      | 1         | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 50%     |
| No        | 101       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 190       | 95.48%  |
| No        | 9         | 4.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 73%     |
| No        | 54        | 27%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 140       | 70%     |
| Yes       | 60        | 30%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Venezuela | 198       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 96        | 45.28%  |
| Maracaibo                  | 15        | 7.08%   |
| Maracay                    | 11        | 5.19%   |
| Mérida                    | 8         | 3.77%   |
| San Cristóbal             | 7         | 3.3%    |
| Valencia                   | 6         | 2.83%   |
| Barquisimeto               | 6         | 2.83%   |
| Barcelona                  | 6         | 2.83%   |
| San Carlos del Zulia       | 5         | 2.36%   |
| Maturín                   | 5         | 2.36%   |
| Barinas                    | 4         | 1.89%   |
| Parroquia El Recreo        | 3         | 1.42%   |
| Lecherias                  | 3         | 1.42%   |
| Ciudad Bolívar            | 3         | 1.42%   |
| Carrizal                   | 3         | 1.42%   |
| San Juan Bautista          | 2         | 0.94%   |
| San Antonio de Los Altos   | 2         | 0.94%   |
| Los Teques                 | 2         | 0.94%   |
| Los Palos Grandes          | 2         | 0.94%   |
| Guatire                    | 2         | 0.94%   |
| Guarenas                   | 2         | 0.94%   |
| Ciudad Guayana             | 2         | 0.94%   |
| Valle de La Pascua         | 1         | 0.47%   |
| San Francisco              | 1         | 0.47%   |
| San Diego                  | 1         | 0.47%   |
| Puerto Ordaz and San Felix | 1         | 0.47%   |
| Puerto Cumarebo            | 1         | 0.47%   |
| Puerto Cruz                | 1         | 0.47%   |
| Porlamar                   | 1         | 0.47%   |
| Mariara                    | 1         | 0.47%   |
| Las Vegas                  | 1         | 0.47%   |
| Guanare                    | 1         | 0.47%   |
| El Hatillo Municipality    | 1         | 0.47%   |
| Cua                        | 1         | 0.47%   |
| Charallave                 | 1         | 0.47%   |
| Carora                     | 1         | 0.47%   |
| Cagua                      | 1         | 0.47%   |
| Cabimas                    | 1         | 0.47%   |
| Baruta                     | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 67        | 92     | 27.02%  |
| Seagate             | 62        | 93     | 25%     |
| Hitachi             | 25        | 38     | 10.08%  |
| Toshiba             | 20        | 21     | 8.06%   |
| Samsung Electronics | 20        | 23     | 8.06%   |
| Kingston            | 9         | 10     | 3.63%   |
| MAXTOR              | 4         | 4      | 1.61%   |
| LITEONIT            | 4         | 6      | 1.61%   |
| Crucial             | 4         | 5      | 1.61%   |
| Unknown             | 3         | 3      | 1.21%   |
| SPCC                | 3         | 4      | 1.21%   |
| SanDisk             | 3         | 3      | 1.21%   |
| Intel               | 3         | 4      | 1.21%   |
| HGST                | 3         | 3      | 1.21%   |
| Fujitsu             | 3         | 3      | 1.21%   |
| SK Hynix            | 2         | 2      | 0.81%   |
| PNY                 | 2         | 2      | 0.81%   |
| Vaseky              | 1         | 1      | 0.4%    |
| Team                | 1         | 1      | 0.4%    |
| Silicon Motion      | 1         | 1      | 0.4%    |
| Patriot             | 1         | 1      | 0.4%    |
| Micron Technology   | 1         | 3      | 0.4%    |
| KingFast            | 1         | 1      | 0.4%    |
| Intenso             | 1         | 1      | 0.4%    |
| ExcelStor           | 1         | 1      | 0.4%    |
| Dell                | 1         | 1      | 0.4%    |
| BIWIN               | 1         | 2      | 0.4%    |
| Apacer              | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 10        | 3.68%   |
| Toshiba DT01ACA050 500GB            | 6         | 2.21%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 4         | 1.47%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 1.47%   |
| Seagate ST320LM000 HM321HI 320GB    | 4         | 1.47%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 1.1%    |
| WDC WD5000AAKX-22ERMA0 500GB        | 3         | 1.1%    |
| WDC WD5000AAKS-00A7B0 500GB         | 3         | 1.1%    |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 1.1%    |
| WDC WD3200AAJS-08L7A0 320GB         | 3         | 1.1%    |
| WDC WD3200AAJS-00L7A0 320GB         | 3         | 1.1%    |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 1.1%    |
| Seagate ST500DM002-1BD142 500GB     | 3         | 1.1%    |
| Seagate ST3320418AS 320GB           | 3         | 1.1%    |
| Seagate ST250LM004 HN-M250MBB 250GB | 3         | 1.1%    |
| Samsung HD502HJ 500GB               | 3         | 1.1%    |
| Samsung HD161HJ 160GB               | 3         | 1.1%    |
| LITEONIT LMS-32L6M 32GB SSD         | 3         | 1.1%    |
| Kingston SA400S37240G 240GB SSD     | 3         | 1.1%    |
| Hitachi HTS542580K9SA00 80GB        | 3         | 1.1%    |
| WDC WD800BD-22MRA1 80GB             | 2         | 0.74%   |
| WDC WD800BB-22JHC0 80GB             | 2         | 0.74%   |
| WDC WD5000LPVT-08G33T1 500GB        | 2         | 0.74%   |
| WDC WD5000AAKX-221CA1 500GB         | 2         | 0.74%   |
| WDC WD5000AAKX-001CA0 500GB         | 2         | 0.74%   |
| WDC WD2500AAJS-60B4A0 250GB         | 2         | 0.74%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.74%   |
| Toshiba MQ01ABF032 320GB            | 2         | 0.74%   |
| SPCC Solid State Disk 128GB         | 2         | 0.74%   |
| SK Hynix SC300B SATA 512GB SSD      | 2         | 0.74%   |
| Seagate ST9160314AS 160GB           | 2         | 0.74%   |
| Seagate ST3250310AS 250GB           | 2         | 0.74%   |
| Seagate ST320LT012-9WS14C 320GB     | 2         | 0.74%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 2         | 0.74%   |
| Seagate ST2000DM001-1CH164 2TB      | 2         | 0.74%   |
| Seagate ST1000NM0011 1TB            | 2         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.74%   |
| Samsung HN-M320MBB 320GB            | 2         | 0.74%   |
| Samsung HM321HI 320GB               | 2         | 0.74%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 0.74%   |
| Hitachi HDS721616PLA380 164GB       | 2         | 0.74%   |
| Hitachi HDS721032CLA362 320GB       | 2         | 0.74%   |
| HGST HTS721010A9E630 1TB            | 2         | 0.74%   |
| WDC WDS500G2B0C-00PXH0 500GB        | 1         | 0.37%   |
| WDC WD800JD-60LSA5 80GB             | 1         | 0.37%   |
| WDC WD800BD-08MRA1 80GB             | 1         | 0.37%   |
| WDC WD5000LPCX-22VHAT0 500GB        | 1         | 0.37%   |
| WDC WD5000BPVT-24HXZT3 500GB        | 1         | 0.37%   |
| WDC WD5000AVCS-632DY1 500GB         | 1         | 0.37%   |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 0.37%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 1         | 0.37%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 0.37%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1         | 0.37%   |
| WDC WD5000AAJS-08A8B0 500GB         | 1         | 0.37%   |
| WDC WD5000AACS-61M6B2 500GB         | 1         | 0.37%   |
| WDC WD5000AACS-00ZUB0 500GB         | 1         | 0.37%   |
| WDC WD50 00BPVT-24HXZT1 500GB       | 1         | 0.37%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 0.37%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 1         | 0.37%   |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 66        | 91     | 33.67%  |
| Seagate             | 60        | 91     | 30.61%  |
| Hitachi             | 25        | 38     | 12.76%  |
| Toshiba             | 19        | 20     | 9.69%   |
| Samsung Electronics | 15        | 18     | 7.65%   |
| MAXTOR              | 4         | 4      | 2.04%   |
| HGST                | 3         | 3      | 1.53%   |
| Fujitsu             | 3         | 3      | 1.53%   |
| ExcelStor           | 1         | 1      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 8         | 9      | 21.62%  |
| LITEONIT            | 4         | 6      | 10.81%  |
| Crucial             | 4         | 5      | 10.81%  |
| SPCC                | 3         | 4      | 8.11%   |
| Samsung Electronics | 3         | 3      | 8.11%   |
| SK Hynix            | 2         | 2      | 5.41%   |
| SanDisk             | 2         | 2      | 5.41%   |
| PNY                 | 2         | 2      | 5.41%   |
| Vaseky              | 1         | 1      | 2.7%    |
| Toshiba             | 1         | 1      | 2.7%    |
| Team                | 1         | 1      | 2.7%    |
| Patriot             | 1         | 1      | 2.7%    |
| Micron Technology   | 1         | 3      | 2.7%    |
| KingFast            | 1         | 1      | 2.7%    |
| Intenso             | 1         | 1      | 2.7%    |
| Dell                | 1         | 1      | 2.7%    |
| BIWIN               | 1         | 2      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 161       | 269    | 75.94%  |
| SSD     | 36        | 45     | 16.98%  |
| NVMe    | 11        | 12     | 5.19%   |
| MMC     | 2         | 2      | 0.94%   |
| Unknown | 2         | 2      | 0.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 187       | 313    | 92.12%  |
| NVMe | 11        | 12     | 5.42%   |
| SAS  | 3         | 3      | 1.48%   |
| MMC  | 2         | 2      | 0.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 174       | 250    | 82.46%  |
| 0.51-1.0   | 26        | 45     | 12.32%  |
| 1.01-2.0   | 7         | 14     | 3.32%   |
| 3.01-4.0   | 2         | 2      | 0.95%   |
| 2.01-3.0   | 2         | 3      | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 69        | 33.01%  |
| 101-250        | 53        | 25.36%  |
| 501-1000       | 26        | 12.44%  |
| 1-20           | 18        | 8.61%   |
| 51-100         | 18        | 8.61%   |
| 21-50          | 11        | 5.26%   |
| 1001-2000      | 7         | 3.35%   |
| 2001-3000      | 3         | 1.44%   |
| More than 3000 | 2         | 0.96%   |
| Unknown        | 2         | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 86        | 40.38%  |
| 21-50          | 37        | 17.37%  |
| 101-250        | 28        | 13.15%  |
| 51-100         | 25        | 11.74%  |
| 251-500        | 19        | 8.92%   |
| 501-1000       | 10        | 4.69%   |
| More than 3000 | 2         | 0.94%   |
| 2001-3000      | 2         | 0.94%   |
| 1001-2000      | 2         | 0.94%   |
| Unknown        | 2         | 0.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB         | 3         | 3      | 5.08%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 2         | 3      | 3.39%   |
| WDC WD5000AAKS-00A7B0 500GB             | 2         | 2      | 3.39%   |
| Seagate ST500DM002-1BD142 500GB         | 2         | 2      | 3.39%   |
| Samsung Electronics HM321HI 320GB       | 2         | 2      | 3.39%   |
| Hitachi HDS721616PLA380 164GB           | 2         | 2      | 3.39%   |
| WDC WD800BD-08MRA1 80GB                 | 1         | 1      | 1.69%   |
| WDC WD800BB-22JHC0 80GB                 | 1         | 1      | 1.69%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 1      | 1.69%   |
| WDC WD5000BPVT-24HXZT3 500GB            | 1         | 1      | 1.69%   |
| WDC WD5000AAKX-221CA1 500GB             | 1         | 1      | 1.69%   |
| WDC WD5000AAKX-08U6AA0 500GB            | 1         | 1      | 1.69%   |
| WDC WD5000AACS-00ZUB0 500GB             | 1         | 1      | 1.69%   |
| WDC WD50 00BPVT-24HXZT1 500GB           | 1         | 1      | 1.69%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 1      | 1.69%   |
| WDC WD3200BEKT-22F3T0 320GB             | 1         | 1      | 1.69%   |
| WDC WD3200AAJS-08L7A0 320GB             | 1         | 2      | 1.69%   |
| WDC WD2003FYPS-27Y2B0 2TB               | 1         | 1      | 1.69%   |
| WDC WD1200BEVS-60UST0 120GB             | 1         | 1      | 1.69%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 2      | 1.69%   |
| WDC WD10EZEX-22RKKA0 1TB                | 1         | 1      | 1.69%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 1         | 1      | 1.69%   |
| Toshiba MQ01ACF050 500GB                | 1         | 1      | 1.69%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 1.69%   |
| Toshiba DT01ACA050 500GB                | 1         | 2      | 1.69%   |
| Seagate ST9500325AS 500GB               | 1         | 1      | 1.69%   |
| Seagate ST9160314AS 160GB               | 1         | 1      | 1.69%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1      | 1.69%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1      | 1.69%   |
| Seagate ST3500630AS 500GB               | 1         | 1      | 1.69%   |
| Seagate ST3500413AS 500GB               | 1         | 1      | 1.69%   |
| Seagate ST340014AS 40GB                 | 1         | 1      | 1.69%   |
| Seagate ST3320418AS 320GB               | 1         | 2      | 1.69%   |
| Seagate ST3250318AS 250GB               | 1         | 1      | 1.69%   |
| Seagate ST3250310AS 250GB               | 1         | 1      | 1.69%   |
| Seagate ST3160215ACE 160GB              | 1         | 1      | 1.69%   |
| Seagate ST3160212SCE 160GB              | 1         | 1      | 1.69%   |
| Samsung Electronics HN-M320MBB 320GB    | 1         | 1      | 1.69%   |
| Samsung Electronics HM250HI 250GB       | 1         | 1      | 1.69%   |
| Samsung Electronics HD161HJ 160GB       | 1         | 2      | 1.69%   |
| Samsung Electronics HD155UI 1TB         | 1         | 1      | 1.69%   |
| MAXTOR STM3250310AS 250GB               | 1         | 1      | 1.69%   |
| MAXTOR STM3160215AS 160GB               | 1         | 1      | 1.69%   |
| Intel SSDPEKKW256G7 256GB               | 1         | 1      | 1.69%   |
| Hitachi HTS543232L9A300 320GB           | 1         | 1      | 1.69%   |
| Hitachi HTS543225L9SA00 250GB           | 1         | 1      | 1.69%   |
| Hitachi HTS542525K9SA00 250GB           | 1         | 1      | 1.69%   |
| Hitachi HDS728080PLA380 40Y9028LEN 80GB | 1         | 1      | 1.69%   |
| Hitachi HDS721050DLE630 500GB           | 1         | 1      | 1.69%   |
| Hitachi HDS721032CLA362 320GB           | 1         | 1      | 1.69%   |
| Hitachi HDP725025GLA380 250GB           | 1         | 1      | 1.69%   |
| ExcelStor Technology J880S 82GB         | 1         | 1      | 1.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 30.19%  |
| WDC                 | 15        | 23     | 28.3%   |
| Hitachi             | 9         | 9      | 16.98%  |
| Samsung Electronics | 6         | 7      | 11.32%  |
| Toshiba             | 3         | 4      | 5.66%   |
| MAXTOR              | 2         | 2      | 3.77%   |
| Intel               | 1         | 1      | 1.89%   |
| ExcelStor           | 1         | 1      | 1.89%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 30.77%  |
| WDC                 | 15        | 23     | 28.85%  |
| Hitachi             | 9         | 9      | 17.31%  |
| Samsung Electronics | 6         | 7      | 11.54%  |
| Toshiba             | 3         | 4      | 5.77%   |
| MAXTOR              | 2         | 2      | 3.85%   |
| ExcelStor           | 1         | 1      | 1.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 64     | 97.78%  |
| NVMe | 1         | 1      | 2.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba DT01ACA050 500GB | 2         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 110       | 191    | 51.16%  |
| Works    | 58        | 72     | 26.98%  |
| Malfunc  | 45        | 65     | 20.93%  |
| Failed   | 2         | 2      | 0.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 163       | 75.46%  |
| AMD                         | 20        | 9.26%   |
| Nvidia                      | 10        | 4.63%   |
| Marvell Technology Group    | 5         | 2.31%   |
| JMicron Technology          | 5         | 2.31%   |
| VIA Technologies            | 3         | 1.39%   |
| Sandisk                     | 2         | 0.93%   |
| Samsung Electronics         | 2         | 0.93%   |
| Silicon Motion              | 1         | 0.46%   |
| Phison Electronics          | 1         | 0.46%   |
| Kingston Technology Company | 1         | 0.46%   |
| ASMedia Technology          | 1         | 0.46%   |
| Adaptec                     | 1         | 0.46%   |
| Unknown                     | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 29        | 9.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 21        | 7.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 15        | 5.15%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 13        | 4.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11        | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11        | 3.78%   |
| Nvidia MCP61 SATA Controller                                                            | 9         | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 3.09%   |
| Nvidia MCP61 IDE                                                                        | 8         | 2.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7         | 2.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 7         | 2.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6         | 2.06%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6         | 2.06%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6         | 2.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 6         | 2.06%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5         | 1.72%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5         | 1.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 5         | 1.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 1.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 5         | 1.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 4         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.37%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 1.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.03%   |
| VIA Serial ATA Controller                                                               | 2         | 0.69%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.69%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.69%   |
| JMicron JMB362 SATA Controller                                                          | 2         | 0.69%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 0.69%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.69%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 0.69%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2         | 0.69%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2         | 0.69%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 2         | 0.69%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2         | 0.69%   |
| AMD FCH IDE Controller                                                                  | 2         | 0.69%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1         | 0.34%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.34%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.34%   |
| Sandisk Non-Volatile memory controller                                                  | 1         | 0.34%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.34%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1         | 0.34%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1         | 0.34%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1         | 0.34%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1         | 0.34%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1         | 0.34%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1         | 0.34%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1         | 0.34%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 0.34%   |
| JMicron JMB368 IDE controller                                                           | 1         | 0.34%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1         | 0.34%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1         | 0.34%   |
| Intel SSD 600P Series                                                                   | 1         | 0.34%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 0.34%   |
| Intel Non-Volatile memory controller                                                    | 1         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 115       | 51.8%   |
| IDE  | 83        | 37.39%  |
| RAID | 11        | 4.95%   |
| NVMe | 11        | 4.95%   |
| SAS  | 1         | 0.45%   |
| SCSI | 1         | 0.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 167       | 84.34%  |
| AMD    | 31        | 15.66%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 6         | 3.03%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5         | 2.53%   |
| Intel Celeron CPU N2805 @ 1.46GHz           | 5         | 2.53%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 4         | 2.02%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 4         | 2.02%   |
| Intel Atom CPU N455 @ 1.66GHz               | 4         | 2.02%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3         | 1.52%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 3         | 1.52%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3         | 1.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3         | 1.52%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 3         | 1.52%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz        | 3         | 1.52%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 2         | 1.01%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2         | 1.01%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 2         | 1.01%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2         | 1.01%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2         | 1.01%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 1.01%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 1.01%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 1.01%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 1.01%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.01%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 1.01%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2         | 1.01%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.01%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 2         | 1.01%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 2         | 1.01%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2         | 1.01%   |
| Intel Atom CPU N570 @ 1.66GHz               | 2         | 1.01%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.01%   |
| AMD Sempron 145 Processor                   | 2         | 1.01%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 2         | 1.01%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1         | 0.51%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 1         | 0.51%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1         | 0.51%   |
| Intel Xeon CPU E5-1607 0 @ 3.00GHz          | 1         | 0.51%   |
| Intel Xeon CPU E31225 @ 3.10GHz             | 1         | 0.51%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1         | 0.51%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.51%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1         | 0.51%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 0.51%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 0.51%   |
| Intel Pentium D CPU 2.80GHz                 | 1         | 0.51%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.51%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.51%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1         | 0.51%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1         | 0.51%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1         | 0.51%   |
| Intel Pentium CPU E5800 @ 3.20GHz           | 1         | 0.51%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.51%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1         | 0.51%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1         | 0.51%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 0.51%   |
| Intel Genuine CPU T2080 @ 1.73GHz           | 1         | 0.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.51%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.51%   |
| Intel Core i7-7820HK CPU @ 2.90GHz          | 1         | 0.51%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.51%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.51%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 27        | 13.64%  |
| Intel Core i3                  | 25        | 12.63%  |
| Intel Pentium Dual-Core        | 21        | 10.61%  |
| Intel Core 2 Duo               | 18        | 9.09%   |
| Intel Core i7                  | 14        | 7.07%   |
| Intel Celeron                  | 14        | 7.07%   |
| Intel Pentium                  | 10        | 5.05%   |
| Intel Atom                     | 8         | 4.04%   |
| Intel Xeon                     | 6         | 3.03%   |
| Intel Pentium Dual             | 5         | 2.53%   |
| AMD Sempron                    | 5         | 2.53%   |
| Other                          | 4         | 2.02%   |
| Intel Pentium 4                | 4         | 2.02%   |
| Intel Core 2 Quad              | 4         | 2.02%   |
| Intel Core 2                   | 3         | 1.52%   |
| AMD Ryzen 5                    | 3         | 1.52%   |
| Intel Genuine                  | 2         | 1.01%   |
| AMD Phenom                     | 2         | 1.01%   |
| AMD FX                         | 2         | 1.01%   |
| AMD E1                         | 2         | 1.01%   |
| AMD Athlon                     | 2         | 1.01%   |
| AMD A6                         | 2         | 1.01%   |
| AMD A10                        | 2         | 1.01%   |
| Intel Pentium Silver           | 1         | 0.51%   |
| Intel Pentium D                | 1         | 0.51%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.51%   |
| AMD Ryzen 7                    | 1         | 0.51%   |
| AMD Ryzen 3                    | 1         | 0.51%   |
| AMD Mobile Sempron             | 1         | 0.51%   |
| AMD E                          | 1         | 0.51%   |
| AMD Athlon II X4               | 1         | 0.51%   |
| AMD Athlon II X2               | 1         | 0.51%   |
| AMD Athlon II                  | 1         | 0.51%   |
| AMD Athlon 64 X2               | 1         | 0.51%   |
| AMD A8                         | 1         | 0.51%   |
| AMD A4                         | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 126       | 63.64%  |
| 4       | 45        | 22.73%  |
| 1       | 16        | 8.08%   |
| Unknown | 4         | 2.02%   |
| 6       | 3         | 1.52%   |
| 3       | 3         | 1.52%   |
| 8       | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 198       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 114       | 57.58%  |
| 2       | 80        | 40.4%   |
| Unknown | 4         | 2.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 189       | 95.45%  |
| 64-bit         | 5         | 2.53%   |
| 32-bit         | 3         | 1.52%   |
| Unknown        | 1         | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 33        | 16.42%  |
| Unknown    | 30        | 14.93%  |
| 0x206a7    | 23        | 11.44%  |
| 0x306a9    | 18        | 8.96%   |
| 0x6fd      | 9         | 4.48%   |
| 0x106ca    | 6         | 2.99%   |
| 0x30673    | 5         | 2.49%   |
| 0x806c1    | 4         | 1.99%   |
| 0x6fb      | 4         | 1.99%   |
| 0x306c3    | 4         | 1.99%   |
| 0x20655    | 4         | 1.99%   |
| 0xf65      | 3         | 1.49%   |
| 0x806e9    | 3         | 1.49%   |
| 0x6f2      | 3         | 1.49%   |
| 0x40651    | 3         | 1.49%   |
| 0x106a5    | 3         | 1.49%   |
| 0x05000119 | 3         | 1.49%   |
| 0x010000c8 | 3         | 1.49%   |
| 0x906e9    | 2         | 1%      |
| 0x406e3    | 2         | 1%      |
| 0x10676    | 2         | 1%      |
| 0x08608103 | 2         | 1%      |
| 0x0810100b | 2         | 1%      |
| 0x010000c7 | 2         | 1%      |
| 0xf47      | 1         | 0.5%    |
| 0xf41      | 1         | 0.5%    |
| 0x906eb    | 1         | 0.5%    |
| 0x806ea    | 1         | 0.5%    |
| 0x706e5    | 1         | 0.5%    |
| 0x6ec      | 1         | 0.5%    |
| 0x506e3    | 1         | 0.5%    |
| 0x406c4    | 1         | 0.5%    |
| 0x306d4    | 1         | 0.5%    |
| 0x30678    | 1         | 0.5%    |
| 0x30661    | 1         | 0.5%    |
| 0x206d7    | 1         | 0.5%    |
| 0x20652    | 1         | 0.5%    |
| 0x10661    | 1         | 0.5%    |
| 0x08600102 | 1         | 0.5%    |
| 0x08101007 | 1         | 0.5%    |
| 0x0700010b | 1         | 0.5%    |
| 0x06006704 | 1         | 0.5%    |
| 0x06006118 | 1         | 0.5%    |
| 0x06003106 | 1         | 0.5%    |
| 0x06001119 | 1         | 0.5%    |
| 0x06000852 | 1         | 0.5%    |
| 0x0600063e | 1         | 0.5%    |
| 0x03000027 | 1         | 0.5%    |
| 0x03000014 | 1         | 0.5%    |
| 0x02000057 | 1         | 0.5%    |
| 0x01000095 | 1         | 0.5%    |
| 0x01000065 | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Penryn          | 36        | 18.18%  |
| SandyBridge     | 29        | 14.65%  |
| IvyBridge       | 21        | 10.61%  |
| Core            | 20        | 10.1%   |
| KabyLake        | 9         | 4.55%   |
| Haswell         | 9         | 4.55%   |
| Westmere        | 8         | 4.04%   |
| K10             | 8         | 4.04%   |
| Bonnell         | 8         | 4.04%   |
| Silvermont      | 7         | 3.54%   |
| NetBurst        | 5         | 2.53%   |
| TigerLake       | 4         | 2.02%   |
| K8 Hammer       | 4         | 2.02%   |
| Zen             | 3         | 1.52%   |
| Skylake         | 3         | 1.52%   |
| Nehalem         | 3         | 1.52%   |
| Bobcat          | 3         | 1.52%   |
| Piledriver      | 2         | 1.01%   |
| K10 Llano       | 2         | 1.01%   |
| Excavator       | 2         | 1.01%   |
| Unknown         | 2         | 1.01%   |
| Zen 2           | 1         | 0.51%   |
| Steamroller     | 1         | 0.51%   |
| P6              | 1         | 0.51%   |
| K8 & K10 hybrid | 1         | 0.51%   |
| Jaguar          | 1         | 0.51%   |
| IceLake         | 1         | 0.51%   |
| Goldmont plus   | 1         | 0.51%   |
| Goldmont        | 1         | 0.51%   |
| Bulldozer       | 1         | 0.51%   |
| Broadwell       | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 140       | 65.73%  |
| AMD               | 35        | 16.43%  |
| Nvidia            | 34        | 15.96%  |
| VIA Technologies  | 3         | 1.41%   |
| ASPEED Technology | 1         | 0.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 26        | 11.71%  |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 13        | 5.86%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 12        | 5.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 7         | 3.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 7         | 3.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 7         | 3.15%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 7         | 3.15%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 7         | 3.15%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 6         | 2.7%    |
| Nvidia GF119 [GeForce GT 520]                                                 | 4         | 1.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 1.8%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 4         | 1.8%    |
| Intel 82946GZ/GL Integrated Graphics Controller                               | 4         | 1.8%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 4         | 1.8%    |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                             | 3         | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 3         | 1.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 3         | 1.35%   |
| Intel HD Graphics 630                                                         | 3         | 1.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 1.35%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 1.35%   |
| Nvidia GT218 [GeForce 210]                                                    | 2         | 0.9%    |
| Nvidia GF119 [GeForce GT 610]                                                 | 2         | 0.9%    |
| Nvidia GF106 [GeForce GTS 450]                                                | 2         | 0.9%    |
| Nvidia G96C [GeForce 9500 GT]                                                 | 2         | 0.9%    |
| Nvidia G86 [GeForce 8500 GT]                                                  | 2         | 0.9%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                       | 2         | 0.9%    |
| Nvidia C61 [GeForce 6150SE nForce 430]                                        | 2         | 0.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 0.9%    |
| Intel HD Graphics 620                                                         | 2         | 0.9%    |
| Intel 82945G/GZ Integrated Graphics Controller                                | 2         | 0.9%    |
| Intel 82865G Integrated Graphics Controller                                   | 2         | 0.9%    |
| AMD Wrestler [Radeon HD 7310]                                                 | 2         | 0.9%    |
| AMD RV670 [Radeon HD 3870]                                                    | 2         | 0.9%    |
| AMD Madison [Mobility Radeon HD 5730 / 6570M]                                 | 2         | 0.9%    |
| AMD Lucienne                                                                  | 2         | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.45%   |
| Nvidia TU117M                                                                 | 1         | 0.45%   |
| Nvidia NV44 [GeForce 6200 LE]                                                 | 1         | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.45%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                      | 1         | 0.45%   |
| Nvidia GM204GLM [Quadro M3000M]                                               | 1         | 0.45%   |
| Nvidia GK208B [GeForce GT 710]                                                | 1         | 0.45%   |
| Nvidia GK107GL [Quadro K600]                                                  | 1         | 0.45%   |
| Nvidia GK107 [GeForce GT 640]                                                 | 1         | 0.45%   |
| Nvidia GK104GL [Quadro K4200]                                                 | 1         | 0.45%   |
| Nvidia GF119 [GeForce 605]                                                    | 1         | 0.45%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                             | 1         | 0.45%   |
| Nvidia GF114 [GeForce GTX 560]                                                | 1         | 0.45%   |
| Nvidia GF108 [GeForce GT 620]                                                 | 1         | 0.45%   |
| Nvidia GF104 [GeForce GTX 460]                                                | 1         | 0.45%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 1         | 0.45%   |
| Nvidia G96C [GeForce 9400 GT]                                                 | 1         | 0.45%   |
| Intel Xeon E3-1200 Processor Family Integrated Graphics Controller            | 1         | 0.45%   |
| Intel UHD Graphics 620                                                        | 1         | 0.45%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.45%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 0.45%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 0.45%   |
| Intel HD Graphics 615                                                         | 1         | 0.45%   |
| Intel HD Graphics 5500                                                        | 1         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 129       | 64.82%  |
| 1 x AMD         | 31        | 15.58%  |
| 1 x Nvidia      | 27        | 13.57%  |
| Intel + Nvidia  | 4         | 2.01%   |
| 1 x VIA         | 3         | 1.51%   |
| Intel + AMD     | 2         | 1.01%   |
| AMD + Nvidia    | 2         | 1.01%   |
| Nvidia + ASPEED | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 172       | 86.87%  |
| Proprietary | 16        | 8.08%   |
| Unknown     | 10        | 5.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 124       | 60.49%  |
| 0.01-0.5   | 33        | 16.1%   |
| 0.51-1.0   | 24        | 11.71%  |
| 1.01-2.0   | 18        | 8.78%   |
| 3.01-4.0   | 6         | 2.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung Electronics                   | 44        | 21.67%  |
| Hewlett-Packard                       | 16        | 7.88%   |
| BOE                                   | 14        | 6.9%    |
| LG Display                            | 12        | 5.91%   |
| Lenovo                                | 12        | 5.91%   |
| Goldstar                              | 12        | 5.91%   |
| AU Optronics                          | 11        | 5.42%   |
| InfoVision                            | 8         | 3.94%   |
| Chimei Innolux                        | 8         | 3.94%   |
| Dell                                  | 6         | 2.96%   |
| Chi Mei Optoelectronics               | 6         | 2.96%   |
| Toshiba                               | 5         | 2.46%   |
| LG Philips                            | 5         | 2.46%   |
| Acer                                  | 5         | 2.46%   |
| AOC                                   | 4         | 1.97%   |
| HannStar                              | 3         | 1.48%   |
| BenQ                                  | 3         | 1.48%   |
| Apple                                 | 3         | 1.48%   |
| Vita                                  | 2         | 0.99%   |
| Sony                                  | 2         | 0.99%   |
| PANDA                                 | 2         | 0.99%   |
| MStar                                 | 2         | 0.99%   |
| ITL                                   | 2         | 0.99%   |
| Envision                              | 2         | 0.99%   |
| Vizio                                 | 1         | 0.49%   |
| ViewSonic                             | 1         | 0.49%   |
| Unknown (XXX)                         | 1         | 0.49%   |
| Toshiba Matsushita Display Technology | 1         | 0.49%   |
| TCL                                   | 1         | 0.49%   |
| Sharp                                 | 1         | 0.49%   |
| PEGA                                  | 1         | 0.49%   |
| Parker                                | 1         | 0.49%   |
| LG Electronics                        | 1         | 0.49%   |
| LED                                   | 1         | 0.49%   |
| KTC                                   | 1         | 0.49%   |
| InnoLux Display                       | 1         | 0.49%   |
| IBM                                   | 1         | 0.49%   |
| CVT                                   | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch           | 5         | 2.44%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 4         | 1.95%   |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                 | 4         | 1.95%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 3         | 1.46%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 3         | 1.46%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                  | 3         | 1.46%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch         | 3         | 1.46%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                    | 2         | 0.98%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch              | 2         | 0.98%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch     | 2         | 0.98%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch  | 2         | 0.98%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 2         | 0.98%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.98%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.98%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 2         | 0.98%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 2         | 0.98%   |
| ITL MT-3185 ITL3185 1366x768 409x230mm 18.5-inch                      | 2         | 0.98%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch           | 2         | 0.98%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 2         | 0.98%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 0.98%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch       | 2         | 0.98%   |
| Apple Color LCD APP9CDD 1920x1080 475x267mm 21.5-inch                 | 2         | 0.98%   |
| Vizio E322AR VIZ0079 1360x768 700x400mm 31.7-inch                     | 1         | 0.49%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch         | 1         | 0.49%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch            | 1         | 0.49%   |
| Toshiba Matsushita Display Technology LCD Monitor LCD-MONITOR         | 1         | 0.49%   |
| TCL T-7005L TCL1770 1280x1024 338x270mm 17.0-inch                     | 1         | 0.49%   |
| Sony TV SNYEB01 1360x768                                              | 1         | 0.49%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.49%   |
| Sony TV SNYDC01 1360x768 1600x900mm 72.3-inch                         | 1         | 0.49%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch  | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0499 1600x900 443x249mm 20.0-inch   | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch   | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM03F5 1920x1200                      | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM03F4 1920x1200 518x324mm 24.1-inch  | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 1         | 0.49%   |
| Samsung Electronics SMBX2050N SAM0719 1600x900 443x249mm 20.0-inch    | 1         | 0.49%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1         | 0.49%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1         | 0.49%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch  | 1         | 0.49%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1         | 0.49%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch      | 1         | 0.49%   |
| Samsung Electronics Monitor SAM1057 1280x1024 306x230mm 15.1-inch     | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SyncMaster 1600x900                   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC8151 1920x1080 382x214mm 17.2-inch | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch  | 1         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 75        | 37.88%  |
| 1920x1080 (FHD)    | 40        | 20.2%   |
| 1280x1024 (SXGA)   | 24        | 12.12%  |
| 1280x800 (WXGA)    | 11        | 5.56%   |
| 1600x900 (HD+)     | 10        | 5.05%   |
| 1440x900 (WXGA+)   | 9         | 4.55%   |
| 1360x768           | 7         | 3.54%   |
| 1680x1050 (WSXGA+) | 5         | 2.53%   |
| 3840x2160 (4K)     | 4         | 2.02%   |
| 1920x1200 (WUXGA)  | 3         | 1.52%   |
| 1024x768 (XGA)     | 3         | 1.52%   |
| 2560x1440 (QHD)    | 2         | 1.01%   |
| 1280x720 (HD)      | 2         | 1.01%   |
| 1024x600           | 2         | 1.01%   |
| Unknown            | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 45        | 22.28%  |
| 18      | 25        | 12.38%  |
| 14      | 21        | 10.4%   |
| 17      | 19        | 9.41%   |
| 13      | 17        | 8.42%   |
| 21      | 16        | 7.92%   |
| 19      | 11        | 5.45%   |
| 10      | 8         | 3.96%   |
| Unknown | 7         | 3.47%   |
| 20      | 6         | 2.97%   |
| 23      | 5         | 2.48%   |
| 74      | 3         | 1.49%   |
| 22      | 3         | 1.49%   |
| 72      | 2         | 0.99%   |
| 52      | 2         | 0.99%   |
| 27      | 2         | 0.99%   |
| 24      | 2         | 0.99%   |
| 16      | 2         | 0.99%   |
| 11      | 2         | 0.99%   |
| 54      | 1         | 0.5%    |
| 32      | 1         | 0.5%    |
| 31      | 1         | 0.5%    |
| 12      | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 96        | 48.73%  |
| 401-500     | 52        | 26.4%   |
| 201-300     | 13        | 6.6%    |
| 351-400     | 10        | 5.08%   |
| 501-600     | 9         | 4.57%   |
| Unknown     | 7         | 3.55%   |
| 1501-2000   | 5         | 2.54%   |
| 1001-1500   | 3         | 1.52%   |
| 701-800     | 1         | 0.51%   |
| 601-700     | 1         | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 124       | 66.31%  |
| 16/10   | 30        | 16.04%  |
| 5/4     | 22        | 11.76%  |
| Unknown | 5         | 2.67%   |
| 4/3     | 4         | 2.14%   |
| 3/2     | 2         | 1.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 45        | 22.39%  |
| 141-150        | 38        | 18.91%  |
| 81-90          | 36        | 17.91%  |
| 151-200        | 26        | 12.94%  |
| 201-250        | 17        | 8.46%   |
| More than 1000 | 8         | 3.98%   |
| 41-50          | 8         | 3.98%   |
| Unknown        | 7         | 3.48%   |
| 121-130        | 4         | 1.99%   |
| 51-60          | 2         | 1%      |
| 351-500        | 2         | 1%      |
| 301-350        | 2         | 1%      |
| 251-300        | 2         | 1%      |
| 71-80          | 1         | 0.5%    |
| 61-70          | 1         | 0.5%    |
| 131-140        | 1         | 0.5%    |
| 91-100         | 1         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 89        | 44.72%  |
| 101-120       | 63        | 31.66%  |
| 121-160       | 27        | 13.57%  |
| 1-50          | 10        | 5.03%   |
| Unknown       | 7         | 3.52%   |
| 161-240       | 2         | 1.01%   |
| More than 240 | 1         | 0.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 169       | 84.5%   |
| 2     | 21        | 10.5%   |
| 0     | 8         | 4%      |
| 3     | 2         | 1%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 123       | 38.2%   |
| Qualcomm Atheros                  | 61        | 18.94%  |
| Intel                             | 53        | 16.46%  |
| Broadcom                          | 23        | 7.14%   |
| Ralink                            | 11        | 3.42%   |
| Nvidia                            | 10        | 3.11%   |
| Ralink Technology                 | 5         | 1.55%   |
| Xiaomi                            | 4         | 1.24%   |
| Qualcomm Atheros Communications   | 4         | 1.24%   |
| Marvell Technology Group          | 4         | 1.24%   |
| Broadcom Limited                  | 4         | 1.24%   |
| VIA Technologies                  | 3         | 0.93%   |
| JMicron Technology                | 3         | 0.93%   |
| Trendchip Technologies            | 2         | 0.62%   |
| Sundance Technology Inc / IC Plus | 2         | 0.62%   |
| Samsung Electronics               | 2         | 0.62%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.31%   |
| National Semiconductor            | 1         | 0.31%   |
| Motorola PCS                      | 1         | 0.31%   |
| Motorola BCS                      | 1         | 0.31%   |
| Mercucys                          | 1         | 0.31%   |
| ICS Advent                        | 1         | 0.31%   |
| Digium                            | 1         | 0.31%   |
| AMD                               | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 70        | 19.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 28        | 7.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 14        | 3.89%   |
| Nvidia MCP61 Ethernet                                                          | 9         | 2.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 8         | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 8         | 2.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 7         | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 6         | 1.67%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 6         | 1.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 1.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 5         | 1.39%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5         | 1.39%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 4         | 1.11%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 4         | 1.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4         | 1.11%   |
| Intel Centrino Wireless-N 105                                                  | 4         | 1.11%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 4         | 1.11%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 4         | 1.11%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 3         | 0.83%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 3         | 0.83%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 3         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 3         | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 0.83%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 3         | 0.83%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3         | 0.83%   |
| Intel Wireless 7260                                                            | 3         | 0.83%   |
| Intel PRO/100 VE Network Connection                                            | 3         | 0.83%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 3         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 0.56%   |
| Trendchip Ethernet controller                                                  | 2         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2         | 0.56%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                         | 2         | 0.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2         | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 2         | 0.56%   |
| Ralink MT7601U Wireless Adapter                                                | 2         | 0.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 2         | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.56%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 0.56%   |
| Intel Wireless 8260                                                            | 2         | 0.56%   |
| Intel Wireless 7265                                                            | 2         | 0.56%   |
| Intel Wireless 3165                                                            | 2         | 0.56%   |
| Intel WiFi Link 5100                                                           | 2         | 0.56%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 0.56%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 0.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 2         | 0.56%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 0.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 0.56%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 46        | 30.46%  |
| Realtek Semiconductor           | 40        | 26.49%  |
| Intel                           | 31        | 20.53%  |
| Broadcom                        | 12        | 7.95%   |
| Ralink                          | 11        | 7.28%   |
| Ralink Technology               | 5         | 3.31%   |
| Qualcomm Atheros Communications | 4         | 2.65%   |
| Mercucys                        | 1         | 0.66%   |
| Broadcom Limited                | 1         | 0.66%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 14        | 9.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 8         | 5.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 8         | 5.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 6         | 3.97%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 6         | 3.97%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5         | 3.31%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 4         | 2.65%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 4         | 2.65%   |
| Intel Centrino Wireless-N 105                                                  | 4         | 2.65%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 4         | 2.65%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 3         | 1.99%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 3         | 1.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 3         | 1.99%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3         | 1.99%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3         | 1.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 3         | 1.99%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3         | 1.99%   |
| Intel Wireless 7260                                                            | 3         | 1.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 1.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2         | 1.32%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                         | 2         | 1.32%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2         | 1.32%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 2         | 1.32%   |
| Ralink MT7601U Wireless Adapter                                                | 2         | 1.32%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 2         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 1.32%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 1.32%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 1.32%   |
| Intel Wireless 8260                                                            | 2         | 1.32%   |
| Intel Wireless 7265                                                            | 2         | 1.32%   |
| Intel Wireless 3165                                                            | 2         | 1.32%   |
| Intel WiFi Link 5100                                                           | 2         | 1.32%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 1.32%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 1.32%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 2         | 1.32%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 1.32%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                              | 2         | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 0.66%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.66%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1         | 0.66%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 0.66%   |
| Ralink RT5372 Wireless Adapter                                                 | 1         | 0.66%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1         | 0.66%   |
| Qualcomm Atheros AR5523                                                        | 1         | 0.66%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1         | 0.66%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]            | 1         | 0.66%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 1         | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 1         | 0.66%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 0.66%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 0.66%   |
| Intel Centrino Ultimate-N 6300                                                 | 1         | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1         | 0.66%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                      | 1         | 0.66%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 1         | 0.66%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller            | 1         | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 106       | 51.71%  |
| Intel                             | 30        | 14.63%  |
| Qualcomm Atheros                  | 21        | 10.24%  |
| Broadcom                          | 11        | 5.37%   |
| Nvidia                            | 10        | 4.88%   |
| Xiaomi                            | 4         | 1.95%   |
| Marvell Technology Group          | 4         | 1.95%   |
| VIA Technologies                  | 3         | 1.46%   |
| JMicron Technology                | 3         | 1.46%   |
| Broadcom Limited                  | 3         | 1.46%   |
| Trendchip Technologies            | 2         | 0.98%   |
| Sundance Technology Inc / IC Plus | 2         | 0.98%   |
| Samsung Electronics               | 2         | 0.98%   |
| National Semiconductor            | 1         | 0.49%   |
| Motorola PCS                      | 1         | 0.49%   |
| Motorola BCS                      | 1         | 0.49%   |
| ICS Advent                        | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 70        | 33.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 28        | 13.59%  |
| Nvidia MCP61 Ethernet                                                      | 9         | 4.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 7         | 3.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 2.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 5         | 2.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 4         | 1.94%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4         | 1.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3         | 1.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3         | 1.46%   |
| Intel PRO/100 VE Network Connection                                        | 3         | 1.46%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 3         | 1.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2         | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2         | 0.97%   |
| Trendchip Ethernet controller                                              | 2         | 0.97%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 2         | 0.97%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2         | 0.97%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 2         | 0.97%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                     | 2         | 0.97%   |
| Intel Ethernet Connection I217-V                                           | 2         | 0.97%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2         | 0.97%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                | 2         | 0.97%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1         | 0.49%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1         | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1         | 0.49%   |
| Realtek Realtek Ethernet controller                                        | 1         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.49%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1         | 0.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                      | 1         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1         | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1         | 0.49%   |
| Nvidia MCP77 Ethernet                                                      | 1         | 0.49%   |
| National DP83815 (MacPhyter) Ethernet Controller                           | 1         | 0.49%   |
| Motorola PCS moto g(6) play                                                | 1         | 0.49%   |
| Motorola BCS SurfBoard SB5100 Cable Modem                                  | 1         | 0.49%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 1         | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                    | 1         | 0.49%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                        | 1         | 0.49%   |
| Intel NM10/ICH7 Family LAN Controller                                      | 1         | 0.49%   |
| Intel I210 Gigabit Network Connection                                      | 1         | 0.49%   |
| Intel Ethernet Connection I219-V                                           | 1         | 0.49%   |
| Intel Ethernet Connection I219-LM                                          | 1         | 0.49%   |
| Intel Ethernet Connection I217-LM                                          | 1         | 0.49%   |
| Intel Ethernet Connection (4) I219-LM                                      | 1         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                                      | 1         | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1         | 0.49%   |
| Intel 82579V Gigabit Network Connection                                    | 1         | 0.49%   |
| Intel 82577LM Gigabit Network Connection                                   | 1         | 0.49%   |
| Intel 82574L Gigabit Network Connection                                    | 1         | 0.49%   |
| Intel 82567V-4 Gigabit Network Connection                                  | 1         | 0.49%   |
| Intel 82567LM-2 Gigabit Network Connection                                 | 1         | 0.49%   |
| Intel 82566DC-2 Gigabit Network Connection                                 | 1         | 0.49%   |
| Intel 82566DC Gigabit Network Connection                                   | 1         | 0.49%   |
| Intel 82562V-2 10/100 Network Connection                                   | 1         | 0.49%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                       | 1         | 0.49%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 1         | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                          | 1         | 0.49%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 1         | 0.49%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                            | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 189       | 55.92%  |
| WiFi     | 146       | 43.2%   |
| Modem    | 2         | 0.59%   |
| Unknown  | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 104       | 50.73%  |
| Ethernet | 101       | 49.27%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 119       | 59.5%   |
| 1     | 75        | 37.5%   |
| 3     | 4         | 2%      |
| 4     | 1         | 0.5%    |
| 0     | 1         | 0.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 198       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 28.33%  |
| Realtek Semiconductor           | 9         | 15%     |
| Qualcomm Atheros Communications | 8         | 13.33%  |
| Cambridge Silicon Radio         | 8         | 13.33%  |
| IMC Networks                    | 7         | 11.67%  |
| Broadcom                        | 6         | 10%     |
| Apple                           | 3         | 5%      |
| ASUSTek Computer                | 2         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 13.33%  |
| Realtek RTL8723B Bluetooth                          | 6         | 10%     |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 6.67%   |
| Realtek Bluetooth Radio                             | 3         | 5%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 5%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 5%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 3.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 3.33%   |
| Intel AX201 Bluetooth                               | 2         | 3.33%   |
| Intel AX200 Bluetooth                               | 2         | 3.33%   |
| IMC Networks Bluetooth                              | 2         | 3.33%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.67%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.67%   |
| IMC Networks Bluetooth Module                       | 1         | 1.67%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.67%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.67%   |
| Broadcom BCM2035B3 Bluetooth Adapter                | 1         | 1.67%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 1.67%   |
| ASUS Bluetooth Adapter                              | 1         | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 162       | 65.85%  |
| AMD                       | 36        | 14.63%  |
| Nvidia                    | 27        | 10.98%  |
| C-Media Electronics       | 6         | 2.44%   |
| VIA Technologies          | 4         | 1.63%   |
| Creative Labs             | 3         | 1.22%   |
| Sennheiser Communications | 2         | 0.81%   |
| JMTek                     | 2         | 0.81%   |
| Unknown                   | 1         | 0.41%   |
| Realtek Semiconductor     | 1         | 0.41%   |
| Microsoft                 | 1         | 0.41%   |
| Logitech                  | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 38        | 13.87%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 28        | 10.22%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 21        | 7.66%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 12        | 4.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                              | 9         | 3.28%   |
| Nvidia MCP61 High Definition Audio                                          | 8         | 2.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 8         | 2.92%   |
| AMD FCH Azalia Controller                                                   | 8         | 2.92%   |
| Nvidia GF119 HDMI Audio Controller                                          | 7         | 2.55%   |
| Intel Sunrise Point-LP HD Audio                                             | 6         | 2.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller  | 6         | 2.19%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 6         | 2.19%   |
| AMD Family 17h/19h HD Audio Controller                                      | 6         | 2.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 5         | 1.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                 | 4         | 1.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 4         | 1.46%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 4         | 1.46%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller              | 3         | 1.09%   |
| Intel Haswell-ULT HD Audio Controller                                       | 3         | 1.09%   |
| Intel 8 Series HD Audio Controller                                          | 3         | 1.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 3         | 1.09%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                            | 3         | 1.09%   |
| AMD Renoir Radeon High Definition Audio Controller                          | 3         | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 3         | 1.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]     | 3         | 1.09%   |
| Sennheiser Communications SC230                                             | 2         | 0.73%   |
| Nvidia High Definition Audio Controller                                     | 2         | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                          | 2         | 0.73%   |
| Nvidia GF106 High Definition Audio Controller                               | 2         | 0.73%   |
| Intel CM238 HD Audio Controller                                             | 2         | 0.73%   |
| Intel Cannon Lake PCH cAVS                                                  | 2         | 0.73%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                        | 2         | 0.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 2         | 0.73%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                               | 2         | 0.73%   |
| C-Media Electronics CM108 Audio Controller                                  | 2         | 0.73%   |
| AMD Wrestler HDMI Audio                                                     | 2         | 0.73%   |
| AMD RV670/680 HDMI Audio [Radeon HD 3690/3800 Series]                       | 2         | 0.73%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                              | 2         | 0.73%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                            | 2         | 0.73%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]         | 2         | 0.73%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1         | 0.36%   |
| Unknown Audio device                                                        | 1         | 0.36%   |
| Realtek Semiconductor USB Audio                                             | 1         | 0.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller              | 1         | 0.36%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                   | 1         | 0.36%   |
| Nvidia GM204 High Definition Audio Controller                               | 1         | 0.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 1         | 0.36%   |
| Nvidia GK104 HDMI Audio Controller                                          | 1         | 0.36%   |
| Nvidia GF116 High Definition Audio Controller                               | 1         | 0.36%   |
| Nvidia GF114 HDMI Audio Controller                                          | 1         | 0.36%   |
| Nvidia GF108 High Definition Audio Controller                               | 1         | 0.36%   |
| Nvidia GF104 High Definition Audio Controller                               | 1         | 0.36%   |
| Nvidia Audio device                                                         | 1         | 0.36%   |
| Microsoft LifeChat LX-4000                                                  | 1         | 0.36%   |
| Logitech H600 [Wireless Headset]                                            | 1         | 0.36%   |
| JMTek USB PnP Audio Device                                                  | 1         | 0.36%   |
| JMTek audio controller                                                      | 1         | 0.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                     | 1         | 0.36%   |
| Intel USB PnP Sound Device                                                  | 1         | 0.36%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                   | 1         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 41        | 24.7%   |
| Samsung Electronics | 24        | 14.46%  |
| SK Hynix            | 20        | 12.05%  |
| Ramaxel Technology  | 16        | 9.64%   |
| Kingston            | 16        | 9.64%   |
| Micron Technology   | 10        | 6.02%   |
| Crucial             | 8         | 4.82%   |
| Corsair             | 8         | 4.82%   |
| Nanya Technology    | 3         | 1.81%   |
| A-DATA Technology   | 3         | 1.81%   |
| Unknown (ABCD)      | 2         | 1.2%    |
| Unknown (0x07D5)    | 2         | 1.2%    |
| ELPIDA              | 2         | 1.2%    |
| Avant               | 2         | 1.2%    |
| Unknown             | 2         | 1.2%    |
| Unknown (0x0CBA)    | 1         | 0.6%    |
| Unknown (081A)      | 1         | 0.6%    |
| Qimonda             | 1         | 0.6%    |
| PNY                 | 1         | 0.6%    |
| OCZ                 | 1         | 0.6%    |
| Memox               | 1         | 0.6%    |
| Kreton              | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2                            | 3         | 1.66%   |
| Unknown RAM Module 1024MB DIMM DDR2                            | 3         | 1.66%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s        | 3         | 1.66%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s        | 3         | 1.66%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s        | 3         | 1.66%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 2         | 1.1%    |
| Unknown RAM Module 2GB DIMM 400MT/s                            | 2         | 1.1%    |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 2         | 1.1%    |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 2         | 1.1%    |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                    | 2         | 1.1%    |
| Unknown (0x07D5) RAM Module 4GB SODIMM DDR3 1333MT/s           | 2         | 1.1%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1.1%    |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s         | 2         | 1.1%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 1.1%    |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                    | 2         | 1.1%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s          | 2         | 1.1%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.1%    |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s            | 2         | 1.1%    |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s        | 2         | 1.1%    |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s        | 2         | 1.1%    |
| Ramaxel RAM Module 4GB SODIMM DDR3 1333MT/s                    | 2         | 1.1%    |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s          | 2         | 1.1%    |
| Kingston RAM Module 4GB SODIMM DDR3 1333MT/s                   | 2         | 1.1%    |
| Unknown                                                        | 2         | 1.1%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 1         | 0.55%   |
| Unknown RAM Module 512MB DIMM DDR2                             | 1         | 0.55%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 0.55%   |
| Unknown RAM Module 4GB DIMM 400MT/s                            | 1         | 0.55%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                           | 1         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 1         | 0.55%   |
| Unknown RAM Module 4096MB DIMM SDRAM                           | 1         | 0.55%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 1         | 0.55%   |
| Unknown RAM Module 4096MB DIMM                                 | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                    | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                      | 1         | 0.55%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1         | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 1         | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1         | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 1         | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                        | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 0.55%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                   | 1         | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                   | 1         | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s                    | 1         | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 1639MT/s                   | 1         | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                     | 1         | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                     | 1         | 0.55%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                        | 1         | 0.55%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 1         | 0.55%   |
| Unknown RAM Module 1GB DIMM DDR 133MT/s                        | 1         | 0.55%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2667MT/s                | 1         | 0.55%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                  | 1         | 0.55%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                     | 1         | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 1         | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 0.55%   |
| Unknown (0x0CBA) RAM JC4S8GB26C03D 8GB SODIMM DDR4 2667MT/s    | 1         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 52        | 40.63%  |
| DDR2    | 30        | 23.44%  |
| DDR4    | 18        | 14.06%  |
| SDRAM   | 14        | 10.94%  |
| Unknown | 7         | 5.47%   |
| DDR     | 5         | 3.91%   |
| LPDDR4  | 2         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 65        | 52.85%  |
| SODIMM       | 56        | 45.53%  |
| Row Of Chips | 2         | 1.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 56        | 38.36%  |
| 4096  | 45        | 30.82%  |
| 8192  | 21        | 14.38%  |
| 1024  | 19        | 13.01%  |
| 16384 | 4         | 2.74%   |
| 512   | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 36        | 25%     |
| 1333    | 18        | 12.5%   |
| Unknown | 16        | 11.11%  |
| 2400    | 8         | 5.56%   |
| 800     | 8         | 5.56%   |
| 667     | 8         | 5.56%   |
| 3200    | 6         | 4.17%   |
| 2667    | 6         | 4.17%   |
| 533     | 6         | 4.17%   |
| 1066    | 5         | 3.47%   |
| 2048    | 4         | 2.78%   |
| 1639    | 3         | 2.08%   |
| 1334    | 3         | 2.08%   |
| 400     | 3         | 2.08%   |
| 133     | 3         | 2.08%   |
| 4199    | 2         | 1.39%   |
| 2133    | 2         | 1.39%   |
| 1067    | 2         | 1.39%   |
| 3266    | 1         | 0.69%   |
| 3000    | 1         | 0.69%   |
| 1867    | 1         | 0.69%   |
| 1024    | 1         | 0.69%   |
| 975     | 1         | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 55.56%  |
| Seiko Epson         | 2         | 22.22%  |
| Samsung Electronics | 2         | 22.22%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 11.11%  |
| Seiko Epson L210 Series                      | 1         | 11.11%  |
| Samsung ML-216x Series Laser Printer         | 1         | 11.11%  |
| Samsung ML-1865                              | 1         | 11.11%  |
| HP LaserJet Professional P1102w              | 1         | 11.11%  |
| HP LaserJet P1006                            | 1         | 11.11%  |
| HP LaserJet P1005                            | 1         | 11.11%  |
| HP LaserJet 1018                             | 1         | 11.11%  |
| HP Color LaserJet CP1215                     | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP Scanjet 200          | 1         | 50%     |
| Canon CanoScan LiDE 110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 21.74%  |
| Acer                                   | 11        | 11.96%  |
| Microdia                               | 10        | 10.87%  |
| Realtek Semiconductor                  | 9         | 9.78%   |
| IMC Networks                           | 6         | 6.52%   |
| Suyin                                  | 5         | 5.43%   |
| Logitech                               | 5         | 5.43%   |
| Apple                                  | 4         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.26%   |
| Syntek                                 | 2         | 2.17%   |
| Ricoh                                  | 2         | 2.17%   |
| Microsoft                              | 2         | 2.17%   |
| KYE Systems (Mouse Systems)            | 2         | 2.17%   |
| Tobii Technology AB                    | 1         | 1.09%   |
| Sunplus Innovation Technology          | 1         | 1.09%   |
| SiGma Micro                            | 1         | 1.09%   |
| Samsung Electronics                    | 1         | 1.09%   |
| Quanta                                 | 1         | 1.09%   |
| Luxvisions Innotech Limited            | 1         | 1.09%   |
| Lite-On Technology                     | 1         | 1.09%   |
| LG Electronics                         | 1         | 1.09%   |
| Lenovo                                 | 1         | 1.09%   |
| Aveo Technology                        | 1         | 1.09%   |
| ALi                                    | 1         | 1.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                        | 9         | 9.78%   |
| Realtek Integrated_Webcam_HD                                  | 4         | 4.35%   |
| Logitech Webcam C270                                          | 3         | 3.26%   |
| Chicony Lenovo EasyCamera                                     | 3         | 3.26%   |
| Microdia USB 2.0 Camera                                       | 2         | 2.17%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 2.17%   |
| IMC Networks USB 2.0 UVC VGA WebCam                           | 2         | 2.17%   |
| Chicony Integrated Camera                                     | 2         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 2         | 2.17%   |
| Apple Built-in iSight                                         | 2         | 2.17%   |
| Acer USB HD Webcam                                            | 2         | 2.17%   |
| Acer USB Camera                                               | 2         | 2.17%   |
| Acer Lenovo EasyCamera                                        | 2         | 2.17%   |
| Acer HD Webcam                                                | 2         | 2.17%   |
| Tobii AB EyeChip                                              | 1         | 1.09%   |
| Syntek USB Camera Device                                      | 1         | 1.09%   |
| Syntek Integrated Webcam                                      | 1         | 1.09%   |
| Suyin USB2.0 UVC 1.3M WebCam                                  | 1         | 1.09%   |
| Suyin HP Webcam 101                                           | 1         | 1.09%   |
| Suyin HP Webcam                                               | 1         | 1.09%   |
| Suyin HD Video WebCam                                         | 1         | 1.09%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 1.09%   |
| Sunplus MTD Camera                                            | 1         | 1.09%   |
| SiGma Micro WebCam SiGma Micro                                | 1         | 1.09%   |
| Samsung Galaxy A5 (MTP)                                       | 1         | 1.09%   |
| Ricoh Sony Vaio Integrated Webcam                             | 1         | 1.09%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 1         | 1.09%   |
| Realtek USB Camera                                            | 1         | 1.09%   |
| Realtek MTD camera                                            | 1         | 1.09%   |
| Realtek Integrated Webcam HD                                  | 1         | 1.09%   |
| Realtek Integrated Webcam                                     | 1         | 1.09%   |
| Realtek HP 1.0MP High Definition Webcam                       | 1         | 1.09%   |
| Quanta HP Webcam                                              | 1         | 1.09%   |
| Microsoft LifeCam VX-5000                                     | 1         | 1.09%   |
| Microsoft LifeCam Studio                                      | 1         | 1.09%   |
| Microdia WebCam SC-13HDL12639P                                | 1         | 1.09%   |
| Microdia USB camera                                           | 1         | 1.09%   |
| Microdia Sonix USB 2.0 Camera                                 | 1         | 1.09%   |
| Microdia Laptop_Integrated_Webcam_HD                          | 1         | 1.09%   |
| Microdia Integrated_Webcam_HD                                 | 1         | 1.09%   |
| Microdia Integrated_Webcam_FHD                                | 1         | 1.09%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera           | 1         | 1.09%   |
| Logitech QuickCam Communicate MP/S5500                        | 1         | 1.09%   |
| Logitech C922 Pro Stream Webcam                               | 1         | 1.09%   |
| Lite-On TOSHIBA Web Camera - HD                               | 1         | 1.09%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)         | 1         | 1.09%   |
| Lenovo CNF7237&CNF7238                                        | 1         | 1.09%   |
| KYE Systems (Mouse Systems) FaceCam 1320                      | 1         | 1.09%   |
| KYE Systems (Mouse Systems) eFace 2025                        | 1         | 1.09%   |
| IMC Networks USB2.0 VGA UVC WebCam                            | 1         | 1.09%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 1         | 1.09%   |
| IMC Networks USB 2.0 Camera                                   | 1         | 1.09%   |
| IMC Networks EasyCamera                                       | 1         | 1.09%   |
| Chicony USB2.0 HD UVC WebCam                                  | 1         | 1.09%   |
| Chicony Lenovo Integrated Camera                              | 1         | 1.09%   |
| Chicony HP HD Camera                                          | 1         | 1.09%   |
| Chicony HD WebCam                                             | 1         | 1.09%   |
| Chicony CNFA213                                               | 1         | 1.09%   |
| Chicony 1.3M HD WebCam                                        | 1         | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD       | 1         | 1.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Validity Sensors    | 4         | 57.14%  |
| AuthenTec           | 2         | 28.57%  |
| Futronic Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 2         | 28.57%  |
| AuthenTec AES2501 Fingerprint Sensor        | 2         | 28.57%  |
| Validity Sensors VFS495 Fingerprint Reader  | 1         | 14.29%  |
| Validity Sensors Fingerprint scanner        | 1         | 14.29%  |
| Futronic Fingerprint Scanner Model FS88     | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 66.67%  |
| Broadcom 5880                                  | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 159       | 79.5%   |
| 1     | 38        | 19%     |
| 2     | 2         | 1%      |
| 4     | 1         | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 16        | 34.04%  |
| Communication controller | 9         | 19.15%  |
| Fingerprint reader       | 7         | 14.89%  |
| Net/wireless             | 4         | 8.51%   |
| Sound                    | 3         | 6.38%   |
| Chipcard                 | 3         | 6.38%   |
| Camera                   | 2         | 4.26%   |
| Storage                  | 1         | 2.13%   |
| Network                  | 1         | 2.13%   |
| Multimedia controller    | 1         | 2.13%   |

