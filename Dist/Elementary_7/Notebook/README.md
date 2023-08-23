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

Total: 196

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro6,2               | [7c62a05800](https://linux-hardware.org/?probe=7c62a05800) | Aug 12, 2023 |
| Acer          | TravelMate B113             | [5d3d27c8bb](https://linux-hardware.org/?probe=5d3d27c8bb) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [80f2f711d8](https://linux-hardware.org/?probe=80f2f711d8) | Aug 10, 2023 |
| HP            | ProBook 4310s               | [ac0c1be078](https://linux-hardware.org/?probe=ac0c1be078) | Aug 09, 2023 |
| HP            | EliteBook 850 G3            | [04a319c904](https://linux-hardware.org/?probe=04a319c904) | Aug 09, 2023 |
| Apple         | MacBookPro8,1               | [6165a2d50e](https://linux-hardware.org/?probe=6165a2d50e) | Aug 08, 2023 |
| HP            | G60                         | [7f3b9aec85](https://linux-hardware.org/?probe=7f3b9aec85) | Aug 07, 2023 |
| Lenovo        | ThinkPad X201 Tablet 298... | [7132bbeb85](https://linux-hardware.org/?probe=7132bbeb85) | Aug 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2b8f90f79d](https://linux-hardware.org/?probe=2b8f90f79d) | Aug 03, 2023 |
| Acer          | Predator G3-571             | [fc950e8651](https://linux-hardware.org/?probe=fc950e8651) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | [73e1dd94b2](https://linux-hardware.org/?probe=73e1dd94b2) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2f4ed3cb1f](https://linux-hardware.org/?probe=2f4ed3cb1f) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | [a13fd4044e](https://linux-hardware.org/?probe=a13fd4044e) | Aug 01, 2023 |
| SHENZHEN Y... | A8S PRO                     | [829a4178a5](https://linux-hardware.org/?probe=829a4178a5) | Jul 30, 2023 |
| Apple         | MacBookPro11,3              | [c7572ce663](https://linux-hardware.org/?probe=c7572ce663) | Jul 30, 2023 |
| Apple         | MacBookPro11,3              | [8ac9af1db8](https://linux-hardware.org/?probe=8ac9af1db8) | Jul 29, 2023 |
| SHENZHEN Y... | A8S PRO                     | [08a6feda0e](https://linux-hardware.org/?probe=08a6feda0e) | Jul 28, 2023 |
| HP            | 255 G8 Notebook PC          | [c2e02d1490](https://linux-hardware.org/?probe=c2e02d1490) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a5359c62e0](https://linux-hardware.org/?probe=a5359c62e0) | Jul 20, 2023 |
| Alienware     | m15 R6                      | [93d5e98358](https://linux-hardware.org/?probe=93d5e98358) | Jul 20, 2023 |
| HP            | Notebook                    | [2ccf016245](https://linux-hardware.org/?probe=2ccf016245) | Jul 19, 2023 |
| Apple         | MacBookPro8,1               | [7dd13cea49](https://linux-hardware.org/?probe=7dd13cea49) | Jul 17, 2023 |
| Google        | Phaser360                   | [1e66458514](https://linux-hardware.org/?probe=1e66458514) | Jul 17, 2023 |
| HP            | ENVY 15                     | [a173db4ea1](https://linux-hardware.org/?probe=a173db4ea1) | Jul 17, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | [2c05f1a964](https://linux-hardware.org/?probe=2c05f1a964) | Jul 16, 2023 |
| Apple         | MacBookPro8,1               | [74420b09b7](https://linux-hardware.org/?probe=74420b09b7) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1a0add8887](https://linux-hardware.org/?probe=1a0add8887) | Jul 11, 2023 |
| HP            | ENVY 15                     | [3ccdaf4d4e](https://linux-hardware.org/?probe=3ccdaf4d4e) | Jul 10, 2023 |
| Apple         | MacBookPro12,1              | [8877b51b89](https://linux-hardware.org/?probe=8877b51b89) | Jul 08, 2023 |
| HP            | Laptop 14-dq0xxx            | [bb065938a5](https://linux-hardware.org/?probe=bb065938a5) | Jul 07, 2023 |
| Apple         | MacBookPro8,1               | [ee299280f8](https://linux-hardware.org/?probe=ee299280f8) | Jul 07, 2023 |
| Dell          | Latitude E7270              | [406e4a918b](https://linux-hardware.org/?probe=406e4a918b) | Jul 06, 2023 |
| Intel Clie... | LAPBC710                    | [fd97a27365](https://linux-hardware.org/?probe=fd97a27365) | Jul 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [2e4a653435](https://linux-hardware.org/?probe=2e4a653435) | Jul 04, 2023 |
| Apple         | MacBookPro9,2               | [f7a7db0702](https://linux-hardware.org/?probe=f7a7db0702) | Jul 04, 2023 |
| GPD           | MicroPC                     | [f666f4c574](https://linux-hardware.org/?probe=f666f4c574) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 23254W5       | [5842896b76](https://linux-hardware.org/?probe=5842896b76) | Jul 03, 2023 |
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
| 5.15.0-58-generic    | 36        | 25.71%  |
| 5.19.0-41-generic    | 18        | 12.86%  |
| 5.19.0-35-generic    | 17        | 12.14%  |
| 5.19.0-46-generic    | 13        | 9.29%   |
| 5.19.0-32-generic    | 12        | 8.57%   |
| 5.19.0-43-generic    | 9         | 6.43%   |
| 5.19.0-38-generic    | 9         | 6.43%   |
| 6.2.0-26-generic     | 5         | 3.57%   |
| 5.19.0-50-generic    | 4         | 2.86%   |
| 5.19.0-40-generic    | 4         | 2.86%   |
| 5.15.0-60-generic    | 4         | 2.86%   |
| 5.19.0-45-generic    | 2         | 1.43%   |
| 5.19.0-42-generic    | 2         | 1.43%   |
| 6.2.7-060207-generic | 1         | 0.71%   |
| 6.1.9-060109-generic | 1         | 0.71%   |
| 6.1.6-060106-generic | 1         | 0.71%   |
| 6.1.0-1013-oem       | 1         | 0.71%   |
| 5.15.0-56-generic    | 1         | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.0  | 85        | 62.96%  |
| 5.15.0  | 41        | 30.37%  |
| 6.2.0   | 5         | 3.7%    |
| 6.2.7   | 1         | 0.74%   |
| 6.1.9   | 1         | 0.74%   |
| 6.1.6   | 1         | 0.74%   |
| 6.1.0   | 1         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19    | 85        | 62.96%  |
| 5.15    | 41        | 30.37%  |
| 6.2     | 6         | 4.44%   |
| 6.1     | 3         | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 132       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 132       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 132       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 107       | 81.06%  |
| LightDM | 25        | 18.94%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 59        | 44.7%   |
| de_DE | 20        | 15.15%  |
| ru_RU | 13        | 9.85%   |
| es_ES | 12        | 9.09%   |
| fr_FR | 5         | 3.79%   |
| en_GB | 4         | 3.03%   |
| pl_PL | 3         | 2.27%   |
| sv_SE | 2         | 1.52%   |
| nb_NO | 2         | 1.52%   |
| it_IT | 2         | 1.52%   |
| en_AU | 2         | 1.52%   |
| el_GR | 2         | 1.52%   |
| uk_UA | 1         | 0.76%   |
| tr_TR | 1         | 0.76%   |
| pt_PT | 1         | 0.76%   |
| pt_BR | 1         | 0.76%   |
| hu_HU | 1         | 0.76%   |
| da_DK | 1         | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 114       | 86.36%  |
| EFI  | 18        | 13.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 126       | 94.74%  |
| Tmpfs   | 4         | 3.01%   |
| Xfs     | 1         | 0.75%   |
| Overlay | 1         | 0.75%   |
| Btrfs   | 1         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 107       | 81.06%  |
| GPT     | 20        | 15.15%  |
| MBR     | 5         | 3.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 131       | 99.24%  |
| Yes       | 1         | 0.76%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 124       | 93.94%  |
| Yes       | 8         | 6.06%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 26        | 19.7%   |
| Lenovo                      | 23        | 17.42%  |
| Apple                       | 19        | 14.39%  |
| ASUSTek Computer            | 13        | 9.85%   |
| Dell                        | 12        | 9.09%   |
| Acer                        | 9         | 6.82%   |
| HUAWEI                      | 5         | 3.79%   |
| MSI                         | 4         | 3.03%   |
| Toshiba                     | 3         | 2.27%   |
| Fujitsu                     | 3         | 2.27%   |
| Sony                        | 2         | 1.52%   |
| HONOR                       | 2         | 1.52%   |
| Alienware                   | 2         | 1.52%   |
| Star Labs                   | 1         | 0.76%   |
| SHENZHEN YOUDISI E-COMMERCE | 1         | 0.76%   |
| Samsung Electronics         | 1         | 0.76%   |
| Razer                       | 1         | 0.76%   |
| PCBOX                       | 1         | 0.76%   |
| GPU Company                 | 1         | 0.76%   |
| GPD                         | 1         | 0.76%   |
| Google                      | 1         | 0.76%   |
| Clevo                       | 1         | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Apple MacBookPro8,1                        | 3         | 2.27%   |
| HUAWEI BOD-WXX9                            | 2         | 1.52%   |
| HP 255 G7 Notebook PC                      | 2         | 1.52%   |
| Apple MacBookPro9,2                        | 2         | 1.52%   |
| Apple MacBookPro11,3                       | 2         | 1.52%   |
| Toshiba TECRA Z40-C                        | 1         | 0.76%   |
| Toshiba TECRA R850                         | 1         | 0.76%   |
| Toshiba Satellite C660                     | 1         | 0.76%   |
| Star Labs StarBook                         | 1         | 0.76%   |
| Sony VPCEH2C5E                             | 1         | 0.76%   |
| Sony SVF1521O4E                            | 1         | 0.76%   |
| SHENZHEN YOUDISI E-COMMERCE A8S PRO        | 1         | 0.76%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.76%   |
| Razer Blade Stealth                        | 1         | 0.76%   |
| PCBOX Kant                                 | 1         | 0.76%   |
| MSI PE70 6QE                               | 1         | 0.76%   |
| MSI GT72 2QE                               | 1         | 0.76%   |
| MSI GE62VR 6RF                             | 1         | 0.76%   |
| MSI CX61 2PC                               | 1         | 0.76%   |
| Lenovo V14 G2 ITL 82KA                     | 1         | 0.76%   |
| Lenovo ThinkPad X240 20AMS0XP0S            | 1         | 0.76%   |
| Lenovo ThinkPad X230 23259S9               | 1         | 0.76%   |
| Lenovo ThinkPad X230 23254W5               | 1         | 0.76%   |
| Lenovo ThinkPad X201 Tablet 2985DMG        | 1         | 0.76%   |
| Lenovo ThinkPad X13 Gen 1 20T3S3SH0U       | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW   | 1         | 0.76%   |
| Lenovo ThinkPad T495 20NKS01W02            | 1         | 0.76%   |
| Lenovo ThinkPad T460 20FMS08H00            | 1         | 0.76%   |
| Lenovo ThinkPad T440p 20AWS38H0G           | 1         | 0.76%   |
| Lenovo ThinkPad T430 2349OB6               | 1         | 0.76%   |
| Lenovo ThinkPad T400s 2808D9G              | 1         | 0.76%   |
| Lenovo ThinkPad P51s 20HB001TUS            | 1         | 0.76%   |
| Lenovo ThinkPad Edge E330 3354AHG          | 1         | 0.76%   |
| Lenovo ThinkPad Edge E330 33542E4          | 1         | 0.76%   |
| Lenovo ThinkPad E560 20EV003DSP            | 1         | 0.76%   |
| Lenovo ThinkBook 13s G3 ACN 20YA           | 1         | 0.76%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.76%   |
| Lenovo IdeaPad 320-15IKB 80XL              | 1         | 0.76%   |
| Lenovo IdeaPad 320-15ABR 80XS              | 1         | 0.76%   |
| Lenovo IdeaPad 3 15IGL05 81WQ              | 1         | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 15        | 11.36%  |
| Acer Aspire                     | 7         | 5.3%    |
| Dell Latitude                   | 6         | 4.55%   |
| HP ProBook                      | 5         | 3.79%   |
| HP Pavilion                     | 5         | 3.79%   |
| ASUS VivoBook                   | 5         | 3.79%   |
| Lenovo IdeaPad                  | 4         | 3.03%   |
| HP Laptop                       | 4         | 3.03%   |
| ASUS ZenBook                    | 4         | 3.03%   |
| Apple MacBookPro8               | 4         | 3.03%   |
| Apple MacBookPro11              | 4         | 3.03%   |
| HP 255                          | 3         | 2.27%   |
| Fujitsu LIFEBOOK                | 3         | 2.27%   |
| Toshiba TECRA                   | 2         | 1.52%   |
| HUAWEI BOD-WXX9                 | 2         | 1.52%   |
| HP EliteBook                    | 2         | 1.52%   |
| Dell XPS                        | 2         | 1.52%   |
| Apple MacBookPro9               | 2         | 1.52%   |
| Apple MacBookPro5               | 2         | 1.52%   |
| Apple MacBookAir3               | 2         | 1.52%   |
| Toshiba Satellite               | 1         | 0.76%   |
| Star Labs StarBook              | 1         | 0.76%   |
| Sony VPCEH2C5E                  | 1         | 0.76%   |
| Sony SVF1521O4E                 | 1         | 0.76%   |
| SHENZHEN YOUDISI E-COMMERCE A8S | 1         | 0.76%   |
| Samsung 300E4A                  | 1         | 0.76%   |
| Razer Blade                     | 1         | 0.76%   |
| PCBOX Kant                      | 1         | 0.76%   |
| MSI PE70                        | 1         | 0.76%   |
| MSI GT72                        | 1         | 0.76%   |
| MSI GE62VR                      | 1         | 0.76%   |
| MSI CX61                        | 1         | 0.76%   |
| Lenovo V14                      | 1         | 0.76%   |
| Lenovo ThinkBook                | 1         | 0.76%   |
| Lenovo Legion                   | 1         | 0.76%   |
| Lenovo G580                     | 1         | 0.76%   |
| HUAWEI NBLB-WAX9N               | 1         | 0.76%   |
| HUAWEI NBD-WXX9                 | 1         | 0.76%   |
| HUAWEI BOHB-WAX9                | 1         | 0.76%   |
| HONOR HYM-WXX                   | 1         | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 15        | 11.36%  |
| 2020 | 14        | 10.61%  |
| 2012 | 14        | 10.61%  |
| 2019 | 12        | 9.09%   |
| 2016 | 10        | 7.58%   |
| 2014 | 9         | 6.82%   |
| 2015 | 8         | 6.06%   |
| 2010 | 8         | 6.06%   |
| 2022 | 7         | 5.3%    |
| 2011 | 7         | 5.3%    |
| 2018 | 6         | 4.55%   |
| 2013 | 6         | 4.55%   |
| 2017 | 5         | 3.79%   |
| 2009 | 5         | 3.79%   |
| 2008 | 4         | 3.03%   |
| 2023 | 2         | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 132       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 126       | 95.45%  |
| Enabled  | 6         | 4.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 130       | 98.48%  |
| Yes  | 2         | 1.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 43        | 32.58%  |
| 8.01-16.0   | 28        | 21.21%  |
| 16.01-24.0  | 25        | 18.94%  |
| 3.01-4.0    | 24        | 18.18%  |
| 32.01-64.0  | 7         | 5.3%    |
| 64.01-256.0 | 2         | 1.52%   |
| 1.01-2.0    | 2         | 1.52%   |
| 2.01-3.0    | 1         | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 60        | 42.86%  |
| 1.01-2.0  | 30        | 21.43%  |
| 3.01-4.0  | 26        | 18.57%  |
| 4.01-8.0  | 18        | 12.86%  |
| 8.01-16.0 | 3         | 2.14%   |
| 0.51-1.0  | 3         | 2.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 105       | 78.95%  |
| 2      | 27        | 20.3%   |
| 4      | 1         | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 65.91%  |
| Yes       | 45        | 34.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 76.52%  |
| No        | 31        | 23.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 88.64%  |
| No        | 15        | 11.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 25        | 18.8%   |
| Germany      | 24        | 18.05%  |
| Russia       | 12        | 9.02%   |
| UK           | 5         | 3.76%   |
| Poland       | 5         | 3.76%   |
| France       | 5         | 3.76%   |
| Spain        | 4         | 3.01%   |
| Norway       | 3         | 2.26%   |
| Netherlands  | 3         | 2.26%   |
| Indonesia    | 3         | 2.26%   |
| India        | 3         | 2.26%   |
| Brazil       | 3         | 2.26%   |
| Australia    | 3         | 2.26%   |
| Thailand     | 2         | 1.5%    |
| Portugal     | 2         | 1.5%    |
| Mexico       | 2         | 1.5%    |
| Italy        | 2         | 1.5%    |
| Israel       | 2         | 1.5%    |
| Greece       | 2         | 1.5%    |
| Canada       | 2         | 1.5%    |
| Argentina    | 2         | 1.5%    |
| Turkey       | 1         | 0.75%   |
| Tunisia      | 1         | 0.75%   |
| Sweden       | 1         | 0.75%   |
| South Africa | 1         | 0.75%   |
| Saudi Arabia | 1         | 0.75%   |
| Puerto Rico  | 1         | 0.75%   |
| Kazakhstan   | 1         | 0.75%   |
| Ireland      | 1         | 0.75%   |
| Hungary      | 1         | 0.75%   |
| Georgia      | 1         | 0.75%   |
| Ecuador      | 1         | 0.75%   |
| Denmark      | 1         | 0.75%   |
| Cyprus       | 1         | 0.75%   |
| Colombia     | 1         | 0.75%   |
| China        | 1         | 0.75%   |
| Chile        | 1         | 0.75%   |
| Belgium      | 1         | 0.75%   |
| Austria      | 1         | 0.75%   |
| Albania      | 1         | 0.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 4         | 2.92%   |
| Berlin                  | 3         | 2.19%   |
| Warsaw                  | 2         | 1.46%   |
| Stuttgart               | 2         | 1.46%   |
| Novosibirsk             | 2         | 1.46%   |
| Madrid                  | 2         | 1.46%   |
| Los Angeles             | 2         | 1.46%   |
| Jakarta                 | 2         | 1.46%   |
| Delhi                   | 2         | 1.46%   |
| Cologne                 | 2         | 1.46%   |
| Bangkok                 | 2         | 1.46%   |
| Zhuantang               | 1         | 0.73%   |
| Yekaterinburg           | 1         | 0.73%   |
| Wouldham                | 1         | 0.73%   |
| Worcestershire          | 1         | 0.73%   |
| Wilsdruff               | 1         | 0.73%   |
| Wiesbaden               | 1         | 0.73%   |
| Villefranche-sur-Saône | 1         | 0.73%   |
| Vigo                    | 1         | 0.73%   |
| Vienna                  | 1         | 0.73%   |
| Twickenham              | 1         | 0.73%   |
| Tuam                    | 1         | 0.73%   |
| Tromsø                 | 1         | 0.73%   |
| Troisdorf               | 1         | 0.73%   |
| Torres Vedras           | 1         | 0.73%   |
| Tirana                  | 1         | 0.73%   |
| Tel Aviv                | 1         | 0.73%   |
| Tbilisi                 | 1         | 0.73%   |
| Sydney                  | 1         | 0.73%   |
| Stockholm               | 1         | 0.73%   |
| St Petersburg           | 1         | 0.73%   |
| Spaichingen             | 1         | 0.73%   |
| Sorum                   | 1         | 0.73%   |
| Slavyansk-na-Kubani     | 1         | 0.73%   |
| Sfax                    | 1         | 0.73%   |
| Sarasota                | 1         | 0.73%   |
| San Juan                | 1         | 0.73%   |
| Salzgitter              | 1         | 0.73%   |
| Rostov-on-Don           | 1         | 0.73%   |
| Roosendaal              | 1         | 0.73%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 25        | 26     | 15.53%  |
| Sandisk                        | 14        | 15     | 8.7%    |
| WDC                            | 13        | 14     | 8.07%   |
| Toshiba                        | 12        | 15     | 7.45%   |
| Crucial                        | 11        | 12     | 6.83%   |
| Seagate                        | 9         | 10     | 5.59%   |
| Apple                          | 9         | 9      | 5.59%   |
| Unknown                        | 7         | 8      | 4.35%   |
| Kingston                       | 7         | 9      | 4.35%   |
| Intel                          | 5         | 6      | 3.11%   |
| China                          | 4         | 4      | 2.48%   |
| Phison Electronics             | 3         | 3      | 1.86%   |
| Micron Technology              | 3         | 3      | 1.86%   |
| HGST                           | 3         | 4      | 1.86%   |
| SK hynix                       | 2         | 3      | 1.24%   |
| KIOXIA                         | 2         | 4      | 1.24%   |
| JMicron Technology             | 2         | 2      | 1.24%   |
| Intenso                        | 2         | 3      | 1.24%   |
| Hitachi                        | 2         | 2      | 1.24%   |
| BIWIN                          | 2         | 2      | 1.24%   |
| VISIPRO                        | 1         | 1      | 0.62%   |
| USB 3.0                        | 1         | 1      | 0.62%   |
| Union Memory                   | 1         | 2      | 0.62%   |
| T-FORCE                        | 1         | 1      | 0.62%   |
| Star Drive                     | 1         | 1      | 0.62%   |
| SPCC                           | 1         | 1      | 0.62%   |
| Solid State Storage Technology | 1         | 1      | 0.62%   |
| Solid State Storage            | 1         | 1      | 0.62%   |
| Silicon Motion                 | 1         | 1      | 0.62%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.62%   |
| Realtek Semiconductor          | 1         | 2      | 0.62%   |
| PNY                            | 1         | 1      | 0.62%   |
| OWC                            | 1         | 1      | 0.62%   |
| LITEON                         | 1         | 1      | 0.62%   |
| KUU                            | 1         | 1      | 0.62%   |
| Kingston Technology Company    | 1         | 1      | 0.62%   |
| JetFlash                       | 1         | 1      | 0.62%   |
| Inland                         | 1         | 1      | 0.62%   |
| GeIL                           | 1         | 1      | 0.62%   |
| Fujitsu                        | 1         | 1      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 3         | 1.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 1.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 1.84%   |
| Phison E12 NVMe Controller 2TB                      | 3         | 1.84%   |
| Unknown MMC Card  7GB                               | 2         | 1.23%   |
| Unknown MMC Card  32GB                              | 2         | 1.23%   |
| Toshiba MK5065GSXF 500GB                            | 2         | 1.23%   |
| Seagate Expansion 1TB                               | 2         | 1.23%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 2         | 1.23%   |
| SanDisk SDSSDA240G 240GB                            | 2         | 1.23%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD                | 2         | 1.23%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1.23%   |
| HGST HTS721010A9E630 1TB                            | 2         | 1.23%   |
| Crucial CT275MX300SSD1 275GB                        | 2         | 1.23%   |
| Crucial CT250MX500SSD1 250GB                        | 2         | 1.23%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 1.23%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 1.23%   |
| Apple SSD SM0512F 500GB                             | 2         | 1.23%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.61%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.61%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 0.61%   |
| WDC WD5000LPVX-80V0TT0 500GB                        | 1         | 0.61%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 0.61%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 0.61%   |
| WDC WD10SPCX-08S8TT0 1TB                            | 1         | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.61%   |
| WDC WD Green 2.5 1000GB                             | 1         | 0.61%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 1         | 0.61%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB                | 1         | 0.61%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                | 1         | 0.61%   |
| VISIPRO SSD 256GB                                   | 1         | 0.61%   |
| USB 3.0 Device 250GB                                | 1         | 0.61%   |
| Unknown SE64G  64GB                                 | 1         | 0.61%   |
| Unknown MMC Card  64GB                              | 1         | 0.61%   |
| Unknown MMC Card  128GB                             | 1         | 0.61%   |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB             | 1         | 0.61%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 1         | 0.61%   |
| Toshiba THNSNJ128GCSU 128GB SSD                     | 1         | 0.61%   |
| Toshiba THNSNJ128G8NU 128GB SSD                     | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 8         | 9      | 27.59%  |
| Toshiba            | 7         | 8      | 24.14%  |
| WDC                | 5         | 5      | 17.24%  |
| HGST               | 3         | 4      | 10.34%  |
| Hitachi            | 2         | 2      | 6.9%    |
| JMicron Technology | 1         | 1      | 3.45%   |
| Fujitsu            | 1         | 1      | 3.45%   |
| ASMT               | 1         | 1      | 3.45%   |
| Apple              | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 11        | 12     | 16.67%  |
| Samsung Electronics | 10        | 11     | 15.15%  |
| Apple               | 8         | 8      | 12.12%  |
| SanDisk             | 7         | 7      | 10.61%  |
| Kingston            | 6         | 8      | 9.09%   |
| WDC                 | 5         | 6      | 7.58%   |
| Toshiba             | 4         | 6      | 6.06%   |
| China               | 4         | 4      | 6.06%   |
| VISIPRO             | 1         | 1      | 1.52%   |
| SPCC                | 1         | 1      | 1.52%   |
| PNY                 | 1         | 1      | 1.52%   |
| OWC                 | 1         | 1      | 1.52%   |
| Micron Technology   | 1         | 1      | 1.52%   |
| LITEON              | 1         | 1      | 1.52%   |
| KUU                 | 1         | 1      | 1.52%   |
| Intenso             | 1         | 2      | 1.52%   |
| Intel               | 1         | 1      | 1.52%   |
| Inland              | 1         | 1      | 1.52%   |
| BIWIN               | 1         | 1      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 61        | 74     | 40.67%  |
| NVMe    | 48        | 58     | 32%     |
| HDD     | 26        | 32     | 17.33%  |
| Unknown | 8         | 8      | 5.33%   |
| MMC     | 7         | 8      | 4.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 86        | 104    | 57.33%  |
| NVMe | 48        | 58     | 32%     |
| SAS  | 9         | 10     | 6%      |
| MMC  | 7         | 8      | 4.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 79     | 75.28%  |
| 0.51-1.0   | 17        | 22     | 19.1%   |
| 1.01-2.0   | 5         | 5      | 5.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 61        | 45.52%  |
| 251-500        | 36        | 26.87%  |
| 501-1000       | 19        | 14.18%  |
| 51-100         | 9         | 6.72%   |
| 2001-3000      | 3         | 2.24%   |
| 1001-2000      | 2         | 1.49%   |
| 1-20           | 2         | 1.49%   |
| More than 3000 | 1         | 0.75%   |
| 21-50          | 1         | 0.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 70        | 51.09%  |
| 21-50          | 33        | 24.09%  |
| 101-250        | 14        | 10.22%  |
| 51-100         | 13        | 9.49%   |
| 251-500        | 3         | 2.19%   |
| 1001-2000      | 2         | 1.46%   |
| More than 3000 | 1         | 0.73%   |
| 501-1000       | 1         | 0.73%   |

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
| Detected | 116       | 159    | 85.93%  |
| Works    | 19        | 21     | 14.07%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 92        | 58.6%   |
| Samsung Electronics            | 19        | 12.1%   |
| SanDisk                        | 10        | 6.37%   |
| AMD                            | 10        | 6.37%   |
| Phison Electronics             | 4         | 2.55%   |
| Nvidia                         | 4         | 2.55%   |
| Solid State Storage Technology | 2         | 1.27%   |
| SK hynix                       | 2         | 1.27%   |
| Micron Technology              | 2         | 1.27%   |
| KIOXIA                         | 2         | 1.27%   |
| Kingston Technology Company    | 2         | 1.27%   |
| Union Memory (Shenzhen)        | 1         | 0.64%   |
| Toshiba America Info Systems   | 1         | 0.64%   |
| Silicon Motion                 | 1         | 0.64%   |
| Shenzhen Longsys Electronics   | 1         | 0.64%   |
| Realtek Semiconductor          | 1         | 0.64%   |
| Marvell Technology Group       | 1         | 0.64%   |
| INNOGRIT                       | 1         | 0.64%   |
| Biwin Storage Technology       | 1         | 0.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 8.48%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 5.45%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 4.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 4.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 3.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 3.64%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 3.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.42%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 2.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 2.42%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 2.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 2.42%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.82%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 3         | 1.82%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.82%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 1.21%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 1.21%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 1.21%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.21%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 1.21%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 1.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.21%   |
| Intel SSD 660P Series                                                          | 2         | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.21%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.21%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                          | 1         | 0.61%   |
| Toshiba America Info Systems XG3 NVMe SSD Controller                           | 1         | 0.61%   |
| Silicon Motion Non-Volatile memory controller                                  | 1         | 0.61%   |
| Shenzhen Longsys Non-Volatile memory controller                                | 1         | 0.61%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.61%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.61%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 96        | 59.26%  |
| NVMe | 48        | 29.63%  |
| RAID | 15        | 9.26%   |
| IDE  | 3         | 1.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 113       | 85.61%  |
| AMD    | 19        | 14.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 4         | 3.03%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 3         | 2.27%   |
| Intel Core i5-2435M CPU @ 2.40GHz               | 3         | 2.27%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 2.27%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 2         | 1.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 2         | 1.52%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 2         | 1.52%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz              | 2         | 1.52%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 2         | 1.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 1.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 2         | 1.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 2         | 1.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 2         | 1.52%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 1.52%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 1.52%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 2         | 1.52%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 2         | 1.52%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 1.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.52%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 1.52%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz     | 1         | 0.76%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 0.76%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 0.76%   |
| Intel Pentium CPU 6805 @ 1.10GHz                | 1         | 0.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.76%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 0.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 0.76%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 0.76%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 0.76%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.76%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz              | 1         | 0.76%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz              | 1         | 0.76%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 1         | 0.76%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 1         | 0.76%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 0.76%   |
| Intel Core i7-3720QM CPU @ 2.60GHz              | 1         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 36        | 27.27%  |
| Intel Core i7           | 27        | 20.45%  |
| Other                   | 17        | 12.88%  |
| Intel Core i3           | 10        | 7.58%   |
| Intel Core 2 Duo        | 9         | 6.82%   |
| Intel Celeron           | 8         | 6.06%   |
| AMD Ryzen 7             | 5         | 3.79%   |
| AMD Ryzen 5             | 4         | 3.03%   |
| Intel Pentium           | 3         | 2.27%   |
| Intel Pentium Silver    | 2         | 1.52%   |
| AMD Athlon              | 2         | 1.52%   |
| AMD A4                  | 2         | 1.52%   |
| AMD A12                 | 2         | 1.52%   |
| Intel Pentium Dual-Core | 1         | 0.76%   |
| AMD Ryzen 5 PRO         | 1         | 0.76%   |
| AMD Ryzen 3             | 1         | 0.76%   |
| AMD A8                  | 1         | 0.76%   |
| AMD A6                  | 1         | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 72        | 54.55%  |
| 4      | 41        | 31.06%  |
| 8      | 8         | 6.06%   |
| 6      | 4         | 3.03%   |
| 10     | 2         | 1.52%   |
| 1      | 2         | 1.52%   |
| 14     | 1         | 0.76%   |
| 12     | 1         | 0.76%   |
| 5      | 1         | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 132       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 103       | 78.03%  |
| 1      | 29        | 21.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 132       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 106       | 79.1%   |
| 0x806ec    | 3         | 2.24%   |
| 0x806c1    | 3         | 2.24%   |
| 0x906a4    | 2         | 1.49%   |
| 0x806d1    | 2         | 1.49%   |
| 0x706e5    | 2         | 1.49%   |
| 0x206a7    | 2         | 1.49%   |
| 0x0a50000c | 2         | 1.49%   |
| 0x906e9    | 1         | 0.75%   |
| 0x906a3    | 1         | 0.75%   |
| 0x806eb    | 1         | 0.75%   |
| 0x806ea    | 1         | 0.75%   |
| 0x706a8    | 1         | 0.75%   |
| 0x40661    | 1         | 0.75%   |
| 0x40651    | 1         | 0.75%   |
| 0x1067a    | 1         | 0.75%   |
| 0x10676    | 1         | 0.75%   |
| 0x0a50000d | 1         | 0.75%   |
| 0x08600106 | 1         | 0.75%   |
| 0x0600611a | 1         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 17        | 12.88%  |
| Haswell          | 15        | 11.36%  |
| IvyBridge        | 13        | 9.85%   |
| TigerLake        | 10        | 7.58%   |
| Penryn           | 10        | 7.58%   |
| Skylake          | 9         | 6.82%   |
| SandyBridge      | 9         | 6.82%   |
| Goldmont plus    | 7         | 5.3%    |
| Zen+             | 5         | 3.79%   |
| Westmere         | 5         | 3.79%   |
| Unknown          | 5         | 3.79%   |
| IceLake          | 4         | 3.03%   |
| Broadwell        | 4         | 3.03%   |
| Zen 3            | 3         | 2.27%   |
| Zen 2            | 3         | 2.27%   |
| Silvermont       | 3         | 2.27%   |
| Excavator        | 3         | 2.27%   |
| Alderlake Hybrid | 3         | 2.27%   |
| Puma             | 2         | 1.52%   |
| Piledriver       | 1         | 0.76%   |
| Core             | 1         | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 103       | 63.98%  |
| Nvidia | 33        | 20.5%   |
| AMD    | 25        | 15.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 13        | 7.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 7         | 4.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 3.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 6         | 3.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 6         | 3.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 5         | 3.03%   |
| Intel Core Processor Integrated Graphics Controller                                   | 5         | 3.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 5         | 3.03%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 4         | 2.42%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 2.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 4         | 2.42%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 1.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 3         | 1.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 1.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 3         | 1.82%   |
| Intel HD Graphics 620                                                                 | 3         | 1.82%   |
| Intel HD Graphics 530                                                                 | 3         | 1.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 1.82%   |
| AMD Renoir                                                                            | 3         | 1.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 3         | 1.82%   |
| Nvidia MCP89 [GeForce 320M]                                                           | 2         | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1.21%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 2         | 1.21%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 2         | 1.21%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 1.21%   |
| Nvidia C79 [GeForce 9400M]                                                            | 2         | 1.21%   |
| Intel UHD Graphics 620                                                                | 2         | 1.21%   |
| Intel HD Graphics 630                                                                 | 2         | 1.21%   |
| Intel HD Graphics 5500                                                                | 2         | 1.21%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 2         | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 1.21%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 1.21%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 2         | 1.21%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.21%   |
| AMD Lucienne                                                                          | 2         | 1.21%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.61%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 0.61%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 0.61%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 75        | 56.82%  |
| Intel + Nvidia | 23        | 17.42%  |
| 1 x AMD        | 17        | 12.88%  |
| 1 x Nvidia     | 7         | 5.3%    |
| Intel + AMD    | 4         | 3.03%   |
| 2 x AMD        | 2         | 1.52%   |
| AMD + Nvidia   | 2         | 1.52%   |
| Other          | 1         | 0.76%   |
| 2 x Nvidia     | 1         | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 124       | 93.94%  |
| Proprietary | 5         | 3.79%   |
| Unknown     | 3         | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 95.45%  |
| 0.01-0.5   | 3         | 2.27%   |
| 1.01-2.0   | 2         | 1.52%   |
| 3.01-4.0   | 1         | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 19.15%  |
| LG Display              | 22        | 15.6%   |
| BOE                     | 19        | 13.48%  |
| Apple                   | 19        | 13.48%  |
| Chimei Innolux          | 15        | 10.64%  |
| Samsung Electronics     | 9         | 6.38%   |
| Sharp                   | 5         | 3.55%   |
| Dell                    | 4         | 2.84%   |
| PANDA                   | 3         | 2.13%   |
| Lenovo                  | 3         | 2.13%   |
| Goldstar                | 3         | 2.13%   |
| Chi Mei Optoelectronics | 2         | 1.42%   |
| Toshiba                 | 1         | 0.71%   |
| Philips                 | 1         | 0.71%   |
| Panasonic               | 1         | 0.71%   |
| Mi                      | 1         | 0.71%   |
| LG Philips              | 1         | 0.71%   |
| InfoVision              | 1         | 0.71%   |
| Hewlett-Packard         | 1         | 0.71%   |
| CPT                     | 1         | 0.71%   |
| Cisco                   | 1         | 0.71%   |
| BenQ                    | 1         | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 3         | 2.1%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 3         | 2.1%    |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 2         | 1.4%    |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch           | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch       | 2         | 1.4%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                  | 2         | 1.4%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                  | 2         | 1.4%    |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                   | 2         | 1.4%    |
| Apple LCD Monitor Color LCD 2880x1800                                  | 2         | 1.4%    |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch                 | 2         | 1.4%    |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                 | 2         | 1.4%    |
| Toshiba ScreenXpert TSB8888 1080x2160                                  | 1         | 0.7%    |
| Sharp LCD Monitor SHP151C 1920x1080 344x194mm 15.5-inch                | 1         | 0.7%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.7%    |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                | 1         | 0.7%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.7%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 1         | 0.7%    |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch      | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch   | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch   | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1         | 0.7%    |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 1         | 0.7%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 1         | 0.7%    |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch                | 1         | 0.7%    |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 0.7%    |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 1         | 0.7%    |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1         | 0.7%    |
| LG Philips LCD Monitor LPLB900 1280x800 330x210mm 15.4-inch            | 1         | 0.7%    |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch            | 1         | 0.7%    |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch            | 1         | 0.7%    |
| LG Display LCD Monitor LGD04A2 1920x1080 276x156mm 12.5-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch            | 1         | 0.7%    |
| LG Display LCD Monitor LGD0419 2560x1440 310x174mm 14.0-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch           | 1         | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 60        | 44.78%  |
| 1366x768 (WXGA)   | 38        | 28.36%  |
| 1280x800 (WXGA)   | 10        | 7.46%   |
| 3840x2160 (4K)    | 4         | 2.99%   |
| 2880x1800         | 4         | 2.99%   |
| 1600x900 (HD+)    | 4         | 2.99%   |
| 1440x900 (WXGA+)  | 4         | 2.99%   |
| 1920x1200 (WUXGA) | 3         | 2.24%   |
| 2560x1600         | 2         | 1.49%   |
| 1280x1024 (SXGA)  | 2         | 1.49%   |
| 3840x2400         | 1         | 0.75%   |
| 3440x1440         | 1         | 0.75%   |
| 2560x1440 (QHD)   | 1         | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 62        | 43.36%  |
| 13      | 26        | 18.18%  |
| 14      | 16        | 11.19%  |
| 17      | 11        | 7.69%   |
| 27      | 4         | 2.8%    |
| 11      | 4         | 2.8%    |
| 21      | 3         | 2.1%    |
| 12      | 3         | 2.1%    |
| 24      | 2         | 1.4%    |
| Unknown | 2         | 1.4%    |
| 84      | 1         | 0.7%    |
| 65      | 1         | 0.7%    |
| 60      | 1         | 0.7%    |
| 34      | 1         | 0.7%    |
| 31      | 1         | 0.7%    |
| 26      | 1         | 0.7%    |
| 23      | 1         | 0.7%    |
| 19      | 1         | 0.7%    |
| 18      | 1         | 0.7%    |
| 16      | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 83        | 58.04%  |
| 201-300     | 27        | 18.88%  |
| 351-400     | 14        | 9.79%   |
| 501-600     | 8         | 5.59%   |
| 401-500     | 4         | 2.8%    |
| 1001-1500   | 2         | 1.4%    |
| Unknown     | 2         | 1.4%    |
| 701-800     | 1         | 0.7%    |
| 601-700     | 1         | 0.7%    |
| 1501-2000   | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 103       | 78.03%  |
| 16/10   | 23        | 17.42%  |
| Unknown | 2         | 1.52%   |
| 5/4     | 1         | 0.76%   |
| 4/3     | 1         | 0.76%   |
| 3/2     | 1         | 0.76%   |
| 21/9    | 1         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 63        | 44.37%  |
| 81-90          | 28        | 19.72%  |
| 71-80          | 14        | 9.86%   |
| 121-130        | 8         | 5.63%   |
| 301-350        | 5         | 3.52%   |
| 51-60          | 4         | 2.82%   |
| 201-250        | 4         | 2.82%   |
| More than 1000 | 3         | 2.11%   |
| 61-70          | 3         | 2.11%   |
| 131-140        | 3         | 2.11%   |
| 351-500        | 2         | 1.41%   |
| Unknown        | 2         | 1.41%   |
| 251-300        | 1         | 0.7%    |
| 151-200        | 1         | 0.7%    |
| 141-150        | 1         | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 64        | 45.71%  |
| 101-120       | 45        | 32.14%  |
| 51-100        | 14        | 10%     |
| 161-240       | 12        | 8.57%   |
| 1-50          | 2         | 1.43%   |
| Unknown       | 2         | 1.43%   |
| More than 240 | 1         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 114       | 86.36%  |
| 2     | 14        | 10.61%  |
| 0     | 3         | 2.27%   |
| 3     | 1         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 60        | 29.85%  |
| Intel                             | 60        | 29.85%  |
| Broadcom                          | 27        | 13.43%  |
| Qualcomm Atheros                  | 23        | 11.44%  |
| Ralink Technology                 | 4         | 1.99%   |
| Broadcom Limited                  | 4         | 1.99%   |
| Samsung Electronics               | 2         | 1%      |
| Qualcomm                          | 2         | 1%      |
| Nvidia                            | 2         | 1%      |
| NetGear                           | 2         | 1%      |
| Marvell Technology Group          | 2         | 1%      |
| Huawei Technologies               | 2         | 1%      |
| Ericsson Business Mobile Networks | 2         | 1%      |
| Dell                              | 2         | 1%      |
| ASIX Electronics                  | 2         | 1%      |
| ZTE WCDMA Technologies MSM        | 1         | 0.5%    |
| Xiaomi                            | 1         | 0.5%    |
| TP-Link                           | 1         | 0.5%    |
| Sierra Wireless                   | 1         | 0.5%    |
| Motorola PCS                      | 1         | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 13.78%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 3.94%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 3.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 3.15%   |
| Intel Wireless 8260                                               | 7         | 2.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 2.36%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 2.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.97%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.57%   |
| Intel Wireless 7260                                               | 4         | 1.57%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.18%   |
| Intel Wireless 7265                                               | 3         | 1.18%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.18%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 1.18%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 3         | 1.18%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 1.18%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.79%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 2         | 0.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.79%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.79%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 2         | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.79%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.79%   |
| Intel Wireless-AC 9260                                            | 2         | 0.79%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.79%   |
| Intel Wireless 3165                                               | 2         | 0.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 58        | 40.56%  |
| Realtek Semiconductor             | 27        | 18.88%  |
| Broadcom                          | 26        | 18.18%  |
| Qualcomm Atheros                  | 18        | 12.59%  |
| Ralink Technology                 | 4         | 2.8%    |
| Broadcom Limited                  | 3         | 2.1%    |
| Qualcomm                          | 2         | 1.4%    |
| TP-Link                           | 1         | 0.7%    |
| Sierra Wireless                   | 1         | 0.7%    |
| NetGear                           | 1         | 0.7%    |
| Ericsson Business Mobile Networks | 1         | 0.7%    |
| Dell                              | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 6.94%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 6.25%   |
| Intel Wireless 8260                                            | 7         | 4.86%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 4.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 3.47%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 3.47%   |
| Intel Wireless 7260                                            | 4         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 2.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 2.08%   |
| Intel Wireless 7265                                            | 3         | 2.08%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 2.08%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 3         | 2.08%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 2.08%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 1.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.39%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.39%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 2         | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 1.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.39%   |
| Intel Wireless-AC 9260                                         | 2         | 1.39%   |
| Intel Wireless 8265 / 8275                                     | 2         | 1.39%   |
| Intel Wireless 3165                                            | 2         | 1.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.39%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 1.39%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.39%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.39%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.39%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 1.39%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.69%   |
| Sierra Wireless EM7455                                         | 1         | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 50        | 46.73%  |
| Intel                      | 24        | 22.43%  |
| Broadcom                   | 10        | 9.35%   |
| Qualcomm Atheros           | 9         | 8.41%   |
| Samsung Electronics        | 2         | 1.87%   |
| Nvidia                     | 2         | 1.87%   |
| Marvell Technology Group   | 2         | 1.87%   |
| Huawei Technologies        | 2         | 1.87%   |
| ASIX Electronics           | 2         | 1.87%   |
| ZTE WCDMA Technologies MSM | 1         | 0.93%   |
| Xiaomi                     | 1         | 0.93%   |
| NetGear                    | 1         | 0.93%   |
| Broadcom Limited           | 1         | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 32.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 7.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 5.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 3.74%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 3.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 3.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.87%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.87%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.87%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.87%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.87%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.87%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.87%   |
| ZTE WCDMA MSM Android                                             | 1         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.93%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.93%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.93%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.93%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.93%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.93%   |
| NetGear LB1120-100NAS                                             | 1         | 0.93%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.93%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.93%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.93%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.93%   |
| Huawei WLZ-AN00                                                   | 1         | 0.93%   |
| Huawei E353/E3131                                                 | 1         | 0.93%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.93%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.93%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 132       | 56.17%  |
| Ethernet | 100       | 42.55%  |
| Modem    | 2         | 0.85%   |
| Unknown  | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 104       | 77.61%  |
| Ethernet | 30        | 22.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 91        | 68.94%  |
| 1     | 39        | 29.55%  |
| 3     | 1         | 0.76%   |
| 0     | 1         | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 95        | 71.43%  |
| Yes  | 38        | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 42.74%  |
| Realtek Semiconductor           | 18        | 15.38%  |
| Apple                           | 18        | 15.38%  |
| Qualcomm Atheros Communications | 7         | 5.98%   |
| Broadcom                        | 6         | 5.13%   |
| Lite-On Technology              | 5         | 4.27%   |
| IMC Networks                    | 5         | 4.27%   |
| Foxconn / Hon Hai               | 5         | 4.27%   |
| Toshiba                         | 1         | 0.85%   |
| Hewlett-Packard                 | 1         | 0.85%   |
| Askey Computer                  | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 17        | 14.53%  |
| Intel AX201 Bluetooth                              | 12        | 10.26%  |
| Apple Bluetooth Host Controller                    | 12        | 10.26%  |
| Realtek  Bluetooth 4.2 Adapter                     | 10        | 8.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 8         | 6.84%   |
| Realtek Bluetooth Radio                            | 7         | 5.98%   |
| Apple Bluetooth USB Host Controller                | 5         | 4.27%   |
| Qualcomm Atheros  Bluetooth Device                 | 3         | 2.56%   |
| Lite-On Bluetooth Device                           | 3         | 2.56%   |
| Intel AX200 Bluetooth                              | 3         | 2.56%   |
| IMC Networks Bluetooth Radio                       | 3         | 2.56%   |
| Foxconn / Hon Hai Bluetooth Device                 | 3         | 2.56%   |
| Qualcomm Atheros AR3011 Bluetooth                  | 2         | 1.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 2         | 1.71%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 2         | 1.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter   | 2         | 1.71%   |
| Intel Bluetooth Device                             | 2         | 1.71%   |
| Intel AX210 Bluetooth                              | 2         | 1.71%   |
| Broadcom BCM43142A0 Bluetooth Device               | 2         | 1.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 2         | 1.71%   |
| Toshiba Bluetooth Device                           | 1         | 0.85%   |
| Realtek RTL8821A Bluetooth                         | 1         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 0.85%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device       | 1         | 0.85%   |
| IMC Networks Bluetooth                             | 1         | 0.85%   |
| IMC Networks BCM20702A0                            | 1         | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 0.85%   |
| Foxconn / Hon Hai BCM43142A0                       | 1         | 0.85%   |
| Foxconn / Hon Hai BCM20702A0                       | 1         | 0.85%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 0.85%   |
| Broadcom BCM2045B (BDC-2.1)                        | 1         | 0.85%   |
| Askey Bluetooth Device                             | 1         | 0.85%   |
| Apple Bluetooth HCI                                | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 109       | 67.7%   |
| AMD                    | 23        | 14.29%  |
| Nvidia                 | 19        | 11.8%   |
| Logitech               | 2         | 1.24%   |
| C-Media Electronics    | 2         | 1.24%   |
| Realtek Semiconductor  | 1         | 0.62%   |
| Microsoft              | 1         | 0.62%   |
| Hewlett-Packard        | 1         | 0.62%   |
| GN Netcom              | 1         | 0.62%   |
| Generalplus Technology | 1         | 0.62%   |
| Dell                   | 1         | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14        | 7.18%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 6.67%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 5.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 5.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 4.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 4.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 3.59%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 3.59%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 3.08%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 3.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 2.05%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.05%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 2.05%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 2.05%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.54%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.54%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.54%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.54%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.54%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 1.03%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.03%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.03%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.03%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 1.03%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.51%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.51%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.51%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.51%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 40.63%  |
| Micron Technology   | 8         | 25%     |
| SK hynix            | 6         | 18.75%  |
| Ramaxel Technology  | 1         | 3.13%   |
| pqi                 | 1         | 3.13%   |
| GSkill              | 1         | 3.13%   |
| Crucial             | 1         | 3.13%   |
| Unknown             | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s    | 2         | 6.25%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s         | 2         | 6.25%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                  | 1         | 3.13%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 3.13%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s        | 1         | 3.13%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s       | 1         | 3.13%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 3.13%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 3.13%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s    | 1         | 3.13%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s             | 1         | 3.13%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                  | 1         | 3.13%   |
| Samsung RAM M471B5273EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 3.13%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 1         | 3.13%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s   | 1         | 3.13%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 3.13%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 3.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 3.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 1         | 3.13%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s  | 1         | 3.13%   |
| Ramaxel RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1         | 3.13%   |
| pqi RAM Module 2GB SODIMM DDR2 667MT/s                        | 1         | 3.13%   |
| Micron RAM MT53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 3.13%   |
| Micron RAM Module 8GB SODIMM DDR4 2667MT/s                    | 1         | 3.13%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 1         | 3.13%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s          | 1         | 3.13%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 1         | 3.13%   |
| Micron RAM 16ATF4G64HZ-3G2E2 32GB SODIMM DDR4 3200MT/s        | 1         | 3.13%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s         | 1         | 3.13%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 1         | 3.13%   |
| Unknown                                                       | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 16        | 57.14%  |
| DDR3   | 5         | 17.86%  |
| LPDDR4 | 4         | 14.29%  |
| LPDDR3 | 1         | 3.57%   |
| DDR5   | 1         | 3.57%   |
| DDR2   | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 21        | 72.41%  |
| Row Of Chips | 8         | 27.59%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 58.62%  |
| 4096  | 6         | 20.69%  |
| 16384 | 3         | 10.34%  |
| 2048  | 2         | 6.9%    |
| 32768 | 1         | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 10        | 34.48%  |
| 2667  | 6         | 20.69%  |
| 4267  | 4         | 13.79%  |
| 1600  | 3         | 10.34%  |
| 4800  | 1         | 3.45%   |
| 2400  | 1         | 3.45%   |
| 2133  | 1         | 3.45%   |
| 1333  | 1         | 3.45%   |
| 800   | 1         | 3.45%   |
| 667   | 1         | 3.45%   |

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
| Chicony Electronics                    | 23        | 18.85%  |
| Apple                                  | 16        | 13.11%  |
| Quanta                                 | 14        | 11.48%  |
| IMC Networks                           | 12        | 9.84%   |
| Realtek Semiconductor                  | 9         | 7.38%   |
| Microdia                               | 9         | 7.38%   |
| Bison Electronics                      | 7         | 5.74%   |
| Sunplus Innovation Technology          | 5         | 4.1%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.28%   |
| Syntek                                 | 2         | 1.64%   |
| SunplusIT                              | 2         | 1.64%   |
| Luxvisions Innotech Limited            | 2         | 1.64%   |
| Lenovo                                 | 2         | 1.64%   |
| Alcor Micro                            | 2         | 1.64%   |
| Acer                                   | 2         | 1.64%   |
| Suyin                                  | 1         | 0.82%   |
| Sunplus Technology                     | 1         | 0.82%   |
| Sonix Technology                       | 1         | 0.82%   |
| Silicon Motion                         | 1         | 0.82%   |
| Shine-optics                           | 1         | 0.82%   |
| Samsung Electronics                    | 1         | 0.82%   |
| Logitech                               | 1         | 0.82%   |
| Lite-On Technology                     | 1         | 0.82%   |
| Intel                                  | 1         | 0.82%   |
| Cubeternet                             | 1         | 0.82%   |
| Cisco Systems                          | 1         | 0.82%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 6         | 4.88%   |
| Apple FaceTime HD Camera                         | 6         | 4.88%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 5         | 4.07%   |
| Microdia Integrated_Webcam_HD                    | 4         | 3.25%   |
| Realtek Integrated_Webcam_HD                     | 3         | 2.44%   |
| IMC Networks USB2.0 HD UVC WebCam                | 3         | 2.44%   |
| IMC Networks Integrated Camera                   | 3         | 2.44%   |
| Apple Built-in iSight                            | 3         | 2.44%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 1.63%   |
| Quanta USB2.0 HD UVC WebCam                      | 2         | 1.63%   |
| Quanta HP TrueVision HD Camera                   | 2         | 1.63%   |
| Quanta HP HD Camera                              | 2         | 1.63%   |
| Quanta HD Webcam                                 | 2         | 1.63%   |
| Quanta HD Camera                                 | 2         | 1.63%   |
| Microdia Integrated Webcam                       | 2         | 1.63%   |
| IMC Networks HD Camera                           | 2         | 1.63%   |
| Chicony HP Webcam                                | 2         | 1.63%   |
| Chicony HP TrueVision HD Camera                  | 2         | 1.63%   |
| Chicony HP Truevision HD                         | 2         | 1.63%   |
| Chicony HD WebCam                                | 2         | 1.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.63%   |
| Bison Lenovo Integrated Webcam                   | 2         | 1.63%   |
| Apple FaceTime Camera                            | 2         | 1.63%   |
| Syntek Lenovo EasyCamera                         | 1         | 0.81%   |
| Syntek EasyCamera                                | 1         | 0.81%   |
| Suyin Acer HD Crystal Eye webcam                 | 1         | 0.81%   |
| SunplusIT HD Camera                              | 1         | 0.81%   |
| SunplusIT HBT Camera                             | 1         | 0.81%   |
| Sunplus 1.3M HD WebCam                           | 1         | 0.81%   |
| Sunplus HD WebCam                                | 1         | 0.81%   |
| Sunplus Dell E5570 integrated webcam             | 1         | 0.81%   |
| Sunplus Camera                                   | 1         | 0.81%   |
| Sonix HP Webcam-101                              | 1         | 0.81%   |
| Silicon Motion WebCam SC-03FFL11939N             | 1         | 0.81%   |
| Shine-optics USB2.0 HD UVC WebCam                | 1         | 0.81%   |
| Samsung Galaxy series, misc. (MTP mode)          | 1         | 0.81%   |
| Realtek USB Camera                               | 1         | 0.81%   |
| Realtek HP Webcam                                | 1         | 0.81%   |
| Realtek HP "Truevision HD" laptop camera         | 1         | 0.81%   |
| Realtek EasyCamera                               | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 37.04%  |
| Shenzhen Goodix Technology | 7         | 25.93%  |
| Synaptics                  | 4         | 14.81%  |
| Elan Microelectronics      | 3         | 11.11%  |
| Upek                       | 1         | 3.7%    |
| LighTuning Technology      | 1         | 3.7%    |
| AuthenTec                  | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 22.22%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 7.41%   |
| Elan ELAN:Fingerprint                                                      | 2         | 7.41%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.7%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 3.7%    |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 3.7%    |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 3.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.7%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 3.7%    |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.7%    |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 3.7%    |
| LighTuning Fingerprint Reader                                              | 1         | 3.7%    |
| Elan ELAN:ARM-M4                                                           | 1         | 3.7%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 42.86%  |
| Upek        | 2         | 28.57%  |
| O2 Micro    | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 28.57%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 78        | 59.09%  |
| 1     | 43        | 32.58%  |
| 2     | 10        | 7.58%   |
| 3     | 1         | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 26        | 40%     |
| Net/wireless          | 12        | 18.46%  |
| Multimedia controller | 9         | 13.85%  |
| Graphics card         | 9         | 13.85%  |
| Chipcard              | 7         | 10.77%  |
| Storage               | 1         | 1.54%   |
| Net/ethernet          | 1         | 1.54%   |

