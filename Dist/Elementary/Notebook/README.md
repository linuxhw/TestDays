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

Total: 1385

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Packard Be... | EasyNote LS11HR             | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| HP            | EliteBook 8460p             | [03dfc41744](https://linux-hardware.org/?probe=03dfc41744) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [f97643f94c](https://linux-hardware.org/?probe=f97643f94c) | Feb 16, 2022 |
| Acer          | Aspire A315-35              | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| Acer          | Swift SF314-56              | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | X540SA                      | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| ASUSTek       | E402NA                      | [ec217b7bd1](https://linux-hardware.org/?probe=ec217b7bd1) | Feb 13, 2022 |
| Dell          | Precision 7720              | [e5c37c787f](https://linux-hardware.org/?probe=e5c37c787f) | Feb 13, 2022 |
| Google        | Lulu                        | [5b81b703ea](https://linux-hardware.org/?probe=5b81b703ea) | Feb 13, 2022 |
| Sony          | SVE15115EN                  | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| Dell          | Inspiron 1764               | [3b22e2edbb](https://linux-hardware.org/?probe=3b22e2edbb) | Feb 11, 2022 |
| Apple         | MacBookAir7,1               | [39d4765770](https://linux-hardware.org/?probe=39d4765770) | Feb 11, 2022 |
| Apple         | MacBookAir4,2               | [113add3cba](https://linux-hardware.org/?probe=113add3cba) | Feb 10, 2022 |
| Apple         | MacBookAir4,2               | [accb1d4232](https://linux-hardware.org/?probe=accb1d4232) | Feb 09, 2022 |
| Timi          | TM1613                      | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| Lenovo        | ThinkPad T440p 20AN006NU... | [d4fccf53c8](https://linux-hardware.org/?probe=d4fccf53c8) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| Lenovo        | ThinkPad E550 20DF0040US    | [ca4c420e00](https://linux-hardware.org/?probe=ca4c420e00) | Feb 07, 2022 |
| Apple         | MacBookPro6,2               | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Timi          | TM1613                      | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| HP            | 240 G4                      | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| Panasonic     | CF-31SBLJGDM                | [488b80a942](https://linux-hardware.org/?probe=488b80a942) | Feb 03, 2022 |
| Dell          | Inspiron 15-3567            | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| ASUSTek       | K95VJ                       | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Acer          | Aspire S3-391               | [87788239d2](https://linux-hardware.org/?probe=87788239d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| HP            | Pavilion 13 x360 PC         | [d2bcb368c1](https://linux-hardware.org/?probe=d2bcb368c1) | Feb 02, 2022 |
| PIPO          | Cherry Trail CR             | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | [34a7deb292](https://linux-hardware.org/?probe=34a7deb292) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | [add488b5fe](https://linux-hardware.org/?probe=add488b5fe) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Dell          | XPS 15 9500                 | [ac78806c22](https://linux-hardware.org/?probe=ac78806c22) | Jan 30, 2022 |
| Dell          | XPS 15 9500                 | [657fbc0f6d](https://linux-hardware.org/?probe=657fbc0f6d) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Razer         | Blade Stealth               | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| HP            | Pavilion dv5                | [62a18fa26b](https://linux-hardware.org/?probe=62a18fa26b) | Jan 26, 2022 |
| ASUSTek       | X555LN                      | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| Dell          | Latitude 5420               | [3aad8f46c6](https://linux-hardware.org/?probe=3aad8f46c6) | Jan 24, 2022 |
| Lenovo        | G550 20023                  | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| Apple         | MacBook5,1                  | [79cf3b66a3](https://linux-hardware.org/?probe=79cf3b66a3) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| HP            | EliteBook Folio 1040 G2     | [4e3ef7a5a7](https://linux-hardware.org/?probe=4e3ef7a5a7) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [92991c028e](https://linux-hardware.org/?probe=92991c028e) | Jan 22, 2022 |
| Apple         | MacBookPro8,3               | [fb5a640b14](https://linux-hardware.org/?probe=fb5a640b14) | Jan 22, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [5007cce576](https://linux-hardware.org/?probe=5007cce576) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fd85b85b8](https://linux-hardware.org/?probe=7fd85b85b8) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2c01bf53cb](https://linux-hardware.org/?probe=2c01bf53cb) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK S760               | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| HP            | ProBook 4540s               | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Apple         | MacBookPro8,2               | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| Dell          | Latitude E5400              | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| HP            | ProBook 4430s               | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| MSI           | GE60 2PE                    | [d74dcddae6](https://linux-hardware.org/?probe=d74dcddae6) | Jan 13, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| ASUSTek       | GL502VS                     | [feb64c0933](https://linux-hardware.org/?probe=feb64c0933) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| ASUSTek       | UX31A                       | [afe25bb395](https://linux-hardware.org/?probe=afe25bb395) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [7ba01d7327](https://linux-hardware.org/?probe=7ba01d7327) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Dell          | Inspiron N5110              | [172b005a76](https://linux-hardware.org/?probe=172b005a76) | Jan 07, 2022 |
| Dell          | Latitude 5420               | [ab3973e74b](https://linux-hardware.org/?probe=ab3973e74b) | Jan 07, 2022 |
| Dell          | Latitude 5420               | [517adf10a8](https://linux-hardware.org/?probe=517adf10a8) | Jan 06, 2022 |
| Star Labs     | StarBook                    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| Dell          | Inspiron N5110              | [a0a13869ab](https://linux-hardware.org/?probe=a0a13869ab) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Acer          | Aspire XXXX                 | [d52d9dc2bd](https://linux-hardware.org/?probe=d52d9dc2bd) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| Acer          | Aspire XXXX                 | [b5d8962bbc](https://linux-hardware.org/?probe=b5d8962bbc) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Timi          | TM1613                      | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| ASUSTek       | E202SA                      | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| Wortmann      | 1220729_1470271             | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fa46d4f41a](https://linux-hardware.org/?probe=fa46d4f41a) | Dec 28, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [22fb358e03](https://linux-hardware.org/?probe=22fb358e03) | Dec 28, 2021 |
| Dell          | Latitude 3580               | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Apple         | MacBook2,1                  | [82483b42e2](https://linux-hardware.org/?probe=82483b42e2) | Dec 21, 2021 |
| Apple         | MacBook2,1                  | [197a4e0280](https://linux-hardware.org/?probe=197a4e0280) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| Dell          | Inspiron 5555               | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Lenovo        | V14-ADA 82C6                | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5627f53d66](https://linux-hardware.org/?probe=5627f53d66) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |
| Dell          | Inspiron 1764               | [a8abf45979](https://linux-hardware.org/?probe=a8abf45979) | Dec 13, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [8280287583](https://linux-hardware.org/?probe=8280287583) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [6f114c2528](https://linux-hardware.org/?probe=6f114c2528) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Dell          | XPS 15 9570                 | [40b1d83a44](https://linux-hardware.org/?probe=40b1d83a44) | Dec 11, 2021 |
| Star Labs     | StarBook                    | [e9414e6bc4](https://linux-hardware.org/?probe=e9414e6bc4) | Dec 09, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [31e281d91b](https://linux-hardware.org/?probe=31e281d91b) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [d32c954439](https://linux-hardware.org/?probe=d32c954439) | Dec 09, 2021 |
| Google        | Cyan                        | [f49c895086](https://linux-hardware.org/?probe=f49c895086) | Dec 08, 2021 |
| Dell          | Latitude E5420              | [e9fdf365b6](https://linux-hardware.org/?probe=e9fdf365b6) | Dec 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ed493cd76f](https://linux-hardware.org/?probe=ed493cd76f) | Dec 05, 2021 |
| HUAWEI        | MACHD-WXX9                  | [970669192e](https://linux-hardware.org/?probe=970669192e) | Dec 05, 2021 |
| HP            | G62                         | [6e055d5b6b](https://linux-hardware.org/?probe=6e055d5b6b) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9143857ca7](https://linux-hardware.org/?probe=9143857ca7) | Dec 05, 2021 |
| ASUSTek       | FX503VD                     | [6b5bd7a6d3](https://linux-hardware.org/?probe=6b5bd7a6d3) | Dec 05, 2021 |
| Acer          | Aspire R3-131T              | [3fd499b264](https://linux-hardware.org/?probe=3fd499b264) | Dec 04, 2021 |
| Packard Be... | EasyNote LS11HR             | [d58c199fda](https://linux-hardware.org/?probe=d58c199fda) | Dec 04, 2021 |
| HP            | ZBook 15 G5                 | [b42c2359f4](https://linux-hardware.org/?probe=b42c2359f4) | Dec 03, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| Acer          | Aspire 5750G                | [0131556200](https://linux-hardware.org/?probe=0131556200) | Dec 01, 2021 |
| Samsung       | 550XDA                      | [30c24b17f4](https://linux-hardware.org/?probe=30c24b17f4) | Dec 01, 2021 |
| HP            | EliteBook 2760p             | [d13f27ae75](https://linux-hardware.org/?probe=d13f27ae75) | Nov 30, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [5052f33272](https://linux-hardware.org/?probe=5052f33272) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| Google        | Kip                         | [958c198a17](https://linux-hardware.org/?probe=958c198a17) | Nov 29, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [26cba9b931](https://linux-hardware.org/?probe=26cba9b931) | Nov 29, 2021 |
| Toshiba       | Satellite L750              | [0a4f8ff5f1](https://linux-hardware.org/?probe=0a4f8ff5f1) | Nov 28, 2021 |
| HP            | Laptop 15s-fq0xxx           | [8b1d090289](https://linux-hardware.org/?probe=8b1d090289) | Nov 28, 2021 |
| HP            | Pavilion dm4                | [e2c582f687](https://linux-hardware.org/?probe=e2c582f687) | Nov 28, 2021 |
| HP            | ProBook 4540s               | [b6762448da](https://linux-hardware.org/?probe=b6762448da) | Nov 28, 2021 |
| Notebook      | L140CU                      | [59021b2a31](https://linux-hardware.org/?probe=59021b2a31) | Nov 27, 2021 |
| Toshiba       | Satellite L840              | [6c29b0fc8d](https://linux-hardware.org/?probe=6c29b0fc8d) | Nov 27, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [c8a72fc7e2](https://linux-hardware.org/?probe=c8a72fc7e2) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | [0004bab911](https://linux-hardware.org/?probe=0004bab911) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | [2ef4f4f273](https://linux-hardware.org/?probe=2ef4f4f273) | Nov 26, 2021 |
| Dell          | Inspiron 15-3573            | [04dc1956ff](https://linux-hardware.org/?probe=04dc1956ff) | Nov 26, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [cd408c48d0](https://linux-hardware.org/?probe=cd408c48d0) | Nov 25, 2021 |
| HP            | Pavilion dv7                | [073367afb1](https://linux-hardware.org/?probe=073367afb1) | Nov 25, 2021 |
| Lenovo        | ThinkPad X140e 20BLS0040... | [94b3c73b50](https://linux-hardware.org/?probe=94b3c73b50) | Nov 25, 2021 |
| Apple         | MacBookPro11,2              | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Dell          | System Inspiron N7110       | [fe6a145b19](https://linux-hardware.org/?probe=fe6a145b19) | Nov 24, 2021 |
| Medion        | E7218                       | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [1bfd5fb612](https://linux-hardware.org/?probe=1bfd5fb612) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| Apple         | MacBookPro12,1              | [4f694a8ba3](https://linux-hardware.org/?probe=4f694a8ba3) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| MSI           | GF72 7RE                    | [8e48a382b9](https://linux-hardware.org/?probe=8e48a382b9) | Nov 21, 2021 |
| Alienware     | 17                          | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Dell          | Vostro 3300                 | [04fc886be3](https://linux-hardware.org/?probe=04fc886be3) | Nov 20, 2021 |
| HP            | ProBook 4730s               | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| Schenker      | X170KM-G                    | [79bb8af2a1](https://linux-hardware.org/?probe=79bb8af2a1) | Nov 19, 2021 |
| HP            | Laptop 15-dy2xxx            | [e49d63158f](https://linux-hardware.org/?probe=e49d63158f) | Nov 19, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [38d8d7827f](https://linux-hardware.org/?probe=38d8d7827f) | Nov 18, 2021 |
| HP            | Compaq 6710b (GB893EA#AB... | [47a6a7a44f](https://linux-hardware.org/?probe=47a6a7a44f) | Nov 17, 2021 |
| Unknown       | Unknown                     | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| Acer          | Aspire 5733Z                | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Acer          | Aspire ES1-571              | [60fef7922d](https://linux-hardware.org/?probe=60fef7922d) | Nov 16, 2021 |
| Dell          | XPS 15 9570                 | [74e99a032e](https://linux-hardware.org/?probe=74e99a032e) | Nov 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [58edd5c8e6](https://linux-hardware.org/?probe=58edd5c8e6) | Nov 14, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| Sony          | SVE15115EN                  | [03cbf5ac5a](https://linux-hardware.org/?probe=03cbf5ac5a) | Nov 11, 2021 |
| HP            | Laptop 17-by3xxx            | [beba4da01c](https://linux-hardware.org/?probe=beba4da01c) | Nov 09, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [e43a236a2c](https://linux-hardware.org/?probe=e43a236a2c) | Nov 06, 2021 |
| Quanta        | TW9/SW9                     | [86643edf2a](https://linux-hardware.org/?probe=86643edf2a) | Nov 06, 2021 |
| ASUSTek       | E502SA                      | [28d4f5e427](https://linux-hardware.org/?probe=28d4f5e427) | Nov 04, 2021 |
| ASUSTek       | K75VJ                       | [9c0bccf601](https://linux-hardware.org/?probe=9c0bccf601) | Nov 01, 2021 |
| HCL Infosy... | HCL ME LAPTOP               | [0db069b4f1](https://linux-hardware.org/?probe=0db069b4f1) | Nov 01, 2021 |
| Fujitsu       | LIFEBOOK U747               | [2b68c16c68](https://linux-hardware.org/?probe=2b68c16c68) | Nov 01, 2021 |
| Dell          | Latitude E6410              | [ba51fc9216](https://linux-hardware.org/?probe=ba51fc9216) | Oct 30, 2021 |
| Lenovo        | ThinkPad X230 23259L3       | [801c1d8af3](https://linux-hardware.org/?probe=801c1d8af3) | Oct 27, 2021 |
| MSI           | Modern 14 B4MW              | [a904daf48d](https://linux-hardware.org/?probe=a904daf48d) | Oct 26, 2021 |
| HP            | ProBook 6460b               | [18f27d1f5c](https://linux-hardware.org/?probe=18f27d1f5c) | Oct 25, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| Apple         | MacBookAir7,2               | [4ce4f8ba78](https://linux-hardware.org/?probe=4ce4f8ba78) | Oct 20, 2021 |
| Google        | Setzer                      | [e9536ccbfb](https://linux-hardware.org/?probe=e9536ccbfb) | Oct 19, 2021 |
| Google        | Setzer                      | [3ba49636ef](https://linux-hardware.org/?probe=3ba49636ef) | Oct 19, 2021 |
| Apple         | MacBookAir7,2               | [370b129f3f](https://linux-hardware.org/?probe=370b129f3f) | Oct 16, 2021 |
| Lenovo        | ThinkPad E470 20H10052IG    | [1342d4ce00](https://linux-hardware.org/?probe=1342d4ce00) | Oct 15, 2021 |
| HP            | Pavilion dv6500             | [dd3c7ef3e7](https://linux-hardware.org/?probe=dd3c7ef3e7) | Oct 14, 2021 |
| HP            | Pavilion dv6500             | [c1c77cf91a](https://linux-hardware.org/?probe=c1c77cf91a) | Oct 14, 2021 |
| Acer          | Aspire ES1-311              | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| ASUSTek       | 1215B                       | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| HP            | EliteBook 8440p             | [e5071e6c43](https://linux-hardware.org/?probe=e5071e6c43) | Oct 10, 2021 |
| HP            | ProBook 4530s               | [0a725a0b81](https://linux-hardware.org/?probe=0a725a0b81) | Oct 07, 2021 |
| Apple         | MacBookPro7,1               | [644b3b5b60](https://linux-hardware.org/?probe=644b3b5b60) | Oct 04, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| Dell          | XPS 13 9350                 | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c28700cfda](https://linux-hardware.org/?probe=c28700cfda) | Sep 26, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [fbcf277174](https://linux-hardware.org/?probe=fbcf277174) | Sep 26, 2021 |
| Lenovo        | G50-45 80E3                 | [59224ec754](https://linux-hardware.org/?probe=59224ec754) | Sep 26, 2021 |
| Apple         | MacBookPro10,2              | [25c8a26c00](https://linux-hardware.org/?probe=25c8a26c00) | Sep 24, 2021 |
| Toshiba       | Satellite C870-1H2          | [73615204f8](https://linux-hardware.org/?probe=73615204f8) | Sep 23, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c1b8f22fa6](https://linux-hardware.org/?probe=c1b8f22fa6) | Sep 22, 2021 |
| Dell          | Precision M4800             | [736b482dc3](https://linux-hardware.org/?probe=736b482dc3) | Sep 22, 2021 |
| eMachines     | G525                        | [8e8d037369](https://linux-hardware.org/?probe=8e8d037369) | Sep 21, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [9d25d0c5c7](https://linux-hardware.org/?probe=9d25d0c5c7) | Sep 21, 2021 |
| Lenovo        | ThinkPad W700 2758MVG       | [66c8ecbaa1](https://linux-hardware.org/?probe=66c8ecbaa1) | Sep 20, 2021 |
| Dell          | XPS 13 9350                 | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| Apple         | MacBookPro10,2              | [0e44f5011a](https://linux-hardware.org/?probe=0e44f5011a) | Sep 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3448B... | [2bec640695](https://linux-hardware.org/?probe=2bec640695) | Sep 20, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d2511347b4](https://linux-hardware.org/?probe=d2511347b4) | Sep 19, 2021 |
| HP            | ENVY 15                     | [ba9a8e1d7a](https://linux-hardware.org/?probe=ba9a8e1d7a) | Sep 19, 2021 |
| Lenovo        | V330-15IKB 81AX             | [9d10bffde2](https://linux-hardware.org/?probe=9d10bffde2) | Sep 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS32H00    | [15981e12f3](https://linux-hardware.org/?probe=15981e12f3) | Sep 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS32H00    | [bcdb4d552d](https://linux-hardware.org/?probe=bcdb4d552d) | Sep 18, 2021 |
| HP            | ENVY 15                     | [d2d607895f](https://linux-hardware.org/?probe=d2d607895f) | Sep 18, 2021 |
| Alienware     | 17                          | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Acer          | Aspire V3-572G              | [addf12cb05](https://linux-hardware.org/?probe=addf12cb05) | Sep 16, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [0c206818b9](https://linux-hardware.org/?probe=0c206818b9) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| Dell          | Latitude E7440              | [fc9f25eecb](https://linux-hardware.org/?probe=fc9f25eecb) | Sep 14, 2021 |
| Toshiba       | Satellite P100              | [bc5b605920](https://linux-hardware.org/?probe=bc5b605920) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | [591ba7a77c](https://linux-hardware.org/?probe=591ba7a77c) | Sep 12, 2021 |
| Dell          | Inspiron 3583               | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| Acer          | Aspire R3-131T              | [e872ba288e](https://linux-hardware.org/?probe=e872ba288e) | Sep 12, 2021 |
| ASUSTek       | UX303LA                     | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| HP            | Pavilion Notebook           | [f373a049e2](https://linux-hardware.org/?probe=f373a049e2) | Sep 10, 2021 |
| HP            | Pavilion Notebook           | [6e97abfd44](https://linux-hardware.org/?probe=6e97abfd44) | Sep 09, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| HP            | Laptop 14-dq1xxx            | [0614925ee7](https://linux-hardware.org/?probe=0614925ee7) | Sep 08, 2021 |
| Gateway       | NV54 Series                 | [fcf57528ed](https://linux-hardware.org/?probe=fcf57528ed) | Sep 08, 2021 |
| Sony          | Serie VJC14                 | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo        | V330-15IKB 81AX             | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| HP            | Laptop 15-bs1xx             | [91ecd39f66](https://linux-hardware.org/?probe=91ecd39f66) | Sep 05, 2021 |
| Medion        | Akoya THE TOUCH 10          | [d49d62a2f5](https://linux-hardware.org/?probe=d49d62a2f5) | Sep 04, 2021 |
| Dell          | Vostro 15-3568              | [9460412d4d](https://linux-hardware.org/?probe=9460412d4d) | Sep 04, 2021 |
| Apple         | MacBookPro8,1               | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| HP            | EliteBook Folio 9470m       | [adbb6a690a](https://linux-hardware.org/?probe=adbb6a690a) | Sep 01, 2021 |
| Dell          | Latitude 3580               | [2befbbba9e](https://linux-hardware.org/?probe=2befbbba9e) | Aug 31, 2021 |
| HP            | Pavilion g6                 | [7dba3c201c](https://linux-hardware.org/?probe=7dba3c201c) | Aug 31, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [cf69bd4423](https://linux-hardware.org/?probe=cf69bd4423) | Aug 31, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| Acer          | Aspire E5-573G              | [8c61841633](https://linux-hardware.org/?probe=8c61841633) | Aug 30, 2021 |
| HP            | ProBook 4320s               | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| eMachines     | G525                        | [d64e29475f](https://linux-hardware.org/?probe=d64e29475f) | Aug 29, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Acer          | Aspire A515-51G             | [df0d3e8ac4](https://linux-hardware.org/?probe=df0d3e8ac4) | Aug 26, 2021 |
| HP            | Laptop 17-by3xxx            | [84aa134848](https://linux-hardware.org/?probe=84aa134848) | Aug 25, 2021 |
| Lenovo        | G500 20236                  | [a23cf0d12d](https://linux-hardware.org/?probe=a23cf0d12d) | Aug 22, 2021 |
| HP            | Laptop 15-bs0xx             | [fae546f5cb](https://linux-hardware.org/?probe=fae546f5cb) | Aug 20, 2021 |
| HP            | Laptop 17-by3xxx            | [674068cb21](https://linux-hardware.org/?probe=674068cb21) | Aug 19, 2021 |
| Apple         | MacBookPro9,1               | [e9bec90506](https://linux-hardware.org/?probe=e9bec90506) | Aug 19, 2021 |
| Acer          | Aspire F5-573G              | [9d7628068c](https://linux-hardware.org/?probe=9d7628068c) | Aug 19, 2021 |
| Dell          | System XPS L321X            | [34d7fb6cbb](https://linux-hardware.org/?probe=34d7fb6cbb) | Aug 18, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| HP            | Notebook                    | [a3058005e3](https://linux-hardware.org/?probe=a3058005e3) | Aug 16, 2021 |
| HP            | Notebook                    | [7800ef9623](https://linux-hardware.org/?probe=7800ef9623) | Aug 16, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [fa6c69671f](https://linux-hardware.org/?probe=fa6c69671f) | Aug 16, 2021 |

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
| Elementary 6.1   | 456       | 45.01%  |
| Elementary 5.1.7 | 150       | 14.81%  |
| Elementary 6     | 143       | 14.12%  |
| Elementary 7     | 105       | 10.37%  |
| Elementary 5.0   | 34        | 3.36%   |
| Elementary 5.1.6 | 29        | 2.86%   |
| Elementary 5.1   | 25        | 2.47%   |
| Elementary 5.1.4 | 23        | 2.27%   |
| Elementary 5.1.2 | 16        | 1.58%   |
| Elementary 5.1.3 | 12        | 1.18%   |
| Elementary 5.1.5 | 8         | 0.79%   |
| Elementary 0.4.1 | 8         | 0.79%   |
| Elementary 6.0   | 4         | 0.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Elementary | 981       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-43-generic | 86        | 7.94%   |
| 5.15.0-58-generic | 42        | 3.88%   |
| 5.13.0-28-generic | 32        | 2.95%   |
| 5.11.0-40-generic | 32        | 2.95%   |
| 5.15.0-46-generic | 31        | 2.86%   |
| 5.13.0-30-generic | 27        | 2.49%   |
| 5.11.0-41-generic | 27        | 2.49%   |
| 5.11.0-27-generic | 27        | 2.49%   |
| 5.15.0-56-generic | 25        | 2.31%   |
| 5.13.0-27-generic | 24        | 2.22%   |
| 5.4.0-42-generic  | 21        | 1.94%   |
| 5.15.0-41-generic | 20        | 1.85%   |
| 5.3.0-62-generic  | 19        | 1.75%   |
| 5.15.0-52-generic | 19        | 1.75%   |
| 5.15.0-48-generic | 19        | 1.75%   |
| 5.11.0-38-generic | 19        | 1.75%   |
| 5.19.0-41-generic | 18        | 1.66%   |
| 5.19.0-35-generic | 17        | 1.57%   |
| 5.13.0-40-generic | 16        | 1.48%   |
| 5.13.0-39-generic | 16        | 1.48%   |
| 5.11.0-37-generic | 16        | 1.48%   |
| 5.11.0-44-generic | 14        | 1.29%   |
| 5.13.0-35-generic | 13        | 1.2%    |
| 5.3.0-51-generic  | 12        | 1.11%   |
| 5.19.0-32-generic | 12        | 1.11%   |
| 5.15.0-43-generic | 12        | 1.11%   |
| 5.13.0-37-generic | 12        | 1.11%   |
| 5.0.0-37-generic  | 12        | 1.11%   |
| 5.3.0-53-generic  | 11        | 1.02%   |
| 5.15.0-53-generic | 11        | 1.02%   |
| 5.11.0-34-generic | 11        | 1.02%   |
| 5.11.0-25-generic | 11        | 1.02%   |
| 5.4.0-65-generic  | 10        | 0.92%   |
| 5.13.0-52-generic | 10        | 0.92%   |
| 5.13.0-41-generic | 10        | 0.92%   |
| 5.11.0-46-generic | 10        | 0.92%   |
| 5.4.0-58-generic  | 9         | 0.83%   |
| 5.4.0-52-generic  | 9         | 0.83%   |
| 5.19.0-38-generic | 9         | 0.83%   |
| 5.19.0-43-generic | 8         | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 248       | 24.24%  |
| 5.15.0  | 194       | 18.96%  |
| 5.13.0  | 173       | 16.91%  |
| 5.4.0   | 138       | 13.49%  |
| 5.3.0   | 77        | 7.53%   |
| 5.19.0  | 70        | 6.84%   |
| 4.15.0  | 57        | 5.57%   |
| 5.0.0   | 15        | 1.47%   |
| 5.8.0   | 8         | 0.78%   |
| 5.10.0  | 3         | 0.29%   |
| 4.13.0  | 3         | 0.29%   |
| 5.14.0  | 2         | 0.2%    |
| 6.2.7   | 1         | 0.1%    |
| 6.1.9   | 1         | 0.1%    |
| 6.1.6   | 1         | 0.1%    |
| 6.1.0   | 1         | 0.1%    |
| 6.0.0   | 1         | 0.1%    |
| 5.9.1   | 1         | 0.1%    |
| 5.8.5   | 1         | 0.1%    |
| 5.8.13  | 1         | 0.1%    |
| 5.6.2   | 1         | 0.1%    |
| 5.6.19  | 1         | 0.1%    |
| 5.6.14  | 1         | 0.1%    |
| 5.5.8   | 1         | 0.1%    |
| 5.5.6   | 1         | 0.1%    |
| 5.4.1   | 1         | 0.1%    |
| 5.3.6   | 1         | 0.1%    |
| 5.3.11  | 1         | 0.1%    |
| 5.19.3  | 1         | 0.1%    |
| 5.19.12 | 1         | 0.1%    |
| 5.19.11 | 1         | 0.1%    |
| 5.18.3  | 1         | 0.1%    |
| 5.16.16 | 1         | 0.1%    |
| 5.16.10 | 1         | 0.1%    |
| 5.16.0  | 1         | 0.1%    |
| 5.15.5  | 1         | 0.1%    |
| 5.15.36 | 1         | 0.1%    |
| 5.15.3  | 1         | 0.1%    |
| 5.15.21 | 1         | 0.1%    |
| 5.15.13 | 1         | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 248       | 24.31%  |
| 5.15    | 201       | 19.71%  |
| 5.13    | 173       | 16.96%  |
| 5.4     | 139       | 13.63%  |
| 5.3     | 79        | 7.75%   |
| 5.19    | 73        | 7.16%   |
| 4.15    | 57        | 5.59%   |
| 5.0     | 15        | 1.47%   |
| 5.8     | 10        | 0.98%   |
| 5.14    | 5         | 0.49%   |
| 5.10    | 4         | 0.39%   |
| 6.1     | 3         | 0.29%   |
| 4.13    | 3         | 0.29%   |
| 5.5     | 2         | 0.2%    |
| 5.16    | 2         | 0.2%    |
| 6.2     | 1         | 0.1%    |
| 6.0     | 1         | 0.1%    |
| 5.9     | 1         | 0.1%    |
| 5.6     | 1         | 0.1%    |
| 5.18    | 1         | 0.1%    |
| 4.10    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 981       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pantheon      | 913       | 92.13%  |
| Unknown       | 62        | 6.26%   |
| GNOME         | 8         | 0.81%   |
| X-Cinnamon    | 4         | 0.4%    |
| XFCE          | 1         | 0.1%    |
| Unity         | 1         | 0.1%    |
| GNOME Classic | 1         | 0.1%    |
| Budgie        | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 981       | 99.9%   |
| Unknown | 1         | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 766       | 77.37%  |
| LightDM | 171       | 17.27%  |
| TDM     | 49        | 4.95%   |
| GDM     | 4         | 0.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 421       | 42.65%  |
| de_DE   | 98        | 9.93%   |
| es_ES   | 63        | 6.38%   |
| ru_RU   | 52        | 5.27%   |
| en_GB   | 48        | 4.86%   |
| pt_BR   | 47        | 4.76%   |
| fr_FR   | 34        | 3.44%   |
| Unknown | 33        | 3.34%   |
| it_IT   | 30        | 3.04%   |
| pl_PL   | 17        | 1.72%   |
| en_AU   | 17        | 1.72%   |
| en_CA   | 13        | 1.32%   |
| pt_PT   | 11        | 1.11%   |
| tr_TR   | 10        | 1.01%   |
| nl_NL   | 10        | 1.01%   |
| en_IN   | 9         | 0.91%   |
| hu_HU   | 8         | 0.81%   |
| es_MX   | 5         | 0.51%   |
| cs_CZ   | 5         | 0.51%   |
| zh_CN   | 4         | 0.41%   |
| uk_UA   | 3         | 0.3%    |
| sv_SE   | 3         | 0.3%    |
| nb_NO   | 3         | 0.3%    |
| id_ID   | 3         | 0.3%    |
| es_EC   | 3         | 0.3%    |
| en_ZA   | 3         | 0.3%    |
| el_GR   | 3         | 0.3%    |
| de_CH   | 3         | 0.3%    |
| fr_CA   | 2         | 0.2%    |
| es_CL   | 2         | 0.2%    |
| es_AR   | 2         | 0.2%    |
| da_DK   | 2         | 0.2%    |
| ca_ES   | 2         | 0.2%    |
| C       | 2         | 0.2%    |
| zh_TW   | 1         | 0.1%    |
| vi_VN   | 1         | 0.1%    |
| ru_UA   | 1         | 0.1%    |
| ro_RO   | 1         | 0.1%    |
| hr_HR   | 1         | 0.1%    |
| gl_ES   | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 578       | 58.03%  |
| BIOS | 418       | 41.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 930       | 94.51%  |
| Overlay | 20        | 2.03%   |
| Btrfs   | 13        | 1.32%   |
| Unknown | 12        | 1.22%   |
| Tmpfs   | 6         | 0.61%   |
| Xfs     | 2         | 0.2%    |
| Ext3    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 798       | 80.61%  |
| GPT     | 156       | 15.76%  |
| MBR     | 36        | 3.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 947       | 96.53%  |
| Yes       | 34        | 3.47%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 874       | 88.46%  |
| Yes       | 114       | 11.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 201       | 20.49%  |
| Hewlett-Packard        | 177       | 18.04%  |
| Dell                   | 123       | 12.54%  |
| ASUSTek Computer       | 98        | 9.99%   |
| Apple                  | 92        | 9.38%   |
| Acer                   | 81        | 8.26%   |
| Toshiba                | 32        | 3.26%   |
| HUAWEI                 | 23        | 2.34%   |
| Samsung Electronics    | 19        | 1.94%   |
| Sony                   | 18        | 1.83%   |
| MSI                    | 16        | 1.63%   |
| Fujitsu                | 7         | 0.71%   |
| Google                 | 6         | 0.61%   |
| Star Labs              | 5         | 0.51%   |
| Notebook               | 5         | 0.51%   |
| Packard Bell           | 4         | 0.41%   |
| Medion                 | 4         | 0.41%   |
| LG Electronics         | 4         | 0.41%   |
| Alienware              | 4         | 0.41%   |
| TUXEDO                 | 3         | 0.31%   |
| Timi                   | 3         | 0.31%   |
| Razer                  | 3         | 0.31%   |
| Compaq                 | 3         | 0.31%   |
| Clevo                  | 3         | 0.31%   |
| Chuwi                  | 3         | 0.31%   |
| Unknown                | 3         | 0.31%   |
| Wortmann AG            | 2         | 0.2%    |
| TrekStor               | 2         | 0.2%    |
| Teclast                | 2         | 0.2%    |
| Positivo               | 2         | 0.2%    |
| Multilaser             | 2         | 0.2%    |
| Monster                | 2         | 0.2%    |
| HONOR                  | 2         | 0.2%    |
| eMachines              | 2         | 0.2%    |
| Avell High Performance | 2         | 0.2%    |
| AMI                    | 2         | 0.2%    |
| System76               | 1         | 0.1%    |
| Standard               | 1         | 0.1%    |
| SNS Network (M)        | 1         | 0.1%    |
| SLIMBOOK               | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP Notebook                   | 6         | 0.61%   |
| Apple MacBookPro8,2           | 6         | 0.61%   |
| Apple MacBookAir7,2           | 6         | 0.61%   |
| Lenovo G50-45 80E3            | 5         | 0.51%   |
| HUAWEI MACHD-WXX9             | 5         | 0.51%   |
| HP Pavilion g6                | 5         | 0.51%   |
| Dell Inspiron 15-3567         | 5         | 0.51%   |
| ASUS ZenBook UX425EA_UX425EA  | 5         | 0.51%   |
| Apple MacBookPro9,2           | 5         | 0.51%   |
| Apple MacBookPro8,1           | 5         | 0.51%   |
| Apple MacBookAir6,2           | 5         | 0.51%   |
| Unknown                       | 5         | 0.51%   |
| HP ProBook 4540s              | 4         | 0.41%   |
| HP Pavilion Notebook          | 4         | 0.41%   |
| HP Pavilion dv7               | 4         | 0.41%   |
| HP Laptop 15-bs0xx            | 4         | 0.41%   |
| Dell Latitude E6400           | 4         | 0.41%   |
| Apple MacBookPro5,5           | 4         | 0.41%   |
| Apple MacBookPro11,2          | 4         | 0.41%   |
| Apple MacBookAir4,2           | 4         | 0.41%   |
| Apple MacBook5,1              | 4         | 0.41%   |
| Apple MacBook4,1              | 4         | 0.41%   |
| Star Labs StarBook            | 3         | 0.31%   |
| Samsung 530U3C/530U4C/532U3C  | 3         | 0.31%   |
| Lenovo IdeaPad 330-15IKB 81FE | 3         | 0.31%   |
| HUAWEI NBLK-WAX9X             | 3         | 0.31%   |
| HUAWEI NBLB-WAX9N             | 3         | 0.31%   |
| HP Laptop 15-db0xxx           | 3         | 0.31%   |
| HP Laptop 15-bw0xx            | 3         | 0.31%   |
| HP EliteBook 840 G3           | 3         | 0.31%   |
| HP 255 G7 Notebook PC         | 3         | 0.31%   |
| HP 250 G7 Notebook PC         | 3         | 0.31%   |
| HP 15                         | 3         | 0.31%   |
| Dell Latitude E5470           | 3         | 0.31%   |
| Dell Inspiron N5110           | 3         | 0.31%   |
| Dell Inspiron 1545            | 3         | 0.31%   |
| ASUS X550CA                   | 3         | 0.31%   |
| Apple MacBookPro9,1           | 3         | 0.31%   |
| Apple MacBookPro6,2           | 3         | 0.31%   |
| Apple MacBookPro10,1          | 3         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 97        | 9.89%   |
| Lenovo IdeaPad        | 61        | 6.22%   |
| Acer Aspire           | 60        | 6.12%   |
| Dell Latitude         | 42        | 4.28%   |
| HP Pavilion           | 41        | 4.18%   |
| Dell Inspiron         | 38        | 3.87%   |
| HP ProBook            | 34        | 3.47%   |
| HP Laptop             | 30        | 3.06%   |
| HP EliteBook          | 26        | 2.65%   |
| Toshiba Satellite     | 24        | 2.45%   |
| Dell XPS              | 16        | 1.63%   |
| ASUS VivoBook         | 15        | 1.53%   |
| ASUS ZenBook          | 14        | 1.43%   |
| Apple MacBookPro8     | 13        | 1.33%   |
| Acer Swift            | 11        | 1.12%   |
| Dell Vostro           | 10        | 1.02%   |
| Apple MacBookPro11    | 10        | 1.02%   |
| Dell Precision        | 8         | 0.82%   |
| Apple MacBookPro9     | 8         | 0.82%   |
| Apple MacBookAir7     | 8         | 0.82%   |
| Fujitsu LIFEBOOK      | 7         | 0.71%   |
| Apple MacBookPro5     | 7         | 0.71%   |
| Apple MacBookAir6     | 7         | 0.71%   |
| Lenovo Legion         | 6         | 0.61%   |
| HP Notebook           | 6         | 0.61%   |
| HP 250                | 6         | 0.61%   |
| Apple MacBook5        | 6         | 0.61%   |
| Lenovo G50-45         | 5         | 0.51%   |
| HUAWEI MACHD-WXX9     | 5         | 0.51%   |
| Apple MacBookPro10    | 5         | 0.51%   |
| Unknown               | 5         | 0.51%   |
| Packard Bell EasyNote | 4         | 0.41%   |
| Lenovo ThinkBook      | 4         | 0.41%   |
| HP ENVY               | 4         | 0.41%   |
| HP 255                | 4         | 0.41%   |
| ASUS ROG              | 4         | 0.41%   |
| Apple MacBookAir4     | 4         | 0.41%   |
| Apple MacBook4        | 4         | 0.41%   |
| Toshiba TECRA         | 3         | 0.31%   |
| Toshiba PORTEGE       | 3         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 93        | 9.48%   |
| 2018    | 89        | 9.07%   |
| 2012    | 88        | 8.97%   |
| 2019    | 80        | 8.15%   |
| 2013    | 78        | 7.95%   |
| 2011    | 74        | 7.54%   |
| 2016    | 73        | 7.44%   |
| 2017    | 67        | 6.83%   |
| 2021    | 66        | 6.73%   |
| 2015    | 66        | 6.73%   |
| 2014    | 58        | 5.91%   |
| 2010    | 56        | 5.71%   |
| 2008    | 34        | 3.47%   |
| 2009    | 33        | 3.36%   |
| 2022    | 11        | 1.12%   |
| 2007    | 10        | 1.02%   |
| 2006    | 3         | 0.31%   |
| 2023    | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 981       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 853       | 86.34%  |
| Enabled  | 135       | 13.66%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 969       | 98.78%  |
| Yes  | 12        | 1.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 331       | 33.47%  |
| 3.01-4.0    | 223       | 22.55%  |
| 8.01-16.0   | 173       | 17.49%  |
| 16.01-24.0  | 165       | 16.68%  |
| 32.01-64.0  | 38        | 3.84%   |
| 1.01-2.0    | 37        | 3.74%   |
| 2.01-3.0    | 10        | 1.01%   |
| 24.01-32.0  | 5         | 0.51%   |
| 64.01-256.0 | 5         | 0.51%   |
| 0.51-1.0    | 2         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 391       | 37.1%   |
| 2.01-3.0   | 330       | 31.31%  |
| 3.01-4.0   | 162       | 15.37%  |
| 4.01-8.0   | 116       | 11.01%  |
| 0.51-1.0   | 31        | 2.94%   |
| 8.01-16.0  | 22        | 2.09%   |
| 24.01-32.0 | 1         | 0.09%   |
| 16.01-24.0 | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 740       | 74.6%   |
| 2      | 227       | 22.88%  |
| 3      | 11        | 1.11%   |
| 4      | 6         | 0.6%    |
| 0      | 5         | 0.5%    |
| 5      | 3         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 637       | 64.67%  |
| Yes       | 348       | 35.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 761       | 77.57%  |
| No        | 220       | 22.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 969       | 98.68%  |
| No        | 13        | 1.32%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 835       | 84.51%  |
| No        | 153       | 15.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 137       | 13.95%  |
| Germany      | 102       | 10.39%  |
| Brazil       | 65        | 6.62%   |
| Russia       | 59        | 6.01%   |
| UK           | 45        | 4.58%   |
| India        | 45        | 4.58%   |
| Italy        | 41        | 4.18%   |
| France       | 30        | 3.05%   |
| Spain        | 29        | 2.95%   |
| Mexico       | 26        | 2.65%   |
| Indonesia    | 26        | 2.65%   |
| Poland       | 24        | 2.44%   |
| Canada       | 23        | 2.34%   |
| Australia    | 23        | 2.34%   |
| Turkey       | 21        | 2.14%   |
| Netherlands  | 18        | 1.83%   |
| Portugal     | 15        | 1.53%   |
| Argentina    | 14        | 1.43%   |
| Belgium      | 12        | 1.22%   |
| Austria      | 11        | 1.12%   |
| Ukraine      | 10        | 1.02%   |
| Chile        | 10        | 1.02%   |
| Hungary      | 9         | 0.92%   |
| Romania      | 8         | 0.81%   |
| Norway       | 8         | 0.81%   |
| Czechia      | 8         | 0.81%   |
| South Africa | 7         | 0.71%   |
| Switzerland  | 6         | 0.61%   |
| Sweden       | 6         | 0.61%   |
| Colombia     | 6         | 0.61%   |
| New Zealand  | 5         | 0.51%   |
| Ireland      | 5         | 0.51%   |
| Greece       | 5         | 0.51%   |
| Denmark      | 5         | 0.51%   |
| China        | 5         | 0.51%   |
| Philippines  | 4         | 0.41%   |
| Peru         | 4         | 0.41%   |
| Malaysia     | 4         | 0.41%   |
| Ecuador      | 4         | 0.41%   |
| Thailand     | 3         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Moscow         | 19        | 1.85%   |
| Berlin         | 11        | 1.07%   |
| St Petersburg  | 9         | 0.88%   |
| Milan          | 9         | 0.88%   |
| Sydney         | 8         | 0.78%   |
| Madrid         | 8         | 0.78%   |
| Istanbul       | 8         | 0.78%   |
| Warsaw         | 7         | 0.68%   |
| Vienna         | 7         | 0.68%   |
| Sao Paulo      | 7         | 0.68%   |
| Perth          | 7         | 0.68%   |
| Munich         | 6         | 0.59%   |
| Jakarta        | 6         | 0.59%   |
| Hamburg        | 6         | 0.59%   |
| The Hague      | 5         | 0.49%   |
| Stuttgart      | 5         | 0.49%   |
| Rome           | 5         | 0.49%   |
| Paris          | 5         | 0.49%   |
| Mexico City    | 5         | 0.49%   |
| Delhi          | 5         | 0.49%   |
| Surabaya       | 4         | 0.39%   |
| Santo André   | 4         | 0.39%   |
| Rio de Janeiro | 4         | 0.39%   |
| Kolkata        | 4         | 0.39%   |
| Fortaleza      | 4         | 0.39%   |
| Córdoba       | 4         | 0.39%   |
| Budapest       | 4         | 0.39%   |
| Vernon         | 3         | 0.29%   |
| Valencia       | 3         | 0.29%   |
| Rostov-on-Don  | 3         | 0.29%   |
| Queretaro      | 3         | 0.29%   |
| Prague         | 3         | 0.29%   |
| Porto          | 3         | 0.29%   |
| Novosibirsk    | 3         | 0.29%   |
| Mumbai         | 3         | 0.29%   |
| Monza          | 3         | 0.29%   |
| Montreal       | 3         | 0.29%   |
| Minsk          | 3         | 0.29%   |
| Melbourne      | 3         | 0.29%   |
| Managua        | 3         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 157       | 185    | 13.04%  |
| WDC                         | 128       | 153    | 10.63%  |
| Seagate                     | 110       | 124    | 9.14%   |
| Toshiba                     | 105       | 118    | 8.72%   |
| SanDisk                     | 91        | 104    | 7.56%   |
| Unknown                     | 79        | 93     | 6.56%   |
| Kingston                    | 68        | 78     | 5.65%   |
| Crucial                     | 51        | 60     | 4.24%   |
| Apple                       | 42        | 47     | 3.49%   |
| HGST                        | 40        | 48     | 3.32%   |
| Hitachi                     | 36        | 37     | 2.99%   |
| Intel                       | 33        | 44     | 2.74%   |
| SK hynix                    | 31        | 40     | 2.57%   |
| Micron Technology           | 21        | 23     | 1.74%   |
| A-DATA Technology           | 21        | 24     | 1.74%   |
| KIOXIA                      | 11        | 20     | 0.91%   |
| Fujitsu                     | 11        | 13     | 0.91%   |
| China                       | 11        | 11     | 0.91%   |
| Phison                      | 9         | 10     | 0.75%   |
| Silicon Motion              | 6         | 7      | 0.5%    |
| LITEON                      | 6         | 6      | 0.5%    |
| JMicron Technology          | 6         | 6      | 0.5%    |
| SPCC                        | 5         | 5      | 0.42%   |
| PNY                         | 5         | 6      | 0.42%   |
| Union Memory                | 4         | 5      | 0.33%   |
| Intenso                     | 4         | 5      | 0.33%   |
| Hewlett-Packard             | 4         | 5      | 0.33%   |
| TO Exter                    | 3         | 3      | 0.25%   |
| Star Drive                  | 3         | 3      | 0.25%   |
| Phison Electronics          | 3         | 3      | 0.25%   |
| Patriot                     | 3         | 5      | 0.25%   |
| OCZ                         | 3         | 4      | 0.25%   |
| Micron/Crucial Technology   | 3         | 3      | 0.25%   |
| Lite-On                     | 3         | 3      | 0.25%   |
| KingDian                    | 3         | 4      | 0.25%   |
| Gigabyte Technology         | 3         | 3      | 0.25%   |
| Unknown                     | 3         | 3      | 0.25%   |
| Yangtze Memory Technologies | 2         | 2      | 0.17%   |
| V-GeN                       | 2         | 2      | 0.17%   |
| UMIS                        | 2         | 2      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                              | 24        | 1.94%   |
| Unknown MMC Card  32GB                              | 22        | 1.78%   |
| Kingston SA400S37240G 240GB SSD                     | 19        | 1.54%   |
| Seagate ST1000LM035-1RK172 1TB                      | 17        | 1.38%   |
| Samsung NVMe SSD Drive 512GB                        | 17        | 1.38%   |
| SanDisk NVMe SSD Drive 512GB                        | 15        | 1.21%   |
| Unknown MMC Card  64GB                              | 14        | 1.13%   |
| Toshiba MQ04ABF100 1TB                              | 14        | 1.13%   |
| Samsung NVMe SSD Drive 256GB                        | 14        | 1.13%   |
| Seagate ST500LT012-1DG142 500GB                     | 13        | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 13        | 1.05%   |
| Unknown MMC Card  128GB                             | 12        | 0.97%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 11        | 0.89%   |
| Toshiba MQ01ABF050 500GB                            | 11        | 0.89%   |
| HGST HTS721010A9E630 1TB                            | 11        | 0.89%   |
| Kingston SA400S37120G 120GB SSD                     | 8         | 0.65%   |
| HGST HTS545050A7E680 500GB                          | 8         | 0.65%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 7         | 0.57%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 7         | 0.57%   |
| Unknown MMC Card  16GB                              | 7         | 0.57%   |
| SK hynix NVMe SSD Drive 512GB                       | 7         | 0.57%   |
| SanDisk NVMe SSD Drive 256GB                        | 7         | 0.57%   |
| Samsung SSD 860 EVO 500GB                           | 7         | 0.57%   |
| Samsung SSD 860 EVO 250GB                           | 7         | 0.57%   |
| Samsung SSD 850 EVO 250GB                           | 7         | 0.57%   |
| Intel NVMe SSD Drive 512GB                          | 7         | 0.57%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 6         | 0.49%   |
| HGST HTS541010A9E680 1TB                            | 6         | 0.49%   |
| Crucial CT500MX500SSD1 500GB                        | 6         | 0.49%   |
| Crucial CT1000MX500SSD1 1TB                         | 6         | 0.49%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 5         | 0.4%    |
| Toshiba NVMe SSD Drive 512GB                        | 5         | 0.4%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD                 | 5         | 0.4%    |
| Seagate ST9500325AS 500GB                           | 5         | 0.4%    |
| Samsung SSD 850 EVO 500GB                           | 5         | 0.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 5         | 0.4%    |
| HGST HTS725050A7E630 500GB                          | 5         | 0.4%    |
| HGST HTS541010B7E610 1TB                            | 5         | 0.4%    |
| Crucial CT480BX500SSD1 480GB                        | 5         | 0.4%    |
| Crucial CT240BX500SSD1 240GB                        | 5         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 109       | 122    | 29.14%  |
| WDC                 | 84        | 101    | 22.46%  |
| Toshiba             | 80        | 86     | 21.39%  |
| HGST                | 40        | 48     | 10.7%   |
| Hitachi             | 36        | 37     | 9.63%   |
| Fujitsu             | 11        | 13     | 2.94%   |
| Samsung Electronics | 5         | 7      | 1.34%   |
| Apple               | 3         | 3      | 0.8%    |
| Unknown             | 2         | 2      | 0.53%   |
| StoreJet            | 1         | 1      | 0.27%   |
| SSK                 | 1         | 1      | 0.27%   |
| Generic-            | 1         | 1      | 0.27%   |
| ASMT                | 1         | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 81        | 92     | 17.8%   |
| Kingston            | 56        | 61     | 12.31%  |
| Crucial             | 51        | 60     | 11.21%  |
| SanDisk             | 49        | 57     | 10.77%  |
| Apple               | 37        | 41     | 8.13%   |
| WDC                 | 31        | 34     | 6.81%   |
| A-DATA Technology   | 18        | 20     | 3.96%   |
| Intel               | 14        | 14     | 3.08%   |
| Toshiba             | 12        | 16     | 2.64%   |
| Micron Technology   | 11        | 13     | 2.42%   |
| China               | 11        | 11     | 2.42%   |
| LITEON              | 6         | 6      | 1.32%   |
| SPCC                | 5         | 5      | 1.1%    |
| SK hynix            | 5         | 5      | 1.1%    |
| PNY                 | 5         | 6      | 1.1%    |
| Hewlett-Packard     | 4         | 5      | 0.88%   |
| TO Exter            | 3         | 3      | 0.66%   |
| Patriot             | 3         | 5      | 0.66%   |
| OCZ                 | 3         | 4      | 0.66%   |
| Intenso             | 3         | 4      | 0.66%   |
| Transcend           | 2         | 2      | 0.44%   |
| Star                | 2         | 2      | 0.44%   |
| NGFF                | 2         | 2      | 0.44%   |
| Netac               | 2         | 2      | 0.44%   |
| LITEONIT            | 2         | 2      | 0.44%   |
| KingDian            | 2         | 3      | 0.44%   |
| Gigabyte Technology | 2         | 2      | 0.44%   |
| FORESEE             | 2         | 2      | 0.44%   |
| Apacer              | 2         | 4      | 0.44%   |
| VT                  | 1         | 1      | 0.22%   |
| V-GeN               | 1         | 1      | 0.22%   |
| TSA                 | 1         | 1      | 0.22%   |
| TrekStor            | 1         | 1      | 0.22%   |
| Teclast             | 1         | 1      | 0.22%   |
| Team                | 1         | 1      | 0.22%   |
| Super Talent        | 1         | 1      | 0.22%   |
| Smartbuy            | 1         | 1      | 0.22%   |
| Plextor             | 1         | 1      | 0.22%   |
| Pioneer             | 1         | 1      | 0.22%   |
| Pichau              | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 431       | 513    | 37.06%  |
| HDD     | 367       | 423    | 31.56%  |
| NVMe    | 261       | 342    | 22.44%  |
| MMC     | 76        | 88     | 6.53%   |
| Unknown | 28        | 31     | 2.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 731       | 925    | 66.27%  |
| NVMe | 258       | 338    | 23.39%  |
| MMC  | 76        | 88     | 6.89%   |
| SAS  | 38        | 46     | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 546       | 666    | 69.82%  |
| 0.51-1.0   | 212       | 242    | 27.11%  |
| 1.01-2.0   | 23        | 27     | 2.94%   |
| 4.01-10.0  | 1         | 1      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 394       | 39.28%  |
| 251-500        | 279       | 27.82%  |
| 501-1000       | 136       | 13.56%  |
| 51-100         | 79        | 7.88%   |
| 21-50          | 43        | 4.29%   |
| 1001-2000      | 38        | 3.79%   |
| 1-20           | 16        | 1.6%    |
| 2001-3000      | 9         | 0.9%    |
| More than 3000 | 6         | 0.6%    |
| Unknown        | 3         | 0.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 453       | 43.47%  |
| 21-50          | 265       | 25.43%  |
| 51-100         | 131       | 12.57%  |
| 101-250        | 105       | 10.08%  |
| 251-500        | 46        | 4.41%   |
| 501-1000       | 25        | 2.4%    |
| 1001-2000      | 10        | 0.96%   |
| 2001-3000      | 3         | 0.29%   |
| Unknown        | 3         | 0.29%   |
| More than 3000 | 1         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 5%      |
| WDC WD5000BPKT-75PK4T0 500GB          | 1         | 1      | 5%      |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1      | 5%      |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 5%      |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 5%      |
| Seagate ST500LM030-2E717D 500GB       | 1         | 1      | 5%      |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 5%      |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 5%      |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 1      | 5%      |
| SanDisk SD7SB3Q256G1002 256GB SSD     | 1         | 1      | 5%      |
| Kingston SV300S37A240G 240GB SSD      | 1         | 1      | 5%      |
| Kingston SUV400S37480G 480GB SSD      | 1         | 1      | 5%      |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 5%      |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 5%      |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 5%      |
| Fujitsu MHZ2160BH G2 160GB            | 1         | 2      | 5%      |
| Crucial CT512M550SSD3 512GB           | 1         | 1      | 5%      |
| China SSD 256GB                       | 1         | 1      | 5%      |
| Apple SSD SM256C 256GB                | 1         | 1      | 5%      |
| A-DATA Technology SP900NS38 128GB SSD | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 3         | 3      | 15%     |
| Seagate           | 3         | 3      | 15%     |
| HGST              | 3         | 3      | 15%     |
| Toshiba           | 2         | 2      | 10%     |
| SanDisk           | 2         | 2      | 10%     |
| Kingston          | 2         | 2      | 10%     |
| Fujitsu           | 1         | 2      | 5%      |
| Crucial           | 1         | 1      | 5%      |
| China             | 1         | 1      | 5%      |
| Apple             | 1         | 1      | 5%      |
| A-DATA Technology | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 27.27%  |
| HGST    | 3         | 3      | 27.27%  |
| WDC     | 2         | 2      | 18.18%  |
| Toshiba | 2         | 2      | 18.18%  |
| Fujitsu | 1         | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 12     | 55%     |
| SSD  | 9         | 9      | 45%     |

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
| Detected | 836       | 1176   | 82.36%  |
| Works    | 158       | 199    | 15.57%  |
| Malfunc  | 20        | 21     | 1.97%   |
| Failed   | 1         | 1      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 702       | 63.53%  |
| AMD                            | 103       | 9.32%   |
| Samsung Electronics            | 91        | 8.24%   |
| SanDisk                        | 56        | 5.07%   |
| SK hynix                       | 25        | 2.26%   |
| Nvidia                         | 21        | 1.9%    |
| Phison Electronics             | 15        | 1.36%   |
| Kingston Technology Company    | 15        | 1.36%   |
| Toshiba America Info Systems   | 14        | 1.27%   |
| Micron Technology              | 10        | 0.9%    |
| KIOXIA                         | 10        | 0.9%    |
| Union Memory (Shenzhen)        | 6         | 0.54%   |
| Silicon Motion                 | 6         | 0.54%   |
| Marvell Technology Group       | 6         | 0.54%   |
| ADATA Technology               | 5         | 0.45%   |
| Solid State Storage Technology | 3         | 0.27%   |
| Realtek Semiconductor          | 3         | 0.27%   |
| Micron/Crucial Technology      | 3         | 0.27%   |
| Lite-On Technology             | 3         | 0.27%   |
| Yangtze Memory Technologies    | 2         | 0.18%   |
| Biwin Storage Technology       | 2         | 0.18%   |
| Apple                          | 2         | 0.18%   |
| INNOGRIT                       | 1         | 0.09%   |
| ASMedia Technology             | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 103       | 8.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 96        | 8.26%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 94        | 8.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 69        | 5.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 55        | 4.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 43        | 3.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 32        | 2.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 28        | 2.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 27        | 2.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 26        | 2.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 25        | 2.15%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 25        | 2.15%   |
| Samsung NVMe SSD Controller 980                                                        | 23        | 1.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 22        | 1.89%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 20        | 1.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 20        | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 15        | 1.29%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 14        | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 14        | 1.2%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 13        | 1.12%   |
| Nvidia MCP79 AHCI Controller                                                           | 13        | 1.12%   |
| Samsung Electronics SATA controller                                                    | 12        | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 12        | 1.03%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 11        | 0.95%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 11        | 0.95%   |
| Intel SSD 660P Series                                                                  | 11        | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 11        | 0.95%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 11        | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 11        | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 11        | 0.95%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 9         | 0.77%   |
| SanDisk PC SN530 NVMe SSD                                                              | 8         | 0.69%   |
| Phison E12 NVMe Controller                                                             | 8         | 0.69%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 8         | 0.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 8         | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 7         | 0.6%    |
| Samsung NVMe SSD Controller SM951/PM951                                                | 7         | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 7         | 0.6%    |
| Micron NVMe Storage Controller                                                         | 7         | 0.6%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 7         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 743       | 65.75%  |
| NVMe | 256       | 22.65%  |
| RAID | 82        | 7.26%   |
| IDE  | 49        | 4.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 836       | 85.22%  |
| AMD    | 145       | 14.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 22        | 2.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 19        | 1.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.73%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 15        | 1.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 14        | 1.43%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 1.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 1.33%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 1.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 1.33%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 1.12%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 1.02%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 10        | 1.02%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 10        | 1.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 9         | 0.92%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 9         | 0.92%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 9         | 0.92%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.92%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 9         | 0.92%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 0.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 0.82%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 8         | 0.82%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 0.82%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 8         | 0.82%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 8         | 0.82%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 7         | 0.71%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 7         | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.71%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 7         | 0.71%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 6         | 0.61%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.61%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 6         | 0.61%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 6         | 0.61%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 6         | 0.61%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 6         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 264       | 26.91%  |
| Intel Core i7                        | 220       | 22.43%  |
| Intel Core i3                        | 100       | 10.19%  |
| Other                                | 67        | 6.83%   |
| Intel Celeron                        | 61        | 6.22%   |
| Intel Core 2 Duo                     | 54        | 5.5%    |
| AMD Ryzen 5                          | 41        | 4.18%   |
| Intel Pentium                        | 23        | 2.34%   |
| AMD Ryzen 7                          | 18        | 1.83%   |
| Intel Atom                           | 14        | 1.43%   |
| AMD A6                               | 11        | 1.12%   |
| Intel Pentium Dual-Core              | 10        | 1.02%   |
| AMD A8                               | 10        | 1.02%   |
| Intel Pentium Silver                 | 9         | 0.92%   |
| AMD Ryzen 3                          | 8         | 0.82%   |
| AMD A4                               | 8         | 0.82%   |
| AMD A10                              | 8         | 0.82%   |
| Intel Core 2                         | 7         | 0.71%   |
| AMD A12                              | 6         | 0.61%   |
| AMD Ryzen 7 PRO                      | 4         | 0.41%   |
| AMD Ryzen 5 PRO                      | 4         | 0.41%   |
| AMD E1                               | 4         | 0.41%   |
| Intel Genuine                        | 3         | 0.31%   |
| Intel Core m3                        | 3         | 0.31%   |
| Intel Celeron Dual-Core              | 3         | 0.31%   |
| Intel Core m5                        | 2         | 0.2%    |
| AMD Ryzen 9                          | 2         | 0.2%    |
| AMD Phenom II                        | 2         | 0.2%    |
| AMD E                                | 2         | 0.2%    |
| AMD C-60                             | 2         | 0.2%    |
| AMD Athlon                           | 2         | 0.2%    |
| Intel Xeon                           | 1         | 0.1%    |
| Intel Pentium Dual                   | 1         | 0.1%    |
| Intel Core i9                        | 1         | 0.1%    |
| Intel Core 2 Quad                    | 1         | 0.1%    |
| Intel Celeron M                      | 1         | 0.1%    |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.1%    |
| AMD E2                               | 1         | 0.1%    |
| AMD Athlon II Neo                    | 1         | 0.1%    |
| AMD Athlon 64 X2                     | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 580       | 59.12%  |
| 4      | 308       | 31.4%   |
| 6      | 49        | 4.99%   |
| 8      | 29        | 2.96%   |
| 1      | 10        | 1.02%   |
| 10     | 2         | 0.2%    |
| 14     | 1         | 0.1%    |
| 12     | 1         | 0.1%    |
| 5      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 981       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 734       | 74.75%  |
| 1      | 248       | 25.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 977       | 99.59%  |
| Unknown        | 4         | 0.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 162       | 16.17%  |
| 0x206a7    | 87        | 8.68%   |
| 0x306a9    | 72        | 7.19%   |
| 0x40651    | 48        | 4.79%   |
| 0x1067a    | 42        | 4.19%   |
| 0x806c1    | 37        | 3.69%   |
| 0x806ea    | 36        | 3.59%   |
| 0x806e9    | 36        | 3.59%   |
| 0x406e3    | 36        | 3.59%   |
| 0x306d4    | 33        | 3.29%   |
| 0x806ec    | 31        | 3.09%   |
| 0x20655    | 26        | 2.59%   |
| 0x306c3    | 23        | 2.3%    |
| 0x20652    | 17        | 1.7%    |
| 0x906ea    | 14        | 1.4%    |
| 0x706e5    | 14        | 1.4%    |
| 0x30678    | 14        | 1.4%    |
| 0x06006705 | 14        | 1.4%    |
| 0x806eb    | 13        | 1.3%    |
| 0x706a1    | 13        | 1.3%    |
| 0x406c3    | 13        | 1.3%    |
| 0xa0652    | 12        | 1.2%    |
| 0x08108109 | 12        | 1.2%    |
| 0x506c9    | 11        | 1.1%    |
| 0x08600106 | 11        | 1.1%    |
| 0x906e9    | 10        | 1%      |
| 0x706a8    | 10        | 1%      |
| 0x10676    | 10        | 1%      |
| 0x08608103 | 9         | 0.9%    |
| 0x40661    | 8         | 0.8%    |
| 0x0a50000c | 8         | 0.8%    |
| 0x08108102 | 8         | 0.8%    |
| 0x07030105 | 8         | 0.8%    |
| 0x6fd      | 7         | 0.7%    |
| 0x406c4    | 7         | 0.7%    |
| 0x506e3    | 6         | 0.6%    |
| 0x06001119 | 6         | 0.6%    |
| 0x6fb      | 5         | 0.5%    |
| 0x6f6      | 5         | 0.5%    |
| 0x05000119 | 5         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 169       | 17.23%  |
| SandyBridge      | 94        | 9.58%   |
| Haswell          | 93        | 9.48%   |
| IvyBridge        | 86        | 8.77%   |
| Penryn           | 60        | 6.12%   |
| Skylake          | 55        | 5.61%   |
| TigerLake        | 48        | 4.89%   |
| Westmere         | 46        | 4.69%   |
| Silvermont       | 42        | 4.28%   |
| Broadwell        | 36        | 3.67%   |
| Excavator        | 30        | 3.06%   |
| Goldmont plus    | 26        | 2.65%   |
| Zen+             | 25        | 2.55%   |
| IceLake          | 22        | 2.24%   |
| Core             | 22        | 2.24%   |
| Zen 2            | 21        | 2.14%   |
| Unknown          | 17        | 1.73%   |
| CometLake        | 13        | 1.33%   |
| Puma             | 12        | 1.22%   |
| Goldmont         | 11        | 1.12%   |
| Zen 3            | 10        | 1.02%   |
| Zen              | 10        | 1.02%   |
| Piledriver       | 8         | 0.82%   |
| Bobcat           | 6         | 0.61%   |
| Jaguar           | 4         | 0.41%   |
| K10              | 3         | 0.31%   |
| Bonnell          | 3         | 0.31%   |
| Alderlake Hybrid | 3         | 0.31%   |
| Nehalem          | 2         | 0.2%    |
| Tremont          | 1         | 0.1%    |
| K8 Hammer        | 1         | 0.1%    |
| K8 & K10 hybrid  | 1         | 0.1%    |
| K10 Llano        | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 760       | 63.12%  |
| Nvidia | 228       | 18.94%  |
| AMD    | 216       | 17.94%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 81        | 6.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 81        | 6.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 54        | 4.33%   |
| Intel HD Graphics 620                                                                    | 44        | 3.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 41        | 3.29%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 39        | 3.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 39        | 3.13%   |
| Intel UHD Graphics 620                                                                   | 37        | 2.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 33        | 2.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 29        | 2.33%   |
| Intel HD Graphics 5500                                                                   | 26        | 2.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 26        | 2.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 2.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 25        | 2.01%   |
| AMD Renoir                                                                               | 21        | 1.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 1.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 20        | 1.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 19        | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 1.36%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 1.04%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 13        | 1.04%   |
| AMD Lucienne                                                                             | 13        | 1.04%   |
| Nvidia C79 [GeForce 9400M]                                                               | 12        | 0.96%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 12        | 0.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 11        | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 0.88%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 0.88%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 11        | 0.88%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 0.8%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 0.8%    |
| Intel HD Graphics 630                                                                    | 10        | 0.8%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 10        | 0.8%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 0.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 0.8%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 9         | 0.72%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 9         | 0.72%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 9         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 545       | 55.56%  |
| Intel + Nvidia | 168       | 17.13%  |
| 1 x AMD        | 139       | 14.17%  |
| 1 x Nvidia     | 48        | 4.89%   |
| Intel + AMD    | 46        | 4.69%   |
| 2 x AMD        | 23        | 2.34%   |
| AMD + Nvidia   | 8         | 0.82%   |
| 2 x Nvidia     | 3         | 0.31%   |
| Other          | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 873       | 88.45%  |
| Proprietary | 100       | 10.13%  |
| Unknown     | 14        | 1.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 634       | 63.85%  |
| 1.01-2.0   | 134       | 13.49%  |
| 0.01-0.5   | 105       | 10.57%  |
| 0.51-1.0   | 65        | 6.55%   |
| 3.01-4.0   | 39        | 3.93%   |
| 5.01-6.0   | 10        | 1.01%   |
| 7.01-8.0   | 4         | 0.4%    |
| 2.01-3.0   | 2         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 194       | 17.96%  |
| LG Display              | 157       | 14.54%  |
| BOE                     | 150       | 13.89%  |
| Chimei Innolux          | 148       | 13.7%   |
| Samsung Electronics     | 95        | 8.8%    |
| Apple                   | 91        | 8.43%   |
| Sharp                   | 30        | 2.78%   |
| Dell                    | 25        | 2.31%   |
| Lenovo                  | 23        | 2.13%   |
| Chi Mei Optoelectronics | 23        | 2.13%   |
| PANDA                   | 17        | 1.57%   |
| Hewlett-Packard         | 12        | 1.11%   |
| Goldstar                | 10        | 0.93%   |
| CSO                     | 7         | 0.65%   |
| BenQ                    | 7         | 0.65%   |
| AOC                     | 7         | 0.65%   |
| Acer                    | 6         | 0.56%   |
| ViewSonic               | 5         | 0.46%   |
| Toshiba                 | 5         | 0.46%   |
| Sony                    | 5         | 0.46%   |
| Philips                 | 5         | 0.46%   |
| CPT                     | 5         | 0.46%   |
| Panasonic               | 4         | 0.37%   |
| LG Philips              | 4         | 0.37%   |
| InfoVision              | 4         | 0.37%   |
| Unknown                 | 3         | 0.28%   |
| Ancor Communications    | 3         | 0.28%   |
| LGD                     | 2         | 0.19%   |
| JDI                     | 2         | 0.19%   |
| HannStar                | 2         | 0.19%   |
| ___                     | 1         | 0.09%   |
| Vizio                   | 1         | 0.09%   |
| Vestel Elektronik       | 1         | 0.09%   |
| TopView                 | 1         | 0.09%   |
| TMX                     | 1         | 0.09%   |
| Tianma XM               | 1         | 0.09%   |
| Tech Concepts           | 1         | 0.09%   |
| SKG                     | 1         | 0.09%   |
| Seiko/Epson             | 1         | 0.09%   |
| SANYO                   | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 11        | 1.01%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 11        | 1.01%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 10        | 0.91%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 9         | 0.82%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 9         | 0.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 8         | 0.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 7         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 7         | 0.64%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 7         | 0.64%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 7         | 0.64%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 7         | 0.64%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 7         | 0.64%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 6         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 6         | 0.55%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 6         | 0.55%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 6         | 0.55%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 5         | 0.46%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 5         | 0.46%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 5         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 5         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 5         | 0.46%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.46%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 5         | 0.46%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 5         | 0.46%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 5         | 0.46%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 5         | 0.46%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 5         | 0.46%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.37%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.37%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 4         | 0.37%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                  | 4         | 0.37%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                    | 4         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 4         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 4         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch         | 4         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 4         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 4         | 0.37%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 4         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 392       | 38.06%  |
| 1366x768 (WXGA)    | 349       | 33.88%  |
| 1280x800 (WXGA)    | 57        | 5.53%   |
| 1600x900 (HD+)     | 54        | 5.24%   |
| 1440x900 (WXGA+)   | 36        | 3.5%    |
| 3840x2160 (4K)     | 32        | 3.11%   |
| 2560x1440 (QHD)    | 20        | 1.94%   |
| 1920x1200 (WUXGA)  | 15        | 1.46%   |
| 2880x1800          | 14        | 1.36%   |
| 2560x1600          | 10        | 0.97%   |
| 3000x2000          | 7         | 0.68%   |
| 1680x1050 (WSXGA+) | 7         | 0.68%   |
| 1280x1024 (SXGA)   | 6         | 0.58%   |
| 1024x600           | 4         | 0.39%   |
| 3840x2400          | 3         | 0.29%   |
| 3200x1800 (QHD+)   | 3         | 0.29%   |
| 2560x1080          | 2         | 0.19%   |
| 1920x540           | 2         | 0.19%   |
| 1920x1280          | 2         | 0.19%   |
| 1360x768           | 2         | 0.19%   |
| Unknown            | 2         | 0.19%   |
| 4240x1080          | 1         | 0.1%    |
| 3840x1100          | 1         | 0.1%    |
| 3840x1080          | 1         | 0.1%    |
| 3440x1440          | 1         | 0.1%    |
| 3072x1920          | 1         | 0.1%    |
| 2256x1504          | 1         | 0.1%    |
| 2160x1440          | 1         | 0.1%    |
| 1920x515           | 1         | 0.1%    |
| 1680x945           | 1         | 0.1%    |
| 1600x1200          | 1         | 0.1%    |
| 1400x1050          | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 412       | 38.01%  |
| 13      | 222       | 20.48%  |
| 14      | 140       | 12.92%  |
| 17      | 71        | 6.55%   |
| 11      | 32        | 2.95%   |
| 27      | 30        | 2.77%   |
| 24      | 25        | 2.31%   |
| 12      | 23        | 2.12%   |
| 21      | 20        | 1.85%   |
| 23      | 19        | 1.75%   |
| Unknown | 19        | 1.75%   |
| 31      | 8         | 0.74%   |
| 18      | 8         | 0.74%   |
| 16      | 8         | 0.74%   |
| 19      | 7         | 0.65%   |
| 84      | 6         | 0.55%   |
| 10      | 6         | 0.55%   |
| 72      | 4         | 0.37%   |
| 25      | 4         | 0.37%   |
| 34      | 3         | 0.28%   |
| 22      | 3         | 0.28%   |
| 52      | 2         | 0.18%   |
| 74      | 1         | 0.09%   |
| 69      | 1         | 0.09%   |
| 65      | 1         | 0.09%   |
| 60      | 1         | 0.09%   |
| 48      | 1         | 0.09%   |
| 47      | 1         | 0.09%   |
| 43      | 1         | 0.09%   |
| 40      | 1         | 0.09%   |
| 37      | 1         | 0.09%   |
| 33      | 1         | 0.09%   |
| 26      | 1         | 0.09%   |
| 20      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 638       | 59.4%   |
| 201-300     | 188       | 17.5%   |
| 351-400     | 87        | 8.1%    |
| 501-600     | 70        | 6.52%   |
| 401-500     | 35        | 3.26%   |
| Unknown     | 19        | 1.77%   |
| 601-700     | 12        | 1.12%   |
| 1501-2000   | 12        | 1.12%   |
| 1001-1500   | 6         | 0.56%   |
| 701-800     | 4         | 0.37%   |
| 801-900     | 2         | 0.19%   |
| 901-1000    | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 787       | 80.97%  |
| 16/10   | 139       | 14.3%   |
| 3/2     | 16        | 1.65%   |
| Unknown | 16        | 1.65%   |
| 5/4     | 5         | 0.51%   |
| 4/3     | 3         | 0.31%   |
| 21/9    | 3         | 0.31%   |
| 3.73    | 1         | 0.1%    |
| 3.40    | 1         | 0.1%    |
| 1.96    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 412       | 38.15%  |
| 81-90          | 276       | 25.56%  |
| 71-80          | 85        | 7.87%   |
| 121-130        | 57        | 5.28%   |
| 201-250        | 51        | 4.72%   |
| 51-60          | 33        | 3.06%   |
| 301-350        | 31        | 2.87%   |
| 61-70          | 23        | 2.13%   |
| Unknown        | 19        | 1.76%   |
| More than 1000 | 16        | 1.48%   |
| 151-200        | 14        | 1.3%    |
| 351-500        | 12        | 1.11%   |
| 131-140        | 12        | 1.11%   |
| 251-300        | 10        | 0.93%   |
| 141-150        | 10        | 0.93%   |
| 111-120        | 7         | 0.65%   |
| 41-50          | 6         | 0.56%   |
| 501-1000       | 5         | 0.46%   |
| 91-100         | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 407       | 38.47%  |
| 101-120       | 401       | 37.9%   |
| 51-100        | 118       | 11.15%  |
| 161-240       | 73        | 6.9%    |
| More than 240 | 27        | 2.55%   |
| Unknown       | 19        | 1.8%    |
| 1-50          | 13        | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 843       | 84.64%  |
| 2     | 127       | 12.75%  |
| 0     | 13        | 1.31%   |
| 3     | 12        | 1.2%    |
| 4     | 1         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 483       | 31.42%  |
| Intel                             | 459       | 29.86%  |
| Qualcomm Atheros                  | 234       | 15.22%  |
| Broadcom                          | 153       | 9.95%   |
| Broadcom Limited                  | 36        | 2.34%   |
| Marvell Technology Group          | 20        | 1.3%    |
| Nvidia                            | 17        | 1.11%   |
| Ralink                            | 13        | 0.85%   |
| TP-Link                           | 10        | 0.65%   |
| MediaTek                          | 9         | 0.59%   |
| Huawei Technologies               | 9         | 0.59%   |
| Sierra Wireless                   | 8         | 0.52%   |
| Ralink Technology                 | 8         | 0.52%   |
| ASIX Electronics                  | 8         | 0.52%   |
| Xiaomi                            | 6         | 0.39%   |
| Qualcomm                          | 6         | 0.39%   |
| Samsung Electronics               | 5         | 0.33%   |
| Ericsson Business Mobile Networks | 5         | 0.33%   |
| D-Link                            | 5         | 0.33%   |
| Hewlett-Packard                   | 4         | 0.26%   |
| OPPO Electronics                  | 3         | 0.2%    |
| Lenovo                            | 3         | 0.2%    |
| Google                            | 3         | 0.2%    |
| Dell                              | 3         | 0.2%    |
| ZTE WCDMA Technologies MSM        | 2         | 0.13%   |
| NetGear                           | 2         | 0.13%   |
| JMicron Technology                | 2         | 0.13%   |
| Apple                             | 2         | 0.13%   |
| TRENDnet                          | 1         | 0.07%   |
| Toshiba                           | 1         | 0.07%   |
| Sitecom Europe                    | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.07%   |
| NEC Computers                     | 1         | 0.07%   |
| Motorola PCS                      | 1         | 0.07%   |
| LSI                               | 1         | 0.07%   |
| Linksys                           | 1         | 0.07%   |
| LG Electronics                    | 1         | 0.07%   |
| ICS Advent                        | 1         | 0.07%   |
| HMD Global                        | 1         | 0.07%   |
| Fibocom                           | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 293       | 15.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 97        | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 50        | 2.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 41        | 2.22%   |
| Intel Wireless 8260                                               | 39        | 2.11%   |
| Intel Wi-Fi 6 AX201                                               | 38        | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 36        | 1.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 35        | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 34        | 1.84%   |
| Intel Wireless 7260                                               | 31        | 1.68%   |
| Intel Wi-Fi 6 AX200                                               | 29        | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 28        | 1.52%   |
| Intel Wireless 8265 / 8275                                        | 28        | 1.52%   |
| Intel Wireless 7265                                               | 28        | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 27        | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 25        | 1.36%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 24        | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 22        | 1.19%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 21        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 18        | 0.98%   |
| Intel Wireless 3165                                               | 18        | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 17        | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.87%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 16        | 0.87%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 16        | 0.87%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 16        | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                     | 16        | 0.87%   |
| Nvidia MCP79 Ethernet                                             | 14        | 0.76%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 13        | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 13        | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 13        | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 0.7%    |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 12        | 0.65%   |
| Intel Centrino Advanced-N 6235                                    | 12        | 0.65%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 12        | 0.65%   |
| Intel Wireless 3160                                               | 11        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 435       | 42.65%  |
| Qualcomm Atheros      | 203       | 19.9%   |
| Realtek Semiconductor | 159       | 15.59%  |
| Broadcom              | 135       | 13.24%  |
| Broadcom Limited      | 30        | 2.94%   |
| Ralink                | 13        | 1.27%   |
| TP-Link               | 10        | 0.98%   |
| Sierra Wireless       | 8         | 0.78%   |
| Ralink Technology     | 8         | 0.78%   |
| MediaTek              | 5         | 0.49%   |
| Qualcomm              | 3         | 0.29%   |
| D-Link                | 3         | 0.29%   |
| TRENDnet              | 1         | 0.1%    |
| Sitecom Europe        | 1         | 0.1%    |
| NetGear               | 1         | 0.1%    |
| Fibocom               | 1         | 0.1%    |
| Edimax Technology     | 1         | 0.1%    |
| Dell                  | 1         | 0.1%    |
| D-Link System         | 1         | 0.1%    |
| ASUSTek Computer      | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 50        | 4.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 41        | 4%      |
| Intel Wireless 8260                                            | 39        | 3.8%    |
| Intel Wi-Fi 6 AX201                                            | 38        | 3.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 35        | 3.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 34        | 3.32%   |
| Intel Wireless 7260                                            | 31        | 3.02%   |
| Intel Wi-Fi 6 AX200                                            | 29        | 2.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 28        | 2.73%   |
| Intel Wireless 8265 / 8275                                     | 28        | 2.73%   |
| Intel Wireless 7265                                            | 28        | 2.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 27        | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 25        | 2.44%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 24        | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 22        | 2.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 18        | 1.76%   |
| Intel Wireless 3165                                            | 18        | 1.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 17        | 1.66%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 16        | 1.56%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 16        | 1.56%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 16        | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                  | 16        | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 13        | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 13        | 1.27%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 12        | 1.17%   |
| Intel Centrino Advanced-N 6235                                 | 12        | 1.17%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 12        | 1.17%   |
| Intel Wireless 3160                                            | 11        | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 11        | 1.07%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 10        | 0.98%   |
| Intel Centrino Advanced-N 6200                                 | 10        | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 9         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 9         | 0.88%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 9         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 8         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 8         | 0.78%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 8         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 417       | 52.72%  |
| Intel                      | 162       | 20.48%  |
| Qualcomm Atheros           | 58        | 7.33%   |
| Broadcom                   | 54        | 6.83%   |
| Marvell Technology Group   | 20        | 2.53%   |
| Nvidia                     | 17        | 2.15%   |
| ASIX Electronics           | 8         | 1.01%   |
| Broadcom Limited           | 7         | 0.88%   |
| Xiaomi                     | 6         | 0.76%   |
| Huawei Technologies        | 6         | 0.76%   |
| MediaTek                   | 4         | 0.51%   |
| Qualcomm                   | 3         | 0.38%   |
| OPPO Electronics           | 3         | 0.38%   |
| Lenovo                     | 3         | 0.38%   |
| Google                     | 3         | 0.38%   |
| Samsung Electronics        | 2         | 0.25%   |
| JMicron Technology         | 2         | 0.25%   |
| Hewlett-Packard            | 2         | 0.25%   |
| D-Link                     | 2         | 0.25%   |
| Apple                      | 2         | 0.25%   |
| ZTE WCDMA Technologies MSM | 1         | 0.13%   |
| NetGear                    | 1         | 0.13%   |
| LSI                        | 1         | 0.13%   |
| Linksys                    | 1         | 0.13%   |
| LG Electronics             | 1         | 0.13%   |
| ICS Advent                 | 1         | 0.13%   |
| HMD Global                 | 1         | 0.13%   |
| DisplayLink                | 1         | 0.13%   |
| Attansic Technology        | 1         | 0.13%   |
| ADMtek                     | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 293       | 36.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 97        | 12.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 36        | 4.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 21        | 2.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 19        | 2.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 16        | 2.01%   |
| Nvidia MCP79 Ethernet                                                          | 14        | 1.75%   |
| Intel Ethernet Connection I219-LM                                              | 13        | 1.63%   |
| Intel Ethernet Connection I218-LM                                              | 13        | 1.63%   |
| Intel 82577LM Gigabit Network Connection                                       | 13        | 1.63%   |
| Intel 82567LM Gigabit Network Connection                                       | 10        | 1.25%   |
| Intel Ethernet Connection (4) I219-V                                           | 9         | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                                          | 9         | 1.13%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 1%      |
| Intel Ethernet Connection I219-V                                               | 7         | 0.88%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 7         | 0.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 6         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.75%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 6         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 6         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 5         | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 5         | 0.63%   |
| Intel Ethernet Connection I217-V                                               | 5         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 4         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 4         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 4         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 0.5%    |
| MediaTek Armor X10 Pro                                                         | 4         | 0.5%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.5%    |
| Huawei LLD-L21                                                                 | 4         | 0.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                                         | 3         | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.38%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 3         | 0.38%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 3         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 971       | 55.49%  |
| Ethernet | 758       | 43.31%  |
| Modem    | 18        | 1.03%   |
| Unknown  | 3         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 831       | 84.19%  |
| Ethernet | 156       | 15.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 707       | 71.92%  |
| 1     | 252       | 25.64%  |
| 0     | 19        | 1.93%   |
| 3     | 5         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 765       | 77.04%  |
| Yes     | 227       | 22.86%  |
| Unknown | 1         | 0.1%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 352       | 41.66%  |
| Realtek Semiconductor           | 91        | 10.77%  |
| Apple                           | 90        | 10.65%  |
| Qualcomm Atheros Communications | 84        | 9.94%   |
| Lite-On Technology              | 44        | 5.21%   |
| Broadcom                        | 44        | 5.21%   |
| Foxconn / Hon Hai               | 35        | 4.14%   |
| IMC Networks                    | 24        | 2.84%   |
| Toshiba                         | 15        | 1.78%   |
| Hewlett-Packard                 | 14        | 1.66%   |
| Dell                            | 13        | 1.54%   |
| Cambridge Silicon Radio         | 13        | 1.54%   |
| Ralink                          | 9         | 1.07%   |
| Realtek                         | 8         | 0.95%   |
| Qcom                            | 2         | 0.24%   |
| ASUSTek Computer                | 2         | 0.24%   |
| Taiyo Yuden                     | 1         | 0.12%   |
| Logitech                        | 1         | 0.12%   |
| Fujitsu                         | 1         | 0.12%   |
| Foxconn International           | 1         | 0.12%   |
| Askey Computer                  | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 157       | 18.58%  |
| Intel AX201 Bluetooth                                                               | 67        | 7.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 56        | 6.63%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 47        | 5.56%   |
| Apple Bluetooth Host Controller                                                     | 46        | 5.44%   |
| Realtek Bluetooth Radio                                                             | 42        | 4.97%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 34        | 4.02%   |
| Intel AX200 Bluetooth                                                               | 29        | 3.43%   |
| Apple Bluetooth USB Host Controller                                                 | 28        | 3.31%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 18        | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 17        | 2.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 15        | 1.78%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 14        | 1.66%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 13        | 1.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 13        | 1.54%   |
| Lite-On Bluetooth Device                                                            | 11        | 1.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 11        | 1.3%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 1.18%   |
| Apple Bluetooth HCI                                                                 | 10        | 1.18%   |
| Ralink RT3290 Bluetooth                                                             | 9         | 1.07%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 9         | 1.07%   |
| Realtek Bluetooth Radio                                                             | 8         | 0.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 0.95%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 8         | 0.95%   |
| IMC Networks Bluetooth Radio                                                        | 8         | 0.95%   |
| Realtek RTL8821A Bluetooth                                                          | 7         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 7         | 0.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 0.83%   |
| Dell DW375 Bluetooth Module                                                         | 7         | 0.83%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 6         | 0.71%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 6         | 0.71%   |
| Intel AX210 Bluetooth                                                               | 5         | 0.59%   |
| IMC Networks Bluetooth Device                                                       | 5         | 0.59%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.59%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 5         | 0.59%   |
| Toshiba RT Bluetooth Radio                                                          | 4         | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 4         | 0.47%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 0.47%   |
| Lite-On Atheros Bluetooth                                                           | 4         | 0.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 805       | 70.61%  |
| AMD                        | 178       | 15.61%  |
| Nvidia                     | 114       | 10%     |
| C-Media Electronics        | 7         | 0.61%   |
| Logitech                   | 6         | 0.53%   |
| Generalplus Technology     | 4         | 0.35%   |
| Realtek Semiconductor      | 3         | 0.26%   |
| GN Netcom                  | 3         | 0.26%   |
| Texas Instruments          | 2         | 0.18%   |
| ESS Technology             | 2         | 0.18%   |
| BEHRINGER International    | 2         | 0.18%   |
| YUAN High-Tech Development | 1         | 0.09%   |
| Trust                      | 1         | 0.09%   |
| TEAC                       | 1         | 0.09%   |
| SteelSeries ApS            | 1         | 0.09%   |
| No brand                   | 1         | 0.09%   |
| Native Instruments         | 1         | 0.09%   |
| Midiplus                   | 1         | 0.09%   |
| JMTek                      | 1         | 0.09%   |
| Huawei Technologies        | 1         | 0.09%   |
| Hewlett-Packard            | 1         | 0.09%   |
| Goldvish                   | 1         | 0.09%   |
| Dell                       | 1         | 0.09%   |
| Corsair                    | 1         | 0.09%   |
| Apple                      | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 130       | 9.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 99        | 7.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 81        | 5.78%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 76        | 5.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 55        | 3.93%   |
| Intel 8 Series HD Audio Controller                                                                | 55        | 3.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 48        | 3.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 48        | 3.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 42        | 3%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 40        | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 38        | 2.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 36        | 2.57%   |
| Intel Broadwell-U Audio Controller                                                                | 36        | 2.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 33        | 2.36%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 31        | 2.21%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 30        | 2.14%   |
| AMD FCH Azalia Controller                                                                         | 28        | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 26        | 1.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 26        | 1.86%   |
| AMD Kabini HDMI/DP Audio                                                                          | 26        | 1.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 23        | 1.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 20        | 1.43%   |
| AMD High Definition Audio Controller                                                              | 20        | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 19        | 1.36%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 18        | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 15        | 1.07%   |
| Nvidia MCP79 High Definition Audio                                                                | 14        | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 13        | 0.93%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 13        | 0.93%   |
| Intel Comet Lake PCH cAVS                                                                         | 12        | 0.86%   |
| Intel CM238 HD Audio Controller                                                                   | 12        | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 11        | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 11        | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 10        | 0.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 0.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 0.57%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 106       | 29.69%  |
| SK hynix            | 72        | 20.17%  |
| Micron Technology   | 50        | 14.01%  |
| Kingston            | 28        | 7.84%   |
| Unknown             | 21        | 5.88%   |
| Crucial             | 13        | 3.64%   |
| Elpida              | 12        | 3.36%   |
| A-DATA Technology   | 8         | 2.24%   |
| Unknown (ABCD)      | 7         | 1.96%   |
| Ramaxel Technology  | 6         | 1.68%   |
| Smart               | 3         | 0.84%   |
| GSkill              | 3         | 0.84%   |
| G.Skill             | 3         | 0.84%   |
| Transcend           | 2         | 0.56%   |
| Nanya Technology    | 2         | 0.56%   |
| Multilaser          | 2         | 0.56%   |
| Corsair             | 2         | 0.56%   |
| Toshiba             | 1         | 0.28%   |
| Timetec             | 1         | 0.28%   |
| Team                | 1         | 0.28%   |
| Smart Brazil        | 1         | 0.28%   |
| SHARETRONIC         | 1         | 0.28%   |
| Qimonda             | 1         | 0.28%   |
| pqi                 | 1         | 0.28%   |
| PNY                 | 1         | 0.28%   |
| Patriot             | 1         | 0.28%   |
| Melco               | 1         | 0.28%   |
| Magnum Tech         | 1         | 0.28%   |
| Kllisre             | 1         | 0.28%   |
| Avant               | 1         | 0.28%   |
| AMD                 | 1         | 0.28%   |
| Aeneon              | 1         | 0.28%   |
| A Force             | 1         | 0.28%   |
| Unknown             | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.84%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 1.84%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 6         | 1.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 1.58%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 4         | 1.05%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.05%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 4         | 1.05%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.05%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.05%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 3         | 0.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.79%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.79%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.79%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 3         | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.79%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 3         | 0.79%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 3         | 0.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.79%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 3         | 0.79%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.79%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 0.79%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s         | 3         | 0.79%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.79%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.79%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.79%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 3         | 0.79%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 2         | 0.53%   |
| Smart RAM SG564283FG8NWKF-Z1 1024MB SODIMM DDR2 800MT/s          | 2         | 0.53%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.53%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1333MT/s                  | 2         | 0.53%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.53%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.53%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.53%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 122       | 41.08%  |
| DDR3   | 117       | 39.39%  |
| LPDDR4 | 26        | 8.75%   |
| DDR2   | 16        | 5.39%   |
| LPDDR3 | 11        | 3.7%    |
| SDRAM  | 4         | 1.35%   |
| DDR5   | 1         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 262       | 87.04%  |
| Row Of Chips | 31        | 10.3%   |
| Chip         | 4         | 1.33%   |
| DIMM         | 3         | 1%      |
| Unknown      | 1         | 0.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 137       | 40.18%  |
| 4096  | 106       | 31.09%  |
| 2048  | 54        | 15.84%  |
| 16384 | 30        | 8.8%    |
| 1024  | 10        | 2.93%   |
| 32768 | 4         | 1.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 81        | 24.62%  |
| 2667    | 67        | 20.36%  |
| 3200    | 38        | 11.55%  |
| 2133    | 26        | 7.9%    |
| 2400    | 25        | 7.6%    |
| 1334    | 17        | 5.17%   |
| 1333    | 15        | 4.56%   |
| 4267    | 12        | 3.65%   |
| 667     | 9         | 2.74%   |
| 1067    | 7         | 2.13%   |
| 800     | 7         | 2.13%   |
| 1066    | 5         | 1.52%   |
| 1867    | 4         | 1.22%   |
| 8400    | 3         | 0.91%   |
| 4199    | 3         | 0.91%   |
| 3266    | 3         | 0.91%   |
| 4266    | 2         | 0.61%   |
| 4800    | 1         | 0.3%    |
| 3733    | 1         | 0.3%    |
| 2048    | 1         | 0.3%    |
| 975     | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Xerox                           | 2         | 16.67%  |
| Seiko Epson                     | 2         | 16.67%  |
| Hewlett-Packard                 | 2         | 16.67%  |
| Canon                           | 2         | 16.67%  |
| Samsung Electronics             | 1         | 8.33%   |
| Prolific Technology             | 1         | 8.33%   |
| cab Produkttechnik GmbH & Co KG | 1         | 8.33%   |
| Brother Industries              | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Xerox Phaser 3610                        | 1         | 8.33%   |
| Xerox Phaser 3040                        | 1         | 8.33%   |
| Seiko Epson XP-200 Series                | 1         | 8.33%   |
| Seiko Epson L355 Series                  | 1         | 8.33%   |
| Samsung M2020 Series                     | 1         | 8.33%   |
| Prolific PL2305 Parallel Port            | 1         | 8.33%   |
| HP Deskjet F4500 series                  | 1         | 8.33%   |
| HP DeskJet 2620 All-in-One Printer       | 1         | 8.33%   |
| Canon PIXMA MG2500 Series                | 1         | 8.33%   |
| Canon G3000 series                       | 1         | 8.33%   |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 8.33%   |
| Brother MFC-T800W                        | 1         | 8.33%   |

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
| Chicony Electronics                    | 211       | 23.68%  |
| Realtek Semiconductor                  | 86        | 9.65%   |
| IMC Networks                           | 79        | 8.87%   |
| Apple                                  | 67        | 7.52%   |
| Microdia                               | 61        | 6.85%   |
| Quanta                                 | 53        | 5.95%   |
| Sunplus Innovation Technology          | 50        | 5.61%   |
| Bison Electronics                      | 42        | 4.71%   |
| Cheng Uei Precision Industry (Foxlink) | 40        | 4.49%   |
| Suyin                                  | 30        | 3.37%   |
| Syntek                                 | 28        | 3.14%   |
| Acer                                   | 22        | 2.47%   |
| Silicon Motion                         | 20        | 2.24%   |
| Alcor Micro                            | 18        | 2.02%   |
| Lite-On Technology                     | 17        | 1.91%   |
| Lenovo                                 | 10        | 1.12%   |
| Luxvisions Innotech Limited            | 8         | 0.9%    |
| Ricoh                                  | 7         | 0.79%   |
| Importek                               | 6         | 0.67%   |
| Logitech                               | 5         | 0.56%   |
| ALi                                    | 4         | 0.45%   |
| Samsung Electronics                    | 3         | 0.34%   |
| Primax Electronics                     | 3         | 0.34%   |
| LG Electronics                         | 3         | 0.34%   |
| KYE Systems (Mouse Systems)            | 2         | 0.22%   |
| Foxconn / Hon Hai                      | 2         | 0.22%   |
| Z-Star Microelectronics                | 1         | 0.11%   |
| Y Media                                | 1         | 0.11%   |
| USB Camera                             | 1         | 0.11%   |
| SunplusIT                              | 1         | 0.11%   |
| Sunplus Technology                     | 1         | 0.11%   |
| Sony                                   | 1         | 0.11%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.11%   |
| kingcome                               | 1         | 0.11%   |
| Jieli Technology                       | 1         | 0.11%   |
| Intel                                  | 1         | 0.11%   |
| Google                                 | 1         | 0.11%   |
| Cubeternet                             | 1         | 0.11%   |
| Cisco Systems                          | 1         | 0.11%   |
| 2M UVC CAMERA                          | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 46        | 5.15%   |
| Chicony HD WebCam                                | 25        | 2.8%    |
| IMC Networks USB2.0 HD UVC WebCam                | 24        | 2.68%   |
| Realtek Integrated_Webcam_HD                     | 23        | 2.57%   |
| Apple FaceTime HD Camera                         | 21        | 2.35%   |
| IMC Networks Integrated Camera                   | 20        | 2.24%   |
| Apple Built-in iSight                            | 19        | 2.13%   |
| Microdia Integrated_Webcam_HD                    | 18        | 2.01%   |
| Syntek Integrated Camera                         | 13        | 1.45%   |
| Sunplus Integrated_Webcam_HD                     | 12        | 1.34%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 12        | 1.34%   |
| Quanta HP Webcam                                 | 10        | 1.12%   |
| Lite-On Integrated Camera                        | 10        | 1.12%   |
| Chicony HP HD Webcam [Fixed]                     | 10        | 1.12%   |
| Realtek USB Camera                               | 9         | 1.01%   |
| Quanta HP TrueVision HD Camera                   | 9         | 1.01%   |
| Microdia Integrated Webcam                       | 9         | 1.01%   |
| Syntek EasyCamera                                | 8         | 0.89%   |
| Sunplus HD WebCam                                | 8         | 0.89%   |
| Realtek USB2.0 HD UVC WebCam                     | 8         | 0.89%   |
| Realtek Integrated Webcam                        | 8         | 0.89%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 8         | 0.89%   |
| Chicony HP Truevision HD                         | 8         | 0.89%   |
| Chicony HP HD Camera                             | 8         | 0.89%   |
| Chicony EasyCamera                               | 8         | 0.89%   |
| Syntek Lenovo EasyCamera                         | 7         | 0.78%   |
| Chicony VGA WebCam                               | 7         | 0.78%   |
| Chicony USB 2.0 Camera                           | 7         | 0.78%   |
| Chicony HP TrueVision HD Camera                  | 7         | 0.78%   |
| Chicony HP HD Webcam                             | 7         | 0.78%   |
| Apple FaceTime Camera                            | 7         | 0.78%   |
| Acer Integrated Camera                           | 7         | 0.78%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 6         | 0.67%   |
| Realtek HD WebCam                                | 6         | 0.67%   |
| Quanta VGA WebCam                                | 6         | 0.67%   |
| Chicony TOSHIBA Web Camera - HD                  | 6         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 6         | 0.67%   |
| Apple FaceTime HD Camera (Built-in)              | 6         | 0.67%   |
| Silicon Motion Web Camera                        | 5         | 0.56%   |
| Quanta HD User Facing                            | 5         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 67        | 38.51%  |
| Synaptics                  | 36        | 20.69%  |
| Shenzhen Goodix Technology | 27        | 15.52%  |
| LighTuning Technology      | 14        | 8.05%   |
| Upek                       | 10        | 5.75%   |
| Elan Microelectronics      | 10        | 5.75%   |
| AuthenTec                  | 7         | 4.02%   |
| STMicroelectronics         | 2         | 1.15%   |
| Focal-systems.Corp         | 1         | 0.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 21        | 12.07%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 7.47%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 6.32%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 6.32%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 5.75%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 5.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 4.6%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 4.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 4.02%   |
| Elan ELAN:Fingerprint                                                      | 7         | 4.02%   |
| Validity Sensors VFS491                                                    | 6         | 3.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 2.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.3%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 2.3%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.3%    |
| AuthenTec Fingerprint Sensor                                               | 4         | 2.3%    |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.72%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.72%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.72%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.72%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.72%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.15%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.15%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.15%   |
| Synaptics  WBDI                                                            | 2         | 1.15%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.15%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.15%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.15%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.57%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.57%   |
| Synaptics WBDI                                                             | 1         | 0.57%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.57%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.57%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.57%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.57%   |
| AuthenTec AES2810                                                          | 1         | 0.57%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.57%   |
| AuthenTec AES1600                                                          | 1         | 0.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 28        | 45.9%   |
| Alcor Micro           | 17        | 27.87%  |
| O2 Micro              | 6         | 9.84%   |
| Lenovo                | 5         | 8.2%    |
| Upek                  | 4         | 6.56%   |
| Gemalto (was Gemplus) | 1         | 1.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 17        | 27.87%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 22.95%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 11.48%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 8.2%    |
| Lenovo Integrated Smart Card Reader                                          | 5         | 8.2%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 6.56%   |
| Broadcom 5880                                                                | 4         | 6.56%   |
| Broadcom 58200                                                               | 3         | 4.92%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.64%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 643       | 64.88%  |
| 1     | 276       | 27.85%  |
| 2     | 64        | 6.46%   |
| 3     | 7         | 0.71%   |
| 7     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 172       | 40.09%  |
| Chipcard                 | 59        | 13.75%  |
| Net/wireless             | 57        | 13.29%  |
| Graphics card            | 53        | 12.35%  |
| Multimedia controller    | 47        | 10.96%  |
| Camera                   | 9         | 2.1%    |
| Bluetooth                | 9         | 2.1%    |
| Storage                  | 8         | 1.86%   |
| Net/ethernet             | 7         | 1.63%   |
| Card reader              | 4         | 0.93%   |
| Sound                    | 3         | 0.7%    |
| Communication controller | 1         | 0.23%   |

