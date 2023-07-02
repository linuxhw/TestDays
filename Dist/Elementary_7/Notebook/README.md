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

Total: 159

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Laptop 17-by3xxx            | [8bfe14749f](https://linux-hardware.org/?probe=8bfe14749f) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430 2349OB6       | [f2f66bb9d0](https://linux-hardware.org/?probe=f2f66bb9d0) | Jun 29, 2023 |
| Dell          | Inspiron 3501               | [afc9f56d8d](https://linux-hardware.org/?probe=afc9f56d8d) | Jun 28, 2023 |
| Dell          | Latitude E5470              | [e10153b4c9](https://linux-hardware.org/?probe=e10153b4c9) | Jun 23, 2023 |
| Toshiba       | TECRA R850                  | [a75e6d35da](https://linux-hardware.org/?probe=a75e6d35da) | Jun 21, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [293b8783a3](https://linux-hardware.org/?probe=293b8783a3) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [2f452cfce0](https://linux-hardware.org/?probe=2f452cfce0) | Jun 20, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [f49534dfa4](https://linux-hardware.org/?probe=f49534dfa4) | Jun 19, 2023 |
| ASUSTek       | X555LA                      | [a57885e16c](https://linux-hardware.org/?probe=a57885e16c) | Jun 18, 2023 |
| ASUSTek       | X555LA                      | [782fa74afe](https://linux-hardware.org/?probe=782fa74afe) | Jun 14, 2023 |
| Razer         | Blade Stealth               | [f218e04a1c](https://linux-hardware.org/?probe=f218e04a1c) | Jun 14, 2023 |
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
| 5.15.0-58-generic    | 29        | 25.89%  |
| 5.19.0-41-generic    | 18        | 16.07%  |
| 5.19.0-35-generic    | 17        | 15.18%  |
| 5.19.0-32-generic    | 12        | 10.71%  |
| 5.19.0-38-generic    | 9         | 8.04%   |
| 5.19.0-43-generic    | 8         | 7.14%   |
| 5.19.0-40-generic    | 4         | 3.57%   |
| 5.15.0-60-generic    | 4         | 3.57%   |
| 5.19.0-46-generic    | 2         | 1.79%   |
| 5.19.0-45-generic    | 2         | 1.79%   |
| 5.19.0-42-generic    | 2         | 1.79%   |
| 6.2.7-060207-generic | 1         | 0.89%   |
| 6.1.9-060109-generic | 1         | 0.89%   |
| 6.1.6-060106-generic | 1         | 0.89%   |
| 6.1.0-1013-oem       | 1         | 0.89%   |
| 5.15.0-56-generic    | 1         | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.0  | 69        | 64.49%  |
| 5.15.0  | 34        | 31.78%  |
| 6.2.7   | 1         | 0.93%   |
| 6.1.9   | 1         | 0.93%   |
| 6.1.6   | 1         | 0.93%   |
| 6.1.0   | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19    | 69        | 64.49%  |
| 5.15    | 34        | 31.78%  |
| 6.1     | 3         | 2.8%    |
| 6.2     | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 105       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 105       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 105       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 83        | 79.05%  |
| LightDM | 22        | 20.95%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 45        | 42.86%  |
| de_DE | 18        | 17.14%  |
| ru_RU | 10        | 9.52%   |
| es_ES | 8         | 7.62%   |
| fr_FR | 4         | 3.81%   |
| en_GB | 4         | 3.81%   |
| pl_PL | 3         | 2.86%   |
| sv_SE | 2         | 1.9%    |
| it_IT | 2         | 1.9%    |
| uk_UA | 1         | 0.95%   |
| tr_TR | 1         | 0.95%   |
| pt_PT | 1         | 0.95%   |
| pt_BR | 1         | 0.95%   |
| nb_NO | 1         | 0.95%   |
| hu_HU | 1         | 0.95%   |
| en_AU | 1         | 0.95%   |
| el_GR | 1         | 0.95%   |
| da_DK | 1         | 0.95%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 89        | 84.76%  |
| EFI  | 16        | 15.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 100       | 94.34%  |
| Tmpfs   | 3         | 2.83%   |
| Xfs     | 1         | 0.94%   |
| Overlay | 1         | 0.94%   |
| Btrfs   | 1         | 0.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 83        | 79.05%  |
| GPT     | 19        | 18.1%   |
| MBR     | 3         | 2.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 99.05%  |
| Yes       | 1         | 0.95%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 92.38%  |
| Yes       | 8         | 7.62%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 20        | 19.05%  |
| Hewlett-Packard     | 20        | 19.05%  |
| Apple               | 12        | 11.43%  |
| Dell                | 11        | 10.48%  |
| ASUSTek Computer    | 10        | 9.52%   |
| Acer                | 7         | 6.67%   |
| MSI                 | 4         | 3.81%   |
| HUAWEI              | 4         | 3.81%   |
| Toshiba             | 3         | 2.86%   |
| Fujitsu             | 3         | 2.86%   |
| Sony                | 2         | 1.9%    |
| HONOR               | 2         | 1.9%    |
| Star Labs           | 1         | 0.95%   |
| Samsung Electronics | 1         | 0.95%   |
| Razer               | 1         | 0.95%   |
| PCBOX               | 1         | 0.95%   |
| GPU Company         | 1         | 0.95%   |
| Clevo               | 1         | 0.95%   |
| Alienware           | 1         | 0.95%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HUAWEI BOD-WXX9                            | 2         | 1.9%    |
| HP 255 G7 Notebook PC                      | 2         | 1.9%    |
| Toshiba TECRA Z40-C                        | 1         | 0.95%   |
| Toshiba TECRA R850                         | 1         | 0.95%   |
| Toshiba Satellite C660                     | 1         | 0.95%   |
| Star Labs StarBook                         | 1         | 0.95%   |
| Sony VPCEH2C5E                             | 1         | 0.95%   |
| Sony SVF1521O4E                            | 1         | 0.95%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.95%   |
| Razer Blade Stealth                        | 1         | 0.95%   |
| PCBOX Kant                                 | 1         | 0.95%   |
| MSI PE70 6QE                               | 1         | 0.95%   |
| MSI GT72 2QE                               | 1         | 0.95%   |
| MSI GE62VR 6RF                             | 1         | 0.95%   |
| MSI CX61 2PC                               | 1         | 0.95%   |
| Lenovo V14 G2 ITL 82KA                     | 1         | 0.95%   |
| Lenovo ThinkPad X240 20AMS0XP0S            | 1         | 0.95%   |
| Lenovo ThinkPad X230 23259S9               | 1         | 0.95%   |
| Lenovo ThinkPad X13 Gen 1 20T3S3SH0U       | 1         | 0.95%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW   | 1         | 0.95%   |
| Lenovo ThinkPad T495 20NKS01W02            | 1         | 0.95%   |
| Lenovo ThinkPad T460 20FMS08H00            | 1         | 0.95%   |
| Lenovo ThinkPad T440p 20AWS38H0G           | 1         | 0.95%   |
| Lenovo ThinkPad T430 2349OB6               | 1         | 0.95%   |
| Lenovo ThinkPad T400s 2808D9G              | 1         | 0.95%   |
| Lenovo ThinkPad P51s 20HB001TUS            | 1         | 0.95%   |
| Lenovo ThinkPad Edge E330 3354AHG          | 1         | 0.95%   |
| Lenovo ThinkPad E560 20EV003DSP            | 1         | 0.95%   |
| Lenovo ThinkBook 13s G3 ACN 20YA           | 1         | 0.95%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.95%   |
| Lenovo IdeaPad 320-15IKB 80XL              | 1         | 0.95%   |
| Lenovo IdeaPad 320-15ABR 80XS              | 1         | 0.95%   |
| Lenovo IdeaPad 3 15IGL05 81WQ              | 1         | 0.95%   |
| Lenovo IdeaPad 3 15ALC6 82KU               | 1         | 0.95%   |
| Lenovo G580 20150                          | 1         | 0.95%   |
| HUAWEI NBLB-WAX9N                          | 1         | 0.95%   |
| HUAWEI NBD-WXX9                            | 1         | 0.95%   |
| HONOR HYM-WXX                              | 1         | 0.95%   |
| HONOR BMH-WCX9                             | 1         | 0.95%   |
| HP ProBook 4540s                           | 1         | 0.95%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 12        | 11.43%  |
| Acer Aspire        | 7         | 6.67%   |
| HP ProBook         | 5         | 4.76%   |
| HP Pavilion        | 5         | 4.76%   |
| Dell Latitude      | 5         | 4.76%   |
| Lenovo IdeaPad     | 4         | 3.81%   |
| ASUS ZenBook       | 4         | 3.81%   |
| HP Laptop          | 3         | 2.86%   |
| Fujitsu LIFEBOOK   | 3         | 2.86%   |
| Apple MacBookPro11 | 3         | 2.86%   |
| Toshiba TECRA      | 2         | 1.9%    |
| HUAWEI BOD-WXX9    | 2         | 1.9%    |
| HP 255             | 2         | 1.9%    |
| Dell XPS           | 2         | 1.9%    |
| ASUS VivoBook      | 2         | 1.9%    |
| Apple MacBookPro5  | 2         | 1.9%    |
| Apple MacBookAir3  | 2         | 1.9%    |
| Toshiba Satellite  | 1         | 0.95%   |
| Star Labs StarBook | 1         | 0.95%   |
| Sony VPCEH2C5E     | 1         | 0.95%   |
| Sony SVF1521O4E    | 1         | 0.95%   |
| Samsung 300E4A     | 1         | 0.95%   |
| Razer Blade        | 1         | 0.95%   |
| PCBOX Kant         | 1         | 0.95%   |
| MSI PE70           | 1         | 0.95%   |
| MSI GT72           | 1         | 0.95%   |
| MSI GE62VR         | 1         | 0.95%   |
| MSI CX61           | 1         | 0.95%   |
| Lenovo V14         | 1         | 0.95%   |
| Lenovo ThinkBook   | 1         | 0.95%   |
| Lenovo Legion      | 1         | 0.95%   |
| Lenovo G580        | 1         | 0.95%   |
| HUAWEI NBLB-WAX9N  | 1         | 0.95%   |
| HUAWEI NBD-WXX9    | 1         | 0.95%   |
| HONOR HYM-WXX      | 1         | 0.95%   |
| HONOR BMH-WCX9     | 1         | 0.95%   |
| HP OMEN            | 1         | 0.95%   |
| HP G62             | 1         | 0.95%   |
| HP EliteBook       | 1         | 0.95%   |
| HP 550             | 1         | 0.95%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 12        | 11.43%  |
| 2021 | 10        | 9.52%   |
| 2012 | 10        | 9.52%   |
| 2019 | 9         | 8.57%   |
| 2014 | 9         | 8.57%   |
| 2016 | 8         | 7.62%   |
| 2022 | 7         | 6.67%   |
| 2015 | 7         | 6.67%   |
| 2018 | 6         | 5.71%   |
| 2013 | 5         | 4.76%   |
| 2010 | 5         | 4.76%   |
| 2009 | 5         | 4.76%   |
| 2017 | 4         | 3.81%   |
| 2011 | 4         | 3.81%   |
| 2008 | 3         | 2.86%   |
| 2023 | 1         | 0.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 105       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 99        | 94.29%  |
| Enabled  | 6         | 5.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 104       | 99.05%  |
| Yes  | 1         | 0.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 35        | 33.33%  |
| 8.01-16.0   | 22        | 20.95%  |
| 16.01-24.0  | 20        | 19.05%  |
| 3.01-4.0    | 17        | 16.19%  |
| 32.01-64.0  | 7         | 6.67%   |
| 1.01-2.0    | 2         | 1.9%    |
| 2.01-3.0    | 1         | 0.95%   |
| 64.01-256.0 | 1         | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 52        | 46.43%  |
| 3.01-4.0  | 22        | 19.64%  |
| 1.01-2.0  | 22        | 19.64%  |
| 4.01-8.0  | 14        | 12.5%   |
| 8.01-16.0 | 1         | 0.89%   |
| 0.51-1.0  | 1         | 0.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 77.36%  |
| 2      | 23        | 21.7%   |
| 4      | 1         | 0.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 64.76%  |
| Yes       | 37        | 35.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 77.14%  |
| No        | 24        | 22.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 86.67%  |
| No        | 14        | 13.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 21        | 20%     |
| USA          | 19        | 18.1%   |
| Russia       | 9         | 8.57%   |
| Poland       | 5         | 4.76%   |
| UK           | 4         | 3.81%   |
| France       | 4         | 3.81%   |
| Thailand     | 2         | 1.9%    |
| Spain        | 2         | 1.9%    |
| Portugal     | 2         | 1.9%    |
| Norway       | 2         | 1.9%    |
| Netherlands  | 2         | 1.9%    |
| Mexico       | 2         | 1.9%    |
| Italy        | 2         | 1.9%    |
| Israel       | 2         | 1.9%    |
| India        | 2         | 1.9%    |
| Australia    | 2         | 1.9%    |
| Turkey       | 1         | 0.95%   |
| Tunisia      | 1         | 0.95%   |
| Sweden       | 1         | 0.95%   |
| South Africa | 1         | 0.95%   |
| Saudi Arabia | 1         | 0.95%   |
| Puerto Rico  | 1         | 0.95%   |
| Kazakhstan   | 1         | 0.95%   |
| Ireland      | 1         | 0.95%   |
| Indonesia    | 1         | 0.95%   |
| Hungary      | 1         | 0.95%   |
| Greece       | 1         | 0.95%   |
| Georgia      | 1         | 0.95%   |
| Ecuador      | 1         | 0.95%   |
| Denmark      | 1         | 0.95%   |
| Cyprus       | 1         | 0.95%   |
| Colombia     | 1         | 0.95%   |
| China        | 1         | 0.95%   |
| Canada       | 1         | 0.95%   |
| Brazil       | 1         | 0.95%   |
| Belgium      | 1         | 0.95%   |
| Austria      | 1         | 0.95%   |
| Argentina    | 1         | 0.95%   |
| Albania      | 1         | 0.95%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 4         | 3.67%   |
| Berlin                  | 3         | 2.75%   |
| Warsaw                  | 2         | 1.83%   |
| Stuttgart               | 2         | 1.83%   |
| Bangkok                 | 2         | 1.83%   |
| Zhuantang               | 1         | 0.92%   |
| Worcestershire          | 1         | 0.92%   |
| Wiesbaden               | 1         | 0.92%   |
| Villefranche-sur-Saône | 1         | 0.92%   |
| Vigo                    | 1         | 0.92%   |
| Vienna                  | 1         | 0.92%   |
| Twickenham              | 1         | 0.92%   |
| Tuam                    | 1         | 0.92%   |
| Tromsø                 | 1         | 0.92%   |
| Troisdorf               | 1         | 0.92%   |
| Torres Vedras           | 1         | 0.92%   |
| Tirana                  | 1         | 0.92%   |
| Tel Aviv                | 1         | 0.92%   |
| Tbilisi                 | 1         | 0.92%   |
| Stockholm               | 1         | 0.92%   |
| St Petersburg           | 1         | 0.92%   |
| Spaichingen             | 1         | 0.92%   |
| Slavyansk-na-Kubani     | 1         | 0.92%   |
| Sfax                    | 1         | 0.92%   |
| Sarasota                | 1         | 0.92%   |
| San Juan                | 1         | 0.92%   |
| Salzgitter              | 1         | 0.92%   |
| Rostov-on-Don           | 1         | 0.92%   |
| Roosendaal              | 1         | 0.92%   |
| Portimao                | 1         | 0.92%   |
| Perth                   | 1         | 0.92%   |
| Pécs                   | 1         | 0.92%   |
| Odessa                  | 1         | 0.92%   |
| Oaxaca City             | 1         | 0.92%   |
| Nuremberg               | 1         | 0.92%   |
| Novosibirsk             | 1         | 0.92%   |
| Nicosia                 | 1         | 0.92%   |
| Newcastle upon Tyne     | 1         | 0.92%   |
| Munich                  | 1         | 0.92%   |
| Mundelein               | 1         | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 19        | 20     | 14.73%  |
| WDC                            | 12        | 13     | 9.3%    |
| Sandisk                        | 10        | 11     | 7.75%   |
| Crucial                        | 10        | 11     | 7.75%   |
| Toshiba                        | 8         | 10     | 6.2%    |
| Seagate                        | 8         | 9      | 6.2%    |
| Apple                          | 8         | 8      | 6.2%    |
| Unknown                        | 6         | 7      | 4.65%   |
| Kingston                       | 6         | 8      | 4.65%   |
| Phison Electronics             | 3         | 3      | 2.33%   |
| Intel                          | 3         | 4      | 2.33%   |
| SK hynix                       | 2         | 3      | 1.55%   |
| Micron Technology              | 2         | 2      | 1.55%   |
| KIOXIA                         | 2         | 4      | 1.55%   |
| JMicron Technology             | 2         | 2      | 1.55%   |
| Intenso                        | 2         | 3      | 1.55%   |
| Hitachi                        | 2         | 2      | 1.55%   |
| HGST                           | 2         | 3      | 1.55%   |
| China                          | 2         | 2      | 1.55%   |
| USB 3.0                        | 1         | 1      | 0.78%   |
| Union Memory                   | 1         | 2      | 0.78%   |
| T-FORCE                        | 1         | 1      | 0.78%   |
| Star Drive                     | 1         | 1      | 0.78%   |
| SPCC                           | 1         | 1      | 0.78%   |
| Solid State Storage Technology | 1         | 1      | 0.78%   |
| Solid State Storage            | 1         | 1      | 0.78%   |
| Silicon Motion                 | 1         | 1      | 0.78%   |
| Realtek Semiconductor          | 1         | 2      | 0.78%   |
| PNY                            | 1         | 1      | 0.78%   |
| OWC                            | 1         | 1      | 0.78%   |
| LITEON                         | 1         | 1      | 0.78%   |
| Kingston Technology Company    | 1         | 1      | 0.78%   |
| JetFlash                       | 1         | 1      | 0.78%   |
| Inland                         | 1         | 1      | 0.78%   |
| GeIL                           | 1         | 1      | 0.78%   |
| Fujitsu                        | 1         | 1      | 0.78%   |
| Biwin Storage Technology       | 1         | 1      | 0.78%   |
| BIWIN                          | 1         | 1      | 0.78%   |
| ASMT                           | 1         | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 3         | 2.29%   |
| Phison E12 NVMe Controller 1TB                      | 3         | 2.29%   |
| Unknown MMC Card  7GB                               | 2         | 1.53%   |
| Unknown MMC Card  32GB                              | 2         | 1.53%   |
| Seagate Expansion 1TB                               | 2         | 1.53%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 2         | 1.53%   |
| SanDisk SDSSDA240G 240GB                            | 2         | 1.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 2         | 1.53%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1.53%   |
| HGST HTS721010A9E630 1TB                            | 2         | 1.53%   |
| Crucial CT250MX500SSD1 250GB                        | 2         | 1.53%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 1.53%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 1.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.76%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.76%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 0.76%   |
| WDC WD5000LPVX-80V0TT0 500GB                        | 1         | 0.76%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 0.76%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 0.76%   |
| WDC WD10SPCX-08S8TT0 1TB                            | 1         | 0.76%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.76%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 1         | 0.76%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB                | 1         | 0.76%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                | 1         | 0.76%   |
| USB 3.0 Device 250GB                                | 1         | 0.76%   |
| Unknown SE64G  64GB                                 | 1         | 0.76%   |
| Unknown MMC Card  128GB                             | 1         | 0.76%   |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB             | 1         | 0.76%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 1         | 0.76%   |
| Toshiba THNSNJ128GCSU 128GB SSD                     | 1         | 0.76%   |
| Toshiba THNSNJ128G8NU 128GB SSD                     | 1         | 0.76%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD             | 1         | 0.76%   |
| Toshiba NVMe Controller 256GB                       | 1         | 0.76%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 0.76%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.76%   |
| Toshiba MK3256GSY 320GB                             | 1         | 0.76%   |
| T-FORCE 2TB                                         | 1         | 0.76%   |
| Star Drive PCIe SSD 480GB                           | 1         | 0.76%   |
| SPCC Solid State Disk 512GB                         | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 31.82%  |
| WDC     | 5         | 5      | 22.73%  |
| Toshiba | 3         | 3      | 13.64%  |
| Hitachi | 2         | 2      | 9.09%   |
| HGST    | 2         | 3      | 9.09%   |
| Fujitsu | 1         | 1      | 4.55%   |
| ASMT    | 1         | 1      | 4.55%   |
| Apple   | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 10        | 11     | 19.23%  |
| Samsung Electronics | 7         | 8      | 13.46%  |
| Apple               | 7         | 7      | 13.46%  |
| Kingston            | 6         | 8      | 11.54%  |
| SanDisk             | 5         | 5      | 9.62%   |
| WDC                 | 4         | 5      | 7.69%   |
| Toshiba             | 4         | 6      | 7.69%   |
| China               | 2         | 2      | 3.85%   |
| SPCC                | 1         | 1      | 1.92%   |
| PNY                 | 1         | 1      | 1.92%   |
| OWC                 | 1         | 1      | 1.92%   |
| LITEON              | 1         | 1      | 1.92%   |
| Intenso             | 1         | 2      | 1.92%   |
| Intel               | 1         | 1      | 1.92%   |
| Inland              | 1         | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 48        | 60     | 39.34%  |
| NVMe    | 41        | 49     | 33.61%  |
| HDD     | 20        | 24     | 16.39%  |
| Unknown | 7         | 7      | 5.74%   |
| MMC     | 6         | 7      | 4.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 67        | 83     | 55.37%  |
| NVMe | 40        | 48     | 33.06%  |
| SAS  | 8         | 9      | 6.61%   |
| MMC  | 6         | 7      | 4.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 56     | 67.61%  |
| 0.51-1.0   | 18        | 23     | 25.35%  |
| 1.01-2.0   | 5         | 5      | 7.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 49        | 45.79%  |
| 251-500        | 29        | 27.1%   |
| 501-1000       | 17        | 15.89%  |
| 51-100         | 7         | 6.54%   |
| 1001-2000      | 2         | 1.87%   |
| More than 3000 | 1         | 0.93%   |
| 2001-3000      | 1         | 0.93%   |
| 1-20           | 1         | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 55        | 50.46%  |
| 21-50          | 25        | 22.94%  |
| 101-250        | 14        | 12.84%  |
| 51-100         | 10        | 9.17%   |
| 251-500        | 3         | 2.75%   |
| More than 3000 | 1         | 0.92%   |
| 1001-2000      | 1         | 0.92%   |

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
| Detected | 92        | 130    | 85.98%  |
| Works    | 15        | 17     | 14.02%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 68        | 54.84%  |
| Samsung Electronics            | 15        | 12.1%   |
| AMD                            | 9         | 7.26%   |
| SanDisk                        | 8         | 6.45%   |
| Phison Electronics             | 4         | 3.23%   |
| Nvidia                         | 4         | 3.23%   |
| Solid State Storage Technology | 2         | 1.61%   |
| SK hynix                       | 2         | 1.61%   |
| Micron Technology              | 2         | 1.61%   |
| KIOXIA                         | 2         | 1.61%   |
| Union Memory (Shenzhen)        | 1         | 0.81%   |
| Toshiba America Info Systems   | 1         | 0.81%   |
| Silicon Motion                 | 1         | 0.81%   |
| Realtek Semiconductor          | 1         | 0.81%   |
| Marvell Technology Group       | 1         | 0.81%   |
| Kingston Technology Company    | 1         | 0.81%   |
| INNOGRIT                       | 1         | 0.81%   |
| Biwin Storage Technology       | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 6.15%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 5.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 4.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 3.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.31%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 2.31%   |
| Phison E12 NVMe Controller                                                     | 3         | 2.31%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 2.31%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 2.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 2.31%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 1.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 1.54%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 1.54%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.54%   |
| Samsung Apple PCIe SSD                                                         | 2         | 1.54%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 1.54%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 1.54%   |
| Micron NVMe Storage Controller                                                 | 2         | 1.54%   |
| Intel SSD 660P Series                                                          | 2         | 1.54%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.54%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.77%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 0.77%   |
| Silicon Motion Non-Volatile memory controller                                  | 1         | 0.77%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.77%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.77%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.77%   |
| SanDisk PC SN530 NVMe SSD                                                      | 1         | 0.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.77%   |
| Samsung NVMe SSD Controller PM9B1                                              | 1         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 74        | 57.36%  |
| NVMe | 40        | 31.01%  |
| RAID | 13        | 10.08%  |
| IDE  | 2         | 1.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 88        | 83.81%  |
| AMD    | 17        | 16.19%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 2.86%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 3         | 2.86%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 2         | 1.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 1.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz               | 2         | 1.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz               | 2         | 1.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 1.9%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 2         | 1.9%    |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 1.9%    |
| Intel Celeron N4020 CPU @ 1.10GHz               | 2         | 1.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.9%    |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 1.9%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 1         | 0.95%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 0.95%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 0.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.95%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 0.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 0.95%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 0.95%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 0.95%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 0.95%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.95%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz              | 1         | 0.95%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz              | 1         | 0.95%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz              | 1         | 0.95%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 0.95%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 1         | 0.95%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 1         | 0.95%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 0.95%   |
| Intel Core i7-3720QM CPU @ 2.60GHz              | 1         | 0.95%   |
| Intel Core i7-3632QM CPU @ 2.20GHz              | 1         | 0.95%   |
| Intel Core i7-2720QM CPU @ 2.20GHz              | 1         | 0.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 0.95%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 1         | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 0.95%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz              | 1         | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 0.95%   |
| Intel Core i5-5250U CPU @ 1.60GHz               | 1         | 0.95%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 30        | 28.57%  |
| Intel Core i7        | 21        | 20%     |
| Other                | 15        | 14.29%  |
| Intel Core 2 Duo     | 9         | 8.57%   |
| Intel Core i3        | 5         | 4.76%   |
| Intel Celeron        | 5         | 4.76%   |
| AMD Ryzen 7          | 4         | 3.81%   |
| AMD Ryzen 5          | 4         | 3.81%   |
| Intel Pentium        | 2         | 1.9%    |
| AMD A4               | 2         | 1.9%    |
| AMD A12              | 2         | 1.9%    |
| Intel Pentium Silver | 1         | 0.95%   |
| AMD Ryzen 5 PRO      | 1         | 0.95%   |
| AMD Ryzen 3          | 1         | 0.95%   |
| AMD Athlon           | 1         | 0.95%   |
| AMD A8               | 1         | 0.95%   |
| AMD A6               | 1         | 0.95%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 53        | 50.48%  |
| 4      | 35        | 33.33%  |
| 8      | 6         | 5.71%   |
| 6      | 4         | 3.81%   |
| 10     | 2         | 1.9%    |
| 1      | 2         | 1.9%    |
| 14     | 1         | 0.95%   |
| 12     | 1         | 0.95%   |
| 5      | 1         | 0.95%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 105       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 81        | 77.14%  |
| 1      | 24        | 22.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 105       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 77.36%  |
| 0x806ec    | 3         | 2.83%   |
| 0x806c1    | 3         | 2.83%   |
| 0x906a4    | 2         | 1.89%   |
| 0x806d1    | 2         | 1.89%   |
| 0x0a50000c | 2         | 1.89%   |
| 0x906a3    | 1         | 0.94%   |
| 0x806eb    | 1         | 0.94%   |
| 0x806ea    | 1         | 0.94%   |
| 0x706e5    | 1         | 0.94%   |
| 0x706a8    | 1         | 0.94%   |
| 0x40661    | 1         | 0.94%   |
| 0x40651    | 1         | 0.94%   |
| 0x206a7    | 1         | 0.94%   |
| 0x1067a    | 1         | 0.94%   |
| 0x10676    | 1         | 0.94%   |
| 0x0a50000d | 1         | 0.94%   |
| 0x0600611a | 1         | 0.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 15        | 14.29%  |
| Haswell          | 13        | 12.38%  |
| IvyBridge        | 10        | 9.52%   |
| TigerLake        | 9         | 8.57%   |
| Penryn           | 9         | 8.57%   |
| Skylake          | 7         | 6.67%   |
| SandyBridge      | 5         | 4.76%   |
| Zen+             | 4         | 3.81%   |
| Unknown          | 4         | 3.81%   |
| Zen 3            | 3         | 2.86%   |
| Westmere         | 3         | 2.86%   |
| Silvermont       | 3         | 2.86%   |
| IceLake          | 3         | 2.86%   |
| Goldmont plus    | 3         | 2.86%   |
| Excavator        | 3         | 2.86%   |
| Alderlake Hybrid | 3         | 2.86%   |
| Zen 2            | 2         | 1.9%    |
| Puma             | 2         | 1.9%    |
| Broadwell        | 2         | 1.9%    |
| Piledriver       | 1         | 0.95%   |
| Core             | 1         | 0.95%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 79        | 60.31%  |
| Nvidia | 29        | 22.14%  |
| AMD    | 23        | 17.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 10        | 7.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 4.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 6         | 4.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 2.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 2.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 2.96%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 3         | 2.22%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 3         | 2.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 3         | 2.22%   |
| Intel HD Graphics 620                                                                 | 3         | 2.22%   |
| Intel HD Graphics 530                                                                 | 3         | 2.22%   |
| Intel Core Processor Integrated Graphics Controller                                   | 3         | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 2.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 2.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 2.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 3         | 2.22%   |
| Nvidia MCP89 [GeForce 320M]                                                           | 2         | 1.48%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1.48%   |
| Nvidia C79 [GeForce 9400M]                                                            | 2         | 1.48%   |
| Intel UHD Graphics 620                                                                | 2         | 1.48%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 2         | 1.48%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 2         | 1.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 1.48%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 1.48%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 2         | 1.48%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.48%   |
| AMD Renoir                                                                            | 2         | 1.48%   |
| AMD Lucienne                                                                          | 2         | 1.48%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.74%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 0.74%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 0.74%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.74%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 1         | 0.74%   |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 1         | 0.74%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 1         | 0.74%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 0.74%   |
| Nvidia GM108GLM [Quadro M520 Mobile]                                                  | 1         | 0.74%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 52.38%  |
| Intel + Nvidia | 20        | 19.05%  |
| 1 x AMD        | 15        | 14.29%  |
| 1 x Nvidia     | 6         | 5.71%   |
| Intel + AMD    | 4         | 3.81%   |
| 2 x AMD        | 2         | 1.9%    |
| AMD + Nvidia   | 2         | 1.9%    |
| 2 x Nvidia     | 1         | 0.95%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 100       | 95.24%  |
| Proprietary | 3         | 2.86%   |
| Unknown     | 2         | 1.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 95.24%  |
| 1.01-2.0   | 2         | 1.9%    |
| 0.01-0.5   | 2         | 1.9%    |
| 3.01-4.0   | 1         | 0.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 21        | 18.42%  |
| BOE                     | 17        | 14.91%  |
| AU Optronics            | 17        | 14.91%  |
| Chimei Innolux          | 13        | 11.4%   |
| Apple                   | 12        | 10.53%  |
| Samsung Electronics     | 8         | 7.02%   |
| Sharp                   | 4         | 3.51%   |
| PANDA                   | 3         | 2.63%   |
| Dell                    | 3         | 2.63%   |
| Lenovo                  | 2         | 1.75%   |
| Goldstar                | 2         | 1.75%   |
| Chi Mei Optoelectronics | 2         | 1.75%   |
| Toshiba                 | 1         | 0.88%   |
| Philips                 | 1         | 0.88%   |
| Panasonic               | 1         | 0.88%   |
| Mi                      | 1         | 0.88%   |
| LG Philips              | 1         | 0.88%   |
| InfoVision              | 1         | 0.88%   |
| Hewlett-Packard         | 1         | 0.88%   |
| CPT                     | 1         | 0.88%   |
| Cisco                   | 1         | 0.88%   |
| BenQ                    | 1         | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 2.61%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 2.61%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 1.74%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 1.74%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 2         | 1.74%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 1.74%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 1.74%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 1         | 0.87%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.87%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.87%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.87%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.87%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1         | 0.87%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 1         | 0.87%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.87%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 1         | 0.87%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.87%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 1         | 0.87%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 1         | 0.87%   |
| LG Philips LCD Monitor LPLB900 1280x800 330x210mm 15.4-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x174mm 14.0-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD035C 1366x768 309x174mm 14.0-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD0354 1366x768 293x165mm 13.2-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 1         | 0.87%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 49        | 45.37%  |
| 1366x768 (WXGA)   | 31        | 28.7%   |
| 1280x800 (WXGA)   | 5         | 4.63%   |
| 3840x2160 (4K)    | 4         | 3.7%    |
| 1600x900 (HD+)    | 4         | 3.7%    |
| 2880x1800         | 3         | 2.78%   |
| 1920x1200 (WUXGA) | 3         | 2.78%   |
| 1440x900 (WXGA+)  | 3         | 2.78%   |
| 1280x1024 (SXGA)  | 2         | 1.85%   |
| 3840x2400         | 1         | 0.93%   |
| 3440x1440         | 1         | 0.93%   |
| 2560x1600         | 1         | 0.93%   |
| 2560x1440 (QHD)   | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 48        | 41.74%  |
| 13      | 19        | 16.52%  |
| 14      | 16        | 13.91%  |
| 17      | 11        | 9.57%   |
| 27      | 3         | 2.61%   |
| 21      | 3         | 2.61%   |
| 24      | 2         | 1.74%   |
| 11      | 2         | 1.74%   |
| 84      | 1         | 0.87%   |
| 65      | 1         | 0.87%   |
| 60      | 1         | 0.87%   |
| 34      | 1         | 0.87%   |
| 31      | 1         | 0.87%   |
| 26      | 1         | 0.87%   |
| 19      | 1         | 0.87%   |
| 18      | 1         | 0.87%   |
| 16      | 1         | 0.87%   |
| 12      | 1         | 0.87%   |
| Unknown | 1         | 0.87%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 59.13%  |
| 201-300     | 17        | 14.78%  |
| 351-400     | 14        | 12.17%  |
| 501-600     | 6         | 5.22%   |
| 401-500     | 4         | 3.48%   |
| 1001-1500   | 2         | 1.74%   |
| 701-800     | 1         | 0.87%   |
| 601-700     | 1         | 0.87%   |
| 1501-2000   | 1         | 0.87%   |
| Unknown     | 1         | 0.87%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 85        | 80.95%  |
| 16/10   | 16        | 15.24%  |
| 5/4     | 1         | 0.95%   |
| 4/3     | 1         | 0.95%   |
| 21/9    | 1         | 0.95%   |
| Unknown | 1         | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 49        | 42.98%  |
| 81-90          | 23        | 20.18%  |
| 71-80          | 12        | 10.53%  |
| 121-130        | 8         | 7.02%   |
| 301-350        | 4         | 3.51%   |
| More than 1000 | 3         | 2.63%   |
| 201-250        | 3         | 2.63%   |
| 131-140        | 3         | 2.63%   |
| 51-60          | 2         | 1.75%   |
| 351-500        | 2         | 1.75%   |
| 61-70          | 1         | 0.88%   |
| 251-300        | 1         | 0.88%   |
| 151-200        | 1         | 0.88%   |
| 141-150        | 1         | 0.88%   |
| Unknown        | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 52        | 46.43%  |
| 101-120       | 35        | 31.25%  |
| 51-100        | 12        | 10.71%  |
| 161-240       | 9         | 8.04%   |
| 1-50          | 2         | 1.79%   |
| More than 240 | 1         | 0.89%   |
| Unknown       | 1         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 89        | 84.76%  |
| 2     | 13        | 12.38%  |
| 0     | 2         | 1.9%    |
| 3     | 1         | 0.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 50        | 30.49%  |
| Realtek Semiconductor             | 47        | 28.66%  |
| Qualcomm Atheros                  | 21        | 12.8%   |
| Broadcom                          | 18        | 10.98%  |
| Broadcom Limited                  | 4         | 2.44%   |
| Samsung Electronics               | 2         | 1.22%   |
| Ralink Technology                 | 2         | 1.22%   |
| Qualcomm                          | 2         | 1.22%   |
| Nvidia                            | 2         | 1.22%   |
| NetGear                           | 2         | 1.22%   |
| Marvell Technology Group          | 2         | 1.22%   |
| Huawei Technologies               | 2         | 1.22%   |
| Ericsson Business Mobile Networks | 2         | 1.22%   |
| Dell                              | 2         | 1.22%   |
| ASIX Electronics                  | 2         | 1.22%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.61%   |
| Xiaomi                            | 1         | 0.61%   |
| Sierra Wireless                   | 1         | 0.61%   |
| Motorola PCS                      | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 14.85%  |
| Intel Wi-Fi 6 AX201                                               | 8         | 3.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 3.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 2.97%   |
| Intel Wireless 8260                                               | 5         | 2.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.98%   |
| Intel Wireless 7260                                               | 4         | 1.98%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.49%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.49%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 1.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.99%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 2         | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.99%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.99%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.99%   |
| Intel Wireless-AC 9260                                            | 2         | 0.99%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.99%   |
| Intel Wireless 7265                                               | 2         | 0.99%   |
| Intel Wireless 3165                                               | 2         | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.99%   |
| Intel Ultimate N WiFi Link 5300                                   | 2         | 0.99%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.99%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.99%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.99%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 2         | 0.99%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 43.64%  |
| Realtek Semiconductor | 19        | 17.27%  |
| Broadcom              | 17        | 15.45%  |
| Qualcomm Atheros      | 16        | 14.55%  |
| Broadcom Limited      | 3         | 2.73%   |
| Ralink Technology     | 2         | 1.82%   |
| Qualcomm              | 2         | 1.82%   |
| Sierra Wireless       | 1         | 0.91%   |
| NetGear               | 1         | 0.91%   |
| Dell                  | 1         | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 8         | 7.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 6.36%   |
| Intel Wireless 8260                                            | 5         | 4.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 3.64%   |
| Intel Wireless 7260                                            | 4         | 3.64%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 3.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 2.73%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 2.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.73%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.82%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 2         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.82%   |
| Intel Wireless-AC 9260                                         | 2         | 1.82%   |
| Intel Wireless 8265 / 8275                                     | 2         | 1.82%   |
| Intel Wireless 7265                                            | 2         | 1.82%   |
| Intel Wireless 3165                                            | 2         | 1.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.82%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 1.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.82%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 1.82%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 1.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 1.82%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.82%   |
| Sierra Wireless EM7455                                         | 1         | 0.91%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.91%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.91%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.91%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.91%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.91%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.91%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.91%   |
| Ralink RT2070 Wireless Adapter                                 | 1         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 41        | 46.59%  |
| Intel                      | 20        | 22.73%  |
| Qualcomm Atheros           | 9         | 10.23%  |
| Broadcom                   | 4         | 4.55%   |
| Samsung Electronics        | 2         | 2.27%   |
| Nvidia                     | 2         | 2.27%   |
| Marvell Technology Group   | 2         | 2.27%   |
| Huawei Technologies        | 2         | 2.27%   |
| ASIX Electronics           | 2         | 2.27%   |
| ZTE WCDMA Technologies MSM | 1         | 1.14%   |
| Xiaomi                     | 1         | 1.14%   |
| NetGear                    | 1         | 1.14%   |
| Broadcom Limited           | 1         | 1.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 34.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 6.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 2.27%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 2.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.27%   |
| Nvidia MCP79 Ethernet                                             | 2         | 2.27%   |
| Intel Ethernet Connection I219-V                                  | 2         | 2.27%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.27%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.27%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 2.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.27%   |
| ZTE WCDMA MSM Android                                             | 1         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.14%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.14%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.14%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.14%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.14%   |
| NetGear LB1120-100NAS                                             | 1         | 1.14%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.14%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.14%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.14%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.14%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.14%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.14%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.14%   |
| Huawei LLD-L21                                                    | 1         | 1.14%   |
| Huawei E353/E3131                                                 | 1         | 1.14%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.14%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.14%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 1         | 1.14%   |
| ASIX AX88772B                                                     | 1         | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 55.26%  |
| Ethernet | 81        | 42.63%  |
| Modem    | 3         | 1.58%   |
| Unknown  | 1         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 77.36%  |
| Ethernet | 24        | 22.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 73        | 69.52%  |
| 1     | 30        | 28.57%  |
| 3     | 1         | 0.95%   |
| 0     | 1         | 0.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 72.38%  |
| Yes  | 29        | 27.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 46.15%  |
| Realtek Semiconductor           | 14        | 15.38%  |
| Apple                           | 11        | 12.09%  |
| Qualcomm Atheros Communications | 7         | 7.69%   |
| Lite-On Technology              | 4         | 4.4%    |
| Foxconn / Hon Hai               | 4         | 4.4%    |
| IMC Networks                    | 3         | 3.3%    |
| Broadcom                        | 3         | 3.3%    |
| Toshiba                         | 1         | 1.1%    |
| Hewlett-Packard                 | 1         | 1.1%    |
| Askey Computer                  | 1         | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 14        | 15.38%  |
| Intel AX201 Bluetooth                              | 11        | 12.09%  |
| Realtek  Bluetooth 4.2 Adapter                     | 8         | 8.79%   |
| Apple Bluetooth Host Controller                    | 6         | 6.59%   |
| Realtek Bluetooth Radio                            | 5         | 5.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 5         | 5.49%   |
| Apple Bluetooth USB Host Controller                | 4         | 4.4%    |
| Qualcomm Atheros  Bluetooth Device                 | 3         | 3.3%    |
| Intel AX200 Bluetooth                              | 3         | 3.3%    |
| Foxconn / Hon Hai Bluetooth Device                 | 3         | 3.3%    |
| Qualcomm Atheros AR3011 Bluetooth                  | 2         | 2.2%    |
| Lite-On Bluetooth Device                           | 2         | 2.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 2         | 2.2%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter   | 2         | 2.2%    |
| Intel Bluetooth Device                             | 2         | 2.2%    |
| Intel AX210 Bluetooth                              | 2         | 2.2%    |
| Toshiba Bluetooth Device                           | 1         | 1.1%    |
| Realtek RTL8821A Bluetooth                         | 1         | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 1.1%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device       | 1         | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 1.1%    |
| IMC Networks Bluetooth Radio                       | 1         | 1.1%    |
| IMC Networks Bluetooth                             | 1         | 1.1%    |
| IMC Networks BCM20702A0                            | 1         | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 1.1%    |
| Foxconn / Hon Hai BCM43142A0                       | 1         | 1.1%    |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 1.1%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 1.1%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.1%    |
| Askey Bluetooth Device                             | 1         | 1.1%    |
| Apple Bluetooth HCI                                | 1         | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 84        | 66.14%  |
| AMD                    | 21        | 16.54%  |
| Nvidia                 | 15        | 11.81%  |
| C-Media Electronics    | 2         | 1.57%   |
| Realtek Semiconductor  | 1         | 0.79%   |
| Logitech               | 1         | 0.79%   |
| Hewlett-Packard        | 1         | 0.79%   |
| GN Netcom              | 1         | 0.79%   |
| Generalplus Technology | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 7.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 6.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 5.77%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 5.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 4.49%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 3.85%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 3.85%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 2.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.56%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 2.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.92%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.92%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 1.28%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 1.28%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.28%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.28%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.28%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 1.28%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.64%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.64%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.64%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.64%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 40.74%  |
| SK hynix            | 6         | 22.22%  |
| Micron Technology   | 6         | 22.22%  |
| Ramaxel Technology  | 1         | 3.7%    |
| pqi                 | 1         | 3.7%    |
| GSkill              | 1         | 3.7%    |
| Crucial             | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s    | 2         | 7.41%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                  | 1         | 3.7%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 3.7%    |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s        | 1         | 3.7%    |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s       | 1         | 3.7%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 3.7%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s     | 1         | 3.7%    |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 3.7%    |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s             | 1         | 3.7%    |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                  | 1         | 3.7%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 1         | 3.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s   | 1         | 3.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 3.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 3.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 1         | 3.7%    |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s  | 1         | 3.7%    |
| Ramaxel RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1         | 3.7%    |
| pqi RAM Module 2GB SODIMM DDR2 667MT/s                        | 1         | 3.7%    |
| Micron RAM MT53E1G32D2NP-046 8GB Row Of Chips LPDDR4 4267MT/s | 1         | 3.7%    |
| Micron RAM Module 8GB SODIMM DDR4 2667MT/s                    | 1         | 3.7%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 1         | 3.7%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s         | 1         | 3.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 1         | 3.7%    |
| Micron RAM 16ATF4G64HZ-3G2E2 32GB SODIMM DDR4 3200MT/s        | 1         | 3.7%    |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s         | 1         | 3.7%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 1         | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 56%     |
| LPDDR4 | 4         | 16%     |
| DDR3   | 4         | 16%     |
| LPDDR3 | 1         | 4%      |
| DDR5   | 1         | 4%      |
| DDR2   | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 69.23%  |
| Row Of Chips | 8         | 30.77%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 15        | 57.69%  |
| 4096  | 5         | 19.23%  |
| 16384 | 3         | 11.54%  |
| 2048  | 2         | 7.69%   |
| 32768 | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 8         | 32%     |
| 2667  | 6         | 24%     |
| 4267  | 4         | 16%     |
| 1600  | 2         | 8%      |
| 4800  | 1         | 4%      |
| 2400  | 1         | 4%      |
| 2133  | 1         | 4%      |
| 1333  | 1         | 4%      |
| 667   | 1         | 4%      |

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


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer | 1         | 100%    |

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
| Chicony Electronics                    | 20        | 21.05%  |
| Quanta                                 | 11        | 11.58%  |
| IMC Networks                           | 11        | 11.58%  |
| Microdia                               | 9         | 9.47%   |
| Realtek Semiconductor                  | 8         | 8.42%   |
| Apple                                  | 8         | 8.42%   |
| Bison Electronics                      | 6         | 6.32%   |
| Sunplus Innovation Technology          | 3         | 3.16%   |
| Syntek                                 | 2         | 2.11%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.11%   |
| Acer                                   | 2         | 2.11%   |
| Suyin                                  | 1         | 1.05%   |
| SunplusIT                              | 1         | 1.05%   |
| Sunplus Technology                     | 1         | 1.05%   |
| Silicon Motion                         | 1         | 1.05%   |
| Samsung Electronics                    | 1         | 1.05%   |
| Luxvisions Innotech Limited            | 1         | 1.05%   |
| Logitech                               | 1         | 1.05%   |
| Lite-On Technology                     | 1         | 1.05%   |
| Lenovo                                 | 1         | 1.05%   |
| Intel                                  | 1         | 1.05%   |
| Cubeternet                             | 1         | 1.05%   |
| Cisco Systems                          | 1         | 1.05%   |
| Alcor Micro                            | 1         | 1.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 5         | 5.21%   |
| Microdia Integrated_Webcam_HD        | 4         | 4.17%   |
| Realtek Integrated_Webcam_HD         | 3         | 3.13%   |
| IMC Networks USB2.0 HD UVC WebCam    | 3         | 3.13%   |
| IMC Networks Integrated Camera       | 3         | 3.13%   |
| Quanta USB2.0 HD UVC WebCam          | 2         | 2.08%   |
| Quanta HP HD Camera                  | 2         | 2.08%   |
| Microdia Integrated Webcam           | 2         | 2.08%   |
| IMC Networks HD Camera               | 2         | 2.08%   |
| Chicony HP TrueVision HD Camera      | 2         | 2.08%   |
| Chicony HP Truevision HD             | 2         | 2.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X      | 2         | 2.08%   |
| Apple FaceTime HD Camera             | 2         | 2.08%   |
| Apple FaceTime Camera                | 2         | 2.08%   |
| Apple Built-in iSight                | 2         | 2.08%   |
| Syntek Lenovo EasyCamera             | 1         | 1.04%   |
| Syntek EasyCamera                    | 1         | 1.04%   |
| Suyin Acer HD Crystal Eye webcam     | 1         | 1.04%   |
| SunplusIT HD Camera                  | 1         | 1.04%   |
| Sunplus 1.3M HD WebCam               | 1         | 1.04%   |
| Sunplus HD WebCam                    | 1         | 1.04%   |
| Sunplus Dell E5570 integrated webcam | 1         | 1.04%   |
| Sunplus Camera                       | 1         | 1.04%   |
| Silicon Motion WebCam SC-03FFL11939N | 1         | 1.04%   |
| Samsung Galaxy A5 (MTP)              | 1         | 1.04%   |
| Realtek USB Camera                   | 1         | 1.04%   |
| Realtek HP Webcam                    | 1         | 1.04%   |
| Realtek EasyCamera                   | 1         | 1.04%   |
| Realtek Acer 640 x 480 laptop camera | 1         | 1.04%   |
| Realtek 2SF022                       | 1         | 1.04%   |
| Quanta VGA WebCam                    | 1         | 1.04%   |
| Quanta ov9734_techfront_camera       | 1         | 1.04%   |
| Quanta HP Wide Vision HD Camera      | 1         | 1.04%   |
| Quanta HP Webcam                     | 1         | 1.04%   |
| Quanta HP TrueVision HD Camera       | 1         | 1.04%   |
| Quanta HD Webcam                     | 1         | 1.04%   |
| Quanta HD Camera                     | 1         | 1.04%   |
| Microdia Webcam Vitade AF            | 1         | 1.04%   |
| Microdia REDRAGON Live Camera Audio  | 1         | 1.04%   |
| Microdia Integrated_Webcam_2M        | 1         | 1.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 32%     |
| Shenzhen Goodix Technology | 7         | 28%     |
| Synaptics                  | 4         | 16%     |
| Elan Microelectronics      | 3         | 12%     |
| Upek                       | 1         | 4%      |
| LighTuning Technology      | 1         | 4%      |
| AuthenTec                  | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 24%     |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 12%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 8%      |
| Elan ELAN:Fingerprint                                                      | 2         | 8%      |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 4%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 4%      |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 4%      |
| Validity Sensors Synaptics WBDI                                            | 1         | 4%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 4%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 4%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 4%      |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 4%      |
| LighTuning Fingerprint Reader                                              | 1         | 4%      |
| Elan ELAN:ARM-M4                                                           | 1         | 4%      |
| AuthenTec Fingerprint Sensor                                               | 1         | 4%      |

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
| 0     | 59        | 56.19%  |
| 1     | 39        | 37.14%  |
| 2     | 7         | 6.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 24        | 45.28%  |
| Net/wireless          | 8         | 15.09%  |
| Multimedia controller | 8         | 15.09%  |
| Chipcard              | 6         | 11.32%  |
| Graphics card         | 5         | 9.43%   |
| Storage               | 1         | 1.89%   |
| Net/ethernet          | 1         | 1.89%   |

