Linux in Sweden - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Sweden.

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

Total: 1086

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Swift SF314-42              | [f4906f3799](https://linux-hardware.org/?probe=f4906f3799) | Jun 01, 2022 |
| Toshiba       | Satellite L50D-B            | [860be26e14](https://linux-hardware.org/?probe=860be26e14) | May 29, 2022 |
| Lenovo        | ThinkPad W500 4061W8H       | [db9160e089](https://linux-hardware.org/?probe=db9160e089) | May 29, 2022 |
| HP            | ProBook 650 G1              | [b32a949b01](https://linux-hardware.org/?probe=b32a949b01) | May 28, 2022 |
| ASUSTek       | U31Jg                       | [b761173e5e](https://linux-hardware.org/?probe=b761173e5e) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| HP            | EliteBook 850 G6            | [25e4d08ac2](https://linux-hardware.org/?probe=25e4d08ac2) | May 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [2d28231751](https://linux-hardware.org/?probe=2d28231751) | May 25, 2022 |
| Apple         | MacBook6,1                  | [683ff3ab1a](https://linux-hardware.org/?probe=683ff3ab1a) | May 24, 2022 |
| Apple         | MacBookAir7,2               | [b620a51628](https://linux-hardware.org/?probe=b620a51628) | May 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [cc0b92bd45](https://linux-hardware.org/?probe=cc0b92bd45) | May 21, 2022 |
| HP            | 635                         | [2421582549](https://linux-hardware.org/?probe=2421582549) | May 21, 2022 |
| Apple         | MacBook6,1                  | [97e7c3fd74](https://linux-hardware.org/?probe=97e7c3fd74) | May 19, 2022 |
| HP            | EliteBook 8460p             | [a1cbc8b911](https://linux-hardware.org/?probe=a1cbc8b911) | May 19, 2022 |
| HP            | EliteBook Folio 1040 G3     | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [736bd1ab68](https://linux-hardware.org/?probe=736bd1ab68) | May 18, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [6c41f73e8a](https://linux-hardware.org/?probe=6c41f73e8a) | May 18, 2022 |
| HP            | 635                         | [3168b50a90](https://linux-hardware.org/?probe=3168b50a90) | May 18, 2022 |
| Apple         | MacBookPro16,2              | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| MSI           | GS73VR 7RG                  | [3815425b08](https://linux-hardware.org/?probe=3815425b08) | May 15, 2022 |
| Notebook      | NS50_70MU                   | [cff8de13ce](https://linux-hardware.org/?probe=cff8de13ce) | May 12, 2022 |
| Notebook      | NS50_70MU                   | [ebf71be1f5](https://linux-hardware.org/?probe=ebf71be1f5) | May 12, 2022 |
| MSI           | GF63 Thin 9SCSR             | [a80ef1636d](https://linux-hardware.org/?probe=a80ef1636d) | May 12, 2022 |
| ASUSTek       | A6U                         | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [38bc924977](https://linux-hardware.org/?probe=38bc924977) | May 12, 2022 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | [615d6650a0](https://linux-hardware.org/?probe=615d6650a0) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| ASUSTek       | E200HA                      | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| Samsung       | 750XDA                      | [466689475e](https://linux-hardware.org/?probe=466689475e) | May 07, 2022 |
| ASUSTek       | E200HA                      | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Dell          | Precision M4700             | [81cc8ba45c](https://linux-hardware.org/?probe=81cc8ba45c) | May 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [64eb136705](https://linux-hardware.org/?probe=64eb136705) | May 03, 2022 |
| Acer          | Aspire A315-41              | [1bd7f7cd93](https://linux-hardware.org/?probe=1bd7f7cd93) | May 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [f6cc5e2ad5](https://linux-hardware.org/?probe=f6cc5e2ad5) | May 01, 2022 |
| HP            | Pavilion Notebook           | [995ea9538b](https://linux-hardware.org/?probe=995ea9538b) | Apr 30, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | [58076aa8e9](https://linux-hardware.org/?probe=58076aa8e9) | Apr 28, 2022 |
| Dell          | XPS 13 7390                 | [37b195945a](https://linux-hardware.org/?probe=37b195945a) | Apr 28, 2022 |
| Dell          | Latitude 7420               | [8e3bcab404](https://linux-hardware.org/?probe=8e3bcab404) | Apr 28, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [3b4a331875](https://linux-hardware.org/?probe=3b4a331875) | Apr 26, 2022 |
| Lenovo        | ThinkPad T61 64665WG        | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| Lenovo        | ThinkPad T450s 20BWS3FX0... | [00d3556f08](https://linux-hardware.org/?probe=00d3556f08) | Apr 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [7988499108](https://linux-hardware.org/?probe=7988499108) | Apr 23, 2022 |
| HP            | EliteBook Folio 9470m       | [cd369fb3e3](https://linux-hardware.org/?probe=cd369fb3e3) | Apr 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [4548a301f8](https://linux-hardware.org/?probe=4548a301f8) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | [ca406cf975](https://linux-hardware.org/?probe=ca406cf975) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | [32d9d8c8df](https://linux-hardware.org/?probe=32d9d8c8df) | Apr 21, 2022 |
| ASUSTek       | G551JW                      | [b0d7f099f5](https://linux-hardware.org/?probe=b0d7f099f5) | Apr 18, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | [7855e19861](https://linux-hardware.org/?probe=7855e19861) | Apr 17, 2022 |
| Acer          | Aspire V3-571               | [5bd64f9988](https://linux-hardware.org/?probe=5bd64f9988) | Apr 17, 2022 |
| Toshiba       | BLB                         | [903779c2b2](https://linux-hardware.org/?probe=903779c2b2) | Apr 16, 2022 |
| Toshiba       | BLB                         | [1dffc347dd](https://linux-hardware.org/?probe=1dffc347dd) | Apr 16, 2022 |
| HP            | ProBook 430 G1              | [c42de00504](https://linux-hardware.org/?probe=c42de00504) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| Dell          | Latitude E7450              | [9af0006104](https://linux-hardware.org/?probe=9af0006104) | Apr 15, 2022 |
| Apple         | MacBookPro11,3              | [b2fdf48a7f](https://linux-hardware.org/?probe=b2fdf48a7f) | Apr 14, 2022 |
| Apple         | MacBookPro11,3              | [ca14d0eb57](https://linux-hardware.org/?probe=ca14d0eb57) | Apr 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [68e6736cd2](https://linux-hardware.org/?probe=68e6736cd2) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [d9f1aff70a](https://linux-hardware.org/?probe=d9f1aff70a) | Apr 13, 2022 |
| Packard Be... | EasyNote ENTG71BM           | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| ASUSTek       | N56DY                       | [8fdcef45a9](https://linux-hardware.org/?probe=8fdcef45a9) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ce0316a106](https://linux-hardware.org/?probe=ce0316a106) | Apr 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Apple         | MacBookPro11,3              | [16fa67b6c1](https://linux-hardware.org/?probe=16fa67b6c1) | Apr 07, 2022 |
| Apple         | MacBookPro11,3              | [fca3b357c3](https://linux-hardware.org/?probe=fca3b357c3) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f4c5281aa9](https://linux-hardware.org/?probe=f4c5281aa9) | Apr 07, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [1c62a4c421](https://linux-hardware.org/?probe=1c62a4c421) | Apr 07, 2022 |
| HP            | EliteBook 8760w             | [e3a9cdfd95](https://linux-hardware.org/?probe=e3a9cdfd95) | Apr 05, 2022 |
| ASUSTek       | UX32VD                      | [31836fcaa9](https://linux-hardware.org/?probe=31836fcaa9) | Apr 05, 2022 |
| Gigabyte      | P65Q                        | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [0b247aa185](https://linux-hardware.org/?probe=0b247aa185) | Mar 30, 2022 |
| Dell          | Precision 5540              | [26060f12a6](https://linux-hardware.org/?probe=26060f12a6) | Mar 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e5b0f5c259](https://linux-hardware.org/?probe=e5b0f5c259) | Mar 27, 2022 |
| Apple         | MacBookPro11,3              | [4e534bb83a](https://linux-hardware.org/?probe=4e534bb83a) | Mar 26, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [e0ae9fa252](https://linux-hardware.org/?probe=e0ae9fa252) | Mar 24, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| HP            | ProBook 430 G1              | [9f295312dc](https://linux-hardware.org/?probe=9f295312dc) | Mar 21, 2022 |
| Dell          | Latitude 7300               | [751dc53e2b](https://linux-hardware.org/?probe=751dc53e2b) | Mar 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| HP            | EliteBook 850 G5            | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| Dell          | Inspiron MP061              | [2b46add19f](https://linux-hardware.org/?probe=2b46add19f) | Mar 16, 2022 |
| Fujitsu       | LIFEBOOK E546               | [247dd3e47c](https://linux-hardware.org/?probe=247dd3e47c) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Toshiba       | Satellite C50D-A-14E        | [256e08de3d](https://linux-hardware.org/?probe=256e08de3d) | Mar 13, 2022 |
| Lenovo        | Flex 2-15 20405             | [3e4ac3a045](https://linux-hardware.org/?probe=3e4ac3a045) | Mar 07, 2022 |
| HP            | ENVY 15                     | [a4f5eedd3c](https://linux-hardware.org/?probe=a4f5eedd3c) | Mar 06, 2022 |
| ASUSTek       | E205SA                      | [4c896c9379](https://linux-hardware.org/?probe=4c896c9379) | Mar 05, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | [af4563cb12](https://linux-hardware.org/?probe=af4563cb12) | Mar 04, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [88a973e27f](https://linux-hardware.org/?probe=88a973e27f) | Mar 02, 2022 |
| Google        | Rammus                      | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| HP            | ProBook 640 G2              | [75cdf384b5](https://linux-hardware.org/?probe=75cdf384b5) | Feb 27, 2022 |
| Acer          | Aspire V3-571               | [ff2de5c1da](https://linux-hardware.org/?probe=ff2de5c1da) | Feb 27, 2022 |
| Sony          | VPCEB36FG                   | [d46f784fbb](https://linux-hardware.org/?probe=d46f784fbb) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [cfd0806662](https://linux-hardware.org/?probe=cfd0806662) | Feb 25, 2022 |
| Acer          | Swift SF314-43              | [1434453fc0](https://linux-hardware.org/?probe=1434453fc0) | Feb 24, 2022 |
| Acer          | Swift SF514-52T             | [3bfa40a4c8](https://linux-hardware.org/?probe=3bfa40a4c8) | Feb 24, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | [4a18cd9a94](https://linux-hardware.org/?probe=4a18cd9a94) | Feb 22, 2022 |
| ASUSTek       | G75VW                       | [d31201b74c](https://linux-hardware.org/?probe=d31201b74c) | Feb 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [672f08c769](https://linux-hardware.org/?probe=672f08c769) | Feb 22, 2022 |
| Dell          | Precision 3510              | [3956ab645b](https://linux-hardware.org/?probe=3956ab645b) | Feb 21, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [d2119e4516](https://linux-hardware.org/?probe=d2119e4516) | Feb 21, 2022 |
| Unknown       | Unknown                     | [129c8a24d9](https://linux-hardware.org/?probe=129c8a24d9) | Feb 20, 2022 |
| ZEPTO         | ZNOTE                       | [5ff5c2b966](https://linux-hardware.org/?probe=5ff5c2b966) | Feb 20, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | [dda75e3ba9](https://linux-hardware.org/?probe=dda75e3ba9) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7b9e4b097d](https://linux-hardware.org/?probe=7b9e4b097d) | Feb 18, 2022 |
| HP            | Pavilion Gaming Notebook    | [b0cf9aa220](https://linux-hardware.org/?probe=b0cf9aa220) | Feb 18, 2022 |
| HP            | Pavilion dv6                | [012e2b5d56](https://linux-hardware.org/?probe=012e2b5d56) | Feb 15, 2022 |
| Dell          | Latitude 5480               | [62ab6cb2c3](https://linux-hardware.org/?probe=62ab6cb2c3) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a8c5477e60](https://linux-hardware.org/?probe=a8c5477e60) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| Dell          | Latitude E6430              | [4b91478aaa](https://linux-hardware.org/?probe=4b91478aaa) | Feb 11, 2022 |
| Dell          | Latitude D620               | [dfbcd57dc6](https://linux-hardware.org/?probe=dfbcd57dc6) | Feb 10, 2022 |
| HP            | ENVY 15                     | [91c40a9559](https://linux-hardware.org/?probe=91c40a9559) | Feb 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [95b53bcaf7](https://linux-hardware.org/?probe=95b53bcaf7) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | [8f36d1baac](https://linux-hardware.org/?probe=8f36d1baac) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | [accf5c8a43](https://linux-hardware.org/?probe=accf5c8a43) | Feb 08, 2022 |
| Lenovo        | E31-70 80KX                 | [d4fe754aa4](https://linux-hardware.org/?probe=d4fe754aa4) | Feb 07, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [2427f8c1da](https://linux-hardware.org/?probe=2427f8c1da) | Feb 07, 2022 |
| Acer          | Swift SF314-43              | [386053c3ce](https://linux-hardware.org/?probe=386053c3ce) | Feb 07, 2022 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [15419beff9](https://linux-hardware.org/?probe=15419beff9) | Feb 02, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [f111410eeb](https://linux-hardware.org/?probe=f111410eeb) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | [108d91c953](https://linux-hardware.org/?probe=108d91c953) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | [d866cabd88](https://linux-hardware.org/?probe=d866cabd88) | Feb 02, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [340ecf86ab](https://linux-hardware.org/?probe=340ecf86ab) | Feb 01, 2022 |
| ASUSTek       | GR8                         | [1d8f5be27c](https://linux-hardware.org/?probe=1d8f5be27c) | Jan 30, 2022 |
| Apple         | MacBook3,1                  | [a59b4aa98d](https://linux-hardware.org/?probe=a59b4aa98d) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [b584b0b69a](https://linux-hardware.org/?probe=b584b0b69a) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6b771832b8](https://linux-hardware.org/?probe=6b771832b8) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | [1d8bb5fbe6](https://linux-hardware.org/?probe=1d8bb5fbe6) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | [87aa03d881](https://linux-hardware.org/?probe=87aa03d881) | Jan 27, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Apple         | MacBookPro12,1              | [c5c764ccd7](https://linux-hardware.org/?probe=c5c764ccd7) | Jan 24, 2022 |
| Dell          | Latitude E7440              | [74aa958191](https://linux-hardware.org/?probe=74aa958191) | Jan 23, 2022 |
| Notebook      | N13xWU                      | [0d615c6812](https://linux-hardware.org/?probe=0d615c6812) | Jan 22, 2022 |
| Acer          | Swift SF315-41              | [95afa35615](https://linux-hardware.org/?probe=95afa35615) | Jan 22, 2022 |
| Dell          | Inspiron 5721               | [5310b893aa](https://linux-hardware.org/?probe=5310b893aa) | Jan 19, 2022 |
| Dell          | Latitude 7480               | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| Acer          | Aspire ES1-111              | [2dfe5563ef](https://linux-hardware.org/?probe=2dfe5563ef) | Jan 17, 2022 |
| HP            | EliteBook 850 G3            | [35b6de7b5d](https://linux-hardware.org/?probe=35b6de7b5d) | Jan 16, 2022 |
| Dell          | Precision 3561              | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | [2e8135c20d](https://linux-hardware.org/?probe=2e8135c20d) | Jan 15, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [df5d687786](https://linux-hardware.org/?probe=df5d687786) | Jan 14, 2022 |
| Lenovo        | ThinkPad X240 20AMS6170H    | [03fc719875](https://linux-hardware.org/?probe=03fc719875) | Jan 14, 2022 |
| Dell          | Latitude 5290               | [f1c632a454](https://linux-hardware.org/?probe=f1c632a454) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| ASUSTek       | UX310UQ                     | [a9b40e5f8c](https://linux-hardware.org/?probe=a9b40e5f8c) | Jan 10, 2022 |
| Sony          | VPCEB3S1E                   | [6f78e2d423](https://linux-hardware.org/?probe=6f78e2d423) | Jan 07, 2022 |
| Lenovo        | B50-30 80ES                 | [42db32249d](https://linux-hardware.org/?probe=42db32249d) | Jan 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | [148a68191d](https://linux-hardware.org/?probe=148a68191d) | Jan 06, 2022 |
| HP            | EliteBook 1040 G2           | [ca6f52fbeb](https://linux-hardware.org/?probe=ca6f52fbeb) | Jan 06, 2022 |
| Samsung       | 935XDB                      | [1bb7122515](https://linux-hardware.org/?probe=1bb7122515) | Jan 06, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Lenovo        | B50-30 80ES                 | [649be03cf4](https://linux-hardware.org/?probe=649be03cf4) | Jan 06, 2022 |
| Packard Be... | EasyNote TE69BM             | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| Dell          | XPS 13 9350                 | [492d47c1fa](https://linux-hardware.org/?probe=492d47c1fa) | Jan 04, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [367ef74be3](https://linux-hardware.org/?probe=367ef74be3) | Jan 01, 2022 |
| Apple         | MacBookPro11,3              | [4a20cd5429](https://linux-hardware.org/?probe=4a20cd5429) | Jan 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [fbc9c7ad1a](https://linux-hardware.org/?probe=fbc9c7ad1a) | Jan 01, 2022 |
| Samsung       | 905S3G/906S3G/915S3G        | [7a756782d8](https://linux-hardware.org/?probe=7a756782d8) | Dec 31, 2021 |
| ZEPTO         | ZNOTE                       | [f81a927e9b](https://linux-hardware.org/?probe=f81a927e9b) | Dec 31, 2021 |
| Dell          | Precision 5540              | [ba4fef27b9](https://linux-hardware.org/?probe=ba4fef27b9) | Dec 30, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [51d4addbb3](https://linux-hardware.org/?probe=51d4addbb3) | Dec 29, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DM... | [e1ba67fc0f](https://linux-hardware.org/?probe=e1ba67fc0f) | Dec 28, 2021 |
| eMachines     | E525                        | [fd80580005](https://linux-hardware.org/?probe=fd80580005) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| Acer          | AOHAPPY                     | [3a8a8f6b8e](https://linux-hardware.org/?probe=3a8a8f6b8e) | Dec 27, 2021 |
| Acer          | Swift SF314-511             | [3a201fd936](https://linux-hardware.org/?probe=3a201fd936) | Dec 27, 2021 |
| Apple         | MacBook3,1                  | [705810cc40](https://linux-hardware.org/?probe=705810cc40) | Dec 25, 2021 |
| eMachines     | E525                        | [fcc3b2a5e3](https://linux-hardware.org/?probe=fcc3b2a5e3) | Dec 25, 2021 |
| eMachines     | E525                        | [e5853e5629](https://linux-hardware.org/?probe=e5853e5629) | Dec 25, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | [edad019098](https://linux-hardware.org/?probe=edad019098) | Dec 23, 2021 |
| HP            | EliteBook Folio 9470m       | [9dd62bbf73](https://linux-hardware.org/?probe=9dd62bbf73) | Dec 23, 2021 |
| Toshiba       | Satellite L50D-B            | [b5a9d0b1dc](https://linux-hardware.org/?probe=b5a9d0b1dc) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Packard Be... | EasyNote TE69HW             | [c6876b9023](https://linux-hardware.org/?probe=c6876b9023) | Dec 20, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [3fea1de018](https://linux-hardware.org/?probe=3fea1de018) | Dec 20, 2021 |
| eMachines     | E525                        | [bcb03ff38c](https://linux-hardware.org/?probe=bcb03ff38c) | Dec 20, 2021 |
| MSI           | Katana GF66 11UE            | [36aea8dc19](https://linux-hardware.org/?probe=36aea8dc19) | Dec 18, 2021 |
| Dell          | Precision 5540              | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| MSI           | Katana GF66 11UE            | [56be528067](https://linux-hardware.org/?probe=56be528067) | Dec 18, 2021 |
| Dell          | XPS 15 9500                 | [98e451612c](https://linux-hardware.org/?probe=98e451612c) | Dec 17, 2021 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | [38d349f99c](https://linux-hardware.org/?probe=38d349f99c) | Dec 15, 2021 |
| Dell          | Latitude E6400              | [2936dcb6ab](https://linux-hardware.org/?probe=2936dcb6ab) | Dec 14, 2021 |
| Acer          | Nitro AN515-45              | [d4bed6e3e7](https://linux-hardware.org/?probe=d4bed6e3e7) | Dec 14, 2021 |
| Dell          | Latitude E7450              | [f5f9fd93f9](https://linux-hardware.org/?probe=f5f9fd93f9) | Dec 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S0V400    | [77c3ba8640](https://linux-hardware.org/?probe=77c3ba8640) | Dec 09, 2021 |
| Dell          | Precision 5560              | [2af841d052](https://linux-hardware.org/?probe=2af841d052) | Dec 07, 2021 |
| Dell          | Precision 5560              | [aeba66f4d6](https://linux-hardware.org/?probe=aeba66f4d6) | Dec 07, 2021 |
| HP            | Pavilion dv6                | [479a9e57d5](https://linux-hardware.org/?probe=479a9e57d5) | Dec 07, 2021 |
| HP            | Pavilion dv6                | [98ad56ddcc](https://linux-hardware.org/?probe=98ad56ddcc) | Dec 07, 2021 |
| Lenovo        | B50-70 80EU                 | [80d04f078e](https://linux-hardware.org/?probe=80d04f078e) | Dec 07, 2021 |
| HP            | Compaq CQ58                 | [a859413f86](https://linux-hardware.org/?probe=a859413f86) | Dec 05, 2021 |
| Apple         | MacBookPro14,3              | [b08702eb1e](https://linux-hardware.org/?probe=b08702eb1e) | Dec 05, 2021 |
| HUAWEI        | VLT-WX0                     | [3e01a8673d](https://linux-hardware.org/?probe=3e01a8673d) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| Dell          | XPS 13 9310                 | [fa0051b73b](https://linux-hardware.org/?probe=fa0051b73b) | Dec 02, 2021 |
| Apple         | MacBookPro14,3              | [a7366c8449](https://linux-hardware.org/?probe=a7366c8449) | Dec 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | [fa59cc1ea9](https://linux-hardware.org/?probe=fa59cc1ea9) | Dec 01, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [5f2264a472](https://linux-hardware.org/?probe=5f2264a472) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [af8104b01a](https://linux-hardware.org/?probe=af8104b01a) | Nov 30, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | [66f2018614](https://linux-hardware.org/?probe=66f2018614) | Nov 30, 2021 |
| Toshiba       | Satellite C50-A-19U         | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Acer          | Predator PT315-51           | [b37881e828](https://linux-hardware.org/?probe=b37881e828) | Nov 29, 2021 |
| HP            | EliteBook 8460p             | [56f6b7ec0a](https://linux-hardware.org/?probe=56f6b7ec0a) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a74aec830e](https://linux-hardware.org/?probe=a74aec830e) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [af530bb7c7](https://linux-hardware.org/?probe=af530bb7c7) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [6056117cca](https://linux-hardware.org/?probe=6056117cca) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | [19f2a1dd2f](https://linux-hardware.org/?probe=19f2a1dd2f) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | [90f2d59148](https://linux-hardware.org/?probe=90f2d59148) | Nov 26, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7ac3b720be](https://linux-hardware.org/?probe=7ac3b720be) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | [3352efa5cd](https://linux-hardware.org/?probe=3352efa5cd) | Nov 25, 2021 |
| Apple         | MacBookPro10,1              | [27d5b7dc47](https://linux-hardware.org/?probe=27d5b7dc47) | Nov 24, 2021 |
| HP            | Pavilion Notebook           | [ee309c7776](https://linux-hardware.org/?probe=ee309c7776) | Nov 23, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [0f39f8f706](https://linux-hardware.org/?probe=0f39f8f706) | Nov 22, 2021 |
| Dell          | XPS 13 9370                 | [9f8a07614e](https://linux-hardware.org/?probe=9f8a07614e) | Nov 21, 2021 |
| ASUSTek       | K53U                        | [12136b1cbd](https://linux-hardware.org/?probe=12136b1cbd) | Nov 20, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [2c0279ade5](https://linux-hardware.org/?probe=2c0279ade5) | Nov 20, 2021 |
| ASUSTek       | K53U                        | [5a5b8c420f](https://linux-hardware.org/?probe=5a5b8c420f) | Nov 20, 2021 |
| Dell          | Latitude E5570              | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Google        | Edgar                       | [0c4bb072e0](https://linux-hardware.org/?probe=0c4bb072e0) | Nov 16, 2021 |
| HP            | ProBook 6450b               | [943ef75a8b](https://linux-hardware.org/?probe=943ef75a8b) | Nov 16, 2021 |
| Dell          | XPS 13 9370                 | [343fdf2e23](https://linux-hardware.org/?probe=343fdf2e23) | Nov 16, 2021 |
| Lenovo        | B50-10 80QR                 | [cb474c37e6](https://linux-hardware.org/?probe=cb474c37e6) | Nov 15, 2021 |
| Lenovo        | ThinkPad 25 20K70000MX      | [86d3ea8b6a](https://linux-hardware.org/?probe=86d3ea8b6a) | Nov 15, 2021 |
| Google        | Edgar                       | [9cb0616971](https://linux-hardware.org/?probe=9cb0616971) | Nov 15, 2021 |
| HP            | Pavilion g7                 | [dbdeebfe86](https://linux-hardware.org/?probe=dbdeebfe86) | Nov 14, 2021 |
| Lenovo        | ThinkPad X260 20F5S0E000    | [2321968d02](https://linux-hardware.org/?probe=2321968d02) | Nov 09, 2021 |
| ASUSTek       | N550JK                      | [23fd9d7d0d](https://linux-hardware.org/?probe=23fd9d7d0d) | Nov 06, 2021 |
| HP            | EliteBook 2570p             | [dc62969834](https://linux-hardware.org/?probe=dc62969834) | Nov 05, 2021 |
| Sony          | VPCCA2S1E                   | [2ce8a8295b](https://linux-hardware.org/?probe=2ce8a8295b) | Nov 05, 2021 |
| HP            | ProBook 640 G1              | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| Google        | Grunt                       | [e6c7c07304](https://linux-hardware.org/?probe=e6c7c07304) | Nov 04, 2021 |
| HP            | ZBook 15 G6                 | [36b8c3bedd](https://linux-hardware.org/?probe=36b8c3bedd) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480 20L50009MX    | [349faf5242](https://linux-hardware.org/?probe=349faf5242) | Nov 03, 2021 |
| On by NetO... | LT1.1 BRZ                   | [a520593d47](https://linux-hardware.org/?probe=a520593d47) | Nov 02, 2021 |
| On by NetO... | LT1.1 BRZ                   | [f9312f99c7](https://linux-hardware.org/?probe=f9312f99c7) | Nov 02, 2021 |
| Unknown       | Unknown                     | [ae9e2708e9](https://linux-hardware.org/?probe=ae9e2708e9) | Nov 02, 2021 |
| HP            | Laptop 15-bw0xx             | [1869db225e](https://linux-hardware.org/?probe=1869db225e) | Nov 02, 2021 |
| HP            | ZBook 14 G2                 | [ffb40f821b](https://linux-hardware.org/?probe=ffb40f821b) | Oct 30, 2021 |
| Sony          | VGN-CS31S_W                 | [13451dd6c5](https://linux-hardware.org/?probe=13451dd6c5) | Oct 30, 2021 |
| HP            | ProBook 430 G1              | [15d9329bd3](https://linux-hardware.org/?probe=15d9329bd3) | Oct 28, 2021 |
| ASUSTek       | T100HAN                     | [c518746ece](https://linux-hardware.org/?probe=c518746ece) | Oct 25, 2021 |
| ASUSTek       | T100HAN                     | [5f27dd2f45](https://linux-hardware.org/?probe=5f27dd2f45) | Oct 25, 2021 |
| Acer          | Nitro AN515-45              | [f6ddc3a2da](https://linux-hardware.org/?probe=f6ddc3a2da) | Oct 24, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e9991e486b](https://linux-hardware.org/?probe=e9991e486b) | Oct 23, 2021 |
| Unknown       | Unknown                     | [470c0932ae](https://linux-hardware.org/?probe=470c0932ae) | Oct 23, 2021 |
| Acer          | Aspire V3-772G              | [10e7ffc71d](https://linux-hardware.org/?probe=10e7ffc71d) | Oct 19, 2021 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [2e44d637e3](https://linux-hardware.org/?probe=2e44d637e3) | Oct 16, 2021 |
| Dell          | Latitude E5250              | [793091ac6a](https://linux-hardware.org/?probe=793091ac6a) | Oct 14, 2021 |
| Google        | Treeya                      | [82b0964b6d](https://linux-hardware.org/?probe=82b0964b6d) | Oct 14, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [c3cdfe0336](https://linux-hardware.org/?probe=c3cdfe0336) | Oct 14, 2021 |
| HP            | EliteBook 830 G6            | [66a9b21300](https://linux-hardware.org/?probe=66a9b21300) | Oct 14, 2021 |
| Google        | Treeya                      | [6c10b9bcb3](https://linux-hardware.org/?probe=6c10b9bcb3) | Oct 14, 2021 |
| ASUSTek       | TP201SA                     | [504956d2e9](https://linux-hardware.org/?probe=504956d2e9) | Oct 13, 2021 |
| eMachines     | G730                        | [6450ba7397](https://linux-hardware.org/?probe=6450ba7397) | Oct 12, 2021 |
| eMachines     | G730                        | [b24afe5dc2](https://linux-hardware.org/?probe=b24afe5dc2) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| Apple         | MacBookAir7,2               | [31ae42bc51](https://linux-hardware.org/?probe=31ae42bc51) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | [5b47e8efcb](https://linux-hardware.org/?probe=5b47e8efcb) | Oct 09, 2021 |
| ASUSTek       | X550LB                      | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| HP            | EliteBook 830 G6            | [28ecb03df2](https://linux-hardware.org/?probe=28ecb03df2) | Oct 05, 2021 |
| Dell          | Latitude 5290               | [e3afd1ef97](https://linux-hardware.org/?probe=e3afd1ef97) | Oct 04, 2021 |
| HP            | ProBook 430 G1              | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Dell          | Precision M6800             | [b85ad62146](https://linux-hardware.org/?probe=b85ad62146) | Oct 03, 2021 |
| Dell          | Precision M6800             | [61a932607b](https://linux-hardware.org/?probe=61a932607b) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [46db33820d](https://linux-hardware.org/?probe=46db33820d) | Oct 03, 2021 |
| Lenovo        | G50-80 80E5                 | [133b546e7f](https://linux-hardware.org/?probe=133b546e7f) | Oct 03, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [9c3c1f9a85](https://linux-hardware.org/?probe=9c3c1f9a85) | Oct 01, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6876f0e86d](https://linux-hardware.org/?probe=6876f0e86d) | Sep 29, 2021 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [4a91c75662](https://linux-hardware.org/?probe=4a91c75662) | Sep 28, 2021 |
| HP            | EliteBook 830 G6            | [72c41f4a85](https://linux-hardware.org/?probe=72c41f4a85) | Sep 27, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [560598d6fb](https://linux-hardware.org/?probe=560598d6fb) | Sep 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | [2460060920](https://linux-hardware.org/?probe=2460060920) | Sep 25, 2021 |
| HP            | Laptop 15s-eq2xxx           | [639131ddd5](https://linux-hardware.org/?probe=639131ddd5) | Sep 25, 2021 |
| ASUSTek       | GL553VE                     | [c55708bb3f](https://linux-hardware.org/?probe=c55708bb3f) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [df7ff85482](https://linux-hardware.org/?probe=df7ff85482) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [36c78f1667](https://linux-hardware.org/?probe=36c78f1667) | Sep 23, 2021 |
| HP            | Presario CQ62               | [dc91fe3b30](https://linux-hardware.org/?probe=dc91fe3b30) | Sep 22, 2021 |
| Apple         | MacBookAir7,2               | [83f3d6df86](https://linux-hardware.org/?probe=83f3d6df86) | Sep 21, 2021 |
| Apple         | MacBookPro8,1               | [5b337fdb0a](https://linux-hardware.org/?probe=5b337fdb0a) | Sep 20, 2021 |
| Dell          | Inspiron 14 5410 2-in-1     | [439f4b690a](https://linux-hardware.org/?probe=439f4b690a) | Sep 20, 2021 |
| Dell          | Inspiron 14 5410 2-in-1     | [a9edf67742](https://linux-hardware.org/?probe=a9edf67742) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | [7c806aa7c5](https://linux-hardware.org/?probe=7c806aa7c5) | Sep 19, 2021 |
| Dell          | Latitude E7450              | [f5963dc359](https://linux-hardware.org/?probe=f5963dc359) | Sep 18, 2021 |
| Dell          | Precision 7720              | [80f3d1e3b0](https://linux-hardware.org/?probe=80f3d1e3b0) | Sep 17, 2021 |
| Dell          | Latitude 5290               | [baae3812d5](https://linux-hardware.org/?probe=baae3812d5) | Sep 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [dc1b85b8c9](https://linux-hardware.org/?probe=dc1b85b8c9) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| HP            | EliteBook 820 G1            | [9631d6f9e1](https://linux-hardware.org/?probe=9631d6f9e1) | Sep 14, 2021 |
| Acer          | Swift SF314-511             | [4286a4710c](https://linux-hardware.org/?probe=4286a4710c) | Sep 11, 2021 |
| Acer          | Swift SF114-33              | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Toshiba       | Satellite L50D-B            | [6eb7be93e9](https://linux-hardware.org/?probe=6eb7be93e9) | Sep 10, 2021 |
| HP            | ProBook 6460b               | [b0f0eaf216](https://linux-hardware.org/?probe=b0f0eaf216) | Sep 09, 2021 |
| HP            | ZBook 17 G3                 | [7e85c2791f](https://linux-hardware.org/?probe=7e85c2791f) | Sep 07, 2021 |
| HP            | ProBook 4540s               | [41d764faaf](https://linux-hardware.org/?probe=41d764faaf) | Sep 06, 2021 |
| PC Special... | N150CU                      | [2fd6f4b53c](https://linux-hardware.org/?probe=2fd6f4b53c) | Sep 05, 2021 |
| HP            | ProBook 6450b               | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d40a00437d](https://linux-hardware.org/?probe=d40a00437d) | Aug 30, 2021 |
| Lenovo        | B51-80 80LM                 | [a81c83bd1c](https://linux-hardware.org/?probe=a81c83bd1c) | Aug 30, 2021 |
| Acer          | Aspire E5-573G              | [78ad2b6854](https://linux-hardware.org/?probe=78ad2b6854) | Aug 27, 2021 |
| Lenovo        | ThinkPad T420s 4174FM9      | [12fd92046e](https://linux-hardware.org/?probe=12fd92046e) | Aug 27, 2021 |
| ASUSTek       | X510UAR                     | [cd238d180b](https://linux-hardware.org/?probe=cd238d180b) | Aug 23, 2021 |
| Toshiba       | Satellite L50D-B            | [1e514cb947](https://linux-hardware.org/?probe=1e514cb947) | Aug 23, 2021 |
| Dell          | Inspiron 7520               | [a8e8ae384a](https://linux-hardware.org/?probe=a8e8ae384a) | Aug 20, 2021 |
| Dell          | XPS 15 9500                 | [6d76e9c22e](https://linux-hardware.org/?probe=6d76e9c22e) | Aug 18, 2021 |
| PC Special... | Standard                    | [b7baa43d24](https://linux-hardware.org/?probe=b7baa43d24) | Aug 18, 2021 |
| MSI           | GP63 Leopard 8RE            | [40a8ec3a95](https://linux-hardware.org/?probe=40a8ec3a95) | Aug 16, 2021 |
| Razer         | Blade                       | [b6bad1f725](https://linux-hardware.org/?probe=b6bad1f725) | Aug 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [77c51b6b7b](https://linux-hardware.org/?probe=77c51b6b7b) | Aug 15, 2021 |
| HP            | Pavilion 17                 | [b628f70687](https://linux-hardware.org/?probe=b628f70687) | Aug 15, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3DK1... | [695ac6427d](https://linux-hardware.org/?probe=695ac6427d) | Aug 15, 2021 |
| HP            | Compaq nc6320 (EV073AV)     | [bf6050f750](https://linux-hardware.org/?probe=bf6050f750) | Aug 14, 2021 |
| Lenovo        | ThinkPad X250 20CM001RMS    | [d0dfc1011e](https://linux-hardware.org/?probe=d0dfc1011e) | Aug 12, 2021 |
| Lenovo        | Z50-70 20354                | [1eba114602](https://linux-hardware.org/?probe=1eba114602) | Aug 11, 2021 |
| Lenovo        | Z50-70 20354                | [a31c1f0fda](https://linux-hardware.org/?probe=a31c1f0fda) | Aug 11, 2021 |
| Dell          | Inspiron ME051              | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| Lenovo        | Z50-70 20354                | [c1209f4d40](https://linux-hardware.org/?probe=c1209f4d40) | Aug 09, 2021 |
| Dell          | Precision M4500             | [d7b650fecf](https://linux-hardware.org/?probe=d7b650fecf) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| Dell          | XPS 15 7590                 | [1778263a70](https://linux-hardware.org/?probe=1778263a70) | Aug 08, 2021 |
| Lenovo        | Z50-70 20354                | [9e08265168](https://linux-hardware.org/?probe=9e08265168) | Aug 08, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| Dell          | Latitude E6400              | [dea83da57d](https://linux-hardware.org/?probe=dea83da57d) | Aug 04, 2021 |
| Packard Be... | EasyNote TS11SB             | [aa9468a3de](https://linux-hardware.org/?probe=aa9468a3de) | Aug 03, 2021 |
| Packard Be... | EasyNote TS11SB             | [57fbaedb1e](https://linux-hardware.org/?probe=57fbaedb1e) | Aug 03, 2021 |
| HP            | Elite x2 1012 G1            | [7c2abb5f03](https://linux-hardware.org/?probe=7c2abb5f03) | Aug 02, 2021 |
| HP            | Pavilion 15                 | [08bd4b9549](https://linux-hardware.org/?probe=08bd4b9549) | Aug 02, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [5cacc2c659](https://linux-hardware.org/?probe=5cacc2c659) | Jul 29, 2021 |
| Toshiba       | Satellite L750              | [822adc34c6](https://linux-hardware.org/?probe=822adc34c6) | Jul 28, 2021 |
| HP            | ProBook 6460b               | [ad2986d747](https://linux-hardware.org/?probe=ad2986d747) | Jul 26, 2021 |
| HP            | Pavilion dv6500             | [896e1bc2a0](https://linux-hardware.org/?probe=896e1bc2a0) | Jul 25, 2021 |
| HP            | Pavilion dv6500             | [1325b6d6c2](https://linux-hardware.org/?probe=1325b6d6c2) | Jul 25, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [ed51414a9d](https://linux-hardware.org/?probe=ed51414a9d) | Jul 22, 2021 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | [64c8fe4e52](https://linux-hardware.org/?probe=64c8fe4e52) | Jul 20, 2021 |
| Dell          | Vostro 3500                 | [2e8c9fa212](https://linux-hardware.org/?probe=2e8c9fa212) | Jul 18, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Intel Clie... | LAPBC710                    | [49a2ccdeee](https://linux-hardware.org/?probe=49a2ccdeee) | Jul 12, 2021 |
| HP            | Pavilion 15                 | [b4eeb3105e](https://linux-hardware.org/?probe=b4eeb3105e) | Jul 12, 2021 |
| HP            | Pavilion dv6                | [bb0f20f7a9](https://linux-hardware.org/?probe=bb0f20f7a9) | Jul 10, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [8845d0216e](https://linux-hardware.org/?probe=8845d0216e) | Jul 09, 2021 |
| HP            | Elite x2 1012 G1            | [4d5cea91ad](https://linux-hardware.org/?probe=4d5cea91ad) | Jul 07, 2021 |
| HP            | EliteBook 8470p             | [505684a737](https://linux-hardware.org/?probe=505684a737) | Jul 07, 2021 |
| Apple         | MacBookPro11,5              | [43d77edd56](https://linux-hardware.org/?probe=43d77edd56) | Jul 01, 2021 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | [c0ba9a0437](https://linux-hardware.org/?probe=c0ba9a0437) | Jun 30, 2021 |
| Apple         | MacBookPro11,5              | [103c0edcbd](https://linux-hardware.org/?probe=103c0edcbd) | Jun 30, 2021 |
| Lenovo        | ThinkPad T460 20FMS06105    | [242cf25827](https://linux-hardware.org/?probe=242cf25827) | Jun 29, 2021 |
| Lenovo        | ThinkPad X201 3626FAG       | [259908557b](https://linux-hardware.org/?probe=259908557b) | Jun 28, 2021 |
| Toshiba       | Satellite L855              | [45df91892a](https://linux-hardware.org/?probe=45df91892a) | Jun 27, 2021 |
| Toshiba       | Satellite L855              | [5fc995dac3](https://linux-hardware.org/?probe=5fc995dac3) | Jun 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [392be37a79](https://linux-hardware.org/?probe=392be37a79) | Jun 25, 2021 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [6995133402](https://linux-hardware.org/?probe=6995133402) | Jun 24, 2021 |
| Lenovo        | B50-30 80ES                 | [b9d0b5be2d](https://linux-hardware.org/?probe=b9d0b5be2d) | Jun 23, 2021 |
| ASUSTek       | ROG Strix G731GW_G731GW     | [85a0c7c512](https://linux-hardware.org/?probe=85a0c7c512) | Jun 23, 2021 |
| Lenovo        | B50-30 80ES                 | [e2b40afe3c](https://linux-hardware.org/?probe=e2b40afe3c) | Jun 23, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [e4ba771332](https://linux-hardware.org/?probe=e4ba771332) | Jun 22, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [495c04a536](https://linux-hardware.org/?probe=495c04a536) | Jun 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c1abf6c844](https://linux-hardware.org/?probe=c1abf6c844) | Jun 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [aa95a9d75f](https://linux-hardware.org/?probe=aa95a9d75f) | Jun 20, 2021 |
| Lenovo        | IdeaPadFlex 15 20309        | [7a60f78b32](https://linux-hardware.org/?probe=7a60f78b32) | Jun 17, 2021 |
| HP            | ZBook 17 G2                 | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| HP            | EliteBook 725 G3            | [f57f7d1e53](https://linux-hardware.org/?probe=f57f7d1e53) | Jun 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [0e1e07507e](https://linux-hardware.org/?probe=0e1e07507e) | Jun 15, 2021 |
| Dell          | Latitude 3350               | [7fe0552d03](https://linux-hardware.org/?probe=7fe0552d03) | Jun 14, 2021 |
| Dell          | XPS 17 9700                 | [293537d794](https://linux-hardware.org/?probe=293537d794) | Jun 11, 2021 |
| HP            | ZBook 17 G2                 | [05a2ecf3ec](https://linux-hardware.org/?probe=05a2ecf3ec) | Jun 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [48bda0fbd3](https://linux-hardware.org/?probe=48bda0fbd3) | Jun 09, 2021 |
| Lenovo        | ThinkPad X201 4492W36       | [f309552e6e](https://linux-hardware.org/?probe=f309552e6e) | Jun 07, 2021 |
| Sony          | VPCCA2S1E                   | [6b20cf032f](https://linux-hardware.org/?probe=6b20cf032f) | Jun 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [117372a8ff](https://linux-hardware.org/?probe=117372a8ff) | Jun 05, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | [6946ffb375](https://linux-hardware.org/?probe=6946ffb375) | Jun 03, 2021 |
| Dell          | Latitude 9520               | [10a4c770cf](https://linux-hardware.org/?probe=10a4c770cf) | Jun 02, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | [d8507e3c64](https://linux-hardware.org/?probe=d8507e3c64) | Jun 01, 2021 |
| Apple         | MacBookPro12,1              | [f7f5736b13](https://linux-hardware.org/?probe=f7f5736b13) | Jun 01, 2021 |
| HP            | EliteBook Revolve 810       | [24758ed5b3](https://linux-hardware.org/?probe=24758ed5b3) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cad013a6a5](https://linux-hardware.org/?probe=cad013a6a5) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [af407b12e2](https://linux-hardware.org/?probe=af407b12e2) | May 29, 2021 |
| HP            | EliteBook Folio 9470m       | [8c36612ff4](https://linux-hardware.org/?probe=8c36612ff4) | May 26, 2021 |
| HP            | ZBook 17 G2                 | [5e10971a64](https://linux-hardware.org/?probe=5e10971a64) | May 25, 2021 |
| Apple         | MacBookPro6,1               | [a0012821b7](https://linux-hardware.org/?probe=a0012821b7) | May 25, 2021 |
| Dell          | Latitude D520               | [7a817a0426](https://linux-hardware.org/?probe=7a817a0426) | May 25, 2021 |
| HP            | EliteBook Revolve 810 G3    | [e0068ae9b7](https://linux-hardware.org/?probe=e0068ae9b7) | May 23, 2021 |
| PC Special... | N150CU                      | [eebe654729](https://linux-hardware.org/?probe=eebe654729) | May 22, 2021 |
| PC Special... | N150CU                      | [99d75e799f](https://linux-hardware.org/?probe=99d75e799f) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [d5ea76578b](https://linux-hardware.org/?probe=d5ea76578b) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [0ccd96a39e](https://linux-hardware.org/?probe=0ccd96a39e) | May 21, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [828f345230](https://linux-hardware.org/?probe=828f345230) | May 19, 2021 |
| Dell          | Precision 5540              | [91e4aff19e](https://linux-hardware.org/?probe=91e4aff19e) | May 17, 2021 |
| Dell          | Latitude 3350               | [f4e6b7cf7f](https://linux-hardware.org/?probe=f4e6b7cf7f) | May 15, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ae6af1c7e1](https://linux-hardware.org/?probe=ae6af1c7e1) | May 14, 2021 |
| HP            | EliteBook 850 G3            | [cb589a4d2c](https://linux-hardware.org/?probe=cb589a4d2c) | May 14, 2021 |
| HP            | EliteBook 850 G3            | [00a23f1149](https://linux-hardware.org/?probe=00a23f1149) | May 14, 2021 |
| Dell          | Latitude 3350               | [bb64b2df5c](https://linux-hardware.org/?probe=bb64b2df5c) | May 13, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [461ae5a890](https://linux-hardware.org/?probe=461ae5a890) | May 08, 2021 |
| HP            | EliteBook 850 G3            | [85a71e335a](https://linux-hardware.org/?probe=85a71e335a) | May 06, 2021 |
| Dell          | XPS 13 9310                 | [5103d9a329](https://linux-hardware.org/?probe=5103d9a329) | May 06, 2021 |
| Dell          | XPS 13 9310                 | [951fb73d61](https://linux-hardware.org/?probe=951fb73d61) | May 06, 2021 |
| Apple         | MacBookPro14,1              | [f1b3020464](https://linux-hardware.org/?probe=f1b3020464) | May 03, 2021 |
| ASUSTek       | X502CA                      | [6763e02e82](https://linux-hardware.org/?probe=6763e02e82) | Apr 30, 2021 |
| Dell          | XPS 17 9700                 | [02dae8d8ba](https://linux-hardware.org/?probe=02dae8d8ba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | [0d0db8039c](https://linux-hardware.org/?probe=0d0db8039c) | Apr 24, 2021 |
| HP            | Compaq 6730s                | [31fa38668e](https://linux-hardware.org/?probe=31fa38668e) | Apr 23, 2021 |
| HP            | Compaq 6730s                | [ad60afcbe6](https://linux-hardware.org/?probe=ad60afcbe6) | Apr 23, 2021 |
| HP            | ProBook 430 G2              | [03a0b4cf9d](https://linux-hardware.org/?probe=03a0b4cf9d) | Apr 22, 2021 |
| HP            | ProBook 430 G2              | [9f9065affa](https://linux-hardware.org/?probe=9f9065affa) | Apr 22, 2021 |
| HP            | Pavilion dv8000 (EW858EA... | [b64833b0b1](https://linux-hardware.org/?probe=b64833b0b1) | Apr 21, 2021 |
| HP            | Pavilion dv8000 (EW858EA... | [e378a38500](https://linux-hardware.org/?probe=e378a38500) | Apr 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9f3189e59c](https://linux-hardware.org/?probe=9f3189e59c) | Apr 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [644309ff4c](https://linux-hardware.org/?probe=644309ff4c) | Apr 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2e1606428e](https://linux-hardware.org/?probe=2e1606428e) | Apr 19, 2021 |
| Dell          | XPS 13 9343                 | [fd2c114081](https://linux-hardware.org/?probe=fd2c114081) | Apr 19, 2021 |
| Dell          | XPS 13 9343                 | [2d99520074](https://linux-hardware.org/?probe=2d99520074) | Apr 19, 2021 |
| Dell          | XPS 17 9700                 | [84387a75f7](https://linux-hardware.org/?probe=84387a75f7) | Apr 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [5d66639b00](https://linux-hardware.org/?probe=5d66639b00) | Apr 17, 2021 |
| Toshiba       | Satellite A300              | [37b42247f5](https://linux-hardware.org/?probe=37b42247f5) | Apr 17, 2021 |
| Toshiba       | Satellite A300              | [d0c0ba115d](https://linux-hardware.org/?probe=d0c0ba115d) | Apr 17, 2021 |
| Dell          | Latitude D520               | [4e8b58ab28](https://linux-hardware.org/?probe=4e8b58ab28) | Apr 16, 2021 |
| ASUSTek       | N53SN                       | [97b4a56f7d](https://linux-hardware.org/?probe=97b4a56f7d) | Apr 16, 2021 |
| Dell          | Precision 3551              | [4e9b5b097e](https://linux-hardware.org/?probe=4e9b5b097e) | Apr 15, 2021 |
| Dell          | Precision 5540              | [a171f512e1](https://linux-hardware.org/?probe=a171f512e1) | Apr 14, 2021 |
| ASUSTek       | G751JY                      | [914c959acf](https://linux-hardware.org/?probe=914c959acf) | Apr 13, 2021 |
| Acer          | Aspire 5560                 | [bc4d7942f2](https://linux-hardware.org/?probe=bc4d7942f2) | Apr 13, 2021 |
| Acer          | Aspire 5560                 | [c01ef90ff1](https://linux-hardware.org/?probe=c01ef90ff1) | Apr 13, 2021 |
| Lenovo        | ThinkPad X390 20Q00056MX    | [377be16b54](https://linux-hardware.org/?probe=377be16b54) | Apr 13, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [8ed94ed92f](https://linux-hardware.org/?probe=8ed94ed92f) | Apr 12, 2021 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | [6a307c820d](https://linux-hardware.org/?probe=6a307c820d) | Apr 12, 2021 |
| Dell          | XPS 15 9560                 | [6dd46ebb68](https://linux-hardware.org/?probe=6dd46ebb68) | Apr 11, 2021 |
| Dell          | Latitude 3350               | [347c1e4246](https://linux-hardware.org/?probe=347c1e4246) | Apr 11, 2021 |
| Lenovo        | ThinkPad W541 20EF000UMN    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| Dell          | Precision 7740              | [e00242182c](https://linux-hardware.org/?probe=e00242182c) | Apr 10, 2021 |
| Dell          | Precision 7740              | [5b18086d86](https://linux-hardware.org/?probe=5b18086d86) | Apr 10, 2021 |
| ASUSTek       | 1008HA                      | [efa68e1607](https://linux-hardware.org/?probe=efa68e1607) | Apr 09, 2021 |
| Apple         | MacBookPro9,2               | [8fe0fefb60](https://linux-hardware.org/?probe=8fe0fefb60) | Apr 09, 2021 |
| HP            | EliteBook 2740p             | [6604ebcf44](https://linux-hardware.org/?probe=6604ebcf44) | Apr 09, 2021 |
| HP            | Compaq 6730b (NN204ET#AK... | [3d9460ecd7](https://linux-hardware.org/?probe=3d9460ecd7) | Apr 08, 2021 |
| Lenovo        | B575e 36852EG               | [494789235b](https://linux-hardware.org/?probe=494789235b) | Apr 08, 2021 |
| Acer          | Aspire VN7-793G             | [881e9bb0dd](https://linux-hardware.org/?probe=881e9bb0dd) | Apr 06, 2021 |
| Acer          | Aspire VN7-793G             | [cd805ae4e6](https://linux-hardware.org/?probe=cd805ae4e6) | Apr 06, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [9c7afa6f8c](https://linux-hardware.org/?probe=9c7afa6f8c) | Apr 06, 2021 |
| ASUSTek       | 1008HA                      | [8819e810d5](https://linux-hardware.org/?probe=8819e810d5) | Apr 05, 2021 |
| HP            | EliteBook 840 G3            | [9bb8d87d34](https://linux-hardware.org/?probe=9bb8d87d34) | Apr 05, 2021 |
| HP            | EliteBook 840 G3            | [1e04362858](https://linux-hardware.org/?probe=1e04362858) | Apr 05, 2021 |
| HP            | EliteBook 840 G3            | [4c92681db0](https://linux-hardware.org/?probe=4c92681db0) | Apr 05, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [6a799a77de](https://linux-hardware.org/?probe=6a799a77de) | Apr 05, 2021 |
| Dell          | Latitude E6430              | [cef48a7c98](https://linux-hardware.org/?probe=cef48a7c98) | Apr 05, 2021 |
| Lenovo        | ThinkPad 11e 3rd Gen 20G... | [d8320bacb4](https://linux-hardware.org/?probe=d8320bacb4) | Apr 05, 2021 |
| Dell          | Latitude E6430              | [8e76a74a21](https://linux-hardware.org/?probe=8e76a74a21) | Apr 04, 2021 |
| ASUSTek       | 1008HA                      | [1045f8543a](https://linux-hardware.org/?probe=1045f8543a) | Apr 04, 2021 |
| Lenovo        | ThinkPad E580 20KS001QMX    | [28b80e551f](https://linux-hardware.org/?probe=28b80e551f) | Apr 04, 2021 |
| HP            | Laptop 17-ca1xxx            | [e21ac181a5](https://linux-hardware.org/?probe=e21ac181a5) | Apr 03, 2021 |
| Dell          | Precision 7540              | [9ad15db73f](https://linux-hardware.org/?probe=9ad15db73f) | Apr 02, 2021 |
| Apple         | MacBookPro8,1               | [6632391038](https://linux-hardware.org/?probe=6632391038) | Apr 02, 2021 |
| Dell          | XPS 15 9560                 | [dd4081dc68](https://linux-hardware.org/?probe=dd4081dc68) | Apr 02, 2021 |
| ASUSTek       | U32U                        | [2842f61fc9](https://linux-hardware.org/?probe=2842f61fc9) | Apr 02, 2021 |
| PC Special... | N150CU                      | [f0729cc9bf](https://linux-hardware.org/?probe=f0729cc9bf) | Apr 01, 2021 |
| PC Special... | N150CU                      | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| Dell          | Latitude 3350               | [9e3b1f256c](https://linux-hardware.org/?probe=9e3b1f256c) | Apr 01, 2021 |
| Lenovo        | ThinkPad X240 20AMS1WW0X    | [1f98cf2913](https://linux-hardware.org/?probe=1f98cf2913) | Mar 31, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [286287736b](https://linux-hardware.org/?probe=286287736b) | Mar 31, 2021 |
| Gigabyte      | AERO 15-SA                  | [26957c118d](https://linux-hardware.org/?probe=26957c118d) | Mar 30, 2021 |
| Dell          | Latitude E6430              | [5989458f51](https://linux-hardware.org/?probe=5989458f51) | Mar 29, 2021 |
| HP            | ProBook 4540s               | [6999b29045](https://linux-hardware.org/?probe=6999b29045) | Mar 29, 2021 |
| HP            | ProBook 440 G5              | [6c5ee38371](https://linux-hardware.org/?probe=6c5ee38371) | Mar 27, 2021 |
| Acer          | Aspire E5-575G              | [d96f9a5cd5](https://linux-hardware.org/?probe=d96f9a5cd5) | Mar 27, 2021 |
| Lenovo        | ThinkPad T430s 2356DH2      | [86d756fb89](https://linux-hardware.org/?probe=86d756fb89) | Mar 27, 2021 |
| HP            | ProBook 440 G5              | [46ffef3efa](https://linux-hardware.org/?probe=46ffef3efa) | Mar 27, 2021 |
| Dell          | XPS 15 7590                 | [6727afc25e](https://linux-hardware.org/?probe=6727afc25e) | Mar 25, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [57162c4f3e](https://linux-hardware.org/?probe=57162c4f3e) | Mar 24, 2021 |
| Lenovo        | ThinkPad T420 4180AZ5       | [4b39173927](https://linux-hardware.org/?probe=4b39173927) | Mar 23, 2021 |
| HP            | ProBook 4540s               | [3eebedc4c6](https://linux-hardware.org/?probe=3eebedc4c6) | Mar 23, 2021 |
| HP            | ProBook 4540s               | [96a4aad39a](https://linux-hardware.org/?probe=96a4aad39a) | Mar 23, 2021 |
| HP            | Laptop 15-da1xxx            | [3a2dc8930d](https://linux-hardware.org/?probe=3a2dc8930d) | Mar 22, 2021 |
| Dell          | Precision 7540              | [b5273482f4](https://linux-hardware.org/?probe=b5273482f4) | Mar 21, 2021 |
| Dell          | Vostro 15-3568              | [2c8acbf86c](https://linux-hardware.org/?probe=2c8acbf86c) | Mar 21, 2021 |
| ASUSTek       | X555LD                      | [90646a2169](https://linux-hardware.org/?probe=90646a2169) | Mar 20, 2021 |
| Acer          | Aspire 5742G                | [da8880b543](https://linux-hardware.org/?probe=da8880b543) | Mar 19, 2021 |
| Acer          | Aspire 5742G                | [047a34bb2c](https://linux-hardware.org/?probe=047a34bb2c) | Mar 19, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f991500c35](https://linux-hardware.org/?probe=f991500c35) | Mar 18, 2021 |
| Dell          | Latitude E4310              | [edbe42639c](https://linux-hardware.org/?probe=edbe42639c) | Mar 17, 2021 |
| HP            | EliteBook Folio 9470m       | [30efdef045](https://linux-hardware.org/?probe=30efdef045) | Mar 15, 2021 |
| HP            | EliteBook 2570p             | [3bf2664982](https://linux-hardware.org/?probe=3bf2664982) | Mar 14, 2021 |
| ASUSTek       | X580VD                      | [968d9a1d18](https://linux-hardware.org/?probe=968d9a1d18) | Mar 14, 2021 |
| ASUSTek       | X580VD                      | [e10f767f8d](https://linux-hardware.org/?probe=e10f767f8d) | Mar 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [44775f7ea2](https://linux-hardware.org/?probe=44775f7ea2) | Mar 12, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [5d7090421a](https://linux-hardware.org/?probe=5d7090421a) | Mar 12, 2021 |
| MSI           | GX60 1AC                    | [774db4f685](https://linux-hardware.org/?probe=774db4f685) | Mar 12, 2021 |
| HP            | EliteBook 840 G2            | [e90e4463c7](https://linux-hardware.org/?probe=e90e4463c7) | Mar 11, 2021 |
| HP            | Compaq 8710w                | [2b1ffee1d7](https://linux-hardware.org/?probe=2b1ffee1d7) | Mar 11, 2021 |
| Acer          | AOD255E                     | [cacd668025](https://linux-hardware.org/?probe=cacd668025) | Mar 10, 2021 |
| PC Special... | N150CU                      | [50a23abcf2](https://linux-hardware.org/?probe=50a23abcf2) | Mar 09, 2021 |
| Dell          | Precision 5540              | [e3aca0cdf9](https://linux-hardware.org/?probe=e3aca0cdf9) | Mar 09, 2021 |
| Dell          | Latitude E7250              | [76aeabfc6d](https://linux-hardware.org/?probe=76aeabfc6d) | Mar 07, 2021 |
| Dell          | XPS 13 9310                 | [5754ce9311](https://linux-hardware.org/?probe=5754ce9311) | Mar 02, 2021 |
| HP            | Laptop 17-ca1xxx            | [a8a82ba1b9](https://linux-hardware.org/?probe=a8a82ba1b9) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK U745               | [2acf51105b](https://linux-hardware.org/?probe=2acf51105b) | Feb 28, 2021 |
| Intel         | SLIMBOOK                    | [36bbd7056a](https://linux-hardware.org/?probe=36bbd7056a) | Feb 28, 2021 |
| Dell          | Latitude E7450              | [dfb4275179](https://linux-hardware.org/?probe=dfb4275179) | Feb 28, 2021 |
| HP            | EliteBook Folio 9470m       | [b9cfaac7a6](https://linux-hardware.org/?probe=b9cfaac7a6) | Feb 27, 2021 |
| ASUSTek       | X202EV                      | [1c1369ff15](https://linux-hardware.org/?probe=1c1369ff15) | Feb 25, 2021 |
| HP            | EliteBook 830 G5            | [65135f4810](https://linux-hardware.org/?probe=65135f4810) | Feb 24, 2021 |
| HP            | EliteBook 820 G2            | [50dcf0521d](https://linux-hardware.org/?probe=50dcf0521d) | Feb 24, 2021 |
| Lenovo        | ThinkPad L590 20Q8S75F01    | [ae827c1e6b](https://linux-hardware.org/?probe=ae827c1e6b) | Feb 24, 2021 |
| Dell          | Precision M4800             | [744b7bc3a5](https://linux-hardware.org/?probe=744b7bc3a5) | Feb 23, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [a05ca7a665](https://linux-hardware.org/?probe=a05ca7a665) | Feb 23, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [2009ef0f7f](https://linux-hardware.org/?probe=2009ef0f7f) | Feb 23, 2021 |
| HP            | EliteBook 2570p             | [f3e1294a65](https://linux-hardware.org/?probe=f3e1294a65) | Feb 23, 2021 |
| Dell          | Latitude E6540              | [550d35b65b](https://linux-hardware.org/?probe=550d35b65b) | Feb 20, 2021 |
| HP            | ProBook 4330s               | [01954b26a9](https://linux-hardware.org/?probe=01954b26a9) | Feb 20, 2021 |
| ASUSTek       | UX430UQ                     | [3dce65d104](https://linux-hardware.org/?probe=3dce65d104) | Feb 19, 2021 |
| ASUSTek       | UX430UQ                     | [11cebb071c](https://linux-hardware.org/?probe=11cebb071c) | Feb 19, 2021 |
| Sony          | VPCF23C5E                   | [fdfa46f36e](https://linux-hardware.org/?probe=fdfa46f36e) | Feb 19, 2021 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [fe2c72978e](https://linux-hardware.org/?probe=fe2c72978e) | Feb 19, 2021 |
| Lenovo        | ThinkPad L590 20Q8S75F01    | [39d098054a](https://linux-hardware.org/?probe=39d098054a) | Feb 18, 2021 |
| Dell          | Vostro 3500                 | [bd2b4fae3a](https://linux-hardware.org/?probe=bd2b4fae3a) | Feb 18, 2021 |
| Dell          | Latitude 5480               | [41472dbe02](https://linux-hardware.org/?probe=41472dbe02) | Feb 18, 2021 |
| HP            | Compaq 6510b (GB867ET#AK... | [c9c18dfdeb](https://linux-hardware.org/?probe=c9c18dfdeb) | Feb 16, 2021 |
| Acer          | Aspire 5750G                | [84855d9ab6](https://linux-hardware.org/?probe=84855d9ab6) | Feb 14, 2021 |
| BOX           | W54_W94_W955TU,-T,-C        | [45730a0879](https://linux-hardware.org/?probe=45730a0879) | Feb 14, 2021 |
| HP            | Pavilion Notebook           | [065510eb37](https://linux-hardware.org/?probe=065510eb37) | Feb 13, 2021 |
| Lenovo        | ThinkPad Edge E530c 3366... | [e34430353c](https://linux-hardware.org/?probe=e34430353c) | Feb 13, 2021 |
| ASUSTek       | K70IO                       | [4912792c07](https://linux-hardware.org/?probe=4912792c07) | Feb 13, 2021 |
| PC Special... | N150CU                      | [9400902b39](https://linux-hardware.org/?probe=9400902b39) | Feb 13, 2021 |
| HP            | ProBook 640 G1              | [3b37587b81](https://linux-hardware.org/?probe=3b37587b81) | Feb 12, 2021 |
| HP            | ZBook 15                    | [dc1d23b1c6](https://linux-hardware.org/?probe=dc1d23b1c6) | Feb 12, 2021 |
| Acer          | Aspire 5750G                | [4d8c753a43](https://linux-hardware.org/?probe=4d8c753a43) | Feb 09, 2021 |
| HP            | ENVY Notebook               | [c951e2abbd](https://linux-hardware.org/?probe=c951e2abbd) | Feb 07, 2021 |
| Notebook      | N2x0WU                      | [e660e0f0da](https://linux-hardware.org/?probe=e660e0f0da) | Feb 05, 2021 |
| ASUSTek       | G75VW                       | [9fc5da433d](https://linux-hardware.org/?probe=9fc5da433d) | Feb 05, 2021 |
| ASUSTek       | ZenBook 13 UX331UAL         | [918139e56e](https://linux-hardware.org/?probe=918139e56e) | Feb 05, 2021 |
| Lenovo        | ThinkPad E520 11438NG       | [3dcd713cd1](https://linux-hardware.org/?probe=3dcd713cd1) | Feb 05, 2021 |
| Dell          | XPS 13 9310                 | [948271ba61](https://linux-hardware.org/?probe=948271ba61) | Feb 05, 2021 |
| ASUSTek       | UX430UAR                    | [65e796cdaf](https://linux-hardware.org/?probe=65e796cdaf) | Feb 04, 2021 |
| HP            | EliteBook 8440p             | [024180fc49](https://linux-hardware.org/?probe=024180fc49) | Feb 03, 2021 |
| System76      | Galago UltraPro             | [ba1c44690a](https://linux-hardware.org/?probe=ba1c44690a) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e746534229](https://linux-hardware.org/?probe=e746534229) | Feb 01, 2021 |
| HP            | EliteBook 8440p             | [32ea31202d](https://linux-hardware.org/?probe=32ea31202d) | Feb 01, 2021 |
| Dell          | Precision 5550              | [61de611018](https://linux-hardware.org/?probe=61de611018) | Jan 29, 2021 |
| Dell          | Precision 7720              | [c99e4945f6](https://linux-hardware.org/?probe=c99e4945f6) | Jan 29, 2021 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | [19aa307625](https://linux-hardware.org/?probe=19aa307625) | Jan 29, 2021 |
| Notebook      | N350TW                      | [8f873c01cb](https://linux-hardware.org/?probe=8f873c01cb) | Jan 28, 2021 |
| Apple         | MacBookAir7,2               | [cf6599a35b](https://linux-hardware.org/?probe=cf6599a35b) | Jan 27, 2021 |
| ASUSTek       | X550LB                      | [427d6af239](https://linux-hardware.org/?probe=427d6af239) | Jan 25, 2021 |
| ASUSTek       | X550LB                      | [a6a84e8eb2](https://linux-hardware.org/?probe=a6a84e8eb2) | Jan 24, 2021 |
| HP            | EliteBook 8570p             | [a2536bd6fe](https://linux-hardware.org/?probe=a2536bd6fe) | Jan 23, 2021 |
| ASUSTek       | TP300LA                     | [890339ddee](https://linux-hardware.org/?probe=890339ddee) | Jan 22, 2021 |
| Toshiba       | Satellite Pro C50-A-1EK     | [b2b20ad037](https://linux-hardware.org/?probe=b2b20ad037) | Jan 21, 2021 |
| Toshiba       | Satellite Pro C50-A-1EK     | [8718991f34](https://linux-hardware.org/?probe=8718991f34) | Jan 21, 2021 |
| Toshiba       | Satellite Pro C50-A-1EK     | [67a92e99d9](https://linux-hardware.org/?probe=67a92e99d9) | Jan 21, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [fa99318483](https://linux-hardware.org/?probe=fa99318483) | Jan 21, 2021 |
| Acer          | Aspire V5-561G              | [41a988bc1c](https://linux-hardware.org/?probe=41a988bc1c) | Jan 17, 2021 |
| HP            | EliteBook 2560p             | [92cd0842ee](https://linux-hardware.org/?probe=92cd0842ee) | Jan 15, 2021 |
| Dell          | Vostro 3500                 | [efa4546342](https://linux-hardware.org/?probe=efa4546342) | Jan 14, 2021 |
| ASUSTek       | N53SN                       | [a0fd8f8b91](https://linux-hardware.org/?probe=a0fd8f8b91) | Jan 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [929b0edb33](https://linux-hardware.org/?probe=929b0edb33) | Jan 11, 2021 |
| HP            | EliteBook 2570p             | [731a3aef2a](https://linux-hardware.org/?probe=731a3aef2a) | Jan 10, 2021 |
| Lenovo        | ThinkPad T460 20FN004CMX    | [0f6a89ef2c](https://linux-hardware.org/?probe=0f6a89ef2c) | Jan 10, 2021 |
| Alienware     | 13 R3                       | [d3e331e671](https://linux-hardware.org/?probe=d3e331e671) | Jan 10, 2021 |
| ASUSTek       | TP300LA                     | [67fa6528dc](https://linux-hardware.org/?probe=67fa6528dc) | Jan 09, 2021 |
| HP            | EliteBook 2570p             | [68910248cd](https://linux-hardware.org/?probe=68910248cd) | Jan 09, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [afdde38feb](https://linux-hardware.org/?probe=afdde38feb) | Jan 08, 2021 |
| Acer          | Aspire V3-571G              | [ae420c0bca](https://linux-hardware.org/?probe=ae420c0bca) | Jan 08, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [55f711c5eb](https://linux-hardware.org/?probe=55f711c5eb) | Jan 08, 2021 |
| Acer          | Aspire 5750G                | [a448a76b2e](https://linux-hardware.org/?probe=a448a76b2e) | Jan 06, 2021 |
| Dell          | Vostro 3559                 | [aa443d9d50](https://linux-hardware.org/?probe=aa443d9d50) | Jan 05, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [ea65a42d36](https://linux-hardware.org/?probe=ea65a42d36) | Jan 05, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [bb226d61ff](https://linux-hardware.org/?probe=bb226d61ff) | Jan 05, 2021 |
| Dell          | Precision M6300             | [5b6ca806fb](https://linux-hardware.org/?probe=5b6ca806fb) | Jan 04, 2021 |
| Notebook      | N350TW                      | [5d6a245e70](https://linux-hardware.org/?probe=5d6a245e70) | Jan 03, 2021 |
| Star Labs     | Lite                        | [02fa9d26a2](https://linux-hardware.org/?probe=02fa9d26a2) | Jan 03, 2021 |
| Dell          | Latitude E4300              | [272cc1ce98](https://linux-hardware.org/?probe=272cc1ce98) | Jan 01, 2021 |
| Star Labs     | Lite                        | [64ec49adf7](https://linux-hardware.org/?probe=64ec49adf7) | Jan 01, 2021 |
| Star Labs     | Lite                        | [8a83fcbe27](https://linux-hardware.org/?probe=8a83fcbe27) | Jan 01, 2021 |
| ASUSTek       | X541UA                      | [7c018503fa](https://linux-hardware.org/?probe=7c018503fa) | Jan 01, 2021 |
| ASUSTek       | X541UA                      | [88a33cb3b7](https://linux-hardware.org/?probe=88a33cb3b7) | Jan 01, 2021 |
| Dell          | Latitude D410               | [26b1a84efa](https://linux-hardware.org/?probe=26b1a84efa) | Dec 31, 2020 |
| Dell          | Latitude D410               | [ef6b6f5048](https://linux-hardware.org/?probe=ef6b6f5048) | Dec 31, 2020 |
| HP            | Compaq nc6400 (RH478EA#A... | [d7fd1a7a8d](https://linux-hardware.org/?probe=d7fd1a7a8d) | Dec 31, 2020 |
| Dell          | Latitude D410               | [6d20834f6e](https://linux-hardware.org/?probe=6d20834f6e) | Dec 30, 2020 |
| Dell          | Latitude D410               | [341284656b](https://linux-hardware.org/?probe=341284656b) | Dec 29, 2020 |
| Apple         | MacBookPro12,1              | [e60ff2c9ad](https://linux-hardware.org/?probe=e60ff2c9ad) | Dec 28, 2020 |
| HP            | Compaq 6510b (GB867ET#AK... | [65279b81c8](https://linux-hardware.org/?probe=65279b81c8) | Dec 28, 2020 |
| HP            | 255 G2                      | [c0f14d1c9f](https://linux-hardware.org/?probe=c0f14d1c9f) | Dec 28, 2020 |
| HP            | ProBook 4330s               | [d6c9d261b3](https://linux-hardware.org/?probe=d6c9d261b3) | Dec 28, 2020 |
| EUROCOM       | Tornado F5                  | [f38086ba01](https://linux-hardware.org/?probe=f38086ba01) | Dec 27, 2020 |
| Packard Be... | EasyNote TK85               | [5fd111e9bf](https://linux-hardware.org/?probe=5fd111e9bf) | Dec 27, 2020 |
| Packard Be... | EasyNote TK85               | [cc2c8a071d](https://linux-hardware.org/?probe=cc2c8a071d) | Dec 26, 2020 |
| ASUSTek       | N56DY                       | [4ff3c1bbac](https://linux-hardware.org/?probe=4ff3c1bbac) | Dec 25, 2020 |
| ASUSTek       | N56DY                       | [5f0b1bccdd](https://linux-hardware.org/?probe=5f0b1bccdd) | Dec 25, 2020 |
| EUROCOM       | Tornado F5                  | [31028ce28e](https://linux-hardware.org/?probe=31028ce28e) | Dec 25, 2020 |
| Samsung       | RC420/RC520/RC720           | [2621a1f2f7](https://linux-hardware.org/?probe=2621a1f2f7) | Dec 24, 2020 |
| PC Special... | N150CU                      | [91fa48cbba](https://linux-hardware.org/?probe=91fa48cbba) | Dec 23, 2020 |
| HP            | ProBook 4330s               | [c49ab6d1cd](https://linux-hardware.org/?probe=c49ab6d1cd) | Dec 23, 2020 |
| HP            | ProBook 4330s               | [3faa3f96b5](https://linux-hardware.org/?probe=3faa3f96b5) | Dec 23, 2020 |
| HP            | ENVY Spectre XT Ultraboo... | [fb90fb35ab](https://linux-hardware.org/?probe=fb90fb35ab) | Dec 21, 2020 |
| HP            | EliteBook Revolve 810       | [b6b29c8237](https://linux-hardware.org/?probe=b6b29c8237) | Dec 17, 2020 |
| ASUSTek       | UX430UAR                    | [27e6c318cf](https://linux-hardware.org/?probe=27e6c318cf) | Dec 17, 2020 |
| Dell          | Latitude E6430              | [f579dcf588](https://linux-hardware.org/?probe=f579dcf588) | Dec 16, 2020 |
| MSI           | GE70 2OC\2OE                | [60dea2620f](https://linux-hardware.org/?probe=60dea2620f) | Dec 15, 2020 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [435ab3dc8c](https://linux-hardware.org/?probe=435ab3dc8c) | Dec 15, 2020 |
| Acer          | Aspire V3-571               | [7d0c6ab7b1](https://linux-hardware.org/?probe=7d0c6ab7b1) | Dec 14, 2020 |
| ASUSTek       | UL50VT                      | [693b14d7bc](https://linux-hardware.org/?probe=693b14d7bc) | Dec 14, 2020 |
| Sony          | VGN-FZ31M                   | [a66ff4c9f1](https://linux-hardware.org/?probe=a66ff4c9f1) | Dec 13, 2020 |
| Lenovo        | V14-IWL 81YB                | [5b1407d6e4](https://linux-hardware.org/?probe=5b1407d6e4) | Dec 11, 2020 |
| Dell          | XPS 17 9700                 | [c86faa6047](https://linux-hardware.org/?probe=c86faa6047) | Dec 11, 2020 |
| Lenovo        | ThinkPad X61s 76693JG       | [037685f512](https://linux-hardware.org/?probe=037685f512) | Dec 10, 2020 |
| Lenovo        | ThinkPad P51 20HH002WMX     | [8eec8ac7f3](https://linux-hardware.org/?probe=8eec8ac7f3) | Dec 09, 2020 |
| Sony          | SVF1521A6EW                 | [b895f1d731](https://linux-hardware.org/?probe=b895f1d731) | Dec 08, 2020 |
| HP            | ProBook 6450b               | [e0290fc13f](https://linux-hardware.org/?probe=e0290fc13f) | Dec 07, 2020 |
| HP            | Pavilion dv9700             | [c2e755bbd2](https://linux-hardware.org/?probe=c2e755bbd2) | Dec 06, 2020 |
| HP            | Pavilion dv7                | [aebd3290e0](https://linux-hardware.org/?probe=aebd3290e0) | Dec 05, 2020 |
| Lenovo        | Y50-70 20378                | [e5069e0526](https://linux-hardware.org/?probe=e5069e0526) | Dec 02, 2020 |
| Dell          | Precision 5540              | [e580d3c815](https://linux-hardware.org/?probe=e580d3c815) | Dec 01, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [c176e7e603](https://linux-hardware.org/?probe=c176e7e603) | Nov 29, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [e4e600f1ed](https://linux-hardware.org/?probe=e4e600f1ed) | Nov 29, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [8b7bafb647](https://linux-hardware.org/?probe=8b7bafb647) | Nov 28, 2020 |
| Packard Be... | EasyNote TE69HW             | [877c539b22](https://linux-hardware.org/?probe=877c539b22) | Nov 27, 2020 |
| Dell          | Latitude E7440              | [7b84406eb7](https://linux-hardware.org/?probe=7b84406eb7) | Nov 25, 2020 |
| Dell          | XPS 15 7590                 | [bfe0a182c7](https://linux-hardware.org/?probe=bfe0a182c7) | Nov 25, 2020 |
| Toshiba       | Satellite L40               | [162b3dae3c](https://linux-hardware.org/?probe=162b3dae3c) | Nov 24, 2020 |
| Toshiba       | Satellite L40               | [65c7d13202](https://linux-hardware.org/?probe=65c7d13202) | Nov 24, 2020 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | [13677ed02e](https://linux-hardware.org/?probe=13677ed02e) | Nov 21, 2020 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | [e77da357d5](https://linux-hardware.org/?probe=e77da357d5) | Nov 19, 2020 |
| Dell          | XPS 15 9500                 | [a550f45f26](https://linux-hardware.org/?probe=a550f45f26) | Nov 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b1b685d6f2](https://linux-hardware.org/?probe=b1b685d6f2) | Nov 18, 2020 |
| Dell          | XPS 13 9310                 | [1e89c57bd3](https://linux-hardware.org/?probe=1e89c57bd3) | Nov 16, 2020 |
| HP            | ProBook 6570b               | [9d02d072b5](https://linux-hardware.org/?probe=9d02d072b5) | Nov 16, 2020 |
| Lenovo        | ThinkPad X220 4286CTO       | [1279053cad](https://linux-hardware.org/?probe=1279053cad) | Nov 15, 2020 |
| HP            | EliteBook 840 G6            | [6a99d1db55](https://linux-hardware.org/?probe=6a99d1db55) | Nov 15, 2020 |
| Dell          | Latitude E6320              | [61bd7b89c9](https://linux-hardware.org/?probe=61bd7b89c9) | Nov 14, 2020 |
| HP            | EliteBook Revolve 810       | [29b4740f0e](https://linux-hardware.org/?probe=29b4740f0e) | Nov 14, 2020 |
| HP            | EliteBook Revolve 810       | [fc46156f6d](https://linux-hardware.org/?probe=fc46156f6d) | Nov 14, 2020 |
| MSI           | GL62 6QD                    | [aae5c5e2a6](https://linux-hardware.org/?probe=aae5c5e2a6) | Nov 13, 2020 |
| Dell          | XPS 13 9310                 | [80343cf550](https://linux-hardware.org/?probe=80343cf550) | Nov 11, 2020 |
| Dell          | Latitude E6320              | [0b28ed3b69](https://linux-hardware.org/?probe=0b28ed3b69) | Nov 11, 2020 |
| Acer          | Aspire E5-521               | [65830eafc6](https://linux-hardware.org/?probe=65830eafc6) | Nov 10, 2020 |
| MSI           | GL73 8RC                    | [44f82bfc01](https://linux-hardware.org/?probe=44f82bfc01) | Nov 09, 2020 |
| Lenovo        | G560 0679                   | [b3a54d7dd5](https://linux-hardware.org/?probe=b3a54d7dd5) | Nov 09, 2020 |
| Lenovo        | V110-14IAP 80TF             | [62946a2f8c](https://linux-hardware.org/?probe=62946a2f8c) | Nov 09, 2020 |
| Dell          | Latitude E6320              | [0157c2fcb3](https://linux-hardware.org/?probe=0157c2fcb3) | Nov 08, 2020 |
| Lenovo        | ThinkPad L440 20ASS34900    | [0320af5232](https://linux-hardware.org/?probe=0320af5232) | Nov 08, 2020 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [fbb029244c](https://linux-hardware.org/?probe=fbb029244c) | Nov 07, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [91f7303817](https://linux-hardware.org/?probe=91f7303817) | Nov 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [543c444fdf](https://linux-hardware.org/?probe=543c444fdf) | Nov 05, 2020 |
| Dell          | Latitude 3350               | [a8f5719a0a](https://linux-hardware.org/?probe=a8f5719a0a) | Nov 05, 2020 |
| Acer          | Aspire VN7-593G             | [3892565ed3](https://linux-hardware.org/?probe=3892565ed3) | Nov 04, 2020 |
| Dell          | Latitude 3350               | [65f4e655fc](https://linux-hardware.org/?probe=65f4e655fc) | Nov 03, 2020 |
| MSI           | GP60 2PE                    | [826e175164](https://linux-hardware.org/?probe=826e175164) | Nov 01, 2020 |
| MSI           | GP60 2PE                    | [ea487475af](https://linux-hardware.org/?probe=ea487475af) | Oct 31, 2020 |
| MSI           | GL62 6QD                    | [6768f07648](https://linux-hardware.org/?probe=6768f07648) | Oct 28, 2020 |
| Dell          | Latitude E7470              | [890fea6488](https://linux-hardware.org/?probe=890fea6488) | Oct 27, 2020 |
| Fujitsu Si... | AMILO Notebook Pa 3553      | [68f95ea08d](https://linux-hardware.org/?probe=68f95ea08d) | Oct 25, 2020 |
| Fujitsu Si... | AMILO Notebook Pa 3553      | [2487ba73b1](https://linux-hardware.org/?probe=2487ba73b1) | Oct 25, 2020 |
| Lenovo        | ThinkPad A485 20MU000DMX    | [3d919ab14e](https://linux-hardware.org/?probe=3d919ab14e) | Oct 23, 2020 |
| Acer          | Nitro AN515-52              | [fd1a6f5055](https://linux-hardware.org/?probe=fd1a6f5055) | Oct 22, 2020 |
| HP            | ZBook 15                    | [83e4ff7f1b](https://linux-hardware.org/?probe=83e4ff7f1b) | Oct 20, 2020 |
| HP            | ZBook 15                    | [1de0f37e99](https://linux-hardware.org/?probe=1de0f37e99) | Oct 20, 2020 |
| HP            | ProBook 450 G3              | [a1767ad1a4](https://linux-hardware.org/?probe=a1767ad1a4) | Oct 17, 2020 |
| HP            | ProBook 450 G3              | [e4faef5664](https://linux-hardware.org/?probe=e4faef5664) | Oct 17, 2020 |
| Lenovo        | ThinkPad A485 20MU000DMX    | [2e95605d0b](https://linux-hardware.org/?probe=2e95605d0b) | Oct 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6bccbe114e](https://linux-hardware.org/?probe=6bccbe114e) | Oct 15, 2020 |
| Dell          | Latitude 3350               | [4cd708305e](https://linux-hardware.org/?probe=4cd708305e) | Oct 15, 2020 |
| Apple         | MacBookPro9,2               | [b2ee43c521](https://linux-hardware.org/?probe=b2ee43c521) | Oct 15, 2020 |
| Dell          | Vostro 5471                 | [22d3ea53f1](https://linux-hardware.org/?probe=22d3ea53f1) | Oct 12, 2020 |
| Dell          | XPS 13 9360                 | [fd0d0c7def](https://linux-hardware.org/?probe=fd0d0c7def) | Oct 12, 2020 |
| HP            | EliteBook 840 G2            | [9cb88c457c](https://linux-hardware.org/?probe=9cb88c457c) | Oct 10, 2020 |
| Dell          | Latitude 7490               | [13b67348d0](https://linux-hardware.org/?probe=13b67348d0) | Oct 09, 2020 |
| Dell          | XPS 13 9360                 | [a748505992](https://linux-hardware.org/?probe=a748505992) | Oct 05, 2020 |
| Dell          | Latitude 3350               | [40f1d36776](https://linux-hardware.org/?probe=40f1d36776) | Oct 05, 2020 |
| Lenovo        | ThinkPad L440 20ASS2JL00    | [f94c3aa8fd](https://linux-hardware.org/?probe=f94c3aa8fd) | Oct 05, 2020 |
| HP            | ZBook 15 G2                 | [10ee29e867](https://linux-hardware.org/?probe=10ee29e867) | Oct 04, 2020 |
| PC Special... | N150CU                      | [d6855993c3](https://linux-hardware.org/?probe=d6855993c3) | Oct 01, 2020 |
| Lenovo        | V130-15IKB 81HN             | [09abf1a088](https://linux-hardware.org/?probe=09abf1a088) | Sep 30, 2020 |
| Lenovo        | ThinkPad L460 20FU002UMX    | [c87dcf0aa1](https://linux-hardware.org/?probe=c87dcf0aa1) | Sep 29, 2020 |
| ASUSTek       | X751BP                      | [f361030dac](https://linux-hardware.org/?probe=f361030dac) | Sep 29, 2020 |
| ASUSTek       | X751BP                      | [0ff716d746](https://linux-hardware.org/?probe=0ff716d746) | Sep 29, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [add52d1094](https://linux-hardware.org/?probe=add52d1094) | Sep 29, 2020 |
| Lenovo        | ThinkPad P52 20M9001FRT     | [51c9d65b89](https://linux-hardware.org/?probe=51c9d65b89) | Sep 29, 2020 |
| Lenovo        | ThinkPad E495 20NE001TMX    | [fe24c7efc7](https://linux-hardware.org/?probe=fe24c7efc7) | Sep 28, 2020 |
| ASUSTek       | X556UB                      | [15790fbe92](https://linux-hardware.org/?probe=15790fbe92) | Sep 28, 2020 |
| Dell          | XPS 15 9570                 | [40fd0fa205](https://linux-hardware.org/?probe=40fd0fa205) | Sep 28, 2020 |
| Acer          | Aspire V3-571               | [0aa3ce7368](https://linux-hardware.org/?probe=0aa3ce7368) | Sep 27, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [cc52f7719c](https://linux-hardware.org/?probe=cc52f7719c) | Sep 26, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [48212a4f99](https://linux-hardware.org/?probe=48212a4f99) | Sep 26, 2020 |
| ASUSTek       | UL30VT                      | [0c2c2af0ce](https://linux-hardware.org/?probe=0c2c2af0ce) | Sep 26, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [31e0cd8ca1](https://linux-hardware.org/?probe=31e0cd8ca1) | Sep 24, 2020 |
| HP            | ZBook Studio G5             | [65ffa6972f](https://linux-hardware.org/?probe=65ffa6972f) | Sep 23, 2020 |
| Dell          | Inspiron 5520               | [d0303f5b83](https://linux-hardware.org/?probe=d0303f5b83) | Sep 23, 2020 |
| HP            | Compaq 6710b (KE121ET#AK... | [7adc66498b](https://linux-hardware.org/?probe=7adc66498b) | Sep 22, 2020 |
| Dell          | Latitude 3350               | [7ac791fc18](https://linux-hardware.org/?probe=7ac791fc18) | Sep 20, 2020 |
| ASUSTek       | UL30VT                      | [48f8840b61](https://linux-hardware.org/?probe=48f8840b61) | Sep 19, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [a96ad52bc9](https://linux-hardware.org/?probe=a96ad52bc9) | Sep 16, 2020 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [1726e5904b](https://linux-hardware.org/?probe=1726e5904b) | Sep 13, 2020 |
| HP            | ProBook 470 G1              | [8369e41ac6](https://linux-hardware.org/?probe=8369e41ac6) | Sep 09, 2020 |
| Toshiba       | Satellite C670D-11P         | [951c1d520e](https://linux-hardware.org/?probe=951c1d520e) | Sep 06, 2020 |
| Toshiba       | Satellite C670D-11P         | [232e086547](https://linux-hardware.org/?probe=232e086547) | Sep 06, 2020 |
| ASUSTek       | G751JY                      | [773aaa38ba](https://linux-hardware.org/?probe=773aaa38ba) | Sep 03, 2020 |
| ASUSTek       | TUF Gaming FA506IV_FX506... | [6265987b7d](https://linux-hardware.org/?probe=6265987b7d) | Sep 02, 2020 |
| Dell          | Precision 5530              | [59be93b9f3](https://linux-hardware.org/?probe=59be93b9f3) | Sep 02, 2020 |
| Dell          | XPS 15 9500                 | [8dae51e89a](https://linux-hardware.org/?probe=8dae51e89a) | Sep 02, 2020 |
| Lenovo        | Z50-70 20354                | [04a50d1273](https://linux-hardware.org/?probe=04a50d1273) | Sep 01, 2020 |
| Dell          | XPS 13 9360                 | [9c688c8ec3](https://linux-hardware.org/?probe=9c688c8ec3) | Sep 01, 2020 |
| Dell          | XPS 13 9360                 | [c43e8e5452](https://linux-hardware.org/?probe=c43e8e5452) | Sep 01, 2020 |
| Dell          | XPS 15 9500                 | [867b9c76b4](https://linux-hardware.org/?probe=867b9c76b4) | Aug 31, 2020 |
| HP            | ProBook 4540s               | [615e7d9dfa](https://linux-hardware.org/?probe=615e7d9dfa) | Aug 29, 2020 |
| Google        | Reks                        | [9642234bc1](https://linux-hardware.org/?probe=9642234bc1) | Aug 27, 2020 |
| Sony          | VPCCW1S1E                   | [a21990e7e3](https://linux-hardware.org/?probe=a21990e7e3) | Aug 26, 2020 |
| Sony          | SVF13N2J4RS                 | [3ce53aa5ba](https://linux-hardware.org/?probe=3ce53aa5ba) | Aug 26, 2020 |
| HP            | EliteBook Folio 1040 G2     | [b0c7b9a8df](https://linux-hardware.org/?probe=b0c7b9a8df) | Aug 24, 2020 |
| Dell          | XPS 15 9570                 | [b2636a7543](https://linux-hardware.org/?probe=b2636a7543) | Aug 24, 2020 |
| HP            | Laptop 14s-dq1xxx           | [e7450d32f7](https://linux-hardware.org/?probe=e7450d32f7) | Aug 24, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [7c299b5384](https://linux-hardware.org/?probe=7c299b5384) | Aug 23, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [19586f3d92](https://linux-hardware.org/?probe=19586f3d92) | Aug 23, 2020 |
| HP            | ProBook 4540s               | [d802ce490d](https://linux-hardware.org/?probe=d802ce490d) | Aug 23, 2020 |
| Dell          | Latitude E6410              | [fd9e17ee51](https://linux-hardware.org/?probe=fd9e17ee51) | Aug 22, 2020 |
| Dell          | Latitude 5480               | [a3d3c7d13d](https://linux-hardware.org/?probe=a3d3c7d13d) | Aug 19, 2020 |
| HP            | EliteBook 840 G6            | [8f768222bd](https://linux-hardware.org/?probe=8f768222bd) | Aug 19, 2020 |
| Lenovo        | ThinkPad W530 24478K0       | [74fda860f1](https://linux-hardware.org/?probe=74fda860f1) | Aug 17, 2020 |
| Acer          | Aspire V3-772G              | [43cad6ef61](https://linux-hardware.org/?probe=43cad6ef61) | Aug 16, 2020 |
| MSI           | PS63 Modern 8SC             | [6a5ce95a82](https://linux-hardware.org/?probe=6a5ce95a82) | Aug 16, 2020 |
| Dell          | Latitude E6230              | [413296aea0](https://linux-hardware.org/?probe=413296aea0) | Aug 15, 2020 |
| Sony          | SVE1713C5E                  | [d5548d16b9](https://linux-hardware.org/?probe=d5548d16b9) | Aug 11, 2020 |
| YJKC          | vBOOK Plus RVP7             | [9d61e799e9](https://linux-hardware.org/?probe=9d61e799e9) | Aug 11, 2020 |
| Packard Be... | EasyNote TE69KB             | [5a431ae254](https://linux-hardware.org/?probe=5a431ae254) | Aug 08, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [df9004d133](https://linux-hardware.org/?probe=df9004d133) | Aug 07, 2020 |
| HP            | ProBook 4540s               | [ba871fc63f](https://linux-hardware.org/?probe=ba871fc63f) | Aug 06, 2020 |
| Dell          | Vostro 15-3568              | [a8ae8e7d68](https://linux-hardware.org/?probe=a8ae8e7d68) | Aug 05, 2020 |
| HP            | EliteBook 820 G3            | [9cc6147a4b](https://linux-hardware.org/?probe=9cc6147a4b) | Aug 03, 2020 |
| HP            | Notebook                    | [daf982706c](https://linux-hardware.org/?probe=daf982706c) | Aug 02, 2020 |
| HP            | Notebook                    | [1b3e005f48](https://linux-hardware.org/?probe=1b3e005f48) | Aug 02, 2020 |
| Sony          | VPCCA2S1E                   | [23d271e5f9](https://linux-hardware.org/?probe=23d271e5f9) | Aug 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [866268f4a1](https://linux-hardware.org/?probe=866268f4a1) | Jul 30, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [7495dfc0db](https://linux-hardware.org/?probe=7495dfc0db) | Jul 28, 2020 |
| Dell          | XPS 15 9560                 | [897c79afd9](https://linux-hardware.org/?probe=897c79afd9) | Jul 28, 2020 |
| HP            | ProBook 440 G4              | [2c9f3809f5](https://linux-hardware.org/?probe=2c9f3809f5) | Jul 25, 2020 |
| Dell          | Latitude 7390               | [66315a7d03](https://linux-hardware.org/?probe=66315a7d03) | Jul 24, 2020 |
| Dell          | Latitude 7400               | [1d53623b83](https://linux-hardware.org/?probe=1d53623b83) | Jul 23, 2020 |
| Lenovo        | G50-80 80E5                 | [4c71d19b3c](https://linux-hardware.org/?probe=4c71d19b3c) | Jul 23, 2020 |
| Toshiba       | Satellite Pro A300          | [f6f47ddd48](https://linux-hardware.org/?probe=f6f47ddd48) | Jul 22, 2020 |
| Dell          | Vostro 15-3568              | [52281c5c2d](https://linux-hardware.org/?probe=52281c5c2d) | Jul 22, 2020 |
| Lenovo        | ThinkPad T420 4236H45       | [61fd4ce395](https://linux-hardware.org/?probe=61fd4ce395) | Jul 20, 2020 |
| ASUSTek       | N550JK                      | [46cb4a6a21](https://linux-hardware.org/?probe=46cb4a6a21) | Jul 19, 2020 |
| Notebook      | N13xWU                      | [b454f8be8b](https://linux-hardware.org/?probe=b454f8be8b) | Jul 19, 2020 |
| Lenovo        | ThinkPad Edge 13IAL# 019... | [f1e0ca231d](https://linux-hardware.org/?probe=f1e0ca231d) | Jul 17, 2020 |
| Packard Be... | DOTS E2                     | [7c39181469](https://linux-hardware.org/?probe=7c39181469) | Jul 16, 2020 |
| Packard Be... | DOTS E2                     | [6ccd387cca](https://linux-hardware.org/?probe=6ccd387cca) | Jul 16, 2020 |
| Toshiba       | Satellite Pro A300          | [161d2f4301](https://linux-hardware.org/?probe=161d2f4301) | Jul 13, 2020 |
| Sony          | VPCYA1V9E                   | [a18b5b10da](https://linux-hardware.org/?probe=a18b5b10da) | Jul 13, 2020 |
| ASUSTek       | G551JM                      | [49c799973a](https://linux-hardware.org/?probe=49c799973a) | Jul 11, 2020 |
| HP            | ProBook 430 G1              | [695797d759](https://linux-hardware.org/?probe=695797d759) | Jul 11, 2020 |
| Lenovo        | IdeaPad S145-14API 81UV     | [04341d8ec3](https://linux-hardware.org/?probe=04341d8ec3) | Jul 11, 2020 |
| GOCLEVER      | INSIGNIA 1010 Business      | [16e0fc6692](https://linux-hardware.org/?probe=16e0fc6692) | Jul 10, 2020 |
| ASUSTek       | N550JV                      | [ef73738889](https://linux-hardware.org/?probe=ef73738889) | Jul 10, 2020 |
| ASUSTek       | N550JV                      | [037229866f](https://linux-hardware.org/?probe=037229866f) | Jul 10, 2020 |
| Notebook      | N2x0WU                      | [3d377a9ec3](https://linux-hardware.org/?probe=3d377a9ec3) | Jul 09, 2020 |
| PC Special... | N150CU                      | [98055ea3a5](https://linux-hardware.org/?probe=98055ea3a5) | Jul 06, 2020 |
| PC Special... | N150CU                      | [940e89b2ae](https://linux-hardware.org/?probe=940e89b2ae) | Jul 05, 2020 |
| PC Special... | N150CU                      | [6f7e0f4a22](https://linux-hardware.org/?probe=6f7e0f4a22) | Jul 04, 2020 |
| Lenovo        | ThinkPad P52 20M9001FRT     | [6deb3ed800](https://linux-hardware.org/?probe=6deb3ed800) | Jul 04, 2020 |
| PC Special... | N150CU                      | [e000363c3f](https://linux-hardware.org/?probe=e000363c3f) | Jul 03, 2020 |
| Lenovo        | ThinkPad P52 20M9001FRT     | [7ad372e11f](https://linux-hardware.org/?probe=7ad372e11f) | Jul 03, 2020 |
| ASUSTek       | K53SD                       | [0d83d52317](https://linux-hardware.org/?probe=0d83d52317) | Jul 01, 2020 |
| Dell          | Latitude 7490               | [4a6f72df25](https://linux-hardware.org/?probe=4a6f72df25) | Jun 30, 2020 |
| Lenovo        | ThinkPad P52 20M9001FRT     | [6ec07a9cad](https://linux-hardware.org/?probe=6ec07a9cad) | Jun 29, 2020 |
| HP            | EliteBook 840 G2            | [ba88603322](https://linux-hardware.org/?probe=ba88603322) | Jun 24, 2020 |
| Dell          | Latitude E6430              | [cc1fa32507](https://linux-hardware.org/?probe=cc1fa32507) | Jun 24, 2020 |
| ASUSTek       | UX430UQ                     | [9c5906b7df](https://linux-hardware.org/?probe=9c5906b7df) | Jun 23, 2020 |
| Sony          | VPCCA2S1E                   | [a26823176d](https://linux-hardware.org/?probe=a26823176d) | Jun 22, 2020 |
| PC Special... | N150CU                      | [82eaf1bef8](https://linux-hardware.org/?probe=82eaf1bef8) | Jun 21, 2020 |
| Fujitsu       | LIFEBOOK E751               | [0b74929cd1](https://linux-hardware.org/?probe=0b74929cd1) | Jun 21, 2020 |
| HP            | ProBook 430 G1              | [473b9249b2](https://linux-hardware.org/?probe=473b9249b2) | Jun 12, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [5467542c77](https://linux-hardware.org/?probe=5467542c77) | Jun 12, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [fb368ee6dc](https://linux-hardware.org/?probe=fb368ee6dc) | Jun 10, 2020 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [4660651265](https://linux-hardware.org/?probe=4660651265) | Jun 09, 2020 |
| HP            | 625                         | [e9ade42809](https://linux-hardware.org/?probe=e9ade42809) | Jun 08, 2020 |
| Lenovo        | ThinkPad E420 114139C       | [26e1631c47](https://linux-hardware.org/?probe=26e1631c47) | Jun 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS4YA00    | [72150af905](https://linux-hardware.org/?probe=72150af905) | Jun 06, 2020 |
| HP            | ProBook 6450b               | [284e204208](https://linux-hardware.org/?probe=284e204208) | Jun 06, 2020 |
| HP            | ZBook 15 G2                 | [9328b8effd](https://linux-hardware.org/?probe=9328b8effd) | Jun 04, 2020 |
| HP            | ZBook 15 G2                 | [9b005ed92f](https://linux-hardware.org/?probe=9b005ed92f) | Jun 04, 2020 |
| HP            | EliteBook 6930p             | [3432c6484b](https://linux-hardware.org/?probe=3432c6484b) | Jun 03, 2020 |
| HP            | Laptop 14s-dq0xxx           | [3ed5064431](https://linux-hardware.org/?probe=3ed5064431) | Jun 02, 2020 |
| Lenovo        | B50-10 80QR                 | [c45530245e](https://linux-hardware.org/?probe=c45530245e) | May 31, 2020 |
| Lenovo        | ThinkPad E585 20KVCTO1WW    | [cf889ffa9b](https://linux-hardware.org/?probe=cf889ffa9b) | May 30, 2020 |
| ASUSTek       | G551JM                      | [bd4ec15cc6](https://linux-hardware.org/?probe=bd4ec15cc6) | May 30, 2020 |
| ASUSTek       | E200HA                      | [36deac6afa](https://linux-hardware.org/?probe=36deac6afa) | May 28, 2020 |
| Notebook      | P570WM                      | [1694f6a1b4](https://linux-hardware.org/?probe=1694f6a1b4) | May 28, 2020 |
| Notebook      | N13xWU                      | [ee1520ea0b](https://linux-hardware.org/?probe=ee1520ea0b) | May 25, 2020 |
| Lenovo        | IdeaPad Y580                | [ba61d3b772](https://linux-hardware.org/?probe=ba61d3b772) | May 25, 2020 |
| Dell          | XPS 15 9570                 | [879f81ed53](https://linux-hardware.org/?probe=879f81ed53) | May 24, 2020 |
| Timi          | Mi Laptop Air 12.5          | [fea499e36a](https://linux-hardware.org/?probe=fea499e36a) | May 23, 2020 |
| HP            | EliteBook 8440p             | [d30d689804](https://linux-hardware.org/?probe=d30d689804) | May 22, 2020 |
| HP            | Pavilion 15                 | [a5e1596dd8](https://linux-hardware.org/?probe=a5e1596dd8) | May 22, 2020 |
| Lenovo        | G50-30 80G0                 | [1a492253fe](https://linux-hardware.org/?probe=1a492253fe) | May 21, 2020 |
| HP            | EliteBook 8440p             | [db74e08b09](https://linux-hardware.org/?probe=db74e08b09) | May 20, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [eb8c922364](https://linux-hardware.org/?probe=eb8c922364) | May 20, 2020 |
| Sony          | SVF13N2J4RS                 | [f779b76a33](https://linux-hardware.org/?probe=f779b76a33) | May 19, 2020 |
| Sony          | SVF13N2J4RS                 | [ba5159d1a8](https://linux-hardware.org/?probe=ba5159d1a8) | May 19, 2020 |
| HP            | ProBook 640 G1              | [b57d5fdc43](https://linux-hardware.org/?probe=b57d5fdc43) | May 17, 2020 |
| Acer          | V5-131                      | [9d9e227434](https://linux-hardware.org/?probe=9d9e227434) | May 16, 2020 |
| Clevo         | P750ZM-G                    | [beb2b53686](https://linux-hardware.org/?probe=beb2b53686) | May 16, 2020 |
| Clevo         | P750ZM-G                    | [4858516cf9](https://linux-hardware.org/?probe=4858516cf9) | May 16, 2020 |
| Acer          | Aspire 4820T                | [8ca11aba8f](https://linux-hardware.org/?probe=8ca11aba8f) | May 16, 2020 |
| HP            | ProBook 4540s               | [f0a5be56bb](https://linux-hardware.org/?probe=f0a5be56bb) | May 15, 2020 |
| Acer          | Aspire 5750G                | [e99f24b527](https://linux-hardware.org/?probe=e99f24b527) | May 15, 2020 |
| Acer          | Nitro AN515-51              | [a569a7d8a9](https://linux-hardware.org/?probe=a569a7d8a9) | May 15, 2020 |
| Acer          | Nitro AN515-51              | [e3fcbaa1a5](https://linux-hardware.org/?probe=e3fcbaa1a5) | May 15, 2020 |
| HP            | ProBook 650 G1              | [04a93aee3e](https://linux-hardware.org/?probe=04a93aee3e) | May 14, 2020 |
| HP            | ProBook 4540s               | [8a4bbfd536](https://linux-hardware.org/?probe=8a4bbfd536) | May 12, 2020 |
| HP            | ProBook 4540s               | [58e5c8e8f5](https://linux-hardware.org/?probe=58e5c8e8f5) | May 12, 2020 |
| HP            | ProBook 4540s               | [51f30e9bc5](https://linux-hardware.org/?probe=51f30e9bc5) | May 12, 2020 |
| Dell          | Precision 3540              | [584cf3a01d](https://linux-hardware.org/?probe=584cf3a01d) | May 12, 2020 |
| HP            | ProBook 650 G1              | [7469ce175f](https://linux-hardware.org/?probe=7469ce175f) | May 11, 2020 |
| ASUSTek       | E402NA                      | [bc0fa6176d](https://linux-hardware.org/?probe=bc0fa6176d) | May 11, 2020 |
| Dell          | XPS 15 9570                 | [aa3b17d74c](https://linux-hardware.org/?probe=aa3b17d74c) | May 10, 2020 |
| HP            | ENVY 17                     | [dc50734505](https://linux-hardware.org/?probe=dc50734505) | May 09, 2020 |
| Lenovo        | ThinkPad X280 20KES3EJ1F    | [0efaa861b2](https://linux-hardware.org/?probe=0efaa861b2) | May 06, 2020 |
| ASUSTek       | UX430UAR                    | [acc88c72e9](https://linux-hardware.org/?probe=acc88c72e9) | May 06, 2020 |
| ASUSTek       | UX430UAR                    | [34b28c7178](https://linux-hardware.org/?probe=34b28c7178) | May 06, 2020 |
| Acer          | Aspire ES1-520              | [a668717511](https://linux-hardware.org/?probe=a668717511) | May 06, 2020 |
| Acer          | Aspire ES1-520              | [1bd4d9bf6d](https://linux-hardware.org/?probe=1bd4d9bf6d) | May 06, 2020 |
| Acer          | Aspire 5750G                | [1f49c0d636](https://linux-hardware.org/?probe=1f49c0d636) | May 06, 2020 |
| ASUSTek       | UL50VT                      | [8e2b687a92](https://linux-hardware.org/?probe=8e2b687a92) | May 05, 2020 |
| HP            | ENVY 17                     | [678613c5fd](https://linux-hardware.org/?probe=678613c5fd) | May 04, 2020 |
| HP            | ENVY 15                     | [b7a95a039c](https://linux-hardware.org/?probe=b7a95a039c) | May 02, 2020 |
| Acer          | Aspire V5-591G              | [c59d87d4e8](https://linux-hardware.org/?probe=c59d87d4e8) | May 02, 2020 |
| Acer          | Aspire V5-591G              | [b61cc2c62c](https://linux-hardware.org/?probe=b61cc2c62c) | May 02, 2020 |
| Acer          | Aspire V5-591G              | [cbd3da2e2c](https://linux-hardware.org/?probe=cbd3da2e2c) | May 02, 2020 |
| ASUSTek       | X556UB                      | [ae412b00e1](https://linux-hardware.org/?probe=ae412b00e1) | May 02, 2020 |
| HP            | Presario CQ56               | [fd2b506a3c](https://linux-hardware.org/?probe=fd2b506a3c) | May 01, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [d8f839baa0](https://linux-hardware.org/?probe=d8f839baa0) | Apr 30, 2020 |
| Dell          | Precision 7720              | [0aec67e1aa](https://linux-hardware.org/?probe=0aec67e1aa) | Apr 30, 2020 |
| HP            | EliteBook Revolve 810       | [40a2ae2d78](https://linux-hardware.org/?probe=40a2ae2d78) | Apr 30, 2020 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [a2524c8953](https://linux-hardware.org/?probe=a2524c8953) | Apr 29, 2020 |
| HP            | Mini 110-4100               | [bbde41e555](https://linux-hardware.org/?probe=bbde41e555) | Apr 29, 2020 |
| Dell          | Latitude E6410              | [1c4ae21a22](https://linux-hardware.org/?probe=1c4ae21a22) | Apr 29, 2020 |
| Dell          | Latitude E6420              | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| Dell          | Latitude E6410              | [6d6e5d12d7](https://linux-hardware.org/?probe=6d6e5d12d7) | Apr 28, 2020 |
| Dell          | Latitude E6420              | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| HP            | EliteBook 8440p             | [2cdb879e53](https://linux-hardware.org/?probe=2cdb879e53) | Apr 27, 2020 |
| HP            | EliteBook Revolve 810       | [e5fef38d4a](https://linux-hardware.org/?probe=e5fef38d4a) | Apr 26, 2020 |
| Apple         | MacBook7,1                  | [407182ed35](https://linux-hardware.org/?probe=407182ed35) | Apr 11, 2020 |
| ASUSTek       | UX430UA                     | [986bd53d04](https://linux-hardware.org/?probe=986bd53d04) | Apr 09, 2020 |
| ASUSTek       | UX430UA                     | [d162142e91](https://linux-hardware.org/?probe=d162142e91) | Apr 08, 2020 |
| ASUSTek       | UX430UA                     | [b4de2d5657](https://linux-hardware.org/?probe=b4de2d5657) | Apr 08, 2020 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [6fab8d402a](https://linux-hardware.org/?probe=6fab8d402a) | Apr 06, 2020 |
| Lenovo        | ThinkPad X200 7455FGG       | [4a3a962ddb](https://linux-hardware.org/?probe=4a3a962ddb) | Apr 06, 2020 |
| Apple         | MacBook7,1                  | [217a5fad34](https://linux-hardware.org/?probe=217a5fad34) | Apr 03, 2020 |
| Apple         | MacBook7,1                  | [bc06b430d4](https://linux-hardware.org/?probe=bc06b430d4) | Apr 03, 2020 |
| Lenovo        | ThinkPad Edge E330 33544... | [d42e44c52b](https://linux-hardware.org/?probe=d42e44c52b) | Apr 02, 2020 |
| Lenovo        | ThinkPad W520 42762QU       | [941c3334ef](https://linux-hardware.org/?probe=941c3334ef) | Apr 01, 2020 |
| Unknown       | Unknown                     | [f50f79e9b1](https://linux-hardware.org/?probe=f50f79e9b1) | Mar 31, 2020 |
| Unknown       | Unknown                     | [59b9d33aff](https://linux-hardware.org/?probe=59b9d33aff) | Mar 31, 2020 |
| Unknown       | Unknown                     | [259cf3831a](https://linux-hardware.org/?probe=259cf3831a) | Mar 31, 2020 |
| Lenovo        | ThinkPad R400 7440WWQ       | [ac4c4ee6d7](https://linux-hardware.org/?probe=ac4c4ee6d7) | Mar 31, 2020 |
| Lenovo        | ThinkPad T61 765912G        | [b0f13713a3](https://linux-hardware.org/?probe=b0f13713a3) | Mar 28, 2020 |
| HP            | Pavilion dv6                | [245afe2ea1](https://linux-hardware.org/?probe=245afe2ea1) | Mar 27, 2020 |
| HP            | Pavilion dv9700             | [7567e3c677](https://linux-hardware.org/?probe=7567e3c677) | Mar 26, 2020 |
| HP            | Pavilion dv7                | [b0ee344201](https://linux-hardware.org/?probe=b0ee344201) | Mar 25, 2020 |
| Sony          | VPCZ12Z9E                   | [ae45786fec](https://linux-hardware.org/?probe=ae45786fec) | Mar 25, 2020 |
| Dell          | Latitude 7400               | [83493959ab](https://linux-hardware.org/?probe=83493959ab) | Mar 23, 2020 |
| HP            | ProBook 470 G2              | [5147582189](https://linux-hardware.org/?probe=5147582189) | Mar 23, 2020 |
| Lenovo        | ThinkPad T61 765912G        | [9fed8f6361](https://linux-hardware.org/?probe=9fed8f6361) | Mar 22, 2020 |
| Packard Be... | EasyNote TE11HC             | [f78d4367a3](https://linux-hardware.org/?probe=f78d4367a3) | Mar 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6c236cb71f](https://linux-hardware.org/?probe=6c236cb71f) | Mar 20, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2b29fb1ae7](https://linux-hardware.org/?probe=2b29fb1ae7) | Mar 20, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b25c0b22cf](https://linux-hardware.org/?probe=b25c0b22cf) | Mar 20, 2020 |
| Dell          | Latitude 7280               | [25e3e0d0c0](https://linux-hardware.org/?probe=25e3e0d0c0) | Mar 18, 2020 |
| ASUSTek       | F3E                         | [e01cca6624](https://linux-hardware.org/?probe=e01cca6624) | Mar 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [e110c6f1b8](https://linux-hardware.org/?probe=e110c6f1b8) | Mar 18, 2020 |
| HP            | Unknown                     | [7ebfd4d205](https://linux-hardware.org/?probe=7ebfd4d205) | Mar 18, 2020 |
| HP            | Laptop 15-db0xxx            | [921bbb3b93](https://linux-hardware.org/?probe=921bbb3b93) | Mar 17, 2020 |
| Lenovo        | ThinkPad X230 2325DM1       | [939a925ce0](https://linux-hardware.org/?probe=939a925ce0) | Mar 17, 2020 |
| ASUSTek       | F3E                         | [d7a53d4fb8](https://linux-hardware.org/?probe=d7a53d4fb8) | Mar 17, 2020 |
| Dell          | Latitude 7280               | [32fc9b1a64](https://linux-hardware.org/?probe=32fc9b1a64) | Mar 17, 2020 |
| MSI           | PS63 Modern 8SC             | [c130f3a54a](https://linux-hardware.org/?probe=c130f3a54a) | Mar 16, 2020 |
| PC Special... | N150CU                      | [63600ae5a5](https://linux-hardware.org/?probe=63600ae5a5) | Mar 16, 2020 |
| HP            | Pavilion dv9700             | [60bcd3ac92](https://linux-hardware.org/?probe=60bcd3ac92) | Mar 15, 2020 |
| Dell          | Precision M6500             | [6a504a8f78](https://linux-hardware.org/?probe=6a504a8f78) | Mar 14, 2020 |
| Lenovo        | ThinkPad Edge 13IAL# 019... | [53c96c3bf1](https://linux-hardware.org/?probe=53c96c3bf1) | Mar 13, 2020 |
| HP            | ProBook 470 G1              | [75e6bdea96](https://linux-hardware.org/?probe=75e6bdea96) | Mar 11, 2020 |
| MSI           | GP62MVR 7RF                 | [c8b9c1580a](https://linux-hardware.org/?probe=c8b9c1580a) | Mar 04, 2020 |
| Dell          | Precision M4500             | [acda89894a](https://linux-hardware.org/?probe=acda89894a) | Mar 04, 2020 |
| ASUSTek       | N53TK                       | [33ca8c2776](https://linux-hardware.org/?probe=33ca8c2776) | Mar 01, 2020 |
| HP            | EliteBook 820 G4            | [b525dfeb66](https://linux-hardware.org/?probe=b525dfeb66) | Mar 01, 2020 |
| HP            | EliteBook 820 G4            | [e28f1711fd](https://linux-hardware.org/?probe=e28f1711fd) | Mar 01, 2020 |
| Acer          | Aspire E5-521               | [a2c53641e0](https://linux-hardware.org/?probe=a2c53641e0) | Mar 01, 2020 |
| HP            | EliteBook 820 G4            | [a1a19da83e](https://linux-hardware.org/?probe=a1a19da83e) | Feb 28, 2020 |
| Acer          | Nitro AN515-54              | [3c1c376379](https://linux-hardware.org/?probe=3c1c376379) | Feb 27, 2020 |
| GIADA         | Cherry Trail CR JHS60V      | [43b5196d13](https://linux-hardware.org/?probe=43b5196d13) | Feb 26, 2020 |
| HP            | EliteBook 840 G1            | [cd0a628cc6](https://linux-hardware.org/?probe=cd0a628cc6) | Feb 23, 2020 |
| HP            | ProBook 470 G2              | [164fe60898](https://linux-hardware.org/?probe=164fe60898) | Feb 22, 2020 |
| Lenovo        | Z50-70 20354                | [6986243613](https://linux-hardware.org/?probe=6986243613) | Feb 20, 2020 |
| ASUSTek       | UX490UA                     | [dceab5e950](https://linux-hardware.org/?probe=dceab5e950) | Feb 12, 2020 |
| Dell          | Precision 7520              | [9c4c70327e](https://linux-hardware.org/?probe=9c4c70327e) | Feb 11, 2020 |
| Dell          | Precision 7520              | [6ea5b490b0](https://linux-hardware.org/?probe=6ea5b490b0) | Feb 11, 2020 |
| HP            | EliteBook 745 G5            | [524879c664](https://linux-hardware.org/?probe=524879c664) | Feb 09, 2020 |
| Dell          | Precision 5540              | [bc3c8c8b06](https://linux-hardware.org/?probe=bc3c8c8b06) | Feb 08, 2020 |
| Sony          | VGN-CR21S_P                 | [2ceca1462f](https://linux-hardware.org/?probe=2ceca1462f) | Feb 08, 2020 |
| Acer          | Predator G3-572             | [4feea4d5ab](https://linux-hardware.org/?probe=4feea4d5ab) | Feb 08, 2020 |
| HP            | EliteBook 8530w             | [0c09501cf1](https://linux-hardware.org/?probe=0c09501cf1) | Feb 07, 2020 |
| HP            | EliteBook 8530w             | [4e7b4a9d8a](https://linux-hardware.org/?probe=4e7b4a9d8a) | Feb 06, 2020 |
| HP            | EliteBook 840 G6            | [cca65a037e](https://linux-hardware.org/?probe=cca65a037e) | Feb 04, 2020 |
| HP            | EliteBook 840 G2            | [22d45681c5](https://linux-hardware.org/?probe=22d45681c5) | Feb 03, 2020 |
| Lenovo        | ThinkPad T460s 20FAS03K0... | [d5fbd58f8b](https://linux-hardware.org/?probe=d5fbd58f8b) | Jan 27, 2020 |
| Lenovo        | ThinkPad T460s 20FAS03K0... | [88338e7031](https://linux-hardware.org/?probe=88338e7031) | Jan 27, 2020 |
| HP            | ProBook 470 G2              | [8dcbd3c2b1](https://linux-hardware.org/?probe=8dcbd3c2b1) | Jan 19, 2020 |
| HP            | Mini 110-4100               | [1fe662dabb](https://linux-hardware.org/?probe=1fe662dabb) | Jan 17, 2020 |
| MSI           | GF63 8RD                    | [df4db86c1b](https://linux-hardware.org/?probe=df4db86c1b) | Jan 17, 2020 |
| HP            | Mini 110-4100               | [b941a5a46e](https://linux-hardware.org/?probe=b941a5a46e) | Jan 15, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [115a69a67c](https://linux-hardware.org/?probe=115a69a67c) | Jan 13, 2020 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [b3f427239c](https://linux-hardware.org/?probe=b3f427239c) | Jan 13, 2020 |
| ASUSTek       | UX301LAA                    | [2acb173a3d](https://linux-hardware.org/?probe=2acb173a3d) | Jan 11, 2020 |
| ASUSTek       | E502SA                      | [3c56957ef8](https://linux-hardware.org/?probe=3c56957ef8) | Jan 05, 2020 |
| Acer          | Aspire E5-521               | [9092bcdf18](https://linux-hardware.org/?probe=9092bcdf18) | Dec 27, 2019 |
| Acer          | Aspire E5-521               | [c1179ad896](https://linux-hardware.org/?probe=c1179ad896) | Dec 27, 2019 |
| Notebook      | W510TU                      | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Dell          | Inspiron 7537               | [584dbb41c7](https://linux-hardware.org/?probe=584dbb41c7) | Dec 22, 2019 |
| Toshiba       | Satellite P70-B             | [52841d6175](https://linux-hardware.org/?probe=52841d6175) | Dec 14, 2019 |
| HP            | Laptop 14-cm0xxx            | [3a1243a77f](https://linux-hardware.org/?probe=3a1243a77f) | Dec 12, 2019 |
| HP            | Laptop 14-cm0xxx            | [71a8ef2f9c](https://linux-hardware.org/?probe=71a8ef2f9c) | Dec 12, 2019 |
| HP            | Laptop 14-cm0xxx            | [492008cdf8](https://linux-hardware.org/?probe=492008cdf8) | Dec 12, 2019 |
| Google        | Reks                        | [ba8fa67918](https://linux-hardware.org/?probe=ba8fa67918) | Dec 07, 2019 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [539c9f807e](https://linux-hardware.org/?probe=539c9f807e) | Dec 03, 2019 |
| Dell          | XPS 13 9380                 | [8eeaf9502b](https://linux-hardware.org/?probe=8eeaf9502b) | Dec 02, 2019 |
| HP            | EliteBook 840 G3            | [13c0b5a2ee](https://linux-hardware.org/?probe=13c0b5a2ee) | Nov 25, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [be40a37ea8](https://linux-hardware.org/?probe=be40a37ea8) | Nov 24, 2019 |
| Dell          | Latitude 7390               | [43cd4a1080](https://linux-hardware.org/?probe=43cd4a1080) | Nov 23, 2019 |
| Acer          | Aspire 5750G                | [1000732301](https://linux-hardware.org/?probe=1000732301) | Nov 22, 2019 |
| HP            | Laptop 15-db0xxx            | [6f881ab9f2](https://linux-hardware.org/?probe=6f881ab9f2) | Nov 13, 2019 |
| Lenovo        | ThinkPad X230 23257J9       | [36e2583bda](https://linux-hardware.org/?probe=36e2583bda) | Nov 04, 2019 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [728af010db](https://linux-hardware.org/?probe=728af010db) | Oct 30, 2019 |
| HP            | EliteBook 840 G3            | [7c15cabb87](https://linux-hardware.org/?probe=7c15cabb87) | Oct 26, 2019 |
| Apple         | MacBookPro15,1              | [7f2d68a6a2](https://linux-hardware.org/?probe=7f2d68a6a2) | Oct 25, 2019 |
| Acer          | Aspire V3-571               | [326131addf](https://linux-hardware.org/?probe=326131addf) | Oct 25, 2019 |
| Acer          | Aspire V3-571               | [8820c8f2a8](https://linux-hardware.org/?probe=8820c8f2a8) | Oct 25, 2019 |
| Acer          | Aspire A515-52              | [bf90e569f0](https://linux-hardware.org/?probe=bf90e569f0) | Oct 22, 2019 |
| Lenovo        | ThinkPad T440p 20AW0045M... | [af93d5a6ab](https://linux-hardware.org/?probe=af93d5a6ab) | Oct 16, 2019 |
| Toshiba       | TECRA Z50-A                 | [ef9f3e6909](https://linux-hardware.org/?probe=ef9f3e6909) | Oct 15, 2019 |
| HP            | Pavilion 17                 | [1bcf00f1f8](https://linux-hardware.org/?probe=1bcf00f1f8) | Oct 14, 2019 |
| MSI           | PS63 Modern 8SC             | [bd1ebc8235](https://linux-hardware.org/?probe=bd1ebc8235) | Oct 12, 2019 |
| HP            | Pavilion dv7                | [917b6cb9d1](https://linux-hardware.org/?probe=917b6cb9d1) | Oct 11, 2019 |
| Dell          | Latitude E6410              | [2d1d7249de](https://linux-hardware.org/?probe=2d1d7249de) | Oct 10, 2019 |
| Lenovo        | G505s 20255                 | [4f005c8ffe](https://linux-hardware.org/?probe=4f005c8ffe) | Oct 09, 2019 |
| Lenovo        | ThinkPad T410 2537W6J       | [1f25447907](https://linux-hardware.org/?probe=1f25447907) | Oct 09, 2019 |
| ASUSTek       | K53E                        | [c50041a286](https://linux-hardware.org/?probe=c50041a286) | Oct 07, 2019 |
| ASUSTek       | S551LN                      | [2f7c16af18](https://linux-hardware.org/?probe=2f7c16af18) | Oct 05, 2019 |
| ASUSTek       | S551LN                      | [a2abf0b84b](https://linux-hardware.org/?probe=a2abf0b84b) | Oct 05, 2019 |
| Lenovo        | ThinkPad T420 4180PBG       | [9ac1a01f50](https://linux-hardware.org/?probe=9ac1a01f50) | Sep 29, 2019 |
| Lenovo        | ThinkPad T420 4180PBG       | [c7d753e640](https://linux-hardware.org/?probe=c7d753e640) | Sep 29, 2019 |
| HP            | EliteBook 840 G1            | [720770f96e](https://linux-hardware.org/?probe=720770f96e) | Sep 28, 2019 |
| HP            | EliteBook 840 G1            | [f748e34af3](https://linux-hardware.org/?probe=f748e34af3) | Sep 28, 2019 |
| Lenovo        | Z50-70 20354                | [acfe20d1cb](https://linux-hardware.org/?probe=acfe20d1cb) | Sep 27, 2019 |
| Lenovo        | ThinkPad T460 20FN003LMD    | [5746413cdb](https://linux-hardware.org/?probe=5746413cdb) | Sep 26, 2019 |
| Lenovo        | ThinkPad T460 20FN003LMD    | [839b45bbcc](https://linux-hardware.org/?probe=839b45bbcc) | Sep 25, 2019 |
| Dell          | Precision 5520              | [ebb304f58e](https://linux-hardware.org/?probe=ebb304f58e) | Sep 19, 2019 |
| Sony          | SVF14N1E2ES                 | [d3ce0f6593](https://linux-hardware.org/?probe=d3ce0f6593) | Sep 18, 2019 |
| Sony          | SVF14N1E2ES                 | [79bb40d8a2](https://linux-hardware.org/?probe=79bb40d8a2) | Sep 18, 2019 |
| Lenovo        | ThinkPad T440p 20AW0045M... | [98097dd871](https://linux-hardware.org/?probe=98097dd871) | Sep 17, 2019 |
| Toshiba       | Satellite L755              | [299e5c9510](https://linux-hardware.org/?probe=299e5c9510) | Sep 16, 2019 |
| Dell          | Precision 5530              | [e5e83e62d1](https://linux-hardware.org/?probe=e5e83e62d1) | Sep 12, 2019 |
| Lenovo        | ThinkPad T61p 64575KU       | [d8398b196b](https://linux-hardware.org/?probe=d8398b196b) | Sep 07, 2019 |
| Lenovo        | ThinkPad T61p 64575KU       | [142dffd0a8](https://linux-hardware.org/?probe=142dffd0a8) | Sep 07, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [ad4dfe7974](https://linux-hardware.org/?probe=ad4dfe7974) | Sep 06, 2019 |
| Acer          | Aspire E5-573               | [1e9a6d075d](https://linux-hardware.org/?probe=1e9a6d075d) | Sep 04, 2019 |
| Acer          | Aspire E5-573               | [ba713d00b4](https://linux-hardware.org/?probe=ba713d00b4) | Sep 03, 2019 |
| Acer          | Aspire A515-52              | [94013da02f](https://linux-hardware.org/?probe=94013da02f) | Sep 01, 2019 |
| Dell          | Latitude E7240              | [adb75ec9e2](https://linux-hardware.org/?probe=adb75ec9e2) | Aug 30, 2019 |
| Dell          | Latitude E7240              | [66479dcb78](https://linux-hardware.org/?probe=66479dcb78) | Aug 26, 2019 |
| Dell          | Latitude E7240              | [f7c0e78cad](https://linux-hardware.org/?probe=f7c0e78cad) | Aug 24, 2019 |
| Dell          | Latitude E7240              | [0190190e34](https://linux-hardware.org/?probe=0190190e34) | Aug 24, 2019 |
| Dell          | Latitude E7240              | [f49e34140c](https://linux-hardware.org/?probe=f49e34140c) | Aug 23, 2019 |
| HP            | G62                         | [30d2858670](https://linux-hardware.org/?probe=30d2858670) | Aug 20, 2019 |
| HP            | G62                         | [ad05c41e4f](https://linux-hardware.org/?probe=ad05c41e4f) | Aug 20, 2019 |
| Acer          | Aspire E5-475               | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Acer          | JM11-MS                     | [7c7be1cb53](https://linux-hardware.org/?probe=7c7be1cb53) | Aug 18, 2019 |
| LG Electro... | R405-A.CPATV                | [7d9e4527b1](https://linux-hardware.org/?probe=7d9e4527b1) | Aug 17, 2019 |
| Dell          | XPS 15 9570                 | [6124772091](https://linux-hardware.org/?probe=6124772091) | Aug 15, 2019 |
| HP            | Pavilion 17                 | [76b4b1f70f](https://linux-hardware.org/?probe=76b4b1f70f) | Aug 15, 2019 |
| Timi          | Mi Laptop Air 12.5          | [8d36fc215c](https://linux-hardware.org/?probe=8d36fc215c) | Aug 14, 2019 |
| Lenovo        | ThinkPad T440s 20AQ0066M... | [54b33d56bb](https://linux-hardware.org/?probe=54b33d56bb) | Aug 14, 2019 |
| Dell          | Latitude E7440              | [5dcc432791](https://linux-hardware.org/?probe=5dcc432791) | Aug 09, 2019 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [82a3a8f8b6](https://linux-hardware.org/?probe=82a3a8f8b6) | Aug 01, 2019 |
| Dell          | XPS 13 9380                 | [369fe503ef](https://linux-hardware.org/?probe=369fe503ef) | Jul 30, 2019 |
| Lenovo        | Z50-70 20354                | [62ed9e8b93](https://linux-hardware.org/?probe=62ed9e8b93) | Jul 29, 2019 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [c07258b9ab](https://linux-hardware.org/?probe=c07258b9ab) | Jul 23, 2019 |
| HP            | Compaq nx7400 (RH410ET#A... | [531d26cdd8](https://linux-hardware.org/?probe=531d26cdd8) | Jul 22, 2019 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [c15e0482ca](https://linux-hardware.org/?probe=c15e0482ca) | Jul 22, 2019 |
| Unknown       | Unknown                     | [b53cddb5c3](https://linux-hardware.org/?probe=b53cddb5c3) | Jul 14, 2019 |
| Unknown       | Unknown                     | [b9f305c7fb](https://linux-hardware.org/?probe=b9f305c7fb) | Jul 14, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [340d0f70dd](https://linux-hardware.org/?probe=340d0f70dd) | Jul 12, 2019 |
| ASUSTek       | T100TA                      | [492943101c](https://linux-hardware.org/?probe=492943101c) | Jul 08, 2019 |
| Notebook      | N150ZU                      | [cca2248332](https://linux-hardware.org/?probe=cca2248332) | Jul 08, 2019 |
| Dell          | Latitude E6430              | [2e0081c6c9](https://linux-hardware.org/?probe=2e0081c6c9) | Jul 06, 2019 |
| HP            | ZBook Studio G5             | [0c96ddc649](https://linux-hardware.org/?probe=0c96ddc649) | Jul 05, 2019 |
| LG Electro... | R405-A.CPATV                | [527defc159](https://linux-hardware.org/?probe=527defc159) | Jul 05, 2019 |
| Notebook      | N150ZU                      | [404de5362a](https://linux-hardware.org/?probe=404de5362a) | Jul 04, 2019 |
| MSI           | GL62M 7RD                   | [4be70464c6](https://linux-hardware.org/?probe=4be70464c6) | Jul 02, 2019 |
| HP            | ProBook 6545b               | [943ae873f7](https://linux-hardware.org/?probe=943ae873f7) | Jun 30, 2019 |
| ASUSTek       | G750JX                      | [5d0fc03224](https://linux-hardware.org/?probe=5d0fc03224) | Jun 22, 2019 |
| HP            | ProBook 6545b               | [27a223171c](https://linux-hardware.org/?probe=27a223171c) | Jun 18, 2019 |
| HP            | ProBook 6545b               | [85b43b7a67](https://linux-hardware.org/?probe=85b43b7a67) | Jun 18, 2019 |
| Dell          | Latitude E5400              | [dd25592a09](https://linux-hardware.org/?probe=dd25592a09) | Jun 15, 2019 |
| Lenovo        | ThinkPad X240 20AMS03400    | [3ec5097b20](https://linux-hardware.org/?probe=3ec5097b20) | Jun 12, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [31a261423c](https://linux-hardware.org/?probe=31a261423c) | Jun 11, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [6a667c9ba7](https://linux-hardware.org/?probe=6a667c9ba7) | Jun 11, 2019 |
| Lenovo        | ThinkPad X240 20AMS03400    | [00a6354cfe](https://linux-hardware.org/?probe=00a6354cfe) | Jun 11, 2019 |
| Dell          | XPS 13 9343                 | [cf32c265c9](https://linux-hardware.org/?probe=cf32c265c9) | Jun 09, 2019 |
| HP            | Laptop 15-db0xxx            | [0ce3ce17c9](https://linux-hardware.org/?probe=0ce3ce17c9) | Jun 09, 2019 |
| HP            | EliteBook Revolve 810       | [d16ce79db7](https://linux-hardware.org/?probe=d16ce79db7) | May 27, 2019 |
| HP            | EliteBook Revolve 810       | [484d3a55b6](https://linux-hardware.org/?probe=484d3a55b6) | May 27, 2019 |
| HP            | EliteBook Revolve 810       | [7d83c8b0c6](https://linux-hardware.org/?probe=7d83c8b0c6) | May 27, 2019 |
| Dell          | Precision M4700             | [87afef045f](https://linux-hardware.org/?probe=87afef045f) | May 26, 2019 |
| Compal        | QAL51                       | [89ec4f0398](https://linux-hardware.org/?probe=89ec4f0398) | May 23, 2019 |
| ASUSTek       | K53SD                       | [1cc0126131](https://linux-hardware.org/?probe=1cc0126131) | May 12, 2019 |
| ASUSTek       | K53SD                       | [aeca3efe75](https://linux-hardware.org/?probe=aeca3efe75) | May 12, 2019 |
| ASUSTek       | G750JM                      | [a4939a2ab2](https://linux-hardware.org/?probe=a4939a2ab2) | May 09, 2019 |
| HP            | Compaq nx8220 (PY522ET#A... | [16f00aae37](https://linux-hardware.org/?probe=16f00aae37) | May 05, 2019 |
| ASUSTek       | X580VD                      | [67dd767da8](https://linux-hardware.org/?probe=67dd767da8) | May 02, 2019 |
| Dell          | Inspiron 1525               | [a670594d28](https://linux-hardware.org/?probe=a670594d28) | May 02, 2019 |
| HP            | Laptop 15-bw0xx             | [75fa0ad712](https://linux-hardware.org/?probe=75fa0ad712) | May 01, 2019 |
| HP            | EliteBook 850 G2            | [a1f762db4e](https://linux-hardware.org/?probe=a1f762db4e) | Apr 30, 2019 |
| Acer          | Aspire E1-571               | [cba53f7e36](https://linux-hardware.org/?probe=cba53f7e36) | Apr 22, 2019 |
| HP            | Pavilion Notebook           | [decb236525](https://linux-hardware.org/?probe=decb236525) | Apr 19, 2019 |
| Alienware     | M11x                        | [b285740a65](https://linux-hardware.org/?probe=b285740a65) | Apr 19, 2019 |
| Notebook      | P95xER                      | [b210a640e8](https://linux-hardware.org/?probe=b210a640e8) | Apr 18, 2019 |
| Notebook      | P95xER                      | [7eff6fd312](https://linux-hardware.org/?probe=7eff6fd312) | Apr 16, 2019 |
| Notebook      | P95xER                      | [ac201a48dd](https://linux-hardware.org/?probe=ac201a48dd) | Apr 16, 2019 |
| Lenovo        | G50-30 80G0                 | [96311d2ed2](https://linux-hardware.org/?probe=96311d2ed2) | Apr 14, 2019 |
| Lenovo        | G50-30 80G0                 | [b7d97c8b7e](https://linux-hardware.org/?probe=b7d97c8b7e) | Apr 14, 2019 |
| Acer          | Predator PH317-52           | [d6d7f9cc30](https://linux-hardware.org/?probe=d6d7f9cc30) | Apr 11, 2019 |
| Acer          | Predator PH317-52           | [c02a5299c0](https://linux-hardware.org/?probe=c02a5299c0) | Apr 11, 2019 |
| Acer          | Predator PH317-52           | [1e305fba69](https://linux-hardware.org/?probe=1e305fba69) | Apr 11, 2019 |
| Compal        | QAL51                       | [d4a586728b](https://linux-hardware.org/?probe=d4a586728b) | Apr 10, 2019 |
| HP            | EliteBook 850 G2            | [5303b9a9c0](https://linux-hardware.org/?probe=5303b9a9c0) | Apr 10, 2019 |
| Dell          | Latitude E6420              | [efd71fbd61](https://linux-hardware.org/?probe=efd71fbd61) | Apr 08, 2019 |
| Acer          | Aspire ES1-311              | [51785e0c60](https://linux-hardware.org/?probe=51785e0c60) | Apr 08, 2019 |
| Lenovo        | B50-30 80ES                 | [c8233fc4ca](https://linux-hardware.org/?probe=c8233fc4ca) | Apr 07, 2019 |
| Dell          | Latitude E6420              | [e9ada78450](https://linux-hardware.org/?probe=e9ada78450) | Apr 04, 2019 |
| HP            | EliteBook 850 G2            | [5fd8ae6342](https://linux-hardware.org/?probe=5fd8ae6342) | Apr 03, 2019 |
| Lenovo        | G50-30 80G0                 | [c9aa18b055](https://linux-hardware.org/?probe=c9aa18b055) | Mar 31, 2019 |
| Lenovo        | G50-30 80G0                 | [1ef12603d4](https://linux-hardware.org/?probe=1ef12603d4) | Mar 31, 2019 |
| Dell          | Latitude E6420              | [6241d440c6](https://linux-hardware.org/?probe=6241d440c6) | Mar 30, 2019 |
| Lenovo        | B50-10 80QR                 | [ee1cff7014](https://linux-hardware.org/?probe=ee1cff7014) | Mar 28, 2019 |
| HP            | Pavilion dv6500             | [2c369d199d](https://linux-hardware.org/?probe=2c369d199d) | Mar 26, 2019 |
| Lenovo        | B50-30 80ES                 | [7fe8b87792](https://linux-hardware.org/?probe=7fe8b87792) | Mar 18, 2019 |
| Dell          | Precision 5520              | [59e81062ed](https://linux-hardware.org/?probe=59e81062ed) | Mar 14, 2019 |
| Dell          | Latitude 7490               | [179aa79466](https://linux-hardware.org/?probe=179aa79466) | Mar 11, 2019 |
| Apple         | MacBook6,1                  | [07e446d7b6](https://linux-hardware.org/?probe=07e446d7b6) | Feb 24, 2019 |
| Unknown       | Unknown                     | [9db4870630](https://linux-hardware.org/?probe=9db4870630) | Feb 03, 2019 |
| Apple         | MacBook6,1                  | [dd10b4292a](https://linux-hardware.org/?probe=dd10b4292a) | Jan 21, 2019 |
| HP            | EliteBook Folio 1040 G1     | [9c1daa8af7](https://linux-hardware.org/?probe=9c1daa8af7) | Jan 13, 2019 |
| Acer          | Aspire 5742G                | [b38929d825](https://linux-hardware.org/?probe=b38929d825) | Jan 11, 2019 |
| Lenovo        | ThinkPad T61 7661KC5        | [020f090196](https://linux-hardware.org/?probe=020f090196) | Jan 07, 2019 |
| Lenovo        | ThinkPad T440s 20ARS19C0... | [358b470fe1](https://linux-hardware.org/?probe=358b470fe1) | Jan 02, 2019 |
| Lenovo        | ThinkPad T440s 20ARS19C0... | [c7b15e8fcc](https://linux-hardware.org/?probe=c7b15e8fcc) | Nov 29, 2018 |
| Lenovo        | ThinkPad X240 20AMS0E300    | [0bbbb9cc2c](https://linux-hardware.org/?probe=0bbbb9cc2c) | Nov 28, 2018 |
| HP            | EliteBook 850 G5            | [d8c8ecc6d6](https://linux-hardware.org/?probe=d8c8ecc6d6) | Nov 26, 2018 |
| HP            | EliteBook 850 G5            | [09baecd7f3](https://linux-hardware.org/?probe=09baecd7f3) | Nov 22, 2018 |
| Lenovo        | G500 20236                  | [2291b3e6df](https://linux-hardware.org/?probe=2291b3e6df) | Nov 18, 2018 |
| Lenovo        | G500 20236                  | [20ced4cf31](https://linux-hardware.org/?probe=20ced4cf31) | Nov 18, 2018 |
| Dell          | XPS 13 9370                 | [de22b154ec](https://linux-hardware.org/?probe=de22b154ec) | Nov 09, 2018 |
| ASUSTek       | GL702VMK                    | [31539069ad](https://linux-hardware.org/?probe=31539069ad) | Nov 04, 2018 |
| Lenovo        | ThinkPad T500 224397G       | [cc1f76e318](https://linux-hardware.org/?probe=cc1f76e318) | Oct 31, 2018 |
| Lenovo        | ThinkPad L380 20M50013MX    | [4d358d79e4](https://linux-hardware.org/?probe=4d358d79e4) | Oct 29, 2018 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [01bed504ba](https://linux-hardware.org/?probe=01bed504ba) | Oct 26, 2018 |
| Lenovo        | ThinkPad T410 252224G       | [2da848af95](https://linux-hardware.org/?probe=2da848af95) | Oct 21, 2018 |
| HP            | Pavilion dv7                | [01378cf7e4](https://linux-hardware.org/?probe=01378cf7e4) | Oct 01, 2018 |
| ASUSTek       | GL702VMK                    | [79423a3080](https://linux-hardware.org/?probe=79423a3080) | Sep 07, 2018 |
| Lenovo        | Y520-15IKBN 80WK            | [bae96b760e](https://linux-hardware.org/?probe=bae96b760e) | Sep 06, 2018 |
| ASUSTek       | K53U                        | [4c564d47eb](https://linux-hardware.org/?probe=4c564d47eb) | Dec 16, 2017 |
| Acer          | Aspire V5-591G              | [04094c3673](https://linux-hardware.org/?probe=04094c3673) | May 24, 2017 |
| ASUSTek       | E502SA                      | [634961b223](https://linux-hardware.org/?probe=634961b223) | May 12, 2017 |
| HP            | Compaq nx6310 (RH334EA#A... | [b7d5546cd6](https://linux-hardware.org/?probe=b7d5546cd6) | Dec 29, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 130       | 16.69%  |
| Ubuntu 18.04                 | 74        | 9.5%    |
| Pop!_OS 21.04                | 22        | 2.82%   |
| OpenMandriva 4.2             | 21        | 2.7%    |
| Debian 11                    | 21        | 2.7%    |
| Ubuntu 19.04                 | 19        | 2.44%   |
| Arch                         | 19        | 2.44%   |
| Fedora 35                    | 18        | 2.31%   |
| Manjaro                      | 17        | 2.18%   |
| Ubuntu 21.10                 | 16        | 2.05%   |
| Pop!_OS 20.10                | 16        | 2.05%   |
| Pop!_OS 20.04                | 16        | 2.05%   |
| Zorin 15                     | 15        | 1.93%   |
| Linux Mint 20.2              | 14        | 1.8%    |
| Ubuntu 19.10                 | 13        | 1.67%   |
| Arch Rolling                 | 13        | 1.67%   |
| Linux Mint 20.1              | 12        | 1.54%   |
| KDE neon 20.04               | 12        | 1.54%   |
| Fedora 34                    | 12        | 1.54%   |
| Zorin 16                     | 11        | 1.41%   |
| Ubuntu 21.04                 | 11        | 1.41%   |
| Ubuntu 20.10                 | 10        | 1.28%   |
| Ubuntu 22.04                 | 9         | 1.16%   |
| Pop!_OS 21.10                | 9         | 1.16%   |
| OpenMandriva 4.3             | 9         | 1.16%   |
| Fedora 33                    | 9         | 1.16%   |
| Linux Mint 20                | 8         | 1.03%   |
| Linux Mint 19.3              | 8         | 1.03%   |
| ArcoLinux Rolling            | 8         | 1.03%   |
| Xubuntu 20.04                | 7         | 0.9%    |
| Ubuntu 18.10                 | 7         | 0.9%    |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 0.9%    |
| Linux Mint 20.3              | 7         | 0.9%    |
| Gentoo 2.6                   | 6         | 0.77%   |
| Fedora 32                    | 6         | 0.77%   |
| Fedora 31                    | 6         | 0.77%   |
| Ubuntu 16.04                 | 5         | 0.64%   |
| Linux Mint 19.1              | 5         | 0.64%   |
| Debian 10                    | 5         | 0.64%   |
| CentOS 8                     | 5         | 0.64%   |
| Kubuntu 20.04                | 4         | 0.51%   |
| Fedora 29                    | 4         | 0.51%   |
| BlackPanther 18.1            | 4         | 0.51%   |
| Pop!_OS 22.04                | 3         | 0.39%   |
| Manjaro 21.2.0               | 3         | 0.39%   |
| Linux Mint 19.2              | 3         | 0.39%   |
| KDE neon 18.04               | 3         | 0.39%   |
| EndeavourOS Rolling          | 3         | 0.39%   |
| EndeavourOS                  | 3         | 0.39%   |
| Elementary 6                 | 3         | 0.39%   |
| Debian Testing               | 3         | 0.39%   |
| ArcoLinux                    | 3         | 0.39%   |
| Xubuntu 22.04                | 2         | 0.26%   |
| Xubuntu 20.10                | 2         | 0.26%   |
| Xubuntu 18.04                | 2         | 0.26%   |
| Ubuntu MATE 20.04            | 2         | 0.26%   |
| ROSA R9                      | 2         | 0.26%   |
| ROSA R10                     | 2         | 0.26%   |
| Peppermint 10                | 2         | 0.26%   |
| OpenMandriva 4.50            | 2         | 0.26%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 280       | 37.33%  |
| Pop!_OS       | 63        | 8.4%    |
| Fedora        | 58        | 7.73%   |
| Linux Mint    | 56        | 7.47%   |
| OpenMandriva  | 33        | 4.4%    |
| Manjaro       | 32        | 4.27%   |
| Arch          | 31        | 4.13%   |
| Debian        | 28        | 3.73%   |
| Zorin         | 26        | 3.47%   |
| Xubuntu       | 16        | 2.13%   |
| KDE neon      | 15        | 2%      |
| ArcoLinux     | 11        | 1.47%   |
| Gentoo        | 9         | 1.2%    |
| Endless       | 8         | 1.07%   |
| ROSA          | 7         | 0.93%   |
| openSUSE      | 7         | 0.93%   |
| Kubuntu       | 7         | 0.93%   |
| EndeavourOS   | 6         | 0.8%    |
| CentOS        | 6         | 0.8%    |
| Ubuntu MATE   | 5         | 0.67%   |
| Kali          | 5         | 0.67%   |
| Elementary    | 4         | 0.53%   |
| BlackPanther  | 4         | 0.53%   |
| Peppermint    | 3         | 0.4%    |
| Parrot        | 3         | 0.4%    |
| Ubuntu Budgie | 2         | 0.27%   |
| Slackware     | 2         | 0.27%   |
| Lubuntu       | 2         | 0.27%   |
| Garuda Linux  | 2         | 0.27%   |
| Clear Linux   | 2         | 0.27%   |
| Chrome OS     | 2         | 0.27%   |
| BunsenLabs    | 2         | 0.27%   |
| Solus         | 1         | 0.13%   |
| Siduction     | 1         | 0.13%   |
| Reborn OS     | 1         | 0.13%   |
| Q4OS          | 1         | 0.13%   |
| NixOS         | 1         | 0.13%   |
| MX            | 1         | 0.13%   |
| LMDE          | 1         | 0.13%   |
| Hefftor       | 1         | 0.13%   |
| Generic       | 1         | 0.13%   |
| Deepin        | 1         | 0.13%   |
| Artix         | 1         | 0.13%   |
| ArchLabs      | 1         | 0.13%   |
| AlmaLinux     | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 21        | 2.49%   |
| 5.4.0-42-generic         | 18        | 2.13%   |
| 5.4.0-48-generic         | 12        | 1.42%   |
| 5.4.0-58-generic         | 11        | 1.3%    |
| 5.3.0-40-generic         | 10        | 1.18%   |
| 5.13.0-30-generic        | 10        | 1.18%   |
| 5.4.0-52-generic         | 9         | 1.07%   |
| 5.4.0-40-generic         | 9         | 1.07%   |
| 5.16.7-desktop-1omv4003  | 9         | 1.07%   |
| 5.11.0-37-generic        | 9         | 1.07%   |
| 5.8.0-48-generic         | 8         | 0.95%   |
| 5.13.0-7614-generic      | 8         | 0.95%   |
| 5.4.0-70-generic         | 7         | 0.83%   |
| 5.4.0-65-generic         | 7         | 0.83%   |
| 5.13.0-39-generic        | 7         | 0.83%   |
| 5.10.0-8-amd64           | 7         | 0.83%   |
| 4.15.0-47-generic        | 7         | 0.83%   |
| 5.8.0-7630-generic       | 6         | 0.71%   |
| 5.4.0-7634-generic       | 6         | 0.71%   |
| 5.4.0-66-generic         | 6         | 0.71%   |
| 5.4.0-54-generic         | 6         | 0.71%   |
| 5.4.0-33-generic         | 6         | 0.71%   |
| 5.3.0-51-generic         | 6         | 0.71%   |
| 5.3.0-28-generic         | 6         | 0.71%   |
| 5.11.0-41-generic        | 6         | 0.71%   |
| 5.4.0-56-generic         | 5         | 0.59%   |
| 5.4.0-37-generic         | 5         | 0.59%   |
| 5.4.0-29-generic         | 5         | 0.59%   |
| 5.11.0-7620-generic      | 5         | 0.59%   |
| 5.11.0-7614-generic      | 5         | 0.59%   |
| 5.11.0-40-generic        | 5         | 0.59%   |
| 5.11.0-38-generic        | 5         | 0.59%   |
| 5.11.0-27-generic        | 5         | 0.59%   |
| 5.0.0-25-generic         | 5         | 0.59%   |
| 5.8.0-7642-generic       | 4         | 0.47%   |
| 5.8.0-50-generic         | 4         | 0.47%   |
| 5.4.0-90-generic         | 4         | 0.47%   |
| 5.4.0-7642-generic       | 4         | 0.47%   |
| 5.4.0-7626-generic       | 4         | 0.47%   |
| 5.4.0-67-generic         | 4         | 0.47%   |
| 5.3.0-42-generic         | 4         | 0.47%   |
| 5.15.5-76051505-generic  | 4         | 0.47%   |
| 5.15.15-76051515-generic | 4         | 0.47%   |
| 5.15.0-25-generic        | 4         | 0.47%   |
| 5.13.0-7620-generic      | 4         | 0.47%   |
| 5.13.0-28-generic        | 4         | 0.47%   |
| 5.11.0-43-generic        | 4         | 0.47%   |
| 5.11.0-34-generic        | 4         | 0.47%   |
| 5.11.0-18-generic        | 4         | 0.47%   |
| 5.10.0-9-amd64           | 4         | 0.47%   |
| 5.0.0-29-generic         | 4         | 0.47%   |
| 5.0.0-27-generic         | 4         | 0.47%   |
| 5.0.0-20-generic         | 4         | 0.47%   |
| 5.0.0-13-generic         | 4         | 0.47%   |
| 4.18.16-desktop-1bP      | 4         | 0.47%   |
| 4.18.0-25-generic        | 4         | 0.47%   |
| 5.9.14-arch1-1           | 3         | 0.36%   |
| 5.8.0-44-generic         | 3         | 0.36%   |
| 5.8.0-43-generic         | 3         | 0.36%   |
| 5.8.0-41-generic         | 3         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 169       | 21.26%  |
| 5.11.0  | 66        | 8.3%    |
| 5.13.0  | 52        | 6.54%   |
| 5.8.0   | 50        | 6.29%   |
| 5.3.0   | 46        | 5.79%   |
| 4.15.0  | 45        | 5.66%   |
| 5.0.0   | 34        | 4.28%   |
| 5.10.0  | 27        | 3.4%    |
| 4.18.0  | 23        | 2.89%   |
| 5.10.14 | 21        | 2.64%   |
| 5.15.0  | 11        | 1.38%   |
| 5.16.7  | 10        | 1.26%   |
| 5.7.0   | 5         | 0.63%   |
| 5.17.1  | 4         | 0.5%    |
| 5.16.2  | 4         | 0.5%    |
| 5.16.15 | 4         | 0.5%    |
| 5.16.0  | 4         | 0.5%    |
| 5.15.5  | 4         | 0.5%    |
| 5.15.15 | 4         | 0.5%    |
| 4.18.16 | 4         | 0.5%    |
| 5.9.14  | 3         | 0.38%   |
| 5.5.8   | 3         | 0.38%   |
| 5.17.5  | 3         | 0.38%   |
| 5.16.18 | 3         | 0.38%   |
| 5.15.8  | 3         | 0.38%   |
| 5.15.7  | 3         | 0.38%   |
| 5.15.11 | 3         | 0.38%   |
| 5.14.11 | 3         | 0.38%   |
| 5.12.4  | 3         | 0.38%   |
| 5.11.11 | 3         | 0.38%   |
| 4.19.0  | 3         | 0.38%   |
| 5.9.8   | 2         | 0.25%   |
| 5.9.3   | 2         | 0.25%   |
| 5.9.11  | 2         | 0.25%   |
| 5.9.0   | 2         | 0.25%   |
| 5.8.3   | 2         | 0.25%   |
| 5.8.11  | 2         | 0.25%   |
| 5.8.1   | 2         | 0.25%   |
| 5.6.14  | 2         | 0.25%   |
| 5.6.0   | 2         | 0.25%   |
| 5.16.11 | 2         | 0.25%   |
| 5.16.10 | 2         | 0.25%   |
| 5.15.2  | 2         | 0.25%   |
| 5.15.12 | 2         | 0.25%   |
| 5.14.9  | 2         | 0.25%   |
| 5.14.18 | 2         | 0.25%   |
| 5.14.15 | 2         | 0.25%   |
| 5.14.0  | 2         | 0.25%   |
| 5.13.8  | 2         | 0.25%   |
| 5.13.4  | 2         | 0.25%   |
| 5.13.13 | 2         | 0.25%   |
| 5.13.10 | 2         | 0.25%   |
| 5.12.9  | 2         | 0.25%   |
| 5.12.3  | 2         | 0.25%   |
| 5.12.12 | 2         | 0.25%   |
| 5.10.16 | 2         | 0.25%   |
| 4.9.60  | 2         | 0.25%   |
| 4.9.20  | 2         | 0.25%   |
| 4.18.12 | 2         | 0.25%   |
| 5.9.15  | 1         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 175       | 22.32%  |
| 5.11    | 77        | 9.82%   |
| 5.10    | 64        | 8.16%   |
| 5.8     | 62        | 7.91%   |
| 5.13    | 62        | 7.91%   |
| 5.3     | 52        | 6.63%   |
| 4.15    | 45        | 5.74%   |
| 5.15    | 40        | 5.1%    |
| 5.0     | 36        | 4.59%   |
| 5.16    | 33        | 4.21%   |
| 4.18    | 29        | 3.7%    |
| 5.9     | 14        | 1.79%   |
| 5.12    | 14        | 1.79%   |
| 5.17    | 12        | 1.53%   |
| 5.14    | 12        | 1.53%   |
| 5.7     | 11        | 1.4%    |
| 5.6     | 11        | 1.4%    |
| 4.19    | 8         | 1.02%   |
| 5.5     | 7         | 0.89%   |
| 5.2     | 6         | 0.77%   |
| 4.9     | 5         | 0.64%   |
| 5.1     | 4         | 0.51%   |
| 4.1     | 2         | 0.26%   |
| 4.20    | 1         | 0.13%   |
| 4.14    | 1         | 0.13%   |
| 3.10    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 704       | 98.05%  |
| i686   | 14        | 1.95%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 369       | 49.07%  |
| Unknown         | 124       | 16.49%  |
| KDE5            | 71        | 9.44%   |
| XFCE            | 50        | 6.65%   |
| X-Cinnamon      | 41        | 5.45%   |
| KDE             | 29        | 3.86%   |
| MATE            | 19        | 2.53%   |
| Cinnamon        | 9         | 1.2%    |
| LXQt            | 5         | 0.66%   |
| i3              | 5         | 0.66%   |
| Pantheon        | 4         | 0.53%   |
| LXDE            | 4         | 0.53%   |
| Unity           | 3         | 0.4%    |
| sway            | 3         | 0.4%    |
| KDE4            | 3         | 0.4%    |
| qtile           | 2         | 0.27%   |
| DWM             | 2         | 0.27%   |
| Deepin          | 2         | 0.27%   |
| Budgie          | 2         | 0.27%   |
| Trinity         | 1         | 0.13%   |
| spectrwm        | 1         | 0.13%   |
| GNOME Flashback | 1         | 0.13%   |
| bspwm           | 1         | 0.13%   |
| awesome         | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 558       | 75.71%  |
| Wayland | 96        | 13.03%  |
| Unknown | 70        | 9.5%    |
| Tty     | 13        | 1.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 452       | 60.59%  |
| GDM     | 98        | 13.14%  |
| SDDM    | 79        | 10.59%  |
| LightDM | 44        | 5.9%    |
| GDM3    | 39        | 5.23%   |
| TDM     | 28        | 3.75%   |
| KDM     | 3         | 0.4%    |
| XDM     | 2         | 0.27%   |
| Ly      | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 340       | 46.01%  |
| sv_SE      | 201       | 27.2%   |
| Unknown    | 117       | 15.83%  |
| en_GB      | 35        | 4.74%   |
| C          | 9         | 1.22%   |
| de_DE      | 8         | 1.08%   |
| ru_RU      | 5         | 0.68%   |
| pl_PL      | 3         | 0.41%   |
| fr_FR      | 3         | 0.41%   |
| lt_LT      | 2         | 0.27%   |
| en_SE      | 2         | 0.27%   |
| en_DK      | 2         | 0.27%   |
| en_CA      | 2         | 0.27%   |
| uk_UA      | 1         | 0.14%   |
| sv_SE.UTF8 | 1         | 0.14%   |
| sv_FI      | 1         | 0.14%   |
| POSIX      | 1         | 0.14%   |
| nn_NO      | 1         | 0.14%   |
| nb_NO      | 1         | 0.14%   |
| hu_HU      | 1         | 0.14%   |
| fi_FI      | 1         | 0.14%   |
| es_ES      | 1         | 0.14%   |
| bg_BG      | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 375       | 51.02%  |
| BIOS | 360       | 48.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 574       | 78.2%   |
| Btrfs   | 59        | 8.04%   |
| Overlay | 47        | 6.4%    |
| Unknown | 31        | 4.22%   |
| Xfs     | 9         | 1.23%   |
| Zfs     | 7         | 0.95%   |
| Ext2    | 6         | 0.82%   |
| F2fs    | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 459       | 62.7%   |
| GPT     | 214       | 29.23%  |
| MBR     | 59        | 8.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 661       | 91.05%  |
| Yes       | 65        | 8.95%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 582       | 80.17%  |
| Yes       | 144       | 19.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 171       | 23.82%  |
| Hewlett-Packard      | 155       | 21.59%  |
| Dell                 | 113       | 15.74%  |
| ASUSTek Computer     | 92        | 12.81%  |
| Acer                 | 49        | 6.82%   |
| Apple                | 26        | 3.62%   |
| Toshiba              | 14        | 1.95%   |
| Sony                 | 14        | 1.95%   |
| MSI                  | 14        | 1.95%   |
| Packard Bell         | 8         | 1.11%   |
| Notebook             | 7         | 0.97%   |
| Samsung Electronics  | 6         | 0.84%   |
| Google               | 6         | 0.84%   |
| Fujitsu              | 6         | 0.84%   |
| Unknown              | 5         | 0.7%    |
| HUAWEI               | 3         | 0.42%   |
| Fujitsu Siemens      | 3         | 0.42%   |
| TUXEDO               | 2         | 0.28%   |
| Razer                | 2         | 0.28%   |
| PC Specialist        | 2         | 0.28%   |
| eMachines            | 2         | 0.28%   |
| Alienware            | 2         | 0.28%   |
| ZEPTO                | 1         | 0.14%   |
| YJKC                 | 1         | 0.14%   |
| Timi                 | 1         | 0.14%   |
| System76             | 1         | 0.14%   |
| Star Labs            | 1         | 0.14%   |
| On by NetOnNet       | 1         | 0.14%   |
| LG Electronics       | 1         | 0.14%   |
| Intel Client Systems | 1         | 0.14%   |
| Intel                | 1         | 0.14%   |
| GOCLEVER             | 1         | 0.14%   |
| Gigabyte Technology  | 1         | 0.14%   |
| GIADA                | 1         | 0.14%   |
| EUROCOM              | 1         | 0.14%   |
| Compal               | 1         | 0.14%   |
| Clevo                | 1         | 0.14%   |
| BOX                  | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell Precision 5540                  | 6         | 0.84%   |
| Unknown                              | 6         | 0.84%   |
| HP EliteBook Folio 9470m             | 5         | 0.7%    |
| Apple MacBookPro11,3                 | 5         | 0.7%    |
| HP Pavilion 15                       | 4         | 0.56%   |
| HP EliteBook 840 G2                  | 4         | 0.56%   |
| Dell XPS 15 9570                     | 4         | 0.56%   |
| Dell XPS 15 9500                     | 4         | 0.56%   |
| Dell XPS 13 9310                     | 4         | 0.56%   |
| Apple MacBookAir7,2                  | 4         | 0.56%   |
| Acer Aspire V3-571                   | 4         | 0.56%   |
| Lenovo Z50-70 20354                  | 3         | 0.42%   |
| HP ProBook 430 G1                    | 3         | 0.42%   |
| HP Pavilion Notebook                 | 3         | 0.42%   |
| HP Pavilion dv7                      | 3         | 0.42%   |
| HP Pavilion dv6                      | 3         | 0.42%   |
| HP Pavilion 17                       | 3         | 0.42%   |
| HP Laptop 15-db0xxx                  | 3         | 0.42%   |
| HP ENVY 15                           | 3         | 0.42%   |
| HP EliteBook 8440p                   | 3         | 0.42%   |
| HP EliteBook 840 G6                  | 3         | 0.42%   |
| Dell XPS 15 7590                     | 3         | 0.42%   |
| Dell XPS 13 9370                     | 3         | 0.42%   |
| Dell Latitude E7440                  | 3         | 0.42%   |
| Dell Latitude E6430                  | 3         | 0.42%   |
| Dell Latitude 5480                   | 3         | 0.42%   |
| Acer Aspire 5750G                    | 3         | 0.42%   |
| Lenovo Yoga Slim 7 14ARE05 82A2      | 2         | 0.28%   |
| Lenovo ThinkPad X220 4286CTO         | 2         | 0.28%   |
| Lenovo ThinkPad T490 20N2005VMX      | 2         | 0.28%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 2         | 0.28%   |
| Lenovo G50-80 80E5                   | 2         | 0.28%   |
| Lenovo G50-30 80G0                   | 2         | 0.28%   |
| Lenovo B50-30 80ES                   | 2         | 0.28%   |
| Lenovo B50-10 80QR                   | 2         | 0.28%   |
| HUAWEI KLVL-WXX9                     | 2         | 0.28%   |
| HP ZBook Studio G5                   | 2         | 0.28%   |
| HP ZBook 15 G2                       | 2         | 0.28%   |
| HP ZBook 15                          | 2         | 0.28%   |
| HP ProBook 650 G1                    | 2         | 0.28%   |
| HP ProBook 6460b                     | 2         | 0.28%   |
| HP ProBook 6450b                     | 2         | 0.28%   |
| HP ProBook 640 G1                    | 2         | 0.28%   |
| HP ProBook 4540s                     | 2         | 0.28%   |
| HP ProBook 4330s                     | 2         | 0.28%   |
| HP Pavilion dv6500                   | 2         | 0.28%   |
| HP Laptop 15-bw0xx                   | 2         | 0.28%   |
| HP EliteBook 850 G5                  | 2         | 0.28%   |
| HP EliteBook 850 G3                  | 2         | 0.28%   |
| HP EliteBook 8460p                   | 2         | 0.28%   |
| HP EliteBook 840 G8 Notebook PC      | 2         | 0.28%   |
| HP EliteBook 840 G3                  | 2         | 0.28%   |
| HP EliteBook 840 G1                  | 2         | 0.28%   |
| HP EliteBook 830 G6                  | 2         | 0.28%   |
| Google Reks                          | 2         | 0.28%   |
| Fujitsu Siemens ESPRIMO Mobile V5535 | 2         | 0.28%   |
| Fujitsu LIFEBOOK AH531/GFO           | 2         | 0.28%   |
| Dell XPS 17 9700                     | 2         | 0.28%   |
| Dell XPS 15 9560                     | 2         | 0.28%   |
| Dell XPS 13 9380                     | 2         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 111       | 15.46%  |
| HP EliteBook            | 56        | 7.8%    |
| Dell Latitude           | 43        | 5.99%   |
| Acer Aspire             | 32        | 4.46%   |
| Dell XPS                | 29        | 4.04%   |
| Dell Precision          | 28        | 3.9%    |
| HP Pavilion             | 25        | 3.48%   |
| HP ProBook              | 24        | 3.34%   |
| Lenovo IdeaPad          | 23        | 3.2%    |
| Toshiba Satellite       | 12        | 1.67%   |
| HP ZBook                | 11        | 1.53%   |
| HP Laptop               | 11        | 1.53%   |
| HP Compaq               | 11        | 1.53%   |
| ASUS VivoBook           | 10        | 1.39%   |
| Dell Inspiron           | 8         | 1.11%   |
| ASUS ZenBook            | 8         | 1.11%   |
| Packard Bell EasyNote   | 7         | 0.97%   |
| Lenovo Legion           | 7         | 0.97%   |
| ASUS ROG                | 7         | 0.97%   |
| Acer Swift              | 7         | 0.97%   |
| HP ENVY                 | 6         | 0.84%   |
| Apple MacBookPro11      | 6         | 0.84%   |
| Unknown                 | 6         | 0.84%   |
| Fujitsu LIFEBOOK        | 5         | 0.7%    |
| Dell Vostro             | 5         | 0.7%    |
| Lenovo Yoga             | 4         | 0.56%   |
| ASUS TUF                | 4         | 0.56%   |
| Apple MacBookAir7       | 4         | 0.56%   |
| Acer Nitro              | 4         | 0.56%   |
| Lenovo Z50-70           | 3         | 0.42%   |
| Acer Predator           | 3         | 0.42%   |
| MSI GF63                | 2         | 0.28%   |
| Lenovo G50-80           | 2         | 0.28%   |
| Lenovo G50-30           | 2         | 0.28%   |
| Lenovo B50-30           | 2         | 0.28%   |
| Lenovo B50-10           | 2         | 0.28%   |
| HUAWEI KLVL-WXX9        | 2         | 0.28%   |
| HP Presario             | 2         | 0.28%   |
| Google Reks             | 2         | 0.28%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.28%   |
| ASUS X580VD             | 2         | 0.28%   |
| ASUS X550LB             | 2         | 0.28%   |
| ASUS UX430UAR           | 2         | 0.28%   |
| ASUS UL30VT             | 2         | 0.28%   |
| ASUS N53SN              | 2         | 0.28%   |
| ASUS K53U               | 2         | 0.28%   |
| ASUS K53SD              | 2         | 0.28%   |
| ASUS G75VW              | 2         | 0.28%   |
| ASUS G751JY             | 2         | 0.28%   |
| ASUS G551JM             | 2         | 0.28%   |
| ASUS E200HA             | 2         | 0.28%   |
| Apple MacBookPro9       | 2         | 0.28%   |
| Apple MacBookPro8       | 2         | 0.28%   |
| Apple MacBookPro14      | 2         | 0.28%   |
| Apple MacBookPro12      | 2         | 0.28%   |
| ZEPTO ZNOTE             | 1         | 0.14%   |
| YJKC vBOOK              | 1         | 0.14%   |
| TUXEDO Pulse            | 1         | 0.14%   |
| TUXEDO InfinityBook     | 1         | 0.14%   |
| Toshiba TECRA           | 1         | 0.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 70        | 9.75%   |
| 2018 | 70        | 9.75%   |
| 2013 | 66        | 9.19%   |
| 2014 | 58        | 8.08%   |
| 2016 | 54        | 7.52%   |
| 2011 | 54        | 7.52%   |
| 2012 | 51        | 7.1%    |
| 2017 | 49        | 6.82%   |
| 2020 | 47        | 6.55%   |
| 2015 | 46        | 6.41%   |
| 2010 | 45        | 6.27%   |
| 2021 | 44        | 6.13%   |
| 2008 | 22        | 3.06%   |
| 2007 | 17        | 2.37%   |
| 2009 | 15        | 2.09%   |
| 2006 | 5         | 0.7%    |
| 2005 | 5         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 718       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 629       | 87%     |
| Enabled  | 94        | 13%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 712       | 99.16%  |
| Yes  | 6         | 0.84%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 206       | 28.45%  |
| 16.01-24.0  | 138       | 19.06%  |
| 3.01-4.0    | 134       | 18.51%  |
| 8.01-16.0   | 127       | 17.54%  |
| 32.01-64.0  | 71        | 9.81%   |
| 1.01-2.0    | 28        | 3.87%   |
| 2.01-3.0    | 7         | 0.97%   |
| 24.01-32.0  | 6         | 0.83%   |
| 0.51-1.0    | 5         | 0.69%   |
| 64.01-256.0 | 2         | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 296       | 37.52%  |
| 2.01-3.0   | 197       | 24.97%  |
| 4.01-8.0   | 117       | 14.83%  |
| 3.01-4.0   | 100       | 12.67%  |
| 0.51-1.0   | 39        | 4.94%   |
| 8.01-16.0  | 24        | 3.04%   |
| 0.01-0.5   | 10        | 1.27%   |
| 16.01-24.0 | 6         | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 577       | 79.15%  |
| 2      | 131       | 17.97%  |
| 3      | 13        | 1.78%   |
| 4      | 4         | 0.55%   |
| 0      | 4         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 488       | 67.68%  |
| Yes       | 233       | 32.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 592       | 82.11%  |
| No        | 129       | 17.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 709       | 98.75%  |
| No        | 9         | 1.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 579       | 79.75%  |
| No        | 147       | 20.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Sweden  | 718       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Stockholm               | 132       | 17.1%   |
| Gothenburg              | 75        | 9.72%   |
| Malmo                   | 34        | 4.4%    |
| Uppsala                 | 25        | 3.24%   |
| Linköping              | 15        | 1.94%   |
| Lund                    | 13        | 1.68%   |
| Bromma                  | 12        | 1.55%   |
| Huddinge                | 11        | 1.42%   |
| Norrköping             | 10        | 1.3%    |
| Bandhagen               | 10        | 1.3%    |
| Vaestra Froelunda       | 8         | 1.04%   |
| Solna                   | 8         | 1.04%   |
| Sollentuna              | 8         | 1.04%   |
| Haegersten              | 8         | 1.04%   |
| Karlstad                | 7         | 0.91%   |
| Helsingborg             | 7         | 0.91%   |
| Vaxjo                   | 6         | 0.78%   |
| Umeå                   | 6         | 0.78%   |
| Staffanstorp            | 6         | 0.78%   |
| Moelndal                | 6         | 0.78%   |
| Mjoelby                 | 6         | 0.78%   |
| Landskrona              | 6         | 0.78%   |
| Kista                   | 6         | 0.78%   |
| Halmstad                | 6         | 0.78%   |
| Sundbyberg              | 5         | 0.65%   |
| Spanga                  | 5         | 0.65%   |
| Örebro                 | 5         | 0.65%   |
| Norsborg                | 5         | 0.65%   |
| Katrineholm             | 5         | 0.65%   |
| Jönköping             | 5         | 0.65%   |
| Handen                  | 5         | 0.65%   |
| Akersberga              | 5         | 0.65%   |
| Västerås              | 4         | 0.52%   |
| Vaennaes                | 4         | 0.52%   |
| Upplands Vasby          | 4         | 0.52%   |
| Tyreso Strand           | 4         | 0.52%   |
| Taby                    | 4         | 0.52%   |
| Södertälje            | 4         | 0.52%   |
| Knivsta                 | 4         | 0.52%   |
| Hässleholm             | 4         | 0.52%   |
| Falun                   | 4         | 0.52%   |
| Eskilstuna              | 4         | 0.52%   |
| Ängelholm              | 4         | 0.52%   |
| Alvsjo                  | 4         | 0.52%   |
| Vendelso                | 3         | 0.39%   |
| Sveg                    | 3         | 0.39%   |
| Skövde                 | 3         | 0.39%   |
| Sigtuna                 | 3         | 0.39%   |
| Örnsköldsvik          | 3         | 0.39%   |
| Nyköping               | 3         | 0.39%   |
| Norrtaelje              | 3         | 0.39%   |
| Motala                  | 3         | 0.39%   |
| Maersta                 | 3         | 0.39%   |
| Lidkoeping              | 3         | 0.39%   |
| Kungälv                | 3         | 0.39%   |
| Kristinehamn            | 3         | 0.39%   |
| Karlskrona              | 3         | 0.39%   |
| Kalmar                  | 3         | 0.39%   |
| Järfälla Municipality | 3         | 0.39%   |
| Jakobsberg              | 3         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 170       | 216    | 19.79%  |
| WDC                            | 92        | 113    | 10.71%  |
| Toshiba                        | 70        | 88     | 8.15%   |
| Seagate                        | 66        | 76     | 7.68%   |
| Sandisk                        | 60        | 78     | 6.98%   |
| Intel                          | 60        | 67     | 6.98%   |
| Kingston                       | 57        | 73     | 6.64%   |
| Unknown                        | 43        | 55     | 5.01%   |
| SK Hynix                       | 36        | 39     | 4.19%   |
| Micron Technology              | 31        | 36     | 3.61%   |
| Hitachi                        | 28        | 33     | 3.26%   |
| HGST                           | 23        | 28     | 2.68%   |
| Crucial                        | 16        | 21     | 1.86%   |
| LITEON                         | 15        | 19     | 1.75%   |
| Apple                          | 15        | 17     | 1.75%   |
| OCZ                            | 9         | 9      | 1.05%   |
| LITEONIT                       | 6         | 10     | 0.7%    |
| KIOXIA                         | 6         | 6      | 0.7%    |
| Phison                         | 4         | 4      | 0.47%   |
| A-DATA Technology              | 4         | 4      | 0.47%   |
| Transcend                      | 3         | 3      | 0.35%   |
| Silicon Motion                 | 3         | 14     | 0.35%   |
| Lenovo                         | 3         | 3      | 0.35%   |
| Intenso                        | 3         | 3      | 0.35%   |
| Fujitsu                        | 3         | 4      | 0.35%   |
| Union Memory                   | 2         | 2      | 0.23%   |
| ROG                            | 2         | 2      | 0.23%   |
| JMicron                        | 2         | 2      | 0.23%   |
| Corsair                        | 2         | 2      | 0.23%   |
| China                          | 2         | 2      | 0.23%   |
| ASMT                           | 2         | 2      | 0.23%   |
| Unknown                        | 2         | 2      | 0.23%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.12%   |
| TO Exter                       | 1         | 1      | 0.12%   |
| Star                           | 1         | 1      | 0.12%   |
| Solid State Storage Technology | 1         | 1      | 0.12%   |
| Realtek                        | 1         | 1      | 0.12%   |
| Radeon                         | 1         | 1      | 0.12%   |
| PNY                            | 1         | 1      | 0.12%   |
| OCZ-VERTEX3                    | 1         | 1      | 0.12%   |
| MyDigitalSSD                   | 1         | 1      | 0.12%   |
| Micron/Crucial Technology      | 1         | 1      | 0.12%   |
| MAXTOR                         | 1         | 1      | 0.12%   |
| Lite-On                        | 1         | 1      | 0.12%   |
| LaCie                          | 1         | 1      | 0.12%   |
| KIOXIA-EXCERIA                 | 1         | 1      | 0.12%   |
| KingSpec                       | 1         | 1      | 0.12%   |
| KingFast                       | 1         | 1      | 0.12%   |
| Hewlett-Packard                | 1         | 2      | 0.12%   |
| GOODRAM                        | 1         | 1      | 0.12%   |
| BHT                            | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba NVMe SSD Drive 512GB         | 12        | 1.37%   |
| SK Hynix NVMe SSD Drive 512GB        | 10        | 1.14%   |
| Sandisk NVMe SSD Drive 512GB         | 9         | 1.03%   |
| Samsung NVMe SSD Drive 256GB         | 9         | 1.03%   |
| Intel SSDPEKKW256G7 256GB            | 9         | 1.03%   |
| Samsung NVMe SSD Drive 512GB         | 8         | 0.91%   |
| HGST HTS721010A9E630 1TB             | 8         | 0.91%   |
| Unknown MMC Card  32GB               | 7         | 0.8%    |
| Unknown MMC Card  16GB               | 7         | 0.8%    |
| Seagate ST9500325AS 500GB            | 7         | 0.8%    |
| Samsung SSD 850 EVO 250GB            | 7         | 0.8%    |
| Samsung NVMe SSD Drive 1024GB        | 7         | 0.8%    |
| Kingston SA400S37480G 480GB SSD      | 7         | 0.8%    |
| Kingston SA400S37120G 120GB SSD      | 7         | 0.8%    |
| WDC WD10JPVX-22JC3T0 1TB             | 6         | 0.68%   |
| Unknown MMC Card  64GB               | 6         | 0.68%   |
| Samsung SSD 970 EVO Plus 1TB         | 6         | 0.68%   |
| Samsung SSD 850 EVO 500GB            | 6         | 0.68%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 6         | 0.68%   |
| Kingston SUV400S37120G 120GB SSD     | 6         | 0.68%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 5         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 0.57%   |
| Intel SSDPEKNW010T8 1TB              | 5         | 0.57%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 4         | 0.46%   |
| Toshiba MQ04ABF100 1TB               | 4         | 0.46%   |
| Toshiba MQ01ACF032 320GB             | 4         | 0.46%   |
| Toshiba MQ01ABD100 1TB               | 4         | 0.46%   |
| Seagate ST9320423AS 320GB            | 4         | 0.46%   |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 0.46%   |
| Sandisk NVMe SSD Drive 256GB         | 4         | 0.46%   |
| Sandisk NVMe SSD Drive 1TB           | 4         | 0.46%   |
| Sandisk NVMe SSD Drive 1024GB        | 4         | 0.46%   |
| Samsung SSD 840 EVO 250GB            | 4         | 0.46%   |
| Samsung MZYLF128HCHP-000L2 128GB SSD | 4         | 0.46%   |
| Micron NVMe SSD Drive 512GB          | 4         | 0.46%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 0.46%   |
| Hitachi HTS545032B9A300 320GB        | 4         | 0.46%   |
| HGST HTS545050A7E680 500GB           | 4         | 0.46%   |
| Apple SSD SM0512F 500GB              | 4         | 0.46%   |
| Apple SSD SM0128G 121GB              | 4         | 0.46%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD     | 3         | 0.34%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 3         | 0.34%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 3         | 0.34%   |
| Unknown MMC Card  128GB              | 3         | 0.34%   |
| Toshiba MQ01ABF050 500GB             | 3         | 0.34%   |
| SK Hynix SC311 SATA 256GB SSD        | 3         | 0.34%   |
| SK Hynix PC711 NVMe 512GB            | 3         | 0.34%   |
| Seagate ST9250410AS 250GB            | 3         | 0.34%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.34%   |
| Samsung SSD 860 EVO 500GB            | 3         | 0.34%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.34%   |
| Samsung SSD 840 EVO 500GB            | 3         | 0.34%   |
| Samsung NVMe SSD Drive 500GB         | 3         | 0.34%   |
| LITEON LCH-256V2S-HP 256GB SSD       | 3         | 0.34%   |
| Intel SSDSC2BF180A4H 180GB           | 3         | 0.34%   |
| Intel NVMe SSD Drive 512GB           | 3         | 0.34%   |
| Intel NVMe SSD Drive 1024GB          | 3         | 0.34%   |
| Hitachi HTS545025B9A300 250GB        | 3         | 0.34%   |
| HGST HTS725050A7E630 500GB           | 3         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 64        | 73     | 30.05%  |
| WDC                 | 55        | 69     | 25.82%  |
| Toshiba             | 33        | 40     | 15.49%  |
| Hitachi             | 28        | 33     | 13.15%  |
| HGST                | 23        | 28     | 10.8%   |
| Samsung Electronics | 3         | 3      | 1.41%   |
| Fujitsu             | 3         | 4      | 1.41%   |
| Apple               | 2         | 2      | 0.94%   |
| Unknown             | 1         | 1      | 0.47%   |
| ASMT                | 1         | 1      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 98        | 133    | 27.07%  |
| Kingston            | 47        | 62     | 12.98%  |
| SanDisk             | 38        | 48     | 10.5%   |
| Intel               | 37        | 40     | 10.22%  |
| Micron Technology   | 20        | 24     | 5.52%   |
| WDC                 | 17        | 22     | 4.7%    |
| Crucial             | 15        | 20     | 4.14%   |
| LITEON              | 14        | 18     | 3.87%   |
| SK Hynix            | 12        | 14     | 3.31%   |
| Apple               | 12        | 14     | 3.31%   |
| Toshiba             | 9         | 16     | 2.49%   |
| OCZ                 | 9         | 9      | 2.49%   |
| LITEONIT            | 6         | 10     | 1.66%   |
| Transcend           | 3         | 3      | 0.83%   |
| Intenso             | 3         | 3      | 0.83%   |
| Corsair             | 2         | 2      | 0.55%   |
| China               | 2         | 2      | 0.55%   |
| A-DATA Technology   | 2         | 2      | 0.55%   |
| Unknown             | 1         | 1      | 0.28%   |
| TO Exter            | 1         | 1      | 0.28%   |
| Star                | 1         | 1      | 0.28%   |
| Seagate             | 1         | 1      | 0.28%   |
| Radeon              | 1         | 1      | 0.28%   |
| PNY                 | 1         | 1      | 0.28%   |
| OCZ-VERTEX3         | 1         | 1      | 0.28%   |
| MyDigitalSSD        | 1         | 1      | 0.28%   |
| MAXTOR              | 1         | 1      | 0.28%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.28%   |
| KingSpec            | 1         | 1      | 0.28%   |
| KingFast            | 1         | 1      | 0.28%   |
| JMicron             | 1         | 1      | 0.28%   |
| GOODRAM             | 1         | 1      | 0.28%   |
| ASMT                | 1         | 1      | 0.28%   |
| Unknown             | 1         | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 335       | 458    | 41.21%  |
| NVMe    | 223       | 282    | 27.43%  |
| HDD     | 207       | 254    | 25.46%  |
| MMC     | 42        | 53     | 5.17%   |
| Unknown | 6         | 6      | 0.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 496       | 699    | 63.51%  |
| NVMe | 222       | 279    | 28.43%  |
| MMC  | 42        | 53     | 5.38%   |
| SAS  | 21        | 22     | 2.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 418       | 568    | 78.13%  |
| 0.51-1.0   | 109       | 135    | 20.37%  |
| 1.01-2.0   | 5         | 6      | 0.93%   |
| 3.01-4.0   | 2         | 2      | 0.37%   |
| 4.01-10.0  | 1         | 1      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 255       | 34.05%  |
| 251-500        | 196       | 26.17%  |
| 501-1000       | 90        | 12.02%  |
| 1-20           | 61        | 8.14%   |
| 51-100         | 42        | 5.61%   |
| 1001-2000      | 38        | 5.07%   |
| 21-50          | 27        | 3.6%    |
| Unknown        | 26        | 3.47%   |
| More than 3000 | 8         | 1.07%   |
| 2001-3000      | 6         | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 350       | 44.76%  |
| 21-50          | 125       | 15.98%  |
| 101-250        | 112       | 14.32%  |
| 51-100         | 86        | 11%     |
| 251-500        | 43        | 5.5%    |
| 501-1000       | 27        | 3.45%   |
| Unknown        | 26        | 3.32%   |
| 1001-2000      | 11        | 1.41%   |
| More than 3000 | 1         | 0.13%   |
| 2001-3000      | 1         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 4         | 4      | 12.5%   |
| Seagate ST9250410AS 250GB                           | 2         | 3      | 6.25%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 2         | 3      | 6.25%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 3.13%   |
| Union Memory UMIS RPJTJ128MED1MWX 128GB             | 1         | 1      | 3.13%   |
| Transcend TS240GMTS420S 240GB SSD                   | 1         | 1      | 3.13%   |
| Toshiba MK1633GSG 160GB                             | 1         | 1      | 3.13%   |
| SK Hynix SH920 mSATA 128GB SSD                      | 1         | 1      | 3.13%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 3.13%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 3.13%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 3.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 3.13%   |
| Samsung Electronics MZ7PA128HMCD-010L1 128GB SSD    | 1         | 1      | 3.13%   |
| OCZ AGILITY3 120GB SSD                              | 1         | 1      | 3.13%   |
| Micron Technology MTFDDAK512TBN-1AR1ZABHA 512GB SSD | 1         | 1      | 3.13%   |
| LITEONIT LMT-256M6M-HP 256GB SSD                    | 1         | 1      | 3.13%   |
| Intel SSDSCKJF180A5H RSED 180GB                     | 1         | 1      | 3.13%   |
| Intel SSDSC2BW480A4 480GB                           | 1         | 1      | 3.13%   |
| Intel SSDSC2BW240A4 240GB                           | 1         | 2      | 3.13%   |
| Intel SSDSA2BW160G3H 160GB                          | 1         | 1      | 3.13%   |
| Hitachi HTS543216L9A300 160GB                       | 1         | 1      | 3.13%   |
| Hitachi HTS542525K9SA00 250GB                       | 1         | 1      | 3.13%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 3.13%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 3.13%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 3.13%   |
| Corsair Force 3 SSD 240GB                           | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 31.25%  |
| Intel               | 4         | 5      | 12.5%   |
| Micron Technology   | 3         | 4      | 9.38%   |
| HGST                | 3         | 3      | 9.38%   |
| Samsung Electronics | 2         | 2      | 6.25%   |
| Hitachi             | 2         | 2      | 6.25%   |
| WDC                 | 1         | 1      | 3.13%   |
| Union Memory        | 1         | 1      | 3.13%   |
| Transcend           | 1         | 1      | 3.13%   |
| Toshiba             | 1         | 1      | 3.13%   |
| SK Hynix            | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| LITEONIT            | 1         | 1      | 3.13%   |
| Corsair             | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 11     | 58.82%  |
| HGST    | 3         | 3      | 17.65%  |
| Hitachi | 2         | 2      | 11.76%  |
| WDC     | 1         | 1      | 5.88%   |
| Toshiba | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 18     | 53.13%  |
| SSD  | 14        | 16     | 43.75%  |
| NVMe | 1         | 1      | 3.13%   |

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
| Detected | 489       | 718    | 64.68%  |
| Works    | 236       | 300    | 31.22%  |
| Malfunc  | 31        | 35     | 4.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 513       | 62.87%  |
| Samsung Electronics              | 83        | 10.17%  |
| AMD                              | 71        | 8.7%    |
| Sandisk                          | 40        | 4.9%    |
| Toshiba America Info Systems     | 31        | 3.8%    |
| SK Hynix                         | 23        | 2.82%   |
| Micron Technology                | 11        | 1.35%   |
| Kingston Technology Company      | 9         | 1.1%    |
| Phison Electronics               | 4         | 0.49%   |
| Nvidia                           | 4         | 0.49%   |
| KIOXIA                           | 4         | 0.49%   |
| Union Memory (Shenzhen)          | 3         | 0.37%   |
| Silicon Motion                   | 3         | 0.37%   |
| Silicon Integrated Systems [SiS] | 3         | 0.37%   |
| Lite-On Technology               | 3         | 0.37%   |
| Lenovo                           | 3         | 0.37%   |
| Apple                            | 2         | 0.25%   |
| ADATA Technology                 | 2         | 0.25%   |
| Solid State Storage Technology   | 1         | 0.12%   |
| Realtek Semiconductor            | 1         | 0.12%   |
| Micron/Crucial Technology        | 1         | 0.12%   |
| Marvell Technology Group         | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 65        | 7.46%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 60        | 6.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 52        | 5.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 45        | 5.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 45        | 5.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 42        | 4.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 41        | 4.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 34        | 3.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 32        | 3.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 27        | 3.1%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 20        | 2.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 19        | 2.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 16        | 1.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 14        | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 13        | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 13        | 1.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 12        | 1.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 1.38%   |
| Samsung NVMe SSD Controller 980                                                  | 11        | 1.26%   |
| Micron Non-Volatile memory controller                                            | 11        | 1.26%   |
| Intel Volume Management Device NVMe RAID Controller                              | 11        | 1.26%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 10        | 1.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 1.15%   |
| Intel SSD 660P Series                                                            | 9         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 1.03%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 8         | 0.92%   |
| SK Hynix Gold P31 SSD                                                            | 8         | 0.92%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 7         | 0.8%    |
| SK Hynix Non-Volatile memory controller                                          | 7         | 0.8%    |
| Samsung Electronics SATA controller                                              | 7         | 0.8%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 7         | 0.8%    |
| Intel SSD 600P Series                                                            | 7         | 0.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 0.8%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 6         | 0.69%   |
| Sandisk Non-Volatile memory controller                                           | 6         | 0.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 6         | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 6         | 0.69%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 5         | 0.57%   |
| Samsung Apple PCIe SSD                                                           | 5         | 0.57%   |
| Kingston Company A2000 NVMe SSD                                                  | 5         | 0.57%   |
| KIOXIA Non-Volatile memory controller                                            | 4         | 0.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 0.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 4         | 0.46%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 0.46%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 0.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 0.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4         | 0.46%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.34%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 3         | 0.34%   |
| Toshiba America Info Systems NVMe Controller                                     | 3         | 0.34%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 3         | 0.34%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 0.34%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 3         | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.34%   |
| Phison PS5013 E13 NVMe Controller                                                | 3         | 0.34%   |
| Lenovo Non-Volatile memory controller                                            | 3         | 0.34%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 0.34%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.34%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 3         | 0.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 503       | 59.6%   |
| NVMe | 225       | 26.66%  |
| RAID | 58        | 6.87%   |
| IDE  | 58        | 6.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 617       | 85.93%  |
| AMD    | 101       | 14.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz       | 15        | 2.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 14        | 1.95%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 12        | 1.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 12        | 1.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 11        | 1.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 11        | 1.53%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 10        | 1.39%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 10        | 1.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 9         | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 9         | 1.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 9         | 1.25%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 8         | 1.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 1.11%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 7         | 0.97%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 7         | 0.97%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 7         | 0.97%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 7         | 0.97%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 7         | 0.97%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 7         | 0.97%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 6         | 0.84%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 6         | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 6         | 0.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 6         | 0.84%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 6         | 0.84%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 6         | 0.84%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 6         | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 6         | 0.84%   |
| Intel Core i7-9850H CPU @ 2.60GHz       | 5         | 0.7%    |
| Intel Core i7-8850H CPU @ 2.60GHz       | 5         | 0.7%    |
| Intel Core i7-8650U CPU @ 1.90GHz       | 5         | 0.7%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 5         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz       | 5         | 0.7%    |
| Intel Core i5-9300H CPU @ 2.40GHz       | 5         | 0.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz       | 5         | 0.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 5         | 0.7%    |
| Intel Core i3-2310M CPU @ 2.10GHz       | 5         | 0.7%    |
| AMD E-450 APU with Radeon HD Graphics   | 5         | 0.7%    |
| Intel Genuine CPU U7300 @ 1.30GHz       | 4         | 0.56%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 4         | 0.56%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 4         | 0.56%   |
| Intel Core i7-4960HQ CPU @ 2.60GHz      | 4         | 0.56%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 4         | 0.56%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 4         | 0.56%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 4         | 0.56%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 4         | 0.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 4         | 0.56%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 4         | 0.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 4         | 0.56%   |
| Intel Core i7 CPU M 620 @ 2.67GHz       | 4         | 0.56%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 4         | 0.56%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 4         | 0.56%   |
| Intel Core i5-7440HQ CPU @ 2.80GHz      | 4         | 0.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 4         | 0.56%   |
| Intel Core i5-4210M CPU @ 2.60GHz       | 4         | 0.56%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 4         | 0.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 4         | 0.56%   |
| Intel Core i5 CPU M 540 @ 2.53GHz       | 4         | 0.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 4         | 0.56%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 4         | 0.56%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz    | 4         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 230       | 32.03%  |
| Intel Core i5                  | 194       | 27.02%  |
| Intel Core i3                  | 43        | 5.99%   |
| Intel Core 2 Duo               | 34        | 4.74%   |
| Other                          | 32        | 4.46%   |
| Intel Celeron                  | 26        | 3.62%   |
| AMD Ryzen 7                    | 21        | 2.92%   |
| AMD Ryzen 5                    | 16        | 2.23%   |
| Intel Pentium                  | 12        | 1.67%   |
| Intel Atom                     | 12        | 1.67%   |
| Intel Genuine                  | 9         | 1.25%   |
| AMD Ryzen 3                    | 8         | 1.11%   |
| AMD A6                         | 8         | 1.11%   |
| Intel Core 2                   | 6         | 0.84%   |
| AMD E1                         | 6         | 0.84%   |
| AMD A8                         | 6         | 0.84%   |
| Intel Core i9                  | 5         | 0.7%    |
| AMD E                          | 5         | 0.7%    |
| AMD A10                        | 5         | 0.7%    |
| AMD Ryzen 9                    | 4         | 0.56%   |
| AMD A4                         | 4         | 0.56%   |
| Intel Xeon                     | 3         | 0.42%   |
| Intel Pentium Dual             | 3         | 0.42%   |
| AMD Ryzen 7 PRO                | 3         | 0.42%   |
| Intel Pentium Silver           | 2         | 0.28%   |
| Intel Pentium M                | 2         | 0.28%   |
| Intel Core m3                  | 2         | 0.28%   |
| Intel Celeron Dual-Core        | 2         | 0.28%   |
| AMD Ryzen 5 PRO                | 2         | 0.28%   |
| Intel Pentium Dual-Core        | 1         | 0.14%   |
| Intel Core m5                  | 1         | 0.14%   |
| Intel Celeron M                | 1         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.14%   |
| AMD Turion II Dual-Core        | 1         | 0.14%   |
| AMD Turion 64 Mobile           | 1         | 0.14%   |
| AMD Quad-Core                  | 1         | 0.14%   |
| AMD PRO A10                    | 1         | 0.14%   |
| AMD Mobile Sempron             | 1         | 0.14%   |
| AMD E2                         | 1         | 0.14%   |
| AMD Athlon II Dual-Core        | 1         | 0.14%   |
| AMD Athlon II                  | 1         | 0.14%   |
| AMD Athlon 64 X2               | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 386       | 53.76%  |
| 4      | 239       | 33.29%  |
| 6      | 51        | 7.1%    |
| 8      | 31        | 4.32%   |
| 1      | 11        | 1.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 718       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 564       | 78.55%  |
| 1      | 154       | 21.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 697       | 96.81%  |
| Unknown        | 16        | 2.22%   |
| 32-bit         | 7         | 0.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 149       | 20.14%  |
| 0x306a9    | 43        | 5.81%   |
| 0x40651    | 41        | 5.54%   |
| 0x206a7    | 38        | 5.14%   |
| 0x306c3    | 35        | 4.73%   |
| 0x306d4    | 30        | 4.05%   |
| 0x406e3    | 29        | 3.92%   |
| 0x806e9    | 26        | 3.51%   |
| 0x806ea    | 25        | 3.38%   |
| 0x806ec    | 24        | 3.24%   |
| 0x20655    | 22        | 2.97%   |
| 0x1067a    | 22        | 2.97%   |
| 0x906ea    | 21        | 2.84%   |
| 0x806c1    | 20        | 2.7%    |
| 0x906e9    | 19        | 2.57%   |
| 0x6fd      | 10        | 1.35%   |
| 0x806eb    | 9         | 1.22%   |
| 0x0700010f | 9         | 1.22%   |
| 0xa0652    | 8         | 1.08%   |
| 0x406c4    | 8         | 1.08%   |
| 0x0810100b | 8         | 1.08%   |
| 0x506e3    | 7         | 0.95%   |
| 0x30678    | 7         | 0.95%   |
| 0x05000119 | 7         | 0.95%   |
| 0x906ed    | 6         | 0.81%   |
| 0x6f6      | 6         | 0.81%   |
| 0x20652    | 6         | 0.81%   |
| 0x08600106 | 6         | 0.81%   |
| 0x08108109 | 6         | 0.81%   |
| 0x6fb      | 5         | 0.68%   |
| 0x40661    | 5         | 0.68%   |
| 0x10676    | 5         | 0.68%   |
| 0x0a50000c | 5         | 0.68%   |
| 0x08108102 | 5         | 0.68%   |
| 0x06001119 | 5         | 0.68%   |
| 0x806d1    | 4         | 0.54%   |
| 0x30673    | 4         | 0.54%   |
| 0x08608103 | 4         | 0.54%   |
| 0x06006705 | 4         | 0.54%   |
| 0x706e5    | 3         | 0.41%   |
| 0x6d8      | 3         | 0.41%   |
| 0x406c3    | 3         | 0.41%   |
| 0x106e5    | 3         | 0.41%   |
| 0x106ca    | 3         | 0.41%   |
| 0x06006110 | 3         | 0.41%   |
| 0x706a8    | 2         | 0.27%   |
| 0x706a1    | 2         | 0.27%   |
| 0x10661    | 2         | 0.27%   |
| 0x08608102 | 2         | 0.27%   |
| 0x08600102 | 2         | 0.27%   |
| 0x07030104 | 2         | 0.27%   |
| 0x06006704 | 2         | 0.27%   |
| 0x03000027 | 2         | 0.27%   |
| 0x6fa      | 1         | 0.14%   |
| 0x6e8      | 1         | 0.14%   |
| 0x506c9    | 1         | 0.14%   |
| 0x306e4    | 1         | 0.14%   |
| 0x30661    | 1         | 0.14%   |
| 0x106c2    | 1         | 0.14%   |
| 0x0a50000b | 1         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 166       | 23.12%  |
| Haswell         | 91        | 12.67%  |
| IvyBridge       | 55        | 7.66%   |
| SandyBridge     | 51        | 7.1%    |
| Skylake         | 44        | 6.13%   |
| Broadwell       | 35        | 4.87%   |
| Westmere        | 32        | 4.46%   |
| Penryn          | 29        | 4.04%   |
| Core            | 27        | 3.76%   |
| TigerLake       | 25        | 3.48%   |
| Silvermont      | 25        | 3.48%   |
| Zen+            | 14        | 1.95%   |
| Zen 2           | 13        | 1.81%   |
| CometLake       | 12        | 1.67%   |
| Zen 3           | 11        | 1.53%   |
| Excavator       | 10        | 1.39%   |
| Zen             | 9         | 1.25%   |
| Jaguar          | 9         | 1.25%   |
| Unknown         | 9         | 1.25%   |
| Piledriver      | 6         | 0.84%   |
| IceLake         | 6         | 0.84%   |
| Bobcat          | 6         | 0.84%   |
| Puma            | 5         | 0.7%    |
| Bonnell         | 5         | 0.7%    |
| P6              | 4         | 0.56%   |
| Goldmont plus   | 4         | 0.56%   |
| Nehalem         | 3         | 0.42%   |
| K8 Hammer       | 3         | 0.42%   |
| K10 Llano       | 3         | 0.42%   |
| K10             | 3         | 0.42%   |
| Goldmont        | 2         | 0.28%   |
| K8 & K10 hybrid | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 547       | 60.31%  |
| Nvidia                           | 218       | 24.04%  |
| AMD                              | 139       | 15.33%  |
| Silicon Integrated Systems [SiS] | 3         | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 4.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 47        | 4.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 45        | 4.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 4.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 33        | 3.5%    |
| Intel UHD Graphics 620                                                                   | 32        | 3.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 32        | 3.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 28        | 2.97%   |
| Intel HD Graphics 5500                                                                   | 27        | 2.86%   |
| Intel HD Graphics 620                                                                    | 25        | 2.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 24        | 2.55%   |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 2.33%   |
| Intel HD Graphics 630                                                                    | 20        | 2.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 1.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 1.38%   |
| AMD Renoir                                                                               | 13        | 1.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 1.27%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 11        | 1.17%   |
| AMD Cezanne                                                                              | 10        | 1.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.74%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 7         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.74%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.74%   |
| AMD Lucienne                                                                             | 7         | 0.74%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.64%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 6         | 0.64%   |
| Nvidia GM108M [GeForce 840M]                                                             | 6         | 0.64%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 6         | 0.64%   |
| Intel HD Graphics 530                                                                    | 6         | 0.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 0.64%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 5         | 0.53%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 5         | 0.53%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 5         | 0.53%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 5         | 0.53%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 5         | 0.53%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 5         | 0.53%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 5         | 0.53%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 0.53%   |
| Nvidia GT218M [NVS 3100M]                                                                | 4         | 0.42%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.42%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 4         | 0.42%   |
| Nvidia GM204M [GeForce GTX 980M]                                                         | 4         | 0.42%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.42%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.42%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 4         | 0.42%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.42%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.42%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 0.42%   |
| Intel Iris Graphics 6100                                                                 | 4         | 0.42%   |
| Intel HD Graphics 6000                                                                   | 4         | 0.42%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 4         | 0.42%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.42%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 372       | 51.67%  |
| Intel + Nvidia | 153       | 21.25%  |
| 1 x AMD        | 88        | 12.22%  |
| 1 x Nvidia     | 53        | 7.36%   |
| Intel + AMD    | 23        | 3.19%   |
| 2 x AMD        | 16        | 2.22%   |
| AMD + Nvidia   | 12        | 1.67%   |
| 1 x SiS        | 3         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 590       | 81.49%  |
| Proprietary | 119       | 16.44%  |
| Unknown     | 15        | 2.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 457       | 62.6%   |
| 1.01-2.0   | 87        | 11.92%  |
| 0.01-0.5   | 80        | 10.96%  |
| 0.51-1.0   | 43        | 5.89%   |
| 3.01-4.0   | 40        | 5.48%   |
| 5.01-6.0   | 12        | 1.64%   |
| 7.01-8.0   | 7         | 0.96%   |
| 2.01-3.0   | 4         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 195       | 23.08%  |
| LG Display              | 119       | 14.08%  |
| Chimei Innolux          | 100       | 11.83%  |
| Samsung Electronics     | 88        | 10.41%  |
| BOE                     | 53        | 6.27%   |
| Sharp                   | 43        | 5.09%   |
| Dell                    | 29        | 3.43%   |
| Apple                   | 26        | 3.08%   |
| Lenovo                  | 22        | 2.6%    |
| Chi Mei Optoelectronics | 17        | 2.01%   |
| LG Philips              | 16        | 1.89%   |
| Philips                 | 15        | 1.78%   |
| InfoVision              | 12        | 1.42%   |
| Hewlett-Packard         | 11        | 1.3%    |
| BenQ                    | 10        | 1.18%   |
| Goldstar                | 8         | 0.95%   |
| ASUSTek Computer        | 8         | 0.95%   |
| AOC                     | 8         | 0.95%   |
| Ancor Communications    | 7         | 0.83%   |
| Acer                    | 6         | 0.71%   |
| PANDA                   | 5         | 0.59%   |
| Sony                    | 4         | 0.47%   |
| Panasonic               | 4         | 0.47%   |
| LGD                     | 4         | 0.47%   |
| Vestel Elektronik       | 3         | 0.36%   |
| CSO                     | 3         | 0.36%   |
| BOE Technology Group    | 3         | 0.36%   |
| Unknown                 | 2         | 0.24%   |
| Toshiba                 | 2         | 0.24%   |
| Quanta Display          | 2         | 0.24%   |
| Nvidia                  | 2         | 0.24%   |
| ViewSonic               | 1         | 0.12%   |
| SMP                     | 1         | 0.12%   |
| RTK                     | 1         | 0.12%   |
| Positivo                | 1         | 0.12%   |
| Olevia                  | 1         | 0.12%   |
| OEM                     | 1         | 0.12%   |
| Marantz                 | 1         | 0.12%   |
| LPL                     | 1         | 0.12%   |
| LG Electronics          | 1         | 0.12%   |
| Lenovo Group Limited    | 1         | 0.12%   |
| ITE                     | 1         | 0.12%   |
| InnoLux Display         | 1         | 0.12%   |
| Grundig                 | 1         | 0.12%   |
| Fujitsu Siemens         | 1         | 0.12%   |
| Eizo                    | 1         | 0.12%   |
| DSGR                    | 1         | 0.12%   |
| CPT                     | 1         | 0.12%   |
| Compaq Computer         | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 1.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.82%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 6         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 6         | 0.7%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.7%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 6         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch         | 5         | 0.58%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 5         | 0.58%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 5         | 0.58%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 4         | 0.47%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch             | 4         | 0.47%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.47%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.47%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 4         | 0.47%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 3         | 0.35%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 3         | 0.35%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 3         | 0.35%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 3         | 0.35%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                  | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 3         | 0.35%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.35%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 3         | 0.35%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 3         | 0.35%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 3         | 0.35%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch              | 3         | 0.35%   |
| Dell U3011 DEL4065 2560x1600 641x401mm 29.8-inch                         | 3         | 0.35%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch         | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 3         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO37ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 309x173mm 13.9-inch           | 3         | 0.35%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 3         | 0.35%   |
| Apple Color LCD APPA019 2880x1800 331x207mm 15.4-inch                    | 3         | 0.35%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 2         | 0.23%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch                  | 2         | 0.23%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 2         | 0.23%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                  | 2         | 0.23%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 2         | 0.23%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 2         | 0.23%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                  | 2         | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 2         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 354       | 43.81%  |
| 1366x768 (WXGA)    | 187       | 23.14%  |
| 3840x2160 (4K)     | 48        | 5.94%   |
| 2560x1440 (QHD)    | 33        | 4.08%   |
| 1600x900 (HD+)     | 32        | 3.96%   |
| 1280x800 (WXGA)    | 32        | 3.96%   |
| 1920x1200 (WUXGA)  | 19        | 2.35%   |
| 1440x900 (WXGA+)   | 16        | 1.98%   |
| 2880x1800          | 12        | 1.49%   |
| 1680x1050 (WSXGA+) | 11        | 1.36%   |
| 3840x2400          | 10        | 1.24%   |
| 2560x1600          | 8         | 0.99%   |
| 3440x1440          | 7         | 0.87%   |
| 1280x1024 (SXGA)   | 6         | 0.74%   |
| 1024x600           | 5         | 0.62%   |
| 1024x768 (XGA)     | 4         | 0.5%    |
| Unknown            | 4         | 0.5%    |
| 3840x1080          | 3         | 0.37%   |
| 3200x1800 (QHD+)   | 3         | 0.37%   |
| 1920x540           | 3         | 0.37%   |
| 2288x1287          | 2         | 0.25%   |
| 2160x1440          | 2         | 0.25%   |
| 1360x768           | 2         | 0.25%   |
| 3840x1600          | 1         | 0.12%   |
| 2880x1920          | 1         | 0.12%   |
| 2560x1080          | 1         | 0.12%   |
| 1920x1280          | 1         | 0.12%   |
| 1400x1050          | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 286       | 33.77%  |
| 13      | 143       | 16.88%  |
| 14      | 107       | 12.63%  |
| 17      | 56        | 6.61%   |
| 12      | 42        | 4.96%   |
| 27      | 37        | 4.37%   |
| 24      | 36        | 4.25%   |
| 23      | 20        | 2.36%   |
| 11      | 20        | 2.36%   |
| Unknown | 20        | 2.36%   |
| 31      | 12        | 1.42%   |
| 21      | 6         | 0.71%   |
| 34      | 5         | 0.59%   |
| 22      | 5         | 0.59%   |
| 19      | 5         | 0.59%   |
| 18      | 5         | 0.59%   |
| 10      | 5         | 0.59%   |
| 84      | 4         | 0.47%   |
| 32      | 3         | 0.35%   |
| 29      | 3         | 0.35%   |
| 16      | 3         | 0.35%   |
| 54      | 2         | 0.24%   |
| 48      | 2         | 0.24%   |
| 47      | 2         | 0.24%   |
| 42      | 2         | 0.24%   |
| 37      | 2         | 0.24%   |
| 35      | 2         | 0.24%   |
| 26      | 2         | 0.24%   |
| 142     | 1         | 0.12%   |
| 75      | 1         | 0.12%   |
| 72      | 1         | 0.12%   |
| 65      | 1         | 0.12%   |
| 60      | 1         | 0.12%   |
| 40      | 1         | 0.12%   |
| 39      | 1         | 0.12%   |
| 33      | 1         | 0.12%   |
| 25      | 1         | 0.12%   |
| 20      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 459       | 54.64%  |
| 201-300        | 139       | 16.55%  |
| 501-600        | 87        | 10.36%  |
| 351-400        | 65        | 7.74%   |
| 601-700        | 20        | 2.38%   |
| Unknown        | 20        | 2.38%   |
| 401-500        | 18        | 2.14%   |
| 701-800        | 9         | 1.07%   |
| 1001-1500      | 8         | 0.95%   |
| 1501-2000      | 6         | 0.71%   |
| 801-900        | 5         | 0.6%    |
| 901-1000       | 3         | 0.36%   |
| More than 2000 | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 591       | 79.33%  |
| 16/10   | 105       | 14.09%  |
| Unknown | 18        | 2.42%   |
| 21/9    | 9         | 1.21%   |
| 4/3     | 7         | 0.94%   |
| 3/2     | 7         | 0.94%   |
| 5/4     | 5         | 0.67%   |
| 32/9    | 2         | 0.27%   |
| 1.00    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 286       | 33.89%  |
| 81-90          | 189       | 22.39%  |
| 71-80          | 60        | 7.11%   |
| 201-250        | 51        | 6.04%   |
| 121-130        | 48        | 5.69%   |
| 61-70          | 40        | 4.74%   |
| 301-350        | 39        | 4.62%   |
| 351-500        | 24        | 2.84%   |
| 51-60          | 20        | 2.37%   |
| Unknown        | 20        | 2.37%   |
| 251-300        | 16        | 1.9%    |
| More than 1000 | 12        | 1.42%   |
| 501-1000       | 9         | 1.07%   |
| 131-140        | 8         | 0.95%   |
| 151-200        | 7         | 0.83%   |
| 41-50          | 5         | 0.59%   |
| 141-150        | 5         | 0.59%   |
| 91-100         | 3         | 0.36%   |
| 111-120        | 2         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 352       | 42.56%  |
| 101-120       | 200       | 24.18%  |
| 51-100        | 127       | 15.36%  |
| 161-240       | 72        | 8.71%   |
| More than 240 | 44        | 5.32%   |
| Unknown       | 20        | 2.42%   |
| 1-50          | 12        | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 570       | 77.76%  |
| 2     | 133       | 18.14%  |
| 3     | 16        | 2.18%   |
| 0     | 14        | 1.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 443       | 40.42%  |
| Realtek Semiconductor             | 273       | 24.91%  |
| Qualcomm Atheros                  | 146       | 13.32%  |
| Broadcom                          | 81        | 7.39%   |
| Broadcom Limited                  | 27        | 2.46%   |
| Hewlett-Packard                   | 15        | 1.37%   |
| Ralink                            | 12        | 1.09%   |
| Marvell Technology Group          | 10        | 0.91%   |
| Dell                              | 9         | 0.82%   |
| Sierra Wireless                   | 8         | 0.73%   |
| MEDIATEK                          | 8         | 0.73%   |
| Lenovo                            | 7         | 0.64%   |
| ASIX Electronics                  | 7         | 0.64%   |
| Ericsson Business Mobile Networks | 6         | 0.55%   |
| Huawei Technologies               | 5         | 0.46%   |
| Fibocom                           | 4         | 0.36%   |
| TP-Link                           | 3         | 0.27%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.27%   |
| Nvidia                            | 3         | 0.27%   |
| DisplayLink                       | 3         | 0.27%   |
| Samsung Electronics               | 2         | 0.18%   |
| Ralink Technology                 | 2         | 0.18%   |
| NetGear                           | 2         | 0.18%   |
| D-Link                            | 2         | 0.18%   |
| Wacom                             | 1         | 0.09%   |
| Texas Instruments                 | 1         | 0.09%   |
| SEGGER                            | 1         | 0.09%   |
| Qualcomm Atheros Communications   | 1         | 0.09%   |
| Qualcomm                          | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.09%   |
| Novatek Microelectronics          | 1         | 0.09%   |
| Microsoft                         | 1         | 0.09%   |
| Linksys                           | 1         | 0.09%   |
| IMC Networks                      | 1         | 0.09%   |
| Gemtek                            | 1         | 0.09%   |
| Edimax Technology                 | 1         | 0.09%   |
| Chu Yuen Enterprise               | 1         | 0.09%   |
| ASUSTek Computer                  | 1         | 0.09%   |
| AMD                               | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 185       | 13.28%  |
| Intel Wireless 8265 / 8275                                        | 49        | 3.52%   |
| Intel Wireless 7260                                               | 49        | 3.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36        | 2.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 36        | 2.58%   |
| Intel Wi-Fi 6 AX200                                               | 35        | 2.51%   |
| Intel Wireless 8260                                               | 31        | 2.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 2.15%   |
| Intel Wireless 7265                                               | 30        | 2.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 24        | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 24        | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 24        | 1.72%   |
| Intel Wi-Fi 6 AX201                                               | 22        | 1.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 19        | 1.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 19        | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 18        | 1.29%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 1.22%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 16        | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16        | 1.15%   |
| Intel Wireless-AC 9260                                            | 14        | 1.01%   |
| Intel Centrino Advanced-N 6200                                    | 14        | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 14        | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 13        | 0.93%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 13        | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 0.86%   |
| Intel Wireless 3160                                               | 12        | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 0.86%   |
| Intel Ethernet Connection I219-V                                  | 11        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 11        | 0.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 11        | 0.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 0.72%   |
| Intel Centrino Advanced-N 6235                                    | 10        | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 0.65%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 9         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 8         | 0.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 7         | 0.5%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 7         | 0.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.43%   |
| Intel WiFi Link 5100                                              | 6         | 0.43%   |
| Intel Ethernet Connection I217-V                                  | 6         | 0.43%   |
| Intel Ethernet Connection (6) I219-LM                             | 6         | 0.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.43%   |
| Intel Centrino Wireless-N 2230                                    | 6         | 0.43%   |
| Intel Centrino Ultimate-N 6300                                    | 6         | 0.43%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.43%   |
| Intel 82566MM Gigabit Network Connection                          | 6         | 0.43%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 6         | 0.43%   |
| Sierra Wireless EM7455                                            | 5         | 0.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 5         | 0.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5         | 0.36%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 424       | 56.68%  |
| Qualcomm Atheros                | 121       | 16.18%  |
| Realtek Semiconductor           | 74        | 9.89%   |
| Broadcom                        | 61        | 8.16%   |
| Broadcom Limited                | 14        | 1.87%   |
| Ralink                          | 12        | 1.6%    |
| Sierra Wireless                 | 8         | 1.07%   |
| MEDIATEK                        | 8         | 1.07%   |
| Hewlett-Packard                 | 4         | 0.53%   |
| Fibocom                         | 4         | 0.53%   |
| Dell                            | 4         | 0.53%   |
| Ralink Technology               | 2         | 0.27%   |
| NetGear                         | 2         | 0.27%   |
| Wacom                           | 1         | 0.13%   |
| TP-Link                         | 1         | 0.13%   |
| Qualcomm Atheros Communications | 1         | 0.13%   |
| Qualcomm                        | 1         | 0.13%   |
| Linksys                         | 1         | 0.13%   |
| IMC Networks                    | 1         | 0.13%   |
| Edimax Technology               | 1         | 0.13%   |
| D-Link                          | 1         | 0.13%   |
| Chu Yuen Enterprise             | 1         | 0.13%   |
| ASUSTek Computer                | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 49        | 6.52%   |
| Intel Wireless 7260                                                     | 49        | 6.52%   |
| Intel Wi-Fi 6 AX200                                                     | 35        | 4.66%   |
| Intel Wireless 8260                                                     | 31        | 4.13%   |
| Intel Wireless 7265                                                     | 30        | 3.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 24        | 3.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 24        | 3.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 24        | 3.2%    |
| Intel Wi-Fi 6 AX201                                                     | 22        | 2.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 2.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 19        | 2.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 18        | 2.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 16        | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 16        | 2.13%   |
| Intel Wireless-AC 9260                                                  | 14        | 1.86%   |
| Intel Centrino Advanced-N 6200                                          | 14        | 1.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 14        | 1.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.6%    |
| Intel Wireless 3160                                                     | 12        | 1.6%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 11        | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.33%   |
| Intel Centrino Advanced-N 6235                                          | 10        | 1.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 9         | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.07%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 0.93%   |
| Intel WiFi Link 5100                                                    | 6         | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.8%    |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.8%    |
| Intel Centrino Ultimate-N 6300                                          | 6         | 0.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 6         | 0.8%    |
| Sierra Wireless EM7455                                                  | 5         | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.67%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.67%   |
| Intel Wireless 3165                                                     | 5         | 0.67%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.67%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 5         | 0.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 5         | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.53%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 4         | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.53%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 4         | 0.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.53%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 4         | 0.53%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.53%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 4         | 0.53%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 4         | 0.53%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 4         | 0.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.53%   |
| Sierra Wireless EM7345 4G LTE                                           | 3         | 0.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.4%    |
| Realtek 802.11ac NIC                                                    | 3         | 0.4%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 252       | 41.18%  |
| Intel                            | 211       | 34.48%  |
| Qualcomm Atheros                 | 52        | 8.5%    |
| Broadcom                         | 34        | 5.56%   |
| Broadcom Limited                 | 14        | 2.29%   |
| Marvell Technology Group         | 10        | 1.63%   |
| Lenovo                           | 7         | 1.14%   |
| ASIX Electronics                 | 7         | 1.14%   |
| Hewlett-Packard                  | 5         | 0.82%   |
| Huawei Technologies              | 4         | 0.65%   |
| Nvidia                           | 3         | 0.49%   |
| DisplayLink                      | 3         | 0.49%   |
| TP-Link                          | 2         | 0.33%   |
| Silicon Integrated Systems [SiS] | 2         | 0.33%   |
| Samsung Electronics              | 2         | 0.33%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.16%   |
| Microsoft                        | 1         | 0.16%   |
| Gemtek                           | 1         | 0.16%   |
| D-Link                           | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 185       | 30.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 36        | 5.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 36        | 5.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 30        | 4.87%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 2.76%   |
| Intel Ethernet Connection (3) I218-LM                                          | 17        | 2.76%   |
| Intel Ethernet Connection (4) I219-V                                           | 13        | 2.11%   |
| Intel Ethernet Connection (4) I219-LM                                          | 13        | 2.11%   |
| Intel 82577LM Gigabit Network Connection                                       | 13        | 2.11%   |
| Intel Ethernet Connection I219-LM                                              | 12        | 1.95%   |
| Intel Ethernet Connection I217-LM                                              | 12        | 1.95%   |
| Intel Ethernet Connection I219-V                                               | 11        | 1.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 11        | 1.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 9         | 1.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 1.3%    |
| Intel Ethernet Connection (6) I219-V                                           | 8         | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 0.97%   |
| Intel Ethernet Connection I217-V                                               | 6         | 0.97%   |
| Intel Ethernet Connection (6) I219-LM                                          | 6         | 0.97%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 0.97%   |
| Intel 82566MM Gigabit Network Connection                                       | 6         | 0.97%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 5         | 0.81%   |
| Intel Ethernet Connection (7) I219-V                                           | 5         | 0.81%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 5         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 4         | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                          | 4         | 0.65%   |
| Intel Ethernet Connection (5) I219-LM                                          | 4         | 0.65%   |
| Huawei MAR-LX1A                                                                | 4         | 0.65%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 4         | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 0.65%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 4         | 0.65%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 3         | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.49%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 3         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 3         | 0.49%   |
| Intel Ethernet Connection I218-V                                               | 3         | 0.49%   |
| Intel 82577LC Gigabit Network Connection                                       | 3         | 0.49%   |
| DisplayLink Dell Universal Dock D6000                                          | 3         | 0.49%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 3         | 0.49%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 3         | 0.49%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 3         | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 2         | 0.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.32%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.32%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.32%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.32%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.32%   |
| Intel Ethernet Connection (10) I219-LM                                         | 2         | 0.32%   |
| Intel 82567LF Gigabit Network Connection                                       | 2         | 0.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.32%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.32%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.32%   |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 0.16%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.16%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.16%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 710       | 53.58%  |
| Ethernet | 589       | 44.45%  |
| Modem    | 25        | 1.89%   |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 587       | 76.73%  |
| Ethernet | 178       | 23.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 536       | 74.65%  |
| 1     | 171       | 23.82%  |
| 3     | 6         | 0.84%   |
| 0     | 5         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 705       | 97.51%  |
| Yes  | 18        | 2.49%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 309       | 53.09%  |
| Qualcomm Atheros Communications | 42        | 7.22%   |
| Realtek Semiconductor           | 38        | 6.53%   |
| Broadcom                        | 36        | 6.19%   |
| IMC Networks                    | 26        | 4.47%   |
| Lite-On Technology              | 22        | 3.78%   |
| Apple                           | 22        | 3.78%   |
| Foxconn / Hon Hai               | 21        | 3.61%   |
| Hewlett-Packard                 | 16        | 2.75%   |
| Dell                            | 13        | 2.23%   |
| ASUSTek Computer                | 8         | 1.37%   |
| Ralink                          | 7         | 1.2%    |
| Cambridge Silicon Radio         | 6         | 1.03%   |
| Toshiba                         | 4         | 0.69%   |
| Realtek                         | 2         | 0.34%   |
| Ralink Technology               | 2         | 0.34%   |
| MediaTek                        | 2         | 0.34%   |
| Chicony Electronics             | 2         | 0.34%   |
| USI                             | 1         | 0.17%   |
| Fujitsu                         | 1         | 0.17%   |
| Creative Technology             | 1         | 0.17%   |
| Alps Electric                   | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 158       | 27.05%  |
| Intel AX201 Bluetooth                               | 42        | 7.19%   |
| Intel AX200 Bluetooth                               | 35        | 5.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 5.48%   |
| Realtek Bluetooth Radio                             | 24        | 4.11%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 16        | 2.74%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 2.4%    |
| Apple Bluetooth Host Controller                     | 14        | 2.4%    |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 2.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 12        | 2.05%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 1.88%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 1.71%   |
| IMC Networks Bluetooth Radio                        | 9         | 1.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 1.37%   |
| IMC Networks Bluetooth Device                       | 8         | 1.37%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 1.37%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 1.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 1.2%    |
| Ralink RT3290 Bluetooth                             | 7         | 1.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 1.2%    |
| Lite-On Bluetooth Device                            | 7         | 1.2%    |
| Apple Bluetooth USB Host Controller                 | 7         | 1.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 1.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.86%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 0.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.86%   |
| Intel AX210 Bluetooth                               | 4         | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.68%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.68%   |
| Broadcom HP Portable SoftSailing                    | 4         | 0.68%   |
| Broadcom BCM20702A0                                 | 4         | 0.68%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.51%   |
| Lite-On Wireless_Device                             | 3         | 0.51%   |
| Dell Wireless 350 Bluetooth                         | 3         | 0.51%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 0.51%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.51%   |
| ASUS BT-253 Bluetooth Adapter                       | 3         | 0.51%   |
| Toshiba Bluetooth Device                            | 2         | 0.34%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.34%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.34%   |
| Realtek Bluetooth Radio                             | 2         | 0.34%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 2         | 0.34%   |
| MediaTek MT7630e Bluetooth Adapter                  | 2         | 0.34%   |
| IMC Networks BCM20702A0                             | 2         | 0.34%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 0.34%   |
| Dell Wireless 365 Bluetooth                         | 2         | 0.34%   |
| Chicony Bluetooth Radio                             | 2         | 0.34%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.34%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.34%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 0.34%   |
| USI Bluetooth Module BCM92070                       | 1         | 0.17%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.17%   |
| Toshiba BCM43142A0                                  | 1         | 0.17%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.17%   |
| Ralink CSR BS8510                                   | 1         | 0.17%   |
| Qualcomm Atheros Bluetooth (AR3011)                 | 1         | 0.17%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.17%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 602       | 66.74%  |
| AMD                              | 118       | 13.08%  |
| Nvidia                           | 108       | 11.97%  |
| C-Media Electronics              | 10        | 1.11%   |
| Realtek Semiconductor            | 9         | 1%      |
| Plantronics                      | 5         | 0.55%   |
| Logitech                         | 5         | 0.55%   |
| Lenovo                           | 5         | 0.55%   |
| Kingston Technology              | 4         | 0.44%   |
| Silicon Integrated Systems [SiS] | 3         | 0.33%   |
| SAVITECH                         | 3         | 0.33%   |
| RODE Microphones                 | 3         | 0.33%   |
| SteelSeries ApS                  | 2         | 0.22%   |
| Hewlett-Packard                  | 2         | 0.22%   |
| GN Netcom                        | 2         | 0.22%   |
| Creative Technology              | 2         | 0.22%   |
| Apple                            | 2         | 0.22%   |
| XMOS                             | 1         | 0.11%   |
| Texas Instruments                | 1         | 0.11%   |
| SlrTek                           | 1         | 0.11%   |
| Sennheiser Communications        | 1         | 0.11%   |
| Samson Technologies              | 1         | 0.11%   |
| QinHeng Electronics              | 1         | 0.11%   |
| PreSonus Audio Electronics       | 1         | 0.11%   |
| No brand                         | 1         | 0.11%   |
| Line6                            | 1         | 0.11%   |
| LG Electronics                   | 1         | 0.11%   |
| JBL                              | 1         | 0.11%   |
| GYROCOM C&C                      | 1         | 0.11%   |
| Focusrite-Novation               | 1         | 0.11%   |
| Elite Silicon                    | 1         | 0.11%   |
| Digidesign                       | 1         | 0.11%   |
| Conexant Systems                 | 1         | 0.11%   |
| Asahi Kasei Microsystems         | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 97        | 8.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 59        | 5.35%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 52        | 4.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 47        | 4.26%   |
| Intel 8 Series HD Audio Controller                                                                | 47        | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 46        | 4.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 43        | 3.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 43        | 3.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 35        | 3.18%   |
| Intel Broadwell-U Audio Controller                                                                | 35        | 3.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 35        | 3.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 28        | 2.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 28        | 2.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 26        | 2.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 25        | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 25        | 2.27%   |
| AMD FCH Azalia Controller                                                                         | 25        | 2.27%   |
| Intel CM238 HD Audio Controller                                                                   | 22        | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 1.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 19        | 1.72%   |
| AMD Kabini HDMI/DP Audio                                                                          | 18        | 1.63%   |
| Nvidia High Definition Audio Controller                                                           | 12        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 12        | 1.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.09%   |
| Intel Comet Lake PCH cAVS                                                                         | 12        | 1.09%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 11        | 1%      |
| Nvidia GF108 High Definition Audio Controller                                                     | 11        | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 1%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 0.91%   |
| Realtek Semiconductor USB Audio                                                                   | 9         | 0.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 0.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 0.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.64%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 6         | 0.54%   |
| AMD Wrestler HDMI Audio                                                                           | 6         | 0.54%   |
| AMD Trinity HDMI Audio Controller                                                                 | 6         | 0.54%   |
| AMD High Definition Audio Controller                                                              | 6         | 0.54%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 0.45%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 5         | 0.45%   |
| Nvidia Audio device                                                                               | 5         | 0.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.36%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4         | 0.36%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.36%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 4         | 0.36%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.36%   |
| Intel Crystal Well HD Audio Controller                                                            | 4         | 0.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.36%   |
| SAVITECH ODAC-revB                                                                                | 3         | 0.27%   |
| RODE Microphones RODE NT-USB                                                                      | 3         | 0.27%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.27%   |
| C-Media Electronics CM108 Audio Controller                                                        | 3         | 0.27%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.27%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.27%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.27%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 0.27%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 2         | 0.18%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.18%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 123       | 30.45%  |
| SK Hynix            | 104       | 25.74%  |
| Micron Technology   | 52        | 12.87%  |
| Kingston            | 33        | 8.17%   |
| Unknown             | 27        | 6.68%   |
| Corsair             | 18        | 4.46%   |
| Crucial             | 12        | 2.97%   |
| Ramaxel Technology  | 9         | 2.23%   |
| Elpida              | 7         | 1.73%   |
| A-DATA Technology   | 6         | 1.49%   |
| Nanya Technology    | 4         | 0.99%   |
| Unknown (ABCD)      | 1         | 0.25%   |
| Team                | 1         | 0.25%   |
| Qimonda             | 1         | 0.25%   |
| Patriot             | 1         | 0.25%   |
| Netlist             | 1         | 0.25%   |
| G.Skill             | 1         | 0.25%   |
| Avant               | 1         | 0.25%   |
| ASint Technology    | 1         | 0.25%   |
| Apacer              | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 2.31%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 8         | 1.85%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.39%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.39%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 1.39%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.15%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.15%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.15%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 1.15%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.92%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s        | 4         | 0.92%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.92%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.92%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 4         | 0.92%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.92%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 4         | 0.92%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.92%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 3         | 0.69%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 0.69%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.69%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 3         | 0.69%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1334MT/s        | 3         | 0.69%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 3         | 0.69%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 3         | 0.69%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.69%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.69%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.69%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 3         | 0.69%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 3         | 0.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.69%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.69%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 3         | 0.69%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s   | 3         | 0.69%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 3         | 0.69%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s        | 3         | 0.69%   |
| Corsair RAM CMSO8GX3M1A1333C9 8GB SODIMM DDR3 1334MT/s           | 3         | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 0.46%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.46%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 2         | 0.46%   |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 2         | 0.46%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.46%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 2         | 0.46%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.46%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.46%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.46%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.46%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.46%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.46%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.46%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.46%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 2         | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s         | 2         | 0.46%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 2         | 0.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.46%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.46%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 148       | 41.23%  |
| DDR3   | 140       | 39%     |
| LPDDR4 | 25        | 6.96%   |
| LPDDR3 | 20        | 5.57%   |
| DDR2   | 15        | 4.18%   |
| SDRAM  | 8         | 2.23%   |
| DDR    | 2         | 0.56%   |
| DRAM   | 1         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 314       | 86.5%   |
| Row Of Chips | 38        | 10.47%  |
| Chip         | 8         | 2.2%    |
| Unknown      | 2         | 0.55%   |
| DIMM         | 1         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 148       | 38.44%  |
| 4096  | 106       | 27.53%  |
| 16384 | 64        | 16.62%  |
| 2048  | 55        | 14.29%  |
| 1024  | 7         | 1.82%   |
| 32768 | 3         | 0.78%   |
| 512   | 2         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 98        | 25.52%  |
| 2667    | 77        | 20.05%  |
| 3200    | 38        | 9.9%    |
| 2400    | 30        | 7.81%   |
| 2133    | 28        | 7.29%   |
| 1334    | 23        | 5.99%   |
| 4267    | 14        | 3.65%   |
| 1333    | 14        | 3.65%   |
| 667     | 10        | 2.6%    |
| 1867    | 9         | 2.34%   |
| Unknown | 9         | 2.34%   |
| 4266    | 6         | 1.56%   |
| 3266    | 6         | 1.56%   |
| 1067    | 5         | 1.3%    |
| 4199    | 4         | 1.04%   |
| 800     | 4         | 1.04%   |
| 2048    | 2         | 0.52%   |
| 3733    | 1         | 0.26%   |
| 1639    | 1         | 0.26%   |
| 1066    | 1         | 0.26%   |
| 975     | 1         | 0.26%   |
| 888     | 1         | 0.26%   |
| 533     | 1         | 0.26%   |
| 266     | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 42.86%  |
| Samsung Electronics | 2         | 28.57%  |
| Oki Data            | 1         | 14.29%  |
| Brother Industries  | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung SCX-3200 Series      | 1         | 14.29%  |
| Samsung M2070 Series         | 1         | 14.29%  |
| Oki Data USB Device          | 1         | 14.29%  |
| HP LaserJet P2035            | 1         | 14.29%  |
| HP ENVY 4520 series          | 1         | 14.29%  |
| HP DeskJet 5650c             | 1         | 14.29%  |
| Brother QL-500 label printer | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP ScanJet 2200c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 177       | 28.32%  |
| Microdia                               | 67        | 10.72%  |
| Acer                                   | 57        | 9.12%   |
| IMC Networks                           | 55        | 8.8%    |
| Realtek Semiconductor                  | 47        | 7.52%   |
| Sunplus Innovation Technology          | 37        | 5.92%   |
| Cheng Uei Precision Industry (Foxlink) | 29        | 4.64%   |
| Lite-On Technology                     | 26        | 4.16%   |
| Quanta                                 | 21        | 3.36%   |
| Apple                                  | 18        | 2.88%   |
| Suyin                                  | 17        | 2.72%   |
| Syntek                                 | 12        | 1.92%   |
| Ricoh                                  | 10        | 1.6%    |
| Logitech                               | 9         | 1.44%   |
| Lenovo                                 | 8         | 1.28%   |
| ALi                                    | 5         | 0.8%    |
| Alcor Micro                            | 5         | 0.8%    |
| Silicon Motion                         | 3         | 0.48%   |
| Samsung Electronics                    | 3         | 0.48%   |
| Primax Electronics                     | 3         | 0.48%   |
| Luxvisions Innotech Limited            | 3         | 0.48%   |
| Unknown                                | 2         | 0.32%   |
| Sunplus Technology                     | 2         | 0.32%   |
| Importek                               | 2         | 0.32%   |
| Creative Technology                    | 2         | 0.32%   |
| Z-Star Microelectronics                | 1         | 0.16%   |
| SunplusIT                              | 1         | 0.16%   |
| LG Electronics                         | 1         | 0.16%   |
| Intel                                  | 1         | 0.16%   |
| DigiTech                               | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                            | 38        | 6.01%   |
| Chicony Integrated Camera                                                | 36        | 5.7%    |
| IMC Networks USB2.0 HD UVC WebCam                                        | 17        | 2.69%   |
| Chicony HD Webcam                                                        | 17        | 2.69%   |
| IMC Networks Integrated Camera                                           | 16        | 2.53%   |
| Realtek Integrated_Webcam_HD                                             | 15        | 2.37%   |
| Acer Integrated Camera                                                   | 14        | 2.22%   |
| Lite-On HP HD Camera                                                     | 12        | 1.9%    |
| Acer Lenovo EasyCamera                                                   | 12        | 1.9%    |
| Sunplus HD WebCam                                                        | 11        | 1.74%   |
| Sunplus Integrated_Webcam_HD                                             | 9         | 1.42%   |
| Chicony HP HD Camera                                                     | 9         | 1.42%   |
| Chicony HP HD Webcam                                                     | 8         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 8         | 1.27%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 8         | 1.27%   |
| Acer SunplusIT Integrated Camera                                         | 8         | 1.27%   |
| Lite-On Integrated Camera                                                | 7         | 1.11%   |
| Chicony HP Truevision HD                                                 | 7         | 1.11%   |
| Chicony HP HD Webcam [Fixed]                                             | 7         | 1.11%   |
| Syntek Lenovo EasyCamera                                                 | 6         | 0.95%   |
| Syntek Integrated Camera                                                 | 6         | 0.95%   |
| Realtek USB2.0 HD UVC WebCam                                             | 6         | 0.95%   |
| Quanta HP HD Camera                                                      | 6         | 0.95%   |
| Chicony USB2.0 HD UVC WebCam                                             | 6         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 6         | 0.95%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 5         | 0.79%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 5         | 0.79%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 5         | 0.79%   |
| Chicony USB2.0 Camera                                                    | 5         | 0.79%   |
| Chicony HD User Facing                                                   | 5         | 0.79%   |
| Acer EasyCamera                                                          | 5         | 0.79%   |
| Sunplus HP HD Webcam [Fixed]                                             | 4         | 0.63%   |
| Realtek Integrated Webcam_HD                                             | 4         | 0.63%   |
| Quanta HD Webcam                                                         | 4         | 0.63%   |
| Lite-On HP HD Webcam                                                     | 4         | 0.63%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                     | 4         | 0.63%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 4         | 0.63%   |
| Chicony Integrated Camera [ThinkPad]                                     | 4         | 0.63%   |
| Chicony Integrated Camera (1280x720@30)                                  | 4         | 0.63%   |
| Chicony HP Webcam [2 MP Macro]                                           | 4         | 0.63%   |
| Apple FaceTime HD Camera                                                 | 4         | 0.63%   |
| ALi Gateway Webcam                                                       | 4         | 0.63%   |
| Acer Integrated IR Camera                                                | 4         | 0.63%   |
| Acer BisonCam, NB Pro                                                    | 4         | 0.63%   |
| Suyin HP Truevision HD                                                   | 3         | 0.47%   |
| Suyin 1.3M HD WebCam                                                     | 3         | 0.47%   |
| Sunplus Laptop Integrated Webcam HD                                      | 3         | 0.47%   |
| Samsung Galaxy A5 (MTP)                                                  | 3         | 0.47%   |
| Ricoh USB2.0 Camera                                                      | 3         | 0.47%   |
| Realtek USB2.0-Camera                                                    | 3         | 0.47%   |
| Quanta HP TrueVision HD Camera                                           | 3         | 0.47%   |
| Quanta HD User Facing                                                    | 3         | 0.47%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 3         | 0.47%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 3         | 0.47%   |
| Microdia Laptop_Integrated_Webcam_2M                                     | 3         | 0.47%   |
| Microdia Integrated Webcam                                               | 3         | 0.47%   |
| Logitech C922 Pro Stream Webcam                                          | 3         | 0.47%   |
| Lenovo Integrated Webcam [R5U877]                                        | 3         | 0.47%   |
| Lenovo Integrated Webcam                                                 | 3         | 0.47%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                 | 3         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 90        | 49.18%  |
| Synaptics                  | 38        | 20.77%  |
| Shenzhen Goodix Technology | 16        | 8.74%   |
| AuthenTec                  | 11        | 6.01%   |
| Upek                       | 10        | 5.46%   |
| Elan Microelectronics      | 10        | 5.46%   |
| STMicroelectronics         | 5         | 2.73%   |
| LighTuning Technology      | 3         | 1.64%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 31        | 16.94%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 7.1%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 6.56%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 6.01%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 4.92%   |
| Validity Sensors VFS491                                                    | 8         | 4.37%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 4.37%   |
| Elan ELAN:Fingerprint                                                      | 8         | 4.37%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 3.83%   |
| Unknown                                                                    | 6         | 3.28%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.73%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.73%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 2.73%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 2.73%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 2.73%   |
| AuthenTec AES2810                                                          | 5         | 2.73%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 2.73%   |
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 2.19%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.64%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.64%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.64%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.09%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.09%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.09%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.09%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.55%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.55%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.55%   |
| Synaptics WBDI Device                                                      | 1         | 0.55%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.55%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.55%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.55%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.55%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 39        | 41.94%  |
| Alcor Micro | 39        | 41.94%  |
| O2 Micro    | 7         | 7.53%   |
| Upek        | 4         | 4.3%    |
| Lenovo      | 4         | 4.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 39        | 41.94%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 17.2%   |
| Broadcom 5880                                                                | 10        | 10.75%  |
| Broadcom 58200                                                               | 7         | 7.53%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 6.45%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 6.45%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 4.3%    |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.3%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 400       | 54.13%  |
| 1     | 256       | 34.64%  |
| 2     | 74        | 10.01%  |
| 3     | 6         | 0.81%   |
| 4     | 2         | 0.27%   |
| 7     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 183       | 43.16%  |
| Chipcard                 | 83        | 19.58%  |
| Graphics card            | 50        | 11.79%  |
| Net/wireless             | 30        | 7.08%   |
| Multimedia controller    | 23        | 5.42%   |
| Bluetooth                | 15        | 3.54%   |
| Camera                   | 13        | 3.07%   |
| Communication controller | 11        | 2.59%   |
| Sound                    | 4         | 0.94%   |
| Card reader              | 4         | 0.94%   |
| Storage                  | 2         | 0.47%   |
| Net/ethernet             | 2         | 0.47%   |
| Modem                    | 2         | 0.47%   |
| Storage/nvme             | 1         | 0.24%   |
| Storage/ide              | 1         | 0.24%   |

