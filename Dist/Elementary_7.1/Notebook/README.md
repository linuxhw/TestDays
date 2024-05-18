Elementary 7.1 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Elementary 7.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 240

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
| HP            | Pavilion dv7                | [483e1957a4](https://linux-hardware.org/?probe=483e1957a4) | Apr 02, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [fe5490324f](https://linux-hardware.org/?probe=fe5490324f) | Apr 01, 2024 |
| HP            | Pavilion dv7                | [a86e8cccf5](https://linux-hardware.org/?probe=a86e8cccf5) | Mar 31, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b68181d354](https://linux-hardware.org/?probe=b68181d354) | Mar 29, 2024 |
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
| Apple         | MacBookPro5,4               | [681e76d909](https://linux-hardware.org/?probe=681e76d909) | Feb 29, 2024 |
| Apple         | MacBookPro5,4               | [ca45519759](https://linux-hardware.org/?probe=ca45519759) | Feb 29, 2024 |
| UNOWHY        | Y13G011S4EI                 | [f785899192](https://linux-hardware.org/?probe=f785899192) | Feb 29, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [11a760c545](https://linux-hardware.org/?probe=11a760c545) | Feb 28, 2024 |
| HP            | 15                          | [6fb113d856](https://linux-hardware.org/?probe=6fb113d856) | Feb 28, 2024 |
| Dell          | Inspiron 5567               | [9a57de6e15](https://linux-hardware.org/?probe=9a57de6e15) | Feb 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [49ac7f8a77](https://linux-hardware.org/?probe=49ac7f8a77) | Feb 27, 2024 |
| Apple         | MacBookPro9,2               | [7167de20ce](https://linux-hardware.org/?probe=7167de20ce) | Feb 27, 2024 |
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
| Apple         | MacBookAir6,1               | [f11ff820e7](https://linux-hardware.org/?probe=f11ff820e7) | Feb 18, 2024 |
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
| Lenovo        | ThinkPad T480 20L6S3ED18    | [63d8796a60](https://linux-hardware.org/?probe=63d8796a60) | Jan 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [86d22c9b40](https://linux-hardware.org/?probe=86d22c9b40) | Jan 17, 2024 |
| Apple         | MacBook6,1                  | [641df770ba](https://linux-hardware.org/?probe=641df770ba) | Jan 17, 2024 |
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
| HP            | EliteBook 845 G7 Noteboo... | [cf1e883f11](https://linux-hardware.org/?probe=cf1e883f11) | Nov 25, 2023 |
| Samsung       | RF510/RF410/RF710           | [a642075264](https://linux-hardware.org/?probe=a642075264) | Nov 25, 2023 |
| Apple         | MacBookPro5,5               | [a2d556bc01](https://linux-hardware.org/?probe=a2d556bc01) | Nov 20, 2023 |
| Apple         | MacBookPro5,5               | [cdc6379993](https://linux-hardware.org/?probe=cdc6379993) | Nov 19, 2023 |
| Apple         | MacBookPro5,5               | [840adf8528](https://linux-hardware.org/?probe=840adf8528) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | [886c5bc9a6](https://linux-hardware.org/?probe=886c5bc9a6) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | [bcd7007cde](https://linux-hardware.org/?probe=bcd7007cde) | Nov 19, 2023 |
| Fujitsu       | LIFEBOOK E780               | [d3a64f5368](https://linux-hardware.org/?probe=d3a64f5368) | Nov 16, 2023 |
| Unknown       | Unknown                     | [66296a4edd](https://linux-hardware.org/?probe=66296a4edd) | Nov 12, 2023 |
| Alienware     | 15 R3                       | [c920563c0b](https://linux-hardware.org/?probe=c920563c0b) | Nov 12, 2023 |
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
| Dell          | Latitude E6400              | [250c9ddcfe](https://linux-hardware.org/?probe=250c9ddcfe) | Oct 24, 2023 |
| Apple         | MacBookPro6,2               | [89f29afb19](https://linux-hardware.org/?probe=89f29afb19) | Oct 24, 2023 |
| Dell          | Latitude E6520              | [c2fd0014ab](https://linux-hardware.org/?probe=c2fd0014ab) | Oct 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3431e88cbe](https://linux-hardware.org/?probe=3431e88cbe) | Oct 22, 2023 |
| Google        | Cave                        | [287887d308](https://linux-hardware.org/?probe=287887d308) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [b11aafb048](https://linux-hardware.org/?probe=b11aafb048) | Oct 20, 2023 |
| HP            | Pavilion 17                 | [855c6109eb](https://linux-hardware.org/?probe=855c6109eb) | Oct 20, 2023 |
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
| Lenovo        | ThinkPad T440p 20AN0069U... | [ccc23328e5](https://linux-hardware.org/?probe=ccc23328e5) | Oct 07, 2023 |
| Dell          | Vostro 1510                 | [39ee83fbf5](https://linux-hardware.org/?probe=39ee83fbf5) | Oct 06, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a49cef1179](https://linux-hardware.org/?probe=a49cef1179) | Oct 04, 2023 |
| Apple         | MacBookPro7,1               | [d88817f79c](https://linux-hardware.org/?probe=d88817f79c) | Oct 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [d91dd7bed6](https://linux-hardware.org/?probe=d91dd7bed6) | Oct 02, 2023 |
| Dell          | Latitude E7270              | [bf1def4fc3](https://linux-hardware.org/?probe=bf1def4fc3) | Oct 01, 2023 |
| Apple         | MacBookAir7,2               | [0a667d66b7](https://linux-hardware.org/?probe=0a667d66b7) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | [15f8d0107f](https://linux-hardware.org/?probe=15f8d0107f) | Sep 26, 2023 |
| Apple         | MacBookPro11,1              | [e9478deeae](https://linux-hardware.org/?probe=e9478deeae) | Sep 23, 2023 |
| HP            | EliteBook 8570p             | [ca346761d3](https://linux-hardware.org/?probe=ca346761d3) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [c8bbae1068](https://linux-hardware.org/?probe=c8bbae1068) | Sep 20, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 6.2.0-33-generic     | 41        | 22.28%  |
| 6.5.0-28-generic     | 19        | 10.33%  |
| 6.5.0-26-generic     | 13        | 7.07%   |
| 6.5.0-27-generic     | 12        | 6.52%   |
| 6.5.0-21-generic     | 11        | 5.98%   |
| 6.2.0-39-generic     | 11        | 5.98%   |
| 6.5.0-15-generic     | 10        | 5.43%   |
| 6.2.0-36-generic     | 10        | 5.43%   |
| 6.2.0-34-generic     | 10        | 5.43%   |
| 6.5.0-25-generic     | 9         | 4.89%   |
| 6.2.0-37-generic     | 9         | 4.89%   |
| 6.5.0-14-generic     | 6         | 3.26%   |
| 6.2.0-35-generic     | 6         | 3.26%   |
| 6.5.0-18-generic     | 5         | 2.72%   |
| 6.5.0-17-generic     | 4         | 2.17%   |
| 6.2.0-26-generic     | 2         | 1.09%   |
| 6.7.3-060703-generic | 1         | 0.54%   |
| 6.5.7-060507-generic | 1         | 0.54%   |
| 6.5.5-x64v3-xanmod1  | 1         | 0.54%   |
| 5.19.0-50-generic    | 1         | 0.54%   |
| 5.19.0-46-generic    | 1         | 0.54%   |
| 5.15.0-58-generic    | 1         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.5.0   | 89        | 48.9%   |
| 6.2.0   | 87        | 47.8%   |
| 5.19.0  | 2         | 1.1%    |
| 6.7.3   | 1         | 0.55%   |
| 6.5.7   | 1         | 0.55%   |
| 6.5.5   | 1         | 0.55%   |
| 5.15.0  | 1         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.5     | 91        | 50%     |
| 6.2     | 87        | 47.8%   |
| 5.19    | 2         | 1.1%    |
| 6.7     | 1         | 0.55%   |
| 5.15    | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 177       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 175       | 98.87%  |
| KDE5     | 1         | 0.56%   |
| Unknown  | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 177       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 141       | 79.21%  |
| LightDM | 36        | 20.22%  |
| SDDM    | 1         | 0.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 68        | 38.42%  |
| ru_RU   | 22        | 12.43%  |
| de_DE   | 17        | 9.6%    |
| it_IT   | 15        | 8.47%   |
| es_ES   | 14        | 7.91%   |
| fr_FR   | 8         | 4.52%   |
| pt_BR   | 7         | 3.95%   |
| en_GB   | 4         | 2.26%   |
| pl_PL   | 3         | 1.69%   |
| nl_NL   | 3         | 1.69%   |
| tr_TR   | 2         | 1.13%   |
| sv_SE   | 2         | 1.13%   |
| fi_FI   | 2         | 1.13%   |
| pt_PT   | 1         | 0.56%   |
| id_ID   | 1         | 0.56%   |
| fr_CA   | 1         | 0.56%   |
| es_AR   | 1         | 0.56%   |
| el_GR   | 1         | 0.56%   |
| de_CH   | 1         | 0.56%   |
| da_DK   | 1         | 0.56%   |
| cs_CZ   | 1         | 0.56%   |
| ar_EG   | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 152       | 85.39%  |
| EFI  | 26        | 14.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 162       | 91.53%  |
| Tmpfs   | 11        | 6.21%   |
| Btrfs   | 2         | 1.13%   |
| Xfs     | 1         | 0.56%   |
| Overlay | 1         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 140       | 78.65%  |
| GPT     | 31        | 17.42%  |
| MBR     | 7         | 3.93%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 175       | 98.87%  |
| Yes       | 2         | 1.13%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 169       | 94.94%  |
| Yes       | 9         | 5.06%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Apple                | 35        | 19.77%  |
| Hewlett-Packard      | 32        | 18.08%  |
| Lenovo               | 29        | 16.38%  |
| Dell                 | 20        | 11.3%   |
| ASUSTek Computer     | 14        | 7.91%   |
| Acer                 | 13        | 7.34%   |
| HUAWEI               | 6         | 3.39%   |
| Samsung Electronics  | 4         | 2.26%   |
| MSI                  | 3         | 1.69%   |
| Google               | 2         | 1.13%   |
| Fujitsu              | 2         | 1.13%   |
| Alienware            | 2         | 1.13%   |
| Unknown              | 2         | 1.13%   |
| UNOWHY               | 1         | 0.56%   |
| UMAX                 | 1         | 0.56%   |
| Timi                 | 1         | 0.56%   |
| THTF                 | 1         | 0.56%   |
| TECNO Mobile Limited | 1         | 0.56%   |
| TECNO                | 1         | 0.56%   |
| Teclast              | 1         | 0.56%   |
| Sony                 | 1         | 0.56%   |
| Positivo             | 1         | 0.56%   |
| Packard Bell         | 1         | 0.56%   |
| Medion               | 1         | 0.56%   |
| HONOR                | 1         | 0.56%   |
| DEPO Computers       | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Apple MacBookAir7,2                      | 7         | 3.95%   |
| Apple MacBookPro9,2                      | 4         | 2.26%   |
| Apple MacBookPro7,1                      | 3         | 1.69%   |
| Apple MacBookPro11,1                     | 3         | 1.69%   |
| Dell Latitude E7240                      | 2         | 1.13%   |
| Apple MacBookPro8,1                      | 2         | 1.13%   |
| Apple MacBookPro6,2                      | 2         | 1.13%   |
| Apple MacBookPro5,4                      | 2         | 1.13%   |
| Apple MacBook5,1                         | 2         | 1.13%   |
| Unknown                                  | 2         | 1.13%   |
| UNOWHY Y13G011S4EI                       | 1         | 0.56%   |
| UMAX VisionBook 14Wr Plus                | 1         | 0.56%   |
| Timi Redmi G 2022                        | 1         | 0.56%   |
| THTF WUJIE 14                            | 1         | 0.56%   |
| TECNO Mobile Limited MEGABOOK T14TA      | 1         | 0.56%   |
| TECNO MEGABOOK T1                        | 1         | 0.56%   |
| Teclast F7                               | 1         | 0.56%   |
| Sony SVE11115ELW                         | 1         | 0.56%   |
| Samsung RF510/RF410/RF710                | 1         | 0.56%   |
| Samsung RC410/RC510/RC710                | 1         | 0.56%   |
| Samsung 550XDA                           | 1         | 0.56%   |
| Samsung 535U3C                           | 1         | 0.56%   |
| Positivo C4128A-15                       | 1         | 0.56%   |
| Packard Bell EasyNote LM81               | 1         | 0.56%   |
| MSI GT62VR 6RE                           | 1         | 0.56%   |
| MSI GF72VR 7RF                           | 1         | 0.56%   |
| MSI GE70 2QE                             | 1         | 0.56%   |
| Medion E11202                            | 1         | 0.56%   |
| Lenovo Yoga Pro 7 14APH8 82Y8            | 1         | 0.56%   |
| Lenovo Yoga 900S-12ISK 80ML              | 1         | 0.56%   |
| Lenovo V15 G2 ITL 82KB                   | 1         | 0.56%   |
| Lenovo ThinkPad X250 20CLS3NA00          | 1         | 0.56%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S2G103 | 1         | 0.56%   |
| Lenovo ThinkPad W500 40623CG             | 1         | 0.56%   |
| Lenovo ThinkPad T530 2429HR5             | 1         | 0.56%   |
| Lenovo ThinkPad T480 20L6S3ED18          | 1         | 0.56%   |
| Lenovo ThinkPad T470 20JNS08H00          | 1         | 0.56%   |
| Lenovo ThinkPad T450s 20BX0011GE         | 1         | 0.56%   |
| Lenovo ThinkPad T440p 20AN0069US         | 1         | 0.56%   |
| Lenovo ThinkPad T410 2537CQ7             | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 13        | 7.34%   |
| Lenovo IdeaPad                | 12        | 6.78%   |
| HP Pavilion                   | 10        | 5.65%   |
| Dell Latitude                 | 9         | 5.08%   |
| HP EliteBook                  | 8         | 4.52%   |
| Acer Aspire                   | 8         | 4.52%   |
| Apple MacBookAir7             | 7         | 3.95%   |
| HP ProBook                    | 6         | 3.39%   |
| Dell Inspiron                 | 5         | 2.82%   |
| ASUS VivoBook                 | 5         | 2.82%   |
| Apple MacBookPro11            | 5         | 2.82%   |
| Apple MacBookPro9             | 4         | 2.26%   |
| Apple MacBookPro5             | 4         | 2.26%   |
| HP ENVY                       | 3         | 1.69%   |
| Dell Vostro                   | 3         | 1.69%   |
| Apple MacBookPro8             | 3         | 1.69%   |
| Apple MacBookPro7             | 3         | 1.69%   |
| Lenovo Yoga                   | 2         | 1.13%   |
| Fujitsu LIFEBOOK              | 2         | 1.13%   |
| ASUS Zenbook                  | 2         | 1.13%   |
| Apple MacBookPro6             | 2         | 1.13%   |
| Apple MacBook5                | 2         | 1.13%   |
| Acer Swift                    | 2         | 1.13%   |
| Unknown                       | 2         | 1.13%   |
| UNOWHY Y13G011S4EI            | 1         | 0.56%   |
| UMAX VisionBook               | 1         | 0.56%   |
| Timi Redmi                    | 1         | 0.56%   |
| THTF WUJIE                    | 1         | 0.56%   |
| TECNO Mobile Limited MEGABOOK | 1         | 0.56%   |
| TECNO MEGABOOK                | 1         | 0.56%   |
| Teclast F7                    | 1         | 0.56%   |
| Sony SVE11115ELW              | 1         | 0.56%   |
| Samsung RF510                 | 1         | 0.56%   |
| Samsung RC410                 | 1         | 0.56%   |
| Samsung 550XDA                | 1         | 0.56%   |
| Samsung 535U3C                | 1         | 0.56%   |
| Positivo C4128A-15            | 1         | 0.56%   |
| Packard Bell EasyNote         | 1         | 0.56%   |
| MSI GT62VR                    | 1         | 0.56%   |
| MSI GF72VR                    | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 16        | 9.04%   |
| 2013 | 15        | 8.47%   |
| 2010 | 14        | 7.91%   |
| 2021 | 13        | 7.34%   |
| 2020 | 12        | 6.78%   |
| 2018 | 12        | 6.78%   |
| 2014 | 12        | 6.78%   |
| 2011 | 11        | 6.21%   |
| 2009 | 11        | 6.21%   |
| 2023 | 10        | 5.65%   |
| 2017 | 10        | 5.65%   |
| 2016 | 9         | 5.08%   |
| 2022 | 8         | 4.52%   |
| 2015 | 7         | 3.95%   |
| 2007 | 7         | 3.95%   |
| 2008 | 6         | 3.39%   |
| 2019 | 4         | 2.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 177       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 174       | 98.31%  |
| Enabled  | 3         | 1.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 175       | 98.87%  |
| Yes  | 2         | 1.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 77        | 43.26%  |
| 3.01-4.0    | 36        | 20.22%  |
| 16.01-24.0  | 33        | 18.54%  |
| 8.01-16.0   | 17        | 9.55%   |
| 32.01-64.0  | 6         | 3.37%   |
| 2.01-3.0    | 4         | 2.25%   |
| 1.01-2.0    | 3         | 1.69%   |
| 24.01-32.0  | 1         | 0.56%   |
| 64.01-256.0 | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 66        | 35.87%  |
| 1.01-2.0  | 49        | 26.63%  |
| 3.01-4.0  | 34        | 18.48%  |
| 4.01-8.0  | 26        | 14.13%  |
| 0.51-1.0  | 5         | 2.72%   |
| 8.01-16.0 | 4         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 130       | 73.45%  |
| 2      | 45        | 25.42%  |
| 3      | 2         | 1.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 116       | 65.54%  |
| Yes       | 61        | 34.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 75.71%  |
| No        | 43        | 24.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 98.87%  |
| No        | 2         | 1.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 85.31%  |
| No        | 26        | 14.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 27        | 15.25%  |
| Russia      | 17        | 9.6%    |
| Germany     | 17        | 9.6%    |
| Italy       | 16        | 9.04%   |
| Brazil      | 11        | 6.21%   |
| France      | 8         | 4.52%   |
| Spain       | 5         | 2.82%   |
| Netherlands | 5         | 2.82%   |
| Mexico      | 5         | 2.82%   |
| Indonesia   | 5         | 2.82%   |
| Austria     | 4         | 2.26%   |
| Switzerland | 3         | 1.69%   |
| Sweden      | 3         | 1.69%   |
| Poland      | 3         | 1.69%   |
| Greece      | 3         | 1.69%   |
| Canada      | 3         | 1.69%   |
| Belarus     | 3         | 1.69%   |
| Argentina   | 3         | 1.69%   |
| Vietnam     | 2         | 1.13%   |
| Turkey      | 2         | 1.13%   |
| Romania     | 2         | 1.13%   |
| Peru        | 2         | 1.13%   |
| New Zealand | 2         | 1.13%   |
| Lithuania   | 2         | 1.13%   |
| Hungary     | 2         | 1.13%   |
| Finland     | 2         | 1.13%   |
| Australia   | 2         | 1.13%   |
| Ukraine     | 1         | 0.56%   |
| UK          | 1         | 0.56%   |
| Thailand    | 1         | 0.56%   |
| Slovakia    | 1         | 0.56%   |
| Puerto Rico | 1         | 0.56%   |
| Portugal    | 1         | 0.56%   |
| Morocco     | 1         | 0.56%   |
| Kazakhstan  | 1         | 0.56%   |
| India       | 1         | 0.56%   |
| Georgia     | 1         | 0.56%   |
| Ecuador     | 1         | 0.56%   |
| Denmark     | 1         | 0.56%   |
| Czechia     | 1         | 0.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 5         | 2.76%   |
| Vitebsk           | 2         | 1.1%    |
| Vienna            | 2         | 1.1%    |
| St Petersburg     | 2         | 1.1%    |
| Paris             | 2         | 1.1%    |
| Naples            | 2         | 1.1%    |
| Mažeikiai        | 2         | 1.1%    |
| Lima              | 2         | 1.1%    |
| Ho Chi Minh City  | 2         | 1.1%    |
| Groningen         | 2         | 1.1%    |
| Cleveland         | 2         | 1.1%    |
| Budapest          | 2         | 1.1%    |
| A Coruña         | 2         | 1.1%    |
| Zurich            | 1         | 0.55%   |
| Zhodzina          | 1         | 0.55%   |
| Zamora            | 1         | 0.55%   |
| Yuzhno-Sakhalinsk | 1         | 0.55%   |
| Yerevan           | 1         | 0.55%   |
| Yekaterinburg     | 1         | 0.55%   |
| Wuerselen         | 1         | 0.55%   |
| Westerville       | 1         | 0.55%   |
| Wellington        | 1         | 0.55%   |
| Warsaw            | 1         | 0.55%   |
| Votorantim        | 1         | 0.55%   |
| Västerås        | 1         | 0.55%   |
| Valby             | 1         | 0.55%   |
| Turku             | 1         | 0.55%   |
| Tucson            | 1         | 0.55%   |
| Tbilisi           | 1         | 0.55%   |
| Tangerang         | 1         | 0.55%   |
| Surabaya          | 1         | 0.55%   |
| Stockholm         | 1         | 0.55%   |
| Staten Island     | 1         | 0.55%   |
| St Louis          | 1         | 0.55%   |
| Sohlde            | 1         | 0.55%   |
| Sochi             | 1         | 0.55%   |
| Sendenhorst       | 1         | 0.55%   |
| Semarang          | 1         | 0.55%   |
| Savannah          | 1         | 0.55%   |
| San Jose          | 1         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 24        | 27     | 10.96%  |
| Toshiba                      | 18        | 21     | 8.22%   |
| Apple                        | 17        | 17     | 7.76%   |
| Sandisk                      | 16        | 18     | 7.31%   |
| Kingston                     | 15        | 18     | 6.85%   |
| WDC                          | 14        | 17     | 6.39%   |
| Unknown                      | 12        | 15     | 5.48%   |
| Seagate                      | 12        | 12     | 5.48%   |
| Intel                        | 10        | 12     | 4.57%   |
| SK hynix                     | 7         | 7      | 3.2%    |
| Hitachi                      | 7         | 7      | 3.2%    |
| KIOXIA                       | 6         | 7      | 2.74%   |
| Crucial                      | 6         | 7      | 2.74%   |
| HGST                         | 5         | 6      | 2.28%   |
| A-DATA Technology            | 5         | 5      | 2.28%   |
| SPCC                         | 3         | 3      | 1.37%   |
| Fanxiang                     | 3         | 3      | 1.37%   |
| China                        | 3         | 3      | 1.37%   |
| Yangtze Memory Technologies  | 2         | 2      | 0.91%   |
| Transcend                    | 2         | 3      | 0.91%   |
| PNY                          | 2         | 2      | 0.91%   |
| Micron Technology            | 2         | 2      | 0.91%   |
| LITEON                       | 2         | 2      | 0.91%   |
| Gigabyte Technology          | 2         | 2      | 0.91%   |
| Unknown                      | 2         | 3      | 0.91%   |
| XrayDisk                     | 1         | 2      | 0.46%   |
| TS-RDF2                      | 1         | 1      | 0.46%   |
| Teclast                      | 1         | 1      | 0.46%   |
| TECHBYTE                     | 1         | 1      | 0.46%   |
| Silicon Motion               | 1         | 1      | 0.46%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.46%   |
| SABRENT                      | 1         | 1      | 0.46%   |
| Phison Electronics           | 1         | 1      | 0.46%   |
| Patriot                      | 1         | 1      | 0.46%   |
| OWC                          | 1         | 1      | 0.46%   |
| NGFF                         | 1         | 1      | 0.46%   |
| MAXIO Technology (Hangzhou)  | 1         | 1      | 0.46%   |
| LS                           | 1         | 1      | 0.46%   |
| Lite-On Technology           | 1         | 1      | 0.46%   |
| Lexar                        | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                            | 7         | 3.14%   |
| Apple SSD SM0128G 121GB                           | 6         | 2.69%   |
| Kingston SA400S37240G 240GB SSD                   | 5         | 2.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 1.79%   |
| Toshiba MQ01ABD100 1TB                            | 3         | 1.35%   |
| Seagate ST500LT012-1DG142 500GB                   | 3         | 1.35%   |
| Seagate ST1000LM035-1RK172 1TB                    | 3         | 1.35%   |
| Kingston SA400S37120G 120GB SSD                   | 3         | 1.35%   |
| HGST HTS721010A9E630 1TB                          | 3         | 1.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 2         | 0.9%    |
| Unknown NVMe SSD Drive 512GB                      | 2         | 0.9%    |
| Toshiba THNSFJ256GCSU 256GB SSD                   | 2         | 0.9%    |
| SPCC Solid State Disk 512GB                       | 2         | 0.9%    |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 2         | 0.9%    |
| Sandisk WD_BLACK SN770 1TB                        | 2         | 0.9%    |
| Sandisk WD Blue SN550 NVMe SSD 2TB                | 2         | 0.9%    |
| Sandisk PC SN520 NVMe SSD 512GB                   | 2         | 0.9%    |
| Samsung SSD 860 EVO 500GB                         | 2         | 0.9%    |
| Samsung SSD 850 EVO 500GB                         | 2         | 0.9%    |
| Samsung MZVL4512HBLU-00BTW 512GB                  | 2         | 0.9%    |
| LITEON L8H-256V2G-HP 256GB SSD                    | 2         | 0.9%    |
| Kingston SUV500MS480G 480GB SSD                   | 2         | 0.9%    |
| Kingston SA400S37480G 480GB SSD                   | 2         | 0.9%    |
| Intel SSDSC2BF180A4H 180GB                        | 2         | 0.9%    |
| Intel SSDPEKNU512GZ 512GB                         | 2         | 0.9%    |
| Apple SSD SM0256F 256GB                           | 2         | 0.9%    |
| A-DATA SU650 240GB SSD                            | 2         | 0.9%    |
| Unknown                                           | 2         | 0.9%    |
| Yangtze Memory YMTC PC005 512GB                   | 1         | 0.45%   |
| Yangtze Memory YMTC PC005 256GB                   | 1         | 0.45%   |
| XrayDisk 256GB SSD                                | 1         | 0.45%   |
| WDC WDS480G2G0C-00AJM0 480GB                      | 1         | 0.45%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                  | 1         | 0.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 1         | 0.45%   |
| WDC WD6400BPVT-22HXZT3 640GB                      | 1         | 0.45%   |
| WDC WD6400BPVT-22HXZT1 640GB                      | 1         | 0.45%   |
| WDC WD5000LPVX-00V0TT0 500GB                      | 1         | 0.45%   |
| WDC WD5000BPVT-24HXZT3 500GB                      | 1         | 0.45%   |
| WDC WD3200BPVT-00JJ5T0 320GB                      | 1         | 0.45%   |
| WDC WD2500BEKT-60PVMT0 250GB                      | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 13        | 16     | 26%     |
| Seagate             | 11        | 11     | 22%     |
| WDC                 | 10        | 10     | 20%     |
| Hitachi             | 7         | 7      | 14%     |
| HGST                | 5         | 6      | 10%     |
| Apple               | 2         | 2      | 4%      |
| Samsung Electronics | 1         | 1      | 2%      |
| SABRENT             | 1         | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 14        | 17     | 14.14%  |
| Apple               | 14        | 14     | 14.14%  |
| Samsung Electronics | 13        | 15     | 13.13%  |
| SanDisk             | 9         | 10     | 9.09%   |
| Crucial             | 6         | 7      | 6.06%   |
| Intel               | 5         | 6      | 5.05%   |
| WDC                 | 4         | 6      | 4.04%   |
| A-DATA Technology   | 4         | 4      | 4.04%   |
| SPCC                | 3         | 3      | 3.03%   |
| China               | 3         | 3      | 3.03%   |
| Transcend           | 2         | 3      | 2.02%   |
| Toshiba             | 2         | 2      | 2.02%   |
| SK hynix            | 2         | 2      | 2.02%   |
| PNY                 | 2         | 2      | 2.02%   |
| LITEON              | 2         | 2      | 2.02%   |
| XrayDisk            | 1         | 2      | 1.01%   |
| Teclast             | 1         | 1      | 1.01%   |
| Seagate             | 1         | 1      | 1.01%   |
| Patriot             | 1         | 1      | 1.01%   |
| OWC                 | 1         | 1      | 1.01%   |
| NGFF                | 1         | 1      | 1.01%   |
| LS                  | 1         | 1      | 1.01%   |
| Lexar               | 1         | 1      | 1.01%   |
| Intenso             | 1         | 1      | 1.01%   |
| Hewlett-Packard     | 1         | 2      | 1.01%   |
| Gigabyte Technology | 1         | 1      | 1.01%   |
| Fanxiang            | 1         | 1      | 1.01%   |
| Apacer              | 1         | 1      | 1.01%   |
| Unknown             | 1         | 1      | 1.01%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 91        | 112    | 43.75%  |
| NVMe    | 52        | 58     | 25%     |
| HDD     | 49        | 54     | 23.56%  |
| MMC     | 10        | 15     | 4.81%   |
| Unknown | 6         | 6      | 2.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 131       | 169    | 66.84%  |
| NVMe | 52        | 58     | 26.53%  |
| MMC  | 10        | 15     | 5.1%    |
| SAS  | 3         | 3      | 1.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 107       | 125    | 74.83%  |
| 0.51-1.0   | 33        | 37     | 23.08%  |
| 1.01-2.0   | 3         | 4      | 2.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 83        | 46.11%  |
| 251-500        | 44        | 24.44%  |
| 501-1000       | 27        | 15%     |
| 51-100         | 11        | 6.11%   |
| 1001-2000      | 7         | 3.89%   |
| 21-50          | 5         | 2.78%   |
| More than 3000 | 1         | 0.56%   |
| 1-20           | 1         | 0.56%   |
| Unknown        | 1         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 85        | 46.7%   |
| 21-50     | 56        | 30.77%  |
| 101-250   | 15        | 8.24%   |
| 51-100    | 12        | 6.59%   |
| 251-500   | 11        | 6.04%   |
| 2001-3000 | 1         | 0.55%   |
| 501-1000  | 1         | 0.55%   |
| Unknown   | 1         | 0.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Notebooks | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1      | 25%     |
| LS 128GB M300 SSD                           | 1         | 1      | 25%     |
| Intel SSDPEKKF512G7H BTPY71141D7T512F 512GB | 1         | 1      | 25%     |
| Crucial CT240M500SSD3 240GB                 | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 25%     |
| LS      | 1         | 1      | 25%     |
| Intel   | 1         | 1      | 25%     |
| Crucial | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 50%     |
| NVMe | 1         | 1      | 25%     |
| HDD  | 1         | 1      | 25%     |

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
| Detected | 154       | 215    | 85.56%  |
| Works    | 22        | 26     | 12.22%  |
| Malfunc  | 4         | 4      | 2.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 114       | 55.88%  |
| Samsung Electronics          | 20        | 9.8%    |
| AMD                          | 18        | 8.82%   |
| Nvidia                       | 11        | 5.39%   |
| SanDisk                      | 8         | 3.92%   |
| KIOXIA                       | 6         | 2.94%   |
| SK hynix                     | 5         | 2.45%   |
| Toshiba America Info Systems | 4         | 1.96%   |
| Yangtze Memory Technologies  | 2         | 0.98%   |
| Silicon Motion               | 2         | 0.98%   |
| Phison Electronics           | 2         | 0.98%   |
| Micron Technology            | 2         | 0.98%   |
| Kingston Technology Company  | 2         | 0.98%   |
| Solidigm                     | 1         | 0.49%   |
| Shenzhen Longsys Electronics | 1         | 0.49%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.49%   |
| Marvell Technology Group     | 1         | 0.49%   |
| Lite-On Technology           | 1         | 0.49%   |
| ASMedia Technology           | 1         | 0.49%   |
| Apple                        | 1         | 0.49%   |
| ADATA Technology             | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 16        | 7.58%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 16        | 7.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 15        | 7.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 4.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 3.79%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                             | 7         | 3.32%   |
| Nvidia MCP79 AHCI Controller                                                           | 7         | 3.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 3.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 6         | 2.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 6         | 2.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 2.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 5         | 2.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 4         | 1.9%    |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 4         | 1.9%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 4         | 1.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 1.9%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 4         | 1.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 1.9%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                | 3         | 1.42%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                                     | 3         | 1.42%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 3         | 1.42%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 3         | 1.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 1.42%   |
| Yangtze Memory PC005 NVMe SSD                                                          | 2         | 0.95%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 0.95%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.95%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                              | 2         | 0.95%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                          | 2         | 0.95%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                    | 2         | 0.95%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                             | 2         | 0.95%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                  | 2         | 0.95%   |
| Intel SSD 600P Series                                                                  | 2         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.95%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 0.95%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                   | 1         | 0.47%   |
| Toshiba America Info Systems Toshiba America Info SATA controller                      | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 137       | 66.5%   |
| NVMe | 52        | 25.24%  |
| RAID | 12        | 5.83%   |
| IDE  | 5         | 2.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 147       | 83.05%  |
| AMD    | 30        | 16.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 6         | 3.39%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 4         | 2.26%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.69%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.69%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.13%   |
| Intel Core i7-5650U CPU @ 2.20GHz             | 2         | 1.13%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 1.13%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1.13%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.13%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 1.13%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 1.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.13%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.13%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 2         | 1.13%   |
| Intel Core i5-4278U CPU @ 2.60GHz             | 2         | 1.13%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.13%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.13%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 2         | 1.13%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.13%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.13%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 2         | 1.13%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.13%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 2         | 1.13%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 1.13%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 1.13%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.13%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 1.13%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.13%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.13%   |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 0.56%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.56%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.56%   |
| Intel Pentium CPU B980 @ 2.40GHz              | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 55        | 31.07%  |
| Intel Core i7           | 33        | 18.64%  |
| Intel Core 2 Duo        | 16        | 9.04%   |
| Intel Core i3           | 12        | 6.78%   |
| Other                   | 11        | 6.21%   |
| Intel Celeron           | 10        | 5.65%   |
| AMD Ryzen 5             | 10        | 5.65%   |
| AMD Ryzen 7             | 6         | 3.39%   |
| Intel Pentium           | 4         | 2.26%   |
| Intel Atom              | 2         | 1.13%   |
| AMD Ryzen 3             | 2         | 1.13%   |
| AMD A6                  | 2         | 1.13%   |
| Intel Xeon              | 1         | 0.56%   |
| Intel Pentium Silver    | 1         | 0.56%   |
| Intel Core m7           | 1         | 0.56%   |
| Intel Core m3           | 1         | 0.56%   |
| Intel Celeron Dual-Core | 1         | 0.56%   |
| AMD V140                | 1         | 0.56%   |
| AMD Turion II Dual-Core | 1         | 0.56%   |
| AMD Ryzen 5 PRO         | 1         | 0.56%   |
| AMD PRO A10             | 1         | 0.56%   |
| AMD FX                  | 1         | 0.56%   |
| AMD E2                  | 1         | 0.56%   |
| AMD A8                  | 1         | 0.56%   |
| AMD A4                  | 1         | 0.56%   |
| AMD A12                 | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 109       | 61.58%  |
| 4      | 46        | 25.99%  |
| 6      | 10        | 5.65%   |
| 8      | 7         | 3.95%   |
| 1      | 3         | 1.69%   |
| 12     | 1         | 0.56%   |
| 10     | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 177       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 137       | 77.4%   |
| 1      | 40        | 22.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 177       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 169       | 94.94%  |
| 0x08608104 | 2         | 1.12%   |
| 0x806c1    | 1         | 0.56%   |
| 0x0a704104 | 1         | 0.56%   |
| 0x0a404102 | 1         | 0.56%   |
| 0x08608103 | 1         | 0.56%   |
| 0x08108109 | 1         | 0.56%   |
| 0x06001119 | 1         | 0.56%   |
| 0x05000119 | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Haswell          | 23        | 12.99%  |
| KabyLake         | 20        | 11.3%   |
| Penryn           | 17        | 9.6%    |
| SandyBridge      | 14        | 7.91%   |
| IvyBridge        | 12        | 6.78%   |
| Westmere         | 11        | 6.21%   |
| Skylake          | 11        | 6.21%   |
| Broadwell        | 11        | 6.21%   |
| Unknown          | 10        | 5.65%   |
| TigerLake        | 7         | 3.95%   |
| Goldmont plus    | 6         | 3.39%   |
| Zen+             | 5         | 2.82%   |
| IceLake          | 4         | 2.26%   |
| Excavator        | 4         | 2.26%   |
| Zen 3            | 3         | 1.69%   |
| Zen 2            | 2         | 1.13%   |
| Silvermont       | 2         | 1.13%   |
| K10              | 2         | 1.13%   |
| Goldmont         | 2         | 1.13%   |
| CometLake        | 2         | 1.13%   |
| Alderlake Hybrid | 2         | 1.13%   |
| Zen              | 1         | 0.56%   |
| Steamroller      | 1         | 0.56%   |
| Puma             | 1         | 0.56%   |
| Piledriver       | 1         | 0.56%   |
| Jaguar           | 1         | 0.56%   |
| Bonnell          | 1         | 0.56%   |
| Bobcat           | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 127       | 60.77%  |
| Nvidia | 44        | 21.05%  |
| AMD    | 38        | 18.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 6.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 6.1%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 5.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 3.76%   |
| Intel HD Graphics 6000                                                                   | 8         | 3.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 3.76%   |
| Nvidia C79 [GeForce 9400M]                                                               | 7         | 3.29%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.82%   |
| Intel HD Graphics 620                                                                    | 6         | 2.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 2.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.35%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 2.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.35%   |
| AMD Lucienne                                                                             | 5         | 2.35%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 4         | 1.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.41%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 3         | 1.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.41%   |
| Intel HD Graphics 630                                                                    | 3         | 1.41%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.94%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.94%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 0.94%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.94%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 0.94%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.94%   |
| Intel HD Graphics 515                                                                    | 2         | 0.94%   |
| Intel HD Graphics 500                                                                    | 2         | 0.94%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 2         | 0.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.94%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.94%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.94%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.94%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.94%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 0.94%   |
| AMD Barcelo                                                                              | 2         | 0.94%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.47%   |
| Nvidia GT218M [GeForce G 105M]                                                           | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 96        | 54.24%  |
| 1 x AMD        | 27        | 15.25%  |
| Intel + Nvidia | 22        | 12.43%  |
| 1 x Nvidia     | 19        | 10.73%  |
| Intel + AMD    | 7         | 3.95%   |
| 2 x AMD        | 2         | 1.13%   |
| AMD + Nvidia   | 2         | 1.13%   |
| Other          | 1         | 0.56%   |
| 2 x Nvidia     | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 165       | 93.22%  |
| Proprietary | 8         | 4.52%   |
| Unknown     | 4         | 2.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 165       | 92.7%   |
| 0.01-0.5   | 9         | 5.06%   |
| 0.51-1.0   | 2         | 1.12%   |
| 3.01-4.0   | 1         | 0.56%   |
| 1.01-2.0   | 1         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Apple                   | 34        | 17.62%  |
| AU Optronics            | 33        | 17.1%   |
| BOE                     | 25        | 12.95%  |
| LG Display              | 23        | 11.92%  |
| Chimei Innolux          | 23        | 11.92%  |
| Samsung Electronics     | 19        | 9.84%   |
| Chi Mei Optoelectronics | 4         | 2.07%   |
| Lenovo                  | 3         | 1.55%   |
| Toshiba                 | 2         | 1.04%   |
| Sharp                   | 2         | 1.04%   |
| PANDA                   | 2         | 1.04%   |
| Mi                      | 2         | 1.04%   |
| HKC                     | 2         | 1.04%   |
| Goldstar                | 2         | 1.04%   |
| Dell                    | 2         | 1.04%   |
| Acer                    | 2         | 1.04%   |
| ViewSonic               | 1         | 0.52%   |
| VIE                     | 1         | 0.52%   |
| Vestel Elektronik       | 1         | 0.52%   |
| Unknown (XXX)           | 1         | 0.52%   |
| TMX                     | 1         | 0.52%   |
| KDB                     | 1         | 0.52%   |
| ITE                     | 1         | 0.52%   |
| InfoVision              | 1         | 0.52%   |
| HGC                     | 1         | 0.52%   |
| Hewlett-Packard         | 1         | 0.52%   |
| Gigabyte Technology     | 1         | 0.52%   |
| Fujitsu Siemens         | 1         | 0.52%   |
| CTO                     | 1         | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 1.55%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 3         | 1.55%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 3         | 1.55%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 3         | 1.55%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 3         | 1.55%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 3         | 1.55%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 1.04%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch          | 2         | 1.04%   |
| LG Display LCD Monitor LGD03DC 1366x768 277x156mm 12.5-inch           | 2         | 1.04%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 2         | 1.04%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 2         | 1.04%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 2         | 1.04%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 2         | 1.04%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 2         | 1.04%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                  | 2         | 1.04%   |
| Apple Color LCD APPA018 2560x1600 286x179mm 13.3-inch                 | 2         | 1.04%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 2         | 1.04%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 2         | 1.04%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch         | 1         | 0.52%   |
| VIE R270Q144 VIE2700 2560x1440 598x336mm 27.0-inch                    | 1         | 0.52%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 1         | 0.52%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1         | 0.52%   |
| Toshiba TV TSB0108 1360x768 698x393mm 31.5-inch                       | 1         | 0.52%   |
| Toshiba TV TSB0100 1920x1080 580x320mm 26.1-inch                      | 1         | 0.52%   |
| TMX TL160ADMP11-0 TMX1601 2560x1600 345x215mm 16.0-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP1457 2560x1440 276x156mm 12.5-inch               | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM0247 1280x1024 376x301mm 19.0-inch  | 1         | 0.52%   |
| Samsung Electronics LS27A600U SAM7172 2560x1440 597x337mm 27.0-inch   | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3252 1600x900 344x194mm 15.5-inch  | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 63        | 33.87%  |
| 1366x768 (WXGA)    | 54        | 29.03%  |
| 1280x800 (WXGA)    | 15        | 8.06%   |
| 1440x900 (WXGA+)   | 13        | 6.99%   |
| 1600x900 (HD+)     | 8         | 4.3%    |
| 2560x1440 (QHD)    | 6         | 3.23%   |
| 3840x2160 (4K)     | 5         | 2.69%   |
| 2560x1600          | 5         | 2.69%   |
| 2880x1800          | 4         | 2.15%   |
| 1920x1200 (WUXGA)  | 3         | 1.61%   |
| 1680x1050 (WSXGA+) | 2         | 1.08%   |
| 1280x1024 (SXGA)   | 2         | 1.08%   |
| 3440x1440          | 1         | 0.54%   |
| 3072x1920          | 1         | 0.54%   |
| 2560x1080          | 1         | 0.54%   |
| 2160x1440          | 1         | 0.54%   |
| 1920x540           | 1         | 0.54%   |
| 1024x600           | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 69        | 35.75%  |
| 13     | 49        | 25.39%  |
| 14     | 23        | 11.92%  |
| 17     | 12        | 6.22%   |
| 12     | 8         | 4.15%   |
| 27     | 5         | 2.59%   |
| 23     | 4         | 2.07%   |
| 11     | 4         | 2.07%   |
| 16     | 3         | 1.55%   |
| 84     | 2         | 1.04%   |
| 34     | 2         | 1.04%   |
| 31     | 2         | 1.04%   |
| 24     | 2         | 1.04%   |
| 19     | 2         | 1.04%   |
| 72     | 1         | 0.52%   |
| 54     | 1         | 0.52%   |
| 26     | 1         | 0.52%   |
| 22     | 1         | 0.52%   |
| 21     | 1         | 0.52%   |
| 10     | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 112       | 58.03%  |
| 201-300     | 42        | 21.76%  |
| 351-400     | 17        | 8.81%   |
| 501-600     | 12        | 6.22%   |
| 1501-2000   | 3         | 1.55%   |
| 701-800     | 2         | 1.04%   |
| 601-700     | 2         | 1.04%   |
| 401-500     | 2         | 1.04%   |
| 1001-1500   | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 130       | 73.03%  |
| 16/10 | 43        | 24.16%  |
| 5/4   | 2         | 1.12%   |
| 21/9  | 2         | 1.12%   |
| 3/2   | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 69        | 35.75%  |
| 81-90          | 58        | 30.05%  |
| 71-80          | 12        | 6.22%   |
| 121-130        | 9         | 4.66%   |
| 61-70          | 8         | 4.15%   |
| 201-250        | 8         | 4.15%   |
| 301-350        | 5         | 2.59%   |
| More than 1000 | 4         | 2.07%   |
| 51-60          | 4         | 2.07%   |
| 351-500        | 4         | 2.07%   |
| 131-140        | 3         | 1.55%   |
| 111-120        | 3         | 1.55%   |
| 151-200        | 2         | 1.04%   |
| 91-100         | 2         | 1.04%   |
| 41-50          | 1         | 0.52%   |
| 251-300        | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 74        | 38.74%  |
| 101-120       | 67        | 35.08%  |
| 51-100        | 26        | 13.61%  |
| 161-240       | 17        | 8.9%    |
| More than 240 | 5         | 2.62%   |
| 1-50          | 2         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 152       | 85.39%  |
| 2     | 22        | 12.36%  |
| 0     | 4         | 2.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 70        | 25.27%  |
| Realtek Semiconductor             | 65        | 23.47%  |
| Broadcom                          | 40        | 14.44%  |
| Qualcomm Atheros                  | 30        | 10.83%  |
| Broadcom Limited                  | 17        | 6.14%   |
| MediaTek                          | 9         | 3.25%   |
| Nvidia                            | 8         | 2.89%   |
| Samsung Electronics               | 6         | 2.17%   |
| Ralink Technology                 | 3         | 1.08%   |
| Qualcomm Atheros Communications   | 3         | 1.08%   |
| Marvell Technology Group          | 3         | 1.08%   |
| Hewlett-Packard                   | 3         | 1.08%   |
| Ericsson Business Mobile Networks | 3         | 1.08%   |
| Xiaomi                            | 2         | 0.72%   |
| TP-Link                           | 2         | 0.72%   |
| Sierra Wireless                   | 2         | 0.72%   |
| ASIX Electronics                  | 2         | 0.72%   |
| ZyDAS                             | 1         | 0.36%   |
| Ralink                            | 1         | 0.36%   |
| Qualcomm                          | 1         | 0.36%   |
| JMicron Technology                | 1         | 0.36%   |
| Dell                              | 1         | 0.36%   |
| D-Link System                     | 1         | 0.36%   |
| D-Link                            | 1         | 0.36%   |
| ASUSTek Computer                  | 1         | 0.36%   |
| Apple                             | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 32        | 9.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 14        | 4.22%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 11        | 3.31%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 10        | 3.01%   |
| Intel Wireless 7265                                                    | 9         | 2.71%   |
| Intel Wireless 8265 / 8275                                             | 8         | 2.41%   |
| Intel Wireless 7260                                                    | 8         | 2.41%   |
| Nvidia MCP79 Ethernet                                                  | 7         | 2.11%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 7         | 2.11%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 7         | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 1.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.51%   |
| Intel Wireless 3165                                                    | 5         | 1.51%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 1.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 1.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 5         | 1.51%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 5         | 1.51%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 1.2%    |
| Intel Wireless 8260                                                    | 4         | 1.2%    |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 0.9%    |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 3         | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                        | 3         | 0.9%    |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.9%    |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 0.9%    |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                          | 3         | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3         | 0.9%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.6%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2         | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.6%    |
| Ralink MT7601U Wireless Adapter                                        | 2         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 32.99%  |
| Broadcom                        | 37        | 19.07%  |
| Qualcomm Atheros                | 26        | 13.4%   |
| Realtek Semiconductor           | 24        | 12.37%  |
| Broadcom Limited                | 16        | 8.25%   |
| MediaTek                        | 9         | 4.64%   |
| Ralink Technology               | 3         | 1.55%   |
| Qualcomm Atheros Communications | 3         | 1.55%   |
| TP-Link                         | 2         | 1.03%   |
| Sierra Wireless                 | 2         | 1.03%   |
| ZyDAS                           | 1         | 0.52%   |
| Ralink                          | 1         | 0.52%   |
| Qualcomm                        | 1         | 0.52%   |
| Hewlett-Packard                 | 1         | 0.52%   |
| Dell                            | 1         | 0.52%   |
| D-Link System                   | 1         | 0.52%   |
| D-Link                          | 1         | 0.52%   |
| ASUSTek Computer                | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 11        | 5.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 10        | 5.13%   |
| Intel Wireless 7265                                                  | 9         | 4.62%   |
| Intel Wireless 8265 / 8275                                           | 8         | 4.1%    |
| Intel Wireless 7260                                                  | 8         | 4.1%    |
| Broadcom BCM4331 802.11a/b/g/n                                       | 7         | 3.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 6         | 3.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 5         | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5         | 2.56%   |
| Intel Wireless 3165                                                  | 5         | 2.56%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 5         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4         | 2.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 4         | 2.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 2.05%   |
| Intel Wireless 8260                                                  | 4         | 2.05%   |
| Intel Wi-Fi 6 AX201                                                  | 4         | 2.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 3         | 1.54%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                    | 3         | 1.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 3         | 1.54%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 3         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                        | 3         | 1.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 3         | 1.54%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 2         | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.03%   |
| Ralink MT7601U Wireless Adapter                                      | 2         | 1.03%   |
| Qualcomm Atheros AR9271 802.11n                                      | 2         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 1.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 1.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2         | 1.03%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 2         | 1.03%   |
| Intel Ultimate N WiFi Link 5300                                      | 2         | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 1.03%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 1.03%   |
| Broadcom Limited BCM43225 802.11b/g/n                                | 2         | 1.03%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter         | 2         | 1.03%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 2         | 1.03%   |
| ZyDAS ZD1211B 802.11g                                                | 1         | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 49        | 37.4%   |
| Intel                    | 33        | 25.19%  |
| Broadcom                 | 15        | 11.45%  |
| Qualcomm Atheros         | 10        | 7.63%   |
| Nvidia                   | 8         | 6.11%   |
| Samsung Electronics      | 6         | 4.58%   |
| Marvell Technology Group | 3         | 2.29%   |
| Xiaomi                   | 2         | 1.53%   |
| ASIX Electronics         | 2         | 1.53%   |
| JMicron Technology       | 1         | 0.76%   |
| Broadcom Limited         | 1         | 0.76%   |
| Apple                    | 1         | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 32        | 24.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 14        | 10.61%  |
| Nvidia MCP79 Ethernet                                                          | 7         | 5.3%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 7         | 5.3%    |
| Intel Ethernet Connection I218-LM                                              | 5         | 3.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 3.79%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 5         | 3.79%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4         | 3.03%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 2.27%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 2.27%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 2.27%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 2.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 1.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 1.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 1.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 1.52%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.52%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.52%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.76%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.76%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.76%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.76%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.76%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.76%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.76%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.76%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.76%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.76%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.76%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 175       | 56.45%  |
| Ethernet | 130       | 41.94%  |
| Modem    | 5         | 1.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 142       | 79.78%  |
| Ethernet | 36        | 20.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 117       | 66.1%   |
| 1     | 58        | 32.77%  |
| 3     | 1         | 0.56%   |
| 0     | 1         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 124       | 70.06%  |
| Yes  | 53        | 29.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 34.44%  |
| Apple                           | 34        | 22.52%  |
| Realtek Semiconductor           | 16        | 10.6%   |
| Qualcomm Atheros Communications | 11        | 7.28%   |
| Broadcom                        | 8         | 5.3%    |
| Lite-On Technology              | 6         | 3.97%   |
| IMC Networks                    | 6         | 3.97%   |
| Foxconn / Hon Hai               | 5         | 3.31%   |
| Realtek                         | 3         | 1.99%   |
| Hewlett-Packard                 | 3         | 1.99%   |
| Dell                            | 2         | 1.32%   |
| Cambridge Silicon Radio         | 2         | 1.32%   |
| Toshiba                         | 1         | 0.66%   |
| Ralink Technology               | 1         | 0.66%   |
| Opticis                         | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 14.57%  |
| Apple Bluetooth Host Controller                     | 21        | 13.91%  |
| Apple Bluetooth USB Host Controller                 | 12        | 7.95%   |
| Intel Bluetooth Device                              | 10        | 6.62%   |
| Realtek Bluetooth Radio                             | 9         | 5.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 5.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 3.31%   |
| Intel AX201 Bluetooth                               | 4         | 2.65%   |
| IMC Networks Wireless_Device                        | 4         | 2.65%   |
| Realtek Bluetooth Radio                             | 3         | 1.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.99%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.99%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.32%   |
| Realtek RTL8821A Bluetooth                          | 2         | 1.32%   |
| Lite-On Wireless_Device                             | 2         | 1.32%   |
| Lite-On Bluetooth Device                            | 2         | 1.32%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.32%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.32%   |
| Intel AX210 Bluetooth                               | 2         | 1.32%   |
| IMC Networks BCM20702A0                             | 2         | 1.32%   |
| Dell DW375 Bluetooth Module                         | 2         | 1.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.32%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.32%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.66%   |
| Realtek RTL8723A Bluetooth                          | 1         | 0.66%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.66%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.66%   |
| Ralink CSR BS8510                                   | 1         | 0.66%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.66%   |
| Opticis Bluetooth Radio                             | 1         | 0.66%   |
| Lite-On BCM43142A0                                  | 1         | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.66%   |
| Intel AX211 Bluetooth                               | 1         | 0.66%   |
| Intel AX200 Bluetooth                               | 1         | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.66%   |
| Foxconn / Hon Hai BT                                | 1         | 0.66%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.66%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 134       | 65.37%  |
| AMD                                  | 33        | 16.1%   |
| Nvidia                               | 31        | 15.12%  |
| Thesycon Systemsoftware & Consulting | 1         | 0.49%   |
| Kingston Technology                  | 1         | 0.49%   |
| JMTek                                | 1         | 0.49%   |
| JBL                                  | 1         | 0.49%   |
| Huawei Technologies                  | 1         | 0.49%   |
| Guillemot                            | 1         | 0.49%   |
| Apple                                | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 22        | 8.3%    |
| AMD Family 17h/19h HD Audio Controller                                     | 17        | 6.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 5.66%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 4.91%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 4.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 4.15%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 4.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 4.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 4.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 3.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 3.77%   |
| Nvidia MCP79 High Definition Audio                                         | 7         | 2.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 2.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.89%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.89%   |
| Nvidia MCP89 High Definition Audio                                         | 4         | 1.51%   |
| Nvidia GT216 HDMI Audio Controller                                         | 4         | 1.51%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.13%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.13%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 1.13%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.75%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 0.75%   |
| Intel Crystal Well HD Audio Controller                                     | 2         | 0.75%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.75%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.75%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 2         | 0.75%   |
| AMD High Definition Audio Controller                                       | 2         | 0.75%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                              | 1         | 0.38%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.38%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 27.66%  |
| SK hynix            | 8         | 17.02%  |
| Micron Technology   | 7         | 14.89%  |
| Kingston            | 4         | 8.51%   |
| Unknown             | 3         | 6.38%   |
| Elpida              | 3         | 6.38%   |
| Crucial             | 3         | 6.38%   |
| Unknown (ABCD)      | 2         | 4.26%   |
| Corsair             | 2         | 4.26%   |
| Timetec             | 1         | 2.13%   |
| Ramaxel Technology  | 1         | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.92%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 1.96%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                       | 1         | 1.96%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.96%   |
| Unknown RAM Module 1GB SODIMM DDR3                               | 1         | 1.96%   |
| Unknown RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.96%   |
| Timetec RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 1.96%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.96%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.96%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 1.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.96%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 1.96%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.96%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 1         | 1.96%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.96%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.96%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.96%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.96%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.96%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.96%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM DDR5 4800MT/s          | 1         | 1.96%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 1.96%   |
| Samsung RAM M04GD08P1333C9 4GB SODIMM DDR3 667MT/s               | 1         | 1.96%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.96%   |
| Ramaxel RAM RMN1740EC48D8W-800 2GB SODIMM DDR2 800MT/s           | 1         | 1.96%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.96%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 1         | 1.96%   |
| Micron RAM MT41K256M16LY-107 2GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 1         | 1.96%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.96%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s            | 1         | 1.96%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.96%   |
| Kingston RAM HX316LS9IB/8 8GB SODIMM DDR3 1600MT/s               | 1         | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 16        | 42.11%  |
| DDR4   | 13        | 34.21%  |
| LPDDR4 | 3         | 7.89%   |
| LPDDR5 | 2         | 5.26%   |
| SDRAM  | 1         | 2.63%   |
| LPDDR3 | 1         | 2.63%   |
| DDR5   | 1         | 2.63%   |
| DDR2   | 1         | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 84.62%  |
| Row Of Chips | 6         | 15.38%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 18        | 42.86%  |
| 4096  | 12        | 28.57%  |
| 2048  | 6         | 14.29%  |
| 16384 | 5         | 11.9%   |
| 1024  | 1         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 10        | 24.39%  |
| 3200    | 6         | 14.63%  |
| 2667    | 6         | 14.63%  |
| 2133    | 3         | 7.32%   |
| 6400    | 2         | 4.88%   |
| 2400    | 2         | 4.88%   |
| 1333    | 2         | 4.88%   |
| 1067    | 2         | 4.88%   |
| 4800    | 1         | 2.44%   |
| 4266    | 1         | 2.44%   |
| 2048    | 1         | 2.44%   |
| 1867    | 1         | 2.44%   |
| 1334    | 1         | 2.44%   |
| 800     | 1         | 2.44%   |
| 667     | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lexmark International | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lexmark International f+ imaging M40adn | 1         | 100%    |

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
| Apple                                  | 24        | 16.11%  |
| Chicony Electronics                    | 23        | 15.44%  |
| IMC Networks                           | 13        | 8.72%   |
| Microdia                               | 11        | 7.38%   |
| Realtek Semiconductor                  | 9         | 6.04%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 6.04%   |
| Quanta                                 | 8         | 5.37%   |
| Suyin                                  | 6         | 4.03%   |
| Sunplus Innovation Technology          | 6         | 4.03%   |
| Bison Electronics                      | 6         | 4.03%   |
| Lite-On Technology                     | 5         | 3.36%   |
| Syntek                                 | 4         | 2.68%   |
| Ricoh                                  | 3         | 2.01%   |
| SunplusIT                              | 2         | 1.34%   |
| Sonix Technology                       | 2         | 1.34%   |
| Silicon Motion                         | 2         | 1.34%   |
| ShineTech                              | 2         | 1.34%   |
| Alcor Micro                            | 2         | 1.34%   |
| Y Media                                | 1         | 0.67%   |
| Sunplus Technology                     | 1         | 0.67%   |
| Samsung Electronics                    | 1         | 0.67%   |
| Primax Electronics                     | 1         | 0.67%   |
| OYT Tech                               | 1         | 0.67%   |
| MacroSilicon                           | 1         | 0.67%   |
| Luxvisions Innotech Limited            | 1         | 0.67%   |
| LG Electronics                         | 1         | 0.67%   |
| Goodong Industry                       | 1         | 0.67%   |
| GEMBIRD                                | 1         | 0.67%   |
| ALi                                    | 1         | 0.67%   |
| Unknown                                | 1         | 0.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                       | 12        | 7.95%   |
| Apple FaceTime HD Camera                                    | 7         | 4.64%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 3.97%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                             | 5         | 3.31%   |
| Microdia Integrated_Webcam_HD                               | 4         | 2.65%   |
| Microdia Integrated Webcam                                  | 4         | 2.65%   |
| Chicony Integrated Camera                                   | 4         | 2.65%   |
| Syntek Integrated Camera                                    | 3         | 1.99%   |
| Realtek Integrated_Webcam_HD                                | 3         | 1.99%   |
| Quanta HD User Facing                                       | 3         | 1.99%   |
| IMC Networks Integrated Camera                              | 3         | 1.99%   |
| Chicony HP Truevision HD camera                             | 3         | 1.99%   |
| ShineTech USB2.0 HD UVC WebCam                              | 2         | 1.32%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.32%   |
| Realtek USB Camera                                          | 2         | 1.32%   |
| Quanta HD Camera                                            | 2         | 1.32%   |
| Lite-On HP HD Camera                                        | 2         | 1.32%   |
| Chicony HP Truevision HD                                    | 2         | 1.32%   |
| Chicony HD WebCam                                           | 2         | 1.32%   |
| Chicony EasyCamera                                          | 2         | 1.32%   |
| Bison SunplusIT Integrated Camera                           | 2         | 1.32%   |
| Bison Integrated Camera                                     | 2         | 1.32%   |
| Y Media USB Camera                                          | 1         | 0.66%   |
| Syntek EasyCamera                                           | 1         | 0.66%   |
| Suyin HP webcam [dv6-1190en]                                | 1         | 0.66%   |
| Suyin HP Truevision HD                                      | 1         | 0.66%   |
| Suyin HD WebCam                                             | 1         | 0.66%   |
| Suyin HD Video WebCam                                       | 1         | 0.66%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.66%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.66%   |
| SunplusIT XiaoMi Webcam                                     | 1         | 0.66%   |
| SunplusIT USB Camera                                        | 1         | 0.66%   |
| Sunplus 1.3M WebCam                                         | 1         | 0.66%   |
| Sunplus PC Camera                                           | 1         | 0.66%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 0.66%   |
| Sunplus Laptop Integrated Webcam FHD                        | 1         | 0.66%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.66%   |
| Sunplus HD WebCam                                           | 1         | 0.66%   |
| Sunplus Asus Webcam                                         | 1         | 0.66%   |
| Sonix USB2.0 FHD UVC WebCam                                 | 1         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 59.26%  |
| Synaptics                  | 4         | 14.81%  |
| Shenzhen Goodix Technology | 4         | 14.81%  |
| Upek                       | 1         | 3.7%    |
| LighTuning Technology      | 1         | 3.7%    |
| AuthenTec                  | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 18.52%  |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 14.81%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 7.41%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 7.41%   |
| Validity Sensors VFS491                                                    | 1         | 3.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.7%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 3.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.7%    |
| Synaptics UWP WBDI Device                                                  | 1         | 3.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 3.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 3.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 3.7%    |
| AuthenTec AES2810                                                          | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 61.54%  |
| Alcor Micro | 2         | 15.38%  |
| Upek        | 1         | 7.69%   |
| O2 Micro    | 1         | 7.69%   |
| Lenovo      | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 23.08%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 15.38%  |
| Broadcom 5880                                                                | 2         | 15.38%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 15.38%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 7.69%   |
| Broadcom 58200                                                               | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 98        | 55.06%  |
| 1     | 60        | 33.71%  |
| 2     | 19        | 10.67%  |
| 3     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 27        | 27.27%  |
| Net/wireless          | 25        | 25.25%  |
| Multimedia controller | 17        | 17.17%  |
| Chipcard              | 12        | 12.12%  |
| Graphics card         | 7         | 7.07%   |
| Storage               | 4         | 4.04%   |
| Camera                | 3         | 3.03%   |
| Sound                 | 1         | 1.01%   |
| Network               | 1         | 1.01%   |
| Modem                 | 1         | 1.01%   |
| Bluetooth             | 1         | 1.01%   |

