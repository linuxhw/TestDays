Elementary - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Elementary.

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

Total: 1734

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3481               | [78cf24846f](https://linux-hardware.org/?probe=78cf24846f) | May 09, 2024 |
| Packard Be... | EasyNote LM81               | [0ea4d18648](https://linux-hardware.org/?probe=0ea4d18648) | May 06, 2024 |
| Samsung       | 550XDA                      | [1ea7dfb8ae](https://linux-hardware.org/?probe=1ea7dfb8ae) | May 06, 2024 |
| Apple         | MacBookPro11,4              | [3c0f7c8c00](https://linux-hardware.org/?probe=3c0f7c8c00) | May 06, 2024 |
| HP            | EliteBook 830 G5            | [7ad59bc402](https://linux-hardware.org/?probe=7ad59bc402) | May 05, 2024 |
| HP            | EliteBook 830 G5            | [a88155be11](https://linux-hardware.org/?probe=a88155be11) | May 05, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | [80f71c25c1](https://linux-hardware.org/?probe=80f71c25c1) | May 05, 2024 |
| Apple         | MacBookAir4,1               | [2e67b6ba22](https://linux-hardware.org/?probe=2e67b6ba22) | May 04, 2024 |
| Lenovo        | ThinkPad T530 2429HR5       | [c5640e6fae](https://linux-hardware.org/?probe=c5640e6fae) | May 04, 2024 |
| Dell          | Latitude 5490               | [b31473028c](https://linux-hardware.org/?probe=b31473028c) | May 04, 2024 |
| Packard Be... | EasyNote LM81               | [44ead9f439](https://linux-hardware.org/?probe=44ead9f439) | May 03, 2024 |
| Google        | Nospike                     | [549d690ae1](https://linux-hardware.org/?probe=549d690ae1) | May 02, 2024 |
| Dell          | Latitude 5490               | [c83e9f5562](https://linux-hardware.org/?probe=c83e9f5562) | May 01, 2024 |
| Lenovo        | IdeaPad P400 Touch 20211    | [cacd80cba3](https://linux-hardware.org/?probe=cacd80cba3) | May 01, 2024 |
| HP            | ProBook 470 G5              | [8ba873e85d](https://linux-hardware.org/?probe=8ba873e85d) | Apr 30, 2024 |
| MSI           | GT62VR 6RE                  | [b7768b7ee9](https://linux-hardware.org/?probe=b7768b7ee9) | Apr 28, 2024 |
| HP            | EliteBook 8440p             | [0dbed15c85](https://linux-hardware.org/?probe=0dbed15c85) | Apr 27, 2024 |
| HUAWEI        | KPL-W0X                     | [0ce65136da](https://linux-hardware.org/?probe=0ce65136da) | Apr 27, 2024 |
| Apple         | MacBook5,1                  | [8da3b01d13](https://linux-hardware.org/?probe=8da3b01d13) | Apr 26, 2024 |
| HP            | EliteBook 745 G4            | [f38a6451f0](https://linux-hardware.org/?probe=f38a6451f0) | Apr 24, 2024 |
| HP            | Pavilion dv6                | [c8d73c3a23](https://linux-hardware.org/?probe=c8d73c3a23) | Apr 24, 2024 |
| HP            | Pavilion dv6                | [08f01fc7ed](https://linux-hardware.org/?probe=08f01fc7ed) | Apr 24, 2024 |
| Acer          | Aspire A515-43              | [ff74a6262e](https://linux-hardware.org/?probe=ff74a6262e) | Apr 23, 2024 |
| Apple         | MacBookAir7,2               | [674850b624](https://linux-hardware.org/?probe=674850b624) | Apr 23, 2024 |
| Unknown       | Unknown                     | [def20611a4](https://linux-hardware.org/?probe=def20611a4) | Apr 23, 2024 |
| Apple         | MacBookAir7,2               | [c7cbc009ef](https://linux-hardware.org/?probe=c7cbc009ef) | Apr 23, 2024 |
| Acer          | Aspire 5750G                | [39ed7553a3](https://linux-hardware.org/?probe=39ed7553a3) | Apr 23, 2024 |
| TECNO         | MEGABOOK T1                 | [01fc56cf5b](https://linux-hardware.org/?probe=01fc56cf5b) | Apr 22, 2024 |
| Apple         | MacBookPro11,1              | [3f4e9ae066](https://linux-hardware.org/?probe=3f4e9ae066) | Apr 21, 2024 |
| Apple         | MacBookPro11,1              | [e70b7338c2](https://linux-hardware.org/?probe=e70b7338c2) | Apr 21, 2024 |
| Acer          | Aspire 5750                 | [9e2621b213](https://linux-hardware.org/?probe=9e2621b213) | Apr 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [8740fd113c](https://linux-hardware.org/?probe=8740fd113c) | Apr 19, 2024 |
| HP            | Pavilion Notebook           | [8b925ca8f0](https://linux-hardware.org/?probe=8b925ca8f0) | Apr 19, 2024 |
| ASUSTek       | K42F                        | [d127923f98](https://linux-hardware.org/?probe=d127923f98) | Apr 17, 2024 |
| HP            | Pavilion x2 Detachable      | [9e5556a266](https://linux-hardware.org/?probe=9e5556a266) | Apr 17, 2024 |
| Apple         | MacBookPro16,1              | [40fd2c63cb](https://linux-hardware.org/?probe=40fd2c63cb) | Apr 16, 2024 |
| DEPO Compu... | W25CEW                      | [6653a2975d](https://linux-hardware.org/?probe=6653a2975d) | Apr 15, 2024 |
| Apple         | MacBookAir7,1               | [c1be5d2dd6](https://linux-hardware.org/?probe=c1be5d2dd6) | Apr 14, 2024 |
| Apple         | MacBookPro9,2               | [5a62c14a1f](https://linux-hardware.org/?probe=5a62c14a1f) | Apr 14, 2024 |
| Apple         | MacBookPro9,2               | [97f0209510](https://linux-hardware.org/?probe=97f0209510) | Apr 14, 2024 |
| Acer          | Aspire 6935                 | [d26ee0494f](https://linux-hardware.org/?probe=d26ee0494f) | Apr 13, 2024 |
| Apple         | MacBookPro8,2               | [e57c02860c](https://linux-hardware.org/?probe=e57c02860c) | Apr 13, 2024 |
| Acer          | Aspire 5750                 | [f64263bd19](https://linux-hardware.org/?probe=f64263bd19) | Apr 12, 2024 |
| Apple         | MacBookAir7,2               | [569f9614a5](https://linux-hardware.org/?probe=569f9614a5) | Apr 12, 2024 |
| HP            | ProBook 6360b               | [81b9d0706b](https://linux-hardware.org/?probe=81b9d0706b) | Apr 11, 2024 |
| Apple         | MacBookPro8,2               | [461d5dfd8d](https://linux-hardware.org/?probe=461d5dfd8d) | Apr 11, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | [35b206d8f8](https://linux-hardware.org/?probe=35b206d8f8) | Apr 10, 2024 |
| HP            | EliteBook 745 G4            | [0d92302707](https://linux-hardware.org/?probe=0d92302707) | Apr 09, 2024 |
| Apple         | MacBookPro8,1               | [ac137b7cb7](https://linux-hardware.org/?probe=ac137b7cb7) | Apr 09, 2024 |
| Apple         | MacBookPro8,1               | [e964beb301](https://linux-hardware.org/?probe=e964beb301) | Apr 09, 2024 |
| Apple         | MacBookPro5,4               | [3ab1d66e10](https://linux-hardware.org/?probe=3ab1d66e10) | Apr 08, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [9099f440bc](https://linux-hardware.org/?probe=9099f440bc) | Apr 08, 2024 |
| Apple         | MacBookPro8,1               | [7efef6a0ae](https://linux-hardware.org/?probe=7efef6a0ae) | Apr 07, 2024 |
| Apple         | MacBookPro8,1               | [d28398beb7](https://linux-hardware.org/?probe=d28398beb7) | Apr 07, 2024 |
| Dell          | XPS 15 9570                 | [ccdb5dcad9](https://linux-hardware.org/?probe=ccdb5dcad9) | Apr 07, 2024 |
| Apple         | MacBookPro9,2               | [a90b694613](https://linux-hardware.org/?probe=a90b694613) | Apr 06, 2024 |
| Acer          | Aspire 5750                 | [27d64e5b3c](https://linux-hardware.org/?probe=27d64e5b3c) | Apr 05, 2024 |
| Apple         | MacBookPro8,1               | [733d6c6e2b](https://linux-hardware.org/?probe=733d6c6e2b) | Apr 05, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | [3d64dfc3a9](https://linux-hardware.org/?probe=3d64dfc3a9) | Apr 04, 2024 |
| Acer          | Aspire 5750                 | [e2cef27ef8](https://linux-hardware.org/?probe=e2cef27ef8) | Apr 03, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9bc584b914](https://linux-hardware.org/?probe=9bc584b914) | Apr 03, 2024 |
| Toshiba       | Satellite L10W-B-101        | [eaa5927086](https://linux-hardware.org/?probe=eaa5927086) | Apr 03, 2024 |
| HP            | Pavilion dv7                | [483e1957a4](https://linux-hardware.org/?probe=483e1957a4) | Apr 02, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [fe5490324f](https://linux-hardware.org/?probe=fe5490324f) | Apr 01, 2024 |
| Medion        | E6217                       | [c2ca377a05](https://linux-hardware.org/?probe=c2ca377a05) | Mar 31, 2024 |
| HP            | Pavilion dv7                | [a86e8cccf5](https://linux-hardware.org/?probe=a86e8cccf5) | Mar 31, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b68181d354](https://linux-hardware.org/?probe=b68181d354) | Mar 29, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [5b4456a2d6](https://linux-hardware.org/?probe=5b4456a2d6) | Mar 29, 2024 |
| Dell          | Inspiron 5423               | [0c6c4c6a58](https://linux-hardware.org/?probe=0c6c4c6a58) | Mar 29, 2024 |
| Lenovo        | ThinkPad W500 40623CG       | [71c868292f](https://linux-hardware.org/?probe=71c868292f) | Mar 27, 2024 |
| Lenovo        | ThinkPad W500 40623CG       | [01d1ef9c31](https://linux-hardware.org/?probe=01d1ef9c31) | Mar 26, 2024 |
| Lenovo        | ThinkPad T410 2537CQ7       | [8b91ec68dd](https://linux-hardware.org/?probe=8b91ec68dd) | Mar 26, 2024 |
| Lenovo        | ThinkPad T450s 20BX0011G... | [3e86099c28](https://linux-hardware.org/?probe=3e86099c28) | Mar 26, 2024 |
| Lenovo        | ThinkPad T450s 20BX0011G... | [598015ca49](https://linux-hardware.org/?probe=598015ca49) | Mar 24, 2024 |
| Samsung       | 535U3C                      | [6b29450ac6](https://linux-hardware.org/?probe=6b29450ac6) | Mar 23, 2024 |
| HUAWEI        | BOM-WXX9                    | [20d2290d1c](https://linux-hardware.org/?probe=20d2290d1c) | Mar 23, 2024 |
| HUAWEI        | NBLB-WAX9N                  | [e5c5d49216](https://linux-hardware.org/?probe=e5c5d49216) | Mar 22, 2024 |
| HP            | ProBook 450 G3              | [a32e851ddd](https://linux-hardware.org/?probe=a32e851ddd) | Mar 21, 2024 |
| HP            | ENVY 17                     | [0ee4da384d](https://linux-hardware.org/?probe=0ee4da384d) | Mar 20, 2024 |
| MSI           | GE70 2QE                    | [31b45c6de7](https://linux-hardware.org/?probe=31b45c6de7) | Mar 17, 2024 |
| HP            | Laptop 17-by3xxx            | [430290e97d](https://linux-hardware.org/?probe=430290e97d) | Mar 17, 2024 |
| Dell          | Latitude E6420              | [dc953135d3](https://linux-hardware.org/?probe=dc953135d3) | Mar 16, 2024 |
| Dell          | Latitude E7240              | [d159f296d4](https://linux-hardware.org/?probe=d159f296d4) | Mar 16, 2024 |
| ASUSTek       | X541UAK                     | [4b33512569](https://linux-hardware.org/?probe=4b33512569) | Mar 16, 2024 |
| Dell          | Latitude E7470              | [4addfb5619](https://linux-hardware.org/?probe=4addfb5619) | Mar 14, 2024 |
| Dell          | Latitude E7470              | [fbf1fe3963](https://linux-hardware.org/?probe=fbf1fe3963) | Mar 14, 2024 |
| Acer          | Aspire E5-573G              | [36653be57c](https://linux-hardware.org/?probe=36653be57c) | Mar 13, 2024 |
| ASUSTek       | X555LAB                     | [8b2310099c](https://linux-hardware.org/?probe=8b2310099c) | Mar 13, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [cfb2591a20](https://linux-hardware.org/?probe=cfb2591a20) | Mar 12, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [9160e106f1](https://linux-hardware.org/?probe=9160e106f1) | Mar 12, 2024 |
| Apple         | MacBookAir7,2               | [89b268f1f8](https://linux-hardware.org/?probe=89b268f1f8) | Mar 11, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | [22f1633f40](https://linux-hardware.org/?probe=22f1633f40) | Mar 09, 2024 |
| ASUSTek       | X541UAK                     | [8b527dc9c9](https://linux-hardware.org/?probe=8b527dc9c9) | Mar 09, 2024 |
| HP            | ENVY Notebook               | [6ab7868737](https://linux-hardware.org/?probe=6ab7868737) | Mar 08, 2024 |
| Apple         | MacBookPro11,2              | [486387c7ef](https://linux-hardware.org/?probe=486387c7ef) | Mar 08, 2024 |
| Apple         | MacBookAir7,2               | [f701ce67f5](https://linux-hardware.org/?probe=f701ce67f5) | Mar 07, 2024 |
| Apple         | MacBookAir7,2               | [4c046066f7](https://linux-hardware.org/?probe=4c046066f7) | Mar 05, 2024 |
| Lenovo        | ThinkPad X250 20CLS3NA00    | [ecea244114](https://linux-hardware.org/?probe=ecea244114) | Mar 03, 2024 |
| Unknown       | Unknown                     | [2ca2d631cc](https://linux-hardware.org/?probe=2ca2d631cc) | Mar 02, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | [d7d8cc5cc7](https://linux-hardware.org/?probe=d7d8cc5cc7) | Mar 02, 2024 |
| HP            | ProBook 4540s               | [46cdfe37d6](https://linux-hardware.org/?probe=46cdfe37d6) | Mar 02, 2024 |
| HP            | ProBook 4540s               | [ec5752452f](https://linux-hardware.org/?probe=ec5752452f) | Mar 02, 2024 |
| HP            | 250 G8 Notebook PC          | [bcac46fe58](https://linux-hardware.org/?probe=bcac46fe58) | Mar 01, 2024 |
| Apple         | MacBookPro5,4               | [681e76d909](https://linux-hardware.org/?probe=681e76d909) | Feb 29, 2024 |
| Apple         | MacBookPro5,4               | [ca45519759](https://linux-hardware.org/?probe=ca45519759) | Feb 29, 2024 |
| UNOWHY        | Y13G011S4EI                 | [f785899192](https://linux-hardware.org/?probe=f785899192) | Feb 29, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [11a760c545](https://linux-hardware.org/?probe=11a760c545) | Feb 28, 2024 |
| HP            | 15                          | [6fb113d856](https://linux-hardware.org/?probe=6fb113d856) | Feb 28, 2024 |
| Dell          | Inspiron 5567               | [9a57de6e15](https://linux-hardware.org/?probe=9a57de6e15) | Feb 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [49ac7f8a77](https://linux-hardware.org/?probe=49ac7f8a77) | Feb 27, 2024 |
| Apple         | MacBookPro9,2               | [7167de20ce](https://linux-hardware.org/?probe=7167de20ce) | Feb 27, 2024 |
| Lenovo        | V15 G1 IML 82NB             | [b51e9d56f2](https://linux-hardware.org/?probe=b51e9d56f2) | Feb 27, 2024 |
| HUAWEI        | KLVL-WXX9                   | [b1c31d32ab](https://linux-hardware.org/?probe=b1c31d32ab) | Feb 27, 2024 |
| ASUSTek       | X441UA                      | [1185900ace](https://linux-hardware.org/?probe=1185900ace) | Feb 26, 2024 |
| Lenovo        | IdeaPad S400 Touch VIUS3    | [61e571e08f](https://linux-hardware.org/?probe=61e571e08f) | Feb 26, 2024 |
| Acer          | TravelMate P256-MG          | [abcfd5362f](https://linux-hardware.org/?probe=abcfd5362f) | Feb 25, 2024 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [ca33f4c1c6](https://linux-hardware.org/?probe=ca33f4c1c6) | Feb 25, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | [6d31b35e19](https://linux-hardware.org/?probe=6d31b35e19) | Feb 25, 2024 |
| Apple         | MacBook5,1                  | [be026cabc8](https://linux-hardware.org/?probe=be026cabc8) | Feb 24, 2024 |
| Acer          | Swift SF314-43              | [56b060901d](https://linux-hardware.org/?probe=56b060901d) | Feb 23, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | [83bf2661f0](https://linux-hardware.org/?probe=83bf2661f0) | Feb 23, 2024 |
| Apple         | MacBookAir7,2               | [627c4721b6](https://linux-hardware.org/?probe=627c4721b6) | Feb 21, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [96fb9606bf](https://linux-hardware.org/?probe=96fb9606bf) | Feb 20, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [520188b3c6](https://linux-hardware.org/?probe=520188b3c6) | Feb 20, 2024 |
| HP            | ProBook 450 G1              | [ba02f5d2ae](https://linux-hardware.org/?probe=ba02f5d2ae) | Feb 18, 2024 |
| Slimbook      | Essential 14                | [05c319f707](https://linux-hardware.org/?probe=05c319f707) | Feb 18, 2024 |
| Apple         | MacBookAir6,1               | [f11ff820e7](https://linux-hardware.org/?probe=f11ff820e7) | Feb 18, 2024 |
| HP            | ProBook 430 G2              | [a4b236fd41](https://linux-hardware.org/?probe=a4b236fd41) | Feb 17, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [b5bad706ef](https://linux-hardware.org/?probe=b5bad706ef) | Feb 15, 2024 |
| HP            | 245 G8                      | [c66563da68](https://linux-hardware.org/?probe=c66563da68) | Feb 14, 2024 |
| Dell          | Vostro 1540                 | [ed9ed14ad8](https://linux-hardware.org/?probe=ed9ed14ad8) | Feb 14, 2024 |
| HP            | ZBook 15                    | [bcb41f3b4c](https://linux-hardware.org/?probe=bcb41f3b4c) | Feb 14, 2024 |
| MSI           | GF72VR 7RF                  | [8fb108b426](https://linux-hardware.org/?probe=8fb108b426) | Feb 13, 2024 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d1856c355f](https://linux-hardware.org/?probe=d1856c355f) | Feb 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [498af1a9a2](https://linux-hardware.org/?probe=498af1a9a2) | Feb 06, 2024 |
| Teclast       | F7                          | [04b33deb97](https://linux-hardware.org/?probe=04b33deb97) | Feb 04, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [fdc21a05c2](https://linux-hardware.org/?probe=fdc21a05c2) | Feb 02, 2024 |
| Acer          | AOD255                      | [43304c651c](https://linux-hardware.org/?probe=43304c651c) | Feb 01, 2024 |
| HUAWEI        | BOD-WXX9                    | [d1a7f0cddb](https://linux-hardware.org/?probe=d1a7f0cddb) | Jan 31, 2024 |
| HP            | Pavilion g6                 | [acd0ae9c04](https://linux-hardware.org/?probe=acd0ae9c04) | Jan 31, 2024 |
| Apple         | MacBookPro7,1               | [973c263365](https://linux-hardware.org/?probe=973c263365) | Jan 30, 2024 |
| Fujitsu       | LIFEBOOK E734               | [7b3a60ae2d](https://linux-hardware.org/?probe=7b3a60ae2d) | Jan 30, 2024 |
| Acer          | Aspire E5-571               | [6ebe6ae5be](https://linux-hardware.org/?probe=6ebe6ae5be) | Jan 28, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | [1c0f2e8a2f](https://linux-hardware.org/?probe=1c0f2e8a2f) | Jan 26, 2024 |
| Dell          | Latitude E7240              | [d8e5d4a8da](https://linux-hardware.org/?probe=d8e5d4a8da) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [81338699ce](https://linux-hardware.org/?probe=81338699ce) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [9f021a2102](https://linux-hardware.org/?probe=9f021a2102) | Jan 25, 2024 |
| Samsung       | RC410/RC510/RC710           | [34369cc7eb](https://linux-hardware.org/?probe=34369cc7eb) | Jan 25, 2024 |
| Samsung       | RC410/RC510/RC710           | [d48bdbaec0](https://linux-hardware.org/?probe=d48bdbaec0) | Jan 24, 2024 |
| Acer          | Aspire E5-573G              | [14eec10d5e](https://linux-hardware.org/?probe=14eec10d5e) | Jan 24, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3361cf9ae9](https://linux-hardware.org/?probe=3361cf9ae9) | Jan 23, 2024 |
| Lenovo        | V17 G2 ITL 82NX             | [40f906871e](https://linux-hardware.org/?probe=40f906871e) | Jan 22, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED18    | [63d8796a60](https://linux-hardware.org/?probe=63d8796a60) | Jan 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [86d22c9b40](https://linux-hardware.org/?probe=86d22c9b40) | Jan 17, 2024 |
| Apple         | MacBook6,1                  | [641df770ba](https://linux-hardware.org/?probe=641df770ba) | Jan 17, 2024 |
| Packard Be... | EasyNote TS11HR             | [41076ef28d](https://linux-hardware.org/?probe=41076ef28d) | Jan 14, 2024 |
| Apple         | MacBookPro9,2               | [7cf8b59aee](https://linux-hardware.org/?probe=7cf8b59aee) | Jan 10, 2024 |
| Apple         | MacBook5,1                  | [75835b3764](https://linux-hardware.org/?probe=75835b3764) | Jan 09, 2024 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [c3a6a2da37](https://linux-hardware.org/?probe=c3a6a2da37) | Jan 09, 2024 |
| Apple         | MacBook5,1                  | [3a4a960ff8](https://linux-hardware.org/?probe=3a4a960ff8) | Jan 06, 2024 |
| Apple         | MacBookPro7,1               | [75fc0fa74a](https://linux-hardware.org/?probe=75fc0fa74a) | Jan 06, 2024 |
| TECNO Mobi... | MEGABOOK T14TA              | [deadd2cf3d](https://linux-hardware.org/?probe=deadd2cf3d) | Jan 05, 2024 |
| HP            | Laptop 17-by3xxx            | [32486bf070](https://linux-hardware.org/?probe=32486bf070) | Jan 04, 2024 |
| Dell          | Latitude E7440              | [75ba78537c](https://linux-hardware.org/?probe=75ba78537c) | Jan 03, 2024 |
| Positivo      | C4128A-15                   | [52bd86685b](https://linux-hardware.org/?probe=52bd86685b) | Jan 03, 2024 |
| Medion        | E11202                      | [cb45690620](https://linux-hardware.org/?probe=cb45690620) | Jan 01, 2024 |
| HP            | EliteBook 840 G1            | [9ab6343dd7](https://linux-hardware.org/?probe=9ab6343dd7) | Jan 01, 2024 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [0120368c3a](https://linux-hardware.org/?probe=0120368c3a) | Jan 01, 2024 |
| Positivo      | C4128A-15                   | [6416d967b8](https://linux-hardware.org/?probe=6416d967b8) | Dec 30, 2023 |
| Positivo      | C4128A-15                   | [bd9afc6d73](https://linux-hardware.org/?probe=bd9afc6d73) | Dec 30, 2023 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [a55f917cf6](https://linux-hardware.org/?probe=a55f917cf6) | Dec 29, 2023 |
| Medion        | E11202                      | [9db140d63c](https://linux-hardware.org/?probe=9db140d63c) | Dec 28, 2023 |
| HP            | Laptop 15-dw3xxx            | [76305a2c98](https://linux-hardware.org/?probe=76305a2c98) | Dec 28, 2023 |
| Acer          | Swift SFX14-41G             | [d39de69e1b](https://linux-hardware.org/?probe=d39de69e1b) | Dec 27, 2023 |
| THTF          | WUJIE 14                    | [c402523a2c](https://linux-hardware.org/?probe=c402523a2c) | Dec 25, 2023 |
| THTF          | WUJIE 14                    | [39ee354a27](https://linux-hardware.org/?probe=39ee354a27) | Dec 25, 2023 |
| Medion        | E11202                      | [af0c7baf03](https://linux-hardware.org/?probe=af0c7baf03) | Dec 22, 2023 |
| ASUSTek       | X555LAB                     | [8a8a35c616](https://linux-hardware.org/?probe=8a8a35c616) | Dec 21, 2023 |
| Apple         | MacBook5,1                  | [9839cacb3a](https://linux-hardware.org/?probe=9839cacb3a) | Dec 19, 2023 |
| Apple         | MacBook5,1                  | [8268b72759](https://linux-hardware.org/?probe=8268b72759) | Dec 19, 2023 |
| Acer          | Aspire 4736Z                | [38866fae79](https://linux-hardware.org/?probe=38866fae79) | Dec 17, 2023 |
| Dell          | Precision 7560              | [0f83098df3](https://linux-hardware.org/?probe=0f83098df3) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [abc0a9283d](https://linux-hardware.org/?probe=abc0a9283d) | Dec 14, 2023 |
| ASUSTek       | X75A1                       | [e7d274ca96](https://linux-hardware.org/?probe=e7d274ca96) | Dec 13, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [4d416a35fa](https://linux-hardware.org/?probe=4d416a35fa) | Dec 12, 2023 |
| Sony          | SVE11115ELW                 | [68fa8c6081](https://linux-hardware.org/?probe=68fa8c6081) | Dec 10, 2023 |
| Sony          | SVE11115ELW                 | [567787c7d3](https://linux-hardware.org/?probe=567787c7d3) | Dec 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5a75d4827a](https://linux-hardware.org/?probe=5a75d4827a) | Dec 10, 2023 |
| Lenovo        | ThinkPad P51s 20HBCTO1WW    | [4c18329d9d](https://linux-hardware.org/?probe=4c18329d9d) | Dec 09, 2023 |
| HP            | Laptop 15-dw3xxx            | [8167f60069](https://linux-hardware.org/?probe=8167f60069) | Dec 05, 2023 |
| Dell          | Inspiron 15-3552            | [8ca2d01e7c](https://linux-hardware.org/?probe=8ca2d01e7c) | Dec 05, 2023 |
| Acer          | Aspire 4736Z                | [844b16d408](https://linux-hardware.org/?probe=844b16d408) | Dec 03, 2023 |
| HP            | EliteBook 840 G3            | [fa8d37e46b](https://linux-hardware.org/?probe=fa8d37e46b) | Nov 30, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [a0d4963838](https://linux-hardware.org/?probe=a0d4963838) | Nov 28, 2023 |
| HP            | Pavilion dv7                | [c617d0a2d4](https://linux-hardware.org/?probe=c617d0a2d4) | Nov 26, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [cf1e883f11](https://linux-hardware.org/?probe=cf1e883f11) | Nov 25, 2023 |
| Samsung       | RF510/RF410/RF710           | [a642075264](https://linux-hardware.org/?probe=a642075264) | Nov 25, 2023 |
| Dell          | Inspiron N5040              | [3b51468cdf](https://linux-hardware.org/?probe=3b51468cdf) | Nov 24, 2023 |
| Apple         | MacBookPro5,5               | [a2d556bc01](https://linux-hardware.org/?probe=a2d556bc01) | Nov 20, 2023 |
| Apple         | MacBookPro5,5               | [cdc6379993](https://linux-hardware.org/?probe=cdc6379993) | Nov 19, 2023 |
| Apple         | MacBookPro5,5               | [840adf8528](https://linux-hardware.org/?probe=840adf8528) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | [886c5bc9a6](https://linux-hardware.org/?probe=886c5bc9a6) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | [bcd7007cde](https://linux-hardware.org/?probe=bcd7007cde) | Nov 19, 2023 |
| iOTA          | IOTA2320                    | [5c4d630f23](https://linux-hardware.org/?probe=5c4d630f23) | Nov 19, 2023 |
| HP            | Pavilion dv7                | [4c482baa30](https://linux-hardware.org/?probe=4c482baa30) | Nov 18, 2023 |
| HP            | Pavilion dv7                | [e05cf328e2](https://linux-hardware.org/?probe=e05cf328e2) | Nov 18, 2023 |
| Fujitsu       | LIFEBOOK E780               | [d3a64f5368](https://linux-hardware.org/?probe=d3a64f5368) | Nov 16, 2023 |
| Unknown       | Unknown                     | [66296a4edd](https://linux-hardware.org/?probe=66296a4edd) | Nov 12, 2023 |
| Alienware     | 15 R3                       | [c920563c0b](https://linux-hardware.org/?probe=c920563c0b) | Nov 12, 2023 |
| Apple         | MacBookAir6,2               | [3595c8f9d1](https://linux-hardware.org/?probe=3595c8f9d1) | Nov 12, 2023 |
| HP            | 245 G8                      | [0b471d312a](https://linux-hardware.org/?probe=0b471d312a) | Nov 11, 2023 |
| HP            | 245 G8                      | [b29efc88ec](https://linux-hardware.org/?probe=b29efc88ec) | Nov 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [9b881d355c](https://linux-hardware.org/?probe=9b881d355c) | Nov 09, 2023 |
| Dell          | Vostro 3500                 | [860fc63d0d](https://linux-hardware.org/?probe=860fc63d0d) | Nov 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [5c39f44ed5](https://linux-hardware.org/?probe=5c39f44ed5) | Nov 08, 2023 |
| Dell          | G7 7500                     | [91adca1093](https://linux-hardware.org/?probe=91adca1093) | Nov 07, 2023 |
| Timi          | Redmi G 2022                | [f8cecbac55](https://linux-hardware.org/?probe=f8cecbac55) | Nov 07, 2023 |
| ASUSTek       | X555LAB                     | [2d3d09097d](https://linux-hardware.org/?probe=2d3d09097d) | Nov 06, 2023 |
| Dell          | G7 7500                     | [3678c5437b](https://linux-hardware.org/?probe=3678c5437b) | Nov 06, 2023 |
| Apple         | MacBookPro11,1              | [2d84377719](https://linux-hardware.org/?probe=2d84377719) | Nov 06, 2023 |
| HP            | 245 G8                      | [e9c1cc78b8](https://linux-hardware.org/?probe=e9c1cc78b8) | Nov 06, 2023 |
| HP            | Spectre Pro G1              | [78bce56071](https://linux-hardware.org/?probe=78bce56071) | Nov 05, 2023 |
| HP            | ProBook 6545b               | [a81427fffa](https://linux-hardware.org/?probe=a81427fffa) | Nov 05, 2023 |
| Acer          | Aspire E5-551G              | [f8e737dbde](https://linux-hardware.org/?probe=f8e737dbde) | Nov 03, 2023 |
| HONOR         | NMH-WDX9                    | [11e32e2482](https://linux-hardware.org/?probe=11e32e2482) | Nov 03, 2023 |
| Alienware     | 14                          | [3d3be9ce75](https://linux-hardware.org/?probe=3d3be9ce75) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [e25974d32d](https://linux-hardware.org/?probe=e25974d32d) | Oct 31, 2023 |
| Dell          | Inspiron 1545               | [5a1d90c1a7](https://linux-hardware.org/?probe=5a1d90c1a7) | Oct 30, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [300d56f39e](https://linux-hardware.org/?probe=300d56f39e) | Oct 29, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [29a362f501](https://linux-hardware.org/?probe=29a362f501) | Oct 29, 2023 |
| Apple         | MacBook7,1                  | [61b133ac1e](https://linux-hardware.org/?probe=61b133ac1e) | Oct 27, 2023 |
| Dell          | Latitude E6520              | [dbbca588de](https://linux-hardware.org/?probe=dbbca588de) | Oct 26, 2023 |
| ASUSTek       | X555LAB                     | [a8b1ad0f53](https://linux-hardware.org/?probe=a8b1ad0f53) | Oct 25, 2023 |
| Dell          | Vostro 15 3515              | [5713b2f30e](https://linux-hardware.org/?probe=5713b2f30e) | Oct 24, 2023 |
| Dell          | Latitude E6400              | [250c9ddcfe](https://linux-hardware.org/?probe=250c9ddcfe) | Oct 24, 2023 |
| Apple         | MacBookPro6,2               | [89f29afb19](https://linux-hardware.org/?probe=89f29afb19) | Oct 24, 2023 |
| Dell          | Latitude E6400              | [6a3537c763](https://linux-hardware.org/?probe=6a3537c763) | Oct 23, 2023 |
| Dell          | Latitude E6520              | [c2fd0014ab](https://linux-hardware.org/?probe=c2fd0014ab) | Oct 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3431e88cbe](https://linux-hardware.org/?probe=3431e88cbe) | Oct 22, 2023 |
| Google        | Cave                        | [287887d308](https://linux-hardware.org/?probe=287887d308) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [b11aafb048](https://linux-hardware.org/?probe=b11aafb048) | Oct 20, 2023 |
| HP            | Pavilion 17                 | [855c6109eb](https://linux-hardware.org/?probe=855c6109eb) | Oct 20, 2023 |
| HP            | Pavilion dv7                | [13b6b396e9](https://linux-hardware.org/?probe=13b6b396e9) | Oct 18, 2023 |
| Apple         | MacBookPro6,2               | [036b6067b8](https://linux-hardware.org/?probe=036b6067b8) | Oct 18, 2023 |
| Apple         | MacBookPro5,3               | [1e3660c797](https://linux-hardware.org/?probe=1e3660c797) | Oct 17, 2023 |
| Apple         | MacBookPro5,3               | [3dde86d447](https://linux-hardware.org/?probe=3dde86d447) | Oct 17, 2023 |
| Dell          | Inspiron 1545               | [87edaec977](https://linux-hardware.org/?probe=87edaec977) | Oct 17, 2023 |
| Acer          | Nitro AN517-54              | [2f6c2f44d3](https://linux-hardware.org/?probe=2f6c2f44d3) | Oct 15, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [de2f74b12a](https://linux-hardware.org/?probe=de2f74b12a) | Oct 13, 2023 |
| Lenovo        | B570 1068FRG                | [e912de748b](https://linux-hardware.org/?probe=e912de748b) | Oct 11, 2023 |
| Dell          | Vostro 1510                 | [6324053514](https://linux-hardware.org/?probe=6324053514) | Oct 10, 2023 |
| HP            | EliteBook 2570p             | [c41bac6f71](https://linux-hardware.org/?probe=c41bac6f71) | Oct 09, 2023 |
| HP            | Pavilion 15                 | [0c8f955052](https://linux-hardware.org/?probe=0c8f955052) | Oct 08, 2023 |
| Apple         | MacBookPro11,5              | [61890a8e2e](https://linux-hardware.org/?probe=61890a8e2e) | Oct 08, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [ccc23328e5](https://linux-hardware.org/?probe=ccc23328e5) | Oct 07, 2023 |
| Dell          | Vostro 1510                 | [39ee83fbf5](https://linux-hardware.org/?probe=39ee83fbf5) | Oct 06, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a49cef1179](https://linux-hardware.org/?probe=a49cef1179) | Oct 04, 2023 |
| Apple         | MacBookPro7,1               | [d88817f79c](https://linux-hardware.org/?probe=d88817f79c) | Oct 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [d91dd7bed6](https://linux-hardware.org/?probe=d91dd7bed6) | Oct 02, 2023 |
| Dell          | Latitude E7270              | [bf1def4fc3](https://linux-hardware.org/?probe=bf1def4fc3) | Oct 01, 2023 |
| Apple         | MacBookAir7,2               | [0a667d66b7](https://linux-hardware.org/?probe=0a667d66b7) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | [15f8d0107f](https://linux-hardware.org/?probe=15f8d0107f) | Sep 26, 2023 |
| Acer          | Aspire R3-131T              | [c643f10970](https://linux-hardware.org/?probe=c643f10970) | Sep 24, 2023 |
| Apple         | MacBookPro11,1              | [e9478deeae](https://linux-hardware.org/?probe=e9478deeae) | Sep 23, 2023 |
| Dell          | Latitude E7270              | [874b8a2ad5](https://linux-hardware.org/?probe=874b8a2ad5) | Sep 23, 2023 |
| HP            | EliteBook 8570p             | [ca346761d3](https://linux-hardware.org/?probe=ca346761d3) | Sep 23, 2023 |
| HP            | Laptop 17-by4xxx            | [dd1d978c67](https://linux-hardware.org/?probe=dd1d978c67) | Sep 22, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [c8bbae1068](https://linux-hardware.org/?probe=c8bbae1068) | Sep 20, 2023 |
| Dell          | Latitude E6410              | [3a9273fd3e](https://linux-hardware.org/?probe=3a9273fd3e) | Sep 17, 2023 |
| Apple         | MacBookAir7,2               | [3941e3e259](https://linux-hardware.org/?probe=3941e3e259) | Sep 16, 2023 |
| Apple         | MacBookAir7,2               | [1ea319e72e](https://linux-hardware.org/?probe=1ea319e72e) | Sep 15, 2023 |
| Apple         | MacBook6,1                  | [8db6f2c947](https://linux-hardware.org/?probe=8db6f2c947) | Sep 14, 2023 |
| Apple         | MacBookPro11,2              | [d3996a81e2](https://linux-hardware.org/?probe=d3996a81e2) | Sep 07, 2023 |
| Dell          | Latitude E5570              | [10d8ad7a3d](https://linux-hardware.org/?probe=10d8ad7a3d) | Sep 05, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [7a27c6dd8d](https://linux-hardware.org/?probe=7a27c6dd8d) | Sep 03, 2023 |
| Timi          | TM1613                      | [6acee9a858](https://linux-hardware.org/?probe=6acee9a858) | Sep 03, 2023 |
| Dell          | Latitude E6410              | [bd6242d5b8](https://linux-hardware.org/?probe=bd6242d5b8) | Sep 02, 2023 |
| Dell          | Latitude E6410              | [9e2aa5e0e5](https://linux-hardware.org/?probe=9e2aa5e0e5) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | [783d0f51f5](https://linux-hardware.org/?probe=783d0f51f5) | Aug 31, 2023 |
| Medion        | E15301                      | [7f6c4eb814](https://linux-hardware.org/?probe=7f6c4eb814) | Aug 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [24ad5e2b06](https://linux-hardware.org/?probe=24ad5e2b06) | Aug 31, 2023 |
| HP            | EliteBook 840 G3            | [b8492993cf](https://linux-hardware.org/?probe=b8492993cf) | Aug 30, 2023 |
| HP            | 350 G1                      | [1e317e5a51](https://linux-hardware.org/?probe=1e317e5a51) | Aug 30, 2023 |
| Digma         | EVE 11 C421Y ES1067EW       | [22e88dc9a5](https://linux-hardware.org/?probe=22e88dc9a5) | Aug 29, 2023 |
| Apple         | MacBookAir6,2               | [7c208705e5](https://linux-hardware.org/?probe=7c208705e5) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | [8741a9bb96](https://linux-hardware.org/?probe=8741a9bb96) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | [7efcdba9ef](https://linux-hardware.org/?probe=7efcdba9ef) | Aug 29, 2023 |
| HP            | 350 G1                      | [d800790bce](https://linux-hardware.org/?probe=d800790bce) | Aug 28, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [627068909d](https://linux-hardware.org/?probe=627068909d) | Aug 25, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [5c956051fb](https://linux-hardware.org/?probe=5c956051fb) | Aug 24, 2023 |
| Dell          | Inspiron 15 3511            | [744be89da4](https://linux-hardware.org/?probe=744be89da4) | Aug 24, 2023 |
| Google        | Eldrid                      | [e451d840cf](https://linux-hardware.org/?probe=e451d840cf) | Aug 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | [8d8d50eabc](https://linux-hardware.org/?probe=8d8d50eabc) | Aug 20, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [01a44fbb3b](https://linux-hardware.org/?probe=01a44fbb3b) | Aug 20, 2023 |
| Apple         | MacBookPro9,2               | [551dc38c00](https://linux-hardware.org/?probe=551dc38c00) | Aug 19, 2023 |
| Apple         | MacBookPro9,2               | [0bbf9ab6c2](https://linux-hardware.org/?probe=0bbf9ab6c2) | Aug 19, 2023 |
| Lenovo        | ThinkPad T540p 20BFS02S0... | [2f59ec7141](https://linux-hardware.org/?probe=2f59ec7141) | Aug 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [8298417da7](https://linux-hardware.org/?probe=8298417da7) | Aug 16, 2023 |
| HP            | ZBook 15                    | [97923a8762](https://linux-hardware.org/?probe=97923a8762) | Aug 15, 2023 |
| Apple         | MacBookPro5,5               | [dc696b572c](https://linux-hardware.org/?probe=dc696b572c) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | [5d7e68e3ae](https://linux-hardware.org/?probe=5d7e68e3ae) | Aug 14, 2023 |
| Acer          | Swift SF515-51T             | [9271029425](https://linux-hardware.org/?probe=9271029425) | Aug 13, 2023 |
| Apple         | MacBookPro6,2               | [7c62a05800](https://linux-hardware.org/?probe=7c62a05800) | Aug 12, 2023 |
| Acer          | TravelMate B113             | [5d3d27c8bb](https://linux-hardware.org/?probe=5d3d27c8bb) | Aug 12, 2023 |
| HP            | EliteBook 2560p             | [0b5cf409d8](https://linux-hardware.org/?probe=0b5cf409d8) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [80f2f711d8](https://linux-hardware.org/?probe=80f2f711d8) | Aug 10, 2023 |
| HP            | ProBook 4310s               | [ac0c1be078](https://linux-hardware.org/?probe=ac0c1be078) | Aug 09, 2023 |
| HP            | EliteBook 850 G3            | [04a319c904](https://linux-hardware.org/?probe=04a319c904) | Aug 09, 2023 |
| Apple         | MacBookPro8,1               | [6165a2d50e](https://linux-hardware.org/?probe=6165a2d50e) | Aug 08, 2023 |
| HP            | G60                         | [7f3b9aec85](https://linux-hardware.org/?probe=7f3b9aec85) | Aug 07, 2023 |
| Lenovo        | ThinkPad X201 Tablet 298... | [7132bbeb85](https://linux-hardware.org/?probe=7132bbeb85) | Aug 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2b8f90f79d](https://linux-hardware.org/?probe=2b8f90f79d) | Aug 03, 2023 |
| Packard Be... | EasyNote LS11HR             | [6e79cf1bf0](https://linux-hardware.org/?probe=6e79cf1bf0) | Aug 03, 2023 |
| Acer          | Predator G3-571             | [fc950e8651](https://linux-hardware.org/?probe=fc950e8651) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | [73e1dd94b2](https://linux-hardware.org/?probe=73e1dd94b2) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2f4ed3cb1f](https://linux-hardware.org/?probe=2f4ed3cb1f) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | [a13fd4044e](https://linux-hardware.org/?probe=a13fd4044e) | Aug 01, 2023 |
| SHENZHEN Y... | A8S PRO                     | [829a4178a5](https://linux-hardware.org/?probe=829a4178a5) | Jul 30, 2023 |
| Apple         | MacBookPro11,3              | [c7572ce663](https://linux-hardware.org/?probe=c7572ce663) | Jul 30, 2023 |
| Apple         | MacBookPro11,3              | [8ac9af1db8](https://linux-hardware.org/?probe=8ac9af1db8) | Jul 29, 2023 |
| Wortmann      | 1220624_1470150             | [b68bd8a80c](https://linux-hardware.org/?probe=b68bd8a80c) | Jul 29, 2023 |
| SHENZHEN Y... | A8S PRO                     | [08a6feda0e](https://linux-hardware.org/?probe=08a6feda0e) | Jul 28, 2023 |
| HP            | 255 G8 Notebook PC          | [c2e02d1490](https://linux-hardware.org/?probe=c2e02d1490) | Jul 24, 2023 |
| HP            | Pavilion dv7                | [a74719eac2](https://linux-hardware.org/?probe=a74719eac2) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a5359c62e0](https://linux-hardware.org/?probe=a5359c62e0) | Jul 20, 2023 |
| Alienware     | m15 R6                      | [93d5e98358](https://linux-hardware.org/?probe=93d5e98358) | Jul 20, 2023 |
| HP            | Notebook                    | [2ccf016245](https://linux-hardware.org/?probe=2ccf016245) | Jul 19, 2023 |
| Apple         | MacBookPro8,1               | [7dd13cea49](https://linux-hardware.org/?probe=7dd13cea49) | Jul 17, 2023 |
| Acer          | Aspire 7750G                | [c7d69d227a](https://linux-hardware.org/?probe=c7d69d227a) | Jul 17, 2023 |
| Google        | Phaser360                   | [1e66458514](https://linux-hardware.org/?probe=1e66458514) | Jul 17, 2023 |
| HP            | ENVY 15                     | [a173db4ea1](https://linux-hardware.org/?probe=a173db4ea1) | Jul 17, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | [2c05f1a964](https://linux-hardware.org/?probe=2c05f1a964) | Jul 16, 2023 |
| Acer          | Aspire A315-32              | [7044de848c](https://linux-hardware.org/?probe=7044de848c) | Jul 15, 2023 |
| Apple         | MacBookPro8,1               | [74420b09b7](https://linux-hardware.org/?probe=74420b09b7) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1a0add8887](https://linux-hardware.org/?probe=1a0add8887) | Jul 11, 2023 |
| HP            | ENVY 15                     | [3ccdaf4d4e](https://linux-hardware.org/?probe=3ccdaf4d4e) | Jul 10, 2023 |
| Apple         | MacBookPro12,1              | [8877b51b89](https://linux-hardware.org/?probe=8877b51b89) | Jul 08, 2023 |
| HP            | Laptop 14-dq0xxx            | [bb065938a5](https://linux-hardware.org/?probe=bb065938a5) | Jul 07, 2023 |
| Apple         | MacBookPro8,1               | [ee299280f8](https://linux-hardware.org/?probe=ee299280f8) | Jul 07, 2023 |
| Dell          | Latitude E7270              | [406e4a918b](https://linux-hardware.org/?probe=406e4a918b) | Jul 06, 2023 |
| Intel Clie... | LAPBC710                    | [fd97a27365](https://linux-hardware.org/?probe=fd97a27365) | Jul 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [2e4a653435](https://linux-hardware.org/?probe=2e4a653435) | Jul 04, 2023 |
| HP            | Pavilion dv7                | [09627980f5](https://linux-hardware.org/?probe=09627980f5) | Jul 04, 2023 |
| Apple         | MacBookPro9,2               | [f7a7db0702](https://linux-hardware.org/?probe=f7a7db0702) | Jul 04, 2023 |
| GPD           | MicroPC                     | [f666f4c574](https://linux-hardware.org/?probe=f666f4c574) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 23254W5       | [5842896b76](https://linux-hardware.org/?probe=5842896b76) | Jul 03, 2023 |
| Acer          | Aspire 7750G                | [ec3012e08e](https://linux-hardware.org/?probe=ec3012e08e) | Jul 01, 2023 |
| HP            | Laptop 17-by3xxx            | [8bfe14749f](https://linux-hardware.org/?probe=8bfe14749f) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430 2349OB6       | [f2f66bb9d0](https://linux-hardware.org/?probe=f2f66bb9d0) | Jun 29, 2023 |
| Dell          | Inspiron 3501               | [afc9f56d8d](https://linux-hardware.org/?probe=afc9f56d8d) | Jun 28, 2023 |
| Dell          | Precision M6600             | [bcc4817c8b](https://linux-hardware.org/?probe=bcc4817c8b) | Jun 27, 2023 |
| Dell          | Inspiron 15-3567            | [614687bba4](https://linux-hardware.org/?probe=614687bba4) | Jun 25, 2023 |
| Dell          | Latitude E5470              | [e10153b4c9](https://linux-hardware.org/?probe=e10153b4c9) | Jun 23, 2023 |
| Toshiba       | TECRA R850                  | [a75e6d35da](https://linux-hardware.org/?probe=a75e6d35da) | Jun 21, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [293b8783a3](https://linux-hardware.org/?probe=293b8783a3) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [2f452cfce0](https://linux-hardware.org/?probe=2f452cfce0) | Jun 20, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [f49534dfa4](https://linux-hardware.org/?probe=f49534dfa4) | Jun 19, 2023 |
| ASUSTek       | X555LA                      | [a57885e16c](https://linux-hardware.org/?probe=a57885e16c) | Jun 18, 2023 |
| ASUSTek       | X555LA                      | [782fa74afe](https://linux-hardware.org/?probe=782fa74afe) | Jun 14, 2023 |
| Razer         | Blade Stealth               | [f218e04a1c](https://linux-hardware.org/?probe=f218e04a1c) | Jun 14, 2023 |
| Dell          | Latitude 5590               | [56f8f9bbaf](https://linux-hardware.org/?probe=56f8f9bbaf) | Jun 14, 2023 |
| Dell          | Latitude 5590               | [f6347f5d6b](https://linux-hardware.org/?probe=f6347f5d6b) | Jun 11, 2023 |
| Apple         | MacBookPro8,1               | [d487214e2a](https://linux-hardware.org/?probe=d487214e2a) | Jun 08, 2023 |
| Apple         | MacBookPro11,1              | [6c62565787](https://linux-hardware.org/?probe=6c62565787) | Jun 07, 2023 |
| ASUSTek       | G750JM                      | [b2281ad2cb](https://linux-hardware.org/?probe=b2281ad2cb) | Jun 06, 2023 |
| Toshiba       | TECRA Z40-C                 | [1ebf23281e](https://linux-hardware.org/?probe=1ebf23281e) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | [274b78cda3](https://linux-hardware.org/?probe=274b78cda3) | Jun 03, 2023 |
| Apple         | MacBookAir7,2               | [119fd5249f](https://linux-hardware.org/?probe=119fd5249f) | Jun 03, 2023 |
| HUAWEI        | BOD-WXX9                    | [532dea434a](https://linux-hardware.org/?probe=532dea434a) | Jun 02, 2023 |
| HP            | G62                         | [f2600c2f4b](https://linux-hardware.org/?probe=f2600c2f4b) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS08H00    | [71208c2344](https://linux-hardware.org/?probe=71208c2344) | Jun 01, 2023 |
| Dell          | Latitude E5540              | [83d7c0065d](https://linux-hardware.org/?probe=83d7c0065d) | Jun 01, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [827e0203ac](https://linux-hardware.org/?probe=827e0203ac) | May 31, 2023 |
| ASUSTek       | X550WA                      | [864236b0c9](https://linux-hardware.org/?probe=864236b0c9) | May 29, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [62764248cb](https://linux-hardware.org/?probe=62764248cb) | May 29, 2023 |
| PCBOX         | Kant                        | [1e2f772d05](https://linux-hardware.org/?probe=1e2f772d05) | May 29, 2023 |
| HP            | ProBook 440 G6              | [35d14ed328](https://linux-hardware.org/?probe=35d14ed328) | May 29, 2023 |
| HP            | ProBook 440 G6              | [36a3563566](https://linux-hardware.org/?probe=36a3563566) | May 29, 2023 |
| Lenovo        | G580 20150                  | [146383f227](https://linux-hardware.org/?probe=146383f227) | May 27, 2023 |
| HP            | ProBook 4540s               | [124c8183a8](https://linux-hardware.org/?probe=124c8183a8) | May 26, 2023 |
| Acer          | Aspire 7750G                | [1ddb5fe9a0](https://linux-hardware.org/?probe=1ddb5fe9a0) | May 26, 2023 |
| Dell          | Precision 5530              | [702b4d7914](https://linux-hardware.org/?probe=702b4d7914) | May 26, 2023 |
| Dell          | Latitude E5470              | [6054d2ee2b](https://linux-hardware.org/?probe=6054d2ee2b) | May 25, 2023 |
| Acer          | Aspire 7750G                | [4ddad1d733](https://linux-hardware.org/?probe=4ddad1d733) | May 24, 2023 |
| HP            | ProBook 4310s               | [1a32d434c0](https://linux-hardware.org/?probe=1a32d434c0) | May 21, 2023 |
| Acer          | Aspire 7750G                | [61ebf173dc](https://linux-hardware.org/?probe=61ebf173dc) | May 21, 2023 |
| HP            | Laptop 17-by3xxx            | [7f15c1b9e3](https://linux-hardware.org/?probe=7f15c1b9e3) | May 21, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [ff730fcbf6](https://linux-hardware.org/?probe=ff730fcbf6) | May 20, 2023 |
| HP            | Pavilion Notebook           | [73d62695e4](https://linux-hardware.org/?probe=73d62695e4) | May 18, 2023 |
| HP            | Pavilion Notebook           | [56aa17165e](https://linux-hardware.org/?probe=56aa17165e) | May 18, 2023 |
| HP            | ProBook 4310s               | [dfcb51e697](https://linux-hardware.org/?probe=dfcb51e697) | May 17, 2023 |
| HP            | EliteBook 840 14 inch G9... | [004f548439](https://linux-hardware.org/?probe=004f548439) | May 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8fb1a89166](https://linux-hardware.org/?probe=8fb1a89166) | May 17, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [155b921e10](https://linux-hardware.org/?probe=155b921e10) | May 13, 2023 |
| Multilaser    | PC150                       | [0a59946a8f](https://linux-hardware.org/?probe=0a59946a8f) | May 12, 2023 |
| Alienware     | m15 R6                      | [bfa28cc7bd](https://linux-hardware.org/?probe=bfa28cc7bd) | May 11, 2023 |
| HUAWEI        | KLVL-WXX9                   | [68720e9d6b](https://linux-hardware.org/?probe=68720e9d6b) | May 10, 2023 |
| Acer          | Aspire E3-111               | [1060697095](https://linux-hardware.org/?probe=1060697095) | May 10, 2023 |
| Dell          | Inspiron 15 5510            | [174505e46f](https://linux-hardware.org/?probe=174505e46f) | May 10, 2023 |
| HP            | Laptop 15s-eq0xxx           | [58000b3a57](https://linux-hardware.org/?probe=58000b3a57) | May 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [1b0786ec5e](https://linux-hardware.org/?probe=1b0786ec5e) | May 07, 2023 |
| HONOR         | BMH-WCX9                    | [ea0b55ed61](https://linux-hardware.org/?probe=ea0b55ed61) | May 07, 2023 |
| HONOR         | BMH-WCX9                    | [df06b3c5b3](https://linux-hardware.org/?probe=df06b3c5b3) | May 07, 2023 |
| MSI           | GE62VR 6RF                  | [bac71eb24d](https://linux-hardware.org/?probe=bac71eb24d) | May 06, 2023 |
| Lenovo        | ThinkPad P51s 20HB001TUS    | [eac4ebdef0](https://linux-hardware.org/?probe=eac4ebdef0) | May 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [834d2304aa](https://linux-hardware.org/?probe=834d2304aa) | May 06, 2023 |
| Clevo         | NL41MU2                     | [6a80029392](https://linux-hardware.org/?probe=6a80029392) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [fe61386871](https://linux-hardware.org/?probe=fe61386871) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [764f38bb65](https://linux-hardware.org/?probe=764f38bb65) | May 05, 2023 |
| HP            | ProBook 450 G6              | [c5927045a3](https://linux-hardware.org/?probe=c5927045a3) | May 04, 2023 |
| MSI           | GE62VR 6RF                  | [97acececd3](https://linux-hardware.org/?probe=97acececd3) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [346cbe0e48](https://linux-hardware.org/?probe=346cbe0e48) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [afafdbce36](https://linux-hardware.org/?probe=afafdbce36) | Apr 28, 2023 |
| Apple         | MacBookPro5,2               | [c188ae4d7d](https://linux-hardware.org/?probe=c188ae4d7d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| MSI           | GE62VR 6RF                  | [2a9fcae8c3](https://linux-hardware.org/?probe=2a9fcae8c3) | Apr 28, 2023 |
| HUAWEI        | BOD-WXX9                    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| HP            | EliteBook 2560p             | [ce35b62e32](https://linux-hardware.org/?probe=ce35b62e32) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| MSI           | PE70 6QE                    | [87c8761eff](https://linux-hardware.org/?probe=87c8761eff) | Apr 27, 2023 |
| HP            | 250 G8 Notebook PC          | [b03cd2f2d2](https://linux-hardware.org/?probe=b03cd2f2d2) | Apr 26, 2023 |
| MSI           | PE70 6QE                    | [53dd8334ac](https://linux-hardware.org/?probe=53dd8334ac) | Apr 26, 2023 |
| Lenovo        | G580 20150                  | [5d8b07dbbd](https://linux-hardware.org/?probe=5d8b07dbbd) | Apr 25, 2023 |
| HP            | Pavilion dv7                | [e8318168c4](https://linux-hardware.org/?probe=e8318168c4) | Apr 25, 2023 |
| HP            | Pavilion dv7                | [8b90982317](https://linux-hardware.org/?probe=8b90982317) | Apr 23, 2023 |
| Lenovo        | V17 G2 ITL 82NX             | [241411df47](https://linux-hardware.org/?probe=241411df47) | Apr 23, 2023 |
| Dell          | Latitude E4300              | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | [763953fb60](https://linux-hardware.org/?probe=763953fb60) | Apr 22, 2023 |
| HP            | Pavilion g6                 | [4d60e2b7da](https://linux-hardware.org/?probe=4d60e2b7da) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | [94bf014457](https://linux-hardware.org/?probe=94bf014457) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | [2ebc6a2f61](https://linux-hardware.org/?probe=2ebc6a2f61) | Apr 17, 2023 |
| Apple         | MacBookAir7,1               | [f4b3f86485](https://linux-hardware.org/?probe=f4b3f86485) | Apr 16, 2023 |
| Apple         | MacBookPro9,2               | [ff6dbdcc10](https://linux-hardware.org/?probe=ff6dbdcc10) | Apr 15, 2023 |
| MSI           | PE70 6QE                    | [936a7d1fe3](https://linux-hardware.org/?probe=936a7d1fe3) | Apr 15, 2023 |
| Dell          | Latitude 5420               | [4c6427b3fc](https://linux-hardware.org/?probe=4c6427b3fc) | Apr 14, 2023 |
| Apple         | MacBookAir3,2               | [c750ece414](https://linux-hardware.org/?probe=c750ece414) | Apr 12, 2023 |
| Notebook      | NLx0MU                      | [6d04c51285](https://linux-hardware.org/?probe=6d04c51285) | Apr 11, 2023 |
| Dell          | Latitude E5570              | [81eaf54f19](https://linux-hardware.org/?probe=81eaf54f19) | Apr 07, 2023 |
| Apple         | MacBookPro10,1              | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| HUAWEI        | BOD-WXX9                    | [3f9238067d](https://linux-hardware.org/?probe=3f9238067d) | Apr 04, 2023 |
| HP            | Pavilion 15                 | [1a3e968dff](https://linux-hardware.org/?probe=1a3e968dff) | Apr 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f7f207f61c](https://linux-hardware.org/?probe=f7f207f61c) | Apr 02, 2023 |
| Multilaser    | PC150                       | [0bcb0ca7ba](https://linux-hardware.org/?probe=0bcb0ca7ba) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | [e06d57c27a](https://linux-hardware.org/?probe=e06d57c27a) | Apr 01, 2023 |
| HUAWEI        | NBD-WXX9                    | [d4c718bdab](https://linux-hardware.org/?probe=d4c718bdab) | Apr 01, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| Dell          | Latitude E7440              | [1159c854cd](https://linux-hardware.org/?probe=1159c854cd) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | [a9a8004509](https://linux-hardware.org/?probe=a9a8004509) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | [1dccfbe9f4](https://linux-hardware.org/?probe=1dccfbe9f4) | Mar 29, 2023 |
| Dell          | Latitude 5420               | [d714c46c4f](https://linux-hardware.org/?probe=d714c46c4f) | Mar 29, 2023 |
| HP            | Laptop 15-bs2xx             | [b6160f7688](https://linux-hardware.org/?probe=b6160f7688) | Mar 27, 2023 |
| HP            | Laptop 15-bs2xx             | [85966e5691](https://linux-hardware.org/?probe=85966e5691) | Mar 27, 2023 |
| Lenovo        | V510-15IKB 80WQ             | [8df3d7641e](https://linux-hardware.org/?probe=8df3d7641e) | Mar 26, 2023 |
| Toshiba       | TECRA Z40-C                 | [39995c1c00](https://linux-hardware.org/?probe=39995c1c00) | Mar 24, 2023 |
| Dell          | Latitude E7440              | [1a986dbeb8](https://linux-hardware.org/?probe=1a986dbeb8) | Mar 24, 2023 |
| Lenovo        | G580 20150                  | [489b8775b6](https://linux-hardware.org/?probe=489b8775b6) | Mar 22, 2023 |
| HONOR         | HYM-WXX                     | [df318ed208](https://linux-hardware.org/?probe=df318ed208) | Mar 21, 2023 |
| Lenovo        | V17 G2 ITL 82NX             | [0365bfc4ca](https://linux-hardware.org/?probe=0365bfc4ca) | Mar 20, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [e40cf4f577](https://linux-hardware.org/?probe=e40cf4f577) | Mar 18, 2023 |
| Dell          | Latitude E5570              | [a15d1b43ca](https://linux-hardware.org/?probe=a15d1b43ca) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [dd07b0c3b3](https://linux-hardware.org/?probe=dd07b0c3b3) | Mar 17, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [421f6945e6](https://linux-hardware.org/?probe=421f6945e6) | Mar 16, 2023 |
| Dell          | G3 3590                     | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | [03e5d43f27](https://linux-hardware.org/?probe=03e5d43f27) | Mar 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | [4c49d73583](https://linux-hardware.org/?probe=4c49d73583) | Mar 15, 2023 |
| Apple         | MacBookPro5,5               | [c6ff6d14a0](https://linux-hardware.org/?probe=c6ff6d14a0) | Mar 15, 2023 |
| Acer          | Aspire V3-771               | [28f8273eb5](https://linux-hardware.org/?probe=28f8273eb5) | Mar 15, 2023 |
| MSI           | GT72 2QE                    | [b3c4766473](https://linux-hardware.org/?probe=b3c4766473) | Mar 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | [a2ee9a2818](https://linux-hardware.org/?probe=a2ee9a2818) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK A359               | [0fa1ebbc11](https://linux-hardware.org/?probe=0fa1ebbc11) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK A359               | [f977012127](https://linux-hardware.org/?probe=f977012127) | Mar 11, 2023 |
| HUAWEI        | KLVL-WXX9                   | [44db3bc5ec](https://linux-hardware.org/?probe=44db3bc5ec) | Mar 11, 2023 |
| Apple         | MacBookPro11,2              | [fce6120754](https://linux-hardware.org/?probe=fce6120754) | Mar 11, 2023 |
| Acer          | Aspire A715-72G             | [32b2d1b194](https://linux-hardware.org/?probe=32b2d1b194) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [82b5297ab8](https://linux-hardware.org/?probe=82b5297ab8) | Mar 11, 2023 |
| Toshiba       | TECRA Z40-C                 | [a4ba2ff90e](https://linux-hardware.org/?probe=a4ba2ff90e) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Sony          | VPCEH2C5E                   | [adf4a69310](https://linux-hardware.org/?probe=adf4a69310) | Mar 07, 2023 |
| Sony          | VPCEH2C5E                   | [9e5b625dda](https://linux-hardware.org/?probe=9e5b625dda) | Mar 07, 2023 |
| ASUSTek       | K55A                        | [15899be9a8](https://linux-hardware.org/?probe=15899be9a8) | Mar 06, 2023 |
| GPU Compan... | GWTN156-11                  | [5afd8e3f42](https://linux-hardware.org/?probe=5afd8e3f42) | Mar 04, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [fe903be37c](https://linux-hardware.org/?probe=fe903be37c) | Mar 04, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [817b72f78f](https://linux-hardware.org/?probe=817b72f78f) | Mar 02, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [053c6d5368](https://linux-hardware.org/?probe=053c6d5368) | Mar 02, 2023 |
| Acer          | Aspire A315-32              | [5203ce8a41](https://linux-hardware.org/?probe=5203ce8a41) | Mar 02, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [fa757fb12a](https://linux-hardware.org/?probe=fa757fb12a) | Mar 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [1025a9748f](https://linux-hardware.org/?probe=1025a9748f) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | [e189c60b09](https://linux-hardware.org/?probe=e189c60b09) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | [3883ba28c7](https://linux-hardware.org/?probe=3883ba28c7) | Mar 01, 2023 |
| Apple         | MacBookAir3,1               | [573644760d](https://linux-hardware.org/?probe=573644760d) | Feb 28, 2023 |
| Fujitsu       | LIFEBOOK E744               | [e331c5e257](https://linux-hardware.org/?probe=e331c5e257) | Feb 27, 2023 |
| Acer          | Aspire E5-771               | [73c974942f](https://linux-hardware.org/?probe=73c974942f) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a66f75c107](https://linux-hardware.org/?probe=a66f75c107) | Feb 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [50a16e7924](https://linux-hardware.org/?probe=50a16e7924) | Feb 25, 2023 |
| HP            | ProBook 430 G4              | [b815c24c07](https://linux-hardware.org/?probe=b815c24c07) | Feb 24, 2023 |
| HP            | ProBook 430 G4              | [e578b951f9](https://linux-hardware.org/?probe=e578b951f9) | Feb 24, 2023 |
| HP            | ProBook 430 G4              | [0dc5add67b](https://linux-hardware.org/?probe=0dc5add67b) | Feb 24, 2023 |
| Lenovo        | ThinkPad T400s 2808D9G      | [b101883e65](https://linux-hardware.org/?probe=b101883e65) | Feb 24, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | [0a3d750f36](https://linux-hardware.org/?probe=0a3d750f36) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ddd8c34644](https://linux-hardware.org/?probe=ddd8c34644) | Feb 22, 2023 |
| Toshiba       | Satellite C50D-A            | [3e9201a0fe](https://linux-hardware.org/?probe=3e9201a0fe) | Feb 20, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | [c79a8f48f9](https://linux-hardware.org/?probe=c79a8f48f9) | Feb 20, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | [7ee9e59831](https://linux-hardware.org/?probe=7ee9e59831) | Feb 20, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [2751aac3e0](https://linux-hardware.org/?probe=2751aac3e0) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| HP            | 550                         | [81b67f211d](https://linux-hardware.org/?probe=81b67f211d) | Feb 15, 2023 |
| Dell          | XPS 15 9560                 | [150c1de326](https://linux-hardware.org/?probe=150c1de326) | Feb 15, 2023 |
| Apple         | MacBook4,1                  | [e8a460c42c](https://linux-hardware.org/?probe=e8a460c42c) | Feb 15, 2023 |
| Apple         | MacBook4,1                  | [a92df0196e](https://linux-hardware.org/?probe=a92df0196e) | Feb 15, 2023 |
| HP            | EliteBook 8460p             | [92ab9b2e0d](https://linux-hardware.org/?probe=92ab9b2e0d) | Feb 14, 2023 |
| Acer          | Aspire V3-771               | [f22c83d683](https://linux-hardware.org/?probe=f22c83d683) | Feb 14, 2023 |
| HP            | EliteBook 8760w             | [456d7c61ce](https://linux-hardware.org/?probe=456d7c61ce) | Feb 14, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [12431d8083](https://linux-hardware.org/?probe=12431d8083) | Feb 14, 2023 |
| HP            | G62                         | [e32c4fdd93](https://linux-hardware.org/?probe=e32c4fdd93) | Feb 13, 2023 |
| Acer          | Extensa 5230                | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | [a1d85b3098](https://linux-hardware.org/?probe=a1d85b3098) | Feb 10, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [9de542dff7](https://linux-hardware.org/?probe=9de542dff7) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | [6e8ed5d5d6](https://linux-hardware.org/?probe=6e8ed5d5d6) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| HP            | Laptop 15-dy2xxx            | [b906f960a0](https://linux-hardware.org/?probe=b906f960a0) | Feb 08, 2023 |
| Unknown       | Unknown                     | [af50508abe](https://linux-hardware.org/?probe=af50508abe) | Feb 07, 2023 |
| HP            | Laptop 14-bs0xx             | [c3607bb4c2](https://linux-hardware.org/?probe=c3607bb4c2) | Feb 07, 2023 |
| HP            | Laptop 17-by3xxx            | [07ea9d3c2f](https://linux-hardware.org/?probe=07ea9d3c2f) | Feb 06, 2023 |
| Dell          | Latitude E6400              | [61e0a7ffe7](https://linux-hardware.org/?probe=61e0a7ffe7) | Feb 05, 2023 |
| Acer          | Aspire E5-575G              | [30e2a88930](https://linux-hardware.org/?probe=30e2a88930) | Feb 05, 2023 |
| Acer          | Aspire 8935G                | [10f8560601](https://linux-hardware.org/?probe=10f8560601) | Feb 05, 2023 |
| Acer          | Aspire 8935G                | [be37cc70f5](https://linux-hardware.org/?probe=be37cc70f5) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | [8d67e1438d](https://linux-hardware.org/?probe=8d67e1438d) | Feb 05, 2023 |
| Apple         | MacBookPro11,3              | [8bdb86b164](https://linux-hardware.org/?probe=8bdb86b164) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | [9d397c2187](https://linux-hardware.org/?probe=9d397c2187) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | [7b676dec23](https://linux-hardware.org/?probe=7b676dec23) | Feb 04, 2023 |
| Dell          | Vostro 3460                 | [8aa57f1d6d](https://linux-hardware.org/?probe=8aa57f1d6d) | Feb 03, 2023 |
| Dell          | Vostro 3460                 | [78919f6127](https://linux-hardware.org/?probe=78919f6127) | Feb 03, 2023 |
| Alienware     | x17 R2                      | [474a70c148](https://linux-hardware.org/?probe=474a70c148) | Feb 03, 2023 |
| Sony          | SVF1521O4E                  | [e2d47879d4](https://linux-hardware.org/?probe=e2d47879d4) | Feb 02, 2023 |
| Acer          | Aspire one 1-132            | [d66a972aa9](https://linux-hardware.org/?probe=d66a972aa9) | Feb 02, 2023 |
| Lenovo        | ThinkPad X230 23259S9       | [3d9e74535f](https://linux-hardware.org/?probe=3d9e74535f) | Feb 01, 2023 |
| Apple         | MacBookAir6,2               | [2261a77abb](https://linux-hardware.org/?probe=2261a77abb) | Feb 01, 2023 |
| Dell          | XPS 13 9360                 | [9037e30b54](https://linux-hardware.org/?probe=9037e30b54) | Jan 30, 2023 |
| Apple         | MacBookPro11,3              | [b7cec06bcb](https://linux-hardware.org/?probe=b7cec06bcb) | Jan 30, 2023 |
| Sony          | VPCSB11FX                   | [7659c1ba93](https://linux-hardware.org/?probe=7659c1ba93) | Jan 29, 2023 |
| HUAWEI        | MACHD-WXX9                  | [cac5b8faa5](https://linux-hardware.org/?probe=cac5b8faa5) | Jan 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [c5168e6b33](https://linux-hardware.org/?probe=c5168e6b33) | Jan 27, 2023 |
| Sony          | SVE1711C5E                  | [73977968f5](https://linux-hardware.org/?probe=73977968f5) | Jan 27, 2023 |
| Sony          | SVE1711C5E                  | [d526ae42aa](https://linux-hardware.org/?probe=d526ae42aa) | Jan 27, 2023 |
| HP            | EliteBook 2560p             | [d5eae98224](https://linux-hardware.org/?probe=d5eae98224) | Jan 25, 2023 |
| Dell          | G3 3500                     | [e81b4d5e46](https://linux-hardware.org/?probe=e81b4d5e46) | Jan 22, 2023 |
| ASUSTek       | X540UA                      | [dda62597f7](https://linux-hardware.org/?probe=dda62597f7) | Jan 21, 2023 |
| Acer          | TravelMate 5735Z            | [712fdb1fa7](https://linux-hardware.org/?probe=712fdb1fa7) | Jan 20, 2023 |
| Acer          | TravelMate 5735Z            | [5b1b812b6e](https://linux-hardware.org/?probe=5b1b812b6e) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [032ac1d52e](https://linux-hardware.org/?probe=032ac1d52e) | Jan 18, 2023 |
| Apple         | MacBookPro8,2               | [271f6a7e85](https://linux-hardware.org/?probe=271f6a7e85) | Jan 17, 2023 |
| HP            | ProBook 455R G6             | [6ca9f4f6c0](https://linux-hardware.org/?probe=6ca9f4f6c0) | Jan 15, 2023 |
| Apple         | MacBookAir6,2               | [2931eab7f7](https://linux-hardware.org/?probe=2931eab7f7) | Jan 15, 2023 |
| Star Labs     | StarBook                    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Chuwi         | AeroBook Pro                | [13da35b0f7](https://linux-hardware.org/?probe=13da35b0f7) | Jan 15, 2023 |
| Lenovo        | Y50-70 20378                | [64ec4b6816](https://linux-hardware.org/?probe=64ec4b6816) | Jan 12, 2023 |
| Lenovo        | Y50-70 20378                | [9cd68b4513](https://linux-hardware.org/?probe=9cd68b4513) | Jan 11, 2023 |
| HP            | ProBook 650 G1              | [1dba72668b](https://linux-hardware.org/?probe=1dba72668b) | Jan 10, 2023 |
| HP            | ProBook 650 G1              | [e6d3982bc0](https://linux-hardware.org/?probe=e6d3982bc0) | Jan 10, 2023 |
| Avell High... | B.ON                        | [23b5b8565e](https://linux-hardware.org/?probe=23b5b8565e) | Jan 10, 2023 |
| Notebook      | NLx0MU                      | [69b46423cb](https://linux-hardware.org/?probe=69b46423cb) | Jan 08, 2023 |
| Notebook      | NLx0MU                      | [e43de3e94e](https://linux-hardware.org/?probe=e43de3e94e) | Jan 08, 2023 |
| HUAWEI        | MACHD-WXX9                  | [3e870855db](https://linux-hardware.org/?probe=3e870855db) | Jan 08, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [b8e1b2ec8e](https://linux-hardware.org/?probe=b8e1b2ec8e) | Jan 07, 2023 |
| Dell          | XPS 15 9510                 | [1893fb2388](https://linux-hardware.org/?probe=1893fb2388) | Jan 06, 2023 |
| Dell          | XPS 15 9510                 | [c3fbbaf7de](https://linux-hardware.org/?probe=c3fbbaf7de) | Jan 06, 2023 |
| Apple         | MacBookPro8,1               | [4641833cab](https://linux-hardware.org/?probe=4641833cab) | Jan 06, 2023 |
| Lenovo        | ThinkPad T480 20L5000YUS    | [4c735329b6](https://linux-hardware.org/?probe=4c735329b6) | Jan 05, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [3a3164f63f](https://linux-hardware.org/?probe=3a3164f63f) | Jan 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2c6b6c2558](https://linux-hardware.org/?probe=2c6b6c2558) | Jan 04, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [c7d37a7616](https://linux-hardware.org/?probe=c7d37a7616) | Jan 04, 2023 |
| Acer          | TravelMate 5735Z            | [9fa5978af4](https://linux-hardware.org/?probe=9fa5978af4) | Jan 01, 2023 |
| Dell          | System XPS L702X            | [7030c340cc](https://linux-hardware.org/?probe=7030c340cc) | Dec 31, 2022 |
| Chuwi         | HeroBook                    | [1664994b07](https://linux-hardware.org/?probe=1664994b07) | Dec 30, 2022 |
| HP            | ProBook 455R G6             | [71c9651ee2](https://linux-hardware.org/?probe=71c9651ee2) | Dec 30, 2022 |
| AMI           | F3C2                        | [ed7d4a2a13](https://linux-hardware.org/?probe=ed7d4a2a13) | Dec 30, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [5e094b34a5](https://linux-hardware.org/?probe=5e094b34a5) | Dec 29, 2022 |
| Acer          | Aspire A315-53              | [9c28036440](https://linux-hardware.org/?probe=9c28036440) | Dec 29, 2022 |
| Apple         | MacBookPro8,1               | [7b03f438db](https://linux-hardware.org/?probe=7b03f438db) | Dec 28, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [f5c5147826](https://linux-hardware.org/?probe=f5c5147826) | Dec 28, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [8dfcf5860f](https://linux-hardware.org/?probe=8dfcf5860f) | Dec 28, 2022 |
| Lenovo        | ThinkPad T430 23448AG       | [00ba06cfd1](https://linux-hardware.org/?probe=00ba06cfd1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b6413f9cf2](https://linux-hardware.org/?probe=b6413f9cf2) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [4ddf1fecb8](https://linux-hardware.org/?probe=4ddf1fecb8) | Dec 28, 2022 |
| Lenovo        | ThinkPad T430 23448AG       | [a570034bbc](https://linux-hardware.org/?probe=a570034bbc) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | [a1e4dd02b2](https://linux-hardware.org/?probe=a1e4dd02b2) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | [cedf39754e](https://linux-hardware.org/?probe=cedf39754e) | Dec 27, 2022 |
| Acer          | Aspire 7741                 | [5ef8e01957](https://linux-hardware.org/?probe=5ef8e01957) | Dec 27, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | [cc7b02033a](https://linux-hardware.org/?probe=cc7b02033a) | Dec 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [6de981f1fc](https://linux-hardware.org/?probe=6de981f1fc) | Dec 24, 2022 |
| Avell High... | B.ON                        | [ea8a4babbf](https://linux-hardware.org/?probe=ea8a4babbf) | Dec 24, 2022 |
| Lenovo        | ThinkPad X201 3680HB1       | [41e1719d61](https://linux-hardware.org/?probe=41e1719d61) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680HB1       | [01e9dfa8b8](https://linux-hardware.org/?probe=01e9dfa8b8) | Dec 22, 2022 |
| Positivo      | S14SL01                     | [476e8a784c](https://linux-hardware.org/?probe=476e8a784c) | Dec 21, 2022 |
| Positivo      | S14SL01                     | [08e3a4d7f2](https://linux-hardware.org/?probe=08e3a4d7f2) | Dec 21, 2022 |
| HP            | EliteBook Folio 1040 G3     | [3d89cf5c71](https://linux-hardware.org/?probe=3d89cf5c71) | Dec 21, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [a285792280](https://linux-hardware.org/?probe=a285792280) | Dec 20, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [f777de4f53](https://linux-hardware.org/?probe=f777de4f53) | Dec 17, 2022 |
| HP            | Pavilion g6                 | [d1bfb26644](https://linux-hardware.org/?probe=d1bfb26644) | Dec 16, 2022 |
| HUAWEI        | NBM-WXX9                    | [a9f5b0866f](https://linux-hardware.org/?probe=a9f5b0866f) | Dec 16, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [4f1aa7401d](https://linux-hardware.org/?probe=4f1aa7401d) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [35d2e25287](https://linux-hardware.org/?probe=35d2e25287) | Dec 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [615d3e1599](https://linux-hardware.org/?probe=615d3e1599) | Dec 14, 2022 |
| MSI           | GF63 Thin 10SC              | [ed86ad34cf](https://linux-hardware.org/?probe=ed86ad34cf) | Dec 13, 2022 |
| MSI           | GF63 Thin 10SC              | [18c3d0d050](https://linux-hardware.org/?probe=18c3d0d050) | Dec 13, 2022 |
| HP            | Laptop 17-ca0xxx            | [0a7b9bd226](https://linux-hardware.org/?probe=0a7b9bd226) | Dec 12, 2022 |
| HP            | Laptop 17-ca0xxx            | [e2d976c5f4](https://linux-hardware.org/?probe=e2d976c5f4) | Dec 11, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [52546b1dd0](https://linux-hardware.org/?probe=52546b1dd0) | Dec 10, 2022 |
| HP            | ProBook 650 G1              | [46d77ce0b4](https://linux-hardware.org/?probe=46d77ce0b4) | Dec 09, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [1a1f2b375d](https://linux-hardware.org/?probe=1a1f2b375d) | Dec 05, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | 250 G7 Notebook PC          | [1002df8858](https://linux-hardware.org/?probe=1002df8858) | Dec 01, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [d95adc01a7](https://linux-hardware.org/?probe=d95adc01a7) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | [4d8bd1760a](https://linux-hardware.org/?probe=4d8bd1760a) | Nov 25, 2022 |
| Apple         | MacBook3,1                  | [404821c7d6](https://linux-hardware.org/?probe=404821c7d6) | Nov 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | [408158ed97](https://linux-hardware.org/?probe=408158ed97) | Nov 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [dce27f6d43](https://linux-hardware.org/?probe=dce27f6d43) | Nov 24, 2022 |
| ASUSTek       | 1001PX                      | [9626b2b4c5](https://linux-hardware.org/?probe=9626b2b4c5) | Nov 24, 2022 |
| Apple         | MacBookPro11,3              | [476415b4e4](https://linux-hardware.org/?probe=476415b4e4) | Nov 22, 2022 |
| Dell          | Latitude E6520              | [1801edca03](https://linux-hardware.org/?probe=1801edca03) | Nov 22, 2022 |
| Acer          | Aspire A315-51              | [3d8ef86616](https://linux-hardware.org/?probe=3d8ef86616) | Nov 21, 2022 |
| Lenovo        | G50-45 80E3                 | [680aac00bd](https://linux-hardware.org/?probe=680aac00bd) | Nov 21, 2022 |
| Apple         | MacBookPro12,1              | [9e16721568](https://linux-hardware.org/?probe=9e16721568) | Nov 17, 2022 |
| Dell          | Inspiron 5584               | [f11ce2dd6c](https://linux-hardware.org/?probe=f11ce2dd6c) | Nov 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d07cacacde](https://linux-hardware.org/?probe=d07cacacde) | Nov 15, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | [b6e353af2b](https://linux-hardware.org/?probe=b6e353af2b) | Nov 14, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | [c642a76e3e](https://linux-hardware.org/?probe=c642a76e3e) | Nov 14, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [32e8c529f0](https://linux-hardware.org/?probe=32e8c529f0) | Nov 14, 2022 |
| Medion        | E7220                       | [7d3df30772](https://linux-hardware.org/?probe=7d3df30772) | Nov 13, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fef97563a0](https://linux-hardware.org/?probe=fef97563a0) | Nov 13, 2022 |
| Apple         | MacBook3,1                  | [3bafc2796b](https://linux-hardware.org/?probe=3bafc2796b) | Nov 11, 2022 |
| Apple         | MacBookPro6,2               | [3c63d3fb1e](https://linux-hardware.org/?probe=3c63d3fb1e) | Nov 11, 2022 |
| Alienware     | m15 R6                      | [63b53e81ed](https://linux-hardware.org/?probe=63b53e81ed) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [22b8b36df5](https://linux-hardware.org/?probe=22b8b36df5) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [3e808157a3](https://linux-hardware.org/?probe=3e808157a3) | Nov 08, 2022 |
| Apple         | MacBookPro9,2               | [e9389bc87e](https://linux-hardware.org/?probe=e9389bc87e) | Nov 08, 2022 |
| Dell          | Studio 1558                 | [8be31a4335](https://linux-hardware.org/?probe=8be31a4335) | Nov 07, 2022 |
| Dell          | Inspiron 15-3567            | [390f51010e](https://linux-hardware.org/?probe=390f51010e) | Nov 06, 2022 |
| Packard Be... | EasyNote LS44HR             | [375b78c3f3](https://linux-hardware.org/?probe=375b78c3f3) | Nov 06, 2022 |
| Wortmann      | 1220624_1470150             | [2782ad2c3e](https://linux-hardware.org/?probe=2782ad2c3e) | Nov 05, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [505b2c2b5d](https://linux-hardware.org/?probe=505b2c2b5d) | Nov 04, 2022 |
| Sony          | VPCEA1S1R                   | [9dfb83587b](https://linux-hardware.org/?probe=9dfb83587b) | Nov 04, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [f8685beefa](https://linux-hardware.org/?probe=f8685beefa) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7d6d6c3c3a](https://linux-hardware.org/?probe=7d6d6c3c3a) | Nov 04, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | [e4d29df724](https://linux-hardware.org/?probe=e4d29df724) | Nov 02, 2022 |
| HP            | Pavilion dv5                | [fb23cec1a6](https://linux-hardware.org/?probe=fb23cec1a6) | Nov 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Laptop 17-ca3xxx            | [2c42913712](https://linux-hardware.org/?probe=2c42913712) | Oct 31, 2022 |
| MSI           | Modern 14 B10MW             | [cf2b620a60](https://linux-hardware.org/?probe=cf2b620a60) | Oct 31, 2022 |
| Toshiba       | TECRA A11                   | [10d2346f7c](https://linux-hardware.org/?probe=10d2346f7c) | Oct 30, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [f4c2d5224b](https://linux-hardware.org/?probe=f4c2d5224b) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [512acddb70](https://linux-hardware.org/?probe=512acddb70) | Oct 30, 2022 |
| Toshiba       | TECRA A11                   | [1af8ca0ac9](https://linux-hardware.org/?probe=1af8ca0ac9) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [9b90ea1d4d](https://linux-hardware.org/?probe=9b90ea1d4d) | Oct 27, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [13873c81b2](https://linux-hardware.org/?probe=13873c81b2) | Oct 24, 2022 |
| HP            | Laptop 15-bw0xx             | [cdd4d21000](https://linux-hardware.org/?probe=cdd4d21000) | Oct 24, 2022 |
| ASUSTek       | UX31A                       | [4b7e610e25](https://linux-hardware.org/?probe=4b7e610e25) | Oct 24, 2022 |
| Toshiba       | TECRA A11                   | [de0b3e96fa](https://linux-hardware.org/?probe=de0b3e96fa) | Oct 23, 2022 |
| Toshiba       | TECRA A11                   | [b91eedb26a](https://linux-hardware.org/?probe=b91eedb26a) | Oct 23, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [4a6e283158](https://linux-hardware.org/?probe=4a6e283158) | Oct 22, 2022 |
| Apple         | MacBookPro10,1              | [6354f13944](https://linux-hardware.org/?probe=6354f13944) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [484cb84d6b](https://linux-hardware.org/?probe=484cb84d6b) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [2dd84a41e8](https://linux-hardware.org/?probe=2dd84a41e8) | Oct 17, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [c5b6ba786e](https://linux-hardware.org/?probe=c5b6ba786e) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [23adba19e0](https://linux-hardware.org/?probe=23adba19e0) | Oct 15, 2022 |
| Dell          | Inspiron 15-3567            | [2b00bd7a92](https://linux-hardware.org/?probe=2b00bd7a92) | Oct 15, 2022 |
| HP            | Pavilion dv7                | [44ae8ac465](https://linux-hardware.org/?probe=44ae8ac465) | Oct 14, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [fd260f87a9](https://linux-hardware.org/?probe=fd260f87a9) | Oct 14, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [64cbdc6e2a](https://linux-hardware.org/?probe=64cbdc6e2a) | Oct 13, 2022 |
| MSI           | GE70 2QE                    | [2825343a52](https://linux-hardware.org/?probe=2825343a52) | Oct 13, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [8926251d64](https://linux-hardware.org/?probe=8926251d64) | Oct 11, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [db3419c5de](https://linux-hardware.org/?probe=db3419c5de) | Oct 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f06f54475b](https://linux-hardware.org/?probe=f06f54475b) | Oct 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [20ea012e04](https://linux-hardware.org/?probe=20ea012e04) | Oct 06, 2022 |
| Toshiba       | Satellite C855-1WX          | [78c5bb7120](https://linux-hardware.org/?probe=78c5bb7120) | Oct 06, 2022 |
| Lenovo        | V130-15IKB 81HN             | [823a068620](https://linux-hardware.org/?probe=823a068620) | Oct 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [c086a688f1](https://linux-hardware.org/?probe=c086a688f1) | Oct 02, 2022 |
| HUAWEI        | HVY-WXX9                    | [4ce296ba38](https://linux-hardware.org/?probe=4ce296ba38) | Sep 30, 2022 |
| Dell          | Vostro 5402                 | [57995ec944](https://linux-hardware.org/?probe=57995ec944) | Sep 30, 2022 |
| Google        | Blooglet                    | [44a9c6559f](https://linux-hardware.org/?probe=44a9c6559f) | Sep 29, 2022 |
| Medion        | Akoya E6422 MD99680         | [52c1708200](https://linux-hardware.org/?probe=52c1708200) | Sep 28, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [18ee2cafd6](https://linux-hardware.org/?probe=18ee2cafd6) | Sep 27, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [ffc2811bfe](https://linux-hardware.org/?probe=ffc2811bfe) | Sep 27, 2022 |
| Dell          | Latitude E6540              | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Dell          | Latitude E5450              | [8738ac7280](https://linux-hardware.org/?probe=8738ac7280) | Sep 26, 2022 |
| Apple         | MacBookAir6,2               | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Dell          | Inspiron 3493               | [b1f8d22e3e](https://linux-hardware.org/?probe=b1f8d22e3e) | Sep 25, 2022 |
| Apple         | MacBookAir6,2               | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [36c369745a](https://linux-hardware.org/?probe=36c369745a) | Sep 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6a0c80f635](https://linux-hardware.org/?probe=6a0c80f635) | Sep 22, 2022 |
| Acer          | Nitro AN515-54              | [7cf2d6a810](https://linux-hardware.org/?probe=7cf2d6a810) | Sep 20, 2022 |
| ASUSTek       | X555LAB                     | [71339e0cfb](https://linux-hardware.org/?probe=71339e0cfb) | Sep 19, 2022 |
| ASUSTek       | X555LAB                     | [a0acb674df](https://linux-hardware.org/?probe=a0acb674df) | Sep 19, 2022 |
| HP            | Laptop 15-bw0xx             | [94baca564e](https://linux-hardware.org/?probe=94baca564e) | Sep 19, 2022 |
| ASUSTek       | X555DG                      | [c46c229dfb](https://linux-hardware.org/?probe=c46c229dfb) | Sep 16, 2022 |
| ASUSTek       | X555DG                      | [e39d4a8247](https://linux-hardware.org/?probe=e39d4a8247) | Sep 16, 2022 |
| Clevo         | W54xEU                      | [bd0c5962bd](https://linux-hardware.org/?probe=bd0c5962bd) | Sep 15, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7861fa17bf](https://linux-hardware.org/?probe=7861fa17bf) | Sep 14, 2022 |
| MSI           | PS63 Modern 8RD             | [8fa2ea42ed](https://linux-hardware.org/?probe=8fa2ea42ed) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [2b12cc11f2](https://linux-hardware.org/?probe=2b12cc11f2) | Sep 13, 2022 |
| Dell          | Inspiron 5458               | [bd26475724](https://linux-hardware.org/?probe=bd26475724) | Sep 12, 2022 |
| Toshiba       | PORTEGE Z30-B               | [6b1829aad1](https://linux-hardware.org/?probe=6b1829aad1) | Sep 12, 2022 |
| Toshiba       | PORTEGE Z30-B               | [9ef29f2258](https://linux-hardware.org/?probe=9ef29f2258) | Sep 12, 2022 |
| HP            | ENVY m6                     | [b9de3b6e35](https://linux-hardware.org/?probe=b9de3b6e35) | Sep 11, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | [f2f2786b99](https://linux-hardware.org/?probe=f2f2786b99) | Sep 10, 2022 |
| Apple         | MacBookPro11,2              | [47708e7772](https://linux-hardware.org/?probe=47708e7772) | Sep 09, 2022 |
| Apple         | MacBookPro11,4              | [c5d5b88740](https://linux-hardware.org/?probe=c5d5b88740) | Sep 09, 2022 |
| ASUSTek       | GL702VSK                    | [5001a76a0e](https://linux-hardware.org/?probe=5001a76a0e) | Sep 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [3932661b8e](https://linux-hardware.org/?probe=3932661b8e) | Sep 07, 2022 |
| Acer          | Aspire V5-552               | [031439a681](https://linux-hardware.org/?probe=031439a681) | Sep 04, 2022 |
| Apple         | MacBookPro8,2               | [b37d844ab3](https://linux-hardware.org/?probe=b37d844ab3) | Sep 04, 2022 |
| TUXEDO        | Book XP14 Gen12             | [cfb0fb9451](https://linux-hardware.org/?probe=cfb0fb9451) | Sep 04, 2022 |
| Timi          | TM1701                      | [f23c551375](https://linux-hardware.org/?probe=f23c551375) | Sep 03, 2022 |
| Notebook      | NLx0MU                      | [90c9b01136](https://linux-hardware.org/?probe=90c9b01136) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | [77d4b4ff99](https://linux-hardware.org/?probe=77d4b4ff99) | Aug 31, 2022 |
| Apple         | MacBookPro8,1               | [f65d685d05](https://linux-hardware.org/?probe=f65d685d05) | Aug 30, 2022 |
| Apple         | MacBookPro5,2               | [7f66ca2cc7](https://linux-hardware.org/?probe=7f66ca2cc7) | Aug 29, 2022 |
| Standard      | Unknown                     | [62e0164e5b](https://linux-hardware.org/?probe=62e0164e5b) | Aug 29, 2022 |
| HP            | Laptop 15-db0xxx            | [d67f262815](https://linux-hardware.org/?probe=d67f262815) | Aug 28, 2022 |
| ASUSTek       | X542UA                      | [0bf776cdc1](https://linux-hardware.org/?probe=0bf776cdc1) | Aug 28, 2022 |
| HP            | 240 G7 Notebook PC          | [af418375d3](https://linux-hardware.org/?probe=af418375d3) | Aug 27, 2022 |
| Complet       | MY8312                      | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Dell          | Inspiron 5537               | [d05888c5bc](https://linux-hardware.org/?probe=d05888c5bc) | Aug 25, 2022 |
| Dell          | Latitude E7250              | [98f4886ef7](https://linux-hardware.org/?probe=98f4886ef7) | Aug 25, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [dfb0ad63df](https://linux-hardware.org/?probe=dfb0ad63df) | Aug 25, 2022 |
| Apple         | MacBookAir7,1               | [079a951d65](https://linux-hardware.org/?probe=079a951d65) | Aug 23, 2022 |
| Apple         | MacBookAir6,2               | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [7169cd34ab](https://linux-hardware.org/?probe=7169cd34ab) | Aug 22, 2022 |
| ASUSTek       | K52F                        | [cafd25a659](https://linux-hardware.org/?probe=cafd25a659) | Aug 21, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [08d6e2e6e8](https://linux-hardware.org/?probe=08d6e2e6e8) | Aug 21, 2022 |
| Apple         | MacBookPro8,2               | [b01d72c341](https://linux-hardware.org/?probe=b01d72c341) | Aug 20, 2022 |
| HP            | 240 G7 Notebook PC          | [ffa5707dc9](https://linux-hardware.org/?probe=ffa5707dc9) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | [a2c5089e9a](https://linux-hardware.org/?probe=a2c5089e9a) | Aug 16, 2022 |
| Acer          | Aspire V5-552G              | [f51f3093d9](https://linux-hardware.org/?probe=f51f3093d9) | Aug 12, 2022 |
| ASUSTek       | K43E                        | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| Dell          | Inspiron 5570               | [b94818059a](https://linux-hardware.org/?probe=b94818059a) | Aug 10, 2022 |
| Toshiba       | Satellite L875-11M          | [5a01928c94](https://linux-hardware.org/?probe=5a01928c94) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [72cfcef1a6](https://linux-hardware.org/?probe=72cfcef1a6) | Aug 10, 2022 |
| Dell          | Latitude D630               | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| Toshiba       | Satellite L875-11M          | [1b423f639e](https://linux-hardware.org/?probe=1b423f639e) | Aug 09, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [b719fff96d](https://linux-hardware.org/?probe=b719fff96d) | Aug 08, 2022 |
| HP            | Pavilion 17                 | [f06bb8d9ab](https://linux-hardware.org/?probe=f06bb8d9ab) | Aug 07, 2022 |
| HP            | Pavilion 17                 | [9c47c2e4f4](https://linux-hardware.org/?probe=9c47c2e4f4) | Aug 07, 2022 |
| TrekStor      | Notebook Slim S130          | [ba73d094e7](https://linux-hardware.org/?probe=ba73d094e7) | Aug 06, 2022 |
| Sony          | VPCEB16FG                   | [6baf989163](https://linux-hardware.org/?probe=6baf989163) | Aug 06, 2022 |
| Sony          | SVS15117FLB                 | [2729210175](https://linux-hardware.org/?probe=2729210175) | Aug 06, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | [6e4a76904c](https://linux-hardware.org/?probe=6e4a76904c) | Aug 06, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [7594659719](https://linux-hardware.org/?probe=7594659719) | Aug 05, 2022 |
| MSI           | Creator 15 A10SET           | [45d9d06fb8](https://linux-hardware.org/?probe=45d9d06fb8) | Aug 05, 2022 |
| Medion        | Akoya E6422 MD99680         | [86cd2f6a0a](https://linux-hardware.org/?probe=86cd2f6a0a) | Aug 05, 2022 |
| Sony          | SVS15117FLB                 | [1f64d30f2f](https://linux-hardware.org/?probe=1f64d30f2f) | Aug 05, 2022 |
| Dell          | Latitude 3190               | [7a0956e5f8](https://linux-hardware.org/?probe=7a0956e5f8) | Aug 04, 2022 |
| ASUSTek       | K43E                        | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [764d4ebd1b](https://linux-hardware.org/?probe=764d4ebd1b) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [5dab148c3e](https://linux-hardware.org/?probe=5dab148c3e) | Aug 04, 2022 |
| Dell          | Latitude E6400              | [54db9ae43d](https://linux-hardware.org/?probe=54db9ae43d) | Aug 04, 2022 |
| HP            | Pavilion dv6                | [b921b586f6](https://linux-hardware.org/?probe=b921b586f6) | Aug 02, 2022 |
| HP            | 431                         | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Dell          | Latitude E6320              | [34270898c6](https://linux-hardware.org/?probe=34270898c6) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | [04487d99ff](https://linux-hardware.org/?probe=04487d99ff) | Jul 30, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [c291b32941](https://linux-hardware.org/?probe=c291b32941) | Jul 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [af8fd9ae70](https://linux-hardware.org/?probe=af8fd9ae70) | Jul 29, 2022 |
| ASUSTek       | K43E                        | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| Dell          | Latitude D630               | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| Dell          | Latitude E6320              | [a5b77aa0e9](https://linux-hardware.org/?probe=a5b77aa0e9) | Jul 28, 2022 |
| Dell          | Latitude 3190               | [36027c80d2](https://linux-hardware.org/?probe=36027c80d2) | Jul 28, 2022 |
| Apple         | MacBook4,1                  | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [d9a5e0b7e6](https://linux-hardware.org/?probe=d9a5e0b7e6) | Jul 27, 2022 |
| HP            | Pavilion g4                 | [c9aa5e235c](https://linux-hardware.org/?probe=c9aa5e235c) | Jul 27, 2022 |
| HP            | 255 G7 Notebook PC          | [8173942fbb](https://linux-hardware.org/?probe=8173942fbb) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | [f4026901c2](https://linux-hardware.org/?probe=f4026901c2) | Jul 25, 2022 |
| HP            | Pavilion g6                 | [73061b2ed5](https://linux-hardware.org/?probe=73061b2ed5) | Jul 23, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [810b379dac](https://linux-hardware.org/?probe=810b379dac) | Jul 19, 2022 |
| HUAWEI        | HLYL-WXX9                   | [3831dd717e](https://linux-hardware.org/?probe=3831dd717e) | Jul 19, 2022 |
| Apple         | MacBookPro8,1               | [d5b50db42e](https://linux-hardware.org/?probe=d5b50db42e) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Acer          | Aspire A315-32              | [ec022ec507](https://linux-hardware.org/?probe=ec022ec507) | Jul 18, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [54152fdf16](https://linux-hardware.org/?probe=54152fdf16) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Apple         | MacBookPro8,1               | [21c49763f5](https://linux-hardware.org/?probe=21c49763f5) | Jul 17, 2022 |
| HP            | ProBook 430 G2              | [0be149d703](https://linux-hardware.org/?probe=0be149d703) | Jul 16, 2022 |
| HP            | EliteBook 8460p             | [b1c5cb2096](https://linux-hardware.org/?probe=b1c5cb2096) | Jul 12, 2022 |
| HP            | Notebook                    | [afaaed48c7](https://linux-hardware.org/?probe=afaaed48c7) | Jul 10, 2022 |
| Acer          | Aspire 1830T                | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| Acer          | Aspire AV15-51              | [1a880a89af](https://linux-hardware.org/?probe=1a880a89af) | Jul 09, 2022 |
| Acer          | Aspire V3-771               | [e8488fb0e2](https://linux-hardware.org/?probe=e8488fb0e2) | Jul 07, 2022 |
| HP            | Notebook                    | [2bf65688ab](https://linux-hardware.org/?probe=2bf65688ab) | Jul 05, 2022 |
| Dell          | Inspiron 3593               | [d34d56c473](https://linux-hardware.org/?probe=d34d56c473) | Jul 05, 2022 |
| HP            | Laptop 15-dy1xxx            | [3fcdd6c039](https://linux-hardware.org/?probe=3fcdd6c039) | Jul 03, 2022 |
| Dell          | XPS 15 9500                 | [7df8533350](https://linux-hardware.org/?probe=7df8533350) | Jul 03, 2022 |
| ASUSTek       | N56VB                       | [88d34c06f3](https://linux-hardware.org/?probe=88d34c06f3) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e13cada6ae](https://linux-hardware.org/?probe=e13cada6ae) | Jul 02, 2022 |
| ASUSTek       | X553MA                      | [804bbd8147](https://linux-hardware.org/?probe=804bbd8147) | Jun 30, 2022 |
| ASUSTek       | X553MA                      | [9fe936cec8](https://linux-hardware.org/?probe=9fe936cec8) | Jun 30, 2022 |
| Dell          | Inspiron 5537               | [9758b4dcff](https://linux-hardware.org/?probe=9758b4dcff) | Jun 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| Lenovo        | V15-IIL 82C5                | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| Toshiba       | Satellite C870-1H2          | [edc5098a6f](https://linux-hardware.org/?probe=edc5098a6f) | Jun 27, 2022 |
| HP            | Pavilion dv5                | [4d0e23962a](https://linux-hardware.org/?probe=4d0e23962a) | Jun 27, 2022 |
| Apple         | MacBookPro14,2              | [7fe621e5a7](https://linux-hardware.org/?probe=7fe621e5a7) | Jun 27, 2022 |
| Compaq        | Presario CQ-23              | [f55fd14f61](https://linux-hardware.org/?probe=f55fd14f61) | Jun 26, 2022 |
| ASUSTek       | UX303LAB                    | [ae3becae01](https://linux-hardware.org/?probe=ae3becae01) | Jun 24, 2022 |
| HP            | Pavilion g4                 | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Alienware     | m17 R3                      | [ea3305a8af](https://linux-hardware.org/?probe=ea3305a8af) | Jun 20, 2022 |
| Dell          | Latitude E5510              | [1f6cc92f98](https://linux-hardware.org/?probe=1f6cc92f98) | Jun 18, 2022 |
| HP            | EliteBook 2170p             | [6c7391f201](https://linux-hardware.org/?probe=6c7391f201) | Jun 17, 2022 |
| HP            | ProBook 455R G6             | [31b94c71c7](https://linux-hardware.org/?probe=31b94c71c7) | Jun 16, 2022 |
| HP            | ProBook 455R G6             | [39d04d1188](https://linux-hardware.org/?probe=39d04d1188) | Jun 16, 2022 |
| Samsung       | Lumpy                       | [50dad22fb3](https://linux-hardware.org/?probe=50dad22fb3) | Jun 15, 2022 |
| ASUSTek       | GR8                         | [3cdc341eda](https://linux-hardware.org/?probe=3cdc341eda) | Jun 15, 2022 |
| Lenovo        | V15-IIL 82C5                | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
| Samsung       | Lumpy                       | [4137bf9757](https://linux-hardware.org/?probe=4137bf9757) | Jun 14, 2022 |
| Acer          | TravelMate 5760             | [90e189c067](https://linux-hardware.org/?probe=90e189c067) | Jun 13, 2022 |
| Apple         | MacBook4,1                  | [83cac56441](https://linux-hardware.org/?probe=83cac56441) | Jun 13, 2022 |
| HP            | ProBook 4540s               | [6688afd4f5](https://linux-hardware.org/?probe=6688afd4f5) | Jun 11, 2022 |
| Acer          | Aspire A315-21              | [9840a70112](https://linux-hardware.org/?probe=9840a70112) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [0ec841e188](https://linux-hardware.org/?probe=0ec841e188) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [5768dfe23f](https://linux-hardware.org/?probe=5768dfe23f) | Jun 11, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c76f63fb68](https://linux-hardware.org/?probe=c76f63fb68) | Jun 10, 2022 |
| HP            | ProBook 4540s               | [d0a6dcaa92](https://linux-hardware.org/?probe=d0a6dcaa92) | Jun 09, 2022 |
| Acer          | Aspire A315-21              | [224023dfd2](https://linux-hardware.org/?probe=224023dfd2) | Jun 08, 2022 |
| HP            | Notebook                    | [f07183fab5](https://linux-hardware.org/?probe=f07183fab5) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| HP            | ProBook 4540s               | [b74c4304e9](https://linux-hardware.org/?probe=b74c4304e9) | Jun 05, 2022 |
| Apple         | MacBookAir7,2               | [9de74ba486](https://linux-hardware.org/?probe=9de74ba486) | Jun 04, 2022 |
| Apple         | MacBookAir7,2               | [eb704f99ee](https://linux-hardware.org/?probe=eb704f99ee) | Jun 04, 2022 |
| Apple         | MacBookAir4,2               | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| HP            | ProBook 4540s               | [da53c77e1a](https://linux-hardware.org/?probe=da53c77e1a) | Jun 02, 2022 |
| Samsung       | 300E5M/300E5L               | [baa12d722c](https://linux-hardware.org/?probe=baa12d722c) | Jun 01, 2022 |
| Dell          | XPS 13 9343                 | [5881b6ea1b](https://linux-hardware.org/?probe=5881b6ea1b) | May 28, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| HUAWEI        | MACHD-WXX9                  | [6cc36ec0ae](https://linux-hardware.org/?probe=6cc36ec0ae) | May 27, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [50f70bc9af](https://linux-hardware.org/?probe=50f70bc9af) | May 27, 2022 |
| ASUSTek       | X550CA                      | [6789d8dad5](https://linux-hardware.org/?probe=6789d8dad5) | May 26, 2022 |
| AMI           | Intel                       | [ee3b1abf63](https://linux-hardware.org/?probe=ee3b1abf63) | May 25, 2022 |
| Acer          | Swift SF114-32              | [601f82b2dd](https://linux-hardware.org/?probe=601f82b2dd) | May 23, 2022 |
| Apple         | MacBook4,1                  | [27f751618e](https://linux-hardware.org/?probe=27f751618e) | May 22, 2022 |
| HP            | ProBook 6550b               | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| AMI           | Intel                       | [6c571e79d0](https://linux-hardware.org/?probe=6c571e79d0) | May 21, 2022 |
| eMachines     | E525                        | [ca296b06c9](https://linux-hardware.org/?probe=ca296b06c9) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| Sony          | VPCEB23FM                   | [4d73e73cf8](https://linux-hardware.org/?probe=4d73e73cf8) | May 17, 2022 |
| Sony          | VPCEB23FM                   | [07d2cadefb](https://linux-hardware.org/?probe=07d2cadefb) | May 17, 2022 |
| Samsung       | Lumpy                       | [84a78226dd](https://linux-hardware.org/?probe=84a78226dd) | May 16, 2022 |
| HP            | ENVY 14                     | [9fe635b800](https://linux-hardware.org/?probe=9fe635b800) | May 15, 2022 |
| ASUSTek       | K55A                        | [3391d004a7](https://linux-hardware.org/?probe=3391d004a7) | May 15, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c0e150d349](https://linux-hardware.org/?probe=c0e150d349) | May 13, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [919200b122](https://linux-hardware.org/?probe=919200b122) | May 13, 2022 |
| ASUSTek       | UX310UQK                    | [1af1efeb46](https://linux-hardware.org/?probe=1af1efeb46) | May 11, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [d5df500fa3](https://linux-hardware.org/?probe=d5df500fa3) | May 10, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | ProBook 4510s               | [1464ea43d3](https://linux-hardware.org/?probe=1464ea43d3) | May 09, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [b726ded078](https://linux-hardware.org/?probe=b726ded078) | May 08, 2022 |
| HP            | ZBook 15                    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| Apple         | MacBookPro8,2               | [2eb968b190](https://linux-hardware.org/?probe=2eb968b190) | May 07, 2022 |
| HP            | EliteBook 8470p             | [d7223d4b03](https://linux-hardware.org/?probe=d7223d4b03) | May 05, 2022 |
| eMachines     | E525                        | [dfc36c2ea0](https://linux-hardware.org/?probe=dfc36c2ea0) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Dell          | Inspiron 7720               | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| HP            | Pavilion 17                 | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X202E                       | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| Acer          | Aspire E5-411G              | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| Avell High... | B.ON                        | [eb3d4d0f78](https://linux-hardware.org/?probe=eb3d4d0f78) | Apr 29, 2022 |
| HP            | Pavilion 17                 | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [c12f5ae663](https://linux-hardware.org/?probe=c12f5ae663) | Apr 28, 2022 |
| HP            | EliteBook 840 G1            | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| Lenovo        | ThinkPad T420 41786VU       | [e2b4c2327b](https://linux-hardware.org/?probe=e2b4c2327b) | Apr 25, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| Dell          | Latitude 3120               | [78f0703e75](https://linux-hardware.org/?probe=78f0703e75) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [2f497982cd](https://linux-hardware.org/?probe=2f497982cd) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HP            | Pavilion g6                 | [63f6b73d50](https://linux-hardware.org/?probe=63f6b73d50) | Apr 21, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [336a67fbee](https://linux-hardware.org/?probe=336a67fbee) | Apr 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [d3d2e2fe8a](https://linux-hardware.org/?probe=d3d2e2fe8a) | Apr 18, 2022 |
| HP            | ProBook 6440b               | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Lenovo        | ThinkPad W541 20EGS0UB03    | [f566cb7f4c](https://linux-hardware.org/?probe=f566cb7f4c) | Apr 14, 2022 |
| Dell          | Latitude 3550               | [6947850074](https://linux-hardware.org/?probe=6947850074) | Apr 14, 2022 |
| HP            | ProBook 440 G7              | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| Panasonic     | CF-31SBLJGDM                | [60a1068658](https://linux-hardware.org/?probe=60a1068658) | Apr 13, 2022 |
| Acer          | Aspire E5-575G              | [07bdcd6978](https://linux-hardware.org/?probe=07bdcd6978) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [379db407c7](https://linux-hardware.org/?probe=379db407c7) | Apr 10, 2022 |
| HP            | Pavilion 13 x360 PC         | [3abf9847e4](https://linux-hardware.org/?probe=3abf9847e4) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | [840239190e](https://linux-hardware.org/?probe=840239190e) | Apr 09, 2022 |
| Apple         | MacBookAir6,2               | [84c694e881](https://linux-hardware.org/?probe=84c694e881) | Apr 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [fd62bf7f91](https://linux-hardware.org/?probe=fd62bf7f91) | Apr 05, 2022 |
| Dell          | Latitude 5410               | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| Apple         | MacBookAir6,2               | [656e7d1b73](https://linux-hardware.org/?probe=656e7d1b73) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| HP            | Notebook                    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Apple         | MacBookAir4,2               | [7fc2cd808d](https://linux-hardware.org/?probe=7fc2cd808d) | Apr 02, 2022 |
| Dell          | Vostro A860                 | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [9375dd090a](https://linux-hardware.org/?probe=9375dd090a) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [ab016f94d5](https://linux-hardware.org/?probe=ab016f94d5) | Apr 01, 2022 |
| HP            | EliteBook 8730w             | [caade8e7ff](https://linux-hardware.org/?probe=caade8e7ff) | Mar 31, 2022 |
| ASUSTek       | UL80VT                      | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Acer          | Aspire ES1-531              | [e617f1e49b](https://linux-hardware.org/?probe=e617f1e49b) | Mar 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| Acer          | Aspire ES1-520              | [95df1e3190](https://linux-hardware.org/?probe=95df1e3190) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| Dell          | Latitude 5520               | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| LG Electro... | P1-JSUVT                    | [b0e2f9e53c](https://linux-hardware.org/?probe=b0e2f9e53c) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| Toshiba       | Satellite C70D-A            | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| Toshiba       | Satellite L50D-C            | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| Dell          | Inspiron MM061              | [1535349482](https://linux-hardware.org/?probe=1535349482) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| Dell          | Inspiron MM061              | [dd34f9d506](https://linux-hardware.org/?probe=dd34f9d506) | Mar 23, 2022 |
| Sony          | SVP1321B4E                  | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| Acer          | Swift SF314-52              | [2d8ab46eed](https://linux-hardware.org/?probe=2d8ab46eed) | Mar 21, 2022 |
| Acer          | Swift SF314-52              | [b1bdc8c7d4](https://linux-hardware.org/?probe=b1bdc8c7d4) | Mar 21, 2022 |
| LG Electro... | A410-G.BC51P1               | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Dell          | Vostro 15 3515              | [6806f47a62](https://linux-hardware.org/?probe=6806f47a62) | Mar 19, 2022 |
| Apple         | MacBookAir7,1               | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| Dell          | Inspiron 5593               | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Dell          | Latitude E6220              | [e2c9477eb3](https://linux-hardware.org/?probe=e2c9477eb3) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| Dell          | Latitude 3550               | [947e147577](https://linux-hardware.org/?probe=947e147577) | Mar 13, 2022 |
| Dell          | Latitude 3550               | [afffe18667](https://linux-hardware.org/?probe=afffe18667) | Mar 13, 2022 |
| Acer          | Aspire A315-21G             | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [7f9721781e](https://linux-hardware.org/?probe=7f9721781e) | Mar 12, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [bc5d95b759](https://linux-hardware.org/?probe=bc5d95b759) | Mar 12, 2022 |
| Teclast       | F15S                        | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| ASUSTek       | X200CA                      | [85c103c654](https://linux-hardware.org/?probe=85c103c654) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | [25518274da](https://linux-hardware.org/?probe=25518274da) | Mar 10, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [b950d195ce](https://linux-hardware.org/?probe=b950d195ce) | Mar 10, 2022 |
| HP            | Laptop 15-db0xxx            | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [83dc415e28](https://linux-hardware.org/?probe=83dc415e28) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | [fc064cce68](https://linux-hardware.org/?probe=fc064cce68) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [c3e1baf45a](https://linux-hardware.org/?probe=c3e1baf45a) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [caa5c3eef1](https://linux-hardware.org/?probe=caa5c3eef1) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | [02818352e0](https://linux-hardware.org/?probe=02818352e0) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | [24a601d3aa](https://linux-hardware.org/?probe=24a601d3aa) | Mar 06, 2022 |
| Lenovo        | IdeaPad Y580                | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | [7e967f4daa](https://linux-hardware.org/?probe=7e967f4daa) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | [db5f524190](https://linux-hardware.org/?probe=db5f524190) | Mar 06, 2022 |
| Acer          | Nitro AN517-52              | [4576110ce4](https://linux-hardware.org/?probe=4576110ce4) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| HP            | ProBook 450 G7              | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [d04715f0dc](https://linux-hardware.org/?probe=d04715f0dc) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| Acer          | Aspire A315-42G             | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Dell          | Inspiron N5050              | [88c13620a2](https://linux-hardware.org/?probe=88c13620a2) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| ASUSTek       | GL753VE                     | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| ASUSTek       | E402SA                      | [b9796e46de](https://linux-hardware.org/?probe=b9796e46de) | Feb 20, 2022 |
| ASUSTek       | K75VJ                       | [e0c07cf9d2](https://linux-hardware.org/?probe=e0c07cf9d2) | Feb 20, 2022 |
| Apple         | MacBook5,1                  | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [da54df3fd4](https://linux-hardware.org/?probe=da54df3fd4) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [05cb921db2](https://linux-hardware.org/?probe=05cb921db2) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Elementary/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Elementary 6.1   | 469       | 37.34%  |
| Elementary 7.1   | 177       | 14.09%  |
| Elementary 7     | 155       | 12.34%  |
| Elementary 5.1.7 | 152       | 12.1%   |
| Elementary 6     | 144       | 11.46%  |
| Elementary 5.0   | 34        | 2.71%   |
| Elementary 5.1.6 | 29        | 2.31%   |
| Elementary 5.1   | 25        | 1.99%   |
| Elementary 5.1.4 | 23        | 1.83%   |
| Elementary 5.1.2 | 16        | 1.27%   |
| Elementary 5.1.3 | 12        | 0.96%   |
| Elementary 5.1.5 | 8         | 0.64%   |
| Elementary 0.4.1 | 8         | 0.64%   |
| Elementary 6.0   | 4         | 0.32%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Elementary | 1211      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-43-generic | 89        | 6.62%   |
| 5.15.0-58-generic | 54        | 4.01%   |
| 6.2.0-33-generic  | 41        | 3.05%   |
| 5.13.0-28-generic | 32        | 2.38%   |
| 5.11.0-40-generic | 32        | 2.38%   |
| 5.15.0-46-generic | 31        | 2.3%    |
| 5.11.0-41-generic | 28        | 2.08%   |
| 5.15.0-56-generic | 27        | 2.01%   |
| 5.13.0-30-generic | 27        | 2.01%   |
| 5.11.0-27-generic | 27        | 2.01%   |
| 5.13.0-27-generic | 24        | 1.78%   |
| 5.4.0-42-generic  | 21        | 1.56%   |
| 6.5.0-28-generic  | 19        | 1.41%   |
| 5.3.0-62-generic  | 19        | 1.41%   |
| 5.15.0-52-generic | 19        | 1.41%   |
| 5.15.0-48-generic | 19        | 1.41%   |
| 5.15.0-41-generic | 19        | 1.41%   |
| 5.11.0-38-generic | 19        | 1.41%   |
| 5.19.0-41-generic | 18        | 1.34%   |
| 5.13.0-40-generic | 17        | 1.26%   |
| 5.13.0-39-generic | 17        | 1.26%   |
| 6.2.0-26-generic  | 16        | 1.19%   |
| 5.19.0-35-generic | 16        | 1.19%   |
| 5.11.0-37-generic | 16        | 1.19%   |
| 5.19.0-46-generic | 15        | 1.12%   |
| 5.11.0-44-generic | 14        | 1.04%   |
| 6.5.0-26-generic  | 13        | 0.97%   |
| 5.13.0-35-generic | 13        | 0.97%   |
| 6.5.0-27-generic  | 12        | 0.89%   |
| 5.3.0-51-generic  | 12        | 0.89%   |
| 5.19.0-32-generic | 12        | 0.89%   |
| 5.15.0-43-generic | 12        | 0.89%   |
| 5.13.0-37-generic | 12        | 0.89%   |
| 5.0.0-37-generic  | 12        | 0.89%   |
| 6.5.0-21-generic  | 11        | 0.82%   |
| 6.2.0-39-generic  | 11        | 0.82%   |
| 5.3.0-53-generic  | 11        | 0.82%   |
| 5.15.0-53-generic | 11        | 0.82%   |
| 5.11.0-34-generic | 11        | 0.82%   |
| 5.11.0-25-generic | 11        | 0.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 252       | 19.8%   |
| 5.15.0  | 219       | 17.2%   |
| 5.13.0  | 173       | 13.59%  |
| 5.4.0   | 140       | 11%     |
| 6.2.0   | 107       | 8.41%   |
| 6.5.0   | 89        | 6.99%   |
| 5.19.0  | 89        | 6.99%   |
| 5.3.0   | 77        | 6.05%   |
| 4.15.0  | 57        | 4.48%   |
| 5.0.0   | 15        | 1.18%   |
| 5.8.0   | 8         | 0.63%   |
| 5.10.0  | 3         | 0.24%   |
| 4.13.0  | 3         | 0.24%   |
| 5.14.0  | 2         | 0.16%   |
| 6.7.3   | 1         | 0.08%   |
| 6.5.7   | 1         | 0.08%   |
| 6.5.5   | 1         | 0.08%   |
| 6.3.13  | 1         | 0.08%   |
| 6.2.7   | 1         | 0.08%   |
| 6.1.9   | 1         | 0.08%   |
| 6.1.6   | 1         | 0.08%   |
| 6.1.0   | 1         | 0.08%   |
| 6.0.0   | 1         | 0.08%   |
| 5.9.1   | 1         | 0.08%   |
| 5.8.5   | 1         | 0.08%   |
| 5.8.13  | 1         | 0.08%   |
| 5.6.2   | 1         | 0.08%   |
| 5.6.19  | 1         | 0.08%   |
| 5.6.14  | 1         | 0.08%   |
| 5.5.8   | 1         | 0.08%   |
| 5.5.6   | 1         | 0.08%   |
| 5.4.1   | 1         | 0.08%   |
| 5.3.6   | 1         | 0.08%   |
| 5.3.11  | 1         | 0.08%   |
| 5.19.3  | 1         | 0.08%   |
| 5.19.12 | 1         | 0.08%   |
| 5.19.11 | 1         | 0.08%   |
| 5.18.3  | 1         | 0.08%   |
| 5.16.16 | 1         | 0.08%   |
| 5.16.10 | 1         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 252       | 19.84%  |
| 5.15    | 226       | 17.8%   |
| 5.13    | 173       | 13.62%  |
| 5.4     | 141       | 11.1%   |
| 6.2     | 108       | 8.5%    |
| 5.19    | 92        | 7.24%   |
| 6.5     | 91        | 7.17%   |
| 5.3     | 79        | 6.22%   |
| 4.15    | 57        | 4.49%   |
| 5.0     | 15        | 1.18%   |
| 5.8     | 10        | 0.79%   |
| 5.14    | 5         | 0.39%   |
| 5.10    | 4         | 0.31%   |
| 6.1     | 3         | 0.24%   |
| 4.13    | 3         | 0.24%   |
| 5.5     | 2         | 0.16%   |
| 5.16    | 2         | 0.16%   |
| 6.7     | 1         | 0.08%   |
| 6.3     | 1         | 0.08%   |
| 6.0     | 1         | 0.08%   |
| 5.9     | 1         | 0.08%   |
| 5.6     | 1         | 0.08%   |
| 5.18    | 1         | 0.08%   |
| 4.10    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1211      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pantheon      | 1140      | 93.29%  |
| Unknown       | 65        | 5.32%   |
| GNOME         | 8         | 0.65%   |
| X-Cinnamon    | 4         | 0.33%   |
| XFCE          | 1         | 0.08%   |
| Unity         | 1         | 0.08%   |
| KDE5          | 1         | 0.08%   |
| GNOME Classic | 1         | 0.08%   |
| Budgie        | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1211      | 99.92%  |
| Unknown | 1         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 949       | 77.53%  |
| LightDM | 221       | 18.06%  |
| TDM     | 49        | 4%      |
| GDM     | 4         | 0.33%   |
| SDDM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 514       | 42.2%   |
| de_DE   | 124       | 10.18%  |
| es_ES   | 83        | 6.81%   |
| ru_RU   | 78        | 6.4%    |
| pt_BR   | 56        | 4.6%    |
| en_GB   | 52        | 4.27%   |
| fr_FR   | 45        | 3.69%   |
| it_IT   | 44        | 3.61%   |
| Unknown | 34        | 2.79%   |
| pl_PL   | 22        | 1.81%   |
| en_AU   | 18        | 1.48%   |
| nl_NL   | 13        | 1.07%   |
| en_CA   | 13        | 1.07%   |
| tr_TR   | 12        | 0.99%   |
| pt_PT   | 11        | 0.9%    |
| en_IN   | 9         | 0.74%   |
| hu_HU   | 8         | 0.66%   |
| cs_CZ   | 6         | 0.49%   |
| sv_SE   | 5         | 0.41%   |
| nb_NO   | 5         | 0.41%   |
| es_MX   | 5         | 0.41%   |
| el_GR   | 5         | 0.41%   |
| zh_CN   | 4         | 0.33%   |
| id_ID   | 4         | 0.33%   |
| de_CH   | 4         | 0.33%   |
| uk_UA   | 3         | 0.25%   |
| fr_CA   | 3         | 0.25%   |
| fi_FI   | 3         | 0.25%   |
| es_EC   | 3         | 0.25%   |
| es_AR   | 3         | 0.25%   |
| en_ZA   | 3         | 0.25%   |
| da_DK   | 3         | 0.25%   |
| es_CL   | 2         | 0.16%   |
| ca_ES   | 2         | 0.16%   |
| C       | 2         | 0.16%   |
| bg_BG   | 2         | 0.16%   |
| zh_TW   | 1         | 0.08%   |
| vi_VN   | 1         | 0.08%   |
| ru_UA   | 1         | 0.08%   |
| ro_RO   | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 620       | 50.37%  |
| BIOS | 611       | 49.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1144      | 94%     |
| Tmpfs   | 21        | 1.73%   |
| Overlay | 21        | 1.73%   |
| Btrfs   | 15        | 1.23%   |
| Unknown | 12        | 0.99%   |
| Xfs     | 3         | 0.25%   |
| Ext3    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 981       | 80.08%  |
| GPT     | 198       | 16.16%  |
| MBR     | 46        | 3.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1174      | 96.94%  |
| Yes       | 37        | 3.06%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1088      | 89.18%  |
| Yes       | 132       | 10.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 238       | 19.65%  |
| Hewlett-Packard        | 217       | 17.92%  |
| Dell                   | 146       | 12.06%  |
| Apple                  | 141       | 11.64%  |
| ASUSTek Computer       | 115       | 9.5%    |
| Acer                   | 98        | 8.09%   |
| Toshiba                | 33        | 2.73%   |
| HUAWEI                 | 31        | 2.56%   |
| Samsung Electronics    | 23        | 1.9%    |
| Sony                   | 19        | 1.57%   |
| MSI                    | 19        | 1.57%   |
| Google                 | 10        | 0.83%   |
| Fujitsu                | 9         | 0.74%   |
| Medion                 | 7         | 0.58%   |
| Packard Bell           | 6         | 0.5%    |
| Alienware              | 6         | 0.5%    |
| Unknown                | 6         | 0.5%    |
| Star Labs              | 5         | 0.41%   |
| Notebook               | 5         | 0.41%   |
| Timi                   | 4         | 0.33%   |
| LG Electronics         | 4         | 0.33%   |
| TUXEDO                 | 3         | 0.25%   |
| Razer                  | 3         | 0.25%   |
| Positivo               | 3         | 0.25%   |
| HONOR                  | 3         | 0.25%   |
| Compaq                 | 3         | 0.25%   |
| Clevo                  | 3         | 0.25%   |
| Chuwi                  | 3         | 0.25%   |
| Wortmann AG            | 2         | 0.17%   |
| TrekStor               | 2         | 0.17%   |
| Teclast                | 2         | 0.17%   |
| Slimbook               | 2         | 0.17%   |
| Multilaser             | 2         | 0.17%   |
| Monster                | 2         | 0.17%   |
| Gigabyte Technology    | 2         | 0.17%   |
| eMachines              | 2         | 0.17%   |
| Avell High Performance | 2         | 0.17%   |
| AMI                    | 2         | 0.17%   |
| UNOWHY                 | 1         | 0.08%   |
| UMAX                   | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Apple MacBookAir7,2           | 14        | 1.16%   |
| Apple MacBookPro9,2           | 11        | 0.91%   |
| Apple MacBookPro8,1           | 10        | 0.83%   |
| Unknown                       | 8         | 0.66%   |
| HP Notebook                   | 7         | 0.58%   |
| Apple MacBookPro8,2           | 7         | 0.58%   |
| Apple MacBookAir6,2           | 7         | 0.58%   |
| Apple MacBook5,1              | 7         | 0.58%   |
| HP Pavilion g6                | 6         | 0.5%    |
| Apple MacBookPro6,2           | 6         | 0.5%    |
| Apple MacBookPro5,5           | 6         | 0.5%    |
| Apple MacBookPro11,2          | 6         | 0.5%    |
| Lenovo G50-45 80E3            | 5         | 0.41%   |
| HUAWEI MACHD-WXX9             | 5         | 0.41%   |
| HP Pavilion dv7               | 5         | 0.41%   |
| HP EliteBook 840 G3           | 5         | 0.41%   |
| Dell Latitude E6400           | 5         | 0.41%   |
| Dell Inspiron 15-3567         | 5         | 0.41%   |
| ASUS ZenBook UX425EA_UX425EA  | 5         | 0.41%   |
| HUAWEI NBLK-WAX9X             | 4         | 0.33%   |
| HUAWEI NBLB-WAX9N             | 4         | 0.33%   |
| HP ProBook 4540s              | 4         | 0.33%   |
| HP Pavilion Notebook          | 4         | 0.33%   |
| HP Laptop 15-bs0xx            | 4         | 0.33%   |
| HP 15                         | 4         | 0.33%   |
| Dell Inspiron 1545            | 4         | 0.33%   |
| Apple MacBookPro7,1           | 4         | 0.33%   |
| Apple MacBookPro11,1          | 4         | 0.33%   |
| Apple MacBookAir4,2           | 4         | 0.33%   |
| Apple MacBook4,1              | 4         | 0.33%   |
| Star Labs StarBook            | 3         | 0.25%   |
| Samsung 530U3C/530U4C/532U3C  | 3         | 0.25%   |
| Lenovo IdeaPad 330-15IKB 81FE | 3         | 0.25%   |
| Lenovo IdeaPad 3 15IGL05 81WQ | 3         | 0.25%   |
| HUAWEI BOD-WXX9               | 3         | 0.25%   |
| HP Pavilion Laptop 15-cs0xxx  | 3         | 0.25%   |
| HP Pavilion 17                | 3         | 0.25%   |
| HP Pavilion 15                | 3         | 0.25%   |
| HP Laptop 15-db0xxx           | 3         | 0.25%   |
| HP Laptop 15-bw0xx            | 3         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 113       | 9.33%   |
| Lenovo IdeaPad        | 75        | 6.19%   |
| Acer Aspire           | 69        | 5.7%    |
| Dell Latitude         | 52        | 4.29%   |
| HP Pavilion           | 51        | 4.21%   |
| Dell Inspiron         | 45        | 3.72%   |
| HP ProBook            | 39        | 3.22%   |
| HP EliteBook          | 36        | 2.97%   |
| HP Laptop             | 32        | 2.64%   |
| Toshiba Satellite     | 25        | 2.06%   |
| ASUS VivoBook         | 23        | 1.9%    |
| Apple MacBookPro8     | 19        | 1.57%   |
| Dell XPS              | 17        | 1.4%    |
| Apple MacBookPro11    | 17        | 1.4%    |
| ASUS ZenBook          | 16        | 1.32%   |
| Apple MacBookAir7     | 16        | 1.32%   |
| Apple MacBookPro9     | 14        | 1.16%   |
| Acer Swift            | 14        | 1.16%   |
| Dell Vostro           | 13        | 1.07%   |
| Apple MacBookPro5     | 12        | 0.99%   |
| Apple MacBookAir6     | 10        | 0.83%   |
| Fujitsu LIFEBOOK      | 9         | 0.74%   |
| Dell Precision        | 9         | 0.74%   |
| Apple MacBook5        | 9         | 0.74%   |
| HP ENVY               | 8         | 0.66%   |
| Unknown               | 8         | 0.66%   |
| Lenovo Legion         | 7         | 0.58%   |
| HP Notebook           | 7         | 0.58%   |
| HP 250                | 7         | 0.58%   |
| Packard Bell EasyNote | 6         | 0.5%    |
| Apple MacBookPro6     | 6         | 0.5%    |
| Lenovo Yoga           | 5         | 0.41%   |
| Lenovo G50-45         | 5         | 0.41%   |
| HUAWEI MACHD-WXX9     | 5         | 0.41%   |
| HP 255                | 5         | 0.41%   |
| Apple MacBookPro10    | 5         | 0.41%   |
| Apple MacBookAir4     | 5         | 0.41%   |
| Lenovo ThinkBook      | 4         | 0.33%   |
| HUAWEI NBLK-WAX9X     | 4         | 0.33%   |
| HUAWEI NBLB-WAX9N     | 4         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 110       | 9.08%   |
| 2020    | 108       | 8.92%   |
| 2018    | 101       | 8.34%   |
| 2013    | 101       | 8.34%   |
| 2011    | 90        | 7.43%   |
| 2021    | 89        | 7.35%   |
| 2019    | 87        | 7.18%   |
| 2016    | 80        | 6.61%   |
| 2017    | 79        | 6.52%   |
| 2010    | 74        | 6.11%   |
| 2014    | 73        | 6.03%   |
| 2015    | 66        | 5.45%   |
| 2009    | 47        | 3.88%   |
| 2008    | 45        | 3.72%   |
| 2007    | 24        | 1.98%   |
| 2022    | 20        | 1.65%   |
| 2023    | 13        | 1.07%   |
| 2006    | 3         | 0.25%   |
| Unknown | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1211      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1078      | 88.43%  |
| Enabled  | 141       | 11.57%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1195      | 98.68%  |
| Yes  | 16        | 1.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 426       | 34.86%  |
| 3.01-4.0    | 277       | 22.67%  |
| 16.01-24.0  | 208       | 17.02%  |
| 8.01-16.0   | 199       | 16.28%  |
| 32.01-64.0  | 44        | 3.6%    |
| 1.01-2.0    | 40        | 3.27%   |
| 2.01-3.0    | 14        | 1.15%   |
| 24.01-32.0  | 6         | 0.49%   |
| 64.01-256.0 | 6         | 0.49%   |
| 0.51-1.0    | 2         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 463       | 35.51%  |
| 2.01-3.0   | 414       | 31.75%  |
| 3.01-4.0   | 207       | 15.87%  |
| 4.01-8.0   | 145       | 11.12%  |
| 0.51-1.0   | 40        | 3.07%   |
| 8.01-16.0  | 33        | 2.53%   |
| 24.01-32.0 | 1         | 0.08%   |
| 16.01-24.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 916       | 74.78%  |
| 2      | 279       | 22.78%  |
| 3      | 15        | 1.22%   |
| 4      | 7         | 0.57%   |
| 0      | 5         | 0.41%   |
| 5      | 3         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 795       | 65.43%  |
| Yes       | 420       | 34.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 930       | 76.8%   |
| No        | 281       | 23.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1196      | 98.68%  |
| No        | 16        | 1.32%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1035      | 84.91%  |
| No        | 184       | 15.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 171       | 14.09%  |
| Germany      | 126       | 10.38%  |
| Russia       | 80        | 6.59%   |
| Brazil       | 80        | 6.59%   |
| Italy        | 55        | 4.53%   |
| UK           | 48        | 3.95%   |
| India        | 48        | 3.95%   |
| France       | 41        | 3.38%   |
| Spain        | 39        | 3.21%   |
| Indonesia    | 34        | 2.8%    |
| Mexico       | 31        | 2.55%   |
| Poland       | 29        | 2.39%   |
| Canada       | 27        | 2.22%   |
| Australia    | 27        | 2.22%   |
| Netherlands  | 24        | 1.98%   |
| Turkey       | 23        | 1.89%   |
| Austria      | 18        | 1.48%   |
| Argentina    | 18        | 1.48%   |
| Portugal     | 16        | 1.32%   |
| Chile        | 13        | 1.07%   |
| Belgium      | 13        | 1.07%   |
| Ukraine      | 11        | 0.91%   |
| Hungary      | 11        | 0.91%   |
| Switzerland  | 10        | 0.82%   |
| Sweden       | 10        | 0.82%   |
| Romania      | 10        | 0.82%   |
| Norway       | 9         | 0.74%   |
| Greece       | 9         | 0.74%   |
| Czechia      | 9         | 0.74%   |
| Colombia     | 8         | 0.66%   |
| South Africa | 7         | 0.58%   |
| New Zealand  | 7         | 0.58%   |
| Denmark      | 6         | 0.49%   |
| Belarus      | 6         | 0.49%   |
| Peru         | 5         | 0.41%   |
| Ireland      | 5         | 0.41%   |
| Finland      | 5         | 0.41%   |
| Ecuador      | 5         | 0.41%   |
| China        | 5         | 0.41%   |
| Vietnam      | 4         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Moscow         | 25        | 1.97%   |
| Berlin         | 12        | 0.94%   |
| Vienna         | 11        | 0.87%   |
| St Petersburg  | 11        | 0.87%   |
| Milan          | 10        | 0.79%   |
| Madrid         | 10        | 0.79%   |
| Warsaw         | 9         | 0.71%   |
| Sydney         | 9         | 0.71%   |
| Jakarta        | 8         | 0.63%   |
| Istanbul       | 8         | 0.63%   |
| Hamburg        | 8         | 0.63%   |
| Sao Paulo      | 7         | 0.55%   |
| Perth          | 7         | 0.55%   |
| Paris          | 7         | 0.55%   |
| Munich         | 7         | 0.55%   |
| Mexico City    | 6         | 0.47%   |
| Delhi          | 6         | 0.47%   |
| Córdoba       | 6         | 0.47%   |
| Budapest       | 6         | 0.47%   |
| The Hague      | 5         | 0.39%   |
| Surabaya       | 5         | 0.39%   |
| Stuttgart      | 5         | 0.39%   |
| Rome           | 5         | 0.39%   |
| Rio de Janeiro | 5         | 0.39%   |
| Cologne        | 5         | 0.39%   |
| Buenos Aires   | 5         | 0.39%   |
| Santo André   | 4         | 0.31%   |
| Prague         | 4         | 0.31%   |
| Novosibirsk    | 4         | 0.31%   |
| Mumbai         | 4         | 0.31%   |
| Montreal       | 4         | 0.31%   |
| Melbourne      | 4         | 0.31%   |
| Los Angeles    | 4         | 0.31%   |
| Kolkata        | 4         | 0.31%   |
| Fortaleza      | 4         | 0.31%   |
| Dresden        | 4         | 0.31%   |
| Yekaterinburg  | 3         | 0.24%   |
| Wellington     | 3         | 0.24%   |
| Vernon         | 3         | 0.24%   |
| Valencia       | 3         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 191       | 228    | 12.8%   |
| WDC                         | 143       | 172    | 9.58%   |
| Toshiba                     | 127       | 144    | 8.51%   |
| Seagate                     | 124       | 140    | 8.31%   |
| SanDisk                     | 115       | 136    | 7.71%   |
| Unknown                     | 94        | 115    | 6.3%    |
| Kingston                    | 83        | 100    | 5.56%   |
| Apple                       | 63        | 70     | 4.22%   |
| Crucial                     | 58        | 69     | 3.89%   |
| HGST                        | 48        | 57     | 3.22%   |
| Intel                       | 46        | 62     | 3.08%   |
| Hitachi                     | 45        | 48     | 3.02%   |
| SK hynix                    | 40        | 49     | 2.68%   |
| A-DATA Technology           | 27        | 31     | 1.81%   |
| Micron Technology           | 26        | 28     | 1.74%   |
| KIOXIA                      | 17        | 28     | 1.14%   |
| China                       | 16        | 16     | 1.07%   |
| Fujitsu                     | 11        | 13     | 0.74%   |
| Phison                      | 10        | 11     | 0.67%   |
| LITEON                      | 9         | 9      | 0.6%    |
| SPCC                        | 8         | 8      | 0.54%   |
| Silicon Motion              | 7         | 8      | 0.47%   |
| PNY                         | 7         | 9      | 0.47%   |
| Unknown                     | 7         | 8      | 0.47%   |
| JMicron Technology          | 6         | 6      | 0.4%    |
| Intenso                     | 6         | 7      | 0.4%    |
| Transcend                   | 5         | 6      | 0.34%   |
| Phison Electronics          | 5         | 5      | 0.34%   |
| Patriot                     | 5         | 7      | 0.34%   |
| Kingston Technology Company | 5         | 5      | 0.34%   |
| Hewlett-Packard             | 5         | 7      | 0.34%   |
| Gigabyte Technology         | 5         | 5      | 0.34%   |
| Yangtze Memory Technologies | 4         | 4      | 0.27%   |
| Union Memory                | 4         | 5      | 0.27%   |
| KingDian                    | 4         | 6      | 0.27%   |
| Fanxiang                    | 4         | 4      | 0.27%   |
| Apacer                      | 4         | 6      | 0.27%   |
| TO Exter                    | 3         | 3      | 0.2%    |
| Star Drive                  | 3         | 3      | 0.2%    |
| OCZ                         | 3         | 4      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                            | 27        | 1.76%   |
| Kingston SA400S37240G 240GB SSD                   | 24        | 1.57%   |
| Unknown MMC Card  64GB                            | 23        | 1.5%    |
| Unknown MMC Card  32GB                            | 22        | 1.44%   |
| Seagate ST1000LM035-1RK172 1TB                    | 21        | 1.37%   |
| Samsung NVMe SSD Drive 512GB                      | 17        | 1.11%   |
| Toshiba MQ04ABF100 1TB                            | 15        | 0.98%   |
| Seagate ST500LT012-1DG142 500GB                   | 15        | 0.98%   |
| SanDisk NVMe SSD Drive 512GB                      | 15        | 0.98%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 14        | 0.91%   |
| HGST HTS721010A9E630 1TB                          | 14        | 0.91%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 13        | 0.85%   |
| Unknown MMC Card  128GB                           | 13        | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 13        | 0.85%   |
| Toshiba MQ01ABF050 500GB                          | 11        | 0.72%   |
| Kingston SA400S37120G 120GB SSD                   | 11        | 0.72%   |
| HGST HTS545050A7E680 500GB                        | 10        | 0.65%   |
| Apple SSD SM0128G 121GB                           | 10        | 0.65%   |
| Unknown MMC Card  16GB                            | 9         | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                | 9         | 0.59%   |
| Samsung SSD 860 EVO 500GB                         | 9         | 0.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 9         | 0.59%   |
| Samsung SSD 860 EVO 250GB                         | 8         | 0.52%   |
| Samsung SSD 850 EVO 250GB                         | 8         | 0.52%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 7         | 0.46%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 7         | 0.46%   |
| SK hynix NVMe SSD Drive 512GB                     | 7         | 0.46%   |
| SanDisk NVMe SSD Drive 256GB                      | 7         | 0.46%   |
| Samsung SSD 850 EVO 500GB                         | 7         | 0.46%   |
| Intel NVMe SSD Drive 512GB                        | 7         | 0.46%   |
| HGST HTS541010A9E680 1TB                          | 7         | 0.46%   |
| Crucial CT500MX500SSD1 500GB                      | 7         | 0.46%   |
| Crucial CT240BX500SSD1 240GB                      | 7         | 0.46%   |
| Apple SSD SM0256F 256GB                           | 7         | 0.46%   |
| Unknown                                           | 7         | 0.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 6         | 0.39%   |
| Seagate ST9500325AS 500GB                         | 6         | 0.39%   |
| HGST HTS541010B7E610 1TB                          | 6         | 0.39%   |
| Crucial CT1000MX500SSD1 1TB                       | 6         | 0.39%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 5         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 122       | 137    | 27.66%  |
| Toshiba             | 97        | 107    | 22%     |
| WDC                 | 94        | 112    | 21.32%  |
| HGST                | 48        | 57     | 10.88%  |
| Hitachi             | 45        | 48     | 10.2%   |
| Fujitsu             | 11        | 13     | 2.49%   |
| Samsung Electronics | 6         | 8      | 1.36%   |
| Apple               | 5         | 5      | 1.13%   |
| TO Exter            | 3         | 3      | 0.68%   |
| JMicron Technology  | 3         | 3      | 0.68%   |
| Unknown             | 2         | 2      | 0.45%   |
| SABRENT             | 2         | 2      | 0.45%   |
| StoreJet            | 1         | 1      | 0.23%   |
| Generic-            | 1         | 1      | 0.23%   |
| ASMT                | 1         | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 98        | 115    | 16.81%  |
| Kingston            | 69        | 81     | 11.84%  |
| SanDisk             | 61        | 74     | 10.46%  |
| Crucial             | 58        | 69     | 9.95%   |
| Apple               | 55        | 61     | 9.43%   |
| WDC                 | 36        | 41     | 6.17%   |
| A-DATA Technology   | 23        | 26     | 3.95%   |
| Intel               | 19        | 21     | 3.26%   |
| China               | 16        | 16     | 2.74%   |
| Toshiba             | 14        | 18     | 2.4%    |
| Micron Technology   | 13        | 15     | 2.23%   |
| SPCC                | 8         | 8      | 1.37%   |
| SK hynix            | 8         | 8      | 1.37%   |
| LITEON              | 8         | 8      | 1.37%   |
| PNY                 | 7         | 9      | 1.2%    |
| Transcend           | 5         | 6      | 0.86%   |
| Patriot             | 5         | 7      | 0.86%   |
| Intenso             | 5         | 6      | 0.86%   |
| Hewlett-Packard     | 5         | 7      | 0.86%   |
| Apacer              | 4         | 6      | 0.69%   |
| OCZ                 | 3         | 4      | 0.51%   |
| NGFF                | 3         | 4      | 0.51%   |
| KingDian            | 3         | 4      | 0.51%   |
| Gigabyte Technology | 3         | 3      | 0.51%   |
| VISIPRO             | 2         | 2      | 0.34%   |
| V-GeN               | 2         | 2      | 0.34%   |
| Star                | 2         | 2      | 0.34%   |
| Phison              | 2         | 3      | 0.34%   |
| OWC                 | 2         | 2      | 0.34%   |
| Netac               | 2         | 2      | 0.34%   |
| LS                  | 2         | 2      | 0.34%   |
| LITEONIT            | 2         | 2      | 0.34%   |
| Lexar               | 2         | 2      | 0.34%   |
| FORESEE             | 2         | 2      | 0.34%   |
| Fanxiang            | 2         | 2      | 0.34%   |
| Unknown             | 2         | 2      | 0.34%   |
| XrayDisk            | 1         | 2      | 0.17%   |
| VT                  | 1         | 1      | 0.17%   |
| USB30               | 1         | 1      | 0.17%   |
| Union Memory        | 1         | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 551       | 674    | 38.45%  |
| HDD     | 427       | 500    | 29.8%   |
| NVMe    | 332       | 427    | 23.17%  |
| MMC     | 90        | 111    | 6.28%   |
| Unknown | 33        | 37     | 2.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 896       | 1158   | 65.74%  |
| NVMe | 332       | 427    | 24.36%  |
| MMC  | 90        | 111    | 6.6%    |
| SAS  | 45        | 53     | 3.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 690       | 856    | 71.35%  |
| 0.51-1.0   | 247       | 281    | 25.54%  |
| 1.01-2.0   | 29        | 36     | 3%      |
| 3.01-4.0   | 1         | 1      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 507       | 40.89%  |
| 251-500        | 336       | 27.1%   |
| 501-1000       | 168       | 13.55%  |
| 51-100         | 94        | 7.58%   |
| 21-50          | 48        | 3.87%   |
| 1001-2000      | 47        | 3.79%   |
| 1-20           | 18        | 1.45%   |
| 2001-3000      | 11        | 0.89%   |
| More than 3000 | 7         | 0.56%   |
| Unknown        | 4         | 0.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 564       | 43.75%  |
| 21-50          | 345       | 26.76%  |
| 51-100         | 146       | 11.33%  |
| 101-250        | 126       | 9.78%   |
| 251-500        | 59        | 4.58%   |
| 501-1000       | 29        | 2.25%   |
| 1001-2000      | 11        | 0.85%   |
| 2001-3000      | 4         | 0.31%   |
| Unknown        | 4         | 0.31%   |
| More than 3000 | 1         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Notebooks | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD            | 1         | 1      | 4%      |
| WDC WD5000BPKT-75PK4T0 500GB                | 1         | 1      | 4%      |
| WDC WD10SPZX-24Z10 1TB                      | 1         | 1      | 4%      |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 4%      |
| Toshiba MK3259GSXP 320GB                    | 1         | 1      | 4%      |
| Seagate ST500LM030-2E717D 500GB             | 1         | 1      | 4%      |
| Seagate ST320LT020-9YG142 320GB             | 1         | 1      | 4%      |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1      | 4%      |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 1         | 1      | 4%      |
| SanDisk SD9SN8W-128G-1006 128GB SSD         | 1         | 1      | 4%      |
| SanDisk SD7SB3Q256G1002 256GB SSD           | 1         | 1      | 4%      |
| LS 128GB M300 SSD                           | 1         | 1      | 4%      |
| Kingston SV300S37A240G 240GB SSD            | 1         | 1      | 4%      |
| Kingston SUV400S37480G 480GB SSD            | 1         | 1      | 4%      |
| Intel SSDPEKKF512G7H BTPY71141D7T512F 512GB | 1         | 1      | 4%      |
| Hitachi HTS547564A9E384 640GB               | 1         | 1      | 4%      |
| HGST HTS725050A7E630 500GB                  | 1         | 1      | 4%      |
| HGST HTS545050A7E680 500GB                  | 1         | 1      | 4%      |
| HGST HTS541010A9E680 1TB                    | 1         | 1      | 4%      |
| Fujitsu MHZ2160BH G2 160GB                  | 1         | 2      | 4%      |
| Crucial CT512M550SSD3 512GB                 | 1         | 1      | 4%      |
| Crucial CT240M500SSD3 240GB                 | 1         | 1      | 4%      |
| China SSD 256GB                             | 1         | 1      | 4%      |
| Apple SSD SM256C 256GB                      | 1         | 1      | 4%      |
| A-DATA Technology SP900NS38 128GB SSD       | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 4         | 4      | 16%     |
| WDC               | 3         | 3      | 12%     |
| HGST              | 3         | 3      | 12%     |
| Toshiba           | 2         | 2      | 8%      |
| SanDisk           | 2         | 2      | 8%      |
| Kingston          | 2         | 2      | 8%      |
| Crucial           | 2         | 2      | 8%      |
| LS                | 1         | 1      | 4%      |
| Intel             | 1         | 1      | 4%      |
| Hitachi           | 1         | 1      | 4%      |
| Fujitsu           | 1         | 2      | 4%      |
| China             | 1         | 1      | 4%      |
| Apple             | 1         | 1      | 4%      |
| A-DATA Technology | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 30.77%  |
| HGST    | 3         | 3      | 23.08%  |
| WDC     | 2         | 2      | 15.38%  |
| Toshiba | 2         | 2      | 15.38%  |
| Hitachi | 1         | 1      | 7.69%   |
| Fujitsu | 1         | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 14     | 52%     |
| SSD  | 11        | 11     | 44%     |
| NVMe | 1         | 1      | 4%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-75Z10T1 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1039      | 1487   | 82.85%  |
| Works    | 189       | 235    | 15.07%  |
| Malfunc  | 25        | 26     | 1.99%   |
| Failed   | 1         | 1      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 854       | 62.02%  |
| AMD                            | 125       | 9.08%   |
| Samsung Electronics            | 119       | 8.64%   |
| SanDisk                        | 69        | 5.01%   |
| Nvidia                         | 34        | 2.47%   |
| SK hynix                       | 31        | 2.25%   |
| Kingston Technology Company    | 20        | 1.45%   |
| Toshiba America Info Systems   | 18        | 1.31%   |
| Phison Electronics             | 18        | 1.31%   |
| KIOXIA                         | 16        | 1.16%   |
| Micron Technology              | 13        | 0.94%   |
| Marvell Technology Group       | 9         | 0.65%   |
| Silicon Motion                 | 8         | 0.58%   |
| Union Memory (Shenzhen)        | 7         | 0.51%   |
| ADATA Technology               | 6         | 0.44%   |
| Lite-On Technology             | 5         | 0.36%   |
| Yangtze Memory Technologies    | 4         | 0.29%   |
| Solid State Storage Technology | 3         | 0.22%   |
| Realtek Semiconductor          | 3         | 0.22%   |
| Micron/Crucial Technology      | 3         | 0.22%   |
| Apple                          | 3         | 0.22%   |
| Shenzhen Longsys Electronics   | 2         | 0.15%   |
| Biwin Storage Technology       | 2         | 0.15%   |
| ASMedia Technology             | 2         | 0.15%   |
| Solidigm                       | 1         | 0.07%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.07%   |
| INNOGRIT                       | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 123       | 8.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 115       | 7.94%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 114       | 7.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 80        | 5.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 64        | 4.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 52        | 3.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 37        | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 34        | 2.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 32        | 2.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 32        | 2.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 32        | 2.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 30        | 2.07%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 29        | 2%      |
| Intel Volume Management Device NVMe RAID Controller                                    | 29        | 2%      |
| Intel Comet Lake SATA AHCI Controller                                                  | 23        | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 23        | 1.59%   |
| Nvidia MCP79 AHCI Controller                                                           | 22        | 1.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 21        | 1.45%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                             | 19        | 1.31%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 19        | 1.31%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                              | 18        | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 17        | 1.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 16        | 1.1%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 13        | 0.9%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 12        | 0.83%   |
| Intel SSD 660P Series                                                                  | 12        | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 12        | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 12        | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 12        | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 12        | 0.83%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                                     | 11        | 0.76%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 11        | 0.76%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 10        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 10        | 0.69%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 9         | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                  | 9         | 0.62%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                  | 9         | 0.62%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 9         | 0.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 9         | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 8         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 922       | 65.58%  |
| NVMe | 330       | 23.47%  |
| RAID | 97        | 6.9%    |
| IDE  | 57        | 4.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1030      | 85.05%  |
| AMD    | 181       | 14.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 24        | 1.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 21        | 1.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 19        | 1.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 19        | 1.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 19        | 1.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 18        | 1.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 16        | 1.32%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 16        | 1.32%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 1.16%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 14        | 1.16%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 14        | 1.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 1.07%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 1.07%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 1.07%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 12        | 0.99%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 12        | 0.99%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 12        | 0.99%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 11        | 0.91%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 11        | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 0.83%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 10        | 0.83%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 0.83%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 10        | 0.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 0.74%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 0.74%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 9         | 0.74%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 0.74%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 9         | 0.74%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 9         | 0.74%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 9         | 0.74%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 8         | 0.66%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 8         | 0.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 0.58%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 7         | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.58%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.58%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 7         | 0.58%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 7         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 332       | 27.42%  |
| Intel Core i7                        | 260       | 21.47%  |
| Intel Core i3                        | 119       | 9.83%   |
| Other                                | 85        | 7.02%   |
| Intel Celeron                        | 77        | 6.36%   |
| Intel Core 2 Duo                     | 72        | 5.95%   |
| AMD Ryzen 5                          | 52        | 4.29%   |
| Intel Pentium                        | 30        | 2.48%   |
| AMD Ryzen 7                          | 28        | 2.31%   |
| Intel Atom                           | 16        | 1.32%   |
| AMD A6                               | 13        | 1.07%   |
| Intel Pentium Silver                 | 11        | 0.91%   |
| Intel Pentium Dual-Core              | 11        | 0.91%   |
| AMD Ryzen 3                          | 11        | 0.91%   |
| AMD A8                               | 10        | 0.83%   |
| AMD A4                               | 9         | 0.74%   |
| AMD A10                              | 8         | 0.66%   |
| Intel Core 2                         | 7         | 0.58%   |
| AMD A12                              | 7         | 0.58%   |
| AMD Ryzen 5 PRO                      | 5         | 0.41%   |
| Intel Core m3                        | 4         | 0.33%   |
| Intel Celeron Dual-Core              | 4         | 0.33%   |
| AMD Ryzen 7 PRO                      | 4         | 0.33%   |
| AMD E1                               | 4         | 0.33%   |
| Intel Genuine                        | 3         | 0.25%   |
| AMD Athlon                           | 3         | 0.25%   |
| Intel Xeon                           | 2         | 0.17%   |
| Intel Core m5                        | 2         | 0.17%   |
| AMD Ryzen 9                          | 2         | 0.17%   |
| AMD Phenom II                        | 2         | 0.17%   |
| AMD E2                               | 2         | 0.17%   |
| AMD E                                | 2         | 0.17%   |
| AMD C-60                             | 2         | 0.17%   |
| Intel Pentium Dual                   | 1         | 0.08%   |
| Intel Core m7                        | 1         | 0.08%   |
| Intel Core i9                        | 1         | 0.08%   |
| Intel Core 2 Quad                    | 1         | 0.08%   |
| Intel Celeron M                      | 1         | 0.08%   |
| AMD V140                             | 1         | 0.08%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 725       | 59.87%  |
| 4      | 367       | 30.31%  |
| 6      | 60        | 4.95%   |
| 8      | 39        | 3.22%   |
| 1      | 13        | 1.07%   |
| 10     | 3         | 0.25%   |
| 12     | 2         | 0.17%   |
| 14     | 1         | 0.08%   |
| 5      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1211      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 913       | 75.33%  |
| 1      | 299       | 24.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1207      | 99.67%  |
| Unknown        | 4         | 0.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 373       | 30.08%  |
| 0x206a7    | 90        | 7.26%   |
| 0x306a9    | 72        | 5.81%   |
| 0x40651    | 48        | 3.87%   |
| 0x1067a    | 42        | 3.39%   |
| 0x806c1    | 39        | 3.15%   |
| 0x406e3    | 38        | 3.06%   |
| 0x806ea    | 36        | 2.9%    |
| 0x806e9    | 36        | 2.9%    |
| 0x306d4    | 33        | 2.66%   |
| 0x806ec    | 31        | 2.5%    |
| 0x20655    | 26        | 2.1%    |
| 0x306c3    | 24        | 1.94%   |
| 0x20652    | 17        | 1.37%   |
| 0x706e5    | 15        | 1.21%   |
| 0x30678    | 15        | 1.21%   |
| 0x906ea    | 14        | 1.13%   |
| 0x406c3    | 14        | 1.13%   |
| 0x06006705 | 14        | 1.13%   |
| 0x806eb    | 13        | 1.05%   |
| 0x706a1    | 13        | 1.05%   |
| 0x08108109 | 13        | 1.05%   |
| 0xa0652    | 12        | 0.97%   |
| 0x706a8    | 12        | 0.97%   |
| 0x08600106 | 12        | 0.97%   |
| 0x906e9    | 11        | 0.89%   |
| 0x506c9    | 11        | 0.89%   |
| 0x10676    | 11        | 0.89%   |
| 0x08608103 | 10        | 0.81%   |
| 0x40661    | 8         | 0.65%   |
| 0x0a50000c | 8         | 0.65%   |
| 0x08108102 | 8         | 0.65%   |
| 0x07030105 | 8         | 0.65%   |
| 0x6fd      | 7         | 0.56%   |
| 0x406c4    | 7         | 0.56%   |
| 0x06001119 | 7         | 0.56%   |
| 0x506e3    | 6         | 0.48%   |
| 0x05000119 | 6         | 0.48%   |
| 0x6fb      | 5         | 0.4%    |
| 0x6f6      | 5         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 194       | 16.01%  |
| Haswell          | 121       | 9.98%   |
| SandyBridge      | 114       | 9.41%   |
| IvyBridge        | 101       | 8.33%   |
| Penryn           | 80        | 6.6%    |
| Skylake          | 70        | 5.78%   |
| TigerLake        | 62        | 5.12%   |
| Westmere         | 61        | 5.03%   |
| Broadwell        | 50        | 4.13%   |
| Silvermont       | 46        | 3.8%    |
| Goldmont plus    | 38        | 3.14%   |
| Excavator        | 34        | 2.81%   |
| Zen+             | 32        | 2.64%   |
| Unknown          | 30        | 2.48%   |
| IceLake          | 26        | 2.15%   |
| Zen 2            | 24        | 1.98%   |
| Core             | 22        | 1.82%   |
| CometLake        | 15        | 1.24%   |
| Zen 3            | 13        | 1.07%   |
| Zen              | 13        | 1.07%   |
| Puma             | 12        | 0.99%   |
| Goldmont         | 12        | 0.99%   |
| Piledriver       | 9         | 0.74%   |
| Bobcat           | 7         | 0.58%   |
| K10              | 5         | 0.41%   |
| Jaguar           | 5         | 0.41%   |
| Alderlake Hybrid | 5         | 0.41%   |
| Bonnell          | 4         | 0.33%   |
| Nehalem          | 2         | 0.17%   |
| Tremont          | 1         | 0.08%   |
| Steamroller      | 1         | 0.08%   |
| K8 Hammer        | 1         | 0.08%   |
| K8 & K10 hybrid  | 1         | 0.08%   |
| K10 Llano        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 932       | 63.36%  |
| Nvidia | 278       | 18.9%   |
| AMD    | 261       | 17.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 101       | 6.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 96        | 6.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 69        | 4.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 52        | 3.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 51        | 3.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 51        | 3.36%   |
| Intel HD Graphics 620                                                                    | 50        | 3.3%    |
| Intel UHD Graphics 620                                                                   | 43        | 2.84%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 37        | 2.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 34        | 2.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 32        | 2.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 32        | 2.11%   |
| Intel HD Graphics 5500                                                                   | 30        | 1.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 28        | 1.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 27        | 1.78%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 24        | 1.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 23        | 1.52%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 22        | 1.45%   |
| Nvidia C79 [GeForce 9400M]                                                               | 21        | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 1.39%   |
| AMD Lucienne                                                                             | 19        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 1.19%   |
| Intel HD Graphics 6000                                                                   | 17        | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 0.92%   |
| Intel HD Graphics 630                                                                    | 14        | 0.92%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 14        | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 0.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 13        | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 0.86%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 13        | 0.86%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 12        | 0.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12        | 0.79%   |
| Nvidia GP108M [GeForce MX150]                                                            | 11        | 0.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 11        | 0.73%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 11        | 0.73%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 0.73%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 11        | 0.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 681       | 56.23%  |
| Intel + Nvidia | 194       | 16.02%  |
| 1 x AMD        | 173       | 14.29%  |
| 1 x Nvidia     | 69        | 5.7%    |
| Intel + AMD    | 53        | 4.38%   |
| 2 x AMD        | 24        | 1.98%   |
| AMD + Nvidia   | 10        | 0.83%   |
| 2 x Nvidia     | 4         | 0.33%   |
| Other          | 3         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1088      | 89.33%  |
| Proprietary | 110       | 9.03%   |
| Unknown     | 20        | 1.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 849       | 69.19%  |
| 1.01-2.0   | 137       | 11.17%  |
| 0.01-0.5   | 116       | 9.45%   |
| 0.51-1.0   | 68        | 5.54%   |
| 3.01-4.0   | 41        | 3.34%   |
| 5.01-6.0   | 10        | 0.81%   |
| 7.01-8.0   | 4         | 0.33%   |
| 2.01-3.0   | 2         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 243       | 18.26%  |
| LG Display              | 183       | 13.75%  |
| BOE                     | 180       | 13.52%  |
| Chimei Innolux          | 179       | 13.45%  |
| Apple                   | 140       | 10.52%  |
| Samsung Electronics     | 116       | 8.72%   |
| Sharp                   | 32        | 2.4%    |
| Dell                    | 28        | 2.1%    |
| Lenovo                  | 27        | 2.03%   |
| Chi Mei Optoelectronics | 27        | 2.03%   |
| PANDA                   | 19        | 1.43%   |
| Goldstar                | 14        | 1.05%   |
| Hewlett-Packard         | 13        | 0.98%   |
| CSO                     | 8         | 0.6%    |
| BenQ                    | 8         | 0.6%    |
| Acer                    | 8         | 0.6%    |
| Toshiba                 | 7         | 0.53%   |
| AOC                     | 7         | 0.53%   |
| ViewSonic               | 6         | 0.45%   |
| Sony                    | 5         | 0.38%   |
| Philips                 | 5         | 0.38%   |
| InfoVision              | 5         | 0.38%   |
| CPT                     | 5         | 0.38%   |
| Panasonic               | 4         | 0.3%    |
| LG Philips              | 4         | 0.3%    |
| Ancor Communications    | 4         | 0.3%    |
| Unknown                 | 3         | 0.23%   |
| Mi                      | 3         | 0.23%   |
| Vestel Elektronik       | 2         | 0.15%   |
| TMX                     | 2         | 0.15%   |
| LGD                     | 2         | 0.15%   |
| JDI                     | 2         | 0.15%   |
| HKC                     | 2         | 0.15%   |
| HannStar                | 2         | 0.15%   |
| Fujitsu Siemens         | 2         | 0.15%   |
| ___                     | 1         | 0.08%   |
| XCX                     | 1         | 0.08%   |
| Vizio                   | 1         | 0.08%   |
| VIE                     | 1         | 0.08%   |
| Unknown (XXX)           | 1         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 13        | 0.96%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 12        | 0.89%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 12        | 0.89%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 12        | 0.89%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 12        | 0.89%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 10        | 0.74%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 10        | 0.74%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 10        | 0.74%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 9         | 0.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 9         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 8         | 0.59%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 8         | 0.59%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 8         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 7         | 0.52%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 7         | 0.52%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                 | 7         | 0.52%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 6         | 0.44%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 6         | 0.44%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 6         | 0.44%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 6         | 0.44%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch        | 6         | 0.44%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 6         | 0.44%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch               | 6         | 0.44%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch               | 6         | 0.44%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 6         | 0.44%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 5         | 0.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 5         | 0.37%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 5         | 0.37%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 5         | 0.37%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch      | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 5         | 0.37%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 5         | 0.37%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 5         | 0.37%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 5         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 476       | 37.45%  |
| 1366x768 (WXGA)    | 418       | 32.89%  |
| 1280x800 (WXGA)    | 80        | 6.29%   |
| 1600x900 (HD+)     | 62        | 4.88%   |
| 1440x900 (WXGA+)   | 53        | 4.17%   |
| 3840x2160 (4K)     | 38        | 2.99%   |
| 2560x1440 (QHD)    | 26        | 2.05%   |
| 2880x1800          | 22        | 1.73%   |
| 1920x1200 (WUXGA)  | 18        | 1.42%   |
| 2560x1600          | 16        | 1.26%   |
| 1680x1050 (WSXGA+) | 9         | 0.71%   |
| 3000x2000          | 7         | 0.55%   |
| 1280x1024 (SXGA)   | 7         | 0.55%   |
| 1024x600           | 5         | 0.39%   |
| 2560x1080          | 4         | 0.31%   |
| 3840x2400          | 3         | 0.24%   |
| 3200x1800 (QHD+)   | 3         | 0.24%   |
| 2160x1440          | 3         | 0.24%   |
| 1920x540           | 3         | 0.24%   |
| 3440x1440          | 2         | 0.16%   |
| 3072x1920          | 2         | 0.16%   |
| 1920x1280          | 2         | 0.16%   |
| 1360x768           | 2         | 0.16%   |
| Unknown            | 2         | 0.16%   |
| 4240x1080          | 1         | 0.08%   |
| 3840x1100          | 1         | 0.08%   |
| 3840x1080          | 1         | 0.08%   |
| 2256x1504          | 1         | 0.08%   |
| 1920x515           | 1         | 0.08%   |
| 1680x945           | 1         | 0.08%   |
| 1600x1200          | 1         | 0.08%   |
| 1400x1050          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 508       | 38%     |
| 13      | 287       | 21.47%  |
| 14      | 164       | 12.27%  |
| 17      | 83        | 6.21%   |
| 11      | 41        | 3.07%   |
| 27      | 38        | 2.84%   |
| 12      | 33        | 2.47%   |
| 24      | 30        | 2.24%   |
| 23      | 22        | 1.65%   |
| 21      | 22        | 1.65%   |
| Unknown | 20        | 1.5%    |
| 16      | 12        | 0.9%    |
| 31      | 10        | 0.75%   |
| 19      | 9         | 0.67%   |
| 84      | 8         | 0.6%    |
| 18      | 8         | 0.6%    |
| 10      | 7         | 0.52%   |
| 34      | 6         | 0.45%   |
| 72      | 5         | 0.37%   |
| 25      | 4         | 0.3%    |
| 22      | 4         | 0.3%    |
| 54      | 2         | 0.15%   |
| 52      | 2         | 0.15%   |
| 86      | 1         | 0.07%   |
| 74      | 1         | 0.07%   |
| 69      | 1         | 0.07%   |
| 65      | 1         | 0.07%   |
| 60      | 1         | 0.07%   |
| 48      | 1         | 0.07%   |
| 43      | 1         | 0.07%   |
| 40      | 1         | 0.07%   |
| 37      | 1         | 0.07%   |
| 33      | 1         | 0.07%   |
| 26      | 1         | 0.07%   |
| 20      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 781       | 58.9%   |
| 201-300     | 251       | 18.93%  |
| 351-400     | 104       | 7.84%   |
| 501-600     | 84        | 6.33%   |
| 401-500     | 38        | 2.87%   |
| Unknown     | 20        | 1.51%   |
| 601-700     | 15        | 1.13%   |
| 1501-2000   | 15        | 1.13%   |
| 1001-1500   | 8         | 0.6%    |
| 701-800     | 7         | 0.53%   |
| 801-900     | 2         | 0.15%   |
| 901-1000    | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 953       | 79.02%  |
| 16/10   | 198       | 16.42%  |
| 3/2     | 19        | 1.58%   |
| Unknown | 17        | 1.41%   |
| 5/4     | 7         | 0.58%   |
| 21/9    | 6         | 0.5%    |
| 4/3     | 2         | 0.17%   |
| 3.73    | 1         | 0.08%   |
| 3.40    | 1         | 0.08%   |
| 1.96    | 1         | 0.08%   |
| 0.56    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 508       | 38.14%  |
| 81-90          | 346       | 25.98%  |
| 71-80          | 102       | 7.66%   |
| 121-130        | 67        | 5.03%   |
| 201-250        | 60        | 4.5%    |
| 51-60          | 42        | 3.15%   |
| 301-350        | 38        | 2.85%   |
| 61-70          | 33        | 2.48%   |
| More than 1000 | 22        | 1.65%   |
| Unknown        | 20        | 1.5%    |
| 351-500        | 17        | 1.28%   |
| 151-200        | 16        | 1.2%    |
| 131-140        | 15        | 1.13%   |
| 251-300        | 12        | 0.9%    |
| 141-150        | 10        | 0.75%   |
| 111-120        | 10        | 0.75%   |
| 41-50          | 7         | 0.53%   |
| 501-1000       | 4         | 0.3%    |
| 91-100         | 3         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 508       | 38.84%  |
| 101-120       | 487       | 37.23%  |
| 51-100        | 147       | 11.24%  |
| 161-240       | 97        | 7.42%   |
| More than 240 | 33        | 2.52%   |
| Unknown       | 20        | 1.53%   |
| 1-50          | 16        | 1.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1048      | 85.2%   |
| 2     | 150       | 12.2%   |
| 0     | 18        | 1.46%   |
| 3     | 13        | 1.06%   |
| 4     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 572       | 30.26%  |
| Intel                             | 547       | 28.94%  |
| Qualcomm Atheros                  | 271       | 14.34%  |
| Broadcom                          | 208       | 11.01%  |
| Broadcom Limited                  | 56        | 2.96%   |
| Nvidia                            | 27        | 1.43%   |
| Marvell Technology Group          | 23        | 1.22%   |
| MediaTek                          | 20        | 1.06%   |
| Ralink                            | 15        | 0.79%   |
| TP-Link                           | 14        | 0.74%   |
| Ralink Technology                 | 12        | 0.63%   |
| Samsung Electronics               | 11        | 0.58%   |
| ASIX Electronics                  | 11        | 0.58%   |
| Sierra Wireless                   | 10        | 0.53%   |
| Huawei Technologies               | 9         | 0.48%   |
| Xiaomi                            | 8         | 0.42%   |
| Ericsson Business Mobile Networks | 8         | 0.42%   |
| Qualcomm                          | 7         | 0.37%   |
| Hewlett-Packard                   | 7         | 0.37%   |
| D-Link                            | 6         | 0.32%   |
| Dell                              | 4         | 0.21%   |
| Qualcomm Atheros Communications   | 3         | 0.16%   |
| OPPO Electronics                  | 3         | 0.16%   |
| Lenovo                            | 3         | 0.16%   |
| JMicron Technology                | 3         | 0.16%   |
| Google                            | 3         | 0.16%   |
| Apple                             | 3         | 0.16%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.11%   |
| NetGear                           | 2         | 0.11%   |
| D-Link System                     | 2         | 0.11%   |
| ASUSTek Computer                  | 2         | 0.11%   |
| ZyDAS                             | 1         | 0.05%   |
| TRENDnet                          | 1         | 0.05%   |
| Toshiba                           | 1         | 0.05%   |
| Sitecom Europe                    | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.05%   |
| NEC Computers                     | 1         | 0.05%   |
| Motorola PCS                      | 1         | 0.05%   |
| LSI                               | 1         | 0.05%   |
| Linksys                           | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 334       | 14.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 113       | 4.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 54        | 2.38%   |
| Intel Wireless 8260                                                    | 48        | 2.11%   |
| Intel Wi-Fi 6 AX201                                                    | 48        | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 47        | 2.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 42        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 42        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 40        | 1.76%   |
| Intel Wireless 7265                                                    | 38        | 1.67%   |
| Intel Wireless 7260                                                    | 38        | 1.67%   |
| Intel Wireless 8265 / 8275                                             | 36        | 1.59%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 36        | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 34        | 1.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 33        | 1.45%   |
| Intel Wi-Fi 6 AX200                                                    | 30        | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 30        | 1.32%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 30        | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 29        | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 29        | 1.28%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 27        | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 23        | 1.01%   |
| Nvidia MCP79 Ethernet                                                  | 23        | 1.01%   |
| Intel Wireless 3165                                                    | 23        | 1.01%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 22        | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 21        | 0.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 21        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 21        | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                          | 20        | 0.88%   |
| Intel Ethernet Connection I219-LM                                      | 18        | 0.79%   |
| Intel Ethernet Connection I218-LM                                      | 17        | 0.75%   |
| Intel 82577LM Gigabit Network Connection                               | 17        | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 14        | 0.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 14        | 0.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 14        | 0.62%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 14        | 0.62%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 13        | 0.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 13        | 0.57%   |
| Intel Centrino Advanced-N 6235                                         | 13        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 517       | 40.61%  |
| Qualcomm Atheros                | 235       | 18.46%  |
| Realtek Semiconductor           | 196       | 15.4%   |
| Broadcom                        | 186       | 14.61%  |
| Broadcom Limited                | 49        | 3.85%   |
| Ralink                          | 15        | 1.18%   |
| MediaTek                        | 15        | 1.18%   |
| TP-Link                         | 14        | 1.1%    |
| Ralink Technology               | 12        | 0.94%   |
| Sierra Wireless                 | 10        | 0.79%   |
| Qualcomm                        | 4         | 0.31%   |
| D-Link                          | 4         | 0.31%   |
| Qualcomm Atheros Communications | 3         | 0.24%   |
| Dell                            | 2         | 0.16%   |
| D-Link System                   | 2         | 0.16%   |
| ASUSTek Computer                | 2         | 0.16%   |
| ZyDAS                           | 1         | 0.08%   |
| TRENDnet                        | 1         | 0.08%   |
| Sitecom Europe                  | 1         | 0.08%   |
| NetGear                         | 1         | 0.08%   |
| Hewlett-Packard                 | 1         | 0.08%   |
| FIBOCOM                         | 1         | 0.08%   |
| Edimax Technology               | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 54        | 4.22%   |
| Intel Wireless 8260                                                  | 48        | 3.75%   |
| Intel Wi-Fi 6 AX201                                                  | 48        | 3.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 47        | 3.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 42        | 3.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 40        | 3.12%   |
| Intel Wireless 7265                                                  | 38        | 2.97%   |
| Intel Wireless 7260                                                  | 38        | 2.97%   |
| Intel Wireless 8265 / 8275                                           | 36        | 2.81%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 36        | 2.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 34        | 2.65%   |
| Intel Wi-Fi 6 AX200                                                  | 30        | 2.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 30        | 2.34%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 30        | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 29        | 2.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 29        | 2.26%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 27        | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 23        | 1.8%    |
| Intel Wireless 3165                                                  | 23        | 1.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                      | 22        | 1.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 21        | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 21        | 1.64%   |
| Broadcom BCM43142 802.11b/g/n                                        | 20        | 1.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 14        | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 14        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 14        | 1.09%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 14        | 1.09%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 13        | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 13        | 1.01%   |
| Intel Centrino Advanced-N 6235                                       | 13        | 1.01%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 12        | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 12        | 0.94%   |
| Intel Wireless 3160                                                  | 12        | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 12        | 0.94%   |
| Intel Centrino Advanced-N 6200                                       | 12        | 0.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 10        | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 10        | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 10        | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 10        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 10        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 480       | 50%     |
| Intel                      | 200       | 20.83%  |
| Broadcom                   | 78        | 8.13%   |
| Qualcomm Atheros           | 70        | 7.29%   |
| Nvidia                     | 27        | 2.81%   |
| Marvell Technology Group   | 23        | 2.4%    |
| Samsung Electronics        | 11        | 1.15%   |
| ASIX Electronics           | 11        | 1.15%   |
| Xiaomi                     | 8         | 0.83%   |
| Broadcom Limited           | 8         | 0.83%   |
| Huawei Technologies        | 6         | 0.63%   |
| MediaTek                   | 5         | 0.52%   |
| Qualcomm                   | 3         | 0.31%   |
| OPPO Electronics           | 3         | 0.31%   |
| Lenovo                     | 3         | 0.31%   |
| JMicron Technology         | 3         | 0.31%   |
| Google                     | 3         | 0.31%   |
| Apple                      | 3         | 0.31%   |
| ZTE WCDMA Technologies MSM | 2         | 0.21%   |
| Hewlett-Packard            | 2         | 0.21%   |
| D-Link                     | 2         | 0.21%   |
| NetGear                    | 1         | 0.1%    |
| LSI                        | 1         | 0.1%    |
| Linksys                    | 1         | 0.1%    |
| LG Electronics             | 1         | 0.1%    |
| ICS Advent                 | 1         | 0.1%    |
| HMD Global                 | 1         | 0.1%    |
| DisplayLink                | 1         | 0.1%    |
| Attansic Technology        | 1         | 0.1%    |
| ADMtek                     | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 334       | 34.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 113       | 11.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 42        | 4.34%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 33        | 3.41%   |
| Nvidia MCP79 Ethernet                                                          | 23        | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 21        | 2.17%   |
| Intel Ethernet Connection I219-LM                                              | 18        | 1.86%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 1.76%   |
| Intel 82577LM Gigabit Network Connection                                       | 17        | 1.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 16        | 1.65%   |
| Intel 82567LM Gigabit Network Connection                                       | 12        | 1.24%   |
| Intel Ethernet Connection I217-LM                                              | 11        | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                           | 10        | 1.03%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 10        | 1.03%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 10        | 1.03%   |
| Intel Ethernet Connection I219-V                                               | 9         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                                          | 9         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 8         | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 8         | 0.83%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.72%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 7         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 6         | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 6         | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 6         | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 6         | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 0.62%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 6         | 0.62%   |
| Intel Ethernet Connection I217-V                                               | 6         | 0.62%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 5         | 0.52%   |
| Realtek Killer E2600 GbE Controller                                            | 5         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 5         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 5         | 0.52%   |
| MediaTek RMX3085                                                               | 5         | 0.52%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 5         | 0.52%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 0.41%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 4         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1199      | 55.92%  |
| Ethernet | 923       | 43.05%  |
| Modem    | 19        | 0.89%   |
| Unknown  | 3         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1018      | 83.24%  |
| Ethernet | 205       | 16.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 851       | 70.16%  |
| 1     | 335       | 27.62%  |
| 0     | 21        | 1.73%   |
| 3     | 6         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 928       | 75.51%  |
| Yes     | 300       | 24.41%  |
| Unknown | 1         | 0.08%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 420       | 40.11%  |
| Apple                           | 139       | 13.28%  |
| Realtek Semiconductor           | 112       | 10.7%   |
| Qualcomm Atheros Communications | 96        | 9.17%   |
| Broadcom                        | 55        | 5.25%   |
| Lite-On Technology              | 52        | 4.97%   |
| Foxconn / Hon Hai               | 42        | 4.01%   |
| IMC Networks                    | 32        | 3.06%   |
| Hewlett-Packard                 | 18        | 1.72%   |
| Toshiba                         | 17        | 1.62%   |
| Cambridge Silicon Radio         | 16        | 1.53%   |
| Dell                            | 15        | 1.43%   |
| Realtek                         | 11        | 1.05%   |
| Ralink                          | 10        | 0.96%   |
| Qcom                            | 2         | 0.19%   |
| ASUSTek Computer                | 2         | 0.19%   |
| Taiyo Yuden                     | 1         | 0.1%    |
| Ralink Technology               | 1         | 0.1%    |
| Opticis                         | 1         | 0.1%    |
| Logitech                        | 1         | 0.1%    |
| Fujitsu                         | 1         | 0.1%    |
| Foxconn International           | 1         | 0.1%    |
| Askey Computer                  | 1         | 0.1%    |
| Unknown                         | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 116       | 11.08%  |
| Intel Bluetooth Device                                                              | 78        | 7.45%   |
| Apple Bluetooth Host Controller                                                     | 77        | 7.35%   |
| Intel AX201 Bluetooth                                                               | 75        | 7.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 70        | 6.69%   |
| Realtek Bluetooth Radio                                                             | 53        | 5.06%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 53        | 5.06%   |
| Apple Bluetooth USB Host Controller                                                 | 45        | 4.3%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 33        | 3.15%   |
| Intel AX200 Bluetooth                                                               | 30        | 2.87%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 20        | 1.91%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 18        | 1.72%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 17        | 1.62%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 16        | 1.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 15        | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 15        | 1.43%   |
| Lite-On Bluetooth Device                                                            | 14        | 1.34%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 13        | 1.24%   |
| Realtek Bluetooth Radio                                                             | 11        | 1.05%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 11        | 1.05%   |
| Ralink RT3290 Bluetooth                                                             | 10        | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 10        | 0.96%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 10        | 0.96%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 10        | 0.96%   |
| IMC Networks Bluetooth Radio                                                        | 10        | 0.96%   |
| Apple Bluetooth HCI                                                                 | 10        | 0.96%   |
| Realtek RTL8821A Bluetooth                                                          | 9         | 0.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 9         | 0.86%   |
| Dell DW375 Bluetooth Module                                                         | 9         | 0.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 0.67%   |
| Intel AX210 Bluetooth                                                               | 7         | 0.67%   |
| IMC Networks Wireless_Device                                                        | 7         | 0.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 7         | 0.67%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 6         | 0.57%   |
| Realtek 802.11ac WLAN Adapter                                                       | 6         | 0.57%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 6         | 0.57%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 6         | 0.57%   |
| IMC Networks Bluetooth Device                                                       | 5         | 0.48%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.48%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 5         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 985       | 69.91%  |
| AMD                                  | 218       | 15.47%  |
| Nvidia                               | 150       | 10.65%  |
| C-Media Electronics                  | 8         | 0.57%   |
| Logitech                             | 7         | 0.5%    |
| Generalplus Technology               | 4         | 0.28%   |
| Realtek Semiconductor                | 3         | 0.21%   |
| GN Netcom                            | 3         | 0.21%   |
| Texas Instruments                    | 2         | 0.14%   |
| JMTek                                | 2         | 0.14%   |
| Huawei Technologies                  | 2         | 0.14%   |
| ESS Technology                       | 2         | 0.14%   |
| Dell                                 | 2         | 0.14%   |
| BEHRINGER International              | 2         | 0.14%   |
| Apple                                | 2         | 0.14%   |
| YUAN High-Tech Development           | 1         | 0.07%   |
| Trust                                | 1         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.07%   |
| TEAC                                 | 1         | 0.07%   |
| SteelSeries ApS                      | 1         | 0.07%   |
| Sony                                 | 1         | 0.07%   |
| No brand                             | 1         | 0.07%   |
| Native Instruments                   | 1         | 0.07%   |
| Midiplus                             | 1         | 0.07%   |
| Microsoft                            | 1         | 0.07%   |
| Kingston Technology                  | 1         | 0.07%   |
| JBL                                  | 1         | 0.07%   |
| Hewlett-Packard                      | 1         | 0.07%   |
| Guillemot                            | 1         | 0.07%   |
| Goldvish                             | 1         | 0.07%   |
| Corsair                              | 1         | 0.07%   |
| BY EDIFIER                           | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 156       | 8.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 118       | 6.77%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 99        | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 97        | 5.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 70        | 4.01%   |
| Intel 8 Series HD Audio Controller                                                                | 70        | 4.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 63        | 3.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 62        | 3.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 54        | 3.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 52        | 2.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 50        | 2.87%   |
| Intel Broadwell-U Audio Controller                                                                | 50        | 2.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 46        | 2.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 42        | 2.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 38        | 2.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 34        | 1.95%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 34        | 1.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 34        | 1.95%   |
| AMD FCH Azalia Controller                                                                         | 32        | 1.83%   |
| AMD Kabini HDMI/DP Audio                                                                          | 29        | 1.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 27        | 1.55%   |
| Nvidia MCP79 High Definition Audio                                                                | 23        | 1.32%   |
| AMD High Definition Audio Controller                                                              | 22        | 1.26%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 21        | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 21        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 21        | 1.2%    |
| Intel CM238 HD Audio Controller                                                                   | 16        | 0.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 0.92%   |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 14        | 0.8%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 14        | 0.8%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 13        | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 12        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 12        | 0.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 11        | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 11        | 0.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 0.63%   |
| Nvidia MCP89 High Definition Audio                                                                | 10        | 0.57%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 9         | 0.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 122       | 29.26%  |
| SK hynix            | 81        | 19.42%  |
| Micron Technology   | 61        | 14.63%  |
| Kingston            | 33        | 7.91%   |
| Unknown             | 24        | 5.76%   |
| Elpida              | 17        | 4.08%   |
| Crucial             | 16        | 3.84%   |
| Unknown (ABCD)      | 10        | 2.4%    |
| A-DATA Technology   | 8         | 1.92%   |
| Ramaxel Technology  | 7         | 1.68%   |
| Corsair             | 4         | 0.96%   |
| Smart               | 3         | 0.72%   |
| GSkill              | 3         | 0.72%   |
| G.Skill             | 3         | 0.72%   |
| Transcend           | 2         | 0.48%   |
| Timetec             | 2         | 0.48%   |
| Nanya Technology    | 2         | 0.48%   |
| Multilaser          | 2         | 0.48%   |
| Unknown             | 2         | 0.48%   |
| Toshiba             | 1         | 0.24%   |
| Team                | 1         | 0.24%   |
| Smart Brazil        | 1         | 0.24%   |
| SHARETRONIC         | 1         | 0.24%   |
| Qimonda             | 1         | 0.24%   |
| pqi                 | 1         | 0.24%   |
| PNY                 | 1         | 0.24%   |
| Patriot             | 1         | 0.24%   |
| Melco               | 1         | 0.24%   |
| Magnum Tech         | 1         | 0.24%   |
| Kllisre             | 1         | 0.24%   |
| Avant               | 1         | 0.24%   |
| AMD                 | 1         | 0.24%   |
| Aeneon              | 1         | 0.24%   |
| A Force             | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 9         | 2.03%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 1.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 1.58%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 4         | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.9%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 4         | 0.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.9%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 4         | 0.9%    |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 4         | 0.9%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 3         | 0.68%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.68%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.68%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 3         | 0.68%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 3         | 0.68%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.68%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.68%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 3         | 0.68%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.68%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.68%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 0.68%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s         | 3         | 0.68%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.68%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 2         | 0.45%   |
| Smart RAM SG564283FG8NWKF-Z1 1024MB SODIMM DDR2 800MT/s          | 2         | 0.45%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1333MT/s                  | 2         | 0.45%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.45%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 139       | 40.41%  |
| DDR3   | 136       | 39.53%  |
| LPDDR4 | 30        | 8.72%   |
| DDR2   | 17        | 4.94%   |
| LPDDR3 | 13        | 3.78%   |
| SDRAM  | 5         | 1.45%   |
| LPDDR5 | 2         | 0.58%   |
| DDR5   | 2         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 304       | 87.11%  |
| Row Of Chips | 37        | 10.6%   |
| Chip         | 4         | 1.15%   |
| DIMM         | 3         | 0.86%   |
| Unknown      | 1         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 163       | 41.16%  |
| 4096  | 117       | 29.55%  |
| 2048  | 61        | 15.4%   |
| 16384 | 37        | 9.34%   |
| 1024  | 11        | 2.78%   |
| 32768 | 7         | 1.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 94        | 24.67%  |
| 2667    | 71        | 18.64%  |
| 3200    | 52        | 13.65%  |
| 2133    | 29        | 7.61%   |
| 2400    | 27        | 7.09%   |
| 1334    | 18        | 4.72%   |
| 1333    | 17        | 4.46%   |
| 4267    | 12        | 3.15%   |
| 667     | 10        | 2.62%   |
| 1067    | 9         | 2.36%   |
| 800     | 8         | 2.1%    |
| 1867    | 6         | 1.57%   |
| 1066    | 5         | 1.31%   |
| 8400    | 3         | 0.79%   |
| 4266    | 3         | 0.79%   |
| 4199    | 3         | 0.79%   |
| 3266    | 3         | 0.79%   |
| 6400    | 2         | 0.52%   |
| 4800    | 2         | 0.52%   |
| 2048    | 2         | 0.52%   |
| 975     | 2         | 0.52%   |
| Unknown | 2         | 0.52%   |
| 3733    | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Xerox                           | 2         | 14.29%  |
| Seiko Epson                     | 2         | 14.29%  |
| Samsung Electronics             | 2         | 14.29%  |
| Hewlett-Packard                 | 2         | 14.29%  |
| Canon                           | 2         | 14.29%  |
| Prolific Technology             | 1         | 7.14%   |
| Lexmark International           | 1         | 7.14%   |
| cab Produkttechnik GmbH & Co KG | 1         | 7.14%   |
| Brother Industries              | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Xerox Phaser 3610                                     | 1         | 7.14%   |
| Xerox Phaser 3040                                     | 1         | 7.14%   |
| Seiko Epson XP-205 207 Series                         | 1         | 7.14%   |
| Seiko Epson L355 Series                               | 1         | 7.14%   |
| Samsung M2020 Series                                  | 1         | 7.14%   |
| Samsung C48x Series Color Laser Multifunction Printer | 1         | 7.14%   |
| Prolific PL2305 Parallel Port                         | 1         | 7.14%   |
| Lexmark International f+ imaging M40adn               | 1         | 7.14%   |
| HP Deskjet F4500 series                               | 1         | 7.14%   |
| HP DeskJet 2600 series                                | 1         | 7.14%   |
| Canon PIXMA MG2500 Series                             | 1         | 7.14%   |
| Canon G3000 series                                    | 1         | 7.14%   |
| cab Produkttechnik GmbH & Co KG EOS2/300              | 1         | 7.14%   |
| Brother MFC-T800W                                     | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 50%     |
| Canon CanoScan LiDE 110                                 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 237       | 21.8%   |
| Apple                                  | 102       | 9.38%   |
| Realtek Semiconductor                  | 97        | 8.92%   |
| IMC Networks                           | 95        | 8.74%   |
| Microdia                               | 72        | 6.62%   |
| Quanta                                 | 66        | 6.07%   |
| Sunplus Innovation Technology          | 60        | 5.52%   |
| Cheng Uei Precision Industry (Foxlink) | 54        | 4.97%   |
| Bison Electronics                      | 50        | 4.6%    |
| Suyin                                  | 36        | 3.31%   |
| Syntek                                 | 33        | 3.04%   |
| Lite-On Technology                     | 24        | 2.21%   |
| Acer                                   | 23        | 2.12%   |
| Silicon Motion                         | 22        | 2.02%   |
| Alcor Micro                            | 20        | 1.84%   |
| Luxvisions Innotech Limited            | 11        | 1.01%   |
| Lenovo                                 | 11        | 1.01%   |
| Ricoh                                  | 10        | 0.92%   |
| Importek                               | 6         | 0.55%   |
| Logitech                               | 5         | 0.46%   |
| ALi                                    | 5         | 0.46%   |
| SunplusIT                              | 4         | 0.37%   |
| Samsung Electronics                    | 4         | 0.37%   |
| Primax Electronics                     | 4         | 0.37%   |
| LG Electronics                         | 4         | 0.37%   |
| Y Media                                | 3         | 0.28%   |
| Sonix Technology                       | 3         | 0.28%   |
| Sunplus Technology                     | 2         | 0.18%   |
| ShineTech                              | 2         | 0.18%   |
| KYE Systems (Mouse Systems)            | 2         | 0.18%   |
| GEMBIRD                                | 2         | 0.18%   |
| Foxconn / Hon Hai                      | 2         | 0.18%   |
| Z-Star Microelectronics                | 1         | 0.09%   |
| Sony                                   | 1         | 0.09%   |
| Shine-optics                           | 1         | 0.09%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.09%   |
| OYT Tech                               | 1         | 0.09%   |
| MacroSilicon                           | 1         | 0.09%   |
| kingcome                               | 1         | 0.09%   |
| Jieli Technology                       | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 51        | 4.67%   |
| Apple Built-in iSight                            | 34        | 3.11%   |
| Apple FaceTime HD Camera                         | 33        | 3.02%   |
| IMC Networks USB2.0 HD UVC WebCam                | 30        | 2.75%   |
| Chicony HD WebCam                                | 30        | 2.75%   |
| Realtek Integrated_Webcam_HD                     | 25        | 2.29%   |
| IMC Networks Integrated Camera                   | 24        | 2.2%    |
| Microdia Integrated_Webcam_HD                    | 23        | 2.11%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 20        | 1.83%   |
| Syntek Integrated Camera                         | 17        | 1.56%   |
| Realtek USB Camera                               | 15        | 1.37%   |
| Sunplus Integrated_Webcam_HD                     | 14        | 1.28%   |
| Microdia Integrated Webcam                       | 12        | 1.1%    |
| Lite-On Integrated Camera                        | 12        | 1.1%    |
| Quanta HP Webcam                                 | 11        | 1.01%   |
| Realtek Integrated Webcam                        | 10        | 0.92%   |
| Quanta HP TrueVision HD Camera                   | 10        | 0.92%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 10        | 0.92%   |
| Chicony HP Truevision HD camera                  | 10        | 0.92%   |
| Chicony HP Truevision HD                         | 10        | 0.92%   |
| Chicony HP HD Webcam [Fixed]                     | 10        | 0.92%   |
| Chicony EasyCamera                               | 10        | 0.92%   |
| Acer Integrated Camera                           | 10        | 0.92%   |
| Syntek EasyCamera                                | 9         | 0.82%   |
| Sunplus HD WebCam                                | 9         | 0.82%   |
| Realtek USB2.0 HD UVC WebCam                     | 9         | 0.82%   |
| Quanta HD User Facing                            | 8         | 0.73%   |
| Apple FaceTime Camera                            | 8         | 0.73%   |
| Syntek Lenovo EasyCamera                         | 7         | 0.64%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 7         | 0.64%   |
| Quanta HD Camera                                 | 7         | 0.64%   |
| Chicony VGA WebCam                               | 7         | 0.64%   |
| Chicony HP HD Webcam                             | 7         | 0.64%   |
| Chicony HP HD Camera                             | 7         | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 7         | 0.64%   |
| Bison SunplusIT Integrated Camera                | 7         | 0.64%   |
| Bison Integrated Camera                          | 7         | 0.64%   |
| Realtek HD WebCam                                | 6         | 0.55%   |
| Quanta VGA WebCam                                | 6         | 0.55%   |
| Microdia USB 2.0 Camera                          | 6         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 86        | 41.35%  |
| Synaptics                  | 40        | 19.23%  |
| Shenzhen Goodix Technology | 32        | 15.38%  |
| LighTuning Technology      | 16        | 7.69%   |
| Upek                       | 11        | 5.29%   |
| Elan Microelectronics      | 11        | 5.29%   |
| AuthenTec                  | 8         | 3.85%   |
| STMicroelectronics         | 2         | 0.96%   |
| Focal-systems.Corp         | 2         | 0.96%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 26        | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 9.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 5.77%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 5.77%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 5.29%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 5.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 4.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 4.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 3.37%   |
| Validity Sensors VFS491                                                    | 7         | 3.37%   |
| Elan ELAN:Fingerprint                                                      | 7         | 3.37%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.4%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.4%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.92%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.92%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 1.92%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.92%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.92%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.44%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.44%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.44%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.44%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.44%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.96%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.96%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.96%   |
| Synaptics  WBDI                                                            | 2         | 0.96%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.96%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 0.96%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.96%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.96%   |
| AuthenTec AES2810                                                          | 2         | 0.96%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.48%   |
| Synaptics WBDI                                                             | 1         | 0.48%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.48%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.48%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.48%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.48%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 36        | 48%     |
| Alcor Micro           | 19        | 25.33%  |
| O2 Micro              | 7         | 9.33%   |
| Upek                  | 6         | 8%      |
| Lenovo                | 6         | 8%      |
| Gemalto (was Gemplus) | 1         | 1.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 25.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 22.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 12%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 8%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 8%      |
| Lenovo Integrated Smart Card Reader                                          | 6         | 8%      |
| Broadcom 5880                                                                | 6         | 8%      |
| Broadcom 58200                                                               | 4         | 5.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.33%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 775       | 63.27%  |
| 1     | 353       | 28.82%  |
| 2     | 86        | 7.02%   |
| 3     | 10        | 0.82%   |
| 8     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 206       | 37.05%  |
| Net/wireless             | 86        | 15.47%  |
| Chipcard                 | 72        | 12.95%  |
| Multimedia controller    | 71        | 12.77%  |
| Graphics card            | 67        | 12.05%  |
| Storage                  | 12        | 2.16%   |
| Camera                   | 12        | 2.16%   |
| Bluetooth                | 11        | 1.98%   |
| Net/ethernet             | 7         | 1.26%   |
| Sound                    | 4         | 0.72%   |
| Card reader              | 4         | 0.72%   |
| Communication controller | 2         | 0.36%   |
| Network                  | 1         | 0.18%   |
| Modem                    | 1         | 0.18%   |

