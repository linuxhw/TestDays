Linux in Hong Kong - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Hong Kong.

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

Total: 317

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [526a6826ab](https://linux-hardware.org/?probe=526a6826ab) | Sep 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [062f19958d](https://linux-hardware.org/?probe=062f19958d) | Sep 01, 2023 |
| HUAWEI        | MACHD-WXX9                  | [2e74e88e2f](https://linux-hardware.org/?probe=2e74e88e2f) | Aug 31, 2023 |
| Dell          | XPS 13 9300                 | [ca90d2134f](https://linux-hardware.org/?probe=ca90d2134f) | Aug 26, 2023 |
| Lenovo        | ThinkPad P51 20HJS5WH0D     | [ae8a51b2f5](https://linux-hardware.org/?probe=ae8a51b2f5) | Aug 21, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | [4c589a0320](https://linux-hardware.org/?probe=4c589a0320) | Aug 18, 2023 |
| Lenovo        | V130-15IKB 81HN             | [88a9c5764d](https://linux-hardware.org/?probe=88a9c5764d) | Aug 11, 2023 |
| Unknown       | Unknown                     | [c90f282238](https://linux-hardware.org/?probe=c90f282238) | Aug 11, 2023 |
| Fujitsu       | UH-X                        | [e26b430aef](https://linux-hardware.org/?probe=e26b430aef) | Aug 09, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [a089f6ff62](https://linux-hardware.org/?probe=a089f6ff62) | Aug 05, 2023 |
| LG Electro... | 16Z90R-K.ADB9U1             | [d3a9e05559](https://linux-hardware.org/?probe=d3a9e05559) | Aug 02, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [dd11fc89fe](https://linux-hardware.org/?probe=dd11fc89fe) | Aug 02, 2023 |
| Chuwi         | HeroBook Pro                | [eb332b024d](https://linux-hardware.org/?probe=eb332b024d) | Jul 30, 2023 |
| Unknown       | Unknown                     | [e8368bcae8](https://linux-hardware.org/?probe=e8368bcae8) | Jul 28, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [0552cb3e44](https://linux-hardware.org/?probe=0552cb3e44) | Jul 26, 2023 |
| Lenovo        | Legion R9000X 2021 82HN     | [0079a4e7a0](https://linux-hardware.org/?probe=0079a4e7a0) | Jul 25, 2023 |
| HP            | Laptop 15s-du3xxx           | [e14cb2c24e](https://linux-hardware.org/?probe=e14cb2c24e) | Jul 25, 2023 |
| HUAWEI        | MACHC-WAX9                  | [bddace9995](https://linux-hardware.org/?probe=bddace9995) | Jul 25, 2023 |
| ASUSTek       | S551LB                      | [edfa5090fc](https://linux-hardware.org/?probe=edfa5090fc) | Jul 21, 2023 |
| Unknown       | Unknown                     | [9430a42f8b](https://linux-hardware.org/?probe=9430a42f8b) | Jul 13, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [9bee6805c0](https://linux-hardware.org/?probe=9bee6805c0) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b89cab90c0](https://linux-hardware.org/?probe=b89cab90c0) | Jul 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [ee5ef8132f](https://linux-hardware.org/?probe=ee5ef8132f) | Jul 09, 2023 |
| Lenovo        | Legion R9000X ARHA7 82UG    | [5da53d3f61](https://linux-hardware.org/?probe=5da53d3f61) | Jul 09, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [c060069870](https://linux-hardware.org/?probe=c060069870) | Jul 07, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
| Google        | Nami                        | [6ffc403580](https://linux-hardware.org/?probe=6ffc403580) | Jun 29, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [928f167dee](https://linux-hardware.org/?probe=928f167dee) | Jun 22, 2023 |
| HUAWEI        | MACH-WX9                    | [016268562d](https://linux-hardware.org/?probe=016268562d) | Jun 21, 2023 |
| HUAWEI        | MACH-WX9                    | [25bc3b1533](https://linux-hardware.org/?probe=25bc3b1533) | Jun 21, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [6a63f44627](https://linux-hardware.org/?probe=6a63f44627) | Jun 19, 2023 |
| Lenovo        | ThinkPad E480 20KNA047CD    | [918de7de03](https://linux-hardware.org/?probe=918de7de03) | Jun 16, 2023 |
| Unknown       | Unknown                     | [bd74568d10](https://linux-hardware.org/?probe=bd74568d10) | Jun 15, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [a67c1e25b2](https://linux-hardware.org/?probe=a67c1e25b2) | Jun 11, 2023 |
| ASUSTek       | S400CA                      | [25c1d47331](https://linux-hardware.org/?probe=25c1d47331) | Jun 08, 2023 |
| Unknown       | Unknown                     | [b7f109f62e](https://linux-hardware.org/?probe=b7f109f62e) | Jun 08, 2023 |
| GPD           | G1619-04                    | [49b9e4edd3](https://linux-hardware.org/?probe=49b9e4edd3) | May 28, 2023 |
| GPD           | G1619-04                    | [caa6b5459d](https://linux-hardware.org/?probe=caa6b5459d) | May 28, 2023 |
| Chuwi         | HeroBook Pro                | [b25115a01a](https://linux-hardware.org/?probe=b25115a01a) | May 19, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [2bfe226026](https://linux-hardware.org/?probe=2bfe226026) | May 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [c2ccca0208](https://linux-hardware.org/?probe=c2ccca0208) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | [cacfc4dacd](https://linux-hardware.org/?probe=cacfc4dacd) | May 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b9cfd37540](https://linux-hardware.org/?probe=b9cfd37540) | May 05, 2023 |
| Fujitsu       | FMVNU6G1C                   | [969957b527](https://linux-hardware.org/?probe=969957b527) | Apr 29, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [65cce76dc9](https://linux-hardware.org/?probe=65cce76dc9) | Apr 20, 2023 |
| Lenovo        | ThinkPad X201 33233QM       | [f84da542f6](https://linux-hardware.org/?probe=f84da542f6) | Apr 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [9d3c5ea28d](https://linux-hardware.org/?probe=9d3c5ea28d) | Apr 11, 2023 |
| MACHENIKE     | T58-V                       | [9a70cca135](https://linux-hardware.org/?probe=9a70cca135) | Apr 08, 2023 |
| Dell          | XPS 17 9710                 | [b4c155dc99](https://linux-hardware.org/?probe=b4c155dc99) | Apr 07, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [832b434c38](https://linux-hardware.org/?probe=832b434c38) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [7e283bfa25](https://linux-hardware.org/?probe=7e283bfa25) | Mar 28, 2023 |
| METAPHYUNI    | MetamechBook                | [7e4076cb61](https://linux-hardware.org/?probe=7e4076cb61) | Mar 24, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d256faa9fc](https://linux-hardware.org/?probe=d256faa9fc) | Mar 06, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [97925534c2](https://linux-hardware.org/?probe=97925534c2) | Mar 02, 2023 |
| Dell          | XPS 13 9300                 | [fc803f9205](https://linux-hardware.org/?probe=fc803f9205) | Feb 27, 2023 |
| Valve         | Jupiter                     | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| Dell          | XPS 15 9570                 | [81cfc27f9e](https://linux-hardware.org/?probe=81cfc27f9e) | Feb 20, 2023 |
| Valve         | Jupiter                     | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [58bcb8bf04](https://linux-hardware.org/?probe=58bcb8bf04) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | [bf63748499](https://linux-hardware.org/?probe=bf63748499) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | [162b72d7a8](https://linux-hardware.org/?probe=162b72d7a8) | Feb 17, 2023 |
| Apple         | MacBookAir6,2               | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| Lenovo        | Y430P 20435                 | [da3030daae](https://linux-hardware.org/?probe=da3030daae) | Feb 16, 2023 |
| Lenovo        | ThinkPad X230 23066RC       | [6a223f0a71](https://linux-hardware.org/?probe=6a223f0a71) | Feb 15, 2023 |
| ASUSTek       | X705UA                      | [cc59e95283](https://linux-hardware.org/?probe=cc59e95283) | Feb 07, 2023 |
| ASUSTek       | X705UA                      | [25188e7cfa](https://linux-hardware.org/?probe=25188e7cfa) | Feb 07, 2023 |
| Timi          | TM1613                      | [503133b0db](https://linux-hardware.org/?probe=503133b0db) | Feb 07, 2023 |
| Valve         | Jupiter                     | [42a3945648](https://linux-hardware.org/?probe=42a3945648) | Feb 06, 2023 |
| Valve         | Jupiter                     | [5f77ae27c2](https://linux-hardware.org/?probe=5f77ae27c2) | Feb 04, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [53015adc9d](https://linux-hardware.org/?probe=53015adc9d) | Jan 28, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | [6d6a8e4be4](https://linux-hardware.org/?probe=6d6a8e4be4) | Jan 24, 2023 |
| Acer          | Swift SF314-57G             | [ae9de10584](https://linux-hardware.org/?probe=ae9de10584) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [4b9d2e6e26](https://linux-hardware.org/?probe=4b9d2e6e26) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [f5bb76ae13](https://linux-hardware.org/?probe=f5bb76ae13) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7cb08d37fb](https://linux-hardware.org/?probe=7cb08d37fb) | Jan 14, 2023 |
| Dell          | XPS 15 9520                 | [2e13f150e6](https://linux-hardware.org/?probe=2e13f150e6) | Jan 09, 2023 |
| Dell          | XPS 15 9520                 | [ec6743fa1b](https://linux-hardware.org/?probe=ec6743fa1b) | Jan 06, 2023 |
| HP            | Stream Notebook PC 13       | [2154a332b0](https://linux-hardware.org/?probe=2154a332b0) | Dec 29, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | [8a5b919c91](https://linux-hardware.org/?probe=8a5b919c91) | Dec 24, 2022 |
| Apple         | MacBookAir5,2               | [641b77c3da](https://linux-hardware.org/?probe=641b77c3da) | Dec 20, 2022 |
| GPD           | P2 MAX                      | [de5983ec37](https://linux-hardware.org/?probe=de5983ec37) | Dec 17, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | [8d631bb590](https://linux-hardware.org/?probe=8d631bb590) | Dec 17, 2022 |
| Dell          | Inspiron 7590               | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| GPD           | P2 MAX                      | [63c199f475](https://linux-hardware.org/?probe=63c199f475) | Dec 08, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | [706e40ed5a](https://linux-hardware.org/?probe=706e40ed5a) | Dec 04, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | [aff020417f](https://linux-hardware.org/?probe=aff020417f) | Dec 01, 2022 |
| Dell          | Latitude 7390               | [7214cac96d](https://linux-hardware.org/?probe=7214cac96d) | Nov 30, 2022 |
| Dell          | Inspiron N4050              | [7b0cf2fa20](https://linux-hardware.org/?probe=7b0cf2fa20) | Nov 30, 2022 |
| GPD           | G1619-04                    | [ce6d16840e](https://linux-hardware.org/?probe=ce6d16840e) | Nov 07, 2022 |
| Dell          | XPS 15 9570                 | [468f8df590](https://linux-hardware.org/?probe=468f8df590) | Nov 06, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| Lenovo        | ThinkPad T470 20HD002TCD    | [0b0ca5a5f6](https://linux-hardware.org/?probe=0b0ca5a5f6) | Oct 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8ebbbf93e4](https://linux-hardware.org/?probe=8ebbbf93e4) | Oct 17, 2022 |
| AMI           | Cherry Trail CR             | [7d3c652547](https://linux-hardware.org/?probe=7d3c652547) | Oct 11, 2022 |
| HP            | ZHAN 66 Pro A 14 inch G5... | [c5587dbec5](https://linux-hardware.org/?probe=c5587dbec5) | Oct 04, 2022 |
| Fujitsu       | FMVNU6G1C                   | [1351f25388](https://linux-hardware.org/?probe=1351f25388) | Sep 30, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7c8030e423](https://linux-hardware.org/?probe=7c8030e423) | Sep 26, 2022 |
| Dell          | Latitude E5250              | [e4ffe3583d](https://linux-hardware.org/?probe=e4ffe3583d) | Sep 26, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | [89a019875a](https://linux-hardware.org/?probe=89a019875a) | Sep 24, 2022 |
| Chuwi         | HeroBook Pro                | [76be3ff1db](https://linux-hardware.org/?probe=76be3ff1db) | Sep 22, 2022 |
| Dell          | Inspiron MP061              | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| Chuwi         | HeroBook Pro                | [3759658825](https://linux-hardware.org/?probe=3759658825) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f454a8f6a5](https://linux-hardware.org/?probe=f454a8f6a5) | Sep 19, 2022 |
| Apple         | MacBookPro15,2              | [5160feeaf2](https://linux-hardware.org/?probe=5160feeaf2) | Sep 13, 2022 |
| Apple         | MacBookPro15,2              | [876e87c7b6](https://linux-hardware.org/?probe=876e87c7b6) | Sep 13, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [1d95c5b6ef](https://linux-hardware.org/?probe=1d95c5b6ef) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4562797ebc](https://linux-hardware.org/?probe=4562797ebc) | Sep 08, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [32ab96441e](https://linux-hardware.org/?probe=32ab96441e) | Sep 08, 2022 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | [d0ddfb5815](https://linux-hardware.org/?probe=d0ddfb5815) | Sep 07, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | [90aed4d5d1](https://linux-hardware.org/?probe=90aed4d5d1) | Aug 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c32d69a956](https://linux-hardware.org/?probe=c32d69a956) | Aug 18, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| Lenovo        | ThinkPad T490s 20NYS79X0... | [5fe4fba501](https://linux-hardware.org/?probe=5fe4fba501) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Acer          | Swift SF314-512             | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| HP            | ZBook 17 G3                 | [bc4cf926f2](https://linux-hardware.org/?probe=bc4cf926f2) | Aug 06, 2022 |
| KOHJINSHA     | SC series                   | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6A... | [76d752f0ad](https://linux-hardware.org/?probe=76d752f0ad) | Aug 01, 2022 |
| Fujitsu       | LIFEBOOK V1020              | [e33ac2916d](https://linux-hardware.org/?probe=e33ac2916d) | Jul 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d449f1aeb9](https://linux-hardware.org/?probe=d449f1aeb9) | Jul 27, 2022 |
| IBM           | 260921H                     | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | [f3e0ebd16e](https://linux-hardware.org/?probe=f3e0ebd16e) | Jul 15, 2022 |
| IBM           | 260921H                     | [5f9b0998d3](https://linux-hardware.org/?probe=5f9b0998d3) | Jul 11, 2022 |
| IBM           | 260921H                     | [f0430651fd](https://linux-hardware.org/?probe=f0430651fd) | Jul 10, 2022 |
| Lenovo        | Unknown                     | [910a4f6587](https://linux-hardware.org/?probe=910a4f6587) | Jul 09, 2022 |
| Acer          | Swift SF314-42              | [bd4792ebd8](https://linux-hardware.org/?probe=bd4792ebd8) | Jul 02, 2022 |
| Compaq        | Tablet PC TC1000            | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [044be44d33](https://linux-hardware.org/?probe=044be44d33) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [5bd3ad4d01](https://linux-hardware.org/?probe=5bd3ad4d01) | Jun 24, 2022 |
| Dell          | XPS 15 9520                 | [ec6f5cce04](https://linux-hardware.org/?probe=ec6f5cce04) | Jun 20, 2022 |
| Dell          | XPS 15 9520                 | [bdd4ec2ef9](https://linux-hardware.org/?probe=bdd4ec2ef9) | Jun 15, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [f4c7f13ff8](https://linux-hardware.org/?probe=f4c7f13ff8) | Jun 14, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | [e3df184136](https://linux-hardware.org/?probe=e3df184136) | Jun 12, 2022 |
| Dell          | XPS 13 9305                 | [e373d39f20](https://linux-hardware.org/?probe=e373d39f20) | Jun 09, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| ASUSTek       | N501VW                      | [2f8215fb0a](https://linux-hardware.org/?probe=2f8215fb0a) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Dell          | XPS 15 9520                 | [4d4c32223e](https://linux-hardware.org/?probe=4d4c32223e) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [63fd75f1a8](https://linux-hardware.org/?probe=63fd75f1a8) | May 29, 2022 |
| Lenovo        | Legion Y7000P2020H 82AX     | [220325c031](https://linux-hardware.org/?probe=220325c031) | May 29, 2022 |
| Dell          | XPS 15 9520                 | [75d345243e](https://linux-hardware.org/?probe=75d345243e) | May 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Intel Clie... | LAPKC71F                    | [1f67896c5c](https://linux-hardware.org/?probe=1f67896c5c) | May 22, 2022 |
| Intel Clie... | LAPKC71F                    | [a227af798c](https://linux-hardware.org/?probe=a227af798c) | May 20, 2022 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [f0b122c199](https://linux-hardware.org/?probe=f0b122c199) | May 09, 2022 |
| Dell          | Precision 7520              | [2dc98a1a8d](https://linux-hardware.org/?probe=2dc98a1a8d) | Apr 30, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [9191742453](https://linux-hardware.org/?probe=9191742453) | Apr 26, 2022 |
| Apple         | MacBookAir5,1               | [3dd8282149](https://linux-hardware.org/?probe=3dd8282149) | Apr 20, 2022 |
| GPD           | P2 MAX                      | [ca842dc5fb](https://linux-hardware.org/?probe=ca842dc5fb) | Apr 19, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [bdca066ba3](https://linux-hardware.org/?probe=bdca066ba3) | Apr 05, 2022 |
| Dell          | Inspiron 14 5410            | [314bd42e78](https://linux-hardware.org/?probe=314bd42e78) | Mar 28, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | [a881a875bd](https://linux-hardware.org/?probe=a881a875bd) | Mar 27, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [2d48cb4419](https://linux-hardware.org/?probe=2d48cb4419) | Mar 26, 2022 |
| Dell          | Latitude 7285               | [87e555f958](https://linux-hardware.org/?probe=87e555f958) | Mar 13, 2022 |
| Fujitsu       | LIFEBOOK AH544              | [03b27c8ca4](https://linux-hardware.org/?probe=03b27c8ca4) | Mar 12, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [4998fff0f9](https://linux-hardware.org/?probe=4998fff0f9) | Mar 12, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [c68cec2207](https://linux-hardware.org/?probe=c68cec2207) | Mar 11, 2022 |
| Fujitsu       | LIFEBOOK AH544              | [96b36779e0](https://linux-hardware.org/?probe=96b36779e0) | Mar 11, 2022 |
| HP            | Notebook                    | [9c04c0776d](https://linux-hardware.org/?probe=9c04c0776d) | Mar 10, 2022 |
| HP            | Notebook                    | [c7d735dc99](https://linux-hardware.org/?probe=c7d735dc99) | Mar 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [0f4fad19b2](https://linux-hardware.org/?probe=0f4fad19b2) | Feb 07, 2022 |
| Dell          | Inspiron 5580               | [515465fd5a](https://linux-hardware.org/?probe=515465fd5a) | Jan 22, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| HP            | EliteBook 830 G5            | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| Fujitsu       | LIFEBOOK LH530              | [8db7409ab5](https://linux-hardware.org/?probe=8db7409ab5) | Dec 14, 2021 |
| Unknown       | Unknown                     | [739be994cb](https://linux-hardware.org/?probe=739be994cb) | Dec 09, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | [024a42eb21](https://linux-hardware.org/?probe=024a42eb21) | Dec 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ee13ae89af](https://linux-hardware.org/?probe=ee13ae89af) | Nov 26, 2021 |
| Apple         | MacBook10,1                 | [6cb99e6a5f](https://linux-hardware.org/?probe=6cb99e6a5f) | Nov 23, 2021 |
| Jumper        | EZbook                      | [5da2b95e2f](https://linux-hardware.org/?probe=5da2b95e2f) | Nov 12, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| Unknown       | Unknown                     | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| HP            | Laptop 15s-du3xxx           | [6f87ece998](https://linux-hardware.org/?probe=6f87ece998) | Oct 26, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [3d42bc888b](https://linux-hardware.org/?probe=3d42bc888b) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [54e54e71bd](https://linux-hardware.org/?probe=54e54e71bd) | Oct 24, 2021 |
| Dell          | XPS 13 9310                 | [20dc49f637](https://linux-hardware.org/?probe=20dc49f637) | Oct 13, 2021 |
| Lenovo        | Legion Y9000P2021H 82JD     | [4c3be0fe24](https://linux-hardware.org/?probe=4c3be0fe24) | Oct 02, 2021 |
| GPD           | G1618-03                    | [41916177c2](https://linux-hardware.org/?probe=41916177c2) | Sep 01, 2021 |
| GPD           | G1618-03                    | [c2abcaf10c](https://linux-hardware.org/?probe=c2abcaf10c) | Sep 01, 2021 |
| Dell          | Precision 7550              | [42721343a3](https://linux-hardware.org/?probe=42721343a3) | Aug 16, 2021 |
| Lenovo        | XiaoXin-14API QC 2019 81... | [814eb97442](https://linux-hardware.org/?probe=814eb97442) | Aug 14, 2021 |
| Lenovo        | ThinkPad T61 6465CTO        | [d93258840e](https://linux-hardware.org/?probe=d93258840e) | Aug 04, 2021 |
| HP            | EliteBook 2540p             | [eb060cd2c4](https://linux-hardware.org/?probe=eb060cd2c4) | Aug 04, 2021 |
| Toshiba       | dynabook R731/E             | [828a52387f](https://linux-hardware.org/?probe=828a52387f) | Aug 02, 2021 |
| Toshiba       | dynabook R731/E             | [12b2c3e130](https://linux-hardware.org/?probe=12b2c3e130) | Aug 01, 2021 |
| Toshiba       | dynabook R731/E             | [3af43c8ebe](https://linux-hardware.org/?probe=3af43c8ebe) | Jul 29, 2021 |
| Toshiba       | dynabook R731/E             | [fa0aa86cef](https://linux-hardware.org/?probe=fa0aa86cef) | Jul 28, 2021 |
| Unknown       | Unknown                     | [8fc32673b3](https://linux-hardware.org/?probe=8fc32673b3) | Jul 25, 2021 |
| Toshiba       | dynabook R731/E             | [c2bfccf320](https://linux-hardware.org/?probe=c2bfccf320) | Jun 16, 2021 |
| Toshiba       | dynabook R731/E             | [d3f69874dd](https://linux-hardware.org/?probe=d3f69874dd) | Jun 16, 2021 |
| Dell          | Precision M4800             | [298694c222](https://linux-hardware.org/?probe=298694c222) | Jun 12, 2021 |
| Acer          | Aspire E5-573               | [4193a2da9d](https://linux-hardware.org/?probe=4193a2da9d) | Jun 08, 2021 |
| Dell          | Precision M4800             | [67fb08d285](https://linux-hardware.org/?probe=67fb08d285) | Jun 06, 2021 |
| Dell          | Precision M4800             | [c72664a2f4](https://linux-hardware.org/?probe=c72664a2f4) | Jun 06, 2021 |
| Toshiba       | dynabook R731/E             | [81ffc7ba9e](https://linux-hardware.org/?probe=81ffc7ba9e) | May 26, 2021 |
| Fujitsu       | UH-X                        | [be65091e59](https://linux-hardware.org/?probe=be65091e59) | May 19, 2021 |
| Panasonic     | CFSZ5-2L                    | [1409e11b30](https://linux-hardware.org/?probe=1409e11b30) | May 12, 2021 |
| Dell          | XPS 13 9310                 | [8d372d62b7](https://linux-hardware.org/?probe=8d372d62b7) | May 07, 2021 |
| Panasonic     | CFSZ5-2L                    | [f35a966b00](https://linux-hardware.org/?probe=f35a966b00) | Apr 14, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | [a917367457](https://linux-hardware.org/?probe=a917367457) | Apr 09, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | [f7937503ac](https://linux-hardware.org/?probe=f7937503ac) | Apr 08, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | [99d71b6ea5](https://linux-hardware.org/?probe=99d71b6ea5) | Apr 06, 2021 |
| Lenovo        | IdeaPad Z410 20292          | [8253b70553](https://linux-hardware.org/?probe=8253b70553) | Apr 06, 2021 |
| Fujitsu       | LIFEBOOK AH544              | [60600f6f0c](https://linux-hardware.org/?probe=60600f6f0c) | Mar 26, 2021 |
| ASUSTek       | UX302LA                     | [fe27a8e195](https://linux-hardware.org/?probe=fe27a8e195) | Mar 12, 2021 |
| Acer          | Aspire A315-34              | [d23d84b5f6](https://linux-hardware.org/?probe=d23d84b5f6) | Mar 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [5051ba6156](https://linux-hardware.org/?probe=5051ba6156) | Mar 05, 2021 |
| Fujitsu       | LIFEBOOK P771               | [2414020b54](https://linux-hardware.org/?probe=2414020b54) | Feb 26, 2021 |
| Fujitsu       | LIFEBOOK P771               | [ae61a5e1fa](https://linux-hardware.org/?probe=ae61a5e1fa) | Feb 26, 2021 |
| Lenovo        | ThinkPad E14 20RAA002CD     | [77ccb1ee60](https://linux-hardware.org/?probe=77ccb1ee60) | Feb 22, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | [7d9f2bee38](https://linux-hardware.org/?probe=7d9f2bee38) | Feb 21, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | [d82924b12b](https://linux-hardware.org/?probe=d82924b12b) | Feb 16, 2021 |
| Lenovo        | G710 20252                  | [f4c2a6bac8](https://linux-hardware.org/?probe=f4c2a6bac8) | Feb 07, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | [d4f69c78fa](https://linux-hardware.org/?probe=d4f69c78fa) | Jan 31, 2021 |
| Fujitsu       | S6420                       | [b23c0f10e7](https://linux-hardware.org/?probe=b23c0f10e7) | Jan 28, 2021 |
| Fujitsu       | S6420                       | [0cf6376b40](https://linux-hardware.org/?probe=0cf6376b40) | Jan 27, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [3d7ce778c6](https://linux-hardware.org/?probe=3d7ce778c6) | Jan 20, 2021 |
| HUAWEI        | KPRC-WX0                    | [fe7d03f093](https://linux-hardware.org/?probe=fe7d03f093) | Jan 18, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [a8ac85cb5a](https://linux-hardware.org/?probe=a8ac85cb5a) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [8c7ba97457](https://linux-hardware.org/?probe=8c7ba97457) | Dec 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [01333c5b9e](https://linux-hardware.org/?probe=01333c5b9e) | Dec 29, 2020 |
| Panasonic     | CFSZ5-2L                    | [728d7e48d4](https://linux-hardware.org/?probe=728d7e48d4) | Dec 27, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | [1d4b16bb0d](https://linux-hardware.org/?probe=1d4b16bb0d) | Dec 22, 2020 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [88a7edec45](https://linux-hardware.org/?probe=88a7edec45) | Dec 18, 2020 |
| Sony          | VPCCB17FG                   | [ede3032fed](https://linux-hardware.org/?probe=ede3032fed) | Nov 29, 2020 |
| Sony          | VPCCB17FG                   | [f3012a2898](https://linux-hardware.org/?probe=f3012a2898) | Nov 29, 2020 |
| Sony          | VPCCB17FG                   | [3c4ff5bb58](https://linux-hardware.org/?probe=3c4ff5bb58) | Nov 27, 2020 |
| Sony          | VPCCB17FG                   | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| Fujitsu       | UH-X                        | [f55a6a6679](https://linux-hardware.org/?probe=f55a6a6679) | Nov 20, 2020 |
| Fujitsu       | UH-X                        | [7aea886f7a](https://linux-hardware.org/?probe=7aea886f7a) | Nov 20, 2020 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | [6254edfb10](https://linux-hardware.org/?probe=6254edfb10) | Nov 14, 2020 |
| Lenovo        | G770 20089                  | [6da9203114](https://linux-hardware.org/?probe=6da9203114) | Nov 13, 2020 |
| HP            | 2000                        | [f548e6d1cc](https://linux-hardware.org/?probe=f548e6d1cc) | Nov 11, 2020 |
| ASUSTek       | K501UX                      | [e1700b887e](https://linux-hardware.org/?probe=e1700b887e) | Nov 09, 2020 |
| HP            | 2000                        | [df76d279ad](https://linux-hardware.org/?probe=df76d279ad) | Nov 05, 2020 |
| Timi          | TM1607                      | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| Acer          | Swift SF314-57              | [8395e5a946](https://linux-hardware.org/?probe=8395e5a946) | Oct 30, 2020 |
| Acer          | Swift SF314-57              | [123f60c868](https://linux-hardware.org/?probe=123f60c868) | Oct 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [f9d1166197](https://linux-hardware.org/?probe=f9d1166197) | Oct 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [77849f8db0](https://linux-hardware.org/?probe=77849f8db0) | Oct 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [77d6dd66e2](https://linux-hardware.org/?probe=77d6dd66e2) | Oct 23, 2020 |
| HP            | 2140                        | [bde3dc449f](https://linux-hardware.org/?probe=bde3dc449f) | Oct 07, 2020 |
| HUAWEI        | WRT-WX9                     | [1fe32b8f6d](https://linux-hardware.org/?probe=1fe32b8f6d) | Oct 04, 2020 |
| HP            | 2000                        | [fbd8bf0e69](https://linux-hardware.org/?probe=fbd8bf0e69) | Oct 01, 2020 |
| Fujitsu       | LIFEBOOK S904               | [5035864c45](https://linux-hardware.org/?probe=5035864c45) | Sep 27, 2020 |
| Dell          | Inspiron N5050              | [37e6b406f7](https://linux-hardware.org/?probe=37e6b406f7) | Sep 27, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [bd8f561b0b](https://linux-hardware.org/?probe=bd8f561b0b) | Sep 27, 2020 |
| Dell          | Inspiron N5050              | [64a249acd1](https://linux-hardware.org/?probe=64a249acd1) | Aug 28, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [6a91a7b38c](https://linux-hardware.org/?probe=6a91a7b38c) | Aug 25, 2020 |
| Samsung       | 930XBE                      | [92925e0656](https://linux-hardware.org/?probe=92925e0656) | Aug 24, 2020 |
| Dell          | Inspiron 5580               | [fbaf2b8f7f](https://linux-hardware.org/?probe=fbaf2b8f7f) | Aug 05, 2020 |
| Panasonic     | CFSZ5-2L                    | [e7488a8b16](https://linux-hardware.org/?probe=e7488a8b16) | Aug 04, 2020 |
| Toshiba       | PORTEGE R830                | [fa44f09e6e](https://linux-hardware.org/?probe=fa44f09e6e) | Aug 03, 2020 |
| Dell          | G7 7588                     | [e85e2949de](https://linux-hardware.org/?probe=e85e2949de) | Aug 01, 2020 |
| Lenovo        | ZHAOYANG K47                | [fa5be40392](https://linux-hardware.org/?probe=fa5be40392) | Jul 24, 2020 |
| Lenovo        | ZHAOYANG K47                | [879b0d586f](https://linux-hardware.org/?probe=879b0d586f) | Jul 22, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [723898cdec](https://linux-hardware.org/?probe=723898cdec) | Jun 20, 2020 |
| Fujitsu       | LIFEBOOK AH544              | [f897dd388f](https://linux-hardware.org/?probe=f897dd388f) | Jun 17, 2020 |
| Lenovo        | E10-30 20424                | [c90b1cb242](https://linux-hardware.org/?probe=c90b1cb242) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | [74dadf599d](https://linux-hardware.org/?probe=74dadf599d) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | [db21903e1a](https://linux-hardware.org/?probe=db21903e1a) | Jun 14, 2020 |
| Lenovo        | ThinkPad T480s 20L7005FU... | [2bc99eeca5](https://linux-hardware.org/?probe=2bc99eeca5) | Jun 09, 2020 |
| Fujitsu       | LIFEBOOK AH556              | [c16b3d9827](https://linux-hardware.org/?probe=c16b3d9827) | May 30, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [55680319a1](https://linux-hardware.org/?probe=55680319a1) | May 29, 2020 |
| Apple         | MacBookPro7,1               | [956da1ac80](https://linux-hardware.org/?probe=956da1ac80) | May 11, 2020 |
| Toshiba       | PORTEGE R830                | [08f3e97afe](https://linux-hardware.org/?probe=08f3e97afe) | May 02, 2020 |
| Lenovo        | 3000 G410                   | [2a909aaad5](https://linux-hardware.org/?probe=2a909aaad5) | May 02, 2020 |
| Dell          | XPS 13 9370                 | [f11d6eedc7](https://linux-hardware.org/?probe=f11d6eedc7) | Apr 14, 2020 |
| HP            | G72                         | [6272536a26](https://linux-hardware.org/?probe=6272536a26) | Apr 11, 2020 |
| Google        | Eve                         | [17c248ca99](https://linux-hardware.org/?probe=17c248ca99) | Apr 04, 2020 |
| Dell          | Inspiron 3593               | [597092ba51](https://linux-hardware.org/?probe=597092ba51) | Feb 28, 2020 |
| Dell          | Inspiron 3593               | [71fc35ceea](https://linux-hardware.org/?probe=71fc35ceea) | Feb 28, 2020 |
| MSI           | GS73VR 7RG                  | [fbdf43d1d6](https://linux-hardware.org/?probe=fbdf43d1d6) | Feb 04, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cf4dbec684](https://linux-hardware.org/?probe=cf4dbec684) | Feb 01, 2020 |
| Unknown       | Unknown                     | [1007637420](https://linux-hardware.org/?probe=1007637420) | Dec 31, 2019 |
| Unknown       | Unknown                     | [bb58a92938](https://linux-hardware.org/?probe=bb58a92938) | Dec 31, 2019 |
| Dell          | XPS 13 9370                 | [0f39165d62](https://linux-hardware.org/?probe=0f39165d62) | Dec 06, 2019 |
| Dell          | XPS 13 9370                 | [816ad4feea](https://linux-hardware.org/?probe=816ad4feea) | Dec 06, 2019 |
| ASUSTek       | X556URK                     | [78f15ad5f0](https://linux-hardware.org/?probe=78f15ad5f0) | Nov 30, 2019 |
| HP            | EliteBook 2540p             | [49e2cab57b](https://linux-hardware.org/?probe=49e2cab57b) | Nov 28, 2019 |
| HUAWEI        | KPRC-WX0                    | [042c4b3c5a](https://linux-hardware.org/?probe=042c4b3c5a) | Nov 22, 2019 |
| HP            | EliteBook 2540p             | [f63dcc4fc8](https://linux-hardware.org/?probe=f63dcc4fc8) | Nov 07, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3497939f58](https://linux-hardware.org/?probe=3497939f58) | Oct 18, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a04ed98be8](https://linux-hardware.org/?probe=a04ed98be8) | Oct 18, 2019 |
| HP            | EliteBook 2540p             | [b2ebcf2c70](https://linux-hardware.org/?probe=b2ebcf2c70) | Oct 10, 2019 |
| HP            | EliteBook 2540p             | [43a5e168a1](https://linux-hardware.org/?probe=43a5e168a1) | Oct 10, 2019 |
| Unknown       | Unknown                     | [f8f1207d2d](https://linux-hardware.org/?probe=f8f1207d2d) | Sep 29, 2019 |
| Unknown       | Unknown                     | [d19b3f1330](https://linux-hardware.org/?probe=d19b3f1330) | Sep 28, 2019 |
| Unknown       | Unknown                     | [a6d4347345](https://linux-hardware.org/?probe=a6d4347345) | Sep 28, 2019 |
| Acer          | Aspire S3-371               | [5086f9ddaa](https://linux-hardware.org/?probe=5086f9ddaa) | Sep 07, 2019 |
| Acer          | Aspire S3-371               | [aa8140a178](https://linux-hardware.org/?probe=aa8140a178) | Sep 03, 2019 |
| ASUSTek       | TUF GAMING FX504GM_FX80G... | [7e9553ea70](https://linux-hardware.org/?probe=7e9553ea70) | Jun 03, 2019 |
| Lenovo        | ThinkPad T430 2342AG4       | [cf7413e712](https://linux-hardware.org/?probe=cf7413e712) | May 31, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | [e8a5c28644](https://linux-hardware.org/?probe=e8a5c28644) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | [b67f52c0c2](https://linux-hardware.org/?probe=b67f52c0c2) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | [c408ceb62e](https://linux-hardware.org/?probe=c408ceb62e) | May 29, 2019 |
| Dell          | Latitude E4310              | [134afc5b6b](https://linux-hardware.org/?probe=134afc5b6b) | May 08, 2019 |
| Lenovo        | ThinkPad T520 4242BC5       | [977c44b97a](https://linux-hardware.org/?probe=977c44b97a) | Apr 29, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | [5801835e32](https://linux-hardware.org/?probe=5801835e32) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | [0f4999f205](https://linux-hardware.org/?probe=0f4999f205) | Apr 27, 2019 |
| Unknown       | A11-COMPUTER                | [fae06bb10f](https://linux-hardware.org/?probe=fae06bb10f) | Mar 28, 2019 |
| Unknown       | A11-COMPUTER                | [427daf4d4e](https://linux-hardware.org/?probe=427daf4d4e) | Mar 28, 2019 |
| Lenovo        | ThinkPad W530 24384KU       | [2064d92892](https://linux-hardware.org/?probe=2064d92892) | Dec 12, 2018 |
| Dell          | XPS 13 9350                 | [6fb539c340](https://linux-hardware.org/?probe=6fb539c340) | Oct 29, 2018 |
| HP            | ProBook 4540s               | [ace9a95fb7](https://linux-hardware.org/?probe=ace9a95fb7) | May 09, 2018 |
| HP            | ProBook 4540s               | [8f50260d94](https://linux-hardware.org/?probe=8f50260d94) | May 09, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 30        | 13.16%  |
| Ubuntu 22.04        | 17        | 7.46%   |
| Arch Rolling        | 12        | 5.26%   |
| Ubuntu 18.04        | 9         | 3.95%   |
| antiX 21            | 9         | 3.95%   |
| Fedora 37           | 8         | 3.51%   |
| Arch                | 8         | 3.51%   |
| Fedora 32           | 5         | 2.19%   |
| ArcoLinux Rolling   | 5         | 2.19%   |
| Ubuntu 19.10        | 4         | 1.75%   |
| OpenMandriva 23.03  | 4         | 1.75%   |
| Gentoo 2.7          | 4         | 1.75%   |
| EndeavourOS Rolling | 4         | 1.75%   |
| Debian 11           | 4         | 1.75%   |
| Ubuntu 22.10        | 3         | 1.32%   |
| OpenMandriva 4.2    | 3         | 1.32%   |
| OpenMandriva 23.01  | 3         | 1.32%   |
| Linux Mint 20       | 3         | 1.32%   |
| Kylin V10           | 3         | 1.32%   |
| Fedora 36           | 3         | 1.32%   |
| Fedora 33           | 3         | 1.32%   |
| Debian 12           | 3         | 1.32%   |
| Chrome OS           | 3         | 1.32%   |
| Ubuntu 23.04        | 2         | 0.88%   |
| Ubuntu 21.04        | 2         | 0.88%   |
| Ubuntu 19.04        | 2         | 0.88%   |
| Ubuntu 16.04        | 2         | 0.88%   |
| SteamOS Rolling     | 2         | 0.88%   |
| Pop!_OS 22.04       | 2         | 0.88%   |
| Pop!_OS 20.10       | 2         | 0.88%   |
| Pop!_OS 20.04       | 2         | 0.88%   |
| OpenMandriva 4.50   | 2         | 0.88%   |
| Manjaro 20.1        | 2         | 0.88%   |
| Linux Mint 20.3     | 2         | 0.88%   |
| KDE neon 20.04      | 2         | 0.88%   |
| Gentoo 2.8          | 2         | 0.88%   |
| Fedora 34           | 2         | 0.88%   |
| Debian Testing      | 2         | 0.88%   |
| Zorin 15            | 1         | 0.44%   |
| UOS 20              | 1         | 0.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 71        | 32.57%  |
| Fedora        | 22        | 10.09%  |
| Arch          | 20        | 9.17%   |
| OpenMandriva  | 14        | 6.42%   |
| antiX         | 9         | 4.13%   |
| Pop!_OS       | 8         | 3.67%   |
| Linux Mint    | 8         | 3.67%   |
| Debian        | 8         | 3.67%   |
| Manjaro       | 6         | 2.75%   |
| Gentoo        | 6         | 2.75%   |
| ArcoLinux     | 5         | 2.29%   |
| EndeavourOS   | 4         | 1.83%   |
| Clear Linux   | 4         | 1.83%   |
| Ubuntu Unity  | 3         | 1.38%   |
| SteamOS       | 3         | 1.38%   |
| Kylin         | 3         | 1.38%   |
| Chrome OS     | 3         | 1.38%   |
| ROSA          | 2         | 0.92%   |
| openSUSE      | 2         | 0.92%   |
| KDE neon      | 2         | 0.92%   |
| Zorin         | 1         | 0.46%   |
| Ultramarine   | 1         | 0.46%   |
| UbuntuDDE     | 1         | 0.46%   |
| Ubuntu MATE   | 1         | 0.46%   |
| Ubuntu Budgie | 1         | 0.46%   |
| PCLinuxOS     | 1         | 0.46%   |
| Oracle Linux  | 1         | 0.46%   |
| Nobara        | 1         | 0.46%   |
| NixOS         | 1         | 0.46%   |
| Kubuntu       | 1         | 0.46%   |
| Kali          | 1         | 0.46%   |
| Guix          | 1         | 0.46%   |
| Elementary    | 1         | 0.46%   |
| Deepin        | 1         | 0.46%   |
| BlackPanther  | 1         | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp       | 9         | 3.7%    |
| 5.4.0-42-generic                | 6         | 2.47%   |
| 6.2.6-desktop-1omv2390          | 4         | 1.65%   |
| 6.3.6-arch1-1                   | 3         | 1.23%   |
| 6.1.1-desktop-1omv2290          | 3         | 1.23%   |
| 5.8.0-43-generic                | 3         | 1.23%   |
| 5.4.0-48-generic                | 3         | 1.23%   |
| 5.19.0-32-generic               | 3         | 1.23%   |
| 5.15.0-46-generic               | 3         | 1.23%   |
| 5.13.0-39-generic               | 3         | 1.23%   |
| 5.10.14-desktop-1omv4002        | 3         | 1.23%   |
| 4.19.49+                        | 3         | 1.23%   |
| 6.1.21-valve1-3-neptune-61      | 2         | 0.82%   |
| 6.1.0-11-amd64                  | 2         | 0.82%   |
| 6.0.12-300.fc37.x86_64          | 2         | 0.82%   |
| 5.9.2-arch1-1                   | 2         | 0.82%   |
| 5.8.0-7630-generic              | 2         | 0.82%   |
| 5.4.0-58-generic                | 2         | 0.82%   |
| 5.4.0-28-generic                | 2         | 0.82%   |
| 5.4.0-26-generic                | 2         | 0.82%   |
| 5.3.0-18-generic                | 2         | 0.82%   |
| 5.17.11-300.fc36.x86_64         | 2         | 0.82%   |
| 5.15.0-60-generic               | 2         | 0.82%   |
| 5.15.0-58-generic               | 2         | 0.82%   |
| 5.15.0-47-generic               | 2         | 0.82%   |
| 5.13.0-35-generic               | 2         | 0.82%   |
| 5.11.0-37-generic               | 2         | 0.82%   |
| 5.0.0-31-generic                | 2         | 0.82%   |
| 4.18.0-15-generic               | 2         | 0.82%   |
| 6.4.7-arch1-1                   | 1         | 0.41%   |
| 6.4.7-100.fc37.x86_64           | 1         | 0.41%   |
| 6.4.3-arch1-1                   | 1         | 0.41%   |
| 6.4.2-zen1-1-zen                | 1         | 0.41%   |
| 6.4.2-arch1-1-custom            | 1         | 0.41%   |
| 6.4.2-arch1-1                   | 1         | 0.41%   |
| 6.4.11-arch2-1                  | 1         | 0.41%   |
| 6.4.0-asahi-00515-g35564c906fa6 | 1         | 0.41%   |
| 6.4.0                           | 1         | 0.41%   |
| 6.3.8-arch1-1                   | 1         | 0.41%   |
| 6.3.5-desktop-3omv2390          | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 9.05%   |
| 5.15.0  | 15        | 6.47%   |
| 5.19.0  | 13        | 5.6%    |
| 5.13.0  | 11        | 4.74%   |
| 5.8.0   | 9         | 3.88%   |
| 4.9.0   | 9         | 3.88%   |
| 4.15.0  | 7         | 3.02%   |
| 6.2.0   | 6         | 2.59%   |
| 5.11.0  | 6         | 2.59%   |
| 5.3.0   | 5         | 2.16%   |
| 5.0.0   | 5         | 2.16%   |
| 6.2.6   | 4         | 1.72%   |
| 6.4.2   | 3         | 1.29%   |
| 6.3.6   | 3         | 1.29%   |
| 6.1.1   | 3         | 1.29%   |
| 6.1.0   | 3         | 1.29%   |
| 5.10.14 | 3         | 1.29%   |
| 5.10.0  | 3         | 1.29%   |
| 4.19.49 | 3         | 1.29%   |
| 6.4.7   | 2         | 0.86%   |
| 6.4.0   | 2         | 0.86%   |
| 6.1.21  | 2         | 0.86%   |
| 6.1.14  | 2         | 0.86%   |
| 6.1.11  | 2         | 0.86%   |
| 6.0.12  | 2         | 0.86%   |
| 6.0.0   | 2         | 0.86%   |
| 5.9.2   | 2         | 0.86%   |
| 5.17.4  | 2         | 0.86%   |
| 5.17.11 | 2         | 0.86%   |
| 4.18.0  | 2         | 0.86%   |
| 6.4.3   | 1         | 0.43%   |
| 6.4.11  | 1         | 0.43%   |
| 6.3.8   | 1         | 0.43%   |
| 6.3.5   | 1         | 0.43%   |
| 6.3.11  | 1         | 0.43%   |
| 6.2.8   | 1         | 0.43%   |
| 6.1.9   | 1         | 0.43%   |
| 6.1.7   | 1         | 0.43%   |
| 6.1.39  | 1         | 0.43%   |
| 6.1.22  | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 21        | 9.21%   |
| 5.19    | 20        | 8.77%   |
| 5.15    | 20        | 8.77%   |
| 6.1     | 17        | 7.46%   |
| 5.13    | 13        | 5.7%    |
| 5.10    | 13        | 5.7%    |
| 5.8     | 12        | 5.26%   |
| 5.11    | 12        | 5.26%   |
| 6.2     | 11        | 4.82%   |
| 4.9     | 11        | 4.82%   |
| 6.4     | 9         | 3.95%   |
| 5.3     | 8         | 3.51%   |
| 5.17    | 8         | 3.51%   |
| 4.15    | 7         | 3.07%   |
| 6.0     | 6         | 2.63%   |
| 5.9     | 6         | 2.63%   |
| 6.3     | 5         | 2.19%   |
| 5.14    | 5         | 2.19%   |
| 5.0     | 5         | 2.19%   |
| 5.7     | 4         | 1.75%   |
| 5.16    | 4         | 1.75%   |
| 5.18    | 3         | 1.32%   |
| 4.19    | 3         | 1.32%   |
| 4.18    | 3         | 1.32%   |
| 5.6     | 1         | 0.44%   |
| 5.12    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 198       | 93.4%   |
| i686    | 12        | 5.66%   |
| i586    | 1         | 0.47%   |
| aarch64 | 1         | 0.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 104       | 47.49%  |
| KDE5       | 48        | 21.92%  |
| Unknown    | 31        | 14.16%  |
| XFCE       | 7         | 3.2%    |
| X-Cinnamon | 6         | 2.74%   |
| i3         | 5         | 2.28%   |
| KDE        | 4         | 1.83%   |
| Unity      | 2         | 0.91%   |
| LXQt       | 2         | 0.91%   |
| dwm        | 2         | 0.91%   |
| Deepin     | 2         | 0.91%   |
| MATE       | 1         | 0.46%   |
| icewm      | 1         | 0.46%   |
| Hyprland   | 1         | 0.46%   |
| fvwm       | 1         | 0.46%   |
| Cinnamon   | 1         | 0.46%   |
| Budgie     | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 158       | 73.49%  |
| Wayland | 43        | 20%     |
| Unknown | 10        | 4.65%   |
| Tty     | 4         | 1.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 81        | 37.85%  |
| SDDM    | 45        | 21.03%  |
| GDM     | 36        | 16.82%  |
| GDM3    | 29        | 13.55%  |
| LightDM | 18        | 8.41%   |
| TDM     | 4         | 1.87%   |
| LXDM    | 1         | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 89        | 40.09%  |
| en_HK   | 43        | 19.37%  |
| zh_CN   | 38        | 17.12%  |
| Unknown | 19        | 8.56%   |
| zh_TW   | 8         | 3.6%    |
| zh_HK   | 8         | 3.6%    |
| C       | 7         | 3.15%   |
| en_GB   | 5         | 2.25%   |
| zh_SG   | 1         | 0.45%   |
| it_IT   | 1         | 0.45%   |
| en_ZA   | 1         | 0.45%   |
| en_AU   | 1         | 0.45%   |
| de_DE   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 154       | 72.3%   |
| BIOS | 59        | 27.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 150       | 69.12%  |
| Btrfs   | 32        | 14.75%  |
| Overlay | 16        | 7.37%   |
| Unknown | 7         | 3.23%   |
| Zfs     | 4         | 1.84%   |
| Xfs     | 3         | 1.38%   |
| Tmpfs   | 2         | 0.92%   |
| Ext2    | 2         | 0.92%   |
| Ext3    | 1         | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 125       | 58.14%  |
| Unknown | 73        | 33.95%  |
| MBR     | 17        | 7.91%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 190       | 88.37%  |
| Yes       | 25        | 11.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 125       | 58.14%  |
| Yes       | 90        | 41.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 69        | 32.55%  |
| Dell                 | 25        | 11.79%  |
| Hewlett-Packard      | 21        | 9.91%   |
| ASUSTek Computer     | 19        | 8.96%   |
| Fujitsu              | 13        | 6.13%   |
| Unknown              | 10        | 4.72%   |
| Acer                 | 8         | 3.77%   |
| HUAWEI               | 7         | 3.3%    |
| Apple                | 6         | 2.83%   |
| Samsung Electronics  | 4         | 1.89%   |
| GPD                  | 4         | 1.89%   |
| Chuwi                | 3         | 1.42%   |
| Toshiba              | 2         | 0.94%   |
| Timi                 | 2         | 0.94%   |
| MSI                  | 2         | 0.94%   |
| KOHJINSHA            | 2         | 0.94%   |
| IBM                  | 2         | 0.94%   |
| Valve                | 1         | 0.47%   |
| Sony                 | 1         | 0.47%   |
| Schenker             | 1         | 0.47%   |
| Panasonic            | 1         | 0.47%   |
| ONE-NETBOOK          | 1         | 0.47%   |
| METAPHYUNI           | 1         | 0.47%   |
| MACHENIKE            | 1         | 0.47%   |
| LG Electronics       | 1         | 0.47%   |
| Jumper               | 1         | 0.47%   |
| Intel Client Systems | 1         | 0.47%   |
| Google               | 1         | 0.47%   |
| Compaq               | 1         | 0.47%   |
| AMI                  | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 11        | 5.19%   |
| Lenovo Legion R7000 2020 82B6       | 3         | 1.42%   |
| Chuwi HeroBook Pro                  | 3         | 1.42%   |
| Lenovo XiaoXinPro 14ITL 2021 82GH   | 2         | 0.94%   |
| Lenovo ThinkBook 14 G4+ ARA 21D0    | 2         | 0.94%   |
| IBM 260921H                         | 2         | 0.94%   |
| HUAWEI KPRC-WX0                     | 2         | 0.94%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC    | 2         | 0.94%   |
| HP Pavilion Gaming Laptop 15-ec2xxx | 2         | 0.94%   |
| HP OMEN by Gaming Laptop 16-wf0xxx  | 2         | 0.94%   |
| HP EliteBook 2540p                  | 2         | 0.94%   |
| GPD G1619-04                        | 2         | 0.94%   |
| Fujitsu UH-X                        | 2         | 0.94%   |
| Fujitsu LIFEBOOK AH544              | 2         | 0.94%   |
| Fujitsu FMVNU6G1C                   | 2         | 0.94%   |
| Dell XPS 13 9310                    | 2         | 0.94%   |
| Dell Inspiron 5580                  | 2         | 0.94%   |
| ASUS TUF Gaming FA506IU_FA506IU     | 2         | 0.94%   |
| Valve Jupiter                       | 1         | 0.47%   |
| Toshiba PORTEGE R830                | 1         | 0.47%   |
| Toshiba dynabook R731/E             | 1         | 0.47%   |
| Timi TM1613                         | 1         | 0.47%   |
| Timi TM1607                         | 1         | 0.47%   |
| Sony VPCCB17FG                      | 1         | 0.47%   |
| Schenker XMG_APEX15_XAP15E20        | 1         | 0.47%   |
| Samsung SQ1S                        | 1         | 0.47%   |
| Samsung 950XCJ/951XCJ/950XCR        | 1         | 0.47%   |
| Samsung 930XBE                      | 1         | 0.47%   |
| Samsung 905S3G/906S3G/915S3G/9305SG | 1         | 0.47%   |
| Panasonic CFSZ5-2L                  | 1         | 0.47%   |
| ONE-NETBOOK ONEXPLAYER 2 ARP23      | 1         | 0.47%   |
| MSI GS73VR 7RG                      | 1         | 0.47%   |
| MSI GS65 Stealth Thin 8RE           | 1         | 0.47%   |
| METAPHYUNI MetamechBook             | 1         | 0.47%   |
| MACHENIKE T58-V                     | 1         | 0.47%   |
| LG 16Z90R-K.ADB9U1                  | 1         | 0.47%   |
| Lenovo ZHAOYANG K47                 | 1         | 0.47%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS  | 1         | 0.47%   |
| Lenovo Y430P 20435                  | 1         | 0.47%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN   | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 33        | 15.57%  |
| Lenovo Legion          | 11        | 5.19%   |
| Unknown                | 11        | 5.19%   |
| Dell XPS               | 9         | 4.25%   |
| Fujitsu LIFEBOOK       | 8         | 3.77%   |
| Dell Inspiron          | 8         | 3.77%   |
| Lenovo IdeaPad         | 7         | 3.3%    |
| Lenovo ThinkBook       | 4         | 1.89%   |
| HP Pavilion            | 4         | 1.89%   |
| Dell Latitude          | 4         | 1.89%   |
| ASUS ROG               | 4         | 1.89%   |
| Acer Swift             | 4         | 1.89%   |
| HP ZHAN                | 3         | 1.42%   |
| HP OMEN                | 3         | 1.42%   |
| HP EliteBook           | 3         | 1.42%   |
| Dell Precision         | 3         | 1.42%   |
| Chuwi HeroBook         | 3         | 1.42%   |
| ASUS TUF               | 3         | 1.42%   |
| Acer Aspire            | 3         | 1.42%   |
| Lenovo XiaoXinPro      | 2         | 0.94%   |
| IBM 260921H            | 2         | 0.94%   |
| HUAWEI KPRC-WX0        | 2         | 0.94%   |
| GPD G1619-04           | 2         | 0.94%   |
| Fujitsu UH-X           | 2         | 0.94%   |
| Fujitsu FMVNU6G1C      | 2         | 0.94%   |
| ASUS VivoBook          | 2         | 0.94%   |
| Apple MacBookAir5      | 2         | 0.94%   |
| Valve Jupiter          | 1         | 0.47%   |
| Toshiba PORTEGE        | 1         | 0.47%   |
| Toshiba dynabook       | 1         | 0.47%   |
| Timi TM1613            | 1         | 0.47%   |
| Timi TM1607            | 1         | 0.47%   |
| Sony VPCCB17FG         | 1         | 0.47%   |
| Schenker XMG           | 1         | 0.47%   |
| Samsung SQ1S           | 1         | 0.47%   |
| Samsung 950XCJ         | 1         | 0.47%   |
| Samsung 930XBE         | 1         | 0.47%   |
| Samsung 905S3G         | 1         | 0.47%   |
| Panasonic CFSZ5-2L     | 1         | 0.47%   |
| ONE-NETBOOK ONEXPLAYER | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 32        | 15.09%  |
| 2018    | 31        | 14.62%  |
| 2021    | 24        | 11.32%  |
| 2019    | 19        | 8.96%   |
| 2022    | 18        | 8.49%   |
| 2017    | 12        | 5.66%   |
| 2011    | 11        | 5.19%   |
| 2014    | 10        | 4.72%   |
| 2012    | 10        | 4.72%   |
| 2010    | 7         | 3.3%    |
| 2015    | 6         | 2.83%   |
| 2023    | 5         | 2.36%   |
| 2016    | 5         | 2.36%   |
| 2013    | 5         | 2.36%   |
| 2008    | 5         | 2.36%   |
| 2007    | 5         | 2.36%   |
| 2009    | 2         | 0.94%   |
| 1999    | 2         | 0.94%   |
| 2005    | 1         | 0.47%   |
| 2003    | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 212       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 183       | 86.32%  |
| Enabled  | 29        | 13.68%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 211       | 99.53%  |
| Yes  | 1         | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 46        | 21.6%   |
| 8.01-16.0   | 45        | 21.13%  |
| 4.01-8.0    | 44        | 20.66%  |
| 32.01-64.0  | 27        | 12.68%  |
| 3.01-4.0    | 21        | 9.86%   |
| 64.01-256.0 | 7         | 3.29%   |
| 24.01-32.0  | 6         | 2.82%   |
| 2.01-3.0    | 5         | 2.35%   |
| 1.01-2.0    | 5         | 2.35%   |
| 0.51-1.0    | 5         | 2.35%   |
| 0.01-0.5    | 2         | 0.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 52        | 22.91%  |
| 2.01-3.0   | 50        | 22.03%  |
| 4.01-8.0   | 41        | 18.06%  |
| 3.01-4.0   | 40        | 17.62%  |
| 8.01-16.0  | 19        | 8.37%   |
| 0.01-0.5   | 15        | 6.61%   |
| 16.01-24.0 | 5         | 2.2%    |
| 0.51-1.0   | 4         | 1.76%   |
| 24.01-32.0 | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 132       | 60%     |
| 2      | 73        | 33.18%  |
| 3      | 11        | 5%      |
| 0      | 3         | 1.36%   |
| 5      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 180       | 84.11%  |
| Yes       | 34        | 15.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 68.84%  |
| No        | 67        | 31.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 210       | 99.06%  |
| No        | 2         | 0.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 170       | 79.44%  |
| No        | 44        | 20.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Hong Kong | 212       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Central           | 121       | 54.5%   |
| Wanchai           | 11        | 4.95%   |
| Kowloon           | 11        | 4.95%   |
| Shatin            | 10        | 4.5%    |
| Tseung Kwan O     | 6         | 2.7%    |
| Tung Chung        | 5         | 2.25%   |
| Hong Kong         | 5         | 2.25%   |
| Tuen Mun          | 4         | 1.8%    |
| Tai Po            | 4         | 1.8%    |
| Hung Hom          | 4         | 1.8%    |
| Tsuen Wan         | 3         | 1.35%   |
| Sai Kung          | 3         | 1.35%   |
| Mong Kok          | 3         | 1.35%   |
| Yuen Long San Hui | 2         | 0.9%    |
| Yuen Long         | 2         | 0.9%    |
| Ngau Wu Tok       | 2         | 0.9%    |
| Man Kok           | 2         | 0.9%    |
| Fanling           | 2         | 0.9%    |
| Discovery Bay     | 2         | 0.9%    |
| Yau Tsim Mong     | 1         | 0.45%   |
| Wong Tai Sin      | 1         | 0.45%   |
| Tuen Mun San Hui  | 1         | 0.45%   |
| Tsimshatsui       | 1         | 0.45%   |
| To Kwa Wan        | 1         | 0.45%   |
| Tin Shui Wai      | 1         | 0.45%   |
| Tai Wan To        | 1         | 0.45%   |
| Tai Wan           | 1         | 0.45%   |
| So Kon Po         | 1         | 0.45%   |
| Sheung Shui       | 1         | 0.45%   |
| Shau Kei Wan      | 1         | 0.45%   |
| Quarry Bay        | 1         | 0.45%   |
| North Point       | 1         | 0.45%   |
| North             | 1         | 0.45%   |
| Lam Tin           | 1         | 0.45%   |
| Kwun Hang         | 1         | 0.45%   |
| Kwai Chung        | 1         | 0.45%   |
| Ho Man Tin        | 1         | 0.45%   |
| Causeway Bay      | 1         | 0.45%   |
| Unknown           | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 62        | 73     | 21.6%   |
| WDC                         | 29        | 32     | 10.1%   |
| Sandisk                     | 19        | 22     | 6.62%   |
| Unknown                     | 18        | 22     | 6.27%   |
| Seagate                     | 15        | 17     | 5.23%   |
| Intel                       | 14        | 18     | 4.88%   |
| SK hynix                    | 11        | 13     | 3.83%   |
| Micron Technology           | 9         | 10     | 3.14%   |
| Hitachi                     | 9         | 9      | 3.14%   |
| Kingston                    | 8         | 9      | 2.79%   |
| Toshiba                     | 7         | 7      | 2.44%   |
| Crucial                     | 6         | 14     | 2.09%   |
| Apple                       | 6         | 18     | 2.09%   |
| KIOXIA                      | 5         | 5      | 1.74%   |
| HGST                        | 5         | 6      | 1.74%   |
| Fujitsu                     | 4         | 6      | 1.39%   |
| Phison                      | 3         | 3      | 1.05%   |
| JMicron Technology          | 3         | 4      | 1.05%   |
| China                       | 3         | 4      | 1.05%   |
| BIWIN                       | 3         | 3      | 1.05%   |
| ZHITAI                      | 2         | 2      | 0.7%    |
| Yangtze Memory Technologies | 2         | 2      | 0.7%    |
| Transcend                   | 2         | 2      | 0.7%    |
| TO Exter                    | 2         | 2      | 0.7%    |
| Plextor                     | 2         | 3      | 0.7%    |
| LITEON                      | 2         | 2      | 0.7%    |
| KingSpec                    | 2         | 3      | 0.7%    |
| HS-SSD-C100                 | 2         | 3      | 0.7%    |
| Hikvision                   | 2         | 2      | 0.7%    |
| ZX1 1TB                     | 1         | 1      | 0.35%   |
| Yangtze Memory              | 1         | 1      | 0.35%   |
| Verbatim                    | 1         | 2      | 0.35%   |
| USB3.0                      | 1         | 1      | 0.35%   |
| Unknown (CF)                | 1         | 1      | 0.35%   |
| Team                        | 1         | 1      | 0.35%   |
| SSSTC                       | 1         | 1      | 0.35%   |
| SPCC                        | 1         | 1      | 0.35%   |
| Silicon Motion              | 1         | 1      | 0.35%   |
| ShineDisk                   | 1         | 1      | 0.35%   |
| ShiJi                       | 1         | 3      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 6         | 2%      |
| Unknown MMC Card  64GB                                | 5         | 1.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 5         | 1.67%   |
| Seagate ST1000LM035-1RK172 1TB                        | 4         | 1.33%   |
| WDC WDS100T2B0C-00PXH0 1TB                            | 3         | 1%      |
| Seagate ST2000LM007-1R8174 2TB                        | 3         | 1%      |
| SanDisk NVMe SSD Drive 512GB                          | 3         | 1%      |
| Samsung SSD 980 1TB                                   | 3         | 1%      |
| Samsung NVMe SSD Drive 512GB                          | 3         | 1%      |
| Samsung MZVL2512HCJQ-00BL2 512GB                      | 3         | 1%      |
| WDC WDS240G2G0B-00EPW0 240GB SSD                      | 2         | 0.67%   |
| WDC WD10SPZX-22Z10T1 1TB                              | 2         | 0.67%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB                  | 2         | 0.67%   |
| Unknown MMC Card  128GB                               | 2         | 0.67%   |
| Toshiba MQ01ABF050 500GB                              | 2         | 0.67%   |
| TO Exter nal USB 3.0 2TB                              | 2         | 0.67%   |
| SK hynix BC501 NVMe 128GB                             | 2         | 0.67%   |
| Seagate ST500LT012-9WS142 500GB                       | 2         | 0.67%   |
| SanDisk NVMe SSD Drive 2TB                            | 2         | 0.67%   |
| SanDisk NVMe SSD Drive 256GB                          | 2         | 0.67%   |
| SanDisk NVMe SSD Drive 1TB                            | 2         | 0.67%   |
| Samsung SSD 970 EVO Plus 2TB                          | 2         | 0.67%   |
| Samsung NVMe SSD Drive 1TB                            | 2         | 0.67%   |
| Samsung MZVLB512HBJQ-000L7 512GB                      | 2         | 0.67%   |
| Samsung MZVLB512HBJQ-000L2 512GB                      | 2         | 0.67%   |
| Samsung MZVL2512HCJQ-00BL7 512GB                      | 2         | 0.67%   |
| Plextor PX-128M7VC 128GB SSD                          | 2         | 0.67%   |
| LITEON CV8-8E128-HP 128GB SSD                         | 2         | 0.67%   |
| KIOXIA NVMe SSD Drive 512GB                           | 2         | 0.67%   |
| JMicron Generic 1TB                                   | 2         | 0.67%   |
| Intel SSDPEKNW512G8 512GB                             | 2         | 0.67%   |
| Intel NVMe SSD Drive 512GB                            | 2         | 0.67%   |
| Fujitsu F300 480GB                                    | 2         | 0.67%   |
| Crucial CT500MX500SSD1 500GB                          | 2         | 0.67%   |
| Crucial CT1000MX500SSD1 1TB                           | 2         | 0.67%   |
| BIWIN SSD 512GB                                       | 2         | 0.67%   |
| Apple SSD TS128E 121GB                                | 2         | 0.67%   |
| ZX1 1TB Disk 1TB                                      | 1         | 0.33%   |
| ZHITAI TiPlus7100 2TB                                 | 1         | 0.33%   |
| ZHITAI TiPlus7100 1TB                                 | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 29.41%  |
| WDC                 | 14        | 14     | 27.45%  |
| Hitachi             | 9         | 9      | 17.65%  |
| HGST                | 5         | 6      | 9.8%    |
| Toshiba             | 3         | 3      | 5.88%   |
| USB3.0              | 1         | 1      | 1.96%   |
| Samsung Electronics | 1         | 1      | 1.96%   |
| JMicron Technology  | 1         | 2      | 1.96%   |
| Fujitsu             | 1         | 1      | 1.96%   |
| External            | 1         | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 20     | 21.92%  |
| Crucial             | 6         | 14     | 8.22%   |
| WDC                 | 5         | 5      | 6.85%   |
| Intel               | 5         | 8      | 6.85%   |
| Kingston            | 4         | 4      | 5.48%   |
| China               | 3         | 4      | 4.11%   |
| Apple               | 3         | 3      | 4.11%   |
| Transcend           | 2         | 2      | 2.74%   |
| TO Exter            | 2         | 2      | 2.74%   |
| SanDisk             | 2         | 2      | 2.74%   |
| Plextor             | 2         | 3      | 2.74%   |
| LITEON              | 2         | 2      | 2.74%   |
| JMicron Technology  | 2         | 2      | 2.74%   |
| Fujitsu             | 2         | 4      | 2.74%   |
| Verbatim            | 1         | 2      | 1.37%   |
| Unknown (CF)        | 1         | 1      | 1.37%   |
| Team                | 1         | 1      | 1.37%   |
| SK hynix            | 1         | 1      | 1.37%   |
| ShiJi               | 1         | 3      | 1.37%   |
| RECADATA            | 1         | 1      | 1.37%   |
| Ramsta              | 1         | 1      | 1.37%   |
| Netac               | 1         | 1      | 1.37%   |
| Micron Technology   | 1         | 2      | 1.37%   |
| Lexar               | 1         | 1      | 1.37%   |
| KLEVV               | 1         | 1      | 1.37%   |
| HS-SSD-C100         | 1         | 1      | 1.37%   |
| Hikvision           | 1         | 1      | 1.37%   |
| DGM                 | 1         | 1      | 1.37%   |
| BIWIN               | 1         | 1      | 1.37%   |
| Apacer              | 1         | 4      | 1.37%   |
| A-DATA Technology   | 1         | 1      | 1.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 120       | 165    | 45.63%  |
| SSD     | 65        | 99     | 24.71%  |
| HDD     | 51        | 55     | 19.39%  |
| MMC     | 17        | 21     | 6.46%   |
| Unknown | 10        | 12     | 3.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 120       | 163    | 46.88%  |
| SATA | 101       | 148    | 39.45%  |
| SAS  | 18        | 20     | 7.03%   |
| MMC  | 17        | 21     | 6.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 74        | 105    | 63.25%  |
| 0.51-1.0   | 33        | 38     | 28.21%  |
| 1.01-2.0   | 9         | 10     | 7.69%   |
| 4.01-10.0  | 1         | 1      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 56        | 25%     |
| 251-500        | 49        | 21.88%  |
| 501-1000       | 34        | 15.18%  |
| 1-20           | 25        | 11.16%  |
| 1001-2000      | 21        | 9.38%   |
| 51-100         | 17        | 7.59%   |
| 21-50          | 8         | 3.57%   |
| 2001-3000      | 7         | 3.13%   |
| More than 3000 | 5         | 2.23%   |
| Unknown        | 2         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 93        | 40.61%  |
| 251-500   | 30        | 13.1%   |
| 21-50     | 30        | 13.1%   |
| 51-100    | 29        | 12.66%  |
| 101-250   | 28        | 12.23%  |
| 501-1000  | 10        | 4.37%   |
| 1001-2000 | 7         | 3.06%   |
| Unknown   | 2         | 0.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| LITEON CV8-8E128-HP 128GB SSD         | 2         | 2      | 14.29%  |
| Seagate ST9500325AS 500GB             | 1         | 1      | 7.14%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 7.14%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 860 EVO 1TB   | 1         | 1      | 7.14%   |
| Hitachi HTS725050A7E630 500GB         | 1         | 1      | 7.14%   |
| Hitachi HTS723216L9A360 160GB         | 1         | 1      | 7.14%   |
| Hitachi HTC426040G8CE00 40GB          | 1         | 1      | 7.14%   |
| HGST TOURO Mobile 1TB                 | 1         | 1      | 7.14%   |
| DGM SSD 120GB S3-120A                 | 1         | 1      | 7.14%   |
| Crucial CT240M500SSD1 240GB           | 1         | 1      | 7.14%   |
| BIWIN SSD 32GB                        | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 3         | 3      | 21.43%  |
| Seagate             | 2         | 2      | 14.29%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| LITEON              | 2         | 2      | 14.29%  |
| SanDisk             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |
| DGM                 | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |
| BIWIN               | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 50%     |
| Seagate | 2         | 2      | 33.33%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 8         | 8      | 57.14%  |
| HDD  | 6         | 6      | 42.86%  |

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
| Works    | 119       | 181    | 51.97%  |
| Detected | 96        | 157    | 41.92%  |
| Malfunc  | 14        | 14     | 6.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 127       | 46.69%  |
| Samsung Electronics            | 50        | 18.38%  |
| SanDisk                        | 27        | 9.93%   |
| AMD                            | 14        | 5.15%   |
| SK hynix                       | 10        | 3.68%   |
| Micron Technology              | 8         | 2.94%   |
| Toshiba America Info Systems   | 6         | 2.21%   |
| Yangtze Memory Technologies    | 4         | 1.47%   |
| Silicon Motion                 | 4         | 1.47%   |
| Phison Electronics             | 4         | 1.47%   |
| Kingston Technology Company    | 4         | 1.47%   |
| KIOXIA                         | 3         | 1.1%    |
| Biwin Storage Technology       | 2         | 0.74%   |
| Apple                          | 2         | 0.74%   |
| VIA Technologies               | 1         | 0.37%   |
| Solid State Storage Technology | 1         | 0.37%   |
| Realtek Semiconductor          | 1         | 0.37%   |
| Nvidia                         | 1         | 0.37%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.37%   |
| Lenovo                         | 1         | 0.37%   |
| INNOGRIT                       | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 23        | 7.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 15        | 5.21%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 4.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 3.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 3.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 3.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 3.47%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 2.43%   |
| Samsung NVMe SSD Controller 980                                                | 7         | 2.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 2.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 2.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 2.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.74%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 5         | 1.74%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 5         | 1.74%   |
| Intel SSD 660P Series                                                          | 5         | 1.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 1.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 1.74%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 1.39%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 1.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.39%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 3         | 1.04%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.04%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 1.04%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 3         | 1.04%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 1.04%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 1.04%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.69%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 2         | 0.69%   |
| SanDisk WD Green SN350 NVMe SSD 1 TB (DRAM-less)                               | 2         | 0.69%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.69%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.69%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 0.69%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 0.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.69%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 121       | 46.18%  |
| SATA | 107       | 40.84%  |
| IDE  | 18        | 6.87%   |
| RAID | 16        | 6.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 170       | 80.19%  |
| AMD          | 40        | 18.87%  |
| GenuineTMx86 | 1         | 0.47%   |
| Unknown      | 1         | 0.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 3.3%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 2.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 2.36%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 5         | 2.36%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 1.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.89%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.89%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.89%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 1.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.89%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 4         | 1.89%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 3         | 1.42%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.42%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.42%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.42%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.42%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.42%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 3         | 1.42%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.42%   |
| AMD Ryzen 7 6800U with Radeon Graphics        | 3         | 1.42%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 1.42%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.42%   |
| Intel Genuine processor 800MHz                | 2         | 0.94%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.94%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.94%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 0.94%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.94%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.94%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.94%   |
| Intel Celeron N4000C CPU @ 1.10GHz            | 2         | 0.94%   |
| Intel Celeron (Mendocino)                     | 2         | 0.94%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 2         | 0.94%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 0.94%   |
| Intel 13th Gen Core i9-13900HX                | 2         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 48        | 22.64%  |
| Intel Core i7           | 46        | 21.7%   |
| Other                   | 29        | 13.68%  |
| AMD Ryzen 7             | 19        | 8.96%   |
| Intel Celeron           | 17        | 8.02%   |
| Intel Core i3           | 11        | 5.19%   |
| AMD Ryzen 5             | 9         | 4.25%   |
| AMD Ryzen 9             | 8         | 3.77%   |
| Intel Atom              | 5         | 2.36%   |
| Intel Core 2 Duo        | 4         | 1.89%   |
| Intel Core m3           | 3         | 1.42%   |
| Intel Xeon              | 2         | 0.94%   |
| Intel Pentium Dual-Core | 2         | 0.94%   |
| Intel Genuine           | 2         | 0.94%   |
| AMD Ryzen 7 PRO         | 2         | 0.94%   |
| Intel Pentium M         | 1         | 0.47%   |
| Intel Pentium Gold      | 1         | 0.47%   |
| Intel Pentium Dual      | 1         | 0.47%   |
| Intel Core 2            | 1         | 0.47%   |
| AMD Quad-Core           | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 74        | 34.91%  |
| 4      | 67        | 31.6%   |
| 8      | 30        | 14.15%  |
| 6      | 17        | 8.02%   |
| 1      | 10        | 4.72%   |
| 14     | 5         | 2.36%   |
| 12     | 5         | 2.36%   |
| 24     | 2         | 0.94%   |
| 16     | 2         | 0.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 212       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 173       | 81.22%  |
| 1      | 40        | 18.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 196       | 92.45%  |
| 32-bit         | 10        | 4.72%   |
| Unknown        | 5         | 2.36%   |
| 64-bit         | 1         | 0.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 26.27%  |
| 0x806ea    | 10        | 4.61%   |
| 0x806e9    | 10        | 4.61%   |
| 0x206a7    | 10        | 4.61%   |
| 0x906ea    | 9         | 4.15%   |
| 0x806ec    | 6         | 2.76%   |
| 0x806c1    | 6         | 2.76%   |
| 0x406e3    | 6         | 2.76%   |
| 0x306a9    | 6         | 2.76%   |
| 0x806eb    | 5         | 2.3%    |
| 0x706e5    | 5         | 2.3%    |
| 0x506c9    | 5         | 2.3%    |
| 0x40651    | 5         | 2.3%    |
| 0x0a50000c | 5         | 2.3%    |
| 0x0a404102 | 5         | 2.3%    |
| 0x08600106 | 5         | 2.3%    |
| 0xa0652    | 4         | 1.84%   |
| 0x106c2    | 4         | 1.84%   |
| 0x906a3    | 3         | 1.38%   |
| 0x706a8    | 3         | 1.38%   |
| 0x306c3    | 3         | 1.38%   |
| 0x20655    | 3         | 1.38%   |
| 0x1067a    | 3         | 1.38%   |
| 0x08600104 | 3         | 1.38%   |
| 0x08108102 | 3         | 1.38%   |
| 0xb0671    | 2         | 0.92%   |
| 0x906e9    | 2         | 0.92%   |
| 0x806d1    | 2         | 0.92%   |
| 0x6fd      | 2         | 0.92%   |
| 0x6d8      | 2         | 0.92%   |
| 0x66a      | 2         | 0.92%   |
| 0x506e3    | 2         | 0.92%   |
| 0x306d4    | 2         | 0.92%   |
| 0x0a601203 | 2         | 0.92%   |
| 0x0a50000b | 2         | 0.92%   |
| 0x08600103 | 2         | 0.92%   |
| 0x706a1    | 1         | 0.46%   |
| 0x6fb      | 1         | 0.46%   |
| 0x6f6      | 1         | 0.46%   |
| 0x6d6      | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 50        | 23.58%  |
| Unknown          | 20        | 9.43%   |
| Zen 2            | 13        | 6.13%   |
| TigerLake        | 13        | 6.13%   |
| SandyBridge      | 13        | 6.13%   |
| Zen 3            | 11        | 5.19%   |
| Haswell          | 11        | 5.19%   |
| Skylake          | 10        | 4.72%   |
| IvyBridge        | 10        | 4.72%   |
| Icelake          | 9         | 4.25%   |
| Goldmont plus    | 6         | 2.83%   |
| Alderlake Hybrid | 6         | 2.83%   |
| Westmere         | 5         | 2.36%   |
| Goldmont         | 5         | 2.36%   |
| CometLake        | 5         | 2.36%   |
| Zen+             | 4         | 1.89%   |
| Penryn           | 4         | 1.89%   |
| Core             | 4         | 1.89%   |
| Bonnell          | 4         | 1.89%   |
| P6               | 3         | 1.42%   |
| Broadwell        | 3         | 1.42%   |
| Silvermont       | 2         | 0.94%   |
| Jaguar           | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 160       | 56.94%  |
| Nvidia      | 73        | 25.98%  |
| AMD         | 45        | 16.01%  |
| Neomagic    | 2         | 0.71%   |
| S3 Graphics | 1         | 0.36%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                        | 13        | 4.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13        | 4.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 11        | 3.79%   |
| AMD Renoir                                                                    | 10        | 3.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 10        | 3.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 9         | 3.1%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 9         | 3.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 8         | 2.76%   |
| AMD Rembrandt [Radeon 680M]                                                   | 8         | 2.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 2.41%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 7         | 2.41%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 6         | 2.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 6         | 2.07%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 6         | 2.07%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 1.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 5         | 1.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 5         | 1.72%   |
| Intel HD Graphics 620                                                         | 5         | 1.72%   |
| Intel HD Graphics 500                                                         | 5         | 1.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 5         | 1.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 4         | 1.38%   |
| Intel HD Graphics 615                                                         | 4         | 1.38%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 1.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 1.38%   |
| Nvidia TU117M [GeForce MX450]                                                 | 3         | 1.03%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 3         | 1.03%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 3         | 1.03%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                               | 3         | 1.03%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 3         | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 1.03%   |
| Intel HD Graphics 5500                                                        | 3         | 1.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.69%   |
| Nvidia TU117M                                                                 | 2         | 0.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 0.69%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 0.69%   |
| Nvidia GP108BM [GeForce MX250]                                                | 2         | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 2         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 106       | 49.77%  |
| Intel + Nvidia  | 48        | 22.54%  |
| 1 x AMD         | 22        | 10.33%  |
| AMD + Nvidia    | 14        | 6.57%   |
| 1 x Nvidia      | 10        | 4.69%   |
| Intel + AMD     | 7         | 3.29%   |
| 2 x AMD         | 2         | 0.94%   |
| 1 x Neomagic    | 2         | 0.94%   |
| Other           | 1         | 0.47%   |
| 1 x S3 Graphics | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 163       | 76.89%  |
| Proprietary | 41        | 19.34%  |
| Unknown     | 8         | 3.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 141       | 66.2%   |
| 1.01-2.0   | 20        | 9.39%   |
| 0.01-0.5   | 20        | 9.39%   |
| 7.01-8.0   | 8         | 3.76%   |
| 5.01-6.0   | 8         | 3.76%   |
| 3.01-4.0   | 8         | 3.76%   |
| 0.51-1.0   | 7         | 3.29%   |
| 2.01-3.0   | 1         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 48        | 20.6%   |
| AU Optronics            | 39        | 16.74%  |
| LG Display              | 28        | 12.02%  |
| Chimei Innolux          | 22        | 9.44%   |
| Samsung Electronics     | 13        | 5.58%   |
| Sharp                   | 12        | 5.15%   |
| Dell                    | 8         | 3.43%   |
| AOC                     | 8         | 3.43%   |
| Apple                   | 6         | 2.58%   |
| Philips                 | 4         | 1.72%   |
| Lenovo                  | 4         | 1.72%   |
| JDI                     | 4         | 1.72%   |
| InfoVision              | 3         | 1.29%   |
| CSO                     | 3         | 1.29%   |
| TMX                     | 2         | 0.86%   |
| PANDA                   | 2         | 0.86%   |
| Mi                      | 2         | 0.86%   |
| LG Philips              | 2         | 0.86%   |
| CPT                     | 2         | 0.86%   |
| Chi Mei Optoelectronics | 2         | 0.86%   |
| Valve                   | 1         | 0.43%   |
| Unknown (DAE)           | 1         | 0.43%   |
| TUO                     | 1         | 0.43%   |
| Sony                    | 1         | 0.43%   |
| SAC                     | 1         | 0.43%   |
| RGT                     | 1         | 0.43%   |
| MStar                   | 1         | 0.43%   |
| Lenovo Group Limited    | 1         | 0.43%   |
| JXC                     | 1         | 0.43%   |
| ITE                     | 1         | 0.43%   |
| IPS                     | 1         | 0.43%   |
| Intehill                | 1         | 0.43%   |
| InnoLux Display         | 1         | 0.43%   |
| Hewlett-Packard         | 1         | 0.43%   |
| Goldstar                | 1         | 0.43%   |
| BenQ                    | 1         | 0.43%   |
| ASUSTek Computer        | 1         | 0.43%   |
| Ancor Communications    | 1         | 0.43%   |
| Acer                    | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                | 4         | 1.69%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 3         | 1.27%   |
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                | 3         | 1.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 1.27%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch       | 3         | 1.27%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch              | 2         | 0.85%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch | 2         | 0.85%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch         | 2         | 0.85%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch          | 2         | 0.85%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 2         | 0.85%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                | 2         | 0.85%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                   | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 2         | 0.85%   |
| BOE LCD Monitor BOE0B7D 2560x1440 355x200mm 16.0-inch                | 2         | 0.85%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                | 2         | 0.85%   |
| AU Optronics LCD Monitor AUOC391 2880x1800 301x188mm 14.0-inch       | 2         | 0.85%   |
| AU Optronics LCD Monitor AUOA195 2240x1400 300x188mm 13.9-inch       | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO233D 1920x1080 309x174mm 14.0-inch       | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch       | 2         | 0.85%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 2         | 0.85%   |
| AOC Q2790 AOC2790 2560x1440 597x336mm 27.0-inch                      | 2         | 0.85%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 1         | 0.42%   |
| Unknown (DAE) L32S6550BN DAE0010 1366x768 698x392mm 31.5-inch        | 1         | 0.42%   |
| TUO 240RS TUO2400 1920x1080 408x255mm 18.9-inch                      | 1         | 0.42%   |
| TMX TL156MDMP01-1 TMX1560 3200x2000 336x210mm 15.6-inch              | 1         | 0.42%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 1         | 0.42%   |
| Sony BW8 MS_9001 2560x1600                                           | 1         | 0.42%   |
| Sharp LQ133M1JW48 SHP14F5 1920x1080 294x165mm 13.3-inch              | 1         | 0.42%   |
| Sharp LQ133M1JW35 SHP14B0 1920x1080 294x165mm 13.3-inch              | 1         | 0.42%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch              | 1         | 0.42%   |
| Sharp LQ123P1JX32 SHP148A 2400x1600 259x173mm 12.3-inch              | 1         | 0.42%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch              | 1         | 0.42%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch              | 1         | 0.42%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 1         | 0.42%   |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch              | 1         | 0.42%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch              | 1         | 0.42%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch              | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM0613 1920x1080                     | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 1         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 102       | 46.36%  |
| 1366x768 (WXGA)   | 29        | 13.18%  |
| 3840x2160 (4K)    | 14        | 6.36%   |
| 2560x1440 (QHD)   | 12        | 5.45%   |
| 2560x1600         | 11        | 5%      |
| 1600x900 (HD+)    | 7         | 3.18%   |
| 1280x800 (WXGA)   | 6         | 2.73%   |
| 3840x2400         | 4         | 1.82%   |
| 2880x1800         | 4         | 1.82%   |
| 1440x900 (WXGA+)  | 4         | 1.82%   |
| 3000x2000         | 3         | 1.36%   |
| 2240x1400         | 3         | 1.36%   |
| 3440x1440         | 2         | 0.91%   |
| 1920x1200 (WUXGA) | 2         | 0.91%   |
| 800x1280          | 1         | 0.45%   |
| 3840x1600         | 1         | 0.45%   |
| 3840x1100         | 1         | 0.45%   |
| 3520x1080         | 1         | 0.45%   |
| 3456x2160         | 1         | 0.45%   |
| 3200x2000         | 1         | 0.45%   |
| 3200x1800 (QHD+)  | 1         | 0.45%   |
| 2880x1920         | 1         | 0.45%   |
| 2880x1620         | 1         | 0.45%   |
| 2400x1600         | 1         | 0.45%   |
| 2304x1440         | 1         | 0.45%   |
| 2256x1504         | 1         | 0.45%   |
| 2160x1440         | 1         | 0.45%   |
| 1600x2560         | 1         | 0.45%   |
| 1024x600          | 1         | 0.45%   |
| 1024x576          | 1         | 0.45%   |
| Unknown           | 1         | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 65        | 27.9%   |
| 13      | 45        | 19.31%  |
| 14      | 38        | 16.31%  |
| 12      | 14        | 6.01%   |
| 16      | 11        | 4.72%   |
| 27      | 7         | 3%      |
| 24      | 7         | 3%      |
| 21      | 7         | 3%      |
| 17      | 7         | 3%      |
| 23      | 6         | 2.58%   |
| 31      | 4         | 1.72%   |
| 40      | 3         | 1.29%   |
| 10      | 3         | 1.29%   |
| 34      | 2         | 0.86%   |
| 19      | 2         | 0.86%   |
| 8       | 2         | 0.86%   |
| Unknown | 2         | 0.86%   |
| 72      | 1         | 0.43%   |
| 52      | 1         | 0.43%   |
| 43      | 1         | 0.43%   |
| 37      | 1         | 0.43%   |
| 26      | 1         | 0.43%   |
| 18      | 1         | 0.43%   |
| 11      | 1         | 0.43%   |
| 7       | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 125       | 54.11%  |
| 201-300     | 47        | 20.35%  |
| 501-600     | 21        | 9.09%   |
| 351-400     | 11        | 4.76%   |
| 401-500     | 9         | 3.9%    |
| 801-900     | 4         | 1.73%   |
| 601-700     | 4         | 1.73%   |
| 701-800     | 2         | 0.87%   |
| 101-200     | 2         | 0.87%   |
| Unknown     | 2         | 0.87%   |
| 1501-2000   | 1         | 0.43%   |
| 1001-1500   | 1         | 0.43%   |
| 901-1000    | 1         | 0.43%   |
| 1-100       | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 160       | 76.19%  |
| 16/10   | 34        | 16.19%  |
| 3/2     | 8         | 3.81%   |
| 21/9    | 3         | 1.43%   |
| 0.62    | 2         | 0.95%   |
| 3.40    | 1         | 0.48%   |
| 0.67    | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 28.63%  |
| 81-90          | 63        | 26.92%  |
| 71-80          | 20        | 8.55%   |
| 201-250        | 16        | 6.84%   |
| 61-70          | 13        | 5.56%   |
| 301-350        | 8         | 3.42%   |
| 111-120        | 8         | 3.42%   |
| 351-500        | 7         | 2.99%   |
| 121-130        | 7         | 2.99%   |
| 151-200        | 5         | 2.14%   |
| 501-1000       | 4         | 1.71%   |
| 41-50          | 3         | 1.28%   |
| 1-40           | 3         | 1.28%   |
| More than 1000 | 2         | 0.85%   |
| 51-60          | 2         | 0.85%   |
| 251-300        | 2         | 0.85%   |
| 91-100         | 2         | 0.85%   |
| Unknown        | 2         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 99        | 44%     |
| 161-240       | 39        | 17.33%  |
| 101-120       | 38        | 16.89%  |
| More than 240 | 22        | 9.78%   |
| 51-100        | 21        | 9.33%   |
| 1-50          | 4         | 1.78%   |
| Unknown       | 2         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 166       | 76.15%  |
| 2     | 41        | 18.81%  |
| 0     | 9         | 4.13%   |
| 3     | 2         | 0.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 128       | 40%     |
| Realtek Semiconductor      | 94        | 29.38%  |
| Qualcomm Atheros           | 34        | 10.63%  |
| Broadcom                   | 15        | 4.69%   |
| MediaTek                   | 13        | 4.06%   |
| ASIX Electronics           | 7         | 2.19%   |
| Ralink Technology          | 4         | 1.25%   |
| Broadcom Limited           | 4         | 1.25%   |
| Qualcomm                   | 3         | 0.94%   |
| Marvell Technology Group   | 3         | 0.94%   |
| TP-Link                    | 2         | 0.63%   |
| Lenovo                     | 2         | 0.63%   |
| Xiaomi                     | 1         | 0.31%   |
| Texas Instruments          | 1         | 0.31%   |
| SEGGER                     | 1         | 0.31%   |
| Ralink                     | 1         | 0.31%   |
| Quectel Wireless Solutions | 1         | 0.31%   |
| OPPO Electronics           | 1         | 0.31%   |
| NetGear                    | 1         | 0.31%   |
| Huawei Technologies        | 1         | 0.31%   |
| Fitbit                     | 1         | 0.31%   |
| DisplayLink                | 1         | 0.31%   |
| Apple                      | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 52        | 13.54%  |
| Intel Wi-Fi 6 AX200                                                     | 17        | 4.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 16        | 4.17%   |
| Intel Wireless 8265 / 8275                                              | 13        | 3.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 2.34%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 2.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 7         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1.82%   |
| Intel Wireless 8260                                                     | 7         | 1.82%   |
| Intel Ethernet Connection (4) I219-V                                    | 7         | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 1.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 1.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.3%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.3%    |
| Intel Wireless 7265                                                     | 5         | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.3%    |
| ASIX AX88179 Gigabit Ethernet                                           | 5         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.04%   |
| Intel Wireless 7260                                                     | 4         | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.04%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.78%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.78%   |
| Intel 82579V Gigabit Network Connection                                 | 3         | 0.78%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.52%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 121       | 55%     |
| Qualcomm Atheros           | 30        | 13.64%  |
| Realtek Semiconductor      | 28        | 12.73%  |
| MediaTek                   | 13        | 5.91%   |
| Broadcom                   | 13        | 5.91%   |
| Ralink Technology          | 4         | 1.82%   |
| Qualcomm                   | 3         | 1.36%   |
| TP-Link                    | 2         | 0.91%   |
| Broadcom Limited           | 2         | 0.91%   |
| Texas Instruments          | 1         | 0.45%   |
| Ralink                     | 1         | 0.45%   |
| Quectel Wireless Solutions | 1         | 0.45%   |
| NetGear                    | 1         | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 17        | 7.69%   |
| Intel Wireless 8265 / 8275                                              | 13        | 5.88%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 3.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 3.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 3.62%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 7         | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 3.17%   |
| Intel Wireless 8260                                                     | 7         | 3.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 2.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 2.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.26%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.26%   |
| Intel Wireless 7265                                                     | 5         | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 2.26%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 2.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.81%   |
| Intel Wireless 7260                                                     | 4         | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.36%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1.36%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.36%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.36%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.9%    |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 2         | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.9%    |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.9%    |
| Intel Raptor Lake PCH CNVi WiFi                                         | 2         | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.9%    |
| Intel 700 Series Chipset Family Wi-Fi                                   | 2         | 0.9%    |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 2         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 81        | 51.59%  |
| Intel                    | 46        | 29.3%   |
| Qualcomm Atheros         | 8         | 5.1%    |
| ASIX Electronics         | 7         | 4.46%   |
| Marvell Technology Group | 3         | 1.91%   |
| Broadcom                 | 3         | 1.91%   |
| Lenovo                   | 2         | 1.27%   |
| Broadcom Limited         | 2         | 1.27%   |
| Xiaomi                   | 1         | 0.64%   |
| OPPO Electronics         | 1         | 0.64%   |
| Huawei Technologies      | 1         | 0.64%   |
| DisplayLink              | 1         | 0.64%   |
| Apple                    | 1         | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 32.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 10%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 5.63%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 4.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 4.38%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 3.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.5%    |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.5%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.25%   |
| Lenovo Thinkpad LAN                                               | 2         | 1.25%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.25%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.25%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.63%   |
| Realtek USB 10/100 LAN                                            | 1         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.63%   |
| OPPO OnePlus Nord                                                 | 1         | 0.63%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.63%   |
| Lenovo USB-C Hub                                                  | 1         | 0.63%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.63%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 210       | 58.33%  |
| Ethernet | 147       | 40.83%  |
| Modem    | 2         | 0.56%   |
| Unknown  | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 181       | 79.39%  |
| Ethernet | 47        | 20.61%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 124       | 58.49%  |
| 1     | 79        | 37.26%  |
| 0     | 9         | 4.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 208       | 98.11%  |
| Yes  | 4         | 1.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 101       | 59.41%  |
| Foxconn / Hon Hai               | 12        | 7.06%   |
| Realtek Semiconductor           | 8         | 4.71%   |
| Qualcomm Atheros Communications | 8         | 4.71%   |
| IMC Networks                    | 8         | 4.71%   |
| Broadcom                        | 8         | 4.71%   |
| Lite-On Technology              | 4         | 2.35%   |
| Apple                           | 4         | 2.35%   |
| Realtek                         | 3         | 1.76%   |
| Hewlett-Packard                 | 3         | 1.76%   |
| Foxconn International           | 3         | 1.76%   |
| Taiyo Yuden                     | 2         | 1.18%   |
| Dell                            | 2         | 1.18%   |
| MediaTek                        | 1         | 0.59%   |
| Fujitsu                         | 1         | 0.59%   |
| Cambridge Silicon Radio         | 1         | 0.59%   |
| Askey Computer                  | 1         | 0.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 28        | 16.47%  |
| Intel AX201 Bluetooth                               | 23        | 13.53%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 10.59%  |
| Intel AX200 Bluetooth                               | 17        | 10%     |
| Intel Bluetooth Device                              | 10        | 5.88%   |
| Realtek Bluetooth Radio                             | 8         | 4.71%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.35%   |
| Intel AX210 Bluetooth                               | 4         | 2.35%   |
| IMC Networks Wireless_Device                        | 4         | 2.35%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 2.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 2.35%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 1.76%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.76%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 1.76%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.18%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.18%   |
| IMC Networks Bluetooth Device                       | 2         | 1.18%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.18%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 1.18%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.59%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.59%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.59%   |
| MediaTek Wireless_Device                            | 1         | 0.59%   |
| Lite-On Bluetooth Radio                             | 1         | 0.59%   |
| Lite-On Bluetooth Device                            | 1         | 0.59%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.59%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.59%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.59%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.59%   |
| Fujitsu Bluetooth Device                            | 1         | 0.59%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.59%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.59%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.59%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.59%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.59%   |
| Broadcom BCM2045A0                                  | 1         | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 165       | 64.71%  |
| AMD                         | 41        | 16.08%  |
| Nvidia                      | 38        | 14.9%   |
| Generalplus Technology      | 2         | 0.78%   |
| ESS Technology              | 2         | 0.78%   |
| VIA Technologies            | 1         | 0.39%   |
| Logitech                    | 1         | 0.39%   |
| iCreate Technologies        | 1         | 0.39%   |
| HECATE G2 GAMING HEADSET    | 1         | 0.39%   |
| FiiO Electronics Technology | 1         | 0.39%   |
| AudioQuest                  | 1         | 0.39%   |
| Apple                       | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 37        | 12.37%  |
| Intel Sunrise Point-LP HD Audio                                            | 32        | 10.7%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 4.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 13        | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 4.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 3.68%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 10        | 3.34%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 3.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 2.68%   |
| Nvidia Audio device                                                        | 7         | 2.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 2.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 2.01%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 2.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 2.01%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 2.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 2.01%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 2.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.67%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 1.67%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5         | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1%      |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1%      |
| Intel CM238 HD Audio Controller                                            | 3         | 1%      |
| Intel Broadwell-U Audio Controller                                         | 3         | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1%      |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.67%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.67%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 0.67%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 0.67%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 2         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 50        | 29.94%  |
| SK hynix                   | 46        | 27.54%  |
| Micron Technology          | 21        | 12.57%  |
| Unknown                    | 13        | 7.78%   |
| Kingston                   | 8         | 4.79%   |
| Crucial                    | 7         | 4.19%   |
| Unknown                    | 7         | 4.19%   |
| Unknown (ABCD)             | 4         | 2.4%    |
| Elpida                     | 2         | 1.2%    |
| Unknown (08C8)             | 1         | 0.6%    |
| Team                       | 1         | 0.6%    |
| Shenzhen Jinge Information | 1         | 0.6%    |
| Ramaxel Technology         | 1         | 0.6%    |
| Nanya Technology           | 1         | 0.6%    |
| Lenovo                     | 1         | 0.6%    |
| Kingmax                    | 1         | 0.6%    |
| ChangXin Memory            | 1         | 0.6%    |
| A-DATA Technology          | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 7         | 4%      |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 2.29%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 2.29%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.29%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.71%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 3         | 1.71%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2         | 1.14%   |
| Unknown RAM Module 256MB SODIMM DRAM                             | 2         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 1.14%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                     | 2         | 1.14%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.14%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 1.14%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.14%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 1.14%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.14%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 2         | 1.14%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.14%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.14%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.14%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.14%   |
| Crucial RAM CT16G4SFS832A.C8FB 16GB SODIMM DDR4 3200MT/s         | 2         | 1.14%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.57%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.57%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2 333MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 0.57%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.57%   |
| Unknown (08C8) RAM Module 16GB SODIMM DDR4 2400MT/s              | 1         | 0.57%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.57%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.57%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                       | 1         | 0.57%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 60        | 42.55%  |
| DDR3    | 22        | 15.6%   |
| LPDDR4  | 16        | 11.35%  |
| LPDDR3  | 13        | 9.22%   |
| DDR5    | 8         | 5.67%   |
| DDR2    | 8         | 5.67%   |
| LPDDR5  | 6         | 4.26%   |
| DRAM    | 3         | 2.13%   |
| SDRAM   | 2         | 1.42%   |
| Unknown | 2         | 1.42%   |
| DDR     | 1         | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 99        | 69.72%  |
| Row Of Chips | 35        | 24.65%  |
| DIMM         | 6         | 4.23%   |
| Unknown      | 2         | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 58        | 37.42%  |
| 4096  | 35        | 22.58%  |
| 16384 | 26        | 16.77%  |
| 2048  | 14        | 9.03%   |
| 32768 | 10        | 6.45%   |
| 1024  | 6         | 3.87%   |
| 256   | 2         | 1.29%   |
| 64    | 2         | 1.29%   |
| 512   | 1         | 0.65%   |
| 232   | 1         | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 28        | 18.79%  |
| 3200    | 24        | 16.11%  |
| 1600    | 20        | 13.42%  |
| 2133    | 12        | 8.05%   |
| 2400    | 10        | 6.71%   |
| 4267    | 7         | 4.7%    |
| 6400    | 6         | 4.03%   |
| 4800    | 6         | 4.03%   |
| Unknown | 6         | 4.03%   |
| 1867    | 5         | 3.36%   |
| 3266    | 4         | 2.68%   |
| 5600    | 3         | 2.01%   |
| 667     | 3         | 2.01%   |
| 3733    | 2         | 1.34%   |
| 1334    | 2         | 1.34%   |
| 533     | 2         | 1.34%   |
| 200     | 2         | 1.34%   |
| 8400    | 1         | 0.67%   |
| 4266    | 1         | 0.67%   |
| 2933    | 1         | 0.67%   |
| 1067    | 1         | 0.67%   |
| 1066    | 1         | 0.67%   |
| 975     | 1         | 0.67%   |
| 333     | 1         | 0.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Xiaomi | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Xiaomi MiMouse 2 | 1         | 100%    |

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
| Chicony Electronics                    | 42        | 23.46%  |
| IMC Networks                           | 20        | 11.17%  |
| Bison Electronics                      | 14        | 7.82%   |
| Microdia                               | 13        | 7.26%   |
| Realtek Semiconductor                  | 11        | 6.15%   |
| Luxvisions Innotech Limited            | 11        | 6.15%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 5.59%   |
| Sunplus Innovation Technology          | 6         | 3.35%   |
| Apple                                  | 6         | 3.35%   |
| Syntek                                 | 5         | 2.79%   |
| Quanta                                 | 5         | 2.79%   |
| Silicon Motion                         | 4         | 2.23%   |
| Suyin                                  | 3         | 1.68%   |
| Sonix Technology                       | 3         | 1.68%   |
| Alcor Micro                            | 3         | 1.68%   |
| Tripath Technology                     | 2         | 1.12%   |
| Lite-On Technology                     | 2         | 1.12%   |
| Importek                               | 2         | 1.12%   |
| Acer                                   | 2         | 1.12%   |
| Xiaomi                                 | 1         | 0.56%   |
| WaveRider Communications               | 1         | 0.56%   |
| SN0002                                 | 1         | 0.56%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.56%   |
| Ricoh                                  | 1         | 0.56%   |
| Primax Electronics                     | 1         | 0.56%   |
| Nebraska Furniture Mart                | 1         | 0.56%   |
| Microsoft                              | 1         | 0.56%   |
| Logitech                               | 1         | 0.56%   |
| lihappe8                               | 1         | 0.56%   |
| Lenovo                                 | 1         | 0.56%   |
| kingcome                               | 1         | 0.56%   |
| icSpring                               | 1         | 0.56%   |
| Genesys Logic                          | 1         | 0.56%   |
| eMPIA Technology                       | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 16        | 8.84%   |
| IMC Networks Integrated Camera                                  | 10        | 5.52%   |
| Microdia Integrated_Webcam_HD                                   | 9         | 4.97%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 6         | 3.31%   |
| Realtek Integrated_Webcam_HD                                    | 5         | 2.76%   |
| Chicony FJ Camera                                               | 5         | 2.76%   |
| Bison Integrated Camera                                         | 5         | 2.76%   |
| Syntek Integrated Camera                                        | 4         | 2.21%   |
| Chicony HD WebCam                                               | 4         | 2.21%   |
| Luxvisions Innotech Limited HP HD Camera                        | 3         | 1.66%   |
| Chicony Integrated IR Camera                                    | 3         | 1.66%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 3         | 1.66%   |
| Apple FaceTime HD Camera (Built-in)                             | 3         | 1.66%   |
| Alcor Micro USB 2.0 PC cam                                      | 3         | 1.66%   |
| Tripath PC Camera                                               | 2         | 1.1%    |
| Sonix USB2.0 FHD UVC WebCam                                     | 2         | 1.1%    |
| Realtek USB Camera                                              | 2         | 1.1%    |
| Luxvisions Innotech Limited Integrated RGB Camera               | 2         | 1.1%    |
| Luxvisions Innotech Limited Integrated Camera                   | 2         | 1.1%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 2         | 1.1%    |
| Lite-On Integrated Camera                                       | 2         | 1.1%    |
| Importek FJ Camera                                              | 2         | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                              | 2         | 1.1%    |
| Chicony Integrated Camera (1280x720@30)                         | 2         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.1%    |
| Bison SunplusIT Integrated Camera                               | 2         | 1.1%    |
| Bison Lenovo EasyCamera                                         | 2         | 1.1%    |
| Bison BisonCam,NB Pro                                           | 2         | 1.1%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 2         | 1.1%    |
| Xiaomi Mi/Redmi series (PTP + ADB)                              | 1         | 0.55%   |
| WaveRider USB 2.0 Camera                                        | 1         | 0.55%   |
| Syntek Lenovo EasyCamera                                        | 1         | 0.55%   |
| Suyin Integrated Webcam                                         | 1         | 0.55%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 1         | 0.55%   |
| Suyin HP Truevision HD                                          | 1         | 0.55%   |
| Sunplus UNIQUESKY_CAR_CAMERA                                    | 1         | 0.55%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 0.55%   |
| Sunplus HP Universal Camera                                     | 1         | 0.55%   |
| Sunplus HD WebCam                                               | 1         | 0.55%   |
| Sunplus Camera                                                  | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 13        | 30.95%  |
| Validity Sensors           | 9         | 21.43%  |
| Shenzhen Goodix Technology | 9         | 21.43%  |
| AuthenTec                  | 4         | 9.52%   |
| Upek                       | 3         | 7.14%   |
| Samsung Electronics        | 2         | 4.76%   |
| LighTuning Technology      | 2         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader       | 7         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 11.9%   |
| Validity Sensors Synaptics WBDI                        | 4         | 9.52%   |
| Shenzhen Goodix  Fingerprint Device                    | 4         | 9.52%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 7.14%   |
| Shenzhen Goodix FingerPrint                            | 3         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 4.76%   |
| AuthenTec Fingerprint Sensor                           | 2         | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 4.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.38%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 2.38%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 2.38%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 2.38%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.38%   |
| Samsung Fingerprint Sensor Device - 730B               | 1         | 2.38%   |
| Samsung Fingerprint Device                             | 1         | 2.38%   |
| Unknown                                                | 1         | 2.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 33.33%  |
| Upek                  | 4         | 26.67%  |
| Lenovo                | 2         | 13.33%  |
| Alcor Micro           | 2         | 13.33%  |
| O2 Micro              | 1         | 6.67%   |
| Advanced Card Systems | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 26.67%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 13.33%  |
| Broadcom 5880                                                                | 2         | 13.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 13.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 6.67%   |
| Broadcom 58200                                                               | 1         | 6.67%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 124       | 57.41%  |
| 1     | 67        | 31.02%  |
| 2     | 19        | 8.8%    |
| 3     | 4         | 1.85%   |
| 5     | 1         | 0.46%   |
| 4     | 1         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 39        | 32.23%  |
| Graphics card            | 30        | 24.79%  |
| Chipcard                 | 14        | 11.57%  |
| Multimedia controller    | 13        | 10.74%  |
| Net/wireless             | 8         | 6.61%   |
| Communication controller | 5         | 4.13%   |
| Camera                   | 4         | 3.31%   |
| Bluetooth                | 3         | 2.48%   |
| Card reader              | 2         | 1.65%   |
| Storage                  | 1         | 0.83%   |
| Sound                    | 1         | 0.83%   |
| Net/ethernet             | 1         | 0.83%   |

