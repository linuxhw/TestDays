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

Total: 332

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | N68-VS3 UCC                 | Desktop     | [688dcf88c9](https://linux-hardware.org/?probe=688dcf88c9) | Aug 30, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [4ccef99860](https://linux-hardware.org/?probe=4ccef99860) | Aug 30, 2022 |
| HP            | 0A60h                       | Desktop     | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [3c63953ca6](https://linux-hardware.org/?probe=3c63953ca6) | Aug 27, 2022 |
| HP            | 1497                        | Desktop     | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [4bd2fabdc7](https://linux-hardware.org/?probe=4bd2fabdc7) | Aug 26, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [659ccaca6e](https://linux-hardware.org/?probe=659ccaca6e) | Aug 22, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| Biostar       | A780L3B                     | Desktop     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| Intel         | S1200BTL E98681-352         | Server      | [1db51bcff9](https://linux-hardware.org/?probe=1db51bcff9) | Aug 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [63a6df97b9](https://linux-hardware.org/?probe=63a6df97b9) | Aug 09, 2022 |
| VIT           | P2402                       | Notebook    | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [fc4f66c2de](https://linux-hardware.org/?probe=fc4f66c2de) | Aug 02, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| Dell          | Latitude 5490               | Notebook    | [743422e837](https://linux-hardware.org/?probe=743422e837) | Aug 02, 2022 |
| Dell          | Latitude 5490               | Notebook    | [78bde5c7cc](https://linux-hardware.org/?probe=78bde5c7cc) | Aug 02, 2022 |
| VIT           | P2402                       | Notebook    | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| HP            | 339A                        | Desktop     | [c19f3d1361](https://linux-hardware.org/?probe=c19f3d1361) | Jul 29, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [a0ebe8cf5a](https://linux-hardware.org/?probe=a0ebe8cf5a) | Jul 20, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| Lenovo        | ThinkCentre M91 7516AD1     | Desktop     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| Intel         | powered classmate PC        | Tablet      | [1abacce964](https://linux-hardware.org/?probe=1abacce964) | Jul 06, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2919feb689](https://linux-hardware.org/?probe=2919feb689) | Jul 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [dee20b535f](https://linux-hardware.org/?probe=dee20b535f) | Jul 04, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2933dddc75](https://linux-hardware.org/?probe=2933dddc75) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| MSI           | H81M-E33                    | Desktop     | [737e14fea7](https://linux-hardware.org/?probe=737e14fea7) | Jul 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [d7282a0f61](https://linux-hardware.org/?probe=d7282a0f61) | Jun 29, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [e4dd9b130e](https://linux-hardware.org/?probe=e4dd9b130e) | Jun 29, 2022 |
| Pegatron      | IPPSB-DB                    | Desktop     | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [c3e90d4ebd](https://linux-hardware.org/?probe=c3e90d4ebd) | Jun 26, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| ASRock        | H370M-HDV                   | Desktop     | [4d6a88cd74](https://linux-hardware.org/?probe=4d6a88cd74) | Jun 16, 2022 |
| Google        | Cyan                        | Notebook    | [7b82520717](https://linux-hardware.org/?probe=7b82520717) | Jun 13, 2022 |
| langchao      | IPM41-D3                    | Desktop     | [bb1a55c140](https://linux-hardware.org/?probe=bb1a55c140) | Jun 13, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [5d8aa17afc](https://linux-hardware.org/?probe=5d8aa17afc) | Jun 10, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [a502ed154f](https://linux-hardware.org/?probe=a502ed154f) | Jun 10, 2022 |
| VIT           | M2420                       | Notebook    | [8152d4c61b](https://linux-hardware.org/?probe=8152d4c61b) | Jun 08, 2022 |
| VIT           | M2420                       | Notebook    | [d09de8cbd7](https://linux-hardware.org/?probe=d09de8cbd7) | Jun 07, 2022 |
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
| Ubuntu 20.04                 | 22        | 9.17%   |
| Debian 11                    | 22        | 9.17%   |
| Ubuntu 18.04                 | 17        | 7.08%   |
| OpenMandriva 4.3             | 13        | 5.42%   |
| Debian 10                    | 10        | 4.17%   |
| OpenMandriva 4.2             | 9         | 3.75%   |
| KDE neon 20.04               | 8         | 3.33%   |
| Xubuntu 18.04                | 6         | 2.5%    |
| Kubuntu 20.04                | 6         | 2.5%    |
| ROSA R9                      | 5         | 2.08%   |
| ROSA R11                     | 5         | 2.08%   |
| Linux Mint 20                | 5         | 2.08%   |
| Linux Mint 19.3              | 5         | 2.08%   |
| Zorin 16                     | 4         | 1.67%   |
| Ubuntu MATE 19.10            | 4         | 1.67%   |
| Ubuntu 22.04                 | 4         | 1.67%   |
| Ubuntu 19.10                 | 4         | 1.67%   |
| Linux Mint 20.3              | 4         | 1.67%   |
| Fedora 35                    | 4         | 1.67%   |
| Zorin 15                     | 3         | 1.25%   |
| Manjaro                      | 3         | 1.25%   |
| KDE neon 18.04               | 3         | 1.25%   |
| Arch Rolling                 | 3         | 1.25%   |
| Xubuntu 20.04                | 2         | 0.83%   |
| Xubuntu 16.04                | 2         | 0.83%   |
| Ubuntu 21.10                 | 2         | 0.83%   |
| Ubuntu 20.10                 | 2         | 0.83%   |
| Ubuntu 16.04                 | 2         | 0.83%   |
| Pop!_OS 22.04                | 2         | 0.83%   |
| Pop!_OS 21.04                | 2         | 0.83%   |
| OpenMandriva 4.50            | 2         | 0.83%   |
| Linux Mint 20.1              | 2         | 0.83%   |
| Fedora 36                    | 2         | 0.83%   |
| Fedora 34                    | 2         | 0.83%   |
| Arch                         | 2         | 0.83%   |
| Xubuntu 21.10                | 1         | 0.42%   |
| Ubuntu MATE 20.04            | 1         | 0.42%   |
| Ubuntu 19.04                 | 1         | 0.42%   |
| Sparky 5.12                  | 1         | 0.42%   |
| Solus 4.3                    | 1         | 0.42%   |
| Solus 4.1                    | 1         | 0.42%   |
| ROSA R8                      | 1         | 0.42%   |
| ROSA R11.1                   | 1         | 0.42%   |
| ROSA 12.1                    | 1         | 0.42%   |
| Q4OS 4                       | 1         | 0.42%   |
| Pop!_OS 20.04                | 1         | 0.42%   |
| PCLinuxOS 2022               | 1         | 0.42%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.42%   |
| MX 21                        | 1         | 0.42%   |
| MX 20                        | 1         | 0.42%   |
| Manjaro 21.2.0               | 1         | 0.42%   |
| Manjaro 21.1.0               | 1         | 0.42%   |
| Manjaro 21.0                 | 1         | 0.42%   |
| Manjaro 20.2.1               | 1         | 0.42%   |
| Manjaro 20.1                 | 1         | 0.42%   |
| Lubuntu 18.04                | 1         | 0.42%   |
| LMDE 5                       | 1         | 0.42%   |
| LMDE 4                       | 1         | 0.42%   |
| Linux Mint 21                | 1         | 0.42%   |
| Linux Mint 20.2              | 1         | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 51        | 22.17%  |
| Debian       | 33        | 14.35%  |
| OpenMandriva | 24        | 10.43%  |
| Linux Mint   | 19        | 8.26%   |
| ROSA         | 13        | 5.65%   |
| Xubuntu      | 10        | 4.35%   |
| KDE neon     | 10        | 4.35%   |
| Fedora       | 9         | 3.91%   |
| Manjaro      | 8         | 3.48%   |
| Zorin        | 7         | 3.04%   |
| Kubuntu      | 6         | 2.61%   |
| Ubuntu MATE  | 5         | 2.17%   |
| Pop!_OS      | 5         | 2.17%   |
| Arch         | 5         | 2.17%   |
| Elementary   | 3         | 1.3%    |
| Solus        | 2         | 0.87%   |
| MX           | 2         | 0.87%   |
| LMDE         | 2         | 0.87%   |
| Garuda Linux | 2         | 0.87%   |
| Feren OS     | 2         | 0.87%   |
| Sparky       | 1         | 0.43%   |
| Q4OS         | 1         | 0.43%   |
| PCLinuxOS    | 1         | 0.43%   |
| openSUSE     | 1         | 0.43%   |
| Lubuntu      | 1         | 0.43%   |
| Linux Lite   | 1         | 0.43%   |
| Kali         | 1         | 0.43%   |
| Endless      | 1         | 0.43%   |
| Deepin       | 1         | 0.43%   |
| ArcoLinux    | 1         | 0.43%   |
| Alpine       | 1         | 0.43%   |
| AlmaLinux    | 1         | 0.43%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                  | Computers | Percent |
|------------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003                  | 13        | 4.98%   |
| 5.10.14-desktop-1omv4002                 | 9         | 3.45%   |
| 5.4.0-42-generic                         | 8         | 3.07%   |
| 5.3.0-40-generic                         | 6         | 2.3%    |
| 5.4.0-77-generic                         | 4         | 1.53%   |
| 5.13.0-39-generic                        | 4         | 1.53%   |
| 5.10.0-16-amd64                          | 4         | 1.53%   |
| 5.10.0-13-amd64                          | 4         | 1.53%   |
| 5.10.0-11-amd64                          | 4         | 1.53%   |
| 5.0.0-37-generic                         | 4         | 1.53%   |
| 4.9.20-nrj-desktop-1rosa-x86_64          | 4         | 1.53%   |
| 4.19.0-17-amd64                          | 4         | 1.53%   |
| 5.4.0-73-generic                         | 3         | 1.15%   |
| 5.4.0-52-generic                         | 3         | 1.15%   |
| 5.3.0-29-generic                         | 3         | 1.15%   |
| 5.15.0-46-generic                        | 3         | 1.15%   |
| 5.11.0-37-generic                        | 3         | 1.15%   |
| 5.10.0-15-amd64                          | 3         | 1.15%   |
| 4.15.0-48-generic                        | 3         | 1.15%   |
| 5.8.0-55-generic                         | 2         | 0.77%   |
| 5.8.0-44-generic                         | 2         | 0.77%   |
| 5.4.0-89-generic                         | 2         | 0.77%   |
| 5.4.0-74-generic                         | 2         | 0.77%   |
| 5.4.0-66-generic                         | 2         | 0.77%   |
| 5.4.0-54-generic                         | 2         | 0.77%   |
| 5.4.0-48-generic                         | 2         | 0.77%   |
| 5.4.0-31-generic                         | 2         | 0.77%   |
| 5.4.0-26-generic                         | 2         | 0.77%   |
| 5.4.0-107-generic                        | 2         | 0.77%   |
| 5.3.0-42-generic                         | 2         | 0.77%   |
| 5.15.0-43-generic                        | 2         | 0.77%   |
| 5.14.10-300.fc35.x86_64                  | 2         | 0.77%   |
| 5.13.0-52-generic                        | 2         | 0.77%   |
| 5.13.0-51-generic                        | 2         | 0.77%   |
| 5.13.0-27-generic                        | 2         | 0.77%   |
| 5.12.4-desktop-1omv4050                  | 2         | 0.77%   |
| 5.10.0-8-amd64                           | 2         | 0.77%   |
| 5.10.0-14-amd64                          | 2         | 0.77%   |
| 5.10.0-12-amd64                          | 2         | 0.77%   |
| 4.15.0-desktop-45.1rosa-x86_64           | 2         | 0.77%   |
| 4.15.0-96-generic                        | 2         | 0.77%   |
| 4.15.0-112-generic                       | 2         | 0.77%   |
| 5.9.16-1-MANJARO                         | 1         | 0.38%   |
| 5.9.0-5-amd64                            | 1         | 0.38%   |
| 5.8.6-1-MANJARO                          | 1         | 0.38%   |
| 5.8.11-arch1-1                           | 1         | 0.38%   |
| 5.8.10-17-tkg-bmq                        | 1         | 0.38%   |
| 5.8.0-63-generic                         | 1         | 0.38%   |
| 5.8.0-59-generic                         | 1         | 0.38%   |
| 5.8.0-53-generic                         | 1         | 0.38%   |
| 5.8.0-45-generic                         | 1         | 0.38%   |
| 5.8.0-41-generic                         | 1         | 0.38%   |
| 5.8.0-40-generic                         | 1         | 0.38%   |
| 5.7.0-1.vanilla.1.fc31.x86_64            | 1         | 0.38%   |
| 5.6.6-1-default                          | 1         | 0.38%   |
| 5.6.18-155.current                       | 1         | 0.38%   |
| 5.6.0-1-amd64                            | 1         | 0.38%   |
| 5.5.4-linux-xanmod-1-rosa-x86_64-xanmod3 | 1         | 0.38%   |
| 5.4.83-0-lts                             | 1         | 0.38%   |
| 5.4.105-1-MANJARO                        | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 45        | 18.6%   |
| 4.15.0  | 23        | 9.5%    |
| 5.10.0  | 22        | 9.09%   |
| 5.13.0  | 18        | 7.44%   |
| 5.16.7  | 13        | 5.37%   |
| 5.3.0   | 12        | 4.96%   |
| 4.19.0  | 12        | 4.96%   |
| 5.8.0   | 9         | 3.72%   |
| 5.11.0  | 9         | 3.72%   |
| 5.10.14 | 9         | 3.72%   |
| 5.15.0  | 7         | 2.89%   |
| 5.0.0   | 7         | 2.89%   |
| 4.9.20  | 5         | 2.07%   |
| 5.14.10 | 3         | 1.24%   |
| 5.15.6  | 2         | 0.83%   |
| 5.12.4  | 2         | 0.83%   |
| 4.9.0   | 2         | 0.83%   |
| 4.18.0  | 2         | 0.83%   |
| 5.9.16  | 1         | 0.41%   |
| 5.9.0   | 1         | 0.41%   |
| 5.8.6   | 1         | 0.41%   |
| 5.8.11  | 1         | 0.41%   |
| 5.8.10  | 1         | 0.41%   |
| 5.7.0   | 1         | 0.41%   |
| 5.6.6   | 1         | 0.41%   |
| 5.6.18  | 1         | 0.41%   |
| 5.6.0   | 1         | 0.41%   |
| 5.5.4   | 1         | 0.41%   |
| 5.4.83  | 1         | 0.41%   |
| 5.4.105 | 1         | 0.41%   |
| 5.18.7  | 1         | 0.41%   |
| 5.17.2  | 1         | 0.41%   |
| 5.17.15 | 1         | 0.41%   |
| 5.17.12 | 1         | 0.41%   |
| 5.17.11 | 1         | 0.41%   |
| 5.16.16 | 1         | 0.41%   |
| 5.16.14 | 1         | 0.41%   |
| 5.15.8  | 1         | 0.41%   |
| 5.15.57 | 1         | 0.41%   |
| 5.15.48 | 1         | 0.41%   |
| 5.15.46 | 1         | 0.41%   |
| 5.15.28 | 1         | 0.41%   |
| 5.15.2  | 1         | 0.41%   |
| 5.15.19 | 1         | 0.41%   |
| 5.15.13 | 1         | 0.41%   |
| 5.15.10 | 1         | 0.41%   |
| 5.13.16 | 1         | 0.41%   |
| 5.13.13 | 1         | 0.41%   |
| 5.13.1  | 1         | 0.41%   |
| 5.12.19 | 1         | 0.41%   |
| 5.10.74 | 1         | 0.41%   |
| 5.10.5  | 1         | 0.41%   |
| 5.10.3  | 1         | 0.41%   |
| 5.10.11 | 1         | 0.41%   |
| 5.10.10 | 1         | 0.41%   |
| 4.4.0   | 1         | 0.41%   |
| 4.13.0  | 1         | 0.41%   |
| 4.1.15  | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 47        | 19.58%  |
| 5.10    | 36        | 15%     |
| 4.15    | 23        | 9.58%   |
| 5.13    | 21        | 8.75%   |
| 5.15    | 16        | 6.67%   |
| 5.16    | 15        | 6.25%   |
| 5.8     | 12        | 5%      |
| 5.3     | 12        | 5%      |
| 4.19    | 12        | 5%      |
| 5.11    | 9         | 3.75%   |
| 5.0     | 7         | 2.92%   |
| 4.9     | 7         | 2.92%   |
| 5.17    | 4         | 1.67%   |
| 5.6     | 3         | 1.25%   |
| 5.14    | 3         | 1.25%   |
| 5.12    | 3         | 1.25%   |
| 5.9     | 2         | 0.83%   |
| 4.18    | 2         | 0.83%   |
| 5.7     | 1         | 0.42%   |
| 5.5     | 1         | 0.42%   |
| 5.18    | 1         | 0.42%   |
| 4.4     | 1         | 0.42%   |
| 4.13    | 1         | 0.42%   |
| 4.1     | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 198       | 88.79%  |
| i686   | 25        | 11.21%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 66        | 27.97%  |
| KDE5            | 51        | 21.61%  |
| XFCE            | 32        | 13.56%  |
| Unknown         | 24        | 10.17%  |
| MATE            | 12        | 5.08%   |
| KDE             | 12        | 5.08%   |
| X-Cinnamon      | 10        | 4.24%   |
| KDE4            | 7         | 2.97%   |
| LXDE            | 4         | 1.69%   |
| Cinnamon        | 4         | 1.69%   |
| Unity           | 3         | 1.27%   |
| Pantheon        | 2         | 0.85%   |
| LXQt            | 2         | 0.85%   |
| GNOME Classic   | 2         | 0.85%   |
| Budgie          | 2         | 0.85%   |
| xmonad          | 1         | 0.42%   |
| GNOME Flashback | 1         | 0.42%   |
| Deepin          | 1         | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 196       | 87.5%   |
| Wayland | 21        | 9.38%   |
| Unknown | 5         | 2.23%   |
| Tty     | 2         | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 100       | 43.48%  |
| SDDM    | 47        | 20.43%  |
| GDM     | 28        | 12.17%  |
| LightDM | 26        | 11.3%   |
| GDM3    | 11        | 4.78%   |
| TDM     | 10        | 4.35%   |
| KDM     | 7         | 3.04%   |
| SLiM    | 1         | 0.43%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_VE   | 131       | 57.46%  |
| en_US   | 53        | 23.25%  |
| Unknown | 25        | 10.96%  |
| es_ES   | 13        | 5.7%    |
| es_US   | 2         | 0.88%   |
| C       | 2         | 0.88%   |
| en_CA   | 1         | 0.44%   |
| de_DE   | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 173       | 76.89%  |
| EFI  | 52        | 23.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 176       | 78.57%  |
| Overlay | 23        | 10.27%  |
| Btrfs   | 11        | 4.91%   |
| Unknown | 8         | 3.57%   |
| Xfs     | 4         | 1.79%   |
| Ext2    | 2         | 0.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 117       | 51.54%  |
| MBR     | 67        | 29.52%  |
| GPT     | 43        | 18.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 188       | 83.19%  |
| Yes       | 38        | 16.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 136       | 60.99%  |
| Yes       | 87        | 39.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 28        | 12.67%  |
| Dell                | 23        | 10.41%  |
| Intel               | 21        | 9.5%    |
| Hewlett-Packard     | 20        | 9.05%   |
| VIT                 | 19        | 8.6%    |
| ASRock              | 19        | 8.6%    |
| ASUSTek Computer    | 16        | 7.24%   |
| Pegatron            | 11        | 4.98%   |
| ECS                 | 11        | 4.98%   |
| Biostar             | 7         | 3.17%   |
| MSI                 | 5         | 2.26%   |
| Gigabyte Technology | 5         | 2.26%   |
| Unknown             | 5         | 2.26%   |
| langchao            | 4         | 1.81%   |
| Foxconn             | 4         | 1.81%   |
| Apple               | 4         | 1.81%   |
| Acer                | 4         | 1.81%   |
| UNIQCELL            | 1         | 0.45%   |
| Toshiba             | 1         | 0.45%   |
| Standard            | 1         | 0.45%   |
| Sony                | 1         | 0.45%   |
| Samsung Electronics | 1         | 0.45%   |
| IP3 Tech            | 1         | 0.45%   |
| Inspur              | 1         | 0.45%   |
| IBM                 | 1         | 0.45%   |
| GPU Company         | 1         | 0.45%   |
| Google              | 1         | 0.45%   |
| Gateway             | 1         | 0.45%   |
| Exo                 | 1         | 0.45%   |
| Clevo               | 1         | 0.45%   |
| AVITA               | 1         | 0.45%   |
| Alienware           | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel powered classmate PC           | 9         | 4.07%   |
| ECS H61H2-CM                         | 6         | 2.71%   |
| VIT P2400                            | 5         | 2.26%   |
| ASRock G41M-VS3                      | 5         | 2.26%   |
| Unknown                              | 5         | 2.26%   |
| langchao 12345                       | 4         | 1.81%   |
| VIT P3400                            | 3         | 1.36%   |
| VIT P2402                            | 3         | 1.36%   |
| VIT M2420                            | 3         | 1.36%   |
| VIT M2421                            | 2         | 0.9%    |
| Pegatron Compaq dx2400 Microtower    | 2         | 0.9%    |
| Lenovo IdeaPad S100c 20194           | 2         | 0.9%    |
| Lenovo 3000 N200 0769ARS             | 2         | 0.9%    |
| Dell Inspiron 1545                   | 2         | 0.9%    |
| ASRock N68C-S UCC                    | 2         | 0.9%    |
| ASRock N68-VS3 UCC                   | 2         | 0.9%    |
| Apple iMac11,2                       | 2         | 0.9%    |
| VIT P1400                            | 1         | 0.45%   |
| VIT NP3020M3                         | 1         | 0.45%   |
| VIT Aptio CRB                        | 1         | 0.45%   |
| UNIQCELL Q15.6                       | 1         | 0.45%   |
| Toshiba Satellite E55t-A             | 1         | 0.45%   |
| Standard AIO                         | 1         | 0.45%   |
| Sony VGN-FW510F                      | 1         | 0.45%   |
| Samsung 355V4C/356V4C/3445VC/3545VC  | 1         | 0.45%   |
| Pegatron T14AF                       | 1         | 0.45%   |
| Pegatron PEGATRON                    | 1         | 0.45%   |
| Pegatron IPPEL-DB                    | 1         | 0.45%   |
| Pegatron IPM41-D3                    | 1         | 0.45%   |
| Pegatron CQ1507LA                    | 1         | 0.45%   |
| Pegatron Compaq dx2400 Microtower PC | 1         | 0.45%   |
| Pegatron BM411AA-ABA CQ5600F         | 1         | 0.45%   |
| Pegatron 20-b010                     | 1         | 0.45%   |
| Pegatron 100-5010la                  | 1         | 0.45%   |
| MSI Pro 3000 Microtower PC           | 1         | 0.45%   |
| MSI MS-7817                          | 1         | 0.45%   |
| MSI MS-7721                          | 1         | 0.45%   |
| MSI MS-7375                          | 1         | 0.45%   |
| MSI MS-1454                          | 1         | 0.45%   |
| Lenovo Z50-75 80EC                   | 1         | 0.45%   |
| Lenovo ThinkPad X201 3680AE2         | 1         | 0.45%   |
| Lenovo ThinkPad SL400 2743A48        | 1         | 0.45%   |
| Lenovo ThinkPad Edge 01962AS         | 1         | 0.45%   |
| Lenovo ThinkPad E560 20EV002FUS      | 1         | 0.45%   |
| Lenovo ThinkCentre XXXX 8705A84      | 1         | 0.45%   |
| Lenovo ThinkCentre M91 7516AD1       | 1         | 0.45%   |
| Lenovo ThinkCentre M71e 3157G6S      | 1         | 0.45%   |
| Lenovo ThinkCentre M55E 9645BN2      | 1         | 0.45%   |
| Lenovo ThinkCentre M55E 9632BU8      | 1         | 0.45%   |
| Lenovo ThinkCentre A58 7515A33       | 1         | 0.45%   |
| Lenovo ThinkCentre A55 8705AV4       | 1         | 0.45%   |
| Lenovo IdeaPad S110 20126            | 1         | 0.45%   |
| Lenovo IdeaPad 5 14ALC05 82LM        | 1         | 0.45%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 0.45%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 1         | 0.45%   |
| Lenovo IdeaPad 1 14IGL05 81VU        | 1         | 0.45%   |
| Lenovo H220 10028                    | 1         | 0.45%   |
| Lenovo G570 4334                     | 1         | 0.45%   |
| Lenovo G480 20150                    | 1         | 0.45%   |
| Lenovo G460 20041                    | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 10        | 4.52%   |
| Intel powered        | 9         | 4.07%   |
| HP Compaq            | 8         | 3.62%   |
| Lenovo ThinkCentre   | 7         | 3.17%   |
| Lenovo IdeaPad       | 7         | 3.17%   |
| HP Pavilion          | 6         | 2.71%   |
| ECS H61H2-CM         | 6         | 2.71%   |
| VIT P2400            | 5         | 2.26%   |
| ASRock G41M-VS3      | 5         | 2.26%   |
| Unknown              | 5         | 2.26%   |
| Lenovo ThinkPad      | 4         | 1.81%   |
| langchao 12345       | 4         | 1.81%   |
| Dell Vostro          | 4         | 1.81%   |
| Dell Latitude        | 4         | 1.81%   |
| VIT P3400            | 3         | 1.36%   |
| VIT P2402            | 3         | 1.36%   |
| VIT M2420            | 3         | 1.36%   |
| Pegatron Compaq      | 3         | 1.36%   |
| Acer Aspire          | 3         | 1.36%   |
| VIT M2421            | 2         | 0.9%    |
| Lenovo 3000          | 2         | 0.9%    |
| HP Presario          | 2         | 0.9%    |
| Dell Precision       | 2         | 0.9%    |
| Dell OptiPlex        | 2         | 0.9%    |
| ASUS VivoBook        | 2         | 0.9%    |
| ASUS P5G41T-M        | 2         | 0.9%    |
| ASUS ASUS            | 2         | 0.9%    |
| ASRock N68C-S        | 2         | 0.9%    |
| ASRock N68-VS3       | 2         | 0.9%    |
| Apple iMac11         | 2         | 0.9%    |
| VIT P1400            | 1         | 0.45%   |
| VIT NP3020M3         | 1         | 0.45%   |
| VIT Aptio            | 1         | 0.45%   |
| UNIQCELL Q15.6       | 1         | 0.45%   |
| Toshiba Satellite    | 1         | 0.45%   |
| Standard AIO         | 1         | 0.45%   |
| Sony VGN-FW510F      | 1         | 0.45%   |
| Samsung 355V4C       | 1         | 0.45%   |
| Pegatron T14AF       | 1         | 0.45%   |
| Pegatron PEGATRON    | 1         | 0.45%   |
| Pegatron IPPEL-DB    | 1         | 0.45%   |
| Pegatron IPM41-D3    | 1         | 0.45%   |
| Pegatron CQ1507LA    | 1         | 0.45%   |
| Pegatron BM411AA-ABA | 1         | 0.45%   |
| Pegatron 20-b010     | 1         | 0.45%   |
| Pegatron 100-5010la  | 1         | 0.45%   |
| MSI Pro              | 1         | 0.45%   |
| MSI MS-7817          | 1         | 0.45%   |
| MSI MS-7721          | 1         | 0.45%   |
| MSI MS-7375          | 1         | 0.45%   |
| MSI MS-1454          | 1         | 0.45%   |
| Lenovo Z50-75        | 1         | 0.45%   |
| Lenovo H220          | 1         | 0.45%   |
| Lenovo G570          | 1         | 0.45%   |
| Lenovo G480          | 1         | 0.45%   |
| Lenovo G460          | 1         | 0.45%   |
| Lenovo B40-70        | 1         | 0.45%   |
| Lenovo 70A4000HUX    | 1         | 0.45%   |
| Lenovo 11051CS       | 1         | 0.45%   |
| IP3 Tech TB20        | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 38        | 17.19%  |
| 2010    | 37        | 16.74%  |
| 2012    | 25        | 11.31%  |
| 2008    | 19        | 8.6%    |
| 2007    | 19        | 8.6%    |
| 2013    | 16        | 7.24%   |
| 2014    | 13        | 5.88%   |
| 2006    | 8         | 3.62%   |
| 2018    | 7         | 3.17%   |
| 2021    | 6         | 2.71%   |
| 2020    | 6         | 2.71%   |
| 2017    | 6         | 2.71%   |
| 2015    | 6         | 2.71%   |
| 2009    | 5         | 2.26%   |
| 2019    | 3         | 1.36%   |
| 2016    | 3         | 1.36%   |
| 2022    | 2         | 0.9%    |
| 2005    | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 109       | 49.32%  |
| Notebook   | 98        | 44.34%  |
| All in one | 6         | 2.71%   |
| Tablet     | 4         | 1.81%   |
| Server     | 3         | 1.36%   |
| Mini pc    | 1         | 0.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 217       | 98.19%  |
| Enabled  | 4         | 1.81%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 220       | 99.55%  |
| Yes  | 1         | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 60        | 26.67%  |
| 4.01-8.0   | 49        | 21.78%  |
| 1.01-2.0   | 46        | 20.44%  |
| 8.01-16.0  | 32        | 14.22%  |
| 16.01-24.0 | 19        | 8.44%   |
| 2.01-3.0   | 9         | 4%      |
| 32.01-64.0 | 4         | 1.78%   |
| 24.01-32.0 | 3         | 1.33%   |
| 0.51-1.0   | 3         | 1.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 101       | 41.22%  |
| 2.01-3.0   | 59        | 24.08%  |
| 0.51-1.0   | 36        | 14.69%  |
| 4.01-8.0   | 25        | 10.2%   |
| 3.01-4.0   | 17        | 6.94%   |
| 0.01-0.5   | 4         | 1.63%   |
| 8.01-16.0  | 2         | 0.82%   |
| 16.01-24.0 | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 145       | 63.88%  |
| 2      | 63        | 27.75%  |
| 3      | 16        | 7.05%   |
| 4      | 2         | 0.88%   |
| 6      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 113       | 50.22%  |
| Yes       | 112       | 49.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 209       | 94.14%  |
| No        | 13        | 5.86%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 72.65%  |
| No        | 61        | 27.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 152       | 67.86%  |
| Yes       | 72        | 32.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Venezuela | 221       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 107       | 44.58%  |
| Maracaibo                  | 17        | 7.08%   |
| Maracay                    | 13        | 5.42%   |
| Valencia                   | 9         | 3.75%   |
| Mérida                    | 9         | 3.75%   |
| San Cristóbal             | 8         | 3.33%   |
| Barquisimeto               | 8         | 3.33%   |
| Barcelona                  | 7         | 2.92%   |
| San Carlos del Zulia       | 5         | 2.08%   |
| Maturín                   | 5         | 2.08%   |
| Barinas                    | 4         | 1.67%   |
| Parroquia El Recreo        | 3         | 1.25%   |
| Lecherias                  | 3         | 1.25%   |
| Ciudad Bolívar            | 3         | 1.25%   |
| Carrizal                   | 3         | 1.25%   |
| San Juan Bautista          | 2         | 0.83%   |
| San Antonio de Los Altos   | 2         | 0.83%   |
| Los Teques                 | 2         | 0.83%   |
| Los Palos Grandes          | 2         | 0.83%   |
| Guatire                    | 2         | 0.83%   |
| Guarenas                   | 2         | 0.83%   |
| Ciudad Guayana             | 2         | 0.83%   |
| Valle de La Pascua         | 1         | 0.42%   |
| Tucape                     | 1         | 0.42%   |
| Santa Rita                 | 1         | 0.42%   |
| San Francisco              | 1         | 0.42%   |
| San Diego                  | 1         | 0.42%   |
| Puerto Ordaz and San Felix | 1         | 0.42%   |
| Puerto Cumarebo            | 1         | 0.42%   |
| Puerto Cruz                | 1         | 0.42%   |
| Porlamar                   | 1         | 0.42%   |
| Mariara                    | 1         | 0.42%   |
| Las Vegas                  | 1         | 0.42%   |
| Guanare                    | 1         | 0.42%   |
| El Hatillo Municipality    | 1         | 0.42%   |
| Ejido                      | 1         | 0.42%   |
| Cua                        | 1         | 0.42%   |
| Charallave                 | 1         | 0.42%   |
| Carora                     | 1         | 0.42%   |
| Cagua                      | 1         | 0.42%   |
| Cabimas                    | 1         | 0.42%   |
| Baruta                     | 1         | 0.42%   |
| Anaco                      | 1         | 0.42%   |
| Acarigua                   | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 73        | 102    | 25.98%  |
| Seagate             | 70        | 108    | 24.91%  |
| Hitachi             | 29        | 42     | 10.32%  |
| Toshiba             | 22        | 23     | 7.83%   |
| Samsung Electronics | 20        | 23     | 7.12%   |
| Kingston            | 10        | 11     | 3.56%   |
| Unknown             | 6         | 8      | 2.14%   |
| Crucial             | 6         | 7      | 2.14%   |
| SanDisk             | 4         | 5      | 1.42%   |
| Maxtor              | 4         | 4      | 1.42%   |
| LITEONIT            | 4         | 7      | 1.42%   |
| SPCC                | 3         | 4      | 1.07%   |
| SK hynix            | 3         | 3      | 1.07%   |
| PNY                 | 3         | 3      | 1.07%   |
| Intel               | 3         | 6      | 1.07%   |
| HGST                | 3         | 3      | 1.07%   |
| Fujitsu             | 3         | 3      | 1.07%   |
| Patriot             | 2         | 2      | 0.71%   |
| Vaseky              | 1         | 1      | 0.36%   |
| Team                | 1         | 1      | 0.36%   |
| Silicon Motion      | 1         | 1      | 0.36%   |
| Phison              | 1         | 1      | 0.36%   |
| Micron Technology   | 1         | 3      | 0.36%   |
| KingFast            | 1         | 2      | 0.36%   |
| Intenso             | 1         | 1      | 0.36%   |
| ExcelStor           | 1         | 1      | 0.36%   |
| Dogfish             | 1         | 1      | 0.36%   |
| Dell                | 1         | 2      | 0.36%   |
| BIWIN               | 1         | 2      | 0.36%   |
| Apacer              | 1         | 1      | 0.36%   |
| addlink             | 1         | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 12        | 3.86%   |
| Toshiba DT01ACA050 500GB            | 7         | 2.25%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 4         | 1.29%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 4         | 1.29%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 1.29%   |
| Seagate ST3320418AS 320GB           | 4         | 1.29%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4         | 1.29%   |
| Seagate ST320LM000 HM321HI 320GB    | 4         | 1.29%   |
| Kingston SA400S37240G 240GB SSD     | 4         | 1.29%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 0.96%   |
| WDC WD5000AAKX-221CA1 500GB         | 3         | 0.96%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3         | 0.96%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 0.96%   |
| WDC WD3200AAJS-08L7A0 320GB         | 3         | 0.96%   |
| WDC WD3200AAJS-00L7A0 320GB         | 3         | 0.96%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 0.96%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 0.96%   |
| Seagate ST250LM004 HN-M250MBB 250GB | 3         | 0.96%   |
| Samsung HD502HJ 500GB               | 3         | 0.96%   |
| Samsung HD161HJ 160GB               | 3         | 0.96%   |
| LITEONIT LMS-32L6M 32GB SSD         | 3         | 0.96%   |
| Hitachi HTS542580K9SA00 80GB        | 3         | 0.96%   |
| WDC WD800BD-22MRA1 80GB             | 2         | 0.64%   |
| WDC WD800BB-22JHC0 80GB             | 2         | 0.64%   |
| WDC WD5000LPVT-08G33T1 500GB        | 2         | 0.64%   |
| WDC WD5000AAKX-001CA0 500GB         | 2         | 0.64%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 2         | 0.64%   |
| WDC WD2500AAJS-60B4A0 250GB         | 2         | 0.64%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.64%   |
| Toshiba MQ01ABF032 320GB            | 2         | 0.64%   |
| Toshiba MQ01ABD050 500GB            | 2         | 0.64%   |
| SPCC Solid State Disk 128GB         | 2         | 0.64%   |
| SK hynix SC300B SATA 512GB SSD      | 2         | 0.64%   |
| Seagate ST9160314AS 160GB           | 2         | 0.64%   |
| Seagate ST3250310AS 250GB           | 2         | 0.64%   |
| Seagate ST320LT012-9WS14C 320GB     | 2         | 0.64%   |
| Seagate ST2000DM001-1CH164 2TB      | 2         | 0.64%   |
| Seagate ST1000NM0011 1TB            | 2         | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.64%   |
| SanDisk NVMe SSD Drive 1TB          | 2         | 0.64%   |
| Samsung HN-M320MBB 320GB            | 2         | 0.64%   |
| Samsung HM321HI 320GB               | 2         | 0.64%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 0.64%   |
| Hitachi HTS545032B9A300 320GB       | 2         | 0.64%   |
| Hitachi HDS721616PLA380 160GB       | 2         | 0.64%   |
| Hitachi HDS721032CLA362 320GB       | 2         | 0.64%   |
| HGST HTS721010A9E630 1TB            | 2         | 0.64%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 0.64%   |
| WDC WDS500G2B0C-00PXH0 500GB        | 1         | 0.32%   |
| WDC WD800JD-60LSA5 80GB             | 1         | 0.32%   |
| WDC WD800BD-08MRA1 80GB             | 1         | 0.32%   |
| WDC WD5000LPCX-22VHAT0 500GB        | 1         | 0.32%   |
| WDC WD5000BPVT-24HXZT3 500GB        | 1         | 0.32%   |
| WDC WD5000AVCS-632DY1 500GB         | 1         | 0.32%   |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 0.32%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 1         | 0.32%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1         | 0.32%   |
| WDC WD5000AAJS-08A8B0 500GB         | 1         | 0.32%   |
| WDC WD5000AACS-61M6B2 500GB         | 1         | 0.32%   |
| WDC WD5000AACS-22ZUB0 500GB         | 1         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 72        | 100    | 33.03%  |
| Seagate             | 68        | 106    | 31.19%  |
| Hitachi             | 29        | 42     | 13.3%   |
| Toshiba             | 21        | 22     | 9.63%   |
| Samsung Electronics | 15        | 18     | 6.88%   |
| Maxtor              | 4         | 4      | 1.83%   |
| HGST                | 3         | 3      | 1.38%   |
| Fujitsu             | 3         | 3      | 1.38%   |
| Unknown             | 2         | 2      | 0.92%   |
| ExcelStor           | 1         | 1      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 9         | 10     | 20.93%  |
| Crucial             | 6         | 7      | 13.95%  |
| LITEONIT            | 4         | 7      | 9.3%    |
| SPCC                | 3         | 4      | 6.98%   |
| Samsung Electronics | 3         | 3      | 6.98%   |
| PNY                 | 3         | 3      | 6.98%   |
| SK hynix            | 2         | 2      | 4.65%   |
| SanDisk             | 2         | 3      | 4.65%   |
| Patriot             | 2         | 2      | 4.65%   |
| Vaseky              | 1         | 1      | 2.33%   |
| Toshiba             | 1         | 1      | 2.33%   |
| Team                | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 3      | 2.33%   |
| KingFast            | 1         | 2      | 2.33%   |
| Intenso             | 1         | 1      | 2.33%   |
| Dogfish             | 1         | 1      | 2.33%   |
| Dell                | 1         | 2      | 2.33%   |
| BIWIN               | 1         | 2      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 178       | 301    | 74.79%  |
| SSD     | 41        | 55     | 17.23%  |
| NVMe    | 13        | 19     | 5.46%   |
| MMC     | 4         | 5      | 1.68%   |
| Unknown | 2         | 2      | 0.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 206       | 353    | 90.35%  |
| NVMe | 13        | 19     | 5.7%    |
| SAS  | 5         | 5      | 2.19%   |
| MMC  | 4         | 5      | 1.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 190       | 284    | 80.85%  |
| 0.51-1.0   | 31        | 50     | 13.19%  |
| 1.01-2.0   | 10        | 17     | 4.26%   |
| 3.01-4.0   | 2         | 2      | 0.85%   |
| 2.01-3.0   | 2         | 3      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 77        | 32.49%  |
| 101-250        | 56        | 23.63%  |
| 501-1000       | 33        | 13.92%  |
| 1-20           | 22        | 9.28%   |
| 51-100         | 20        | 8.44%   |
| 21-50          | 12        | 5.06%   |
| 1001-2000      | 8         | 3.38%   |
| 2001-3000      | 4         | 1.69%   |
| Unknown        | 3         | 1.27%   |
| More than 3000 | 2         | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 98        | 40.66%  |
| 21-50          | 42        | 17.43%  |
| 101-250        | 34        | 14.11%  |
| 51-100         | 25        | 10.37%  |
| 251-500        | 21        | 8.71%   |
| 501-1000       | 11        | 4.56%   |
| 2001-3000      | 3         | 1.24%   |
| Unknown        | 3         | 1.24%   |
| More than 3000 | 2         | 0.83%   |
| 1001-2000      | 2         | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB         | 5         | 6      | 7.35%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 2         | 3      | 2.94%   |
| WDC WD5000AAKX-221CA1 500GB             | 2         | 2      | 2.94%   |
| WDC WD5000AAKS-00A7B0 500GB             | 2         | 2      | 2.94%   |
| Toshiba DT01ACA050 500GB                | 2         | 3      | 2.94%   |
| Seagate ST500DM002-1BD142 500GB         | 2         | 2      | 2.94%   |
| Samsung Electronics HM321HI 320GB       | 2         | 2      | 2.94%   |
| Hitachi HDS721616PLA380 160GB           | 2         | 2      | 2.94%   |
| WDC WD800BD-08MRA1 80GB                 | 1         | 1      | 1.47%   |
| WDC WD800BB-22JHC0 80GB                 | 1         | 1      | 1.47%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 1      | 1.47%   |
| WDC WD5000BPVT-24HXZT3 500GB            | 1         | 1      | 1.47%   |
| WDC WD5000AAKX-08U6AA0 500GB            | 1         | 1      | 1.47%   |
| WDC WD5000AACS-00ZUB0 500GB             | 1         | 1      | 1.47%   |
| WDC WD50 00BPVT-24HXZT1 500GB           | 1         | 1      | 1.47%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 1      | 1.47%   |
| WDC WD3200BEKT-22F3T0 320GB             | 1         | 1      | 1.47%   |
| WDC WD3200AAJS-08L7A0 320GB             | 1         | 2      | 1.47%   |
| WDC WD2003FYPS-27Y2B0 2TB               | 1         | 1      | 1.47%   |
| WDC WD1200BEVS-60UST0 120GB             | 1         | 1      | 1.47%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 2      | 1.47%   |
| WDC WD10EZEX-22RKKA0 1TB                | 1         | 1      | 1.47%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 1         | 1      | 1.47%   |
| Toshiba MQ01ACF050 500GB                | 1         | 1      | 1.47%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 1.47%   |
| Seagate ST9500325AS 500GB               | 1         | 1      | 1.47%   |
| Seagate ST9320325AS 320GB               | 1         | 1      | 1.47%   |
| Seagate ST9160314AS 160GB               | 1         | 1      | 1.47%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1      | 1.47%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1      | 1.47%   |
| Seagate ST3500630AS 500GB               | 1         | 1      | 1.47%   |
| Seagate ST3500418AS 500GB               | 1         | 1      | 1.47%   |
| Seagate ST3500413AS 500GB               | 1         | 1      | 1.47%   |
| Seagate ST340014AS 40GB                 | 1         | 1      | 1.47%   |
| Seagate ST3320418AS 320GB               | 1         | 2      | 1.47%   |
| Seagate ST3250318AS 250GB               | 1         | 1      | 1.47%   |
| Seagate ST3250310AS 250GB               | 1         | 1      | 1.47%   |
| Seagate ST3160215ACE 160GB              | 1         | 1      | 1.47%   |
| Seagate ST3160212SCE 160GB              | 1         | 1      | 1.47%   |
| Seagate ST31000525SV 1TB                | 1         | 1      | 1.47%   |
| Samsung Electronics HN-M320MBB 320GB    | 1         | 1      | 1.47%   |
| Samsung Electronics HM250HI 250GB       | 1         | 1      | 1.47%   |
| Samsung Electronics HD161HJ 160GB       | 1         | 2      | 1.47%   |
| Samsung Electronics HD155UI 1TB         | 1         | 1      | 1.47%   |
| Maxtor STM3250310AS 250GB               | 1         | 1      | 1.47%   |
| Maxtor STM3160215AS 160GB               | 1         | 1      | 1.47%   |
| Intel SSDPEKKW256G7 256GB               | 1         | 1      | 1.47%   |
| Hitachi HUA722020ALA331 2TB             | 1         | 1      | 1.47%   |
| Hitachi HTS543232L9A300 320GB           | 1         | 1      | 1.47%   |
| Hitachi HTS543225L9SA00 250GB           | 1         | 1      | 1.47%   |
| Hitachi HTS542525K9SA00 250GB           | 1         | 1      | 1.47%   |
| Hitachi HDT721016SLA380 160GB           | 1         | 1      | 1.47%   |
| Hitachi HDS728080PLA380 40Y9028LEN 80GB | 1         | 1      | 1.47%   |
| Hitachi HDS721050DLE630 500GB           | 1         | 1      | 1.47%   |
| Hitachi HDS721032CLA362 320GB           | 1         | 1      | 1.47%   |
| Hitachi HDP725025GLA380 250GB           | 1         | 1      | 1.47%   |
| ExcelStor Technology J880S 82GB         | 1         | 1      | 1.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 24     | 33.87%  |
| WDC                 | 16        | 24     | 25.81%  |
| Hitachi             | 11        | 11     | 17.74%  |
| Samsung Electronics | 6         | 7      | 9.68%   |
| Toshiba             | 4         | 5      | 6.45%   |
| Maxtor              | 2         | 2      | 3.23%   |
| Intel               | 1         | 1      | 1.61%   |
| ExcelStor           | 1         | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 24     | 34.43%  |
| WDC                 | 16        | 24     | 26.23%  |
| Hitachi             | 11        | 11     | 18.03%  |
| Samsung Electronics | 6         | 7      | 9.84%   |
| Toshiba             | 4         | 5      | 6.56%   |
| Maxtor              | 2         | 2      | 3.28%   |
| ExcelStor           | 1         | 1      | 1.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 52        | 74     | 98.11%  |
| NVMe | 1         | 1      | 1.89%   |

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
| Detected | 122       | 217    | 50%     |
| Works    | 67        | 88     | 27.46%  |
| Malfunc  | 53        | 75     | 21.72%  |
| Failed   | 2         | 2      | 0.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 182       | 76.15%  |
| AMD                         | 21        | 8.79%   |
| Nvidia                      | 11        | 4.6%    |
| Marvell Technology Group    | 5         | 2.09%   |
| JMicron Technology          | 5         | 2.09%   |
| VIA Technologies            | 3         | 1.26%   |
| SanDisk                     | 2         | 0.84%   |
| Samsung Electronics         | 2         | 0.84%   |
| Phison Electronics          | 2         | 0.84%   |
| SK hynix                    | 1         | 0.42%   |
| Silicon Motion              | 1         | 0.42%   |
| Kingston Technology Company | 1         | 0.42%   |
| ASMedia Technology          | 1         | 0.42%   |
| Adaptec                     | 1         | 0.42%   |
| Unknown                     | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 32        | 9.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 24        | 7.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 16        | 4.94%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 13        | 4.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12        | 3.7%    |
| Nvidia MCP61 SATA Controller                                                            | 10        | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 3.09%   |
| Nvidia MCP61 IDE                                                                        | 9         | 2.78%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7         | 2.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 7         | 2.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 7         | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 2.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6         | 1.85%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6         | 1.85%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6         | 1.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 1.54%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5         | 1.54%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 5         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 4         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 1.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.23%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.93%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.93%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3         | 0.93%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3         | 0.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.93%   |
| VIA Serial ATA Controller                                                               | 2         | 0.62%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.62%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 0.62%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.62%   |
| JMicron JMB362 SATA Controller                                                          | 2         | 0.62%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 0.62%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 2         | 0.62%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 0.62%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2         | 0.62%   |
| AMD FCH IDE Controller                                                                  | 2         | 0.62%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1         | 0.31%   |
| SK hynix Gold P31 SSD                                                                   | 1         | 0.31%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.31%   |
| SanDisk WD Blue SN570 NVMe SSD                                                          | 1         | 0.31%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.31%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.31%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1         | 0.31%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1         | 0.31%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1         | 0.31%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1         | 0.31%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1         | 0.31%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1         | 0.31%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1         | 0.31%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 0.31%   |
| JMicron JMB368 IDE controller                                                           | 1         | 0.31%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 1         | 0.31%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1         | 0.31%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 126       | 51.01%  |
| IDE  | 92        | 37.25%  |
| RAID | 14        | 5.67%   |
| NVMe | 13        | 5.26%   |
| SAS  | 1         | 0.4%    |
| SCSI | 1         | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 188       | 85.07%  |
| AMD    | 33        | 14.93%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 6         | 2.71%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 6         | 2.71%   |
| Intel Celeron CPU N2805 @ 1.46GHz           | 5         | 2.26%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 4         | 1.81%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 4         | 1.81%   |
| Intel Atom CPU N455 @ 1.66GHz               | 4         | 1.81%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 3         | 1.36%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3         | 1.36%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 1.36%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 3         | 1.36%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3         | 1.36%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3         | 1.36%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3         | 1.36%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 3         | 1.36%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz        | 3         | 1.36%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 2         | 0.9%    |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2         | 0.9%    |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 2         | 0.9%    |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 2         | 0.9%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2         | 0.9%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 0.9%    |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 0.9%    |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 0.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 0.9%    |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 0.9%    |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.9%    |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 0.9%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 0.9%    |
| Intel Core i3-4000M CPU @ 2.40GHz           | 2         | 0.9%    |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 0.9%    |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 0.9%    |
| Intel Core i3 CPU 550 @ 3.20GHz             | 2         | 0.9%    |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 2         | 0.9%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2         | 0.9%    |
| Intel Atom CPU N570 @ 1.66GHz               | 2         | 0.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 0.9%    |
| AMD Sempron 145 Processor                   | 2         | 0.9%    |
| AMD E1-1200 APU with Radeon HD Graphics     | 2         | 0.9%    |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1         | 0.45%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 1         | 0.45%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1         | 0.45%   |
| Intel Xeon CPU E5-1607 0 @ 3.00GHz          | 1         | 0.45%   |
| Intel Xeon CPU E31225 @ 3.10GHz             | 1         | 0.45%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1         | 0.45%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1         | 0.45%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.45%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 0.45%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 0.45%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.45%   |
| Intel Pentium D CPU 2.80GHz                 | 1         | 0.45%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.45%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.45%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1         | 0.45%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1         | 0.45%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1         | 0.45%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1         | 0.45%   |
| Intel Pentium CPU E5800 @ 3.20GHz           | 1         | 0.45%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.45%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1         | 0.45%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 32        | 14.48%  |
| Intel Core i3                  | 28        | 12.67%  |
| Intel Pentium Dual-Core        | 23        | 10.41%  |
| Intel Core 2 Duo               | 19        | 8.6%    |
| Intel Core i7                  | 16        | 7.24%   |
| Intel Celeron                  | 16        | 7.24%   |
| Intel Pentium                  | 12        | 5.43%   |
| Intel Atom                     | 8         | 3.62%   |
| Intel Xeon                     | 7         | 3.17%   |
| Intel Pentium Dual             | 6         | 2.71%   |
| Other                          | 5         | 2.26%   |
| AMD Sempron                    | 5         | 2.26%   |
| Intel Pentium 4                | 4         | 1.81%   |
| Intel Core 2 Quad              | 4         | 1.81%   |
| Intel Core 2                   | 4         | 1.81%   |
| AMD Ryzen 5                    | 3         | 1.36%   |
| Intel Genuine                  | 2         | 0.9%    |
| AMD Phenom                     | 2         | 0.9%    |
| AMD FX                         | 2         | 0.9%    |
| AMD E1                         | 2         | 0.9%    |
| AMD Athlon II X2               | 2         | 0.9%    |
| AMD Athlon                     | 2         | 0.9%    |
| AMD A6                         | 2         | 0.9%    |
| AMD A10                        | 2         | 0.9%    |
| Intel Pentium Silver           | 1         | 0.45%   |
| Intel Pentium D                | 1         | 0.45%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.45%   |
| AMD Ryzen 7                    | 1         | 0.45%   |
| AMD Ryzen 3                    | 1         | 0.45%   |
| AMD Phenom II X4               | 1         | 0.45%   |
| AMD Mobile Sempron             | 1         | 0.45%   |
| AMD E                          | 1         | 0.45%   |
| AMD Athlon II X4               | 1         | 0.45%   |
| AMD Athlon II                  | 1         | 0.45%   |
| AMD Athlon 64 X2               | 1         | 0.45%   |
| AMD A8                         | 1         | 0.45%   |
| AMD A4                         | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 142       | 64.25%  |
| 4       | 51        | 23.08%  |
| 1       | 16        | 7.24%   |
| Unknown | 4         | 1.81%   |
| 6       | 3         | 1.36%   |
| 3       | 3         | 1.36%   |
| 8       | 2         | 0.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 221       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 127       | 57.47%  |
| 2       | 90        | 40.72%  |
| Unknown | 4         | 1.81%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 212       | 95.93%  |
| 64-bit         | 5         | 2.26%   |
| 32-bit         | 3         | 1.36%   |
| Unknown        | 1         | 0.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 15.86%  |
| 0x1067a    | 35        | 15.42%  |
| 0x206a7    | 26        | 11.45%  |
| 0x306a9    | 21        | 9.25%   |
| 0x6fd      | 9         | 3.96%   |
| 0x306c3    | 7         | 3.08%   |
| 0x106ca    | 6         | 2.64%   |
| 0x806e9    | 5         | 2.2%    |
| 0x30673    | 5         | 2.2%    |
| 0x806c1    | 4         | 1.76%   |
| 0x6fb      | 4         | 1.76%   |
| 0x20655    | 4         | 1.76%   |
| 0xf65      | 3         | 1.32%   |
| 0x6f2      | 3         | 1.32%   |
| 0x40651    | 3         | 1.32%   |
| 0x106a5    | 3         | 1.32%   |
| 0x05000119 | 3         | 1.32%   |
| 0x010000c8 | 3         | 1.32%   |
| 0x906e9    | 2         | 0.88%   |
| 0x406e3    | 2         | 0.88%   |
| 0x406c4    | 2         | 0.88%   |
| 0x10676    | 2         | 0.88%   |
| 0x08608103 | 2         | 0.88%   |
| 0x0810100b | 2         | 0.88%   |
| 0x010000c7 | 2         | 0.88%   |
| 0xf47      | 1         | 0.44%   |
| 0xf41      | 1         | 0.44%   |
| 0x906eb    | 1         | 0.44%   |
| 0x806ea    | 1         | 0.44%   |
| 0x806d1    | 1         | 0.44%   |
| 0x706e5    | 1         | 0.44%   |
| 0x706a8    | 1         | 0.44%   |
| 0x6fa      | 1         | 0.44%   |
| 0x6f6      | 1         | 0.44%   |
| 0x6ec      | 1         | 0.44%   |
| 0x506e3    | 1         | 0.44%   |
| 0x306d4    | 1         | 0.44%   |
| 0x30678    | 1         | 0.44%   |
| 0x30661    | 1         | 0.44%   |
| 0x206d7    | 1         | 0.44%   |
| 0x20652    | 1         | 0.44%   |
| 0x10661    | 1         | 0.44%   |
| 0x08600102 | 1         | 0.44%   |
| 0x08101007 | 1         | 0.44%   |
| 0x0700010b | 1         | 0.44%   |
| 0x06006704 | 1         | 0.44%   |
| 0x06006118 | 1         | 0.44%   |
| 0x06003106 | 1         | 0.44%   |
| 0x06001119 | 1         | 0.44%   |
| 0x06000852 | 1         | 0.44%   |
| 0x0600063e | 1         | 0.44%   |
| 0x03000027 | 1         | 0.44%   |
| 0x03000014 | 1         | 0.44%   |
| 0x02000057 | 1         | 0.44%   |
| 0x010000db | 1         | 0.44%   |
| 0x010000b6 | 1         | 0.44%   |
| 0x01000095 | 1         | 0.44%   |
| 0x01000065 | 1         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Penryn          | 38        | 17.19%  |
| SandyBridge     | 34        | 15.38%  |
| IvyBridge       | 24        | 10.86%  |
| Core            | 23        | 10.41%  |
| Haswell         | 12        | 5.43%   |
| KabyLake        | 11        | 4.98%   |
| K10             | 10        | 4.52%   |
| Westmere        | 8         | 3.62%   |
| Silvermont      | 8         | 3.62%   |
| Bonnell         | 8         | 3.62%   |
| NetBurst        | 5         | 2.26%   |
| TigerLake       | 4         | 1.81%   |
| K8 Hammer       | 4         | 1.81%   |
| Zen             | 3         | 1.36%   |
| Skylake         | 3         | 1.36%   |
| Nehalem         | 3         | 1.36%   |
| Bobcat          | 3         | 1.36%   |
| Piledriver      | 2         | 0.9%    |
| K10 Llano       | 2         | 0.9%    |
| IceLake         | 2         | 0.9%    |
| Goldmont plus   | 2         | 0.9%    |
| Excavator       | 2         | 0.9%    |
| Unknown         | 2         | 0.9%    |
| Zen 2           | 1         | 0.45%   |
| Steamroller     | 1         | 0.45%   |
| P6              | 1         | 0.45%   |
| K8 & K10 hybrid | 1         | 0.45%   |
| Jaguar          | 1         | 0.45%   |
| Goldmont        | 1         | 0.45%   |
| Bulldozer       | 1         | 0.45%   |
| Broadwell       | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 158       | 66.67%  |
| Nvidia                     | 37        | 15.61%  |
| AMD                        | 37        | 15.61%  |
| VIA Technologies           | 3         | 1.27%   |
| Matrox Electronics Systems | 1         | 0.42%   |
| ASPEED Technology          | 1         | 0.42%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 12.2%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 16        | 6.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 5.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 2.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 2.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 2.85%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 7         | 2.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 2.03%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 4         | 1.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.63%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 1.63%   |
| Intel 82946GZ/GL Integrated Graphics Controller                                          | 4         | 1.63%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 4         | 1.63%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 1.22%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.22%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 3         | 1.22%   |
| Intel HD Graphics 630                                                                    | 3         | 1.22%   |
| Intel HD Graphics 620                                                                    | 3         | 1.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.22%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.81%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2         | 0.81%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 2         | 0.81%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 0.81%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2         | 0.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.81%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2         | 0.81%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.81%   |
| Intel 82865G Integrated Graphics Controller                                              | 2         | 0.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.81%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.81%   |
| AMD RV670 [Radeon HD 3870]                                                               | 2         | 0.81%   |
| AMD Madison [Mobility Radeon HD 5730 / 6570M]                                            | 2         | 0.81%   |
| AMD Lucienne                                                                             | 2         | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.41%   |
| Nvidia TU117M                                                                            | 1         | 0.41%   |
| Nvidia NV44 [GeForce 6200 LE]                                                            | 1         | 0.41%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.41%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.41%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 0.41%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.41%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1         | 0.41%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 0.41%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 1         | 0.41%   |
| Nvidia GF119 [GeForce 605]                                                               | 1         | 0.41%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1         | 0.41%   |
| Nvidia GF114 [GeForce GTX 560]                                                           | 1         | 0.41%   |
| Nvidia GF108 [GeForce GT 620]                                                            | 1         | 0.41%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1         | 0.41%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.41%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.41%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1         | 0.41%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 0.41%   |
| Intel Xeon E3-1200 Processor Family Integrated Graphics Controller                       | 1         | 0.41%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 146       | 65.77%  |
| 1 x AMD         | 33        | 14.86%  |
| 1 x Nvidia      | 29        | 13.06%  |
| Intel + Nvidia  | 5         | 2.25%   |
| 1 x VIA         | 3         | 1.35%   |
| Intel + AMD     | 2         | 0.9%    |
| AMD + Nvidia    | 2         | 0.9%    |
| Nvidia + ASPEED | 1         | 0.45%   |
| 1 x Matrox      | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 192       | 86.88%  |
| Proprietary | 18        | 8.14%   |
| Unknown     | 11        | 4.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 144       | 63.16%  |
| 0.01-0.5   | 34        | 14.91%  |
| 0.51-1.0   | 26        | 11.4%   |
| 1.01-2.0   | 18        | 7.89%   |
| 3.01-4.0   | 6         | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung Electronics                   | 49        | 21.88%  |
| Hewlett-Packard                       | 16        | 7.14%   |
| BOE                                   | 16        | 7.14%   |
| AU Optronics                          | 14        | 6.25%   |
| Lenovo                                | 13        | 5.8%    |
| Goldstar                              | 13        | 5.8%    |
| LG Display                            | 12        | 5.36%   |
| Chimei Innolux                        | 10        | 4.46%   |
| InfoVision                            | 8         | 3.57%   |
| Dell                                  | 8         | 3.57%   |
| Toshiba                               | 6         | 2.68%   |
| Chi Mei Optoelectronics               | 6         | 2.68%   |
| LG Philips                            | 5         | 2.23%   |
| AOC                                   | 5         | 2.23%   |
| Acer                                  | 5         | 2.23%   |
| Apple                                 | 4         | 1.79%   |
| HannStar                              | 3         | 1.34%   |
| BenQ                                  | 3         | 1.34%   |
| Vita                                  | 2         | 0.89%   |
| Sony                                  | 2         | 0.89%   |
| PANDA                                 | 2         | 0.89%   |
| MStar                                 | 2         | 0.89%   |
| ITL                                   | 2         | 0.89%   |
| Envision                              | 2         | 0.89%   |
| Vizio                                 | 1         | 0.45%   |
| ViewSonic                             | 1         | 0.45%   |
| Unknown (XXX)                         | 1         | 0.45%   |
| Toshiba Matsushita Display Technology | 1         | 0.45%   |
| TCL                                   | 1         | 0.45%   |
| Sharp                                 | 1         | 0.45%   |
| Plain Tree Systems                    | 1         | 0.45%   |
| PEGA                                  | 1         | 0.45%   |
| Parker                                | 1         | 0.45%   |
| LSC                                   | 1         | 0.45%   |
| LG Electronics                        | 1         | 0.45%   |
| LED                                   | 1         | 0.45%   |
| KTC                                   | 1         | 0.45%   |
| InnoLux Display                       | 1         | 0.45%   |
| IBM                                   | 1         | 0.45%   |
| CVT                                   | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch           | 5         | 2.2%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 4         | 1.76%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 4         | 1.76%   |
| Lenovo LEN L171 LEN240B 1280x1024 340x270mm 17.1-inch                 | 4         | 1.76%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 3         | 1.32%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch              | 3         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch       | 3         | 1.32%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                  | 3         | 1.32%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch         | 3         | 1.32%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                    | 2         | 0.88%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch     | 2         | 0.88%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch  | 2         | 0.88%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 2         | 0.88%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.88%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.88%   |
| MStar Demo MST0030 1920x540 708x398mm 32.0-inch                       | 2         | 0.88%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 2         | 0.88%   |
| ITL MT-3185 ITL3185 1366x768 409x230mm 18.5-inch                      | 2         | 0.88%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch           | 2         | 0.88%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 2         | 0.88%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 0.88%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2         | 0.88%   |
| Goldstar FHD GSM5BC9 1920x1080 480x270mm 21.7-inch                    | 2         | 0.88%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                  | 2         | 0.88%   |
| Apple Color LCD APP9CDD 1920x1080 475x267mm 21.5-inch                 | 2         | 0.88%   |
| Vizio E322AR VIZ0079 1360x768 700x400mm 31.7-inch                     | 1         | 0.44%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch         | 1         | 0.44%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch            | 1         | 0.44%   |
| Toshiba Matsushita Display Technology LCD Monitor LCD-MONITOR         | 1         | 0.44%   |
| TCL T-7005L TCL1770 1280x1024 338x270mm 17.0-inch                     | 1         | 0.44%   |
| Sony TV SNYEB01 1360x768                                              | 1         | 0.44%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.44%   |
| Sony TV SNYDC01 1360x768                                              | 1         | 0.44%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch  | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM0499 1600x900 443x249mm 20.0-inch   | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch   | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM03F5 1920x1200                      | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM03F4 1920x1200 518x324mm 24.1-inch  | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch   | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch   | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 1         | 0.44%   |
| Samsung Electronics SMBX2050N SAM0719 1600x900 443x249mm 20.0-inch    | 1         | 0.44%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1         | 0.44%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch     | 1         | 0.44%   |
| Samsung Electronics SA300/SA350 SAM0849 1920x1080 477x268mm 21.5-inch | 1         | 0.44%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch  | 1         | 0.44%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1         | 0.44%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch      | 1         | 0.44%   |
| Samsung Electronics Monitor SAM1057 1280x1024 306x230mm 15.1-inch     | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SyncMaster 1600x900                   | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch  | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 83        | 37.9%   |
| 1920x1080 (FHD)    | 44        | 20.09%  |
| 1280x1024 (SXGA)   | 27        | 12.33%  |
| 1440x900 (WXGA+)   | 11        | 5.02%   |
| 1280x800 (WXGA)    | 11        | 5.02%   |
| 1600x900 (HD+)     | 10        | 4.57%   |
| 1360x768           | 7         | 3.2%    |
| 1680x1050 (WSXGA+) | 6         | 2.74%   |
| 3840x2160 (4K)     | 4         | 1.83%   |
| 1920x1200 (WUXGA)  | 3         | 1.37%   |
| 1280x720 (HD)      | 3         | 1.37%   |
| 1024x768 (XGA)     | 3         | 1.37%   |
| 2560x1440 (QHD)    | 2         | 0.91%   |
| 1024x600           | 2         | 0.91%   |
| Unknown            | 2         | 0.91%   |
| 3840x1080          | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 45        | 20.18%  |
| 18      | 28        | 12.56%  |
| 17      | 23        | 10.31%  |
| 14      | 22        | 9.87%   |
| 13      | 21        | 9.42%   |
| 21      | 19        | 8.52%   |
| 19      | 12        | 5.38%   |
| 10      | 8         | 3.59%   |
| Unknown | 8         | 3.59%   |
| 20      | 7         | 3.14%   |
| 23      | 5         | 2.24%   |
| 74      | 3         | 1.35%   |
| 22      | 3         | 1.35%   |
| 16      | 3         | 1.35%   |
| 11      | 3         | 1.35%   |
| 72      | 2         | 0.9%    |
| 52      | 2         | 0.9%    |
| 27      | 2         | 0.9%    |
| 24      | 2         | 0.9%    |
| 54      | 1         | 0.45%   |
| 39      | 1         | 0.45%   |
| 32      | 1         | 0.45%   |
| 31      | 1         | 0.45%   |
| 12      | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 104       | 47.71%  |
| 401-500     | 60        | 27.52%  |
| 201-300     | 14        | 6.42%   |
| 351-400     | 12        | 5.5%    |
| 501-600     | 9         | 4.13%   |
| Unknown     | 8         | 3.67%   |
| 1501-2000   | 5         | 2.29%   |
| 1001-1500   | 3         | 1.38%   |
| 801-900     | 1         | 0.46%   |
| 701-800     | 1         | 0.46%   |
| 601-700     | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 137       | 66.18%  |
| 16/10   | 33        | 15.94%  |
| 5/4     | 25        | 12.08%  |
| Unknown | 6         | 2.9%    |
| 4/3     | 4         | 1.93%   |
| 3/2     | 2         | 0.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 45        | 20.27%  |
| 141-150        | 43        | 19.37%  |
| 81-90          | 41        | 18.47%  |
| 151-200        | 30        | 13.51%  |
| 201-250        | 19        | 8.56%   |
| More than 1000 | 8         | 3.6%    |
| 41-50          | 8         | 3.6%    |
| Unknown        | 8         | 3.6%    |
| 121-130        | 6         | 2.7%    |
| 51-60          | 3         | 1.35%   |
| 351-500        | 2         | 0.9%    |
| 301-350        | 2         | 0.9%    |
| 251-300        | 2         | 0.9%    |
| 71-80          | 1         | 0.45%   |
| 61-70          | 1         | 0.45%   |
| 131-140        | 1         | 0.45%   |
| 501-1000       | 1         | 0.45%   |
| 91-100         | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 99        | 45%     |
| 101-120       | 71        | 32.27%  |
| 121-160       | 29        | 13.18%  |
| 1-50          | 10        | 4.55%   |
| Unknown       | 8         | 3.64%   |
| 161-240       | 2         | 0.91%   |
| More than 240 | 1         | 0.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 189       | 84.75%  |
| 2     | 23        | 10.31%  |
| 0     | 9         | 4.04%   |
| 3     | 2         | 0.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 135       | 37.6%   |
| Qualcomm Atheros                  | 65        | 18.11%  |
| Intel                             | 62        | 17.27%  |
| Broadcom                          | 25        | 6.96%   |
| Ralink                            | 11        | 3.06%   |
| Nvidia                            | 11        | 3.06%   |
| Ralink Technology                 | 7         | 1.95%   |
| Xiaomi                            | 5         | 1.39%   |
| Marvell Technology Group          | 5         | 1.39%   |
| Broadcom Limited                  | 5         | 1.39%   |
| Qualcomm Atheros Communications   | 4         | 1.11%   |
| VIA Technologies                  | 3         | 0.84%   |
| Samsung Electronics               | 3         | 0.84%   |
| JMicron Technology                | 3         | 0.84%   |
| Trendchip Technologies            | 2         | 0.56%   |
| Sundance Technology Inc / IC Plus | 2         | 0.56%   |
| Mercucys                          | 2         | 0.56%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.28%   |
| National Semiconductor            | 1         | 0.28%   |
| Motorola PCS                      | 1         | 0.28%   |
| Motorola BCS                      | 1         | 0.28%   |
| MediaTek                          | 1         | 0.28%   |
| ICS Advent                        | 1         | 0.28%   |
| Digium                            | 1         | 0.28%   |
| D-Link System                     | 1         | 0.28%   |
| AMD                               | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 77        | 19.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 29        | 7.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 14        | 3.47%   |
| Nvidia MCP61 Ethernet                                                          | 10        | 2.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 2.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 9         | 2.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 8         | 1.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 7         | 1.74%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 7         | 1.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 6         | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 6         | 1.49%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 5         | 1.24%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5         | 1.24%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 5         | 1.24%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 4         | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4         | 0.99%   |
| Intel Wireless 7265                                                            | 4         | 0.99%   |
| Intel Centrino Wireless-N 105                                                  | 4         | 0.99%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 4         | 0.99%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 4         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 3         | 0.74%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 0.74%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 3         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 3         | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 3         | 0.74%   |
| Ralink MT7601U Wireless Adapter                                                | 3         | 0.74%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 3         | 0.74%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3         | 0.74%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3         | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 3         | 0.74%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3         | 0.74%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 0.74%   |
| Intel Wireless 7260                                                            | 3         | 0.74%   |
| Intel PRO/100 VE Network Connection                                            | 3         | 0.74%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 3         | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 0.5%    |
| Trendchip Ethernet controller                                                  | 2         | 0.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2         | 0.5%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                         | 2         | 0.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2         | 0.5%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 2         | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.5%    |
| Mercucys MW300UM RTL8192EU wifi                                                | 2         | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.5%    |
| Intel Wireless 8260                                                            | 2         | 0.5%    |
| Intel Wireless 3165                                                            | 2         | 0.5%    |
| Intel WiFi Link 5100                                                           | 2         | 0.5%    |
| Intel Wi-Fi 6 AX201                                                            | 2         | 0.5%    |
| Intel Wi-Fi 6 AX200                                                            | 2         | 0.5%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 2         | 0.5%    |
| Intel Ethernet Connection I217-V                                               | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 49        | 28.99%  |
| Realtek Semiconductor           | 44        | 26.04%  |
| Intel                           | 35        | 20.71%  |
| Broadcom                        | 14        | 8.28%   |
| Ralink                          | 11        | 6.51%   |
| Ralink Technology               | 7         | 4.14%   |
| Qualcomm Atheros Communications | 4         | 2.37%   |
| Mercucys                        | 2         | 1.18%   |
| MediaTek                        | 1         | 0.59%   |
| D-Link System                   | 1         | 0.59%   |
| Broadcom Limited                | 1         | 0.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 14        | 8.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 9         | 5.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 8         | 4.73%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 7         | 4.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 6         | 3.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 5         | 2.96%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5         | 2.96%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 4         | 2.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 2.37%   |
| Intel Wireless 7265                                                            | 4         | 2.37%   |
| Intel Centrino Wireless-N 105                                                  | 4         | 2.37%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 4         | 2.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 1.78%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 3         | 1.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 3         | 1.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 3         | 1.78%   |
| Ralink MT7601U Wireless Adapter                                                | 3         | 1.78%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 3         | 1.78%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3         | 1.78%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3         | 1.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 3         | 1.78%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3         | 1.78%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 1.78%   |
| Intel Wireless 7260                                                            | 3         | 1.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.18%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2         | 1.18%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                         | 2         | 1.18%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2         | 1.18%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 2         | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 1.18%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 2         | 1.18%   |
| Intel Wireless 8260                                                            | 2         | 1.18%   |
| Intel Wireless 3165                                                            | 2         | 1.18%   |
| Intel WiFi Link 5100                                                           | 2         | 1.18%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 1.18%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 1.18%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 2         | 1.18%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 1.18%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2         | 1.18%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                              | 2         | 1.18%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 0.59%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.59%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1         | 0.59%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 0.59%   |
| Ralink RT5372 Wireless Adapter                                                 | 1         | 0.59%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1         | 0.59%   |
| Qualcomm Atheros AR5523                                                        | 1         | 0.59%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1         | 0.59%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]            | 1         | 0.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.59%   |
| Intel Gemini Lake PCH CNVi WiFi                                                | 1         | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 1         | 0.59%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 0.59%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 0.59%   |
| Intel Centrino Ultimate-N 6300                                                 | 1         | 0.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1         | 0.59%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]           | 1         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 115       | 50.66%  |
| Intel                             | 36        | 15.86%  |
| Qualcomm Atheros                  | 23        | 10.13%  |
| Nvidia                            | 11        | 4.85%   |
| Broadcom                          | 11        | 4.85%   |
| Xiaomi                            | 5         | 2.2%    |
| Marvell Technology Group          | 5         | 2.2%    |
| Broadcom Limited                  | 4         | 1.76%   |
| VIA Technologies                  | 3         | 1.32%   |
| Samsung Electronics               | 3         | 1.32%   |
| JMicron Technology                | 3         | 1.32%   |
| Trendchip Technologies            | 2         | 0.88%   |
| Sundance Technology Inc / IC Plus | 2         | 0.88%   |
| National Semiconductor            | 1         | 0.44%   |
| Motorola PCS                      | 1         | 0.44%   |
| Motorola BCS                      | 1         | 0.44%   |
| ICS Advent                        | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 77        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 29        | 12.55%  |
| Nvidia MCP61 Ethernet                                                      | 10        | 4.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 10        | 4.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 7         | 3.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 6         | 2.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 5         | 2.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 4         | 1.73%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4         | 1.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3         | 1.3%    |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3         | 1.3%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3         | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3         | 1.3%    |
| Intel PRO/100 VE Network Connection                                        | 3         | 1.3%    |
| Intel 82567V-2 Gigabit Network Connection                                  | 3         | 1.3%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2         | 0.87%   |
| Trendchip Ethernet controller                                              | 2         | 0.87%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2         | 0.87%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 2         | 0.87%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                     | 2         | 0.87%   |
| Intel Ethernet Connection I217-V                                           | 2         | 0.87%   |
| Intel Ethernet Connection I217-LM                                          | 2         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 0.87%   |
| Intel 82574L Gigabit Network Connection                                    | 2         | 0.87%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2         | 0.87%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                | 2         | 0.87%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1         | 0.43%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1         | 0.43%   |
| Realtek Realtek Ethernet controller                                        | 1         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.43%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1         | 0.43%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                      | 1         | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1         | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1         | 0.43%   |
| Nvidia MCP77 Ethernet                                                      | 1         | 0.43%   |
| National DP83815 (MacPhyter) Ethernet Controller                           | 1         | 0.43%   |
| Motorola PCS Moto E (4) Plus                                               | 1         | 0.43%   |
| Motorola BCS SurfBoard SB5100 Cable Modem                                  | 1         | 0.43%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                    | 1         | 0.43%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 1         | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                    | 1         | 0.43%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                        | 1         | 0.43%   |
| Intel NM10/ICH7 Family LAN Controller                                      | 1         | 0.43%   |
| Intel I210 Gigabit Network Connection                                      | 1         | 0.43%   |
| Intel Ethernet Connection I219-V                                           | 1         | 0.43%   |
| Intel Ethernet Connection I219-LM                                          | 1         | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                                      | 1         | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1         | 0.43%   |
| Intel 82579V Gigabit Network Connection                                    | 1         | 0.43%   |
| Intel 82577LM Gigabit Network Connection                                   | 1         | 0.43%   |
| Intel 82567V-4 Gigabit Network Connection                                  | 1         | 0.43%   |
| Intel 82567LM-2 Gigabit Network Connection                                 | 1         | 0.43%   |
| Intel 82566DC-2 Gigabit Network Connection                                 | 1         | 0.43%   |
| Intel 82566DC Gigabit Network Connection                                   | 1         | 0.43%   |
| Intel 82562V-2 10/100 Network Connection                                   | 1         | 0.43%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                       | 1         | 0.43%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 1         | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                          | 1         | 0.43%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 208       | 55.76%  |
| WiFi     | 162       | 43.43%  |
| Modem    | 2         | 0.54%   |
| Unknown  | 1         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 117       | 50.87%  |
| WiFi     | 113       | 49.13%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 131       | 58.48%  |
| 1     | 86        | 38.39%  |
| 3     | 4         | 1.79%   |
| 0     | 2         | 0.89%   |
| 4     | 1         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 221       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 29.17%  |
| IMC Networks                    | 11        | 15.28%  |
| Qualcomm Atheros Communications | 10        | 13.89%  |
| Realtek Semiconductor           | 9         | 12.5%   |
| Cambridge Silicon Radio         | 8         | 11.11%  |
| Broadcom                        | 6         | 8.33%   |
| Apple                           | 4         | 5.56%   |
| ASUSTek Computer                | 3         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 13        | 18.06%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 11.11%  |
| Realtek RTL8723B Bluetooth                          | 6         | 8.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 5.56%   |
| Realtek Bluetooth Radio                             | 3         | 4.17%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 4.17%   |
| IMC Networks Bluetooth                              | 3         | 4.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 4.17%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 4.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 2.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.78%   |
| Intel AX201 Bluetooth                               | 2         | 2.78%   |
| Intel AX200 Bluetooth                               | 2         | 2.78%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.78%   |
| IMC Networks Bluetooth Module                       | 2         | 2.78%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 2.78%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.39%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.39%   |
| IMC Networks Wireless_Device                        | 1         | 1.39%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.39%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.39%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.39%   |
| Broadcom BCM2035B3 Bluetooth Adapter                | 1         | 1.39%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 1.39%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.39%   |
| ASUS Bluetooth Adapter                              | 1         | 1.39%   |
| Apple Bluetooth HCI                                 | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 182       | 65.94%  |
| AMD                       | 38        | 13.77%  |
| Nvidia                    | 31        | 11.23%  |
| C-Media Electronics       | 6         | 2.17%   |
| VIA Technologies          | 4         | 1.45%   |
| Creative Labs             | 3         | 1.09%   |
| Sennheiser Communications | 2         | 0.72%   |
| Microsoft                 | 2         | 0.72%   |
| Logitech                  | 2         | 0.72%   |
| JMTek                     | 2         | 0.72%   |
| Unknown                   | 1         | 0.36%   |
| Realtek Semiconductor     | 1         | 0.36%   |
| Generalplus Technology    | 1         | 0.36%   |
| Cirrus Logic              | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 41        | 13.36%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 32        | 10.42%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 7.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 3.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 3.58%   |
| Nvidia MCP61 High Definition Audio                                                                | 9         | 2.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.61%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 2.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.61%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.61%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 7         | 2.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.95%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 1.95%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 1.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.3%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.3%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 1.3%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.98%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.98%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3         | 0.98%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 0.98%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 0.98%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.98%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 0.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.98%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.98%   |
| Sennheiser Communications SC230                                                                   | 2         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.65%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.65%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 2         | 0.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.65%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 2         | 0.65%   |
| C-Media Electronics CM108 Audio Controller                                                        | 2         | 0.65%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.65%   |
| AMD RV670/680 HDMI Audio [Radeon HD 3690/3800 Series]                                             | 2         | 0.65%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.65%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.65%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                       | 1         | 0.33%   |
| Unknown Audio device                                                                              | 1         | 0.33%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.33%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.33%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.33%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.33%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.33%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.33%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1         | 0.33%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.33%   |
| Nvidia Audio device                                                                               | 1         | 0.33%   |
| Microsoft LifeChat LX-6000 Headset                                                                | 1         | 0.33%   |
| Microsoft LifeChat LX-4000                                                                        | 1         | 0.33%   |
| Logitech H600 [Wireless Headset]                                                                  | 1         | 0.33%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 45        | 24.19%  |
| Samsung Electronics | 25        | 13.44%  |
| SK hynix            | 23        | 12.37%  |
| Ramaxel Technology  | 18        | 9.68%   |
| Kingston            | 17        | 9.14%   |
| Micron Technology   | 12        | 6.45%   |
| Crucial             | 9         | 4.84%   |
| Corsair             | 8         | 4.3%    |
| Elpida              | 4         | 2.15%   |
| Nanya Technology    | 3         | 1.61%   |
| A-DATA Technology   | 3         | 1.61%   |
| Unknown             | 3         | 1.61%   |
| Unknown (ABCD)      | 2         | 1.08%   |
| Unknown (0x07D5)    | 2         | 1.08%   |
| Qimonda             | 2         | 1.08%   |
| Avant               | 2         | 1.08%   |
| Unknown (0x0CBA)    | 1         | 0.54%   |
| Unknown (081A)      | 1         | 0.54%   |
| Team                | 1         | 0.54%   |
| PNY                 | 1         | 0.54%   |
| OCZ                 | 1         | 0.54%   |
| Memox               | 1         | 0.54%   |
| Kreton              | 1         | 0.54%   |
| Apacer              | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2                        | 3         | 1.46%   |
| Unknown RAM Module 1024MB DIMM DDR2                        | 3         | 1.46%   |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s | 3         | 1.46%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s    | 3         | 1.46%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s    | 3         | 1.46%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s    | 3         | 1.46%   |
| Unknown                                                    | 3         | 1.46%   |
| Unknown RAM Module 4GB DIMM SDRAM                          | 2         | 0.97%   |
| Unknown RAM Module 4GB DIMM 400MT/s                        | 2         | 0.97%   |
| Unknown RAM Module 2GB DIMM DDR2                           | 2         | 0.97%   |
| Unknown RAM Module 2GB DIMM 400MT/s                        | 2         | 0.97%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 2         | 0.97%   |
| Unknown RAM Module 1024MB DIMM SDRAM                       | 2         | 0.97%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                | 2         | 0.97%   |
| Unknown (0x07D5) RAM Module 4GB SODIMM DDR3 1333MT/s       | 2         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 0.97%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s     | 2         | 0.97%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 2         | 0.97%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                | 2         | 0.97%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s      | 2         | 0.97%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 0.97%   |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s        | 2         | 0.97%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 2         | 0.97%   |
| Ramaxel RAM RMR5030ME68F9F1600 4096MB DIMM DDR3 1600MT/s   | 2         | 0.97%   |
| Ramaxel RAM Module 4GB SODIMM DDR3 1333MT/s                | 2         | 0.97%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s         | 2         | 0.97%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s     | 2         | 0.97%   |
| Kingston RAM Module 4GB SODIMM DDR3 1333MT/s               | 2         | 0.97%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 0.49%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                       | 1         | 0.49%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s             | 1         | 0.49%   |
| Unknown RAM Module 512MB DIMM DDR2                         | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM 667MT/s                        | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                       | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s             | 1         | 0.49%   |
| Unknown RAM Module 4096MB DIMM SDRAM                       | 1         | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s               | 1         | 0.49%   |
| Unknown RAM Module 4096MB DIMM                             | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2                         | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                  | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                  | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s              | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2                      | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s               | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s               | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s                | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR2 1639MT/s               | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                 | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                 | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                 | 1         | 0.49%   |
| Unknown RAM Module 1GB DIMM DDR 133MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2667MT/s            | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 60        | 41.67%  |
| DDR2    | 32        | 22.22%  |
| DDR4    | 21        | 14.58%  |
| SDRAM   | 14        | 9.72%   |
| Unknown | 9         | 6.25%   |
| DDR     | 5         | 3.47%   |
| LPDDR4  | 3         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 75        | 54.35%  |
| SODIMM       | 61        | 44.2%   |
| Row Of Chips | 2         | 1.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 60        | 36.36%  |
| 4096  | 52        | 31.52%  |
| 8192  | 27        | 16.36%  |
| 1024  | 20        | 12.12%  |
| 16384 | 4         | 2.42%   |
| 512   | 2         | 1.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 40        | 24.84%  |
| 1333    | 22        | 13.66%  |
| Unknown | 17        | 10.56%  |
| 667     | 10        | 6.21%   |
| 2667    | 8         | 4.97%   |
| 2400    | 8         | 4.97%   |
| 800     | 8         | 4.97%   |
| 3200    | 7         | 4.35%   |
| 533     | 6         | 3.73%   |
| 1066    | 5         | 3.11%   |
| 2048    | 4         | 2.48%   |
| 400     | 4         | 2.48%   |
| 1639    | 3         | 1.86%   |
| 1334    | 3         | 1.86%   |
| 1067    | 3         | 1.86%   |
| 133     | 3         | 1.86%   |
| 4199    | 2         | 1.24%   |
| 2133    | 2         | 1.24%   |
| 1867    | 2         | 1.24%   |
| 3266    | 1         | 0.62%   |
| 3000    | 1         | 0.62%   |
| 1024    | 1         | 0.62%   |
| 975     | 1         | 0.62%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 60%     |
| Seiko Epson         | 2         | 20%     |
| Samsung Electronics | 2         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 10%     |
| Seiko Epson L210 Series                      | 1         | 10%     |
| Samsung ML-216x Series Laser Printer         | 1         | 10%     |
| Samsung ML-1865                              | 1         | 10%     |
| HP LaserJet Professional P1102w              | 1         | 10%     |
| HP LaserJet P1006                            | 1         | 10%     |
| HP LaserJet P1005                            | 1         | 10%     |
| HP LaserJet 1018                             | 1         | 10%     |
| HP DeskJet 2300 series                       | 1         | 10%     |
| HP Color LaserJet CP1215                     | 1         | 10%     |

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
| Chicony Electronics                    | 22        | 21.78%  |
| Microdia                               | 11        | 10.89%  |
| Acer                                   | 11        | 10.89%  |
| Realtek Semiconductor                  | 10        | 9.9%    |
| IMC Networks                           | 7         | 6.93%   |
| Suyin                                  | 5         | 4.95%   |
| Logitech                               | 5         | 4.95%   |
| Apple                                  | 5         | 4.95%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.97%   |
| Syntek                                 | 2         | 1.98%   |
| Sunplus Innovation Technology          | 2         | 1.98%   |
| Ricoh                                  | 2         | 1.98%   |
| Microsoft                              | 2         | 1.98%   |
| Lite-On Technology                     | 2         | 1.98%   |
| KYE Systems (Mouse Systems)            | 2         | 1.98%   |
| Tobii Technology AB                    | 1         | 0.99%   |
| Sonix Technology                       | 1         | 0.99%   |
| SiGma Micro                            | 1         | 0.99%   |
| Samsung Electronics                    | 1         | 0.99%   |
| Quanta                                 | 1         | 0.99%   |
| Luxvisions Innotech Limited            | 1         | 0.99%   |
| LG Electronics                         | 1         | 0.99%   |
| Lenovo                                 | 1         | 0.99%   |
| Aveo Technology                        | 1         | 0.99%   |
| ALi                                    | 1         | 0.99%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                        | 9         | 8.91%   |
| Realtek Integrated_Webcam_HD                                  | 4         | 3.96%   |
| Acer HD Webcam                                                | 4         | 3.96%   |
| Microdia USB 2.0 Camera                                       | 3         | 2.97%   |
| Logitech Webcam C270                                          | 3         | 2.97%   |
| Chicony Lenovo EasyCamera                                     | 3         | 2.97%   |
| Apple Built-in iSight                                         | 3         | 2.97%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 1.98%   |
| IMC Networks USB 2.0 UVC VGA WebCam                           | 2         | 1.98%   |
| Chicony Integrated Camera                                     | 2         | 1.98%   |
| Chicony HD WebCam                                             | 2         | 1.98%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 2         | 1.98%   |
| Acer USB Camera                                               | 2         | 1.98%   |
| Acer Lenovo EasyCamera                                        | 2         | 1.98%   |
| Tobii AB EyeChip                                              | 1         | 0.99%   |
| Syntek USB Camera Device                                      | 1         | 0.99%   |
| Syntek Integrated Webcam                                      | 1         | 0.99%   |
| Suyin USB2.0 UVC 1.3M WebCam                                  | 1         | 0.99%   |
| Suyin HP Webcam 101                                           | 1         | 0.99%   |
| Suyin HP Webcam                                               | 1         | 0.99%   |
| Suyin HD Video WebCam                                         | 1         | 0.99%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 0.99%   |
| Sunplus MTD Camera                                            | 1         | 0.99%   |
| Sunplus Integrated_Webcam_HD                                  | 1         | 0.99%   |
| Sonix USB2.0 HD UVC WebCam                                    | 1         | 0.99%   |
| SiGma Micro WebCam SiGma Micro                                | 1         | 0.99%   |
| Samsung Galaxy series, misc. (MTP mode)                       | 1         | 0.99%   |
| Ricoh Sony Vaio Integrated Webcam                             | 1         | 0.99%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 1         | 0.99%   |
| Realtek USB2.0 camera                                         | 1         | 0.99%   |
| Realtek USB Camera                                            | 1         | 0.99%   |
| Realtek Integrated Webcam HD                                  | 1         | 0.99%   |
| Realtek Integrated Webcam                                     | 1         | 0.99%   |
| Realtek HP 1.0MP High Definition Webcam                       | 1         | 0.99%   |
| Realtek EasyCamera                                            | 1         | 0.99%   |
| Quanta HP Webcam                                              | 1         | 0.99%   |
| Microsoft LifeCam VX-5000                                     | 1         | 0.99%   |
| Microsoft LifeCam Studio                                      | 1         | 0.99%   |
| Microdia WebCam SC-13HDL12639P                                | 1         | 0.99%   |
| Microdia USB camera                                           | 1         | 0.99%   |
| Microdia Sonix USB 2.0 Camera                                 | 1         | 0.99%   |
| Microdia Laptop_Integrated_Webcam_HD                          | 1         | 0.99%   |
| Microdia Integrated_Webcam_HD                                 | 1         | 0.99%   |
| Microdia Integrated_Webcam_FHD                                | 1         | 0.99%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera           | 1         | 0.99%   |
| Logitech QuickCam Communicate MP/S5500                        | 1         | 0.99%   |
| Logitech C922 Pro Stream Webcam                               | 1         | 0.99%   |
| Lite-On TOSHIBA Web Camera - HD                               | 1         | 0.99%   |
| Lite-On HP HD Webcam                                          | 1         | 0.99%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)         | 1         | 0.99%   |
| Lenovo CNF7237&CNF7238                                        | 1         | 0.99%   |
| KYE Systems (Mouse Systems) FaceCam 1320                      | 1         | 0.99%   |
| KYE Systems (Mouse Systems) eFace 2025                        | 1         | 0.99%   |
| IMC Networks USB2.0 VGA UVC WebCam                            | 1         | 0.99%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                           | 1         | 0.99%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 1         | 0.99%   |
| IMC Networks USB 2.0 Camera                                   | 1         | 0.99%   |
| IMC Networks EasyCamera                                       | 1         | 0.99%   |
| Chicony USB2.0 VGA UVC WebCam                                 | 1         | 0.99%   |
| Chicony USB2.0 HD UVC WebCam                                  | 1         | 0.99%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Validity Sensors    | 5         | 62.5%   |
| AuthenTec           | 2         | 25%     |
| Futronic Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 2         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader  | 2         | 25%     |
| AuthenTec AES2501 Fingerprint Sensor        | 2         | 25%     |
| Validity Sensors Fingerprint scanner        | 1         | 12.5%   |
| Futronic Fingerprint Scanner Model FS88     | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 4         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 50%     |
| Broadcom 5880                                  | 2         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 180       | 80.36%  |
| 1     | 40        | 17.86%  |
| 2     | 3         | 1.34%   |
| 4     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 16        | 31.37%  |
| Communication controller | 10        | 19.61%  |
| Fingerprint reader       | 8         | 15.69%  |
| Net/wireless             | 5         | 9.8%    |
| Chipcard                 | 4         | 7.84%   |
| Sound                    | 3         | 5.88%   |
| Camera                   | 2         | 3.92%   |
| Storage                  | 1         | 1.96%   |
| Network                  | 1         | 1.96%   |
| Multimedia controller    | 1         | 1.96%   |

