Linux in Hong Kong - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Hong Kong.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Hong_Kong/Desktop/README.md) and [notebooks](/Location/Hong_Kong/Notebook/README.md).

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

Total: 515

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [832b434c38](https://linux-hardware.org/?probe=832b434c38) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [7e283bfa25](https://linux-hardware.org/?probe=7e283bfa25) | Mar 28, 2023 |
| METAPHYUNI    | MetamechBook                | Notebook    | [7e4076cb61](https://linux-hardware.org/?probe=7e4076cb61) | Mar 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [79e1666c41](https://linux-hardware.org/?probe=79e1666c41) | Mar 23, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4757b31751](https://linux-hardware.org/?probe=4757b31751) | Mar 19, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [cdf57a039e](https://linux-hardware.org/?probe=cdf57a039e) | Mar 19, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | Desktop     | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| Intel         | W2600CR G21602-308          | Server      | [96cda648c2](https://linux-hardware.org/?probe=96cda648c2) | Mar 14, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d256faa9fc](https://linux-hardware.org/?probe=d256faa9fc) | Mar 06, 2023 |
| Dell          | 06WXJT A02                  | Server      | [a4f3535e84](https://linux-hardware.org/?probe=a4f3535e84) | Mar 03, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | Notebook    | [97925534c2](https://linux-hardware.org/?probe=97925534c2) | Mar 02, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [fc803f9205](https://linux-hardware.org/?probe=fc803f9205) | Feb 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [601836815c](https://linux-hardware.org/?probe=601836815c) | Feb 22, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [c1936488f5](https://linux-hardware.org/?probe=c1936488f5) | Feb 20, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [81cfc27f9e](https://linux-hardware.org/?probe=81cfc27f9e) | Feb 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [ee4e2b3cde](https://linux-hardware.org/?probe=ee4e2b3cde) | Feb 19, 2023 |
| AOKZOE        | A1 AR07                     | Tablet      | [fe54acc90f](https://linux-hardware.org/?probe=fe54acc90f) | Feb 18, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [58bcb8bf04](https://linux-hardware.org/?probe=58bcb8bf04) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [bf63748499](https://linux-hardware.org/?probe=bf63748499) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [162b72d7a8](https://linux-hardware.org/?probe=162b72d7a8) | Feb 17, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| Lenovo        | Y430P 20435                 | Notebook    | [da3030daae](https://linux-hardware.org/?probe=da3030daae) | Feb 16, 2023 |
| Lenovo        | ThinkPad X230 23066RC       | Notebook    | [6a223f0a71](https://linux-hardware.org/?probe=6a223f0a71) | Feb 15, 2023 |
| ASUSTek       | X705UA                      | Notebook    | [cc59e95283](https://linux-hardware.org/?probe=cc59e95283) | Feb 07, 2023 |
| ASUSTek       | X705UA                      | Notebook    | [25188e7cfa](https://linux-hardware.org/?probe=25188e7cfa) | Feb 07, 2023 |
| Timi          | TM1613                      | Notebook    | [503133b0db](https://linux-hardware.org/?probe=503133b0db) | Feb 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [42a3945648](https://linux-hardware.org/?probe=42a3945648) | Feb 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [5f77ae27c2](https://linux-hardware.org/?probe=5f77ae27c2) | Feb 04, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [53015adc9d](https://linux-hardware.org/?probe=53015adc9d) | Jan 28, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [6d6a8e4be4](https://linux-hardware.org/?probe=6d6a8e4be4) | Jan 24, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [81c1e35182](https://linux-hardware.org/?probe=81c1e35182) | Jan 24, 2023 |
| Acer          | Swift SF314-57G             | Notebook    | [ae9de10584](https://linux-hardware.org/?probe=ae9de10584) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [4b9d2e6e26](https://linux-hardware.org/?probe=4b9d2e6e26) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [f5bb76ae13](https://linux-hardware.org/?probe=f5bb76ae13) | Jan 21, 2023 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [a18f404d39](https://linux-hardware.org/?probe=a18f404d39) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7cb08d37fb](https://linux-hardware.org/?probe=7cb08d37fb) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | Desktop     | [4ce5e1fd02](https://linux-hardware.org/?probe=4ce5e1fd02) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | Desktop     | [09560460b9](https://linux-hardware.org/?probe=09560460b9) | Jan 14, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2e13f150e6](https://linux-hardware.org/?probe=2e13f150e6) | Jan 09, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ec6743fa1b](https://linux-hardware.org/?probe=ec6743fa1b) | Jan 06, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [dc81fac0f7](https://linux-hardware.org/?probe=dc81fac0f7) | Jan 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [ecf944f539](https://linux-hardware.org/?probe=ecf944f539) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [0031785936](https://linux-hardware.org/?probe=0031785936) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [4bd2096c80](https://linux-hardware.org/?probe=4bd2096c80) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [7b3c89637b](https://linux-hardware.org/?probe=7b3c89637b) | Dec 30, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [2154a332b0](https://linux-hardware.org/?probe=2154a332b0) | Dec 29, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [8a5b919c91](https://linux-hardware.org/?probe=8a5b919c91) | Dec 24, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [641b77c3da](https://linux-hardware.org/?probe=641b77c3da) | Dec 20, 2022 |
| GPD           | P2 MAX                      | Notebook    | [de5983ec37](https://linux-hardware.org/?probe=de5983ec37) | Dec 17, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | Notebook    | [8d631bb590](https://linux-hardware.org/?probe=8d631bb590) | Dec 17, 2022 |
| Dell          | Inspiron 7590               | Notebook    | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| GPD           | P2 MAX                      | Notebook    | [63c199f475](https://linux-hardware.org/?probe=63c199f475) | Dec 08, 2022 |
| Lenovo        | ThinkSystem SR358FV2 Res... | Server      | [3702b80721](https://linux-hardware.org/?probe=3702b80721) | Dec 07, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [706e40ed5a](https://linux-hardware.org/?probe=706e40ed5a) | Dec 04, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | Desktop     | [5476b73cb7](https://linux-hardware.org/?probe=5476b73cb7) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | Desktop     | [6d07106192](https://linux-hardware.org/?probe=6d07106192) | Dec 02, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [aff020417f](https://linux-hardware.org/?probe=aff020417f) | Dec 01, 2022 |
| Dell          | Latitude 7390               | Notebook    | [7214cac96d](https://linux-hardware.org/?probe=7214cac96d) | Nov 30, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [7b0cf2fa20](https://linux-hardware.org/?probe=7b0cf2fa20) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20A... | Convertible | [341287988f](https://linux-hardware.org/?probe=341287988f) | Nov 17, 2022 |
| GPD           | G1619-04                    | Notebook    | [ce6d16840e](https://linux-hardware.org/?probe=ce6d16840e) | Nov 07, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [468f8df590](https://linux-hardware.org/?probe=468f8df590) | Nov 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [895a345eb9](https://linux-hardware.org/?probe=895a345eb9) | Nov 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9d9d3a4967](https://linux-hardware.org/?probe=9d9d3a4967) | Nov 02, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| ASRock        | H470M-STX                   | Desktop     | [02f3177542](https://linux-hardware.org/?probe=02f3177542) | Oct 26, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [ce7a9a3171](https://linux-hardware.org/?probe=ce7a9a3171) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [a9c49ccd5d](https://linux-hardware.org/?probe=a9c49ccd5d) | Oct 21, 2022 |
| Lenovo        | ThinkPad T470 20HD002TCD    | Notebook    | [0b0ca5a5f6](https://linux-hardware.org/?probe=0b0ca5a5f6) | Oct 20, 2022 |
| HP            | 8956 010                    | Mini pc     | [d959cdb332](https://linux-hardware.org/?probe=d959cdb332) | Oct 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8ebbbf93e4](https://linux-hardware.org/?probe=8ebbbf93e4) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [7d3c652547](https://linux-hardware.org/?probe=7d3c652547) | Oct 11, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6207d55486](https://linux-hardware.org/?probe=6207d55486) | Oct 05, 2022 |
| HP            | ZHAN 66 Pro A 14 inch G5... | Notebook    | [c5587dbec5](https://linux-hardware.org/?probe=c5587dbec5) | Oct 04, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [2163cddbe4](https://linux-hardware.org/?probe=2163cddbe4) | Oct 04, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| Fujitsu       | FMVNU6G1C                   | Notebook    | [1351f25388](https://linux-hardware.org/?probe=1351f25388) | Sep 30, 2022 |
| HP            | 18E7                        | Desktop     | [132a87f746](https://linux-hardware.org/?probe=132a87f746) | Sep 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [7c8030e423](https://linux-hardware.org/?probe=7c8030e423) | Sep 26, 2022 |
| Dell          | Latitude E5250              | Notebook    | [e4ffe3583d](https://linux-hardware.org/?probe=e4ffe3583d) | Sep 26, 2022 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [e939330716](https://linux-hardware.org/?probe=e939330716) | Sep 25, 2022 |
| Unknown       | Apple iPad Pro (9.7-inch... | Desktop     | [822d20fcdb](https://linux-hardware.org/?probe=822d20fcdb) | Sep 25, 2022 |
| Unknown       | Apple iPad Pro (9.7-inch... | Desktop     | [92f244ac1c](https://linux-hardware.org/?probe=92f244ac1c) | Sep 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [7e4f539e70](https://linux-hardware.org/?probe=7e4f539e70) | Sep 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [64cd74457e](https://linux-hardware.org/?probe=64cd74457e) | Sep 24, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [89a019875a](https://linux-hardware.org/?probe=89a019875a) | Sep 24, 2022 |
| ASRock        | Z490 PG Velocita            | Desktop     | [eac045585b](https://linux-hardware.org/?probe=eac045585b) | Sep 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [76be3ff1db](https://linux-hardware.org/?probe=76be3ff1db) | Sep 22, 2022 |
| Huanan        | X99-TF                      | Desktop     | [657d78e891](https://linux-hardware.org/?probe=657d78e891) | Sep 21, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [3759658825](https://linux-hardware.org/?probe=3759658825) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f454a8f6a5](https://linux-hardware.org/?probe=f454a8f6a5) | Sep 19, 2022 |
| HUAWEI        | PGU-WBY0                    | Soc         | [3f3d475864](https://linux-hardware.org/?probe=3f3d475864) | Sep 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [5160feeaf2](https://linux-hardware.org/?probe=5160feeaf2) | Sep 13, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [876e87c7b6](https://linux-hardware.org/?probe=876e87c7b6) | Sep 13, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [1d95c5b6ef](https://linux-hardware.org/?probe=1d95c5b6ef) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4562797ebc](https://linux-hardware.org/?probe=4562797ebc) | Sep 08, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [32ab96441e](https://linux-hardware.org/?probe=32ab96441e) | Sep 08, 2022 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | Notebook    | [d0ddfb5815](https://linux-hardware.org/?probe=d0ddfb5815) | Sep 07, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [302c3f11ec](https://linux-hardware.org/?probe=302c3f11ec) | Aug 29, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [9a83e7ee58](https://linux-hardware.org/?probe=9a83e7ee58) | Aug 28, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [638f08fc43](https://linux-hardware.org/?probe=638f08fc43) | Aug 27, 2022 |
| Dell          | 0427JK A00                  | Desktop     | [8f6a2c8d0b](https://linux-hardware.org/?probe=8f6a2c8d0b) | Aug 22, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [90aed4d5d1](https://linux-hardware.org/?probe=90aed4d5d1) | Aug 20, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [58b22885a8](https://linux-hardware.org/?probe=58b22885a8) | Aug 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c32d69a956](https://linux-hardware.org/?probe=c32d69a956) | Aug 18, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [bd7c6f361d](https://linux-hardware.org/?probe=bd7c6f361d) | Aug 18, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [56ba58f5d0](https://linux-hardware.org/?probe=56ba58f5d0) | Aug 16, 2022 |
| Lenovo        | ThinkPad T490s 20NYS79X0... | Notebook    | [5fe4fba501](https://linux-hardware.org/?probe=5fe4fba501) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| HP            | ZBook 17 G3                 | Notebook    | [bc4cf926f2](https://linux-hardware.org/?probe=bc4cf926f2) | Aug 06, 2022 |
| KOHJINSHA     | SC series                   | Notebook    | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | Notebook    | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6A... | Notebook    | [76d752f0ad](https://linux-hardware.org/?probe=76d752f0ad) | Aug 01, 2022 |
| Fujitsu       | LIFEBOOK V1020              | Notebook    | [e33ac2916d](https://linux-hardware.org/?probe=e33ac2916d) | Jul 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d449f1aeb9](https://linux-hardware.org/?probe=d449f1aeb9) | Jul 27, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [353168b909](https://linux-hardware.org/?probe=353168b909) | Jul 18, 2022 |
| Huanan        | X99-TF                      | Desktop     | [55b43de5a6](https://linux-hardware.org/?probe=55b43de5a6) | Jul 17, 2022 |
| IBM           | 260921H                     | Notebook    | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | Notebook    | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | Notebook    | [f3e0ebd16e](https://linux-hardware.org/?probe=f3e0ebd16e) | Jul 15, 2022 |
| IBM           | 260921H                     | Notebook    | [5f9b0998d3](https://linux-hardware.org/?probe=5f9b0998d3) | Jul 11, 2022 |
| IBM           | 260921H                     | Notebook    | [f0430651fd](https://linux-hardware.org/?probe=f0430651fd) | Jul 10, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e9adf47b7a](https://linux-hardware.org/?probe=e9adf47b7a) | Jul 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [910a4f6587](https://linux-hardware.org/?probe=910a4f6587) | Jul 09, 2022 |
| Soyo          | SY-A68M FS V2.0             | Desktop     | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [bd4792ebd8](https://linux-hardware.org/?probe=bd4792ebd8) | Jul 02, 2022 |
| Compaq        | Tablet PC TC1000            | Notebook    | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | Notebook    | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | Notebook    | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [044be44d33](https://linux-hardware.org/?probe=044be44d33) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [5bd3ad4d01](https://linux-hardware.org/?probe=5bd3ad4d01) | Jun 24, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [518331cc83](https://linux-hardware.org/?probe=518331cc83) | Jun 21, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ec6f5cce04](https://linux-hardware.org/?probe=ec6f5cce04) | Jun 20, 2022 |
| Huanan        | X99-TF                      | Desktop     | [04dc5246af](https://linux-hardware.org/?probe=04dc5246af) | Jun 18, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | Desktop     | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [bdd4ec2ef9](https://linux-hardware.org/?probe=bdd4ec2ef9) | Jun 15, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [f4c7f13ff8](https://linux-hardware.org/?probe=f4c7f13ff8) | Jun 14, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | Notebook    | [e3df184136](https://linux-hardware.org/?probe=e3df184136) | Jun 12, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e373d39f20](https://linux-hardware.org/?probe=e373d39f20) | Jun 09, 2022 |
| Huanan        | X99-TF                      | Desktop     | [4e5364e832](https://linux-hardware.org/?probe=4e5364e832) | Jun 08, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [2f8215fb0a](https://linux-hardware.org/?probe=2f8215fb0a) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [4d4c32223e](https://linux-hardware.org/?probe=4d4c32223e) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [63fd75f1a8](https://linux-hardware.org/?probe=63fd75f1a8) | May 29, 2022 |
| Lenovo        | Legion Y7000P2020H 82AX     | Notebook    | [220325c031](https://linux-hardware.org/?probe=220325c031) | May 29, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [75d345243e](https://linux-hardware.org/?probe=75d345243e) | May 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [1f67896c5c](https://linux-hardware.org/?probe=1f67896c5c) | May 22, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [a227af798c](https://linux-hardware.org/?probe=a227af798c) | May 20, 2022 |
| Gigabyte      | HA65M-UD3H-B3               | Desktop     | [d368918a0b](https://linux-hardware.org/?probe=d368918a0b) | May 13, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e45fa22892](https://linux-hardware.org/?probe=e45fa22892) | May 11, 2022 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [f0b122c199](https://linux-hardware.org/?probe=f0b122c199) | May 09, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [99e0958898](https://linux-hardware.org/?probe=99e0958898) | May 01, 2022 |
| Dell          | Precision 7520              | Notebook    | [2dc98a1a8d](https://linux-hardware.org/?probe=2dc98a1a8d) | Apr 30, 2022 |
| MSI           | H87I                        | Desktop     | [af4a26a5ea](https://linux-hardware.org/?probe=af4a26a5ea) | Apr 30, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [0633ac7757](https://linux-hardware.org/?probe=0633ac7757) | Apr 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [9191742453](https://linux-hardware.org/?probe=9191742453) | Apr 26, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [56902c7998](https://linux-hardware.org/?probe=56902c7998) | Apr 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [a3aa6e30b9](https://linux-hardware.org/?probe=a3aa6e30b9) | Apr 21, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [3dd8282149](https://linux-hardware.org/?probe=3dd8282149) | Apr 20, 2022 |
| GPD           | P2 MAX                      | Notebook    | [ca842dc5fb](https://linux-hardware.org/?probe=ca842dc5fb) | Apr 19, 2022 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [d359794b2f](https://linux-hardware.org/?probe=d359794b2f) | Apr 19, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [7ea786c89b](https://linux-hardware.org/?probe=7ea786c89b) | Apr 18, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0ac1f4daf9](https://linux-hardware.org/?probe=0ac1f4daf9) | Apr 12, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [abed3ae34d](https://linux-hardware.org/?probe=abed3ae34d) | Apr 12, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| ASUSTek       | VM62                        | Desktop     | [ae684cdf71](https://linux-hardware.org/?probe=ae684cdf71) | Apr 05, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [bdca066ba3](https://linux-hardware.org/?probe=bdca066ba3) | Apr 05, 2022 |
| ASRock        | H410M-ITX/ac                | Desktop     | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [314bd42e78](https://linux-hardware.org/?probe=314bd42e78) | Mar 28, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [a881a875bd](https://linux-hardware.org/?probe=a881a875bd) | Mar 27, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [2d48cb4419](https://linux-hardware.org/?probe=2d48cb4419) | Mar 26, 2022 |
| Dell          | 0Y3R3K A03                  | Desktop     | [b772cf9d86](https://linux-hardware.org/?probe=b772cf9d86) | Mar 26, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [e7fb180535](https://linux-hardware.org/?probe=e7fb180535) | Mar 16, 2022 |
| Dell          | Latitude 7285               | Notebook    | [87e555f958](https://linux-hardware.org/?probe=87e555f958) | Mar 13, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [7320ed668a](https://linux-hardware.org/?probe=7320ed668a) | Mar 12, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [03b27c8ca4](https://linux-hardware.org/?probe=03b27c8ca4) | Mar 12, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [4998fff0f9](https://linux-hardware.org/?probe=4998fff0f9) | Mar 12, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [99d3e16ede](https://linux-hardware.org/?probe=99d3e16ede) | Mar 12, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [c68cec2207](https://linux-hardware.org/?probe=c68cec2207) | Mar 11, 2022 |
| Unknown       | Intel X79                   | Desktop     | [e947d6af7f](https://linux-hardware.org/?probe=e947d6af7f) | Mar 11, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [96b36779e0](https://linux-hardware.org/?probe=96b36779e0) | Mar 11, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4d16610cf3](https://linux-hardware.org/?probe=4d16610cf3) | Mar 10, 2022 |
| HP            | Notebook                    | Notebook    | [9c04c0776d](https://linux-hardware.org/?probe=9c04c0776d) | Mar 10, 2022 |
| HP            | Notebook                    | Notebook    | [c7d735dc99](https://linux-hardware.org/?probe=c7d735dc99) | Mar 10, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0b9a7acb84](https://linux-hardware.org/?probe=0b9a7acb84) | Feb 27, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [3c7daed552](https://linux-hardware.org/?probe=3c7daed552) | Feb 22, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [6c00869d7b](https://linux-hardware.org/?probe=6c00869d7b) | Feb 21, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [0f4fad19b2](https://linux-hardware.org/?probe=0f4fad19b2) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6e5689a733](https://linux-hardware.org/?probe=6e5689a733) | Jan 28, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 Rev ... | Soc         | [2a66f4b578](https://linux-hardware.org/?probe=2a66f4b578) | Jan 24, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [515465fd5a](https://linux-hardware.org/?probe=515465fd5a) | Jan 22, 2022 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [4c32bf6d7b](https://linux-hardware.org/?probe=4c32bf6d7b) | Jan 18, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| HP            | 8597                        | Desktop     | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c5fa4a0cec](https://linux-hardware.org/?probe=c5fa4a0cec) | Dec 24, 2021 |
| ASRock        | H410M-ITX/ac                | Desktop     | [99c341562a](https://linux-hardware.org/?probe=99c341562a) | Dec 21, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| MSI           | 870-G45                     | Desktop     | [e6317a2b91](https://linux-hardware.org/?probe=e6317a2b91) | Dec 19, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| Fujitsu       | LIFEBOOK LH530              | Notebook    | [8db7409ab5](https://linux-hardware.org/?probe=8db7409ab5) | Dec 14, 2021 |
| Unknown       | Intel X79                   | Desktop     | [985655e4b3](https://linux-hardware.org/?probe=985655e4b3) | Dec 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [739be994cb](https://linux-hardware.org/?probe=739be994cb) | Dec 09, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [024a42eb21](https://linux-hardware.org/?probe=024a42eb21) | Dec 08, 2021 |
| Unknown       | Intel X79                   | Desktop     | [6f32192557](https://linux-hardware.org/?probe=6f32192557) | Dec 08, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| MSI           | Boston                      | Desktop     | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| Supermicro    | C2SBC-Q                     | Desktop     | [1099e48366](https://linux-hardware.org/?probe=1099e48366) | Nov 28, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [58d43162d2](https://linux-hardware.org/?probe=58d43162d2) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ee13ae89af](https://linux-hardware.org/?probe=ee13ae89af) | Nov 26, 2021 |
| Apple         | MacBook10,1                 | Notebook    | [6cb99e6a5f](https://linux-hardware.org/?probe=6cb99e6a5f) | Nov 23, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [fc59694424](https://linux-hardware.org/?probe=fc59694424) | Nov 17, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [35b58ec233](https://linux-hardware.org/?probe=35b58ec233) | Nov 16, 2021 |
| Jumper        | EZbook                      | Notebook    | [5da2b95e2f](https://linux-hardware.org/?probe=5da2b95e2f) | Nov 12, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| Seco          | C40 C                       | Desktop     | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [9bcd3d5479](https://linux-hardware.org/?probe=9bcd3d5479) | Oct 29, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [c7fc01bd49](https://linux-hardware.org/?probe=c7fc01bd49) | Oct 27, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [c7a0fe2f88](https://linux-hardware.org/?probe=c7a0fe2f88) | Oct 26, 2021 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [6f87ece998](https://linux-hardware.org/?probe=6f87ece998) | Oct 26, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [3d42bc888b](https://linux-hardware.org/?probe=3d42bc888b) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [54e54e71bd](https://linux-hardware.org/?probe=54e54e71bd) | Oct 24, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [aedfc53de6](https://linux-hardware.org/?probe=aedfc53de6) | Oct 20, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [20dc49f637](https://linux-hardware.org/?probe=20dc49f637) | Oct 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [aee062d6e5](https://linux-hardware.org/?probe=aee062d6e5) | Oct 04, 2021 |
| Lenovo        | Legion Y9000P2021H 82JD     | Notebook    | [4c3be0fe24](https://linux-hardware.org/?probe=4c3be0fe24) | Oct 02, 2021 |
| MSI           | H61M-P23                    | Desktop     | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| GPD           | G1618-03                    | Notebook    | [41916177c2](https://linux-hardware.org/?probe=41916177c2) | Sep 01, 2021 |
| GPD           | G1618-03                    | Notebook    | [c2abcaf10c](https://linux-hardware.org/?probe=c2abcaf10c) | Sep 01, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [1440e244f6](https://linux-hardware.org/?probe=1440e244f6) | Aug 26, 2021 |
| Dell          | Precision 7550              | Notebook    | [42721343a3](https://linux-hardware.org/?probe=42721343a3) | Aug 16, 2021 |
| Lenovo        | XiaoXin-14API QC 2019 81... | Notebook    | [814eb97442](https://linux-hardware.org/?probe=814eb97442) | Aug 14, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [d920558127](https://linux-hardware.org/?probe=d920558127) | Aug 14, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5cd377c0e0](https://linux-hardware.org/?probe=5cd377c0e0) | Aug 13, 2021 |
| Gigabyte      | B75M-D2P                    | Desktop     | [5e54c2a102](https://linux-hardware.org/?probe=5e54c2a102) | Aug 12, 2021 |
| Lenovo        | ThinkPad T61 6465CTO        | Notebook    | [d93258840e](https://linux-hardware.org/?probe=d93258840e) | Aug 04, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [eb060cd2c4](https://linux-hardware.org/?probe=eb060cd2c4) | Aug 04, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [828a52387f](https://linux-hardware.org/?probe=828a52387f) | Aug 02, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [12b2c3e130](https://linux-hardware.org/?probe=12b2c3e130) | Aug 01, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [3af43c8ebe](https://linux-hardware.org/?probe=3af43c8ebe) | Jul 29, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [fa0aa86cef](https://linux-hardware.org/?probe=fa0aa86cef) | Jul 28, 2021 |
| HP            | 2B38                        | Desktop     | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [8fc32673b3](https://linux-hardware.org/?probe=8fc32673b3) | Jul 25, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [58b70e282d](https://linux-hardware.org/?probe=58b70e282d) | Jul 14, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [66cf378cf1](https://linux-hardware.org/?probe=66cf378cf1) | Jul 10, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [6496f18326](https://linux-hardware.org/?probe=6496f18326) | Jul 02, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [71da4978c9](https://linux-hardware.org/?probe=71da4978c9) | Jun 29, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [ed911e7e8c](https://linux-hardware.org/?probe=ed911e7e8c) | Jun 26, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [8785d98b0b](https://linux-hardware.org/?probe=8785d98b0b) | Jun 19, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [54e520ac17](https://linux-hardware.org/?probe=54e520ac17) | Jun 17, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [c2bfccf320](https://linux-hardware.org/?probe=c2bfccf320) | Jun 16, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [d3f69874dd](https://linux-hardware.org/?probe=d3f69874dd) | Jun 16, 2021 |
| Lenovo        | IdeaCentre B305 10052       | All in one  | [8399296d51](https://linux-hardware.org/?probe=8399296d51) | Jun 13, 2021 |
| Dell          | Precision M4800             | Notebook    | [298694c222](https://linux-hardware.org/?probe=298694c222) | Jun 12, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [76219e9cca](https://linux-hardware.org/?probe=76219e9cca) | Jun 09, 2021 |
| Acer          | Aspire E5-573               | Notebook    | [4193a2da9d](https://linux-hardware.org/?probe=4193a2da9d) | Jun 08, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [bcb80080a5](https://linux-hardware.org/?probe=bcb80080a5) | Jun 06, 2021 |
| Dell          | Precision M4800             | Notebook    | [67fb08d285](https://linux-hardware.org/?probe=67fb08d285) | Jun 06, 2021 |
| Dell          | Precision M4800             | Notebook    | [c72664a2f4](https://linux-hardware.org/?probe=c72664a2f4) | Jun 06, 2021 |
| HP            | 18E7                        | Desktop     | [9844f6635c](https://linux-hardware.org/?probe=9844f6635c) | May 30, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [81ffc7ba9e](https://linux-hardware.org/?probe=81ffc7ba9e) | May 26, 2021 |
| ASUSTek       | VM62                        | Desktop     | [486aeb5b89](https://linux-hardware.org/?probe=486aeb5b89) | May 25, 2021 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [e19475cd4c](https://linux-hardware.org/?probe=e19475cd4c) | May 22, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [a201bdfc36](https://linux-hardware.org/?probe=a201bdfc36) | May 19, 2021 |
| Fujitsu       | UH-X                        | Notebook    | [be65091e59](https://linux-hardware.org/?probe=be65091e59) | May 19, 2021 |
| ASUSTek       | M4A78-VM                    | Desktop     | [3313d34c41](https://linux-hardware.org/?probe=3313d34c41) | May 15, 2021 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [1409e11b30](https://linux-hardware.org/?probe=1409e11b30) | May 12, 2021 |
| Nvidia        | Tegra                       | Soc         | [54592ec1a2](https://linux-hardware.org/?probe=54592ec1a2) | May 08, 2021 |
| Nvidia        | Tegra                       | Soc         | [ab1c7d5eab](https://linux-hardware.org/?probe=ab1c7d5eab) | May 08, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [8d372d62b7](https://linux-hardware.org/?probe=8d372d62b7) | May 07, 2021 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [1b777c6f08](https://linux-hardware.org/?probe=1b777c6f08) | May 02, 2021 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [4c7956a34c](https://linux-hardware.org/?probe=4c7956a34c) | May 02, 2021 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [f35a966b00](https://linux-hardware.org/?probe=f35a966b00) | Apr 14, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [a917367457](https://linux-hardware.org/?probe=a917367457) | Apr 09, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [f7937503ac](https://linux-hardware.org/?probe=f7937503ac) | Apr 08, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [99d71b6ea5](https://linux-hardware.org/?probe=99d71b6ea5) | Apr 06, 2021 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [8253b70553](https://linux-hardware.org/?probe=8253b70553) | Apr 06, 2021 |
| MSI           | Boston                      | Desktop     | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [60600f6f0c](https://linux-hardware.org/?probe=60600f6f0c) | Mar 26, 2021 |
| HP            | 1632                        | Desktop     | [adf9ebb679](https://linux-hardware.org/?probe=adf9ebb679) | Mar 25, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [6a4196e0aa](https://linux-hardware.org/?probe=6a4196e0aa) | Mar 23, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [dc64c81c35](https://linux-hardware.org/?probe=dc64c81c35) | Mar 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [280785b873](https://linux-hardware.org/?probe=280785b873) | Mar 22, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [20d78f0b3a](https://linux-hardware.org/?probe=20d78f0b3a) | Mar 22, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [71ef988016](https://linux-hardware.org/?probe=71ef988016) | Mar 21, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [e44a5ce779](https://linux-hardware.org/?probe=e44a5ce779) | Mar 14, 2021 |
| ASUSTek       | UX302LA                     | Notebook    | [fe27a8e195](https://linux-hardware.org/?probe=fe27a8e195) | Mar 12, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [d23d84b5f6](https://linux-hardware.org/?probe=d23d84b5f6) | Mar 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [5051ba6156](https://linux-hardware.org/?probe=5051ba6156) | Mar 05, 2021 |
| MSI           | Boston                      | Desktop     | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [b94539c6dc](https://linux-hardware.org/?probe=b94539c6dc) | Mar 01, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [b2cb174b9a](https://linux-hardware.org/?probe=b2cb174b9a) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [2414020b54](https://linux-hardware.org/?probe=2414020b54) | Feb 26, 2021 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [ae61a5e1fa](https://linux-hardware.org/?probe=ae61a5e1fa) | Feb 26, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [87c36a9322](https://linux-hardware.org/?probe=87c36a9322) | Feb 23, 2021 |
| Lenovo        | ThinkPad E14 20RAA002CD     | Notebook    | [77ccb1ee60](https://linux-hardware.org/?probe=77ccb1ee60) | Feb 22, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [7d9f2bee38](https://linux-hardware.org/?probe=7d9f2bee38) | Feb 21, 2021 |
| ASUSTek       | VM45                        | Desktop     | [03eeb85521](https://linux-hardware.org/?probe=03eeb85521) | Feb 21, 2021 |
| ASUSTek       | VM65-K                      | Desktop     | [6b97cf71eb](https://linux-hardware.org/?probe=6b97cf71eb) | Feb 18, 2021 |
| ASUSTek       | VM65-K                      | Desktop     | [4f0bcd1276](https://linux-hardware.org/?probe=4f0bcd1276) | Feb 17, 2021 |
| ASUSTek       | VM40B                       | Desktop     | [6c0bf22f39](https://linux-hardware.org/?probe=6c0bf22f39) | Feb 17, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [d82924b12b](https://linux-hardware.org/?probe=d82924b12b) | Feb 16, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [ebc5645105](https://linux-hardware.org/?probe=ebc5645105) | Feb 11, 2021 |
| Lenovo        | IdeaCentre K330             | Desktop     | [78ce34058b](https://linux-hardware.org/?probe=78ce34058b) | Feb 11, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [f4c2a6bac8](https://linux-hardware.org/?probe=f4c2a6bac8) | Feb 07, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [d4f69c78fa](https://linux-hardware.org/?probe=d4f69c78fa) | Jan 31, 2021 |
| Fujitsu       | S6420                       | Notebook    | [b23c0f10e7](https://linux-hardware.org/?probe=b23c0f10e7) | Jan 28, 2021 |
| Fujitsu       | S6420                       | Notebook    | [0cf6376b40](https://linux-hardware.org/?probe=0cf6376b40) | Jan 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1d0000672d](https://linux-hardware.org/?probe=1d0000672d) | Jan 23, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [3d7ce778c6](https://linux-hardware.org/?probe=3d7ce778c6) | Jan 20, 2021 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [fe7d03f093](https://linux-hardware.org/?probe=fe7d03f093) | Jan 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [b8f5d6f1e4](https://linux-hardware.org/?probe=b8f5d6f1e4) | Jan 16, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [39bc70ca5d](https://linux-hardware.org/?probe=39bc70ca5d) | Jan 13, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [d2420f233b](https://linux-hardware.org/?probe=d2420f233b) | Jan 10, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| Dell          | 0TP412                      | Desktop     | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| Intel         | NUC6CAYB J23203-406         | Mini pc     | [038dce10fa](https://linux-hardware.org/?probe=038dce10fa) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [a8ac85cb5a](https://linux-hardware.org/?probe=a8ac85cb5a) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [8c7ba97457](https://linux-hardware.org/?probe=8c7ba97457) | Dec 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [01333c5b9e](https://linux-hardware.org/?probe=01333c5b9e) | Dec 29, 2020 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [728d7e48d4](https://linux-hardware.org/?probe=728d7e48d4) | Dec 27, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [1d4b16bb0d](https://linux-hardware.org/?probe=1d4b16bb0d) | Dec 22, 2020 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [cf7386e848](https://linux-hardware.org/?probe=cf7386e848) | Dec 18, 2020 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [88a7edec45](https://linux-hardware.org/?probe=88a7edec45) | Dec 18, 2020 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [1d6b7df7b4](https://linux-hardware.org/?probe=1d6b7df7b4) | Dec 08, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [8309aa39cf](https://linux-hardware.org/?probe=8309aa39cf) | Nov 30, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [ede3032fed](https://linux-hardware.org/?probe=ede3032fed) | Nov 29, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [f3012a2898](https://linux-hardware.org/?probe=f3012a2898) | Nov 29, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [37d5acae7d](https://linux-hardware.org/?probe=37d5acae7d) | Nov 27, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [3c4ff5bb58](https://linux-hardware.org/?probe=3c4ff5bb58) | Nov 27, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [97c485886b](https://linux-hardware.org/?probe=97c485886b) | Nov 25, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [8f55b945a1](https://linux-hardware.org/?probe=8f55b945a1) | Nov 20, 2020 |
| Fujitsu       | UH-X                        | Notebook    | [f55a6a6679](https://linux-hardware.org/?probe=f55a6a6679) | Nov 20, 2020 |
| Fujitsu       | UH-X                        | Notebook    | [7aea886f7a](https://linux-hardware.org/?probe=7aea886f7a) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [de597aa847](https://linux-hardware.org/?probe=de597aa847) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f5aa8c9150](https://linux-hardware.org/?probe=f5aa8c9150) | Nov 20, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a3c484b8ee](https://linux-hardware.org/?probe=a3c484b8ee) | Nov 16, 2020 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | Notebook    | [6254edfb10](https://linux-hardware.org/?probe=6254edfb10) | Nov 14, 2020 |
| Lenovo        | G770 20089                  | Notebook    | [6da9203114](https://linux-hardware.org/?probe=6da9203114) | Nov 13, 2020 |
| HP            | 2000                        | Notebook    | [f548e6d1cc](https://linux-hardware.org/?probe=f548e6d1cc) | Nov 11, 2020 |
| ASUSTek       | K501UX                      | Notebook    | [e1700b887e](https://linux-hardware.org/?probe=e1700b887e) | Nov 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [69fb29494b](https://linux-hardware.org/?probe=69fb29494b) | Nov 07, 2020 |
| HP            | 2000                        | Notebook    | [df76d279ad](https://linux-hardware.org/?probe=df76d279ad) | Nov 05, 2020 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [f90977870e](https://linux-hardware.org/?probe=f90977870e) | Nov 04, 2020 |
| Timi          | TM1607                      | Notebook    | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| ZOTAC         | ZBOX-ID92/ZBOX-IQ01         | Mini pc     | [fbba9f6a3b](https://linux-hardware.org/?probe=fbba9f6a3b) | Nov 02, 2020 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [e970e25954](https://linux-hardware.org/?probe=e970e25954) | Nov 02, 2020 |
| Acer          | Swift SF314-57              | Notebook    | [8395e5a946](https://linux-hardware.org/?probe=8395e5a946) | Oct 30, 2020 |
| Acer          | Swift SF314-57              | Notebook    | [123f60c868](https://linux-hardware.org/?probe=123f60c868) | Oct 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [f9d1166197](https://linux-hardware.org/?probe=f9d1166197) | Oct 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [77849f8db0](https://linux-hardware.org/?probe=77849f8db0) | Oct 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [77d6dd66e2](https://linux-hardware.org/?probe=77d6dd66e2) | Oct 23, 2020 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [1af7b2b551](https://linux-hardware.org/?probe=1af7b2b551) | Oct 13, 2020 |
| HP            | 2140                        | Notebook    | [bde3dc449f](https://linux-hardware.org/?probe=bde3dc449f) | Oct 07, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [1fe32b8f6d](https://linux-hardware.org/?probe=1fe32b8f6d) | Oct 04, 2020 |
| HP            | 2000                        | Notebook    | [fbd8bf0e69](https://linux-hardware.org/?probe=fbd8bf0e69) | Oct 01, 2020 |
| Fujitsu       | LIFEBOOK S904               | Notebook    | [5035864c45](https://linux-hardware.org/?probe=5035864c45) | Sep 27, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [37e6b406f7](https://linux-hardware.org/?probe=37e6b406f7) | Sep 27, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [bd8f561b0b](https://linux-hardware.org/?probe=bd8f561b0b) | Sep 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e292456297](https://linux-hardware.org/?probe=e292456297) | Sep 17, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e7b41f62a4](https://linux-hardware.org/?probe=e7b41f62a4) | Sep 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [20bdbc68b7](https://linux-hardware.org/?probe=20bdbc68b7) | Sep 12, 2020 |
| ASUSTek       | H81M-E                      | Desktop     | [43b8c677bc](https://linux-hardware.org/?probe=43b8c677bc) | Sep 10, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [24cad8bed5](https://linux-hardware.org/?probe=24cad8bed5) | Aug 28, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [3d4c2a283d](https://linux-hardware.org/?probe=3d4c2a283d) | Aug 28, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [64a249acd1](https://linux-hardware.org/?probe=64a249acd1) | Aug 28, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [6a91a7b38c](https://linux-hardware.org/?probe=6a91a7b38c) | Aug 25, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [e27db6fb31](https://linux-hardware.org/?probe=e27db6fb31) | Aug 24, 2020 |
| Samsung       | 930XBE                      | Notebook    | [92925e0656](https://linux-hardware.org/?probe=92925e0656) | Aug 24, 2020 |
| HP            | 802E                        | Desktop     | [653b11eec3](https://linux-hardware.org/?probe=653b11eec3) | Aug 11, 2020 |
| HP            | 802E                        | Desktop     | [6f32afeb2b](https://linux-hardware.org/?probe=6f32afeb2b) | Aug 10, 2020 |
| HP            | 802E                        | Desktop     | [25d8ddc0bb](https://linux-hardware.org/?probe=25d8ddc0bb) | Aug 10, 2020 |
| Dell          | Inspiron 5580               | Notebook    | [fbaf2b8f7f](https://linux-hardware.org/?probe=fbaf2b8f7f) | Aug 05, 2020 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [e7488a8b16](https://linux-hardware.org/?probe=e7488a8b16) | Aug 04, 2020 |
| Toshiba       | PORTEGE R830                | Notebook    | [fa44f09e6e](https://linux-hardware.org/?probe=fa44f09e6e) | Aug 03, 2020 |
| Dell          | G7 7588                     | Notebook    | [e85e2949de](https://linux-hardware.org/?probe=e85e2949de) | Aug 01, 2020 |
| Lenovo        | ZHAOYANG K47                | Notebook    | [fa5be40392](https://linux-hardware.org/?probe=fa5be40392) | Jul 24, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [50dc692a9e](https://linux-hardware.org/?probe=50dc692a9e) | Jul 23, 2020 |
| Lenovo        | ZHAOYANG K47                | Notebook    | [879b0d586f](https://linux-hardware.org/?probe=879b0d586f) | Jul 22, 2020 |
| Gigabyte      | Z170X-Gaming 5 Modified ... | Desktop     | [a62f520dc3](https://linux-hardware.org/?probe=a62f520dc3) | Jul 18, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [723898cdec](https://linux-hardware.org/?probe=723898cdec) | Jun 20, 2020 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [f897dd388f](https://linux-hardware.org/?probe=f897dd388f) | Jun 17, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [c90b1cb242](https://linux-hardware.org/?probe=c90b1cb242) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [74dadf599d](https://linux-hardware.org/?probe=74dadf599d) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [db21903e1a](https://linux-hardware.org/?probe=db21903e1a) | Jun 14, 2020 |
| Lenovo        | ThinkPad T480s 20L7005FU... | Notebook    | [2bc99eeca5](https://linux-hardware.org/?probe=2bc99eeca5) | Jun 09, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| HP            | 1998                        | Desktop     | [255863fefb](https://linux-hardware.org/?probe=255863fefb) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | Desktop     | [b159b440f2](https://linux-hardware.org/?probe=b159b440f2) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | Desktop     | [4181637bf3](https://linux-hardware.org/?probe=4181637bf3) | Jun 01, 2020 |
| Fujitsu       | LIFEBOOK AH556              | Notebook    | [c16b3d9827](https://linux-hardware.org/?probe=c16b3d9827) | May 30, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [55680319a1](https://linux-hardware.org/?probe=55680319a1) | May 29, 2020 |
| Biostar       | H110MHC                     | Desktop     | [98d1029698](https://linux-hardware.org/?probe=98d1029698) | May 26, 2020 |
| ASUSTek       | B150M-C                     | Desktop     | [2229b866b3](https://linux-hardware.org/?probe=2229b866b3) | May 26, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Apple         | MacBookPro7,1               | Notebook    | [956da1ac80](https://linux-hardware.org/?probe=956da1ac80) | May 11, 2020 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| Toshiba       | PORTEGE R830                | Notebook    | [08f3e97afe](https://linux-hardware.org/?probe=08f3e97afe) | May 02, 2020 |
| Lenovo        | 3000 G410                   | Notebook    | [2a909aaad5](https://linux-hardware.org/?probe=2a909aaad5) | May 02, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [179a82277c](https://linux-hardware.org/?probe=179a82277c) | May 01, 2020 |
| MSI           | 2A9C                        | Desktop     | [23df26e5de](https://linux-hardware.org/?probe=23df26e5de) | Apr 25, 2020 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [664ac5b85b](https://linux-hardware.org/?probe=664ac5b85b) | Apr 24, 2020 |
| MSI           | Boston                      | Desktop     | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [f11d6eedc7](https://linux-hardware.org/?probe=f11d6eedc7) | Apr 14, 2020 |
| HP            | G72                         | Notebook    | [6272536a26](https://linux-hardware.org/?probe=6272536a26) | Apr 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [f504649d96](https://linux-hardware.org/?probe=f504649d96) | Apr 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [3916938374](https://linux-hardware.org/?probe=3916938374) | Apr 11, 2020 |
| Gigabyte      | Z87-HD3                     | Desktop     | [52a7dab5ac](https://linux-hardware.org/?probe=52a7dab5ac) | Apr 09, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [9c72670aa1](https://linux-hardware.org/?probe=9c72670aa1) | Apr 05, 2020 |
| Google        | Eve                         | Notebook    | [17c248ca99](https://linux-hardware.org/?probe=17c248ca99) | Apr 04, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [37fb7cae94](https://linux-hardware.org/?probe=37fb7cae94) | Mar 30, 2020 |
| MSI           | B360M FIRE                  | Desktop     | [8bb021d2a6](https://linux-hardware.org/?probe=8bb021d2a6) | Mar 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [18b565a861](https://linux-hardware.org/?probe=18b565a861) | Mar 26, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [abce376627](https://linux-hardware.org/?probe=abce376627) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e6860a26ae](https://linux-hardware.org/?probe=e6860a26ae) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [5f2e14b65b](https://linux-hardware.org/?probe=5f2e14b65b) | Mar 16, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [1bcf8a4701](https://linux-hardware.org/?probe=1bcf8a4701) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [bd55777a4f](https://linux-hardware.org/?probe=bd55777a4f) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [137262daa3](https://linux-hardware.org/?probe=137262daa3) | Mar 05, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [597092ba51](https://linux-hardware.org/?probe=597092ba51) | Feb 28, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [71fc35ceea](https://linux-hardware.org/?probe=71fc35ceea) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [047acafb1a](https://linux-hardware.org/?probe=047acafb1a) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e8315b1469](https://linux-hardware.org/?probe=e8315b1469) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [04e5b85d84](https://linux-hardware.org/?probe=04e5b85d84) | Feb 28, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [310ae04477](https://linux-hardware.org/?probe=310ae04477) | Feb 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [046814376c](https://linux-hardware.org/?probe=046814376c) | Feb 20, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a417965167](https://linux-hardware.org/?probe=a417965167) | Feb 19, 2020 |
| Intel         | DH77DF AAG40293-301         | Desktop     | [ac00169b1c](https://linux-hardware.org/?probe=ac00169b1c) | Feb 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [cef9a00862](https://linux-hardware.org/?probe=cef9a00862) | Feb 12, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [dcc65f9ee3](https://linux-hardware.org/?probe=dcc65f9ee3) | Feb 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [900a11f8b3](https://linux-hardware.org/?probe=900a11f8b3) | Feb 10, 2020 |
| MSI           | GS73VR 7RG                  | Notebook    | [fbdf43d1d6](https://linux-hardware.org/?probe=fbdf43d1d6) | Feb 04, 2020 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [20d5a3bd6a](https://linux-hardware.org/?probe=20d5a3bd6a) | Feb 01, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cf4dbec684](https://linux-hardware.org/?probe=cf4dbec684) | Feb 01, 2020 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Gigabyte      | P55A-UD3                    | Desktop     | [7168fd0137](https://linux-hardware.org/?probe=7168fd0137) | Jan 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [1007637420](https://linux-hardware.org/?probe=1007637420) | Dec 31, 2019 |
| Unknown       | Unknown                     | Notebook    | [bb58a92938](https://linux-hardware.org/?probe=bb58a92938) | Dec 31, 2019 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [b2d6dabaa7](https://linux-hardware.org/?probe=b2d6dabaa7) | Dec 23, 2019 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [e3b6ce369a](https://linux-hardware.org/?probe=e3b6ce369a) | Dec 23, 2019 |
| Dell          | XPS 13 9370                 | Notebook    | [0f39165d62](https://linux-hardware.org/?probe=0f39165d62) | Dec 06, 2019 |
| Dell          | XPS 13 9370                 | Notebook    | [816ad4feea](https://linux-hardware.org/?probe=816ad4feea) | Dec 06, 2019 |
| ASUSTek       | X556URK                     | Notebook    | [78f15ad5f0](https://linux-hardware.org/?probe=78f15ad5f0) | Nov 30, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [49e2cab57b](https://linux-hardware.org/?probe=49e2cab57b) | Nov 28, 2019 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [042c4b3c5a](https://linux-hardware.org/?probe=042c4b3c5a) | Nov 22, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [f63dcc4fc8](https://linux-hardware.org/?probe=f63dcc4fc8) | Nov 07, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [15f84fa3f2](https://linux-hardware.org/?probe=15f84fa3f2) | Oct 26, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3497939f58](https://linux-hardware.org/?probe=3497939f58) | Oct 18, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a04ed98be8](https://linux-hardware.org/?probe=a04ed98be8) | Oct 18, 2019 |
| CompuLab      | Airtop                      | Mini pc     | [ff3ce414e4](https://linux-hardware.org/?probe=ff3ce414e4) | Oct 16, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [b2ebcf2c70](https://linux-hardware.org/?probe=b2ebcf2c70) | Oct 10, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [43a5e168a1](https://linux-hardware.org/?probe=43a5e168a1) | Oct 10, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [3392a03f3c](https://linux-hardware.org/?probe=3392a03f3c) | Oct 03, 2019 |
| Unknown       | Unknown                     | Notebook    | [f8f1207d2d](https://linux-hardware.org/?probe=f8f1207d2d) | Sep 29, 2019 |
| Unknown       | Unknown                     | Notebook    | [d19b3f1330](https://linux-hardware.org/?probe=d19b3f1330) | Sep 28, 2019 |
| Unknown       | Unknown                     | Notebook    | [a6d4347345](https://linux-hardware.org/?probe=a6d4347345) | Sep 28, 2019 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [4302e84025](https://linux-hardware.org/?probe=4302e84025) | Sep 24, 2019 |
| Acer          | Aspire S3-371               | Notebook    | [5086f9ddaa](https://linux-hardware.org/?probe=5086f9ddaa) | Sep 07, 2019 |
| Acer          | Aspire S3-371               | Notebook    | [aa8140a178](https://linux-hardware.org/?probe=aa8140a178) | Sep 03, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [e8ccb234ed](https://linux-hardware.org/?probe=e8ccb234ed) | Aug 30, 2019 |
| ASRock        | B75M R2.0                   | Desktop     | [1479826c17](https://linux-hardware.org/?probe=1479826c17) | Aug 28, 2019 |
| Hardkernel    | ODROID-H2                   | Desktop     | [26d6c60ad5](https://linux-hardware.org/?probe=26d6c60ad5) | Jul 06, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [ea2ad2bc4d](https://linux-hardware.org/?probe=ea2ad2bc4d) | Jun 05, 2019 |
| ASUSTek       | TUF GAMING FX504GM_FX80G... | Notebook    | [7e9553ea70](https://linux-hardware.org/?probe=7e9553ea70) | Jun 03, 2019 |
| Lenovo        | ThinkPad T430 2342AG4       | Notebook    | [cf7413e712](https://linux-hardware.org/?probe=cf7413e712) | May 31, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [e8a5c28644](https://linux-hardware.org/?probe=e8a5c28644) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [b67f52c0c2](https://linux-hardware.org/?probe=b67f52c0c2) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [c408ceb62e](https://linux-hardware.org/?probe=c408ceb62e) | May 29, 2019 |
| Dell          | Latitude E4310              | Notebook    | [134afc5b6b](https://linux-hardware.org/?probe=134afc5b6b) | May 08, 2019 |
| Lenovo        | ThinkPad T520 4242BC5       | Notebook    | [977c44b97a](https://linux-hardware.org/?probe=977c44b97a) | Apr 29, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | Notebook    | [5801835e32](https://linux-hardware.org/?probe=5801835e32) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | Notebook    | [0f4999f205](https://linux-hardware.org/?probe=0f4999f205) | Apr 27, 2019 |
| Dell          | 0CRH6C A01                  | Desktop     | [23dcf2aff6](https://linux-hardware.org/?probe=23dcf2aff6) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [61bb547684](https://linux-hardware.org/?probe=61bb547684) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [8549b6dfd8](https://linux-hardware.org/?probe=8549b6dfd8) | Apr 08, 2019 |
| Unknown       | A11-COMPUTER                | Notebook    | [fae06bb10f](https://linux-hardware.org/?probe=fae06bb10f) | Mar 28, 2019 |
| Unknown       | A11-COMPUTER                | Notebook    | [427daf4d4e](https://linux-hardware.org/?probe=427daf4d4e) | Mar 28, 2019 |
| Lenovo        | ThinkPad W530 24384KU       | Notebook    | [2064d92892](https://linux-hardware.org/?probe=2064d92892) | Dec 12, 2018 |
| Dell          | XPS 13 9350                 | Notebook    | [6fb539c340](https://linux-hardware.org/?probe=6fb539c340) | Oct 29, 2018 |
| ASRock        | Z270 Killer SLI             | Desktop     | [a03ea38833](https://linux-hardware.org/?probe=a03ea38833) | Jul 06, 2018 |
| HP            | ProBook 4540s               | Notebook    | [ace9a95fb7](https://linux-hardware.org/?probe=ace9a95fb7) | May 09, 2018 |
| HP            | ProBook 4540s               | Notebook    | [8f50260d94](https://linux-hardware.org/?probe=8f50260d94) | May 09, 2018 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [17f0958960](https://linux-hardware.org/?probe=17f0958960) | Oct 06, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hong_Kong/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 50        | 13.7%   |
| Ubuntu 22.04        | 24        | 6.58%   |
| Ubuntu 18.04        | 23        | 6.3%    |
| Arch Rolling        | 14        | 3.84%   |
| OpenMandriva 4.2    | 13        | 3.56%   |
| Debian 11           | 12        | 3.29%   |
| Arch                | 11        | 3.01%   |
| antiX 21            | 9         | 2.47%   |
| Ubuntu 19.10        | 8         | 2.19%   |
| Pop!_OS 22.04       | 7         | 1.92%   |
| OpenMandriva 4.3    | 7         | 1.92%   |
| KDE neon 20.04      | 7         | 1.92%   |
| Fedora 37           | 7         | 1.92%   |
| Ubuntu 20.10        | 6         | 1.64%   |
| Gentoo 2.7          | 6         | 1.64%   |
| Fedora 35           | 6         | 1.64%   |
| Fedora 32           | 6         | 1.64%   |
| ArcoLinux Rolling   | 6         | 1.64%   |
| Fedora 36           | 5         | 1.37%   |
| EndeavourOS Rolling | 5         | 1.37%   |
| Ubuntu 22.10        | 4         | 1.1%    |
| Ubuntu 21.04        | 4         | 1.1%    |
| Ubuntu 19.04        | 4         | 1.1%    |
| Pop!_OS 20.10       | 4         | 1.1%    |
| Linux Mint 20       | 4         | 1.1%    |
| Fedora 33           | 4         | 1.1%    |
| Ubuntu 21.10        | 3         | 0.82%   |
| Ubuntu 16.04        | 3         | 0.82%   |
| OpenMandriva 4.50   | 3         | 0.82%   |
| OpenMandriva 23.01  | 3         | 0.82%   |
| Linux Mint 20.3     | 3         | 0.82%   |
| Gentoo 2.8          | 3         | 0.82%   |
| Elementary 5.1.7    | 3         | 0.82%   |
| Chrome OS           | 3         | 0.82%   |
| Zorin 15            | 2         | 0.55%   |
| SteamOS 3.4         | 2         | 0.55%   |
| SteamOS 3.3         | 2         | 0.55%   |
| Slackware 15.0      | 2         | 0.55%   |
| PostmarketOS Edge   | 2         | 0.55%   |
| Pop!_OS 21.04       | 2         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu            | 123       | 34.84%  |
| Fedora            | 32        | 9.07%   |
| OpenMandriva      | 27        | 7.65%   |
| Arch              | 25        | 7.08%   |
| Pop!_OS           | 16        | 4.53%   |
| Debian            | 14        | 3.97%   |
| Manjaro           | 10        | 2.83%   |
| Linux Mint        | 10        | 2.83%   |
| Gentoo            | 9         | 2.55%   |
| antiX             | 9         | 2.55%   |
| KDE neon          | 7         | 1.98%   |
| EndeavourOS       | 6         | 1.7%    |
| Clear Linux       | 6         | 1.7%    |
| ArcoLinux         | 6         | 1.7%    |
| SteamOS           | 4         | 1.13%   |
| Kubuntu           | 4         | 1.13%   |
| Elementary        | 4         | 1.13%   |
| Zorin             | 3         | 0.85%   |
| Ubuntu Unity      | 3         | 0.85%   |
| Ubuntu MATE       | 3         | 0.85%   |
| Slackware         | 3         | 0.85%   |
| ROSA              | 3         | 0.85%   |
| Chrome OS         | 3         | 0.85%   |
| CentOS            | 3         | 0.85%   |
| PostmarketOS      | 2         | 0.57%   |
| Parrot            | 2         | 0.57%   |
| Kali              | 2         | 0.57%   |
| Xubuntu           | 1         | 0.28%   |
| Ultramarine Linux | 1         | 0.28%   |
| UbuntuDDE         | 1         | 0.28%   |
| Ubuntu Budgie     | 1         | 0.28%   |
| Raspbian          | 1         | 0.28%   |
| PCLinuxOS         | 1         | 0.28%   |
| Oracle Linux      | 1         | 0.28%   |
| openSUSE          | 1         | 0.28%   |
| Nobara            | 1         | 0.28%   |
| Lubuntu           | 1         | 0.28%   |
| Kylin             | 1         | 0.28%   |
| Guix              | 1         | 0.28%   |
| BlackPanther      | 1         | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002  | 12        | 3.01%   |
| 5.4.0-42-generic          | 9         | 2.26%   |
| 4.9.0-279-antix.1-486-smp | 8         | 2.01%   |
| 5.16.7-desktop-1omv4003   | 7         | 1.75%   |
| 5.15.0-46-generic         | 5         | 1.25%   |
| 5.15.0-52-generic         | 4         | 1%      |
| 5.13.0-39-generic         | 4         | 1%      |
| 5.13.0-35-generic         | 4         | 1%      |
| 6.1.1-desktop-1omv2290    | 3         | 0.75%   |
| 5.8.0-7630-generic        | 3         | 0.75%   |
| 5.8.0-55-generic          | 3         | 0.75%   |
| 5.8.0-43-generic          | 3         | 0.75%   |
| 5.4.0-48-generic          | 3         | 0.75%   |
| 5.4.0-33-generic          | 3         | 0.75%   |
| 5.4.0-28-generic          | 3         | 0.75%   |
| 5.4.0-26-generic          | 3         | 0.75%   |
| 5.3.0-46-generic          | 3         | 0.75%   |
| 5.15.0-58-generic         | 3         | 0.75%   |
| 5.15.0-47-generic         | 3         | 0.75%   |
| 5.11.0-37-generic         | 3         | 0.75%   |
| 4.19.49+                  | 3         | 0.75%   |
| 6.1.1-arch1-1             | 2         | 0.5%    |
| 6.0.12-300.fc37.x86_64    | 2         | 0.5%    |
| 5.9.2-arch1-1             | 2         | 0.5%    |
| 5.5.0-1parrot1-amd64      | 2         | 0.5%    |
| 5.4.0-58-generic          | 2         | 0.5%    |
| 5.4.0-56-generic          | 2         | 0.5%    |
| 5.4.0-52-generic          | 2         | 0.5%    |
| 5.4.0-47-generic          | 2         | 0.5%    |
| 5.4.0-109-generic         | 2         | 0.5%    |
| 5.3.0-24-generic          | 2         | 0.5%    |
| 5.3.0-18-generic          | 2         | 0.5%    |
| 5.19.0-76051900-generic   | 2         | 0.5%    |
| 5.19.0-31-generic         | 2         | 0.5%    |
| 5.17.5-76051705-generic   | 2         | 0.5%    |
| 5.17.11-300.fc36.x86_64   | 2         | 0.5%    |
| 5.16.12-200.fc35.x86_64   | 2         | 0.5%    |
| 5.15.0-60-generic         | 2         | 0.5%    |
| 5.15.0-56-generic         | 2         | 0.5%    |
| 5.15.0-53-generic         | 2         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 41        | 10.9%   |
| 5.15.0  | 29        | 7.71%   |
| 5.8.0   | 22        | 5.85%   |
| 5.13.0  | 21        | 5.59%   |
| 5.11.0  | 15        | 3.99%   |
| 4.15.0  | 14        | 3.72%   |
| 5.3.0   | 12        | 3.19%   |
| 5.19.0  | 12        | 3.19%   |
| 5.10.14 | 12        | 3.19%   |
| 5.0.0   | 10        | 2.66%   |
| 4.9.0   | 9         | 2.39%   |
| 5.10.0  | 8         | 2.13%   |
| 5.16.7  | 7         | 1.86%   |
| 6.1.1   | 6         | 1.6%    |
| 4.18.0  | 5         | 1.33%   |
| 6.0.0   | 4         | 1.06%   |
| 5.17.5  | 4         | 1.06%   |
| 6.0.12  | 3         | 0.8%    |
| 4.19.49 | 3         | 0.8%    |
| 6.1.14  | 2         | 0.53%   |
| 6.1.11  | 2         | 0.53%   |
| 5.9.2   | 2         | 0.53%   |
| 5.5.0   | 2         | 0.53%   |
| 5.19.13 | 2         | 0.53%   |
| 5.18.5  | 2         | 0.53%   |
| 5.17.4  | 2         | 0.53%   |
| 5.17.11 | 2         | 0.53%   |
| 5.16.12 | 2         | 0.53%   |
| 5.16.11 | 2         | 0.53%   |
| 5.15.74 | 2         | 0.53%   |
| 5.14.14 | 2         | 0.53%   |
| 5.14.0  | 2         | 0.53%   |
| 5.11.12 | 2         | 0.53%   |
| 5.10.76 | 2         | 0.53%   |
| 6.2.7   | 1         | 0.27%   |
| 6.2.6   | 1         | 0.27%   |
| 6.1.9   | 1         | 0.27%   |
| 6.1.7   | 1         | 0.27%   |
| 6.1.5   | 1         | 0.27%   |
| 6.1.18  | 1         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 11.11%  |
| 5.15    | 41        | 11.11%  |
| 5.10    | 32        | 8.67%   |
| 5.8     | 28        | 7.59%   |
| 5.13    | 25        | 6.78%   |
| 5.19    | 22        | 5.96%   |
| 5.11    | 22        | 5.96%   |
| 6.1     | 15        | 4.07%   |
| 5.3     | 15        | 4.07%   |
| 5.16    | 14        | 3.79%   |
| 4.15    | 14        | 3.79%   |
| 5.17    | 13        | 3.52%   |
| 4.9     | 13        | 3.52%   |
| 6.0     | 10        | 2.71%   |
| 5.9     | 10        | 2.71%   |
| 5.0     | 10        | 2.71%   |
| 5.18    | 7         | 1.9%    |
| 5.14    | 7         | 1.9%    |
| 5.7     | 6         | 1.63%   |
| 4.18    | 6         | 1.63%   |
| 5.6     | 3         | 0.81%   |
| 5.5     | 3         | 0.81%   |
| 5.12    | 3         | 0.81%   |
| 4.19    | 3         | 0.81%   |
| 6.2     | 2         | 0.54%   |
| 4.4     | 2         | 0.54%   |
| 4.17    | 1         | 0.27%   |
| 3.10    | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 320       | 93.29%  |
| i686    | 12        | 3.5%    |
| aarch64 | 9         | 2.62%   |
| i586    | 1         | 0.29%   |
| armv7l  | 1         | 0.29%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 166       | 47.03%  |
| KDE5       | 70        | 19.83%  |
| Unknown    | 59        | 16.71%  |
| XFCE       | 13        | 3.68%   |
| KDE        | 8         | 2.27%   |
| X-Cinnamon | 7         | 1.98%   |
| MATE       | 5         | 1.42%   |
| i3         | 4         | 1.13%   |
| Pantheon   | 3         | 0.85%   |
| Unity      | 2         | 0.57%   |
| sway       | 2         | 0.57%   |
| openbox    | 2         | 0.57%   |
| LXDE       | 2         | 0.57%   |
| dwm        | 2         | 0.57%   |
| Deepin     | 2         | 0.57%   |
| LXQt       | 1         | 0.28%   |
| KDE4       | 1         | 0.28%   |
| fvwm       | 1         | 0.28%   |
| Cinnamon   | 1         | 0.28%   |
| Budgie     | 1         | 0.28%   |
| awesome    | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 263       | 74.29%  |
| Wayland | 61        | 17.23%  |
| Unknown | 20        | 5.65%   |
| Tty     | 10        | 2.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 158       | 44.89%  |
| SDDM    | 68        | 19.32%  |
| GDM     | 49        | 13.92%  |
| GDM3    | 40        | 11.36%  |
| LightDM | 25        | 7.1%    |
| TDM     | 7         | 1.99%   |
| Ly      | 2         | 0.57%   |
| XDM     | 1         | 0.28%   |
| LXDM    | 1         | 0.28%   |
| KDM     | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 136       | 37.99%  |
| en_HK   | 91        | 25.42%  |
| zh_CN   | 39        | 10.89%  |
| Unknown | 34        | 9.5%    |
| zh_TW   | 19        | 5.31%   |
| zh_HK   | 13        | 3.63%   |
| en_GB   | 10        | 2.79%   |
| C       | 9         | 2.51%   |
| en_AU   | 3         | 0.84%   |
| zh_SG   | 1         | 0.28%   |
| it_IT   | 1         | 0.28%   |
| en_ZA   | 1         | 0.28%   |
| de_DE   | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 215       | 61.78%  |
| BIOS | 133       | 38.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 253       | 72.08%  |
| Btrfs   | 46        | 13.11%  |
| Overlay | 23        | 6.55%   |
| Xfs     | 9         | 2.56%   |
| Unknown | 8         | 2.28%   |
| Zfs     | 7         | 1.99%   |
| Ext3    | 2         | 0.57%   |
| Ext2    | 2         | 0.57%   |
| F2fs    | 1         | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 167       | 47.99%  |
| Unknown | 146       | 41.95%  |
| MBR     | 35        | 10.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 296       | 84.33%  |
| Yes       | 55        | 15.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 228       | 65.33%  |
| Yes       | 121       | 34.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 70        | 20.41%  |
| ASUSTek Computer        | 49        | 14.29%  |
| Dell                    | 34        | 9.91%   |
| MSI                     | 28        | 8.16%   |
| Hewlett-Packard         | 28        | 8.16%   |
| Gigabyte Technology     | 24        | 7%      |
| ASRock                  | 14        | 4.08%   |
| Fujitsu                 | 12        | 3.5%    |
| Unknown                 | 12        | 3.5%    |
| Acer                    | 9         | 2.62%   |
| Apple                   | 7         | 2.04%   |
| Intel                   | 5         | 1.46%   |
| HUAWEI                  | 5         | 1.46%   |
| Raspberry Pi Foundation | 4         | 1.17%   |
| Supermicro              | 3         | 0.87%   |
| Samsung Electronics     | 3         | 0.87%   |
| GPD                     | 3         | 0.87%   |
| AMI                     | 3         | 0.87%   |
| Toshiba                 | 2         | 0.58%   |
| Timi                    | 2         | 0.58%   |
| KOHJINSHA               | 2         | 0.58%   |
| IBM                     | 2         | 0.58%   |
| AOKZOE                  | 2         | 0.58%   |
| ZOTAC                   | 1         | 0.29%   |
| Valve                   | 1         | 0.29%   |
| Soyo                    | 1         | 0.29%   |
| Sony                    | 1         | 0.29%   |
| Seco                    | 1         | 0.29%   |
| Schenker                | 1         | 0.29%   |
| Panasonic               | 1         | 0.29%   |
| ONE-NETBOOK             | 1         | 0.29%   |
| Nvidia                  | 1         | 0.29%   |
| METAPHYUNI              | 1         | 0.29%   |
| Jumper                  | 1         | 0.29%   |
| Intel Client Systems    | 1         | 0.29%   |
| Huanan                  | 1         | 0.29%   |
| Hardkernel              | 1         | 0.29%   |
| Google                  | 1         | 0.29%   |
| Foxconn                 | 1         | 0.29%   |
| CompuLab                | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 13        | 3.79%   |
| MSI MS-7C94                            | 3         | 0.87%   |
| Lenovo Legion R7000 2020 82B6          | 3         | 0.87%   |
| ASUS H110I-PLUS                        | 3         | 0.87%   |
| ASUS All Series                        | 3         | 0.87%   |
| RPi Raspberry Pi                       | 2         | 0.58%   |
| MSI MS-7D42                            | 2         | 0.58%   |
| MSI MS-7C02                            | 2         | 0.58%   |
| MSI MS-7B93                            | 2         | 0.58%   |
| IBM 260921H                            | 2         | 0.58%   |
| HUAWEI KPRC-WX0                        | 2         | 0.58%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC       | 2         | 0.58%   |
| HP ProDesk 600 G1 SFF                  | 2         | 0.58%   |
| HP EliteBook 2540p                     | 2         | 0.58%   |
| Gigabyte X570 AORUS ELITE              | 2         | 0.58%   |
| Fujitsu UH-X                           | 2         | 0.58%   |
| Fujitsu LIFEBOOK AH544                 | 2         | 0.58%   |
| Dell XPS 13 9310                       | 2         | 0.58%   |
| Dell Inspiron 5580                     | 2         | 0.58%   |
| ASUS Z8NA-D6                           | 2         | 0.58%   |
| ASUS VM65                              | 2         | 0.58%   |
| ASUS VM62                              | 2         | 0.58%   |
| ASUS TUF Gaming FA506IU_FA506IU        | 2         | 0.58%   |
| ASRock H410M-ITX/ac                    | 2         | 0.58%   |
| ASRock H410M-HDV                       | 2         | 0.58%   |
| AOKZOE A1 AR07                         | 2         | 0.58%   |
| AMI Aptio CRB                          | 2         | 0.58%   |
| ZOTAC ZBOX-ID92/ZBOX-IQ01              | 1         | 0.29%   |
| Valve Jupiter                          | 1         | 0.29%   |
| Toshiba PORTEGE R830                   | 1         | 0.29%   |
| Toshiba dynabook R731/E                | 1         | 0.29%   |
| Timi TM1613                            | 1         | 0.29%   |
| Timi TM1607                            | 1         | 0.29%   |
| Supermicro X9DRD-7LN4F(-JBOD)/X9DRD-EF | 1         | 0.29%   |
| Supermicro PIO-617R-TLN4F+-ST031       | 1         | 0.29%   |
| Supermicro C2SBC-Q                     | 1         | 0.29%   |
| Soyo SY-A68M FS V2.0                   | 1         | 0.29%   |
| Sony VPCCB17FG                         | 1         | 0.29%   |
| Seco C40                               | 1         | 0.29%   |
| Schenker XMG_APEX15_XAP15E20           | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 28        | 8.16%   |
| Unknown            | 13        | 3.79%   |
| Dell Inspiron      | 10        | 2.92%   |
| Lenovo Legion      | 9         | 2.62%   |
| Dell XPS           | 9         | 2.62%   |
| Fujitsu LIFEBOOK   | 8         | 2.33%   |
| ASUS PRIME         | 7         | 2.04%   |
| Lenovo IdeaPad     | 6         | 1.75%   |
| Dell Precision     | 6         | 1.75%   |
| ASUS TUF           | 6         | 1.75%   |
| ASUS ROG           | 5         | 1.46%   |
| RPi Raspberry      | 4         | 1.17%   |
| Lenovo Yoga        | 4         | 1.17%   |
| Lenovo ThinkCentre | 4         | 1.17%   |
| Dell OptiPlex      | 4         | 1.17%   |
| Dell Latitude      | 4         | 1.17%   |
| Acer Swift         | 4         | 1.17%   |
| Acer Aspire        | 4         | 1.17%   |
| MSI MS-7C94        | 3         | 0.87%   |
| Lenovo ThinkBook   | 3         | 0.87%   |
| HP ZHAN            | 3         | 0.87%   |
| HP ProDesk         | 3         | 0.87%   |
| HP Pavilion        | 3         | 0.87%   |
| HP EliteBook       | 3         | 0.87%   |
| Gigabyte X570      | 3         | 0.87%   |
| ASUS H110I-PLUS    | 3         | 0.87%   |
| ASUS All           | 3         | 0.87%   |
| MSI MS-7D42        | 2         | 0.58%   |
| MSI MS-7C02        | 2         | 0.58%   |
| MSI MS-7B93        | 2         | 0.58%   |
| Lenovo IdeaPadFlex | 2         | 0.58%   |
| Lenovo IdeaCentre  | 2         | 0.58%   |
| IBM 260921H        | 2         | 0.58%   |
| HUAWEI KPRC-WX0    | 2         | 0.58%   |
| Gigabyte B450      | 2         | 0.58%   |
| Fujitsu UH-X       | 2         | 0.58%   |
| ASUS Z8NA-D6       | 2         | 0.58%   |
| ASUS VM65          | 2         | 0.58%   |
| ASUS VM62          | 2         | 0.58%   |
| ASRock H410M-ITX   | 2         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 49        | 14.29%  |
| 2020    | 45        | 13.12%  |
| 2019    | 34        | 9.91%   |
| 2021    | 33        | 9.62%   |
| 2014    | 20        | 5.83%   |
| 2022    | 18        | 5.25%   |
| 2013    | 18        | 5.25%   |
| 2011    | 18        | 5.25%   |
| 2016    | 17        | 4.96%   |
| 2010    | 16        | 4.66%   |
| 2015    | 15        | 4.37%   |
| 2012    | 14        | 4.08%   |
| 2017    | 13        | 3.79%   |
| Unknown | 9         | 2.62%   |
| 2008    | 8         | 2.33%   |
| 2009    | 6         | 1.75%   |
| 2007    | 4         | 1.17%   |
| 2023    | 2         | 0.58%   |
| 1999    | 2         | 0.58%   |
| 2005    | 1         | 0.29%   |
| 2003    | 1         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 178       | 51.9%   |
| Desktop        | 135       | 39.36%  |
| Mini pc        | 8         | 2.33%   |
| Convertible    | 7         | 2.04%   |
| System on chip | 6         | 1.75%   |
| Server         | 4         | 1.17%   |
| Tablet         | 3         | 0.87%   |
| All in one     | 2         | 0.58%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 316       | 92.13%  |
| Enabled  | 27        | 7.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 342       | 99.71%  |
| Yes  | 1         | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 79        | 22.7%   |
| 8.01-16.0   | 75        | 21.55%  |
| 4.01-8.0    | 58        | 16.67%  |
| 32.01-64.0  | 49        | 14.08%  |
| 3.01-4.0    | 37        | 10.63%  |
| 64.01-256.0 | 22        | 6.32%   |
| 24.01-32.0  | 8         | 2.3%    |
| 1.01-2.0    | 7         | 2.01%   |
| 2.01-3.0    | 6         | 1.72%   |
| 0.51-1.0    | 4         | 1.15%   |
| 0.01-0.5    | 3         | 0.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 104       | 27.96%  |
| 2.01-3.0   | 85        | 22.85%  |
| 4.01-8.0   | 65        | 17.47%  |
| 3.01-4.0   | 52        | 13.98%  |
| 8.01-16.0  | 24        | 6.45%   |
| 0.01-0.5   | 18        | 4.84%   |
| 0.51-1.0   | 15        | 4.03%   |
| 16.01-24.0 | 7         | 1.88%   |
| 32.01-64.0 | 1         | 0.27%   |
| 24.01-32.0 | 1         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 188       | 52.81%  |
| 2      | 109       | 30.62%  |
| 3      | 32        | 8.99%   |
| 5      | 9         | 2.53%   |
| 4      | 7         | 1.97%   |
| 0      | 5         | 1.4%    |
| 9      | 2         | 0.56%   |
| 6      | 2         | 0.56%   |
| 11     | 1         | 0.28%   |
| 7      | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 267       | 77.17%  |
| Yes       | 79        | 22.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 277       | 80.52%  |
| No        | 67        | 19.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 268       | 77.01%  |
| No        | 80        | 22.99%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 226       | 64.76%  |
| No        | 123       | 35.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Hong Kong | 343       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Central          | 189       | 52.21%  |
| Kowloon          | 17        | 4.7%    |
| Tuen Mun         | 13        | 3.59%   |
| Shatin           | 13        | 3.59%   |
| Hong Kong        | 12        | 3.31%   |
| Tseung Kwan O    | 11        | 3.04%   |
| Wanchai          | 9         | 2.49%   |
| Tai Po           | 7         | 1.93%   |
| Hung Hom         | 7         | 1.93%   |
| Tung Chung       | 6         | 1.66%   |
| Ngau Wu Tok      | 6         | 1.66%   |
| Yuen Long        | 5         | 1.38%   |
| Sai Kung         | 5         | 1.38%   |
| To Kwa Wan       | 4         | 1.1%    |
| Quarry Bay       | 3         | 0.83%   |
| Ma On Shan Tsuen | 3         | 0.83%   |
| Kowloon Bay      | 3         | 0.83%   |
| Ho Man Tin       | 3         | 0.83%   |
| Yau Tsim Mong    | 2         | 0.55%   |
| Wong Tai Sin     | 2         | 0.55%   |
| Tsuen Wan        | 2         | 0.55%   |
| Tsimshatsui      | 2         | 0.55%   |
| Tai Wan To       | 2         | 0.55%   |
| Sheung Shui      | 2         | 0.55%   |
| Sha Tin Wai      | 2         | 0.55%   |
| Mong Kok         | 2         | 0.55%   |
| Man Kok          | 2         | 0.55%   |
| Kwun Hang        | 2         | 0.55%   |
| Kwu Tung         | 2         | 0.55%   |
| Fanling          | 2         | 0.55%   |
| Discovery Bay    | 2         | 0.55%   |
| Cheung Sha Lan   | 2         | 0.55%   |
| Tuen Mun San Hui | 1         | 0.28%   |
| Tin Shui Wai     | 1         | 0.28%   |
| Tai Wan          | 1         | 0.28%   |
| Tai Kok Tsui     | 1         | 0.28%   |
| So Kon Po        | 1         | 0.28%   |
| Shau Kei Wan     | 1         | 0.28%   |
| Sham Shui Po     | 1         | 0.28%   |
| North Point      | 1         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                   | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Samsung Electronics      | 81        | 103    | 15.06%  |
| WDC                      | 69        | 99     | 12.83%  |
| Seagate                  | 60        | 83     | 11.15%  |
| Sandisk                  | 31        | 35     | 5.76%   |
| Toshiba                  | 28        | 37     | 5.2%    |
| Unknown                  | 22        | 26     | 4.09%   |
| Kingston                 | 22        | 25     | 4.09%   |
| Hitachi                  | 16        | 21     | 2.97%   |
| SK hynix                 | 15        | 21     | 2.79%   |
| Intel                    | 15        | 22     | 2.79%   |
| A-DATA Technology        | 15        | 21     | 2.79%   |
| Crucial                  | 14        | 25     | 2.6%    |
| HGST                     | 11        | 13     | 2.04%   |
| Micron Technology        | 9         | 10     | 1.67%   |
| Silicon Motion           | 8         | 10     | 1.49%   |
| Fujitsu                  | 8         | 15     | 1.49%   |
| Apple                    | 7         | 16     | 1.3%    |
| Transcend                | 6         | 7      | 1.12%   |
| Phison                   | 6         | 9      | 1.12%   |
| JMicron Technology       | 6         | 10     | 1.12%   |
| Hikvision                | 5         | 5      | 0.93%   |
| Plextor                  | 4         | 5      | 0.74%   |
| LITEON                   | 4         | 4      | 0.74%   |
| HS-SSD-C100              | 4         | 5      | 0.74%   |
| China                    | 4         | 5      | 0.74%   |
| Unknown                  | 4         | 4      | 0.74%   |
| ZHITAI                   | 3         | 4      | 0.56%   |
| Team                     | 3         | 3      | 0.56%   |
| KIOXIA                   | 3         | 3      | 0.56%   |
| DOGGO                    | 3         | 3      | 0.56%   |
| BIWIN                    | 3         | 3      | 0.56%   |
| TO Exter                 | 2         | 2      | 0.37%   |
| Netac                    | 2         | 2      | 0.37%   |
| Lite-On                  | 2         | 4      | 0.37%   |
| Lexar                    | 2         | 2      | 0.37%   |
| KingSpec                 | 2         | 3      | 0.37%   |
| Gigabyte Technology      | 2         | 5      | 0.37%   |
| Biwin Storage Technology | 2         | 2      | 0.37%   |
| Apacer                   | 2         | 7      | 0.37%   |
| ZX1 1TB                  | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB           | 6         | 1.04%   |
| Samsung SSD 860 EVO 1TB          | 6         | 1.04%   |
| Samsung NVMe SSD Drive 512GB     | 6         | 1.04%   |
| Unknown MMC Card  64GB           | 5         | 0.86%   |
| JMicron Generic 500GB            | 5         | 0.86%   |
| Fujitsu F300 480GB               | 5         | 0.86%   |
| Crucial CT500MX500SSD1 500GB     | 5         | 0.86%   |
| A-DATA SP550 240GB SSD           | 5         | 0.86%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 4         | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4         | 0.69%   |
| Unknown MMC Card  32GB           | 4         | 0.69%   |
| Toshiba DT01ACA050 500GB         | 4         | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB   | 4         | 0.69%   |
| SanDisk NVMe SSD Drive 1TB       | 4         | 0.69%   |
| Samsung NVMe SSD Drive 1024GB    | 4         | 0.69%   |
| Kingston SA400S37480G 480GB SSD  | 4         | 0.69%   |
| Unknown                          | 4         | 0.69%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 3         | 0.52%   |
| WDC WD30EZRX-00D8PB0 3TB         | 3         | 0.52%   |
| Toshiba DT01ACA300 3TB           | 3         | 0.52%   |
| Seagate ST500DM002-1BD142 500GB  | 3         | 0.52%   |
| Seagate ST3500418AS 500GB        | 3         | 0.52%   |
| Seagate ST3500413AS 500GB        | 3         | 0.52%   |
| Seagate ST2000LM007-1R8174 2TB   | 3         | 0.52%   |
| Seagate ST2000DM008-2FR102 2TB   | 3         | 0.52%   |
| SanDisk NVMe SSD Drive 512GB     | 3         | 0.52%   |
| Samsung SSD 980 1TB              | 3         | 0.52%   |
| Samsung SSD 970 EVO Plus 2TB     | 3         | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB     | 3         | 0.52%   |
| Samsung SSD 860 EVO 250GB        | 3         | 0.52%   |
| Samsung NVMe SSD Drive 1TB       | 3         | 0.52%   |
| Samsung MZVL2512HCJQ-00BL7 512GB | 3         | 0.52%   |
| Kingston SA400S37120G 120GB SSD  | 3         | 0.52%   |
| DOGGO DQ-60G SSD                 | 3         | 0.52%   |
| Crucial CT1000MX500SSD1 1TB      | 3         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2         | 0.35%   |
| WDC WDS200T2B0A 2TB SSD          | 2         | 0.35%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 2         | 0.35%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 2         | 0.35%   |
| WDC WD10SPZX-22Z10T1 1TB         | 2         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 60        | 83     | 37.5%   |
| WDC                 | 41        | 64     | 25.63%  |
| Toshiba             | 24        | 33     | 15%     |
| Hitachi             | 16        | 21     | 10%     |
| HGST                | 11        | 13     | 6.88%   |
| Fujitsu             | 2         | 2      | 1.25%   |
| Unknown             | 1         | 1      | 0.63%   |
| Samsung Electronics | 1         | 1      | 0.63%   |
| Maxtor              | 1         | 1      | 0.63%   |
| JMicron Technology  | 1         | 2      | 0.63%   |
| HGST HTS            | 1         | 1      | 0.63%   |
| Apple               | 1         | 1      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 40     | 17.18%  |
| Kingston            | 15        | 17     | 9.2%    |
| Crucial             | 13        | 24     | 7.98%   |
| WDC                 | 12        | 12     | 7.36%   |
| A-DATA Technology   | 12        | 18     | 7.36%   |
| SanDisk             | 7         | 7      | 4.29%   |
| Transcend           | 6         | 7      | 3.68%   |
| Intel               | 6         | 11     | 3.68%   |
| JMicron Technology  | 5         | 8      | 3.07%   |
| Fujitsu             | 5         | 12     | 3.07%   |
| China               | 4         | 5      | 2.45%   |
| Team                | 3         | 3      | 1.84%   |
| SK hynix            | 3         | 7      | 1.84%   |
| Plextor             | 3         | 4      | 1.84%   |
| LITEON              | 3         | 3      | 1.84%   |
| DOGGO               | 3         | 3      | 1.84%   |
| Apple               | 3         | 3      | 1.84%   |
| ZHITAI              | 2         | 2      | 1.23%   |
| TO Exter            | 2         | 2      | 1.23%   |
| Netac               | 2         | 2      | 1.23%   |
| Micron Technology   | 2         | 3      | 1.23%   |
| Lexar               | 2         | 2      | 1.23%   |
| HS-SSD-C100         | 2         | 2      | 1.23%   |
| Hikvision           | 2         | 2      | 1.23%   |
| Apacer              | 2         | 7      | 1.23%   |
| Verbatim            | 1         | 2      | 0.61%   |
| Unknown (CF)        | 1         | 1      | 0.61%   |
| tigo                | 1         | 1      | 0.61%   |
| SPCC                | 1         | 1      | 0.61%   |
| RECADATA            | 1         | 1      | 0.61%   |
| Ramsta              | 1         | 1      | 0.61%   |
| PNY                 | 1         | 1      | 0.61%   |
| OCZ                 | 1         | 1      | 0.61%   |
| KLEVV               | 1         | 1      | 0.61%   |
| Dogfish             | 1         | 1      | 0.61%   |
| DGM                 | 1         | 1      | 0.61%   |
| Corsair             | 1         | 1      | 0.61%   |
| BIWIN               | 1         | 1      | 0.61%   |
| Aoluska             | 1         | 1      | 0.61%   |
| AGI                 | 1         | 1      | 0.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 161       | 228    | 33.97%  |
| SSD     | 140       | 223    | 29.54%  |
| HDD     | 138       | 223    | 29.11%  |
| MMC     | 22        | 26     | 4.64%   |
| Unknown | 13        | 16     | 2.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 219       | 427    | 50.93%  |
| NVMe | 160       | 225    | 37.21%  |
| SAS  | 29        | 38     | 6.74%   |
| MMC  | 22        | 26     | 5.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 159       | 261    | 56.38%  |
| 0.51-1.0        | 73        | 96     | 25.89%  |
| 1.01-2.0        | 23        | 29     | 8.16%   |
| 2.01-3.0        | 10        | 16     | 3.55%   |
| 3.01-4.0        | 8         | 29     | 2.84%   |
| 4.01-10.0       | 7         | 11     | 2.48%   |
| More than 100.0 | 1         | 1      | 0.35%   |
| 10.01-20.0      | 1         | 3      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 90        | 24.66%  |
| 251-500        | 68        | 18.63%  |
| 501-1000       | 51        | 13.97%  |
| 1001-2000      | 37        | 10.14%  |
| 51-100         | 33        | 9.04%   |
| 1-20           | 30        | 8.22%   |
| More than 3000 | 17        | 4.66%   |
| 2001-3000      | 15        | 4.11%   |
| Unknown        | 13        | 3.56%   |
| 21-50          | 11        | 3.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 157       | 41.1%   |
| 101-250        | 45        | 11.78%  |
| 251-500        | 42        | 10.99%  |
| 21-50          | 42        | 10.99%  |
| 51-100         | 39        | 10.21%  |
| 501-1000       | 20        | 5.24%   |
| 1001-2000      | 15        | 3.93%   |
| Unknown        | 13        | 3.4%    |
| 2001-3000      | 6         | 1.57%   |
| More than 3000 | 3         | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB                 | 2         | 2      | 6.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD          | 1         | 1      | 3.23%   |
| WDC WD30EZRX-00D8PB0 3TB                  | 1         | 1      | 3.23%   |
| WDC WD10EZEX-60WN4A1 1TB                  | 1         | 1      | 3.23%   |
| WDC WD10EZEX-00RKKA0 1TB                  | 1         | 1      | 3.23%   |
| WDC WD10EALS-00Z8A0 1TB                   | 1         | 2      | 3.23%   |
| Toshiba MK1252GSX 120GB                   | 1         | 1      | 3.23%   |
| Toshiba DT01ACA100 1TB                    | 1         | 1      | 3.23%   |
| SK hynix BC711 HFM512GD3JX013N 512GB      | 1         | 1      | 3.23%   |
| Seagate ST9500325AS 500GB                 | 1         | 1      | 3.23%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 3.23%   |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 3.23%   |
| Seagate ST3160815AS 160GB                 | 1         | 1      | 3.23%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB       | 1         | 1      | 3.23%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD       | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 870 EVO 500GB     | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 860 EVO 1TB       | 1         | 1      | 3.23%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD | 1         | 1      | 3.23%   |
| Kingston SV300S37A120G 120GB SSD          | 1         | 1      | 3.23%   |
| Kingston SA400S37480G 480GB SSD           | 1         | 1      | 3.23%   |
| Intel SSDPEKKW128G7 128GB                 | 1         | 1      | 3.23%   |
| Hitachi HTS725050A7E630 500GB             | 1         | 1      | 3.23%   |
| Hitachi HTS723216L9A360 160GB             | 1         | 1      | 3.23%   |
| Hitachi HTS542512K9SA00 120GB             | 1         | 1      | 3.23%   |
| Hitachi HTC426040G8CE00 40GB              | 1         | 1      | 3.23%   |
| HGST TOURO Mobile 1TB                     | 1         | 1      | 3.23%   |
| HGST HTS 541010A9E680 1TB                 | 1         | 1      | 3.23%   |
| DGM SSD 120GB S3-120A                     | 1         | 1      | 3.23%   |
| Crucial CT500MX500SSD1 500GB              | 1         | 2      | 3.23%   |
| Crucial CT240M500SSD1 240GB               | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 23.33%  |
| WDC                 | 4         | 6      | 13.33%  |
| Hitachi             | 4         | 4      | 13.33%  |
| Toshiba             | 2         | 2      | 6.67%   |
| Samsung Electronics | 2         | 2      | 6.67%   |
| Kingston            | 2         | 2      | 6.67%   |
| Crucial             | 2         | 3      | 6.67%   |
| SK hynix            | 1         | 1      | 3.33%   |
| SanDisk             | 1         | 1      | 3.33%   |
| LITEON              | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| HGST HTS            | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |
| DGM                 | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 7         | 7      | 38.89%  |
| Hitachi  | 4         | 4      | 22.22%  |
| WDC      | 3         | 5      | 16.67%  |
| Toshiba  | 2         | 2      | 11.11%  |
| HGST HTS | 1         | 1      | 5.56%   |
| HGST     | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 20     | 58.62%  |
| SSD  | 10        | 11     | 34.48%  |
| NVMe | 2         | 2      | 6.9%    |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 177       | 356    | 47.45%  |
| Works    | 167       | 327    | 44.77%  |
| Malfunc  | 29        | 33     | 7.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 225       | 47.57%  |
| Samsung Electronics            | 57        | 12.05%  |
| AMD                            | 48        | 10.15%  |
| SanDisk                        | 41        | 8.67%   |
| SK hynix                       | 12        | 2.54%   |
| Silicon Motion                 | 12        | 2.54%   |
| ASMedia Technology             | 11        | 2.33%   |
| Phison Electronics             | 9         | 1.9%    |
| Micron Technology              | 7         | 1.48%   |
| Kingston Technology Company    | 7         | 1.48%   |
| Toshiba America Info Systems   | 5         | 1.06%   |
| Marvell Technology Group       | 5         | 1.06%   |
| ADATA Technology               | 5         | 1.06%   |
| Yangtze Memory Technologies    | 3         | 0.63%   |
| KIOXIA                         | 3         | 0.63%   |
| Biwin Storage Technology       | 3         | 0.63%   |
| VIA Technologies               | 2         | 0.42%   |
| Nvidia                         | 2         | 0.42%   |
| Micron/Crucial Technology      | 2         | 0.42%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.42%   |
| Lite-On Technology             | 2         | 0.42%   |
| JMicron Technology             | 2         | 0.42%   |
| Apple                          | 2         | 0.42%   |
| Solid State Storage Technology | 1         | 0.21%   |
| LSI Logic / Symbios Logic      | 1         | 0.21%   |
| Lenovo                         | 1         | 0.21%   |
| Integrated Technology Express  | 1         | 0.21%   |
| Huawei Technologies            | 1         | 0.21%   |
| Broadcom / LSI                 | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 6.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 29        | 5.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 20        | 3.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 3.25%   |
| Intel Volume Management Device NVMe RAID Controller                            | 14        | 2.68%   |
| AMD 400 Series Chipset SATA Controller                                         | 13        | 2.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 12        | 2.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 2.1%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 10        | 1.91%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 10        | 1.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 1.72%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 9         | 1.72%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 8         | 1.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 1.53%   |
| Samsung NVMe SSD Controller 980                                                | 8         | 1.53%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 7         | 1.34%   |
| SanDisk NVMe Controller                                                        | 7         | 1.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7         | 1.34%   |
| Micron NVMe Storage Controller                                                 | 7         | 1.34%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 1.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7         | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 1.34%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.34%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 6         | 1.15%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 1.15%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 0.96%   |
| Intel SSD 660P Series                                                          | 5         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5         | 0.96%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 5         | 0.96%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 0.76%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 0.76%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 4         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 237       | 51.63%  |
| NVMe | 161       | 35.08%  |
| IDE  | 31        | 6.75%   |
| RAID | 27        | 5.88%   |
| SAS  | 3         | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 260       | 75.8%   |
| AMD          | 72        | 20.99%  |
| ARM          | 5         | 1.46%   |
| Unknown      | 3         | 0.87%   |
| Phytium      | 1         | 0.29%   |
| HISILICON    | 1         | 0.29%   |
| GenuineTMx86 | 1         | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 2.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.74%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.45%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.45%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 1.16%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 4         | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.16%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.16%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 1.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.16%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.16%   |
| ARM Processor                                 | 4         | 1.16%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 4         | 1.16%   |
| AMD Ryzen 7 6800U with Radeon Graphics        | 4         | 1.16%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 1.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.87%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 3         | 0.87%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.87%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 3         | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.87%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 3         | 0.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.87%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 3         | 0.87%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 0.87%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 3         | 0.87%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 3         | 0.87%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 0.87%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.87%   |
|                                               | 3         | 0.87%   |
| Intel Xeon CPU X5675 @ 3.07GHz                | 2         | 0.58%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 0.58%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 2         | 0.58%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.58%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 0.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.58%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.58%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 2         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 68        | 19.77%  |
| Intel Core i5           | 67        | 19.48%  |
| Other                   | 44        | 12.79%  |
| AMD Ryzen 7             | 26        | 7.56%   |
| Intel Core i3           | 24        | 6.98%   |
| Intel Celeron           | 21        | 6.1%    |
| AMD Ryzen 5             | 21        | 6.1%    |
| Intel Xeon              | 13        | 3.78%   |
| AMD Ryzen 9             | 10        | 2.91%   |
| Intel Pentium           | 6         | 1.74%   |
| Intel Core 2 Duo        | 5         | 1.45%   |
| Intel Atom              | 5         | 1.45%   |
| Intel Core m3           | 3         | 0.87%   |
| AMD Phenom II X4        | 3         | 0.87%   |
| Intel Pentium Gold      | 2         | 0.58%   |
| Intel Pentium Dual-Core | 2         | 0.58%   |
| Intel Pentium Dual      | 2         | 0.58%   |
| Intel Core i9           | 2         | 0.58%   |
| AMD Ryzen 7 PRO         | 2         | 0.58%   |
| Intel Xeon Silver       | 1         | 0.29%   |
| Intel Pentium Silver    | 1         | 0.29%   |
| Intel Pentium M         | 1         | 0.29%   |
| Intel Genuine           | 1         | 0.29%   |
| Intel Core 2 Quad       | 1         | 0.29%   |
| Intel Core 2 Extreme    | 1         | 0.29%   |
| Intel Core 2            | 1         | 0.29%   |
| ARM BCM                 | 1         | 0.29%   |
| AMD Ryzen Threadripper  | 1         | 0.29%   |
| AMD Ryzen Embedded      | 1         | 0.29%   |
| AMD Quad-Core           | 1         | 0.29%   |
| AMD Phenom II X6        | 1         | 0.29%   |
| AMD FX                  | 1         | 0.29%   |
| AMD Athlon II X4        | 1         | 0.29%   |
| AMD Athlon II X3        | 1         | 0.29%   |
| AMD Athlon 64 X2        | 1         | 0.29%   |
| AMD A8                  | 1         | 0.29%   |
| AMD A10                 | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 126       | 36.63%  |
| 2       | 94        | 27.33%  |
| 8       | 47        | 13.66%  |
| 6       | 36        | 10.47%  |
| 12      | 12        | 3.49%   |
| 1       | 9         | 2.62%   |
| 10      | 5         | 1.45%   |
| 16      | 4         | 1.16%   |
| 14      | 4         | 1.16%   |
| 24      | 2         | 0.58%   |
| 3       | 2         | 0.58%   |
| Unknown | 2         | 0.58%   |
| 64      | 1         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 335       | 97.67%  |
| 2       | 6         | 1.75%   |
| Unknown | 2         | 0.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 246       | 71.3%   |
| 1       | 97        | 28.12%  |
| Unknown | 2         | 0.58%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 322       | 93.88%  |
| 32-bit         | 9         | 2.62%   |
| Unknown        | 9         | 2.62%   |
| 64-bit         | 3         | 0.87%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 22%     |
| 0x306c3    | 17        | 4.86%   |
| 0x206a7    | 17        | 4.86%   |
| 0x906ea    | 14        | 4%      |
| 0x806e9    | 13        | 3.71%   |
| 0x306a9    | 13        | 3.71%   |
| 0x806ea    | 11        | 3.14%   |
| 0x806c1    | 9         | 2.57%   |
| 0x506e3    | 8         | 2.29%   |
| 0x40651    | 8         | 2.29%   |
| 0x0a50000c | 8         | 2.29%   |
| 0x90672    | 7         | 2%      |
| 0x806eb    | 7         | 2%      |
| 0x406e3    | 6         | 1.71%   |
| 0x906ed    | 5         | 1.43%   |
| 0x906e9    | 5         | 1.43%   |
| 0x706e5    | 5         | 1.43%   |
| 0x506c9    | 5         | 1.43%   |
| 0x08600106 | 5         | 1.43%   |
| 0x806ec    | 4         | 1.14%   |
| 0x306e4    | 4         | 1.14%   |
| 0x20655    | 4         | 1.14%   |
| 0x106c2    | 4         | 1.14%   |
| 0x1067a    | 4         | 1.14%   |
| 0x08701013 | 4         | 1.14%   |
| 0x0800820d | 4         | 1.14%   |
| 0xa0653    | 3         | 0.86%   |
| 0xa0652    | 3         | 0.86%   |
| 0x906a3    | 3         | 0.86%   |
| 0x6fd      | 3         | 0.86%   |
| 0x20652    | 3         | 0.86%   |
| 0x0a201009 | 3         | 0.86%   |
| 0x08600104 | 3         | 0.86%   |
| 0x08108102 | 3         | 0.86%   |
| 0xa0671    | 2         | 0.57%   |
| 0x90675    | 2         | 0.57%   |
| 0x806d1    | 2         | 0.57%   |
| 0x706a8    | 2         | 0.57%   |
| 0x706a1    | 2         | 0.57%   |
| 0x66a      | 2         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 65        | 18.84%  |
| Haswell          | 32        | 9.28%   |
| Unknown          | 30        | 8.7%    |
| Zen 2            | 22        | 6.38%   |
| SandyBridge      | 21        | 6.09%   |
| IvyBridge        | 21        | 6.09%   |
| Zen 3            | 19        | 5.51%   |
| Skylake          | 19        | 5.51%   |
| TigerLake        | 13        | 3.77%   |
| IceLake          | 11        | 3.19%   |
| CometLake        | 11        | 3.19%   |
| Zen+             | 10        | 2.9%    |
| Westmere         | 10        | 2.9%    |
| Alderlake Hybrid | 10        | 2.9%    |
| Penryn           | 6         | 1.74%   |
| K10              | 6         | 1.74%   |
| Goldmont         | 6         | 1.74%   |
| Core             | 6         | 1.74%   |
| Silvermont       | 4         | 1.16%   |
| Goldmont plus    | 4         | 1.16%   |
| Broadwell        | 4         | 1.16%   |
| Bonnell          | 4         | 1.16%   |
| Zen              | 2         | 0.58%   |
| Steamroller      | 2         | 0.58%   |
| P6               | 2         | 0.58%   |
| Tremont          | 1         | 0.29%   |
| Piledriver       | 1         | 0.29%   |
| Nehalem          | 1         | 0.29%   |
| K8 Hammer        | 1         | 0.29%   |
| Jaguar           | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 202       | 49.27%  |
| Nvidia                     | 123       | 30%     |
| AMD                        | 78        | 19.02%  |
| Neomagic                   | 2         | 0.49%   |
| Matrox Electronics Systems | 2         | 0.49%   |
| ASPEED Technology          | 2         | 0.49%   |
| S3 Graphics                | 1         | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 16        | 3.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 13        | 3.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11        | 2.63%   |
| Intel UHD Graphics 620                                                      | 11        | 2.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 11        | 2.63%   |
| AMD Renoir                                                                  | 11        | 2.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 10        | 2.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 9         | 2.15%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 9         | 2.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 8         | 1.91%   |
| Intel HD Graphics 620                                                       | 7         | 1.67%   |
| AMD Rembrandt [Radeon 680M]                                                 | 7         | 1.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 6         | 1.43%   |
| Intel HD Graphics 530                                                       | 6         | 1.43%   |
| Intel HD Graphics 500                                                       | 6         | 1.43%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6         | 1.43%   |
| Nvidia GP108M [GeForce MX150]                                               | 5         | 1.19%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 5         | 1.19%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 5         | 1.19%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5         | 1.19%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 5         | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5         | 1.19%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 4         | 0.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4         | 0.95%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4         | 0.95%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4         | 0.95%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 4         | 0.95%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 4         | 0.95%   |
| Intel HD Graphics 615                                                       | 4         | 0.95%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4         | 0.95%   |
| Intel Core Processor Integrated Graphics Controller                         | 4         | 0.95%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4         | 0.95%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4         | 0.95%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 0.72%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3         | 0.72%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 0.72%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 3         | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 3         | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 3         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 146       | 42.44%  |
| 1 x Nvidia      | 62        | 18.02%  |
| 1 x AMD         | 54        | 15.7%   |
| Intel + Nvidia  | 44        | 12.79%  |
| AMD + Nvidia    | 15        | 4.36%   |
| Other           | 8         | 2.33%   |
| Intel + AMD     | 6         | 1.74%   |
| 2 x AMD         | 2         | 0.58%   |
| 1 x Neomagic    | 2         | 0.58%   |
| 1 x ASPEED      | 2         | 0.58%   |
| 1 x S3 Graphics | 1         | 0.29%   |
| Nvidia + Matrox | 1         | 0.29%   |
| 1 x Matrox      | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 256       | 74.2%   |
| Proprietary | 68        | 19.71%  |
| Unknown     | 21        | 6.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 207       | 59.31%  |
| 1.01-2.0   | 31        | 8.88%   |
| 0.01-0.5   | 27        | 7.74%   |
| 0.51-1.0   | 24        | 6.88%   |
| 7.01-8.0   | 23        | 6.59%   |
| 3.01-4.0   | 20        | 5.73%   |
| 5.01-6.0   | 12        | 3.44%   |
| 2.01-3.0   | 2         | 0.57%   |
| 8.01-16.0  | 2         | 0.57%   |
| 16.01-24.0 | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 37        | 10.25%  |
| AU Optronics            | 35        | 9.7%    |
| Samsung Electronics     | 28        | 7.76%   |
| LG Display              | 24        | 6.65%   |
| Chimei Innolux          | 24        | 6.65%   |
| Dell                    | 22        | 6.09%   |
| AOC                     | 20        | 5.54%   |
| Goldstar                | 18        | 4.99%   |
| Philips                 | 14        | 3.88%   |
| Sharp                   | 11        | 3.05%   |
| Ancor Communications    | 9         | 2.49%   |
| Unknown                 | 7         | 1.94%   |
| BenQ                    | 7         | 1.94%   |
| Acer                    | 7         | 1.94%   |
| Lenovo                  | 6         | 1.66%   |
| Apple                   | 6         | 1.66%   |
| AMO                     | 6         | 1.66%   |
| ViewSonic               | 5         | 1.39%   |
| RTK                     | 5         | 1.39%   |
| ASUSTek Computer        | 5         | 1.39%   |
| Hewlett-Packard         | 4         | 1.11%   |
| PANDA                   | 3         | 0.83%   |
| IPS                     | 3         | 0.83%   |
| CSO                     | 3         | 0.83%   |
| TMX                     | 2         | 0.55%   |
| SKY                     | 2         | 0.55%   |
| Mi                      | 2         | 0.55%   |
| LG Philips              | 2         | 0.55%   |
| InfoVision              | 2         | 0.55%   |
| HSO                     | 2         | 0.55%   |
| CPT                     | 2         | 0.55%   |
| Chi Mei Optoelectronics | 2         | 0.55%   |
| AUS                     | 2         | 0.55%   |
| Xiaomi                  | 1         | 0.28%   |
| Xiangye                 | 1         | 0.28%   |
| Valve                   | 1         | 0.28%   |
| Unknown (DAE)           | 1         | 0.28%   |
| Unknown (AAA)           | 1         | 0.28%   |
| TUO                     | 1         | 0.28%   |
| Toshiba                 | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AMO HS241P AMO2800 3840x2160 620x350mm 28.0-inch                      | 4         | 1.09%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 3         | 0.82%   |
| RTK LCD Monitor RTK2A3B 1200x1920 114x184mm 8.5-inch                  | 3         | 0.82%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 3         | 0.82%   |
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 0.82%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.82%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 3         | 0.82%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 3         | 0.82%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 3         | 0.82%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 0.54%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.54%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch               | 2         | 0.54%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 2         | 0.54%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.54%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch              | 2         | 0.54%   |
| IPS LCD Monitor IPS2700 2560x1440 597x336mm 27.0-inch                 | 2         | 0.54%   |
| HSO B2431M HSO2431 3840x2160 520x290mm 23.4-inch                      | 2         | 0.54%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.54%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.54%   |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                   | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 2         | 0.54%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 0.54%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                 | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO233D 1920x1080 309x174mm 14.0-inch        | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 0.54%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 2         | 0.54%   |
| AOC G2490W1G4 AOC2490 1920x1080 527x296mm 23.8-inch                   | 2         | 0.54%   |
| Xiaomi Mi TV XMD004A 1360x768 708x398mm 32.0-inch                     | 1         | 0.27%   |
| Xiangye XE2400 XYE2380 3840x2160 520x310mm 23.8-inch                  | 1         | 0.27%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 477x268mm 21.5-inch              | 1         | 0.27%   |
| ViewSonic VX2239 SERIES VSC5225 1920x1080 480x270mm 21.7-inch         | 1         | 0.27%   |
| ViewSonic VG921m VSC301E 1280x1024 380x300mm 19.1-inch                | 1         | 0.27%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 1         | 0.27%   |
| ViewSonic VA1616wSERIES VSC0021 1366x768 348x197mm 15.7-inch          | 1         | 0.27%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 156       | 46.02%  |
| 3840x2160 (4K)     | 43        | 12.68%  |
| 1366x768 (WXGA)    | 29        | 8.55%   |
| 2560x1440 (QHD)    | 23        | 6.78%   |
| 1440x900 (WXGA+)   | 11        | 3.24%   |
| 2560x1600          | 8         | 2.36%   |
| 1600x900 (HD+)     | 8         | 2.36%   |
| Unknown            | 7         | 2.06%   |
| 1680x1050 (WSXGA+) | 5         | 1.47%   |
| 1280x800 (WXGA)    | 5         | 1.47%   |
| 3440x1440          | 4         | 1.18%   |
| 3840x2400          | 3         | 0.88%   |
| 3840x1080          | 3         | 0.88%   |
| 2880x1800          | 3         | 0.88%   |
| 1360x768           | 3         | 0.88%   |
| 1280x1024 (SXGA)   | 3         | 0.88%   |
| 2560x1080          | 2         | 0.59%   |
| 1920x1200 (WUXGA)  | 2         | 0.59%   |
| 1024x768 (XGA)     | 2         | 0.59%   |
| 800x1280           | 1         | 0.29%   |
| 5120x1440          | 1         | 0.29%   |
| 4480x1440          | 1         | 0.29%   |
| 3840x1600          | 1         | 0.29%   |
| 3520x1080          | 1         | 0.29%   |
| 3456x2160          | 1         | 0.29%   |
| 3200x2000          | 1         | 0.29%   |
| 3200x1800 (QHD+)   | 1         | 0.29%   |
| 3200x1080          | 1         | 0.29%   |
| 2880x1920          | 1         | 0.29%   |
| 2400x1600          | 1         | 0.29%   |
| 2304x1440          | 1         | 0.29%   |
| 2256x1504          | 1         | 0.29%   |
| 2240x1400          | 1         | 0.29%   |
| 2160x1440          | 1         | 0.29%   |
| 2160x1350          | 1         | 0.29%   |
| 1600x2560          | 1         | 0.29%   |
| 1024x600           | 1         | 0.29%   |
| 1024x576           | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 61        | 17.23%  |
| 13      | 44        | 12.43%  |
| 14      | 33        | 9.32%   |
| 23      | 29        | 8.19%   |
| 21      | 28        | 7.91%   |
| 24      | 23        | 6.5%    |
| Unknown | 22        | 6.21%   |
| 27      | 21        | 5.93%   |
| 31      | 13        | 3.67%   |
| 12      | 11        | 3.11%   |
| 18      | 9         | 2.54%   |
| 17      | 7         | 1.98%   |
| 19      | 6         | 1.69%   |
| 40      | 5         | 1.41%   |
| 34      | 5         | 1.41%   |
| 28      | 5         | 1.41%   |
| 16      | 5         | 1.41%   |
| 57      | 3         | 0.85%   |
| 22      | 3         | 0.85%   |
| 10      | 3         | 0.85%   |
| 84      | 2         | 0.56%   |
| 26      | 2         | 0.56%   |
| 25      | 2         | 0.56%   |
| 8       | 2         | 0.56%   |
| 72      | 1         | 0.28%   |
| 65      | 1         | 0.28%   |
| 58      | 1         | 0.28%   |
| 52      | 1         | 0.28%   |
| 48      | 1         | 0.28%   |
| 37      | 1         | 0.28%   |
| 32      | 1         | 0.28%   |
| 20      | 1         | 0.28%   |
| 11      | 1         | 0.28%   |
| 7       | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 115       | 33.14%  |
| 501-600     | 71        | 20.46%  |
| 401-500     | 44        | 12.68%  |
| 201-300     | 42        | 12.1%   |
| Unknown     | 22        | 6.34%   |
| 601-700     | 19        | 5.48%   |
| 701-800     | 9         | 2.59%   |
| 351-400     | 9         | 2.59%   |
| 801-900     | 6         | 1.73%   |
| 1001-1500   | 4         | 1.15%   |
| 1501-2000   | 3         | 0.86%   |
| 101-200     | 2         | 0.58%   |
| 1-100       | 1         | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 241       | 74.61%  |
| 16/10   | 43        | 13.31%  |
| Unknown | 18        | 5.57%   |
| 21/9    | 6         | 1.86%   |
| 3/2     | 4         | 1.24%   |
| 0.56    | 3         | 0.93%   |
| 6/5     | 2         | 0.62%   |
| 0.62    | 2         | 0.62%   |
| 5/4     | 1         | 0.31%   |
| 4/3     | 1         | 0.31%   |
| 32/9    | 1         | 0.31%   |
| 0.67    | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 69        | 19.71%  |
| 101-110        | 62        | 17.71%  |
| 81-90          | 56        | 16%     |
| 301-350        | 28        | 8%      |
| 71-80          | 22        | 6.29%   |
| Unknown        | 22        | 6.29%   |
| 351-500        | 20        | 5.71%   |
| 151-200        | 16        | 4.57%   |
| 61-70          | 10        | 2.86%   |
| More than 1000 | 9         | 2.57%   |
| 251-300        | 7         | 2%      |
| 121-130        | 6         | 1.71%   |
| 501-1000       | 6         | 1.71%   |
| 141-150        | 5         | 1.43%   |
| 41-50          | 3         | 0.86%   |
| 1-40           | 3         | 0.86%   |
| 111-120        | 3         | 0.86%   |
| 51-60          | 1         | 0.29%   |
| 131-140        | 1         | 0.29%   |
| 91-100         | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 94        | 27.41%  |
| 51-100        | 92        | 26.82%  |
| 101-120       | 67        | 19.53%  |
| 161-240       | 40        | 11.66%  |
| Unknown       | 22        | 6.41%   |
| More than 240 | 19        | 5.54%   |
| 1-50          | 9         | 2.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 277       | 79.83%  |
| 2     | 50        | 14.41%  |
| 0     | 18        | 5.19%   |
| 3     | 2         | 0.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 199       | 40.04%  |
| Realtek Semiconductor                  | 163       | 32.8%   |
| Qualcomm Atheros                       | 37        | 7.44%   |
| Broadcom                               | 23        | 4.63%   |
| MediaTek                               | 15        | 3.02%   |
| TP-Link                                | 9         | 1.81%   |
| Ralink Technology                      | 8         | 1.61%   |
| ASIX Electronics                       | 7         | 1.41%   |
| Broadcom Limited                       | 4         | 0.8%    |
| Qualcomm                               | 3         | 0.6%    |
| Microsoft                              | 3         | 0.6%    |
| Marvell Technology Group               | 3         | 0.6%    |
| Xiaomi                                 | 2         | 0.4%    |
| SEGGER                                 | 2         | 0.4%    |
| Huawei Technologies                    | 2         | 0.4%    |
| Texas Instruments                      | 1         | 0.2%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.2%    |
| Samsung Electronics                    | 1         | 0.2%    |
| Ralink                                 | 1         | 0.2%    |
| PEAK-System Technik                    | 1         | 0.2%    |
| OPPO Electronics                       | 1         | 0.2%    |
| Nvidia                                 | 1         | 0.2%    |
| NetGear                                | 1         | 0.2%    |
| National Semiconductor                 | 1         | 0.2%    |
| Lenovo                                 | 1         | 0.2%    |
| ICS Advent                             | 1         | 0.2%    |
| Fitbit                                 | 1         | 0.2%    |
| DisplayLink                            | 1         | 0.2%    |
| D-Link                                 | 1         | 0.2%    |
| Belkin Components                      | 1         | 0.2%    |
| Aquantia                               | 1         | 0.2%    |
| Apple                                  | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 108       | 18.09%  |
| Intel Wi-Fi 6 AX200                                               | 30        | 5.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 2.18%   |
| Intel Wireless 8265 / 8275                                        | 13        | 2.18%   |
| Intel I211 Gigabit Network Connection                             | 13        | 2.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 2.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10        | 1.68%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 1.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 9         | 1.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 1.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.34%   |
| Intel Wireless 7265                                               | 8         | 1.34%   |
| Intel Wireless 7260                                               | 8         | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.34%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 1.17%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 1.01%   |
| Intel Wireless 8260                                               | 6         | 1.01%   |
| Intel Ethernet Controller I225-V                                  | 6         | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.01%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 6         | 1.01%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 1.01%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 5         | 0.84%   |
| Ralink MT7601U Wireless Adapter                                   | 5         | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 0.84%   |
| Intel I350 Gigabit Network Connection                             | 5         | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.67%   |
| Intel Ethernet Connection (11) I219-V                             | 4         | 0.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 0.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.5%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 3         | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 158       | 55.83%  |
| Realtek Semiconductor | 34        | 12.01%  |
| Qualcomm Atheros      | 29        | 10.25%  |
| Broadcom              | 18        | 6.36%   |
| MediaTek              | 15        | 5.3%    |
| TP-Link               | 9         | 3.18%   |
| Ralink Technology     | 8         | 2.83%   |
| Qualcomm              | 3         | 1.06%   |
| Microsoft             | 3         | 1.06%   |
| Broadcom Limited      | 2         | 0.71%   |
| Texas Instruments     | 1         | 0.35%   |
| Ralink                | 1         | 0.35%   |
| NetGear               | 1         | 0.35%   |
| Belkin Components     | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 30        | 10.56%  |
| Intel Wireless 8265 / 8275                                              | 13        | 4.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 10        | 3.52%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 3.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.82%   |
| Intel Wireless 7265                                                     | 8         | 2.82%   |
| Intel Wireless 7260                                                     | 8         | 2.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 2.82%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 2.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 2.11%   |
| Intel Wireless 8260                                                     | 6         | 2.11%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 6         | 2.11%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 1.76%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 1.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 1.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.06%   |
| Microsoft XBOX ACC                                                      | 3         | 1.06%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 1.06%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.06%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.06%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3         | 1.06%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.7%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.7%    |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 2         | 0.7%    |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)               | 2         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 150       | 50.17%  |
| Intel                                  | 104       | 34.78%  |
| Qualcomm Atheros                       | 11        | 3.68%   |
| Broadcom                               | 7         | 2.34%   |
| ASIX Electronics                       | 7         | 2.34%   |
| Marvell Technology Group               | 3         | 1%      |
| Xiaomi                                 | 2         | 0.67%   |
| Huawei Technologies                    | 2         | 0.67%   |
| Broadcom Limited                       | 2         | 0.67%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.33%   |
| Samsung Electronics                    | 1         | 0.33%   |
| OPPO Electronics                       | 1         | 0.33%   |
| Nvidia                                 | 1         | 0.33%   |
| National Semiconductor                 | 1         | 0.33%   |
| Lenovo                                 | 1         | 0.33%   |
| ICS Advent                             | 1         | 0.33%   |
| DisplayLink                            | 1         | 0.33%   |
| D-Link                                 | 1         | 0.33%   |
| Aquantia                               | 1         | 0.33%   |
| Apple                                  | 1         | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 108       | 35.18%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 4.23%   |
| Intel I211 Gigabit Network Connection                             | 13        | 4.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.93%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 2.28%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 2.28%   |
| Intel Ethernet Controller I225-V                                  | 6         | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.95%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 1.95%   |
| Intel I350 Gigabit Network Connection                             | 5         | 1.63%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 1.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.3%    |
| Intel Ethernet Connection (11) I219-V                             | 4         | 1.3%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 3         | 0.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.98%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.98%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.98%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.65%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.65%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.65%   |
| Sony Ericsson Mobile AB XQ-CC72                                   | 1         | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.33%   |
| Realtek USB 10/100 LAN                                            | 1         | 0.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.33%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 276       | 50.18%  |
| WiFi     | 268       | 48.73%  |
| Modem    | 3         | 0.55%   |
| Unknown  | 3         | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 201       | 55.37%  |
| Ethernet | 162       | 44.63%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 175       | 50.58%  |
| 1     | 144       | 41.62%  |
| 0     | 15        | 4.34%   |
| 3     | 6         | 1.73%   |
| 4     | 4         | 1.16%   |
| 8     | 1         | 0.29%   |
| 7     | 1         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 339       | 98.26%  |
| Yes  | 6         | 1.74%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 136       | 59.39%  |
| Cambridge Silicon Radio         | 16        | 6.99%   |
| Broadcom                        | 10        | 4.37%   |
| Realtek Semiconductor           | 9         | 3.93%   |
| Qualcomm Atheros Communications | 9         | 3.93%   |
| Foxconn / Hon Hai               | 9         | 3.93%   |
| IMC Networks                    | 7         | 3.06%   |
| Apple                           | 6         | 2.62%   |
| Lite-On Technology              | 5         | 2.18%   |
| MediaTek                        | 4         | 1.75%   |
| Realtek                         | 3         | 1.31%   |
| Hewlett-Packard                 | 3         | 1.31%   |
| Foxconn International           | 3         | 1.31%   |
| Dell                            | 2         | 0.87%   |
| ASUSTek Computer                | 2         | 0.87%   |
| Taiyo Yuden                     | 1         | 0.44%   |
| SINO WEALTH                     | 1         | 0.44%   |
| Micro Star International        | 1         | 0.44%   |
| Fujitsu                         | 1         | 0.44%   |
| Askey Computer                  | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 35        | 15.28%  |
| Intel AX200 Bluetooth                               | 30        | 13.1%   |
| Intel AX201 Bluetooth                               | 28        | 12.23%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 7.42%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16        | 6.99%   |
| Realtek Bluetooth Radio                             | 9         | 3.93%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 3.93%   |
| Intel Bluetooth Device                              | 6         | 2.62%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.18%   |
| Intel AX210 Bluetooth                               | 5         | 2.18%   |
| MediaTek Wireless_Device                            | 4         | 1.75%   |
| IMC Networks Wireless_Device                        | 4         | 1.75%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 1.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 1.75%   |
| Realtek Bluetooth Radio                             | 3         | 1.31%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.31%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.31%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.31%   |
| Apple Bluetooth Host Controller                     | 3         | 1.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.87%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.87%   |
| IMC Networks Bluetooth Device                       | 2         | 0.87%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.87%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.87%   |
| ASUS Bluetooth Radio                                | 2         | 0.87%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.87%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.44%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1         | 0.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.44%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.44%   |
| Micro Star International Bluetooth Dongle           | 1         | 0.44%   |
| Lite-On Bluetooth Radio                             | 1         | 0.44%   |
| Lite-On Bluetooth Device                            | 1         | 0.44%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.44%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.44%   |
| Fujitsu Bluetooth Device                            | 1         | 0.44%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.44%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 251       | 54.09%  |
| Nvidia                               | 91        | 19.61%  |
| AMD                                  | 84        | 18.1%   |
| C-Media Electronics                  | 9         | 1.94%   |
| Logitech                             | 3         | 0.65%   |
| FiiO Electronics Technology          | 3         | 0.65%   |
| Generalplus Technology               | 2         | 0.43%   |
| Focusrite-Novation                   | 2         | 0.43%   |
| ESS Technology                       | 2         | 0.43%   |
| Creative Labs                        | 2         | 0.43%   |
| AudioQuest                           | 2         | 0.43%   |
| XMOS                                 | 1         | 0.22%   |
| Winbond Electronics                  | 1         | 0.22%   |
| VIA Technologies                     | 1         | 0.22%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.22%   |
| Texas Instruments                    | 1         | 0.22%   |
| Sony                                 | 1         | 0.22%   |
| SAVITECH                             | 1         | 0.22%   |
| Realtek Semiconductor                | 1         | 0.22%   |
| Micro Star International             | 1         | 0.22%   |
| Lynx                                 | 1         | 0.22%   |
| iCreate Technologies                 | 1         | 0.22%   |
| BY EDIFIER                           | 1         | 0.22%   |
| Apple                                | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 39        | 7.14%   |
| Intel Sunrise Point-LP HD Audio                                            | 31        | 5.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20        | 3.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20        | 3.66%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 19        | 3.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18        | 3.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 3.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 2.75%   |
| AMD Starship/Matisse HD Audio Controller                                   | 15        | 2.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 13        | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 2.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 1.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 9         | 1.65%   |
| Intel Alder Lake-S HD Audio Controller                                     | 9         | 1.65%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 9         | 1.65%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 1.47%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 1.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.47%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 1.28%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 1.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 1.28%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 1.28%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.28%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 1.28%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.1%    |
| Nvidia GM206 High Definition Audio Controller                              | 6         | 1.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 6         | 1.1%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 1.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.1%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6         | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 0.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 0.92%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5         | 0.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.73%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 52        | 21.94%  |
| SK hynix            | 45        | 18.99%  |
| Kingston            | 32        | 13.5%   |
| Micron Technology   | 24        | 10.13%  |
| Unknown             | 17        | 7.17%   |
| Corsair             | 13        | 5.49%   |
| A-DATA Technology   | 10        | 4.22%   |
| Crucial             | 9         | 3.8%    |
| Unknown             | 7         | 2.95%   |
| G.Skill             | 4         | 1.69%   |
| Elpida              | 4         | 1.69%   |
| Team                | 3         | 1.27%   |
| Ramaxel Technology  | 3         | 1.27%   |
| Unknown (ABCD)      | 2         | 0.84%   |
| Nanya Technology    | 2         | 0.84%   |
| Kingmax             | 2         | 0.84%   |
| Unknown (0x0AFD)    | 1         | 0.42%   |
| Transcend           | 1         | 0.42%   |
| tigo                | 1         | 0.42%   |
| Lenovo              | 1         | 0.42%   |
| Juhor               | 1         | 0.42%   |
| GLOWAY              | 1         | 0.42%   |
| Essencore Limited   | 1         | 0.42%   |
| Apacer              | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 7         | 2.78%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 4         | 1.59%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 4         | 1.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 4         | 1.59%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s        | 3         | 1.19%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 2         | 0.79%   |
| Unknown RAM Module 256MB SODIMM DRAM                         | 2         | 0.79%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s | 2         | 0.79%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                 | 2         | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.79%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s         | 2         | 0.79%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 2         | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.79%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.79%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 0.79%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 2         | 0.79%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 2         | 0.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.79%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.79%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.79%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.79%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s               | 2         | 0.79%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s          | 2         | 0.79%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s      | 2         | 0.79%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s        | 2         | 0.79%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 2         | 0.79%   |
| Corsair RAM CM4X16GC3600C18K2D 16GB DIMM DDR4 3600MT/s       | 2         | 0.79%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                     | 2         | 0.79%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.4%    |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                 | 1         | 0.4%    |
| Unknown RAM Module 512MB SODIMM DRAM                         | 1         | 0.4%    |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1         | 0.4%    |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s                  | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 333MT/s                   | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR                            | 1         | 0.4%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 109       | 52.91%  |
| DDR3    | 46        | 22.33%  |
| LPDDR3  | 12        | 5.83%   |
| LPDDR4  | 11        | 5.34%   |
| DDR2    | 9         | 4.37%   |
| SDRAM   | 5         | 2.43%   |
| DDR5    | 5         | 2.43%   |
| Unknown | 4         | 1.94%   |
| DRAM    | 3         | 1.46%   |
| LPDDR5  | 1         | 0.49%   |
| DDR     | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 97        | 47.32%  |
| DIMM         | 81        | 39.51%  |
| Row Of Chips | 26        | 12.68%  |
| Unknown      | 1         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 82        | 36.44%  |
| 4096  | 49        | 21.78%  |
| 16384 | 43        | 19.11%  |
| 2048  | 21        | 9.33%   |
| 32768 | 17        | 7.56%   |
| 1024  | 6         | 2.67%   |
| 256   | 2         | 0.89%   |
| 64    | 2         | 0.89%   |
| 32767 | 1         | 0.44%   |
| 512   | 1         | 0.44%   |
| 232   | 1         | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 39        | 17.81%  |
| 2667    | 37        | 16.89%  |
| 1600    | 35        | 15.98%  |
| 2133    | 15        | 6.85%   |
| 2400    | 13        | 5.94%   |
| 1333    | 9         | 4.11%   |
| 4800    | 6         | 2.74%   |
| 3600    | 6         | 2.74%   |
| Unknown | 6         | 2.74%   |
| 4267    | 5         | 2.28%   |
| 2666    | 5         | 2.28%   |
| 1867    | 5         | 2.28%   |
| 3266    | 4         | 1.83%   |
| 667     | 4         | 1.83%   |
| 3466    | 3         | 1.37%   |
| 3000    | 3         | 1.37%   |
| 1334    | 2         | 0.91%   |
| 800     | 2         | 0.91%   |
| 533     | 2         | 0.91%   |
| 8400    | 1         | 0.46%   |
| 6400    | 1         | 0.46%   |
| 5808    | 1         | 0.46%   |
| 4266    | 1         | 0.46%   |
| 4199    | 1         | 0.46%   |
| 3866    | 1         | 0.46%   |
| 3800    | 1         | 0.46%   |
| 3733    | 1         | 0.46%   |
| 3400    | 1         | 0.46%   |
| 3007    | 1         | 0.46%   |
| 2933    | 1         | 0.46%   |
| 1866    | 1         | 0.46%   |
| 1800    | 1         | 0.46%   |
| 1067    | 1         | 0.46%   |
| 1066    | 1         | 0.46%   |
| 975     | 1         | 0.46%   |
| 333     | 1         | 0.46%   |
| 200     | 1         | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Xiaomi             | 1         | 20%     |
| Hewlett-Packard    | 1         | 20%     |
| Fuji Xerox         | 1         | 20%     |
| Canon              | 1         | 20%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                       | Computers | Percent |
|-----------------------------|-----------|---------|
| Xiaomi MiMouse 2            | 1         | 20%     |
| HP LaserJet P2035           | 1         | 20%     |
| Fuji Xerox DocuPrint P158 b | 1         | 20%     |
| Canon MP160                 | 1         | 20%     |
| Brother HL-L2320D series    | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 37        | 21.02%  |
| IMC Networks                           | 17        | 9.66%   |
| Microdia                               | 14        | 7.95%   |
| Acer                                   | 14        | 7.95%   |
| Logitech                               | 10        | 5.68%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 5.11%   |
| Realtek Semiconductor                  | 8         | 4.55%   |
| Luxvisions Innotech Limited            | 7         | 3.98%   |
| Apple                                  | 7         | 3.98%   |
| Syntek                                 | 6         | 3.41%   |
| Sunplus Innovation Technology          | 5         | 2.84%   |
| Silicon Motion                         | 4         | 2.27%   |
| Quanta                                 | 4         | 2.27%   |
| Suyin                                  | 3         | 1.7%    |
| Alcor Micro                            | 3         | 1.7%    |
| Lite-On Technology                     | 2         | 1.14%   |
| Importek                               | 2         | 1.14%   |
| eMPIA Technology                       | 2         | 1.14%   |
| Cubeternet                             | 2         | 1.14%   |
| Z-Star Microelectronics                | 1         | 0.57%   |
| Xiaomi                                 | 1         | 0.57%   |
| WaveRider Communications               | 1         | 0.57%   |
| USB Camera                             | 1         | 0.57%   |
| Tripath Technology                     | 1         | 0.57%   |
| Sonix Technology                       | 1         | 0.57%   |
| SN0002                                 | 1         | 0.57%   |
| Ricoh                                  | 1         | 0.57%   |
| Primax Electronics                     | 1         | 0.57%   |
| Nokia Mobile Phones                    | 1         | 0.57%   |
| Nebraska Furniture Mart                | 1         | 0.57%   |
| Microsoft                              | 1         | 0.57%   |
| lihappe8                               | 1         | 0.57%   |
| Hopewin Electronic Material            | 1         | 0.57%   |
| Google                                 | 1         | 0.57%   |
| Genesys Logic                          | 1         | 0.57%   |
| Essential Products                     | 1         | 0.57%   |
| Bison Electronics                      | 1         | 0.57%   |
| ARC International                      | 1         | 0.57%   |
| A4Tech                                 | 1         | 0.57%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 13        | 7.26%   |
| Microdia Integrated_Webcam_HD                                              | 9         | 5.03%   |
| IMC Networks Integrated Camera                                             | 8         | 4.47%   |
| Acer Integrated Camera                                                     | 6         | 3.35%   |
| Syntek Integrated Camera                                                   | 5         | 2.79%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 2.79%   |
| Chicony FJ Camera                                                          | 5         | 2.79%   |
| Logitech Webcam C270                                                       | 4         | 2.23%   |
| Chicony HD WebCam                                                          | 4         | 2.23%   |
| Apple FaceTime HD Camera (Built-in)                                        | 4         | 2.23%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 1.68%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 3         | 1.68%   |
| Alcor Micro USB 2.0 Camera                                                 | 3         | 1.68%   |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 1.12%   |
| Logitech B525 HD Webcam                                                    | 2         | 1.12%   |
| Lite-On Integrated Camera                                                  | 2         | 1.12%   |
| Importek FJ Camera                                                         | 2         | 1.12%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 1.12%   |
| Chicony Integrated IR Camera                                               | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 2         | 1.12%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 2         | 1.12%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 1.12%   |
| Acer Lenovo EasyCamera                                                     | 2         | 1.12%   |
| Z-Star Sirius USB2.0 Camera                                                | 1         | 0.56%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                                         | 1         | 0.56%   |
| WaveRider USB 2.0 Camera                                                   | 1         | 0.56%   |
| USB Camera USB Camera                                                      | 1         | 0.56%   |
| Tripath USB Camera                                                         | 1         | 0.56%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.56%   |
| Suyin Integrated Webcam                                                    | 1         | 0.56%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 0.56%   |
| Suyin HP Truevision HD                                                     | 1         | 0.56%   |
| Sunplus USB Camera                                                         | 1         | 0.56%   |
| Sunplus SPCA2085 PC Camera                                                 | 1         | 0.56%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 0.56%   |
| Sunplus HP Universal Camera                                                | 1         | 0.56%   |
| Sunplus HD WebCam                                                          | 1         | 0.56%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 0.56%   |
| SN0002 2K USB Camera                                                       | 1         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 18        | 43.9%   |
| Validity Sensors           | 8         | 19.51%  |
| Shenzhen Goodix Technology | 7         | 17.07%  |
| AuthenTec                  | 3         | 7.32%   |
| Upek                       | 2         | 4.88%   |
| LighTuning Technology      | 2         | 4.88%   |
| Samsung Electronics        | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader       | 7         | 17.07%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 12.2%   |
| Validity Sensors Synaptics WBDI                        | 3         | 7.32%   |
| Shenzhen Goodix FingerPrint                            | 3         | 7.32%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 4.88%   |
| Synaptics WBDI                                         | 2         | 4.88%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 4.88%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 4.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 4.88%   |
| AuthenTec Fingerprint Sensor                           | 2         | 4.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.44%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 2.44%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 2.44%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 2.44%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.44%   |
| Synaptics UWP WBDI                                     | 1         | 2.44%   |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1         | 2.44%   |
| Synaptics  WBDI                                        | 1         | 2.44%   |
| Samsung Fingerprint Device                             | 1         | 2.44%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 2.44%   |
| Unknown                                                | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 27.78%  |
| Upek                  | 4         | 22.22%  |
| Advanced Card Systems | 3         | 16.67%  |
| Lenovo                | 2         | 11.11%  |
| Alcor Micro           | 2         | 11.11%  |
| Yubico.com            | 1         | 5.56%   |
| O2 Micro              | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 22.22%  |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 3         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 11.11%  |
| Broadcom 5880                                                                | 2         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 11.11%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5.56%   |
| Broadcom 58200                                                               | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 231       | 65.25%  |
| 1     | 94        | 26.55%  |
| 2     | 19        | 5.37%   |
| 3     | 5         | 1.41%   |
| 4     | 4         | 1.13%   |
| 5     | 1         | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 39        | 23.78%  |
| Fingerprint reader       | 38        | 23.17%  |
| Net/wireless             | 23        | 14.02%  |
| Chipcard                 | 16        | 9.76%   |
| Communication controller | 14        | 8.54%   |
| Multimedia controller    | 13        | 7.93%   |
| Bluetooth                | 4         | 2.44%   |
| Unassigned class         | 3         | 1.83%   |
| Sound                    | 3         | 1.83%   |
| Camera                   | 3         | 1.83%   |
| Storage                  | 2         | 1.22%   |
| Net/ethernet             | 2         | 1.22%   |
| Storage/raid             | 1         | 0.61%   |
| Storage/ata              | 1         | 0.61%   |
| Network                  | 1         | 0.61%   |
| Card reader              | 1         | 0.61%   |

