Elementary 7 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Elementary 7.

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

Total: 148

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro8,1               | [d487214e2a](https://linux-hardware.org/?probe=d487214e2a) | Jun 08, 2023 |
| Apple         | MacBookPro11,1              | [6c62565787](https://linux-hardware.org/?probe=6c62565787) | Jun 07, 2023 |
| ASUSTek       | G750JM                      | [b2281ad2cb](https://linux-hardware.org/?probe=b2281ad2cb) | Jun 06, 2023 |
| Toshiba       | TECRA Z40-C                 | [1ebf23281e](https://linux-hardware.org/?probe=1ebf23281e) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | [274b78cda3](https://linux-hardware.org/?probe=274b78cda3) | Jun 03, 2023 |
| Apple         | MacBookAir7,2               | [119fd5249f](https://linux-hardware.org/?probe=119fd5249f) | Jun 03, 2023 |
| HUAWEI        | BOD-WXX9                    | [532dea434a](https://linux-hardware.org/?probe=532dea434a) | Jun 02, 2023 |
| HP            | G62                         | [f2600c2f4b](https://linux-hardware.org/?probe=f2600c2f4b) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS08H00    | [71208c2344](https://linux-hardware.org/?probe=71208c2344) | Jun 01, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [827e0203ac](https://linux-hardware.org/?probe=827e0203ac) | May 31, 2023 |
| ASUSTek       | X550WA                      | [864236b0c9](https://linux-hardware.org/?probe=864236b0c9) | May 29, 2023 |
| PCBOX         | Kant                        | [1e2f772d05](https://linux-hardware.org/?probe=1e2f772d05) | May 29, 2023 |
| HP            | ProBook 440 G6              | [35d14ed328](https://linux-hardware.org/?probe=35d14ed328) | May 29, 2023 |
| HP            | ProBook 440 G6              | [36a3563566](https://linux-hardware.org/?probe=36a3563566) | May 29, 2023 |
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
| Acer          | Aspire E3-111               | [1060697095](https://linux-hardware.org/?probe=1060697095) | May 10, 2023 |
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
| Apple         | MacBookPro5,2               | [c188ae4d7d](https://linux-hardware.org/?probe=c188ae4d7d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| MSI           | GE62VR 6RF                  | [2a9fcae8c3](https://linux-hardware.org/?probe=2a9fcae8c3) | Apr 28, 2023 |
| HUAWEI        | BOD-WXX9                    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| MSI           | PE70 6QE                    | [87c8761eff](https://linux-hardware.org/?probe=87c8761eff) | Apr 27, 2023 |
| HP            | 250 G8 Notebook PC          | [b03cd2f2d2](https://linux-hardware.org/?probe=b03cd2f2d2) | Apr 26, 2023 |
| MSI           | PE70 6QE                    | [53dd8334ac](https://linux-hardware.org/?probe=53dd8334ac) | Apr 26, 2023 |
| Lenovo        | G580 20150                  | [5d8b07dbbd](https://linux-hardware.org/?probe=5d8b07dbbd) | Apr 25, 2023 |
| Dell          | Latitude E4300              | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | [763953fb60](https://linux-hardware.org/?probe=763953fb60) | Apr 22, 2023 |
| HP            | Pavilion g6                 | [4d60e2b7da](https://linux-hardware.org/?probe=4d60e2b7da) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | [94bf014457](https://linux-hardware.org/?probe=94bf014457) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | [2ebc6a2f61](https://linux-hardware.org/?probe=2ebc6a2f61) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | [ff6dbdcc10](https://linux-hardware.org/?probe=ff6dbdcc10) | Apr 15, 2023 |
| MSI           | PE70 6QE                    | [936a7d1fe3](https://linux-hardware.org/?probe=936a7d1fe3) | Apr 15, 2023 |
| Dell          | Latitude 5420               | [4c6427b3fc](https://linux-hardware.org/?probe=4c6427b3fc) | Apr 14, 2023 |
| Apple         | MacBookAir3,2               | [c750ece414](https://linux-hardware.org/?probe=c750ece414) | Apr 12, 2023 |
| Dell          | Latitude E5570              | [81eaf54f19](https://linux-hardware.org/?probe=81eaf54f19) | Apr 07, 2023 |
| Apple         | MacBookPro10,1              | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| HUAWEI        | BOD-WXX9                    | [3f9238067d](https://linux-hardware.org/?probe=3f9238067d) | Apr 04, 2023 |
| HP            | Pavilion 15                 | [1a3e968dff](https://linux-hardware.org/?probe=1a3e968dff) | Apr 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f7f207f61c](https://linux-hardware.org/?probe=f7f207f61c) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | [e06d57c27a](https://linux-hardware.org/?probe=e06d57c27a) | Apr 01, 2023 |
| HUAWEI        | NBD-WXX9                    | [d4c718bdab](https://linux-hardware.org/?probe=d4c718bdab) | Apr 01, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| Dell          | Latitude E7440              | [1159c854cd](https://linux-hardware.org/?probe=1159c854cd) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | [a9a8004509](https://linux-hardware.org/?probe=a9a8004509) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | [1dccfbe9f4](https://linux-hardware.org/?probe=1dccfbe9f4) | Mar 29, 2023 |
| Dell          | Latitude 5420               | [d714c46c4f](https://linux-hardware.org/?probe=d714c46c4f) | Mar 29, 2023 |
| Toshiba       | TECRA Z40-C                 | [39995c1c00](https://linux-hardware.org/?probe=39995c1c00) | Mar 24, 2023 |
| Dell          | Latitude E7440              | [1a986dbeb8](https://linux-hardware.org/?probe=1a986dbeb8) | Mar 24, 2023 |
| HONOR         | HYM-WXX                     | [df318ed208](https://linux-hardware.org/?probe=df318ed208) | Mar 21, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [e40cf4f577](https://linux-hardware.org/?probe=e40cf4f577) | Mar 18, 2023 |
| Dell          | Latitude E5570              | [a15d1b43ca](https://linux-hardware.org/?probe=a15d1b43ca) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [dd07b0c3b3](https://linux-hardware.org/?probe=dd07b0c3b3) | Mar 17, 2023 |
| Dell          | G3 3590                     | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | [03e5d43f27](https://linux-hardware.org/?probe=03e5d43f27) | Mar 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | [4c49d73583](https://linux-hardware.org/?probe=4c49d73583) | Mar 15, 2023 |
| Apple         | MacBookPro5,5               | [c6ff6d14a0](https://linux-hardware.org/?probe=c6ff6d14a0) | Mar 15, 2023 |
| Acer          | Aspire V3-771               | [28f8273eb5](https://linux-hardware.org/?probe=28f8273eb5) | Mar 15, 2023 |
| MSI           | GT72 2QE                    | [b3c4766473](https://linux-hardware.org/?probe=b3c4766473) | Mar 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | [a2ee9a2818](https://linux-hardware.org/?probe=a2ee9a2818) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK A359               | [0fa1ebbc11](https://linux-hardware.org/?probe=0fa1ebbc11) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK A359               | [f977012127](https://linux-hardware.org/?probe=f977012127) | Mar 11, 2023 |
| Apple         | MacBookPro11,2              | [fce6120754](https://linux-hardware.org/?probe=fce6120754) | Mar 11, 2023 |
| Acer          | Aspire A715-72G             | [32b2d1b194](https://linux-hardware.org/?probe=32b2d1b194) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [82b5297ab8](https://linux-hardware.org/?probe=82b5297ab8) | Mar 11, 2023 |
| Toshiba       | TECRA Z40-C                 | [a4ba2ff90e](https://linux-hardware.org/?probe=a4ba2ff90e) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Sony          | VPCEH2C5E                   | [adf4a69310](https://linux-hardware.org/?probe=adf4a69310) | Mar 07, 2023 |
| Sony          | VPCEH2C5E                   | [9e5b625dda](https://linux-hardware.org/?probe=9e5b625dda) | Mar 07, 2023 |
| GPU Compan... | GWTN156-11                  | [5afd8e3f42](https://linux-hardware.org/?probe=5afd8e3f42) | Mar 04, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [817b72f78f](https://linux-hardware.org/?probe=817b72f78f) | Mar 02, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [053c6d5368](https://linux-hardware.org/?probe=053c6d5368) | Mar 02, 2023 |
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
| HP            | OMEN by Laptop 17-ck0xxx    | [12431d8083](https://linux-hardware.org/?probe=12431d8083) | Feb 14, 2023 |
| Acer          | Extensa 5230                | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | [a1d85b3098](https://linux-hardware.org/?probe=a1d85b3098) | Feb 10, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [9de542dff7](https://linux-hardware.org/?probe=9de542dff7) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | [6e8ed5d5d6](https://linux-hardware.org/?probe=6e8ed5d5d6) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| HP            | Laptop 15-dy2xxx            | [b906f960a0](https://linux-hardware.org/?probe=b906f960a0) | Feb 08, 2023 |
| HP            | Laptop 14-bs0xx             | [c3607bb4c2](https://linux-hardware.org/?probe=c3607bb4c2) | Feb 07, 2023 |
| HP            | Laptop 17-by3xxx            | [07ea9d3c2f](https://linux-hardware.org/?probe=07ea9d3c2f) | Feb 06, 2023 |
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
| Lenovo        | ThinkPad X230 23259S9       | [3d9e74535f](https://linux-hardware.org/?probe=3d9e74535f) | Feb 01, 2023 |
| Star Labs     | StarBook                    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS01W02    | [cc7b02033a](https://linux-hardware.org/?probe=cc7b02033a) | Dec 24, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.15.0-58-generic    | 27        | 25.96%  |
| 5.19.0-41-generic    | 18        | 17.31%  |
| 5.19.0-35-generic    | 17        | 16.35%  |
| 5.19.0-32-generic    | 12        | 11.54%  |
| 5.19.0-38-generic    | 9         | 8.65%   |
| 5.19.0-43-generic    | 6         | 5.77%   |
| 5.19.0-40-generic    | 4         | 3.85%   |
| 5.15.0-60-generic    | 4         | 3.85%   |
| 5.19.0-42-generic    | 2         | 1.92%   |
| 6.2.7-060207-generic | 1         | 0.96%   |
| 6.1.9-060109-generic | 1         | 0.96%   |
| 6.1.6-060106-generic | 1         | 0.96%   |
| 6.1.0-1013-oem       | 1         | 0.96%   |
| 5.15.0-56-generic    | 1         | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.0  | 64        | 64%     |
| 5.15.0  | 32        | 32%     |
| 6.2.7   | 1         | 1%      |
| 6.1.9   | 1         | 1%      |
| 6.1.6   | 1         | 1%      |
| 6.1.0   | 1         | 1%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19    | 64        | 64%     |
| 5.15    | 32        | 32%     |
| 6.1     | 3         | 3%      |
| 6.2     | 1         | 1%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 98        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 98        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 98        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 78        | 79.59%  |
| LightDM | 20        | 20.41%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 42        | 42.86%  |
| de_DE | 16        | 16.33%  |
| ru_RU | 9         | 9.18%   |
| es_ES | 8         | 8.16%   |
| fr_FR | 4         | 4.08%   |
| en_GB | 4         | 4.08%   |
| pl_PL | 3         | 3.06%   |
| sv_SE | 2         | 2.04%   |
| it_IT | 2         | 2.04%   |
| uk_UA | 1         | 1.02%   |
| pt_PT | 1         | 1.02%   |
| pt_BR | 1         | 1.02%   |
| nb_NO | 1         | 1.02%   |
| hu_HU | 1         | 1.02%   |
| en_AU | 1         | 1.02%   |
| el_GR | 1         | 1.02%   |
| da_DK | 1         | 1.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 82        | 83.67%  |
| EFI  | 16        | 16.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 94        | 94.95%  |
| Tmpfs   | 2         | 2.02%   |
| Xfs     | 1         | 1.01%   |
| Overlay | 1         | 1.01%   |
| Btrfs   | 1         | 1.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 78        | 79.59%  |
| GPT     | 18        | 18.37%  |
| MBR     | 2         | 2.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 98.98%  |
| Yes       | 1         | 1.02%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 92.86%  |
| Yes       | 7         | 7.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 20        | 20.41%  |
| Lenovo              | 17        | 17.35%  |
| Apple               | 12        | 12.24%  |
| Dell                | 10        | 10.2%   |
| ASUSTek Computer    | 9         | 9.18%   |
| Acer                | 7         | 7.14%   |
| MSI                 | 4         | 4.08%   |
| HUAWEI              | 4         | 4.08%   |
| Fujitsu             | 3         | 3.06%   |
| Toshiba             | 2         | 2.04%   |
| Sony                | 2         | 2.04%   |
| HONOR               | 2         | 2.04%   |
| Star Labs           | 1         | 1.02%   |
| Samsung Electronics | 1         | 1.02%   |
| PCBOX               | 1         | 1.02%   |
| GPU Company         | 1         | 1.02%   |
| Clevo               | 1         | 1.02%   |
| Alienware           | 1         | 1.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HUAWEI BOD-WXX9                            | 2         | 2.04%   |
| HP 255 G7 Notebook PC                      | 2         | 2.04%   |
| Toshiba TECRA Z40-C                        | 1         | 1.02%   |
| Toshiba Satellite C660                     | 1         | 1.02%   |
| Star Labs StarBook                         | 1         | 1.02%   |
| Sony VPCEH2C5E                             | 1         | 1.02%   |
| Sony SVF1521O4E                            | 1         | 1.02%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 1.02%   |
| PCBOX Kant                                 | 1         | 1.02%   |
| MSI PE70 6QE                               | 1         | 1.02%   |
| MSI GT72 2QE                               | 1         | 1.02%   |
| MSI GE62VR 6RF                             | 1         | 1.02%   |
| MSI CX61 2PC                               | 1         | 1.02%   |
| Lenovo V14 G2 ITL 82KA                     | 1         | 1.02%   |
| Lenovo ThinkPad X240 20AMS0XP0S            | 1         | 1.02%   |
| Lenovo ThinkPad X230 23259S9               | 1         | 1.02%   |
| Lenovo ThinkPad X13 Gen 1 20T3S3SH0U       | 1         | 1.02%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW   | 1         | 1.02%   |
| Lenovo ThinkPad T495 20NKS01W02            | 1         | 1.02%   |
| Lenovo ThinkPad T460 20FMS08H00            | 1         | 1.02%   |
| Lenovo ThinkPad T440p 20AWS38H0G           | 1         | 1.02%   |
| Lenovo ThinkPad T400s 2808D9G              | 1         | 1.02%   |
| Lenovo ThinkPad P51s 20HB001TUS            | 1         | 1.02%   |
| Lenovo ThinkPad E560 20EV003DSP            | 1         | 1.02%   |
| Lenovo ThinkBook 13s G3 ACN 20YA           | 1         | 1.02%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 1.02%   |
| Lenovo IdeaPad 320-15IKB 80XL              | 1         | 1.02%   |
| Lenovo IdeaPad 320-15ABR 80XS              | 1         | 1.02%   |
| Lenovo IdeaPad 3 15ALC6 82KU               | 1         | 1.02%   |
| Lenovo G580 20150                          | 1         | 1.02%   |
| HUAWEI NBLB-WAX9N                          | 1         | 1.02%   |
| HUAWEI NBD-WXX9                            | 1         | 1.02%   |
| HONOR HYM-WXX                              | 1         | 1.02%   |
| HONOR BMH-WCX9                             | 1         | 1.02%   |
| HP ProBook 4540s                           | 1         | 1.02%   |
| HP ProBook 450 G6                          | 1         | 1.02%   |
| HP ProBook 450 15.6 inch G9 Notebook PC    | 1         | 1.02%   |
| HP ProBook 440 G6                          | 1         | 1.02%   |
| HP ProBook 4310s                           | 1         | 1.02%   |
| HP Pavilion Notebook                       | 1         | 1.02%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 10        | 10.2%   |
| Acer Aspire        | 7         | 7.14%   |
| HP ProBook         | 5         | 5.1%    |
| HP Pavilion        | 5         | 5.1%    |
| Dell Latitude      | 5         | 5.1%    |
| ASUS ZenBook       | 4         | 4.08%   |
| Lenovo IdeaPad     | 3         | 3.06%   |
| HP Laptop          | 3         | 3.06%   |
| Fujitsu LIFEBOOK   | 3         | 3.06%   |
| Apple MacBookPro11 | 3         | 3.06%   |
| HUAWEI BOD-WXX9    | 2         | 2.04%   |
| HP 255             | 2         | 2.04%   |
| Dell XPS           | 2         | 2.04%   |
| ASUS VivoBook      | 2         | 2.04%   |
| Apple MacBookPro5  | 2         | 2.04%   |
| Apple MacBookAir3  | 2         | 2.04%   |
| Toshiba TECRA      | 1         | 1.02%   |
| Toshiba Satellite  | 1         | 1.02%   |
| Star Labs StarBook | 1         | 1.02%   |
| Sony VPCEH2C5E     | 1         | 1.02%   |
| Sony SVF1521O4E    | 1         | 1.02%   |
| Samsung 300E4A     | 1         | 1.02%   |
| PCBOX Kant         | 1         | 1.02%   |
| MSI PE70           | 1         | 1.02%   |
| MSI GT72           | 1         | 1.02%   |
| MSI GE62VR         | 1         | 1.02%   |
| MSI CX61           | 1         | 1.02%   |
| Lenovo V14         | 1         | 1.02%   |
| Lenovo ThinkBook   | 1         | 1.02%   |
| Lenovo Legion      | 1         | 1.02%   |
| Lenovo G580        | 1         | 1.02%   |
| HUAWEI NBLB-WAX9N  | 1         | 1.02%   |
| HUAWEI NBD-WXX9    | 1         | 1.02%   |
| HONOR HYM-WXX      | 1         | 1.02%   |
| HONOR BMH-WCX9     | 1         | 1.02%   |
| HP OMEN            | 1         | 1.02%   |
| HP G62             | 1         | 1.02%   |
| HP EliteBook       | 1         | 1.02%   |
| HP 550             | 1         | 1.02%   |
| HP 250             | 1         | 1.02%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 10        | 10.2%   |
| 2020 | 10        | 10.2%   |
| 2019 | 8         | 8.16%   |
| 2016 | 8         | 8.16%   |
| 2014 | 8         | 8.16%   |
| 2012 | 8         | 8.16%   |
| 2022 | 7         | 7.14%   |
| 2015 | 7         | 7.14%   |
| 2018 | 6         | 6.12%   |
| 2013 | 5         | 5.1%    |
| 2010 | 5         | 5.1%    |
| 2009 | 5         | 5.1%    |
| 2017 | 4         | 4.08%   |
| 2011 | 3         | 3.06%   |
| 2008 | 3         | 3.06%   |
| 2023 | 1         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 98        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 92        | 93.88%  |
| Enabled  | 6         | 6.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 97        | 98.98%  |
| Yes  | 1         | 1.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 33        | 33.67%  |
| 8.01-16.0   | 20        | 20.41%  |
| 16.01-24.0  | 18        | 18.37%  |
| 3.01-4.0    | 16        | 16.33%  |
| 32.01-64.0  | 7         | 7.14%   |
| 1.01-2.0    | 2         | 2.04%   |
| 2.01-3.0    | 1         | 1.02%   |
| 64.01-256.0 | 1         | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 45        | 43.27%  |
| 3.01-4.0  | 22        | 21.15%  |
| 1.01-2.0  | 22        | 21.15%  |
| 4.01-8.0  | 13        | 12.5%   |
| 8.01-16.0 | 1         | 0.96%   |
| 0.51-1.0  | 1         | 0.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 77        | 77.78%  |
| 2      | 21        | 21.21%  |
| 4      | 1         | 1.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 64.29%  |
| Yes       | 35        | 35.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 77.55%  |
| No        | 22        | 22.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 87.76%  |
| No        | 12        | 12.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 19        | 19.39%  |
| USA          | 17        | 17.35%  |
| Russia       | 9         | 9.18%   |
| Poland       | 5         | 5.1%    |
| UK           | 4         | 4.08%   |
| France       | 4         | 4.08%   |
| Thailand     | 2         | 2.04%   |
| Spain        | 2         | 2.04%   |
| Norway       | 2         | 2.04%   |
| Netherlands  | 2         | 2.04%   |
| Mexico       | 2         | 2.04%   |
| Italy        | 2         | 2.04%   |
| India        | 2         | 2.04%   |
| Australia    | 2         | 2.04%   |
| Tunisia      | 1         | 1.02%   |
| Sweden       | 1         | 1.02%   |
| South Africa | 1         | 1.02%   |
| Saudi Arabia | 1         | 1.02%   |
| Puerto Rico  | 1         | 1.02%   |
| Portugal     | 1         | 1.02%   |
| Kazakhstan   | 1         | 1.02%   |
| Israel       | 1         | 1.02%   |
| Ireland      | 1         | 1.02%   |
| Indonesia    | 1         | 1.02%   |
| Hungary      | 1         | 1.02%   |
| Greece       | 1         | 1.02%   |
| Georgia      | 1         | 1.02%   |
| Ecuador      | 1         | 1.02%   |
| Denmark      | 1         | 1.02%   |
| Cyprus       | 1         | 1.02%   |
| Colombia     | 1         | 1.02%   |
| China        | 1         | 1.02%   |
| Canada       | 1         | 1.02%   |
| Brazil       | 1         | 1.02%   |
| Belgium      | 1         | 1.02%   |
| Austria      | 1         | 1.02%   |
| Argentina    | 1         | 1.02%   |
| Albania      | 1         | 1.02%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 4         | 3.96%   |
| Warsaw                  | 2         | 1.98%   |
| Stuttgart               | 2         | 1.98%   |
| Berlin                  | 2         | 1.98%   |
| Bangkok                 | 2         | 1.98%   |
| Zhuantang               | 1         | 0.99%   |
| Worcestershire          | 1         | 0.99%   |
| Wiesbaden               | 1         | 0.99%   |
| Villefranche-sur-Saône | 1         | 0.99%   |
| Vigo                    | 1         | 0.99%   |
| Vienna                  | 1         | 0.99%   |
| Twickenham              | 1         | 0.99%   |
| Tuam                    | 1         | 0.99%   |
| Tromsø                 | 1         | 0.99%   |
| Troisdorf               | 1         | 0.99%   |
| Tirana                  | 1         | 0.99%   |
| Tel Aviv                | 1         | 0.99%   |
| Tbilisi                 | 1         | 0.99%   |
| Stockholm               | 1         | 0.99%   |
| St Petersburg           | 1         | 0.99%   |
| Spaichingen             | 1         | 0.99%   |
| Slavyansk-na-Kubani     | 1         | 0.99%   |
| Sfax                    | 1         | 0.99%   |
| Sarasota                | 1         | 0.99%   |
| San Juan                | 1         | 0.99%   |
| Salzgitter              | 1         | 0.99%   |
| Rostov-on-Don           | 1         | 0.99%   |
| Roosendaal              | 1         | 0.99%   |
| Portimao                | 1         | 0.99%   |
| Perth                   | 1         | 0.99%   |
| Pécs                   | 1         | 0.99%   |
| Odessa                  | 1         | 0.99%   |
| Oaxaca City             | 1         | 0.99%   |
| Novosibirsk             | 1         | 0.99%   |
| Nicosia                 | 1         | 0.99%   |
| Newcastle upon Tyne     | 1         | 0.99%   |
| Munich                  | 1         | 0.99%   |
| Mundelein               | 1         | 0.99%   |
| Monza                   | 1         | 0.99%   |
| Miami                   | 1         | 0.99%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 18        | 19     | 15.13%  |
| WDC                         | 11        | 12     | 9.24%   |
| Crucial                     | 9         | 10     | 7.56%   |
| Toshiba                     | 8         | 10     | 6.72%   |
| Seagate                     | 8         | 9      | 6.72%   |
| SanDisk                     | 8         | 9      | 6.72%   |
| Apple                       | 8         | 8      | 6.72%   |
| Kingston                    | 6         | 7      | 5.04%   |
| Unknown                     | 4         | 5      | 3.36%   |
| Phison Electronics          | 3         | 3      | 2.52%   |
| SK hynix                    | 2         | 3      | 1.68%   |
| Micron Technology           | 2         | 2      | 1.68%   |
| KIOXIA                      | 2         | 3      | 1.68%   |
| JMicron Technology          | 2         | 2      | 1.68%   |
| Intenso                     | 2         | 3      | 1.68%   |
| Intel                       | 2         | 3      | 1.68%   |
| HGST                        | 2         | 3      | 1.68%   |
| China                       | 2         | 2      | 1.68%   |
| USB 3.0                     | 1         | 1      | 0.84%   |
| Union Memory                | 1         | 2      | 0.84%   |
| T-FORCE                     | 1         | 1      | 0.84%   |
| Star Drive                  | 1         | 1      | 0.84%   |
| SPCC                        | 1         | 1      | 0.84%   |
| Solid State Storage         | 1         | 1      | 0.84%   |
| Silicon Motion              | 1         | 1      | 0.84%   |
| Realtek Semiconductor       | 1         | 2      | 0.84%   |
| PNY                         | 1         | 1      | 0.84%   |
| OWC                         | 1         | 1      | 0.84%   |
| LITEON                      | 1         | 1      | 0.84%   |
| Kingston Technology Company | 1         | 1      | 0.84%   |
| JetFlash                    | 1         | 1      | 0.84%   |
| Inland                      | 1         | 1      | 0.84%   |
| Hitachi                     | 1         | 1      | 0.84%   |
| GeIL                        | 1         | 1      | 0.84%   |
| Fujitsu                     | 1         | 1      | 0.84%   |
| Biwin Storage Technology    | 1         | 1      | 0.84%   |
| BIWIN                       | 1         | 1      | 0.84%   |
| ASMT                        | 1         | 1      | 0.84%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 3         | 2.48%   |
| Phison E12 NVMe Controller 256GB                    | 3         | 2.48%   |
| Unknown MMC Card  32GB                              | 2         | 1.65%   |
| Seagate Expansion 1TB                               | 2         | 1.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 1.65%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1.65%   |
| HGST HTS721010A9E630 1TB                            | 2         | 1.65%   |
| Crucial CT250MX500SSD1 250GB                        | 2         | 1.65%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 1.65%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.83%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.83%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.83%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 0.83%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 0.83%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 0.83%   |
| WDC WD10SPCX-08S8TT0 1TB                            | 1         | 0.83%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.83%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 1         | 0.83%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB                | 1         | 0.83%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                | 1         | 0.83%   |
| USB 3.0 Device 250GB                                | 1         | 0.83%   |
| Unknown MMC Card  7GB                               | 1         | 0.83%   |
| Unknown MMC Card  128GB                             | 1         | 0.83%   |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB             | 1         | 0.83%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 1         | 0.83%   |
| Toshiba THNSNJ128GCSU 128GB SSD                     | 1         | 0.83%   |
| Toshiba THNSNJ128G8NU 128GB SSD                     | 1         | 0.83%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD             | 1         | 0.83%   |
| Toshiba NVMe Controller 256GB                       | 1         | 0.83%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 0.83%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.83%   |
| Toshiba MK3256GSY 320GB                             | 1         | 0.83%   |
| T-FORCE 2TB                                         | 1         | 0.83%   |
| Star Drive PCIe SSD 480GB                           | 1         | 0.83%   |
| SPCC Solid State Disk 512GB                         | 1         | 0.83%   |
| Solid State Storage CL1-3D512-Q11 NVMe SSSTC 512GB  | 1         | 0.83%   |
| SK hynix PC711 NVMe 1TB                             | 1         | 0.83%   |
| SK hynix HFM512GD3JX013N 512GB                      | 1         | 0.83%   |
| Silicon Motion PCIe-8 SSD 256GB                     | 1         | 0.83%   |
| Seagate ST9500325AS 500GB                           | 1         | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 35%     |
| WDC     | 4         | 4      | 20%     |
| Toshiba | 3         | 3      | 15%     |
| HGST    | 2         | 3      | 10%     |
| Hitachi | 1         | 1      | 5%      |
| Fujitsu | 1         | 1      | 5%      |
| ASMT    | 1         | 1      | 5%      |
| Apple   | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 10     | 18%     |
| Samsung Electronics | 7         | 8      | 14%     |
| Apple               | 7         | 7      | 14%     |
| Kingston            | 6         | 7      | 12%     |
| WDC                 | 4         | 5      | 8%      |
| Toshiba             | 4         | 6      | 8%      |
| SanDisk             | 4         | 4      | 8%      |
| China               | 2         | 2      | 4%      |
| SPCC                | 1         | 1      | 2%      |
| PNY                 | 1         | 1      | 2%      |
| OWC                 | 1         | 1      | 2%      |
| LITEON              | 1         | 1      | 2%      |
| JMicron Technology  | 1         | 1      | 2%      |
| Intenso             | 1         | 2      | 2%      |
| Inland              | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 46        | 57     | 41.07%  |
| NVMe    | 37        | 44     | 33.04%  |
| HDD     | 18        | 22     | 16.07%  |
| Unknown | 7         | 7      | 6.25%   |
| MMC     | 4         | 5      | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 63        | 77     | 56.25%  |
| NVMe | 37        | 44     | 33.04%  |
| SAS  | 8         | 9      | 7.14%   |
| MMC  | 4         | 5      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 54     | 67.16%  |
| 0.51-1.0   | 17        | 20     | 25.37%  |
| 1.01-2.0   | 5         | 5      | 7.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 45        | 45%     |
| 251-500        | 28        | 28%     |
| 501-1000       | 16        | 16%     |
| 51-100         | 6         | 6%      |
| 1001-2000      | 2         | 2%      |
| More than 3000 | 1         | 1%      |
| 2001-3000      | 1         | 1%      |
| 1-20           | 1         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 52        | 50.98%  |
| 21-50          | 22        | 21.57%  |
| 101-250        | 13        | 12.75%  |
| 51-100         | 10        | 9.8%    |
| 251-500        | 3         | 2.94%   |
| More than 3000 | 1         | 0.98%   |
| 1001-2000      | 1         | 0.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 85        | 120    | 85.86%  |
| Works    | 14        | 15     | 14.14%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 62        | 53.91%  |
| Samsung Electronics            | 14        | 12.17%  |
| AMD                            | 9         | 7.83%   |
| SanDisk                        | 7         | 6.09%   |
| Phison Electronics             | 4         | 3.48%   |
| Nvidia                         | 4         | 3.48%   |
| SK hynix                       | 2         | 1.74%   |
| Micron Technology              | 2         | 1.74%   |
| KIOXIA                         | 2         | 1.74%   |
| Union Memory (Shenzhen)        | 1         | 0.87%   |
| Toshiba America Info Systems   | 1         | 0.87%   |
| Solid State Storage Technology | 1         | 0.87%   |
| Silicon Motion                 | 1         | 0.87%   |
| Realtek Semiconductor          | 1         | 0.87%   |
| Marvell Technology Group       | 1         | 0.87%   |
| Kingston Technology Company    | 1         | 0.87%   |
| INNOGRIT                       | 1         | 0.87%   |
| Biwin Storage Technology       | 1         | 0.87%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 6.61%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 6.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 5.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 4.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 4.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 3.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 3.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.48%   |
| Phison E12 NVMe Controller                                                     | 3         | 2.48%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 2.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 2.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 2.48%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 1.65%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 1.65%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.65%   |
| Samsung Apple PCIe SSD                                                         | 2         | 1.65%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 1.65%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 1.65%   |
| Micron NVMe Storage Controller                                                 | 2         | 1.65%   |
| Intel SSD 660P Series                                                          | 2         | 1.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.65%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.83%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 0.83%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.83%   |
| Silicon Motion Non-Volatile memory controller                                  | 1         | 0.83%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.83%   |
| SanDisk NVMe Controller                                                        | 1         | 0.83%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.83%   |
| Samsung NVMe SSD Controller PM9B1                                              | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 68        | 56.67%  |
| NVMe | 37        | 30.83%  |
| RAID | 13        | 10.83%  |
| IDE  | 2         | 1.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 81        | 82.65%  |
| AMD    | 17        | 17.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 3.06%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 3         | 3.06%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 2         | 2.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 2.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 2.04%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 2         | 2.04%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 2.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 2.04%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 2.04%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 1         | 1.02%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 1.02%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 1.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 1.02%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 1.02%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 1.02%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 1.02%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 1.02%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 1.02%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz              | 1         | 1.02%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz              | 1         | 1.02%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz              | 1         | 1.02%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 1.02%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 1         | 1.02%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 1         | 1.02%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 1.02%   |
| Intel Core i7-3720QM CPU @ 2.60GHz              | 1         | 1.02%   |
| Intel Core i7-3632QM CPU @ 2.20GHz              | 1         | 1.02%   |
| Intel Core i7-2720QM CPU @ 2.20GHz              | 1         | 1.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 1.02%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 1         | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 1.02%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz              | 1         | 1.02%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 1.02%   |
| Intel Core i5-5250U CPU @ 1.60GHz               | 1         | 1.02%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 1.02%   |
| Intel Core i5-4300M CPU @ 2.60GHz               | 1         | 1.02%   |
| Intel Core i5-4278U CPU @ 2.60GHz               | 1         | 1.02%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 1.02%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 1         | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 25        | 25.51%  |
| Intel Core i7        | 20        | 20.41%  |
| Other                | 15        | 15.31%  |
| Intel Core 2 Duo     | 9         | 9.18%   |
| Intel Core i3        | 5         | 5.1%    |
| Intel Celeron        | 4         | 4.08%   |
| AMD Ryzen 7          | 4         | 4.08%   |
| AMD Ryzen 5          | 4         | 4.08%   |
| Intel Pentium        | 2         | 2.04%   |
| AMD A4               | 2         | 2.04%   |
| AMD A12              | 2         | 2.04%   |
| Intel Pentium Silver | 1         | 1.02%   |
| AMD Ryzen 5 PRO      | 1         | 1.02%   |
| AMD Ryzen 3          | 1         | 1.02%   |
| AMD Athlon           | 1         | 1.02%   |
| AMD A8               | 1         | 1.02%   |
| AMD A6               | 1         | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 48        | 48.98%  |
| 4      | 33        | 33.67%  |
| 8      | 6         | 6.12%   |
| 6      | 4         | 4.08%   |
| 10     | 2         | 2.04%   |
| 1      | 2         | 2.04%   |
| 14     | 1         | 1.02%   |
| 12     | 1         | 1.02%   |
| 5      | 1         | 1.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 98        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 75        | 76.53%  |
| 1      | 23        | 23.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 98        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 77.78%  |
| 0x806ec    | 3         | 3.03%   |
| 0x806c1    | 3         | 3.03%   |
| 0x906a4    | 2         | 2.02%   |
| 0x806d1    | 2         | 2.02%   |
| 0x0a50000c | 2         | 2.02%   |
| 0x906a3    | 1         | 1.01%   |
| 0x806eb    | 1         | 1.01%   |
| 0x806ea    | 1         | 1.01%   |
| 0x706e5    | 1         | 1.01%   |
| 0x40661    | 1         | 1.01%   |
| 0x40651    | 1         | 1.01%   |
| 0x1067a    | 1         | 1.01%   |
| 0x10676    | 1         | 1.01%   |
| 0x0a50000d | 1         | 1.01%   |
| 0x0600611a | 1         | 1.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 14        | 14.29%  |
| Haswell          | 12        | 12.24%  |
| TigerLake        | 9         | 9.18%   |
| Penryn           | 9         | 9.18%   |
| IvyBridge        | 8         | 8.16%   |
| Skylake          | 7         | 7.14%   |
| Zen+             | 4         | 4.08%   |
| SandyBridge      | 4         | 4.08%   |
| Unknown          | 4         | 4.08%   |
| Zen 3            | 3         | 3.06%   |
| Westmere         | 3         | 3.06%   |
| Silvermont       | 3         | 3.06%   |
| Excavator        | 3         | 3.06%   |
| Alderlake Hybrid | 3         | 3.06%   |
| Zen 2            | 2         | 2.04%   |
| Puma             | 2         | 2.04%   |
| Icelake          | 2         | 2.04%   |
| Goldmont plus    | 2         | 2.04%   |
| Broadwell        | 2         | 2.04%   |
| Piledriver       | 1         | 1.02%   |
| Core             | 1         | 1.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 72        | 58.54%  |
| Nvidia | 28        | 22.76%  |
| AMD    | 23        | 18.7%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 8         | 6.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 4.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 5         | 3.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 3.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 3.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 3.15%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 2.36%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 3         | 2.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 3         | 2.36%   |
| Intel HD Graphics 620                                                                 | 3         | 2.36%   |
| Intel HD Graphics 530                                                                 | 3         | 2.36%   |
| Intel Core Processor Integrated Graphics Controller                                   | 3         | 2.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 2.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 2.36%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 3         | 2.36%   |
| Nvidia MCP89 [GeForce 320M]                                                           | 2         | 1.57%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1.57%   |
| Nvidia C79 [GeForce 9400M]                                                            | 2         | 1.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 2         | 1.57%   |
| Intel UHD Graphics 620                                                                | 2         | 1.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 2         | 1.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 1.57%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 1.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 1.57%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 2         | 1.57%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.57%   |
| AMD Renoir                                                                            | 2         | 1.57%   |
| AMD Lucienne                                                                          | 2         | 1.57%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.79%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 0.79%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.79%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 1         | 0.79%   |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 1         | 0.79%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 1         | 0.79%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 0.79%   |
| Nvidia GM108GLM [Quadro M520 Mobile]                                                  | 1         | 0.79%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 0.79%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 1         | 0.79%   |
| Nvidia GM107M [GeForce GTX 860M]                                                      | 1         | 0.79%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 1         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 50%     |
| Intel + Nvidia | 19        | 19.39%  |
| 1 x AMD        | 15        | 15.31%  |
| 1 x Nvidia     | 6         | 6.12%   |
| Intel + AMD    | 4         | 4.08%   |
| 2 x AMD        | 2         | 2.04%   |
| AMD + Nvidia   | 2         | 2.04%   |
| 2 x Nvidia     | 1         | 1.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 93        | 94.9%   |
| Proprietary | 3         | 3.06%   |
| Unknown     | 2         | 2.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 94.9%   |
| 1.01-2.0   | 2         | 2.04%   |
| 0.01-0.5   | 2         | 2.04%   |
| 3.01-4.0   | 1         | 1.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 18        | 16.67%  |
| BOE                     | 16        | 14.81%  |
| AU Optronics            | 16        | 14.81%  |
| Chimei Innolux          | 13        | 12.04%  |
| Apple                   | 12        | 11.11%  |
| Samsung Electronics     | 8         | 7.41%   |
| Sharp                   | 3         | 2.78%   |
| PANDA                   | 3         | 2.78%   |
| Dell                    | 3         | 2.78%   |
| Lenovo                  | 2         | 1.85%   |
| Goldstar                | 2         | 1.85%   |
| Chi Mei Optoelectronics | 2         | 1.85%   |
| Toshiba                 | 1         | 0.93%   |
| Philips                 | 1         | 0.93%   |
| Panasonic               | 1         | 0.93%   |
| Mi                      | 1         | 0.93%   |
| LG Philips              | 1         | 0.93%   |
| InfoVision              | 1         | 0.93%   |
| Hewlett-Packard         | 1         | 0.93%   |
| CPT                     | 1         | 0.93%   |
| Cisco                   | 1         | 0.93%   |
| BenQ                    | 1         | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 2.75%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 2.75%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 1.83%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 1.83%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 2         | 1.83%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 1.83%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 1.83%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 1         | 0.92%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.92%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.92%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.92%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1         | 0.92%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 1         | 0.92%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.92%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 1         | 0.92%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.92%   |
| Panasonic TV MEIA296 3840x2160 708x398mm 32.0-inch                    | 1         | 0.92%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 1         | 0.92%   |
| LG Philips LCD Monitor LPLB900 1280x800 330x210mm 15.4-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x174mm 14.0-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD035C 1366x768 309x174mm 14.0-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD01DA 1366x768 294x166mm 13.3-inch           | 1         | 0.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 46        | 45.1%   |
| 1366x768 (WXGA)   | 28        | 27.45%  |
| 1280x800 (WXGA)   | 5         | 4.9%    |
| 3840x2160 (4K)    | 4         | 3.92%   |
| 1600x900 (HD+)    | 4         | 3.92%   |
| 2880x1800         | 3         | 2.94%   |
| 1920x1200 (WUXGA) | 3         | 2.94%   |
| 1440x900 (WXGA+)  | 3         | 2.94%   |
| 1280x1024 (SXGA)  | 2         | 1.96%   |
| 3840x2400         | 1         | 0.98%   |
| 3440x1440         | 1         | 0.98%   |
| 2560x1600         | 1         | 0.98%   |
| 2560x1440 (QHD)   | 1         | 0.98%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 45        | 41.28%  |
| 13      | 17        | 15.6%   |
| 14      | 15        | 13.76%  |
| 17      | 11        | 10.09%  |
| 27      | 3         | 2.75%   |
| 21      | 3         | 2.75%   |
| 24      | 2         | 1.83%   |
| 11      | 2         | 1.83%   |
| 84      | 1         | 0.92%   |
| 65      | 1         | 0.92%   |
| 60      | 1         | 0.92%   |
| 34      | 1         | 0.92%   |
| 31      | 1         | 0.92%   |
| 26      | 1         | 0.92%   |
| 19      | 1         | 0.92%   |
| 18      | 1         | 0.92%   |
| 16      | 1         | 0.92%   |
| 12      | 1         | 0.92%   |
| Unknown | 1         | 0.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 64        | 58.72%  |
| 201-300     | 15        | 13.76%  |
| 351-400     | 14        | 12.84%  |
| 501-600     | 6         | 5.5%    |
| 401-500     | 4         | 3.67%   |
| 1001-1500   | 2         | 1.83%   |
| 701-800     | 1         | 0.92%   |
| 601-700     | 1         | 0.92%   |
| 1501-2000   | 1         | 0.92%   |
| Unknown     | 1         | 0.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 79        | 79.8%   |
| 16/10   | 16        | 16.16%  |
| 5/4     | 1         | 1.01%   |
| 4/3     | 1         | 1.01%   |
| 21/9    | 1         | 1.01%   |
| Unknown | 1         | 1.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 46        | 42.59%  |
| 81-90          | 22        | 20.37%  |
| 71-80          | 10        | 9.26%   |
| 121-130        | 8         | 7.41%   |
| 301-350        | 4         | 3.7%    |
| More than 1000 | 3         | 2.78%   |
| 201-250        | 3         | 2.78%   |
| 131-140        | 3         | 2.78%   |
| 51-60          | 2         | 1.85%   |
| 351-500        | 2         | 1.85%   |
| 61-70          | 1         | 0.93%   |
| 251-300        | 1         | 0.93%   |
| 151-200        | 1         | 0.93%   |
| 141-150        | 1         | 0.93%   |
| Unknown        | 1         | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 50        | 47.17%  |
| 101-120       | 33        | 31.13%  |
| 51-100        | 11        | 10.38%  |
| 161-240       | 8         | 7.55%   |
| 1-50          | 2         | 1.89%   |
| More than 240 | 1         | 0.94%   |
| Unknown       | 1         | 0.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 82        | 83.67%  |
| 2     | 13        | 13.27%  |
| 0     | 2         | 2.04%   |
| 3     | 1         | 1.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 45        | 29.41%  |
| Realtek Semiconductor             | 44        | 28.76%  |
| Qualcomm Atheros                  | 19        | 12.42%  |
| Broadcom                          | 18        | 11.76%  |
| Broadcom Limited                  | 4         | 2.61%   |
| Samsung Electronics               | 2         | 1.31%   |
| Ralink Technology                 | 2         | 1.31%   |
| Qualcomm                          | 2         | 1.31%   |
| Nvidia                            | 2         | 1.31%   |
| NetGear                           | 2         | 1.31%   |
| Marvell Technology Group          | 2         | 1.31%   |
| Huawei Technologies               | 2         | 1.31%   |
| Ericsson Business Mobile Networks | 2         | 1.31%   |
| Dell                              | 2         | 1.31%   |
| ASIX Electronics                  | 2         | 1.31%   |
| Xiaomi                            | 1         | 0.65%   |
| Sierra Wireless                   | 1         | 0.65%   |
| Motorola PCS                      | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 14.74%  |
| Intel Wi-Fi 6 AX201                                               | 8         | 4.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 3.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 3.16%   |
| Intel Wireless 8260                                               | 5         | 2.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 2.11%   |
| Intel Wireless 7260                                               | 4         | 2.11%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.58%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.58%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 1.58%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.05%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 2         | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.05%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.05%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.05%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.05%   |
| Intel Wireless-AC 9260                                            | 2         | 1.05%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.05%   |
| Intel Wireless 7265                                               | 2         | 1.05%   |
| Intel Wireless 3165                                               | 2         | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.05%   |
| Intel Ultimate N WiFi Link 5300                                   | 2         | 1.05%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.05%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.05%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.05%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 2         | 1.05%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 1.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.05%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 44        | 42.72%  |
| Realtek Semiconductor | 18        | 17.48%  |
| Broadcom              | 17        | 16.5%   |
| Qualcomm Atheros      | 14        | 13.59%  |
| Broadcom Limited      | 3         | 2.91%   |
| Ralink Technology     | 2         | 1.94%   |
| Qualcomm              | 2         | 1.94%   |
| Sierra Wireless       | 1         | 0.97%   |
| NetGear               | 1         | 0.97%   |
| Dell                  | 1         | 0.97%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 8         | 7.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 6.8%    |
| Intel Wireless 8260                                            | 5         | 4.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 3.88%   |
| Intel Wireless 7260                                            | 4         | 3.88%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 3.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 2.91%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 2.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.91%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 2.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.94%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 2         | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.94%   |
| Intel Wireless-AC 9260                                         | 2         | 1.94%   |
| Intel Wireless 8265 / 8275                                     | 2         | 1.94%   |
| Intel Wireless 7265                                            | 2         | 1.94%   |
| Intel Wireless 3165                                            | 2         | 1.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.94%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 1.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.94%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 1.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 1.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 1.94%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.94%   |
| Sierra Wireless EM7455                                         | 1         | 0.97%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.97%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.97%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.97%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.97%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.97%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.97%   |
| Ralink RT2070 Wireless Adapter                                 | 1         | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 39        | 46.99%  |
| Intel                    | 18        | 21.69%  |
| Qualcomm Atheros         | 9         | 10.84%  |
| Broadcom                 | 4         | 4.82%   |
| Samsung Electronics      | 2         | 2.41%   |
| Nvidia                   | 2         | 2.41%   |
| Marvell Technology Group | 2         | 2.41%   |
| Huawei Technologies      | 2         | 2.41%   |
| ASIX Electronics         | 2         | 2.41%   |
| Xiaomi                   | 1         | 1.2%    |
| NetGear                  | 1         | 1.2%    |
| Broadcom Limited         | 1         | 1.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 33.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 7.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 4.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 2.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 2.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.41%   |
| Nvidia MCP79 Ethernet                                             | 2         | 2.41%   |
| Intel Ethernet Connection I219-V                                  | 2         | 2.41%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.41%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.41%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 2.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.2%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.2%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.2%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.2%    |
| NetGear LB1120-100NAS                                             | 1         | 1.2%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.2%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.2%    |
| Intel Ethernet Connection I217-V                                  | 1         | 1.2%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.2%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.2%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.2%    |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.2%    |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.2%    |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.2%    |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.2%    |
| Huawei E353/E3131                                                 | 1         | 1.2%    |
| Huawei ANE-LX1                                                    | 1         | 1.2%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.2%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.2%    |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 1         | 1.2%    |
| ASIX AX88772B                                                     | 1         | 1.2%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 55.06%  |
| Ethernet | 76        | 42.7%   |
| Modem    | 3         | 1.69%   |
| Unknown  | 1         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 76.53%  |
| Ethernet | 23        | 23.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 69        | 70.41%  |
| 1     | 27        | 27.55%  |
| 3     | 1         | 1.02%   |
| 0     | 1         | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 71        | 72.45%  |
| Yes  | 27        | 27.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 44.19%  |
| Realtek Semiconductor           | 13        | 15.12%  |
| Apple                           | 11        | 12.79%  |
| Qualcomm Atheros Communications | 7         | 8.14%   |
| Lite-On Technology              | 4         | 4.65%   |
| Foxconn / Hon Hai               | 4         | 4.65%   |
| IMC Networks                    | 3         | 3.49%   |
| Broadcom                        | 3         | 3.49%   |
| Toshiba                         | 1         | 1.16%   |
| Hewlett-Packard                 | 1         | 1.16%   |
| Askey Computer                  | 1         | 1.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 14        | 16.28%  |
| Intel AX201 Bluetooth                              | 11        | 12.79%  |
| Realtek  Bluetooth 4.2 Adapter                     | 8         | 9.3%    |
| Apple Bluetooth Host Controller                    | 6         | 6.98%   |
| Realtek Bluetooth Radio                            | 4         | 4.65%   |
| Apple Bluetooth USB Host Controller                | 4         | 4.65%   |
| Qualcomm Atheros  Bluetooth Device                 | 3         | 3.49%   |
| Intel Bluetooth Device                             | 3         | 3.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 3         | 3.49%   |
| Intel AX200 Bluetooth                              | 3         | 3.49%   |
| Foxconn / Hon Hai Bluetooth Device                 | 3         | 3.49%   |
| Qualcomm Atheros AR3011 Bluetooth                  | 2         | 2.33%   |
| Lite-On Bluetooth Device                           | 2         | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 2         | 2.33%   |
| Intel AX210 Bluetooth                              | 2         | 2.33%   |
| Toshiba Bluetooth Device                           | 1         | 1.16%   |
| Realtek RTL8821A Bluetooth                         | 1         | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 1.16%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device       | 1         | 1.16%   |
| IMC Networks Bluetooth Radio                       | 1         | 1.16%   |
| IMC Networks Bluetooth                             | 1         | 1.16%   |
| IMC Networks BCM20702A0                            | 1         | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 1.16%   |
| Foxconn / Hon Hai BCM43142A0                       | 1         | 1.16%   |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 1.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 1.16%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.16%   |
| Askey Bluetooth Device                             | 1         | 1.16%   |
| Apple Bluetooth HCI                                | 1         | 1.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 77        | 64.17%  |
| AMD                    | 21        | 17.5%   |
| Nvidia                 | 15        | 12.5%   |
| C-Media Electronics    | 2         | 1.67%   |
| Realtek Semiconductor  | 1         | 0.83%   |
| Logitech               | 1         | 0.83%   |
| Hewlett-Packard        | 1         | 0.83%   |
| GN Netcom              | 1         | 0.83%   |
| Generalplus Technology | 1         | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 7.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 6.08%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 6.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 5.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 4.73%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 4.05%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 3.38%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 3.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.7%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.7%    |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 2.7%    |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.03%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 2.03%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 1.35%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 1.35%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.35%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.35%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.35%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 1.35%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.68%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 40%     |
| SK hynix            | 6         | 24%     |
| Micron Technology   | 6         | 24%     |
| Ramaxel Technology  | 1         | 4%      |
| pqi                 | 1         | 4%      |
| GSkill              | 1         | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s    | 2         | 8%      |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                  | 1         | 4%      |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 4%      |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s        | 1         | 4%      |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s       | 1         | 4%      |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 4%      |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 4%      |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 4%      |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                  | 1         | 4%      |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 1         | 4%      |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s   | 1         | 4%      |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 4%      |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 4%      |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 1         | 4%      |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s  | 1         | 4%      |
| Ramaxel RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1         | 4%      |
| pqi RAM Module 2GB SODIMM DDR2 667MT/s                        | 1         | 4%      |
| Micron RAM MT53E1G32D2NP-046 8GB Row Of Chips LPDDR4 4267MT/s | 1         | 4%      |
| Micron RAM Module 8GB SODIMM DDR4 2667MT/s                    | 1         | 4%      |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 1         | 4%      |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s         | 1         | 4%      |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 1         | 4%      |
| Micron RAM 16ATF4G64HZ-3G2E2 32GB SODIMM DDR4 3200MT/s        | 1         | 4%      |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s         | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 56.52%  |
| LPDDR4 | 4         | 17.39%  |
| DDR3   | 3         | 13.04%  |
| LPDDR3 | 1         | 4.35%   |
| DDR5   | 1         | 4.35%   |
| DDR2   | 1         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 17        | 70.83%  |
| Row Of Chips | 7         | 29.17%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 14        | 58.33%  |
| 4096  | 4         | 16.67%  |
| 16384 | 3         | 12.5%   |
| 2048  | 2         | 8.33%   |
| 32768 | 1         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 8         | 34.78%  |
| 2667  | 6         | 26.09%  |
| 4267  | 4         | 17.39%  |
| 4800  | 1         | 4.35%   |
| 2133  | 1         | 4.35%   |
| 1600  | 1         | 4.35%   |
| 1333  | 1         | 4.35%   |
| 667   | 1         | 4.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| HP DeskJet 2600 series | 1         | 100%    |

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
| Chicony Electronics                    | 19        | 21.35%  |
| Quanta                                 | 11        | 12.36%  |
| IMC Networks                           | 9         | 10.11%  |
| Microdia                               | 8         | 8.99%   |
| Apple                                  | 8         | 8.99%   |
| Realtek Semiconductor                  | 7         | 7.87%   |
| Bison Electronics                      | 6         | 6.74%   |
| Sunplus Innovation Technology          | 3         | 3.37%   |
| Syntek                                 | 2         | 2.25%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.25%   |
| Suyin                                  | 1         | 1.12%   |
| SunplusIT                              | 1         | 1.12%   |
| Sunplus Technology                     | 1         | 1.12%   |
| Silicon Motion                         | 1         | 1.12%   |
| Samsung Electronics                    | 1         | 1.12%   |
| Luxvisions Innotech Limited            | 1         | 1.12%   |
| Logitech                               | 1         | 1.12%   |
| Lite-On Technology                     | 1         | 1.12%   |
| Lenovo                                 | 1         | 1.12%   |
| Intel                                  | 1         | 1.12%   |
| Cubeternet                             | 1         | 1.12%   |
| Cisco Systems                          | 1         | 1.12%   |
| Alcor Micro                            | 1         | 1.12%   |
| Acer                                   | 1         | 1.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 5         | 5.56%   |
| Realtek Integrated_Webcam_HD              | 3         | 3.33%   |
| Microdia Integrated_Webcam_HD             | 3         | 3.33%   |
| IMC Networks USB2.0 HD UVC WebCam         | 3         | 3.33%   |
| Quanta USB2.0 HD UVC WebCam               | 2         | 2.22%   |
| Quanta HP HD Camera                       | 2         | 2.22%   |
| Microdia Integrated Webcam                | 2         | 2.22%   |
| IMC Networks HD Camera                    | 2         | 2.22%   |
| Chicony HP TrueVision HD Camera           | 2         | 2.22%   |
| Chicony HP Truevision HD                  | 2         | 2.22%   |
| Bison Integrated Camera                   | 2         | 2.22%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X           | 2         | 2.22%   |
| Apple FaceTime HD Camera                  | 2         | 2.22%   |
| Apple FaceTime Camera                     | 2         | 2.22%   |
| Apple Built-in iSight                     | 2         | 2.22%   |
| Syntek Lenovo EasyCamera                  | 1         | 1.11%   |
| Syntek EasyCamera                         | 1         | 1.11%   |
| Suyin Acer HD Crystal Eye webcam          | 1         | 1.11%   |
| SunplusIT HD Camera                       | 1         | 1.11%   |
| Sunplus 1.3M HD WebCam                    | 1         | 1.11%   |
| Sunplus MTD Camera                        | 1         | 1.11%   |
| Sunplus HD WebCam                         | 1         | 1.11%   |
| Sunplus Dell E5570 integrated webcam      | 1         | 1.11%   |
| Silicon Motion WebCam SC-03FFL11939N      | 1         | 1.11%   |
| Samsung Galaxy series, misc. (MTP mode)   | 1         | 1.11%   |
| Realtek HP Webcam                         | 1         | 1.11%   |
| Realtek EasyCamera                        | 1         | 1.11%   |
| Realtek Acer 640 x 480 laptop camera      | 1         | 1.11%   |
| Realtek 2SF022                            | 1         | 1.11%   |
| Quanta VGA WebCam                         | 1         | 1.11%   |
| Quanta ov9734_techfront_camera            | 1         | 1.11%   |
| Quanta HP Wide Vision HD Camera           | 1         | 1.11%   |
| Quanta HP Webcam                          | 1         | 1.11%   |
| Quanta HP TrueVision HD Camera            | 1         | 1.11%   |
| Quanta HD Webcam                          | 1         | 1.11%   |
| Quanta HD Camera                          | 1         | 1.11%   |
| Microdia Webcam Vitade AF                 | 1         | 1.11%   |
| Microdia Integrated_Webcam_2M             | 1         | 1.11%   |
| Microdia CameraA                          | 1         | 1.11%   |
| Luxvisions Innotech Limited HP 5MP Camera | 1         | 1.11%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 33.33%  |
| Shenzhen Goodix Technology | 7         | 29.17%  |
| Synaptics                  | 4         | 16.67%  |
| Elan Microelectronics      | 3         | 12.5%   |
| Upek                       | 1         | 4.17%   |
| LighTuning Technology      | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 8.33%   |
| Elan ELAN:Fingerprint                                                      | 2         | 8.33%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 4.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 4.17%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 4.17%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 4.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 4.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 4.17%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 4.17%   |
| LighTuning Fingerprint Reader                                              | 1         | 4.17%   |
| Elan ELAN:ARM-M4                                                           | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 50%     |
| Upek        | 1         | 16.67%  |
| O2 Micro    | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 53        | 54.08%  |
| 1     | 38        | 38.78%  |
| 2     | 7         | 7.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 23        | 44.23%  |
| Net/wireless          | 8         | 15.38%  |
| Multimedia controller | 8         | 15.38%  |
| Chipcard              | 6         | 11.54%  |
| Graphics card         | 5         | 9.62%   |
| Storage               | 1         | 1.92%   |
| Net/ethernet          | 1         | 1.92%   |

