Linux in Estonia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Estonia.

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

Total: 405

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8460p             | [17cd1c1733](https://linux-hardware.org/?probe=17cd1c1733) | Dec 25, 2025 |
| HP            | EliteBook 840 G8 Noteboo... | [ec7b63cebb](https://linux-hardware.org/?probe=ec7b63cebb) | Dec 15, 2025 |
| Apple         | MacBookPro11,2              | [6aa16084f0](https://linux-hardware.org/?probe=6aa16084f0) | Dec 07, 2025 |
| Lenovo        | ThinkPad X230 2325SG2       | [38b00653b3](https://linux-hardware.org/?probe=38b00653b3) | Dec 04, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [8310635b74](https://linux-hardware.org/?probe=8310635b74) | Dec 03, 2025 |
| HP            | EliteBook Folio 1040 G2     | [cec6d02e50](https://linux-hardware.org/?probe=cec6d02e50) | Nov 29, 2025 |
| HP            | ProBook 640 G1              | [5d214afddf](https://linux-hardware.org/?probe=5d214afddf) | Nov 29, 2025 |
| HP            | Pavilion 15                 | [66f29bd82a](https://linux-hardware.org/?probe=66f29bd82a) | Nov 24, 2025 |
| Apple         | MacBook8,1                  | [8bc9d8aa99](https://linux-hardware.org/?probe=8bc9d8aa99) | Nov 24, 2025 |
| Apple         | MacBook8,1                  | [a334a69680](https://linux-hardware.org/?probe=a334a69680) | Nov 24, 2025 |
| Lenovo        | ThinkPad T430 2347HM4       | [09150691a8](https://linux-hardware.org/?probe=09150691a8) | Nov 22, 2025 |
| Lenovo        | ThinkPad T480 20L50011US    | [b0d8e874d7](https://linux-hardware.org/?probe=b0d8e874d7) | Oct 14, 2025 |
| Lenovo        | LOQ 15ARP9 83JC             | [92a5998356](https://linux-hardware.org/?probe=92a5998356) | Oct 13, 2025 |
| HUAWEI        | MACHD-WXX9                  | [15e5fecee0](https://linux-hardware.org/?probe=15e5fecee0) | Oct 03, 2025 |
| Dell          | Inspiron 7737               | [2e2b0ce8da](https://linux-hardware.org/?probe=2e2b0ce8da) | Oct 01, 2025 |
| Dell          | Inspiron 7737               | [bbc74021e1](https://linux-hardware.org/?probe=bbc74021e1) | Oct 01, 2025 |
| Chuwi         | CoreBook X                  | [c8bb120e05](https://linux-hardware.org/?probe=c8bb120e05) | Sep 24, 2025 |
| Chuwi         | CoreBook X                  | [084cecffb5](https://linux-hardware.org/?probe=084cecffb5) | Sep 23, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MMS... | [345a58a039](https://linux-hardware.org/?probe=345a58a039) | Sep 15, 2025 |
| Notebook      | N9x0TD_TF                   | [7281d4fccf](https://linux-hardware.org/?probe=7281d4fccf) | Sep 15, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MMS... | [8d04cd4279](https://linux-hardware.org/?probe=8d04cd4279) | Sep 15, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [5e381a1979](https://linux-hardware.org/?probe=5e381a1979) | Sep 12, 2025 |
| Dell          | Inspiron 15-3567            | [03d0038733](https://linux-hardware.org/?probe=03d0038733) | Sep 09, 2025 |
| Lenovo        | ThinkPad X280 20KE003KMX    | [cadf220563](https://linux-hardware.org/?probe=cadf220563) | Sep 06, 2025 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [b15b20f5fd](https://linux-hardware.org/?probe=b15b20f5fd) | Aug 10, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MCS... | [69b4399293](https://linux-hardware.org/?probe=69b4399293) | Aug 07, 2025 |
| Lenovo        | ThinkPad T420 4236W9P       | [6c0a7ada9d](https://linux-hardware.org/?probe=6c0a7ada9d) | Aug 03, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [62f44f6c6b](https://linux-hardware.org/?probe=62f44f6c6b) | Jul 29, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [3f690161be](https://linux-hardware.org/?probe=3f690161be) | Jul 27, 2025 |
| Dell          | Latitude 5490               | [188dd223da](https://linux-hardware.org/?probe=188dd223da) | Jul 22, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [e11c75dc55](https://linux-hardware.org/?probe=e11c75dc55) | Jul 18, 2025 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [2ab3e26358](https://linux-hardware.org/?probe=2ab3e26358) | Jul 14, 2025 |
| Lenovo        | ThinkPad W530 2436CTO       | [109e3b0a4b](https://linux-hardware.org/?probe=109e3b0a4b) | Jul 14, 2025 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [927261893b](https://linux-hardware.org/?probe=927261893b) | Jul 14, 2025 |
| Dell          | Latitude 7420               | [1d1f41c660](https://linux-hardware.org/?probe=1d1f41c660) | Jul 11, 2025 |
| Dell          | Latitude 7420               | [a45d25c768](https://linux-hardware.org/?probe=a45d25c768) | Jul 11, 2025 |
| Apple         | MacBookPro5,4               | [380af89a75](https://linux-hardware.org/?probe=380af89a75) | Jun 23, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [b59e1e98fe](https://linux-hardware.org/?probe=b59e1e98fe) | Jun 20, 2025 |
| HP            | EliteBook 850 G6            | [2f0fd20ed5](https://linux-hardware.org/?probe=2f0fd20ed5) | May 31, 2025 |
| HP            | EliteBook 850 G6            | [4bc436ca7a](https://linux-hardware.org/?probe=4bc436ca7a) | May 31, 2025 |
| Lenovo        | ThinkPad Edge 022138G       | [4a0bff5124](https://linux-hardware.org/?probe=4a0bff5124) | May 29, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | [134387e9b6](https://linux-hardware.org/?probe=134387e9b6) | May 26, 2025 |
| Notebook      | N9x0TD_TF                   | [fd4e0c03f7](https://linux-hardware.org/?probe=fd4e0c03f7) | Apr 24, 2025 |
| Notebook      | N9x0TD_TF                   | [c10fb115aa](https://linux-hardware.org/?probe=c10fb115aa) | Apr 22, 2025 |
| HP            | Elite Dragonfly 13.5 inc... | [57c675dad5](https://linux-hardware.org/?probe=57c675dad5) | Apr 12, 2025 |
| Dell          | Vostro 3700                 | [fa66ce1fa7](https://linux-hardware.org/?probe=fa66ce1fa7) | Apr 05, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | [fbda73a703](https://linux-hardware.org/?probe=fbda73a703) | Apr 01, 2025 |
| Apple         | MacBookAir7,2               | [241c2d8a5c](https://linux-hardware.org/?probe=241c2d8a5c) | Mar 31, 2025 |
| HP            | ZBook 17 G3                 | [c90d04b1e8](https://linux-hardware.org/?probe=c90d04b1e8) | Mar 28, 2025 |
| Dell          | Latitude 7490               | [e3d46aa669](https://linux-hardware.org/?probe=e3d46aa669) | Mar 24, 2025 |
| GPD           | G1619-04                    | [c52627c2de](https://linux-hardware.org/?probe=c52627c2de) | Mar 21, 2025 |
| Dell          | Latitude 7280               | [9378675ecb](https://linux-hardware.org/?probe=9378675ecb) | Mar 17, 2025 |
| Lenovo        | V330-14IKB 81B0             | [a1af0b781e](https://linux-hardware.org/?probe=a1af0b781e) | Mar 13, 2025 |
| Dell          | Latitude 7640               | [abd6719d67](https://linux-hardware.org/?probe=abd6719d67) | Mar 06, 2025 |
| Notebook      | N9x0TD_TF                   | [902efa63b3](https://linux-hardware.org/?probe=902efa63b3) | Mar 04, 2025 |
| Notebook      | N9x0TD_TF                   | [ef4ee4970c](https://linux-hardware.org/?probe=ef4ee4970c) | Mar 03, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | [c9cd04c99a](https://linux-hardware.org/?probe=c9cd04c99a) | Mar 02, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | [a4c826ce08](https://linux-hardware.org/?probe=a4c826ce08) | Mar 02, 2025 |
| Dell          | XPS 15 9570                 | [f913fd0139](https://linux-hardware.org/?probe=f913fd0139) | Feb 24, 2025 |
| Dell          | Latitude 7640               | [ad3ce4d65c](https://linux-hardware.org/?probe=ad3ce4d65c) | Feb 23, 2025 |
| GPD           | G1619-04                    | [5328fd045b](https://linux-hardware.org/?probe=5328fd045b) | Feb 18, 2025 |
| Samsung       | 905S3G/906S3G/915S3G        | [cdfe8ff639](https://linux-hardware.org/?probe=cdfe8ff639) | Feb 15, 2025 |
| Dell          | Precision M6700             | [11f8956de8](https://linux-hardware.org/?probe=11f8956de8) | Feb 13, 2025 |
| Lenovo        | ThinkPad P70 20ER000EMS     | [21552aaa9a](https://linux-hardware.org/?probe=21552aaa9a) | Feb 08, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [4432213b4b](https://linux-hardware.org/?probe=4432213b4b) | Feb 08, 2025 |
| Acer          | Aspire 5750ZG               | [b55d95dc40](https://linux-hardware.org/?probe=b55d95dc40) | Jan 23, 2025 |
| Acer          | Aspire 5750ZG               | [fa9b739c95](https://linux-hardware.org/?probe=fa9b739c95) | Jan 23, 2025 |
| Lenovo        | ThinkPad T500 2056VPG       | [8ee528a59e](https://linux-hardware.org/?probe=8ee528a59e) | Jan 16, 2025 |
| Dell          | Latitude 7640               | [f7e928b28a](https://linux-hardware.org/?probe=f7e928b28a) | Jan 14, 2025 |
| Dell          | Latitude 3340               | [83ea4fad0a](https://linux-hardware.org/?probe=83ea4fad0a) | Jan 13, 2025 |
| Dell          | Latitude 7640               | [6d1fd722cb](https://linux-hardware.org/?probe=6d1fd722cb) | Jan 13, 2025 |
| HP            | EliteBook 8470p             | [7a5df9412c](https://linux-hardware.org/?probe=7a5df9412c) | Dec 31, 2024 |
| Dell          | Latitude 7640               | [931523acc9](https://linux-hardware.org/?probe=931523acc9) | Dec 28, 2024 |
| Dell          | System XPS 15Z              | [9e7fc2d36e](https://linux-hardware.org/?probe=9e7fc2d36e) | Dec 20, 2024 |
| Lenovo        | ThinkPad T60 1951FDG        | [9c3c2fb92b](https://linux-hardware.org/?probe=9c3c2fb92b) | Dec 13, 2024 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [b3ea15c92e](https://linux-hardware.org/?probe=b3ea15c92e) | Dec 12, 2024 |
| Lenovo        | ThinkPad T460s 20F9003RM... | [5092bec86b](https://linux-hardware.org/?probe=5092bec86b) | Dec 07, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [e51903f612](https://linux-hardware.org/?probe=e51903f612) | Dec 05, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4e0782715d](https://linux-hardware.org/?probe=4e0782715d) | Dec 02, 2024 |
| HP            | Laptop 15-db0xxx            | [469069638e](https://linux-hardware.org/?probe=469069638e) | Dec 01, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [458a67a9e4](https://linux-hardware.org/?probe=458a67a9e4) | Nov 30, 2024 |
| HP            | EliteBook 8470p             | [f03062334f](https://linux-hardware.org/?probe=f03062334f) | Nov 29, 2024 |
| Dell          | XPS 13 9310                 | [5a464dff99](https://linux-hardware.org/?probe=5a464dff99) | Nov 27, 2024 |
| Toshiba       | Satellite L870-120          | [44263921b6](https://linux-hardware.org/?probe=44263921b6) | Nov 26, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MCS... | [2d30a85677](https://linux-hardware.org/?probe=2d30a85677) | Nov 18, 2024 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [ccf9df80ca](https://linux-hardware.org/?probe=ccf9df80ca) | Nov 11, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [7b749bf585](https://linux-hardware.org/?probe=7b749bf585) | Nov 11, 2024 |
| Dell          | Latitude 7640               | [f092c8cc9f](https://linux-hardware.org/?probe=f092c8cc9f) | Oct 27, 2024 |
| Lenovo        | ThinkPad T420 4236W9P       | [25a5b7315a](https://linux-hardware.org/?probe=25a5b7315a) | Oct 21, 2024 |
| HP            | Compaq 6910p                | [2d33276514](https://linux-hardware.org/?probe=2d33276514) | Oct 17, 2024 |
| Lenovo        | ThinkPad T420 4236W9P       | [676dd2d194](https://linux-hardware.org/?probe=676dd2d194) | Oct 14, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [ec688a0cae](https://linux-hardware.org/?probe=ec688a0cae) | Oct 13, 2024 |
| Dell          | XPS L322X                   | [ebe83a8923](https://linux-hardware.org/?probe=ebe83a8923) | Oct 07, 2024 |
| Lenovo        | ThinkPad T420 4236W9P       | [d55aedf9d2](https://linux-hardware.org/?probe=d55aedf9d2) | Oct 06, 2024 |
| HP            | Laptop 14s-dq3xxx           | [e93a1db49f](https://linux-hardware.org/?probe=e93a1db49f) | Oct 06, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [76e2b2a322](https://linux-hardware.org/?probe=76e2b2a322) | Sep 22, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a8bb2af7ad](https://linux-hardware.org/?probe=a8bb2af7ad) | Sep 20, 2024 |
| HP            | EliteBook 835 G8 Noteboo... | [7b97957b7a](https://linux-hardware.org/?probe=7b97957b7a) | Sep 10, 2024 |
| HP            | Laptop 14s-dq3xxx           | [c107b751c7](https://linux-hardware.org/?probe=c107b751c7) | Sep 03, 2024 |
| HP            | Laptop 14s-dq3xxx           | [d05b98ac9f](https://linux-hardware.org/?probe=d05b98ac9f) | Sep 01, 2024 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [b3dd1179a9](https://linux-hardware.org/?probe=b3dd1179a9) | Aug 05, 2024 |
| Dell          | Latitude 3340               | [533fe2ea9d](https://linux-hardware.org/?probe=533fe2ea9d) | Aug 04, 2024 |
| Dell          | XPS L322X                   | [8b14979f7c](https://linux-hardware.org/?probe=8b14979f7c) | Jul 30, 2024 |
| Dell          | XPS L322X                   | [bf4c97865c](https://linux-hardware.org/?probe=bf4c97865c) | Jul 30, 2024 |
| Dell          | Latitude E7450              | [ba9d36e59d](https://linux-hardware.org/?probe=ba9d36e59d) | Jul 25, 2024 |
| Apple         | MacBookPro9,2               | [4f3c1e544b](https://linux-hardware.org/?probe=4f3c1e544b) | Jul 15, 2024 |
| Valve         | Jupiter                     | [c83514f0ef](https://linux-hardware.org/?probe=c83514f0ef) | Jul 13, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [8bc58488a8](https://linux-hardware.org/?probe=8bc58488a8) | Jul 09, 2024 |
| Acer          | Aspire 5755G                | [9d85820d8a](https://linux-hardware.org/?probe=9d85820d8a) | Jul 06, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8046341f97](https://linux-hardware.org/?probe=8046341f97) | Jul 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a4411a1a03](https://linux-hardware.org/?probe=a4411a1a03) | Jul 03, 2024 |
| Notebook      | PE60RNE_RND_RNC             | [82b61a10fa](https://linux-hardware.org/?probe=82b61a10fa) | Jul 03, 2024 |
| Valve         | Jupiter                     | [64bd09dae7](https://linux-hardware.org/?probe=64bd09dae7) | Jul 02, 2024 |
| Lenovo        | ThinkPad T470 20HES00300    | [a311daa558](https://linux-hardware.org/?probe=a311daa558) | Jul 01, 2024 |
| Lenovo        | ThinkPad T470 20HES00300    | [8df67624a1](https://linux-hardware.org/?probe=8df67624a1) | Jul 01, 2024 |
| Valve         | Jupiter                     | [7cb4543c27](https://linux-hardware.org/?probe=7cb4543c27) | Jun 30, 2024 |
| Dell          | Latitude 5431               | [b945bd0e46](https://linux-hardware.org/?probe=b945bd0e46) | Jun 21, 2024 |
| Dell          | XPS L322X                   | [1af333c86d](https://linux-hardware.org/?probe=1af333c86d) | Jun 18, 2024 |
| Dell          | XPS L322X                   | [34bcf0a790](https://linux-hardware.org/?probe=34bcf0a790) | Jun 18, 2024 |
| Dell          | Latitude 5431               | [7469c5f44a](https://linux-hardware.org/?probe=7469c5f44a) | Jun 17, 2024 |
| Lenovo        | V15-ADA 82C7                | [161e412652](https://linux-hardware.org/?probe=161e412652) | Jun 09, 2024 |
| Acer          | Aspire A315-24P             | [f265233665](https://linux-hardware.org/?probe=f265233665) | Jun 05, 2024 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | [8534f873cf](https://linux-hardware.org/?probe=8534f873cf) | May 24, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [548c48e57a](https://linux-hardware.org/?probe=548c48e57a) | May 21, 2024 |
| Dell          | XPS 13 9360                 | [536f8ed319](https://linux-hardware.org/?probe=536f8ed319) | May 09, 2024 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [ed0902f81c](https://linux-hardware.org/?probe=ed0902f81c) | May 08, 2024 |
| HP            | Laptop 14-ck0xxx            | [2dee9df53a](https://linux-hardware.org/?probe=2dee9df53a) | May 02, 2024 |
| Dell          | Latitude 3300               | [639fb8097f](https://linux-hardware.org/?probe=639fb8097f) | May 02, 2024 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [eefd534cd5](https://linux-hardware.org/?probe=eefd534cd5) | May 01, 2024 |
| Acer          | Extensa 5620                | [4150199b68](https://linux-hardware.org/?probe=4150199b68) | Apr 29, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [fad4840965](https://linux-hardware.org/?probe=fad4840965) | Apr 26, 2024 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | [01d705d92b](https://linux-hardware.org/?probe=01d705d92b) | Apr 25, 2024 |
| Apple         | MacBookPro5,3               | [4661f5b412](https://linux-hardware.org/?probe=4661f5b412) | Apr 08, 2024 |
| Lenovo        | ThinkPad T490s 20NX006HM... | [52e2e29f44](https://linux-hardware.org/?probe=52e2e29f44) | Mar 22, 2024 |
| Dell          | Inspiron 5558               | [2202cb6328](https://linux-hardware.org/?probe=2202cb6328) | Mar 21, 2024 |
| HP            | 650                         | [d58bfc527e](https://linux-hardware.org/?probe=d58bfc527e) | Mar 17, 2024 |
| Lenovo        | ThinkPad P50 20EN0007MS     | [8c9bcaf098](https://linux-hardware.org/?probe=8c9bcaf098) | Mar 14, 2024 |
| HP            | EliteBook 840 G5            | [16dee4c095](https://linux-hardware.org/?probe=16dee4c095) | Mar 13, 2024 |
| Dell          | Latitude 5420 Rugged        | [f9c7c915c9](https://linux-hardware.org/?probe=f9c7c915c9) | Mar 08, 2024 |
| Lenovo        | ThinkPad T470 20HDS01L00    | [d3de9797e5](https://linux-hardware.org/?probe=d3de9797e5) | Mar 07, 2024 |
| Lenovo        | ThinkPad T470 20HDS01L00    | [48c9ed444c](https://linux-hardware.org/?probe=48c9ed444c) | Mar 06, 2024 |
| Lenovo        | ThinkPad T480s 20L8002UM... | [a8c23be08a](https://linux-hardware.org/?probe=a8c23be08a) | Mar 05, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c2b5dc013f](https://linux-hardware.org/?probe=c2b5dc013f) | Mar 03, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7c8e1659f2](https://linux-hardware.org/?probe=7c8e1659f2) | Feb 24, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [b1c2e786ed](https://linux-hardware.org/?probe=b1c2e786ed) | Feb 17, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0ea90e3ee0](https://linux-hardware.org/?probe=0ea90e3ee0) | Feb 17, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [50746a2234](https://linux-hardware.org/?probe=50746a2234) | Feb 09, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [07deb1efe3](https://linux-hardware.org/?probe=07deb1efe3) | Feb 04, 2024 |
| Valve         | Jupiter                     | [ff59f7877a](https://linux-hardware.org/?probe=ff59f7877a) | Feb 02, 2024 |
| Dell          | Latitude 7490               | [d2085f3674](https://linux-hardware.org/?probe=d2085f3674) | Jan 24, 2024 |
| Dell          | Inspiron N5010              | [ab07a9741b](https://linux-hardware.org/?probe=ab07a9741b) | Jan 13, 2024 |
| MSI           | Pulse GL66 11UDK            | [fdb748bed5](https://linux-hardware.org/?probe=fdb748bed5) | Jan 13, 2024 |
| Dell          | Inspiron N5010              | [8991ffeadc](https://linux-hardware.org/?probe=8991ffeadc) | Jan 04, 2024 |
| Acer          | Nitro AN517-55              | [f3e3de235b](https://linux-hardware.org/?probe=f3e3de235b) | Dec 23, 2023 |
| HP            | ProBook 6570b               | [7dbd0f9be1](https://linux-hardware.org/?probe=7dbd0f9be1) | Dec 21, 2023 |
| HP            | ProBook 6570b               | [7a4a6018b6](https://linux-hardware.org/?probe=7a4a6018b6) | Dec 21, 2023 |
| TUXEDO        | Polaris AMD Gen5            | [84a93dbb91](https://linux-hardware.org/?probe=84a93dbb91) | Dec 19, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [646c403e2f](https://linux-hardware.org/?probe=646c403e2f) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [7fc71d8954](https://linux-hardware.org/?probe=7fc71d8954) | Dec 16, 2023 |
| Apple         | MacBookAir6,2               | [62734db5de](https://linux-hardware.org/?probe=62734db5de) | Dec 10, 2023 |
| HP            | ProBook 4530s               | [5743a3e441](https://linux-hardware.org/?probe=5743a3e441) | Nov 28, 2023 |
| Dell          | Precision M4600             | [864f0c5cfe](https://linux-hardware.org/?probe=864f0c5cfe) | Nov 22, 2023 |
| Dell          | Precision M4600             | [af124219eb](https://linux-hardware.org/?probe=af124219eb) | Nov 18, 2023 |
| Acer          | Predator PH317-53           | [84650e7d6f](https://linux-hardware.org/?probe=84650e7d6f) | Nov 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [0d9316dbcf](https://linux-hardware.org/?probe=0d9316dbcf) | Oct 31, 2023 |
| HP            | 250 G5 Notebook PC          | [bc710e10c6](https://linux-hardware.org/?probe=bc710e10c6) | Oct 27, 2023 |
| Lenovo        | ThinkPad T440p 20AWS49Q0... | [65fa77246e](https://linux-hardware.org/?probe=65fa77246e) | Sep 21, 2023 |
| Dell          | Latitude E5550              | [9044f3b345](https://linux-hardware.org/?probe=9044f3b345) | Sep 12, 2023 |
| HP            | 250 G5 Notebook PC          | [773143cf61](https://linux-hardware.org/?probe=773143cf61) | Sep 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | [3d7ba31c2a](https://linux-hardware.org/?probe=3d7ba31c2a) | Aug 24, 2023 |
| Lenovo        | ThinkPad P50 20EQS4XN00     | [a517cc57b8](https://linux-hardware.org/?probe=a517cc57b8) | Aug 23, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | [cb5346a558](https://linux-hardware.org/?probe=cb5346a558) | Aug 17, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | [4bfb2c68ca](https://linux-hardware.org/?probe=4bfb2c68ca) | Aug 17, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [482b97d3de](https://linux-hardware.org/?probe=482b97d3de) | Aug 02, 2023 |
| Dell          | Vostro 3700                 | [96e4579b7b](https://linux-hardware.org/?probe=96e4579b7b) | Aug 01, 2023 |
| Intel         | powered classmate PC        | [ccbb0cb45a](https://linux-hardware.org/?probe=ccbb0cb45a) | Jul 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00bda81c25](https://linux-hardware.org/?probe=00bda81c25) | Jul 19, 2023 |
| HP            | ProBook 640 G1              | [8c2fd03132](https://linux-hardware.org/?probe=8c2fd03132) | Jul 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| Lenovo        | ThinkPad L480 20LTSAK70R    | [551d238ad3](https://linux-hardware.org/?probe=551d238ad3) | May 16, 2023 |
| Notebook      | N150SD/N155SD               | [55f219bc3f](https://linux-hardware.org/?probe=55f219bc3f) | May 11, 2023 |
| ASUSTek       | N550JK                      | [a799667521](https://linux-hardware.org/?probe=a799667521) | May 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [fdaef83d1e](https://linux-hardware.org/?probe=fdaef83d1e) | Apr 23, 2023 |
| MSI           | GF63 Thin 10SCXR            | [33e5d369a7](https://linux-hardware.org/?probe=33e5d369a7) | Apr 04, 2023 |
| Apple         | MacBookPro5,1               | [b06257fd9c](https://linux-hardware.org/?probe=b06257fd9c) | Mar 28, 2023 |
| Apple         | MacBookPro5,1               | [3a0d77d195](https://linux-hardware.org/?probe=3a0d77d195) | Mar 28, 2023 |
| Gigabyte      | G5 KD                       | [32afc6a4cf](https://linux-hardware.org/?probe=32afc6a4cf) | Mar 23, 2023 |
| Apple         | MacBookPro9,2               | [4efbf8be88](https://linux-hardware.org/?probe=4efbf8be88) | Mar 23, 2023 |
| GPD           | G1619-04                    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [c87313bdd4](https://linux-hardware.org/?probe=c87313bdd4) | Mar 20, 2023 |
| Lenovo        | ThinkPad T540p 20BFS3BR0... | [6218acf76f](https://linux-hardware.org/?probe=6218acf76f) | Mar 12, 2023 |
| Packard Be... | EasyNote TK87               | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [2141789e3a](https://linux-hardware.org/?probe=2141789e3a) | Jan 14, 2023 |
| Packard Be... | EasyNote TK87               | [f1c4c8b89e](https://linux-hardware.org/?probe=f1c4c8b89e) | Jan 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [ff12fe840d](https://linux-hardware.org/?probe=ff12fe840d) | Jan 12, 2023 |
| HP            | EliteBook 840 G2            | [4a85ebbc33](https://linux-hardware.org/?probe=4a85ebbc33) | Dec 26, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [d8b614d1ca](https://linux-hardware.org/?probe=d8b614d1ca) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1f904e68af](https://linux-hardware.org/?probe=1f904e68af) | Nov 29, 2022 |
| HP            | EliteBook 8460p             | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| ASUSTek       | N53Jf                       | [e4dc6e5cd9](https://linux-hardware.org/?probe=e4dc6e5cd9) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [b792955af6](https://linux-hardware.org/?probe=b792955af6) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [033e206fab](https://linux-hardware.org/?probe=033e206fab) | Nov 25, 2022 |
| Valve         | Jupiter                     | [0e77de9dba](https://linux-hardware.org/?probe=0e77de9dba) | Nov 20, 2022 |
| Acer          | Swift SF114-34              | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [b8dae15ebf](https://linux-hardware.org/?probe=b8dae15ebf) | Nov 09, 2022 |
| Alienware     | 17                          | [91358a0bec](https://linux-hardware.org/?probe=91358a0bec) | Nov 09, 2022 |
| Fujitsu       | LIFEBOOK A512               | [c479fc2cea](https://linux-hardware.org/?probe=c479fc2cea) | Nov 06, 2022 |
| HP            | Unknown                     | [aa28b92716](https://linux-hardware.org/?probe=aa28b92716) | Nov 06, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [36d7199821](https://linux-hardware.org/?probe=36d7199821) | Nov 01, 2022 |
| MSI           | GL72 6QD                    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| HUAWEI        | BOM-WXX9                    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| Dell          | Latitude 7390               | [268add52b3](https://linux-hardware.org/?probe=268add52b3) | Sep 19, 2022 |
| Chuwi         | HeroBook Pro                | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| ASUSTek       | 1225C                       | [91f049c977](https://linux-hardware.org/?probe=91f049c977) | Sep 09, 2022 |
| Fujitsu       | LIFEBOOK S760               | [d805aa67b2](https://linux-hardware.org/?probe=d805aa67b2) | Sep 09, 2022 |
| Apple         | MacBookPro11,1              | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Valve         | Jupiter                     | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| ASUSTek       | E502NA                      | [d65dd8fc52](https://linux-hardware.org/?probe=d65dd8fc52) | Jun 09, 2022 |
| ASUSTek       | E502NA                      | [d3d64dcb5b](https://linux-hardware.org/?probe=d3d64dcb5b) | Jun 09, 2022 |
| HP            | Presario CQ57               | [9f87592293](https://linux-hardware.org/?probe=9f87592293) | Jun 02, 2022 |
| Dell          | Latitude 5520               | [320ed1c4fc](https://linux-hardware.org/?probe=320ed1c4fc) | May 17, 2022 |
| Dell          | Latitude 5520               | [18823f33fb](https://linux-hardware.org/?probe=18823f33fb) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| HP            | EliteBook 8470p             | [0773b6244e](https://linux-hardware.org/?probe=0773b6244e) | May 11, 2022 |
| Lenovo        | ThinkPad T490s 20NX000AM... | [f07b38c5f9](https://linux-hardware.org/?probe=f07b38c5f9) | May 10, 2022 |
| Apple         | MacBookPro8,1               | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| mPTech        | ARC 11.6 128GB HD           | [aafa7cb1cb](https://linux-hardware.org/?probe=aafa7cb1cb) | May 07, 2022 |
| Dell          | Precision 7540              | [8b1b7dd8da](https://linux-hardware.org/?probe=8b1b7dd8da) | Apr 30, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | [a10fb9fe10](https://linux-hardware.org/?probe=a10fb9fe10) | Apr 23, 2022 |
| HP            | EliteBook 840 G2            | [b963507390](https://linux-hardware.org/?probe=b963507390) | Apr 19, 2022 |
| HP            | EliteBook 840 G2            | [fff8ad361e](https://linux-hardware.org/?probe=fff8ad361e) | Apr 19, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | [d948d987b4](https://linux-hardware.org/?probe=d948d987b4) | Apr 18, 2022 |
| Framework     | Laptop                      | [d4a02dfec9](https://linux-hardware.org/?probe=d4a02dfec9) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Dell          | Latitude 5520               | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | [7fb04e6c7d](https://linux-hardware.org/?probe=7fb04e6c7d) | Mar 03, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | [0f27bdf5a8](https://linux-hardware.org/?probe=0f27bdf5a8) | Mar 02, 2022 |
| Lenovo        | ThinkPad X220 429136G       | [324d66c0fc](https://linux-hardware.org/?probe=324d66c0fc) | Feb 23, 2022 |
| HP            | EliteBook Folio 1040 G2     | [5f3cd9e8d5](https://linux-hardware.org/?probe=5f3cd9e8d5) | Feb 16, 2022 |
| Dell          | XPS 15 7590                 | [96f97ed2d6](https://linux-hardware.org/?probe=96f97ed2d6) | Jan 23, 2022 |
| HP            | EliteBook 8460p             | [ca26ae6ff8](https://linux-hardware.org/?probe=ca26ae6ff8) | Dec 22, 2021 |
| ASUSTek       | K52Jc                       | [f6789bc7ac](https://linux-hardware.org/?probe=f6789bc7ac) | Dec 18, 2021 |
| HP            | EliteBook 820 G1            | [dbbe56da66](https://linux-hardware.org/?probe=dbbe56da66) | Dec 01, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [dc981a1604](https://linux-hardware.org/?probe=dc981a1604) | Nov 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [362a840c47](https://linux-hardware.org/?probe=362a840c47) | Nov 20, 2021 |
| Alienware     | 17                          | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Dell          | Precision 5550              | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Getac         | B300G4                      | [78b2fab1e0](https://linux-hardware.org/?probe=78b2fab1e0) | Oct 17, 2021 |
| HP            | Pavilion dv7                | [6c14033e55](https://linux-hardware.org/?probe=6c14033e55) | Oct 16, 2021 |
| HP            | Pavilion dv7                | [f93789f29a](https://linux-hardware.org/?probe=f93789f29a) | Oct 16, 2021 |
| Acer          | Extensa 5620                | [5cae4fe0fa](https://linux-hardware.org/?probe=5cae4fe0fa) | Oct 11, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Alienware     | 17                          | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4f393c5347](https://linux-hardware.org/?probe=4f393c5347) | Sep 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| ASUSTek       | UX530UX                     | [c713dcf9e2](https://linux-hardware.org/?probe=c713dcf9e2) | Sep 08, 2021 |
| ASUSTek       | X510UA                      | [0a8045cc4f](https://linux-hardware.org/?probe=0a8045cc4f) | Sep 05, 2021 |
| ASUSTek       | X550ZA                      | [210ca88228](https://linux-hardware.org/?probe=210ca88228) | Aug 30, 2021 |
| Lenovo        | ThinkPad X201 3680CG7       | [9565bae9c3](https://linux-hardware.org/?probe=9565bae9c3) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [75619baa6e](https://linux-hardware.org/?probe=75619baa6e) | Aug 29, 2021 |
| ASUSTek       | X550ZA                      | [0a21d3b326](https://linux-hardware.org/?probe=0a21d3b326) | Aug 27, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| Lenovo        | ThinkPad 20AY001DMH         | [d3f7b62a42](https://linux-hardware.org/?probe=d3f7b62a42) | Aug 19, 2021 |
| Dell          | XPS 15 9500                 | [f21459caa1](https://linux-hardware.org/?probe=f21459caa1) | Aug 19, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | [5f9d1cd1a6](https://linux-hardware.org/?probe=5f9d1cd1a6) | Aug 18, 2021 |
| HP            | EliteBook 8460p             | [0ce69e02fa](https://linux-hardware.org/?probe=0ce69e02fa) | Aug 17, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | [fcd91a58e2](https://linux-hardware.org/?probe=fcd91a58e2) | Aug 13, 2021 |
| HP            | Pavilion dv7                | [a56935a751](https://linux-hardware.org/?probe=a56935a751) | Aug 09, 2021 |
| MSI           | GP62M 7RDX                  | [f02c96473f](https://linux-hardware.org/?probe=f02c96473f) | Jul 30, 2021 |
| Dell          | Inspiron 15-3567            | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | [7207e6aa0f](https://linux-hardware.org/?probe=7207e6aa0f) | Jul 08, 2021 |
| Dell          | XPS 15 9500                 | [a47fb764b4](https://linux-hardware.org/?probe=a47fb764b4) | Jul 01, 2021 |
| Lenovo        | IdeaPadFlex 10 20324        | [d96aea9f90](https://linux-hardware.org/?probe=d96aea9f90) | Jun 26, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [cb4242a344](https://linux-hardware.org/?probe=cb4242a344) | Jun 15, 2021 |
| HP            | EliteBook 8460p             | [7bf0e678ea](https://linux-hardware.org/?probe=7bf0e678ea) | Jun 13, 2021 |
| Lenovo        | ThinkPad T450s 20BWS1RG0... | [79d386a567](https://linux-hardware.org/?probe=79d386a567) | Jun 08, 2021 |
| Dell          | Latitude 5511               | [933fb253d4](https://linux-hardware.org/?probe=933fb253d4) | Jun 07, 2021 |
| Dell          | Latitude 5511               | [7b5e6276c0](https://linux-hardware.org/?probe=7b5e6276c0) | Jun 07, 2021 |
| HP            | EliteBook 8460p             | [6a7fe6469a](https://linux-hardware.org/?probe=6a7fe6469a) | Jun 06, 2021 |
| Timi          | RedmiBook 14 II             | [8700a7eaed](https://linux-hardware.org/?probe=8700a7eaed) | May 31, 2021 |
| Dell          | XPS 15 9500                 | [1ba665b0b3](https://linux-hardware.org/?probe=1ba665b0b3) | May 24, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [3ae2f83c9f](https://linux-hardware.org/?probe=3ae2f83c9f) | May 23, 2021 |
| Dell          | G5 5587                     | [39be80ad79](https://linux-hardware.org/?probe=39be80ad79) | May 19, 2021 |
| Dell          | Precision 5530              | [aa0aa77e62](https://linux-hardware.org/?probe=aa0aa77e62) | May 16, 2021 |
| HP            | EliteBook 8460p             | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| Dell          | Vostro V131                 | [43fe3f190f](https://linux-hardware.org/?probe=43fe3f190f) | May 14, 2021 |
| HP            | EliteBook 8460p             | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Lenovo        | Y50-70 20378                | [fe95dd9355](https://linux-hardware.org/?probe=fe95dd9355) | May 11, 2021 |
| Dell          | System Inspiron N7110       | [f5f418c337](https://linux-hardware.org/?probe=f5f418c337) | May 02, 2021 |
| Dell          | XPS 15 9500                 | [1bbe4079c5](https://linux-hardware.org/?probe=1bbe4079c5) | Apr 27, 2021 |
| HP            | Compaq nx6120 (PV170PA#U... | [5f105dda68](https://linux-hardware.org/?probe=5f105dda68) | Apr 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f84cf26650](https://linux-hardware.org/?probe=f84cf26650) | Apr 10, 2021 |
| Dell          | Inspiron N5110              | [a677fe0972](https://linux-hardware.org/?probe=a677fe0972) | Apr 08, 2021 |
| Dell          | Latitude E5430 non-vPro     | [ed6b3b5754](https://linux-hardware.org/?probe=ed6b3b5754) | Apr 04, 2021 |
| Dell          | Latitude E5430 non-vPro     | [218092e59f](https://linux-hardware.org/?probe=218092e59f) | Apr 03, 2021 |
| Lenovo        | Y50-70 20378                | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Dell          | XPS 15 7590                 | [6e6dc77b21](https://linux-hardware.org/?probe=6e6dc77b21) | Mar 29, 2021 |
| Samsung       | R410                        | [331d909654](https://linux-hardware.org/?probe=331d909654) | Mar 27, 2021 |
| Samsung       | R410                        | [5aa6fee818](https://linux-hardware.org/?probe=5aa6fee818) | Mar 25, 2021 |
| Samsung       | R410                        | [d3f94bcc8c](https://linux-hardware.org/?probe=d3f94bcc8c) | Mar 24, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [fb33c2e9b9](https://linux-hardware.org/?probe=fb33c2e9b9) | Mar 17, 2021 |
| Notebook      | W35xSS_370SS                | [0e98472f08](https://linux-hardware.org/?probe=0e98472f08) | Mar 02, 2021 |
| Lenovo        | ThinkPad T61 766112G        | [04ec7d5efd](https://linux-hardware.org/?probe=04ec7d5efd) | Feb 25, 2021 |
| Acer          | Aspire V5-572P              | [61834c786c](https://linux-hardware.org/?probe=61834c786c) | Feb 24, 2021 |
| HP            | EliteBook 850 G2            | [4c935ce981](https://linux-hardware.org/?probe=4c935ce981) | Feb 18, 2021 |
| HP            | EliteBook 850 G2            | [69090d5f4c](https://linux-hardware.org/?probe=69090d5f4c) | Feb 17, 2021 |
| Dell          | XPS 15 9500                 | [8652b51903](https://linux-hardware.org/?probe=8652b51903) | Jan 20, 2021 |
| Dell          | XPS 15 9500                 | [77be7c1164](https://linux-hardware.org/?probe=77be7c1164) | Jan 18, 2021 |
| HP            | EliteBook 840 G5            | [59aaeda6a9](https://linux-hardware.org/?probe=59aaeda6a9) | Dec 28, 2020 |
| Fujitsu       | LIFEBOOK E744               | [81daeffb49](https://linux-hardware.org/?probe=81daeffb49) | Dec 28, 2020 |
| Timi          | RedmiBook 16                | [34bc3ceb48](https://linux-hardware.org/?probe=34bc3ceb48) | Dec 24, 2020 |
| MSI           | GT70 2OC/2OD                | [e52bbc40aa](https://linux-hardware.org/?probe=e52bbc40aa) | Dec 19, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | [95355fcff6](https://linux-hardware.org/?probe=95355fcff6) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | [3ee030e6ac](https://linux-hardware.org/?probe=3ee030e6ac) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 765912G        | [9651814a46](https://linux-hardware.org/?probe=9651814a46) | Dec 08, 2020 |
| Lenovo        | Y50-70 20378                | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [4defcea6f8](https://linux-hardware.org/?probe=4defcea6f8) | Nov 24, 2020 |
| Notebook      | W35xSS_370SS                | [ed0e6634d4](https://linux-hardware.org/?probe=ed0e6634d4) | Sep 29, 2020 |
| HP            | EliteBook 745 G5            | [e9d2889a6d](https://linux-hardware.org/?probe=e9d2889a6d) | Sep 28, 2020 |
| Dell          | Latitude 7490               | [cfd6c8dcc4](https://linux-hardware.org/?probe=cfd6c8dcc4) | Sep 28, 2020 |
| TUXEDO        | Book BA1510                 | [d89436074e](https://linux-hardware.org/?probe=d89436074e) | Sep 23, 2020 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [3399940dd9](https://linux-hardware.org/?probe=3399940dd9) | Sep 17, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [5bd6ca5aba](https://linux-hardware.org/?probe=5bd6ca5aba) | Sep 15, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [83263681eb](https://linux-hardware.org/?probe=83263681eb) | Sep 15, 2020 |
| Notebook      | W35xSS_370SS                | [5b35813fca](https://linux-hardware.org/?probe=5b35813fca) | Sep 10, 2020 |
| HP            | ZBook 17                    | [605dfd3279](https://linux-hardware.org/?probe=605dfd3279) | Sep 08, 2020 |
| HP            | ZBook 17                    | [09e5bd8eb6](https://linux-hardware.org/?probe=09e5bd8eb6) | Sep 08, 2020 |
| ASUSTek       | X542UQR                     | [7782f01f3c](https://linux-hardware.org/?probe=7782f01f3c) | Sep 04, 2020 |
| ASUSTek       | E502MA                      | [1eb9e7db73](https://linux-hardware.org/?probe=1eb9e7db73) | Sep 01, 2020 |
| ASUSTek       | X501U                       | [006dc7a8d6](https://linux-hardware.org/?probe=006dc7a8d6) | Aug 15, 2020 |
| Lenovo        | ThinkPad X220 4291R30       | [bdf2c40591](https://linux-hardware.org/?probe=bdf2c40591) | Aug 06, 2020 |
| Lenovo        | ThinkPad T490 20N2000NMX    | [8f21de6e06](https://linux-hardware.org/?probe=8f21de6e06) | Aug 05, 2020 |
| Acer          | Extensa 5620                | [dba48971a3](https://linux-hardware.org/?probe=dba48971a3) | Jul 24, 2020 |
| Lenovo        | ThinkPad T480s 20L7001VU... | [03bcc8865c](https://linux-hardware.org/?probe=03bcc8865c) | Jul 23, 2020 |
| HP            | Presario CQ56               | [f668bc59f5](https://linux-hardware.org/?probe=f668bc59f5) | Jun 23, 2020 |
| HP            | Presario CQ56               | [b8db4c3694](https://linux-hardware.org/?probe=b8db4c3694) | Jun 23, 2020 |
| Dell          | XPS 15 9560                 | [867ca870fd](https://linux-hardware.org/?probe=867ca870fd) | Jun 14, 2020 |
| Samsung       | 535U3C                      | [e7bc13b354](https://linux-hardware.org/?probe=e7bc13b354) | May 30, 2020 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | [26c8949a0a](https://linux-hardware.org/?probe=26c8949a0a) | May 29, 2020 |
| Lenovo        | ThinkPad T540p 20BFS4510... | [6c5bf8bfbe](https://linux-hardware.org/?probe=6c5bf8bfbe) | May 05, 2020 |
| HP            | EliteBook 840 G2            | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [a1a1ce6e00](https://linux-hardware.org/?probe=a1a1ce6e00) | May 02, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [e3321de949](https://linux-hardware.org/?probe=e3321de949) | May 02, 2020 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [35b95432ac](https://linux-hardware.org/?probe=35b95432ac) | Apr 30, 2020 |
| Dell          | XPS 15 9560                 | [eea0fa4941](https://linux-hardware.org/?probe=eea0fa4941) | Apr 25, 2020 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [91770bcd78](https://linux-hardware.org/?probe=91770bcd78) | Apr 22, 2020 |
| MSI           | GS75 Stealth 8SE            | [1c50333136](https://linux-hardware.org/?probe=1c50333136) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | [cdca82a043](https://linux-hardware.org/?probe=cdca82a043) | Apr 05, 2020 |
| Samsung       | 275E4E/275E5E               | [6b624f1079](https://linux-hardware.org/?probe=6b624f1079) | Mar 12, 2020 |
| Lenovo        | ThinkPad A285 20MXS0BG00    | [4dabcb8d3f](https://linux-hardware.org/?probe=4dabcb8d3f) | Mar 11, 2020 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [c71def9148](https://linux-hardware.org/?probe=c71def9148) | Feb 18, 2020 |
| HP            | EliteBook 8470p             | [ed5efcdf48](https://linux-hardware.org/?probe=ed5efcdf48) | Feb 03, 2020 |
| Dell          | Precision 5510              | [68c56e0ab4](https://linux-hardware.org/?probe=68c56e0ab4) | Dec 02, 2019 |
| HP            | Pavilion Gaming Notebook    | [c4917de06e](https://linux-hardware.org/?probe=c4917de06e) | Oct 17, 2019 |
| HP            | Pavilion Gaming Notebook    | [9f867b307a](https://linux-hardware.org/?probe=9f867b307a) | Oct 12, 2019 |
| HP            | Pavilion Gaming Notebook    | [f3f1a208c1](https://linux-hardware.org/?probe=f3f1a208c1) | Sep 26, 2019 |
| HP            | Pavilion Gaming Notebook    | [0639ef182a](https://linux-hardware.org/?probe=0639ef182a) | Sep 20, 2019 |
| HP            | Pavilion Gaming Notebook    | [3b99dff2c2](https://linux-hardware.org/?probe=3b99dff2c2) | Sep 19, 2019 |
| Dell          | Inspiron 5748               | [75647e5457](https://linux-hardware.org/?probe=75647e5457) | Sep 03, 2019 |
| Acer          | Aspire V3-771               | [335c3fea78](https://linux-hardware.org/?probe=335c3fea78) | Aug 10, 2019 |
| Quanta        | TWH                         | [b6c3554305](https://linux-hardware.org/?probe=b6c3554305) | Aug 05, 2019 |
| Quanta        | TWH                         | [243be58298](https://linux-hardware.org/?probe=243be58298) | Aug 05, 2019 |
| HP            | OMEN by Laptop              | [4a247c1234](https://linux-hardware.org/?probe=4a247c1234) | Aug 03, 2019 |
| Lenovo        | V110-15ISK 80TL             | [15bfdc0f25](https://linux-hardware.org/?probe=15bfdc0f25) | Aug 03, 2019 |
| HP            | OMEN by Laptop              | [cd37f24ff8](https://linux-hardware.org/?probe=cd37f24ff8) | Aug 01, 2019 |
| Dell          | Inspiron 5558               | [f26b9a5e36](https://linux-hardware.org/?probe=f26b9a5e36) | Jun 29, 2019 |
| ASUSTek       | N56VZ                       | [02928f6b1e](https://linux-hardware.org/?probe=02928f6b1e) | Jun 25, 2019 |
| Lenovo        | IdeaPad U330p 20267         | [1edb7b5f96](https://linux-hardware.org/?probe=1edb7b5f96) | May 25, 2019 |
| HP            | Pavilion dv4000 (EK980EA... | [837230178b](https://linux-hardware.org/?probe=837230178b) | May 23, 2019 |
| Lenovo        | G50-70 20351                | [84c3544bb2](https://linux-hardware.org/?probe=84c3544bb2) | May 20, 2019 |
| Samsung       | 275E4E/275E5E               | [60cb87eeb6](https://linux-hardware.org/?probe=60cb87eeb6) | May 11, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | [cfcb3e3b82](https://linux-hardware.org/?probe=cfcb3e3b82) | May 02, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | [c577dfbf17](https://linux-hardware.org/?probe=c577dfbf17) | May 02, 2019 |
| Samsung       | 770Z5E/780Z5E               | [e07529a7fc](https://linux-hardware.org/?probe=e07529a7fc) | Apr 14, 2019 |
| Fujitsu Si... | AMILO La1703                | [4530891733](https://linux-hardware.org/?probe=4530891733) | Apr 01, 2019 |
| Dell          | Inspiron 3543               | [e411551975](https://linux-hardware.org/?probe=e411551975) | Mar 21, 2019 |
| Dell          | Inspiron 3543               | [f85fec55bb](https://linux-hardware.org/?probe=f85fec55bb) | Mar 19, 2019 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [bee48cd1c5](https://linux-hardware.org/?probe=bee48cd1c5) | Mar 09, 2019 |
| Lenovo        | ThinkPad T580 20L90026MX    | [14afd9ea12](https://linux-hardware.org/?probe=14afd9ea12) | Feb 27, 2019 |
| HP            | ProBook 470 G1              | [268414d1b5](https://linux-hardware.org/?probe=268414d1b5) | Feb 07, 2019 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [5357d8ad3a](https://linux-hardware.org/?probe=5357d8ad3a) | Dec 04, 2018 |
| Lenovo        | Y520-15IKBN 80WK            | [a075fc73d3](https://linux-hardware.org/?probe=a075fc73d3) | Oct 09, 2018 |
| ASUSTek       | X55A                        | [403b1aa1d7](https://linux-hardware.org/?probe=403b1aa1d7) | May 08, 2018 |
| ASUSTek       | K40IJ                       | [24366329c2](https://linux-hardware.org/?probe=24366329c2) | May 07, 2018 |
| Dell          | Inspiron N5110              | [d7b2f7f719](https://linux-hardware.org/?probe=d7b2f7f719) | Oct 05, 2017 |
| Acer          | Aspire 6530G                | [2f88dba791](https://linux-hardware.org/?probe=2f88dba791) | Aug 13, 2017 |
| HP            | Compaq nx7400 (RH387EA#A... | [116c8bc9de](https://linux-hardware.org/?probe=116c8bc9de) | Jun 03, 2017 |
| Toshiba       | Satellite L855              | [de2e163003](https://linux-hardware.org/?probe=de2e163003) | May 17, 2017 |
| HP            | Pavilion dv5                | [3191678465](https://linux-hardware.org/?probe=3191678465) | May 04, 2017 |
| HP            | Pavilion dv5                | [1f21f421ed](https://linux-hardware.org/?probe=1f21f421ed) | May 02, 2017 |
| Quanta        | TWH                         | [4807bd6702](https://linux-hardware.org/?probe=4807bd6702) | Apr 28, 2017 |
| Quanta        | TWH                         | [0105619fb7](https://linux-hardware.org/?probe=0105619fb7) | Apr 27, 2017 |
| Acer          | Aspire 5541                 | [efa45ad21c](https://linux-hardware.org/?probe=efa45ad21c) | Nov 14, 2016 |
| Acer          | Aspire 5541                 | [b61eb7bcb0](https://linux-hardware.org/?probe=b61eb7bcb0) | Nov 13, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 22.04        | 26        | 8.5%    |
| Ubuntu 20.04        | 20        | 6.54%   |
| Ubuntu 18.04        | 14        | 4.58%   |
| Arch Rolling        | 14        | 4.58%   |
| ArcoLinux Rolling   | 10        | 3.27%   |
| Ubuntu 24.04        | 8         | 2.61%   |
| Arch                | 7         | 2.29%   |
| Ubuntu MATE 22.04   | 6         | 1.96%   |
| Ubuntu 19.04        | 6         | 1.96%   |
| Pop!_OS 22.04       | 5         | 1.63%   |
| Linux Mint 20.1     | 5         | 1.63%   |
| Fedora 42           | 5         | 1.63%   |
| Zorin 17            | 4         | 1.31%   |
| Linux Mint 21.2     | 4         | 1.31%   |
| Kubuntu 22.04       | 4         | 1.31%   |
| Fedora 41           | 4         | 1.31%   |
| Fedora 34           | 4         | 1.31%   |
| Debian 11           | 4         | 1.31%   |
| ROSA R9             | 3         | 0.98%   |
| ROSA R8.1           | 3         | 0.98%   |
| ROSA R11            | 3         | 0.98%   |
| Pop!_OS 20.04       | 3         | 0.98%   |
| OpenMandriva 4.3    | 3         | 0.98%   |
| OpenMandriva 4.2    | 3         | 0.98%   |
| Manjaro             | 3         | 0.98%   |
| Linux Mint 20.3     | 3         | 0.98%   |
| Kubuntu 20.04       | 3         | 0.98%   |
| KDE neon 24.04      | 3         | 0.98%   |
| Fedora 36           | 3         | 0.98%   |
| EndeavourOS Rolling | 3         | 0.98%   |
| Debian 12           | 3         | 0.98%   |
| Zorin 16            | 2         | 0.65%   |
| Xubuntu 20.04       | 2         | 0.65%   |
| Ubuntu 20.10        | 2         | 0.65%   |
| Ubuntu 19.10        | 2         | 0.65%   |
| ROSA 12.2           | 2         | 0.65%   |
| Reborn OS           | 2         | 0.65%   |
| OpenMandriva 25.01  | 2         | 0.65%   |
| Methaneos Stable    | 2         | 0.65%   |
| Manjaro 20.1        | 2         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 78        | 26.26%  |
| Linux Mint   | 26        | 8.75%   |
| Fedora       | 23        | 7.74%   |
| Arch         | 21        | 7.07%   |
| ROSA         | 15        | 5.05%   |
| OpenMandriva | 14        | 4.71%   |
| Debian       | 12        | 4.04%   |
| Pop!_OS      | 10        | 3.37%   |
| ArcoLinux    | 10        | 3.37%   |
| Manjaro      | 9         | 3.03%   |
| Kubuntu      | 9         | 3.03%   |
| Zorin        | 7         | 2.36%   |
| Ubuntu MATE  | 7         | 2.36%   |
| KDE neon     | 7         | 2.36%   |
| Xubuntu      | 6         | 2.02%   |
| Elementary   | 5         | 1.68%   |
| Endless      | 4         | 1.35%   |
| SteamOS      | 3         | 1.01%   |
| NixOS        | 3         | 1.01%   |
| Lubuntu      | 3         | 1.01%   |
| Kali         | 3         | 1.01%   |
| EndeavourOS  | 3         | 1.01%   |
| Reborn OS    | 2         | 0.67%   |
| Nobara       | 2         | 0.67%   |
| Methaneos    | 2         | 0.67%   |
| Clear Linux  | 2         | 0.67%   |
| ALT Linux    | 2         | 0.67%   |
| Xero         | 1         | 0.34%   |
| Ubuntu Unity | 1         | 0.34%   |
| TUXEDO OS    | 1         | 0.34%   |
| Parrot       | 1         | 0.34%   |
| MX           | 1         | 0.34%   |
| LMDE         | 1         | 0.34%   |
| Garuda Linux | 1         | 0.34%   |
| Devuan       | 1         | 0.34%   |
| ChimeraOS    | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 6         | 1.81%   |
| 6.2.0-26-generic                   | 4         | 1.21%   |
| 5.15.0-52-generic                  | 4         | 1.21%   |
| 6.8.0-60-generic                   | 3         | 0.91%   |
| 6.8.0-49-generic                   | 3         | 0.91%   |
| 6.14.0-33-generic                  | 3         | 0.91%   |
| 5.4.0-47-generic                   | 3         | 0.91%   |
| 5.4.0-28-generic                   | 3         | 0.91%   |
| 5.16.7-desktop-1omv4003            | 3         | 0.91%   |
| 5.15.0-53-generic                  | 3         | 0.91%   |
| 5.10.14-desktop-1omv4002           | 3         | 0.91%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 3         | 0.91%   |
| 6.9.6-methane-jn27                 | 2         | 0.6%    |
| 6.9.3-76060903-generic             | 2         | 0.6%    |
| 6.8.0-52-generic                   | 2         | 0.6%    |
| 6.8.0-51-generic                   | 2         | 0.6%    |
| 6.8.0-45-generic                   | 2         | 0.6%    |
| 6.8.0-31-generic                   | 2         | 0.6%    |
| 6.5.0-9-generic                    | 2         | 0.6%    |
| 6.5.0-45-generic                   | 2         | 0.6%    |
| 6.2.0-39-generic                   | 2         | 0.6%    |
| 6.14.2-desktop-3omv2590            | 2         | 0.6%    |
| 6.12.9-desktop-1omv2490            | 2         | 0.6%    |
| 6.1.0-kali7-amd64                  | 2         | 0.6%    |
| 6.1.0-18-amd64                     | 2         | 0.6%    |
| 5.8.0-53-generic                   | 2         | 0.6%    |
| 5.4.0-88-generic                   | 2         | 0.6%    |
| 5.4.0-65-generic                   | 2         | 0.6%    |
| 5.15.2-arch1-1                     | 2         | 0.6%    |
| 5.15.0-56-generic                  | 2         | 0.6%    |
| 5.15.0-126-generic                 | 2         | 0.6%    |
| 5.13.10-arch1-1                    | 2         | 0.6%    |
| 5.13.0-39-generic                  | 2         | 0.6%    |
| 5.11.0-27-generic                  | 2         | 0.6%    |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 0.6%    |
| 5.10.0-28-amd64                    | 2         | 0.6%    |
| 5.0.0-23-generic                   | 2         | 0.6%    |
| 4.18.0-15-generic                  | 2         | 0.6%    |
| 4.15.0-45-generic                  | 2         | 0.6%    |
| 6.9.3-arch1-1                      | 1         | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 32        | 9.94%   |
| 5.15.0  | 25        | 7.76%   |
| 6.8.0   | 19        | 5.9%    |
| 6.5.0   | 13        | 4.04%   |
| 4.15.0  | 13        | 4.04%   |
| 6.2.0   | 9         | 2.8%    |
| 5.8.0   | 9         | 2.8%    |
| 5.11.0  | 8         | 2.48%   |
| 5.13.0  | 7         | 2.17%   |
| 5.0.0   | 7         | 2.17%   |
| 6.14.0  | 6         | 1.86%   |
| 6.1.0   | 5         | 1.55%   |
| 4.18.0  | 5         | 1.55%   |
| 5.10.0  | 4         | 1.24%   |
| 4.9.20  | 4         | 1.24%   |
| 6.9.3   | 3         | 0.93%   |
| 6.17.9  | 3         | 0.93%   |
| 6.12.9  | 3         | 0.93%   |
| 6.11.0  | 3         | 0.93%   |
| 5.3.0   | 3         | 0.93%   |
| 5.19.0  | 3         | 0.93%   |
| 5.16.7  | 3         | 0.93%   |
| 5.10.14 | 3         | 0.93%   |
| 6.9.6   | 2         | 0.62%   |
| 6.6.65  | 2         | 0.62%   |
| 6.6.10  | 2         | 0.62%   |
| 6.14.2  | 2         | 0.62%   |
| 6.13.7  | 2         | 0.62%   |
| 6.13.5  | 2         | 0.62%   |
| 6.13.2  | 2         | 0.62%   |
| 6.0.9   | 2         | 0.62%   |
| 5.17.1  | 2         | 0.62%   |
| 5.15.2  | 2         | 0.62%   |
| 5.13.13 | 2         | 0.62%   |
| 5.13.12 | 2         | 0.62%   |
| 5.13.10 | 2         | 0.62%   |
| 5.11.12 | 2         | 0.62%   |
| 5.10.74 | 2         | 0.62%   |
| 6.9.0   | 1         | 0.31%   |
| 6.8.8   | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 33        | 10.41%  |
| 5.15    | 30        | 9.46%   |
| 6.8     | 21        | 6.62%   |
| 5.13    | 16        | 5.05%   |
| 6.5     | 15        | 4.73%   |
| 5.10    | 14        | 4.42%   |
| 4.15    | 13        | 4.1%    |
| 6.1     | 12        | 3.79%   |
| 6.2     | 11        | 3.47%   |
| 5.11    | 11        | 3.47%   |
| 6.6     | 10        | 3.15%   |
| 6.11    | 10        | 3.15%   |
| 5.8     | 10        | 3.15%   |
| 6.14    | 9         | 2.84%   |
| 6.12    | 9         | 2.84%   |
| 5.0     | 8         | 2.52%   |
| 4.9     | 7         | 2.21%   |
| 6.9     | 6         | 1.89%   |
| 6.17    | 6         | 1.89%   |
| 6.15    | 6         | 1.89%   |
| 5.16    | 6         | 1.89%   |
| 6.13    | 5         | 1.58%   |
| 6.0     | 5         | 1.58%   |
| 4.18    | 5         | 1.58%   |
| 5.9     | 4         | 1.26%   |
| 5.19    | 4         | 1.26%   |
| 5.17    | 4         | 1.26%   |
| 6.16    | 3         | 0.95%   |
| 5.3     | 3         | 0.95%   |
| 5.14    | 3         | 0.95%   |
| 5.12    | 3         | 0.95%   |
| 6.7     | 2         | 0.63%   |
| 6.3     | 2         | 0.63%   |
| 6.10    | 2         | 0.63%   |
| 4.19    | 2         | 0.63%   |
| 6.4     | 1         | 0.32%   |
| 5.6     | 1         | 0.32%   |
| 5.5     | 1         | 0.32%   |
| 4.4     | 1         | 0.32%   |
| 4.10    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 285       | 98.28%  |
| i686   | 5         | 1.72%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 109       | 36.33%  |
| KDE5       | 39        | 13%     |
| Unknown    | 28        | 9.33%   |
| XFCE       | 23        | 7.67%   |
| KDE6       | 23        | 7.67%   |
| X-Cinnamon | 21        | 7%      |
| MATE       | 13        | 4.33%   |
| KDE4       | 8         | 2.67%   |
| KDE        | 6         | 2%      |
| Pantheon   | 5         | 1.67%   |
| LXQt       | 4         | 1.33%   |
| i3         | 4         | 1.33%   |
| Hyprland   | 3         | 1%      |
| Unity      | 2         | 0.67%   |
| niri       | 2         | 0.67%   |
| LXDE       | 2         | 0.67%   |
| Budgie     | 2         | 0.67%   |
| awesome    | 2         | 0.67%   |
| Yoyo       | 1         | 0.33%   |
| openbox    | 1         | 0.33%   |
| COSMIC     | 1         | 0.33%   |
| Cinnamon   | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 195       | 66.1%   |
| Wayland | 86        | 29.15%  |
| Unknown | 12        | 4.07%   |
| Tty     | 2         | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 124       | 41.61%  |
| SDDM           | 57        | 19.13%  |
| GDM3           | 41        | 13.76%  |
| LightDM        | 32        | 10.74%  |
| GDM            | 24        | 8.05%   |
| TDM            | 9         | 3.02%   |
| KDM            | 8         | 2.68%   |
| GREETD         | 2         | 0.67%   |
| COSMIC-GREETER | 1         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 157       | 53.4%   |
| et_EE           | 45        | 15.31%  |
| Unknown         | 33        | 11.22%  |
| ru_RU           | 23        | 7.82%   |
| en_GB           | 15        | 5.1%    |
| C               | 10        | 3.4%    |
| de_DE           | 3         | 1.02%   |
| uk_UA           | 1         | 0.34%   |
| ru_UA           | 1         | 0.34%   |
| fr_FR           | 1         | 0.34%   |
| es_MX           | 1         | 0.34%   |
| en_US.utf-8     | 1         | 0.34%   |
| en_US.iso885915 | 1         | 0.34%   |
| en_DK           | 1         | 0.34%   |
| en_AU           | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 150       | 50.51%  |
| EFI  | 147       | 49.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 195       | 66.33%  |
| Btrfs   | 40        | 13.61%  |
| Tmpfs   | 20        | 6.8%    |
| Overlay | 14        | 4.76%   |
| Unknown | 12        | 4.08%   |
| Zfs     | 7         | 2.38%   |
| Xfs     | 4         | 1.36%   |
| Ext3    | 2         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 143       | 48.31%  |
| Unknown | 126       | 42.57%  |
| MBR     | 27        | 9.12%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 264       | 90.41%  |
| Yes       | 28        | 9.59%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 214       | 72.3%   |
| Yes       | 82        | 27.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 96        | 33.1%   |
| Hewlett-Packard     | 51        | 17.59%  |
| Dell                | 45        | 15.52%  |
| ASUSTek Computer    | 27        | 9.31%   |
| Apple               | 11        | 3.79%   |
| Acer                | 11        | 3.79%   |
| Samsung Electronics | 9         | 3.1%    |
| MSI                 | 6         | 2.07%   |
| Valve               | 4         | 1.38%   |
| Notebook            | 4         | 1.38%   |
| Fujitsu             | 3         | 1.03%   |
| TUXEDO              | 2         | 0.69%   |
| Toshiba             | 2         | 0.69%   |
| Timi                | 2         | 0.69%   |
| Quanta              | 2         | 0.69%   |
| HUAWEI              | 2         | 0.69%   |
| Framework           | 2         | 0.69%   |
| Chuwi               | 2         | 0.69%   |
| Alienware           | 2         | 0.69%   |
| Packard Bell        | 1         | 0.34%   |
| mPTech              | 1         | 0.34%   |
| Intel               | 1         | 0.34%   |
| GPD                 | 1         | 0.34%   |
| Gigabyte Technology | 1         | 0.34%   |
| Getac               | 1         | 0.34%   |
| Fujitsu Siemens     | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 4         | 1.38%   |
| HP EliteBook 8470p                                    | 3         | 1.03%   |
| HP EliteBook 8460p                                    | 3         | 1.03%   |
| Dell Latitude 7490                                    | 3         | 1.03%   |
| Quanta TWH                                            | 2         | 0.69%   |
| Lenovo Y50-70 20378                                   | 2         | 0.69%   |
| Lenovo ThinkPad T14 Gen 5 21MCS00J00                  | 2         | 0.69%   |
| HP ProBook 640 G1                                     | 2         | 0.69%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 0.69%   |
| HP Pavilion dv7                                       | 2         | 0.69%   |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 0.69%   |
| HP EliteBook Folio 1040 G2                            | 2         | 0.69%   |
| HP EliteBook 840 G8 Notebook PC                       | 2         | 0.69%   |
| HP EliteBook 840 G5                                   | 2         | 0.69%   |
| HP EliteBook 840 G2                                   | 2         | 0.69%   |
| Dell Inspiron N5110                                   | 2         | 0.69%   |
| Dell Inspiron 5558                                    | 2         | 0.69%   |
| Dell Inspiron 15-3567                                 | 2         | 0.69%   |
| ASUS ZenBook UX325EA_UX325EA                          | 2         | 0.69%   |
| Apple MacBookPro9,2                                   | 2         | 0.69%   |
| Alienware 17                                          | 2         | 0.69%   |
| TUXEDO Polaris AMD Gen5                               | 1         | 0.34%   |
| TUXEDO Book BA1510                                    | 1         | 0.34%   |
| Toshiba Satellite L870-120                            | 1         | 0.34%   |
| Toshiba Satellite L855                                | 1         | 0.34%   |
| Timi RedmiBook 16                                     | 1         | 0.34%   |
| Timi RedmiBook 14 II                                  | 1         | 0.34%   |
| Samsung R410                                          | 1         | 0.34%   |
| Samsung 905S3G/906S3G/915S3G                          | 1         | 0.34%   |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.34%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.34%   |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.34%   |
| Samsung 535U3C                                        | 1         | 0.34%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.34%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.34%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.34%   |
| Packard Bell EasyNote TK87                            | 1         | 0.34%   |
| Notebook W35xSS_370SS                                 | 1         | 0.34%   |
| Notebook PE60RNE_RND_RNC                              | 1         | 0.34%   |
| Notebook N9x0TD_TF                                    | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 71        | 24.48%  |
| HP EliteBook       | 20        | 6.9%    |
| Dell Latitude      | 17        | 5.86%   |
| Dell Inspiron      | 10        | 3.45%   |
| Lenovo IdeaPad     | 8         | 2.76%   |
| HP Pavilion        | 8         | 2.76%   |
| Dell XPS           | 7         | 2.41%   |
| Acer Aspire        | 7         | 2.41%   |
| Dell Precision     | 6         | 2.07%   |
| HP ProBook         | 5         | 1.72%   |
| Valve Jupiter      | 4         | 1.38%   |
| Lenovo Legion      | 4         | 1.38%   |
| ASUS Zenbook       | 4         | 1.38%   |
| ASUS VivoBook      | 4         | 1.38%   |
| ASUS ASUS          | 4         | 1.38%   |
| HP Laptop          | 3         | 1.03%   |
| HP Compaq          | 3         | 1.03%   |
| Fujitsu LIFEBOOK   | 3         | 1.03%   |
| Apple MacBookPro5  | 3         | 1.03%   |
| Toshiba Satellite  | 2         | 0.69%   |
| Timi RedmiBook     | 2         | 0.69%   |
| Samsung 900X3C     | 2         | 0.69%   |
| Quanta TWH         | 2         | 0.69%   |
| Lenovo Yoga        | 2         | 0.69%   |
| Lenovo Y50-70      | 2         | 0.69%   |
| Lenovo LOQ         | 2         | 0.69%   |
| HP ZBook           | 2         | 0.69%   |
| HP Presario        | 2         | 0.69%   |
| HP OMEN            | 2         | 0.69%   |
| HP ENVY            | 2         | 0.69%   |
| Framework Laptop   | 2         | 0.69%   |
| Dell Vostro        | 2         | 0.69%   |
| Dell System        | 2         | 0.69%   |
| Apple MacBookPro9  | 2         | 0.69%   |
| Apple MacBookPro11 | 2         | 0.69%   |
| Alienware 17       | 2         | 0.69%   |
| TUXEDO Polaris     | 1         | 0.34%   |
| TUXEDO Book        | 1         | 0.34%   |
| Samsung R410       | 1         | 0.34%   |
| Samsung 905S3G     | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 30        | 10.34%  |
| 2020 | 28        | 9.66%   |
| 2018 | 28        | 9.66%   |
| 2011 | 25        | 8.62%   |
| 2019 | 22        | 7.59%   |
| 2021 | 17        | 5.86%   |
| 2012 | 17        | 5.86%   |
| 2014 | 16        | 5.52%   |
| 2015 | 15        | 5.17%   |
| 2022 | 13        | 4.48%   |
| 2017 | 13        | 4.48%   |
| 2016 | 12        | 4.14%   |
| 2023 | 10        | 3.45%   |
| 2010 | 10        | 3.45%   |
| 2024 | 9         | 3.1%    |
| 2008 | 9         | 3.1%    |
| 2007 | 8         | 2.76%   |
| 2009 | 4         | 1.38%   |
| 2006 | 3         | 1.03%   |
| 2025 | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 290       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 269       | 91.81%  |
| Enabled  | 24        | 8.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 290       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 64        | 21.77%  |
| 8.01-16.0   | 63        | 21.43%  |
| 16.01-24.0  | 62        | 21.09%  |
| 3.01-4.0    | 42        | 14.29%  |
| 32.01-64.0  | 26        | 8.84%   |
| 24.01-32.0  | 16        | 5.44%   |
| 2.01-3.0    | 10        | 3.4%    |
| 1.01-2.0    | 6         | 2.04%   |
| 64.01-256.0 | 5         | 1.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 83        | 26.6%   |
| 2.01-3.0   | 75        | 24.04%  |
| 4.01-8.0   | 69        | 22.12%  |
| 3.01-4.0   | 48        | 15.38%  |
| 8.01-16.0  | 19        | 6.09%   |
| 0.51-1.0   | 12        | 3.85%   |
| 16.01-24.0 | 4         | 1.28%   |
| 32.01-64.0 | 1         | 0.32%   |
| 24.01-32.0 | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 225       | 76.01%  |
| 2      | 56        | 18.92%  |
| 3      | 11        | 3.72%   |
| 4      | 2         | 0.68%   |
| 5      | 1         | 0.34%   |
| 0      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 205       | 69.97%  |
| Yes       | 88        | 30.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 244       | 83.28%  |
| No        | 49        | 16.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 285       | 98.28%  |
| No        | 5         | 1.72%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 239       | 81.57%  |
| No        | 54        | 18.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Estonia | 290       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Tallinn           | 182       | 60.87%  |
| Tartu             | 36        | 12.04%  |
| Pärnu            | 12        | 4.01%   |
| Rapla             | 6         | 2.01%   |
| Narva             | 6         | 2.01%   |
| Rakvere           | 5         | 1.67%   |
| Tabasalu          | 4         | 1.34%   |
| Maardu            | 4         | 1.34%   |
| Saku              | 3         | 1%      |
| Keila             | 3         | 1%      |
| Vinni             | 2         | 0.67%   |
| Viljandi          | 2         | 0.67%   |
| Viimsi            | 2         | 0.67%   |
| Valga             | 2         | 0.67%   |
| Otepaeae          | 2         | 0.67%   |
| Laagri            | 2         | 0.67%   |
| Kupu              | 2         | 0.67%   |
| Võru             | 1         | 0.33%   |
| Vatla             | 1         | 0.33%   |
| Torvandi          | 1         | 0.33%   |
| Tila              | 1         | 0.33%   |
| Tapa              | 1         | 0.33%   |
| Sindi             | 1         | 0.33%   |
| Sillamäe         | 1         | 0.33%   |
| Sauga             | 1         | 0.33%   |
| Reiu              | 1         | 0.33%   |
| Rae Parish        | 1         | 0.33%   |
| Põlva            | 1         | 0.33%   |
| Pohja-Sakala vald | 1         | 0.33%   |
| Palamuse          | 1         | 0.33%   |
| Muraste           | 1         | 0.33%   |
| Lääne-Virumaa   | 1         | 0.33%   |
| Kuressaare        | 1         | 0.33%   |
| Kose              | 1         | 0.33%   |
| Kärdla           | 1         | 0.33%   |
| Kaeina            | 1         | 0.33%   |
| Jüri             | 1         | 0.33%   |
| Jõhvi            | 1         | 0.33%   |
| Jõgeva           | 1         | 0.33%   |
| Jaerveotsa        | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 80        | 98     | 22.16%  |
| Seagate                     | 37        | 40     | 10.25%  |
| Sandisk                     | 24        | 28     | 6.65%   |
| Kingston                    | 24        | 29     | 6.65%   |
| Toshiba                     | 23        | 23     | 6.37%   |
| SK hynix                    | 22        | 27     | 6.09%   |
| WDC                         | 19        | 23     | 5.26%   |
| Unknown                     | 13        | 14     | 3.6%    |
| Intel                       | 13        | 14     | 3.6%    |
| Micron Technology           | 12        | 12     | 3.32%   |
| KIOXIA                      | 8         | 11     | 2.22%   |
| Patriot                     | 7         | 8      | 1.94%   |
| HGST                        | 7         | 8      | 1.94%   |
| A-DATA Technology           | 6         | 6      | 1.66%   |
| Kingston Technology Company | 5         | 8      | 1.39%   |
| Hitachi                     | 5         | 5      | 1.39%   |
| Crucial                     | 5         | 5      | 1.39%   |
| Apple                       | 5         | 5      | 1.39%   |
| China                       | 4         | 4      | 1.11%   |
| Unknown                     | 4         | 4      | 1.11%   |
| Phison Electronics          | 3         | 4      | 0.83%   |
| Lenovo                      | 3         | 3      | 0.83%   |
| Apacer                      | 3         | 3      | 0.83%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.55%   |
| Transcend                   | 2         | 5      | 0.55%   |
| SPCC                        | 2         | 4      | 0.55%   |
| LITEONIT                    | 2         | 2      | 0.55%   |
| KingSpec                    | 2         | 3      | 0.55%   |
| Gigabyte Technology         | 2         | 3      | 0.55%   |
| Fujitsu                     | 2         | 2      | 0.55%   |
| ADATA Technology            | 2         | 2      | 0.55%   |
| XPG                         | 1         | 1      | 0.28%   |
| UMIS                        | 1         | 1      | 0.28%   |
| Team                        | 1         | 1      | 0.28%   |
| PNY                         | 1         | 1      | 0.28%   |
| Phison                      | 1         | 1      | 0.28%   |
| Netac                       | 1         | 1      | 0.28%   |
| Micron/Crucial Technology   | 1         | 5      | 0.28%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.28%   |
| Lexar                       | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 8         | 2.15%   |
| Samsung SSD 850 EVO 500GB                          | 4         | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 4         | 1.08%   |
| Unknown                                            | 4         | 1.08%   |
| Seagate ST500LM021-1KJ152 500GB                    | 3         | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 3         | 0.81%   |
| Samsung SSD 860 EVO 250GB                          | 3         | 0.81%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB            | 3         | 0.81%   |
| Kingston SA400S37960G 960GB SSD                    | 3         | 0.81%   |
| Kingston SA400S37240G 240GB SSD                    | 3         | 0.81%   |
| Kingston SA400S37120G 120GB SSD                    | 3         | 0.81%   |
| HGST HTS721010A9E630 1TB                           | 3         | 0.81%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 2         | 0.54%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB               | 2         | 0.54%   |
| Unknown MMC Card  512GB                            | 2         | 0.54%   |
| Unknown MMC Card  16GB                             | 2         | 0.54%   |
| Unknown MMC Card  128GB                            | 2         | 0.54%   |
| Toshiba XG6 NVMe SSD Controller 1024GB             | 2         | 0.54%   |
| Toshiba NVMe SSD Drive 512GB                       | 2         | 0.54%   |
| Toshiba MQ01ABD100 1TB                             | 2         | 0.54%   |
| SK hynix SKHynix_HFS256GD9TNI-L2B0B 256GB          | 2         | 0.54%   |
| SK hynix PC601 NVMe 512GB                          | 2         | 0.54%   |
| SK hynix NVMe SSD Drive 512GB                      | 2         | 0.54%   |
| SK hynix NVMe SSD Drive 256GB                      | 2         | 0.54%   |
| Seagate ST9750420AS 752GB                          | 2         | 0.54%   |
| Seagate ST500LT012-1DG142 500GB                    | 2         | 0.54%   |
| Seagate ST1000LM049-2GH172 1TB                     | 2         | 0.54%   |
| Seagate ST1000LM048-2E7172 1TB                     | 2         | 0.54%   |
| Seagate BUP Portable 5TB                           | 2         | 0.54%   |
| Sandisk WD PC SN740 SDDQNQD-1T00-1201 1TB          | 2         | 0.54%   |
| SanDisk SD8SBAT256G1122 256GB SSD                  | 2         | 0.54%   |
| SanDisk NVMe SSD Drive 512GB                       | 2         | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB                     | 2         | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB                       | 2         | 0.54%   |
| Samsung SSD 870 QVO 1TB                            | 2         | 0.54%   |
| Samsung SSD 850 EVO mSATA 1TB                      | 2         | 0.54%   |
| Samsung SSD 850 EVO M.2 500GB                      | 2         | 0.54%   |
| Samsung NVMe SSD Drive 512GB                       | 2         | 0.54%   |
| Samsung NVMe SSD Drive 1TB                         | 2         | 0.54%   |
| Samsung NVMe SSD Drive 1024GB                      | 2         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 34        | 37     | 52.31%  |
| Toshiba  | 9         | 9      | 13.85%  |
| WDC      | 7         | 9      | 10.77%  |
| HGST     | 7         | 8      | 10.77%  |
| Hitachi  | 5         | 5      | 7.69%   |
| Fujitsu  | 2         | 2      | 3.08%   |
| External | 1         | 1      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 53     | 33.09%  |
| Kingston            | 20        | 25     | 14.71%  |
| SanDisk             | 9         | 11     | 6.62%   |
| Patriot             | 6         | 7      | 4.41%   |
| SK hynix            | 5         | 5      | 3.68%   |
| Micron Technology   | 5         | 5      | 3.68%   |
| Intel               | 5         | 6      | 3.68%   |
| A-DATA Technology   | 5         | 5      | 3.68%   |
| WDC                 | 4         | 6      | 2.94%   |
| Crucial             | 4         | 4      | 2.94%   |
| China               | 4         | 4      | 2.94%   |
| Apple               | 4         | 4      | 2.94%   |
| Toshiba             | 3         | 3      | 2.21%   |
| Apacer              | 3         | 3      | 2.21%   |
| Transcend           | 2         | 5      | 1.47%   |
| LITEONIT            | 2         | 2      | 1.47%   |
| KingSpec            | 2         | 3      | 1.47%   |
| XPG                 | 1         | 1      | 0.74%   |
| Team                | 1         | 1      | 0.74%   |
| SPCC                | 1         | 3      | 0.74%   |
| Netac               | 1         | 1      | 0.74%   |
| Lexar               | 1         | 1      | 0.74%   |
| Intenso             | 1         | 1      | 0.74%   |
| Gigabyte Technology | 1         | 2      | 0.74%   |
| Unknown             | 1         | 1      | 0.74%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 124       | 169    | 37.8%   |
| SSD     | 122       | 162    | 37.2%   |
| HDD     | 63        | 71     | 19.21%  |
| MMC     | 14        | 15     | 4.27%   |
| Unknown | 5         | 6      | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 171       | 228    | 53.11%  |
| NVMe | 124       | 167    | 38.51%  |
| MMC  | 14        | 15     | 4.35%   |
| SAS  | 13        | 13     | 4.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 137       | 171    | 71.35%  |
| 0.51-1.0   | 47        | 54     | 24.48%  |
| 1.01-2.0   | 5         | 5      | 2.6%    |
| 4.01-10.0  | 2         | 2      | 1.04%   |
| 3.01-4.0   | 1         | 1      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 100       | 33.44%  |
| 251-500        | 62        | 20.74%  |
| 501-1000       | 42        | 14.05%  |
| 1-20           | 29        | 9.7%    |
| 1001-2000      | 17        | 5.69%   |
| 51-100         | 17        | 5.69%   |
| Unknown        | 14        | 4.68%   |
| More than 3000 | 10        | 3.34%   |
| 21-50          | 5         | 1.67%   |
| 2001-3000      | 3         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 112       | 36.48%  |
| 21-50          | 56        | 18.24%  |
| 101-250        | 45        | 14.66%  |
| 51-100         | 37        | 12.05%  |
| 251-500        | 23        | 7.49%   |
| 501-1000       | 14        | 4.56%   |
| Unknown        | 14        | 4.56%   |
| More than 3000 | 4         | 1.3%    |
| 2001-3000      | 1         | 0.33%   |
| 1001-2000      | 1         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB                         | 1         | 1      | 4.55%   |
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 4.55%   |
| Toshiba KSG60ZMV512G M.2 2280 512GB SSD             | 1         | 1      | 4.55%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 4.55%   |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 4.55%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 4.55%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 4.55%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 4.55%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 4.55%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 4.55%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 4.55%   |
| SanDisk SDSSDX480GG25 480GB                         | 1         | 1      | 4.55%   |
| Samsung Electronics SSD 850 EVO mSATA 1TB           | 1         | 1      | 4.55%   |
| Netac SSD 720GB                                     | 1         | 1      | 4.55%   |
| Micron Technology MTFDDAK256TDL-1AW15ABHA 256GB SSD | 1         | 1      | 4.55%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 4.55%   |
| Kingston SA400S37960G 960GB SSD                     | 1         | 1      | 4.55%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 4.55%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 4.55%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 4.55%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 4.55%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 36.36%  |
| WDC                 | 2         | 2      | 9.09%   |
| Micron Technology   | 2         | 2      | 9.09%   |
| Kingston            | 2         | 2      | 9.09%   |
| Toshiba             | 1         | 1      | 4.55%   |
| SanDisk             | 1         | 1      | 4.55%   |
| Samsung Electronics | 1         | 1      | 4.55%   |
| Netac               | 1         | 1      | 4.55%   |
| Hitachi             | 1         | 1      | 4.55%   |
| HGST                | 1         | 1      | 4.55%   |
| Fujitsu             | 1         | 1      | 4.55%   |
| Crucial             | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 61.54%  |
| WDC     | 2         | 2      | 15.38%  |
| Hitachi | 1         | 1      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |
| Fujitsu | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 61.9%   |
| SSD  | 8         | 9      | 38.1%   |

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
| Detected | 160       | 246    | 52.63%  |
| Works    | 124       | 155    | 40.79%  |
| Malfunc  | 20        | 22     | 6.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 179       | 52.03%  |
| Samsung Electronics                     | 39        | 11.34%  |
| AMD                                     | 29        | 8.43%   |
| Sandisk                                 | 22        | 6.4%    |
| SK hynix                                | 17        | 4.94%   |
| Toshiba America Info Systems            | 10        | 2.91%   |
| KIOXIA                                  | 8         | 2.33%   |
| Kingston Technology Company             | 8         | 2.33%   |
| Micron Technology                       | 7         | 2.03%   |
| Phison Electronics                      | 5         | 1.45%   |
| Nvidia                                  | 3         | 0.87%   |
| Lenovo                                  | 3         | 0.87%   |
| ADATA Technology                        | 3         | 0.87%   |
| Micron/Crucial Technology               | 2         | 0.58%   |
| Marvell Technology Group                | 2         | 0.58%   |
| VIA Technologies                        | 1         | 0.29%   |
| Union Memory (Shenzhen)                 | 1         | 0.29%   |
| Shenzhen Unionmemory Information System | 1         | 0.29%   |
| Realtek Semiconductor                   | 1         | 0.29%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.29%   |
| Hosin Global Electronics                | 1         | 0.29%   |
| Apple                                   | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 24        | 6.54%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 24        | 6.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 21        | 5.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 19        | 5.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 4.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 17        | 4.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 12        | 3.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 2.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 2.18%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 1.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 1.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 1.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 1.63%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.36%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 1.36%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 1.36%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 1.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.36%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.36%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 1.09%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 4         | 1.09%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 4         | 1.09%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 4         | 1.09%   |
| Intel SSD 660P Series                                                          | 4         | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.09%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 3         | 0.82%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 3         | 0.82%   |
| Sandisk WD Blue SN580 NVMe SSD (DRAM-less)                                     | 3         | 0.82%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.82%   |
| Nvidia MCP79 AHCI Controller                                                   | 3         | 0.82%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 3         | 0.82%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 3         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 0.82%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 2         | 0.54%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.54%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 191       | 54.57%  |
| NVMe | 125       | 35.71%  |
| IDE  | 18        | 5.14%   |
| RAID | 16        | 4.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 226       | 77.93%  |
| AMD    | 64        | 22.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz          | 10        | 3.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 5         | 1.72%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 5         | 1.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 5         | 1.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 5         | 1.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 5         | 1.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 4         | 1.38%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 4         | 1.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 4         | 1.38%   |
| AMD Custom APU 0405                        | 4         | 1.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 3         | 1.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 3         | 1.03%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 3         | 1.03%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 3         | 1.03%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz         | 3         | 1.03%   |
| Intel Core i7-10750H CPU @ 2.60GHz         | 3         | 1.03%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 3         | 1.03%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 3         | 1.03%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 3         | 1.03%   |
| Intel Core i5-2450M CPU @ 2.50GHz          | 3         | 1.03%   |
| Intel Core i5 CPU M 460 @ 2.53GHz          | 3         | 1.03%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics | 3         | 1.03%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 3         | 1.03%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics | 3         | 1.03%   |
| AMD Ryzen 5 4600H with Radeon Graphics     | 3         | 1.03%   |
| Intel Pentium Silver N6000 @ 1.10GHz       | 2         | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 2         | 0.69%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 2         | 0.69%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz         | 2         | 0.69%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz         | 2         | 0.69%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 2         | 0.69%   |
| Intel Core i7-4510U CPU @ 2.00GHz          | 2         | 0.69%   |
| Intel Core i7-4500U CPU @ 1.80GHz          | 2         | 0.69%   |
| Intel Core i7-3610QM CPU @ 2.30GHz         | 2         | 0.69%   |
| Intel Core i7-2620M CPU @ 2.70GHz          | 2         | 0.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 0.69%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz         | 2         | 0.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 2         | 0.69%   |
| Intel Core i5-5250U CPU @ 1.60GHz          | 2         | 0.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 2         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 75        | 25.86%  |
| Intel Core i7                  | 74        | 25.52%  |
| Other                          | 31        | 10.69%  |
| AMD Ryzen 7                    | 17        | 5.86%   |
| AMD Ryzen 5                    | 13        | 4.48%   |
| Intel Core i3                  | 12        | 4.14%   |
| Intel Core 2 Duo               | 12        | 4.14%   |
| Intel Celeron                  | 10        | 3.45%   |
| AMD Ryzen 7 PRO                | 7         | 2.41%   |
| Intel Pentium                  | 3         | 1.03%   |
| AMD Ryzen 5 PRO                | 3         | 1.03%   |
| Intel Pentium Silver           | 2         | 0.69%   |
| Intel Pentium M                | 2         | 0.69%   |
| Intel Core 2                   | 2         | 0.69%   |
| Intel Celeron Dual-Core        | 2         | 0.69%   |
| Intel Atom                     | 2         | 0.69%   |
| AMD Ryzen 3 PRO                | 2         | 0.69%   |
| AMD Ryzen 3                    | 2         | 0.69%   |
| AMD A4                         | 2         | 0.69%   |
| Intel Xeon                     | 1         | 0.34%   |
| Intel Pentium Dual             | 1         | 0.34%   |
| Intel Core M                   | 1         | 0.34%   |
| Intel Core i9                  | 1         | 0.34%   |
| Intel Core                     | 1         | 0.34%   |
| Intel Celeron M                | 1         | 0.34%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.34%   |
| AMD Turion II Neo              | 1         | 0.34%   |
| AMD Quad-Core                  | 1         | 0.34%   |
| AMD E2                         | 1         | 0.34%   |
| AMD E                          | 1         | 0.34%   |
| AMD C-60                       | 1         | 0.34%   |
| AMD Athlon II Dual-Core        | 1         | 0.34%   |
| AMD Athlon 64 X2               | 1         | 0.34%   |
| AMD A8                         | 1         | 0.34%   |
| AMD A6                         | 1         | 0.34%   |
| AMD A10                        | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 125       | 43.1%   |
| 4       | 92        | 31.72%  |
| 6       | 27        | 9.31%   |
| 8       | 24        | 8.28%   |
| 1       | 7         | 2.41%   |
| 10      | 5         | 1.72%   |
| 12      | 4         | 1.38%   |
| 14      | 3         | 1.03%   |
| Unknown | 2         | 0.69%   |
| 16      | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 290       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 230       | 79.04%  |
| 1       | 59        | 20.27%  |
| Unknown | 2         | 0.69%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 287       | 98.97%  |
| 32-bit         | 2         | 0.69%   |
| Unknown        | 1         | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 140       | 47.3%   |
| 0x206a7    | 14        | 4.73%   |
| 0x306a9    | 13        | 4.39%   |
| 0x306c3    | 12        | 4.05%   |
| 0x806ea    | 9         | 3.04%   |
| 0x40651    | 8         | 2.7%    |
| 0x08600106 | 7         | 2.36%   |
| 0x306d4    | 6         | 2.03%   |
| 0x906e9    | 5         | 1.69%   |
| 0x806ec    | 5         | 1.69%   |
| 0x806c1    | 5         | 1.69%   |
| 0x20655    | 5         | 1.69%   |
| 0x1067a    | 5         | 1.69%   |
| 0xa0652    | 4         | 1.35%   |
| 0x6fb      | 4         | 1.35%   |
| 0x506e3    | 4         | 1.35%   |
| 0x906ea    | 3         | 1.01%   |
| 0x806e9    | 3         | 1.01%   |
| 0x6fd      | 3         | 1.01%   |
| 0x406e3    | 3         | 1.01%   |
| 0x08108102 | 3         | 1.01%   |
| 0x05000119 | 3         | 1.01%   |
| 0x706a1    | 2         | 0.68%   |
| 0x6d8      | 2         | 0.68%   |
| 0x30678    | 2         | 0.68%   |
| 0x0a50000d | 2         | 0.68%   |
| 0x0a50000c | 2         | 0.68%   |
| 0x08600104 | 2         | 0.68%   |
| 0x906ed    | 1         | 0.34%   |
| 0x806eb    | 1         | 0.34%   |
| 0x806d1    | 1         | 0.34%   |
| 0x706a8    | 1         | 0.34%   |
| 0x6fa      | 1         | 0.34%   |
| 0x6f6      | 1         | 0.34%   |
| 0x30661    | 1         | 0.34%   |
| 0x106ca    | 1         | 0.34%   |
| 0x10676    | 1         | 0.34%   |
| 0x0b204019 | 1         | 0.34%   |
| 0x0a704103 | 1         | 0.34%   |
| 0x0a50000f | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 54        | 18.62%  |
| Haswell          | 30        | 10.34%  |
| Unknown          | 29        | 10%     |
| IvyBridge        | 24        | 8.28%   |
| SandyBridge      | 23        | 7.93%   |
| Zen 2            | 15        | 5.17%   |
| Broadwell        | 14        | 4.83%   |
| Skylake          | 13        | 4.48%   |
| TigerLake        | 12        | 4.14%   |
| Core             | 10        | 3.45%   |
| Zen 3            | 8         | 2.76%   |
| Westmere         | 8         | 2.76%   |
| Penryn           | 8         | 2.76%   |
| Zen+             | 5         | 1.72%   |
| Alderlake Hybrid | 5         | 1.72%   |
| Goldmont plus    | 4         | 1.38%   |
| CometLake        | 4         | 1.38%   |
| Bobcat           | 3         | 1.03%   |
| Zen              | 2         | 0.69%   |
| Silvermont       | 2         | 0.69%   |
| Piledriver       | 2         | 0.69%   |
| P6               | 2         | 0.69%   |
| K10              | 2         | 0.69%   |
| Excavator        | 2         | 0.69%   |
| Bonnell          | 2         | 0.69%   |
| Tremont          | 1         | 0.34%   |
| Steamroller      | 1         | 0.34%   |
| K8 Hammer        | 1         | 0.34%   |
| K8 & K10 hybrid  | 1         | 0.34%   |
| Jaguar           | 1         | 0.34%   |
| Icelake          | 1         | 0.34%   |
| Goldmont         | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 212       | 55.5%   |
| Nvidia           | 98        | 25.65%  |
| AMD              | 71        | 18.59%  |
| VIA Technologies | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 22        | 5.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 21        | 5.32%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                      | 20        | 5.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 15        | 3.8%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 14        | 3.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 12        | 3.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 11        | 2.78%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                      | 10        | 2.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 9         | 2.28%   |
| Intel Core Processor Integrated Graphics Controller                           | 8         | 2.03%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 7         | 1.77%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                         | 7         | 1.77%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                       | 7         | 1.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 6         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 6         | 1.52%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 5         | 1.27%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 1.27%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 1.27%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 5         | 1.27%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                       | 5         | 1.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 1.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 5         | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 4         | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 4         | 1.01%   |
| Nvidia GM107GLM [Quadro M2000M]                                               | 4         | 1.01%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                         | 4         | 1.01%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 4         | 1.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 1.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 1.01%   |
| AMD VanGogh [AMD Custom GPU 0405]                                             | 4         | 1.01%   |
| AMD Phoenix1                                                                  | 4         | 1.01%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 3         | 0.76%   |
| Nvidia GK208M [GeForce GT 730M]                                               | 3         | 0.76%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 3         | 0.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 3         | 0.76%   |
| Nvidia C79 [GeForce 9400M]                                                    | 3         | 0.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 0.76%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 0.76%   |
| AMD Strix [Radeon 880M / 890M]                                                | 3         | 0.76%   |
| AMD Rembrandt [Radeon 680M]                                                   | 3         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 128       | 44.14%  |
| Intel + Nvidia | 75        | 25.86%  |
| 1 x AMD        | 51        | 17.59%  |
| 1 x Nvidia     | 11        | 3.79%   |
| AMD + Nvidia   | 10        | 3.45%   |
| Intel + AMD    | 7         | 2.41%   |
| 2 x AMD        | 3         | 1.03%   |
| 2 x Nvidia     | 2         | 0.69%   |
| 2 x Intel      | 2         | 0.69%   |
| 1 x VIA        | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 234       | 79.59%  |
| Proprietary | 46        | 15.65%  |
| Unknown     | 14        | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 184       | 62.8%   |
| 1.01-2.0   | 38        | 12.97%  |
| 0.01-0.5   | 31        | 10.58%  |
| 0.51-1.0   | 18        | 6.14%   |
| 3.01-4.0   | 15        | 5.12%   |
| 5.01-6.0   | 4         | 1.37%   |
| 7.01-8.0   | 1         | 0.34%   |
| 2.01-3.0   | 1         | 0.34%   |
| 8.01-16.0  | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 64        | 18.5%   |
| Chimei Innolux          | 47        | 13.58%  |
| LG Display              | 38        | 10.98%  |
| BOE                     | 38        | 10.98%  |
| Dell                    | 29        | 8.38%   |
| Samsung Electronics     | 27        | 7.8%    |
| Sharp                   | 12        | 3.47%   |
| Lenovo                  | 12        | 3.47%   |
| Chi Mei Optoelectronics | 12        | 3.47%   |
| Apple                   | 10        | 2.89%   |
| Hewlett-Packard         | 7         | 2.02%   |
| Goldstar                | 7         | 2.02%   |
| PANDA                   | 5         | 1.45%   |
| LG Philips              | 4         | 1.16%   |
| Sony                    | 3         | 0.87%   |
| CSO                     | 3         | 0.87%   |
| Valve                   | 2         | 0.58%   |
| Panasonic               | 2         | 0.58%   |
| InfoVision              | 2         | 0.58%   |
| CSOT                    | 2         | 0.58%   |
| CPT                     | 2         | 0.58%   |
| AOC                     | 2         | 0.58%   |
| ViewSonic               | 1         | 0.29%   |
| Vestel Elektronik       | 1         | 0.29%   |
| Toshiba                 | 1         | 0.29%   |
| Sun                     | 1         | 0.29%   |
| Seiko/Epson             | 1         | 0.29%   |
| Philips                 | 1         | 0.29%   |
| Mi                      | 1         | 0.29%   |
| Lenovo Group Limited    | 1         | 0.29%   |
| KDB                     | 1         | 0.29%   |
| JDI                     | 1         | 0.29%   |
| Iiyama                  | 1         | 0.29%   |
| IBM                     | 1         | 0.29%   |
| CTO                     | 1         | 0.29%   |
| ASUSTek Computer        | 1         | 0.29%   |
| Analogix                | 1         | 0.29%   |
| Acer                    | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 5         | 1.41%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 4         | 1.13%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 4         | 1.13%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 4         | 1.13%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 3         | 0.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 3         | 0.85%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 3         | 0.85%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 0.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 3         | 0.85%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 3         | 0.85%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 2         | 0.56%   |
| Sony TV SNYDB01 1920x1080                                                 | 2         | 0.56%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.56%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 2         | 0.56%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                   | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 0.56%   |
| Panasonic VVX11F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch              | 2         | 0.56%   |
| LG Philips LCD Monitor LPL0133 1280x800 304x190mm 14.1-inch               | 2         | 0.56%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 0.56%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch               | 2         | 0.56%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch              | 2         | 0.56%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 2         | 0.56%   |
| Lenovo B140UAN02.7 LEN403A 1920x1200 302x188mm 14.0-inch                  | 2         | 0.56%   |
| Hewlett-Packard LE2202x HWP2967 1920x1080 480x270mm 21.7-inch             | 2         | 0.56%   |
| Goldstar 27GL850 GSM5B80 2560x1440 697x392mm 31.5-inch                    | 2         | 0.56%   |
| Dell P3421W DELA1A8 3440x1440 800x330mm 34.1-inch                         | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 2         | 0.56%   |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO7AA7 2560x1600 312x195mm 14.5-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 143       | 43.33%  |
| 1366x768 (WXGA)    | 58        | 17.58%  |
| 3840x2160 (4K)     | 21        | 6.36%   |
| 1920x1200 (WUXGA)  | 20        | 6.06%   |
| 1600x900 (HD+)     | 20        | 6.06%   |
| 1280x800 (WXGA)    | 13        | 3.94%   |
| 2560x1600          | 10        | 3.03%   |
| 2560x1440 (QHD)    | 9         | 2.73%   |
| 1680x1050 (WSXGA+) | 6         | 1.82%   |
| 3440x1440          | 5         | 1.52%   |
| 1440x900 (WXGA+)   | 5         | 1.52%   |
| 2880x1800          | 4         | 1.21%   |
| 800x1280           | 3         | 0.91%   |
| 1600x1200          | 2         | 0.61%   |
| 1280x1024 (SXGA)   | 2         | 0.61%   |
| 3840x2400          | 1         | 0.3%    |
| 3200x1800 (QHD+)   | 1         | 0.3%    |
| 3000x2000          | 1         | 0.3%    |
| 2560x1080          | 1         | 0.3%    |
| 2304x1440          | 1         | 0.3%    |
| 2256x1504          | 1         | 0.3%    |
| 2160x1440          | 1         | 0.3%    |
| 1920x1280          | 1         | 0.3%    |
| 1024x768 (XGA)     | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 112       | 32%     |
| 14      | 61        | 17.43%  |
| 13      | 51        | 14.57%  |
| 17      | 22        | 6.29%   |
| 24      | 19        | 5.43%   |
| 27      | 14        | 4%      |
| 12      | 12        | 3.43%   |
| 16      | 8         | 2.29%   |
| 34      | 6         | 1.71%   |
| 21      | 6         | 1.71%   |
| 31      | 5         | 1.43%   |
| Unknown | 4         | 1.14%   |
| 72      | 3         | 0.86%   |
| 23      | 3         | 0.86%   |
| 22      | 3         | 0.86%   |
| 84      | 2         | 0.57%   |
| 40      | 2         | 0.57%   |
| 29      | 2         | 0.57%   |
| 20      | 2         | 0.57%   |
| 7       | 2         | 0.57%   |
| 86      | 1         | 0.29%   |
| 65      | 1         | 0.29%   |
| 54      | 1         | 0.29%   |
| 43      | 1         | 0.29%   |
| 38      | 1         | 0.29%   |
| 19      | 1         | 0.29%   |
| 18      | 1         | 0.29%   |
| 11      | 1         | 0.29%   |
| 10      | 1         | 0.29%   |
| 9       | 1         | 0.29%   |
| 3       | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 198       | 57.23%  |
| 201-300     | 45        | 13.01%  |
| 501-600     | 34        | 9.83%   |
| 351-400     | 24        | 6.94%   |
| 401-500     | 12        | 3.47%   |
| 601-700     | 8         | 2.31%   |
| 701-800     | 6         | 1.73%   |
| 1501-2000   | 5         | 1.45%   |
| Unknown     | 4         | 1.16%   |
| 801-900     | 3         | 0.87%   |
| 1001-1500   | 3         | 0.87%   |
| 1-100       | 3         | 0.87%   |
| 901-1000    | 1         | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 231       | 74.04%  |
| 16/10   | 57        | 18.27%  |
| 3/2     | 6         | 1.92%   |
| 21/9    | 6         | 1.92%   |
| 4/3     | 3         | 0.96%   |
| Unknown | 3         | 0.96%   |
| 5/4     | 2         | 0.64%   |
| 0.67    | 2         | 0.64%   |
| 6/5     | 1         | 0.32%   |
| 0.56    | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 109       | 31.32%  |
| 81-90          | 86        | 24.71%  |
| 71-80          | 23        | 6.61%   |
| 201-250        | 20        | 5.75%   |
| 121-130        | 20        | 5.75%   |
| 301-350        | 14        | 4.02%   |
| 351-500        | 13        | 3.74%   |
| 61-70          | 11        | 3.16%   |
| 111-120        | 11        | 3.16%   |
| 251-300        | 10        | 2.87%   |
| More than 1000 | 8         | 2.3%    |
| 501-1000       | 4         | 1.15%   |
| Unknown        | 4         | 1.15%   |
| 1-40           | 3         | 0.86%   |
| 151-200        | 3         | 0.86%   |
| 91-100         | 3         | 0.86%   |
| 41-50          | 2         | 0.57%   |
| 141-150        | 2         | 0.57%   |
| 51-60          | 1         | 0.29%   |
| 131-140        | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 143       | 41.57%  |
| 101-120       | 80        | 23.26%  |
| 51-100        | 54        | 15.7%   |
| 161-240       | 43        | 12.5%   |
| More than 240 | 14        | 4.07%   |
| 1-50          | 6         | 1.74%   |
| Unknown       | 4         | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 223       | 75.59%  |
| 2     | 57        | 19.32%  |
| 3     | 10        | 3.39%   |
| 0     | 5         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 167       | 35.99%  |
| Realtek Semiconductor             | 127       | 27.37%  |
| Qualcomm Atheros                  | 54        | 11.64%  |
| Broadcom                          | 29        | 6.25%   |
| MediaTek                          | 16        | 3.45%   |
| ASIX Electronics                  | 9         | 1.94%   |
| Sierra Wireless                   | 5         | 1.08%   |
| Ralink                            | 5         | 1.08%   |
| Lenovo                            | 5         | 1.08%   |
| Fibocom                           | 5         | 1.08%   |
| Ericsson Business Mobile Networks | 5         | 1.08%   |
| Broadcom Limited                  | 5         | 1.08%   |
| Qualcomm Technologies             | 4         | 0.86%   |
| TP-Link                           | 3         | 0.65%   |
| Shenzhen Goodix Technology        | 3         | 0.65%   |
| Nvidia                            | 3         | 0.65%   |
| Hewlett-Packard                   | 3         | 0.65%   |
| Samsung Electronics               | 2         | 0.43%   |
| Qualcomm                          | 2         | 0.43%   |
| JMicron Technology                | 2         | 0.43%   |
| Huawei Technologies               | 2         | 0.43%   |
| VIA Technologies                  | 1         | 0.22%   |
| Van Ooijen Technische Informatica | 1         | 0.22%   |
| Quectel Wireless Solutions        | 1         | 0.22%   |
| QinHeng Electronics               | 1         | 0.22%   |
| OPPO Electronics                  | 1         | 0.22%   |
| Marvell Technology Group          | 1         | 0.22%   |
| DisplayLink                       | 1         | 0.22%   |
| ASUSTek Computer                  | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 72        | 12.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 3.63%   |
| Intel Wireless 8265 / 8275                                             | 20        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 15        | 2.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 14        | 2.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 2.25%   |
| Intel Wi-Fi 6 AX200                                                    | 13        | 2.25%   |
| Intel Wireless 7260                                                    | 12        | 2.07%   |
| Intel Wireless 7265                                                    | 11        | 1.9%    |
| Intel Wi-Fi 6 AX201                                                    | 10        | 1.73%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 9         | 1.55%   |
| Intel Ethernet Connection (4) I219-V                                   | 9         | 1.55%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 1.55%   |
| Intel Wireless 8260                                                    | 8         | 1.38%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 1.38%   |
| ASIX AX88179 Gigabit Ethernet                                          | 8         | 1.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 1.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 7         | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 7         | 1.21%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 6         | 1.04%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 6         | 1.04%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.86%   |
| Intel 82566MM Gigabit Network Connection                               | 5         | 0.86%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                      | 5         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 4         | 0.69%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]       | 4         | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.69%   |
| Intel Wireless 3160                                                    | 4         | 0.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 4         | 0.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 155       | 51.32%  |
| Qualcomm Atheros           | 42        | 13.91%  |
| Realtek Semiconductor      | 36        | 11.92%  |
| Broadcom                   | 25        | 8.28%   |
| MediaTek                   | 14        | 4.64%   |
| Sierra Wireless            | 5         | 1.66%   |
| Ralink                     | 5         | 1.66%   |
| Fibocom                    | 5         | 1.66%   |
| Qualcomm Technologies      | 4         | 1.32%   |
| Broadcom Limited           | 4         | 1.32%   |
| TP-Link                    | 2         | 0.66%   |
| Qualcomm                   | 2         | 0.66%   |
| Hewlett-Packard            | 2         | 0.66%   |
| Quectel Wireless Solutions | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 20        | 6.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 15        | 4.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 14        | 4.64%   |
| Intel Wi-Fi 6 AX200                                                  | 13        | 4.3%    |
| Intel Wireless 7260                                                  | 12        | 3.97%   |
| Intel Wireless 7265                                                  | 11        | 3.64%   |
| Intel Wi-Fi 6 AX201                                                  | 10        | 3.31%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 9         | 2.98%   |
| Intel Wireless 8260                                                  | 8         | 2.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 7         | 2.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 7         | 2.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 2.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 7         | 2.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 7         | 2.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 6         | 1.99%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 6         | 1.99%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                    | 5         | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 1.32%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]     | 4         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 1.32%   |
| Intel Wireless 3160                                                  | 4         | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 4         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 4         | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 4         | 1.32%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 3         | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3         | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 3         | 0.99%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 3         | 0.99%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 3         | 0.99%   |
| Intel Wireless 3165                                                  | 3         | 0.99%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 3         | 0.99%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 3         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 3         | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3         | 0.99%   |
| Intel Centrino Advanced-N 6235                                       | 3         | 0.99%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 0.99%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 0.99%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 3         | 0.99%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 3         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 110       | 42.47%  |
| Intel                    | 91        | 35.14%  |
| Qualcomm Atheros         | 19        | 7.34%   |
| Broadcom                 | 10        | 3.86%   |
| ASIX Electronics         | 9         | 3.47%   |
| Lenovo                   | 4         | 1.54%   |
| Nvidia                   | 3         | 1.16%   |
| Samsung Electronics      | 2         | 0.77%   |
| MediaTek                 | 2         | 0.77%   |
| JMicron Technology       | 2         | 0.77%   |
| VIA Technologies         | 1         | 0.39%   |
| TP-Link                  | 1         | 0.39%   |
| OPPO Electronics         | 1         | 0.39%   |
| Marvell Technology Group | 1         | 0.39%   |
| DisplayLink              | 1         | 0.39%   |
| Broadcom Limited         | 1         | 0.39%   |
| ASUSTek Computer         | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 72        | 27.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 8.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 6.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 4.98%   |
| Intel Ethernet Connection (4) I219-V                                   | 9         | 3.45%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 3.45%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 3.07%   |
| ASIX AX88179 Gigabit Ethernet                                          | 8         | 3.07%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 2.3%    |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 1.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 1.92%   |
| Intel 82566MM Gigabit Network Connection                               | 5         | 1.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 1.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 1.15%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 1.15%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 1.15%   |
| Intel Ethernet Connection I217-V                                       | 3         | 1.15%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 1.15%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.77%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 0.77%   |
| Lenovo ThinkPad TBT3 LAN                                               | 2         | 0.77%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.77%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.38%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.38%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.38%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.38%   |
| OPPO Ace 3V                                                            | 1         | 0.38%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.38%   |
| MediaTek Infinix HOT 50i                                               | 1         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 285       | 52.39%  |
| Ethernet | 244       | 44.85%  |
| Modem    | 15        | 2.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 231       | 75%     |
| Ethernet | 77        | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 219       | 75.52%  |
| 1     | 66        | 22.76%  |
| 3     | 3         | 1.03%   |
| 0     | 2         | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 240       | 80.81%  |
| Yes  | 57        | 19.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 49.38%  |
| Qualcomm Atheros Communications | 21        | 8.71%   |
| Realtek Semiconductor           | 18        | 7.47%   |
| Broadcom                        | 16        | 6.64%   |
| IMC Networks                    | 15        | 6.22%   |
| Foxconn / Hon Hai               | 13        | 5.39%   |
| Apple                           | 10        | 4.15%   |
| Hewlett-Packard                 | 6         | 2.49%   |
| Cambridge Silicon Radio         | 6         | 2.49%   |
| Realtek                         | 4         | 1.66%   |
| Dell                            | 3         | 1.24%   |
| Toshiba                         | 2         | 0.83%   |
| Lite-On Technology              | 2         | 0.83%   |
| USI                             | 1         | 0.41%   |
| TP-Link                         | 1         | 0.41%   |
| Ralink                          | 1         | 0.41%   |
| Quectel Wireless Solutions      | 1         | 0.41%   |
| MediaTek                        | 1         | 0.41%   |
| Askey Computer                  | 1         | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 54        | 22.41%  |
| Intel AX201 Bluetooth                               | 21        | 8.71%   |
| Realtek Bluetooth Radio                             | 12        | 4.98%   |
| Intel AX200 Bluetooth                               | 11        | 4.56%   |
| Intel Bluetooth Device                              | 10        | 4.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 4.15%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 3.73%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 7         | 2.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 2.49%   |
| IMC Networks Bluetooth Radio                        | 6         | 2.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 2.49%   |
| IMC Networks Bluetooth Device                       | 5         | 2.07%   |
| Apple Bluetooth USB Host Controller                 | 5         | 2.07%   |
| Apple Bluetooth Host Controller                     | 5         | 2.07%   |
| Realtek Bluetooth Radio                             | 4         | 1.66%   |
| Intel AX210 Bluetooth                               | 4         | 1.66%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 1.66%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 4         | 1.66%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.24%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.24%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.24%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.24%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.24%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.24%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.24%   |
| Toshiba Bluetooth USB Host Controller               | 2         | 0.83%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.83%   |
| IMC Networks Wireless_Device                        | 2         | 0.83%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.83%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.83%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.83%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.83%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 0.83%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.83%   |
| USI Bluetooth Device                                | 1         | 0.41%   |
| TP-Link TP-T@- UB500 Adapter                        | 1         | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.41%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 222       | 61.84%  |
| AMD                   | 67        | 18.66%  |
| Nvidia                | 46        | 12.81%  |
| Lenovo                | 7         | 1.95%   |
| Logitech              | 3         | 0.84%   |
| Sony                  | 2         | 0.56%   |
| Realtek Semiconductor | 2         | 0.56%   |
| VIA Technologies      | 1         | 0.28%   |
| Texas Instruments     | 1         | 0.28%   |
| TerraTec Electronic   | 1         | 0.28%   |
| Roland                | 1         | 0.28%   |
| Micronas              | 1         | 0.28%   |
| Mark of the Unicorn   | 1         | 0.28%   |
| Kingston Technology   | 1         | 0.28%   |
| JMTek                 | 1         | 0.28%   |
| GN Netcom             | 1         | 0.28%   |
| C-Media Electronics   | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 46        | 10.27%  |
| Intel Sunrise Point-LP HD Audio                                            | 33        | 7.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 26        | 5.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 4.69%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 20        | 4.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19        | 4.24%   |
| AMD Radeon High Definition Audio Controller                                | 15        | 3.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 3.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 14        | 3.13%   |
| Intel Broadwell-U Audio Controller                                         | 14        | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 2.68%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 2.46%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 2.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 1.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.34%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 6         | 1.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.34%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.12%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.12%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 0.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 0.89%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 0.89%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.67%   |
| Nvidia MCP79 High Definition Audio                                         | 3         | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.67%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3         | 0.67%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.67%   |
| Nvidia AD107 High Definition Audio Controller                              | 3         | 0.67%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.45%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 70        | 34.31%  |
| SK hynix            | 45        | 22.06%  |
| Micron Technology   | 29        | 14.22%  |
| Kingston            | 19        | 9.31%   |
| Unknown             | 7         | 3.43%   |
| Crucial             | 7         | 3.43%   |
| Nanya Technology    | 5         | 2.45%   |
| G.Skill             | 4         | 1.96%   |
| A-DATA Technology   | 4         | 1.96%   |
| Ramaxel Technology  | 3         | 1.47%   |
| Elpida              | 3         | 1.47%   |
| Unknown (ABCD)      | 2         | 0.98%   |
| ASint Technology    | 2         | 0.98%   |
| Unifosa             | 1         | 0.49%   |
| Qimonda             | 1         | 0.49%   |
| Lexar               | 1         | 0.49%   |
| Kllisre             | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 2.75%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 4         | 1.83%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.83%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.38%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.38%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.38%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.38%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.92%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 2         | 0.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.92%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.92%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.92%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.92%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.92%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 2         | 0.92%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.92%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.92%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 2         | 0.92%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 2         | 0.92%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 2         | 0.92%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.92%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.92%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 2         | 0.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.92%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16GB SODIMM DDR4 2667MT/s           | 2         | 0.92%   |
| Kingston RAM KF556S40-32 32GB SODIMM DDR5 5600MT/s               | 2         | 0.92%   |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s          | 2         | 0.92%   |
| G.Skill RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 0.92%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.92%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 71        | 42.26%  |
| DDR3   | 58        | 34.52%  |
| LPDDR5 | 10        | 5.95%   |
| DDR2   | 9         | 5.36%   |
| LPDDR4 | 8         | 4.76%   |
| DDR5   | 8         | 4.76%   |
| LPDDR3 | 2         | 1.19%   |
| SDRAM  | 1         | 0.6%    |
| DDR    | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 152       | 93.25%  |
| Row Of Chips | 10        | 6.13%   |
| DIMM         | 1         | 0.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 70        | 37.23%  |
| 4096  | 50        | 26.6%   |
| 16384 | 35        | 18.62%  |
| 2048  | 17        | 9.04%   |
| 32768 | 8         | 4.26%   |
| 1024  | 7         | 3.72%   |
| 512   | 1         | 0.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 39        | 20.63%  |
| 2667    | 34        | 17.99%  |
| 3200    | 30        | 15.87%  |
| 2400    | 12        | 6.35%   |
| 1334    | 11        | 5.82%   |
| 1333    | 10        | 5.29%   |
| 5600    | 7         | 3.7%    |
| 6400    | 5         | 2.65%   |
| 4267    | 5         | 2.65%   |
| 2133    | 5         | 2.65%   |
| 1067    | 5         | 2.65%   |
| 667     | 5         | 2.65%   |
| 8400    | 3         | 1.59%   |
| 7500    | 3         | 1.59%   |
| Unknown | 3         | 1.59%   |
| 4266    | 2         | 1.06%   |
| 3266    | 2         | 1.06%   |
| 12800   | 1         | 0.53%   |
| 4800    | 1         | 0.53%   |
| 4199    | 1         | 0.53%   |
| 1867    | 1         | 0.53%   |
| 975     | 1         | 0.53%   |
| 800     | 1         | 0.53%   |
| 533     | 1         | 0.53%   |
| 400     | 1         | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung Electronics             | 1         | 25%     |
| QinHeng Electronics             | 1         | 25%     |
| cab Produkttechnik GmbH & Co KG | 1         | 25%     |
| Brother Industries              | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung ML-1670 Series                   | 1         | 25%     |
| QinHeng CH340S                           | 1         | 25%     |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 25%     |
| Brother DCP-L2510D series                | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 62        | 24.9%   |
| Microdia                               | 26        | 10.44%  |
| IMC Networks                           | 26        | 10.44%  |
| Bison Electronics                      | 23        | 9.24%   |
| Sunplus Innovation Technology          | 17        | 6.83%   |
| Realtek Semiconductor                  | 17        | 6.83%   |
| Lite-On Technology                     | 10        | 4.02%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 3.61%   |
| Luxvisions Innotech Limited            | 8         | 3.21%   |
| Syntek                                 | 7         | 2.81%   |
| Suyin                                  | 7         | 2.81%   |
| Silicon Motion                         | 7         | 2.81%   |
| Apple                                  | 7         | 2.81%   |
| Quanta                                 | 5         | 2.01%   |
| Logitech                               | 3         | 1.2%    |
| Sonix Technology                       | 2         | 0.8%    |
| Lenovo                                 | 2         | 0.8%    |
| Acer                                   | 2         | 0.8%    |
| Xiaomi                                 | 1         | 0.4%    |
| Tripath Technology                     | 1         | 0.4%    |
| Shinetech                              | 1         | 0.4%    |
| Samsung Electronics                    | 1         | 0.4%    |
| LG Electronics                         | 1         | 0.4%    |
| Importek                               | 1         | 0.4%    |
| HYGD-XH--241023                        | 1         | 0.4%    |
| Huddly                                 | 1         | 0.4%    |
| Alcor Micro                            | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 17        | 6.75%   |
| Microdia Integrated_Webcam_HD                           | 15        | 5.95%   |
| IMC Networks Integrated Camera                          | 10        | 3.97%   |
| Lite-On Integrated Camera                               | 8         | 3.17%   |
| Bison Integrated Camera                                 | 8         | 3.17%   |
| Syntek Integrated Camera                                | 5         | 1.98%   |
| Sunplus Integrated_Webcam_HD                            | 5         | 1.98%   |
| Realtek USB Camera                                      | 4         | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 1.59%   |
| Chicony Integrated HP HD Webcam                         | 4         | 1.59%   |
| Chicony HP HD Webcam                                    | 4         | 1.59%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.19%   |
| Quanta HP HD Camera                                     | 3         | 1.19%   |
| Luxvisions Innotech Limited Integrated RGB Camera       | 3         | 1.19%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.19%   |
| Chicony ThinkPad T490 Webcam                            | 3         | 1.19%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 1.19%   |
| Chicony FJ Camera                                       | 3         | 1.19%   |
| Apple FaceTime HD Camera                                | 3         | 1.19%   |
| Apple Built-in iSight                                   | 3         | 1.19%   |
| Suyin 1.3M HD WebCam                                    | 2         | 0.79%   |
| Sunplus Asus Webcam                                     | 2         | 0.79%   |
| Sonix USB2.0 FHD UVC WebCam                             | 2         | 0.79%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 0.79%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.79%   |
| Realtek Lenovo EasyCamera                               | 2         | 0.79%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 0.79%   |
| Luxvisions Innotech Limited Integrated Camera           | 2         | 0.79%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 0.79%   |
| IMC Networks EasyCamera                                 | 2         | 0.79%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 0.79%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 0.79%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 0.79%   |
| Chicony HP HD Camera                                    | 2         | 0.79%   |
| Chicony HD Webcam                                       | 2         | 0.79%   |
| Chicony HD User Facing                                  | 2         | 0.79%   |
| Chicony Chicony USB2.0 Camera                           | 2         | 0.79%   |
| Bison SunplusIT Integrated Camera                       | 2         | 0.79%   |
| Bison SunplusIT INC. Integrated Camera                  | 2         | 0.79%   |
| Bison Integrated IR Camera                              | 2         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 27        | 37.5%   |
| Synaptics                          | 25        | 34.72%  |
| STMicroelectronics                 | 5         | 6.94%   |
| Shenzhen Goodix Technology         | 5         | 6.94%   |
| Upek                               | 4         | 5.56%   |
| AuthenTec                          | 3         | 4.17%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.39%   |
| LighTuning Technology              | 1         | 1.39%   |
| Elan Microelectronics              | 1         | 1.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 11        | 15.28%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 8         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 8         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 6.94%   |
| STMicroelectronics Fingerprint Reader                           | 5         | 6.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 4         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 5.56%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 4.17%   |
| Shenzhen Goodix FingerPrint                                     | 3         | 4.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 2.78%   |
| Validity Sensors VFS491                                         | 2         | 2.78%   |
| Synaptics Prometheus Fingerprint Reader                         | 2         | 2.78%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 2.78%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 1.39%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 1.39%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.39%   |
| Synaptics WBDI                                                  | 1         | 1.39%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.39%   |
| Synaptics  WBDI                                                 | 1         | 1.39%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.39%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.39%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 1.39%   |
| Elan ELAN:Fingerprint                                           | 1         | 1.39%   |
| AuthenTec AES2810                                               | 1         | 1.39%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 1.39%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 1.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 36        | 54.55%  |
| Broadcom              | 13        | 19.7%   |
| OmniKey               | 6         | 9.09%   |
| Lenovo                | 6         | 9.09%   |
| Gemalto (was Gemplus) | 3         | 4.55%   |
| Upek                  | 1         | 1.52%   |
| O2 Micro              | 1         | 1.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 36        | 54.55%  |
| Lenovo Integrated Smart Card Reader                                          | 6         | 9.09%   |
| OmniKey CardMan 4321                                                         | 3         | 4.55%   |
| OmniKey CardMan 1021                                                         | 3         | 4.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 4.55%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 3         | 4.55%   |
| Broadcom 5880                                                                | 3         | 4.55%   |
| Broadcom 58200                                                               | 3         | 4.55%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 3.03%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.52%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.52%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.52%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 1.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 151       | 51.01%  |
| 1     | 107       | 36.15%  |
| 2     | 34        | 11.49%  |
| 3     | 3         | 1.01%   |
| 4     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 71        | 39.23%  |
| Graphics card            | 39        | 21.55%  |
| Chipcard                 | 38        | 20.99%  |
| Multimedia controller    | 11        | 6.08%   |
| Card reader              | 5         | 2.76%   |
| Camera                   | 5         | 2.76%   |
| Net/wireless             | 4         | 2.21%   |
| Net/ethernet             | 2         | 1.1%    |
| Modem                    | 2         | 1.1%    |
| Communication controller | 2         | 1.1%    |
| Storage                  | 1         | 0.55%   |
| Bluetooth                | 1         | 0.55%   |

