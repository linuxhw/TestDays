Linux in Czechia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

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

Total: 1580

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| UMAX          | VisionBook-N12R             | [2477ae9a0e](https://linux-hardware.org/?probe=2477ae9a0e) | Feb 27, 2023 |
| Standard      | Unknown                     | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [f0fa613cd2](https://linux-hardware.org/?probe=f0fa613cd2) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | Latitude 5420               | [231c7534d3](https://linux-hardware.org/?probe=231c7534d3) | Feb 21, 2023 |
| HP            | Laptop 15-rb0xx             | [3dd7359a43](https://linux-hardware.org/?probe=3dd7359a43) | Feb 20, 2023 |
| HP            | Laptop 15-rb0xx             | [53ef54922c](https://linux-hardware.org/?probe=53ef54922c) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| Toshiba       | Satellite L50D-B            | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| Dell          | Vostro1710                  | [91b1af7ed6](https://linux-hardware.org/?probe=91b1af7ed6) | Feb 19, 2023 |
| Standard      | Unknown                     | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | UX31E                       | [4c3c50a992](https://linux-hardware.org/?probe=4c3c50a992) | Feb 18, 2023 |
| ASUSTek       | UX31E                       | [e6391763b2](https://linux-hardware.org/?probe=e6391763b2) | Feb 17, 2023 |
| HP            | Laptop 17-cn0xxx            | [0e2199617b](https://linux-hardware.org/?probe=0e2199617b) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [6c8bdf1f73](https://linux-hardware.org/?probe=6c8bdf1f73) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [89f9d45c66](https://linux-hardware.org/?probe=89f9d45c66) | Feb 17, 2023 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [f546833d76](https://linux-hardware.org/?probe=f546833d76) | Feb 17, 2023 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [1026c10fa9](https://linux-hardware.org/?probe=1026c10fa9) | Feb 16, 2023 |
| ASUSTek       | UX31E                       | [0255141f61](https://linux-hardware.org/?probe=0255141f61) | Feb 15, 2023 |
| HP            | ProBook 470 G4              | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| HP            | Pavilion g6                 | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| HP            | OMEN by Laptop              | [849a50c7fd](https://linux-hardware.org/?probe=849a50c7fd) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| Acer          | Swift SF314-42              | [938edcc32a](https://linux-hardware.org/?probe=938edcc32a) | Feb 15, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| MSI           | GX700                       | [11154709fd](https://linux-hardware.org/?probe=11154709fd) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| ASUSTek       | UX31E                       | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [16d6cdad97](https://linux-hardware.org/?probe=16d6cdad97) | Feb 09, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| HP            | Laptop 15-db0xxx            | [8cb1801046](https://linux-hardware.org/?probe=8cb1801046) | Feb 07, 2023 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [e9082b6ebf](https://linux-hardware.org/?probe=e9082b6ebf) | Feb 04, 2023 |
| HP            | OMEN by Laptop              | [330da24dc9](https://linux-hardware.org/?probe=330da24dc9) | Feb 04, 2023 |
| HP            | ProBook 4530s               | [9ff88cbe9a](https://linux-hardware.org/?probe=9ff88cbe9a) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | [922ee5ede0](https://linux-hardware.org/?probe=922ee5ede0) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [0b73c3afe8](https://linux-hardware.org/?probe=0b73c3afe8) | Feb 03, 2023 |
| HP            | Stream Notebook PC 14       | [69628da41b](https://linux-hardware.org/?probe=69628da41b) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | [3bcca39276](https://linux-hardware.org/?probe=3bcca39276) | Feb 02, 2023 |
| HP            | OMEN by Laptop              | [1651e1e5af](https://linux-hardware.org/?probe=1651e1e5af) | Feb 02, 2023 |
| ASUSTek       | GL702VT                     | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| Lenovo        | ThinkPad E520 1143JYG       | [87735dd3b0](https://linux-hardware.org/?probe=87735dd3b0) | Feb 01, 2023 |
| HP            | Laptop 15-bw0xx             | [b7fce61d74](https://linux-hardware.org/?probe=b7fce61d74) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
| HP            | Compaq CQ58                 | [63dfd6ca48](https://linux-hardware.org/?probe=63dfd6ca48) | Jan 30, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| ASUSTek       | X200MA                      | [1c1f2d4d5b](https://linux-hardware.org/?probe=1c1f2d4d5b) | Jan 28, 2023 |
| Timi          | A35S                        | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| ASUSTek       | UX31E                       | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| HP            | EliteBook 8460p             | [bb83f545f7](https://linux-hardware.org/?probe=bb83f545f7) | Jan 24, 2023 |
| Dell          | Latitude 5530               | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Dell          | Precision 3530              | [f0fa541c85](https://linux-hardware.org/?probe=f0fa541c85) | Jan 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| ASUSTek       | UX303LN                     | [60f8946cdf](https://linux-hardware.org/?probe=60f8946cdf) | Jan 21, 2023 |
| Lenovo        | Yoga 700-14ISK 80QD         | [4e07ace043](https://linux-hardware.org/?probe=4e07ace043) | Jan 21, 2023 |
| ASUSTek       | UX303LN                     | [846e3df466](https://linux-hardware.org/?probe=846e3df466) | Jan 21, 2023 |
| HP            | EliteBook 8570p             | [66c806fbfe](https://linux-hardware.org/?probe=66c806fbfe) | Jan 21, 2023 |
| ASUSTek       | X555LF                      | [7220c25a3b](https://linux-hardware.org/?probe=7220c25a3b) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6c2dd878d0](https://linux-hardware.org/?probe=6c2dd878d0) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5f73278ca0](https://linux-hardware.org/?probe=5f73278ca0) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f7fcfb7b18](https://linux-hardware.org/?probe=f7fcfb7b18) | Jan 19, 2023 |
| ASUSTek       | 1011PX                      | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad E550 20DF0081MC    | [1b7e734f36](https://linux-hardware.org/?probe=1b7e734f36) | Jan 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [5b0e671bb8](https://linux-hardware.org/?probe=5b0e671bb8) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [395a44652b](https://linux-hardware.org/?probe=395a44652b) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [fa4fd9061f](https://linux-hardware.org/?probe=fa4fd9061f) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [6841633faf](https://linux-hardware.org/?probe=6841633faf) | Jan 16, 2023 |
| HP            | Pavilion dv6500             | [33985f088a](https://linux-hardware.org/?probe=33985f088a) | Jan 16, 2023 |
| HP            | 250 G3                      | [717fbc7972](https://linux-hardware.org/?probe=717fbc7972) | Jan 15, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [32f2651aa1](https://linux-hardware.org/?probe=32f2651aa1) | Jan 14, 2023 |
| HP            | ProBook 6560b               | [a9eba68b79](https://linux-hardware.org/?probe=a9eba68b79) | Jan 14, 2023 |
| ASUSTek       | UX31E                       | [d60bab803e](https://linux-hardware.org/?probe=d60bab803e) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Lenovo        | ThinkPad T450 20BUA0UG00    | [b0854ecbf8](https://linux-hardware.org/?probe=b0854ecbf8) | Jan 12, 2023 |
| Acer          | Extensa 2519                | [c044faaa05](https://linux-hardware.org/?probe=c044faaa05) | Jan 11, 2023 |
| Dell          | Precision 7710              | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| HP            | Laptop 15-rb0xx             | [fd8d969adb](https://linux-hardware.org/?probe=fd8d969adb) | Jan 11, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [e4c19089b5](https://linux-hardware.org/?probe=e4c19089b5) | Jan 11, 2023 |
| Dell          | Precision 5510              | [22a344ddad](https://linux-hardware.org/?probe=22a344ddad) | Jan 09, 2023 |
| HP            | EliteBook 840 G1            | [42f10f6d45](https://linux-hardware.org/?probe=42f10f6d45) | Jan 09, 2023 |
| Dell          | Precision 7710              | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| Lenovo        | ThinkPad X230 2320JNG       | [29d3023af5](https://linux-hardware.org/?probe=29d3023af5) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | [667330c83f](https://linux-hardware.org/?probe=667330c83f) | Jan 07, 2023 |
| UMAX          | VisionBook N14G Plus        | [412180b4de](https://linux-hardware.org/?probe=412180b4de) | Jan 06, 2023 |
| Acer          | TravelMate B115-M           | [c39cf71ff8](https://linux-hardware.org/?probe=c39cf71ff8) | Jan 05, 2023 |
| ASUSTek       | X405UA                      | [c56206ea8a](https://linux-hardware.org/?probe=c56206ea8a) | Jan 05, 2023 |
| Acer          | Aspire E1-531G              | [9b5a0200df](https://linux-hardware.org/?probe=9b5a0200df) | Jan 04, 2023 |
| Acer          | Aspire E1-531G              | [47813fa627](https://linux-hardware.org/?probe=47813fa627) | Jan 03, 2023 |
| HP            | ProBook 635 Aero G8         | [f710248f3c](https://linux-hardware.org/?probe=f710248f3c) | Jan 02, 2023 |
| Google        | Chell                       | [02a0ae3bea](https://linux-hardware.org/?probe=02a0ae3bea) | Jan 02, 2023 |
| Valve         | Jupiter                     | [dc3612b4e1](https://linux-hardware.org/?probe=dc3612b4e1) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Acer          | Aspire A515-47              | [aaf0830ffc](https://linux-hardware.org/?probe=aaf0830ffc) | Jan 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [bd53b75b7b](https://linux-hardware.org/?probe=bd53b75b7b) | Dec 30, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [2b646304f0](https://linux-hardware.org/?probe=2b646304f0) | Dec 29, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [74f8dcfbb4](https://linux-hardware.org/?probe=74f8dcfbb4) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK E736               | [8d54484965](https://linux-hardware.org/?probe=8d54484965) | Dec 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| UMAX          | VisionBook 14Wa Pro         | [7eb49ce0ab](https://linux-hardware.org/?probe=7eb49ce0ab) | Dec 24, 2022 |
| UMAX          | VisionBook 14Wa Pro         | [4123115ef0](https://linux-hardware.org/?probe=4123115ef0) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2b25ab8790](https://linux-hardware.org/?probe=2b25ab8790) | Dec 22, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [af14f0c425](https://linux-hardware.org/?probe=af14f0c425) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [e7393fd2b7](https://linux-hardware.org/?probe=e7393fd2b7) | Dec 20, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c20be92503](https://linux-hardware.org/?probe=c20be92503) | Dec 19, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [3fe5be03b1](https://linux-hardware.org/?probe=3fe5be03b1) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [b34d0f3a2c](https://linux-hardware.org/?probe=b34d0f3a2c) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | [651fa58fbd](https://linux-hardware.org/?probe=651fa58fbd) | Dec 12, 2022 |
| HP            | Pavilion TS 11              | [db2a3e8ebb](https://linux-hardware.org/?probe=db2a3e8ebb) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | [b5d4116615](https://linux-hardware.org/?probe=b5d4116615) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | [144f698515](https://linux-hardware.org/?probe=144f698515) | Dec 11, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [6e2cf6514a](https://linux-hardware.org/?probe=6e2cf6514a) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [b9ea8b5b2b](https://linux-hardware.org/?probe=b9ea8b5b2b) | Dec 08, 2022 |
| ASUSTek       | X55A                        | [283ef64c76](https://linux-hardware.org/?probe=283ef64c76) | Dec 08, 2022 |
| ASUSTek       | UX31E                       | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| MSI           | Prestige 14 A11SCX          | [2b5a2c145c](https://linux-hardware.org/?probe=2b5a2c145c) | Dec 06, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [2f14f32399](https://linux-hardware.org/?probe=2f14f32399) | Dec 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS2291X    | [312119ddbd](https://linux-hardware.org/?probe=312119ddbd) | Dec 06, 2022 |
| MSI           | Prestige 14 A11SCX          | [ca5bc5dfe6](https://linux-hardware.org/?probe=ca5bc5dfe6) | Dec 05, 2022 |
| ASUSTek       | UX31E                       | [7bde8b90c7](https://linux-hardware.org/?probe=7bde8b90c7) | Dec 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [e44ba4a41b](https://linux-hardware.org/?probe=e44ba4a41b) | Dec 03, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [2b1a977b21](https://linux-hardware.org/?probe=2b1a977b21) | Dec 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5955142015](https://linux-hardware.org/?probe=5955142015) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ea8b9066f6](https://linux-hardware.org/?probe=ea8b9066f6) | Nov 30, 2022 |
| HP            | 620                         | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| Fujitsu       | LIFEBOOK E756               | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [53b311f78c](https://linux-hardware.org/?probe=53b311f78c) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| HP            | 620                         | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| MSI           | Modern 14 B5M               | [2bd9abfe2c](https://linux-hardware.org/?probe=2bd9abfe2c) | Nov 20, 2022 |
| ASUSTek       | N73SV                       | [10840bac50](https://linux-hardware.org/?probe=10840bac50) | Nov 20, 2022 |
| ASUSTek       | K50IJ                       | [c57a9ae3d5](https://linux-hardware.org/?probe=c57a9ae3d5) | Nov 19, 2022 |
| ASUSTek       | K50IJ                       | [99ed91b58d](https://linux-hardware.org/?probe=99ed91b58d) | Nov 19, 2022 |
| Dell          | Precision 5510              | [a9467ec69d](https://linux-hardware.org/?probe=a9467ec69d) | Nov 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3eaa12ef7a](https://linux-hardware.org/?probe=3eaa12ef7a) | Nov 16, 2022 |
| ASUSTek       | K50IJ                       | [c7ac1636bc](https://linux-hardware.org/?probe=c7ac1636bc) | Nov 15, 2022 |
| ASUSTek       | N61Jv                       | [c8c143ccdd](https://linux-hardware.org/?probe=c8c143ccdd) | Nov 14, 2022 |
| ASUSTek       | N61Jv                       | [bc9518dbad](https://linux-hardware.org/?probe=bc9518dbad) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | [a7e35fd231](https://linux-hardware.org/?probe=a7e35fd231) | Nov 12, 2022 |
| Dell          | Latitude 7480               | [62d1e401a4](https://linux-hardware.org/?probe=62d1e401a4) | Nov 12, 2022 |
| HP            | Pavilion g6                 | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| Dell          | Latitude 7480               | [350e3f7ee2](https://linux-hardware.org/?probe=350e3f7ee2) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| HP            | Pavilion dv7                | [5b01559647](https://linux-hardware.org/?probe=5b01559647) | Nov 11, 2022 |
| ASUSTek       | K54LY                       | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| ASUSTek       | X550VXK                     | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Packard Be... | EasyNote TK85               | [8a4f5a2c29](https://linux-hardware.org/?probe=8a4f5a2c29) | Nov 07, 2022 |
| HP            | ProBook 4530s               | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| Dell          | Inspiron 5515               | [fcb59bae39](https://linux-hardware.org/?probe=fcb59bae39) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | [001308a248](https://linux-hardware.org/?probe=001308a248) | Nov 06, 2022 |
| HP            | Pavilion g6                 | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| HP            | Pavilion g6                 | [38b8d5a898](https://linux-hardware.org/?probe=38b8d5a898) | Nov 04, 2022 |
| Acer          | Aspire 5738                 | [f5ac63680f](https://linux-hardware.org/?probe=f5ac63680f) | Nov 04, 2022 |
| SLIMBOOK      | Executive                   | [cff86cc921](https://linux-hardware.org/?probe=cff86cc921) | Nov 04, 2022 |
| Sony          | VPCYB1S1E                   | [54d0a26de9](https://linux-hardware.org/?probe=54d0a26de9) | Nov 03, 2022 |
| UMAX          | VisionBook N15G Plus        | [eba9cd6286](https://linux-hardware.org/?probe=eba9cd6286) | Nov 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | [e4f3828910](https://linux-hardware.org/?probe=e4f3828910) | Nov 01, 2022 |
| ASUSTek       | UX31E                       | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| UMAX          | VisionBook 12Wi 64G         | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| Lenovo        | B590 20206                  | [8a8967999b](https://linux-hardware.org/?probe=8a8967999b) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Dell          | Latitude E6440              | [307356784a](https://linux-hardware.org/?probe=307356784a) | Oct 26, 2022 |
| Apple         | MacBookPro10,1              | [212ce8900d](https://linux-hardware.org/?probe=212ce8900d) | Oct 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| HP            | Pavilion dv7                | [4c6edfec3e](https://linux-hardware.org/?probe=4c6edfec3e) | Oct 18, 2022 |
| HP            | Pavilion dv7                | [22031176a8](https://linux-hardware.org/?probe=22031176a8) | Oct 18, 2022 |
| ASUSTek       | UX31E                       | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| Dell          | XPS 15 9550                 | [00d5f7c4b1](https://linux-hardware.org/?probe=00d5f7c4b1) | Oct 13, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| SmbiosType... | SmbiosType1_SystemProduc... | [d105b4c1f7](https://linux-hardware.org/?probe=d105b4c1f7) | Oct 11, 2022 |
| ASUSTek       | UX31E                       | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| Dell          | Latitude E7250              | [5ecb7bbb6c](https://linux-hardware.org/?probe=5ecb7bbb6c) | Oct 07, 2022 |
| ASUSTek       | 1001PXD                     | [524e4ab046](https://linux-hardware.org/?probe=524e4ab046) | Oct 06, 2022 |
| HP            | EliteBook 1040 G4           | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| Timi          | A35S                        | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | [7c19c1f557](https://linux-hardware.org/?probe=7c19c1f557) | Oct 02, 2022 |
| Acer          | Aspire 7540                 | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| ASUSTek       | K54LY                       | [98197c818f](https://linux-hardware.org/?probe=98197c818f) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [92f9efe077](https://linux-hardware.org/?probe=92f9efe077) | Sep 30, 2022 |
| Notebook      | NJ50GU                      | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [9377d23abd](https://linux-hardware.org/?probe=9377d23abd) | Sep 28, 2022 |
| Timi          | A35S                        | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | K53SV                       | [d2801f9560](https://linux-hardware.org/?probe=d2801f9560) | Sep 26, 2022 |
| Lenovo        | 3000 V100 076346G           | [0575c1ea4f](https://linux-hardware.org/?probe=0575c1ea4f) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| Timi          | RedmiBook 16                | [0a65bab615](https://linux-hardware.org/?probe=0a65bab615) | Sep 25, 2022 |
| Acer          | Aspire VN7-592G             | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| HP            | ProBook 450 G5              | [262ff53f6a](https://linux-hardware.org/?probe=262ff53f6a) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | [d1ed6b20cf](https://linux-hardware.org/?probe=d1ed6b20cf) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | [9e04fb330b](https://linux-hardware.org/?probe=9e04fb330b) | Sep 24, 2022 |
| Timi          | A35S                        | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Valve         | Jupiter                     | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Acer          | Nitro AN515-57              | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [dce5b5917c](https://linux-hardware.org/?probe=dce5b5917c) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| Lenovo        | IdeaPad Y570 20091          | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Dell          | Latitude 5430               | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| Lenovo        | ThinkPad T540p 20BF002CM... | [3343da6005](https://linux-hardware.org/?probe=3343da6005) | Sep 12, 2022 |
| ASUSTek       | UX31E                       | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 23444ZG       | [d83eee9752](https://linux-hardware.org/?probe=d83eee9752) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| UMAX          | VisionBook N15G Plus        | [d17fb4f8f9](https://linux-hardware.org/?probe=d17fb4f8f9) | Sep 11, 2022 |
| Dell          | Latitude 5531               | [66eac260ef](https://linux-hardware.org/?probe=66eac260ef) | Sep 09, 2022 |
| Dell          | Precision 3551              | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
| Lenovo        | B71-80 80RJ                 | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Dell          | Latitude 5531               | [dff44a5e24](https://linux-hardware.org/?probe=dff44a5e24) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| Google        | Coral                       | [af898f9be4](https://linux-hardware.org/?probe=af898f9be4) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| ASUSTek       | UX31E                       | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [60b4add0a0](https://linux-hardware.org/?probe=60b4add0a0) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [2a3eb4b772](https://linux-hardware.org/?probe=2a3eb4b772) | Sep 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cc30fbdce2](https://linux-hardware.org/?probe=cc30fbdce2) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| HP            | EliteBook 650 15.6 inch ... | [918418e0fc](https://linux-hardware.org/?probe=918418e0fc) | Aug 29, 2022 |
| ASUSTek       | X553MA                      | [108e0c7803](https://linux-hardware.org/?probe=108e0c7803) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [bddbedffed](https://linux-hardware.org/?probe=bddbedffed) | Aug 29, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Valve         | Jupiter                     | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| MSI           | GS73VR 6RF                  | [870534e620](https://linux-hardware.org/?probe=870534e620) | Aug 23, 2022 |
| Dell          | Latitude 5490               | [a37eabe03f](https://linux-hardware.org/?probe=a37eabe03f) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2e77015116](https://linux-hardware.org/?probe=2e77015116) | Aug 21, 2022 |
| ASUSTek       | UX31E                       | [84ed4c9d73](https://linux-hardware.org/?probe=84ed4c9d73) | Aug 20, 2022 |
| HP            | ElitePad 1000 G2            | [ed06ba603c](https://linux-hardware.org/?probe=ed06ba603c) | Aug 19, 2022 |
| Lenovo        | ThinkPad Edge E431 62774... | [b7d37d0c4c](https://linux-hardware.org/?probe=b7d37d0c4c) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| HP            | ZBook 15 G3                 | [f89a185aa6](https://linux-hardware.org/?probe=f89a185aa6) | Aug 17, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Acer          | Aspire 3100                 | [8ea61dbd3c](https://linux-hardware.org/?probe=8ea61dbd3c) | Aug 14, 2022 |
| Acer          | Aspire A515-56              | [e93f8de88b](https://linux-hardware.org/?probe=e93f8de88b) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | [e429237c05](https://linux-hardware.org/?probe=e429237c05) | Aug 13, 2022 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [0f367345a0](https://linux-hardware.org/?probe=0f367345a0) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| Dell          | XPS 13 9360                 | [a78c885366](https://linux-hardware.org/?probe=a78c885366) | Aug 12, 2022 |
| Lenovo        | ThinkPad E590 20NB0029MC    | [233b3cdd54](https://linux-hardware.org/?probe=233b3cdd54) | Aug 11, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [8b0ede5e40](https://linux-hardware.org/?probe=8b0ede5e40) | Aug 10, 2022 |
| HUAWEI        | BOHB-WAX9                   | [9d55b54de7](https://linux-hardware.org/?probe=9d55b54de7) | Aug 10, 2022 |
| Dell          | Latitude 5421               | [b088f6b599](https://linux-hardware.org/?probe=b088f6b599) | Aug 10, 2022 |
| Dell          | Latitude 5531               | [64998a7d5a](https://linux-hardware.org/?probe=64998a7d5a) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [9c945add4e](https://linux-hardware.org/?probe=9c945add4e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [d1ab7d1d36](https://linux-hardware.org/?probe=d1ab7d1d36) | Aug 06, 2022 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [2577ffae50](https://linux-hardware.org/?probe=2577ffae50) | Aug 06, 2022 |
| Dell          | Inspiron 5558               | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| HP            | 250 G5 Notebook PC          | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [45e79d015c](https://linux-hardware.org/?probe=45e79d015c) | Jul 23, 2022 |
| ASUSTek       | UX31E                       | [1ae28afad9](https://linux-hardware.org/?probe=1ae28afad9) | Jul 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [c000bcc566](https://linux-hardware.org/?probe=c000bcc566) | Jul 20, 2022 |
| HP            | ProBook 450 G5              | [47c85dbefd](https://linux-hardware.org/?probe=47c85dbefd) | Jul 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [179267a713](https://linux-hardware.org/?probe=179267a713) | Jul 15, 2022 |
| Dell          | G3 3590                     | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | K54LY                       | [9b66e8ad0e](https://linux-hardware.org/?probe=9b66e8ad0e) | Jul 14, 2022 |
| ASUSTek       | UX31E                       | [004f74eaf4](https://linux-hardware.org/?probe=004f74eaf4) | Jul 13, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| HP            | ProBook 450 G5              | [e3962f34e4](https://linux-hardware.org/?probe=e3962f34e4) | Jul 11, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | ProBook 450 G5              | [90f45f2ebc](https://linux-hardware.org/?probe=90f45f2ebc) | Jul 08, 2022 |
| Dell          | XPS 15 9510                 | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6a78826e86](https://linux-hardware.org/?probe=6a78826e86) | Jul 07, 2022 |
| ASUSTek       | X542UQR                     | [04cc10b779](https://linux-hardware.org/?probe=04cc10b779) | Jul 07, 2022 |
| Dell          | Inspiron 3542               | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| HP            | ProBook 4530s               | [db207530bc](https://linux-hardware.org/?probe=db207530bc) | Jul 06, 2022 |
| HP            | Notebook                    | [9b87d6ee2d](https://linux-hardware.org/?probe=9b87d6ee2d) | Jul 06, 2022 |
| Dell          | Latitude 7520               | [531ccedcf2](https://linux-hardware.org/?probe=531ccedcf2) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| HP            | 625                         | [0acc5581d4](https://linux-hardware.org/?probe=0acc5581d4) | Jul 03, 2022 |
| ASUSTek       | UX31E                       | [7504f06baa](https://linux-hardware.org/?probe=7504f06baa) | Jul 02, 2022 |
| Lenovo        | Z70-80 80FG                 | [eaf34443c7](https://linux-hardware.org/?probe=eaf34443c7) | Jul 01, 2022 |
| ASUSTek       | UX31E                       | [d3f27ab291](https://linux-hardware.org/?probe=d3f27ab291) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [bef849e3d1](https://linux-hardware.org/?probe=bef849e3d1) | Jun 29, 2022 |
| Lenovo        | ThinkPad S5-S540 20B3001... | [d5be9c4fca](https://linux-hardware.org/?probe=d5be9c4fca) | Jun 29, 2022 |
| Valve         | Jupiter                     | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| ASUSTek       | UX31E                       | [a346ece8f5](https://linux-hardware.org/?probe=a346ece8f5) | Jun 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| Dell          | Precision 5550              | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| Dell          | Precision 5550              | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [6ed235813a](https://linux-hardware.org/?probe=6ed235813a) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [af51b1d9da](https://linux-hardware.org/?probe=af51b1d9da) | Jun 19, 2022 |
| Dell          | Latitude E5470              | [e18ba2b5d7](https://linux-hardware.org/?probe=e18ba2b5d7) | Jun 18, 2022 |
| HP            | Compaq nc6120 (PN936AV)     | [c1ecdd7b5a](https://linux-hardware.org/?probe=c1ecdd7b5a) | Jun 17, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [4a8b021e76](https://linux-hardware.org/?probe=4a8b021e76) | Jun 11, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| Lenovo        | ThinkPad T460s 20FA003JM... | [417d162cab](https://linux-hardware.org/?probe=417d162cab) | Jun 09, 2022 |
| ASUSTek       | UX31E                       | [4abfa2a1d0](https://linux-hardware.org/?probe=4abfa2a1d0) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | [81335c6978](https://linux-hardware.org/?probe=81335c6978) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | [62d39f4677](https://linux-hardware.org/?probe=62d39f4677) | Jun 08, 2022 |
| ASUSTek       | K54LY                       | [39ad69783e](https://linux-hardware.org/?probe=39ad69783e) | Jun 08, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c6975f2914](https://linux-hardware.org/?probe=c6975f2914) | Jun 07, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [77b282aaaa](https://linux-hardware.org/?probe=77b282aaaa) | Jun 05, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [b320ea6050](https://linux-hardware.org/?probe=b320ea6050) | Jun 05, 2022 |
| MSI           | GP72 7QF                    | [ad0e85dbf9](https://linux-hardware.org/?probe=ad0e85dbf9) | Jun 05, 2022 |
| ASUSTek       | UX31E                       | [250825e17e](https://linux-hardware.org/?probe=250825e17e) | Jun 03, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [ac88b5f927](https://linux-hardware.org/?probe=ac88b5f927) | Jun 03, 2022 |
| HP            | ProBook 450 G7              | [010b492184](https://linux-hardware.org/?probe=010b492184) | May 31, 2022 |
| ASUSTek       | UX31E                       | [201add5732](https://linux-hardware.org/?probe=201add5732) | May 29, 2022 |
| HP            | Pavilion dv6                | [3623a980f8](https://linux-hardware.org/?probe=3623a980f8) | May 28, 2022 |
| HP            | EliteBook 8760w             | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| ASUSTek       | UX31E                       | [3905de150e](https://linux-hardware.org/?probe=3905de150e) | May 24, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [9f202f07cd](https://linux-hardware.org/?probe=9f202f07cd) | May 24, 2022 |
| Lenovo        | ThinkPad T420 42362L0       | [3aa17b879d](https://linux-hardware.org/?probe=3aa17b879d) | May 22, 2022 |
| Toshiba       | Satellite L10W-C            | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| ASUSTek       | UX31E                       | [12407852be](https://linux-hardware.org/?probe=12407852be) | May 21, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| Acer          | Swift SF314-52              | [4c199417ea](https://linux-hardware.org/?probe=4c199417ea) | May 19, 2022 |
| Acer          | Aspire 3100                 | [47e42883f4](https://linux-hardware.org/?probe=47e42883f4) | May 18, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| Acer          | Swift SF314-52              | [a532101bbf](https://linux-hardware.org/?probe=a532101bbf) | May 17, 2022 |
| HP            | ProBook 455 G7              | [95daa19596](https://linux-hardware.org/?probe=95daa19596) | May 17, 2022 |
| HP            | ProBook 455 G7              | [a96c7163a5](https://linux-hardware.org/?probe=a96c7163a5) | May 17, 2022 |
| Dell          | Vostro 5568                 | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| ASUSTek       | X101CH                      | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| ASUSTek       | X555LB                      | [2c2e8fcf67](https://linux-hardware.org/?probe=2c2e8fcf67) | May 15, 2022 |
| ASUSTek       | UX31E                       | [85613b8729](https://linux-hardware.org/?probe=85613b8729) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| ASUSTek       | UX31E                       | [b83f4f894e](https://linux-hardware.org/?probe=b83f4f894e) | May 13, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Chuwi         | MiniBook X                  | [541609a32e](https://linux-hardware.org/?probe=541609a32e) | May 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [52fa4973d5](https://linux-hardware.org/?probe=52fa4973d5) | May 10, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | [a70f694f0b](https://linux-hardware.org/?probe=a70f694f0b) | May 09, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [badd8c8562](https://linux-hardware.org/?probe=badd8c8562) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | [73714bdb43](https://linux-hardware.org/?probe=73714bdb43) | May 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [dcff76e99c](https://linux-hardware.org/?probe=dcff76e99c) | May 02, 2022 |
| ASUSTek       | UX31E                       | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Dell          | Latitude 3330               | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| ASUSTek       | UX31E                       | [8f165f54aa](https://linux-hardware.org/?probe=8f165f54aa) | Apr 29, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-45              | [aee7cca97f](https://linux-hardware.org/?probe=aee7cca97f) | Apr 28, 2022 |
| ASUSTek       | UX31E                       | [ef86b0396a](https://linux-hardware.org/?probe=ef86b0396a) | Apr 27, 2022 |
| Acer          | Aspire 5742G                | [313e7bcf23](https://linux-hardware.org/?probe=313e7bcf23) | Apr 27, 2022 |
| HP            | ZBook 17 G3                 | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Dell          | Latitude 7390 2-in-1        | [8391ca514e](https://linux-hardware.org/?probe=8391ca514e) | Apr 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| Lenovo        | ThinkPad E15 20RD001EMC     | [d98ca42427](https://linux-hardware.org/?probe=d98ca42427) | Apr 20, 2022 |
| Dell          | Latitude 5480               | [811930e65e](https://linux-hardware.org/?probe=811930e65e) | Apr 20, 2022 |
| Lenovo        | B50-80 80EW                 | [2d1471986b](https://linux-hardware.org/?probe=2d1471986b) | Apr 19, 2022 |
| Acer          | Aspire V3-112P              | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |
| ASUSTek       | UX31E                       | [fa535559e0](https://linux-hardware.org/?probe=fa535559e0) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [fccfb454e4](https://linux-hardware.org/?probe=fccfb454e4) | Apr 16, 2022 |
| Lenovo        | ThinkPad T400 6474AH2       | [f5e7108c33](https://linux-hardware.org/?probe=f5e7108c33) | Apr 15, 2022 |
| Lenovo        | E31-80 80MX                 | [ea96e85c49](https://linux-hardware.org/?probe=ea96e85c49) | Apr 14, 2022 |
| Lenovo        | B50-80 80EW                 | [d180d3831a](https://linux-hardware.org/?probe=d180d3831a) | Apr 10, 2022 |
| Acer          | TravelMate 4670             | [f5067e581b](https://linux-hardware.org/?probe=f5067e581b) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | [7f4e9c9158](https://linux-hardware.org/?probe=7f4e9c9158) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | [7249da837c](https://linux-hardware.org/?probe=7249da837c) | Apr 06, 2022 |
| Acer          | Extensa 5630                | [7ff131392d](https://linux-hardware.org/?probe=7ff131392d) | Apr 05, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [59eedbbc1b](https://linux-hardware.org/?probe=59eedbbc1b) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Dell          | XPS 15 9550                 | [487aa8af18](https://linux-hardware.org/?probe=487aa8af18) | Apr 03, 2022 |
| Acer          | Extensa 5630                | [4c6f7067bc](https://linux-hardware.org/?probe=4c6f7067bc) | Apr 02, 2022 |
| ASUSTek       | UX31E                       | [beb645df2c](https://linux-hardware.org/?probe=beb645df2c) | Apr 02, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [96e4eca691](https://linux-hardware.org/?probe=96e4eca691) | Apr 01, 2022 |
| ASUSTek       | UX31E                       | [54717b42d3](https://linux-hardware.org/?probe=54717b42d3) | Mar 31, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [e69dbda259](https://linux-hardware.org/?probe=e69dbda259) | Mar 31, 2022 |
| Acer          | Aspire E5-573G              | [39d3a3ac9d](https://linux-hardware.org/?probe=39d3a3ac9d) | Mar 30, 2022 |
| Acer          | Aspire P3-171               | [972861cbcc](https://linux-hardware.org/?probe=972861cbcc) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AWA07B0... | [4e67f54e53](https://linux-hardware.org/?probe=4e67f54e53) | Mar 29, 2022 |
| ASUSTek       | UX31E                       | [d83c6588f2](https://linux-hardware.org/?probe=d83c6588f2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [649bc1b13a](https://linux-hardware.org/?probe=649bc1b13a) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [d1638977bc](https://linux-hardware.org/?probe=d1638977bc) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | [67c079dd83](https://linux-hardware.org/?probe=67c079dd83) | Mar 28, 2022 |
| HP            | Compaq 615                  | [77439caf8f](https://linux-hardware.org/?probe=77439caf8f) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | [582d76d560](https://linux-hardware.org/?probe=582d76d560) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Acer          | Aspire 3000                 | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | [6df7f8330c](https://linux-hardware.org/?probe=6df7f8330c) | Mar 25, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [c6ed527183](https://linux-hardware.org/?probe=c6ed527183) | Mar 25, 2022 |
| Lenovo        | ThinkPad X61s 7667CB5       | [05a3f6eba9](https://linux-hardware.org/?probe=05a3f6eba9) | Mar 25, 2022 |
| ASUSTek       | UX31E                       | [ad8feeb6a4](https://linux-hardware.org/?probe=ad8feeb6a4) | Mar 24, 2022 |
| HP            | Compaq 615                  | [c61f5e75c7](https://linux-hardware.org/?probe=c61f5e75c7) | Mar 24, 2022 |
| Dell          | Latitude E6430s             | [8ac18b3ae9](https://linux-hardware.org/?probe=8ac18b3ae9) | Mar 24, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [26443633b7](https://linux-hardware.org/?probe=26443633b7) | Mar 23, 2022 |
| ASUSTek       | UX31E                       | [3f268da44f](https://linux-hardware.org/?probe=3f268da44f) | Mar 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [9fb46d3913](https://linux-hardware.org/?probe=9fb46d3913) | Mar 22, 2022 |
| HP            | ProBook 450 G6              | [e8072f850f](https://linux-hardware.org/?probe=e8072f850f) | Mar 22, 2022 |
| ASUSTek       | UX31E                       | [86242fab56](https://linux-hardware.org/?probe=86242fab56) | Mar 21, 2022 |
| Acer          | Aspire E5-521               | [ad4ffeb6d5](https://linux-hardware.org/?probe=ad4ffeb6d5) | Mar 20, 2022 |
| Acer          | Aspire E5-521               | [7f37d7148d](https://linux-hardware.org/?probe=7f37d7148d) | Mar 20, 2022 |
| HP            | Pavilion Notebook 15-dp0... | [4824a016cc](https://linux-hardware.org/?probe=4824a016cc) | Mar 18, 2022 |
| HP            | Pavilion Notebook 15-dp0... | [847871aa63](https://linux-hardware.org/?probe=847871aa63) | Mar 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [12249482c6](https://linux-hardware.org/?probe=12249482c6) | Mar 17, 2022 |
| Dell          | Latitude E4200              | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| ASUSTek       | X550VXK                     | [9d51869d37](https://linux-hardware.org/?probe=9d51869d37) | Mar 15, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [d627d6a6a0](https://linux-hardware.org/?probe=d627d6a6a0) | Mar 14, 2022 |
| ASUSTek       | UX31E                       | [620772c443](https://linux-hardware.org/?probe=620772c443) | Mar 11, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| Acer          | Aspire 3100                 | [0429db8c01](https://linux-hardware.org/?probe=0429db8c01) | Mar 11, 2022 |
| HP            | Laptop 15-db0xxx            | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Toshiba       | Satellite L750D             | [84ccdf8375](https://linux-hardware.org/?probe=84ccdf8375) | Mar 10, 2022 |
| ASUSTek       | UX31E                       | [62f3b41d12](https://linux-hardware.org/?probe=62f3b41d12) | Mar 09, 2022 |
| Acer          | TP-SW5-012-16UW             | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| Toshiba       | Satellite L750D             | [71d5919c2d](https://linux-hardware.org/?probe=71d5919c2d) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | [889c1ad7d2](https://linux-hardware.org/?probe=889c1ad7d2) | Mar 07, 2022 |
| Acer          | Aspire 5349                 | [cd3380a8b4](https://linux-hardware.org/?probe=cd3380a8b4) | Mar 07, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [3667f5b9e9](https://linux-hardware.org/?probe=3667f5b9e9) | Mar 07, 2022 |
| Acer          | Extensa 5620                | [3104016080](https://linux-hardware.org/?probe=3104016080) | Mar 06, 2022 |
| ASUSTek       | UX31E                       | [885cc74a20](https://linux-hardware.org/?probe=885cc74a20) | Mar 05, 2022 |
| HP            | ProBook 455 G7              | [311c6da8e0](https://linux-hardware.org/?probe=311c6da8e0) | Mar 05, 2022 |
| Dell          | Latitude E5470              | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [3333e54277](https://linux-hardware.org/?probe=3333e54277) | Mar 04, 2022 |
| Dell          | Latitude 7520               | [023fba74f0](https://linux-hardware.org/?probe=023fba74f0) | Mar 04, 2022 |
| ASUSTek       | UX31E                       | [c4106a59b1](https://linux-hardware.org/?probe=c4106a59b1) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [6d96f7e645](https://linux-hardware.org/?probe=6d96f7e645) | Mar 02, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [66cdff8786](https://linux-hardware.org/?probe=66cdff8786) | Mar 02, 2022 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [21b4f724b8](https://linux-hardware.org/?probe=21b4f724b8) | Mar 02, 2022 |
| Dell          | Latitude 7520               | [d31adbbcad](https://linux-hardware.org/?probe=d31adbbcad) | Mar 02, 2022 |
| ASUSTek       | UX31E                       | [36ea5044b6](https://linux-hardware.org/?probe=36ea5044b6) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [cab4f22396](https://linux-hardware.org/?probe=cab4f22396) | Feb 28, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [55773feeee](https://linux-hardware.org/?probe=55773feeee) | Feb 27, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [9ffeec636e](https://linux-hardware.org/?probe=9ffeec636e) | Feb 26, 2022 |
| ASUSTek       | UX31E                       | [477b323b68](https://linux-hardware.org/?probe=477b323b68) | Feb 25, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [4cb3686ee5](https://linux-hardware.org/?probe=4cb3686ee5) | Feb 24, 2022 |
| ASUSTek       | UX31E                       | [a6dae44349](https://linux-hardware.org/?probe=a6dae44349) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [245600d3fd](https://linux-hardware.org/?probe=245600d3fd) | Feb 23, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [bedd29ee73](https://linux-hardware.org/?probe=bedd29ee73) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56496468de](https://linux-hardware.org/?probe=56496468de) | Feb 21, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [6cb1c24dd7](https://linux-hardware.org/?probe=6cb1c24dd7) | Feb 20, 2022 |
| ASUSTek       | X75A1                       | [232712babb](https://linux-hardware.org/?probe=232712babb) | Feb 19, 2022 |
| ASUSTek       | UX31E                       | [5651fbf2c8](https://linux-hardware.org/?probe=5651fbf2c8) | Feb 18, 2022 |
| Google        | Chell                       | [46b95ce3a4](https://linux-hardware.org/?probe=46b95ce3a4) | Feb 17, 2022 |
| Acer          | Aspire E5-573G              | [e162c17653](https://linux-hardware.org/?probe=e162c17653) | Feb 17, 2022 |
| Lenovo        | IdeaPad Z580                | [26e55e169b](https://linux-hardware.org/?probe=26e55e169b) | Feb 16, 2022 |
| Gigabyte      | GB-BSi7A-6500               | [9cfc09f66c](https://linux-hardware.org/?probe=9cfc09f66c) | Feb 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5JW0... | [df9633e08e](https://linux-hardware.org/?probe=df9633e08e) | Feb 13, 2022 |
| ASUSTek       | UX31E                       | [7b2a1e633f](https://linux-hardware.org/?probe=7b2a1e633f) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | [b78e30f502](https://linux-hardware.org/?probe=b78e30f502) | Feb 11, 2022 |
| Dell          | Latitude 5480               | [eddd68780f](https://linux-hardware.org/?probe=eddd68780f) | Feb 09, 2022 |
| ASUSTek       | UX31E                       | [f70763fe0a](https://linux-hardware.org/?probe=f70763fe0a) | Feb 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [3fa68165ea](https://linux-hardware.org/?probe=3fa68165ea) | Feb 07, 2022 |
| ASUSTek       | UX31E                       | [4346690bc8](https://linux-hardware.org/?probe=4346690bc8) | Feb 06, 2022 |
| Acer          | Aspire SW3-016              | [6375ec93db](https://linux-hardware.org/?probe=6375ec93db) | Feb 05, 2022 |
| ASUSTek       | UX31E                       | [1eceff18e2](https://linux-hardware.org/?probe=1eceff18e2) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| Lenovo        | G710 20252                  | [ffc1b2ca5a](https://linux-hardware.org/?probe=ffc1b2ca5a) | Feb 04, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| Lenovo        | G50-70 20351                | [c31d2c4893](https://linux-hardware.org/?probe=c31d2c4893) | Feb 04, 2022 |
| ASUSTek       | F5RL                        | [09497d2017](https://linux-hardware.org/?probe=09497d2017) | Feb 02, 2022 |
| ASUSTek       | F5RL                        | [77baf7aac1](https://linux-hardware.org/?probe=77baf7aac1) | Feb 02, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | [449f0842a4](https://linux-hardware.org/?probe=449f0842a4) | Feb 01, 2022 |
| Lenovo        | ThinkPad W530 2441B88       | [9c15c47f51](https://linux-hardware.org/?probe=9c15c47f51) | Feb 01, 2022 |
| Dell          | Latitude 7490               | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cd876e95b9](https://linux-hardware.org/?probe=cd876e95b9) | Jan 29, 2022 |
| ASUSTek       | X556UQ                      | [b9589b97a3](https://linux-hardware.org/?probe=b9589b97a3) | Jan 28, 2022 |
| HP            | ProBook 445 G7              | [a386252eaa](https://linux-hardware.org/?probe=a386252eaa) | Jan 28, 2022 |
| Unknown       | Unknown                     | [a6e928b122](https://linux-hardware.org/?probe=a6e928b122) | Jan 28, 2022 |
| Dell          | XPS 15 9560                 | [ee50dc0bb1](https://linux-hardware.org/?probe=ee50dc0bb1) | Jan 27, 2022 |
| ASUSTek       | K50ID                       | [fed48cd01d](https://linux-hardware.org/?probe=fed48cd01d) | Jan 27, 2022 |
| ASUSTek       | UX31E                       | [d6d51a7ce7](https://linux-hardware.org/?probe=d6d51a7ce7) | Jan 26, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S7D300    | [3fcdce23b5](https://linux-hardware.org/?probe=3fcdce23b5) | Jan 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [ab4eb272cb](https://linux-hardware.org/?probe=ab4eb272cb) | Jan 24, 2022 |
| Acer          | NC-E1-572-54208G            | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| UMAX          | MediaBook 14                | [87cb50f680](https://linux-hardware.org/?probe=87cb50f680) | Jan 23, 2022 |
| ASUSTek       | UX31E                       | [c64e8bdde9](https://linux-hardware.org/?probe=c64e8bdde9) | Jan 22, 2022 |
| Lenovo        | ThinkPad X395 20NL000HMC    | [6c07e3f92a](https://linux-hardware.org/?probe=6c07e3f92a) | Jan 21, 2022 |
| ASUSTek       | UX31E                       | [08320d55cd](https://linux-hardware.org/?probe=08320d55cd) | Jan 21, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [e5d8911653](https://linux-hardware.org/?probe=e5d8911653) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | [3f0a902b2e](https://linux-hardware.org/?probe=3f0a902b2e) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | [0b31274785](https://linux-hardware.org/?probe=0b31274785) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c76a20872b](https://linux-hardware.org/?probe=c76a20872b) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [11d1f56125](https://linux-hardware.org/?probe=11d1f56125) | Jan 18, 2022 |
| Dell          | Latitude 5420               | [dd45d8465d](https://linux-hardware.org/?probe=dd45d8465d) | Jan 17, 2022 |
| HP            | EliteBook 840 G6            | [c6b20915de](https://linux-hardware.org/?probe=c6b20915de) | Jan 17, 2022 |
| Notebook      | NS50MU                      | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| ASUSTek       | UX31E                       | [77c7eedd86](https://linux-hardware.org/?probe=77c7eedd86) | Jan 15, 2022 |
| Toshiba       | Satellite C55-A-19N         | [b53c0c9b39](https://linux-hardware.org/?probe=b53c0c9b39) | Jan 14, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [ba41989095](https://linux-hardware.org/?probe=ba41989095) | Jan 14, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [9111c65725](https://linux-hardware.org/?probe=9111c65725) | Jan 12, 2022 |
| HP            | ZBook 17 G2                 | [232d1f1cb4](https://linux-hardware.org/?probe=232d1f1cb4) | Jan 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | [94d85b9f5b](https://linux-hardware.org/?probe=94d85b9f5b) | Jan 12, 2022 |
| Dell          | Inspiron 13 5310            | [f45f45197a](https://linux-hardware.org/?probe=f45f45197a) | Jan 11, 2022 |
| HP            | ProBook 6450b               | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Lenovo        | ThinkPad E590 20NB001WMC    | [f114fe6200](https://linux-hardware.org/?probe=f114fe6200) | Jan 08, 2022 |
| Toshiba       | Satellite C55-A-1NU         | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| HP            | EliteBook 8540p             | [20b9948e89](https://linux-hardware.org/?probe=20b9948e89) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [13c6bafd04](https://linux-hardware.org/?probe=13c6bafd04) | Jan 08, 2022 |
| ASUSTek       | UX31E                       | [b976b5921e](https://linux-hardware.org/?probe=b976b5921e) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e50bae67a6](https://linux-hardware.org/?probe=e50bae67a6) | Jan 08, 2022 |
| Lenovo        | Yoga 2 13 20344             | [581a4abb8e](https://linux-hardware.org/?probe=581a4abb8e) | Jan 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| HP            | ProBook 4510s               | [50904e6b69](https://linux-hardware.org/?probe=50904e6b69) | Jan 06, 2022 |
| HP            | ProBook 4510s               | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Precision M4500             | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| Dell          | Latitude 3470               | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d774f42123](https://linux-hardware.org/?probe=d774f42123) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| Dell          | Inspiron 5570               | [3e6d1befd6](https://linux-hardware.org/?probe=3e6d1befd6) | Jan 03, 2022 |
| Dell          | Latitude 7480               | [24244e5717](https://linux-hardware.org/?probe=24244e5717) | Jan 02, 2022 |
| Acer          | Swift SF114-34              | [94b665863b](https://linux-hardware.org/?probe=94b665863b) | Jan 02, 2022 |
| ASUSTek       | UX31E                       | [926c4f82d1](https://linux-hardware.org/?probe=926c4f82d1) | Jan 01, 2022 |
| HP            | EliteBook 820 G1            | [90deec9056](https://linux-hardware.org/?probe=90deec9056) | Dec 30, 2021 |
| Dell          | Inspiron 7559               | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| HP            | ProBook 4540s               | [20af449f2a](https://linux-hardware.org/?probe=20af449f2a) | Dec 29, 2021 |
| HP            | ProBook 4540s               | [99fb3303bb](https://linux-hardware.org/?probe=99fb3303bb) | Dec 29, 2021 |
| Acer          | Aspire ES1-571              | [ae601c56b8](https://linux-hardware.org/?probe=ae601c56b8) | Dec 28, 2021 |
| ASUSTek       | UX31E                       | [cd8cc790a0](https://linux-hardware.org/?probe=cd8cc790a0) | Dec 27, 2021 |
| HP            | Laptop 17-cp0xxx            | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| HUAWEI        | HVY-WXX9                    | [2c33c2931e](https://linux-hardware.org/?probe=2c33c2931e) | Dec 26, 2021 |
| Lenovo        | G710 20252                  | [961341534c](https://linux-hardware.org/?probe=961341534c) | Dec 26, 2021 |
| Acer          | Swift SF315-41              | [92f264978e](https://linux-hardware.org/?probe=92f264978e) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | [d94d38f29b](https://linux-hardware.org/?probe=d94d38f29b) | Dec 25, 2021 |
| ASUSTek       | X705NC                      | [c3cdc81bd8](https://linux-hardware.org/?probe=c3cdc81bd8) | Dec 25, 2021 |
| ASUSTek       | UX31E                       | [62488dea12](https://linux-hardware.org/?probe=62488dea12) | Dec 25, 2021 |
| Dell          | Latitude 5400               | [692bc521a6](https://linux-hardware.org/?probe=692bc521a6) | Dec 20, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| HP            | EliteBook 850 G6            | [0f1c42ef5d](https://linux-hardware.org/?probe=0f1c42ef5d) | Dec 18, 2021 |
| ASUSTek       | UX31E                       | [8c6db8aa19](https://linux-hardware.org/?probe=8c6db8aa19) | Dec 17, 2021 |
| Acer          | Aspire A515-56              | [a50b285530](https://linux-hardware.org/?probe=a50b285530) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440 20B7S1MW07    | [21baa9b1cc](https://linux-hardware.org/?probe=21baa9b1cc) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [a0ec890791](https://linux-hardware.org/?probe=a0ec890791) | Dec 15, 2021 |
| ASUSTek       | X751LN                      | [f7489ee0ae](https://linux-hardware.org/?probe=f7489ee0ae) | Dec 15, 2021 |
| ASUSTek       | UX31E                       | [f5d5138937](https://linux-hardware.org/?probe=f5d5138937) | Dec 13, 2021 |
| HP            | EliteBook 840 G6            | [a20ecb525c](https://linux-hardware.org/?probe=a20ecb525c) | Dec 13, 2021 |
| Acer          | Aspire E5-721               | [53ab8f6179](https://linux-hardware.org/?probe=53ab8f6179) | Dec 12, 2021 |
| HP            | Laptop 14-cf0xxx            | [2f4ec869f9](https://linux-hardware.org/?probe=2f4ec869f9) | Dec 12, 2021 |
| ASUSTek       | UX31E                       | [d48bfc96ce](https://linux-hardware.org/?probe=d48bfc96ce) | Dec 12, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Dell          | Latitude E4300              | [3dd32ae25d](https://linux-hardware.org/?probe=3dd32ae25d) | Dec 10, 2021 |
| Acer          | Extensa 5220                | [2572d3336d](https://linux-hardware.org/?probe=2572d3336d) | Dec 09, 2021 |
| Acer          | Extensa 5220                | [524256971b](https://linux-hardware.org/?probe=524256971b) | Dec 09, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [2694c27280](https://linux-hardware.org/?probe=2694c27280) | Dec 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| ASUSTek       | UX31E                       | [04c3a4b6c7](https://linux-hardware.org/?probe=04c3a4b6c7) | Dec 03, 2021 |
| Lenovo        | G770 20089                  | [6a4de555a2](https://linux-hardware.org/?probe=6a4de555a2) | Dec 03, 2021 |
| UMAX          | VisionBook N15G Plus        | [4b16e8ea9d](https://linux-hardware.org/?probe=4b16e8ea9d) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| Google        | Akemi                       | [0867d0658c](https://linux-hardware.org/?probe=0867d0658c) | Dec 01, 2021 |
| Google        | Akemi                       | [2344df2c6b](https://linux-hardware.org/?probe=2344df2c6b) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ae6614d6fb](https://linux-hardware.org/?probe=ae6614d6fb) | Nov 29, 2021 |
| ASUSTek       | UX31E                       | [0af8133ca3](https://linux-hardware.org/?probe=0af8133ca3) | Nov 29, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [9dd7b3ad9b](https://linux-hardware.org/?probe=9dd7b3ad9b) | Nov 29, 2021 |
| Acer          | P4LJ0                       | [0f57f6b606](https://linux-hardware.org/?probe=0f57f6b606) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [f047b9db0a](https://linux-hardware.org/?probe=f047b9db0a) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [d8d17c1820](https://linux-hardware.org/?probe=d8d17c1820) | Nov 27, 2021 |
| Lenovo        | G780                        | [ffeaa607f9](https://linux-hardware.org/?probe=ffeaa607f9) | Nov 27, 2021 |
| Lenovo        | G780                        | [26ea5410e6](https://linux-hardware.org/?probe=26ea5410e6) | Nov 27, 2021 |
| Fujitsu       | LIFEBOOK T901               | [d9b8b1c304](https://linux-hardware.org/?probe=d9b8b1c304) | Nov 27, 2021 |
| ASUSTek       | X751LN                      | [2c8e1bfecd](https://linux-hardware.org/?probe=2c8e1bfecd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| ASUSTek       | X751LN                      | [50d304e970](https://linux-hardware.org/?probe=50d304e970) | Nov 22, 2021 |
| Unknown       | Unknown                     | [81e2289408](https://linux-hardware.org/?probe=81e2289408) | Nov 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6b2b37cfc2](https://linux-hardware.org/?probe=6b2b37cfc2) | Nov 20, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [c174aa242d](https://linux-hardware.org/?probe=c174aa242d) | Nov 20, 2021 |
| HP            | OMEN by Laptop              | [0b8f3a5da9](https://linux-hardware.org/?probe=0b8f3a5da9) | Nov 19, 2021 |
| ASUSTek       | UX31E                       | [27fde62ce2](https://linux-hardware.org/?probe=27fde62ce2) | Nov 18, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [f3bf7b971f](https://linux-hardware.org/?probe=f3bf7b971f) | Nov 18, 2021 |
| HP            | ProBook 4510s               | [46c61312c4](https://linux-hardware.org/?probe=46c61312c4) | Nov 18, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [66fd774069](https://linux-hardware.org/?probe=66fd774069) | Nov 17, 2021 |
| HP            | ProBook 4510s               | [cf53b2e2db](https://linux-hardware.org/?probe=cf53b2e2db) | Nov 17, 2021 |
| Fujitsu       | LIFEBOOK E754               | [9569f15e49](https://linux-hardware.org/?probe=9569f15e49) | Nov 16, 2021 |
| Dell          | Latitude E6420              | [71905152a8](https://linux-hardware.org/?probe=71905152a8) | Nov 14, 2021 |
| HP            | ProBook 455 G6              | [2a37f0ed64](https://linux-hardware.org/?probe=2a37f0ed64) | Nov 14, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [bf655cd438](https://linux-hardware.org/?probe=bf655cd438) | Nov 13, 2021 |
| HUAWEI        | HN-WX9X                     | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [1fe63ecbee](https://linux-hardware.org/?probe=1fe63ecbee) | Nov 13, 2021 |
| HP            | ProBook 640 G1              | [72d5b9727b](https://linux-hardware.org/?probe=72d5b9727b) | Nov 12, 2021 |
| HP            | OMEN by Laptop              | [207d9a7985](https://linux-hardware.org/?probe=207d9a7985) | Nov 12, 2021 |
| HP            | Pavilion g6                 | [0332d112e9](https://linux-hardware.org/?probe=0332d112e9) | Nov 12, 2021 |
| HP            | ProBook 455 G6              | [6045aa2b3a](https://linux-hardware.org/?probe=6045aa2b3a) | Nov 12, 2021 |
| Dell          | Latitude E5440              | [310f365903](https://linux-hardware.org/?probe=310f365903) | Nov 10, 2021 |
| Timi          | A35                         | [f8818e4273](https://linux-hardware.org/?probe=f8818e4273) | Nov 10, 2021 |
| Lenovo        | ThinkPad Edge E431 62774... | [2af76d7459](https://linux-hardware.org/?probe=2af76d7459) | Nov 09, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | [a67ec35b48](https://linux-hardware.org/?probe=a67ec35b48) | Nov 08, 2021 |
| HP            | Pavilion dv6                | [12800ce664](https://linux-hardware.org/?probe=12800ce664) | Nov 06, 2021 |
| HP            | Pavilion dv6                | [9b00744856](https://linux-hardware.org/?probe=9b00744856) | Nov 06, 2021 |
| Dell          | XPS 15 9550                 | [1ae65e25ca](https://linux-hardware.org/?probe=1ae65e25ca) | Nov 06, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | [91c9beef79](https://linux-hardware.org/?probe=91c9beef79) | Nov 05, 2021 |
| Dell          | XPS 15 9550                 | [3cea241e9d](https://linux-hardware.org/?probe=3cea241e9d) | Nov 04, 2021 |
| ASUSTek       | X555BA                      | [99ef7179aa](https://linux-hardware.org/?probe=99ef7179aa) | Nov 04, 2021 |
| HP            | ProBook 650 G2              | [510bf1ba13](https://linux-hardware.org/?probe=510bf1ba13) | Nov 03, 2021 |
| HP            | OMEN by Laptop              | [d5eda0a4df](https://linux-hardware.org/?probe=d5eda0a4df) | Nov 01, 2021 |
| MSI           | GE76 Raider 11UG            | [cbbe604f22](https://linux-hardware.org/?probe=cbbe604f22) | Nov 01, 2021 |
| ASUSTek       | UX31E                       | [b089d44dc0](https://linux-hardware.org/?probe=b089d44dc0) | Nov 01, 2021 |
| Purism        | librem_15v4                 | [f3e5eba0c2](https://linux-hardware.org/?probe=f3e5eba0c2) | Oct 31, 2021 |
| Purism        | librem_15v4                 | [c74129a618](https://linux-hardware.org/?probe=c74129a618) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | [d55ac505b9](https://linux-hardware.org/?probe=d55ac505b9) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | [65a70acf15](https://linux-hardware.org/?probe=65a70acf15) | Oct 31, 2021 |
| ASUSTek       | F5RL                        | [7a2e7c66e9](https://linux-hardware.org/?probe=7a2e7c66e9) | Oct 31, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [3802a77d98](https://linux-hardware.org/?probe=3802a77d98) | Oct 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [eadbbabab0](https://linux-hardware.org/?probe=eadbbabab0) | Oct 29, 2021 |
| Dell          | Latitude E7240              | [18213a2e29](https://linux-hardware.org/?probe=18213a2e29) | Oct 28, 2021 |
| Lenovo        | ThinkPad E590 20NB0018MC    | [3678e02e46](https://linux-hardware.org/?probe=3678e02e46) | Oct 27, 2021 |
| Lenovo        | ThinkPad E590 20NB0018MC    | [5a44640ff8](https://linux-hardware.org/?probe=5a44640ff8) | Oct 27, 2021 |
| Lenovo        | B50-80 80EW                 | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Sony          | VPCZ13M9E                   | [2d1739dc58](https://linux-hardware.org/?probe=2d1739dc58) | Oct 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| ASUSTek       | UX31E                       | [62ce68edef](https://linux-hardware.org/?probe=62ce68edef) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Alienware     | 15                          | [5a84b0e8e8](https://linux-hardware.org/?probe=5a84b0e8e8) | Oct 25, 2021 |
| ASUSTek       | UX31E                       | [3783b25b2a](https://linux-hardware.org/?probe=3783b25b2a) | Oct 24, 2021 |
| Acer          | Aspire E5-721               | [0b2ec748f2](https://linux-hardware.org/?probe=0b2ec748f2) | Oct 23, 2021 |
| Acer          | Aspire E5-721               | [46ae1c3c30](https://linux-hardware.org/?probe=46ae1c3c30) | Oct 23, 2021 |
| Sony          | VPCZ13M9E                   | [d727cf6e00](https://linux-hardware.org/?probe=d727cf6e00) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Sony          | VPCZ13M9E                   | [6ccc652e28](https://linux-hardware.org/?probe=6ccc652e28) | Oct 22, 2021 |
| Alienware     | 15                          | [8c4eaaa333](https://linux-hardware.org/?probe=8c4eaaa333) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Dell          | Latitude 5400               | [8a880e6565](https://linux-hardware.org/?probe=8a880e6565) | Oct 19, 2021 |
| Dell          | Latitude 5400               | [0a94130eb2](https://linux-hardware.org/?probe=0a94130eb2) | Oct 19, 2021 |
| HP            | Laptop 15-bw0xx             | [f60949a3cc](https://linux-hardware.org/?probe=f60949a3cc) | Oct 18, 2021 |
| Sony          | VPCEB1E1E                   | [1473b3d2ca](https://linux-hardware.org/?probe=1473b3d2ca) | Oct 18, 2021 |
| Acer          | Aspire A515-51G             | [43bfef3bcd](https://linux-hardware.org/?probe=43bfef3bcd) | Oct 17, 2021 |
| Dell          | Latitude E5420              | [a1027f938f](https://linux-hardware.org/?probe=a1027f938f) | Oct 16, 2021 |
| Medion        | E7218                       | [cca261a107](https://linux-hardware.org/?probe=cca261a107) | Oct 16, 2021 |
| Dell          | XPS 13 9310                 | [f04cc5e7a8](https://linux-hardware.org/?probe=f04cc5e7a8) | Oct 15, 2021 |
| Dell          | XPS 13 9300                 | [22029905ac](https://linux-hardware.org/?probe=22029905ac) | Oct 15, 2021 |
| ASUSTek       | UX31E                       | [a20549b1ee](https://linux-hardware.org/?probe=a20549b1ee) | Oct 14, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fb676e6e3f](https://linux-hardware.org/?probe=fb676e6e3f) | Oct 14, 2021 |
| Dell          | XPS 15 9550                 | [2269836aab](https://linux-hardware.org/?probe=2269836aab) | Oct 13, 2021 |
| HP            | EliteBook 8570w             | [b703149715](https://linux-hardware.org/?probe=b703149715) | Oct 13, 2021 |
| ASUSTek       | UX31E                       | [33cb7873b3](https://linux-hardware.org/?probe=33cb7873b3) | Oct 11, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [fd09df16d9](https://linux-hardware.org/?probe=fd09df16d9) | Oct 10, 2021 |
| Lenovo        | ThinkPad T570 20H90000MC    | [51c709d90c](https://linux-hardware.org/?probe=51c709d90c) | Oct 09, 2021 |
| HP            | Compaq 6530b (GW688AV)      | [13444fc399](https://linux-hardware.org/?probe=13444fc399) | Oct 08, 2021 |
| ASUSTek       | E502SA                      | [7034e6708d](https://linux-hardware.org/?probe=7034e6708d) | Oct 07, 2021 |
| MSI           | GL63 8RD                    | [9f55f25caf](https://linux-hardware.org/?probe=9f55f25caf) | Oct 07, 2021 |
| ASUSTek       | UX31E                       | [3d656a59f6](https://linux-hardware.org/?probe=3d656a59f6) | Oct 06, 2021 |
| ASUSTek       | UX31E                       | [b24ee374eb](https://linux-hardware.org/?probe=b24ee374eb) | Oct 04, 2021 |
| HP            | ProBook 455 G1              | [43115b1585](https://linux-hardware.org/?probe=43115b1585) | Oct 04, 2021 |
| Acer          | Aspire A114-32              | [153c60004b](https://linux-hardware.org/?probe=153c60004b) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | [0c7f8d9bc1](https://linux-hardware.org/?probe=0c7f8d9bc1) | Oct 03, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [c3f376b088](https://linux-hardware.org/?probe=c3f376b088) | Oct 01, 2021 |
| ASUSTek       | UX31E                       | [634508203a](https://linux-hardware.org/?probe=634508203a) | Oct 01, 2021 |
| ASUSTek       | UX31E                       | [ae53a22db8](https://linux-hardware.org/?probe=ae53a22db8) | Sep 30, 2021 |
| ASUSTek       | E502SA                      | [7f17ddd3af](https://linux-hardware.org/?probe=7f17ddd3af) | Sep 30, 2021 |
| Acer          | Extensa 5235                | [aadc334520](https://linux-hardware.org/?probe=aadc334520) | Sep 29, 2021 |
| MSI           | GL72 6QD                    | [4a25280ba6](https://linux-hardware.org/?probe=4a25280ba6) | Sep 28, 2021 |
| ASUSTek       | UX31E                       | [1ce98669cc](https://linux-hardware.org/?probe=1ce98669cc) | Sep 27, 2021 |
| ASUSTek       | UX31E                       | [65594b31db](https://linux-hardware.org/?probe=65594b31db) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| ASUSTek       | UX31E                       | [61a05f66ef](https://linux-hardware.org/?probe=61a05f66ef) | Sep 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [534a4c683f](https://linux-hardware.org/?probe=534a4c683f) | Sep 24, 2021 |
| ASUSTek       | 1015BXO                     | [0f2bd07e92](https://linux-hardware.org/?probe=0f2bd07e92) | Sep 23, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [28cec81520](https://linux-hardware.org/?probe=28cec81520) | Sep 22, 2021 |
| Dell          | XPS 15 7590                 | [7e0c5640af](https://linux-hardware.org/?probe=7e0c5640af) | Sep 21, 2021 |
| HP            | 255 G4                      | [3385bd5e87](https://linux-hardware.org/?probe=3385bd5e87) | Sep 20, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [3c54753690](https://linux-hardware.org/?probe=3c54753690) | Sep 20, 2021 |
| ASUSTek       | UX31E                       | [02b242903b](https://linux-hardware.org/?probe=02b242903b) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| Toshiba       | Satellite C850-19P          | [be0e0fc39c](https://linux-hardware.org/?probe=be0e0fc39c) | Sep 19, 2021 |
| ASUSTek       | N73SV                       | [4dae78bc6e](https://linux-hardware.org/?probe=4dae78bc6e) | Sep 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [caa2e90160](https://linux-hardware.org/?probe=caa2e90160) | Sep 18, 2021 |
| Lenovo        | B50-80 80EW                 | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | [6d3c0cb595](https://linux-hardware.org/?probe=6d3c0cb595) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | [4771fb2aab](https://linux-hardware.org/?probe=4771fb2aab) | Sep 17, 2021 |
| Lenovo        | B51-80 80LM                 | [320ab41cbb](https://linux-hardware.org/?probe=320ab41cbb) | Sep 17, 2021 |
| ASUSTek       | UX31E                       | [6c54ed5e3e](https://linux-hardware.org/?probe=6c54ed5e3e) | Sep 16, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [10c9991f0b](https://linux-hardware.org/?probe=10c9991f0b) | Sep 16, 2021 |
| ASUSTek       | UX31E                       | [aa60d02a7b](https://linux-hardware.org/?probe=aa60d02a7b) | Sep 15, 2021 |
| Dell          | Vostro 14 5410              | [8bd0f5b675](https://linux-hardware.org/?probe=8bd0f5b675) | Sep 15, 2021 |
| Dell          | Vostro 14 5410              | [e044b5770b](https://linux-hardware.org/?probe=e044b5770b) | Sep 15, 2021 |
| HP            | ProBook 455 G6              | [8c5aa4304c](https://linux-hardware.org/?probe=8c5aa4304c) | Sep 14, 2021 |
| HP            | ProBook 455 G6              | [49a26a21af](https://linux-hardware.org/?probe=49a26a21af) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b1c5ad62b3](https://linux-hardware.org/?probe=b1c5ad62b3) | Sep 13, 2021 |
| ASUSTek       | UX31E                       | [e1b27b035e](https://linux-hardware.org/?probe=e1b27b035e) | Sep 13, 2021 |
| Dell          | Latitude 5400               | [1fed0bdd29](https://linux-hardware.org/?probe=1fed0bdd29) | Sep 13, 2021 |
| ASUSTek       | UX303LA                     | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| Dell          | XPS 15 9550                 | [5ef10e99fc](https://linux-hardware.org/?probe=5ef10e99fc) | Sep 11, 2021 |
| Unknown       | Unknown                     | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| ASUSTek       | UX31E                       | [d137a3a584](https://linux-hardware.org/?probe=d137a3a584) | Sep 09, 2021 |
| ASUSTek       | UX31E                       | [4b97784aeb](https://linux-hardware.org/?probe=4b97784aeb) | Sep 08, 2021 |
| Dell          | Latitude 5511               | [75e4394ca1](https://linux-hardware.org/?probe=75e4394ca1) | Sep 07, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [7d28c4a737](https://linux-hardware.org/?probe=7d28c4a737) | Sep 07, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [c33f77f320](https://linux-hardware.org/?probe=c33f77f320) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| ASUSTek       | UX31E                       | [e0160c202c](https://linux-hardware.org/?probe=e0160c202c) | Sep 06, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [96642dc49d](https://linux-hardware.org/?probe=96642dc49d) | Sep 02, 2021 |
| HP            | Pavilion g6                 | [7f23204904](https://linux-hardware.org/?probe=7f23204904) | Sep 02, 2021 |
| ASUSTek       | UX31E                       | [36e2960d9e](https://linux-hardware.org/?probe=36e2960d9e) | Sep 01, 2021 |
| MSI           | GP72MVR 7RFX                | [8bf96cd534](https://linux-hardware.org/?probe=8bf96cd534) | Sep 01, 2021 |
| ASUSTek       | UX31E                       | [f8455be078](https://linux-hardware.org/?probe=f8455be078) | Aug 31, 2021 |
| ASUSTek       | UX31E                       | [715882de9a](https://linux-hardware.org/?probe=715882de9a) | Aug 30, 2021 |
| Dell          | Inspiron 14 5410            | [9ac57ec075](https://linux-hardware.org/?probe=9ac57ec075) | Aug 29, 2021 |
| Dell          | Inspiron 5570               | [47c81ea7a3](https://linux-hardware.org/?probe=47c81ea7a3) | Aug 28, 2021 |
| HP            | ProBook 450 G2              | [8228226f9b](https://linux-hardware.org/?probe=8228226f9b) | Aug 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| ASUSTek       | UX31E                       | [a626915a9b](https://linux-hardware.org/?probe=a626915a9b) | Aug 27, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [b3185cd80d](https://linux-hardware.org/?probe=b3185cd80d) | Aug 26, 2021 |
| ASUSTek       | UX31E                       | [48a1496d43](https://linux-hardware.org/?probe=48a1496d43) | Aug 26, 2021 |
| HP            | Pavilion dv7                | [89e7202467](https://linux-hardware.org/?probe=89e7202467) | Aug 25, 2021 |
| HP            | ProBook 455 G7              | [56da4a55e4](https://linux-hardware.org/?probe=56da4a55e4) | Aug 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [42c87d7154](https://linux-hardware.org/?probe=42c87d7154) | Aug 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b773fc8716](https://linux-hardware.org/?probe=b773fc8716) | Aug 23, 2021 |
| HP            | 250 G6 Notebook PC          | [d0d5aa4d58](https://linux-hardware.org/?probe=d0d5aa4d58) | Aug 23, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7e6371d41f](https://linux-hardware.org/?probe=7e6371d41f) | Aug 22, 2021 |
| ASUSTek       | UX31E                       | [f11d89cc89](https://linux-hardware.org/?probe=f11d89cc89) | Aug 21, 2021 |
| ASUSTek       | UX31E                       | [36beb5b173](https://linux-hardware.org/?probe=36beb5b173) | Aug 19, 2021 |
| Dell          | Latitude 7320               | [33536a85d3](https://linux-hardware.org/?probe=33536a85d3) | Aug 19, 2021 |
| ASUSTek       | X556UQK                     | [7306b98101](https://linux-hardware.org/?probe=7306b98101) | Aug 18, 2021 |
| ASUSTek       | UX31E                       | [0816a877bd](https://linux-hardware.org/?probe=0816a877bd) | Aug 18, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [4f0fc1bae7](https://linux-hardware.org/?probe=4f0fc1bae7) | Aug 18, 2021 |
| ASUSTek       | UX31E                       | [7b007be9fd](https://linux-hardware.org/?probe=7b007be9fd) | Aug 16, 2021 |
| ASUSTek       | UX31E                       | [f9243be85f](https://linux-hardware.org/?probe=f9243be85f) | Aug 16, 2021 |
| Acer          | Extensa 5630                | [29a71214dd](https://linux-hardware.org/?probe=29a71214dd) | Aug 15, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [465b8fec82](https://linux-hardware.org/?probe=465b8fec82) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| ASUSTek       | UX31E                       | [80cfc9b687](https://linux-hardware.org/?probe=80cfc9b687) | Aug 12, 2021 |
| Acer          | Extensa 5630                | [43a2f7646a](https://linux-hardware.org/?probe=43a2f7646a) | Aug 12, 2021 |
| Dell          | XPS 15 7590                 | [185cff6125](https://linux-hardware.org/?probe=185cff6125) | Aug 12, 2021 |
| ASUSTek       | X553SA                      | [58875de3c3](https://linux-hardware.org/?probe=58875de3c3) | Aug 12, 2021 |
| ASUSTek       | UX31E                       | [4651e027d9](https://linux-hardware.org/?probe=4651e027d9) | Aug 11, 2021 |
| Dell          | Latitude 5400               | [4f804f2046](https://linux-hardware.org/?probe=4f804f2046) | Aug 11, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek       | UX31E                       | [28897c5b5f](https://linux-hardware.org/?probe=28897c5b5f) | Aug 09, 2021 |
| HP            | Pavilion g6                 | [a52650a605](https://linux-hardware.org/?probe=a52650a605) | Aug 09, 2021 |
| Dell          | XPS 15 9550                 | [17e8358196](https://linux-hardware.org/?probe=17e8358196) | Aug 08, 2021 |
| ASUSTek       | UX31E                       | [5c64722433](https://linux-hardware.org/?probe=5c64722433) | Aug 07, 2021 |
| ASUSTek       | UX31E                       | [88c691e7f1](https://linux-hardware.org/?probe=88c691e7f1) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| Dell          | Latitude 7490               | [32c82c54b5](https://linux-hardware.org/?probe=32c82c54b5) | Aug 06, 2021 |
| HP            | Pavilion dv6500             | [983611f01f](https://linux-hardware.org/?probe=983611f01f) | Aug 05, 2021 |
| HP            | Pavilion dv6500             | [5e399cedc5](https://linux-hardware.org/?probe=5e399cedc5) | Aug 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [30131c51fb](https://linux-hardware.org/?probe=30131c51fb) | Aug 05, 2021 |
| ASUSTek       | UX31E                       | [1e458b84be](https://linux-hardware.org/?probe=1e458b84be) | Aug 04, 2021 |
| ASUSTek       | UX31E                       | [8951f246ed](https://linux-hardware.org/?probe=8951f246ed) | Aug 04, 2021 |
| ASUSTek       | G55VW                       | [9e7dc8e8cf](https://linux-hardware.org/?probe=9e7dc8e8cf) | Aug 03, 2021 |
| Acer          | Swift SF514-54GT            | [bbe1d82ec7](https://linux-hardware.org/?probe=bbe1d82ec7) | Aug 02, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e9fd822a6](https://linux-hardware.org/?probe=0e9fd822a6) | Jul 29, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [1d638fd7ae](https://linux-hardware.org/?probe=1d638fd7ae) | Jul 29, 2021 |
| ASUSTek       | UX31E                       | [44b0620279](https://linux-hardware.org/?probe=44b0620279) | Jul 29, 2021 |
| HP            | ZBook 15 G6                 | [617fd327a3](https://linux-hardware.org/?probe=617fd327a3) | Jul 28, 2021 |
| HP            | Laptop 15-da2xxx            | [b90f06f2eb](https://linux-hardware.org/?probe=b90f06f2eb) | Jul 28, 2021 |
| ASUSTek       | X556UQ                      | [9dee8d2c07](https://linux-hardware.org/?probe=9dee8d2c07) | Jul 27, 2021 |
| ASUSTek       | X556UQ                      | [88b38f3c6b](https://linux-hardware.org/?probe=88b38f3c6b) | Jul 26, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| ASUSTek       | F5RL                        | [1ac5feaf25](https://linux-hardware.org/?probe=1ac5feaf25) | Jul 26, 2021 |
| ASUSTek       | F5RL                        | [3ca5d000c3](https://linux-hardware.org/?probe=3ca5d000c3) | Jul 26, 2021 |
| Dell          | Latitude E5520              | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| Lenovo        | ThinkPad X220 429137G       | [ab41516068](https://linux-hardware.org/?probe=ab41516068) | Jul 25, 2021 |
| Acer          | Aspire V3-111P              | [e3aca6b408](https://linux-hardware.org/?probe=e3aca6b408) | Jul 24, 2021 |
| Acer          | Swift SF514-55GT            | [bb95e7c75b](https://linux-hardware.org/?probe=bb95e7c75b) | Jul 24, 2021 |
| Lenovo        | ThinkPad E495 20NE000BMC    | [487f5a67bf](https://linux-hardware.org/?probe=487f5a67bf) | Jul 24, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [72cbbe92a0](https://linux-hardware.org/?probe=72cbbe92a0) | Jul 22, 2021 |
| HP            | EliteBook 850 G6            | [d0a8afe992](https://linux-hardware.org/?probe=d0a8afe992) | Jul 20, 2021 |
| Sony          | VPCEB1E1E                   | [b57d8d169b](https://linux-hardware.org/?probe=b57d8d169b) | Jul 20, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [db3e0c8073](https://linux-hardware.org/?probe=db3e0c8073) | Jul 17, 2021 |
| Dell          | XPS 15 9550                 | [594fbbbb38](https://linux-hardware.org/?probe=594fbbbb38) | Jul 17, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [4b6bb5e980](https://linux-hardware.org/?probe=4b6bb5e980) | Jul 16, 2021 |
| Dell          | Vostro 5515                 | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [d67f028892](https://linux-hardware.org/?probe=d67f028892) | Jul 15, 2021 |
| Toshiba       | Satellite L850              | [1697c7eaf6](https://linux-hardware.org/?probe=1697c7eaf6) | Jul 15, 2021 |
| Lenovo        | 0769BLG                     | [2d8e74d05c](https://linux-hardware.org/?probe=2d8e74d05c) | Jul 15, 2021 |
| Lenovo        | ThinkPad W540 20BHS2LM02    | [6d00312e5e](https://linux-hardware.org/?probe=6d00312e5e) | Jul 12, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [96f87991b2](https://linux-hardware.org/?probe=96f87991b2) | Jul 12, 2021 |
| HP            | Compaq 6730b (GB988EA)      | [ca4426ce30](https://linux-hardware.org/?probe=ca4426ce30) | Jul 11, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [eb84cf8198](https://linux-hardware.org/?probe=eb84cf8198) | Jul 10, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| HP            | EliteBook 840 G3            | [950a407dff](https://linux-hardware.org/?probe=950a407dff) | Jul 08, 2021 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | [048e092d2f](https://linux-hardware.org/?probe=048e092d2f) | Jul 08, 2021 |
| Apple         | MacBookAir7,2               | [a88a1df2f5](https://linux-hardware.org/?probe=a88a1df2f5) | Jul 07, 2021 |
| Apple         | MacBookAir7,2               | [77f6869d84](https://linux-hardware.org/?probe=77f6869d84) | Jul 07, 2021 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [dcad6f0184](https://linux-hardware.org/?probe=dcad6f0184) | Jul 06, 2021 |
| Packard Be... | EasyNote LS11HR             | [09dbdc286a](https://linux-hardware.org/?probe=09dbdc286a) | Jul 05, 2021 |
| HP            | Pavilion dv7                | [43afdddf0e](https://linux-hardware.org/?probe=43afdddf0e) | Jul 04, 2021 |
| HP            | EliteBook 850 G6            | [27b614c70e](https://linux-hardware.org/?probe=27b614c70e) | Jul 04, 2021 |
| HP            | ProBook 4720s               | [2112bd8af0](https://linux-hardware.org/?probe=2112bd8af0) | Jul 03, 2021 |
| HP            | ProBook 4720s               | [f6be4a39bb](https://linux-hardware.org/?probe=f6be4a39bb) | Jul 03, 2021 |
| Dell          | Latitude E6400              | [18d5b00f71](https://linux-hardware.org/?probe=18d5b00f71) | Jul 03, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [6e5f031c7a](https://linux-hardware.org/?probe=6e5f031c7a) | Jul 03, 2021 |
| HP            | Pavilion x2 Detachable P... | [d917cdea53](https://linux-hardware.org/?probe=d917cdea53) | Jul 02, 2021 |
| Dell          | Latitude E6430              | [43100da49e](https://linux-hardware.org/?probe=43100da49e) | Jul 02, 2021 |
| Dell          | Inspiron 1750               | [2ff81df67a](https://linux-hardware.org/?probe=2ff81df67a) | Jul 02, 2021 |
| Acer          | E1-510                      | [74ed9018a7](https://linux-hardware.org/?probe=74ed9018a7) | Jul 02, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [c19ad895a0](https://linux-hardware.org/?probe=c19ad895a0) | Jul 02, 2021 |
| Acer          | E1-510                      | [1f5fc816d2](https://linux-hardware.org/?probe=1f5fc816d2) | Jul 02, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [0260c559c1](https://linux-hardware.org/?probe=0260c559c1) | Jul 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | [ee813e9b02](https://linux-hardware.org/?probe=ee813e9b02) | Jul 02, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [d26e9b673d](https://linux-hardware.org/?probe=d26e9b673d) | Jul 01, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [858ab16aee](https://linux-hardware.org/?probe=858ab16aee) | Jun 29, 2021 |
| Unknown       | Unknown                     | [4d4040c7bd](https://linux-hardware.org/?probe=4d4040c7bd) | Jun 27, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [e1fe98a9de](https://linux-hardware.org/?probe=e1fe98a9de) | Jun 23, 2021 |
| Lenovo        | V330-15IKB 81AX             | [e6e76d81ec](https://linux-hardware.org/?probe=e6e76d81ec) | Jun 19, 2021 |
| Acer          | Nitro AN515-54              | [cf48431ab4](https://linux-hardware.org/?probe=cf48431ab4) | Jun 18, 2021 |
| Acer          | Nitro AN515-54              | [0db05d1420](https://linux-hardware.org/?probe=0db05d1420) | Jun 18, 2021 |
| Dell          | XPS 15 9550                 | [8c980bf3ca](https://linux-hardware.org/?probe=8c980bf3ca) | Jun 17, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [4134764afd](https://linux-hardware.org/?probe=4134764afd) | Jun 09, 2021 |
| Dell          | XPS 15 7590                 | [03514539b0](https://linux-hardware.org/?probe=03514539b0) | Jun 09, 2021 |
| HP            | Pavilion dv5                | [a3ec72db59](https://linux-hardware.org/?probe=a3ec72db59) | Jun 08, 2021 |
| Dell          | Latitude E5510              | [648d4a58e1](https://linux-hardware.org/?probe=648d4a58e1) | Jun 06, 2021 |
| ASUSTek       | X55U                        | [4a44c680de](https://linux-hardware.org/?probe=4a44c680de) | Jun 05, 2021 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [da76c3ea04](https://linux-hardware.org/?probe=da76c3ea04) | Jun 05, 2021 |
| HP            | Pavilion g6                 | [ca0eb881c4](https://linux-hardware.org/?probe=ca0eb881c4) | Jun 04, 2021 |
| HP            | Pavilion g6                 | [1bbb6d6e34](https://linux-hardware.org/?probe=1bbb6d6e34) | Jun 03, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [e50e7e65b4](https://linux-hardware.org/?probe=e50e7e65b4) | May 28, 2021 |
| Insyde        | Braswell                    | [cedca78b3a](https://linux-hardware.org/?probe=cedca78b3a) | May 28, 2021 |
| HP            | ProBook 455 G7              | [fc1870a101](https://linux-hardware.org/?probe=fc1870a101) | May 28, 2021 |
| HP            | ProBook 455 G7              | [75f763a124](https://linux-hardware.org/?probe=75f763a124) | May 28, 2021 |
| HP            | Pavilion dv7                | [91d0ba53c9](https://linux-hardware.org/?probe=91d0ba53c9) | May 28, 2021 |
| ASUSTek       | K53SV                       | [a8fd68fccc](https://linux-hardware.org/?probe=a8fd68fccc) | May 26, 2021 |
| Dell          | G5 5587                     | [65c1600593](https://linux-hardware.org/?probe=65c1600593) | May 24, 2021 |
| Dell          | Latitude 7420               | [38380cec21](https://linux-hardware.org/?probe=38380cec21) | May 22, 2021 |
| Dell          | Latitude 5511               | [6fdc31e1e9](https://linux-hardware.org/?probe=6fdc31e1e9) | May 21, 2021 |
| MSI           | GE72 7RE                    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| Lenovo        | V130-15IKB 81HN             | [3630dfb215](https://linux-hardware.org/?probe=3630dfb215) | May 17, 2021 |
| HP            | ProBook 450 G7              | [cbde33b709](https://linux-hardware.org/?probe=cbde33b709) | May 16, 2021 |
| HP            | ProBook 4520s (WT121EA)     | [af5a9f1662](https://linux-hardware.org/?probe=af5a9f1662) | May 15, 2021 |
| HP            | ProBook 455 G7              | [faeed14705](https://linux-hardware.org/?probe=faeed14705) | May 15, 2021 |
| HP            | ProBook 455 G7              | [5a9153e5cc](https://linux-hardware.org/?probe=5a9153e5cc) | May 14, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [33069aaebb](https://linux-hardware.org/?probe=33069aaebb) | May 12, 2021 |
| Unknown       | Unknown                     | [a54c655ae8](https://linux-hardware.org/?probe=a54c655ae8) | May 12, 2021 |
| Unknown       | Unknown                     | [e6eed05cc3](https://linux-hardware.org/?probe=e6eed05cc3) | May 12, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [ec0cb83241](https://linux-hardware.org/?probe=ec0cb83241) | May 10, 2021 |
| Acer          | Aspire VN7-591G             | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |
| Acer          | Aspire 5740                 | [ed5c778d4f](https://linux-hardware.org/?probe=ed5c778d4f) | May 09, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [75431661e3](https://linux-hardware.org/?probe=75431661e3) | May 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ffaf24e2ab](https://linux-hardware.org/?probe=ffaf24e2ab) | May 06, 2021 |
| ASUSTek       | T100TA                      | [61c9e8ca48](https://linux-hardware.org/?probe=61c9e8ca48) | May 05, 2021 |
| Lenovo        | B70-80 80MR                 | [17bea3da43](https://linux-hardware.org/?probe=17bea3da43) | May 04, 2021 |
| ASUSTek       | UX31E                       | [4acf6ce595](https://linux-hardware.org/?probe=4acf6ce595) | May 04, 2021 |
| ASUSTek       | X540SA                      | [0f79fb429b](https://linux-hardware.org/?probe=0f79fb429b) | May 02, 2021 |
| Dell          | Vostro 3350                 | [9f2372a38c](https://linux-hardware.org/?probe=9f2372a38c) | May 02, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1707ff6faf](https://linux-hardware.org/?probe=1707ff6faf) | May 02, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [36cd5135b6](https://linux-hardware.org/?probe=36cd5135b6) | May 02, 2021 |
| Sony          | VGN-FW31J                   | [87da15d562](https://linux-hardware.org/?probe=87da15d562) | May 01, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [184bedf2fd](https://linux-hardware.org/?probe=184bedf2fd) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [a6afe0cc34](https://linux-hardware.org/?probe=a6afe0cc34) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [0790e842a9](https://linux-hardware.org/?probe=0790e842a9) | May 01, 2021 |
| Dell          | Latitude 5401               | [cd8363b187](https://linux-hardware.org/?probe=cd8363b187) | Apr 27, 2021 |
| Lenovo        | ThinkPad T430 23501F9       | [d855b9bf0f](https://linux-hardware.org/?probe=d855b9bf0f) | Apr 26, 2021 |
| HP            | EliteBook 840 G5            | [266fb405d7](https://linux-hardware.org/?probe=266fb405d7) | Apr 26, 2021 |
| Acer          | TravelMate 6460             | [287952fb68](https://linux-hardware.org/?probe=287952fb68) | Apr 24, 2021 |
| Lenovo        | ThinkPad R500 2714AAG       | [0f62cca304](https://linux-hardware.org/?probe=0f62cca304) | Apr 20, 2021 |
| ASUSTek       | F5SL                        | [e1a84e3bdf](https://linux-hardware.org/?probe=e1a84e3bdf) | Apr 17, 2021 |
| HP            | ProBook 450 G7              | [45189929cc](https://linux-hardware.org/?probe=45189929cc) | Apr 17, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [4cc6403330](https://linux-hardware.org/?probe=4cc6403330) | Apr 15, 2021 |
| ASUSTek       | N73JQ                       | [29398a5494](https://linux-hardware.org/?probe=29398a5494) | Apr 15, 2021 |
| Dell          | XPS 13 9360                 | [4b5e9623a8](https://linux-hardware.org/?probe=4b5e9623a8) | Apr 13, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [538618720c](https://linux-hardware.org/?probe=538618720c) | Apr 11, 2021 |
| HP            | ProBook 4530s               | [6b62bad9ad](https://linux-hardware.org/?probe=6b62bad9ad) | Apr 11, 2021 |
| HP            | Notebook                    | [b50b4aa14f](https://linux-hardware.org/?probe=b50b4aa14f) | Apr 11, 2021 |
| HP            | EliteBook 850 G5            | [8351e652e0](https://linux-hardware.org/?probe=8351e652e0) | Apr 11, 2021 |
| ASUSTek       | UX31E                       | [22901fcbc7](https://linux-hardware.org/?probe=22901fcbc7) | Apr 11, 2021 |
| HP            | EliteBook 850 G5            | [71a5cf1e09](https://linux-hardware.org/?probe=71a5cf1e09) | Apr 11, 2021 |
| Fujitsu       | LIFEBOOK E5510              | [034e192416](https://linux-hardware.org/?probe=034e192416) | Apr 11, 2021 |
| Dell          | Inspiron 3501               | [cc2dcd8258](https://linux-hardware.org/?probe=cc2dcd8258) | Apr 10, 2021 |
| Sony          | VPCEB1E1E                   | [d73e70bc03](https://linux-hardware.org/?probe=d73e70bc03) | Apr 10, 2021 |
| Toshiba       | Unknown                     | [0c98d143f2](https://linux-hardware.org/?probe=0c98d143f2) | Apr 09, 2021 |
| Dell          | Inspiron 5593               | [f41c784317](https://linux-hardware.org/?probe=f41c784317) | Apr 09, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | [4e38c1e886](https://linux-hardware.org/?probe=4e38c1e886) | Apr 09, 2021 |
| Lenovo        | Yoga 300-11IBY 80M0         | [a1481ccf2a](https://linux-hardware.org/?probe=a1481ccf2a) | Apr 07, 2021 |
| Dell          | Inspiron 7348               | [bd1d84d6e7](https://linux-hardware.org/?probe=bd1d84d6e7) | Apr 07, 2021 |
| Lenovo        | ThinkPad E495 20NEA001GE    | [c7a893da2e](https://linux-hardware.org/?probe=c7a893da2e) | Apr 06, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | [c40cb2c60f](https://linux-hardware.org/?probe=c40cb2c60f) | Apr 06, 2021 |
| Dell          | Precision 5530              | [64ca23f74b](https://linux-hardware.org/?probe=64ca23f74b) | Apr 06, 2021 |
| Toshiba       | Satellite L300D             | [35514af81d](https://linux-hardware.org/?probe=35514af81d) | Apr 04, 2021 |
| Dell          | Inspiron 5593               | [bf647eb6cd](https://linux-hardware.org/?probe=bf647eb6cd) | Apr 03, 2021 |
| Dell          | Inspiron N5110              | [6fe414f2da](https://linux-hardware.org/?probe=6fe414f2da) | Apr 02, 2021 |
| Acer          | Aspire A515-54G             | [4ceb1f2a16](https://linux-hardware.org/?probe=4ceb1f2a16) | Mar 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [fc6346c32b](https://linux-hardware.org/?probe=fc6346c32b) | Mar 29, 2021 |
| Dell          | Latitude 3400               | [e1cab5dc75](https://linux-hardware.org/?probe=e1cab5dc75) | Mar 29, 2021 |
| Lenovo        | B71-80 80RJ                 | [178235fdc8](https://linux-hardware.org/?probe=178235fdc8) | Mar 28, 2021 |
| HP            | EliteBook 850 G5            | [889d834138](https://linux-hardware.org/?probe=889d834138) | Mar 26, 2021 |
| HP            | 250 G2                      | [54d0d70b5f](https://linux-hardware.org/?probe=54d0d70b5f) | Mar 24, 2021 |
| Dell          | Inspiron 5570               | [4faf6a3407](https://linux-hardware.org/?probe=4faf6a3407) | Mar 23, 2021 |
| HP            | EliteBook 8530p             | [7ee41a2d5d](https://linux-hardware.org/?probe=7ee41a2d5d) | Mar 23, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [e4bd78422e](https://linux-hardware.org/?probe=e4bd78422e) | Mar 22, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [c99d44a48e](https://linux-hardware.org/?probe=c99d44a48e) | Mar 21, 2021 |
| ASUSTek       | X555LD                      | [cf0c496200](https://linux-hardware.org/?probe=cf0c496200) | Mar 20, 2021 |
| Dell          | Latitude E6400              | [ae7a7ffce1](https://linux-hardware.org/?probe=ae7a7ffce1) | Mar 19, 2021 |
| HP            | 250 G6 Notebook PC          | [240e99298f](https://linux-hardware.org/?probe=240e99298f) | Mar 17, 2021 |
| Dell          | Latitude E6420              | [e7f5f57404](https://linux-hardware.org/?probe=e7f5f57404) | Mar 17, 2021 |
| Clevo         | W250ENQ / W270ENQ           | [aad8ca4f6f](https://linux-hardware.org/?probe=aad8ca4f6f) | Mar 17, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [9f125de705](https://linux-hardware.org/?probe=9f125de705) | Mar 16, 2021 |
| Dell          | Latitude 5411               | [e992a2c9e6](https://linux-hardware.org/?probe=e992a2c9e6) | Mar 16, 2021 |
| HP            | ProBook 455 G7              | [c8bdece188](https://linux-hardware.org/?probe=c8bdece188) | Mar 15, 2021 |
| HP            | EliteBook 2570p             | [0072a02a5d](https://linux-hardware.org/?probe=0072a02a5d) | Mar 14, 2021 |
| Lenovo        | ThinkPad T400 6475R1G       | [9a6cc50c52](https://linux-hardware.org/?probe=9a6cc50c52) | Mar 13, 2021 |
| HP            | Pavilion dv6                | [65c8aaa5aa](https://linux-hardware.org/?probe=65c8aaa5aa) | Mar 13, 2021 |
| HP            | Pavilion dv6                | [5eed23aaf7](https://linux-hardware.org/?probe=5eed23aaf7) | Mar 13, 2021 |
| Lenovo        | G500 20236                  | [453b938647](https://linux-hardware.org/?probe=453b938647) | Mar 13, 2021 |
| HP            | 250 G6 Notebook PC          | [ecb1d8ee1d](https://linux-hardware.org/?probe=ecb1d8ee1d) | Mar 11, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [fc3b7d2f2b](https://linux-hardware.org/?probe=fc3b7d2f2b) | Mar 10, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [b1a4fc67b5](https://linux-hardware.org/?probe=b1a4fc67b5) | Mar 10, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [da00de06ed](https://linux-hardware.org/?probe=da00de06ed) | Mar 10, 2021 |
| HP            | EliteBook 2170p             | [dc06698753](https://linux-hardware.org/?probe=dc06698753) | Mar 10, 2021 |
| ASUSTek       | UX51VZA                     | [14ae24e6d8](https://linux-hardware.org/?probe=14ae24e6d8) | Mar 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [590b33fc27](https://linux-hardware.org/?probe=590b33fc27) | Mar 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [094e63ef62](https://linux-hardware.org/?probe=094e63ef62) | Mar 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [fb0bf9134c](https://linux-hardware.org/?probe=fb0bf9134c) | Mar 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [192f0fd756](https://linux-hardware.org/?probe=192f0fd756) | Mar 05, 2021 |
| Dell          | XPS 13 9300                 | [c4265bb6c4](https://linux-hardware.org/?probe=c4265bb6c4) | Mar 04, 2021 |
| Lenovo        | Flex 2 Pro-15 80FL          | [8e5ead087c](https://linux-hardware.org/?probe=8e5ead087c) | Mar 04, 2021 |
| Toshiba       | Satellite L740              | [91b7d3fb4d](https://linux-hardware.org/?probe=91b7d3fb4d) | Mar 02, 2021 |
| HP            | ProBook 470 G4              | [c3d85c83ec](https://linux-hardware.org/?probe=c3d85c83ec) | Feb 28, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [675be05d71](https://linux-hardware.org/?probe=675be05d71) | Feb 27, 2021 |
| Dell          | Latitude E6230              | [c3772d78aa](https://linux-hardware.org/?probe=c3772d78aa) | Feb 26, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [5dcdaebb4e](https://linux-hardware.org/?probe=5dcdaebb4e) | Feb 26, 2021 |
| Dell          | Latitude E6410              | [6f3fa9e9f2](https://linux-hardware.org/?probe=6f3fa9e9f2) | Feb 26, 2021 |
| HP            | ProBook 4540s               | [9ab78f21ad](https://linux-hardware.org/?probe=9ab78f21ad) | Feb 26, 2021 |
| HP            | ProBook 4540s               | [dd4d88de48](https://linux-hardware.org/?probe=dd4d88de48) | Feb 26, 2021 |
| ASUSTek       | X555LD                      | [665cf4701a](https://linux-hardware.org/?probe=665cf4701a) | Feb 25, 2021 |
| ASUSTek       | M50Vc                       | [8abf85e052](https://linux-hardware.org/?probe=8abf85e052) | Feb 24, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [58d3bac346](https://linux-hardware.org/?probe=58d3bac346) | Feb 24, 2021 |
| ASUSTek       | X751SJ                      | [81295695f3](https://linux-hardware.org/?probe=81295695f3) | Feb 24, 2021 |
| Lenovo        | IdeaPad Z580                | [9cd18dc0e4](https://linux-hardware.org/?probe=9cd18dc0e4) | Feb 24, 2021 |
| ASUSTek       | M50Vc                       | [3a9a5e9b7c](https://linux-hardware.org/?probe=3a9a5e9b7c) | Feb 24, 2021 |
| ASUSTek       | M50Vc                       | [295654ca20](https://linux-hardware.org/?probe=295654ca20) | Feb 24, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [f1d7117dc7](https://linux-hardware.org/?probe=f1d7117dc7) | Feb 23, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [9d65892538](https://linux-hardware.org/?probe=9d65892538) | Feb 22, 2021 |
| Dell          | G5 5587                     | [0b0fc3b694](https://linux-hardware.org/?probe=0b0fc3b694) | Feb 22, 2021 |
| Lenovo        | ThinkPad T490 20N2000CMC    | [b23d98dd6a](https://linux-hardware.org/?probe=b23d98dd6a) | Feb 22, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [db101fb87e](https://linux-hardware.org/?probe=db101fb87e) | Feb 21, 2021 |
| ASUSTek       | K55VM                       | [7e11b6bd85](https://linux-hardware.org/?probe=7e11b6bd85) | Feb 20, 2021 |
| HP            | EliteBook 2170p             | [36d10d9091](https://linux-hardware.org/?probe=36d10d9091) | Feb 16, 2021 |
| Dell          | Latitude 3400               | [38dbd98cd4](https://linux-hardware.org/?probe=38dbd98cd4) | Feb 15, 2021 |
| Lenovo        | Z710 20250                  | [c9694dd19b](https://linux-hardware.org/?probe=c9694dd19b) | Feb 15, 2021 |
| UMAX          | VisionBook 14Wa Plus        | [85de5460d8](https://linux-hardware.org/?probe=85de5460d8) | Feb 15, 2021 |
| ASUSTek       | F5RL                        | [6379e4d092](https://linux-hardware.org/?probe=6379e4d092) | Feb 12, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4ce0e6df68](https://linux-hardware.org/?probe=4ce0e6df68) | Feb 11, 2021 |
| Dell          | Studio 1747                 | [4ca3a3577f](https://linux-hardware.org/?probe=4ca3a3577f) | Feb 11, 2021 |
| ASUSTek       | X453SA                      | [5e4fcc2492](https://linux-hardware.org/?probe=5e4fcc2492) | Feb 10, 2021 |
| HP            | EliteBook 850 G6            | [40877f0c5d](https://linux-hardware.org/?probe=40877f0c5d) | Feb 10, 2021 |
| HP            | EliteBook 840 G6            | [4caff97f56](https://linux-hardware.org/?probe=4caff97f56) | Feb 08, 2021 |
| Dell          | Latitude E6230              | [6562ca7135](https://linux-hardware.org/?probe=6562ca7135) | Feb 07, 2021 |
| HP            | Stream Laptop 11-y0XX       | [1a6227c6cf](https://linux-hardware.org/?probe=1a6227c6cf) | Feb 07, 2021 |
| Sony          | VGN-FW31J                   | [3ac086a40c](https://linux-hardware.org/?probe=3ac086a40c) | Feb 07, 2021 |
| Dell          | Latitude E5450              | [9b2f037a8e](https://linux-hardware.org/?probe=9b2f037a8e) | Feb 06, 2021 |
| Dell          | Latitude E5450              | [9cce8a2306](https://linux-hardware.org/?probe=9cce8a2306) | Feb 06, 2021 |
| Dell          | Latitude E6410              | [02a7d362ab](https://linux-hardware.org/?probe=02a7d362ab) | Feb 05, 2021 |
| Dell          | Latitude E6400              | [99e1f46388](https://linux-hardware.org/?probe=99e1f46388) | Feb 03, 2021 |
| Acer          | Aspire S3-391               | [c7205a1bc6](https://linux-hardware.org/?probe=c7205a1bc6) | Feb 02, 2021 |
| Lenovo        | G510 20238                  | [29483c03e0](https://linux-hardware.org/?probe=29483c03e0) | Feb 01, 2021 |
| ASUSTek       | X555LD                      | [eb3be3f63f](https://linux-hardware.org/?probe=eb3be3f63f) | Jan 31, 2021 |
| Dell          | Inspiron 7577               | [46453067b0](https://linux-hardware.org/?probe=46453067b0) | Jan 31, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [bbfd58bb17](https://linux-hardware.org/?probe=bbfd58bb17) | Jan 31, 2021 |
| Acer          | Aspire one                  | [596cf5fb05](https://linux-hardware.org/?probe=596cf5fb05) | Jan 30, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [ebe001400f](https://linux-hardware.org/?probe=ebe001400f) | Jan 30, 2021 |
| Acer          | Aspire V7-581G              | [bc8dcae398](https://linux-hardware.org/?probe=bc8dcae398) | Jan 28, 2021 |
| HP            | EliteBook 820 G2            | [655fd94c5b](https://linux-hardware.org/?probe=655fd94c5b) | Jan 27, 2021 |
| Dell          | Precision 5510              | [f548cf6034](https://linux-hardware.org/?probe=f548cf6034) | Jan 27, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [59a1df6c23](https://linux-hardware.org/?probe=59a1df6c23) | Jan 27, 2021 |
| HP            | EliteBook 820 G2            | [0d9fb09cb0](https://linux-hardware.org/?probe=0d9fb09cb0) | Jan 27, 2021 |
| HP            | 250 G6 Notebook PC          | [e92acb1c9f](https://linux-hardware.org/?probe=e92acb1c9f) | Jan 25, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [a519fed9ad](https://linux-hardware.org/?probe=a519fed9ad) | Jan 25, 2021 |
| Dell          | Latitude E5500              | [bf4f6f14c2](https://linux-hardware.org/?probe=bf4f6f14c2) | Jan 22, 2021 |
| Dell          | Precision 5510              | [023ebcd846](https://linux-hardware.org/?probe=023ebcd846) | Jan 21, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 156       | 13.18%  |
| Ubuntu 18.04                 | 83        | 7.01%   |
| OpenMandriva 4.2             | 74        | 6.25%   |
| OpenMandriva 4.50            | 57        | 4.81%   |
| Ubuntu 22.04                 | 43        | 3.63%   |
| OpenMandriva 4.3             | 35        | 2.96%   |
| Ubuntu 21.10                 | 28        | 2.36%   |
| Ubuntu 19.10                 | 22        | 1.86%   |
| Fedora 34                    | 22        | 1.86%   |
| Ubuntu 20.10                 | 21        | 1.77%   |
| Ubuntu 21.04                 | 18        | 1.52%   |
| Zorin 16                     | 17        | 1.44%   |
| Zorin 15                     | 17        | 1.44%   |
| Linux Mint 20                | 17        | 1.44%   |
| Debian 11                    | 17        | 1.44%   |
| Arch                         | 17        | 1.44%   |
| Linux Mint 20.2              | 16        | 1.35%   |
| Linux Mint 19.3              | 16        | 1.35%   |
| Arch Rolling                 | 15        | 1.27%   |
| Linux Mint 20.3              | 14        | 1.18%   |
| Fedora 35                    | 14        | 1.18%   |
| Fedora 33                    | 14        | 1.18%   |
| Manjaro                      | 13        | 1.1%    |
| Linux Mint 20.1              | 13        | 1.1%    |
| Fedora 32                    | 13        | 1.1%    |
| Fedora 31                    | 13        | 1.1%    |
| Xubuntu 20.04                | 12        | 1.01%   |
| Ubuntu 19.04                 | 12        | 1.01%   |
| openSUSE Tumbleweed-XXXXXXXX | 12        | 1.01%   |
| Linux Mint 21                | 12        | 1.01%   |
| Fedora 36                    | 12        | 1.01%   |
| OpenMandriva 23.01           | 10        | 0.84%   |
| Linux Mint 21.1              | 10        | 0.84%   |
| Kubuntu 20.04                | 10        | 0.84%   |
| Xubuntu 18.04                | 9         | 0.76%   |
| Fedora 37                    | 9         | 0.76%   |
| Debian 10                    | 9         | 0.76%   |
| Pop!_OS 20.04                | 8         | 0.68%   |
| KDE neon 20.04               | 7         | 0.59%   |
| Ubuntu 22.10                 | 6         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 369       | 33.21%  |
| OpenMandriva     | 178       | 16.02%  |
| Fedora           | 100       | 9%      |
| Linux Mint       | 99        | 8.91%   |
| Zorin            | 35        | 3.15%   |
| Xubuntu          | 33        | 2.97%   |
| Manjaro          | 32        | 2.88%   |
| Arch             | 32        | 2.88%   |
| Debian           | 31        | 2.79%   |
| Kubuntu          | 22        | 1.98%   |
| Pop!_OS          | 20        | 1.8%    |
| Gentoo           | 18        | 1.62%   |
| openSUSE         | 17        | 1.53%   |
| ROSA             | 16        | 1.44%   |
| Lubuntu          | 11        | 0.99%   |
| KDE neon         | 10        | 0.9%    |
| Kali             | 9         | 0.81%   |
| Endless          | 8         | 0.72%   |
| Elementary       | 8         | 0.72%   |
| ArcoLinux        | 6         | 0.54%   |
| Ubuntu Unity     | 5         | 0.45%   |
| Ubuntu MATE      | 5         | 0.45%   |
| RHEL             | 5         | 0.45%   |
| SteamOS          | 4         | 0.36%   |
| Parrot           | 3         | 0.27%   |
| MX               | 3         | 0.27%   |
| BlackPanther     | 3         | 0.27%   |
| Rocky Linux      | 2         | 0.18%   |
| LinuxFX          | 2         | 0.18%   |
| EndeavourOS      | 2         | 0.18%   |
| Artix            | 2         | 0.18%   |
| Void Linux       | 1         | 0.09%   |
| Ubuntu Budgie    | 1         | 0.09%   |
| SystemRescue     | 1         | 0.09%   |
| Solus            | 1         | 0.09%   |
| Sabayon          | 1         | 0.09%   |
| Reborn OS        | 1         | 0.09%   |
| Peppermint       | 1         | 0.09%   |
| org.kde.Platform | 1         | 0.09%   |
| Nobara           | 1         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 73        | 5.7%    |
| 5.14.7-desktop-1omv4050  | 55        | 4.29%   |
| 5.16.7-desktop-1omv4003  | 34        | 2.65%   |
| 5.4.0-42-generic         | 23        | 1.8%    |
| 5.4.0-52-generic         | 15        | 1.17%   |
| 5.15.0-46-generic        | 15        | 1.17%   |
| 5.4.0-26-generic         | 13        | 1.01%   |
| 5.15.0-56-generic        | 12        | 0.94%   |
| 5.4.0-58-generic         | 11        | 0.86%   |
| 5.3.0-40-generic         | 11        | 0.86%   |
| 5.15.0-58-generic        | 10        | 0.78%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.7%    |
| 5.4.0-65-generic         | 9         | 0.7%    |
| 5.15.0-48-generic        | 9         | 0.7%    |
| 5.0.0-37-generic         | 9         | 0.7%    |
| 5.8.0-59-generic         | 8         | 0.62%   |
| 5.4.0-48-generic         | 8         | 0.62%   |
| 5.4.0-40-generic         | 8         | 0.62%   |
| 5.15.0-52-generic        | 8         | 0.62%   |
| 5.13.0-21-generic        | 8         | 0.62%   |
| 5.4.0-91-generic         | 7         | 0.55%   |
| 5.11.0-27-generic        | 7         | 0.55%   |
| 5.8.0-53-generic         | 6         | 0.47%   |
| 5.4.0-70-generic         | 6         | 0.47%   |
| 5.4.0-56-generic         | 6         | 0.47%   |
| 5.4.0-37-generic         | 6         | 0.47%   |
| 5.4.0-29-generic         | 6         | 0.47%   |
| 5.3.0-46-generic         | 6         | 0.47%   |
| 5.3.0-42-generic         | 6         | 0.47%   |
| 5.3.0-28-generic         | 6         | 0.47%   |
| 5.13.0-30-generic        | 6         | 0.47%   |
| 5.13.0-22-generic        | 6         | 0.47%   |
| 5.11.0-34-generic        | 6         | 0.47%   |
| 5.11.0-25-generic        | 6         | 0.47%   |
| 5.11.0-22-generic        | 6         | 0.47%   |
| 5.0.0-31-generic         | 6         | 0.47%   |
| 5.0.0-25-generic         | 6         | 0.47%   |
| 5.8.0-48-generic         | 5         | 0.39%   |
| 5.4.0-7642-generic       | 5         | 0.39%   |
| 5.3.0-45-generic         | 5         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 190       | 15.79%  |
| 5.15.0  | 85        | 7.07%   |
| 5.10.14 | 73        | 6.07%   |
| 5.3.0   | 68        | 5.65%   |
| 5.13.0  | 64        | 5.32%   |
| 5.11.0  | 63        | 5.24%   |
| 5.8.0   | 58        | 4.82%   |
| 4.15.0  | 58        | 4.82%   |
| 5.14.7  | 56        | 4.66%   |
| 5.0.0   | 44        | 3.66%   |
| 5.16.7  | 35        | 2.91%   |
| 4.18.0  | 26        | 2.16%   |
| 5.10.0  | 25        | 2.08%   |
| 6.1.1   | 12        | 1%      |
| 5.19.0  | 11        | 0.91%   |
| 4.19.0  | 8         | 0.67%   |
| 5.15.12 | 5         | 0.42%   |
| 4.13.0  | 5         | 0.42%   |
| 5.9.0   | 4         | 0.33%   |
| 5.6.16  | 4         | 0.33%   |
| 5.3.18  | 4         | 0.33%   |
| 5.17.0  | 4         | 0.33%   |
| 5.16.11 | 4         | 0.33%   |
| 5.14.0  | 4         | 0.33%   |
| 5.11.12 | 4         | 0.33%   |
| 5.10.74 | 4         | 0.33%   |
| 4.4.0   | 4         | 0.33%   |
| 6.0.2   | 3         | 0.25%   |
| 6.0.0   | 3         | 0.25%   |
| 5.9.16  | 3         | 0.25%   |
| 5.8.18  | 3         | 0.25%   |
| 5.18.12 | 3         | 0.25%   |
| 5.18.0  | 3         | 0.25%   |
| 5.17.5  | 3         | 0.25%   |
| 5.17.1  | 3         | 0.25%   |
| 5.16.2  | 3         | 0.25%   |
| 5.14.15 | 3         | 0.25%   |
| 5.13.19 | 3         | 0.25%   |
| 5.11.16 | 3         | 0.25%   |
| 5.10.52 | 3         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 206       | 17.2%   |
| 5.10    | 125       | 10.43%  |
| 5.15    | 114       | 9.52%   |
| 5.11    | 84        | 7.01%   |
| 5.13    | 77        | 6.43%   |
| 5.3     | 76        | 6.34%   |
| 5.8     | 74        | 6.18%   |
| 5.14    | 72        | 6.01%   |
| 4.15    | 60        | 5.01%   |
| 5.16    | 52        | 4.34%   |
| 5.0     | 46        | 3.84%   |
| 4.18    | 28        | 2.34%   |
| 5.19    | 25        | 2.09%   |
| 6.1     | 23        | 1.92%   |
| 5.17    | 20        | 1.67%   |
| 6.0     | 19        | 1.59%   |
| 5.9     | 15        | 1.25%   |
| 5.6     | 15        | 1.25%   |
| 5.18    | 15        | 1.25%   |
| 4.19    | 12        | 1%      |
| 5.12    | 7         | 0.58%   |
| 4.9     | 7         | 0.58%   |
| 5.7     | 6         | 0.5%    |
| 5.5     | 6         | 0.5%    |
| 4.13    | 5         | 0.42%   |
| 4.4     | 4         | 0.33%   |
| 5.1     | 2         | 0.17%   |
| 4.8     | 1         | 0.08%   |
| 4.17    | 1         | 0.08%   |
| 4.14    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1057      | 96.53%  |
| i686   | 38        | 3.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 456       | 40.35%  |
| KDE5            | 266       | 23.54%  |
| Unknown         | 136       | 12.04%  |
| XFCE            | 92        | 8.14%   |
| X-Cinnamon      | 50        | 4.42%   |
| MATE            | 28        | 2.48%   |
| KDE             | 23        | 2.04%   |
| Cinnamon        | 18        | 1.59%   |
| Pantheon        | 8         | 0.71%   |
| LXQt            | 8         | 0.71%   |
| Unity           | 6         | 0.53%   |
| LXDE            | 6         | 0.53%   |
| KDE4            | 6         | 0.53%   |
| GNOME Flashback | 6         | 0.53%   |
| awesome         | 4         | 0.35%   |
| i3              | 3         | 0.27%   |
| sway            | 2         | 0.18%   |
| qtile           | 2         | 0.18%   |
| openbox         | 2         | 0.18%   |
| Budgie          | 2         | 0.18%   |
| XSession        | 1         | 0.09%   |
| xinitrc         | 1         | 0.09%   |
| GNUstep         | 1         | 0.09%   |
| Enlightenment   | 1         | 0.09%   |
| DWM             | 1         | 0.09%   |
| custom          | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 860       | 76.65%  |
| Wayland | 171       | 15.24%  |
| Unknown | 81        | 7.22%   |
| Tty     | 10        | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 494       | 43.72%  |
| SDDM    | 259       | 22.92%  |
| GDM     | 133       | 11.77%  |
| GDM3    | 98        | 8.67%   |
| LightDM | 91        | 8.05%   |
| TDM     | 39        | 3.45%   |
| KDM     | 5         | 0.44%   |
| XDM     | 4         | 0.35%   |
| SLiM    | 3         | 0.27%   |
| LXDM    | 2         | 0.18%   |
| Ly      | 1         | 0.09%   |
| GREETD  | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| cs_CZ   | 597       | 53.59%  |
| en_US   | 317       | 28.46%  |
| Unknown | 122       | 10.95%  |
| en_GB   | 22        | 1.97%   |
| C       | 20        | 1.8%    |
| ru_RU   | 14        | 1.26%   |
| sk_SK   | 4         | 0.36%   |
| POSIX   | 3         | 0.27%   |
| pl_PL   | 2         | 0.18%   |
| it_IT   | 2         | 0.18%   |
| fr_FR   | 2         | 0.18%   |
| de_DE   | 2         | 0.18%   |
| uk_UA   | 1         | 0.09%   |
| ro_RO   | 1         | 0.09%   |
| es_ES   | 1         | 0.09%   |
| en_NG   | 1         | 0.09%   |
| en_150  | 1         | 0.09%   |
| el_GR   | 1         | 0.09%   |
| bg_BG   | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 584       | 52%     |
| EFI  | 539       | 48%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 750       | 67.69%  |
| Overlay  | 197       | 17.78%  |
| Btrfs    | 89        | 8.03%   |
| Unknown  | 33        | 2.98%   |
| Xfs      | 23        | 2.08%   |
| Zfs      | 5         | 0.45%   |
| Ext3     | 3         | 0.27%   |
| Tmpfs    | 2         | 0.18%   |
| Ext2     | 2         | 0.18%   |
| Aufs     | 2         | 0.18%   |
| Reiserfs | 1         | 0.09%   |
| F2fs     | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 527       | 47.52%  |
| GPT     | 371       | 33.45%  |
| MBR     | 211       | 19.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1005      | 91.12%  |
| Yes       | 98        | 8.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 701       | 62.81%  |
| Yes       | 415       | 37.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 278       | 25.39%  |
| ASUSTek Computer               | 226       | 20.64%  |
| Hewlett-Packard                | 203       | 18.54%  |
| Dell                           | 149       | 13.61%  |
| Acer                           | 103       | 9.41%   |
| MSI                            | 17        | 1.55%   |
| Toshiba                        | 16        | 1.46%   |
| UMAX                           | 15        | 1.37%   |
| Sony                           | 14        | 1.28%   |
| Fujitsu                        | 9         | 0.82%   |
| HUAWEI                         | 7         | 0.64%   |
| Apple                          | 5         | 0.46%   |
| Unknown                        | 5         | 0.46%   |
| Valve                          | 4         | 0.37%   |
| Timi                           | 4         | 0.37%   |
| TUXEDO                         | 3         | 0.27%   |
| Packard Bell                   | 3         | 0.27%   |
| Google                         | 3         | 0.27%   |
| Fujitsu Siemens                | 3         | 0.27%   |
| Notebook                       | 2         | 0.18%   |
| Insyde                         | 2         | 0.18%   |
| Chuwi                          | 2         | 0.18%   |
| Alienware                      | 2         | 0.18%   |
| Standard                       | 1         | 0.09%   |
| SmbiosType1_SystemManufacturer | 1         | 0.09%   |
| SLIMBOOK                       | 1         | 0.09%   |
| Samsung Electronics            | 1         | 0.09%   |
| Purism                         | 1         | 0.09%   |
| Prestigio                      | 1         | 0.09%   |
| Panasonic                      | 1         | 0.09%   |
| Medion                         | 1         | 0.09%   |
| Jumper                         | 1         | 0.09%   |
| Intel                          | 1         | 0.09%   |
| INET                           | 1         | 0.09%   |
| In-Sing                        | 1         | 0.09%   |
| IBM                            | 1         | 0.09%   |
| Gigabyte Technology            | 1         | 0.09%   |
| EUROCOM                        | 1         | 0.09%   |
| Dynabook                       | 1         | 0.09%   |
| DATABOX                        | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ASUS UX31E                               | 114       | 10.41%  |
| Unknown                                  | 7         | 0.64%   |
| HP ProBook 455 G7                        | 6         | 0.55%   |
| Lenovo ThinkPad E14 20RA001LMC           | 5         | 0.46%   |
| HP ProBook 4530s                         | 5         | 0.46%   |
| HP ProBook 450 G5                        | 5         | 0.46%   |
| Dell Latitude E6400                      | 5         | 0.46%   |
| Dell Latitude 5401                       | 5         | 0.46%   |
| Valve Jupiter                            | 4         | 0.37%   |
| HP ProBook 4540s                         | 4         | 0.37%   |
| HP Pavilion dv7                          | 4         | 0.37%   |
| HP Notebook                              | 4         | 0.37%   |
| HP EliteBook 840 G6                      | 4         | 0.37%   |
| HP EliteBook 840 G3                      | 4         | 0.37%   |
| Dell XPS 15 7590                         | 4         | 0.37%   |
| Dell Precision M6500                     | 4         | 0.37%   |
| Acer Extensa 5620                        | 4         | 0.37%   |
| Lenovo Z50-75 80EC                       | 3         | 0.27%   |
| Lenovo ThinkPad T14 Gen 1 20UES2WA00     | 3         | 0.27%   |
| Lenovo IdeaPad S130-11IGM 81J1           | 3         | 0.27%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL    | 3         | 0.27%   |
| Lenovo IdeaPad 5 14ARE05 81YM            | 3         | 0.27%   |
| HP ProBook 4510s                         | 3         | 0.27%   |
| HP Pavilion dv6                          | 3         | 0.27%   |
| HP Laptop 15-bw0xx                       | 3         | 0.27%   |
| HP EliteBook 855 G7 Notebook PC          | 3         | 0.27%   |
| HP EliteBook 850 G6                      | 3         | 0.27%   |
| HP 250 G6 Notebook PC                    | 3         | 0.27%   |
| Dell XPS 15 9560                         | 3         | 0.27%   |
| Dell XPS 13 9360                         | 3         | 0.27%   |
| Dell Precision 5510                      | 3         | 0.27%   |
| Dell Latitude E6420                      | 3         | 0.27%   |
| Dell Latitude E5520                      | 3         | 0.27%   |
| Dell Latitude E5470                      | 3         | 0.27%   |
| Dell Latitude 7480                       | 3         | 0.27%   |
| Dell Latitude 5480                       | 3         | 0.27%   |
| ASUS VivoBook_ASUSLaptop X3500PH_K3500PH | 3         | 0.27%   |
| ASUS E502SA                              | 3         | 0.27%   |
| Acer Extensa 5235                        | 3         | 0.27%   |
| Acer Extensa 5220                        | 3         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 148       | 13.52%  |
| ASUS UX31E            | 114       | 10.41%  |
| Dell Latitude         | 76        | 6.94%   |
| Acer Aspire           | 61        | 5.57%   |
| Lenovo IdeaPad        | 58        | 5.3%    |
| HP ProBook            | 58        | 5.3%    |
| HP EliteBook          | 54        | 4.93%   |
| HP Pavilion           | 23        | 2.1%    |
| Dell XPS              | 22        | 2.01%   |
| Dell Precision        | 18        | 1.64%   |
| Dell Inspiron         | 18        | 1.64%   |
| Toshiba Satellite     | 15        | 1.37%   |
| HP Compaq             | 14        | 1.28%   |
| Acer Extensa          | 14        | 1.28%   |
| UMAX VisionBook       | 12        | 1.1%    |
| Lenovo Yoga           | 12        | 1.1%    |
| Lenovo Legion         | 12        | 1.1%    |
| HP Laptop             | 12        | 1.1%    |
| ASUS VivoBook         | 12        | 1.1%    |
| ASUS ZenBook          | 11        | 1%      |
| Acer TravelMate       | 10        | 0.91%   |
| HP ZBook              | 9         | 0.82%   |
| Fujitsu LIFEBOOK      | 9         | 0.82%   |
| Acer Swift            | 9         | 0.82%   |
| Lenovo ThinkBook      | 8         | 0.73%   |
| HP 250                | 7         | 0.64%   |
| Dell Vostro           | 7         | 0.64%   |
| Unknown               | 7         | 0.64%   |
| Valve Jupiter         | 4         | 0.37%   |
| HP Notebook           | 4         | 0.37%   |
| ASUS ASUS             | 4         | 0.37%   |
| Packard Bell EasyNote | 3         | 0.27%   |
| Lenovo Z50-75         | 3         | 0.27%   |
| HP OMEN               | 3         | 0.27%   |
| Fujitsu Siemens AMILO | 3         | 0.27%   |
| Dell G5               | 3         | 0.27%   |
| ASUS ROG              | 3         | 0.27%   |
| ASUS E502SA           | 3         | 0.27%   |
| Acer Nitro            | 3         | 0.27%   |
| MSI GE620             | 2         | 0.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 179       | 16.35%  |
| 2020    | 103       | 9.41%   |
| 2019    | 98        | 8.95%   |
| 2021    | 82        | 7.49%   |
| 2018    | 80        | 7.31%   |
| 2012    | 71        | 6.48%   |
| 2015    | 63        | 5.75%   |
| 2017    | 61        | 5.57%   |
| 2014    | 61        | 5.57%   |
| 2013    | 56        | 5.11%   |
| 2008    | 55        | 5.02%   |
| 2016    | 51        | 4.66%   |
| 2010    | 43        | 3.93%   |
| 2007    | 31        | 2.83%   |
| 2009    | 25        | 2.28%   |
| 2022    | 18        | 1.64%   |
| 2006    | 11        | 1%      |
| 2005    | 3         | 0.27%   |
| 2004    | 2         | 0.18%   |
| Unknown | 2         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1095      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 965       | 87.02%  |
| Enabled  | 144       | 12.98%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1091      | 99.63%  |
| Yes  | 4         | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 332       | 29.88%  |
| 4.01-8.0    | 235       | 21.15%  |
| 8.01-16.0   | 184       | 16.56%  |
| 16.01-24.0  | 160       | 14.4%   |
| 32.01-64.0  | 80        | 7.2%    |
| 1.01-2.0    | 61        | 5.49%   |
| 2.01-3.0    | 20        | 1.8%    |
| 24.01-32.0  | 16        | 1.44%   |
| 0.51-1.0    | 14        | 1.26%   |
| 64.01-256.0 | 8         | 0.72%   |
| 0.01-0.5    | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 464       | 38.6%   |
| 2.01-3.0   | 260       | 21.63%  |
| 4.01-8.0   | 172       | 14.31%  |
| 3.01-4.0   | 142       | 11.81%  |
| 0.51-1.0   | 72        | 5.99%   |
| 8.01-16.0  | 65        | 5.41%   |
| 0.01-0.5   | 15        | 1.25%   |
| 16.01-24.0 | 9         | 0.75%   |
| 32.01-64.0 | 2         | 0.17%   |
| 24.01-32.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 885       | 79.09%  |
| 2      | 196       | 17.52%  |
| 3      | 24        | 2.14%   |
| 0      | 13        | 1.16%   |
| 4      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 758       | 68.85%  |
| Yes       | 343       | 31.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 930       | 84.32%  |
| No        | 173       | 15.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1070      | 97.63%  |
| No        | 26        | 2.37%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 792       | 71.42%  |
| No        | 317       | 28.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Czechia | 1095      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Prague               | 474       | 41.73%  |
| Brno                 | 106       | 9.33%   |
| Ostrava              | 32        | 2.82%   |
| Pilsen               | 22        | 1.94%   |
| Olomouc              | 15        | 1.32%   |
| Pardubice            | 13        | 1.14%   |
| Liberec              | 13        | 1.14%   |
| České Budějovice  | 13        | 1.14%   |
| Hradec Králové     | 11        | 0.97%   |
| Chomutov             | 10        | 0.88%   |
| Most                 | 8         | 0.7%    |
| Havířov            | 8         | 0.7%    |
| Zlín                | 7         | 0.62%   |
| Karlovy Vary         | 7         | 0.62%   |
| Jihlava              | 7         | 0.62%   |
| Ústí nad Labem     | 6         | 0.53%   |
| Znojmo               | 5         | 0.44%   |
| Tábor               | 5         | 0.44%   |
| Roznov pod Radhostem | 5         | 0.44%   |
| Příbram            | 5         | 0.44%   |
| Přerov              | 5         | 0.44%   |
| Kladno               | 5         | 0.44%   |
| Teplice              | 4         | 0.35%   |
| Opava                | 4         | 0.35%   |
| Mladá Boleslav      | 4         | 0.35%   |
| Mariánské Lázně  | 4         | 0.35%   |
| Česká Lípa        | 4         | 0.35%   |
| Ceska Kamenice       | 4         | 0.35%   |
| Uvaly                | 3         | 0.26%   |
| Uhlirske Janovice    | 3         | 0.26%   |
| Třebíč            | 3         | 0.26%   |
| Slavkov u Brna       | 3         | 0.26%   |
| Prelouc              | 3         | 0.26%   |
| Praha 10             | 3         | 0.26%   |
| Pelhrimov            | 3         | 0.26%   |
| Odolena Voda         | 3         | 0.26%   |
| Mohelnice            | 3         | 0.26%   |
| Milovice             | 3         | 0.26%   |
| Kraluv Dvur          | 3         | 0.26%   |
| Kralupy nad Vltavou  | 3         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 213       | 281    | 16.45%  |
| Sandisk                        | 172       | 180    | 13.28%  |
| WDC                            | 137       | 163    | 10.58%  |
| Seagate                        | 127       | 177    | 9.81%   |
| Toshiba                        | 101       | 124    | 7.8%    |
| Kingston                       | 72        | 77     | 5.56%   |
| Unknown                        | 69        | 89     | 5.33%   |
| SK hynix                       | 57        | 71     | 4.4%    |
| Hitachi                        | 45        | 53     | 3.47%   |
| HGST                           | 40        | 49     | 3.09%   |
| Micron Technology              | 37        | 45     | 2.86%   |
| Intel                          | 36        | 44     | 2.78%   |
| A-DATA Technology              | 24        | 27     | 1.85%   |
| Crucial                        | 20        | 30     | 1.54%   |
| Patriot                        | 19        | 24     | 1.47%   |
| KIOXIA                         | 11        | 18     | 0.85%   |
| Transcend                      | 9         | 9      | 0.69%   |
| Unknown                        | 8         | 9      | 0.62%   |
| LITEONIT                       | 7         | 9      | 0.54%   |
| Fujitsu                        | 7         | 7      | 0.54%   |
| Apacer                         | 7         | 9      | 0.54%   |
| China                          | 6         | 7      | 0.46%   |
| Phison                         | 5         | 12     | 0.39%   |
| LITEON                         | 5         | 5      | 0.39%   |
| Phison Electronics             | 4         | 4      | 0.31%   |
| JMicron Technology             | 4         | 4      | 0.31%   |
| Apple                          | 4         | 4      | 0.31%   |
| Silicon Motion                 | 3         | 3      | 0.23%   |
| Gigabyte Technology            | 3         | 7      | 0.23%   |
| ASMedia                        | 3         | 5      | 0.23%   |
| Verbatim                       | 2         | 2      | 0.15%   |
| UMAX                           | 2         | 2      | 0.15%   |
| Team                           | 2         | 2      | 0.15%   |
| Solid State Storage Technology | 2         | 2      | 0.15%   |
| Micron/Crucial Technology      | 2         | 2      | 0.15%   |
| Lite-On                        | 2         | 4      | 0.15%   |
| Lenovo                         | 2         | 3      | 0.15%   |
| GOODRAM                        | 2         | 3      | 0.15%   |
| Corsair                        | 2         | 2      | 0.15%   |
| ASMT                           | 2         | 2      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB                              | 113       | 8.38%   |
| Samsung NVMe SSD Drive 512GB                        | 17        | 1.26%   |
| HGST HTS721010A9E630 1TB                            | 16        | 1.19%   |
| Seagate ST1000LM035-1RK172 1TB                      | 14        | 1.04%   |
| Unknown MMC Card  32GB                              | 13        | 0.96%   |
| Samsung SSD 860 EVO 500GB                           | 13        | 0.96%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                      | 10        | 0.74%   |
| SanDisk NVMe SSD Drive 512GB                        | 9         | 0.67%   |
| Kingston SA400S37480G 480GB SSD                     | 9         | 0.67%   |
| Kingston SA400S37240G 240GB SSD                     | 9         | 0.67%   |
| Unknown MMC Card  64GB                              | 8         | 0.59%   |
| Toshiba NVMe SSD Drive 256GB                        | 8         | 0.59%   |
| Toshiba MQ01ABD100 1TB                              | 8         | 0.59%   |
| SK hynix NVMe SSD Drive 512GB                       | 8         | 0.59%   |
| Samsung SSD 850 EVO 250GB                           | 8         | 0.59%   |
| Unknown                                             | 8         | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 7         | 0.52%   |
| Unknown MMC Card  16GB                              | 7         | 0.52%   |
| Toshiba MQ01ABF050 500GB                            | 7         | 0.52%   |
| Seagate ST500LT012-1DG142 500GB                     | 7         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 7         | 0.52%   |
| SanDisk NVMe SSD Drive 1024GB                       | 7         | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 7         | 0.52%   |
| Patriot Burst 480GB SSD                             | 7         | 0.52%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 7         | 0.52%   |
| HGST HTS725050A7E630 500GB                          | 7         | 0.52%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 6         | 0.44%   |
| Unknown MMC Card  128GB                             | 6         | 0.44%   |
| Toshiba NVMe SSD Drive 512GB                        | 6         | 0.44%   |
| Toshiba MQ04ABF100 1TB                              | 6         | 0.44%   |
| Seagate ST9500420AS 500GB                           | 6         | 0.44%   |
| Samsung SSD 970 EVO 1TB                             | 6         | 0.44%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 6         | 0.44%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 6         | 0.44%   |
| Kingston SA400S37120G 120GB SSD                     | 6         | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 5         | 0.37%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 5         | 0.37%   |
| Seagate ST500LM030-2E717D 500GB                     | 5         | 0.37%   |
| Seagate ST500LM000-1EJ162 500GB                     | 5         | 0.37%   |
| Seagate ST2000LM007-1R8174 2TB                      | 5         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 126       | 176    | 34.33%  |
| WDC                 | 80        | 95     | 21.8%   |
| Toshiba             | 59        | 67     | 16.08%  |
| Hitachi             | 45        | 53     | 12.26%  |
| HGST                | 40        | 49     | 10.9%   |
| Fujitsu             | 7         | 7      | 1.91%   |
| Samsung Electronics | 2         | 2      | 0.54%   |
| JMicron Technology  | 2         | 2      | 0.54%   |
| ASMedia             | 2         | 3      | 0.54%   |
| USB3.0              | 1         | 1      | 0.27%   |
| Unknown             | 1         | 1      | 0.27%   |
| SABRENT             | 1         | 1      | 0.27%   |
| IBM/Hitachi         | 1         | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 142       | 145    | 29.52%  |
| Samsung Electronics | 94        | 118    | 19.54%  |
| Kingston            | 55        | 60     | 11.43%  |
| WDC                 | 25        | 34     | 5.2%    |
| A-DATA Technology   | 22        | 25     | 4.57%   |
| Patriot             | 19        | 24     | 3.95%   |
| Crucial             | 19        | 29     | 3.95%   |
| Micron Technology   | 15        | 20     | 3.12%   |
| Intel               | 13        | 15     | 2.7%    |
| SK hynix            | 11        | 12     | 2.29%   |
| Transcend           | 9         | 9      | 1.87%   |
| Toshiba             | 9         | 11     | 1.87%   |
| LITEONIT            | 7         | 9      | 1.46%   |
| Apacer              | 7         | 9      | 1.46%   |
| China               | 6         | 7      | 1.25%   |
| LITEON              | 4         | 4      | 0.83%   |
| Apple               | 3         | 3      | 0.62%   |
| Verbatim            | 2         | 2      | 0.42%   |
| UMAX                | 2         | 2      | 0.42%   |
| GOODRAM             | 2         | 3      | 0.42%   |
| Gigabyte Technology | 2         | 5      | 0.42%   |
| ASMT                | 2         | 2      | 0.42%   |
| UMIS                | 1         | 1      | 0.21%   |
| TO Exter            | 1         | 2      | 0.21%   |
| Team                | 1         | 1      | 0.21%   |
| ShanDianZhe         | 1         | 1      | 0.21%   |
| Seagate             | 1         | 1      | 0.21%   |
| OCZ                 | 1         | 4      | 0.21%   |
| Netac               | 1         | 1      | 0.21%   |
| Mushkin             | 1         | 1      | 0.21%   |
| Hewlett-Packard     | 1         | 1      | 0.21%   |
| CT500MX5            | 1         | 1      | 0.21%   |
| ADATA SU            | 1         | 1      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 461       | 563    | 36.79%  |
| HDD     | 357       | 458    | 28.49%  |
| NVMe    | 347       | 461    | 27.69%  |
| MMC     | 81        | 105    | 6.46%   |
| Unknown | 7         | 9      | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 747       | 988    | 61.84%  |
| NVMe | 346       | 460    | 28.64%  |
| MMC  | 81        | 105    | 6.71%   |
| SAS  | 34        | 43     | 2.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 612       | 755    | 76.02%  |
| 0.51-1.0   | 176       | 236    | 21.86%  |
| 1.01-2.0   | 16        | 28     | 1.99%   |
| 3.01-4.0   | 1         | 2      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 282       | 24.78%  |
| 251-500        | 258       | 22.67%  |
| 1-20           | 199       | 17.49%  |
| 501-1000       | 150       | 13.18%  |
| 51-100         | 84        | 7.38%   |
| 1001-2000      | 51        | 4.48%   |
| 21-50          | 48        | 4.22%   |
| Unknown        | 40        | 3.51%   |
| More than 3000 | 18        | 1.58%   |
| 2001-3000      | 8         | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 555       | 46.88%  |
| 21-50          | 153       | 12.92%  |
| 101-250        | 151       | 12.75%  |
| 51-100         | 122       | 10.3%   |
| 251-500        | 96        | 8.11%   |
| 501-1000       | 41        | 3.46%   |
| Unknown        | 40        | 3.38%   |
| 1001-2000      | 16        | 1.35%   |
| More than 3000 | 6         | 0.51%   |
| 2001-3000      | 4         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                           | 113       | 113    | 63.84%  |
| HGST HTS725050A7E630 500GB                       | 3         | 3      | 1.69%   |
| Toshiba MQ01ABD075 752GB                         | 2         | 2      | 1.13%   |
| SK hynix BC711 HFM512GD3JX013N 512GB             | 2         | 3      | 1.13%   |
| Seagate ST9500420AS 500GB                        | 2         | 3      | 1.13%   |
| Seagate ST1000LX015-1U7172 1TB                   | 2         | 2      | 1.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 2         | 2      | 1.13%   |
| HGST HTS721010A9E630 1TB                         | 2         | 2      | 1.13%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                 | 1         | 1      | 0.56%   |
| WDC WD7500BPVT-22HXZT3 752GB                     | 1         | 1      | 0.56%   |
| WDC WD6400BPVT-60HXZT1 640GB                     | 1         | 1      | 0.56%   |
| WDC WD3200BEVT-60ZCT1 320GB                      | 1         | 1      | 0.56%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 0.56%   |
| Toshiba MK8037GSX 80GB                           | 1         | 1      | 0.56%   |
| Toshiba MK6465GSXN 640GB                         | 1         | 1      | 0.56%   |
| Toshiba MK5056GSY 500GB                          | 1         | 1      | 0.56%   |
| Toshiba MK2552GSX 250GB                          | 1         | 1      | 0.56%   |
| Toshiba MK1234GSX 120GB                          | 1         | 1      | 0.56%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD            | 1         | 1      | 0.56%   |
| SK hynix HFS128G39TND-N210A 128GB SSD            | 1         | 1      | 0.56%   |
| Seagate ST980811AS 80GB                          | 1         | 1      | 0.56%   |
| Seagate ST9500420ASG 500GB                       | 1         | 1      | 0.56%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 0.56%   |
| Seagate ST9250827AS 250GB                        | 1         | 1      | 0.56%   |
| Seagate ST9250410ASG 250GB                       | 1         | 1      | 0.56%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 0.56%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 0.56%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 0.56%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 0.56%   |
| Seagate ST2000LM007-1R8174 2TB                   | 1         | 1      | 0.56%   |
| SanDisk SD8SBAT-032G-1006 32GB SSD               | 1         | 1      | 0.56%   |
| SanDisk SD7SB3Q256G1002 256GB SSD                | 1         | 1      | 0.56%   |
| Samsung Electronics SSD 850 EVO 1TB              | 1         | 1      | 0.56%   |
| Samsung Electronics MZVLB1T0HALR-000L2 1TB       | 1         | 1      | 0.56%   |
| Samsung Electronics MZVL21T0HCLR-00B00 1TB       | 1         | 1      | 0.56%   |
| Samsung Electronics MZ7TE256HMHP-000L7 256GB SSD | 1         | 1      | 0.56%   |
| Micron Technology 1100 SATA 256GB SSD            | 1         | 1      | 0.56%   |
| LITEONIT LAT-128M2S 128GB SSD                    | 1         | 1      | 0.56%   |
| Kingston SHFS37A120G 120GB SSD                   | 1         | 1      | 0.56%   |
| Intel SSDSCKJF240A5L 240GB                       | 1         | 1      | 0.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 115       | 115    | 64.97%  |
| Seagate             | 16        | 17     | 9.04%   |
| Hitachi             | 9         | 9      | 5.08%   |
| Toshiba             | 8         | 8      | 4.52%   |
| HGST                | 7         | 7      | 3.95%   |
| WDC                 | 4         | 4      | 2.26%   |
| SK hynix            | 4         | 5      | 2.26%   |
| Samsung Electronics | 4         | 4      | 2.26%   |
| Intel               | 2         | 2      | 1.13%   |
| A-DATA Technology   | 2         | 3      | 1.13%   |
| Micron Technology   | 1         | 1      | 0.56%   |
| LITEONIT            | 1         | 1      | 0.56%   |
| Kingston            | 1         | 1      | 0.56%   |
| IBM/Hitachi         | 1         | 1      | 0.56%   |
| Fujitsu             | 1         | 1      | 0.56%   |
| Crucial             | 1         | 1      | 0.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 16        | 17     | 35.56%  |
| Hitachi     | 9         | 9      | 20%     |
| Toshiba     | 8         | 8      | 17.78%  |
| HGST        | 7         | 7      | 15.56%  |
| WDC         | 3         | 3      | 6.67%   |
| IBM/Hitachi | 1         | 1      | 2.22%   |
| Fujitsu     | 1         | 1      | 2.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 128       | 129    | 72.32%  |
| HDD  | 45        | 46     | 25.42%  |
| NVMe | 4         | 5      | 2.26%   |

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
| Detected | 595       | 948    | 52.06%  |
| Works    | 372       | 468    | 32.55%  |
| Malfunc  | 176       | 180    | 15.4%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 777       | 61.96%  |
| Samsung Electronics              | 125       | 9.97%   |
| AMD                              | 123       | 9.81%   |
| SanDisk                          | 55        | 4.39%   |
| SK hynix                         | 43        | 3.43%   |
| Toshiba America Info Systems     | 33        | 2.63%   |
| Micron Technology                | 22        | 1.75%   |
| Kingston Technology Company      | 17        | 1.36%   |
| KIOXIA                           | 13        | 1.04%   |
| Phison Electronics               | 12        | 0.96%   |
| Silicon Motion                   | 5         | 0.4%    |
| Union Memory (Shenzhen)          | 3         | 0.24%   |
| Silicon Integrated Systems [SiS] | 3         | 0.24%   |
| Micron/Crucial Technology        | 3         | 0.24%   |
| Lite-On Technology               | 3         | 0.24%   |
| ADATA Technology                 | 3         | 0.24%   |
| Solid State Storage Technology   | 2         | 0.16%   |
| Nvidia                           | 2         | 0.16%   |
| Lenovo                           | 2         | 0.16%   |
| ASMedia Technology               | 2         | 0.16%   |
| VIA Technologies                 | 1         | 0.08%   |
| Realtek Semiconductor            | 1         | 0.08%   |
| Marvell Technology Group         | 1         | 0.08%   |
| JMicron Technology               | 1         | 0.08%   |
| Biwin Storage Technology         | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 169       | 12.55%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 99        | 7.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 72        | 5.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 65        | 4.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 57        | 4.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 50        | 3.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 44        | 3.27%   |
| Samsung NVMe SSD Controller 980                                                  | 41        | 3.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 33        | 2.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 31        | 2.3%    |
| Intel Volume Management Device NVMe RAID Controller                              | 30        | 2.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 29        | 2.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 27        | 2%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 24        | 1.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 23        | 1.71%   |
| Micron Non-Volatile memory controller                                            | 22        | 1.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 20        | 1.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 20        | 1.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 20        | 1.48%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 19        | 1.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 18        | 1.34%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 17        | 1.26%   |
| Intel Comet Lake SATA AHCI Controller                                            | 15        | 1.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 14        | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 14        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 14        | 1.04%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 13        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 13        | 0.97%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 12        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 11        | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 10        | 0.74%   |
| SK hynix BC511                                                                   | 9         | 0.67%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 9         | 0.67%   |
| Intel Tiger Lake-LP SATA Controller                                              | 9         | 0.67%   |
| Intel SSD 660P Series                                                            | 9         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 0.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 9         | 0.67%   |
| SK hynix Non-Volatile memory controller                                          | 8         | 0.59%   |
| SanDisk Non-Volatile memory controller                                           | 8         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 787       | 60.59%  |
| NVMe | 349       | 26.87%  |
| RAID | 83        | 6.39%   |
| IDE  | 80        | 6.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 904       | 82.56%  |
| AMD    | 191       | 17.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 114       | 10.4%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 17        | 1.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 1.37%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 14        | 1.28%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 1.19%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 13        | 1.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 12        | 1.09%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 1.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 1.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 1%      |
| AMD Ryzen 5 4500U with Radeon Graphics        | 11        | 1%      |
| Intel Core i7-10850H CPU @ 2.70GHz            | 10        | 0.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 0.91%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 0.91%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 0.91%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 10        | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 9         | 0.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 0.82%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 0.73%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 8         | 0.73%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 0.73%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.73%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 7         | 0.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 7         | 0.64%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 7         | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.64%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.64%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 0.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 0.55%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.55%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 6         | 0.55%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 0.55%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 0.55%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 6         | 0.55%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 6         | 0.55%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 6         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 342       | 31.2%   |
| Intel Core i5           | 213       | 19.43%  |
| Intel Core 2 Duo        | 71        | 6.48%   |
| Intel Celeron           | 68        | 6.2%    |
| Other                   | 66        | 6.02%   |
| Intel Core i3           | 63        | 5.75%   |
| AMD Ryzen 5             | 43        | 3.92%   |
| AMD Ryzen 7             | 39        | 3.56%   |
| Intel Pentium           | 26        | 2.37%   |
| Intel Atom              | 22        | 2.01%   |
| AMD Ryzen 7 PRO         | 21        | 1.92%   |
| AMD A6                  | 12        | 1.09%   |
| AMD A4                  | 10        | 0.91%   |
| AMD A8                  | 7         | 0.64%   |
| Intel Pentium Dual-Core | 6         | 0.55%   |
| Intel Celeron M         | 6         | 0.55%   |
| Intel Pentium Silver    | 5         | 0.46%   |
| Intel Core 2            | 5         | 0.46%   |
| Intel Celeron Dual-Core | 5         | 0.46%   |
| Intel Pentium M         | 4         | 0.36%   |
| AMD Turion II           | 4         | 0.36%   |
| AMD Ryzen 9             | 4         | 0.36%   |
| AMD Ryzen 5 PRO         | 4         | 0.36%   |
| AMD Ryzen 3             | 4         | 0.36%   |
| AMD E1                  | 4         | 0.36%   |
| AMD E                   | 4         | 0.36%   |
| Intel Xeon              | 3         | 0.27%   |
| Intel Pentium Dual      | 3         | 0.27%   |
| Intel Genuine           | 3         | 0.27%   |
| AMD Turion 64 X2 Mobile | 3         | 0.27%   |
| AMD Mobile Sempron      | 3         | 0.27%   |
| AMD FX                  | 3         | 0.27%   |
| AMD E2                  | 3         | 0.27%   |
| AMD A10                 | 3         | 0.27%   |
| Intel Core i9           | 2         | 0.18%   |
| AMD Athlon X2           | 2         | 0.18%   |
| AMD Athlon II Dual-Core | 2         | 0.18%   |
| AMD A12                 | 2         | 0.18%   |
| Intel Core m5           | 1         | 0.09%   |
| Intel Core Duo          | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 590       | 53.83%  |
| 4       | 325       | 29.65%  |
| 6       | 80        | 7.3%    |
| 8       | 64        | 5.84%   |
| 1       | 28        | 2.55%   |
| 14      | 3         | 0.27%   |
| 10      | 3         | 0.27%   |
| 12      | 2         | 0.18%   |
| Unknown | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1095      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 789       | 71.99%  |
| 1       | 306       | 27.92%  |
| Unknown | 1         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1063      | 96.72%  |
| 32-bit         | 18        | 1.64%   |
| Unknown        | 17        | 1.55%   |
| 64-bit         | 1         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 195       | 17.23%  |
| 0x206a7    | 168       | 14.84%  |
| 0x306a9    | 48        | 4.24%   |
| 0x806ec    | 39        | 3.45%   |
| 0x806ea    | 39        | 3.45%   |
| 0x406e3    | 35        | 3.09%   |
| 0x1067a    | 35        | 3.09%   |
| 0x906ea    | 30        | 2.65%   |
| 0x806c1    | 30        | 2.65%   |
| 0x40651    | 29        | 2.56%   |
| 0x08600106 | 27        | 2.39%   |
| 0x306c3    | 26        | 2.3%    |
| 0x806e9    | 24        | 2.12%   |
| 0x306d4    | 22        | 1.94%   |
| 0x0a50000c | 21        | 1.86%   |
| 0x6fd      | 19        | 1.68%   |
| 0x30678    | 18        | 1.59%   |
| 0xa0652    | 14        | 1.24%   |
| 0x20655    | 14        | 1.24%   |
| 0x706a1    | 13        | 1.15%   |
| 0x506e3    | 13        | 1.15%   |
| 0x10676    | 12        | 1.06%   |
| 0x906e9    | 11        | 0.97%   |
| 0x406c3    | 11        | 0.97%   |
| 0x406c4    | 10        | 0.88%   |
| 0x08608103 | 10        | 0.88%   |
| 0x08108102 | 10        | 0.88%   |
| 0x906ed    | 9         | 0.8%    |
| 0x06006705 | 9         | 0.8%    |
| 0x706e5    | 8         | 0.71%   |
| 0x506c9    | 8         | 0.71%   |
| 0x08600104 | 8         | 0.71%   |
| 0x07030105 | 8         | 0.71%   |
| 0x806eb    | 7         | 0.62%   |
| 0x20652    | 7         | 0.62%   |
| 0x106e5    | 7         | 0.62%   |
| 0x10661    | 7         | 0.62%   |
| 0x08600103 | 7         | 0.62%   |
| 0x6fb      | 6         | 0.53%   |
| 0x6e8      | 6         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 188       | 17.17%  |
| SandyBridge      | 183       | 16.71%  |
| Haswell          | 68        | 6.21%   |
| IvyBridge        | 61        | 5.57%   |
| Penryn           | 58        | 5.3%    |
| Skylake          | 56        | 5.11%   |
| Zen 2            | 49        | 4.47%   |
| Silvermont       | 49        | 4.47%   |
| TigerLake        | 40        | 3.65%   |
| Core             | 40        | 3.65%   |
| Zen 3            | 29        | 2.65%   |
| Westmere         | 29        | 2.65%   |
| Broadwell        | 27        | 2.47%   |
| Unknown          | 23        | 2.1%    |
| Goldmont plus    | 20        | 1.83%   |
| Excavator        | 18        | 1.64%   |
| CometLake        | 18        | 1.64%   |
| Zen+             | 17        | 1.55%   |
| Icelake          | 13        | 1.19%   |
| Puma             | 11        | 1%      |
| P6               | 11        | 1%      |
| Goldmont         | 10        | 0.91%   |
| Nehalem          | 9         | 0.82%   |
| Bonnell          | 9         | 0.82%   |
| Piledriver       | 8         | 0.73%   |
| Bobcat           | 8         | 0.73%   |
| Alderlake Hybrid | 8         | 0.73%   |
| K10              | 7         | 0.64%   |
| K8 Hammer        | 6         | 0.55%   |
| Zen              | 5         | 0.46%   |
| Steamroller      | 5         | 0.46%   |
| Tremont          | 4         | 0.37%   |
| Jaguar           | 4         | 0.37%   |
| K8 & K10 hybrid  | 3         | 0.27%   |
| K10 Llano        | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 813       | 60.13%  |
| Nvidia                           | 268       | 19.82%  |
| AMD                              | 267       | 19.75%  |
| Silicon Integrated Systems [SiS] | 2         | 0.15%   |
| VIA Technologies                 | 1         | 0.07%   |
| ATI Technologies                 | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 175       | 12.42%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 57        | 4.05%   |
| AMD Renoir                                                                               | 48        | 3.41%   |
| Intel UHD Graphics 620                                                                   | 46        | 3.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 37        | 2.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 35        | 2.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 34        | 2.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 33        | 2.34%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 33        | 2.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 2.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 27        | 1.92%   |
| Intel HD Graphics 620                                                                    | 26        | 1.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 26        | 1.85%   |
| Intel HD Graphics 5500                                                                   | 24        | 1.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 1.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 22        | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 20        | 1.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 20        | 1.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 17        | 1.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 1.21%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 1.14%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 16        | 1.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 15        | 1.06%   |
| AMD Lucienne                                                                             | 15        | 1.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 14        | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 13        | 0.92%   |
| Intel HD Graphics 630                                                                    | 13        | 0.92%   |
| Intel HD Graphics 530                                                                    | 13        | 0.92%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 13        | 0.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 12        | 0.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 12        | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 0.71%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 10        | 0.71%   |
| Intel HD Graphics 500                                                                    | 10        | 0.71%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.64%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 9         | 0.64%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 8         | 0.57%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 8         | 0.57%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 8         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 572       | 52.24%  |
| Intel + Nvidia | 193       | 17.63%  |
| 1 x AMD        | 182       | 16.62%  |
| 1 x Nvidia     | 59        | 5.39%   |
| Intel + AMD    | 48        | 4.38%   |
| 2 x AMD        | 22        | 2.01%   |
| AMD + Nvidia   | 16        | 1.46%   |
| 1 x SiS        | 2         | 0.18%   |
| 1 x VIA        | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 952       | 86.39%  |
| Proprietary | 120       | 10.89%  |
| Unknown     | 30        | 2.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 731       | 65.15%  |
| 0.01-0.5   | 142       | 12.66%  |
| 1.01-2.0   | 135       | 12.03%  |
| 0.51-1.0   | 54        | 4.81%   |
| 3.01-4.0   | 39        | 3.48%   |
| 5.01-6.0   | 13        | 1.16%   |
| 2.01-3.0   | 4         | 0.36%   |
| 7.01-8.0   | 3         | 0.27%   |
| 8.01-16.0  | 1         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 229       | 17.39%  |
| LG Display              | 167       | 12.68%  |
| Chimei Innolux          | 136       | 10.33%  |
| Samsung Electronics     | 123       | 9.34%   |
| BOE                     | 120       | 9.11%   |
| CPT                     | 116       | 8.81%   |
| Dell                    | 58        | 4.4%    |
| Eizo                    | 48        | 3.64%   |
| Sharp                   | 36        | 2.73%   |
| Lenovo                  | 31        | 2.35%   |
| Chi Mei Optoelectronics | 28        | 2.13%   |
| Hewlett-Packard         | 23        | 1.75%   |
| PANDA                   | 22        | 1.67%   |
| Goldstar                | 18        | 1.37%   |
| Philips                 | 17        | 1.29%   |
| LG Philips              | 16        | 1.21%   |
| BenQ                    | 16        | 1.21%   |
| AOC                     | 13        | 0.99%   |
| Acer                    | 12        | 0.91%   |
| CSO                     | 8         | 0.61%   |
| InfoVision              | 7         | 0.53%   |
| Sony                    | 6         | 0.46%   |
| Quanta Display          | 6         | 0.46%   |
| Iiyama                  | 6         | 0.46%   |
| Panasonic               | 5         | 0.38%   |
| Apple                   | 5         | 0.38%   |
| Ancor Communications    | 5         | 0.38%   |
| Toshiba                 | 4         | 0.3%    |
| HannStar                | 4         | 0.3%    |
| ANX                     | 3         | 0.23%   |
| Vestel Elektronik       | 2         | 0.15%   |
| OEM                     | 2         | 0.15%   |
| NEC Computers           | 2         | 0.15%   |
| JDI                     | 2         | 0.15%   |
| Hitachi                 | 2         | 0.15%   |
| Fujitsu Siemens         | 2         | 0.15%   |
| DENON                   | 2         | 0.15%   |
| ViewSonic               | 1         | 0.08%   |
| Valve                   | 1         | 0.08%   |
| Unknown                 | 1         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                      | 114       | 8.43%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                         | 46        | 3.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 14        | 1.03%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 10        | 0.74%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 10        | 0.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 8         | 0.59%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 7         | 0.52%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 7         | 0.52%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 6         | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 6         | 0.44%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 6         | 0.44%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                         | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 6         | 0.44%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 5         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 5         | 0.37%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 5         | 0.37%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch               | 5         | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 5         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 5         | 0.37%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                     | 5         | 0.37%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch            | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 5         | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 4         | 0.3%    |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch      | 4         | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 4         | 0.3%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 4         | 0.3%    |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                   | 4         | 0.3%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 4         | 0.3%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 4         | 0.3%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 4         | 0.3%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 4         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1520 1680x1050 331x207mm 15.4-inch | 4         | 0.3%    |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                     | 4         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 509       | 41.28%  |
| 1366x768 (WXGA)    | 231       | 18.73%  |
| 1600x900 (HD+)     | 177       | 14.36%  |
| 3840x2160 (4K)     | 87        | 7.06%   |
| 1280x800 (WXGA)    | 60        | 4.87%   |
| 2560x1440 (QHD)    | 38        | 3.08%   |
| 1920x1200 (WUXGA)  | 28        | 2.27%   |
| 1440x900 (WXGA+)   | 15        | 1.22%   |
| 1680x1050 (WSXGA+) | 14        | 1.14%   |
| 2560x1600          | 9         | 0.73%   |
| 1280x1024 (SXGA)   | 8         | 0.65%   |
| 1024x600           | 6         | 0.49%   |
| 1024x768 (XGA)     | 5         | 0.41%   |
| 800x1280           | 4         | 0.32%   |
| 1360x768           | 4         | 0.32%   |
| 3840x2400          | 3         | 0.24%   |
| 3456x2160          | 3         | 0.24%   |
| 3000x2000          | 3         | 0.24%   |
| 2880x1800          | 3         | 0.24%   |
| 2160x1440          | 3         | 0.24%   |
| 1920x540           | 3         | 0.24%   |
| Unknown            | 3         | 0.24%   |
| 3840x1200          | 2         | 0.16%   |
| 3440x1440          | 2         | 0.16%   |
| 3200x1800 (QHD+)   | 2         | 0.16%   |
| 1400x1050          | 2         | 0.16%   |
| 8320x2160          | 1         | 0.08%   |
| 5760x2160          | 1         | 0.08%   |
| 3840x1080          | 1         | 0.08%   |
| 3072x1920          | 1         | 0.08%   |
| 2880x1620          | 1         | 0.08%   |
| 2560x1080          | 1         | 0.08%   |
| 2240x1400          | 1         | 0.08%   |
| 2160x1350          | 1         | 0.08%   |
| 1920x515           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 455       | 34.29%  |
| 13      | 259       | 19.52%  |
| 14      | 143       | 10.78%  |
| 17      | 80        | 6.03%   |
| 24      | 70        | 5.28%   |
| 31      | 58        | 4.37%   |
| 27      | 47        | 3.54%   |
| 23      | 38        | 2.86%   |
| 12      | 28        | 2.11%   |
| 11      | 28        | 2.11%   |
| 21      | 20        | 1.51%   |
| Unknown | 16        | 1.21%   |
| 16      | 10        | 0.75%   |
| 22      | 9         | 0.68%   |
| 10      | 8         | 0.6%    |
| 84      | 7         | 0.53%   |
| 18      | 7         | 0.53%   |
| 20      | 6         | 0.45%   |
| 19      | 5         | 0.38%   |
| 25      | 4         | 0.3%    |
| 54      | 3         | 0.23%   |
| 40      | 3         | 0.23%   |
| 34      | 3         | 0.23%   |
| 33      | 3         | 0.23%   |
| 32      | 3         | 0.23%   |
| 26      | 3         | 0.23%   |
| 72      | 2         | 0.15%   |
| 49      | 2         | 0.15%   |
| 43      | 2         | 0.15%   |
| 60      | 1         | 0.08%   |
| 52      | 1         | 0.08%   |
| 46      | 1         | 0.08%   |
| 38      | 1         | 0.08%   |
| 7       | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 672       | 51.53%  |
| 201-300     | 244       | 18.71%  |
| 501-600     | 141       | 10.81%  |
| 351-400     | 94        | 7.21%   |
| 601-700     | 63        | 4.83%   |
| 401-500     | 41        | 3.14%   |
| Unknown     | 16        | 1.23%   |
| 1001-1500   | 10        | 0.77%   |
| 701-800     | 9         | 0.69%   |
| 1501-2000   | 9         | 0.69%   |
| 801-900     | 4         | 0.31%   |
| 1-100       | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 917       | 82.99%  |
| 16/10   | 146       | 13.21%  |
| Unknown | 9         | 0.81%   |
| 5/4     | 8         | 0.72%   |
| 3/2     | 8         | 0.72%   |
| 4/3     | 7         | 0.63%   |
| 21/9    | 3         | 0.27%   |
| 0.62    | 3         | 0.27%   |
| 3.20    | 2         | 0.18%   |
| 3.73    | 1         | 0.09%   |
| 0.67    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 450       | 34.07%  |
| 81-90          | 228       | 17.26%  |
| 71-80          | 172       | 13.02%  |
| 201-250        | 106       | 8.02%   |
| 351-500        | 67        | 5.07%   |
| 121-130        | 62        | 4.69%   |
| 301-350        | 50        | 3.79%   |
| 61-70          | 28        | 2.12%   |
| 51-60          | 28        | 2.12%   |
| 251-300        | 28        | 2.12%   |
| Unknown        | 16        | 1.21%   |
| More than 1000 | 15        | 1.14%   |
| 151-200        | 14        | 1.06%   |
| 131-140        | 14        | 1.06%   |
| 141-150        | 10        | 0.76%   |
| 111-120        | 10        | 0.76%   |
| 41-50          | 8         | 0.61%   |
| 501-1000       | 7         | 0.53%   |
| 91-100         | 7         | 0.53%   |
| 1-40           | 1         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 616       | 49.44%  |
| 101-120       | 262       | 21.03%  |
| 51-100        | 237       | 19.02%  |
| 161-240       | 78        | 6.26%   |
| More than 240 | 26        | 2.09%   |
| Unknown       | 16        | 1.28%   |
| 1-50          | 11        | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 825       | 73.01%  |
| 2     | 235       | 20.8%   |
| 0     | 35        | 3.1%    |
| 3     | 34        | 3.01%   |
| 4     | 1         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 575       | 32.16%  |
| Realtek Semiconductor                  | 457       | 25.56%  |
| Qualcomm Atheros                       | 336       | 18.79%  |
| Samsung Electronics                    | 115       | 6.43%   |
| Broadcom                               | 97        | 5.43%   |
| Broadcom Limited                       | 41        | 2.29%   |
| MediaTek                               | 23        | 1.29%   |
| Lenovo                                 | 20        | 1.12%   |
| Marvell Technology Group               | 18        | 1.01%   |
| Dell                                   | 13        | 0.73%   |
| Ralink                                 | 11        | 0.62%   |
| ASIX Electronics                       | 11        | 0.62%   |
| TP-Link                                | 9         | 0.5%    |
| Sierra Wireless                        | 9         | 0.5%    |
| DisplayLink                            | 9         | 0.5%    |
| Ralink Technology                      | 7         | 0.39%   |
| Qualcomm Atheros Communications        | 5         | 0.28%   |
| Attansic Technology                    | 5         | 0.28%   |
| Hewlett-Packard                        | 3         | 0.17%   |
| Ericsson Business Mobile Networks      | 3         | 0.17%   |
| Spreadtrum Communications              | 2         | 0.11%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.11%   |
| Qualcomm                               | 2         | 0.11%   |
| Huawei Technologies                    | 2         | 0.11%   |
| Fibocom                                | 2         | 0.11%   |
| D-Link                                 | 2         | 0.11%   |
| Xiaomi                                 | 1         | 0.06%   |
| VIA Technologies                       | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| ICS Advent                             | 1         | 0.06%   |
| Fujitsu Siemens Computers              | 1         | 0.06%   |
| Foxconn / Hon Hai                      | 1         | 0.06%   |
| ASUSTek Computer                       | 1         | 0.06%   |
| Arduino SA                             | 1         | 0.06%   |
| AMD                                    | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 292       | 13.66%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 137       | 6.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 113       | 5.29%   |
| Intel Wi-Fi 6 AX200                                               | 69        | 3.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 2.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 56        | 2.62%   |
| Intel Wireless 8265 / 8275                                        | 47        | 2.2%    |
| Intel Wireless 7260                                               | 43        | 2.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 2.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 39        | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 34        | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 34        | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 32        | 1.5%    |
| Intel Wireless 8260                                               | 31        | 1.45%   |
| Intel Wi-Fi 6 AX201                                               | 30        | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 25        | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 24        | 1.12%   |
| Intel Wireless 3165                                               | 23        | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 23        | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 23        | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 22        | 1.03%   |
| Intel Wireless 7265                                               | 21        | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 20        | 0.94%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 18        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 17        | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 17        | 0.8%    |
| Intel WiFi Link 5100                                              | 16        | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 14        | 0.66%   |
| Intel Wireless 3160                                               | 14        | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 14        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 14        | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 0.61%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 0.61%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 13        | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 12        | 0.56%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 12        | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                     | 12        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 562       | 50.4%   |
| Qualcomm Atheros                | 299       | 26.82%  |
| Realtek Semiconductor           | 104       | 9.33%   |
| Broadcom                        | 58        | 5.2%    |
| Broadcom Limited                | 22        | 1.97%   |
| MediaTek                        | 16        | 1.43%   |
| Ralink                          | 11        | 0.99%   |
| Sierra Wireless                 | 9         | 0.81%   |
| TP-Link                         | 8         | 0.72%   |
| Ralink Technology               | 7         | 0.63%   |
| Dell                            | 7         | 0.63%   |
| Qualcomm Atheros Communications | 5         | 0.45%   |
| Fibocom                         | 2         | 0.18%   |
| Qualcomm                        | 1         | 0.09%   |
| Hewlett-Packard                 | 1         | 0.09%   |
| Fujitsu Siemens Computers       | 1         | 0.09%   |
| D-Link                          | 1         | 0.09%   |
| ASUSTek Computer                | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 137       | 12.24%  |
| Intel Wi-Fi 6 AX200                                            | 69        | 6.17%   |
| Intel Wireless 8265 / 8275                                     | 47        | 4.2%    |
| Intel Wireless 7260                                            | 43        | 3.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 39        | 3.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 34        | 3.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 34        | 3.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 32        | 2.86%   |
| Intel Wireless 8260                                            | 31        | 2.77%   |
| Intel Wi-Fi 6 AX201                                            | 30        | 2.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 25        | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 24        | 2.14%   |
| Intel Wireless 3165                                            | 23        | 2.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 23        | 2.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 22        | 1.97%   |
| Intel Wireless 7265                                            | 21        | 1.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 18        | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 17        | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 17        | 1.52%   |
| Intel WiFi Link 5100                                           | 16        | 1.43%   |
| Intel Wireless 3160                                            | 14        | 1.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 14        | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 14        | 1.25%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 12        | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 0.98%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 11        | 0.98%   |
| Intel Ultimate N WiFi Link 5300                                | 10        | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 9         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 9         | 0.8%    |
| Intel Centrino Wireless-N 2230                                 | 9         | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 8         | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8         | 0.71%   |
| Intel Wireless-AC 9260                                         | 8         | 0.71%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 8         | 0.71%   |
| Intel Centrino Advanced-N 6235                                 | 8         | 0.71%   |
| Intel Centrino Advanced-N 6200                                 | 8         | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 8         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 412       | 42%     |
| Intel                            | 234       | 23.85%  |
| Samsung Electronics              | 115       | 11.72%  |
| Qualcomm Atheros                 | 73        | 7.44%   |
| Broadcom                         | 45        | 4.59%   |
| Lenovo                           | 20        | 2.04%   |
| Broadcom Limited                 | 19        | 1.94%   |
| Marvell Technology Group         | 18        | 1.83%   |
| ASIX Electronics                 | 11        | 1.12%   |
| DisplayLink                      | 9         | 0.92%   |
| MediaTek                         | 7         | 0.71%   |
| Attansic Technology              | 5         | 0.51%   |
| Spreadtrum Communications        | 2         | 0.2%    |
| Silicon Integrated Systems [SiS] | 2         | 0.2%    |
| Xiaomi                           | 1         | 0.1%    |
| VIA Technologies                 | 1         | 0.1%    |
| TP-Link                          | 1         | 0.1%    |
| Qualcomm                         | 1         | 0.1%    |
| ICS Advent                       | 1         | 0.1%    |
| Huawei Technologies              | 1         | 0.1%    |
| Hewlett-Packard                  | 1         | 0.1%    |
| Foxconn / Hon Hai                | 1         | 0.1%    |
| D-Link                           | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 292       | 29.23%  |
| Samsung Galaxy series, misc. (tethering mode)                                  | 113       | 11.31%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 64        | 6.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 56        | 5.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 43        | 4.3%    |
| Intel Ethernet Connection (4) I219-LM                                          | 23        | 2.3%    |
| Intel 82567LM Gigabit Network Connection                                       | 18        | 1.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 14        | 1.4%    |
| Intel Ethernet Connection I219-LM                                              | 13        | 1.3%    |
| Intel Ethernet Connection I218-LM                                              | 13        | 1.3%    |
| Intel Ethernet Connection I217-LM                                              | 13        | 1.3%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 13        | 1.3%    |
| Lenovo ThinkPad TBT 3 Dock                                                     | 12        | 1.2%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 11        | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                                          | 11        | 1.1%    |
| Intel Ethernet Connection (6) I219-V                                           | 11        | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 10        | 1%      |
| Intel Ethernet Connection (4) I219-V                                           | 8         | 0.8%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 8         | 0.8%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 7         | 0.7%    |
| Intel Ethernet Connection I219-V                                               | 7         | 0.7%    |
| Intel Ethernet Connection (6) I219-LM                                          | 7         | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 0.7%    |
| Intel Ethernet Connection (10) I219-LM                                         | 7         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 6         | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 5         | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 5         | 0.5%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 5         | 0.5%    |
| Intel Ethernet Connection (11) I219-LM                                         | 5         | 0.5%    |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 5         | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 5         | 0.5%    |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 5         | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 4         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 4         | 0.4%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 4         | 0.4%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 4         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1070      | 53.1%   |
| Ethernet | 926       | 45.96%  |
| Modem    | 18        | 0.89%   |
| Unknown  | 1         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 788       | 68.17%  |
| Ethernet | 368       | 31.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 737       | 67.18%  |
| 1     | 327       | 29.81%  |
| 0     | 22        | 2.01%   |
| 3     | 11        | 1%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 957       | 86.37%  |
| Yes  | 151       | 13.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 399       | 50.06%  |
| Realtek Semiconductor           | 67        | 8.41%   |
| Qualcomm Atheros Communications | 62        | 7.78%   |
| IMC Networks                    | 58        | 7.28%   |
| Broadcom                        | 49        | 6.15%   |
| Foxconn / Hon Hai               | 36        | 4.52%   |
| Lite-On Technology              | 33        | 4.14%   |
| Hewlett-Packard                 | 25        | 3.14%   |
| Dell                            | 15        | 1.88%   |
| ASUSTek Computer                | 13        | 1.63%   |
| Ralink                          | 8         | 1%      |
| Cambridge Silicon Radio         | 5         | 0.63%   |
| Alps Electric                   | 5         | 0.63%   |
| Toshiba                         | 4         | 0.5%    |
| Realtek                         | 4         | 0.5%    |
| MediaTek                        | 4         | 0.5%    |
| Apple                           | 4         | 0.5%    |
| Ralink Technology               | 2         | 0.25%   |
| Micro Star International        | 1         | 0.13%   |
| Fujitsu Siemens Computers       | 1         | 0.13%   |
| Foxconn International           | 1         | 0.13%   |
| Askey Computer                  | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 172       | 21.58%  |
| Intel AX201 Bluetooth                                                               | 71        | 8.91%   |
| Intel AX200 Bluetooth                                                               | 69        | 8.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 46        | 5.77%   |
| Realtek Bluetooth Radio                                                             | 40        | 5.02%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 23        | 2.89%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 20        | 2.51%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 16        | 2.01%   |
| IMC Networks Bluetooth Device                                                       | 16        | 2.01%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 14        | 1.76%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 14        | 1.76%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 13        | 1.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 12        | 1.51%   |
| IMC Networks Bluetooth Radio                                                        | 12        | 1.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 10        | 1.25%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 10        | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 10        | 1.25%   |
| Broadcom BCM2045 Bluetooth                                                          | 10        | 1.25%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 9         | 1.13%   |
| IMC Networks Wireless_Device                                                        | 9         | 1.13%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 1%      |
| Dell DW375 Bluetooth Module                                                         | 8         | 1%      |
| Broadcom BCM2045B (BDC-2.1)                                                         | 8         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 0.88%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 7         | 0.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 7         | 0.88%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 7         | 0.88%   |
| Qualcomm Atheros Bluetooth                                                          | 6         | 0.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 0.75%   |
| Intel Bluetooth Device                                                              | 6         | 0.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 6         | 0.75%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 5         | 0.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 0.63%   |
| Broadcom HP Portable SoftSailing                                                    | 5         | 0.63%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 4         | 0.5%    |
| Lite-On Bluetooth Device                                                            | 4         | 0.5%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 0.5%    |
| Intel AX210 Bluetooth                                                               | 4         | 0.5%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 883       | 65.85%  |
| AMD                                  | 221       | 16.48%  |
| Nvidia                               | 115       | 8.58%   |
| Lenovo                               | 23        | 1.72%   |
| C-Media Electronics                  | 18        | 1.34%   |
| Realtek Semiconductor                | 16        | 1.19%   |
| Hewlett-Packard                      | 7         | 0.52%   |
| GN Netcom                            | 7         | 0.52%   |
| Logitech                             | 6         | 0.45%   |
| JMTek                                | 5         | 0.37%   |
| Plantronics                          | 4         | 0.3%    |
| Creative Technology                  | 4         | 0.3%    |
| Silicon Integrated Systems [SiS]     | 3         | 0.22%   |
| RODE Microphones                     | 2         | 0.15%   |
| DSEA A/S                             | 2         | 0.15%   |
| Dell                                 | 2         | 0.15%   |
| BEHRINGER International              | 2         | 0.15%   |
| Yealink Network Technology           | 1         | 0.07%   |
| VIA Technologies                     | 1         | 0.07%   |
| Trust                                | 1         | 0.07%   |
| Toshiba                              | 1         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.07%   |
| Syntek                               | 1         | 0.07%   |
| SG.Ltd                               | 1         | 0.07%   |
| Samson Technologies                  | 1         | 0.07%   |
| Razer USA                            | 1         | 0.07%   |
| Orbbec 3D Technology International   | 1         | 0.07%   |
| M-Audio                              | 1         | 0.07%   |
| Kingston Technology                  | 1         | 0.07%   |
| Harman                               | 1         | 0.07%   |
| GYROCOM C&C                          | 1         | 0.07%   |
| Generalplus Technology               | 1         | 0.07%   |
| Focusrite-Novation                   | 1         | 0.07%   |
| DigiTech                             | 1         | 0.07%   |
| Datelink Technology                  | 1         | 0.07%   |
| Conexant Systems                     | 1         | 0.07%   |
| AudioQuest                           | 1         | 0.07%   |
| Apple                                | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 174       | 10.9%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 113       | 7.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 113       | 7.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 78        | 4.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 69        | 4.32%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 53        | 3.32%   |
| Intel Cannon Lake PCH cAVS                                                                        | 41        | 2.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 40        | 2.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 38        | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 37        | 2.32%   |
| Intel 8 Series HD Audio Controller                                                                | 37        | 2.32%   |
| AMD FCH Azalia Controller                                                                         | 33        | 2.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 32        | 2.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 31        | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 31        | 1.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 29        | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 27        | 1.69%   |
| Intel Broadwell-U Audio Controller                                                                | 27        | 1.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 23        | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 20        | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 19        | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 19        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 18        | 1.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 18        | 1.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 18        | 1.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 1.07%   |
| AMD Kabini HDMI/DP Audio                                                                          | 17        | 1.07%   |
| Realtek Semiconductor USB Audio                                                                   | 16        | 1%      |
| AMD High Definition Audio Controller                                                              | 16        | 1%      |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 0.94%   |
| Intel CM238 HD Audio Controller                                                                   | 14        | 0.88%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 12        | 0.75%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 12        | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.56%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 9         | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 9         | 0.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 179       | 24.35%  |
| SK hynix             | 150       | 20.41%  |
| Elpida               | 127       | 17.28%  |
| Micron Technology    | 91        | 12.38%  |
| Kingston             | 68        | 9.25%   |
| Unknown              | 37        | 5.03%   |
| Crucial              | 20        | 2.72%   |
| Ramaxel Technology   | 18        | 2.45%   |
| Unknown (ABCD)       | 10        | 1.36%   |
| Corsair              | 10        | 1.36%   |
| A-DATA Technology    | 10        | 1.36%   |
| Nanya Technology     | 5         | 0.68%   |
| Patriot              | 3         | 0.41%   |
| Transcend            | 2         | 0.27%   |
| Unknown (AB)         | 1         | 0.14%   |
| ProMos/Mosel Vitelic | 1         | 0.14%   |
| OnBoard              | 1         | 0.14%   |
| Nayna                | 1         | 0.14%   |
| Golden Empire        | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 113       | 14.73%  |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 9         | 1.17%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 1.04%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 1.04%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 1.04%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 1.04%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 0.91%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.91%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.91%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 6         | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.78%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 6         | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.65%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 5         | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.65%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.65%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.65%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.65%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.65%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.52%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 4         | 0.52%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.52%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.52%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.52%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.52%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.52%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 4         | 0.52%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 4         | 0.52%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 2400MT/s         | 4         | 0.52%   |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s          | 4         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 274       | 42.88%  |
| DDR3    | 269       | 42.1%   |
| LPDDR4  | 40        | 6.26%   |
| DDR2    | 25        | 3.91%   |
| LPDDR3  | 17        | 2.66%   |
| SDRAM   | 8         | 1.25%   |
| DDR     | 3         | 0.47%   |
| LPDDR5  | 2         | 0.31%   |
| Unknown | 1         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 581       | 90.22%  |
| Row Of Chips | 50        | 7.76%   |
| Chip         | 10        | 1.55%   |
| DIMM         | 2         | 0.31%   |
| Unknown      | 1         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 218       | 31.92%  |
| 2048  | 174       | 25.48%  |
| 4096  | 153       | 22.4%   |
| 16384 | 107       | 15.67%  |
| 1024  | 15        | 2.2%    |
| 32768 | 11        | 1.61%   |
| 512   | 2         | 0.29%   |
| 6144  | 1         | 0.15%   |
| 3072  | 1         | 0.15%   |
| 256   | 1         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1333    | 129       | 19.08%  |
| 3200    | 120       | 17.75%  |
| 2667    | 109       | 16.12%  |
| 1600    | 107       | 15.83%  |
| 2400    | 55        | 8.14%   |
| 2133    | 27        | 3.99%   |
| 1334    | 27        | 3.99%   |
| 4267    | 16        | 2.37%   |
| Unknown | 12        | 1.78%   |
| 1867    | 10        | 1.48%   |
| 667     | 10        | 1.48%   |
| 3266    | 8         | 1.18%   |
| 1067    | 8         | 1.18%   |
| 800     | 6         | 0.89%   |
| 4266    | 4         | 0.59%   |
| 4199    | 4         | 0.59%   |
| 1066    | 4         | 0.59%   |
| 975     | 4         | 0.59%   |
| 533     | 4         | 0.59%   |
| 3733    | 3         | 0.44%   |
| 8400    | 2         | 0.3%    |
| 6400    | 2         | 0.3%    |
| 2048    | 2         | 0.3%    |
| 2933    | 1         | 0.15%   |
| 1639    | 1         | 0.15%   |
| 1400    | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Xerox               | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Prolific Technology | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Xerox Phaser 3260                | 1         | 20%     |
| Samsung M2070 Series             | 1         | 20%     |
| Prolific PL2305 Parallel Port    | 1         | 20%     |
| HP LaserJet Professional P 1102w | 1         | 20%     |
| Canon LBP3010/LBP3018/LBP3050    | 1         | 20%     |

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
| Chicony Electronics                    | 235       | 27.26%  |
| Realtek Semiconductor                  | 89        | 10.32%  |
| Acer                                   | 87        | 10.09%  |
| IMC Networks                           | 84        | 9.74%   |
| Microdia                               | 66        | 7.66%   |
| Sunplus Innovation Technology          | 55        | 6.38%   |
| Lite-On Technology                     | 39        | 4.52%   |
| Cheng Uei Precision Industry (Foxlink) | 37        | 4.29%   |
| Quanta                                 | 33        | 3.83%   |
| Suyin                                  | 31        | 3.6%    |
| Syntek                                 | 23        | 2.67%   |
| Ricoh                                  | 10        | 1.16%   |
| Lenovo                                 | 10        | 1.16%   |
| Apple                                  | 10        | 1.16%   |
| Alcor Micro                            | 10        | 1.16%   |
| Samsung Electronics                    | 6         | 0.7%    |
| Logitech                               | 5         | 0.58%   |
| Primax Electronics                     | 4         | 0.46%   |
| Luxvisions Innotech Limited            | 4         | 0.46%   |
| Sonix Technology                       | 2         | 0.23%   |
| Intel                                  | 2         | 0.23%   |
| icSpring                               | 2         | 0.23%   |
| Z-Star Microelectronics                | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |
| Sunplus Technology                     | 1         | 0.12%   |
| Silicon Motion                         | 1         | 0.12%   |
| Ruision                                | 1         | 0.12%   |
| Pixart Imaging                         | 1         | 0.12%   |
| Orbbec 3D Technology International     | 1         | 0.12%   |
| Microsoft                              | 1         | 0.12%   |
| lihappe8                               | 1         | 0.12%   |
| KYE Systems (Mouse Systems)            | 1         | 0.12%   |
| Goodong Industry                       | 1         | 0.12%   |
| Genesys Logic                          | 1         | 0.12%   |
| GEMBIRD                                | 1         | 0.12%   |
| eMPIA Technology                       | 1         | 0.12%   |
| Elecom                                 | 1         | 0.12%   |
| Creative Technology                    | 1         | 0.12%   |
| ALi                                    | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 60        | 6.93%   |
| IMC Networks Integrated Camera                | 38        | 4.39%   |
| Microdia Integrated_Webcam_HD                 | 31        | 3.58%   |
| Realtek Integrated_Webcam_HD                  | 29        | 3.35%   |
| Chicony HD Webcam                             | 25        | 2.89%   |
| Chicony HP HD Camera                          | 23        | 2.66%   |
| Acer Lenovo EasyCamera                        | 21        | 2.42%   |
| Acer Integrated Camera                        | 21        | 2.42%   |
| Lite-On HP HD Camera                          | 18        | 2.08%   |
| IMC Networks USB2.0 HD UVC WebCam             | 17        | 1.96%   |
| Sunplus Integrated_Webcam_HD                  | 13        | 1.5%    |
| Chicony Integrated Camera (1280x720@30)       | 13        | 1.5%    |
| Lite-On Integrated Camera                     | 11        | 1.27%   |
| Syntek Integrated Camera                      | 10        | 1.15%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 10        | 1.15%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 10        | 1.15%   |
| Chicony USB2.0 VGA UVC WebCam                 | 10        | 1.15%   |
| Quanta HD User Facing                         | 9         | 1.04%   |
| Realtek Integrated Webcam HD                  | 8         | 0.92%   |
| Quanta HP HD Camera                           | 8         | 0.92%   |
| Microdia Integrated Webcam                    | 8         | 0.92%   |
| Apple iPhone 5/5C/5S/6/SE                     | 8         | 0.92%   |
| Acer SunplusIT Integrated Camera              | 8         | 0.92%   |
| Syntek Lenovo EasyCamera                      | 7         | 0.81%   |
| Sunplus HD WebCam                             | 7         | 0.81%   |
| Sunplus Asus Webcam                           | 7         | 0.81%   |
| Lenovo Integrated Webcam                      | 7         | 0.81%   |
| Chicony Lenovo EasyCamera                     | 7         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 7         | 0.81%   |
| Sunplus Laptop Integrated WebCam HD           | 6         | 0.69%   |
| Samsung Galaxy A5 (MTP)                       | 6         | 0.69%   |
| Realtek USB2.0 VGA UVC WebCam                 | 6         | 0.69%   |
| Realtek USB2.0 HD UVC WebCam                  | 6         | 0.69%   |
| Realtek MTD camera                            | 6         | 0.69%   |
| Chicony HP HD Webcam                          | 6         | 0.69%   |
| Acer Lenovo Integrated Webcam                 | 6         | 0.69%   |
| Sunplus HP HD Webcam [Fixed]                  | 5         | 0.58%   |
| Realtek USB Camera                            | 5         | 0.58%   |
| Chicony TOSHIBA Web Camera - HD               | 5         | 0.58%   |
| Chicony FJ Camera                             | 5         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 84        | 33.47%  |
| Synaptics                          | 82        | 32.67%  |
| Shenzhen Goodix Technology         | 30        | 11.95%  |
| AuthenTec                          | 27        | 10.76%  |
| Upek                               | 13        | 5.18%   |
| Elan Microelectronics              | 8         | 3.19%   |
| LighTuning Technology              | 5         | 1.99%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.4%    |
| Microsoft                          | 1         | 0.4%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 10.76%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 9.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 6.77%   |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 6.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 5.58%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 5.18%   |
| Unknown                                                                    | 12        | 4.78%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 11        | 4.38%   |
| AuthenTec AES2810                                                          | 11        | 4.38%   |
| Validity Sensors VFS491                                                    | 8         | 3.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 3.19%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 3.19%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 8         | 3.19%   |
| AuthenTec AES1600                                                          | 7         | 2.79%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.39%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.39%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.99%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.99%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.99%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.99%   |
| Elan ELAN:Fingerprint                                                      | 5         | 1.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.2%    |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.2%    |
| Synaptics  WBDI                                                            | 3         | 1.2%    |
| Elan ELAN:ARM-M4                                                           | 3         | 1.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.8%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.8%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.4%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.4%    |
| Synaptics WBDI Device                                                      | 1         | 0.4%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.4%    |
| Microsoft Fingerprint Reader                                               | 1         | 0.4%    |
| LighTuning Fingerprint Sensor                                              | 1         | 0.4%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.4%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 56        | 52.83%  |
| Alcor Micro               | 30        | 28.3%   |
| O2 Micro                  | 9         | 8.49%   |
| Lenovo                    | 5         | 4.72%   |
| Upek                      | 2         | 1.89%   |
| SCM Microsystems          | 2         | 1.89%   |
| Purism, SPC               | 1         | 0.94%   |
| Aladdin Knowledge Systems | 1         | 0.94%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 30        | 28.3%   |
| Broadcom 58200                                                               | 18        | 16.98%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 13.21%  |
| Broadcom 5880                                                                | 13        | 12.26%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 10.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 7.55%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.72%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.89%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.89%   |
| Purism, SPC Librem Key                                                       | 1         | 0.94%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.94%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 651       | 58.33%  |
| 1     | 348       | 31.18%  |
| 2     | 93        | 8.33%   |
| 3     | 19        | 1.7%    |
| 4     | 3         | 0.27%   |
| 5     | 2         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 246       | 41.34%  |
| Graphics card            | 102       | 17.14%  |
| Chipcard                 | 94        | 15.8%   |
| Net/wireless             | 40        | 6.72%   |
| Multimedia controller    | 21        | 3.53%   |
| Storage                  | 18        | 3.03%   |
| Bluetooth                | 17        | 2.86%   |
| Camera                   | 15        | 2.52%   |
| Communication controller | 11        | 1.85%   |
| Card reader              | 9         | 1.51%   |
| Flash memory             | 6         | 1.01%   |
| Net/ethernet             | 5         | 0.84%   |
| Modem                    | 5         | 0.84%   |
| Sound                    | 4         | 0.67%   |
| Storage/ata              | 1         | 0.17%   |
| Network                  | 1         | 0.17%   |

